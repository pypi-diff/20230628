# Comparing `tmp/types-aiobotocore-sso-admin-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sso-admin-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sso-admin-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-sso-admin-2.5.1.tar", last modified: Wed Jun 28 01:44:14 2023, max compression
```

## Comparing `types-aiobotocore-sso-admin-2.5.0.post1.tar` & `types-aiobotocore-sso-admin-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.631659 types-aiobotocore-sso-admin-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20799 2023-03-11 12:27:23.627659 types-aiobotocore-sso-admin-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19221 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.631659 types-aiobotocore-sso-admin-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2137 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.627659 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/
--rw-r--r--   0 runner    (1001) docker     (123)     3748 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3747 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    36934 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    36877 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10664 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10662 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    16003 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    15989 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39786 2023-03-11 12:24:45.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    39737 2023-03-11 12:24:44.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:43.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.627659 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20799 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:27:23.000000 types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.518221 types-aiobotocore-sso-admin-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20793 2023-06-28 01:44:14.518221 types-aiobotocore-sso-admin-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19221 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:14.518221 types-aiobotocore-sso-admin-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.518221 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/
+-rw-r--r--   0 runner    (1001) docker     (123)     3748 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3747 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      937 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36933 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36876 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10873 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10871 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15937 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15924 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    39852 2023-06-28 01:41:34.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39803 2023-06-28 01:41:34.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:33.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.518221 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20793 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:44:14.000000 types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/LICENSE` & `types-aiobotocore-sso-admin-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sso-admin-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso-admin
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSOAdmin 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSOAdmin 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso-admin"></a>
 
 # types-aiobotocore-sso-admin
 
 [![PyPI - types-aiobotocore-sso-admin](https://img.shields.io/pypi/v/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-admin?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-admin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOAdmin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
+[aiobotocore.SSOAdmin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
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
 [types-aiobotocore-sso-admin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -379,15 +379,14 @@
     AccountAssignmentOperationStatusMetadataTypeDef,
     AccountAssignmentOperationStatusTypeDef,
     AccountAssignmentTypeDef,
     CustomerManagedPolicyReferenceTypeDef,
     AttachManagedPolicyToPermissionSetRequestRequestTypeDef,
     AttachedManagedPolicyTypeDef,
     CreateAccountAssignmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     PermissionSetTypeDef,
     DeleteAccountAssignmentRequestRequestTypeDef,
     DeleteInlinePolicyFromPermissionSetRequestRequestTypeDef,
     DeleteInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DeletePermissionSetRequestRequestTypeDef,
     DeletePermissionsBoundaryFromPermissionSetRequestRequestTypeDef,
@@ -395,70 +394,71 @@
     DescribeAccountAssignmentDeletionStatusRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribePermissionSetProvisioningStatusRequestRequestTypeDef,
     PermissionSetProvisioningStatusTypeDef,
     DescribePermissionSetRequestRequestTypeDef,
     DetachManagedPolicyFromPermissionSetRequestRequestTypeDef,
     GetInlinePolicyForPermissionSetRequestRequestTypeDef,
+    GetInlinePolicyForPermissionSetResponseTypeDef,
     GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef,
     InstanceMetadataTypeDef,
     OperationStatusFilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
     ListAccountAssignmentsRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
     ListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
+    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
     ListManagedPoliciesInPermissionSetRequestRequestTypeDef,
     PermissionSetProvisioningStatusMetadataTypeDef,
+    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
     ListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
+    ListPermissionSetsProvisionedToAccountResponseTypeDef,
+    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
     ListPermissionSetsRequestRequestTypeDef,
+    ListPermissionSetsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProvisionPermissionSetRequestRequestTypeDef,
     PutInlinePolicyToPermissionSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePermissionSetRequestRequestTypeDef,
     AccessControlAttributeTypeDef,
-    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
-    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
-    PermissionsBoundaryTypeDef,
+    ListAccountAssignmentCreationStatusResponseTypeDef,
+    ListAccountAssignmentDeletionStatusResponseTypeDef,
     CreateAccountAssignmentResponseTypeDef,
     DeleteAccountAssignmentResponseTypeDef,
     DescribeAccountAssignmentCreationStatusResponseTypeDef,
     DescribeAccountAssignmentDeletionStatusResponseTypeDef,
-    GetInlinePolicyForPermissionSetResponseTypeDef,
-    ListAccountAssignmentCreationStatusResponseTypeDef,
-    ListAccountAssignmentDeletionStatusResponseTypeDef,
     ListAccountAssignmentsResponseTypeDef,
-    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
+    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef,
+    PermissionsBoundaryTypeDef,
     ListManagedPoliciesInPermissionSetResponseTypeDef,
-    ListPermissionSetsProvisionedToAccountResponseTypeDef,
-    ListPermissionSetsResponseTypeDef,
     CreatePermissionSetRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreatePermissionSetResponseTypeDef,
     DescribePermissionSetResponseTypeDef,
     DescribePermissionSetProvisioningStatusResponseTypeDef,
     ProvisionPermissionSetResponseTypeDef,
     ListInstancesResponseTypeDef,
-    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
-    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
-    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
     ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
-    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
-    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
-    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusResponseTypeDef,
     InstanceAccessControlAttributeConfigurationTypeDef,
     GetPermissionsBoundaryForPermissionSetResponseTypeDef,
     PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef,
     CreateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef,
     UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
@@ -472,43 +472,43 @@
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/README.md` & `types-aiobotocore-sso-admin-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sso-admin"></a>
 
 # types-aiobotocore-sso-admin
 
 [![PyPI - types-aiobotocore-sso-admin](https://img.shields.io/pypi/v/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-admin?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-admin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOAdmin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
+[aiobotocore.SSOAdmin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
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
 [types-aiobotocore-sso-admin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -346,15 +346,14 @@
     AccountAssignmentOperationStatusMetadataTypeDef,
     AccountAssignmentOperationStatusTypeDef,
     AccountAssignmentTypeDef,
     CustomerManagedPolicyReferenceTypeDef,
     AttachManagedPolicyToPermissionSetRequestRequestTypeDef,
     AttachedManagedPolicyTypeDef,
     CreateAccountAssignmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     PermissionSetTypeDef,
     DeleteAccountAssignmentRequestRequestTypeDef,
     DeleteInlinePolicyFromPermissionSetRequestRequestTypeDef,
     DeleteInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DeletePermissionSetRequestRequestTypeDef,
     DeletePermissionsBoundaryFromPermissionSetRequestRequestTypeDef,
@@ -362,70 +361,71 @@
     DescribeAccountAssignmentDeletionStatusRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribePermissionSetProvisioningStatusRequestRequestTypeDef,
     PermissionSetProvisioningStatusTypeDef,
     DescribePermissionSetRequestRequestTypeDef,
     DetachManagedPolicyFromPermissionSetRequestRequestTypeDef,
     GetInlinePolicyForPermissionSetRequestRequestTypeDef,
+    GetInlinePolicyForPermissionSetResponseTypeDef,
     GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef,
     InstanceMetadataTypeDef,
     OperationStatusFilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
     ListAccountAssignmentsRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
     ListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
+    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
     ListManagedPoliciesInPermissionSetRequestRequestTypeDef,
     PermissionSetProvisioningStatusMetadataTypeDef,
+    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
     ListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
+    ListPermissionSetsProvisionedToAccountResponseTypeDef,
+    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
     ListPermissionSetsRequestRequestTypeDef,
+    ListPermissionSetsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProvisionPermissionSetRequestRequestTypeDef,
     PutInlinePolicyToPermissionSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePermissionSetRequestRequestTypeDef,
     AccessControlAttributeTypeDef,
-    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
-    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
-    PermissionsBoundaryTypeDef,
+    ListAccountAssignmentCreationStatusResponseTypeDef,
+    ListAccountAssignmentDeletionStatusResponseTypeDef,
     CreateAccountAssignmentResponseTypeDef,
     DeleteAccountAssignmentResponseTypeDef,
     DescribeAccountAssignmentCreationStatusResponseTypeDef,
     DescribeAccountAssignmentDeletionStatusResponseTypeDef,
-    GetInlinePolicyForPermissionSetResponseTypeDef,
-    ListAccountAssignmentCreationStatusResponseTypeDef,
-    ListAccountAssignmentDeletionStatusResponseTypeDef,
     ListAccountAssignmentsResponseTypeDef,
-    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
+    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef,
+    PermissionsBoundaryTypeDef,
     ListManagedPoliciesInPermissionSetResponseTypeDef,
-    ListPermissionSetsProvisionedToAccountResponseTypeDef,
-    ListPermissionSetsResponseTypeDef,
     CreatePermissionSetRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreatePermissionSetResponseTypeDef,
     DescribePermissionSetResponseTypeDef,
     DescribePermissionSetProvisioningStatusResponseTypeDef,
     ProvisionPermissionSetResponseTypeDef,
     ListInstancesResponseTypeDef,
-    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
-    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
-    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
     ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
-    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
-    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
-    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusResponseTypeDef,
     InstanceAccessControlAttributeConfigurationTypeDef,
     GetPermissionsBoundaryForPermissionSetResponseTypeDef,
     PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef,
     CreateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef,
     UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
@@ -439,43 +439,43 @@
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/setup.py` & `types-aiobotocore-sso-admin-2.5.1/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sso-admin.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sso-admin",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sso_admin"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSOAdmin 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SSOAdmin 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/"
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__init__.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__init__.pyi` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/__main__.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/__main__.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSOAdmin 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSOAdmin 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin\nOther"
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/client.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -490,15 +490,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/client/#list_permission_set_provisioning_status)
         """
 
     async def list_permission_sets(
         self, *, InstanceArn: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPermissionSetsResponseTypeDef:
         """
-        Lists the  PermissionSet s in an IAM Identity Center instance.
+        Lists the  PermissionSets in an IAM Identity Center instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Client.list_permission_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/client/#list_permission_sets)
         """
 
     async def list_permission_sets_provisioned_to_account(
         self,
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/client.pyi` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -455,15 +455,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Client.list_permission_set_provisioning_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/client/#list_permission_set_provisioning_status)
         """
     async def list_permission_sets(
         self, *, InstanceArn: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPermissionSetsResponseTypeDef:
         """
-        Lists the  PermissionSet s in an IAM Identity Center instance.
+        Lists the  PermissionSets in an IAM Identity Center instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Client.list_permission_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/client/#list_permission_sets)
         """
     async def list_permission_sets_provisioned_to_account(
         self,
         *,
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/literals.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -137,14 +137,15 @@
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
@@ -223,14 +224,15 @@
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
@@ -241,14 +243,15 @@
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
@@ -284,14 +287,15 @@
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
@@ -310,16 +314,19 @@
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
@@ -403,15 +410,17 @@
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/literals.pyi` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -135,14 +135,15 @@
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
@@ -221,14 +222,15 @@
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
@@ -239,14 +241,15 @@
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
@@ -282,14 +285,15 @@
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
@@ -308,16 +312,19 @@
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
@@ -401,15 +408,17 @@
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/paginator.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_managed_policies_in_permission_set_paginator: ListManagedPoliciesInPermissionSetPaginator = client.get_paginator("list_managed_policies_in_permission_set")
         list_permission_set_provisioning_status_paginator: ListPermissionSetProvisioningStatusPaginator = client.get_paginator("list_permission_set_provisioning_status")
         list_permission_sets_paginator: ListPermissionSetsPaginator = client.get_paginator("list_permission_sets")
         list_permission_sets_provisioned_to_account_paginator: ListPermissionSetsProvisionedToAccountPaginator = client.get_paginator("list_permission_sets_provisioned_to_account")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProvisioningStatusType
 from .type_defs import (
     ListAccountAssignmentCreationStatusResponseTypeDef,
@@ -59,20 +58,14 @@
     ListPermissionSetsProvisionedToAccountResponseTypeDef,
     ListPermissionSetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     OperationStatusFilterTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAccountAssignmentCreationStatusPaginator",
     "ListAccountAssignmentDeletionStatusPaginator",
     "ListAccountAssignmentsPaginator",
     "ListAccountsForProvisionedPermissionSetPaginator",
     "ListCustomerManagedPolicyReferencesInPermissionSetPaginator",
     "ListInstancesPaginator",
@@ -101,15 +94,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentCreationStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentCreationStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentcreationstatuspaginator)
         """
 
 
@@ -120,15 +113,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentDeletionStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentDeletionStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentdeletionstatuspaginator)
         """
 
 
@@ -140,15 +133,15 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         AccountId: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentspaginator)
         """
 
 
@@ -160,15 +153,15 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
         ProvisioningStatus: ProvisioningStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsForProvisionedPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountsForProvisionedPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountsforprovisionedpermissionsetpaginator)
         """
 
 
@@ -179,30 +172,30 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListCustomerManagedPolicyReferencesInPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listcustomermanagedpolicyreferencesinpermissionsetpaginator)
         """
 
 
 class ListInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listinstancespaginator)
         """
 
 
@@ -213,15 +206,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedPoliciesInPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListManagedPoliciesInPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listmanagedpoliciesinpermissionsetpaginator)
         """
 
 
@@ -232,30 +225,30 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetProvisioningStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetProvisioningStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetprovisioningstatuspaginator)
         """
 
 
 class ListPermissionSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetspaginator)
     """
 
     def paginate(
-        self, *, InstanceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetspaginator)
         """
 
 
@@ -267,28 +260,32 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         AccountId: str,
         ProvisioningStatus: ProvisioningStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetsProvisionedToAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetsProvisionedToAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetsprovisionedtoaccountpaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, InstanceArn: str, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        InstanceArn: str,
+        ResourceArn: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/paginator.pyi` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_managed_policies_in_permission_set_paginator: ListManagedPoliciesInPermissionSetPaginator = client.get_paginator("list_managed_policies_in_permission_set")
         list_permission_set_provisioning_status_paginator: ListPermissionSetProvisioningStatusPaginator = client.get_paginator("list_permission_set_provisioning_status")
         list_permission_sets_paginator: ListPermissionSetsPaginator = client.get_paginator("list_permission_sets")
         list_permission_sets_provisioned_to_account_paginator: ListPermissionSetsProvisionedToAccountPaginator = client.get_paginator("list_permission_sets_provisioned_to_account")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProvisioningStatusType
 from .type_defs import (
     ListAccountAssignmentCreationStatusResponseTypeDef,
@@ -59,19 +58,14 @@
     ListPermissionSetsProvisionedToAccountResponseTypeDef,
     ListPermissionSetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     OperationStatusFilterTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAccountAssignmentCreationStatusPaginator",
     "ListAccountAssignmentDeletionStatusPaginator",
     "ListAccountAssignmentsPaginator",
     "ListAccountsForProvisionedPermissionSetPaginator",
     "ListCustomerManagedPolicyReferencesInPermissionSetPaginator",
     "ListInstancesPaginator",
@@ -97,15 +91,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentCreationStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentCreationStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentcreationstatuspaginator)
         """
 
 class ListAccountAssignmentDeletionStatusPaginator(AioPaginator):
@@ -115,15 +109,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentDeletionStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignmentDeletionStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentdeletionstatuspaginator)
         """
 
 class ListAccountAssignmentsPaginator(AioPaginator):
@@ -134,15 +128,15 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         AccountId: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssignmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountAssignments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountassignmentspaginator)
         """
 
 class ListAccountsForProvisionedPermissionSetPaginator(AioPaginator):
@@ -153,15 +147,15 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
         ProvisioningStatus: ProvisioningStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsForProvisionedPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListAccountsForProvisionedPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listaccountsforprovisionedpermissionsetpaginator)
         """
 
 class ListCustomerManagedPolicyReferencesInPermissionSetPaginator(AioPaginator):
@@ -171,29 +165,29 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListCustomerManagedPolicyReferencesInPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listcustomermanagedpolicyreferencesinpermissionsetpaginator)
         """
 
 class ListInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listinstancespaginator)
         """
 
 class ListManagedPoliciesInPermissionSetPaginator(AioPaginator):
@@ -203,15 +197,15 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         PermissionSetArn: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedPoliciesInPermissionSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListManagedPoliciesInPermissionSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listmanagedpoliciesinpermissionsetpaginator)
         """
 
 class ListPermissionSetProvisioningStatusPaginator(AioPaginator):
@@ -221,29 +215,29 @@
     """
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         Filter: OperationStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetProvisioningStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetProvisioningStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetprovisioningstatuspaginator)
         """
 
 class ListPermissionSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetspaginator)
     """
 
     def paginate(
-        self, *, InstanceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetspaginator)
         """
 
 class ListPermissionSetsProvisionedToAccountPaginator(AioPaginator):
@@ -254,27 +248,31 @@
 
     def paginate(
         self,
         *,
         InstanceArn: str,
         AccountId: str,
         ProvisioningStatus: ProvisioningStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionSetsProvisionedToAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListPermissionSetsProvisionedToAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listpermissionsetsprovisionedtoaccountpaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, InstanceArn: str, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        InstanceArn: str,
+        ResourceArn: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/type_defs.py` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/type_defs.py`

 * *Files 12% similar despite different names*

```diff
@@ -38,15 +38,14 @@
     "AccountAssignmentOperationStatusMetadataTypeDef",
     "AccountAssignmentOperationStatusTypeDef",
     "AccountAssignmentTypeDef",
     "CustomerManagedPolicyReferenceTypeDef",
     "AttachManagedPolicyToPermissionSetRequestRequestTypeDef",
     "AttachedManagedPolicyTypeDef",
     "CreateAccountAssignmentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "PermissionSetTypeDef",
     "DeleteAccountAssignmentRequestRequestTypeDef",
     "DeleteInlinePolicyFromPermissionSetRequestRequestTypeDef",
     "DeleteInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DeletePermissionSetRequestRequestTypeDef",
     "DeletePermissionsBoundaryFromPermissionSetRequestRequestTypeDef",
@@ -54,70 +53,71 @@
     "DescribeAccountAssignmentDeletionStatusRequestRequestTypeDef",
     "DescribeInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DescribePermissionSetProvisioningStatusRequestRequestTypeDef",
     "PermissionSetProvisioningStatusTypeDef",
     "DescribePermissionSetRequestRequestTypeDef",
     "DetachManagedPolicyFromPermissionSetRequestRequestTypeDef",
     "GetInlinePolicyForPermissionSetRequestRequestTypeDef",
+    "GetInlinePolicyForPermissionSetResponseTypeDef",
     "GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef",
     "InstanceMetadataTypeDef",
     "OperationStatusFilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
     "ListAccountAssignmentsRequestRequestTypeDef",
+    "ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
     "ListAccountsForProvisionedPermissionSetRequestRequestTypeDef",
+    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    "ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
     "ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
+    "ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
     "ListManagedPoliciesInPermissionSetRequestRequestTypeDef",
     "PermissionSetProvisioningStatusMetadataTypeDef",
+    "ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
     "ListPermissionSetsProvisionedToAccountRequestRequestTypeDef",
+    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+    "ListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
     "ListPermissionSetsRequestRequestTypeDef",
+    "ListPermissionSetsResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ProvisionPermissionSetRequestRequestTypeDef",
     "PutInlinePolicyToPermissionSetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePermissionSetRequestRequestTypeDef",
     "AccessControlAttributeTypeDef",
-    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
-    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
-    "PermissionsBoundaryTypeDef",
+    "ListAccountAssignmentCreationStatusResponseTypeDef",
+    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     "CreateAccountAssignmentResponseTypeDef",
     "DeleteAccountAssignmentResponseTypeDef",
     "DescribeAccountAssignmentCreationStatusResponseTypeDef",
     "DescribeAccountAssignmentDeletionStatusResponseTypeDef",
-    "GetInlinePolicyForPermissionSetResponseTypeDef",
-    "ListAccountAssignmentCreationStatusResponseTypeDef",
-    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     "ListAccountAssignmentsResponseTypeDef",
-    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
+    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
     "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
+    "PermissionsBoundaryTypeDef",
     "ListManagedPoliciesInPermissionSetResponseTypeDef",
-    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
-    "ListPermissionSetsResponseTypeDef",
     "CreatePermissionSetRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreatePermissionSetResponseTypeDef",
     "DescribePermissionSetResponseTypeDef",
     "DescribePermissionSetProvisioningStatusResponseTypeDef",
     "ProvisionPermissionSetResponseTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    "ListAccountAssignmentDeletionStatusRequestRequestTypeDef",
-    "ListPermissionSetProvisioningStatusRequestRequestTypeDef",
     "ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
+    "ListAccountAssignmentCreationStatusRequestRequestTypeDef",
     "ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
-    "ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    "ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    "ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    "ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    "ListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     "ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
-    "ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    "ListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "ListPermissionSetProvisioningStatusRequestRequestTypeDef",
     "ListPermissionSetProvisioningStatusResponseTypeDef",
     "InstanceAccessControlAttributeConfigurationTypeDef",
     "GetPermissionsBoundaryForPermissionSetResponseTypeDef",
     "PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef",
     "CreateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef",
     "UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
@@ -214,25 +214,14 @@
         "TargetType": Literal["AWS_ACCOUNT"],
         "PermissionSetArn": str,
         "PrincipalType": PrincipalTypeType,
         "PrincipalId": str,
     },
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -358,14 +347,22 @@
     "GetInlinePolicyForPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
 
+GetInlinePolicyForPermissionSetResponseTypeDef = TypedDict(
+    "GetInlinePolicyForPermissionSetResponseTypeDef",
+    {
+        "InlinePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef = TypedDict(
     "GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -383,24 +380,38 @@
     "OperationStatusFilterTypeDef",
     {
         "Status": StatusValuesType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "InstanceArn": str,
+        "AccountId": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef(
+    _RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
+    _OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccountAssignmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountAssignmentsRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "AccountId": str,
         "PermissionSetArn": str,
     },
@@ -418,14 +429,38 @@
 class ListAccountAssignmentsRequestRequestTypeDef(
     _RequiredListAccountAssignmentsRequestRequestTypeDef,
     _OptionalListAccountAssignmentsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
+    {
+        "ProvisioningStatus": ProvisioningStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef(
+    _RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
+    _OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -443,14 +478,46 @@
 class ListAccountsForProvisionedPermissionSetRequestRequestTypeDef(
     _RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
     _OptionalListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
 ):
     pass
 
 
+ListAccountsForProvisionedPermissionSetResponseTypeDef = TypedDict(
+    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    {
+        "AccountIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef(
+    _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
+    _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -467,23 +534,54 @@
 class ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef(
     _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
     _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
 ):
     pass
 
 
+ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "ListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstancesRequestRequestTypeDef = TypedDict(
     "ListInstancesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef(
+    _RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+    _OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListManagedPoliciesInPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListManagedPoliciesInPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -510,14 +608,38 @@
         "Status": StatusValuesType,
         "RequestId": str,
         "CreatedDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "AccountId": str,
+    },
+)
+_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
+    {
+        "ProvisioningStatus": ProvisioningStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef(
+    _RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
+    _OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "AccountId": str,
     },
 )
@@ -535,14 +657,45 @@
 class ListPermissionSetsProvisionedToAccountRequestRequestTypeDef(
     _RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
     _OptionalListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
 ):
     pass
 
 
+ListPermissionSetsProvisionedToAccountResponseTypeDef = TypedDict(
+    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+    {
+        "NextToken": str,
+        "PermissionSets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
+    {
+        "InstanceArn": str,
+    },
+)
+_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPermissionSetsRequestListPermissionSetsPaginateTypeDef(
+    _RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
+    _OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPermissionSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionSetsRequestRequestTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListPermissionSetsRequestRequestTypeDef = TypedDict(
@@ -558,14 +711,46 @@
 class ListPermissionSetsRequestRequestTypeDef(
     _RequiredListPermissionSetsRequestRequestTypeDef,
     _OptionalListPermissionSetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListPermissionSetsResponseTypeDef = TypedDict(
+    "ListPermissionSetsResponseTypeDef",
+    {
+        "PermissionSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "InstanceArn": str,
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
         "InstanceArn": str,
         "ResourceArn": str,
     },
 )
@@ -581,14 +766,24 @@
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
+
 _RequiredProvisionPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredProvisionPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
         "TargetType": ProvisionTargetTypeType,
     },
@@ -614,14 +809,25 @@
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
         "InlinePolicy": str,
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
         "InstanceArn": str,
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
@@ -656,150 +862,115 @@
     "AccessControlAttributeTypeDef",
     {
         "Key": str,
         "Value": AccessControlAttributeValueTypeDef,
     },
 )
 
-AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef = TypedDict(
-    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
-    },
-)
-
-DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef = TypedDict(
-    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
+ListAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
+    "ListAccountAssignmentCreationStatusResponseTypeDef",
     {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
+        "AccountAssignmentsCreationStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PermissionsBoundaryTypeDef = TypedDict(
-    "PermissionsBoundaryTypeDef",
+ListAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
+    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     {
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
-        "ManagedPolicyArn": str,
+        "AccountAssignmentsDeletionStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 CreateAccountAssignmentResponseTypeDef = TypedDict(
     "CreateAccountAssignmentResponseTypeDef",
     {
         "AccountAssignmentCreationStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAccountAssignmentResponseTypeDef = TypedDict(
     "DeleteAccountAssignmentResponseTypeDef",
     {
         "AccountAssignmentDeletionStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
     "DescribeAccountAssignmentCreationStatusResponseTypeDef",
     {
         "AccountAssignmentCreationStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
     "DescribeAccountAssignmentDeletionStatusResponseTypeDef",
     {
         "AccountAssignmentDeletionStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInlinePolicyForPermissionSetResponseTypeDef = TypedDict(
-    "GetInlinePolicyForPermissionSetResponseTypeDef",
-    {
-        "InlinePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
-    "ListAccountAssignmentCreationStatusResponseTypeDef",
-    {
-        "AccountAssignmentsCreationStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
-    "ListAccountAssignmentDeletionStatusResponseTypeDef",
-    {
-        "AccountAssignmentsDeletionStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountAssignmentsResponseTypeDef = TypedDict(
     "ListAccountAssignmentsResponseTypeDef",
     {
         "AccountAssignments": List[AccountAssignmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccountsForProvisionedPermissionSetResponseTypeDef = TypedDict(
-    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef = TypedDict(
+    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
     {
-        "AccountIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
     },
 )
 
-ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef = TypedDict(
-    "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
+DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef = TypedDict(
+    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
     {
-        "CustomerManagedPolicyReferences": List[CustomerManagedPolicyReferenceTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
     },
 )
 
-ListManagedPoliciesInPermissionSetResponseTypeDef = TypedDict(
-    "ListManagedPoliciesInPermissionSetResponseTypeDef",
+ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef = TypedDict(
+    "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
     {
-        "AttachedManagedPolicies": List[AttachedManagedPolicyTypeDef],
+        "CustomerManagedPolicyReferences": List[CustomerManagedPolicyReferenceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPermissionSetsProvisionedToAccountResponseTypeDef = TypedDict(
-    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+PermissionsBoundaryTypeDef = TypedDict(
+    "PermissionsBoundaryTypeDef",
     {
-        "NextToken": str,
-        "PermissionSets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
+        "ManagedPolicyArn": str,
     },
+    total=False,
 )
 
-ListPermissionSetsResponseTypeDef = TypedDict(
-    "ListPermissionSetsResponseTypeDef",
+ListManagedPoliciesInPermissionSetResponseTypeDef = TypedDict(
+    "ListManagedPoliciesInPermissionSetResponseTypeDef",
     {
-        "PermissionSets": List[str],
+        "AttachedManagedPolicies": List[AttachedManagedPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePermissionSetRequestRequestTypeDef",
     {
         "Name": str,
@@ -826,15 +997,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "InstanceArn": str,
@@ -843,384 +1014,213 @@
     },
 )
 
 CreatePermissionSetResponseTypeDef = TypedDict(
     "CreatePermissionSetResponseTypeDef",
     {
         "PermissionSet": PermissionSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionSetResponseTypeDef = TypedDict(
     "DescribePermissionSetResponseTypeDef",
     {
         "PermissionSet": PermissionSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionSetProvisioningStatusResponseTypeDef = TypedDict(
     "DescribePermissionSetProvisioningStatusResponseTypeDef",
     {
         "PermissionSetProvisioningStatus": PermissionSetProvisioningStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionPermissionSetResponseTypeDef = TypedDict(
     "ProvisionPermissionSetResponseTypeDef",
     {
         "PermissionSetProvisioningStatus": PermissionSetProvisioningStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "Instances": List[InstanceMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    {
-        "MaxResults": int,
-        "NextToken": str,
-        "Filter": OperationStatusFilterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListAccountAssignmentCreationStatusRequestRequestTypeDef(
-    _RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef,
-    _OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef,
-):
-    pass
-
-
-_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef",
+_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
-_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef",
+_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filter": OperationStatusFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class ListAccountAssignmentDeletionStatusRequestRequestTypeDef(
-    _RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef,
-    _OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef,
+class ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef(
+    _RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+    _OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef",
+_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
     },
 )
-_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef",
+_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
 
-class ListPermissionSetProvisioningStatusRequestRequestTypeDef(
-    _RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef,
-    _OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef,
-):
-    pass
-
-
-_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
-    {
-        "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef(
-    _RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
-    _OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+class ListAccountAssignmentCreationStatusRequestRequestTypeDef(
+    _RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef,
+    _OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef,
 ):
     pass
 
 
 _RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef = TypedDict(
     "_RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef = TypedDict(
     "_OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
     {
         "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef(
     _RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
     _OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "AccountId": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef(
-    _RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-    _OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    {
-        "ProvisioningStatus": ProvisioningStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef(
-    _RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-    _OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef(
-    _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-    _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-):
-    pass
-
-
-ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
-        "PermissionSetArn": str,
     },
 )
-_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
+        "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
 
-class ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef(
-    _RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
-    _OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+class ListAccountAssignmentDeletionStatusRequestRequestTypeDef(
+    _RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef,
+    _OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef,
 ):
     pass
 
 
 _RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef = TypedDict(
     "_RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef = TypedDict(
     "_OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
     {
         "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef(
     _RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
     _OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "AccountId": str,
-    },
-)
-_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    {
-        "ProvisioningStatus": ProvisioningStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef(
-    _RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-    _OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPermissionSetsRequestListPermissionSetsPaginateTypeDef(
-    _RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-    _OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
-        "ResourceArn": str,
     },
 )
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
+        "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
 
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+class ListPermissionSetProvisioningStatusRequestRequestTypeDef(
+    _RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef,
+    _OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef,
 ):
     pass
 
 
 ListPermissionSetProvisioningStatusResponseTypeDef = TypedDict(
     "ListPermissionSetProvisioningStatusResponseTypeDef",
     {
         "PermissionSetsProvisioningStatus": List[PermissionSetProvisioningStatusMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceAccessControlAttributeConfigurationTypeDef = TypedDict(
     "InstanceAccessControlAttributeConfigurationTypeDef",
     {
         "AccessControlAttributes": Sequence[AccessControlAttributeTypeDef],
     },
 )
 
 GetPermissionsBoundaryForPermissionSetResponseTypeDef = TypedDict(
     "GetPermissionsBoundaryForPermissionSetResponseTypeDef",
     {
         "PermissionsBoundary": PermissionsBoundaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef = TypedDict(
     "PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
@@ -1243,15 +1243,15 @@
     "DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef",
     {
         "Status": InstanceAccessControlAttributeConfigurationStatusType,
         "StatusReason": str,
         "InstanceAccessControlAttributeConfiguration": (
             InstanceAccessControlAttributeConfigurationTypeDef
         ),
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     {
         "InstanceArn": str,
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin/type_defs.pyi` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -37,15 +37,14 @@
     "AccountAssignmentOperationStatusMetadataTypeDef",
     "AccountAssignmentOperationStatusTypeDef",
     "AccountAssignmentTypeDef",
     "CustomerManagedPolicyReferenceTypeDef",
     "AttachManagedPolicyToPermissionSetRequestRequestTypeDef",
     "AttachedManagedPolicyTypeDef",
     "CreateAccountAssignmentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "PermissionSetTypeDef",
     "DeleteAccountAssignmentRequestRequestTypeDef",
     "DeleteInlinePolicyFromPermissionSetRequestRequestTypeDef",
     "DeleteInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DeletePermissionSetRequestRequestTypeDef",
     "DeletePermissionsBoundaryFromPermissionSetRequestRequestTypeDef",
@@ -53,70 +52,71 @@
     "DescribeAccountAssignmentDeletionStatusRequestRequestTypeDef",
     "DescribeInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DescribePermissionSetProvisioningStatusRequestRequestTypeDef",
     "PermissionSetProvisioningStatusTypeDef",
     "DescribePermissionSetRequestRequestTypeDef",
     "DetachManagedPolicyFromPermissionSetRequestRequestTypeDef",
     "GetInlinePolicyForPermissionSetRequestRequestTypeDef",
+    "GetInlinePolicyForPermissionSetResponseTypeDef",
     "GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef",
     "InstanceMetadataTypeDef",
     "OperationStatusFilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
     "ListAccountAssignmentsRequestRequestTypeDef",
+    "ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
     "ListAccountsForProvisionedPermissionSetRequestRequestTypeDef",
+    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    "ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
     "ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
+    "ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
     "ListManagedPoliciesInPermissionSetRequestRequestTypeDef",
     "PermissionSetProvisioningStatusMetadataTypeDef",
+    "ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
     "ListPermissionSetsProvisionedToAccountRequestRequestTypeDef",
+    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+    "ListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
     "ListPermissionSetsRequestRequestTypeDef",
+    "ListPermissionSetsResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ProvisionPermissionSetRequestRequestTypeDef",
     "PutInlinePolicyToPermissionSetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePermissionSetRequestRequestTypeDef",
     "AccessControlAttributeTypeDef",
-    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
-    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
-    "PermissionsBoundaryTypeDef",
+    "ListAccountAssignmentCreationStatusResponseTypeDef",
+    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     "CreateAccountAssignmentResponseTypeDef",
     "DeleteAccountAssignmentResponseTypeDef",
     "DescribeAccountAssignmentCreationStatusResponseTypeDef",
     "DescribeAccountAssignmentDeletionStatusResponseTypeDef",
-    "GetInlinePolicyForPermissionSetResponseTypeDef",
-    "ListAccountAssignmentCreationStatusResponseTypeDef",
-    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     "ListAccountAssignmentsResponseTypeDef",
-    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
+    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
     "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
+    "PermissionsBoundaryTypeDef",
     "ListManagedPoliciesInPermissionSetResponseTypeDef",
-    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
-    "ListPermissionSetsResponseTypeDef",
     "CreatePermissionSetRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreatePermissionSetResponseTypeDef",
     "DescribePermissionSetResponseTypeDef",
     "DescribePermissionSetProvisioningStatusResponseTypeDef",
     "ProvisionPermissionSetResponseTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    "ListAccountAssignmentDeletionStatusRequestRequestTypeDef",
-    "ListPermissionSetProvisioningStatusRequestRequestTypeDef",
     "ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
+    "ListAccountAssignmentCreationStatusRequestRequestTypeDef",
     "ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
-    "ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    "ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    "ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    "ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    "ListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     "ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
-    "ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    "ListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    "ListPermissionSetProvisioningStatusRequestRequestTypeDef",
     "ListPermissionSetProvisioningStatusResponseTypeDef",
     "InstanceAccessControlAttributeConfigurationTypeDef",
     "GetPermissionsBoundaryForPermissionSetResponseTypeDef",
     "PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef",
     "CreateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     "DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef",
     "UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
@@ -211,25 +211,14 @@
         "TargetType": Literal["AWS_ACCOUNT"],
         "PermissionSetArn": str,
         "PrincipalType": PrincipalTypeType,
         "PrincipalId": str,
     },
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -355,14 +344,22 @@
     "GetInlinePolicyForPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
 
+GetInlinePolicyForPermissionSetResponseTypeDef = TypedDict(
+    "GetInlinePolicyForPermissionSetResponseTypeDef",
+    {
+        "InlinePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef = TypedDict(
     "GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -380,24 +377,36 @@
     "OperationStatusFilterTypeDef",
     {
         "Status": StatusValuesType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "InstanceArn": str,
+        "AccountId": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef(
+    _RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
+    _OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccountAssignmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountAssignmentsRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "AccountId": str,
         "PermissionSetArn": str,
     },
@@ -413,14 +422,36 @@
 
 class ListAccountAssignmentsRequestRequestTypeDef(
     _RequiredListAccountAssignmentsRequestRequestTypeDef,
     _OptionalListAccountAssignmentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
+    {
+        "ProvisioningStatus": ProvisioningStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef(
+    _RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
+    _OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -436,14 +467,44 @@
 
 class ListAccountsForProvisionedPermissionSetRequestRequestTypeDef(
     _RequiredListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
     _OptionalListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
 ):
     pass
 
+ListAccountsForProvisionedPermissionSetResponseTypeDef = TypedDict(
+    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+    {
+        "AccountIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef(
+    _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
+    _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
+):
+    pass
+
 _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -458,23 +519,52 @@
 
 class ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef(
     _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
     _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
 ):
     pass
 
+ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "ListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstancesRequestRequestTypeDef = TypedDict(
     "ListInstancesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
+    "_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+    },
+)
+_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
+    "_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef(
+    _RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+    _OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+):
+    pass
+
 _RequiredListManagedPoliciesInPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredListManagedPoliciesInPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
     },
 )
@@ -499,14 +589,36 @@
         "Status": StatusValuesType,
         "RequestId": str,
         "CreatedDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
+    {
+        "InstanceArn": str,
+        "AccountId": str,
+    },
+)
+_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
+    {
+        "ProvisioningStatus": ProvisioningStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef(
+    _RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
+    _OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
+):
+    pass
+
 _RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "AccountId": str,
     },
 )
@@ -522,14 +634,43 @@
 
 class ListPermissionSetsProvisionedToAccountRequestRequestTypeDef(
     _RequiredListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
     _OptionalListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
 ):
     pass
 
+ListPermissionSetsProvisionedToAccountResponseTypeDef = TypedDict(
+    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+    {
+        "NextToken": str,
+        "PermissionSets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
+    {
+        "InstanceArn": str,
+    },
+)
+_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPermissionSetsRequestListPermissionSetsPaginateTypeDef(
+    _RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
+    _OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPermissionSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionSetsRequestRequestTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListPermissionSetsRequestRequestTypeDef = TypedDict(
@@ -543,14 +684,44 @@
 
 class ListPermissionSetsRequestRequestTypeDef(
     _RequiredListPermissionSetsRequestRequestTypeDef,
     _OptionalListPermissionSetsRequestRequestTypeDef,
 ):
     pass
 
+ListPermissionSetsResponseTypeDef = TypedDict(
+    "ListPermissionSetsResponseTypeDef",
+    {
+        "PermissionSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "InstanceArn": str,
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
         "InstanceArn": str,
         "ResourceArn": str,
     },
 )
@@ -564,14 +735,24 @@
 
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
+
 _RequiredProvisionPermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredProvisionPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
         "TargetType": ProvisionTargetTypeType,
     },
@@ -595,14 +776,25 @@
     {
         "InstanceArn": str,
         "PermissionSetArn": str,
         "InlinePolicy": str,
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
         "InstanceArn": str,
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
@@ -635,150 +827,115 @@
     "AccessControlAttributeTypeDef",
     {
         "Key": str,
         "Value": AccessControlAttributeValueTypeDef,
     },
 )
 
-AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef = TypedDict(
-    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
-    },
-)
-
-DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef = TypedDict(
-    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
+ListAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
+    "ListAccountAssignmentCreationStatusResponseTypeDef",
     {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
+        "AccountAssignmentsCreationStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PermissionsBoundaryTypeDef = TypedDict(
-    "PermissionsBoundaryTypeDef",
+ListAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
+    "ListAccountAssignmentDeletionStatusResponseTypeDef",
     {
-        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
-        "ManagedPolicyArn": str,
+        "AccountAssignmentsDeletionStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 CreateAccountAssignmentResponseTypeDef = TypedDict(
     "CreateAccountAssignmentResponseTypeDef",
     {
         "AccountAssignmentCreationStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAccountAssignmentResponseTypeDef = TypedDict(
     "DeleteAccountAssignmentResponseTypeDef",
     {
         "AccountAssignmentDeletionStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
     "DescribeAccountAssignmentCreationStatusResponseTypeDef",
     {
         "AccountAssignmentCreationStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
     "DescribeAccountAssignmentDeletionStatusResponseTypeDef",
     {
         "AccountAssignmentDeletionStatus": AccountAssignmentOperationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInlinePolicyForPermissionSetResponseTypeDef = TypedDict(
-    "GetInlinePolicyForPermissionSetResponseTypeDef",
-    {
-        "InlinePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssignmentCreationStatusResponseTypeDef = TypedDict(
-    "ListAccountAssignmentCreationStatusResponseTypeDef",
-    {
-        "AccountAssignmentsCreationStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssignmentDeletionStatusResponseTypeDef = TypedDict(
-    "ListAccountAssignmentDeletionStatusResponseTypeDef",
-    {
-        "AccountAssignmentsDeletionStatus": List[AccountAssignmentOperationStatusMetadataTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountAssignmentsResponseTypeDef = TypedDict(
     "ListAccountAssignmentsResponseTypeDef",
     {
         "AccountAssignments": List[AccountAssignmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccountsForProvisionedPermissionSetResponseTypeDef = TypedDict(
-    "ListAccountsForProvisionedPermissionSetResponseTypeDef",
+AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef = TypedDict(
+    "AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef",
     {
-        "AccountIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
     },
 )
 
-ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef = TypedDict(
-    "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
+DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef = TypedDict(
+    "DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef",
     {
-        "CustomerManagedPolicyReferences": List[CustomerManagedPolicyReferenceTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InstanceArn": str,
+        "PermissionSetArn": str,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
     },
 )
 
-ListManagedPoliciesInPermissionSetResponseTypeDef = TypedDict(
-    "ListManagedPoliciesInPermissionSetResponseTypeDef",
+ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef = TypedDict(
+    "ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef",
     {
-        "AttachedManagedPolicies": List[AttachedManagedPolicyTypeDef],
+        "CustomerManagedPolicyReferences": List[CustomerManagedPolicyReferenceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPermissionSetsProvisionedToAccountResponseTypeDef = TypedDict(
-    "ListPermissionSetsProvisionedToAccountResponseTypeDef",
+PermissionsBoundaryTypeDef = TypedDict(
+    "PermissionsBoundaryTypeDef",
     {
-        "NextToken": str,
-        "PermissionSets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CustomerManagedPolicyReference": CustomerManagedPolicyReferenceTypeDef,
+        "ManagedPolicyArn": str,
     },
+    total=False,
 )
 
-ListPermissionSetsResponseTypeDef = TypedDict(
-    "ListPermissionSetsResponseTypeDef",
+ListManagedPoliciesInPermissionSetResponseTypeDef = TypedDict(
+    "ListManagedPoliciesInPermissionSetResponseTypeDef",
     {
-        "PermissionSets": List[str],
+        "AttachedManagedPolicies": List[AttachedManagedPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePermissionSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePermissionSetRequestRequestTypeDef",
     {
         "Name": str,
@@ -803,15 +960,15 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "InstanceArn": str,
@@ -820,358 +977,201 @@
     },
 )
 
 CreatePermissionSetResponseTypeDef = TypedDict(
     "CreatePermissionSetResponseTypeDef",
     {
         "PermissionSet": PermissionSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionSetResponseTypeDef = TypedDict(
     "DescribePermissionSetResponseTypeDef",
     {
         "PermissionSet": PermissionSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionSetProvisioningStatusResponseTypeDef = TypedDict(
     "DescribePermissionSetProvisioningStatusResponseTypeDef",
     {
         "PermissionSetProvisioningStatus": PermissionSetProvisioningStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionPermissionSetResponseTypeDef = TypedDict(
     "ProvisionPermissionSetResponseTypeDef",
     {
         "PermissionSetProvisioningStatus": PermissionSetProvisioningStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "Instances": List[InstanceMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef",
-    {
-        "MaxResults": int,
-        "NextToken": str,
-        "Filter": OperationStatusFilterTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountAssignmentCreationStatusRequestRequestTypeDef(
-    _RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef,
-    _OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef,
-):
-    pass
-
-_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef",
+_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
-_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef",
+_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filter": OperationStatusFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListAccountAssignmentDeletionStatusRequestRequestTypeDef(
-    _RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef,
-    _OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef,
+class ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef(
+    _RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+    _OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
 ):
     pass
 
-_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
-    "_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef",
+_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
     },
 )
-_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
-    "_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef",
+_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
-class ListPermissionSetProvisioningStatusRequestRequestTypeDef(
-    _RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef,
-    _OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef,
-):
-    pass
-
-_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef",
-    {
-        "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef(
-    _RequiredListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
-    _OptionalListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+class ListAccountAssignmentCreationStatusRequestRequestTypeDef(
+    _RequiredListAccountAssignmentCreationStatusRequestRequestTypeDef,
+    _OptionalListAccountAssignmentCreationStatusRequestRequestTypeDef,
 ):
     pass
 
 _RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef = TypedDict(
     "_RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef = TypedDict(
     "_OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef",
     {
         "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef(
     _RequiredListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
     _OptionalListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
 ):
     pass
 
-_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
-    "_RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "AccountId": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef = TypedDict(
-    "_OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef(
-    _RequiredListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-    _OptionalListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-):
-    pass
-
-_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef",
-    {
-        "ProvisioningStatus": ProvisioningStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef(
-    _RequiredListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-    _OptionalListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-):
-    pass
-
-_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "PermissionSetArn": str,
-    },
-)
-_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef(
-    _RequiredListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-    _OptionalListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-):
-    pass
-
-ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
-    "_RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
-        "PermissionSetArn": str,
     },
 )
-_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef = TypedDict(
-    "_OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef",
+_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
+        "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
-class ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef(
-    _RequiredListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
-    _OptionalListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+class ListAccountAssignmentDeletionStatusRequestRequestTypeDef(
+    _RequiredListAccountAssignmentDeletionStatusRequestRequestTypeDef,
+    _OptionalListAccountAssignmentDeletionStatusRequestRequestTypeDef,
 ):
     pass
 
 _RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef = TypedDict(
     "_RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
     {
         "InstanceArn": str,
     },
 )
 _OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef = TypedDict(
     "_OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef",
     {
         "Filter": OperationStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef(
     _RequiredListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
     _OptionalListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
 ):
     pass
 
-_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    {
-        "InstanceArn": str,
-        "AccountId": str,
-    },
-)
-_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef",
-    {
-        "ProvisioningStatus": ProvisioningStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef(
-    _RequiredListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-    _OptionalListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-):
-    pass
-
-_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    {
-        "InstanceArn": str,
-    },
-)
-_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPermissionSetsRequestListPermissionSetsPaginateTypeDef(
-    _RequiredListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-    _OptionalListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
+    "_RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef",
     {
         "InstanceArn": str,
-        "ResourceArn": str,
     },
 )
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef = TypedDict(
+    "_OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
+        "Filter": OperationStatusFilterTypeDef,
     },
     total=False,
 )
 
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+class ListPermissionSetProvisioningStatusRequestRequestTypeDef(
+    _RequiredListPermissionSetProvisioningStatusRequestRequestTypeDef,
+    _OptionalListPermissionSetProvisioningStatusRequestRequestTypeDef,
 ):
     pass
 
 ListPermissionSetProvisioningStatusResponseTypeDef = TypedDict(
     "ListPermissionSetProvisioningStatusResponseTypeDef",
     {
         "PermissionSetsProvisioningStatus": List[PermissionSetProvisioningStatusMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceAccessControlAttributeConfigurationTypeDef = TypedDict(
     "InstanceAccessControlAttributeConfigurationTypeDef",
     {
         "AccessControlAttributes": Sequence[AccessControlAttributeTypeDef],
     },
 )
 
 GetPermissionsBoundaryForPermissionSetResponseTypeDef = TypedDict(
     "GetPermissionsBoundaryForPermissionSetResponseTypeDef",
     {
         "PermissionsBoundary": PermissionsBoundaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef = TypedDict(
     "PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef",
     {
         "InstanceArn": str,
@@ -1194,15 +1194,15 @@
     "DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef",
     {
         "Status": InstanceAccessControlAttributeConfigurationStatusType,
         "StatusReason": str,
         "InstanceAccessControlAttributeConfiguration": (
             InstanceAccessControlAttributeConfigurationTypeDef
         ),
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef",
     {
         "InstanceArn": str,
```

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/PKG-INFO` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso-admin
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSOAdmin 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSOAdmin 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso-admin"></a>
 
 # types-aiobotocore-sso-admin
 
 [![PyPI - types-aiobotocore-sso-admin](https://img.shields.io/pypi/v/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-admin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-admin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-admin?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-admin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOAdmin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
+[aiobotocore.SSOAdmin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-admin.html#SSOAdmin)
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
 [types-aiobotocore-sso-admin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_admin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -379,15 +379,14 @@
     AccountAssignmentOperationStatusMetadataTypeDef,
     AccountAssignmentOperationStatusTypeDef,
     AccountAssignmentTypeDef,
     CustomerManagedPolicyReferenceTypeDef,
     AttachManagedPolicyToPermissionSetRequestRequestTypeDef,
     AttachedManagedPolicyTypeDef,
     CreateAccountAssignmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     PermissionSetTypeDef,
     DeleteAccountAssignmentRequestRequestTypeDef,
     DeleteInlinePolicyFromPermissionSetRequestRequestTypeDef,
     DeleteInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DeletePermissionSetRequestRequestTypeDef,
     DeletePermissionsBoundaryFromPermissionSetRequestRequestTypeDef,
@@ -395,70 +394,71 @@
     DescribeAccountAssignmentDeletionStatusRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribePermissionSetProvisioningStatusRequestRequestTypeDef,
     PermissionSetProvisioningStatusTypeDef,
     DescribePermissionSetRequestRequestTypeDef,
     DetachManagedPolicyFromPermissionSetRequestRequestTypeDef,
     GetInlinePolicyForPermissionSetRequestRequestTypeDef,
+    GetInlinePolicyForPermissionSetResponseTypeDef,
     GetPermissionsBoundaryForPermissionSetRequestRequestTypeDef,
     InstanceMetadataTypeDef,
     OperationStatusFilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
     ListAccountAssignmentsRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
     ListAccountsForProvisionedPermissionSetRequestRequestTypeDef,
+    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetRequestRequestTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
+    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
     ListManagedPoliciesInPermissionSetRequestRequestTypeDef,
     PermissionSetProvisioningStatusMetadataTypeDef,
+    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
     ListPermissionSetsProvisionedToAccountRequestRequestTypeDef,
+    ListPermissionSetsProvisionedToAccountResponseTypeDef,
+    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
     ListPermissionSetsRequestRequestTypeDef,
+    ListPermissionSetsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProvisionPermissionSetRequestRequestTypeDef,
     PutInlinePolicyToPermissionSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePermissionSetRequestRequestTypeDef,
     AccessControlAttributeTypeDef,
-    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
-    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
-    PermissionsBoundaryTypeDef,
+    ListAccountAssignmentCreationStatusResponseTypeDef,
+    ListAccountAssignmentDeletionStatusResponseTypeDef,
     CreateAccountAssignmentResponseTypeDef,
     DeleteAccountAssignmentResponseTypeDef,
     DescribeAccountAssignmentCreationStatusResponseTypeDef,
     DescribeAccountAssignmentDeletionStatusResponseTypeDef,
-    GetInlinePolicyForPermissionSetResponseTypeDef,
-    ListAccountAssignmentCreationStatusResponseTypeDef,
-    ListAccountAssignmentDeletionStatusResponseTypeDef,
     ListAccountAssignmentsResponseTypeDef,
-    ListAccountsForProvisionedPermissionSetResponseTypeDef,
+    AttachCustomerManagedPolicyReferenceToPermissionSetRequestRequestTypeDef,
+    DetachCustomerManagedPolicyReferenceFromPermissionSetRequestRequestTypeDef,
     ListCustomerManagedPolicyReferencesInPermissionSetResponseTypeDef,
+    PermissionsBoundaryTypeDef,
     ListManagedPoliciesInPermissionSetResponseTypeDef,
-    ListPermissionSetsProvisionedToAccountResponseTypeDef,
-    ListPermissionSetsResponseTypeDef,
     CreatePermissionSetRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreatePermissionSetResponseTypeDef,
     DescribePermissionSetResponseTypeDef,
     DescribePermissionSetProvisioningStatusResponseTypeDef,
     ProvisionPermissionSetResponseTypeDef,
     ListInstancesResponseTypeDef,
-    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
-    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
-    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListAccountAssignmentCreationStatusRequestListAccountAssignmentCreationStatusPaginateTypeDef,
+    ListAccountAssignmentCreationStatusRequestRequestTypeDef,
     ListAccountAssignmentDeletionStatusRequestListAccountAssignmentDeletionStatusPaginateTypeDef,
-    ListAccountAssignmentsRequestListAccountAssignmentsPaginateTypeDef,
-    ListAccountsForProvisionedPermissionSetRequestListAccountsForProvisionedPermissionSetPaginateTypeDef,
-    ListCustomerManagedPolicyReferencesInPermissionSetRequestListCustomerManagedPolicyReferencesInPermissionSetPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
-    ListManagedPoliciesInPermissionSetRequestListManagedPoliciesInPermissionSetPaginateTypeDef,
+    ListAccountAssignmentDeletionStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusRequestListPermissionSetProvisioningStatusPaginateTypeDef,
-    ListPermissionSetsProvisionedToAccountRequestListPermissionSetsProvisionedToAccountPaginateTypeDef,
-    ListPermissionSetsRequestListPermissionSetsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    ListPermissionSetProvisioningStatusRequestRequestTypeDef,
     ListPermissionSetProvisioningStatusResponseTypeDef,
     InstanceAccessControlAttributeConfigurationTypeDef,
     GetPermissionsBoundaryForPermissionSetResponseTypeDef,
     PutPermissionsBoundaryToPermissionSetRequestRequestTypeDef,
     CreateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
     DescribeInstanceAccessControlAttributeConfigurationResponseTypeDef,
     UpdateInstanceAccessControlAttributeConfigurationRequestRequestTypeDef,
@@ -472,43 +472,43 @@
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

### Comparing `types-aiobotocore-sso-admin-2.5.0.post1/types_aiobotocore_sso_admin.egg-info/SOURCES.txt` & `types-aiobotocore-sso-admin-2.5.1/types_aiobotocore_sso_admin.egg-info/SOURCES.txt`

 * *Files identical despite different names*

