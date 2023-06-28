# Comparing `tmp/types-aiobotocore-imagebuilder-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-imagebuilder-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-imagebuilder-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-imagebuilder-2.5.1.tar", last modified: Wed Jun 28 01:43:35 2023, max compression
```

## Comparing `types-aiobotocore-imagebuilder-2.5.0.post1.tar` & `types-aiobotocore-imagebuilder-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.227272 types-aiobotocore-imagebuilder-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18427 2023-03-11 12:26:44.227272 types-aiobotocore-imagebuilder-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16836 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.227272 types-aiobotocore-imagebuilder-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.219272 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/
--rw-r--r--   0 runner    (1001) docker     (123)      482 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      481 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    39886 2023-03-11 12:15:49.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    39827 2023-03-11 12:15:49.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8763 2023-03-11 12:15:49.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8761 2023-03-11 12:15:49.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    54216 2023-03-11 12:15:50.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    54167 2023-03-11 12:15:49.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:48.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.227272 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18427 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:44.000000 types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.742148 types-aiobotocore-imagebuilder-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:23.000000 types-aiobotocore-imagebuilder-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19842 2023-06-28 01:43:35.742148 types-aiobotocore-imagebuilder-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18257 2023-06-28 01:32:23.000000 types-aiobotocore-imagebuilder-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:35.742148 types-aiobotocore-imagebuilder-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:32:23.000000 types-aiobotocore-imagebuilder-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.742148 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/
+-rw-r--r--   0 runner    (1001) docker     (123)      482 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      481 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44284 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44219 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9690 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9688 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:24.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    66695 2023-06-28 01:32:26.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    66640 2023-06-28 01:32:26.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:23.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.742148 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19842 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:35.000000 types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/LICENSE` & `types-aiobotocore-imagebuilder-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/PKG-INFO` & `types-aiobotocore-imagebuilder-2.5.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-imagebuilder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.imagebuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.imagebuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-imagebuilder"></a>
 
 # types-aiobotocore-imagebuilder
 
 [![PyPI - types-aiobotocore-imagebuilder](https://img.shields.io/pypi/v/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-imagebuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-imagebuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.imagebuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
+[aiobotocore.imagebuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
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
 [types-aiobotocore-imagebuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,21 +277,26 @@
     ComponentFormatType,
     ComponentStatusType,
     ComponentTypeType,
     ContainerRepositoryServiceType,
     ContainerTypeType,
     DiskImageFormatType,
     EbsVolumeTypeType,
+    ImageScanStatusType,
     ImageSourceType,
     ImageStatusType,
     ImageTypeType,
     OwnershipType,
     PipelineExecutionStartConditionType,
     PipelineStatusType,
     PlatformType,
+    WorkflowExecutionStatusType,
+    WorkflowStepExecutionRollbackStatusType,
+    WorkflowStepExecutionStatusType,
+    WorkflowTypeType,
     imagebuilderServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
 def check_value(value: BuildTypeType) -> bool:
@@ -303,201 +308,234 @@
 ### Typed dictionaries
 
 `types_aiobotocore_imagebuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_imagebuilder.type_defs import (
+    SeverityCountsTypeDef,
     SystemsManagerAgentTypeDef,
     LaunchPermissionConfigurationTypeDef,
     ImageStateTypeDef,
     CancelImageCreationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelImageCreationResponseTypeDef,
     ComponentParameterTypeDef,
     ComponentParameterDetailTypeDef,
     ComponentStateTypeDef,
     ComponentVersionTypeDef,
     TargetContainerRepositoryTypeDef,
     ContainerRecipeSummaryTypeDef,
     ContainerTypeDef,
     CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateContainerRecipeResponseTypeDef,
+    CreateDistributionConfigurationResponseTypeDef,
     ImageTestsConfigurationTypeDef,
     ScheduleTypeDef,
+    CreateImagePipelineResponseTypeDef,
+    CreateImageRecipeResponseTypeDef,
+    CreateImageResponseTypeDef,
     InstanceMetadataOptionsTypeDef,
+    CreateInfrastructureConfigurationResponseTypeDef,
+    CvssScoreAdjustmentTypeDef,
+    CvssScoreTypeDef,
     DeleteComponentRequestRequestTypeDef,
+    DeleteComponentResponseTypeDef,
     DeleteContainerRecipeRequestRequestTypeDef,
+    DeleteContainerRecipeResponseTypeDef,
     DeleteDistributionConfigurationRequestRequestTypeDef,
+    DeleteDistributionConfigurationResponseTypeDef,
     DeleteImagePipelineRequestRequestTypeDef,
+    DeleteImagePipelineResponseTypeDef,
     DeleteImageRecipeRequestRequestTypeDef,
+    DeleteImageRecipeResponseTypeDef,
     DeleteImageRequestRequestTypeDef,
+    DeleteImageResponseTypeDef,
     DeleteInfrastructureConfigurationRequestRequestTypeDef,
+    DeleteInfrastructureConfigurationResponseTypeDef,
     DistributionConfigurationSummaryTypeDef,
     LaunchTemplateConfigurationTypeDef,
     S3ExportConfigurationTypeDef,
     EbsInstanceBlockDeviceSpecificationTypeDef,
+    EcrConfigurationTypeDef,
     FastLaunchLaunchTemplateSpecificationTypeDef,
     FastLaunchSnapshotConfigurationTypeDef,
     FilterTypeDef,
     GetComponentPolicyRequestRequestTypeDef,
+    GetComponentPolicyResponseTypeDef,
     GetComponentRequestRequestTypeDef,
     GetContainerRecipePolicyRequestRequestTypeDef,
+    GetContainerRecipePolicyResponseTypeDef,
     GetContainerRecipeRequestRequestTypeDef,
     GetDistributionConfigurationRequestRequestTypeDef,
     GetImagePipelineRequestRequestTypeDef,
     GetImagePolicyRequestRequestTypeDef,
+    GetImagePolicyResponseTypeDef,
     GetImageRecipePolicyRequestRequestTypeDef,
+    GetImageRecipePolicyResponseTypeDef,
     GetImageRecipeRequestRequestTypeDef,
     GetImageRequestRequestTypeDef,
     GetInfrastructureConfigurationRequestRequestTypeDef,
+    GetWorkflowExecutionRequestRequestTypeDef,
+    GetWorkflowExecutionResponseTypeDef,
+    GetWorkflowStepExecutionRequestRequestTypeDef,
+    GetWorkflowStepExecutionResponseTypeDef,
     ImagePackageTypeDef,
     ImageRecipeSummaryTypeDef,
+    ImageScanFindingsFilterTypeDef,
+    ImageScanStateTypeDef,
     ImageVersionTypeDef,
     ImportComponentRequestRequestTypeDef,
+    ImportComponentResponseTypeDef,
     ImportVmImageRequestRequestTypeDef,
+    ImportVmImageResponseTypeDef,
     InfrastructureConfigurationSummaryTypeDef,
     ListComponentBuildVersionsRequestRequestTypeDef,
     ListImagePackagesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkflowExecutionsRequestRequestTypeDef,
+    WorkflowExecutionMetadataTypeDef,
+    ListWorkflowStepExecutionsRequestRequestTypeDef,
+    WorkflowStepMetadataTypeDef,
     S3LogsTypeDef,
+    VulnerablePackageTypeDef,
     PutComponentPolicyRequestRequestTypeDef,
+    PutComponentPolicyResponseTypeDef,
     PutContainerRecipePolicyRequestRequestTypeDef,
+    PutContainerRecipePolicyResponseTypeDef,
     PutImagePolicyRequestRequestTypeDef,
+    PutImagePolicyResponseTypeDef,
     PutImageRecipePolicyRequestRequestTypeDef,
+    PutImageRecipePolicyResponseTypeDef,
+    RemediationRecommendationTypeDef,
+    ResponseMetadataTypeDef,
     StartImagePipelineExecutionRequestRequestTypeDef,
+    StartImagePipelineExecutionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AdditionalInstanceConfigurationTypeDef,
-    AmiDistributionConfigurationTypeDef,
-    AmiTypeDef,
-    CancelImageCreationResponseTypeDef,
-    CreateComponentResponseTypeDef,
-    CreateContainerRecipeResponseTypeDef,
-    CreateDistributionConfigurationResponseTypeDef,
-    CreateImagePipelineResponseTypeDef,
-    CreateImageRecipeResponseTypeDef,
-    CreateImageResponseTypeDef,
-    CreateInfrastructureConfigurationResponseTypeDef,
-    DeleteComponentResponseTypeDef,
-    DeleteContainerRecipeResponseTypeDef,
-    DeleteDistributionConfigurationResponseTypeDef,
-    DeleteImagePipelineResponseTypeDef,
-    DeleteImageRecipeResponseTypeDef,
-    DeleteImageResponseTypeDef,
-    DeleteInfrastructureConfigurationResponseTypeDef,
-    GetComponentPolicyResponseTypeDef,
-    GetContainerRecipePolicyResponseTypeDef,
-    GetImagePolicyResponseTypeDef,
-    GetImageRecipePolicyResponseTypeDef,
-    ImportComponentResponseTypeDef,
-    ImportVmImageResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutComponentPolicyResponseTypeDef,
-    PutContainerRecipePolicyResponseTypeDef,
-    PutImagePolicyResponseTypeDef,
-    PutImageRecipePolicyResponseTypeDef,
-    StartImagePipelineExecutionResponseTypeDef,
     UpdateDistributionConfigurationResponseTypeDef,
     UpdateImagePipelineResponseTypeDef,
     UpdateInfrastructureConfigurationResponseTypeDef,
+    AccountAggregationTypeDef,
+    ImageAggregationTypeDef,
+    ImagePipelineAggregationTypeDef,
+    VulnerabilityIdAggregationTypeDef,
+    AdditionalInstanceConfigurationTypeDef,
+    AmiDistributionConfigurationTypeDef,
+    AmiTypeDef,
     ComponentConfigurationTypeDef,
     ComponentSummaryTypeDef,
     ComponentTypeDef,
     ListComponentsResponseTypeDef,
     ContainerDistributionConfigurationTypeDef,
     ListContainerRecipesResponseTypeDef,
-    CreateImageRequestRequestTypeDef,
-    CreateImagePipelineRequestRequestTypeDef,
-    ImagePipelineTypeDef,
-    UpdateImagePipelineRequestRequestTypeDef,
+    CvssScoreDetailsTypeDef,
     ListDistributionConfigurationsResponseTypeDef,
     InstanceBlockDeviceMappingTypeDef,
+    ImageScanningConfigurationTypeDef,
     FastLaunchConfigurationTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListContainerRecipesRequestRequestTypeDef,
     ListDistributionConfigurationsRequestRequestTypeDef,
     ListImageBuildVersionsRequestRequestTypeDef,
     ListImagePipelineImagesRequestRequestTypeDef,
     ListImagePipelinesRequestRequestTypeDef,
     ListImageRecipesRequestRequestTypeDef,
+    ListImageScanFindingAggregationsRequestRequestTypeDef,
     ListImagesRequestRequestTypeDef,
     ListInfrastructureConfigurationsRequestRequestTypeDef,
     ListImagePackagesResponseTypeDef,
     ListImageRecipesResponseTypeDef,
+    ListImageScanFindingsRequestRequestTypeDef,
     ListImagesResponseTypeDef,
     ListInfrastructureConfigurationsResponseTypeDef,
+    ListWorkflowExecutionsResponseTypeDef,
+    ListWorkflowStepExecutionsResponseTypeDef,
     LoggingTypeDef,
+    PackageVulnerabilityDetailsTypeDef,
+    RemediationTypeDef,
+    ImageScanFindingAggregationTypeDef,
     OutputResourcesTypeDef,
     ListComponentBuildVersionsResponseTypeDef,
     GetComponentResponseTypeDef,
-    GetImagePipelineResponseTypeDef,
-    ListImagePipelinesResponseTypeDef,
+    InspectorScoreDetailsTypeDef,
     CreateImageRecipeRequestRequestTypeDef,
     ImageRecipeTypeDef,
     InstanceConfigurationTypeDef,
+    CreateImagePipelineRequestRequestTypeDef,
+    CreateImageRequestRequestTypeDef,
+    ImagePipelineTypeDef,
+    UpdateImagePipelineRequestRequestTypeDef,
     DistributionTypeDef,
     CreateInfrastructureConfigurationRequestRequestTypeDef,
     InfrastructureConfigurationTypeDef,
     UpdateInfrastructureConfigurationRequestRequestTypeDef,
+    ListImageScanFindingAggregationsResponseTypeDef,
     ImageSummaryTypeDef,
+    ImageScanFindingTypeDef,
     GetImageRecipeResponseTypeDef,
     ContainerRecipeTypeDef,
     CreateContainerRecipeRequestRequestTypeDef,
+    GetImagePipelineResponseTypeDef,
+    ListImagePipelinesResponseTypeDef,
     CreateDistributionConfigurationRequestRequestTypeDef,
     DistributionConfigurationTypeDef,
     UpdateDistributionConfigurationRequestRequestTypeDef,
     GetInfrastructureConfigurationResponseTypeDef,
     ListImageBuildVersionsResponseTypeDef,
     ListImagePipelineImagesResponseTypeDef,
+    ListImageScanFindingsResponseTypeDef,
     GetContainerRecipeResponseTypeDef,
     GetDistributionConfigurationResponseTypeDef,
     ImageTypeDef,
     GetImageResponseTypeDef,
 )
 
 
-def get_structure() -> SystemsManagerAgentTypeDef:
+def get_structure() -> SeverityCountsTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/README.md` & `types-aiobotocore-imagebuilder-2.5.1/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-imagebuilder"></a>
 
 # types-aiobotocore-imagebuilder
 
 [![PyPI - types-aiobotocore-imagebuilder](https://img.shields.io/pypi/v/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-imagebuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-imagebuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.imagebuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
+[aiobotocore.imagebuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
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
 [types-aiobotocore-imagebuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -244,21 +244,26 @@
     ComponentFormatType,
     ComponentStatusType,
     ComponentTypeType,
     ContainerRepositoryServiceType,
     ContainerTypeType,
     DiskImageFormatType,
     EbsVolumeTypeType,
+    ImageScanStatusType,
     ImageSourceType,
     ImageStatusType,
     ImageTypeType,
     OwnershipType,
     PipelineExecutionStartConditionType,
     PipelineStatusType,
     PlatformType,
+    WorkflowExecutionStatusType,
+    WorkflowStepExecutionRollbackStatusType,
+    WorkflowStepExecutionStatusType,
+    WorkflowTypeType,
     imagebuilderServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
 def check_value(value: BuildTypeType) -> bool:
@@ -270,201 +275,234 @@
 ### Typed dictionaries
 
 `types_aiobotocore_imagebuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_imagebuilder.type_defs import (
+    SeverityCountsTypeDef,
     SystemsManagerAgentTypeDef,
     LaunchPermissionConfigurationTypeDef,
     ImageStateTypeDef,
     CancelImageCreationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelImageCreationResponseTypeDef,
     ComponentParameterTypeDef,
     ComponentParameterDetailTypeDef,
     ComponentStateTypeDef,
     ComponentVersionTypeDef,
     TargetContainerRepositoryTypeDef,
     ContainerRecipeSummaryTypeDef,
     ContainerTypeDef,
     CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateContainerRecipeResponseTypeDef,
+    CreateDistributionConfigurationResponseTypeDef,
     ImageTestsConfigurationTypeDef,
     ScheduleTypeDef,
+    CreateImagePipelineResponseTypeDef,
+    CreateImageRecipeResponseTypeDef,
+    CreateImageResponseTypeDef,
     InstanceMetadataOptionsTypeDef,
+    CreateInfrastructureConfigurationResponseTypeDef,
+    CvssScoreAdjustmentTypeDef,
+    CvssScoreTypeDef,
     DeleteComponentRequestRequestTypeDef,
+    DeleteComponentResponseTypeDef,
     DeleteContainerRecipeRequestRequestTypeDef,
+    DeleteContainerRecipeResponseTypeDef,
     DeleteDistributionConfigurationRequestRequestTypeDef,
+    DeleteDistributionConfigurationResponseTypeDef,
     DeleteImagePipelineRequestRequestTypeDef,
+    DeleteImagePipelineResponseTypeDef,
     DeleteImageRecipeRequestRequestTypeDef,
+    DeleteImageRecipeResponseTypeDef,
     DeleteImageRequestRequestTypeDef,
+    DeleteImageResponseTypeDef,
     DeleteInfrastructureConfigurationRequestRequestTypeDef,
+    DeleteInfrastructureConfigurationResponseTypeDef,
     DistributionConfigurationSummaryTypeDef,
     LaunchTemplateConfigurationTypeDef,
     S3ExportConfigurationTypeDef,
     EbsInstanceBlockDeviceSpecificationTypeDef,
+    EcrConfigurationTypeDef,
     FastLaunchLaunchTemplateSpecificationTypeDef,
     FastLaunchSnapshotConfigurationTypeDef,
     FilterTypeDef,
     GetComponentPolicyRequestRequestTypeDef,
+    GetComponentPolicyResponseTypeDef,
     GetComponentRequestRequestTypeDef,
     GetContainerRecipePolicyRequestRequestTypeDef,
+    GetContainerRecipePolicyResponseTypeDef,
     GetContainerRecipeRequestRequestTypeDef,
     GetDistributionConfigurationRequestRequestTypeDef,
     GetImagePipelineRequestRequestTypeDef,
     GetImagePolicyRequestRequestTypeDef,
+    GetImagePolicyResponseTypeDef,
     GetImageRecipePolicyRequestRequestTypeDef,
+    GetImageRecipePolicyResponseTypeDef,
     GetImageRecipeRequestRequestTypeDef,
     GetImageRequestRequestTypeDef,
     GetInfrastructureConfigurationRequestRequestTypeDef,
+    GetWorkflowExecutionRequestRequestTypeDef,
+    GetWorkflowExecutionResponseTypeDef,
+    GetWorkflowStepExecutionRequestRequestTypeDef,
+    GetWorkflowStepExecutionResponseTypeDef,
     ImagePackageTypeDef,
     ImageRecipeSummaryTypeDef,
+    ImageScanFindingsFilterTypeDef,
+    ImageScanStateTypeDef,
     ImageVersionTypeDef,
     ImportComponentRequestRequestTypeDef,
+    ImportComponentResponseTypeDef,
     ImportVmImageRequestRequestTypeDef,
+    ImportVmImageResponseTypeDef,
     InfrastructureConfigurationSummaryTypeDef,
     ListComponentBuildVersionsRequestRequestTypeDef,
     ListImagePackagesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkflowExecutionsRequestRequestTypeDef,
+    WorkflowExecutionMetadataTypeDef,
+    ListWorkflowStepExecutionsRequestRequestTypeDef,
+    WorkflowStepMetadataTypeDef,
     S3LogsTypeDef,
+    VulnerablePackageTypeDef,
     PutComponentPolicyRequestRequestTypeDef,
+    PutComponentPolicyResponseTypeDef,
     PutContainerRecipePolicyRequestRequestTypeDef,
+    PutContainerRecipePolicyResponseTypeDef,
     PutImagePolicyRequestRequestTypeDef,
+    PutImagePolicyResponseTypeDef,
     PutImageRecipePolicyRequestRequestTypeDef,
+    PutImageRecipePolicyResponseTypeDef,
+    RemediationRecommendationTypeDef,
+    ResponseMetadataTypeDef,
     StartImagePipelineExecutionRequestRequestTypeDef,
+    StartImagePipelineExecutionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AdditionalInstanceConfigurationTypeDef,
-    AmiDistributionConfigurationTypeDef,
-    AmiTypeDef,
-    CancelImageCreationResponseTypeDef,
-    CreateComponentResponseTypeDef,
-    CreateContainerRecipeResponseTypeDef,
-    CreateDistributionConfigurationResponseTypeDef,
-    CreateImagePipelineResponseTypeDef,
-    CreateImageRecipeResponseTypeDef,
-    CreateImageResponseTypeDef,
-    CreateInfrastructureConfigurationResponseTypeDef,
-    DeleteComponentResponseTypeDef,
-    DeleteContainerRecipeResponseTypeDef,
-    DeleteDistributionConfigurationResponseTypeDef,
-    DeleteImagePipelineResponseTypeDef,
-    DeleteImageRecipeResponseTypeDef,
-    DeleteImageResponseTypeDef,
-    DeleteInfrastructureConfigurationResponseTypeDef,
-    GetComponentPolicyResponseTypeDef,
-    GetContainerRecipePolicyResponseTypeDef,
-    GetImagePolicyResponseTypeDef,
-    GetImageRecipePolicyResponseTypeDef,
-    ImportComponentResponseTypeDef,
-    ImportVmImageResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutComponentPolicyResponseTypeDef,
-    PutContainerRecipePolicyResponseTypeDef,
-    PutImagePolicyResponseTypeDef,
-    PutImageRecipePolicyResponseTypeDef,
-    StartImagePipelineExecutionResponseTypeDef,
     UpdateDistributionConfigurationResponseTypeDef,
     UpdateImagePipelineResponseTypeDef,
     UpdateInfrastructureConfigurationResponseTypeDef,
+    AccountAggregationTypeDef,
+    ImageAggregationTypeDef,
+    ImagePipelineAggregationTypeDef,
+    VulnerabilityIdAggregationTypeDef,
+    AdditionalInstanceConfigurationTypeDef,
+    AmiDistributionConfigurationTypeDef,
+    AmiTypeDef,
     ComponentConfigurationTypeDef,
     ComponentSummaryTypeDef,
     ComponentTypeDef,
     ListComponentsResponseTypeDef,
     ContainerDistributionConfigurationTypeDef,
     ListContainerRecipesResponseTypeDef,
-    CreateImageRequestRequestTypeDef,
-    CreateImagePipelineRequestRequestTypeDef,
-    ImagePipelineTypeDef,
-    UpdateImagePipelineRequestRequestTypeDef,
+    CvssScoreDetailsTypeDef,
     ListDistributionConfigurationsResponseTypeDef,
     InstanceBlockDeviceMappingTypeDef,
+    ImageScanningConfigurationTypeDef,
     FastLaunchConfigurationTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListContainerRecipesRequestRequestTypeDef,
     ListDistributionConfigurationsRequestRequestTypeDef,
     ListImageBuildVersionsRequestRequestTypeDef,
     ListImagePipelineImagesRequestRequestTypeDef,
     ListImagePipelinesRequestRequestTypeDef,
     ListImageRecipesRequestRequestTypeDef,
+    ListImageScanFindingAggregationsRequestRequestTypeDef,
     ListImagesRequestRequestTypeDef,
     ListInfrastructureConfigurationsRequestRequestTypeDef,
     ListImagePackagesResponseTypeDef,
     ListImageRecipesResponseTypeDef,
+    ListImageScanFindingsRequestRequestTypeDef,
     ListImagesResponseTypeDef,
     ListInfrastructureConfigurationsResponseTypeDef,
+    ListWorkflowExecutionsResponseTypeDef,
+    ListWorkflowStepExecutionsResponseTypeDef,
     LoggingTypeDef,
+    PackageVulnerabilityDetailsTypeDef,
+    RemediationTypeDef,
+    ImageScanFindingAggregationTypeDef,
     OutputResourcesTypeDef,
     ListComponentBuildVersionsResponseTypeDef,
     GetComponentResponseTypeDef,
-    GetImagePipelineResponseTypeDef,
-    ListImagePipelinesResponseTypeDef,
+    InspectorScoreDetailsTypeDef,
     CreateImageRecipeRequestRequestTypeDef,
     ImageRecipeTypeDef,
     InstanceConfigurationTypeDef,
+    CreateImagePipelineRequestRequestTypeDef,
+    CreateImageRequestRequestTypeDef,
+    ImagePipelineTypeDef,
+    UpdateImagePipelineRequestRequestTypeDef,
     DistributionTypeDef,
     CreateInfrastructureConfigurationRequestRequestTypeDef,
     InfrastructureConfigurationTypeDef,
     UpdateInfrastructureConfigurationRequestRequestTypeDef,
+    ListImageScanFindingAggregationsResponseTypeDef,
     ImageSummaryTypeDef,
+    ImageScanFindingTypeDef,
     GetImageRecipeResponseTypeDef,
     ContainerRecipeTypeDef,
     CreateContainerRecipeRequestRequestTypeDef,
+    GetImagePipelineResponseTypeDef,
+    ListImagePipelinesResponseTypeDef,
     CreateDistributionConfigurationRequestRequestTypeDef,
     DistributionConfigurationTypeDef,
     UpdateDistributionConfigurationRequestRequestTypeDef,
     GetInfrastructureConfigurationResponseTypeDef,
     ListImageBuildVersionsResponseTypeDef,
     ListImagePipelineImagesResponseTypeDef,
+    ListImageScanFindingsResponseTypeDef,
     GetContainerRecipeResponseTypeDef,
     GetDistributionConfigurationResponseTypeDef,
     ImageTypeDef,
     GetImageResponseTypeDef,
 )
 
 
-def get_structure() -> SystemsManagerAgentTypeDef:
+def get_structure() -> SeverityCountsTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/setup.py` & `types-aiobotocore-imagebuilder-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-imagebuilder.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-imagebuilder",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_imagebuilder"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.imagebuilder 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.imagebuilder 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/"
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/__main__.py` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.imagebuilder 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.imagebuilder 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder\nOther"
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/client.py` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -48,14 +48,18 @@
     GetDistributionConfigurationResponseTypeDef,
     GetImagePipelineResponseTypeDef,
     GetImagePolicyResponseTypeDef,
     GetImageRecipePolicyResponseTypeDef,
     GetImageRecipeResponseTypeDef,
     GetImageResponseTypeDef,
     GetInfrastructureConfigurationResponseTypeDef,
+    GetWorkflowExecutionResponseTypeDef,
+    GetWorkflowStepExecutionResponseTypeDef,
+    ImageScanFindingsFilterTypeDef,
+    ImageScanningConfigurationTypeDef,
     ImageTestsConfigurationTypeDef,
     ImportComponentResponseTypeDef,
     ImportVmImageResponseTypeDef,
     InstanceBlockDeviceMappingTypeDef,
     InstanceConfigurationTypeDef,
     InstanceMetadataOptionsTypeDef,
     ListComponentBuildVersionsResponseTypeDef,
@@ -63,17 +67,21 @@
     ListContainerRecipesResponseTypeDef,
     ListDistributionConfigurationsResponseTypeDef,
     ListImageBuildVersionsResponseTypeDef,
     ListImagePackagesResponseTypeDef,
     ListImagePipelineImagesResponseTypeDef,
     ListImagePipelinesResponseTypeDef,
     ListImageRecipesResponseTypeDef,
+    ListImageScanFindingAggregationsResponseTypeDef,
+    ListImageScanFindingsResponseTypeDef,
     ListImagesResponseTypeDef,
     ListInfrastructureConfigurationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWorkflowExecutionsResponseTypeDef,
+    ListWorkflowStepExecutionsResponseTypeDef,
     LoggingTypeDef,
     PutComponentPolicyResponseTypeDef,
     PutContainerRecipePolicyResponseTypeDef,
     PutImagePolicyResponseTypeDef,
     PutImageRecipePolicyResponseTypeDef,
     ScheduleTypeDef,
     StartImagePipelineExecutionResponseTypeDef,
@@ -84,26 +92,23 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("imagebuilderClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     CallRateLimitExceededException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ClientException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
@@ -116,15 +121,14 @@
     ResourceDependencyException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
 
-
 class imagebuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
     """
 
     meta: ClientMeta
@@ -133,41 +137,37 @@
     def exceptions(self) -> Exceptions:
         """
         imagebuilderClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#can_paginate)
         """
-
     async def cancel_image_creation(
         self, *, imageBuildVersionArn: str, clientToken: str
     ) -> CancelImageCreationResponseTypeDef:
         """
         CancelImageCreation cancels the creation of Image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.cancel_image_creation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#cancel_image_creation)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#close)
         """
-
     async def create_component(
         self,
         *,
         name: str,
         semanticVersion: str,
         platform: PlatformType,
         clientToken: str,
@@ -182,15 +182,14 @@
         """
         Creates a new component that can be used to build, validate, test, and assess
         your image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_component)
         """
-
     async def create_container_recipe(
         self,
         *,
         containerType: Literal["DOCKER"],
         name: str,
         semanticVersion: str,
         components: Sequence[ComponentConfigurationTypeDef],
@@ -209,15 +208,14 @@
     ) -> CreateContainerRecipeResponseTypeDef:
         """
         Creates a new container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_container_recipe)
         """
-
     async def create_distribution_configuration(
         self,
         *,
         name: str,
         distributions: Sequence[DistributionTypeDef],
         clientToken: str,
         description: str = ...,
@@ -225,57 +223,56 @@
     ) -> CreateDistributionConfigurationResponseTypeDef:
         """
         Creates a new distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_distribution_configuration)
         """
-
     async def create_image(
         self,
         *,
         infrastructureConfigurationArn: str,
         clientToken: str,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> CreateImageResponseTypeDef:
         """
         Creates a new image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image)
         """
-
     async def create_image_pipeline(
         self,
         *,
         name: str,
         infrastructureConfigurationArn: str,
         clientToken: str,
         description: str = ...,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
         schedule: ScheduleTypeDef = ...,
         status: PipelineStatusType = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> CreateImagePipelineResponseTypeDef:
         """
         Creates a new image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image_pipeline)
         """
-
     async def create_image_recipe(
         self,
         *,
         name: str,
         semanticVersion: str,
         components: Sequence[ComponentConfigurationTypeDef],
         parentImage: str,
@@ -288,15 +285,14 @@
     ) -> CreateImageRecipeResponseTypeDef:
         """
         Creates a new image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image_recipe)
         """
-
     async def create_infrastructure_configuration(
         self,
         *,
         name: str,
         instanceProfileName: str,
         clientToken: str,
         description: str = ...,
@@ -313,193 +309,193 @@
     ) -> CreateInfrastructureConfigurationResponseTypeDef:
         """
         Creates a new infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_infrastructure_configuration)
         """
-
     async def delete_component(
         self, *, componentBuildVersionArn: str
     ) -> DeleteComponentResponseTypeDef:
         """
         Deletes a component build version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_component)
         """
-
     async def delete_container_recipe(
         self, *, containerRecipeArn: str
     ) -> DeleteContainerRecipeResponseTypeDef:
         """
         Deletes a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_container_recipe)
         """
-
     async def delete_distribution_configuration(
         self, *, distributionConfigurationArn: str
     ) -> DeleteDistributionConfigurationResponseTypeDef:
         """
         Deletes a distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_distribution_configuration)
         """
-
     async def delete_image(self, *, imageBuildVersionArn: str) -> DeleteImageResponseTypeDef:
         """
         Deletes an Image Builder image resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image)
         """
-
     async def delete_image_pipeline(
         self, *, imagePipelineArn: str
     ) -> DeleteImagePipelineResponseTypeDef:
         """
         Deletes an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image_pipeline)
         """
-
     async def delete_image_recipe(self, *, imageRecipeArn: str) -> DeleteImageRecipeResponseTypeDef:
         """
         Deletes an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image_recipe)
         """
-
     async def delete_infrastructure_configuration(
         self, *, infrastructureConfigurationArn: str
     ) -> DeleteInfrastructureConfigurationResponseTypeDef:
         """
         Deletes an infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_infrastructure_configuration)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#generate_presigned_url)
         """
-
     async def get_component(self, *, componentBuildVersionArn: str) -> GetComponentResponseTypeDef:
         """
         Gets a component object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_component)
         """
-
     async def get_component_policy(self, *, componentArn: str) -> GetComponentPolicyResponseTypeDef:
         """
         Gets a component policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_component_policy)
         """
-
     async def get_container_recipe(
         self, *, containerRecipeArn: str
     ) -> GetContainerRecipeResponseTypeDef:
         """
         Retrieves a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_container_recipe)
         """
-
     async def get_container_recipe_policy(
         self, *, containerRecipeArn: str
     ) -> GetContainerRecipePolicyResponseTypeDef:
         """
         Retrieves the policy for a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_container_recipe_policy)
         """
-
     async def get_distribution_configuration(
         self, *, distributionConfigurationArn: str
     ) -> GetDistributionConfigurationResponseTypeDef:
         """
         Gets a distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_distribution_configuration)
         """
-
     async def get_image(self, *, imageBuildVersionArn: str) -> GetImageResponseTypeDef:
         """
         Gets an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image)
         """
-
     async def get_image_pipeline(self, *, imagePipelineArn: str) -> GetImagePipelineResponseTypeDef:
         """
         Gets an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_pipeline)
         """
-
     async def get_image_policy(self, *, imageArn: str) -> GetImagePolicyResponseTypeDef:
         """
         Gets an image policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_policy)
         """
-
     async def get_image_recipe(self, *, imageRecipeArn: str) -> GetImageRecipeResponseTypeDef:
         """
         Gets an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_recipe)
         """
-
     async def get_image_recipe_policy(
         self, *, imageRecipeArn: str
     ) -> GetImageRecipePolicyResponseTypeDef:
         """
         Gets an image recipe policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_recipe_policy)
         """
-
     async def get_infrastructure_configuration(
         self, *, infrastructureConfigurationArn: str
     ) -> GetInfrastructureConfigurationResponseTypeDef:
         """
         Gets an infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_infrastructure_configuration)
         """
+    async def get_workflow_execution(
+        self, *, workflowExecutionId: str
+    ) -> GetWorkflowExecutionResponseTypeDef:
+        """
+        Get the runtime information that was logged for a specific runtime instance of
+        the workflow.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_workflow_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_workflow_execution)
+        """
+    async def get_workflow_step_execution(
+        self, *, stepExecutionId: str
+    ) -> GetWorkflowStepExecutionResponseTypeDef:
+        """
+        Get the runtime information that was logged for a specific runtime instance of
+        the workflow step.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_workflow_step_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_workflow_step_execution)
+        """
     async def import_component(
         self,
         *,
         name: str,
         semanticVersion: str,
         type: ComponentTypeType,
         format: Literal["SHELL"],
@@ -514,15 +510,14 @@
     ) -> ImportComponentResponseTypeDef:
         """
         Imports a component and transforms its data into a component document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.import_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#import_component)
         """
-
     async def import_vm_image(
         self,
         *,
         name: str,
         semanticVersion: str,
         platform: PlatformType,
         vmImportTaskId: str,
@@ -535,25 +530,23 @@
         When you export your virtual machine (VM) from its virtualization environment,
         that process creates a set of one or more disk container files that act as
         snapshots of your VM’s environment, settings, and data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.import_vm_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#import_vm_image)
         """
-
     async def list_component_build_versions(
         self, *, componentVersionArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListComponentBuildVersionsResponseTypeDef:
         """
         Returns the list of component build versions for the specified semantic version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_component_build_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_component_build_versions)
         """
-
     async def list_components(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         byName: bool = ...,
         maxResults: int = ...,
@@ -562,106 +555,120 @@
         """
         Returns the list of components that can be filtered by name, or by using the
         listed `filters` to streamline results.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_components)
         """
-
     async def list_container_recipes(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListContainerRecipesResponseTypeDef:
         """
         Returns a list of container recipes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_container_recipes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_container_recipes)
         """
-
     async def list_distribution_configurations(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListDistributionConfigurationsResponseTypeDef:
         """
         Returns a list of distribution configurations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_distribution_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_distribution_configurations)
         """
-
     async def list_image_build_versions(
         self,
         *,
         imageVersionArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImageBuildVersionsResponseTypeDef:
         """
         Returns a list of image build versions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_build_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_build_versions)
         """
-
     async def list_image_packages(
         self, *, imageBuildVersionArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListImagePackagesResponseTypeDef:
         """
         List the Packages that are associated with an Image Build Version, as determined
         by Amazon Web Services Systems Manager Inventory at build time.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_packages)
         """
-
     async def list_image_pipeline_images(
         self,
         *,
         imagePipelineArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImagePipelineImagesResponseTypeDef:
         """
         Returns a list of images created by the specified pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipeline_images)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_pipeline_images)
         """
-
     async def list_image_pipelines(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListImagePipelinesResponseTypeDef:
         """
         Returns a list of image pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipelines)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_pipelines)
         """
-
     async def list_image_recipes(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImageRecipesResponseTypeDef:
         """
         Returns a list of image recipes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_recipes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_recipes)
         """
+    async def list_image_scan_finding_aggregations(
+        self, *, filter: FilterTypeDef = ..., nextToken: str = ...
+    ) -> ListImageScanFindingAggregationsResponseTypeDef:
+        """
+        Returns a list of image scan aggregations for your account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_scan_finding_aggregations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_scan_finding_aggregations)
+        """
+    async def list_image_scan_findings(
+        self,
+        *,
+        filters: Sequence[ImageScanFindingsFilterTypeDef] = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListImageScanFindingsResponseTypeDef:
+        """
+        Returns a list of image scan findings for your account.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_scan_findings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_scan_findings)
+        """
     async def list_images(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         byName: bool = ...,
         maxResults: int = ...,
@@ -670,138 +677,147 @@
     ) -> ListImagesResponseTypeDef:
         """
         Returns the list of images that you have access to.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_images)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_images)
         """
-
     async def list_infrastructure_configurations(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListInfrastructureConfigurationsResponseTypeDef:
         """
         Returns a list of infrastructure configurations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_infrastructure_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_infrastructure_configurations)
         """
-
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Returns the list of tags for the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_tags_for_resource)
         """
+    async def list_workflow_executions(
+        self, *, imageBuildVersionArn: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListWorkflowExecutionsResponseTypeDef:
+        """
+        Returns a list of workflow runtime instance metadata objects for a specific
+        image build version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_workflow_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_workflow_executions)
+        """
+    async def list_workflow_step_executions(
+        self, *, workflowExecutionId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListWorkflowStepExecutionsResponseTypeDef:
+        """
+        Shows runtime data for each step in a runtime instance of the workflow that you
+        specify in the request.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_workflow_step_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_workflow_step_executions)
+        """
     async def put_component_policy(
         self, *, componentArn: str, policy: str
     ) -> PutComponentPolicyResponseTypeDef:
         """
         Applies a policy to a component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_component_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_component_policy)
         """
-
     async def put_container_recipe_policy(
         self, *, containerRecipeArn: str, policy: str
     ) -> PutContainerRecipePolicyResponseTypeDef:
         """
         Applies a policy to a container image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_container_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_container_recipe_policy)
         """
-
     async def put_image_policy(
         self, *, imageArn: str, policy: str
     ) -> PutImagePolicyResponseTypeDef:
         """
         Applies a policy to an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_image_policy)
         """
-
     async def put_image_recipe_policy(
         self, *, imageRecipeArn: str, policy: str
     ) -> PutImageRecipePolicyResponseTypeDef:
         """
         Applies a policy to an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_image_recipe_policy)
         """
-
     async def start_image_pipeline_execution(
         self, *, imagePipelineArn: str, clientToken: str
     ) -> StartImagePipelineExecutionResponseTypeDef:
         """
         Manually triggers a pipeline to create an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.start_image_pipeline_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#start_image_pipeline_execution)
         """
-
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds a tag to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#tag_resource)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a tag from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#untag_resource)
         """
-
     async def update_distribution_configuration(
         self,
         *,
         distributionConfigurationArn: str,
         distributions: Sequence[DistributionTypeDef],
         clientToken: str,
         description: str = ...
     ) -> UpdateDistributionConfigurationResponseTypeDef:
         """
         Updates a new distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_distribution_configuration)
         """
-
     async def update_image_pipeline(
         self,
         *,
         imagePipelineArn: str,
         infrastructureConfigurationArn: str,
         clientToken: str,
         description: str = ...,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
         schedule: ScheduleTypeDef = ...,
-        status: PipelineStatusType = ...
+        status: PipelineStatusType = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> UpdateImagePipelineResponseTypeDef:
         """
         Updates an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_image_pipeline)
         """
-
     async def update_infrastructure_configuration(
         self,
         *,
         infrastructureConfigurationArn: str,
         instanceProfileName: str,
         clientToken: str,
         description: str = ...,
@@ -817,19 +833,17 @@
     ) -> UpdateInfrastructureConfigurationResponseTypeDef:
         """
         Updates a new infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_infrastructure_configuration)
         """
-
     async def __aenter__(self) -> "imagebuilderClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
         """
```

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/client.pyi` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/client.py`

 * *Files 5% similar despite different names*

```diff
@@ -48,14 +48,18 @@
     GetDistributionConfigurationResponseTypeDef,
     GetImagePipelineResponseTypeDef,
     GetImagePolicyResponseTypeDef,
     GetImageRecipePolicyResponseTypeDef,
     GetImageRecipeResponseTypeDef,
     GetImageResponseTypeDef,
     GetInfrastructureConfigurationResponseTypeDef,
+    GetWorkflowExecutionResponseTypeDef,
+    GetWorkflowStepExecutionResponseTypeDef,
+    ImageScanFindingsFilterTypeDef,
+    ImageScanningConfigurationTypeDef,
     ImageTestsConfigurationTypeDef,
     ImportComponentResponseTypeDef,
     ImportVmImageResponseTypeDef,
     InstanceBlockDeviceMappingTypeDef,
     InstanceConfigurationTypeDef,
     InstanceMetadataOptionsTypeDef,
     ListComponentBuildVersionsResponseTypeDef,
@@ -63,17 +67,21 @@
     ListContainerRecipesResponseTypeDef,
     ListDistributionConfigurationsResponseTypeDef,
     ListImageBuildVersionsResponseTypeDef,
     ListImagePackagesResponseTypeDef,
     ListImagePipelineImagesResponseTypeDef,
     ListImagePipelinesResponseTypeDef,
     ListImageRecipesResponseTypeDef,
+    ListImageScanFindingAggregationsResponseTypeDef,
+    ListImageScanFindingsResponseTypeDef,
     ListImagesResponseTypeDef,
     ListInfrastructureConfigurationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWorkflowExecutionsResponseTypeDef,
+    ListWorkflowStepExecutionsResponseTypeDef,
     LoggingTypeDef,
     PutComponentPolicyResponseTypeDef,
     PutContainerRecipePolicyResponseTypeDef,
     PutImagePolicyResponseTypeDef,
     PutImageRecipePolicyResponseTypeDef,
     ScheduleTypeDef,
     StartImagePipelineExecutionResponseTypeDef,
@@ -84,23 +92,26 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("imagebuilderClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     CallRateLimitExceededException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ClientException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
@@ -113,14 +124,15 @@
     ResourceDependencyException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
 
+
 class imagebuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
     """
 
     meta: ClientMeta
@@ -129,37 +141,41 @@
     def exceptions(self) -> Exceptions:
         """
         imagebuilderClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#can_paginate)
         """
+
     async def cancel_image_creation(
         self, *, imageBuildVersionArn: str, clientToken: str
     ) -> CancelImageCreationResponseTypeDef:
         """
         CancelImageCreation cancels the creation of Image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.cancel_image_creation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#cancel_image_creation)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#close)
         """
+
     async def create_component(
         self,
         *,
         name: str,
         semanticVersion: str,
         platform: PlatformType,
         clientToken: str,
@@ -174,14 +190,15 @@
         """
         Creates a new component that can be used to build, validate, test, and assess
         your image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_component)
         """
+
     async def create_container_recipe(
         self,
         *,
         containerType: Literal["DOCKER"],
         name: str,
         semanticVersion: str,
         components: Sequence[ComponentConfigurationTypeDef],
@@ -200,14 +217,15 @@
     ) -> CreateContainerRecipeResponseTypeDef:
         """
         Creates a new container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_container_recipe)
         """
+
     async def create_distribution_configuration(
         self,
         *,
         name: str,
         distributions: Sequence[DistributionTypeDef],
         clientToken: str,
         description: str = ...,
@@ -215,54 +233,59 @@
     ) -> CreateDistributionConfigurationResponseTypeDef:
         """
         Creates a new distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_distribution_configuration)
         """
+
     async def create_image(
         self,
         *,
         infrastructureConfigurationArn: str,
         clientToken: str,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> CreateImageResponseTypeDef:
         """
         Creates a new image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image)
         """
+
     async def create_image_pipeline(
         self,
         *,
         name: str,
         infrastructureConfigurationArn: str,
         clientToken: str,
         description: str = ...,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
         schedule: ScheduleTypeDef = ...,
         status: PipelineStatusType = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> CreateImagePipelineResponseTypeDef:
         """
         Creates a new image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image_pipeline)
         """
+
     async def create_image_recipe(
         self,
         *,
         name: str,
         semanticVersion: str,
         components: Sequence[ComponentConfigurationTypeDef],
         parentImage: str,
@@ -275,14 +298,15 @@
     ) -> CreateImageRecipeResponseTypeDef:
         """
         Creates a new image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_image_recipe)
         """
+
     async def create_infrastructure_configuration(
         self,
         *,
         name: str,
         instanceProfileName: str,
         clientToken: str,
         description: str = ...,
@@ -299,173 +323,215 @@
     ) -> CreateInfrastructureConfigurationResponseTypeDef:
         """
         Creates a new infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.create_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#create_infrastructure_configuration)
         """
+
     async def delete_component(
         self, *, componentBuildVersionArn: str
     ) -> DeleteComponentResponseTypeDef:
         """
         Deletes a component build version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_component)
         """
+
     async def delete_container_recipe(
         self, *, containerRecipeArn: str
     ) -> DeleteContainerRecipeResponseTypeDef:
         """
         Deletes a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_container_recipe)
         """
+
     async def delete_distribution_configuration(
         self, *, distributionConfigurationArn: str
     ) -> DeleteDistributionConfigurationResponseTypeDef:
         """
         Deletes a distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_distribution_configuration)
         """
+
     async def delete_image(self, *, imageBuildVersionArn: str) -> DeleteImageResponseTypeDef:
         """
         Deletes an Image Builder image resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image)
         """
+
     async def delete_image_pipeline(
         self, *, imagePipelineArn: str
     ) -> DeleteImagePipelineResponseTypeDef:
         """
         Deletes an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image_pipeline)
         """
+
     async def delete_image_recipe(self, *, imageRecipeArn: str) -> DeleteImageRecipeResponseTypeDef:
         """
         Deletes an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_image_recipe)
         """
+
     async def delete_infrastructure_configuration(
         self, *, infrastructureConfigurationArn: str
     ) -> DeleteInfrastructureConfigurationResponseTypeDef:
         """
         Deletes an infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.delete_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#delete_infrastructure_configuration)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#generate_presigned_url)
         """
+
     async def get_component(self, *, componentBuildVersionArn: str) -> GetComponentResponseTypeDef:
         """
         Gets a component object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_component)
         """
+
     async def get_component_policy(self, *, componentArn: str) -> GetComponentPolicyResponseTypeDef:
         """
         Gets a component policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_component_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_component_policy)
         """
+
     async def get_container_recipe(
         self, *, containerRecipeArn: str
     ) -> GetContainerRecipeResponseTypeDef:
         """
         Retrieves a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_container_recipe)
         """
+
     async def get_container_recipe_policy(
         self, *, containerRecipeArn: str
     ) -> GetContainerRecipePolicyResponseTypeDef:
         """
         Retrieves the policy for a container recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_container_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_container_recipe_policy)
         """
+
     async def get_distribution_configuration(
         self, *, distributionConfigurationArn: str
     ) -> GetDistributionConfigurationResponseTypeDef:
         """
         Gets a distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_distribution_configuration)
         """
+
     async def get_image(self, *, imageBuildVersionArn: str) -> GetImageResponseTypeDef:
         """
         Gets an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image)
         """
+
     async def get_image_pipeline(self, *, imagePipelineArn: str) -> GetImagePipelineResponseTypeDef:
         """
         Gets an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_pipeline)
         """
+
     async def get_image_policy(self, *, imageArn: str) -> GetImagePolicyResponseTypeDef:
         """
         Gets an image policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_policy)
         """
+
     async def get_image_recipe(self, *, imageRecipeArn: str) -> GetImageRecipeResponseTypeDef:
         """
         Gets an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_recipe)
         """
+
     async def get_image_recipe_policy(
         self, *, imageRecipeArn: str
     ) -> GetImageRecipePolicyResponseTypeDef:
         """
         Gets an image recipe policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_image_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_image_recipe_policy)
         """
+
     async def get_infrastructure_configuration(
         self, *, infrastructureConfigurationArn: str
     ) -> GetInfrastructureConfigurationResponseTypeDef:
         """
         Gets an infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_infrastructure_configuration)
         """
+
+    async def get_workflow_execution(
+        self, *, workflowExecutionId: str
+    ) -> GetWorkflowExecutionResponseTypeDef:
+        """
+        Get the runtime information that was logged for a specific runtime instance of
+        the workflow.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_workflow_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_workflow_execution)
+        """
+
+    async def get_workflow_step_execution(
+        self, *, stepExecutionId: str
+    ) -> GetWorkflowStepExecutionResponseTypeDef:
+        """
+        Get the runtime information that was logged for a specific runtime instance of
+        the workflow step.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.get_workflow_step_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#get_workflow_step_execution)
+        """
+
     async def import_component(
         self,
         *,
         name: str,
         semanticVersion: str,
         type: ComponentTypeType,
         format: Literal["SHELL"],
@@ -480,14 +546,15 @@
     ) -> ImportComponentResponseTypeDef:
         """
         Imports a component and transforms its data into a component document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.import_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#import_component)
         """
+
     async def import_vm_image(
         self,
         *,
         name: str,
         semanticVersion: str,
         platform: PlatformType,
         vmImportTaskId: str,
@@ -500,23 +567,25 @@
         When you export your virtual machine (VM) from its virtualization environment,
         that process creates a set of one or more disk container files that act as
         snapshots of your VM’s environment, settings, and data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.import_vm_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#import_vm_image)
         """
+
     async def list_component_build_versions(
         self, *, componentVersionArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListComponentBuildVersionsResponseTypeDef:
         """
         Returns the list of component build versions for the specified semantic version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_component_build_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_component_build_versions)
         """
+
     async def list_components(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         byName: bool = ...,
         maxResults: int = ...,
@@ -525,98 +594,130 @@
         """
         Returns the list of components that can be filtered by name, or by using the
         listed `filters` to streamline results.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_components)
         """
+
     async def list_container_recipes(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListContainerRecipesResponseTypeDef:
         """
         Returns a list of container recipes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_container_recipes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_container_recipes)
         """
+
     async def list_distribution_configurations(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListDistributionConfigurationsResponseTypeDef:
         """
         Returns a list of distribution configurations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_distribution_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_distribution_configurations)
         """
+
     async def list_image_build_versions(
         self,
         *,
         imageVersionArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImageBuildVersionsResponseTypeDef:
         """
         Returns a list of image build versions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_build_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_build_versions)
         """
+
     async def list_image_packages(
         self, *, imageBuildVersionArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListImagePackagesResponseTypeDef:
         """
         List the Packages that are associated with an Image Build Version, as determined
         by Amazon Web Services Systems Manager Inventory at build time.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_packages)
         """
+
     async def list_image_pipeline_images(
         self,
         *,
         imagePipelineArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImagePipelineImagesResponseTypeDef:
         """
         Returns a list of images created by the specified pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipeline_images)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_pipeline_images)
         """
+
     async def list_image_pipelines(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListImagePipelinesResponseTypeDef:
         """
         Returns a list of image pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_pipelines)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_pipelines)
         """
+
     async def list_image_recipes(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListImageRecipesResponseTypeDef:
         """
         Returns a list of image recipes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_recipes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_recipes)
         """
+
+    async def list_image_scan_finding_aggregations(
+        self, *, filter: FilterTypeDef = ..., nextToken: str = ...
+    ) -> ListImageScanFindingAggregationsResponseTypeDef:
+        """
+        Returns a list of image scan aggregations for your account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_scan_finding_aggregations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_scan_finding_aggregations)
+        """
+
+    async def list_image_scan_findings(
+        self,
+        *,
+        filters: Sequence[ImageScanFindingsFilterTypeDef] = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListImageScanFindingsResponseTypeDef:
+        """
+        Returns a list of image scan findings for your account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_image_scan_findings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_image_scan_findings)
+        """
+
     async def list_images(
         self,
         *,
         owner: OwnershipType = ...,
         filters: Sequence[FilterTypeDef] = ...,
         byName: bool = ...,
         maxResults: int = ...,
@@ -625,126 +726,161 @@
     ) -> ListImagesResponseTypeDef:
         """
         Returns the list of images that you have access to.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_images)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_images)
         """
+
     async def list_infrastructure_configurations(
         self, *, filters: Sequence[FilterTypeDef] = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListInfrastructureConfigurationsResponseTypeDef:
         """
         Returns a list of infrastructure configurations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_infrastructure_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_infrastructure_configurations)
         """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Returns the list of tags for the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_tags_for_resource)
         """
+
+    async def list_workflow_executions(
+        self, *, imageBuildVersionArn: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListWorkflowExecutionsResponseTypeDef:
+        """
+        Returns a list of workflow runtime instance metadata objects for a specific
+        image build version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_workflow_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_workflow_executions)
+        """
+
+    async def list_workflow_step_executions(
+        self, *, workflowExecutionId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListWorkflowStepExecutionsResponseTypeDef:
+        """
+        Shows runtime data for each step in a runtime instance of the workflow that you
+        specify in the request.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.list_workflow_step_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#list_workflow_step_executions)
+        """
+
     async def put_component_policy(
         self, *, componentArn: str, policy: str
     ) -> PutComponentPolicyResponseTypeDef:
         """
         Applies a policy to a component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_component_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_component_policy)
         """
+
     async def put_container_recipe_policy(
         self, *, containerRecipeArn: str, policy: str
     ) -> PutContainerRecipePolicyResponseTypeDef:
         """
         Applies a policy to a container image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_container_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_container_recipe_policy)
         """
+
     async def put_image_policy(
         self, *, imageArn: str, policy: str
     ) -> PutImagePolicyResponseTypeDef:
         """
         Applies a policy to an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_image_policy)
         """
+
     async def put_image_recipe_policy(
         self, *, imageRecipeArn: str, policy: str
     ) -> PutImageRecipePolicyResponseTypeDef:
         """
         Applies a policy to an image recipe.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.put_image_recipe_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#put_image_recipe_policy)
         """
+
     async def start_image_pipeline_execution(
         self, *, imagePipelineArn: str, clientToken: str
     ) -> StartImagePipelineExecutionResponseTypeDef:
         """
         Manually triggers a pipeline to create an image.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.start_image_pipeline_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#start_image_pipeline_execution)
         """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds a tag to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#tag_resource)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a tag from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#untag_resource)
         """
+
     async def update_distribution_configuration(
         self,
         *,
         distributionConfigurationArn: str,
         distributions: Sequence[DistributionTypeDef],
         clientToken: str,
         description: str = ...
     ) -> UpdateDistributionConfigurationResponseTypeDef:
         """
         Updates a new distribution configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_distribution_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_distribution_configuration)
         """
+
     async def update_image_pipeline(
         self,
         *,
         imagePipelineArn: str,
         infrastructureConfigurationArn: str,
         clientToken: str,
         description: str = ...,
         imageRecipeArn: str = ...,
         containerRecipeArn: str = ...,
         distributionConfigurationArn: str = ...,
         imageTestsConfiguration: ImageTestsConfigurationTypeDef = ...,
         enhancedImageMetadataEnabled: bool = ...,
         schedule: ScheduleTypeDef = ...,
-        status: PipelineStatusType = ...
+        status: PipelineStatusType = ...,
+        imageScanningConfiguration: ImageScanningConfigurationTypeDef = ...
     ) -> UpdateImagePipelineResponseTypeDef:
         """
         Updates an image pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_image_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_image_pipeline)
         """
+
     async def update_infrastructure_configuration(
         self,
         *,
         infrastructureConfigurationArn: str,
         instanceProfileName: str,
         clientToken: str,
         description: str = ...,
@@ -760,17 +896,19 @@
     ) -> UpdateInfrastructureConfigurationResponseTypeDef:
         """
         Updates a new infrastructure configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client.update_infrastructure_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/#update_infrastructure_configuration)
         """
+
     async def __aenter__(self) -> "imagebuilderClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/client/)
         """
```

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/literals.py` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/literals.py`

 * *Files 12% similar despite different names*

```diff
@@ -24,35 +24,43 @@
     "ComponentFormatType",
     "ComponentStatusType",
     "ComponentTypeType",
     "ContainerRepositoryServiceType",
     "ContainerTypeType",
     "DiskImageFormatType",
     "EbsVolumeTypeType",
+    "ImageScanStatusType",
     "ImageSourceType",
     "ImageStatusType",
     "ImageTypeType",
     "OwnershipType",
     "PipelineExecutionStartConditionType",
     "PipelineStatusType",
     "PlatformType",
+    "WorkflowExecutionStatusType",
+    "WorkflowStepExecutionRollbackStatusType",
+    "WorkflowStepExecutionStatusType",
+    "WorkflowTypeType",
     "imagebuilderServiceName",
     "ServiceName",
     "ResourceServiceName",
 )
 
 
 BuildTypeType = Literal["IMPORT", "SCHEDULED", "USER_INITIATED"]
 ComponentFormatType = Literal["SHELL"]
 ComponentStatusType = Literal["DEPRECATED"]
 ComponentTypeType = Literal["BUILD", "TEST"]
 ContainerRepositoryServiceType = Literal["ECR"]
 ContainerTypeType = Literal["DOCKER"]
 DiskImageFormatType = Literal["RAW", "VHD", "VMDK"]
 EbsVolumeTypeType = Literal["gp2", "gp3", "io1", "io2", "sc1", "st1", "standard"]
+ImageScanStatusType = Literal[
+    "ABANDONED", "COLLECTING", "COMPLETED", "FAILED", "PENDING", "SCANNING", "TIMED_OUT"
+]
 ImageSourceType = Literal["AMAZON_MANAGED", "AWS_MARKETPLACE", "CUSTOM", "IMPORTED"]
 ImageStatusType = Literal[
     "AVAILABLE",
     "BUILDING",
     "CANCELLED",
     "CREATING",
     "DELETED",
@@ -66,14 +74,26 @@
 ImageTypeType = Literal["AMI", "DOCKER"]
 OwnershipType = Literal["Amazon", "Self", "Shared", "ThirdParty"]
 PipelineExecutionStartConditionType = Literal[
     "EXPRESSION_MATCH_AND_DEPENDENCY_UPDATES_AVAILABLE", "EXPRESSION_MATCH_ONLY"
 ]
 PipelineStatusType = Literal["DISABLED", "ENABLED"]
 PlatformType = Literal["Linux", "Windows"]
+WorkflowExecutionStatusType = Literal[
+    "COMPLETED",
+    "FAILED",
+    "PENDING",
+    "ROLLBACK_COMPLETED",
+    "ROLLBACK_IN_PROGRESS",
+    "RUNNING",
+    "SKIPPED",
+]
+WorkflowStepExecutionRollbackStatusType = Literal["COMPLETED", "FAILED", "RUNNING", "SKIPPED"]
+WorkflowStepExecutionStatusType = Literal["COMPLETED", "FAILED", "PENDING", "RUNNING", "SKIPPED"]
+WorkflowTypeType = Literal["BUILD", "DISTRIBUTION", "TEST"]
 imagebuilderServiceName = Literal["imagebuilder"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -129,14 +149,15 @@
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
@@ -215,14 +236,15 @@
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
@@ -233,14 +255,15 @@
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
@@ -276,14 +299,15 @@
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
@@ -302,16 +326,19 @@
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
@@ -395,15 +422,17 @@
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/literals.pyi` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -23,34 +23,42 @@
     "ComponentFormatType",
     "ComponentStatusType",
     "ComponentTypeType",
     "ContainerRepositoryServiceType",
     "ContainerTypeType",
     "DiskImageFormatType",
     "EbsVolumeTypeType",
+    "ImageScanStatusType",
     "ImageSourceType",
     "ImageStatusType",
     "ImageTypeType",
     "OwnershipType",
     "PipelineExecutionStartConditionType",
     "PipelineStatusType",
     "PlatformType",
+    "WorkflowExecutionStatusType",
+    "WorkflowStepExecutionRollbackStatusType",
+    "WorkflowStepExecutionStatusType",
+    "WorkflowTypeType",
     "imagebuilderServiceName",
     "ServiceName",
     "ResourceServiceName",
 )
 
 BuildTypeType = Literal["IMPORT", "SCHEDULED", "USER_INITIATED"]
 ComponentFormatType = Literal["SHELL"]
 ComponentStatusType = Literal["DEPRECATED"]
 ComponentTypeType = Literal["BUILD", "TEST"]
 ContainerRepositoryServiceType = Literal["ECR"]
 ContainerTypeType = Literal["DOCKER"]
 DiskImageFormatType = Literal["RAW", "VHD", "VMDK"]
 EbsVolumeTypeType = Literal["gp2", "gp3", "io1", "io2", "sc1", "st1", "standard"]
+ImageScanStatusType = Literal[
+    "ABANDONED", "COLLECTING", "COMPLETED", "FAILED", "PENDING", "SCANNING", "TIMED_OUT"
+]
 ImageSourceType = Literal["AMAZON_MANAGED", "AWS_MARKETPLACE", "CUSTOM", "IMPORTED"]
 ImageStatusType = Literal[
     "AVAILABLE",
     "BUILDING",
     "CANCELLED",
     "CREATING",
     "DELETED",
@@ -64,14 +72,26 @@
 ImageTypeType = Literal["AMI", "DOCKER"]
 OwnershipType = Literal["Amazon", "Self", "Shared", "ThirdParty"]
 PipelineExecutionStartConditionType = Literal[
     "EXPRESSION_MATCH_AND_DEPENDENCY_UPDATES_AVAILABLE", "EXPRESSION_MATCH_ONLY"
 ]
 PipelineStatusType = Literal["DISABLED", "ENABLED"]
 PlatformType = Literal["Linux", "Windows"]
+WorkflowExecutionStatusType = Literal[
+    "COMPLETED",
+    "FAILED",
+    "PENDING",
+    "ROLLBACK_COMPLETED",
+    "ROLLBACK_IN_PROGRESS",
+    "RUNNING",
+    "SKIPPED",
+]
+WorkflowStepExecutionRollbackStatusType = Literal["COMPLETED", "FAILED", "RUNNING", "SKIPPED"]
+WorkflowStepExecutionStatusType = Literal["COMPLETED", "FAILED", "PENDING", "RUNNING", "SKIPPED"]
+WorkflowTypeType = Literal["BUILD", "DISTRIBUTION", "TEST"]
 imagebuilderServiceName = Literal["imagebuilder"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -127,14 +147,15 @@
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
@@ -213,14 +234,15 @@
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
@@ -231,14 +253,15 @@
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
@@ -274,14 +297,15 @@
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
@@ -300,16 +324,19 @@
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
@@ -393,15 +420,17 @@
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/type_defs.py` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -2,193 +2,243 @@
 Type annotations for imagebuilder service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_imagebuilder.type_defs import SystemsManagerAgentTypeDef
+    from types_aiobotocore_imagebuilder.type_defs import SeverityCountsTypeDef
 
-    data: SystemsManagerAgentTypeDef = {...}
+    data: SeverityCountsTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     BuildTypeType,
     ComponentTypeType,
     DiskImageFormatType,
     EbsVolumeTypeType,
+    ImageScanStatusType,
     ImageSourceType,
     ImageStatusType,
     ImageTypeType,
     OwnershipType,
     PipelineExecutionStartConditionType,
     PipelineStatusType,
     PlatformType,
+    WorkflowExecutionStatusType,
+    WorkflowStepExecutionRollbackStatusType,
+    WorkflowStepExecutionStatusType,
+    WorkflowTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
+    "SeverityCountsTypeDef",
     "SystemsManagerAgentTypeDef",
     "LaunchPermissionConfigurationTypeDef",
     "ImageStateTypeDef",
     "CancelImageCreationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelImageCreationResponseTypeDef",
     "ComponentParameterTypeDef",
     "ComponentParameterDetailTypeDef",
     "ComponentStateTypeDef",
     "ComponentVersionTypeDef",
     "TargetContainerRepositoryTypeDef",
     "ContainerRecipeSummaryTypeDef",
     "ContainerTypeDef",
     "CreateComponentRequestRequestTypeDef",
+    "CreateComponentResponseTypeDef",
+    "CreateContainerRecipeResponseTypeDef",
+    "CreateDistributionConfigurationResponseTypeDef",
     "ImageTestsConfigurationTypeDef",
     "ScheduleTypeDef",
+    "CreateImagePipelineResponseTypeDef",
+    "CreateImageRecipeResponseTypeDef",
+    "CreateImageResponseTypeDef",
     "InstanceMetadataOptionsTypeDef",
+    "CreateInfrastructureConfigurationResponseTypeDef",
+    "CvssScoreAdjustmentTypeDef",
+    "CvssScoreTypeDef",
     "DeleteComponentRequestRequestTypeDef",
+    "DeleteComponentResponseTypeDef",
     "DeleteContainerRecipeRequestRequestTypeDef",
+    "DeleteContainerRecipeResponseTypeDef",
     "DeleteDistributionConfigurationRequestRequestTypeDef",
+    "DeleteDistributionConfigurationResponseTypeDef",
     "DeleteImagePipelineRequestRequestTypeDef",
+    "DeleteImagePipelineResponseTypeDef",
     "DeleteImageRecipeRequestRequestTypeDef",
+    "DeleteImageRecipeResponseTypeDef",
     "DeleteImageRequestRequestTypeDef",
+    "DeleteImageResponseTypeDef",
     "DeleteInfrastructureConfigurationRequestRequestTypeDef",
+    "DeleteInfrastructureConfigurationResponseTypeDef",
     "DistributionConfigurationSummaryTypeDef",
     "LaunchTemplateConfigurationTypeDef",
     "S3ExportConfigurationTypeDef",
     "EbsInstanceBlockDeviceSpecificationTypeDef",
+    "EcrConfigurationTypeDef",
     "FastLaunchLaunchTemplateSpecificationTypeDef",
     "FastLaunchSnapshotConfigurationTypeDef",
     "FilterTypeDef",
     "GetComponentPolicyRequestRequestTypeDef",
+    "GetComponentPolicyResponseTypeDef",
     "GetComponentRequestRequestTypeDef",
     "GetContainerRecipePolicyRequestRequestTypeDef",
+    "GetContainerRecipePolicyResponseTypeDef",
     "GetContainerRecipeRequestRequestTypeDef",
     "GetDistributionConfigurationRequestRequestTypeDef",
     "GetImagePipelineRequestRequestTypeDef",
     "GetImagePolicyRequestRequestTypeDef",
+    "GetImagePolicyResponseTypeDef",
     "GetImageRecipePolicyRequestRequestTypeDef",
+    "GetImageRecipePolicyResponseTypeDef",
     "GetImageRecipeRequestRequestTypeDef",
     "GetImageRequestRequestTypeDef",
     "GetInfrastructureConfigurationRequestRequestTypeDef",
+    "GetWorkflowExecutionRequestRequestTypeDef",
+    "GetWorkflowExecutionResponseTypeDef",
+    "GetWorkflowStepExecutionRequestRequestTypeDef",
+    "GetWorkflowStepExecutionResponseTypeDef",
     "ImagePackageTypeDef",
     "ImageRecipeSummaryTypeDef",
+    "ImageScanFindingsFilterTypeDef",
+    "ImageScanStateTypeDef",
     "ImageVersionTypeDef",
     "ImportComponentRequestRequestTypeDef",
+    "ImportComponentResponseTypeDef",
     "ImportVmImageRequestRequestTypeDef",
+    "ImportVmImageResponseTypeDef",
     "InfrastructureConfigurationSummaryTypeDef",
     "ListComponentBuildVersionsRequestRequestTypeDef",
     "ListImagePackagesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorkflowExecutionsRequestRequestTypeDef",
+    "WorkflowExecutionMetadataTypeDef",
+    "ListWorkflowStepExecutionsRequestRequestTypeDef",
+    "WorkflowStepMetadataTypeDef",
     "S3LogsTypeDef",
+    "VulnerablePackageTypeDef",
     "PutComponentPolicyRequestRequestTypeDef",
+    "PutComponentPolicyResponseTypeDef",
     "PutContainerRecipePolicyRequestRequestTypeDef",
+    "PutContainerRecipePolicyResponseTypeDef",
     "PutImagePolicyRequestRequestTypeDef",
+    "PutImagePolicyResponseTypeDef",
     "PutImageRecipePolicyRequestRequestTypeDef",
+    "PutImageRecipePolicyResponseTypeDef",
+    "RemediationRecommendationTypeDef",
+    "ResponseMetadataTypeDef",
     "StartImagePipelineExecutionRequestRequestTypeDef",
+    "StartImagePipelineExecutionResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AdditionalInstanceConfigurationTypeDef",
-    "AmiDistributionConfigurationTypeDef",
-    "AmiTypeDef",
-    "CancelImageCreationResponseTypeDef",
-    "CreateComponentResponseTypeDef",
-    "CreateContainerRecipeResponseTypeDef",
-    "CreateDistributionConfigurationResponseTypeDef",
-    "CreateImagePipelineResponseTypeDef",
-    "CreateImageRecipeResponseTypeDef",
-    "CreateImageResponseTypeDef",
-    "CreateInfrastructureConfigurationResponseTypeDef",
-    "DeleteComponentResponseTypeDef",
-    "DeleteContainerRecipeResponseTypeDef",
-    "DeleteDistributionConfigurationResponseTypeDef",
-    "DeleteImagePipelineResponseTypeDef",
-    "DeleteImageRecipeResponseTypeDef",
-    "DeleteImageResponseTypeDef",
-    "DeleteInfrastructureConfigurationResponseTypeDef",
-    "GetComponentPolicyResponseTypeDef",
-    "GetContainerRecipePolicyResponseTypeDef",
-    "GetImagePolicyResponseTypeDef",
-    "GetImageRecipePolicyResponseTypeDef",
-    "ImportComponentResponseTypeDef",
-    "ImportVmImageResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutComponentPolicyResponseTypeDef",
-    "PutContainerRecipePolicyResponseTypeDef",
-    "PutImagePolicyResponseTypeDef",
-    "PutImageRecipePolicyResponseTypeDef",
-    "StartImagePipelineExecutionResponseTypeDef",
     "UpdateDistributionConfigurationResponseTypeDef",
     "UpdateImagePipelineResponseTypeDef",
     "UpdateInfrastructureConfigurationResponseTypeDef",
+    "AccountAggregationTypeDef",
+    "ImageAggregationTypeDef",
+    "ImagePipelineAggregationTypeDef",
+    "VulnerabilityIdAggregationTypeDef",
+    "AdditionalInstanceConfigurationTypeDef",
+    "AmiDistributionConfigurationTypeDef",
+    "AmiTypeDef",
     "ComponentConfigurationTypeDef",
     "ComponentSummaryTypeDef",
     "ComponentTypeDef",
     "ListComponentsResponseTypeDef",
     "ContainerDistributionConfigurationTypeDef",
     "ListContainerRecipesResponseTypeDef",
-    "CreateImageRequestRequestTypeDef",
-    "CreateImagePipelineRequestRequestTypeDef",
-    "ImagePipelineTypeDef",
-    "UpdateImagePipelineRequestRequestTypeDef",
+    "CvssScoreDetailsTypeDef",
     "ListDistributionConfigurationsResponseTypeDef",
     "InstanceBlockDeviceMappingTypeDef",
+    "ImageScanningConfigurationTypeDef",
     "FastLaunchConfigurationTypeDef",
     "ListComponentsRequestRequestTypeDef",
     "ListContainerRecipesRequestRequestTypeDef",
     "ListDistributionConfigurationsRequestRequestTypeDef",
     "ListImageBuildVersionsRequestRequestTypeDef",
     "ListImagePipelineImagesRequestRequestTypeDef",
     "ListImagePipelinesRequestRequestTypeDef",
     "ListImageRecipesRequestRequestTypeDef",
+    "ListImageScanFindingAggregationsRequestRequestTypeDef",
     "ListImagesRequestRequestTypeDef",
     "ListInfrastructureConfigurationsRequestRequestTypeDef",
     "ListImagePackagesResponseTypeDef",
     "ListImageRecipesResponseTypeDef",
+    "ListImageScanFindingsRequestRequestTypeDef",
     "ListImagesResponseTypeDef",
     "ListInfrastructureConfigurationsResponseTypeDef",
+    "ListWorkflowExecutionsResponseTypeDef",
+    "ListWorkflowStepExecutionsResponseTypeDef",
     "LoggingTypeDef",
+    "PackageVulnerabilityDetailsTypeDef",
+    "RemediationTypeDef",
+    "ImageScanFindingAggregationTypeDef",
     "OutputResourcesTypeDef",
     "ListComponentBuildVersionsResponseTypeDef",
     "GetComponentResponseTypeDef",
-    "GetImagePipelineResponseTypeDef",
-    "ListImagePipelinesResponseTypeDef",
+    "InspectorScoreDetailsTypeDef",
     "CreateImageRecipeRequestRequestTypeDef",
     "ImageRecipeTypeDef",
     "InstanceConfigurationTypeDef",
+    "CreateImagePipelineRequestRequestTypeDef",
+    "CreateImageRequestRequestTypeDef",
+    "ImagePipelineTypeDef",
+    "UpdateImagePipelineRequestRequestTypeDef",
     "DistributionTypeDef",
     "CreateInfrastructureConfigurationRequestRequestTypeDef",
     "InfrastructureConfigurationTypeDef",
     "UpdateInfrastructureConfigurationRequestRequestTypeDef",
+    "ListImageScanFindingAggregationsResponseTypeDef",
     "ImageSummaryTypeDef",
+    "ImageScanFindingTypeDef",
     "GetImageRecipeResponseTypeDef",
     "ContainerRecipeTypeDef",
     "CreateContainerRecipeRequestRequestTypeDef",
+    "GetImagePipelineResponseTypeDef",
+    "ListImagePipelinesResponseTypeDef",
     "CreateDistributionConfigurationRequestRequestTypeDef",
     "DistributionConfigurationTypeDef",
     "UpdateDistributionConfigurationRequestRequestTypeDef",
     "GetInfrastructureConfigurationResponseTypeDef",
     "ListImageBuildVersionsResponseTypeDef",
     "ListImagePipelineImagesResponseTypeDef",
+    "ListImageScanFindingsResponseTypeDef",
     "GetContainerRecipeResponseTypeDef",
     "GetDistributionConfigurationResponseTypeDef",
     "ImageTypeDef",
     "GetImageResponseTypeDef",
 )
 
+SeverityCountsTypeDef = TypedDict(
+    "SeverityCountsTypeDef",
+    {
+        "all": int,
+        "critical": int,
+        "high": int,
+        "medium": int,
+    },
+    total=False,
+)
+
 SystemsManagerAgentTypeDef = TypedDict(
     "SystemsManagerAgentTypeDef",
     {
         "uninstallAfterBuild": bool,
     },
     total=False,
 )
@@ -217,22 +267,21 @@
     "CancelImageCreationRequestRequestTypeDef",
     {
         "imageBuildVersionArn": str,
         "clientToken": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelImageCreationResponseTypeDef = TypedDict(
+    "CancelImageCreationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "requestId": str,
+        "clientToken": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentParameterTypeDef = TypedDict(
     "ComponentParameterTypeDef",
     {
         "name": str,
@@ -346,14 +395,44 @@
 
 class CreateComponentRequestRequestTypeDef(
     _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
 ):
     pass
 
 
+CreateComponentResponseTypeDef = TypedDict(
+    "CreateComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateContainerRecipeResponseTypeDef = TypedDict(
+    "CreateContainerRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDistributionConfigurationResponseTypeDef = TypedDict(
+    "CreateDistributionConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageTestsConfigurationTypeDef = TypedDict(
     "ImageTestsConfigurationTypeDef",
     {
         "imageTestsEnabled": bool,
         "timeoutMinutes": int,
     },
     total=False,
@@ -365,72 +444,195 @@
         "scheduleExpression": str,
         "timezone": str,
         "pipelineExecutionStartCondition": PipelineExecutionStartConditionType,
     },
     total=False,
 )
 
+CreateImagePipelineResponseTypeDef = TypedDict(
+    "CreateImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateImageRecipeResponseTypeDef = TypedDict(
+    "CreateImageRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateImageResponseTypeDef = TypedDict(
+    "CreateImageResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstanceMetadataOptionsTypeDef = TypedDict(
     "InstanceMetadataOptionsTypeDef",
     {
         "httpTokens": str,
         "httpPutResponseHopLimit": int,
     },
     total=False,
 )
 
+CreateInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "CreateInfrastructureConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CvssScoreAdjustmentTypeDef = TypedDict(
+    "CvssScoreAdjustmentTypeDef",
+    {
+        "metric": str,
+        "reason": str,
+    },
+    total=False,
+)
+
+CvssScoreTypeDef = TypedDict(
+    "CvssScoreTypeDef",
+    {
+        "baseScore": float,
+        "scoringVector": str,
+        "version": str,
+        "source": str,
+    },
+    total=False,
+)
+
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "componentBuildVersionArn": str,
     },
 )
 
+DeleteComponentResponseTypeDef = TypedDict(
+    "DeleteComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteContainerRecipeRequestRequestTypeDef = TypedDict(
     "DeleteContainerRecipeRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
+DeleteContainerRecipeResponseTypeDef = TypedDict(
+    "DeleteContainerRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDistributionConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteDistributionConfigurationRequestRequestTypeDef",
     {
         "distributionConfigurationArn": str,
     },
 )
 
+DeleteDistributionConfigurationResponseTypeDef = TypedDict(
+    "DeleteDistributionConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImagePipelineRequestRequestTypeDef = TypedDict(
     "DeleteImagePipelineRequestRequestTypeDef",
     {
         "imagePipelineArn": str,
     },
 )
 
+DeleteImagePipelineResponseTypeDef = TypedDict(
+    "DeleteImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImageRecipeRequestRequestTypeDef = TypedDict(
     "DeleteImageRecipeRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
+DeleteImageRecipeResponseTypeDef = TypedDict(
+    "DeleteImageRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImageRequestRequestTypeDef = TypedDict(
     "DeleteImageRequestRequestTypeDef",
     {
         "imageBuildVersionArn": str,
     },
 )
 
+DeleteImageResponseTypeDef = TypedDict(
+    "DeleteImageResponseTypeDef",
+    {
+        "requestId": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteInfrastructureConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteInfrastructureConfigurationRequestRequestTypeDef",
     {
         "infrastructureConfigurationArn": str,
     },
 )
 
+DeleteInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "DeleteInfrastructureConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DistributionConfigurationSummaryTypeDef = TypedDict(
     "DistributionConfigurationSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "description": str,
         "dateCreated": str,
@@ -497,14 +699,23 @@
         "volumeSize": int,
         "volumeType": EbsVolumeTypeType,
         "throughput": int,
     },
     total=False,
 )
 
+EcrConfigurationTypeDef = TypedDict(
+    "EcrConfigurationTypeDef",
+    {
+        "repositoryName": str,
+        "containerTags": Sequence[str],
+    },
+    total=False,
+)
+
 FastLaunchLaunchTemplateSpecificationTypeDef = TypedDict(
     "FastLaunchLaunchTemplateSpecificationTypeDef",
     {
         "launchTemplateId": str,
         "launchTemplateName": str,
         "launchTemplateVersion": str,
     },
@@ -531,28 +742,46 @@
 GetComponentPolicyRequestRequestTypeDef = TypedDict(
     "GetComponentPolicyRequestRequestTypeDef",
     {
         "componentArn": str,
     },
 )
 
+GetComponentPolicyResponseTypeDef = TypedDict(
+    "GetComponentPolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetComponentRequestRequestTypeDef = TypedDict(
     "GetComponentRequestRequestTypeDef",
     {
         "componentBuildVersionArn": str,
     },
 )
 
 GetContainerRecipePolicyRequestRequestTypeDef = TypedDict(
     "GetContainerRecipePolicyRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
+GetContainerRecipePolicyResponseTypeDef = TypedDict(
+    "GetContainerRecipePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContainerRecipeRequestRequestTypeDef = TypedDict(
     "GetContainerRecipeRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
@@ -573,21 +802,39 @@
 GetImagePolicyRequestRequestTypeDef = TypedDict(
     "GetImagePolicyRequestRequestTypeDef",
     {
         "imageArn": str,
     },
 )
 
+GetImagePolicyResponseTypeDef = TypedDict(
+    "GetImagePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImageRecipePolicyRequestRequestTypeDef = TypedDict(
     "GetImageRecipePolicyRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
+GetImageRecipePolicyResponseTypeDef = TypedDict(
+    "GetImageRecipePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImageRecipeRequestRequestTypeDef = TypedDict(
     "GetImageRecipeRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
@@ -601,14 +848,72 @@
 GetInfrastructureConfigurationRequestRequestTypeDef = TypedDict(
     "GetInfrastructureConfigurationRequestRequestTypeDef",
     {
         "infrastructureConfigurationArn": str,
     },
 )
 
+GetWorkflowExecutionRequestRequestTypeDef = TypedDict(
+    "GetWorkflowExecutionRequestRequestTypeDef",
+    {
+        "workflowExecutionId": str,
+    },
+)
+
+GetWorkflowExecutionResponseTypeDef = TypedDict(
+    "GetWorkflowExecutionResponseTypeDef",
+    {
+        "requestId": str,
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "type": WorkflowTypeType,
+        "status": WorkflowExecutionStatusType,
+        "message": str,
+        "totalStepCount": int,
+        "totalStepsSucceeded": int,
+        "totalStepsFailed": int,
+        "totalStepsSkipped": int,
+        "startTime": str,
+        "endTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetWorkflowStepExecutionRequestRequestTypeDef = TypedDict(
+    "GetWorkflowStepExecutionRequestRequestTypeDef",
+    {
+        "stepExecutionId": str,
+    },
+)
+
+GetWorkflowStepExecutionResponseTypeDef = TypedDict(
+    "GetWorkflowStepExecutionResponseTypeDef",
+    {
+        "requestId": str,
+        "stepExecutionId": str,
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "name": str,
+        "description": str,
+        "action": str,
+        "status": WorkflowStepExecutionStatusType,
+        "rollbackStatus": WorkflowStepExecutionRollbackStatusType,
+        "message": str,
+        "inputs": str,
+        "outputs": str,
+        "startTime": str,
+        "endTime": str,
+        "onFailure": str,
+        "timeoutSeconds": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImagePackageTypeDef = TypedDict(
     "ImagePackageTypeDef",
     {
         "packageName": str,
         "packageVersion": str,
     },
     total=False,
@@ -624,14 +929,32 @@
         "parentImage": str,
         "dateCreated": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ImageScanFindingsFilterTypeDef = TypedDict(
+    "ImageScanFindingsFilterTypeDef",
+    {
+        "name": str,
+        "values": Sequence[str],
+    },
+    total=False,
+)
+
+ImageScanStateTypeDef = TypedDict(
+    "ImageScanStateTypeDef",
+    {
+        "status": ImageScanStatusType,
+        "reason": str,
+    },
+    total=False,
+)
+
 ImageVersionTypeDef = TypedDict(
     "ImageVersionTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ImageTypeType,
         "version": str,
@@ -672,14 +995,24 @@
 
 class ImportComponentRequestRequestTypeDef(
     _RequiredImportComponentRequestRequestTypeDef, _OptionalImportComponentRequestRequestTypeDef
 ):
     pass
 
 
+ImportComponentResponseTypeDef = TypedDict(
+    "ImportComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportVmImageRequestRequestTypeDef = TypedDict(
     "_RequiredImportVmImageRequestRequestTypeDef",
     {
         "name": str,
         "semanticVersion": str,
         "platform": PlatformType,
         "vmImportTaskId": str,
@@ -699,14 +1032,24 @@
 
 class ImportVmImageRequestRequestTypeDef(
     _RequiredImportVmImageRequestRequestTypeDef, _OptionalImportVmImageRequestRequestTypeDef
 ):
     pass
 
 
+ImportVmImageResponseTypeDef = TypedDict(
+    "ImportVmImageResponseTypeDef",
+    {
+        "requestId": str,
+        "imageArn": str,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InfrastructureConfigurationSummaryTypeDef = TypedDict(
     "InfrastructureConfigurationSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "description": str,
         "dateCreated": str,
@@ -767,395 +1110,351 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
-S3LogsTypeDef = TypedDict(
-    "S3LogsTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "s3BucketName": str,
-        "s3KeyPrefix": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-PutComponentPolicyRequestRequestTypeDef = TypedDict(
-    "PutComponentPolicyRequestRequestTypeDef",
+_RequiredListWorkflowExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWorkflowExecutionsRequestRequestTypeDef",
     {
-        "componentArn": str,
-        "policy": str,
+        "imageBuildVersionArn": str,
     },
 )
-
-PutContainerRecipePolicyRequestRequestTypeDef = TypedDict(
-    "PutContainerRecipePolicyRequestRequestTypeDef",
+_OptionalListWorkflowExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWorkflowExecutionsRequestRequestTypeDef",
     {
-        "containerRecipeArn": str,
-        "policy": str,
+        "maxResults": int,
+        "nextToken": str,
     },
+    total=False,
 )
 
-PutImagePolicyRequestRequestTypeDef = TypedDict(
-    "PutImagePolicyRequestRequestTypeDef",
-    {
-        "imageArn": str,
-        "policy": str,
-    },
-)
 
-PutImageRecipePolicyRequestRequestTypeDef = TypedDict(
-    "PutImageRecipePolicyRequestRequestTypeDef",
-    {
-        "imageRecipeArn": str,
-        "policy": str,
-    },
-)
+class ListWorkflowExecutionsRequestRequestTypeDef(
+    _RequiredListWorkflowExecutionsRequestRequestTypeDef,
+    _OptionalListWorkflowExecutionsRequestRequestTypeDef,
+):
+    pass
 
-StartImagePipelineExecutionRequestRequestTypeDef = TypedDict(
-    "StartImagePipelineExecutionRequestRequestTypeDef",
-    {
-        "imagePipelineArn": str,
-        "clientToken": str,
-    },
-)
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+WorkflowExecutionMetadataTypeDef = TypedDict(
+    "WorkflowExecutionMetadataTypeDef",
     {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "type": WorkflowTypeType,
+        "status": WorkflowExecutionStatusType,
+        "message": str,
+        "totalStepCount": int,
+        "totalStepsSucceeded": int,
+        "totalStepsFailed": int,
+        "totalStepsSkipped": int,
+        "startTime": str,
+        "endTime": str,
     },
+    total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+_RequiredListWorkflowStepExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWorkflowStepExecutionsRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
+        "workflowExecutionId": str,
     },
 )
-
-AdditionalInstanceConfigurationTypeDef = TypedDict(
-    "AdditionalInstanceConfigurationTypeDef",
+_OptionalListWorkflowStepExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWorkflowStepExecutionsRequestRequestTypeDef",
     {
-        "systemsManagerAgent": SystemsManagerAgentTypeDef,
-        "userDataOverride": str,
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
-AmiDistributionConfigurationTypeDef = TypedDict(
-    "AmiDistributionConfigurationTypeDef",
+
+class ListWorkflowStepExecutionsRequestRequestTypeDef(
+    _RequiredListWorkflowStepExecutionsRequestRequestTypeDef,
+    _OptionalListWorkflowStepExecutionsRequestRequestTypeDef,
+):
+    pass
+
+
+WorkflowStepMetadataTypeDef = TypedDict(
+    "WorkflowStepMetadataTypeDef",
     {
+        "stepExecutionId": str,
         "name": str,
         "description": str,
-        "targetAccountIds": Sequence[str],
-        "amiTags": Mapping[str, str],
-        "kmsKeyId": str,
-        "launchPermission": LaunchPermissionConfigurationTypeDef,
+        "action": str,
+        "status": WorkflowStepExecutionStatusType,
+        "rollbackStatus": WorkflowStepExecutionRollbackStatusType,
+        "message": str,
+        "inputs": str,
+        "outputs": str,
+        "startTime": str,
+        "endTime": str,
     },
     total=False,
 )
 
-AmiTypeDef = TypedDict(
-    "AmiTypeDef",
+S3LogsTypeDef = TypedDict(
+    "S3LogsTypeDef",
     {
-        "region": str,
-        "image": str,
-        "name": str,
-        "description": str,
-        "state": ImageStateTypeDef,
-        "accountId": str,
+        "s3BucketName": str,
+        "s3KeyPrefix": str,
     },
     total=False,
 )
 
-CancelImageCreationResponseTypeDef = TypedDict(
-    "CancelImageCreationResponseTypeDef",
+VulnerablePackageTypeDef = TypedDict(
+    "VulnerablePackageTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
+        "version": str,
+        "sourceLayerHash": str,
+        "epoch": int,
+        "release": str,
+        "arch": str,
+        "packageManager": str,
+        "filePath": str,
+        "fixedInVersion": str,
+        "remediation": str,
     },
+    total=False,
 )
 
-CreateComponentResponseTypeDef = TypedDict(
-    "CreateComponentResponseTypeDef",
+PutComponentPolicyRequestRequestTypeDef = TypedDict(
+    "PutComponentPolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "componentArn": str,
+        "policy": str,
     },
 )
 
-CreateContainerRecipeResponseTypeDef = TypedDict(
-    "CreateContainerRecipeResponseTypeDef",
+PutComponentPolicyResponseTypeDef = TypedDict(
+    "PutComponentPolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "componentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateDistributionConfigurationResponseTypeDef = TypedDict(
-    "CreateDistributionConfigurationResponseTypeDef",
+PutContainerRecipePolicyRequestRequestTypeDef = TypedDict(
+    "PutContainerRecipePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "containerRecipeArn": str,
+        "policy": str,
     },
 )
 
-CreateImagePipelineResponseTypeDef = TypedDict(
-    "CreateImagePipelineResponseTypeDef",
+PutContainerRecipePolicyResponseTypeDef = TypedDict(
+    "PutContainerRecipePolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateImageRecipeResponseTypeDef = TypedDict(
-    "CreateImageRecipeResponseTypeDef",
+PutImagePolicyRequestRequestTypeDef = TypedDict(
+    "PutImagePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageArn": str,
+        "policy": str,
     },
 )
 
-CreateImageResponseTypeDef = TypedDict(
-    "CreateImageResponseTypeDef",
+PutImagePolicyResponseTypeDef = TypedDict(
+    "PutImagePolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "CreateInfrastructureConfigurationResponseTypeDef",
+PutImageRecipePolicyRequestRequestTypeDef = TypedDict(
+    "PutImageRecipePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageRecipeArn": str,
+        "policy": str,
     },
 )
 
-DeleteComponentResponseTypeDef = TypedDict(
-    "DeleteComponentResponseTypeDef",
+PutImageRecipePolicyResponseTypeDef = TypedDict(
+    "PutImageRecipePolicyResponseTypeDef",
     {
         "requestId": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteContainerRecipeResponseTypeDef = TypedDict(
-    "DeleteContainerRecipeResponseTypeDef",
+RemediationRecommendationTypeDef = TypedDict(
+    "RemediationRecommendationTypeDef",
     {
-        "requestId": str,
-        "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "text": str,
+        "url": str,
     },
+    total=False,
 )
 
-DeleteDistributionConfigurationResponseTypeDef = TypedDict(
-    "DeleteDistributionConfigurationResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "requestId": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DeleteImagePipelineResponseTypeDef = TypedDict(
-    "DeleteImagePipelineResponseTypeDef",
+StartImagePipelineExecutionRequestRequestTypeDef = TypedDict(
+    "StartImagePipelineExecutionRequestRequestTypeDef",
     {
-        "requestId": str,
         "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteImageRecipeResponseTypeDef = TypedDict(
-    "DeleteImageRecipeResponseTypeDef",
-    {
-        "requestId": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientToken": str,
     },
 )
 
-DeleteImageResponseTypeDef = TypedDict(
-    "DeleteImageResponseTypeDef",
+StartImagePipelineExecutionResponseTypeDef = TypedDict(
+    "StartImagePipelineExecutionResponseTypeDef",
     {
         "requestId": str,
+        "clientToken": str,
         "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "DeleteInfrastructureConfigurationResponseTypeDef",
-    {
-        "requestId": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComponentPolicyResponseTypeDef = TypedDict(
-    "GetComponentPolicyResponseTypeDef",
-    {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContainerRecipePolicyResponseTypeDef = TypedDict(
-    "GetContainerRecipePolicyResponseTypeDef",
-    {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImagePolicyResponseTypeDef = TypedDict(
-    "GetImagePolicyResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-GetImageRecipePolicyResponseTypeDef = TypedDict(
-    "GetImageRecipePolicyResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-ImportComponentResponseTypeDef = TypedDict(
-    "ImportComponentResponseTypeDef",
+UpdateDistributionConfigurationResponseTypeDef = TypedDict(
+    "UpdateDistributionConfigurationResponseTypeDef",
     {
         "requestId": str,
         "clientToken": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ImportVmImageResponseTypeDef = TypedDict(
-    "ImportVmImageResponseTypeDef",
+UpdateImagePipelineResponseTypeDef = TypedDict(
+    "UpdateImagePipelineResponseTypeDef",
     {
         "requestId": str,
-        "imageArn": str,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutComponentPolicyResponseTypeDef = TypedDict(
-    "PutComponentPolicyResponseTypeDef",
+UpdateInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "UpdateInfrastructureConfigurationResponseTypeDef",
     {
         "requestId": str,
-        "componentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientToken": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutContainerRecipePolicyResponseTypeDef = TypedDict(
-    "PutContainerRecipePolicyResponseTypeDef",
+AccountAggregationTypeDef = TypedDict(
+    "AccountAggregationTypeDef",
     {
-        "requestId": str,
-        "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accountId": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-PutImagePolicyResponseTypeDef = TypedDict(
-    "PutImagePolicyResponseTypeDef",
+ImageAggregationTypeDef = TypedDict(
+    "ImageAggregationTypeDef",
     {
-        "requestId": str,
-        "imageArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageBuildVersionArn": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-PutImageRecipePolicyResponseTypeDef = TypedDict(
-    "PutImageRecipePolicyResponseTypeDef",
+ImagePipelineAggregationTypeDef = TypedDict(
+    "ImagePipelineAggregationTypeDef",
     {
-        "requestId": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imagePipelineArn": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-StartImagePipelineExecutionResponseTypeDef = TypedDict(
-    "StartImagePipelineExecutionResponseTypeDef",
+VulnerabilityIdAggregationTypeDef = TypedDict(
+    "VulnerabilityIdAggregationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "vulnerabilityId": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-UpdateDistributionConfigurationResponseTypeDef = TypedDict(
-    "UpdateDistributionConfigurationResponseTypeDef",
+AdditionalInstanceConfigurationTypeDef = TypedDict(
+    "AdditionalInstanceConfigurationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "systemsManagerAgent": SystemsManagerAgentTypeDef,
+        "userDataOverride": str,
     },
+    total=False,
 )
 
-UpdateImagePipelineResponseTypeDef = TypedDict(
-    "UpdateImagePipelineResponseTypeDef",
+AmiDistributionConfigurationTypeDef = TypedDict(
+    "AmiDistributionConfigurationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
+        "description": str,
+        "targetAccountIds": Sequence[str],
+        "amiTags": Mapping[str, str],
+        "kmsKeyId": str,
+        "launchPermission": LaunchPermissionConfigurationTypeDef,
     },
+    total=False,
 )
 
-UpdateInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "UpdateInfrastructureConfigurationResponseTypeDef",
+AmiTypeDef = TypedDict(
+    "AmiTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "region": str,
+        "image": str,
+        "name": str,
+        "description": str,
+        "state": ImageStateTypeDef,
+        "accountId": str,
     },
+    total=False,
 )
 
 _RequiredComponentConfigurationTypeDef = TypedDict(
     "_RequiredComponentConfigurationTypeDef",
     {
         "componentArn": str,
     },
@@ -1223,15 +1522,15 @@
 
 ListComponentsResponseTypeDef = TypedDict(
     "ListComponentsResponseTypeDef",
     {
         "requestId": str,
         "componentVersionList": List[ComponentVersionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContainerDistributionConfigurationTypeDef = TypedDict(
     "_RequiredContainerDistributionConfigurationTypeDef",
     {
         "targetRepository": TargetContainerRepositoryTypeDef,
@@ -1256,153 +1555,61 @@
 
 ListContainerRecipesResponseTypeDef = TypedDict(
     "ListContainerRecipesResponseTypeDef",
     {
         "requestId": str,
         "containerRecipeSummaryList": List[ContainerRecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateImageRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateImageRequestRequestTypeDef",
-    {
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalCreateImageRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateImageRequestRequestTypeDef",
-    {
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "tags": Mapping[str, str],
-    },
-    total=False,
-)
-
-
-class CreateImageRequestRequestTypeDef(
-    _RequiredCreateImageRequestRequestTypeDef, _OptionalCreateImageRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredCreateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateImagePipelineRequestRequestTypeDef",
-    {
-        "name": str,
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalCreateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateImagePipelineRequestRequestTypeDef",
-    {
-        "description": str,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
-        "tags": Mapping[str, str],
-    },
-    total=False,
-)
-
-
-class CreateImagePipelineRequestRequestTypeDef(
-    _RequiredCreateImagePipelineRequestRequestTypeDef,
-    _OptionalCreateImagePipelineRequestRequestTypeDef,
-):
-    pass
-
-
-ImagePipelineTypeDef = TypedDict(
-    "ImagePipelineTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "description": str,
-        "platform": PlatformType,
-        "enhancedImageMetadataEnabled": bool,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "infrastructureConfigurationArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
-        "dateCreated": str,
-        "dateUpdated": str,
-        "dateLastRun": str,
-        "dateNextRun": str,
-        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredUpdateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateImagePipelineRequestRequestTypeDef",
+CvssScoreDetailsTypeDef = TypedDict(
+    "CvssScoreDetailsTypeDef",
     {
-        "imagePipelineArn": str,
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalUpdateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateImagePipelineRequestRequestTypeDef",
-    {
-        "description": str,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
+        "scoreSource": str,
+        "cvssSource": str,
+        "version": str,
+        "score": float,
+        "scoringVector": str,
+        "adjustments": List[CvssScoreAdjustmentTypeDef],
     },
     total=False,
 )
 
-
-class UpdateImagePipelineRequestRequestTypeDef(
-    _RequiredUpdateImagePipelineRequestRequestTypeDef,
-    _OptionalUpdateImagePipelineRequestRequestTypeDef,
-):
-    pass
-
-
 ListDistributionConfigurationsResponseTypeDef = TypedDict(
     "ListDistributionConfigurationsResponseTypeDef",
     {
         "requestId": str,
         "distributionConfigurationSummaryList": List[DistributionConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceBlockDeviceMappingTypeDef = TypedDict(
     "InstanceBlockDeviceMappingTypeDef",
     {
         "deviceName": str,
         "ebs": EbsInstanceBlockDeviceSpecificationTypeDef,
         "virtualName": str,
         "noDevice": str,
     },
     total=False,
 )
 
+ImageScanningConfigurationTypeDef = TypedDict(
+    "ImageScanningConfigurationTypeDef",
+    {
+        "imageScanningEnabled": bool,
+        "ecrConfiguration": EcrConfigurationTypeDef,
+    },
+    total=False,
+)
+
 _RequiredFastLaunchConfigurationTypeDef = TypedDict(
     "_RequiredFastLaunchConfigurationTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalFastLaunchConfigurationTypeDef = TypedDict(
@@ -1521,14 +1728,23 @@
         "filters": Sequence[FilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListImageScanFindingAggregationsRequestRequestTypeDef = TypedDict(
+    "ListImageScanFindingAggregationsRequestRequestTypeDef",
+    {
+        "filter": FilterTypeDef,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListImagesRequestRequestTypeDef = TypedDict(
     "ListImagesRequestRequestTypeDef",
     {
         "owner": OwnershipType,
         "filters": Sequence[FilterTypeDef],
         "byName": bool,
         "maxResults": int,
@@ -1550,56 +1766,140 @@
 
 ListImagePackagesResponseTypeDef = TypedDict(
     "ListImagePackagesResponseTypeDef",
     {
         "requestId": str,
         "imagePackageList": List[ImagePackageTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImageRecipesResponseTypeDef = TypedDict(
     "ListImageRecipesResponseTypeDef",
     {
         "requestId": str,
         "imageRecipeSummaryList": List[ImageRecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListImageScanFindingsRequestRequestTypeDef = TypedDict(
+    "ListImageScanFindingsRequestRequestTypeDef",
+    {
+        "filters": Sequence[ImageScanFindingsFilterTypeDef],
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListImagesResponseTypeDef = TypedDict(
     "ListImagesResponseTypeDef",
     {
         "requestId": str,
         "imageVersionList": List[ImageVersionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInfrastructureConfigurationsResponseTypeDef = TypedDict(
     "ListInfrastructureConfigurationsResponseTypeDef",
     {
         "requestId": str,
         "infrastructureConfigurationSummaryList": List[InfrastructureConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkflowExecutionsResponseTypeDef = TypedDict(
+    "ListWorkflowExecutionsResponseTypeDef",
+    {
+        "requestId": str,
+        "workflowExecutions": List[WorkflowExecutionMetadataTypeDef],
+        "imageBuildVersionArn": str,
+        "message": str,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkflowStepExecutionsResponseTypeDef = TypedDict(
+    "ListWorkflowStepExecutionsResponseTypeDef",
+    {
+        "requestId": str,
+        "steps": List[WorkflowStepMetadataTypeDef],
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "message": str,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingTypeDef = TypedDict(
     "LoggingTypeDef",
     {
         "s3Logs": S3LogsTypeDef,
     },
     total=False,
 )
 
+_RequiredPackageVulnerabilityDetailsTypeDef = TypedDict(
+    "_RequiredPackageVulnerabilityDetailsTypeDef",
+    {
+        "vulnerabilityId": str,
+    },
+)
+_OptionalPackageVulnerabilityDetailsTypeDef = TypedDict(
+    "_OptionalPackageVulnerabilityDetailsTypeDef",
+    {
+        "vulnerablePackages": List[VulnerablePackageTypeDef],
+        "source": str,
+        "cvss": List[CvssScoreTypeDef],
+        "relatedVulnerabilities": List[str],
+        "sourceUrl": str,
+        "vendorSeverity": str,
+        "vendorCreatedAt": datetime,
+        "vendorUpdatedAt": datetime,
+        "referenceUrls": List[str],
+    },
+    total=False,
+)
+
+
+class PackageVulnerabilityDetailsTypeDef(
+    _RequiredPackageVulnerabilityDetailsTypeDef, _OptionalPackageVulnerabilityDetailsTypeDef
+):
+    pass
+
+
+RemediationTypeDef = TypedDict(
+    "RemediationTypeDef",
+    {
+        "recommendation": RemediationRecommendationTypeDef,
+    },
+    total=False,
+)
+
+ImageScanFindingAggregationTypeDef = TypedDict(
+    "ImageScanFindingAggregationTypeDef",
+    {
+        "accountAggregation": AccountAggregationTypeDef,
+        "imageAggregation": ImageAggregationTypeDef,
+        "imagePipelineAggregation": ImagePipelineAggregationTypeDef,
+        "vulnerabilityIdAggregation": VulnerabilityIdAggregationTypeDef,
+    },
+    total=False,
+)
+
 OutputResourcesTypeDef = TypedDict(
     "OutputResourcesTypeDef",
     {
         "amis": List[AmiTypeDef],
         "containers": List[ContainerTypeDef],
     },
     total=False,
@@ -1607,44 +1907,33 @@
 
 ListComponentBuildVersionsResponseTypeDef = TypedDict(
     "ListComponentBuildVersionsResponseTypeDef",
     {
         "requestId": str,
         "componentSummaryList": List[ComponentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentResponseTypeDef = TypedDict(
     "GetComponentResponseTypeDef",
     {
         "requestId": str,
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImagePipelineResponseTypeDef = TypedDict(
-    "GetImagePipelineResponseTypeDef",
-    {
-        "requestId": str,
-        "imagePipeline": ImagePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListImagePipelinesResponseTypeDef = TypedDict(
-    "ListImagePipelinesResponseTypeDef",
+InspectorScoreDetailsTypeDef = TypedDict(
+    "InspectorScoreDetailsTypeDef",
     {
-        "requestId": str,
-        "imagePipelineList": List[ImagePipelineTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "adjustedCvss": CvssScoreDetailsTypeDef,
     },
+    total=False,
 )
 
 _RequiredCreateImageRecipeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateImageRecipeRequestRequestTypeDef",
     {
         "name": str,
         "semanticVersion": str,
@@ -1698,14 +1987,132 @@
     {
         "image": str,
         "blockDeviceMappings": Sequence[InstanceBlockDeviceMappingTypeDef],
     },
     total=False,
 )
 
+_RequiredCreateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateImagePipelineRequestRequestTypeDef",
+    {
+        "name": str,
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalCreateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateImagePipelineRequestRequestTypeDef",
+    {
+        "description": str,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "tags": Mapping[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateImagePipelineRequestRequestTypeDef(
+    _RequiredCreateImagePipelineRequestRequestTypeDef,
+    _OptionalCreateImagePipelineRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredCreateImageRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateImageRequestRequestTypeDef",
+    {
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalCreateImageRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateImageRequestRequestTypeDef",
+    {
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "tags": Mapping[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateImageRequestRequestTypeDef(
+    _RequiredCreateImageRequestRequestTypeDef, _OptionalCreateImageRequestRequestTypeDef
+):
+    pass
+
+
+ImagePipelineTypeDef = TypedDict(
+    "ImagePipelineTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "description": str,
+        "platform": PlatformType,
+        "enhancedImageMetadataEnabled": bool,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "infrastructureConfigurationArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "dateCreated": str,
+        "dateUpdated": str,
+        "dateLastRun": str,
+        "dateNextRun": str,
+        "tags": Dict[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+_RequiredUpdateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateImagePipelineRequestRequestTypeDef",
+    {
+        "imagePipelineArn": str,
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalUpdateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateImagePipelineRequestRequestTypeDef",
+    {
+        "description": str,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateImagePipelineRequestRequestTypeDef(
+    _RequiredUpdateImagePipelineRequestRequestTypeDef,
+    _OptionalUpdateImagePipelineRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredDistributionTypeDef = TypedDict(
     "_RequiredDistributionTypeDef",
     {
         "region": str,
     },
 )
 _OptionalDistributionTypeDef = TypedDict(
@@ -1812,14 +2219,25 @@
 class UpdateInfrastructureConfigurationRequestRequestTypeDef(
     _RequiredUpdateInfrastructureConfigurationRequestRequestTypeDef,
     _OptionalUpdateInfrastructureConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
+ListImageScanFindingAggregationsResponseTypeDef = TypedDict(
+    "ListImageScanFindingAggregationsResponseTypeDef",
+    {
+        "requestId": str,
+        "aggregationType": str,
+        "responses": List[ImageScanFindingAggregationTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageSummaryTypeDef = TypedDict(
     "ImageSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ImageTypeType,
         "version": str,
@@ -1832,20 +2250,41 @@
         "tags": Dict[str, str],
         "buildType": BuildTypeType,
         "imageSource": ImageSourceType,
     },
     total=False,
 )
 
+ImageScanFindingTypeDef = TypedDict(
+    "ImageScanFindingTypeDef",
+    {
+        "awsAccountId": str,
+        "imageBuildVersionArn": str,
+        "imagePipelineArn": str,
+        "type": str,
+        "description": str,
+        "title": str,
+        "remediation": RemediationTypeDef,
+        "severity": str,
+        "firstObservedAt": datetime,
+        "updatedAt": datetime,
+        "inspectorScore": float,
+        "inspectorScoreDetails": InspectorScoreDetailsTypeDef,
+        "packageVulnerabilityDetails": PackageVulnerabilityDetailsTypeDef,
+        "fixAvailable": str,
+    },
+    total=False,
+)
+
 GetImageRecipeResponseTypeDef = TypedDict(
     "GetImageRecipeResponseTypeDef",
     {
         "requestId": str,
         "imageRecipe": ImageRecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerRecipeTypeDef = TypedDict(
     "ContainerRecipeTypeDef",
     {
         "arn": str,
@@ -1901,14 +2340,33 @@
 class CreateContainerRecipeRequestRequestTypeDef(
     _RequiredCreateContainerRecipeRequestRequestTypeDef,
     _OptionalCreateContainerRecipeRequestRequestTypeDef,
 ):
     pass
 
 
+GetImagePipelineResponseTypeDef = TypedDict(
+    "GetImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipeline": ImagePipelineTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImagePipelinesResponseTypeDef = TypedDict(
+    "ListImagePipelinesResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipelineList": List[ImagePipelineTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDistributionConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDistributionConfigurationRequestRequestTypeDef",
     {
         "name": str,
         "distributions": Sequence[DistributionTypeDef],
         "clientToken": str,
     },
@@ -1982,53 +2440,63 @@
 
 
 GetInfrastructureConfigurationResponseTypeDef = TypedDict(
     "GetInfrastructureConfigurationResponseTypeDef",
     {
         "requestId": str,
         "infrastructureConfiguration": InfrastructureConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImageBuildVersionsResponseTypeDef = TypedDict(
     "ListImageBuildVersionsResponseTypeDef",
     {
         "requestId": str,
         "imageSummaryList": List[ImageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImagePipelineImagesResponseTypeDef = TypedDict(
     "ListImagePipelineImagesResponseTypeDef",
     {
         "requestId": str,
         "imageSummaryList": List[ImageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImageScanFindingsResponseTypeDef = TypedDict(
+    "ListImageScanFindingsResponseTypeDef",
+    {
+        "requestId": str,
+        "findings": List[ImageScanFindingTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerRecipeResponseTypeDef = TypedDict(
     "GetContainerRecipeResponseTypeDef",
     {
         "requestId": str,
         "containerRecipe": ContainerRecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionConfigurationResponseTypeDef = TypedDict(
     "GetDistributionConfigurationResponseTypeDef",
     {
         "requestId": str,
         "distributionConfiguration": DistributionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageTypeDef = TypedDict(
     "ImageTypeDef",
     {
         "arn": str,
@@ -2047,19 +2515,21 @@
         "distributionConfiguration": DistributionConfigurationTypeDef,
         "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
         "dateCreated": str,
         "outputResources": OutputResourcesTypeDef,
         "tags": Dict[str, str],
         "buildType": BuildTypeType,
         "imageSource": ImageSourceType,
+        "scanState": ImageScanStateTypeDef,
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
     },
     total=False,
 )
 
 GetImageResponseTypeDef = TypedDict(
     "GetImageResponseTypeDef",
     {
         "requestId": str,
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder/type_defs.pyi` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder/type_defs.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -2,192 +2,242 @@
 Type annotations for imagebuilder service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_imagebuilder.type_defs import SystemsManagerAgentTypeDef
+    from types_aiobotocore_imagebuilder.type_defs import SeverityCountsTypeDef
 
-    data: SystemsManagerAgentTypeDef = {...}
+    data: SeverityCountsTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     BuildTypeType,
     ComponentTypeType,
     DiskImageFormatType,
     EbsVolumeTypeType,
+    ImageScanStatusType,
     ImageSourceType,
     ImageStatusType,
     ImageTypeType,
     OwnershipType,
     PipelineExecutionStartConditionType,
     PipelineStatusType,
     PlatformType,
+    WorkflowExecutionStatusType,
+    WorkflowStepExecutionRollbackStatusType,
+    WorkflowStepExecutionStatusType,
+    WorkflowTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
+    "SeverityCountsTypeDef",
     "SystemsManagerAgentTypeDef",
     "LaunchPermissionConfigurationTypeDef",
     "ImageStateTypeDef",
     "CancelImageCreationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelImageCreationResponseTypeDef",
     "ComponentParameterTypeDef",
     "ComponentParameterDetailTypeDef",
     "ComponentStateTypeDef",
     "ComponentVersionTypeDef",
     "TargetContainerRepositoryTypeDef",
     "ContainerRecipeSummaryTypeDef",
     "ContainerTypeDef",
     "CreateComponentRequestRequestTypeDef",
+    "CreateComponentResponseTypeDef",
+    "CreateContainerRecipeResponseTypeDef",
+    "CreateDistributionConfigurationResponseTypeDef",
     "ImageTestsConfigurationTypeDef",
     "ScheduleTypeDef",
+    "CreateImagePipelineResponseTypeDef",
+    "CreateImageRecipeResponseTypeDef",
+    "CreateImageResponseTypeDef",
     "InstanceMetadataOptionsTypeDef",
+    "CreateInfrastructureConfigurationResponseTypeDef",
+    "CvssScoreAdjustmentTypeDef",
+    "CvssScoreTypeDef",
     "DeleteComponentRequestRequestTypeDef",
+    "DeleteComponentResponseTypeDef",
     "DeleteContainerRecipeRequestRequestTypeDef",
+    "DeleteContainerRecipeResponseTypeDef",
     "DeleteDistributionConfigurationRequestRequestTypeDef",
+    "DeleteDistributionConfigurationResponseTypeDef",
     "DeleteImagePipelineRequestRequestTypeDef",
+    "DeleteImagePipelineResponseTypeDef",
     "DeleteImageRecipeRequestRequestTypeDef",
+    "DeleteImageRecipeResponseTypeDef",
     "DeleteImageRequestRequestTypeDef",
+    "DeleteImageResponseTypeDef",
     "DeleteInfrastructureConfigurationRequestRequestTypeDef",
+    "DeleteInfrastructureConfigurationResponseTypeDef",
     "DistributionConfigurationSummaryTypeDef",
     "LaunchTemplateConfigurationTypeDef",
     "S3ExportConfigurationTypeDef",
     "EbsInstanceBlockDeviceSpecificationTypeDef",
+    "EcrConfigurationTypeDef",
     "FastLaunchLaunchTemplateSpecificationTypeDef",
     "FastLaunchSnapshotConfigurationTypeDef",
     "FilterTypeDef",
     "GetComponentPolicyRequestRequestTypeDef",
+    "GetComponentPolicyResponseTypeDef",
     "GetComponentRequestRequestTypeDef",
     "GetContainerRecipePolicyRequestRequestTypeDef",
+    "GetContainerRecipePolicyResponseTypeDef",
     "GetContainerRecipeRequestRequestTypeDef",
     "GetDistributionConfigurationRequestRequestTypeDef",
     "GetImagePipelineRequestRequestTypeDef",
     "GetImagePolicyRequestRequestTypeDef",
+    "GetImagePolicyResponseTypeDef",
     "GetImageRecipePolicyRequestRequestTypeDef",
+    "GetImageRecipePolicyResponseTypeDef",
     "GetImageRecipeRequestRequestTypeDef",
     "GetImageRequestRequestTypeDef",
     "GetInfrastructureConfigurationRequestRequestTypeDef",
+    "GetWorkflowExecutionRequestRequestTypeDef",
+    "GetWorkflowExecutionResponseTypeDef",
+    "GetWorkflowStepExecutionRequestRequestTypeDef",
+    "GetWorkflowStepExecutionResponseTypeDef",
     "ImagePackageTypeDef",
     "ImageRecipeSummaryTypeDef",
+    "ImageScanFindingsFilterTypeDef",
+    "ImageScanStateTypeDef",
     "ImageVersionTypeDef",
     "ImportComponentRequestRequestTypeDef",
+    "ImportComponentResponseTypeDef",
     "ImportVmImageRequestRequestTypeDef",
+    "ImportVmImageResponseTypeDef",
     "InfrastructureConfigurationSummaryTypeDef",
     "ListComponentBuildVersionsRequestRequestTypeDef",
     "ListImagePackagesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorkflowExecutionsRequestRequestTypeDef",
+    "WorkflowExecutionMetadataTypeDef",
+    "ListWorkflowStepExecutionsRequestRequestTypeDef",
+    "WorkflowStepMetadataTypeDef",
     "S3LogsTypeDef",
+    "VulnerablePackageTypeDef",
     "PutComponentPolicyRequestRequestTypeDef",
+    "PutComponentPolicyResponseTypeDef",
     "PutContainerRecipePolicyRequestRequestTypeDef",
+    "PutContainerRecipePolicyResponseTypeDef",
     "PutImagePolicyRequestRequestTypeDef",
+    "PutImagePolicyResponseTypeDef",
     "PutImageRecipePolicyRequestRequestTypeDef",
+    "PutImageRecipePolicyResponseTypeDef",
+    "RemediationRecommendationTypeDef",
+    "ResponseMetadataTypeDef",
     "StartImagePipelineExecutionRequestRequestTypeDef",
+    "StartImagePipelineExecutionResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AdditionalInstanceConfigurationTypeDef",
-    "AmiDistributionConfigurationTypeDef",
-    "AmiTypeDef",
-    "CancelImageCreationResponseTypeDef",
-    "CreateComponentResponseTypeDef",
-    "CreateContainerRecipeResponseTypeDef",
-    "CreateDistributionConfigurationResponseTypeDef",
-    "CreateImagePipelineResponseTypeDef",
-    "CreateImageRecipeResponseTypeDef",
-    "CreateImageResponseTypeDef",
-    "CreateInfrastructureConfigurationResponseTypeDef",
-    "DeleteComponentResponseTypeDef",
-    "DeleteContainerRecipeResponseTypeDef",
-    "DeleteDistributionConfigurationResponseTypeDef",
-    "DeleteImagePipelineResponseTypeDef",
-    "DeleteImageRecipeResponseTypeDef",
-    "DeleteImageResponseTypeDef",
-    "DeleteInfrastructureConfigurationResponseTypeDef",
-    "GetComponentPolicyResponseTypeDef",
-    "GetContainerRecipePolicyResponseTypeDef",
-    "GetImagePolicyResponseTypeDef",
-    "GetImageRecipePolicyResponseTypeDef",
-    "ImportComponentResponseTypeDef",
-    "ImportVmImageResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutComponentPolicyResponseTypeDef",
-    "PutContainerRecipePolicyResponseTypeDef",
-    "PutImagePolicyResponseTypeDef",
-    "PutImageRecipePolicyResponseTypeDef",
-    "StartImagePipelineExecutionResponseTypeDef",
     "UpdateDistributionConfigurationResponseTypeDef",
     "UpdateImagePipelineResponseTypeDef",
     "UpdateInfrastructureConfigurationResponseTypeDef",
+    "AccountAggregationTypeDef",
+    "ImageAggregationTypeDef",
+    "ImagePipelineAggregationTypeDef",
+    "VulnerabilityIdAggregationTypeDef",
+    "AdditionalInstanceConfigurationTypeDef",
+    "AmiDistributionConfigurationTypeDef",
+    "AmiTypeDef",
     "ComponentConfigurationTypeDef",
     "ComponentSummaryTypeDef",
     "ComponentTypeDef",
     "ListComponentsResponseTypeDef",
     "ContainerDistributionConfigurationTypeDef",
     "ListContainerRecipesResponseTypeDef",
-    "CreateImageRequestRequestTypeDef",
-    "CreateImagePipelineRequestRequestTypeDef",
-    "ImagePipelineTypeDef",
-    "UpdateImagePipelineRequestRequestTypeDef",
+    "CvssScoreDetailsTypeDef",
     "ListDistributionConfigurationsResponseTypeDef",
     "InstanceBlockDeviceMappingTypeDef",
+    "ImageScanningConfigurationTypeDef",
     "FastLaunchConfigurationTypeDef",
     "ListComponentsRequestRequestTypeDef",
     "ListContainerRecipesRequestRequestTypeDef",
     "ListDistributionConfigurationsRequestRequestTypeDef",
     "ListImageBuildVersionsRequestRequestTypeDef",
     "ListImagePipelineImagesRequestRequestTypeDef",
     "ListImagePipelinesRequestRequestTypeDef",
     "ListImageRecipesRequestRequestTypeDef",
+    "ListImageScanFindingAggregationsRequestRequestTypeDef",
     "ListImagesRequestRequestTypeDef",
     "ListInfrastructureConfigurationsRequestRequestTypeDef",
     "ListImagePackagesResponseTypeDef",
     "ListImageRecipesResponseTypeDef",
+    "ListImageScanFindingsRequestRequestTypeDef",
     "ListImagesResponseTypeDef",
     "ListInfrastructureConfigurationsResponseTypeDef",
+    "ListWorkflowExecutionsResponseTypeDef",
+    "ListWorkflowStepExecutionsResponseTypeDef",
     "LoggingTypeDef",
+    "PackageVulnerabilityDetailsTypeDef",
+    "RemediationTypeDef",
+    "ImageScanFindingAggregationTypeDef",
     "OutputResourcesTypeDef",
     "ListComponentBuildVersionsResponseTypeDef",
     "GetComponentResponseTypeDef",
-    "GetImagePipelineResponseTypeDef",
-    "ListImagePipelinesResponseTypeDef",
+    "InspectorScoreDetailsTypeDef",
     "CreateImageRecipeRequestRequestTypeDef",
     "ImageRecipeTypeDef",
     "InstanceConfigurationTypeDef",
+    "CreateImagePipelineRequestRequestTypeDef",
+    "CreateImageRequestRequestTypeDef",
+    "ImagePipelineTypeDef",
+    "UpdateImagePipelineRequestRequestTypeDef",
     "DistributionTypeDef",
     "CreateInfrastructureConfigurationRequestRequestTypeDef",
     "InfrastructureConfigurationTypeDef",
     "UpdateInfrastructureConfigurationRequestRequestTypeDef",
+    "ListImageScanFindingAggregationsResponseTypeDef",
     "ImageSummaryTypeDef",
+    "ImageScanFindingTypeDef",
     "GetImageRecipeResponseTypeDef",
     "ContainerRecipeTypeDef",
     "CreateContainerRecipeRequestRequestTypeDef",
+    "GetImagePipelineResponseTypeDef",
+    "ListImagePipelinesResponseTypeDef",
     "CreateDistributionConfigurationRequestRequestTypeDef",
     "DistributionConfigurationTypeDef",
     "UpdateDistributionConfigurationRequestRequestTypeDef",
     "GetInfrastructureConfigurationResponseTypeDef",
     "ListImageBuildVersionsResponseTypeDef",
     "ListImagePipelineImagesResponseTypeDef",
+    "ListImageScanFindingsResponseTypeDef",
     "GetContainerRecipeResponseTypeDef",
     "GetDistributionConfigurationResponseTypeDef",
     "ImageTypeDef",
     "GetImageResponseTypeDef",
 )
 
+SeverityCountsTypeDef = TypedDict(
+    "SeverityCountsTypeDef",
+    {
+        "all": int,
+        "critical": int,
+        "high": int,
+        "medium": int,
+    },
+    total=False,
+)
+
 SystemsManagerAgentTypeDef = TypedDict(
     "SystemsManagerAgentTypeDef",
     {
         "uninstallAfterBuild": bool,
     },
     total=False,
 )
@@ -216,22 +266,21 @@
     "CancelImageCreationRequestRequestTypeDef",
     {
         "imageBuildVersionArn": str,
         "clientToken": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelImageCreationResponseTypeDef = TypedDict(
+    "CancelImageCreationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "requestId": str,
+        "clientToken": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentParameterTypeDef = TypedDict(
     "ComponentParameterTypeDef",
     {
         "name": str,
@@ -341,14 +390,44 @@
 )
 
 class CreateComponentRequestRequestTypeDef(
     _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
 ):
     pass
 
+CreateComponentResponseTypeDef = TypedDict(
+    "CreateComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateContainerRecipeResponseTypeDef = TypedDict(
+    "CreateContainerRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDistributionConfigurationResponseTypeDef = TypedDict(
+    "CreateDistributionConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageTestsConfigurationTypeDef = TypedDict(
     "ImageTestsConfigurationTypeDef",
     {
         "imageTestsEnabled": bool,
         "timeoutMinutes": int,
     },
     total=False,
@@ -360,72 +439,195 @@
         "scheduleExpression": str,
         "timezone": str,
         "pipelineExecutionStartCondition": PipelineExecutionStartConditionType,
     },
     total=False,
 )
 
+CreateImagePipelineResponseTypeDef = TypedDict(
+    "CreateImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateImageRecipeResponseTypeDef = TypedDict(
+    "CreateImageRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateImageResponseTypeDef = TypedDict(
+    "CreateImageResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstanceMetadataOptionsTypeDef = TypedDict(
     "InstanceMetadataOptionsTypeDef",
     {
         "httpTokens": str,
         "httpPutResponseHopLimit": int,
     },
     total=False,
 )
 
+CreateInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "CreateInfrastructureConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CvssScoreAdjustmentTypeDef = TypedDict(
+    "CvssScoreAdjustmentTypeDef",
+    {
+        "metric": str,
+        "reason": str,
+    },
+    total=False,
+)
+
+CvssScoreTypeDef = TypedDict(
+    "CvssScoreTypeDef",
+    {
+        "baseScore": float,
+        "scoringVector": str,
+        "version": str,
+        "source": str,
+    },
+    total=False,
+)
+
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "componentBuildVersionArn": str,
     },
 )
 
+DeleteComponentResponseTypeDef = TypedDict(
+    "DeleteComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteContainerRecipeRequestRequestTypeDef = TypedDict(
     "DeleteContainerRecipeRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
+DeleteContainerRecipeResponseTypeDef = TypedDict(
+    "DeleteContainerRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDistributionConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteDistributionConfigurationRequestRequestTypeDef",
     {
         "distributionConfigurationArn": str,
     },
 )
 
+DeleteDistributionConfigurationResponseTypeDef = TypedDict(
+    "DeleteDistributionConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImagePipelineRequestRequestTypeDef = TypedDict(
     "DeleteImagePipelineRequestRequestTypeDef",
     {
         "imagePipelineArn": str,
     },
 )
 
+DeleteImagePipelineResponseTypeDef = TypedDict(
+    "DeleteImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImageRecipeRequestRequestTypeDef = TypedDict(
     "DeleteImageRecipeRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
+DeleteImageRecipeResponseTypeDef = TypedDict(
+    "DeleteImageRecipeResponseTypeDef",
+    {
+        "requestId": str,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImageRequestRequestTypeDef = TypedDict(
     "DeleteImageRequestRequestTypeDef",
     {
         "imageBuildVersionArn": str,
     },
 )
 
+DeleteImageResponseTypeDef = TypedDict(
+    "DeleteImageResponseTypeDef",
+    {
+        "requestId": str,
+        "imageBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteInfrastructureConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteInfrastructureConfigurationRequestRequestTypeDef",
     {
         "infrastructureConfigurationArn": str,
     },
 )
 
+DeleteInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "DeleteInfrastructureConfigurationResponseTypeDef",
+    {
+        "requestId": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DistributionConfigurationSummaryTypeDef = TypedDict(
     "DistributionConfigurationSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "description": str,
         "dateCreated": str,
@@ -488,14 +690,23 @@
         "volumeSize": int,
         "volumeType": EbsVolumeTypeType,
         "throughput": int,
     },
     total=False,
 )
 
+EcrConfigurationTypeDef = TypedDict(
+    "EcrConfigurationTypeDef",
+    {
+        "repositoryName": str,
+        "containerTags": Sequence[str],
+    },
+    total=False,
+)
+
 FastLaunchLaunchTemplateSpecificationTypeDef = TypedDict(
     "FastLaunchLaunchTemplateSpecificationTypeDef",
     {
         "launchTemplateId": str,
         "launchTemplateName": str,
         "launchTemplateVersion": str,
     },
@@ -522,28 +733,46 @@
 GetComponentPolicyRequestRequestTypeDef = TypedDict(
     "GetComponentPolicyRequestRequestTypeDef",
     {
         "componentArn": str,
     },
 )
 
+GetComponentPolicyResponseTypeDef = TypedDict(
+    "GetComponentPolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetComponentRequestRequestTypeDef = TypedDict(
     "GetComponentRequestRequestTypeDef",
     {
         "componentBuildVersionArn": str,
     },
 )
 
 GetContainerRecipePolicyRequestRequestTypeDef = TypedDict(
     "GetContainerRecipePolicyRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
+GetContainerRecipePolicyResponseTypeDef = TypedDict(
+    "GetContainerRecipePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContainerRecipeRequestRequestTypeDef = TypedDict(
     "GetContainerRecipeRequestRequestTypeDef",
     {
         "containerRecipeArn": str,
     },
 )
 
@@ -564,21 +793,39 @@
 GetImagePolicyRequestRequestTypeDef = TypedDict(
     "GetImagePolicyRequestRequestTypeDef",
     {
         "imageArn": str,
     },
 )
 
+GetImagePolicyResponseTypeDef = TypedDict(
+    "GetImagePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImageRecipePolicyRequestRequestTypeDef = TypedDict(
     "GetImageRecipePolicyRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
+GetImageRecipePolicyResponseTypeDef = TypedDict(
+    "GetImageRecipePolicyResponseTypeDef",
+    {
+        "requestId": str,
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImageRecipeRequestRequestTypeDef = TypedDict(
     "GetImageRecipeRequestRequestTypeDef",
     {
         "imageRecipeArn": str,
     },
 )
 
@@ -592,14 +839,72 @@
 GetInfrastructureConfigurationRequestRequestTypeDef = TypedDict(
     "GetInfrastructureConfigurationRequestRequestTypeDef",
     {
         "infrastructureConfigurationArn": str,
     },
 )
 
+GetWorkflowExecutionRequestRequestTypeDef = TypedDict(
+    "GetWorkflowExecutionRequestRequestTypeDef",
+    {
+        "workflowExecutionId": str,
+    },
+)
+
+GetWorkflowExecutionResponseTypeDef = TypedDict(
+    "GetWorkflowExecutionResponseTypeDef",
+    {
+        "requestId": str,
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "type": WorkflowTypeType,
+        "status": WorkflowExecutionStatusType,
+        "message": str,
+        "totalStepCount": int,
+        "totalStepsSucceeded": int,
+        "totalStepsFailed": int,
+        "totalStepsSkipped": int,
+        "startTime": str,
+        "endTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetWorkflowStepExecutionRequestRequestTypeDef = TypedDict(
+    "GetWorkflowStepExecutionRequestRequestTypeDef",
+    {
+        "stepExecutionId": str,
+    },
+)
+
+GetWorkflowStepExecutionResponseTypeDef = TypedDict(
+    "GetWorkflowStepExecutionResponseTypeDef",
+    {
+        "requestId": str,
+        "stepExecutionId": str,
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "name": str,
+        "description": str,
+        "action": str,
+        "status": WorkflowStepExecutionStatusType,
+        "rollbackStatus": WorkflowStepExecutionRollbackStatusType,
+        "message": str,
+        "inputs": str,
+        "outputs": str,
+        "startTime": str,
+        "endTime": str,
+        "onFailure": str,
+        "timeoutSeconds": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImagePackageTypeDef = TypedDict(
     "ImagePackageTypeDef",
     {
         "packageName": str,
         "packageVersion": str,
     },
     total=False,
@@ -615,14 +920,32 @@
         "parentImage": str,
         "dateCreated": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ImageScanFindingsFilterTypeDef = TypedDict(
+    "ImageScanFindingsFilterTypeDef",
+    {
+        "name": str,
+        "values": Sequence[str],
+    },
+    total=False,
+)
+
+ImageScanStateTypeDef = TypedDict(
+    "ImageScanStateTypeDef",
+    {
+        "status": ImageScanStatusType,
+        "reason": str,
+    },
+    total=False,
+)
+
 ImageVersionTypeDef = TypedDict(
     "ImageVersionTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ImageTypeType,
         "version": str,
@@ -661,14 +984,24 @@
 )
 
 class ImportComponentRequestRequestTypeDef(
     _RequiredImportComponentRequestRequestTypeDef, _OptionalImportComponentRequestRequestTypeDef
 ):
     pass
 
+ImportComponentResponseTypeDef = TypedDict(
+    "ImportComponentResponseTypeDef",
+    {
+        "requestId": str,
+        "clientToken": str,
+        "componentBuildVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportVmImageRequestRequestTypeDef = TypedDict(
     "_RequiredImportVmImageRequestRequestTypeDef",
     {
         "name": str,
         "semanticVersion": str,
         "platform": PlatformType,
         "vmImportTaskId": str,
@@ -686,14 +1019,24 @@
 )
 
 class ImportVmImageRequestRequestTypeDef(
     _RequiredImportVmImageRequestRequestTypeDef, _OptionalImportVmImageRequestRequestTypeDef
 ):
     pass
 
+ImportVmImageResponseTypeDef = TypedDict(
+    "ImportVmImageResponseTypeDef",
+    {
+        "requestId": str,
+        "imageArn": str,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InfrastructureConfigurationSummaryTypeDef = TypedDict(
     "InfrastructureConfigurationSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "description": str,
         "dateCreated": str,
@@ -750,395 +1093,347 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
-S3LogsTypeDef = TypedDict(
-    "S3LogsTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "s3BucketName": str,
-        "s3KeyPrefix": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-PutComponentPolicyRequestRequestTypeDef = TypedDict(
-    "PutComponentPolicyRequestRequestTypeDef",
+_RequiredListWorkflowExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWorkflowExecutionsRequestRequestTypeDef",
     {
-        "componentArn": str,
-        "policy": str,
+        "imageBuildVersionArn": str,
     },
 )
-
-PutContainerRecipePolicyRequestRequestTypeDef = TypedDict(
-    "PutContainerRecipePolicyRequestRequestTypeDef",
+_OptionalListWorkflowExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWorkflowExecutionsRequestRequestTypeDef",
     {
-        "containerRecipeArn": str,
-        "policy": str,
+        "maxResults": int,
+        "nextToken": str,
     },
+    total=False,
 )
 
-PutImagePolicyRequestRequestTypeDef = TypedDict(
-    "PutImagePolicyRequestRequestTypeDef",
-    {
-        "imageArn": str,
-        "policy": str,
-    },
-)
+class ListWorkflowExecutionsRequestRequestTypeDef(
+    _RequiredListWorkflowExecutionsRequestRequestTypeDef,
+    _OptionalListWorkflowExecutionsRequestRequestTypeDef,
+):
+    pass
 
-PutImageRecipePolicyRequestRequestTypeDef = TypedDict(
-    "PutImageRecipePolicyRequestRequestTypeDef",
+WorkflowExecutionMetadataTypeDef = TypedDict(
+    "WorkflowExecutionMetadataTypeDef",
     {
-        "imageRecipeArn": str,
-        "policy": str,
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "type": WorkflowTypeType,
+        "status": WorkflowExecutionStatusType,
+        "message": str,
+        "totalStepCount": int,
+        "totalStepsSucceeded": int,
+        "totalStepsFailed": int,
+        "totalStepsSkipped": int,
+        "startTime": str,
+        "endTime": str,
     },
+    total=False,
 )
 
-StartImagePipelineExecutionRequestRequestTypeDef = TypedDict(
-    "StartImagePipelineExecutionRequestRequestTypeDef",
+_RequiredListWorkflowStepExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWorkflowStepExecutionsRequestRequestTypeDef",
     {
-        "imagePipelineArn": str,
-        "clientToken": str,
+        "workflowExecutionId": str,
     },
 )
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+_OptionalListWorkflowStepExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWorkflowStepExecutionsRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
+        "maxResults": int,
+        "nextToken": str,
     },
+    total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
+class ListWorkflowStepExecutionsRequestRequestTypeDef(
+    _RequiredListWorkflowStepExecutionsRequestRequestTypeDef,
+    _OptionalListWorkflowStepExecutionsRequestRequestTypeDef,
+):
+    pass
 
-AdditionalInstanceConfigurationTypeDef = TypedDict(
-    "AdditionalInstanceConfigurationTypeDef",
+WorkflowStepMetadataTypeDef = TypedDict(
+    "WorkflowStepMetadataTypeDef",
     {
-        "systemsManagerAgent": SystemsManagerAgentTypeDef,
-        "userDataOverride": str,
+        "stepExecutionId": str,
+        "name": str,
+        "description": str,
+        "action": str,
+        "status": WorkflowStepExecutionStatusType,
+        "rollbackStatus": WorkflowStepExecutionRollbackStatusType,
+        "message": str,
+        "inputs": str,
+        "outputs": str,
+        "startTime": str,
+        "endTime": str,
     },
     total=False,
 )
 
-AmiDistributionConfigurationTypeDef = TypedDict(
-    "AmiDistributionConfigurationTypeDef",
+S3LogsTypeDef = TypedDict(
+    "S3LogsTypeDef",
     {
-        "name": str,
-        "description": str,
-        "targetAccountIds": Sequence[str],
-        "amiTags": Mapping[str, str],
-        "kmsKeyId": str,
-        "launchPermission": LaunchPermissionConfigurationTypeDef,
+        "s3BucketName": str,
+        "s3KeyPrefix": str,
     },
     total=False,
 )
 
-AmiTypeDef = TypedDict(
-    "AmiTypeDef",
+VulnerablePackageTypeDef = TypedDict(
+    "VulnerablePackageTypeDef",
     {
-        "region": str,
-        "image": str,
         "name": str,
-        "description": str,
-        "state": ImageStateTypeDef,
-        "accountId": str,
+        "version": str,
+        "sourceLayerHash": str,
+        "epoch": int,
+        "release": str,
+        "arch": str,
+        "packageManager": str,
+        "filePath": str,
+        "fixedInVersion": str,
+        "remediation": str,
     },
     total=False,
 )
 
-CancelImageCreationResponseTypeDef = TypedDict(
-    "CancelImageCreationResponseTypeDef",
+PutComponentPolicyRequestRequestTypeDef = TypedDict(
+    "PutComponentPolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "componentArn": str,
+        "policy": str,
     },
 )
 
-CreateComponentResponseTypeDef = TypedDict(
-    "CreateComponentResponseTypeDef",
+PutComponentPolicyResponseTypeDef = TypedDict(
+    "PutComponentPolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "componentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateContainerRecipeResponseTypeDef = TypedDict(
-    "CreateContainerRecipeResponseTypeDef",
+PutContainerRecipePolicyRequestRequestTypeDef = TypedDict(
+    "PutContainerRecipePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
         "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDistributionConfigurationResponseTypeDef = TypedDict(
-    "CreateDistributionConfigurationResponseTypeDef",
-    {
-        "requestId": str,
-        "clientToken": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policy": str,
     },
 )
 
-CreateImagePipelineResponseTypeDef = TypedDict(
-    "CreateImagePipelineResponseTypeDef",
+PutContainerRecipePolicyResponseTypeDef = TypedDict(
+    "PutContainerRecipePolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "containerRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateImageRecipeResponseTypeDef = TypedDict(
-    "CreateImageRecipeResponseTypeDef",
+PutImagePolicyRequestRequestTypeDef = TypedDict(
+    "PutImagePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageArn": str,
+        "policy": str,
     },
 )
 
-CreateImageResponseTypeDef = TypedDict(
-    "CreateImageResponseTypeDef",
+PutImagePolicyResponseTypeDef = TypedDict(
+    "PutImagePolicyResponseTypeDef",
     {
         "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "CreateInfrastructureConfigurationResponseTypeDef",
+PutImageRecipePolicyRequestRequestTypeDef = TypedDict(
+    "PutImageRecipePolicyRequestRequestTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageRecipeArn": str,
+        "policy": str,
     },
 )
 
-DeleteComponentResponseTypeDef = TypedDict(
-    "DeleteComponentResponseTypeDef",
+PutImageRecipePolicyResponseTypeDef = TypedDict(
+    "PutImageRecipePolicyResponseTypeDef",
     {
         "requestId": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageRecipeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteContainerRecipeResponseTypeDef = TypedDict(
-    "DeleteContainerRecipeResponseTypeDef",
+RemediationRecommendationTypeDef = TypedDict(
+    "RemediationRecommendationTypeDef",
     {
-        "requestId": str,
-        "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "text": str,
+        "url": str,
     },
+    total=False,
 )
 
-DeleteDistributionConfigurationResponseTypeDef = TypedDict(
-    "DeleteDistributionConfigurationResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "requestId": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DeleteImagePipelineResponseTypeDef = TypedDict(
-    "DeleteImagePipelineResponseTypeDef",
+StartImagePipelineExecutionRequestRequestTypeDef = TypedDict(
+    "StartImagePipelineExecutionRequestRequestTypeDef",
     {
-        "requestId": str,
         "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteImageRecipeResponseTypeDef = TypedDict(
-    "DeleteImageRecipeResponseTypeDef",
-    {
-        "requestId": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientToken": str,
     },
 )
 
-DeleteImageResponseTypeDef = TypedDict(
-    "DeleteImageResponseTypeDef",
+StartImagePipelineExecutionResponseTypeDef = TypedDict(
+    "StartImagePipelineExecutionResponseTypeDef",
     {
         "requestId": str,
+        "clientToken": str,
         "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "DeleteInfrastructureConfigurationResponseTypeDef",
-    {
-        "requestId": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComponentPolicyResponseTypeDef = TypedDict(
-    "GetComponentPolicyResponseTypeDef",
-    {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContainerRecipePolicyResponseTypeDef = TypedDict(
-    "GetContainerRecipePolicyResponseTypeDef",
-    {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetImagePolicyResponseTypeDef = TypedDict(
-    "GetImagePolicyResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-GetImageRecipePolicyResponseTypeDef = TypedDict(
-    "GetImageRecipePolicyResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "requestId": str,
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-ImportComponentResponseTypeDef = TypedDict(
-    "ImportComponentResponseTypeDef",
+UpdateDistributionConfigurationResponseTypeDef = TypedDict(
+    "UpdateDistributionConfigurationResponseTypeDef",
     {
         "requestId": str,
         "clientToken": str,
-        "componentBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "distributionConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ImportVmImageResponseTypeDef = TypedDict(
-    "ImportVmImageResponseTypeDef",
+UpdateImagePipelineResponseTypeDef = TypedDict(
+    "UpdateImagePipelineResponseTypeDef",
     {
         "requestId": str,
-        "imageArn": str,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imagePipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutComponentPolicyResponseTypeDef = TypedDict(
-    "PutComponentPolicyResponseTypeDef",
+UpdateInfrastructureConfigurationResponseTypeDef = TypedDict(
+    "UpdateInfrastructureConfigurationResponseTypeDef",
     {
         "requestId": str,
-        "componentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientToken": str,
+        "infrastructureConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutContainerRecipePolicyResponseTypeDef = TypedDict(
-    "PutContainerRecipePolicyResponseTypeDef",
+AccountAggregationTypeDef = TypedDict(
+    "AccountAggregationTypeDef",
     {
-        "requestId": str,
-        "containerRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accountId": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-PutImagePolicyResponseTypeDef = TypedDict(
-    "PutImagePolicyResponseTypeDef",
+ImageAggregationTypeDef = TypedDict(
+    "ImageAggregationTypeDef",
     {
-        "requestId": str,
-        "imageArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageBuildVersionArn": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-PutImageRecipePolicyResponseTypeDef = TypedDict(
-    "PutImageRecipePolicyResponseTypeDef",
+ImagePipelineAggregationTypeDef = TypedDict(
+    "ImagePipelineAggregationTypeDef",
     {
-        "requestId": str,
-        "imageRecipeArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imagePipelineArn": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-StartImagePipelineExecutionResponseTypeDef = TypedDict(
-    "StartImagePipelineExecutionResponseTypeDef",
+VulnerabilityIdAggregationTypeDef = TypedDict(
+    "VulnerabilityIdAggregationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imageBuildVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "vulnerabilityId": str,
+        "severityCounts": SeverityCountsTypeDef,
     },
+    total=False,
 )
 
-UpdateDistributionConfigurationResponseTypeDef = TypedDict(
-    "UpdateDistributionConfigurationResponseTypeDef",
+AdditionalInstanceConfigurationTypeDef = TypedDict(
+    "AdditionalInstanceConfigurationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "distributionConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "systemsManagerAgent": SystemsManagerAgentTypeDef,
+        "userDataOverride": str,
     },
+    total=False,
 )
 
-UpdateImagePipelineResponseTypeDef = TypedDict(
-    "UpdateImagePipelineResponseTypeDef",
+AmiDistributionConfigurationTypeDef = TypedDict(
+    "AmiDistributionConfigurationTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "imagePipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
+        "description": str,
+        "targetAccountIds": Sequence[str],
+        "amiTags": Mapping[str, str],
+        "kmsKeyId": str,
+        "launchPermission": LaunchPermissionConfigurationTypeDef,
     },
+    total=False,
 )
 
-UpdateInfrastructureConfigurationResponseTypeDef = TypedDict(
-    "UpdateInfrastructureConfigurationResponseTypeDef",
+AmiTypeDef = TypedDict(
+    "AmiTypeDef",
     {
-        "requestId": str,
-        "clientToken": str,
-        "infrastructureConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "region": str,
+        "image": str,
+        "name": str,
+        "description": str,
+        "state": ImageStateTypeDef,
+        "accountId": str,
     },
+    total=False,
 )
 
 _RequiredComponentConfigurationTypeDef = TypedDict(
     "_RequiredComponentConfigurationTypeDef",
     {
         "componentArn": str,
     },
@@ -1204,15 +1499,15 @@
 
 ListComponentsResponseTypeDef = TypedDict(
     "ListComponentsResponseTypeDef",
     {
         "requestId": str,
         "componentVersionList": List[ComponentVersionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContainerDistributionConfigurationTypeDef = TypedDict(
     "_RequiredContainerDistributionConfigurationTypeDef",
     {
         "targetRepository": TargetContainerRepositoryTypeDef,
@@ -1235,147 +1530,61 @@
 
 ListContainerRecipesResponseTypeDef = TypedDict(
     "ListContainerRecipesResponseTypeDef",
     {
         "requestId": str,
         "containerRecipeSummaryList": List[ContainerRecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateImageRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateImageRequestRequestTypeDef",
-    {
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalCreateImageRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateImageRequestRequestTypeDef",
-    {
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "tags": Mapping[str, str],
-    },
-    total=False,
-)
-
-class CreateImageRequestRequestTypeDef(
-    _RequiredCreateImageRequestRequestTypeDef, _OptionalCreateImageRequestRequestTypeDef
-):
-    pass
-
-_RequiredCreateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateImagePipelineRequestRequestTypeDef",
-    {
-        "name": str,
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalCreateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateImagePipelineRequestRequestTypeDef",
-    {
-        "description": str,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
-        "tags": Mapping[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class CreateImagePipelineRequestRequestTypeDef(
-    _RequiredCreateImagePipelineRequestRequestTypeDef,
-    _OptionalCreateImagePipelineRequestRequestTypeDef,
-):
-    pass
-
-ImagePipelineTypeDef = TypedDict(
-    "ImagePipelineTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "description": str,
-        "platform": PlatformType,
-        "enhancedImageMetadataEnabled": bool,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "infrastructureConfigurationArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
-        "dateCreated": str,
-        "dateUpdated": str,
-        "dateLastRun": str,
-        "dateNextRun": str,
-        "tags": Dict[str, str],
-    },
-    total=False,
-)
-
-_RequiredUpdateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateImagePipelineRequestRequestTypeDef",
+CvssScoreDetailsTypeDef = TypedDict(
+    "CvssScoreDetailsTypeDef",
     {
-        "imagePipelineArn": str,
-        "infrastructureConfigurationArn": str,
-        "clientToken": str,
-    },
-)
-_OptionalUpdateImagePipelineRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateImagePipelineRequestRequestTypeDef",
-    {
-        "description": str,
-        "imageRecipeArn": str,
-        "containerRecipeArn": str,
-        "distributionConfigurationArn": str,
-        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
-        "enhancedImageMetadataEnabled": bool,
-        "schedule": ScheduleTypeDef,
-        "status": PipelineStatusType,
+        "scoreSource": str,
+        "cvssSource": str,
+        "version": str,
+        "score": float,
+        "scoringVector": str,
+        "adjustments": List[CvssScoreAdjustmentTypeDef],
     },
     total=False,
 )
 
-class UpdateImagePipelineRequestRequestTypeDef(
-    _RequiredUpdateImagePipelineRequestRequestTypeDef,
-    _OptionalUpdateImagePipelineRequestRequestTypeDef,
-):
-    pass
-
 ListDistributionConfigurationsResponseTypeDef = TypedDict(
     "ListDistributionConfigurationsResponseTypeDef",
     {
         "requestId": str,
         "distributionConfigurationSummaryList": List[DistributionConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceBlockDeviceMappingTypeDef = TypedDict(
     "InstanceBlockDeviceMappingTypeDef",
     {
         "deviceName": str,
         "ebs": EbsInstanceBlockDeviceSpecificationTypeDef,
         "virtualName": str,
         "noDevice": str,
     },
     total=False,
 )
 
+ImageScanningConfigurationTypeDef = TypedDict(
+    "ImageScanningConfigurationTypeDef",
+    {
+        "imageScanningEnabled": bool,
+        "ecrConfiguration": EcrConfigurationTypeDef,
+    },
+    total=False,
+)
+
 _RequiredFastLaunchConfigurationTypeDef = TypedDict(
     "_RequiredFastLaunchConfigurationTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalFastLaunchConfigurationTypeDef = TypedDict(
@@ -1488,14 +1697,23 @@
         "filters": Sequence[FilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListImageScanFindingAggregationsRequestRequestTypeDef = TypedDict(
+    "ListImageScanFindingAggregationsRequestRequestTypeDef",
+    {
+        "filter": FilterTypeDef,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListImagesRequestRequestTypeDef = TypedDict(
     "ListImagesRequestRequestTypeDef",
     {
         "owner": OwnershipType,
         "filters": Sequence[FilterTypeDef],
         "byName": bool,
         "maxResults": int,
@@ -1517,56 +1735,138 @@
 
 ListImagePackagesResponseTypeDef = TypedDict(
     "ListImagePackagesResponseTypeDef",
     {
         "requestId": str,
         "imagePackageList": List[ImagePackageTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImageRecipesResponseTypeDef = TypedDict(
     "ListImageRecipesResponseTypeDef",
     {
         "requestId": str,
         "imageRecipeSummaryList": List[ImageRecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListImageScanFindingsRequestRequestTypeDef = TypedDict(
+    "ListImageScanFindingsRequestRequestTypeDef",
+    {
+        "filters": Sequence[ImageScanFindingsFilterTypeDef],
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListImagesResponseTypeDef = TypedDict(
     "ListImagesResponseTypeDef",
     {
         "requestId": str,
         "imageVersionList": List[ImageVersionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInfrastructureConfigurationsResponseTypeDef = TypedDict(
     "ListInfrastructureConfigurationsResponseTypeDef",
     {
         "requestId": str,
         "infrastructureConfigurationSummaryList": List[InfrastructureConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkflowExecutionsResponseTypeDef = TypedDict(
+    "ListWorkflowExecutionsResponseTypeDef",
+    {
+        "requestId": str,
+        "workflowExecutions": List[WorkflowExecutionMetadataTypeDef],
+        "imageBuildVersionArn": str,
+        "message": str,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkflowStepExecutionsResponseTypeDef = TypedDict(
+    "ListWorkflowStepExecutionsResponseTypeDef",
+    {
+        "requestId": str,
+        "steps": List[WorkflowStepMetadataTypeDef],
+        "workflowBuildVersionArn": str,
+        "workflowExecutionId": str,
+        "imageBuildVersionArn": str,
+        "message": str,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingTypeDef = TypedDict(
     "LoggingTypeDef",
     {
         "s3Logs": S3LogsTypeDef,
     },
     total=False,
 )
 
+_RequiredPackageVulnerabilityDetailsTypeDef = TypedDict(
+    "_RequiredPackageVulnerabilityDetailsTypeDef",
+    {
+        "vulnerabilityId": str,
+    },
+)
+_OptionalPackageVulnerabilityDetailsTypeDef = TypedDict(
+    "_OptionalPackageVulnerabilityDetailsTypeDef",
+    {
+        "vulnerablePackages": List[VulnerablePackageTypeDef],
+        "source": str,
+        "cvss": List[CvssScoreTypeDef],
+        "relatedVulnerabilities": List[str],
+        "sourceUrl": str,
+        "vendorSeverity": str,
+        "vendorCreatedAt": datetime,
+        "vendorUpdatedAt": datetime,
+        "referenceUrls": List[str],
+    },
+    total=False,
+)
+
+class PackageVulnerabilityDetailsTypeDef(
+    _RequiredPackageVulnerabilityDetailsTypeDef, _OptionalPackageVulnerabilityDetailsTypeDef
+):
+    pass
+
+RemediationTypeDef = TypedDict(
+    "RemediationTypeDef",
+    {
+        "recommendation": RemediationRecommendationTypeDef,
+    },
+    total=False,
+)
+
+ImageScanFindingAggregationTypeDef = TypedDict(
+    "ImageScanFindingAggregationTypeDef",
+    {
+        "accountAggregation": AccountAggregationTypeDef,
+        "imageAggregation": ImageAggregationTypeDef,
+        "imagePipelineAggregation": ImagePipelineAggregationTypeDef,
+        "vulnerabilityIdAggregation": VulnerabilityIdAggregationTypeDef,
+    },
+    total=False,
+)
+
 OutputResourcesTypeDef = TypedDict(
     "OutputResourcesTypeDef",
     {
         "amis": List[AmiTypeDef],
         "containers": List[ContainerTypeDef],
     },
     total=False,
@@ -1574,44 +1874,33 @@
 
 ListComponentBuildVersionsResponseTypeDef = TypedDict(
     "ListComponentBuildVersionsResponseTypeDef",
     {
         "requestId": str,
         "componentSummaryList": List[ComponentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentResponseTypeDef = TypedDict(
     "GetComponentResponseTypeDef",
     {
         "requestId": str,
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetImagePipelineResponseTypeDef = TypedDict(
-    "GetImagePipelineResponseTypeDef",
+InspectorScoreDetailsTypeDef = TypedDict(
+    "InspectorScoreDetailsTypeDef",
     {
-        "requestId": str,
-        "imagePipeline": ImagePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListImagePipelinesResponseTypeDef = TypedDict(
-    "ListImagePipelinesResponseTypeDef",
-    {
-        "requestId": str,
-        "imagePipelineList": List[ImagePipelineTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "adjustedCvss": CvssScoreDetailsTypeDef,
     },
+    total=False,
 )
 
 _RequiredCreateImageRecipeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateImageRecipeRequestRequestTypeDef",
     {
         "name": str,
         "semanticVersion": str,
@@ -1663,14 +1952,126 @@
     {
         "image": str,
         "blockDeviceMappings": Sequence[InstanceBlockDeviceMappingTypeDef],
     },
     total=False,
 )
 
+_RequiredCreateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateImagePipelineRequestRequestTypeDef",
+    {
+        "name": str,
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalCreateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateImagePipelineRequestRequestTypeDef",
+    {
+        "description": str,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "tags": Mapping[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class CreateImagePipelineRequestRequestTypeDef(
+    _RequiredCreateImagePipelineRequestRequestTypeDef,
+    _OptionalCreateImagePipelineRequestRequestTypeDef,
+):
+    pass
+
+_RequiredCreateImageRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateImageRequestRequestTypeDef",
+    {
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalCreateImageRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateImageRequestRequestTypeDef",
+    {
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "tags": Mapping[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class CreateImageRequestRequestTypeDef(
+    _RequiredCreateImageRequestRequestTypeDef, _OptionalCreateImageRequestRequestTypeDef
+):
+    pass
+
+ImagePipelineTypeDef = TypedDict(
+    "ImagePipelineTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "description": str,
+        "platform": PlatformType,
+        "enhancedImageMetadataEnabled": bool,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "infrastructureConfigurationArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "dateCreated": str,
+        "dateUpdated": str,
+        "dateLastRun": str,
+        "dateNextRun": str,
+        "tags": Dict[str, str],
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+_RequiredUpdateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateImagePipelineRequestRequestTypeDef",
+    {
+        "imagePipelineArn": str,
+        "infrastructureConfigurationArn": str,
+        "clientToken": str,
+    },
+)
+_OptionalUpdateImagePipelineRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateImagePipelineRequestRequestTypeDef",
+    {
+        "description": str,
+        "imageRecipeArn": str,
+        "containerRecipeArn": str,
+        "distributionConfigurationArn": str,
+        "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
+        "enhancedImageMetadataEnabled": bool,
+        "schedule": ScheduleTypeDef,
+        "status": PipelineStatusType,
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class UpdateImagePipelineRequestRequestTypeDef(
+    _RequiredUpdateImagePipelineRequestRequestTypeDef,
+    _OptionalUpdateImagePipelineRequestRequestTypeDef,
+):
+    pass
+
 _RequiredDistributionTypeDef = TypedDict(
     "_RequiredDistributionTypeDef",
     {
         "region": str,
     },
 )
 _OptionalDistributionTypeDef = TypedDict(
@@ -1771,14 +2172,25 @@
 
 class UpdateInfrastructureConfigurationRequestRequestTypeDef(
     _RequiredUpdateInfrastructureConfigurationRequestRequestTypeDef,
     _OptionalUpdateInfrastructureConfigurationRequestRequestTypeDef,
 ):
     pass
 
+ListImageScanFindingAggregationsResponseTypeDef = TypedDict(
+    "ListImageScanFindingAggregationsResponseTypeDef",
+    {
+        "requestId": str,
+        "aggregationType": str,
+        "responses": List[ImageScanFindingAggregationTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageSummaryTypeDef = TypedDict(
     "ImageSummaryTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ImageTypeType,
         "version": str,
@@ -1791,20 +2203,41 @@
         "tags": Dict[str, str],
         "buildType": BuildTypeType,
         "imageSource": ImageSourceType,
     },
     total=False,
 )
 
+ImageScanFindingTypeDef = TypedDict(
+    "ImageScanFindingTypeDef",
+    {
+        "awsAccountId": str,
+        "imageBuildVersionArn": str,
+        "imagePipelineArn": str,
+        "type": str,
+        "description": str,
+        "title": str,
+        "remediation": RemediationTypeDef,
+        "severity": str,
+        "firstObservedAt": datetime,
+        "updatedAt": datetime,
+        "inspectorScore": float,
+        "inspectorScoreDetails": InspectorScoreDetailsTypeDef,
+        "packageVulnerabilityDetails": PackageVulnerabilityDetailsTypeDef,
+        "fixAvailable": str,
+    },
+    total=False,
+)
+
 GetImageRecipeResponseTypeDef = TypedDict(
     "GetImageRecipeResponseTypeDef",
     {
         "requestId": str,
         "imageRecipe": ImageRecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerRecipeTypeDef = TypedDict(
     "ContainerRecipeTypeDef",
     {
         "arn": str,
@@ -1858,14 +2291,33 @@
 
 class CreateContainerRecipeRequestRequestTypeDef(
     _RequiredCreateContainerRecipeRequestRequestTypeDef,
     _OptionalCreateContainerRecipeRequestRequestTypeDef,
 ):
     pass
 
+GetImagePipelineResponseTypeDef = TypedDict(
+    "GetImagePipelineResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipeline": ImagePipelineTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImagePipelinesResponseTypeDef = TypedDict(
+    "ListImagePipelinesResponseTypeDef",
+    {
+        "requestId": str,
+        "imagePipelineList": List[ImagePipelineTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDistributionConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDistributionConfigurationRequestRequestTypeDef",
     {
         "name": str,
         "distributions": Sequence[DistributionTypeDef],
         "clientToken": str,
     },
@@ -1933,53 +2385,63 @@
     pass
 
 GetInfrastructureConfigurationResponseTypeDef = TypedDict(
     "GetInfrastructureConfigurationResponseTypeDef",
     {
         "requestId": str,
         "infrastructureConfiguration": InfrastructureConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImageBuildVersionsResponseTypeDef = TypedDict(
     "ListImageBuildVersionsResponseTypeDef",
     {
         "requestId": str,
         "imageSummaryList": List[ImageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImagePipelineImagesResponseTypeDef = TypedDict(
     "ListImagePipelineImagesResponseTypeDef",
     {
         "requestId": str,
         "imageSummaryList": List[ImageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImageScanFindingsResponseTypeDef = TypedDict(
+    "ListImageScanFindingsResponseTypeDef",
+    {
+        "requestId": str,
+        "findings": List[ImageScanFindingTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerRecipeResponseTypeDef = TypedDict(
     "GetContainerRecipeResponseTypeDef",
     {
         "requestId": str,
         "containerRecipe": ContainerRecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionConfigurationResponseTypeDef = TypedDict(
     "GetDistributionConfigurationResponseTypeDef",
     {
         "requestId": str,
         "distributionConfiguration": DistributionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageTypeDef = TypedDict(
     "ImageTypeDef",
     {
         "arn": str,
@@ -1998,19 +2460,21 @@
         "distributionConfiguration": DistributionConfigurationTypeDef,
         "imageTestsConfiguration": ImageTestsConfigurationTypeDef,
         "dateCreated": str,
         "outputResources": OutputResourcesTypeDef,
         "tags": Dict[str, str],
         "buildType": BuildTypeType,
         "imageSource": ImageSourceType,
+        "scanState": ImageScanStateTypeDef,
+        "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
     },
     total=False,
 )
 
 GetImageResponseTypeDef = TypedDict(
     "GetImageResponseTypeDef",
     {
         "requestId": str,
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/PKG-INFO` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-imagebuilder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.imagebuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.imagebuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-imagebuilder"></a>
 
 # types-aiobotocore-imagebuilder
 
 [![PyPI - types-aiobotocore-imagebuilder](https://img.shields.io/pypi/v/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-imagebuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-imagebuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-imagebuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-imagebuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.imagebuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
+[aiobotocore.imagebuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/imagebuilder.html#imagebuilder)
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
 [types-aiobotocore-imagebuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_imagebuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,21 +277,26 @@
     ComponentFormatType,
     ComponentStatusType,
     ComponentTypeType,
     ContainerRepositoryServiceType,
     ContainerTypeType,
     DiskImageFormatType,
     EbsVolumeTypeType,
+    ImageScanStatusType,
     ImageSourceType,
     ImageStatusType,
     ImageTypeType,
     OwnershipType,
     PipelineExecutionStartConditionType,
     PipelineStatusType,
     PlatformType,
+    WorkflowExecutionStatusType,
+    WorkflowStepExecutionRollbackStatusType,
+    WorkflowStepExecutionStatusType,
+    WorkflowTypeType,
     imagebuilderServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
 def check_value(value: BuildTypeType) -> bool:
@@ -303,201 +308,234 @@
 ### Typed dictionaries
 
 `types_aiobotocore_imagebuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_imagebuilder.type_defs import (
+    SeverityCountsTypeDef,
     SystemsManagerAgentTypeDef,
     LaunchPermissionConfigurationTypeDef,
     ImageStateTypeDef,
     CancelImageCreationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelImageCreationResponseTypeDef,
     ComponentParameterTypeDef,
     ComponentParameterDetailTypeDef,
     ComponentStateTypeDef,
     ComponentVersionTypeDef,
     TargetContainerRepositoryTypeDef,
     ContainerRecipeSummaryTypeDef,
     ContainerTypeDef,
     CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateContainerRecipeResponseTypeDef,
+    CreateDistributionConfigurationResponseTypeDef,
     ImageTestsConfigurationTypeDef,
     ScheduleTypeDef,
+    CreateImagePipelineResponseTypeDef,
+    CreateImageRecipeResponseTypeDef,
+    CreateImageResponseTypeDef,
     InstanceMetadataOptionsTypeDef,
+    CreateInfrastructureConfigurationResponseTypeDef,
+    CvssScoreAdjustmentTypeDef,
+    CvssScoreTypeDef,
     DeleteComponentRequestRequestTypeDef,
+    DeleteComponentResponseTypeDef,
     DeleteContainerRecipeRequestRequestTypeDef,
+    DeleteContainerRecipeResponseTypeDef,
     DeleteDistributionConfigurationRequestRequestTypeDef,
+    DeleteDistributionConfigurationResponseTypeDef,
     DeleteImagePipelineRequestRequestTypeDef,
+    DeleteImagePipelineResponseTypeDef,
     DeleteImageRecipeRequestRequestTypeDef,
+    DeleteImageRecipeResponseTypeDef,
     DeleteImageRequestRequestTypeDef,
+    DeleteImageResponseTypeDef,
     DeleteInfrastructureConfigurationRequestRequestTypeDef,
+    DeleteInfrastructureConfigurationResponseTypeDef,
     DistributionConfigurationSummaryTypeDef,
     LaunchTemplateConfigurationTypeDef,
     S3ExportConfigurationTypeDef,
     EbsInstanceBlockDeviceSpecificationTypeDef,
+    EcrConfigurationTypeDef,
     FastLaunchLaunchTemplateSpecificationTypeDef,
     FastLaunchSnapshotConfigurationTypeDef,
     FilterTypeDef,
     GetComponentPolicyRequestRequestTypeDef,
+    GetComponentPolicyResponseTypeDef,
     GetComponentRequestRequestTypeDef,
     GetContainerRecipePolicyRequestRequestTypeDef,
+    GetContainerRecipePolicyResponseTypeDef,
     GetContainerRecipeRequestRequestTypeDef,
     GetDistributionConfigurationRequestRequestTypeDef,
     GetImagePipelineRequestRequestTypeDef,
     GetImagePolicyRequestRequestTypeDef,
+    GetImagePolicyResponseTypeDef,
     GetImageRecipePolicyRequestRequestTypeDef,
+    GetImageRecipePolicyResponseTypeDef,
     GetImageRecipeRequestRequestTypeDef,
     GetImageRequestRequestTypeDef,
     GetInfrastructureConfigurationRequestRequestTypeDef,
+    GetWorkflowExecutionRequestRequestTypeDef,
+    GetWorkflowExecutionResponseTypeDef,
+    GetWorkflowStepExecutionRequestRequestTypeDef,
+    GetWorkflowStepExecutionResponseTypeDef,
     ImagePackageTypeDef,
     ImageRecipeSummaryTypeDef,
+    ImageScanFindingsFilterTypeDef,
+    ImageScanStateTypeDef,
     ImageVersionTypeDef,
     ImportComponentRequestRequestTypeDef,
+    ImportComponentResponseTypeDef,
     ImportVmImageRequestRequestTypeDef,
+    ImportVmImageResponseTypeDef,
     InfrastructureConfigurationSummaryTypeDef,
     ListComponentBuildVersionsRequestRequestTypeDef,
     ListImagePackagesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkflowExecutionsRequestRequestTypeDef,
+    WorkflowExecutionMetadataTypeDef,
+    ListWorkflowStepExecutionsRequestRequestTypeDef,
+    WorkflowStepMetadataTypeDef,
     S3LogsTypeDef,
+    VulnerablePackageTypeDef,
     PutComponentPolicyRequestRequestTypeDef,
+    PutComponentPolicyResponseTypeDef,
     PutContainerRecipePolicyRequestRequestTypeDef,
+    PutContainerRecipePolicyResponseTypeDef,
     PutImagePolicyRequestRequestTypeDef,
+    PutImagePolicyResponseTypeDef,
     PutImageRecipePolicyRequestRequestTypeDef,
+    PutImageRecipePolicyResponseTypeDef,
+    RemediationRecommendationTypeDef,
+    ResponseMetadataTypeDef,
     StartImagePipelineExecutionRequestRequestTypeDef,
+    StartImagePipelineExecutionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AdditionalInstanceConfigurationTypeDef,
-    AmiDistributionConfigurationTypeDef,
-    AmiTypeDef,
-    CancelImageCreationResponseTypeDef,
-    CreateComponentResponseTypeDef,
-    CreateContainerRecipeResponseTypeDef,
-    CreateDistributionConfigurationResponseTypeDef,
-    CreateImagePipelineResponseTypeDef,
-    CreateImageRecipeResponseTypeDef,
-    CreateImageResponseTypeDef,
-    CreateInfrastructureConfigurationResponseTypeDef,
-    DeleteComponentResponseTypeDef,
-    DeleteContainerRecipeResponseTypeDef,
-    DeleteDistributionConfigurationResponseTypeDef,
-    DeleteImagePipelineResponseTypeDef,
-    DeleteImageRecipeResponseTypeDef,
-    DeleteImageResponseTypeDef,
-    DeleteInfrastructureConfigurationResponseTypeDef,
-    GetComponentPolicyResponseTypeDef,
-    GetContainerRecipePolicyResponseTypeDef,
-    GetImagePolicyResponseTypeDef,
-    GetImageRecipePolicyResponseTypeDef,
-    ImportComponentResponseTypeDef,
-    ImportVmImageResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutComponentPolicyResponseTypeDef,
-    PutContainerRecipePolicyResponseTypeDef,
-    PutImagePolicyResponseTypeDef,
-    PutImageRecipePolicyResponseTypeDef,
-    StartImagePipelineExecutionResponseTypeDef,
     UpdateDistributionConfigurationResponseTypeDef,
     UpdateImagePipelineResponseTypeDef,
     UpdateInfrastructureConfigurationResponseTypeDef,
+    AccountAggregationTypeDef,
+    ImageAggregationTypeDef,
+    ImagePipelineAggregationTypeDef,
+    VulnerabilityIdAggregationTypeDef,
+    AdditionalInstanceConfigurationTypeDef,
+    AmiDistributionConfigurationTypeDef,
+    AmiTypeDef,
     ComponentConfigurationTypeDef,
     ComponentSummaryTypeDef,
     ComponentTypeDef,
     ListComponentsResponseTypeDef,
     ContainerDistributionConfigurationTypeDef,
     ListContainerRecipesResponseTypeDef,
-    CreateImageRequestRequestTypeDef,
-    CreateImagePipelineRequestRequestTypeDef,
-    ImagePipelineTypeDef,
-    UpdateImagePipelineRequestRequestTypeDef,
+    CvssScoreDetailsTypeDef,
     ListDistributionConfigurationsResponseTypeDef,
     InstanceBlockDeviceMappingTypeDef,
+    ImageScanningConfigurationTypeDef,
     FastLaunchConfigurationTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListContainerRecipesRequestRequestTypeDef,
     ListDistributionConfigurationsRequestRequestTypeDef,
     ListImageBuildVersionsRequestRequestTypeDef,
     ListImagePipelineImagesRequestRequestTypeDef,
     ListImagePipelinesRequestRequestTypeDef,
     ListImageRecipesRequestRequestTypeDef,
+    ListImageScanFindingAggregationsRequestRequestTypeDef,
     ListImagesRequestRequestTypeDef,
     ListInfrastructureConfigurationsRequestRequestTypeDef,
     ListImagePackagesResponseTypeDef,
     ListImageRecipesResponseTypeDef,
+    ListImageScanFindingsRequestRequestTypeDef,
     ListImagesResponseTypeDef,
     ListInfrastructureConfigurationsResponseTypeDef,
+    ListWorkflowExecutionsResponseTypeDef,
+    ListWorkflowStepExecutionsResponseTypeDef,
     LoggingTypeDef,
+    PackageVulnerabilityDetailsTypeDef,
+    RemediationTypeDef,
+    ImageScanFindingAggregationTypeDef,
     OutputResourcesTypeDef,
     ListComponentBuildVersionsResponseTypeDef,
     GetComponentResponseTypeDef,
-    GetImagePipelineResponseTypeDef,
-    ListImagePipelinesResponseTypeDef,
+    InspectorScoreDetailsTypeDef,
     CreateImageRecipeRequestRequestTypeDef,
     ImageRecipeTypeDef,
     InstanceConfigurationTypeDef,
+    CreateImagePipelineRequestRequestTypeDef,
+    CreateImageRequestRequestTypeDef,
+    ImagePipelineTypeDef,
+    UpdateImagePipelineRequestRequestTypeDef,
     DistributionTypeDef,
     CreateInfrastructureConfigurationRequestRequestTypeDef,
     InfrastructureConfigurationTypeDef,
     UpdateInfrastructureConfigurationRequestRequestTypeDef,
+    ListImageScanFindingAggregationsResponseTypeDef,
     ImageSummaryTypeDef,
+    ImageScanFindingTypeDef,
     GetImageRecipeResponseTypeDef,
     ContainerRecipeTypeDef,
     CreateContainerRecipeRequestRequestTypeDef,
+    GetImagePipelineResponseTypeDef,
+    ListImagePipelinesResponseTypeDef,
     CreateDistributionConfigurationRequestRequestTypeDef,
     DistributionConfigurationTypeDef,
     UpdateDistributionConfigurationRequestRequestTypeDef,
     GetInfrastructureConfigurationResponseTypeDef,
     ListImageBuildVersionsResponseTypeDef,
     ListImagePipelineImagesResponseTypeDef,
+    ListImageScanFindingsResponseTypeDef,
     GetContainerRecipeResponseTypeDef,
     GetDistributionConfigurationResponseTypeDef,
     ImageTypeDef,
     GetImageResponseTypeDef,
 )
 
 
-def get_structure() -> SystemsManagerAgentTypeDef:
+def get_structure() -> SeverityCountsTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-imagebuilder-2.5.0.post1/types_aiobotocore_imagebuilder.egg-info/SOURCES.txt` & `types-aiobotocore-imagebuilder-2.5.1/types_aiobotocore_imagebuilder.egg-info/SOURCES.txt`

 * *Files identical despite different names*

