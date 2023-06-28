# Comparing `tmp/types-aiobotocore-transfer-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-transfer-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-transfer-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-transfer-2.5.1.tar", last modified: Wed Jun 28 01:44:18 2023, max compression
```

## Comparing `types-aiobotocore-transfer-2.5.0.post1.tar` & `types-aiobotocore-transfer-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.939699 types-aiobotocore-transfer-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22110 2023-03-11 12:27:27.939699 types-aiobotocore-transfer-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20535 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:27.939699 types-aiobotocore-transfer-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.931699 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/
--rw-r--r--   0 runner    (1001) docker     (123)     2923 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    48774 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    48694 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11729 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11727 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12923 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12909 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    58839 2023-03-11 12:25:12.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    58750 2023-03-11 12:25:11.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2438 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2436 2023-03-11 12:25:10.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.939699 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22110 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      907 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:27.000000 types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.986228 types-aiobotocore-transfer-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22138 2023-06-28 01:44:17.986228 types-aiobotocore-transfer-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20569 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:17.986228 types-aiobotocore-transfer-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.978227 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/
+-rw-r--r--   0 runner    (1001) docker     (123)     2923 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48970 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48890 2023-06-28 01:41:59.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12176 2023-06-28 01:42:02.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12174 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12849 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12836 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    59204 2023-06-28 01:42:03.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59115 2023-06-28 01:42:02.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:58.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2438 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2436 2023-06-28 01:42:01.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.986228 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22138 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      907 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:17.000000 types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/LICENSE` & `types-aiobotocore-transfer-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/PKG-INFO` & `types-aiobotocore-transfer-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-transfer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Transfer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Transfer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-transfer"></a>
 
 # types-aiobotocore-transfer
 
 [![PyPI - types-aiobotocore-transfer](https://img.shields.io/pypi/v/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transfer?color=blue)](https://pypistats.org/packages/types-aiobotocore-transfer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Transfer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
+[aiobotocore.Transfer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
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
 [types-aiobotocore-transfer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -377,14 +377,15 @@
     MdnSigningAlgType,
     OverwriteExistingType,
     ProfileTypeType,
     ProtocolType,
     ServerOfflineWaiterName,
     ServerOnlineWaiterName,
     SetStatOptionType,
+    SftpAuthenticationMethodsType,
     SigningAlgType,
     StateType,
     TlsSessionResumptionModeType,
     WorkflowStepTypeType,
     TransferServiceName,
     ServiceName,
     ResourceServiceName,
@@ -406,19 +407,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_transfer.type_defs import (
     As2ConnectorConfigTypeDef,
     HomeDirectoryMapEntryTypeDef,
     PosixProfileTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessResponseTypeDef,
     TagTypeDef,
+    CreateAgreementResponseTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateProfileResponseTypeDef,
     EndpointDetailsTypeDef,
     IdentityProviderDetailsTypeDef,
     ProtocolDetailsTypeDef,
+    CreateServerResponseTypeDef,
+    CreateUserResponseTypeDef,
+    CreateWorkflowResponseTypeDef,
     CustomStepDetailsTypeDef,
     DeleteAccessRequestRequestTypeDef,
     DeleteAgreementRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteConnectorRequestRequestTypeDef,
     DeleteHostKeyRequestRequestTypeDef,
     DeleteProfileRequestRequestTypeDef,
@@ -439,80 +446,85 @@
     DescribeServerRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeUserRequestRequestTypeDef,
     DescribeWorkflowRequestRequestTypeDef,
     LoggingConfigurationTypeDef,
     SshPublicKeyTypeDef,
     EfsFileLocationTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionErrorTypeDef,
     S3FileLocationTypeDef,
+    ImportCertificateResponseTypeDef,
+    ImportHostKeyResponseTypeDef,
     ImportSshPublicKeyRequestRequestTypeDef,
+    ImportSshPublicKeyResponseTypeDef,
     S3InputFileLocationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessesRequestListAccessesPaginateTypeDef,
     ListAccessesRequestRequestTypeDef,
     ListedAccessTypeDef,
+    ListAgreementsRequestListAgreementsPaginateTypeDef,
     ListAgreementsRequestRequestTypeDef,
     ListedAgreementTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
     ListedCertificateTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListedConnectorTypeDef,
+    ListExecutionsRequestListExecutionsPaginateTypeDef,
     ListExecutionsRequestRequestTypeDef,
     ListHostKeysRequestRequestTypeDef,
     ListedHostKeyTypeDef,
+    ListProfilesRequestListProfilesPaginateTypeDef,
     ListProfilesRequestRequestTypeDef,
     ListedProfileTypeDef,
+    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
+    ListSecurityPoliciesResponseTypeDef,
+    ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     ListedServerTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListedUserTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     ListedWorkflowTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3TagTypeDef,
     SendWorkflowStepStateRequestRequestTypeDef,
     UserDetailsTypeDef,
     StartFileTransferRequestRequestTypeDef,
+    StartFileTransferResponseTypeDef,
     StartServerRequestRequestTypeDef,
     StopServerRequestRequestTypeDef,
     TestIdentityProviderRequestRequestTypeDef,
+    TestIdentityProviderResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAccessResponseTypeDef,
     UpdateAgreementRequestRequestTypeDef,
+    UpdateAgreementResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
+    UpdateCertificateResponseTypeDef,
+    UpdateConnectorResponseTypeDef,
     UpdateHostKeyRequestRequestTypeDef,
+    UpdateHostKeyResponseTypeDef,
     UpdateProfileRequestRequestTypeDef,
+    UpdateProfileResponseTypeDef,
+    UpdateServerResponseTypeDef,
+    UpdateUserResponseTypeDef,
     WorkflowDetailTypeDef,
     UpdateConnectorRequestRequestTypeDef,
     CreateAccessRequestRequestTypeDef,
     DescribedAccessTypeDef,
     UpdateAccessRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
-    CreateAccessResponseTypeDef,
-    CreateAgreementResponseTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    CreateServerResponseTypeDef,
-    CreateUserResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ImportCertificateResponseTypeDef,
-    ImportHostKeyResponseTypeDef,
-    ImportSshPublicKeyResponseTypeDef,
-    ListSecurityPoliciesResponseTypeDef,
-    StartFileTransferResponseTypeDef,
-    TestIdentityProviderResponseTypeDef,
-    UpdateAccessResponseTypeDef,
-    UpdateAgreementResponseTypeDef,
-    UpdateCertificateResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
-    UpdateHostKeyResponseTypeDef,
-    UpdateProfileResponseTypeDef,
-    UpdateServerResponseTypeDef,
-    UpdateUserResponseTypeDef,
     CreateAgreementRequestRequestTypeDef,
     CreateConnectorRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribedAgreementTypeDef,
     DescribedCertificateTypeDef,
     DescribedConnectorTypeDef,
@@ -525,25 +537,14 @@
     DescribeSecurityPolicyResponseTypeDef,
     DescribeServerRequestServerOfflineWaitTypeDef,
     DescribeServerRequestServerOnlineWaitTypeDef,
     DescribedUserTypeDef,
     ExecutionStepResultTypeDef,
     FileLocationTypeDef,
     InputFileLocationTypeDef,
-    ListAccessesRequestListAccessesPaginateTypeDef,
-    ListAgreementsRequestListAgreementsPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListExecutionsRequestListExecutionsPaginateTypeDef,
-    ListProfilesRequestListProfilesPaginateTypeDef,
-    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
-    ListServersRequestListServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListAccessesResponseTypeDef,
     ListAgreementsResponseTypeDef,
     ListCertificatesResponseTypeDef,
     ListConnectorsResponseTypeDef,
     ListHostKeysResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListServersResponseTypeDef,
@@ -584,43 +585,43 @@
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/README.md` & `types-aiobotocore-transfer-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-transfer"></a>
 
 # types-aiobotocore-transfer
 
 [![PyPI - types-aiobotocore-transfer](https://img.shields.io/pypi/v/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transfer?color=blue)](https://pypistats.org/packages/types-aiobotocore-transfer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Transfer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
+[aiobotocore.Transfer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
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
 [types-aiobotocore-transfer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,14 +344,15 @@
     MdnSigningAlgType,
     OverwriteExistingType,
     ProfileTypeType,
     ProtocolType,
     ServerOfflineWaiterName,
     ServerOnlineWaiterName,
     SetStatOptionType,
+    SftpAuthenticationMethodsType,
     SigningAlgType,
     StateType,
     TlsSessionResumptionModeType,
     WorkflowStepTypeType,
     TransferServiceName,
     ServiceName,
     ResourceServiceName,
@@ -373,19 +374,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_transfer.type_defs import (
     As2ConnectorConfigTypeDef,
     HomeDirectoryMapEntryTypeDef,
     PosixProfileTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessResponseTypeDef,
     TagTypeDef,
+    CreateAgreementResponseTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateProfileResponseTypeDef,
     EndpointDetailsTypeDef,
     IdentityProviderDetailsTypeDef,
     ProtocolDetailsTypeDef,
+    CreateServerResponseTypeDef,
+    CreateUserResponseTypeDef,
+    CreateWorkflowResponseTypeDef,
     CustomStepDetailsTypeDef,
     DeleteAccessRequestRequestTypeDef,
     DeleteAgreementRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteConnectorRequestRequestTypeDef,
     DeleteHostKeyRequestRequestTypeDef,
     DeleteProfileRequestRequestTypeDef,
@@ -406,80 +413,85 @@
     DescribeServerRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeUserRequestRequestTypeDef,
     DescribeWorkflowRequestRequestTypeDef,
     LoggingConfigurationTypeDef,
     SshPublicKeyTypeDef,
     EfsFileLocationTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionErrorTypeDef,
     S3FileLocationTypeDef,
+    ImportCertificateResponseTypeDef,
+    ImportHostKeyResponseTypeDef,
     ImportSshPublicKeyRequestRequestTypeDef,
+    ImportSshPublicKeyResponseTypeDef,
     S3InputFileLocationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessesRequestListAccessesPaginateTypeDef,
     ListAccessesRequestRequestTypeDef,
     ListedAccessTypeDef,
+    ListAgreementsRequestListAgreementsPaginateTypeDef,
     ListAgreementsRequestRequestTypeDef,
     ListedAgreementTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
     ListedCertificateTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListedConnectorTypeDef,
+    ListExecutionsRequestListExecutionsPaginateTypeDef,
     ListExecutionsRequestRequestTypeDef,
     ListHostKeysRequestRequestTypeDef,
     ListedHostKeyTypeDef,
+    ListProfilesRequestListProfilesPaginateTypeDef,
     ListProfilesRequestRequestTypeDef,
     ListedProfileTypeDef,
+    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
+    ListSecurityPoliciesResponseTypeDef,
+    ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     ListedServerTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListedUserTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     ListedWorkflowTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3TagTypeDef,
     SendWorkflowStepStateRequestRequestTypeDef,
     UserDetailsTypeDef,
     StartFileTransferRequestRequestTypeDef,
+    StartFileTransferResponseTypeDef,
     StartServerRequestRequestTypeDef,
     StopServerRequestRequestTypeDef,
     TestIdentityProviderRequestRequestTypeDef,
+    TestIdentityProviderResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAccessResponseTypeDef,
     UpdateAgreementRequestRequestTypeDef,
+    UpdateAgreementResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
+    UpdateCertificateResponseTypeDef,
+    UpdateConnectorResponseTypeDef,
     UpdateHostKeyRequestRequestTypeDef,
+    UpdateHostKeyResponseTypeDef,
     UpdateProfileRequestRequestTypeDef,
+    UpdateProfileResponseTypeDef,
+    UpdateServerResponseTypeDef,
+    UpdateUserResponseTypeDef,
     WorkflowDetailTypeDef,
     UpdateConnectorRequestRequestTypeDef,
     CreateAccessRequestRequestTypeDef,
     DescribedAccessTypeDef,
     UpdateAccessRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
-    CreateAccessResponseTypeDef,
-    CreateAgreementResponseTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    CreateServerResponseTypeDef,
-    CreateUserResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ImportCertificateResponseTypeDef,
-    ImportHostKeyResponseTypeDef,
-    ImportSshPublicKeyResponseTypeDef,
-    ListSecurityPoliciesResponseTypeDef,
-    StartFileTransferResponseTypeDef,
-    TestIdentityProviderResponseTypeDef,
-    UpdateAccessResponseTypeDef,
-    UpdateAgreementResponseTypeDef,
-    UpdateCertificateResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
-    UpdateHostKeyResponseTypeDef,
-    UpdateProfileResponseTypeDef,
-    UpdateServerResponseTypeDef,
-    UpdateUserResponseTypeDef,
     CreateAgreementRequestRequestTypeDef,
     CreateConnectorRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribedAgreementTypeDef,
     DescribedCertificateTypeDef,
     DescribedConnectorTypeDef,
@@ -492,25 +504,14 @@
     DescribeSecurityPolicyResponseTypeDef,
     DescribeServerRequestServerOfflineWaitTypeDef,
     DescribeServerRequestServerOnlineWaitTypeDef,
     DescribedUserTypeDef,
     ExecutionStepResultTypeDef,
     FileLocationTypeDef,
     InputFileLocationTypeDef,
-    ListAccessesRequestListAccessesPaginateTypeDef,
-    ListAgreementsRequestListAgreementsPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListExecutionsRequestListExecutionsPaginateTypeDef,
-    ListProfilesRequestListProfilesPaginateTypeDef,
-    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
-    ListServersRequestListServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListAccessesResponseTypeDef,
     ListAgreementsResponseTypeDef,
     ListCertificatesResponseTypeDef,
     ListConnectorsResponseTypeDef,
     ListHostKeysResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListServersResponseTypeDef,
@@ -551,43 +552,43 @@
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/setup.py` & `types-aiobotocore-transfer-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-transfer.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-transfer",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_transfer"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Transfer 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Transfer 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/"
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__init__.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__init__.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/__main__.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Transfer 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Transfer 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer\nOther"
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/client.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -250,15 +250,16 @@
         LoggingRole: str = ...,
         PostAuthenticationLoginBanner: str = ...,
         PreAuthenticationLoginBanner: str = ...,
         Protocols: Sequence[ProtocolType] = ...,
         ProtocolDetails: ProtocolDetailsTypeDef = ...,
         SecurityPolicyName: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        WorkflowDetails: WorkflowDetailsTypeDef = ...
+        WorkflowDetails: WorkflowDetailsTypeDef = ...,
+        StructuredLogDestinations: Sequence[str] = ...
     ) -> CreateServerResponseTypeDef:
         """
         Instantiates an auto-scaling virtual server based on the selected file transfer
         protocol in Amazon Web Services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#create_server)
@@ -313,15 +314,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_access)
         """
 
     async def delete_agreement(
         self, *, AgreementId: str, ServerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Delete the agreement that's specified in the provided `AgreementId` .
+        Delete the agreement that's specified in the provided `AgreementId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_agreement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_agreement)
         """
 
     async def delete_certificate(self, *, CertificateId: str) -> EmptyResponseMetadataTypeDef:
         """
@@ -329,25 +330,25 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_certificate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_certificate)
         """
 
     async def delete_connector(self, *, ConnectorId: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the agreement that's specified in the provided `ConnectorId` .
+        Deletes the agreement that's specified in the provided `ConnectorId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_connector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_connector)
         """
 
     async def delete_host_key(
         self, *, ServerId: str, HostKeyId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the host key that's specified in the `HoskKeyId` parameter.
+        Deletes the host key that's specified in the `HostKeyId` parameter.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_host_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_host_key)
         """
 
     async def delete_profile(self, *, ProfileId: str) -> EmptyResponseMetadataTypeDef:
         """
@@ -393,35 +394,35 @@
         """
 
     async def describe_access(
         self, *, ServerId: str, ExternalId: str
     ) -> DescribeAccessResponseTypeDef:
         """
         Describes the access that is assigned to the specific file transfer protocol-
-        enabled server, as identified by its `ServerId` property and its `ExternalId` .
+        enabled server, as identified by its `ServerId` property and its `ExternalId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_access)
         """
 
     async def describe_agreement(
         self, *, AgreementId: str, ServerId: str
     ) -> DescribeAgreementResponseTypeDef:
         """
-        Describes the agreement that's identified by the `AgreementId` .
+        Describes the agreement that's identified by the `AgreementId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_agreement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_agreement)
         """
 
     async def describe_certificate(
         self, *, CertificateId: str
     ) -> DescribeCertificateResponseTypeDef:
         """
-        Describes the certificate that's identified by the `CertificateId` .
+        Describes the certificate that's identified by the `CertificateId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_certificate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_certificate)
         """
 
     async def describe_connector(self, *, ConnectorId: str) -> DescribeConnectorResponseTypeDef:
         """
@@ -445,23 +446,23 @@
         """
 
     async def describe_host_key(
         self, *, ServerId: str, HostKeyId: str
     ) -> DescribeHostKeyResponseTypeDef:
         """
         Returns the details of the host key that's specified by the `HostKeyId` and
-        `ServerId` .
+        `ServerId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_host_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_host_key)
         """
 
     async def describe_profile(self, *, ProfileId: str) -> DescribeProfileResponseTypeDef:
         """
-        Returns the details of the profile that's specified by the `ProfileId` .
+        Returns the details of the profile that's specified by the `ProfileId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_profile)
         """
 
     async def describe_security_policy(
         self, *, SecurityPolicyName: str
@@ -549,17 +550,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#import_host_key)
         """
 
     async def import_ssh_public_key(
         self, *, ServerId: str, SshPublicKeyBody: str, UserName: str
     ) -> ImportSshPublicKeyResponseTypeDef:
         """
-        Adds a Secure Shell (SSH) public key to a user account identified by a
+        Adds a Secure Shell (SSH) public key to a Transfer Family user identified by a
         `UserName` value assigned to the specific file transfer protocol-enabled server,
-        identified by `ServerId` .
+        identified by `ServerId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.import_ssh_public_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#import_ssh_public_key)
         """
 
     async def list_accesses(
         self, *, ServerId: str, MaxResults: int = ..., NextToken: str = ...
@@ -603,15 +604,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_connectors)
         """
 
     async def list_executions(
         self, *, WorkflowId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListExecutionsResponseTypeDef:
         """
-        Lists all executions for the specified workflow.
+        Lists all in-progress executions for the specified workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_executions)
         """
 
     async def list_host_keys(
         self, *, ServerId: str, MaxResults: int = ..., NextToken: str = ...
@@ -678,15 +679,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_users)
         """
 
     async def list_workflows(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListWorkflowsResponseTypeDef:
         """
-        Lists all of your workflows.
+        Lists all workflows associated with your Amazon Web Services account for your
+        current region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_workflows)
         """
 
     async def send_workflow_step_state(
         self, *, WorkflowId: str, ExecutionId: str, Token: str, Status: CustomStepStatusType
@@ -744,15 +746,15 @@
         UserName: str,
         ServerProtocol: ProtocolType = ...,
         SourceIp: str = ...,
         UserPassword: str = ...
     ) -> TestIdentityProviderResponseTypeDef:
         """
         If the `IdentityProviderType` of a file transfer protocol-enabled server is
-        `AWS_DIRECTORY_SERVICE` or `API_Gateway` , tests whether your identity provider
+        `AWS_DIRECTORY_SERVICE` or `API_Gateway`, tests whether your identity provider
         is set up successfully.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.test_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#test_identity_provider)
         """
 
     async def untag_resource(
@@ -868,15 +870,16 @@
         HostKey: str = ...,
         IdentityProviderDetails: IdentityProviderDetailsTypeDef = ...,
         LoggingRole: str = ...,
         PostAuthenticationLoginBanner: str = ...,
         PreAuthenticationLoginBanner: str = ...,
         Protocols: Sequence[ProtocolType] = ...,
         SecurityPolicyName: str = ...,
-        WorkflowDetails: WorkflowDetailsTypeDef = ...
+        WorkflowDetails: WorkflowDetailsTypeDef = ...,
+        StructuredLogDestinations: Sequence[str] = ...
     ) -> UpdateServerResponseTypeDef:
         """
         Updates the file transfer protocol-enabled server's properties after that server
         has been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.update_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#update_server)
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/client.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -239,15 +239,16 @@
         LoggingRole: str = ...,
         PostAuthenticationLoginBanner: str = ...,
         PreAuthenticationLoginBanner: str = ...,
         Protocols: Sequence[ProtocolType] = ...,
         ProtocolDetails: ProtocolDetailsTypeDef = ...,
         SecurityPolicyName: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        WorkflowDetails: WorkflowDetailsTypeDef = ...
+        WorkflowDetails: WorkflowDetailsTypeDef = ...,
+        StructuredLogDestinations: Sequence[str] = ...
     ) -> CreateServerResponseTypeDef:
         """
         Instantiates an auto-scaling virtual server based on the selected file transfer
         protocol in Amazon Web Services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.create_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#create_server)
@@ -298,38 +299,38 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_access)
         """
     async def delete_agreement(
         self, *, AgreementId: str, ServerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Delete the agreement that's specified in the provided `AgreementId` .
+        Delete the agreement that's specified in the provided `AgreementId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_agreement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_agreement)
         """
     async def delete_certificate(self, *, CertificateId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the certificate that's specified in the `CertificateId` parameter.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_certificate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_certificate)
         """
     async def delete_connector(self, *, ConnectorId: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the agreement that's specified in the provided `ConnectorId` .
+        Deletes the agreement that's specified in the provided `ConnectorId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_connector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_connector)
         """
     async def delete_host_key(
         self, *, ServerId: str, HostKeyId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the host key that's specified in the `HoskKeyId` parameter.
+        Deletes the host key that's specified in the `HostKeyId` parameter.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.delete_host_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_host_key)
         """
     async def delete_profile(self, *, ProfileId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the profile that's specified in the `ProfileId` parameter.
@@ -369,33 +370,33 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#delete_workflow)
         """
     async def describe_access(
         self, *, ServerId: str, ExternalId: str
     ) -> DescribeAccessResponseTypeDef:
         """
         Describes the access that is assigned to the specific file transfer protocol-
-        enabled server, as identified by its `ServerId` property and its `ExternalId` .
+        enabled server, as identified by its `ServerId` property and its `ExternalId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_access)
         """
     async def describe_agreement(
         self, *, AgreementId: str, ServerId: str
     ) -> DescribeAgreementResponseTypeDef:
         """
-        Describes the agreement that's identified by the `AgreementId` .
+        Describes the agreement that's identified by the `AgreementId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_agreement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_agreement)
         """
     async def describe_certificate(
         self, *, CertificateId: str
     ) -> DescribeCertificateResponseTypeDef:
         """
-        Describes the certificate that's identified by the `CertificateId` .
+        Describes the certificate that's identified by the `CertificateId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_certificate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_certificate)
         """
     async def describe_connector(self, *, ConnectorId: str) -> DescribeConnectorResponseTypeDef:
         """
         Describes the connector that's identified by the `ConnectorId.` See also: [AWS
@@ -416,22 +417,22 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_execution)
         """
     async def describe_host_key(
         self, *, ServerId: str, HostKeyId: str
     ) -> DescribeHostKeyResponseTypeDef:
         """
         Returns the details of the host key that's specified by the `HostKeyId` and
-        `ServerId` .
+        `ServerId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_host_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_host_key)
         """
     async def describe_profile(self, *, ProfileId: str) -> DescribeProfileResponseTypeDef:
         """
-        Returns the details of the profile that's specified by the `ProfileId` .
+        Returns the details of the profile that's specified by the `ProfileId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.describe_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#describe_profile)
         """
     async def describe_security_policy(
         self, *, SecurityPolicyName: str
     ) -> DescribeSecurityPolicyResponseTypeDef:
@@ -511,17 +512,17 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.import_host_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#import_host_key)
         """
     async def import_ssh_public_key(
         self, *, ServerId: str, SshPublicKeyBody: str, UserName: str
     ) -> ImportSshPublicKeyResponseTypeDef:
         """
-        Adds a Secure Shell (SSH) public key to a user account identified by a
+        Adds a Secure Shell (SSH) public key to a Transfer Family user identified by a
         `UserName` value assigned to the specific file transfer protocol-enabled server,
-        identified by `ServerId` .
+        identified by `ServerId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.import_ssh_public_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#import_ssh_public_key)
         """
     async def list_accesses(
         self, *, ServerId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAccessesResponseTypeDef:
@@ -560,15 +561,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_connectors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_connectors)
         """
     async def list_executions(
         self, *, WorkflowId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListExecutionsResponseTypeDef:
         """
-        Lists all executions for the specified workflow.
+        Lists all in-progress executions for the specified workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_executions)
         """
     async def list_host_keys(
         self, *, ServerId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListHostKeysResponseTypeDef:
@@ -628,15 +629,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_users)
         """
     async def list_workflows(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListWorkflowsResponseTypeDef:
         """
-        Lists all of your workflows.
+        Lists all workflows associated with your Amazon Web Services account for your
+        current region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#list_workflows)
         """
     async def send_workflow_step_state(
         self, *, WorkflowId: str, ExecutionId: str, Token: str, Status: CustomStepStatusType
     ) -> Dict[str, Any]:
@@ -688,15 +690,15 @@
         UserName: str,
         ServerProtocol: ProtocolType = ...,
         SourceIp: str = ...,
         UserPassword: str = ...
     ) -> TestIdentityProviderResponseTypeDef:
         """
         If the `IdentityProviderType` of a file transfer protocol-enabled server is
-        `AWS_DIRECTORY_SERVICE` or `API_Gateway` , tests whether your identity provider
+        `AWS_DIRECTORY_SERVICE` or `API_Gateway`, tests whether your identity provider
         is set up successfully.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.test_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#test_identity_provider)
         """
     async def untag_resource(
         self, *, Arn: str, TagKeys: Sequence[str]
@@ -804,15 +806,16 @@
         HostKey: str = ...,
         IdentityProviderDetails: IdentityProviderDetailsTypeDef = ...,
         LoggingRole: str = ...,
         PostAuthenticationLoginBanner: str = ...,
         PreAuthenticationLoginBanner: str = ...,
         Protocols: Sequence[ProtocolType] = ...,
         SecurityPolicyName: str = ...,
-        WorkflowDetails: WorkflowDetailsTypeDef = ...
+        WorkflowDetails: WorkflowDetailsTypeDef = ...,
+        StructuredLogDestinations: Sequence[str] = ...
     ) -> UpdateServerResponseTypeDef:
         """
         Updates the file transfer protocol-enabled server's properties after that server
         has been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Client.update_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/client/#update_server)
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/literals.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -50,14 +50,15 @@
     "MdnSigningAlgType",
     "OverwriteExistingType",
     "ProfileTypeType",
     "ProtocolType",
     "ServerOfflineWaiterName",
     "ServerOnlineWaiterName",
     "SetStatOptionType",
+    "SftpAuthenticationMethodsType",
     "SigningAlgType",
     "StateType",
     "TlsSessionResumptionModeType",
     "WorkflowStepTypeType",
     "TransferServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -108,14 +109,17 @@
 MdnSigningAlgType = Literal["DEFAULT", "NONE", "SHA1", "SHA256", "SHA384", "SHA512"]
 OverwriteExistingType = Literal["FALSE", "TRUE"]
 ProfileTypeType = Literal["LOCAL", "PARTNER"]
 ProtocolType = Literal["AS2", "FTP", "FTPS", "SFTP"]
 ServerOfflineWaiterName = Literal["server_offline"]
 ServerOnlineWaiterName = Literal["server_online"]
 SetStatOptionType = Literal["DEFAULT", "ENABLE_NO_OP"]
+SftpAuthenticationMethodsType = Literal[
+    "PASSWORD", "PUBLIC_KEY", "PUBLIC_KEY_AND_PASSWORD", "PUBLIC_KEY_OR_PASSWORD"
+]
 SigningAlgType = Literal["NONE", "SHA1", "SHA256", "SHA384", "SHA512"]
 StateType = Literal["OFFLINE", "ONLINE", "STARTING", "START_FAILED", "STOPPING", "STOP_FAILED"]
 TlsSessionResumptionModeType = Literal["DISABLED", "ENABLED", "ENFORCED"]
 WorkflowStepTypeType = Literal["COPY", "CUSTOM", "DECRYPT", "DELETE", "TAG"]
 TransferServiceName = Literal["transfer"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -175,14 +179,15 @@
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
@@ -261,14 +266,15 @@
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
@@ -279,14 +285,15 @@
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
@@ -322,14 +329,15 @@
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
@@ -348,16 +356,19 @@
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
@@ -441,15 +452,17 @@
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
@@ -488,24 +501,28 @@
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/literals.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -49,14 +49,15 @@
     "MdnSigningAlgType",
     "OverwriteExistingType",
     "ProfileTypeType",
     "ProtocolType",
     "ServerOfflineWaiterName",
     "ServerOnlineWaiterName",
     "SetStatOptionType",
+    "SftpAuthenticationMethodsType",
     "SigningAlgType",
     "StateType",
     "TlsSessionResumptionModeType",
     "WorkflowStepTypeType",
     "TransferServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -106,14 +107,17 @@
 MdnSigningAlgType = Literal["DEFAULT", "NONE", "SHA1", "SHA256", "SHA384", "SHA512"]
 OverwriteExistingType = Literal["FALSE", "TRUE"]
 ProfileTypeType = Literal["LOCAL", "PARTNER"]
 ProtocolType = Literal["AS2", "FTP", "FTPS", "SFTP"]
 ServerOfflineWaiterName = Literal["server_offline"]
 ServerOnlineWaiterName = Literal["server_online"]
 SetStatOptionType = Literal["DEFAULT", "ENABLE_NO_OP"]
+SftpAuthenticationMethodsType = Literal[
+    "PASSWORD", "PUBLIC_KEY", "PUBLIC_KEY_AND_PASSWORD", "PUBLIC_KEY_OR_PASSWORD"
+]
 SigningAlgType = Literal["NONE", "SHA1", "SHA256", "SHA384", "SHA512"]
 StateType = Literal["OFFLINE", "ONLINE", "STARTING", "START_FAILED", "STOPPING", "STOP_FAILED"]
 TlsSessionResumptionModeType = Literal["DISABLED", "ENABLED", "ENFORCED"]
 WorkflowStepTypeType = Literal["COPY", "CUSTOM", "DECRYPT", "DELETE", "TAG"]
 TransferServiceName = Literal["transfer"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -173,14 +177,15 @@
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
@@ -259,14 +264,15 @@
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
@@ -277,14 +283,15 @@
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
@@ -320,14 +327,15 @@
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
@@ -346,16 +354,19 @@
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
@@ -439,15 +450,17 @@
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
@@ -486,24 +499,28 @@
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/paginator.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_security_policies_paginator: ListSecurityPoliciesPaginator = client.get_paginator("list_security_policies")
         list_servers_paginator: ListServersPaginator = client.get_paginator("list_servers")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProfileTypeType
 from .type_defs import (
     ListAccessesResponseTypeDef,
@@ -58,20 +57,14 @@
     ListServersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListUsersResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAccessesPaginator",
     "ListAgreementsPaginator",
     "ListCertificatesPaginator",
     "ListConnectorsPaginator",
     "ListExecutionsPaginator",
     "ListProfilesPaginator",
@@ -96,163 +89,166 @@
 class ListAccessesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAccesses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listaccessespaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAccesses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listaccessespaginator)
         """
 
 
 class ListAgreementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAgreements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listagreementspaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAgreementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAgreements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listagreementspaginator)
         """
 
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listcertificatespaginator)
         """
 
 
 class ListConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listconnectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listconnectorspaginator)
         """
 
 
 class ListExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listexecutionspaginator)
     """
 
     def paginate(
-        self, *, WorkflowId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkflowId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listexecutionspaginator)
         """
 
 
 class ListProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listprofilespaginator)
     """
 
     def paginate(
-        self, *, ProfileType: ProfileTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ProfileType: ProfileTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listprofilespaginator)
         """
 
 
 class ListSecurityPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListSecurityPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listsecuritypoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListSecurityPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listsecuritypoliciespaginator)
         """
 
 
 class ListServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listserverspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listserverspaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, Arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listtagsforresourcepaginator)
         """
 
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listuserspaginator)
         """
 
 
 class ListWorkflowsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListWorkflows)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listworkflowspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/paginator.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_security_policies_paginator: ListSecurityPoliciesPaginator = client.get_paginator("list_security_policies")
         list_servers_paginator: ListServersPaginator = client.get_paginator("list_servers")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProfileTypeType
 from .type_defs import (
     ListAccessesResponseTypeDef,
@@ -58,19 +57,14 @@
     ListServersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListUsersResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAccessesPaginator",
     "ListAgreementsPaginator",
     "ListCertificatesPaginator",
     "ListConnectorsPaginator",
     "ListExecutionsPaginator",
     "ListProfilesPaginator",
@@ -92,153 +86,156 @@
 class ListAccessesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAccesses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listaccessespaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAccesses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listaccessespaginator)
         """
 
 class ListAgreementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAgreements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listagreementspaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAgreementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListAgreements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listagreementspaginator)
         """
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listcertificatespaginator)
         """
 
 class ListConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listconnectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listconnectorspaginator)
         """
 
 class ListExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listexecutionspaginator)
     """
 
     def paginate(
-        self, *, WorkflowId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkflowId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listexecutionspaginator)
         """
 
 class ListProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listprofilespaginator)
     """
 
     def paginate(
-        self, *, ProfileType: ProfileTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ProfileType: ProfileTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listprofilespaginator)
         """
 
 class ListSecurityPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListSecurityPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listsecuritypoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListSecurityPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listsecuritypoliciespaginator)
         """
 
 class ListServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listserverspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listserverspaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, Arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listtagsforresourcepaginator)
         """
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, ServerId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listuserspaginator)
         """
 
 class ListWorkflowsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListWorkflows)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listworkflowspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/type_defs.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -31,14 +31,15 @@
     IdentityProviderTypeType,
     MdnResponseType,
     MdnSigningAlgType,
     OverwriteExistingType,
     ProfileTypeType,
     ProtocolType,
     SetStatOptionType,
+    SftpAuthenticationMethodsType,
     SigningAlgType,
     StateType,
     TlsSessionResumptionModeType,
     WorkflowStepTypeType,
 )
 
 if sys.version_info >= (3, 9):
@@ -51,19 +52,25 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "As2ConnectorConfigTypeDef",
     "HomeDirectoryMapEntryTypeDef",
     "PosixProfileTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessResponseTypeDef",
     "TagTypeDef",
+    "CreateAgreementResponseTypeDef",
+    "CreateConnectorResponseTypeDef",
+    "CreateProfileResponseTypeDef",
     "EndpointDetailsTypeDef",
     "IdentityProviderDetailsTypeDef",
     "ProtocolDetailsTypeDef",
+    "CreateServerResponseTypeDef",
+    "CreateUserResponseTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "CustomStepDetailsTypeDef",
     "DeleteAccessRequestRequestTypeDef",
     "DeleteAgreementRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteConnectorRequestRequestTypeDef",
     "DeleteHostKeyRequestRequestTypeDef",
     "DeleteProfileRequestRequestTypeDef",
@@ -84,80 +91,85 @@
     "DescribeServerRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "DescribeWorkflowRequestRequestTypeDef",
     "LoggingConfigurationTypeDef",
     "SshPublicKeyTypeDef",
     "EfsFileLocationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExecutionErrorTypeDef",
     "S3FileLocationTypeDef",
+    "ImportCertificateResponseTypeDef",
+    "ImportHostKeyResponseTypeDef",
     "ImportSshPublicKeyRequestRequestTypeDef",
+    "ImportSshPublicKeyResponseTypeDef",
     "S3InputFileLocationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessesRequestListAccessesPaginateTypeDef",
     "ListAccessesRequestRequestTypeDef",
     "ListedAccessTypeDef",
+    "ListAgreementsRequestListAgreementsPaginateTypeDef",
     "ListAgreementsRequestRequestTypeDef",
     "ListedAgreementTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
     "ListedCertificateTypeDef",
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     "ListConnectorsRequestRequestTypeDef",
     "ListedConnectorTypeDef",
+    "ListExecutionsRequestListExecutionsPaginateTypeDef",
     "ListExecutionsRequestRequestTypeDef",
     "ListHostKeysRequestRequestTypeDef",
     "ListedHostKeyTypeDef",
+    "ListProfilesRequestListProfilesPaginateTypeDef",
     "ListProfilesRequestRequestTypeDef",
     "ListedProfileTypeDef",
+    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
     "ListSecurityPoliciesRequestRequestTypeDef",
+    "ListSecurityPoliciesResponseTypeDef",
+    "ListServersRequestListServersPaginateTypeDef",
     "ListServersRequestRequestTypeDef",
     "ListedServerTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "ListedUserTypeDef",
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "ListedWorkflowTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3TagTypeDef",
     "SendWorkflowStepStateRequestRequestTypeDef",
     "UserDetailsTypeDef",
     "StartFileTransferRequestRequestTypeDef",
+    "StartFileTransferResponseTypeDef",
     "StartServerRequestRequestTypeDef",
     "StopServerRequestRequestTypeDef",
     "TestIdentityProviderRequestRequestTypeDef",
+    "TestIdentityProviderResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAccessResponseTypeDef",
     "UpdateAgreementRequestRequestTypeDef",
+    "UpdateAgreementResponseTypeDef",
     "UpdateCertificateRequestRequestTypeDef",
+    "UpdateCertificateResponseTypeDef",
+    "UpdateConnectorResponseTypeDef",
     "UpdateHostKeyRequestRequestTypeDef",
+    "UpdateHostKeyResponseTypeDef",
     "UpdateProfileRequestRequestTypeDef",
+    "UpdateProfileResponseTypeDef",
+    "UpdateServerResponseTypeDef",
+    "UpdateUserResponseTypeDef",
     "WorkflowDetailTypeDef",
     "UpdateConnectorRequestRequestTypeDef",
     "CreateAccessRequestRequestTypeDef",
     "DescribedAccessTypeDef",
     "UpdateAccessRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
-    "CreateAccessResponseTypeDef",
-    "CreateAgreementResponseTypeDef",
-    "CreateConnectorResponseTypeDef",
-    "CreateProfileResponseTypeDef",
-    "CreateServerResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ImportCertificateResponseTypeDef",
-    "ImportHostKeyResponseTypeDef",
-    "ImportSshPublicKeyResponseTypeDef",
-    "ListSecurityPoliciesResponseTypeDef",
-    "StartFileTransferResponseTypeDef",
-    "TestIdentityProviderResponseTypeDef",
-    "UpdateAccessResponseTypeDef",
-    "UpdateAgreementResponseTypeDef",
-    "UpdateCertificateResponseTypeDef",
-    "UpdateConnectorResponseTypeDef",
-    "UpdateHostKeyResponseTypeDef",
-    "UpdateProfileResponseTypeDef",
-    "UpdateServerResponseTypeDef",
-    "UpdateUserResponseTypeDef",
     "CreateAgreementRequestRequestTypeDef",
     "CreateConnectorRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DescribedAgreementTypeDef",
     "DescribedCertificateTypeDef",
     "DescribedConnectorTypeDef",
@@ -170,25 +182,14 @@
     "DescribeSecurityPolicyResponseTypeDef",
     "DescribeServerRequestServerOfflineWaitTypeDef",
     "DescribeServerRequestServerOnlineWaitTypeDef",
     "DescribedUserTypeDef",
     "ExecutionStepResultTypeDef",
     "FileLocationTypeDef",
     "InputFileLocationTypeDef",
-    "ListAccessesRequestListAccessesPaginateTypeDef",
-    "ListAgreementsRequestListAgreementsPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    "ListExecutionsRequestListExecutionsPaginateTypeDef",
-    "ListProfilesRequestListProfilesPaginateTypeDef",
-    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
-    "ListServersRequestListServersPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListAccessesResponseTypeDef",
     "ListAgreementsResponseTypeDef",
     "ListCertificatesResponseTypeDef",
     "ListConnectorsResponseTypeDef",
     "ListHostKeysResponseTypeDef",
     "ListProfilesResponseTypeDef",
     "ListServersResponseTypeDef",
@@ -260,33 +261,55 @@
 )
 
 
 class PosixProfileTypeDef(_RequiredPosixProfileTypeDef, _OptionalPosixProfileTypeDef):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAccessResponseTypeDef = TypedDict(
+    "CreateAccessResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServerId": str,
+        "ExternalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAgreementResponseTypeDef = TypedDict(
+    "CreateAgreementResponseTypeDef",
+    {
+        "AgreementId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateConnectorResponseTypeDef = TypedDict(
+    "CreateConnectorResponseTypeDef",
+    {
+        "ConnectorId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileResponseTypeDef = TypedDict(
+    "CreateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EndpointDetailsTypeDef = TypedDict(
     "EndpointDetailsTypeDef",
     {
         "AddressAllocationIds": Sequence[str],
         "SubnetIds": Sequence[str],
         "VpcEndpointId": str,
         "VpcId": str,
@@ -298,14 +321,15 @@
 IdentityProviderDetailsTypeDef = TypedDict(
     "IdentityProviderDetailsTypeDef",
     {
         "Url": str,
         "InvocationRole": str,
         "DirectoryId": str,
         "Function": str,
+        "SftpAuthenticationMethods": SftpAuthenticationMethodsType,
     },
     total=False,
 )
 
 ProtocolDetailsTypeDef = TypedDict(
     "ProtocolDetailsTypeDef",
     {
@@ -313,14 +337,39 @@
         "TlsSessionResumptionMode": TlsSessionResumptionModeType,
         "SetStatOption": SetStatOptionType,
         "As2Transports": Sequence[Literal["HTTP"]],
     },
     total=False,
 )
 
+CreateServerResponseTypeDef = TypedDict(
+    "CreateServerResponseTypeDef",
+    {
+        "ServerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "ServerId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "WorkflowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomStepDetailsTypeDef = TypedDict(
     "CustomStepDetailsTypeDef",
     {
         "Name": str,
         "Target": str,
         "TimeoutSeconds": int,
         "SourceFileLocation": str,
@@ -552,14 +601,21 @@
     {
         "FileSystemId": str,
         "Path": str,
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
 ExecutionErrorTypeDef = TypedDict(
     "ExecutionErrorTypeDef",
     {
         "Type": ExecutionErrorTypeType,
         "Message": str,
     },
 )
@@ -571,42 +627,81 @@
         "Key": str,
         "VersionId": str,
         "Etag": str,
     },
     total=False,
 )
 
+ImportCertificateResponseTypeDef = TypedDict(
+    "ImportCertificateResponseTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportHostKeyResponseTypeDef = TypedDict(
+    "ImportHostKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "HostKeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImportSshPublicKeyRequestRequestTypeDef = TypedDict(
     "ImportSshPublicKeyRequestRequestTypeDef",
     {
         "ServerId": str,
         "SshPublicKeyBody": str,
         "UserName": str,
     },
 )
 
+ImportSshPublicKeyResponseTypeDef = TypedDict(
+    "ImportSshPublicKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "SshPublicKeyId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3InputFileLocationTypeDef = TypedDict(
     "S3InputFileLocationTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
+    "_RequiredListAccessesRequestListAccessesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServerId": str,
+    },
+)
+_OptionalListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
+    "_OptionalListAccessesRequestListAccessesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAccessesRequestListAccessesPaginateTypeDef(
+    _RequiredListAccessesRequestListAccessesPaginateTypeDef,
+    _OptionalListAccessesRequestListAccessesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccessesRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessesRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 _OptionalListAccessesRequestRequestTypeDef = TypedDict(
@@ -632,14 +727,36 @@
         "HomeDirectoryType": HomeDirectoryTypeType,
         "Role": str,
         "ExternalId": str,
     },
     total=False,
 )
 
+_RequiredListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
+    "_RequiredListAgreementsRequestListAgreementsPaginateTypeDef",
+    {
+        "ServerId": str,
+    },
+)
+_OptionalListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
+    "_OptionalListAgreementsRequestListAgreementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAgreementsRequestListAgreementsPaginateTypeDef(
+    _RequiredListAgreementsRequestListAgreementsPaginateTypeDef,
+    _OptionalListAgreementsRequestListAgreementsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAgreementsRequestRequestTypeDef = TypedDict(
     "_RequiredListAgreementsRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 _OptionalListAgreementsRequestRequestTypeDef = TypedDict(
@@ -668,14 +785,22 @@
         "ServerId": str,
         "LocalProfileId": str,
         "PartnerProfileId": str,
     },
     total=False,
 )
 
+ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCertificatesRequestRequestTypeDef = TypedDict(
     "ListCertificatesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -692,14 +817,22 @@
         "InactiveDate": datetime,
         "Type": CertificateTypeType,
         "Description": str,
     },
     total=False,
 )
 
+ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConnectorsRequestRequestTypeDef = TypedDict(
     "ListConnectorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -711,14 +844,36 @@
         "Arn": str,
         "ConnectorId": str,
         "Url": str,
     },
     total=False,
 )
 
+_RequiredListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListExecutionsRequestListExecutionsPaginateTypeDef",
+    {
+        "WorkflowId": str,
+    },
+)
+_OptionalListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListExecutionsRequestListExecutionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListExecutionsRequestListExecutionsPaginateTypeDef(
+    _RequiredListExecutionsRequestListExecutionsPaginateTypeDef,
+    _OptionalListExecutionsRequestListExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExecutionsRequestRequestTypeDef",
     {
         "WorkflowId": str,
     },
 )
 _OptionalListExecutionsRequestRequestTypeDef = TypedDict(
@@ -778,14 +933,23 @@
 )
 
 
 class ListedHostKeyTypeDef(_RequiredListedHostKeyTypeDef, _OptionalListedHostKeyTypeDef):
     pass
 
 
+ListProfilesRequestListProfilesPaginateTypeDef = TypedDict(
+    "ListProfilesRequestListProfilesPaginateTypeDef",
+    {
+        "ProfileType": ProfileTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProfilesRequestRequestTypeDef = TypedDict(
     "ListProfilesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ProfileType": ProfileTypeType,
     },
@@ -799,23 +963,48 @@
         "ProfileId": str,
         "As2Id": str,
         "ProfileType": ProfileTypeType,
     },
     total=False,
 )
 
+ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef = TypedDict(
+    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecurityPoliciesRequestRequestTypeDef = TypedDict(
     "ListSecurityPoliciesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListSecurityPoliciesResponseTypeDef = TypedDict(
+    "ListSecurityPoliciesResponseTypeDef",
+    {
+        "NextToken": str,
+        "SecurityPolicyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListServersRequestListServersPaginateTypeDef = TypedDict(
+    "ListServersRequestListServersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServersRequestRequestTypeDef = TypedDict(
     "ListServersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -842,14 +1031,36 @@
 )
 
 
 class ListedServerTypeDef(_RequiredListedServerTypeDef, _OptionalListedServerTypeDef):
     pass
 
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "Arn": str,
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
         "Arn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -865,14 +1076,36 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "ServerId": str,
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
         "ServerId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -910,14 +1143,22 @@
 )
 
 
 class ListedUserTypeDef(_RequiredListedUserTypeDef, _OptionalListedUserTypeDef):
     pass
 
 
+ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -929,14 +1170,35 @@
         "WorkflowId": str,
         "Description": str,
         "Arn": str,
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
 S3TagTypeDef = TypedDict(
     "S3TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -975,14 +1237,22 @@
     "StartFileTransferRequestRequestTypeDef",
     {
         "ConnectorId": str,
         "SendFilePaths": Sequence[str],
     },
 )
 
+StartFileTransferResponseTypeDef = TypedDict(
+    "StartFileTransferResponseTypeDef",
+    {
+        "TransferId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartServerRequestRequestTypeDef = TypedDict(
     "StartServerRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 
@@ -1014,22 +1284,42 @@
 class TestIdentityProviderRequestRequestTypeDef(
     _RequiredTestIdentityProviderRequestRequestTypeDef,
     _OptionalTestIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
 
+TestIdentityProviderResponseTypeDef = TypedDict(
+    "TestIdentityProviderResponseTypeDef",
+    {
+        "Response": str,
+        "StatusCode": int,
+        "Message": str,
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAccessResponseTypeDef = TypedDict(
+    "UpdateAccessResponseTypeDef",
+    {
+        "ServerId": str,
+        "ExternalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAgreementRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAgreementRequestRequestTypeDef",
     {
         "AgreementId": str,
         "ServerId": str,
     },
 )
@@ -1049,14 +1339,22 @@
 
 class UpdateAgreementRequestRequestTypeDef(
     _RequiredUpdateAgreementRequestRequestTypeDef, _OptionalUpdateAgreementRequestRequestTypeDef
 ):
     pass
 
 
+UpdateAgreementResponseTypeDef = TypedDict(
+    "UpdateAgreementResponseTypeDef",
+    {
+        "AgreementId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCertificateRequestRequestTypeDef",
     {
         "CertificateId": str,
     },
 )
 _OptionalUpdateCertificateRequestRequestTypeDef = TypedDict(
@@ -1072,23 +1370,48 @@
 
 class UpdateCertificateRequestRequestTypeDef(
     _RequiredUpdateCertificateRequestRequestTypeDef, _OptionalUpdateCertificateRequestRequestTypeDef
 ):
     pass
 
 
+UpdateCertificateResponseTypeDef = TypedDict(
+    "UpdateCertificateResponseTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateConnectorResponseTypeDef = TypedDict(
+    "UpdateConnectorResponseTypeDef",
+    {
+        "ConnectorId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateHostKeyRequestRequestTypeDef = TypedDict(
     "UpdateHostKeyRequestRequestTypeDef",
     {
         "ServerId": str,
         "HostKeyId": str,
         "Description": str,
     },
 )
 
+UpdateHostKeyResponseTypeDef = TypedDict(
+    "UpdateHostKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "HostKeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProfileRequestRequestTypeDef",
     {
         "ProfileId": str,
     },
 )
 _OptionalUpdateProfileRequestRequestTypeDef = TypedDict(
@@ -1102,14 +1425,39 @@
 
 class UpdateProfileRequestRequestTypeDef(
     _RequiredUpdateProfileRequestRequestTypeDef, _OptionalUpdateProfileRequestRequestTypeDef
 ):
     pass
 
 
+UpdateProfileResponseTypeDef = TypedDict(
+    "UpdateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateServerResponseTypeDef = TypedDict(
+    "UpdateServerResponseTypeDef",
+    {
+        "ServerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateUserResponseTypeDef = TypedDict(
+    "UpdateUserResponseTypeDef",
+    {
+        "ServerId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowDetailTypeDef = TypedDict(
     "WorkflowDetailTypeDef",
     {
         "WorkflowId": str,
         "ExecutionRole": str,
     },
 )
@@ -1229,201 +1577,14 @@
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
 ):
     pass
 
 
-CreateAccessResponseTypeDef = TypedDict(
-    "CreateAccessResponseTypeDef",
-    {
-        "ServerId": str,
-        "ExternalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAgreementResponseTypeDef = TypedDict(
-    "CreateAgreementResponseTypeDef",
-    {
-        "AgreementId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConnectorResponseTypeDef = TypedDict(
-    "CreateConnectorResponseTypeDef",
-    {
-        "ConnectorId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProfileResponseTypeDef = TypedDict(
-    "CreateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateServerResponseTypeDef = TypedDict(
-    "CreateServerResponseTypeDef",
-    {
-        "ServerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "ServerId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
-    {
-        "WorkflowId": str,
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
-ImportCertificateResponseTypeDef = TypedDict(
-    "ImportCertificateResponseTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportHostKeyResponseTypeDef = TypedDict(
-    "ImportHostKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "HostKeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSshPublicKeyResponseTypeDef = TypedDict(
-    "ImportSshPublicKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "SshPublicKeyId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSecurityPoliciesResponseTypeDef = TypedDict(
-    "ListSecurityPoliciesResponseTypeDef",
-    {
-        "NextToken": str,
-        "SecurityPolicyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFileTransferResponseTypeDef = TypedDict(
-    "StartFileTransferResponseTypeDef",
-    {
-        "TransferId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestIdentityProviderResponseTypeDef = TypedDict(
-    "TestIdentityProviderResponseTypeDef",
-    {
-        "Response": str,
-        "StatusCode": int,
-        "Message": str,
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAccessResponseTypeDef = TypedDict(
-    "UpdateAccessResponseTypeDef",
-    {
-        "ServerId": str,
-        "ExternalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAgreementResponseTypeDef = TypedDict(
-    "UpdateAgreementResponseTypeDef",
-    {
-        "AgreementId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCertificateResponseTypeDef = TypedDict(
-    "UpdateCertificateResponseTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorResponseTypeDef = TypedDict(
-    "UpdateConnectorResponseTypeDef",
-    {
-        "ConnectorId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateHostKeyResponseTypeDef = TypedDict(
-    "UpdateHostKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "HostKeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProfileResponseTypeDef = TypedDict(
-    "UpdateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateServerResponseTypeDef = TypedDict(
-    "UpdateServerResponseTypeDef",
-    {
-        "ServerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateUserResponseTypeDef = TypedDict(
-    "UpdateUserResponseTypeDef",
-    {
-        "ServerId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateAgreementRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAgreementRequestRequestTypeDef",
     {
         "ServerId": str,
         "LocalProfileId": str,
         "PartnerProfileId": str,
         "BaseDirectory": str,
@@ -1710,15 +1871,15 @@
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Arn": str,
         "NextToken": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "Arn": str,
@@ -1726,15 +1887,15 @@
     },
 )
 
 DescribeSecurityPolicyResponseTypeDef = TypedDict(
     "DescribeSecurityPolicyResponseTypeDef",
     {
         "SecurityPolicy": DescribedSecurityPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeServerRequestServerOfflineWaitTypeDef = TypedDict(
     "_RequiredDescribeServerRequestServerOfflineWaitTypeDef",
     {
         "ServerId": str,
@@ -1829,254 +1990,95 @@
     {
         "S3FileLocation": S3InputFileLocationTypeDef,
         "EfsFileLocation": EfsFileLocationTypeDef,
     },
     total=False,
 )
 
-_RequiredListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
-    "_RequiredListAccessesRequestListAccessesPaginateTypeDef",
-    {
-        "ServerId": str,
-    },
-)
-_OptionalListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
-    "_OptionalListAccessesRequestListAccessesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccessesRequestListAccessesPaginateTypeDef(
-    _RequiredListAccessesRequestListAccessesPaginateTypeDef,
-    _OptionalListAccessesRequestListAccessesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
-    "_RequiredListAgreementsRequestListAgreementsPaginateTypeDef",
-    {
-        "ServerId": str,
-    },
-)
-_OptionalListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
-    "_OptionalListAgreementsRequestListAgreementsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAgreementsRequestListAgreementsPaginateTypeDef(
-    _RequiredListAgreementsRequestListAgreementsPaginateTypeDef,
-    _OptionalListAgreementsRequestListAgreementsPaginateTypeDef,
-):
-    pass
-
-
-ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListExecutionsRequestListExecutionsPaginateTypeDef",
-    {
-        "WorkflowId": str,
-    },
-)
-_OptionalListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListExecutionsRequestListExecutionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListExecutionsRequestListExecutionsPaginateTypeDef(
-    _RequiredListExecutionsRequestListExecutionsPaginateTypeDef,
-    _OptionalListExecutionsRequestListExecutionsPaginateTypeDef,
-):
-    pass
-
-
-ListProfilesRequestListProfilesPaginateTypeDef = TypedDict(
-    "ListProfilesRequestListProfilesPaginateTypeDef",
-    {
-        "ProfileType": ProfileTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef = TypedDict(
-    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServersRequestListServersPaginateTypeDef = TypedDict(
-    "ListServersRequestListServersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "Arn": str,
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
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "ServerId": str,
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
-
-ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListAccessesResponseTypeDef = TypedDict(
     "ListAccessesResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "Accesses": List[ListedAccessTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAgreementsResponseTypeDef = TypedDict(
     "ListAgreementsResponseTypeDef",
     {
         "NextToken": str,
         "Agreements": List[ListedAgreementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCertificatesResponseTypeDef = TypedDict(
     "ListCertificatesResponseTypeDef",
     {
         "NextToken": str,
         "Certificates": List[ListedCertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectorsResponseTypeDef = TypedDict(
     "ListConnectorsResponseTypeDef",
     {
         "NextToken": str,
         "Connectors": List[ListedConnectorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostKeysResponseTypeDef = TypedDict(
     "ListHostKeysResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "HostKeys": List[ListedHostKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfilesResponseTypeDef = TypedDict(
     "ListProfilesResponseTypeDef",
     {
         "NextToken": str,
         "Profiles": List[ListedProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServersResponseTypeDef = TypedDict(
     "ListServersResponseTypeDef",
     {
         "NextToken": str,
         "Servers": List[ListedServerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "Users": List[ListedUserTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "NextToken": str,
         "Workflows": List[ListedWorkflowTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagStepDetailsTypeDef = TypedDict(
     "TagStepDetailsTypeDef",
     {
         "Name": str,
@@ -2103,64 +2105,64 @@
 )
 
 DescribeAccessResponseTypeDef = TypedDict(
     "DescribeAccessResponseTypeDef",
     {
         "ServerId": str,
         "Access": DescribedAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAgreementResponseTypeDef = TypedDict(
     "DescribeAgreementResponseTypeDef",
     {
         "Agreement": DescribedAgreementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResponseTypeDef = TypedDict(
     "DescribeCertificateResponseTypeDef",
     {
         "Certificate": DescribedCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorResponseTypeDef = TypedDict(
     "DescribeConnectorResponseTypeDef",
     {
         "Connector": DescribedConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHostKeyResponseTypeDef = TypedDict(
     "DescribeHostKeyResponseTypeDef",
     {
         "HostKey": DescribedHostKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProfileResponseTypeDef = TypedDict(
     "DescribeProfileResponseTypeDef",
     {
         "Profile": DescribedProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserResponseTypeDef = TypedDict(
     "DescribeUserResponseTypeDef",
     {
         "ServerId": str,
         "User": DescribedUserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecutionResultsTypeDef = TypedDict(
     "ExecutionResultsTypeDef",
     {
         "Steps": List[ExecutionStepResultTypeDef],
@@ -2229,14 +2231,15 @@
         "PostAuthenticationLoginBanner": str,
         "PreAuthenticationLoginBanner": str,
         "Protocols": Sequence[ProtocolType],
         "ProtocolDetails": ProtocolDetailsTypeDef,
         "SecurityPolicyName": str,
         "Tags": Sequence[TagTypeDef],
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": Sequence[str],
     },
     total=False,
 )
 
 _RequiredDescribedServerTypeDef = TypedDict(
     "_RequiredDescribedServerTypeDef",
     {
@@ -2260,14 +2263,15 @@
         "Protocols": List[ProtocolType],
         "SecurityPolicyName": str,
         "ServerId": str,
         "State": StateType,
         "Tags": List[TagTypeDef],
         "UserCount": int,
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": List[str],
     },
     total=False,
 )
 
 
 class DescribedServerTypeDef(_RequiredDescribedServerTypeDef, _OptionalDescribedServerTypeDef):
     pass
@@ -2290,14 +2294,15 @@
         "IdentityProviderDetails": IdentityProviderDetailsTypeDef,
         "LoggingRole": str,
         "PostAuthenticationLoginBanner": str,
         "PreAuthenticationLoginBanner": str,
         "Protocols": Sequence[ProtocolType],
         "SecurityPolicyName": str,
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": Sequence[str],
     },
     total=False,
 )
 
 
 class UpdateServerRequestRequestTypeDef(
     _RequiredUpdateServerRequestRequestTypeDef, _OptionalUpdateServerRequestRequestTypeDef
@@ -2335,32 +2340,32 @@
 
 ListExecutionsResponseTypeDef = TypedDict(
     "ListExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "WorkflowId": str,
         "Executions": List[ListedExecutionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServerResponseTypeDef = TypedDict(
     "DescribeServerResponseTypeDef",
     {
         "Server": DescribedServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExecutionResponseTypeDef = TypedDict(
     "DescribeExecutionResponseTypeDef",
     {
         "WorkflowId": str,
         "Execution": DescribedExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "Steps": Sequence[WorkflowStepTypeDef],
@@ -2408,10 +2413,10 @@
     pass
 
 
 DescribeWorkflowResponseTypeDef = TypedDict(
     "DescribeWorkflowResponseTypeDef",
     {
         "Workflow": DescribedWorkflowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/type_defs.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -31,14 +31,15 @@
     IdentityProviderTypeType,
     MdnResponseType,
     MdnSigningAlgType,
     OverwriteExistingType,
     ProfileTypeType,
     ProtocolType,
     SetStatOptionType,
+    SftpAuthenticationMethodsType,
     SigningAlgType,
     StateType,
     TlsSessionResumptionModeType,
     WorkflowStepTypeType,
 )
 
 if sys.version_info >= (3, 9):
@@ -50,19 +51,25 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "As2ConnectorConfigTypeDef",
     "HomeDirectoryMapEntryTypeDef",
     "PosixProfileTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessResponseTypeDef",
     "TagTypeDef",
+    "CreateAgreementResponseTypeDef",
+    "CreateConnectorResponseTypeDef",
+    "CreateProfileResponseTypeDef",
     "EndpointDetailsTypeDef",
     "IdentityProviderDetailsTypeDef",
     "ProtocolDetailsTypeDef",
+    "CreateServerResponseTypeDef",
+    "CreateUserResponseTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "CustomStepDetailsTypeDef",
     "DeleteAccessRequestRequestTypeDef",
     "DeleteAgreementRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteConnectorRequestRequestTypeDef",
     "DeleteHostKeyRequestRequestTypeDef",
     "DeleteProfileRequestRequestTypeDef",
@@ -83,80 +90,85 @@
     "DescribeServerRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "DescribeWorkflowRequestRequestTypeDef",
     "LoggingConfigurationTypeDef",
     "SshPublicKeyTypeDef",
     "EfsFileLocationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExecutionErrorTypeDef",
     "S3FileLocationTypeDef",
+    "ImportCertificateResponseTypeDef",
+    "ImportHostKeyResponseTypeDef",
     "ImportSshPublicKeyRequestRequestTypeDef",
+    "ImportSshPublicKeyResponseTypeDef",
     "S3InputFileLocationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessesRequestListAccessesPaginateTypeDef",
     "ListAccessesRequestRequestTypeDef",
     "ListedAccessTypeDef",
+    "ListAgreementsRequestListAgreementsPaginateTypeDef",
     "ListAgreementsRequestRequestTypeDef",
     "ListedAgreementTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
     "ListedCertificateTypeDef",
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     "ListConnectorsRequestRequestTypeDef",
     "ListedConnectorTypeDef",
+    "ListExecutionsRequestListExecutionsPaginateTypeDef",
     "ListExecutionsRequestRequestTypeDef",
     "ListHostKeysRequestRequestTypeDef",
     "ListedHostKeyTypeDef",
+    "ListProfilesRequestListProfilesPaginateTypeDef",
     "ListProfilesRequestRequestTypeDef",
     "ListedProfileTypeDef",
+    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
     "ListSecurityPoliciesRequestRequestTypeDef",
+    "ListSecurityPoliciesResponseTypeDef",
+    "ListServersRequestListServersPaginateTypeDef",
     "ListServersRequestRequestTypeDef",
     "ListedServerTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "ListedUserTypeDef",
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "ListedWorkflowTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3TagTypeDef",
     "SendWorkflowStepStateRequestRequestTypeDef",
     "UserDetailsTypeDef",
     "StartFileTransferRequestRequestTypeDef",
+    "StartFileTransferResponseTypeDef",
     "StartServerRequestRequestTypeDef",
     "StopServerRequestRequestTypeDef",
     "TestIdentityProviderRequestRequestTypeDef",
+    "TestIdentityProviderResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAccessResponseTypeDef",
     "UpdateAgreementRequestRequestTypeDef",
+    "UpdateAgreementResponseTypeDef",
     "UpdateCertificateRequestRequestTypeDef",
+    "UpdateCertificateResponseTypeDef",
+    "UpdateConnectorResponseTypeDef",
     "UpdateHostKeyRequestRequestTypeDef",
+    "UpdateHostKeyResponseTypeDef",
     "UpdateProfileRequestRequestTypeDef",
+    "UpdateProfileResponseTypeDef",
+    "UpdateServerResponseTypeDef",
+    "UpdateUserResponseTypeDef",
     "WorkflowDetailTypeDef",
     "UpdateConnectorRequestRequestTypeDef",
     "CreateAccessRequestRequestTypeDef",
     "DescribedAccessTypeDef",
     "UpdateAccessRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
-    "CreateAccessResponseTypeDef",
-    "CreateAgreementResponseTypeDef",
-    "CreateConnectorResponseTypeDef",
-    "CreateProfileResponseTypeDef",
-    "CreateServerResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ImportCertificateResponseTypeDef",
-    "ImportHostKeyResponseTypeDef",
-    "ImportSshPublicKeyResponseTypeDef",
-    "ListSecurityPoliciesResponseTypeDef",
-    "StartFileTransferResponseTypeDef",
-    "TestIdentityProviderResponseTypeDef",
-    "UpdateAccessResponseTypeDef",
-    "UpdateAgreementResponseTypeDef",
-    "UpdateCertificateResponseTypeDef",
-    "UpdateConnectorResponseTypeDef",
-    "UpdateHostKeyResponseTypeDef",
-    "UpdateProfileResponseTypeDef",
-    "UpdateServerResponseTypeDef",
-    "UpdateUserResponseTypeDef",
     "CreateAgreementRequestRequestTypeDef",
     "CreateConnectorRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DescribedAgreementTypeDef",
     "DescribedCertificateTypeDef",
     "DescribedConnectorTypeDef",
@@ -169,25 +181,14 @@
     "DescribeSecurityPolicyResponseTypeDef",
     "DescribeServerRequestServerOfflineWaitTypeDef",
     "DescribeServerRequestServerOnlineWaitTypeDef",
     "DescribedUserTypeDef",
     "ExecutionStepResultTypeDef",
     "FileLocationTypeDef",
     "InputFileLocationTypeDef",
-    "ListAccessesRequestListAccessesPaginateTypeDef",
-    "ListAgreementsRequestListAgreementsPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    "ListExecutionsRequestListExecutionsPaginateTypeDef",
-    "ListProfilesRequestListProfilesPaginateTypeDef",
-    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
-    "ListServersRequestListServersPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListAccessesResponseTypeDef",
     "ListAgreementsResponseTypeDef",
     "ListCertificatesResponseTypeDef",
     "ListConnectorsResponseTypeDef",
     "ListHostKeysResponseTypeDef",
     "ListProfilesResponseTypeDef",
     "ListServersResponseTypeDef",
@@ -257,33 +258,55 @@
     },
     total=False,
 )
 
 class PosixProfileTypeDef(_RequiredPosixProfileTypeDef, _OptionalPosixProfileTypeDef):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAccessResponseTypeDef = TypedDict(
+    "CreateAccessResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServerId": str,
+        "ExternalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAgreementResponseTypeDef = TypedDict(
+    "CreateAgreementResponseTypeDef",
+    {
+        "AgreementId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateConnectorResponseTypeDef = TypedDict(
+    "CreateConnectorResponseTypeDef",
+    {
+        "ConnectorId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileResponseTypeDef = TypedDict(
+    "CreateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EndpointDetailsTypeDef = TypedDict(
     "EndpointDetailsTypeDef",
     {
         "AddressAllocationIds": Sequence[str],
         "SubnetIds": Sequence[str],
         "VpcEndpointId": str,
         "VpcId": str,
@@ -295,14 +318,15 @@
 IdentityProviderDetailsTypeDef = TypedDict(
     "IdentityProviderDetailsTypeDef",
     {
         "Url": str,
         "InvocationRole": str,
         "DirectoryId": str,
         "Function": str,
+        "SftpAuthenticationMethods": SftpAuthenticationMethodsType,
     },
     total=False,
 )
 
 ProtocolDetailsTypeDef = TypedDict(
     "ProtocolDetailsTypeDef",
     {
@@ -310,14 +334,39 @@
         "TlsSessionResumptionMode": TlsSessionResumptionModeType,
         "SetStatOption": SetStatOptionType,
         "As2Transports": Sequence[Literal["HTTP"]],
     },
     total=False,
 )
 
+CreateServerResponseTypeDef = TypedDict(
+    "CreateServerResponseTypeDef",
+    {
+        "ServerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "ServerId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "WorkflowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomStepDetailsTypeDef = TypedDict(
     "CustomStepDetailsTypeDef",
     {
         "Name": str,
         "Target": str,
         "TimeoutSeconds": int,
         "SourceFileLocation": str,
@@ -547,14 +596,21 @@
     {
         "FileSystemId": str,
         "Path": str,
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
 ExecutionErrorTypeDef = TypedDict(
     "ExecutionErrorTypeDef",
     {
         "Type": ExecutionErrorTypeType,
         "Message": str,
     },
 )
@@ -566,42 +622,79 @@
         "Key": str,
         "VersionId": str,
         "Etag": str,
     },
     total=False,
 )
 
+ImportCertificateResponseTypeDef = TypedDict(
+    "ImportCertificateResponseTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportHostKeyResponseTypeDef = TypedDict(
+    "ImportHostKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "HostKeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImportSshPublicKeyRequestRequestTypeDef = TypedDict(
     "ImportSshPublicKeyRequestRequestTypeDef",
     {
         "ServerId": str,
         "SshPublicKeyBody": str,
         "UserName": str,
     },
 )
 
+ImportSshPublicKeyResponseTypeDef = TypedDict(
+    "ImportSshPublicKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "SshPublicKeyId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3InputFileLocationTypeDef = TypedDict(
     "S3InputFileLocationTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
+    "_RequiredListAccessesRequestListAccessesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServerId": str,
+    },
+)
+_OptionalListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
+    "_OptionalListAccessesRequestListAccessesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAccessesRequestListAccessesPaginateTypeDef(
+    _RequiredListAccessesRequestListAccessesPaginateTypeDef,
+    _OptionalListAccessesRequestListAccessesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccessesRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessesRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 _OptionalListAccessesRequestRequestTypeDef = TypedDict(
@@ -625,14 +718,34 @@
         "HomeDirectoryType": HomeDirectoryTypeType,
         "Role": str,
         "ExternalId": str,
     },
     total=False,
 )
 
+_RequiredListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
+    "_RequiredListAgreementsRequestListAgreementsPaginateTypeDef",
+    {
+        "ServerId": str,
+    },
+)
+_OptionalListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
+    "_OptionalListAgreementsRequestListAgreementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAgreementsRequestListAgreementsPaginateTypeDef(
+    _RequiredListAgreementsRequestListAgreementsPaginateTypeDef,
+    _OptionalListAgreementsRequestListAgreementsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAgreementsRequestRequestTypeDef = TypedDict(
     "_RequiredListAgreementsRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 _OptionalListAgreementsRequestRequestTypeDef = TypedDict(
@@ -659,14 +772,22 @@
         "ServerId": str,
         "LocalProfileId": str,
         "PartnerProfileId": str,
     },
     total=False,
 )
 
+ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCertificatesRequestRequestTypeDef = TypedDict(
     "ListCertificatesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -683,14 +804,22 @@
         "InactiveDate": datetime,
         "Type": CertificateTypeType,
         "Description": str,
     },
     total=False,
 )
 
+ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConnectorsRequestRequestTypeDef = TypedDict(
     "ListConnectorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -702,14 +831,34 @@
         "Arn": str,
         "ConnectorId": str,
         "Url": str,
     },
     total=False,
 )
 
+_RequiredListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListExecutionsRequestListExecutionsPaginateTypeDef",
+    {
+        "WorkflowId": str,
+    },
+)
+_OptionalListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListExecutionsRequestListExecutionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListExecutionsRequestListExecutionsPaginateTypeDef(
+    _RequiredListExecutionsRequestListExecutionsPaginateTypeDef,
+    _OptionalListExecutionsRequestListExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExecutionsRequestRequestTypeDef",
     {
         "WorkflowId": str,
     },
 )
 _OptionalListExecutionsRequestRequestTypeDef = TypedDict(
@@ -763,14 +912,23 @@
     },
     total=False,
 )
 
 class ListedHostKeyTypeDef(_RequiredListedHostKeyTypeDef, _OptionalListedHostKeyTypeDef):
     pass
 
+ListProfilesRequestListProfilesPaginateTypeDef = TypedDict(
+    "ListProfilesRequestListProfilesPaginateTypeDef",
+    {
+        "ProfileType": ProfileTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProfilesRequestRequestTypeDef = TypedDict(
     "ListProfilesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ProfileType": ProfileTypeType,
     },
@@ -784,23 +942,48 @@
         "ProfileId": str,
         "As2Id": str,
         "ProfileType": ProfileTypeType,
     },
     total=False,
 )
 
+ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef = TypedDict(
+    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecurityPoliciesRequestRequestTypeDef = TypedDict(
     "ListSecurityPoliciesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListSecurityPoliciesResponseTypeDef = TypedDict(
+    "ListSecurityPoliciesResponseTypeDef",
+    {
+        "NextToken": str,
+        "SecurityPolicyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListServersRequestListServersPaginateTypeDef = TypedDict(
+    "ListServersRequestListServersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServersRequestRequestTypeDef = TypedDict(
     "ListServersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -825,14 +1008,34 @@
     },
     total=False,
 )
 
 class ListedServerTypeDef(_RequiredListedServerTypeDef, _OptionalListedServerTypeDef):
     pass
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "Arn": str,
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
         "Arn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -846,14 +1049,34 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "ServerId": str,
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
         "ServerId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -887,14 +1110,22 @@
     },
     total=False,
 )
 
 class ListedUserTypeDef(_RequiredListedUserTypeDef, _OptionalListedUserTypeDef):
     pass
 
+ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -906,14 +1137,35 @@
         "WorkflowId": str,
         "Description": str,
         "Arn": str,
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
 S3TagTypeDef = TypedDict(
     "S3TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -950,14 +1202,22 @@
     "StartFileTransferRequestRequestTypeDef",
     {
         "ConnectorId": str,
         "SendFilePaths": Sequence[str],
     },
 )
 
+StartFileTransferResponseTypeDef = TypedDict(
+    "StartFileTransferResponseTypeDef",
+    {
+        "TransferId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartServerRequestRequestTypeDef = TypedDict(
     "StartServerRequestRequestTypeDef",
     {
         "ServerId": str,
     },
 )
 
@@ -987,22 +1247,42 @@
 
 class TestIdentityProviderRequestRequestTypeDef(
     _RequiredTestIdentityProviderRequestRequestTypeDef,
     _OptionalTestIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
+TestIdentityProviderResponseTypeDef = TypedDict(
+    "TestIdentityProviderResponseTypeDef",
+    {
+        "Response": str,
+        "StatusCode": int,
+        "Message": str,
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAccessResponseTypeDef = TypedDict(
+    "UpdateAccessResponseTypeDef",
+    {
+        "ServerId": str,
+        "ExternalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAgreementRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAgreementRequestRequestTypeDef",
     {
         "AgreementId": str,
         "ServerId": str,
     },
 )
@@ -1020,14 +1300,22 @@
 )
 
 class UpdateAgreementRequestRequestTypeDef(
     _RequiredUpdateAgreementRequestRequestTypeDef, _OptionalUpdateAgreementRequestRequestTypeDef
 ):
     pass
 
+UpdateAgreementResponseTypeDef = TypedDict(
+    "UpdateAgreementResponseTypeDef",
+    {
+        "AgreementId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCertificateRequestRequestTypeDef",
     {
         "CertificateId": str,
     },
 )
 _OptionalUpdateCertificateRequestRequestTypeDef = TypedDict(
@@ -1041,23 +1329,48 @@
 )
 
 class UpdateCertificateRequestRequestTypeDef(
     _RequiredUpdateCertificateRequestRequestTypeDef, _OptionalUpdateCertificateRequestRequestTypeDef
 ):
     pass
 
+UpdateCertificateResponseTypeDef = TypedDict(
+    "UpdateCertificateResponseTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateConnectorResponseTypeDef = TypedDict(
+    "UpdateConnectorResponseTypeDef",
+    {
+        "ConnectorId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateHostKeyRequestRequestTypeDef = TypedDict(
     "UpdateHostKeyRequestRequestTypeDef",
     {
         "ServerId": str,
         "HostKeyId": str,
         "Description": str,
     },
 )
 
+UpdateHostKeyResponseTypeDef = TypedDict(
+    "UpdateHostKeyResponseTypeDef",
+    {
+        "ServerId": str,
+        "HostKeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProfileRequestRequestTypeDef",
     {
         "ProfileId": str,
     },
 )
 _OptionalUpdateProfileRequestRequestTypeDef = TypedDict(
@@ -1069,14 +1382,39 @@
 )
 
 class UpdateProfileRequestRequestTypeDef(
     _RequiredUpdateProfileRequestRequestTypeDef, _OptionalUpdateProfileRequestRequestTypeDef
 ):
     pass
 
+UpdateProfileResponseTypeDef = TypedDict(
+    "UpdateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateServerResponseTypeDef = TypedDict(
+    "UpdateServerResponseTypeDef",
+    {
+        "ServerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateUserResponseTypeDef = TypedDict(
+    "UpdateUserResponseTypeDef",
+    {
+        "ServerId": str,
+        "UserName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowDetailTypeDef = TypedDict(
     "WorkflowDetailTypeDef",
     {
         "WorkflowId": str,
         "ExecutionRole": str,
     },
 )
@@ -1188,201 +1526,14 @@
 )
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
 ):
     pass
 
-CreateAccessResponseTypeDef = TypedDict(
-    "CreateAccessResponseTypeDef",
-    {
-        "ServerId": str,
-        "ExternalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAgreementResponseTypeDef = TypedDict(
-    "CreateAgreementResponseTypeDef",
-    {
-        "AgreementId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConnectorResponseTypeDef = TypedDict(
-    "CreateConnectorResponseTypeDef",
-    {
-        "ConnectorId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProfileResponseTypeDef = TypedDict(
-    "CreateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateServerResponseTypeDef = TypedDict(
-    "CreateServerResponseTypeDef",
-    {
-        "ServerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "ServerId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
-    {
-        "WorkflowId": str,
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
-ImportCertificateResponseTypeDef = TypedDict(
-    "ImportCertificateResponseTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportHostKeyResponseTypeDef = TypedDict(
-    "ImportHostKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "HostKeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSshPublicKeyResponseTypeDef = TypedDict(
-    "ImportSshPublicKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "SshPublicKeyId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSecurityPoliciesResponseTypeDef = TypedDict(
-    "ListSecurityPoliciesResponseTypeDef",
-    {
-        "NextToken": str,
-        "SecurityPolicyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFileTransferResponseTypeDef = TypedDict(
-    "StartFileTransferResponseTypeDef",
-    {
-        "TransferId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestIdentityProviderResponseTypeDef = TypedDict(
-    "TestIdentityProviderResponseTypeDef",
-    {
-        "Response": str,
-        "StatusCode": int,
-        "Message": str,
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAccessResponseTypeDef = TypedDict(
-    "UpdateAccessResponseTypeDef",
-    {
-        "ServerId": str,
-        "ExternalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAgreementResponseTypeDef = TypedDict(
-    "UpdateAgreementResponseTypeDef",
-    {
-        "AgreementId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCertificateResponseTypeDef = TypedDict(
-    "UpdateCertificateResponseTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorResponseTypeDef = TypedDict(
-    "UpdateConnectorResponseTypeDef",
-    {
-        "ConnectorId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateHostKeyResponseTypeDef = TypedDict(
-    "UpdateHostKeyResponseTypeDef",
-    {
-        "ServerId": str,
-        "HostKeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProfileResponseTypeDef = TypedDict(
-    "UpdateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateServerResponseTypeDef = TypedDict(
-    "UpdateServerResponseTypeDef",
-    {
-        "ServerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateUserResponseTypeDef = TypedDict(
-    "UpdateUserResponseTypeDef",
-    {
-        "ServerId": str,
-        "UserName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateAgreementRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAgreementRequestRequestTypeDef",
     {
         "ServerId": str,
         "LocalProfileId": str,
         "PartnerProfileId": str,
         "BaseDirectory": str,
@@ -1647,15 +1798,15 @@
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Arn": str,
         "NextToken": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "Arn": str,
@@ -1663,15 +1814,15 @@
     },
 )
 
 DescribeSecurityPolicyResponseTypeDef = TypedDict(
     "DescribeSecurityPolicyResponseTypeDef",
     {
         "SecurityPolicy": DescribedSecurityPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeServerRequestServerOfflineWaitTypeDef = TypedDict(
     "_RequiredDescribeServerRequestServerOfflineWaitTypeDef",
     {
         "ServerId": str,
@@ -1760,244 +1911,95 @@
     {
         "S3FileLocation": S3InputFileLocationTypeDef,
         "EfsFileLocation": EfsFileLocationTypeDef,
     },
     total=False,
 )
 
-_RequiredListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
-    "_RequiredListAccessesRequestListAccessesPaginateTypeDef",
-    {
-        "ServerId": str,
-    },
-)
-_OptionalListAccessesRequestListAccessesPaginateTypeDef = TypedDict(
-    "_OptionalListAccessesRequestListAccessesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccessesRequestListAccessesPaginateTypeDef(
-    _RequiredListAccessesRequestListAccessesPaginateTypeDef,
-    _OptionalListAccessesRequestListAccessesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
-    "_RequiredListAgreementsRequestListAgreementsPaginateTypeDef",
-    {
-        "ServerId": str,
-    },
-)
-_OptionalListAgreementsRequestListAgreementsPaginateTypeDef = TypedDict(
-    "_OptionalListAgreementsRequestListAgreementsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAgreementsRequestListAgreementsPaginateTypeDef(
-    _RequiredListAgreementsRequestListAgreementsPaginateTypeDef,
-    _OptionalListAgreementsRequestListAgreementsPaginateTypeDef,
-):
-    pass
-
-ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListExecutionsRequestListExecutionsPaginateTypeDef",
-    {
-        "WorkflowId": str,
-    },
-)
-_OptionalListExecutionsRequestListExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListExecutionsRequestListExecutionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListExecutionsRequestListExecutionsPaginateTypeDef(
-    _RequiredListExecutionsRequestListExecutionsPaginateTypeDef,
-    _OptionalListExecutionsRequestListExecutionsPaginateTypeDef,
-):
-    pass
-
-ListProfilesRequestListProfilesPaginateTypeDef = TypedDict(
-    "ListProfilesRequestListProfilesPaginateTypeDef",
-    {
-        "ProfileType": ProfileTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef = TypedDict(
-    "ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServersRequestListServersPaginateTypeDef = TypedDict(
-    "ListServersRequestListServersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "Arn": str,
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
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "ServerId": str,
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
-
-ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListAccessesResponseTypeDef = TypedDict(
     "ListAccessesResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "Accesses": List[ListedAccessTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAgreementsResponseTypeDef = TypedDict(
     "ListAgreementsResponseTypeDef",
     {
         "NextToken": str,
         "Agreements": List[ListedAgreementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCertificatesResponseTypeDef = TypedDict(
     "ListCertificatesResponseTypeDef",
     {
         "NextToken": str,
         "Certificates": List[ListedCertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectorsResponseTypeDef = TypedDict(
     "ListConnectorsResponseTypeDef",
     {
         "NextToken": str,
         "Connectors": List[ListedConnectorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostKeysResponseTypeDef = TypedDict(
     "ListHostKeysResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "HostKeys": List[ListedHostKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfilesResponseTypeDef = TypedDict(
     "ListProfilesResponseTypeDef",
     {
         "NextToken": str,
         "Profiles": List[ListedProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServersResponseTypeDef = TypedDict(
     "ListServersResponseTypeDef",
     {
         "NextToken": str,
         "Servers": List[ListedServerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "NextToken": str,
         "ServerId": str,
         "Users": List[ListedUserTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "NextToken": str,
         "Workflows": List[ListedWorkflowTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagStepDetailsTypeDef = TypedDict(
     "TagStepDetailsTypeDef",
     {
         "Name": str,
@@ -2024,64 +2026,64 @@
 )
 
 DescribeAccessResponseTypeDef = TypedDict(
     "DescribeAccessResponseTypeDef",
     {
         "ServerId": str,
         "Access": DescribedAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAgreementResponseTypeDef = TypedDict(
     "DescribeAgreementResponseTypeDef",
     {
         "Agreement": DescribedAgreementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResponseTypeDef = TypedDict(
     "DescribeCertificateResponseTypeDef",
     {
         "Certificate": DescribedCertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorResponseTypeDef = TypedDict(
     "DescribeConnectorResponseTypeDef",
     {
         "Connector": DescribedConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHostKeyResponseTypeDef = TypedDict(
     "DescribeHostKeyResponseTypeDef",
     {
         "HostKey": DescribedHostKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProfileResponseTypeDef = TypedDict(
     "DescribeProfileResponseTypeDef",
     {
         "Profile": DescribedProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserResponseTypeDef = TypedDict(
     "DescribeUserResponseTypeDef",
     {
         "ServerId": str,
         "User": DescribedUserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecutionResultsTypeDef = TypedDict(
     "ExecutionResultsTypeDef",
     {
         "Steps": List[ExecutionStepResultTypeDef],
@@ -2148,14 +2150,15 @@
         "PostAuthenticationLoginBanner": str,
         "PreAuthenticationLoginBanner": str,
         "Protocols": Sequence[ProtocolType],
         "ProtocolDetails": ProtocolDetailsTypeDef,
         "SecurityPolicyName": str,
         "Tags": Sequence[TagTypeDef],
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": Sequence[str],
     },
     total=False,
 )
 
 _RequiredDescribedServerTypeDef = TypedDict(
     "_RequiredDescribedServerTypeDef",
     {
@@ -2179,14 +2182,15 @@
         "Protocols": List[ProtocolType],
         "SecurityPolicyName": str,
         "ServerId": str,
         "State": StateType,
         "Tags": List[TagTypeDef],
         "UserCount": int,
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": List[str],
     },
     total=False,
 )
 
 class DescribedServerTypeDef(_RequiredDescribedServerTypeDef, _OptionalDescribedServerTypeDef):
     pass
 
@@ -2207,14 +2211,15 @@
         "IdentityProviderDetails": IdentityProviderDetailsTypeDef,
         "LoggingRole": str,
         "PostAuthenticationLoginBanner": str,
         "PreAuthenticationLoginBanner": str,
         "Protocols": Sequence[ProtocolType],
         "SecurityPolicyName": str,
         "WorkflowDetails": WorkflowDetailsTypeDef,
+        "StructuredLogDestinations": Sequence[str],
     },
     total=False,
 )
 
 class UpdateServerRequestRequestTypeDef(
     _RequiredUpdateServerRequestRequestTypeDef, _OptionalUpdateServerRequestRequestTypeDef
 ):
@@ -2250,32 +2255,32 @@
 
 ListExecutionsResponseTypeDef = TypedDict(
     "ListExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "WorkflowId": str,
         "Executions": List[ListedExecutionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServerResponseTypeDef = TypedDict(
     "DescribeServerResponseTypeDef",
     {
         "Server": DescribedServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExecutionResponseTypeDef = TypedDict(
     "DescribeExecutionResponseTypeDef",
     {
         "WorkflowId": str,
         "Execution": DescribedExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "Steps": Sequence[WorkflowStepTypeDef],
@@ -2319,10 +2324,10 @@
 ):
     pass
 
 DescribeWorkflowResponseTypeDef = TypedDict(
     "DescribeWorkflowResponseTypeDef",
     {
         "Workflow": DescribedWorkflowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/waiter.py` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer/waiter.pyi` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/PKG-INFO` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-transfer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Transfer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Transfer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-transfer"></a>
 
 # types-aiobotocore-transfer
 
 [![PyPI - types-aiobotocore-transfer](https://img.shields.io/pypi/v/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transfer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transfer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transfer?color=blue)](https://pypistats.org/packages/types-aiobotocore-transfer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Transfer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
+[aiobotocore.Transfer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
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
 [types-aiobotocore-transfer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -377,14 +377,15 @@
     MdnSigningAlgType,
     OverwriteExistingType,
     ProfileTypeType,
     ProtocolType,
     ServerOfflineWaiterName,
     ServerOnlineWaiterName,
     SetStatOptionType,
+    SftpAuthenticationMethodsType,
     SigningAlgType,
     StateType,
     TlsSessionResumptionModeType,
     WorkflowStepTypeType,
     TransferServiceName,
     ServiceName,
     ResourceServiceName,
@@ -406,19 +407,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_transfer.type_defs import (
     As2ConnectorConfigTypeDef,
     HomeDirectoryMapEntryTypeDef,
     PosixProfileTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessResponseTypeDef,
     TagTypeDef,
+    CreateAgreementResponseTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateProfileResponseTypeDef,
     EndpointDetailsTypeDef,
     IdentityProviderDetailsTypeDef,
     ProtocolDetailsTypeDef,
+    CreateServerResponseTypeDef,
+    CreateUserResponseTypeDef,
+    CreateWorkflowResponseTypeDef,
     CustomStepDetailsTypeDef,
     DeleteAccessRequestRequestTypeDef,
     DeleteAgreementRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteConnectorRequestRequestTypeDef,
     DeleteHostKeyRequestRequestTypeDef,
     DeleteProfileRequestRequestTypeDef,
@@ -439,80 +446,85 @@
     DescribeServerRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeUserRequestRequestTypeDef,
     DescribeWorkflowRequestRequestTypeDef,
     LoggingConfigurationTypeDef,
     SshPublicKeyTypeDef,
     EfsFileLocationTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionErrorTypeDef,
     S3FileLocationTypeDef,
+    ImportCertificateResponseTypeDef,
+    ImportHostKeyResponseTypeDef,
     ImportSshPublicKeyRequestRequestTypeDef,
+    ImportSshPublicKeyResponseTypeDef,
     S3InputFileLocationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessesRequestListAccessesPaginateTypeDef,
     ListAccessesRequestRequestTypeDef,
     ListedAccessTypeDef,
+    ListAgreementsRequestListAgreementsPaginateTypeDef,
     ListAgreementsRequestRequestTypeDef,
     ListedAgreementTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
     ListedCertificateTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListedConnectorTypeDef,
+    ListExecutionsRequestListExecutionsPaginateTypeDef,
     ListExecutionsRequestRequestTypeDef,
     ListHostKeysRequestRequestTypeDef,
     ListedHostKeyTypeDef,
+    ListProfilesRequestListProfilesPaginateTypeDef,
     ListProfilesRequestRequestTypeDef,
     ListedProfileTypeDef,
+    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
+    ListSecurityPoliciesResponseTypeDef,
+    ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     ListedServerTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListedUserTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     ListedWorkflowTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3TagTypeDef,
     SendWorkflowStepStateRequestRequestTypeDef,
     UserDetailsTypeDef,
     StartFileTransferRequestRequestTypeDef,
+    StartFileTransferResponseTypeDef,
     StartServerRequestRequestTypeDef,
     StopServerRequestRequestTypeDef,
     TestIdentityProviderRequestRequestTypeDef,
+    TestIdentityProviderResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAccessResponseTypeDef,
     UpdateAgreementRequestRequestTypeDef,
+    UpdateAgreementResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
+    UpdateCertificateResponseTypeDef,
+    UpdateConnectorResponseTypeDef,
     UpdateHostKeyRequestRequestTypeDef,
+    UpdateHostKeyResponseTypeDef,
     UpdateProfileRequestRequestTypeDef,
+    UpdateProfileResponseTypeDef,
+    UpdateServerResponseTypeDef,
+    UpdateUserResponseTypeDef,
     WorkflowDetailTypeDef,
     UpdateConnectorRequestRequestTypeDef,
     CreateAccessRequestRequestTypeDef,
     DescribedAccessTypeDef,
     UpdateAccessRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
-    CreateAccessResponseTypeDef,
-    CreateAgreementResponseTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    CreateServerResponseTypeDef,
-    CreateUserResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ImportCertificateResponseTypeDef,
-    ImportHostKeyResponseTypeDef,
-    ImportSshPublicKeyResponseTypeDef,
-    ListSecurityPoliciesResponseTypeDef,
-    StartFileTransferResponseTypeDef,
-    TestIdentityProviderResponseTypeDef,
-    UpdateAccessResponseTypeDef,
-    UpdateAgreementResponseTypeDef,
-    UpdateCertificateResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
-    UpdateHostKeyResponseTypeDef,
-    UpdateProfileResponseTypeDef,
-    UpdateServerResponseTypeDef,
-    UpdateUserResponseTypeDef,
     CreateAgreementRequestRequestTypeDef,
     CreateConnectorRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribedAgreementTypeDef,
     DescribedCertificateTypeDef,
     DescribedConnectorTypeDef,
@@ -525,25 +537,14 @@
     DescribeSecurityPolicyResponseTypeDef,
     DescribeServerRequestServerOfflineWaitTypeDef,
     DescribeServerRequestServerOnlineWaitTypeDef,
     DescribedUserTypeDef,
     ExecutionStepResultTypeDef,
     FileLocationTypeDef,
     InputFileLocationTypeDef,
-    ListAccessesRequestListAccessesPaginateTypeDef,
-    ListAgreementsRequestListAgreementsPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListExecutionsRequestListExecutionsPaginateTypeDef,
-    ListProfilesRequestListProfilesPaginateTypeDef,
-    ListSecurityPoliciesRequestListSecurityPoliciesPaginateTypeDef,
-    ListServersRequestListServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListAccessesResponseTypeDef,
     ListAgreementsResponseTypeDef,
     ListCertificatesResponseTypeDef,
     ListConnectorsResponseTypeDef,
     ListHostKeysResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListServersResponseTypeDef,
@@ -584,43 +585,43 @@
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

### Comparing `types-aiobotocore-transfer-2.5.0.post1/types_aiobotocore_transfer.egg-info/SOURCES.txt` & `types-aiobotocore-transfer-2.5.1/types_aiobotocore_transfer.egg-info/SOURCES.txt`

 * *Files identical despite different names*

