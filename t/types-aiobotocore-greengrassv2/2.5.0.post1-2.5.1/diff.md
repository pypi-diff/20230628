# Comparing `tmp/types-aiobotocore-greengrassv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-greengrassv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-greengrassv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:41 2023, max compression
+gzip compressed data, was "types-aiobotocore-greengrassv2-2.5.1.tar", last modified: Wed Jun 28 01:43:33 2023, max compression
```

## Comparing `types-aiobotocore-greengrassv2-2.5.0.post1.tar` & `types-aiobotocore-greengrassv2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.851248 types-aiobotocore-greengrassv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19479 2023-03-11 12:26:41.851248 types-aiobotocore-greengrassv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17888 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:41.851248 types-aiobotocore-greengrassv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.851248 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/
--rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27509 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27464 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10826 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10824 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10031 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10021 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    37169 2023-03-11 12:15:27.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    37136 2023-03-11 12:15:27.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:26.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.851248 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19479 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:41.000000 types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.746144 types-aiobotocore-greengrassv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19476 2023-06-28 01:43:33.746144 types-aiobotocore-greengrassv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17891 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:33.746144 types-aiobotocore-greengrassv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.746144 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/
+-rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27509 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27464 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11048 2023-06-28 01:32:02.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11046 2023-06-28 01:32:02.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9925 2023-06-28 01:32:02.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9916 2023-06-28 01:32:02.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    37233 2023-06-28 01:32:03.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37200 2023-06-28 01:32:03.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:01.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.746144 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19476 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:33.000000 types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/LICENSE` & `types-aiobotocore-greengrassv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-greengrassv2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-greengrassv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GreengrassV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GreengrassV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-greengrassv2"></a>
 
 # types-aiobotocore-greengrassv2
 
 [![PyPI - types-aiobotocore-greengrassv2](https://img.shields.io/pypi/v/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-greengrassv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-greengrassv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GreengrassV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
+[aiobotocore.GreengrassV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
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
 [types-aiobotocore-greengrassv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,73 +366,80 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_greengrassv2.type_defs import (
     AssociateClientDeviceWithCoreDeviceEntryTypeDef,
     AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef,
     AssociateServiceRoleToAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateServiceRoleToAccountResponseTypeDef,
     AssociatedClientDeviceTypeDef,
     DisassociateClientDeviceFromCoreDeviceEntryTypeDef,
     DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef,
     CancelDeploymentRequestRequestTypeDef,
+    CancelDeploymentResponseTypeDef,
     CloudComponentStatusTypeDef,
     ComponentCandidateTypeDef,
     ComponentConfigurationUpdateTypeDef,
     ComponentDependencyRequirementTypeDef,
     ComponentPlatformTypeDef,
     SystemResourceLimitsTypeDef,
     ComponentVersionListItemTypeDef,
     ConnectivityInfoTypeDef,
     CoreDeviceTypeDef,
+    CreateDeploymentResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteCoreDeviceRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeploymentComponentUpdatePolicyTypeDef,
     DeploymentConfigurationValidationPolicyTypeDef,
     IoTJobTimeoutConfigTypeDef,
     DeploymentTypeDef,
     DescribeComponentRequestRequestTypeDef,
+    DisassociateServiceRoleFromAccountResponseTypeDef,
     EffectiveDeploymentStatusDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetComponentVersionArtifactRequestRequestTypeDef,
+    GetComponentVersionArtifactResponseTypeDef,
     GetConnectivityInfoRequestRequestTypeDef,
     GetCoreDeviceRequestRequestTypeDef,
+    GetCoreDeviceResponseTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetServiceRoleForAccountResponseTypeDef,
     InstalledComponentTypeDef,
     IoTJobAbortCriteriaTypeDef,
     IoTJobRateIncreaseCriteriaTypeDef,
     LambdaDeviceMountTypeDef,
     LambdaVolumeMountTypeDef,
     LambdaEventSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
+    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
     ListComponentVersionsRequestRequestTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
     ListCoreDevicesRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
     ListEffectiveDeploymentsRequestRequestTypeDef,
+    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ListInstalledComponentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResolvedComponentVersionTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectivityInfoResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
-    AssociateServiceRoleToAccountResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef,
-    CancelDeploymentResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    DisassociateServiceRoleFromAccountResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetComponentResponseTypeDef,
-    GetComponentVersionArtifactResponseTypeDef,
-    GetCoreDeviceResponseTypeDef,
-    GetServiceRoleForAccountResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateConnectivityInfoResponseTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef,
     CreateComponentVersionResponseTypeDef,
     ComponentLatestVersionTypeDef,
     DescribeComponentResponseTypeDef,
     ResolveComponentCandidatesRequestRequestTypeDef,
@@ -444,21 +451,14 @@
     DeploymentPoliciesTypeDef,
     ListDeploymentsResponseTypeDef,
     EffectiveDeploymentTypeDef,
     ListInstalledComponentsResponseTypeDef,
     IoTJobAbortConfigTypeDef,
     IoTJobExponentialRolloutRateTypeDef,
     LambdaContainerParamsTypeDef,
-    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ResolveComponentCandidatesResponseTypeDef,
     ComponentTypeDef,
     ComponentDeploymentSpecificationTypeDef,
     ListEffectiveDeploymentsResponseTypeDef,
     IoTJobExecutionsRolloutConfigTypeDef,
     LambdaLinuxProcessParamsTypeDef,
     ListComponentsResponseTypeDef,
@@ -478,43 +478,43 @@
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/README.md` & `types-aiobotocore-greengrassv2-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-greengrassv2"></a>
 
 # types-aiobotocore-greengrassv2
 
 [![PyPI - types-aiobotocore-greengrassv2](https://img.shields.io/pypi/v/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-greengrassv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-greengrassv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GreengrassV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
+[aiobotocore.GreengrassV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
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
 [types-aiobotocore-greengrassv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -333,73 +333,80 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_greengrassv2.type_defs import (
     AssociateClientDeviceWithCoreDeviceEntryTypeDef,
     AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef,
     AssociateServiceRoleToAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateServiceRoleToAccountResponseTypeDef,
     AssociatedClientDeviceTypeDef,
     DisassociateClientDeviceFromCoreDeviceEntryTypeDef,
     DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef,
     CancelDeploymentRequestRequestTypeDef,
+    CancelDeploymentResponseTypeDef,
     CloudComponentStatusTypeDef,
     ComponentCandidateTypeDef,
     ComponentConfigurationUpdateTypeDef,
     ComponentDependencyRequirementTypeDef,
     ComponentPlatformTypeDef,
     SystemResourceLimitsTypeDef,
     ComponentVersionListItemTypeDef,
     ConnectivityInfoTypeDef,
     CoreDeviceTypeDef,
+    CreateDeploymentResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteCoreDeviceRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeploymentComponentUpdatePolicyTypeDef,
     DeploymentConfigurationValidationPolicyTypeDef,
     IoTJobTimeoutConfigTypeDef,
     DeploymentTypeDef,
     DescribeComponentRequestRequestTypeDef,
+    DisassociateServiceRoleFromAccountResponseTypeDef,
     EffectiveDeploymentStatusDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetComponentVersionArtifactRequestRequestTypeDef,
+    GetComponentVersionArtifactResponseTypeDef,
     GetConnectivityInfoRequestRequestTypeDef,
     GetCoreDeviceRequestRequestTypeDef,
+    GetCoreDeviceResponseTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetServiceRoleForAccountResponseTypeDef,
     InstalledComponentTypeDef,
     IoTJobAbortCriteriaTypeDef,
     IoTJobRateIncreaseCriteriaTypeDef,
     LambdaDeviceMountTypeDef,
     LambdaVolumeMountTypeDef,
     LambdaEventSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
+    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
     ListComponentVersionsRequestRequestTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
     ListCoreDevicesRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
     ListEffectiveDeploymentsRequestRequestTypeDef,
+    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ListInstalledComponentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResolvedComponentVersionTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectivityInfoResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
-    AssociateServiceRoleToAccountResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef,
-    CancelDeploymentResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    DisassociateServiceRoleFromAccountResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetComponentResponseTypeDef,
-    GetComponentVersionArtifactResponseTypeDef,
-    GetCoreDeviceResponseTypeDef,
-    GetServiceRoleForAccountResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateConnectivityInfoResponseTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef,
     CreateComponentVersionResponseTypeDef,
     ComponentLatestVersionTypeDef,
     DescribeComponentResponseTypeDef,
     ResolveComponentCandidatesRequestRequestTypeDef,
@@ -411,21 +418,14 @@
     DeploymentPoliciesTypeDef,
     ListDeploymentsResponseTypeDef,
     EffectiveDeploymentTypeDef,
     ListInstalledComponentsResponseTypeDef,
     IoTJobAbortConfigTypeDef,
     IoTJobExponentialRolloutRateTypeDef,
     LambdaContainerParamsTypeDef,
-    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ResolveComponentCandidatesResponseTypeDef,
     ComponentTypeDef,
     ComponentDeploymentSpecificationTypeDef,
     ListEffectiveDeploymentsResponseTypeDef,
     IoTJobExecutionsRolloutConfigTypeDef,
     LambdaLinuxProcessParamsTypeDef,
     ListComponentsResponseTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/setup.py` & `types-aiobotocore-greengrassv2-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-greengrassv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-greengrassv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_greengrassv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.GreengrassV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.GreengrassV2 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/"
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__init__.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__init__.pyi` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/__main__.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.GreengrassV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.GreengrassV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2\nOther"
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/client.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/client.pyi` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/literals.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -59,15 +59,15 @@
 ComponentVisibilityScopeType = Literal["PRIVATE", "PUBLIC"]
 CoreDeviceStatusType = Literal["HEALTHY", "UNHEALTHY"]
 DeploymentComponentUpdatePolicyActionType = Literal["NOTIFY_COMPONENTS", "SKIP_NOTIFY_COMPONENTS"]
 DeploymentFailureHandlingPolicyType = Literal["DO_NOTHING", "ROLLBACK"]
 DeploymentHistoryFilterType = Literal["ALL", "LATEST_ONLY"]
 DeploymentStatusType = Literal["ACTIVE", "CANCELED", "COMPLETED", "FAILED", "INACTIVE"]
 EffectiveDeploymentExecutionStatusType = Literal[
-    "CANCELED", "COMPLETED", "FAILED", "IN_PROGRESS", "QUEUED", "REJECTED", "TIMED_OUT"
+    "CANCELED", "COMPLETED", "FAILED", "IN_PROGRESS", "QUEUED", "REJECTED", "SUCCEEDED", "TIMED_OUT"
 ]
 InstalledComponentLifecycleStateType = Literal[
     "BROKEN", "ERRORED", "FINISHED", "INSTALLED", "NEW", "RUNNING", "STARTING", "STOPPING"
 ]
 InstalledComponentTopologyFilterType = Literal["ALL", "ROOT"]
 IoTJobAbortActionType = Literal["CANCEL"]
 IoTJobExecutionFailureTypeType = Literal["ALL", "FAILED", "REJECTED", "TIMED_OUT"]
@@ -145,14 +145,15 @@
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
@@ -231,14 +232,15 @@
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
@@ -249,14 +251,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -318,16 +322,19 @@
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
@@ -411,15 +418,17 @@
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/literals.pyi` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -57,15 +57,15 @@
 ComponentVisibilityScopeType = Literal["PRIVATE", "PUBLIC"]
 CoreDeviceStatusType = Literal["HEALTHY", "UNHEALTHY"]
 DeploymentComponentUpdatePolicyActionType = Literal["NOTIFY_COMPONENTS", "SKIP_NOTIFY_COMPONENTS"]
 DeploymentFailureHandlingPolicyType = Literal["DO_NOTHING", "ROLLBACK"]
 DeploymentHistoryFilterType = Literal["ALL", "LATEST_ONLY"]
 DeploymentStatusType = Literal["ACTIVE", "CANCELED", "COMPLETED", "FAILED", "INACTIVE"]
 EffectiveDeploymentExecutionStatusType = Literal[
-    "CANCELED", "COMPLETED", "FAILED", "IN_PROGRESS", "QUEUED", "REJECTED", "TIMED_OUT"
+    "CANCELED", "COMPLETED", "FAILED", "IN_PROGRESS", "QUEUED", "REJECTED", "SUCCEEDED", "TIMED_OUT"
 ]
 InstalledComponentLifecycleStateType = Literal[
     "BROKEN", "ERRORED", "FINISHED", "INSTALLED", "NEW", "RUNNING", "STARTING", "STOPPING"
 ]
 InstalledComponentTopologyFilterType = Literal["ALL", "ROOT"]
 IoTJobAbortActionType = Literal["CANCEL"]
 IoTJobExecutionFailureTypeType = Literal["ALL", "FAILED", "REJECTED", "TIMED_OUT"]
@@ -143,14 +143,15 @@
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
@@ -229,14 +230,15 @@
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
@@ -247,14 +249,15 @@
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
@@ -290,14 +293,15 @@
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
@@ -316,16 +320,19 @@
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
@@ -409,15 +416,17 @@
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/paginator.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_core_devices_paginator: ListCoreDevicesPaginator = client.get_paginator("list_core_devices")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_effective_deployments_paginator: ListEffectiveDeploymentsPaginator = client.get_paginator("list_effective_deployments")
         list_installed_components_paginator: ListInstalledComponentsPaginator = client.get_paginator("list_installed_components")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ComponentVisibilityScopeType,
     CoreDeviceStatusType,
@@ -51,20 +50,14 @@
     ListCoreDevicesResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEffectiveDeploymentsResponseTypeDef,
     ListInstalledComponentsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListClientDevicesAssociatedWithCoreDevicePaginator",
     "ListComponentVersionsPaginator",
     "ListComponentsPaginator",
     "ListCoreDevicesPaginator",
     "ListDeploymentsPaginator",
     "ListEffectiveDeploymentsPaginator",
@@ -85,30 +78,30 @@
 class ListClientDevicesAssociatedWithCoreDevicePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListClientDevicesAssociatedWithCoreDevice)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listclientdevicesassociatedwithcoredevicepaginator)
     """
 
     def paginate(
-        self, *, coreDeviceThingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, coreDeviceThingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListClientDevicesAssociatedWithCoreDevice.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listclientdevicesassociatedwithcoredevicepaginator)
         """
 
 
 class ListComponentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentversionspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentversionspaginator)
         """
 
 
@@ -118,15 +111,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentspaginator)
     """
 
     def paginate(
         self,
         *,
         scope: ComponentVisibilityScopeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentspaginator)
         """
 
 
@@ -137,15 +130,15 @@
     """
 
     def paginate(
         self,
         *,
         thingGroupArn: str = ...,
         status: CoreDeviceStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListCoreDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcoredevicespaginator)
         """
 
 
@@ -157,30 +150,30 @@
 
     def paginate(
         self,
         *,
         targetArn: str = ...,
         historyFilter: DeploymentHistoryFilterType = ...,
         parentTargetArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listdeploymentspaginator)
         """
 
 
 class ListEffectiveDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListEffectiveDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listeffectivedeploymentspaginator)
     """
 
     def paginate(
-        self, *, coreDeviceThingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, coreDeviceThingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEffectiveDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListEffectiveDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listeffectivedeploymentspaginator)
         """
 
 
@@ -191,13 +184,13 @@
     """
 
     def paginate(
         self,
         *,
         coreDeviceThingName: str,
         topologyFilter: InstalledComponentTopologyFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstalledComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListInstalledComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listinstalledcomponentspaginator)
         """
```

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/paginator.pyi` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_core_devices_paginator: ListCoreDevicesPaginator = client.get_paginator("list_core_devices")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_effective_deployments_paginator: ListEffectiveDeploymentsPaginator = client.get_paginator("list_effective_deployments")
         list_installed_components_paginator: ListInstalledComponentsPaginator = client.get_paginator("list_installed_components")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ComponentVisibilityScopeType,
     CoreDeviceStatusType,
@@ -51,19 +50,14 @@
     ListCoreDevicesResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEffectiveDeploymentsResponseTypeDef,
     ListInstalledComponentsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListClientDevicesAssociatedWithCoreDevicePaginator",
     "ListComponentVersionsPaginator",
     "ListComponentsPaginator",
     "ListCoreDevicesPaginator",
     "ListDeploymentsPaginator",
     "ListEffectiveDeploymentsPaginator",
@@ -81,29 +75,29 @@
 class ListClientDevicesAssociatedWithCoreDevicePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListClientDevicesAssociatedWithCoreDevice)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listclientdevicesassociatedwithcoredevicepaginator)
     """
 
     def paginate(
-        self, *, coreDeviceThingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, coreDeviceThingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListClientDevicesAssociatedWithCoreDevice.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listclientdevicesassociatedwithcoredevicepaginator)
         """
 
 class ListComponentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentversionspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentversionspaginator)
         """
 
 class ListComponentsPaginator(AioPaginator):
@@ -112,15 +106,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentspaginator)
     """
 
     def paginate(
         self,
         *,
         scope: ComponentVisibilityScopeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcomponentspaginator)
         """
 
 class ListCoreDevicesPaginator(AioPaginator):
@@ -130,15 +124,15 @@
     """
 
     def paginate(
         self,
         *,
         thingGroupArn: str = ...,
         status: CoreDeviceStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListCoreDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listcoredevicespaginator)
         """
 
 class ListDeploymentsPaginator(AioPaginator):
@@ -149,29 +143,29 @@
 
     def paginate(
         self,
         *,
         targetArn: str = ...,
         historyFilter: DeploymentHistoryFilterType = ...,
         parentTargetArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listdeploymentspaginator)
         """
 
 class ListEffectiveDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListEffectiveDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listeffectivedeploymentspaginator)
     """
 
     def paginate(
-        self, *, coreDeviceThingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, coreDeviceThingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEffectiveDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListEffectiveDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listeffectivedeploymentspaginator)
         """
 
 class ListInstalledComponentsPaginator(AioPaginator):
@@ -181,13 +175,13 @@
     """
 
     def paginate(
         self,
         *,
         coreDeviceThingName: str,
         topologyFilter: InstalledComponentTopologyFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstalledComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2.Paginator.ListInstalledComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/paginators/#listinstalledcomponentspaginator)
         """
```

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/type_defs.py` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -48,73 +48,80 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateClientDeviceWithCoreDeviceEntryTypeDef",
     "AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef",
     "AssociateServiceRoleToAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateServiceRoleToAccountResponseTypeDef",
     "AssociatedClientDeviceTypeDef",
     "DisassociateClientDeviceFromCoreDeviceEntryTypeDef",
     "DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef",
     "CancelDeploymentRequestRequestTypeDef",
+    "CancelDeploymentResponseTypeDef",
     "CloudComponentStatusTypeDef",
     "ComponentCandidateTypeDef",
     "ComponentConfigurationUpdateTypeDef",
     "ComponentDependencyRequirementTypeDef",
     "ComponentPlatformTypeDef",
     "SystemResourceLimitsTypeDef",
     "ComponentVersionListItemTypeDef",
     "ConnectivityInfoTypeDef",
     "CoreDeviceTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteCoreDeviceRequestRequestTypeDef",
     "DeleteDeploymentRequestRequestTypeDef",
     "DeploymentComponentUpdatePolicyTypeDef",
     "DeploymentConfigurationValidationPolicyTypeDef",
     "IoTJobTimeoutConfigTypeDef",
     "DeploymentTypeDef",
     "DescribeComponentRequestRequestTypeDef",
+    "DisassociateServiceRoleFromAccountResponseTypeDef",
     "EffectiveDeploymentStatusDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetComponentRequestRequestTypeDef",
+    "GetComponentResponseTypeDef",
     "GetComponentVersionArtifactRequestRequestTypeDef",
+    "GetComponentVersionArtifactResponseTypeDef",
     "GetConnectivityInfoRequestRequestTypeDef",
     "GetCoreDeviceRequestRequestTypeDef",
+    "GetCoreDeviceResponseTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetServiceRoleForAccountResponseTypeDef",
     "InstalledComponentTypeDef",
     "IoTJobAbortCriteriaTypeDef",
     "IoTJobRateIncreaseCriteriaTypeDef",
     "LambdaDeviceMountTypeDef",
     "LambdaVolumeMountTypeDef",
     "LambdaEventSourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
     "ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef",
+    "ListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
     "ListComponentVersionsRequestRequestTypeDef",
+    "ListComponentsRequestListComponentsPaginateTypeDef",
     "ListComponentsRequestRequestTypeDef",
+    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
     "ListCoreDevicesRequestRequestTypeDef",
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
+    "ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
     "ListEffectiveDeploymentsRequestRequestTypeDef",
+    "ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
     "ListInstalledComponentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "ResolvedComponentVersionTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateConnectivityInfoResponseTypeDef",
     "BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef",
-    "AssociateServiceRoleToAccountResponseTypeDef",
     "BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef",
-    "CancelDeploymentResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "DisassociateServiceRoleFromAccountResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetComponentResponseTypeDef",
-    "GetComponentVersionArtifactResponseTypeDef",
-    "GetCoreDeviceResponseTypeDef",
-    "GetServiceRoleForAccountResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateConnectivityInfoResponseTypeDef",
     "ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef",
     "BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef",
     "BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef",
     "CreateComponentVersionResponseTypeDef",
     "ComponentLatestVersionTypeDef",
     "DescribeComponentResponseTypeDef",
     "ResolveComponentCandidatesRequestRequestTypeDef",
@@ -126,21 +133,14 @@
     "DeploymentPoliciesTypeDef",
     "ListDeploymentsResponseTypeDef",
     "EffectiveDeploymentTypeDef",
     "ListInstalledComponentsResponseTypeDef",
     "IoTJobAbortConfigTypeDef",
     "IoTJobExponentialRolloutRateTypeDef",
     "LambdaContainerParamsTypeDef",
-    "ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    "ListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    "ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    "ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
     "ResolveComponentCandidatesResponseTypeDef",
     "ComponentTypeDef",
     "ComponentDeploymentSpecificationTypeDef",
     "ListEffectiveDeploymentsResponseTypeDef",
     "IoTJobExecutionsRolloutConfigTypeDef",
     "LambdaLinuxProcessParamsTypeDef",
     "ListComponentsResponseTypeDef",
@@ -172,22 +172,19 @@
 AssociateServiceRoleToAccountRequestRequestTypeDef = TypedDict(
     "AssociateServiceRoleToAccountRequestRequestTypeDef",
     {
         "roleArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateServiceRoleToAccountResponseTypeDef = TypedDict(
+    "AssociateServiceRoleToAccountResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "associatedAt": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatedClientDeviceTypeDef = TypedDict(
     "AssociatedClientDeviceTypeDef",
     {
         "thingName": str,
@@ -216,14 +213,22 @@
 CancelDeploymentRequestRequestTypeDef = TypedDict(
     "CancelDeploymentRequestRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 
+CancelDeploymentResponseTypeDef = TypedDict(
+    "CancelDeploymentResponseTypeDef",
+    {
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudComponentStatusTypeDef = TypedDict(
     "CloudComponentStatusTypeDef",
     {
         "componentState": CloudComponentStateType,
         "message": str,
         "errors": Dict[str, str],
         "vendorGuidance": VendorGuidanceType,
@@ -305,14 +310,24 @@
         "coreDeviceThingName": str,
         "status": CoreDeviceStatusType,
         "lastStatusUpdateTimestamp": datetime,
     },
     total=False,
 )
 
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "deploymentId": str,
+        "iotJobId": str,
+        "iotJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -373,23 +388,38 @@
 DescribeComponentRequestRequestTypeDef = TypedDict(
     "DescribeComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
+DisassociateServiceRoleFromAccountResponseTypeDef = TypedDict(
+    "DisassociateServiceRoleFromAccountResponseTypeDef",
+    {
+        "disassociatedAt": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EffectiveDeploymentStatusDetailsTypeDef = TypedDict(
     "EffectiveDeploymentStatusDetailsTypeDef",
     {
         "errorStack": List[str],
         "errorTypes": List[str],
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
 _RequiredGetComponentRequestRequestTypeDef = TypedDict(
     "_RequiredGetComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalGetComponentRequestRequestTypeDef = TypedDict(
@@ -403,43 +433,84 @@
 
 class GetComponentRequestRequestTypeDef(
     _RequiredGetComponentRequestRequestTypeDef, _OptionalGetComponentRequestRequestTypeDef
 ):
     pass
 
 
+GetComponentResponseTypeDef = TypedDict(
+    "GetComponentResponseTypeDef",
+    {
+        "recipeOutputFormat": RecipeOutputFormatType,
+        "recipe": bytes,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetComponentVersionArtifactRequestRequestTypeDef = TypedDict(
     "GetComponentVersionArtifactRequestRequestTypeDef",
     {
         "arn": str,
         "artifactName": str,
     },
 )
 
+GetComponentVersionArtifactResponseTypeDef = TypedDict(
+    "GetComponentVersionArtifactResponseTypeDef",
+    {
+        "preSignedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConnectivityInfoRequestRequestTypeDef = TypedDict(
     "GetConnectivityInfoRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
 GetCoreDeviceRequestRequestTypeDef = TypedDict(
     "GetCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 
+GetCoreDeviceResponseTypeDef = TypedDict(
+    "GetCoreDeviceResponseTypeDef",
+    {
+        "coreDeviceThingName": str,
+        "coreVersion": str,
+        "platform": str,
+        "architecture": str,
+        "status": CoreDeviceStatusType,
+        "lastStatusUpdateTimestamp": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 
+GetServiceRoleForAccountResponseTypeDef = TypedDict(
+    "GetServiceRoleForAccountResponseTypeDef",
+    {
+        "associatedAt": str,
+        "roleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstalledComponentTypeDef = TypedDict(
     "InstalledComponentTypeDef",
     {
         "componentName": str,
         "componentVersion": str,
         "lifecycleState": InstalledComponentLifecycleStateType,
         "lifecycleStateDetails": str,
@@ -520,24 +591,36 @@
     "LambdaEventSourceTypeDef",
     {
         "topic": str,
         "type": LambdaEventSourceTypeType,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
+    "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
+    "_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef(
+    _RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
+    _OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef = TypedDict(
@@ -553,14 +636,36 @@
 class ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef(
     _RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
     _OptionalListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListComponentVersionsRequestListComponentVersionsPaginateTypeDef(
+    _RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
+    _OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListComponentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListComponentVersionsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListComponentVersionsRequestRequestTypeDef = TypedDict(
@@ -576,47 +681,99 @@
 class ListComponentVersionsRequestRequestTypeDef(
     _RequiredListComponentVersionsRequestRequestTypeDef,
     _OptionalListComponentVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsRequestListComponentsPaginateTypeDef",
+    {
+        "scope": ComponentVisibilityScopeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsRequestRequestTypeDef = TypedDict(
     "ListComponentsRequestRequestTypeDef",
     {
         "scope": ComponentVisibilityScopeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCoreDevicesRequestListCoreDevicesPaginateTypeDef = TypedDict(
+    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
+    {
+        "thingGroupArn": str,
+        "status": CoreDeviceStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCoreDevicesRequestRequestTypeDef = TypedDict(
     "ListCoreDevicesRequestRequestTypeDef",
     {
         "thingGroupArn": str,
         "status": CoreDeviceStatusType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "targetArn": str,
+        "historyFilter": DeploymentHistoryFilterType,
+        "parentTargetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentsRequestRequestTypeDef = TypedDict(
     "ListDeploymentsRequestRequestTypeDef",
     {
         "targetArn": str,
         "historyFilter": DeploymentHistoryFilterType,
         "parentTargetArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
+    {
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef(
+    _RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
+    _OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEffectiveDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListEffectiveDeploymentsRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListEffectiveDeploymentsRequestRequestTypeDef = TypedDict(
@@ -632,14 +789,37 @@
 class ListEffectiveDeploymentsRequestRequestTypeDef(
     _RequiredListEffectiveDeploymentsRequestRequestTypeDef,
     _OptionalListEffectiveDeploymentsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
+    "_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
+    {
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
+    "_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
+    {
+        "topologyFilter": InstalledComponentTopologyFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef(
+    _RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
+    _OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInstalledComponentsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstalledComponentsRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListInstalledComponentsRequestRequestTypeDef = TypedDict(
@@ -663,27 +843,56 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
 ResolvedComponentVersionTypeDef = TypedDict(
     "ResolvedComponentVersionTypeDef",
     {
         "arn": str,
         "componentName": str,
         "componentVersion": str,
         "recipe": bytes,
         "vendorGuidance": VendorGuidanceType,
         "message": str,
     },
     total=False,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -692,14 +901,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateConnectivityInfoResponseTypeDef = TypedDict(
+    "UpdateConnectivityInfoResponseTypeDef",
+    {
+        "version": str,
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef = TypedDict(
@@ -714,127 +932,28 @@
 class BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef(
     _RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
     _OptionalBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
 ):
     pass
 
 
-AssociateServiceRoleToAccountResponseTypeDef = TypedDict(
-    "AssociateServiceRoleToAccountResponseTypeDef",
-    {
-        "associatedAt": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef = TypedDict(
     "BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef",
     {
         "errorEntries": List[AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelDeploymentResponseTypeDef = TypedDict(
-    "CancelDeploymentResponseTypeDef",
-    {
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "deploymentId": str,
-        "iotJobId": str,
-        "iotJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateServiceRoleFromAccountResponseTypeDef = TypedDict(
-    "DisassociateServiceRoleFromAccountResponseTypeDef",
-    {
-        "disassociatedAt": str,
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
-GetComponentResponseTypeDef = TypedDict(
-    "GetComponentResponseTypeDef",
-    {
-        "recipeOutputFormat": RecipeOutputFormatType,
-        "recipe": bytes,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComponentVersionArtifactResponseTypeDef = TypedDict(
-    "GetComponentVersionArtifactResponseTypeDef",
-    {
-        "preSignedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCoreDeviceResponseTypeDef = TypedDict(
-    "GetCoreDeviceResponseTypeDef",
-    {
-        "coreDeviceThingName": str,
-        "coreVersion": str,
-        "platform": str,
-        "architecture": str,
-        "status": CoreDeviceStatusType,
-        "lastStatusUpdateTimestamp": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetServiceRoleForAccountResponseTypeDef = TypedDict(
-    "GetServiceRoleForAccountResponseTypeDef",
-    {
-        "associatedAt": str,
-        "roleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectivityInfoResponseTypeDef = TypedDict(
-    "UpdateConnectivityInfoResponseTypeDef",
-    {
-        "version": str,
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef = TypedDict(
     "ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef",
     {
         "associatedClientDevices": List[AssociatedClientDeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
@@ -856,27 +975,27 @@
     pass
 
 
 BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef = TypedDict(
     "BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef",
     {
         "errorEntries": List[DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComponentVersionResponseTypeDef = TypedDict(
     "CreateComponentVersionResponseTypeDef",
     {
         "arn": str,
         "componentName": str,
         "componentVersion": str,
         "creationTimestamp": datetime,
         "status": CloudComponentStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentLatestVersionTypeDef = TypedDict(
     "ComponentLatestVersionTypeDef",
     {
         "arn": str,
@@ -897,15 +1016,15 @@
         "componentVersion": str,
         "creationTimestamp": datetime,
         "publisher": str,
         "description": str,
         "status": CloudComponentStatusTypeDef,
         "platforms": List[ComponentPlatformTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResolveComponentCandidatesRequestRequestTypeDef = TypedDict(
     "ResolveComponentCandidatesRequestRequestTypeDef",
     {
         "platform": ComponentPlatformTypeDef,
@@ -925,24 +1044,24 @@
 )
 
 ListComponentVersionsResponseTypeDef = TypedDict(
     "ListComponentVersionsResponseTypeDef",
     {
         "componentVersions": List[ComponentVersionListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectivityInfoResponseTypeDef = TypedDict(
     "GetConnectivityInfoResponseTypeDef",
     {
         "connectivityInfo": List[ConnectivityInfoTypeDef],
         "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConnectivityInfoRequestRequestTypeDef = TypedDict(
     "UpdateConnectivityInfoRequestRequestTypeDef",
     {
         "thingName": str,
@@ -951,15 +1070,15 @@
 )
 
 ListCoreDevicesResponseTypeDef = TypedDict(
     "ListCoreDevicesResponseTypeDef",
     {
         "coreDevices": List[CoreDeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentPoliciesTypeDef = TypedDict(
     "DeploymentPoliciesTypeDef",
     {
         "failureHandlingPolicy": DeploymentFailureHandlingPolicyType,
@@ -970,15 +1089,15 @@
 )
 
 ListDeploymentsResponseTypeDef = TypedDict(
     "ListDeploymentsResponseTypeDef",
     {
         "deployments": List[DeploymentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEffectiveDeploymentTypeDef = TypedDict(
     "_RequiredEffectiveDeploymentTypeDef",
     {
         "deploymentId": str,
@@ -1009,15 +1128,15 @@
 
 
 ListInstalledComponentsResponseTypeDef = TypedDict(
     "ListInstalledComponentsResponseTypeDef",
     {
         "installedComponents": List[InstalledComponentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IoTJobAbortConfigTypeDef = TypedDict(
     "IoTJobAbortConfigTypeDef",
     {
         "criteriaList": Sequence[IoTJobAbortCriteriaTypeDef],
@@ -1040,138 +1159,19 @@
         "mountROSysfs": bool,
         "volumes": Sequence[LambdaVolumeMountTypeDef],
         "devices": Sequence[LambdaDeviceMountTypeDef],
     },
     total=False,
 )
 
-_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
-    "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
-    "_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef(
-    _RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-    _OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListComponentVersionsRequestListComponentVersionsPaginateTypeDef(
-    _RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-    _OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    {
-        "scope": ComponentVisibilityScopeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCoreDevicesRequestListCoreDevicesPaginateTypeDef = TypedDict(
-    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
-    {
-        "thingGroupArn": str,
-        "status": CoreDeviceStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "targetArn": str,
-        "historyFilter": DeploymentHistoryFilterType,
-        "parentTargetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef(
-    _RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-    _OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
-    "_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
-    "_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
-    {
-        "topologyFilter": InstalledComponentTopologyFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef(
-    _RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
-    _OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
-):
-    pass
-
-
 ResolveComponentCandidatesResponseTypeDef = TypedDict(
     "ResolveComponentCandidatesResponseTypeDef",
     {
         "resolvedComponentVersions": List[ResolvedComponentVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentTypeDef = TypedDict(
     "ComponentTypeDef",
     {
         "arn": str,
@@ -1192,15 +1192,15 @@
 )
 
 ListEffectiveDeploymentsResponseTypeDef = TypedDict(
     "ListEffectiveDeploymentsResponseTypeDef",
     {
         "effectiveDeployments": List[EffectiveDeploymentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IoTJobExecutionsRolloutConfigTypeDef = TypedDict(
     "IoTJobExecutionsRolloutConfigTypeDef",
     {
         "exponentialRate": IoTJobExponentialRolloutRateTypeDef,
@@ -1219,15 +1219,15 @@
 )
 
 ListComponentsResponseTypeDef = TypedDict(
     "ListComponentsResponseTypeDef",
     {
         "components": List[ComponentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentIoTJobConfigurationTypeDef = TypedDict(
     "DeploymentIoTJobConfigurationTypeDef",
     {
         "jobExecutionsRolloutConfig": IoTJobExecutionsRolloutConfigTypeDef,
@@ -1295,15 +1295,15 @@
         "components": Dict[str, ComponentDeploymentSpecificationTypeDef],
         "deploymentPolicies": DeploymentPoliciesTypeDef,
         "iotJobConfiguration": DeploymentIoTJobConfigurationTypeDef,
         "creationTimestamp": datetime,
         "isLatestForTarget": bool,
         "parentTargetArn": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLambdaFunctionRecipeSourceTypeDef = TypedDict(
     "_RequiredLambdaFunctionRecipeSourceTypeDef",
     {
         "lambdaArn": str,
```

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2/type_defs.pyi` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -47,73 +47,80 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateClientDeviceWithCoreDeviceEntryTypeDef",
     "AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef",
     "AssociateServiceRoleToAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateServiceRoleToAccountResponseTypeDef",
     "AssociatedClientDeviceTypeDef",
     "DisassociateClientDeviceFromCoreDeviceEntryTypeDef",
     "DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef",
     "CancelDeploymentRequestRequestTypeDef",
+    "CancelDeploymentResponseTypeDef",
     "CloudComponentStatusTypeDef",
     "ComponentCandidateTypeDef",
     "ComponentConfigurationUpdateTypeDef",
     "ComponentDependencyRequirementTypeDef",
     "ComponentPlatformTypeDef",
     "SystemResourceLimitsTypeDef",
     "ComponentVersionListItemTypeDef",
     "ConnectivityInfoTypeDef",
     "CoreDeviceTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteCoreDeviceRequestRequestTypeDef",
     "DeleteDeploymentRequestRequestTypeDef",
     "DeploymentComponentUpdatePolicyTypeDef",
     "DeploymentConfigurationValidationPolicyTypeDef",
     "IoTJobTimeoutConfigTypeDef",
     "DeploymentTypeDef",
     "DescribeComponentRequestRequestTypeDef",
+    "DisassociateServiceRoleFromAccountResponseTypeDef",
     "EffectiveDeploymentStatusDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetComponentRequestRequestTypeDef",
+    "GetComponentResponseTypeDef",
     "GetComponentVersionArtifactRequestRequestTypeDef",
+    "GetComponentVersionArtifactResponseTypeDef",
     "GetConnectivityInfoRequestRequestTypeDef",
     "GetCoreDeviceRequestRequestTypeDef",
+    "GetCoreDeviceResponseTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetServiceRoleForAccountResponseTypeDef",
     "InstalledComponentTypeDef",
     "IoTJobAbortCriteriaTypeDef",
     "IoTJobRateIncreaseCriteriaTypeDef",
     "LambdaDeviceMountTypeDef",
     "LambdaVolumeMountTypeDef",
     "LambdaEventSourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
     "ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef",
+    "ListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
     "ListComponentVersionsRequestRequestTypeDef",
+    "ListComponentsRequestListComponentsPaginateTypeDef",
     "ListComponentsRequestRequestTypeDef",
+    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
     "ListCoreDevicesRequestRequestTypeDef",
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
+    "ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
     "ListEffectiveDeploymentsRequestRequestTypeDef",
+    "ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
     "ListInstalledComponentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "ResolvedComponentVersionTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateConnectivityInfoResponseTypeDef",
     "BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef",
-    "AssociateServiceRoleToAccountResponseTypeDef",
     "BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef",
-    "CancelDeploymentResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "DisassociateServiceRoleFromAccountResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetComponentResponseTypeDef",
-    "GetComponentVersionArtifactResponseTypeDef",
-    "GetCoreDeviceResponseTypeDef",
-    "GetServiceRoleForAccountResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateConnectivityInfoResponseTypeDef",
     "ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef",
     "BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef",
     "BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef",
     "CreateComponentVersionResponseTypeDef",
     "ComponentLatestVersionTypeDef",
     "DescribeComponentResponseTypeDef",
     "ResolveComponentCandidatesRequestRequestTypeDef",
@@ -125,21 +132,14 @@
     "DeploymentPoliciesTypeDef",
     "ListDeploymentsResponseTypeDef",
     "EffectiveDeploymentTypeDef",
     "ListInstalledComponentsResponseTypeDef",
     "IoTJobAbortConfigTypeDef",
     "IoTJobExponentialRolloutRateTypeDef",
     "LambdaContainerParamsTypeDef",
-    "ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    "ListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    "ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    "ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
     "ResolveComponentCandidatesResponseTypeDef",
     "ComponentTypeDef",
     "ComponentDeploymentSpecificationTypeDef",
     "ListEffectiveDeploymentsResponseTypeDef",
     "IoTJobExecutionsRolloutConfigTypeDef",
     "LambdaLinuxProcessParamsTypeDef",
     "ListComponentsResponseTypeDef",
@@ -171,22 +171,19 @@
 AssociateServiceRoleToAccountRequestRequestTypeDef = TypedDict(
     "AssociateServiceRoleToAccountRequestRequestTypeDef",
     {
         "roleArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateServiceRoleToAccountResponseTypeDef = TypedDict(
+    "AssociateServiceRoleToAccountResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "associatedAt": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatedClientDeviceTypeDef = TypedDict(
     "AssociatedClientDeviceTypeDef",
     {
         "thingName": str,
@@ -215,14 +212,22 @@
 CancelDeploymentRequestRequestTypeDef = TypedDict(
     "CancelDeploymentRequestRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 
+CancelDeploymentResponseTypeDef = TypedDict(
+    "CancelDeploymentResponseTypeDef",
+    {
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudComponentStatusTypeDef = TypedDict(
     "CloudComponentStatusTypeDef",
     {
         "componentState": CloudComponentStateType,
         "message": str,
         "errors": Dict[str, str],
         "vendorGuidance": VendorGuidanceType,
@@ -304,14 +309,24 @@
         "coreDeviceThingName": str,
         "status": CoreDeviceStatusType,
         "lastStatusUpdateTimestamp": datetime,
     },
     total=False,
 )
 
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "deploymentId": str,
+        "iotJobId": str,
+        "iotJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -372,23 +387,38 @@
 DescribeComponentRequestRequestTypeDef = TypedDict(
     "DescribeComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
+DisassociateServiceRoleFromAccountResponseTypeDef = TypedDict(
+    "DisassociateServiceRoleFromAccountResponseTypeDef",
+    {
+        "disassociatedAt": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EffectiveDeploymentStatusDetailsTypeDef = TypedDict(
     "EffectiveDeploymentStatusDetailsTypeDef",
     {
         "errorStack": List[str],
         "errorTypes": List[str],
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
 _RequiredGetComponentRequestRequestTypeDef = TypedDict(
     "_RequiredGetComponentRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalGetComponentRequestRequestTypeDef = TypedDict(
@@ -400,43 +430,84 @@
 )
 
 class GetComponentRequestRequestTypeDef(
     _RequiredGetComponentRequestRequestTypeDef, _OptionalGetComponentRequestRequestTypeDef
 ):
     pass
 
+GetComponentResponseTypeDef = TypedDict(
+    "GetComponentResponseTypeDef",
+    {
+        "recipeOutputFormat": RecipeOutputFormatType,
+        "recipe": bytes,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetComponentVersionArtifactRequestRequestTypeDef = TypedDict(
     "GetComponentVersionArtifactRequestRequestTypeDef",
     {
         "arn": str,
         "artifactName": str,
     },
 )
 
+GetComponentVersionArtifactResponseTypeDef = TypedDict(
+    "GetComponentVersionArtifactResponseTypeDef",
+    {
+        "preSignedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConnectivityInfoRequestRequestTypeDef = TypedDict(
     "GetConnectivityInfoRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
 GetCoreDeviceRequestRequestTypeDef = TypedDict(
     "GetCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 
+GetCoreDeviceResponseTypeDef = TypedDict(
+    "GetCoreDeviceResponseTypeDef",
+    {
+        "coreDeviceThingName": str,
+        "coreVersion": str,
+        "platform": str,
+        "architecture": str,
+        "status": CoreDeviceStatusType,
+        "lastStatusUpdateTimestamp": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 
+GetServiceRoleForAccountResponseTypeDef = TypedDict(
+    "GetServiceRoleForAccountResponseTypeDef",
+    {
+        "associatedAt": str,
+        "roleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstalledComponentTypeDef = TypedDict(
     "InstalledComponentTypeDef",
     {
         "componentName": str,
         "componentVersion": str,
         "lifecycleState": InstalledComponentLifecycleStateType,
         "lifecycleStateDetails": str,
@@ -513,24 +584,34 @@
     "LambdaEventSourceTypeDef",
     {
         "topic": str,
         "type": LambdaEventSourceTypeType,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
+    "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
+    "_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef(
+    _RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
+    _OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
+):
+    pass
+
 _RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef = TypedDict(
@@ -544,14 +625,34 @@
 
 class ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef(
     _RequiredListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
     _OptionalListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListComponentVersionsRequestListComponentVersionsPaginateTypeDef(
+    _RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
+    _OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListComponentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListComponentVersionsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListComponentVersionsRequestRequestTypeDef = TypedDict(
@@ -565,47 +666,97 @@
 
 class ListComponentVersionsRequestRequestTypeDef(
     _RequiredListComponentVersionsRequestRequestTypeDef,
     _OptionalListComponentVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsRequestListComponentsPaginateTypeDef",
+    {
+        "scope": ComponentVisibilityScopeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsRequestRequestTypeDef = TypedDict(
     "ListComponentsRequestRequestTypeDef",
     {
         "scope": ComponentVisibilityScopeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCoreDevicesRequestListCoreDevicesPaginateTypeDef = TypedDict(
+    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
+    {
+        "thingGroupArn": str,
+        "status": CoreDeviceStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCoreDevicesRequestRequestTypeDef = TypedDict(
     "ListCoreDevicesRequestRequestTypeDef",
     {
         "thingGroupArn": str,
         "status": CoreDeviceStatusType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "targetArn": str,
+        "historyFilter": DeploymentHistoryFilterType,
+        "parentTargetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentsRequestRequestTypeDef = TypedDict(
     "ListDeploymentsRequestRequestTypeDef",
     {
         "targetArn": str,
         "historyFilter": DeploymentHistoryFilterType,
         "parentTargetArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
+    {
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef(
+    _RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
+    _OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEffectiveDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListEffectiveDeploymentsRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListEffectiveDeploymentsRequestRequestTypeDef = TypedDict(
@@ -619,14 +770,35 @@
 
 class ListEffectiveDeploymentsRequestRequestTypeDef(
     _RequiredListEffectiveDeploymentsRequestRequestTypeDef,
     _OptionalListEffectiveDeploymentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
+    "_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
+    {
+        "coreDeviceThingName": str,
+    },
+)
+_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
+    "_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
+    {
+        "topologyFilter": InstalledComponentTopologyFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef(
+    _RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
+    _OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListInstalledComponentsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstalledComponentsRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalListInstalledComponentsRequestRequestTypeDef = TypedDict(
@@ -648,27 +820,56 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
 ResolvedComponentVersionTypeDef = TypedDict(
     "ResolvedComponentVersionTypeDef",
     {
         "arn": str,
         "componentName": str,
         "componentVersion": str,
         "recipe": bytes,
         "vendorGuidance": VendorGuidanceType,
         "message": str,
     },
     total=False,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -677,14 +878,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateConnectivityInfoResponseTypeDef = TypedDict(
+    "UpdateConnectivityInfoResponseTypeDef",
+    {
+        "version": str,
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 _OptionalBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef = TypedDict(
@@ -697,127 +907,28 @@
 
 class BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef(
     _RequiredBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
     _OptionalBatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
 ):
     pass
 
-AssociateServiceRoleToAccountResponseTypeDef = TypedDict(
-    "AssociateServiceRoleToAccountResponseTypeDef",
-    {
-        "associatedAt": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef = TypedDict(
     "BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef",
     {
         "errorEntries": List[AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelDeploymentResponseTypeDef = TypedDict(
-    "CancelDeploymentResponseTypeDef",
-    {
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "deploymentId": str,
-        "iotJobId": str,
-        "iotJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateServiceRoleFromAccountResponseTypeDef = TypedDict(
-    "DisassociateServiceRoleFromAccountResponseTypeDef",
-    {
-        "disassociatedAt": str,
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
-GetComponentResponseTypeDef = TypedDict(
-    "GetComponentResponseTypeDef",
-    {
-        "recipeOutputFormat": RecipeOutputFormatType,
-        "recipe": bytes,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComponentVersionArtifactResponseTypeDef = TypedDict(
-    "GetComponentVersionArtifactResponseTypeDef",
-    {
-        "preSignedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCoreDeviceResponseTypeDef = TypedDict(
-    "GetCoreDeviceResponseTypeDef",
-    {
-        "coreDeviceThingName": str,
-        "coreVersion": str,
-        "platform": str,
-        "architecture": str,
-        "status": CoreDeviceStatusType,
-        "lastStatusUpdateTimestamp": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetServiceRoleForAccountResponseTypeDef = TypedDict(
-    "GetServiceRoleForAccountResponseTypeDef",
-    {
-        "associatedAt": str,
-        "roleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectivityInfoResponseTypeDef = TypedDict(
-    "UpdateConnectivityInfoResponseTypeDef",
-    {
-        "version": str,
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef = TypedDict(
     "ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef",
     {
         "associatedClientDevices": List[AssociatedClientDeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef",
     {
         "coreDeviceThingName": str,
@@ -837,27 +948,27 @@
 ):
     pass
 
 BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef = TypedDict(
     "BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef",
     {
         "errorEntries": List[DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComponentVersionResponseTypeDef = TypedDict(
     "CreateComponentVersionResponseTypeDef",
     {
         "arn": str,
         "componentName": str,
         "componentVersion": str,
         "creationTimestamp": datetime,
         "status": CloudComponentStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentLatestVersionTypeDef = TypedDict(
     "ComponentLatestVersionTypeDef",
     {
         "arn": str,
@@ -878,15 +989,15 @@
         "componentVersion": str,
         "creationTimestamp": datetime,
         "publisher": str,
         "description": str,
         "status": CloudComponentStatusTypeDef,
         "platforms": List[ComponentPlatformTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResolveComponentCandidatesRequestRequestTypeDef = TypedDict(
     "ResolveComponentCandidatesRequestRequestTypeDef",
     {
         "platform": ComponentPlatformTypeDef,
@@ -906,24 +1017,24 @@
 )
 
 ListComponentVersionsResponseTypeDef = TypedDict(
     "ListComponentVersionsResponseTypeDef",
     {
         "componentVersions": List[ComponentVersionListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectivityInfoResponseTypeDef = TypedDict(
     "GetConnectivityInfoResponseTypeDef",
     {
         "connectivityInfo": List[ConnectivityInfoTypeDef],
         "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConnectivityInfoRequestRequestTypeDef = TypedDict(
     "UpdateConnectivityInfoRequestRequestTypeDef",
     {
         "thingName": str,
@@ -932,15 +1043,15 @@
 )
 
 ListCoreDevicesResponseTypeDef = TypedDict(
     "ListCoreDevicesResponseTypeDef",
     {
         "coreDevices": List[CoreDeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentPoliciesTypeDef = TypedDict(
     "DeploymentPoliciesTypeDef",
     {
         "failureHandlingPolicy": DeploymentFailureHandlingPolicyType,
@@ -951,15 +1062,15 @@
 )
 
 ListDeploymentsResponseTypeDef = TypedDict(
     "ListDeploymentsResponseTypeDef",
     {
         "deployments": List[DeploymentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEffectiveDeploymentTypeDef = TypedDict(
     "_RequiredEffectiveDeploymentTypeDef",
     {
         "deploymentId": str,
@@ -988,15 +1099,15 @@
     pass
 
 ListInstalledComponentsResponseTypeDef = TypedDict(
     "ListInstalledComponentsResponseTypeDef",
     {
         "installedComponents": List[InstalledComponentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IoTJobAbortConfigTypeDef = TypedDict(
     "IoTJobAbortConfigTypeDef",
     {
         "criteriaList": Sequence[IoTJobAbortCriteriaTypeDef],
@@ -1019,130 +1130,19 @@
         "mountROSysfs": bool,
         "volumes": Sequence[LambdaVolumeMountTypeDef],
         "devices": Sequence[LambdaDeviceMountTypeDef],
     },
     total=False,
 )
 
-_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
-    "_RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef = TypedDict(
-    "_OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef(
-    _RequiredListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-    _OptionalListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-):
-    pass
-
-_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListComponentVersionsRequestListComponentVersionsPaginateTypeDef(
-    _RequiredListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-    _OptionalListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-):
-    pass
-
-ListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    {
-        "scope": ComponentVisibilityScopeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCoreDevicesRequestListCoreDevicesPaginateTypeDef = TypedDict(
-    "ListCoreDevicesRequestListCoreDevicesPaginateTypeDef",
-    {
-        "thingGroupArn": str,
-        "status": CoreDeviceStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "targetArn": str,
-        "historyFilter": DeploymentHistoryFilterType,
-        "parentTargetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef(
-    _RequiredListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-    _OptionalListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-):
-    pass
-
-_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
-    "_RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
-    {
-        "coreDeviceThingName": str,
-    },
-)
-_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef = TypedDict(
-    "_OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef",
-    {
-        "topologyFilter": InstalledComponentTopologyFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef(
-    _RequiredListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
-    _OptionalListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
-):
-    pass
-
 ResolveComponentCandidatesResponseTypeDef = TypedDict(
     "ResolveComponentCandidatesResponseTypeDef",
     {
         "resolvedComponentVersions": List[ResolvedComponentVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentTypeDef = TypedDict(
     "ComponentTypeDef",
     {
         "arn": str,
@@ -1163,15 +1163,15 @@
 )
 
 ListEffectiveDeploymentsResponseTypeDef = TypedDict(
     "ListEffectiveDeploymentsResponseTypeDef",
     {
         "effectiveDeployments": List[EffectiveDeploymentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IoTJobExecutionsRolloutConfigTypeDef = TypedDict(
     "IoTJobExecutionsRolloutConfigTypeDef",
     {
         "exponentialRate": IoTJobExponentialRolloutRateTypeDef,
@@ -1190,15 +1190,15 @@
 )
 
 ListComponentsResponseTypeDef = TypedDict(
     "ListComponentsResponseTypeDef",
     {
         "components": List[ComponentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentIoTJobConfigurationTypeDef = TypedDict(
     "DeploymentIoTJobConfigurationTypeDef",
     {
         "jobExecutionsRolloutConfig": IoTJobExecutionsRolloutConfigTypeDef,
@@ -1264,15 +1264,15 @@
         "components": Dict[str, ComponentDeploymentSpecificationTypeDef],
         "deploymentPolicies": DeploymentPoliciesTypeDef,
         "iotJobConfiguration": DeploymentIoTJobConfigurationTypeDef,
         "creationTimestamp": datetime,
         "isLatestForTarget": bool,
         "parentTargetArn": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLambdaFunctionRecipeSourceTypeDef = TypedDict(
     "_RequiredLambdaFunctionRecipeSourceTypeDef",
     {
         "lambdaArn": str,
```

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/PKG-INFO` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-greengrassv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GreengrassV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GreengrassV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-greengrassv2"></a>
 
 # types-aiobotocore-greengrassv2
 
 [![PyPI - types-aiobotocore-greengrassv2](https://img.shields.io/pypi/v/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-greengrassv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-greengrassv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-greengrassv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-greengrassv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GreengrassV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
+[aiobotocore.GreengrassV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/greengrassv2.html#GreengrassV2)
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
 [types-aiobotocore-greengrassv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_greengrassv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,73 +366,80 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_greengrassv2.type_defs import (
     AssociateClientDeviceWithCoreDeviceEntryTypeDef,
     AssociateClientDeviceWithCoreDeviceErrorEntryTypeDef,
     AssociateServiceRoleToAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateServiceRoleToAccountResponseTypeDef,
     AssociatedClientDeviceTypeDef,
     DisassociateClientDeviceFromCoreDeviceEntryTypeDef,
     DisassociateClientDeviceFromCoreDeviceErrorEntryTypeDef,
     CancelDeploymentRequestRequestTypeDef,
+    CancelDeploymentResponseTypeDef,
     CloudComponentStatusTypeDef,
     ComponentCandidateTypeDef,
     ComponentConfigurationUpdateTypeDef,
     ComponentDependencyRequirementTypeDef,
     ComponentPlatformTypeDef,
     SystemResourceLimitsTypeDef,
     ComponentVersionListItemTypeDef,
     ConnectivityInfoTypeDef,
     CoreDeviceTypeDef,
+    CreateDeploymentResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteCoreDeviceRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeploymentComponentUpdatePolicyTypeDef,
     DeploymentConfigurationValidationPolicyTypeDef,
     IoTJobTimeoutConfigTypeDef,
     DeploymentTypeDef,
     DescribeComponentRequestRequestTypeDef,
+    DisassociateServiceRoleFromAccountResponseTypeDef,
     EffectiveDeploymentStatusDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetComponentVersionArtifactRequestRequestTypeDef,
+    GetComponentVersionArtifactResponseTypeDef,
     GetConnectivityInfoRequestRequestTypeDef,
     GetCoreDeviceRequestRequestTypeDef,
+    GetCoreDeviceResponseTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetServiceRoleForAccountResponseTypeDef,
     InstalledComponentTypeDef,
     IoTJobAbortCriteriaTypeDef,
     IoTJobRateIncreaseCriteriaTypeDef,
     LambdaDeviceMountTypeDef,
     LambdaVolumeMountTypeDef,
     LambdaEventSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceRequestRequestTypeDef,
+    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
     ListComponentVersionsRequestRequestTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
     ListCoreDevicesRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
     ListEffectiveDeploymentsRequestRequestTypeDef,
+    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ListInstalledComponentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResolvedComponentVersionTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectivityInfoResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceRequestRequestTypeDef,
-    AssociateServiceRoleToAccountResponseTypeDef,
     BatchAssociateClientDeviceWithCoreDeviceResponseTypeDef,
-    CancelDeploymentResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    DisassociateServiceRoleFromAccountResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetComponentResponseTypeDef,
-    GetComponentVersionArtifactResponseTypeDef,
-    GetCoreDeviceResponseTypeDef,
-    GetServiceRoleForAccountResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateConnectivityInfoResponseTypeDef,
     ListClientDevicesAssociatedWithCoreDeviceResponseTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceRequestRequestTypeDef,
     BatchDisassociateClientDeviceFromCoreDeviceResponseTypeDef,
     CreateComponentVersionResponseTypeDef,
     ComponentLatestVersionTypeDef,
     DescribeComponentResponseTypeDef,
     ResolveComponentCandidatesRequestRequestTypeDef,
@@ -444,21 +451,14 @@
     DeploymentPoliciesTypeDef,
     ListDeploymentsResponseTypeDef,
     EffectiveDeploymentTypeDef,
     ListInstalledComponentsResponseTypeDef,
     IoTJobAbortConfigTypeDef,
     IoTJobExponentialRolloutRateTypeDef,
     LambdaContainerParamsTypeDef,
-    ListClientDevicesAssociatedWithCoreDeviceRequestListClientDevicesAssociatedWithCoreDevicePaginateTypeDef,
-    ListComponentVersionsRequestListComponentVersionsPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListCoreDevicesRequestListCoreDevicesPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEffectiveDeploymentsRequestListEffectiveDeploymentsPaginateTypeDef,
-    ListInstalledComponentsRequestListInstalledComponentsPaginateTypeDef,
     ResolveComponentCandidatesResponseTypeDef,
     ComponentTypeDef,
     ComponentDeploymentSpecificationTypeDef,
     ListEffectiveDeploymentsResponseTypeDef,
     IoTJobExecutionsRolloutConfigTypeDef,
     LambdaLinuxProcessParamsTypeDef,
     ListComponentsResponseTypeDef,
@@ -478,43 +478,43 @@
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

### Comparing `types-aiobotocore-greengrassv2-2.5.0.post1/types_aiobotocore_greengrassv2.egg-info/SOURCES.txt` & `types-aiobotocore-greengrassv2-2.5.1/types_aiobotocore_greengrassv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

