# Comparing `tmp/types-aiobotocore-discovery-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-discovery-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-discovery-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-discovery-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-discovery-2.5.0.post1.tar` & `types-aiobotocore-discovery-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.911135 types-aiobotocore-discovery-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17229 2023-03-11 12:26:30.907135 types-aiobotocore-discovery-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15632 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:30.911135 types-aiobotocore-discovery-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.895135 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/
--rw-r--r--   0 runner    (1001) docker     (123)     1925 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1924 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24524 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24484 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9750 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9748 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8805 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8796 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23853 2023-03-11 12:12:31.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23832 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.907135 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17229 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:30.000000 types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.670124 types-aiobotocore-discovery-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17452 2023-06-28 01:43:22.670124 types-aiobotocore-discovery-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15861 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.670124 types-aiobotocore-discovery-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2150 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.666124 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/
+-rw-r--r--   0 runner    (1001) docker     (123)     1925 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1924 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24648 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24608 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10272 2023-06-28 01:29:09.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10270 2023-06-28 01:29:09.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8697 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8689 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25199 2023-06-28 01:29:09.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25178 2023-06-28 01:29:09.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:08.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.670124 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17452 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:22.000000 types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/LICENSE` & `types-aiobotocore-discovery-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/PKG-INFO` & `types-aiobotocore-discovery-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-discovery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-discovery"></a>
 
 # types-aiobotocore-discovery
 
 [![PyPI - types-aiobotocore-discovery](https://img.shields.io/pypi/v/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-discovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-discovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationDiscoveryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
+[aiobotocore.ApplicationDiscoveryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
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
 [types-aiobotocore-discovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,14 +327,18 @@
     DescribeExportTasksPaginatorName,
     DescribeTagsPaginatorName,
     ExportDataFormatType,
     ExportStatusType,
     ImportStatusType,
     ImportTaskFilterNameType,
     ListConfigurationsPaginatorName,
+    OfferingClassType,
+    PurchasingOptionType,
+    TenancyType,
+    TermLengthType,
     orderStringType,
     ApplicationDiscoveryServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -354,120 +358,124 @@
 ```python
 from types_aiobotocore_discovery.type_defs import (
     AgentConfigurationStatusTypeDef,
     AgentNetworkInfoTypeDef,
     AssociateConfigurationItemsToApplicationRequestRequestTypeDef,
     BatchDeleteImportDataErrorTypeDef,
     BatchDeleteImportDataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ConfigurationTagTypeDef,
     ContinuousExportDescriptionTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     TagTypeDef,
     CustomerAgentInfoTypeDef,
     CustomerAgentlessCollectorInfoTypeDef,
     CustomerConnectorInfoTypeDef,
     CustomerMeCollectorInfoTypeDef,
     DeleteApplicationsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeConfigurationsRequestRequestTypeDef,
+    DescribeConfigurationsResponseTypeDef,
+    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
     DescribeContinuousExportsRequestRequestTypeDef,
+    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
     DescribeExportConfigurationsRequestRequestTypeDef,
     ExportInfoTypeDef,
     ExportFilterTypeDef,
     ImportTaskFilterTypeDef,
     ImportTaskTypeDef,
     TagFilterTypeDef,
     DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef,
+    ReservedInstanceOptionsTypeDef,
+    UsageMetricBasisTypeDef,
+    ExportConfigurationsResponseTypeDef,
     OrderByElementTypeDef,
+    ListConfigurationsResponseTypeDef,
     ListServerNeighborsRequestRequestTypeDef,
     NeighborConnectionDetailTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsRequestRequestTypeDef,
+    StartExportTaskResponseTypeDef,
     StartImportTaskRequestRequestTypeDef,
     StopContinuousExportRequestRequestTypeDef,
+    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    AgentInfoTypeDef,
-    BatchDeleteImportDataResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeConfigurationsResponseTypeDef,
-    ExportConfigurationsResponseTypeDef,
-    ListConfigurationsResponseTypeDef,
-    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsResponseTypeDef,
-    StartExportTaskResponseTypeDef,
-    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsResponseTypeDef,
+    AgentInfoTypeDef,
+    BatchDeleteImportDataResponseTypeDef,
     DescribeTagsResponseTypeDef,
     DescribeContinuousExportsResponseTypeDef,
     CreateTagsRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     GetDiscoverySummaryResponseTypeDef,
-    DescribeAgentsRequestRequestTypeDef,
     DescribeAgentsRequestDescribeAgentsPaginateTypeDef,
-    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
-    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
+    DescribeAgentsRequestRequestTypeDef,
     DescribeExportConfigurationsResponseTypeDef,
     DescribeExportTasksResponseTypeDef,
     DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksRequestRequestTypeDef,
-    StartExportTaskRequestRequestTypeDef,
     DescribeImportTasksRequestRequestTypeDef,
     DescribeImportTasksResponseTypeDef,
     StartImportTaskResponseTypeDef,
     DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
+    Ec2RecommendationsExportPreferencesTypeDef,
     ListConfigurationsRequestListConfigurationsPaginateTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListServerNeighborsResponseTypeDef,
     DescribeAgentsResponseTypeDef,
+    ExportPreferencesTypeDef,
+    StartExportTaskRequestRequestTypeDef,
 )
 
 
 def get_structure() -> AgentConfigurationStatusTypeDef:
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/README.md` & `types-aiobotocore-discovery-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-discovery"></a>
 
 # types-aiobotocore-discovery
 
 [![PyPI - types-aiobotocore-discovery](https://img.shields.io/pypi/v/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-discovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-discovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationDiscoveryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
+[aiobotocore.ApplicationDiscoveryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
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
 [types-aiobotocore-discovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,14 +294,18 @@
     DescribeExportTasksPaginatorName,
     DescribeTagsPaginatorName,
     ExportDataFormatType,
     ExportStatusType,
     ImportStatusType,
     ImportTaskFilterNameType,
     ListConfigurationsPaginatorName,
+    OfferingClassType,
+    PurchasingOptionType,
+    TenancyType,
+    TermLengthType,
     orderStringType,
     ApplicationDiscoveryServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -321,120 +325,124 @@
 ```python
 from types_aiobotocore_discovery.type_defs import (
     AgentConfigurationStatusTypeDef,
     AgentNetworkInfoTypeDef,
     AssociateConfigurationItemsToApplicationRequestRequestTypeDef,
     BatchDeleteImportDataErrorTypeDef,
     BatchDeleteImportDataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ConfigurationTagTypeDef,
     ContinuousExportDescriptionTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     TagTypeDef,
     CustomerAgentInfoTypeDef,
     CustomerAgentlessCollectorInfoTypeDef,
     CustomerConnectorInfoTypeDef,
     CustomerMeCollectorInfoTypeDef,
     DeleteApplicationsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeConfigurationsRequestRequestTypeDef,
+    DescribeConfigurationsResponseTypeDef,
+    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
     DescribeContinuousExportsRequestRequestTypeDef,
+    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
     DescribeExportConfigurationsRequestRequestTypeDef,
     ExportInfoTypeDef,
     ExportFilterTypeDef,
     ImportTaskFilterTypeDef,
     ImportTaskTypeDef,
     TagFilterTypeDef,
     DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef,
+    ReservedInstanceOptionsTypeDef,
+    UsageMetricBasisTypeDef,
+    ExportConfigurationsResponseTypeDef,
     OrderByElementTypeDef,
+    ListConfigurationsResponseTypeDef,
     ListServerNeighborsRequestRequestTypeDef,
     NeighborConnectionDetailTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsRequestRequestTypeDef,
+    StartExportTaskResponseTypeDef,
     StartImportTaskRequestRequestTypeDef,
     StopContinuousExportRequestRequestTypeDef,
+    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    AgentInfoTypeDef,
-    BatchDeleteImportDataResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeConfigurationsResponseTypeDef,
-    ExportConfigurationsResponseTypeDef,
-    ListConfigurationsResponseTypeDef,
-    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsResponseTypeDef,
-    StartExportTaskResponseTypeDef,
-    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsResponseTypeDef,
+    AgentInfoTypeDef,
+    BatchDeleteImportDataResponseTypeDef,
     DescribeTagsResponseTypeDef,
     DescribeContinuousExportsResponseTypeDef,
     CreateTagsRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     GetDiscoverySummaryResponseTypeDef,
-    DescribeAgentsRequestRequestTypeDef,
     DescribeAgentsRequestDescribeAgentsPaginateTypeDef,
-    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
-    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
+    DescribeAgentsRequestRequestTypeDef,
     DescribeExportConfigurationsResponseTypeDef,
     DescribeExportTasksResponseTypeDef,
     DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksRequestRequestTypeDef,
-    StartExportTaskRequestRequestTypeDef,
     DescribeImportTasksRequestRequestTypeDef,
     DescribeImportTasksResponseTypeDef,
     StartImportTaskResponseTypeDef,
     DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
+    Ec2RecommendationsExportPreferencesTypeDef,
     ListConfigurationsRequestListConfigurationsPaginateTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListServerNeighborsResponseTypeDef,
     DescribeAgentsResponseTypeDef,
+    ExportPreferencesTypeDef,
+    StartExportTaskRequestRequestTypeDef,
 )
 
 
 def get_structure() -> AgentConfigurationStatusTypeDef:
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/setup.py` & `types-aiobotocore-discovery-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-discovery.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-discovery",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_discovery"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/"
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__init__.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__init__.pyi` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/__main__.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService\nOther"
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/client.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 import sys
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ConfigurationItemTypeType, ExportDataFormatType
+from .literals import ConfigurationItemTypeType
 from .paginator import (
     DescribeAgentsPaginator,
     DescribeContinuousExportsPaginator,
     DescribeExportConfigurationsPaginator,
     DescribeExportTasksPaginator,
     DescribeTagsPaginator,
     ListConfigurationsPaginator,
@@ -38,14 +38,15 @@
     DescribeContinuousExportsResponseTypeDef,
     DescribeExportConfigurationsResponseTypeDef,
     DescribeExportTasksResponseTypeDef,
     DescribeImportTasksResponseTypeDef,
     DescribeTagsResponseTypeDef,
     ExportConfigurationsResponseTypeDef,
     ExportFilterTypeDef,
+    ExportPreferencesTypeDef,
     FilterTypeDef,
     GetDiscoverySummaryResponseTypeDef,
     ImportTaskFilterTypeDef,
     ListConfigurationsResponseTypeDef,
     ListServerNeighborsResponseTypeDef,
     OrderByElementTypeDef,
     StartContinuousExportResponseTypeDef,
@@ -184,15 +185,15 @@
         *,
         agentIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeAgentsResponseTypeDef:
         """
-        Lists agents or connectors as specified by ID or other filters.
+        Lists agents or collectors as specified by ID or other filters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_agents)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#describe_agents)
         """
 
     async def describe_configurations(
         self, *, configurationIds: Sequence[str]
@@ -259,15 +260,15 @@
         *,
         filters: Sequence[TagFilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeTagsResponseTypeDef:
         """
         Retrieves a list of configuration items that have tags as specified by the key-
-        value pairs, name and value, passed to the optional parameter `filters` .
+        value pairs, name and value, passed to the optional parameter `filters`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#describe_tags)
         """
 
     async def disassociate_configuration_items_from_application(
         self, *, applicationConfigurationId: str, configurationIds: Sequence[str]
@@ -351,43 +352,45 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_continuous_export)
         """
 
     async def start_data_collection_by_agent_ids(
         self, *, agentIds: Sequence[str]
     ) -> StartDataCollectionByAgentIdsResponseTypeDef:
         """
-        Instructs the specified agents or connectors to start collecting data.
+        Instructs the specified agents to start collecting data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_data_collection_by_agent_ids)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_data_collection_by_agent_ids)
         """
 
     async def start_export_task(
         self,
         *,
-        exportDataFormat: Sequence[ExportDataFormatType] = ...,
+        exportDataFormat: Sequence[Literal["CSV"]] = ...,
         filters: Sequence[ExportFilterTypeDef] = ...,
         startTime: Union[datetime, str] = ...,
-        endTime: Union[datetime, str] = ...
+        endTime: Union[datetime, str] = ...,
+        preferences: ExportPreferencesTypeDef = ...
     ) -> StartExportTaskResponseTypeDef:
         """
-        Begins the export of discovered data to an S3 bucket.
+        Begins the export of a discovered data report to an Amazon S3 bucket managed by
+        Amazon Web Services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_export_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_export_task)
         """
 
     async def start_import_task(
         self, *, name: str, importUrl: str, clientRequestToken: str = ...
     ) -> StartImportTaskResponseTypeDef:
         """
         Starts an import task, which allows you to import details of your on-premises
         environment directly into Amazon Web Services Migration Hub without having to
-        use the Application Discovery Service (ADS) tools such as the Discovery
-        Connector or Discovery Agent.
+        use the Amazon Web Services Application Discovery Service (Application Discovery
+        Service) tools such as the Amazon Web Services Application D...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_import_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_import_task)
         """
 
     async def stop_continuous_export(self, *, exportId: str) -> StopContinuousExportResponseTypeDef:
         """
@@ -397,15 +400,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#stop_continuous_export)
         """
 
     async def stop_data_collection_by_agent_ids(
         self, *, agentIds: Sequence[str]
     ) -> StopDataCollectionByAgentIdsResponseTypeDef:
         """
-        Instructs the specified agents or connectors to stop collecting data.
+        Instructs the specified agents to stop collecting data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.stop_data_collection_by_agent_ids)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#stop_data_collection_by_agent_ids)
         """
 
     async def update_application(
         self, *, configurationId: str, name: str = ..., description: str = ...
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/client.pyi` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 import sys
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ConfigurationItemTypeType, ExportDataFormatType
+from .literals import ConfigurationItemTypeType
 from .paginator import (
     DescribeAgentsPaginator,
     DescribeContinuousExportsPaginator,
     DescribeExportConfigurationsPaginator,
     DescribeExportTasksPaginator,
     DescribeTagsPaginator,
     ListConfigurationsPaginator,
@@ -38,14 +38,15 @@
     DescribeContinuousExportsResponseTypeDef,
     DescribeExportConfigurationsResponseTypeDef,
     DescribeExportTasksResponseTypeDef,
     DescribeImportTasksResponseTypeDef,
     DescribeTagsResponseTypeDef,
     ExportConfigurationsResponseTypeDef,
     ExportFilterTypeDef,
+    ExportPreferencesTypeDef,
     FilterTypeDef,
     GetDiscoverySummaryResponseTypeDef,
     ImportTaskFilterTypeDef,
     ListConfigurationsResponseTypeDef,
     ListServerNeighborsResponseTypeDef,
     OrderByElementTypeDef,
     StartContinuousExportResponseTypeDef,
@@ -171,15 +172,15 @@
         *,
         agentIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeAgentsResponseTypeDef:
         """
-        Lists agents or connectors as specified by ID or other filters.
+        Lists agents or collectors as specified by ID or other filters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_agents)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#describe_agents)
         """
     async def describe_configurations(
         self, *, configurationIds: Sequence[str]
     ) -> DescribeConfigurationsResponseTypeDef:
@@ -240,15 +241,15 @@
         *,
         filters: Sequence[TagFilterTypeDef] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeTagsResponseTypeDef:
         """
         Retrieves a list of configuration items that have tags as specified by the key-
-        value pairs, name and value, passed to the optional parameter `filters` .
+        value pairs, name and value, passed to the optional parameter `filters`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.describe_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#describe_tags)
         """
     async def disassociate_configuration_items_from_application(
         self, *, applicationConfigurationId: str, configurationIds: Sequence[str]
     ) -> Dict[str, Any]:
@@ -324,41 +325,43 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_continuous_export)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_continuous_export)
         """
     async def start_data_collection_by_agent_ids(
         self, *, agentIds: Sequence[str]
     ) -> StartDataCollectionByAgentIdsResponseTypeDef:
         """
-        Instructs the specified agents or connectors to start collecting data.
+        Instructs the specified agents to start collecting data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_data_collection_by_agent_ids)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_data_collection_by_agent_ids)
         """
     async def start_export_task(
         self,
         *,
-        exportDataFormat: Sequence[ExportDataFormatType] = ...,
+        exportDataFormat: Sequence[Literal["CSV"]] = ...,
         filters: Sequence[ExportFilterTypeDef] = ...,
         startTime: Union[datetime, str] = ...,
-        endTime: Union[datetime, str] = ...
+        endTime: Union[datetime, str] = ...,
+        preferences: ExportPreferencesTypeDef = ...
     ) -> StartExportTaskResponseTypeDef:
         """
-        Begins the export of discovered data to an S3 bucket.
+        Begins the export of a discovered data report to an Amazon S3 bucket managed by
+        Amazon Web Services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_export_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_export_task)
         """
     async def start_import_task(
         self, *, name: str, importUrl: str, clientRequestToken: str = ...
     ) -> StartImportTaskResponseTypeDef:
         """
         Starts an import task, which allows you to import details of your on-premises
         environment directly into Amazon Web Services Migration Hub without having to
-        use the Application Discovery Service (ADS) tools such as the Discovery
-        Connector or Discovery Agent.
+        use the Amazon Web Services Application Discovery Service (Application Discovery
+        Service) tools such as the Amazon Web Services Application D...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.start_import_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#start_import_task)
         """
     async def stop_continuous_export(self, *, exportId: str) -> StopContinuousExportResponseTypeDef:
         """
         Stop the continuous flow of agent's discovered data into Amazon Athena.
@@ -366,15 +369,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.stop_continuous_export)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#stop_continuous_export)
         """
     async def stop_data_collection_by_agent_ids(
         self, *, agentIds: Sequence[str]
     ) -> StopDataCollectionByAgentIdsResponseTypeDef:
         """
-        Instructs the specified agents or connectors to stop collecting data.
+        Instructs the specified agents to stop collecting data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Client.stop_data_collection_by_agent_ids)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/client/#stop_data_collection_by_agent_ids)
         """
     async def update_application(
         self, *, configurationId: str, name: str = ..., description: str = ...
     ) -> Dict[str, Any]:
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/literals.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/literals.py`

 * *Files 7% similar despite different names*

```diff
@@ -31,14 +31,18 @@
     "DescribeExportTasksPaginatorName",
     "DescribeTagsPaginatorName",
     "ExportDataFormatType",
     "ExportStatusType",
     "ImportStatusType",
     "ImportTaskFilterNameType",
     "ListConfigurationsPaginatorName",
+    "OfferingClassType",
+    "PurchasingOptionType",
+    "TenancyType",
+    "TermLengthType",
     "orderStringType",
     "ApplicationDiscoveryServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -58,15 +62,15 @@
 ]
 DataSourceType = Literal["AGENT"]
 DescribeAgentsPaginatorName = Literal["describe_agents"]
 DescribeContinuousExportsPaginatorName = Literal["describe_continuous_exports"]
 DescribeExportConfigurationsPaginatorName = Literal["describe_export_configurations"]
 DescribeExportTasksPaginatorName = Literal["describe_export_tasks"]
 DescribeTagsPaginatorName = Literal["describe_tags"]
-ExportDataFormatType = Literal["CSV", "GRAPHML"]
+ExportDataFormatType = Literal["CSV"]
 ExportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 ImportStatusType = Literal[
     "DELETE_COMPLETE",
     "DELETE_FAILED",
     "DELETE_FAILED_LIMIT_EXCEEDED",
     "DELETE_IN_PROGRESS",
     "IMPORT_COMPLETE",
@@ -75,14 +79,18 @@
     "IMPORT_FAILED_RECORD_LIMIT_EXCEEDED",
     "IMPORT_FAILED_SERVER_LIMIT_EXCEEDED",
     "IMPORT_IN_PROGRESS",
     "INTERNAL_ERROR",
 ]
 ImportTaskFilterNameType = Literal["IMPORT_TASK_ID", "NAME", "STATUS"]
 ListConfigurationsPaginatorName = Literal["list_configurations"]
+OfferingClassType = Literal["CONVERTIBLE", "STANDARD"]
+PurchasingOptionType = Literal["ALL_UPFRONT", "NO_UPFRONT", "PARTIAL_UPFRONT"]
+TenancyType = Literal["DEDICATED", "SHARED"]
+TermLengthType = Literal["ONE_YEAR", "THREE_YEAR"]
 orderStringType = Literal["ASC", "DESC"]
 ApplicationDiscoveryServiceServiceName = Literal["discovery"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -139,14 +147,15 @@
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
@@ -225,14 +234,15 @@
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
@@ -243,14 +253,15 @@
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
@@ -286,14 +297,15 @@
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
@@ -312,16 +324,19 @@
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
@@ -405,15 +420,17 @@
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/literals.pyi` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -30,14 +30,18 @@
     "DescribeExportTasksPaginatorName",
     "DescribeTagsPaginatorName",
     "ExportDataFormatType",
     "ExportStatusType",
     "ImportStatusType",
     "ImportTaskFilterNameType",
     "ListConfigurationsPaginatorName",
+    "OfferingClassType",
+    "PurchasingOptionType",
+    "TenancyType",
+    "TermLengthType",
     "orderStringType",
     "ApplicationDiscoveryServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -56,15 +60,15 @@
 ]
 DataSourceType = Literal["AGENT"]
 DescribeAgentsPaginatorName = Literal["describe_agents"]
 DescribeContinuousExportsPaginatorName = Literal["describe_continuous_exports"]
 DescribeExportConfigurationsPaginatorName = Literal["describe_export_configurations"]
 DescribeExportTasksPaginatorName = Literal["describe_export_tasks"]
 DescribeTagsPaginatorName = Literal["describe_tags"]
-ExportDataFormatType = Literal["CSV", "GRAPHML"]
+ExportDataFormatType = Literal["CSV"]
 ExportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 ImportStatusType = Literal[
     "DELETE_COMPLETE",
     "DELETE_FAILED",
     "DELETE_FAILED_LIMIT_EXCEEDED",
     "DELETE_IN_PROGRESS",
     "IMPORT_COMPLETE",
@@ -73,14 +77,18 @@
     "IMPORT_FAILED_RECORD_LIMIT_EXCEEDED",
     "IMPORT_FAILED_SERVER_LIMIT_EXCEEDED",
     "IMPORT_IN_PROGRESS",
     "INTERNAL_ERROR",
 ]
 ImportTaskFilterNameType = Literal["IMPORT_TASK_ID", "NAME", "STATUS"]
 ListConfigurationsPaginatorName = Literal["list_configurations"]
+OfferingClassType = Literal["CONVERTIBLE", "STANDARD"]
+PurchasingOptionType = Literal["ALL_UPFRONT", "NO_UPFRONT", "PARTIAL_UPFRONT"]
+TenancyType = Literal["DEDICATED", "SHARED"]
+TermLengthType = Literal["ONE_YEAR", "THREE_YEAR"]
 orderStringType = Literal["ASC", "DESC"]
 ApplicationDiscoveryServiceServiceName = Literal["discovery"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -137,14 +145,15 @@
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
@@ -223,14 +232,15 @@
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
@@ -241,14 +251,15 @@
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
@@ -284,14 +295,15 @@
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
@@ -310,16 +322,19 @@
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
@@ -403,15 +418,17 @@
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/paginator.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         describe_continuous_exports_paginator: DescribeContinuousExportsPaginator = client.get_paginator("describe_continuous_exports")
         describe_export_configurations_paginator: DescribeExportConfigurationsPaginator = client.get_paginator("describe_export_configurations")
         describe_export_tasks_paginator: DescribeExportTasksPaginator = client.get_paginator("describe_export_tasks")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
         list_configurations_paginator: ListConfigurationsPaginator = client.get_paginator("list_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ConfigurationItemTypeType
 from .type_defs import (
     DescribeAgentsResponseTypeDef,
@@ -47,20 +46,14 @@
     FilterTypeDef,
     ListConfigurationsResponseTypeDef,
     OrderByElementTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAgentsPaginator",
     "DescribeContinuousExportsPaginator",
     "DescribeExportConfigurationsPaginator",
     "DescribeExportTasksPaginator",
     "DescribeTagsPaginator",
     "ListConfigurationsPaginator",
@@ -84,45 +77,45 @@
     """
 
     def paginate(
         self,
         *,
         agentIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeagentspaginator)
         """
 
 
 class DescribeContinuousExportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeContinuousExports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describecontinuousexportspaginator)
     """
 
     def paginate(
-        self, *, exportIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, exportIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeContinuousExportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeContinuousExports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describecontinuousexportspaginator)
         """
 
 
 class DescribeExportConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexportconfigurationspaginator)
     """
 
     def paginate(
-        self, *, exportIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, exportIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeExportConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexportconfigurationspaginator)
         """
 
 
@@ -133,15 +126,15 @@
     """
 
     def paginate(
         self,
         *,
         exportIds: Sequence[str] = ...,
         filters: Sequence[ExportFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeExportTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexporttaskspaginator)
         """
 
 
@@ -151,15 +144,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describetagspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[TagFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describetagspaginator)
         """
 
 
@@ -171,13 +164,13 @@
 
     def paginate(
         self,
         *,
         configurationType: ConfigurationItemTypeType,
         filters: Sequence[FilterTypeDef] = ...,
         orderBy: Sequence[OrderByElementTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.ListConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#listconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/paginator.pyi` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         describe_continuous_exports_paginator: DescribeContinuousExportsPaginator = client.get_paginator("describe_continuous_exports")
         describe_export_configurations_paginator: DescribeExportConfigurationsPaginator = client.get_paginator("describe_export_configurations")
         describe_export_tasks_paginator: DescribeExportTasksPaginator = client.get_paginator("describe_export_tasks")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
         list_configurations_paginator: ListConfigurationsPaginator = client.get_paginator("list_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ConfigurationItemTypeType
 from .type_defs import (
     DescribeAgentsResponseTypeDef,
@@ -47,19 +46,14 @@
     FilterTypeDef,
     ListConfigurationsResponseTypeDef,
     OrderByElementTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAgentsPaginator",
     "DescribeContinuousExportsPaginator",
     "DescribeExportConfigurationsPaginator",
     "DescribeExportTasksPaginator",
     "DescribeTagsPaginator",
     "ListConfigurationsPaginator",
@@ -80,43 +74,43 @@
     """
 
     def paginate(
         self,
         *,
         agentIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeagentspaginator)
         """
 
 class DescribeContinuousExportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeContinuousExports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describecontinuousexportspaginator)
     """
 
     def paginate(
-        self, *, exportIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, exportIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeContinuousExportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeContinuousExports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describecontinuousexportspaginator)
         """
 
 class DescribeExportConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexportconfigurationspaginator)
     """
 
     def paginate(
-        self, *, exportIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, exportIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeExportConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexportconfigurationspaginator)
         """
 
 class DescribeExportTasksPaginator(AioPaginator):
@@ -126,15 +120,15 @@
     """
 
     def paginate(
         self,
         *,
         exportIds: Sequence[str] = ...,
         filters: Sequence[ExportFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeExportTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeExportTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describeexporttaskspaginator)
         """
 
 class DescribeTagsPaginator(AioPaginator):
@@ -143,15 +137,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describetagspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[TagFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#describetagspaginator)
         """
 
 class ListConfigurationsPaginator(AioPaginator):
@@ -162,13 +156,13 @@
 
     def paginate(
         self,
         *,
         configurationType: ConfigurationItemTypeType,
         filters: Sequence[FilterTypeDef] = ...,
         orderBy: Sequence[OrderByElementTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService.Paginator.ListConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/paginators/#listconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/type_defs.py` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -16,100 +16,106 @@
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AgentStatusType,
     BatchDeleteImportDataErrorCodeType,
     ConfigurationItemTypeType,
     ContinuousExportStatusType,
-    ExportDataFormatType,
     ExportStatusType,
     ImportStatusType,
     ImportTaskFilterNameType,
+    OfferingClassType,
+    PurchasingOptionType,
+    TenancyType,
+    TermLengthType,
     orderStringType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AgentConfigurationStatusTypeDef",
     "AgentNetworkInfoTypeDef",
     "AssociateConfigurationItemsToApplicationRequestRequestTypeDef",
     "BatchDeleteImportDataErrorTypeDef",
     "BatchDeleteImportDataRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ConfigurationTagTypeDef",
     "ContinuousExportDescriptionTypeDef",
     "CreateApplicationRequestRequestTypeDef",
+    "CreateApplicationResponseTypeDef",
     "TagTypeDef",
     "CustomerAgentInfoTypeDef",
     "CustomerAgentlessCollectorInfoTypeDef",
     "CustomerConnectorInfoTypeDef",
     "CustomerMeCollectorInfoTypeDef",
     "DeleteApplicationsRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeConfigurationsRequestRequestTypeDef",
+    "DescribeConfigurationsResponseTypeDef",
+    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
     "DescribeContinuousExportsRequestRequestTypeDef",
+    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
     "DescribeExportConfigurationsRequestRequestTypeDef",
     "ExportInfoTypeDef",
     "ExportFilterTypeDef",
     "ImportTaskFilterTypeDef",
     "ImportTaskTypeDef",
     "TagFilterTypeDef",
     "DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef",
+    "ReservedInstanceOptionsTypeDef",
+    "UsageMetricBasisTypeDef",
+    "ExportConfigurationsResponseTypeDef",
     "OrderByElementTypeDef",
+    "ListConfigurationsResponseTypeDef",
     "ListServerNeighborsRequestRequestTypeDef",
     "NeighborConnectionDetailTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartContinuousExportResponseTypeDef",
     "StartDataCollectionByAgentIdsRequestRequestTypeDef",
+    "StartExportTaskResponseTypeDef",
     "StartImportTaskRequestRequestTypeDef",
     "StopContinuousExportRequestRequestTypeDef",
+    "StopContinuousExportResponseTypeDef",
     "StopDataCollectionByAgentIdsRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "AgentInfoTypeDef",
-    "BatchDeleteImportDataResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "DescribeConfigurationsResponseTypeDef",
-    "ExportConfigurationsResponseTypeDef",
-    "ListConfigurationsResponseTypeDef",
-    "StartContinuousExportResponseTypeDef",
     "StartDataCollectionByAgentIdsResponseTypeDef",
-    "StartExportTaskResponseTypeDef",
-    "StopContinuousExportResponseTypeDef",
     "StopDataCollectionByAgentIdsResponseTypeDef",
+    "AgentInfoTypeDef",
+    "BatchDeleteImportDataResponseTypeDef",
     "DescribeTagsResponseTypeDef",
     "DescribeContinuousExportsResponseTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "GetDiscoverySummaryResponseTypeDef",
-    "DescribeAgentsRequestRequestTypeDef",
     "DescribeAgentsRequestDescribeAgentsPaginateTypeDef",
-    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
-    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+    "DescribeAgentsRequestRequestTypeDef",
     "DescribeExportConfigurationsResponseTypeDef",
     "DescribeExportTasksResponseTypeDef",
     "DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef",
     "DescribeExportTasksRequestRequestTypeDef",
-    "StartExportTaskRequestRequestTypeDef",
     "DescribeImportTasksRequestRequestTypeDef",
     "DescribeImportTasksResponseTypeDef",
     "StartImportTaskResponseTypeDef",
     "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeTagsRequestRequestTypeDef",
+    "Ec2RecommendationsExportPreferencesTypeDef",
     "ListConfigurationsRequestListConfigurationsPaginateTypeDef",
     "ListConfigurationsRequestRequestTypeDef",
     "ListServerNeighborsResponseTypeDef",
     "DescribeAgentsResponseTypeDef",
+    "ExportPreferencesTypeDef",
+    "StartExportTaskRequestRequestTypeDef",
 )
 
 AgentConfigurationStatusTypeDef = TypedDict(
     "AgentConfigurationStatusTypeDef",
     {
         "agentId": str,
         "operationSucceeded": bool,
@@ -148,25 +154,14 @@
 BatchDeleteImportDataRequestRequestTypeDef = TypedDict(
     "BatchDeleteImportDataRequestRequestTypeDef",
     {
         "importTaskIds": Sequence[str],
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
 ConfigurationTagTypeDef = TypedDict(
     "ConfigurationTagTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
         "configurationId": str,
         "key": str,
         "value": str,
@@ -200,20 +195,26 @@
     "_OptionalCreateApplicationRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
-
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
+    {
+        "configurationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
@@ -283,41 +284,57 @@
     {
         "name": str,
         "values": Sequence[str],
         "condition": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeConfigurationsRequestRequestTypeDef = TypedDict(
+    "DescribeConfigurationsRequestRequestTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "configurationIds": Sequence[str],
     },
-    total=False,
 )
 
-DescribeConfigurationsRequestRequestTypeDef = TypedDict(
-    "DescribeConfigurationsRequestRequestTypeDef",
+DescribeConfigurationsResponseTypeDef = TypedDict(
+    "DescribeConfigurationsResponseTypeDef",
     {
-        "configurationIds": Sequence[str],
+        "configurations": List[Dict[str, str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef = TypedDict(
+    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
+    {
+        "exportIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeContinuousExportsRequestRequestTypeDef = TypedDict(
     "DescribeContinuousExportsRequestRequestTypeDef",
     {
         "exportIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+    {
+        "exportIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeExportConfigurationsRequestRequestTypeDef = TypedDict(
     "DescribeExportConfigurationsRequestRequestTypeDef",
     {
         "exportIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
@@ -340,19 +357,17 @@
         "isTruncated": bool,
         "requestedStartTime": datetime,
         "requestedEndTime": datetime,
     },
     total=False,
 )
 
-
 class ExportInfoTypeDef(_RequiredExportInfoTypeDef, _OptionalExportInfoTypeDef):
     pass
 
-
 ExportFilterTypeDef = TypedDict(
     "ExportFilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
         "condition": str,
     },
@@ -399,32 +414,65 @@
     "DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef",
     {
         "applicationConfigurationId": str,
         "configurationIds": Sequence[str],
     },
 )
 
+ReservedInstanceOptionsTypeDef = TypedDict(
+    "ReservedInstanceOptionsTypeDef",
+    {
+        "purchasingOption": PurchasingOptionType,
+        "offeringClass": OfferingClassType,
+        "termLength": TermLengthType,
+    },
+)
+
+UsageMetricBasisTypeDef = TypedDict(
+    "UsageMetricBasisTypeDef",
+    {
+        "name": str,
+        "percentageAdjust": float,
+    },
+    total=False,
+)
+
+ExportConfigurationsResponseTypeDef = TypedDict(
+    "ExportConfigurationsResponseTypeDef",
+    {
+        "exportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredOrderByElementTypeDef = TypedDict(
     "_RequiredOrderByElementTypeDef",
     {
         "fieldName": str,
     },
 )
 _OptionalOrderByElementTypeDef = TypedDict(
     "_OptionalOrderByElementTypeDef",
     {
         "sortOrder": orderStringType,
     },
     total=False,
 )
 
-
 class OrderByElementTypeDef(_RequiredOrderByElementTypeDef, _OptionalOrderByElementTypeDef):
     pass
 
+ListConfigurationsResponseTypeDef = TypedDict(
+    "ListConfigurationsResponseTypeDef",
+    {
+        "configurations": List[Dict[str, str]],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredListServerNeighborsRequestRequestTypeDef = TypedDict(
     "_RequiredListServerNeighborsRequestRequestTypeDef",
     {
         "configurationId": str,
     },
 )
@@ -435,22 +483,20 @@
         "neighborConfigurationIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListServerNeighborsRequestRequestTypeDef(
     _RequiredListServerNeighborsRequestRequestTypeDef,
     _OptionalListServerNeighborsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredNeighborConnectionDetailTypeDef = TypedDict(
     "_RequiredNeighborConnectionDetailTypeDef",
     {
         "sourceServerId": str,
         "destinationServerId": str,
         "connectionsCount": int,
     },
@@ -460,28 +506,67 @@
     {
         "destinationPort": int,
         "transportProtocol": str,
     },
     total=False,
 )
 
-
 class NeighborConnectionDetailTypeDef(
     _RequiredNeighborConnectionDetailTypeDef, _OptionalNeighborConnectionDetailTypeDef
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
+StartContinuousExportResponseTypeDef = TypedDict(
+    "StartContinuousExportResponseTypeDef",
+    {
+        "exportId": str,
+        "s3Bucket": str,
+        "startTime": datetime,
+        "dataSource": Literal["AGENT"],
+        "schemaStorageConfig": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StartDataCollectionByAgentIdsRequestRequestTypeDef = TypedDict(
     "StartDataCollectionByAgentIdsRequestRequestTypeDef",
     {
         "agentIds": Sequence[str],
     },
 )
 
+StartExportTaskResponseTypeDef = TypedDict(
+    "StartExportTaskResponseTypeDef",
+    {
+        "exportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartImportTaskRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportTaskRequestRequestTypeDef",
     {
         "name": str,
         "importUrl": str,
     },
 )
@@ -489,28 +574,35 @@
     "_OptionalStartImportTaskRequestRequestTypeDef",
     {
         "clientRequestToken": str,
     },
     total=False,
 )
 
-
 class StartImportTaskRequestRequestTypeDef(
     _RequiredStartImportTaskRequestRequestTypeDef, _OptionalStartImportTaskRequestRequestTypeDef
 ):
     pass
 
-
 StopContinuousExportRequestRequestTypeDef = TypedDict(
     "StopContinuousExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
+StopContinuousExportResponseTypeDef = TypedDict(
+    "StopContinuousExportResponseTypeDef",
+    {
+        "startTime": datetime,
+        "stopTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDataCollectionByAgentIdsRequestRequestTypeDef = TypedDict(
     "StopDataCollectionByAgentIdsRequestRequestTypeDef",
     {
         "agentIds": Sequence[str],
     },
 )
 
@@ -525,20 +617,34 @@
     {
         "name": str,
         "description": str,
     },
     total=False,
 )
 
-
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
+StartDataCollectionByAgentIdsResponseTypeDef = TypedDict(
+    "StartDataCollectionByAgentIdsResponseTypeDef",
+    {
+        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopDataCollectionByAgentIdsResponseTypeDef = TypedDict(
+    "StopDataCollectionByAgentIdsResponseTypeDef",
+    {
+        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 AgentInfoTypeDef = TypedDict(
     "AgentInfoTypeDef",
     {
         "agentId": str,
         "hostName": str,
         "agentNetworkInfoList": List[AgentNetworkInfoTypeDef],
@@ -553,111 +659,33 @@
     total=False,
 )
 
 BatchDeleteImportDataResponseTypeDef = TypedDict(
     "BatchDeleteImportDataResponseTypeDef",
     {
         "errors": List[BatchDeleteImportDataErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "configurationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationsResponseTypeDef = TypedDict(
-    "DescribeConfigurationsResponseTypeDef",
-    {
-        "configurations": List[Dict[str, str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportConfigurationsResponseTypeDef = TypedDict(
-    "ExportConfigurationsResponseTypeDef",
-    {
-        "exportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationsResponseTypeDef = TypedDict(
-    "ListConfigurationsResponseTypeDef",
-    {
-        "configurations": List[Dict[str, str]],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartContinuousExportResponseTypeDef = TypedDict(
-    "StartContinuousExportResponseTypeDef",
-    {
-        "exportId": str,
-        "s3Bucket": str,
-        "startTime": datetime,
-        "dataSource": Literal["AGENT"],
-        "schemaStorageConfig": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataCollectionByAgentIdsResponseTypeDef = TypedDict(
-    "StartDataCollectionByAgentIdsResponseTypeDef",
-    {
-        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExportTaskResponseTypeDef = TypedDict(
-    "StartExportTaskResponseTypeDef",
-    {
-        "exportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopContinuousExportResponseTypeDef = TypedDict(
-    "StopContinuousExportResponseTypeDef",
-    {
-        "startTime": datetime,
-        "stopTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDataCollectionByAgentIdsResponseTypeDef = TypedDict(
-    "StopDataCollectionByAgentIdsResponseTypeDef",
-    {
-        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "tags": List[ConfigurationTagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContinuousExportsResponseTypeDef = TypedDict(
     "DescribeContinuousExportsResponseTypeDef",
     {
         "descriptions": List[ContinuousExportDescriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTagsRequestRequestTypeDef = TypedDict(
     "CreateTagsRequestRequestTypeDef",
     {
         "configurationIds": Sequence[str],
@@ -675,99 +703,79 @@
     "_OptionalDeleteTagsRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class DeleteTagsRequestRequestTypeDef(
     _RequiredDeleteTagsRequestRequestTypeDef, _OptionalDeleteTagsRequestRequestTypeDef
 ):
     pass
 
-
 GetDiscoverySummaryResponseTypeDef = TypedDict(
     "GetDiscoverySummaryResponseTypeDef",
     {
         "servers": int,
         "applications": int,
         "serversMappedToApplications": int,
         "serversMappedtoTags": int,
         "agentSummary": CustomerAgentInfoTypeDef,
         "connectorSummary": CustomerConnectorInfoTypeDef,
         "meCollectorSummary": CustomerMeCollectorInfoTypeDef,
         "agentlessCollectorSummary": CustomerAgentlessCollectorInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAgentsRequestRequestTypeDef = TypedDict(
-    "DescribeAgentsRequestRequestTypeDef",
-    {
-        "agentIds": Sequence[str],
-        "filters": Sequence[FilterTypeDef],
-        "maxResults": int,
-        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 DescribeAgentsRequestDescribeAgentsPaginateTypeDef = TypedDict(
     "DescribeAgentsRequestDescribeAgentsPaginateTypeDef",
     {
         "agentIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef = TypedDict(
-    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
-    {
-        "exportIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+DescribeAgentsRequestRequestTypeDef = TypedDict(
+    "DescribeAgentsRequestRequestTypeDef",
     {
-        "exportIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "agentIds": Sequence[str],
+        "filters": Sequence[FilterTypeDef],
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
 DescribeExportConfigurationsResponseTypeDef = TypedDict(
     "DescribeExportConfigurationsResponseTypeDef",
     {
         "exportsInfo": List[ExportInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportTasksResponseTypeDef = TypedDict(
     "DescribeExportTasksResponseTypeDef",
     {
         "exportsInfo": List[ExportInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef = TypedDict(
     "DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef",
     {
         "exportIds": Sequence[str],
         "filters": Sequence[ExportFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeExportTasksRequestRequestTypeDef = TypedDict(
     "DescribeExportTasksRequestRequestTypeDef",
     {
@@ -775,25 +783,14 @@
         "filters": Sequence[ExportFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-StartExportTaskRequestRequestTypeDef = TypedDict(
-    "StartExportTaskRequestRequestTypeDef",
-    {
-        "exportDataFormat": Sequence[ExportDataFormatType],
-        "filters": Sequence[ExportFilterTypeDef],
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-    total=False,
-)
-
 DescribeImportTasksRequestRequestTypeDef = TypedDict(
     "DescribeImportTasksRequestRequestTypeDef",
     {
         "filters": Sequence[ImportTaskFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
@@ -801,69 +798,81 @@
 )
 
 DescribeImportTasksResponseTypeDef = TypedDict(
     "DescribeImportTasksResponseTypeDef",
     {
         "nextToken": str,
         "tasks": List[ImportTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartImportTaskResponseTypeDef = TypedDict(
     "StartImportTaskResponseTypeDef",
     {
         "task": ImportTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
     "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     {
         "filters": Sequence[TagFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeTagsRequestRequestTypeDef = TypedDict(
     "DescribeTagsRequestRequestTypeDef",
     {
         "filters": Sequence[TagFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+Ec2RecommendationsExportPreferencesTypeDef = TypedDict(
+    "Ec2RecommendationsExportPreferencesTypeDef",
+    {
+        "enabled": bool,
+        "cpuPerformanceMetricBasis": UsageMetricBasisTypeDef,
+        "ramPerformanceMetricBasis": UsageMetricBasisTypeDef,
+        "tenancy": TenancyType,
+        "excludedInstanceTypes": Sequence[str],
+        "preferredRegion": str,
+        "reservedInstanceOptions": ReservedInstanceOptionsTypeDef,
+    },
+    total=False,
+)
+
 _RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef = TypedDict(
     "_RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
     },
 )
 _OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef = TypedDict(
     "_OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
         "orderBy": Sequence[OrderByElementTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListConfigurationsRequestListConfigurationsPaginateTypeDef(
     _RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef,
     _OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListConfigurationsRequestRequestTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
     },
 )
 _OptionalListConfigurationsRequestRequestTypeDef = TypedDict(
@@ -873,33 +882,51 @@
         "maxResults": int,
         "nextToken": str,
         "orderBy": Sequence[OrderByElementTypeDef],
     },
     total=False,
 )
 
-
 class ListConfigurationsRequestRequestTypeDef(
     _RequiredListConfigurationsRequestRequestTypeDef,
     _OptionalListConfigurationsRequestRequestTypeDef,
 ):
     pass
 
-
 ListServerNeighborsResponseTypeDef = TypedDict(
     "ListServerNeighborsResponseTypeDef",
     {
         "neighbors": List[NeighborConnectionDetailTypeDef],
         "nextToken": str,
         "knownDependencyCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAgentsResponseTypeDef = TypedDict(
     "DescribeAgentsResponseTypeDef",
     {
         "agentsInfo": List[AgentInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportPreferencesTypeDef = TypedDict(
+    "ExportPreferencesTypeDef",
+    {
+        "ec2RecommendationsPreferences": Ec2RecommendationsExportPreferencesTypeDef,
     },
+    total=False,
+)
+
+StartExportTaskRequestRequestTypeDef = TypedDict(
+    "StartExportTaskRequestRequestTypeDef",
+    {
+        "exportDataFormat": Sequence[Literal["CSV"]],
+        "filters": Sequence[ExportFilterTypeDef],
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "preferences": ExportPreferencesTypeDef,
+    },
+    total=False,
 )
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery/type_defs.pyi` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,99 +16,107 @@
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AgentStatusType,
     BatchDeleteImportDataErrorCodeType,
     ConfigurationItemTypeType,
     ContinuousExportStatusType,
-    ExportDataFormatType,
     ExportStatusType,
     ImportStatusType,
     ImportTaskFilterNameType,
+    OfferingClassType,
+    PurchasingOptionType,
+    TenancyType,
+    TermLengthType,
     orderStringType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AgentConfigurationStatusTypeDef",
     "AgentNetworkInfoTypeDef",
     "AssociateConfigurationItemsToApplicationRequestRequestTypeDef",
     "BatchDeleteImportDataErrorTypeDef",
     "BatchDeleteImportDataRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ConfigurationTagTypeDef",
     "ContinuousExportDescriptionTypeDef",
     "CreateApplicationRequestRequestTypeDef",
+    "CreateApplicationResponseTypeDef",
     "TagTypeDef",
     "CustomerAgentInfoTypeDef",
     "CustomerAgentlessCollectorInfoTypeDef",
     "CustomerConnectorInfoTypeDef",
     "CustomerMeCollectorInfoTypeDef",
     "DeleteApplicationsRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeConfigurationsRequestRequestTypeDef",
+    "DescribeConfigurationsResponseTypeDef",
+    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
     "DescribeContinuousExportsRequestRequestTypeDef",
+    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
     "DescribeExportConfigurationsRequestRequestTypeDef",
     "ExportInfoTypeDef",
     "ExportFilterTypeDef",
     "ImportTaskFilterTypeDef",
     "ImportTaskTypeDef",
     "TagFilterTypeDef",
     "DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef",
+    "ReservedInstanceOptionsTypeDef",
+    "UsageMetricBasisTypeDef",
+    "ExportConfigurationsResponseTypeDef",
     "OrderByElementTypeDef",
+    "ListConfigurationsResponseTypeDef",
     "ListServerNeighborsRequestRequestTypeDef",
     "NeighborConnectionDetailTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartContinuousExportResponseTypeDef",
     "StartDataCollectionByAgentIdsRequestRequestTypeDef",
+    "StartExportTaskResponseTypeDef",
     "StartImportTaskRequestRequestTypeDef",
     "StopContinuousExportRequestRequestTypeDef",
+    "StopContinuousExportResponseTypeDef",
     "StopDataCollectionByAgentIdsRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "AgentInfoTypeDef",
-    "BatchDeleteImportDataResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "DescribeConfigurationsResponseTypeDef",
-    "ExportConfigurationsResponseTypeDef",
-    "ListConfigurationsResponseTypeDef",
-    "StartContinuousExportResponseTypeDef",
     "StartDataCollectionByAgentIdsResponseTypeDef",
-    "StartExportTaskResponseTypeDef",
-    "StopContinuousExportResponseTypeDef",
     "StopDataCollectionByAgentIdsResponseTypeDef",
+    "AgentInfoTypeDef",
+    "BatchDeleteImportDataResponseTypeDef",
     "DescribeTagsResponseTypeDef",
     "DescribeContinuousExportsResponseTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "GetDiscoverySummaryResponseTypeDef",
-    "DescribeAgentsRequestRequestTypeDef",
     "DescribeAgentsRequestDescribeAgentsPaginateTypeDef",
-    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
-    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+    "DescribeAgentsRequestRequestTypeDef",
     "DescribeExportConfigurationsResponseTypeDef",
     "DescribeExportTasksResponseTypeDef",
     "DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef",
     "DescribeExportTasksRequestRequestTypeDef",
-    "StartExportTaskRequestRequestTypeDef",
     "DescribeImportTasksRequestRequestTypeDef",
     "DescribeImportTasksResponseTypeDef",
     "StartImportTaskResponseTypeDef",
     "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeTagsRequestRequestTypeDef",
+    "Ec2RecommendationsExportPreferencesTypeDef",
     "ListConfigurationsRequestListConfigurationsPaginateTypeDef",
     "ListConfigurationsRequestRequestTypeDef",
     "ListServerNeighborsResponseTypeDef",
     "DescribeAgentsResponseTypeDef",
+    "ExportPreferencesTypeDef",
+    "StartExportTaskRequestRequestTypeDef",
 )
 
 AgentConfigurationStatusTypeDef = TypedDict(
     "AgentConfigurationStatusTypeDef",
     {
         "agentId": str,
         "operationSucceeded": bool,
@@ -147,25 +155,14 @@
 BatchDeleteImportDataRequestRequestTypeDef = TypedDict(
     "BatchDeleteImportDataRequestRequestTypeDef",
     {
         "importTaskIds": Sequence[str],
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
 ConfigurationTagTypeDef = TypedDict(
     "ConfigurationTagTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
         "configurationId": str,
         "key": str,
         "value": str,
@@ -199,19 +196,29 @@
     "_OptionalCreateApplicationRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
+
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
+
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
+    {
+        "configurationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
@@ -280,41 +287,57 @@
     {
         "name": str,
         "values": Sequence[str],
         "condition": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeConfigurationsRequestRequestTypeDef = TypedDict(
+    "DescribeConfigurationsRequestRequestTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "configurationIds": Sequence[str],
     },
-    total=False,
 )
 
-DescribeConfigurationsRequestRequestTypeDef = TypedDict(
-    "DescribeConfigurationsRequestRequestTypeDef",
+DescribeConfigurationsResponseTypeDef = TypedDict(
+    "DescribeConfigurationsResponseTypeDef",
     {
-        "configurationIds": Sequence[str],
+        "configurations": List[Dict[str, str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef = TypedDict(
+    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
+    {
+        "exportIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeContinuousExportsRequestRequestTypeDef = TypedDict(
     "DescribeContinuousExportsRequestRequestTypeDef",
     {
         "exportIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+    {
+        "exportIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeExportConfigurationsRequestRequestTypeDef = TypedDict(
     "DescribeExportConfigurationsRequestRequestTypeDef",
     {
         "exportIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
@@ -337,17 +360,19 @@
         "isTruncated": bool,
         "requestedStartTime": datetime,
         "requestedEndTime": datetime,
     },
     total=False,
 )
 
+
 class ExportInfoTypeDef(_RequiredExportInfoTypeDef, _OptionalExportInfoTypeDef):
     pass
 
+
 ExportFilterTypeDef = TypedDict(
     "ExportFilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
         "condition": str,
     },
@@ -394,31 +419,68 @@
     "DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef",
     {
         "applicationConfigurationId": str,
         "configurationIds": Sequence[str],
     },
 )
 
+ReservedInstanceOptionsTypeDef = TypedDict(
+    "ReservedInstanceOptionsTypeDef",
+    {
+        "purchasingOption": PurchasingOptionType,
+        "offeringClass": OfferingClassType,
+        "termLength": TermLengthType,
+    },
+)
+
+UsageMetricBasisTypeDef = TypedDict(
+    "UsageMetricBasisTypeDef",
+    {
+        "name": str,
+        "percentageAdjust": float,
+    },
+    total=False,
+)
+
+ExportConfigurationsResponseTypeDef = TypedDict(
+    "ExportConfigurationsResponseTypeDef",
+    {
+        "exportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredOrderByElementTypeDef = TypedDict(
     "_RequiredOrderByElementTypeDef",
     {
         "fieldName": str,
     },
 )
 _OptionalOrderByElementTypeDef = TypedDict(
     "_OptionalOrderByElementTypeDef",
     {
         "sortOrder": orderStringType,
     },
     total=False,
 )
 
+
 class OrderByElementTypeDef(_RequiredOrderByElementTypeDef, _OptionalOrderByElementTypeDef):
     pass
 
+
+ListConfigurationsResponseTypeDef = TypedDict(
+    "ListConfigurationsResponseTypeDef",
+    {
+        "configurations": List[Dict[str, str]],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListServerNeighborsRequestRequestTypeDef = TypedDict(
     "_RequiredListServerNeighborsRequestRequestTypeDef",
     {
         "configurationId": str,
     },
 )
 _OptionalListServerNeighborsRequestRequestTypeDef = TypedDict(
@@ -428,20 +490,22 @@
         "neighborConfigurationIds": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListServerNeighborsRequestRequestTypeDef(
     _RequiredListServerNeighborsRequestRequestTypeDef,
     _OptionalListServerNeighborsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredNeighborConnectionDetailTypeDef = TypedDict(
     "_RequiredNeighborConnectionDetailTypeDef",
     {
         "sourceServerId": str,
         "destinationServerId": str,
         "connectionsCount": int,
     },
@@ -451,26 +515,69 @@
     {
         "destinationPort": int,
         "transportProtocol": str,
     },
     total=False,
 )
 
+
 class NeighborConnectionDetailTypeDef(
     _RequiredNeighborConnectionDetailTypeDef, _OptionalNeighborConnectionDetailTypeDef
 ):
     pass
 
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
+StartContinuousExportResponseTypeDef = TypedDict(
+    "StartContinuousExportResponseTypeDef",
+    {
+        "exportId": str,
+        "s3Bucket": str,
+        "startTime": datetime,
+        "dataSource": Literal["AGENT"],
+        "schemaStorageConfig": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartDataCollectionByAgentIdsRequestRequestTypeDef = TypedDict(
     "StartDataCollectionByAgentIdsRequestRequestTypeDef",
     {
         "agentIds": Sequence[str],
     },
 )
 
+StartExportTaskResponseTypeDef = TypedDict(
+    "StartExportTaskResponseTypeDef",
+    {
+        "exportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartImportTaskRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportTaskRequestRequestTypeDef",
     {
         "name": str,
         "importUrl": str,
     },
 )
@@ -478,26 +585,37 @@
     "_OptionalStartImportTaskRequestRequestTypeDef",
     {
         "clientRequestToken": str,
     },
     total=False,
 )
 
+
 class StartImportTaskRequestRequestTypeDef(
     _RequiredStartImportTaskRequestRequestTypeDef, _OptionalStartImportTaskRequestRequestTypeDef
 ):
     pass
 
+
 StopContinuousExportRequestRequestTypeDef = TypedDict(
     "StopContinuousExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
+StopContinuousExportResponseTypeDef = TypedDict(
+    "StopContinuousExportResponseTypeDef",
+    {
+        "startTime": datetime,
+        "stopTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDataCollectionByAgentIdsRequestRequestTypeDef = TypedDict(
     "StopDataCollectionByAgentIdsRequestRequestTypeDef",
     {
         "agentIds": Sequence[str],
     },
 )
 
@@ -512,19 +630,37 @@
     {
         "name": str,
         "description": str,
     },
     total=False,
 )
 
+
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
+
+StartDataCollectionByAgentIdsResponseTypeDef = TypedDict(
+    "StartDataCollectionByAgentIdsResponseTypeDef",
+    {
+        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopDataCollectionByAgentIdsResponseTypeDef = TypedDict(
+    "StopDataCollectionByAgentIdsResponseTypeDef",
+    {
+        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AgentInfoTypeDef = TypedDict(
     "AgentInfoTypeDef",
     {
         "agentId": str,
         "hostName": str,
         "agentNetworkInfoList": List[AgentNetworkInfoTypeDef],
         "connectorId": str,
@@ -538,111 +674,33 @@
     total=False,
 )
 
 BatchDeleteImportDataResponseTypeDef = TypedDict(
     "BatchDeleteImportDataResponseTypeDef",
     {
         "errors": List[BatchDeleteImportDataErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "configurationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationsResponseTypeDef = TypedDict(
-    "DescribeConfigurationsResponseTypeDef",
-    {
-        "configurations": List[Dict[str, str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportConfigurationsResponseTypeDef = TypedDict(
-    "ExportConfigurationsResponseTypeDef",
-    {
-        "exportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationsResponseTypeDef = TypedDict(
-    "ListConfigurationsResponseTypeDef",
-    {
-        "configurations": List[Dict[str, str]],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartContinuousExportResponseTypeDef = TypedDict(
-    "StartContinuousExportResponseTypeDef",
-    {
-        "exportId": str,
-        "s3Bucket": str,
-        "startTime": datetime,
-        "dataSource": Literal["AGENT"],
-        "schemaStorageConfig": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataCollectionByAgentIdsResponseTypeDef = TypedDict(
-    "StartDataCollectionByAgentIdsResponseTypeDef",
-    {
-        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExportTaskResponseTypeDef = TypedDict(
-    "StartExportTaskResponseTypeDef",
-    {
-        "exportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopContinuousExportResponseTypeDef = TypedDict(
-    "StopContinuousExportResponseTypeDef",
-    {
-        "startTime": datetime,
-        "stopTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDataCollectionByAgentIdsResponseTypeDef = TypedDict(
-    "StopDataCollectionByAgentIdsResponseTypeDef",
-    {
-        "agentsConfigurationStatus": List[AgentConfigurationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "tags": List[ConfigurationTagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContinuousExportsResponseTypeDef = TypedDict(
     "DescribeContinuousExportsResponseTypeDef",
     {
         "descriptions": List[ContinuousExportDescriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTagsRequestRequestTypeDef = TypedDict(
     "CreateTagsRequestRequestTypeDef",
     {
         "configurationIds": Sequence[str],
@@ -660,97 +718,81 @@
     "_OptionalDeleteTagsRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class DeleteTagsRequestRequestTypeDef(
     _RequiredDeleteTagsRequestRequestTypeDef, _OptionalDeleteTagsRequestRequestTypeDef
 ):
     pass
 
+
 GetDiscoverySummaryResponseTypeDef = TypedDict(
     "GetDiscoverySummaryResponseTypeDef",
     {
         "servers": int,
         "applications": int,
         "serversMappedToApplications": int,
         "serversMappedtoTags": int,
         "agentSummary": CustomerAgentInfoTypeDef,
         "connectorSummary": CustomerConnectorInfoTypeDef,
         "meCollectorSummary": CustomerMeCollectorInfoTypeDef,
         "agentlessCollectorSummary": CustomerAgentlessCollectorInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeAgentsRequestRequestTypeDef = TypedDict(
-    "DescribeAgentsRequestRequestTypeDef",
-    {
-        "agentIds": Sequence[str],
-        "filters": Sequence[FilterTypeDef],
-        "maxResults": int,
-        "nextToken": str,
-    },
-    total=False,
-)
-
 DescribeAgentsRequestDescribeAgentsPaginateTypeDef = TypedDict(
     "DescribeAgentsRequestDescribeAgentsPaginateTypeDef",
     {
         "agentIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef = TypedDict(
-    "DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef",
-    {
-        "exportIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef",
+DescribeAgentsRequestRequestTypeDef = TypedDict(
+    "DescribeAgentsRequestRequestTypeDef",
     {
-        "exportIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "agentIds": Sequence[str],
+        "filters": Sequence[FilterTypeDef],
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
 DescribeExportConfigurationsResponseTypeDef = TypedDict(
     "DescribeExportConfigurationsResponseTypeDef",
     {
         "exportsInfo": List[ExportInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportTasksResponseTypeDef = TypedDict(
     "DescribeExportTasksResponseTypeDef",
     {
         "exportsInfo": List[ExportInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef = TypedDict(
     "DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef",
     {
         "exportIds": Sequence[str],
         "filters": Sequence[ExportFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeExportTasksRequestRequestTypeDef = TypedDict(
     "DescribeExportTasksRequestRequestTypeDef",
     {
@@ -758,25 +800,14 @@
         "filters": Sequence[ExportFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-StartExportTaskRequestRequestTypeDef = TypedDict(
-    "StartExportTaskRequestRequestTypeDef",
-    {
-        "exportDataFormat": Sequence[ExportDataFormatType],
-        "filters": Sequence[ExportFilterTypeDef],
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-    total=False,
-)
-
 DescribeImportTasksRequestRequestTypeDef = TypedDict(
     "DescribeImportTasksRequestRequestTypeDef",
     {
         "filters": Sequence[ImportTaskFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
@@ -784,67 +815,83 @@
 )
 
 DescribeImportTasksResponseTypeDef = TypedDict(
     "DescribeImportTasksResponseTypeDef",
     {
         "nextToken": str,
         "tasks": List[ImportTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartImportTaskResponseTypeDef = TypedDict(
     "StartImportTaskResponseTypeDef",
     {
         "task": ImportTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
     "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     {
         "filters": Sequence[TagFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeTagsRequestRequestTypeDef = TypedDict(
     "DescribeTagsRequestRequestTypeDef",
     {
         "filters": Sequence[TagFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+Ec2RecommendationsExportPreferencesTypeDef = TypedDict(
+    "Ec2RecommendationsExportPreferencesTypeDef",
+    {
+        "enabled": bool,
+        "cpuPerformanceMetricBasis": UsageMetricBasisTypeDef,
+        "ramPerformanceMetricBasis": UsageMetricBasisTypeDef,
+        "tenancy": TenancyType,
+        "excludedInstanceTypes": Sequence[str],
+        "preferredRegion": str,
+        "reservedInstanceOptions": ReservedInstanceOptionsTypeDef,
+    },
+    total=False,
+)
+
 _RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef = TypedDict(
     "_RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
     },
 )
 _OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef = TypedDict(
     "_OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
         "orderBy": Sequence[OrderByElementTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListConfigurationsRequestListConfigurationsPaginateTypeDef(
     _RequiredListConfigurationsRequestListConfigurationsPaginateTypeDef,
     _OptionalListConfigurationsRequestListConfigurationsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListConfigurationsRequestRequestTypeDef",
     {
         "configurationType": ConfigurationItemTypeType,
     },
 )
 _OptionalListConfigurationsRequestRequestTypeDef = TypedDict(
@@ -854,31 +901,53 @@
         "maxResults": int,
         "nextToken": str,
         "orderBy": Sequence[OrderByElementTypeDef],
     },
     total=False,
 )
 
+
 class ListConfigurationsRequestRequestTypeDef(
     _RequiredListConfigurationsRequestRequestTypeDef,
     _OptionalListConfigurationsRequestRequestTypeDef,
 ):
     pass
 
+
 ListServerNeighborsResponseTypeDef = TypedDict(
     "ListServerNeighborsResponseTypeDef",
     {
         "neighbors": List[NeighborConnectionDetailTypeDef],
         "nextToken": str,
         "knownDependencyCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAgentsResponseTypeDef = TypedDict(
     "DescribeAgentsResponseTypeDef",
     {
         "agentsInfo": List[AgentInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportPreferencesTypeDef = TypedDict(
+    "ExportPreferencesTypeDef",
+    {
+        "ec2RecommendationsPreferences": Ec2RecommendationsExportPreferencesTypeDef,
     },
+    total=False,
+)
+
+StartExportTaskRequestRequestTypeDef = TypedDict(
+    "StartExportTaskRequestRequestTypeDef",
+    {
+        "exportDataFormat": Sequence[Literal["CSV"]],
+        "filters": Sequence[ExportFilterTypeDef],
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "preferences": ExportPreferencesTypeDef,
+    },
+    total=False,
 )
```

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/PKG-INFO` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-discovery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationDiscoveryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-discovery"></a>
 
 # types-aiobotocore-discovery
 
 [![PyPI - types-aiobotocore-discovery](https://img.shields.io/pypi/v/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-discovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-discovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-discovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-discovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationDiscoveryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
+[aiobotocore.ApplicationDiscoveryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/discovery.html#ApplicationDiscoveryService)
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
 [types-aiobotocore-discovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_discovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,14 +327,18 @@
     DescribeExportTasksPaginatorName,
     DescribeTagsPaginatorName,
     ExportDataFormatType,
     ExportStatusType,
     ImportStatusType,
     ImportTaskFilterNameType,
     ListConfigurationsPaginatorName,
+    OfferingClassType,
+    PurchasingOptionType,
+    TenancyType,
+    TermLengthType,
     orderStringType,
     ApplicationDiscoveryServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -354,120 +358,124 @@
 ```python
 from types_aiobotocore_discovery.type_defs import (
     AgentConfigurationStatusTypeDef,
     AgentNetworkInfoTypeDef,
     AssociateConfigurationItemsToApplicationRequestRequestTypeDef,
     BatchDeleteImportDataErrorTypeDef,
     BatchDeleteImportDataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ConfigurationTagTypeDef,
     ContinuousExportDescriptionTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     TagTypeDef,
     CustomerAgentInfoTypeDef,
     CustomerAgentlessCollectorInfoTypeDef,
     CustomerConnectorInfoTypeDef,
     CustomerMeCollectorInfoTypeDef,
     DeleteApplicationsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeConfigurationsRequestRequestTypeDef,
+    DescribeConfigurationsResponseTypeDef,
+    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
     DescribeContinuousExportsRequestRequestTypeDef,
+    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
     DescribeExportConfigurationsRequestRequestTypeDef,
     ExportInfoTypeDef,
     ExportFilterTypeDef,
     ImportTaskFilterTypeDef,
     ImportTaskTypeDef,
     TagFilterTypeDef,
     DisassociateConfigurationItemsFromApplicationRequestRequestTypeDef,
+    ReservedInstanceOptionsTypeDef,
+    UsageMetricBasisTypeDef,
+    ExportConfigurationsResponseTypeDef,
     OrderByElementTypeDef,
+    ListConfigurationsResponseTypeDef,
     ListServerNeighborsRequestRequestTypeDef,
     NeighborConnectionDetailTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsRequestRequestTypeDef,
+    StartExportTaskResponseTypeDef,
     StartImportTaskRequestRequestTypeDef,
     StopContinuousExportRequestRequestTypeDef,
+    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    AgentInfoTypeDef,
-    BatchDeleteImportDataResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeConfigurationsResponseTypeDef,
-    ExportConfigurationsResponseTypeDef,
-    ListConfigurationsResponseTypeDef,
-    StartContinuousExportResponseTypeDef,
     StartDataCollectionByAgentIdsResponseTypeDef,
-    StartExportTaskResponseTypeDef,
-    StopContinuousExportResponseTypeDef,
     StopDataCollectionByAgentIdsResponseTypeDef,
+    AgentInfoTypeDef,
+    BatchDeleteImportDataResponseTypeDef,
     DescribeTagsResponseTypeDef,
     DescribeContinuousExportsResponseTypeDef,
     CreateTagsRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     GetDiscoverySummaryResponseTypeDef,
-    DescribeAgentsRequestRequestTypeDef,
     DescribeAgentsRequestDescribeAgentsPaginateTypeDef,
-    DescribeContinuousExportsRequestDescribeContinuousExportsPaginateTypeDef,
-    DescribeExportConfigurationsRequestDescribeExportConfigurationsPaginateTypeDef,
+    DescribeAgentsRequestRequestTypeDef,
     DescribeExportConfigurationsResponseTypeDef,
     DescribeExportTasksResponseTypeDef,
     DescribeExportTasksRequestDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksRequestRequestTypeDef,
-    StartExportTaskRequestRequestTypeDef,
     DescribeImportTasksRequestRequestTypeDef,
     DescribeImportTasksResponseTypeDef,
     StartImportTaskResponseTypeDef,
     DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
+    Ec2RecommendationsExportPreferencesTypeDef,
     ListConfigurationsRequestListConfigurationsPaginateTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListServerNeighborsResponseTypeDef,
     DescribeAgentsResponseTypeDef,
+    ExportPreferencesTypeDef,
+    StartExportTaskRequestRequestTypeDef,
 )
 
 
 def get_structure() -> AgentConfigurationStatusTypeDef:
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

### Comparing `types-aiobotocore-discovery-2.5.0.post1/types_aiobotocore_discovery.egg-info/SOURCES.txt` & `types-aiobotocore-discovery-2.5.1/types_aiobotocore_discovery.egg-info/SOURCES.txt`

 * *Files identical despite different names*

