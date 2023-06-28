# Comparing `tmp/types-aiobotocore-proton-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-proton-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-proton-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-proton-2.5.1.tar", last modified: Wed Jun 28 01:44:00 2023, max compression
```

## Comparing `types-aiobotocore-proton-2.5.0.post1.tar` & `types-aiobotocore-proton-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.723514 types-aiobotocore-proton-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    30488 2023-03-11 12:27:08.715514 types-aiobotocore-proton-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    28921 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.723514 types-aiobotocore-proton-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:20:07.000000 types-aiobotocore-proton-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.707514 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/
--rw-r--r--   0 runner    (1001) docker     (123)     7822 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7821 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    70485 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    70370 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15249 2023-03-11 12:20:09.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15247 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    26345 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    26322 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    98591 2023-03-11 12:20:12.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    98427 2023-03-11 12:20:09.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    10765 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    10755 2023-03-11 12:20:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.715514 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    30488 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      865 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.670195 types-aiobotocore-proton-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    31369 2023-06-28 01:44:00.670195 types-aiobotocore-proton-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    29808 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:00.670195 types-aiobotocore-proton-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.670195 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/
+-rw-r--r--   0 runner    (1001) docker     (123)     7822 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7821 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75675 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75552 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15582 2023-06-28 01:36:57.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15580 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    26161 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26139 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   105744 2023-06-28 01:36:58.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   105571 2023-06-28 01:36:57.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:54.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10765 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10755 2023-06-28 01:36:56.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.670195 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    31369 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      865 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:44:00.000000 types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/LICENSE` & `types-aiobotocore-proton-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-proton-2.5.0.post1/PKG-INFO` & `types-aiobotocore-proton-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-proton
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Proton 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Proton 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-proton"></a>
 
 # types-aiobotocore-proton
 
 [![PyPI - types-aiobotocore-proton](https://img.shields.io/pypi/v/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-proton?color=blue)](https://pypistats.org/packages/types-aiobotocore-proton)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Proton 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
+[aiobotocore.Proton 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
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
 [types-aiobotocore-proton docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/).
 
 See how it helps to find and fix potential bugs:
 
@@ -420,14 +420,16 @@
 ### Literals
 
 `types_aiobotocore_proton.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_proton.literals import (
+    BlockerStatusType,
+    BlockerTypeType,
     ComponentDeletedWaiterName,
     ComponentDeployedWaiterName,
     ComponentDeploymentUpdateTypeType,
     DeploymentStatusType,
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
@@ -478,30 +480,29 @@
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
 )
 
 
-def check_value(value: ComponentDeletedWaiterName) -> bool:
+def check_value(value: BlockerStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_proton.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_proton.type_defs import (
     AcceptEnvironmentAccountConnectionInputRequestTypeDef,
     EnvironmentAccountConnectionTypeDef,
-    ResponseMetadataTypeDef,
     RepositoryBranchTypeDef,
     CancelComponentDeploymentInputRequestTypeDef,
     ComponentTypeDef,
     CancelEnvironmentDeploymentInputRequestTypeDef,
     CancelServiceInstanceDeploymentInputRequestTypeDef,
     ServiceInstanceTypeDef,
     CancelServicePipelineDeploymentInputRequestTypeDef,
@@ -511,24 +512,27 @@
     ComponentSummaryTypeDef,
     ResourceCountsSummaryTypeDef,
     TagTypeDef,
     RepositoryBranchInputTypeDef,
     EnvironmentTemplateTypeDef,
     EnvironmentTemplateVersionTypeDef,
     RepositoryTypeDef,
+    CreateServiceSyncConfigInputRequestTypeDef,
+    ServiceSyncConfigTypeDef,
     ServiceTemplateTypeDef,
     CreateTemplateSyncConfigInputRequestTypeDef,
     TemplateSyncConfigTypeDef,
     DeleteComponentInputRequestTypeDef,
     DeleteEnvironmentAccountConnectionInputRequestTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DeleteEnvironmentTemplateInputRequestTypeDef,
     DeleteEnvironmentTemplateVersionInputRequestTypeDef,
     DeleteRepositoryInputRequestTypeDef,
     DeleteServiceInputRequestTypeDef,
+    DeleteServiceSyncConfigInputRequestTypeDef,
     DeleteServiceTemplateInputRequestTypeDef,
     DeleteServiceTemplateVersionInputRequestTypeDef,
     DeleteTemplateSyncConfigInputRequestTypeDef,
     EnvironmentAccountConnectionSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     EnvironmentTemplateFilterTypeDef,
     EnvironmentTemplateSummaryTypeDef,
@@ -539,59 +543,84 @@
     GetEnvironmentInputRequestTypeDef,
     GetEnvironmentTemplateInputRequestTypeDef,
     GetEnvironmentTemplateVersionInputRequestTypeDef,
     GetRepositoryInputRequestTypeDef,
     GetRepositorySyncStatusInputRequestTypeDef,
     GetServiceInputRequestTypeDef,
     GetServiceInstanceInputRequestTypeDef,
+    GetServiceInstanceSyncStatusInputRequestTypeDef,
+    RevisionTypeDef,
+    GetServiceSyncBlockerSummaryInputRequestTypeDef,
+    GetServiceSyncConfigInputRequestTypeDef,
     GetServiceTemplateInputRequestTypeDef,
     GetServiceTemplateVersionInputRequestTypeDef,
     GetTemplateSyncConfigInputRequestTypeDef,
     GetTemplateSyncStatusInputRequestTypeDef,
-    RevisionTypeDef,
-    PaginatorConfigTypeDef,
+    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
     ListComponentOutputsInputRequestTypeDef,
     OutputTypeDef,
+    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
     ListComponentProvisionedResourcesInputRequestTypeDef,
     ProvisionedResourceTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
     ListEnvironmentAccountConnectionsInputRequestTypeDef,
+    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
     ListEnvironmentOutputsInputRequestTypeDef,
+    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
     ListEnvironmentProvisionedResourcesInputRequestTypeDef,
+    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
     ListEnvironmentTemplateVersionsInputRequestTypeDef,
+    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
     ListEnvironmentTemplatesInputRequestTypeDef,
+    ListRepositoriesInputListRepositoriesPaginateTypeDef,
     ListRepositoriesInputRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
     ListRepositorySyncDefinitionsInputRequestTypeDef,
     RepositorySyncDefinitionTypeDef,
+    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
     ListServiceInstanceOutputsInputRequestTypeDef,
+    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
     ListServiceInstanceProvisionedResourcesInputRequestTypeDef,
     ListServiceInstancesFilterTypeDef,
     ServiceInstanceSummaryTypeDef,
+    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
     ListServicePipelineOutputsInputRequestTypeDef,
+    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
     ListServicePipelineProvisionedResourcesInputRequestTypeDef,
+    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
     ListServiceTemplateVersionsInputRequestTypeDef,
     ServiceTemplateVersionSummaryTypeDef,
+    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
     ListServiceTemplatesInputRequestTypeDef,
     ServiceTemplateSummaryTypeDef,
+    ListServicesInputListServicesPaginateTypeDef,
     ListServicesInputRequestTypeDef,
     ServiceSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     RejectEnvironmentAccountConnectionInputRequestTypeDef,
     RepositorySyncEventTypeDef,
     ResourceSyncEventTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectSourceTypeDef,
+    SyncBlockerContextTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateComponentInputRequestTypeDef,
     UpdateEnvironmentAccountConnectionInputRequestTypeDef,
     UpdateEnvironmentTemplateInputRequestTypeDef,
     UpdateEnvironmentTemplateVersionInputRequestTypeDef,
     UpdateServiceInputRequestTypeDef,
     UpdateServiceInstanceInputRequestTypeDef,
     UpdateServicePipelineInputRequestTypeDef,
+    UpdateServiceSyncBlockerInputRequestTypeDef,
+    UpdateServiceSyncConfigInputRequestTypeDef,
     UpdateServiceTemplateInputRequestTypeDef,
     UpdateTemplateSyncConfigInputRequestTypeDef,
     AcceptEnvironmentAccountConnectionOutputTypeDef,
     CreateEnvironmentAccountConnectionOutputTypeDef,
     DeleteEnvironmentAccountConnectionOutputTypeDef,
     GetEnvironmentAccountConnectionOutputTypeDef,
     RejectEnvironmentAccountConnectionOutputTypeDef,
@@ -600,28 +629,30 @@
     EnvironmentTypeDef,
     CancelComponentDeploymentOutputTypeDef,
     CreateComponentOutputTypeDef,
     DeleteComponentOutputTypeDef,
     GetComponentOutputTypeDef,
     UpdateComponentOutputTypeDef,
     CancelServiceInstanceDeploymentOutputTypeDef,
+    CreateServiceInstanceOutputTypeDef,
     GetServiceInstanceOutputTypeDef,
     UpdateServiceInstanceOutputTypeDef,
     CancelServicePipelineDeploymentOutputTypeDef,
     ServiceTypeDef,
     UpdateServicePipelineOutputTypeDef,
     UpdateServiceTemplateVersionInputRequestTypeDef,
     ServiceTemplateVersionTypeDef,
     ListComponentsOutputTypeDef,
     CountsSummaryTypeDef,
     CreateComponentInputRequestTypeDef,
     CreateEnvironmentAccountConnectionInputRequestTypeDef,
     CreateEnvironmentTemplateInputRequestTypeDef,
     CreateRepositoryInputRequestTypeDef,
     CreateServiceInputRequestTypeDef,
+    CreateServiceInstanceInputRequestTypeDef,
     CreateServiceTemplateInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     CreateEnvironmentTemplateOutputTypeDef,
@@ -631,56 +662,42 @@
     CreateEnvironmentTemplateVersionOutputTypeDef,
     DeleteEnvironmentTemplateVersionOutputTypeDef,
     GetEnvironmentTemplateVersionOutputTypeDef,
     UpdateEnvironmentTemplateVersionOutputTypeDef,
     CreateRepositoryOutputTypeDef,
     DeleteRepositoryOutputTypeDef,
     GetRepositoryOutputTypeDef,
+    CreateServiceSyncConfigOutputTypeDef,
+    DeleteServiceSyncConfigOutputTypeDef,
+    GetServiceSyncConfigOutputTypeDef,
+    UpdateServiceSyncConfigOutputTypeDef,
     CreateServiceTemplateOutputTypeDef,
     DeleteServiceTemplateOutputTypeDef,
     GetServiceTemplateOutputTypeDef,
     UpdateServiceTemplateOutputTypeDef,
     CreateTemplateSyncConfigOutputTypeDef,
     DeleteTemplateSyncConfigOutputTypeDef,
     GetTemplateSyncConfigOutputTypeDef,
     UpdateTemplateSyncConfigOutputTypeDef,
     ListEnvironmentAccountConnectionsOutputTypeDef,
     ListEnvironmentsOutputTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
     ListEnvironmentTemplatesOutputTypeDef,
     ListEnvironmentTemplateVersionsOutputTypeDef,
     GetComponentInputComponentDeletedWaitTypeDef,
     GetComponentInputComponentDeployedWaitTypeDef,
     GetEnvironmentInputEnvironmentDeployedWaitTypeDef,
     GetEnvironmentTemplateVersionInputEnvironmentTemplateVersionRegisteredWaitTypeDef,
     GetServiceInputServiceCreatedWaitTypeDef,
     GetServiceInputServiceDeletedWaitTypeDef,
     GetServiceInputServicePipelineDeployedWaitTypeDef,
     GetServiceInputServiceUpdatedWaitTypeDef,
     GetServiceInstanceInputServiceInstanceDeployedWaitTypeDef,
     GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
-    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
-    ListRepositoriesInputListRepositoriesPaginateTypeDef,
-    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
-    ListServicesInputListServicesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListEnvironmentOutputsOutputTypeDef,
     ListServiceInstanceOutputsOutputTypeDef,
     ListServicePipelineOutputsOutputTypeDef,
     NotifyResourceDeploymentStatusChangeInputRequestTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListEnvironmentProvisionedResourcesOutputTypeDef,
@@ -693,14 +710,15 @@
     ListServiceInstancesOutputTypeDef,
     ListServiceTemplateVersionsOutputTypeDef,
     ListServiceTemplatesOutputTypeDef,
     ListServicesOutputTypeDef,
     RepositorySyncAttemptTypeDef,
     ResourceSyncAttemptTypeDef,
     TemplateVersionSourceInputTypeDef,
+    SyncBlockerTypeDef,
     GetAccountSettingsOutputTypeDef,
     UpdateAccountSettingsOutputTypeDef,
     CancelEnvironmentDeploymentOutputTypeDef,
     CreateEnvironmentOutputTypeDef,
     DeleteEnvironmentOutputTypeDef,
     GetEnvironmentOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
@@ -710,60 +728,64 @@
     UpdateServiceOutputTypeDef,
     CreateServiceTemplateVersionOutputTypeDef,
     DeleteServiceTemplateVersionOutputTypeDef,
     GetServiceTemplateVersionOutputTypeDef,
     UpdateServiceTemplateVersionOutputTypeDef,
     GetResourcesSummaryOutputTypeDef,
     GetRepositorySyncStatusOutputTypeDef,
+    GetServiceInstanceSyncStatusOutputTypeDef,
     GetTemplateSyncStatusOutputTypeDef,
     CreateEnvironmentTemplateVersionInputRequestTypeDef,
     CreateServiceTemplateVersionInputRequestTypeDef,
+    ServiceSyncBlockerSummaryTypeDef,
+    UpdateServiceSyncBlockerOutputTypeDef,
+    GetServiceSyncBlockerSummaryOutputTypeDef,
 )
 
 
 def get_structure() -> AcceptEnvironmentAccountConnectionInputRequestTypeDef:
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/README.md` & `types-aiobotocore-proton-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-proton"></a>
 
 # types-aiobotocore-proton
 
 [![PyPI - types-aiobotocore-proton](https://img.shields.io/pypi/v/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-proton?color=blue)](https://pypistats.org/packages/types-aiobotocore-proton)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Proton 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
+[aiobotocore.Proton 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
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
 [types-aiobotocore-proton docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/).
 
 See how it helps to find and fix potential bugs:
 
@@ -387,14 +387,16 @@
 ### Literals
 
 `types_aiobotocore_proton.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_proton.literals import (
+    BlockerStatusType,
+    BlockerTypeType,
     ComponentDeletedWaiterName,
     ComponentDeployedWaiterName,
     ComponentDeploymentUpdateTypeType,
     DeploymentStatusType,
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
@@ -445,30 +447,29 @@
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
 )
 
 
-def check_value(value: ComponentDeletedWaiterName) -> bool:
+def check_value(value: BlockerStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_proton.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_proton.type_defs import (
     AcceptEnvironmentAccountConnectionInputRequestTypeDef,
     EnvironmentAccountConnectionTypeDef,
-    ResponseMetadataTypeDef,
     RepositoryBranchTypeDef,
     CancelComponentDeploymentInputRequestTypeDef,
     ComponentTypeDef,
     CancelEnvironmentDeploymentInputRequestTypeDef,
     CancelServiceInstanceDeploymentInputRequestTypeDef,
     ServiceInstanceTypeDef,
     CancelServicePipelineDeploymentInputRequestTypeDef,
@@ -478,24 +479,27 @@
     ComponentSummaryTypeDef,
     ResourceCountsSummaryTypeDef,
     TagTypeDef,
     RepositoryBranchInputTypeDef,
     EnvironmentTemplateTypeDef,
     EnvironmentTemplateVersionTypeDef,
     RepositoryTypeDef,
+    CreateServiceSyncConfigInputRequestTypeDef,
+    ServiceSyncConfigTypeDef,
     ServiceTemplateTypeDef,
     CreateTemplateSyncConfigInputRequestTypeDef,
     TemplateSyncConfigTypeDef,
     DeleteComponentInputRequestTypeDef,
     DeleteEnvironmentAccountConnectionInputRequestTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DeleteEnvironmentTemplateInputRequestTypeDef,
     DeleteEnvironmentTemplateVersionInputRequestTypeDef,
     DeleteRepositoryInputRequestTypeDef,
     DeleteServiceInputRequestTypeDef,
+    DeleteServiceSyncConfigInputRequestTypeDef,
     DeleteServiceTemplateInputRequestTypeDef,
     DeleteServiceTemplateVersionInputRequestTypeDef,
     DeleteTemplateSyncConfigInputRequestTypeDef,
     EnvironmentAccountConnectionSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     EnvironmentTemplateFilterTypeDef,
     EnvironmentTemplateSummaryTypeDef,
@@ -506,59 +510,84 @@
     GetEnvironmentInputRequestTypeDef,
     GetEnvironmentTemplateInputRequestTypeDef,
     GetEnvironmentTemplateVersionInputRequestTypeDef,
     GetRepositoryInputRequestTypeDef,
     GetRepositorySyncStatusInputRequestTypeDef,
     GetServiceInputRequestTypeDef,
     GetServiceInstanceInputRequestTypeDef,
+    GetServiceInstanceSyncStatusInputRequestTypeDef,
+    RevisionTypeDef,
+    GetServiceSyncBlockerSummaryInputRequestTypeDef,
+    GetServiceSyncConfigInputRequestTypeDef,
     GetServiceTemplateInputRequestTypeDef,
     GetServiceTemplateVersionInputRequestTypeDef,
     GetTemplateSyncConfigInputRequestTypeDef,
     GetTemplateSyncStatusInputRequestTypeDef,
-    RevisionTypeDef,
-    PaginatorConfigTypeDef,
+    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
     ListComponentOutputsInputRequestTypeDef,
     OutputTypeDef,
+    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
     ListComponentProvisionedResourcesInputRequestTypeDef,
     ProvisionedResourceTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
     ListEnvironmentAccountConnectionsInputRequestTypeDef,
+    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
     ListEnvironmentOutputsInputRequestTypeDef,
+    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
     ListEnvironmentProvisionedResourcesInputRequestTypeDef,
+    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
     ListEnvironmentTemplateVersionsInputRequestTypeDef,
+    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
     ListEnvironmentTemplatesInputRequestTypeDef,
+    ListRepositoriesInputListRepositoriesPaginateTypeDef,
     ListRepositoriesInputRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
     ListRepositorySyncDefinitionsInputRequestTypeDef,
     RepositorySyncDefinitionTypeDef,
+    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
     ListServiceInstanceOutputsInputRequestTypeDef,
+    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
     ListServiceInstanceProvisionedResourcesInputRequestTypeDef,
     ListServiceInstancesFilterTypeDef,
     ServiceInstanceSummaryTypeDef,
+    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
     ListServicePipelineOutputsInputRequestTypeDef,
+    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
     ListServicePipelineProvisionedResourcesInputRequestTypeDef,
+    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
     ListServiceTemplateVersionsInputRequestTypeDef,
     ServiceTemplateVersionSummaryTypeDef,
+    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
     ListServiceTemplatesInputRequestTypeDef,
     ServiceTemplateSummaryTypeDef,
+    ListServicesInputListServicesPaginateTypeDef,
     ListServicesInputRequestTypeDef,
     ServiceSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     RejectEnvironmentAccountConnectionInputRequestTypeDef,
     RepositorySyncEventTypeDef,
     ResourceSyncEventTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectSourceTypeDef,
+    SyncBlockerContextTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateComponentInputRequestTypeDef,
     UpdateEnvironmentAccountConnectionInputRequestTypeDef,
     UpdateEnvironmentTemplateInputRequestTypeDef,
     UpdateEnvironmentTemplateVersionInputRequestTypeDef,
     UpdateServiceInputRequestTypeDef,
     UpdateServiceInstanceInputRequestTypeDef,
     UpdateServicePipelineInputRequestTypeDef,
+    UpdateServiceSyncBlockerInputRequestTypeDef,
+    UpdateServiceSyncConfigInputRequestTypeDef,
     UpdateServiceTemplateInputRequestTypeDef,
     UpdateTemplateSyncConfigInputRequestTypeDef,
     AcceptEnvironmentAccountConnectionOutputTypeDef,
     CreateEnvironmentAccountConnectionOutputTypeDef,
     DeleteEnvironmentAccountConnectionOutputTypeDef,
     GetEnvironmentAccountConnectionOutputTypeDef,
     RejectEnvironmentAccountConnectionOutputTypeDef,
@@ -567,28 +596,30 @@
     EnvironmentTypeDef,
     CancelComponentDeploymentOutputTypeDef,
     CreateComponentOutputTypeDef,
     DeleteComponentOutputTypeDef,
     GetComponentOutputTypeDef,
     UpdateComponentOutputTypeDef,
     CancelServiceInstanceDeploymentOutputTypeDef,
+    CreateServiceInstanceOutputTypeDef,
     GetServiceInstanceOutputTypeDef,
     UpdateServiceInstanceOutputTypeDef,
     CancelServicePipelineDeploymentOutputTypeDef,
     ServiceTypeDef,
     UpdateServicePipelineOutputTypeDef,
     UpdateServiceTemplateVersionInputRequestTypeDef,
     ServiceTemplateVersionTypeDef,
     ListComponentsOutputTypeDef,
     CountsSummaryTypeDef,
     CreateComponentInputRequestTypeDef,
     CreateEnvironmentAccountConnectionInputRequestTypeDef,
     CreateEnvironmentTemplateInputRequestTypeDef,
     CreateRepositoryInputRequestTypeDef,
     CreateServiceInputRequestTypeDef,
+    CreateServiceInstanceInputRequestTypeDef,
     CreateServiceTemplateInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     CreateEnvironmentTemplateOutputTypeDef,
@@ -598,56 +629,42 @@
     CreateEnvironmentTemplateVersionOutputTypeDef,
     DeleteEnvironmentTemplateVersionOutputTypeDef,
     GetEnvironmentTemplateVersionOutputTypeDef,
     UpdateEnvironmentTemplateVersionOutputTypeDef,
     CreateRepositoryOutputTypeDef,
     DeleteRepositoryOutputTypeDef,
     GetRepositoryOutputTypeDef,
+    CreateServiceSyncConfigOutputTypeDef,
+    DeleteServiceSyncConfigOutputTypeDef,
+    GetServiceSyncConfigOutputTypeDef,
+    UpdateServiceSyncConfigOutputTypeDef,
     CreateServiceTemplateOutputTypeDef,
     DeleteServiceTemplateOutputTypeDef,
     GetServiceTemplateOutputTypeDef,
     UpdateServiceTemplateOutputTypeDef,
     CreateTemplateSyncConfigOutputTypeDef,
     DeleteTemplateSyncConfigOutputTypeDef,
     GetTemplateSyncConfigOutputTypeDef,
     UpdateTemplateSyncConfigOutputTypeDef,
     ListEnvironmentAccountConnectionsOutputTypeDef,
     ListEnvironmentsOutputTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
     ListEnvironmentTemplatesOutputTypeDef,
     ListEnvironmentTemplateVersionsOutputTypeDef,
     GetComponentInputComponentDeletedWaitTypeDef,
     GetComponentInputComponentDeployedWaitTypeDef,
     GetEnvironmentInputEnvironmentDeployedWaitTypeDef,
     GetEnvironmentTemplateVersionInputEnvironmentTemplateVersionRegisteredWaitTypeDef,
     GetServiceInputServiceCreatedWaitTypeDef,
     GetServiceInputServiceDeletedWaitTypeDef,
     GetServiceInputServicePipelineDeployedWaitTypeDef,
     GetServiceInputServiceUpdatedWaitTypeDef,
     GetServiceInstanceInputServiceInstanceDeployedWaitTypeDef,
     GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
-    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
-    ListRepositoriesInputListRepositoriesPaginateTypeDef,
-    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
-    ListServicesInputListServicesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListEnvironmentOutputsOutputTypeDef,
     ListServiceInstanceOutputsOutputTypeDef,
     ListServicePipelineOutputsOutputTypeDef,
     NotifyResourceDeploymentStatusChangeInputRequestTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListEnvironmentProvisionedResourcesOutputTypeDef,
@@ -660,14 +677,15 @@
     ListServiceInstancesOutputTypeDef,
     ListServiceTemplateVersionsOutputTypeDef,
     ListServiceTemplatesOutputTypeDef,
     ListServicesOutputTypeDef,
     RepositorySyncAttemptTypeDef,
     ResourceSyncAttemptTypeDef,
     TemplateVersionSourceInputTypeDef,
+    SyncBlockerTypeDef,
     GetAccountSettingsOutputTypeDef,
     UpdateAccountSettingsOutputTypeDef,
     CancelEnvironmentDeploymentOutputTypeDef,
     CreateEnvironmentOutputTypeDef,
     DeleteEnvironmentOutputTypeDef,
     GetEnvironmentOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
@@ -677,60 +695,64 @@
     UpdateServiceOutputTypeDef,
     CreateServiceTemplateVersionOutputTypeDef,
     DeleteServiceTemplateVersionOutputTypeDef,
     GetServiceTemplateVersionOutputTypeDef,
     UpdateServiceTemplateVersionOutputTypeDef,
     GetResourcesSummaryOutputTypeDef,
     GetRepositorySyncStatusOutputTypeDef,
+    GetServiceInstanceSyncStatusOutputTypeDef,
     GetTemplateSyncStatusOutputTypeDef,
     CreateEnvironmentTemplateVersionInputRequestTypeDef,
     CreateServiceTemplateVersionInputRequestTypeDef,
+    ServiceSyncBlockerSummaryTypeDef,
+    UpdateServiceSyncBlockerOutputTypeDef,
+    GetServiceSyncBlockerSummaryOutputTypeDef,
 )
 
 
 def get_structure() -> AcceptEnvironmentAccountConnectionInputRequestTypeDef:
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/setup.py` & `types-aiobotocore-proton-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-proton.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-proton",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_proton"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Proton 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Proton 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/"
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__init__.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__init__.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/__main__.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Proton 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Proton 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton\nOther"
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/client.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/client.py`

 * *Files 5% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesSortByType,
     RepositoryProviderType,
     ResourceDeploymentStatusType,
     SortOrderType,
+    SyncTypeType,
     TemplateTypeType,
     TemplateVersionStatusType,
 )
 from .paginator import (
     ListComponentOutputsPaginator,
     ListComponentProvisionedResourcesPaginator,
     ListComponentsPaginator,
@@ -63,40 +64,46 @@
     CompatibleEnvironmentTemplateInputTypeDef,
     CreateComponentOutputTypeDef,
     CreateEnvironmentAccountConnectionOutputTypeDef,
     CreateEnvironmentOutputTypeDef,
     CreateEnvironmentTemplateOutputTypeDef,
     CreateEnvironmentTemplateVersionOutputTypeDef,
     CreateRepositoryOutputTypeDef,
+    CreateServiceInstanceOutputTypeDef,
     CreateServiceOutputTypeDef,
+    CreateServiceSyncConfigOutputTypeDef,
     CreateServiceTemplateOutputTypeDef,
     CreateServiceTemplateVersionOutputTypeDef,
     CreateTemplateSyncConfigOutputTypeDef,
     DeleteComponentOutputTypeDef,
     DeleteEnvironmentAccountConnectionOutputTypeDef,
     DeleteEnvironmentOutputTypeDef,
     DeleteEnvironmentTemplateOutputTypeDef,
     DeleteEnvironmentTemplateVersionOutputTypeDef,
     DeleteRepositoryOutputTypeDef,
     DeleteServiceOutputTypeDef,
+    DeleteServiceSyncConfigOutputTypeDef,
     DeleteServiceTemplateOutputTypeDef,
     DeleteServiceTemplateVersionOutputTypeDef,
     DeleteTemplateSyncConfigOutputTypeDef,
     EnvironmentTemplateFilterTypeDef,
     GetAccountSettingsOutputTypeDef,
     GetComponentOutputTypeDef,
     GetEnvironmentAccountConnectionOutputTypeDef,
     GetEnvironmentOutputTypeDef,
     GetEnvironmentTemplateOutputTypeDef,
     GetEnvironmentTemplateVersionOutputTypeDef,
     GetRepositoryOutputTypeDef,
     GetRepositorySyncStatusOutputTypeDef,
     GetResourcesSummaryOutputTypeDef,
     GetServiceInstanceOutputTypeDef,
+    GetServiceInstanceSyncStatusOutputTypeDef,
     GetServiceOutputTypeDef,
+    GetServiceSyncBlockerSummaryOutputTypeDef,
+    GetServiceSyncConfigOutputTypeDef,
     GetServiceTemplateOutputTypeDef,
     GetServiceTemplateVersionOutputTypeDef,
     GetTemplateSyncConfigOutputTypeDef,
     GetTemplateSyncStatusOutputTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListComponentsOutputTypeDef,
@@ -128,14 +135,16 @@
     UpdateEnvironmentAccountConnectionOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
     UpdateEnvironmentTemplateOutputTypeDef,
     UpdateEnvironmentTemplateVersionOutputTypeDef,
     UpdateServiceInstanceOutputTypeDef,
     UpdateServiceOutputTypeDef,
     UpdateServicePipelineOutputTypeDef,
+    UpdateServiceSyncBlockerOutputTypeDef,
+    UpdateServiceSyncConfigOutputTypeDef,
     UpdateServiceTemplateOutputTypeDef,
     UpdateServiceTemplateVersionOutputTypeDef,
     UpdateTemplateSyncConfigOutputTypeDef,
 )
 from .waiter import (
     ComponentDeletedWaiter,
     ComponentDeployedWaiter,
@@ -266,14 +275,15 @@
 
     async def create_component(
         self,
         *,
         manifest: str,
         name: str,
         templateFile: str,
+        clientToken: str = ...,
         description: str = ...,
         environmentName: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
         serviceSpec: str = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> CreateComponentOutputTypeDef:
@@ -394,14 +404,48 @@
         """
         Create an Proton service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service)
         """
 
+    async def create_service_instance(
+        self,
+        *,
+        name: str,
+        serviceName: str,
+        spec: str,
+        clientToken: str = ...,
+        tags: Sequence[TagTypeDef] = ...,
+        templateMajorVersion: str = ...,
+        templateMinorVersion: str = ...
+    ) -> CreateServiceInstanceOutputTypeDef:
+        """
+        Create a service instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service_instance)
+        """
+
+    async def create_service_sync_config(
+        self,
+        *,
+        branch: str,
+        filePath: str,
+        repositoryName: str,
+        repositoryProvider: RepositoryProviderType,
+        serviceName: str
+    ) -> CreateServiceSyncConfigOutputTypeDef:
+        """
+        Create the Proton Ops configuration file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service_sync_config)
+        """
+
     async def create_service_template(
         self,
         *,
         name: str,
         description: str = ...,
         displayName: str = ...,
         encryptionKey: str = ...,
@@ -514,14 +558,24 @@
         """
         Delete a service, with its instances and pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service)
         """
 
+    async def delete_service_sync_config(
+        self, *, serviceName: str
+    ) -> DeleteServiceSyncConfigOutputTypeDef:
+        """
+        Delete the Proton Ops file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service_sync_config)
+        """
+
     async def delete_service_template(self, *, name: str) -> DeleteServiceTemplateOutputTypeDef:
         """
         If no other major or minor versions of the service template exist, delete the
         service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service_template)
@@ -627,15 +681,15 @@
 
     async def get_repository_sync_status(
         self,
         *,
         branch: str,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"]
+        syncType: SyncTypeType
     ) -> GetRepositorySyncStatusOutputTypeDef:
         """
         Get the sync status of a repository used for Proton template sync.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_repository_sync_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_repository_sync_status)
         """
@@ -662,14 +716,44 @@
         """
         Get detailed data for a service instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_instance)
         """
 
+    async def get_service_instance_sync_status(
+        self, *, serviceInstanceName: str, serviceName: str
+    ) -> GetServiceInstanceSyncStatusOutputTypeDef:
+        """
+        Get the status of the synced service instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_instance_sync_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_instance_sync_status)
+        """
+
+    async def get_service_sync_blocker_summary(
+        self, *, serviceName: str, serviceInstanceName: str = ...
+    ) -> GetServiceSyncBlockerSummaryOutputTypeDef:
+        """
+        Get detailed data for the service sync blocker summary.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_sync_blocker_summary)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_sync_blocker_summary)
+        """
+
+    async def get_service_sync_config(
+        self, *, serviceName: str
+    ) -> GetServiceSyncConfigOutputTypeDef:
+        """
+        Get detailed information for the service sync configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_sync_config)
+        """
+
     async def get_service_template(self, *, name: str) -> GetServiceTemplateOutputTypeDef:
         """
         Get detailed data for a service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_template)
         """
@@ -826,15 +910,15 @@
         """
 
     async def list_repository_sync_definitions(
         self,
         *,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"],
+        syncType: SyncTypeType,
         nextToken: str = ...
     ) -> ListRepositorySyncDefinitionsOutputTypeDef:
         """
         List repository sync definitions with detail data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.list_repository_sync_definitions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#list_repository_sync_definitions)
@@ -1003,14 +1087,15 @@
         """
 
     async def update_component(
         self,
         *,
         deploymentType: ComponentDeploymentUpdateTypeType,
         name: str,
+        clientToken: str = ...,
         description: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
         serviceSpec: str = ...,
         templateFile: str = ...
     ) -> UpdateComponentOutputTypeDef:
         """
@@ -1096,14 +1181,15 @@
 
     async def update_service_instance(
         self,
         *,
         deploymentType: DeploymentUpdateTypeType,
         name: str,
         serviceName: str,
+        clientToken: str = ...,
         spec: str = ...,
         templateMajorVersion: str = ...,
         templateMinorVersion: str = ...
     ) -> UpdateServiceInstanceOutputTypeDef:
         """
         Update a service instance.
 
@@ -1123,14 +1209,40 @@
         """
         Update the service pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_pipeline)
         """
 
+    async def update_service_sync_blocker(
+        self, *, id: str, resolvedReason: str
+    ) -> UpdateServiceSyncBlockerOutputTypeDef:
+        """
+        Update the service sync blocker by resolving it.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_sync_blocker)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_sync_blocker)
+        """
+
+    async def update_service_sync_config(
+        self,
+        *,
+        branch: str,
+        filePath: str,
+        repositoryName: str,
+        repositoryProvider: RepositoryProviderType,
+        serviceName: str
+    ) -> UpdateServiceSyncConfigOutputTypeDef:
+        """
+        Update the Proton Ops config file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_sync_config)
+        """
+
     async def update_service_template(
         self, *, name: str, description: str = ..., displayName: str = ...
     ) -> UpdateServiceTemplateOutputTypeDef:
         """
         Update a service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_template)
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/client.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/client.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesSortByType,
     RepositoryProviderType,
     ResourceDeploymentStatusType,
     SortOrderType,
+    SyncTypeType,
     TemplateTypeType,
     TemplateVersionStatusType,
 )
 from .paginator import (
     ListComponentOutputsPaginator,
     ListComponentProvisionedResourcesPaginator,
     ListComponentsPaginator,
@@ -63,40 +64,46 @@
     CompatibleEnvironmentTemplateInputTypeDef,
     CreateComponentOutputTypeDef,
     CreateEnvironmentAccountConnectionOutputTypeDef,
     CreateEnvironmentOutputTypeDef,
     CreateEnvironmentTemplateOutputTypeDef,
     CreateEnvironmentTemplateVersionOutputTypeDef,
     CreateRepositoryOutputTypeDef,
+    CreateServiceInstanceOutputTypeDef,
     CreateServiceOutputTypeDef,
+    CreateServiceSyncConfigOutputTypeDef,
     CreateServiceTemplateOutputTypeDef,
     CreateServiceTemplateVersionOutputTypeDef,
     CreateTemplateSyncConfigOutputTypeDef,
     DeleteComponentOutputTypeDef,
     DeleteEnvironmentAccountConnectionOutputTypeDef,
     DeleteEnvironmentOutputTypeDef,
     DeleteEnvironmentTemplateOutputTypeDef,
     DeleteEnvironmentTemplateVersionOutputTypeDef,
     DeleteRepositoryOutputTypeDef,
     DeleteServiceOutputTypeDef,
+    DeleteServiceSyncConfigOutputTypeDef,
     DeleteServiceTemplateOutputTypeDef,
     DeleteServiceTemplateVersionOutputTypeDef,
     DeleteTemplateSyncConfigOutputTypeDef,
     EnvironmentTemplateFilterTypeDef,
     GetAccountSettingsOutputTypeDef,
     GetComponentOutputTypeDef,
     GetEnvironmentAccountConnectionOutputTypeDef,
     GetEnvironmentOutputTypeDef,
     GetEnvironmentTemplateOutputTypeDef,
     GetEnvironmentTemplateVersionOutputTypeDef,
     GetRepositoryOutputTypeDef,
     GetRepositorySyncStatusOutputTypeDef,
     GetResourcesSummaryOutputTypeDef,
     GetServiceInstanceOutputTypeDef,
+    GetServiceInstanceSyncStatusOutputTypeDef,
     GetServiceOutputTypeDef,
+    GetServiceSyncBlockerSummaryOutputTypeDef,
+    GetServiceSyncConfigOutputTypeDef,
     GetServiceTemplateOutputTypeDef,
     GetServiceTemplateVersionOutputTypeDef,
     GetTemplateSyncConfigOutputTypeDef,
     GetTemplateSyncStatusOutputTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListComponentsOutputTypeDef,
@@ -128,14 +135,16 @@
     UpdateEnvironmentAccountConnectionOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
     UpdateEnvironmentTemplateOutputTypeDef,
     UpdateEnvironmentTemplateVersionOutputTypeDef,
     UpdateServiceInstanceOutputTypeDef,
     UpdateServiceOutputTypeDef,
     UpdateServicePipelineOutputTypeDef,
+    UpdateServiceSyncBlockerOutputTypeDef,
+    UpdateServiceSyncConfigOutputTypeDef,
     UpdateServiceTemplateOutputTypeDef,
     UpdateServiceTemplateVersionOutputTypeDef,
     UpdateTemplateSyncConfigOutputTypeDef,
 )
 from .waiter import (
     ComponentDeletedWaiter,
     ComponentDeployedWaiter,
@@ -254,14 +263,15 @@
         """
     async def create_component(
         self,
         *,
         manifest: str,
         name: str,
         templateFile: str,
+        clientToken: str = ...,
         description: str = ...,
         environmentName: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
         serviceSpec: str = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> CreateComponentOutputTypeDef:
@@ -375,14 +385,46 @@
     ) -> CreateServiceOutputTypeDef:
         """
         Create an Proton service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service)
         """
+    async def create_service_instance(
+        self,
+        *,
+        name: str,
+        serviceName: str,
+        spec: str,
+        clientToken: str = ...,
+        tags: Sequence[TagTypeDef] = ...,
+        templateMajorVersion: str = ...,
+        templateMinorVersion: str = ...
+    ) -> CreateServiceInstanceOutputTypeDef:
+        """
+        Create a service instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service_instance)
+        """
+    async def create_service_sync_config(
+        self,
+        *,
+        branch: str,
+        filePath: str,
+        repositoryName: str,
+        repositoryProvider: RepositoryProviderType,
+        serviceName: str
+    ) -> CreateServiceSyncConfigOutputTypeDef:
+        """
+        Create the Proton Ops configuration file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.create_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#create_service_sync_config)
+        """
     async def create_service_template(
         self,
         *,
         name: str,
         description: str = ...,
         displayName: str = ...,
         encryptionKey: str = ...,
@@ -485,14 +527,23 @@
     async def delete_service(self, *, name: str) -> DeleteServiceOutputTypeDef:
         """
         Delete a service, with its instances and pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service)
         """
+    async def delete_service_sync_config(
+        self, *, serviceName: str
+    ) -> DeleteServiceSyncConfigOutputTypeDef:
+        """
+        Delete the Proton Ops file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service_sync_config)
+        """
     async def delete_service_template(self, *, name: str) -> DeleteServiceTemplateOutputTypeDef:
         """
         If no other major or minor versions of the service template exist, delete the
         service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.delete_service_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#delete_service_template)
@@ -587,15 +638,15 @@
         """
     async def get_repository_sync_status(
         self,
         *,
         branch: str,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"]
+        syncType: SyncTypeType
     ) -> GetRepositorySyncStatusOutputTypeDef:
         """
         Get the sync status of a repository used for Proton template sync.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_repository_sync_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_repository_sync_status)
         """
@@ -618,14 +669,41 @@
     ) -> GetServiceInstanceOutputTypeDef:
         """
         Get detailed data for a service instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_instance)
         """
+    async def get_service_instance_sync_status(
+        self, *, serviceInstanceName: str, serviceName: str
+    ) -> GetServiceInstanceSyncStatusOutputTypeDef:
+        """
+        Get the status of the synced service instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_instance_sync_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_instance_sync_status)
+        """
+    async def get_service_sync_blocker_summary(
+        self, *, serviceName: str, serviceInstanceName: str = ...
+    ) -> GetServiceSyncBlockerSummaryOutputTypeDef:
+        """
+        Get detailed data for the service sync blocker summary.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_sync_blocker_summary)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_sync_blocker_summary)
+        """
+    async def get_service_sync_config(
+        self, *, serviceName: str
+    ) -> GetServiceSyncConfigOutputTypeDef:
+        """
+        Get detailed information for the service sync configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_sync_config)
+        """
     async def get_service_template(self, *, name: str) -> GetServiceTemplateOutputTypeDef:
         """
         Get detailed data for a service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.get_service_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#get_service_template)
         """
@@ -768,15 +846,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#list_repositories)
         """
     async def list_repository_sync_definitions(
         self,
         *,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"],
+        syncType: SyncTypeType,
         nextToken: str = ...
     ) -> ListRepositorySyncDefinitionsOutputTypeDef:
         """
         List repository sync definitions with detail data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.list_repository_sync_definitions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#list_repository_sync_definitions)
@@ -930,14 +1008,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_account_settings)
         """
     async def update_component(
         self,
         *,
         deploymentType: ComponentDeploymentUpdateTypeType,
         name: str,
+        clientToken: str = ...,
         description: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
         serviceSpec: str = ...,
         templateFile: str = ...
     ) -> UpdateComponentOutputTypeDef:
         """
@@ -1017,14 +1096,15 @@
         """
     async def update_service_instance(
         self,
         *,
         deploymentType: DeploymentUpdateTypeType,
         name: str,
         serviceName: str,
+        clientToken: str = ...,
         spec: str = ...,
         templateMajorVersion: str = ...,
         templateMinorVersion: str = ...
     ) -> UpdateServiceInstanceOutputTypeDef:
         """
         Update a service instance.
 
@@ -1042,14 +1122,38 @@
     ) -> UpdateServicePipelineOutputTypeDef:
         """
         Update the service pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_pipeline)
         """
+    async def update_service_sync_blocker(
+        self, *, id: str, resolvedReason: str
+    ) -> UpdateServiceSyncBlockerOutputTypeDef:
+        """
+        Update the service sync blocker by resolving it.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_sync_blocker)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_sync_blocker)
+        """
+    async def update_service_sync_config(
+        self,
+        *,
+        branch: str,
+        filePath: str,
+        repositoryName: str,
+        repositoryProvider: RepositoryProviderType,
+        serviceName: str
+    ) -> UpdateServiceSyncConfigOutputTypeDef:
+        """
+        Update the Proton Ops config file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_sync_config)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/client/#update_service_sync_config)
+        """
     async def update_service_template(
         self, *, name: str, description: str = ..., displayName: str = ...
     ) -> UpdateServiceTemplateOutputTypeDef:
         """
         Update a service template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Client.update_service_template)
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/literals.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,28 +2,30 @@
 Type annotations for proton service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_proton.literals import ComponentDeletedWaiterName
+    from types_aiobotocore_proton.literals import BlockerStatusType
 
-    data: ComponentDeletedWaiterName = "component_deleted"
+    data: BlockerStatusType = "ACTIVE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "BlockerStatusType",
+    "BlockerTypeType",
     "ComponentDeletedWaiterName",
     "ComponentDeployedWaiterName",
     "ComponentDeploymentUpdateTypeType",
     "DeploymentStatusType",
     "DeploymentUpdateTypeType",
     "EnvironmentAccountConnectionRequesterAccountTypeType",
     "EnvironmentAccountConnectionStatusType",
@@ -74,14 +76,16 @@
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
 
+BlockerStatusType = Literal["ACTIVE", "RESOLVED"]
+BlockerTypeType = Literal["AUTOMATED"]
 ComponentDeletedWaiterName = Literal["component_deleted"]
 ComponentDeployedWaiterName = Literal["component_deployed"]
 ComponentDeploymentUpdateTypeType = Literal["CURRENT_VERSION", "NONE"]
 DeploymentStatusType = Literal[
     "CANCELLED",
     "CANCELLING",
     "DELETE_COMPLETE",
@@ -169,15 +173,15 @@
     "UPDATE_FAILED_CLEANUP_IN_PROGRESS",
     "UPDATE_IN_PROGRESS",
 ]
 ServiceTemplateSupportedComponentSourceTypeType = Literal["DIRECTLY_DEFINED"]
 ServiceTemplateVersionRegisteredWaiterName = Literal["service_template_version_registered"]
 ServiceUpdatedWaiterName = Literal["service_updated"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
-SyncTypeType = Literal["TEMPLATE_SYNC"]
+SyncTypeType = Literal["SERVICE_SYNC", "TEMPLATE_SYNC"]
 TemplateTypeType = Literal["ENVIRONMENT", "SERVICE"]
 TemplateVersionStatusType = Literal[
     "DRAFT", "PUBLISHED", "REGISTRATION_FAILED", "REGISTRATION_IN_PROGRESS"
 ]
 ProtonServiceName = Literal["proton"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -237,14 +241,15 @@
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
@@ -323,14 +328,15 @@
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
@@ -341,14 +347,15 @@
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
@@ -384,14 +391,15 @@
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
@@ -410,16 +418,19 @@
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
@@ -503,15 +514,17 @@
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/literals.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,27 +2,29 @@
 Type annotations for proton service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_proton.literals import ComponentDeletedWaiterName
+    from types_aiobotocore_proton.literals import BlockerStatusType
 
-    data: ComponentDeletedWaiterName = "component_deleted"
+    data: BlockerStatusType = "ACTIVE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "BlockerStatusType",
+    "BlockerTypeType",
     "ComponentDeletedWaiterName",
     "ComponentDeployedWaiterName",
     "ComponentDeploymentUpdateTypeType",
     "DeploymentStatusType",
     "DeploymentUpdateTypeType",
     "EnvironmentAccountConnectionRequesterAccountTypeType",
     "EnvironmentAccountConnectionStatusType",
@@ -72,14 +74,16 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+BlockerStatusType = Literal["ACTIVE", "RESOLVED"]
+BlockerTypeType = Literal["AUTOMATED"]
 ComponentDeletedWaiterName = Literal["component_deleted"]
 ComponentDeployedWaiterName = Literal["component_deployed"]
 ComponentDeploymentUpdateTypeType = Literal["CURRENT_VERSION", "NONE"]
 DeploymentStatusType = Literal[
     "CANCELLED",
     "CANCELLING",
     "DELETE_COMPLETE",
@@ -167,15 +171,15 @@
     "UPDATE_FAILED_CLEANUP_IN_PROGRESS",
     "UPDATE_IN_PROGRESS",
 ]
 ServiceTemplateSupportedComponentSourceTypeType = Literal["DIRECTLY_DEFINED"]
 ServiceTemplateVersionRegisteredWaiterName = Literal["service_template_version_registered"]
 ServiceUpdatedWaiterName = Literal["service_updated"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
-SyncTypeType = Literal["TEMPLATE_SYNC"]
+SyncTypeType = Literal["SERVICE_SYNC", "TEMPLATE_SYNC"]
 TemplateTypeType = Literal["ENVIRONMENT", "SERVICE"]
 TemplateVersionStatusType = Literal[
     "DRAFT", "PUBLISHED", "REGISTRATION_FAILED", "REGISTRATION_IN_PROGRESS"
 ]
 ProtonServiceName = Literal["proton"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -235,14 +239,15 @@
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
@@ -321,14 +326,15 @@
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
@@ -339,14 +345,15 @@
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
@@ -382,14 +389,15 @@
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
@@ -408,16 +416,19 @@
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
@@ -501,15 +512,17 @@
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/paginator.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -54,26 +54,26 @@
         list_service_pipeline_provisioned_resources_paginator: ListServicePipelineProvisionedResourcesPaginator = client.get_paginator("list_service_pipeline_provisioned_resources")
         list_service_template_versions_paginator: ListServiceTemplateVersionsPaginator = client.get_paginator("list_service_template_versions")
         list_service_templates_paginator: ListServiceTemplatesPaginator = client.get_paginator("list_service_templates")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesSortByType,
     RepositoryProviderType,
     SortOrderType,
+    SyncTypeType,
 )
 from .type_defs import (
     EnvironmentTemplateFilterTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListComponentsOutputTypeDef,
     ListEnvironmentAccountConnectionsOutputTypeDef,
@@ -93,24 +93,14 @@
     ListServicesOutputTypeDef,
     ListServiceTemplatesOutputTypeDef,
     ListServiceTemplateVersionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-
-
 __all__ = (
     "ListComponentOutputsPaginator",
     "ListComponentProvisionedResourcesPaginator",
     "ListComponentsPaginator",
     "ListEnvironmentAccountConnectionsPaginator",
     "ListEnvironmentOutputsPaginator",
     "ListEnvironmentProvisionedResourcesPaginator",
@@ -144,30 +134,30 @@
 class ListComponentOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentoutputspaginator)
     """
 
     def paginate(
-        self, *, componentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, componentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentoutputspaginator)
         """
 
 
 class ListComponentProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, componentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, componentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentprovisionedresourcespaginator)
         """
 
 
@@ -179,15 +169,15 @@
 
     def paginate(
         self,
         *,
         environmentName: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentspaginator)
         """
 
 
@@ -199,45 +189,45 @@
 
     def paginate(
         self,
         *,
         requestedBy: EnvironmentAccountConnectionRequesterAccountTypeType,
         environmentName: str = ...,
         statuses: Sequence[EnvironmentAccountConnectionStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentAccountConnectionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentAccountConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentaccountconnectionspaginator)
         """
 
 
 class ListEnvironmentOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentoutputspaginator)
     """
 
     def paginate(
-        self, *, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentoutputspaginator)
         """
 
 
 class ListEnvironmentProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentprovisionedresourcespaginator)
         """
 
 
@@ -248,30 +238,30 @@
     """
 
     def paginate(
         self,
         *,
         templateName: str,
         majorVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentTemplateVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplateversionspaginator)
         """
 
 
 class ListEnvironmentTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplatespaginator)
         """
 
 
@@ -281,30 +271,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         environmentTemplates: Sequence[EnvironmentTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentspaginator)
         """
 
 
 class ListRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositoriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositoriespaginator)
         """
 
 
@@ -315,16 +305,16 @@
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        syncType: SyncTypeType,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositorySyncDefinitionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositorySyncDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositorysyncdefinitionspaginator)
         """
 
 
@@ -335,15 +325,15 @@
     """
 
     def paginate(
         self,
         *,
         serviceInstanceName: str,
         serviceName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstanceOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstanceOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstanceoutputspaginator)
         """
 
 
@@ -354,15 +344,15 @@
     """
 
     def paginate(
         self,
         *,
         serviceInstanceName: str,
         serviceName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstanceProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstanceProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstanceprovisionedresourcespaginator)
         """
 
 
@@ -375,45 +365,45 @@
     def paginate(
         self,
         *,
         filters: Sequence[ListServiceInstancesFilterTypeDef] = ...,
         serviceName: str = ...,
         sortBy: ListServiceInstancesSortByType = ...,
         sortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstancespaginator)
         """
 
 
 class ListServicePipelineOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineoutputspaginator)
     """
 
     def paginate(
-        self, *, serviceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serviceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicePipelineOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineoutputspaginator)
         """
 
 
 class ListServicePipelineProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, serviceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serviceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicePipelineProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineprovisionedresourcespaginator)
         """
 
 
@@ -424,58 +414,58 @@
     """
 
     def paginate(
         self,
         *,
         templateName: str,
         majorVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceTemplateVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplateversionspaginator)
         """
 
 
 class ListServiceTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplatespaginator)
         """
 
 
 class ListServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/paginator.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -54,26 +54,26 @@
         list_service_pipeline_provisioned_resources_paginator: ListServicePipelineProvisionedResourcesPaginator = client.get_paginator("list_service_pipeline_provisioned_resources")
         list_service_template_versions_paginator: ListServiceTemplateVersionsPaginator = client.get_paginator("list_service_template_versions")
         list_service_templates_paginator: ListServiceTemplatesPaginator = client.get_paginator("list_service_templates")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesSortByType,
     RepositoryProviderType,
     SortOrderType,
+    SyncTypeType,
 )
 from .type_defs import (
     EnvironmentTemplateFilterTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListComponentsOutputTypeDef,
     ListEnvironmentAccountConnectionsOutputTypeDef,
@@ -93,23 +93,14 @@
     ListServicesOutputTypeDef,
     ListServiceTemplatesOutputTypeDef,
     ListServiceTemplateVersionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-
 __all__ = (
     "ListComponentOutputsPaginator",
     "ListComponentProvisionedResourcesPaginator",
     "ListComponentsPaginator",
     "ListEnvironmentAccountConnectionsPaginator",
     "ListEnvironmentOutputsPaginator",
     "ListEnvironmentProvisionedResourcesPaginator",
@@ -140,29 +131,29 @@
 class ListComponentOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentoutputspaginator)
     """
 
     def paginate(
-        self, *, componentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, componentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentoutputspaginator)
         """
 
 class ListComponentProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, componentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, componentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponentProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentprovisionedresourcespaginator)
         """
 
 class ListComponentsPaginator(AioPaginator):
@@ -173,15 +164,15 @@
 
     def paginate(
         self,
         *,
         environmentName: str = ...,
         serviceInstanceName: str = ...,
         serviceName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listcomponentspaginator)
         """
 
 class ListEnvironmentAccountConnectionsPaginator(AioPaginator):
@@ -192,43 +183,43 @@
 
     def paginate(
         self,
         *,
         requestedBy: EnvironmentAccountConnectionRequesterAccountTypeType,
         environmentName: str = ...,
         statuses: Sequence[EnvironmentAccountConnectionStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentAccountConnectionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentAccountConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentaccountconnectionspaginator)
         """
 
 class ListEnvironmentOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentoutputspaginator)
     """
 
     def paginate(
-        self, *, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentoutputspaginator)
         """
 
 class ListEnvironmentProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentprovisionedresourcespaginator)
         """
 
 class ListEnvironmentTemplateVersionsPaginator(AioPaginator):
@@ -238,29 +229,29 @@
     """
 
     def paginate(
         self,
         *,
         templateName: str,
         majorVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentTemplateVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplateversionspaginator)
         """
 
 class ListEnvironmentTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironmentTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmenttemplatespaginator)
         """
 
 class ListEnvironmentsPaginator(AioPaginator):
@@ -269,29 +260,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         environmentTemplates: Sequence[EnvironmentTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listenvironmentspaginator)
         """
 
 class ListRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositoriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositoriespaginator)
         """
 
 class ListRepositorySyncDefinitionsPaginator(AioPaginator):
@@ -301,16 +292,16 @@
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         repositoryProvider: RepositoryProviderType,
-        syncType: Literal["TEMPLATE_SYNC"],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        syncType: SyncTypeType,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositorySyncDefinitionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListRepositorySyncDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listrepositorysyncdefinitionspaginator)
         """
 
 class ListServiceInstanceOutputsPaginator(AioPaginator):
@@ -320,15 +311,15 @@
     """
 
     def paginate(
         self,
         *,
         serviceInstanceName: str,
         serviceName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstanceOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstanceOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstanceoutputspaginator)
         """
 
 class ListServiceInstanceProvisionedResourcesPaginator(AioPaginator):
@@ -338,15 +329,15 @@
     """
 
     def paginate(
         self,
         *,
         serviceInstanceName: str,
         serviceName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstanceProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstanceProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstanceprovisionedresourcespaginator)
         """
 
 class ListServiceInstancesPaginator(AioPaginator):
@@ -358,43 +349,43 @@
     def paginate(
         self,
         *,
         filters: Sequence[ListServiceInstancesFilterTypeDef] = ...,
         serviceName: str = ...,
         sortBy: ListServiceInstancesSortByType = ...,
         sortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listserviceinstancespaginator)
         """
 
 class ListServicePipelineOutputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineOutputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineoutputspaginator)
     """
 
     def paginate(
-        self, *, serviceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serviceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicePipelineOutputsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineOutputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineoutputspaginator)
         """
 
 class ListServicePipelineProvisionedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineProvisionedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineprovisionedresourcespaginator)
     """
 
     def paginate(
-        self, *, serviceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serviceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicePipelineProvisionedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServicePipelineProvisionedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicepipelineprovisionedresourcespaginator)
         """
 
 class ListServiceTemplateVersionsPaginator(AioPaginator):
@@ -404,55 +395,55 @@
     """
 
     def paginate(
         self,
         *,
         templateName: str,
         majorVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceTemplateVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplateversionspaginator)
         """
 
 class ListServiceTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServiceTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicetemplatespaginator)
         """
 
 class ListServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listservicespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/type_defs.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -12,28 +12,30 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    BlockerStatusType,
     ComponentDeploymentUpdateTypeType,
     DeploymentStatusType,
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesFilterByType,
     ListServiceInstancesSortByType,
     ProvisionedResourceEngineType,
     RepositoryProviderType,
     RepositorySyncStatusType,
     ResourceDeploymentStatusType,
     ResourceSyncStatusType,
     ServiceStatusType,
     SortOrderType,
+    SyncTypeType,
     TemplateTypeType,
     TemplateVersionStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -43,15 +45,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptEnvironmentAccountConnectionInputRequestTypeDef",
     "EnvironmentAccountConnectionTypeDef",
-    "ResponseMetadataTypeDef",
     "RepositoryBranchTypeDef",
     "CancelComponentDeploymentInputRequestTypeDef",
     "ComponentTypeDef",
     "CancelEnvironmentDeploymentInputRequestTypeDef",
     "CancelServiceInstanceDeploymentInputRequestTypeDef",
     "ServiceInstanceTypeDef",
     "CancelServicePipelineDeploymentInputRequestTypeDef",
@@ -61,24 +62,27 @@
     "ComponentSummaryTypeDef",
     "ResourceCountsSummaryTypeDef",
     "TagTypeDef",
     "RepositoryBranchInputTypeDef",
     "EnvironmentTemplateTypeDef",
     "EnvironmentTemplateVersionTypeDef",
     "RepositoryTypeDef",
+    "CreateServiceSyncConfigInputRequestTypeDef",
+    "ServiceSyncConfigTypeDef",
     "ServiceTemplateTypeDef",
     "CreateTemplateSyncConfigInputRequestTypeDef",
     "TemplateSyncConfigTypeDef",
     "DeleteComponentInputRequestTypeDef",
     "DeleteEnvironmentAccountConnectionInputRequestTypeDef",
     "DeleteEnvironmentInputRequestTypeDef",
     "DeleteEnvironmentTemplateInputRequestTypeDef",
     "DeleteEnvironmentTemplateVersionInputRequestTypeDef",
     "DeleteRepositoryInputRequestTypeDef",
     "DeleteServiceInputRequestTypeDef",
+    "DeleteServiceSyncConfigInputRequestTypeDef",
     "DeleteServiceTemplateInputRequestTypeDef",
     "DeleteServiceTemplateVersionInputRequestTypeDef",
     "DeleteTemplateSyncConfigInputRequestTypeDef",
     "EnvironmentAccountConnectionSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
     "EnvironmentTemplateFilterTypeDef",
     "EnvironmentTemplateSummaryTypeDef",
@@ -89,59 +93,84 @@
     "GetEnvironmentInputRequestTypeDef",
     "GetEnvironmentTemplateInputRequestTypeDef",
     "GetEnvironmentTemplateVersionInputRequestTypeDef",
     "GetRepositoryInputRequestTypeDef",
     "GetRepositorySyncStatusInputRequestTypeDef",
     "GetServiceInputRequestTypeDef",
     "GetServiceInstanceInputRequestTypeDef",
+    "GetServiceInstanceSyncStatusInputRequestTypeDef",
+    "RevisionTypeDef",
+    "GetServiceSyncBlockerSummaryInputRequestTypeDef",
+    "GetServiceSyncConfigInputRequestTypeDef",
     "GetServiceTemplateInputRequestTypeDef",
     "GetServiceTemplateVersionInputRequestTypeDef",
     "GetTemplateSyncConfigInputRequestTypeDef",
     "GetTemplateSyncStatusInputRequestTypeDef",
-    "RevisionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     "ListComponentOutputsInputRequestTypeDef",
     "OutputTypeDef",
+    "ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
     "ListComponentProvisionedResourcesInputRequestTypeDef",
     "ProvisionedResourceTypeDef",
+    "ListComponentsInputListComponentsPaginateTypeDef",
     "ListComponentsInputRequestTypeDef",
+    "ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
     "ListEnvironmentAccountConnectionsInputRequestTypeDef",
+    "ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
     "ListEnvironmentOutputsInputRequestTypeDef",
+    "ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
     "ListEnvironmentProvisionedResourcesInputRequestTypeDef",
+    "ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
     "ListEnvironmentTemplateVersionsInputRequestTypeDef",
+    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
     "ListEnvironmentTemplatesInputRequestTypeDef",
+    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
     "ListRepositoriesInputRequestTypeDef",
     "RepositorySummaryTypeDef",
+    "ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
     "ListRepositorySyncDefinitionsInputRequestTypeDef",
     "RepositorySyncDefinitionTypeDef",
+    "ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
     "ListServiceInstanceOutputsInputRequestTypeDef",
+    "ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
     "ListServiceInstanceProvisionedResourcesInputRequestTypeDef",
     "ListServiceInstancesFilterTypeDef",
     "ServiceInstanceSummaryTypeDef",
+    "ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
     "ListServicePipelineOutputsInputRequestTypeDef",
+    "ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
     "ListServicePipelineProvisionedResourcesInputRequestTypeDef",
+    "ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
     "ListServiceTemplateVersionsInputRequestTypeDef",
     "ServiceTemplateVersionSummaryTypeDef",
+    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
     "ListServiceTemplatesInputRequestTypeDef",
     "ServiceTemplateSummaryTypeDef",
+    "ListServicesInputListServicesPaginateTypeDef",
     "ListServicesInputRequestTypeDef",
     "ServiceSummaryTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RejectEnvironmentAccountConnectionInputRequestTypeDef",
     "RepositorySyncEventTypeDef",
     "ResourceSyncEventTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ObjectSourceTypeDef",
+    "SyncBlockerContextTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateComponentInputRequestTypeDef",
     "UpdateEnvironmentAccountConnectionInputRequestTypeDef",
     "UpdateEnvironmentTemplateInputRequestTypeDef",
     "UpdateEnvironmentTemplateVersionInputRequestTypeDef",
     "UpdateServiceInputRequestTypeDef",
     "UpdateServiceInstanceInputRequestTypeDef",
     "UpdateServicePipelineInputRequestTypeDef",
+    "UpdateServiceSyncBlockerInputRequestTypeDef",
+    "UpdateServiceSyncConfigInputRequestTypeDef",
     "UpdateServiceTemplateInputRequestTypeDef",
     "UpdateTemplateSyncConfigInputRequestTypeDef",
     "AcceptEnvironmentAccountConnectionOutputTypeDef",
     "CreateEnvironmentAccountConnectionOutputTypeDef",
     "DeleteEnvironmentAccountConnectionOutputTypeDef",
     "GetEnvironmentAccountConnectionOutputTypeDef",
     "RejectEnvironmentAccountConnectionOutputTypeDef",
@@ -150,28 +179,30 @@
     "EnvironmentTypeDef",
     "CancelComponentDeploymentOutputTypeDef",
     "CreateComponentOutputTypeDef",
     "DeleteComponentOutputTypeDef",
     "GetComponentOutputTypeDef",
     "UpdateComponentOutputTypeDef",
     "CancelServiceInstanceDeploymentOutputTypeDef",
+    "CreateServiceInstanceOutputTypeDef",
     "GetServiceInstanceOutputTypeDef",
     "UpdateServiceInstanceOutputTypeDef",
     "CancelServicePipelineDeploymentOutputTypeDef",
     "ServiceTypeDef",
     "UpdateServicePipelineOutputTypeDef",
     "UpdateServiceTemplateVersionInputRequestTypeDef",
     "ServiceTemplateVersionTypeDef",
     "ListComponentsOutputTypeDef",
     "CountsSummaryTypeDef",
     "CreateComponentInputRequestTypeDef",
     "CreateEnvironmentAccountConnectionInputRequestTypeDef",
     "CreateEnvironmentTemplateInputRequestTypeDef",
     "CreateRepositoryInputRequestTypeDef",
     "CreateServiceInputRequestTypeDef",
+    "CreateServiceInstanceInputRequestTypeDef",
     "CreateServiceTemplateInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "CreateEnvironmentInputRequestTypeDef",
     "UpdateAccountSettingsInputRequestTypeDef",
     "UpdateEnvironmentInputRequestTypeDef",
     "CreateEnvironmentTemplateOutputTypeDef",
@@ -181,56 +212,42 @@
     "CreateEnvironmentTemplateVersionOutputTypeDef",
     "DeleteEnvironmentTemplateVersionOutputTypeDef",
     "GetEnvironmentTemplateVersionOutputTypeDef",
     "UpdateEnvironmentTemplateVersionOutputTypeDef",
     "CreateRepositoryOutputTypeDef",
     "DeleteRepositoryOutputTypeDef",
     "GetRepositoryOutputTypeDef",
+    "CreateServiceSyncConfigOutputTypeDef",
+    "DeleteServiceSyncConfigOutputTypeDef",
+    "GetServiceSyncConfigOutputTypeDef",
+    "UpdateServiceSyncConfigOutputTypeDef",
     "CreateServiceTemplateOutputTypeDef",
     "DeleteServiceTemplateOutputTypeDef",
     "GetServiceTemplateOutputTypeDef",
     "UpdateServiceTemplateOutputTypeDef",
     "CreateTemplateSyncConfigOutputTypeDef",
     "DeleteTemplateSyncConfigOutputTypeDef",
     "GetTemplateSyncConfigOutputTypeDef",
     "UpdateTemplateSyncConfigOutputTypeDef",
     "ListEnvironmentAccountConnectionsOutputTypeDef",
     "ListEnvironmentsOutputTypeDef",
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsInputRequestTypeDef",
     "ListEnvironmentTemplatesOutputTypeDef",
     "ListEnvironmentTemplateVersionsOutputTypeDef",
     "GetComponentInputComponentDeletedWaitTypeDef",
     "GetComponentInputComponentDeployedWaitTypeDef",
     "GetEnvironmentInputEnvironmentDeployedWaitTypeDef",
     "GetEnvironmentTemplateVersionInputEnvironmentTemplateVersionRegisteredWaitTypeDef",
     "GetServiceInputServiceCreatedWaitTypeDef",
     "GetServiceInputServiceDeletedWaitTypeDef",
     "GetServiceInputServicePipelineDeployedWaitTypeDef",
     "GetServiceInputServiceUpdatedWaitTypeDef",
     "GetServiceInstanceInputServiceInstanceDeployedWaitTypeDef",
     "GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef",
-    "ListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    "ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    "ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    "ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    "ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    "ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
-    "ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    "ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    "ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    "ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    "ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    "ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
-    "ListServicesInputListServicesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListComponentOutputsOutputTypeDef",
     "ListEnvironmentOutputsOutputTypeDef",
     "ListServiceInstanceOutputsOutputTypeDef",
     "ListServicePipelineOutputsOutputTypeDef",
     "NotifyResourceDeploymentStatusChangeInputRequestTypeDef",
     "ListComponentProvisionedResourcesOutputTypeDef",
     "ListEnvironmentProvisionedResourcesOutputTypeDef",
@@ -243,14 +260,15 @@
     "ListServiceInstancesOutputTypeDef",
     "ListServiceTemplateVersionsOutputTypeDef",
     "ListServiceTemplatesOutputTypeDef",
     "ListServicesOutputTypeDef",
     "RepositorySyncAttemptTypeDef",
     "ResourceSyncAttemptTypeDef",
     "TemplateVersionSourceInputTypeDef",
+    "SyncBlockerTypeDef",
     "GetAccountSettingsOutputTypeDef",
     "UpdateAccountSettingsOutputTypeDef",
     "CancelEnvironmentDeploymentOutputTypeDef",
     "CreateEnvironmentOutputTypeDef",
     "DeleteEnvironmentOutputTypeDef",
     "GetEnvironmentOutputTypeDef",
     "UpdateEnvironmentOutputTypeDef",
@@ -260,17 +278,21 @@
     "UpdateServiceOutputTypeDef",
     "CreateServiceTemplateVersionOutputTypeDef",
     "DeleteServiceTemplateVersionOutputTypeDef",
     "GetServiceTemplateVersionOutputTypeDef",
     "UpdateServiceTemplateVersionOutputTypeDef",
     "GetResourcesSummaryOutputTypeDef",
     "GetRepositorySyncStatusOutputTypeDef",
+    "GetServiceInstanceSyncStatusOutputTypeDef",
     "GetTemplateSyncStatusOutputTypeDef",
     "CreateEnvironmentTemplateVersionInputRequestTypeDef",
     "CreateServiceTemplateVersionInputRequestTypeDef",
+    "ServiceSyncBlockerSummaryTypeDef",
+    "UpdateServiceSyncBlockerOutputTypeDef",
+    "GetServiceSyncBlockerSummaryOutputTypeDef",
 )
 
 AcceptEnvironmentAccountConnectionInputRequestTypeDef = TypedDict(
     "AcceptEnvironmentAccountConnectionInputRequestTypeDef",
     {
         "id": str,
     },
@@ -302,25 +324,14 @@
 
 class EnvironmentAccountConnectionTypeDef(
     _RequiredEnvironmentAccountConnectionTypeDef, _OptionalEnvironmentAccountConnectionTypeDef
 ):
     pass
 
 
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
 RepositoryBranchTypeDef = TypedDict(
     "RepositoryBranchTypeDef",
     {
         "arn": str,
         "branch": str,
         "name": str,
         "provider": RepositoryProviderType,
@@ -346,14 +357,15 @@
     },
 )
 _OptionalComponentTypeDef = TypedDict(
     "_OptionalComponentTypeDef",
     {
         "deploymentStatusMessage": str,
         "description": str,
+        "lastClientRequestToken": str,
         "lastDeploymentAttemptedAt": datetime,
         "lastDeploymentSucceededAt": datetime,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
     },
     total=False,
@@ -395,14 +407,15 @@
         "templateName": str,
     },
 )
 _OptionalServiceInstanceTypeDef = TypedDict(
     "_OptionalServiceInstanceTypeDef",
     {
         "deploymentStatusMessage": str,
+        "lastClientRequestToken": str,
         "spec": str,
     },
     total=False,
 )
 
 
 class ServiceInstanceTypeDef(_RequiredServiceInstanceTypeDef, _OptionalServiceInstanceTypeDef):
@@ -604,14 +617,36 @@
 )
 
 
 class RepositoryTypeDef(_RequiredRepositoryTypeDef, _OptionalRepositoryTypeDef):
     pass
 
 
+CreateServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "CreateServiceSyncConfigInputRequestTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
+ServiceSyncConfigTypeDef = TypedDict(
+    "ServiceSyncConfigTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
 _RequiredServiceTemplateTypeDef = TypedDict(
     "_RequiredServiceTemplateTypeDef",
     {
         "arn": str,
         "createdAt": datetime,
         "lastModifiedAt": datetime,
         "name": str,
@@ -733,14 +768,21 @@
 DeleteServiceInputRequestTypeDef = TypedDict(
     "DeleteServiceInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "DeleteServiceSyncConfigInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+
 DeleteServiceTemplateInputRequestTypeDef = TypedDict(
     "DeleteServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
@@ -947,15 +989,15 @@
 
 GetRepositorySyncStatusInputRequestTypeDef = TypedDict(
     "GetRepositorySyncStatusInputRequestTypeDef",
     {
         "branch": str,
         "repositoryName": str,
         "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
+        "syncType": SyncTypeType,
     },
 )
 
 GetServiceInputRequestTypeDef = TypedDict(
     "GetServiceInputRequestTypeDef",
     {
         "name": str,
@@ -966,14 +1008,62 @@
     "GetServiceInstanceInputRequestTypeDef",
     {
         "name": str,
         "serviceName": str,
     },
 )
 
+GetServiceInstanceSyncStatusInputRequestTypeDef = TypedDict(
+    "GetServiceInstanceSyncStatusInputRequestTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+
+RevisionTypeDef = TypedDict(
+    "RevisionTypeDef",
+    {
+        "branch": str,
+        "directory": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "sha": str,
+    },
+)
+
+_RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef = TypedDict(
+    "_RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef = TypedDict(
+    "_OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef",
+    {
+        "serviceInstanceName": str,
+    },
+    total=False,
+)
+
+
+class GetServiceSyncBlockerSummaryInputRequestTypeDef(
+    _RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef,
+    _OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef,
+):
+    pass
+
+
+GetServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "GetServiceSyncConfigInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+
 GetServiceTemplateInputRequestTypeDef = TypedDict(
     "GetServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
@@ -999,35 +1089,36 @@
     {
         "templateName": str,
         "templateType": TemplateTypeType,
         "templateVersion": str,
     },
 )
 
-RevisionTypeDef = TypedDict(
-    "RevisionTypeDef",
+_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     {
-        "branch": str,
-        "directory": str,
-        "repositoryName": str,
-        "repositoryProvider": RepositoryProviderType,
-        "sha": str,
+        "componentName": str,
     },
 )
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListComponentOutputsInputListComponentOutputsPaginateTypeDef(
+    _RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef,
+    _OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListComponentOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListComponentOutputsInputRequestTypeDef",
     {
         "componentName": str,
     },
 )
 _OptionalListComponentOutputsInputRequestTypeDef = TypedDict(
@@ -1051,14 +1142,36 @@
     {
         "key": str,
         "valueString": str,
     },
     total=False,
 )
 
+_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
+    {
+        "componentName": str,
+    },
+)
+_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef(
+    _RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
+    _OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListComponentProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListComponentProvisionedResourcesInputRequestTypeDef",
     {
         "componentName": str,
     },
 )
 _OptionalListComponentProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1083,26 +1196,61 @@
         "identifier": str,
         "name": str,
         "provisioningEngine": ProvisionedResourceEngineType,
     },
     total=False,
 )
 
+ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsInputListComponentsPaginateTypeDef",
+    {
+        "environmentName": str,
+        "serviceInstanceName": str,
+        "serviceName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsInputRequestTypeDef = TypedDict(
     "ListComponentsInputRequestTypeDef",
     {
         "environmentName": str,
         "maxResults": int,
         "nextToken": str,
         "serviceInstanceName": str,
         "serviceName": str,
     },
     total=False,
 )
 
+_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
+    {
+        "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
+    },
+)
+_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
+    {
+        "environmentName": str,
+        "statuses": Sequence[EnvironmentAccountConnectionStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef(
+    _RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
+    _OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnvironmentAccountConnectionsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentAccountConnectionsInputRequestTypeDef",
     {
         "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
     },
 )
 _OptionalListEnvironmentAccountConnectionsInputRequestTypeDef = TypedDict(
@@ -1120,14 +1268,36 @@
 class ListEnvironmentAccountConnectionsInputRequestTypeDef(
     _RequiredListEnvironmentAccountConnectionsInputRequestTypeDef,
     _OptionalListEnvironmentAccountConnectionsInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
+    {
+        "environmentName": str,
+    },
+)
+_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef(
+    _RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
+    _OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnvironmentOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentOutputsInputRequestTypeDef",
     {
         "environmentName": str,
     },
 )
 _OptionalListEnvironmentOutputsInputRequestTypeDef = TypedDict(
@@ -1142,14 +1312,36 @@
 class ListEnvironmentOutputsInputRequestTypeDef(
     _RequiredListEnvironmentOutputsInputRequestTypeDef,
     _OptionalListEnvironmentOutputsInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
+    {
+        "environmentName": str,
+    },
+)
+_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef(
+    _RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
+    _OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef",
     {
         "environmentName": str,
     },
 )
 _OptionalListEnvironmentProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1164,14 +1356,37 @@
 class ListEnvironmentProvisionedResourcesInputRequestTypeDef(
     _RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef,
     _OptionalListEnvironmentProvisionedResourcesInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
+    {
+        "majorVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef(
+    _RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
+    _OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnvironmentTemplateVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentTemplateVersionsInputRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListEnvironmentTemplateVersionsInputRequestTypeDef = TypedDict(
@@ -1188,47 +1403,88 @@
 class ListEnvironmentTemplateVersionsInputRequestTypeDef(
     _RequiredListEnvironmentTemplateVersionsInputRequestTypeDef,
     _OptionalListEnvironmentTemplateVersionsInputRequestTypeDef,
 ):
     pass
 
 
+ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef = TypedDict(
+    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentTemplatesInputRequestTypeDef = TypedDict(
     "ListEnvironmentTemplatesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListRepositoriesInputListRepositoriesPaginateTypeDef = TypedDict(
+    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRepositoriesInputRequestTypeDef = TypedDict(
     "ListRepositoriesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
 RepositorySummaryTypeDef = TypedDict(
     "RepositorySummaryTypeDef",
     {
         "arn": str,
+        "connectionArn": str,
         "name": str,
         "provider": RepositoryProviderType,
     },
 )
 
+_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
+    {
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "syncType": SyncTypeType,
+    },
+)
+_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef(
+    _RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
+    _OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRepositorySyncDefinitionsInputRequestTypeDef = TypedDict(
     "_RequiredListRepositorySyncDefinitionsInputRequestTypeDef",
     {
         "repositoryName": str,
         "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
+        "syncType": SyncTypeType,
     },
 )
 _OptionalListRepositorySyncDefinitionsInputRequestTypeDef = TypedDict(
     "_OptionalListRepositorySyncDefinitionsInputRequestTypeDef",
     {
         "nextToken": str,
     },
@@ -1249,14 +1505,37 @@
         "branch": str,
         "directory": str,
         "parent": str,
         "target": str,
     },
 )
 
+_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef(
+    _RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
+    _OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServiceInstanceOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListServiceInstanceOutputsInputRequestTypeDef",
     {
         "serviceInstanceName": str,
         "serviceName": str,
     },
 )
@@ -1272,14 +1551,37 @@
 class ListServiceInstanceOutputsInputRequestTypeDef(
     _RequiredListServiceInstanceOutputsInputRequestTypeDef,
     _OptionalListServiceInstanceOutputsInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef(
+    _RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
+    _OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServiceInstanceProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListServiceInstanceProvisionedResourcesInputRequestTypeDef",
     {
         "serviceInstanceName": str,
         "serviceName": str,
     },
 )
@@ -1335,14 +1637,36 @@
 
 class ServiceInstanceSummaryTypeDef(
     _RequiredServiceInstanceSummaryTypeDef, _OptionalServiceInstanceSummaryTypeDef
 ):
     pass
 
 
+_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef(
+    _RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
+    _OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServicePipelineOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListServicePipelineOutputsInputRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 _OptionalListServicePipelineOutputsInputRequestTypeDef = TypedDict(
@@ -1357,14 +1681,36 @@
 class ListServicePipelineOutputsInputRequestTypeDef(
     _RequiredListServicePipelineOutputsInputRequestTypeDef,
     _OptionalListServicePipelineOutputsInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef(
+    _RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
+    _OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 _OptionalListServicePipelineProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1379,14 +1725,37 @@
 class ListServicePipelineProvisionedResourcesInputRequestTypeDef(
     _RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef,
     _OptionalListServicePipelineProvisionedResourcesInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
+    {
+        "majorVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef(
+    _RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
+    _OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServiceTemplateVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListServiceTemplateVersionsInputRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListServiceTemplateVersionsInputRequestTypeDef = TypedDict(
@@ -1432,14 +1801,22 @@
 
 class ServiceTemplateVersionSummaryTypeDef(
     _RequiredServiceTemplateVersionSummaryTypeDef, _OptionalServiceTemplateVersionSummaryTypeDef
 ):
     pass
 
 
+ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef = TypedDict(
+    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceTemplatesInputRequestTypeDef = TypedDict(
     "ListServiceTemplatesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1468,14 +1845,22 @@
 
 class ServiceTemplateSummaryTypeDef(
     _RequiredServiceTemplateSummaryTypeDef, _OptionalServiceTemplateSummaryTypeDef
 ):
     pass
 
 
+ListServicesInputListServicesPaginateTypeDef = TypedDict(
+    "ListServicesInputListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesInputRequestTypeDef = TypedDict(
     "ListServicesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1502,14 +1887,36 @@
 )
 
 
 class ServiceSummaryTypeDef(_RequiredServiceSummaryTypeDef, _OptionalServiceSummaryTypeDef):
     pass
 
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -1524,14 +1931,24 @@
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
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
 RejectEnvironmentAccountConnectionInputRequestTypeDef = TypedDict(
     "RejectEnvironmentAccountConnectionInputRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -1577,22 +1994,41 @@
 
 class ResourceSyncEventTypeDef(
     _RequiredResourceSyncEventTypeDef, _OptionalResourceSyncEventTypeDef
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
 S3ObjectSourceTypeDef = TypedDict(
     "S3ObjectSourceTypeDef",
     {
         "bucket": str,
         "key": str,
     },
 )
 
+SyncBlockerContextTypeDef = TypedDict(
+    "SyncBlockerContextTypeDef",
+    {
+        "key": str,
+        "value": str,
+    },
+)
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1603,14 +2039,15 @@
         "deploymentType": ComponentDeploymentUpdateTypeType,
         "name": str,
     },
 )
 _OptionalUpdateComponentInputRequestTypeDef = TypedDict(
     "_OptionalUpdateComponentInputRequestTypeDef",
     {
+        "clientToken": str,
         "description": str,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
         "templateFile": str,
     },
     total=False,
@@ -1724,14 +2161,15 @@
         "name": str,
         "serviceName": str,
     },
 )
 _OptionalUpdateServiceInstanceInputRequestTypeDef = TypedDict(
     "_OptionalUpdateServiceInstanceInputRequestTypeDef",
     {
+        "clientToken": str,
         "spec": str,
         "templateMajorVersion": str,
         "templateMinorVersion": str,
     },
     total=False,
 )
 
@@ -1764,14 +2202,33 @@
 class UpdateServicePipelineInputRequestTypeDef(
     _RequiredUpdateServicePipelineInputRequestTypeDef,
     _OptionalUpdateServicePipelineInputRequestTypeDef,
 ):
     pass
 
 
+UpdateServiceSyncBlockerInputRequestTypeDef = TypedDict(
+    "UpdateServiceSyncBlockerInputRequestTypeDef",
+    {
+        "id": str,
+        "resolvedReason": str,
+    },
+)
+
+UpdateServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "UpdateServiceSyncConfigInputRequestTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
 _RequiredUpdateServiceTemplateInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateServiceTemplateInputRequestTypeDef = TypedDict(
@@ -1817,55 +2274,55 @@
     pass
 
 
 AcceptEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "AcceptEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "CreateEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "DeleteEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "GetEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "RejectEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "UpdateEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccountSettingsTypeDef = TypedDict(
     "AccountSettingsTypeDef",
     {
         "pipelineCodebuildRoleArn": str,
@@ -1911,79 +2368,87 @@
     pass
 
 
 CancelComponentDeploymentOutputTypeDef = TypedDict(
     "CancelComponentDeploymentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComponentOutputTypeDef = TypedDict(
     "CreateComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteComponentOutputTypeDef = TypedDict(
     "DeleteComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentOutputTypeDef = TypedDict(
     "GetComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateComponentOutputTypeDef = TypedDict(
     "UpdateComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelServiceInstanceDeploymentOutputTypeDef = TypedDict(
     "CancelServiceInstanceDeploymentOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateServiceInstanceOutputTypeDef = TypedDict(
+    "CreateServiceInstanceOutputTypeDef",
+    {
+        "serviceInstance": ServiceInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceInstanceOutputTypeDef = TypedDict(
     "GetServiceInstanceOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceInstanceOutputTypeDef = TypedDict(
     "UpdateServiceInstanceOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelServicePipelineDeploymentOutputTypeDef = TypedDict(
     "CancelServicePipelineDeploymentOutputTypeDef",
     {
         "pipeline": ServicePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredServiceTypeDef = TypedDict(
     "_RequiredServiceTypeDef",
     {
         "arn": str,
@@ -2013,15 +2478,15 @@
     pass
 
 
 UpdateServicePipelineOutputTypeDef = TypedDict(
     "UpdateServicePipelineOutputTypeDef",
     {
         "pipeline": ServicePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateServiceTemplateVersionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceTemplateVersionInputRequestTypeDef",
     {
         "majorVersion": str,
@@ -2081,15 +2546,15 @@
 
 
 ListComponentsOutputTypeDef = TypedDict(
     "ListComponentsOutputTypeDef",
     {
         "components": List[ComponentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CountsSummaryTypeDef = TypedDict(
     "CountsSummaryTypeDef",
     {
         "components": ResourceCountsSummaryTypeDef,
@@ -2110,14 +2575,15 @@
         "name": str,
         "templateFile": str,
     },
 )
 _OptionalCreateComponentInputRequestTypeDef = TypedDict(
     "_OptionalCreateComponentInputRequestTypeDef",
     {
+        "clientToken": str,
         "description": str,
         "environmentName": str,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
         "tags": Sequence[TagTypeDef],
     },
@@ -2233,14 +2699,41 @@
 
 class CreateServiceInputRequestTypeDef(
     _RequiredCreateServiceInputRequestTypeDef, _OptionalCreateServiceInputRequestTypeDef
 ):
     pass
 
 
+_RequiredCreateServiceInstanceInputRequestTypeDef = TypedDict(
+    "_RequiredCreateServiceInstanceInputRequestTypeDef",
+    {
+        "name": str,
+        "serviceName": str,
+        "spec": str,
+    },
+)
+_OptionalCreateServiceInstanceInputRequestTypeDef = TypedDict(
+    "_OptionalCreateServiceInstanceInputRequestTypeDef",
+    {
+        "clientToken": str,
+        "tags": Sequence[TagTypeDef],
+        "templateMajorVersion": str,
+        "templateMinorVersion": str,
+    },
+    total=False,
+)
+
+
+class CreateServiceInstanceInputRequestTypeDef(
+    _RequiredCreateServiceInstanceInputRequestTypeDef,
+    _OptionalCreateServiceInstanceInputRequestTypeDef,
+):
+    pass
+
+
 _RequiredCreateServiceTemplateInputRequestTypeDef = TypedDict(
     "_RequiredCreateServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateServiceTemplateInputRequestTypeDef = TypedDict(
@@ -2264,15 +2757,15 @@
 
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "nextToken": str,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -2352,178 +2845,219 @@
     pass
 
 
 CreateEnvironmentTemplateOutputTypeDef = TypedDict(
     "CreateEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentTemplateOutputTypeDef = TypedDict(
     "DeleteEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentTemplateOutputTypeDef = TypedDict(
     "GetEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentTemplateOutputTypeDef = TypedDict(
     "UpdateEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "CreateEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "DeleteEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "GetEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "UpdateEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryOutputTypeDef = TypedDict(
     "CreateRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryOutputTypeDef = TypedDict(
     "DeleteRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositoryOutputTypeDef = TypedDict(
     "GetRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateServiceSyncConfigOutputTypeDef = TypedDict(
+    "CreateServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteServiceSyncConfigOutputTypeDef = TypedDict(
+    "DeleteServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceSyncConfigOutputTypeDef = TypedDict(
+    "GetServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateServiceSyncConfigOutputTypeDef = TypedDict(
+    "UpdateServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceTemplateOutputTypeDef = TypedDict(
     "CreateServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceTemplateOutputTypeDef = TypedDict(
     "DeleteServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceTemplateOutputTypeDef = TypedDict(
     "GetServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceTemplateOutputTypeDef = TypedDict(
     "UpdateServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTemplateSyncConfigOutputTypeDef = TypedDict(
     "CreateTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTemplateSyncConfigOutputTypeDef = TypedDict(
     "DeleteTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSyncConfigOutputTypeDef = TypedDict(
     "GetTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTemplateSyncConfigOutputTypeDef = TypedDict(
     "UpdateTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentAccountConnectionsOutputTypeDef = TypedDict(
     "ListEnvironmentAccountConnectionsOutputTypeDef",
     {
         "environmentAccountConnections": List[EnvironmentAccountConnectionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsOutputTypeDef = TypedDict(
     "ListEnvironmentsOutputTypeDef",
     {
         "environments": List[EnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
+    {
+        "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListEnvironmentsInputRequestTypeDef = TypedDict(
     "ListEnvironmentsInputRequestTypeDef",
     {
         "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
         "maxResults": int,
@@ -2533,24 +3067,24 @@
 )
 
 ListEnvironmentTemplatesOutputTypeDef = TypedDict(
     "ListEnvironmentTemplatesOutputTypeDef",
     {
         "nextToken": str,
         "templates": List[EnvironmentTemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentTemplateVersionsOutputTypeDef = TypedDict(
     "ListEnvironmentTemplateVersionsOutputTypeDef",
     {
         "nextToken": str,
         "templateVersions": List[EnvironmentTemplateVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetComponentInputComponentDeletedWaitTypeDef = TypedDict(
     "_RequiredGetComponentInputComponentDeletedWaitTypeDef",
     {
         "name": str,
@@ -2771,393 +3305,47 @@
 class GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef(
     _RequiredGetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
     _OptionalGetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
 ):
     pass
 
 
-_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    {
-        "componentName": str,
-    },
-)
-_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListComponentOutputsInputListComponentOutputsPaginateTypeDef(
-    _RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-    _OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    {
-        "componentName": str,
-    },
-)
-_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef(
-    _RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-    _OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-
-ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    {
-        "environmentName": str,
-        "serviceInstanceName": str,
-        "serviceName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    {
-        "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
-    },
-)
-_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    {
-        "environmentName": str,
-        "statuses": Sequence[EnvironmentAccountConnectionStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef(
-    _RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-    _OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    {
-        "environmentName": str,
-    },
-)
-_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef(
-    _RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-    _OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    {
-        "environmentName": str,
-    },
-)
-_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef(
-    _RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-    _OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    {
-        "majorVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef(
-    _RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-    _OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef = TypedDict(
-    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    {
-        "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRepositoriesInputListRepositoriesPaginateTypeDef = TypedDict(
-    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    {
-        "repositoryName": str,
-        "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
-    },
-)
-_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef(
-    _RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-    _OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    {
-        "serviceInstanceName": str,
-        "serviceName": str,
-    },
-)
-_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef(
-    _RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-    _OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    {
-        "serviceInstanceName": str,
-        "serviceName": str,
-    },
-)
-_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef(
-    _RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-    _OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    {
-        "serviceName": str,
-    },
-)
-_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef(
-    _RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-    _OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    {
-        "serviceName": str,
-    },
-)
-_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef(
-    _RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-    _OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    {
-        "majorVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef(
-    _RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-    _OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef = TypedDict(
-    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServicesInputListServicesPaginateTypeDef = TypedDict(
-    "ListServicesInputListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
 ListComponentOutputsOutputTypeDef = TypedDict(
     "ListComponentOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentOutputsOutputTypeDef = TypedDict(
     "ListEnvironmentOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstanceOutputsOutputTypeDef = TypedDict(
     "ListServiceInstanceOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicePipelineOutputsOutputTypeDef = TypedDict(
     "ListServicePipelineOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNotifyResourceDeploymentStatusChangeInputRequestTypeDef = TypedDict(
     "_RequiredNotifyResourceDeploymentStatusChangeInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -3183,71 +3371,71 @@
 
 
 ListComponentProvisionedResourcesOutputTypeDef = TypedDict(
     "ListComponentProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentProvisionedResourcesOutputTypeDef = TypedDict(
     "ListEnvironmentProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstanceProvisionedResourcesOutputTypeDef = TypedDict(
     "ListServiceInstanceProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicePipelineProvisionedResourcesOutputTypeDef = TypedDict(
     "ListServicePipelineProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesOutputTypeDef = TypedDict(
     "ListRepositoriesOutputTypeDef",
     {
         "nextToken": str,
         "repositories": List[RepositorySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositorySyncDefinitionsOutputTypeDef = TypedDict(
     "ListRepositorySyncDefinitionsOutputTypeDef",
     {
         "nextToken": str,
         "syncDefinitions": List[RepositorySyncDefinitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstancesInputListServiceInstancesPaginateTypeDef = TypedDict(
     "ListServiceInstancesInputListServiceInstancesPaginateTypeDef",
     {
         "filters": Sequence[ListServiceInstancesFilterTypeDef],
         "serviceName": str,
         "sortBy": ListServiceInstancesSortByType,
         "sortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServiceInstancesInputRequestTypeDef = TypedDict(
     "ListServiceInstancesInputRequestTypeDef",
     {
@@ -3262,42 +3450,42 @@
 )
 
 ListServiceInstancesOutputTypeDef = TypedDict(
     "ListServiceInstancesOutputTypeDef",
     {
         "nextToken": str,
         "serviceInstances": List[ServiceInstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceTemplateVersionsOutputTypeDef = TypedDict(
     "ListServiceTemplateVersionsOutputTypeDef",
     {
         "nextToken": str,
         "templateVersions": List[ServiceTemplateVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceTemplatesOutputTypeDef = TypedDict(
     "ListServiceTemplatesOutputTypeDef",
     {
         "nextToken": str,
         "templates": List[ServiceTemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesOutputTypeDef = TypedDict(
     "ListServicesOutputTypeDef",
     {
         "nextToken": str,
         "services": List[ServiceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RepositorySyncAttemptTypeDef = TypedDict(
     "RepositorySyncAttemptTypeDef",
     {
         "events": List[RepositorySyncEventTypeDef],
@@ -3322,157 +3510,192 @@
     "TemplateVersionSourceInputTypeDef",
     {
         "s3": S3ObjectSourceTypeDef,
     },
     total=False,
 )
 
+_RequiredSyncBlockerTypeDef = TypedDict(
+    "_RequiredSyncBlockerTypeDef",
+    {
+        "createdAt": datetime,
+        "createdReason": str,
+        "id": str,
+        "status": BlockerStatusType,
+        "type": Literal["AUTOMATED"],
+    },
+)
+_OptionalSyncBlockerTypeDef = TypedDict(
+    "_OptionalSyncBlockerTypeDef",
+    {
+        "contexts": List[SyncBlockerContextTypeDef],
+        "resolvedAt": datetime,
+        "resolvedReason": str,
+    },
+    total=False,
+)
+
+
+class SyncBlockerTypeDef(_RequiredSyncBlockerTypeDef, _OptionalSyncBlockerTypeDef):
+    pass
+
+
 GetAccountSettingsOutputTypeDef = TypedDict(
     "GetAccountSettingsOutputTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountSettingsOutputTypeDef = TypedDict(
     "UpdateAccountSettingsOutputTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelEnvironmentDeploymentOutputTypeDef = TypedDict(
     "CancelEnvironmentDeploymentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentOutputTypeDef = TypedDict(
     "CreateEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentOutputTypeDef = TypedDict(
     "DeleteEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentOutputTypeDef = TypedDict(
     "GetEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentOutputTypeDef = TypedDict(
     "UpdateEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceOutputTypeDef = TypedDict(
     "CreateServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceOutputTypeDef = TypedDict(
     "DeleteServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceOutputTypeDef = TypedDict(
     "GetServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceOutputTypeDef = TypedDict(
     "UpdateServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceTemplateVersionOutputTypeDef = TypedDict(
     "CreateServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceTemplateVersionOutputTypeDef = TypedDict(
     "DeleteServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceTemplateVersionOutputTypeDef = TypedDict(
     "GetServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceTemplateVersionOutputTypeDef = TypedDict(
     "UpdateServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesSummaryOutputTypeDef = TypedDict(
     "GetResourcesSummaryOutputTypeDef",
     {
         "counts": CountsSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositorySyncStatusOutputTypeDef = TypedDict(
     "GetRepositorySyncStatusOutputTypeDef",
     {
         "latestSync": RepositorySyncAttemptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceInstanceSyncStatusOutputTypeDef = TypedDict(
+    "GetServiceInstanceSyncStatusOutputTypeDef",
+    {
+        "desiredState": RevisionTypeDef,
+        "latestSuccessfulSync": ResourceSyncAttemptTypeDef,
+        "latestSync": ResourceSyncAttemptTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSyncStatusOutputTypeDef = TypedDict(
     "GetTemplateSyncStatusOutputTypeDef",
     {
         "desiredState": RevisionTypeDef,
         "latestSuccessfulSync": ResourceSyncAttemptTypeDef,
         "latestSync": ResourceSyncAttemptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEnvironmentTemplateVersionInputRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentTemplateVersionInputRequestTypeDef",
     {
         "source": TemplateVersionSourceInputTypeDef,
@@ -3520,7 +3743,48 @@
 
 
 class CreateServiceTemplateVersionInputRequestTypeDef(
     _RequiredCreateServiceTemplateVersionInputRequestTypeDef,
     _OptionalCreateServiceTemplateVersionInputRequestTypeDef,
 ):
     pass
+
+
+_RequiredServiceSyncBlockerSummaryTypeDef = TypedDict(
+    "_RequiredServiceSyncBlockerSummaryTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalServiceSyncBlockerSummaryTypeDef = TypedDict(
+    "_OptionalServiceSyncBlockerSummaryTypeDef",
+    {
+        "latestBlockers": List[SyncBlockerTypeDef],
+        "serviceInstanceName": str,
+    },
+    total=False,
+)
+
+
+class ServiceSyncBlockerSummaryTypeDef(
+    _RequiredServiceSyncBlockerSummaryTypeDef, _OptionalServiceSyncBlockerSummaryTypeDef
+):
+    pass
+
+
+UpdateServiceSyncBlockerOutputTypeDef = TypedDict(
+    "UpdateServiceSyncBlockerOutputTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+        "serviceSyncBlocker": SyncBlockerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceSyncBlockerSummaryOutputTypeDef = TypedDict(
+    "GetServiceSyncBlockerSummaryOutputTypeDef",
+    {
+        "serviceSyncBlockerSummary": ServiceSyncBlockerSummaryTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/type_defs.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -12,28 +12,30 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    BlockerStatusType,
     ComponentDeploymentUpdateTypeType,
     DeploymentStatusType,
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
     ListServiceInstancesFilterByType,
     ListServiceInstancesSortByType,
     ProvisionedResourceEngineType,
     RepositoryProviderType,
     RepositorySyncStatusType,
     ResourceDeploymentStatusType,
     ResourceSyncStatusType,
     ServiceStatusType,
     SortOrderType,
+    SyncTypeType,
     TemplateTypeType,
     TemplateVersionStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -42,15 +44,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptEnvironmentAccountConnectionInputRequestTypeDef",
     "EnvironmentAccountConnectionTypeDef",
-    "ResponseMetadataTypeDef",
     "RepositoryBranchTypeDef",
     "CancelComponentDeploymentInputRequestTypeDef",
     "ComponentTypeDef",
     "CancelEnvironmentDeploymentInputRequestTypeDef",
     "CancelServiceInstanceDeploymentInputRequestTypeDef",
     "ServiceInstanceTypeDef",
     "CancelServicePipelineDeploymentInputRequestTypeDef",
@@ -60,24 +61,27 @@
     "ComponentSummaryTypeDef",
     "ResourceCountsSummaryTypeDef",
     "TagTypeDef",
     "RepositoryBranchInputTypeDef",
     "EnvironmentTemplateTypeDef",
     "EnvironmentTemplateVersionTypeDef",
     "RepositoryTypeDef",
+    "CreateServiceSyncConfigInputRequestTypeDef",
+    "ServiceSyncConfigTypeDef",
     "ServiceTemplateTypeDef",
     "CreateTemplateSyncConfigInputRequestTypeDef",
     "TemplateSyncConfigTypeDef",
     "DeleteComponentInputRequestTypeDef",
     "DeleteEnvironmentAccountConnectionInputRequestTypeDef",
     "DeleteEnvironmentInputRequestTypeDef",
     "DeleteEnvironmentTemplateInputRequestTypeDef",
     "DeleteEnvironmentTemplateVersionInputRequestTypeDef",
     "DeleteRepositoryInputRequestTypeDef",
     "DeleteServiceInputRequestTypeDef",
+    "DeleteServiceSyncConfigInputRequestTypeDef",
     "DeleteServiceTemplateInputRequestTypeDef",
     "DeleteServiceTemplateVersionInputRequestTypeDef",
     "DeleteTemplateSyncConfigInputRequestTypeDef",
     "EnvironmentAccountConnectionSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
     "EnvironmentTemplateFilterTypeDef",
     "EnvironmentTemplateSummaryTypeDef",
@@ -88,59 +92,84 @@
     "GetEnvironmentInputRequestTypeDef",
     "GetEnvironmentTemplateInputRequestTypeDef",
     "GetEnvironmentTemplateVersionInputRequestTypeDef",
     "GetRepositoryInputRequestTypeDef",
     "GetRepositorySyncStatusInputRequestTypeDef",
     "GetServiceInputRequestTypeDef",
     "GetServiceInstanceInputRequestTypeDef",
+    "GetServiceInstanceSyncStatusInputRequestTypeDef",
+    "RevisionTypeDef",
+    "GetServiceSyncBlockerSummaryInputRequestTypeDef",
+    "GetServiceSyncConfigInputRequestTypeDef",
     "GetServiceTemplateInputRequestTypeDef",
     "GetServiceTemplateVersionInputRequestTypeDef",
     "GetTemplateSyncConfigInputRequestTypeDef",
     "GetTemplateSyncStatusInputRequestTypeDef",
-    "RevisionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     "ListComponentOutputsInputRequestTypeDef",
     "OutputTypeDef",
+    "ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
     "ListComponentProvisionedResourcesInputRequestTypeDef",
     "ProvisionedResourceTypeDef",
+    "ListComponentsInputListComponentsPaginateTypeDef",
     "ListComponentsInputRequestTypeDef",
+    "ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
     "ListEnvironmentAccountConnectionsInputRequestTypeDef",
+    "ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
     "ListEnvironmentOutputsInputRequestTypeDef",
+    "ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
     "ListEnvironmentProvisionedResourcesInputRequestTypeDef",
+    "ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
     "ListEnvironmentTemplateVersionsInputRequestTypeDef",
+    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
     "ListEnvironmentTemplatesInputRequestTypeDef",
+    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
     "ListRepositoriesInputRequestTypeDef",
     "RepositorySummaryTypeDef",
+    "ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
     "ListRepositorySyncDefinitionsInputRequestTypeDef",
     "RepositorySyncDefinitionTypeDef",
+    "ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
     "ListServiceInstanceOutputsInputRequestTypeDef",
+    "ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
     "ListServiceInstanceProvisionedResourcesInputRequestTypeDef",
     "ListServiceInstancesFilterTypeDef",
     "ServiceInstanceSummaryTypeDef",
+    "ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
     "ListServicePipelineOutputsInputRequestTypeDef",
+    "ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
     "ListServicePipelineProvisionedResourcesInputRequestTypeDef",
+    "ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
     "ListServiceTemplateVersionsInputRequestTypeDef",
     "ServiceTemplateVersionSummaryTypeDef",
+    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
     "ListServiceTemplatesInputRequestTypeDef",
     "ServiceTemplateSummaryTypeDef",
+    "ListServicesInputListServicesPaginateTypeDef",
     "ListServicesInputRequestTypeDef",
     "ServiceSummaryTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RejectEnvironmentAccountConnectionInputRequestTypeDef",
     "RepositorySyncEventTypeDef",
     "ResourceSyncEventTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ObjectSourceTypeDef",
+    "SyncBlockerContextTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateComponentInputRequestTypeDef",
     "UpdateEnvironmentAccountConnectionInputRequestTypeDef",
     "UpdateEnvironmentTemplateInputRequestTypeDef",
     "UpdateEnvironmentTemplateVersionInputRequestTypeDef",
     "UpdateServiceInputRequestTypeDef",
     "UpdateServiceInstanceInputRequestTypeDef",
     "UpdateServicePipelineInputRequestTypeDef",
+    "UpdateServiceSyncBlockerInputRequestTypeDef",
+    "UpdateServiceSyncConfigInputRequestTypeDef",
     "UpdateServiceTemplateInputRequestTypeDef",
     "UpdateTemplateSyncConfigInputRequestTypeDef",
     "AcceptEnvironmentAccountConnectionOutputTypeDef",
     "CreateEnvironmentAccountConnectionOutputTypeDef",
     "DeleteEnvironmentAccountConnectionOutputTypeDef",
     "GetEnvironmentAccountConnectionOutputTypeDef",
     "RejectEnvironmentAccountConnectionOutputTypeDef",
@@ -149,28 +178,30 @@
     "EnvironmentTypeDef",
     "CancelComponentDeploymentOutputTypeDef",
     "CreateComponentOutputTypeDef",
     "DeleteComponentOutputTypeDef",
     "GetComponentOutputTypeDef",
     "UpdateComponentOutputTypeDef",
     "CancelServiceInstanceDeploymentOutputTypeDef",
+    "CreateServiceInstanceOutputTypeDef",
     "GetServiceInstanceOutputTypeDef",
     "UpdateServiceInstanceOutputTypeDef",
     "CancelServicePipelineDeploymentOutputTypeDef",
     "ServiceTypeDef",
     "UpdateServicePipelineOutputTypeDef",
     "UpdateServiceTemplateVersionInputRequestTypeDef",
     "ServiceTemplateVersionTypeDef",
     "ListComponentsOutputTypeDef",
     "CountsSummaryTypeDef",
     "CreateComponentInputRequestTypeDef",
     "CreateEnvironmentAccountConnectionInputRequestTypeDef",
     "CreateEnvironmentTemplateInputRequestTypeDef",
     "CreateRepositoryInputRequestTypeDef",
     "CreateServiceInputRequestTypeDef",
+    "CreateServiceInstanceInputRequestTypeDef",
     "CreateServiceTemplateInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "CreateEnvironmentInputRequestTypeDef",
     "UpdateAccountSettingsInputRequestTypeDef",
     "UpdateEnvironmentInputRequestTypeDef",
     "CreateEnvironmentTemplateOutputTypeDef",
@@ -180,56 +211,42 @@
     "CreateEnvironmentTemplateVersionOutputTypeDef",
     "DeleteEnvironmentTemplateVersionOutputTypeDef",
     "GetEnvironmentTemplateVersionOutputTypeDef",
     "UpdateEnvironmentTemplateVersionOutputTypeDef",
     "CreateRepositoryOutputTypeDef",
     "DeleteRepositoryOutputTypeDef",
     "GetRepositoryOutputTypeDef",
+    "CreateServiceSyncConfigOutputTypeDef",
+    "DeleteServiceSyncConfigOutputTypeDef",
+    "GetServiceSyncConfigOutputTypeDef",
+    "UpdateServiceSyncConfigOutputTypeDef",
     "CreateServiceTemplateOutputTypeDef",
     "DeleteServiceTemplateOutputTypeDef",
     "GetServiceTemplateOutputTypeDef",
     "UpdateServiceTemplateOutputTypeDef",
     "CreateTemplateSyncConfigOutputTypeDef",
     "DeleteTemplateSyncConfigOutputTypeDef",
     "GetTemplateSyncConfigOutputTypeDef",
     "UpdateTemplateSyncConfigOutputTypeDef",
     "ListEnvironmentAccountConnectionsOutputTypeDef",
     "ListEnvironmentsOutputTypeDef",
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsInputRequestTypeDef",
     "ListEnvironmentTemplatesOutputTypeDef",
     "ListEnvironmentTemplateVersionsOutputTypeDef",
     "GetComponentInputComponentDeletedWaitTypeDef",
     "GetComponentInputComponentDeployedWaitTypeDef",
     "GetEnvironmentInputEnvironmentDeployedWaitTypeDef",
     "GetEnvironmentTemplateVersionInputEnvironmentTemplateVersionRegisteredWaitTypeDef",
     "GetServiceInputServiceCreatedWaitTypeDef",
     "GetServiceInputServiceDeletedWaitTypeDef",
     "GetServiceInputServicePipelineDeployedWaitTypeDef",
     "GetServiceInputServiceUpdatedWaitTypeDef",
     "GetServiceInstanceInputServiceInstanceDeployedWaitTypeDef",
     "GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef",
-    "ListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    "ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    "ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    "ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    "ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    "ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
-    "ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    "ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    "ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    "ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    "ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    "ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
-    "ListServicesInputListServicesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListComponentOutputsOutputTypeDef",
     "ListEnvironmentOutputsOutputTypeDef",
     "ListServiceInstanceOutputsOutputTypeDef",
     "ListServicePipelineOutputsOutputTypeDef",
     "NotifyResourceDeploymentStatusChangeInputRequestTypeDef",
     "ListComponentProvisionedResourcesOutputTypeDef",
     "ListEnvironmentProvisionedResourcesOutputTypeDef",
@@ -242,14 +259,15 @@
     "ListServiceInstancesOutputTypeDef",
     "ListServiceTemplateVersionsOutputTypeDef",
     "ListServiceTemplatesOutputTypeDef",
     "ListServicesOutputTypeDef",
     "RepositorySyncAttemptTypeDef",
     "ResourceSyncAttemptTypeDef",
     "TemplateVersionSourceInputTypeDef",
+    "SyncBlockerTypeDef",
     "GetAccountSettingsOutputTypeDef",
     "UpdateAccountSettingsOutputTypeDef",
     "CancelEnvironmentDeploymentOutputTypeDef",
     "CreateEnvironmentOutputTypeDef",
     "DeleteEnvironmentOutputTypeDef",
     "GetEnvironmentOutputTypeDef",
     "UpdateEnvironmentOutputTypeDef",
@@ -259,17 +277,21 @@
     "UpdateServiceOutputTypeDef",
     "CreateServiceTemplateVersionOutputTypeDef",
     "DeleteServiceTemplateVersionOutputTypeDef",
     "GetServiceTemplateVersionOutputTypeDef",
     "UpdateServiceTemplateVersionOutputTypeDef",
     "GetResourcesSummaryOutputTypeDef",
     "GetRepositorySyncStatusOutputTypeDef",
+    "GetServiceInstanceSyncStatusOutputTypeDef",
     "GetTemplateSyncStatusOutputTypeDef",
     "CreateEnvironmentTemplateVersionInputRequestTypeDef",
     "CreateServiceTemplateVersionInputRequestTypeDef",
+    "ServiceSyncBlockerSummaryTypeDef",
+    "UpdateServiceSyncBlockerOutputTypeDef",
+    "GetServiceSyncBlockerSummaryOutputTypeDef",
 )
 
 AcceptEnvironmentAccountConnectionInputRequestTypeDef = TypedDict(
     "AcceptEnvironmentAccountConnectionInputRequestTypeDef",
     {
         "id": str,
     },
@@ -299,25 +321,14 @@
 )
 
 class EnvironmentAccountConnectionTypeDef(
     _RequiredEnvironmentAccountConnectionTypeDef, _OptionalEnvironmentAccountConnectionTypeDef
 ):
     pass
 
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
 RepositoryBranchTypeDef = TypedDict(
     "RepositoryBranchTypeDef",
     {
         "arn": str,
         "branch": str,
         "name": str,
         "provider": RepositoryProviderType,
@@ -343,14 +354,15 @@
     },
 )
 _OptionalComponentTypeDef = TypedDict(
     "_OptionalComponentTypeDef",
     {
         "deploymentStatusMessage": str,
         "description": str,
+        "lastClientRequestToken": str,
         "lastDeploymentAttemptedAt": datetime,
         "lastDeploymentSucceededAt": datetime,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
     },
     total=False,
@@ -390,14 +402,15 @@
         "templateName": str,
     },
 )
 _OptionalServiceInstanceTypeDef = TypedDict(
     "_OptionalServiceInstanceTypeDef",
     {
         "deploymentStatusMessage": str,
+        "lastClientRequestToken": str,
         "spec": str,
     },
     total=False,
 )
 
 class ServiceInstanceTypeDef(_RequiredServiceInstanceTypeDef, _OptionalServiceInstanceTypeDef):
     pass
@@ -585,14 +598,36 @@
     },
     total=False,
 )
 
 class RepositoryTypeDef(_RequiredRepositoryTypeDef, _OptionalRepositoryTypeDef):
     pass
 
+CreateServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "CreateServiceSyncConfigInputRequestTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
+ServiceSyncConfigTypeDef = TypedDict(
+    "ServiceSyncConfigTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
 _RequiredServiceTemplateTypeDef = TypedDict(
     "_RequiredServiceTemplateTypeDef",
     {
         "arn": str,
         "createdAt": datetime,
         "lastModifiedAt": datetime,
         "name": str,
@@ -708,14 +743,21 @@
 DeleteServiceInputRequestTypeDef = TypedDict(
     "DeleteServiceInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "DeleteServiceSyncConfigInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+
 DeleteServiceTemplateInputRequestTypeDef = TypedDict(
     "DeleteServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
@@ -914,15 +956,15 @@
 
 GetRepositorySyncStatusInputRequestTypeDef = TypedDict(
     "GetRepositorySyncStatusInputRequestTypeDef",
     {
         "branch": str,
         "repositoryName": str,
         "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
+        "syncType": SyncTypeType,
     },
 )
 
 GetServiceInputRequestTypeDef = TypedDict(
     "GetServiceInputRequestTypeDef",
     {
         "name": str,
@@ -933,14 +975,60 @@
     "GetServiceInstanceInputRequestTypeDef",
     {
         "name": str,
         "serviceName": str,
     },
 )
 
+GetServiceInstanceSyncStatusInputRequestTypeDef = TypedDict(
+    "GetServiceInstanceSyncStatusInputRequestTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+
+RevisionTypeDef = TypedDict(
+    "RevisionTypeDef",
+    {
+        "branch": str,
+        "directory": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "sha": str,
+    },
+)
+
+_RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef = TypedDict(
+    "_RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef = TypedDict(
+    "_OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef",
+    {
+        "serviceInstanceName": str,
+    },
+    total=False,
+)
+
+class GetServiceSyncBlockerSummaryInputRequestTypeDef(
+    _RequiredGetServiceSyncBlockerSummaryInputRequestTypeDef,
+    _OptionalGetServiceSyncBlockerSummaryInputRequestTypeDef,
+):
+    pass
+
+GetServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "GetServiceSyncConfigInputRequestTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+
 GetServiceTemplateInputRequestTypeDef = TypedDict(
     "GetServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 
@@ -966,35 +1054,34 @@
     {
         "templateName": str,
         "templateType": TemplateTypeType,
         "templateVersion": str,
     },
 )
 
-RevisionTypeDef = TypedDict(
-    "RevisionTypeDef",
+_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     {
-        "branch": str,
-        "directory": str,
-        "repositoryName": str,
-        "repositoryProvider": RepositoryProviderType,
-        "sha": str,
+        "componentName": str,
     },
 )
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListComponentOutputsInputListComponentOutputsPaginateTypeDef(
+    _RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef,
+    _OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef,
+):
+    pass
+
 _RequiredListComponentOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListComponentOutputsInputRequestTypeDef",
     {
         "componentName": str,
     },
 )
 _OptionalListComponentOutputsInputRequestTypeDef = TypedDict(
@@ -1016,14 +1103,34 @@
     {
         "key": str,
         "valueString": str,
     },
     total=False,
 )
 
+_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
+    {
+        "componentName": str,
+    },
+)
+_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef(
+    _RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
+    _OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListComponentProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListComponentProvisionedResourcesInputRequestTypeDef",
     {
         "componentName": str,
     },
 )
 _OptionalListComponentProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1046,26 +1153,59 @@
         "identifier": str,
         "name": str,
         "provisioningEngine": ProvisionedResourceEngineType,
     },
     total=False,
 )
 
+ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsInputListComponentsPaginateTypeDef",
+    {
+        "environmentName": str,
+        "serviceInstanceName": str,
+        "serviceName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsInputRequestTypeDef = TypedDict(
     "ListComponentsInputRequestTypeDef",
     {
         "environmentName": str,
         "maxResults": int,
         "nextToken": str,
         "serviceInstanceName": str,
         "serviceName": str,
     },
     total=False,
 )
 
+_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
+    {
+        "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
+    },
+)
+_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
+    {
+        "environmentName": str,
+        "statuses": Sequence[EnvironmentAccountConnectionStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef(
+    _RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
+    _OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEnvironmentAccountConnectionsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentAccountConnectionsInputRequestTypeDef",
     {
         "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
     },
 )
 _OptionalListEnvironmentAccountConnectionsInputRequestTypeDef = TypedDict(
@@ -1081,14 +1221,34 @@
 
 class ListEnvironmentAccountConnectionsInputRequestTypeDef(
     _RequiredListEnvironmentAccountConnectionsInputRequestTypeDef,
     _OptionalListEnvironmentAccountConnectionsInputRequestTypeDef,
 ):
     pass
 
+_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
+    {
+        "environmentName": str,
+    },
+)
+_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef(
+    _RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
+    _OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEnvironmentOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentOutputsInputRequestTypeDef",
     {
         "environmentName": str,
     },
 )
 _OptionalListEnvironmentOutputsInputRequestTypeDef = TypedDict(
@@ -1101,14 +1261,34 @@
 
 class ListEnvironmentOutputsInputRequestTypeDef(
     _RequiredListEnvironmentOutputsInputRequestTypeDef,
     _OptionalListEnvironmentOutputsInputRequestTypeDef,
 ):
     pass
 
+_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
+    {
+        "environmentName": str,
+    },
+)
+_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef(
+    _RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
+    _OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef",
     {
         "environmentName": str,
     },
 )
 _OptionalListEnvironmentProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1121,14 +1301,35 @@
 
 class ListEnvironmentProvisionedResourcesInputRequestTypeDef(
     _RequiredListEnvironmentProvisionedResourcesInputRequestTypeDef,
     _OptionalListEnvironmentProvisionedResourcesInputRequestTypeDef,
 ):
     pass
 
+_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
+    {
+        "majorVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef(
+    _RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
+    _OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEnvironmentTemplateVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentTemplateVersionsInputRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListEnvironmentTemplateVersionsInputRequestTypeDef = TypedDict(
@@ -1143,47 +1344,86 @@
 
 class ListEnvironmentTemplateVersionsInputRequestTypeDef(
     _RequiredListEnvironmentTemplateVersionsInputRequestTypeDef,
     _OptionalListEnvironmentTemplateVersionsInputRequestTypeDef,
 ):
     pass
 
+ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef = TypedDict(
+    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentTemplatesInputRequestTypeDef = TypedDict(
     "ListEnvironmentTemplatesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListRepositoriesInputListRepositoriesPaginateTypeDef = TypedDict(
+    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRepositoriesInputRequestTypeDef = TypedDict(
     "ListRepositoriesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
 RepositorySummaryTypeDef = TypedDict(
     "RepositorySummaryTypeDef",
     {
         "arn": str,
+        "connectionArn": str,
         "name": str,
         "provider": RepositoryProviderType,
     },
 )
 
+_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
+    {
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "syncType": SyncTypeType,
+    },
+)
+_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef(
+    _RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
+    _OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRepositorySyncDefinitionsInputRequestTypeDef = TypedDict(
     "_RequiredListRepositorySyncDefinitionsInputRequestTypeDef",
     {
         "repositoryName": str,
         "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
+        "syncType": SyncTypeType,
     },
 )
 _OptionalListRepositorySyncDefinitionsInputRequestTypeDef = TypedDict(
     "_OptionalListRepositorySyncDefinitionsInputRequestTypeDef",
     {
         "nextToken": str,
     },
@@ -1202,14 +1442,35 @@
         "branch": str,
         "directory": str,
         "parent": str,
         "target": str,
     },
 )
 
+_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef(
+    _RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
+    _OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
+):
+    pass
+
 _RequiredListServiceInstanceOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListServiceInstanceOutputsInputRequestTypeDef",
     {
         "serviceInstanceName": str,
         "serviceName": str,
     },
 )
@@ -1223,14 +1484,35 @@
 
 class ListServiceInstanceOutputsInputRequestTypeDef(
     _RequiredListServiceInstanceOutputsInputRequestTypeDef,
     _OptionalListServiceInstanceOutputsInputRequestTypeDef,
 ):
     pass
 
+_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+    },
+)
+_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef(
+    _RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
+    _OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListServiceInstanceProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListServiceInstanceProvisionedResourcesInputRequestTypeDef",
     {
         "serviceInstanceName": str,
         "serviceName": str,
     },
 )
@@ -1282,14 +1564,34 @@
 )
 
 class ServiceInstanceSummaryTypeDef(
     _RequiredServiceInstanceSummaryTypeDef, _OptionalServiceInstanceSummaryTypeDef
 ):
     pass
 
+_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
+    "_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
+    "_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef(
+    _RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
+    _OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
+):
+    pass
+
 _RequiredListServicePipelineOutputsInputRequestTypeDef = TypedDict(
     "_RequiredListServicePipelineOutputsInputRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 _OptionalListServicePipelineOutputsInputRequestTypeDef = TypedDict(
@@ -1302,14 +1604,34 @@
 
 class ListServicePipelineOutputsInputRequestTypeDef(
     _RequiredListServicePipelineOutputsInputRequestTypeDef,
     _OptionalListServicePipelineOutputsInputRequestTypeDef,
 ):
     pass
 
+_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef(
+    _RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
+    _OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 _OptionalListServicePipelineProvisionedResourcesInputRequestTypeDef = TypedDict(
@@ -1322,14 +1644,35 @@
 
 class ListServicePipelineProvisionedResourcesInputRequestTypeDef(
     _RequiredListServicePipelineProvisionedResourcesInputRequestTypeDef,
     _OptionalListServicePipelineProvisionedResourcesInputRequestTypeDef,
 ):
     pass
 
+_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
+    {
+        "majorVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef(
+    _RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
+    _OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListServiceTemplateVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListServiceTemplateVersionsInputRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListServiceTemplateVersionsInputRequestTypeDef = TypedDict(
@@ -1371,14 +1714,22 @@
 )
 
 class ServiceTemplateVersionSummaryTypeDef(
     _RequiredServiceTemplateVersionSummaryTypeDef, _OptionalServiceTemplateVersionSummaryTypeDef
 ):
     pass
 
+ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef = TypedDict(
+    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceTemplatesInputRequestTypeDef = TypedDict(
     "ListServiceTemplatesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1405,14 +1756,22 @@
 )
 
 class ServiceTemplateSummaryTypeDef(
     _RequiredServiceTemplateSummaryTypeDef, _OptionalServiceTemplateSummaryTypeDef
 ):
     pass
 
+ListServicesInputListServicesPaginateTypeDef = TypedDict(
+    "ListServicesInputListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesInputRequestTypeDef = TypedDict(
     "ListServicesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1437,14 +1796,34 @@
     },
     total=False,
 )
 
 class ServiceSummaryTypeDef(_RequiredServiceSummaryTypeDef, _OptionalServiceSummaryTypeDef):
     pass
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -1457,14 +1836,24 @@
 )
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
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
 RejectEnvironmentAccountConnectionInputRequestTypeDef = TypedDict(
     "RejectEnvironmentAccountConnectionInputRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -1506,22 +1895,41 @@
 )
 
 class ResourceSyncEventTypeDef(
     _RequiredResourceSyncEventTypeDef, _OptionalResourceSyncEventTypeDef
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
 S3ObjectSourceTypeDef = TypedDict(
     "S3ObjectSourceTypeDef",
     {
         "bucket": str,
         "key": str,
     },
 )
 
+SyncBlockerContextTypeDef = TypedDict(
+    "SyncBlockerContextTypeDef",
+    {
+        "key": str,
+        "value": str,
+    },
+)
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1532,14 +1940,15 @@
         "deploymentType": ComponentDeploymentUpdateTypeType,
         "name": str,
     },
 )
 _OptionalUpdateComponentInputRequestTypeDef = TypedDict(
     "_OptionalUpdateComponentInputRequestTypeDef",
     {
+        "clientToken": str,
         "description": str,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
         "templateFile": str,
     },
     total=False,
@@ -1643,14 +2052,15 @@
         "name": str,
         "serviceName": str,
     },
 )
 _OptionalUpdateServiceInstanceInputRequestTypeDef = TypedDict(
     "_OptionalUpdateServiceInstanceInputRequestTypeDef",
     {
+        "clientToken": str,
         "spec": str,
         "templateMajorVersion": str,
         "templateMinorVersion": str,
     },
     total=False,
 )
 
@@ -1679,14 +2089,33 @@
 
 class UpdateServicePipelineInputRequestTypeDef(
     _RequiredUpdateServicePipelineInputRequestTypeDef,
     _OptionalUpdateServicePipelineInputRequestTypeDef,
 ):
     pass
 
+UpdateServiceSyncBlockerInputRequestTypeDef = TypedDict(
+    "UpdateServiceSyncBlockerInputRequestTypeDef",
+    {
+        "id": str,
+        "resolvedReason": str,
+    },
+)
+
+UpdateServiceSyncConfigInputRequestTypeDef = TypedDict(
+    "UpdateServiceSyncConfigInputRequestTypeDef",
+    {
+        "branch": str,
+        "filePath": str,
+        "repositoryName": str,
+        "repositoryProvider": RepositoryProviderType,
+        "serviceName": str,
+    },
+)
+
 _RequiredUpdateServiceTemplateInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateServiceTemplateInputRequestTypeDef = TypedDict(
@@ -1728,55 +2157,55 @@
 ):
     pass
 
 AcceptEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "AcceptEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "CreateEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "DeleteEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "GetEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "RejectEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentAccountConnectionOutputTypeDef = TypedDict(
     "UpdateEnvironmentAccountConnectionOutputTypeDef",
     {
         "environmentAccountConnection": EnvironmentAccountConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccountSettingsTypeDef = TypedDict(
     "AccountSettingsTypeDef",
     {
         "pipelineCodebuildRoleArn": str,
@@ -1820,79 +2249,87 @@
 class EnvironmentTypeDef(_RequiredEnvironmentTypeDef, _OptionalEnvironmentTypeDef):
     pass
 
 CancelComponentDeploymentOutputTypeDef = TypedDict(
     "CancelComponentDeploymentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateComponentOutputTypeDef = TypedDict(
     "CreateComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteComponentOutputTypeDef = TypedDict(
     "DeleteComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentOutputTypeDef = TypedDict(
     "GetComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateComponentOutputTypeDef = TypedDict(
     "UpdateComponentOutputTypeDef",
     {
         "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelServiceInstanceDeploymentOutputTypeDef = TypedDict(
     "CancelServiceInstanceDeploymentOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateServiceInstanceOutputTypeDef = TypedDict(
+    "CreateServiceInstanceOutputTypeDef",
+    {
+        "serviceInstance": ServiceInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceInstanceOutputTypeDef = TypedDict(
     "GetServiceInstanceOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceInstanceOutputTypeDef = TypedDict(
     "UpdateServiceInstanceOutputTypeDef",
     {
         "serviceInstance": ServiceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelServicePipelineDeploymentOutputTypeDef = TypedDict(
     "CancelServicePipelineDeploymentOutputTypeDef",
     {
         "pipeline": ServicePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredServiceTypeDef = TypedDict(
     "_RequiredServiceTypeDef",
     {
         "arn": str,
@@ -1920,15 +2357,15 @@
 class ServiceTypeDef(_RequiredServiceTypeDef, _OptionalServiceTypeDef):
     pass
 
 UpdateServicePipelineOutputTypeDef = TypedDict(
     "UpdateServicePipelineOutputTypeDef",
     {
         "pipeline": ServicePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateServiceTemplateVersionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceTemplateVersionInputRequestTypeDef",
     {
         "majorVersion": str,
@@ -1984,15 +2421,15 @@
     pass
 
 ListComponentsOutputTypeDef = TypedDict(
     "ListComponentsOutputTypeDef",
     {
         "components": List[ComponentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CountsSummaryTypeDef = TypedDict(
     "CountsSummaryTypeDef",
     {
         "components": ResourceCountsSummaryTypeDef,
@@ -2013,14 +2450,15 @@
         "name": str,
         "templateFile": str,
     },
 )
 _OptionalCreateComponentInputRequestTypeDef = TypedDict(
     "_OptionalCreateComponentInputRequestTypeDef",
     {
+        "clientToken": str,
         "description": str,
         "environmentName": str,
         "serviceInstanceName": str,
         "serviceName": str,
         "serviceSpec": str,
         "tags": Sequence[TagTypeDef],
     },
@@ -2126,14 +2564,39 @@
 )
 
 class CreateServiceInputRequestTypeDef(
     _RequiredCreateServiceInputRequestTypeDef, _OptionalCreateServiceInputRequestTypeDef
 ):
     pass
 
+_RequiredCreateServiceInstanceInputRequestTypeDef = TypedDict(
+    "_RequiredCreateServiceInstanceInputRequestTypeDef",
+    {
+        "name": str,
+        "serviceName": str,
+        "spec": str,
+    },
+)
+_OptionalCreateServiceInstanceInputRequestTypeDef = TypedDict(
+    "_OptionalCreateServiceInstanceInputRequestTypeDef",
+    {
+        "clientToken": str,
+        "tags": Sequence[TagTypeDef],
+        "templateMajorVersion": str,
+        "templateMinorVersion": str,
+    },
+    total=False,
+)
+
+class CreateServiceInstanceInputRequestTypeDef(
+    _RequiredCreateServiceInstanceInputRequestTypeDef,
+    _OptionalCreateServiceInstanceInputRequestTypeDef,
+):
+    pass
+
 _RequiredCreateServiceTemplateInputRequestTypeDef = TypedDict(
     "_RequiredCreateServiceTemplateInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateServiceTemplateInputRequestTypeDef = TypedDict(
@@ -2155,15 +2618,15 @@
     pass
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "nextToken": str,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -2239,180 +2702,221 @@
 ):
     pass
 
 CreateEnvironmentTemplateOutputTypeDef = TypedDict(
     "CreateEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentTemplateOutputTypeDef = TypedDict(
     "DeleteEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentTemplateOutputTypeDef = TypedDict(
     "GetEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentTemplateOutputTypeDef = TypedDict(
     "UpdateEnvironmentTemplateOutputTypeDef",
     {
         "environmentTemplate": EnvironmentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "CreateEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "DeleteEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "GetEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentTemplateVersionOutputTypeDef = TypedDict(
     "UpdateEnvironmentTemplateVersionOutputTypeDef",
     {
         "environmentTemplateVersion": EnvironmentTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryOutputTypeDef = TypedDict(
     "CreateRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryOutputTypeDef = TypedDict(
     "DeleteRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositoryOutputTypeDef = TypedDict(
     "GetRepositoryOutputTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateServiceSyncConfigOutputTypeDef = TypedDict(
+    "CreateServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteServiceSyncConfigOutputTypeDef = TypedDict(
+    "DeleteServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceSyncConfigOutputTypeDef = TypedDict(
+    "GetServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateServiceSyncConfigOutputTypeDef = TypedDict(
+    "UpdateServiceSyncConfigOutputTypeDef",
+    {
+        "serviceSyncConfig": ServiceSyncConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceTemplateOutputTypeDef = TypedDict(
     "CreateServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceTemplateOutputTypeDef = TypedDict(
     "DeleteServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceTemplateOutputTypeDef = TypedDict(
     "GetServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceTemplateOutputTypeDef = TypedDict(
     "UpdateServiceTemplateOutputTypeDef",
     {
         "serviceTemplate": ServiceTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTemplateSyncConfigOutputTypeDef = TypedDict(
     "CreateTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTemplateSyncConfigOutputTypeDef = TypedDict(
     "DeleteTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSyncConfigOutputTypeDef = TypedDict(
     "GetTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTemplateSyncConfigOutputTypeDef = TypedDict(
     "UpdateTemplateSyncConfigOutputTypeDef",
     {
         "templateSyncConfig": TemplateSyncConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentAccountConnectionsOutputTypeDef = TypedDict(
     "ListEnvironmentAccountConnectionsOutputTypeDef",
     {
         "environmentAccountConnections": List[EnvironmentAccountConnectionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsOutputTypeDef = TypedDict(
     "ListEnvironmentsOutputTypeDef",
     {
         "environments": List[EnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
+    {
+        "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsInputRequestTypeDef = TypedDict(
     "ListEnvironmentsInputRequestTypeDef",
     {
         "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
@@ -2420,24 +2924,24 @@
 )
 
 ListEnvironmentTemplatesOutputTypeDef = TypedDict(
     "ListEnvironmentTemplatesOutputTypeDef",
     {
         "nextToken": str,
         "templates": List[EnvironmentTemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentTemplateVersionsOutputTypeDef = TypedDict(
     "ListEnvironmentTemplateVersionsOutputTypeDef",
     {
         "nextToken": str,
         "templateVersions": List[EnvironmentTemplateVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetComponentInputComponentDeletedWaitTypeDef = TypedDict(
     "_RequiredGetComponentInputComponentDeletedWaitTypeDef",
     {
         "name": str,
@@ -2638,367 +3142,47 @@
 
 class GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef(
     _RequiredGetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
     _OptionalGetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
 ):
     pass
 
-_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    {
-        "componentName": str,
-    },
-)
-_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListComponentOutputsInputListComponentOutputsPaginateTypeDef(
-    _RequiredListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-    _OptionalListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-):
-    pass
-
-_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    {
-        "componentName": str,
-    },
-)
-_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef(
-    _RequiredListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-    _OptionalListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    {
-        "environmentName": str,
-        "serviceInstanceName": str,
-        "serviceName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    {
-        "requestedBy": EnvironmentAccountConnectionRequesterAccountTypeType,
-    },
-)
-_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef",
-    {
-        "environmentName": str,
-        "statuses": Sequence[EnvironmentAccountConnectionStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef(
-    _RequiredListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-    _OptionalListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    {
-        "environmentName": str,
-    },
-)
-_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef(
-    _RequiredListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-    _OptionalListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-):
-    pass
-
-_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    {
-        "environmentName": str,
-    },
-)
-_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef(
-    _RequiredListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-    _OptionalListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef",
-    {
-        "majorVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef(
-    _RequiredListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-    _OptionalListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef = TypedDict(
-    "ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    {
-        "environmentTemplates": Sequence[EnvironmentTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRepositoriesInputListRepositoriesPaginateTypeDef = TypedDict(
-    "ListRepositoriesInputListRepositoriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    {
-        "repositoryName": str,
-        "repositoryProvider": RepositoryProviderType,
-        "syncType": Literal["TEMPLATE_SYNC"],
-    },
-)
-_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef(
-    _RequiredListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-    _OptionalListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    {
-        "serviceInstanceName": str,
-        "serviceName": str,
-    },
-)
-_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef(
-    _RequiredListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-    _OptionalListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-):
-    pass
-
-_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    {
-        "serviceInstanceName": str,
-        "serviceName": str,
-    },
-)
-_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef(
-    _RequiredListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-    _OptionalListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
-    "_RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    {
-        "serviceName": str,
-    },
-)
-_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef = TypedDict(
-    "_OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef(
-    _RequiredListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-    _OptionalListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-):
-    pass
-
-_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    {
-        "serviceName": str,
-    },
-)
-_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef(
-    _RequiredListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-    _OptionalListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef",
-    {
-        "majorVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef(
-    _RequiredListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-    _OptionalListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef = TypedDict(
-    "ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServicesInputListServicesPaginateTypeDef = TypedDict(
-    "ListServicesInputListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
 ListComponentOutputsOutputTypeDef = TypedDict(
     "ListComponentOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentOutputsOutputTypeDef = TypedDict(
     "ListEnvironmentOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstanceOutputsOutputTypeDef = TypedDict(
     "ListServiceInstanceOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicePipelineOutputsOutputTypeDef = TypedDict(
     "ListServicePipelineOutputsOutputTypeDef",
     {
         "nextToken": str,
         "outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNotifyResourceDeploymentStatusChangeInputRequestTypeDef = TypedDict(
     "_RequiredNotifyResourceDeploymentStatusChangeInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -3022,71 +3206,71 @@
     pass
 
 ListComponentProvisionedResourcesOutputTypeDef = TypedDict(
     "ListComponentProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentProvisionedResourcesOutputTypeDef = TypedDict(
     "ListEnvironmentProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstanceProvisionedResourcesOutputTypeDef = TypedDict(
     "ListServiceInstanceProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicePipelineProvisionedResourcesOutputTypeDef = TypedDict(
     "ListServicePipelineProvisionedResourcesOutputTypeDef",
     {
         "nextToken": str,
         "provisionedResources": List[ProvisionedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesOutputTypeDef = TypedDict(
     "ListRepositoriesOutputTypeDef",
     {
         "nextToken": str,
         "repositories": List[RepositorySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositorySyncDefinitionsOutputTypeDef = TypedDict(
     "ListRepositorySyncDefinitionsOutputTypeDef",
     {
         "nextToken": str,
         "syncDefinitions": List[RepositorySyncDefinitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceInstancesInputListServiceInstancesPaginateTypeDef = TypedDict(
     "ListServiceInstancesInputListServiceInstancesPaginateTypeDef",
     {
         "filters": Sequence[ListServiceInstancesFilterTypeDef],
         "serviceName": str,
         "sortBy": ListServiceInstancesSortByType,
         "sortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServiceInstancesInputRequestTypeDef = TypedDict(
     "ListServiceInstancesInputRequestTypeDef",
     {
@@ -3101,42 +3285,42 @@
 )
 
 ListServiceInstancesOutputTypeDef = TypedDict(
     "ListServiceInstancesOutputTypeDef",
     {
         "nextToken": str,
         "serviceInstances": List[ServiceInstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceTemplateVersionsOutputTypeDef = TypedDict(
     "ListServiceTemplateVersionsOutputTypeDef",
     {
         "nextToken": str,
         "templateVersions": List[ServiceTemplateVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceTemplatesOutputTypeDef = TypedDict(
     "ListServiceTemplatesOutputTypeDef",
     {
         "nextToken": str,
         "templates": List[ServiceTemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesOutputTypeDef = TypedDict(
     "ListServicesOutputTypeDef",
     {
         "nextToken": str,
         "services": List[ServiceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RepositorySyncAttemptTypeDef = TypedDict(
     "RepositorySyncAttemptTypeDef",
     {
         "events": List[RepositorySyncEventTypeDef],
@@ -3161,157 +3345,190 @@
     "TemplateVersionSourceInputTypeDef",
     {
         "s3": S3ObjectSourceTypeDef,
     },
     total=False,
 )
 
+_RequiredSyncBlockerTypeDef = TypedDict(
+    "_RequiredSyncBlockerTypeDef",
+    {
+        "createdAt": datetime,
+        "createdReason": str,
+        "id": str,
+        "status": BlockerStatusType,
+        "type": Literal["AUTOMATED"],
+    },
+)
+_OptionalSyncBlockerTypeDef = TypedDict(
+    "_OptionalSyncBlockerTypeDef",
+    {
+        "contexts": List[SyncBlockerContextTypeDef],
+        "resolvedAt": datetime,
+        "resolvedReason": str,
+    },
+    total=False,
+)
+
+class SyncBlockerTypeDef(_RequiredSyncBlockerTypeDef, _OptionalSyncBlockerTypeDef):
+    pass
+
 GetAccountSettingsOutputTypeDef = TypedDict(
     "GetAccountSettingsOutputTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountSettingsOutputTypeDef = TypedDict(
     "UpdateAccountSettingsOutputTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelEnvironmentDeploymentOutputTypeDef = TypedDict(
     "CancelEnvironmentDeploymentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentOutputTypeDef = TypedDict(
     "CreateEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEnvironmentOutputTypeDef = TypedDict(
     "DeleteEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentOutputTypeDef = TypedDict(
     "GetEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentOutputTypeDef = TypedDict(
     "UpdateEnvironmentOutputTypeDef",
     {
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceOutputTypeDef = TypedDict(
     "CreateServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceOutputTypeDef = TypedDict(
     "DeleteServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceOutputTypeDef = TypedDict(
     "GetServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceOutputTypeDef = TypedDict(
     "UpdateServiceOutputTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceTemplateVersionOutputTypeDef = TypedDict(
     "CreateServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceTemplateVersionOutputTypeDef = TypedDict(
     "DeleteServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceTemplateVersionOutputTypeDef = TypedDict(
     "GetServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceTemplateVersionOutputTypeDef = TypedDict(
     "UpdateServiceTemplateVersionOutputTypeDef",
     {
         "serviceTemplateVersion": ServiceTemplateVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesSummaryOutputTypeDef = TypedDict(
     "GetResourcesSummaryOutputTypeDef",
     {
         "counts": CountsSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositorySyncStatusOutputTypeDef = TypedDict(
     "GetRepositorySyncStatusOutputTypeDef",
     {
         "latestSync": RepositorySyncAttemptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceInstanceSyncStatusOutputTypeDef = TypedDict(
+    "GetServiceInstanceSyncStatusOutputTypeDef",
+    {
+        "desiredState": RevisionTypeDef,
+        "latestSuccessfulSync": ResourceSyncAttemptTypeDef,
+        "latestSync": ResourceSyncAttemptTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateSyncStatusOutputTypeDef = TypedDict(
     "GetTemplateSyncStatusOutputTypeDef",
     {
         "desiredState": RevisionTypeDef,
         "latestSuccessfulSync": ResourceSyncAttemptTypeDef,
         "latestSync": ResourceSyncAttemptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEnvironmentTemplateVersionInputRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentTemplateVersionInputRequestTypeDef",
     {
         "source": TemplateVersionSourceInputTypeDef,
@@ -3356,7 +3573,45 @@
 )
 
 class CreateServiceTemplateVersionInputRequestTypeDef(
     _RequiredCreateServiceTemplateVersionInputRequestTypeDef,
     _OptionalCreateServiceTemplateVersionInputRequestTypeDef,
 ):
     pass
+
+_RequiredServiceSyncBlockerSummaryTypeDef = TypedDict(
+    "_RequiredServiceSyncBlockerSummaryTypeDef",
+    {
+        "serviceName": str,
+    },
+)
+_OptionalServiceSyncBlockerSummaryTypeDef = TypedDict(
+    "_OptionalServiceSyncBlockerSummaryTypeDef",
+    {
+        "latestBlockers": List[SyncBlockerTypeDef],
+        "serviceInstanceName": str,
+    },
+    total=False,
+)
+
+class ServiceSyncBlockerSummaryTypeDef(
+    _RequiredServiceSyncBlockerSummaryTypeDef, _OptionalServiceSyncBlockerSummaryTypeDef
+):
+    pass
+
+UpdateServiceSyncBlockerOutputTypeDef = TypedDict(
+    "UpdateServiceSyncBlockerOutputTypeDef",
+    {
+        "serviceInstanceName": str,
+        "serviceName": str,
+        "serviceSyncBlocker": SyncBlockerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetServiceSyncBlockerSummaryOutputTypeDef = TypedDict(
+    "GetServiceSyncBlockerSummaryOutputTypeDef",
+    {
+        "serviceSyncBlockerSummary": ServiceSyncBlockerSummaryTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
```

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/waiter.py` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton/waiter.pyi` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/PKG-INFO` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-proton
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Proton 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Proton 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-proton"></a>
 
 # types-aiobotocore-proton
 
 [![PyPI - types-aiobotocore-proton](https://img.shields.io/pypi/v/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-proton.svg?color=blue)](https://pypi.org/project/types-aiobotocore-proton)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-proton?color=blue)](https://pypistats.org/packages/types-aiobotocore-proton)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Proton 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
+[aiobotocore.Proton 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/proton.html#Proton)
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
 [types-aiobotocore-proton docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_proton/).
 
 See how it helps to find and fix potential bugs:
 
@@ -420,14 +420,16 @@
 ### Literals
 
 `types_aiobotocore_proton.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_proton.literals import (
+    BlockerStatusType,
+    BlockerTypeType,
     ComponentDeletedWaiterName,
     ComponentDeployedWaiterName,
     ComponentDeploymentUpdateTypeType,
     DeploymentStatusType,
     DeploymentUpdateTypeType,
     EnvironmentAccountConnectionRequesterAccountTypeType,
     EnvironmentAccountConnectionStatusType,
@@ -478,30 +480,29 @@
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
 )
 
 
-def check_value(value: ComponentDeletedWaiterName) -> bool:
+def check_value(value: BlockerStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_proton.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_proton.type_defs import (
     AcceptEnvironmentAccountConnectionInputRequestTypeDef,
     EnvironmentAccountConnectionTypeDef,
-    ResponseMetadataTypeDef,
     RepositoryBranchTypeDef,
     CancelComponentDeploymentInputRequestTypeDef,
     ComponentTypeDef,
     CancelEnvironmentDeploymentInputRequestTypeDef,
     CancelServiceInstanceDeploymentInputRequestTypeDef,
     ServiceInstanceTypeDef,
     CancelServicePipelineDeploymentInputRequestTypeDef,
@@ -511,24 +512,27 @@
     ComponentSummaryTypeDef,
     ResourceCountsSummaryTypeDef,
     TagTypeDef,
     RepositoryBranchInputTypeDef,
     EnvironmentTemplateTypeDef,
     EnvironmentTemplateVersionTypeDef,
     RepositoryTypeDef,
+    CreateServiceSyncConfigInputRequestTypeDef,
+    ServiceSyncConfigTypeDef,
     ServiceTemplateTypeDef,
     CreateTemplateSyncConfigInputRequestTypeDef,
     TemplateSyncConfigTypeDef,
     DeleteComponentInputRequestTypeDef,
     DeleteEnvironmentAccountConnectionInputRequestTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DeleteEnvironmentTemplateInputRequestTypeDef,
     DeleteEnvironmentTemplateVersionInputRequestTypeDef,
     DeleteRepositoryInputRequestTypeDef,
     DeleteServiceInputRequestTypeDef,
+    DeleteServiceSyncConfigInputRequestTypeDef,
     DeleteServiceTemplateInputRequestTypeDef,
     DeleteServiceTemplateVersionInputRequestTypeDef,
     DeleteTemplateSyncConfigInputRequestTypeDef,
     EnvironmentAccountConnectionSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     EnvironmentTemplateFilterTypeDef,
     EnvironmentTemplateSummaryTypeDef,
@@ -539,59 +543,84 @@
     GetEnvironmentInputRequestTypeDef,
     GetEnvironmentTemplateInputRequestTypeDef,
     GetEnvironmentTemplateVersionInputRequestTypeDef,
     GetRepositoryInputRequestTypeDef,
     GetRepositorySyncStatusInputRequestTypeDef,
     GetServiceInputRequestTypeDef,
     GetServiceInstanceInputRequestTypeDef,
+    GetServiceInstanceSyncStatusInputRequestTypeDef,
+    RevisionTypeDef,
+    GetServiceSyncBlockerSummaryInputRequestTypeDef,
+    GetServiceSyncConfigInputRequestTypeDef,
     GetServiceTemplateInputRequestTypeDef,
     GetServiceTemplateVersionInputRequestTypeDef,
     GetTemplateSyncConfigInputRequestTypeDef,
     GetTemplateSyncStatusInputRequestTypeDef,
-    RevisionTypeDef,
-    PaginatorConfigTypeDef,
+    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
     ListComponentOutputsInputRequestTypeDef,
     OutputTypeDef,
+    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
     ListComponentProvisionedResourcesInputRequestTypeDef,
     ProvisionedResourceTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
     ListEnvironmentAccountConnectionsInputRequestTypeDef,
+    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
     ListEnvironmentOutputsInputRequestTypeDef,
+    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
     ListEnvironmentProvisionedResourcesInputRequestTypeDef,
+    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
     ListEnvironmentTemplateVersionsInputRequestTypeDef,
+    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
     ListEnvironmentTemplatesInputRequestTypeDef,
+    ListRepositoriesInputListRepositoriesPaginateTypeDef,
     ListRepositoriesInputRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
     ListRepositorySyncDefinitionsInputRequestTypeDef,
     RepositorySyncDefinitionTypeDef,
+    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
     ListServiceInstanceOutputsInputRequestTypeDef,
+    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
     ListServiceInstanceProvisionedResourcesInputRequestTypeDef,
     ListServiceInstancesFilterTypeDef,
     ServiceInstanceSummaryTypeDef,
+    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
     ListServicePipelineOutputsInputRequestTypeDef,
+    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
     ListServicePipelineProvisionedResourcesInputRequestTypeDef,
+    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
     ListServiceTemplateVersionsInputRequestTypeDef,
     ServiceTemplateVersionSummaryTypeDef,
+    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
     ListServiceTemplatesInputRequestTypeDef,
     ServiceTemplateSummaryTypeDef,
+    ListServicesInputListServicesPaginateTypeDef,
     ListServicesInputRequestTypeDef,
     ServiceSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     RejectEnvironmentAccountConnectionInputRequestTypeDef,
     RepositorySyncEventTypeDef,
     ResourceSyncEventTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectSourceTypeDef,
+    SyncBlockerContextTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateComponentInputRequestTypeDef,
     UpdateEnvironmentAccountConnectionInputRequestTypeDef,
     UpdateEnvironmentTemplateInputRequestTypeDef,
     UpdateEnvironmentTemplateVersionInputRequestTypeDef,
     UpdateServiceInputRequestTypeDef,
     UpdateServiceInstanceInputRequestTypeDef,
     UpdateServicePipelineInputRequestTypeDef,
+    UpdateServiceSyncBlockerInputRequestTypeDef,
+    UpdateServiceSyncConfigInputRequestTypeDef,
     UpdateServiceTemplateInputRequestTypeDef,
     UpdateTemplateSyncConfigInputRequestTypeDef,
     AcceptEnvironmentAccountConnectionOutputTypeDef,
     CreateEnvironmentAccountConnectionOutputTypeDef,
     DeleteEnvironmentAccountConnectionOutputTypeDef,
     GetEnvironmentAccountConnectionOutputTypeDef,
     RejectEnvironmentAccountConnectionOutputTypeDef,
@@ -600,28 +629,30 @@
     EnvironmentTypeDef,
     CancelComponentDeploymentOutputTypeDef,
     CreateComponentOutputTypeDef,
     DeleteComponentOutputTypeDef,
     GetComponentOutputTypeDef,
     UpdateComponentOutputTypeDef,
     CancelServiceInstanceDeploymentOutputTypeDef,
+    CreateServiceInstanceOutputTypeDef,
     GetServiceInstanceOutputTypeDef,
     UpdateServiceInstanceOutputTypeDef,
     CancelServicePipelineDeploymentOutputTypeDef,
     ServiceTypeDef,
     UpdateServicePipelineOutputTypeDef,
     UpdateServiceTemplateVersionInputRequestTypeDef,
     ServiceTemplateVersionTypeDef,
     ListComponentsOutputTypeDef,
     CountsSummaryTypeDef,
     CreateComponentInputRequestTypeDef,
     CreateEnvironmentAccountConnectionInputRequestTypeDef,
     CreateEnvironmentTemplateInputRequestTypeDef,
     CreateRepositoryInputRequestTypeDef,
     CreateServiceInputRequestTypeDef,
+    CreateServiceInstanceInputRequestTypeDef,
     CreateServiceTemplateInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     CreateEnvironmentTemplateOutputTypeDef,
@@ -631,56 +662,42 @@
     CreateEnvironmentTemplateVersionOutputTypeDef,
     DeleteEnvironmentTemplateVersionOutputTypeDef,
     GetEnvironmentTemplateVersionOutputTypeDef,
     UpdateEnvironmentTemplateVersionOutputTypeDef,
     CreateRepositoryOutputTypeDef,
     DeleteRepositoryOutputTypeDef,
     GetRepositoryOutputTypeDef,
+    CreateServiceSyncConfigOutputTypeDef,
+    DeleteServiceSyncConfigOutputTypeDef,
+    GetServiceSyncConfigOutputTypeDef,
+    UpdateServiceSyncConfigOutputTypeDef,
     CreateServiceTemplateOutputTypeDef,
     DeleteServiceTemplateOutputTypeDef,
     GetServiceTemplateOutputTypeDef,
     UpdateServiceTemplateOutputTypeDef,
     CreateTemplateSyncConfigOutputTypeDef,
     DeleteTemplateSyncConfigOutputTypeDef,
     GetTemplateSyncConfigOutputTypeDef,
     UpdateTemplateSyncConfigOutputTypeDef,
     ListEnvironmentAccountConnectionsOutputTypeDef,
     ListEnvironmentsOutputTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
     ListEnvironmentTemplatesOutputTypeDef,
     ListEnvironmentTemplateVersionsOutputTypeDef,
     GetComponentInputComponentDeletedWaitTypeDef,
     GetComponentInputComponentDeployedWaitTypeDef,
     GetEnvironmentInputEnvironmentDeployedWaitTypeDef,
     GetEnvironmentTemplateVersionInputEnvironmentTemplateVersionRegisteredWaitTypeDef,
     GetServiceInputServiceCreatedWaitTypeDef,
     GetServiceInputServiceDeletedWaitTypeDef,
     GetServiceInputServicePipelineDeployedWaitTypeDef,
     GetServiceInputServiceUpdatedWaitTypeDef,
     GetServiceInstanceInputServiceInstanceDeployedWaitTypeDef,
     GetServiceTemplateVersionInputServiceTemplateVersionRegisteredWaitTypeDef,
-    ListComponentOutputsInputListComponentOutputsPaginateTypeDef,
-    ListComponentProvisionedResourcesInputListComponentProvisionedResourcesPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListEnvironmentAccountConnectionsInputListEnvironmentAccountConnectionsPaginateTypeDef,
-    ListEnvironmentOutputsInputListEnvironmentOutputsPaginateTypeDef,
-    ListEnvironmentProvisionedResourcesInputListEnvironmentProvisionedResourcesPaginateTypeDef,
-    ListEnvironmentTemplateVersionsInputListEnvironmentTemplateVersionsPaginateTypeDef,
-    ListEnvironmentTemplatesInputListEnvironmentTemplatesPaginateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
-    ListRepositoriesInputListRepositoriesPaginateTypeDef,
-    ListRepositorySyncDefinitionsInputListRepositorySyncDefinitionsPaginateTypeDef,
-    ListServiceInstanceOutputsInputListServiceInstanceOutputsPaginateTypeDef,
-    ListServiceInstanceProvisionedResourcesInputListServiceInstanceProvisionedResourcesPaginateTypeDef,
-    ListServicePipelineOutputsInputListServicePipelineOutputsPaginateTypeDef,
-    ListServicePipelineProvisionedResourcesInputListServicePipelineProvisionedResourcesPaginateTypeDef,
-    ListServiceTemplateVersionsInputListServiceTemplateVersionsPaginateTypeDef,
-    ListServiceTemplatesInputListServiceTemplatesPaginateTypeDef,
-    ListServicesInputListServicesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListComponentOutputsOutputTypeDef,
     ListEnvironmentOutputsOutputTypeDef,
     ListServiceInstanceOutputsOutputTypeDef,
     ListServicePipelineOutputsOutputTypeDef,
     NotifyResourceDeploymentStatusChangeInputRequestTypeDef,
     ListComponentProvisionedResourcesOutputTypeDef,
     ListEnvironmentProvisionedResourcesOutputTypeDef,
@@ -693,14 +710,15 @@
     ListServiceInstancesOutputTypeDef,
     ListServiceTemplateVersionsOutputTypeDef,
     ListServiceTemplatesOutputTypeDef,
     ListServicesOutputTypeDef,
     RepositorySyncAttemptTypeDef,
     ResourceSyncAttemptTypeDef,
     TemplateVersionSourceInputTypeDef,
+    SyncBlockerTypeDef,
     GetAccountSettingsOutputTypeDef,
     UpdateAccountSettingsOutputTypeDef,
     CancelEnvironmentDeploymentOutputTypeDef,
     CreateEnvironmentOutputTypeDef,
     DeleteEnvironmentOutputTypeDef,
     GetEnvironmentOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
@@ -710,60 +728,64 @@
     UpdateServiceOutputTypeDef,
     CreateServiceTemplateVersionOutputTypeDef,
     DeleteServiceTemplateVersionOutputTypeDef,
     GetServiceTemplateVersionOutputTypeDef,
     UpdateServiceTemplateVersionOutputTypeDef,
     GetResourcesSummaryOutputTypeDef,
     GetRepositorySyncStatusOutputTypeDef,
+    GetServiceInstanceSyncStatusOutputTypeDef,
     GetTemplateSyncStatusOutputTypeDef,
     CreateEnvironmentTemplateVersionInputRequestTypeDef,
     CreateServiceTemplateVersionInputRequestTypeDef,
+    ServiceSyncBlockerSummaryTypeDef,
+    UpdateServiceSyncBlockerOutputTypeDef,
+    GetServiceSyncBlockerSummaryOutputTypeDef,
 )
 
 
 def get_structure() -> AcceptEnvironmentAccountConnectionInputRequestTypeDef:
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

### Comparing `types-aiobotocore-proton-2.5.0.post1/types_aiobotocore_proton.egg-info/SOURCES.txt` & `types-aiobotocore-proton-2.5.1/types_aiobotocore_proton.egg-info/SOURCES.txt`

 * *Files identical despite different names*

