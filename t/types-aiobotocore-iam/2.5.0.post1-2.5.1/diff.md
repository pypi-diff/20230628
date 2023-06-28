# Comparing `tmp/types-aiobotocore-iam-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iam-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iam-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:43 2023, max compression
+gzip compressed data, was "types-aiobotocore-iam-2.5.1.tar", last modified: Wed Jun 28 01:43:35 2023, max compression
```

## Comparing `types-aiobotocore-iam-2.5.0.post1.tar` & `types-aiobotocore-iam-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:43.827268 types-aiobotocore-iam-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    42168 2023-03-11 12:26:43.827268 types-aiobotocore-iam-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    40613 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:43.827268 types-aiobotocore-iam-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:43.815268 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/
--rw-r--r--   0 runner    (1001) docker     (123)     7145 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7144 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   115094 2023-03-11 12:15:40.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   114896 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14335 2023-03-11 12:15:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14333 2023-03-11 12:15:42.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    32277 2023-03-11 12:15:42.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    32247 2023-03-11 12:15:42.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   155097 2023-03-11 12:15:41.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)   154716 2023-03-11 12:15:40.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)   144175 2023-03-11 12:15:45.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   143976 2023-03-11 12:15:44.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:39.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     4212 2023-03-11 12:15:42.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4208 2023-03-11 12:15:42.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:43.827268 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    42168 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      887 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:43.000000 types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.058147 types-aiobotocore-iam-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    43100 2023-06-28 01:43:35.050147 types-aiobotocore-iam-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    41551 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:35.058147 types-aiobotocore-iam-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.050147 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/
+-rw-r--r--   0 runner    (1001) docker     (123)     8755 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8754 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   119024 2023-06-28 01:32:16.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   118818 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15545 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15543 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    40152 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40116 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   154972 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)   154591 2023-06-28 01:32:17.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)   146148 2023-06-28 01:32:22.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   145933 2023-06-28 01:32:20.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:15.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4212 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4208 2023-06-28 01:32:18.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.050147 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    43100 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      887 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:34.000000 types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/LICENSE` & `types-aiobotocore-iam-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iam-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iam-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-iam
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IAM 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore iam type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-iam"></a>
 
 # types-aiobotocore-iam
 
 [![PyPI - types-aiobotocore-iam](https://img.shields.io/pypi/v/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iam?color=blue)](https://pypistats.org/packages/types-aiobotocore-iam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
+[aiobotocore.IAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
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
 [types-aiobotocore-iam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,22 +253,29 @@
     ListAttachedGroupPoliciesPaginator,
     ListAttachedRolePoliciesPaginator,
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsPaginator,
     ListGroupsForUserPaginator,
+    ListInstanceProfileTagsPaginator,
     ListInstanceProfilesPaginator,
     ListInstanceProfilesForRolePaginator,
+    ListMFADeviceTagsPaginator,
     ListMFADevicesPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
+    ListRoleTagsPaginator,
     ListRolesPaginator,
+    ListSAMLProviderTagsPaginator,
     ListSSHPublicKeysPaginator,
+    ListServerCertificateTagsPaginator,
     ListServerCertificatesPaginator,
     ListSigningCertificatesPaginator,
     ListUserPoliciesPaginator,
     ListUserTagsPaginator,
     ListUsersPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -337,32 +311,49 @@
     list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator(
         "list_group_policies"
     )
     list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
     list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator(
         "list_groups_for_user"
     )
+    list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator(
+        "list_instance_profile_tags"
+    )
     list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator(
         "list_instance_profiles"
     )
     list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = (
         client.get_paginator("list_instance_profiles_for_role")
     )
+    list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator(
+        "list_mfa_device_tags"
+    )
     list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+    list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = (
+        client.get_paginator("list_open_id_connect_provider_tags")
+    )
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+    list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
     list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator(
         "list_policy_versions"
     )
     list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator(
         "list_role_policies"
     )
+    list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
     list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+    list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator(
+        "list_saml_provider_tags"
+    )
     list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator(
         "list_ssh_public_keys"
     )
+    list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = (
+        client.get_paginator("list_server_certificate_tags")
+    )
     list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator(
         "list_server_certificates"
     )
     list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator(
         "list_signing_certificates"
     )
     list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator(
@@ -559,22 +550,29 @@
     ListAttachedGroupPoliciesPaginatorName,
     ListAttachedRolePoliciesPaginatorName,
     ListAttachedUserPoliciesPaginatorName,
     ListEntitiesForPolicyPaginatorName,
     ListGroupPoliciesPaginatorName,
     ListGroupsForUserPaginatorName,
     ListGroupsPaginatorName,
+    ListInstanceProfileTagsPaginatorName,
     ListInstanceProfilesForRolePaginatorName,
     ListInstanceProfilesPaginatorName,
+    ListMFADeviceTagsPaginatorName,
     ListMFADevicesPaginatorName,
+    ListOpenIDConnectProviderTagsPaginatorName,
     ListPoliciesPaginatorName,
+    ListPolicyTagsPaginatorName,
     ListPolicyVersionsPaginatorName,
     ListRolePoliciesPaginatorName,
+    ListRoleTagsPaginatorName,
     ListRolesPaginatorName,
+    ListSAMLProviderTagsPaginatorName,
     ListSSHPublicKeysPaginatorName,
+    ListServerCertificateTagsPaginatorName,
     ListServerCertificatesPaginatorName,
     ListSigningCertificatesPaginatorName,
     ListUserPoliciesPaginatorName,
     ListUserTagsPaginatorName,
     ListUsersPaginatorName,
     ListVirtualMFADevicesPaginatorName,
     PermissionsBoundaryAttachmentTypeType,
@@ -634,15 +632,15 @@
     AttachGroupPolicyRequestRequestTypeDef,
     AttachRolePolicyRequestPolicyAttachRoleTypeDef,
     AttachRolePolicyRequestRequestTypeDef,
     AttachRolePolicyRequestRoleAttachPolicyTypeDef,
     AttachUserPolicyRequestPolicyAttachUserTypeDef,
     AttachUserPolicyRequestRequestTypeDef,
     AttachUserPolicyRequestUserAttachPolicyTypeDef,
-    ResponseMetadataTypeDef,
+    AttachedPermissionsBoundaryResponseMetadataTypeDef,
     AttachedPermissionsBoundaryTypeDef,
     AttachedPolicyTypeDef,
     ChangePasswordRequestRequestTypeDef,
     ChangePasswordRequestServiceResourceChangePasswordTypeDef,
     ContextEntryTypeDef,
     CreateAccessKeyRequestRequestTypeDef,
     CreateAccountAliasRequestRequestTypeDef,
@@ -675,14 +673,15 @@
     DeleteRolePermissionsBoundaryRequestRequestTypeDef,
     DeleteRolePolicyRequestRequestTypeDef,
     DeleteRoleRequestRequestTypeDef,
     DeleteSAMLProviderRequestRequestTypeDef,
     DeleteSSHPublicKeyRequestRequestTypeDef,
     DeleteServerCertificateRequestRequestTypeDef,
     DeleteServiceLinkedRoleRequestRequestTypeDef,
+    DeleteServiceLinkedRoleResponseTypeDef,
     DeleteServiceSpecificCredentialRequestRequestTypeDef,
     DeleteSigningCertificateRequestRequestTypeDef,
     DeleteUserPermissionsBoundaryRequestRequestTypeDef,
     DeleteUserPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeleteVirtualMFADeviceRequestRequestTypeDef,
     RoleUsageTypeTypeDef,
@@ -691,94 +690,141 @@
     DetachGroupPolicyRequestRequestTypeDef,
     DetachRolePolicyRequestPolicyDetachRoleTypeDef,
     DetachRolePolicyRequestRequestTypeDef,
     DetachRolePolicyRequestRoleDetachPolicyTypeDef,
     DetachUserPolicyRequestPolicyDetachUserTypeDef,
     DetachUserPolicyRequestRequestTypeDef,
     DetachUserPolicyRequestUserDetachPolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMFADeviceRequestMfaDeviceAssociateTypeDef,
     EnableMFADeviceRequestRequestTypeDef,
     EnableMFADeviceRequestUserEnableMfaTypeDef,
     EntityInfoTypeDef,
     ErrorDetailsTypeDef,
     OrganizationsDecisionDetailTypeDef,
     PermissionsBoundaryDecisionDetailTypeDef,
+    GenerateCredentialReportResponseTypeDef,
     GenerateOrganizationsAccessReportRequestRequestTypeDef,
+    GenerateOrganizationsAccessReportResponseTypeDef,
     GenerateServiceLastAccessedDetailsRequestRequestTypeDef,
+    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
     GetAccountAuthorizationDetailsRequestRequestTypeDef,
     PasswordPolicyTypeDef,
+    GetAccountSummaryResponseTypeDef,
     GetContextKeysForCustomPolicyRequestRequestTypeDef,
+    GetContextKeysForPolicyResponseTypeDef,
     GetContextKeysForPrincipalPolicyRequestRequestTypeDef,
+    GetCredentialReportResponseTypeDef,
     GetGroupPolicyRequestRequestTypeDef,
+    GetGroupPolicyResponseTypeDef,
+    GetGroupRequestGetGroupPaginateTypeDef,
     GetGroupRequestRequestTypeDef,
     WaiterConfigTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetLoginProfileRequestRequestTypeDef,
+    GetMFADeviceRequestRequestTypeDef,
+    GetMFADeviceResponseTypeDef,
     GetOpenIDConnectProviderRequestRequestTypeDef,
     GetOrganizationsAccessReportRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
     GetRolePolicyRequestRequestTypeDef,
+    GetRolePolicyResponseTypeDef,
     GetRoleRequestRequestTypeDef,
     GetSAMLProviderRequestRequestTypeDef,
     GetSSHPublicKeyRequestRequestTypeDef,
     SSHPublicKeyTypeDef,
     GetServerCertificateRequestRequestTypeDef,
     GetServiceLastAccessedDetailsRequestRequestTypeDef,
     GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef,
     GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef,
     GetUserPolicyRequestRequestTypeDef,
+    GetUserPolicyResponseTypeDef,
     GetUserRequestRequestTypeDef,
     PolicyDetailTypeDef,
-    GroupPolicyRequestTypeDef,
+    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
     ListAccessKeysRequestRequestTypeDef,
+    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
     ListAccountAliasesRequestRequestTypeDef,
+    ListAccountAliasesResponseTypeDef,
+    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
     ListAttachedGroupPoliciesRequestRequestTypeDef,
+    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
     ListAttachedRolePoliciesRequestRequestTypeDef,
+    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
     ListAttachedUserPoliciesRequestRequestTypeDef,
+    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
     ListEntitiesForPolicyRequestRequestTypeDef,
     PolicyGroupTypeDef,
     PolicyRoleTypeDef,
     PolicyUserTypeDef,
+    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
     ListGroupPoliciesRequestRequestTypeDef,
+    ListGroupPoliciesResponseTypeDef,
+    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
     ListGroupsForUserRequestRequestTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
+    ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
     ListInstanceProfileTagsRequestRequestTypeDef,
+    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
     ListInstanceProfilesForRoleRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
     ListMFADeviceTagsRequestRequestTypeDef,
+    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
     ListMFADevicesRequestRequestTypeDef,
     MFADeviceTypeDef,
+    ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
     ListOpenIDConnectProviderTagsRequestRequestTypeDef,
     OpenIDConnectProviderListEntryTypeDef,
     PolicyGrantingServiceAccessTypeDef,
     ListPoliciesGrantingServiceAccessRequestRequestTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
     ListPolicyTagsRequestRequestTypeDef,
+    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
+    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
     ListRolePoliciesRequestRequestTypeDef,
+    ListRolePoliciesResponseTypeDef,
+    ListRoleTagsRequestListRoleTagsPaginateTypeDef,
     ListRoleTagsRequestRequestTypeDef,
+    ListRolesRequestListRolesPaginateTypeDef,
     ListRolesRequestRequestTypeDef,
+    ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
     ListSAMLProviderTagsRequestRequestTypeDef,
     SAMLProviderListEntryTypeDef,
+    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
     ListSSHPublicKeysRequestRequestTypeDef,
     SSHPublicKeyMetadataTypeDef,
+    ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
     ListServerCertificateTagsRequestRequestTypeDef,
+    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
     ListServerCertificatesRequestRequestTypeDef,
     ServerCertificateMetadataTypeDef,
     ListServiceSpecificCredentialsRequestRequestTypeDef,
     ServiceSpecificCredentialMetadataTypeDef,
+    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
     ListSigningCertificatesRequestRequestTypeDef,
     SigningCertificateTypeDef,
+    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
     ListUserPoliciesRequestRequestTypeDef,
+    ListUserPoliciesResponseTypeDef,
+    ListUserTagsRequestListUserTagsPaginateTypeDef,
     ListUserTagsRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
+    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
     ListVirtualMFADevicesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PositionTypeDef,
     PutGroupPolicyRequestGroupCreatePolicyTypeDef,
     PutGroupPolicyRequestGroupPolicyPutTypeDef,
     PutGroupPolicyRequestRequestTypeDef,
     PutRolePermissionsBoundaryRequestRequestTypeDef,
     PutRolePolicyRequestRequestTypeDef,
     PutRolePolicyRequestRolePolicyPutTypeDef,
@@ -789,37 +835,21 @@
     RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef,
     RemoveRoleFromInstanceProfileRequestInstanceProfileRemoveRoleTypeDef,
     RemoveRoleFromInstanceProfileRequestRequestTypeDef,
     RemoveUserFromGroupRequestGroupRemoveUserTypeDef,
     RemoveUserFromGroupRequestRequestTypeDef,
     RemoveUserFromGroupRequestUserRemoveGroupTypeDef,
     ResetServiceSpecificCredentialRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResyncMFADeviceRequestMfaDeviceResyncTypeDef,
     ResyncMFADeviceRequestRequestTypeDef,
     RoleLastUsedTypeDef,
-    RolePolicyRequestTypeDef,
+    RoleLastUsedResponseMetadataTypeDef,
+    ServerCertificateMetadataResponseMetadataTypeDef,
     TrackedActionLastAccessedTypeDef,
-    ServiceResourceAccessKeyPairRequestTypeDef,
-    ServiceResourceAccessKeyRequestTypeDef,
-    ServiceResourceAssumeRolePolicyRequestTypeDef,
-    ServiceResourceGroupPolicyRequestTypeDef,
-    ServiceResourceGroupRequestTypeDef,
-    ServiceResourceInstanceProfileRequestTypeDef,
-    ServiceResourceLoginProfileRequestTypeDef,
-    ServiceResourceMfaDeviceRequestTypeDef,
-    ServiceResourcePolicyRequestTypeDef,
-    ServiceResourcePolicyVersionRequestTypeDef,
-    ServiceResourceRolePolicyRequestTypeDef,
-    ServiceResourceRoleRequestTypeDef,
-    ServiceResourceSamlProviderRequestTypeDef,
-    ServiceResourceServerCertificateRequestTypeDef,
-    ServiceResourceSigningCertificateRequestTypeDef,
-    ServiceResourceUserPolicyRequestTypeDef,
-    ServiceResourceUserRequestTypeDef,
-    ServiceResourceVirtualMfaDeviceRequestTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetSecurityTokenServicePreferencesRequestRequestTypeDef,
     UntagInstanceProfileRequestRequestTypeDef,
     UntagMFADeviceRequestRequestTypeDef,
     UntagOpenIDConnectProviderRequestRequestTypeDef,
     UntagPolicyRequestRequestTypeDef,
     UntagRoleRequestRequestTypeDef,
@@ -841,57 +871,37 @@
     UpdateLoginProfileRequestLoginProfileUpdateTypeDef,
     UpdateLoginProfileRequestRequestTypeDef,
     UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef,
     UpdateRoleDescriptionRequestRequestTypeDef,
     UpdateRoleRequestRequestTypeDef,
     UpdateSAMLProviderRequestRequestTypeDef,
     UpdateSAMLProviderRequestSamlProviderUpdateTypeDef,
+    UpdateSAMLProviderResponseTypeDef,
     UpdateSSHPublicKeyRequestRequestTypeDef,
     UpdateServerCertificateRequestRequestTypeDef,
     UpdateServerCertificateRequestServerCertificateUpdateTypeDef,
     UpdateServiceSpecificCredentialRequestRequestTypeDef,
     UpdateSigningCertificateRequestRequestTypeDef,
     UpdateSigningCertificateRequestSigningCertificateActivateTypeDef,
     UpdateSigningCertificateRequestSigningCertificateDeactivateTypeDef,
     UpdateUserRequestRequestTypeDef,
     UpdateUserRequestUserUpdateTypeDef,
     UploadSSHPublicKeyRequestRequestTypeDef,
     UploadSigningCertificateRequestRequestTypeDef,
     UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
-    UserAccessKeyRequestTypeDef,
-    UserMfaDeviceRequestTypeDef,
-    UserPolicyRequestTypeDef,
-    UserSigningCertificateRequestTypeDef,
-    AttachedPermissionsBoundaryResponseMetadataTypeDef,
-    CreateAccessKeyResponseTypeDef,
-    DeleteServiceLinkedRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GenerateCredentialReportResponseTypeDef,
-    GenerateOrganizationsAccessReportResponseTypeDef,
-    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedResponseTypeDef,
-    GetAccountSummaryResponseTypeDef,
-    GetContextKeysForPolicyResponseTypeDef,
-    GetCredentialReportResponseTypeDef,
-    GetGroupPolicyResponseTypeDef,
-    GetRolePolicyResponseTypeDef,
-    GetUserPolicyResponseTypeDef,
     ListAccessKeysResponseTypeDef,
-    ListAccountAliasesResponseTypeDef,
-    ListGroupPoliciesResponseTypeDef,
-    ListRolePoliciesResponseTypeDef,
-    ListUserPoliciesResponseTypeDef,
-    RoleLastUsedResponseMetadataTypeDef,
-    ServerCertificateMetadataResponseMetadataTypeDef,
-    UpdateSAMLProviderResponseTypeDef,
+    CreateAccessKeyResponseTypeDef,
     ListAttachedGroupPoliciesResponseTypeDef,
     ListAttachedRolePoliciesResponseTypeDef,
     ListAttachedUserPoliciesResponseTypeDef,
     SimulateCustomPolicyRequestRequestTypeDef,
+    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
     SimulatePrincipalPolicyRequestRequestTypeDef,
+    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     CreateGroupResponseTypeDef,
     ListGroupsForUserResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     CreateInstanceProfileRequestServiceResourceCreateInstanceProfileTypeDef,
     CreateOpenIDConnectProviderRequestRequestTypeDef,
     CreateOpenIDConnectProviderResponseTypeDef,
@@ -937,41 +947,14 @@
     ListPolicyVersionsResponseTypeDef,
     ManagedPolicyDetailTypeDef,
     CreateServiceSpecificCredentialResponseTypeDef,
     ResetServiceSpecificCredentialResponseTypeDef,
     DeletionTaskFailureReasonTypeTypeDef,
     EntityDetailsTypeDef,
     GetOrganizationsAccessReportResponseTypeDef,
-    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
-    GetGroupRequestGetGroupPaginateTypeDef,
-    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
-    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
-    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-    ListRolesRequestListRolesPaginateTypeDef,
-    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
-    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
-    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
-    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-    ListUserTagsRequestListUserTagsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
-    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     GetAccountPasswordPolicyResponseTypeDef,
     GetInstanceProfileRequestInstanceProfileExistsWaitTypeDef,
     GetPolicyRequestPolicyExistsWaitTypeDef,
     GetRoleRequestRoleExistsWaitTypeDef,
     GetUserRequestUserExistsWaitTypeDef,
     GetSSHPublicKeyResponseTypeDef,
     UploadSSHPublicKeyResponseTypeDef,
@@ -1032,43 +1015,43 @@
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

### Comparing `types-aiobotocore-iam-2.5.0.post1/README.md` & `types-aiobotocore-iam-2.5.1/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-iam
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IAM 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore iam type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-iam"></a>
 
 # types-aiobotocore-iam
 
 [![PyPI - types-aiobotocore-iam](https://img.shields.io/pypi/v/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iam?color=blue)](https://pypistats.org/packages/types-aiobotocore-iam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
+[aiobotocore.IAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
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
 [types-aiobotocore-iam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -253,22 +286,29 @@
     ListAttachedGroupPoliciesPaginator,
     ListAttachedRolePoliciesPaginator,
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsPaginator,
     ListGroupsForUserPaginator,
+    ListInstanceProfileTagsPaginator,
     ListInstanceProfilesPaginator,
     ListInstanceProfilesForRolePaginator,
+    ListMFADeviceTagsPaginator,
     ListMFADevicesPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
+    ListRoleTagsPaginator,
     ListRolesPaginator,
+    ListSAMLProviderTagsPaginator,
     ListSSHPublicKeysPaginator,
+    ListServerCertificateTagsPaginator,
     ListServerCertificatesPaginator,
     ListSigningCertificatesPaginator,
     ListUserPoliciesPaginator,
     ListUserTagsPaginator,
     ListUsersPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -304,32 +344,49 @@
     list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator(
         "list_group_policies"
     )
     list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
     list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator(
         "list_groups_for_user"
     )
+    list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator(
+        "list_instance_profile_tags"
+    )
     list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator(
         "list_instance_profiles"
     )
     list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = (
         client.get_paginator("list_instance_profiles_for_role")
     )
+    list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator(
+        "list_mfa_device_tags"
+    )
     list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+    list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = (
+        client.get_paginator("list_open_id_connect_provider_tags")
+    )
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+    list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
     list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator(
         "list_policy_versions"
     )
     list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator(
         "list_role_policies"
     )
+    list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
     list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+    list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator(
+        "list_saml_provider_tags"
+    )
     list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator(
         "list_ssh_public_keys"
     )
+    list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = (
+        client.get_paginator("list_server_certificate_tags")
+    )
     list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator(
         "list_server_certificates"
     )
     list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator(
         "list_signing_certificates"
     )
     list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator(
@@ -526,22 +583,29 @@
     ListAttachedGroupPoliciesPaginatorName,
     ListAttachedRolePoliciesPaginatorName,
     ListAttachedUserPoliciesPaginatorName,
     ListEntitiesForPolicyPaginatorName,
     ListGroupPoliciesPaginatorName,
     ListGroupsForUserPaginatorName,
     ListGroupsPaginatorName,
+    ListInstanceProfileTagsPaginatorName,
     ListInstanceProfilesForRolePaginatorName,
     ListInstanceProfilesPaginatorName,
+    ListMFADeviceTagsPaginatorName,
     ListMFADevicesPaginatorName,
+    ListOpenIDConnectProviderTagsPaginatorName,
     ListPoliciesPaginatorName,
+    ListPolicyTagsPaginatorName,
     ListPolicyVersionsPaginatorName,
     ListRolePoliciesPaginatorName,
+    ListRoleTagsPaginatorName,
     ListRolesPaginatorName,
+    ListSAMLProviderTagsPaginatorName,
     ListSSHPublicKeysPaginatorName,
+    ListServerCertificateTagsPaginatorName,
     ListServerCertificatesPaginatorName,
     ListSigningCertificatesPaginatorName,
     ListUserPoliciesPaginatorName,
     ListUserTagsPaginatorName,
     ListUsersPaginatorName,
     ListVirtualMFADevicesPaginatorName,
     PermissionsBoundaryAttachmentTypeType,
@@ -601,15 +665,15 @@
     AttachGroupPolicyRequestRequestTypeDef,
     AttachRolePolicyRequestPolicyAttachRoleTypeDef,
     AttachRolePolicyRequestRequestTypeDef,
     AttachRolePolicyRequestRoleAttachPolicyTypeDef,
     AttachUserPolicyRequestPolicyAttachUserTypeDef,
     AttachUserPolicyRequestRequestTypeDef,
     AttachUserPolicyRequestUserAttachPolicyTypeDef,
-    ResponseMetadataTypeDef,
+    AttachedPermissionsBoundaryResponseMetadataTypeDef,
     AttachedPermissionsBoundaryTypeDef,
     AttachedPolicyTypeDef,
     ChangePasswordRequestRequestTypeDef,
     ChangePasswordRequestServiceResourceChangePasswordTypeDef,
     ContextEntryTypeDef,
     CreateAccessKeyRequestRequestTypeDef,
     CreateAccountAliasRequestRequestTypeDef,
@@ -642,14 +706,15 @@
     DeleteRolePermissionsBoundaryRequestRequestTypeDef,
     DeleteRolePolicyRequestRequestTypeDef,
     DeleteRoleRequestRequestTypeDef,
     DeleteSAMLProviderRequestRequestTypeDef,
     DeleteSSHPublicKeyRequestRequestTypeDef,
     DeleteServerCertificateRequestRequestTypeDef,
     DeleteServiceLinkedRoleRequestRequestTypeDef,
+    DeleteServiceLinkedRoleResponseTypeDef,
     DeleteServiceSpecificCredentialRequestRequestTypeDef,
     DeleteSigningCertificateRequestRequestTypeDef,
     DeleteUserPermissionsBoundaryRequestRequestTypeDef,
     DeleteUserPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeleteVirtualMFADeviceRequestRequestTypeDef,
     RoleUsageTypeTypeDef,
@@ -658,94 +723,141 @@
     DetachGroupPolicyRequestRequestTypeDef,
     DetachRolePolicyRequestPolicyDetachRoleTypeDef,
     DetachRolePolicyRequestRequestTypeDef,
     DetachRolePolicyRequestRoleDetachPolicyTypeDef,
     DetachUserPolicyRequestPolicyDetachUserTypeDef,
     DetachUserPolicyRequestRequestTypeDef,
     DetachUserPolicyRequestUserDetachPolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMFADeviceRequestMfaDeviceAssociateTypeDef,
     EnableMFADeviceRequestRequestTypeDef,
     EnableMFADeviceRequestUserEnableMfaTypeDef,
     EntityInfoTypeDef,
     ErrorDetailsTypeDef,
     OrganizationsDecisionDetailTypeDef,
     PermissionsBoundaryDecisionDetailTypeDef,
+    GenerateCredentialReportResponseTypeDef,
     GenerateOrganizationsAccessReportRequestRequestTypeDef,
+    GenerateOrganizationsAccessReportResponseTypeDef,
     GenerateServiceLastAccessedDetailsRequestRequestTypeDef,
+    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
     GetAccountAuthorizationDetailsRequestRequestTypeDef,
     PasswordPolicyTypeDef,
+    GetAccountSummaryResponseTypeDef,
     GetContextKeysForCustomPolicyRequestRequestTypeDef,
+    GetContextKeysForPolicyResponseTypeDef,
     GetContextKeysForPrincipalPolicyRequestRequestTypeDef,
+    GetCredentialReportResponseTypeDef,
     GetGroupPolicyRequestRequestTypeDef,
+    GetGroupPolicyResponseTypeDef,
+    GetGroupRequestGetGroupPaginateTypeDef,
     GetGroupRequestRequestTypeDef,
     WaiterConfigTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetLoginProfileRequestRequestTypeDef,
+    GetMFADeviceRequestRequestTypeDef,
+    GetMFADeviceResponseTypeDef,
     GetOpenIDConnectProviderRequestRequestTypeDef,
     GetOrganizationsAccessReportRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
     GetRolePolicyRequestRequestTypeDef,
+    GetRolePolicyResponseTypeDef,
     GetRoleRequestRequestTypeDef,
     GetSAMLProviderRequestRequestTypeDef,
     GetSSHPublicKeyRequestRequestTypeDef,
     SSHPublicKeyTypeDef,
     GetServerCertificateRequestRequestTypeDef,
     GetServiceLastAccessedDetailsRequestRequestTypeDef,
     GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef,
     GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef,
     GetUserPolicyRequestRequestTypeDef,
+    GetUserPolicyResponseTypeDef,
     GetUserRequestRequestTypeDef,
     PolicyDetailTypeDef,
-    GroupPolicyRequestTypeDef,
+    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
     ListAccessKeysRequestRequestTypeDef,
+    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
     ListAccountAliasesRequestRequestTypeDef,
+    ListAccountAliasesResponseTypeDef,
+    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
     ListAttachedGroupPoliciesRequestRequestTypeDef,
+    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
     ListAttachedRolePoliciesRequestRequestTypeDef,
+    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
     ListAttachedUserPoliciesRequestRequestTypeDef,
+    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
     ListEntitiesForPolicyRequestRequestTypeDef,
     PolicyGroupTypeDef,
     PolicyRoleTypeDef,
     PolicyUserTypeDef,
+    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
     ListGroupPoliciesRequestRequestTypeDef,
+    ListGroupPoliciesResponseTypeDef,
+    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
     ListGroupsForUserRequestRequestTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
+    ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
     ListInstanceProfileTagsRequestRequestTypeDef,
+    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
     ListInstanceProfilesForRoleRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
     ListMFADeviceTagsRequestRequestTypeDef,
+    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
     ListMFADevicesRequestRequestTypeDef,
     MFADeviceTypeDef,
+    ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
     ListOpenIDConnectProviderTagsRequestRequestTypeDef,
     OpenIDConnectProviderListEntryTypeDef,
     PolicyGrantingServiceAccessTypeDef,
     ListPoliciesGrantingServiceAccessRequestRequestTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
     ListPolicyTagsRequestRequestTypeDef,
+    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
+    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
     ListRolePoliciesRequestRequestTypeDef,
+    ListRolePoliciesResponseTypeDef,
+    ListRoleTagsRequestListRoleTagsPaginateTypeDef,
     ListRoleTagsRequestRequestTypeDef,
+    ListRolesRequestListRolesPaginateTypeDef,
     ListRolesRequestRequestTypeDef,
+    ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
     ListSAMLProviderTagsRequestRequestTypeDef,
     SAMLProviderListEntryTypeDef,
+    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
     ListSSHPublicKeysRequestRequestTypeDef,
     SSHPublicKeyMetadataTypeDef,
+    ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
     ListServerCertificateTagsRequestRequestTypeDef,
+    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
     ListServerCertificatesRequestRequestTypeDef,
     ServerCertificateMetadataTypeDef,
     ListServiceSpecificCredentialsRequestRequestTypeDef,
     ServiceSpecificCredentialMetadataTypeDef,
+    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
     ListSigningCertificatesRequestRequestTypeDef,
     SigningCertificateTypeDef,
+    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
     ListUserPoliciesRequestRequestTypeDef,
+    ListUserPoliciesResponseTypeDef,
+    ListUserTagsRequestListUserTagsPaginateTypeDef,
     ListUserTagsRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
+    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
     ListVirtualMFADevicesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PositionTypeDef,
     PutGroupPolicyRequestGroupCreatePolicyTypeDef,
     PutGroupPolicyRequestGroupPolicyPutTypeDef,
     PutGroupPolicyRequestRequestTypeDef,
     PutRolePermissionsBoundaryRequestRequestTypeDef,
     PutRolePolicyRequestRequestTypeDef,
     PutRolePolicyRequestRolePolicyPutTypeDef,
@@ -756,37 +868,21 @@
     RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef,
     RemoveRoleFromInstanceProfileRequestInstanceProfileRemoveRoleTypeDef,
     RemoveRoleFromInstanceProfileRequestRequestTypeDef,
     RemoveUserFromGroupRequestGroupRemoveUserTypeDef,
     RemoveUserFromGroupRequestRequestTypeDef,
     RemoveUserFromGroupRequestUserRemoveGroupTypeDef,
     ResetServiceSpecificCredentialRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResyncMFADeviceRequestMfaDeviceResyncTypeDef,
     ResyncMFADeviceRequestRequestTypeDef,
     RoleLastUsedTypeDef,
-    RolePolicyRequestTypeDef,
+    RoleLastUsedResponseMetadataTypeDef,
+    ServerCertificateMetadataResponseMetadataTypeDef,
     TrackedActionLastAccessedTypeDef,
-    ServiceResourceAccessKeyPairRequestTypeDef,
-    ServiceResourceAccessKeyRequestTypeDef,
-    ServiceResourceAssumeRolePolicyRequestTypeDef,
-    ServiceResourceGroupPolicyRequestTypeDef,
-    ServiceResourceGroupRequestTypeDef,
-    ServiceResourceInstanceProfileRequestTypeDef,
-    ServiceResourceLoginProfileRequestTypeDef,
-    ServiceResourceMfaDeviceRequestTypeDef,
-    ServiceResourcePolicyRequestTypeDef,
-    ServiceResourcePolicyVersionRequestTypeDef,
-    ServiceResourceRolePolicyRequestTypeDef,
-    ServiceResourceRoleRequestTypeDef,
-    ServiceResourceSamlProviderRequestTypeDef,
-    ServiceResourceServerCertificateRequestTypeDef,
-    ServiceResourceSigningCertificateRequestTypeDef,
-    ServiceResourceUserPolicyRequestTypeDef,
-    ServiceResourceUserRequestTypeDef,
-    ServiceResourceVirtualMfaDeviceRequestTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetSecurityTokenServicePreferencesRequestRequestTypeDef,
     UntagInstanceProfileRequestRequestTypeDef,
     UntagMFADeviceRequestRequestTypeDef,
     UntagOpenIDConnectProviderRequestRequestTypeDef,
     UntagPolicyRequestRequestTypeDef,
     UntagRoleRequestRequestTypeDef,
@@ -808,57 +904,37 @@
     UpdateLoginProfileRequestLoginProfileUpdateTypeDef,
     UpdateLoginProfileRequestRequestTypeDef,
     UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef,
     UpdateRoleDescriptionRequestRequestTypeDef,
     UpdateRoleRequestRequestTypeDef,
     UpdateSAMLProviderRequestRequestTypeDef,
     UpdateSAMLProviderRequestSamlProviderUpdateTypeDef,
+    UpdateSAMLProviderResponseTypeDef,
     UpdateSSHPublicKeyRequestRequestTypeDef,
     UpdateServerCertificateRequestRequestTypeDef,
     UpdateServerCertificateRequestServerCertificateUpdateTypeDef,
     UpdateServiceSpecificCredentialRequestRequestTypeDef,
     UpdateSigningCertificateRequestRequestTypeDef,
     UpdateSigningCertificateRequestSigningCertificateActivateTypeDef,
     UpdateSigningCertificateRequestSigningCertificateDeactivateTypeDef,
     UpdateUserRequestRequestTypeDef,
     UpdateUserRequestUserUpdateTypeDef,
     UploadSSHPublicKeyRequestRequestTypeDef,
     UploadSigningCertificateRequestRequestTypeDef,
     UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
-    UserAccessKeyRequestTypeDef,
-    UserMfaDeviceRequestTypeDef,
-    UserPolicyRequestTypeDef,
-    UserSigningCertificateRequestTypeDef,
-    AttachedPermissionsBoundaryResponseMetadataTypeDef,
-    CreateAccessKeyResponseTypeDef,
-    DeleteServiceLinkedRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GenerateCredentialReportResponseTypeDef,
-    GenerateOrganizationsAccessReportResponseTypeDef,
-    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedResponseTypeDef,
-    GetAccountSummaryResponseTypeDef,
-    GetContextKeysForPolicyResponseTypeDef,
-    GetCredentialReportResponseTypeDef,
-    GetGroupPolicyResponseTypeDef,
-    GetRolePolicyResponseTypeDef,
-    GetUserPolicyResponseTypeDef,
     ListAccessKeysResponseTypeDef,
-    ListAccountAliasesResponseTypeDef,
-    ListGroupPoliciesResponseTypeDef,
-    ListRolePoliciesResponseTypeDef,
-    ListUserPoliciesResponseTypeDef,
-    RoleLastUsedResponseMetadataTypeDef,
-    ServerCertificateMetadataResponseMetadataTypeDef,
-    UpdateSAMLProviderResponseTypeDef,
+    CreateAccessKeyResponseTypeDef,
     ListAttachedGroupPoliciesResponseTypeDef,
     ListAttachedRolePoliciesResponseTypeDef,
     ListAttachedUserPoliciesResponseTypeDef,
     SimulateCustomPolicyRequestRequestTypeDef,
+    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
     SimulatePrincipalPolicyRequestRequestTypeDef,
+    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     CreateGroupResponseTypeDef,
     ListGroupsForUserResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     CreateInstanceProfileRequestServiceResourceCreateInstanceProfileTypeDef,
     CreateOpenIDConnectProviderRequestRequestTypeDef,
     CreateOpenIDConnectProviderResponseTypeDef,
@@ -904,41 +980,14 @@
     ListPolicyVersionsResponseTypeDef,
     ManagedPolicyDetailTypeDef,
     CreateServiceSpecificCredentialResponseTypeDef,
     ResetServiceSpecificCredentialResponseTypeDef,
     DeletionTaskFailureReasonTypeTypeDef,
     EntityDetailsTypeDef,
     GetOrganizationsAccessReportResponseTypeDef,
-    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
-    GetGroupRequestGetGroupPaginateTypeDef,
-    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
-    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
-    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-    ListRolesRequestListRolesPaginateTypeDef,
-    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
-    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
-    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
-    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-    ListUserTagsRequestListUserTagsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
-    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     GetAccountPasswordPolicyResponseTypeDef,
     GetInstanceProfileRequestInstanceProfileExistsWaitTypeDef,
     GetPolicyRequestPolicyExistsWaitTypeDef,
     GetRoleRequestRoleExistsWaitTypeDef,
     GetUserRequestUserExistsWaitTypeDef,
     GetSSHPublicKeyResponseTypeDef,
     UploadSSHPublicKeyResponseTypeDef,
@@ -999,43 +1048,43 @@
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

### Comparing `types-aiobotocore-iam-2.5.0.post1/setup.py` & `types-aiobotocore-iam-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iam.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iam",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iam"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IAM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.IAM 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/",
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

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__init__.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__init__.py`

 * *Files 18% similar despite different names*

```diff
@@ -17,22 +17,29 @@
         ListAttachedGroupPoliciesPaginator,
         ListAttachedRolePoliciesPaginator,
         ListAttachedUserPoliciesPaginator,
         ListEntitiesForPolicyPaginator,
         ListGroupPoliciesPaginator,
         ListGroupsForUserPaginator,
         ListGroupsPaginator,
+        ListInstanceProfileTagsPaginator,
         ListInstanceProfilesForRolePaginator,
         ListInstanceProfilesPaginator,
+        ListMFADeviceTagsPaginator,
         ListMFADevicesPaginator,
+        ListOpenIDConnectProviderTagsPaginator,
         ListPoliciesPaginator,
+        ListPolicyTagsPaginator,
         ListPolicyVersionsPaginator,
         ListRolePoliciesPaginator,
+        ListRoleTagsPaginator,
         ListRolesPaginator,
+        ListSAMLProviderTagsPaginator,
         ListSSHPublicKeysPaginator,
+        ListServerCertificateTagsPaginator,
         ListServerCertificatesPaginator,
         ListSigningCertificatesPaginator,
         ListUserPoliciesPaginator,
         ListUserTagsPaginator,
         ListUsersPaginator,
         ListVirtualMFADevicesPaginator,
         PolicyExistsWaiter,
@@ -61,22 +68,29 @@
     list_attached_group_policies_paginator: ListAttachedGroupPoliciesPaginator = client.get_paginator("list_attached_group_policies")
     list_attached_role_policies_paginator: ListAttachedRolePoliciesPaginator = client.get_paginator("list_attached_role_policies")
     list_attached_user_policies_paginator: ListAttachedUserPoliciesPaginator = client.get_paginator("list_attached_user_policies")
     list_entities_for_policy_paginator: ListEntitiesForPolicyPaginator = client.get_paginator("list_entities_for_policy")
     list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator("list_group_policies")
     list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
     list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator("list_groups_for_user")
+    list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator("list_instance_profile_tags")
     list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator("list_instance_profiles")
     list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = client.get_paginator("list_instance_profiles_for_role")
+    list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator("list_mfa_device_tags")
     list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+    list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = client.get_paginator("list_open_id_connect_provider_tags")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+    list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
     list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator("list_policy_versions")
     list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator("list_role_policies")
+    list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
     list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+    list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator("list_saml_provider_tags")
     list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator("list_ssh_public_keys")
+    list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = client.get_paginator("list_server_certificate_tags")
     list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator("list_server_certificates")
     list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator("list_signing_certificates")
     list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator("list_user_policies")
     list_user_tags_paginator: ListUserTagsPaginator = client.get_paginator("list_user_tags")
     list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     list_virtual_mfa_devices_paginator: ListVirtualMFADevicesPaginator = client.get_paginator("list_virtual_mfa_devices")
     simulate_custom_policy_paginator: SimulateCustomPolicyPaginator = client.get_paginator("simulate_custom_policy")
@@ -94,20 +108,27 @@
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsForUserPaginator,
     ListGroupsPaginator,
     ListInstanceProfilesForRolePaginator,
     ListInstanceProfilesPaginator,
+    ListInstanceProfileTagsPaginator,
     ListMFADevicesPaginator,
+    ListMFADeviceTagsPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
     ListRolesPaginator,
+    ListRoleTagsPaginator,
+    ListSAMLProviderTagsPaginator,
     ListServerCertificatesPaginator,
+    ListServerCertificateTagsPaginator,
     ListSigningCertificatesPaginator,
     ListSSHPublicKeysPaginator,
     ListUserPoliciesPaginator,
     ListUsersPaginator,
     ListUserTagsPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -136,22 +157,29 @@
     "ListAttachedGroupPoliciesPaginator",
     "ListAttachedRolePoliciesPaginator",
     "ListAttachedUserPoliciesPaginator",
     "ListEntitiesForPolicyPaginator",
     "ListGroupPoliciesPaginator",
     "ListGroupsForUserPaginator",
     "ListGroupsPaginator",
+    "ListInstanceProfileTagsPaginator",
     "ListInstanceProfilesForRolePaginator",
     "ListInstanceProfilesPaginator",
+    "ListMFADeviceTagsPaginator",
     "ListMFADevicesPaginator",
+    "ListOpenIDConnectProviderTagsPaginator",
     "ListPoliciesPaginator",
+    "ListPolicyTagsPaginator",
     "ListPolicyVersionsPaginator",
     "ListRolePoliciesPaginator",
+    "ListRoleTagsPaginator",
     "ListRolesPaginator",
+    "ListSAMLProviderTagsPaginator",
     "ListSSHPublicKeysPaginator",
+    "ListServerCertificateTagsPaginator",
     "ListServerCertificatesPaginator",
     "ListSigningCertificatesPaginator",
     "ListUserPoliciesPaginator",
     "ListUserTagsPaginator",
     "ListUsersPaginator",
     "ListVirtualMFADevicesPaginator",
     "PolicyExistsWaiter",
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__init__.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__init__.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -17,22 +17,29 @@
         ListAttachedGroupPoliciesPaginator,
         ListAttachedRolePoliciesPaginator,
         ListAttachedUserPoliciesPaginator,
         ListEntitiesForPolicyPaginator,
         ListGroupPoliciesPaginator,
         ListGroupsForUserPaginator,
         ListGroupsPaginator,
+        ListInstanceProfileTagsPaginator,
         ListInstanceProfilesForRolePaginator,
         ListInstanceProfilesPaginator,
+        ListMFADeviceTagsPaginator,
         ListMFADevicesPaginator,
+        ListOpenIDConnectProviderTagsPaginator,
         ListPoliciesPaginator,
+        ListPolicyTagsPaginator,
         ListPolicyVersionsPaginator,
         ListRolePoliciesPaginator,
+        ListRoleTagsPaginator,
         ListRolesPaginator,
+        ListSAMLProviderTagsPaginator,
         ListSSHPublicKeysPaginator,
+        ListServerCertificateTagsPaginator,
         ListServerCertificatesPaginator,
         ListSigningCertificatesPaginator,
         ListUserPoliciesPaginator,
         ListUserTagsPaginator,
         ListUsersPaginator,
         ListVirtualMFADevicesPaginator,
         PolicyExistsWaiter,
@@ -61,22 +68,29 @@
     list_attached_group_policies_paginator: ListAttachedGroupPoliciesPaginator = client.get_paginator("list_attached_group_policies")
     list_attached_role_policies_paginator: ListAttachedRolePoliciesPaginator = client.get_paginator("list_attached_role_policies")
     list_attached_user_policies_paginator: ListAttachedUserPoliciesPaginator = client.get_paginator("list_attached_user_policies")
     list_entities_for_policy_paginator: ListEntitiesForPolicyPaginator = client.get_paginator("list_entities_for_policy")
     list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator("list_group_policies")
     list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
     list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator("list_groups_for_user")
+    list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator("list_instance_profile_tags")
     list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator("list_instance_profiles")
     list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = client.get_paginator("list_instance_profiles_for_role")
+    list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator("list_mfa_device_tags")
     list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+    list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = client.get_paginator("list_open_id_connect_provider_tags")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+    list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
     list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator("list_policy_versions")
     list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator("list_role_policies")
+    list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
     list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+    list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator("list_saml_provider_tags")
     list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator("list_ssh_public_keys")
+    list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = client.get_paginator("list_server_certificate_tags")
     list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator("list_server_certificates")
     list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator("list_signing_certificates")
     list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator("list_user_policies")
     list_user_tags_paginator: ListUserTagsPaginator = client.get_paginator("list_user_tags")
     list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     list_virtual_mfa_devices_paginator: ListVirtualMFADevicesPaginator = client.get_paginator("list_virtual_mfa_devices")
     simulate_custom_policy_paginator: SimulateCustomPolicyPaginator = client.get_paginator("simulate_custom_policy")
@@ -94,20 +108,27 @@
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsForUserPaginator,
     ListGroupsPaginator,
     ListInstanceProfilesForRolePaginator,
     ListInstanceProfilesPaginator,
+    ListInstanceProfileTagsPaginator,
     ListMFADevicesPaginator,
+    ListMFADeviceTagsPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
     ListRolesPaginator,
+    ListRoleTagsPaginator,
+    ListSAMLProviderTagsPaginator,
     ListServerCertificatesPaginator,
+    ListServerCertificateTagsPaginator,
     ListSigningCertificatesPaginator,
     ListSSHPublicKeysPaginator,
     ListUserPoliciesPaginator,
     ListUsersPaginator,
     ListUserTagsPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -135,22 +156,29 @@
     "ListAttachedGroupPoliciesPaginator",
     "ListAttachedRolePoliciesPaginator",
     "ListAttachedUserPoliciesPaginator",
     "ListEntitiesForPolicyPaginator",
     "ListGroupPoliciesPaginator",
     "ListGroupsForUserPaginator",
     "ListGroupsPaginator",
+    "ListInstanceProfileTagsPaginator",
     "ListInstanceProfilesForRolePaginator",
     "ListInstanceProfilesPaginator",
+    "ListMFADeviceTagsPaginator",
     "ListMFADevicesPaginator",
+    "ListOpenIDConnectProviderTagsPaginator",
     "ListPoliciesPaginator",
+    "ListPolicyTagsPaginator",
     "ListPolicyVersionsPaginator",
     "ListRolePoliciesPaginator",
+    "ListRoleTagsPaginator",
     "ListRolesPaginator",
+    "ListSAMLProviderTagsPaginator",
     "ListSSHPublicKeysPaginator",
+    "ListServerCertificateTagsPaginator",
     "ListServerCertificatesPaginator",
     "ListSigningCertificatesPaginator",
     "ListUserPoliciesPaginator",
     "ListUserTagsPaginator",
     "ListUsersPaginator",
     "ListVirtualMFADevicesPaginator",
     "PolicyExistsWaiter",
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/__main__.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IAM 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IAM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM\nOther"
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

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/client.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -41,20 +41,27 @@
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsForUserPaginator,
     ListGroupsPaginator,
     ListInstanceProfilesForRolePaginator,
     ListInstanceProfilesPaginator,
+    ListInstanceProfileTagsPaginator,
     ListMFADevicesPaginator,
+    ListMFADeviceTagsPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
     ListRolesPaginator,
+    ListRoleTagsPaginator,
+    ListSAMLProviderTagsPaginator,
     ListServerCertificatesPaginator,
+    ListServerCertificateTagsPaginator,
     ListSigningCertificatesPaginator,
     ListSSHPublicKeysPaginator,
     ListUserPoliciesPaginator,
     ListUsersPaginator,
     ListUserTagsPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -86,14 +93,15 @@
     GetAccountSummaryResponseTypeDef,
     GetContextKeysForPolicyResponseTypeDef,
     GetCredentialReportResponseTypeDef,
     GetGroupPolicyResponseTypeDef,
     GetGroupResponseTypeDef,
     GetInstanceProfileResponseTypeDef,
     GetLoginProfileResponseTypeDef,
+    GetMFADeviceResponseTypeDef,
     GetOpenIDConnectProviderResponseTypeDef,
     GetOrganizationsAccessReportResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetPolicyVersionResponseTypeDef,
     GetRolePolicyResponseTypeDef,
     GetRoleResponseTypeDef,
     GetSAMLProviderResponseTypeDef,
@@ -618,15 +626,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#delete_server_certificate)
         """
 
     async def delete_service_linked_role(
         self, *, RoleName: str
     ) -> DeleteServiceLinkedRoleResponseTypeDef:
         """
-        Submits a service-linked role deletion request and returns a `DeletionTaskId` ,
+        Submits a service-linked role deletion request and returns a `DeletionTaskId`,
         which you can use to check the status of the deletion.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.delete_service_linked_role)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#delete_service_linked_role)
         """
 
     async def delete_service_specific_credential(
@@ -887,14 +895,24 @@
         """
         Retrieves the user name for the specified IAM user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_login_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_login_profile)
         """
 
+    async def get_mfa_device(
+        self, *, SerialNumber: str, UserName: str = ...
+    ) -> GetMFADeviceResponseTypeDef:
+        """
+        Retrieves information about an MFA device for a specified user.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_mfa_device)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_mfa_device)
+        """
+
     async def get_open_id_connect_provider(
         self, *, OpenIDConnectProviderArn: str
     ) -> GetOpenIDConnectProviderResponseTypeDef:
         """
         Returns information about the specified OpenID Connect (OIDC) provider resource
         object in IAM.
 
@@ -2039,14 +2057,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_instance_profile_tags"]
+    ) -> ListInstanceProfileTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_instance_profiles"]
     ) -> ListInstanceProfilesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
@@ -2056,28 +2083,53 @@
     ) -> ListInstanceProfilesForRolePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_mfa_device_tags"]
+    ) -> ListMFADeviceTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_mfa_devices"]) -> ListMFADevicesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_open_id_connect_provider_tags"]
+    ) -> ListOpenIDConnectProviderTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_policies"]) -> ListPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(self, operation_name: Literal["list_policy_tags"]) -> ListPolicyTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(
         self, operation_name: Literal["list_policy_versions"]
     ) -> ListPolicyVersionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
@@ -2088,31 +2140,56 @@
     ) -> ListRolePoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(self, operation_name: Literal["list_role_tags"]) -> ListRoleTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_roles"]) -> ListRolesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_saml_provider_tags"]
+    ) -> ListSAMLProviderTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_ssh_public_keys"]
     ) -> ListSSHPublicKeysPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_server_certificate_tags"]
+    ) -> ListServerCertificateTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_server_certificates"]
     ) -> ListServerCertificatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/client.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -41,20 +41,27 @@
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsForUserPaginator,
     ListGroupsPaginator,
     ListInstanceProfilesForRolePaginator,
     ListInstanceProfilesPaginator,
+    ListInstanceProfileTagsPaginator,
     ListMFADevicesPaginator,
+    ListMFADeviceTagsPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
     ListRolesPaginator,
+    ListRoleTagsPaginator,
+    ListSAMLProviderTagsPaginator,
     ListServerCertificatesPaginator,
+    ListServerCertificateTagsPaginator,
     ListSigningCertificatesPaginator,
     ListSSHPublicKeysPaginator,
     ListUserPoliciesPaginator,
     ListUsersPaginator,
     ListUserTagsPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -86,14 +93,15 @@
     GetAccountSummaryResponseTypeDef,
     GetContextKeysForPolicyResponseTypeDef,
     GetCredentialReportResponseTypeDef,
     GetGroupPolicyResponseTypeDef,
     GetGroupResponseTypeDef,
     GetInstanceProfileResponseTypeDef,
     GetLoginProfileResponseTypeDef,
+    GetMFADeviceResponseTypeDef,
     GetOpenIDConnectProviderResponseTypeDef,
     GetOrganizationsAccessReportResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetPolicyVersionResponseTypeDef,
     GetRolePolicyResponseTypeDef,
     GetRoleResponseTypeDef,
     GetSAMLProviderResponseTypeDef,
@@ -574,15 +582,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.delete_server_certificate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#delete_server_certificate)
         """
     async def delete_service_linked_role(
         self, *, RoleName: str
     ) -> DeleteServiceLinkedRoleResponseTypeDef:
         """
-        Submits a service-linked role deletion request and returns a `DeletionTaskId` ,
+        Submits a service-linked role deletion request and returns a `DeletionTaskId`,
         which you can use to check the status of the deletion.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.delete_service_linked_role)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#delete_service_linked_role)
         """
     async def delete_service_specific_credential(
         self, *, ServiceSpecificCredentialId: str, UserName: str = ...
@@ -816,14 +824,23 @@
     async def get_login_profile(self, *, UserName: str) -> GetLoginProfileResponseTypeDef:
         """
         Retrieves the user name for the specified IAM user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_login_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_login_profile)
         """
+    async def get_mfa_device(
+        self, *, SerialNumber: str, UserName: str = ...
+    ) -> GetMFADeviceResponseTypeDef:
+        """
+        Retrieves information about an MFA device for a specified user.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_mfa_device)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_mfa_device)
+        """
     async def get_open_id_connect_provider(
         self, *, OpenIDConnectProviderArn: str
     ) -> GetOpenIDConnectProviderResponseTypeDef:
         """
         Returns information about the specified OpenID Connect (OIDC) provider resource
         object in IAM.
 
@@ -1862,14 +1879,22 @@
     ) -> ListGroupsForUserPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_instance_profile_tags"]
+    ) -> ListInstanceProfileTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_instance_profiles"]
     ) -> ListInstanceProfilesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
@@ -1877,26 +1902,48 @@
         self, operation_name: Literal["list_instance_profiles_for_role"]
     ) -> ListInstanceProfilesForRolePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_mfa_device_tags"]
+    ) -> ListMFADeviceTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_mfa_devices"]) -> ListMFADevicesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_open_id_connect_provider_tags"]
+    ) -> ListOpenIDConnectProviderTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_policies"]) -> ListPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
+    def get_paginator(self, operation_name: Literal["list_policy_tags"]) -> ListPolicyTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
     def get_paginator(
         self, operation_name: Literal["list_policy_versions"]
     ) -> ListPolicyVersionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
@@ -1905,29 +1952,51 @@
         self, operation_name: Literal["list_role_policies"]
     ) -> ListRolePoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
+    def get_paginator(self, operation_name: Literal["list_role_tags"]) -> ListRoleTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_roles"]) -> ListRolesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_saml_provider_tags"]
+    ) -> ListSAMLProviderTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_ssh_public_keys"]
     ) -> ListSSHPublicKeysPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_server_certificate_tags"]
+    ) -> ListServerCertificateTagsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_server_certificates"]
     ) -> ListServerCertificatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/client/#get_paginator)
         """
     @overload
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/literals.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -32,22 +32,29 @@
     "ListAttachedGroupPoliciesPaginatorName",
     "ListAttachedRolePoliciesPaginatorName",
     "ListAttachedUserPoliciesPaginatorName",
     "ListEntitiesForPolicyPaginatorName",
     "ListGroupPoliciesPaginatorName",
     "ListGroupsForUserPaginatorName",
     "ListGroupsPaginatorName",
+    "ListInstanceProfileTagsPaginatorName",
     "ListInstanceProfilesForRolePaginatorName",
     "ListInstanceProfilesPaginatorName",
+    "ListMFADeviceTagsPaginatorName",
     "ListMFADevicesPaginatorName",
+    "ListOpenIDConnectProviderTagsPaginatorName",
     "ListPoliciesPaginatorName",
+    "ListPolicyTagsPaginatorName",
     "ListPolicyVersionsPaginatorName",
     "ListRolePoliciesPaginatorName",
+    "ListRoleTagsPaginatorName",
     "ListRolesPaginatorName",
+    "ListSAMLProviderTagsPaginatorName",
     "ListSSHPublicKeysPaginatorName",
+    "ListServerCertificateTagsPaginatorName",
     "ListServerCertificatesPaginatorName",
     "ListSigningCertificatesPaginatorName",
     "ListUserPoliciesPaginatorName",
     "ListUserTagsPaginatorName",
     "ListUsersPaginatorName",
     "ListVirtualMFADevicesPaginatorName",
     "PermissionsBoundaryAttachmentTypeType",
@@ -104,22 +111,29 @@
 ListAttachedGroupPoliciesPaginatorName = Literal["list_attached_group_policies"]
 ListAttachedRolePoliciesPaginatorName = Literal["list_attached_role_policies"]
 ListAttachedUserPoliciesPaginatorName = Literal["list_attached_user_policies"]
 ListEntitiesForPolicyPaginatorName = Literal["list_entities_for_policy"]
 ListGroupPoliciesPaginatorName = Literal["list_group_policies"]
 ListGroupsForUserPaginatorName = Literal["list_groups_for_user"]
 ListGroupsPaginatorName = Literal["list_groups"]
+ListInstanceProfileTagsPaginatorName = Literal["list_instance_profile_tags"]
 ListInstanceProfilesForRolePaginatorName = Literal["list_instance_profiles_for_role"]
 ListInstanceProfilesPaginatorName = Literal["list_instance_profiles"]
+ListMFADeviceTagsPaginatorName = Literal["list_mfa_device_tags"]
 ListMFADevicesPaginatorName = Literal["list_mfa_devices"]
+ListOpenIDConnectProviderTagsPaginatorName = Literal["list_open_id_connect_provider_tags"]
 ListPoliciesPaginatorName = Literal["list_policies"]
+ListPolicyTagsPaginatorName = Literal["list_policy_tags"]
 ListPolicyVersionsPaginatorName = Literal["list_policy_versions"]
 ListRolePoliciesPaginatorName = Literal["list_role_policies"]
+ListRoleTagsPaginatorName = Literal["list_role_tags"]
 ListRolesPaginatorName = Literal["list_roles"]
+ListSAMLProviderTagsPaginatorName = Literal["list_saml_provider_tags"]
 ListSSHPublicKeysPaginatorName = Literal["list_ssh_public_keys"]
+ListServerCertificateTagsPaginatorName = Literal["list_server_certificate_tags"]
 ListServerCertificatesPaginatorName = Literal["list_server_certificates"]
 ListSigningCertificatesPaginatorName = Literal["list_signing_certificates"]
 ListUserPoliciesPaginatorName = Literal["list_user_policies"]
 ListUserTagsPaginatorName = Literal["list_user_tags"]
 ListUsersPaginatorName = Literal["list_users"]
 ListVirtualMFADevicesPaginatorName = Literal["list_virtual_mfa_devices"]
 PermissionsBoundaryAttachmentTypeType = Literal["PermissionsBoundaryPolicy"]
@@ -236,14 +250,15 @@
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
@@ -322,14 +337,15 @@
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
@@ -340,14 +356,15 @@
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
@@ -383,14 +400,15 @@
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
@@ -409,16 +427,19 @@
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
@@ -502,15 +523,17 @@
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
@@ -540,21 +563,28 @@
     "list_attached_group_policies",
     "list_attached_role_policies",
     "list_attached_user_policies",
     "list_entities_for_policy",
     "list_group_policies",
     "list_groups",
     "list_groups_for_user",
+    "list_instance_profile_tags",
     "list_instance_profiles",
     "list_instance_profiles_for_role",
+    "list_mfa_device_tags",
     "list_mfa_devices",
+    "list_open_id_connect_provider_tags",
     "list_policies",
+    "list_policy_tags",
     "list_policy_versions",
     "list_role_policies",
+    "list_role_tags",
     "list_roles",
+    "list_saml_provider_tags",
+    "list_server_certificate_tags",
     "list_server_certificates",
     "list_signing_certificates",
     "list_ssh_public_keys",
     "list_user_policies",
     "list_user_tags",
     "list_users",
     "list_virtual_mfa_devices",
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/literals.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -31,22 +31,29 @@
     "ListAttachedGroupPoliciesPaginatorName",
     "ListAttachedRolePoliciesPaginatorName",
     "ListAttachedUserPoliciesPaginatorName",
     "ListEntitiesForPolicyPaginatorName",
     "ListGroupPoliciesPaginatorName",
     "ListGroupsForUserPaginatorName",
     "ListGroupsPaginatorName",
+    "ListInstanceProfileTagsPaginatorName",
     "ListInstanceProfilesForRolePaginatorName",
     "ListInstanceProfilesPaginatorName",
+    "ListMFADeviceTagsPaginatorName",
     "ListMFADevicesPaginatorName",
+    "ListOpenIDConnectProviderTagsPaginatorName",
     "ListPoliciesPaginatorName",
+    "ListPolicyTagsPaginatorName",
     "ListPolicyVersionsPaginatorName",
     "ListRolePoliciesPaginatorName",
+    "ListRoleTagsPaginatorName",
     "ListRolesPaginatorName",
+    "ListSAMLProviderTagsPaginatorName",
     "ListSSHPublicKeysPaginatorName",
+    "ListServerCertificateTagsPaginatorName",
     "ListServerCertificatesPaginatorName",
     "ListSigningCertificatesPaginatorName",
     "ListUserPoliciesPaginatorName",
     "ListUserTagsPaginatorName",
     "ListUsersPaginatorName",
     "ListVirtualMFADevicesPaginatorName",
     "PermissionsBoundaryAttachmentTypeType",
@@ -102,22 +109,29 @@
 ListAttachedGroupPoliciesPaginatorName = Literal["list_attached_group_policies"]
 ListAttachedRolePoliciesPaginatorName = Literal["list_attached_role_policies"]
 ListAttachedUserPoliciesPaginatorName = Literal["list_attached_user_policies"]
 ListEntitiesForPolicyPaginatorName = Literal["list_entities_for_policy"]
 ListGroupPoliciesPaginatorName = Literal["list_group_policies"]
 ListGroupsForUserPaginatorName = Literal["list_groups_for_user"]
 ListGroupsPaginatorName = Literal["list_groups"]
+ListInstanceProfileTagsPaginatorName = Literal["list_instance_profile_tags"]
 ListInstanceProfilesForRolePaginatorName = Literal["list_instance_profiles_for_role"]
 ListInstanceProfilesPaginatorName = Literal["list_instance_profiles"]
+ListMFADeviceTagsPaginatorName = Literal["list_mfa_device_tags"]
 ListMFADevicesPaginatorName = Literal["list_mfa_devices"]
+ListOpenIDConnectProviderTagsPaginatorName = Literal["list_open_id_connect_provider_tags"]
 ListPoliciesPaginatorName = Literal["list_policies"]
+ListPolicyTagsPaginatorName = Literal["list_policy_tags"]
 ListPolicyVersionsPaginatorName = Literal["list_policy_versions"]
 ListRolePoliciesPaginatorName = Literal["list_role_policies"]
+ListRoleTagsPaginatorName = Literal["list_role_tags"]
 ListRolesPaginatorName = Literal["list_roles"]
+ListSAMLProviderTagsPaginatorName = Literal["list_saml_provider_tags"]
 ListSSHPublicKeysPaginatorName = Literal["list_ssh_public_keys"]
+ListServerCertificateTagsPaginatorName = Literal["list_server_certificate_tags"]
 ListServerCertificatesPaginatorName = Literal["list_server_certificates"]
 ListSigningCertificatesPaginatorName = Literal["list_signing_certificates"]
 ListUserPoliciesPaginatorName = Literal["list_user_policies"]
 ListUserTagsPaginatorName = Literal["list_user_tags"]
 ListUsersPaginatorName = Literal["list_users"]
 ListVirtualMFADevicesPaginatorName = Literal["list_virtual_mfa_devices"]
 PermissionsBoundaryAttachmentTypeType = Literal["PermissionsBoundaryPolicy"]
@@ -234,14 +248,15 @@
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
@@ -320,14 +335,15 @@
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
@@ -338,14 +354,15 @@
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
@@ -381,14 +398,15 @@
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
@@ -407,16 +425,19 @@
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
@@ -500,15 +521,17 @@
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
@@ -538,21 +561,28 @@
     "list_attached_group_policies",
     "list_attached_role_policies",
     "list_attached_user_policies",
     "list_entities_for_policy",
     "list_group_policies",
     "list_groups",
     "list_groups_for_user",
+    "list_instance_profile_tags",
     "list_instance_profiles",
     "list_instance_profiles_for_role",
+    "list_mfa_device_tags",
     "list_mfa_devices",
+    "list_open_id_connect_provider_tags",
     "list_policies",
+    "list_policy_tags",
     "list_policy_versions",
     "list_role_policies",
+    "list_role_tags",
     "list_roles",
+    "list_saml_provider_tags",
+    "list_server_certificate_tags",
     "list_server_certificates",
     "list_signing_certificates",
     "list_ssh_public_keys",
     "list_user_policies",
     "list_user_tags",
     "list_users",
     "list_virtual_mfa_devices",
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/paginator.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -17,22 +17,29 @@
         ListAttachedGroupPoliciesPaginator,
         ListAttachedRolePoliciesPaginator,
         ListAttachedUserPoliciesPaginator,
         ListEntitiesForPolicyPaginator,
         ListGroupPoliciesPaginator,
         ListGroupsPaginator,
         ListGroupsForUserPaginator,
+        ListInstanceProfileTagsPaginator,
         ListInstanceProfilesPaginator,
         ListInstanceProfilesForRolePaginator,
+        ListMFADeviceTagsPaginator,
         ListMFADevicesPaginator,
+        ListOpenIDConnectProviderTagsPaginator,
         ListPoliciesPaginator,
+        ListPolicyTagsPaginator,
         ListPolicyVersionsPaginator,
         ListRolePoliciesPaginator,
+        ListRoleTagsPaginator,
         ListRolesPaginator,
+        ListSAMLProviderTagsPaginator,
         ListSSHPublicKeysPaginator,
+        ListServerCertificateTagsPaginator,
         ListServerCertificatesPaginator,
         ListSigningCertificatesPaginator,
         ListUserPoliciesPaginator,
         ListUserTagsPaginator,
         ListUsersPaginator,
         ListVirtualMFADevicesPaginator,
         SimulateCustomPolicyPaginator,
@@ -50,34 +57,40 @@
         list_attached_group_policies_paginator: ListAttachedGroupPoliciesPaginator = client.get_paginator("list_attached_group_policies")
         list_attached_role_policies_paginator: ListAttachedRolePoliciesPaginator = client.get_paginator("list_attached_role_policies")
         list_attached_user_policies_paginator: ListAttachedUserPoliciesPaginator = client.get_paginator("list_attached_user_policies")
         list_entities_for_policy_paginator: ListEntitiesForPolicyPaginator = client.get_paginator("list_entities_for_policy")
         list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator("list_group_policies")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator("list_groups_for_user")
+        list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator("list_instance_profile_tags")
         list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator("list_instance_profiles")
         list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = client.get_paginator("list_instance_profiles_for_role")
+        list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator("list_mfa_device_tags")
         list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+        list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = client.get_paginator("list_open_id_connect_provider_tags")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+        list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
         list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator("list_policy_versions")
         list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator("list_role_policies")
+        list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
         list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+        list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator("list_saml_provider_tags")
         list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator("list_ssh_public_keys")
+        list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = client.get_paginator("list_server_certificate_tags")
         list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator("list_server_certificates")
         list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator("list_signing_certificates")
         list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator("list_user_policies")
         list_user_tags_paginator: ListUserTagsPaginator = client.get_paginator("list_user_tags")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
         list_virtual_mfa_devices_paginator: ListVirtualMFADevicesPaginator = client.get_paginator("list_virtual_mfa_devices")
         simulate_custom_policy_paginator: SimulateCustomPolicyPaginator = client.get_paginator("simulate_custom_policy")
         simulate_principal_policy_paginator: SimulatePrincipalPolicyPaginator = client.get_paginator("simulate_principal_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     EntityTypeType,
     PolicyUsageTypeType,
@@ -95,56 +108,64 @@
     ListAttachedUserPoliciesResponseTypeDef,
     ListEntitiesForPolicyResponseTypeDef,
     ListGroupPoliciesResponseTypeDef,
     ListGroupsForUserResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListInstanceProfilesForRoleResponseTypeDef,
     ListInstanceProfilesResponseTypeDef,
+    ListInstanceProfileTagsResponseTypeDef,
     ListMFADevicesResponseTypeDef,
+    ListMFADeviceTagsResponseTypeDef,
+    ListOpenIDConnectProviderTagsResponseTypeDef,
     ListPoliciesResponseTypeDef,
+    ListPolicyTagsResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListRolePoliciesResponseTypeDef,
     ListRolesResponseTypeDef,
+    ListRoleTagsResponseTypeDef,
+    ListSAMLProviderTagsResponseTypeDef,
     ListServerCertificatesResponseTypeDef,
+    ListServerCertificateTagsResponseTypeDef,
     ListSigningCertificatesResponseTypeDef,
     ListSSHPublicKeysResponseTypeDef,
     ListUserPoliciesResponseTypeDef,
     ListUsersResponseTypeDef,
     ListUserTagsResponseTypeDef,
     ListVirtualMFADevicesResponseTypeDef,
     PaginatorConfigTypeDef,
     SimulatePolicyResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetAccountAuthorizationDetailsPaginator",
     "GetGroupPaginator",
     "ListAccessKeysPaginator",
     "ListAccountAliasesPaginator",
     "ListAttachedGroupPoliciesPaginator",
     "ListAttachedRolePoliciesPaginator",
     "ListAttachedUserPoliciesPaginator",
     "ListEntitiesForPolicyPaginator",
     "ListGroupPoliciesPaginator",
     "ListGroupsPaginator",
     "ListGroupsForUserPaginator",
+    "ListInstanceProfileTagsPaginator",
     "ListInstanceProfilesPaginator",
     "ListInstanceProfilesForRolePaginator",
+    "ListMFADeviceTagsPaginator",
     "ListMFADevicesPaginator",
+    "ListOpenIDConnectProviderTagsPaginator",
     "ListPoliciesPaginator",
+    "ListPolicyTagsPaginator",
     "ListPolicyVersionsPaginator",
     "ListRolePoliciesPaginator",
+    "ListRoleTagsPaginator",
     "ListRolesPaginator",
+    "ListSAMLProviderTagsPaginator",
     "ListSSHPublicKeysPaginator",
+    "ListServerCertificateTagsPaginator",
     "ListServerCertificatesPaginator",
     "ListSigningCertificatesPaginator",
     "ListUserPoliciesPaginator",
     "ListUserTagsPaginator",
     "ListUsersPaginator",
     "ListVirtualMFADevicesPaginator",
     "SimulateCustomPolicyPaginator",
@@ -168,60 +189,60 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getaccountauthorizationdetailspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: Sequence[EntityTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAccountAuthorizationDetailsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetAccountAuthorizationDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getaccountauthorizationdetailspaginator)
         """
 
 
 class GetGroupPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetGroup)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getgrouppaginator)
     """
 
     def paginate(
-        self, *, GroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getgrouppaginator)
         """
 
 
 class ListAccessKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccessKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccesskeyspaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccessKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccesskeyspaginator)
         """
 
 
 class ListAccountAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccountAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccountaliasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccountAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccountaliasespaginator)
         """
 
 
@@ -232,15 +253,15 @@
     """
 
     def paginate(
         self,
         *,
         GroupName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedGroupPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedGroupPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattachedgrouppoliciespaginator)
         """
 
 
@@ -251,15 +272,15 @@
     """
 
     def paginate(
         self,
         *,
         RoleName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedRolePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedRolePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattachedrolepoliciespaginator)
         """
 
 
@@ -270,15 +291,15 @@
     """
 
     def paginate(
         self,
         *,
         UserName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedUserPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedUserPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattacheduserpoliciespaginator)
         """
 
 
@@ -291,261 +312,366 @@
     def paginate(
         self,
         *,
         PolicyArn: str,
         EntityFilter: EntityTypeType = ...,
         PathPrefix: str = ...,
         PolicyUsageFilter: PolicyUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntitiesForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListEntitiesForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listentitiesforpolicypaginator)
         """
 
 
 class ListGroupPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgrouppoliciespaginator)
     """
 
     def paginate(
-        self, *, GroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgrouppoliciespaginator)
         """
 
 
 class ListGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupspaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupspaginator)
         """
 
 
 class ListGroupsForUserPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupsForUser)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupsforuserpaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsForUserResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupsForUser.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupsforuserpaginator)
         """
 
 
+class ListInstanceProfileTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfileTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofiletagspaginator)
+    """
+
+    def paginate(
+        self, *, InstanceProfileName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListInstanceProfileTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfileTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofiletagspaginator)
+        """
+
+
 class ListInstanceProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilespaginator)
         """
 
 
 class ListInstanceProfilesForRolePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfilesForRole)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilesforrolepaginator)
     """
 
     def paginate(
-        self, *, RoleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesForRoleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfilesForRole.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilesforrolepaginator)
         """
 
 
+class ListMFADeviceTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADeviceTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicetagspaginator)
+    """
+
+    def paginate(
+        self, *, SerialNumber: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListMFADeviceTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADeviceTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicetagspaginator)
+        """
+
+
 class ListMFADevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicespaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMFADevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicespaginator)
         """
 
 
+class ListOpenIDConnectProviderTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListOpenIDConnectProviderTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listopenidconnectprovidertagspaginator)
+    """
+
+    def paginate(
+        self, *, OpenIDConnectProviderArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListOpenIDConnectProviderTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListOpenIDConnectProviderTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listopenidconnectprovidertagspaginator)
+        """
+
+
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         Scope: policyScopeTypeType = ...,
         OnlyAttached: bool = ...,
         PathPrefix: str = ...,
         PolicyUsageFilter: PolicyUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpoliciespaginator)
         """
 
 
+class ListPolicyTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicytagspaginator)
+    """
+
+    def paginate(
+        self, *, PolicyArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPolicyTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicytagspaginator)
+        """
+
+
 class ListPolicyVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicyversionspaginator)
     """
 
     def paginate(
-        self, *, PolicyArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicyversionspaginator)
         """
 
 
 class ListRolePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRolePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolepoliciespaginator)
     """
 
     def paginate(
-        self, *, RoleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRolePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRolePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolepoliciespaginator)
         """
 
 
+class ListRoleTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoleTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listroletagspaginator)
+    """
+
+    def paginate(
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListRoleTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoleTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listroletagspaginator)
+        """
+
+
 class ListRolesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRolesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolespaginator)
         """
 
 
+class ListSAMLProviderTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSAMLProviderTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsamlprovidertagspaginator)
+    """
+
+    def paginate(
+        self, *, SAMLProviderArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListSAMLProviderTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSAMLProviderTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsamlprovidertagspaginator)
+        """
+
+
 class ListSSHPublicKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSSHPublicKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsshpublickeyspaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSSHPublicKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSSHPublicKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsshpublickeyspaginator)
         """
 
 
+class ListServerCertificateTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificateTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatetagspaginator)
+    """
+
+    def paginate(
+        self, *, ServerCertificateName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListServerCertificateTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificateTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatetagspaginator)
+        """
+
+
 class ListServerCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServerCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatespaginator)
         """
 
 
 class ListSigningCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSigningCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsigningcertificatespaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSigningCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsigningcertificatespaginator)
         """
 
 
 class ListUserPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserpoliciespaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserpoliciespaginator)
         """
 
 
 class ListUserTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listusertagspaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listusertagspaginator)
         """
 
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserspaginator)
         """
 
 
@@ -555,15 +681,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listvirtualmfadevicespaginator)
     """
 
     def paginate(
         self,
         *,
         AssignmentStatus: assignmentStatusTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualMFADevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListVirtualMFADevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listvirtualmfadevicespaginator)
         """
 
 
@@ -581,15 +707,15 @@
         PermissionsBoundaryPolicyInputList: Sequence[str] = ...,
         ResourceArns: Sequence[str] = ...,
         ResourcePolicy: str = ...,
         ResourceOwner: str = ...,
         CallerArn: str = ...,
         ContextEntries: Sequence[ContextEntryTypeDef] = ...,
         ResourceHandlingOption: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SimulatePolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.SimulateCustomPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#simulatecustompolicypaginator)
         """
 
 
@@ -608,13 +734,13 @@
         PermissionsBoundaryPolicyInputList: Sequence[str] = ...,
         ResourceArns: Sequence[str] = ...,
         ResourcePolicy: str = ...,
         ResourceOwner: str = ...,
         CallerArn: str = ...,
         ContextEntries: Sequence[ContextEntryTypeDef] = ...,
         ResourceHandlingOption: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SimulatePolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.SimulatePrincipalPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#simulateprincipalpolicypaginator)
         """
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/paginator.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/paginator.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -17,22 +17,29 @@
         ListAttachedGroupPoliciesPaginator,
         ListAttachedRolePoliciesPaginator,
         ListAttachedUserPoliciesPaginator,
         ListEntitiesForPolicyPaginator,
         ListGroupPoliciesPaginator,
         ListGroupsPaginator,
         ListGroupsForUserPaginator,
+        ListInstanceProfileTagsPaginator,
         ListInstanceProfilesPaginator,
         ListInstanceProfilesForRolePaginator,
+        ListMFADeviceTagsPaginator,
         ListMFADevicesPaginator,
+        ListOpenIDConnectProviderTagsPaginator,
         ListPoliciesPaginator,
+        ListPolicyTagsPaginator,
         ListPolicyVersionsPaginator,
         ListRolePoliciesPaginator,
+        ListRoleTagsPaginator,
         ListRolesPaginator,
+        ListSAMLProviderTagsPaginator,
         ListSSHPublicKeysPaginator,
+        ListServerCertificateTagsPaginator,
         ListServerCertificatesPaginator,
         ListSigningCertificatesPaginator,
         ListUserPoliciesPaginator,
         ListUserTagsPaginator,
         ListUsersPaginator,
         ListVirtualMFADevicesPaginator,
         SimulateCustomPolicyPaginator,
@@ -50,34 +57,40 @@
         list_attached_group_policies_paginator: ListAttachedGroupPoliciesPaginator = client.get_paginator("list_attached_group_policies")
         list_attached_role_policies_paginator: ListAttachedRolePoliciesPaginator = client.get_paginator("list_attached_role_policies")
         list_attached_user_policies_paginator: ListAttachedUserPoliciesPaginator = client.get_paginator("list_attached_user_policies")
         list_entities_for_policy_paginator: ListEntitiesForPolicyPaginator = client.get_paginator("list_entities_for_policy")
         list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator("list_group_policies")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator("list_groups_for_user")
+        list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator("list_instance_profile_tags")
         list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator("list_instance_profiles")
         list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = client.get_paginator("list_instance_profiles_for_role")
+        list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator("list_mfa_device_tags")
         list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+        list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = client.get_paginator("list_open_id_connect_provider_tags")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+        list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
         list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator("list_policy_versions")
         list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator("list_role_policies")
+        list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
         list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+        list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator("list_saml_provider_tags")
         list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator("list_ssh_public_keys")
+        list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = client.get_paginator("list_server_certificate_tags")
         list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator("list_server_certificates")
         list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator("list_signing_certificates")
         list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator("list_user_policies")
         list_user_tags_paginator: ListUserTagsPaginator = client.get_paginator("list_user_tags")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
         list_virtual_mfa_devices_paginator: ListVirtualMFADevicesPaginator = client.get_paginator("list_virtual_mfa_devices")
         simulate_custom_policy_paginator: SimulateCustomPolicyPaginator = client.get_paginator("simulate_custom_policy")
         simulate_principal_policy_paginator: SimulatePrincipalPolicyPaginator = client.get_paginator("simulate_principal_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     EntityTypeType,
     PolicyUsageTypeType,
@@ -95,55 +108,64 @@
     ListAttachedUserPoliciesResponseTypeDef,
     ListEntitiesForPolicyResponseTypeDef,
     ListGroupPoliciesResponseTypeDef,
     ListGroupsForUserResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListInstanceProfilesForRoleResponseTypeDef,
     ListInstanceProfilesResponseTypeDef,
+    ListInstanceProfileTagsResponseTypeDef,
     ListMFADevicesResponseTypeDef,
+    ListMFADeviceTagsResponseTypeDef,
+    ListOpenIDConnectProviderTagsResponseTypeDef,
     ListPoliciesResponseTypeDef,
+    ListPolicyTagsResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListRolePoliciesResponseTypeDef,
     ListRolesResponseTypeDef,
+    ListRoleTagsResponseTypeDef,
+    ListSAMLProviderTagsResponseTypeDef,
     ListServerCertificatesResponseTypeDef,
+    ListServerCertificateTagsResponseTypeDef,
     ListSigningCertificatesResponseTypeDef,
     ListSSHPublicKeysResponseTypeDef,
     ListUserPoliciesResponseTypeDef,
     ListUsersResponseTypeDef,
     ListUserTagsResponseTypeDef,
     ListVirtualMFADevicesResponseTypeDef,
     PaginatorConfigTypeDef,
     SimulatePolicyResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetAccountAuthorizationDetailsPaginator",
     "GetGroupPaginator",
     "ListAccessKeysPaginator",
     "ListAccountAliasesPaginator",
     "ListAttachedGroupPoliciesPaginator",
     "ListAttachedRolePoliciesPaginator",
     "ListAttachedUserPoliciesPaginator",
     "ListEntitiesForPolicyPaginator",
     "ListGroupPoliciesPaginator",
     "ListGroupsPaginator",
     "ListGroupsForUserPaginator",
+    "ListInstanceProfileTagsPaginator",
     "ListInstanceProfilesPaginator",
     "ListInstanceProfilesForRolePaginator",
+    "ListMFADeviceTagsPaginator",
     "ListMFADevicesPaginator",
+    "ListOpenIDConnectProviderTagsPaginator",
     "ListPoliciesPaginator",
+    "ListPolicyTagsPaginator",
     "ListPolicyVersionsPaginator",
     "ListRolePoliciesPaginator",
+    "ListRoleTagsPaginator",
     "ListRolesPaginator",
+    "ListSAMLProviderTagsPaginator",
     "ListSSHPublicKeysPaginator",
+    "ListServerCertificateTagsPaginator",
     "ListServerCertificatesPaginator",
     "ListSigningCertificatesPaginator",
     "ListUserPoliciesPaginator",
     "ListUserTagsPaginator",
     "ListUsersPaginator",
     "ListVirtualMFADevicesPaginator",
     "SimulateCustomPolicyPaginator",
@@ -164,57 +186,57 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getaccountauthorizationdetailspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: Sequence[EntityTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAccountAuthorizationDetailsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetAccountAuthorizationDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getaccountauthorizationdetailspaginator)
         """
 
 class GetGroupPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetGroup)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getgrouppaginator)
     """
 
     def paginate(
-        self, *, GroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.GetGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#getgrouppaginator)
         """
 
 class ListAccessKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccessKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccesskeyspaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccessKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccesskeyspaginator)
         """
 
 class ListAccountAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccountAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccountaliasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAccountAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listaccountaliasespaginator)
         """
 
 class ListAttachedGroupPoliciesPaginator(AioPaginator):
@@ -224,15 +246,15 @@
     """
 
     def paginate(
         self,
         *,
         GroupName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedGroupPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedGroupPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattachedgrouppoliciespaginator)
         """
 
 class ListAttachedRolePoliciesPaginator(AioPaginator):
@@ -242,15 +264,15 @@
     """
 
     def paginate(
         self,
         *,
         RoleName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedRolePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedRolePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattachedrolepoliciespaginator)
         """
 
 class ListAttachedUserPoliciesPaginator(AioPaginator):
@@ -260,15 +282,15 @@
     """
 
     def paginate(
         self,
         *,
         UserName: str,
         PathPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedUserPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListAttachedUserPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listattacheduserpoliciespaginator)
         """
 
 class ListEntitiesForPolicyPaginator(AioPaginator):
@@ -280,245 +302,343 @@
     def paginate(
         self,
         *,
         PolicyArn: str,
         EntityFilter: EntityTypeType = ...,
         PathPrefix: str = ...,
         PolicyUsageFilter: PolicyUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntitiesForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListEntitiesForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listentitiesforpolicypaginator)
         """
 
 class ListGroupPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgrouppoliciespaginator)
     """
 
     def paginate(
-        self, *, GroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgrouppoliciespaginator)
         """
 
 class ListGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupspaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupspaginator)
         """
 
 class ListGroupsForUserPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupsForUser)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupsforuserpaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsForUserResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListGroupsForUser.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listgroupsforuserpaginator)
         """
 
+class ListInstanceProfileTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfileTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofiletagspaginator)
+    """
+
+    def paginate(
+        self, *, InstanceProfileName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListInstanceProfileTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfileTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofiletagspaginator)
+        """
+
 class ListInstanceProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilespaginator)
         """
 
 class ListInstanceProfilesForRolePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfilesForRole)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilesforrolepaginator)
     """
 
     def paginate(
-        self, *, RoleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesForRoleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListInstanceProfilesForRole.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listinstanceprofilesforrolepaginator)
         """
 
+class ListMFADeviceTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADeviceTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicetagspaginator)
+    """
+
+    def paginate(
+        self, *, SerialNumber: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListMFADeviceTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADeviceTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicetagspaginator)
+        """
+
 class ListMFADevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicespaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMFADevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListMFADevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listmfadevicespaginator)
         """
 
+class ListOpenIDConnectProviderTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListOpenIDConnectProviderTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listopenidconnectprovidertagspaginator)
+    """
+
+    def paginate(
+        self, *, OpenIDConnectProviderArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListOpenIDConnectProviderTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListOpenIDConnectProviderTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listopenidconnectprovidertagspaginator)
+        """
+
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         Scope: policyScopeTypeType = ...,
         OnlyAttached: bool = ...,
         PathPrefix: str = ...,
         PolicyUsageFilter: PolicyUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpoliciespaginator)
         """
 
+class ListPolicyTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicytagspaginator)
+    """
+
+    def paginate(
+        self, *, PolicyArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPolicyTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicytagspaginator)
+        """
+
 class ListPolicyVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicyversionspaginator)
     """
 
     def paginate(
-        self, *, PolicyArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListPolicyVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listpolicyversionspaginator)
         """
 
 class ListRolePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRolePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolepoliciespaginator)
     """
 
     def paginate(
-        self, *, RoleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRolePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRolePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolepoliciespaginator)
         """
 
+class ListRoleTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoleTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listroletagspaginator)
+    """
+
+    def paginate(
+        self, *, RoleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListRoleTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoleTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listroletagspaginator)
+        """
+
 class ListRolesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRolesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListRoles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listrolespaginator)
         """
 
+class ListSAMLProviderTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSAMLProviderTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsamlprovidertagspaginator)
+    """
+
+    def paginate(
+        self, *, SAMLProviderArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListSAMLProviderTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSAMLProviderTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsamlprovidertagspaginator)
+        """
+
 class ListSSHPublicKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSSHPublicKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsshpublickeyspaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSSHPublicKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSSHPublicKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsshpublickeyspaginator)
         """
 
+class ListServerCertificateTagsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificateTags)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatetagspaginator)
+    """
+
+    def paginate(
+        self, *, ServerCertificateName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListServerCertificateTagsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificateTags.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatetagspaginator)
+        """
+
 class ListServerCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatespaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServerCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListServerCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listservercertificatespaginator)
         """
 
 class ListSigningCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSigningCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsigningcertificatespaginator)
     """
 
     def paginate(
-        self, *, UserName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListSigningCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listsigningcertificatespaginator)
         """
 
 class ListUserPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserpoliciespaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserpoliciespaginator)
         """
 
 class ListUserTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listusertagspaginator)
     """
 
     def paginate(
-        self, *, UserName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUserTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listusertagspaginator)
         """
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, PathPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PathPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listuserspaginator)
         """
 
 class ListVirtualMFADevicesPaginator(AioPaginator):
@@ -527,15 +647,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listvirtualmfadevicespaginator)
     """
 
     def paginate(
         self,
         *,
         AssignmentStatus: assignmentStatusTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualMFADevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.ListVirtualMFADevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#listvirtualmfadevicespaginator)
         """
 
 class SimulateCustomPolicyPaginator(AioPaginator):
@@ -552,15 +672,15 @@
         PermissionsBoundaryPolicyInputList: Sequence[str] = ...,
         ResourceArns: Sequence[str] = ...,
         ResourcePolicy: str = ...,
         ResourceOwner: str = ...,
         CallerArn: str = ...,
         ContextEntries: Sequence[ContextEntryTypeDef] = ...,
         ResourceHandlingOption: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SimulatePolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.SimulateCustomPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#simulatecustompolicypaginator)
         """
 
 class SimulatePrincipalPolicyPaginator(AioPaginator):
@@ -578,13 +698,13 @@
         PermissionsBoundaryPolicyInputList: Sequence[str] = ...,
         ResourceArns: Sequence[str] = ...,
         ResourcePolicy: str = ...,
         ResourceOwner: str = ...,
         CallerArn: str = ...,
         ContextEntries: Sequence[ContextEntryTypeDef] = ...,
         ResourceHandlingOption: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SimulatePolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.Paginator.SimulatePrincipalPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/paginators/#simulateprincipalpolicypaginator)
         """
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/service_resource.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/service_resource.py`

 * *Files 0% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         my_server_certificate: iam_resources.ServerCertificate = resource.ServerCertificate(...)
         my_signing_certificate: iam_resources.SigningCertificate = resource.SigningCertificate(...)
         my_user: iam_resources.User = resource.User(...)
         my_user_policy: iam_resources.UserPolicy = resource.UserPolicy(...)
         my_virtual_mfa_device: iam_resources.VirtualMfaDevice = resource.VirtualMfaDevice(...)
 ```
 """
-import sys
 from datetime import datetime
-from typing import Awaitable, Dict, List, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, NoReturn, Sequence
 
 from .client import IAMClient
 from .literals import (
     EntityTypeType,
     PolicyUsageTypeType,
     assignmentStatusTypeType,
     policyScopeTypeType,
@@ -65,18 +64,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ResourceMeta
 
 
 __all__ = (
@@ -3021,15 +3016,15 @@
         """
         Creates a MfaDevice resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.ServiceResource.MfaDevice)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/service_resource/#iamserviceresourcemfadevice-method)
         """
 
-    async def Policy(self, policy_arn: str) -> _Policy:
+    async def Policy(self, arn: str) -> _Policy:
         """
         Creates a Policy resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.ServiceResource.Policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/service_resource/#iamserviceresourcepolicy-method)
         """
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/service_resource.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/service_resource.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         my_server_certificate: iam_resources.ServerCertificate = resource.ServerCertificate(...)
         my_signing_certificate: iam_resources.SigningCertificate = resource.SigningCertificate(...)
         my_user: iam_resources.User = resource.User(...)
         my_user_policy: iam_resources.UserPolicy = resource.UserPolicy(...)
         my_virtual_mfa_device: iam_resources.VirtualMfaDevice = resource.VirtualMfaDevice(...)
 ```
 """
-import sys
 from datetime import datetime
-from typing import Awaitable, Dict, List, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, NoReturn, Sequence
 
 from .client import IAMClient
 from .literals import (
     EntityTypeType,
     PolicyUsageTypeType,
     assignmentStatusTypeType,
     policyScopeTypeType,
@@ -65,18 +64,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ResourceMeta
 
 __all__ = (
     "IAMServiceResource",
@@ -2666,15 +2661,15 @@
     async def MfaDevice(self, user_name: str, serial_number: str) -> _MfaDevice:
         """
         Creates a MfaDevice resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.ServiceResource.MfaDevice)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/service_resource/#iamserviceresourcemfadevice-method)
         """
-    async def Policy(self, policy_arn: str) -> _Policy:
+    async def Policy(self, arn: str) -> _Policy:
         """
         Creates a Policy resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM.ServiceResource.Policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/service_resource/#iamserviceresourcepolicy-method)
         """
     async def PolicyVersion(self, arn: str, version_id: str) -> _PolicyVersion:
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/type_defs.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/type_defs.py`

 * *Files 12% similar despite different names*

```diff
@@ -62,15 +62,15 @@
     "AttachGroupPolicyRequestRequestTypeDef",
     "AttachRolePolicyRequestPolicyAttachRoleTypeDef",
     "AttachRolePolicyRequestRequestTypeDef",
     "AttachRolePolicyRequestRoleAttachPolicyTypeDef",
     "AttachUserPolicyRequestPolicyAttachUserTypeDef",
     "AttachUserPolicyRequestRequestTypeDef",
     "AttachUserPolicyRequestUserAttachPolicyTypeDef",
-    "ResponseMetadataTypeDef",
+    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
     "AttachedPermissionsBoundaryTypeDef",
     "AttachedPolicyTypeDef",
     "ChangePasswordRequestRequestTypeDef",
     "ChangePasswordRequestServiceResourceChangePasswordTypeDef",
     "ContextEntryTypeDef",
     "CreateAccessKeyRequestRequestTypeDef",
     "CreateAccountAliasRequestRequestTypeDef",
@@ -103,14 +103,15 @@
     "DeleteRolePermissionsBoundaryRequestRequestTypeDef",
     "DeleteRolePolicyRequestRequestTypeDef",
     "DeleteRoleRequestRequestTypeDef",
     "DeleteSAMLProviderRequestRequestTypeDef",
     "DeleteSSHPublicKeyRequestRequestTypeDef",
     "DeleteServerCertificateRequestRequestTypeDef",
     "DeleteServiceLinkedRoleRequestRequestTypeDef",
+    "DeleteServiceLinkedRoleResponseTypeDef",
     "DeleteServiceSpecificCredentialRequestRequestTypeDef",
     "DeleteSigningCertificateRequestRequestTypeDef",
     "DeleteUserPermissionsBoundaryRequestRequestTypeDef",
     "DeleteUserPolicyRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DeleteVirtualMFADeviceRequestRequestTypeDef",
     "RoleUsageTypeTypeDef",
@@ -119,94 +120,141 @@
     "DetachGroupPolicyRequestRequestTypeDef",
     "DetachRolePolicyRequestPolicyDetachRoleTypeDef",
     "DetachRolePolicyRequestRequestTypeDef",
     "DetachRolePolicyRequestRoleDetachPolicyTypeDef",
     "DetachUserPolicyRequestPolicyDetachUserTypeDef",
     "DetachUserPolicyRequestRequestTypeDef",
     "DetachUserPolicyRequestUserDetachPolicyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableMFADeviceRequestMfaDeviceAssociateTypeDef",
     "EnableMFADeviceRequestRequestTypeDef",
     "EnableMFADeviceRequestUserEnableMfaTypeDef",
     "EntityInfoTypeDef",
     "ErrorDetailsTypeDef",
     "OrganizationsDecisionDetailTypeDef",
     "PermissionsBoundaryDecisionDetailTypeDef",
+    "GenerateCredentialReportResponseTypeDef",
     "GenerateOrganizationsAccessReportRequestRequestTypeDef",
+    "GenerateOrganizationsAccessReportResponseTypeDef",
     "GenerateServiceLastAccessedDetailsRequestRequestTypeDef",
+    "GenerateServiceLastAccessedDetailsResponseTypeDef",
     "GetAccessKeyLastUsedRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
     "GetAccountAuthorizationDetailsRequestRequestTypeDef",
     "PasswordPolicyTypeDef",
+    "GetAccountSummaryResponseTypeDef",
     "GetContextKeysForCustomPolicyRequestRequestTypeDef",
+    "GetContextKeysForPolicyResponseTypeDef",
     "GetContextKeysForPrincipalPolicyRequestRequestTypeDef",
+    "GetCredentialReportResponseTypeDef",
     "GetGroupPolicyRequestRequestTypeDef",
+    "GetGroupPolicyResponseTypeDef",
+    "GetGroupRequestGetGroupPaginateTypeDef",
     "GetGroupRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "GetInstanceProfileRequestRequestTypeDef",
     "GetLoginProfileRequestRequestTypeDef",
+    "GetMFADeviceRequestRequestTypeDef",
+    "GetMFADeviceResponseTypeDef",
     "GetOpenIDConnectProviderRequestRequestTypeDef",
     "GetOrganizationsAccessReportRequestRequestTypeDef",
     "GetPolicyRequestRequestTypeDef",
     "GetPolicyVersionRequestRequestTypeDef",
     "GetRolePolicyRequestRequestTypeDef",
+    "GetRolePolicyResponseTypeDef",
     "GetRoleRequestRequestTypeDef",
     "GetSAMLProviderRequestRequestTypeDef",
     "GetSSHPublicKeyRequestRequestTypeDef",
     "SSHPublicKeyTypeDef",
     "GetServerCertificateRequestRequestTypeDef",
     "GetServiceLastAccessedDetailsRequestRequestTypeDef",
     "GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef",
     "GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef",
     "GetUserPolicyRequestRequestTypeDef",
+    "GetUserPolicyResponseTypeDef",
     "GetUserRequestRequestTypeDef",
     "PolicyDetailTypeDef",
-    "GroupPolicyRequestTypeDef",
+    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
     "ListAccessKeysRequestRequestTypeDef",
+    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
     "ListAccountAliasesRequestRequestTypeDef",
+    "ListAccountAliasesResponseTypeDef",
+    "ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
     "ListAttachedGroupPoliciesRequestRequestTypeDef",
+    "ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
     "ListAttachedRolePoliciesRequestRequestTypeDef",
+    "ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
     "ListAttachedUserPoliciesRequestRequestTypeDef",
+    "ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
     "ListEntitiesForPolicyRequestRequestTypeDef",
     "PolicyGroupTypeDef",
     "PolicyRoleTypeDef",
     "PolicyUserTypeDef",
+    "ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
     "ListGroupPoliciesRequestRequestTypeDef",
+    "ListGroupPoliciesResponseTypeDef",
+    "ListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
     "ListGroupsForUserRequestRequestTypeDef",
+    "ListGroupsRequestListGroupsPaginateTypeDef",
     "ListGroupsRequestRequestTypeDef",
+    "ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
     "ListInstanceProfileTagsRequestRequestTypeDef",
+    "ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
     "ListInstanceProfilesForRoleRequestRequestTypeDef",
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
     "ListInstanceProfilesRequestRequestTypeDef",
+    "ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
     "ListMFADeviceTagsRequestRequestTypeDef",
+    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
     "ListMFADevicesRequestRequestTypeDef",
     "MFADeviceTypeDef",
+    "ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
     "ListOpenIDConnectProviderTagsRequestRequestTypeDef",
     "OpenIDConnectProviderListEntryTypeDef",
     "PolicyGrantingServiceAccessTypeDef",
     "ListPoliciesGrantingServiceAccessRequestRequestTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
     "ListPolicyTagsRequestRequestTypeDef",
+    "ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
     "ListPolicyVersionsRequestRequestTypeDef",
+    "ListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
     "ListRolePoliciesRequestRequestTypeDef",
+    "ListRolePoliciesResponseTypeDef",
+    "ListRoleTagsRequestListRoleTagsPaginateTypeDef",
     "ListRoleTagsRequestRequestTypeDef",
+    "ListRolesRequestListRolesPaginateTypeDef",
     "ListRolesRequestRequestTypeDef",
+    "ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
     "ListSAMLProviderTagsRequestRequestTypeDef",
     "SAMLProviderListEntryTypeDef",
+    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
     "ListSSHPublicKeysRequestRequestTypeDef",
     "SSHPublicKeyMetadataTypeDef",
+    "ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
     "ListServerCertificateTagsRequestRequestTypeDef",
+    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
     "ListServerCertificatesRequestRequestTypeDef",
     "ServerCertificateMetadataTypeDef",
     "ListServiceSpecificCredentialsRequestRequestTypeDef",
     "ServiceSpecificCredentialMetadataTypeDef",
+    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
     "ListSigningCertificatesRequestRequestTypeDef",
     "SigningCertificateTypeDef",
+    "ListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
     "ListUserPoliciesRequestRequestTypeDef",
+    "ListUserPoliciesResponseTypeDef",
+    "ListUserTagsRequestListUserTagsPaginateTypeDef",
     "ListUserTagsRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
+    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
     "ListVirtualMFADevicesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PositionTypeDef",
     "PutGroupPolicyRequestGroupCreatePolicyTypeDef",
     "PutGroupPolicyRequestGroupPolicyPutTypeDef",
     "PutGroupPolicyRequestRequestTypeDef",
     "PutRolePermissionsBoundaryRequestRequestTypeDef",
     "PutRolePolicyRequestRequestTypeDef",
     "PutRolePolicyRequestRolePolicyPutTypeDef",
@@ -217,37 +265,21 @@
     "RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef",
     "RemoveRoleFromInstanceProfileRequestInstanceProfileRemoveRoleTypeDef",
     "RemoveRoleFromInstanceProfileRequestRequestTypeDef",
     "RemoveUserFromGroupRequestGroupRemoveUserTypeDef",
     "RemoveUserFromGroupRequestRequestTypeDef",
     "RemoveUserFromGroupRequestUserRemoveGroupTypeDef",
     "ResetServiceSpecificCredentialRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResyncMFADeviceRequestMfaDeviceResyncTypeDef",
     "ResyncMFADeviceRequestRequestTypeDef",
     "RoleLastUsedTypeDef",
-    "RolePolicyRequestTypeDef",
+    "RoleLastUsedResponseMetadataTypeDef",
+    "ServerCertificateMetadataResponseMetadataTypeDef",
     "TrackedActionLastAccessedTypeDef",
-    "ServiceResourceAccessKeyPairRequestTypeDef",
-    "ServiceResourceAccessKeyRequestTypeDef",
-    "ServiceResourceAssumeRolePolicyRequestTypeDef",
-    "ServiceResourceGroupPolicyRequestTypeDef",
-    "ServiceResourceGroupRequestTypeDef",
-    "ServiceResourceInstanceProfileRequestTypeDef",
-    "ServiceResourceLoginProfileRequestTypeDef",
-    "ServiceResourceMfaDeviceRequestTypeDef",
-    "ServiceResourcePolicyRequestTypeDef",
-    "ServiceResourcePolicyVersionRequestTypeDef",
-    "ServiceResourceRolePolicyRequestTypeDef",
-    "ServiceResourceRoleRequestTypeDef",
-    "ServiceResourceSamlProviderRequestTypeDef",
-    "ServiceResourceServerCertificateRequestTypeDef",
-    "ServiceResourceSigningCertificateRequestTypeDef",
-    "ServiceResourceUserPolicyRequestTypeDef",
-    "ServiceResourceUserRequestTypeDef",
-    "ServiceResourceVirtualMfaDeviceRequestTypeDef",
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     "SetSecurityTokenServicePreferencesRequestRequestTypeDef",
     "UntagInstanceProfileRequestRequestTypeDef",
     "UntagMFADeviceRequestRequestTypeDef",
     "UntagOpenIDConnectProviderRequestRequestTypeDef",
     "UntagPolicyRequestRequestTypeDef",
     "UntagRoleRequestRequestTypeDef",
@@ -269,57 +301,37 @@
     "UpdateLoginProfileRequestLoginProfileUpdateTypeDef",
     "UpdateLoginProfileRequestRequestTypeDef",
     "UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef",
     "UpdateRoleDescriptionRequestRequestTypeDef",
     "UpdateRoleRequestRequestTypeDef",
     "UpdateSAMLProviderRequestRequestTypeDef",
     "UpdateSAMLProviderRequestSamlProviderUpdateTypeDef",
+    "UpdateSAMLProviderResponseTypeDef",
     "UpdateSSHPublicKeyRequestRequestTypeDef",
     "UpdateServerCertificateRequestRequestTypeDef",
     "UpdateServerCertificateRequestServerCertificateUpdateTypeDef",
     "UpdateServiceSpecificCredentialRequestRequestTypeDef",
     "UpdateSigningCertificateRequestRequestTypeDef",
     "UpdateSigningCertificateRequestSigningCertificateActivateTypeDef",
     "UpdateSigningCertificateRequestSigningCertificateDeactivateTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UpdateUserRequestUserUpdateTypeDef",
     "UploadSSHPublicKeyRequestRequestTypeDef",
     "UploadSigningCertificateRequestRequestTypeDef",
     "UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef",
-    "UserAccessKeyRequestTypeDef",
-    "UserMfaDeviceRequestTypeDef",
-    "UserPolicyRequestTypeDef",
-    "UserSigningCertificateRequestTypeDef",
-    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
-    "CreateAccessKeyResponseTypeDef",
-    "DeleteServiceLinkedRoleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GenerateCredentialReportResponseTypeDef",
-    "GenerateOrganizationsAccessReportResponseTypeDef",
-    "GenerateServiceLastAccessedDetailsResponseTypeDef",
     "GetAccessKeyLastUsedResponseTypeDef",
-    "GetAccountSummaryResponseTypeDef",
-    "GetContextKeysForPolicyResponseTypeDef",
-    "GetCredentialReportResponseTypeDef",
-    "GetGroupPolicyResponseTypeDef",
-    "GetRolePolicyResponseTypeDef",
-    "GetUserPolicyResponseTypeDef",
     "ListAccessKeysResponseTypeDef",
-    "ListAccountAliasesResponseTypeDef",
-    "ListGroupPoliciesResponseTypeDef",
-    "ListRolePoliciesResponseTypeDef",
-    "ListUserPoliciesResponseTypeDef",
-    "RoleLastUsedResponseMetadataTypeDef",
-    "ServerCertificateMetadataResponseMetadataTypeDef",
-    "UpdateSAMLProviderResponseTypeDef",
+    "CreateAccessKeyResponseTypeDef",
     "ListAttachedGroupPoliciesResponseTypeDef",
     "ListAttachedRolePoliciesResponseTypeDef",
     "ListAttachedUserPoliciesResponseTypeDef",
     "SimulateCustomPolicyRequestRequestTypeDef",
+    "SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
     "SimulatePrincipalPolicyRequestRequestTypeDef",
+    "SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
     "CreateGroupResponseTypeDef",
     "ListGroupsForUserResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "CreateInstanceProfileRequestRequestTypeDef",
     "CreateInstanceProfileRequestServiceResourceCreateInstanceProfileTypeDef",
     "CreateOpenIDConnectProviderRequestRequestTypeDef",
     "CreateOpenIDConnectProviderResponseTypeDef",
@@ -365,41 +377,14 @@
     "ListPolicyVersionsResponseTypeDef",
     "ManagedPolicyDetailTypeDef",
     "CreateServiceSpecificCredentialResponseTypeDef",
     "ResetServiceSpecificCredentialResponseTypeDef",
     "DeletionTaskFailureReasonTypeTypeDef",
     "EntityDetailsTypeDef",
     "GetOrganizationsAccessReportResponseTypeDef",
-    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
-    "GetGroupRequestGetGroupPaginateTypeDef",
-    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
-    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
-    "ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    "ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    "ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    "ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    "ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    "ListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    "ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    "ListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    "ListRolesRequestListRolesPaginateTypeDef",
-    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
-    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
-    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
-    "ListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    "ListUserTagsRequestListUserTagsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
-    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
-    "SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    "SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
     "GetAccountPasswordPolicyResponseTypeDef",
     "GetInstanceProfileRequestInstanceProfileExistsWaitTypeDef",
     "GetPolicyRequestPolicyExistsWaitTypeDef",
     "GetRoleRequestRoleExistsWaitTypeDef",
     "GetUserRequestUserExistsWaitTypeDef",
     "GetSSHPublicKeyResponseTypeDef",
     "UploadSSHPublicKeyResponseTypeDef",
@@ -624,22 +609,20 @@
 AttachUserPolicyRequestUserAttachPolicyTypeDef = TypedDict(
     "AttachUserPolicyRequestUserAttachPolicyTypeDef",
     {
         "PolicyArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AttachedPermissionsBoundaryResponseMetadataTypeDef = TypedDict(
+    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
+        "PermissionsBoundaryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachedPermissionsBoundaryTypeDef = TypedDict(
     "AttachedPermissionsBoundaryTypeDef",
     {
         "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
@@ -1096,14 +1079,22 @@
 DeleteServiceLinkedRoleRequestRequestTypeDef = TypedDict(
     "DeleteServiceLinkedRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 
+DeleteServiceLinkedRoleResponseTypeDef = TypedDict(
+    "DeleteServiceLinkedRoleResponseTypeDef",
+    {
+        "DeletionTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteServiceSpecificCredentialRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteServiceSpecificCredentialRequestRequestTypeDef",
     {
         "ServiceSpecificCredentialId": str,
     },
 )
 _OptionalDeleteServiceSpecificCredentialRequestRequestTypeDef = TypedDict(
@@ -1244,14 +1235,21 @@
 DetachUserPolicyRequestUserDetachPolicyTypeDef = TypedDict(
     "DetachUserPolicyRequestUserDetachPolicyTypeDef",
     {
         "PolicyArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableMFADeviceRequestMfaDeviceAssociateTypeDef = TypedDict(
     "EnableMFADeviceRequestMfaDeviceAssociateTypeDef",
     {
         "AuthenticationCode1": str,
         "AuthenticationCode2": str,
     },
 )
@@ -1317,14 +1315,23 @@
     "PermissionsBoundaryDecisionDetailTypeDef",
     {
         "AllowedByPermissionsBoundary": bool,
     },
     total=False,
 )
 
+GenerateCredentialReportResponseTypeDef = TypedDict(
+    "GenerateCredentialReportResponseTypeDef",
+    {
+        "State": ReportStateTypeType,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef",
     {
         "EntityPath": str,
     },
 )
 _OptionalGenerateOrganizationsAccessReportRequestRequestTypeDef = TypedDict(
@@ -1339,14 +1346,22 @@
 class GenerateOrganizationsAccessReportRequestRequestTypeDef(
     _RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef,
     _OptionalGenerateOrganizationsAccessReportRequestRequestTypeDef,
 ):
     pass
 
 
+GenerateOrganizationsAccessReportResponseTypeDef = TypedDict(
+    "GenerateOrganizationsAccessReportResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 _OptionalGenerateServiceLastAccessedDetailsRequestRequestTypeDef = TypedDict(
@@ -1361,27 +1376,34 @@
 class GenerateServiceLastAccessedDetailsRequestRequestTypeDef(
     _RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef,
     _OptionalGenerateServiceLastAccessedDetailsRequestRequestTypeDef,
 ):
     pass
 
 
+GenerateServiceLastAccessedDetailsResponseTypeDef = TypedDict(
+    "GenerateServiceLastAccessedDetailsResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessKeyLastUsedRequestRequestTypeDef = TypedDict(
     "GetAccessKeyLastUsedRequestRequestTypeDef",
     {
         "AccessKeyId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef = TypedDict(
+    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Filter": Sequence[EntityTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetAccountAuthorizationDetailsRequestRequestTypeDef = TypedDict(
     "GetAccountAuthorizationDetailsRequestRequestTypeDef",
     {
@@ -1405,21 +1427,37 @@
         "MaxPasswordAge": int,
         "PasswordReusePrevention": int,
         "HardExpiry": bool,
     },
     total=False,
 )
 
+GetAccountSummaryResponseTypeDef = TypedDict(
+    "GetAccountSummaryResponseTypeDef",
+    {
+        "SummaryMap": Dict[summaryKeyTypeType, int],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContextKeysForCustomPolicyRequestRequestTypeDef = TypedDict(
     "GetContextKeysForCustomPolicyRequestRequestTypeDef",
     {
         "PolicyInputList": Sequence[str],
     },
 )
 
+GetContextKeysForPolicyResponseTypeDef = TypedDict(
+    "GetContextKeysForPolicyResponseTypeDef",
+    {
+        "ContextKeyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef",
     {
         "PolicySourceArn": str,
     },
 )
 _OptionalGetContextKeysForPrincipalPolicyRequestRequestTypeDef = TypedDict(
@@ -1434,22 +1472,63 @@
 class GetContextKeysForPrincipalPolicyRequestRequestTypeDef(
     _RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef,
     _OptionalGetContextKeysForPrincipalPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+GetCredentialReportResponseTypeDef = TypedDict(
+    "GetCredentialReportResponseTypeDef",
+    {
+        "Content": bytes,
+        "ReportFormat": Literal["text/csv"],
+        "GeneratedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGroupPolicyRequestRequestTypeDef = TypedDict(
     "GetGroupPolicyRequestRequestTypeDef",
     {
         "GroupName": str,
         "PolicyName": str,
     },
 )
 
+GetGroupPolicyResponseTypeDef = TypedDict(
+    "GetGroupPolicyResponseTypeDef",
+    {
+        "GroupName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
+    "_RequiredGetGroupRequestGetGroupPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
+    "_OptionalGetGroupRequestGetGroupPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetGroupRequestGetGroupPaginateTypeDef(
+    _RequiredGetGroupRequestGetGroupPaginateTypeDef, _OptionalGetGroupRequestGetGroupPaginateTypeDef
+):
+    pass
+
+
 _RequiredGetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredGetGroupRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalGetGroupRequestRequestTypeDef = TypedDict(
@@ -1487,14 +1566,46 @@
 GetLoginProfileRequestRequestTypeDef = TypedDict(
     "GetLoginProfileRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 
+_RequiredGetMFADeviceRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMFADeviceRequestRequestTypeDef",
+    {
+        "SerialNumber": str,
+    },
+)
+_OptionalGetMFADeviceRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMFADeviceRequestRequestTypeDef",
+    {
+        "UserName": str,
+    },
+    total=False,
+)
+
+
+class GetMFADeviceRequestRequestTypeDef(
+    _RequiredGetMFADeviceRequestRequestTypeDef, _OptionalGetMFADeviceRequestRequestTypeDef
+):
+    pass
+
+
+GetMFADeviceResponseTypeDef = TypedDict(
+    "GetMFADeviceResponseTypeDef",
+    {
+        "UserName": str,
+        "SerialNumber": str,
+        "EnableDate": datetime,
+        "Certifications": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetOpenIDConnectProviderRequestRequestTypeDef = TypedDict(
     "GetOpenIDConnectProviderRequestRequestTypeDef",
     {
         "OpenIDConnectProviderArn": str,
     },
 )
 
@@ -1541,14 +1652,24 @@
     "GetRolePolicyRequestRequestTypeDef",
     {
         "RoleName": str,
         "PolicyName": str,
     },
 )
 
+GetRolePolicyResponseTypeDef = TypedDict(
+    "GetRolePolicyResponseTypeDef",
+    {
+        "RoleName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRoleRequestRequestTypeDef = TypedDict(
     "GetRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 
@@ -1656,14 +1777,24 @@
     "GetUserPolicyRequestRequestTypeDef",
     {
         "UserName": str,
         "PolicyName": str,
     },
 )
 
+GetUserPolicyResponseTypeDef = TypedDict(
+    "GetUserPolicyResponseTypeDef",
+    {
+        "UserName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetUserRequestRequestTypeDef = TypedDict(
     "GetUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
     total=False,
 )
@@ -1673,40 +1804,83 @@
     {
         "PolicyName": str,
         "PolicyDocument": str,
     },
     total=False,
 )
 
-GroupPolicyRequestTypeDef = TypedDict(
-    "GroupPolicyRequestTypeDef",
+ListAccessKeysRequestListAccessKeysPaginateTypeDef = TypedDict(
+    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
     {
-        "name": str,
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListAccessKeysRequestRequestTypeDef = TypedDict(
     "ListAccessKeysRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListAccountAliasesRequestListAccountAliasesPaginateTypeDef = TypedDict(
+    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccountAliasesRequestRequestTypeDef = TypedDict(
     "ListAccountAliasesRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListAccountAliasesResponseTypeDef = TypedDict(
+    "ListAccountAliasesResponseTypeDef",
+    {
+        "AccountAliases": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef(
+    _RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
+    _OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedGroupPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedGroupPoliciesRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalListAttachedGroupPoliciesRequestRequestTypeDef = TypedDict(
@@ -1723,14 +1897,37 @@
 class ListAttachedGroupPoliciesRequestRequestTypeDef(
     _RequiredListAttachedGroupPoliciesRequestRequestTypeDef,
     _OptionalListAttachedGroupPoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef(
+    _RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
+    _OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedRolePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedRolePoliciesRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListAttachedRolePoliciesRequestRequestTypeDef = TypedDict(
@@ -1747,14 +1944,37 @@
 class ListAttachedRolePoliciesRequestRequestTypeDef(
     _RequiredListAttachedRolePoliciesRequestRequestTypeDef,
     _OptionalListAttachedRolePoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef(
+    _RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
+    _OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedUserPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedUserPoliciesRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListAttachedUserPoliciesRequestRequestTypeDef = TypedDict(
@@ -1771,14 +1991,39 @@
 class ListAttachedUserPoliciesRequestRequestTypeDef(
     _RequiredListAttachedUserPoliciesRequestRequestTypeDef,
     _OptionalListAttachedUserPoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
+    {
+        "EntityFilter": EntityTypeType,
+        "PathPrefix": str,
+        "PolicyUsageFilter": PolicyUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef(
+    _RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
+    _OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEntitiesForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitiesForPolicyRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListEntitiesForPolicyRequestRequestTypeDef = TypedDict(
@@ -1824,14 +2069,36 @@
     {
         "UserName": str,
         "UserId": str,
     },
     total=False,
 )
 
+_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef(
+    _RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
+    _OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupPoliciesRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalListGroupPoliciesRequestRequestTypeDef = TypedDict(
@@ -1846,14 +2113,46 @@
 
 class ListGroupPoliciesRequestRequestTypeDef(
     _RequiredListGroupPoliciesRequestRequestTypeDef, _OptionalListGroupPoliciesRequestRequestTypeDef
 ):
     pass
 
 
+ListGroupPoliciesResponseTypeDef = TypedDict(
+    "ListGroupPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGroupsForUserRequestListGroupsForUserPaginateTypeDef(
+    _RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
+    _OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupsForUserRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsForUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListGroupsForUserRequestRequestTypeDef = TypedDict(
@@ -1868,24 +2167,55 @@
 
 class ListGroupsForUserRequestRequestTypeDef(
     _RequiredListGroupsForUserRequestRequestTypeDef, _OptionalListGroupsForUserRequestRequestTypeDef
 ):
     pass
 
 
+ListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "ListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGroupsRequestRequestTypeDef = TypedDict(
     "ListGroupsRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef = TypedDict(
+    "_RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
+    {
+        "InstanceProfileName": str,
+    },
+)
+_OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef = TypedDict(
+    "_OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef(
+    _RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
+    _OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInstanceProfileTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceProfileTagsRequestRequestTypeDef",
     {
         "InstanceProfileName": str,
     },
 )
 _OptionalListInstanceProfileTagsRequestRequestTypeDef = TypedDict(
@@ -1901,14 +2231,36 @@
 class ListInstanceProfileTagsRequestRequestTypeDef(
     _RequiredListInstanceProfileTagsRequestRequestTypeDef,
     _OptionalListInstanceProfileTagsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
+    "_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
+    "_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef(
+    _RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
+    _OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInstanceProfilesForRoleRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceProfilesForRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListInstanceProfilesForRoleRequestRequestTypeDef = TypedDict(
@@ -1924,24 +2276,55 @@
 class ListInstanceProfilesForRoleRequestRequestTypeDef(
     _RequiredListInstanceProfilesForRoleRequestRequestTypeDef,
     _OptionalListInstanceProfilesForRoleRequestRequestTypeDef,
 ):
     pass
 
 
+ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstanceProfilesRequestRequestTypeDef = TypedDict(
     "ListInstanceProfilesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef = TypedDict(
+    "_RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
+    {
+        "SerialNumber": str,
+    },
+)
+_OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef = TypedDict(
+    "_OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef(
+    _RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
+    _OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMFADeviceTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListMFADeviceTagsRequestRequestTypeDef",
     {
         "SerialNumber": str,
     },
 )
 _OptionalListMFADeviceTagsRequestRequestTypeDef = TypedDict(
@@ -1956,14 +2339,23 @@
 
 class ListMFADeviceTagsRequestRequestTypeDef(
     _RequiredListMFADeviceTagsRequestRequestTypeDef, _OptionalListMFADeviceTagsRequestRequestTypeDef
 ):
     pass
 
 
+ListMFADevicesRequestListMFADevicesPaginateTypeDef = TypedDict(
+    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMFADevicesRequestRequestTypeDef = TypedDict(
     "ListMFADevicesRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -1975,14 +2367,40 @@
     {
         "UserName": str,
         "SerialNumber": str,
         "EnableDate": datetime,
     },
 )
 
+_RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
+        {
+            "OpenIDConnectProviderArn": str,
+        },
+    )
+)
+_OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef(
+    _RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
+    _OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListOpenIDConnectProviderTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListOpenIDConnectProviderTagsRequestRequestTypeDef",
     {
         "OpenIDConnectProviderArn": str,
     },
 )
 _OptionalListOpenIDConnectProviderTagsRequestRequestTypeDef = TypedDict(
@@ -2053,27 +2471,61 @@
 class ListPoliciesGrantingServiceAccessRequestRequestTypeDef(
     _RequiredListPoliciesGrantingServiceAccessRequestRequestTypeDef,
     _OptionalListPoliciesGrantingServiceAccessRequestRequestTypeDef,
 ):
     pass
 
 
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "Scope": policyScopeTypeType,
+        "OnlyAttached": bool,
+        "PathPrefix": str,
+        "PolicyUsageFilter": PolicyUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "Scope": policyScopeTypeType,
         "OnlyAttached": bool,
         "PathPrefix": str,
         "PolicyUsageFilter": PolicyUsageTypeType,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPolicyTagsRequestListPolicyTagsPaginateTypeDef(
+    _RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
+    _OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPolicyTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyTagsRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListPolicyTagsRequestRequestTypeDef = TypedDict(
@@ -2088,14 +2540,36 @@
 
 class ListPolicyTagsRequestRequestTypeDef(
     _RequiredListPolicyTagsRequestRequestTypeDef, _OptionalListPolicyTagsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef(
+    _RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
+    _OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPolicyVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyVersionsRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListPolicyVersionsRequestRequestTypeDef = TypedDict(
@@ -2111,14 +2585,36 @@
 class ListPolicyVersionsRequestRequestTypeDef(
     _RequiredListPolicyVersionsRequestRequestTypeDef,
     _OptionalListPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRolePoliciesRequestListRolePoliciesPaginateTypeDef(
+    _RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
+    _OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRolePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListRolePoliciesRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListRolePoliciesRequestRequestTypeDef = TypedDict(
@@ -2133,14 +2629,46 @@
 
 class ListRolePoliciesRequestRequestTypeDef(
     _RequiredListRolePoliciesRequestRequestTypeDef, _OptionalListRolePoliciesRequestRequestTypeDef
 ):
     pass
 
 
+ListRolePoliciesResponseTypeDef = TypedDict(
+    "ListRolePoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef = TypedDict(
+    "_RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef = TypedDict(
+    "_OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRoleTagsRequestListRoleTagsPaginateTypeDef(
+    _RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef,
+    _OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRoleTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListRoleTagsRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListRoleTagsRequestRequestTypeDef = TypedDict(
@@ -2155,24 +2683,55 @@
 
 class ListRoleTagsRequestRequestTypeDef(
     _RequiredListRoleTagsRequestRequestTypeDef, _OptionalListRoleTagsRequestRequestTypeDef
 ):
     pass
 
 
+ListRolesRequestListRolesPaginateTypeDef = TypedDict(
+    "ListRolesRequestListRolesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRolesRequestRequestTypeDef = TypedDict(
     "ListRolesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef = TypedDict(
+    "_RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
+    {
+        "SAMLProviderArn": str,
+    },
+)
+_OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef = TypedDict(
+    "_OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef(
+    _RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
+    _OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSAMLProviderTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListSAMLProviderTagsRequestRequestTypeDef",
     {
         "SAMLProviderArn": str,
     },
 )
 _OptionalListSAMLProviderTagsRequestRequestTypeDef = TypedDict(
@@ -2198,14 +2757,23 @@
         "Arn": str,
         "ValidUntil": datetime,
         "CreateDate": datetime,
     },
     total=False,
 )
 
+ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef = TypedDict(
+    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSSHPublicKeysRequestRequestTypeDef = TypedDict(
     "ListSSHPublicKeysRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2218,14 +2786,36 @@
         "UserName": str,
         "SSHPublicKeyId": str,
         "Status": statusTypeType,
         "UploadDate": datetime,
     },
 )
 
+_RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef = TypedDict(
+    "_RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
+    {
+        "ServerCertificateName": str,
+    },
+)
+_OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef = TypedDict(
+    "_OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef(
+    _RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
+    _OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServerCertificateTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListServerCertificateTagsRequestRequestTypeDef",
     {
         "ServerCertificateName": str,
     },
 )
 _OptionalListServerCertificateTagsRequestRequestTypeDef = TypedDict(
@@ -2241,14 +2831,23 @@
 class ListServerCertificateTagsRequestRequestTypeDef(
     _RequiredListServerCertificateTagsRequestRequestTypeDef,
     _OptionalListServerCertificateTagsRequestRequestTypeDef,
 ):
     pass
 
 
+ListServerCertificatesRequestListServerCertificatesPaginateTypeDef = TypedDict(
+    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServerCertificatesRequestRequestTypeDef = TypedDict(
     "ListServerCertificatesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2297,14 +2896,23 @@
         "ServiceUserName": str,
         "CreateDate": datetime,
         "ServiceSpecificCredentialId": str,
         "ServiceName": str,
     },
 )
 
+ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef = TypedDict(
+    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningCertificatesRequestRequestTypeDef = TypedDict(
     "ListSigningCertificatesRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2331,14 +2939,36 @@
 
 class SigningCertificateTypeDef(
     _RequiredSigningCertificateTypeDef, _OptionalSigningCertificateTypeDef
 ):
     pass
 
 
+_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUserPoliciesRequestListUserPoliciesPaginateTypeDef(
+    _RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
+    _OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUserPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListUserPoliciesRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListUserPoliciesRequestRequestTypeDef = TypedDict(
@@ -2353,14 +2983,46 @@
 
 class ListUserPoliciesRequestRequestTypeDef(
     _RequiredListUserPoliciesRequestRequestTypeDef, _OptionalListUserPoliciesRequestRequestTypeDef
 ):
     pass
 
 
+ListUserPoliciesResponseTypeDef = TypedDict(
+    "ListUserPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
+    "_RequiredListUserTagsRequestListUserTagsPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
+    "_OptionalListUserTagsRequestListUserTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUserTagsRequestListUserTagsPaginateTypeDef(
+    _RequiredListUserTagsRequestListUserTagsPaginateTypeDef,
+    _OptionalListUserTagsRequestListUserTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUserTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListUserTagsRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListUserTagsRequestRequestTypeDef = TypedDict(
@@ -2375,34 +3037,62 @@
 
 class ListUserTagsRequestRequestTypeDef(
     _RequiredListUserTagsRequestRequestTypeDef, _OptionalListUserTagsRequestRequestTypeDef
 ):
     pass
 
 
+ListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "ListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUsersRequestRequestTypeDef = TypedDict(
     "ListUsersRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef = TypedDict(
+    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
+    {
+        "AssignmentStatus": assignmentStatusTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualMFADevicesRequestRequestTypeDef = TypedDict(
     "ListVirtualMFADevicesRequestRequestTypeDef",
     {
         "AssignmentStatus": assignmentStatusTypeType,
         "Marker": str,
         "MaxItems": int,
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
 PositionTypeDef = TypedDict(
     "PositionTypeDef",
     {
         "Line": int,
         "Column": int,
     },
     total=False,
@@ -2551,14 +3241,25 @@
 class ResetServiceSpecificCredentialRequestRequestTypeDef(
     _RequiredResetServiceSpecificCredentialRequestRequestTypeDef,
     _OptionalResetServiceSpecificCredentialRequestRequestTypeDef,
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
 ResyncMFADeviceRequestMfaDeviceResyncTypeDef = TypedDict(
     "ResyncMFADeviceRequestMfaDeviceResyncTypeDef",
     {
         "AuthenticationCode1": str,
         "AuthenticationCode2": str,
     },
 )
@@ -2578,167 +3279,47 @@
     {
         "LastUsedDate": datetime,
         "Region": str,
     },
     total=False,
 )
 
-RolePolicyRequestTypeDef = TypedDict(
-    "RolePolicyRequestTypeDef",
+RoleLastUsedResponseMetadataTypeDef = TypedDict(
+    "RoleLastUsedResponseMetadataTypeDef",
     {
-        "name": str,
+        "LastUsedDate": datetime,
+        "Region": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ServerCertificateMetadataResponseMetadataTypeDef = TypedDict(
+    "ServerCertificateMetadataResponseMetadataTypeDef",
+    {
+        "Path": str,
+        "ServerCertificateName": str,
+        "ServerCertificateId": str,
+        "Arn": str,
+        "UploadDate": datetime,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrackedActionLastAccessedTypeDef = TypedDict(
     "TrackedActionLastAccessedTypeDef",
     {
         "ActionName": str,
         "LastAccessedEntity": str,
         "LastAccessedTime": datetime,
         "LastAccessedRegion": str,
     },
     total=False,
 )
 
-ServiceResourceAccessKeyPairRequestTypeDef = TypedDict(
-    "ServiceResourceAccessKeyPairRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-        "secret": str,
-    },
-)
-
-ServiceResourceAccessKeyRequestTypeDef = TypedDict(
-    "ServiceResourceAccessKeyRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceAssumeRolePolicyRequestTypeDef = TypedDict(
-    "ServiceResourceAssumeRolePolicyRequestTypeDef",
-    {
-        "role_name": str,
-    },
-)
-
-ServiceResourceGroupPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceGroupPolicyRequestTypeDef",
-    {
-        "group_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceGroupRequestTypeDef = TypedDict(
-    "ServiceResourceGroupRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceInstanceProfileRequestTypeDef = TypedDict(
-    "ServiceResourceInstanceProfileRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceLoginProfileRequestTypeDef = TypedDict(
-    "ServiceResourceLoginProfileRequestTypeDef",
-    {
-        "user_name": str,
-    },
-)
-
-ServiceResourceMfaDeviceRequestTypeDef = TypedDict(
-    "ServiceResourceMfaDeviceRequestTypeDef",
-    {
-        "user_name": str,
-        "serial_number": str,
-    },
-)
-
-ServiceResourcePolicyRequestTypeDef = TypedDict(
-    "ServiceResourcePolicyRequestTypeDef",
-    {
-        "policy_arn": str,
-    },
-)
-
-ServiceResourcePolicyVersionRequestTypeDef = TypedDict(
-    "ServiceResourcePolicyVersionRequestTypeDef",
-    {
-        "arn": str,
-        "version_id": str,
-    },
-)
-
-ServiceResourceRolePolicyRequestTypeDef = TypedDict(
-    "ServiceResourceRolePolicyRequestTypeDef",
-    {
-        "role_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceRoleRequestTypeDef = TypedDict(
-    "ServiceResourceRoleRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceSamlProviderRequestTypeDef = TypedDict(
-    "ServiceResourceSamlProviderRequestTypeDef",
-    {
-        "arn": str,
-    },
-)
-
-ServiceResourceServerCertificateRequestTypeDef = TypedDict(
-    "ServiceResourceServerCertificateRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceSigningCertificateRequestTypeDef = TypedDict(
-    "ServiceResourceSigningCertificateRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceUserPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceUserPolicyRequestTypeDef",
-    {
-        "user_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceUserRequestTypeDef = TypedDict(
-    "ServiceResourceUserRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceVirtualMfaDeviceRequestTypeDef = TypedDict(
-    "ServiceResourceVirtualMfaDeviceRequestTypeDef",
-    {
-        "serial_number": str,
-    },
-)
-
 SetDefaultPolicyVersionRequestRequestTypeDef = TypedDict(
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     {
         "PolicyArn": str,
         "VersionId": str,
     },
 )
@@ -3043,14 +3624,22 @@
 UpdateSAMLProviderRequestSamlProviderUpdateTypeDef = TypedDict(
     "UpdateSAMLProviderRequestSamlProviderUpdateTypeDef",
     {
         "SAMLMetadataDocument": str,
     },
 )
 
+UpdateSAMLProviderResponseTypeDef = TypedDict(
+    "UpdateSAMLProviderResponseTypeDef",
+    {
+        "SAMLProviderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSSHPublicKeyRequestRequestTypeDef = TypedDict(
     "UpdateSSHPublicKeyRequestRequestTypeDef",
     {
         "UserName": str,
         "SSHPublicKeyId": str,
         "Status": statusTypeType,
     },
@@ -3229,271 +3818,68 @@
 class UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef(
     _RequiredUploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
     _OptionalUploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
 ):
     pass
 
 
-UserAccessKeyRequestTypeDef = TypedDict(
-    "UserAccessKeyRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-UserMfaDeviceRequestTypeDef = TypedDict(
-    "UserMfaDeviceRequestTypeDef",
-    {
-        "serial_number": str,
-    },
-)
-
-UserPolicyRequestTypeDef = TypedDict(
-    "UserPolicyRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-UserSigningCertificateRequestTypeDef = TypedDict(
-    "UserSigningCertificateRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-AttachedPermissionsBoundaryResponseMetadataTypeDef = TypedDict(
-    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
-    {
-        "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
-        "PermissionsBoundaryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessKeyResponseTypeDef = TypedDict(
-    "CreateAccessKeyResponseTypeDef",
-    {
-        "AccessKey": AccessKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteServiceLinkedRoleResponseTypeDef = TypedDict(
-    "DeleteServiceLinkedRoleResponseTypeDef",
-    {
-        "DeletionTaskId": str,
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
-GenerateCredentialReportResponseTypeDef = TypedDict(
-    "GenerateCredentialReportResponseTypeDef",
-    {
-        "State": ReportStateTypeType,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateOrganizationsAccessReportResponseTypeDef = TypedDict(
-    "GenerateOrganizationsAccessReportResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateServiceLastAccessedDetailsResponseTypeDef = TypedDict(
-    "GenerateServiceLastAccessedDetailsResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetAccessKeyLastUsedResponseTypeDef = TypedDict(
     "GetAccessKeyLastUsedResponseTypeDef",
     {
         "UserName": str,
         "AccessKeyLastUsed": AccessKeyLastUsedTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSummaryResponseTypeDef = TypedDict(
-    "GetAccountSummaryResponseTypeDef",
-    {
-        "SummaryMap": Dict[summaryKeyTypeType, int],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContextKeysForPolicyResponseTypeDef = TypedDict(
-    "GetContextKeysForPolicyResponseTypeDef",
-    {
-        "ContextKeyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCredentialReportResponseTypeDef = TypedDict(
-    "GetCredentialReportResponseTypeDef",
-    {
-        "Content": bytes,
-        "ReportFormat": Literal["text/csv"],
-        "GeneratedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupPolicyResponseTypeDef = TypedDict(
-    "GetGroupPolicyResponseTypeDef",
-    {
-        "GroupName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRolePolicyResponseTypeDef = TypedDict(
-    "GetRolePolicyResponseTypeDef",
-    {
-        "RoleName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserPolicyResponseTypeDef = TypedDict(
-    "GetUserPolicyResponseTypeDef",
-    {
-        "UserName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccessKeysResponseTypeDef = TypedDict(
     "ListAccessKeysResponseTypeDef",
     {
         "AccessKeyMetadata": List[AccessKeyMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAliasesResponseTypeDef = TypedDict(
-    "ListAccountAliasesResponseTypeDef",
-    {
-        "AccountAliases": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGroupPoliciesResponseTypeDef = TypedDict(
-    "ListGroupPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRolePoliciesResponseTypeDef = TypedDict(
-    "ListRolePoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListUserPoliciesResponseTypeDef = TypedDict(
-    "ListUserPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RoleLastUsedResponseMetadataTypeDef = TypedDict(
-    "RoleLastUsedResponseMetadataTypeDef",
-    {
-        "LastUsedDate": datetime,
-        "Region": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ServerCertificateMetadataResponseMetadataTypeDef = TypedDict(
-    "ServerCertificateMetadataResponseMetadataTypeDef",
-    {
-        "Path": str,
-        "ServerCertificateName": str,
-        "ServerCertificateId": str,
-        "Arn": str,
-        "UploadDate": datetime,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSAMLProviderResponseTypeDef = TypedDict(
-    "UpdateSAMLProviderResponseTypeDef",
+CreateAccessKeyResponseTypeDef = TypedDict(
+    "CreateAccessKeyResponseTypeDef",
     {
-        "SAMLProviderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AccessKey": AccessKeyTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedGroupPoliciesResponseTypeDef = TypedDict(
     "ListAttachedGroupPoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedRolePoliciesResponseTypeDef = TypedDict(
     "ListAttachedRolePoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedUserPoliciesResponseTypeDef = TypedDict(
     "ListAttachedUserPoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSimulateCustomPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSimulateCustomPolicyRequestRequestTypeDef",
     {
         "PolicyInputList": Sequence[str],
@@ -3520,14 +3906,44 @@
 class SimulateCustomPolicyRequestRequestTypeDef(
     _RequiredSimulateCustomPolicyRequestRequestTypeDef,
     _OptionalSimulateCustomPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
+    "_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
+    {
+        "PolicyInputList": Sequence[str],
+        "ActionNames": Sequence[str],
+    },
+)
+_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
+    "_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
+    {
+        "PermissionsBoundaryPolicyInputList": Sequence[str],
+        "ResourceArns": Sequence[str],
+        "ResourcePolicy": str,
+        "ResourceOwner": str,
+        "CallerArn": str,
+        "ContextEntries": Sequence[ContextEntryTypeDef],
+        "ResourceHandlingOption": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef(
+    _RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
+    _OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
+):
+    pass
+
+
 _RequiredSimulatePrincipalPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSimulatePrincipalPolicyRequestRequestTypeDef",
     {
         "PolicySourceArn": str,
         "ActionNames": Sequence[str],
     },
 )
@@ -3552,39 +3968,70 @@
 class SimulatePrincipalPolicyRequestRequestTypeDef(
     _RequiredSimulatePrincipalPolicyRequestRequestTypeDef,
     _OptionalSimulatePrincipalPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
+    "_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
+    {
+        "PolicySourceArn": str,
+        "ActionNames": Sequence[str],
+    },
+)
+_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
+    "_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
+    {
+        "PolicyInputList": Sequence[str],
+        "PermissionsBoundaryPolicyInputList": Sequence[str],
+        "ResourceArns": Sequence[str],
+        "ResourcePolicy": str,
+        "ResourceOwner": str,
+        "CallerArn": str,
+        "ContextEntries": Sequence[ContextEntryTypeDef],
+        "ResourceHandlingOption": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef(
+    _RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
+    _OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
+):
+    pass
+
+
 CreateGroupResponseTypeDef = TypedDict(
     "CreateGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsForUserResponseTypeDef = TypedDict(
     "ListGroupsForUserResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateInstanceProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceProfileRequestRequestTypeDef",
     {
         "InstanceProfileName": str,
@@ -3655,15 +4102,15 @@
 
 
 CreateOpenIDConnectProviderResponseTypeDef = TypedDict(
     "CreateOpenIDConnectProviderResponseTypeDef",
     {
         "OpenIDConnectProviderArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
@@ -3812,15 +4259,15 @@
 
 
 CreateSAMLProviderResponseTypeDef = TypedDict(
     "CreateSAMLProviderResponseTypeDef",
     {
         "SAMLProviderArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "UserName": str,
@@ -3927,106 +4374,106 @@
     "GetOpenIDConnectProviderResponseTypeDef",
     {
         "Url": str,
         "ClientIDList": List[str],
         "ThumbprintList": List[str],
         "CreateDate": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSAMLProviderResponseTypeDef = TypedDict(
     "GetSAMLProviderResponseTypeDef",
     {
         "SAMLMetadataDocument": str,
         "CreateDate": datetime,
         "ValidUntil": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfileTagsResponseTypeDef = TypedDict(
     "ListInstanceProfileTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMFADeviceTagsResponseTypeDef = TypedDict(
     "ListMFADeviceTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpenIDConnectProviderTagsResponseTypeDef = TypedDict(
     "ListOpenIDConnectProviderTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyTagsResponseTypeDef = TypedDict(
     "ListPolicyTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoleTagsResponseTypeDef = TypedDict(
     "ListRoleTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSAMLProviderTagsResponseTypeDef = TypedDict(
     "ListSAMLProviderTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServerCertificateTagsResponseTypeDef = TypedDict(
     "ListServerCertificateTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserTagsResponseTypeDef = TypedDict(
     "ListUserTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyTypeDef = TypedDict(
     "PolicyTypeDef",
     {
         "PolicyName": str,
@@ -4168,15 +4615,15 @@
         "UserName": str,
         "UserId": str,
         "Arn": str,
         "CreateDate": datetime,
         "PasswordLastUsed": datetime,
         "PermissionsBoundary": AttachedPermissionsBoundaryTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUserTypeDef = TypedDict(
     "_RequiredUserTypeDef",
     {
         "Path": str,
@@ -4201,49 +4648,49 @@
     pass
 
 
 CreateLoginProfileResponseTypeDef = TypedDict(
     "CreateLoginProfileResponseTypeDef",
     {
         "LoginProfile": LoginProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoginProfileResponseTypeDef = TypedDict(
     "GetLoginProfileResponseTypeDef",
     {
         "LoginProfile": LoginProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePolicyVersionResponseTypeDef = TypedDict(
     "CreatePolicyVersionResponseTypeDef",
     {
         "PolicyVersion": PolicyVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPolicyVersionResponseTypeDef = TypedDict(
     "GetPolicyVersionResponseTypeDef",
     {
         "PolicyVersion": PolicyVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyVersionsResponseTypeDef = TypedDict(
     "ListPolicyVersionsResponseTypeDef",
     {
         "Versions": List[PolicyVersionTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ManagedPolicyDetailTypeDef = TypedDict(
     "ManagedPolicyDetailTypeDef",
     {
         "PolicyName": str,
@@ -4262,23 +4709,23 @@
     total=False,
 )
 
 CreateServiceSpecificCredentialResponseTypeDef = TypedDict(
     "CreateServiceSpecificCredentialResponseTypeDef",
     {
         "ServiceSpecificCredential": ServiceSpecificCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetServiceSpecificCredentialResponseTypeDef = TypedDict(
     "ResetServiceSpecificCredentialResponseTypeDef",
     {
         "ServiceSpecificCredential": ServiceSpecificCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletionTaskFailureReasonTypeTypeDef = TypedDict(
     "DeletionTaskFailureReasonTypeTypeDef",
     {
         "Reason": str,
@@ -4314,472 +4761,23 @@
         "JobCompletionDate": datetime,
         "NumberOfServicesAccessible": int,
         "NumberOfServicesNotAccessed": int,
         "AccessDetails": List[AccessDetailTypeDef],
         "IsTruncated": bool,
         "Marker": str,
         "ErrorDetails": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef = TypedDict(
-    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
-    {
-        "Filter": Sequence[EntityTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
-    "_RequiredGetGroupRequestGetGroupPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
-    "_OptionalGetGroupRequestGetGroupPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetGroupRequestGetGroupPaginateTypeDef(
-    _RequiredGetGroupRequestGetGroupPaginateTypeDef, _OptionalGetGroupRequestGetGroupPaginateTypeDef
-):
-    pass
-
-
-ListAccessKeysRequestListAccessKeysPaginateTypeDef = TypedDict(
-    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAccountAliasesRequestListAccountAliasesPaginateTypeDef = TypedDict(
-    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef(
-    _RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-    _OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef(
-    _RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-    _OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef(
-    _RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-    _OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    {
-        "PolicyArn": str,
-    },
-)
-_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    {
-        "EntityFilter": EntityTypeType,
-        "PathPrefix": str,
-        "PolicyUsageFilter": PolicyUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef(
-    _RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-    _OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef(
-    _RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-    _OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGroupsForUserRequestListGroupsForUserPaginateTypeDef(
-    _RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-    _OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-):
-    pass
-
-
-ListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
-    "_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
-    "_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef(
-    _RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-    _OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-):
-    pass
-
-
-ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMFADevicesRequestListMFADevicesPaginateTypeDef = TypedDict(
-    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "Scope": policyScopeTypeType,
-        "OnlyAttached": bool,
-        "PathPrefix": str,
-        "PolicyUsageFilter": PolicyUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    {
-        "PolicyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef(
-    _RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-    _OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRolePoliciesRequestListRolePoliciesPaginateTypeDef(
-    _RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-    _OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-):
-    pass
-
-
-ListRolesRequestListRolesPaginateTypeDef = TypedDict(
-    "ListRolesRequestListRolesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef = TypedDict(
-    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServerCertificatesRequestListServerCertificatesPaginateTypeDef = TypedDict(
-    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef = TypedDict(
-    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUserPoliciesRequestListUserPoliciesPaginateTypeDef(
-    _RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-    _OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
-    "_RequiredListUserTagsRequestListUserTagsPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
-    "_OptionalListUserTagsRequestListUserTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUserTagsRequestListUserTagsPaginateTypeDef(
-    _RequiredListUserTagsRequestListUserTagsPaginateTypeDef,
-    _OptionalListUserTagsRequestListUserTagsPaginateTypeDef,
-):
-    pass
-
-
-ListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "ListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef = TypedDict(
-    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
-    {
-        "AssignmentStatus": assignmentStatusTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
-    "_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    {
-        "PolicyInputList": Sequence[str],
-        "ActionNames": Sequence[str],
-    },
-)
-_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
-    "_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    {
-        "PermissionsBoundaryPolicyInputList": Sequence[str],
-        "ResourceArns": Sequence[str],
-        "ResourcePolicy": str,
-        "ResourceOwner": str,
-        "CallerArn": str,
-        "ContextEntries": Sequence[ContextEntryTypeDef],
-        "ResourceHandlingOption": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef(
-    _RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-    _OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-):
-    pass
-
-
-_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
-    "_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
-    {
-        "PolicySourceArn": str,
-        "ActionNames": Sequence[str],
-    },
-)
-_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
-    "_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
-    {
-        "PolicyInputList": Sequence[str],
-        "PermissionsBoundaryPolicyInputList": Sequence[str],
-        "ResourceArns": Sequence[str],
-        "ResourcePolicy": str,
-        "ResourceOwner": str,
-        "CallerArn": str,
-        "ContextEntries": Sequence[ContextEntryTypeDef],
-        "ResourceHandlingOption": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef(
-    _RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
-    _OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
-):
-    pass
-
 
 GetAccountPasswordPolicyResponseTypeDef = TypedDict(
     "GetAccountPasswordPolicyResponseTypeDef",
     {
         "PasswordPolicy": PasswordPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetInstanceProfileRequestInstanceProfileExistsWaitTypeDef = TypedDict(
     "_RequiredGetInstanceProfileRequestInstanceProfileExistsWaitTypeDef",
     {
         "InstanceProfileName": str,
@@ -4853,23 +4851,23 @@
     total=False,
 )
 
 GetSSHPublicKeyResponseTypeDef = TypedDict(
     "GetSSHPublicKeyResponseTypeDef",
     {
         "SSHPublicKey": SSHPublicKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadSSHPublicKeyResponseTypeDef = TypedDict(
     "UploadSSHPublicKeyResponseTypeDef",
     {
         "SSHPublicKey": SSHPublicKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GroupDetailTypeDef = TypedDict(
     "GroupDetailTypeDef",
     {
         "Path": str,
@@ -4904,33 +4902,33 @@
     "ListEntitiesForPolicyResponseTypeDef",
     {
         "PolicyGroups": List[PolicyGroupTypeDef],
         "PolicyUsers": List[PolicyUserTypeDef],
         "PolicyRoles": List[PolicyRoleTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMFADevicesResponseTypeDef = TypedDict(
     "ListMFADevicesResponseTypeDef",
     {
         "MFADevices": List[MFADeviceTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpenIDConnectProvidersResponseTypeDef = TypedDict(
     "ListOpenIDConnectProvidersResponseTypeDef",
     {
         "OpenIDConnectProviderList": List[OpenIDConnectProviderListEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesGrantingServiceAccessEntryTypeDef = TypedDict(
     "ListPoliciesGrantingServiceAccessEntryTypeDef",
     {
         "ServiceNamespace": str,
@@ -4939,35 +4937,35 @@
     total=False,
 )
 
 ListSAMLProvidersResponseTypeDef = TypedDict(
     "ListSAMLProvidersResponseTypeDef",
     {
         "SAMLProviderList": List[SAMLProviderListEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSSHPublicKeysResponseTypeDef = TypedDict(
     "ListSSHPublicKeysResponseTypeDef",
     {
         "SSHPublicKeys": List[SSHPublicKeyMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServerCertificatesResponseTypeDef = TypedDict(
     "ListServerCertificatesResponseTypeDef",
     {
         "ServerCertificateMetadataList": List[ServerCertificateMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredServerCertificateTypeDef = TypedDict(
     "_RequiredServerCertificateTypeDef",
     {
         "ServerCertificateMetadata": ServerCertificateMetadataTypeDef,
@@ -4991,41 +4989,41 @@
 
 
 UploadServerCertificateResponseTypeDef = TypedDict(
     "UploadServerCertificateResponseTypeDef",
     {
         "ServerCertificateMetadata": ServerCertificateMetadataTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceSpecificCredentialsResponseTypeDef = TypedDict(
     "ListServiceSpecificCredentialsResponseTypeDef",
     {
         "ServiceSpecificCredentials": List[ServiceSpecificCredentialMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSigningCertificatesResponseTypeDef = TypedDict(
     "ListSigningCertificatesResponseTypeDef",
     {
         "Certificates": List[SigningCertificateTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadSigningCertificateResponseTypeDef = TypedDict(
     "UploadSigningCertificateResponseTypeDef",
     {
         "Certificate": SigningCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatementTypeDef = TypedDict(
     "StatementTypeDef",
     {
         "SourcePolicyId": str,
@@ -5090,70 +5088,70 @@
     pass
 
 
 CreatePolicyResponseTypeDef = TypedDict(
     "CreatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "Policies": List[PolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResponseTypeDef = TypedDict(
     "GetGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
         "Users": List[UserTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserResponseTypeDef = TypedDict(
     "GetUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVirtualMFADeviceTypeDef = TypedDict(
     "_RequiredVirtualMFADeviceTypeDef",
     {
         "SerialNumber": str,
@@ -5177,47 +5175,47 @@
 
 
 GetServiceLinkedRoleDeletionStatusResponseTypeDef = TypedDict(
     "GetServiceLinkedRoleDeletionStatusResponseTypeDef",
     {
         "Status": DeletionTaskStatusTypeType,
         "Reason": DeletionTaskFailureReasonTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef = TypedDict(
     "GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef",
     {
         "JobStatus": jobStatusTypeType,
         "JobCreationDate": datetime,
         "JobCompletionDate": datetime,
         "EntityDetailsList": List[EntityDetailsTypeDef],
         "IsTruncated": bool,
         "Marker": str,
         "Error": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesGrantingServiceAccessResponseTypeDef = TypedDict(
     "ListPoliciesGrantingServiceAccessResponseTypeDef",
     {
         "PoliciesGrantingServiceAccess": List[ListPoliciesGrantingServiceAccessEntryTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerCertificateResponseTypeDef = TypedDict(
     "GetServerCertificateResponseTypeDef",
     {
         "ServerCertificate": ServerCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceSpecificResultTypeDef = TypedDict(
     "_RequiredResourceSpecificResultTypeDef",
     {
         "EvalResourceName": str,
@@ -5242,31 +5240,31 @@
     pass
 
 
 CreateRoleResponseTypeDef = TypedDict(
     "CreateRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceLinkedRoleResponseTypeDef = TypedDict(
     "CreateServiceLinkedRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleResponseTypeDef = TypedDict(
     "GetRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInstanceProfileTypeDef = TypedDict(
     "_RequiredInstanceProfileTypeDef",
     {
         "Path": str,
@@ -5292,56 +5290,56 @@
 
 ListRolesResponseTypeDef = TypedDict(
     "ListRolesResponseTypeDef",
     {
         "Roles": List[RoleTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoleDescriptionResponseTypeDef = TypedDict(
     "UpdateRoleDescriptionResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceLastAccessedDetailsResponseTypeDef = TypedDict(
     "GetServiceLastAccessedDetailsResponseTypeDef",
     {
         "JobStatus": jobStatusTypeType,
         "JobType": AccessAdvisorUsageGranularityTypeType,
         "JobCreationDate": datetime,
         "ServicesLastAccessed": List[ServiceLastAccessedTypeDef],
         "JobCompletionDate": datetime,
         "IsTruncated": bool,
         "Marker": str,
         "Error": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVirtualMFADeviceResponseTypeDef = TypedDict(
     "CreateVirtualMFADeviceResponseTypeDef",
     {
         "VirtualMFADevice": VirtualMFADeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualMFADevicesResponseTypeDef = TypedDict(
     "ListVirtualMFADevicesResponseTypeDef",
     {
         "VirtualMFADevices": List[VirtualMFADeviceTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEvaluationResultTypeDef = TypedDict(
     "_RequiredEvaluationResultTypeDef",
     {
         "EvalActionName": str,
@@ -5367,43 +5365,43 @@
     pass
 
 
 CreateInstanceProfileResponseTypeDef = TypedDict(
     "CreateInstanceProfileResponseTypeDef",
     {
         "InstanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceProfileResponseTypeDef = TypedDict(
     "GetInstanceProfileResponseTypeDef",
     {
         "InstanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesForRoleResponseTypeDef = TypedDict(
     "ListInstanceProfilesForRoleResponseTypeDef",
     {
         "InstanceProfiles": List[InstanceProfileTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesResponseTypeDef = TypedDict(
     "ListInstanceProfilesResponseTypeDef",
     {
         "InstanceProfiles": List[InstanceProfileTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RoleDetailTypeDef = TypedDict(
     "RoleDetailTypeDef",
     {
         "Path": str,
@@ -5424,23 +5422,23 @@
 
 SimulatePolicyResponseTypeDef = TypedDict(
     "SimulatePolicyResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountAuthorizationDetailsResponseTypeDef = TypedDict(
     "GetAccountAuthorizationDetailsResponseTypeDef",
     {
         "UserDetailList": List[UserDetailTypeDef],
         "GroupDetailList": List[GroupDetailTypeDef],
         "RoleDetailList": List[RoleDetailTypeDef],
         "Policies": List[ManagedPolicyDetailTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/type_defs.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/type_defs.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -61,15 +61,15 @@
     "AttachGroupPolicyRequestRequestTypeDef",
     "AttachRolePolicyRequestPolicyAttachRoleTypeDef",
     "AttachRolePolicyRequestRequestTypeDef",
     "AttachRolePolicyRequestRoleAttachPolicyTypeDef",
     "AttachUserPolicyRequestPolicyAttachUserTypeDef",
     "AttachUserPolicyRequestRequestTypeDef",
     "AttachUserPolicyRequestUserAttachPolicyTypeDef",
-    "ResponseMetadataTypeDef",
+    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
     "AttachedPermissionsBoundaryTypeDef",
     "AttachedPolicyTypeDef",
     "ChangePasswordRequestRequestTypeDef",
     "ChangePasswordRequestServiceResourceChangePasswordTypeDef",
     "ContextEntryTypeDef",
     "CreateAccessKeyRequestRequestTypeDef",
     "CreateAccountAliasRequestRequestTypeDef",
@@ -102,14 +102,15 @@
     "DeleteRolePermissionsBoundaryRequestRequestTypeDef",
     "DeleteRolePolicyRequestRequestTypeDef",
     "DeleteRoleRequestRequestTypeDef",
     "DeleteSAMLProviderRequestRequestTypeDef",
     "DeleteSSHPublicKeyRequestRequestTypeDef",
     "DeleteServerCertificateRequestRequestTypeDef",
     "DeleteServiceLinkedRoleRequestRequestTypeDef",
+    "DeleteServiceLinkedRoleResponseTypeDef",
     "DeleteServiceSpecificCredentialRequestRequestTypeDef",
     "DeleteSigningCertificateRequestRequestTypeDef",
     "DeleteUserPermissionsBoundaryRequestRequestTypeDef",
     "DeleteUserPolicyRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DeleteVirtualMFADeviceRequestRequestTypeDef",
     "RoleUsageTypeTypeDef",
@@ -118,94 +119,141 @@
     "DetachGroupPolicyRequestRequestTypeDef",
     "DetachRolePolicyRequestPolicyDetachRoleTypeDef",
     "DetachRolePolicyRequestRequestTypeDef",
     "DetachRolePolicyRequestRoleDetachPolicyTypeDef",
     "DetachUserPolicyRequestPolicyDetachUserTypeDef",
     "DetachUserPolicyRequestRequestTypeDef",
     "DetachUserPolicyRequestUserDetachPolicyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableMFADeviceRequestMfaDeviceAssociateTypeDef",
     "EnableMFADeviceRequestRequestTypeDef",
     "EnableMFADeviceRequestUserEnableMfaTypeDef",
     "EntityInfoTypeDef",
     "ErrorDetailsTypeDef",
     "OrganizationsDecisionDetailTypeDef",
     "PermissionsBoundaryDecisionDetailTypeDef",
+    "GenerateCredentialReportResponseTypeDef",
     "GenerateOrganizationsAccessReportRequestRequestTypeDef",
+    "GenerateOrganizationsAccessReportResponseTypeDef",
     "GenerateServiceLastAccessedDetailsRequestRequestTypeDef",
+    "GenerateServiceLastAccessedDetailsResponseTypeDef",
     "GetAccessKeyLastUsedRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
     "GetAccountAuthorizationDetailsRequestRequestTypeDef",
     "PasswordPolicyTypeDef",
+    "GetAccountSummaryResponseTypeDef",
     "GetContextKeysForCustomPolicyRequestRequestTypeDef",
+    "GetContextKeysForPolicyResponseTypeDef",
     "GetContextKeysForPrincipalPolicyRequestRequestTypeDef",
+    "GetCredentialReportResponseTypeDef",
     "GetGroupPolicyRequestRequestTypeDef",
+    "GetGroupPolicyResponseTypeDef",
+    "GetGroupRequestGetGroupPaginateTypeDef",
     "GetGroupRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "GetInstanceProfileRequestRequestTypeDef",
     "GetLoginProfileRequestRequestTypeDef",
+    "GetMFADeviceRequestRequestTypeDef",
+    "GetMFADeviceResponseTypeDef",
     "GetOpenIDConnectProviderRequestRequestTypeDef",
     "GetOrganizationsAccessReportRequestRequestTypeDef",
     "GetPolicyRequestRequestTypeDef",
     "GetPolicyVersionRequestRequestTypeDef",
     "GetRolePolicyRequestRequestTypeDef",
+    "GetRolePolicyResponseTypeDef",
     "GetRoleRequestRequestTypeDef",
     "GetSAMLProviderRequestRequestTypeDef",
     "GetSSHPublicKeyRequestRequestTypeDef",
     "SSHPublicKeyTypeDef",
     "GetServerCertificateRequestRequestTypeDef",
     "GetServiceLastAccessedDetailsRequestRequestTypeDef",
     "GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef",
     "GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef",
     "GetUserPolicyRequestRequestTypeDef",
+    "GetUserPolicyResponseTypeDef",
     "GetUserRequestRequestTypeDef",
     "PolicyDetailTypeDef",
-    "GroupPolicyRequestTypeDef",
+    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
     "ListAccessKeysRequestRequestTypeDef",
+    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
     "ListAccountAliasesRequestRequestTypeDef",
+    "ListAccountAliasesResponseTypeDef",
+    "ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
     "ListAttachedGroupPoliciesRequestRequestTypeDef",
+    "ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
     "ListAttachedRolePoliciesRequestRequestTypeDef",
+    "ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
     "ListAttachedUserPoliciesRequestRequestTypeDef",
+    "ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
     "ListEntitiesForPolicyRequestRequestTypeDef",
     "PolicyGroupTypeDef",
     "PolicyRoleTypeDef",
     "PolicyUserTypeDef",
+    "ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
     "ListGroupPoliciesRequestRequestTypeDef",
+    "ListGroupPoliciesResponseTypeDef",
+    "ListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
     "ListGroupsForUserRequestRequestTypeDef",
+    "ListGroupsRequestListGroupsPaginateTypeDef",
     "ListGroupsRequestRequestTypeDef",
+    "ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
     "ListInstanceProfileTagsRequestRequestTypeDef",
+    "ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
     "ListInstanceProfilesForRoleRequestRequestTypeDef",
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
     "ListInstanceProfilesRequestRequestTypeDef",
+    "ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
     "ListMFADeviceTagsRequestRequestTypeDef",
+    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
     "ListMFADevicesRequestRequestTypeDef",
     "MFADeviceTypeDef",
+    "ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
     "ListOpenIDConnectProviderTagsRequestRequestTypeDef",
     "OpenIDConnectProviderListEntryTypeDef",
     "PolicyGrantingServiceAccessTypeDef",
     "ListPoliciesGrantingServiceAccessRequestRequestTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
     "ListPolicyTagsRequestRequestTypeDef",
+    "ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
     "ListPolicyVersionsRequestRequestTypeDef",
+    "ListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
     "ListRolePoliciesRequestRequestTypeDef",
+    "ListRolePoliciesResponseTypeDef",
+    "ListRoleTagsRequestListRoleTagsPaginateTypeDef",
     "ListRoleTagsRequestRequestTypeDef",
+    "ListRolesRequestListRolesPaginateTypeDef",
     "ListRolesRequestRequestTypeDef",
+    "ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
     "ListSAMLProviderTagsRequestRequestTypeDef",
     "SAMLProviderListEntryTypeDef",
+    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
     "ListSSHPublicKeysRequestRequestTypeDef",
     "SSHPublicKeyMetadataTypeDef",
+    "ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
     "ListServerCertificateTagsRequestRequestTypeDef",
+    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
     "ListServerCertificatesRequestRequestTypeDef",
     "ServerCertificateMetadataTypeDef",
     "ListServiceSpecificCredentialsRequestRequestTypeDef",
     "ServiceSpecificCredentialMetadataTypeDef",
+    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
     "ListSigningCertificatesRequestRequestTypeDef",
     "SigningCertificateTypeDef",
+    "ListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
     "ListUserPoliciesRequestRequestTypeDef",
+    "ListUserPoliciesResponseTypeDef",
+    "ListUserTagsRequestListUserTagsPaginateTypeDef",
     "ListUserTagsRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
+    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
     "ListVirtualMFADevicesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PositionTypeDef",
     "PutGroupPolicyRequestGroupCreatePolicyTypeDef",
     "PutGroupPolicyRequestGroupPolicyPutTypeDef",
     "PutGroupPolicyRequestRequestTypeDef",
     "PutRolePermissionsBoundaryRequestRequestTypeDef",
     "PutRolePolicyRequestRequestTypeDef",
     "PutRolePolicyRequestRolePolicyPutTypeDef",
@@ -216,37 +264,21 @@
     "RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef",
     "RemoveRoleFromInstanceProfileRequestInstanceProfileRemoveRoleTypeDef",
     "RemoveRoleFromInstanceProfileRequestRequestTypeDef",
     "RemoveUserFromGroupRequestGroupRemoveUserTypeDef",
     "RemoveUserFromGroupRequestRequestTypeDef",
     "RemoveUserFromGroupRequestUserRemoveGroupTypeDef",
     "ResetServiceSpecificCredentialRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResyncMFADeviceRequestMfaDeviceResyncTypeDef",
     "ResyncMFADeviceRequestRequestTypeDef",
     "RoleLastUsedTypeDef",
-    "RolePolicyRequestTypeDef",
+    "RoleLastUsedResponseMetadataTypeDef",
+    "ServerCertificateMetadataResponseMetadataTypeDef",
     "TrackedActionLastAccessedTypeDef",
-    "ServiceResourceAccessKeyPairRequestTypeDef",
-    "ServiceResourceAccessKeyRequestTypeDef",
-    "ServiceResourceAssumeRolePolicyRequestTypeDef",
-    "ServiceResourceGroupPolicyRequestTypeDef",
-    "ServiceResourceGroupRequestTypeDef",
-    "ServiceResourceInstanceProfileRequestTypeDef",
-    "ServiceResourceLoginProfileRequestTypeDef",
-    "ServiceResourceMfaDeviceRequestTypeDef",
-    "ServiceResourcePolicyRequestTypeDef",
-    "ServiceResourcePolicyVersionRequestTypeDef",
-    "ServiceResourceRolePolicyRequestTypeDef",
-    "ServiceResourceRoleRequestTypeDef",
-    "ServiceResourceSamlProviderRequestTypeDef",
-    "ServiceResourceServerCertificateRequestTypeDef",
-    "ServiceResourceSigningCertificateRequestTypeDef",
-    "ServiceResourceUserPolicyRequestTypeDef",
-    "ServiceResourceUserRequestTypeDef",
-    "ServiceResourceVirtualMfaDeviceRequestTypeDef",
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     "SetSecurityTokenServicePreferencesRequestRequestTypeDef",
     "UntagInstanceProfileRequestRequestTypeDef",
     "UntagMFADeviceRequestRequestTypeDef",
     "UntagOpenIDConnectProviderRequestRequestTypeDef",
     "UntagPolicyRequestRequestTypeDef",
     "UntagRoleRequestRequestTypeDef",
@@ -268,57 +300,37 @@
     "UpdateLoginProfileRequestLoginProfileUpdateTypeDef",
     "UpdateLoginProfileRequestRequestTypeDef",
     "UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef",
     "UpdateRoleDescriptionRequestRequestTypeDef",
     "UpdateRoleRequestRequestTypeDef",
     "UpdateSAMLProviderRequestRequestTypeDef",
     "UpdateSAMLProviderRequestSamlProviderUpdateTypeDef",
+    "UpdateSAMLProviderResponseTypeDef",
     "UpdateSSHPublicKeyRequestRequestTypeDef",
     "UpdateServerCertificateRequestRequestTypeDef",
     "UpdateServerCertificateRequestServerCertificateUpdateTypeDef",
     "UpdateServiceSpecificCredentialRequestRequestTypeDef",
     "UpdateSigningCertificateRequestRequestTypeDef",
     "UpdateSigningCertificateRequestSigningCertificateActivateTypeDef",
     "UpdateSigningCertificateRequestSigningCertificateDeactivateTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UpdateUserRequestUserUpdateTypeDef",
     "UploadSSHPublicKeyRequestRequestTypeDef",
     "UploadSigningCertificateRequestRequestTypeDef",
     "UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef",
-    "UserAccessKeyRequestTypeDef",
-    "UserMfaDeviceRequestTypeDef",
-    "UserPolicyRequestTypeDef",
-    "UserSigningCertificateRequestTypeDef",
-    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
-    "CreateAccessKeyResponseTypeDef",
-    "DeleteServiceLinkedRoleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GenerateCredentialReportResponseTypeDef",
-    "GenerateOrganizationsAccessReportResponseTypeDef",
-    "GenerateServiceLastAccessedDetailsResponseTypeDef",
     "GetAccessKeyLastUsedResponseTypeDef",
-    "GetAccountSummaryResponseTypeDef",
-    "GetContextKeysForPolicyResponseTypeDef",
-    "GetCredentialReportResponseTypeDef",
-    "GetGroupPolicyResponseTypeDef",
-    "GetRolePolicyResponseTypeDef",
-    "GetUserPolicyResponseTypeDef",
     "ListAccessKeysResponseTypeDef",
-    "ListAccountAliasesResponseTypeDef",
-    "ListGroupPoliciesResponseTypeDef",
-    "ListRolePoliciesResponseTypeDef",
-    "ListUserPoliciesResponseTypeDef",
-    "RoleLastUsedResponseMetadataTypeDef",
-    "ServerCertificateMetadataResponseMetadataTypeDef",
-    "UpdateSAMLProviderResponseTypeDef",
+    "CreateAccessKeyResponseTypeDef",
     "ListAttachedGroupPoliciesResponseTypeDef",
     "ListAttachedRolePoliciesResponseTypeDef",
     "ListAttachedUserPoliciesResponseTypeDef",
     "SimulateCustomPolicyRequestRequestTypeDef",
+    "SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
     "SimulatePrincipalPolicyRequestRequestTypeDef",
+    "SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
     "CreateGroupResponseTypeDef",
     "ListGroupsForUserResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "CreateInstanceProfileRequestRequestTypeDef",
     "CreateInstanceProfileRequestServiceResourceCreateInstanceProfileTypeDef",
     "CreateOpenIDConnectProviderRequestRequestTypeDef",
     "CreateOpenIDConnectProviderResponseTypeDef",
@@ -364,41 +376,14 @@
     "ListPolicyVersionsResponseTypeDef",
     "ManagedPolicyDetailTypeDef",
     "CreateServiceSpecificCredentialResponseTypeDef",
     "ResetServiceSpecificCredentialResponseTypeDef",
     "DeletionTaskFailureReasonTypeTypeDef",
     "EntityDetailsTypeDef",
     "GetOrganizationsAccessReportResponseTypeDef",
-    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
-    "GetGroupRequestGetGroupPaginateTypeDef",
-    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
-    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
-    "ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    "ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    "ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    "ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    "ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    "ListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    "ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    "ListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    "ListRolesRequestListRolesPaginateTypeDef",
-    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
-    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
-    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
-    "ListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    "ListUserTagsRequestListUserTagsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
-    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
-    "SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    "SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
     "GetAccountPasswordPolicyResponseTypeDef",
     "GetInstanceProfileRequestInstanceProfileExistsWaitTypeDef",
     "GetPolicyRequestPolicyExistsWaitTypeDef",
     "GetRoleRequestRoleExistsWaitTypeDef",
     "GetUserRequestUserExistsWaitTypeDef",
     "GetSSHPublicKeyResponseTypeDef",
     "UploadSSHPublicKeyResponseTypeDef",
@@ -619,22 +604,20 @@
 AttachUserPolicyRequestUserAttachPolicyTypeDef = TypedDict(
     "AttachUserPolicyRequestUserAttachPolicyTypeDef",
     {
         "PolicyArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AttachedPermissionsBoundaryResponseMetadataTypeDef = TypedDict(
+    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
+        "PermissionsBoundaryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachedPermissionsBoundaryTypeDef = TypedDict(
     "AttachedPermissionsBoundaryTypeDef",
     {
         "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
@@ -1071,14 +1054,22 @@
 DeleteServiceLinkedRoleRequestRequestTypeDef = TypedDict(
     "DeleteServiceLinkedRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 
+DeleteServiceLinkedRoleResponseTypeDef = TypedDict(
+    "DeleteServiceLinkedRoleResponseTypeDef",
+    {
+        "DeletionTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteServiceSpecificCredentialRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteServiceSpecificCredentialRequestRequestTypeDef",
     {
         "ServiceSpecificCredentialId": str,
     },
 )
 _OptionalDeleteServiceSpecificCredentialRequestRequestTypeDef = TypedDict(
@@ -1215,14 +1206,21 @@
 DetachUserPolicyRequestUserDetachPolicyTypeDef = TypedDict(
     "DetachUserPolicyRequestUserDetachPolicyTypeDef",
     {
         "PolicyArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableMFADeviceRequestMfaDeviceAssociateTypeDef = TypedDict(
     "EnableMFADeviceRequestMfaDeviceAssociateTypeDef",
     {
         "AuthenticationCode1": str,
         "AuthenticationCode2": str,
     },
 )
@@ -1286,14 +1284,23 @@
     "PermissionsBoundaryDecisionDetailTypeDef",
     {
         "AllowedByPermissionsBoundary": bool,
     },
     total=False,
 )
 
+GenerateCredentialReportResponseTypeDef = TypedDict(
+    "GenerateCredentialReportResponseTypeDef",
+    {
+        "State": ReportStateTypeType,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef",
     {
         "EntityPath": str,
     },
 )
 _OptionalGenerateOrganizationsAccessReportRequestRequestTypeDef = TypedDict(
@@ -1306,14 +1313,22 @@
 
 class GenerateOrganizationsAccessReportRequestRequestTypeDef(
     _RequiredGenerateOrganizationsAccessReportRequestRequestTypeDef,
     _OptionalGenerateOrganizationsAccessReportRequestRequestTypeDef,
 ):
     pass
 
+GenerateOrganizationsAccessReportResponseTypeDef = TypedDict(
+    "GenerateOrganizationsAccessReportResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 _OptionalGenerateServiceLastAccessedDetailsRequestRequestTypeDef = TypedDict(
@@ -1326,27 +1341,34 @@
 
 class GenerateServiceLastAccessedDetailsRequestRequestTypeDef(
     _RequiredGenerateServiceLastAccessedDetailsRequestRequestTypeDef,
     _OptionalGenerateServiceLastAccessedDetailsRequestRequestTypeDef,
 ):
     pass
 
+GenerateServiceLastAccessedDetailsResponseTypeDef = TypedDict(
+    "GenerateServiceLastAccessedDetailsResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessKeyLastUsedRequestRequestTypeDef = TypedDict(
     "GetAccessKeyLastUsedRequestRequestTypeDef",
     {
         "AccessKeyId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef = TypedDict(
+    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Filter": Sequence[EntityTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetAccountAuthorizationDetailsRequestRequestTypeDef = TypedDict(
     "GetAccountAuthorizationDetailsRequestRequestTypeDef",
     {
@@ -1370,21 +1392,37 @@
         "MaxPasswordAge": int,
         "PasswordReusePrevention": int,
         "HardExpiry": bool,
     },
     total=False,
 )
 
+GetAccountSummaryResponseTypeDef = TypedDict(
+    "GetAccountSummaryResponseTypeDef",
+    {
+        "SummaryMap": Dict[summaryKeyTypeType, int],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContextKeysForCustomPolicyRequestRequestTypeDef = TypedDict(
     "GetContextKeysForCustomPolicyRequestRequestTypeDef",
     {
         "PolicyInputList": Sequence[str],
     },
 )
 
+GetContextKeysForPolicyResponseTypeDef = TypedDict(
+    "GetContextKeysForPolicyResponseTypeDef",
+    {
+        "ContextKeyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef",
     {
         "PolicySourceArn": str,
     },
 )
 _OptionalGetContextKeysForPrincipalPolicyRequestRequestTypeDef = TypedDict(
@@ -1397,22 +1435,61 @@
 
 class GetContextKeysForPrincipalPolicyRequestRequestTypeDef(
     _RequiredGetContextKeysForPrincipalPolicyRequestRequestTypeDef,
     _OptionalGetContextKeysForPrincipalPolicyRequestRequestTypeDef,
 ):
     pass
 
+GetCredentialReportResponseTypeDef = TypedDict(
+    "GetCredentialReportResponseTypeDef",
+    {
+        "Content": bytes,
+        "ReportFormat": Literal["text/csv"],
+        "GeneratedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGroupPolicyRequestRequestTypeDef = TypedDict(
     "GetGroupPolicyRequestRequestTypeDef",
     {
         "GroupName": str,
         "PolicyName": str,
     },
 )
 
+GetGroupPolicyResponseTypeDef = TypedDict(
+    "GetGroupPolicyResponseTypeDef",
+    {
+        "GroupName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
+    "_RequiredGetGroupRequestGetGroupPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
+    "_OptionalGetGroupRequestGetGroupPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetGroupRequestGetGroupPaginateTypeDef(
+    _RequiredGetGroupRequestGetGroupPaginateTypeDef, _OptionalGetGroupRequestGetGroupPaginateTypeDef
+):
+    pass
+
 _RequiredGetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredGetGroupRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalGetGroupRequestRequestTypeDef = TypedDict(
@@ -1448,14 +1525,44 @@
 GetLoginProfileRequestRequestTypeDef = TypedDict(
     "GetLoginProfileRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 
+_RequiredGetMFADeviceRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMFADeviceRequestRequestTypeDef",
+    {
+        "SerialNumber": str,
+    },
+)
+_OptionalGetMFADeviceRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMFADeviceRequestRequestTypeDef",
+    {
+        "UserName": str,
+    },
+    total=False,
+)
+
+class GetMFADeviceRequestRequestTypeDef(
+    _RequiredGetMFADeviceRequestRequestTypeDef, _OptionalGetMFADeviceRequestRequestTypeDef
+):
+    pass
+
+GetMFADeviceResponseTypeDef = TypedDict(
+    "GetMFADeviceResponseTypeDef",
+    {
+        "UserName": str,
+        "SerialNumber": str,
+        "EnableDate": datetime,
+        "Certifications": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetOpenIDConnectProviderRequestRequestTypeDef = TypedDict(
     "GetOpenIDConnectProviderRequestRequestTypeDef",
     {
         "OpenIDConnectProviderArn": str,
     },
 )
 
@@ -1500,14 +1607,24 @@
     "GetRolePolicyRequestRequestTypeDef",
     {
         "RoleName": str,
         "PolicyName": str,
     },
 )
 
+GetRolePolicyResponseTypeDef = TypedDict(
+    "GetRolePolicyResponseTypeDef",
+    {
+        "RoleName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRoleRequestRequestTypeDef = TypedDict(
     "GetRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 
@@ -1609,14 +1726,24 @@
     "GetUserPolicyRequestRequestTypeDef",
     {
         "UserName": str,
         "PolicyName": str,
     },
 )
 
+GetUserPolicyResponseTypeDef = TypedDict(
+    "GetUserPolicyResponseTypeDef",
+    {
+        "UserName": str,
+        "PolicyName": str,
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetUserRequestRequestTypeDef = TypedDict(
     "GetUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
     total=False,
 )
@@ -1626,40 +1753,81 @@
     {
         "PolicyName": str,
         "PolicyDocument": str,
     },
     total=False,
 )
 
-GroupPolicyRequestTypeDef = TypedDict(
-    "GroupPolicyRequestTypeDef",
+ListAccessKeysRequestListAccessKeysPaginateTypeDef = TypedDict(
+    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
     {
-        "name": str,
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListAccessKeysRequestRequestTypeDef = TypedDict(
     "ListAccessKeysRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListAccountAliasesRequestListAccountAliasesPaginateTypeDef = TypedDict(
+    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccountAliasesRequestRequestTypeDef = TypedDict(
     "ListAccountAliasesRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListAccountAliasesResponseTypeDef = TypedDict(
+    "ListAccountAliasesResponseTypeDef",
+    {
+        "AccountAliases": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef(
+    _RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
+    _OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttachedGroupPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedGroupPoliciesRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalListAttachedGroupPoliciesRequestRequestTypeDef = TypedDict(
@@ -1674,14 +1842,35 @@
 
 class ListAttachedGroupPoliciesRequestRequestTypeDef(
     _RequiredListAttachedGroupPoliciesRequestRequestTypeDef,
     _OptionalListAttachedGroupPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef(
+    _RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
+    _OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttachedRolePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedRolePoliciesRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListAttachedRolePoliciesRequestRequestTypeDef = TypedDict(
@@ -1696,14 +1885,35 @@
 
 class ListAttachedRolePoliciesRequestRequestTypeDef(
     _RequiredListAttachedRolePoliciesRequestRequestTypeDef,
     _OptionalListAttachedRolePoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef(
+    _RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
+    _OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttachedUserPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedUserPoliciesRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListAttachedUserPoliciesRequestRequestTypeDef = TypedDict(
@@ -1718,14 +1928,37 @@
 
 class ListAttachedUserPoliciesRequestRequestTypeDef(
     _RequiredListAttachedUserPoliciesRequestRequestTypeDef,
     _OptionalListAttachedUserPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
+    {
+        "EntityFilter": EntityTypeType,
+        "PathPrefix": str,
+        "PolicyUsageFilter": PolicyUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef(
+    _RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
+    _OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
+):
+    pass
+
 _RequiredListEntitiesForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitiesForPolicyRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListEntitiesForPolicyRequestRequestTypeDef = TypedDict(
@@ -1769,14 +2002,34 @@
     {
         "UserName": str,
         "UserId": str,
     },
     total=False,
 )
 
+_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
+    {
+        "GroupName": str,
+    },
+)
+_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef(
+    _RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
+    _OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupPoliciesRequestRequestTypeDef",
     {
         "GroupName": str,
     },
 )
 _OptionalListGroupPoliciesRequestRequestTypeDef = TypedDict(
@@ -1789,14 +2042,44 @@
 )
 
 class ListGroupPoliciesRequestRequestTypeDef(
     _RequiredListGroupPoliciesRequestRequestTypeDef, _OptionalListGroupPoliciesRequestRequestTypeDef
 ):
     pass
 
+ListGroupPoliciesResponseTypeDef = TypedDict(
+    "ListGroupPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGroupsForUserRequestListGroupsForUserPaginateTypeDef(
+    _RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
+    _OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupsForUserRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsForUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListGroupsForUserRequestRequestTypeDef = TypedDict(
@@ -1809,24 +2092,53 @@
 )
 
 class ListGroupsForUserRequestRequestTypeDef(
     _RequiredListGroupsForUserRequestRequestTypeDef, _OptionalListGroupsForUserRequestRequestTypeDef
 ):
     pass
 
+ListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "ListGroupsRequestListGroupsPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGroupsRequestRequestTypeDef = TypedDict(
     "ListGroupsRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef = TypedDict(
+    "_RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
+    {
+        "InstanceProfileName": str,
+    },
+)
+_OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef = TypedDict(
+    "_OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef(
+    _RequiredListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
+    _OptionalListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListInstanceProfileTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceProfileTagsRequestRequestTypeDef",
     {
         "InstanceProfileName": str,
     },
 )
 _OptionalListInstanceProfileTagsRequestRequestTypeDef = TypedDict(
@@ -1840,14 +2152,34 @@
 
 class ListInstanceProfileTagsRequestRequestTypeDef(
     _RequiredListInstanceProfileTagsRequestRequestTypeDef,
     _OptionalListInstanceProfileTagsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
+    "_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
+    "_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef(
+    _RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
+    _OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
+):
+    pass
+
 _RequiredListInstanceProfilesForRoleRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceProfilesForRoleRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListInstanceProfilesForRoleRequestRequestTypeDef = TypedDict(
@@ -1861,24 +2193,53 @@
 
 class ListInstanceProfilesForRoleRequestRequestTypeDef(
     _RequiredListInstanceProfilesForRoleRequestRequestTypeDef,
     _OptionalListInstanceProfilesForRoleRequestRequestTypeDef,
 ):
     pass
 
+ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstanceProfilesRequestRequestTypeDef = TypedDict(
     "ListInstanceProfilesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef = TypedDict(
+    "_RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
+    {
+        "SerialNumber": str,
+    },
+)
+_OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef = TypedDict(
+    "_OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef(
+    _RequiredListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
+    _OptionalListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListMFADeviceTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListMFADeviceTagsRequestRequestTypeDef",
     {
         "SerialNumber": str,
     },
 )
 _OptionalListMFADeviceTagsRequestRequestTypeDef = TypedDict(
@@ -1891,14 +2252,23 @@
 )
 
 class ListMFADeviceTagsRequestRequestTypeDef(
     _RequiredListMFADeviceTagsRequestRequestTypeDef, _OptionalListMFADeviceTagsRequestRequestTypeDef
 ):
     pass
 
+ListMFADevicesRequestListMFADevicesPaginateTypeDef = TypedDict(
+    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMFADevicesRequestRequestTypeDef = TypedDict(
     "ListMFADevicesRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -1910,14 +2280,38 @@
     {
         "UserName": str,
         "SerialNumber": str,
         "EnableDate": datetime,
     },
 )
 
+_RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
+        {
+            "OpenIDConnectProviderArn": str,
+        },
+    )
+)
+_OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef(
+    _RequiredListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
+    _OptionalListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListOpenIDConnectProviderTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListOpenIDConnectProviderTagsRequestRequestTypeDef",
     {
         "OpenIDConnectProviderArn": str,
     },
 )
 _OptionalListOpenIDConnectProviderTagsRequestRequestTypeDef = TypedDict(
@@ -1982,27 +2376,59 @@
 
 class ListPoliciesGrantingServiceAccessRequestRequestTypeDef(
     _RequiredListPoliciesGrantingServiceAccessRequestRequestTypeDef,
     _OptionalListPoliciesGrantingServiceAccessRequestRequestTypeDef,
 ):
     pass
 
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "Scope": policyScopeTypeType,
+        "OnlyAttached": bool,
+        "PathPrefix": str,
+        "PolicyUsageFilter": PolicyUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "Scope": policyScopeTypeType,
         "OnlyAttached": bool,
         "PathPrefix": str,
         "PolicyUsageFilter": PolicyUsageTypeType,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPolicyTagsRequestListPolicyTagsPaginateTypeDef(
+    _RequiredListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
+    _OptionalListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPolicyTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyTagsRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListPolicyTagsRequestRequestTypeDef = TypedDict(
@@ -2015,14 +2441,34 @@
 )
 
 class ListPolicyTagsRequestRequestTypeDef(
     _RequiredListPolicyTagsRequestRequestTypeDef, _OptionalListPolicyTagsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
+    {
+        "PolicyArn": str,
+    },
+)
+_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef(
+    _RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
+    _OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPolicyVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyVersionsRequestRequestTypeDef",
     {
         "PolicyArn": str,
     },
 )
 _OptionalListPolicyVersionsRequestRequestTypeDef = TypedDict(
@@ -2036,14 +2482,34 @@
 
 class ListPolicyVersionsRequestRequestTypeDef(
     _RequiredListPolicyVersionsRequestRequestTypeDef,
     _OptionalListPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRolePoliciesRequestListRolePoliciesPaginateTypeDef(
+    _RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
+    _OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListRolePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListRolePoliciesRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListRolePoliciesRequestRequestTypeDef = TypedDict(
@@ -2056,14 +2522,44 @@
 )
 
 class ListRolePoliciesRequestRequestTypeDef(
     _RequiredListRolePoliciesRequestRequestTypeDef, _OptionalListRolePoliciesRequestRequestTypeDef
 ):
     pass
 
+ListRolePoliciesResponseTypeDef = TypedDict(
+    "ListRolePoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef = TypedDict(
+    "_RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef",
+    {
+        "RoleName": str,
+    },
+)
+_OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef = TypedDict(
+    "_OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRoleTagsRequestListRoleTagsPaginateTypeDef(
+    _RequiredListRoleTagsRequestListRoleTagsPaginateTypeDef,
+    _OptionalListRoleTagsRequestListRoleTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRoleTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListRoleTagsRequestRequestTypeDef",
     {
         "RoleName": str,
     },
 )
 _OptionalListRoleTagsRequestRequestTypeDef = TypedDict(
@@ -2076,24 +2572,53 @@
 )
 
 class ListRoleTagsRequestRequestTypeDef(
     _RequiredListRoleTagsRequestRequestTypeDef, _OptionalListRoleTagsRequestRequestTypeDef
 ):
     pass
 
+ListRolesRequestListRolesPaginateTypeDef = TypedDict(
+    "ListRolesRequestListRolesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRolesRequestRequestTypeDef = TypedDict(
     "ListRolesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef = TypedDict(
+    "_RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
+    {
+        "SAMLProviderArn": str,
+    },
+)
+_OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef = TypedDict(
+    "_OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef(
+    _RequiredListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
+    _OptionalListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListSAMLProviderTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListSAMLProviderTagsRequestRequestTypeDef",
     {
         "SAMLProviderArn": str,
     },
 )
 _OptionalListSAMLProviderTagsRequestRequestTypeDef = TypedDict(
@@ -2117,14 +2642,23 @@
         "Arn": str,
         "ValidUntil": datetime,
         "CreateDate": datetime,
     },
     total=False,
 )
 
+ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef = TypedDict(
+    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSSHPublicKeysRequestRequestTypeDef = TypedDict(
     "ListSSHPublicKeysRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2137,14 +2671,34 @@
         "UserName": str,
         "SSHPublicKeyId": str,
         "Status": statusTypeType,
         "UploadDate": datetime,
     },
 )
 
+_RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef = TypedDict(
+    "_RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
+    {
+        "ServerCertificateName": str,
+    },
+)
+_OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef = TypedDict(
+    "_OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef(
+    _RequiredListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
+    _OptionalListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListServerCertificateTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListServerCertificateTagsRequestRequestTypeDef",
     {
         "ServerCertificateName": str,
     },
 )
 _OptionalListServerCertificateTagsRequestRequestTypeDef = TypedDict(
@@ -2158,14 +2712,23 @@
 
 class ListServerCertificateTagsRequestRequestTypeDef(
     _RequiredListServerCertificateTagsRequestRequestTypeDef,
     _OptionalListServerCertificateTagsRequestRequestTypeDef,
 ):
     pass
 
+ListServerCertificatesRequestListServerCertificatesPaginateTypeDef = TypedDict(
+    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServerCertificatesRequestRequestTypeDef = TypedDict(
     "ListServerCertificatesRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2212,14 +2775,23 @@
         "ServiceUserName": str,
         "CreateDate": datetime,
         "ServiceSpecificCredentialId": str,
         "ServiceName": str,
     },
 )
 
+ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef = TypedDict(
+    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
+    {
+        "UserName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningCertificatesRequestRequestTypeDef = TypedDict(
     "ListSigningCertificatesRequestRequestTypeDef",
     {
         "UserName": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -2244,14 +2816,34 @@
 )
 
 class SigningCertificateTypeDef(
     _RequiredSigningCertificateTypeDef, _OptionalSigningCertificateTypeDef
 ):
     pass
 
+_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUserPoliciesRequestListUserPoliciesPaginateTypeDef(
+    _RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
+    _OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListUserPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListUserPoliciesRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListUserPoliciesRequestRequestTypeDef = TypedDict(
@@ -2264,14 +2856,44 @@
 )
 
 class ListUserPoliciesRequestRequestTypeDef(
     _RequiredListUserPoliciesRequestRequestTypeDef, _OptionalListUserPoliciesRequestRequestTypeDef
 ):
     pass
 
+ListUserPoliciesResponseTypeDef = TypedDict(
+    "ListUserPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "IsTruncated": bool,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
+    "_RequiredListUserTagsRequestListUserTagsPaginateTypeDef",
+    {
+        "UserName": str,
+    },
+)
+_OptionalListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
+    "_OptionalListUserTagsRequestListUserTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUserTagsRequestListUserTagsPaginateTypeDef(
+    _RequiredListUserTagsRequestListUserTagsPaginateTypeDef,
+    _OptionalListUserTagsRequestListUserTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListUserTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListUserTagsRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 _OptionalListUserTagsRequestRequestTypeDef = TypedDict(
@@ -2284,34 +2906,62 @@
 )
 
 class ListUserTagsRequestRequestTypeDef(
     _RequiredListUserTagsRequestRequestTypeDef, _OptionalListUserTagsRequestRequestTypeDef
 ):
     pass
 
+ListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "ListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PathPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUsersRequestRequestTypeDef = TypedDict(
     "ListUsersRequestRequestTypeDef",
     {
         "PathPrefix": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef = TypedDict(
+    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
+    {
+        "AssignmentStatus": assignmentStatusTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualMFADevicesRequestRequestTypeDef = TypedDict(
     "ListVirtualMFADevicesRequestRequestTypeDef",
     {
         "AssignmentStatus": assignmentStatusTypeType,
         "Marker": str,
         "MaxItems": int,
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
 PositionTypeDef = TypedDict(
     "PositionTypeDef",
     {
         "Line": int,
         "Column": int,
     },
     total=False,
@@ -2458,14 +3108,25 @@
 
 class ResetServiceSpecificCredentialRequestRequestTypeDef(
     _RequiredResetServiceSpecificCredentialRequestRequestTypeDef,
     _OptionalResetServiceSpecificCredentialRequestRequestTypeDef,
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
 ResyncMFADeviceRequestMfaDeviceResyncTypeDef = TypedDict(
     "ResyncMFADeviceRequestMfaDeviceResyncTypeDef",
     {
         "AuthenticationCode1": str,
         "AuthenticationCode2": str,
     },
 )
@@ -2485,167 +3146,47 @@
     {
         "LastUsedDate": datetime,
         "Region": str,
     },
     total=False,
 )
 
-RolePolicyRequestTypeDef = TypedDict(
-    "RolePolicyRequestTypeDef",
+RoleLastUsedResponseMetadataTypeDef = TypedDict(
+    "RoleLastUsedResponseMetadataTypeDef",
     {
-        "name": str,
+        "LastUsedDate": datetime,
+        "Region": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ServerCertificateMetadataResponseMetadataTypeDef = TypedDict(
+    "ServerCertificateMetadataResponseMetadataTypeDef",
+    {
+        "Path": str,
+        "ServerCertificateName": str,
+        "ServerCertificateId": str,
+        "Arn": str,
+        "UploadDate": datetime,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrackedActionLastAccessedTypeDef = TypedDict(
     "TrackedActionLastAccessedTypeDef",
     {
         "ActionName": str,
         "LastAccessedEntity": str,
         "LastAccessedTime": datetime,
         "LastAccessedRegion": str,
     },
     total=False,
 )
 
-ServiceResourceAccessKeyPairRequestTypeDef = TypedDict(
-    "ServiceResourceAccessKeyPairRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-        "secret": str,
-    },
-)
-
-ServiceResourceAccessKeyRequestTypeDef = TypedDict(
-    "ServiceResourceAccessKeyRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceAssumeRolePolicyRequestTypeDef = TypedDict(
-    "ServiceResourceAssumeRolePolicyRequestTypeDef",
-    {
-        "role_name": str,
-    },
-)
-
-ServiceResourceGroupPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceGroupPolicyRequestTypeDef",
-    {
-        "group_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceGroupRequestTypeDef = TypedDict(
-    "ServiceResourceGroupRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceInstanceProfileRequestTypeDef = TypedDict(
-    "ServiceResourceInstanceProfileRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceLoginProfileRequestTypeDef = TypedDict(
-    "ServiceResourceLoginProfileRequestTypeDef",
-    {
-        "user_name": str,
-    },
-)
-
-ServiceResourceMfaDeviceRequestTypeDef = TypedDict(
-    "ServiceResourceMfaDeviceRequestTypeDef",
-    {
-        "user_name": str,
-        "serial_number": str,
-    },
-)
-
-ServiceResourcePolicyRequestTypeDef = TypedDict(
-    "ServiceResourcePolicyRequestTypeDef",
-    {
-        "policy_arn": str,
-    },
-)
-
-ServiceResourcePolicyVersionRequestTypeDef = TypedDict(
-    "ServiceResourcePolicyVersionRequestTypeDef",
-    {
-        "arn": str,
-        "version_id": str,
-    },
-)
-
-ServiceResourceRolePolicyRequestTypeDef = TypedDict(
-    "ServiceResourceRolePolicyRequestTypeDef",
-    {
-        "role_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceRoleRequestTypeDef = TypedDict(
-    "ServiceResourceRoleRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceSamlProviderRequestTypeDef = TypedDict(
-    "ServiceResourceSamlProviderRequestTypeDef",
-    {
-        "arn": str,
-    },
-)
-
-ServiceResourceServerCertificateRequestTypeDef = TypedDict(
-    "ServiceResourceServerCertificateRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceSigningCertificateRequestTypeDef = TypedDict(
-    "ServiceResourceSigningCertificateRequestTypeDef",
-    {
-        "user_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceUserPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceUserPolicyRequestTypeDef",
-    {
-        "user_name": str,
-        "name": str,
-    },
-)
-
-ServiceResourceUserRequestTypeDef = TypedDict(
-    "ServiceResourceUserRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceVirtualMfaDeviceRequestTypeDef = TypedDict(
-    "ServiceResourceVirtualMfaDeviceRequestTypeDef",
-    {
-        "serial_number": str,
-    },
-)
-
 SetDefaultPolicyVersionRequestRequestTypeDef = TypedDict(
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     {
         "PolicyArn": str,
         "VersionId": str,
     },
 )
@@ -2942,14 +3483,22 @@
 UpdateSAMLProviderRequestSamlProviderUpdateTypeDef = TypedDict(
     "UpdateSAMLProviderRequestSamlProviderUpdateTypeDef",
     {
         "SAMLMetadataDocument": str,
     },
 )
 
+UpdateSAMLProviderResponseTypeDef = TypedDict(
+    "UpdateSAMLProviderResponseTypeDef",
+    {
+        "SAMLProviderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSSHPublicKeyRequestRequestTypeDef = TypedDict(
     "UpdateSSHPublicKeyRequestRequestTypeDef",
     {
         "UserName": str,
         "SSHPublicKeyId": str,
         "Status": statusTypeType,
     },
@@ -3116,271 +3665,68 @@
 
 class UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef(
     _RequiredUploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
     _OptionalUploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
 ):
     pass
 
-UserAccessKeyRequestTypeDef = TypedDict(
-    "UserAccessKeyRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-UserMfaDeviceRequestTypeDef = TypedDict(
-    "UserMfaDeviceRequestTypeDef",
-    {
-        "serial_number": str,
-    },
-)
-
-UserPolicyRequestTypeDef = TypedDict(
-    "UserPolicyRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-UserSigningCertificateRequestTypeDef = TypedDict(
-    "UserSigningCertificateRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-AttachedPermissionsBoundaryResponseMetadataTypeDef = TypedDict(
-    "AttachedPermissionsBoundaryResponseMetadataTypeDef",
-    {
-        "PermissionsBoundaryType": Literal["PermissionsBoundaryPolicy"],
-        "PermissionsBoundaryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessKeyResponseTypeDef = TypedDict(
-    "CreateAccessKeyResponseTypeDef",
-    {
-        "AccessKey": AccessKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteServiceLinkedRoleResponseTypeDef = TypedDict(
-    "DeleteServiceLinkedRoleResponseTypeDef",
-    {
-        "DeletionTaskId": str,
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
-GenerateCredentialReportResponseTypeDef = TypedDict(
-    "GenerateCredentialReportResponseTypeDef",
-    {
-        "State": ReportStateTypeType,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateOrganizationsAccessReportResponseTypeDef = TypedDict(
-    "GenerateOrganizationsAccessReportResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateServiceLastAccessedDetailsResponseTypeDef = TypedDict(
-    "GenerateServiceLastAccessedDetailsResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetAccessKeyLastUsedResponseTypeDef = TypedDict(
     "GetAccessKeyLastUsedResponseTypeDef",
     {
         "UserName": str,
         "AccessKeyLastUsed": AccessKeyLastUsedTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSummaryResponseTypeDef = TypedDict(
-    "GetAccountSummaryResponseTypeDef",
-    {
-        "SummaryMap": Dict[summaryKeyTypeType, int],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContextKeysForPolicyResponseTypeDef = TypedDict(
-    "GetContextKeysForPolicyResponseTypeDef",
-    {
-        "ContextKeyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCredentialReportResponseTypeDef = TypedDict(
-    "GetCredentialReportResponseTypeDef",
-    {
-        "Content": bytes,
-        "ReportFormat": Literal["text/csv"],
-        "GeneratedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupPolicyResponseTypeDef = TypedDict(
-    "GetGroupPolicyResponseTypeDef",
-    {
-        "GroupName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRolePolicyResponseTypeDef = TypedDict(
-    "GetRolePolicyResponseTypeDef",
-    {
-        "RoleName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserPolicyResponseTypeDef = TypedDict(
-    "GetUserPolicyResponseTypeDef",
-    {
-        "UserName": str,
-        "PolicyName": str,
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccessKeysResponseTypeDef = TypedDict(
     "ListAccessKeysResponseTypeDef",
     {
         "AccessKeyMetadata": List[AccessKeyMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAliasesResponseTypeDef = TypedDict(
-    "ListAccountAliasesResponseTypeDef",
-    {
-        "AccountAliases": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGroupPoliciesResponseTypeDef = TypedDict(
-    "ListGroupPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRolePoliciesResponseTypeDef = TypedDict(
-    "ListRolePoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListUserPoliciesResponseTypeDef = TypedDict(
-    "ListUserPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "IsTruncated": bool,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RoleLastUsedResponseMetadataTypeDef = TypedDict(
-    "RoleLastUsedResponseMetadataTypeDef",
-    {
-        "LastUsedDate": datetime,
-        "Region": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ServerCertificateMetadataResponseMetadataTypeDef = TypedDict(
-    "ServerCertificateMetadataResponseMetadataTypeDef",
-    {
-        "Path": str,
-        "ServerCertificateName": str,
-        "ServerCertificateId": str,
-        "Arn": str,
-        "UploadDate": datetime,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateSAMLProviderResponseTypeDef = TypedDict(
-    "UpdateSAMLProviderResponseTypeDef",
+CreateAccessKeyResponseTypeDef = TypedDict(
+    "CreateAccessKeyResponseTypeDef",
     {
-        "SAMLProviderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AccessKey": AccessKeyTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedGroupPoliciesResponseTypeDef = TypedDict(
     "ListAttachedGroupPoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedRolePoliciesResponseTypeDef = TypedDict(
     "ListAttachedRolePoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachedUserPoliciesResponseTypeDef = TypedDict(
     "ListAttachedUserPoliciesResponseTypeDef",
     {
         "AttachedPolicies": List[AttachedPolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSimulateCustomPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSimulateCustomPolicyRequestRequestTypeDef",
     {
         "PolicyInputList": Sequence[str],
@@ -3405,14 +3751,42 @@
 
 class SimulateCustomPolicyRequestRequestTypeDef(
     _RequiredSimulateCustomPolicyRequestRequestTypeDef,
     _OptionalSimulateCustomPolicyRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
+    "_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
+    {
+        "PolicyInputList": Sequence[str],
+        "ActionNames": Sequence[str],
+    },
+)
+_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
+    "_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
+    {
+        "PermissionsBoundaryPolicyInputList": Sequence[str],
+        "ResourceArns": Sequence[str],
+        "ResourcePolicy": str,
+        "ResourceOwner": str,
+        "CallerArn": str,
+        "ContextEntries": Sequence[ContextEntryTypeDef],
+        "ResourceHandlingOption": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef(
+    _RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
+    _OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
+):
+    pass
+
 _RequiredSimulatePrincipalPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSimulatePrincipalPolicyRequestRequestTypeDef",
     {
         "PolicySourceArn": str,
         "ActionNames": Sequence[str],
     },
 )
@@ -3435,39 +3809,68 @@
 
 class SimulatePrincipalPolicyRequestRequestTypeDef(
     _RequiredSimulatePrincipalPolicyRequestRequestTypeDef,
     _OptionalSimulatePrincipalPolicyRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
+    "_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
+    {
+        "PolicySourceArn": str,
+        "ActionNames": Sequence[str],
+    },
+)
+_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
+    "_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
+    {
+        "PolicyInputList": Sequence[str],
+        "PermissionsBoundaryPolicyInputList": Sequence[str],
+        "ResourceArns": Sequence[str],
+        "ResourcePolicy": str,
+        "ResourceOwner": str,
+        "CallerArn": str,
+        "ContextEntries": Sequence[ContextEntryTypeDef],
+        "ResourceHandlingOption": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef(
+    _RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
+    _OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
+):
+    pass
+
 CreateGroupResponseTypeDef = TypedDict(
     "CreateGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsForUserResponseTypeDef = TypedDict(
     "ListGroupsForUserResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateInstanceProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceProfileRequestRequestTypeDef",
     {
         "InstanceProfileName": str,
@@ -3532,15 +3935,15 @@
     pass
 
 CreateOpenIDConnectProviderResponseTypeDef = TypedDict(
     "CreateOpenIDConnectProviderResponseTypeDef",
     {
         "OpenIDConnectProviderArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
@@ -3677,15 +4080,15 @@
     pass
 
 CreateSAMLProviderResponseTypeDef = TypedDict(
     "CreateSAMLProviderResponseTypeDef",
     {
         "SAMLProviderArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "UserName": str,
@@ -3784,106 +4187,106 @@
     "GetOpenIDConnectProviderResponseTypeDef",
     {
         "Url": str,
         "ClientIDList": List[str],
         "ThumbprintList": List[str],
         "CreateDate": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSAMLProviderResponseTypeDef = TypedDict(
     "GetSAMLProviderResponseTypeDef",
     {
         "SAMLMetadataDocument": str,
         "CreateDate": datetime,
         "ValidUntil": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfileTagsResponseTypeDef = TypedDict(
     "ListInstanceProfileTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMFADeviceTagsResponseTypeDef = TypedDict(
     "ListMFADeviceTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpenIDConnectProviderTagsResponseTypeDef = TypedDict(
     "ListOpenIDConnectProviderTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyTagsResponseTypeDef = TypedDict(
     "ListPolicyTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoleTagsResponseTypeDef = TypedDict(
     "ListRoleTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSAMLProviderTagsResponseTypeDef = TypedDict(
     "ListSAMLProviderTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServerCertificateTagsResponseTypeDef = TypedDict(
     "ListServerCertificateTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserTagsResponseTypeDef = TypedDict(
     "ListUserTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyTypeDef = TypedDict(
     "PolicyTypeDef",
     {
         "PolicyName": str,
@@ -4021,15 +4424,15 @@
         "UserName": str,
         "UserId": str,
         "Arn": str,
         "CreateDate": datetime,
         "PasswordLastUsed": datetime,
         "PermissionsBoundary": AttachedPermissionsBoundaryTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUserTypeDef = TypedDict(
     "_RequiredUserTypeDef",
     {
         "Path": str,
@@ -4052,49 +4455,49 @@
 class UserTypeDef(_RequiredUserTypeDef, _OptionalUserTypeDef):
     pass
 
 CreateLoginProfileResponseTypeDef = TypedDict(
     "CreateLoginProfileResponseTypeDef",
     {
         "LoginProfile": LoginProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoginProfileResponseTypeDef = TypedDict(
     "GetLoginProfileResponseTypeDef",
     {
         "LoginProfile": LoginProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePolicyVersionResponseTypeDef = TypedDict(
     "CreatePolicyVersionResponseTypeDef",
     {
         "PolicyVersion": PolicyVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPolicyVersionResponseTypeDef = TypedDict(
     "GetPolicyVersionResponseTypeDef",
     {
         "PolicyVersion": PolicyVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyVersionsResponseTypeDef = TypedDict(
     "ListPolicyVersionsResponseTypeDef",
     {
         "Versions": List[PolicyVersionTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ManagedPolicyDetailTypeDef = TypedDict(
     "ManagedPolicyDetailTypeDef",
     {
         "PolicyName": str,
@@ -4113,23 +4516,23 @@
     total=False,
 )
 
 CreateServiceSpecificCredentialResponseTypeDef = TypedDict(
     "CreateServiceSpecificCredentialResponseTypeDef",
     {
         "ServiceSpecificCredential": ServiceSpecificCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetServiceSpecificCredentialResponseTypeDef = TypedDict(
     "ResetServiceSpecificCredentialResponseTypeDef",
     {
         "ServiceSpecificCredential": ServiceSpecificCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletionTaskFailureReasonTypeTypeDef = TypedDict(
     "DeletionTaskFailureReasonTypeTypeDef",
     {
         "Reason": str,
@@ -4163,444 +4566,23 @@
         "JobCompletionDate": datetime,
         "NumberOfServicesAccessible": int,
         "NumberOfServicesNotAccessed": int,
         "AccessDetails": List[AccessDetailTypeDef],
         "IsTruncated": bool,
         "Marker": str,
         "ErrorDetails": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef = TypedDict(
-    "GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef",
-    {
-        "Filter": Sequence[EntityTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
-    "_RequiredGetGroupRequestGetGroupPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalGetGroupRequestGetGroupPaginateTypeDef = TypedDict(
-    "_OptionalGetGroupRequestGetGroupPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetGroupRequestGetGroupPaginateTypeDef(
-    _RequiredGetGroupRequestGetGroupPaginateTypeDef, _OptionalGetGroupRequestGetGroupPaginateTypeDef
-):
-    pass
-
-ListAccessKeysRequestListAccessKeysPaginateTypeDef = TypedDict(
-    "ListAccessKeysRequestListAccessKeysPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAccountAliasesRequestListAccountAliasesPaginateTypeDef = TypedDict(
-    "ListAccountAliasesRequestListAccountAliasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef(
-    _RequiredListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-    _OptionalListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef(
-    _RequiredListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-    _OptionalListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef(
-    _RequiredListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-    _OptionalListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    {
-        "PolicyArn": str,
-    },
-)
-_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef",
-    {
-        "EntityFilter": EntityTypeType,
-        "PathPrefix": str,
-        "PolicyUsageFilter": PolicyUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef(
-    _RequiredListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-    _OptionalListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-):
-    pass
-
-_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    {
-        "GroupName": str,
-    },
-)
-_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef(
-    _RequiredListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-    _OptionalListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGroupsForUserRequestListGroupsForUserPaginateTypeDef(
-    _RequiredListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-    _OptionalListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-):
-    pass
-
-ListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "ListGroupsRequestListGroupsPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
-    "_RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef = TypedDict(
-    "_OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef(
-    _RequiredListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-    _OptionalListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-):
-    pass
-
-ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMFADevicesRequestListMFADevicesPaginateTypeDef = TypedDict(
-    "ListMFADevicesRequestListMFADevicesPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "Scope": policyScopeTypeType,
-        "OnlyAttached": bool,
-        "PathPrefix": str,
-        "PolicyUsageFilter": PolicyUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    {
-        "PolicyArn": str,
-    },
-)
-_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef(
-    _RequiredListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-    _OptionalListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    {
-        "RoleName": str,
-    },
-)
-_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRolePoliciesRequestListRolePoliciesPaginateTypeDef(
-    _RequiredListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-    _OptionalListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-):
-    pass
-
-ListRolesRequestListRolesPaginateTypeDef = TypedDict(
-    "ListRolesRequestListRolesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef = TypedDict(
-    "ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServerCertificatesRequestListServerCertificatesPaginateTypeDef = TypedDict(
-    "ListServerCertificatesRequestListServerCertificatesPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef = TypedDict(
-    "ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef",
-    {
-        "UserName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUserPoliciesRequestListUserPoliciesPaginateTypeDef(
-    _RequiredListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-    _OptionalListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
-    "_RequiredListUserTagsRequestListUserTagsPaginateTypeDef",
-    {
-        "UserName": str,
-    },
-)
-_OptionalListUserTagsRequestListUserTagsPaginateTypeDef = TypedDict(
-    "_OptionalListUserTagsRequestListUserTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUserTagsRequestListUserTagsPaginateTypeDef(
-    _RequiredListUserTagsRequestListUserTagsPaginateTypeDef,
-    _OptionalListUserTagsRequestListUserTagsPaginateTypeDef,
-):
-    pass
-
-ListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "ListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PathPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef = TypedDict(
-    "ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef",
-    {
-        "AssignmentStatus": assignmentStatusTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
-    "_RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    {
-        "PolicyInputList": Sequence[str],
-        "ActionNames": Sequence[str],
-    },
-)
-_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef = TypedDict(
-    "_OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef",
-    {
-        "PermissionsBoundaryPolicyInputList": Sequence[str],
-        "ResourceArns": Sequence[str],
-        "ResourcePolicy": str,
-        "ResourceOwner": str,
-        "CallerArn": str,
-        "ContextEntries": Sequence[ContextEntryTypeDef],
-        "ResourceHandlingOption": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef(
-    _RequiredSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-    _OptionalSimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-):
-    pass
-
-_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
-    "_RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
-    {
-        "PolicySourceArn": str,
-        "ActionNames": Sequence[str],
-    },
-)
-_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef = TypedDict(
-    "_OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef",
-    {
-        "PolicyInputList": Sequence[str],
-        "PermissionsBoundaryPolicyInputList": Sequence[str],
-        "ResourceArns": Sequence[str],
-        "ResourcePolicy": str,
-        "ResourceOwner": str,
-        "CallerArn": str,
-        "ContextEntries": Sequence[ContextEntryTypeDef],
-        "ResourceHandlingOption": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef(
-    _RequiredSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
-    _OptionalSimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
-):
-    pass
-
 GetAccountPasswordPolicyResponseTypeDef = TypedDict(
     "GetAccountPasswordPolicyResponseTypeDef",
     {
         "PasswordPolicy": PasswordPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetInstanceProfileRequestInstanceProfileExistsWaitTypeDef = TypedDict(
     "_RequiredGetInstanceProfileRequestInstanceProfileExistsWaitTypeDef",
     {
         "InstanceProfileName": str,
@@ -4668,23 +4650,23 @@
     total=False,
 )
 
 GetSSHPublicKeyResponseTypeDef = TypedDict(
     "GetSSHPublicKeyResponseTypeDef",
     {
         "SSHPublicKey": SSHPublicKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadSSHPublicKeyResponseTypeDef = TypedDict(
     "UploadSSHPublicKeyResponseTypeDef",
     {
         "SSHPublicKey": SSHPublicKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GroupDetailTypeDef = TypedDict(
     "GroupDetailTypeDef",
     {
         "Path": str,
@@ -4719,33 +4701,33 @@
     "ListEntitiesForPolicyResponseTypeDef",
     {
         "PolicyGroups": List[PolicyGroupTypeDef],
         "PolicyUsers": List[PolicyUserTypeDef],
         "PolicyRoles": List[PolicyRoleTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMFADevicesResponseTypeDef = TypedDict(
     "ListMFADevicesResponseTypeDef",
     {
         "MFADevices": List[MFADeviceTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpenIDConnectProvidersResponseTypeDef = TypedDict(
     "ListOpenIDConnectProvidersResponseTypeDef",
     {
         "OpenIDConnectProviderList": List[OpenIDConnectProviderListEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesGrantingServiceAccessEntryTypeDef = TypedDict(
     "ListPoliciesGrantingServiceAccessEntryTypeDef",
     {
         "ServiceNamespace": str,
@@ -4754,35 +4736,35 @@
     total=False,
 )
 
 ListSAMLProvidersResponseTypeDef = TypedDict(
     "ListSAMLProvidersResponseTypeDef",
     {
         "SAMLProviderList": List[SAMLProviderListEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSSHPublicKeysResponseTypeDef = TypedDict(
     "ListSSHPublicKeysResponseTypeDef",
     {
         "SSHPublicKeys": List[SSHPublicKeyMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServerCertificatesResponseTypeDef = TypedDict(
     "ListServerCertificatesResponseTypeDef",
     {
         "ServerCertificateMetadataList": List[ServerCertificateMetadataTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredServerCertificateTypeDef = TypedDict(
     "_RequiredServerCertificateTypeDef",
     {
         "ServerCertificateMetadata": ServerCertificateMetadataTypeDef,
@@ -4804,41 +4786,41 @@
     pass
 
 UploadServerCertificateResponseTypeDef = TypedDict(
     "UploadServerCertificateResponseTypeDef",
     {
         "ServerCertificateMetadata": ServerCertificateMetadataTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceSpecificCredentialsResponseTypeDef = TypedDict(
     "ListServiceSpecificCredentialsResponseTypeDef",
     {
         "ServiceSpecificCredentials": List[ServiceSpecificCredentialMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSigningCertificatesResponseTypeDef = TypedDict(
     "ListSigningCertificatesResponseTypeDef",
     {
         "Certificates": List[SigningCertificateTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadSigningCertificateResponseTypeDef = TypedDict(
     "UploadSigningCertificateResponseTypeDef",
     {
         "Certificate": SigningCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatementTypeDef = TypedDict(
     "StatementTypeDef",
     {
         "SourcePolicyId": str,
@@ -4899,70 +4881,70 @@
 ):
     pass
 
 CreatePolicyResponseTypeDef = TypedDict(
     "CreatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "Policies": List[PolicyTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResponseTypeDef = TypedDict(
     "GetGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
         "Users": List[UserTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserResponseTypeDef = TypedDict(
     "GetUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVirtualMFADeviceTypeDef = TypedDict(
     "_RequiredVirtualMFADeviceTypeDef",
     {
         "SerialNumber": str,
@@ -4984,47 +4966,47 @@
     pass
 
 GetServiceLinkedRoleDeletionStatusResponseTypeDef = TypedDict(
     "GetServiceLinkedRoleDeletionStatusResponseTypeDef",
     {
         "Status": DeletionTaskStatusTypeType,
         "Reason": DeletionTaskFailureReasonTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef = TypedDict(
     "GetServiceLastAccessedDetailsWithEntitiesResponseTypeDef",
     {
         "JobStatus": jobStatusTypeType,
         "JobCreationDate": datetime,
         "JobCompletionDate": datetime,
         "EntityDetailsList": List[EntityDetailsTypeDef],
         "IsTruncated": bool,
         "Marker": str,
         "Error": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesGrantingServiceAccessResponseTypeDef = TypedDict(
     "ListPoliciesGrantingServiceAccessResponseTypeDef",
     {
         "PoliciesGrantingServiceAccess": List[ListPoliciesGrantingServiceAccessEntryTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerCertificateResponseTypeDef = TypedDict(
     "GetServerCertificateResponseTypeDef",
     {
         "ServerCertificate": ServerCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceSpecificResultTypeDef = TypedDict(
     "_RequiredResourceSpecificResultTypeDef",
     {
         "EvalResourceName": str,
@@ -5047,31 +5029,31 @@
 ):
     pass
 
 CreateRoleResponseTypeDef = TypedDict(
     "CreateRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceLinkedRoleResponseTypeDef = TypedDict(
     "CreateServiceLinkedRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleResponseTypeDef = TypedDict(
     "GetRoleResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInstanceProfileTypeDef = TypedDict(
     "_RequiredInstanceProfileTypeDef",
     {
         "Path": str,
@@ -5095,56 +5077,56 @@
 
 ListRolesResponseTypeDef = TypedDict(
     "ListRolesResponseTypeDef",
     {
         "Roles": List[RoleTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoleDescriptionResponseTypeDef = TypedDict(
     "UpdateRoleDescriptionResponseTypeDef",
     {
         "Role": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceLastAccessedDetailsResponseTypeDef = TypedDict(
     "GetServiceLastAccessedDetailsResponseTypeDef",
     {
         "JobStatus": jobStatusTypeType,
         "JobType": AccessAdvisorUsageGranularityTypeType,
         "JobCreationDate": datetime,
         "ServicesLastAccessed": List[ServiceLastAccessedTypeDef],
         "JobCompletionDate": datetime,
         "IsTruncated": bool,
         "Marker": str,
         "Error": ErrorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVirtualMFADeviceResponseTypeDef = TypedDict(
     "CreateVirtualMFADeviceResponseTypeDef",
     {
         "VirtualMFADevice": VirtualMFADeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualMFADevicesResponseTypeDef = TypedDict(
     "ListVirtualMFADevicesResponseTypeDef",
     {
         "VirtualMFADevices": List[VirtualMFADeviceTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEvaluationResultTypeDef = TypedDict(
     "_RequiredEvaluationResultTypeDef",
     {
         "EvalActionName": str,
@@ -5168,43 +5150,43 @@
 class EvaluationResultTypeDef(_RequiredEvaluationResultTypeDef, _OptionalEvaluationResultTypeDef):
     pass
 
 CreateInstanceProfileResponseTypeDef = TypedDict(
     "CreateInstanceProfileResponseTypeDef",
     {
         "InstanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceProfileResponseTypeDef = TypedDict(
     "GetInstanceProfileResponseTypeDef",
     {
         "InstanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesForRoleResponseTypeDef = TypedDict(
     "ListInstanceProfilesForRoleResponseTypeDef",
     {
         "InstanceProfiles": List[InstanceProfileTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesResponseTypeDef = TypedDict(
     "ListInstanceProfilesResponseTypeDef",
     {
         "InstanceProfiles": List[InstanceProfileTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RoleDetailTypeDef = TypedDict(
     "RoleDetailTypeDef",
     {
         "Path": str,
@@ -5225,23 +5207,23 @@
 
 SimulatePolicyResponseTypeDef = TypedDict(
     "SimulatePolicyResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountAuthorizationDetailsResponseTypeDef = TypedDict(
     "GetAccountAuthorizationDetailsResponseTypeDef",
     {
         "UserDetailList": List[UserDetailTypeDef],
         "GroupDetailList": List[GroupDetailTypeDef],
         "RoleDetailList": List[RoleDetailTypeDef],
         "Policies": List[ManagedPolicyDetailTypeDef],
         "IsTruncated": bool,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/waiter.py` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam/waiter.pyi` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/PKG-INFO` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iam
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IAM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IAM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iam"></a>
 
 # types-aiobotocore-iam
 
 [![PyPI - types-aiobotocore-iam](https://img.shields.io/pypi/v/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iam?color=blue)](https://pypistats.org/packages/types-aiobotocore-iam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
+[aiobotocore.IAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iam.html#IAM)
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
 [types-aiobotocore-iam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,22 +286,29 @@
     ListAttachedGroupPoliciesPaginator,
     ListAttachedRolePoliciesPaginator,
     ListAttachedUserPoliciesPaginator,
     ListEntitiesForPolicyPaginator,
     ListGroupPoliciesPaginator,
     ListGroupsPaginator,
     ListGroupsForUserPaginator,
+    ListInstanceProfileTagsPaginator,
     ListInstanceProfilesPaginator,
     ListInstanceProfilesForRolePaginator,
+    ListMFADeviceTagsPaginator,
     ListMFADevicesPaginator,
+    ListOpenIDConnectProviderTagsPaginator,
     ListPoliciesPaginator,
+    ListPolicyTagsPaginator,
     ListPolicyVersionsPaginator,
     ListRolePoliciesPaginator,
+    ListRoleTagsPaginator,
     ListRolesPaginator,
+    ListSAMLProviderTagsPaginator,
     ListSSHPublicKeysPaginator,
+    ListServerCertificateTagsPaginator,
     ListServerCertificatesPaginator,
     ListSigningCertificatesPaginator,
     ListUserPoliciesPaginator,
     ListUserTagsPaginator,
     ListUsersPaginator,
     ListVirtualMFADevicesPaginator,
     SimulateCustomPolicyPaginator,
@@ -337,32 +344,49 @@
     list_group_policies_paginator: ListGroupPoliciesPaginator = client.get_paginator(
         "list_group_policies"
     )
     list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
     list_groups_for_user_paginator: ListGroupsForUserPaginator = client.get_paginator(
         "list_groups_for_user"
     )
+    list_instance_profile_tags_paginator: ListInstanceProfileTagsPaginator = client.get_paginator(
+        "list_instance_profile_tags"
+    )
     list_instance_profiles_paginator: ListInstanceProfilesPaginator = client.get_paginator(
         "list_instance_profiles"
     )
     list_instance_profiles_for_role_paginator: ListInstanceProfilesForRolePaginator = (
         client.get_paginator("list_instance_profiles_for_role")
     )
+    list_mfa_device_tags_paginator: ListMFADeviceTagsPaginator = client.get_paginator(
+        "list_mfa_device_tags"
+    )
     list_mfa_devices_paginator: ListMFADevicesPaginator = client.get_paginator("list_mfa_devices")
+    list_open_id_connect_provider_tags_paginator: ListOpenIDConnectProviderTagsPaginator = (
+        client.get_paginator("list_open_id_connect_provider_tags")
+    )
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
+    list_policy_tags_paginator: ListPolicyTagsPaginator = client.get_paginator("list_policy_tags")
     list_policy_versions_paginator: ListPolicyVersionsPaginator = client.get_paginator(
         "list_policy_versions"
     )
     list_role_policies_paginator: ListRolePoliciesPaginator = client.get_paginator(
         "list_role_policies"
     )
+    list_role_tags_paginator: ListRoleTagsPaginator = client.get_paginator("list_role_tags")
     list_roles_paginator: ListRolesPaginator = client.get_paginator("list_roles")
+    list_saml_provider_tags_paginator: ListSAMLProviderTagsPaginator = client.get_paginator(
+        "list_saml_provider_tags"
+    )
     list_ssh_public_keys_paginator: ListSSHPublicKeysPaginator = client.get_paginator(
         "list_ssh_public_keys"
     )
+    list_server_certificate_tags_paginator: ListServerCertificateTagsPaginator = (
+        client.get_paginator("list_server_certificate_tags")
+    )
     list_server_certificates_paginator: ListServerCertificatesPaginator = client.get_paginator(
         "list_server_certificates"
     )
     list_signing_certificates_paginator: ListSigningCertificatesPaginator = client.get_paginator(
         "list_signing_certificates"
     )
     list_user_policies_paginator: ListUserPoliciesPaginator = client.get_paginator(
@@ -559,22 +583,29 @@
     ListAttachedGroupPoliciesPaginatorName,
     ListAttachedRolePoliciesPaginatorName,
     ListAttachedUserPoliciesPaginatorName,
     ListEntitiesForPolicyPaginatorName,
     ListGroupPoliciesPaginatorName,
     ListGroupsForUserPaginatorName,
     ListGroupsPaginatorName,
+    ListInstanceProfileTagsPaginatorName,
     ListInstanceProfilesForRolePaginatorName,
     ListInstanceProfilesPaginatorName,
+    ListMFADeviceTagsPaginatorName,
     ListMFADevicesPaginatorName,
+    ListOpenIDConnectProviderTagsPaginatorName,
     ListPoliciesPaginatorName,
+    ListPolicyTagsPaginatorName,
     ListPolicyVersionsPaginatorName,
     ListRolePoliciesPaginatorName,
+    ListRoleTagsPaginatorName,
     ListRolesPaginatorName,
+    ListSAMLProviderTagsPaginatorName,
     ListSSHPublicKeysPaginatorName,
+    ListServerCertificateTagsPaginatorName,
     ListServerCertificatesPaginatorName,
     ListSigningCertificatesPaginatorName,
     ListUserPoliciesPaginatorName,
     ListUserTagsPaginatorName,
     ListUsersPaginatorName,
     ListVirtualMFADevicesPaginatorName,
     PermissionsBoundaryAttachmentTypeType,
@@ -634,15 +665,15 @@
     AttachGroupPolicyRequestRequestTypeDef,
     AttachRolePolicyRequestPolicyAttachRoleTypeDef,
     AttachRolePolicyRequestRequestTypeDef,
     AttachRolePolicyRequestRoleAttachPolicyTypeDef,
     AttachUserPolicyRequestPolicyAttachUserTypeDef,
     AttachUserPolicyRequestRequestTypeDef,
     AttachUserPolicyRequestUserAttachPolicyTypeDef,
-    ResponseMetadataTypeDef,
+    AttachedPermissionsBoundaryResponseMetadataTypeDef,
     AttachedPermissionsBoundaryTypeDef,
     AttachedPolicyTypeDef,
     ChangePasswordRequestRequestTypeDef,
     ChangePasswordRequestServiceResourceChangePasswordTypeDef,
     ContextEntryTypeDef,
     CreateAccessKeyRequestRequestTypeDef,
     CreateAccountAliasRequestRequestTypeDef,
@@ -675,14 +706,15 @@
     DeleteRolePermissionsBoundaryRequestRequestTypeDef,
     DeleteRolePolicyRequestRequestTypeDef,
     DeleteRoleRequestRequestTypeDef,
     DeleteSAMLProviderRequestRequestTypeDef,
     DeleteSSHPublicKeyRequestRequestTypeDef,
     DeleteServerCertificateRequestRequestTypeDef,
     DeleteServiceLinkedRoleRequestRequestTypeDef,
+    DeleteServiceLinkedRoleResponseTypeDef,
     DeleteServiceSpecificCredentialRequestRequestTypeDef,
     DeleteSigningCertificateRequestRequestTypeDef,
     DeleteUserPermissionsBoundaryRequestRequestTypeDef,
     DeleteUserPolicyRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DeleteVirtualMFADeviceRequestRequestTypeDef,
     RoleUsageTypeTypeDef,
@@ -691,94 +723,141 @@
     DetachGroupPolicyRequestRequestTypeDef,
     DetachRolePolicyRequestPolicyDetachRoleTypeDef,
     DetachRolePolicyRequestRequestTypeDef,
     DetachRolePolicyRequestRoleDetachPolicyTypeDef,
     DetachUserPolicyRequestPolicyDetachUserTypeDef,
     DetachUserPolicyRequestRequestTypeDef,
     DetachUserPolicyRequestUserDetachPolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMFADeviceRequestMfaDeviceAssociateTypeDef,
     EnableMFADeviceRequestRequestTypeDef,
     EnableMFADeviceRequestUserEnableMfaTypeDef,
     EntityInfoTypeDef,
     ErrorDetailsTypeDef,
     OrganizationsDecisionDetailTypeDef,
     PermissionsBoundaryDecisionDetailTypeDef,
+    GenerateCredentialReportResponseTypeDef,
     GenerateOrganizationsAccessReportRequestRequestTypeDef,
+    GenerateOrganizationsAccessReportResponseTypeDef,
     GenerateServiceLastAccessedDetailsRequestRequestTypeDef,
+    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
     GetAccountAuthorizationDetailsRequestRequestTypeDef,
     PasswordPolicyTypeDef,
+    GetAccountSummaryResponseTypeDef,
     GetContextKeysForCustomPolicyRequestRequestTypeDef,
+    GetContextKeysForPolicyResponseTypeDef,
     GetContextKeysForPrincipalPolicyRequestRequestTypeDef,
+    GetCredentialReportResponseTypeDef,
     GetGroupPolicyRequestRequestTypeDef,
+    GetGroupPolicyResponseTypeDef,
+    GetGroupRequestGetGroupPaginateTypeDef,
     GetGroupRequestRequestTypeDef,
     WaiterConfigTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetLoginProfileRequestRequestTypeDef,
+    GetMFADeviceRequestRequestTypeDef,
+    GetMFADeviceResponseTypeDef,
     GetOpenIDConnectProviderRequestRequestTypeDef,
     GetOrganizationsAccessReportRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
     GetRolePolicyRequestRequestTypeDef,
+    GetRolePolicyResponseTypeDef,
     GetRoleRequestRequestTypeDef,
     GetSAMLProviderRequestRequestTypeDef,
     GetSSHPublicKeyRequestRequestTypeDef,
     SSHPublicKeyTypeDef,
     GetServerCertificateRequestRequestTypeDef,
     GetServiceLastAccessedDetailsRequestRequestTypeDef,
     GetServiceLastAccessedDetailsWithEntitiesRequestRequestTypeDef,
     GetServiceLinkedRoleDeletionStatusRequestRequestTypeDef,
     GetUserPolicyRequestRequestTypeDef,
+    GetUserPolicyResponseTypeDef,
     GetUserRequestRequestTypeDef,
     PolicyDetailTypeDef,
-    GroupPolicyRequestTypeDef,
+    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
     ListAccessKeysRequestRequestTypeDef,
+    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
     ListAccountAliasesRequestRequestTypeDef,
+    ListAccountAliasesResponseTypeDef,
+    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
     ListAttachedGroupPoliciesRequestRequestTypeDef,
+    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
     ListAttachedRolePoliciesRequestRequestTypeDef,
+    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
     ListAttachedUserPoliciesRequestRequestTypeDef,
+    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
     ListEntitiesForPolicyRequestRequestTypeDef,
     PolicyGroupTypeDef,
     PolicyRoleTypeDef,
     PolicyUserTypeDef,
+    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
     ListGroupPoliciesRequestRequestTypeDef,
+    ListGroupPoliciesResponseTypeDef,
+    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
     ListGroupsForUserRequestRequestTypeDef,
+    ListGroupsRequestListGroupsPaginateTypeDef,
     ListGroupsRequestRequestTypeDef,
+    ListInstanceProfileTagsRequestListInstanceProfileTagsPaginateTypeDef,
     ListInstanceProfileTagsRequestRequestTypeDef,
+    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
     ListInstanceProfilesForRoleRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListMFADeviceTagsRequestListMFADeviceTagsPaginateTypeDef,
     ListMFADeviceTagsRequestRequestTypeDef,
+    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
     ListMFADevicesRequestRequestTypeDef,
     MFADeviceTypeDef,
+    ListOpenIDConnectProviderTagsRequestListOpenIDConnectProviderTagsPaginateTypeDef,
     ListOpenIDConnectProviderTagsRequestRequestTypeDef,
     OpenIDConnectProviderListEntryTypeDef,
     PolicyGrantingServiceAccessTypeDef,
     ListPoliciesGrantingServiceAccessRequestRequestTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyTagsRequestListPolicyTagsPaginateTypeDef,
     ListPolicyTagsRequestRequestTypeDef,
+    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
+    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
     ListRolePoliciesRequestRequestTypeDef,
+    ListRolePoliciesResponseTypeDef,
+    ListRoleTagsRequestListRoleTagsPaginateTypeDef,
     ListRoleTagsRequestRequestTypeDef,
+    ListRolesRequestListRolesPaginateTypeDef,
     ListRolesRequestRequestTypeDef,
+    ListSAMLProviderTagsRequestListSAMLProviderTagsPaginateTypeDef,
     ListSAMLProviderTagsRequestRequestTypeDef,
     SAMLProviderListEntryTypeDef,
+    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
     ListSSHPublicKeysRequestRequestTypeDef,
     SSHPublicKeyMetadataTypeDef,
+    ListServerCertificateTagsRequestListServerCertificateTagsPaginateTypeDef,
     ListServerCertificateTagsRequestRequestTypeDef,
+    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
     ListServerCertificatesRequestRequestTypeDef,
     ServerCertificateMetadataTypeDef,
     ListServiceSpecificCredentialsRequestRequestTypeDef,
     ServiceSpecificCredentialMetadataTypeDef,
+    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
     ListSigningCertificatesRequestRequestTypeDef,
     SigningCertificateTypeDef,
+    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
     ListUserPoliciesRequestRequestTypeDef,
+    ListUserPoliciesResponseTypeDef,
+    ListUserTagsRequestListUserTagsPaginateTypeDef,
     ListUserTagsRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
+    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
     ListVirtualMFADevicesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PositionTypeDef,
     PutGroupPolicyRequestGroupCreatePolicyTypeDef,
     PutGroupPolicyRequestGroupPolicyPutTypeDef,
     PutGroupPolicyRequestRequestTypeDef,
     PutRolePermissionsBoundaryRequestRequestTypeDef,
     PutRolePolicyRequestRequestTypeDef,
     PutRolePolicyRequestRolePolicyPutTypeDef,
@@ -789,37 +868,21 @@
     RemoveClientIDFromOpenIDConnectProviderRequestRequestTypeDef,
     RemoveRoleFromInstanceProfileRequestInstanceProfileRemoveRoleTypeDef,
     RemoveRoleFromInstanceProfileRequestRequestTypeDef,
     RemoveUserFromGroupRequestGroupRemoveUserTypeDef,
     RemoveUserFromGroupRequestRequestTypeDef,
     RemoveUserFromGroupRequestUserRemoveGroupTypeDef,
     ResetServiceSpecificCredentialRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResyncMFADeviceRequestMfaDeviceResyncTypeDef,
     ResyncMFADeviceRequestRequestTypeDef,
     RoleLastUsedTypeDef,
-    RolePolicyRequestTypeDef,
+    RoleLastUsedResponseMetadataTypeDef,
+    ServerCertificateMetadataResponseMetadataTypeDef,
     TrackedActionLastAccessedTypeDef,
-    ServiceResourceAccessKeyPairRequestTypeDef,
-    ServiceResourceAccessKeyRequestTypeDef,
-    ServiceResourceAssumeRolePolicyRequestTypeDef,
-    ServiceResourceGroupPolicyRequestTypeDef,
-    ServiceResourceGroupRequestTypeDef,
-    ServiceResourceInstanceProfileRequestTypeDef,
-    ServiceResourceLoginProfileRequestTypeDef,
-    ServiceResourceMfaDeviceRequestTypeDef,
-    ServiceResourcePolicyRequestTypeDef,
-    ServiceResourcePolicyVersionRequestTypeDef,
-    ServiceResourceRolePolicyRequestTypeDef,
-    ServiceResourceRoleRequestTypeDef,
-    ServiceResourceSamlProviderRequestTypeDef,
-    ServiceResourceServerCertificateRequestTypeDef,
-    ServiceResourceSigningCertificateRequestTypeDef,
-    ServiceResourceUserPolicyRequestTypeDef,
-    ServiceResourceUserRequestTypeDef,
-    ServiceResourceVirtualMfaDeviceRequestTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetSecurityTokenServicePreferencesRequestRequestTypeDef,
     UntagInstanceProfileRequestRequestTypeDef,
     UntagMFADeviceRequestRequestTypeDef,
     UntagOpenIDConnectProviderRequestRequestTypeDef,
     UntagPolicyRequestRequestTypeDef,
     UntagRoleRequestRequestTypeDef,
@@ -841,57 +904,37 @@
     UpdateLoginProfileRequestLoginProfileUpdateTypeDef,
     UpdateLoginProfileRequestRequestTypeDef,
     UpdateOpenIDConnectProviderThumbprintRequestRequestTypeDef,
     UpdateRoleDescriptionRequestRequestTypeDef,
     UpdateRoleRequestRequestTypeDef,
     UpdateSAMLProviderRequestRequestTypeDef,
     UpdateSAMLProviderRequestSamlProviderUpdateTypeDef,
+    UpdateSAMLProviderResponseTypeDef,
     UpdateSSHPublicKeyRequestRequestTypeDef,
     UpdateServerCertificateRequestRequestTypeDef,
     UpdateServerCertificateRequestServerCertificateUpdateTypeDef,
     UpdateServiceSpecificCredentialRequestRequestTypeDef,
     UpdateSigningCertificateRequestRequestTypeDef,
     UpdateSigningCertificateRequestSigningCertificateActivateTypeDef,
     UpdateSigningCertificateRequestSigningCertificateDeactivateTypeDef,
     UpdateUserRequestRequestTypeDef,
     UpdateUserRequestUserUpdateTypeDef,
     UploadSSHPublicKeyRequestRequestTypeDef,
     UploadSigningCertificateRequestRequestTypeDef,
     UploadSigningCertificateRequestServiceResourceCreateSigningCertificateTypeDef,
-    UserAccessKeyRequestTypeDef,
-    UserMfaDeviceRequestTypeDef,
-    UserPolicyRequestTypeDef,
-    UserSigningCertificateRequestTypeDef,
-    AttachedPermissionsBoundaryResponseMetadataTypeDef,
-    CreateAccessKeyResponseTypeDef,
-    DeleteServiceLinkedRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GenerateCredentialReportResponseTypeDef,
-    GenerateOrganizationsAccessReportResponseTypeDef,
-    GenerateServiceLastAccessedDetailsResponseTypeDef,
     GetAccessKeyLastUsedResponseTypeDef,
-    GetAccountSummaryResponseTypeDef,
-    GetContextKeysForPolicyResponseTypeDef,
-    GetCredentialReportResponseTypeDef,
-    GetGroupPolicyResponseTypeDef,
-    GetRolePolicyResponseTypeDef,
-    GetUserPolicyResponseTypeDef,
     ListAccessKeysResponseTypeDef,
-    ListAccountAliasesResponseTypeDef,
-    ListGroupPoliciesResponseTypeDef,
-    ListRolePoliciesResponseTypeDef,
-    ListUserPoliciesResponseTypeDef,
-    RoleLastUsedResponseMetadataTypeDef,
-    ServerCertificateMetadataResponseMetadataTypeDef,
-    UpdateSAMLProviderResponseTypeDef,
+    CreateAccessKeyResponseTypeDef,
     ListAttachedGroupPoliciesResponseTypeDef,
     ListAttachedRolePoliciesResponseTypeDef,
     ListAttachedUserPoliciesResponseTypeDef,
     SimulateCustomPolicyRequestRequestTypeDef,
+    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
     SimulatePrincipalPolicyRequestRequestTypeDef,
+    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     CreateGroupResponseTypeDef,
     ListGroupsForUserResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     CreateInstanceProfileRequestServiceResourceCreateInstanceProfileTypeDef,
     CreateOpenIDConnectProviderRequestRequestTypeDef,
     CreateOpenIDConnectProviderResponseTypeDef,
@@ -937,41 +980,14 @@
     ListPolicyVersionsResponseTypeDef,
     ManagedPolicyDetailTypeDef,
     CreateServiceSpecificCredentialResponseTypeDef,
     ResetServiceSpecificCredentialResponseTypeDef,
     DeletionTaskFailureReasonTypeTypeDef,
     EntityDetailsTypeDef,
     GetOrganizationsAccessReportResponseTypeDef,
-    GetAccountAuthorizationDetailsRequestGetAccountAuthorizationDetailsPaginateTypeDef,
-    GetGroupRequestGetGroupPaginateTypeDef,
-    ListAccessKeysRequestListAccessKeysPaginateTypeDef,
-    ListAccountAliasesRequestListAccountAliasesPaginateTypeDef,
-    ListAttachedGroupPoliciesRequestListAttachedGroupPoliciesPaginateTypeDef,
-    ListAttachedRolePoliciesRequestListAttachedRolePoliciesPaginateTypeDef,
-    ListAttachedUserPoliciesRequestListAttachedUserPoliciesPaginateTypeDef,
-    ListEntitiesForPolicyRequestListEntitiesForPolicyPaginateTypeDef,
-    ListGroupPoliciesRequestListGroupPoliciesPaginateTypeDef,
-    ListGroupsForUserRequestListGroupsForUserPaginateTypeDef,
-    ListGroupsRequestListGroupsPaginateTypeDef,
-    ListInstanceProfilesForRoleRequestListInstanceProfilesForRolePaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListMFADevicesRequestListMFADevicesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyVersionsRequestListPolicyVersionsPaginateTypeDef,
-    ListRolePoliciesRequestListRolePoliciesPaginateTypeDef,
-    ListRolesRequestListRolesPaginateTypeDef,
-    ListSSHPublicKeysRequestListSSHPublicKeysPaginateTypeDef,
-    ListServerCertificatesRequestListServerCertificatesPaginateTypeDef,
-    ListSigningCertificatesRequestListSigningCertificatesPaginateTypeDef,
-    ListUserPoliciesRequestListUserPoliciesPaginateTypeDef,
-    ListUserTagsRequestListUserTagsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListVirtualMFADevicesRequestListVirtualMFADevicesPaginateTypeDef,
-    SimulateCustomPolicyRequestSimulateCustomPolicyPaginateTypeDef,
-    SimulatePrincipalPolicyRequestSimulatePrincipalPolicyPaginateTypeDef,
     GetAccountPasswordPolicyResponseTypeDef,
     GetInstanceProfileRequestInstanceProfileExistsWaitTypeDef,
     GetPolicyRequestPolicyExistsWaitTypeDef,
     GetRoleRequestRoleExistsWaitTypeDef,
     GetUserRequestUserExistsWaitTypeDef,
     GetSSHPublicKeyResponseTypeDef,
     UploadSSHPublicKeyResponseTypeDef,
@@ -1032,43 +1048,43 @@
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

### Comparing `types-aiobotocore-iam-2.5.0.post1/types_aiobotocore_iam.egg-info/SOURCES.txt` & `types-aiobotocore-iam-2.5.1/types_aiobotocore_iam.egg-info/SOURCES.txt`

 * *Files identical despite different names*

