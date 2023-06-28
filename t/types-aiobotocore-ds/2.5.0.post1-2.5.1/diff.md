# Comparing `tmp/types-aiobotocore-ds-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ds-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ds-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:32 2023, max compression
+gzip compressed data, was "types-aiobotocore-ds-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-ds-2.5.0.post1.tar` & `types-aiobotocore-ds-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.039147 types-aiobotocore-ds-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22535 2023-03-11 12:26:32.035147 types-aiobotocore-ds-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20970 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:32.039147 types-aiobotocore-ds-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.027147 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/
--rw-r--r--   0 runner    (1001) docker     (123)     3709 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3708 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      940 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    54552 2023-03-11 12:12:45.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    54462 2023-03-11 12:12:45.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13380 2023-03-11 12:12:46.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13378 2023-03-11 12:12:46.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17855 2023-03-11 12:12:46.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    17838 2023-03-11 12:12:46.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    57622 2023-03-11 12:12:47.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    57549 2023-03-11 12:12:46.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:44.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.035147 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22535 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      718 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:26:31.000000 types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.678127 types-aiobotocore-ds-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22522 2023-06-28 01:43:24.678127 types-aiobotocore-ds-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20963 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.678127 types-aiobotocore-ds-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.674127 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/
+-rw-r--r--   0 runner    (1001) docker     (123)     3709 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3708 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      928 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54551 2023-06-28 01:29:25.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54461 2023-06-28 01:29:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13611 2023-06-28 01:29:25.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13609 2023-06-28 01:29:25.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17776 2023-06-28 01:29:25.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17759 2023-06-28 01:29:25.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    57753 2023-06-28 01:29:26.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57680 2023-06-28 01:29:26.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:23.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.678127 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22522 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:43:24.000000 types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/LICENSE` & `types-aiobotocore-ds-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ds-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ds-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ds
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DirectoryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DirectoryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ds"></a>
 
 # types-aiobotocore-ds
 
 [![PyPI - types-aiobotocore-ds](https://img.shields.io/pypi/v/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ds?color=blue)](https://pypistats.org/packages/types-aiobotocore-ds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectoryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
+[aiobotocore.DirectoryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
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
 [types-aiobotocore-ds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -408,57 +408,73 @@
 
 `types_aiobotocore_ds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ds.type_defs import (
     AcceptSharedDirectoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     SharedDirectoryTypeDef,
     IpRouteTypeDef,
     DirectoryVpcSettingsTypeDef,
     TagTypeDef,
     AttributeTypeDef,
     CancelSchemaExtensionRequestRequestTypeDef,
     CertificateInfoTypeDef,
     ClientCertAuthSettingsTypeDef,
     ClientAuthenticationSettingInfoTypeDef,
     ConditionalForwarderTypeDef,
     DirectoryConnectSettingsTypeDef,
+    ConnectDirectoryResultTypeDef,
     CreateAliasRequestRequestTypeDef,
+    CreateAliasResultTypeDef,
     CreateConditionalForwarderRequestRequestTypeDef,
+    CreateDirectoryResultTypeDef,
     CreateLogSubscriptionRequestRequestTypeDef,
+    CreateMicrosoftADResultTypeDef,
     CreateSnapshotRequestRequestTypeDef,
+    CreateSnapshotResultTypeDef,
     CreateTrustRequestRequestTypeDef,
+    CreateTrustResultTypeDef,
     DeleteConditionalForwarderRequestRequestTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResultTypeDef,
     DeleteLogSubscriptionRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResultTypeDef,
     DeleteTrustRequestRequestTypeDef,
+    DeleteTrustResultTypeDef,
     DeregisterCertificateRequestRequestTypeDef,
     DeregisterEventTopicRequestRequestTypeDef,
     DescribeCertificateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
     DescribeClientAuthenticationSettingsRequestRequestTypeDef,
     DescribeConditionalForwardersRequestRequestTypeDef,
+    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
     DescribeDirectoriesRequestRequestTypeDef,
+    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
     DescribeDomainControllersRequestRequestTypeDef,
     DomainControllerTypeDef,
     DescribeEventTopicsRequestRequestTypeDef,
     EventTopicTypeDef,
+    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
     DescribeLDAPSSettingsRequestRequestTypeDef,
     LDAPSSettingInfoTypeDef,
+    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
     DescribeRegionsRequestRequestTypeDef,
     DescribeSettingsRequestRequestTypeDef,
     SettingEntryTypeDef,
+    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
     DescribeSharedDirectoriesRequestRequestTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     SnapshotTypeDef,
+    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
     DescribeTrustsRequestRequestTypeDef,
     TrustTypeDef,
+    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
     DescribeUpdateDirectoryRequestRequestTypeDef,
     DirectoryConnectSettingsDescriptionTypeDef,
     DirectoryVpcSettingsDescriptionTypeDef,
     RadiusSettingsTypeDef,
     RegionsInfoTypeDef,
     DirectoryLimitsTypeDef,
     DisableClientAuthenticationRequestRequestTypeDef,
@@ -467,53 +483,51 @@
     DisableSsoRequestRequestTypeDef,
     EnableClientAuthenticationRequestRequestTypeDef,
     EnableLDAPSRequestRequestTypeDef,
     EnableSsoRequestRequestTypeDef,
     GetSnapshotLimitsRequestRequestTypeDef,
     SnapshotLimitsTypeDef,
     IpRouteInfoTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
     ListIpRoutesRequestRequestTypeDef,
+    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
     ListLogSubscriptionsRequestRequestTypeDef,
     LogSubscriptionTypeDef,
+    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
     ListSchemaExtensionsRequestRequestTypeDef,
     SchemaExtensionInfoTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OSUpdateSettingsTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterCertificateResultTypeDef,
     RegisterEventTopicRequestRequestTypeDef,
     RejectSharedDirectoryRequestRequestTypeDef,
+    RejectSharedDirectoryResultTypeDef,
     RemoveIpRoutesRequestRequestTypeDef,
     RemoveRegionRequestRequestTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     SettingTypeDef,
     ShareTargetTypeDef,
+    ShareDirectoryResultTypeDef,
     StartSchemaExtensionRequestRequestTypeDef,
+    StartSchemaExtensionResultTypeDef,
     UnshareTargetTypeDef,
+    UnshareDirectoryResultTypeDef,
     UpdateConditionalForwarderRequestRequestTypeDef,
     UpdateNumberOfDomainControllersRequestRequestTypeDef,
-    UpdateTrustRequestRequestTypeDef,
-    VerifyTrustRequestRequestTypeDef,
-    ConnectDirectoryResultTypeDef,
-    CreateAliasResultTypeDef,
-    CreateDirectoryResultTypeDef,
-    CreateMicrosoftADResultTypeDef,
-    CreateSnapshotResultTypeDef,
-    CreateTrustResultTypeDef,
-    DeleteDirectoryResultTypeDef,
-    DeleteSnapshotResultTypeDef,
-    DeleteTrustResultTypeDef,
-    RegisterCertificateResultTypeDef,
-    RejectSharedDirectoryResultTypeDef,
-    ShareDirectoryResultTypeDef,
-    StartSchemaExtensionResultTypeDef,
-    UnshareDirectoryResultTypeDef,
     UpdateSettingsResultTypeDef,
+    UpdateTrustRequestRequestTypeDef,
     UpdateTrustResultTypeDef,
+    VerifyTrustRequestRequestTypeDef,
     VerifyTrustResultTypeDef,
     AcceptSharedDirectoryResultTypeDef,
     DescribeSharedDirectoriesResultTypeDef,
     AddIpRoutesRequestRequestTypeDef,
     AddRegionRequestRequestTypeDef,
     RegionDescriptionTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
@@ -524,28 +538,14 @@
     CreateComputerRequestRequestTypeDef,
     ListCertificatesResultTypeDef,
     CertificateTypeDef,
     RegisterCertificateRequestRequestTypeDef,
     DescribeClientAuthenticationSettingsResultTypeDef,
     DescribeConditionalForwardersResultTypeDef,
     ConnectDirectoryRequestRequestTypeDef,
-    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
-    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
-    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
-    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
-    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeDomainControllersResultTypeDef,
     DescribeEventTopicsResultTypeDef,
     DescribeLDAPSSettingsResultTypeDef,
     DescribeSettingsResultTypeDef,
     DescribeSnapshotsResultTypeDef,
     DescribeTrustsResultTypeDef,
     EnableRadiusRequestRequestTypeDef,
@@ -578,43 +578,43 @@
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

### Comparing `types-aiobotocore-ds-2.5.0.post1/README.md` & `types-aiobotocore-ds-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ds"></a>
 
 # types-aiobotocore-ds
 
 [![PyPI - types-aiobotocore-ds](https://img.shields.io/pypi/v/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ds?color=blue)](https://pypistats.org/packages/types-aiobotocore-ds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectoryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
+[aiobotocore.DirectoryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
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
 [types-aiobotocore-ds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -375,57 +375,73 @@
 
 `types_aiobotocore_ds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ds.type_defs import (
     AcceptSharedDirectoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     SharedDirectoryTypeDef,
     IpRouteTypeDef,
     DirectoryVpcSettingsTypeDef,
     TagTypeDef,
     AttributeTypeDef,
     CancelSchemaExtensionRequestRequestTypeDef,
     CertificateInfoTypeDef,
     ClientCertAuthSettingsTypeDef,
     ClientAuthenticationSettingInfoTypeDef,
     ConditionalForwarderTypeDef,
     DirectoryConnectSettingsTypeDef,
+    ConnectDirectoryResultTypeDef,
     CreateAliasRequestRequestTypeDef,
+    CreateAliasResultTypeDef,
     CreateConditionalForwarderRequestRequestTypeDef,
+    CreateDirectoryResultTypeDef,
     CreateLogSubscriptionRequestRequestTypeDef,
+    CreateMicrosoftADResultTypeDef,
     CreateSnapshotRequestRequestTypeDef,
+    CreateSnapshotResultTypeDef,
     CreateTrustRequestRequestTypeDef,
+    CreateTrustResultTypeDef,
     DeleteConditionalForwarderRequestRequestTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResultTypeDef,
     DeleteLogSubscriptionRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResultTypeDef,
     DeleteTrustRequestRequestTypeDef,
+    DeleteTrustResultTypeDef,
     DeregisterCertificateRequestRequestTypeDef,
     DeregisterEventTopicRequestRequestTypeDef,
     DescribeCertificateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
     DescribeClientAuthenticationSettingsRequestRequestTypeDef,
     DescribeConditionalForwardersRequestRequestTypeDef,
+    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
     DescribeDirectoriesRequestRequestTypeDef,
+    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
     DescribeDomainControllersRequestRequestTypeDef,
     DomainControllerTypeDef,
     DescribeEventTopicsRequestRequestTypeDef,
     EventTopicTypeDef,
+    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
     DescribeLDAPSSettingsRequestRequestTypeDef,
     LDAPSSettingInfoTypeDef,
+    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
     DescribeRegionsRequestRequestTypeDef,
     DescribeSettingsRequestRequestTypeDef,
     SettingEntryTypeDef,
+    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
     DescribeSharedDirectoriesRequestRequestTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     SnapshotTypeDef,
+    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
     DescribeTrustsRequestRequestTypeDef,
     TrustTypeDef,
+    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
     DescribeUpdateDirectoryRequestRequestTypeDef,
     DirectoryConnectSettingsDescriptionTypeDef,
     DirectoryVpcSettingsDescriptionTypeDef,
     RadiusSettingsTypeDef,
     RegionsInfoTypeDef,
     DirectoryLimitsTypeDef,
     DisableClientAuthenticationRequestRequestTypeDef,
@@ -434,53 +450,51 @@
     DisableSsoRequestRequestTypeDef,
     EnableClientAuthenticationRequestRequestTypeDef,
     EnableLDAPSRequestRequestTypeDef,
     EnableSsoRequestRequestTypeDef,
     GetSnapshotLimitsRequestRequestTypeDef,
     SnapshotLimitsTypeDef,
     IpRouteInfoTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
     ListIpRoutesRequestRequestTypeDef,
+    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
     ListLogSubscriptionsRequestRequestTypeDef,
     LogSubscriptionTypeDef,
+    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
     ListSchemaExtensionsRequestRequestTypeDef,
     SchemaExtensionInfoTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OSUpdateSettingsTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterCertificateResultTypeDef,
     RegisterEventTopicRequestRequestTypeDef,
     RejectSharedDirectoryRequestRequestTypeDef,
+    RejectSharedDirectoryResultTypeDef,
     RemoveIpRoutesRequestRequestTypeDef,
     RemoveRegionRequestRequestTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     SettingTypeDef,
     ShareTargetTypeDef,
+    ShareDirectoryResultTypeDef,
     StartSchemaExtensionRequestRequestTypeDef,
+    StartSchemaExtensionResultTypeDef,
     UnshareTargetTypeDef,
+    UnshareDirectoryResultTypeDef,
     UpdateConditionalForwarderRequestRequestTypeDef,
     UpdateNumberOfDomainControllersRequestRequestTypeDef,
-    UpdateTrustRequestRequestTypeDef,
-    VerifyTrustRequestRequestTypeDef,
-    ConnectDirectoryResultTypeDef,
-    CreateAliasResultTypeDef,
-    CreateDirectoryResultTypeDef,
-    CreateMicrosoftADResultTypeDef,
-    CreateSnapshotResultTypeDef,
-    CreateTrustResultTypeDef,
-    DeleteDirectoryResultTypeDef,
-    DeleteSnapshotResultTypeDef,
-    DeleteTrustResultTypeDef,
-    RegisterCertificateResultTypeDef,
-    RejectSharedDirectoryResultTypeDef,
-    ShareDirectoryResultTypeDef,
-    StartSchemaExtensionResultTypeDef,
-    UnshareDirectoryResultTypeDef,
     UpdateSettingsResultTypeDef,
+    UpdateTrustRequestRequestTypeDef,
     UpdateTrustResultTypeDef,
+    VerifyTrustRequestRequestTypeDef,
     VerifyTrustResultTypeDef,
     AcceptSharedDirectoryResultTypeDef,
     DescribeSharedDirectoriesResultTypeDef,
     AddIpRoutesRequestRequestTypeDef,
     AddRegionRequestRequestTypeDef,
     RegionDescriptionTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
@@ -491,28 +505,14 @@
     CreateComputerRequestRequestTypeDef,
     ListCertificatesResultTypeDef,
     CertificateTypeDef,
     RegisterCertificateRequestRequestTypeDef,
     DescribeClientAuthenticationSettingsResultTypeDef,
     DescribeConditionalForwardersResultTypeDef,
     ConnectDirectoryRequestRequestTypeDef,
-    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
-    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
-    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
-    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
-    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeDomainControllersResultTypeDef,
     DescribeEventTopicsResultTypeDef,
     DescribeLDAPSSettingsResultTypeDef,
     DescribeSettingsResultTypeDef,
     DescribeSnapshotsResultTypeDef,
     DescribeTrustsResultTypeDef,
     EnableRadiusRequestRequestTypeDef,
@@ -545,43 +545,43 @@
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

### Comparing `types-aiobotocore-ds-2.5.0.post1/setup.py` & `types-aiobotocore-ds-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ds.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ds",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ds"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DirectoryService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DirectoryService 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/",
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

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__init__.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__init__.pyi` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/__main__.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DirectoryService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DirectoryService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService\nOther"
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

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/client.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -861,15 +861,15 @@
         *,
         DirectoryId: str,
         ShareTarget: ShareTargetTypeDef,
         ShareMethod: ShareMethodType,
         ShareNotes: str = ...
     ) -> ShareDirectoryResultTypeDef:
         """
-        Shares a specified directory ( `DirectoryId` ) in your Amazon Web Services
+        Shares a specified directory ( `DirectoryId`) in your Amazon Web Services
         account (directory owner) with another Amazon Web Services account (directory
         consumer).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.share_directory)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/client/#share_directory)
         """
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/client.pyi` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -796,15 +796,15 @@
         *,
         DirectoryId: str,
         ShareTarget: ShareTargetTypeDef,
         ShareMethod: ShareMethodType,
         ShareNotes: str = ...
     ) -> ShareDirectoryResultTypeDef:
         """
-        Shares a specified directory ( `DirectoryId` ) in your Amazon Web Services
+        Shares a specified directory ( `DirectoryId`) in your Amazon Web Services
         account (directory owner) with another Amazon Web Services account (directory
         consumer).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Client.share_directory)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/client/#share_directory)
         """
     async def start_schema_extension(
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/literals.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "CertificateStateType",
     "CertificateTypeType",
     "ClientAuthenticationStatusType",
     "ClientAuthenticationTypeType",
     "DescribeClientAuthenticationSettingsPaginatorName",
     "DescribeDirectoriesPaginatorName",
@@ -68,15 +67,14 @@
     "DirectoryServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 CertificateStateType = Literal[
     "DeregisterFailed",
     "Deregistered",
     "Deregistering",
     "RegisterFailed",
     "Registered",
     "Registering",
@@ -234,14 +232,15 @@
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
@@ -320,14 +319,15 @@
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
@@ -338,14 +338,15 @@
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
@@ -381,14 +382,15 @@
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
@@ -407,16 +409,19 @@
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
@@ -500,15 +505,17 @@
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
@@ -553,14 +560,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/literals.pyi` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "CertificateStateType",
     "CertificateTypeType",
     "ClientAuthenticationStatusType",
     "ClientAuthenticationTypeType",
     "DescribeClientAuthenticationSettingsPaginatorName",
     "DescribeDirectoriesPaginatorName",
@@ -67,14 +68,15 @@
     "DirectoryServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 CertificateStateType = Literal[
     "DeregisterFailed",
     "Deregistered",
     "Deregistering",
     "RegisterFailed",
     "Registered",
     "Registering",
@@ -232,14 +234,15 @@
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
@@ -318,14 +321,15 @@
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
@@ -336,14 +340,15 @@
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
@@ -379,14 +384,15 @@
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
@@ -405,16 +411,19 @@
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
@@ -498,15 +507,17 @@
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
@@ -551,14 +562,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/paginator.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -43,15 +43,15 @@
         list_ip_routes_paginator: ListIpRoutesPaginator = client.get_paginator("list_ip_routes")
         list_log_subscriptions_paginator: ListLogSubscriptionsPaginator = client.get_paginator("list_log_subscriptions")
         list_schema_extensions_paginator: ListSchemaExtensionsPaginator = client.get_paginator("list_schema_extensions")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ClientAuthenticationTypeType
 from .type_defs import (
     DescribeClientAuthenticationSettingsResultTypeDef,
@@ -67,18 +67,14 @@
     ListIpRoutesResultTypeDef,
     ListLogSubscriptionsResultTypeDef,
     ListSchemaExtensionsResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -116,30 +112,30 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         Type: ClientAuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClientAuthenticationSettingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeClientAuthenticationSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeclientauthenticationsettingspaginator)
         """
 
 
 class DescribeDirectoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDirectories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedirectoriespaginator)
     """
 
     def paginate(
-        self, *, DirectoryIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedirectoriespaginator)
         """
 
 
@@ -150,15 +146,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         DomainControllerIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDomainControllersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDomainControllers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedomaincontrollerspaginator)
         """
 
 
@@ -169,15 +165,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         Type: Literal["Client"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLDAPSSettingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeLDAPSSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeldapssettingspaginator)
         """
 
 
@@ -188,15 +184,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         RegionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRegionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeRegions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeregionspaginator)
         """
 
 
@@ -207,15 +203,15 @@
     """
 
     def paginate(
         self,
         *,
         OwnerDirectoryId: str,
         SharedDirectoryIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSharedDirectoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeSharedDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeshareddirectoriespaginator)
         """
 
 
@@ -226,15 +222,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str = ...,
         SnapshotIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describesnapshotspaginator)
         """
 
 
@@ -245,15 +241,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str = ...,
         TrustIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTrustsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeTrusts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describetrustspaginator)
         """
 
 
@@ -265,88 +261,88 @@
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         UpdateType: Literal["OS"],
         RegionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUpdateDirectoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeUpdateDirectory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeupdatedirectorypaginator)
         """
 
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listcertificatespaginator)
         """
 
 
 class ListIpRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListIpRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listiproutespaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIpRoutesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListIpRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listiproutespaginator)
         """
 
 
 class ListLogSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListLogSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listlogsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLogSubscriptionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListLogSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listlogsubscriptionspaginator)
         """
 
 
 class ListSchemaExtensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListSchemaExtensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listschemaextensionspaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaExtensionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListSchemaExtensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listschemaextensionspaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/paginator.pyi` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -43,15 +43,15 @@
         list_ip_routes_paginator: ListIpRoutesPaginator = client.get_paginator("list_ip_routes")
         list_log_subscriptions_paginator: ListLogSubscriptionsPaginator = client.get_paginator("list_log_subscriptions")
         list_schema_extensions_paginator: ListSchemaExtensionsPaginator = client.get_paginator("list_schema_extensions")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ClientAuthenticationTypeType
 from .type_defs import (
     DescribeClientAuthenticationSettingsResultTypeDef,
@@ -67,18 +67,14 @@
     ListIpRoutesResultTypeDef,
     ListLogSubscriptionsResultTypeDef,
     ListSchemaExtensionsResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "DescribeClientAuthenticationSettingsPaginator",
@@ -112,29 +108,29 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         Type: ClientAuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClientAuthenticationSettingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeClientAuthenticationSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeclientauthenticationsettingspaginator)
         """
 
 class DescribeDirectoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDirectories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedirectoriespaginator)
     """
 
     def paginate(
-        self, *, DirectoryIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedirectoriespaginator)
         """
 
 class DescribeDomainControllersPaginator(AioPaginator):
@@ -144,15 +140,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         DomainControllerIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDomainControllersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeDomainControllers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describedomaincontrollerspaginator)
         """
 
 class DescribeLDAPSSettingsPaginator(AioPaginator):
@@ -162,15 +158,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         Type: Literal["Client"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLDAPSSettingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeLDAPSSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeldapssettingspaginator)
         """
 
 class DescribeRegionsPaginator(AioPaginator):
@@ -180,15 +176,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         RegionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRegionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeRegions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeregionspaginator)
         """
 
 class DescribeSharedDirectoriesPaginator(AioPaginator):
@@ -198,15 +194,15 @@
     """
 
     def paginate(
         self,
         *,
         OwnerDirectoryId: str,
         SharedDirectoryIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSharedDirectoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeSharedDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeshareddirectoriespaginator)
         """
 
 class DescribeSnapshotsPaginator(AioPaginator):
@@ -216,15 +212,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str = ...,
         SnapshotIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describesnapshotspaginator)
         """
 
 class DescribeTrustsPaginator(AioPaginator):
@@ -234,15 +230,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryId: str = ...,
         TrustIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTrustsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeTrusts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describetrustspaginator)
         """
 
 class DescribeUpdateDirectoryPaginator(AioPaginator):
@@ -253,83 +249,83 @@
 
     def paginate(
         self,
         *,
         DirectoryId: str,
         UpdateType: Literal["OS"],
         RegionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUpdateDirectoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.DescribeUpdateDirectory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#describeupdatedirectorypaginator)
         """
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listcertificatespaginator)
         """
 
 class ListIpRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListIpRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listiproutespaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIpRoutesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListIpRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listiproutespaginator)
         """
 
 class ListLogSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListLogSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listlogsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLogSubscriptionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListLogSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listlogsubscriptionspaginator)
         """
 
 class ListSchemaExtensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListSchemaExtensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listschemaextensionspaginator)
     """
 
     def paginate(
-        self, *, DirectoryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DirectoryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaExtensionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListSchemaExtensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listschemaextensionspaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/type_defs.py` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -53,57 +53,73 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptSharedDirectoryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "SharedDirectoryTypeDef",
     "IpRouteTypeDef",
     "DirectoryVpcSettingsTypeDef",
     "TagTypeDef",
     "AttributeTypeDef",
     "CancelSchemaExtensionRequestRequestTypeDef",
     "CertificateInfoTypeDef",
     "ClientCertAuthSettingsTypeDef",
     "ClientAuthenticationSettingInfoTypeDef",
     "ConditionalForwarderTypeDef",
     "DirectoryConnectSettingsTypeDef",
+    "ConnectDirectoryResultTypeDef",
     "CreateAliasRequestRequestTypeDef",
+    "CreateAliasResultTypeDef",
     "CreateConditionalForwarderRequestRequestTypeDef",
+    "CreateDirectoryResultTypeDef",
     "CreateLogSubscriptionRequestRequestTypeDef",
+    "CreateMicrosoftADResultTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
+    "CreateSnapshotResultTypeDef",
     "CreateTrustRequestRequestTypeDef",
+    "CreateTrustResultTypeDef",
     "DeleteConditionalForwarderRequestRequestTypeDef",
     "DeleteDirectoryRequestRequestTypeDef",
+    "DeleteDirectoryResultTypeDef",
     "DeleteLogSubscriptionRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
+    "DeleteSnapshotResultTypeDef",
     "DeleteTrustRequestRequestTypeDef",
+    "DeleteTrustResultTypeDef",
     "DeregisterCertificateRequestRequestTypeDef",
     "DeregisterEventTopicRequestRequestTypeDef",
     "DescribeCertificateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
     "DescribeClientAuthenticationSettingsRequestRequestTypeDef",
     "DescribeConditionalForwardersRequestRequestTypeDef",
+    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
     "DescribeDirectoriesRequestRequestTypeDef",
+    "DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
     "DescribeDomainControllersRequestRequestTypeDef",
     "DomainControllerTypeDef",
     "DescribeEventTopicsRequestRequestTypeDef",
     "EventTopicTypeDef",
+    "DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
     "DescribeLDAPSSettingsRequestRequestTypeDef",
     "LDAPSSettingInfoTypeDef",
+    "DescribeRegionsRequestDescribeRegionsPaginateTypeDef",
     "DescribeRegionsRequestRequestTypeDef",
     "DescribeSettingsRequestRequestTypeDef",
     "SettingEntryTypeDef",
+    "DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
     "DescribeSharedDirectoriesRequestRequestTypeDef",
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
     "SnapshotTypeDef",
+    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
     "DescribeTrustsRequestRequestTypeDef",
     "TrustTypeDef",
+    "DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
     "DescribeUpdateDirectoryRequestRequestTypeDef",
     "DirectoryConnectSettingsDescriptionTypeDef",
     "DirectoryVpcSettingsDescriptionTypeDef",
     "RadiusSettingsTypeDef",
     "RegionsInfoTypeDef",
     "DirectoryLimitsTypeDef",
     "DisableClientAuthenticationRequestRequestTypeDef",
@@ -112,53 +128,51 @@
     "DisableSsoRequestRequestTypeDef",
     "EnableClientAuthenticationRequestRequestTypeDef",
     "EnableLDAPSRequestRequestTypeDef",
     "EnableSsoRequestRequestTypeDef",
     "GetSnapshotLimitsRequestRequestTypeDef",
     "SnapshotLimitsTypeDef",
     "IpRouteInfoTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
+    "ListIpRoutesRequestListIpRoutesPaginateTypeDef",
     "ListIpRoutesRequestRequestTypeDef",
+    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
     "ListLogSubscriptionsRequestRequestTypeDef",
     "LogSubscriptionTypeDef",
+    "ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
     "ListSchemaExtensionsRequestRequestTypeDef",
     "SchemaExtensionInfoTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OSUpdateSettingsTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterCertificateResultTypeDef",
     "RegisterEventTopicRequestRequestTypeDef",
     "RejectSharedDirectoryRequestRequestTypeDef",
+    "RejectSharedDirectoryResultTypeDef",
     "RemoveIpRoutesRequestRequestTypeDef",
     "RemoveRegionRequestRequestTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
     "ResetUserPasswordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreFromSnapshotRequestRequestTypeDef",
     "SettingTypeDef",
     "ShareTargetTypeDef",
+    "ShareDirectoryResultTypeDef",
     "StartSchemaExtensionRequestRequestTypeDef",
+    "StartSchemaExtensionResultTypeDef",
     "UnshareTargetTypeDef",
+    "UnshareDirectoryResultTypeDef",
     "UpdateConditionalForwarderRequestRequestTypeDef",
     "UpdateNumberOfDomainControllersRequestRequestTypeDef",
-    "UpdateTrustRequestRequestTypeDef",
-    "VerifyTrustRequestRequestTypeDef",
-    "ConnectDirectoryResultTypeDef",
-    "CreateAliasResultTypeDef",
-    "CreateDirectoryResultTypeDef",
-    "CreateMicrosoftADResultTypeDef",
-    "CreateSnapshotResultTypeDef",
-    "CreateTrustResultTypeDef",
-    "DeleteDirectoryResultTypeDef",
-    "DeleteSnapshotResultTypeDef",
-    "DeleteTrustResultTypeDef",
-    "RegisterCertificateResultTypeDef",
-    "RejectSharedDirectoryResultTypeDef",
-    "ShareDirectoryResultTypeDef",
-    "StartSchemaExtensionResultTypeDef",
-    "UnshareDirectoryResultTypeDef",
     "UpdateSettingsResultTypeDef",
+    "UpdateTrustRequestRequestTypeDef",
     "UpdateTrustResultTypeDef",
+    "VerifyTrustRequestRequestTypeDef",
     "VerifyTrustResultTypeDef",
     "AcceptSharedDirectoryResultTypeDef",
     "DescribeSharedDirectoriesResultTypeDef",
     "AddIpRoutesRequestRequestTypeDef",
     "AddRegionRequestRequestTypeDef",
     "RegionDescriptionTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
@@ -169,28 +183,14 @@
     "CreateComputerRequestRequestTypeDef",
     "ListCertificatesResultTypeDef",
     "CertificateTypeDef",
     "RegisterCertificateRequestRequestTypeDef",
     "DescribeClientAuthenticationSettingsResultTypeDef",
     "DescribeConditionalForwardersResultTypeDef",
     "ConnectDirectoryRequestRequestTypeDef",
-    "DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
-    "DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    "DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    "DescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    "DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
-    "DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
-    "ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeDomainControllersResultTypeDef",
     "DescribeEventTopicsResultTypeDef",
     "DescribeLDAPSSettingsResultTypeDef",
     "DescribeSettingsResultTypeDef",
     "DescribeSnapshotsResultTypeDef",
     "DescribeTrustsResultTypeDef",
     "EnableRadiusRequestRequestTypeDef",
@@ -218,25 +218,14 @@
 AcceptSharedDirectoryRequestRequestTypeDef = TypedDict(
     "AcceptSharedDirectoryRequestRequestTypeDef",
     {
         "SharedDirectoryId": str,
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
 SharedDirectoryTypeDef = TypedDict(
     "SharedDirectoryTypeDef",
     {
         "OwnerAccountId": str,
         "OwnerDirectoryId": str,
         "ShareMethod": ShareMethodType,
         "SharedAccountId": str,
@@ -337,39 +326,72 @@
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "CustomerDnsIps": Sequence[str],
         "CustomerUserName": str,
     },
 )
 
+ConnectDirectoryResultTypeDef = TypedDict(
+    "ConnectDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateAliasRequestRequestTypeDef = TypedDict(
     "CreateAliasRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "Alias": str,
     },
 )
 
+CreateAliasResultTypeDef = TypedDict(
+    "CreateAliasResultTypeDef",
+    {
+        "DirectoryId": str,
+        "Alias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConditionalForwarderRequestRequestTypeDef = TypedDict(
     "CreateConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "DnsIpAddrs": Sequence[str],
     },
 )
 
+CreateDirectoryResultTypeDef = TypedDict(
+    "CreateDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateLogSubscriptionRequestRequestTypeDef = TypedDict(
     "CreateLogSubscriptionRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "LogGroupName": str,
     },
 )
 
+CreateMicrosoftADResultTypeDef = TypedDict(
+    "CreateMicrosoftADResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalCreateSnapshotRequestRequestTypeDef = TypedDict(
@@ -383,14 +405,22 @@
 
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
 
+CreateSnapshotResultTypeDef = TypedDict(
+    "CreateSnapshotResultTypeDef",
+    {
+        "SnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateTrustRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrustRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "TrustPassword": str,
         "TrustDirection": TrustDirectionType,
@@ -409,14 +439,22 @@
 
 class CreateTrustRequestRequestTypeDef(
     _RequiredCreateTrustRequestRequestTypeDef, _OptionalCreateTrustRequestRequestTypeDef
 ):
     pass
 
 
+CreateTrustResultTypeDef = TypedDict(
+    "CreateTrustResultTypeDef",
+    {
+        "TrustId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteConditionalForwarderRequestRequestTypeDef = TypedDict(
     "DeleteConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
     },
 )
@@ -424,28 +462,44 @@
 DeleteDirectoryRequestRequestTypeDef = TypedDict(
     "DeleteDirectoryRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 
+DeleteDirectoryResultTypeDef = TypedDict(
+    "DeleteDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLogSubscriptionRequestRequestTypeDef = TypedDict(
     "DeleteLogSubscriptionRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 
 DeleteSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 
+DeleteSnapshotResultTypeDef = TypedDict(
+    "DeleteSnapshotResultTypeDef",
+    {
+        "SnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTrustRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTrustRequestRequestTypeDef",
     {
         "TrustId": str,
     },
 )
 _OptionalDeleteTrustRequestRequestTypeDef = TypedDict(
@@ -459,14 +513,22 @@
 
 class DeleteTrustRequestRequestTypeDef(
     _RequiredDeleteTrustRequestRequestTypeDef, _OptionalDeleteTrustRequestRequestTypeDef
 ):
     pass
 
 
+DeleteTrustResultTypeDef = TypedDict(
+    "DeleteTrustResultTypeDef",
+    {
+        "TrustId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterCertificateRequestRequestTypeDef = TypedDict(
     "DeregisterCertificateRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CertificateId": str,
     },
 )
@@ -483,24 +545,37 @@
     "DescribeCertificateRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CertificateId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
+    {
+        "Type": ClientAuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef(
+    _RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
+    _OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeClientAuthenticationSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeClientAuthenticationSettingsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeClientAuthenticationSettingsRequestRequestTypeDef = TypedDict(
@@ -539,24 +614,56 @@
 class DescribeConditionalForwardersRequestRequestTypeDef(
     _RequiredDescribeConditionalForwardersRequestRequestTypeDef,
     _OptionalDescribeConditionalForwardersRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef = TypedDict(
+    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
+    {
+        "DirectoryIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectoriesRequestRequestTypeDef = TypedDict(
     "DescribeDirectoriesRequestRequestTypeDef",
     {
         "DirectoryIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
+    {
+        "DomainControllerIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef(
+    _RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
+    _OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeDomainControllersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDomainControllersRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeDomainControllersRequestRequestTypeDef = TypedDict(
@@ -611,14 +718,37 @@
         "TopicArn": str,
         "CreatedDateTime": datetime,
         "Status": TopicStatusType,
     },
     total=False,
 )
 
+_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
+    {
+        "Type": Literal["Client"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef(
+    _RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
+    _OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeLDAPSSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLDAPSSettingsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeLDAPSSettingsRequestRequestTypeDef = TypedDict(
@@ -645,14 +775,37 @@
         "LDAPSStatus": LDAPSStatusType,
         "LDAPSStatusReason": str,
         "LastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
+    {
+        "RegionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeRegionsRequestDescribeRegionsPaginateTypeDef(
+    _RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
+    _OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeRegionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRegionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeRegionsRequestRequestTypeDef = TypedDict(
@@ -702,18 +855,42 @@
         "AppliedValue": str,
         "RequestedValue": str,
         "RequestStatus": DirectoryConfigurationStatusType,
         "RequestDetailedStatus": Dict[str, DirectoryConfigurationStatusType],
         "RequestStatusMessage": str,
         "LastUpdatedDateTime": datetime,
         "LastRequestedDateTime": datetime,
+        "DataType": str,
+    },
+    total=False,
+)
+
+_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
+    {
+        "OwnerDirectoryId": str,
+    },
+)
+_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
+    {
+        "SharedDirectoryIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef(
+    _RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
+    _OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeSharedDirectoriesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSharedDirectoriesRequestRequestTypeDef",
     {
         "OwnerDirectoryId": str,
     },
 )
 _OptionalDescribeSharedDirectoriesRequestRequestTypeDef = TypedDict(
@@ -730,14 +907,24 @@
 class DescribeSharedDirectoriesRequestRequestTypeDef(
     _RequiredDescribeSharedDirectoriesRequestRequestTypeDef,
     _OptionalDescribeSharedDirectoriesRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "SnapshotIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "SnapshotIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
@@ -754,14 +941,24 @@
         "Name": str,
         "Status": SnapshotStatusType,
         "StartTime": datetime,
     },
     total=False,
 )
 
+DescribeTrustsRequestDescribeTrustsPaginateTypeDef = TypedDict(
+    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "TrustIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeTrustsRequestRequestTypeDef = TypedDict(
     "DescribeTrustsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "TrustIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
@@ -783,14 +980,38 @@
         "StateLastUpdatedDateTime": datetime,
         "TrustStateReason": str,
         "SelectiveAuth": SelectiveAuthType,
     },
     total=False,
 )
 
+_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
+    "_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "UpdateType": Literal["OS"],
+    },
+)
+_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
+    "_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
+    {
+        "RegionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef(
+    _RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
+    _OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeUpdateDirectoryRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeUpdateDirectoryRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "UpdateType": Literal["OS"],
     },
 )
@@ -984,14 +1205,36 @@
         "AddedDateTime": datetime,
         "IpRouteStatusReason": str,
         "Description": str,
     },
     total=False,
 )
 
+_RequiredListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "_RequiredListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "_OptionalListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCertificatesRequestListCertificatesPaginateTypeDef(
+    _RequiredListCertificatesRequestListCertificatesPaginateTypeDef,
+    _OptionalListCertificatesRequestListCertificatesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCertificatesRequestRequestTypeDef = TypedDict(
     "_RequiredListCertificatesRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListCertificatesRequestRequestTypeDef = TypedDict(
@@ -1006,14 +1249,36 @@
 
 class ListCertificatesRequestRequestTypeDef(
     _RequiredListCertificatesRequestRequestTypeDef, _OptionalListCertificatesRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListIpRoutesRequestListIpRoutesPaginateTypeDef(
+    _RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef,
+    _OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListIpRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredListIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListIpRoutesRequestRequestTypeDef = TypedDict(
@@ -1028,14 +1293,23 @@
 
 class ListIpRoutesRequestRequestTypeDef(
     _RequiredListIpRoutesRequestRequestTypeDef, _OptionalListIpRoutesRequestRequestTypeDef
 ):
     pass
 
 
+ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef = TypedDict(
+    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLogSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListLogSubscriptionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "NextToken": str,
         "Limit": int,
     },
@@ -1048,14 +1322,36 @@
         "DirectoryId": str,
         "LogGroupName": str,
         "SubscriptionCreatedDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef(
+    _RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
+    _OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemaExtensionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemaExtensionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListSchemaExtensionsRequestRequestTypeDef = TypedDict(
@@ -1085,14 +1381,36 @@
         "SchemaExtensionStatusReason": str,
         "StartDateTime": datetime,
         "EndDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceId": str,
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
         "ResourceId": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -1116,14 +1434,32 @@
     "OSUpdateSettingsTypeDef",
     {
         "OSVersion": OSVersionType,
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
+RegisterCertificateResultTypeDef = TypedDict(
+    "RegisterCertificateResultTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterEventTopicRequestRequestTypeDef = TypedDict(
     "RegisterEventTopicRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "TopicName": str,
     },
 )
@@ -1131,14 +1467,22 @@
 RejectSharedDirectoryRequestRequestTypeDef = TypedDict(
     "RejectSharedDirectoryRequestRequestTypeDef",
     {
         "SharedDirectoryId": str,
     },
 )
 
+RejectSharedDirectoryResultTypeDef = TypedDict(
+    "RejectSharedDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveIpRoutesRequestRequestTypeDef = TypedDict(
     "RemoveIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CidrIps": Sequence[str],
     },
 )
@@ -1163,14 +1507,25 @@
     {
         "DirectoryId": str,
         "UserName": str,
         "NewPassword": str,
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
 RestoreFromSnapshotRequestRequestTypeDef = TypedDict(
     "RestoreFromSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 
@@ -1186,32 +1541,56 @@
     "ShareTargetTypeDef",
     {
         "Id": str,
         "Type": Literal["ACCOUNT"],
     },
 )
 
+ShareDirectoryResultTypeDef = TypedDict(
+    "ShareDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartSchemaExtensionRequestRequestTypeDef = TypedDict(
     "StartSchemaExtensionRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CreateSnapshotBeforeSchemaExtension": bool,
         "LdifContent": str,
         "Description": str,
     },
 )
 
+StartSchemaExtensionResultTypeDef = TypedDict(
+    "StartSchemaExtensionResultTypeDef",
+    {
+        "SchemaExtensionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnshareTargetTypeDef = TypedDict(
     "UnshareTargetTypeDef",
     {
         "Id": str,
         "Type": Literal["ACCOUNT"],
     },
 )
 
+UnshareDirectoryResultTypeDef = TypedDict(
+    "UnshareDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateConditionalForwarderRequestRequestTypeDef = TypedDict(
     "UpdateConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "DnsIpAddrs": Sequence[str],
     },
@@ -1221,14 +1600,22 @@
     "UpdateNumberOfDomainControllersRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "DesiredNumber": int,
     },
 )
 
+UpdateSettingsResultTypeDef = TypedDict(
+    "UpdateSettingsResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateTrustRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTrustRequestRequestTypeDef",
     {
         "TrustId": str,
     },
 )
 _OptionalUpdateTrustRequestRequestTypeDef = TypedDict(
@@ -1242,173 +1629,52 @@
 
 class UpdateTrustRequestRequestTypeDef(
     _RequiredUpdateTrustRequestRequestTypeDef, _OptionalUpdateTrustRequestRequestTypeDef
 ):
     pass
 
 
-VerifyTrustRequestRequestTypeDef = TypedDict(
-    "VerifyTrustRequestRequestTypeDef",
-    {
-        "TrustId": str,
-    },
-)
-
-ConnectDirectoryResultTypeDef = TypedDict(
-    "ConnectDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAliasResultTypeDef = TypedDict(
-    "CreateAliasResultTypeDef",
-    {
-        "DirectoryId": str,
-        "Alias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDirectoryResultTypeDef = TypedDict(
-    "CreateDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMicrosoftADResultTypeDef = TypedDict(
-    "CreateMicrosoftADResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSnapshotResultTypeDef = TypedDict(
-    "CreateSnapshotResultTypeDef",
-    {
-        "SnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTrustResultTypeDef = TypedDict(
-    "CreateTrustResultTypeDef",
-    {
-        "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDirectoryResultTypeDef = TypedDict(
-    "DeleteDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSnapshotResultTypeDef = TypedDict(
-    "DeleteSnapshotResultTypeDef",
-    {
-        "SnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteTrustResultTypeDef = TypedDict(
-    "DeleteTrustResultTypeDef",
+UpdateTrustResultTypeDef = TypedDict(
+    "UpdateTrustResultTypeDef",
     {
+        "RequestId": str,
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateResultTypeDef = TypedDict(
-    "RegisterCertificateResultTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RejectSharedDirectoryResultTypeDef = TypedDict(
-    "RejectSharedDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ShareDirectoryResultTypeDef = TypedDict(
-    "ShareDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSchemaExtensionResultTypeDef = TypedDict(
-    "StartSchemaExtensionResultTypeDef",
-    {
-        "SchemaExtensionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnshareDirectoryResultTypeDef = TypedDict(
-    "UnshareDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSettingsResultTypeDef = TypedDict(
-    "UpdateSettingsResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateTrustResultTypeDef = TypedDict(
-    "UpdateTrustResultTypeDef",
+VerifyTrustRequestRequestTypeDef = TypedDict(
+    "VerifyTrustRequestRequestTypeDef",
     {
-        "RequestId": str,
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
 VerifyTrustResultTypeDef = TypedDict(
     "VerifyTrustResultTypeDef",
     {
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptSharedDirectoryResultTypeDef = TypedDict(
     "AcceptSharedDirectoryResultTypeDef",
     {
         "SharedDirectory": SharedDirectoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSharedDirectoriesResultTypeDef = TypedDict(
     "DescribeSharedDirectoriesResultTypeDef",
     {
         "SharedDirectories": List[SharedDirectoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddIpRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredAddIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -1516,15 +1782,15 @@
 
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComputerTypeDef = TypedDict(
     "ComputerTypeDef",
     {
         "ComputerId": str,
@@ -1559,15 +1825,15 @@
 
 
 ListCertificatesResultTypeDef = TypedDict(
     "ListCertificatesResultTypeDef",
     {
         "NextToken": str,
         "CertificatesInfo": List[CertificateInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateTypeDef = TypedDict(
     "CertificateTypeDef",
     {
         "CertificateId": str,
@@ -1607,23 +1873,23 @@
 
 
 DescribeClientAuthenticationSettingsResultTypeDef = TypedDict(
     "DescribeClientAuthenticationSettingsResultTypeDef",
     {
         "ClientAuthenticationSettingsInfo": List[ClientAuthenticationSettingInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConditionalForwardersResultTypeDef = TypedDict(
     "DescribeConditionalForwardersResultTypeDef",
     {
         "ConditionalForwarders": List[ConditionalForwarderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConnectDirectoryRequestRequestTypeDef = TypedDict(
     "_RequiredConnectDirectoryRequestRequestTypeDef",
     {
         "Name": str,
@@ -1645,330 +1911,65 @@
 
 class ConnectDirectoryRequestRequestTypeDef(
     _RequiredConnectDirectoryRequestRequestTypeDef, _OptionalConnectDirectoryRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    {
-        "Type": ClientAuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef(
-    _RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-    _OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-):
-    pass
-
-
-DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef = TypedDict(
-    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
-    {
-        "DirectoryIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    {
-        "DomainControllerIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef(
-    _RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-    _OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    {
-        "Type": Literal["Client"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef(
-    _RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-    _OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    {
-        "RegionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeRegionsRequestDescribeRegionsPaginateTypeDef(
-    _RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-    _OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    {
-        "OwnerDirectoryId": str,
-    },
-)
-_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    {
-        "SharedDirectoryIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef(
-    _RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-    _OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-):
-    pass
-
-
-DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "SnapshotIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeTrustsRequestDescribeTrustsPaginateTypeDef = TypedDict(
-    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "TrustIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
-    "_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "UpdateType": Literal["OS"],
-    },
-)
-_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
-    "_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    {
-        "RegionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef(
-    _RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-    _OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "_RequiredListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "_OptionalListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCertificatesRequestListCertificatesPaginateTypeDef(
-    _RequiredListCertificatesRequestListCertificatesPaginateTypeDef,
-    _OptionalListCertificatesRequestListCertificatesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListIpRoutesRequestListIpRoutesPaginateTypeDef(
-    _RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef,
-    _OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef,
-):
-    pass
-
-
-ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef = TypedDict(
-    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef(
-    _RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-    _OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceId": str,
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
 DescribeDomainControllersResultTypeDef = TypedDict(
     "DescribeDomainControllersResultTypeDef",
     {
         "DomainControllers": List[DomainControllerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventTopicsResultTypeDef = TypedDict(
     "DescribeEventTopicsResultTypeDef",
     {
         "EventTopics": List[EventTopicTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLDAPSSettingsResultTypeDef = TypedDict(
     "DescribeLDAPSSettingsResultTypeDef",
     {
         "LDAPSSettingsInfo": List[LDAPSSettingInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSettingsResultTypeDef = TypedDict(
     "DescribeSettingsResultTypeDef",
     {
         "DirectoryId": str,
         "SettingEntries": List[SettingEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResultTypeDef = TypedDict(
     "DescribeSnapshotsResultTypeDef",
     {
         "Snapshots": List[SnapshotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustsResultTypeDef = TypedDict(
     "DescribeTrustsResultTypeDef",
     {
         "Trusts": List[TrustTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableRadiusRequestRequestTypeDef = TypedDict(
     "EnableRadiusRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -1997,50 +1998,50 @@
     },
 )
 
 GetDirectoryLimitsResultTypeDef = TypedDict(
     "GetDirectoryLimitsResultTypeDef",
     {
         "DirectoryLimits": DirectoryLimitsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotLimitsResultTypeDef = TypedDict(
     "GetSnapshotLimitsResultTypeDef",
     {
         "SnapshotLimits": SnapshotLimitsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIpRoutesResultTypeDef = TypedDict(
     "ListIpRoutesResultTypeDef",
     {
         "IpRoutesInfo": List[IpRouteInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLogSubscriptionsResultTypeDef = TypedDict(
     "ListLogSubscriptionsResultTypeDef",
     {
         "LogSubscriptions": List[LogSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaExtensionsResultTypeDef = TypedDict(
     "ListSchemaExtensionsResultTypeDef",
     {
         "SchemaExtensionsInfo": List[SchemaExtensionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDirectorySetupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDirectorySetupRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -2112,31 +2113,31 @@
 )
 
 DescribeRegionsResultTypeDef = TypedDict(
     "DescribeRegionsResultTypeDef",
     {
         "RegionsDescription": List[RegionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComputerResultTypeDef = TypedDict(
     "CreateComputerResultTypeDef",
     {
         "Computer": ComputerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResultTypeDef = TypedDict(
     "DescribeCertificateResultTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DirectoryDescriptionTypeDef = TypedDict(
     "DirectoryDescriptionTypeDef",
     {
         "DirectoryId": str,
@@ -2185,19 +2186,19 @@
 )
 
 DescribeDirectoriesResultTypeDef = TypedDict(
     "DescribeDirectoriesResultTypeDef",
     {
         "DirectoryDescriptions": List[DirectoryDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUpdateDirectoryResultTypeDef = TypedDict(
     "DescribeUpdateDirectoryResultTypeDef",
     {
         "UpdateActivities": List[UpdateInfoEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds/type_defs.pyi` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -52,57 +52,73 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptSharedDirectoryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "SharedDirectoryTypeDef",
     "IpRouteTypeDef",
     "DirectoryVpcSettingsTypeDef",
     "TagTypeDef",
     "AttributeTypeDef",
     "CancelSchemaExtensionRequestRequestTypeDef",
     "CertificateInfoTypeDef",
     "ClientCertAuthSettingsTypeDef",
     "ClientAuthenticationSettingInfoTypeDef",
     "ConditionalForwarderTypeDef",
     "DirectoryConnectSettingsTypeDef",
+    "ConnectDirectoryResultTypeDef",
     "CreateAliasRequestRequestTypeDef",
+    "CreateAliasResultTypeDef",
     "CreateConditionalForwarderRequestRequestTypeDef",
+    "CreateDirectoryResultTypeDef",
     "CreateLogSubscriptionRequestRequestTypeDef",
+    "CreateMicrosoftADResultTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
+    "CreateSnapshotResultTypeDef",
     "CreateTrustRequestRequestTypeDef",
+    "CreateTrustResultTypeDef",
     "DeleteConditionalForwarderRequestRequestTypeDef",
     "DeleteDirectoryRequestRequestTypeDef",
+    "DeleteDirectoryResultTypeDef",
     "DeleteLogSubscriptionRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
+    "DeleteSnapshotResultTypeDef",
     "DeleteTrustRequestRequestTypeDef",
+    "DeleteTrustResultTypeDef",
     "DeregisterCertificateRequestRequestTypeDef",
     "DeregisterEventTopicRequestRequestTypeDef",
     "DescribeCertificateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
     "DescribeClientAuthenticationSettingsRequestRequestTypeDef",
     "DescribeConditionalForwardersRequestRequestTypeDef",
+    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
     "DescribeDirectoriesRequestRequestTypeDef",
+    "DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
     "DescribeDomainControllersRequestRequestTypeDef",
     "DomainControllerTypeDef",
     "DescribeEventTopicsRequestRequestTypeDef",
     "EventTopicTypeDef",
+    "DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
     "DescribeLDAPSSettingsRequestRequestTypeDef",
     "LDAPSSettingInfoTypeDef",
+    "DescribeRegionsRequestDescribeRegionsPaginateTypeDef",
     "DescribeRegionsRequestRequestTypeDef",
     "DescribeSettingsRequestRequestTypeDef",
     "SettingEntryTypeDef",
+    "DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
     "DescribeSharedDirectoriesRequestRequestTypeDef",
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
     "SnapshotTypeDef",
+    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
     "DescribeTrustsRequestRequestTypeDef",
     "TrustTypeDef",
+    "DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
     "DescribeUpdateDirectoryRequestRequestTypeDef",
     "DirectoryConnectSettingsDescriptionTypeDef",
     "DirectoryVpcSettingsDescriptionTypeDef",
     "RadiusSettingsTypeDef",
     "RegionsInfoTypeDef",
     "DirectoryLimitsTypeDef",
     "DisableClientAuthenticationRequestRequestTypeDef",
@@ -111,53 +127,51 @@
     "DisableSsoRequestRequestTypeDef",
     "EnableClientAuthenticationRequestRequestTypeDef",
     "EnableLDAPSRequestRequestTypeDef",
     "EnableSsoRequestRequestTypeDef",
     "GetSnapshotLimitsRequestRequestTypeDef",
     "SnapshotLimitsTypeDef",
     "IpRouteInfoTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
+    "ListIpRoutesRequestListIpRoutesPaginateTypeDef",
     "ListIpRoutesRequestRequestTypeDef",
+    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
     "ListLogSubscriptionsRequestRequestTypeDef",
     "LogSubscriptionTypeDef",
+    "ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
     "ListSchemaExtensionsRequestRequestTypeDef",
     "SchemaExtensionInfoTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OSUpdateSettingsTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterCertificateResultTypeDef",
     "RegisterEventTopicRequestRequestTypeDef",
     "RejectSharedDirectoryRequestRequestTypeDef",
+    "RejectSharedDirectoryResultTypeDef",
     "RemoveIpRoutesRequestRequestTypeDef",
     "RemoveRegionRequestRequestTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
     "ResetUserPasswordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreFromSnapshotRequestRequestTypeDef",
     "SettingTypeDef",
     "ShareTargetTypeDef",
+    "ShareDirectoryResultTypeDef",
     "StartSchemaExtensionRequestRequestTypeDef",
+    "StartSchemaExtensionResultTypeDef",
     "UnshareTargetTypeDef",
+    "UnshareDirectoryResultTypeDef",
     "UpdateConditionalForwarderRequestRequestTypeDef",
     "UpdateNumberOfDomainControllersRequestRequestTypeDef",
-    "UpdateTrustRequestRequestTypeDef",
-    "VerifyTrustRequestRequestTypeDef",
-    "ConnectDirectoryResultTypeDef",
-    "CreateAliasResultTypeDef",
-    "CreateDirectoryResultTypeDef",
-    "CreateMicrosoftADResultTypeDef",
-    "CreateSnapshotResultTypeDef",
-    "CreateTrustResultTypeDef",
-    "DeleteDirectoryResultTypeDef",
-    "DeleteSnapshotResultTypeDef",
-    "DeleteTrustResultTypeDef",
-    "RegisterCertificateResultTypeDef",
-    "RejectSharedDirectoryResultTypeDef",
-    "ShareDirectoryResultTypeDef",
-    "StartSchemaExtensionResultTypeDef",
-    "UnshareDirectoryResultTypeDef",
     "UpdateSettingsResultTypeDef",
+    "UpdateTrustRequestRequestTypeDef",
     "UpdateTrustResultTypeDef",
+    "VerifyTrustRequestRequestTypeDef",
     "VerifyTrustResultTypeDef",
     "AcceptSharedDirectoryResultTypeDef",
     "DescribeSharedDirectoriesResultTypeDef",
     "AddIpRoutesRequestRequestTypeDef",
     "AddRegionRequestRequestTypeDef",
     "RegionDescriptionTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
@@ -168,28 +182,14 @@
     "CreateComputerRequestRequestTypeDef",
     "ListCertificatesResultTypeDef",
     "CertificateTypeDef",
     "RegisterCertificateRequestRequestTypeDef",
     "DescribeClientAuthenticationSettingsResultTypeDef",
     "DescribeConditionalForwardersResultTypeDef",
     "ConnectDirectoryRequestRequestTypeDef",
-    "DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
-    "DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    "DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    "DescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    "DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
-    "DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
-    "ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeDomainControllersResultTypeDef",
     "DescribeEventTopicsResultTypeDef",
     "DescribeLDAPSSettingsResultTypeDef",
     "DescribeSettingsResultTypeDef",
     "DescribeSnapshotsResultTypeDef",
     "DescribeTrustsResultTypeDef",
     "EnableRadiusRequestRequestTypeDef",
@@ -217,25 +217,14 @@
 AcceptSharedDirectoryRequestRequestTypeDef = TypedDict(
     "AcceptSharedDirectoryRequestRequestTypeDef",
     {
         "SharedDirectoryId": str,
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
 SharedDirectoryTypeDef = TypedDict(
     "SharedDirectoryTypeDef",
     {
         "OwnerAccountId": str,
         "OwnerDirectoryId": str,
         "ShareMethod": ShareMethodType,
         "SharedAccountId": str,
@@ -336,39 +325,72 @@
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "CustomerDnsIps": Sequence[str],
         "CustomerUserName": str,
     },
 )
 
+ConnectDirectoryResultTypeDef = TypedDict(
+    "ConnectDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateAliasRequestRequestTypeDef = TypedDict(
     "CreateAliasRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "Alias": str,
     },
 )
 
+CreateAliasResultTypeDef = TypedDict(
+    "CreateAliasResultTypeDef",
+    {
+        "DirectoryId": str,
+        "Alias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConditionalForwarderRequestRequestTypeDef = TypedDict(
     "CreateConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "DnsIpAddrs": Sequence[str],
     },
 )
 
+CreateDirectoryResultTypeDef = TypedDict(
+    "CreateDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateLogSubscriptionRequestRequestTypeDef = TypedDict(
     "CreateLogSubscriptionRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "LogGroupName": str,
     },
 )
 
+CreateMicrosoftADResultTypeDef = TypedDict(
+    "CreateMicrosoftADResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalCreateSnapshotRequestRequestTypeDef = TypedDict(
@@ -380,14 +402,22 @@
 )
 
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
+CreateSnapshotResultTypeDef = TypedDict(
+    "CreateSnapshotResultTypeDef",
+    {
+        "SnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateTrustRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrustRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "TrustPassword": str,
         "TrustDirection": TrustDirectionType,
@@ -404,14 +434,22 @@
 )
 
 class CreateTrustRequestRequestTypeDef(
     _RequiredCreateTrustRequestRequestTypeDef, _OptionalCreateTrustRequestRequestTypeDef
 ):
     pass
 
+CreateTrustResultTypeDef = TypedDict(
+    "CreateTrustResultTypeDef",
+    {
+        "TrustId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteConditionalForwarderRequestRequestTypeDef = TypedDict(
     "DeleteConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
     },
 )
@@ -419,28 +457,44 @@
 DeleteDirectoryRequestRequestTypeDef = TypedDict(
     "DeleteDirectoryRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 
+DeleteDirectoryResultTypeDef = TypedDict(
+    "DeleteDirectoryResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLogSubscriptionRequestRequestTypeDef = TypedDict(
     "DeleteLogSubscriptionRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 
 DeleteSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 
+DeleteSnapshotResultTypeDef = TypedDict(
+    "DeleteSnapshotResultTypeDef",
+    {
+        "SnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTrustRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTrustRequestRequestTypeDef",
     {
         "TrustId": str,
     },
 )
 _OptionalDeleteTrustRequestRequestTypeDef = TypedDict(
@@ -452,14 +506,22 @@
 )
 
 class DeleteTrustRequestRequestTypeDef(
     _RequiredDeleteTrustRequestRequestTypeDef, _OptionalDeleteTrustRequestRequestTypeDef
 ):
     pass
 
+DeleteTrustResultTypeDef = TypedDict(
+    "DeleteTrustResultTypeDef",
+    {
+        "TrustId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterCertificateRequestRequestTypeDef = TypedDict(
     "DeregisterCertificateRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CertificateId": str,
     },
 )
@@ -476,24 +538,35 @@
     "DescribeCertificateRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CertificateId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
+    {
+        "Type": ClientAuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef(
+    _RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
+    _OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeClientAuthenticationSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeClientAuthenticationSettingsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeClientAuthenticationSettingsRequestRequestTypeDef = TypedDict(
@@ -528,24 +601,54 @@
 
 class DescribeConditionalForwardersRequestRequestTypeDef(
     _RequiredDescribeConditionalForwardersRequestRequestTypeDef,
     _OptionalDescribeConditionalForwardersRequestRequestTypeDef,
 ):
     pass
 
+DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef = TypedDict(
+    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
+    {
+        "DirectoryIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectoriesRequestRequestTypeDef = TypedDict(
     "DescribeDirectoriesRequestRequestTypeDef",
     {
         "DirectoryIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
+    {
+        "DomainControllerIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef(
+    _RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
+    _OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDomainControllersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDomainControllersRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeDomainControllersRequestRequestTypeDef = TypedDict(
@@ -598,14 +701,35 @@
         "TopicArn": str,
         "CreatedDateTime": datetime,
         "Status": TopicStatusType,
     },
     total=False,
 )
 
+_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
+    {
+        "Type": Literal["Client"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef(
+    _RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
+    _OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeLDAPSSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLDAPSSettingsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeLDAPSSettingsRequestRequestTypeDef = TypedDict(
@@ -630,14 +754,35 @@
         "LDAPSStatus": LDAPSStatusType,
         "LDAPSStatusReason": str,
         "LastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
+    {
+        "RegionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeRegionsRequestDescribeRegionsPaginateTypeDef(
+    _RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
+    _OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeRegionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRegionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalDescribeRegionsRequestRequestTypeDef = TypedDict(
@@ -683,18 +828,40 @@
         "AppliedValue": str,
         "RequestedValue": str,
         "RequestStatus": DirectoryConfigurationStatusType,
         "RequestDetailedStatus": Dict[str, DirectoryConfigurationStatusType],
         "RequestStatusMessage": str,
         "LastUpdatedDateTime": datetime,
         "LastRequestedDateTime": datetime,
+        "DataType": str,
+    },
+    total=False,
+)
+
+_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
+    {
+        "OwnerDirectoryId": str,
+    },
+)
+_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
+    {
+        "SharedDirectoryIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef(
+    _RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
+    _OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeSharedDirectoriesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSharedDirectoriesRequestRequestTypeDef",
     {
         "OwnerDirectoryId": str,
     },
 )
 _OptionalDescribeSharedDirectoriesRequestRequestTypeDef = TypedDict(
@@ -709,14 +876,24 @@
 
 class DescribeSharedDirectoriesRequestRequestTypeDef(
     _RequiredDescribeSharedDirectoriesRequestRequestTypeDef,
     _OptionalDescribeSharedDirectoriesRequestRequestTypeDef,
 ):
     pass
 
+DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "SnapshotIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "SnapshotIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
@@ -733,14 +910,24 @@
         "Name": str,
         "Status": SnapshotStatusType,
         "StartTime": datetime,
     },
     total=False,
 )
 
+DescribeTrustsRequestDescribeTrustsPaginateTypeDef = TypedDict(
+    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "TrustIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeTrustsRequestRequestTypeDef = TypedDict(
     "DescribeTrustsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "TrustIds": Sequence[str],
         "NextToken": str,
         "Limit": int,
@@ -762,14 +949,36 @@
         "StateLastUpdatedDateTime": datetime,
         "TrustStateReason": str,
         "SelectiveAuth": SelectiveAuthType,
     },
     total=False,
 )
 
+_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
+    "_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "UpdateType": Literal["OS"],
+    },
+)
+_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
+    "_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
+    {
+        "RegionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef(
+    _RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
+    _OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeUpdateDirectoryRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeUpdateDirectoryRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "UpdateType": Literal["OS"],
     },
 )
@@ -957,14 +1166,34 @@
         "AddedDateTime": datetime,
         "IpRouteStatusReason": str,
         "Description": str,
     },
     total=False,
 )
 
+_RequiredListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "_RequiredListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "_OptionalListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCertificatesRequestListCertificatesPaginateTypeDef(
+    _RequiredListCertificatesRequestListCertificatesPaginateTypeDef,
+    _OptionalListCertificatesRequestListCertificatesPaginateTypeDef,
+):
+    pass
+
 _RequiredListCertificatesRequestRequestTypeDef = TypedDict(
     "_RequiredListCertificatesRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListCertificatesRequestRequestTypeDef = TypedDict(
@@ -977,14 +1206,34 @@
 )
 
 class ListCertificatesRequestRequestTypeDef(
     _RequiredListCertificatesRequestRequestTypeDef, _OptionalListCertificatesRequestRequestTypeDef
 ):
     pass
 
+_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListIpRoutesRequestListIpRoutesPaginateTypeDef(
+    _RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef,
+    _OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef,
+):
+    pass
+
 _RequiredListIpRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredListIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListIpRoutesRequestRequestTypeDef = TypedDict(
@@ -997,14 +1246,23 @@
 )
 
 class ListIpRoutesRequestRequestTypeDef(
     _RequiredListIpRoutesRequestRequestTypeDef, _OptionalListIpRoutesRequestRequestTypeDef
 ):
     pass
 
+ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef = TypedDict(
+    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLogSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListLogSubscriptionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "NextToken": str,
         "Limit": int,
     },
@@ -1017,14 +1275,34 @@
         "DirectoryId": str,
         "LogGroupName": str,
         "SubscriptionCreatedDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
+    {
+        "DirectoryId": str,
+    },
+)
+_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef(
+    _RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
+    _OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemaExtensionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemaExtensionsRequestRequestTypeDef",
     {
         "DirectoryId": str,
     },
 )
 _OptionalListSchemaExtensionsRequestRequestTypeDef = TypedDict(
@@ -1052,14 +1330,34 @@
         "SchemaExtensionStatusReason": str,
         "StartDateTime": datetime,
         "EndDateTime": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceId": str,
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
         "ResourceId": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -1081,14 +1379,32 @@
     "OSUpdateSettingsTypeDef",
     {
         "OSVersion": OSVersionType,
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
+RegisterCertificateResultTypeDef = TypedDict(
+    "RegisterCertificateResultTypeDef",
+    {
+        "CertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterEventTopicRequestRequestTypeDef = TypedDict(
     "RegisterEventTopicRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "TopicName": str,
     },
 )
@@ -1096,14 +1412,22 @@
 RejectSharedDirectoryRequestRequestTypeDef = TypedDict(
     "RejectSharedDirectoryRequestRequestTypeDef",
     {
         "SharedDirectoryId": str,
     },
 )
 
+RejectSharedDirectoryResultTypeDef = TypedDict(
+    "RejectSharedDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveIpRoutesRequestRequestTypeDef = TypedDict(
     "RemoveIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CidrIps": Sequence[str],
     },
 )
@@ -1128,14 +1452,25 @@
     {
         "DirectoryId": str,
         "UserName": str,
         "NewPassword": str,
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
 RestoreFromSnapshotRequestRequestTypeDef = TypedDict(
     "RestoreFromSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 
@@ -1151,32 +1486,56 @@
     "ShareTargetTypeDef",
     {
         "Id": str,
         "Type": Literal["ACCOUNT"],
     },
 )
 
+ShareDirectoryResultTypeDef = TypedDict(
+    "ShareDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartSchemaExtensionRequestRequestTypeDef = TypedDict(
     "StartSchemaExtensionRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "CreateSnapshotBeforeSchemaExtension": bool,
         "LdifContent": str,
         "Description": str,
     },
 )
 
+StartSchemaExtensionResultTypeDef = TypedDict(
+    "StartSchemaExtensionResultTypeDef",
+    {
+        "SchemaExtensionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnshareTargetTypeDef = TypedDict(
     "UnshareTargetTypeDef",
     {
         "Id": str,
         "Type": Literal["ACCOUNT"],
     },
 )
 
+UnshareDirectoryResultTypeDef = TypedDict(
+    "UnshareDirectoryResultTypeDef",
+    {
+        "SharedDirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateConditionalForwarderRequestRequestTypeDef = TypedDict(
     "UpdateConditionalForwarderRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "RemoteDomainName": str,
         "DnsIpAddrs": Sequence[str],
     },
@@ -1186,14 +1545,22 @@
     "UpdateNumberOfDomainControllersRequestRequestTypeDef",
     {
         "DirectoryId": str,
         "DesiredNumber": int,
     },
 )
 
+UpdateSettingsResultTypeDef = TypedDict(
+    "UpdateSettingsResultTypeDef",
+    {
+        "DirectoryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateTrustRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTrustRequestRequestTypeDef",
     {
         "TrustId": str,
     },
 )
 _OptionalUpdateTrustRequestRequestTypeDef = TypedDict(
@@ -1205,173 +1572,52 @@
 )
 
 class UpdateTrustRequestRequestTypeDef(
     _RequiredUpdateTrustRequestRequestTypeDef, _OptionalUpdateTrustRequestRequestTypeDef
 ):
     pass
 
-VerifyTrustRequestRequestTypeDef = TypedDict(
-    "VerifyTrustRequestRequestTypeDef",
-    {
-        "TrustId": str,
-    },
-)
-
-ConnectDirectoryResultTypeDef = TypedDict(
-    "ConnectDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAliasResultTypeDef = TypedDict(
-    "CreateAliasResultTypeDef",
-    {
-        "DirectoryId": str,
-        "Alias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDirectoryResultTypeDef = TypedDict(
-    "CreateDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMicrosoftADResultTypeDef = TypedDict(
-    "CreateMicrosoftADResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSnapshotResultTypeDef = TypedDict(
-    "CreateSnapshotResultTypeDef",
-    {
-        "SnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTrustResultTypeDef = TypedDict(
-    "CreateTrustResultTypeDef",
-    {
-        "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDirectoryResultTypeDef = TypedDict(
-    "DeleteDirectoryResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSnapshotResultTypeDef = TypedDict(
-    "DeleteSnapshotResultTypeDef",
-    {
-        "SnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteTrustResultTypeDef = TypedDict(
-    "DeleteTrustResultTypeDef",
+UpdateTrustResultTypeDef = TypedDict(
+    "UpdateTrustResultTypeDef",
     {
+        "RequestId": str,
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateResultTypeDef = TypedDict(
-    "RegisterCertificateResultTypeDef",
-    {
-        "CertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RejectSharedDirectoryResultTypeDef = TypedDict(
-    "RejectSharedDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ShareDirectoryResultTypeDef = TypedDict(
-    "ShareDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSchemaExtensionResultTypeDef = TypedDict(
-    "StartSchemaExtensionResultTypeDef",
-    {
-        "SchemaExtensionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnshareDirectoryResultTypeDef = TypedDict(
-    "UnshareDirectoryResultTypeDef",
-    {
-        "SharedDirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateSettingsResultTypeDef = TypedDict(
-    "UpdateSettingsResultTypeDef",
-    {
-        "DirectoryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTrustResultTypeDef = TypedDict(
-    "UpdateTrustResultTypeDef",
+VerifyTrustRequestRequestTypeDef = TypedDict(
+    "VerifyTrustRequestRequestTypeDef",
     {
-        "RequestId": str,
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
 VerifyTrustResultTypeDef = TypedDict(
     "VerifyTrustResultTypeDef",
     {
         "TrustId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptSharedDirectoryResultTypeDef = TypedDict(
     "AcceptSharedDirectoryResultTypeDef",
     {
         "SharedDirectory": SharedDirectoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSharedDirectoriesResultTypeDef = TypedDict(
     "DescribeSharedDirectoriesResultTypeDef",
     {
         "SharedDirectories": List[SharedDirectoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddIpRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredAddIpRoutesRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -1473,15 +1719,15 @@
     pass
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComputerTypeDef = TypedDict(
     "ComputerTypeDef",
     {
         "ComputerId": str,
@@ -1514,15 +1760,15 @@
     pass
 
 ListCertificatesResultTypeDef = TypedDict(
     "ListCertificatesResultTypeDef",
     {
         "NextToken": str,
         "CertificatesInfo": List[CertificateInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateTypeDef = TypedDict(
     "CertificateTypeDef",
     {
         "CertificateId": str,
@@ -1560,23 +1806,23 @@
     pass
 
 DescribeClientAuthenticationSettingsResultTypeDef = TypedDict(
     "DescribeClientAuthenticationSettingsResultTypeDef",
     {
         "ClientAuthenticationSettingsInfo": List[ClientAuthenticationSettingInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConditionalForwardersResultTypeDef = TypedDict(
     "DescribeConditionalForwardersResultTypeDef",
     {
         "ConditionalForwarders": List[ConditionalForwarderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConnectDirectoryRequestRequestTypeDef = TypedDict(
     "_RequiredConnectDirectoryRequestRequestTypeDef",
     {
         "Name": str,
@@ -1596,310 +1842,65 @@
 )
 
 class ConnectDirectoryRequestRequestTypeDef(
     _RequiredConnectDirectoryRequestRequestTypeDef, _OptionalConnectDirectoryRequestRequestTypeDef
 ):
     pass
 
-_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef",
-    {
-        "Type": ClientAuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef(
-    _RequiredDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-    _OptionalDescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-):
-    pass
-
-DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef = TypedDict(
-    "DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef",
-    {
-        "DirectoryIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef",
-    {
-        "DomainControllerIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef(
-    _RequiredDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-    _OptionalDescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef",
-    {
-        "Type": Literal["Client"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef(
-    _RequiredDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-    _OptionalDescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef",
-    {
-        "RegionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeRegionsRequestDescribeRegionsPaginateTypeDef(
-    _RequiredDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-    _OptionalDescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    {
-        "OwnerDirectoryId": str,
-    },
-)
-_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef",
-    {
-        "SharedDirectoryIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef(
-    _RequiredDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-    _OptionalDescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-):
-    pass
-
-DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "SnapshotIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeTrustsRequestDescribeTrustsPaginateTypeDef = TypedDict(
-    "DescribeTrustsRequestDescribeTrustsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "TrustIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
-    "_RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "UpdateType": Literal["OS"],
-    },
-)
-_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef = TypedDict(
-    "_OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef",
-    {
-        "RegionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef(
-    _RequiredDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-    _OptionalDescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "_RequiredListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "_OptionalListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCertificatesRequestListCertificatesPaginateTypeDef(
-    _RequiredListCertificatesRequestListCertificatesPaginateTypeDef,
-    _OptionalListCertificatesRequestListCertificatesPaginateTypeDef,
-):
-    pass
-
-_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListIpRoutesRequestListIpRoutesPaginateTypeDef(
-    _RequiredListIpRoutesRequestListIpRoutesPaginateTypeDef,
-    _OptionalListIpRoutesRequestListIpRoutesPaginateTypeDef,
-):
-    pass
-
-ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef = TypedDict(
-    "ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    {
-        "DirectoryId": str,
-    },
-)
-_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef(
-    _RequiredListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-    _OptionalListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceId": str,
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
 DescribeDomainControllersResultTypeDef = TypedDict(
     "DescribeDomainControllersResultTypeDef",
     {
         "DomainControllers": List[DomainControllerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventTopicsResultTypeDef = TypedDict(
     "DescribeEventTopicsResultTypeDef",
     {
         "EventTopics": List[EventTopicTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLDAPSSettingsResultTypeDef = TypedDict(
     "DescribeLDAPSSettingsResultTypeDef",
     {
         "LDAPSSettingsInfo": List[LDAPSSettingInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSettingsResultTypeDef = TypedDict(
     "DescribeSettingsResultTypeDef",
     {
         "DirectoryId": str,
         "SettingEntries": List[SettingEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResultTypeDef = TypedDict(
     "DescribeSnapshotsResultTypeDef",
     {
         "Snapshots": List[SnapshotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustsResultTypeDef = TypedDict(
     "DescribeTrustsResultTypeDef",
     {
         "Trusts": List[TrustTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableRadiusRequestRequestTypeDef = TypedDict(
     "EnableRadiusRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -1928,50 +1929,50 @@
     },
 )
 
 GetDirectoryLimitsResultTypeDef = TypedDict(
     "GetDirectoryLimitsResultTypeDef",
     {
         "DirectoryLimits": DirectoryLimitsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotLimitsResultTypeDef = TypedDict(
     "GetSnapshotLimitsResultTypeDef",
     {
         "SnapshotLimits": SnapshotLimitsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIpRoutesResultTypeDef = TypedDict(
     "ListIpRoutesResultTypeDef",
     {
         "IpRoutesInfo": List[IpRouteInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLogSubscriptionsResultTypeDef = TypedDict(
     "ListLogSubscriptionsResultTypeDef",
     {
         "LogSubscriptions": List[LogSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaExtensionsResultTypeDef = TypedDict(
     "ListSchemaExtensionsResultTypeDef",
     {
         "SchemaExtensionsInfo": List[SchemaExtensionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDirectorySetupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDirectorySetupRequestRequestTypeDef",
     {
         "DirectoryId": str,
@@ -2039,31 +2040,31 @@
 )
 
 DescribeRegionsResultTypeDef = TypedDict(
     "DescribeRegionsResultTypeDef",
     {
         "RegionsDescription": List[RegionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComputerResultTypeDef = TypedDict(
     "CreateComputerResultTypeDef",
     {
         "Computer": ComputerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResultTypeDef = TypedDict(
     "DescribeCertificateResultTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DirectoryDescriptionTypeDef = TypedDict(
     "DirectoryDescriptionTypeDef",
     {
         "DirectoryId": str,
@@ -2112,19 +2113,19 @@
 )
 
 DescribeDirectoriesResultTypeDef = TypedDict(
     "DescribeDirectoriesResultTypeDef",
     {
         "DirectoryDescriptions": List[DirectoryDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUpdateDirectoryResultTypeDef = TypedDict(
     "DescribeUpdateDirectoryResultTypeDef",
     {
         "UpdateActivities": List[UpdateInfoEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/PKG-INFO` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ds
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DirectoryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DirectoryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ds"></a>
 
 # types-aiobotocore-ds
 
 [![PyPI - types-aiobotocore-ds](https://img.shields.io/pypi/v/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ds?color=blue)](https://pypistats.org/packages/types-aiobotocore-ds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectoryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
+[aiobotocore.DirectoryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ds.html#DirectoryService)
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
 [types-aiobotocore-ds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -408,57 +408,73 @@
 
 `types_aiobotocore_ds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ds.type_defs import (
     AcceptSharedDirectoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     SharedDirectoryTypeDef,
     IpRouteTypeDef,
     DirectoryVpcSettingsTypeDef,
     TagTypeDef,
     AttributeTypeDef,
     CancelSchemaExtensionRequestRequestTypeDef,
     CertificateInfoTypeDef,
     ClientCertAuthSettingsTypeDef,
     ClientAuthenticationSettingInfoTypeDef,
     ConditionalForwarderTypeDef,
     DirectoryConnectSettingsTypeDef,
+    ConnectDirectoryResultTypeDef,
     CreateAliasRequestRequestTypeDef,
+    CreateAliasResultTypeDef,
     CreateConditionalForwarderRequestRequestTypeDef,
+    CreateDirectoryResultTypeDef,
     CreateLogSubscriptionRequestRequestTypeDef,
+    CreateMicrosoftADResultTypeDef,
     CreateSnapshotRequestRequestTypeDef,
+    CreateSnapshotResultTypeDef,
     CreateTrustRequestRequestTypeDef,
+    CreateTrustResultTypeDef,
     DeleteConditionalForwarderRequestRequestTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResultTypeDef,
     DeleteLogSubscriptionRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResultTypeDef,
     DeleteTrustRequestRequestTypeDef,
+    DeleteTrustResultTypeDef,
     DeregisterCertificateRequestRequestTypeDef,
     DeregisterEventTopicRequestRequestTypeDef,
     DescribeCertificateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
     DescribeClientAuthenticationSettingsRequestRequestTypeDef,
     DescribeConditionalForwardersRequestRequestTypeDef,
+    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
     DescribeDirectoriesRequestRequestTypeDef,
+    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
     DescribeDomainControllersRequestRequestTypeDef,
     DomainControllerTypeDef,
     DescribeEventTopicsRequestRequestTypeDef,
     EventTopicTypeDef,
+    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
     DescribeLDAPSSettingsRequestRequestTypeDef,
     LDAPSSettingInfoTypeDef,
+    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
     DescribeRegionsRequestRequestTypeDef,
     DescribeSettingsRequestRequestTypeDef,
     SettingEntryTypeDef,
+    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
     DescribeSharedDirectoriesRequestRequestTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     SnapshotTypeDef,
+    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
     DescribeTrustsRequestRequestTypeDef,
     TrustTypeDef,
+    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
     DescribeUpdateDirectoryRequestRequestTypeDef,
     DirectoryConnectSettingsDescriptionTypeDef,
     DirectoryVpcSettingsDescriptionTypeDef,
     RadiusSettingsTypeDef,
     RegionsInfoTypeDef,
     DirectoryLimitsTypeDef,
     DisableClientAuthenticationRequestRequestTypeDef,
@@ -467,53 +483,51 @@
     DisableSsoRequestRequestTypeDef,
     EnableClientAuthenticationRequestRequestTypeDef,
     EnableLDAPSRequestRequestTypeDef,
     EnableSsoRequestRequestTypeDef,
     GetSnapshotLimitsRequestRequestTypeDef,
     SnapshotLimitsTypeDef,
     IpRouteInfoTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
     ListIpRoutesRequestRequestTypeDef,
+    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
     ListLogSubscriptionsRequestRequestTypeDef,
     LogSubscriptionTypeDef,
+    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
     ListSchemaExtensionsRequestRequestTypeDef,
     SchemaExtensionInfoTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OSUpdateSettingsTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterCertificateResultTypeDef,
     RegisterEventTopicRequestRequestTypeDef,
     RejectSharedDirectoryRequestRequestTypeDef,
+    RejectSharedDirectoryResultTypeDef,
     RemoveIpRoutesRequestRequestTypeDef,
     RemoveRegionRequestRequestTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     SettingTypeDef,
     ShareTargetTypeDef,
+    ShareDirectoryResultTypeDef,
     StartSchemaExtensionRequestRequestTypeDef,
+    StartSchemaExtensionResultTypeDef,
     UnshareTargetTypeDef,
+    UnshareDirectoryResultTypeDef,
     UpdateConditionalForwarderRequestRequestTypeDef,
     UpdateNumberOfDomainControllersRequestRequestTypeDef,
-    UpdateTrustRequestRequestTypeDef,
-    VerifyTrustRequestRequestTypeDef,
-    ConnectDirectoryResultTypeDef,
-    CreateAliasResultTypeDef,
-    CreateDirectoryResultTypeDef,
-    CreateMicrosoftADResultTypeDef,
-    CreateSnapshotResultTypeDef,
-    CreateTrustResultTypeDef,
-    DeleteDirectoryResultTypeDef,
-    DeleteSnapshotResultTypeDef,
-    DeleteTrustResultTypeDef,
-    RegisterCertificateResultTypeDef,
-    RejectSharedDirectoryResultTypeDef,
-    ShareDirectoryResultTypeDef,
-    StartSchemaExtensionResultTypeDef,
-    UnshareDirectoryResultTypeDef,
     UpdateSettingsResultTypeDef,
+    UpdateTrustRequestRequestTypeDef,
     UpdateTrustResultTypeDef,
+    VerifyTrustRequestRequestTypeDef,
     VerifyTrustResultTypeDef,
     AcceptSharedDirectoryResultTypeDef,
     DescribeSharedDirectoriesResultTypeDef,
     AddIpRoutesRequestRequestTypeDef,
     AddRegionRequestRequestTypeDef,
     RegionDescriptionTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
@@ -524,28 +538,14 @@
     CreateComputerRequestRequestTypeDef,
     ListCertificatesResultTypeDef,
     CertificateTypeDef,
     RegisterCertificateRequestRequestTypeDef,
     DescribeClientAuthenticationSettingsResultTypeDef,
     DescribeConditionalForwardersResultTypeDef,
     ConnectDirectoryRequestRequestTypeDef,
-    DescribeClientAuthenticationSettingsRequestDescribeClientAuthenticationSettingsPaginateTypeDef,
-    DescribeDirectoriesRequestDescribeDirectoriesPaginateTypeDef,
-    DescribeDomainControllersRequestDescribeDomainControllersPaginateTypeDef,
-    DescribeLDAPSSettingsRequestDescribeLDAPSSettingsPaginateTypeDef,
-    DescribeRegionsRequestDescribeRegionsPaginateTypeDef,
-    DescribeSharedDirectoriesRequestDescribeSharedDirectoriesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeTrustsRequestDescribeTrustsPaginateTypeDef,
-    DescribeUpdateDirectoryRequestDescribeUpdateDirectoryPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListIpRoutesRequestListIpRoutesPaginateTypeDef,
-    ListLogSubscriptionsRequestListLogSubscriptionsPaginateTypeDef,
-    ListSchemaExtensionsRequestListSchemaExtensionsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeDomainControllersResultTypeDef,
     DescribeEventTopicsResultTypeDef,
     DescribeLDAPSSettingsResultTypeDef,
     DescribeSettingsResultTypeDef,
     DescribeSnapshotsResultTypeDef,
     DescribeTrustsResultTypeDef,
     EnableRadiusRequestRequestTypeDef,
@@ -578,43 +578,43 @@
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

### Comparing `types-aiobotocore-ds-2.5.0.post1/types_aiobotocore_ds.egg-info/SOURCES.txt` & `types-aiobotocore-ds-2.5.1/types_aiobotocore_ds.egg-info/SOURCES.txt`

 * *Files identical despite different names*

