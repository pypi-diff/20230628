# Comparing `tmp/types-aiobotocore-workmail-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-workmail-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-workmail-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-workmail-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-workmail-2.5.0.post1.tar` & `types-aiobotocore-workmail-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.279721 types-aiobotocore-workmail-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21569 2023-03-11 12:27:30.279721 types-aiobotocore-workmail-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19994 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.279721 types-aiobotocore-workmail-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.275721 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/
--rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2344 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    60367 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    60269 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9875 2023-03-11 12:25:42.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9873 2023-03-11 12:25:42.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11188 2023-03-11 12:25:42.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11176 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    59711 2023-03-11 12:25:43.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    59632 2023-03-11 12:25:42.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:41.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.275721 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21569 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:30.000000 types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.470232 types-aiobotocore-workmail-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21562 2023-06-28 01:44:20.470232 types-aiobotocore-workmail-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19993 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.470232 types-aiobotocore-workmail-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:42:34.000000 types-aiobotocore-workmail-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.466232 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/
+-rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2344 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60366 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60268 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10084 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10082 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11150 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11139 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    59811 2023-06-28 01:42:39.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59732 2023-06-28 01:42:38.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:35.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.470232 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21562 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:20.000000 types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/LICENSE` & `types-aiobotocore-workmail-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/PKG-INFO` & `types-aiobotocore-workmail-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workmail
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkMail 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkMail 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workmail"></a>
 
 # types-aiobotocore-workmail
 
 [![PyPI - types-aiobotocore-workmail](https://img.shields.io/pypi/v/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmail?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
+[aiobotocore.WorkMail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
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
 [types-aiobotocore-workmail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -367,128 +367,137 @@
 
 ```python
 from types_aiobotocore_workmail.type_defs import (
     AccessControlRuleTypeDef,
     AssociateDelegateToResourceRequestRequestTypeDef,
     AssociateMemberToGroupRequestRequestTypeDef,
     AssumeImpersonationRoleRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssumeImpersonationRoleResponseTypeDef,
     LambdaAvailabilityProviderTypeDef,
     RedactedEwsAvailabilityProviderTypeDef,
     BookingOptionsTypeDef,
     CancelMailboxExportJobRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     EwsAvailabilityProviderTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     ImpersonationRuleTypeDef,
+    CreateImpersonationRoleResponseTypeDef,
     CreateMobileDeviceAccessRuleRequestRequestTypeDef,
+    CreateMobileDeviceAccessRuleResponseTypeDef,
     DomainTypeDef,
+    CreateOrganizationResponseTypeDef,
     CreateResourceRequestRequestTypeDef,
+    CreateResourceResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     DelegateTypeDef,
     DeleteAccessControlRuleRequestRequestTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteAvailabilityConfigurationRequestRequestTypeDef,
     DeleteEmailMonitoringConfigurationRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteImpersonationRoleRequestRequestTypeDef,
     DeleteMailboxPermissionsRequestRequestTypeDef,
     DeleteMobileDeviceAccessOverrideRequestRequestTypeDef,
     DeleteMobileDeviceAccessRuleRequestRequestTypeDef,
     DeleteOrganizationRequestRequestTypeDef,
+    DeleteOrganizationResponseTypeDef,
     DeleteResourceRequestRequestTypeDef,
     DeleteRetentionPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeregisterFromWorkMailRequestRequestTypeDef,
     DeregisterMailDomainRequestRequestTypeDef,
     DescribeEmailMonitoringConfigurationRequestRequestTypeDef,
+    DescribeEmailMonitoringConfigurationResponseTypeDef,
     DescribeGroupRequestRequestTypeDef,
+    DescribeGroupResponseTypeDef,
     DescribeInboundDmarcSettingsRequestRequestTypeDef,
+    DescribeInboundDmarcSettingsResponseTypeDef,
     DescribeMailboxExportJobRequestRequestTypeDef,
+    DescribeMailboxExportJobResponseTypeDef,
     DescribeOrganizationRequestRequestTypeDef,
+    DescribeOrganizationResponseTypeDef,
     DescribeResourceRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
+    DescribeUserResponseTypeDef,
     DisassociateDelegateFromResourceRequestRequestTypeDef,
     DisassociateMemberFromGroupRequestRequestTypeDef,
     DnsRecordTypeDef,
     FolderConfigurationTypeDef,
     GetAccessControlEffectRequestRequestTypeDef,
+    GetAccessControlEffectResponseTypeDef,
     GetDefaultRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectRequestRequestTypeDef,
     ImpersonationMatchedRuleTypeDef,
     GetImpersonationRoleRequestRequestTypeDef,
     GetMailDomainRequestRequestTypeDef,
     GetMailboxDetailsRequestRequestTypeDef,
+    GetMailboxDetailsResponseTypeDef,
     GetMobileDeviceAccessEffectRequestRequestTypeDef,
     MobileDeviceAccessMatchedRuleTypeDef,
     GetMobileDeviceAccessOverrideRequestRequestTypeDef,
+    GetMobileDeviceAccessOverrideResponseTypeDef,
     GroupTypeDef,
     ImpersonationRoleTypeDef,
     ListAccessControlRulesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListAliasesResponseTypeDef,
+    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
     ListAvailabilityConfigurationsRequestRequestTypeDef,
+    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
     ListGroupMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListImpersonationRolesRequestRequestTypeDef,
     ListMailDomainsRequestRequestTypeDef,
     MailDomainSummaryTypeDef,
     ListMailboxExportJobsRequestRequestTypeDef,
     MailboxExportJobTypeDef,
+    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
     ListMailboxPermissionsRequestRequestTypeDef,
     PermissionTypeDef,
     ListMobileDeviceAccessOverridesRequestRequestTypeDef,
     MobileDeviceAccessOverrideTypeDef,
     ListMobileDeviceAccessRulesRequestRequestTypeDef,
     MobileDeviceAccessRuleTypeDef,
+    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
     ListOrganizationsRequestRequestTypeDef,
     OrganizationSummaryTypeDef,
+    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
     ListResourceDelegatesRequestRequestTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     PutAccessControlRuleRequestRequestTypeDef,
     PutEmailMonitoringConfigurationRequestRequestTypeDef,
     PutInboundDmarcSettingsRequestRequestTypeDef,
     PutMailboxPermissionsRequestRequestTypeDef,
     PutMobileDeviceAccessOverrideRequestRequestTypeDef,
     RegisterMailDomainRequestRequestTypeDef,
     RegisterToWorkMailRequestRequestTypeDef,
     ResetPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMailboxExportJobRequestRequestTypeDef,
+    StartMailboxExportJobResponseTypeDef,
+    TestAvailabilityConfigurationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDefaultMailDomainRequestRequestTypeDef,
     UpdateMailboxQuotaRequestRequestTypeDef,
     UpdateMobileDeviceAccessRuleRequestRequestTypeDef,
     UpdatePrimaryEmailAddressRequestRequestTypeDef,
-    AssumeImpersonationRoleResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateImpersonationRoleResponseTypeDef,
-    CreateMobileDeviceAccessRuleResponseTypeDef,
-    CreateOrganizationResponseTypeDef,
-    CreateResourceResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteOrganizationResponseTypeDef,
-    DescribeEmailMonitoringConfigurationResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    DescribeInboundDmarcSettingsResponseTypeDef,
-    DescribeMailboxExportJobResponseTypeDef,
-    DescribeOrganizationResponseTypeDef,
-    DescribeUserResponseTypeDef,
-    GetAccessControlEffectResponseTypeDef,
-    GetMailboxDetailsResponseTypeDef,
-    GetMobileDeviceAccessOverrideResponseTypeDef,
     ListAccessControlRulesResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    StartMailboxExportJobResponseTypeDef,
-    TestAvailabilityConfigurationResponseTypeDef,
     AvailabilityConfigurationTypeDef,
     DescribeResourceResponseTypeDef,
     UpdateResourceRequestRequestTypeDef,
     CreateAvailabilityConfigurationRequestRequestTypeDef,
     TestAvailabilityConfigurationRequestRequestTypeDef,
     UpdateAvailabilityConfigurationRequestRequestTypeDef,
     CreateImpersonationRoleRequestRequestTypeDef,
@@ -499,23 +508,14 @@
     GetMailDomainResponseTypeDef,
     GetDefaultRetentionPolicyResponseTypeDef,
     PutRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectResponseTypeDef,
     GetMobileDeviceAccessEffectResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListImpersonationRolesResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
-    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListGroupMembersResponseTypeDef,
     ListMailDomainsResponseTypeDef,
     ListMailboxExportJobsResponseTypeDef,
     ListMailboxPermissionsResponseTypeDef,
     ListMobileDeviceAccessOverridesResponseTypeDef,
     ListMobileDeviceAccessRulesResponseTypeDef,
     ListOrganizationsResponseTypeDef,
@@ -534,43 +534,43 @@
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/README.md` & `types-aiobotocore-workmail-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-workmail"></a>
 
 # types-aiobotocore-workmail
 
 [![PyPI - types-aiobotocore-workmail](https://img.shields.io/pypi/v/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmail?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
+[aiobotocore.WorkMail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
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
 [types-aiobotocore-workmail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,128 +334,137 @@
 
 ```python
 from types_aiobotocore_workmail.type_defs import (
     AccessControlRuleTypeDef,
     AssociateDelegateToResourceRequestRequestTypeDef,
     AssociateMemberToGroupRequestRequestTypeDef,
     AssumeImpersonationRoleRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssumeImpersonationRoleResponseTypeDef,
     LambdaAvailabilityProviderTypeDef,
     RedactedEwsAvailabilityProviderTypeDef,
     BookingOptionsTypeDef,
     CancelMailboxExportJobRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     EwsAvailabilityProviderTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     ImpersonationRuleTypeDef,
+    CreateImpersonationRoleResponseTypeDef,
     CreateMobileDeviceAccessRuleRequestRequestTypeDef,
+    CreateMobileDeviceAccessRuleResponseTypeDef,
     DomainTypeDef,
+    CreateOrganizationResponseTypeDef,
     CreateResourceRequestRequestTypeDef,
+    CreateResourceResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     DelegateTypeDef,
     DeleteAccessControlRuleRequestRequestTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteAvailabilityConfigurationRequestRequestTypeDef,
     DeleteEmailMonitoringConfigurationRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteImpersonationRoleRequestRequestTypeDef,
     DeleteMailboxPermissionsRequestRequestTypeDef,
     DeleteMobileDeviceAccessOverrideRequestRequestTypeDef,
     DeleteMobileDeviceAccessRuleRequestRequestTypeDef,
     DeleteOrganizationRequestRequestTypeDef,
+    DeleteOrganizationResponseTypeDef,
     DeleteResourceRequestRequestTypeDef,
     DeleteRetentionPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeregisterFromWorkMailRequestRequestTypeDef,
     DeregisterMailDomainRequestRequestTypeDef,
     DescribeEmailMonitoringConfigurationRequestRequestTypeDef,
+    DescribeEmailMonitoringConfigurationResponseTypeDef,
     DescribeGroupRequestRequestTypeDef,
+    DescribeGroupResponseTypeDef,
     DescribeInboundDmarcSettingsRequestRequestTypeDef,
+    DescribeInboundDmarcSettingsResponseTypeDef,
     DescribeMailboxExportJobRequestRequestTypeDef,
+    DescribeMailboxExportJobResponseTypeDef,
     DescribeOrganizationRequestRequestTypeDef,
+    DescribeOrganizationResponseTypeDef,
     DescribeResourceRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
+    DescribeUserResponseTypeDef,
     DisassociateDelegateFromResourceRequestRequestTypeDef,
     DisassociateMemberFromGroupRequestRequestTypeDef,
     DnsRecordTypeDef,
     FolderConfigurationTypeDef,
     GetAccessControlEffectRequestRequestTypeDef,
+    GetAccessControlEffectResponseTypeDef,
     GetDefaultRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectRequestRequestTypeDef,
     ImpersonationMatchedRuleTypeDef,
     GetImpersonationRoleRequestRequestTypeDef,
     GetMailDomainRequestRequestTypeDef,
     GetMailboxDetailsRequestRequestTypeDef,
+    GetMailboxDetailsResponseTypeDef,
     GetMobileDeviceAccessEffectRequestRequestTypeDef,
     MobileDeviceAccessMatchedRuleTypeDef,
     GetMobileDeviceAccessOverrideRequestRequestTypeDef,
+    GetMobileDeviceAccessOverrideResponseTypeDef,
     GroupTypeDef,
     ImpersonationRoleTypeDef,
     ListAccessControlRulesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListAliasesResponseTypeDef,
+    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
     ListAvailabilityConfigurationsRequestRequestTypeDef,
+    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
     ListGroupMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListImpersonationRolesRequestRequestTypeDef,
     ListMailDomainsRequestRequestTypeDef,
     MailDomainSummaryTypeDef,
     ListMailboxExportJobsRequestRequestTypeDef,
     MailboxExportJobTypeDef,
+    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
     ListMailboxPermissionsRequestRequestTypeDef,
     PermissionTypeDef,
     ListMobileDeviceAccessOverridesRequestRequestTypeDef,
     MobileDeviceAccessOverrideTypeDef,
     ListMobileDeviceAccessRulesRequestRequestTypeDef,
     MobileDeviceAccessRuleTypeDef,
+    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
     ListOrganizationsRequestRequestTypeDef,
     OrganizationSummaryTypeDef,
+    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
     ListResourceDelegatesRequestRequestTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     PutAccessControlRuleRequestRequestTypeDef,
     PutEmailMonitoringConfigurationRequestRequestTypeDef,
     PutInboundDmarcSettingsRequestRequestTypeDef,
     PutMailboxPermissionsRequestRequestTypeDef,
     PutMobileDeviceAccessOverrideRequestRequestTypeDef,
     RegisterMailDomainRequestRequestTypeDef,
     RegisterToWorkMailRequestRequestTypeDef,
     ResetPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMailboxExportJobRequestRequestTypeDef,
+    StartMailboxExportJobResponseTypeDef,
+    TestAvailabilityConfigurationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDefaultMailDomainRequestRequestTypeDef,
     UpdateMailboxQuotaRequestRequestTypeDef,
     UpdateMobileDeviceAccessRuleRequestRequestTypeDef,
     UpdatePrimaryEmailAddressRequestRequestTypeDef,
-    AssumeImpersonationRoleResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateImpersonationRoleResponseTypeDef,
-    CreateMobileDeviceAccessRuleResponseTypeDef,
-    CreateOrganizationResponseTypeDef,
-    CreateResourceResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteOrganizationResponseTypeDef,
-    DescribeEmailMonitoringConfigurationResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    DescribeInboundDmarcSettingsResponseTypeDef,
-    DescribeMailboxExportJobResponseTypeDef,
-    DescribeOrganizationResponseTypeDef,
-    DescribeUserResponseTypeDef,
-    GetAccessControlEffectResponseTypeDef,
-    GetMailboxDetailsResponseTypeDef,
-    GetMobileDeviceAccessOverrideResponseTypeDef,
     ListAccessControlRulesResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    StartMailboxExportJobResponseTypeDef,
-    TestAvailabilityConfigurationResponseTypeDef,
     AvailabilityConfigurationTypeDef,
     DescribeResourceResponseTypeDef,
     UpdateResourceRequestRequestTypeDef,
     CreateAvailabilityConfigurationRequestRequestTypeDef,
     TestAvailabilityConfigurationRequestRequestTypeDef,
     UpdateAvailabilityConfigurationRequestRequestTypeDef,
     CreateImpersonationRoleRequestRequestTypeDef,
@@ -466,23 +475,14 @@
     GetMailDomainResponseTypeDef,
     GetDefaultRetentionPolicyResponseTypeDef,
     PutRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectResponseTypeDef,
     GetMobileDeviceAccessEffectResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListImpersonationRolesResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
-    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListGroupMembersResponseTypeDef,
     ListMailDomainsResponseTypeDef,
     ListMailboxExportJobsResponseTypeDef,
     ListMailboxPermissionsResponseTypeDef,
     ListMobileDeviceAccessOverridesResponseTypeDef,
     ListMobileDeviceAccessRulesResponseTypeDef,
     ListOrganizationsResponseTypeDef,
@@ -501,43 +501,43 @@
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/setup.py` & `types-aiobotocore-workmail-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-workmail.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-workmail",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_workmail"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WorkMail 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.WorkMail 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/"
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__init__.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__init__.pyi` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/__main__.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WorkMail 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WorkMail 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail\nOther"
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/client.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -685,15 +685,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/client/#list_aliases)
         """
 
     async def list_availability_configurations(
         self, *, OrganizationId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAvailabilityConfigurationsResponseTypeDef:
         """
-        List all the `AvailabilityConfiguration` 's for the given WorkMail organization.
+        List all the `AvailabilityConfiguration`'s for the given WorkMail organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Client.list_availability_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/client/#list_availability_configurations)
         """
 
     async def list_group_members(
         self, *, OrganizationId: str, GroupId: str, NextToken: str = ..., MaxResults: int = ...
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/client.pyi` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -631,15 +631,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Client.list_aliases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/client/#list_aliases)
         """
     async def list_availability_configurations(
         self, *, OrganizationId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAvailabilityConfigurationsResponseTypeDef:
         """
-        List all the `AvailabilityConfiguration` 's for the given WorkMail organization.
+        List all the `AvailabilityConfiguration`'s for the given WorkMail organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Client.list_availability_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/client/#list_availability_configurations)
         """
     async def list_group_members(
         self, *, OrganizationId: str, GroupId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListGroupMembersResponseTypeDef:
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/literals.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -133,14 +133,15 @@
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
@@ -219,14 +220,15 @@
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
@@ -237,14 +239,15 @@
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
@@ -280,14 +283,15 @@
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
@@ -306,16 +310,19 @@
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
@@ -399,15 +406,17 @@
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/literals.pyi` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -131,14 +131,15 @@
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
@@ -217,14 +218,15 @@
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
@@ -235,14 +237,15 @@
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
@@ -278,14 +281,15 @@
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
@@ -304,16 +308,19 @@
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
@@ -397,15 +404,17 @@
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/paginator.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_mailbox_permissions_paginator: ListMailboxPermissionsPaginator = client.get_paginator("list_mailbox_permissions")
         list_organizations_paginator: ListOrganizationsPaginator = client.get_paginator("list_organizations")
         list_resource_delegates_paginator: ListResourceDelegatesPaginator = client.get_paginator("list_resource_delegates")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAliasesResponseTypeDef,
     ListAvailabilityConfigurationsResponseTypeDef,
@@ -51,20 +50,14 @@
     ListOrganizationsResponseTypeDef,
     ListResourceDelegatesResponseTypeDef,
     ListResourcesResponseTypeDef,
     ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAliasesPaginator",
     "ListAvailabilityConfigurationsPaginator",
     "ListGroupMembersPaginator",
     "ListGroupsPaginator",
     "ListMailboxPermissionsPaginator",
     "ListOrganizationsPaginator",
@@ -87,90 +80,98 @@
 class ListAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listaliasespaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, EntityId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        OrganizationId: str,
+        EntityId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listaliasespaginator)
         """
 
 
 class ListAvailabilityConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAvailabilityConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listavailabilityconfigurationspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAvailabilityConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAvailabilityConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listavailabilityconfigurationspaginator)
         """
 
 
 class ListGroupMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroupMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupmemberspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, GroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, GroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroupMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupmemberspaginator)
         """
 
 
 class ListGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupspaginator)
         """
 
 
 class ListMailboxPermissionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListMailboxPermissions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listmailboxpermissionspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, EntityId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        OrganizationId: str,
+        EntityId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMailboxPermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListMailboxPermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listmailboxpermissionspaginator)
         """
 
 
 class ListOrganizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListOrganizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listorganizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListOrganizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listorganizationspaginator)
         """
 
 
@@ -181,43 +182,43 @@
     """
 
     def paginate(
         self,
         *,
         OrganizationId: str,
         ResourceId: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceDelegatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResourceDelegates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcedelegatespaginator)
         """
 
 
 class ListResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcespaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcespaginator)
         """
 
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/paginator.pyi` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_mailbox_permissions_paginator: ListMailboxPermissionsPaginator = client.get_paginator("list_mailbox_permissions")
         list_organizations_paginator: ListOrganizationsPaginator = client.get_paginator("list_organizations")
         list_resource_delegates_paginator: ListResourceDelegatesPaginator = client.get_paginator("list_resource_delegates")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAliasesResponseTypeDef,
     ListAvailabilityConfigurationsResponseTypeDef,
@@ -51,19 +50,14 @@
     ListOrganizationsResponseTypeDef,
     ListResourceDelegatesResponseTypeDef,
     ListResourcesResponseTypeDef,
     ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAliasesPaginator",
     "ListAvailabilityConfigurationsPaginator",
     "ListGroupMembersPaginator",
     "ListGroupsPaginator",
     "ListMailboxPermissionsPaginator",
     "ListOrganizationsPaginator",
@@ -83,85 +77,93 @@
 class ListAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listaliasespaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, EntityId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        OrganizationId: str,
+        EntityId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listaliasespaginator)
         """
 
 class ListAvailabilityConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAvailabilityConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listavailabilityconfigurationspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAvailabilityConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListAvailabilityConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listavailabilityconfigurationspaginator)
         """
 
 class ListGroupMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroupMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupmemberspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, GroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, GroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroupMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupmemberspaginator)
         """
 
 class ListGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listgroupspaginator)
         """
 
 class ListMailboxPermissionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListMailboxPermissions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listmailboxpermissionspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, EntityId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        OrganizationId: str,
+        EntityId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMailboxPermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListMailboxPermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listmailboxpermissionspaginator)
         """
 
 class ListOrganizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListOrganizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listorganizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListOrganizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listorganizationspaginator)
         """
 
 class ListResourceDelegatesPaginator(AioPaginator):
@@ -171,41 +173,41 @@
     """
 
     def paginate(
         self,
         *,
         OrganizationId: str,
         ResourceId: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceDelegatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResourceDelegates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcedelegatespaginator)
         """
 
 class ListResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcespaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listresourcespaginator)
         """
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/type_defs.py` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,128 +39,137 @@
 
 
 __all__ = (
     "AccessControlRuleTypeDef",
     "AssociateDelegateToResourceRequestRequestTypeDef",
     "AssociateMemberToGroupRequestRequestTypeDef",
     "AssumeImpersonationRoleRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssumeImpersonationRoleResponseTypeDef",
     "LambdaAvailabilityProviderTypeDef",
     "RedactedEwsAvailabilityProviderTypeDef",
     "BookingOptionsTypeDef",
     "CancelMailboxExportJobRequestRequestTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "EwsAvailabilityProviderTypeDef",
     "CreateGroupRequestRequestTypeDef",
+    "CreateGroupResponseTypeDef",
     "ImpersonationRuleTypeDef",
+    "CreateImpersonationRoleResponseTypeDef",
     "CreateMobileDeviceAccessRuleRequestRequestTypeDef",
+    "CreateMobileDeviceAccessRuleResponseTypeDef",
     "DomainTypeDef",
+    "CreateOrganizationResponseTypeDef",
     "CreateResourceRequestRequestTypeDef",
+    "CreateResourceResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "CreateUserResponseTypeDef",
     "DelegateTypeDef",
     "DeleteAccessControlRuleRequestRequestTypeDef",
     "DeleteAliasRequestRequestTypeDef",
     "DeleteAvailabilityConfigurationRequestRequestTypeDef",
     "DeleteEmailMonitoringConfigurationRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteImpersonationRoleRequestRequestTypeDef",
     "DeleteMailboxPermissionsRequestRequestTypeDef",
     "DeleteMobileDeviceAccessOverrideRequestRequestTypeDef",
     "DeleteMobileDeviceAccessRuleRequestRequestTypeDef",
     "DeleteOrganizationRequestRequestTypeDef",
+    "DeleteOrganizationResponseTypeDef",
     "DeleteResourceRequestRequestTypeDef",
     "DeleteRetentionPolicyRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DeregisterFromWorkMailRequestRequestTypeDef",
     "DeregisterMailDomainRequestRequestTypeDef",
     "DescribeEmailMonitoringConfigurationRequestRequestTypeDef",
+    "DescribeEmailMonitoringConfigurationResponseTypeDef",
     "DescribeGroupRequestRequestTypeDef",
+    "DescribeGroupResponseTypeDef",
     "DescribeInboundDmarcSettingsRequestRequestTypeDef",
+    "DescribeInboundDmarcSettingsResponseTypeDef",
     "DescribeMailboxExportJobRequestRequestTypeDef",
+    "DescribeMailboxExportJobResponseTypeDef",
     "DescribeOrganizationRequestRequestTypeDef",
+    "DescribeOrganizationResponseTypeDef",
     "DescribeResourceRequestRequestTypeDef",
     "DescribeUserRequestRequestTypeDef",
+    "DescribeUserResponseTypeDef",
     "DisassociateDelegateFromResourceRequestRequestTypeDef",
     "DisassociateMemberFromGroupRequestRequestTypeDef",
     "DnsRecordTypeDef",
     "FolderConfigurationTypeDef",
     "GetAccessControlEffectRequestRequestTypeDef",
+    "GetAccessControlEffectResponseTypeDef",
     "GetDefaultRetentionPolicyRequestRequestTypeDef",
     "GetImpersonationRoleEffectRequestRequestTypeDef",
     "ImpersonationMatchedRuleTypeDef",
     "GetImpersonationRoleRequestRequestTypeDef",
     "GetMailDomainRequestRequestTypeDef",
     "GetMailboxDetailsRequestRequestTypeDef",
+    "GetMailboxDetailsResponseTypeDef",
     "GetMobileDeviceAccessEffectRequestRequestTypeDef",
     "MobileDeviceAccessMatchedRuleTypeDef",
     "GetMobileDeviceAccessOverrideRequestRequestTypeDef",
+    "GetMobileDeviceAccessOverrideResponseTypeDef",
     "GroupTypeDef",
     "ImpersonationRoleTypeDef",
     "ListAccessControlRulesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListAliasesResponseTypeDef",
+    "ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
     "ListAvailabilityConfigurationsRequestRequestTypeDef",
+    "ListGroupMembersRequestListGroupMembersPaginateTypeDef",
     "ListGroupMembersRequestRequestTypeDef",
     "MemberTypeDef",
+    "ListGroupsRequestListGroupsPaginateTypeDef",
     "ListGroupsRequestRequestTypeDef",
     "ListImpersonationRolesRequestRequestTypeDef",
     "ListMailDomainsRequestRequestTypeDef",
     "MailDomainSummaryTypeDef",
     "ListMailboxExportJobsRequestRequestTypeDef",
     "MailboxExportJobTypeDef",
+    "ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
     "ListMailboxPermissionsRequestRequestTypeDef",
     "PermissionTypeDef",
     "ListMobileDeviceAccessOverridesRequestRequestTypeDef",
     "MobileDeviceAccessOverrideTypeDef",
     "ListMobileDeviceAccessRulesRequestRequestTypeDef",
     "MobileDeviceAccessRuleTypeDef",
+    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
     "ListOrganizationsRequestRequestTypeDef",
     "OrganizationSummaryTypeDef",
+    "ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
     "ListResourceDelegatesRequestRequestTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "UserTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccessControlRuleRequestRequestTypeDef",
     "PutEmailMonitoringConfigurationRequestRequestTypeDef",
     "PutInboundDmarcSettingsRequestRequestTypeDef",
     "PutMailboxPermissionsRequestRequestTypeDef",
     "PutMobileDeviceAccessOverrideRequestRequestTypeDef",
     "RegisterMailDomainRequestRequestTypeDef",
     "RegisterToWorkMailRequestRequestTypeDef",
     "ResetPasswordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartMailboxExportJobRequestRequestTypeDef",
+    "StartMailboxExportJobResponseTypeDef",
+    "TestAvailabilityConfigurationResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDefaultMailDomainRequestRequestTypeDef",
     "UpdateMailboxQuotaRequestRequestTypeDef",
     "UpdateMobileDeviceAccessRuleRequestRequestTypeDef",
     "UpdatePrimaryEmailAddressRequestRequestTypeDef",
-    "AssumeImpersonationRoleResponseTypeDef",
-    "CreateGroupResponseTypeDef",
-    "CreateImpersonationRoleResponseTypeDef",
-    "CreateMobileDeviceAccessRuleResponseTypeDef",
-    "CreateOrganizationResponseTypeDef",
-    "CreateResourceResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DeleteOrganizationResponseTypeDef",
-    "DescribeEmailMonitoringConfigurationResponseTypeDef",
-    "DescribeGroupResponseTypeDef",
-    "DescribeInboundDmarcSettingsResponseTypeDef",
-    "DescribeMailboxExportJobResponseTypeDef",
-    "DescribeOrganizationResponseTypeDef",
-    "DescribeUserResponseTypeDef",
-    "GetAccessControlEffectResponseTypeDef",
-    "GetMailboxDetailsResponseTypeDef",
-    "GetMobileDeviceAccessOverrideResponseTypeDef",
     "ListAccessControlRulesResponseTypeDef",
-    "ListAliasesResponseTypeDef",
-    "StartMailboxExportJobResponseTypeDef",
-    "TestAvailabilityConfigurationResponseTypeDef",
     "AvailabilityConfigurationTypeDef",
     "DescribeResourceResponseTypeDef",
     "UpdateResourceRequestRequestTypeDef",
     "CreateAvailabilityConfigurationRequestRequestTypeDef",
     "TestAvailabilityConfigurationRequestRequestTypeDef",
     "UpdateAvailabilityConfigurationRequestRequestTypeDef",
     "CreateImpersonationRoleRequestRequestTypeDef",
@@ -171,23 +180,14 @@
     "GetMailDomainResponseTypeDef",
     "GetDefaultRetentionPolicyResponseTypeDef",
     "PutRetentionPolicyRequestRequestTypeDef",
     "GetImpersonationRoleEffectResponseTypeDef",
     "GetMobileDeviceAccessEffectResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "ListImpersonationRolesResponseTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    "ListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    "ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
-    "ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListGroupMembersResponseTypeDef",
     "ListMailDomainsResponseTypeDef",
     "ListMailboxExportJobsResponseTypeDef",
     "ListMailboxPermissionsResponseTypeDef",
     "ListMobileDeviceAccessOverridesResponseTypeDef",
     "ListMobileDeviceAccessRulesResponseTypeDef",
     "ListOrganizationsResponseTypeDef",
@@ -240,22 +240,20 @@
     "AssumeImpersonationRoleRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ImpersonationRoleId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssumeImpersonationRoleResponseTypeDef = TypedDict(
+    "AssumeImpersonationRoleResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Token": str,
+        "ExpiresIn": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LambdaAvailabilityProviderTypeDef = TypedDict(
     "LambdaAvailabilityProviderTypeDef",
     {
         "LambdaArn": str,
@@ -312,14 +310,22 @@
     "CreateGroupRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
     },
 )
 
+CreateGroupResponseTypeDef = TypedDict(
+    "CreateGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImpersonationRuleTypeDef = TypedDict(
     "_RequiredImpersonationRuleTypeDef",
     {
         "ImpersonationRuleId": str,
         "Effect": AccessEffectType,
     },
 )
@@ -337,14 +343,22 @@
 
 class ImpersonationRuleTypeDef(
     _RequiredImpersonationRuleTypeDef, _OptionalImpersonationRuleTypeDef
 ):
     pass
 
 
+CreateImpersonationRoleResponseTypeDef = TypedDict(
+    "CreateImpersonationRoleResponseTypeDef",
+    {
+        "ImpersonationRoleId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "Effect": MobileDeviceAccessRuleEffectType,
     },
@@ -370,42 +384,74 @@
 class CreateMobileDeviceAccessRuleRequestRequestTypeDef(
     _RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef,
     _OptionalCreateMobileDeviceAccessRuleRequestRequestTypeDef,
 ):
     pass
 
 
+CreateMobileDeviceAccessRuleResponseTypeDef = TypedDict(
+    "CreateMobileDeviceAccessRuleResponseTypeDef",
+    {
+        "MobileDeviceAccessRuleId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
         "DomainName": str,
         "HostedZoneId": str,
     },
     total=False,
 )
 
+CreateOrganizationResponseTypeDef = TypedDict(
+    "CreateOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateResourceRequestRequestTypeDef = TypedDict(
     "CreateResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "Type": ResourceTypeType,
     },
 )
 
+CreateResourceResponseTypeDef = TypedDict(
+    "CreateResourceResponseTypeDef",
+    {
+        "ResourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateUserRequestRequestTypeDef = TypedDict(
     "CreateUserRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "DisplayName": str,
         "Password": str,
     },
 )
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "UserId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DelegateTypeDef = TypedDict(
     "DelegateTypeDef",
     {
         "Id": str,
         "Type": MemberTypeType,
     },
 )
@@ -503,14 +549,23 @@
 class DeleteOrganizationRequestRequestTypeDef(
     _RequiredDeleteOrganizationRequestRequestTypeDef,
     _OptionalDeleteOrganizationRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteOrganizationResponseTypeDef = TypedDict(
+    "DeleteOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourceRequestRequestTypeDef = TypedDict(
     "DeleteResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -550,44 +605,109 @@
 DescribeEmailMonitoringConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeEmailMonitoringConfigurationRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeEmailMonitoringConfigurationResponseTypeDef = TypedDict(
+    "DescribeEmailMonitoringConfigurationResponseTypeDef",
+    {
+        "RoleArn": str,
+        "LogGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGroupRequestRequestTypeDef = TypedDict(
     "DescribeGroupRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "GroupId": str,
     },
 )
 
+DescribeGroupResponseTypeDef = TypedDict(
+    "DescribeGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "Name": str,
+        "Email": str,
+        "State": EntityStateType,
+        "EnabledDate": datetime,
+        "DisabledDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeInboundDmarcSettingsRequestRequestTypeDef = TypedDict(
     "DescribeInboundDmarcSettingsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeInboundDmarcSettingsResponseTypeDef = TypedDict(
+    "DescribeInboundDmarcSettingsResponseTypeDef",
+    {
+        "Enforced": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeMailboxExportJobRequestRequestTypeDef = TypedDict(
     "DescribeMailboxExportJobRequestRequestTypeDef",
     {
         "JobId": str,
         "OrganizationId": str,
     },
 )
 
+DescribeMailboxExportJobResponseTypeDef = TypedDict(
+    "DescribeMailboxExportJobResponseTypeDef",
+    {
+        "EntityId": str,
+        "Description": str,
+        "RoleArn": str,
+        "KmsKeyArn": str,
+        "S3BucketName": str,
+        "S3Prefix": str,
+        "S3Path": str,
+        "EstimatedProgress": int,
+        "State": MailboxExportJobStateType,
+        "ErrorInfo": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeOrganizationRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeOrganizationResponseTypeDef = TypedDict(
+    "DescribeOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "Alias": str,
+        "State": str,
+        "DirectoryId": str,
+        "DirectoryType": str,
+        "DefaultMailDomain": str,
+        "CompletedDate": datetime,
+        "ErrorMessage": str,
+        "ARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeResourceRequestRequestTypeDef = TypedDict(
     "DescribeResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -596,14 +716,29 @@
     "DescribeUserRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "UserId": str,
     },
 )
 
+DescribeUserResponseTypeDef = TypedDict(
+    "DescribeUserResponseTypeDef",
+    {
+        "UserId": str,
+        "Name": str,
+        "Email": str,
+        "DisplayName": str,
+        "State": EntityStateType,
+        "UserRole": UserRoleType,
+        "EnabledDate": datetime,
+        "DisabledDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateDelegateFromResourceRequestRequestTypeDef = TypedDict(
     "DisassociateDelegateFromResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
         "EntityId": str,
     },
@@ -671,14 +806,23 @@
 class GetAccessControlEffectRequestRequestTypeDef(
     _RequiredGetAccessControlEffectRequestRequestTypeDef,
     _OptionalGetAccessControlEffectRequestRequestTypeDef,
 ):
     pass
 
 
+GetAccessControlEffectResponseTypeDef = TypedDict(
+    "GetAccessControlEffectResponseTypeDef",
+    {
+        "Effect": AccessControlRuleEffectType,
+        "MatchedRules": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDefaultRetentionPolicyRequestRequestTypeDef = TypedDict(
     "GetDefaultRetentionPolicyRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
@@ -720,14 +864,23 @@
     "GetMailboxDetailsRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "UserId": str,
     },
 )
 
+GetMailboxDetailsResponseTypeDef = TypedDict(
+    "GetMailboxDetailsResponseTypeDef",
+    {
+        "MailboxQuota": int,
+        "MailboxSize": float,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetMobileDeviceAccessEffectRequestRequestTypeDef = TypedDict(
     "_RequiredGetMobileDeviceAccessEffectRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalGetMobileDeviceAccessEffectRequestRequestTypeDef = TypedDict(
@@ -763,14 +916,27 @@
     {
         "OrganizationId": str,
         "UserId": str,
         "DeviceId": str,
     },
 )
 
+GetMobileDeviceAccessOverrideResponseTypeDef = TypedDict(
+    "GetMobileDeviceAccessOverrideResponseTypeDef",
+    {
+        "UserId": str,
+        "DeviceId": str,
+        "Effect": MobileDeviceAccessRuleEffectType,
+        "Description": str,
+        "DateCreated": datetime,
+        "DateModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupTypeDef = TypedDict(
     "GroupTypeDef",
     {
         "Id": str,
         "Email": str,
         "Name": str,
         "State": EntityStateType,
@@ -795,24 +961,37 @@
 ListAccessControlRulesRequestRequestTypeDef = TypedDict(
     "ListAccessControlRulesRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "OrganizationId": str,
+        "EntityId": str,
+    },
+)
+_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAliasesRequestListAliasesPaginateTypeDef(
+    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
+    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredListAliasesRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "EntityId": str,
     },
 )
@@ -828,14 +1007,45 @@
 
 class ListAliasesRequestRequestTypeDef(
     _RequiredListAliasesRequestRequestTypeDef, _OptionalListAliasesRequestRequestTypeDef
 ):
     pass
 
 
+ListAliasesResponseTypeDef = TypedDict(
+    "ListAliasesResponseTypeDef",
+    {
+        "Aliases": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
+    "_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
+    "_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef(
+    _RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
+    _OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAvailabilityConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailabilityConfigurationsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListAvailabilityConfigurationsRequestRequestTypeDef = TypedDict(
@@ -851,14 +1061,37 @@
 class ListAvailabilityConfigurationsRequestRequestTypeDef(
     _RequiredListAvailabilityConfigurationsRequestRequestTypeDef,
     _OptionalListAvailabilityConfigurationsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
+    "_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "GroupId": str,
+    },
+)
+_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
+    "_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGroupMembersRequestListGroupMembersPaginateTypeDef(
+    _RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef,
+    _OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembersRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "GroupId": str,
     },
 )
@@ -887,14 +1120,36 @@
         "State": EntityStateType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
     },
     total=False,
 )
 
+_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGroupsRequestListGroupsPaginateTypeDef(
+    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
+    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListGroupsRequestRequestTypeDef = TypedDict(
@@ -1002,14 +1257,37 @@
         "State": MailboxExportJobStateType,
         "StartTime": datetime,
         "EndTime": datetime,
     },
     total=False,
 )
 
+_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
+    "_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "EntityId": str,
+    },
+)
+_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
+    "_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef(
+    _RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
+    _OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMailboxPermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListMailboxPermissionsRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "EntityId": str,
     },
 )
@@ -1101,14 +1379,22 @@
         "NotDeviceUserAgents": List[str],
         "DateCreated": datetime,
         "DateModified": datetime,
     },
     total=False,
 )
 
+ListOrganizationsRequestListOrganizationsPaginateTypeDef = TypedDict(
+    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOrganizationsRequestRequestTypeDef = TypedDict(
     "ListOrganizationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1122,14 +1408,37 @@
         "DefaultMailDomain": str,
         "ErrorMessage": str,
         "State": str,
     },
     total=False,
 )
 
+_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
+    "_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "ResourceId": str,
+    },
+)
+_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
+    "_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef(
+    _RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
+    _OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourceDelegatesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceDelegatesRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -1146,14 +1455,36 @@
 class ListResourceDelegatesRequestRequestTypeDef(
     _RequiredListResourceDelegatesRequestRequestTypeDef,
     _OptionalListResourceDelegatesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -1197,14 +1528,36 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -1234,14 +1587,24 @@
         "UserRole": UserRoleType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
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
 _RequiredPutAccessControlRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutAccessControlRuleRequestRequestTypeDef",
     {
         "Name": str,
         "Effect": AccessControlRuleEffectType,
         "Description": str,
         "OrganizationId": str,
@@ -1359,14 +1722,25 @@
     {
         "OrganizationId": str,
         "UserId": str,
         "Password": str,
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
 _RequiredStartMailboxExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartMailboxExportJobRequestRequestTypeDef",
     {
         "ClientToken": str,
         "OrganizationId": str,
         "EntityId": str,
         "RoleArn": str,
@@ -1387,14 +1761,31 @@
 class StartMailboxExportJobRequestRequestTypeDef(
     _RequiredStartMailboxExportJobRequestRequestTypeDef,
     _OptionalStartMailboxExportJobRequestRequestTypeDef,
 ):
     pass
 
 
+StartMailboxExportJobResponseTypeDef = TypedDict(
+    "StartMailboxExportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestAvailabilityConfigurationResponseTypeDef = TypedDict(
+    "TestAvailabilityConfigurationResponseTypeDef",
+    {
+        "TestPassed": bool,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -1454,222 +1845,19 @@
     {
         "OrganizationId": str,
         "EntityId": str,
         "Email": str,
     },
 )
 
-AssumeImpersonationRoleResponseTypeDef = TypedDict(
-    "AssumeImpersonationRoleResponseTypeDef",
-    {
-        "Token": str,
-        "ExpiresIn": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGroupResponseTypeDef = TypedDict(
-    "CreateGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImpersonationRoleResponseTypeDef = TypedDict(
-    "CreateImpersonationRoleResponseTypeDef",
-    {
-        "ImpersonationRoleId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMobileDeviceAccessRuleResponseTypeDef = TypedDict(
-    "CreateMobileDeviceAccessRuleResponseTypeDef",
-    {
-        "MobileDeviceAccessRuleId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOrganizationResponseTypeDef = TypedDict(
-    "CreateOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourceResponseTypeDef = TypedDict(
-    "CreateResourceResponseTypeDef",
-    {
-        "ResourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "UserId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteOrganizationResponseTypeDef = TypedDict(
-    "DeleteOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEmailMonitoringConfigurationResponseTypeDef = TypedDict(
-    "DescribeEmailMonitoringConfigurationResponseTypeDef",
-    {
-        "RoleArn": str,
-        "LogGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupResponseTypeDef = TypedDict(
-    "DescribeGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "Name": str,
-        "Email": str,
-        "State": EntityStateType,
-        "EnabledDate": datetime,
-        "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeInboundDmarcSettingsResponseTypeDef = TypedDict(
-    "DescribeInboundDmarcSettingsResponseTypeDef",
-    {
-        "Enforced": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeMailboxExportJobResponseTypeDef = TypedDict(
-    "DescribeMailboxExportJobResponseTypeDef",
-    {
-        "EntityId": str,
-        "Description": str,
-        "RoleArn": str,
-        "KmsKeyArn": str,
-        "S3BucketName": str,
-        "S3Prefix": str,
-        "S3Path": str,
-        "EstimatedProgress": int,
-        "State": MailboxExportJobStateType,
-        "ErrorInfo": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationResponseTypeDef = TypedDict(
-    "DescribeOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "Alias": str,
-        "State": str,
-        "DirectoryId": str,
-        "DirectoryType": str,
-        "DefaultMailDomain": str,
-        "CompletedDate": datetime,
-        "ErrorMessage": str,
-        "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeUserResponseTypeDef = TypedDict(
-    "DescribeUserResponseTypeDef",
-    {
-        "UserId": str,
-        "Name": str,
-        "Email": str,
-        "DisplayName": str,
-        "State": EntityStateType,
-        "UserRole": UserRoleType,
-        "EnabledDate": datetime,
-        "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessControlEffectResponseTypeDef = TypedDict(
-    "GetAccessControlEffectResponseTypeDef",
-    {
-        "Effect": AccessControlRuleEffectType,
-        "MatchedRules": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMailboxDetailsResponseTypeDef = TypedDict(
-    "GetMailboxDetailsResponseTypeDef",
-    {
-        "MailboxQuota": int,
-        "MailboxSize": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMobileDeviceAccessOverrideResponseTypeDef = TypedDict(
-    "GetMobileDeviceAccessOverrideResponseTypeDef",
-    {
-        "UserId": str,
-        "DeviceId": str,
-        "Effect": MobileDeviceAccessRuleEffectType,
-        "Description": str,
-        "DateCreated": datetime,
-        "DateModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAccessControlRulesResponseTypeDef = TypedDict(
     "ListAccessControlRulesResponseTypeDef",
     {
         "Rules": List[AccessControlRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAliasesResponseTypeDef = TypedDict(
-    "ListAliasesResponseTypeDef",
-    {
-        "Aliases": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMailboxExportJobResponseTypeDef = TypedDict(
-    "StartMailboxExportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestAvailabilityConfigurationResponseTypeDef = TypedDict(
-    "TestAvailabilityConfigurationResponseTypeDef",
-    {
-        "TestPassed": bool,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AvailabilityConfigurationTypeDef = TypedDict(
     "AvailabilityConfigurationTypeDef",
     {
         "DomainName": str,
@@ -1689,15 +1877,15 @@
         "Email": str,
         "Name": str,
         "Type": ResourceTypeType,
         "BookingOptions": BookingOptionsTypeDef,
         "State": EntityStateType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1825,15 +2013,15 @@
         "ImpersonationRoleId": str,
         "Name": str,
         "Type": ImpersonationRoleTypeType,
         "Description": str,
         "Rules": List[ImpersonationRuleTypeDef],
         "DateCreated": datetime,
         "DateModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateImpersonationRoleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateImpersonationRoleRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1886,38 +2074,38 @@
 
 
 ListResourceDelegatesResponseTypeDef = TypedDict(
     "ListResourceDelegatesResponseTypeDef",
     {
         "Delegates": List[DelegateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMailDomainResponseTypeDef = TypedDict(
     "GetMailDomainResponseTypeDef",
     {
         "Records": List[DnsRecordTypeDef],
         "IsTestDomain": bool,
         "IsDefault": bool,
         "OwnershipVerificationStatus": DnsRecordVerificationStatusType,
         "DkimVerificationStatus": DnsRecordVerificationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDefaultRetentionPolicyResponseTypeDef = TypedDict(
     "GetDefaultRetentionPolicyResponseTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "FolderConfigurations": List[FolderConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRetentionPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutRetentionPolicyRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1944,309 +2132,121 @@
 
 GetImpersonationRoleEffectResponseTypeDef = TypedDict(
     "GetImpersonationRoleEffectResponseTypeDef",
     {
         "Type": ImpersonationRoleTypeType,
         "Effect": AccessEffectType,
         "MatchedRules": List[ImpersonationMatchedRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMobileDeviceAccessEffectResponseTypeDef = TypedDict(
     "GetMobileDeviceAccessEffectResponseTypeDef",
     {
         "Effect": MobileDeviceAccessRuleEffectType,
         "MatchedRules": List[MobileDeviceAccessMatchedRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImpersonationRolesResponseTypeDef = TypedDict(
     "ListImpersonationRolesResponseTypeDef",
     {
         "Roles": List[ImpersonationRoleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "EntityId": str,
-    },
-)
-_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAliasesRequestListAliasesPaginateTypeDef(
-    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
-    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
-    "_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
-    "_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef(
-    _RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-    _OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
-    "_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "GroupId": str,
-    },
-)
-_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
-    "_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGroupMembersRequestListGroupMembersPaginateTypeDef(
-    _RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef,
-    _OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGroupsRequestListGroupsPaginateTypeDef(
-    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
-    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
-    "_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "EntityId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
-    "_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef(
-    _RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-    _OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-):
-    pass
-
-
-ListOrganizationsRequestListOrganizationsPaginateTypeDef = TypedDict(
-    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
-    "_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "ResourceId": str,
-    },
-)
-_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
-    "_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef(
-    _RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-    _OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
-):
-    pass
-
 
 ListGroupMembersResponseTypeDef = TypedDict(
     "ListGroupMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailDomainsResponseTypeDef = TypedDict(
     "ListMailDomainsResponseTypeDef",
     {
         "MailDomains": List[MailDomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailboxExportJobsResponseTypeDef = TypedDict(
     "ListMailboxExportJobsResponseTypeDef",
     {
         "Jobs": List[MailboxExportJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailboxPermissionsResponseTypeDef = TypedDict(
     "ListMailboxPermissionsResponseTypeDef",
     {
         "Permissions": List[PermissionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileDeviceAccessOverridesResponseTypeDef = TypedDict(
     "ListMobileDeviceAccessOverridesResponseTypeDef",
     {
         "Overrides": List[MobileDeviceAccessOverrideTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileDeviceAccessRulesResponseTypeDef = TypedDict(
     "ListMobileDeviceAccessRulesResponseTypeDef",
     {
         "Rules": List[MobileDeviceAccessRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrganizationsResponseTypeDef = TypedDict(
     "ListOrganizationsResponseTypeDef",
     {
         "OrganizationSummaries": List[OrganizationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "Resources": List[ResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
@@ -2255,19 +2255,19 @@
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailabilityConfigurationsResponseTypeDef = TypedDict(
     "ListAvailabilityConfigurationsResponseTypeDef",
     {
         "AvailabilityConfigurations": List[AvailabilityConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail/type_defs.pyi` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -38,128 +38,137 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccessControlRuleTypeDef",
     "AssociateDelegateToResourceRequestRequestTypeDef",
     "AssociateMemberToGroupRequestRequestTypeDef",
     "AssumeImpersonationRoleRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssumeImpersonationRoleResponseTypeDef",
     "LambdaAvailabilityProviderTypeDef",
     "RedactedEwsAvailabilityProviderTypeDef",
     "BookingOptionsTypeDef",
     "CancelMailboxExportJobRequestRequestTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "EwsAvailabilityProviderTypeDef",
     "CreateGroupRequestRequestTypeDef",
+    "CreateGroupResponseTypeDef",
     "ImpersonationRuleTypeDef",
+    "CreateImpersonationRoleResponseTypeDef",
     "CreateMobileDeviceAccessRuleRequestRequestTypeDef",
+    "CreateMobileDeviceAccessRuleResponseTypeDef",
     "DomainTypeDef",
+    "CreateOrganizationResponseTypeDef",
     "CreateResourceRequestRequestTypeDef",
+    "CreateResourceResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "CreateUserResponseTypeDef",
     "DelegateTypeDef",
     "DeleteAccessControlRuleRequestRequestTypeDef",
     "DeleteAliasRequestRequestTypeDef",
     "DeleteAvailabilityConfigurationRequestRequestTypeDef",
     "DeleteEmailMonitoringConfigurationRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteImpersonationRoleRequestRequestTypeDef",
     "DeleteMailboxPermissionsRequestRequestTypeDef",
     "DeleteMobileDeviceAccessOverrideRequestRequestTypeDef",
     "DeleteMobileDeviceAccessRuleRequestRequestTypeDef",
     "DeleteOrganizationRequestRequestTypeDef",
+    "DeleteOrganizationResponseTypeDef",
     "DeleteResourceRequestRequestTypeDef",
     "DeleteRetentionPolicyRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DeregisterFromWorkMailRequestRequestTypeDef",
     "DeregisterMailDomainRequestRequestTypeDef",
     "DescribeEmailMonitoringConfigurationRequestRequestTypeDef",
+    "DescribeEmailMonitoringConfigurationResponseTypeDef",
     "DescribeGroupRequestRequestTypeDef",
+    "DescribeGroupResponseTypeDef",
     "DescribeInboundDmarcSettingsRequestRequestTypeDef",
+    "DescribeInboundDmarcSettingsResponseTypeDef",
     "DescribeMailboxExportJobRequestRequestTypeDef",
+    "DescribeMailboxExportJobResponseTypeDef",
     "DescribeOrganizationRequestRequestTypeDef",
+    "DescribeOrganizationResponseTypeDef",
     "DescribeResourceRequestRequestTypeDef",
     "DescribeUserRequestRequestTypeDef",
+    "DescribeUserResponseTypeDef",
     "DisassociateDelegateFromResourceRequestRequestTypeDef",
     "DisassociateMemberFromGroupRequestRequestTypeDef",
     "DnsRecordTypeDef",
     "FolderConfigurationTypeDef",
     "GetAccessControlEffectRequestRequestTypeDef",
+    "GetAccessControlEffectResponseTypeDef",
     "GetDefaultRetentionPolicyRequestRequestTypeDef",
     "GetImpersonationRoleEffectRequestRequestTypeDef",
     "ImpersonationMatchedRuleTypeDef",
     "GetImpersonationRoleRequestRequestTypeDef",
     "GetMailDomainRequestRequestTypeDef",
     "GetMailboxDetailsRequestRequestTypeDef",
+    "GetMailboxDetailsResponseTypeDef",
     "GetMobileDeviceAccessEffectRequestRequestTypeDef",
     "MobileDeviceAccessMatchedRuleTypeDef",
     "GetMobileDeviceAccessOverrideRequestRequestTypeDef",
+    "GetMobileDeviceAccessOverrideResponseTypeDef",
     "GroupTypeDef",
     "ImpersonationRoleTypeDef",
     "ListAccessControlRulesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListAliasesResponseTypeDef",
+    "ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
     "ListAvailabilityConfigurationsRequestRequestTypeDef",
+    "ListGroupMembersRequestListGroupMembersPaginateTypeDef",
     "ListGroupMembersRequestRequestTypeDef",
     "MemberTypeDef",
+    "ListGroupsRequestListGroupsPaginateTypeDef",
     "ListGroupsRequestRequestTypeDef",
     "ListImpersonationRolesRequestRequestTypeDef",
     "ListMailDomainsRequestRequestTypeDef",
     "MailDomainSummaryTypeDef",
     "ListMailboxExportJobsRequestRequestTypeDef",
     "MailboxExportJobTypeDef",
+    "ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
     "ListMailboxPermissionsRequestRequestTypeDef",
     "PermissionTypeDef",
     "ListMobileDeviceAccessOverridesRequestRequestTypeDef",
     "MobileDeviceAccessOverrideTypeDef",
     "ListMobileDeviceAccessRulesRequestRequestTypeDef",
     "MobileDeviceAccessRuleTypeDef",
+    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
     "ListOrganizationsRequestRequestTypeDef",
     "OrganizationSummaryTypeDef",
+    "ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
     "ListResourceDelegatesRequestRequestTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "UserTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccessControlRuleRequestRequestTypeDef",
     "PutEmailMonitoringConfigurationRequestRequestTypeDef",
     "PutInboundDmarcSettingsRequestRequestTypeDef",
     "PutMailboxPermissionsRequestRequestTypeDef",
     "PutMobileDeviceAccessOverrideRequestRequestTypeDef",
     "RegisterMailDomainRequestRequestTypeDef",
     "RegisterToWorkMailRequestRequestTypeDef",
     "ResetPasswordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartMailboxExportJobRequestRequestTypeDef",
+    "StartMailboxExportJobResponseTypeDef",
+    "TestAvailabilityConfigurationResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDefaultMailDomainRequestRequestTypeDef",
     "UpdateMailboxQuotaRequestRequestTypeDef",
     "UpdateMobileDeviceAccessRuleRequestRequestTypeDef",
     "UpdatePrimaryEmailAddressRequestRequestTypeDef",
-    "AssumeImpersonationRoleResponseTypeDef",
-    "CreateGroupResponseTypeDef",
-    "CreateImpersonationRoleResponseTypeDef",
-    "CreateMobileDeviceAccessRuleResponseTypeDef",
-    "CreateOrganizationResponseTypeDef",
-    "CreateResourceResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DeleteOrganizationResponseTypeDef",
-    "DescribeEmailMonitoringConfigurationResponseTypeDef",
-    "DescribeGroupResponseTypeDef",
-    "DescribeInboundDmarcSettingsResponseTypeDef",
-    "DescribeMailboxExportJobResponseTypeDef",
-    "DescribeOrganizationResponseTypeDef",
-    "DescribeUserResponseTypeDef",
-    "GetAccessControlEffectResponseTypeDef",
-    "GetMailboxDetailsResponseTypeDef",
-    "GetMobileDeviceAccessOverrideResponseTypeDef",
     "ListAccessControlRulesResponseTypeDef",
-    "ListAliasesResponseTypeDef",
-    "StartMailboxExportJobResponseTypeDef",
-    "TestAvailabilityConfigurationResponseTypeDef",
     "AvailabilityConfigurationTypeDef",
     "DescribeResourceResponseTypeDef",
     "UpdateResourceRequestRequestTypeDef",
     "CreateAvailabilityConfigurationRequestRequestTypeDef",
     "TestAvailabilityConfigurationRequestRequestTypeDef",
     "UpdateAvailabilityConfigurationRequestRequestTypeDef",
     "CreateImpersonationRoleRequestRequestTypeDef",
@@ -170,23 +179,14 @@
     "GetMailDomainResponseTypeDef",
     "GetDefaultRetentionPolicyResponseTypeDef",
     "PutRetentionPolicyRequestRequestTypeDef",
     "GetImpersonationRoleEffectResponseTypeDef",
     "GetMobileDeviceAccessEffectResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "ListImpersonationRolesResponseTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    "ListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    "ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
-    "ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListGroupMembersResponseTypeDef",
     "ListMailDomainsResponseTypeDef",
     "ListMailboxExportJobsResponseTypeDef",
     "ListMailboxPermissionsResponseTypeDef",
     "ListMobileDeviceAccessOverridesResponseTypeDef",
     "ListMobileDeviceAccessRulesResponseTypeDef",
     "ListOrganizationsResponseTypeDef",
@@ -239,22 +239,20 @@
     "AssumeImpersonationRoleRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ImpersonationRoleId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssumeImpersonationRoleResponseTypeDef = TypedDict(
+    "AssumeImpersonationRoleResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Token": str,
+        "ExpiresIn": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LambdaAvailabilityProviderTypeDef = TypedDict(
     "LambdaAvailabilityProviderTypeDef",
     {
         "LambdaArn": str,
@@ -311,14 +309,22 @@
     "CreateGroupRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
     },
 )
 
+CreateGroupResponseTypeDef = TypedDict(
+    "CreateGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImpersonationRuleTypeDef = TypedDict(
     "_RequiredImpersonationRuleTypeDef",
     {
         "ImpersonationRuleId": str,
         "Effect": AccessEffectType,
     },
 )
@@ -334,14 +340,22 @@
 )
 
 class ImpersonationRuleTypeDef(
     _RequiredImpersonationRuleTypeDef, _OptionalImpersonationRuleTypeDef
 ):
     pass
 
+CreateImpersonationRoleResponseTypeDef = TypedDict(
+    "CreateImpersonationRoleResponseTypeDef",
+    {
+        "ImpersonationRoleId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "Effect": MobileDeviceAccessRuleEffectType,
     },
@@ -365,42 +379,74 @@
 
 class CreateMobileDeviceAccessRuleRequestRequestTypeDef(
     _RequiredCreateMobileDeviceAccessRuleRequestRequestTypeDef,
     _OptionalCreateMobileDeviceAccessRuleRequestRequestTypeDef,
 ):
     pass
 
+CreateMobileDeviceAccessRuleResponseTypeDef = TypedDict(
+    "CreateMobileDeviceAccessRuleResponseTypeDef",
+    {
+        "MobileDeviceAccessRuleId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
         "DomainName": str,
         "HostedZoneId": str,
     },
     total=False,
 )
 
+CreateOrganizationResponseTypeDef = TypedDict(
+    "CreateOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateResourceRequestRequestTypeDef = TypedDict(
     "CreateResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "Type": ResourceTypeType,
     },
 )
 
+CreateResourceResponseTypeDef = TypedDict(
+    "CreateResourceResponseTypeDef",
+    {
+        "ResourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateUserRequestRequestTypeDef = TypedDict(
     "CreateUserRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "Name": str,
         "DisplayName": str,
         "Password": str,
     },
 )
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "UserId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DelegateTypeDef = TypedDict(
     "DelegateTypeDef",
     {
         "Id": str,
         "Type": MemberTypeType,
     },
 )
@@ -496,14 +542,23 @@
 
 class DeleteOrganizationRequestRequestTypeDef(
     _RequiredDeleteOrganizationRequestRequestTypeDef,
     _OptionalDeleteOrganizationRequestRequestTypeDef,
 ):
     pass
 
+DeleteOrganizationResponseTypeDef = TypedDict(
+    "DeleteOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourceRequestRequestTypeDef = TypedDict(
     "DeleteResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -543,44 +598,109 @@
 DescribeEmailMonitoringConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeEmailMonitoringConfigurationRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeEmailMonitoringConfigurationResponseTypeDef = TypedDict(
+    "DescribeEmailMonitoringConfigurationResponseTypeDef",
+    {
+        "RoleArn": str,
+        "LogGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGroupRequestRequestTypeDef = TypedDict(
     "DescribeGroupRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "GroupId": str,
     },
 )
 
+DescribeGroupResponseTypeDef = TypedDict(
+    "DescribeGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "Name": str,
+        "Email": str,
+        "State": EntityStateType,
+        "EnabledDate": datetime,
+        "DisabledDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeInboundDmarcSettingsRequestRequestTypeDef = TypedDict(
     "DescribeInboundDmarcSettingsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeInboundDmarcSettingsResponseTypeDef = TypedDict(
+    "DescribeInboundDmarcSettingsResponseTypeDef",
+    {
+        "Enforced": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeMailboxExportJobRequestRequestTypeDef = TypedDict(
     "DescribeMailboxExportJobRequestRequestTypeDef",
     {
         "JobId": str,
         "OrganizationId": str,
     },
 )
 
+DescribeMailboxExportJobResponseTypeDef = TypedDict(
+    "DescribeMailboxExportJobResponseTypeDef",
+    {
+        "EntityId": str,
+        "Description": str,
+        "RoleArn": str,
+        "KmsKeyArn": str,
+        "S3BucketName": str,
+        "S3Prefix": str,
+        "S3Path": str,
+        "EstimatedProgress": int,
+        "State": MailboxExportJobStateType,
+        "ErrorInfo": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeOrganizationRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
+DescribeOrganizationResponseTypeDef = TypedDict(
+    "DescribeOrganizationResponseTypeDef",
+    {
+        "OrganizationId": str,
+        "Alias": str,
+        "State": str,
+        "DirectoryId": str,
+        "DirectoryType": str,
+        "DefaultMailDomain": str,
+        "CompletedDate": datetime,
+        "ErrorMessage": str,
+        "ARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeResourceRequestRequestTypeDef = TypedDict(
     "DescribeResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -589,14 +709,29 @@
     "DescribeUserRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "UserId": str,
     },
 )
 
+DescribeUserResponseTypeDef = TypedDict(
+    "DescribeUserResponseTypeDef",
+    {
+        "UserId": str,
+        "Name": str,
+        "Email": str,
+        "DisplayName": str,
+        "State": EntityStateType,
+        "UserRole": UserRoleType,
+        "EnabledDate": datetime,
+        "DisabledDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateDelegateFromResourceRequestRequestTypeDef = TypedDict(
     "DisassociateDelegateFromResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
         "EntityId": str,
     },
@@ -660,14 +795,23 @@
 
 class GetAccessControlEffectRequestRequestTypeDef(
     _RequiredGetAccessControlEffectRequestRequestTypeDef,
     _OptionalGetAccessControlEffectRequestRequestTypeDef,
 ):
     pass
 
+GetAccessControlEffectResponseTypeDef = TypedDict(
+    "GetAccessControlEffectResponseTypeDef",
+    {
+        "Effect": AccessControlRuleEffectType,
+        "MatchedRules": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDefaultRetentionPolicyRequestRequestTypeDef = TypedDict(
     "GetDefaultRetentionPolicyRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
@@ -709,14 +853,23 @@
     "GetMailboxDetailsRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "UserId": str,
     },
 )
 
+GetMailboxDetailsResponseTypeDef = TypedDict(
+    "GetMailboxDetailsResponseTypeDef",
+    {
+        "MailboxQuota": int,
+        "MailboxSize": float,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetMobileDeviceAccessEffectRequestRequestTypeDef = TypedDict(
     "_RequiredGetMobileDeviceAccessEffectRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalGetMobileDeviceAccessEffectRequestRequestTypeDef = TypedDict(
@@ -750,14 +903,27 @@
     {
         "OrganizationId": str,
         "UserId": str,
         "DeviceId": str,
     },
 )
 
+GetMobileDeviceAccessOverrideResponseTypeDef = TypedDict(
+    "GetMobileDeviceAccessOverrideResponseTypeDef",
+    {
+        "UserId": str,
+        "DeviceId": str,
+        "Effect": MobileDeviceAccessRuleEffectType,
+        "Description": str,
+        "DateCreated": datetime,
+        "DateModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupTypeDef = TypedDict(
     "GroupTypeDef",
     {
         "Id": str,
         "Email": str,
         "Name": str,
         "State": EntityStateType,
@@ -782,24 +948,35 @@
 ListAccessControlRulesRequestRequestTypeDef = TypedDict(
     "ListAccessControlRulesRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "OrganizationId": str,
+        "EntityId": str,
+    },
+)
+_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAliasesRequestListAliasesPaginateTypeDef(
+    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
+    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredListAliasesRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "EntityId": str,
     },
 )
@@ -813,14 +990,43 @@
 )
 
 class ListAliasesRequestRequestTypeDef(
     _RequiredListAliasesRequestRequestTypeDef, _OptionalListAliasesRequestRequestTypeDef
 ):
     pass
 
+ListAliasesResponseTypeDef = TypedDict(
+    "ListAliasesResponseTypeDef",
+    {
+        "Aliases": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
+    "_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
+    "_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef(
+    _RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
+    _OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAvailabilityConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailabilityConfigurationsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListAvailabilityConfigurationsRequestRequestTypeDef = TypedDict(
@@ -834,14 +1040,35 @@
 
 class ListAvailabilityConfigurationsRequestRequestTypeDef(
     _RequiredListAvailabilityConfigurationsRequestRequestTypeDef,
     _OptionalListAvailabilityConfigurationsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
+    "_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "GroupId": str,
+    },
+)
+_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
+    "_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGroupMembersRequestListGroupMembersPaginateTypeDef(
+    _RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef,
+    _OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembersRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "GroupId": str,
     },
 )
@@ -868,14 +1095,34 @@
         "State": EntityStateType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
     },
     total=False,
 )
 
+_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGroupsRequestListGroupsPaginateTypeDef(
+    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
+    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListGroupsRequestRequestTypeDef = TypedDict(
@@ -975,14 +1222,35 @@
         "State": MailboxExportJobStateType,
         "StartTime": datetime,
         "EndTime": datetime,
     },
     total=False,
 )
 
+_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
+    "_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "EntityId": str,
+    },
+)
+_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
+    "_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef(
+    _RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
+    _OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListMailboxPermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListMailboxPermissionsRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "EntityId": str,
     },
 )
@@ -1070,14 +1338,22 @@
         "NotDeviceUserAgents": List[str],
         "DateCreated": datetime,
         "DateModified": datetime,
     },
     total=False,
 )
 
+ListOrganizationsRequestListOrganizationsPaginateTypeDef = TypedDict(
+    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOrganizationsRequestRequestTypeDef = TypedDict(
     "ListOrganizationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1091,14 +1367,35 @@
         "DefaultMailDomain": str,
         "ErrorMessage": str,
         "State": str,
     },
     total=False,
 )
 
+_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
+    "_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
+    {
+        "OrganizationId": str,
+        "ResourceId": str,
+    },
+)
+_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
+    "_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef(
+    _RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
+    _OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourceDelegatesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceDelegatesRequestRequestTypeDef",
     {
         "OrganizationId": str,
         "ResourceId": str,
     },
 )
@@ -1113,14 +1410,34 @@
 
 class ListResourceDelegatesRequestRequestTypeDef(
     _RequiredListResourceDelegatesRequestRequestTypeDef,
     _OptionalListResourceDelegatesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -1162,14 +1479,34 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -1197,14 +1534,24 @@
         "UserRole": UserRoleType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
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
 _RequiredPutAccessControlRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutAccessControlRuleRequestRequestTypeDef",
     {
         "Name": str,
         "Effect": AccessControlRuleEffectType,
         "Description": str,
         "OrganizationId": str,
@@ -1316,14 +1663,25 @@
     {
         "OrganizationId": str,
         "UserId": str,
         "Password": str,
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
 _RequiredStartMailboxExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartMailboxExportJobRequestRequestTypeDef",
     {
         "ClientToken": str,
         "OrganizationId": str,
         "EntityId": str,
         "RoleArn": str,
@@ -1342,14 +1700,31 @@
 
 class StartMailboxExportJobRequestRequestTypeDef(
     _RequiredStartMailboxExportJobRequestRequestTypeDef,
     _OptionalStartMailboxExportJobRequestRequestTypeDef,
 ):
     pass
 
+StartMailboxExportJobResponseTypeDef = TypedDict(
+    "StartMailboxExportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestAvailabilityConfigurationResponseTypeDef = TypedDict(
+    "TestAvailabilityConfigurationResponseTypeDef",
+    {
+        "TestPassed": bool,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -1407,222 +1782,19 @@
     {
         "OrganizationId": str,
         "EntityId": str,
         "Email": str,
     },
 )
 
-AssumeImpersonationRoleResponseTypeDef = TypedDict(
-    "AssumeImpersonationRoleResponseTypeDef",
-    {
-        "Token": str,
-        "ExpiresIn": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGroupResponseTypeDef = TypedDict(
-    "CreateGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImpersonationRoleResponseTypeDef = TypedDict(
-    "CreateImpersonationRoleResponseTypeDef",
-    {
-        "ImpersonationRoleId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMobileDeviceAccessRuleResponseTypeDef = TypedDict(
-    "CreateMobileDeviceAccessRuleResponseTypeDef",
-    {
-        "MobileDeviceAccessRuleId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOrganizationResponseTypeDef = TypedDict(
-    "CreateOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourceResponseTypeDef = TypedDict(
-    "CreateResourceResponseTypeDef",
-    {
-        "ResourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "UserId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteOrganizationResponseTypeDef = TypedDict(
-    "DeleteOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEmailMonitoringConfigurationResponseTypeDef = TypedDict(
-    "DescribeEmailMonitoringConfigurationResponseTypeDef",
-    {
-        "RoleArn": str,
-        "LogGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupResponseTypeDef = TypedDict(
-    "DescribeGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "Name": str,
-        "Email": str,
-        "State": EntityStateType,
-        "EnabledDate": datetime,
-        "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeInboundDmarcSettingsResponseTypeDef = TypedDict(
-    "DescribeInboundDmarcSettingsResponseTypeDef",
-    {
-        "Enforced": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeMailboxExportJobResponseTypeDef = TypedDict(
-    "DescribeMailboxExportJobResponseTypeDef",
-    {
-        "EntityId": str,
-        "Description": str,
-        "RoleArn": str,
-        "KmsKeyArn": str,
-        "S3BucketName": str,
-        "S3Prefix": str,
-        "S3Path": str,
-        "EstimatedProgress": int,
-        "State": MailboxExportJobStateType,
-        "ErrorInfo": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationResponseTypeDef = TypedDict(
-    "DescribeOrganizationResponseTypeDef",
-    {
-        "OrganizationId": str,
-        "Alias": str,
-        "State": str,
-        "DirectoryId": str,
-        "DirectoryType": str,
-        "DefaultMailDomain": str,
-        "CompletedDate": datetime,
-        "ErrorMessage": str,
-        "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeUserResponseTypeDef = TypedDict(
-    "DescribeUserResponseTypeDef",
-    {
-        "UserId": str,
-        "Name": str,
-        "Email": str,
-        "DisplayName": str,
-        "State": EntityStateType,
-        "UserRole": UserRoleType,
-        "EnabledDate": datetime,
-        "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessControlEffectResponseTypeDef = TypedDict(
-    "GetAccessControlEffectResponseTypeDef",
-    {
-        "Effect": AccessControlRuleEffectType,
-        "MatchedRules": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMailboxDetailsResponseTypeDef = TypedDict(
-    "GetMailboxDetailsResponseTypeDef",
-    {
-        "MailboxQuota": int,
-        "MailboxSize": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMobileDeviceAccessOverrideResponseTypeDef = TypedDict(
-    "GetMobileDeviceAccessOverrideResponseTypeDef",
-    {
-        "UserId": str,
-        "DeviceId": str,
-        "Effect": MobileDeviceAccessRuleEffectType,
-        "Description": str,
-        "DateCreated": datetime,
-        "DateModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAccessControlRulesResponseTypeDef = TypedDict(
     "ListAccessControlRulesResponseTypeDef",
     {
         "Rules": List[AccessControlRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAliasesResponseTypeDef = TypedDict(
-    "ListAliasesResponseTypeDef",
-    {
-        "Aliases": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMailboxExportJobResponseTypeDef = TypedDict(
-    "StartMailboxExportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestAvailabilityConfigurationResponseTypeDef = TypedDict(
-    "TestAvailabilityConfigurationResponseTypeDef",
-    {
-        "TestPassed": bool,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AvailabilityConfigurationTypeDef = TypedDict(
     "AvailabilityConfigurationTypeDef",
     {
         "DomainName": str,
@@ -1642,15 +1814,15 @@
         "Email": str,
         "Name": str,
         "Type": ResourceTypeType,
         "BookingOptions": BookingOptionsTypeDef,
         "State": EntityStateType,
         "EnabledDate": datetime,
         "DisabledDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1768,15 +1940,15 @@
         "ImpersonationRoleId": str,
         "Name": str,
         "Type": ImpersonationRoleTypeType,
         "Description": str,
         "Rules": List[ImpersonationRuleTypeDef],
         "DateCreated": datetime,
         "DateModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateImpersonationRoleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateImpersonationRoleRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1825,38 +1997,38 @@
     pass
 
 ListResourceDelegatesResponseTypeDef = TypedDict(
     "ListResourceDelegatesResponseTypeDef",
     {
         "Delegates": List[DelegateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMailDomainResponseTypeDef = TypedDict(
     "GetMailDomainResponseTypeDef",
     {
         "Records": List[DnsRecordTypeDef],
         "IsTestDomain": bool,
         "IsDefault": bool,
         "OwnershipVerificationStatus": DnsRecordVerificationStatusType,
         "DkimVerificationStatus": DnsRecordVerificationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDefaultRetentionPolicyResponseTypeDef = TypedDict(
     "GetDefaultRetentionPolicyResponseTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "FolderConfigurations": List[FolderConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRetentionPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutRetentionPolicyRequestRequestTypeDef",
     {
         "OrganizationId": str,
@@ -1881,293 +2053,121 @@
 
 GetImpersonationRoleEffectResponseTypeDef = TypedDict(
     "GetImpersonationRoleEffectResponseTypeDef",
     {
         "Type": ImpersonationRoleTypeType,
         "Effect": AccessEffectType,
         "MatchedRules": List[ImpersonationMatchedRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMobileDeviceAccessEffectResponseTypeDef = TypedDict(
     "GetMobileDeviceAccessEffectResponseTypeDef",
     {
         "Effect": MobileDeviceAccessRuleEffectType,
         "MatchedRules": List[MobileDeviceAccessMatchedRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImpersonationRolesResponseTypeDef = TypedDict(
     "ListImpersonationRolesResponseTypeDef",
     {
         "Roles": List[ImpersonationRoleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "EntityId": str,
-    },
-)
-_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAliasesRequestListAliasesPaginateTypeDef(
-    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
-    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
-    "_RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef = TypedDict(
-    "_OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef(
-    _RequiredListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-    _OptionalListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-):
-    pass
-
-_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
-    "_RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "GroupId": str,
-    },
-)
-_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef = TypedDict(
-    "_OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGroupMembersRequestListGroupMembersPaginateTypeDef(
-    _RequiredListGroupMembersRequestListGroupMembersPaginateTypeDef,
-    _OptionalListGroupMembersRequestListGroupMembersPaginateTypeDef,
-):
-    pass
-
-_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "OrganizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGroupsRequestListGroupsPaginateTypeDef(
-    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
-    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
-    "_RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "EntityId": str,
-    },
-)
-_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef = TypedDict(
-    "_OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef(
-    _RequiredListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-    _OptionalListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-):
-    pass
-
-ListOrganizationsRequestListOrganizationsPaginateTypeDef = TypedDict(
-    "ListOrganizationsRequestListOrganizationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
-    "_RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-        "ResourceId": str,
-    },
-)
-_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef = TypedDict(
-    "_OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef(
-    _RequiredListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-    _OptionalListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-):
-    pass
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
-):
-    pass
 
 ListGroupMembersResponseTypeDef = TypedDict(
     "ListGroupMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailDomainsResponseTypeDef = TypedDict(
     "ListMailDomainsResponseTypeDef",
     {
         "MailDomains": List[MailDomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailboxExportJobsResponseTypeDef = TypedDict(
     "ListMailboxExportJobsResponseTypeDef",
     {
         "Jobs": List[MailboxExportJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMailboxPermissionsResponseTypeDef = TypedDict(
     "ListMailboxPermissionsResponseTypeDef",
     {
         "Permissions": List[PermissionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileDeviceAccessOverridesResponseTypeDef = TypedDict(
     "ListMobileDeviceAccessOverridesResponseTypeDef",
     {
         "Overrides": List[MobileDeviceAccessOverrideTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMobileDeviceAccessRulesResponseTypeDef = TypedDict(
     "ListMobileDeviceAccessRulesResponseTypeDef",
     {
         "Rules": List[MobileDeviceAccessRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrganizationsResponseTypeDef = TypedDict(
     "ListOrganizationsResponseTypeDef",
     {
         "OrganizationSummaries": List[OrganizationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "Resources": List[ResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
@@ -2176,19 +2176,19 @@
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailabilityConfigurationsResponseTypeDef = TypedDict(
     "ListAvailabilityConfigurationsResponseTypeDef",
     {
         "AvailabilityConfigurations": List[AvailabilityConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/PKG-INFO` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workmail
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkMail 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkMail 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workmail"></a>
 
 # types-aiobotocore-workmail
 
 [![PyPI - types-aiobotocore-workmail](https://img.shields.io/pypi/v/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmail?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
+[aiobotocore.WorkMail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmail.html#WorkMail)
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
 [types-aiobotocore-workmail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -367,128 +367,137 @@
 
 ```python
 from types_aiobotocore_workmail.type_defs import (
     AccessControlRuleTypeDef,
     AssociateDelegateToResourceRequestRequestTypeDef,
     AssociateMemberToGroupRequestRequestTypeDef,
     AssumeImpersonationRoleRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssumeImpersonationRoleResponseTypeDef,
     LambdaAvailabilityProviderTypeDef,
     RedactedEwsAvailabilityProviderTypeDef,
     BookingOptionsTypeDef,
     CancelMailboxExportJobRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     EwsAvailabilityProviderTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     ImpersonationRuleTypeDef,
+    CreateImpersonationRoleResponseTypeDef,
     CreateMobileDeviceAccessRuleRequestRequestTypeDef,
+    CreateMobileDeviceAccessRuleResponseTypeDef,
     DomainTypeDef,
+    CreateOrganizationResponseTypeDef,
     CreateResourceRequestRequestTypeDef,
+    CreateResourceResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     DelegateTypeDef,
     DeleteAccessControlRuleRequestRequestTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteAvailabilityConfigurationRequestRequestTypeDef,
     DeleteEmailMonitoringConfigurationRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteImpersonationRoleRequestRequestTypeDef,
     DeleteMailboxPermissionsRequestRequestTypeDef,
     DeleteMobileDeviceAccessOverrideRequestRequestTypeDef,
     DeleteMobileDeviceAccessRuleRequestRequestTypeDef,
     DeleteOrganizationRequestRequestTypeDef,
+    DeleteOrganizationResponseTypeDef,
     DeleteResourceRequestRequestTypeDef,
     DeleteRetentionPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeregisterFromWorkMailRequestRequestTypeDef,
     DeregisterMailDomainRequestRequestTypeDef,
     DescribeEmailMonitoringConfigurationRequestRequestTypeDef,
+    DescribeEmailMonitoringConfigurationResponseTypeDef,
     DescribeGroupRequestRequestTypeDef,
+    DescribeGroupResponseTypeDef,
     DescribeInboundDmarcSettingsRequestRequestTypeDef,
+    DescribeInboundDmarcSettingsResponseTypeDef,
     DescribeMailboxExportJobRequestRequestTypeDef,
+    DescribeMailboxExportJobResponseTypeDef,
     DescribeOrganizationRequestRequestTypeDef,
+    DescribeOrganizationResponseTypeDef,
     DescribeResourceRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
+    DescribeUserResponseTypeDef,
     DisassociateDelegateFromResourceRequestRequestTypeDef,
     DisassociateMemberFromGroupRequestRequestTypeDef,
     DnsRecordTypeDef,
     FolderConfigurationTypeDef,
     GetAccessControlEffectRequestRequestTypeDef,
+    GetAccessControlEffectResponseTypeDef,
     GetDefaultRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectRequestRequestTypeDef,
     ImpersonationMatchedRuleTypeDef,
     GetImpersonationRoleRequestRequestTypeDef,
     GetMailDomainRequestRequestTypeDef,
     GetMailboxDetailsRequestRequestTypeDef,
+    GetMailboxDetailsResponseTypeDef,
     GetMobileDeviceAccessEffectRequestRequestTypeDef,
     MobileDeviceAccessMatchedRuleTypeDef,
     GetMobileDeviceAccessOverrideRequestRequestTypeDef,
+    GetMobileDeviceAccessOverrideResponseTypeDef,
     GroupTypeDef,
     ImpersonationRoleTypeDef,
     ListAccessControlRulesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListAliasesResponseTypeDef,
+    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
     ListAvailabilityConfigurationsRequestRequestTypeDef,
+    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
     ListGroupMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListImpersonationRolesRequestRequestTypeDef,
     ListMailDomainsRequestRequestTypeDef,
     MailDomainSummaryTypeDef,
     ListMailboxExportJobsRequestRequestTypeDef,
     MailboxExportJobTypeDef,
+    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
     ListMailboxPermissionsRequestRequestTypeDef,
     PermissionTypeDef,
     ListMobileDeviceAccessOverridesRequestRequestTypeDef,
     MobileDeviceAccessOverrideTypeDef,
     ListMobileDeviceAccessRulesRequestRequestTypeDef,
     MobileDeviceAccessRuleTypeDef,
+    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
     ListOrganizationsRequestRequestTypeDef,
     OrganizationSummaryTypeDef,
+    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
     ListResourceDelegatesRequestRequestTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     PutAccessControlRuleRequestRequestTypeDef,
     PutEmailMonitoringConfigurationRequestRequestTypeDef,
     PutInboundDmarcSettingsRequestRequestTypeDef,
     PutMailboxPermissionsRequestRequestTypeDef,
     PutMobileDeviceAccessOverrideRequestRequestTypeDef,
     RegisterMailDomainRequestRequestTypeDef,
     RegisterToWorkMailRequestRequestTypeDef,
     ResetPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMailboxExportJobRequestRequestTypeDef,
+    StartMailboxExportJobResponseTypeDef,
+    TestAvailabilityConfigurationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDefaultMailDomainRequestRequestTypeDef,
     UpdateMailboxQuotaRequestRequestTypeDef,
     UpdateMobileDeviceAccessRuleRequestRequestTypeDef,
     UpdatePrimaryEmailAddressRequestRequestTypeDef,
-    AssumeImpersonationRoleResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateImpersonationRoleResponseTypeDef,
-    CreateMobileDeviceAccessRuleResponseTypeDef,
-    CreateOrganizationResponseTypeDef,
-    CreateResourceResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteOrganizationResponseTypeDef,
-    DescribeEmailMonitoringConfigurationResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    DescribeInboundDmarcSettingsResponseTypeDef,
-    DescribeMailboxExportJobResponseTypeDef,
-    DescribeOrganizationResponseTypeDef,
-    DescribeUserResponseTypeDef,
-    GetAccessControlEffectResponseTypeDef,
-    GetMailboxDetailsResponseTypeDef,
-    GetMobileDeviceAccessOverrideResponseTypeDef,
     ListAccessControlRulesResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    StartMailboxExportJobResponseTypeDef,
-    TestAvailabilityConfigurationResponseTypeDef,
     AvailabilityConfigurationTypeDef,
     DescribeResourceResponseTypeDef,
     UpdateResourceRequestRequestTypeDef,
     CreateAvailabilityConfigurationRequestRequestTypeDef,
     TestAvailabilityConfigurationRequestRequestTypeDef,
     UpdateAvailabilityConfigurationRequestRequestTypeDef,
     CreateImpersonationRoleRequestRequestTypeDef,
@@ -499,23 +508,14 @@
     GetMailDomainResponseTypeDef,
     GetDefaultRetentionPolicyResponseTypeDef,
     PutRetentionPolicyRequestRequestTypeDef,
     GetImpersonationRoleEffectResponseTypeDef,
     GetMobileDeviceAccessEffectResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListImpersonationRolesResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListAvailabilityConfigurationsRequestListAvailabilityConfigurationsPaginateTypeDef,
-    ListGroupMembersRequestListGroupMembersPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListMailboxPermissionsRequestListMailboxPermissionsPaginateTypeDef,
-    ListOrganizationsRequestListOrganizationsPaginateTypeDef,
-    ListResourceDelegatesRequestListResourceDelegatesPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListGroupMembersResponseTypeDef,
     ListMailDomainsResponseTypeDef,
     ListMailboxExportJobsResponseTypeDef,
     ListMailboxPermissionsResponseTypeDef,
     ListMobileDeviceAccessOverridesResponseTypeDef,
     ListMobileDeviceAccessRulesResponseTypeDef,
     ListOrganizationsResponseTypeDef,
@@ -534,43 +534,43 @@
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

### Comparing `types-aiobotocore-workmail-2.5.0.post1/types_aiobotocore_workmail.egg-info/SOURCES.txt` & `types-aiobotocore-workmail-2.5.1/types_aiobotocore_workmail.egg-info/SOURCES.txt`

 * *Files identical despite different names*

