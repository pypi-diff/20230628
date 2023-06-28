# Comparing `tmp/types-aiobotocore-license-manager-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-license-manager-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-license-manager-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:54 2023, max compression
+gzip compressed data, was "types-aiobotocore-license-manager-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-license-manager-2.5.0.post1.tar` & `types-aiobotocore-license-manager-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.143371 types-aiobotocore-license-manager-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20565 2023-03-11 12:26:54.143371 types-aiobotocore-license-manager-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18963 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:54.143371 types-aiobotocore-license-manager-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2179 2023-03-11 12:17:31.000000 types-aiobotocore-license-manager-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.135371 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/
--rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43024 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    42960 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12001 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11999 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8051 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8043 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    54800 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    54729 2023-03-11 12:17:34.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:32.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.143371 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20565 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.290166 types-aiobotocore-license-manager-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20631 2023-06-28 01:43:45.286166 types-aiobotocore-license-manager-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19035 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.290166 types-aiobotocore-license-manager-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.278166 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/
+-rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43066 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43002 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12392 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12390 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7941 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7934 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    55171 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55100 2023-06-28 01:34:14.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:13.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.286166 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20631 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/LICENSE` & `types-aiobotocore-license-manager-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/PKG-INFO` & `types-aiobotocore-license-manager-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager"></a>
 
 # types-aiobotocore-license-manager
 
 [![PyPI - types-aiobotocore-license-manager](https://img.shields.io/pypi/v/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
+[aiobotocore.LicenseManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
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
 [types-aiobotocore-license-manager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,14 +312,15 @@
 ### Literals
 
 `types_aiobotocore_license_manager.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_license_manager.literals import (
+    ActivationOverrideBehaviorType,
     AllowedOperationType,
     CheckoutTypeType,
     DigitalSignatureMethodType,
     EntitlementDataUnitType,
     EntitlementUnitType,
     GrantStatusType,
     InventoryFilterConditionType,
@@ -343,146 +344,147 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AllowedOperationType) -> bool:
+def check_value(value: ActivationOverrideBehaviorType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_license_manager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_license_manager.type_defs import (
     AcceptGrantRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptGrantResponseTypeDef,
     AutomatedDiscoveryInformationTypeDef,
     BorrowConfigurationTypeDef,
     CheckInLicenseRequestRequestTypeDef,
     EntitlementDataTypeDef,
     MetadataTypeDef,
     ConsumedLicenseSummaryTypeDef,
     ProvisionalConfigurationTypeDef,
     CreateGrantRequestRequestTypeDef,
-    CreateGrantVersionRequestRequestTypeDef,
+    CreateGrantResponseTypeDef,
+    OptionsTypeDef,
+    CreateGrantVersionResponseTypeDef,
     TagTypeDef,
+    CreateLicenseConfigurationResponseTypeDef,
     LicenseConversionContextTypeDef,
+    CreateLicenseConversionTaskForResourceResponseTypeDef,
     ReportContextTypeDef,
     ReportFrequencyTypeDef,
+    CreateLicenseManagerReportGeneratorResponseTypeDef,
     DatetimeRangeTypeDef,
     EntitlementTypeDef,
     IssuerTypeDef,
+    CreateLicenseResponseTypeDef,
+    CreateLicenseVersionResponseTypeDef,
     CreateTokenRequestRequestTypeDef,
+    CreateTokenResponseTypeDef,
     DeleteGrantRequestRequestTypeDef,
+    DeleteGrantResponseTypeDef,
     DeleteLicenseConfigurationRequestRequestTypeDef,
     DeleteLicenseManagerReportGeneratorRequestRequestTypeDef,
     DeleteLicenseRequestRequestTypeDef,
+    DeleteLicenseResponseTypeDef,
     DeleteTokenRequestRequestTypeDef,
     EntitlementUsageTypeDef,
     ExtendLicenseConsumptionRequestRequestTypeDef,
+    ExtendLicenseConsumptionResponseTypeDef,
     FilterTypeDef,
     GetAccessTokenRequestRequestTypeDef,
+    GetAccessTokenResponseTypeDef,
     GetGrantRequestRequestTypeDef,
-    GrantTypeDef,
     GetLicenseConfigurationRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
     GetLicenseConversionTaskRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorRequestRequestTypeDef,
     GetLicenseRequestRequestTypeDef,
     GetLicenseUsageRequestRequestTypeDef,
     OrganizationConfigurationTypeDef,
     IssuerDetailsTypeDef,
     ReceivedMetadataTypeDef,
     InventoryFilterTypeDef,
     LicenseConfigurationAssociationTypeDef,
     LicenseConfigurationUsageTypeDef,
     LicenseSpecificationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
     ListAssociationsForLicenseConfigurationRequestRequestTypeDef,
     ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
+    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
     ListLicenseSpecificationsForResourceRequestRequestTypeDef,
     ListLicenseVersionsRequestRequestTypeDef,
     ResourceInventoryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TokenDataTypeDef,
+    PaginatorConfigTypeDef,
     ProductInformationFilterTypeDef,
     RejectGrantRequestRequestTypeDef,
+    RejectGrantResponseTypeDef,
     S3LocationTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceptGrantResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    CreateGrantVersionResponseTypeDef,
-    CreateLicenseConfigurationResponseTypeDef,
-    CreateLicenseConversionTaskForResourceResponseTypeDef,
-    CreateLicenseManagerReportGeneratorResponseTypeDef,
-    CreateLicenseResponseTypeDef,
-    CreateLicenseVersionResponseTypeDef,
-    CreateTokenResponseTypeDef,
-    DeleteGrantResponseTypeDef,
-    DeleteLicenseResponseTypeDef,
-    ExtendLicenseConsumptionResponseTypeDef,
-    GetAccessTokenResponseTypeDef,
-    RejectGrantResponseTypeDef,
     CheckoutLicenseRequestRequestTypeDef,
     CheckoutLicenseResponseTypeDef,
     CheckoutBorrowLicenseRequestRequestTypeDef,
     CheckoutBorrowLicenseResponseTypeDef,
     LicenseOperationFailureTypeDef,
     ConsumptionConfigurationTypeDef,
+    CreateGrantVersionRequestRequestTypeDef,
+    GrantTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateLicenseConversionTaskForResourceRequestRequestTypeDef,
     GetLicenseConversionTaskResponseTypeDef,
     LicenseConversionTaskTypeDef,
     CreateLicenseManagerReportGeneratorRequestRequestTypeDef,
     UpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
     LicenseUsageTypeDef,
     ListDistributedGrantsRequestRequestTypeDef,
+    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
     ListLicenseConfigurationsRequestRequestTypeDef,
     ListLicenseConversionTasksRequestRequestTypeDef,
     ListLicenseManagerReportGeneratorsRequestRequestTypeDef,
     ListLicensesRequestRequestTypeDef,
     ListReceivedGrantsForOrganizationRequestRequestTypeDef,
     ListReceivedGrantsRequestRequestTypeDef,
     ListReceivedLicensesForOrganizationRequestRequestTypeDef,
     ListReceivedLicensesRequestRequestTypeDef,
     ListTokensRequestRequestTypeDef,
+    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListUsageForLicenseConfigurationRequestRequestTypeDef,
-    GetGrantResponseTypeDef,
-    ListDistributedGrantsResponseTypeDef,
-    ListReceivedGrantsForOrganizationResponseTypeDef,
-    ListReceivedGrantsResponseTypeDef,
     GetServiceSettingsResponseTypeDef,
     UpdateServiceSettingsRequestRequestTypeDef,
+    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
     ListResourceInventoryRequestRequestTypeDef,
     ListAssociationsForLicenseConfigurationResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     ListLicenseSpecificationsForResourceResponseTypeDef,
     UpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
-    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
-    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
-    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListTokensResponseTypeDef,
     ProductInformationTypeDef,
     ReportGeneratorTypeDef,
     ListFailuresForLicenseConfigurationOperationsResponseTypeDef,
     CreateLicenseRequestRequestTypeDef,
     CreateLicenseVersionRequestRequestTypeDef,
     GrantedLicenseTypeDef,
     LicenseTypeDef,
+    GetGrantResponseTypeDef,
+    ListDistributedGrantsResponseTypeDef,
+    ListReceivedGrantsForOrganizationResponseTypeDef,
+    ListReceivedGrantsResponseTypeDef,
     ListLicenseConversionTasksResponseTypeDef,
     GetLicenseUsageResponseTypeDef,
     CreateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseConfigurationResponseTypeDef,
     LicenseConfigurationTypeDef,
     UpdateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorResponseTypeDef,
@@ -503,43 +505,43 @@
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/README.md` & `types-aiobotocore-license-manager-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-license-manager"></a>
 
 # types-aiobotocore-license-manager
 
 [![PyPI - types-aiobotocore-license-manager](https://img.shields.io/pypi/v/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
+[aiobotocore.LicenseManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
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
 [types-aiobotocore-license-manager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -279,14 +279,15 @@
 ### Literals
 
 `types_aiobotocore_license_manager.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_license_manager.literals import (
+    ActivationOverrideBehaviorType,
     AllowedOperationType,
     CheckoutTypeType,
     DigitalSignatureMethodType,
     EntitlementDataUnitType,
     EntitlementUnitType,
     GrantStatusType,
     InventoryFilterConditionType,
@@ -310,146 +311,147 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AllowedOperationType) -> bool:
+def check_value(value: ActivationOverrideBehaviorType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_license_manager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_license_manager.type_defs import (
     AcceptGrantRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptGrantResponseTypeDef,
     AutomatedDiscoveryInformationTypeDef,
     BorrowConfigurationTypeDef,
     CheckInLicenseRequestRequestTypeDef,
     EntitlementDataTypeDef,
     MetadataTypeDef,
     ConsumedLicenseSummaryTypeDef,
     ProvisionalConfigurationTypeDef,
     CreateGrantRequestRequestTypeDef,
-    CreateGrantVersionRequestRequestTypeDef,
+    CreateGrantResponseTypeDef,
+    OptionsTypeDef,
+    CreateGrantVersionResponseTypeDef,
     TagTypeDef,
+    CreateLicenseConfigurationResponseTypeDef,
     LicenseConversionContextTypeDef,
+    CreateLicenseConversionTaskForResourceResponseTypeDef,
     ReportContextTypeDef,
     ReportFrequencyTypeDef,
+    CreateLicenseManagerReportGeneratorResponseTypeDef,
     DatetimeRangeTypeDef,
     EntitlementTypeDef,
     IssuerTypeDef,
+    CreateLicenseResponseTypeDef,
+    CreateLicenseVersionResponseTypeDef,
     CreateTokenRequestRequestTypeDef,
+    CreateTokenResponseTypeDef,
     DeleteGrantRequestRequestTypeDef,
+    DeleteGrantResponseTypeDef,
     DeleteLicenseConfigurationRequestRequestTypeDef,
     DeleteLicenseManagerReportGeneratorRequestRequestTypeDef,
     DeleteLicenseRequestRequestTypeDef,
+    DeleteLicenseResponseTypeDef,
     DeleteTokenRequestRequestTypeDef,
     EntitlementUsageTypeDef,
     ExtendLicenseConsumptionRequestRequestTypeDef,
+    ExtendLicenseConsumptionResponseTypeDef,
     FilterTypeDef,
     GetAccessTokenRequestRequestTypeDef,
+    GetAccessTokenResponseTypeDef,
     GetGrantRequestRequestTypeDef,
-    GrantTypeDef,
     GetLicenseConfigurationRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
     GetLicenseConversionTaskRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorRequestRequestTypeDef,
     GetLicenseRequestRequestTypeDef,
     GetLicenseUsageRequestRequestTypeDef,
     OrganizationConfigurationTypeDef,
     IssuerDetailsTypeDef,
     ReceivedMetadataTypeDef,
     InventoryFilterTypeDef,
     LicenseConfigurationAssociationTypeDef,
     LicenseConfigurationUsageTypeDef,
     LicenseSpecificationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
     ListAssociationsForLicenseConfigurationRequestRequestTypeDef,
     ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
+    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
     ListLicenseSpecificationsForResourceRequestRequestTypeDef,
     ListLicenseVersionsRequestRequestTypeDef,
     ResourceInventoryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TokenDataTypeDef,
+    PaginatorConfigTypeDef,
     ProductInformationFilterTypeDef,
     RejectGrantRequestRequestTypeDef,
+    RejectGrantResponseTypeDef,
     S3LocationTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceptGrantResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    CreateGrantVersionResponseTypeDef,
-    CreateLicenseConfigurationResponseTypeDef,
-    CreateLicenseConversionTaskForResourceResponseTypeDef,
-    CreateLicenseManagerReportGeneratorResponseTypeDef,
-    CreateLicenseResponseTypeDef,
-    CreateLicenseVersionResponseTypeDef,
-    CreateTokenResponseTypeDef,
-    DeleteGrantResponseTypeDef,
-    DeleteLicenseResponseTypeDef,
-    ExtendLicenseConsumptionResponseTypeDef,
-    GetAccessTokenResponseTypeDef,
-    RejectGrantResponseTypeDef,
     CheckoutLicenseRequestRequestTypeDef,
     CheckoutLicenseResponseTypeDef,
     CheckoutBorrowLicenseRequestRequestTypeDef,
     CheckoutBorrowLicenseResponseTypeDef,
     LicenseOperationFailureTypeDef,
     ConsumptionConfigurationTypeDef,
+    CreateGrantVersionRequestRequestTypeDef,
+    GrantTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateLicenseConversionTaskForResourceRequestRequestTypeDef,
     GetLicenseConversionTaskResponseTypeDef,
     LicenseConversionTaskTypeDef,
     CreateLicenseManagerReportGeneratorRequestRequestTypeDef,
     UpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
     LicenseUsageTypeDef,
     ListDistributedGrantsRequestRequestTypeDef,
+    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
     ListLicenseConfigurationsRequestRequestTypeDef,
     ListLicenseConversionTasksRequestRequestTypeDef,
     ListLicenseManagerReportGeneratorsRequestRequestTypeDef,
     ListLicensesRequestRequestTypeDef,
     ListReceivedGrantsForOrganizationRequestRequestTypeDef,
     ListReceivedGrantsRequestRequestTypeDef,
     ListReceivedLicensesForOrganizationRequestRequestTypeDef,
     ListReceivedLicensesRequestRequestTypeDef,
     ListTokensRequestRequestTypeDef,
+    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListUsageForLicenseConfigurationRequestRequestTypeDef,
-    GetGrantResponseTypeDef,
-    ListDistributedGrantsResponseTypeDef,
-    ListReceivedGrantsForOrganizationResponseTypeDef,
-    ListReceivedGrantsResponseTypeDef,
     GetServiceSettingsResponseTypeDef,
     UpdateServiceSettingsRequestRequestTypeDef,
+    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
     ListResourceInventoryRequestRequestTypeDef,
     ListAssociationsForLicenseConfigurationResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     ListLicenseSpecificationsForResourceResponseTypeDef,
     UpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
-    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
-    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
-    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListTokensResponseTypeDef,
     ProductInformationTypeDef,
     ReportGeneratorTypeDef,
     ListFailuresForLicenseConfigurationOperationsResponseTypeDef,
     CreateLicenseRequestRequestTypeDef,
     CreateLicenseVersionRequestRequestTypeDef,
     GrantedLicenseTypeDef,
     LicenseTypeDef,
+    GetGrantResponseTypeDef,
+    ListDistributedGrantsResponseTypeDef,
+    ListReceivedGrantsForOrganizationResponseTypeDef,
+    ListReceivedGrantsResponseTypeDef,
     ListLicenseConversionTasksResponseTypeDef,
     GetLicenseUsageResponseTypeDef,
     CreateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseConfigurationResponseTypeDef,
     LicenseConfigurationTypeDef,
     UpdateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorResponseTypeDef,
@@ -470,43 +472,43 @@
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/setup.py` & `types-aiobotocore-license-manager-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-license-manager.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-license-manager",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_license_manager"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LicenseManager 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LicenseManager 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/"
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__init__.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__init__.pyi` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/__main__.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LicenseManager 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LicenseManager 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager\nOther"
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/client.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -82,14 +82,15 @@
     ListReceivedLicensesForOrganizationResponseTypeDef,
     ListReceivedLicensesResponseTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTokensResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     MetadataTypeDef,
+    OptionsTypeDef,
     OrganizationConfigurationTypeDef,
     ProductInformationTypeDef,
     RejectGrantResponseTypeDef,
     ReportContextTypeDef,
     ReportFrequencyTypeDef,
     TagTypeDef,
 )
@@ -240,15 +241,16 @@
         *,
         ClientToken: str,
         GrantArn: str,
         GrantName: str = ...,
         AllowedOperations: Sequence[AllowedOperationType] = ...,
         Status: GrantStatusType = ...,
         StatusReason: str = ...,
-        SourceVersion: str = ...
+        SourceVersion: str = ...,
+        Options: OptionsTypeDef = ...
     ) -> CreateGrantVersionResponseTypeDef:
         """
         Creates a new version of the specified grant.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Client.create_grant_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/client/#create_grant_version)
         """
@@ -620,15 +622,15 @@
         *,
         GrantArns: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListReceivedGrantsResponseTypeDef:
         """
-        Lists grants that are received but not accepted.
+        Lists grants that are received.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Client.list_received_grants)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/client/#list_received_grants)
         """
 
     async def list_received_grants_for_organization(
         self,
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/client.pyi` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -82,14 +82,15 @@
     ListReceivedLicensesForOrganizationResponseTypeDef,
     ListReceivedLicensesResponseTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTokensResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     MetadataTypeDef,
+    OptionsTypeDef,
     OrganizationConfigurationTypeDef,
     ProductInformationTypeDef,
     RejectGrantResponseTypeDef,
     ReportContextTypeDef,
     ReportFrequencyTypeDef,
     TagTypeDef,
 )
@@ -228,15 +229,16 @@
         *,
         ClientToken: str,
         GrantArn: str,
         GrantName: str = ...,
         AllowedOperations: Sequence[AllowedOperationType] = ...,
         Status: GrantStatusType = ...,
         StatusReason: str = ...,
-        SourceVersion: str = ...
+        SourceVersion: str = ...,
+        Options: OptionsTypeDef = ...
     ) -> CreateGrantVersionResponseTypeDef:
         """
         Creates a new version of the specified grant.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Client.create_grant_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/client/#create_grant_version)
         """
@@ -577,15 +579,15 @@
         *,
         GrantArns: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListReceivedGrantsResponseTypeDef:
         """
-        Lists grants that are received but not accepted.
+        Lists grants that are received.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Client.list_received_grants)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/client/#list_received_grants)
         """
     async def list_received_grants_for_organization(
         self,
         *,
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/literals.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,28 +2,29 @@
 Type annotations for license-manager service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_license_manager.literals import AllowedOperationType
+    from types_aiobotocore_license_manager.literals import ActivationOverrideBehaviorType
 
-    data: AllowedOperationType = "CheckInLicense"
+    data: ActivationOverrideBehaviorType = "ALL_GRANTS_PERMITTED_BY_ISSUER"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "ActivationOverrideBehaviorType",
     "AllowedOperationType",
     "CheckoutTypeType",
     "DigitalSignatureMethodType",
     "EntitlementDataUnitType",
     "EntitlementUnitType",
     "GrantStatusType",
     "InventoryFilterConditionType",
@@ -47,14 +48,17 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
+ActivationOverrideBehaviorType = Literal[
+    "ALL_GRANTS_PERMITTED_BY_ISSUER", "DISTRIBUTED_GRANTS_ONLY"
+]
 AllowedOperationType = Literal[
     "CheckInLicense",
     "CheckoutBorrowLicense",
     "CheckoutLicense",
     "CreateGrant",
     "CreateToken",
     "ExtendConsumptionLicense",
@@ -230,14 +234,15 @@
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
@@ -316,14 +321,15 @@
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
@@ -334,14 +340,15 @@
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
@@ -377,14 +384,15 @@
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
@@ -403,16 +411,19 @@
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
@@ -496,15 +507,17 @@
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/literals.pyi` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,27 +2,28 @@
 Type annotations for license-manager service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_license_manager.literals import AllowedOperationType
+    from types_aiobotocore_license_manager.literals import ActivationOverrideBehaviorType
 
-    data: AllowedOperationType = "CheckInLicense"
+    data: ActivationOverrideBehaviorType = "ALL_GRANTS_PERMITTED_BY_ISSUER"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "ActivationOverrideBehaviorType",
     "AllowedOperationType",
     "CheckoutTypeType",
     "DigitalSignatureMethodType",
     "EntitlementDataUnitType",
     "EntitlementUnitType",
     "GrantStatusType",
     "InventoryFilterConditionType",
@@ -45,14 +46,17 @@
     "LicenseManagerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+ActivationOverrideBehaviorType = Literal[
+    "ALL_GRANTS_PERMITTED_BY_ISSUER", "DISTRIBUTED_GRANTS_ONLY"
+]
 AllowedOperationType = Literal[
     "CheckInLicense",
     "CheckoutBorrowLicense",
     "CheckoutLicense",
     "CreateGrant",
     "CreateToken",
     "ExtendConsumptionLicense",
@@ -228,14 +232,15 @@
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
@@ -314,14 +319,15 @@
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
@@ -332,14 +338,15 @@
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
@@ -375,14 +382,15 @@
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
@@ -401,16 +409,19 @@
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
@@ -494,15 +505,17 @@
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/paginator.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         list_associations_for_license_configuration_paginator: ListAssociationsForLicenseConfigurationPaginator = client.get_paginator("list_associations_for_license_configuration")
         list_license_configurations_paginator: ListLicenseConfigurationsPaginator = client.get_paginator("list_license_configurations")
         list_license_specifications_for_resource_paginator: ListLicenseSpecificationsForResourcePaginator = client.get_paginator("list_license_specifications_for_resource")
         list_resource_inventory_paginator: ListResourceInventoryPaginator = client.get_paginator("list_resource_inventory")
         list_usage_for_license_configuration_paginator: ListUsageForLicenseConfigurationPaginator = client.get_paginator("list_usage_for_license_configuration")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     InventoryFilterTypeDef,
@@ -41,20 +40,14 @@
     ListLicenseConfigurationsResponseTypeDef,
     ListLicenseSpecificationsForResourceResponseTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssociationsForLicenseConfigurationPaginator",
     "ListLicenseConfigurationsPaginator",
     "ListLicenseSpecificationsForResourcePaginator",
     "ListResourceInventoryPaginator",
     "ListUsageForLicenseConfigurationPaginator",
 )
@@ -73,15 +66,15 @@
 class ListAssociationsForLicenseConfigurationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListAssociationsForLicenseConfiguration)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listassociationsforlicenseconfigurationpaginator)
     """
 
     def paginate(
-        self, *, LicenseConfigurationArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, LicenseConfigurationArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationsForLicenseConfigurationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListAssociationsForLicenseConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listassociationsforlicenseconfigurationpaginator)
         """
 
 
@@ -92,30 +85,30 @@
     """
 
     def paginate(
         self,
         *,
         LicenseConfigurationArns: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLicenseConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicenseconfigurationspaginator)
         """
 
 
 class ListLicenseSpecificationsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseSpecificationsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicensespecificationsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLicenseSpecificationsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseSpecificationsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicensespecificationsforresourcepaginator)
         """
 
 
@@ -125,15 +118,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listresourceinventorypaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[InventoryFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceInventoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListResourceInventory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listresourceinventorypaginator)
         """
 
 
@@ -144,13 +137,13 @@
     """
 
     def paginate(
         self,
         *,
         LicenseConfigurationArn: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsageForLicenseConfigurationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListUsageForLicenseConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listusageforlicenseconfigurationpaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/paginator.pyi` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         list_associations_for_license_configuration_paginator: ListAssociationsForLicenseConfigurationPaginator = client.get_paginator("list_associations_for_license_configuration")
         list_license_configurations_paginator: ListLicenseConfigurationsPaginator = client.get_paginator("list_license_configurations")
         list_license_specifications_for_resource_paginator: ListLicenseSpecificationsForResourcePaginator = client.get_paginator("list_license_specifications_for_resource")
         list_resource_inventory_paginator: ListResourceInventoryPaginator = client.get_paginator("list_resource_inventory")
         list_usage_for_license_configuration_paginator: ListUsageForLicenseConfigurationPaginator = client.get_paginator("list_usage_for_license_configuration")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     InventoryFilterTypeDef,
@@ -41,19 +40,14 @@
     ListLicenseConfigurationsResponseTypeDef,
     ListLicenseSpecificationsForResourceResponseTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssociationsForLicenseConfigurationPaginator",
     "ListLicenseConfigurationsPaginator",
     "ListLicenseSpecificationsForResourcePaginator",
     "ListResourceInventoryPaginator",
     "ListUsageForLicenseConfigurationPaginator",
 )
@@ -69,15 +63,15 @@
 class ListAssociationsForLicenseConfigurationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListAssociationsForLicenseConfiguration)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listassociationsforlicenseconfigurationpaginator)
     """
 
     def paginate(
-        self, *, LicenseConfigurationArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, LicenseConfigurationArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationsForLicenseConfigurationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListAssociationsForLicenseConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listassociationsforlicenseconfigurationpaginator)
         """
 
 class ListLicenseConfigurationsPaginator(AioPaginator):
@@ -87,29 +81,29 @@
     """
 
     def paginate(
         self,
         *,
         LicenseConfigurationArns: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLicenseConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicenseconfigurationspaginator)
         """
 
 class ListLicenseSpecificationsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseSpecificationsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicensespecificationsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLicenseSpecificationsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListLicenseSpecificationsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listlicensespecificationsforresourcepaginator)
         """
 
 class ListResourceInventoryPaginator(AioPaginator):
@@ -118,15 +112,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listresourceinventorypaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[InventoryFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceInventoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListResourceInventory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listresourceinventorypaginator)
         """
 
 class ListUsageForLicenseConfigurationPaginator(AioPaginator):
@@ -136,13 +130,13 @@
     """
 
     def paginate(
         self,
         *,
         LicenseConfigurationArn: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsageForLicenseConfigurationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager.Paginator.ListUsageForLicenseConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/paginators/#listusageforlicenseconfigurationpaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/type_defs.py` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -12,14 +12,15 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    ActivationOverrideBehaviorType,
     AllowedOperationType,
     CheckoutTypeType,
     EntitlementDataUnitType,
     EntitlementUnitType,
     GrantStatusType,
     InventoryFilterConditionType,
     LicenseConfigurationStatusType,
@@ -39,135 +40,135 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AcceptGrantRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcceptGrantResponseTypeDef",
     "AutomatedDiscoveryInformationTypeDef",
     "BorrowConfigurationTypeDef",
     "CheckInLicenseRequestRequestTypeDef",
     "EntitlementDataTypeDef",
     "MetadataTypeDef",
     "ConsumedLicenseSummaryTypeDef",
     "ProvisionalConfigurationTypeDef",
     "CreateGrantRequestRequestTypeDef",
-    "CreateGrantVersionRequestRequestTypeDef",
+    "CreateGrantResponseTypeDef",
+    "OptionsTypeDef",
+    "CreateGrantVersionResponseTypeDef",
     "TagTypeDef",
+    "CreateLicenseConfigurationResponseTypeDef",
     "LicenseConversionContextTypeDef",
+    "CreateLicenseConversionTaskForResourceResponseTypeDef",
     "ReportContextTypeDef",
     "ReportFrequencyTypeDef",
+    "CreateLicenseManagerReportGeneratorResponseTypeDef",
     "DatetimeRangeTypeDef",
     "EntitlementTypeDef",
     "IssuerTypeDef",
+    "CreateLicenseResponseTypeDef",
+    "CreateLicenseVersionResponseTypeDef",
     "CreateTokenRequestRequestTypeDef",
+    "CreateTokenResponseTypeDef",
     "DeleteGrantRequestRequestTypeDef",
+    "DeleteGrantResponseTypeDef",
     "DeleteLicenseConfigurationRequestRequestTypeDef",
     "DeleteLicenseManagerReportGeneratorRequestRequestTypeDef",
     "DeleteLicenseRequestRequestTypeDef",
+    "DeleteLicenseResponseTypeDef",
     "DeleteTokenRequestRequestTypeDef",
     "EntitlementUsageTypeDef",
     "ExtendLicenseConsumptionRequestRequestTypeDef",
+    "ExtendLicenseConsumptionResponseTypeDef",
     "FilterTypeDef",
     "GetAccessTokenRequestRequestTypeDef",
+    "GetAccessTokenResponseTypeDef",
     "GetGrantRequestRequestTypeDef",
-    "GrantTypeDef",
     "GetLicenseConfigurationRequestRequestTypeDef",
     "ManagedResourceSummaryTypeDef",
     "GetLicenseConversionTaskRequestRequestTypeDef",
     "GetLicenseManagerReportGeneratorRequestRequestTypeDef",
     "GetLicenseRequestRequestTypeDef",
     "GetLicenseUsageRequestRequestTypeDef",
     "OrganizationConfigurationTypeDef",
     "IssuerDetailsTypeDef",
     "ReceivedMetadataTypeDef",
     "InventoryFilterTypeDef",
     "LicenseConfigurationAssociationTypeDef",
     "LicenseConfigurationUsageTypeDef",
     "LicenseSpecificationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
     "ListAssociationsForLicenseConfigurationRequestRequestTypeDef",
     "ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef",
+    "ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
     "ListLicenseSpecificationsForResourceRequestRequestTypeDef",
     "ListLicenseVersionsRequestRequestTypeDef",
     "ResourceInventoryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TokenDataTypeDef",
+    "PaginatorConfigTypeDef",
     "ProductInformationFilterTypeDef",
     "RejectGrantRequestRequestTypeDef",
+    "RejectGrantResponseTypeDef",
     "S3LocationTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AcceptGrantResponseTypeDef",
-    "CreateGrantResponseTypeDef",
-    "CreateGrantVersionResponseTypeDef",
-    "CreateLicenseConfigurationResponseTypeDef",
-    "CreateLicenseConversionTaskForResourceResponseTypeDef",
-    "CreateLicenseManagerReportGeneratorResponseTypeDef",
-    "CreateLicenseResponseTypeDef",
-    "CreateLicenseVersionResponseTypeDef",
-    "CreateTokenResponseTypeDef",
-    "DeleteGrantResponseTypeDef",
-    "DeleteLicenseResponseTypeDef",
-    "ExtendLicenseConsumptionResponseTypeDef",
-    "GetAccessTokenResponseTypeDef",
-    "RejectGrantResponseTypeDef",
     "CheckoutLicenseRequestRequestTypeDef",
     "CheckoutLicenseResponseTypeDef",
     "CheckoutBorrowLicenseRequestRequestTypeDef",
     "CheckoutBorrowLicenseResponseTypeDef",
     "LicenseOperationFailureTypeDef",
     "ConsumptionConfigurationTypeDef",
+    "CreateGrantVersionRequestRequestTypeDef",
+    "GrantTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateLicenseConversionTaskForResourceRequestRequestTypeDef",
     "GetLicenseConversionTaskResponseTypeDef",
     "LicenseConversionTaskTypeDef",
     "CreateLicenseManagerReportGeneratorRequestRequestTypeDef",
     "UpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     "LicenseUsageTypeDef",
     "ListDistributedGrantsRequestRequestTypeDef",
+    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
     "ListLicenseConfigurationsRequestRequestTypeDef",
     "ListLicenseConversionTasksRequestRequestTypeDef",
     "ListLicenseManagerReportGeneratorsRequestRequestTypeDef",
     "ListLicensesRequestRequestTypeDef",
     "ListReceivedGrantsForOrganizationRequestRequestTypeDef",
     "ListReceivedGrantsRequestRequestTypeDef",
     "ListReceivedLicensesForOrganizationRequestRequestTypeDef",
     "ListReceivedLicensesRequestRequestTypeDef",
     "ListTokensRequestRequestTypeDef",
+    "ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     "ListUsageForLicenseConfigurationRequestRequestTypeDef",
-    "GetGrantResponseTypeDef",
-    "ListDistributedGrantsResponseTypeDef",
-    "ListReceivedGrantsForOrganizationResponseTypeDef",
-    "ListReceivedGrantsResponseTypeDef",
     "GetServiceSettingsResponseTypeDef",
     "UpdateServiceSettingsRequestRequestTypeDef",
+    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
     "ListResourceInventoryRequestRequestTypeDef",
     "ListAssociationsForLicenseConfigurationResponseTypeDef",
     "ListUsageForLicenseConfigurationResponseTypeDef",
     "ListLicenseSpecificationsForResourceResponseTypeDef",
     "UpdateLicenseSpecificationsForResourceRequestRequestTypeDef",
-    "ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
-    "ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
-    "ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     "ListResourceInventoryResponseTypeDef",
     "ListTokensResponseTypeDef",
     "ProductInformationTypeDef",
     "ReportGeneratorTypeDef",
     "ListFailuresForLicenseConfigurationOperationsResponseTypeDef",
     "CreateLicenseRequestRequestTypeDef",
     "CreateLicenseVersionRequestRequestTypeDef",
     "GrantedLicenseTypeDef",
     "LicenseTypeDef",
+    "GetGrantResponseTypeDef",
+    "ListDistributedGrantsResponseTypeDef",
+    "ListReceivedGrantsForOrganizationResponseTypeDef",
+    "ListReceivedGrantsResponseTypeDef",
     "ListLicenseConversionTasksResponseTypeDef",
     "GetLicenseUsageResponseTypeDef",
     "CreateLicenseConfigurationRequestRequestTypeDef",
     "GetLicenseConfigurationResponseTypeDef",
     "LicenseConfigurationTypeDef",
     "UpdateLicenseConfigurationRequestRequestTypeDef",
     "GetLicenseManagerReportGeneratorResponseTypeDef",
@@ -183,22 +184,21 @@
 AcceptGrantRequestRequestTypeDef = TypedDict(
     "AcceptGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcceptGrantResponseTypeDef = TypedDict(
+    "AcceptGrantResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutomatedDiscoveryInformationTypeDef = TypedDict(
     "AutomatedDiscoveryInformationTypeDef",
     {
         "LastRunTime": datetime,
@@ -224,21 +224,19 @@
     "_OptionalCheckInLicenseRequestRequestTypeDef",
     {
         "Beneficiary": str,
     },
     total=False,
 )
 
-
 class CheckInLicenseRequestRequestTypeDef(
     _RequiredCheckInLicenseRequestRequestTypeDef, _OptionalCheckInLicenseRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredEntitlementDataTypeDef = TypedDict(
     "_RequiredEntitlementDataTypeDef",
     {
         "Name": str,
         "Unit": EntitlementDataUnitType,
     },
 )
@@ -246,19 +244,17 @@
     "_OptionalEntitlementDataTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-
 class EntitlementDataTypeDef(_RequiredEntitlementDataTypeDef, _OptionalEntitlementDataTypeDef):
     pass
 
-
 MetadataTypeDef = TypedDict(
     "MetadataTypeDef",
     {
         "Name": str,
         "Value": str,
     },
     total=False,
@@ -288,58 +284,75 @@
         "LicenseArn": str,
         "Principals": Sequence[str],
         "HomeRegion": str,
         "AllowedOperations": Sequence[AllowedOperationType],
     },
 )
 
-_RequiredCreateGrantVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateGrantVersionRequestRequestTypeDef",
+CreateGrantResponseTypeDef = TypedDict(
+    "CreateGrantResponseTypeDef",
     {
-        "ClientToken": str,
         "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalCreateGrantVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateGrantVersionRequestRequestTypeDef",
+
+OptionsTypeDef = TypedDict(
+    "OptionsTypeDef",
     {
-        "GrantName": str,
-        "AllowedOperations": Sequence[AllowedOperationType],
-        "Status": GrantStatusType,
-        "StatusReason": str,
-        "SourceVersion": str,
+        "ActivationOverrideBehavior": ActivationOverrideBehaviorType,
     },
     total=False,
 )
 
-
-class CreateGrantVersionRequestRequestTypeDef(
-    _RequiredCreateGrantVersionRequestRequestTypeDef,
-    _OptionalCreateGrantVersionRequestRequestTypeDef,
-):
-    pass
-
+CreateGrantVersionResponseTypeDef = TypedDict(
+    "CreateGrantVersionResponseTypeDef",
+    {
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+CreateLicenseConfigurationResponseTypeDef = TypedDict(
+    "CreateLicenseConfigurationResponseTypeDef",
+    {
+        "LicenseConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LicenseConversionContextTypeDef = TypedDict(
     "LicenseConversionContextTypeDef",
     {
         "UsageOperation": str,
     },
     total=False,
 )
 
+CreateLicenseConversionTaskForResourceResponseTypeDef = TypedDict(
+    "CreateLicenseConversionTaskForResourceResponseTypeDef",
+    {
+        "LicenseConversionTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReportContextTypeDef = TypedDict(
     "ReportContextTypeDef",
     {
         "licenseConfigurationArns": Sequence[str],
     },
 )
 
@@ -348,33 +361,39 @@
     {
         "value": int,
         "period": ReportFrequencyTypeType,
     },
     total=False,
 )
 
+CreateLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
+    "CreateLicenseManagerReportGeneratorResponseTypeDef",
+    {
+        "LicenseManagerReportGeneratorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDatetimeRangeTypeDef = TypedDict(
     "_RequiredDatetimeRangeTypeDef",
     {
         "Begin": str,
     },
 )
 _OptionalDatetimeRangeTypeDef = TypedDict(
     "_OptionalDatetimeRangeTypeDef",
     {
         "End": str,
     },
     total=False,
 )
 
-
 class DatetimeRangeTypeDef(_RequiredDatetimeRangeTypeDef, _OptionalDatetimeRangeTypeDef):
     pass
 
-
 _RequiredEntitlementTypeDef = TypedDict(
     "_RequiredEntitlementTypeDef",
     {
         "Name": str,
         "Unit": EntitlementUnitType,
     },
 )
@@ -385,37 +404,53 @@
         "MaxCount": int,
         "Overage": bool,
         "AllowCheckIn": bool,
     },
     total=False,
 )
 
-
 class EntitlementTypeDef(_RequiredEntitlementTypeDef, _OptionalEntitlementTypeDef):
     pass
 
-
 _RequiredIssuerTypeDef = TypedDict(
     "_RequiredIssuerTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalIssuerTypeDef = TypedDict(
     "_OptionalIssuerTypeDef",
     {
         "SignKey": str,
     },
     total=False,
 )
 
-
 class IssuerTypeDef(_RequiredIssuerTypeDef, _OptionalIssuerTypeDef):
     pass
 
+CreateLicenseResponseTypeDef = TypedDict(
+    "CreateLicenseResponseTypeDef",
+    {
+        "LicenseArn": str,
+        "Status": LicenseStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLicenseVersionResponseTypeDef = TypedDict(
+    "CreateLicenseVersionResponseTypeDef",
+    {
+        "LicenseArn": str,
+        "Version": str,
+        "Status": LicenseStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTokenRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "ClientToken": str,
     },
@@ -426,20 +461,28 @@
         "RoleArns": Sequence[str],
         "ExpirationInDays": int,
         "TokenProperties": Sequence[str],
     },
     total=False,
 )
 
-
 class CreateTokenRequestRequestTypeDef(
     _RequiredCreateTokenRequestRequestTypeDef, _OptionalCreateTokenRequestRequestTypeDef
 ):
     pass
 
+CreateTokenResponseTypeDef = TypedDict(
+    "CreateTokenResponseTypeDef",
+    {
+        "TokenId": str,
+        "TokenType": Literal["REFRESH_TOKEN"],
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDeleteGrantRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
         "Version": str,
     },
@@ -448,20 +491,28 @@
     "_OptionalDeleteGrantRequestRequestTypeDef",
     {
         "StatusReason": str,
     },
     total=False,
 )
 
-
 class DeleteGrantRequestRequestTypeDef(
     _RequiredDeleteGrantRequestRequestTypeDef, _OptionalDeleteGrantRequestRequestTypeDef
 ):
     pass
 
+DeleteGrantResponseTypeDef = TypedDict(
+    "DeleteGrantResponseTypeDef",
+    {
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
@@ -477,14 +528,23 @@
     "DeleteLicenseRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "SourceVersion": str,
     },
 )
 
+DeleteLicenseResponseTypeDef = TypedDict(
+    "DeleteLicenseResponseTypeDef",
+    {
+        "Status": LicenseDeletionStatusType,
+        "DeletionDate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTokenRequestRequestTypeDef = TypedDict(
     "DeleteTokenRequestRequestTypeDef",
     {
         "TokenId": str,
     },
 )
 
@@ -500,40 +560,45 @@
     "_OptionalEntitlementUsageTypeDef",
     {
         "MaxCount": str,
     },
     total=False,
 )
 
-
 class EntitlementUsageTypeDef(_RequiredEntitlementUsageTypeDef, _OptionalEntitlementUsageTypeDef):
     pass
 
-
 _RequiredExtendLicenseConsumptionRequestRequestTypeDef = TypedDict(
     "_RequiredExtendLicenseConsumptionRequestRequestTypeDef",
     {
         "LicenseConsumptionToken": str,
     },
 )
 _OptionalExtendLicenseConsumptionRequestRequestTypeDef = TypedDict(
     "_OptionalExtendLicenseConsumptionRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
-
 class ExtendLicenseConsumptionRequestRequestTypeDef(
     _RequiredExtendLicenseConsumptionRequestRequestTypeDef,
     _OptionalExtendLicenseConsumptionRequestRequestTypeDef,
 ):
     pass
 
+ExtendLicenseConsumptionResponseTypeDef = TypedDict(
+    "ExtendLicenseConsumptionResponseTypeDef",
+    {
+        "LicenseConsumptionToken": str,
+        "Expiration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
@@ -550,20 +615,26 @@
     "_OptionalGetAccessTokenRequestRequestTypeDef",
     {
         "TokenProperties": Sequence[str],
     },
     total=False,
 )
 
-
 class GetAccessTokenRequestRequestTypeDef(
     _RequiredGetAccessTokenRequestRequestTypeDef, _OptionalGetAccessTokenRequestRequestTypeDef
 ):
     pass
 
+GetAccessTokenResponseTypeDef = TypedDict(
+    "GetAccessTokenResponseTypeDef",
+    {
+        "AccessToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetGrantRequestRequestTypeDef = TypedDict(
     "_RequiredGetGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
@@ -571,48 +642,19 @@
     "_OptionalGetGrantRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetGrantRequestRequestTypeDef(
     _RequiredGetGrantRequestRequestTypeDef, _OptionalGetGrantRequestRequestTypeDef
 ):
     pass
 
-
-_RequiredGrantTypeDef = TypedDict(
-    "_RequiredGrantTypeDef",
-    {
-        "GrantArn": str,
-        "GrantName": str,
-        "ParentArn": str,
-        "LicenseArn": str,
-        "GranteePrincipalArn": str,
-        "HomeRegion": str,
-        "GrantStatus": GrantStatusType,
-        "Version": str,
-        "GrantedOperations": List[AllowedOperationType],
-    },
-)
-_OptionalGrantTypeDef = TypedDict(
-    "_OptionalGrantTypeDef",
-    {
-        "StatusReason": str,
-    },
-    total=False,
-)
-
-
-class GrantTypeDef(_RequiredGrantTypeDef, _OptionalGrantTypeDef):
-    pass
-
-
 GetLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "GetLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 
@@ -649,21 +691,19 @@
     "_OptionalGetLicenseRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetLicenseRequestRequestTypeDef(
     _RequiredGetLicenseRequestRequestTypeDef, _OptionalGetLicenseRequestRequestTypeDef
 ):
     pass
 
-
 GetLicenseUsageRequestRequestTypeDef = TypedDict(
     "GetLicenseUsageRequestRequestTypeDef",
     {
         "LicenseArn": str,
     },
 )
 
@@ -705,19 +745,17 @@
     "_OptionalInventoryFilterTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-
 class InventoryFilterTypeDef(_RequiredInventoryFilterTypeDef, _OptionalInventoryFilterTypeDef):
     pass
 
-
 LicenseConfigurationAssociationTypeDef = TypedDict(
     "LicenseConfigurationAssociationTypeDef",
     {
         "ResourceArn": str,
         "ResourceType": ResourceTypeType,
         "ResourceOwnerId": str,
         "AssociationTime": datetime,
@@ -749,31 +787,39 @@
     "_OptionalLicenseSpecificationTypeDef",
     {
         "AmiAssociationScope": str,
     },
     total=False,
 )
 
-
 class LicenseSpecificationTypeDef(
     _RequiredLicenseSpecificationTypeDef, _OptionalLicenseSpecificationTypeDef
 ):
     pass
 
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "LicenseConfigurationArn": str,
+    },
+)
+_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef(
+    _RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
+    _OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 _OptionalListAssociationsForLicenseConfigurationRequestRequestTypeDef = TypedDict(
@@ -781,22 +827,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListAssociationsForLicenseConfigurationRequestRequestTypeDef(
     _RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef,
     _OptionalListAssociationsForLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef = TypedDict(
     "_RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 _OptionalListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef = TypedDict(
@@ -804,21 +848,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef(
     _RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
     _OptionalListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef(
+    _RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
+    _OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
+):
+    pass
 
 _RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
@@ -827,22 +889,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListLicenseSpecificationsForResourceRequestRequestTypeDef(
     _RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef,
     _OptionalListLicenseSpecificationsForResourceRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListLicenseVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListLicenseVersionsRequestRequestTypeDef",
     {
         "LicenseArn": str,
     },
 )
 _OptionalListLicenseVersionsRequestRequestTypeDef = TypedDict(
@@ -850,22 +910,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListLicenseVersionsRequestRequestTypeDef(
     _RequiredListLicenseVersionsRequestRequestTypeDef,
     _OptionalListLicenseVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 ResourceInventoryTypeDef = TypedDict(
     "ResourceInventoryTypeDef",
     {
         "ResourceId": str,
         "ResourceType": ResourceTypeType,
         "ResourceArn": str,
         "Platform": str,
@@ -892,14 +950,24 @@
         "TokenProperties": List[str],
         "RoleArns": List[str],
         "Status": str,
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
 _RequiredProductInformationFilterTypeDef = TypedDict(
     "_RequiredProductInformationFilterTypeDef",
     {
         "ProductInformationFilterName": str,
         "ProductInformationFilterComparator": str,
     },
 )
@@ -907,172 +975,61 @@
     "_OptionalProductInformationFilterTypeDef",
     {
         "ProductInformationFilterValue": Sequence[str],
     },
     total=False,
 )
 
-
 class ProductInformationFilterTypeDef(
     _RequiredProductInformationFilterTypeDef, _OptionalProductInformationFilterTypeDef
 ):
     pass
 
-
 RejectGrantRequestRequestTypeDef = TypedDict(
     "RejectGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
 
-S3LocationTypeDef = TypedDict(
-    "S3LocationTypeDef",
-    {
-        "bucket": str,
-        "keyPrefix": str,
-    },
-    total=False,
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-AcceptGrantResponseTypeDef = TypedDict(
-    "AcceptGrantResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantResponseTypeDef = TypedDict(
-    "CreateGrantResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantVersionResponseTypeDef = TypedDict(
-    "CreateGrantVersionResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseConfigurationResponseTypeDef = TypedDict(
-    "CreateLicenseConfigurationResponseTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseConversionTaskForResourceResponseTypeDef = TypedDict(
-    "CreateLicenseConversionTaskForResourceResponseTypeDef",
-    {
-        "LicenseConversionTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
-    "CreateLicenseManagerReportGeneratorResponseTypeDef",
-    {
-        "LicenseManagerReportGeneratorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseResponseTypeDef = TypedDict(
-    "CreateLicenseResponseTypeDef",
-    {
-        "LicenseArn": str,
-        "Status": LicenseStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseVersionResponseTypeDef = TypedDict(
-    "CreateLicenseVersionResponseTypeDef",
-    {
-        "LicenseArn": str,
-        "Version": str,
-        "Status": LicenseStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTokenResponseTypeDef = TypedDict(
-    "CreateTokenResponseTypeDef",
-    {
-        "TokenId": str,
-        "TokenType": Literal["REFRESH_TOKEN"],
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGrantResponseTypeDef = TypedDict(
-    "DeleteGrantResponseTypeDef",
+RejectGrantResponseTypeDef = TypedDict(
+    "RejectGrantResponseTypeDef",
     {
         "GrantArn": str,
         "Status": GrantStatusType,
         "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteLicenseResponseTypeDef = TypedDict(
-    "DeleteLicenseResponseTypeDef",
-    {
-        "Status": LicenseDeletionStatusType,
-        "DeletionDate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExtendLicenseConsumptionResponseTypeDef = TypedDict(
-    "ExtendLicenseConsumptionResponseTypeDef",
+S3LocationTypeDef = TypedDict(
+    "S3LocationTypeDef",
     {
-        "LicenseConsumptionToken": str,
-        "Expiration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "bucket": str,
+        "keyPrefix": str,
     },
+    total=False,
 )
 
-GetAccessTokenResponseTypeDef = TypedDict(
-    "GetAccessTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "AccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-RejectGrantResponseTypeDef = TypedDict(
-    "RejectGrantResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 _RequiredCheckoutLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCheckoutLicenseRequestRequestTypeDef",
     {
         "ProductSKU": str,
@@ -1087,33 +1044,31 @@
     {
         "Beneficiary": str,
         "NodeId": str,
     },
     total=False,
 )
 
-
 class CheckoutLicenseRequestRequestTypeDef(
     _RequiredCheckoutLicenseRequestRequestTypeDef, _OptionalCheckoutLicenseRequestRequestTypeDef
 ):
     pass
 
-
 CheckoutLicenseResponseTypeDef = TypedDict(
     "CheckoutLicenseResponseTypeDef",
     {
         "CheckoutType": CheckoutTypeType,
         "LicenseConsumptionToken": str,
         "EntitlementsAllowed": List[EntitlementDataTypeDef],
         "SignedToken": str,
         "NodeId": str,
         "IssuedAt": str,
         "Expiration": str,
         "LicenseArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCheckoutBorrowLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCheckoutBorrowLicenseRequestRequestTypeDef",
     {
         "LicenseArn": str,
@@ -1127,34 +1082,32 @@
     {
         "NodeId": str,
         "CheckoutMetadata": Sequence[MetadataTypeDef],
     },
     total=False,
 )
 
-
 class CheckoutBorrowLicenseRequestRequestTypeDef(
     _RequiredCheckoutBorrowLicenseRequestRequestTypeDef,
     _OptionalCheckoutBorrowLicenseRequestRequestTypeDef,
 ):
     pass
 
-
 CheckoutBorrowLicenseResponseTypeDef = TypedDict(
     "CheckoutBorrowLicenseResponseTypeDef",
     {
         "LicenseArn": str,
         "LicenseConsumptionToken": str,
         "EntitlementsAllowed": List[EntitlementDataTypeDef],
         "NodeId": str,
         "SignedToken": str,
         "IssuedAt": str,
         "Expiration": str,
         "CheckoutMetadata": List[MetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseOperationFailureTypeDef = TypedDict(
     "LicenseOperationFailureTypeDef",
     {
         "ResourceArn": str,
@@ -1175,19 +1128,71 @@
         "RenewType": RenewTypeType,
         "ProvisionalConfiguration": ProvisionalConfigurationTypeDef,
         "BorrowConfiguration": BorrowConfigurationTypeDef,
     },
     total=False,
 )
 
+_RequiredCreateGrantVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateGrantVersionRequestRequestTypeDef",
+    {
+        "ClientToken": str,
+        "GrantArn": str,
+    },
+)
+_OptionalCreateGrantVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateGrantVersionRequestRequestTypeDef",
+    {
+        "GrantName": str,
+        "AllowedOperations": Sequence[AllowedOperationType],
+        "Status": GrantStatusType,
+        "StatusReason": str,
+        "SourceVersion": str,
+        "Options": OptionsTypeDef,
+    },
+    total=False,
+)
+
+class CreateGrantVersionRequestRequestTypeDef(
+    _RequiredCreateGrantVersionRequestRequestTypeDef,
+    _OptionalCreateGrantVersionRequestRequestTypeDef,
+):
+    pass
+
+_RequiredGrantTypeDef = TypedDict(
+    "_RequiredGrantTypeDef",
+    {
+        "GrantArn": str,
+        "GrantName": str,
+        "ParentArn": str,
+        "LicenseArn": str,
+        "GranteePrincipalArn": str,
+        "HomeRegion": str,
+        "GrantStatus": GrantStatusType,
+        "Version": str,
+        "GrantedOperations": List[AllowedOperationType],
+    },
+)
+_OptionalGrantTypeDef = TypedDict(
+    "_OptionalGrantTypeDef",
+    {
+        "StatusReason": str,
+        "Options": OptionsTypeDef,
+    },
+    total=False,
+)
+
+class GrantTypeDef(_RequiredGrantTypeDef, _OptionalGrantTypeDef):
+    pass
+
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
         "ResourceArn": str,
@@ -1212,15 +1217,15 @@
         "SourceLicenseContext": LicenseConversionContextTypeDef,
         "DestinationLicenseContext": LicenseConversionContextTypeDef,
         "StatusMessage": str,
         "Status": LicenseConversionTaskStatusType,
         "StartTime": datetime,
         "LicenseConversionTime": datetime,
         "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseConversionTaskTypeDef = TypedDict(
     "LicenseConversionTaskTypeDef",
     {
         "LicenseConversionTaskId": str,
@@ -1251,22 +1256,20 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateLicenseManagerReportGeneratorRequestRequestTypeDef(
     _RequiredCreateLicenseManagerReportGeneratorRequestRequestTypeDef,
     _OptionalCreateLicenseManagerReportGeneratorRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     {
         "LicenseManagerReportGeneratorArn": str,
         "ReportGeneratorName": str,
         "Type": Sequence[ReportTypeType],
         "ReportContext": ReportContextTypeDef,
@@ -1278,22 +1281,20 @@
     "_OptionalUpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateLicenseManagerReportGeneratorRequestRequestTypeDef(
     _RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
     _OptionalUpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
 ):
     pass
 
-
 LicenseUsageTypeDef = TypedDict(
     "LicenseUsageTypeDef",
     {
         "EntitlementUsages": List[EntitlementUsageTypeDef],
     },
     total=False,
 )
@@ -1305,14 +1306,24 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef = TypedDict(
+    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
+    {
+        "LicenseConfigurationArns": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLicenseConfigurationsRequestRequestTypeDef = TypedDict(
     "ListLicenseConfigurationsRequestRequestTypeDef",
     {
         "LicenseConfigurationArns": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
@@ -1363,22 +1374,20 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListReceivedGrantsForOrganizationRequestRequestTypeDef(
     _RequiredListReceivedGrantsForOrganizationRequestRequestTypeDef,
     _OptionalListReceivedGrantsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
-
 ListReceivedGrantsRequestRequestTypeDef = TypedDict(
     "ListReceivedGrantsRequestRequestTypeDef",
     {
         "GrantArns": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
@@ -1414,96 +1423,89 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef",
+_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
-_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef",
+_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ListUsageForLicenseConfigurationRequestRequestTypeDef(
-    _RequiredListUsageForLicenseConfigurationRequestRequestTypeDef,
-    _OptionalListUsageForLicenseConfigurationRequestRequestTypeDef,
+class ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef(
+    _RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
+    _OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
 ):
     pass
 
-
-GetGrantResponseTypeDef = TypedDict(
-    "GetGrantResponseTypeDef",
-    {
-        "Grant": GrantTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDistributedGrantsResponseTypeDef = TypedDict(
-    "ListDistributedGrantsResponseTypeDef",
+_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef",
     {
-        "Grants": List[GrantTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "LicenseConfigurationArn": str,
     },
 )
-
-ListReceivedGrantsForOrganizationResponseTypeDef = TypedDict(
-    "ListReceivedGrantsForOrganizationResponseTypeDef",
+_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef",
     {
-        "Grants": List[GrantTypeDef],
+        "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filters": Sequence[FilterTypeDef],
     },
+    total=False,
 )
 
-ListReceivedGrantsResponseTypeDef = TypedDict(
-    "ListReceivedGrantsResponseTypeDef",
-    {
-        "Grants": List[GrantTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListUsageForLicenseConfigurationRequestRequestTypeDef(
+    _RequiredListUsageForLicenseConfigurationRequestRequestTypeDef,
+    _OptionalListUsageForLicenseConfigurationRequestRequestTypeDef,
+):
+    pass
 
 GetServiceSettingsResponseTypeDef = TypedDict(
     "GetServiceSettingsResponseTypeDef",
     {
         "S3BucketArn": str,
         "SnsTopicArn": str,
         "OrganizationConfiguration": OrganizationConfigurationTypeDef,
         "EnableCrossAccountsDiscovery": bool,
         "LicenseManagerResourceShareArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceSettingsRequestRequestTypeDef = TypedDict(
     "UpdateServiceSettingsRequestRequestTypeDef",
     {
         "S3BucketArn": str,
         "SnsTopicArn": str,
         "OrganizationConfiguration": OrganizationConfigurationTypeDef,
         "EnableCrossAccountsDiscovery": bool,
     },
     total=False,
 )
 
+ListResourceInventoryRequestListResourceInventoryPaginateTypeDef = TypedDict(
+    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
+    {
+        "Filters": Sequence[InventoryFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceInventoryRequestRequestTypeDef = TypedDict(
     "ListResourceInventoryRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[InventoryFilterTypeDef],
     },
@@ -1511,33 +1513,33 @@
 )
 
 ListAssociationsForLicenseConfigurationResponseTypeDef = TypedDict(
     "ListAssociationsForLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationAssociations": List[LicenseConfigurationAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsageForLicenseConfigurationResponseTypeDef = TypedDict(
     "ListUsageForLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationUsageList": List[LicenseConfigurationUsageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseSpecificationsForResourceResponseTypeDef = TypedDict(
     "ListLicenseSpecificationsForResourceResponseTypeDef",
     {
         "LicenseSpecifications": List[LicenseSpecificationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1548,123 +1550,35 @@
     {
         "AddLicenseSpecifications": Sequence[LicenseSpecificationTypeDef],
         "RemoveLicenseSpecifications": Sequence[LicenseSpecificationTypeDef],
     },
     total=False,
 )
 
-
 class UpdateLicenseSpecificationsForResourceRequestRequestTypeDef(
     _RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
     _OptionalUpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
 ):
     pass
 
-
-_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-    },
-)
-_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef(
-    _RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-    _OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-):
-    pass
-
-
-ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef = TypedDict(
-    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
-    {
-        "LicenseConfigurationArns": Sequence[str],
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef(
-    _RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-    _OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-):
-    pass
-
-
-ListResourceInventoryRequestListResourceInventoryPaginateTypeDef = TypedDict(
-    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
-    {
-        "Filters": Sequence[InventoryFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-    },
-)
-_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef(
-    _RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
-    _OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
-):
-    pass
-
-
 ListResourceInventoryResponseTypeDef = TypedDict(
     "ListResourceInventoryResponseTypeDef",
     {
         "ResourceInventoryList": List[ResourceInventoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTokensResponseTypeDef = TypedDict(
     "ListTokensResponseTypeDef",
     {
         "Tokens": List[TokenDataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProductInformationTypeDef = TypedDict(
     "ProductInformationTypeDef",
     {
         "ResourceType": str,
@@ -1693,15 +1607,15 @@
 )
 
 ListFailuresForLicenseConfigurationOperationsResponseTypeDef = TypedDict(
     "ListFailuresForLicenseConfigurationOperationsResponseTypeDef",
     {
         "LicenseOperationFailureList": List[LicenseOperationFailureTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseRequestRequestTypeDef",
     {
         "LicenseName": str,
@@ -1720,21 +1634,19 @@
     "_OptionalCreateLicenseRequestRequestTypeDef",
     {
         "LicenseMetadata": Sequence[MetadataTypeDef],
     },
     total=False,
 )
 
-
 class CreateLicenseRequestRequestTypeDef(
     _RequiredCreateLicenseRequestRequestTypeDef, _OptionalCreateLicenseRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateLicenseVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseVersionRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "LicenseName": str,
         "ProductName": str,
         "Issuer": IssuerTypeDef,
@@ -1751,22 +1663,20 @@
     {
         "LicenseMetadata": Sequence[MetadataTypeDef],
         "SourceVersion": str,
     },
     total=False,
 )
 
-
 class CreateLicenseVersionRequestRequestTypeDef(
     _RequiredCreateLicenseVersionRequestRequestTypeDef,
     _OptionalCreateLicenseVersionRequestRequestTypeDef,
 ):
     pass
 
-
 GrantedLicenseTypeDef = TypedDict(
     "GrantedLicenseTypeDef",
     {
         "LicenseArn": str,
         "LicenseName": str,
         "ProductName": str,
         "ProductSKU": str,
@@ -1802,28 +1712,63 @@
         "LicenseMetadata": List[MetadataTypeDef],
         "CreateTime": str,
         "Version": str,
     },
     total=False,
 )
 
+GetGrantResponseTypeDef = TypedDict(
+    "GetGrantResponseTypeDef",
+    {
+        "Grant": GrantTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDistributedGrantsResponseTypeDef = TypedDict(
+    "ListDistributedGrantsResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceivedGrantsForOrganizationResponseTypeDef = TypedDict(
+    "ListReceivedGrantsForOrganizationResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceivedGrantsResponseTypeDef = TypedDict(
+    "ListReceivedGrantsResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListLicenseConversionTasksResponseTypeDef = TypedDict(
     "ListLicenseConversionTasksResponseTypeDef",
     {
         "LicenseConversionTasks": List[LicenseConversionTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLicenseUsageResponseTypeDef = TypedDict(
     "GetLicenseUsageResponseTypeDef",
     {
         "LicenseUsage": LicenseUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseConfigurationRequestRequestTypeDef",
     {
         "Name": str,
@@ -1840,22 +1785,20 @@
         "Tags": Sequence[TagTypeDef],
         "DisassociateWhenNotFound": bool,
         "ProductInformationList": Sequence[ProductInformationTypeDef],
     },
     total=False,
 )
 
-
 class CreateLicenseConfigurationRequestRequestTypeDef(
     _RequiredCreateLicenseConfigurationRequestRequestTypeDef,
     _OptionalCreateLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetLicenseConfigurationResponseTypeDef = TypedDict(
     "GetLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationId": str,
         "LicenseConfigurationArn": str,
         "Name": str,
         "Description": str,
@@ -1868,15 +1811,15 @@
         "OwnerAccountId": str,
         "ConsumedLicenseSummaryList": List[ConsumedLicenseSummaryTypeDef],
         "ManagedResourceSummaryList": List[ManagedResourceSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "ProductInformationList": List[ProductInformationTypeDef],
         "AutomatedDiscoveryInformation": AutomatedDiscoveryInformationTypeDef,
         "DisassociateWhenNotFound": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseConfigurationTypeDef = TypedDict(
     "LicenseConfigurationTypeDef",
     {
         "LicenseConfigurationId": str,
@@ -1916,84 +1859,82 @@
         "Description": str,
         "ProductInformationList": Sequence[ProductInformationTypeDef],
         "DisassociateWhenNotFound": bool,
     },
     total=False,
 )
 
-
 class UpdateLicenseConfigurationRequestRequestTypeDef(
     _RequiredUpdateLicenseConfigurationRequestRequestTypeDef,
     _OptionalUpdateLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
     "GetLicenseManagerReportGeneratorResponseTypeDef",
     {
         "ReportGenerator": ReportGeneratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseManagerReportGeneratorsResponseTypeDef = TypedDict(
     "ListLicenseManagerReportGeneratorsResponseTypeDef",
     {
         "ReportGenerators": List[ReportGeneratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReceivedLicensesForOrganizationResponseTypeDef = TypedDict(
     "ListReceivedLicensesForOrganizationResponseTypeDef",
     {
         "Licenses": List[GrantedLicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReceivedLicensesResponseTypeDef = TypedDict(
     "ListReceivedLicensesResponseTypeDef",
     {
         "Licenses": List[GrantedLicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLicenseResponseTypeDef = TypedDict(
     "GetLicenseResponseTypeDef",
     {
         "License": LicenseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseVersionsResponseTypeDef = TypedDict(
     "ListLicenseVersionsResponseTypeDef",
     {
         "Licenses": List[LicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicensesResponseTypeDef = TypedDict(
     "ListLicensesResponseTypeDef",
     {
         "Licenses": List[LicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseConfigurationsResponseTypeDef = TypedDict(
     "ListLicenseConfigurationsResponseTypeDef",
     {
         "LicenseConfigurations": List[LicenseConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager/type_defs.pyi` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,14 +12,15 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    ActivationOverrideBehaviorType,
     AllowedOperationType,
     CheckoutTypeType,
     EntitlementDataUnitType,
     EntitlementUnitType,
     GrantStatusType,
     InventoryFilterConditionType,
     LicenseConfigurationStatusType,
@@ -39,134 +40,136 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AcceptGrantRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcceptGrantResponseTypeDef",
     "AutomatedDiscoveryInformationTypeDef",
     "BorrowConfigurationTypeDef",
     "CheckInLicenseRequestRequestTypeDef",
     "EntitlementDataTypeDef",
     "MetadataTypeDef",
     "ConsumedLicenseSummaryTypeDef",
     "ProvisionalConfigurationTypeDef",
     "CreateGrantRequestRequestTypeDef",
-    "CreateGrantVersionRequestRequestTypeDef",
+    "CreateGrantResponseTypeDef",
+    "OptionsTypeDef",
+    "CreateGrantVersionResponseTypeDef",
     "TagTypeDef",
+    "CreateLicenseConfigurationResponseTypeDef",
     "LicenseConversionContextTypeDef",
+    "CreateLicenseConversionTaskForResourceResponseTypeDef",
     "ReportContextTypeDef",
     "ReportFrequencyTypeDef",
+    "CreateLicenseManagerReportGeneratorResponseTypeDef",
     "DatetimeRangeTypeDef",
     "EntitlementTypeDef",
     "IssuerTypeDef",
+    "CreateLicenseResponseTypeDef",
+    "CreateLicenseVersionResponseTypeDef",
     "CreateTokenRequestRequestTypeDef",
+    "CreateTokenResponseTypeDef",
     "DeleteGrantRequestRequestTypeDef",
+    "DeleteGrantResponseTypeDef",
     "DeleteLicenseConfigurationRequestRequestTypeDef",
     "DeleteLicenseManagerReportGeneratorRequestRequestTypeDef",
     "DeleteLicenseRequestRequestTypeDef",
+    "DeleteLicenseResponseTypeDef",
     "DeleteTokenRequestRequestTypeDef",
     "EntitlementUsageTypeDef",
     "ExtendLicenseConsumptionRequestRequestTypeDef",
+    "ExtendLicenseConsumptionResponseTypeDef",
     "FilterTypeDef",
     "GetAccessTokenRequestRequestTypeDef",
+    "GetAccessTokenResponseTypeDef",
     "GetGrantRequestRequestTypeDef",
-    "GrantTypeDef",
     "GetLicenseConfigurationRequestRequestTypeDef",
     "ManagedResourceSummaryTypeDef",
     "GetLicenseConversionTaskRequestRequestTypeDef",
     "GetLicenseManagerReportGeneratorRequestRequestTypeDef",
     "GetLicenseRequestRequestTypeDef",
     "GetLicenseUsageRequestRequestTypeDef",
     "OrganizationConfigurationTypeDef",
     "IssuerDetailsTypeDef",
     "ReceivedMetadataTypeDef",
     "InventoryFilterTypeDef",
     "LicenseConfigurationAssociationTypeDef",
     "LicenseConfigurationUsageTypeDef",
     "LicenseSpecificationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
     "ListAssociationsForLicenseConfigurationRequestRequestTypeDef",
     "ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef",
+    "ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
     "ListLicenseSpecificationsForResourceRequestRequestTypeDef",
     "ListLicenseVersionsRequestRequestTypeDef",
     "ResourceInventoryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TokenDataTypeDef",
+    "PaginatorConfigTypeDef",
     "ProductInformationFilterTypeDef",
     "RejectGrantRequestRequestTypeDef",
+    "RejectGrantResponseTypeDef",
     "S3LocationTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AcceptGrantResponseTypeDef",
-    "CreateGrantResponseTypeDef",
-    "CreateGrantVersionResponseTypeDef",
-    "CreateLicenseConfigurationResponseTypeDef",
-    "CreateLicenseConversionTaskForResourceResponseTypeDef",
-    "CreateLicenseManagerReportGeneratorResponseTypeDef",
-    "CreateLicenseResponseTypeDef",
-    "CreateLicenseVersionResponseTypeDef",
-    "CreateTokenResponseTypeDef",
-    "DeleteGrantResponseTypeDef",
-    "DeleteLicenseResponseTypeDef",
-    "ExtendLicenseConsumptionResponseTypeDef",
-    "GetAccessTokenResponseTypeDef",
-    "RejectGrantResponseTypeDef",
     "CheckoutLicenseRequestRequestTypeDef",
     "CheckoutLicenseResponseTypeDef",
     "CheckoutBorrowLicenseRequestRequestTypeDef",
     "CheckoutBorrowLicenseResponseTypeDef",
     "LicenseOperationFailureTypeDef",
     "ConsumptionConfigurationTypeDef",
+    "CreateGrantVersionRequestRequestTypeDef",
+    "GrantTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateLicenseConversionTaskForResourceRequestRequestTypeDef",
     "GetLicenseConversionTaskResponseTypeDef",
     "LicenseConversionTaskTypeDef",
     "CreateLicenseManagerReportGeneratorRequestRequestTypeDef",
     "UpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     "LicenseUsageTypeDef",
     "ListDistributedGrantsRequestRequestTypeDef",
+    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
     "ListLicenseConfigurationsRequestRequestTypeDef",
     "ListLicenseConversionTasksRequestRequestTypeDef",
     "ListLicenseManagerReportGeneratorsRequestRequestTypeDef",
     "ListLicensesRequestRequestTypeDef",
     "ListReceivedGrantsForOrganizationRequestRequestTypeDef",
     "ListReceivedGrantsRequestRequestTypeDef",
     "ListReceivedLicensesForOrganizationRequestRequestTypeDef",
     "ListReceivedLicensesRequestRequestTypeDef",
     "ListTokensRequestRequestTypeDef",
+    "ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     "ListUsageForLicenseConfigurationRequestRequestTypeDef",
-    "GetGrantResponseTypeDef",
-    "ListDistributedGrantsResponseTypeDef",
-    "ListReceivedGrantsForOrganizationResponseTypeDef",
-    "ListReceivedGrantsResponseTypeDef",
     "GetServiceSettingsResponseTypeDef",
     "UpdateServiceSettingsRequestRequestTypeDef",
+    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
     "ListResourceInventoryRequestRequestTypeDef",
     "ListAssociationsForLicenseConfigurationResponseTypeDef",
     "ListUsageForLicenseConfigurationResponseTypeDef",
     "ListLicenseSpecificationsForResourceResponseTypeDef",
     "UpdateLicenseSpecificationsForResourceRequestRequestTypeDef",
-    "ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
-    "ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
-    "ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     "ListResourceInventoryResponseTypeDef",
     "ListTokensResponseTypeDef",
     "ProductInformationTypeDef",
     "ReportGeneratorTypeDef",
     "ListFailuresForLicenseConfigurationOperationsResponseTypeDef",
     "CreateLicenseRequestRequestTypeDef",
     "CreateLicenseVersionRequestRequestTypeDef",
     "GrantedLicenseTypeDef",
     "LicenseTypeDef",
+    "GetGrantResponseTypeDef",
+    "ListDistributedGrantsResponseTypeDef",
+    "ListReceivedGrantsForOrganizationResponseTypeDef",
+    "ListReceivedGrantsResponseTypeDef",
     "ListLicenseConversionTasksResponseTypeDef",
     "GetLicenseUsageResponseTypeDef",
     "CreateLicenseConfigurationRequestRequestTypeDef",
     "GetLicenseConfigurationResponseTypeDef",
     "LicenseConfigurationTypeDef",
     "UpdateLicenseConfigurationRequestRequestTypeDef",
     "GetLicenseManagerReportGeneratorResponseTypeDef",
@@ -182,22 +185,21 @@
 AcceptGrantRequestRequestTypeDef = TypedDict(
     "AcceptGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcceptGrantResponseTypeDef = TypedDict(
+    "AcceptGrantResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutomatedDiscoveryInformationTypeDef = TypedDict(
     "AutomatedDiscoveryInformationTypeDef",
     {
         "LastRunTime": datetime,
@@ -223,19 +225,21 @@
     "_OptionalCheckInLicenseRequestRequestTypeDef",
     {
         "Beneficiary": str,
     },
     total=False,
 )
 
+
 class CheckInLicenseRequestRequestTypeDef(
     _RequiredCheckInLicenseRequestRequestTypeDef, _OptionalCheckInLicenseRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredEntitlementDataTypeDef = TypedDict(
     "_RequiredEntitlementDataTypeDef",
     {
         "Name": str,
         "Unit": EntitlementDataUnitType,
     },
 )
@@ -243,17 +247,19 @@
     "_OptionalEntitlementDataTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+
 class EntitlementDataTypeDef(_RequiredEntitlementDataTypeDef, _OptionalEntitlementDataTypeDef):
     pass
 
+
 MetadataTypeDef = TypedDict(
     "MetadataTypeDef",
     {
         "Name": str,
         "Value": str,
     },
     total=False,
@@ -283,56 +289,75 @@
         "LicenseArn": str,
         "Principals": Sequence[str],
         "HomeRegion": str,
         "AllowedOperations": Sequence[AllowedOperationType],
     },
 )
 
-_RequiredCreateGrantVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateGrantVersionRequestRequestTypeDef",
+CreateGrantResponseTypeDef = TypedDict(
+    "CreateGrantResponseTypeDef",
     {
-        "ClientToken": str,
         "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalCreateGrantVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateGrantVersionRequestRequestTypeDef",
+
+OptionsTypeDef = TypedDict(
+    "OptionsTypeDef",
     {
-        "GrantName": str,
-        "AllowedOperations": Sequence[AllowedOperationType],
-        "Status": GrantStatusType,
-        "StatusReason": str,
-        "SourceVersion": str,
+        "ActivationOverrideBehavior": ActivationOverrideBehaviorType,
     },
     total=False,
 )
 
-class CreateGrantVersionRequestRequestTypeDef(
-    _RequiredCreateGrantVersionRequestRequestTypeDef,
-    _OptionalCreateGrantVersionRequestRequestTypeDef,
-):
-    pass
+CreateGrantVersionResponseTypeDef = TypedDict(
+    "CreateGrantVersionResponseTypeDef",
+    {
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+CreateLicenseConfigurationResponseTypeDef = TypedDict(
+    "CreateLicenseConfigurationResponseTypeDef",
+    {
+        "LicenseConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LicenseConversionContextTypeDef = TypedDict(
     "LicenseConversionContextTypeDef",
     {
         "UsageOperation": str,
     },
     total=False,
 )
 
+CreateLicenseConversionTaskForResourceResponseTypeDef = TypedDict(
+    "CreateLicenseConversionTaskForResourceResponseTypeDef",
+    {
+        "LicenseConversionTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReportContextTypeDef = TypedDict(
     "ReportContextTypeDef",
     {
         "licenseConfigurationArns": Sequence[str],
     },
 )
 
@@ -341,31 +366,41 @@
     {
         "value": int,
         "period": ReportFrequencyTypeType,
     },
     total=False,
 )
 
+CreateLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
+    "CreateLicenseManagerReportGeneratorResponseTypeDef",
+    {
+        "LicenseManagerReportGeneratorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDatetimeRangeTypeDef = TypedDict(
     "_RequiredDatetimeRangeTypeDef",
     {
         "Begin": str,
     },
 )
 _OptionalDatetimeRangeTypeDef = TypedDict(
     "_OptionalDatetimeRangeTypeDef",
     {
         "End": str,
     },
     total=False,
 )
 
+
 class DatetimeRangeTypeDef(_RequiredDatetimeRangeTypeDef, _OptionalDatetimeRangeTypeDef):
     pass
 
+
 _RequiredEntitlementTypeDef = TypedDict(
     "_RequiredEntitlementTypeDef",
     {
         "Name": str,
         "Unit": EntitlementUnitType,
     },
 )
@@ -376,34 +411,58 @@
         "MaxCount": int,
         "Overage": bool,
         "AllowCheckIn": bool,
     },
     total=False,
 )
 
+
 class EntitlementTypeDef(_RequiredEntitlementTypeDef, _OptionalEntitlementTypeDef):
     pass
 
+
 _RequiredIssuerTypeDef = TypedDict(
     "_RequiredIssuerTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalIssuerTypeDef = TypedDict(
     "_OptionalIssuerTypeDef",
     {
         "SignKey": str,
     },
     total=False,
 )
 
+
 class IssuerTypeDef(_RequiredIssuerTypeDef, _OptionalIssuerTypeDef):
     pass
 
+
+CreateLicenseResponseTypeDef = TypedDict(
+    "CreateLicenseResponseTypeDef",
+    {
+        "LicenseArn": str,
+        "Status": LicenseStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLicenseVersionResponseTypeDef = TypedDict(
+    "CreateLicenseVersionResponseTypeDef",
+    {
+        "LicenseArn": str,
+        "Version": str,
+        "Status": LicenseStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTokenRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "ClientToken": str,
     },
 )
@@ -413,19 +472,31 @@
         "RoleArns": Sequence[str],
         "ExpirationInDays": int,
         "TokenProperties": Sequence[str],
     },
     total=False,
 )
 
+
 class CreateTokenRequestRequestTypeDef(
     _RequiredCreateTokenRequestRequestTypeDef, _OptionalCreateTokenRequestRequestTypeDef
 ):
     pass
 
+
+CreateTokenResponseTypeDef = TypedDict(
+    "CreateTokenResponseTypeDef",
+    {
+        "TokenId": str,
+        "TokenType": Literal["REFRESH_TOKEN"],
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteGrantRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
         "Version": str,
     },
 )
@@ -433,19 +504,31 @@
     "_OptionalDeleteGrantRequestRequestTypeDef",
     {
         "StatusReason": str,
     },
     total=False,
 )
 
+
 class DeleteGrantRequestRequestTypeDef(
     _RequiredDeleteGrantRequestRequestTypeDef, _OptionalDeleteGrantRequestRequestTypeDef
 ):
     pass
 
+
+DeleteGrantResponseTypeDef = TypedDict(
+    "DeleteGrantResponseTypeDef",
+    {
+        "GrantArn": str,
+        "Status": GrantStatusType,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 
@@ -460,14 +543,23 @@
     "DeleteLicenseRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "SourceVersion": str,
     },
 )
 
+DeleteLicenseResponseTypeDef = TypedDict(
+    "DeleteLicenseResponseTypeDef",
+    {
+        "Status": LicenseDeletionStatusType,
+        "DeletionDate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTokenRequestRequestTypeDef = TypedDict(
     "DeleteTokenRequestRequestTypeDef",
     {
         "TokenId": str,
     },
 )
 
@@ -483,37 +575,50 @@
     "_OptionalEntitlementUsageTypeDef",
     {
         "MaxCount": str,
     },
     total=False,
 )
 
+
 class EntitlementUsageTypeDef(_RequiredEntitlementUsageTypeDef, _OptionalEntitlementUsageTypeDef):
     pass
 
+
 _RequiredExtendLicenseConsumptionRequestRequestTypeDef = TypedDict(
     "_RequiredExtendLicenseConsumptionRequestRequestTypeDef",
     {
         "LicenseConsumptionToken": str,
     },
 )
 _OptionalExtendLicenseConsumptionRequestRequestTypeDef = TypedDict(
     "_OptionalExtendLicenseConsumptionRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
+
 class ExtendLicenseConsumptionRequestRequestTypeDef(
     _RequiredExtendLicenseConsumptionRequestRequestTypeDef,
     _OptionalExtendLicenseConsumptionRequestRequestTypeDef,
 ):
     pass
 
+
+ExtendLicenseConsumptionResponseTypeDef = TypedDict(
+    "ExtendLicenseConsumptionResponseTypeDef",
+    {
+        "LicenseConsumptionToken": str,
+        "Expiration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
     total=False,
@@ -529,62 +634,49 @@
     "_OptionalGetAccessTokenRequestRequestTypeDef",
     {
         "TokenProperties": Sequence[str],
     },
     total=False,
 )
 
+
 class GetAccessTokenRequestRequestTypeDef(
     _RequiredGetAccessTokenRequestRequestTypeDef, _OptionalGetAccessTokenRequestRequestTypeDef
 ):
     pass
 
+
+GetAccessTokenResponseTypeDef = TypedDict(
+    "GetAccessTokenResponseTypeDef",
+    {
+        "AccessToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetGrantRequestRequestTypeDef = TypedDict(
     "_RequiredGetGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
 _OptionalGetGrantRequestRequestTypeDef = TypedDict(
     "_OptionalGetGrantRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetGrantRequestRequestTypeDef(
     _RequiredGetGrantRequestRequestTypeDef, _OptionalGetGrantRequestRequestTypeDef
 ):
     pass
 
-_RequiredGrantTypeDef = TypedDict(
-    "_RequiredGrantTypeDef",
-    {
-        "GrantArn": str,
-        "GrantName": str,
-        "ParentArn": str,
-        "LicenseArn": str,
-        "GranteePrincipalArn": str,
-        "HomeRegion": str,
-        "GrantStatus": GrantStatusType,
-        "Version": str,
-        "GrantedOperations": List[AllowedOperationType],
-    },
-)
-_OptionalGrantTypeDef = TypedDict(
-    "_OptionalGrantTypeDef",
-    {
-        "StatusReason": str,
-    },
-    total=False,
-)
-
-class GrantTypeDef(_RequiredGrantTypeDef, _OptionalGrantTypeDef):
-    pass
 
 GetLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "GetLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
@@ -622,19 +714,21 @@
     "_OptionalGetLicenseRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetLicenseRequestRequestTypeDef(
     _RequiredGetLicenseRequestRequestTypeDef, _OptionalGetLicenseRequestRequestTypeDef
 ):
     pass
 
+
 GetLicenseUsageRequestRequestTypeDef = TypedDict(
     "GetLicenseUsageRequestRequestTypeDef",
     {
         "LicenseArn": str,
     },
 )
 
@@ -676,17 +770,19 @@
     "_OptionalInventoryFilterTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+
 class InventoryFilterTypeDef(_RequiredInventoryFilterTypeDef, _OptionalInventoryFilterTypeDef):
     pass
 
+
 LicenseConfigurationAssociationTypeDef = TypedDict(
     "LicenseConfigurationAssociationTypeDef",
     {
         "ResourceArn": str,
         "ResourceType": ResourceTypeType,
         "ResourceOwnerId": str,
         "AssociationTime": datetime,
@@ -718,29 +814,43 @@
     "_OptionalLicenseSpecificationTypeDef",
     {
         "AmiAssociationScope": str,
     },
     total=False,
 )
 
+
 class LicenseSpecificationTypeDef(
     _RequiredLicenseSpecificationTypeDef, _OptionalLicenseSpecificationTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "LicenseConfigurationArn": str,
+    },
+)
+_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef(
+    _RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
+    _OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 _OptionalListAssociationsForLicenseConfigurationRequestRequestTypeDef = TypedDict(
@@ -748,20 +858,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListAssociationsForLicenseConfigurationRequestRequestTypeDef(
     _RequiredListAssociationsForLicenseConfigurationRequestRequestTypeDef,
     _OptionalListAssociationsForLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef = TypedDict(
     "_RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
 _OptionalListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef = TypedDict(
@@ -769,20 +881,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef(
     _RequiredListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
     _OptionalListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef(
+    _RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
+    _OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListLicenseSpecificationsForResourceRequestRequestTypeDef = TypedDict(
@@ -790,20 +926,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListLicenseSpecificationsForResourceRequestRequestTypeDef(
     _RequiredListLicenseSpecificationsForResourceRequestRequestTypeDef,
     _OptionalListLicenseSpecificationsForResourceRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListLicenseVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListLicenseVersionsRequestRequestTypeDef",
     {
         "LicenseArn": str,
     },
 )
 _OptionalListLicenseVersionsRequestRequestTypeDef = TypedDict(
@@ -811,20 +949,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListLicenseVersionsRequestRequestTypeDef(
     _RequiredListLicenseVersionsRequestRequestTypeDef,
     _OptionalListLicenseVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 ResourceInventoryTypeDef = TypedDict(
     "ResourceInventoryTypeDef",
     {
         "ResourceId": str,
         "ResourceType": ResourceTypeType,
         "ResourceArn": str,
         "Platform": str,
@@ -851,14 +991,24 @@
         "TokenProperties": List[str],
         "RoleArns": List[str],
         "Status": str,
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
 _RequiredProductInformationFilterTypeDef = TypedDict(
     "_RequiredProductInformationFilterTypeDef",
     {
         "ProductInformationFilterName": str,
         "ProductInformationFilterComparator": str,
     },
 )
@@ -866,170 +1016,63 @@
     "_OptionalProductInformationFilterTypeDef",
     {
         "ProductInformationFilterValue": Sequence[str],
     },
     total=False,
 )
 
+
 class ProductInformationFilterTypeDef(
     _RequiredProductInformationFilterTypeDef, _OptionalProductInformationFilterTypeDef
 ):
     pass
 
+
 RejectGrantRequestRequestTypeDef = TypedDict(
     "RejectGrantRequestRequestTypeDef",
     {
         "GrantArn": str,
     },
 )
 
-S3LocationTypeDef = TypedDict(
-    "S3LocationTypeDef",
-    {
-        "bucket": str,
-        "keyPrefix": str,
-    },
-    total=False,
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-AcceptGrantResponseTypeDef = TypedDict(
-    "AcceptGrantResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantResponseTypeDef = TypedDict(
-    "CreateGrantResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantVersionResponseTypeDef = TypedDict(
-    "CreateGrantVersionResponseTypeDef",
-    {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseConfigurationResponseTypeDef = TypedDict(
-    "CreateLicenseConfigurationResponseTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseConversionTaskForResourceResponseTypeDef = TypedDict(
-    "CreateLicenseConversionTaskForResourceResponseTypeDef",
-    {
-        "LicenseConversionTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
-    "CreateLicenseManagerReportGeneratorResponseTypeDef",
-    {
-        "LicenseManagerReportGeneratorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseResponseTypeDef = TypedDict(
-    "CreateLicenseResponseTypeDef",
-    {
-        "LicenseArn": str,
-        "Status": LicenseStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLicenseVersionResponseTypeDef = TypedDict(
-    "CreateLicenseVersionResponseTypeDef",
-    {
-        "LicenseArn": str,
-        "Version": str,
-        "Status": LicenseStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTokenResponseTypeDef = TypedDict(
-    "CreateTokenResponseTypeDef",
-    {
-        "TokenId": str,
-        "TokenType": Literal["REFRESH_TOKEN"],
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGrantResponseTypeDef = TypedDict(
-    "DeleteGrantResponseTypeDef",
+RejectGrantResponseTypeDef = TypedDict(
+    "RejectGrantResponseTypeDef",
     {
         "GrantArn": str,
         "Status": GrantStatusType,
         "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteLicenseResponseTypeDef = TypedDict(
-    "DeleteLicenseResponseTypeDef",
-    {
-        "Status": LicenseDeletionStatusType,
-        "DeletionDate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExtendLicenseConsumptionResponseTypeDef = TypedDict(
-    "ExtendLicenseConsumptionResponseTypeDef",
+S3LocationTypeDef = TypedDict(
+    "S3LocationTypeDef",
     {
-        "LicenseConsumptionToken": str,
-        "Expiration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "bucket": str,
+        "keyPrefix": str,
     },
+    total=False,
 )
 
-GetAccessTokenResponseTypeDef = TypedDict(
-    "GetAccessTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "AccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-RejectGrantResponseTypeDef = TypedDict(
-    "RejectGrantResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "GrantArn": str,
-        "Status": GrantStatusType,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 _RequiredCheckoutLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCheckoutLicenseRequestRequestTypeDef",
     {
         "ProductSKU": str,
@@ -1044,31 +1087,33 @@
     {
         "Beneficiary": str,
         "NodeId": str,
     },
     total=False,
 )
 
+
 class CheckoutLicenseRequestRequestTypeDef(
     _RequiredCheckoutLicenseRequestRequestTypeDef, _OptionalCheckoutLicenseRequestRequestTypeDef
 ):
     pass
 
+
 CheckoutLicenseResponseTypeDef = TypedDict(
     "CheckoutLicenseResponseTypeDef",
     {
         "CheckoutType": CheckoutTypeType,
         "LicenseConsumptionToken": str,
         "EntitlementsAllowed": List[EntitlementDataTypeDef],
         "SignedToken": str,
         "NodeId": str,
         "IssuedAt": str,
         "Expiration": str,
         "LicenseArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCheckoutBorrowLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCheckoutBorrowLicenseRequestRequestTypeDef",
     {
         "LicenseArn": str,
@@ -1082,32 +1127,34 @@
     {
         "NodeId": str,
         "CheckoutMetadata": Sequence[MetadataTypeDef],
     },
     total=False,
 )
 
+
 class CheckoutBorrowLicenseRequestRequestTypeDef(
     _RequiredCheckoutBorrowLicenseRequestRequestTypeDef,
     _OptionalCheckoutBorrowLicenseRequestRequestTypeDef,
 ):
     pass
 
+
 CheckoutBorrowLicenseResponseTypeDef = TypedDict(
     "CheckoutBorrowLicenseResponseTypeDef",
     {
         "LicenseArn": str,
         "LicenseConsumptionToken": str,
         "EntitlementsAllowed": List[EntitlementDataTypeDef],
         "NodeId": str,
         "SignedToken": str,
         "IssuedAt": str,
         "Expiration": str,
         "CheckoutMetadata": List[MetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseOperationFailureTypeDef = TypedDict(
     "LicenseOperationFailureTypeDef",
     {
         "ResourceArn": str,
@@ -1128,19 +1175,75 @@
         "RenewType": RenewTypeType,
         "ProvisionalConfiguration": ProvisionalConfigurationTypeDef,
         "BorrowConfiguration": BorrowConfigurationTypeDef,
     },
     total=False,
 )
 
+_RequiredCreateGrantVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateGrantVersionRequestRequestTypeDef",
+    {
+        "ClientToken": str,
+        "GrantArn": str,
+    },
+)
+_OptionalCreateGrantVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateGrantVersionRequestRequestTypeDef",
+    {
+        "GrantName": str,
+        "AllowedOperations": Sequence[AllowedOperationType],
+        "Status": GrantStatusType,
+        "StatusReason": str,
+        "SourceVersion": str,
+        "Options": OptionsTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateGrantVersionRequestRequestTypeDef(
+    _RequiredCreateGrantVersionRequestRequestTypeDef,
+    _OptionalCreateGrantVersionRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredGrantTypeDef = TypedDict(
+    "_RequiredGrantTypeDef",
+    {
+        "GrantArn": str,
+        "GrantName": str,
+        "ParentArn": str,
+        "LicenseArn": str,
+        "GranteePrincipalArn": str,
+        "HomeRegion": str,
+        "GrantStatus": GrantStatusType,
+        "Version": str,
+        "GrantedOperations": List[AllowedOperationType],
+    },
+)
+_OptionalGrantTypeDef = TypedDict(
+    "_OptionalGrantTypeDef",
+    {
+        "StatusReason": str,
+        "Options": OptionsTypeDef,
+    },
+    total=False,
+)
+
+
+class GrantTypeDef(_RequiredGrantTypeDef, _OptionalGrantTypeDef):
+    pass
+
+
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
         "ResourceArn": str,
@@ -1165,15 +1268,15 @@
         "SourceLicenseContext": LicenseConversionContextTypeDef,
         "DestinationLicenseContext": LicenseConversionContextTypeDef,
         "StatusMessage": str,
         "Status": LicenseConversionTaskStatusType,
         "StartTime": datetime,
         "LicenseConversionTime": datetime,
         "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseConversionTaskTypeDef = TypedDict(
     "LicenseConversionTaskTypeDef",
     {
         "LicenseConversionTaskId": str,
@@ -1204,20 +1307,22 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateLicenseManagerReportGeneratorRequestRequestTypeDef(
     _RequiredCreateLicenseManagerReportGeneratorRequestRequestTypeDef,
     _OptionalCreateLicenseManagerReportGeneratorRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     {
         "LicenseManagerReportGeneratorArn": str,
         "ReportGeneratorName": str,
         "Type": Sequence[ReportTypeType],
         "ReportContext": ReportContextTypeDef,
@@ -1229,20 +1334,22 @@
     "_OptionalUpdateLicenseManagerReportGeneratorRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateLicenseManagerReportGeneratorRequestRequestTypeDef(
     _RequiredUpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
     _OptionalUpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
 ):
     pass
 
+
 LicenseUsageTypeDef = TypedDict(
     "LicenseUsageTypeDef",
     {
         "EntitlementUsages": List[EntitlementUsageTypeDef],
     },
     total=False,
 )
@@ -1254,14 +1361,24 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef = TypedDict(
+    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
+    {
+        "LicenseConfigurationArns": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLicenseConfigurationsRequestRequestTypeDef = TypedDict(
     "ListLicenseConfigurationsRequestRequestTypeDef",
     {
         "LicenseConfigurationArns": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
@@ -1312,20 +1429,22 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListReceivedGrantsForOrganizationRequestRequestTypeDef(
     _RequiredListReceivedGrantsForOrganizationRequestRequestTypeDef,
     _OptionalListReceivedGrantsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
+
 ListReceivedGrantsRequestRequestTypeDef = TypedDict(
     "ListReceivedGrantsRequestRequestTypeDef",
     {
         "GrantArns": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
@@ -1361,94 +1480,93 @@
         "Filters": Sequence[FilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef",
+_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     {
         "LicenseConfigurationArn": str,
     },
 )
-_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef",
+_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
+    "_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListUsageForLicenseConfigurationRequestRequestTypeDef(
-    _RequiredListUsageForLicenseConfigurationRequestRequestTypeDef,
-    _OptionalListUsageForLicenseConfigurationRequestRequestTypeDef,
+
+class ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef(
+    _RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
+    _OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
 ):
     pass
 
-GetGrantResponseTypeDef = TypedDict(
-    "GetGrantResponseTypeDef",
-    {
-        "Grant": GrantTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListDistributedGrantsResponseTypeDef = TypedDict(
-    "ListDistributedGrantsResponseTypeDef",
+_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsageForLicenseConfigurationRequestRequestTypeDef",
     {
-        "Grants": List[GrantTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "LicenseConfigurationArn": str,
     },
 )
-
-ListReceivedGrantsForOrganizationResponseTypeDef = TypedDict(
-    "ListReceivedGrantsForOrganizationResponseTypeDef",
+_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsageForLicenseConfigurationRequestRequestTypeDef",
     {
-        "Grants": List[GrantTypeDef],
+        "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filters": Sequence[FilterTypeDef],
     },
+    total=False,
 )
 
-ListReceivedGrantsResponseTypeDef = TypedDict(
-    "ListReceivedGrantsResponseTypeDef",
-    {
-        "Grants": List[GrantTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+
+class ListUsageForLicenseConfigurationRequestRequestTypeDef(
+    _RequiredListUsageForLicenseConfigurationRequestRequestTypeDef,
+    _OptionalListUsageForLicenseConfigurationRequestRequestTypeDef,
+):
+    pass
+
 
 GetServiceSettingsResponseTypeDef = TypedDict(
     "GetServiceSettingsResponseTypeDef",
     {
         "S3BucketArn": str,
         "SnsTopicArn": str,
         "OrganizationConfiguration": OrganizationConfigurationTypeDef,
         "EnableCrossAccountsDiscovery": bool,
         "LicenseManagerResourceShareArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceSettingsRequestRequestTypeDef = TypedDict(
     "UpdateServiceSettingsRequestRequestTypeDef",
     {
         "S3BucketArn": str,
         "SnsTopicArn": str,
         "OrganizationConfiguration": OrganizationConfigurationTypeDef,
         "EnableCrossAccountsDiscovery": bool,
     },
     total=False,
 )
 
+ListResourceInventoryRequestListResourceInventoryPaginateTypeDef = TypedDict(
+    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
+    {
+        "Filters": Sequence[InventoryFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceInventoryRequestRequestTypeDef = TypedDict(
     "ListResourceInventoryRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[InventoryFilterTypeDef],
     },
@@ -1456,33 +1574,33 @@
 )
 
 ListAssociationsForLicenseConfigurationResponseTypeDef = TypedDict(
     "ListAssociationsForLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationAssociations": List[LicenseConfigurationAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsageForLicenseConfigurationResponseTypeDef = TypedDict(
     "ListUsageForLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationUsageList": List[LicenseConfigurationUsageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseSpecificationsForResourceResponseTypeDef = TypedDict(
     "ListLicenseSpecificationsForResourceResponseTypeDef",
     {
         "LicenseSpecifications": List[LicenseSpecificationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1493,115 +1611,37 @@
     {
         "AddLicenseSpecifications": Sequence[LicenseSpecificationTypeDef],
         "RemoveLicenseSpecifications": Sequence[LicenseSpecificationTypeDef],
     },
     total=False,
 )
 
+
 class UpdateLicenseSpecificationsForResourceRequestRequestTypeDef(
     _RequiredUpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
     _OptionalUpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
 ):
     pass
 
-_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-    },
-)
-_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef(
-    _RequiredListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-    _OptionalListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-):
-    pass
-
-ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef = TypedDict(
-    "ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef",
-    {
-        "LicenseConfigurationArns": Sequence[str],
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef(
-    _RequiredListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-    _OptionalListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-):
-    pass
-
-ListResourceInventoryRequestListResourceInventoryPaginateTypeDef = TypedDict(
-    "ListResourceInventoryRequestListResourceInventoryPaginateTypeDef",
-    {
-        "Filters": Sequence[InventoryFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
-    {
-        "LicenseConfigurationArn": str,
-    },
-)
-_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef = TypedDict(
-    "_OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef(
-    _RequiredListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
-    _OptionalListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
-):
-    pass
 
 ListResourceInventoryResponseTypeDef = TypedDict(
     "ListResourceInventoryResponseTypeDef",
     {
         "ResourceInventoryList": List[ResourceInventoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTokensResponseTypeDef = TypedDict(
     "ListTokensResponseTypeDef",
     {
         "Tokens": List[TokenDataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProductInformationTypeDef = TypedDict(
     "ProductInformationTypeDef",
     {
         "ResourceType": str,
@@ -1630,15 +1670,15 @@
 )
 
 ListFailuresForLicenseConfigurationOperationsResponseTypeDef = TypedDict(
     "ListFailuresForLicenseConfigurationOperationsResponseTypeDef",
     {
         "LicenseOperationFailureList": List[LicenseOperationFailureTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLicenseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseRequestRequestTypeDef",
     {
         "LicenseName": str,
@@ -1657,19 +1697,21 @@
     "_OptionalCreateLicenseRequestRequestTypeDef",
     {
         "LicenseMetadata": Sequence[MetadataTypeDef],
     },
     total=False,
 )
 
+
 class CreateLicenseRequestRequestTypeDef(
     _RequiredCreateLicenseRequestRequestTypeDef, _OptionalCreateLicenseRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateLicenseVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseVersionRequestRequestTypeDef",
     {
         "LicenseArn": str,
         "LicenseName": str,
         "ProductName": str,
         "Issuer": IssuerTypeDef,
@@ -1686,20 +1728,22 @@
     {
         "LicenseMetadata": Sequence[MetadataTypeDef],
         "SourceVersion": str,
     },
     total=False,
 )
 
+
 class CreateLicenseVersionRequestRequestTypeDef(
     _RequiredCreateLicenseVersionRequestRequestTypeDef,
     _OptionalCreateLicenseVersionRequestRequestTypeDef,
 ):
     pass
 
+
 GrantedLicenseTypeDef = TypedDict(
     "GrantedLicenseTypeDef",
     {
         "LicenseArn": str,
         "LicenseName": str,
         "ProductName": str,
         "ProductSKU": str,
@@ -1735,28 +1779,63 @@
         "LicenseMetadata": List[MetadataTypeDef],
         "CreateTime": str,
         "Version": str,
     },
     total=False,
 )
 
+GetGrantResponseTypeDef = TypedDict(
+    "GetGrantResponseTypeDef",
+    {
+        "Grant": GrantTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDistributedGrantsResponseTypeDef = TypedDict(
+    "ListDistributedGrantsResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceivedGrantsForOrganizationResponseTypeDef = TypedDict(
+    "ListReceivedGrantsForOrganizationResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceivedGrantsResponseTypeDef = TypedDict(
+    "ListReceivedGrantsResponseTypeDef",
+    {
+        "Grants": List[GrantTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListLicenseConversionTasksResponseTypeDef = TypedDict(
     "ListLicenseConversionTasksResponseTypeDef",
     {
         "LicenseConversionTasks": List[LicenseConversionTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLicenseUsageResponseTypeDef = TypedDict(
     "GetLicenseUsageResponseTypeDef",
     {
         "LicenseUsage": LicenseUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLicenseConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLicenseConfigurationRequestRequestTypeDef",
     {
         "Name": str,
@@ -1773,20 +1852,22 @@
         "Tags": Sequence[TagTypeDef],
         "DisassociateWhenNotFound": bool,
         "ProductInformationList": Sequence[ProductInformationTypeDef],
     },
     total=False,
 )
 
+
 class CreateLicenseConfigurationRequestRequestTypeDef(
     _RequiredCreateLicenseConfigurationRequestRequestTypeDef,
     _OptionalCreateLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetLicenseConfigurationResponseTypeDef = TypedDict(
     "GetLicenseConfigurationResponseTypeDef",
     {
         "LicenseConfigurationId": str,
         "LicenseConfigurationArn": str,
         "Name": str,
         "Description": str,
@@ -1799,15 +1880,15 @@
         "OwnerAccountId": str,
         "ConsumedLicenseSummaryList": List[ConsumedLicenseSummaryTypeDef],
         "ManagedResourceSummaryList": List[ManagedResourceSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "ProductInformationList": List[ProductInformationTypeDef],
         "AutomatedDiscoveryInformation": AutomatedDiscoveryInformationTypeDef,
         "DisassociateWhenNotFound": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LicenseConfigurationTypeDef = TypedDict(
     "LicenseConfigurationTypeDef",
     {
         "LicenseConfigurationId": str,
@@ -1847,82 +1928,84 @@
         "Description": str,
         "ProductInformationList": Sequence[ProductInformationTypeDef],
         "DisassociateWhenNotFound": bool,
     },
     total=False,
 )
 
+
 class UpdateLicenseConfigurationRequestRequestTypeDef(
     _RequiredUpdateLicenseConfigurationRequestRequestTypeDef,
     _OptionalUpdateLicenseConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetLicenseManagerReportGeneratorResponseTypeDef = TypedDict(
     "GetLicenseManagerReportGeneratorResponseTypeDef",
     {
         "ReportGenerator": ReportGeneratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseManagerReportGeneratorsResponseTypeDef = TypedDict(
     "ListLicenseManagerReportGeneratorsResponseTypeDef",
     {
         "ReportGenerators": List[ReportGeneratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReceivedLicensesForOrganizationResponseTypeDef = TypedDict(
     "ListReceivedLicensesForOrganizationResponseTypeDef",
     {
         "Licenses": List[GrantedLicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReceivedLicensesResponseTypeDef = TypedDict(
     "ListReceivedLicensesResponseTypeDef",
     {
         "Licenses": List[GrantedLicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLicenseResponseTypeDef = TypedDict(
     "GetLicenseResponseTypeDef",
     {
         "License": LicenseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseVersionsResponseTypeDef = TypedDict(
     "ListLicenseVersionsResponseTypeDef",
     {
         "Licenses": List[LicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicensesResponseTypeDef = TypedDict(
     "ListLicensesResponseTypeDef",
     {
         "Licenses": List[LicenseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLicenseConfigurationsResponseTypeDef = TypedDict(
     "ListLicenseConfigurationsResponseTypeDef",
     {
         "LicenseConfigurations": List[LicenseConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/PKG-INFO` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager"></a>
 
 # types-aiobotocore-license-manager
 
 [![PyPI - types-aiobotocore-license-manager](https://img.shields.io/pypi/v/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
+[aiobotocore.LicenseManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager.html#LicenseManager)
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
 [types-aiobotocore-license-manager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,14 +312,15 @@
 ### Literals
 
 `types_aiobotocore_license_manager.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_license_manager.literals import (
+    ActivationOverrideBehaviorType,
     AllowedOperationType,
     CheckoutTypeType,
     DigitalSignatureMethodType,
     EntitlementDataUnitType,
     EntitlementUnitType,
     GrantStatusType,
     InventoryFilterConditionType,
@@ -343,146 +344,147 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AllowedOperationType) -> bool:
+def check_value(value: ActivationOverrideBehaviorType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_license_manager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_license_manager.type_defs import (
     AcceptGrantRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptGrantResponseTypeDef,
     AutomatedDiscoveryInformationTypeDef,
     BorrowConfigurationTypeDef,
     CheckInLicenseRequestRequestTypeDef,
     EntitlementDataTypeDef,
     MetadataTypeDef,
     ConsumedLicenseSummaryTypeDef,
     ProvisionalConfigurationTypeDef,
     CreateGrantRequestRequestTypeDef,
-    CreateGrantVersionRequestRequestTypeDef,
+    CreateGrantResponseTypeDef,
+    OptionsTypeDef,
+    CreateGrantVersionResponseTypeDef,
     TagTypeDef,
+    CreateLicenseConfigurationResponseTypeDef,
     LicenseConversionContextTypeDef,
+    CreateLicenseConversionTaskForResourceResponseTypeDef,
     ReportContextTypeDef,
     ReportFrequencyTypeDef,
+    CreateLicenseManagerReportGeneratorResponseTypeDef,
     DatetimeRangeTypeDef,
     EntitlementTypeDef,
     IssuerTypeDef,
+    CreateLicenseResponseTypeDef,
+    CreateLicenseVersionResponseTypeDef,
     CreateTokenRequestRequestTypeDef,
+    CreateTokenResponseTypeDef,
     DeleteGrantRequestRequestTypeDef,
+    DeleteGrantResponseTypeDef,
     DeleteLicenseConfigurationRequestRequestTypeDef,
     DeleteLicenseManagerReportGeneratorRequestRequestTypeDef,
     DeleteLicenseRequestRequestTypeDef,
+    DeleteLicenseResponseTypeDef,
     DeleteTokenRequestRequestTypeDef,
     EntitlementUsageTypeDef,
     ExtendLicenseConsumptionRequestRequestTypeDef,
+    ExtendLicenseConsumptionResponseTypeDef,
     FilterTypeDef,
     GetAccessTokenRequestRequestTypeDef,
+    GetAccessTokenResponseTypeDef,
     GetGrantRequestRequestTypeDef,
-    GrantTypeDef,
     GetLicenseConfigurationRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
     GetLicenseConversionTaskRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorRequestRequestTypeDef,
     GetLicenseRequestRequestTypeDef,
     GetLicenseUsageRequestRequestTypeDef,
     OrganizationConfigurationTypeDef,
     IssuerDetailsTypeDef,
     ReceivedMetadataTypeDef,
     InventoryFilterTypeDef,
     LicenseConfigurationAssociationTypeDef,
     LicenseConfigurationUsageTypeDef,
     LicenseSpecificationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
     ListAssociationsForLicenseConfigurationRequestRequestTypeDef,
     ListFailuresForLicenseConfigurationOperationsRequestRequestTypeDef,
+    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
     ListLicenseSpecificationsForResourceRequestRequestTypeDef,
     ListLicenseVersionsRequestRequestTypeDef,
     ResourceInventoryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TokenDataTypeDef,
+    PaginatorConfigTypeDef,
     ProductInformationFilterTypeDef,
     RejectGrantRequestRequestTypeDef,
+    RejectGrantResponseTypeDef,
     S3LocationTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceptGrantResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    CreateGrantVersionResponseTypeDef,
-    CreateLicenseConfigurationResponseTypeDef,
-    CreateLicenseConversionTaskForResourceResponseTypeDef,
-    CreateLicenseManagerReportGeneratorResponseTypeDef,
-    CreateLicenseResponseTypeDef,
-    CreateLicenseVersionResponseTypeDef,
-    CreateTokenResponseTypeDef,
-    DeleteGrantResponseTypeDef,
-    DeleteLicenseResponseTypeDef,
-    ExtendLicenseConsumptionResponseTypeDef,
-    GetAccessTokenResponseTypeDef,
-    RejectGrantResponseTypeDef,
     CheckoutLicenseRequestRequestTypeDef,
     CheckoutLicenseResponseTypeDef,
     CheckoutBorrowLicenseRequestRequestTypeDef,
     CheckoutBorrowLicenseResponseTypeDef,
     LicenseOperationFailureTypeDef,
     ConsumptionConfigurationTypeDef,
+    CreateGrantVersionRequestRequestTypeDef,
+    GrantTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateLicenseConversionTaskForResourceRequestRequestTypeDef,
     GetLicenseConversionTaskResponseTypeDef,
     LicenseConversionTaskTypeDef,
     CreateLicenseManagerReportGeneratorRequestRequestTypeDef,
     UpdateLicenseManagerReportGeneratorRequestRequestTypeDef,
     LicenseUsageTypeDef,
     ListDistributedGrantsRequestRequestTypeDef,
+    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
     ListLicenseConfigurationsRequestRequestTypeDef,
     ListLicenseConversionTasksRequestRequestTypeDef,
     ListLicenseManagerReportGeneratorsRequestRequestTypeDef,
     ListLicensesRequestRequestTypeDef,
     ListReceivedGrantsForOrganizationRequestRequestTypeDef,
     ListReceivedGrantsRequestRequestTypeDef,
     ListReceivedLicensesForOrganizationRequestRequestTypeDef,
     ListReceivedLicensesRequestRequestTypeDef,
     ListTokensRequestRequestTypeDef,
+    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListUsageForLicenseConfigurationRequestRequestTypeDef,
-    GetGrantResponseTypeDef,
-    ListDistributedGrantsResponseTypeDef,
-    ListReceivedGrantsForOrganizationResponseTypeDef,
-    ListReceivedGrantsResponseTypeDef,
     GetServiceSettingsResponseTypeDef,
     UpdateServiceSettingsRequestRequestTypeDef,
+    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
     ListResourceInventoryRequestRequestTypeDef,
     ListAssociationsForLicenseConfigurationResponseTypeDef,
     ListUsageForLicenseConfigurationResponseTypeDef,
     ListLicenseSpecificationsForResourceResponseTypeDef,
     UpdateLicenseSpecificationsForResourceRequestRequestTypeDef,
-    ListAssociationsForLicenseConfigurationRequestListAssociationsForLicenseConfigurationPaginateTypeDef,
-    ListLicenseConfigurationsRequestListLicenseConfigurationsPaginateTypeDef,
-    ListLicenseSpecificationsForResourceRequestListLicenseSpecificationsForResourcePaginateTypeDef,
-    ListResourceInventoryRequestListResourceInventoryPaginateTypeDef,
-    ListUsageForLicenseConfigurationRequestListUsageForLicenseConfigurationPaginateTypeDef,
     ListResourceInventoryResponseTypeDef,
     ListTokensResponseTypeDef,
     ProductInformationTypeDef,
     ReportGeneratorTypeDef,
     ListFailuresForLicenseConfigurationOperationsResponseTypeDef,
     CreateLicenseRequestRequestTypeDef,
     CreateLicenseVersionRequestRequestTypeDef,
     GrantedLicenseTypeDef,
     LicenseTypeDef,
+    GetGrantResponseTypeDef,
+    ListDistributedGrantsResponseTypeDef,
+    ListReceivedGrantsForOrganizationResponseTypeDef,
+    ListReceivedGrantsResponseTypeDef,
     ListLicenseConversionTasksResponseTypeDef,
     GetLicenseUsageResponseTypeDef,
     CreateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseConfigurationResponseTypeDef,
     LicenseConfigurationTypeDef,
     UpdateLicenseConfigurationRequestRequestTypeDef,
     GetLicenseManagerReportGeneratorResponseTypeDef,
@@ -503,43 +505,43 @@
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

### Comparing `types-aiobotocore-license-manager-2.5.0.post1/types_aiobotocore_license_manager.egg-info/SOURCES.txt` & `types-aiobotocore-license-manager-2.5.1/types_aiobotocore_license_manager.egg-info/SOURCES.txt`

 * *Files identical despite different names*

