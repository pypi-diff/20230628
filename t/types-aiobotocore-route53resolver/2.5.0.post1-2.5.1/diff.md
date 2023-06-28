# Comparing `tmp/types-aiobotocore-route53resolver-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53resolver-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53resolver-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53resolver-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-route53resolver-2.5.0.post1.tar` & `types-aiobotocore-route53resolver-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.327578 types-aiobotocore-route53resolver-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    25047 2023-03-11 12:27:15.323578 types-aiobotocore-route53resolver-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    23444 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.327578 types-aiobotocore-route53resolver-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.319579 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/
--rw-r--r--   0 runner    (1001) docker     (123)     4341 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4340 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    57838 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    57751 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13246 2023-03-11 12:22:48.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13244 2023-03-11 12:22:45.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20531 2023-03-11 12:22:45.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    20513 2023-03-11 12:22:45.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    56643 2023-03-11 12:22:49.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    56600 2023-03-11 12:22:48.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:44.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.323578 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    25047 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:27:15.000000 types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.666204 types-aiobotocore-route53resolver-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    25105 2023-06-28 01:44:05.666204 types-aiobotocore-route53resolver-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23508 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.666204 types-aiobotocore-route53resolver-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2174 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.662204 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/
+-rw-r--r--   0 runner    (1001) docker     (123)     4341 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4340 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58137 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58050 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13933 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13931 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    20441 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20424 2023-06-28 01:39:32.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    57085 2023-06-28 01:39:35.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57044 2023-06-28 01:39:33.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:31.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.666204 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    25105 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:44:05.000000 types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/LICENSE` & `types-aiobotocore-route53resolver-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53resolver-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53resolver
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53Resolver 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53Resolver 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53resolver"></a>
 
 # types-aiobotocore-route53resolver
 
 [![PyPI - types-aiobotocore-route53resolver](https://img.shields.io/pypi/v/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53resolver?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53resolver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Resolver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
+[aiobotocore.Route53Resolver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
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
 [types-aiobotocore-route53resolver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -383,14 +383,15 @@
     ListResolverRulesPaginatorName,
     ListTagsForResourcePaginatorName,
     MutationProtectionStatusType,
     ResolverAutodefinedReverseStatusType,
     ResolverDNSSECValidationStatusType,
     ResolverEndpointDirectionType,
     ResolverEndpointStatusType,
+    ResolverEndpointTypeType,
     ResolverQueryLogConfigAssociationErrorType,
     ResolverQueryLogConfigAssociationStatusType,
     ResolverQueryLogConfigStatusType,
     ResolverRuleAssociationStatusType,
     ResolverRuleStatusType,
     RuleTypeOptionType,
     ShareStatusType,
@@ -415,15 +416,14 @@
 `types_aiobotocore_route53resolver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53resolver.type_defs import (
     TagTypeDef,
     FirewallRuleGroupAssociationTypeDef,
-    ResponseMetadataTypeDef,
     IpAddressUpdateTypeDef,
     ResolverEndpointTypeDef,
     AssociateResolverQueryLogConfigRequestRequestTypeDef,
     ResolverQueryLogConfigAssociationTypeDef,
     AssociateResolverRuleRequestRequestTypeDef,
     ResolverRuleAssociationTypeDef,
     FirewallDomainListTypeDef,
@@ -446,68 +446,78 @@
     FirewallConfigTypeDef,
     FirewallDomainListMetadataTypeDef,
     FirewallRuleGroupMetadataTypeDef,
     GetFirewallConfigRequestRequestTypeDef,
     GetFirewallDomainListRequestRequestTypeDef,
     GetFirewallRuleGroupAssociationRequestRequestTypeDef,
     GetFirewallRuleGroupPolicyRequestRequestTypeDef,
+    GetFirewallRuleGroupPolicyResponseTypeDef,
     GetFirewallRuleGroupRequestRequestTypeDef,
     GetResolverConfigRequestRequestTypeDef,
     ResolverConfigTypeDef,
     GetResolverDnssecConfigRequestRequestTypeDef,
     ResolverDnssecConfigTypeDef,
     GetResolverEndpointRequestRequestTypeDef,
     GetResolverQueryLogConfigAssociationRequestRequestTypeDef,
     GetResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    GetResolverQueryLogConfigPolicyResponseTypeDef,
     GetResolverQueryLogConfigRequestRequestTypeDef,
     GetResolverRuleAssociationRequestRequestTypeDef,
     GetResolverRulePolicyRequestRequestTypeDef,
+    GetResolverRulePolicyResponseTypeDef,
     GetResolverRuleRequestRequestTypeDef,
     ImportFirewallDomainsRequestRequestTypeDef,
+    ImportFirewallDomainsResponseTypeDef,
     IpAddressResponseTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
     ListFirewallConfigsRequestRequestTypeDef,
+    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
     ListFirewallDomainListsRequestRequestTypeDef,
+    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
     ListFirewallDomainsRequestRequestTypeDef,
+    ListFirewallDomainsResponseTypeDef,
+    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
     ListFirewallRuleGroupAssociationsRequestRequestTypeDef,
+    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
     ListFirewallRuleGroupsRequestRequestTypeDef,
+    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
     ListFirewallRulesRequestRequestTypeDef,
+    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
     ListResolverConfigsRequestRequestTypeDef,
+    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
     ListResolverEndpointIpAddressesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutFirewallRuleGroupPolicyRequestRequestTypeDef,
+    PutFirewallRuleGroupPolicyResponseTypeDef,
     PutResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    PutResolverQueryLogConfigPolicyResponseTypeDef,
     PutResolverRulePolicyRequestRequestTypeDef,
+    PutResolverRulePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallConfigRequestRequestTypeDef,
     UpdateFirewallDomainsRequestRequestTypeDef,
+    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
     UpdateFirewallRuleRequestRequestTypeDef,
+    UpdateIpAddressTypeDef,
     UpdateResolverConfigRequestRequestTypeDef,
     UpdateResolverDnssecConfigRequestRequestTypeDef,
-    UpdateResolverEndpointRequestRequestTypeDef,
     AssociateFirewallRuleGroupRequestRequestTypeDef,
     CreateFirewallDomainListRequestRequestTypeDef,
     CreateFirewallRuleGroupRequestRequestTypeDef,
     CreateResolverQueryLogConfigRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     AssociateFirewallRuleGroupResponseTypeDef,
     DisassociateFirewallRuleGroupResponseTypeDef,
     GetFirewallRuleGroupAssociationResponseTypeDef,
-    GetFirewallRuleGroupPolicyResponseTypeDef,
-    GetResolverQueryLogConfigPolicyResponseTypeDef,
-    GetResolverRulePolicyResponseTypeDef,
-    ImportFirewallDomainsResponseTypeDef,
-    ListFirewallDomainsResponseTypeDef,
     ListFirewallRuleGroupAssociationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutFirewallRuleGroupPolicyResponseTypeDef,
-    PutResolverQueryLogConfigPolicyResponseTypeDef,
-    PutResolverRulePolicyResponseTypeDef,
-    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationResponseTypeDef,
     AssociateResolverEndpointIpAddressRequestRequestTypeDef,
     DisassociateResolverEndpointIpAddressRequestRequestTypeDef,
     AssociateResolverEndpointIpAddressResponseTypeDef,
     CreateResolverEndpointResponseTypeDef,
     DeleteResolverEndpointResponseTypeDef,
     DisassociateResolverEndpointIpAddressResponseTypeDef,
@@ -536,47 +546,39 @@
     CreateResolverQueryLogConfigResponseTypeDef,
     DeleteResolverQueryLogConfigResponseTypeDef,
     GetResolverQueryLogConfigResponseTypeDef,
     ListResolverQueryLogConfigsResponseTypeDef,
     CreateResolverRuleRequestRequestTypeDef,
     ResolverRuleConfigTypeDef,
     ResolverRuleTypeDef,
+    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
     ListResolverDnssecConfigsRequestRequestTypeDef,
+    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
     ListResolverEndpointsRequestRequestTypeDef,
+    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
     ListResolverQueryLogConfigAssociationsRequestRequestTypeDef,
+    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
     ListResolverQueryLogConfigsRequestRequestTypeDef,
+    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
     ListResolverRuleAssociationsRequestRequestTypeDef,
+    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
     ListResolverRulesRequestRequestTypeDef,
     GetFirewallConfigResponseTypeDef,
     ListFirewallConfigsResponseTypeDef,
     UpdateFirewallConfigResponseTypeDef,
     ListFirewallDomainListsResponseTypeDef,
     ListFirewallRuleGroupsResponseTypeDef,
     GetResolverConfigResponseTypeDef,
     ListResolverConfigsResponseTypeDef,
     UpdateResolverConfigResponseTypeDef,
     GetResolverDnssecConfigResponseTypeDef,
     ListResolverDnssecConfigsResponseTypeDef,
     UpdateResolverDnssecConfigResponseTypeDef,
     ListResolverEndpointIpAddressesResponseTypeDef,
-    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
-    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
-    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
-    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
-    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
-    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
-    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
-    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
-    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
-    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
-    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    UpdateResolverEndpointRequestRequestTypeDef,
     UpdateResolverRuleRequestRequestTypeDef,
     CreateResolverRuleResponseTypeDef,
     DeleteResolverRuleResponseTypeDef,
     GetResolverRuleResponseTypeDef,
     ListResolverRulesResponseTypeDef,
     UpdateResolverRuleResponseTypeDef,
 )
@@ -589,43 +591,43 @@
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/README.md` & `types-aiobotocore-route53resolver-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53resolver"></a>
 
 # types-aiobotocore-route53resolver
 
 [![PyPI - types-aiobotocore-route53resolver](https://img.shields.io/pypi/v/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53resolver?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53resolver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Resolver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
+[aiobotocore.Route53Resolver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
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
 [types-aiobotocore-route53resolver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,14 +350,15 @@
     ListResolverRulesPaginatorName,
     ListTagsForResourcePaginatorName,
     MutationProtectionStatusType,
     ResolverAutodefinedReverseStatusType,
     ResolverDNSSECValidationStatusType,
     ResolverEndpointDirectionType,
     ResolverEndpointStatusType,
+    ResolverEndpointTypeType,
     ResolverQueryLogConfigAssociationErrorType,
     ResolverQueryLogConfigAssociationStatusType,
     ResolverQueryLogConfigStatusType,
     ResolverRuleAssociationStatusType,
     ResolverRuleStatusType,
     RuleTypeOptionType,
     ShareStatusType,
@@ -382,15 +383,14 @@
 `types_aiobotocore_route53resolver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53resolver.type_defs import (
     TagTypeDef,
     FirewallRuleGroupAssociationTypeDef,
-    ResponseMetadataTypeDef,
     IpAddressUpdateTypeDef,
     ResolverEndpointTypeDef,
     AssociateResolverQueryLogConfigRequestRequestTypeDef,
     ResolverQueryLogConfigAssociationTypeDef,
     AssociateResolverRuleRequestRequestTypeDef,
     ResolverRuleAssociationTypeDef,
     FirewallDomainListTypeDef,
@@ -413,68 +413,78 @@
     FirewallConfigTypeDef,
     FirewallDomainListMetadataTypeDef,
     FirewallRuleGroupMetadataTypeDef,
     GetFirewallConfigRequestRequestTypeDef,
     GetFirewallDomainListRequestRequestTypeDef,
     GetFirewallRuleGroupAssociationRequestRequestTypeDef,
     GetFirewallRuleGroupPolicyRequestRequestTypeDef,
+    GetFirewallRuleGroupPolicyResponseTypeDef,
     GetFirewallRuleGroupRequestRequestTypeDef,
     GetResolverConfigRequestRequestTypeDef,
     ResolverConfigTypeDef,
     GetResolverDnssecConfigRequestRequestTypeDef,
     ResolverDnssecConfigTypeDef,
     GetResolverEndpointRequestRequestTypeDef,
     GetResolverQueryLogConfigAssociationRequestRequestTypeDef,
     GetResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    GetResolverQueryLogConfigPolicyResponseTypeDef,
     GetResolverQueryLogConfigRequestRequestTypeDef,
     GetResolverRuleAssociationRequestRequestTypeDef,
     GetResolverRulePolicyRequestRequestTypeDef,
+    GetResolverRulePolicyResponseTypeDef,
     GetResolverRuleRequestRequestTypeDef,
     ImportFirewallDomainsRequestRequestTypeDef,
+    ImportFirewallDomainsResponseTypeDef,
     IpAddressResponseTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
     ListFirewallConfigsRequestRequestTypeDef,
+    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
     ListFirewallDomainListsRequestRequestTypeDef,
+    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
     ListFirewallDomainsRequestRequestTypeDef,
+    ListFirewallDomainsResponseTypeDef,
+    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
     ListFirewallRuleGroupAssociationsRequestRequestTypeDef,
+    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
     ListFirewallRuleGroupsRequestRequestTypeDef,
+    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
     ListFirewallRulesRequestRequestTypeDef,
+    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
     ListResolverConfigsRequestRequestTypeDef,
+    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
     ListResolverEndpointIpAddressesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutFirewallRuleGroupPolicyRequestRequestTypeDef,
+    PutFirewallRuleGroupPolicyResponseTypeDef,
     PutResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    PutResolverQueryLogConfigPolicyResponseTypeDef,
     PutResolverRulePolicyRequestRequestTypeDef,
+    PutResolverRulePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallConfigRequestRequestTypeDef,
     UpdateFirewallDomainsRequestRequestTypeDef,
+    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
     UpdateFirewallRuleRequestRequestTypeDef,
+    UpdateIpAddressTypeDef,
     UpdateResolverConfigRequestRequestTypeDef,
     UpdateResolverDnssecConfigRequestRequestTypeDef,
-    UpdateResolverEndpointRequestRequestTypeDef,
     AssociateFirewallRuleGroupRequestRequestTypeDef,
     CreateFirewallDomainListRequestRequestTypeDef,
     CreateFirewallRuleGroupRequestRequestTypeDef,
     CreateResolverQueryLogConfigRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     AssociateFirewallRuleGroupResponseTypeDef,
     DisassociateFirewallRuleGroupResponseTypeDef,
     GetFirewallRuleGroupAssociationResponseTypeDef,
-    GetFirewallRuleGroupPolicyResponseTypeDef,
-    GetResolverQueryLogConfigPolicyResponseTypeDef,
-    GetResolverRulePolicyResponseTypeDef,
-    ImportFirewallDomainsResponseTypeDef,
-    ListFirewallDomainsResponseTypeDef,
     ListFirewallRuleGroupAssociationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutFirewallRuleGroupPolicyResponseTypeDef,
-    PutResolverQueryLogConfigPolicyResponseTypeDef,
-    PutResolverRulePolicyResponseTypeDef,
-    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationResponseTypeDef,
     AssociateResolverEndpointIpAddressRequestRequestTypeDef,
     DisassociateResolverEndpointIpAddressRequestRequestTypeDef,
     AssociateResolverEndpointIpAddressResponseTypeDef,
     CreateResolverEndpointResponseTypeDef,
     DeleteResolverEndpointResponseTypeDef,
     DisassociateResolverEndpointIpAddressResponseTypeDef,
@@ -503,47 +513,39 @@
     CreateResolverQueryLogConfigResponseTypeDef,
     DeleteResolverQueryLogConfigResponseTypeDef,
     GetResolverQueryLogConfigResponseTypeDef,
     ListResolverQueryLogConfigsResponseTypeDef,
     CreateResolverRuleRequestRequestTypeDef,
     ResolverRuleConfigTypeDef,
     ResolverRuleTypeDef,
+    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
     ListResolverDnssecConfigsRequestRequestTypeDef,
+    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
     ListResolverEndpointsRequestRequestTypeDef,
+    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
     ListResolverQueryLogConfigAssociationsRequestRequestTypeDef,
+    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
     ListResolverQueryLogConfigsRequestRequestTypeDef,
+    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
     ListResolverRuleAssociationsRequestRequestTypeDef,
+    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
     ListResolverRulesRequestRequestTypeDef,
     GetFirewallConfigResponseTypeDef,
     ListFirewallConfigsResponseTypeDef,
     UpdateFirewallConfigResponseTypeDef,
     ListFirewallDomainListsResponseTypeDef,
     ListFirewallRuleGroupsResponseTypeDef,
     GetResolverConfigResponseTypeDef,
     ListResolverConfigsResponseTypeDef,
     UpdateResolverConfigResponseTypeDef,
     GetResolverDnssecConfigResponseTypeDef,
     ListResolverDnssecConfigsResponseTypeDef,
     UpdateResolverDnssecConfigResponseTypeDef,
     ListResolverEndpointIpAddressesResponseTypeDef,
-    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
-    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
-    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
-    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
-    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
-    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
-    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
-    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
-    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
-    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
-    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    UpdateResolverEndpointRequestRequestTypeDef,
     UpdateResolverRuleRequestRequestTypeDef,
     CreateResolverRuleResponseTypeDef,
     DeleteResolverRuleResponseTypeDef,
     GetResolverRuleResponseTypeDef,
     ListResolverRulesResponseTypeDef,
     UpdateResolverRuleResponseTypeDef,
 )
@@ -556,43 +558,43 @@
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/setup.py` & `types-aiobotocore-route53resolver-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53resolver.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53resolver",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53resolver"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53Resolver 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Route53Resolver 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/"
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__init__.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__init__.pyi` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/__main__.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Route53Resolver 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Route53Resolver 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver\nOther"
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/client.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     AutodefinedReverseFlagType,
     BlockResponseType,
     FirewallDomainUpdateOperationType,
     FirewallFailOpenStatusType,
     FirewallRuleGroupAssociationStatusType,
     MutationProtectionStatusType,
     ResolverEndpointDirectionType,
+    ResolverEndpointTypeType,
     RuleTypeOptionType,
     SortOrderType,
     ValidationType,
 )
 from .paginator import (
     ListFirewallConfigsPaginator,
     ListFirewallDomainListsPaginator,
@@ -110,14 +111,15 @@
     ResolverRuleConfigTypeDef,
     TagTypeDef,
     TargetAddressTypeDef,
     UpdateFirewallConfigResponseTypeDef,
     UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationResponseTypeDef,
     UpdateFirewallRuleResponseTypeDef,
+    UpdateIpAddressTypeDef,
     UpdateResolverConfigResponseTypeDef,
     UpdateResolverDnssecConfigResponseTypeDef,
     UpdateResolverEndpointResponseTypeDef,
     UpdateResolverRuleResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -286,15 +288,16 @@
         self,
         *,
         CreatorRequestId: str,
         SecurityGroupIds: Sequence[str],
         Direction: ResolverEndpointDirectionType,
         IpAddresses: Sequence[IpAddressRequestTypeDef],
         Name: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        ResolverEndpointType: ResolverEndpointTypeType = ...
     ) -> CreateResolverEndpointResponseTypeDef:
         """
         Creates a Resolver endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_resolver_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#create_resolver_endpoint)
         """
@@ -918,18 +921,24 @@
         Updates an existing DNSSEC validation configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_dnssec_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#update_resolver_dnssec_config)
         """
 
     async def update_resolver_endpoint(
-        self, *, ResolverEndpointId: str, Name: str = ...
+        self,
+        *,
+        ResolverEndpointId: str,
+        Name: str = ...,
+        ResolverEndpointType: ResolverEndpointTypeType = ...,
+        UpdateIpAddresses: Sequence[UpdateIpAddressTypeDef] = ...
     ) -> UpdateResolverEndpointResponseTypeDef:
         """
-        Updates the name of an inbound or an outbound Resolver endpoint.
+        Updates the name, or enpoint type for an inbound or an outbound Resolver
+        endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#update_resolver_endpoint)
         """
 
     async def update_resolver_rule(
         self, *, ResolverRuleId: str, Config: ResolverRuleConfigTypeDef
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/client.pyi` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     AutodefinedReverseFlagType,
     BlockResponseType,
     FirewallDomainUpdateOperationType,
     FirewallFailOpenStatusType,
     FirewallRuleGroupAssociationStatusType,
     MutationProtectionStatusType,
     ResolverEndpointDirectionType,
+    ResolverEndpointTypeType,
     RuleTypeOptionType,
     SortOrderType,
     ValidationType,
 )
 from .paginator import (
     ListFirewallConfigsPaginator,
     ListFirewallDomainListsPaginator,
@@ -110,14 +111,15 @@
     ResolverRuleConfigTypeDef,
     TagTypeDef,
     TargetAddressTypeDef,
     UpdateFirewallConfigResponseTypeDef,
     UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationResponseTypeDef,
     UpdateFirewallRuleResponseTypeDef,
+    UpdateIpAddressTypeDef,
     UpdateResolverConfigResponseTypeDef,
     UpdateResolverDnssecConfigResponseTypeDef,
     UpdateResolverEndpointResponseTypeDef,
     UpdateResolverRuleResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -272,15 +274,16 @@
         self,
         *,
         CreatorRequestId: str,
         SecurityGroupIds: Sequence[str],
         Direction: ResolverEndpointDirectionType,
         IpAddresses: Sequence[IpAddressRequestTypeDef],
         Name: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        ResolverEndpointType: ResolverEndpointTypeType = ...
     ) -> CreateResolverEndpointResponseTypeDef:
         """
         Creates a Resolver endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.create_resolver_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#create_resolver_endpoint)
         """
@@ -849,18 +852,24 @@
         """
         Updates an existing DNSSEC validation configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_dnssec_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#update_resolver_dnssec_config)
         """
     async def update_resolver_endpoint(
-        self, *, ResolverEndpointId: str, Name: str = ...
+        self,
+        *,
+        ResolverEndpointId: str,
+        Name: str = ...,
+        ResolverEndpointType: ResolverEndpointTypeType = ...,
+        UpdateIpAddresses: Sequence[UpdateIpAddressTypeDef] = ...
     ) -> UpdateResolverEndpointResponseTypeDef:
         """
-        Updates the name of an inbound or an outbound Resolver endpoint.
+        Updates the name, or enpoint type for an inbound or an outbound Resolver
+        endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Client.update_resolver_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/client/#update_resolver_endpoint)
         """
     async def update_resolver_rule(
         self, *, ResolverRuleId: str, Config: ResolverRuleConfigTypeDef
     ) -> UpdateResolverRuleResponseTypeDef:
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/literals.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -47,14 +47,15 @@
     "ListResolverRulesPaginatorName",
     "ListTagsForResourcePaginatorName",
     "MutationProtectionStatusType",
     "ResolverAutodefinedReverseStatusType",
     "ResolverDNSSECValidationStatusType",
     "ResolverEndpointDirectionType",
     "ResolverEndpointStatusType",
+    "ResolverEndpointTypeType",
     "ResolverQueryLogConfigAssociationErrorType",
     "ResolverQueryLogConfigAssociationStatusType",
     "ResolverQueryLogConfigStatusType",
     "ResolverRuleAssociationStatusType",
     "ResolverRuleStatusType",
     "RuleTypeOptionType",
     "ShareStatusType",
@@ -65,36 +66,37 @@
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 ActionType = Literal["ALERT", "ALLOW", "BLOCK"]
-AutodefinedReverseFlagType = Literal["DISABLE", "ENABLE"]
+AutodefinedReverseFlagType = Literal["DISABLE", "ENABLE", "USE_LOCAL_RESOURCE_SETTING"]
 BlockOverrideDnsTypeType = Literal["CNAME"]
 BlockResponseType = Literal["NODATA", "NXDOMAIN", "OVERRIDE"]
 FirewallDomainImportOperationType = Literal["REPLACE"]
 FirewallDomainListStatusType = Literal[
     "COMPLETE", "COMPLETE_IMPORT_FAILED", "DELETING", "IMPORTING", "UPDATING"
 ]
 FirewallDomainUpdateOperationType = Literal["ADD", "REMOVE", "REPLACE"]
-FirewallFailOpenStatusType = Literal["DISABLED", "ENABLED"]
+FirewallFailOpenStatusType = Literal["DISABLED", "ENABLED", "USE_LOCAL_RESOURCE_SETTING"]
 FirewallRuleGroupAssociationStatusType = Literal["COMPLETE", "DELETING", "UPDATING"]
 FirewallRuleGroupStatusType = Literal["COMPLETE", "DELETING", "UPDATING"]
 IpAddressStatusType = Literal[
     "ATTACHED",
     "ATTACHING",
     "CREATING",
     "DELETE_FAILED_FAS_EXPIRED",
     "DELETING",
     "DETACHING",
     "FAILED_CREATION",
     "FAILED_RESOURCE_GONE",
     "REMAP_ATTACHING",
     "REMAP_DETACHING",
+    "UPDATING",
 ]
 ListFirewallConfigsPaginatorName = Literal["list_firewall_configs"]
 ListFirewallDomainListsPaginatorName = Literal["list_firewall_domain_lists"]
 ListFirewallDomainsPaginatorName = Literal["list_firewall_domains"]
 ListFirewallRuleGroupAssociationsPaginatorName = Literal["list_firewall_rule_group_associations"]
 ListFirewallRuleGroupsPaginatorName = Literal["list_firewall_rule_groups"]
 ListFirewallRulesPaginatorName = Literal["list_firewall_rules"]
@@ -106,35 +108,50 @@
     "list_resolver_query_log_config_associations"
 ]
 ListResolverQueryLogConfigsPaginatorName = Literal["list_resolver_query_log_configs"]
 ListResolverRuleAssociationsPaginatorName = Literal["list_resolver_rule_associations"]
 ListResolverRulesPaginatorName = Literal["list_resolver_rules"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 MutationProtectionStatusType = Literal["DISABLED", "ENABLED"]
-ResolverAutodefinedReverseStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
-ResolverDNSSECValidationStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
+ResolverAutodefinedReverseStatusType = Literal[
+    "DISABLED",
+    "DISABLING",
+    "ENABLED",
+    "ENABLING",
+    "UPDATING_TO_USE_LOCAL_RESOURCE_SETTING",
+    "USE_LOCAL_RESOURCE_SETTING",
+]
+ResolverDNSSECValidationStatusType = Literal[
+    "DISABLED",
+    "DISABLING",
+    "ENABLED",
+    "ENABLING",
+    "UPDATING_TO_USE_LOCAL_RESOURCE_SETTING",
+    "USE_LOCAL_RESOURCE_SETTING",
+]
 ResolverEndpointDirectionType = Literal["INBOUND", "OUTBOUND"]
 ResolverEndpointStatusType = Literal[
     "ACTION_NEEDED", "AUTO_RECOVERING", "CREATING", "DELETING", "OPERATIONAL", "UPDATING"
 ]
+ResolverEndpointTypeType = Literal["DUALSTACK", "IPV4", "IPV6"]
 ResolverQueryLogConfigAssociationErrorType = Literal[
     "ACCESS_DENIED", "DESTINATION_NOT_FOUND", "INTERNAL_SERVICE_ERROR", "NONE"
 ]
 ResolverQueryLogConfigAssociationStatusType = Literal[
     "ACTION_NEEDED", "ACTIVE", "CREATING", "DELETING", "FAILED"
 ]
 ResolverQueryLogConfigStatusType = Literal["CREATED", "CREATING", "DELETING", "FAILED"]
 ResolverRuleAssociationStatusType = Literal[
     "COMPLETE", "CREATING", "DELETING", "FAILED", "OVERRIDDEN"
 ]
 ResolverRuleStatusType = Literal["COMPLETE", "DELETING", "FAILED", "UPDATING"]
 RuleTypeOptionType = Literal["FORWARD", "RECURSIVE", "SYSTEM"]
 ShareStatusType = Literal["NOT_SHARED", "SHARED_BY_ME", "SHARED_WITH_ME"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
-ValidationType = Literal["DISABLE", "ENABLE"]
+ValidationType = Literal["DISABLE", "ENABLE", "USE_LOCAL_RESOURCE_SETTING"]
 Route53ResolverServiceName = Literal["route53resolver"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -190,14 +207,15 @@
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
@@ -276,14 +294,15 @@
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
@@ -294,14 +313,15 @@
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
@@ -337,14 +357,15 @@
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
@@ -363,16 +384,19 @@
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
@@ -456,15 +480,17 @@
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
@@ -506,21 +532,25 @@
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/literals.pyi` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -46,14 +46,15 @@
     "ListResolverRulesPaginatorName",
     "ListTagsForResourcePaginatorName",
     "MutationProtectionStatusType",
     "ResolverAutodefinedReverseStatusType",
     "ResolverDNSSECValidationStatusType",
     "ResolverEndpointDirectionType",
     "ResolverEndpointStatusType",
+    "ResolverEndpointTypeType",
     "ResolverQueryLogConfigAssociationErrorType",
     "ResolverQueryLogConfigAssociationStatusType",
     "ResolverQueryLogConfigStatusType",
     "ResolverRuleAssociationStatusType",
     "ResolverRuleStatusType",
     "RuleTypeOptionType",
     "ShareStatusType",
@@ -63,36 +64,37 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 ActionType = Literal["ALERT", "ALLOW", "BLOCK"]
-AutodefinedReverseFlagType = Literal["DISABLE", "ENABLE"]
+AutodefinedReverseFlagType = Literal["DISABLE", "ENABLE", "USE_LOCAL_RESOURCE_SETTING"]
 BlockOverrideDnsTypeType = Literal["CNAME"]
 BlockResponseType = Literal["NODATA", "NXDOMAIN", "OVERRIDE"]
 FirewallDomainImportOperationType = Literal["REPLACE"]
 FirewallDomainListStatusType = Literal[
     "COMPLETE", "COMPLETE_IMPORT_FAILED", "DELETING", "IMPORTING", "UPDATING"
 ]
 FirewallDomainUpdateOperationType = Literal["ADD", "REMOVE", "REPLACE"]
-FirewallFailOpenStatusType = Literal["DISABLED", "ENABLED"]
+FirewallFailOpenStatusType = Literal["DISABLED", "ENABLED", "USE_LOCAL_RESOURCE_SETTING"]
 FirewallRuleGroupAssociationStatusType = Literal["COMPLETE", "DELETING", "UPDATING"]
 FirewallRuleGroupStatusType = Literal["COMPLETE", "DELETING", "UPDATING"]
 IpAddressStatusType = Literal[
     "ATTACHED",
     "ATTACHING",
     "CREATING",
     "DELETE_FAILED_FAS_EXPIRED",
     "DELETING",
     "DETACHING",
     "FAILED_CREATION",
     "FAILED_RESOURCE_GONE",
     "REMAP_ATTACHING",
     "REMAP_DETACHING",
+    "UPDATING",
 ]
 ListFirewallConfigsPaginatorName = Literal["list_firewall_configs"]
 ListFirewallDomainListsPaginatorName = Literal["list_firewall_domain_lists"]
 ListFirewallDomainsPaginatorName = Literal["list_firewall_domains"]
 ListFirewallRuleGroupAssociationsPaginatorName = Literal["list_firewall_rule_group_associations"]
 ListFirewallRuleGroupsPaginatorName = Literal["list_firewall_rule_groups"]
 ListFirewallRulesPaginatorName = Literal["list_firewall_rules"]
@@ -104,35 +106,50 @@
     "list_resolver_query_log_config_associations"
 ]
 ListResolverQueryLogConfigsPaginatorName = Literal["list_resolver_query_log_configs"]
 ListResolverRuleAssociationsPaginatorName = Literal["list_resolver_rule_associations"]
 ListResolverRulesPaginatorName = Literal["list_resolver_rules"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 MutationProtectionStatusType = Literal["DISABLED", "ENABLED"]
-ResolverAutodefinedReverseStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
-ResolverDNSSECValidationStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
+ResolverAutodefinedReverseStatusType = Literal[
+    "DISABLED",
+    "DISABLING",
+    "ENABLED",
+    "ENABLING",
+    "UPDATING_TO_USE_LOCAL_RESOURCE_SETTING",
+    "USE_LOCAL_RESOURCE_SETTING",
+]
+ResolverDNSSECValidationStatusType = Literal[
+    "DISABLED",
+    "DISABLING",
+    "ENABLED",
+    "ENABLING",
+    "UPDATING_TO_USE_LOCAL_RESOURCE_SETTING",
+    "USE_LOCAL_RESOURCE_SETTING",
+]
 ResolverEndpointDirectionType = Literal["INBOUND", "OUTBOUND"]
 ResolverEndpointStatusType = Literal[
     "ACTION_NEEDED", "AUTO_RECOVERING", "CREATING", "DELETING", "OPERATIONAL", "UPDATING"
 ]
+ResolverEndpointTypeType = Literal["DUALSTACK", "IPV4", "IPV6"]
 ResolverQueryLogConfigAssociationErrorType = Literal[
     "ACCESS_DENIED", "DESTINATION_NOT_FOUND", "INTERNAL_SERVICE_ERROR", "NONE"
 ]
 ResolverQueryLogConfigAssociationStatusType = Literal[
     "ACTION_NEEDED", "ACTIVE", "CREATING", "DELETING", "FAILED"
 ]
 ResolverQueryLogConfigStatusType = Literal["CREATED", "CREATING", "DELETING", "FAILED"]
 ResolverRuleAssociationStatusType = Literal[
     "COMPLETE", "CREATING", "DELETING", "FAILED", "OVERRIDDEN"
 ]
 ResolverRuleStatusType = Literal["COMPLETE", "DELETING", "FAILED", "UPDATING"]
 RuleTypeOptionType = Literal["FORWARD", "RECURSIVE", "SYSTEM"]
 ShareStatusType = Literal["NOT_SHARED", "SHARED_BY_ME", "SHARED_WITH_ME"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
-ValidationType = Literal["DISABLE", "ENABLE"]
+ValidationType = Literal["DISABLE", "ENABLE", "USE_LOCAL_RESOURCE_SETTING"]
 Route53ResolverServiceName = Literal["route53resolver"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -188,14 +205,15 @@
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
@@ -274,14 +292,15 @@
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
@@ -292,14 +311,15 @@
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
@@ -335,14 +355,15 @@
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
@@ -361,16 +382,19 @@
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
@@ -454,15 +478,17 @@
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
@@ -504,21 +530,25 @@
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/paginator.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -44,16 +44,15 @@
         list_resolver_query_log_config_associations_paginator: ListResolverQueryLogConfigAssociationsPaginator = client.get_paginator("list_resolver_query_log_config_associations")
         list_resolver_query_log_configs_paginator: ListResolverQueryLogConfigsPaginator = client.get_paginator("list_resolver_query_log_configs")
         list_resolver_rule_associations_paginator: ListResolverRuleAssociationsPaginator = client.get_paginator("list_resolver_rule_associations")
         list_resolver_rules_paginator: ListResolverRulesPaginator = client.get_paginator("list_resolver_rules")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ActionType, FirewallRuleGroupAssociationStatusType, SortOrderType
 from .type_defs import (
     FilterTypeDef,
@@ -71,20 +70,14 @@
     ListResolverQueryLogConfigsResponseTypeDef,
     ListResolverRuleAssociationsResponseTypeDef,
     ListResolverRulesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListFirewallConfigsPaginator",
     "ListFirewallDomainListsPaginator",
     "ListFirewallDomainsPaginator",
     "ListFirewallRuleGroupAssociationsPaginator",
     "ListFirewallRuleGroupsPaginator",
     "ListFirewallRulesPaginator",
@@ -113,45 +106,45 @@
 class ListFirewallConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallconfigspaginator)
         """
 
 
 class ListFirewallDomainListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomainLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainlistspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallDomainListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomainLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainlistspaginator)
         """
 
 
 class ListFirewallDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainspaginator)
     """
 
     def paginate(
-        self, *, FirewallDomainListId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FirewallDomainListId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainspaginator)
         """
 
 
@@ -164,30 +157,30 @@
     def paginate(
         self,
         *,
         FirewallRuleGroupId: str = ...,
         VpcId: str = ...,
         Priority: int = ...,
         Status: FirewallRuleGroupAssociationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRuleGroupAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroupAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupassociationspaginator)
         """
 
 
 class ListFirewallRuleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRuleGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupspaginator)
         """
 
 
@@ -199,30 +192,30 @@
 
     def paginate(
         self,
         *,
         FirewallRuleGroupId: str,
         Priority: int = ...,
         Action: ActionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulespaginator)
         """
 
 
 class ListResolverConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverconfigspaginator)
         """
 
 
@@ -232,30 +225,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverdnssecconfigspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverDnssecConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverDnssecConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverdnssecconfigspaginator)
         """
 
 
 class ListResolverEndpointIpAddressesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpointIpAddresses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointipaddressespaginator)
     """
 
     def paginate(
-        self, *, ResolverEndpointId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResolverEndpointId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverEndpointIpAddressesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpointIpAddresses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointipaddressespaginator)
         """
 
 
@@ -265,15 +258,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointspaginator)
         """
 
 
@@ -285,15 +278,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         SortBy: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverQueryLogConfigAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverQueryLogConfigAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverquerylogconfigassociationspaginator)
         """
 
 
@@ -305,15 +298,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         SortBy: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverQueryLogConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverQueryLogConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverquerylogconfigspaginator)
         """
 
 
@@ -323,15 +316,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverruleassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverRuleAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverRuleAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverruleassociationspaginator)
         """
 
 
@@ -341,28 +334,28 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverrulespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverrulespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/paginator.pyi` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -44,16 +44,15 @@
         list_resolver_query_log_config_associations_paginator: ListResolverQueryLogConfigAssociationsPaginator = client.get_paginator("list_resolver_query_log_config_associations")
         list_resolver_query_log_configs_paginator: ListResolverQueryLogConfigsPaginator = client.get_paginator("list_resolver_query_log_configs")
         list_resolver_rule_associations_paginator: ListResolverRuleAssociationsPaginator = client.get_paginator("list_resolver_rule_associations")
         list_resolver_rules_paginator: ListResolverRulesPaginator = client.get_paginator("list_resolver_rules")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ActionType, FirewallRuleGroupAssociationStatusType, SortOrderType
 from .type_defs import (
     FilterTypeDef,
@@ -71,19 +70,14 @@
     ListResolverQueryLogConfigsResponseTypeDef,
     ListResolverRuleAssociationsResponseTypeDef,
     ListResolverRulesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListFirewallConfigsPaginator",
     "ListFirewallDomainListsPaginator",
     "ListFirewallDomainsPaginator",
     "ListFirewallRuleGroupAssociationsPaginator",
     "ListFirewallRuleGroupsPaginator",
     "ListFirewallRulesPaginator",
@@ -109,43 +103,43 @@
 class ListFirewallConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallconfigspaginator)
         """
 
 class ListFirewallDomainListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomainLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainlistspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallDomainListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomainLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainlistspaginator)
         """
 
 class ListFirewallDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainspaginator)
     """
 
     def paginate(
-        self, *, FirewallDomainListId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FirewallDomainListId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewalldomainspaginator)
         """
 
 class ListFirewallRuleGroupAssociationsPaginator(AioPaginator):
@@ -157,29 +151,29 @@
     def paginate(
         self,
         *,
         FirewallRuleGroupId: str = ...,
         VpcId: str = ...,
         Priority: int = ...,
         Status: FirewallRuleGroupAssociationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRuleGroupAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroupAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupassociationspaginator)
         """
 
 class ListFirewallRuleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRuleGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRuleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulegroupspaginator)
         """
 
 class ListFirewallRulesPaginator(AioPaginator):
@@ -190,29 +184,29 @@
 
     def paginate(
         self,
         *,
         FirewallRuleGroupId: str,
         Priority: int = ...,
         Action: ActionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListFirewallRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listfirewallrulespaginator)
         """
 
 class ListResolverConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverconfigspaginator)
         """
 
 class ListResolverDnssecConfigsPaginator(AioPaginator):
@@ -221,29 +215,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverdnssecconfigspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverDnssecConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverDnssecConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverdnssecconfigspaginator)
         """
 
 class ListResolverEndpointIpAddressesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpointIpAddresses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointipaddressespaginator)
     """
 
     def paginate(
-        self, *, ResolverEndpointId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResolverEndpointId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverEndpointIpAddressesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpointIpAddresses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointipaddressespaginator)
         """
 
 class ListResolverEndpointsPaginator(AioPaginator):
@@ -252,15 +246,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverendpointspaginator)
         """
 
 class ListResolverQueryLogConfigAssociationsPaginator(AioPaginator):
@@ -271,15 +265,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         SortBy: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverQueryLogConfigAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverQueryLogConfigAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverquerylogconfigassociationspaginator)
         """
 
 class ListResolverQueryLogConfigsPaginator(AioPaginator):
@@ -290,15 +284,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         SortBy: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverQueryLogConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverQueryLogConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverquerylogconfigspaginator)
         """
 
 class ListResolverRuleAssociationsPaginator(AioPaginator):
@@ -307,15 +301,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverruleassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverRuleAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverRuleAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverruleassociationspaginator)
         """
 
 class ListResolverRulesPaginator(AioPaginator):
@@ -324,27 +318,27 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverrulespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolverRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListResolverRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listresolverrulespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/type_defs.py` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     FirewallRuleGroupStatusType,
     IpAddressStatusType,
     MutationProtectionStatusType,
     ResolverAutodefinedReverseStatusType,
     ResolverDNSSECValidationStatusType,
     ResolverEndpointDirectionType,
     ResolverEndpointStatusType,
+    ResolverEndpointTypeType,
     ResolverQueryLogConfigAssociationErrorType,
     ResolverQueryLogConfigAssociationStatusType,
     ResolverQueryLogConfigStatusType,
     ResolverRuleAssociationStatusType,
     ResolverRuleStatusType,
     RuleTypeOptionType,
     ShareStatusType,
@@ -45,19 +46,17 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "TagTypeDef",
     "FirewallRuleGroupAssociationTypeDef",
-    "ResponseMetadataTypeDef",
     "IpAddressUpdateTypeDef",
     "ResolverEndpointTypeDef",
     "AssociateResolverQueryLogConfigRequestRequestTypeDef",
     "ResolverQueryLogConfigAssociationTypeDef",
     "AssociateResolverRuleRequestRequestTypeDef",
     "ResolverRuleAssociationTypeDef",
     "FirewallDomainListTypeDef",
@@ -80,68 +79,78 @@
     "FirewallConfigTypeDef",
     "FirewallDomainListMetadataTypeDef",
     "FirewallRuleGroupMetadataTypeDef",
     "GetFirewallConfigRequestRequestTypeDef",
     "GetFirewallDomainListRequestRequestTypeDef",
     "GetFirewallRuleGroupAssociationRequestRequestTypeDef",
     "GetFirewallRuleGroupPolicyRequestRequestTypeDef",
+    "GetFirewallRuleGroupPolicyResponseTypeDef",
     "GetFirewallRuleGroupRequestRequestTypeDef",
     "GetResolverConfigRequestRequestTypeDef",
     "ResolverConfigTypeDef",
     "GetResolverDnssecConfigRequestRequestTypeDef",
     "ResolverDnssecConfigTypeDef",
     "GetResolverEndpointRequestRequestTypeDef",
     "GetResolverQueryLogConfigAssociationRequestRequestTypeDef",
     "GetResolverQueryLogConfigPolicyRequestRequestTypeDef",
+    "GetResolverQueryLogConfigPolicyResponseTypeDef",
     "GetResolverQueryLogConfigRequestRequestTypeDef",
     "GetResolverRuleAssociationRequestRequestTypeDef",
     "GetResolverRulePolicyRequestRequestTypeDef",
+    "GetResolverRulePolicyResponseTypeDef",
     "GetResolverRuleRequestRequestTypeDef",
     "ImportFirewallDomainsRequestRequestTypeDef",
+    "ImportFirewallDomainsResponseTypeDef",
     "IpAddressResponseTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
     "ListFirewallConfigsRequestRequestTypeDef",
+    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
     "ListFirewallDomainListsRequestRequestTypeDef",
+    "ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
     "ListFirewallDomainsRequestRequestTypeDef",
+    "ListFirewallDomainsResponseTypeDef",
+    "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
     "ListFirewallRuleGroupAssociationsRequestRequestTypeDef",
+    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
     "ListFirewallRuleGroupsRequestRequestTypeDef",
+    "ListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
     "ListFirewallRulesRequestRequestTypeDef",
+    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
     "ListResolverConfigsRequestRequestTypeDef",
+    "ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
     "ListResolverEndpointIpAddressesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutFirewallRuleGroupPolicyRequestRequestTypeDef",
+    "PutFirewallRuleGroupPolicyResponseTypeDef",
     "PutResolverQueryLogConfigPolicyRequestRequestTypeDef",
+    "PutResolverQueryLogConfigPolicyResponseTypeDef",
     "PutResolverRulePolicyRequestRequestTypeDef",
+    "PutResolverRulePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFirewallConfigRequestRequestTypeDef",
     "UpdateFirewallDomainsRequestRequestTypeDef",
+    "UpdateFirewallDomainsResponseTypeDef",
     "UpdateFirewallRuleGroupAssociationRequestRequestTypeDef",
     "UpdateFirewallRuleRequestRequestTypeDef",
+    "UpdateIpAddressTypeDef",
     "UpdateResolverConfigRequestRequestTypeDef",
     "UpdateResolverDnssecConfigRequestRequestTypeDef",
-    "UpdateResolverEndpointRequestRequestTypeDef",
     "AssociateFirewallRuleGroupRequestRequestTypeDef",
     "CreateFirewallDomainListRequestRequestTypeDef",
     "CreateFirewallRuleGroupRequestRequestTypeDef",
     "CreateResolverQueryLogConfigRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "AssociateFirewallRuleGroupResponseTypeDef",
     "DisassociateFirewallRuleGroupResponseTypeDef",
     "GetFirewallRuleGroupAssociationResponseTypeDef",
-    "GetFirewallRuleGroupPolicyResponseTypeDef",
-    "GetResolverQueryLogConfigPolicyResponseTypeDef",
-    "GetResolverRulePolicyResponseTypeDef",
-    "ImportFirewallDomainsResponseTypeDef",
-    "ListFirewallDomainsResponseTypeDef",
     "ListFirewallRuleGroupAssociationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutFirewallRuleGroupPolicyResponseTypeDef",
-    "PutResolverQueryLogConfigPolicyResponseTypeDef",
-    "PutResolverRulePolicyResponseTypeDef",
-    "UpdateFirewallDomainsResponseTypeDef",
     "UpdateFirewallRuleGroupAssociationResponseTypeDef",
     "AssociateResolverEndpointIpAddressRequestRequestTypeDef",
     "DisassociateResolverEndpointIpAddressRequestRequestTypeDef",
     "AssociateResolverEndpointIpAddressResponseTypeDef",
     "CreateResolverEndpointResponseTypeDef",
     "DeleteResolverEndpointResponseTypeDef",
     "DisassociateResolverEndpointIpAddressResponseTypeDef",
@@ -170,47 +179,39 @@
     "CreateResolverQueryLogConfigResponseTypeDef",
     "DeleteResolverQueryLogConfigResponseTypeDef",
     "GetResolverQueryLogConfigResponseTypeDef",
     "ListResolverQueryLogConfigsResponseTypeDef",
     "CreateResolverRuleRequestRequestTypeDef",
     "ResolverRuleConfigTypeDef",
     "ResolverRuleTypeDef",
+    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
     "ListResolverDnssecConfigsRequestRequestTypeDef",
+    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
     "ListResolverEndpointsRequestRequestTypeDef",
+    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
     "ListResolverQueryLogConfigAssociationsRequestRequestTypeDef",
+    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
     "ListResolverQueryLogConfigsRequestRequestTypeDef",
+    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
     "ListResolverRuleAssociationsRequestRequestTypeDef",
+    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
     "ListResolverRulesRequestRequestTypeDef",
     "GetFirewallConfigResponseTypeDef",
     "ListFirewallConfigsResponseTypeDef",
     "UpdateFirewallConfigResponseTypeDef",
     "ListFirewallDomainListsResponseTypeDef",
     "ListFirewallRuleGroupsResponseTypeDef",
     "GetResolverConfigResponseTypeDef",
     "ListResolverConfigsResponseTypeDef",
     "UpdateResolverConfigResponseTypeDef",
     "GetResolverDnssecConfigResponseTypeDef",
     "ListResolverDnssecConfigsResponseTypeDef",
     "UpdateResolverDnssecConfigResponseTypeDef",
     "ListResolverEndpointIpAddressesResponseTypeDef",
-    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
-    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
-    "ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
-    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
-    "ListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
-    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
-    "ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
-    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
-    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
-    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
-    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
-    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "UpdateResolverEndpointRequestRequestTypeDef",
     "UpdateResolverRuleRequestRequestTypeDef",
     "CreateResolverRuleResponseTypeDef",
     "DeleteResolverRuleResponseTypeDef",
     "GetResolverRuleResponseTypeDef",
     "ListResolverRulesResponseTypeDef",
     "UpdateResolverRuleResponseTypeDef",
 )
@@ -239,31 +240,21 @@
         "CreatorRequestId": str,
         "CreationTime": str,
         "ModificationTime": str,
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
 IpAddressUpdateTypeDef = TypedDict(
     "IpAddressUpdateTypeDef",
     {
         "IpId": str,
         "SubnetId": str,
         "Ip": str,
+        "Ipv6": str,
     },
     total=False,
 )
 
 ResolverEndpointTypeDef = TypedDict(
     "ResolverEndpointTypeDef",
     {
@@ -275,14 +266,15 @@
         "Direction": ResolverEndpointDirectionType,
         "IpAddressCount": int,
         "HostVPCId": str,
         "Status": ResolverEndpointStatusType,
         "StatusMessage": str,
         "CreationTime": str,
         "ModificationTime": str,
+        "ResolverEndpointType": ResolverEndpointTypeType,
     },
     total=False,
 )
 
 AssociateResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "AssociateResolverQueryLogConfigRequestRequestTypeDef",
     {
@@ -316,22 +308,20 @@
     "_OptionalAssociateResolverRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
-
 class AssociateResolverRuleRequestRequestTypeDef(
     _RequiredAssociateResolverRuleRequestRequestTypeDef,
     _OptionalAssociateResolverRuleRequestRequestTypeDef,
 ):
     pass
 
-
 ResolverRuleAssociationTypeDef = TypedDict(
     "ResolverRuleAssociationTypeDef",
     {
         "Id": str,
         "ResolverRuleId": str,
         "Name": str,
         "VPCId": str,
@@ -394,22 +384,20 @@
         "BlockOverrideDomain": str,
         "BlockOverrideDnsType": Literal["CNAME"],
         "BlockOverrideTtl": int,
     },
     total=False,
 )
 
-
 class CreateFirewallRuleRequestRequestTypeDef(
     _RequiredCreateFirewallRuleRequestRequestTypeDef,
     _OptionalCreateFirewallRuleRequestRequestTypeDef,
 ):
     pass
 
-
 FirewallRuleTypeDef = TypedDict(
     "FirewallRuleTypeDef",
     {
         "FirewallRuleGroupId": str,
         "FirewallDomainListId": str,
         "Name": str,
         "Priority": int,
@@ -431,23 +419,22 @@
         "SubnetId": str,
     },
 )
 _OptionalIpAddressRequestTypeDef = TypedDict(
     "_OptionalIpAddressRequestTypeDef",
     {
         "Ip": str,
+        "Ipv6": str,
     },
     total=False,
 )
 
-
 class IpAddressRequestTypeDef(_RequiredIpAddressRequestTypeDef, _OptionalIpAddressRequestTypeDef):
     pass
 
-
 ResolverQueryLogConfigTypeDef = TypedDict(
     "ResolverQueryLogConfigTypeDef",
     {
         "Id": str,
         "OwnerId": str,
         "Status": ResolverQueryLogConfigStatusType,
         "ShareStatus": ShareStatusType,
@@ -457,33 +444,24 @@
         "DestinationArn": str,
         "CreatorRequestId": str,
         "CreationTime": str,
     },
     total=False,
 )
 
-_RequiredTargetAddressTypeDef = TypedDict(
-    "_RequiredTargetAddressTypeDef",
+TargetAddressTypeDef = TypedDict(
+    "TargetAddressTypeDef",
     {
         "Ip": str,
-    },
-)
-_OptionalTargetAddressTypeDef = TypedDict(
-    "_OptionalTargetAddressTypeDef",
-    {
         "Port": int,
+        "Ipv6": str,
     },
     total=False,
 )
 
-
-class TargetAddressTypeDef(_RequiredTargetAddressTypeDef, _OptionalTargetAddressTypeDef):
-    pass
-
-
 DeleteFirewallDomainListRequestRequestTypeDef = TypedDict(
     "DeleteFirewallDomainListRequestRequestTypeDef",
     {
         "FirewallDomainListId": str,
     },
 )
 
@@ -615,14 +593,22 @@
 GetFirewallRuleGroupPolicyRequestRequestTypeDef = TypedDict(
     "GetFirewallRuleGroupPolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
+    "GetFirewallRuleGroupPolicyResponseTypeDef",
+    {
+        "FirewallRuleGroupPolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "GetFirewallRuleGroupRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
     },
 )
 
@@ -679,14 +665,22 @@
 GetResolverQueryLogConfigPolicyRequestRequestTypeDef = TypedDict(
     "GetResolverQueryLogConfigPolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
+    "GetResolverQueryLogConfigPolicyResponseTypeDef",
+    {
+        "ResolverQueryLogConfigPolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "GetResolverQueryLogConfigRequestRequestTypeDef",
     {
         "ResolverQueryLogConfigId": str,
     },
 )
 
@@ -700,14 +694,22 @@
 GetResolverRulePolicyRequestRequestTypeDef = TypedDict(
     "GetResolverRulePolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetResolverRulePolicyResponseTypeDef = TypedDict(
+    "GetResolverRulePolicyResponseTypeDef",
+    {
+        "ResolverRulePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverRuleRequestRequestTypeDef = TypedDict(
     "GetResolverRuleRequestRequestTypeDef",
     {
         "ResolverRuleId": str,
     },
 )
 
@@ -716,56 +718,94 @@
     {
         "FirewallDomainListId": str,
         "Operation": Literal["REPLACE"],
         "DomainFileUrl": str,
     },
 )
 
+ImportFirewallDomainsResponseTypeDef = TypedDict(
+    "ImportFirewallDomainsResponseTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Status": FirewallDomainListStatusType,
+        "StatusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IpAddressResponseTypeDef = TypedDict(
     "IpAddressResponseTypeDef",
     {
         "IpId": str,
         "SubnetId": str,
         "Ip": str,
+        "Ipv6": str,
         "Status": IpAddressStatusType,
         "StatusMessage": str,
         "CreationTime": str,
         "ModificationTime": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef = TypedDict(
+    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFirewallConfigsRequestRequestTypeDef = TypedDict(
     "ListFirewallConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef = TypedDict(
+    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallDomainListsRequestRequestTypeDef = TypedDict(
     "ListFirewallDomainListsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
+    "_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
+    {
+        "FirewallDomainListId": str,
+    },
+)
+_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
+    "_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef(
+    _RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
+    _OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
+):
+    pass
+
 _RequiredListFirewallDomainsRequestRequestTypeDef = TypedDict(
     "_RequiredListFirewallDomainsRequestRequestTypeDef",
     {
         "FirewallDomainListId": str,
     },
 )
 _OptionalListFirewallDomainsRequestRequestTypeDef = TypedDict(
@@ -773,44 +813,95 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListFirewallDomainsRequestRequestTypeDef(
     _RequiredListFirewallDomainsRequestRequestTypeDef,
     _OptionalListFirewallDomainsRequestRequestTypeDef,
 ):
     pass
 
+ListFirewallDomainsResponseTypeDef = TypedDict(
+    "ListFirewallDomainsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Domains": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef = (
+    TypedDict(
+        "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
+        {
+            "FirewallRuleGroupId": str,
+            "VpcId": str,
+            "Priority": int,
+            "Status": FirewallRuleGroupAssociationStatusType,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
 
 ListFirewallRuleGroupAssociationsRequestRequestTypeDef = TypedDict(
     "ListFirewallRuleGroupAssociationsRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
         "VpcId": str,
         "Priority": int,
         "Status": FirewallRuleGroupAssociationStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef = TypedDict(
+    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallRuleGroupsRequestRequestTypeDef = TypedDict(
     "ListFirewallRuleGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
+    "_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
+    {
+        "FirewallRuleGroupId": str,
+    },
+)
+_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
+    "_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
+    {
+        "Priority": int,
+        "Action": ActionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFirewallRulesRequestListFirewallRulesPaginateTypeDef(
+    _RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
+    _OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
+):
+    pass
+
 _RequiredListFirewallRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListFirewallRulesRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
     },
 )
 _OptionalListFirewallRulesRequestRequestTypeDef = TypedDict(
@@ -820,30 +911,56 @@
         "Action": ActionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListFirewallRulesRequestRequestTypeDef(
     _RequiredListFirewallRulesRequestRequestTypeDef, _OptionalListFirewallRulesRequestRequestTypeDef
 ):
     pass
 
+ListResolverConfigsRequestListResolverConfigsPaginateTypeDef = TypedDict(
+    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListResolverConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
+    "_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+    {
+        "ResolverEndpointId": str,
+    },
+)
+_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
+    "_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef(
+    _RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
+    _OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResolverEndpointIpAddressesRequestRequestTypeDef = TypedDict(
     "_RequiredListResolverEndpointIpAddressesRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
     },
 )
 _OptionalListResolverEndpointIpAddressesRequestRequestTypeDef = TypedDict(
@@ -851,21 +968,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListResolverEndpointIpAddressesRequestRequestTypeDef(
     _RequiredListResolverEndpointIpAddressesRequestRequestTypeDef,
     _OptionalListResolverEndpointIpAddressesRequestRequestTypeDef,
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
 
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
@@ -874,46 +1009,89 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
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
 
 PutFirewallRuleGroupPolicyRequestRequestTypeDef = TypedDict(
     "PutFirewallRuleGroupPolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "FirewallRuleGroupPolicy": str,
     },
 )
 
+PutFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
+    "PutFirewallRuleGroupPolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutResolverQueryLogConfigPolicyRequestRequestTypeDef = TypedDict(
     "PutResolverQueryLogConfigPolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "ResolverQueryLogConfigPolicy": str,
     },
 )
 
+PutResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
+    "PutResolverQueryLogConfigPolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutResolverRulePolicyRequestRequestTypeDef = TypedDict(
     "PutResolverRulePolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "ResolverRulePolicy": str,
     },
 )
 
+PutResolverRulePolicyResponseTypeDef = TypedDict(
+    "PutResolverRulePolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -931,14 +1109,25 @@
     {
         "FirewallDomainListId": str,
         "Operation": FirewallDomainUpdateOperationType,
         "Domains": Sequence[str],
     },
 )
 
+UpdateFirewallDomainsResponseTypeDef = TypedDict(
+    "UpdateFirewallDomainsResponseTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Status": FirewallDomainListStatusType,
+        "StatusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef",
     {
         "FirewallRuleGroupAssociationId": str,
     },
 )
 _OptionalUpdateFirewallRuleGroupAssociationRequestRequestTypeDef = TypedDict(
@@ -947,22 +1136,20 @@
         "Priority": int,
         "MutationProtection": MutationProtectionStatusType,
         "Name": str,
     },
     total=False,
 )
 
-
 class UpdateFirewallRuleGroupAssociationRequestRequestTypeDef(
     _RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
     _OptionalUpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateFirewallRuleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallRuleRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
         "FirewallDomainListId": str,
     },
 )
@@ -976,21 +1163,27 @@
         "BlockOverrideDnsType": Literal["CNAME"],
         "BlockOverrideTtl": int,
         "Name": str,
     },
     total=False,
 )
 
-
 class UpdateFirewallRuleRequestRequestTypeDef(
     _RequiredUpdateFirewallRuleRequestRequestTypeDef,
     _OptionalUpdateFirewallRuleRequestRequestTypeDef,
 ):
     pass
 
+UpdateIpAddressTypeDef = TypedDict(
+    "UpdateIpAddressTypeDef",
+    {
+        "IpId": str,
+        "Ipv6": str,
+    },
+)
 
 UpdateResolverConfigRequestRequestTypeDef = TypedDict(
     "UpdateResolverConfigRequestRequestTypeDef",
     {
         "ResourceId": str,
         "AutodefinedReverseFlag": AutodefinedReverseFlagType,
     },
@@ -1000,36 +1193,14 @@
     "UpdateResolverDnssecConfigRequestRequestTypeDef",
     {
         "ResourceId": str,
         "Validation": ValidationType,
     },
 )
 
-_RequiredUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateResolverEndpointRequestRequestTypeDef",
-    {
-        "ResolverEndpointId": str,
-    },
-)
-_OptionalUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateResolverEndpointRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-    total=False,
-)
-
-
-class UpdateResolverEndpointRequestRequestTypeDef(
-    _RequiredUpdateResolverEndpointRequestRequestTypeDef,
-    _OptionalUpdateResolverEndpointRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredAssociateFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateFirewallRuleGroupRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "FirewallRuleGroupId": str,
         "VpcId": str,
         "Priority": int,
@@ -1041,22 +1212,20 @@
     {
         "MutationProtection": MutationProtectionStatusType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class AssociateFirewallRuleGroupRequestRequestTypeDef(
     _RequiredAssociateFirewallRuleGroupRequestRequestTypeDef,
     _OptionalAssociateFirewallRuleGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateFirewallDomainListRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallDomainListRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "Name": str,
     },
 )
@@ -1064,22 +1233,20 @@
     "_OptionalCreateFirewallDomainListRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateFirewallDomainListRequestRequestTypeDef(
     _RequiredCreateFirewallDomainListRequestRequestTypeDef,
     _OptionalCreateFirewallDomainListRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallRuleGroupRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "Name": str,
     },
 )
@@ -1087,22 +1254,20 @@
     "_OptionalCreateFirewallRuleGroupRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateFirewallRuleGroupRequestRequestTypeDef(
     _RequiredCreateFirewallRuleGroupRequestRequestTypeDef,
     _OptionalCreateFirewallRuleGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverQueryLogConfigRequestRequestTypeDef",
     {
         "Name": str,
         "DestinationArn": str,
         "CreatorRequestId": str,
     },
@@ -1111,156 +1276,75 @@
     "_OptionalCreateResolverQueryLogConfigRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateResolverQueryLogConfigRequestRequestTypeDef(
     _RequiredCreateResolverQueryLogConfigRequestRequestTypeDef,
     _OptionalCreateResolverQueryLogConfigRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
 AssociateFirewallRuleGroupResponseTypeDef = TypedDict(
     "AssociateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateFirewallRuleGroupResponseTypeDef = TypedDict(
     "DisassociateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallRuleGroupAssociationResponseTypeDef = TypedDict(
     "GetFirewallRuleGroupAssociationResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
-    "GetFirewallRuleGroupPolicyResponseTypeDef",
-    {
-        "FirewallRuleGroupPolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
-    "GetResolverQueryLogConfigPolicyResponseTypeDef",
-    {
-        "ResolverQueryLogConfigPolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResolverRulePolicyResponseTypeDef = TypedDict(
-    "GetResolverRulePolicyResponseTypeDef",
-    {
-        "ResolverRulePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportFirewallDomainsResponseTypeDef = TypedDict(
-    "ImportFirewallDomainsResponseTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Status": FirewallDomainListStatusType,
-        "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFirewallDomainsResponseTypeDef = TypedDict(
-    "ListFirewallDomainsResponseTypeDef",
-    {
-        "NextToken": str,
-        "Domains": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRuleGroupAssociationsResponseTypeDef = TypedDict(
     "ListFirewallRuleGroupAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRuleGroupAssociations": List[FirewallRuleGroupAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
-    "PutFirewallRuleGroupPolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
-    "PutResolverQueryLogConfigPolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResolverRulePolicyResponseTypeDef = TypedDict(
-    "PutResolverRulePolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDomainsResponseTypeDef = TypedDict(
-    "UpdateFirewallDomainsResponseTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Status": FirewallDomainListStatusType,
-        "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallRuleGroupAssociationResponseTypeDef = TypedDict(
     "UpdateFirewallRuleGroupAssociationResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverEndpointIpAddressRequestRequestTypeDef = TypedDict(
     "AssociateResolverEndpointIpAddressRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
@@ -1276,215 +1360,215 @@
     },
 )
 
 AssociateResolverEndpointIpAddressResponseTypeDef = TypedDict(
     "AssociateResolverEndpointIpAddressResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResolverEndpointResponseTypeDef = TypedDict(
     "CreateResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverEndpointResponseTypeDef = TypedDict(
     "DeleteResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverEndpointIpAddressResponseTypeDef = TypedDict(
     "DisassociateResolverEndpointIpAddressResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverEndpointResponseTypeDef = TypedDict(
     "GetResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverEndpointsResponseTypeDef = TypedDict(
     "ListResolverEndpointsResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverEndpoints": List[ResolverEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverEndpointResponseTypeDef = TypedDict(
     "UpdateResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "AssociateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "DisassociateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverQueryLogConfigAssociationResponseTypeDef = TypedDict(
     "GetResolverQueryLogConfigAssociationResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverQueryLogConfigAssociationsResponseTypeDef = TypedDict(
     "ListResolverQueryLogConfigAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "TotalCount": int,
         "TotalFilteredCount": int,
         "ResolverQueryLogConfigAssociations": List[ResolverQueryLogConfigAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverRuleResponseTypeDef = TypedDict(
     "AssociateResolverRuleResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverRuleResponseTypeDef = TypedDict(
     "DisassociateResolverRuleResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverRuleAssociationResponseTypeDef = TypedDict(
     "GetResolverRuleAssociationResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverRuleAssociationsResponseTypeDef = TypedDict(
     "ListResolverRuleAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverRuleAssociations": List[ResolverRuleAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallDomainListResponseTypeDef = TypedDict(
     "CreateFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallDomainListResponseTypeDef = TypedDict(
     "DeleteFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallDomainListResponseTypeDef = TypedDict(
     "GetFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallRuleGroupResponseTypeDef = TypedDict(
     "CreateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallRuleGroupResponseTypeDef = TypedDict(
     "DeleteFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallRuleGroupResponseTypeDef = TypedDict(
     "GetFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallRuleResponseTypeDef = TypedDict(
     "CreateFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallRuleResponseTypeDef = TypedDict(
     "DeleteFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRulesResponseTypeDef = TypedDict(
     "ListFirewallRulesResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRules": List[FirewallRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallRuleResponseTypeDef = TypedDict(
     "UpdateFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateResolverEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverEndpointRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
@@ -1494,58 +1578,57 @@
     },
 )
 _OptionalCreateResolverEndpointRequestRequestTypeDef = TypedDict(
     "_OptionalCreateResolverEndpointRequestRequestTypeDef",
     {
         "Name": str,
         "Tags": Sequence[TagTypeDef],
+        "ResolverEndpointType": ResolverEndpointTypeType,
     },
     total=False,
 )
 
-
 class CreateResolverEndpointRequestRequestTypeDef(
     _RequiredCreateResolverEndpointRequestRequestTypeDef,
     _OptionalCreateResolverEndpointRequestRequestTypeDef,
 ):
     pass
 
-
 CreateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "CreateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverQueryLogConfigResponseTypeDef = TypedDict(
     "DeleteResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverQueryLogConfigResponseTypeDef = TypedDict(
     "GetResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverQueryLogConfigsResponseTypeDef = TypedDict(
     "ListResolverQueryLogConfigsResponseTypeDef",
     {
         "NextToken": str,
         "TotalCount": int,
         "TotalFilteredCount": int,
         "ResolverQueryLogConfigs": List[ResolverQueryLogConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateResolverRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverRuleRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
@@ -1560,22 +1643,20 @@
         "TargetIps": Sequence[TargetAddressTypeDef],
         "ResolverEndpointId": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateResolverRuleRequestRequestTypeDef(
     _RequiredCreateResolverRuleRequestRequestTypeDef,
     _OptionalCreateResolverRuleRequestRequestTypeDef,
 ):
     pass
 
-
 ResolverRuleConfigTypeDef = TypedDict(
     "ResolverRuleConfigTypeDef",
     {
         "Name": str,
         "TargetIps": Sequence[TargetAddressTypeDef],
         "ResolverEndpointId": str,
     },
@@ -1599,417 +1680,303 @@
         "ShareStatus": ShareStatusType,
         "CreationTime": str,
         "ModificationTime": str,
     },
     total=False,
 )
 
+ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef = TypedDict(
+    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverDnssecConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverDnssecConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef = TypedDict(
+    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverEndpointsRequestRequestTypeDef = TypedDict(
     "ListResolverEndpointsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef = TypedDict(
+    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "SortBy": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverQueryLogConfigAssociationsRequestRequestTypeDef = TypedDict(
     "ListResolverQueryLogConfigAssociationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
 )
 
+ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef = TypedDict(
+    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "SortBy": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverQueryLogConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverQueryLogConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
 )
 
+ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef = TypedDict(
+    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverRuleAssociationsRequestRequestTypeDef = TypedDict(
     "ListResolverRuleAssociationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverRulesRequestListResolverRulesPaginateTypeDef = TypedDict(
+    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverRulesRequestRequestTypeDef = TypedDict(
     "ListResolverRulesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
 GetFirewallConfigResponseTypeDef = TypedDict(
     "GetFirewallConfigResponseTypeDef",
     {
         "FirewallConfig": FirewallConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallConfigsResponseTypeDef = TypedDict(
     "ListFirewallConfigsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallConfigs": List[FirewallConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallConfigResponseTypeDef = TypedDict(
     "UpdateFirewallConfigResponseTypeDef",
     {
         "FirewallConfig": FirewallConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallDomainListsResponseTypeDef = TypedDict(
     "ListFirewallDomainListsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallDomainLists": List[FirewallDomainListMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRuleGroupsResponseTypeDef = TypedDict(
     "ListFirewallRuleGroupsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRuleGroups": List[FirewallRuleGroupMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverConfigResponseTypeDef = TypedDict(
     "GetResolverConfigResponseTypeDef",
     {
         "ResolverConfig": ResolverConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverConfigsResponseTypeDef = TypedDict(
     "ListResolverConfigsResponseTypeDef",
     {
         "NextToken": str,
         "ResolverConfigs": List[ResolverConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverConfigResponseTypeDef = TypedDict(
     "UpdateResolverConfigResponseTypeDef",
     {
         "ResolverConfig": ResolverConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverDnssecConfigResponseTypeDef = TypedDict(
     "GetResolverDnssecConfigResponseTypeDef",
     {
         "ResolverDNSSECConfig": ResolverDnssecConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverDnssecConfigsResponseTypeDef = TypedDict(
     "ListResolverDnssecConfigsResponseTypeDef",
     {
         "NextToken": str,
         "ResolverDnssecConfigs": List[ResolverDnssecConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverDnssecConfigResponseTypeDef = TypedDict(
     "UpdateResolverDnssecConfigResponseTypeDef",
     {
         "ResolverDNSSECConfig": ResolverDnssecConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverEndpointIpAddressesResponseTypeDef = TypedDict(
     "ListResolverEndpointIpAddressesResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "IpAddresses": List[IpAddressResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef = TypedDict(
-    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef = TypedDict(
-    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
-    "_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    {
-        "FirewallDomainListId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
-    "_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef(
-    _RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-    _OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-):
-    pass
-
-
-ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef = (
-    TypedDict(
-        "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
-        {
-            "FirewallRuleGroupId": str,
-            "VpcId": str,
-            "Priority": int,
-            "Status": FirewallRuleGroupAssociationStatusType,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef = TypedDict(
-    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
-    "_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    {
-        "FirewallRuleGroupId": str,
-    },
-)
-_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
-    "_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    {
-        "Priority": int,
-        "Action": ActionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFirewallRulesRequestListFirewallRulesPaginateTypeDef(
-    _RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-    _OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-):
-    pass
-
-
-ListResolverConfigsRequestListResolverConfigsPaginateTypeDef = TypedDict(
-    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef = TypedDict(
-    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
-    "_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+_RequiredUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResolverEndpointRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
     },
 )
-_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
-    "_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef(
-    _RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-    _OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-):
-    pass
-
-
-ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef = TypedDict(
-    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef = TypedDict(
-    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "SortBy": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef = TypedDict(
-    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "SortBy": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef = TypedDict(
-    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverRulesRequestListResolverRulesPaginateTypeDef = TypedDict(
-    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+_OptionalUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResolverEndpointRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Name": str,
+        "ResolverEndpointType": ResolverEndpointTypeType,
+        "UpdateIpAddresses": Sequence[UpdateIpAddressTypeDef],
     },
     total=False,
 )
 
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+class UpdateResolverEndpointRequestRequestTypeDef(
+    _RequiredUpdateResolverEndpointRequestRequestTypeDef,
+    _OptionalUpdateResolverEndpointRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateResolverRuleRequestRequestTypeDef = TypedDict(
     "UpdateResolverRuleRequestRequestTypeDef",
     {
         "ResolverRuleId": str,
         "Config": ResolverRuleConfigTypeDef,
     },
 )
 
 CreateResolverRuleResponseTypeDef = TypedDict(
     "CreateResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverRuleResponseTypeDef = TypedDict(
     "DeleteResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverRuleResponseTypeDef = TypedDict(
     "GetResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverRulesResponseTypeDef = TypedDict(
     "ListResolverRulesResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverRules": List[ResolverRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverRuleResponseTypeDef = TypedDict(
     "UpdateResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver/type_defs.pyi` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     FirewallRuleGroupStatusType,
     IpAddressStatusType,
     MutationProtectionStatusType,
     ResolverAutodefinedReverseStatusType,
     ResolverDNSSECValidationStatusType,
     ResolverEndpointDirectionType,
     ResolverEndpointStatusType,
+    ResolverEndpointTypeType,
     ResolverQueryLogConfigAssociationErrorType,
     ResolverQueryLogConfigAssociationStatusType,
     ResolverQueryLogConfigStatusType,
     ResolverRuleAssociationStatusType,
     ResolverRuleStatusType,
     RuleTypeOptionType,
     ShareStatusType,
@@ -45,18 +46,18 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "TagTypeDef",
     "FirewallRuleGroupAssociationTypeDef",
-    "ResponseMetadataTypeDef",
     "IpAddressUpdateTypeDef",
     "ResolverEndpointTypeDef",
     "AssociateResolverQueryLogConfigRequestRequestTypeDef",
     "ResolverQueryLogConfigAssociationTypeDef",
     "AssociateResolverRuleRequestRequestTypeDef",
     "ResolverRuleAssociationTypeDef",
     "FirewallDomainListTypeDef",
@@ -79,68 +80,78 @@
     "FirewallConfigTypeDef",
     "FirewallDomainListMetadataTypeDef",
     "FirewallRuleGroupMetadataTypeDef",
     "GetFirewallConfigRequestRequestTypeDef",
     "GetFirewallDomainListRequestRequestTypeDef",
     "GetFirewallRuleGroupAssociationRequestRequestTypeDef",
     "GetFirewallRuleGroupPolicyRequestRequestTypeDef",
+    "GetFirewallRuleGroupPolicyResponseTypeDef",
     "GetFirewallRuleGroupRequestRequestTypeDef",
     "GetResolverConfigRequestRequestTypeDef",
     "ResolverConfigTypeDef",
     "GetResolverDnssecConfigRequestRequestTypeDef",
     "ResolverDnssecConfigTypeDef",
     "GetResolverEndpointRequestRequestTypeDef",
     "GetResolverQueryLogConfigAssociationRequestRequestTypeDef",
     "GetResolverQueryLogConfigPolicyRequestRequestTypeDef",
+    "GetResolverQueryLogConfigPolicyResponseTypeDef",
     "GetResolverQueryLogConfigRequestRequestTypeDef",
     "GetResolverRuleAssociationRequestRequestTypeDef",
     "GetResolverRulePolicyRequestRequestTypeDef",
+    "GetResolverRulePolicyResponseTypeDef",
     "GetResolverRuleRequestRequestTypeDef",
     "ImportFirewallDomainsRequestRequestTypeDef",
+    "ImportFirewallDomainsResponseTypeDef",
     "IpAddressResponseTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
     "ListFirewallConfigsRequestRequestTypeDef",
+    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
     "ListFirewallDomainListsRequestRequestTypeDef",
+    "ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
     "ListFirewallDomainsRequestRequestTypeDef",
+    "ListFirewallDomainsResponseTypeDef",
+    "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
     "ListFirewallRuleGroupAssociationsRequestRequestTypeDef",
+    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
     "ListFirewallRuleGroupsRequestRequestTypeDef",
+    "ListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
     "ListFirewallRulesRequestRequestTypeDef",
+    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
     "ListResolverConfigsRequestRequestTypeDef",
+    "ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
     "ListResolverEndpointIpAddressesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutFirewallRuleGroupPolicyRequestRequestTypeDef",
+    "PutFirewallRuleGroupPolicyResponseTypeDef",
     "PutResolverQueryLogConfigPolicyRequestRequestTypeDef",
+    "PutResolverQueryLogConfigPolicyResponseTypeDef",
     "PutResolverRulePolicyRequestRequestTypeDef",
+    "PutResolverRulePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFirewallConfigRequestRequestTypeDef",
     "UpdateFirewallDomainsRequestRequestTypeDef",
+    "UpdateFirewallDomainsResponseTypeDef",
     "UpdateFirewallRuleGroupAssociationRequestRequestTypeDef",
     "UpdateFirewallRuleRequestRequestTypeDef",
+    "UpdateIpAddressTypeDef",
     "UpdateResolverConfigRequestRequestTypeDef",
     "UpdateResolverDnssecConfigRequestRequestTypeDef",
-    "UpdateResolverEndpointRequestRequestTypeDef",
     "AssociateFirewallRuleGroupRequestRequestTypeDef",
     "CreateFirewallDomainListRequestRequestTypeDef",
     "CreateFirewallRuleGroupRequestRequestTypeDef",
     "CreateResolverQueryLogConfigRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "AssociateFirewallRuleGroupResponseTypeDef",
     "DisassociateFirewallRuleGroupResponseTypeDef",
     "GetFirewallRuleGroupAssociationResponseTypeDef",
-    "GetFirewallRuleGroupPolicyResponseTypeDef",
-    "GetResolverQueryLogConfigPolicyResponseTypeDef",
-    "GetResolverRulePolicyResponseTypeDef",
-    "ImportFirewallDomainsResponseTypeDef",
-    "ListFirewallDomainsResponseTypeDef",
     "ListFirewallRuleGroupAssociationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutFirewallRuleGroupPolicyResponseTypeDef",
-    "PutResolverQueryLogConfigPolicyResponseTypeDef",
-    "PutResolverRulePolicyResponseTypeDef",
-    "UpdateFirewallDomainsResponseTypeDef",
     "UpdateFirewallRuleGroupAssociationResponseTypeDef",
     "AssociateResolverEndpointIpAddressRequestRequestTypeDef",
     "DisassociateResolverEndpointIpAddressRequestRequestTypeDef",
     "AssociateResolverEndpointIpAddressResponseTypeDef",
     "CreateResolverEndpointResponseTypeDef",
     "DeleteResolverEndpointResponseTypeDef",
     "DisassociateResolverEndpointIpAddressResponseTypeDef",
@@ -169,47 +180,39 @@
     "CreateResolverQueryLogConfigResponseTypeDef",
     "DeleteResolverQueryLogConfigResponseTypeDef",
     "GetResolverQueryLogConfigResponseTypeDef",
     "ListResolverQueryLogConfigsResponseTypeDef",
     "CreateResolverRuleRequestRequestTypeDef",
     "ResolverRuleConfigTypeDef",
     "ResolverRuleTypeDef",
+    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
     "ListResolverDnssecConfigsRequestRequestTypeDef",
+    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
     "ListResolverEndpointsRequestRequestTypeDef",
+    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
     "ListResolverQueryLogConfigAssociationsRequestRequestTypeDef",
+    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
     "ListResolverQueryLogConfigsRequestRequestTypeDef",
+    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
     "ListResolverRuleAssociationsRequestRequestTypeDef",
+    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
     "ListResolverRulesRequestRequestTypeDef",
     "GetFirewallConfigResponseTypeDef",
     "ListFirewallConfigsResponseTypeDef",
     "UpdateFirewallConfigResponseTypeDef",
     "ListFirewallDomainListsResponseTypeDef",
     "ListFirewallRuleGroupsResponseTypeDef",
     "GetResolverConfigResponseTypeDef",
     "ListResolverConfigsResponseTypeDef",
     "UpdateResolverConfigResponseTypeDef",
     "GetResolverDnssecConfigResponseTypeDef",
     "ListResolverDnssecConfigsResponseTypeDef",
     "UpdateResolverDnssecConfigResponseTypeDef",
     "ListResolverEndpointIpAddressesResponseTypeDef",
-    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
-    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
-    "ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
-    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
-    "ListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
-    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
-    "ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
-    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
-    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
-    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
-    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
-    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "UpdateResolverEndpointRequestRequestTypeDef",
     "UpdateResolverRuleRequestRequestTypeDef",
     "CreateResolverRuleResponseTypeDef",
     "DeleteResolverRuleResponseTypeDef",
     "GetResolverRuleResponseTypeDef",
     "ListResolverRulesResponseTypeDef",
     "UpdateResolverRuleResponseTypeDef",
 )
@@ -238,31 +241,21 @@
         "CreatorRequestId": str,
         "CreationTime": str,
         "ModificationTime": str,
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
 IpAddressUpdateTypeDef = TypedDict(
     "IpAddressUpdateTypeDef",
     {
         "IpId": str,
         "SubnetId": str,
         "Ip": str,
+        "Ipv6": str,
     },
     total=False,
 )
 
 ResolverEndpointTypeDef = TypedDict(
     "ResolverEndpointTypeDef",
     {
@@ -274,14 +267,15 @@
         "Direction": ResolverEndpointDirectionType,
         "IpAddressCount": int,
         "HostVPCId": str,
         "Status": ResolverEndpointStatusType,
         "StatusMessage": str,
         "CreationTime": str,
         "ModificationTime": str,
+        "ResolverEndpointType": ResolverEndpointTypeType,
     },
     total=False,
 )
 
 AssociateResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "AssociateResolverQueryLogConfigRequestRequestTypeDef",
     {
@@ -315,20 +309,22 @@
     "_OptionalAssociateResolverRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+
 class AssociateResolverRuleRequestRequestTypeDef(
     _RequiredAssociateResolverRuleRequestRequestTypeDef,
     _OptionalAssociateResolverRuleRequestRequestTypeDef,
 ):
     pass
 
+
 ResolverRuleAssociationTypeDef = TypedDict(
     "ResolverRuleAssociationTypeDef",
     {
         "Id": str,
         "ResolverRuleId": str,
         "Name": str,
         "VPCId": str,
@@ -391,20 +387,22 @@
         "BlockOverrideDomain": str,
         "BlockOverrideDnsType": Literal["CNAME"],
         "BlockOverrideTtl": int,
     },
     total=False,
 )
 
+
 class CreateFirewallRuleRequestRequestTypeDef(
     _RequiredCreateFirewallRuleRequestRequestTypeDef,
     _OptionalCreateFirewallRuleRequestRequestTypeDef,
 ):
     pass
 
+
 FirewallRuleTypeDef = TypedDict(
     "FirewallRuleTypeDef",
     {
         "FirewallRuleGroupId": str,
         "FirewallDomainListId": str,
         "Name": str,
         "Priority": int,
@@ -426,21 +424,24 @@
         "SubnetId": str,
     },
 )
 _OptionalIpAddressRequestTypeDef = TypedDict(
     "_OptionalIpAddressRequestTypeDef",
     {
         "Ip": str,
+        "Ipv6": str,
     },
     total=False,
 )
 
+
 class IpAddressRequestTypeDef(_RequiredIpAddressRequestTypeDef, _OptionalIpAddressRequestTypeDef):
     pass
 
+
 ResolverQueryLogConfigTypeDef = TypedDict(
     "ResolverQueryLogConfigTypeDef",
     {
         "Id": str,
         "OwnerId": str,
         "Status": ResolverQueryLogConfigStatusType,
         "ShareStatus": ShareStatusType,
@@ -450,31 +451,24 @@
         "DestinationArn": str,
         "CreatorRequestId": str,
         "CreationTime": str,
     },
     total=False,
 )
 
-_RequiredTargetAddressTypeDef = TypedDict(
-    "_RequiredTargetAddressTypeDef",
+TargetAddressTypeDef = TypedDict(
+    "TargetAddressTypeDef",
     {
         "Ip": str,
-    },
-)
-_OptionalTargetAddressTypeDef = TypedDict(
-    "_OptionalTargetAddressTypeDef",
-    {
         "Port": int,
+        "Ipv6": str,
     },
     total=False,
 )
 
-class TargetAddressTypeDef(_RequiredTargetAddressTypeDef, _OptionalTargetAddressTypeDef):
-    pass
-
 DeleteFirewallDomainListRequestRequestTypeDef = TypedDict(
     "DeleteFirewallDomainListRequestRequestTypeDef",
     {
         "FirewallDomainListId": str,
     },
 )
 
@@ -606,14 +600,22 @@
 GetFirewallRuleGroupPolicyRequestRequestTypeDef = TypedDict(
     "GetFirewallRuleGroupPolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
+    "GetFirewallRuleGroupPolicyResponseTypeDef",
+    {
+        "FirewallRuleGroupPolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "GetFirewallRuleGroupRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
     },
 )
 
@@ -670,14 +672,22 @@
 GetResolverQueryLogConfigPolicyRequestRequestTypeDef = TypedDict(
     "GetResolverQueryLogConfigPolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
+    "GetResolverQueryLogConfigPolicyResponseTypeDef",
+    {
+        "ResolverQueryLogConfigPolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "GetResolverQueryLogConfigRequestRequestTypeDef",
     {
         "ResolverQueryLogConfigId": str,
     },
 )
 
@@ -691,14 +701,22 @@
 GetResolverRulePolicyRequestRequestTypeDef = TypedDict(
     "GetResolverRulePolicyRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetResolverRulePolicyResponseTypeDef = TypedDict(
+    "GetResolverRulePolicyResponseTypeDef",
+    {
+        "ResolverRulePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverRuleRequestRequestTypeDef = TypedDict(
     "GetResolverRuleRequestRequestTypeDef",
     {
         "ResolverRuleId": str,
     },
 )
 
@@ -707,56 +725,96 @@
     {
         "FirewallDomainListId": str,
         "Operation": Literal["REPLACE"],
         "DomainFileUrl": str,
     },
 )
 
+ImportFirewallDomainsResponseTypeDef = TypedDict(
+    "ImportFirewallDomainsResponseTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Status": FirewallDomainListStatusType,
+        "StatusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IpAddressResponseTypeDef = TypedDict(
     "IpAddressResponseTypeDef",
     {
         "IpId": str,
         "SubnetId": str,
         "Ip": str,
+        "Ipv6": str,
         "Status": IpAddressStatusType,
         "StatusMessage": str,
         "CreationTime": str,
         "ModificationTime": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef = TypedDict(
+    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFirewallConfigsRequestRequestTypeDef = TypedDict(
     "ListFirewallConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef = TypedDict(
+    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallDomainListsRequestRequestTypeDef = TypedDict(
     "ListFirewallDomainListsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
+    "_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
+    {
+        "FirewallDomainListId": str,
+    },
+)
+_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
+    "_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef(
+    _RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
+    _OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFirewallDomainsRequestRequestTypeDef = TypedDict(
     "_RequiredListFirewallDomainsRequestRequestTypeDef",
     {
         "FirewallDomainListId": str,
     },
 )
 _OptionalListFirewallDomainsRequestRequestTypeDef = TypedDict(
@@ -764,42 +822,99 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListFirewallDomainsRequestRequestTypeDef(
     _RequiredListFirewallDomainsRequestRequestTypeDef,
     _OptionalListFirewallDomainsRequestRequestTypeDef,
 ):
     pass
 
+
+ListFirewallDomainsResponseTypeDef = TypedDict(
+    "ListFirewallDomainsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Domains": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef = (
+    TypedDict(
+        "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
+        {
+            "FirewallRuleGroupId": str,
+            "VpcId": str,
+            "Priority": int,
+            "Status": FirewallRuleGroupAssociationStatusType,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
 ListFirewallRuleGroupAssociationsRequestRequestTypeDef = TypedDict(
     "ListFirewallRuleGroupAssociationsRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
         "VpcId": str,
         "Priority": int,
         "Status": FirewallRuleGroupAssociationStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef = TypedDict(
+    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallRuleGroupsRequestRequestTypeDef = TypedDict(
     "ListFirewallRuleGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
+    "_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
+    {
+        "FirewallRuleGroupId": str,
+    },
+)
+_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
+    "_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
+    {
+        "Priority": int,
+        "Action": ActionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFirewallRulesRequestListFirewallRulesPaginateTypeDef(
+    _RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
+    _OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFirewallRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListFirewallRulesRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
     },
 )
 _OptionalListFirewallRulesRequestRequestTypeDef = TypedDict(
@@ -809,28 +924,60 @@
         "Action": ActionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListFirewallRulesRequestRequestTypeDef(
     _RequiredListFirewallRulesRequestRequestTypeDef, _OptionalListFirewallRulesRequestRequestTypeDef
 ):
     pass
 
+
+ListResolverConfigsRequestListResolverConfigsPaginateTypeDef = TypedDict(
+    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
+    "_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+    {
+        "ResolverEndpointId": str,
+    },
+)
+_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
+    "_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef(
+    _RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
+    _OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResolverEndpointIpAddressesRequestRequestTypeDef = TypedDict(
     "_RequiredListResolverEndpointIpAddressesRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
     },
 )
 _OptionalListResolverEndpointIpAddressesRequestRequestTypeDef = TypedDict(
@@ -838,20 +985,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListResolverEndpointIpAddressesRequestRequestTypeDef(
     _RequiredListResolverEndpointIpAddressesRequestRequestTypeDef,
     _OptionalListResolverEndpointIpAddressesRequestRequestTypeDef,
 ):
     pass
 
+
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
@@ -859,44 +1030,91 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
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
 PutFirewallRuleGroupPolicyRequestRequestTypeDef = TypedDict(
     "PutFirewallRuleGroupPolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "FirewallRuleGroupPolicy": str,
     },
 )
 
+PutFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
+    "PutFirewallRuleGroupPolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutResolverQueryLogConfigPolicyRequestRequestTypeDef = TypedDict(
     "PutResolverQueryLogConfigPolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "ResolverQueryLogConfigPolicy": str,
     },
 )
 
+PutResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
+    "PutResolverQueryLogConfigPolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutResolverRulePolicyRequestRequestTypeDef = TypedDict(
     "PutResolverRulePolicyRequestRequestTypeDef",
     {
         "Arn": str,
         "ResolverRulePolicy": str,
     },
 )
 
+PutResolverRulePolicyResponseTypeDef = TypedDict(
+    "PutResolverRulePolicyResponseTypeDef",
+    {
+        "ReturnValue": bool,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -914,14 +1132,25 @@
     {
         "FirewallDomainListId": str,
         "Operation": FirewallDomainUpdateOperationType,
         "Domains": Sequence[str],
     },
 )
 
+UpdateFirewallDomainsResponseTypeDef = TypedDict(
+    "UpdateFirewallDomainsResponseTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Status": FirewallDomainListStatusType,
+        "StatusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef",
     {
         "FirewallRuleGroupAssociationId": str,
     },
 )
 _OptionalUpdateFirewallRuleGroupAssociationRequestRequestTypeDef = TypedDict(
@@ -930,20 +1159,22 @@
         "Priority": int,
         "MutationProtection": MutationProtectionStatusType,
         "Name": str,
     },
     total=False,
 )
 
+
 class UpdateFirewallRuleGroupAssociationRequestRequestTypeDef(
     _RequiredUpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
     _OptionalUpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateFirewallRuleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallRuleRequestRequestTypeDef",
     {
         "FirewallRuleGroupId": str,
         "FirewallDomainListId": str,
     },
 )
@@ -957,20 +1188,30 @@
         "BlockOverrideDnsType": Literal["CNAME"],
         "BlockOverrideTtl": int,
         "Name": str,
     },
     total=False,
 )
 
+
 class UpdateFirewallRuleRequestRequestTypeDef(
     _RequiredUpdateFirewallRuleRequestRequestTypeDef,
     _OptionalUpdateFirewallRuleRequestRequestTypeDef,
 ):
     pass
 
+
+UpdateIpAddressTypeDef = TypedDict(
+    "UpdateIpAddressTypeDef",
+    {
+        "IpId": str,
+        "Ipv6": str,
+    },
+)
+
 UpdateResolverConfigRequestRequestTypeDef = TypedDict(
     "UpdateResolverConfigRequestRequestTypeDef",
     {
         "ResourceId": str,
         "AutodefinedReverseFlag": AutodefinedReverseFlagType,
     },
 )
@@ -979,34 +1220,14 @@
     "UpdateResolverDnssecConfigRequestRequestTypeDef",
     {
         "ResourceId": str,
         "Validation": ValidationType,
     },
 )
 
-_RequiredUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateResolverEndpointRequestRequestTypeDef",
-    {
-        "ResolverEndpointId": str,
-    },
-)
-_OptionalUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateResolverEndpointRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-    total=False,
-)
-
-class UpdateResolverEndpointRequestRequestTypeDef(
-    _RequiredUpdateResolverEndpointRequestRequestTypeDef,
-    _OptionalUpdateResolverEndpointRequestRequestTypeDef,
-):
-    pass
-
 _RequiredAssociateFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateFirewallRuleGroupRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "FirewallRuleGroupId": str,
         "VpcId": str,
         "Priority": int,
@@ -1018,20 +1239,22 @@
     {
         "MutationProtection": MutationProtectionStatusType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class AssociateFirewallRuleGroupRequestRequestTypeDef(
     _RequiredAssociateFirewallRuleGroupRequestRequestTypeDef,
     _OptionalAssociateFirewallRuleGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateFirewallDomainListRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallDomainListRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "Name": str,
     },
 )
@@ -1039,20 +1262,22 @@
     "_OptionalCreateFirewallDomainListRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateFirewallDomainListRequestRequestTypeDef(
     _RequiredCreateFirewallDomainListRequestRequestTypeDef,
     _OptionalCreateFirewallDomainListRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateFirewallRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallRuleGroupRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
         "Name": str,
     },
 )
@@ -1060,20 +1285,22 @@
     "_OptionalCreateFirewallRuleGroupRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateFirewallRuleGroupRequestRequestTypeDef(
     _RequiredCreateFirewallRuleGroupRequestRequestTypeDef,
     _OptionalCreateFirewallRuleGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateResolverQueryLogConfigRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverQueryLogConfigRequestRequestTypeDef",
     {
         "Name": str,
         "DestinationArn": str,
         "CreatorRequestId": str,
     },
@@ -1082,154 +1309,77 @@
     "_OptionalCreateResolverQueryLogConfigRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateResolverQueryLogConfigRequestRequestTypeDef(
     _RequiredCreateResolverQueryLogConfigRequestRequestTypeDef,
     _OptionalCreateResolverQueryLogConfigRequestRequestTypeDef,
 ):
     pass
 
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
 AssociateFirewallRuleGroupResponseTypeDef = TypedDict(
     "AssociateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateFirewallRuleGroupResponseTypeDef = TypedDict(
     "DisassociateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallRuleGroupAssociationResponseTypeDef = TypedDict(
     "GetFirewallRuleGroupAssociationResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
-    "GetFirewallRuleGroupPolicyResponseTypeDef",
-    {
-        "FirewallRuleGroupPolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
-    "GetResolverQueryLogConfigPolicyResponseTypeDef",
-    {
-        "ResolverQueryLogConfigPolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResolverRulePolicyResponseTypeDef = TypedDict(
-    "GetResolverRulePolicyResponseTypeDef",
-    {
-        "ResolverRulePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportFirewallDomainsResponseTypeDef = TypedDict(
-    "ImportFirewallDomainsResponseTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Status": FirewallDomainListStatusType,
-        "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFirewallDomainsResponseTypeDef = TypedDict(
-    "ListFirewallDomainsResponseTypeDef",
-    {
-        "NextToken": str,
-        "Domains": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRuleGroupAssociationsResponseTypeDef = TypedDict(
     "ListFirewallRuleGroupAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRuleGroupAssociations": List[FirewallRuleGroupAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutFirewallRuleGroupPolicyResponseTypeDef = TypedDict(
-    "PutFirewallRuleGroupPolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResolverQueryLogConfigPolicyResponseTypeDef = TypedDict(
-    "PutResolverQueryLogConfigPolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResolverRulePolicyResponseTypeDef = TypedDict(
-    "PutResolverRulePolicyResponseTypeDef",
-    {
-        "ReturnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDomainsResponseTypeDef = TypedDict(
-    "UpdateFirewallDomainsResponseTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Status": FirewallDomainListStatusType,
-        "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallRuleGroupAssociationResponseTypeDef = TypedDict(
     "UpdateFirewallRuleGroupAssociationResponseTypeDef",
     {
         "FirewallRuleGroupAssociation": FirewallRuleGroupAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverEndpointIpAddressRequestRequestTypeDef = TypedDict(
     "AssociateResolverEndpointIpAddressRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
@@ -1245,215 +1395,215 @@
     },
 )
 
 AssociateResolverEndpointIpAddressResponseTypeDef = TypedDict(
     "AssociateResolverEndpointIpAddressResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResolverEndpointResponseTypeDef = TypedDict(
     "CreateResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverEndpointResponseTypeDef = TypedDict(
     "DeleteResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverEndpointIpAddressResponseTypeDef = TypedDict(
     "DisassociateResolverEndpointIpAddressResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverEndpointResponseTypeDef = TypedDict(
     "GetResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverEndpointsResponseTypeDef = TypedDict(
     "ListResolverEndpointsResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverEndpoints": List[ResolverEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverEndpointResponseTypeDef = TypedDict(
     "UpdateResolverEndpointResponseTypeDef",
     {
         "ResolverEndpoint": ResolverEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "AssociateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "DisassociateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverQueryLogConfigAssociationResponseTypeDef = TypedDict(
     "GetResolverQueryLogConfigAssociationResponseTypeDef",
     {
         "ResolverQueryLogConfigAssociation": ResolverQueryLogConfigAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverQueryLogConfigAssociationsResponseTypeDef = TypedDict(
     "ListResolverQueryLogConfigAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "TotalCount": int,
         "TotalFilteredCount": int,
         "ResolverQueryLogConfigAssociations": List[ResolverQueryLogConfigAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResolverRuleResponseTypeDef = TypedDict(
     "AssociateResolverRuleResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResolverRuleResponseTypeDef = TypedDict(
     "DisassociateResolverRuleResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverRuleAssociationResponseTypeDef = TypedDict(
     "GetResolverRuleAssociationResponseTypeDef",
     {
         "ResolverRuleAssociation": ResolverRuleAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverRuleAssociationsResponseTypeDef = TypedDict(
     "ListResolverRuleAssociationsResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverRuleAssociations": List[ResolverRuleAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallDomainListResponseTypeDef = TypedDict(
     "CreateFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallDomainListResponseTypeDef = TypedDict(
     "DeleteFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallDomainListResponseTypeDef = TypedDict(
     "GetFirewallDomainListResponseTypeDef",
     {
         "FirewallDomainList": FirewallDomainListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallRuleGroupResponseTypeDef = TypedDict(
     "CreateFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallRuleGroupResponseTypeDef = TypedDict(
     "DeleteFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFirewallRuleGroupResponseTypeDef = TypedDict(
     "GetFirewallRuleGroupResponseTypeDef",
     {
         "FirewallRuleGroup": FirewallRuleGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFirewallRuleResponseTypeDef = TypedDict(
     "CreateFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallRuleResponseTypeDef = TypedDict(
     "DeleteFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRulesResponseTypeDef = TypedDict(
     "ListFirewallRulesResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRules": List[FirewallRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallRuleResponseTypeDef = TypedDict(
     "UpdateFirewallRuleResponseTypeDef",
     {
         "FirewallRule": FirewallRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateResolverEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverEndpointRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
@@ -1463,56 +1613,59 @@
     },
 )
 _OptionalCreateResolverEndpointRequestRequestTypeDef = TypedDict(
     "_OptionalCreateResolverEndpointRequestRequestTypeDef",
     {
         "Name": str,
         "Tags": Sequence[TagTypeDef],
+        "ResolverEndpointType": ResolverEndpointTypeType,
     },
     total=False,
 )
 
+
 class CreateResolverEndpointRequestRequestTypeDef(
     _RequiredCreateResolverEndpointRequestRequestTypeDef,
     _OptionalCreateResolverEndpointRequestRequestTypeDef,
 ):
     pass
 
+
 CreateResolverQueryLogConfigResponseTypeDef = TypedDict(
     "CreateResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverQueryLogConfigResponseTypeDef = TypedDict(
     "DeleteResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverQueryLogConfigResponseTypeDef = TypedDict(
     "GetResolverQueryLogConfigResponseTypeDef",
     {
         "ResolverQueryLogConfig": ResolverQueryLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverQueryLogConfigsResponseTypeDef = TypedDict(
     "ListResolverQueryLogConfigsResponseTypeDef",
     {
         "NextToken": str,
         "TotalCount": int,
         "TotalFilteredCount": int,
         "ResolverQueryLogConfigs": List[ResolverQueryLogConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateResolverRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResolverRuleRequestRequestTypeDef",
     {
         "CreatorRequestId": str,
@@ -1527,20 +1680,22 @@
         "TargetIps": Sequence[TargetAddressTypeDef],
         "ResolverEndpointId": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateResolverRuleRequestRequestTypeDef(
     _RequiredCreateResolverRuleRequestRequestTypeDef,
     _OptionalCreateResolverRuleRequestRequestTypeDef,
 ):
     pass
 
+
 ResolverRuleConfigTypeDef = TypedDict(
     "ResolverRuleConfigTypeDef",
     {
         "Name": str,
         "TargetIps": Sequence[TargetAddressTypeDef],
         "ResolverEndpointId": str,
     },
@@ -1564,409 +1719,305 @@
         "ShareStatus": ShareStatusType,
         "CreationTime": str,
         "ModificationTime": str,
     },
     total=False,
 )
 
+ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef = TypedDict(
+    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverDnssecConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverDnssecConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef = TypedDict(
+    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverEndpointsRequestRequestTypeDef = TypedDict(
     "ListResolverEndpointsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef = TypedDict(
+    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "SortBy": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverQueryLogConfigAssociationsRequestRequestTypeDef = TypedDict(
     "ListResolverQueryLogConfigAssociationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
 )
 
+ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef = TypedDict(
+    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "SortBy": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverQueryLogConfigsRequestRequestTypeDef = TypedDict(
     "ListResolverQueryLogConfigsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
 )
 
+ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef = TypedDict(
+    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverRuleAssociationsRequestRequestTypeDef = TypedDict(
     "ListResolverRuleAssociationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+ListResolverRulesRequestListResolverRulesPaginateTypeDef = TypedDict(
+    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResolverRulesRequestRequestTypeDef = TypedDict(
     "ListResolverRulesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
 GetFirewallConfigResponseTypeDef = TypedDict(
     "GetFirewallConfigResponseTypeDef",
     {
         "FirewallConfig": FirewallConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallConfigsResponseTypeDef = TypedDict(
     "ListFirewallConfigsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallConfigs": List[FirewallConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallConfigResponseTypeDef = TypedDict(
     "UpdateFirewallConfigResponseTypeDef",
     {
         "FirewallConfig": FirewallConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallDomainListsResponseTypeDef = TypedDict(
     "ListFirewallDomainListsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallDomainLists": List[FirewallDomainListMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallRuleGroupsResponseTypeDef = TypedDict(
     "ListFirewallRuleGroupsResponseTypeDef",
     {
         "NextToken": str,
         "FirewallRuleGroups": List[FirewallRuleGroupMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverConfigResponseTypeDef = TypedDict(
     "GetResolverConfigResponseTypeDef",
     {
         "ResolverConfig": ResolverConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverConfigsResponseTypeDef = TypedDict(
     "ListResolverConfigsResponseTypeDef",
     {
         "NextToken": str,
         "ResolverConfigs": List[ResolverConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverConfigResponseTypeDef = TypedDict(
     "UpdateResolverConfigResponseTypeDef",
     {
         "ResolverConfig": ResolverConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverDnssecConfigResponseTypeDef = TypedDict(
     "GetResolverDnssecConfigResponseTypeDef",
     {
         "ResolverDNSSECConfig": ResolverDnssecConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverDnssecConfigsResponseTypeDef = TypedDict(
     "ListResolverDnssecConfigsResponseTypeDef",
     {
         "NextToken": str,
         "ResolverDnssecConfigs": List[ResolverDnssecConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverDnssecConfigResponseTypeDef = TypedDict(
     "UpdateResolverDnssecConfigResponseTypeDef",
     {
         "ResolverDNSSECConfig": ResolverDnssecConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverEndpointIpAddressesResponseTypeDef = TypedDict(
     "ListResolverEndpointIpAddressesResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "IpAddresses": List[IpAddressResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef = TypedDict(
-    "ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef = TypedDict(
-    "ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
-    "_RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    {
-        "FirewallDomainListId": str,
-    },
-)
-_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef = TypedDict(
-    "_OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef(
-    _RequiredListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-    _OptionalListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-):
-    pass
-
-ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef = (
-    TypedDict(
-        "ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef",
-        {
-            "FirewallRuleGroupId": str,
-            "VpcId": str,
-            "Priority": int,
-            "Status": FirewallRuleGroupAssociationStatusType,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef = TypedDict(
-    "ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
-    "_RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    {
-        "FirewallRuleGroupId": str,
-    },
-)
-_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef = TypedDict(
-    "_OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef",
-    {
-        "Priority": int,
-        "Action": ActionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFirewallRulesRequestListFirewallRulesPaginateTypeDef(
-    _RequiredListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-    _OptionalListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-):
-    pass
-
-ListResolverConfigsRequestListResolverConfigsPaginateTypeDef = TypedDict(
-    "ListResolverConfigsRequestListResolverConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef = TypedDict(
-    "ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
-    "_RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
+_RequiredUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResolverEndpointRequestRequestTypeDef",
     {
         "ResolverEndpointId": str,
     },
 )
-_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef = TypedDict(
-    "_OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef(
-    _RequiredListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-    _OptionalListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-):
-    pass
-
-ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef = TypedDict(
-    "ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef = TypedDict(
-    "ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "SortBy": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef = TypedDict(
-    "ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "SortBy": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef = TypedDict(
-    "ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResolverRulesRequestListResolverRulesPaginateTypeDef = TypedDict(
-    "ListResolverRulesRequestListResolverRulesPaginateTypeDef",
+_OptionalUpdateResolverEndpointRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResolverEndpointRequestRequestTypeDef",
     {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Name": str,
+        "ResolverEndpointType": ResolverEndpointTypeType,
+        "UpdateIpAddresses": Sequence[UpdateIpAddressTypeDef],
     },
     total=False,
 )
 
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
 
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+class UpdateResolverEndpointRequestRequestTypeDef(
+    _RequiredUpdateResolverEndpointRequestRequestTypeDef,
+    _OptionalUpdateResolverEndpointRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateResolverRuleRequestRequestTypeDef = TypedDict(
     "UpdateResolverRuleRequestRequestTypeDef",
     {
         "ResolverRuleId": str,
         "Config": ResolverRuleConfigTypeDef,
     },
 )
 
 CreateResolverRuleResponseTypeDef = TypedDict(
     "CreateResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResolverRuleResponseTypeDef = TypedDict(
     "DeleteResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverRuleResponseTypeDef = TypedDict(
     "GetResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolverRulesResponseTypeDef = TypedDict(
     "ListResolverRulesResponseTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResolverRules": List[ResolverRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverRuleResponseTypeDef = TypedDict(
     "UpdateResolverRuleResponseTypeDef",
     {
         "ResolverRule": ResolverRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/PKG-INFO` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53resolver
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53Resolver 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53Resolver 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53resolver"></a>
 
 # types-aiobotocore-route53resolver
 
 [![PyPI - types-aiobotocore-route53resolver](https://img.shields.io/pypi/v/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53resolver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53resolver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53resolver?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53resolver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Resolver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
+[aiobotocore.Route53Resolver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53resolver.html#Route53Resolver)
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
 [types-aiobotocore-route53resolver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53resolver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -383,14 +383,15 @@
     ListResolverRulesPaginatorName,
     ListTagsForResourcePaginatorName,
     MutationProtectionStatusType,
     ResolverAutodefinedReverseStatusType,
     ResolverDNSSECValidationStatusType,
     ResolverEndpointDirectionType,
     ResolverEndpointStatusType,
+    ResolverEndpointTypeType,
     ResolverQueryLogConfigAssociationErrorType,
     ResolverQueryLogConfigAssociationStatusType,
     ResolverQueryLogConfigStatusType,
     ResolverRuleAssociationStatusType,
     ResolverRuleStatusType,
     RuleTypeOptionType,
     ShareStatusType,
@@ -415,15 +416,14 @@
 `types_aiobotocore_route53resolver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53resolver.type_defs import (
     TagTypeDef,
     FirewallRuleGroupAssociationTypeDef,
-    ResponseMetadataTypeDef,
     IpAddressUpdateTypeDef,
     ResolverEndpointTypeDef,
     AssociateResolverQueryLogConfigRequestRequestTypeDef,
     ResolverQueryLogConfigAssociationTypeDef,
     AssociateResolverRuleRequestRequestTypeDef,
     ResolverRuleAssociationTypeDef,
     FirewallDomainListTypeDef,
@@ -446,68 +446,78 @@
     FirewallConfigTypeDef,
     FirewallDomainListMetadataTypeDef,
     FirewallRuleGroupMetadataTypeDef,
     GetFirewallConfigRequestRequestTypeDef,
     GetFirewallDomainListRequestRequestTypeDef,
     GetFirewallRuleGroupAssociationRequestRequestTypeDef,
     GetFirewallRuleGroupPolicyRequestRequestTypeDef,
+    GetFirewallRuleGroupPolicyResponseTypeDef,
     GetFirewallRuleGroupRequestRequestTypeDef,
     GetResolverConfigRequestRequestTypeDef,
     ResolverConfigTypeDef,
     GetResolverDnssecConfigRequestRequestTypeDef,
     ResolverDnssecConfigTypeDef,
     GetResolverEndpointRequestRequestTypeDef,
     GetResolverQueryLogConfigAssociationRequestRequestTypeDef,
     GetResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    GetResolverQueryLogConfigPolicyResponseTypeDef,
     GetResolverQueryLogConfigRequestRequestTypeDef,
     GetResolverRuleAssociationRequestRequestTypeDef,
     GetResolverRulePolicyRequestRequestTypeDef,
+    GetResolverRulePolicyResponseTypeDef,
     GetResolverRuleRequestRequestTypeDef,
     ImportFirewallDomainsRequestRequestTypeDef,
+    ImportFirewallDomainsResponseTypeDef,
     IpAddressResponseTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
     ListFirewallConfigsRequestRequestTypeDef,
+    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
     ListFirewallDomainListsRequestRequestTypeDef,
+    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
     ListFirewallDomainsRequestRequestTypeDef,
+    ListFirewallDomainsResponseTypeDef,
+    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
     ListFirewallRuleGroupAssociationsRequestRequestTypeDef,
+    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
     ListFirewallRuleGroupsRequestRequestTypeDef,
+    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
     ListFirewallRulesRequestRequestTypeDef,
+    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
     ListResolverConfigsRequestRequestTypeDef,
+    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
     ListResolverEndpointIpAddressesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutFirewallRuleGroupPolicyRequestRequestTypeDef,
+    PutFirewallRuleGroupPolicyResponseTypeDef,
     PutResolverQueryLogConfigPolicyRequestRequestTypeDef,
+    PutResolverQueryLogConfigPolicyResponseTypeDef,
     PutResolverRulePolicyRequestRequestTypeDef,
+    PutResolverRulePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallConfigRequestRequestTypeDef,
     UpdateFirewallDomainsRequestRequestTypeDef,
+    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationRequestRequestTypeDef,
     UpdateFirewallRuleRequestRequestTypeDef,
+    UpdateIpAddressTypeDef,
     UpdateResolverConfigRequestRequestTypeDef,
     UpdateResolverDnssecConfigRequestRequestTypeDef,
-    UpdateResolverEndpointRequestRequestTypeDef,
     AssociateFirewallRuleGroupRequestRequestTypeDef,
     CreateFirewallDomainListRequestRequestTypeDef,
     CreateFirewallRuleGroupRequestRequestTypeDef,
     CreateResolverQueryLogConfigRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     AssociateFirewallRuleGroupResponseTypeDef,
     DisassociateFirewallRuleGroupResponseTypeDef,
     GetFirewallRuleGroupAssociationResponseTypeDef,
-    GetFirewallRuleGroupPolicyResponseTypeDef,
-    GetResolverQueryLogConfigPolicyResponseTypeDef,
-    GetResolverRulePolicyResponseTypeDef,
-    ImportFirewallDomainsResponseTypeDef,
-    ListFirewallDomainsResponseTypeDef,
     ListFirewallRuleGroupAssociationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutFirewallRuleGroupPolicyResponseTypeDef,
-    PutResolverQueryLogConfigPolicyResponseTypeDef,
-    PutResolverRulePolicyResponseTypeDef,
-    UpdateFirewallDomainsResponseTypeDef,
     UpdateFirewallRuleGroupAssociationResponseTypeDef,
     AssociateResolverEndpointIpAddressRequestRequestTypeDef,
     DisassociateResolverEndpointIpAddressRequestRequestTypeDef,
     AssociateResolverEndpointIpAddressResponseTypeDef,
     CreateResolverEndpointResponseTypeDef,
     DeleteResolverEndpointResponseTypeDef,
     DisassociateResolverEndpointIpAddressResponseTypeDef,
@@ -536,47 +546,39 @@
     CreateResolverQueryLogConfigResponseTypeDef,
     DeleteResolverQueryLogConfigResponseTypeDef,
     GetResolverQueryLogConfigResponseTypeDef,
     ListResolverQueryLogConfigsResponseTypeDef,
     CreateResolverRuleRequestRequestTypeDef,
     ResolverRuleConfigTypeDef,
     ResolverRuleTypeDef,
+    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
     ListResolverDnssecConfigsRequestRequestTypeDef,
+    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
     ListResolverEndpointsRequestRequestTypeDef,
+    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
     ListResolverQueryLogConfigAssociationsRequestRequestTypeDef,
+    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
     ListResolverQueryLogConfigsRequestRequestTypeDef,
+    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
     ListResolverRuleAssociationsRequestRequestTypeDef,
+    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
     ListResolverRulesRequestRequestTypeDef,
     GetFirewallConfigResponseTypeDef,
     ListFirewallConfigsResponseTypeDef,
     UpdateFirewallConfigResponseTypeDef,
     ListFirewallDomainListsResponseTypeDef,
     ListFirewallRuleGroupsResponseTypeDef,
     GetResolverConfigResponseTypeDef,
     ListResolverConfigsResponseTypeDef,
     UpdateResolverConfigResponseTypeDef,
     GetResolverDnssecConfigResponseTypeDef,
     ListResolverDnssecConfigsResponseTypeDef,
     UpdateResolverDnssecConfigResponseTypeDef,
     ListResolverEndpointIpAddressesResponseTypeDef,
-    ListFirewallConfigsRequestListFirewallConfigsPaginateTypeDef,
-    ListFirewallDomainListsRequestListFirewallDomainListsPaginateTypeDef,
-    ListFirewallDomainsRequestListFirewallDomainsPaginateTypeDef,
-    ListFirewallRuleGroupAssociationsRequestListFirewallRuleGroupAssociationsPaginateTypeDef,
-    ListFirewallRuleGroupsRequestListFirewallRuleGroupsPaginateTypeDef,
-    ListFirewallRulesRequestListFirewallRulesPaginateTypeDef,
-    ListResolverConfigsRequestListResolverConfigsPaginateTypeDef,
-    ListResolverDnssecConfigsRequestListResolverDnssecConfigsPaginateTypeDef,
-    ListResolverEndpointIpAddressesRequestListResolverEndpointIpAddressesPaginateTypeDef,
-    ListResolverEndpointsRequestListResolverEndpointsPaginateTypeDef,
-    ListResolverQueryLogConfigAssociationsRequestListResolverQueryLogConfigAssociationsPaginateTypeDef,
-    ListResolverQueryLogConfigsRequestListResolverQueryLogConfigsPaginateTypeDef,
-    ListResolverRuleAssociationsRequestListResolverRuleAssociationsPaginateTypeDef,
-    ListResolverRulesRequestListResolverRulesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    UpdateResolverEndpointRequestRequestTypeDef,
     UpdateResolverRuleRequestRequestTypeDef,
     CreateResolverRuleResponseTypeDef,
     DeleteResolverRuleResponseTypeDef,
     GetResolverRuleResponseTypeDef,
     ListResolverRulesResponseTypeDef,
     UpdateResolverRuleResponseTypeDef,
 )
@@ -589,43 +591,43 @@
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

### Comparing `types-aiobotocore-route53resolver-2.5.0.post1/types_aiobotocore_route53resolver.egg-info/SOURCES.txt` & `types-aiobotocore-route53resolver-2.5.1/types_aiobotocore_route53resolver.egg-info/SOURCES.txt`

 * *Files identical despite different names*

