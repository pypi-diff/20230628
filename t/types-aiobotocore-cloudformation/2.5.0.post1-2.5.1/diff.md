# Comparing `tmp/types-aiobotocore-cloudformation-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudformation-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudformation-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudformation-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudformation-2.5.0.post1.tar` & `types-aiobotocore-cloudformation-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.927024 types-aiobotocore-cloudformation-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    30106 2023-03-11 12:26:19.919024 types-aiobotocore-cloudformation-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    28507 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.927024 types-aiobotocore-cloudformation-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.915024 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/
--rw-r--r--   0 runner    (1001) docker     (123)     5254 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5253 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    66562 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    66465 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17962 2023-03-11 12:10:45.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    17960 2023-03-11 12:10:45.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    18150 2023-03-11 12:10:44.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    18133 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25671 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    25624 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    90573 2023-03-11 12:10:46.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    90460 2023-03-11 12:10:46.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:43.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     9291 2023-03-11 12:10:44.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     9283 2023-03-11 12:10:44.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.919024 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    30106 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1140 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:19.000000 types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.306107 types-aiobotocore-cloudformation-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    30039 2023-06-28 01:43:13.302107 types-aiobotocore-cloudformation-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    28446 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.306107 types-aiobotocore-cloudformation-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.302107 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/
+-rw-r--r--   0 runner    (1001) docker     (123)     5254 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5253 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68293 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68193 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    18426 2023-06-28 01:27:22.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18424 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    18058 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18042 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25564 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25517 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    90394 2023-06-28 01:27:23.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    90281 2023-06-28 01:27:23.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:20.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9291 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9283 2023-06-28 01:27:21.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.302107 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    30039 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1140 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:13.000000 types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudformation-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudformation-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudformation
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudFormation 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudFormation 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudformation"></a>
 
 # types-aiobotocore-cloudformation
 
 [![PyPI - types-aiobotocore-cloudformation](https://img.shields.io/pypi/v/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
+[aiobotocore.CloudFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
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
 [types-aiobotocore-cloudformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -497,16 +497,18 @@
     ListStackResourcesPaginatorName,
     ListStackSetOperationResultsPaginatorName,
     ListStackSetOperationsPaginatorName,
     ListStackSetsPaginatorName,
     ListStacksPaginatorName,
     ListTypesPaginatorName,
     OnFailureType,
+    OnStackFailureType,
     OperationResultFilterNameType,
     OperationStatusType,
+    OrganizationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     PublisherStatusType,
     RegionConcurrencyTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ReplacementType,
@@ -560,168 +562,165 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudformation.type_defs import (
     AccountGateResultTypeDef,
     AccountLimitTypeDef,
     LoggingConfigTypeDef,
-    ResponseMetadataTypeDef,
+    ActivateTypeOutputTypeDef,
     AutoDeploymentTypeDef,
     TypeConfigurationIdentifierTypeDef,
     TypeConfigurationDetailsTypeDef,
     CancelUpdateStackInputRequestTypeDef,
     CancelUpdateStackInputStackCancelUpdateTypeDef,
     ChangeSetHookResourceTargetDetailsTypeDef,
     ChangeSetSummaryTypeDef,
     ContinueUpdateRollbackInputRequestTypeDef,
     ParameterTypeDef,
     ResourceToImportTypeDef,
     TagTypeDef,
+    CreateChangeSetOutputTypeDef,
     DeploymentTargetsTypeDef,
     StackSetOperationPreferencesTypeDef,
+    CreateStackInstancesOutputTypeDef,
+    CreateStackOutputTypeDef,
     ManagedExecutionTypeDef,
+    CreateStackSetOutputTypeDef,
     DeactivateTypeInputRequestTypeDef,
     DeleteChangeSetInputRequestTypeDef,
     DeleteStackInputRequestTypeDef,
     DeleteStackInputStackDeleteTypeDef,
+    DeleteStackInstancesOutputTypeDef,
     DeleteStackSetInputRequestTypeDef,
     DeregisterTypeInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     DescribeChangeSetHooksInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
     DescribeChangeSetInputRequestTypeDef,
+    DescribeOrganizationsAccessInputRequestTypeDef,
+    DescribeOrganizationsAccessOutputTypeDef,
     DescribePublisherInputRequestTypeDef,
+    DescribePublisherOutputTypeDef,
     DescribeStackDriftDetectionStatusInputRequestTypeDef,
+    DescribeStackDriftDetectionStatusOutputTypeDef,
+    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
     DescribeStackEventsInputRequestTypeDef,
     StackEventTypeDef,
     DescribeStackInstanceInputRequestTypeDef,
     DescribeStackResourceDriftsInputRequestTypeDef,
     DescribeStackResourceInputRequestTypeDef,
     DescribeStackResourcesInputRequestTypeDef,
     DescribeStackSetInputRequestTypeDef,
     DescribeStackSetOperationInputRequestTypeDef,
+    DescribeStacksInputDescribeStacksPaginateTypeDef,
     DescribeStacksInputRequestTypeDef,
     DescribeTypeInputRequestTypeDef,
     RequiredActivatedTypeTypeDef,
     DescribeTypeRegistrationInputRequestTypeDef,
+    DescribeTypeRegistrationOutputTypeDef,
     DetectStackDriftInputRequestTypeDef,
+    DetectStackDriftOutputTypeDef,
     DetectStackResourceDriftInputRequestTypeDef,
+    DetectStackSetDriftOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    EstimateTemplateCostOutputTypeDef,
     ExecuteChangeSetInputRequestTypeDef,
     ExportTypeDef,
     GetStackPolicyInputRequestTypeDef,
+    GetStackPolicyOutputTypeDef,
     GetTemplateInputRequestTypeDef,
+    GetTemplateOutputTypeDef,
     GetTemplateSummaryInputRequestTypeDef,
     ResourceIdentifierSummaryTypeDef,
+    ImportStacksToStackSetOutputTypeDef,
+    ListChangeSetsInputListChangeSetsPaginateTypeDef,
     ListChangeSetsInputRequestTypeDef,
+    ListExportsInputListExportsPaginateTypeDef,
     ListExportsInputRequestTypeDef,
+    ListImportsInputListImportsPaginateTypeDef,
     ListImportsInputRequestTypeDef,
+    ListImportsOutputTypeDef,
     StackInstanceFilterTypeDef,
+    ListStackResourcesInputListStackResourcesPaginateTypeDef,
     ListStackResourcesInputRequestTypeDef,
     OperationResultFilterTypeDef,
+    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
     ListStackSetOperationsInputRequestTypeDef,
+    ListStackSetsInputListStackSetsPaginateTypeDef,
     ListStackSetsInputRequestTypeDef,
+    ListStacksInputListStacksPaginateTypeDef,
     ListStacksInputRequestTypeDef,
     ListTypeRegistrationsInputRequestTypeDef,
+    ListTypeRegistrationsOutputTypeDef,
     ListTypeVersionsInputRequestTypeDef,
     TypeVersionSummaryTypeDef,
     TypeFiltersTypeDef,
     TypeSummaryTypeDef,
+    ModuleInfoResponseMetadataTypeDef,
     ModuleInfoTypeDef,
     OutputTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     PhysicalResourceIdContextKeyValuePairTypeDef,
     PropertyDifferenceTypeDef,
     PublishTypeInputRequestTypeDef,
+    PublishTypeOutputTypeDef,
     RecordHandlerProgressInputRequestTypeDef,
     RegisterPublisherInputRequestTypeDef,
+    RegisterPublisherOutputTypeDef,
+    RegisterTypeOutputTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     RollbackStackInputRequestTypeDef,
-    ServiceResourceEventRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackResourceRequestTypeDef,
-    ServiceResourceStackResourceSummaryRequestTypeDef,
+    RollbackStackOutputTypeDef,
     SetStackPolicyInputRequestTypeDef,
     SetTypeConfigurationInputRequestTypeDef,
+    SetTypeConfigurationOutputTypeDef,
     SetTypeDefaultVersionInputRequestTypeDef,
     SignalResourceInputRequestTypeDef,
+    StackDriftInformationResponseMetadataTypeDef,
     StackDriftInformationSummaryTypeDef,
     StackDriftInformationTypeDef,
     StackInstanceComprehensiveStatusTypeDef,
     StackResourceDriftInformationTypeDef,
+    StackResourceDriftInformationResponseMetadataTypeDef,
+    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     StackResourceDriftInformationSummaryTypeDef,
-    StackResourceRequestTypeDef,
     StackSetDriftDetectionDetailsTypeDef,
     StackSetOperationStatusDetailsTypeDef,
     StopStackSetOperationInputRequestTypeDef,
     TemplateParameterTypeDef,
     TestTypeInputRequestTypeDef,
-    UpdateTerminationProtectionInputRequestTypeDef,
-    ValidateTemplateInputRequestTypeDef,
-    StackSetOperationResultSummaryTypeDef,
-    ActivateTypeInputRequestTypeDef,
-    RegisterTypeInputRequestTypeDef,
-    ActivateTypeOutputTypeDef,
-    CreateChangeSetOutputTypeDef,
-    CreateStackInstancesOutputTypeDef,
-    CreateStackOutputTypeDef,
-    CreateStackSetOutputTypeDef,
-    DeleteStackInstancesOutputTypeDef,
-    DescribeAccountLimitsOutputTypeDef,
-    DescribePublisherOutputTypeDef,
-    DescribeStackDriftDetectionStatusOutputTypeDef,
-    DescribeTypeRegistrationOutputTypeDef,
-    DetectStackDriftOutputTypeDef,
-    DetectStackSetDriftOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EstimateTemplateCostOutputTypeDef,
-    GetStackPolicyOutputTypeDef,
-    GetTemplateOutputTypeDef,
-    ImportStacksToStackSetOutputTypeDef,
-    ListImportsOutputTypeDef,
-    ListTypeRegistrationsOutputTypeDef,
-    ModuleInfoResponseMetadataTypeDef,
-    PublishTypeOutputTypeDef,
-    RegisterPublisherOutputTypeDef,
-    RegisterTypeOutputTypeDef,
-    RollbackStackOutputTypeDef,
-    SetTypeConfigurationOutputTypeDef,
-    StackDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     TestTypeOutputTypeDef,
     UpdateStackInstancesOutputTypeDef,
     UpdateStackOutputTypeDef,
     UpdateStackSetOutputTypeDef,
+    UpdateTerminationProtectionInputRequestTypeDef,
     UpdateTerminationProtectionOutputTypeDef,
+    ValidateTemplateInputRequestTypeDef,
+    StackSetOperationResultSummaryTypeDef,
+    DescribeAccountLimitsOutputTypeDef,
+    ActivateTypeInputRequestTypeDef,
+    RegisterTypeInputRequestTypeDef,
     BatchDescribeTypeConfigurationsErrorTypeDef,
     BatchDescribeTypeConfigurationsInputRequestTypeDef,
     ChangeSetHookTargetDetailsTypeDef,
     ListChangeSetsOutputTypeDef,
     EstimateTemplateCostInputRequestTypeDef,
     CreateStackInstancesInputRequestTypeDef,
     DeleteStackInstancesInputRequestTypeDef,
     DetectStackSetDriftInputRequestTypeDef,
     ImportStacksToStackSetInputRequestTypeDef,
     UpdateStackInstancesInputRequestTypeDef,
     CreateStackSetInputRequestTypeDef,
     StackSetSummaryTypeDef,
     UpdateStackSetInputRequestTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
-    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
-    DescribeStacksInputDescribeStacksPaginateTypeDef,
-    ListChangeSetsInputListChangeSetsPaginateTypeDef,
-    ListExportsInputListExportsPaginateTypeDef,
-    ListImportsInputListImportsPaginateTypeDef,
-    ListStackResourcesInputListStackResourcesPaginateTypeDef,
-    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-    ListStackSetsInputListStackSetsPaginateTypeDef,
-    ListStacksInputListStacksPaginateTypeDef,
     DescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef,
     DescribeStacksInputStackCreateCompleteWaitTypeDef,
     DescribeStacksInputStackDeleteCompleteWaitTypeDef,
     DescribeStacksInputStackExistsWaitTypeDef,
     DescribeStacksInputStackImportCompleteWaitTypeDef,
     DescribeStacksInputStackRollbackCompleteWaitTypeDef,
     DescribeStacksInputStackUpdateCompleteWaitTypeDef,
@@ -789,43 +788,43 @@
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/README.md` & `types-aiobotocore-cloudformation-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudformation"></a>
 
 # types-aiobotocore-cloudformation
 
 [![PyPI - types-aiobotocore-cloudformation](https://img.shields.io/pypi/v/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
+[aiobotocore.CloudFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
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
 [types-aiobotocore-cloudformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -464,16 +464,18 @@
     ListStackResourcesPaginatorName,
     ListStackSetOperationResultsPaginatorName,
     ListStackSetOperationsPaginatorName,
     ListStackSetsPaginatorName,
     ListStacksPaginatorName,
     ListTypesPaginatorName,
     OnFailureType,
+    OnStackFailureType,
     OperationResultFilterNameType,
     OperationStatusType,
+    OrganizationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     PublisherStatusType,
     RegionConcurrencyTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ReplacementType,
@@ -527,168 +529,165 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudformation.type_defs import (
     AccountGateResultTypeDef,
     AccountLimitTypeDef,
     LoggingConfigTypeDef,
-    ResponseMetadataTypeDef,
+    ActivateTypeOutputTypeDef,
     AutoDeploymentTypeDef,
     TypeConfigurationIdentifierTypeDef,
     TypeConfigurationDetailsTypeDef,
     CancelUpdateStackInputRequestTypeDef,
     CancelUpdateStackInputStackCancelUpdateTypeDef,
     ChangeSetHookResourceTargetDetailsTypeDef,
     ChangeSetSummaryTypeDef,
     ContinueUpdateRollbackInputRequestTypeDef,
     ParameterTypeDef,
     ResourceToImportTypeDef,
     TagTypeDef,
+    CreateChangeSetOutputTypeDef,
     DeploymentTargetsTypeDef,
     StackSetOperationPreferencesTypeDef,
+    CreateStackInstancesOutputTypeDef,
+    CreateStackOutputTypeDef,
     ManagedExecutionTypeDef,
+    CreateStackSetOutputTypeDef,
     DeactivateTypeInputRequestTypeDef,
     DeleteChangeSetInputRequestTypeDef,
     DeleteStackInputRequestTypeDef,
     DeleteStackInputStackDeleteTypeDef,
+    DeleteStackInstancesOutputTypeDef,
     DeleteStackSetInputRequestTypeDef,
     DeregisterTypeInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     DescribeChangeSetHooksInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
     DescribeChangeSetInputRequestTypeDef,
+    DescribeOrganizationsAccessInputRequestTypeDef,
+    DescribeOrganizationsAccessOutputTypeDef,
     DescribePublisherInputRequestTypeDef,
+    DescribePublisherOutputTypeDef,
     DescribeStackDriftDetectionStatusInputRequestTypeDef,
+    DescribeStackDriftDetectionStatusOutputTypeDef,
+    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
     DescribeStackEventsInputRequestTypeDef,
     StackEventTypeDef,
     DescribeStackInstanceInputRequestTypeDef,
     DescribeStackResourceDriftsInputRequestTypeDef,
     DescribeStackResourceInputRequestTypeDef,
     DescribeStackResourcesInputRequestTypeDef,
     DescribeStackSetInputRequestTypeDef,
     DescribeStackSetOperationInputRequestTypeDef,
+    DescribeStacksInputDescribeStacksPaginateTypeDef,
     DescribeStacksInputRequestTypeDef,
     DescribeTypeInputRequestTypeDef,
     RequiredActivatedTypeTypeDef,
     DescribeTypeRegistrationInputRequestTypeDef,
+    DescribeTypeRegistrationOutputTypeDef,
     DetectStackDriftInputRequestTypeDef,
+    DetectStackDriftOutputTypeDef,
     DetectStackResourceDriftInputRequestTypeDef,
+    DetectStackSetDriftOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    EstimateTemplateCostOutputTypeDef,
     ExecuteChangeSetInputRequestTypeDef,
     ExportTypeDef,
     GetStackPolicyInputRequestTypeDef,
+    GetStackPolicyOutputTypeDef,
     GetTemplateInputRequestTypeDef,
+    GetTemplateOutputTypeDef,
     GetTemplateSummaryInputRequestTypeDef,
     ResourceIdentifierSummaryTypeDef,
+    ImportStacksToStackSetOutputTypeDef,
+    ListChangeSetsInputListChangeSetsPaginateTypeDef,
     ListChangeSetsInputRequestTypeDef,
+    ListExportsInputListExportsPaginateTypeDef,
     ListExportsInputRequestTypeDef,
+    ListImportsInputListImportsPaginateTypeDef,
     ListImportsInputRequestTypeDef,
+    ListImportsOutputTypeDef,
     StackInstanceFilterTypeDef,
+    ListStackResourcesInputListStackResourcesPaginateTypeDef,
     ListStackResourcesInputRequestTypeDef,
     OperationResultFilterTypeDef,
+    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
     ListStackSetOperationsInputRequestTypeDef,
+    ListStackSetsInputListStackSetsPaginateTypeDef,
     ListStackSetsInputRequestTypeDef,
+    ListStacksInputListStacksPaginateTypeDef,
     ListStacksInputRequestTypeDef,
     ListTypeRegistrationsInputRequestTypeDef,
+    ListTypeRegistrationsOutputTypeDef,
     ListTypeVersionsInputRequestTypeDef,
     TypeVersionSummaryTypeDef,
     TypeFiltersTypeDef,
     TypeSummaryTypeDef,
+    ModuleInfoResponseMetadataTypeDef,
     ModuleInfoTypeDef,
     OutputTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     PhysicalResourceIdContextKeyValuePairTypeDef,
     PropertyDifferenceTypeDef,
     PublishTypeInputRequestTypeDef,
+    PublishTypeOutputTypeDef,
     RecordHandlerProgressInputRequestTypeDef,
     RegisterPublisherInputRequestTypeDef,
+    RegisterPublisherOutputTypeDef,
+    RegisterTypeOutputTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     RollbackStackInputRequestTypeDef,
-    ServiceResourceEventRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackResourceRequestTypeDef,
-    ServiceResourceStackResourceSummaryRequestTypeDef,
+    RollbackStackOutputTypeDef,
     SetStackPolicyInputRequestTypeDef,
     SetTypeConfigurationInputRequestTypeDef,
+    SetTypeConfigurationOutputTypeDef,
     SetTypeDefaultVersionInputRequestTypeDef,
     SignalResourceInputRequestTypeDef,
+    StackDriftInformationResponseMetadataTypeDef,
     StackDriftInformationSummaryTypeDef,
     StackDriftInformationTypeDef,
     StackInstanceComprehensiveStatusTypeDef,
     StackResourceDriftInformationTypeDef,
+    StackResourceDriftInformationResponseMetadataTypeDef,
+    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     StackResourceDriftInformationSummaryTypeDef,
-    StackResourceRequestTypeDef,
     StackSetDriftDetectionDetailsTypeDef,
     StackSetOperationStatusDetailsTypeDef,
     StopStackSetOperationInputRequestTypeDef,
     TemplateParameterTypeDef,
     TestTypeInputRequestTypeDef,
-    UpdateTerminationProtectionInputRequestTypeDef,
-    ValidateTemplateInputRequestTypeDef,
-    StackSetOperationResultSummaryTypeDef,
-    ActivateTypeInputRequestTypeDef,
-    RegisterTypeInputRequestTypeDef,
-    ActivateTypeOutputTypeDef,
-    CreateChangeSetOutputTypeDef,
-    CreateStackInstancesOutputTypeDef,
-    CreateStackOutputTypeDef,
-    CreateStackSetOutputTypeDef,
-    DeleteStackInstancesOutputTypeDef,
-    DescribeAccountLimitsOutputTypeDef,
-    DescribePublisherOutputTypeDef,
-    DescribeStackDriftDetectionStatusOutputTypeDef,
-    DescribeTypeRegistrationOutputTypeDef,
-    DetectStackDriftOutputTypeDef,
-    DetectStackSetDriftOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EstimateTemplateCostOutputTypeDef,
-    GetStackPolicyOutputTypeDef,
-    GetTemplateOutputTypeDef,
-    ImportStacksToStackSetOutputTypeDef,
-    ListImportsOutputTypeDef,
-    ListTypeRegistrationsOutputTypeDef,
-    ModuleInfoResponseMetadataTypeDef,
-    PublishTypeOutputTypeDef,
-    RegisterPublisherOutputTypeDef,
-    RegisterTypeOutputTypeDef,
-    RollbackStackOutputTypeDef,
-    SetTypeConfigurationOutputTypeDef,
-    StackDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     TestTypeOutputTypeDef,
     UpdateStackInstancesOutputTypeDef,
     UpdateStackOutputTypeDef,
     UpdateStackSetOutputTypeDef,
+    UpdateTerminationProtectionInputRequestTypeDef,
     UpdateTerminationProtectionOutputTypeDef,
+    ValidateTemplateInputRequestTypeDef,
+    StackSetOperationResultSummaryTypeDef,
+    DescribeAccountLimitsOutputTypeDef,
+    ActivateTypeInputRequestTypeDef,
+    RegisterTypeInputRequestTypeDef,
     BatchDescribeTypeConfigurationsErrorTypeDef,
     BatchDescribeTypeConfigurationsInputRequestTypeDef,
     ChangeSetHookTargetDetailsTypeDef,
     ListChangeSetsOutputTypeDef,
     EstimateTemplateCostInputRequestTypeDef,
     CreateStackInstancesInputRequestTypeDef,
     DeleteStackInstancesInputRequestTypeDef,
     DetectStackSetDriftInputRequestTypeDef,
     ImportStacksToStackSetInputRequestTypeDef,
     UpdateStackInstancesInputRequestTypeDef,
     CreateStackSetInputRequestTypeDef,
     StackSetSummaryTypeDef,
     UpdateStackSetInputRequestTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
-    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
-    DescribeStacksInputDescribeStacksPaginateTypeDef,
-    ListChangeSetsInputListChangeSetsPaginateTypeDef,
-    ListExportsInputListExportsPaginateTypeDef,
-    ListImportsInputListImportsPaginateTypeDef,
-    ListStackResourcesInputListStackResourcesPaginateTypeDef,
-    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-    ListStackSetsInputListStackSetsPaginateTypeDef,
-    ListStacksInputListStacksPaginateTypeDef,
     DescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef,
     DescribeStacksInputStackCreateCompleteWaitTypeDef,
     DescribeStacksInputStackDeleteCompleteWaitTypeDef,
     DescribeStacksInputStackExistsWaitTypeDef,
     DescribeStacksInputStackImportCompleteWaitTypeDef,
     DescribeStacksInputStackRollbackCompleteWaitTypeDef,
     DescribeStacksInputStackUpdateCompleteWaitTypeDef,
@@ -756,43 +755,43 @@
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/setup.py` & `types-aiobotocore-cloudformation-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudformation.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudformation",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudformation"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudFormation 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudFormation 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/"
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__init__.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__init__.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/__main__.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudFormation 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudFormation 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation\nOther"
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/client.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,14 +23,15 @@
 from .literals import (
     CallAsType,
     CapabilityType,
     ChangeSetTypeType,
     DeprecatedStatusType,
     HandlerErrorCodeType,
     OnFailureType,
+    OnStackFailureType,
     OperationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ResourceSignalStatusType,
     StackResourceDriftStatusType,
@@ -66,14 +67,15 @@
     CreateStackOutputTypeDef,
     CreateStackSetOutputTypeDef,
     DeleteStackInstancesOutputTypeDef,
     DeploymentTargetsTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     DescribeChangeSetHooksOutputTypeDef,
     DescribeChangeSetOutputTypeDef,
+    DescribeOrganizationsAccessOutputTypeDef,
     DescribePublisherOutputTypeDef,
     DescribeStackDriftDetectionStatusOutputTypeDef,
     DescribeStackEventsOutputTypeDef,
     DescribeStackInstanceOutputTypeDef,
     DescribeStackResourceDriftsOutputTypeDef,
     DescribeStackResourceOutputTypeDef,
     DescribeStackResourcesOutputTypeDef,
@@ -193,14 +195,22 @@
         """
         CloudFormationClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#exceptions)
         """
 
+    async def activate_organizations_access(self) -> Dict[str, Any]:
+        """
+        Activate trusted access with Organizations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.activate_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#activate_organizations_access)
+        """
+
     async def activate_type(
         self,
         *,
         Type: ThirdPartyTypeType = ...,
         PublicTypeArn: str = ...,
         PublisherId: str = ...,
         TypeName: str = ...,
@@ -220,15 +230,15 @@
         """
 
     async def batch_describe_type_configurations(
         self, *, TypeConfigurationIdentifiers: Sequence[TypeConfigurationIdentifierTypeDef]
     ) -> BatchDescribeTypeConfigurationsOutputTypeDef:
         """
         Returns configuration data for the specified CloudFormation extensions, from the
-        CloudFormation registry for the account and region.
+        CloudFormation registry for the account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.batch_describe_type_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#batch_describe_type_configurations)
         """
 
     def can_paginate(self, operation_name: str) -> bool:
         """
@@ -287,15 +297,16 @@
         RollbackConfiguration: RollbackConfigurationTypeDef = ...,
         NotificationARNs: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ClientToken: str = ...,
         Description: str = ...,
         ChangeSetType: ChangeSetTypeType = ...,
         ResourcesToImport: Sequence[ResourceToImportTypeDef] = ...,
-        IncludeNestedStacks: bool = ...
+        IncludeNestedStacks: bool = ...,
+        OnStackFailure: OnStackFailureType = ...
     ) -> CreateChangeSetOutputTypeDef:
         """
         Creates a list of changes that will be applied to a stack so that you can review
         the changes before executing them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_change_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#create_change_set)
@@ -371,20 +382,28 @@
         """
         Creates a stack set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_stack_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#create_stack_set)
         """
 
+    async def deactivate_organizations_access(self) -> Dict[str, Any]:
+        """
+        Deactivates trusted access with Organizations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deactivate_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#deactivate_organizations_access)
+        """
+
     async def deactivate_type(
         self, *, TypeName: str = ..., Type: ThirdPartyTypeType = ..., Arn: str = ...
     ) -> Dict[str, Any]:
         """
         Deactivates a public extension that was previously activated in this account and
-        region.
+        Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deactivate_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#deactivate_type)
         """
 
     async def delete_change_set(
         self, *, ChangeSetName: str, StackName: str = ...
@@ -491,14 +510,24 @@
         Returns hook-related information for the change set and a list of changes that
         CloudFormation makes when you run the change set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_change_set_hooks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_change_set_hooks)
         """
 
+    async def describe_organizations_access(
+        self, *, CallAs: CallAsType = ...
+    ) -> DescribeOrganizationsAccessOutputTypeDef:
+        """
+        Retrieves information about the account's `OrganizationAccess` status.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_organizations_access)
+        """
+
     async def describe_publisher(self, *, PublisherId: str = ...) -> DescribePublisherOutputTypeDef:
         """
         Returns information about a CloudFormation extension publisher.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_publisher)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_publisher)
         """
@@ -529,16 +558,16 @@
         *,
         StackSetName: str,
         StackInstanceAccount: str,
         StackInstanceRegion: str,
         CallAs: CallAsType = ...
     ) -> DescribeStackInstanceOutputTypeDef:
         """
-        Returns the stack instance that's associated with the specified stack set,
-        Amazon Web Services account, and Region.
+        Returns the stack instance that's associated with the specified StackSet, Amazon
+        Web Services account, and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_instance)
         """
 
     async def describe_stack_resource(
         self, *, StackName: str, LogicalResourceId: str
@@ -577,25 +606,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_resources)
         """
 
     async def describe_stack_set(
         self, *, StackSetName: str, CallAs: CallAsType = ...
     ) -> DescribeStackSetOutputTypeDef:
         """
-        Returns the description of the specified stack set.
+        Returns the description of the specified StackSet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_set)
         """
 
     async def describe_stack_set_operation(
         self, *, StackSetName: str, OperationId: str, CallAs: CallAsType = ...
     ) -> DescribeStackSetOperationOutputTypeDef:
         """
-        Returns the description of the specified stack set operation.
+        Returns the description of the specified StackSet operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_set_operation)
         """
 
     async def describe_stacks(
         self, *, StackName: str = ..., NextToken: str = ...
@@ -636,29 +665,29 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_type_registration)
         """
 
     async def detect_stack_drift(
         self, *, StackName: str, LogicalResourceIds: Sequence[str] = ...
     ) -> DetectStackDriftOutputTypeDef:
         """
-        Detects whether a stack's actual configuration differs, or has *drifted* , from
-        it's expected configuration, as defined in the stack template and any values
+        Detects whether a stack's actual configuration differs, or has *drifted*, from
+        its expected configuration, as defined in the stack template and any values
         specified as template parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_drift)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#detect_stack_drift)
         """
 
     async def detect_stack_resource_drift(
         self, *, StackName: str, LogicalResourceId: str
     ) -> DetectStackResourceDriftOutputTypeDef:
         """
         Returns information about whether a resource's actual configuration differs, or
-        has *drifted* , from it's expected configuration, as defined in the stack
-        template and any values specified as template parameters.
+        has *drifted*, from its expected configuration, as defined in the stack template
+        and any values specified as template parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_resource_drift)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#detect_stack_resource_drift)
         """
 
     async def detect_stack_set_drift(
         self,
@@ -951,15 +980,15 @@
         Type: ThirdPartyTypeType = ...,
         Arn: str = ...,
         TypeName: str = ...,
         PublicVersionNumber: str = ...
     ) -> PublishTypeOutputTypeDef:
         """
         Publishes the specified extension to the CloudFormation registry as a public
-        extension in this region.
+        extension in this Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.publish_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#publish_type)
         """
 
     async def record_handler_progress(
         self,
@@ -1007,15 +1036,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#register_type)
         """
 
     async def rollback_stack(
         self, *, StackName: str, RoleARN: str = ..., ClientRequestToken: str = ...
     ) -> RollbackStackOutputTypeDef:
         """
-        When specifying `RollbackStack` , you preserve the state of previously
+        When specifying `RollbackStack`, you preserve the state of previously
         provisioned resources when an operation fails.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.rollback_stack)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#rollback_stack)
         """
 
     async def set_stack_policy(
@@ -1035,15 +1064,15 @@
         TypeArn: str = ...,
         ConfigurationAlias: str = ...,
         TypeName: str = ...,
         Type: ThirdPartyTypeType = ...
     ) -> SetTypeConfigurationOutputTypeDef:
         """
         Specifies the configuration data for a registered CloudFormation extension, in
-        the given account and region.
+        the given account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.set_type_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#set_type_configuration)
         """
 
     async def set_type_default_version(
         self,
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/client.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -23,14 +23,15 @@
 from .literals import (
     CallAsType,
     CapabilityType,
     ChangeSetTypeType,
     DeprecatedStatusType,
     HandlerErrorCodeType,
     OnFailureType,
+    OnStackFailureType,
     OperationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ResourceSignalStatusType,
     StackResourceDriftStatusType,
@@ -66,14 +67,15 @@
     CreateStackOutputTypeDef,
     CreateStackSetOutputTypeDef,
     DeleteStackInstancesOutputTypeDef,
     DeploymentTargetsTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     DescribeChangeSetHooksOutputTypeDef,
     DescribeChangeSetOutputTypeDef,
+    DescribeOrganizationsAccessOutputTypeDef,
     DescribePublisherOutputTypeDef,
     DescribeStackDriftDetectionStatusOutputTypeDef,
     DescribeStackEventsOutputTypeDef,
     DescribeStackInstanceOutputTypeDef,
     DescribeStackResourceDriftsOutputTypeDef,
     DescribeStackResourceOutputTypeDef,
     DescribeStackResourcesOutputTypeDef,
@@ -188,14 +190,21 @@
     def exceptions(self) -> Exceptions:
         """
         CloudFormationClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#exceptions)
         """
+    async def activate_organizations_access(self) -> Dict[str, Any]:
+        """
+        Activate trusted access with Organizations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.activate_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#activate_organizations_access)
+        """
     async def activate_type(
         self,
         *,
         Type: ThirdPartyTypeType = ...,
         PublicTypeArn: str = ...,
         PublisherId: str = ...,
         TypeName: str = ...,
@@ -214,15 +223,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#activate_type)
         """
     async def batch_describe_type_configurations(
         self, *, TypeConfigurationIdentifiers: Sequence[TypeConfigurationIdentifierTypeDef]
     ) -> BatchDescribeTypeConfigurationsOutputTypeDef:
         """
         Returns configuration data for the specified CloudFormation extensions, from the
-        CloudFormation registry for the account and region.
+        CloudFormation registry for the account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.batch_describe_type_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#batch_describe_type_configurations)
         """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
@@ -276,15 +285,16 @@
         RollbackConfiguration: RollbackConfigurationTypeDef = ...,
         NotificationARNs: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ClientToken: str = ...,
         Description: str = ...,
         ChangeSetType: ChangeSetTypeType = ...,
         ResourcesToImport: Sequence[ResourceToImportTypeDef] = ...,
-        IncludeNestedStacks: bool = ...
+        IncludeNestedStacks: bool = ...,
+        OnStackFailure: OnStackFailureType = ...
     ) -> CreateChangeSetOutputTypeDef:
         """
         Creates a list of changes that will be applied to a stack so that you can review
         the changes before executing them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_change_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#create_change_set)
@@ -356,20 +366,27 @@
     ) -> CreateStackSetOutputTypeDef:
         """
         Creates a stack set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.create_stack_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#create_stack_set)
         """
+    async def deactivate_organizations_access(self) -> Dict[str, Any]:
+        """
+        Deactivates trusted access with Organizations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deactivate_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#deactivate_organizations_access)
+        """
     async def deactivate_type(
         self, *, TypeName: str = ..., Type: ThirdPartyTypeType = ..., Arn: str = ...
     ) -> Dict[str, Any]:
         """
         Deactivates a public extension that was previously activated in this account and
-        region.
+        Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.deactivate_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#deactivate_type)
         """
     async def delete_change_set(
         self, *, ChangeSetName: str, StackName: str = ...
     ) -> Dict[str, Any]:
@@ -467,14 +484,23 @@
         """
         Returns hook-related information for the change set and a list of changes that
         CloudFormation makes when you run the change set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_change_set_hooks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_change_set_hooks)
         """
+    async def describe_organizations_access(
+        self, *, CallAs: CallAsType = ...
+    ) -> DescribeOrganizationsAccessOutputTypeDef:
+        """
+        Retrieves information about the account's `OrganizationAccess` status.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_organizations_access)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_organizations_access)
+        """
     async def describe_publisher(self, *, PublisherId: str = ...) -> DescribePublisherOutputTypeDef:
         """
         Returns information about a CloudFormation extension publisher.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_publisher)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_publisher)
         """
@@ -502,16 +528,16 @@
         *,
         StackSetName: str,
         StackInstanceAccount: str,
         StackInstanceRegion: str,
         CallAs: CallAsType = ...
     ) -> DescribeStackInstanceOutputTypeDef:
         """
-        Returns the stack instance that's associated with the specified stack set,
-        Amazon Web Services account, and Region.
+        Returns the stack instance that's associated with the specified StackSet, Amazon
+        Web Services account, and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_instance)
         """
     async def describe_stack_resource(
         self, *, StackName: str, LogicalResourceId: str
     ) -> DescribeStackResourceOutputTypeDef:
@@ -546,24 +572,24 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_resources)
         """
     async def describe_stack_set(
         self, *, StackSetName: str, CallAs: CallAsType = ...
     ) -> DescribeStackSetOutputTypeDef:
         """
-        Returns the description of the specified stack set.
+        Returns the description of the specified StackSet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_set)
         """
     async def describe_stack_set_operation(
         self, *, StackSetName: str, OperationId: str, CallAs: CallAsType = ...
     ) -> DescribeStackSetOperationOutputTypeDef:
         """
-        Returns the description of the specified stack set operation.
+        Returns the description of the specified StackSet operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_stack_set_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_stack_set_operation)
         """
     async def describe_stacks(
         self, *, StackName: str = ..., NextToken: str = ...
     ) -> DescribeStacksOutputTypeDef:
@@ -600,28 +626,28 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.describe_type_registration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#describe_type_registration)
         """
     async def detect_stack_drift(
         self, *, StackName: str, LogicalResourceIds: Sequence[str] = ...
     ) -> DetectStackDriftOutputTypeDef:
         """
-        Detects whether a stack's actual configuration differs, or has *drifted* , from
-        it's expected configuration, as defined in the stack template and any values
+        Detects whether a stack's actual configuration differs, or has *drifted*, from
+        its expected configuration, as defined in the stack template and any values
         specified as template parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_drift)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#detect_stack_drift)
         """
     async def detect_stack_resource_drift(
         self, *, StackName: str, LogicalResourceId: str
     ) -> DetectStackResourceDriftOutputTypeDef:
         """
         Returns information about whether a resource's actual configuration differs, or
-        has *drifted* , from it's expected configuration, as defined in the stack
-        template and any values specified as template parameters.
+        has *drifted*, from its expected configuration, as defined in the stack template
+        and any values specified as template parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.detect_stack_resource_drift)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#detect_stack_resource_drift)
         """
     async def detect_stack_set_drift(
         self,
         *,
@@ -893,15 +919,15 @@
         Type: ThirdPartyTypeType = ...,
         Arn: str = ...,
         TypeName: str = ...,
         PublicVersionNumber: str = ...
     ) -> PublishTypeOutputTypeDef:
         """
         Publishes the specified extension to the CloudFormation registry as a public
-        extension in this region.
+        extension in this Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.publish_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#publish_type)
         """
     async def record_handler_progress(
         self,
         *,
@@ -945,15 +971,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.register_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#register_type)
         """
     async def rollback_stack(
         self, *, StackName: str, RoleARN: str = ..., ClientRequestToken: str = ...
     ) -> RollbackStackOutputTypeDef:
         """
-        When specifying `RollbackStack` , you preserve the state of previously
+        When specifying `RollbackStack`, you preserve the state of previously
         provisioned resources when an operation fails.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.rollback_stack)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#rollback_stack)
         """
     async def set_stack_policy(
         self, *, StackName: str, StackPolicyBody: str = ..., StackPolicyURL: str = ...
@@ -971,15 +997,15 @@
         TypeArn: str = ...,
         ConfigurationAlias: str = ...,
         TypeName: str = ...,
         Type: ThirdPartyTypeType = ...
     ) -> SetTypeConfigurationOutputTypeDef:
         """
         Specifies the configuration data for a registered CloudFormation extension, in
-        the given account and region.
+        the given account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Client.set_type_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/client/#set_type_configuration)
         """
     async def set_type_default_version(
         self,
         *,
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/literals.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -53,16 +53,18 @@
     "ListStackResourcesPaginatorName",
     "ListStackSetOperationResultsPaginatorName",
     "ListStackSetOperationsPaginatorName",
     "ListStackSetsPaginatorName",
     "ListStacksPaginatorName",
     "ListTypesPaginatorName",
     "OnFailureType",
+    "OnStackFailureType",
     "OperationResultFilterNameType",
     "OperationStatusType",
+    "OrganizationStatusType",
     "PermissionModelsType",
     "ProvisioningTypeType",
     "PublisherStatusType",
     "RegionConcurrencyTypeType",
     "RegistrationStatusType",
     "RegistryTypeType",
     "ReplacementType",
@@ -181,16 +183,18 @@
 ListStackResourcesPaginatorName = Literal["list_stack_resources"]
 ListStackSetOperationResultsPaginatorName = Literal["list_stack_set_operation_results"]
 ListStackSetOperationsPaginatorName = Literal["list_stack_set_operations"]
 ListStackSetsPaginatorName = Literal["list_stack_sets"]
 ListStacksPaginatorName = Literal["list_stacks"]
 ListTypesPaginatorName = Literal["list_types"]
 OnFailureType = Literal["DELETE", "DO_NOTHING", "ROLLBACK"]
+OnStackFailureType = Literal["DELETE", "DO_NOTHING", "ROLLBACK"]
 OperationResultFilterNameType = Literal["OPERATION_RESULT_STATUS"]
 OperationStatusType = Literal["FAILED", "IN_PROGRESS", "PENDING", "SUCCESS"]
+OrganizationStatusType = Literal["DISABLED", "DISABLED_PERMANENTLY", "ENABLED"]
 PermissionModelsType = Literal["SELF_MANAGED", "SERVICE_MANAGED"]
 ProvisioningTypeType = Literal["FULLY_MUTABLE", "IMMUTABLE", "NON_PROVISIONABLE"]
 PublisherStatusType = Literal["UNVERIFIED", "VERIFIED"]
 RegionConcurrencyTypeType = Literal["PARALLEL", "SEQUENTIAL"]
 RegistrationStatusType = Literal["COMPLETE", "FAILED", "IN_PROGRESS"]
 RegistryTypeType = Literal["HOOK", "MODULE", "RESOURCE"]
 ReplacementType = Literal["Conditional", "False", "True"]
@@ -228,15 +232,21 @@
 StackDriftDetectionStatusType = Literal[
     "DETECTION_COMPLETE", "DETECTION_FAILED", "DETECTION_IN_PROGRESS"
 ]
 StackDriftStatusType = Literal["DRIFTED", "IN_SYNC", "NOT_CHECKED", "UNKNOWN"]
 StackExistsWaiterName = Literal["stack_exists"]
 StackImportCompleteWaiterName = Literal["stack_import_complete"]
 StackInstanceDetailedStatusType = Literal[
-    "CANCELLED", "FAILED", "INOPERABLE", "PENDING", "RUNNING", "SUCCEEDED"
+    "CANCELLED",
+    "FAILED",
+    "INOPERABLE",
+    "PENDING",
+    "RUNNING",
+    "SKIPPED_SUSPENDED_ACCOUNT",
+    "SUCCEEDED",
 ]
 StackInstanceFilterNameType = Literal["DETAILED_STATUS", "LAST_OPERATION_ID"]
 StackInstanceStatusType = Literal["CURRENT", "INOPERABLE", "OUTDATED"]
 StackResourceDriftStatusType = Literal["DELETED", "IN_SYNC", "MODIFIED", "NOT_CHECKED"]
 StackRollbackCompleteWaiterName = Literal["stack_rollback_complete"]
 StackSetDriftDetectionStatusType = Literal[
     "COMPLETED", "FAILED", "IN_PROGRESS", "PARTIAL_SUCCESS", "STOPPED"
@@ -341,14 +351,15 @@
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
@@ -427,14 +438,15 @@
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
@@ -445,14 +457,15 @@
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
@@ -488,14 +501,15 @@
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
@@ -514,16 +528,19 @@
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
@@ -607,15 +624,17 @@
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/literals.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -52,16 +52,18 @@
     "ListStackResourcesPaginatorName",
     "ListStackSetOperationResultsPaginatorName",
     "ListStackSetOperationsPaginatorName",
     "ListStackSetsPaginatorName",
     "ListStacksPaginatorName",
     "ListTypesPaginatorName",
     "OnFailureType",
+    "OnStackFailureType",
     "OperationResultFilterNameType",
     "OperationStatusType",
+    "OrganizationStatusType",
     "PermissionModelsType",
     "ProvisioningTypeType",
     "PublisherStatusType",
     "RegionConcurrencyTypeType",
     "RegistrationStatusType",
     "RegistryTypeType",
     "ReplacementType",
@@ -179,16 +181,18 @@
 ListStackResourcesPaginatorName = Literal["list_stack_resources"]
 ListStackSetOperationResultsPaginatorName = Literal["list_stack_set_operation_results"]
 ListStackSetOperationsPaginatorName = Literal["list_stack_set_operations"]
 ListStackSetsPaginatorName = Literal["list_stack_sets"]
 ListStacksPaginatorName = Literal["list_stacks"]
 ListTypesPaginatorName = Literal["list_types"]
 OnFailureType = Literal["DELETE", "DO_NOTHING", "ROLLBACK"]
+OnStackFailureType = Literal["DELETE", "DO_NOTHING", "ROLLBACK"]
 OperationResultFilterNameType = Literal["OPERATION_RESULT_STATUS"]
 OperationStatusType = Literal["FAILED", "IN_PROGRESS", "PENDING", "SUCCESS"]
+OrganizationStatusType = Literal["DISABLED", "DISABLED_PERMANENTLY", "ENABLED"]
 PermissionModelsType = Literal["SELF_MANAGED", "SERVICE_MANAGED"]
 ProvisioningTypeType = Literal["FULLY_MUTABLE", "IMMUTABLE", "NON_PROVISIONABLE"]
 PublisherStatusType = Literal["UNVERIFIED", "VERIFIED"]
 RegionConcurrencyTypeType = Literal["PARALLEL", "SEQUENTIAL"]
 RegistrationStatusType = Literal["COMPLETE", "FAILED", "IN_PROGRESS"]
 RegistryTypeType = Literal["HOOK", "MODULE", "RESOURCE"]
 ReplacementType = Literal["Conditional", "False", "True"]
@@ -226,15 +230,21 @@
 StackDriftDetectionStatusType = Literal[
     "DETECTION_COMPLETE", "DETECTION_FAILED", "DETECTION_IN_PROGRESS"
 ]
 StackDriftStatusType = Literal["DRIFTED", "IN_SYNC", "NOT_CHECKED", "UNKNOWN"]
 StackExistsWaiterName = Literal["stack_exists"]
 StackImportCompleteWaiterName = Literal["stack_import_complete"]
 StackInstanceDetailedStatusType = Literal[
-    "CANCELLED", "FAILED", "INOPERABLE", "PENDING", "RUNNING", "SUCCEEDED"
+    "CANCELLED",
+    "FAILED",
+    "INOPERABLE",
+    "PENDING",
+    "RUNNING",
+    "SKIPPED_SUSPENDED_ACCOUNT",
+    "SUCCEEDED",
 ]
 StackInstanceFilterNameType = Literal["DETAILED_STATUS", "LAST_OPERATION_ID"]
 StackInstanceStatusType = Literal["CURRENT", "INOPERABLE", "OUTDATED"]
 StackResourceDriftStatusType = Literal["DELETED", "IN_SYNC", "MODIFIED", "NOT_CHECKED"]
 StackRollbackCompleteWaiterName = Literal["stack_rollback_complete"]
 StackSetDriftDetectionStatusType = Literal[
     "COMPLETED", "FAILED", "IN_PROGRESS", "PARTIAL_SUCCESS", "STOPPED"
@@ -339,14 +349,15 @@
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
@@ -425,14 +436,15 @@
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
@@ -443,14 +455,15 @@
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
@@ -486,14 +499,15 @@
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
@@ -512,16 +526,19 @@
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
@@ -605,15 +622,17 @@
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/paginator.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -42,16 +42,15 @@
         list_stack_set_operation_results_paginator: ListStackSetOperationResultsPaginator = client.get_paginator("list_stack_set_operation_results")
         list_stack_set_operations_paginator: ListStackSetOperationsPaginator = client.get_paginator("list_stack_set_operations")
         list_stack_sets_paginator: ListStackSetsPaginator = client.get_paginator("list_stack_sets")
         list_stacks_paginator: ListStacksPaginator = client.get_paginator("list_stacks")
         list_types_paginator: ListTypesPaginator = client.get_paginator("list_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     CallAsType,
     DeprecatedStatusType,
@@ -78,20 +77,14 @@
     ListTypesOutputTypeDef,
     OperationResultFilterTypeDef,
     PaginatorConfigTypeDef,
     StackInstanceFilterTypeDef,
     TypeFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAccountLimitsPaginator",
     "DescribeChangeSetPaginator",
     "DescribeStackEventsPaginator",
     "DescribeStacksPaginator",
     "ListChangeSetsPaginator",
     "ListExportsPaginator",
@@ -119,15 +112,15 @@
 class DescribeAccountLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeAccountLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describeaccountlimitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccountLimitsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeAccountLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describeaccountlimitspaginator)
         """
 
 
@@ -138,90 +131,90 @@
     """
 
     def paginate(
         self,
         *,
         ChangeSetName: str,
         StackName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeChangeSetOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeChangeSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describechangesetpaginator)
         """
 
 
 class DescribeStackEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStackEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackeventspaginator)
     """
 
     def paginate(
-        self, *, StackName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStackEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStackEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackeventspaginator)
         """
 
 
 class DescribeStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackspaginator)
     """
 
     def paginate(
-        self, *, StackName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStacksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackspaginator)
         """
 
 
 class ListChangeSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListChangeSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listchangesetspaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChangeSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListChangeSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listchangesetspaginator)
         """
 
 
 class ListExportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListExports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listexportspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListExports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listexportspaginator)
         """
 
 
 class ListImportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListImports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listimportspaginator)
     """
 
     def paginate(
-        self, *, ExportName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ExportName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListImports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listimportspaginator)
         """
 
 
@@ -235,30 +228,30 @@
         self,
         *,
         StackSetName: str,
         Filters: Sequence[StackInstanceFilterTypeDef] = ...,
         StackInstanceAccount: str = ...,
         StackInstanceRegion: str = ...,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackinstancespaginator)
         """
 
 
 class ListStackResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackresourcespaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackresourcespaginator)
         """
 
 
@@ -271,15 +264,15 @@
     def paginate(
         self,
         *,
         StackSetName: str,
         OperationId: str,
         CallAs: CallAsType = ...,
         Filters: Sequence[OperationResultFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetOperationResultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSetOperationResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetoperationresultspaginator)
         """
 
 
@@ -290,15 +283,15 @@
     """
 
     def paginate(
         self,
         *,
         StackSetName: str,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSetOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetoperationspaginator)
         """
 
 
@@ -309,15 +302,15 @@
     """
 
     def paginate(
         self,
         *,
         Status: StackSetStatusType = ...,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetspaginator)
         """
 
 
@@ -327,15 +320,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackspaginator)
     """
 
     def paginate(
         self,
         *,
         StackStatusFilter: Sequence[StackStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStacksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackspaginator)
         """
 
 
@@ -349,13 +342,13 @@
         self,
         *,
         Visibility: VisibilityType = ...,
         ProvisioningType: ProvisioningTypeType = ...,
         DeprecatedStatus: DeprecatedStatusType = ...,
         Type: RegistryTypeType = ...,
         Filters: TypeFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listtypespaginator)
         """
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/paginator.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -42,16 +42,15 @@
         list_stack_set_operation_results_paginator: ListStackSetOperationResultsPaginator = client.get_paginator("list_stack_set_operation_results")
         list_stack_set_operations_paginator: ListStackSetOperationsPaginator = client.get_paginator("list_stack_set_operations")
         list_stack_sets_paginator: ListStackSetsPaginator = client.get_paginator("list_stack_sets")
         list_stacks_paginator: ListStacksPaginator = client.get_paginator("list_stacks")
         list_types_paginator: ListTypesPaginator = client.get_paginator("list_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     CallAsType,
     DeprecatedStatusType,
@@ -78,19 +77,14 @@
     ListTypesOutputTypeDef,
     OperationResultFilterTypeDef,
     PaginatorConfigTypeDef,
     StackInstanceFilterTypeDef,
     TypeFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAccountLimitsPaginator",
     "DescribeChangeSetPaginator",
     "DescribeStackEventsPaginator",
     "DescribeStacksPaginator",
     "ListChangeSetsPaginator",
     "ListExportsPaginator",
@@ -115,15 +109,15 @@
 class DescribeAccountLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeAccountLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describeaccountlimitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccountLimitsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeAccountLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describeaccountlimitspaginator)
         """
 
 class DescribeChangeSetPaginator(AioPaginator):
@@ -133,85 +127,85 @@
     """
 
     def paginate(
         self,
         *,
         ChangeSetName: str,
         StackName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeChangeSetOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeChangeSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describechangesetpaginator)
         """
 
 class DescribeStackEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStackEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackeventspaginator)
     """
 
     def paginate(
-        self, *, StackName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStackEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStackEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackeventspaginator)
         """
 
 class DescribeStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackspaginator)
     """
 
     def paginate(
-        self, *, StackName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStacksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.DescribeStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#describestackspaginator)
         """
 
 class ListChangeSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListChangeSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listchangesetspaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChangeSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListChangeSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listchangesetspaginator)
         """
 
 class ListExportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListExports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listexportspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListExports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listexportspaginator)
         """
 
 class ListImportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListImports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listimportspaginator)
     """
 
     def paginate(
-        self, *, ExportName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ExportName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListImports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listimportspaginator)
         """
 
 class ListStackInstancesPaginator(AioPaginator):
@@ -224,29 +218,29 @@
         self,
         *,
         StackSetName: str,
         Filters: Sequence[StackInstanceFilterTypeDef] = ...,
         StackInstanceAccount: str = ...,
         StackInstanceRegion: str = ...,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackinstancespaginator)
         """
 
 class ListStackResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackresourcespaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackresourcespaginator)
         """
 
 class ListStackSetOperationResultsPaginator(AioPaginator):
@@ -258,15 +252,15 @@
     def paginate(
         self,
         *,
         StackSetName: str,
         OperationId: str,
         CallAs: CallAsType = ...,
         Filters: Sequence[OperationResultFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetOperationResultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSetOperationResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetoperationresultspaginator)
         """
 
 class ListStackSetOperationsPaginator(AioPaginator):
@@ -276,15 +270,15 @@
     """
 
     def paginate(
         self,
         *,
         StackSetName: str,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSetOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetoperationspaginator)
         """
 
 class ListStackSetsPaginator(AioPaginator):
@@ -294,15 +288,15 @@
     """
 
     def paginate(
         self,
         *,
         Status: StackSetStatusType = ...,
         CallAs: CallAsType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStackSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStackSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststacksetspaginator)
         """
 
 class ListStacksPaginator(AioPaginator):
@@ -311,15 +305,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackspaginator)
     """
 
     def paginate(
         self,
         *,
         StackStatusFilter: Sequence[StackStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStacksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#liststackspaginator)
         """
 
 class ListTypesPaginator(AioPaginator):
@@ -332,13 +326,13 @@
         self,
         *,
         Visibility: VisibilityType = ...,
         ProvisioningType: ProvisioningTypeType = ...,
         DeprecatedStatus: DeprecatedStatusType = ...,
         Type: RegistryTypeType = ...,
         Filters: TypeFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation.Paginator.ListTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/paginators/#listtypespaginator)
         """
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/service_resource.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/service_resource.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,15 +19,15 @@
         my_stack: cloudformation_resources.Stack = resource.Stack(...)
         my_stack_resource: cloudformation_resources.StackResource = resource.StackResource(...)
         my_stack_resource_summary: cloudformation_resources.StackResourceSummary = resource.StackResourceSummary(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import Awaitable, List, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, List, NoReturn, Sequence
 
 from .client import CloudFormationClient
 from .literals import (
     CapabilityType,
     HookFailureModeType,
     HookStatusType,
     OnFailureType,
@@ -51,18 +51,14 @@
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
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/service_resource.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/service_resource.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -19,15 +19,15 @@
         my_stack: cloudformation_resources.Stack = resource.Stack(...)
         my_stack_resource: cloudformation_resources.StackResource = resource.StackResource(...)
         my_stack_resource_summary: cloudformation_resources.StackResourceSummary = resource.StackResourceSummary(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import Awaitable, List, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, List, NoReturn, Sequence
 
 from .client import CloudFormationClient
 from .literals import (
     CapabilityType,
     HookFailureModeType,
     HookStatusType,
     OnFailureType,
@@ -51,18 +51,14 @@
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
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/type_defs.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -31,15 +31,17 @@
     EvaluationTypeType,
     ExecutionStatusType,
     HandlerErrorCodeType,
     HookFailureModeType,
     HookStatusType,
     IdentityProviderType,
     OnFailureType,
+    OnStackFailureType,
     OperationStatusType,
+    OrganizationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     PublisherStatusType,
     RegionConcurrencyTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ReplacementType,
@@ -77,168 +79,165 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountGateResultTypeDef",
     "AccountLimitTypeDef",
     "LoggingConfigTypeDef",
-    "ResponseMetadataTypeDef",
+    "ActivateTypeOutputTypeDef",
     "AutoDeploymentTypeDef",
     "TypeConfigurationIdentifierTypeDef",
     "TypeConfigurationDetailsTypeDef",
     "CancelUpdateStackInputRequestTypeDef",
     "CancelUpdateStackInputStackCancelUpdateTypeDef",
     "ChangeSetHookResourceTargetDetailsTypeDef",
     "ChangeSetSummaryTypeDef",
     "ContinueUpdateRollbackInputRequestTypeDef",
     "ParameterTypeDef",
     "ResourceToImportTypeDef",
     "TagTypeDef",
+    "CreateChangeSetOutputTypeDef",
     "DeploymentTargetsTypeDef",
     "StackSetOperationPreferencesTypeDef",
+    "CreateStackInstancesOutputTypeDef",
+    "CreateStackOutputTypeDef",
     "ManagedExecutionTypeDef",
+    "CreateStackSetOutputTypeDef",
     "DeactivateTypeInputRequestTypeDef",
     "DeleteChangeSetInputRequestTypeDef",
     "DeleteStackInputRequestTypeDef",
     "DeleteStackInputStackDeleteTypeDef",
+    "DeleteStackInstancesOutputTypeDef",
     "DeleteStackSetInputRequestTypeDef",
     "DeregisterTypeInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsInputRequestTypeDef",
     "DescribeChangeSetHooksInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
     "DescribeChangeSetInputRequestTypeDef",
+    "DescribeOrganizationsAccessInputRequestTypeDef",
+    "DescribeOrganizationsAccessOutputTypeDef",
     "DescribePublisherInputRequestTypeDef",
+    "DescribePublisherOutputTypeDef",
     "DescribeStackDriftDetectionStatusInputRequestTypeDef",
+    "DescribeStackDriftDetectionStatusOutputTypeDef",
+    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
     "DescribeStackEventsInputRequestTypeDef",
     "StackEventTypeDef",
     "DescribeStackInstanceInputRequestTypeDef",
     "DescribeStackResourceDriftsInputRequestTypeDef",
     "DescribeStackResourceInputRequestTypeDef",
     "DescribeStackResourcesInputRequestTypeDef",
     "DescribeStackSetInputRequestTypeDef",
     "DescribeStackSetOperationInputRequestTypeDef",
+    "DescribeStacksInputDescribeStacksPaginateTypeDef",
     "DescribeStacksInputRequestTypeDef",
     "DescribeTypeInputRequestTypeDef",
     "RequiredActivatedTypeTypeDef",
     "DescribeTypeRegistrationInputRequestTypeDef",
+    "DescribeTypeRegistrationOutputTypeDef",
     "DetectStackDriftInputRequestTypeDef",
+    "DetectStackDriftOutputTypeDef",
     "DetectStackResourceDriftInputRequestTypeDef",
+    "DetectStackSetDriftOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "EstimateTemplateCostOutputTypeDef",
     "ExecuteChangeSetInputRequestTypeDef",
     "ExportTypeDef",
     "GetStackPolicyInputRequestTypeDef",
+    "GetStackPolicyOutputTypeDef",
     "GetTemplateInputRequestTypeDef",
+    "GetTemplateOutputTypeDef",
     "GetTemplateSummaryInputRequestTypeDef",
     "ResourceIdentifierSummaryTypeDef",
+    "ImportStacksToStackSetOutputTypeDef",
+    "ListChangeSetsInputListChangeSetsPaginateTypeDef",
     "ListChangeSetsInputRequestTypeDef",
+    "ListExportsInputListExportsPaginateTypeDef",
     "ListExportsInputRequestTypeDef",
+    "ListImportsInputListImportsPaginateTypeDef",
     "ListImportsInputRequestTypeDef",
+    "ListImportsOutputTypeDef",
     "StackInstanceFilterTypeDef",
+    "ListStackResourcesInputListStackResourcesPaginateTypeDef",
     "ListStackResourcesInputRequestTypeDef",
     "OperationResultFilterTypeDef",
+    "ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
     "ListStackSetOperationsInputRequestTypeDef",
+    "ListStackSetsInputListStackSetsPaginateTypeDef",
     "ListStackSetsInputRequestTypeDef",
+    "ListStacksInputListStacksPaginateTypeDef",
     "ListStacksInputRequestTypeDef",
     "ListTypeRegistrationsInputRequestTypeDef",
+    "ListTypeRegistrationsOutputTypeDef",
     "ListTypeVersionsInputRequestTypeDef",
     "TypeVersionSummaryTypeDef",
     "TypeFiltersTypeDef",
     "TypeSummaryTypeDef",
+    "ModuleInfoResponseMetadataTypeDef",
     "ModuleInfoTypeDef",
     "OutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterConstraintsTypeDef",
     "PhysicalResourceIdContextKeyValuePairTypeDef",
     "PropertyDifferenceTypeDef",
     "PublishTypeInputRequestTypeDef",
+    "PublishTypeOutputTypeDef",
     "RecordHandlerProgressInputRequestTypeDef",
     "RegisterPublisherInputRequestTypeDef",
+    "RegisterPublisherOutputTypeDef",
+    "RegisterTypeOutputTypeDef",
     "ResourceTargetDefinitionTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTriggerTypeDef",
     "RollbackStackInputRequestTypeDef",
-    "ServiceResourceEventRequestTypeDef",
-    "ServiceResourceStackRequestTypeDef",
-    "ServiceResourceStackResourceRequestTypeDef",
-    "ServiceResourceStackResourceSummaryRequestTypeDef",
+    "RollbackStackOutputTypeDef",
     "SetStackPolicyInputRequestTypeDef",
     "SetTypeConfigurationInputRequestTypeDef",
+    "SetTypeConfigurationOutputTypeDef",
     "SetTypeDefaultVersionInputRequestTypeDef",
     "SignalResourceInputRequestTypeDef",
+    "StackDriftInformationResponseMetadataTypeDef",
     "StackDriftInformationSummaryTypeDef",
     "StackDriftInformationTypeDef",
     "StackInstanceComprehensiveStatusTypeDef",
     "StackResourceDriftInformationTypeDef",
+    "StackResourceDriftInformationResponseMetadataTypeDef",
+    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
     "StackResourceDriftInformationSummaryTypeDef",
-    "StackResourceRequestTypeDef",
     "StackSetDriftDetectionDetailsTypeDef",
     "StackSetOperationStatusDetailsTypeDef",
     "StopStackSetOperationInputRequestTypeDef",
     "TemplateParameterTypeDef",
     "TestTypeInputRequestTypeDef",
-    "UpdateTerminationProtectionInputRequestTypeDef",
-    "ValidateTemplateInputRequestTypeDef",
-    "StackSetOperationResultSummaryTypeDef",
-    "ActivateTypeInputRequestTypeDef",
-    "RegisterTypeInputRequestTypeDef",
-    "ActivateTypeOutputTypeDef",
-    "CreateChangeSetOutputTypeDef",
-    "CreateStackInstancesOutputTypeDef",
-    "CreateStackOutputTypeDef",
-    "CreateStackSetOutputTypeDef",
-    "DeleteStackInstancesOutputTypeDef",
-    "DescribeAccountLimitsOutputTypeDef",
-    "DescribePublisherOutputTypeDef",
-    "DescribeStackDriftDetectionStatusOutputTypeDef",
-    "DescribeTypeRegistrationOutputTypeDef",
-    "DetectStackDriftOutputTypeDef",
-    "DetectStackSetDriftOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EstimateTemplateCostOutputTypeDef",
-    "GetStackPolicyOutputTypeDef",
-    "GetTemplateOutputTypeDef",
-    "ImportStacksToStackSetOutputTypeDef",
-    "ListImportsOutputTypeDef",
-    "ListTypeRegistrationsOutputTypeDef",
-    "ModuleInfoResponseMetadataTypeDef",
-    "PublishTypeOutputTypeDef",
-    "RegisterPublisherOutputTypeDef",
-    "RegisterTypeOutputTypeDef",
-    "RollbackStackOutputTypeDef",
-    "SetTypeConfigurationOutputTypeDef",
-    "StackDriftInformationResponseMetadataTypeDef",
-    "StackResourceDriftInformationResponseMetadataTypeDef",
-    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
     "TestTypeOutputTypeDef",
     "UpdateStackInstancesOutputTypeDef",
     "UpdateStackOutputTypeDef",
     "UpdateStackSetOutputTypeDef",
+    "UpdateTerminationProtectionInputRequestTypeDef",
     "UpdateTerminationProtectionOutputTypeDef",
+    "ValidateTemplateInputRequestTypeDef",
+    "StackSetOperationResultSummaryTypeDef",
+    "DescribeAccountLimitsOutputTypeDef",
+    "ActivateTypeInputRequestTypeDef",
+    "RegisterTypeInputRequestTypeDef",
     "BatchDescribeTypeConfigurationsErrorTypeDef",
     "BatchDescribeTypeConfigurationsInputRequestTypeDef",
     "ChangeSetHookTargetDetailsTypeDef",
     "ListChangeSetsOutputTypeDef",
     "EstimateTemplateCostInputRequestTypeDef",
     "CreateStackInstancesInputRequestTypeDef",
     "DeleteStackInstancesInputRequestTypeDef",
     "DetectStackSetDriftInputRequestTypeDef",
     "ImportStacksToStackSetInputRequestTypeDef",
     "UpdateStackInstancesInputRequestTypeDef",
     "CreateStackSetInputRequestTypeDef",
     "StackSetSummaryTypeDef",
     "UpdateStackSetInputRequestTypeDef",
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    "DescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
-    "DescribeStacksInputDescribeStacksPaginateTypeDef",
-    "ListChangeSetsInputListChangeSetsPaginateTypeDef",
-    "ListExportsInputListExportsPaginateTypeDef",
-    "ListImportsInputListImportsPaginateTypeDef",
-    "ListStackResourcesInputListStackResourcesPaginateTypeDef",
-    "ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    "ListStackSetsInputListStackSetsPaginateTypeDef",
-    "ListStacksInputListStacksPaginateTypeDef",
     "DescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef",
     "DescribeStacksInputStackCreateCompleteWaitTypeDef",
     "DescribeStacksInputStackDeleteCompleteWaitTypeDef",
     "DescribeStacksInputStackExistsWaitTypeDef",
     "DescribeStacksInputStackImportCompleteWaitTypeDef",
     "DescribeStacksInputStackRollbackCompleteWaitTypeDef",
     "DescribeStacksInputStackUpdateCompleteWaitTypeDef",
@@ -320,22 +319,19 @@
     "LoggingConfigTypeDef",
     {
         "LogRoleArn": str,
         "LogGroupName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ActivateTypeOutputTypeDef = TypedDict(
+    "ActivateTypeOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoDeploymentTypeDef = TypedDict(
     "AutoDeploymentTypeDef",
     {
         "Enabled": bool,
@@ -476,14 +472,23 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateChangeSetOutputTypeDef = TypedDict(
+    "CreateChangeSetOutputTypeDef",
+    {
+        "Id": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentTargetsTypeDef = TypedDict(
     "DeploymentTargetsTypeDef",
     {
         "Accounts": Sequence[str],
         "AccountsUrl": str,
         "OrganizationalUnitIds": Sequence[str],
         "AccountFilterType": AccountFilterTypeType,
@@ -500,22 +505,46 @@
         "FailureTolerancePercentage": int,
         "MaxConcurrentCount": int,
         "MaxConcurrentPercentage": int,
     },
     total=False,
 )
 
+CreateStackInstancesOutputTypeDef = TypedDict(
+    "CreateStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStackOutputTypeDef = TypedDict(
+    "CreateStackOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ManagedExecutionTypeDef = TypedDict(
     "ManagedExecutionTypeDef",
     {
         "Active": bool,
     },
     total=False,
 )
 
+CreateStackSetOutputTypeDef = TypedDict(
+    "CreateStackSetOutputTypeDef",
+    {
+        "StackSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeactivateTypeInputRequestTypeDef = TypedDict(
     "DeactivateTypeInputRequestTypeDef",
     {
         "TypeName": str,
         "Type": ThirdPartyTypeType,
         "Arn": str,
     },
@@ -572,14 +601,22 @@
         "RetainResources": Sequence[str],
         "RoleARN": str,
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+DeleteStackInstancesOutputTypeDef = TypedDict(
+    "DeleteStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteStackSetInputRequestTypeDef = TypedDict(
     "_RequiredDeleteStackSetInputRequestTypeDef",
     {
         "StackSetName": str,
     },
 )
 _OptionalDeleteStackSetInputRequestTypeDef = TypedDict(
@@ -604,20 +641,18 @@
         "Type": RegistryTypeType,
         "TypeName": str,
         "VersionId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAccountLimitsInputRequestTypeDef = TypedDict(
     "DescribeAccountLimitsInputRequestTypeDef",
     {
@@ -655,14 +690,37 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
+    {
+        "ChangeSetName": str,
+    },
+)
+_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeChangeSetInputDescribeChangeSetPaginateTypeDef(
+    _RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
+    _OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeChangeSetInputRequestTypeDef = TypedDict(
     "_RequiredDescribeChangeSetInputRequestTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalDescribeChangeSetInputRequestTypeDef = TypedDict(
@@ -677,29 +735,79 @@
 
 class DescribeChangeSetInputRequestTypeDef(
     _RequiredDescribeChangeSetInputRequestTypeDef, _OptionalDescribeChangeSetInputRequestTypeDef
 ):
     pass
 
 
+DescribeOrganizationsAccessInputRequestTypeDef = TypedDict(
+    "DescribeOrganizationsAccessInputRequestTypeDef",
+    {
+        "CallAs": CallAsType,
+    },
+    total=False,
+)
+
+DescribeOrganizationsAccessOutputTypeDef = TypedDict(
+    "DescribeOrganizationsAccessOutputTypeDef",
+    {
+        "Status": OrganizationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePublisherInputRequestTypeDef = TypedDict(
     "DescribePublisherInputRequestTypeDef",
     {
         "PublisherId": str,
     },
     total=False,
 )
 
+DescribePublisherOutputTypeDef = TypedDict(
+    "DescribePublisherOutputTypeDef",
+    {
+        "PublisherId": str,
+        "PublisherStatus": PublisherStatusType,
+        "IdentityProvider": IdentityProviderType,
+        "PublisherProfile": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeStackDriftDetectionStatusInputRequestTypeDef = TypedDict(
     "DescribeStackDriftDetectionStatusInputRequestTypeDef",
     {
         "StackDriftDetectionId": str,
     },
 )
 
+DescribeStackDriftDetectionStatusOutputTypeDef = TypedDict(
+    "DescribeStackDriftDetectionStatusOutputTypeDef",
+    {
+        "StackId": str,
+        "StackDriftDetectionId": str,
+        "StackDriftStatus": StackDriftStatusType,
+        "DetectionStatus": StackDriftDetectionStatusType,
+        "DetectionStatusReason": str,
+        "DriftedStackResourceCount": int,
+        "Timestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeStackEventsInputDescribeStackEventsPaginateTypeDef = TypedDict(
+    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStackEventsInputRequestTypeDef = TypedDict(
     "DescribeStackEventsInputRequestTypeDef",
     {
         "StackName": str,
         "NextToken": str,
     },
     total=False,
@@ -844,14 +952,23 @@
 class DescribeStackSetOperationInputRequestTypeDef(
     _RequiredDescribeStackSetOperationInputRequestTypeDef,
     _OptionalDescribeStackSetOperationInputRequestTypeDef,
 ):
     pass
 
 
+DescribeStacksInputDescribeStacksPaginateTypeDef = TypedDict(
+    "DescribeStacksInputDescribeStacksPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStacksInputRequestTypeDef = TypedDict(
     "DescribeStacksInputRequestTypeDef",
     {
         "StackName": str,
         "NextToken": str,
     },
     total=False,
@@ -884,14 +1001,25 @@
 DescribeTypeRegistrationInputRequestTypeDef = TypedDict(
     "DescribeTypeRegistrationInputRequestTypeDef",
     {
         "RegistrationToken": str,
     },
 )
 
+DescribeTypeRegistrationOutputTypeDef = TypedDict(
+    "DescribeTypeRegistrationOutputTypeDef",
+    {
+        "ProgressStatus": RegistrationStatusType,
+        "Description": str,
+        "TypeArn": str,
+        "TypeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDetectStackDriftInputRequestTypeDef = TypedDict(
     "_RequiredDetectStackDriftInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalDetectStackDriftInputRequestTypeDef = TypedDict(
@@ -905,22 +1033,53 @@
 
 class DetectStackDriftInputRequestTypeDef(
     _RequiredDetectStackDriftInputRequestTypeDef, _OptionalDetectStackDriftInputRequestTypeDef
 ):
     pass
 
 
+DetectStackDriftOutputTypeDef = TypedDict(
+    "DetectStackDriftOutputTypeDef",
+    {
+        "StackDriftDetectionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetectStackResourceDriftInputRequestTypeDef = TypedDict(
     "DetectStackResourceDriftInputRequestTypeDef",
     {
         "StackName": str,
         "LogicalResourceId": str,
     },
 )
 
+DetectStackSetDriftOutputTypeDef = TypedDict(
+    "DetectStackSetDriftOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EstimateTemplateCostOutputTypeDef = TypedDict(
+    "EstimateTemplateCostOutputTypeDef",
+    {
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExecuteChangeSetInputRequestTypeDef = TypedDict(
     "_RequiredExecuteChangeSetInputRequestTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalExecuteChangeSetInputRequestTypeDef = TypedDict(
@@ -953,24 +1112,41 @@
 GetStackPolicyInputRequestTypeDef = TypedDict(
     "GetStackPolicyInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 
+GetStackPolicyOutputTypeDef = TypedDict(
+    "GetStackPolicyOutputTypeDef",
+    {
+        "StackPolicyBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTemplateInputRequestTypeDef = TypedDict(
     "GetTemplateInputRequestTypeDef",
     {
         "StackName": str,
         "ChangeSetName": str,
         "TemplateStage": TemplateStageType,
     },
     total=False,
 )
 
+GetTemplateOutputTypeDef = TypedDict(
+    "GetTemplateOutputTypeDef",
+    {
+        "TemplateBody": Dict[str, Any],
+        "StagesAvailable": List[TemplateStageType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTemplateSummaryInputRequestTypeDef = TypedDict(
     "GetTemplateSummaryInputRequestTypeDef",
     {
         "TemplateBody": str,
         "TemplateURL": str,
         "StackName": str,
         "StackSetName": str,
@@ -985,14 +1161,44 @@
         "ResourceType": str,
         "LogicalResourceIds": List[str],
         "ResourceIdentifiers": List[str],
     },
     total=False,
 )
 
+ImportStacksToStackSetOutputTypeDef = TypedDict(
+    "ImportStacksToStackSetOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListChangeSetsInputListChangeSetsPaginateTypeDef(
+    _RequiredListChangeSetsInputListChangeSetsPaginateTypeDef,
+    _OptionalListChangeSetsInputListChangeSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListChangeSetsInputRequestTypeDef = TypedDict(
     "_RequiredListChangeSetsInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListChangeSetsInputRequestTypeDef = TypedDict(
@@ -1006,22 +1212,52 @@
 
 class ListChangeSetsInputRequestTypeDef(
     _RequiredListChangeSetsInputRequestTypeDef, _OptionalListChangeSetsInputRequestTypeDef
 ):
     pass
 
 
+ListExportsInputListExportsPaginateTypeDef = TypedDict(
+    "ListExportsInputListExportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListExportsInputRequestTypeDef = TypedDict(
     "ListExportsInputRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListImportsInputListImportsPaginateTypeDef = TypedDict(
+    "_RequiredListImportsInputListImportsPaginateTypeDef",
+    {
+        "ExportName": str,
+    },
+)
+_OptionalListImportsInputListImportsPaginateTypeDef = TypedDict(
+    "_OptionalListImportsInputListImportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListImportsInputListImportsPaginateTypeDef(
+    _RequiredListImportsInputListImportsPaginateTypeDef,
+    _OptionalListImportsInputListImportsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListImportsInputRequestTypeDef = TypedDict(
     "_RequiredListImportsInputRequestTypeDef",
     {
         "ExportName": str,
     },
 )
 _OptionalListImportsInputRequestTypeDef = TypedDict(
@@ -1035,23 +1271,54 @@
 
 class ListImportsInputRequestTypeDef(
     _RequiredListImportsInputRequestTypeDef, _OptionalListImportsInputRequestTypeDef
 ):
     pass
 
 
+ListImportsOutputTypeDef = TypedDict(
+    "ListImportsOutputTypeDef",
+    {
+        "Imports": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StackInstanceFilterTypeDef = TypedDict(
     "StackInstanceFilterTypeDef",
     {
         "Name": StackInstanceFilterNameType,
         "Values": str,
     },
     total=False,
 )
 
+_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStackResourcesInputListStackResourcesPaginateTypeDef(
+    _RequiredListStackResourcesInputListStackResourcesPaginateTypeDef,
+    _OptionalListStackResourcesInputListStackResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStackResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListStackResourcesInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListStackResourcesInputRequestTypeDef = TypedDict(
@@ -1074,14 +1341,37 @@
     {
         "Name": Literal["OPERATION_RESULT_STATUS"],
         "Values": str,
     },
     total=False,
 )
 
+_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
+    "_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
+    {
+        "StackSetName": str,
+    },
+)
+_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
+    "_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
+    {
+        "CallAs": CallAsType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef(
+    _RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
+    _OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStackSetOperationsInputRequestTypeDef = TypedDict(
     "_RequiredListStackSetOperationsInputRequestTypeDef",
     {
         "StackSetName": str,
     },
 )
 _OptionalListStackSetOperationsInputRequestTypeDef = TypedDict(
@@ -1098,25 +1388,44 @@
 class ListStackSetOperationsInputRequestTypeDef(
     _RequiredListStackSetOperationsInputRequestTypeDef,
     _OptionalListStackSetOperationsInputRequestTypeDef,
 ):
     pass
 
 
+ListStackSetsInputListStackSetsPaginateTypeDef = TypedDict(
+    "ListStackSetsInputListStackSetsPaginateTypeDef",
+    {
+        "Status": StackSetStatusType,
+        "CallAs": CallAsType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStackSetsInputRequestTypeDef = TypedDict(
     "ListStackSetsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Status": StackSetStatusType,
         "CallAs": CallAsType,
     },
     total=False,
 )
 
+ListStacksInputListStacksPaginateTypeDef = TypedDict(
+    "ListStacksInputListStacksPaginateTypeDef",
+    {
+        "StackStatusFilter": Sequence[StackStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStacksInputRequestTypeDef = TypedDict(
     "ListStacksInputRequestTypeDef",
     {
         "NextToken": str,
         "StackStatusFilter": Sequence[StackStatusType],
     },
     total=False,
@@ -1131,14 +1440,23 @@
         "RegistrationStatusFilter": RegistrationStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListTypeRegistrationsOutputTypeDef = TypedDict(
+    "ListTypeRegistrationsOutputTypeDef",
+    {
+        "RegistrationTokenList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTypeVersionsInputRequestTypeDef = TypedDict(
     "ListTypeVersionsInputRequestTypeDef",
     {
         "Type": RegistryTypeType,
         "TypeName": str,
         "Arn": str,
         "MaxResults": int,
@@ -1190,14 +1508,23 @@
         "PublisherIdentity": IdentityProviderType,
         "PublisherName": str,
         "IsActivated": bool,
     },
     total=False,
 )
 
+ModuleInfoResponseMetadataTypeDef = TypedDict(
+    "ModuleInfoResponseMetadataTypeDef",
+    {
+        "TypeHierarchy": str,
+        "LogicalIdHierarchy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModuleInfoTypeDef = TypedDict(
     "ModuleInfoTypeDef",
     {
         "TypeHierarchy": str,
         "LogicalIdHierarchy": str,
     },
     total=False,
@@ -1210,14 +1537,24 @@
         "OutputValue": str,
         "Description": str,
         "ExportName": str,
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
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "AllowedValues": List[str],
     },
     total=False,
 )
@@ -1247,14 +1584,22 @@
         "Arn": str,
         "TypeName": str,
         "PublicVersionNumber": str,
     },
     total=False,
 )
 
+PublishTypeOutputTypeDef = TypedDict(
+    "PublishTypeOutputTypeDef",
+    {
+        "PublicTypeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecordHandlerProgressInputRequestTypeDef = TypedDict(
     "_RequiredRecordHandlerProgressInputRequestTypeDef",
     {
         "BearerToken": str,
         "OperationStatus": OperationStatusType,
     },
 )
@@ -1283,24 +1628,51 @@
     {
         "AcceptTermsAndConditions": bool,
         "ConnectionArn": str,
     },
     total=False,
 )
 
+RegisterPublisherOutputTypeDef = TypedDict(
+    "RegisterPublisherOutputTypeDef",
+    {
+        "PublisherId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTypeOutputTypeDef = TypedDict(
+    "RegisterTypeOutputTypeDef",
+    {
+        "RegistrationToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceTargetDefinitionTypeDef = TypedDict(
     "ResourceTargetDefinitionTypeDef",
     {
         "Attribute": ResourceAttributeType,
         "Name": str,
         "RequiresRecreation": RequiresRecreationType,
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
 RollbackTriggerTypeDef = TypedDict(
     "RollbackTriggerTypeDef",
     {
         "Arn": str,
         "Type": str,
     },
 )
@@ -1323,41 +1695,19 @@
 
 class RollbackStackInputRequestTypeDef(
     _RequiredRollbackStackInputRequestTypeDef, _OptionalRollbackStackInputRequestTypeDef
 ):
     pass
 
 
-ServiceResourceEventRequestTypeDef = TypedDict(
-    "ServiceResourceEventRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceStackRequestTypeDef = TypedDict(
-    "ServiceResourceStackRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceStackResourceRequestTypeDef = TypedDict(
-    "ServiceResourceStackResourceRequestTypeDef",
-    {
-        "stack_name": str,
-        "logical_id": str,
-    },
-)
-
-ServiceResourceStackResourceSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceStackResourceSummaryRequestTypeDef",
+RollbackStackOutputTypeDef = TypedDict(
+    "RollbackStackOutputTypeDef",
     {
-        "stack_name": str,
-        "logical_id": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetStackPolicyInputRequestTypeDef = TypedDict(
     "_RequiredSetStackPolicyInputRequestTypeDef",
     {
         "StackName": str,
@@ -1400,14 +1750,22 @@
 class SetTypeConfigurationInputRequestTypeDef(
     _RequiredSetTypeConfigurationInputRequestTypeDef,
     _OptionalSetTypeConfigurationInputRequestTypeDef,
 ):
     pass
 
 
+SetTypeConfigurationOutputTypeDef = TypedDict(
+    "SetTypeConfigurationOutputTypeDef",
+    {
+        "ConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetTypeDefaultVersionInputRequestTypeDef = TypedDict(
     "SetTypeDefaultVersionInputRequestTypeDef",
     {
         "Arn": str,
         "Type": RegistryTypeType,
         "TypeName": str,
         "VersionId": str,
@@ -1421,14 +1779,23 @@
         "StackName": str,
         "LogicalResourceId": str,
         "UniqueId": str,
         "Status": ResourceSignalStatusType,
     },
 )
 
+StackDriftInformationResponseMetadataTypeDef = TypedDict(
+    "StackDriftInformationResponseMetadataTypeDef",
+    {
+        "StackDriftStatus": StackDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStackDriftInformationSummaryTypeDef = TypedDict(
     "_RequiredStackDriftInformationSummaryTypeDef",
     {
         "StackDriftStatus": StackDriftStatusType,
     },
 )
 _OptionalStackDriftInformationSummaryTypeDef = TypedDict(
@@ -1492,14 +1859,32 @@
 
 class StackResourceDriftInformationTypeDef(
     _RequiredStackResourceDriftInformationTypeDef, _OptionalStackResourceDriftInformationTypeDef
 ):
     pass
 
 
+StackResourceDriftInformationResponseMetadataTypeDef = TypedDict(
+    "StackResourceDriftInformationResponseMetadataTypeDef",
+    {
+        "StackResourceDriftStatus": StackResourceDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StackResourceDriftInformationSummaryResponseMetadataTypeDef = TypedDict(
+    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
+    {
+        "StackResourceDriftStatus": StackResourceDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStackResourceDriftInformationSummaryTypeDef = TypedDict(
     "_RequiredStackResourceDriftInformationSummaryTypeDef",
     {
         "StackResourceDriftStatus": StackResourceDriftStatusType,
     },
 )
 _OptionalStackResourceDriftInformationSummaryTypeDef = TypedDict(
@@ -1514,21 +1899,14 @@
 class StackResourceDriftInformationSummaryTypeDef(
     _RequiredStackResourceDriftInformationSummaryTypeDef,
     _OptionalStackResourceDriftInformationSummaryTypeDef,
 ):
     pass
 
 
-StackResourceRequestTypeDef = TypedDict(
-    "StackResourceRequestTypeDef",
-    {
-        "logical_id": str,
-    },
-)
-
 StackSetDriftDetectionDetailsTypeDef = TypedDict(
     "StackSetDriftDetectionDetailsTypeDef",
     {
         "DriftStatus": StackSetDriftStatusType,
         "DriftDetectionStatus": StackSetDriftDetectionStatusType,
         "LastDriftCheckTimestamp": datetime,
         "TotalStackInstancesCount": int,
@@ -1590,22 +1968,62 @@
         "TypeName": str,
         "VersionId": str,
         "LogDeliveryBucket": str,
     },
     total=False,
 )
 
+TestTypeOutputTypeDef = TypedDict(
+    "TestTypeOutputTypeDef",
+    {
+        "TypeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackInstancesOutputTypeDef = TypedDict(
+    "UpdateStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackOutputTypeDef = TypedDict(
+    "UpdateStackOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackSetOutputTypeDef = TypedDict(
+    "UpdateStackSetOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateTerminationProtectionInputRequestTypeDef = TypedDict(
     "UpdateTerminationProtectionInputRequestTypeDef",
     {
         "EnableTerminationProtection": bool,
         "StackName": str,
     },
 )
 
+UpdateTerminationProtectionOutputTypeDef = TypedDict(
+    "UpdateTerminationProtectionOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ValidateTemplateInputRequestTypeDef = TypedDict(
     "ValidateTemplateInputRequestTypeDef",
     {
         "TemplateBody": str,
         "TemplateURL": str,
     },
     total=False,
@@ -1620,14 +2038,23 @@
         "StatusReason": str,
         "AccountGateResult": AccountGateResultTypeDef,
         "OrganizationalUnitId": str,
     },
     total=False,
 )
 
+DescribeAccountLimitsOutputTypeDef = TypedDict(
+    "DescribeAccountLimitsOutputTypeDef",
+    {
+        "AccountLimits": List[AccountLimitTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivateTypeInputRequestTypeDef = TypedDict(
     "ActivateTypeInputRequestTypeDef",
     {
         "Type": ThirdPartyTypeType,
         "PublicTypeArn": str,
         "PublisherId": str,
         "TypeName": str,
@@ -1662,298 +2089,14 @@
 
 class RegisterTypeInputRequestTypeDef(
     _RequiredRegisterTypeInputRequestTypeDef, _OptionalRegisterTypeInputRequestTypeDef
 ):
     pass
 
 
-ActivateTypeOutputTypeDef = TypedDict(
-    "ActivateTypeOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChangeSetOutputTypeDef = TypedDict(
-    "CreateChangeSetOutputTypeDef",
-    {
-        "Id": str,
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackInstancesOutputTypeDef = TypedDict(
-    "CreateStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackOutputTypeDef = TypedDict(
-    "CreateStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackSetOutputTypeDef = TypedDict(
-    "CreateStackSetOutputTypeDef",
-    {
-        "StackSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteStackInstancesOutputTypeDef = TypedDict(
-    "DeleteStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountLimitsOutputTypeDef = TypedDict(
-    "DescribeAccountLimitsOutputTypeDef",
-    {
-        "AccountLimits": List[AccountLimitTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePublisherOutputTypeDef = TypedDict(
-    "DescribePublisherOutputTypeDef",
-    {
-        "PublisherId": str,
-        "PublisherStatus": PublisherStatusType,
-        "IdentityProvider": IdentityProviderType,
-        "PublisherProfile": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeStackDriftDetectionStatusOutputTypeDef = TypedDict(
-    "DescribeStackDriftDetectionStatusOutputTypeDef",
-    {
-        "StackId": str,
-        "StackDriftDetectionId": str,
-        "StackDriftStatus": StackDriftStatusType,
-        "DetectionStatus": StackDriftDetectionStatusType,
-        "DetectionStatusReason": str,
-        "DriftedStackResourceCount": int,
-        "Timestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTypeRegistrationOutputTypeDef = TypedDict(
-    "DescribeTypeRegistrationOutputTypeDef",
-    {
-        "ProgressStatus": RegistrationStatusType,
-        "Description": str,
-        "TypeArn": str,
-        "TypeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectStackDriftOutputTypeDef = TypedDict(
-    "DetectStackDriftOutputTypeDef",
-    {
-        "StackDriftDetectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectStackSetDriftOutputTypeDef = TypedDict(
-    "DetectStackSetDriftOutputTypeDef",
-    {
-        "OperationId": str,
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
-EstimateTemplateCostOutputTypeDef = TypedDict(
-    "EstimateTemplateCostOutputTypeDef",
-    {
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetStackPolicyOutputTypeDef = TypedDict(
-    "GetStackPolicyOutputTypeDef",
-    {
-        "StackPolicyBody": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemplateOutputTypeDef = TypedDict(
-    "GetTemplateOutputTypeDef",
-    {
-        "TemplateBody": Dict[str, Any],
-        "StagesAvailable": List[TemplateStageType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportStacksToStackSetOutputTypeDef = TypedDict(
-    "ImportStacksToStackSetOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListImportsOutputTypeDef = TypedDict(
-    "ListImportsOutputTypeDef",
-    {
-        "Imports": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTypeRegistrationsOutputTypeDef = TypedDict(
-    "ListTypeRegistrationsOutputTypeDef",
-    {
-        "RegistrationTokenList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModuleInfoResponseMetadataTypeDef = TypedDict(
-    "ModuleInfoResponseMetadataTypeDef",
-    {
-        "TypeHierarchy": str,
-        "LogicalIdHierarchy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishTypeOutputTypeDef = TypedDict(
-    "PublishTypeOutputTypeDef",
-    {
-        "PublicTypeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterPublisherOutputTypeDef = TypedDict(
-    "RegisterPublisherOutputTypeDef",
-    {
-        "PublisherId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTypeOutputTypeDef = TypedDict(
-    "RegisterTypeOutputTypeDef",
-    {
-        "RegistrationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackStackOutputTypeDef = TypedDict(
-    "RollbackStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetTypeConfigurationOutputTypeDef = TypedDict(
-    "SetTypeConfigurationOutputTypeDef",
-    {
-        "ConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackDriftInformationResponseMetadataTypeDef = TypedDict(
-    "StackDriftInformationResponseMetadataTypeDef",
-    {
-        "StackDriftStatus": StackDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackResourceDriftInformationResponseMetadataTypeDef = TypedDict(
-    "StackResourceDriftInformationResponseMetadataTypeDef",
-    {
-        "StackResourceDriftStatus": StackResourceDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackResourceDriftInformationSummaryResponseMetadataTypeDef = TypedDict(
-    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
-    {
-        "StackResourceDriftStatus": StackResourceDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestTypeOutputTypeDef = TypedDict(
-    "TestTypeOutputTypeDef",
-    {
-        "TypeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackInstancesOutputTypeDef = TypedDict(
-    "UpdateStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackOutputTypeDef = TypedDict(
-    "UpdateStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackSetOutputTypeDef = TypedDict(
-    "UpdateStackSetOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTerminationProtectionOutputTypeDef = TypedDict(
-    "UpdateTerminationProtectionOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchDescribeTypeConfigurationsErrorTypeDef = TypedDict(
     "BatchDescribeTypeConfigurationsErrorTypeDef",
     {
         "ErrorCode": str,
         "ErrorMessage": str,
         "TypeConfigurationIdentifier": TypeConfigurationIdentifierTypeDef,
     },
@@ -1977,15 +2120,15 @@
 )
 
 ListChangeSetsOutputTypeDef = TypedDict(
     "ListChangeSetsOutputTypeDef",
     {
         "Summaries": List[ChangeSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EstimateTemplateCostInputRequestTypeDef = TypedDict(
     "EstimateTemplateCostInputRequestTypeDef",
     {
         "TemplateBody": str,
@@ -2213,179 +2356,14 @@
 
 class UpdateStackSetInputRequestTypeDef(
     _RequiredUpdateStackSetInputRequestTypeDef, _OptionalUpdateStackSetInputRequestTypeDef
 ):
     pass
 
 
-DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    {
-        "ChangeSetName": str,
-    },
-)
-_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeChangeSetInputDescribeChangeSetPaginateTypeDef(
-    _RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-    _OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-):
-    pass
-
-
-DescribeStackEventsInputDescribeStackEventsPaginateTypeDef = TypedDict(
-    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeStacksInputDescribeStacksPaginateTypeDef = TypedDict(
-    "DescribeStacksInputDescribeStacksPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
-    "_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
-    "_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListChangeSetsInputListChangeSetsPaginateTypeDef(
-    _RequiredListChangeSetsInputListChangeSetsPaginateTypeDef,
-    _OptionalListChangeSetsInputListChangeSetsPaginateTypeDef,
-):
-    pass
-
-
-ListExportsInputListExportsPaginateTypeDef = TypedDict(
-    "ListExportsInputListExportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListImportsInputListImportsPaginateTypeDef = TypedDict(
-    "_RequiredListImportsInputListImportsPaginateTypeDef",
-    {
-        "ExportName": str,
-    },
-)
-_OptionalListImportsInputListImportsPaginateTypeDef = TypedDict(
-    "_OptionalListImportsInputListImportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListImportsInputListImportsPaginateTypeDef(
-    _RequiredListImportsInputListImportsPaginateTypeDef,
-    _OptionalListImportsInputListImportsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStackResourcesInputListStackResourcesPaginateTypeDef(
-    _RequiredListStackResourcesInputListStackResourcesPaginateTypeDef,
-    _OptionalListStackResourcesInputListStackResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
-    "_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    {
-        "StackSetName": str,
-    },
-)
-_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
-    "_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    {
-        "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef(
-    _RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-    _OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-):
-    pass
-
-
-ListStackSetsInputListStackSetsPaginateTypeDef = TypedDict(
-    "ListStackSetsInputListStackSetsPaginateTypeDef",
-    {
-        "Status": StackSetStatusType,
-        "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListStacksInputListStacksPaginateTypeDef = TypedDict(
-    "ListStacksInputListStacksPaginateTypeDef",
-    {
-        "StackStatusFilter": Sequence[StackStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef = TypedDict(
     "_RequiredDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef = TypedDict(
@@ -2489,15 +2467,15 @@
 
 
 DescribeStackEventsOutputTypeDef = TypedDict(
     "DescribeStackEventsOutputTypeDef",
     {
         "StackEvents": List[StackEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTypeOutputTypeDef = TypedDict(
     "DescribeTypeOutputTypeDef",
     {
         "Arn": str,
@@ -2523,24 +2501,24 @@
         "PublisherId": str,
         "OriginalTypeName": str,
         "OriginalTypeArn": str,
         "PublicVersionNumber": str,
         "LatestPublicVersion": str,
         "IsActivated": bool,
         "AutoUpdate": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExportsOutputTypeDef = TypedDict(
     "ListExportsOutputTypeDef",
     {
         "Exports": List[ExportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListStackInstancesInputListStackInstancesPaginateTypeDef = TypedDict(
     "_RequiredListStackInstancesInputListStackInstancesPaginateTypeDef",
     {
         "StackSetName": str,
@@ -2549,15 +2527,15 @@
 _OptionalListStackInstancesInputListStackInstancesPaginateTypeDef = TypedDict(
     "_OptionalListStackInstancesInputListStackInstancesPaginateTypeDef",
     {
         "Filters": Sequence[StackInstanceFilterTypeDef],
         "StackInstanceAccount": str,
         "StackInstanceRegion": str,
         "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListStackInstancesInputListStackInstancesPaginateTypeDef(
     _RequiredListStackInstancesInputListStackInstancesPaginateTypeDef,
@@ -2600,15 +2578,15 @@
     },
 )
 _OptionalListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef = TypedDict(
     "_OptionalListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef",
     {
         "CallAs": CallAsType,
         "Filters": Sequence[OperationResultFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef(
     _RequiredListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef,
@@ -2644,27 +2622,27 @@
 
 
 ListTypeVersionsOutputTypeDef = TypedDict(
     "ListTypeVersionsOutputTypeDef",
     {
         "TypeVersionSummaries": List[TypeVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTypesInputListTypesPaginateTypeDef = TypedDict(
     "ListTypesInputListTypesPaginateTypeDef",
     {
         "Visibility": VisibilityType,
         "ProvisioningType": ProvisioningTypeType,
         "DeprecatedStatus": DeprecatedStatusType,
         "Type": RegistryTypeType,
         "Filters": TypeFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTypesInputRequestTypeDef = TypedDict(
     "ListTypesInputRequestTypeDef",
     {
@@ -2680,15 +2658,15 @@
 )
 
 ListTypesOutputTypeDef = TypedDict(
     "ListTypesOutputTypeDef",
     {
         "TypeSummaries": List[TypeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParameterDeclarationTypeDef = TypedDict(
     "ParameterDeclarationTypeDef",
     {
         "ParameterKey": str,
@@ -2743,15 +2721,15 @@
 )
 
 RollbackConfigurationResponseMetadataTypeDef = TypedDict(
     "RollbackConfigurationResponseMetadataTypeDef",
     {
         "RollbackTriggers": List[RollbackTriggerTypeDef],
         "MonitoringTimeInMinutes": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackConfigurationTypeDef = TypedDict(
     "RollbackConfigurationTypeDef",
     {
         "RollbackTriggers": Sequence[RollbackTriggerTypeDef],
@@ -2975,34 +2953,34 @@
     "ValidateTemplateOutputTypeDef",
     {
         "Parameters": List[TemplateParameterTypeDef],
         "Description": str,
         "Capabilities": List[CapabilityType],
         "CapabilitiesReason": str,
         "DeclaredTransforms": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackSetOperationResultsOutputTypeDef = TypedDict(
     "ListStackSetOperationResultsOutputTypeDef",
     {
         "Summaries": List[StackSetOperationResultSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDescribeTypeConfigurationsOutputTypeDef = TypedDict(
     "BatchDescribeTypeConfigurationsOutputTypeDef",
     {
         "Errors": List[BatchDescribeTypeConfigurationsErrorTypeDef],
         "UnprocessedTypeConfigurations": List[TypeConfigurationIdentifierTypeDef],
         "TypeConfigurations": List[TypeConfigurationDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSetHookTypeDef = TypedDict(
     "ChangeSetHookTypeDef",
     {
         "InvocationPoint": Literal["PRE_PROVISION"],
@@ -3016,15 +2994,15 @@
 )
 
 ListStackSetsOutputTypeDef = TypedDict(
     "ListStackSetsOutputTypeDef",
     {
         "Summaries": List[StackSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSummaryOutputTypeDef = TypedDict(
     "GetTemplateSummaryOutputTypeDef",
     {
         "Parameters": List[ParameterDeclarationTypeDef],
@@ -3032,32 +3010,32 @@
         "Capabilities": List[CapabilityType],
         "CapabilitiesReason": str,
         "ResourceTypes": List[str],
         "Version": str,
         "Metadata": str,
         "DeclaredTransforms": List[str],
         "ResourceIdentifierSummaries": List[ResourceIdentifierSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourceDriftsOutputTypeDef = TypedDict(
     "DescribeStackResourceDriftsOutputTypeDef",
     {
         "StackResourceDrifts": List[StackResourceDriftTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectStackResourceDriftOutputTypeDef = TypedDict(
     "DetectStackResourceDriftOutputTypeDef",
     {
         "StackResourceDrift": StackResourceDriftTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceChangeTypeDef = TypedDict(
     "ResourceChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -3094,14 +3072,15 @@
         "NotificationARNs": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "ClientToken": str,
         "Description": str,
         "ChangeSetType": ChangeSetTypeType,
         "ResourcesToImport": Sequence[ResourceToImportTypeDef],
         "IncludeNestedStacks": bool,
+        "OnStackFailure": OnStackFailureType,
     },
     total=False,
 )
 
 
 class CreateChangeSetInputRequestTypeDef(
     _RequiredCreateChangeSetInputRequestTypeDef, _OptionalCreateChangeSetInputRequestTypeDef
@@ -3281,96 +3260,96 @@
 )
 
 ListStacksOutputTypeDef = TypedDict(
     "ListStacksOutputTypeDef",
     {
         "StackSummaries": List[StackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackInstancesOutputTypeDef = TypedDict(
     "ListStackInstancesOutputTypeDef",
     {
         "Summaries": List[StackInstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackInstanceOutputTypeDef = TypedDict(
     "DescribeStackInstanceOutputTypeDef",
     {
         "StackInstance": StackInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourceOutputTypeDef = TypedDict(
     "DescribeStackResourceOutputTypeDef",
     {
         "StackResourceDetail": StackResourceDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourcesOutputTypeDef = TypedDict(
     "DescribeStackResourcesOutputTypeDef",
     {
         "StackResources": List[StackResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackResourcesOutputTypeDef = TypedDict(
     "ListStackResourcesOutputTypeDef",
     {
         "StackResourceSummaries": List[StackResourceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSetOutputTypeDef = TypedDict(
     "DescribeStackSetOutputTypeDef",
     {
         "StackSet": StackSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackSetOperationsOutputTypeDef = TypedDict(
     "ListStackSetOperationsOutputTypeDef",
     {
         "Summaries": List[StackSetOperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSetOperationOutputTypeDef = TypedDict(
     "DescribeStackSetOperationOutputTypeDef",
     {
         "StackSetOperation": StackSetOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChangeSetHooksOutputTypeDef = TypedDict(
     "DescribeChangeSetHooksOutputTypeDef",
     {
         "ChangeSetId": str,
         "ChangeSetName": str,
         "Hooks": List[ChangeSetHookTypeDef],
         "Status": ChangeSetHooksStatusType,
         "NextToken": str,
         "StackId": str,
         "StackName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeTypeDef = TypedDict(
     "ChangeTypeDef",
     {
         "Type": Literal["Resource"],
@@ -3381,15 +3360,15 @@
 )
 
 DescribeStacksOutputTypeDef = TypedDict(
     "DescribeStacksOutputTypeDef",
     {
         "Stacks": List[StackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChangeSetOutputTypeDef = TypedDict(
     "DescribeChangeSetOutputTypeDef",
     {
         "ChangeSetName": str,
@@ -3407,10 +3386,11 @@
         "Capabilities": List[CapabilityType],
         "Tags": List[TagTypeDef],
         "Changes": List[ChangeTypeDef],
         "NextToken": str,
         "IncludeNestedStacks": bool,
         "ParentChangeSetId": str,
         "RootChangeSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "OnStackFailure": OnStackFailureType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/type_defs.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -31,15 +31,17 @@
     EvaluationTypeType,
     ExecutionStatusType,
     HandlerErrorCodeType,
     HookFailureModeType,
     HookStatusType,
     IdentityProviderType,
     OnFailureType,
+    OnStackFailureType,
     OperationStatusType,
+    OrganizationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     PublisherStatusType,
     RegionConcurrencyTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ReplacementType,
@@ -76,168 +78,165 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountGateResultTypeDef",
     "AccountLimitTypeDef",
     "LoggingConfigTypeDef",
-    "ResponseMetadataTypeDef",
+    "ActivateTypeOutputTypeDef",
     "AutoDeploymentTypeDef",
     "TypeConfigurationIdentifierTypeDef",
     "TypeConfigurationDetailsTypeDef",
     "CancelUpdateStackInputRequestTypeDef",
     "CancelUpdateStackInputStackCancelUpdateTypeDef",
     "ChangeSetHookResourceTargetDetailsTypeDef",
     "ChangeSetSummaryTypeDef",
     "ContinueUpdateRollbackInputRequestTypeDef",
     "ParameterTypeDef",
     "ResourceToImportTypeDef",
     "TagTypeDef",
+    "CreateChangeSetOutputTypeDef",
     "DeploymentTargetsTypeDef",
     "StackSetOperationPreferencesTypeDef",
+    "CreateStackInstancesOutputTypeDef",
+    "CreateStackOutputTypeDef",
     "ManagedExecutionTypeDef",
+    "CreateStackSetOutputTypeDef",
     "DeactivateTypeInputRequestTypeDef",
     "DeleteChangeSetInputRequestTypeDef",
     "DeleteStackInputRequestTypeDef",
     "DeleteStackInputStackDeleteTypeDef",
+    "DeleteStackInstancesOutputTypeDef",
     "DeleteStackSetInputRequestTypeDef",
     "DeregisterTypeInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsInputRequestTypeDef",
     "DescribeChangeSetHooksInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
     "DescribeChangeSetInputRequestTypeDef",
+    "DescribeOrganizationsAccessInputRequestTypeDef",
+    "DescribeOrganizationsAccessOutputTypeDef",
     "DescribePublisherInputRequestTypeDef",
+    "DescribePublisherOutputTypeDef",
     "DescribeStackDriftDetectionStatusInputRequestTypeDef",
+    "DescribeStackDriftDetectionStatusOutputTypeDef",
+    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
     "DescribeStackEventsInputRequestTypeDef",
     "StackEventTypeDef",
     "DescribeStackInstanceInputRequestTypeDef",
     "DescribeStackResourceDriftsInputRequestTypeDef",
     "DescribeStackResourceInputRequestTypeDef",
     "DescribeStackResourcesInputRequestTypeDef",
     "DescribeStackSetInputRequestTypeDef",
     "DescribeStackSetOperationInputRequestTypeDef",
+    "DescribeStacksInputDescribeStacksPaginateTypeDef",
     "DescribeStacksInputRequestTypeDef",
     "DescribeTypeInputRequestTypeDef",
     "RequiredActivatedTypeTypeDef",
     "DescribeTypeRegistrationInputRequestTypeDef",
+    "DescribeTypeRegistrationOutputTypeDef",
     "DetectStackDriftInputRequestTypeDef",
+    "DetectStackDriftOutputTypeDef",
     "DetectStackResourceDriftInputRequestTypeDef",
+    "DetectStackSetDriftOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "EstimateTemplateCostOutputTypeDef",
     "ExecuteChangeSetInputRequestTypeDef",
     "ExportTypeDef",
     "GetStackPolicyInputRequestTypeDef",
+    "GetStackPolicyOutputTypeDef",
     "GetTemplateInputRequestTypeDef",
+    "GetTemplateOutputTypeDef",
     "GetTemplateSummaryInputRequestTypeDef",
     "ResourceIdentifierSummaryTypeDef",
+    "ImportStacksToStackSetOutputTypeDef",
+    "ListChangeSetsInputListChangeSetsPaginateTypeDef",
     "ListChangeSetsInputRequestTypeDef",
+    "ListExportsInputListExportsPaginateTypeDef",
     "ListExportsInputRequestTypeDef",
+    "ListImportsInputListImportsPaginateTypeDef",
     "ListImportsInputRequestTypeDef",
+    "ListImportsOutputTypeDef",
     "StackInstanceFilterTypeDef",
+    "ListStackResourcesInputListStackResourcesPaginateTypeDef",
     "ListStackResourcesInputRequestTypeDef",
     "OperationResultFilterTypeDef",
+    "ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
     "ListStackSetOperationsInputRequestTypeDef",
+    "ListStackSetsInputListStackSetsPaginateTypeDef",
     "ListStackSetsInputRequestTypeDef",
+    "ListStacksInputListStacksPaginateTypeDef",
     "ListStacksInputRequestTypeDef",
     "ListTypeRegistrationsInputRequestTypeDef",
+    "ListTypeRegistrationsOutputTypeDef",
     "ListTypeVersionsInputRequestTypeDef",
     "TypeVersionSummaryTypeDef",
     "TypeFiltersTypeDef",
     "TypeSummaryTypeDef",
+    "ModuleInfoResponseMetadataTypeDef",
     "ModuleInfoTypeDef",
     "OutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterConstraintsTypeDef",
     "PhysicalResourceIdContextKeyValuePairTypeDef",
     "PropertyDifferenceTypeDef",
     "PublishTypeInputRequestTypeDef",
+    "PublishTypeOutputTypeDef",
     "RecordHandlerProgressInputRequestTypeDef",
     "RegisterPublisherInputRequestTypeDef",
+    "RegisterPublisherOutputTypeDef",
+    "RegisterTypeOutputTypeDef",
     "ResourceTargetDefinitionTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTriggerTypeDef",
     "RollbackStackInputRequestTypeDef",
-    "ServiceResourceEventRequestTypeDef",
-    "ServiceResourceStackRequestTypeDef",
-    "ServiceResourceStackResourceRequestTypeDef",
-    "ServiceResourceStackResourceSummaryRequestTypeDef",
+    "RollbackStackOutputTypeDef",
     "SetStackPolicyInputRequestTypeDef",
     "SetTypeConfigurationInputRequestTypeDef",
+    "SetTypeConfigurationOutputTypeDef",
     "SetTypeDefaultVersionInputRequestTypeDef",
     "SignalResourceInputRequestTypeDef",
+    "StackDriftInformationResponseMetadataTypeDef",
     "StackDriftInformationSummaryTypeDef",
     "StackDriftInformationTypeDef",
     "StackInstanceComprehensiveStatusTypeDef",
     "StackResourceDriftInformationTypeDef",
+    "StackResourceDriftInformationResponseMetadataTypeDef",
+    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
     "StackResourceDriftInformationSummaryTypeDef",
-    "StackResourceRequestTypeDef",
     "StackSetDriftDetectionDetailsTypeDef",
     "StackSetOperationStatusDetailsTypeDef",
     "StopStackSetOperationInputRequestTypeDef",
     "TemplateParameterTypeDef",
     "TestTypeInputRequestTypeDef",
-    "UpdateTerminationProtectionInputRequestTypeDef",
-    "ValidateTemplateInputRequestTypeDef",
-    "StackSetOperationResultSummaryTypeDef",
-    "ActivateTypeInputRequestTypeDef",
-    "RegisterTypeInputRequestTypeDef",
-    "ActivateTypeOutputTypeDef",
-    "CreateChangeSetOutputTypeDef",
-    "CreateStackInstancesOutputTypeDef",
-    "CreateStackOutputTypeDef",
-    "CreateStackSetOutputTypeDef",
-    "DeleteStackInstancesOutputTypeDef",
-    "DescribeAccountLimitsOutputTypeDef",
-    "DescribePublisherOutputTypeDef",
-    "DescribeStackDriftDetectionStatusOutputTypeDef",
-    "DescribeTypeRegistrationOutputTypeDef",
-    "DetectStackDriftOutputTypeDef",
-    "DetectStackSetDriftOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EstimateTemplateCostOutputTypeDef",
-    "GetStackPolicyOutputTypeDef",
-    "GetTemplateOutputTypeDef",
-    "ImportStacksToStackSetOutputTypeDef",
-    "ListImportsOutputTypeDef",
-    "ListTypeRegistrationsOutputTypeDef",
-    "ModuleInfoResponseMetadataTypeDef",
-    "PublishTypeOutputTypeDef",
-    "RegisterPublisherOutputTypeDef",
-    "RegisterTypeOutputTypeDef",
-    "RollbackStackOutputTypeDef",
-    "SetTypeConfigurationOutputTypeDef",
-    "StackDriftInformationResponseMetadataTypeDef",
-    "StackResourceDriftInformationResponseMetadataTypeDef",
-    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
     "TestTypeOutputTypeDef",
     "UpdateStackInstancesOutputTypeDef",
     "UpdateStackOutputTypeDef",
     "UpdateStackSetOutputTypeDef",
+    "UpdateTerminationProtectionInputRequestTypeDef",
     "UpdateTerminationProtectionOutputTypeDef",
+    "ValidateTemplateInputRequestTypeDef",
+    "StackSetOperationResultSummaryTypeDef",
+    "DescribeAccountLimitsOutputTypeDef",
+    "ActivateTypeInputRequestTypeDef",
+    "RegisterTypeInputRequestTypeDef",
     "BatchDescribeTypeConfigurationsErrorTypeDef",
     "BatchDescribeTypeConfigurationsInputRequestTypeDef",
     "ChangeSetHookTargetDetailsTypeDef",
     "ListChangeSetsOutputTypeDef",
     "EstimateTemplateCostInputRequestTypeDef",
     "CreateStackInstancesInputRequestTypeDef",
     "DeleteStackInstancesInputRequestTypeDef",
     "DetectStackSetDriftInputRequestTypeDef",
     "ImportStacksToStackSetInputRequestTypeDef",
     "UpdateStackInstancesInputRequestTypeDef",
     "CreateStackSetInputRequestTypeDef",
     "StackSetSummaryTypeDef",
     "UpdateStackSetInputRequestTypeDef",
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    "DescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
-    "DescribeStacksInputDescribeStacksPaginateTypeDef",
-    "ListChangeSetsInputListChangeSetsPaginateTypeDef",
-    "ListExportsInputListExportsPaginateTypeDef",
-    "ListImportsInputListImportsPaginateTypeDef",
-    "ListStackResourcesInputListStackResourcesPaginateTypeDef",
-    "ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    "ListStackSetsInputListStackSetsPaginateTypeDef",
-    "ListStacksInputListStacksPaginateTypeDef",
     "DescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef",
     "DescribeStacksInputStackCreateCompleteWaitTypeDef",
     "DescribeStacksInputStackDeleteCompleteWaitTypeDef",
     "DescribeStacksInputStackExistsWaitTypeDef",
     "DescribeStacksInputStackImportCompleteWaitTypeDef",
     "DescribeStacksInputStackRollbackCompleteWaitTypeDef",
     "DescribeStacksInputStackUpdateCompleteWaitTypeDef",
@@ -319,22 +318,19 @@
     "LoggingConfigTypeDef",
     {
         "LogRoleArn": str,
         "LogGroupName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ActivateTypeOutputTypeDef = TypedDict(
+    "ActivateTypeOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoDeploymentTypeDef = TypedDict(
     "AutoDeploymentTypeDef",
     {
         "Enabled": bool,
@@ -471,14 +467,23 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateChangeSetOutputTypeDef = TypedDict(
+    "CreateChangeSetOutputTypeDef",
+    {
+        "Id": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentTargetsTypeDef = TypedDict(
     "DeploymentTargetsTypeDef",
     {
         "Accounts": Sequence[str],
         "AccountsUrl": str,
         "OrganizationalUnitIds": Sequence[str],
         "AccountFilterType": AccountFilterTypeType,
@@ -495,22 +500,46 @@
         "FailureTolerancePercentage": int,
         "MaxConcurrentCount": int,
         "MaxConcurrentPercentage": int,
     },
     total=False,
 )
 
+CreateStackInstancesOutputTypeDef = TypedDict(
+    "CreateStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStackOutputTypeDef = TypedDict(
+    "CreateStackOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ManagedExecutionTypeDef = TypedDict(
     "ManagedExecutionTypeDef",
     {
         "Active": bool,
     },
     total=False,
 )
 
+CreateStackSetOutputTypeDef = TypedDict(
+    "CreateStackSetOutputTypeDef",
+    {
+        "StackSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeactivateTypeInputRequestTypeDef = TypedDict(
     "DeactivateTypeInputRequestTypeDef",
     {
         "TypeName": str,
         "Type": ThirdPartyTypeType,
         "Arn": str,
     },
@@ -563,14 +592,22 @@
         "RetainResources": Sequence[str],
         "RoleARN": str,
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+DeleteStackInstancesOutputTypeDef = TypedDict(
+    "DeleteStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteStackSetInputRequestTypeDef = TypedDict(
     "_RequiredDeleteStackSetInputRequestTypeDef",
     {
         "StackSetName": str,
     },
 )
 _OptionalDeleteStackSetInputRequestTypeDef = TypedDict(
@@ -593,20 +630,18 @@
         "Type": RegistryTypeType,
         "TypeName": str,
         "VersionId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAccountLimitsInputRequestTypeDef = TypedDict(
     "DescribeAccountLimitsInputRequestTypeDef",
     {
@@ -642,14 +677,35 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
+    {
+        "ChangeSetName": str,
+    },
+)
+_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeChangeSetInputDescribeChangeSetPaginateTypeDef(
+    _RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
+    _OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeChangeSetInputRequestTypeDef = TypedDict(
     "_RequiredDescribeChangeSetInputRequestTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalDescribeChangeSetInputRequestTypeDef = TypedDict(
@@ -662,29 +718,79 @@
 )
 
 class DescribeChangeSetInputRequestTypeDef(
     _RequiredDescribeChangeSetInputRequestTypeDef, _OptionalDescribeChangeSetInputRequestTypeDef
 ):
     pass
 
+DescribeOrganizationsAccessInputRequestTypeDef = TypedDict(
+    "DescribeOrganizationsAccessInputRequestTypeDef",
+    {
+        "CallAs": CallAsType,
+    },
+    total=False,
+)
+
+DescribeOrganizationsAccessOutputTypeDef = TypedDict(
+    "DescribeOrganizationsAccessOutputTypeDef",
+    {
+        "Status": OrganizationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePublisherInputRequestTypeDef = TypedDict(
     "DescribePublisherInputRequestTypeDef",
     {
         "PublisherId": str,
     },
     total=False,
 )
 
+DescribePublisherOutputTypeDef = TypedDict(
+    "DescribePublisherOutputTypeDef",
+    {
+        "PublisherId": str,
+        "PublisherStatus": PublisherStatusType,
+        "IdentityProvider": IdentityProviderType,
+        "PublisherProfile": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeStackDriftDetectionStatusInputRequestTypeDef = TypedDict(
     "DescribeStackDriftDetectionStatusInputRequestTypeDef",
     {
         "StackDriftDetectionId": str,
     },
 )
 
+DescribeStackDriftDetectionStatusOutputTypeDef = TypedDict(
+    "DescribeStackDriftDetectionStatusOutputTypeDef",
+    {
+        "StackId": str,
+        "StackDriftDetectionId": str,
+        "StackDriftStatus": StackDriftStatusType,
+        "DetectionStatus": StackDriftDetectionStatusType,
+        "DetectionStatusReason": str,
+        "DriftedStackResourceCount": int,
+        "Timestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeStackEventsInputDescribeStackEventsPaginateTypeDef = TypedDict(
+    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStackEventsInputRequestTypeDef = TypedDict(
     "DescribeStackEventsInputRequestTypeDef",
     {
         "StackName": str,
         "NextToken": str,
     },
     total=False,
@@ -819,14 +925,23 @@
 
 class DescribeStackSetOperationInputRequestTypeDef(
     _RequiredDescribeStackSetOperationInputRequestTypeDef,
     _OptionalDescribeStackSetOperationInputRequestTypeDef,
 ):
     pass
 
+DescribeStacksInputDescribeStacksPaginateTypeDef = TypedDict(
+    "DescribeStacksInputDescribeStacksPaginateTypeDef",
+    {
+        "StackName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStacksInputRequestTypeDef = TypedDict(
     "DescribeStacksInputRequestTypeDef",
     {
         "StackName": str,
         "NextToken": str,
     },
     total=False,
@@ -859,14 +974,25 @@
 DescribeTypeRegistrationInputRequestTypeDef = TypedDict(
     "DescribeTypeRegistrationInputRequestTypeDef",
     {
         "RegistrationToken": str,
     },
 )
 
+DescribeTypeRegistrationOutputTypeDef = TypedDict(
+    "DescribeTypeRegistrationOutputTypeDef",
+    {
+        "ProgressStatus": RegistrationStatusType,
+        "Description": str,
+        "TypeArn": str,
+        "TypeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDetectStackDriftInputRequestTypeDef = TypedDict(
     "_RequiredDetectStackDriftInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalDetectStackDriftInputRequestTypeDef = TypedDict(
@@ -878,22 +1004,53 @@
 )
 
 class DetectStackDriftInputRequestTypeDef(
     _RequiredDetectStackDriftInputRequestTypeDef, _OptionalDetectStackDriftInputRequestTypeDef
 ):
     pass
 
+DetectStackDriftOutputTypeDef = TypedDict(
+    "DetectStackDriftOutputTypeDef",
+    {
+        "StackDriftDetectionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetectStackResourceDriftInputRequestTypeDef = TypedDict(
     "DetectStackResourceDriftInputRequestTypeDef",
     {
         "StackName": str,
         "LogicalResourceId": str,
     },
 )
 
+DetectStackSetDriftOutputTypeDef = TypedDict(
+    "DetectStackSetDriftOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EstimateTemplateCostOutputTypeDef = TypedDict(
+    "EstimateTemplateCostOutputTypeDef",
+    {
+        "Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExecuteChangeSetInputRequestTypeDef = TypedDict(
     "_RequiredExecuteChangeSetInputRequestTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalExecuteChangeSetInputRequestTypeDef = TypedDict(
@@ -924,24 +1081,41 @@
 GetStackPolicyInputRequestTypeDef = TypedDict(
     "GetStackPolicyInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 
+GetStackPolicyOutputTypeDef = TypedDict(
+    "GetStackPolicyOutputTypeDef",
+    {
+        "StackPolicyBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTemplateInputRequestTypeDef = TypedDict(
     "GetTemplateInputRequestTypeDef",
     {
         "StackName": str,
         "ChangeSetName": str,
         "TemplateStage": TemplateStageType,
     },
     total=False,
 )
 
+GetTemplateOutputTypeDef = TypedDict(
+    "GetTemplateOutputTypeDef",
+    {
+        "TemplateBody": Dict[str, Any],
+        "StagesAvailable": List[TemplateStageType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTemplateSummaryInputRequestTypeDef = TypedDict(
     "GetTemplateSummaryInputRequestTypeDef",
     {
         "TemplateBody": str,
         "TemplateURL": str,
         "StackName": str,
         "StackSetName": str,
@@ -956,14 +1130,42 @@
         "ResourceType": str,
         "LogicalResourceIds": List[str],
         "ResourceIdentifiers": List[str],
     },
     total=False,
 )
 
+ImportStacksToStackSetOutputTypeDef = TypedDict(
+    "ImportStacksToStackSetOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListChangeSetsInputListChangeSetsPaginateTypeDef(
+    _RequiredListChangeSetsInputListChangeSetsPaginateTypeDef,
+    _OptionalListChangeSetsInputListChangeSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListChangeSetsInputRequestTypeDef = TypedDict(
     "_RequiredListChangeSetsInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListChangeSetsInputRequestTypeDef = TypedDict(
@@ -975,22 +1177,50 @@
 )
 
 class ListChangeSetsInputRequestTypeDef(
     _RequiredListChangeSetsInputRequestTypeDef, _OptionalListChangeSetsInputRequestTypeDef
 ):
     pass
 
+ListExportsInputListExportsPaginateTypeDef = TypedDict(
+    "ListExportsInputListExportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListExportsInputRequestTypeDef = TypedDict(
     "ListExportsInputRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListImportsInputListImportsPaginateTypeDef = TypedDict(
+    "_RequiredListImportsInputListImportsPaginateTypeDef",
+    {
+        "ExportName": str,
+    },
+)
+_OptionalListImportsInputListImportsPaginateTypeDef = TypedDict(
+    "_OptionalListImportsInputListImportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListImportsInputListImportsPaginateTypeDef(
+    _RequiredListImportsInputListImportsPaginateTypeDef,
+    _OptionalListImportsInputListImportsPaginateTypeDef,
+):
+    pass
+
 _RequiredListImportsInputRequestTypeDef = TypedDict(
     "_RequiredListImportsInputRequestTypeDef",
     {
         "ExportName": str,
     },
 )
 _OptionalListImportsInputRequestTypeDef = TypedDict(
@@ -1002,23 +1232,52 @@
 )
 
 class ListImportsInputRequestTypeDef(
     _RequiredListImportsInputRequestTypeDef, _OptionalListImportsInputRequestTypeDef
 ):
     pass
 
+ListImportsOutputTypeDef = TypedDict(
+    "ListImportsOutputTypeDef",
+    {
+        "Imports": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StackInstanceFilterTypeDef = TypedDict(
     "StackInstanceFilterTypeDef",
     {
         "Name": StackInstanceFilterNameType,
         "Values": str,
     },
     total=False,
 )
 
+_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStackResourcesInputListStackResourcesPaginateTypeDef(
+    _RequiredListStackResourcesInputListStackResourcesPaginateTypeDef,
+    _OptionalListStackResourcesInputListStackResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListStackResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListStackResourcesInputRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListStackResourcesInputRequestTypeDef = TypedDict(
@@ -1039,14 +1298,35 @@
     {
         "Name": Literal["OPERATION_RESULT_STATUS"],
         "Values": str,
     },
     total=False,
 )
 
+_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
+    "_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
+    {
+        "StackSetName": str,
+    },
+)
+_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
+    "_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
+    {
+        "CallAs": CallAsType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef(
+    _RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
+    _OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListStackSetOperationsInputRequestTypeDef = TypedDict(
     "_RequiredListStackSetOperationsInputRequestTypeDef",
     {
         "StackSetName": str,
     },
 )
 _OptionalListStackSetOperationsInputRequestTypeDef = TypedDict(
@@ -1061,25 +1341,44 @@
 
 class ListStackSetOperationsInputRequestTypeDef(
     _RequiredListStackSetOperationsInputRequestTypeDef,
     _OptionalListStackSetOperationsInputRequestTypeDef,
 ):
     pass
 
+ListStackSetsInputListStackSetsPaginateTypeDef = TypedDict(
+    "ListStackSetsInputListStackSetsPaginateTypeDef",
+    {
+        "Status": StackSetStatusType,
+        "CallAs": CallAsType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStackSetsInputRequestTypeDef = TypedDict(
     "ListStackSetsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Status": StackSetStatusType,
         "CallAs": CallAsType,
     },
     total=False,
 )
 
+ListStacksInputListStacksPaginateTypeDef = TypedDict(
+    "ListStacksInputListStacksPaginateTypeDef",
+    {
+        "StackStatusFilter": Sequence[StackStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStacksInputRequestTypeDef = TypedDict(
     "ListStacksInputRequestTypeDef",
     {
         "NextToken": str,
         "StackStatusFilter": Sequence[StackStatusType],
     },
     total=False,
@@ -1094,14 +1393,23 @@
         "RegistrationStatusFilter": RegistrationStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListTypeRegistrationsOutputTypeDef = TypedDict(
+    "ListTypeRegistrationsOutputTypeDef",
+    {
+        "RegistrationTokenList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTypeVersionsInputRequestTypeDef = TypedDict(
     "ListTypeVersionsInputRequestTypeDef",
     {
         "Type": RegistryTypeType,
         "TypeName": str,
         "Arn": str,
         "MaxResults": int,
@@ -1153,14 +1461,23 @@
         "PublisherIdentity": IdentityProviderType,
         "PublisherName": str,
         "IsActivated": bool,
     },
     total=False,
 )
 
+ModuleInfoResponseMetadataTypeDef = TypedDict(
+    "ModuleInfoResponseMetadataTypeDef",
+    {
+        "TypeHierarchy": str,
+        "LogicalIdHierarchy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModuleInfoTypeDef = TypedDict(
     "ModuleInfoTypeDef",
     {
         "TypeHierarchy": str,
         "LogicalIdHierarchy": str,
     },
     total=False,
@@ -1173,14 +1490,24 @@
         "OutputValue": str,
         "Description": str,
         "ExportName": str,
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
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "AllowedValues": List[str],
     },
     total=False,
 )
@@ -1210,14 +1537,22 @@
         "Arn": str,
         "TypeName": str,
         "PublicVersionNumber": str,
     },
     total=False,
 )
 
+PublishTypeOutputTypeDef = TypedDict(
+    "PublishTypeOutputTypeDef",
+    {
+        "PublicTypeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecordHandlerProgressInputRequestTypeDef = TypedDict(
     "_RequiredRecordHandlerProgressInputRequestTypeDef",
     {
         "BearerToken": str,
         "OperationStatus": OperationStatusType,
     },
 )
@@ -1244,24 +1579,51 @@
     {
         "AcceptTermsAndConditions": bool,
         "ConnectionArn": str,
     },
     total=False,
 )
 
+RegisterPublisherOutputTypeDef = TypedDict(
+    "RegisterPublisherOutputTypeDef",
+    {
+        "PublisherId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTypeOutputTypeDef = TypedDict(
+    "RegisterTypeOutputTypeDef",
+    {
+        "RegistrationToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceTargetDefinitionTypeDef = TypedDict(
     "ResourceTargetDefinitionTypeDef",
     {
         "Attribute": ResourceAttributeType,
         "Name": str,
         "RequiresRecreation": RequiresRecreationType,
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
 RollbackTriggerTypeDef = TypedDict(
     "RollbackTriggerTypeDef",
     {
         "Arn": str,
         "Type": str,
     },
 )
@@ -1282,41 +1644,19 @@
 )
 
 class RollbackStackInputRequestTypeDef(
     _RequiredRollbackStackInputRequestTypeDef, _OptionalRollbackStackInputRequestTypeDef
 ):
     pass
 
-ServiceResourceEventRequestTypeDef = TypedDict(
-    "ServiceResourceEventRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceStackRequestTypeDef = TypedDict(
-    "ServiceResourceStackRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceStackResourceRequestTypeDef = TypedDict(
-    "ServiceResourceStackResourceRequestTypeDef",
-    {
-        "stack_name": str,
-        "logical_id": str,
-    },
-)
-
-ServiceResourceStackResourceSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceStackResourceSummaryRequestTypeDef",
+RollbackStackOutputTypeDef = TypedDict(
+    "RollbackStackOutputTypeDef",
     {
-        "stack_name": str,
-        "logical_id": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetStackPolicyInputRequestTypeDef = TypedDict(
     "_RequiredSetStackPolicyInputRequestTypeDef",
     {
         "StackName": str,
@@ -1355,14 +1695,22 @@
 
 class SetTypeConfigurationInputRequestTypeDef(
     _RequiredSetTypeConfigurationInputRequestTypeDef,
     _OptionalSetTypeConfigurationInputRequestTypeDef,
 ):
     pass
 
+SetTypeConfigurationOutputTypeDef = TypedDict(
+    "SetTypeConfigurationOutputTypeDef",
+    {
+        "ConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetTypeDefaultVersionInputRequestTypeDef = TypedDict(
     "SetTypeDefaultVersionInputRequestTypeDef",
     {
         "Arn": str,
         "Type": RegistryTypeType,
         "TypeName": str,
         "VersionId": str,
@@ -1376,14 +1724,23 @@
         "StackName": str,
         "LogicalResourceId": str,
         "UniqueId": str,
         "Status": ResourceSignalStatusType,
     },
 )
 
+StackDriftInformationResponseMetadataTypeDef = TypedDict(
+    "StackDriftInformationResponseMetadataTypeDef",
+    {
+        "StackDriftStatus": StackDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStackDriftInformationSummaryTypeDef = TypedDict(
     "_RequiredStackDriftInformationSummaryTypeDef",
     {
         "StackDriftStatus": StackDriftStatusType,
     },
 )
 _OptionalStackDriftInformationSummaryTypeDef = TypedDict(
@@ -1441,14 +1798,32 @@
 )
 
 class StackResourceDriftInformationTypeDef(
     _RequiredStackResourceDriftInformationTypeDef, _OptionalStackResourceDriftInformationTypeDef
 ):
     pass
 
+StackResourceDriftInformationResponseMetadataTypeDef = TypedDict(
+    "StackResourceDriftInformationResponseMetadataTypeDef",
+    {
+        "StackResourceDriftStatus": StackResourceDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StackResourceDriftInformationSummaryResponseMetadataTypeDef = TypedDict(
+    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
+    {
+        "StackResourceDriftStatus": StackResourceDriftStatusType,
+        "LastCheckTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStackResourceDriftInformationSummaryTypeDef = TypedDict(
     "_RequiredStackResourceDriftInformationSummaryTypeDef",
     {
         "StackResourceDriftStatus": StackResourceDriftStatusType,
     },
 )
 _OptionalStackResourceDriftInformationSummaryTypeDef = TypedDict(
@@ -1461,21 +1836,14 @@
 
 class StackResourceDriftInformationSummaryTypeDef(
     _RequiredStackResourceDriftInformationSummaryTypeDef,
     _OptionalStackResourceDriftInformationSummaryTypeDef,
 ):
     pass
 
-StackResourceRequestTypeDef = TypedDict(
-    "StackResourceRequestTypeDef",
-    {
-        "logical_id": str,
-    },
-)
-
 StackSetDriftDetectionDetailsTypeDef = TypedDict(
     "StackSetDriftDetectionDetailsTypeDef",
     {
         "DriftStatus": StackSetDriftStatusType,
         "DriftDetectionStatus": StackSetDriftDetectionStatusType,
         "LastDriftCheckTimestamp": datetime,
         "TotalStackInstancesCount": int,
@@ -1535,22 +1903,62 @@
         "TypeName": str,
         "VersionId": str,
         "LogDeliveryBucket": str,
     },
     total=False,
 )
 
+TestTypeOutputTypeDef = TypedDict(
+    "TestTypeOutputTypeDef",
+    {
+        "TypeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackInstancesOutputTypeDef = TypedDict(
+    "UpdateStackInstancesOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackOutputTypeDef = TypedDict(
+    "UpdateStackOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStackSetOutputTypeDef = TypedDict(
+    "UpdateStackSetOutputTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateTerminationProtectionInputRequestTypeDef = TypedDict(
     "UpdateTerminationProtectionInputRequestTypeDef",
     {
         "EnableTerminationProtection": bool,
         "StackName": str,
     },
 )
 
+UpdateTerminationProtectionOutputTypeDef = TypedDict(
+    "UpdateTerminationProtectionOutputTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ValidateTemplateInputRequestTypeDef = TypedDict(
     "ValidateTemplateInputRequestTypeDef",
     {
         "TemplateBody": str,
         "TemplateURL": str,
     },
     total=False,
@@ -1565,14 +1973,23 @@
         "StatusReason": str,
         "AccountGateResult": AccountGateResultTypeDef,
         "OrganizationalUnitId": str,
     },
     total=False,
 )
 
+DescribeAccountLimitsOutputTypeDef = TypedDict(
+    "DescribeAccountLimitsOutputTypeDef",
+    {
+        "AccountLimits": List[AccountLimitTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivateTypeInputRequestTypeDef = TypedDict(
     "ActivateTypeInputRequestTypeDef",
     {
         "Type": ThirdPartyTypeType,
         "PublicTypeArn": str,
         "PublisherId": str,
         "TypeName": str,
@@ -1605,298 +2022,14 @@
 )
 
 class RegisterTypeInputRequestTypeDef(
     _RequiredRegisterTypeInputRequestTypeDef, _OptionalRegisterTypeInputRequestTypeDef
 ):
     pass
 
-ActivateTypeOutputTypeDef = TypedDict(
-    "ActivateTypeOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChangeSetOutputTypeDef = TypedDict(
-    "CreateChangeSetOutputTypeDef",
-    {
-        "Id": str,
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackInstancesOutputTypeDef = TypedDict(
-    "CreateStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackOutputTypeDef = TypedDict(
-    "CreateStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackSetOutputTypeDef = TypedDict(
-    "CreateStackSetOutputTypeDef",
-    {
-        "StackSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteStackInstancesOutputTypeDef = TypedDict(
-    "DeleteStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountLimitsOutputTypeDef = TypedDict(
-    "DescribeAccountLimitsOutputTypeDef",
-    {
-        "AccountLimits": List[AccountLimitTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePublisherOutputTypeDef = TypedDict(
-    "DescribePublisherOutputTypeDef",
-    {
-        "PublisherId": str,
-        "PublisherStatus": PublisherStatusType,
-        "IdentityProvider": IdentityProviderType,
-        "PublisherProfile": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeStackDriftDetectionStatusOutputTypeDef = TypedDict(
-    "DescribeStackDriftDetectionStatusOutputTypeDef",
-    {
-        "StackId": str,
-        "StackDriftDetectionId": str,
-        "StackDriftStatus": StackDriftStatusType,
-        "DetectionStatus": StackDriftDetectionStatusType,
-        "DetectionStatusReason": str,
-        "DriftedStackResourceCount": int,
-        "Timestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTypeRegistrationOutputTypeDef = TypedDict(
-    "DescribeTypeRegistrationOutputTypeDef",
-    {
-        "ProgressStatus": RegistrationStatusType,
-        "Description": str,
-        "TypeArn": str,
-        "TypeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectStackDriftOutputTypeDef = TypedDict(
-    "DetectStackDriftOutputTypeDef",
-    {
-        "StackDriftDetectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectStackSetDriftOutputTypeDef = TypedDict(
-    "DetectStackSetDriftOutputTypeDef",
-    {
-        "OperationId": str,
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
-EstimateTemplateCostOutputTypeDef = TypedDict(
-    "EstimateTemplateCostOutputTypeDef",
-    {
-        "Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetStackPolicyOutputTypeDef = TypedDict(
-    "GetStackPolicyOutputTypeDef",
-    {
-        "StackPolicyBody": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemplateOutputTypeDef = TypedDict(
-    "GetTemplateOutputTypeDef",
-    {
-        "TemplateBody": Dict[str, Any],
-        "StagesAvailable": List[TemplateStageType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportStacksToStackSetOutputTypeDef = TypedDict(
-    "ImportStacksToStackSetOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListImportsOutputTypeDef = TypedDict(
-    "ListImportsOutputTypeDef",
-    {
-        "Imports": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTypeRegistrationsOutputTypeDef = TypedDict(
-    "ListTypeRegistrationsOutputTypeDef",
-    {
-        "RegistrationTokenList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModuleInfoResponseMetadataTypeDef = TypedDict(
-    "ModuleInfoResponseMetadataTypeDef",
-    {
-        "TypeHierarchy": str,
-        "LogicalIdHierarchy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishTypeOutputTypeDef = TypedDict(
-    "PublishTypeOutputTypeDef",
-    {
-        "PublicTypeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterPublisherOutputTypeDef = TypedDict(
-    "RegisterPublisherOutputTypeDef",
-    {
-        "PublisherId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTypeOutputTypeDef = TypedDict(
-    "RegisterTypeOutputTypeDef",
-    {
-        "RegistrationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackStackOutputTypeDef = TypedDict(
-    "RollbackStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetTypeConfigurationOutputTypeDef = TypedDict(
-    "SetTypeConfigurationOutputTypeDef",
-    {
-        "ConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackDriftInformationResponseMetadataTypeDef = TypedDict(
-    "StackDriftInformationResponseMetadataTypeDef",
-    {
-        "StackDriftStatus": StackDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackResourceDriftInformationResponseMetadataTypeDef = TypedDict(
-    "StackResourceDriftInformationResponseMetadataTypeDef",
-    {
-        "StackResourceDriftStatus": StackResourceDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackResourceDriftInformationSummaryResponseMetadataTypeDef = TypedDict(
-    "StackResourceDriftInformationSummaryResponseMetadataTypeDef",
-    {
-        "StackResourceDriftStatus": StackResourceDriftStatusType,
-        "LastCheckTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestTypeOutputTypeDef = TypedDict(
-    "TestTypeOutputTypeDef",
-    {
-        "TypeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackInstancesOutputTypeDef = TypedDict(
-    "UpdateStackInstancesOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackOutputTypeDef = TypedDict(
-    "UpdateStackOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStackSetOutputTypeDef = TypedDict(
-    "UpdateStackSetOutputTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTerminationProtectionOutputTypeDef = TypedDict(
-    "UpdateTerminationProtectionOutputTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchDescribeTypeConfigurationsErrorTypeDef = TypedDict(
     "BatchDescribeTypeConfigurationsErrorTypeDef",
     {
         "ErrorCode": str,
         "ErrorMessage": str,
         "TypeConfigurationIdentifier": TypeConfigurationIdentifierTypeDef,
     },
@@ -1920,15 +2053,15 @@
 )
 
 ListChangeSetsOutputTypeDef = TypedDict(
     "ListChangeSetsOutputTypeDef",
     {
         "Summaries": List[ChangeSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EstimateTemplateCostInputRequestTypeDef = TypedDict(
     "EstimateTemplateCostInputRequestTypeDef",
     {
         "TemplateBody": str,
@@ -2142,169 +2275,14 @@
 )
 
 class UpdateStackSetInputRequestTypeDef(
     _RequiredUpdateStackSetInputRequestTypeDef, _OptionalUpdateStackSetInputRequestTypeDef
 ):
     pass
 
-DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    {
-        "ChangeSetName": str,
-    },
-)
-_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeChangeSetInputDescribeChangeSetPaginateTypeDef(
-    _RequiredDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-    _OptionalDescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-):
-    pass
-
-DescribeStackEventsInputDescribeStackEventsPaginateTypeDef = TypedDict(
-    "DescribeStackEventsInputDescribeStackEventsPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeStacksInputDescribeStacksPaginateTypeDef = TypedDict(
-    "DescribeStacksInputDescribeStacksPaginateTypeDef",
-    {
-        "StackName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
-    "_RequiredListChangeSetsInputListChangeSetsPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef = TypedDict(
-    "_OptionalListChangeSetsInputListChangeSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListChangeSetsInputListChangeSetsPaginateTypeDef(
-    _RequiredListChangeSetsInputListChangeSetsPaginateTypeDef,
-    _OptionalListChangeSetsInputListChangeSetsPaginateTypeDef,
-):
-    pass
-
-ListExportsInputListExportsPaginateTypeDef = TypedDict(
-    "ListExportsInputListExportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListImportsInputListImportsPaginateTypeDef = TypedDict(
-    "_RequiredListImportsInputListImportsPaginateTypeDef",
-    {
-        "ExportName": str,
-    },
-)
-_OptionalListImportsInputListImportsPaginateTypeDef = TypedDict(
-    "_OptionalListImportsInputListImportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListImportsInputListImportsPaginateTypeDef(
-    _RequiredListImportsInputListImportsPaginateTypeDef,
-    _OptionalListImportsInputListImportsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListStackResourcesInputListStackResourcesPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListStackResourcesInputListStackResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStackResourcesInputListStackResourcesPaginateTypeDef(
-    _RequiredListStackResourcesInputListStackResourcesPaginateTypeDef,
-    _OptionalListStackResourcesInputListStackResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
-    "_RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    {
-        "StackSetName": str,
-    },
-)
-_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef = TypedDict(
-    "_OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef",
-    {
-        "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef(
-    _RequiredListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-    _OptionalListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-):
-    pass
-
-ListStackSetsInputListStackSetsPaginateTypeDef = TypedDict(
-    "ListStackSetsInputListStackSetsPaginateTypeDef",
-    {
-        "Status": StackSetStatusType,
-        "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListStacksInputListStacksPaginateTypeDef = TypedDict(
-    "ListStacksInputListStacksPaginateTypeDef",
-    {
-        "StackStatusFilter": Sequence[StackStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef = TypedDict(
     "_RequiredDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef",
     {
         "ChangeSetName": str,
     },
 )
 _OptionalDescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef = TypedDict(
@@ -2404,15 +2382,15 @@
     pass
 
 DescribeStackEventsOutputTypeDef = TypedDict(
     "DescribeStackEventsOutputTypeDef",
     {
         "StackEvents": List[StackEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTypeOutputTypeDef = TypedDict(
     "DescribeTypeOutputTypeDef",
     {
         "Arn": str,
@@ -2438,24 +2416,24 @@
         "PublisherId": str,
         "OriginalTypeName": str,
         "OriginalTypeArn": str,
         "PublicVersionNumber": str,
         "LatestPublicVersion": str,
         "IsActivated": bool,
         "AutoUpdate": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExportsOutputTypeDef = TypedDict(
     "ListExportsOutputTypeDef",
     {
         "Exports": List[ExportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListStackInstancesInputListStackInstancesPaginateTypeDef = TypedDict(
     "_RequiredListStackInstancesInputListStackInstancesPaginateTypeDef",
     {
         "StackSetName": str,
@@ -2464,15 +2442,15 @@
 _OptionalListStackInstancesInputListStackInstancesPaginateTypeDef = TypedDict(
     "_OptionalListStackInstancesInputListStackInstancesPaginateTypeDef",
     {
         "Filters": Sequence[StackInstanceFilterTypeDef],
         "StackInstanceAccount": str,
         "StackInstanceRegion": str,
         "CallAs": CallAsType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListStackInstancesInputListStackInstancesPaginateTypeDef(
     _RequiredListStackInstancesInputListStackInstancesPaginateTypeDef,
     _OptionalListStackInstancesInputListStackInstancesPaginateTypeDef,
@@ -2511,15 +2489,15 @@
     },
 )
 _OptionalListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef = TypedDict(
     "_OptionalListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef",
     {
         "CallAs": CallAsType,
         "Filters": Sequence[OperationResultFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef(
     _RequiredListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef,
     _OptionalListStackSetOperationResultsInputListStackSetOperationResultsPaginateTypeDef,
@@ -2551,27 +2529,27 @@
     pass
 
 ListTypeVersionsOutputTypeDef = TypedDict(
     "ListTypeVersionsOutputTypeDef",
     {
         "TypeVersionSummaries": List[TypeVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTypesInputListTypesPaginateTypeDef = TypedDict(
     "ListTypesInputListTypesPaginateTypeDef",
     {
         "Visibility": VisibilityType,
         "ProvisioningType": ProvisioningTypeType,
         "DeprecatedStatus": DeprecatedStatusType,
         "Type": RegistryTypeType,
         "Filters": TypeFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTypesInputRequestTypeDef = TypedDict(
     "ListTypesInputRequestTypeDef",
     {
@@ -2587,15 +2565,15 @@
 )
 
 ListTypesOutputTypeDef = TypedDict(
     "ListTypesOutputTypeDef",
     {
         "TypeSummaries": List[TypeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParameterDeclarationTypeDef = TypedDict(
     "ParameterDeclarationTypeDef",
     {
         "ParameterKey": str,
@@ -2648,15 +2626,15 @@
 )
 
 RollbackConfigurationResponseMetadataTypeDef = TypedDict(
     "RollbackConfigurationResponseMetadataTypeDef",
     {
         "RollbackTriggers": List[RollbackTriggerTypeDef],
         "MonitoringTimeInMinutes": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackConfigurationTypeDef = TypedDict(
     "RollbackConfigurationTypeDef",
     {
         "RollbackTriggers": Sequence[RollbackTriggerTypeDef],
@@ -2872,34 +2850,34 @@
     "ValidateTemplateOutputTypeDef",
     {
         "Parameters": List[TemplateParameterTypeDef],
         "Description": str,
         "Capabilities": List[CapabilityType],
         "CapabilitiesReason": str,
         "DeclaredTransforms": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackSetOperationResultsOutputTypeDef = TypedDict(
     "ListStackSetOperationResultsOutputTypeDef",
     {
         "Summaries": List[StackSetOperationResultSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDescribeTypeConfigurationsOutputTypeDef = TypedDict(
     "BatchDescribeTypeConfigurationsOutputTypeDef",
     {
         "Errors": List[BatchDescribeTypeConfigurationsErrorTypeDef],
         "UnprocessedTypeConfigurations": List[TypeConfigurationIdentifierTypeDef],
         "TypeConfigurations": List[TypeConfigurationDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSetHookTypeDef = TypedDict(
     "ChangeSetHookTypeDef",
     {
         "InvocationPoint": Literal["PRE_PROVISION"],
@@ -2913,15 +2891,15 @@
 )
 
 ListStackSetsOutputTypeDef = TypedDict(
     "ListStackSetsOutputTypeDef",
     {
         "Summaries": List[StackSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSummaryOutputTypeDef = TypedDict(
     "GetTemplateSummaryOutputTypeDef",
     {
         "Parameters": List[ParameterDeclarationTypeDef],
@@ -2929,32 +2907,32 @@
         "Capabilities": List[CapabilityType],
         "CapabilitiesReason": str,
         "ResourceTypes": List[str],
         "Version": str,
         "Metadata": str,
         "DeclaredTransforms": List[str],
         "ResourceIdentifierSummaries": List[ResourceIdentifierSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourceDriftsOutputTypeDef = TypedDict(
     "DescribeStackResourceDriftsOutputTypeDef",
     {
         "StackResourceDrifts": List[StackResourceDriftTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectStackResourceDriftOutputTypeDef = TypedDict(
     "DetectStackResourceDriftOutputTypeDef",
     {
         "StackResourceDrift": StackResourceDriftTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceChangeTypeDef = TypedDict(
     "ResourceChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -2991,14 +2969,15 @@
         "NotificationARNs": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "ClientToken": str,
         "Description": str,
         "ChangeSetType": ChangeSetTypeType,
         "ResourcesToImport": Sequence[ResourceToImportTypeDef],
         "IncludeNestedStacks": bool,
+        "OnStackFailure": OnStackFailureType,
     },
     total=False,
 )
 
 class CreateChangeSetInputRequestTypeDef(
     _RequiredCreateChangeSetInputRequestTypeDef, _OptionalCreateChangeSetInputRequestTypeDef
 ):
@@ -3168,96 +3147,96 @@
 )
 
 ListStacksOutputTypeDef = TypedDict(
     "ListStacksOutputTypeDef",
     {
         "StackSummaries": List[StackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackInstancesOutputTypeDef = TypedDict(
     "ListStackInstancesOutputTypeDef",
     {
         "Summaries": List[StackInstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackInstanceOutputTypeDef = TypedDict(
     "DescribeStackInstanceOutputTypeDef",
     {
         "StackInstance": StackInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourceOutputTypeDef = TypedDict(
     "DescribeStackResourceOutputTypeDef",
     {
         "StackResourceDetail": StackResourceDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackResourcesOutputTypeDef = TypedDict(
     "DescribeStackResourcesOutputTypeDef",
     {
         "StackResources": List[StackResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackResourcesOutputTypeDef = TypedDict(
     "ListStackResourcesOutputTypeDef",
     {
         "StackResourceSummaries": List[StackResourceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSetOutputTypeDef = TypedDict(
     "DescribeStackSetOutputTypeDef",
     {
         "StackSet": StackSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStackSetOperationsOutputTypeDef = TypedDict(
     "ListStackSetOperationsOutputTypeDef",
     {
         "Summaries": List[StackSetOperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSetOperationOutputTypeDef = TypedDict(
     "DescribeStackSetOperationOutputTypeDef",
     {
         "StackSetOperation": StackSetOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChangeSetHooksOutputTypeDef = TypedDict(
     "DescribeChangeSetHooksOutputTypeDef",
     {
         "ChangeSetId": str,
         "ChangeSetName": str,
         "Hooks": List[ChangeSetHookTypeDef],
         "Status": ChangeSetHooksStatusType,
         "NextToken": str,
         "StackId": str,
         "StackName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeTypeDef = TypedDict(
     "ChangeTypeDef",
     {
         "Type": Literal["Resource"],
@@ -3268,15 +3247,15 @@
 )
 
 DescribeStacksOutputTypeDef = TypedDict(
     "DescribeStacksOutputTypeDef",
     {
         "Stacks": List[StackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChangeSetOutputTypeDef = TypedDict(
     "DescribeChangeSetOutputTypeDef",
     {
         "ChangeSetName": str,
@@ -3294,10 +3273,11 @@
         "Capabilities": List[CapabilityType],
         "Tags": List[TagTypeDef],
         "Changes": List[ChangeTypeDef],
         "NextToken": str,
         "IncludeNestedStacks": bool,
         "ParentChangeSetId": str,
         "RootChangeSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "OnStackFailure": OnStackFailureType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/waiter.py` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation/waiter.pyi` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/PKG-INFO` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudformation
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudFormation 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudFormation 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudformation"></a>
 
 # types-aiobotocore-cloudformation
 
 [![PyPI - types-aiobotocore-cloudformation](https://img.shields.io/pypi/v/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
+[aiobotocore.CloudFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html#CloudFormation)
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
 [types-aiobotocore-cloudformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -497,16 +497,18 @@
     ListStackResourcesPaginatorName,
     ListStackSetOperationResultsPaginatorName,
     ListStackSetOperationsPaginatorName,
     ListStackSetsPaginatorName,
     ListStacksPaginatorName,
     ListTypesPaginatorName,
     OnFailureType,
+    OnStackFailureType,
     OperationResultFilterNameType,
     OperationStatusType,
+    OrganizationStatusType,
     PermissionModelsType,
     ProvisioningTypeType,
     PublisherStatusType,
     RegionConcurrencyTypeType,
     RegistrationStatusType,
     RegistryTypeType,
     ReplacementType,
@@ -560,168 +562,165 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudformation.type_defs import (
     AccountGateResultTypeDef,
     AccountLimitTypeDef,
     LoggingConfigTypeDef,
-    ResponseMetadataTypeDef,
+    ActivateTypeOutputTypeDef,
     AutoDeploymentTypeDef,
     TypeConfigurationIdentifierTypeDef,
     TypeConfigurationDetailsTypeDef,
     CancelUpdateStackInputRequestTypeDef,
     CancelUpdateStackInputStackCancelUpdateTypeDef,
     ChangeSetHookResourceTargetDetailsTypeDef,
     ChangeSetSummaryTypeDef,
     ContinueUpdateRollbackInputRequestTypeDef,
     ParameterTypeDef,
     ResourceToImportTypeDef,
     TagTypeDef,
+    CreateChangeSetOutputTypeDef,
     DeploymentTargetsTypeDef,
     StackSetOperationPreferencesTypeDef,
+    CreateStackInstancesOutputTypeDef,
+    CreateStackOutputTypeDef,
     ManagedExecutionTypeDef,
+    CreateStackSetOutputTypeDef,
     DeactivateTypeInputRequestTypeDef,
     DeleteChangeSetInputRequestTypeDef,
     DeleteStackInputRequestTypeDef,
     DeleteStackInputStackDeleteTypeDef,
+    DeleteStackInstancesOutputTypeDef,
     DeleteStackSetInputRequestTypeDef,
     DeregisterTypeInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     DescribeChangeSetHooksInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
     DescribeChangeSetInputRequestTypeDef,
+    DescribeOrganizationsAccessInputRequestTypeDef,
+    DescribeOrganizationsAccessOutputTypeDef,
     DescribePublisherInputRequestTypeDef,
+    DescribePublisherOutputTypeDef,
     DescribeStackDriftDetectionStatusInputRequestTypeDef,
+    DescribeStackDriftDetectionStatusOutputTypeDef,
+    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
     DescribeStackEventsInputRequestTypeDef,
     StackEventTypeDef,
     DescribeStackInstanceInputRequestTypeDef,
     DescribeStackResourceDriftsInputRequestTypeDef,
     DescribeStackResourceInputRequestTypeDef,
     DescribeStackResourcesInputRequestTypeDef,
     DescribeStackSetInputRequestTypeDef,
     DescribeStackSetOperationInputRequestTypeDef,
+    DescribeStacksInputDescribeStacksPaginateTypeDef,
     DescribeStacksInputRequestTypeDef,
     DescribeTypeInputRequestTypeDef,
     RequiredActivatedTypeTypeDef,
     DescribeTypeRegistrationInputRequestTypeDef,
+    DescribeTypeRegistrationOutputTypeDef,
     DetectStackDriftInputRequestTypeDef,
+    DetectStackDriftOutputTypeDef,
     DetectStackResourceDriftInputRequestTypeDef,
+    DetectStackSetDriftOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    EstimateTemplateCostOutputTypeDef,
     ExecuteChangeSetInputRequestTypeDef,
     ExportTypeDef,
     GetStackPolicyInputRequestTypeDef,
+    GetStackPolicyOutputTypeDef,
     GetTemplateInputRequestTypeDef,
+    GetTemplateOutputTypeDef,
     GetTemplateSummaryInputRequestTypeDef,
     ResourceIdentifierSummaryTypeDef,
+    ImportStacksToStackSetOutputTypeDef,
+    ListChangeSetsInputListChangeSetsPaginateTypeDef,
     ListChangeSetsInputRequestTypeDef,
+    ListExportsInputListExportsPaginateTypeDef,
     ListExportsInputRequestTypeDef,
+    ListImportsInputListImportsPaginateTypeDef,
     ListImportsInputRequestTypeDef,
+    ListImportsOutputTypeDef,
     StackInstanceFilterTypeDef,
+    ListStackResourcesInputListStackResourcesPaginateTypeDef,
     ListStackResourcesInputRequestTypeDef,
     OperationResultFilterTypeDef,
+    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
     ListStackSetOperationsInputRequestTypeDef,
+    ListStackSetsInputListStackSetsPaginateTypeDef,
     ListStackSetsInputRequestTypeDef,
+    ListStacksInputListStacksPaginateTypeDef,
     ListStacksInputRequestTypeDef,
     ListTypeRegistrationsInputRequestTypeDef,
+    ListTypeRegistrationsOutputTypeDef,
     ListTypeVersionsInputRequestTypeDef,
     TypeVersionSummaryTypeDef,
     TypeFiltersTypeDef,
     TypeSummaryTypeDef,
+    ModuleInfoResponseMetadataTypeDef,
     ModuleInfoTypeDef,
     OutputTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     PhysicalResourceIdContextKeyValuePairTypeDef,
     PropertyDifferenceTypeDef,
     PublishTypeInputRequestTypeDef,
+    PublishTypeOutputTypeDef,
     RecordHandlerProgressInputRequestTypeDef,
     RegisterPublisherInputRequestTypeDef,
+    RegisterPublisherOutputTypeDef,
+    RegisterTypeOutputTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     RollbackStackInputRequestTypeDef,
-    ServiceResourceEventRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackResourceRequestTypeDef,
-    ServiceResourceStackResourceSummaryRequestTypeDef,
+    RollbackStackOutputTypeDef,
     SetStackPolicyInputRequestTypeDef,
     SetTypeConfigurationInputRequestTypeDef,
+    SetTypeConfigurationOutputTypeDef,
     SetTypeDefaultVersionInputRequestTypeDef,
     SignalResourceInputRequestTypeDef,
+    StackDriftInformationResponseMetadataTypeDef,
     StackDriftInformationSummaryTypeDef,
     StackDriftInformationTypeDef,
     StackInstanceComprehensiveStatusTypeDef,
     StackResourceDriftInformationTypeDef,
+    StackResourceDriftInformationResponseMetadataTypeDef,
+    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     StackResourceDriftInformationSummaryTypeDef,
-    StackResourceRequestTypeDef,
     StackSetDriftDetectionDetailsTypeDef,
     StackSetOperationStatusDetailsTypeDef,
     StopStackSetOperationInputRequestTypeDef,
     TemplateParameterTypeDef,
     TestTypeInputRequestTypeDef,
-    UpdateTerminationProtectionInputRequestTypeDef,
-    ValidateTemplateInputRequestTypeDef,
-    StackSetOperationResultSummaryTypeDef,
-    ActivateTypeInputRequestTypeDef,
-    RegisterTypeInputRequestTypeDef,
-    ActivateTypeOutputTypeDef,
-    CreateChangeSetOutputTypeDef,
-    CreateStackInstancesOutputTypeDef,
-    CreateStackOutputTypeDef,
-    CreateStackSetOutputTypeDef,
-    DeleteStackInstancesOutputTypeDef,
-    DescribeAccountLimitsOutputTypeDef,
-    DescribePublisherOutputTypeDef,
-    DescribeStackDriftDetectionStatusOutputTypeDef,
-    DescribeTypeRegistrationOutputTypeDef,
-    DetectStackDriftOutputTypeDef,
-    DetectStackSetDriftOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EstimateTemplateCostOutputTypeDef,
-    GetStackPolicyOutputTypeDef,
-    GetTemplateOutputTypeDef,
-    ImportStacksToStackSetOutputTypeDef,
-    ListImportsOutputTypeDef,
-    ListTypeRegistrationsOutputTypeDef,
-    ModuleInfoResponseMetadataTypeDef,
-    PublishTypeOutputTypeDef,
-    RegisterPublisherOutputTypeDef,
-    RegisterTypeOutputTypeDef,
-    RollbackStackOutputTypeDef,
-    SetTypeConfigurationOutputTypeDef,
-    StackDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationResponseMetadataTypeDef,
-    StackResourceDriftInformationSummaryResponseMetadataTypeDef,
     TestTypeOutputTypeDef,
     UpdateStackInstancesOutputTypeDef,
     UpdateStackOutputTypeDef,
     UpdateStackSetOutputTypeDef,
+    UpdateTerminationProtectionInputRequestTypeDef,
     UpdateTerminationProtectionOutputTypeDef,
+    ValidateTemplateInputRequestTypeDef,
+    StackSetOperationResultSummaryTypeDef,
+    DescribeAccountLimitsOutputTypeDef,
+    ActivateTypeInputRequestTypeDef,
+    RegisterTypeInputRequestTypeDef,
     BatchDescribeTypeConfigurationsErrorTypeDef,
     BatchDescribeTypeConfigurationsInputRequestTypeDef,
     ChangeSetHookTargetDetailsTypeDef,
     ListChangeSetsOutputTypeDef,
     EstimateTemplateCostInputRequestTypeDef,
     CreateStackInstancesInputRequestTypeDef,
     DeleteStackInstancesInputRequestTypeDef,
     DetectStackSetDriftInputRequestTypeDef,
     ImportStacksToStackSetInputRequestTypeDef,
     UpdateStackInstancesInputRequestTypeDef,
     CreateStackSetInputRequestTypeDef,
     StackSetSummaryTypeDef,
     UpdateStackSetInputRequestTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
-    DescribeChangeSetInputDescribeChangeSetPaginateTypeDef,
-    DescribeStackEventsInputDescribeStackEventsPaginateTypeDef,
-    DescribeStacksInputDescribeStacksPaginateTypeDef,
-    ListChangeSetsInputListChangeSetsPaginateTypeDef,
-    ListExportsInputListExportsPaginateTypeDef,
-    ListImportsInputListImportsPaginateTypeDef,
-    ListStackResourcesInputListStackResourcesPaginateTypeDef,
-    ListStackSetOperationsInputListStackSetOperationsPaginateTypeDef,
-    ListStackSetsInputListStackSetsPaginateTypeDef,
-    ListStacksInputListStacksPaginateTypeDef,
     DescribeChangeSetInputChangeSetCreateCompleteWaitTypeDef,
     DescribeStacksInputStackCreateCompleteWaitTypeDef,
     DescribeStacksInputStackDeleteCompleteWaitTypeDef,
     DescribeStacksInputStackExistsWaitTypeDef,
     DescribeStacksInputStackImportCompleteWaitTypeDef,
     DescribeStacksInputStackRollbackCompleteWaitTypeDef,
     DescribeStacksInputStackUpdateCompleteWaitTypeDef,
@@ -789,43 +788,43 @@
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

### Comparing `types-aiobotocore-cloudformation-2.5.0.post1/types_aiobotocore_cloudformation.egg-info/SOURCES.txt` & `types-aiobotocore-cloudformation-2.5.1/types_aiobotocore_cloudformation.egg-info/SOURCES.txt`

 * *Files identical despite different names*

