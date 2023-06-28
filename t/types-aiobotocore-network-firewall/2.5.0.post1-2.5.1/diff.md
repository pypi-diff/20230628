# Comparing `tmp/types-aiobotocore-network-firewall-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-network-firewall-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-network-firewall-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-network-firewall-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-network-firewall-2.5.0.post1.tar` & `types-aiobotocore-network-firewall-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.559464 types-aiobotocore-network-firewall-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18581 2023-03-11 12:27:03.559464 types-aiobotocore-network-firewall-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16975 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.559464 types-aiobotocore-network-firewall-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.555464 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/
--rw-r--r--   0 runner    (1001) docker     (123)     1376 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1375 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29403 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    29359 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10476 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10474 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5993 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5986 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39754 2023-03-11 12:19:08.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    39704 2023-03-11 12:19:07.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:06.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.555464 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18581 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:27:03.000000 types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.326183 types-aiobotocore-network-firewall-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19798 2023-06-28 01:43:54.326183 types-aiobotocore-network-firewall-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18198 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.326183 types-aiobotocore-network-firewall-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:35:49.000000 types-aiobotocore-network-firewall-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.322183 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/
+-rw-r--r--   0 runner    (1001) docker     (123)     1672 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1671 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34077 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34027 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10942 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10940 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7201 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7194 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    47547 2023-06-28 01:35:52.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47491 2023-06-28 01:35:52.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:51.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.326183 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19798 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:54.000000 types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/LICENSE` & `types-aiobotocore-network-firewall-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/PKG-INFO` & `types-aiobotocore-network-firewall-2.5.1/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-network-firewall
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NetworkFirewall 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NetworkFirewall 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-network-firewall"></a>
 
 # types-aiobotocore-network-firewall
 
 [![PyPI - types-aiobotocore-network-firewall](https://img.shields.io/pypi/v/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-network-firewall?color=blue)](https://pypistats.org/packages/types-aiobotocore-network-firewall)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkFirewall 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
+[aiobotocore.NetworkFirewall 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
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
 [types-aiobotocore-network-firewall docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,28 +276,32 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_network_firewall import NetworkFirewallClient
 from types_aiobotocore_network_firewall.paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
+    ListTLSInspectionConfigurationsPaginator,
     ListTagsForResourcePaginator,
 )
 
 session = get_session()
 async with session.create_client("network-firewall") as client:
     client: NetworkFirewallClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator(
         "list_firewall_policies"
     )
     list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
     list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+    list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = (
+        client.get_paginator("list_tls_inspection_configurations")
+    )
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator(
         "list_tags_for_resource"
     )
 ```
 
 <a id="literals"></a>
 
@@ -313,14 +317,15 @@
     EncryptionTypeType,
     FirewallStatusValueType,
     GeneratedRulesTypeType,
     IPAddressTypeType,
     ListFirewallPoliciesPaginatorName,
     ListFirewallsPaginatorName,
     ListRuleGroupsPaginatorName,
+    ListTLSInspectionConfigurationsPaginatorName,
     ListTagsForResourcePaginatorName,
     LogDestinationTypeType,
     LogTypeType,
     OverrideActionType,
     PerObjectSyncStatusType,
     ResourceManagedStatusType,
     ResourceManagedTypeType,
@@ -352,66 +357,77 @@
 `types_aiobotocore_network_firewall.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_network_firewall.type_defs import (
     AddressTypeDef,
     AssociateFirewallPolicyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateFirewallPolicyResponseTypeDef,
     SubnetMappingTypeDef,
     AttachmentTypeDef,
     IPSetMetadataTypeDef,
     EncryptionConfigurationTypeDef,
     TagTypeDef,
     SourceMetadataTypeDef,
     DeleteFirewallPolicyRequestRequestTypeDef,
     DeleteFirewallRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
+    DeleteTLSInspectionConfigurationRequestRequestTypeDef,
     DescribeFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallRequestRequestTypeDef,
     DescribeLoggingConfigurationRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeRuleGroupMetadataRequestRequestTypeDef,
     StatefulRuleOptionsTypeDef,
     DescribeRuleGroupRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationRequestRequestTypeDef,
     DimensionTypeDef,
     DisassociateSubnetsRequestRequestTypeDef,
     FirewallMetadataTypeDef,
     FirewallPolicyMetadataTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupReferenceTypeDef,
     HeaderTypeDef,
     IPSetReferenceTypeDef,
     IPSetTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
     ListFirewallPoliciesRequestRequestTypeDef,
+    ListFirewallsRequestListFirewallsPaginateTypeDef,
     ListFirewallsRequestRequestTypeDef,
+    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     RuleGroupMetadataTypeDef,
+    ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef,
+    ListTLSInspectionConfigurationsRequestRequestTypeDef,
+    TLSInspectionConfigurationMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     LogDestinationConfigTypeDef,
     PortRangeTypeDef,
     TCPFlagFieldTypeDef,
+    PaginatorConfigTypeDef,
     PerObjectStatusTypeDef,
     PortSetTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuleOptionTypeDef,
     RulesSourceListTypeDef,
+    ServerCertificateTypeDef,
     StatefulRuleGroupOverrideTypeDef,
+    TlsCertificateDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallDeleteProtectionRequestRequestTypeDef,
-    UpdateFirewallDescriptionRequestRequestTypeDef,
-    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
-    UpdateSubnetChangeProtectionRequestRequestTypeDef,
-    AssociateFirewallPolicyResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
     UpdateFirewallDeleteProtectionResponseTypeDef,
+    UpdateFirewallDescriptionRequestRequestTypeDef,
     UpdateFirewallDescriptionResponseTypeDef,
+    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
     UpdateFirewallPolicyChangeProtectionResponseTypeDef,
+    UpdateSubnetChangeProtectionRequestRequestTypeDef,
     UpdateSubnetChangeProtectionResponseTypeDef,
     AssociateSubnetsRequestRequestTypeDef,
     AssociateSubnetsResponseTypeDef,
     DisassociateSubnetsResponseTypeDef,
     CIDRSummaryTypeDef,
     UpdateFirewallEncryptionConfigurationRequestRequestTypeDef,
     UpdateFirewallEncryptionConfigurationResponseTypeDef,
@@ -422,44 +438,52 @@
     TagResourceRequestRequestTypeDef,
     RuleGroupResponseTypeDef,
     DescribeRuleGroupMetadataResponseTypeDef,
     PublishMetricActionTypeDef,
     ListFirewallsResponseTypeDef,
     ListFirewallPoliciesResponseTypeDef,
     ReferenceSetsTypeDef,
-    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
-    ListFirewallsRequestListFirewallsPaginateTypeDef,
-    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    PolicyVariablesTypeDef,
     ListRuleGroupsResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     LoggingConfigurationTypeDef,
+    ServerCertificateScopeTypeDef,
     MatchAttributesTypeDef,
     SyncStateTypeDef,
     RuleVariablesTypeDef,
     StatefulRuleTypeDef,
     StatefulRuleGroupReferenceTypeDef,
+    TLSInspectionConfigurationResponseTypeDef,
     CapacityUsageSummaryTypeDef,
     CreateFirewallPolicyResponseTypeDef,
     DeleteFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     DeleteRuleGroupResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     ActionDefinitionTypeDef,
     DescribeLoggingConfigurationResponseTypeDef,
     UpdateLoggingConfigurationRequestRequestTypeDef,
     UpdateLoggingConfigurationResponseTypeDef,
+    ServerCertificateConfigurationTypeDef,
     RuleDefinitionTypeDef,
+    CreateTLSInspectionConfigurationResponseTypeDef,
+    DeleteTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationResponseTypeDef,
     FirewallStatusTypeDef,
     CustomActionTypeDef,
+    TLSInspectionConfigurationTypeDef,
     StatelessRuleTypeDef,
     CreateFirewallResponseTypeDef,
     DeleteFirewallResponseTypeDef,
     DescribeFirewallResponseTypeDef,
     FirewallPolicyTypeDef,
+    CreateTLSInspectionConfigurationRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationRequestRequestTypeDef,
     StatelessRulesAndCustomActionsTypeDef,
     CreateFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyRequestRequestTypeDef,
     RulesSourceTypeDef,
     RuleGroupTypeDef,
     CreateRuleGroupRequestRequestTypeDef,
@@ -475,43 +499,43 @@
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/README.md` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-network-firewall
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NetworkFirewall 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore network-firewall type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-network-firewall"></a>
 
 # types-aiobotocore-network-firewall
 
 [![PyPI - types-aiobotocore-network-firewall](https://img.shields.io/pypi/v/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-network-firewall?color=blue)](https://pypistats.org/packages/types-aiobotocore-network-firewall)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkFirewall 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
+[aiobotocore.NetworkFirewall 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
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
 [types-aiobotocore-network-firewall docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/).
 
 See how it helps to find and fix potential bugs:
 
@@ -243,28 +276,32 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_network_firewall import NetworkFirewallClient
 from types_aiobotocore_network_firewall.paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
+    ListTLSInspectionConfigurationsPaginator,
     ListTagsForResourcePaginator,
 )
 
 session = get_session()
 async with session.create_client("network-firewall") as client:
     client: NetworkFirewallClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator(
         "list_firewall_policies"
     )
     list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
     list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+    list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = (
+        client.get_paginator("list_tls_inspection_configurations")
+    )
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator(
         "list_tags_for_resource"
     )
 ```
 
 <a id="literals"></a>
 
@@ -280,14 +317,15 @@
     EncryptionTypeType,
     FirewallStatusValueType,
     GeneratedRulesTypeType,
     IPAddressTypeType,
     ListFirewallPoliciesPaginatorName,
     ListFirewallsPaginatorName,
     ListRuleGroupsPaginatorName,
+    ListTLSInspectionConfigurationsPaginatorName,
     ListTagsForResourcePaginatorName,
     LogDestinationTypeType,
     LogTypeType,
     OverrideActionType,
     PerObjectSyncStatusType,
     ResourceManagedStatusType,
     ResourceManagedTypeType,
@@ -319,66 +357,77 @@
 `types_aiobotocore_network_firewall.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_network_firewall.type_defs import (
     AddressTypeDef,
     AssociateFirewallPolicyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateFirewallPolicyResponseTypeDef,
     SubnetMappingTypeDef,
     AttachmentTypeDef,
     IPSetMetadataTypeDef,
     EncryptionConfigurationTypeDef,
     TagTypeDef,
     SourceMetadataTypeDef,
     DeleteFirewallPolicyRequestRequestTypeDef,
     DeleteFirewallRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
+    DeleteTLSInspectionConfigurationRequestRequestTypeDef,
     DescribeFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallRequestRequestTypeDef,
     DescribeLoggingConfigurationRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeRuleGroupMetadataRequestRequestTypeDef,
     StatefulRuleOptionsTypeDef,
     DescribeRuleGroupRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationRequestRequestTypeDef,
     DimensionTypeDef,
     DisassociateSubnetsRequestRequestTypeDef,
     FirewallMetadataTypeDef,
     FirewallPolicyMetadataTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupReferenceTypeDef,
     HeaderTypeDef,
     IPSetReferenceTypeDef,
     IPSetTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
     ListFirewallPoliciesRequestRequestTypeDef,
+    ListFirewallsRequestListFirewallsPaginateTypeDef,
     ListFirewallsRequestRequestTypeDef,
+    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     RuleGroupMetadataTypeDef,
+    ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef,
+    ListTLSInspectionConfigurationsRequestRequestTypeDef,
+    TLSInspectionConfigurationMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     LogDestinationConfigTypeDef,
     PortRangeTypeDef,
     TCPFlagFieldTypeDef,
+    PaginatorConfigTypeDef,
     PerObjectStatusTypeDef,
     PortSetTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuleOptionTypeDef,
     RulesSourceListTypeDef,
+    ServerCertificateTypeDef,
     StatefulRuleGroupOverrideTypeDef,
+    TlsCertificateDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallDeleteProtectionRequestRequestTypeDef,
-    UpdateFirewallDescriptionRequestRequestTypeDef,
-    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
-    UpdateSubnetChangeProtectionRequestRequestTypeDef,
-    AssociateFirewallPolicyResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
     UpdateFirewallDeleteProtectionResponseTypeDef,
+    UpdateFirewallDescriptionRequestRequestTypeDef,
     UpdateFirewallDescriptionResponseTypeDef,
+    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
     UpdateFirewallPolicyChangeProtectionResponseTypeDef,
+    UpdateSubnetChangeProtectionRequestRequestTypeDef,
     UpdateSubnetChangeProtectionResponseTypeDef,
     AssociateSubnetsRequestRequestTypeDef,
     AssociateSubnetsResponseTypeDef,
     DisassociateSubnetsResponseTypeDef,
     CIDRSummaryTypeDef,
     UpdateFirewallEncryptionConfigurationRequestRequestTypeDef,
     UpdateFirewallEncryptionConfigurationResponseTypeDef,
@@ -389,44 +438,52 @@
     TagResourceRequestRequestTypeDef,
     RuleGroupResponseTypeDef,
     DescribeRuleGroupMetadataResponseTypeDef,
     PublishMetricActionTypeDef,
     ListFirewallsResponseTypeDef,
     ListFirewallPoliciesResponseTypeDef,
     ReferenceSetsTypeDef,
-    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
-    ListFirewallsRequestListFirewallsPaginateTypeDef,
-    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    PolicyVariablesTypeDef,
     ListRuleGroupsResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     LoggingConfigurationTypeDef,
+    ServerCertificateScopeTypeDef,
     MatchAttributesTypeDef,
     SyncStateTypeDef,
     RuleVariablesTypeDef,
     StatefulRuleTypeDef,
     StatefulRuleGroupReferenceTypeDef,
+    TLSInspectionConfigurationResponseTypeDef,
     CapacityUsageSummaryTypeDef,
     CreateFirewallPolicyResponseTypeDef,
     DeleteFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     DeleteRuleGroupResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     ActionDefinitionTypeDef,
     DescribeLoggingConfigurationResponseTypeDef,
     UpdateLoggingConfigurationRequestRequestTypeDef,
     UpdateLoggingConfigurationResponseTypeDef,
+    ServerCertificateConfigurationTypeDef,
     RuleDefinitionTypeDef,
+    CreateTLSInspectionConfigurationResponseTypeDef,
+    DeleteTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationResponseTypeDef,
     FirewallStatusTypeDef,
     CustomActionTypeDef,
+    TLSInspectionConfigurationTypeDef,
     StatelessRuleTypeDef,
     CreateFirewallResponseTypeDef,
     DeleteFirewallResponseTypeDef,
     DescribeFirewallResponseTypeDef,
     FirewallPolicyTypeDef,
+    CreateTLSInspectionConfigurationRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationRequestRequestTypeDef,
     StatelessRulesAndCustomActionsTypeDef,
     CreateFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyRequestRequestTypeDef,
     RulesSourceTypeDef,
     RuleGroupTypeDef,
     CreateRuleGroupRequestRequestTypeDef,
@@ -442,43 +499,43 @@
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/setup.py` & `types-aiobotocore-network-firewall-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-network-firewall.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-network-firewall",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_network_firewall"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.NetworkFirewall 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.NetworkFirewall 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/"
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__init__.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__init__.py`

 * *Files 26% similar despite different names*

```diff
@@ -6,42 +6,46 @@
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_network_firewall import (
         Client,
         ListFirewallPoliciesPaginator,
         ListFirewallsPaginator,
         ListRuleGroupsPaginator,
+        ListTLSInspectionConfigurationsPaginator,
         ListTagsForResourcePaginator,
         NetworkFirewallClient,
     )
 
     session = get_session()
     async with session.create_client("network-firewall") as client:
         client: NetworkFirewallClient
         ...
 
 
     list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator("list_firewall_policies")
     list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
     list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+    list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = client.get_paginator("list_tls_inspection_configurations")
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
 from .client import NetworkFirewallClient
 from .paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
     ListTagsForResourcePaginator,
+    ListTLSInspectionConfigurationsPaginator,
 )
 
 Client = NetworkFirewallClient
 
 
 __all__ = (
     "Client",
     "ListFirewallPoliciesPaginator",
     "ListFirewallsPaginator",
     "ListRuleGroupsPaginator",
+    "ListTLSInspectionConfigurationsPaginator",
     "ListTagsForResourcePaginator",
     "NetworkFirewallClient",
 )
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__init__.pyi` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__init__.pyi`

 * *Files 26% similar despite different names*

```diff
@@ -6,41 +6,45 @@
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_network_firewall import (
         Client,
         ListFirewallPoliciesPaginator,
         ListFirewallsPaginator,
         ListRuleGroupsPaginator,
+        ListTLSInspectionConfigurationsPaginator,
         ListTagsForResourcePaginator,
         NetworkFirewallClient,
     )
 
     session = get_session()
     async with session.create_client("network-firewall") as client:
         client: NetworkFirewallClient
         ...
 
 
     list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator("list_firewall_policies")
     list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
     list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+    list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = client.get_paginator("list_tls_inspection_configurations")
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
 from .client import NetworkFirewallClient
 from .paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
     ListTagsForResourcePaginator,
+    ListTLSInspectionConfigurationsPaginator,
 )
 
 Client = NetworkFirewallClient
 
 __all__ = (
     "Client",
     "ListFirewallPoliciesPaginator",
     "ListFirewallsPaginator",
     "ListRuleGroupsPaginator",
+    "ListTLSInspectionConfigurationsPaginator",
     "ListTagsForResourcePaginator",
     "NetworkFirewallClient",
 )
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/__main__.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.NetworkFirewall 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.NetworkFirewall 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall\nOther"
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/client.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,50 +22,57 @@
 
 from .literals import ResourceManagedStatusType, ResourceManagedTypeType, RuleGroupTypeType
 from .paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
     ListTagsForResourcePaginator,
+    ListTLSInspectionConfigurationsPaginator,
 )
 from .type_defs import (
     AssociateFirewallPolicyResponseTypeDef,
     AssociateSubnetsResponseTypeDef,
     CreateFirewallPolicyResponseTypeDef,
     CreateFirewallResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
+    CreateTLSInspectionConfigurationResponseTypeDef,
     DeleteFirewallPolicyResponseTypeDef,
     DeleteFirewallResponseTypeDef,
     DeleteRuleGroupResponseTypeDef,
+    DeleteTLSInspectionConfigurationResponseTypeDef,
     DescribeFirewallPolicyResponseTypeDef,
     DescribeFirewallResponseTypeDef,
     DescribeLoggingConfigurationResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeRuleGroupMetadataResponseTypeDef,
     DescribeRuleGroupResponseTypeDef,
+    DescribeTLSInspectionConfigurationResponseTypeDef,
     DisassociateSubnetsResponseTypeDef,
     EncryptionConfigurationTypeDef,
     FirewallPolicyTypeDef,
     ListFirewallPoliciesResponseTypeDef,
     ListFirewallsResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     LoggingConfigurationTypeDef,
     RuleGroupTypeDef,
     SourceMetadataTypeDef,
     SubnetMappingTypeDef,
     TagTypeDef,
+    TLSInspectionConfigurationTypeDef,
     UpdateFirewallDeleteProtectionResponseTypeDef,
     UpdateFirewallDescriptionResponseTypeDef,
     UpdateFirewallEncryptionConfigurationResponseTypeDef,
     UpdateFirewallPolicyChangeProtectionResponseTypeDef,
     UpdateFirewallPolicyResponseTypeDef,
     UpdateLoggingConfigurationResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     UpdateSubnetChangeProtectionResponseTypeDef,
+    UpdateTLSInspectionConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -217,14 +224,30 @@
         Creates the specified stateless or stateful rule group, which includes the rules
         for network traffic inspection, a capacity setting, and tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_rule_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#create_rule_group)
         """
 
+    async def create_tls_inspection_configuration(
+        self,
+        *,
+        TLSInspectionConfigurationName: str,
+        TLSInspectionConfiguration: TLSInspectionConfigurationTypeDef,
+        Description: str = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        EncryptionConfiguration: EncryptionConfigurationTypeDef = ...
+    ) -> CreateTLSInspectionConfigurationResponseTypeDef:
+        """
+        Creates an Network Firewall TLS inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#create_tls_inspection_configuration)
+        """
+
     async def delete_firewall(
         self, *, FirewallName: str = ..., FirewallArn: str = ...
     ) -> DeleteFirewallResponseTypeDef:
         """
         Deletes the specified  Firewall and its  FirewallStatus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_firewall)
@@ -255,14 +278,24 @@
         """
         Deletes the specified  RuleGroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_rule_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#delete_rule_group)
         """
 
+    async def delete_tls_inspection_configuration(
+        self, *, TLSInspectionConfigurationArn: str = ..., TLSInspectionConfigurationName: str = ...
+    ) -> DeleteTLSInspectionConfigurationResponseTypeDef:
+        """
+        Deletes the specified  TLSInspectionConfiguration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#delete_tls_inspection_configuration)
+        """
+
     async def describe_firewall(
         self, *, FirewallName: str = ..., FirewallArn: str = ...
     ) -> DescribeFirewallResponseTypeDef:
         """
         Returns the data objects for the specified firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_firewall)
@@ -316,14 +349,24 @@
         High-level information about a rule group, returned by operations like create
         and describe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_rule_group_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#describe_rule_group_metadata)
         """
 
+    async def describe_tls_inspection_configuration(
+        self, *, TLSInspectionConfigurationArn: str = ..., TLSInspectionConfigurationName: str = ...
+    ) -> DescribeTLSInspectionConfigurationResponseTypeDef:
+        """
+        Returns the data objects for the specified TLS inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#describe_tls_inspection_configuration)
+        """
+
     async def disassociate_subnets(
         self,
         *,
         SubnetIds: Sequence[str],
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
@@ -391,14 +434,25 @@
         """
         Retrieves the tags associated with the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#list_tags_for_resource)
         """
 
+    async def list_tls_inspection_configurations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListTLSInspectionConfigurationsResponseTypeDef:
+        """
+        Retrieves the metadata for the TLS inspection configurations that you have
+        defined.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_tls_inspection_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#list_tls_inspection_configurations)
+        """
+
     async def put_resource_policy(self, *, ResourceArn: str, Policy: str) -> Dict[str, Any]:
         """
         Creates or updates an IAM policy for your rule group or firewall policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.put_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#put_resource_policy)
         """
@@ -424,16 +478,16 @@
         *,
         DeleteProtection: bool,
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
     ) -> UpdateFirewallDeleteProtectionResponseTypeDef:
         """
-        Modifies the flag, `DeleteProtection` , which indicates whether it is possible
-        to delete the firewall.
+        Modifies the flag, `DeleteProtection`, which indicates whether it is possible to
+        delete the firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_delete_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_firewall_delete_protection)
         """
 
     async def update_firewall_description(
         self,
@@ -488,16 +542,16 @@
         *,
         FirewallPolicyChangeProtection: bool,
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
     ) -> UpdateFirewallPolicyChangeProtectionResponseTypeDef:
         """
-        Modifies the flag, `ChangeProtection` , which indicates whether it is possible
-        to change the firewall.
+        Modifies the flag, `ChangeProtection`, which indicates whether it is possible to
+        change the firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_policy_change_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_firewall_policy_change_protection)
         """
 
     async def update_logging_configuration(
         self,
@@ -547,14 +601,32 @@
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/network-
         firewall-2020-11-12/UpdateSubnetChangeProtection).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_subnet_change_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_subnet_change_protection)
         """
 
+    async def update_tls_inspection_configuration(
+        self,
+        *,
+        TLSInspectionConfiguration: TLSInspectionConfigurationTypeDef,
+        UpdateToken: str,
+        TLSInspectionConfigurationArn: str = ...,
+        TLSInspectionConfigurationName: str = ...,
+        Description: str = ...,
+        EncryptionConfiguration: EncryptionConfigurationTypeDef = ...
+    ) -> UpdateTLSInspectionConfigurationResponseTypeDef:
+        """
+        Updates the TLS inspection configuration settings for the specified TLS
+        inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_tls_inspection_configuration)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_firewall_policies"]
     ) -> ListFirewallPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
@@ -572,14 +644,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_tls_inspection_configurations"]
+    ) -> ListTLSInspectionConfigurationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_tags_for_resource"]
     ) -> ListTagsForResourcePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/client.pyi` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/client.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -22,50 +22,57 @@
 
 from .literals import ResourceManagedStatusType, ResourceManagedTypeType, RuleGroupTypeType
 from .paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
     ListTagsForResourcePaginator,
+    ListTLSInspectionConfigurationsPaginator,
 )
 from .type_defs import (
     AssociateFirewallPolicyResponseTypeDef,
     AssociateSubnetsResponseTypeDef,
     CreateFirewallPolicyResponseTypeDef,
     CreateFirewallResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
+    CreateTLSInspectionConfigurationResponseTypeDef,
     DeleteFirewallPolicyResponseTypeDef,
     DeleteFirewallResponseTypeDef,
     DeleteRuleGroupResponseTypeDef,
+    DeleteTLSInspectionConfigurationResponseTypeDef,
     DescribeFirewallPolicyResponseTypeDef,
     DescribeFirewallResponseTypeDef,
     DescribeLoggingConfigurationResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeRuleGroupMetadataResponseTypeDef,
     DescribeRuleGroupResponseTypeDef,
+    DescribeTLSInspectionConfigurationResponseTypeDef,
     DisassociateSubnetsResponseTypeDef,
     EncryptionConfigurationTypeDef,
     FirewallPolicyTypeDef,
     ListFirewallPoliciesResponseTypeDef,
     ListFirewallsResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     LoggingConfigurationTypeDef,
     RuleGroupTypeDef,
     SourceMetadataTypeDef,
     SubnetMappingTypeDef,
     TagTypeDef,
+    TLSInspectionConfigurationTypeDef,
     UpdateFirewallDeleteProtectionResponseTypeDef,
     UpdateFirewallDescriptionResponseTypeDef,
     UpdateFirewallEncryptionConfigurationResponseTypeDef,
     UpdateFirewallPolicyChangeProtectionResponseTypeDef,
     UpdateFirewallPolicyResponseTypeDef,
     UpdateLoggingConfigurationResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     UpdateSubnetChangeProtectionResponseTypeDef,
+    UpdateTLSInspectionConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -205,14 +212,29 @@
         """
         Creates the specified stateless or stateful rule group, which includes the rules
         for network traffic inspection, a capacity setting, and tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_rule_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#create_rule_group)
         """
+    async def create_tls_inspection_configuration(
+        self,
+        *,
+        TLSInspectionConfigurationName: str,
+        TLSInspectionConfiguration: TLSInspectionConfigurationTypeDef,
+        Description: str = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        EncryptionConfiguration: EncryptionConfigurationTypeDef = ...
+    ) -> CreateTLSInspectionConfigurationResponseTypeDef:
+        """
+        Creates an Network Firewall TLS inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.create_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#create_tls_inspection_configuration)
+        """
     async def delete_firewall(
         self, *, FirewallName: str = ..., FirewallArn: str = ...
     ) -> DeleteFirewallResponseTypeDef:
         """
         Deletes the specified  Firewall and its  FirewallStatus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_firewall)
@@ -239,14 +261,23 @@
     ) -> DeleteRuleGroupResponseTypeDef:
         """
         Deletes the specified  RuleGroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_rule_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#delete_rule_group)
         """
+    async def delete_tls_inspection_configuration(
+        self, *, TLSInspectionConfigurationArn: str = ..., TLSInspectionConfigurationName: str = ...
+    ) -> DeleteTLSInspectionConfigurationResponseTypeDef:
+        """
+        Deletes the specified  TLSInspectionConfiguration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.delete_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#delete_tls_inspection_configuration)
+        """
     async def describe_firewall(
         self, *, FirewallName: str = ..., FirewallArn: str = ...
     ) -> DescribeFirewallResponseTypeDef:
         """
         Returns the data objects for the specified firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_firewall)
@@ -294,14 +325,23 @@
         """
         High-level information about a rule group, returned by operations like create
         and describe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_rule_group_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#describe_rule_group_metadata)
         """
+    async def describe_tls_inspection_configuration(
+        self, *, TLSInspectionConfigurationArn: str = ..., TLSInspectionConfigurationName: str = ...
+    ) -> DescribeTLSInspectionConfigurationResponseTypeDef:
+        """
+        Returns the data objects for the specified TLS inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.describe_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#describe_tls_inspection_configuration)
+        """
     async def disassociate_subnets(
         self,
         *,
         SubnetIds: Sequence[str],
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
@@ -363,14 +403,24 @@
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Retrieves the tags associated with the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#list_tags_for_resource)
         """
+    async def list_tls_inspection_configurations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListTLSInspectionConfigurationsResponseTypeDef:
+        """
+        Retrieves the metadata for the TLS inspection configurations that you have
+        defined.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.list_tls_inspection_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#list_tls_inspection_configurations)
+        """
     async def put_resource_policy(self, *, ResourceArn: str, Policy: str) -> Dict[str, Any]:
         """
         Creates or updates an IAM policy for your rule group or firewall policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.put_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#put_resource_policy)
         """
@@ -393,16 +443,16 @@
         *,
         DeleteProtection: bool,
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
     ) -> UpdateFirewallDeleteProtectionResponseTypeDef:
         """
-        Modifies the flag, `DeleteProtection` , which indicates whether it is possible
-        to delete the firewall.
+        Modifies the flag, `DeleteProtection`, which indicates whether it is possible to
+        delete the firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_delete_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_firewall_delete_protection)
         """
     async def update_firewall_description(
         self,
         *,
@@ -453,16 +503,16 @@
         *,
         FirewallPolicyChangeProtection: bool,
         UpdateToken: str = ...,
         FirewallArn: str = ...,
         FirewallName: str = ...
     ) -> UpdateFirewallPolicyChangeProtectionResponseTypeDef:
         """
-        Modifies the flag, `ChangeProtection` , which indicates whether it is possible
-        to change the firewall.
+        Modifies the flag, `ChangeProtection`, which indicates whether it is possible to
+        change the firewall.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_firewall_policy_change_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_firewall_policy_change_protection)
         """
     async def update_logging_configuration(
         self,
         *,
@@ -508,14 +558,31 @@
         See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/network-
         firewall-2020-11-12/UpdateSubnetChangeProtection).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_subnet_change_protection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_subnet_change_protection)
         """
+    async def update_tls_inspection_configuration(
+        self,
+        *,
+        TLSInspectionConfiguration: TLSInspectionConfigurationTypeDef,
+        UpdateToken: str,
+        TLSInspectionConfigurationArn: str = ...,
+        TLSInspectionConfigurationName: str = ...,
+        Description: str = ...,
+        EncryptionConfiguration: EncryptionConfigurationTypeDef = ...
+    ) -> UpdateTLSInspectionConfigurationResponseTypeDef:
+        """
+        Updates the TLS inspection configuration settings for the specified TLS
+        inspection configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.update_tls_inspection_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#update_tls_inspection_configuration)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_firewall_policies"]
     ) -> ListFirewallPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
@@ -530,14 +597,22 @@
     def get_paginator(self, operation_name: Literal["list_rule_groups"]) -> ListRuleGroupsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_tls_inspection_configurations"]
+    ) -> ListTLSInspectionConfigurationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_tags_for_resource"]
     ) -> ListTagsForResourcePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/client/#get_paginator)
         """
     async def __aenter__(self) -> "NetworkFirewallClient":
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/literals.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,25 +14,25 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AttachmentStatusType",
     "ConfigurationSyncStateType",
     "EncryptionTypeType",
     "FirewallStatusValueType",
     "GeneratedRulesTypeType",
     "IPAddressTypeType",
     "ListFirewallPoliciesPaginatorName",
     "ListFirewallsPaginatorName",
     "ListRuleGroupsPaginatorName",
+    "ListTLSInspectionConfigurationsPaginatorName",
     "ListTagsForResourcePaginatorName",
     "LogDestinationTypeType",
     "LogTypeType",
     "OverrideActionType",
     "PerObjectSyncStatusType",
     "ResourceManagedStatusType",
     "ResourceManagedTypeType",
@@ -48,24 +48,24 @@
     "NetworkFirewallServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
-AttachmentStatusType = Literal["CREATING", "DELETING", "READY", "SCALING"]
+AttachmentStatusType = Literal["CREATING", "DELETING", "ERROR", "FAILED", "READY", "SCALING"]
 ConfigurationSyncStateType = Literal["CAPACITY_CONSTRAINED", "IN_SYNC", "PENDING"]
 EncryptionTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_KMS"]
 FirewallStatusValueType = Literal["DELETING", "PROVISIONING", "READY"]
 GeneratedRulesTypeType = Literal["ALLOWLIST", "DENYLIST"]
-IPAddressTypeType = Literal["DUALSTACK", "IPV4"]
+IPAddressTypeType = Literal["DUALSTACK", "IPV4", "IPV6"]
 ListFirewallPoliciesPaginatorName = Literal["list_firewall_policies"]
 ListFirewallsPaginatorName = Literal["list_firewalls"]
 ListRuleGroupsPaginatorName = Literal["list_rule_groups"]
+ListTLSInspectionConfigurationsPaginatorName = Literal["list_tls_inspection_configurations"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 LogDestinationTypeType = Literal["CloudWatchLogs", "KinesisDataFirehose", "S3"]
 LogTypeType = Literal["ALERT", "FLOW"]
 OverrideActionType = Literal["DROP_TO_ALERT"]
 PerObjectSyncStatusType = Literal["CAPACITY_CONSTRAINED", "IN_SYNC", "PENDING"]
 ResourceManagedStatusType = Literal["ACCOUNT", "MANAGED"]
 ResourceManagedTypeType = Literal["AWS_MANAGED_DOMAIN_LISTS", "AWS_MANAGED_THREAT_SIGNATURES"]
@@ -91,15 +91,15 @@
     "SMTP",
     "SSH",
     "TCP",
     "TFTP",
     "TLS",
     "UDP",
 ]
-StreamExceptionPolicyType = Literal["CONTINUE", "DROP"]
+StreamExceptionPolicyType = Literal["CONTINUE", "DROP", "REJECT"]
 TCPFlagType = Literal["ACK", "CWR", "ECE", "FIN", "PSH", "RST", "SYN", "URG"]
 TargetTypeType = Literal["HTTP_HOST", "TLS_SNI"]
 NetworkFirewallServiceName = Literal["network-firewall"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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
@@ -450,15 +459,19 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
-    "list_firewall_policies", "list_firewalls", "list_rule_groups", "list_tags_for_resource"
+    "list_firewall_policies",
+    "list_firewalls",
+    "list_rule_groups",
+    "list_tags_for_resource",
+    "list_tls_inspection_configurations",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
@@ -469,14 +482,15 @@
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-south-1",
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/literals.pyi` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,24 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AttachmentStatusType",
     "ConfigurationSyncStateType",
     "EncryptionTypeType",
     "FirewallStatusValueType",
     "GeneratedRulesTypeType",
     "IPAddressTypeType",
     "ListFirewallPoliciesPaginatorName",
     "ListFirewallsPaginatorName",
     "ListRuleGroupsPaginatorName",
+    "ListTLSInspectionConfigurationsPaginatorName",
     "ListTagsForResourcePaginatorName",
     "LogDestinationTypeType",
     "LogTypeType",
     "OverrideActionType",
     "PerObjectSyncStatusType",
     "ResourceManagedStatusType",
     "ResourceManagedTypeType",
@@ -47,23 +49,25 @@
     "NetworkFirewallServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-AttachmentStatusType = Literal["CREATING", "DELETING", "READY", "SCALING"]
+
+AttachmentStatusType = Literal["CREATING", "DELETING", "ERROR", "FAILED", "READY", "SCALING"]
 ConfigurationSyncStateType = Literal["CAPACITY_CONSTRAINED", "IN_SYNC", "PENDING"]
 EncryptionTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_KMS"]
 FirewallStatusValueType = Literal["DELETING", "PROVISIONING", "READY"]
 GeneratedRulesTypeType = Literal["ALLOWLIST", "DENYLIST"]
-IPAddressTypeType = Literal["DUALSTACK", "IPV4"]
+IPAddressTypeType = Literal["DUALSTACK", "IPV4", "IPV6"]
 ListFirewallPoliciesPaginatorName = Literal["list_firewall_policies"]
 ListFirewallsPaginatorName = Literal["list_firewalls"]
 ListRuleGroupsPaginatorName = Literal["list_rule_groups"]
+ListTLSInspectionConfigurationsPaginatorName = Literal["list_tls_inspection_configurations"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 LogDestinationTypeType = Literal["CloudWatchLogs", "KinesisDataFirehose", "S3"]
 LogTypeType = Literal["ALERT", "FLOW"]
 OverrideActionType = Literal["DROP_TO_ALERT"]
 PerObjectSyncStatusType = Literal["CAPACITY_CONSTRAINED", "IN_SYNC", "PENDING"]
 ResourceManagedStatusType = Literal["ACCOUNT", "MANAGED"]
 ResourceManagedTypeType = Literal["AWS_MANAGED_DOMAIN_LISTS", "AWS_MANAGED_THREAT_SIGNATURES"]
@@ -89,15 +93,15 @@
     "SMTP",
     "SSH",
     "TCP",
     "TFTP",
     "TLS",
     "UDP",
 ]
-StreamExceptionPolicyType = Literal["CONTINUE", "DROP"]
+StreamExceptionPolicyType = Literal["CONTINUE", "DROP", "REJECT"]
 TCPFlagType = Literal["ACK", "CWR", "ECE", "FIN", "PSH", "RST", "SYN", "URG"]
 TargetTypeType = Literal["HTTP_HOST", "TLS_SNI"]
 NetworkFirewallServiceName = Literal["network-firewall"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -155,14 +159,15 @@
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
@@ -241,14 +246,15 @@
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
@@ -259,14 +265,15 @@
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
@@ -302,14 +309,15 @@
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
@@ -328,16 +336,19 @@
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
@@ -421,15 +432,17 @@
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
@@ -448,15 +461,19 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
-    "list_firewall_policies", "list_firewalls", "list_rule_groups", "list_tags_for_resource"
+    "list_firewall_policies",
+    "list_firewalls",
+    "list_rule_groups",
+    "list_tags_for_resource",
+    "list_tls_inspection_configurations",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
@@ -467,14 +484,15 @@
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-south-1",
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/paginator.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/paginator.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -9,122 +9,127 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_network_firewall.client import NetworkFirewallClient
     from types_aiobotocore_network_firewall.paginator import (
         ListFirewallPoliciesPaginator,
         ListFirewallsPaginator,
         ListRuleGroupsPaginator,
+        ListTLSInspectionConfigurationsPaginator,
         ListTagsForResourcePaginator,
     )
 
     session = get_session()
     with session.create_client("network-firewall") as client:
         client: NetworkFirewallClient
 
         list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator("list_firewall_policies")
         list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
         list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+        list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = client.get_paginator("list_tls_inspection_configurations")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceManagedStatusType, ResourceManagedTypeType, RuleGroupTypeType
 from .type_defs import (
     ListFirewallPoliciesResponseTypeDef,
     ListFirewallsResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListFirewallPoliciesPaginator",
     "ListFirewallsPaginator",
     "ListRuleGroupsPaginator",
+    "ListTLSInspectionConfigurationsPaginator",
     "ListTagsForResourcePaginator",
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
 class ListFirewallPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewallPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewallPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallpoliciespaginator)
         """
 
-
 class ListFirewallsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewalls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallspaginator)
     """
 
     def paginate(
-        self, *, VpcIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, VpcIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewalls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallspaginator)
         """
 
-
 class ListRuleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListRuleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listrulegroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Scope: ResourceManagedStatusType = ...,
         ManagedType: ResourceManagedTypeType = ...,
         Type: RuleGroupTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRuleGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListRuleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listrulegroupspaginator)
         """
 
+class ListTLSInspectionConfigurationsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTLSInspectionConfigurations)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtlsinspectionconfigurationspaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListTLSInspectionConfigurationsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTLSInspectionConfigurations.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtlsinspectionconfigurationspaginator)
+        """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/paginator.pyi` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/paginator.py`

 * *Files 10% similar despite different names*

```diff
@@ -9,115 +9,134 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_network_firewall.client import NetworkFirewallClient
     from types_aiobotocore_network_firewall.paginator import (
         ListFirewallPoliciesPaginator,
         ListFirewallsPaginator,
         ListRuleGroupsPaginator,
+        ListTLSInspectionConfigurationsPaginator,
         ListTagsForResourcePaginator,
     )
 
     session = get_session()
     with session.create_client("network-firewall") as client:
         client: NetworkFirewallClient
 
         list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator("list_firewall_policies")
         list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
         list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+        list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = client.get_paginator("list_tls_inspection_configurations")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceManagedStatusType, ResourceManagedTypeType, RuleGroupTypeType
 from .type_defs import (
     ListFirewallPoliciesResponseTypeDef,
     ListFirewallsResponseTypeDef,
     ListRuleGroupsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListFirewallPoliciesPaginator",
     "ListFirewallsPaginator",
     "ListRuleGroupsPaginator",
+    "ListTLSInspectionConfigurationsPaginator",
     "ListTagsForResourcePaginator",
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
 class ListFirewallPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewallPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewallPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallpoliciespaginator)
         """
 
+
 class ListFirewallsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewalls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallspaginator)
     """
 
     def paginate(
-        self, *, VpcIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, VpcIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFirewallsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListFirewalls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listfirewallspaginator)
         """
 
+
 class ListRuleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListRuleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listrulegroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Scope: ResourceManagedStatusType = ...,
         ManagedType: ResourceManagedTypeType = ...,
         Type: RuleGroupTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRuleGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListRuleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listrulegroupspaginator)
         """
 
+
+class ListTLSInspectionConfigurationsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTLSInspectionConfigurations)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtlsinspectionconfigurationspaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListTLSInspectionConfigurationsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTLSInspectionConfigurations.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtlsinspectionconfigurationspaginator)
+        """
+
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/type_defs.py` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/type_defs.py`

 * *Files 12% similar despite different names*

```diff
@@ -47,66 +47,77 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddressTypeDef",
     "AssociateFirewallPolicyRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateFirewallPolicyResponseTypeDef",
     "SubnetMappingTypeDef",
     "AttachmentTypeDef",
     "IPSetMetadataTypeDef",
     "EncryptionConfigurationTypeDef",
     "TagTypeDef",
     "SourceMetadataTypeDef",
     "DeleteFirewallPolicyRequestRequestTypeDef",
     "DeleteFirewallRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteRuleGroupRequestRequestTypeDef",
+    "DeleteTLSInspectionConfigurationRequestRequestTypeDef",
     "DescribeFirewallPolicyRequestRequestTypeDef",
     "DescribeFirewallRequestRequestTypeDef",
     "DescribeLoggingConfigurationRequestRequestTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeRuleGroupMetadataRequestRequestTypeDef",
     "StatefulRuleOptionsTypeDef",
     "DescribeRuleGroupRequestRequestTypeDef",
+    "DescribeTLSInspectionConfigurationRequestRequestTypeDef",
     "DimensionTypeDef",
     "DisassociateSubnetsRequestRequestTypeDef",
     "FirewallMetadataTypeDef",
     "FirewallPolicyMetadataTypeDef",
     "StatefulEngineOptionsTypeDef",
     "StatelessRuleGroupReferenceTypeDef",
     "HeaderTypeDef",
     "IPSetReferenceTypeDef",
     "IPSetTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
     "ListFirewallPoliciesRequestRequestTypeDef",
+    "ListFirewallsRequestListFirewallsPaginateTypeDef",
     "ListFirewallsRequestRequestTypeDef",
+    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
     "ListRuleGroupsRequestRequestTypeDef",
     "RuleGroupMetadataTypeDef",
+    "ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef",
+    "ListTLSInspectionConfigurationsRequestRequestTypeDef",
+    "TLSInspectionConfigurationMetadataTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "LogDestinationConfigTypeDef",
     "PortRangeTypeDef",
     "TCPFlagFieldTypeDef",
+    "PaginatorConfigTypeDef",
     "PerObjectStatusTypeDef",
     "PortSetTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RuleOptionTypeDef",
     "RulesSourceListTypeDef",
+    "ServerCertificateTypeDef",
     "StatefulRuleGroupOverrideTypeDef",
+    "TlsCertificateDataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFirewallDeleteProtectionRequestRequestTypeDef",
-    "UpdateFirewallDescriptionRequestRequestTypeDef",
-    "UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
-    "UpdateSubnetChangeProtectionRequestRequestTypeDef",
-    "AssociateFirewallPolicyResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
     "UpdateFirewallDeleteProtectionResponseTypeDef",
+    "UpdateFirewallDescriptionRequestRequestTypeDef",
     "UpdateFirewallDescriptionResponseTypeDef",
+    "UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
     "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
+    "UpdateSubnetChangeProtectionRequestRequestTypeDef",
     "UpdateSubnetChangeProtectionResponseTypeDef",
     "AssociateSubnetsRequestRequestTypeDef",
     "AssociateSubnetsResponseTypeDef",
     "DisassociateSubnetsResponseTypeDef",
     "CIDRSummaryTypeDef",
     "UpdateFirewallEncryptionConfigurationRequestRequestTypeDef",
     "UpdateFirewallEncryptionConfigurationResponseTypeDef",
@@ -117,44 +128,52 @@
     "TagResourceRequestRequestTypeDef",
     "RuleGroupResponseTypeDef",
     "DescribeRuleGroupMetadataResponseTypeDef",
     "PublishMetricActionTypeDef",
     "ListFirewallsResponseTypeDef",
     "ListFirewallPoliciesResponseTypeDef",
     "ReferenceSetsTypeDef",
-    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
-    "ListFirewallsRequestListFirewallsPaginateTypeDef",
-    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "PolicyVariablesTypeDef",
     "ListRuleGroupsResponseTypeDef",
+    "ListTLSInspectionConfigurationsResponseTypeDef",
     "LoggingConfigurationTypeDef",
+    "ServerCertificateScopeTypeDef",
     "MatchAttributesTypeDef",
     "SyncStateTypeDef",
     "RuleVariablesTypeDef",
     "StatefulRuleTypeDef",
     "StatefulRuleGroupReferenceTypeDef",
+    "TLSInspectionConfigurationResponseTypeDef",
     "CapacityUsageSummaryTypeDef",
     "CreateFirewallPolicyResponseTypeDef",
     "DeleteFirewallPolicyResponseTypeDef",
     "UpdateFirewallPolicyResponseTypeDef",
     "CreateRuleGroupResponseTypeDef",
     "DeleteRuleGroupResponseTypeDef",
     "UpdateRuleGroupResponseTypeDef",
     "ActionDefinitionTypeDef",
     "DescribeLoggingConfigurationResponseTypeDef",
     "UpdateLoggingConfigurationRequestRequestTypeDef",
     "UpdateLoggingConfigurationResponseTypeDef",
+    "ServerCertificateConfigurationTypeDef",
     "RuleDefinitionTypeDef",
+    "CreateTLSInspectionConfigurationResponseTypeDef",
+    "DeleteTLSInspectionConfigurationResponseTypeDef",
+    "UpdateTLSInspectionConfigurationResponseTypeDef",
     "FirewallStatusTypeDef",
     "CustomActionTypeDef",
+    "TLSInspectionConfigurationTypeDef",
     "StatelessRuleTypeDef",
     "CreateFirewallResponseTypeDef",
     "DeleteFirewallResponseTypeDef",
     "DescribeFirewallResponseTypeDef",
     "FirewallPolicyTypeDef",
+    "CreateTLSInspectionConfigurationRequestRequestTypeDef",
+    "DescribeTLSInspectionConfigurationResponseTypeDef",
+    "UpdateTLSInspectionConfigurationRequestRequestTypeDef",
     "StatelessRulesAndCustomActionsTypeDef",
     "CreateFirewallPolicyRequestRequestTypeDef",
     "DescribeFirewallPolicyResponseTypeDef",
     "UpdateFirewallPolicyRequestRequestTypeDef",
     "RulesSourceTypeDef",
     "RuleGroupTypeDef",
     "CreateRuleGroupRequestRequestTypeDef",
@@ -189,22 +208,22 @@
 class AssociateFirewallPolicyRequestRequestTypeDef(
     _RequiredAssociateFirewallPolicyRequestRequestTypeDef,
     _OptionalAssociateFirewallPolicyRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateFirewallPolicyResponseTypeDef = TypedDict(
+    "AssociateFirewallPolicyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "FirewallArn": str,
+        "FirewallName": str,
+        "FirewallPolicyArn": str,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubnetMappingTypeDef = TypedDict(
     "_RequiredSubnetMappingTypeDef",
     {
         "SubnetId": str,
@@ -311,14 +330,23 @@
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
     total=False,
 )
 
+DeleteTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "DeleteTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+    },
+    total=False,
+)
+
 DescribeFirewallPolicyRequestRequestTypeDef = TypedDict(
     "DescribeFirewallPolicyRequestRequestTypeDef",
     {
         "FirewallPolicyName": str,
         "FirewallPolicyArn": str,
     },
     total=False,
@@ -345,14 +373,22 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRuleGroupMetadataRequestRequestTypeDef = TypedDict(
     "DescribeRuleGroupMetadataRequestRequestTypeDef",
     {
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
@@ -373,14 +409,23 @@
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
     total=False,
 )
 
+DescribeTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "DescribeTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+    },
+    total=False,
+)
+
 DimensionTypeDef = TypedDict(
     "DimensionTypeDef",
     {
         "Value": str,
     },
 )
 
@@ -466,43 +511,61 @@
 IPSetTypeDef = TypedDict(
     "IPSetTypeDef",
     {
         "Definition": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef = TypedDict(
+    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFirewallPoliciesRequestRequestTypeDef = TypedDict(
     "ListFirewallPoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListFirewallsRequestListFirewallsPaginateTypeDef = TypedDict(
+    "ListFirewallsRequestListFirewallsPaginateTypeDef",
+    {
+        "VpcIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallsRequestRequestTypeDef = TypedDict(
     "ListFirewallsRequestRequestTypeDef",
     {
         "NextToken": str,
         "VpcIds": Sequence[str],
         "MaxResults": int,
     },
     total=False,
 )
 
+ListRuleGroupsRequestListRuleGroupsPaginateTypeDef = TypedDict(
+    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
+    {
+        "Scope": ResourceManagedStatusType,
+        "ManagedType": ResourceManagedTypeType,
+        "Type": RuleGroupTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRuleGroupsRequestRequestTypeDef = TypedDict(
     "ListRuleGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Scope": ResourceManagedStatusType,
         "ManagedType": ResourceManagedTypeType,
@@ -516,14 +579,62 @@
     {
         "Name": str,
         "Arn": str,
     },
     total=False,
 )
 
+ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListTLSInspectionConfigurationsRequestRequestTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+TLSInspectionConfigurationMetadataTypeDef = TypedDict(
+    "TLSInspectionConfigurationMetadataTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+    },
+    total=False,
+)
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
@@ -575,14 +686,24 @@
 )
 
 
 class TCPFlagFieldTypeDef(_RequiredTCPFlagFieldTypeDef, _OptionalTCPFlagFieldTypeDef):
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
 PerObjectStatusTypeDef = TypedDict(
     "PerObjectStatusTypeDef",
     {
         "SyncStatus": PerObjectSyncStatusType,
         "UpdateToken": str,
     },
     total=False,
@@ -600,14 +721,25 @@
     "PutResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
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
 _RequiredRuleOptionTypeDef = TypedDict(
     "_RequiredRuleOptionTypeDef",
     {
         "Keyword": str,
     },
 )
 _OptionalRuleOptionTypeDef = TypedDict(
@@ -628,22 +760,41 @@
     {
         "Targets": Sequence[str],
         "TargetTypes": Sequence[TargetTypeType],
         "GeneratedRulesType": GeneratedRulesTypeType,
     },
 )
 
+ServerCertificateTypeDef = TypedDict(
+    "ServerCertificateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+    total=False,
+)
+
 StatefulRuleGroupOverrideTypeDef = TypedDict(
     "StatefulRuleGroupOverrideTypeDef",
     {
         "Action": Literal["DROP_TO_ALERT"],
     },
     total=False,
 )
 
+TlsCertificateDataTypeDef = TypedDict(
+    "TlsCertificateDataTypeDef",
+    {
+        "CertificateArn": str,
+        "CertificateSerial": str,
+        "Status": str,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -668,25 +819,47 @@
 class UpdateFirewallDeleteProtectionRequestRequestTypeDef(
     _RequiredUpdateFirewallDeleteProtectionRequestRequestTypeDef,
     _OptionalUpdateFirewallDeleteProtectionRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateFirewallDeleteProtectionResponseTypeDef = TypedDict(
+    "UpdateFirewallDeleteProtectionResponseTypeDef",
+    {
+        "FirewallArn": str,
+        "FirewallName": str,
+        "DeleteProtection": bool,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateFirewallDescriptionRequestRequestTypeDef = TypedDict(
     "UpdateFirewallDescriptionRequestRequestTypeDef",
     {
         "UpdateToken": str,
         "FirewallArn": str,
         "FirewallName": str,
         "Description": str,
     },
     total=False,
 )
 
+UpdateFirewallDescriptionResponseTypeDef = TypedDict(
+    "UpdateFirewallDescriptionResponseTypeDef",
+    {
+        "FirewallArn": str,
+        "FirewallName": str,
+        "Description": str,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
     {
         "FirewallPolicyChangeProtection": bool,
     },
 )
 _OptionalUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef = TypedDict(
@@ -703,14 +876,25 @@
 class UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef(
     _RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
     _OptionalUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateFirewallPolicyChangeProtectionResponseTypeDef = TypedDict(
+    "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "FirewallArn": str,
+        "FirewallName": str,
+        "FirewallPolicyChangeProtection": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef",
     {
         "SubnetChangeProtection": bool,
     },
 )
 _OptionalUpdateSubnetChangeProtectionRequestRequestTypeDef = TypedDict(
@@ -727,74 +911,22 @@
 class UpdateSubnetChangeProtectionRequestRequestTypeDef(
     _RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef,
     _OptionalUpdateSubnetChangeProtectionRequestRequestTypeDef,
 ):
     pass
 
 
-AssociateFirewallPolicyResponseTypeDef = TypedDict(
-    "AssociateFirewallPolicyResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "FirewallPolicyArn": str,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDeleteProtectionResponseTypeDef = TypedDict(
-    "UpdateFirewallDeleteProtectionResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "DeleteProtection": bool,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDescriptionResponseTypeDef = TypedDict(
-    "UpdateFirewallDescriptionResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "Description": str,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallPolicyChangeProtectionResponseTypeDef = TypedDict(
-    "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
-    {
-        "UpdateToken": str,
-        "FirewallArn": str,
-        "FirewallName": str,
-        "FirewallPolicyChangeProtection": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSubnetChangeProtectionResponseTypeDef = TypedDict(
     "UpdateSubnetChangeProtectionResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetChangeProtection": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateSubnetsRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateSubnetsRequestRequestTypeDef",
     {
         "SubnetMappings": Sequence[SubnetMappingTypeDef],
@@ -820,26 +952,26 @@
 AssociateSubnetsResponseTypeDef = TypedDict(
     "AssociateSubnetsResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetMappings": List[SubnetMappingTypeDef],
         "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateSubnetsResponseTypeDef = TypedDict(
     "DisassociateSubnetsResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetMappings": List[SubnetMappingTypeDef],
         "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CIDRSummaryTypeDef = TypedDict(
     "CIDRSummaryTypeDef",
     {
         "AvailableCIDRCount": int,
@@ -863,15 +995,15 @@
 UpdateFirewallEncryptionConfigurationResponseTypeDef = TypedDict(
     "UpdateFirewallEncryptionConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "UpdateToken": str,
         "EncryptionConfiguration": EncryptionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFirewallRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallRequestRequestTypeDef",
     {
         "FirewallName": str,
@@ -960,15 +1092,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "NextToken": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1015,15 +1147,15 @@
         "RuleGroupArn": str,
         "RuleGroupName": str,
         "Description": str,
         "Type": RuleGroupTypeType,
         "Capacity": int,
         "StatefulRuleOptions": StatefulRuleOptionsTypeDef,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublishMetricActionTypeDef = TypedDict(
     "PublishMetricActionTypeDef",
     {
         "Dimensions": Sequence[DimensionTypeDef],
@@ -1031,101 +1163,80 @@
 )
 
 ListFirewallsResponseTypeDef = TypedDict(
     "ListFirewallsResponseTypeDef",
     {
         "NextToken": str,
         "Firewalls": List[FirewallMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallPoliciesResponseTypeDef = TypedDict(
     "ListFirewallPoliciesResponseTypeDef",
     {
         "NextToken": str,
         "FirewallPolicies": List[FirewallPolicyMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReferenceSetsTypeDef = TypedDict(
     "ReferenceSetsTypeDef",
     {
         "IPSetReferences": Mapping[str, IPSetReferenceTypeDef],
     },
     total=False,
 )
 
-ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef = TypedDict(
-    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFirewallsRequestListFirewallsPaginateTypeDef = TypedDict(
-    "ListFirewallsRequestListFirewallsPaginateTypeDef",
+PolicyVariablesTypeDef = TypedDict(
+    "PolicyVariablesTypeDef",
     {
-        "VpcIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RuleVariables": Mapping[str, IPSetTypeDef],
     },
     total=False,
 )
 
-ListRuleGroupsRequestListRuleGroupsPaginateTypeDef = TypedDict(
-    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
-    {
-        "Scope": ResourceManagedStatusType,
-        "ManagedType": ResourceManagedTypeType,
-        "Type": RuleGroupTypeType,
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
+ListRuleGroupsResponseTypeDef = TypedDict(
+    "ListRuleGroupsResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "RuleGroups": List[RuleGroupMetadataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-ListRuleGroupsResponseTypeDef = TypedDict(
-    "ListRuleGroupsResponseTypeDef",
+ListTLSInspectionConfigurationsResponseTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsResponseTypeDef",
     {
         "NextToken": str,
-        "RuleGroups": List[RuleGroupMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TLSInspectionConfigurations": List[TLSInspectionConfigurationMetadataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationTypeDef = TypedDict(
     "LoggingConfigurationTypeDef",
     {
         "LogDestinationConfigs": List[LogDestinationConfigTypeDef],
     },
 )
 
+ServerCertificateScopeTypeDef = TypedDict(
+    "ServerCertificateScopeTypeDef",
+    {
+        "Sources": Sequence[AddressTypeDef],
+        "Destinations": Sequence[AddressTypeDef],
+        "SourcePorts": Sequence[PortRangeTypeDef],
+        "DestinationPorts": Sequence[PortRangeTypeDef],
+        "Protocols": Sequence[int],
+    },
+    total=False,
+)
+
 MatchAttributesTypeDef = TypedDict(
     "MatchAttributesTypeDef",
     {
         "Sources": Sequence[AddressTypeDef],
         "Destinations": Sequence[AddressTypeDef],
         "SourcePorts": Sequence[PortRangeTypeDef],
         "DestinationPorts": Sequence[PortRangeTypeDef],
@@ -1180,71 +1291,101 @@
 
 class StatefulRuleGroupReferenceTypeDef(
     _RequiredStatefulRuleGroupReferenceTypeDef, _OptionalStatefulRuleGroupReferenceTypeDef
 ):
     pass
 
 
+_RequiredTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "_RequiredTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+        "TLSInspectionConfigurationId": str,
+    },
+)
+_OptionalTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "_OptionalTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationStatus": ResourceStatusType,
+        "Description": str,
+        "Tags": List[TagTypeDef],
+        "LastModifiedTime": datetime,
+        "NumberOfAssociations": int,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+        "Certificates": List[TlsCertificateDataTypeDef],
+    },
+    total=False,
+)
+
+
+class TLSInspectionConfigurationResponseTypeDef(
+    _RequiredTLSInspectionConfigurationResponseTypeDef,
+    _OptionalTLSInspectionConfigurationResponseTypeDef,
+):
+    pass
+
+
 CapacityUsageSummaryTypeDef = TypedDict(
     "CapacityUsageSummaryTypeDef",
     {
         "CIDRs": CIDRSummaryTypeDef,
     },
     total=False,
 )
 
 CreateFirewallPolicyResponseTypeDef = TypedDict(
     "CreateFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallPolicyResponseTypeDef = TypedDict(
     "DeleteFirewallPolicyResponseTypeDef",
     {
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallPolicyResponseTypeDef = TypedDict(
     "UpdateFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleGroupResponseTypeDef = TypedDict(
     "CreateRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRuleGroupResponseTypeDef = TypedDict(
     "DeleteRuleGroupResponseTypeDef",
     {
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRuleGroupResponseTypeDef = TypedDict(
     "UpdateRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionDefinitionTypeDef = TypedDict(
     "ActionDefinitionTypeDef",
     {
         "PublishMetricAction": PublishMetricActionTypeDef,
@@ -1253,15 +1394,15 @@
 )
 
 DescribeLoggingConfigurationResponseTypeDef = TypedDict(
     "DescribeLoggingConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateLoggingConfigurationRequestRequestTypeDef",
     {
         "FirewallArn": str,
@@ -1273,26 +1414,61 @@
 
 UpdateLoggingConfigurationResponseTypeDef = TypedDict(
     "UpdateLoggingConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ServerCertificateConfigurationTypeDef = TypedDict(
+    "ServerCertificateConfigurationTypeDef",
+    {
+        "ServerCertificates": Sequence[ServerCertificateTypeDef],
+        "Scopes": Sequence[ServerCertificateScopeTypeDef],
+    },
+    total=False,
+)
+
 RuleDefinitionTypeDef = TypedDict(
     "RuleDefinitionTypeDef",
     {
         "MatchAttributes": MatchAttributesTypeDef,
         "Actions": Sequence[str],
     },
 )
 
+CreateTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "CreateTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "DeleteTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "UpdateTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFirewallStatusTypeDef = TypedDict(
     "_RequiredFirewallStatusTypeDef",
     {
         "Status": FirewallStatusValueType,
         "ConfigurationSyncStateSummary": ConfigurationSyncStateType,
     },
 )
@@ -1314,47 +1490,55 @@
     "CustomActionTypeDef",
     {
         "ActionName": str,
         "ActionDefinition": ActionDefinitionTypeDef,
     },
 )
 
+TLSInspectionConfigurationTypeDef = TypedDict(
+    "TLSInspectionConfigurationTypeDef",
+    {
+        "ServerCertificateConfigurations": Sequence[ServerCertificateConfigurationTypeDef],
+    },
+    total=False,
+)
+
 StatelessRuleTypeDef = TypedDict(
     "StatelessRuleTypeDef",
     {
         "RuleDefinition": RuleDefinitionTypeDef,
         "Priority": int,
     },
 )
 
 CreateFirewallResponseTypeDef = TypedDict(
     "CreateFirewallResponseTypeDef",
     {
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallResponseTypeDef = TypedDict(
     "DeleteFirewallResponseTypeDef",
     {
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFirewallResponseTypeDef = TypedDict(
     "DescribeFirewallResponseTypeDef",
     {
         "UpdateToken": str,
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFirewallPolicyTypeDef = TypedDict(
     "_RequiredFirewallPolicyTypeDef",
     {
         "StatelessDefaultActions": Sequence[str],
@@ -1365,23 +1549,86 @@
     "_OptionalFirewallPolicyTypeDef",
     {
         "StatelessRuleGroupReferences": Sequence[StatelessRuleGroupReferenceTypeDef],
         "StatelessCustomActions": Sequence[CustomActionTypeDef],
         "StatefulRuleGroupReferences": Sequence[StatefulRuleGroupReferenceTypeDef],
         "StatefulDefaultActions": Sequence[str],
         "StatefulEngineOptions": StatefulEngineOptionsTypeDef,
+        "TLSInspectionConfigurationArn": str,
+        "PolicyVariables": PolicyVariablesTypeDef,
     },
     total=False,
 )
 
 
 class FirewallPolicyTypeDef(_RequiredFirewallPolicyTypeDef, _OptionalFirewallPolicyTypeDef):
     pass
 
 
+_RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationName": str,
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+    },
+)
+_OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "Description": str,
+        "Tags": Sequence[TagTypeDef],
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateTLSInspectionConfigurationRequestRequestTypeDef(
+    _RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef,
+    _OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef,
+):
+    pass
+
+
+DescribeTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "DescribeTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+        "UpdateToken": str,
+    },
+)
+_OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+        "Description": str,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateTLSInspectionConfigurationRequestRequestTypeDef(
+    _RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef,
+    _OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredStatelessRulesAndCustomActionsTypeDef = TypedDict(
     "_RequiredStatelessRulesAndCustomActionsTypeDef",
     {
         "StatelessRules": Sequence[StatelessRuleTypeDef],
     },
 )
 _OptionalStatelessRulesAndCustomActionsTypeDef = TypedDict(
@@ -1427,15 +1674,15 @@
 
 DescribeFirewallPolicyResponseTypeDef = TypedDict(
     "DescribeFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
         "FirewallPolicy": FirewallPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFirewallPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallPolicyRequestRequestTypeDef",
     {
         "UpdateToken": str,
@@ -1525,15 +1772,15 @@
 
 DescribeRuleGroupResponseTypeDef = TypedDict(
     "DescribeRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroup": RuleGroupTypeDef,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRuleGroupRequestRequestTypeDef",
     {
         "UpdateToken": str,
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall/type_defs.pyi` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -46,66 +46,77 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddressTypeDef",
     "AssociateFirewallPolicyRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateFirewallPolicyResponseTypeDef",
     "SubnetMappingTypeDef",
     "AttachmentTypeDef",
     "IPSetMetadataTypeDef",
     "EncryptionConfigurationTypeDef",
     "TagTypeDef",
     "SourceMetadataTypeDef",
     "DeleteFirewallPolicyRequestRequestTypeDef",
     "DeleteFirewallRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteRuleGroupRequestRequestTypeDef",
+    "DeleteTLSInspectionConfigurationRequestRequestTypeDef",
     "DescribeFirewallPolicyRequestRequestTypeDef",
     "DescribeFirewallRequestRequestTypeDef",
     "DescribeLoggingConfigurationRequestRequestTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeRuleGroupMetadataRequestRequestTypeDef",
     "StatefulRuleOptionsTypeDef",
     "DescribeRuleGroupRequestRequestTypeDef",
+    "DescribeTLSInspectionConfigurationRequestRequestTypeDef",
     "DimensionTypeDef",
     "DisassociateSubnetsRequestRequestTypeDef",
     "FirewallMetadataTypeDef",
     "FirewallPolicyMetadataTypeDef",
     "StatefulEngineOptionsTypeDef",
     "StatelessRuleGroupReferenceTypeDef",
     "HeaderTypeDef",
     "IPSetReferenceTypeDef",
     "IPSetTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
     "ListFirewallPoliciesRequestRequestTypeDef",
+    "ListFirewallsRequestListFirewallsPaginateTypeDef",
     "ListFirewallsRequestRequestTypeDef",
+    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
     "ListRuleGroupsRequestRequestTypeDef",
     "RuleGroupMetadataTypeDef",
+    "ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef",
+    "ListTLSInspectionConfigurationsRequestRequestTypeDef",
+    "TLSInspectionConfigurationMetadataTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "LogDestinationConfigTypeDef",
     "PortRangeTypeDef",
     "TCPFlagFieldTypeDef",
+    "PaginatorConfigTypeDef",
     "PerObjectStatusTypeDef",
     "PortSetTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RuleOptionTypeDef",
     "RulesSourceListTypeDef",
+    "ServerCertificateTypeDef",
     "StatefulRuleGroupOverrideTypeDef",
+    "TlsCertificateDataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFirewallDeleteProtectionRequestRequestTypeDef",
-    "UpdateFirewallDescriptionRequestRequestTypeDef",
-    "UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
-    "UpdateSubnetChangeProtectionRequestRequestTypeDef",
-    "AssociateFirewallPolicyResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
     "UpdateFirewallDeleteProtectionResponseTypeDef",
+    "UpdateFirewallDescriptionRequestRequestTypeDef",
     "UpdateFirewallDescriptionResponseTypeDef",
+    "UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
     "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
+    "UpdateSubnetChangeProtectionRequestRequestTypeDef",
     "UpdateSubnetChangeProtectionResponseTypeDef",
     "AssociateSubnetsRequestRequestTypeDef",
     "AssociateSubnetsResponseTypeDef",
     "DisassociateSubnetsResponseTypeDef",
     "CIDRSummaryTypeDef",
     "UpdateFirewallEncryptionConfigurationRequestRequestTypeDef",
     "UpdateFirewallEncryptionConfigurationResponseTypeDef",
@@ -116,44 +127,52 @@
     "TagResourceRequestRequestTypeDef",
     "RuleGroupResponseTypeDef",
     "DescribeRuleGroupMetadataResponseTypeDef",
     "PublishMetricActionTypeDef",
     "ListFirewallsResponseTypeDef",
     "ListFirewallPoliciesResponseTypeDef",
     "ReferenceSetsTypeDef",
-    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
-    "ListFirewallsRequestListFirewallsPaginateTypeDef",
-    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "PolicyVariablesTypeDef",
     "ListRuleGroupsResponseTypeDef",
+    "ListTLSInspectionConfigurationsResponseTypeDef",
     "LoggingConfigurationTypeDef",
+    "ServerCertificateScopeTypeDef",
     "MatchAttributesTypeDef",
     "SyncStateTypeDef",
     "RuleVariablesTypeDef",
     "StatefulRuleTypeDef",
     "StatefulRuleGroupReferenceTypeDef",
+    "TLSInspectionConfigurationResponseTypeDef",
     "CapacityUsageSummaryTypeDef",
     "CreateFirewallPolicyResponseTypeDef",
     "DeleteFirewallPolicyResponseTypeDef",
     "UpdateFirewallPolicyResponseTypeDef",
     "CreateRuleGroupResponseTypeDef",
     "DeleteRuleGroupResponseTypeDef",
     "UpdateRuleGroupResponseTypeDef",
     "ActionDefinitionTypeDef",
     "DescribeLoggingConfigurationResponseTypeDef",
     "UpdateLoggingConfigurationRequestRequestTypeDef",
     "UpdateLoggingConfigurationResponseTypeDef",
+    "ServerCertificateConfigurationTypeDef",
     "RuleDefinitionTypeDef",
+    "CreateTLSInspectionConfigurationResponseTypeDef",
+    "DeleteTLSInspectionConfigurationResponseTypeDef",
+    "UpdateTLSInspectionConfigurationResponseTypeDef",
     "FirewallStatusTypeDef",
     "CustomActionTypeDef",
+    "TLSInspectionConfigurationTypeDef",
     "StatelessRuleTypeDef",
     "CreateFirewallResponseTypeDef",
     "DeleteFirewallResponseTypeDef",
     "DescribeFirewallResponseTypeDef",
     "FirewallPolicyTypeDef",
+    "CreateTLSInspectionConfigurationRequestRequestTypeDef",
+    "DescribeTLSInspectionConfigurationResponseTypeDef",
+    "UpdateTLSInspectionConfigurationRequestRequestTypeDef",
     "StatelessRulesAndCustomActionsTypeDef",
     "CreateFirewallPolicyRequestRequestTypeDef",
     "DescribeFirewallPolicyResponseTypeDef",
     "UpdateFirewallPolicyRequestRequestTypeDef",
     "RulesSourceTypeDef",
     "RuleGroupTypeDef",
     "CreateRuleGroupRequestRequestTypeDef",
@@ -186,22 +205,22 @@
 
 class AssociateFirewallPolicyRequestRequestTypeDef(
     _RequiredAssociateFirewallPolicyRequestRequestTypeDef,
     _OptionalAssociateFirewallPolicyRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateFirewallPolicyResponseTypeDef = TypedDict(
+    "AssociateFirewallPolicyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "FirewallArn": str,
+        "FirewallName": str,
+        "FirewallPolicyArn": str,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubnetMappingTypeDef = TypedDict(
     "_RequiredSubnetMappingTypeDef",
     {
         "SubnetId": str,
@@ -304,14 +323,23 @@
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
     total=False,
 )
 
+DeleteTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "DeleteTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+    },
+    total=False,
+)
+
 DescribeFirewallPolicyRequestRequestTypeDef = TypedDict(
     "DescribeFirewallPolicyRequestRequestTypeDef",
     {
         "FirewallPolicyName": str,
         "FirewallPolicyArn": str,
     },
     total=False,
@@ -338,14 +366,22 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRuleGroupMetadataRequestRequestTypeDef = TypedDict(
     "DescribeRuleGroupMetadataRequestRequestTypeDef",
     {
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
@@ -366,14 +402,23 @@
         "RuleGroupName": str,
         "RuleGroupArn": str,
         "Type": RuleGroupTypeType,
     },
     total=False,
 )
 
+DescribeTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "DescribeTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+    },
+    total=False,
+)
+
 DimensionTypeDef = TypedDict(
     "DimensionTypeDef",
     {
         "Value": str,
     },
 )
 
@@ -457,43 +502,61 @@
 IPSetTypeDef = TypedDict(
     "IPSetTypeDef",
     {
         "Definition": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef = TypedDict(
+    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFirewallPoliciesRequestRequestTypeDef = TypedDict(
     "ListFirewallPoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListFirewallsRequestListFirewallsPaginateTypeDef = TypedDict(
+    "ListFirewallsRequestListFirewallsPaginateTypeDef",
+    {
+        "VpcIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFirewallsRequestRequestTypeDef = TypedDict(
     "ListFirewallsRequestRequestTypeDef",
     {
         "NextToken": str,
         "VpcIds": Sequence[str],
         "MaxResults": int,
     },
     total=False,
 )
 
+ListRuleGroupsRequestListRuleGroupsPaginateTypeDef = TypedDict(
+    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
+    {
+        "Scope": ResourceManagedStatusType,
+        "ManagedType": ResourceManagedTypeType,
+        "Type": RuleGroupTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRuleGroupsRequestRequestTypeDef = TypedDict(
     "ListRuleGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Scope": ResourceManagedStatusType,
         "ManagedType": ResourceManagedTypeType,
@@ -507,14 +570,60 @@
     {
         "Name": str,
         "Arn": str,
     },
     total=False,
 )
 
+ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListTLSInspectionConfigurationsRequestRequestTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+TLSInspectionConfigurationMetadataTypeDef = TypedDict(
+    "TLSInspectionConfigurationMetadataTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+    },
+    total=False,
+)
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
@@ -562,14 +671,24 @@
     },
     total=False,
 )
 
 class TCPFlagFieldTypeDef(_RequiredTCPFlagFieldTypeDef, _OptionalTCPFlagFieldTypeDef):
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
 PerObjectStatusTypeDef = TypedDict(
     "PerObjectStatusTypeDef",
     {
         "SyncStatus": PerObjectSyncStatusType,
         "UpdateToken": str,
     },
     total=False,
@@ -587,14 +706,25 @@
     "PutResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
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
 _RequiredRuleOptionTypeDef = TypedDict(
     "_RequiredRuleOptionTypeDef",
     {
         "Keyword": str,
     },
 )
 _OptionalRuleOptionTypeDef = TypedDict(
@@ -613,22 +743,41 @@
     {
         "Targets": Sequence[str],
         "TargetTypes": Sequence[TargetTypeType],
         "GeneratedRulesType": GeneratedRulesTypeType,
     },
 )
 
+ServerCertificateTypeDef = TypedDict(
+    "ServerCertificateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+    total=False,
+)
+
 StatefulRuleGroupOverrideTypeDef = TypedDict(
     "StatefulRuleGroupOverrideTypeDef",
     {
         "Action": Literal["DROP_TO_ALERT"],
     },
     total=False,
 )
 
+TlsCertificateDataTypeDef = TypedDict(
+    "TlsCertificateDataTypeDef",
+    {
+        "CertificateArn": str,
+        "CertificateSerial": str,
+        "Status": str,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -651,25 +800,47 @@
 
 class UpdateFirewallDeleteProtectionRequestRequestTypeDef(
     _RequiredUpdateFirewallDeleteProtectionRequestRequestTypeDef,
     _OptionalUpdateFirewallDeleteProtectionRequestRequestTypeDef,
 ):
     pass
 
+UpdateFirewallDeleteProtectionResponseTypeDef = TypedDict(
+    "UpdateFirewallDeleteProtectionResponseTypeDef",
+    {
+        "FirewallArn": str,
+        "FirewallName": str,
+        "DeleteProtection": bool,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateFirewallDescriptionRequestRequestTypeDef = TypedDict(
     "UpdateFirewallDescriptionRequestRequestTypeDef",
     {
         "UpdateToken": str,
         "FirewallArn": str,
         "FirewallName": str,
         "Description": str,
     },
     total=False,
 )
 
+UpdateFirewallDescriptionResponseTypeDef = TypedDict(
+    "UpdateFirewallDescriptionResponseTypeDef",
+    {
+        "FirewallArn": str,
+        "FirewallName": str,
+        "Description": str,
+        "UpdateToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef",
     {
         "FirewallPolicyChangeProtection": bool,
     },
 )
 _OptionalUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef = TypedDict(
@@ -684,14 +855,25 @@
 
 class UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef(
     _RequiredUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
     _OptionalUpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
 ):
     pass
 
+UpdateFirewallPolicyChangeProtectionResponseTypeDef = TypedDict(
+    "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "FirewallArn": str,
+        "FirewallName": str,
+        "FirewallPolicyChangeProtection": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef",
     {
         "SubnetChangeProtection": bool,
     },
 )
 _OptionalUpdateSubnetChangeProtectionRequestRequestTypeDef = TypedDict(
@@ -706,74 +888,22 @@
 
 class UpdateSubnetChangeProtectionRequestRequestTypeDef(
     _RequiredUpdateSubnetChangeProtectionRequestRequestTypeDef,
     _OptionalUpdateSubnetChangeProtectionRequestRequestTypeDef,
 ):
     pass
 
-AssociateFirewallPolicyResponseTypeDef = TypedDict(
-    "AssociateFirewallPolicyResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "FirewallPolicyArn": str,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDeleteProtectionResponseTypeDef = TypedDict(
-    "UpdateFirewallDeleteProtectionResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "DeleteProtection": bool,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallDescriptionResponseTypeDef = TypedDict(
-    "UpdateFirewallDescriptionResponseTypeDef",
-    {
-        "FirewallArn": str,
-        "FirewallName": str,
-        "Description": str,
-        "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFirewallPolicyChangeProtectionResponseTypeDef = TypedDict(
-    "UpdateFirewallPolicyChangeProtectionResponseTypeDef",
-    {
-        "UpdateToken": str,
-        "FirewallArn": str,
-        "FirewallName": str,
-        "FirewallPolicyChangeProtection": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSubnetChangeProtectionResponseTypeDef = TypedDict(
     "UpdateSubnetChangeProtectionResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetChangeProtection": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateSubnetsRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateSubnetsRequestRequestTypeDef",
     {
         "SubnetMappings": Sequence[SubnetMappingTypeDef],
@@ -797,26 +927,26 @@
 AssociateSubnetsResponseTypeDef = TypedDict(
     "AssociateSubnetsResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetMappings": List[SubnetMappingTypeDef],
         "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateSubnetsResponseTypeDef = TypedDict(
     "DisassociateSubnetsResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "SubnetMappings": List[SubnetMappingTypeDef],
         "UpdateToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CIDRSummaryTypeDef = TypedDict(
     "CIDRSummaryTypeDef",
     {
         "AvailableCIDRCount": int,
@@ -840,15 +970,15 @@
 UpdateFirewallEncryptionConfigurationResponseTypeDef = TypedDict(
     "UpdateFirewallEncryptionConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "UpdateToken": str,
         "EncryptionConfiguration": EncryptionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFirewallRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFirewallRequestRequestTypeDef",
     {
         "FirewallName": str,
@@ -931,15 +1061,15 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "NextToken": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -984,15 +1114,15 @@
         "RuleGroupArn": str,
         "RuleGroupName": str,
         "Description": str,
         "Type": RuleGroupTypeType,
         "Capacity": int,
         "StatefulRuleOptions": StatefulRuleOptionsTypeDef,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublishMetricActionTypeDef = TypedDict(
     "PublishMetricActionTypeDef",
     {
         "Dimensions": Sequence[DimensionTypeDef],
@@ -1000,99 +1130,80 @@
 )
 
 ListFirewallsResponseTypeDef = TypedDict(
     "ListFirewallsResponseTypeDef",
     {
         "NextToken": str,
         "Firewalls": List[FirewallMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFirewallPoliciesResponseTypeDef = TypedDict(
     "ListFirewallPoliciesResponseTypeDef",
     {
         "NextToken": str,
         "FirewallPolicies": List[FirewallPolicyMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReferenceSetsTypeDef = TypedDict(
     "ReferenceSetsTypeDef",
     {
         "IPSetReferences": Mapping[str, IPSetReferenceTypeDef],
     },
     total=False,
 )
 
-ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef = TypedDict(
-    "ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFirewallsRequestListFirewallsPaginateTypeDef = TypedDict(
-    "ListFirewallsRequestListFirewallsPaginateTypeDef",
+PolicyVariablesTypeDef = TypedDict(
+    "PolicyVariablesTypeDef",
     {
-        "VpcIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RuleVariables": Mapping[str, IPSetTypeDef],
     },
     total=False,
 )
 
-ListRuleGroupsRequestListRuleGroupsPaginateTypeDef = TypedDict(
-    "ListRuleGroupsRequestListRuleGroupsPaginateTypeDef",
+ListRuleGroupsResponseTypeDef = TypedDict(
+    "ListRuleGroupsResponseTypeDef",
     {
-        "Scope": ResourceManagedStatusType,
-        "ManagedType": ResourceManagedTypeType,
-        "Type": RuleGroupTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "RuleGroups": List[RuleGroupMetadataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
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
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-ListRuleGroupsResponseTypeDef = TypedDict(
-    "ListRuleGroupsResponseTypeDef",
+ListTLSInspectionConfigurationsResponseTypeDef = TypedDict(
+    "ListTLSInspectionConfigurationsResponseTypeDef",
     {
         "NextToken": str,
-        "RuleGroups": List[RuleGroupMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TLSInspectionConfigurations": List[TLSInspectionConfigurationMetadataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationTypeDef = TypedDict(
     "LoggingConfigurationTypeDef",
     {
         "LogDestinationConfigs": List[LogDestinationConfigTypeDef],
     },
 )
 
+ServerCertificateScopeTypeDef = TypedDict(
+    "ServerCertificateScopeTypeDef",
+    {
+        "Sources": Sequence[AddressTypeDef],
+        "Destinations": Sequence[AddressTypeDef],
+        "SourcePorts": Sequence[PortRangeTypeDef],
+        "DestinationPorts": Sequence[PortRangeTypeDef],
+        "Protocols": Sequence[int],
+    },
+    total=False,
+)
+
 MatchAttributesTypeDef = TypedDict(
     "MatchAttributesTypeDef",
     {
         "Sources": Sequence[AddressTypeDef],
         "Destinations": Sequence[AddressTypeDef],
         "SourcePorts": Sequence[PortRangeTypeDef],
         "DestinationPorts": Sequence[PortRangeTypeDef],
@@ -1145,71 +1256,99 @@
 )
 
 class StatefulRuleGroupReferenceTypeDef(
     _RequiredStatefulRuleGroupReferenceTypeDef, _OptionalStatefulRuleGroupReferenceTypeDef
 ):
     pass
 
+_RequiredTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "_RequiredTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+        "TLSInspectionConfigurationId": str,
+    },
+)
+_OptionalTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "_OptionalTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationStatus": ResourceStatusType,
+        "Description": str,
+        "Tags": List[TagTypeDef],
+        "LastModifiedTime": datetime,
+        "NumberOfAssociations": int,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+        "Certificates": List[TlsCertificateDataTypeDef],
+    },
+    total=False,
+)
+
+class TLSInspectionConfigurationResponseTypeDef(
+    _RequiredTLSInspectionConfigurationResponseTypeDef,
+    _OptionalTLSInspectionConfigurationResponseTypeDef,
+):
+    pass
+
 CapacityUsageSummaryTypeDef = TypedDict(
     "CapacityUsageSummaryTypeDef",
     {
         "CIDRs": CIDRSummaryTypeDef,
     },
     total=False,
 )
 
 CreateFirewallPolicyResponseTypeDef = TypedDict(
     "CreateFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallPolicyResponseTypeDef = TypedDict(
     "DeleteFirewallPolicyResponseTypeDef",
     {
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFirewallPolicyResponseTypeDef = TypedDict(
     "UpdateFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleGroupResponseTypeDef = TypedDict(
     "CreateRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRuleGroupResponseTypeDef = TypedDict(
     "DeleteRuleGroupResponseTypeDef",
     {
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRuleGroupResponseTypeDef = TypedDict(
     "UpdateRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionDefinitionTypeDef = TypedDict(
     "ActionDefinitionTypeDef",
     {
         "PublishMetricAction": PublishMetricActionTypeDef,
@@ -1218,15 +1357,15 @@
 )
 
 DescribeLoggingConfigurationResponseTypeDef = TypedDict(
     "DescribeLoggingConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateLoggingConfigurationRequestRequestTypeDef",
     {
         "FirewallArn": str,
@@ -1238,26 +1377,61 @@
 
 UpdateLoggingConfigurationResponseTypeDef = TypedDict(
     "UpdateLoggingConfigurationResponseTypeDef",
     {
         "FirewallArn": str,
         "FirewallName": str,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ServerCertificateConfigurationTypeDef = TypedDict(
+    "ServerCertificateConfigurationTypeDef",
+    {
+        "ServerCertificates": Sequence[ServerCertificateTypeDef],
+        "Scopes": Sequence[ServerCertificateScopeTypeDef],
     },
+    total=False,
 )
 
 RuleDefinitionTypeDef = TypedDict(
     "RuleDefinitionTypeDef",
     {
         "MatchAttributes": MatchAttributesTypeDef,
         "Actions": Sequence[str],
     },
 )
 
+CreateTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "CreateTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "DeleteTLSInspectionConfigurationResponseTypeDef",
+    {
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "UpdateTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFirewallStatusTypeDef = TypedDict(
     "_RequiredFirewallStatusTypeDef",
     {
         "Status": FirewallStatusValueType,
         "ConfigurationSyncStateSummary": ConfigurationSyncStateType,
     },
 )
@@ -1277,47 +1451,55 @@
     "CustomActionTypeDef",
     {
         "ActionName": str,
         "ActionDefinition": ActionDefinitionTypeDef,
     },
 )
 
+TLSInspectionConfigurationTypeDef = TypedDict(
+    "TLSInspectionConfigurationTypeDef",
+    {
+        "ServerCertificateConfigurations": Sequence[ServerCertificateConfigurationTypeDef],
+    },
+    total=False,
+)
+
 StatelessRuleTypeDef = TypedDict(
     "StatelessRuleTypeDef",
     {
         "RuleDefinition": RuleDefinitionTypeDef,
         "Priority": int,
     },
 )
 
 CreateFirewallResponseTypeDef = TypedDict(
     "CreateFirewallResponseTypeDef",
     {
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFirewallResponseTypeDef = TypedDict(
     "DeleteFirewallResponseTypeDef",
     {
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFirewallResponseTypeDef = TypedDict(
     "DescribeFirewallResponseTypeDef",
     {
         "UpdateToken": str,
         "Firewall": FirewallTypeDef,
         "FirewallStatus": FirewallStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFirewallPolicyTypeDef = TypedDict(
     "_RequiredFirewallPolicyTypeDef",
     {
         "StatelessDefaultActions": Sequence[str],
@@ -1328,21 +1510,80 @@
     "_OptionalFirewallPolicyTypeDef",
     {
         "StatelessRuleGroupReferences": Sequence[StatelessRuleGroupReferenceTypeDef],
         "StatelessCustomActions": Sequence[CustomActionTypeDef],
         "StatefulRuleGroupReferences": Sequence[StatefulRuleGroupReferenceTypeDef],
         "StatefulDefaultActions": Sequence[str],
         "StatefulEngineOptions": StatefulEngineOptionsTypeDef,
+        "TLSInspectionConfigurationArn": str,
+        "PolicyVariables": PolicyVariablesTypeDef,
     },
     total=False,
 )
 
 class FirewallPolicyTypeDef(_RequiredFirewallPolicyTypeDef, _OptionalFirewallPolicyTypeDef):
     pass
 
+_RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationName": str,
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+    },
+)
+_OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "Description": str,
+        "Tags": Sequence[TagTypeDef],
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class CreateTLSInspectionConfigurationRequestRequestTypeDef(
+    _RequiredCreateTLSInspectionConfigurationRequestRequestTypeDef,
+    _OptionalCreateTLSInspectionConfigurationRequestRequestTypeDef,
+):
+    pass
+
+DescribeTLSInspectionConfigurationResponseTypeDef = TypedDict(
+    "DescribeTLSInspectionConfigurationResponseTypeDef",
+    {
+        "UpdateToken": str,
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+        "TLSInspectionConfigurationResponse": TLSInspectionConfigurationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfiguration": TLSInspectionConfigurationTypeDef,
+        "UpdateToken": str,
+    },
+)
+_OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef",
+    {
+        "TLSInspectionConfigurationArn": str,
+        "TLSInspectionConfigurationName": str,
+        "Description": str,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class UpdateTLSInspectionConfigurationRequestRequestTypeDef(
+    _RequiredUpdateTLSInspectionConfigurationRequestRequestTypeDef,
+    _OptionalUpdateTLSInspectionConfigurationRequestRequestTypeDef,
+):
+    pass
+
 _RequiredStatelessRulesAndCustomActionsTypeDef = TypedDict(
     "_RequiredStatelessRulesAndCustomActionsTypeDef",
     {
         "StatelessRules": Sequence[StatelessRuleTypeDef],
     },
 )
 _OptionalStatelessRulesAndCustomActionsTypeDef = TypedDict(
@@ -1384,15 +1625,15 @@
 
 DescribeFirewallPolicyResponseTypeDef = TypedDict(
     "DescribeFirewallPolicyResponseTypeDef",
     {
         "UpdateToken": str,
         "FirewallPolicyResponse": FirewallPolicyResponseTypeDef,
         "FirewallPolicy": FirewallPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFirewallPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFirewallPolicyRequestRequestTypeDef",
     {
         "UpdateToken": str,
@@ -1476,15 +1717,15 @@
 
 DescribeRuleGroupResponseTypeDef = TypedDict(
     "DescribeRuleGroupResponseTypeDef",
     {
         "UpdateToken": str,
         "RuleGroup": RuleGroupTypeDef,
         "RuleGroupResponse": RuleGroupResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRuleGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRuleGroupRequestRequestTypeDef",
     {
         "UpdateToken": str,
```

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/PKG-INFO` & `types-aiobotocore-network-firewall-2.5.1/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-network-firewall
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NetworkFirewall 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore network-firewall type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-network-firewall"></a>
 
 # types-aiobotocore-network-firewall
 
 [![PyPI - types-aiobotocore-network-firewall](https://img.shields.io/pypi/v/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-network-firewall.svg?color=blue)](https://pypi.org/project/types-aiobotocore-network-firewall)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-network-firewall?color=blue)](https://pypistats.org/packages/types-aiobotocore-network-firewall)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkFirewall 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
+[aiobotocore.NetworkFirewall 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/network-firewall.html#NetworkFirewall)
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
 [types-aiobotocore-network-firewall docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_network_firewall/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,28 +243,32 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_network_firewall import NetworkFirewallClient
 from types_aiobotocore_network_firewall.paginator import (
     ListFirewallPoliciesPaginator,
     ListFirewallsPaginator,
     ListRuleGroupsPaginator,
+    ListTLSInspectionConfigurationsPaginator,
     ListTagsForResourcePaginator,
 )
 
 session = get_session()
 async with session.create_client("network-firewall") as client:
     client: NetworkFirewallClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_firewall_policies_paginator: ListFirewallPoliciesPaginator = client.get_paginator(
         "list_firewall_policies"
     )
     list_firewalls_paginator: ListFirewallsPaginator = client.get_paginator("list_firewalls")
     list_rule_groups_paginator: ListRuleGroupsPaginator = client.get_paginator("list_rule_groups")
+    list_tls_inspection_configurations_paginator: ListTLSInspectionConfigurationsPaginator = (
+        client.get_paginator("list_tls_inspection_configurations")
+    )
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator(
         "list_tags_for_resource"
     )
 ```
 
 <a id="literals"></a>
 
@@ -313,14 +284,15 @@
     EncryptionTypeType,
     FirewallStatusValueType,
     GeneratedRulesTypeType,
     IPAddressTypeType,
     ListFirewallPoliciesPaginatorName,
     ListFirewallsPaginatorName,
     ListRuleGroupsPaginatorName,
+    ListTLSInspectionConfigurationsPaginatorName,
     ListTagsForResourcePaginatorName,
     LogDestinationTypeType,
     LogTypeType,
     OverrideActionType,
     PerObjectSyncStatusType,
     ResourceManagedStatusType,
     ResourceManagedTypeType,
@@ -352,66 +324,77 @@
 `types_aiobotocore_network_firewall.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_network_firewall.type_defs import (
     AddressTypeDef,
     AssociateFirewallPolicyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateFirewallPolicyResponseTypeDef,
     SubnetMappingTypeDef,
     AttachmentTypeDef,
     IPSetMetadataTypeDef,
     EncryptionConfigurationTypeDef,
     TagTypeDef,
     SourceMetadataTypeDef,
     DeleteFirewallPolicyRequestRequestTypeDef,
     DeleteFirewallRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRuleGroupRequestRequestTypeDef,
+    DeleteTLSInspectionConfigurationRequestRequestTypeDef,
     DescribeFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallRequestRequestTypeDef,
     DescribeLoggingConfigurationRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeRuleGroupMetadataRequestRequestTypeDef,
     StatefulRuleOptionsTypeDef,
     DescribeRuleGroupRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationRequestRequestTypeDef,
     DimensionTypeDef,
     DisassociateSubnetsRequestRequestTypeDef,
     FirewallMetadataTypeDef,
     FirewallPolicyMetadataTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupReferenceTypeDef,
     HeaderTypeDef,
     IPSetReferenceTypeDef,
     IPSetTypeDef,
-    PaginatorConfigTypeDef,
+    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
     ListFirewallPoliciesRequestRequestTypeDef,
+    ListFirewallsRequestListFirewallsPaginateTypeDef,
     ListFirewallsRequestRequestTypeDef,
+    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
     ListRuleGroupsRequestRequestTypeDef,
     RuleGroupMetadataTypeDef,
+    ListTLSInspectionConfigurationsRequestListTLSInspectionConfigurationsPaginateTypeDef,
+    ListTLSInspectionConfigurationsRequestRequestTypeDef,
+    TLSInspectionConfigurationMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     LogDestinationConfigTypeDef,
     PortRangeTypeDef,
     TCPFlagFieldTypeDef,
+    PaginatorConfigTypeDef,
     PerObjectStatusTypeDef,
     PortSetTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuleOptionTypeDef,
     RulesSourceListTypeDef,
+    ServerCertificateTypeDef,
     StatefulRuleGroupOverrideTypeDef,
+    TlsCertificateDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFirewallDeleteProtectionRequestRequestTypeDef,
-    UpdateFirewallDescriptionRequestRequestTypeDef,
-    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
-    UpdateSubnetChangeProtectionRequestRequestTypeDef,
-    AssociateFirewallPolicyResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
     UpdateFirewallDeleteProtectionResponseTypeDef,
+    UpdateFirewallDescriptionRequestRequestTypeDef,
     UpdateFirewallDescriptionResponseTypeDef,
+    UpdateFirewallPolicyChangeProtectionRequestRequestTypeDef,
     UpdateFirewallPolicyChangeProtectionResponseTypeDef,
+    UpdateSubnetChangeProtectionRequestRequestTypeDef,
     UpdateSubnetChangeProtectionResponseTypeDef,
     AssociateSubnetsRequestRequestTypeDef,
     AssociateSubnetsResponseTypeDef,
     DisassociateSubnetsResponseTypeDef,
     CIDRSummaryTypeDef,
     UpdateFirewallEncryptionConfigurationRequestRequestTypeDef,
     UpdateFirewallEncryptionConfigurationResponseTypeDef,
@@ -422,44 +405,52 @@
     TagResourceRequestRequestTypeDef,
     RuleGroupResponseTypeDef,
     DescribeRuleGroupMetadataResponseTypeDef,
     PublishMetricActionTypeDef,
     ListFirewallsResponseTypeDef,
     ListFirewallPoliciesResponseTypeDef,
     ReferenceSetsTypeDef,
-    ListFirewallPoliciesRequestListFirewallPoliciesPaginateTypeDef,
-    ListFirewallsRequestListFirewallsPaginateTypeDef,
-    ListRuleGroupsRequestListRuleGroupsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    PolicyVariablesTypeDef,
     ListRuleGroupsResponseTypeDef,
+    ListTLSInspectionConfigurationsResponseTypeDef,
     LoggingConfigurationTypeDef,
+    ServerCertificateScopeTypeDef,
     MatchAttributesTypeDef,
     SyncStateTypeDef,
     RuleVariablesTypeDef,
     StatefulRuleTypeDef,
     StatefulRuleGroupReferenceTypeDef,
+    TLSInspectionConfigurationResponseTypeDef,
     CapacityUsageSummaryTypeDef,
     CreateFirewallPolicyResponseTypeDef,
     DeleteFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyResponseTypeDef,
     CreateRuleGroupResponseTypeDef,
     DeleteRuleGroupResponseTypeDef,
     UpdateRuleGroupResponseTypeDef,
     ActionDefinitionTypeDef,
     DescribeLoggingConfigurationResponseTypeDef,
     UpdateLoggingConfigurationRequestRequestTypeDef,
     UpdateLoggingConfigurationResponseTypeDef,
+    ServerCertificateConfigurationTypeDef,
     RuleDefinitionTypeDef,
+    CreateTLSInspectionConfigurationResponseTypeDef,
+    DeleteTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationResponseTypeDef,
     FirewallStatusTypeDef,
     CustomActionTypeDef,
+    TLSInspectionConfigurationTypeDef,
     StatelessRuleTypeDef,
     CreateFirewallResponseTypeDef,
     DeleteFirewallResponseTypeDef,
     DescribeFirewallResponseTypeDef,
     FirewallPolicyTypeDef,
+    CreateTLSInspectionConfigurationRequestRequestTypeDef,
+    DescribeTLSInspectionConfigurationResponseTypeDef,
+    UpdateTLSInspectionConfigurationRequestRequestTypeDef,
     StatelessRulesAndCustomActionsTypeDef,
     CreateFirewallPolicyRequestRequestTypeDef,
     DescribeFirewallPolicyResponseTypeDef,
     UpdateFirewallPolicyRequestRequestTypeDef,
     RulesSourceTypeDef,
     RuleGroupTypeDef,
     CreateRuleGroupRequestRequestTypeDef,
@@ -475,43 +466,43 @@
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

### Comparing `types-aiobotocore-network-firewall-2.5.0.post1/types_aiobotocore_network_firewall.egg-info/SOURCES.txt` & `types-aiobotocore-network-firewall-2.5.1/types_aiobotocore_network_firewall.egg-info/SOURCES.txt`

 * *Files identical despite different names*

