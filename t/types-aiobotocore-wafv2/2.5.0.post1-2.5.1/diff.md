# Comparing `tmp/types-aiobotocore-wafv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-wafv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-wafv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:28 2023, max compression
+gzip compressed data, was "types-aiobotocore-wafv2-2.5.1.tar", last modified: Wed Jun 28 01:44:19 2023, max compression
```

## Comparing `types-aiobotocore-wafv2-2.5.0.post1.tar` & `types-aiobotocore-wafv2-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.555705 types-aiobotocore-wafv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19066 2023-03-11 12:27:28.551705 types-aiobotocore-wafv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17503 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:28.555705 types-aiobotocore-wafv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.551705 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/
--rw-r--r--   0 runner    (1001) docker     (123)      426 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35905 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35849 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12885 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12883 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    60423 2023-03-11 12:25:30.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    60348 2023-03-11 12:25:30.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:29.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.551705 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19066 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      700 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:28.000000 types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.134230 types-aiobotocore-wafv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20053 2023-06-28 01:44:19.134230 types-aiobotocore-wafv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18496 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:19.134230 types-aiobotocore-wafv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.130230 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/
+-rw-r--r--   0 runner    (1001) docker     (123)      426 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39179 2023-06-28 01:42:23.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39118 2023-06-28 01:42:23.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13456 2023-06-28 01:42:23.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13454 2023-06-28 01:42:23.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    68396 2023-06-28 01:42:24.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68315 2023-06-28 01:42:24.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:22.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.134230 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20053 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:44:18.000000 types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/LICENSE` & `types-aiobotocore-wafv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-wafv2-2.5.1/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-wafv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WAFV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WAFV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-wafv2"></a>
 
 # types-aiobotocore-wafv2
 
 [![PyPI - types-aiobotocore-wafv2](https://img.shields.io/pypi/v/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wafv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-wafv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WAFV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
+[aiobotocore.WAFV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
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
 [types-aiobotocore-wafv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -268,14 +268,15 @@
 
 `types_aiobotocore_wafv2.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_wafv2.literals import (
     ActionValueType,
+    AssociatedResourceTypeType,
     BodyParsingFallbackBehaviorType,
     ComparisonOperatorType,
     CountryCodeType,
     FailureReasonType,
     FallbackBehaviorType,
     FilterBehaviorType,
     FilterRequirementType,
@@ -290,14 +291,15 @@
     PlatformType,
     PositionalConstraintType,
     RateBasedStatementAggregateKeyTypeType,
     ResourceTypeType,
     ResponseContentTypeType,
     ScopeType,
     SensitivityLevelType,
+    SizeInspectionLimitType,
     TextTransformationTypeType,
     WAFV2ServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -311,111 +313,132 @@
 ### Typed dictionaries
 
 `types_aiobotocore_wafv2.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_wafv2.type_defs import (
+    APIKeySummaryTypeDef,
     AWSManagedRulesBotControlRuleSetTypeDef,
     ActionConditionTypeDef,
+    AddressFieldTypeDef,
     AndStatementTypeDef,
     AssociateWebACLRequestRequestTypeDef,
+    RequestBodyAssociatedResourceTypeConfigTypeDef,
     BodyTypeDef,
     TextTransformationTypeDef,
     ImmunityTimePropertyTypeDef,
     CaptchaResponseTypeDef,
     ChallengeResponseTypeDef,
-    ResponseMetadataTypeDef,
+    CheckCapacityResponseTypeDef,
     LabelNameConditionTypeDef,
     CookieMatchPatternTypeDef,
+    CreateAPIKeyRequestRequestTypeDef,
+    CreateAPIKeyResponseTypeDef,
     TagTypeDef,
     IPSetSummaryTypeDef,
     RegexTypeDef,
     RegexPatternSetSummaryTypeDef,
     CustomResponseBodyTypeDef,
     VisibilityConfigTypeDef,
     RuleGroupSummaryTypeDef,
     WebACLSummaryTypeDef,
     CustomHTTPHeaderTypeDef,
     DeleteFirewallManagerRuleGroupsRequestRequestTypeDef,
+    DeleteFirewallManagerRuleGroupsResponseTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeletePermissionPolicyRequestRequestTypeDef,
     DeleteRegexPatternSetRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
     DeleteWebACLRequestRequestTypeDef,
+    DescribeAllManagedProductsRequestRequestTypeDef,
+    ManagedProductDescriptorTypeDef,
+    DescribeManagedProductsByVendorRequestRequestTypeDef,
     DescribeManagedRuleGroupRequestRequestTypeDef,
     LabelSummaryTypeDef,
     DisassociateWebACLRequestRequestTypeDef,
+    EmailFieldTypeDef,
     ExcludedRuleTypeDef,
+    HeaderOrderTypeDef,
     SingleHeaderTypeDef,
     SingleQueryArgumentTypeDef,
     ForwardedIPConfigTypeDef,
     GenerateMobileSdkReleaseUrlRequestRequestTypeDef,
+    GenerateMobileSdkReleaseUrlResponseTypeDef,
+    GetDecryptedAPIKeyRequestRequestTypeDef,
+    GetDecryptedAPIKeyResponseTypeDef,
     GetIPSetRequestRequestTypeDef,
     IPSetTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetManagedRuleSetRequestRequestTypeDef,
     GetMobileSdkReleaseRequestRequestTypeDef,
     GetPermissionPolicyRequestRequestTypeDef,
+    GetPermissionPolicyResponseTypeDef,
     GetRateBasedStatementManagedKeysRequestRequestTypeDef,
     RateBasedStatementManagedKeysIPSetTypeDef,
     GetRegexPatternSetRequestRequestTypeDef,
     GetRuleGroupRequestRequestTypeDef,
     TimeWindowTypeDef,
     GetWebACLForResourceRequestRequestTypeDef,
     GetWebACLRequestRequestTypeDef,
     HTTPHeaderTypeDef,
     HeaderMatchPatternTypeDef,
     IPSetForwardedIPConfigTypeDef,
     JsonMatchPatternTypeDef,
     LabelMatchStatementTypeDef,
     LabelTypeDef,
+    ListAPIKeysRequestRequestTypeDef,
     ListAvailableManagedRuleGroupVersionsRequestRequestTypeDef,
     ManagedRuleGroupVersionTypeDef,
     ListAvailableManagedRuleGroupsRequestRequestTypeDef,
     ManagedRuleGroupSummaryTypeDef,
     ListIPSetsRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListManagedRuleSetsRequestRequestTypeDef,
     ManagedRuleSetSummaryTypeDef,
     ListMobileSdkReleasesRequestRequestTypeDef,
     ReleaseSummaryTypeDef,
     ListRegexPatternSetsRequestRequestTypeDef,
     ListResourcesForWebACLRequestRequestTypeDef,
+    ListResourcesForWebACLResponseTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListWebACLsRequestRequestTypeDef,
     PasswordFieldTypeDef,
     UsernameFieldTypeDef,
     ManagedRuleSetVersionTypeDef,
     NotStatementTypeDef,
     OrStatementTypeDef,
+    PhoneNumberFieldTypeDef,
     VersionToPublishTypeDef,
+    PutManagedRuleSetVersionsResponseTypeDef,
     PutPermissionPolicyRequestRequestTypeDef,
+    RateLimitLabelNamespaceTypeDef,
     ResponseInspectionBodyContainsTypeDef,
     ResponseInspectionHeaderTypeDef,
     ResponseInspectionJsonTypeDef,
     ResponseInspectionStatusCodeTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
-    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
-    CaptchaConfigTypeDef,
-    ChallengeConfigTypeDef,
-    CheckCapacityResponseTypeDef,
-    DeleteFirewallManagerRuleGroupsResponseTypeDef,
-    GenerateMobileSdkReleaseUrlResponseTypeDef,
-    GetPermissionPolicyResponseTypeDef,
-    ListResourcesForWebACLResponseTypeDef,
-    PutManagedRuleSetVersionsResponseTypeDef,
     UpdateIPSetResponseTypeDef,
+    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
     UpdateManagedRuleSetVersionExpiryDateResponseTypeDef,
     UpdateRegexPatternSetResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     UpdateWebACLResponseTypeDef,
+    ListAPIKeysResponseTypeDef,
+    AssociationConfigTypeDef,
+    RateLimitCookieTypeDef,
+    RateLimitHeaderTypeDef,
+    RateLimitQueryArgumentTypeDef,
+    RateLimitQueryStringTypeDef,
+    CaptchaConfigTypeDef,
+    ChallengeConfigTypeDef,
     ConditionTypeDef,
     CookiesTypeDef,
     CreateIPSetRequestRequestTypeDef,
     MobileSdkReleaseTypeDef,
     TagInfoForResourceTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateIPSetResponseTypeDef,
@@ -427,44 +450,49 @@
     ListRegexPatternSetsResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     CreateWebACLResponseTypeDef,
     ListWebACLsResponseTypeDef,
     CustomRequestHandlingTypeDef,
     CustomResponseTypeDef,
+    DescribeAllManagedProductsResponseTypeDef,
+    DescribeManagedProductsByVendorResponseTypeDef,
     GeoMatchStatementTypeDef,
-    RateBasedStatementTypeDef,
     GetIPSetResponseTypeDef,
     GetRateBasedStatementManagedKeysResponseTypeDef,
     GetSampledRequestsRequestRequestTypeDef,
     HTTPRequestTypeDef,
     HeadersTypeDef,
     IPSetReferenceStatementTypeDef,
     JsonBodyTypeDef,
     ListAvailableManagedRuleGroupVersionsResponseTypeDef,
     ListAvailableManagedRuleGroupsResponseTypeDef,
     ListManagedRuleSetsResponseTypeDef,
     ListMobileSdkReleasesResponseTypeDef,
     RequestInspectionTypeDef,
     ManagedRuleSetTypeDef,
+    RequestInspectionACFPTypeDef,
     PutManagedRuleSetVersionsRequestRequestTypeDef,
     ResponseInspectionTypeDef,
+    RateBasedStatementCustomKeyTypeDef,
     FilterTypeDef,
     GetMobileSdkReleaseResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     GetRegexPatternSetResponseTypeDef,
     AllowActionTypeDef,
     CaptchaActionTypeDef,
     ChallengeActionTypeDef,
     CountActionTypeDef,
     BlockActionTypeDef,
     SampledHTTPRequestTypeDef,
     FieldToMatchTypeDef,
     GetManagedRuleSetResponseTypeDef,
+    AWSManagedRulesACFPRuleSetTypeDef,
     AWSManagedRulesATPRuleSetTypeDef,
+    RateBasedStatementTypeDef,
     LoggingFilterTypeDef,
     OverrideActionTypeDef,
     DefaultActionTypeDef,
     RuleActionTypeDef,
     GetSampledRequestsResponseTypeDef,
     ByteMatchStatementTypeDef,
     RegexMatchStatementTypeDef,
@@ -496,54 +524,54 @@
     FirewallManagerRuleGroupTypeDef,
     WebACLTypeDef,
     GetWebACLForResourceResponseTypeDef,
     GetWebACLResponseTypeDef,
 )
 
 
-def get_structure() -> AWSManagedRulesBotControlRuleSetTypeDef:
+def get_structure() -> APIKeySummaryTypeDef:
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/README.md` & `types-aiobotocore-wafv2-2.5.1/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-wafv2"></a>
 
 # types-aiobotocore-wafv2
 
 [![PyPI - types-aiobotocore-wafv2](https://img.shields.io/pypi/v/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wafv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-wafv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WAFV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
+[aiobotocore.WAFV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
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
 [types-aiobotocore-wafv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -235,14 +235,15 @@
 
 `types_aiobotocore_wafv2.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_wafv2.literals import (
     ActionValueType,
+    AssociatedResourceTypeType,
     BodyParsingFallbackBehaviorType,
     ComparisonOperatorType,
     CountryCodeType,
     FailureReasonType,
     FallbackBehaviorType,
     FilterBehaviorType,
     FilterRequirementType,
@@ -257,14 +258,15 @@
     PlatformType,
     PositionalConstraintType,
     RateBasedStatementAggregateKeyTypeType,
     ResourceTypeType,
     ResponseContentTypeType,
     ScopeType,
     SensitivityLevelType,
+    SizeInspectionLimitType,
     TextTransformationTypeType,
     WAFV2ServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -278,111 +280,132 @@
 ### Typed dictionaries
 
 `types_aiobotocore_wafv2.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_wafv2.type_defs import (
+    APIKeySummaryTypeDef,
     AWSManagedRulesBotControlRuleSetTypeDef,
     ActionConditionTypeDef,
+    AddressFieldTypeDef,
     AndStatementTypeDef,
     AssociateWebACLRequestRequestTypeDef,
+    RequestBodyAssociatedResourceTypeConfigTypeDef,
     BodyTypeDef,
     TextTransformationTypeDef,
     ImmunityTimePropertyTypeDef,
     CaptchaResponseTypeDef,
     ChallengeResponseTypeDef,
-    ResponseMetadataTypeDef,
+    CheckCapacityResponseTypeDef,
     LabelNameConditionTypeDef,
     CookieMatchPatternTypeDef,
+    CreateAPIKeyRequestRequestTypeDef,
+    CreateAPIKeyResponseTypeDef,
     TagTypeDef,
     IPSetSummaryTypeDef,
     RegexTypeDef,
     RegexPatternSetSummaryTypeDef,
     CustomResponseBodyTypeDef,
     VisibilityConfigTypeDef,
     RuleGroupSummaryTypeDef,
     WebACLSummaryTypeDef,
     CustomHTTPHeaderTypeDef,
     DeleteFirewallManagerRuleGroupsRequestRequestTypeDef,
+    DeleteFirewallManagerRuleGroupsResponseTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeletePermissionPolicyRequestRequestTypeDef,
     DeleteRegexPatternSetRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
     DeleteWebACLRequestRequestTypeDef,
+    DescribeAllManagedProductsRequestRequestTypeDef,
+    ManagedProductDescriptorTypeDef,
+    DescribeManagedProductsByVendorRequestRequestTypeDef,
     DescribeManagedRuleGroupRequestRequestTypeDef,
     LabelSummaryTypeDef,
     DisassociateWebACLRequestRequestTypeDef,
+    EmailFieldTypeDef,
     ExcludedRuleTypeDef,
+    HeaderOrderTypeDef,
     SingleHeaderTypeDef,
     SingleQueryArgumentTypeDef,
     ForwardedIPConfigTypeDef,
     GenerateMobileSdkReleaseUrlRequestRequestTypeDef,
+    GenerateMobileSdkReleaseUrlResponseTypeDef,
+    GetDecryptedAPIKeyRequestRequestTypeDef,
+    GetDecryptedAPIKeyResponseTypeDef,
     GetIPSetRequestRequestTypeDef,
     IPSetTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetManagedRuleSetRequestRequestTypeDef,
     GetMobileSdkReleaseRequestRequestTypeDef,
     GetPermissionPolicyRequestRequestTypeDef,
+    GetPermissionPolicyResponseTypeDef,
     GetRateBasedStatementManagedKeysRequestRequestTypeDef,
     RateBasedStatementManagedKeysIPSetTypeDef,
     GetRegexPatternSetRequestRequestTypeDef,
     GetRuleGroupRequestRequestTypeDef,
     TimeWindowTypeDef,
     GetWebACLForResourceRequestRequestTypeDef,
     GetWebACLRequestRequestTypeDef,
     HTTPHeaderTypeDef,
     HeaderMatchPatternTypeDef,
     IPSetForwardedIPConfigTypeDef,
     JsonMatchPatternTypeDef,
     LabelMatchStatementTypeDef,
     LabelTypeDef,
+    ListAPIKeysRequestRequestTypeDef,
     ListAvailableManagedRuleGroupVersionsRequestRequestTypeDef,
     ManagedRuleGroupVersionTypeDef,
     ListAvailableManagedRuleGroupsRequestRequestTypeDef,
     ManagedRuleGroupSummaryTypeDef,
     ListIPSetsRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListManagedRuleSetsRequestRequestTypeDef,
     ManagedRuleSetSummaryTypeDef,
     ListMobileSdkReleasesRequestRequestTypeDef,
     ReleaseSummaryTypeDef,
     ListRegexPatternSetsRequestRequestTypeDef,
     ListResourcesForWebACLRequestRequestTypeDef,
+    ListResourcesForWebACLResponseTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListWebACLsRequestRequestTypeDef,
     PasswordFieldTypeDef,
     UsernameFieldTypeDef,
     ManagedRuleSetVersionTypeDef,
     NotStatementTypeDef,
     OrStatementTypeDef,
+    PhoneNumberFieldTypeDef,
     VersionToPublishTypeDef,
+    PutManagedRuleSetVersionsResponseTypeDef,
     PutPermissionPolicyRequestRequestTypeDef,
+    RateLimitLabelNamespaceTypeDef,
     ResponseInspectionBodyContainsTypeDef,
     ResponseInspectionHeaderTypeDef,
     ResponseInspectionJsonTypeDef,
     ResponseInspectionStatusCodeTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
-    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
-    CaptchaConfigTypeDef,
-    ChallengeConfigTypeDef,
-    CheckCapacityResponseTypeDef,
-    DeleteFirewallManagerRuleGroupsResponseTypeDef,
-    GenerateMobileSdkReleaseUrlResponseTypeDef,
-    GetPermissionPolicyResponseTypeDef,
-    ListResourcesForWebACLResponseTypeDef,
-    PutManagedRuleSetVersionsResponseTypeDef,
     UpdateIPSetResponseTypeDef,
+    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
     UpdateManagedRuleSetVersionExpiryDateResponseTypeDef,
     UpdateRegexPatternSetResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     UpdateWebACLResponseTypeDef,
+    ListAPIKeysResponseTypeDef,
+    AssociationConfigTypeDef,
+    RateLimitCookieTypeDef,
+    RateLimitHeaderTypeDef,
+    RateLimitQueryArgumentTypeDef,
+    RateLimitQueryStringTypeDef,
+    CaptchaConfigTypeDef,
+    ChallengeConfigTypeDef,
     ConditionTypeDef,
     CookiesTypeDef,
     CreateIPSetRequestRequestTypeDef,
     MobileSdkReleaseTypeDef,
     TagInfoForResourceTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateIPSetResponseTypeDef,
@@ -394,44 +417,49 @@
     ListRegexPatternSetsResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     CreateWebACLResponseTypeDef,
     ListWebACLsResponseTypeDef,
     CustomRequestHandlingTypeDef,
     CustomResponseTypeDef,
+    DescribeAllManagedProductsResponseTypeDef,
+    DescribeManagedProductsByVendorResponseTypeDef,
     GeoMatchStatementTypeDef,
-    RateBasedStatementTypeDef,
     GetIPSetResponseTypeDef,
     GetRateBasedStatementManagedKeysResponseTypeDef,
     GetSampledRequestsRequestRequestTypeDef,
     HTTPRequestTypeDef,
     HeadersTypeDef,
     IPSetReferenceStatementTypeDef,
     JsonBodyTypeDef,
     ListAvailableManagedRuleGroupVersionsResponseTypeDef,
     ListAvailableManagedRuleGroupsResponseTypeDef,
     ListManagedRuleSetsResponseTypeDef,
     ListMobileSdkReleasesResponseTypeDef,
     RequestInspectionTypeDef,
     ManagedRuleSetTypeDef,
+    RequestInspectionACFPTypeDef,
     PutManagedRuleSetVersionsRequestRequestTypeDef,
     ResponseInspectionTypeDef,
+    RateBasedStatementCustomKeyTypeDef,
     FilterTypeDef,
     GetMobileSdkReleaseResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     GetRegexPatternSetResponseTypeDef,
     AllowActionTypeDef,
     CaptchaActionTypeDef,
     ChallengeActionTypeDef,
     CountActionTypeDef,
     BlockActionTypeDef,
     SampledHTTPRequestTypeDef,
     FieldToMatchTypeDef,
     GetManagedRuleSetResponseTypeDef,
+    AWSManagedRulesACFPRuleSetTypeDef,
     AWSManagedRulesATPRuleSetTypeDef,
+    RateBasedStatementTypeDef,
     LoggingFilterTypeDef,
     OverrideActionTypeDef,
     DefaultActionTypeDef,
     RuleActionTypeDef,
     GetSampledRequestsResponseTypeDef,
     ByteMatchStatementTypeDef,
     RegexMatchStatementTypeDef,
@@ -463,54 +491,54 @@
     FirewallManagerRuleGroupTypeDef,
     WebACLTypeDef,
     GetWebACLForResourceResponseTypeDef,
     GetWebACLResponseTypeDef,
 )
 
 
-def get_structure() -> AWSManagedRulesBotControlRuleSetTypeDef:
+def get_structure() -> APIKeySummaryTypeDef:
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/setup.py` & `types-aiobotocore-wafv2-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-wafv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-wafv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_wafv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WAFV2 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.WAFV2 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/"
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/__main__.py` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WAFV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WAFV2 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2\nOther"
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/client.py` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,37 +18,43 @@
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import IPAddressVersionType, PlatformType, ResourceTypeType, ScopeType
 from .type_defs import (
+    AssociationConfigTypeDef,
     CaptchaConfigTypeDef,
     ChallengeConfigTypeDef,
     CheckCapacityResponseTypeDef,
+    CreateAPIKeyResponseTypeDef,
     CreateIPSetResponseTypeDef,
     CreateRegexPatternSetResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     CreateWebACLResponseTypeDef,
     CustomResponseBodyTypeDef,
     DefaultActionTypeDef,
     DeleteFirewallManagerRuleGroupsResponseTypeDef,
+    DescribeAllManagedProductsResponseTypeDef,
+    DescribeManagedProductsByVendorResponseTypeDef,
     DescribeManagedRuleGroupResponseTypeDef,
     GenerateMobileSdkReleaseUrlResponseTypeDef,
+    GetDecryptedAPIKeyResponseTypeDef,
     GetIPSetResponseTypeDef,
     GetLoggingConfigurationResponseTypeDef,
     GetManagedRuleSetResponseTypeDef,
     GetMobileSdkReleaseResponseTypeDef,
     GetPermissionPolicyResponseTypeDef,
     GetRateBasedStatementManagedKeysResponseTypeDef,
     GetRegexPatternSetResponseTypeDef,
     GetRuleGroupResponseTypeDef,
     GetSampledRequestsResponseTypeDef,
     GetWebACLForResourceResponseTypeDef,
     GetWebACLResponseTypeDef,
+    ListAPIKeysResponseTypeDef,
     ListAvailableManagedRuleGroupsResponseTypeDef,
     ListAvailableManagedRuleGroupVersionsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListLoggingConfigurationsResponseTypeDef,
     ListManagedRuleSetsResponseTypeDef,
     ListMobileSdkReleasesResponseTypeDef,
     ListRegexPatternSetsResponseTypeDef,
@@ -99,14 +105,15 @@
     WAFNonexistentItemException: Type[BotocoreClientError]
     WAFOptimisticLockException: Type[BotocoreClientError]
     WAFServiceLinkedRoleErrorException: Type[BotocoreClientError]
     WAFSubscriptionNotFoundException: Type[BotocoreClientError]
     WAFTagOperationException: Type[BotocoreClientError]
     WAFTagOperationInternalErrorException: Type[BotocoreClientError]
     WAFUnavailableEntityException: Type[BotocoreClientError]
+    WAFUnsupportedAggregateKeyTypeException: Type[BotocoreClientError]
 
 
 class WAFV2Client(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/)
     """
@@ -154,14 +161,24 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#close)
         """
 
+    async def create_api_key(
+        self, *, Scope: ScopeType, TokenDomains: Sequence[str]
+    ) -> CreateAPIKeyResponseTypeDef:
+        """
+        Creates an API key that contains a set of token domains.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.create_api_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#create_api_key)
+        """
+
     async def create_ip_set(
         self,
         *,
         Name: str,
         Scope: ScopeType,
         IPAddressVersion: IPAddressVersionType,
         Addresses: Sequence[str],
@@ -222,15 +239,16 @@
         VisibilityConfig: VisibilityConfigTypeDef,
         Description: str = ...,
         Rules: Sequence[RuleTypeDef] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         CustomResponseBodies: Mapping[str, CustomResponseBodyTypeDef] = ...,
         CaptchaConfig: CaptchaConfigTypeDef = ...,
         ChallengeConfig: ChallengeConfigTypeDef = ...,
-        TokenDomains: Sequence[str] = ...
+        TokenDomains: Sequence[str] = ...,
+        AssociationConfig: AssociationConfigTypeDef = ...
     ) -> CreateWebACLResponseTypeDef:
         """
         Creates a  WebACL per the specifications provided.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.create_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#create_web_acl)
         """
@@ -298,14 +316,36 @@
         """
         Deletes the specified  WebACL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.delete_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#delete_web_acl)
         """
 
+    async def describe_all_managed_products(
+        self, *, Scope: ScopeType
+    ) -> DescribeAllManagedProductsResponseTypeDef:
+        """
+        Provides high-level information for the Amazon Web Services Managed Rules rule
+        groups and Amazon Web Services Marketplace managed rule groups.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.describe_all_managed_products)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#describe_all_managed_products)
+        """
+
+    async def describe_managed_products_by_vendor(
+        self, *, VendorName: str, Scope: ScopeType
+    ) -> DescribeManagedProductsByVendorResponseTypeDef:
+        """
+        Provides high-level information for the managed rule groups owned by a specific
+        vendor.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.describe_managed_products_by_vendor)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#describe_managed_products_by_vendor)
+        """
+
     async def describe_managed_rule_group(
         self, *, VendorName: str, Name: str, Scope: ScopeType, VersionName: str = ...
     ) -> DescribeManagedRuleGroupResponseTypeDef:
         """
         Provides high-level information for a managed rule group, including descriptions
         of the rules.
 
@@ -342,14 +382,24 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#generate_presigned_url)
         """
 
+    async def get_decrypted_api_key(
+        self, *, Scope: ScopeType, APIKey: str
+    ) -> GetDecryptedAPIKeyResponseTypeDef:
+        """
+        Returns your API key in decrypted form.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_decrypted_api_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_decrypted_api_key)
+        """
+
     async def get_ip_set(self, *, Name: str, Scope: ScopeType, Id: str) -> GetIPSetResponseTypeDef:
         """
         Retrieves the specified  IPSet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_ip_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_ip_set)
         """
@@ -401,15 +451,16 @@
         Scope: ScopeType,
         WebACLName: str,
         WebACLId: str,
         RuleName: str,
         RuleGroupRuleName: str = ...
     ) -> GetRateBasedStatementManagedKeysResponseTypeDef:
         """
-        Retrieves the keys that are currently blocked by a rate-based rule instance.
+        Retrieves the IP addresses that are currently blocked by a rate-based rule
+        instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_rate_based_statement_managed_keys)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_rate_based_statement_managed_keys)
         """
 
     async def get_regex_pattern_set(
         self, *, Name: str, Scope: ScopeType, Id: str
@@ -465,14 +516,24 @@
         """
         Retrieves the  WebACL for the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_web_acl_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_web_acl_for_resource)
         """
 
+    async def list_api_keys(
+        self, *, Scope: ScopeType, NextMarker: str = ..., Limit: int = ...
+    ) -> ListAPIKeysResponseTypeDef:
+        """
+        Retrieves a list of the API keys that you've defined for the specified scope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.list_api_keys)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#list_api_keys)
+        """
+
     async def list_available_managed_rule_group_versions(
         self,
         *,
         VendorName: str,
         Name: str,
         Scope: ScopeType,
         NextMarker: str = ...,
@@ -722,15 +783,16 @@
         VisibilityConfig: VisibilityConfigTypeDef,
         LockToken: str,
         Description: str = ...,
         Rules: Sequence[RuleTypeDef] = ...,
         CustomResponseBodies: Mapping[str, CustomResponseBodyTypeDef] = ...,
         CaptchaConfig: CaptchaConfigTypeDef = ...,
         ChallengeConfig: ChallengeConfigTypeDef = ...,
-        TokenDomains: Sequence[str] = ...
+        TokenDomains: Sequence[str] = ...,
+        AssociationConfig: AssociationConfigTypeDef = ...
     ) -> UpdateWebACLResponseTypeDef:
         """
         Updates the specified  WebACL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.update_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#update_web_acl)
         """
```

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/client.pyi` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,37 +18,43 @@
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import IPAddressVersionType, PlatformType, ResourceTypeType, ScopeType
 from .type_defs import (
+    AssociationConfigTypeDef,
     CaptchaConfigTypeDef,
     ChallengeConfigTypeDef,
     CheckCapacityResponseTypeDef,
+    CreateAPIKeyResponseTypeDef,
     CreateIPSetResponseTypeDef,
     CreateRegexPatternSetResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     CreateWebACLResponseTypeDef,
     CustomResponseBodyTypeDef,
     DefaultActionTypeDef,
     DeleteFirewallManagerRuleGroupsResponseTypeDef,
+    DescribeAllManagedProductsResponseTypeDef,
+    DescribeManagedProductsByVendorResponseTypeDef,
     DescribeManagedRuleGroupResponseTypeDef,
     GenerateMobileSdkReleaseUrlResponseTypeDef,
+    GetDecryptedAPIKeyResponseTypeDef,
     GetIPSetResponseTypeDef,
     GetLoggingConfigurationResponseTypeDef,
     GetManagedRuleSetResponseTypeDef,
     GetMobileSdkReleaseResponseTypeDef,
     GetPermissionPolicyResponseTypeDef,
     GetRateBasedStatementManagedKeysResponseTypeDef,
     GetRegexPatternSetResponseTypeDef,
     GetRuleGroupResponseTypeDef,
     GetSampledRequestsResponseTypeDef,
     GetWebACLForResourceResponseTypeDef,
     GetWebACLResponseTypeDef,
+    ListAPIKeysResponseTypeDef,
     ListAvailableManagedRuleGroupsResponseTypeDef,
     ListAvailableManagedRuleGroupVersionsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListLoggingConfigurationsResponseTypeDef,
     ListManagedRuleSetsResponseTypeDef,
     ListMobileSdkReleasesResponseTypeDef,
     ListRegexPatternSetsResponseTypeDef,
@@ -97,14 +103,15 @@
     WAFNonexistentItemException: Type[BotocoreClientError]
     WAFOptimisticLockException: Type[BotocoreClientError]
     WAFServiceLinkedRoleErrorException: Type[BotocoreClientError]
     WAFSubscriptionNotFoundException: Type[BotocoreClientError]
     WAFTagOperationException: Type[BotocoreClientError]
     WAFTagOperationInternalErrorException: Type[BotocoreClientError]
     WAFUnavailableEntityException: Type[BotocoreClientError]
+    WAFUnsupportedAggregateKeyTypeException: Type[BotocoreClientError]
 
 class WAFV2Client(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/)
     """
 
@@ -146,14 +153,23 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#close)
         """
+    async def create_api_key(
+        self, *, Scope: ScopeType, TokenDomains: Sequence[str]
+    ) -> CreateAPIKeyResponseTypeDef:
+        """
+        Creates an API key that contains a set of token domains.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.create_api_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#create_api_key)
+        """
     async def create_ip_set(
         self,
         *,
         Name: str,
         Scope: ScopeType,
         IPAddressVersion: IPAddressVersionType,
         Addresses: Sequence[str],
@@ -211,15 +227,16 @@
         VisibilityConfig: VisibilityConfigTypeDef,
         Description: str = ...,
         Rules: Sequence[RuleTypeDef] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         CustomResponseBodies: Mapping[str, CustomResponseBodyTypeDef] = ...,
         CaptchaConfig: CaptchaConfigTypeDef = ...,
         ChallengeConfig: ChallengeConfigTypeDef = ...,
-        TokenDomains: Sequence[str] = ...
+        TokenDomains: Sequence[str] = ...,
+        AssociationConfig: AssociationConfigTypeDef = ...
     ) -> CreateWebACLResponseTypeDef:
         """
         Creates a  WebACL per the specifications provided.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.create_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#create_web_acl)
         """
@@ -279,14 +296,34 @@
     ) -> Dict[str, Any]:
         """
         Deletes the specified  WebACL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.delete_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#delete_web_acl)
         """
+    async def describe_all_managed_products(
+        self, *, Scope: ScopeType
+    ) -> DescribeAllManagedProductsResponseTypeDef:
+        """
+        Provides high-level information for the Amazon Web Services Managed Rules rule
+        groups and Amazon Web Services Marketplace managed rule groups.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.describe_all_managed_products)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#describe_all_managed_products)
+        """
+    async def describe_managed_products_by_vendor(
+        self, *, VendorName: str, Scope: ScopeType
+    ) -> DescribeManagedProductsByVendorResponseTypeDef:
+        """
+        Provides high-level information for the managed rule groups owned by a specific
+        vendor.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.describe_managed_products_by_vendor)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#describe_managed_products_by_vendor)
+        """
     async def describe_managed_rule_group(
         self, *, VendorName: str, Name: str, Scope: ScopeType, VersionName: str = ...
     ) -> DescribeManagedRuleGroupResponseTypeDef:
         """
         Provides high-level information for a managed rule group, including descriptions
         of the rules.
 
@@ -319,14 +356,23 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#generate_presigned_url)
         """
+    async def get_decrypted_api_key(
+        self, *, Scope: ScopeType, APIKey: str
+    ) -> GetDecryptedAPIKeyResponseTypeDef:
+        """
+        Returns your API key in decrypted form.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_decrypted_api_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_decrypted_api_key)
+        """
     async def get_ip_set(self, *, Name: str, Scope: ScopeType, Id: str) -> GetIPSetResponseTypeDef:
         """
         Retrieves the specified  IPSet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_ip_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_ip_set)
         """
@@ -373,15 +419,16 @@
         Scope: ScopeType,
         WebACLName: str,
         WebACLId: str,
         RuleName: str,
         RuleGroupRuleName: str = ...
     ) -> GetRateBasedStatementManagedKeysResponseTypeDef:
         """
-        Retrieves the keys that are currently blocked by a rate-based rule instance.
+        Retrieves the IP addresses that are currently blocked by a rate-based rule
+        instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_rate_based_statement_managed_keys)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_rate_based_statement_managed_keys)
         """
     async def get_regex_pattern_set(
         self, *, Name: str, Scope: ScopeType, Id: str
     ) -> GetRegexPatternSetResponseTypeDef:
@@ -431,14 +478,23 @@
     ) -> GetWebACLForResourceResponseTypeDef:
         """
         Retrieves the  WebACL for the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.get_web_acl_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#get_web_acl_for_resource)
         """
+    async def list_api_keys(
+        self, *, Scope: ScopeType, NextMarker: str = ..., Limit: int = ...
+    ) -> ListAPIKeysResponseTypeDef:
+        """
+        Retrieves a list of the API keys that you've defined for the specified scope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.list_api_keys)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#list_api_keys)
+        """
     async def list_available_managed_rule_group_versions(
         self,
         *,
         VendorName: str,
         Name: str,
         Scope: ScopeType,
         NextMarker: str = ...,
@@ -668,15 +724,16 @@
         VisibilityConfig: VisibilityConfigTypeDef,
         LockToken: str,
         Description: str = ...,
         Rules: Sequence[RuleTypeDef] = ...,
         CustomResponseBodies: Mapping[str, CustomResponseBodyTypeDef] = ...,
         CaptchaConfig: CaptchaConfigTypeDef = ...,
         ChallengeConfig: ChallengeConfigTypeDef = ...,
-        TokenDomains: Sequence[str] = ...
+        TokenDomains: Sequence[str] = ...,
+        AssociationConfig: AssociationConfigTypeDef = ...
     ) -> UpdateWebACLResponseTypeDef:
         """
         Updates the specified  WebACL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2.Client.update_web_acl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/client/#update_web_acl)
         """
```

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/literals.py` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,14 +17,15 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "ActionValueType",
+    "AssociatedResourceTypeType",
     "BodyParsingFallbackBehaviorType",
     "ComparisonOperatorType",
     "CountryCodeType",
     "FailureReasonType",
     "FallbackBehaviorType",
     "FilterBehaviorType",
     "FilterRequirementType",
@@ -39,23 +40,25 @@
     "PlatformType",
     "PositionalConstraintType",
     "RateBasedStatementAggregateKeyTypeType",
     "ResourceTypeType",
     "ResponseContentTypeType",
     "ScopeType",
     "SensitivityLevelType",
+    "SizeInspectionLimitType",
     "TextTransformationTypeType",
     "WAFV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
 ActionValueType = Literal["ALLOW", "BLOCK", "CAPTCHA", "CHALLENGE", "COUNT", "EXCLUDED_AS_COUNT"]
+AssociatedResourceTypeType = Literal["CLOUDFRONT"]
 BodyParsingFallbackBehaviorType = Literal["EVALUATE_AS_STRING", "MATCH", "NO_MATCH"]
 ComparisonOperatorType = Literal["EQ", "GE", "GT", "LE", "LT", "NE"]
 CountryCodeType = Literal[
     "AD",
     "AE",
     "AF",
     "AG",
@@ -320,21 +323,27 @@
 MapMatchScopeType = Literal["ALL", "KEY", "VALUE"]
 OversizeHandlingType = Literal["CONTINUE", "MATCH", "NO_MATCH"]
 PayloadTypeType = Literal["FORM_ENCODED", "JSON"]
 PlatformType = Literal["ANDROID", "IOS"]
 PositionalConstraintType = Literal[
     "CONTAINS", "CONTAINS_WORD", "ENDS_WITH", "EXACTLY", "STARTS_WITH"
 ]
-RateBasedStatementAggregateKeyTypeType = Literal["FORWARDED_IP", "IP"]
+RateBasedStatementAggregateKeyTypeType = Literal["CONSTANT", "CUSTOM_KEYS", "FORWARDED_IP", "IP"]
 ResourceTypeType = Literal[
-    "API_GATEWAY", "APPLICATION_LOAD_BALANCER", "APPSYNC", "COGNITO_USER_POOL"
+    "API_GATEWAY",
+    "APPLICATION_LOAD_BALANCER",
+    "APPSYNC",
+    "APP_RUNNER_SERVICE",
+    "COGNITO_USER_POOL",
+    "VERIFIED_ACCESS_INSTANCE",
 ]
 ResponseContentTypeType = Literal["APPLICATION_JSON", "TEXT_HTML", "TEXT_PLAIN"]
 ScopeType = Literal["CLOUDFRONT", "REGIONAL"]
 SensitivityLevelType = Literal["HIGH", "LOW"]
+SizeInspectionLimitType = Literal["KB_16", "KB_32", "KB_48", "KB_64"]
 TextTransformationTypeType = Literal[
     "BASE64_DECODE",
     "BASE64_DECODE_EXT",
     "CMD_LINE",
     "COMPRESS_WHITE_SPACE",
     "CSS_DECODE",
     "ESCAPE_SEQ_DECODE",
@@ -413,14 +422,15 @@
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
@@ -499,14 +509,15 @@
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
@@ -517,14 +528,15 @@
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
@@ -560,14 +572,15 @@
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
@@ -586,16 +599,19 @@
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
@@ -679,15 +695,17 @@
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
@@ -712,21 +730,25 @@
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/literals.pyi` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,14 +16,15 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ActionValueType",
+    "AssociatedResourceTypeType",
     "BodyParsingFallbackBehaviorType",
     "ComparisonOperatorType",
     "CountryCodeType",
     "FailureReasonType",
     "FallbackBehaviorType",
     "FilterBehaviorType",
     "FilterRequirementType",
@@ -38,22 +39,24 @@
     "PlatformType",
     "PositionalConstraintType",
     "RateBasedStatementAggregateKeyTypeType",
     "ResourceTypeType",
     "ResponseContentTypeType",
     "ScopeType",
     "SensitivityLevelType",
+    "SizeInspectionLimitType",
     "TextTransformationTypeType",
     "WAFV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 ActionValueType = Literal["ALLOW", "BLOCK", "CAPTCHA", "CHALLENGE", "COUNT", "EXCLUDED_AS_COUNT"]
+AssociatedResourceTypeType = Literal["CLOUDFRONT"]
 BodyParsingFallbackBehaviorType = Literal["EVALUATE_AS_STRING", "MATCH", "NO_MATCH"]
 ComparisonOperatorType = Literal["EQ", "GE", "GT", "LE", "LT", "NE"]
 CountryCodeType = Literal[
     "AD",
     "AE",
     "AF",
     "AG",
@@ -318,21 +321,27 @@
 MapMatchScopeType = Literal["ALL", "KEY", "VALUE"]
 OversizeHandlingType = Literal["CONTINUE", "MATCH", "NO_MATCH"]
 PayloadTypeType = Literal["FORM_ENCODED", "JSON"]
 PlatformType = Literal["ANDROID", "IOS"]
 PositionalConstraintType = Literal[
     "CONTAINS", "CONTAINS_WORD", "ENDS_WITH", "EXACTLY", "STARTS_WITH"
 ]
-RateBasedStatementAggregateKeyTypeType = Literal["FORWARDED_IP", "IP"]
+RateBasedStatementAggregateKeyTypeType = Literal["CONSTANT", "CUSTOM_KEYS", "FORWARDED_IP", "IP"]
 ResourceTypeType = Literal[
-    "API_GATEWAY", "APPLICATION_LOAD_BALANCER", "APPSYNC", "COGNITO_USER_POOL"
+    "API_GATEWAY",
+    "APPLICATION_LOAD_BALANCER",
+    "APPSYNC",
+    "APP_RUNNER_SERVICE",
+    "COGNITO_USER_POOL",
+    "VERIFIED_ACCESS_INSTANCE",
 ]
 ResponseContentTypeType = Literal["APPLICATION_JSON", "TEXT_HTML", "TEXT_PLAIN"]
 ScopeType = Literal["CLOUDFRONT", "REGIONAL"]
 SensitivityLevelType = Literal["HIGH", "LOW"]
+SizeInspectionLimitType = Literal["KB_16", "KB_32", "KB_48", "KB_64"]
 TextTransformationTypeType = Literal[
     "BASE64_DECODE",
     "BASE64_DECODE_EXT",
     "CMD_LINE",
     "COMPRESS_WHITE_SPACE",
     "CSS_DECODE",
     "ESCAPE_SEQ_DECODE",
@@ -411,14 +420,15 @@
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
@@ -497,14 +507,15 @@
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
@@ -515,14 +526,15 @@
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
@@ -558,14 +570,15 @@
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
@@ -584,16 +597,19 @@
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
@@ -677,15 +693,17 @@
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
@@ -710,21 +728,25 @@
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/type_defs.py` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for wafv2 service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_wafv2.type_defs import AWSManagedRulesBotControlRuleSetTypeDef
+    from types_aiobotocore_wafv2.type_defs import APIKeySummaryTypeDef
 
-    data: AWSManagedRulesBotControlRuleSetTypeDef = {...}
+    data: APIKeySummaryTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -37,121 +37,147 @@
     PlatformType,
     PositionalConstraintType,
     RateBasedStatementAggregateKeyTypeType,
     ResourceTypeType,
     ResponseContentTypeType,
     ScopeType,
     SensitivityLevelType,
+    SizeInspectionLimitType,
     TextTransformationTypeType,
 )
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
+    "APIKeySummaryTypeDef",
     "AWSManagedRulesBotControlRuleSetTypeDef",
     "ActionConditionTypeDef",
+    "AddressFieldTypeDef",
     "AndStatementTypeDef",
     "AssociateWebACLRequestRequestTypeDef",
+    "RequestBodyAssociatedResourceTypeConfigTypeDef",
     "BodyTypeDef",
     "TextTransformationTypeDef",
     "ImmunityTimePropertyTypeDef",
     "CaptchaResponseTypeDef",
     "ChallengeResponseTypeDef",
-    "ResponseMetadataTypeDef",
+    "CheckCapacityResponseTypeDef",
     "LabelNameConditionTypeDef",
     "CookieMatchPatternTypeDef",
+    "CreateAPIKeyRequestRequestTypeDef",
+    "CreateAPIKeyResponseTypeDef",
     "TagTypeDef",
     "IPSetSummaryTypeDef",
     "RegexTypeDef",
     "RegexPatternSetSummaryTypeDef",
     "CustomResponseBodyTypeDef",
     "VisibilityConfigTypeDef",
     "RuleGroupSummaryTypeDef",
     "WebACLSummaryTypeDef",
     "CustomHTTPHeaderTypeDef",
     "DeleteFirewallManagerRuleGroupsRequestRequestTypeDef",
+    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
     "DeleteIPSetRequestRequestTypeDef",
     "DeleteLoggingConfigurationRequestRequestTypeDef",
     "DeletePermissionPolicyRequestRequestTypeDef",
     "DeleteRegexPatternSetRequestRequestTypeDef",
     "DeleteRuleGroupRequestRequestTypeDef",
     "DeleteWebACLRequestRequestTypeDef",
+    "DescribeAllManagedProductsRequestRequestTypeDef",
+    "ManagedProductDescriptorTypeDef",
+    "DescribeManagedProductsByVendorRequestRequestTypeDef",
     "DescribeManagedRuleGroupRequestRequestTypeDef",
     "LabelSummaryTypeDef",
     "DisassociateWebACLRequestRequestTypeDef",
+    "EmailFieldTypeDef",
     "ExcludedRuleTypeDef",
+    "HeaderOrderTypeDef",
     "SingleHeaderTypeDef",
     "SingleQueryArgumentTypeDef",
     "ForwardedIPConfigTypeDef",
     "GenerateMobileSdkReleaseUrlRequestRequestTypeDef",
+    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+    "GetDecryptedAPIKeyRequestRequestTypeDef",
+    "GetDecryptedAPIKeyResponseTypeDef",
     "GetIPSetRequestRequestTypeDef",
     "IPSetTypeDef",
     "GetLoggingConfigurationRequestRequestTypeDef",
     "GetManagedRuleSetRequestRequestTypeDef",
     "GetMobileSdkReleaseRequestRequestTypeDef",
     "GetPermissionPolicyRequestRequestTypeDef",
+    "GetPermissionPolicyResponseTypeDef",
     "GetRateBasedStatementManagedKeysRequestRequestTypeDef",
     "RateBasedStatementManagedKeysIPSetTypeDef",
     "GetRegexPatternSetRequestRequestTypeDef",
     "GetRuleGroupRequestRequestTypeDef",
     "TimeWindowTypeDef",
     "GetWebACLForResourceRequestRequestTypeDef",
     "GetWebACLRequestRequestTypeDef",
     "HTTPHeaderTypeDef",
     "HeaderMatchPatternTypeDef",
     "IPSetForwardedIPConfigTypeDef",
     "JsonMatchPatternTypeDef",
     "LabelMatchStatementTypeDef",
     "LabelTypeDef",
+    "ListAPIKeysRequestRequestTypeDef",
     "ListAvailableManagedRuleGroupVersionsRequestRequestTypeDef",
     "ManagedRuleGroupVersionTypeDef",
     "ListAvailableManagedRuleGroupsRequestRequestTypeDef",
     "ManagedRuleGroupSummaryTypeDef",
     "ListIPSetsRequestRequestTypeDef",
     "ListLoggingConfigurationsRequestRequestTypeDef",
     "ListManagedRuleSetsRequestRequestTypeDef",
     "ManagedRuleSetSummaryTypeDef",
     "ListMobileSdkReleasesRequestRequestTypeDef",
     "ReleaseSummaryTypeDef",
     "ListRegexPatternSetsRequestRequestTypeDef",
     "ListResourcesForWebACLRequestRequestTypeDef",
+    "ListResourcesForWebACLResponseTypeDef",
     "ListRuleGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListWebACLsRequestRequestTypeDef",
     "PasswordFieldTypeDef",
     "UsernameFieldTypeDef",
     "ManagedRuleSetVersionTypeDef",
     "NotStatementTypeDef",
     "OrStatementTypeDef",
+    "PhoneNumberFieldTypeDef",
     "VersionToPublishTypeDef",
+    "PutManagedRuleSetVersionsResponseTypeDef",
     "PutPermissionPolicyRequestRequestTypeDef",
+    "RateLimitLabelNamespaceTypeDef",
     "ResponseInspectionBodyContainsTypeDef",
     "ResponseInspectionHeaderTypeDef",
     "ResponseInspectionJsonTypeDef",
     "ResponseInspectionStatusCodeTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateIPSetRequestRequestTypeDef",
-    "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
-    "CaptchaConfigTypeDef",
-    "ChallengeConfigTypeDef",
-    "CheckCapacityResponseTypeDef",
-    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
-    "GenerateMobileSdkReleaseUrlResponseTypeDef",
-    "GetPermissionPolicyResponseTypeDef",
-    "ListResourcesForWebACLResponseTypeDef",
-    "PutManagedRuleSetVersionsResponseTypeDef",
     "UpdateIPSetResponseTypeDef",
+    "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
     "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
     "UpdateRegexPatternSetResponseTypeDef",
     "UpdateRuleGroupResponseTypeDef",
     "UpdateWebACLResponseTypeDef",
+    "ListAPIKeysResponseTypeDef",
+    "AssociationConfigTypeDef",
+    "RateLimitCookieTypeDef",
+    "RateLimitHeaderTypeDef",
+    "RateLimitQueryArgumentTypeDef",
+    "RateLimitQueryStringTypeDef",
+    "CaptchaConfigTypeDef",
+    "ChallengeConfigTypeDef",
     "ConditionTypeDef",
     "CookiesTypeDef",
     "CreateIPSetRequestRequestTypeDef",
     "MobileSdkReleaseTypeDef",
     "TagInfoForResourceTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateIPSetResponseTypeDef",
@@ -163,44 +189,49 @@
     "ListRegexPatternSetsResponseTypeDef",
     "CreateRuleGroupResponseTypeDef",
     "ListRuleGroupsResponseTypeDef",
     "CreateWebACLResponseTypeDef",
     "ListWebACLsResponseTypeDef",
     "CustomRequestHandlingTypeDef",
     "CustomResponseTypeDef",
+    "DescribeAllManagedProductsResponseTypeDef",
+    "DescribeManagedProductsByVendorResponseTypeDef",
     "GeoMatchStatementTypeDef",
-    "RateBasedStatementTypeDef",
     "GetIPSetResponseTypeDef",
     "GetRateBasedStatementManagedKeysResponseTypeDef",
     "GetSampledRequestsRequestRequestTypeDef",
     "HTTPRequestTypeDef",
     "HeadersTypeDef",
     "IPSetReferenceStatementTypeDef",
     "JsonBodyTypeDef",
     "ListAvailableManagedRuleGroupVersionsResponseTypeDef",
     "ListAvailableManagedRuleGroupsResponseTypeDef",
     "ListManagedRuleSetsResponseTypeDef",
     "ListMobileSdkReleasesResponseTypeDef",
     "RequestInspectionTypeDef",
     "ManagedRuleSetTypeDef",
+    "RequestInspectionACFPTypeDef",
     "PutManagedRuleSetVersionsRequestRequestTypeDef",
     "ResponseInspectionTypeDef",
+    "RateBasedStatementCustomKeyTypeDef",
     "FilterTypeDef",
     "GetMobileSdkReleaseResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "GetRegexPatternSetResponseTypeDef",
     "AllowActionTypeDef",
     "CaptchaActionTypeDef",
     "ChallengeActionTypeDef",
     "CountActionTypeDef",
     "BlockActionTypeDef",
     "SampledHTTPRequestTypeDef",
     "FieldToMatchTypeDef",
     "GetManagedRuleSetResponseTypeDef",
+    "AWSManagedRulesACFPRuleSetTypeDef",
     "AWSManagedRulesATPRuleSetTypeDef",
+    "RateBasedStatementTypeDef",
     "LoggingFilterTypeDef",
     "OverrideActionTypeDef",
     "DefaultActionTypeDef",
     "RuleActionTypeDef",
     "GetSampledRequestsResponseTypeDef",
     "ByteMatchStatementTypeDef",
     "RegexMatchStatementTypeDef",
@@ -231,28 +262,46 @@
     "GetRuleGroupResponseTypeDef",
     "FirewallManagerRuleGroupTypeDef",
     "WebACLTypeDef",
     "GetWebACLForResourceResponseTypeDef",
     "GetWebACLResponseTypeDef",
 )
 
+APIKeySummaryTypeDef = TypedDict(
+    "APIKeySummaryTypeDef",
+    {
+        "TokenDomains": List[str],
+        "APIKey": str,
+        "CreationTimestamp": datetime,
+        "Version": int,
+    },
+    total=False,
+)
+
 AWSManagedRulesBotControlRuleSetTypeDef = TypedDict(
     "AWSManagedRulesBotControlRuleSetTypeDef",
     {
         "InspectionLevel": InspectionLevelType,
     },
 )
 
 ActionConditionTypeDef = TypedDict(
     "ActionConditionTypeDef",
     {
         "Action": ActionValueType,
     },
 )
 
+AddressFieldTypeDef = TypedDict(
+    "AddressFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 AndStatementTypeDef = TypedDict(
     "AndStatementTypeDef",
     {
         "Statements": Sequence["StatementTypeDef"],
     },
 )
 
@@ -260,14 +309,21 @@
     "AssociateWebACLRequestRequestTypeDef",
     {
         "WebACLArn": str,
         "ResourceArn": str,
     },
 )
 
+RequestBodyAssociatedResourceTypeConfigTypeDef = TypedDict(
+    "RequestBodyAssociatedResourceTypeConfigTypeDef",
+    {
+        "DefaultSizeInspectionLimit": SizeInspectionLimitType,
+    },
+)
+
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "OversizeHandling": OversizeHandlingType,
     },
     total=False,
 )
@@ -303,22 +359,19 @@
         "ResponseCode": int,
         "SolveTimestamp": int,
         "FailureReason": FailureReasonType,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CheckCapacityResponseTypeDef = TypedDict(
+    "CheckCapacityResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Capacity": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelNameConditionTypeDef = TypedDict(
     "LabelNameConditionTypeDef",
     {
         "LabelName": str,
@@ -331,14 +384,30 @@
         "All": Mapping[str, Any],
         "IncludedCookies": Sequence[str],
         "ExcludedCookies": Sequence[str],
     },
     total=False,
 )
 
+CreateAPIKeyRequestRequestTypeDef = TypedDict(
+    "CreateAPIKeyRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+        "TokenDomains": Sequence[str],
+    },
+)
+
+CreateAPIKeyResponseTypeDef = TypedDict(
+    "CreateAPIKeyResponseTypeDef",
+    {
+        "APIKey": str,
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
@@ -428,14 +497,22 @@
     "DeleteFirewallManagerRuleGroupsRequestRequestTypeDef",
     {
         "WebACLArn": str,
         "WebACLLockToken": str,
     },
 )
 
+DeleteFirewallManagerRuleGroupsResponseTypeDef = TypedDict(
+    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
+    {
+        "NextWebACLLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIPSetRequestRequestTypeDef = TypedDict(
     "DeleteIPSetRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
@@ -482,14 +559,45 @@
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
     },
 )
 
+DescribeAllManagedProductsRequestRequestTypeDef = TypedDict(
+    "DescribeAllManagedProductsRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+    },
+)
+
+ManagedProductDescriptorTypeDef = TypedDict(
+    "ManagedProductDescriptorTypeDef",
+    {
+        "VendorName": str,
+        "ManagedRuleSetName": str,
+        "ProductId": str,
+        "ProductLink": str,
+        "ProductTitle": str,
+        "ProductDescription": str,
+        "SnsTopicArn": str,
+        "IsVersioningSupported": bool,
+        "IsAdvancedManagedRuleSet": bool,
+    },
+    total=False,
+)
+
+DescribeManagedProductsByVendorRequestRequestTypeDef = TypedDict(
+    "DescribeManagedProductsByVendorRequestRequestTypeDef",
+    {
+        "VendorName": str,
+        "Scope": ScopeType,
+    },
+)
+
 _RequiredDescribeManagedRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeManagedRuleGroupRequestRequestTypeDef",
     {
         "VendorName": str,
         "Name": str,
         "Scope": ScopeType,
     },
@@ -521,21 +629,35 @@
 DisassociateWebACLRequestRequestTypeDef = TypedDict(
     "DisassociateWebACLRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+EmailFieldTypeDef = TypedDict(
+    "EmailFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 ExcludedRuleTypeDef = TypedDict(
     "ExcludedRuleTypeDef",
     {
         "Name": str,
     },
 )
 
+HeaderOrderTypeDef = TypedDict(
+    "HeaderOrderTypeDef",
+    {
+        "OversizeHandling": OversizeHandlingType,
+    },
+)
+
 SingleHeaderTypeDef = TypedDict(
     "SingleHeaderTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -558,14 +680,39 @@
     "GenerateMobileSdkReleaseUrlRequestRequestTypeDef",
     {
         "Platform": PlatformType,
         "ReleaseVersion": str,
     },
 )
 
+GenerateMobileSdkReleaseUrlResponseTypeDef = TypedDict(
+    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+    {
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDecryptedAPIKeyRequestRequestTypeDef = TypedDict(
+    "GetDecryptedAPIKeyRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+        "APIKey": str,
+    },
+)
+
+GetDecryptedAPIKeyResponseTypeDef = TypedDict(
+    "GetDecryptedAPIKeyResponseTypeDef",
+    {
+        "TokenDomains": List[str],
+        "CreationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIPSetRequestRequestTypeDef = TypedDict(
     "GetIPSetRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
     },
@@ -621,14 +768,22 @@
 GetPermissionPolicyRequestRequestTypeDef = TypedDict(
     "GetPermissionPolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetPermissionPolicyResponseTypeDef = TypedDict(
+    "GetPermissionPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRateBasedStatementManagedKeysRequestRequestTypeDef = TypedDict(
     "_RequiredGetRateBasedStatementManagedKeysRequestRequestTypeDef",
     {
         "Scope": ScopeType,
         "WebACLName": str,
         "WebACLId": str,
         "RuleName": str,
@@ -751,14 +906,36 @@
 LabelTypeDef = TypedDict(
     "LabelTypeDef",
     {
         "Name": str,
     },
 )
 
+_RequiredListAPIKeysRequestRequestTypeDef = TypedDict(
+    "_RequiredListAPIKeysRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+    },
+)
+_OptionalListAPIKeysRequestRequestTypeDef = TypedDict(
+    "_OptionalListAPIKeysRequestRequestTypeDef",
+    {
+        "NextMarker": str,
+        "Limit": int,
+    },
+    total=False,
+)
+
+
+class ListAPIKeysRequestRequestTypeDef(
+    _RequiredListAPIKeysRequestRequestTypeDef, _OptionalListAPIKeysRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredListAvailableManagedRuleGroupVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailableManagedRuleGroupVersionsRequestRequestTypeDef",
     {
         "VendorName": str,
         "Name": str,
         "Scope": ScopeType,
     },
@@ -977,14 +1154,22 @@
 class ListResourcesForWebACLRequestRequestTypeDef(
     _RequiredListResourcesForWebACLRequestRequestTypeDef,
     _OptionalListResourcesForWebACLRequestRequestTypeDef,
 ):
     pass
 
 
+ListResourcesForWebACLResponseTypeDef = TypedDict(
+    "ListResourcesForWebACLResponseTypeDef",
+    {
+        "ResourceArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListRuleGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListRuleGroupsRequestRequestTypeDef",
     {
         "Scope": ScopeType,
     },
 )
 _OptionalListRuleGroupsRequestRequestTypeDef = TypedDict(
@@ -1085,31 +1270,53 @@
 OrStatementTypeDef = TypedDict(
     "OrStatementTypeDef",
     {
         "Statements": Sequence[Dict[str, Any]],
     },
 )
 
+PhoneNumberFieldTypeDef = TypedDict(
+    "PhoneNumberFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 VersionToPublishTypeDef = TypedDict(
     "VersionToPublishTypeDef",
     {
         "AssociatedRuleGroupArn": str,
         "ForecastedLifetime": int,
     },
     total=False,
 )
 
+PutManagedRuleSetVersionsResponseTypeDef = TypedDict(
+    "PutManagedRuleSetVersionsResponseTypeDef",
+    {
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutPermissionPolicyRequestRequestTypeDef = TypedDict(
     "PutPermissionPolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
     },
 )
 
+RateLimitLabelNamespaceTypeDef = TypedDict(
+    "RateLimitLabelNamespaceTypeDef",
+    {
+        "Namespace": str,
+    },
+)
+
 ResponseInspectionBodyContainsTypeDef = TypedDict(
     "ResponseInspectionBodyContainsTypeDef",
     {
         "SuccessStrings": Sequence[str],
         "FailureStrings": Sequence[str],
     },
 )
@@ -1136,14 +1343,25 @@
     "ResponseInspectionStatusCodeTypeDef",
     {
         "SuccessCodes": Sequence[int],
         "FailureCodes": Sequence[int],
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1169,130 +1387,133 @@
 
 class UpdateIPSetRequestRequestTypeDef(
     _RequiredUpdateIPSetRequestRequestTypeDef, _OptionalUpdateIPSetRequestRequestTypeDef
 ):
     pass
 
 
+UpdateIPSetResponseTypeDef = TypedDict(
+    "UpdateIPSetResponseTypeDef",
+    {
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef = TypedDict(
     "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
         "VersionToExpire": str,
         "ExpiryTimestamp": Union[datetime, str],
     },
 )
 
-CaptchaConfigTypeDef = TypedDict(
-    "CaptchaConfigTypeDef",
-    {
-        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
-    },
-    total=False,
-)
-
-ChallengeConfigTypeDef = TypedDict(
-    "ChallengeConfigTypeDef",
+UpdateManagedRuleSetVersionExpiryDateResponseTypeDef = TypedDict(
+    "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
     {
-        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
+        "ExpiringVersion": str,
+        "ExpiryTimestamp": datetime,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CheckCapacityResponseTypeDef = TypedDict(
-    "CheckCapacityResponseTypeDef",
+UpdateRegexPatternSetResponseTypeDef = TypedDict(
+    "UpdateRegexPatternSetResponseTypeDef",
     {
-        "Capacity": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFirewallManagerRuleGroupsResponseTypeDef = TypedDict(
-    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
+UpdateRuleGroupResponseTypeDef = TypedDict(
+    "UpdateRuleGroupResponseTypeDef",
     {
-        "NextWebACLLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GenerateMobileSdkReleaseUrlResponseTypeDef = TypedDict(
-    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+UpdateWebACLResponseTypeDef = TypedDict(
+    "UpdateWebACLResponseTypeDef",
     {
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetPermissionPolicyResponseTypeDef = TypedDict(
-    "GetPermissionPolicyResponseTypeDef",
+ListAPIKeysResponseTypeDef = TypedDict(
+    "ListAPIKeysResponseTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextMarker": str,
+        "APIKeySummaries": List[APIKeySummaryTypeDef],
+        "ApplicationIntegrationURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourcesForWebACLResponseTypeDef = TypedDict(
-    "ListResourcesForWebACLResponseTypeDef",
+AssociationConfigTypeDef = TypedDict(
+    "AssociationConfigTypeDef",
     {
-        "ResourceArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestBody": Mapping[
+            Literal["CLOUDFRONT"], RequestBodyAssociatedResourceTypeConfigTypeDef
+        ],
     },
+    total=False,
 )
 
-PutManagedRuleSetVersionsResponseTypeDef = TypedDict(
-    "PutManagedRuleSetVersionsResponseTypeDef",
+RateLimitCookieTypeDef = TypedDict(
+    "RateLimitCookieTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateIPSetResponseTypeDef = TypedDict(
-    "UpdateIPSetResponseTypeDef",
+RateLimitHeaderTypeDef = TypedDict(
+    "RateLimitHeaderTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateManagedRuleSetVersionExpiryDateResponseTypeDef = TypedDict(
-    "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
+RateLimitQueryArgumentTypeDef = TypedDict(
+    "RateLimitQueryArgumentTypeDef",
     {
-        "ExpiringVersion": str,
-        "ExpiryTimestamp": datetime,
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateRegexPatternSetResponseTypeDef = TypedDict(
-    "UpdateRegexPatternSetResponseTypeDef",
+RateLimitQueryStringTypeDef = TypedDict(
+    "RateLimitQueryStringTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateRuleGroupResponseTypeDef = TypedDict(
-    "UpdateRuleGroupResponseTypeDef",
+CaptchaConfigTypeDef = TypedDict(
+    "CaptchaConfigTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
     },
+    total=False,
 )
 
-UpdateWebACLResponseTypeDef = TypedDict(
-    "UpdateWebACLResponseTypeDef",
+ChallengeConfigTypeDef = TypedDict(
+    "ChallengeConfigTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
     },
+    total=False,
 )
 
 ConditionTypeDef = TypedDict(
     "ConditionTypeDef",
     {
         "ActionCondition": ActionConditionTypeDef,
         "LabelNameCondition": LabelNameConditionTypeDef,
@@ -1362,24 +1583,24 @@
     },
 )
 
 CreateIPSetResponseTypeDef = TypedDict(
     "CreateIPSetResponseTypeDef",
     {
         "Summary": IPSetSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIPSetsResponseTypeDef = TypedDict(
     "ListIPSetsResponseTypeDef",
     {
         "NextMarker": str,
         "IPSets": List[IPSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRegexPatternSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRegexPatternSetRequestRequestTypeDef",
     {
         "Name": str,
@@ -1442,58 +1663,58 @@
     pass
 
 
 CreateRegexPatternSetResponseTypeDef = TypedDict(
     "CreateRegexPatternSetResponseTypeDef",
     {
         "Summary": RegexPatternSetSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRegexPatternSetsResponseTypeDef = TypedDict(
     "ListRegexPatternSetsResponseTypeDef",
     {
         "NextMarker": str,
         "RegexPatternSets": List[RegexPatternSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleGroupResponseTypeDef = TypedDict(
     "CreateRuleGroupResponseTypeDef",
     {
         "Summary": RuleGroupSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRuleGroupsResponseTypeDef = TypedDict(
     "ListRuleGroupsResponseTypeDef",
     {
         "NextMarker": str,
         "RuleGroups": List[RuleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWebACLResponseTypeDef = TypedDict(
     "CreateWebACLResponseTypeDef",
     {
         "Summary": WebACLSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebACLsResponseTypeDef = TypedDict(
     "ListWebACLsResponseTypeDef",
     {
         "NextMarker": str,
         "WebACLs": List[WebACLSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomRequestHandlingTypeDef = TypedDict(
     "CustomRequestHandlingTypeDef",
     {
         "InsertHeaders": Sequence[CustomHTTPHeaderTypeDef],
@@ -1516,61 +1737,54 @@
 )
 
 
 class CustomResponseTypeDef(_RequiredCustomResponseTypeDef, _OptionalCustomResponseTypeDef):
     pass
 
 
-GeoMatchStatementTypeDef = TypedDict(
-    "GeoMatchStatementTypeDef",
+DescribeAllManagedProductsResponseTypeDef = TypedDict(
+    "DescribeAllManagedProductsResponseTypeDef",
     {
-        "CountryCodes": Sequence[CountryCodeType],
-        "ForwardedIPConfig": ForwardedIPConfigTypeDef,
+        "ManagedProducts": List[ManagedProductDescriptorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredRateBasedStatementTypeDef = TypedDict(
-    "_RequiredRateBasedStatementTypeDef",
+DescribeManagedProductsByVendorResponseTypeDef = TypedDict(
+    "DescribeManagedProductsByVendorResponseTypeDef",
     {
-        "Limit": int,
-        "AggregateKeyType": RateBasedStatementAggregateKeyTypeType,
+        "ManagedProducts": List[ManagedProductDescriptorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalRateBasedStatementTypeDef = TypedDict(
-    "_OptionalRateBasedStatementTypeDef",
+
+GeoMatchStatementTypeDef = TypedDict(
+    "GeoMatchStatementTypeDef",
     {
-        "ScopeDownStatement": "StatementTypeDef",
+        "CountryCodes": Sequence[CountryCodeType],
         "ForwardedIPConfig": ForwardedIPConfigTypeDef,
     },
     total=False,
 )
 
-
-class RateBasedStatementTypeDef(
-    _RequiredRateBasedStatementTypeDef, _OptionalRateBasedStatementTypeDef
-):
-    pass
-
-
 GetIPSetResponseTypeDef = TypedDict(
     "GetIPSetResponseTypeDef",
     {
         "IPSet": IPSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRateBasedStatementManagedKeysResponseTypeDef = TypedDict(
     "GetRateBasedStatementManagedKeysResponseTypeDef",
     {
         "ManagedKeysIPV4": RateBasedStatementManagedKeysIPSetTypeDef,
         "ManagedKeysIPV6": RateBasedStatementManagedKeysIPSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSampledRequestsRequestRequestTypeDef = TypedDict(
     "GetSampledRequestsRequestRequestTypeDef",
     {
         "WebAclArn": str,
@@ -1647,42 +1861,42 @@
 
 ListAvailableManagedRuleGroupVersionsResponseTypeDef = TypedDict(
     "ListAvailableManagedRuleGroupVersionsResponseTypeDef",
     {
         "NextMarker": str,
         "Versions": List[ManagedRuleGroupVersionTypeDef],
         "CurrentDefaultVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableManagedRuleGroupsResponseTypeDef = TypedDict(
     "ListAvailableManagedRuleGroupsResponseTypeDef",
     {
         "NextMarker": str,
         "ManagedRuleGroups": List[ManagedRuleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedRuleSetsResponseTypeDef = TypedDict(
     "ListManagedRuleSetsResponseTypeDef",
     {
         "NextMarker": str,
         "ManagedRuleSets": List[ManagedRuleSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileSdkReleasesResponseTypeDef = TypedDict(
     "ListMobileSdkReleasesResponseTypeDef",
     {
         "ReleaseSummaries": List[ReleaseSummaryTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestInspectionTypeDef = TypedDict(
     "RequestInspectionTypeDef",
     {
         "PayloadType": PayloadTypeType,
@@ -1711,14 +1925,39 @@
 )
 
 
 class ManagedRuleSetTypeDef(_RequiredManagedRuleSetTypeDef, _OptionalManagedRuleSetTypeDef):
     pass
 
 
+_RequiredRequestInspectionACFPTypeDef = TypedDict(
+    "_RequiredRequestInspectionACFPTypeDef",
+    {
+        "PayloadType": PayloadTypeType,
+    },
+)
+_OptionalRequestInspectionACFPTypeDef = TypedDict(
+    "_OptionalRequestInspectionACFPTypeDef",
+    {
+        "UsernameField": UsernameFieldTypeDef,
+        "PasswordField": PasswordFieldTypeDef,
+        "EmailField": EmailFieldTypeDef,
+        "PhoneNumberFields": Sequence[PhoneNumberFieldTypeDef],
+        "AddressFields": Sequence[AddressFieldTypeDef],
+    },
+    total=False,
+)
+
+
+class RequestInspectionACFPTypeDef(
+    _RequiredRequestInspectionACFPTypeDef, _OptionalRequestInspectionACFPTypeDef
+):
+    pass
+
+
 _RequiredPutManagedRuleSetVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutManagedRuleSetVersionsRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
@@ -1748,46 +1987,61 @@
         "Header": ResponseInspectionHeaderTypeDef,
         "BodyContains": ResponseInspectionBodyContainsTypeDef,
         "Json": ResponseInspectionJsonTypeDef,
     },
     total=False,
 )
 
+RateBasedStatementCustomKeyTypeDef = TypedDict(
+    "RateBasedStatementCustomKeyTypeDef",
+    {
+        "Header": RateLimitHeaderTypeDef,
+        "Cookie": RateLimitCookieTypeDef,
+        "QueryArgument": RateLimitQueryArgumentTypeDef,
+        "QueryString": RateLimitQueryStringTypeDef,
+        "HTTPMethod": Mapping[str, Any],
+        "ForwardedIP": Mapping[str, Any],
+        "IP": Mapping[str, Any],
+        "LabelNamespace": RateLimitLabelNamespaceTypeDef,
+    },
+    total=False,
+)
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Behavior": FilterBehaviorType,
         "Requirement": FilterRequirementType,
         "Conditions": List[ConditionTypeDef],
     },
 )
 
 GetMobileSdkReleaseResponseTypeDef = TypedDict(
     "GetMobileSdkReleaseResponseTypeDef",
     {
         "MobileSdkRelease": MobileSdkReleaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "NextMarker": str,
         "TagInfoForResource": TagInfoForResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegexPatternSetResponseTypeDef = TypedDict(
     "GetRegexPatternSetResponseTypeDef",
     {
         "RegexPatternSet": RegexPatternSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllowActionTypeDef = TypedDict(
     "AllowActionTypeDef",
     {
         "CustomRequestHandling": CustomRequestHandlingTypeDef,
@@ -1866,49 +2120,99 @@
         "UriPath": Mapping[str, Any],
         "QueryString": Mapping[str, Any],
         "Body": BodyTypeDef,
         "Method": Mapping[str, Any],
         "JsonBody": JsonBodyTypeDef,
         "Headers": HeadersTypeDef,
         "Cookies": CookiesTypeDef,
+        "HeaderOrder": HeaderOrderTypeDef,
     },
     total=False,
 )
 
 GetManagedRuleSetResponseTypeDef = TypedDict(
     "GetManagedRuleSetResponseTypeDef",
     {
         "ManagedRuleSet": ManagedRuleSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredAWSManagedRulesACFPRuleSetTypeDef = TypedDict(
+    "_RequiredAWSManagedRulesACFPRuleSetTypeDef",
+    {
+        "CreationPath": str,
+        "RegistrationPagePath": str,
+        "RequestInspection": RequestInspectionACFPTypeDef,
+    },
+)
+_OptionalAWSManagedRulesACFPRuleSetTypeDef = TypedDict(
+    "_OptionalAWSManagedRulesACFPRuleSetTypeDef",
+    {
+        "ResponseInspection": ResponseInspectionTypeDef,
+        "EnableRegexInPath": bool,
+    },
+    total=False,
+)
+
+
+class AWSManagedRulesACFPRuleSetTypeDef(
+    _RequiredAWSManagedRulesACFPRuleSetTypeDef, _OptionalAWSManagedRulesACFPRuleSetTypeDef
+):
+    pass
+
+
 _RequiredAWSManagedRulesATPRuleSetTypeDef = TypedDict(
     "_RequiredAWSManagedRulesATPRuleSetTypeDef",
     {
         "LoginPath": str,
     },
 )
 _OptionalAWSManagedRulesATPRuleSetTypeDef = TypedDict(
     "_OptionalAWSManagedRulesATPRuleSetTypeDef",
     {
         "RequestInspection": RequestInspectionTypeDef,
         "ResponseInspection": ResponseInspectionTypeDef,
+        "EnableRegexInPath": bool,
     },
     total=False,
 )
 
 
 class AWSManagedRulesATPRuleSetTypeDef(
     _RequiredAWSManagedRulesATPRuleSetTypeDef, _OptionalAWSManagedRulesATPRuleSetTypeDef
 ):
     pass
 
 
+_RequiredRateBasedStatementTypeDef = TypedDict(
+    "_RequiredRateBasedStatementTypeDef",
+    {
+        "Limit": int,
+        "AggregateKeyType": RateBasedStatementAggregateKeyTypeType,
+    },
+)
+_OptionalRateBasedStatementTypeDef = TypedDict(
+    "_OptionalRateBasedStatementTypeDef",
+    {
+        "ScopeDownStatement": "StatementTypeDef",
+        "ForwardedIPConfig": ForwardedIPConfigTypeDef,
+        "CustomKeys": Sequence[RateBasedStatementCustomKeyTypeDef],
+    },
+    total=False,
+)
+
+
+class RateBasedStatementTypeDef(
+    _RequiredRateBasedStatementTypeDef, _OptionalRateBasedStatementTypeDef
+):
+    pass
+
+
 LoggingFilterTypeDef = TypedDict(
     "LoggingFilterTypeDef",
     {
         "Filters": List[FilterTypeDef],
         "DefaultBehavior": FilterBehaviorType,
     },
 )
@@ -1945,15 +2249,15 @@
 
 GetSampledRequestsResponseTypeDef = TypedDict(
     "GetSampledRequestsResponseTypeDef",
     {
         "SampledRequests": List[SampledHTTPRequestTypeDef],
         "PopulationSize": int,
         "TimeWindow": TimeWindowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ByteMatchStatementTypeDef = TypedDict(
     "ByteMatchStatementTypeDef",
     {
         "SearchString": Union[str, bytes, IO[Any], StreamingBody],
@@ -2026,14 +2330,15 @@
     {
         "LoginPath": str,
         "PayloadType": PayloadTypeType,
         "UsernameField": UsernameFieldTypeDef,
         "PasswordField": PasswordFieldTypeDef,
         "AWSManagedRulesBotControlRuleSet": AWSManagedRulesBotControlRuleSetTypeDef,
         "AWSManagedRulesATPRuleSet": AWSManagedRulesATPRuleSetTypeDef,
+        "AWSManagedRulesACFPRuleSet": AWSManagedRulesACFPRuleSetTypeDef,
     },
     total=False,
 )
 
 _RequiredLoggingConfigurationTypeDef = TypedDict(
     "_RequiredLoggingConfigurationTypeDef",
     {
@@ -2101,39 +2406,39 @@
     pass
 
 
 GetLoggingConfigurationResponseTypeDef = TypedDict(
     "GetLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLoggingConfigurationsResponseTypeDef = TypedDict(
     "ListLoggingConfigurationsResponseTypeDef",
     {
         "LoggingConfigurations": List[LoggingConfigurationTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "PutLoggingConfigurationRequestRequestTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
     },
 )
 
 PutLoggingConfigurationResponseTypeDef = TypedDict(
     "PutLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredManagedRuleGroupStatementTypeDef = TypedDict(
     "_RequiredManagedRuleGroupStatementTypeDef",
     {
         "VendorName": str,
@@ -2187,15 +2492,15 @@
         "VersionName": str,
         "SnsTopicArn": str,
         "Capacity": int,
         "Rules": List[RuleSummaryTypeDef],
         "LabelNamespace": str,
         "AvailableLabels": List[LabelSummaryTypeDef],
         "ConsumedLabels": List[LabelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CheckCapacityRequestRequestTypeDef = TypedDict(
     "CheckCapacityRequestRequestTypeDef",
     {
         "Scope": ScopeType,
@@ -2245,14 +2550,15 @@
         "Description": str,
         "Rules": Sequence[RuleTypeDef],
         "Tags": Sequence[TagTypeDef],
         "CustomResponseBodies": Mapping[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": Sequence[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 
 class CreateWebACLRequestRequestTypeDef(
     _RequiredCreateWebACLRequestRequestTypeDef, _OptionalCreateWebACLRequestRequestTypeDef
@@ -2331,14 +2637,15 @@
     {
         "Description": str,
         "Rules": Sequence[RuleTypeDef],
         "CustomResponseBodies": Mapping[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": Sequence[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 
 class UpdateWebACLRequestRequestTypeDef(
     _RequiredUpdateWebACLRequestRequestTypeDef, _OptionalUpdateWebACLRequestRequestTypeDef
@@ -2378,15 +2685,15 @@
 )
 
 GetRuleGroupResponseTypeDef = TypedDict(
     "GetRuleGroupResponseTypeDef",
     {
         "RuleGroup": RuleGroupTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FirewallManagerRuleGroupTypeDef = TypedDict(
     "FirewallManagerRuleGroupTypeDef",
     {
         "Name": str,
@@ -2417,33 +2724,34 @@
         "PostProcessFirewallManagerRuleGroups": List[FirewallManagerRuleGroupTypeDef],
         "ManagedByFirewallManager": bool,
         "LabelNamespace": str,
         "CustomResponseBodies": Dict[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": List[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 
 class WebACLTypeDef(_RequiredWebACLTypeDef, _OptionalWebACLTypeDef):
     pass
 
 
 GetWebACLForResourceResponseTypeDef = TypedDict(
     "GetWebACLForResourceResponseTypeDef",
     {
         "WebACL": WebACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWebACLResponseTypeDef = TypedDict(
     "GetWebACLResponseTypeDef",
     {
         "WebACL": WebACLTypeDef,
         "LockToken": str,
         "ApplicationIntegrationURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2/type_defs.pyi` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for wafv2 service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_wafv2.type_defs import AWSManagedRulesBotControlRuleSetTypeDef
+    from types_aiobotocore_wafv2.type_defs import APIKeySummaryTypeDef
 
-    data: AWSManagedRulesBotControlRuleSetTypeDef = {...}
+    data: APIKeySummaryTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -37,120 +37,146 @@
     PlatformType,
     PositionalConstraintType,
     RateBasedStatementAggregateKeyTypeType,
     ResourceTypeType,
     ResponseContentTypeType,
     ScopeType,
     SensitivityLevelType,
+    SizeInspectionLimitType,
     TextTransformationTypeType,
 )
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
+    "APIKeySummaryTypeDef",
     "AWSManagedRulesBotControlRuleSetTypeDef",
     "ActionConditionTypeDef",
+    "AddressFieldTypeDef",
     "AndStatementTypeDef",
     "AssociateWebACLRequestRequestTypeDef",
+    "RequestBodyAssociatedResourceTypeConfigTypeDef",
     "BodyTypeDef",
     "TextTransformationTypeDef",
     "ImmunityTimePropertyTypeDef",
     "CaptchaResponseTypeDef",
     "ChallengeResponseTypeDef",
-    "ResponseMetadataTypeDef",
+    "CheckCapacityResponseTypeDef",
     "LabelNameConditionTypeDef",
     "CookieMatchPatternTypeDef",
+    "CreateAPIKeyRequestRequestTypeDef",
+    "CreateAPIKeyResponseTypeDef",
     "TagTypeDef",
     "IPSetSummaryTypeDef",
     "RegexTypeDef",
     "RegexPatternSetSummaryTypeDef",
     "CustomResponseBodyTypeDef",
     "VisibilityConfigTypeDef",
     "RuleGroupSummaryTypeDef",
     "WebACLSummaryTypeDef",
     "CustomHTTPHeaderTypeDef",
     "DeleteFirewallManagerRuleGroupsRequestRequestTypeDef",
+    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
     "DeleteIPSetRequestRequestTypeDef",
     "DeleteLoggingConfigurationRequestRequestTypeDef",
     "DeletePermissionPolicyRequestRequestTypeDef",
     "DeleteRegexPatternSetRequestRequestTypeDef",
     "DeleteRuleGroupRequestRequestTypeDef",
     "DeleteWebACLRequestRequestTypeDef",
+    "DescribeAllManagedProductsRequestRequestTypeDef",
+    "ManagedProductDescriptorTypeDef",
+    "DescribeManagedProductsByVendorRequestRequestTypeDef",
     "DescribeManagedRuleGroupRequestRequestTypeDef",
     "LabelSummaryTypeDef",
     "DisassociateWebACLRequestRequestTypeDef",
+    "EmailFieldTypeDef",
     "ExcludedRuleTypeDef",
+    "HeaderOrderTypeDef",
     "SingleHeaderTypeDef",
     "SingleQueryArgumentTypeDef",
     "ForwardedIPConfigTypeDef",
     "GenerateMobileSdkReleaseUrlRequestRequestTypeDef",
+    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+    "GetDecryptedAPIKeyRequestRequestTypeDef",
+    "GetDecryptedAPIKeyResponseTypeDef",
     "GetIPSetRequestRequestTypeDef",
     "IPSetTypeDef",
     "GetLoggingConfigurationRequestRequestTypeDef",
     "GetManagedRuleSetRequestRequestTypeDef",
     "GetMobileSdkReleaseRequestRequestTypeDef",
     "GetPermissionPolicyRequestRequestTypeDef",
+    "GetPermissionPolicyResponseTypeDef",
     "GetRateBasedStatementManagedKeysRequestRequestTypeDef",
     "RateBasedStatementManagedKeysIPSetTypeDef",
     "GetRegexPatternSetRequestRequestTypeDef",
     "GetRuleGroupRequestRequestTypeDef",
     "TimeWindowTypeDef",
     "GetWebACLForResourceRequestRequestTypeDef",
     "GetWebACLRequestRequestTypeDef",
     "HTTPHeaderTypeDef",
     "HeaderMatchPatternTypeDef",
     "IPSetForwardedIPConfigTypeDef",
     "JsonMatchPatternTypeDef",
     "LabelMatchStatementTypeDef",
     "LabelTypeDef",
+    "ListAPIKeysRequestRequestTypeDef",
     "ListAvailableManagedRuleGroupVersionsRequestRequestTypeDef",
     "ManagedRuleGroupVersionTypeDef",
     "ListAvailableManagedRuleGroupsRequestRequestTypeDef",
     "ManagedRuleGroupSummaryTypeDef",
     "ListIPSetsRequestRequestTypeDef",
     "ListLoggingConfigurationsRequestRequestTypeDef",
     "ListManagedRuleSetsRequestRequestTypeDef",
     "ManagedRuleSetSummaryTypeDef",
     "ListMobileSdkReleasesRequestRequestTypeDef",
     "ReleaseSummaryTypeDef",
     "ListRegexPatternSetsRequestRequestTypeDef",
     "ListResourcesForWebACLRequestRequestTypeDef",
+    "ListResourcesForWebACLResponseTypeDef",
     "ListRuleGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListWebACLsRequestRequestTypeDef",
     "PasswordFieldTypeDef",
     "UsernameFieldTypeDef",
     "ManagedRuleSetVersionTypeDef",
     "NotStatementTypeDef",
     "OrStatementTypeDef",
+    "PhoneNumberFieldTypeDef",
     "VersionToPublishTypeDef",
+    "PutManagedRuleSetVersionsResponseTypeDef",
     "PutPermissionPolicyRequestRequestTypeDef",
+    "RateLimitLabelNamespaceTypeDef",
     "ResponseInspectionBodyContainsTypeDef",
     "ResponseInspectionHeaderTypeDef",
     "ResponseInspectionJsonTypeDef",
     "ResponseInspectionStatusCodeTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateIPSetRequestRequestTypeDef",
-    "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
-    "CaptchaConfigTypeDef",
-    "ChallengeConfigTypeDef",
-    "CheckCapacityResponseTypeDef",
-    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
-    "GenerateMobileSdkReleaseUrlResponseTypeDef",
-    "GetPermissionPolicyResponseTypeDef",
-    "ListResourcesForWebACLResponseTypeDef",
-    "PutManagedRuleSetVersionsResponseTypeDef",
     "UpdateIPSetResponseTypeDef",
+    "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
     "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
     "UpdateRegexPatternSetResponseTypeDef",
     "UpdateRuleGroupResponseTypeDef",
     "UpdateWebACLResponseTypeDef",
+    "ListAPIKeysResponseTypeDef",
+    "AssociationConfigTypeDef",
+    "RateLimitCookieTypeDef",
+    "RateLimitHeaderTypeDef",
+    "RateLimitQueryArgumentTypeDef",
+    "RateLimitQueryStringTypeDef",
+    "CaptchaConfigTypeDef",
+    "ChallengeConfigTypeDef",
     "ConditionTypeDef",
     "CookiesTypeDef",
     "CreateIPSetRequestRequestTypeDef",
     "MobileSdkReleaseTypeDef",
     "TagInfoForResourceTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateIPSetResponseTypeDef",
@@ -162,44 +188,49 @@
     "ListRegexPatternSetsResponseTypeDef",
     "CreateRuleGroupResponseTypeDef",
     "ListRuleGroupsResponseTypeDef",
     "CreateWebACLResponseTypeDef",
     "ListWebACLsResponseTypeDef",
     "CustomRequestHandlingTypeDef",
     "CustomResponseTypeDef",
+    "DescribeAllManagedProductsResponseTypeDef",
+    "DescribeManagedProductsByVendorResponseTypeDef",
     "GeoMatchStatementTypeDef",
-    "RateBasedStatementTypeDef",
     "GetIPSetResponseTypeDef",
     "GetRateBasedStatementManagedKeysResponseTypeDef",
     "GetSampledRequestsRequestRequestTypeDef",
     "HTTPRequestTypeDef",
     "HeadersTypeDef",
     "IPSetReferenceStatementTypeDef",
     "JsonBodyTypeDef",
     "ListAvailableManagedRuleGroupVersionsResponseTypeDef",
     "ListAvailableManagedRuleGroupsResponseTypeDef",
     "ListManagedRuleSetsResponseTypeDef",
     "ListMobileSdkReleasesResponseTypeDef",
     "RequestInspectionTypeDef",
     "ManagedRuleSetTypeDef",
+    "RequestInspectionACFPTypeDef",
     "PutManagedRuleSetVersionsRequestRequestTypeDef",
     "ResponseInspectionTypeDef",
+    "RateBasedStatementCustomKeyTypeDef",
     "FilterTypeDef",
     "GetMobileSdkReleaseResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "GetRegexPatternSetResponseTypeDef",
     "AllowActionTypeDef",
     "CaptchaActionTypeDef",
     "ChallengeActionTypeDef",
     "CountActionTypeDef",
     "BlockActionTypeDef",
     "SampledHTTPRequestTypeDef",
     "FieldToMatchTypeDef",
     "GetManagedRuleSetResponseTypeDef",
+    "AWSManagedRulesACFPRuleSetTypeDef",
     "AWSManagedRulesATPRuleSetTypeDef",
+    "RateBasedStatementTypeDef",
     "LoggingFilterTypeDef",
     "OverrideActionTypeDef",
     "DefaultActionTypeDef",
     "RuleActionTypeDef",
     "GetSampledRequestsResponseTypeDef",
     "ByteMatchStatementTypeDef",
     "RegexMatchStatementTypeDef",
@@ -230,28 +261,46 @@
     "GetRuleGroupResponseTypeDef",
     "FirewallManagerRuleGroupTypeDef",
     "WebACLTypeDef",
     "GetWebACLForResourceResponseTypeDef",
     "GetWebACLResponseTypeDef",
 )
 
+APIKeySummaryTypeDef = TypedDict(
+    "APIKeySummaryTypeDef",
+    {
+        "TokenDomains": List[str],
+        "APIKey": str,
+        "CreationTimestamp": datetime,
+        "Version": int,
+    },
+    total=False,
+)
+
 AWSManagedRulesBotControlRuleSetTypeDef = TypedDict(
     "AWSManagedRulesBotControlRuleSetTypeDef",
     {
         "InspectionLevel": InspectionLevelType,
     },
 )
 
 ActionConditionTypeDef = TypedDict(
     "ActionConditionTypeDef",
     {
         "Action": ActionValueType,
     },
 )
 
+AddressFieldTypeDef = TypedDict(
+    "AddressFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 AndStatementTypeDef = TypedDict(
     "AndStatementTypeDef",
     {
         "Statements": Sequence["StatementTypeDef"],
     },
 )
 
@@ -259,14 +308,21 @@
     "AssociateWebACLRequestRequestTypeDef",
     {
         "WebACLArn": str,
         "ResourceArn": str,
     },
 )
 
+RequestBodyAssociatedResourceTypeConfigTypeDef = TypedDict(
+    "RequestBodyAssociatedResourceTypeConfigTypeDef",
+    {
+        "DefaultSizeInspectionLimit": SizeInspectionLimitType,
+    },
+)
+
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "OversizeHandling": OversizeHandlingType,
     },
     total=False,
 )
@@ -302,22 +358,19 @@
         "ResponseCode": int,
         "SolveTimestamp": int,
         "FailureReason": FailureReasonType,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CheckCapacityResponseTypeDef = TypedDict(
+    "CheckCapacityResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Capacity": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelNameConditionTypeDef = TypedDict(
     "LabelNameConditionTypeDef",
     {
         "LabelName": str,
@@ -330,14 +383,30 @@
         "All": Mapping[str, Any],
         "IncludedCookies": Sequence[str],
         "ExcludedCookies": Sequence[str],
     },
     total=False,
 )
 
+CreateAPIKeyRequestRequestTypeDef = TypedDict(
+    "CreateAPIKeyRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+        "TokenDomains": Sequence[str],
+    },
+)
+
+CreateAPIKeyResponseTypeDef = TypedDict(
+    "CreateAPIKeyResponseTypeDef",
+    {
+        "APIKey": str,
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
@@ -427,14 +496,22 @@
     "DeleteFirewallManagerRuleGroupsRequestRequestTypeDef",
     {
         "WebACLArn": str,
         "WebACLLockToken": str,
     },
 )
 
+DeleteFirewallManagerRuleGroupsResponseTypeDef = TypedDict(
+    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
+    {
+        "NextWebACLLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIPSetRequestRequestTypeDef = TypedDict(
     "DeleteIPSetRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
@@ -481,14 +558,45 @@
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
     },
 )
 
+DescribeAllManagedProductsRequestRequestTypeDef = TypedDict(
+    "DescribeAllManagedProductsRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+    },
+)
+
+ManagedProductDescriptorTypeDef = TypedDict(
+    "ManagedProductDescriptorTypeDef",
+    {
+        "VendorName": str,
+        "ManagedRuleSetName": str,
+        "ProductId": str,
+        "ProductLink": str,
+        "ProductTitle": str,
+        "ProductDescription": str,
+        "SnsTopicArn": str,
+        "IsVersioningSupported": bool,
+        "IsAdvancedManagedRuleSet": bool,
+    },
+    total=False,
+)
+
+DescribeManagedProductsByVendorRequestRequestTypeDef = TypedDict(
+    "DescribeManagedProductsByVendorRequestRequestTypeDef",
+    {
+        "VendorName": str,
+        "Scope": ScopeType,
+    },
+)
+
 _RequiredDescribeManagedRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeManagedRuleGroupRequestRequestTypeDef",
     {
         "VendorName": str,
         "Name": str,
         "Scope": ScopeType,
     },
@@ -518,21 +626,35 @@
 DisassociateWebACLRequestRequestTypeDef = TypedDict(
     "DisassociateWebACLRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+EmailFieldTypeDef = TypedDict(
+    "EmailFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 ExcludedRuleTypeDef = TypedDict(
     "ExcludedRuleTypeDef",
     {
         "Name": str,
     },
 )
 
+HeaderOrderTypeDef = TypedDict(
+    "HeaderOrderTypeDef",
+    {
+        "OversizeHandling": OversizeHandlingType,
+    },
+)
+
 SingleHeaderTypeDef = TypedDict(
     "SingleHeaderTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -555,14 +677,39 @@
     "GenerateMobileSdkReleaseUrlRequestRequestTypeDef",
     {
         "Platform": PlatformType,
         "ReleaseVersion": str,
     },
 )
 
+GenerateMobileSdkReleaseUrlResponseTypeDef = TypedDict(
+    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+    {
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDecryptedAPIKeyRequestRequestTypeDef = TypedDict(
+    "GetDecryptedAPIKeyRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+        "APIKey": str,
+    },
+)
+
+GetDecryptedAPIKeyResponseTypeDef = TypedDict(
+    "GetDecryptedAPIKeyResponseTypeDef",
+    {
+        "TokenDomains": List[str],
+        "CreationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIPSetRequestRequestTypeDef = TypedDict(
     "GetIPSetRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
     },
@@ -616,14 +763,22 @@
 GetPermissionPolicyRequestRequestTypeDef = TypedDict(
     "GetPermissionPolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetPermissionPolicyResponseTypeDef = TypedDict(
+    "GetPermissionPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRateBasedStatementManagedKeysRequestRequestTypeDef = TypedDict(
     "_RequiredGetRateBasedStatementManagedKeysRequestRequestTypeDef",
     {
         "Scope": ScopeType,
         "WebACLName": str,
         "WebACLId": str,
         "RuleName": str,
@@ -744,14 +899,34 @@
 LabelTypeDef = TypedDict(
     "LabelTypeDef",
     {
         "Name": str,
     },
 )
 
+_RequiredListAPIKeysRequestRequestTypeDef = TypedDict(
+    "_RequiredListAPIKeysRequestRequestTypeDef",
+    {
+        "Scope": ScopeType,
+    },
+)
+_OptionalListAPIKeysRequestRequestTypeDef = TypedDict(
+    "_OptionalListAPIKeysRequestRequestTypeDef",
+    {
+        "NextMarker": str,
+        "Limit": int,
+    },
+    total=False,
+)
+
+class ListAPIKeysRequestRequestTypeDef(
+    _RequiredListAPIKeysRequestRequestTypeDef, _OptionalListAPIKeysRequestRequestTypeDef
+):
+    pass
+
 _RequiredListAvailableManagedRuleGroupVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailableManagedRuleGroupVersionsRequestRequestTypeDef",
     {
         "VendorName": str,
         "Name": str,
         "Scope": ScopeType,
     },
@@ -954,14 +1129,22 @@
 
 class ListResourcesForWebACLRequestRequestTypeDef(
     _RequiredListResourcesForWebACLRequestRequestTypeDef,
     _OptionalListResourcesForWebACLRequestRequestTypeDef,
 ):
     pass
 
+ListResourcesForWebACLResponseTypeDef = TypedDict(
+    "ListResourcesForWebACLResponseTypeDef",
+    {
+        "ResourceArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListRuleGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListRuleGroupsRequestRequestTypeDef",
     {
         "Scope": ScopeType,
     },
 )
 _OptionalListRuleGroupsRequestRequestTypeDef = TypedDict(
@@ -1056,31 +1239,53 @@
 OrStatementTypeDef = TypedDict(
     "OrStatementTypeDef",
     {
         "Statements": Sequence[Dict[str, Any]],
     },
 )
 
+PhoneNumberFieldTypeDef = TypedDict(
+    "PhoneNumberFieldTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+
 VersionToPublishTypeDef = TypedDict(
     "VersionToPublishTypeDef",
     {
         "AssociatedRuleGroupArn": str,
         "ForecastedLifetime": int,
     },
     total=False,
 )
 
+PutManagedRuleSetVersionsResponseTypeDef = TypedDict(
+    "PutManagedRuleSetVersionsResponseTypeDef",
+    {
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutPermissionPolicyRequestRequestTypeDef = TypedDict(
     "PutPermissionPolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
     },
 )
 
+RateLimitLabelNamespaceTypeDef = TypedDict(
+    "RateLimitLabelNamespaceTypeDef",
+    {
+        "Namespace": str,
+    },
+)
+
 ResponseInspectionBodyContainsTypeDef = TypedDict(
     "ResponseInspectionBodyContainsTypeDef",
     {
         "SuccessStrings": Sequence[str],
         "FailureStrings": Sequence[str],
     },
 )
@@ -1107,14 +1312,25 @@
     "ResponseInspectionStatusCodeTypeDef",
     {
         "SuccessCodes": Sequence[int],
         "FailureCodes": Sequence[int],
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1138,130 +1354,133 @@
 )
 
 class UpdateIPSetRequestRequestTypeDef(
     _RequiredUpdateIPSetRequestRequestTypeDef, _OptionalUpdateIPSetRequestRequestTypeDef
 ):
     pass
 
+UpdateIPSetResponseTypeDef = TypedDict(
+    "UpdateIPSetResponseTypeDef",
+    {
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef = TypedDict(
     "UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
         "VersionToExpire": str,
         "ExpiryTimestamp": Union[datetime, str],
     },
 )
 
-CaptchaConfigTypeDef = TypedDict(
-    "CaptchaConfigTypeDef",
-    {
-        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
-    },
-    total=False,
-)
-
-ChallengeConfigTypeDef = TypedDict(
-    "ChallengeConfigTypeDef",
+UpdateManagedRuleSetVersionExpiryDateResponseTypeDef = TypedDict(
+    "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
     {
-        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
+        "ExpiringVersion": str,
+        "ExpiryTimestamp": datetime,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CheckCapacityResponseTypeDef = TypedDict(
-    "CheckCapacityResponseTypeDef",
+UpdateRegexPatternSetResponseTypeDef = TypedDict(
+    "UpdateRegexPatternSetResponseTypeDef",
     {
-        "Capacity": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFirewallManagerRuleGroupsResponseTypeDef = TypedDict(
-    "DeleteFirewallManagerRuleGroupsResponseTypeDef",
+UpdateRuleGroupResponseTypeDef = TypedDict(
+    "UpdateRuleGroupResponseTypeDef",
     {
-        "NextWebACLLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GenerateMobileSdkReleaseUrlResponseTypeDef = TypedDict(
-    "GenerateMobileSdkReleaseUrlResponseTypeDef",
+UpdateWebACLResponseTypeDef = TypedDict(
+    "UpdateWebACLResponseTypeDef",
     {
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextLockToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetPermissionPolicyResponseTypeDef = TypedDict(
-    "GetPermissionPolicyResponseTypeDef",
+ListAPIKeysResponseTypeDef = TypedDict(
+    "ListAPIKeysResponseTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextMarker": str,
+        "APIKeySummaries": List[APIKeySummaryTypeDef],
+        "ApplicationIntegrationURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourcesForWebACLResponseTypeDef = TypedDict(
-    "ListResourcesForWebACLResponseTypeDef",
+AssociationConfigTypeDef = TypedDict(
+    "AssociationConfigTypeDef",
     {
-        "ResourceArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestBody": Mapping[
+            Literal["CLOUDFRONT"], RequestBodyAssociatedResourceTypeConfigTypeDef
+        ],
     },
+    total=False,
 )
 
-PutManagedRuleSetVersionsResponseTypeDef = TypedDict(
-    "PutManagedRuleSetVersionsResponseTypeDef",
+RateLimitCookieTypeDef = TypedDict(
+    "RateLimitCookieTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateIPSetResponseTypeDef = TypedDict(
-    "UpdateIPSetResponseTypeDef",
+RateLimitHeaderTypeDef = TypedDict(
+    "RateLimitHeaderTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateManagedRuleSetVersionExpiryDateResponseTypeDef = TypedDict(
-    "UpdateManagedRuleSetVersionExpiryDateResponseTypeDef",
+RateLimitQueryArgumentTypeDef = TypedDict(
+    "RateLimitQueryArgumentTypeDef",
     {
-        "ExpiringVersion": str,
-        "ExpiryTimestamp": datetime,
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateRegexPatternSetResponseTypeDef = TypedDict(
-    "UpdateRegexPatternSetResponseTypeDef",
+RateLimitQueryStringTypeDef = TypedDict(
+    "RateLimitQueryStringTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TextTransformations": Sequence[TextTransformationTypeDef],
     },
 )
 
-UpdateRuleGroupResponseTypeDef = TypedDict(
-    "UpdateRuleGroupResponseTypeDef",
+CaptchaConfigTypeDef = TypedDict(
+    "CaptchaConfigTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
     },
+    total=False,
 )
 
-UpdateWebACLResponseTypeDef = TypedDict(
-    "UpdateWebACLResponseTypeDef",
+ChallengeConfigTypeDef = TypedDict(
+    "ChallengeConfigTypeDef",
     {
-        "NextLockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ImmunityTimeProperty": ImmunityTimePropertyTypeDef,
     },
+    total=False,
 )
 
 ConditionTypeDef = TypedDict(
     "ConditionTypeDef",
     {
         "ActionCondition": ActionConditionTypeDef,
         "LabelNameCondition": LabelNameConditionTypeDef,
@@ -1329,24 +1548,24 @@
     },
 )
 
 CreateIPSetResponseTypeDef = TypedDict(
     "CreateIPSetResponseTypeDef",
     {
         "Summary": IPSetSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIPSetsResponseTypeDef = TypedDict(
     "ListIPSetsResponseTypeDef",
     {
         "NextMarker": str,
         "IPSets": List[IPSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRegexPatternSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRegexPatternSetRequestRequestTypeDef",
     {
         "Name": str,
@@ -1405,58 +1624,58 @@
 ):
     pass
 
 CreateRegexPatternSetResponseTypeDef = TypedDict(
     "CreateRegexPatternSetResponseTypeDef",
     {
         "Summary": RegexPatternSetSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRegexPatternSetsResponseTypeDef = TypedDict(
     "ListRegexPatternSetsResponseTypeDef",
     {
         "NextMarker": str,
         "RegexPatternSets": List[RegexPatternSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleGroupResponseTypeDef = TypedDict(
     "CreateRuleGroupResponseTypeDef",
     {
         "Summary": RuleGroupSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRuleGroupsResponseTypeDef = TypedDict(
     "ListRuleGroupsResponseTypeDef",
     {
         "NextMarker": str,
         "RuleGroups": List[RuleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWebACLResponseTypeDef = TypedDict(
     "CreateWebACLResponseTypeDef",
     {
         "Summary": WebACLSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebACLsResponseTypeDef = TypedDict(
     "ListWebACLsResponseTypeDef",
     {
         "NextMarker": str,
         "WebACLs": List[WebACLSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomRequestHandlingTypeDef = TypedDict(
     "CustomRequestHandlingTypeDef",
     {
         "InsertHeaders": Sequence[CustomHTTPHeaderTypeDef],
@@ -1477,59 +1696,54 @@
     },
     total=False,
 )
 
 class CustomResponseTypeDef(_RequiredCustomResponseTypeDef, _OptionalCustomResponseTypeDef):
     pass
 
-GeoMatchStatementTypeDef = TypedDict(
-    "GeoMatchStatementTypeDef",
+DescribeAllManagedProductsResponseTypeDef = TypedDict(
+    "DescribeAllManagedProductsResponseTypeDef",
     {
-        "CountryCodes": Sequence[CountryCodeType],
-        "ForwardedIPConfig": ForwardedIPConfigTypeDef,
+        "ManagedProducts": List[ManagedProductDescriptorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredRateBasedStatementTypeDef = TypedDict(
-    "_RequiredRateBasedStatementTypeDef",
+DescribeManagedProductsByVendorResponseTypeDef = TypedDict(
+    "DescribeManagedProductsByVendorResponseTypeDef",
     {
-        "Limit": int,
-        "AggregateKeyType": RateBasedStatementAggregateKeyTypeType,
+        "ManagedProducts": List[ManagedProductDescriptorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalRateBasedStatementTypeDef = TypedDict(
-    "_OptionalRateBasedStatementTypeDef",
+
+GeoMatchStatementTypeDef = TypedDict(
+    "GeoMatchStatementTypeDef",
     {
-        "ScopeDownStatement": "StatementTypeDef",
+        "CountryCodes": Sequence[CountryCodeType],
         "ForwardedIPConfig": ForwardedIPConfigTypeDef,
     },
     total=False,
 )
 
-class RateBasedStatementTypeDef(
-    _RequiredRateBasedStatementTypeDef, _OptionalRateBasedStatementTypeDef
-):
-    pass
-
 GetIPSetResponseTypeDef = TypedDict(
     "GetIPSetResponseTypeDef",
     {
         "IPSet": IPSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRateBasedStatementManagedKeysResponseTypeDef = TypedDict(
     "GetRateBasedStatementManagedKeysResponseTypeDef",
     {
         "ManagedKeysIPV4": RateBasedStatementManagedKeysIPSetTypeDef,
         "ManagedKeysIPV6": RateBasedStatementManagedKeysIPSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSampledRequestsRequestRequestTypeDef = TypedDict(
     "GetSampledRequestsRequestRequestTypeDef",
     {
         "WebAclArn": str,
@@ -1602,42 +1816,42 @@
 
 ListAvailableManagedRuleGroupVersionsResponseTypeDef = TypedDict(
     "ListAvailableManagedRuleGroupVersionsResponseTypeDef",
     {
         "NextMarker": str,
         "Versions": List[ManagedRuleGroupVersionTypeDef],
         "CurrentDefaultVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableManagedRuleGroupsResponseTypeDef = TypedDict(
     "ListAvailableManagedRuleGroupsResponseTypeDef",
     {
         "NextMarker": str,
         "ManagedRuleGroups": List[ManagedRuleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedRuleSetsResponseTypeDef = TypedDict(
     "ListManagedRuleSetsResponseTypeDef",
     {
         "NextMarker": str,
         "ManagedRuleSets": List[ManagedRuleSetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileSdkReleasesResponseTypeDef = TypedDict(
     "ListMobileSdkReleasesResponseTypeDef",
     {
         "ReleaseSummaries": List[ReleaseSummaryTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestInspectionTypeDef = TypedDict(
     "RequestInspectionTypeDef",
     {
         "PayloadType": PayloadTypeType,
@@ -1664,14 +1878,37 @@
     },
     total=False,
 )
 
 class ManagedRuleSetTypeDef(_RequiredManagedRuleSetTypeDef, _OptionalManagedRuleSetTypeDef):
     pass
 
+_RequiredRequestInspectionACFPTypeDef = TypedDict(
+    "_RequiredRequestInspectionACFPTypeDef",
+    {
+        "PayloadType": PayloadTypeType,
+    },
+)
+_OptionalRequestInspectionACFPTypeDef = TypedDict(
+    "_OptionalRequestInspectionACFPTypeDef",
+    {
+        "UsernameField": UsernameFieldTypeDef,
+        "PasswordField": PasswordFieldTypeDef,
+        "EmailField": EmailFieldTypeDef,
+        "PhoneNumberFields": Sequence[PhoneNumberFieldTypeDef],
+        "AddressFields": Sequence[AddressFieldTypeDef],
+    },
+    total=False,
+)
+
+class RequestInspectionACFPTypeDef(
+    _RequiredRequestInspectionACFPTypeDef, _OptionalRequestInspectionACFPTypeDef
+):
+    pass
+
 _RequiredPutManagedRuleSetVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutManagedRuleSetVersionsRequestRequestTypeDef",
     {
         "Name": str,
         "Scope": ScopeType,
         "Id": str,
         "LockToken": str,
@@ -1699,46 +1936,61 @@
         "Header": ResponseInspectionHeaderTypeDef,
         "BodyContains": ResponseInspectionBodyContainsTypeDef,
         "Json": ResponseInspectionJsonTypeDef,
     },
     total=False,
 )
 
+RateBasedStatementCustomKeyTypeDef = TypedDict(
+    "RateBasedStatementCustomKeyTypeDef",
+    {
+        "Header": RateLimitHeaderTypeDef,
+        "Cookie": RateLimitCookieTypeDef,
+        "QueryArgument": RateLimitQueryArgumentTypeDef,
+        "QueryString": RateLimitQueryStringTypeDef,
+        "HTTPMethod": Mapping[str, Any],
+        "ForwardedIP": Mapping[str, Any],
+        "IP": Mapping[str, Any],
+        "LabelNamespace": RateLimitLabelNamespaceTypeDef,
+    },
+    total=False,
+)
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Behavior": FilterBehaviorType,
         "Requirement": FilterRequirementType,
         "Conditions": List[ConditionTypeDef],
     },
 )
 
 GetMobileSdkReleaseResponseTypeDef = TypedDict(
     "GetMobileSdkReleaseResponseTypeDef",
     {
         "MobileSdkRelease": MobileSdkReleaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "NextMarker": str,
         "TagInfoForResource": TagInfoForResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegexPatternSetResponseTypeDef = TypedDict(
     "GetRegexPatternSetResponseTypeDef",
     {
         "RegexPatternSet": RegexPatternSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllowActionTypeDef = TypedDict(
     "AllowActionTypeDef",
     {
         "CustomRequestHandling": CustomRequestHandlingTypeDef,
@@ -1815,47 +2067,93 @@
         "UriPath": Mapping[str, Any],
         "QueryString": Mapping[str, Any],
         "Body": BodyTypeDef,
         "Method": Mapping[str, Any],
         "JsonBody": JsonBodyTypeDef,
         "Headers": HeadersTypeDef,
         "Cookies": CookiesTypeDef,
+        "HeaderOrder": HeaderOrderTypeDef,
     },
     total=False,
 )
 
 GetManagedRuleSetResponseTypeDef = TypedDict(
     "GetManagedRuleSetResponseTypeDef",
     {
         "ManagedRuleSet": ManagedRuleSetTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredAWSManagedRulesACFPRuleSetTypeDef = TypedDict(
+    "_RequiredAWSManagedRulesACFPRuleSetTypeDef",
+    {
+        "CreationPath": str,
+        "RegistrationPagePath": str,
+        "RequestInspection": RequestInspectionACFPTypeDef,
+    },
+)
+_OptionalAWSManagedRulesACFPRuleSetTypeDef = TypedDict(
+    "_OptionalAWSManagedRulesACFPRuleSetTypeDef",
+    {
+        "ResponseInspection": ResponseInspectionTypeDef,
+        "EnableRegexInPath": bool,
     },
+    total=False,
 )
 
+class AWSManagedRulesACFPRuleSetTypeDef(
+    _RequiredAWSManagedRulesACFPRuleSetTypeDef, _OptionalAWSManagedRulesACFPRuleSetTypeDef
+):
+    pass
+
 _RequiredAWSManagedRulesATPRuleSetTypeDef = TypedDict(
     "_RequiredAWSManagedRulesATPRuleSetTypeDef",
     {
         "LoginPath": str,
     },
 )
 _OptionalAWSManagedRulesATPRuleSetTypeDef = TypedDict(
     "_OptionalAWSManagedRulesATPRuleSetTypeDef",
     {
         "RequestInspection": RequestInspectionTypeDef,
         "ResponseInspection": ResponseInspectionTypeDef,
+        "EnableRegexInPath": bool,
     },
     total=False,
 )
 
 class AWSManagedRulesATPRuleSetTypeDef(
     _RequiredAWSManagedRulesATPRuleSetTypeDef, _OptionalAWSManagedRulesATPRuleSetTypeDef
 ):
     pass
 
+_RequiredRateBasedStatementTypeDef = TypedDict(
+    "_RequiredRateBasedStatementTypeDef",
+    {
+        "Limit": int,
+        "AggregateKeyType": RateBasedStatementAggregateKeyTypeType,
+    },
+)
+_OptionalRateBasedStatementTypeDef = TypedDict(
+    "_OptionalRateBasedStatementTypeDef",
+    {
+        "ScopeDownStatement": "StatementTypeDef",
+        "ForwardedIPConfig": ForwardedIPConfigTypeDef,
+        "CustomKeys": Sequence[RateBasedStatementCustomKeyTypeDef],
+    },
+    total=False,
+)
+
+class RateBasedStatementTypeDef(
+    _RequiredRateBasedStatementTypeDef, _OptionalRateBasedStatementTypeDef
+):
+    pass
+
 LoggingFilterTypeDef = TypedDict(
     "LoggingFilterTypeDef",
     {
         "Filters": List[FilterTypeDef],
         "DefaultBehavior": FilterBehaviorType,
     },
 )
@@ -1892,15 +2190,15 @@
 
 GetSampledRequestsResponseTypeDef = TypedDict(
     "GetSampledRequestsResponseTypeDef",
     {
         "SampledRequests": List[SampledHTTPRequestTypeDef],
         "PopulationSize": int,
         "TimeWindow": TimeWindowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ByteMatchStatementTypeDef = TypedDict(
     "ByteMatchStatementTypeDef",
     {
         "SearchString": Union[str, bytes, IO[Any], StreamingBody],
@@ -1971,14 +2269,15 @@
     {
         "LoginPath": str,
         "PayloadType": PayloadTypeType,
         "UsernameField": UsernameFieldTypeDef,
         "PasswordField": PasswordFieldTypeDef,
         "AWSManagedRulesBotControlRuleSet": AWSManagedRulesBotControlRuleSetTypeDef,
         "AWSManagedRulesATPRuleSet": AWSManagedRulesATPRuleSetTypeDef,
+        "AWSManagedRulesACFPRuleSet": AWSManagedRulesACFPRuleSetTypeDef,
     },
     total=False,
 )
 
 _RequiredLoggingConfigurationTypeDef = TypedDict(
     "_RequiredLoggingConfigurationTypeDef",
     {
@@ -2042,39 +2341,39 @@
 class RuleTypeDef(_RequiredRuleTypeDef, _OptionalRuleTypeDef):
     pass
 
 GetLoggingConfigurationResponseTypeDef = TypedDict(
     "GetLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLoggingConfigurationsResponseTypeDef = TypedDict(
     "ListLoggingConfigurationsResponseTypeDef",
     {
         "LoggingConfigurations": List[LoggingConfigurationTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "PutLoggingConfigurationRequestRequestTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
     },
 )
 
 PutLoggingConfigurationResponseTypeDef = TypedDict(
     "PutLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredManagedRuleGroupStatementTypeDef = TypedDict(
     "_RequiredManagedRuleGroupStatementTypeDef",
     {
         "VendorName": str,
@@ -2124,15 +2423,15 @@
         "VersionName": str,
         "SnsTopicArn": str,
         "Capacity": int,
         "Rules": List[RuleSummaryTypeDef],
         "LabelNamespace": str,
         "AvailableLabels": List[LabelSummaryTypeDef],
         "ConsumedLabels": List[LabelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CheckCapacityRequestRequestTypeDef = TypedDict(
     "CheckCapacityRequestRequestTypeDef",
     {
         "Scope": ScopeType,
@@ -2180,14 +2479,15 @@
         "Description": str,
         "Rules": Sequence[RuleTypeDef],
         "Tags": Sequence[TagTypeDef],
         "CustomResponseBodies": Mapping[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": Sequence[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 class CreateWebACLRequestRequestTypeDef(
     _RequiredCreateWebACLRequestRequestTypeDef, _OptionalCreateWebACLRequestRequestTypeDef
 ):
@@ -2260,14 +2560,15 @@
     {
         "Description": str,
         "Rules": Sequence[RuleTypeDef],
         "CustomResponseBodies": Mapping[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": Sequence[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 class UpdateWebACLRequestRequestTypeDef(
     _RequiredUpdateWebACLRequestRequestTypeDef, _OptionalUpdateWebACLRequestRequestTypeDef
 ):
@@ -2305,15 +2606,15 @@
 )
 
 GetRuleGroupResponseTypeDef = TypedDict(
     "GetRuleGroupResponseTypeDef",
     {
         "RuleGroup": RuleGroupTypeDef,
         "LockToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FirewallManagerRuleGroupTypeDef = TypedDict(
     "FirewallManagerRuleGroupTypeDef",
     {
         "Name": str,
@@ -2344,31 +2645,32 @@
         "PostProcessFirewallManagerRuleGroups": List[FirewallManagerRuleGroupTypeDef],
         "ManagedByFirewallManager": bool,
         "LabelNamespace": str,
         "CustomResponseBodies": Dict[str, CustomResponseBodyTypeDef],
         "CaptchaConfig": CaptchaConfigTypeDef,
         "ChallengeConfig": ChallengeConfigTypeDef,
         "TokenDomains": List[str],
+        "AssociationConfig": AssociationConfigTypeDef,
     },
     total=False,
 )
 
 class WebACLTypeDef(_RequiredWebACLTypeDef, _OptionalWebACLTypeDef):
     pass
 
 GetWebACLForResourceResponseTypeDef = TypedDict(
     "GetWebACLForResourceResponseTypeDef",
     {
         "WebACL": WebACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWebACLResponseTypeDef = TypedDict(
     "GetWebACLResponseTypeDef",
     {
         "WebACL": WebACLTypeDef,
         "LockToken": str,
         "ApplicationIntegrationURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/PKG-INFO` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-wafv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WAFV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WAFV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-wafv2"></a>
 
 # types-aiobotocore-wafv2
 
 [![PyPI - types-aiobotocore-wafv2](https://img.shields.io/pypi/v/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wafv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wafv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wafv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-wafv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WAFV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
+[aiobotocore.WAFV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
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
 [types-aiobotocore-wafv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wafv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -268,14 +268,15 @@
 
 `types_aiobotocore_wafv2.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_wafv2.literals import (
     ActionValueType,
+    AssociatedResourceTypeType,
     BodyParsingFallbackBehaviorType,
     ComparisonOperatorType,
     CountryCodeType,
     FailureReasonType,
     FallbackBehaviorType,
     FilterBehaviorType,
     FilterRequirementType,
@@ -290,14 +291,15 @@
     PlatformType,
     PositionalConstraintType,
     RateBasedStatementAggregateKeyTypeType,
     ResourceTypeType,
     ResponseContentTypeType,
     ScopeType,
     SensitivityLevelType,
+    SizeInspectionLimitType,
     TextTransformationTypeType,
     WAFV2ServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -311,111 +313,132 @@
 ### Typed dictionaries
 
 `types_aiobotocore_wafv2.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_wafv2.type_defs import (
+    APIKeySummaryTypeDef,
     AWSManagedRulesBotControlRuleSetTypeDef,
     ActionConditionTypeDef,
+    AddressFieldTypeDef,
     AndStatementTypeDef,
     AssociateWebACLRequestRequestTypeDef,
+    RequestBodyAssociatedResourceTypeConfigTypeDef,
     BodyTypeDef,
     TextTransformationTypeDef,
     ImmunityTimePropertyTypeDef,
     CaptchaResponseTypeDef,
     ChallengeResponseTypeDef,
-    ResponseMetadataTypeDef,
+    CheckCapacityResponseTypeDef,
     LabelNameConditionTypeDef,
     CookieMatchPatternTypeDef,
+    CreateAPIKeyRequestRequestTypeDef,
+    CreateAPIKeyResponseTypeDef,
     TagTypeDef,
     IPSetSummaryTypeDef,
     RegexTypeDef,
     RegexPatternSetSummaryTypeDef,
     CustomResponseBodyTypeDef,
     VisibilityConfigTypeDef,
     RuleGroupSummaryTypeDef,
     WebACLSummaryTypeDef,
     CustomHTTPHeaderTypeDef,
     DeleteFirewallManagerRuleGroupsRequestRequestTypeDef,
+    DeleteFirewallManagerRuleGroupsResponseTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeletePermissionPolicyRequestRequestTypeDef,
     DeleteRegexPatternSetRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
     DeleteWebACLRequestRequestTypeDef,
+    DescribeAllManagedProductsRequestRequestTypeDef,
+    ManagedProductDescriptorTypeDef,
+    DescribeManagedProductsByVendorRequestRequestTypeDef,
     DescribeManagedRuleGroupRequestRequestTypeDef,
     LabelSummaryTypeDef,
     DisassociateWebACLRequestRequestTypeDef,
+    EmailFieldTypeDef,
     ExcludedRuleTypeDef,
+    HeaderOrderTypeDef,
     SingleHeaderTypeDef,
     SingleQueryArgumentTypeDef,
     ForwardedIPConfigTypeDef,
     GenerateMobileSdkReleaseUrlRequestRequestTypeDef,
+    GenerateMobileSdkReleaseUrlResponseTypeDef,
+    GetDecryptedAPIKeyRequestRequestTypeDef,
+    GetDecryptedAPIKeyResponseTypeDef,
     GetIPSetRequestRequestTypeDef,
     IPSetTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetManagedRuleSetRequestRequestTypeDef,
     GetMobileSdkReleaseRequestRequestTypeDef,
     GetPermissionPolicyRequestRequestTypeDef,
+    GetPermissionPolicyResponseTypeDef,
     GetRateBasedStatementManagedKeysRequestRequestTypeDef,
     RateBasedStatementManagedKeysIPSetTypeDef,
     GetRegexPatternSetRequestRequestTypeDef,
     GetRuleGroupRequestRequestTypeDef,
     TimeWindowTypeDef,
     GetWebACLForResourceRequestRequestTypeDef,
     GetWebACLRequestRequestTypeDef,
     HTTPHeaderTypeDef,
     HeaderMatchPatternTypeDef,
     IPSetForwardedIPConfigTypeDef,
     JsonMatchPatternTypeDef,
     LabelMatchStatementTypeDef,
     LabelTypeDef,
+    ListAPIKeysRequestRequestTypeDef,
     ListAvailableManagedRuleGroupVersionsRequestRequestTypeDef,
     ManagedRuleGroupVersionTypeDef,
     ListAvailableManagedRuleGroupsRequestRequestTypeDef,
     ManagedRuleGroupSummaryTypeDef,
     ListIPSetsRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListManagedRuleSetsRequestRequestTypeDef,
     ManagedRuleSetSummaryTypeDef,
     ListMobileSdkReleasesRequestRequestTypeDef,
     ReleaseSummaryTypeDef,
     ListRegexPatternSetsRequestRequestTypeDef,
     ListResourcesForWebACLRequestRequestTypeDef,
+    ListResourcesForWebACLResponseTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListWebACLsRequestRequestTypeDef,
     PasswordFieldTypeDef,
     UsernameFieldTypeDef,
     ManagedRuleSetVersionTypeDef,
     NotStatementTypeDef,
     OrStatementTypeDef,
+    PhoneNumberFieldTypeDef,
     VersionToPublishTypeDef,
+    PutManagedRuleSetVersionsResponseTypeDef,
     PutPermissionPolicyRequestRequestTypeDef,
+    RateLimitLabelNamespaceTypeDef,
     ResponseInspectionBodyContainsTypeDef,
     ResponseInspectionHeaderTypeDef,
     ResponseInspectionJsonTypeDef,
     ResponseInspectionStatusCodeTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
-    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
-    CaptchaConfigTypeDef,
-    ChallengeConfigTypeDef,
-    CheckCapacityResponseTypeDef,
-    DeleteFirewallManagerRuleGroupsResponseTypeDef,
-    GenerateMobileSdkReleaseUrlResponseTypeDef,
-    GetPermissionPolicyResponseTypeDef,
-    ListResourcesForWebACLResponseTypeDef,
-    PutManagedRuleSetVersionsResponseTypeDef,
     UpdateIPSetResponseTypeDef,
+    UpdateManagedRuleSetVersionExpiryDateRequestRequestTypeDef,
     UpdateManagedRuleSetVersionExpiryDateResponseTypeDef,
     UpdateRegexPatternSetResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     UpdateWebACLResponseTypeDef,
+    ListAPIKeysResponseTypeDef,
+    AssociationConfigTypeDef,
+    RateLimitCookieTypeDef,
+    RateLimitHeaderTypeDef,
+    RateLimitQueryArgumentTypeDef,
+    RateLimitQueryStringTypeDef,
+    CaptchaConfigTypeDef,
+    ChallengeConfigTypeDef,
     ConditionTypeDef,
     CookiesTypeDef,
     CreateIPSetRequestRequestTypeDef,
     MobileSdkReleaseTypeDef,
     TagInfoForResourceTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateIPSetResponseTypeDef,
@@ -427,44 +450,49 @@
     ListRegexPatternSetsResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     CreateWebACLResponseTypeDef,
     ListWebACLsResponseTypeDef,
     CustomRequestHandlingTypeDef,
     CustomResponseTypeDef,
+    DescribeAllManagedProductsResponseTypeDef,
+    DescribeManagedProductsByVendorResponseTypeDef,
     GeoMatchStatementTypeDef,
-    RateBasedStatementTypeDef,
     GetIPSetResponseTypeDef,
     GetRateBasedStatementManagedKeysResponseTypeDef,
     GetSampledRequestsRequestRequestTypeDef,
     HTTPRequestTypeDef,
     HeadersTypeDef,
     IPSetReferenceStatementTypeDef,
     JsonBodyTypeDef,
     ListAvailableManagedRuleGroupVersionsResponseTypeDef,
     ListAvailableManagedRuleGroupsResponseTypeDef,
     ListManagedRuleSetsResponseTypeDef,
     ListMobileSdkReleasesResponseTypeDef,
     RequestInspectionTypeDef,
     ManagedRuleSetTypeDef,
+    RequestInspectionACFPTypeDef,
     PutManagedRuleSetVersionsRequestRequestTypeDef,
     ResponseInspectionTypeDef,
+    RateBasedStatementCustomKeyTypeDef,
     FilterTypeDef,
     GetMobileSdkReleaseResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     GetRegexPatternSetResponseTypeDef,
     AllowActionTypeDef,
     CaptchaActionTypeDef,
     ChallengeActionTypeDef,
     CountActionTypeDef,
     BlockActionTypeDef,
     SampledHTTPRequestTypeDef,
     FieldToMatchTypeDef,
     GetManagedRuleSetResponseTypeDef,
+    AWSManagedRulesACFPRuleSetTypeDef,
     AWSManagedRulesATPRuleSetTypeDef,
+    RateBasedStatementTypeDef,
     LoggingFilterTypeDef,
     OverrideActionTypeDef,
     DefaultActionTypeDef,
     RuleActionTypeDef,
     GetSampledRequestsResponseTypeDef,
     ByteMatchStatementTypeDef,
     RegexMatchStatementTypeDef,
@@ -496,54 +524,54 @@
     FirewallManagerRuleGroupTypeDef,
     WebACLTypeDef,
     GetWebACLForResourceResponseTypeDef,
     GetWebACLResponseTypeDef,
 )
 
 
-def get_structure() -> AWSManagedRulesBotControlRuleSetTypeDef:
+def get_structure() -> APIKeySummaryTypeDef:
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

### Comparing `types-aiobotocore-wafv2-2.5.0.post1/types_aiobotocore_wafv2.egg-info/SOURCES.txt` & `types-aiobotocore-wafv2-2.5.1/types_aiobotocore_wafv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

