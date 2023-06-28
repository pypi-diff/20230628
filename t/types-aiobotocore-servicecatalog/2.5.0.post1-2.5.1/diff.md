# Comparing `tmp/types-aiobotocore-servicecatalog-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-servicecatalog-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-servicecatalog-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-servicecatalog-2.5.1.tar", last modified: Wed Jun 28 01:44:10 2023, max compression
```

## Comparing `types-aiobotocore-servicecatalog-2.5.0.post1.tar` & `types-aiobotocore-servicecatalog-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.595630 types-aiobotocore-servicecatalog-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    27825 2023-03-11 12:27:20.595630 types-aiobotocore-servicecatalog-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    26226 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.595630 types-aiobotocore-servicecatalog-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.595630 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/
--rw-r--r--   0 runner    (1001) docker     (123)     4639 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4638 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    77087 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    76975 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14300 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14298 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    22794 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    22775 2023-03-11 12:24:01.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    99254 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    99115 2023-03-11 12:24:02.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:57.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.595630 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    27825 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.658214 types-aiobotocore-servicecatalog-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28159 2023-06-28 01:44:10.658214 types-aiobotocore-servicecatalog-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    26566 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:10.658214 types-aiobotocore-servicecatalog-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.658214 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/
+-rw-r--r--   0 runner    (1001) docker     (123)     4639 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4638 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    79727 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    79612 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14789 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14787 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    22719 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22700 2023-06-28 01:40:47.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   102873 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   102728 2023-06-28 01:40:48.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:46.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.658214 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28159 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/LICENSE` & `types-aiobotocore-servicecatalog-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/PKG-INFO` & `types-aiobotocore-servicecatalog-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicecatalog
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceCatalog 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceCatalog 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicecatalog"></a>
 
 # types-aiobotocore-servicecatalog
 
 [![PyPI - types-aiobotocore-servicecatalog](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
+[aiobotocore.ServiceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
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
 [types-aiobotocore-servicecatalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,14 +358,15 @@
 from types_aiobotocore_servicecatalog.literals import (
     AccessLevelFilterKeyType,
     AccessStatusType,
     ChangeActionType,
     CopyOptionType,
     CopyProductStatusType,
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     EvaluationTypeType,
     LastSyncStatusType,
     ListAcceptedPortfolioSharesPaginatorName,
     ListConstraintsForPortfolioPaginatorName,
     ListLaunchPathsPaginatorName,
     ListOrganizationPortfolioAccessPaginatorName,
     ListPortfoliosForProductPaginatorName,
@@ -434,40 +435,44 @@
     AssociateBudgetWithResourceInputRequestTypeDef,
     AssociatePrincipalWithPortfolioInputRequestTypeDef,
     AssociateProductWithPortfolioInputRequestTypeDef,
     AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     AssociateTagOptionWithResourceInputRequestTypeDef,
     ServiceActionAssociationTypeDef,
     FailedServiceActionAssociationTypeDef,
-    ResponseMetadataTypeDef,
     BudgetDetailTypeDef,
     CloudWatchDashboardTypeDef,
     CodeStarParametersTypeDef,
     ConstraintDetailTypeDef,
     ConstraintSummaryTypeDef,
     CopyProductInputRequestTypeDef,
+    CopyProductOutputTypeDef,
     CreateConstraintInputRequestTypeDef,
     TagTypeDef,
     PortfolioDetailTypeDef,
     OrganizationNodeTypeDef,
+    CreatePortfolioShareOutputTypeDef,
     ProvisioningArtifactPropertiesTypeDef,
     ProvisioningArtifactDetailTypeDef,
     UpdateProvisioningParameterTypeDef,
+    CreateProvisionedProductPlanOutputTypeDef,
     CreateServiceActionInputRequestTypeDef,
     CreateTagOptionInputRequestTypeDef,
     TagOptionDetailTypeDef,
     DeleteConstraintInputRequestTypeDef,
     DeletePortfolioInputRequestTypeDef,
+    DeletePortfolioShareOutputTypeDef,
     DeleteProductInputRequestTypeDef,
     DeleteProvisionedProductPlanInputRequestTypeDef,
     DeleteProvisioningArtifactInputRequestTypeDef,
     DeleteServiceActionInputRequestTypeDef,
     DeleteTagOptionInputRequestTypeDef,
     DescribeConstraintInputRequestTypeDef,
     DescribeCopyProductStatusInputRequestTypeDef,
+    DescribeCopyProductStatusOutputTypeDef,
     DescribePortfolioInputRequestTypeDef,
     DescribePortfolioShareStatusInputRequestTypeDef,
     DescribePortfolioSharesInputRequestTypeDef,
     PortfolioShareDetailTypeDef,
     DescribeProductAsAdminInputRequestTypeDef,
     ProvisioningArtifactSummaryTypeDef,
     DescribeProductInputRequestTypeDef,
@@ -491,76 +496,88 @@
     DescribeServiceActionInputRequestTypeDef,
     DescribeTagOptionInputRequestTypeDef,
     DisassociateBudgetFromResourceInputRequestTypeDef,
     DisassociatePrincipalFromPortfolioInputRequestTypeDef,
     DisassociateProductFromPortfolioInputRequestTypeDef,
     DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     DisassociateTagOptionFromResourceInputRequestTypeDef,
+    UniqueTagResourceIdentifierTypeDef,
     ExecuteProvisionedProductPlanInputRequestTypeDef,
     ExecuteProvisionedProductServiceActionInputRequestTypeDef,
+    GetAWSOrganizationsAccessStatusOutputTypeDef,
     GetProvisionedProductOutputsInputRequestTypeDef,
     ImportAsProvisionedProductInputRequestTypeDef,
     LastSyncTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
     ListAcceptedPortfolioSharesInputRequestTypeDef,
     ListBudgetsForResourceInputRequestTypeDef,
+    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
     ListConstraintsForPortfolioInputRequestTypeDef,
+    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
     ListLaunchPathsInputRequestTypeDef,
+    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
     ListOrganizationPortfolioAccessInputRequestTypeDef,
     ListPortfolioAccessInputRequestTypeDef,
+    ListPortfolioAccessOutputTypeDef,
+    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
     ListPortfoliosForProductInputRequestTypeDef,
+    ListPortfoliosInputListPortfoliosPaginateTypeDef,
     ListPortfoliosInputRequestTypeDef,
+    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
     ListPrincipalsForPortfolioInputRequestTypeDef,
     PrincipalTypeDef,
     ProvisionedProductPlanSummaryTypeDef,
+    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
     ListProvisioningArtifactsForServiceActionInputRequestTypeDef,
     ListProvisioningArtifactsInputRequestTypeDef,
     ListRecordHistorySearchFilterTypeDef,
+    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
     ListResourcesForTagOptionInputRequestTypeDef,
     ResourceDetailTypeDef,
+    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
     ListServiceActionsForProvisioningArtifactInputRequestTypeDef,
     ServiceActionSummaryTypeDef,
+    ListServiceActionsInputListServiceActionsPaginateTypeDef,
     ListServiceActionsInputRequestTypeDef,
     ListStackInstancesForProvisionedProductInputRequestTypeDef,
     StackInstanceTypeDef,
     ListTagOptionsFiltersTypeDef,
+    NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     ProductViewAggregationValueTypeDef,
     ProvisioningParameterTypeDef,
     ProvisioningPreferencesTypeDef,
     RecordErrorTypeDef,
     RecordTagTypeDef,
     RejectPortfolioShareInputRequestTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     SearchProductsAsAdminInputRequestTypeDef,
+    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
     SearchProductsInputRequestTypeDef,
     ShareErrorTypeDef,
     TerminateProvisionedProductInputRequestTypeDef,
     UpdateConstraintInputRequestTypeDef,
+    UpdatePortfolioShareOutputTypeDef,
     UpdateProvisioningPreferencesTypeDef,
     UpdateProvisionedProductPropertiesInputRequestTypeDef,
+    UpdateProvisionedProductPropertiesOutputTypeDef,
     UpdateProvisioningArtifactInputRequestTypeDef,
     UpdateServiceActionInputRequestTypeDef,
     UpdateTagOptionInputRequestTypeDef,
+    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
     ListProvisionedProductPlansInputRequestTypeDef,
     ScanProvisionedProductsInputRequestTypeDef,
+    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
     SearchProvisionedProductsInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef,
-    CopyProductOutputTypeDef,
-    CreatePortfolioShareOutputTypeDef,
-    CreateProvisionedProductPlanOutputTypeDef,
-    DeletePortfolioShareOutputTypeDef,
-    DescribeCopyProductStatusOutputTypeDef,
-    GetAWSOrganizationsAccessStatusOutputTypeDef,
-    ListPortfolioAccessOutputTypeDef,
-    UpdatePortfolioShareOutputTypeDef,
-    UpdateProvisionedProductPropertiesOutputTypeDef,
     ListBudgetsForResourceOutputTypeDef,
     SourceConnectionParametersTypeDef,
     CreateConstraintOutputTypeDef,
     DescribeConstraintOutputTypeDef,
     ListConstraintsForPortfolioOutputTypeDef,
     UpdateConstraintOutputTypeDef,
     CreatePortfolioInputRequestTypeDef,
@@ -574,15 +591,14 @@
     UpdatePortfolioOutputTypeDef,
     CreatePortfolioShareInputRequestTypeDef,
     DeletePortfolioShareInputRequestTypeDef,
     ListOrganizationPortfolioAccessOutputTypeDef,
     UpdatePortfolioShareInputRequestTypeDef,
     CreateProvisioningArtifactInputRequestTypeDef,
     CreateProvisioningArtifactOutputTypeDef,
-    DescribeProvisioningArtifactOutputTypeDef,
     ListProvisioningArtifactsOutputTypeDef,
     UpdateProvisioningArtifactOutputTypeDef,
     CreateProvisionedProductPlanInputRequestTypeDef,
     ProvisionedProductPlanDetailsTypeDef,
     CreateTagOptionOutputTypeDef,
     DescribePortfolioOutputTypeDef,
     DescribeTagOptionOutputTypeDef,
@@ -591,29 +607,17 @@
     DescribePortfolioSharesOutputTypeDef,
     DescribeProductOutputTypeDef,
     DescribeProductViewOutputTypeDef,
     ProvisioningArtifactViewTypeDef,
     DescribeProvisionedProductOutputTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     GetProvisionedProductOutputsOutputTypeDef,
+    NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
     DescribeServiceActionExecutionParametersOutputTypeDef,
-    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
-    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-    ListPortfoliosInputListPortfoliosPaginateTypeDef,
-    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
-    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
-    ListServiceActionsInputListServiceActionsPaginateTypeDef,
-    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
-    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
+    EngineWorkflowResourceIdentifierTypeDef,
     ListPrincipalsForPortfolioOutputTypeDef,
     ListProvisionedProductPlansOutputTypeDef,
     ListRecordHistoryInputListRecordHistoryPaginateTypeDef,
     ListRecordHistoryInputRequestTypeDef,
     ListResourcesForTagOptionOutputTypeDef,
     ListServiceActionsForProvisioningArtifactOutputTypeDef,
     ListServiceActionsOutputTypeDef,
@@ -629,17 +633,19 @@
     ShareDetailsTypeDef,
     UpdateProvisionedProductInputRequestTypeDef,
     SourceConnectionDetailTypeDef,
     SourceConnectionTypeDef,
     ListLaunchPathsOutputTypeDef,
     SearchProvisionedProductsOutputTypeDef,
     ListProvisioningArtifactsForServiceActionOutputTypeDef,
+    NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
     CreateServiceActionOutputTypeDef,
     DescribeServiceActionOutputTypeDef,
     UpdateServiceActionOutputTypeDef,
+    DescribeProvisioningArtifactOutputTypeDef,
     DescribeProvisioningParametersOutputTypeDef,
     DescribeRecordOutputTypeDef,
     ExecuteProvisionedProductPlanOutputTypeDef,
     ExecuteProvisionedProductServiceActionOutputTypeDef,
     ImportAsProvisionedProductOutputTypeDef,
     ListRecordHistoryOutputTypeDef,
     ProvisionProductOutputTypeDef,
@@ -665,43 +671,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/README.md` & `types-aiobotocore-servicecatalog-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-servicecatalog"></a>
 
 # types-aiobotocore-servicecatalog
 
 [![PyPI - types-aiobotocore-servicecatalog](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
+[aiobotocore.ServiceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
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
 [types-aiobotocore-servicecatalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,14 +325,15 @@
 from types_aiobotocore_servicecatalog.literals import (
     AccessLevelFilterKeyType,
     AccessStatusType,
     ChangeActionType,
     CopyOptionType,
     CopyProductStatusType,
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     EvaluationTypeType,
     LastSyncStatusType,
     ListAcceptedPortfolioSharesPaginatorName,
     ListConstraintsForPortfolioPaginatorName,
     ListLaunchPathsPaginatorName,
     ListOrganizationPortfolioAccessPaginatorName,
     ListPortfoliosForProductPaginatorName,
@@ -401,40 +402,44 @@
     AssociateBudgetWithResourceInputRequestTypeDef,
     AssociatePrincipalWithPortfolioInputRequestTypeDef,
     AssociateProductWithPortfolioInputRequestTypeDef,
     AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     AssociateTagOptionWithResourceInputRequestTypeDef,
     ServiceActionAssociationTypeDef,
     FailedServiceActionAssociationTypeDef,
-    ResponseMetadataTypeDef,
     BudgetDetailTypeDef,
     CloudWatchDashboardTypeDef,
     CodeStarParametersTypeDef,
     ConstraintDetailTypeDef,
     ConstraintSummaryTypeDef,
     CopyProductInputRequestTypeDef,
+    CopyProductOutputTypeDef,
     CreateConstraintInputRequestTypeDef,
     TagTypeDef,
     PortfolioDetailTypeDef,
     OrganizationNodeTypeDef,
+    CreatePortfolioShareOutputTypeDef,
     ProvisioningArtifactPropertiesTypeDef,
     ProvisioningArtifactDetailTypeDef,
     UpdateProvisioningParameterTypeDef,
+    CreateProvisionedProductPlanOutputTypeDef,
     CreateServiceActionInputRequestTypeDef,
     CreateTagOptionInputRequestTypeDef,
     TagOptionDetailTypeDef,
     DeleteConstraintInputRequestTypeDef,
     DeletePortfolioInputRequestTypeDef,
+    DeletePortfolioShareOutputTypeDef,
     DeleteProductInputRequestTypeDef,
     DeleteProvisionedProductPlanInputRequestTypeDef,
     DeleteProvisioningArtifactInputRequestTypeDef,
     DeleteServiceActionInputRequestTypeDef,
     DeleteTagOptionInputRequestTypeDef,
     DescribeConstraintInputRequestTypeDef,
     DescribeCopyProductStatusInputRequestTypeDef,
+    DescribeCopyProductStatusOutputTypeDef,
     DescribePortfolioInputRequestTypeDef,
     DescribePortfolioShareStatusInputRequestTypeDef,
     DescribePortfolioSharesInputRequestTypeDef,
     PortfolioShareDetailTypeDef,
     DescribeProductAsAdminInputRequestTypeDef,
     ProvisioningArtifactSummaryTypeDef,
     DescribeProductInputRequestTypeDef,
@@ -458,76 +463,88 @@
     DescribeServiceActionInputRequestTypeDef,
     DescribeTagOptionInputRequestTypeDef,
     DisassociateBudgetFromResourceInputRequestTypeDef,
     DisassociatePrincipalFromPortfolioInputRequestTypeDef,
     DisassociateProductFromPortfolioInputRequestTypeDef,
     DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     DisassociateTagOptionFromResourceInputRequestTypeDef,
+    UniqueTagResourceIdentifierTypeDef,
     ExecuteProvisionedProductPlanInputRequestTypeDef,
     ExecuteProvisionedProductServiceActionInputRequestTypeDef,
+    GetAWSOrganizationsAccessStatusOutputTypeDef,
     GetProvisionedProductOutputsInputRequestTypeDef,
     ImportAsProvisionedProductInputRequestTypeDef,
     LastSyncTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
     ListAcceptedPortfolioSharesInputRequestTypeDef,
     ListBudgetsForResourceInputRequestTypeDef,
+    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
     ListConstraintsForPortfolioInputRequestTypeDef,
+    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
     ListLaunchPathsInputRequestTypeDef,
+    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
     ListOrganizationPortfolioAccessInputRequestTypeDef,
     ListPortfolioAccessInputRequestTypeDef,
+    ListPortfolioAccessOutputTypeDef,
+    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
     ListPortfoliosForProductInputRequestTypeDef,
+    ListPortfoliosInputListPortfoliosPaginateTypeDef,
     ListPortfoliosInputRequestTypeDef,
+    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
     ListPrincipalsForPortfolioInputRequestTypeDef,
     PrincipalTypeDef,
     ProvisionedProductPlanSummaryTypeDef,
+    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
     ListProvisioningArtifactsForServiceActionInputRequestTypeDef,
     ListProvisioningArtifactsInputRequestTypeDef,
     ListRecordHistorySearchFilterTypeDef,
+    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
     ListResourcesForTagOptionInputRequestTypeDef,
     ResourceDetailTypeDef,
+    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
     ListServiceActionsForProvisioningArtifactInputRequestTypeDef,
     ServiceActionSummaryTypeDef,
+    ListServiceActionsInputListServiceActionsPaginateTypeDef,
     ListServiceActionsInputRequestTypeDef,
     ListStackInstancesForProvisionedProductInputRequestTypeDef,
     StackInstanceTypeDef,
     ListTagOptionsFiltersTypeDef,
+    NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     ProductViewAggregationValueTypeDef,
     ProvisioningParameterTypeDef,
     ProvisioningPreferencesTypeDef,
     RecordErrorTypeDef,
     RecordTagTypeDef,
     RejectPortfolioShareInputRequestTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     SearchProductsAsAdminInputRequestTypeDef,
+    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
     SearchProductsInputRequestTypeDef,
     ShareErrorTypeDef,
     TerminateProvisionedProductInputRequestTypeDef,
     UpdateConstraintInputRequestTypeDef,
+    UpdatePortfolioShareOutputTypeDef,
     UpdateProvisioningPreferencesTypeDef,
     UpdateProvisionedProductPropertiesInputRequestTypeDef,
+    UpdateProvisionedProductPropertiesOutputTypeDef,
     UpdateProvisioningArtifactInputRequestTypeDef,
     UpdateServiceActionInputRequestTypeDef,
     UpdateTagOptionInputRequestTypeDef,
+    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
     ListProvisionedProductPlansInputRequestTypeDef,
     ScanProvisionedProductsInputRequestTypeDef,
+    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
     SearchProvisionedProductsInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef,
-    CopyProductOutputTypeDef,
-    CreatePortfolioShareOutputTypeDef,
-    CreateProvisionedProductPlanOutputTypeDef,
-    DeletePortfolioShareOutputTypeDef,
-    DescribeCopyProductStatusOutputTypeDef,
-    GetAWSOrganizationsAccessStatusOutputTypeDef,
-    ListPortfolioAccessOutputTypeDef,
-    UpdatePortfolioShareOutputTypeDef,
-    UpdateProvisionedProductPropertiesOutputTypeDef,
     ListBudgetsForResourceOutputTypeDef,
     SourceConnectionParametersTypeDef,
     CreateConstraintOutputTypeDef,
     DescribeConstraintOutputTypeDef,
     ListConstraintsForPortfolioOutputTypeDef,
     UpdateConstraintOutputTypeDef,
     CreatePortfolioInputRequestTypeDef,
@@ -541,15 +558,14 @@
     UpdatePortfolioOutputTypeDef,
     CreatePortfolioShareInputRequestTypeDef,
     DeletePortfolioShareInputRequestTypeDef,
     ListOrganizationPortfolioAccessOutputTypeDef,
     UpdatePortfolioShareInputRequestTypeDef,
     CreateProvisioningArtifactInputRequestTypeDef,
     CreateProvisioningArtifactOutputTypeDef,
-    DescribeProvisioningArtifactOutputTypeDef,
     ListProvisioningArtifactsOutputTypeDef,
     UpdateProvisioningArtifactOutputTypeDef,
     CreateProvisionedProductPlanInputRequestTypeDef,
     ProvisionedProductPlanDetailsTypeDef,
     CreateTagOptionOutputTypeDef,
     DescribePortfolioOutputTypeDef,
     DescribeTagOptionOutputTypeDef,
@@ -558,29 +574,17 @@
     DescribePortfolioSharesOutputTypeDef,
     DescribeProductOutputTypeDef,
     DescribeProductViewOutputTypeDef,
     ProvisioningArtifactViewTypeDef,
     DescribeProvisionedProductOutputTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     GetProvisionedProductOutputsOutputTypeDef,
+    NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
     DescribeServiceActionExecutionParametersOutputTypeDef,
-    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
-    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-    ListPortfoliosInputListPortfoliosPaginateTypeDef,
-    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
-    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
-    ListServiceActionsInputListServiceActionsPaginateTypeDef,
-    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
-    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
+    EngineWorkflowResourceIdentifierTypeDef,
     ListPrincipalsForPortfolioOutputTypeDef,
     ListProvisionedProductPlansOutputTypeDef,
     ListRecordHistoryInputListRecordHistoryPaginateTypeDef,
     ListRecordHistoryInputRequestTypeDef,
     ListResourcesForTagOptionOutputTypeDef,
     ListServiceActionsForProvisioningArtifactOutputTypeDef,
     ListServiceActionsOutputTypeDef,
@@ -596,17 +600,19 @@
     ShareDetailsTypeDef,
     UpdateProvisionedProductInputRequestTypeDef,
     SourceConnectionDetailTypeDef,
     SourceConnectionTypeDef,
     ListLaunchPathsOutputTypeDef,
     SearchProvisionedProductsOutputTypeDef,
     ListProvisioningArtifactsForServiceActionOutputTypeDef,
+    NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
     CreateServiceActionOutputTypeDef,
     DescribeServiceActionOutputTypeDef,
     UpdateServiceActionOutputTypeDef,
+    DescribeProvisioningArtifactOutputTypeDef,
     DescribeProvisioningParametersOutputTypeDef,
     DescribeRecordOutputTypeDef,
     ExecuteProvisionedProductPlanOutputTypeDef,
     ExecuteProvisionedProductServiceActionOutputTypeDef,
     ImportAsProvisionedProductOutputTypeDef,
     ListRecordHistoryOutputTypeDef,
     ProvisionProductOutputTypeDef,
@@ -632,43 +638,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/setup.py` & `types-aiobotocore-servicecatalog-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-servicecatalog.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-servicecatalog",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_servicecatalog"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ServiceCatalog 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ServiceCatalog 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/"
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__init__.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__init__.pyi` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/__main__.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ServiceCatalog 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ServiceCatalog 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog\nOther"
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/client.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
     PrincipalTypeType,
     ProductTypeType,
     ProductViewFilterByType,
     ProductViewSortByType,
     PropertyKeyType,
@@ -77,14 +78,15 @@
     DescribeProvisionedProductPlanOutputTypeDef,
     DescribeProvisioningArtifactOutputTypeDef,
     DescribeProvisioningParametersOutputTypeDef,
     DescribeRecordOutputTypeDef,
     DescribeServiceActionExecutionParametersOutputTypeDef,
     DescribeServiceActionOutputTypeDef,
     DescribeTagOptionOutputTypeDef,
+    EngineWorkflowResourceIdentifierTypeDef,
     ExecuteProvisionedProductPlanOutputTypeDef,
     ExecuteProvisionedProductServiceActionOutputTypeDef,
     GetAWSOrganizationsAccessStatusOutputTypeDef,
     GetProvisionedProductOutputsOutputTypeDef,
     ImportAsProvisionedProductOutputTypeDef,
     ListAcceptedPortfolioSharesOutputTypeDef,
     ListBudgetsForResourceOutputTypeDef,
@@ -107,14 +109,15 @@
     ListTagOptionsFiltersTypeDef,
     ListTagOptionsOutputTypeDef,
     OrganizationNodeTypeDef,
     ProvisioningArtifactPropertiesTypeDef,
     ProvisioningParameterTypeDef,
     ProvisioningPreferencesTypeDef,
     ProvisionProductOutputTypeDef,
+    RecordOutputTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     SearchProductsAsAdminOutputTypeDef,
     SearchProductsOutputTypeDef,
     SearchProvisionedProductsOutputTypeDef,
     ServiceActionAssociationTypeDef,
     SourceConnectionTypeDef,
     TagTypeDef,
@@ -650,15 +653,16 @@
         self,
         *,
         AcceptLanguage: str = ...,
         ProvisioningArtifactId: str = ...,
         ProductId: str = ...,
         ProvisioningArtifactName: str = ...,
         ProductName: str = ...,
-        Verbose: bool = ...
+        Verbose: bool = ...,
+        IncludeProvisioningArtifactParameters: bool = ...
     ) -> DescribeProvisioningArtifactOutputTypeDef:
         """
         Gets information about the specified provisioning artifact (also known as a
         version) for the specified product.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.describe_provisioning_artifact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#describe_provisioning_artifact)
@@ -857,15 +861,15 @@
         ProvisionedProductId: str = ...,
         ProvisionedProductName: str = ...,
         OutputKeys: Sequence[str] = ...,
         PageSize: int = ...,
         PageToken: str = ...
     ) -> GetProvisionedProductOutputsOutputTypeDef:
         """
-        This API takes either a `ProvisonedProductId` or a `ProvisionedProductName` ,
+        This API takes either a `ProvisonedProductId` or a `ProvisionedProductName`,
         along with a list of one or more output keys, and responds with the key/value
         pairs of those outputs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.get_provisioned_product_outputs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#get_provisioned_product_outputs)
         """
 
@@ -1011,16 +1015,16 @@
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
         PageSize: int = ...,
         PageToken: str = ...
     ) -> ListPrincipalsForPortfolioOutputTypeDef:
         """
-        Lists all `PrincipalARN` s and corresponding `PrincipalType` s associated with
-        the specified portfolio.
+        Lists all `PrincipalARN`s and corresponding `PrincipalType`s associated with the
+        specified portfolio.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.list_principals_for_portfolio)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#list_principals_for_portfolio)
         """
 
     async def list_provisioned_product_plans(
         self,
@@ -1150,14 +1154,65 @@
         """
         Lists the specified TagOptions or all TagOptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.list_tag_options)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#list_tag_options)
         """
 
+    async def notify_provision_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...,
+        ResourceIdentifier: EngineWorkflowResourceIdentifierTypeDef = ...,
+        Outputs: Sequence[RecordOutputTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the provisioning engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_provision_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_provision_product_engine_workflow_result)
+        """
+
+    async def notify_terminate_provisioned_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the terminate engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_terminate_provisioned_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_terminate_provisioned_product_engine_workflow_result)
+        """
+
+    async def notify_update_provisioned_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...,
+        Outputs: Sequence[RecordOutputTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the update engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_update_provisioned_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_update_provisioned_product_engine_workflow_result)
+        """
+
     async def provision_product(
         self,
         *,
         ProvisionedProductName: str,
         ProvisionToken: str,
         AcceptLanguage: str = ...,
         ProductId: str = ...,
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/client.pyi` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
     PrincipalTypeType,
     ProductTypeType,
     ProductViewFilterByType,
     ProductViewSortByType,
     PropertyKeyType,
@@ -77,14 +78,15 @@
     DescribeProvisionedProductPlanOutputTypeDef,
     DescribeProvisioningArtifactOutputTypeDef,
     DescribeProvisioningParametersOutputTypeDef,
     DescribeRecordOutputTypeDef,
     DescribeServiceActionExecutionParametersOutputTypeDef,
     DescribeServiceActionOutputTypeDef,
     DescribeTagOptionOutputTypeDef,
+    EngineWorkflowResourceIdentifierTypeDef,
     ExecuteProvisionedProductPlanOutputTypeDef,
     ExecuteProvisionedProductServiceActionOutputTypeDef,
     GetAWSOrganizationsAccessStatusOutputTypeDef,
     GetProvisionedProductOutputsOutputTypeDef,
     ImportAsProvisionedProductOutputTypeDef,
     ListAcceptedPortfolioSharesOutputTypeDef,
     ListBudgetsForResourceOutputTypeDef,
@@ -107,14 +109,15 @@
     ListTagOptionsFiltersTypeDef,
     ListTagOptionsOutputTypeDef,
     OrganizationNodeTypeDef,
     ProvisioningArtifactPropertiesTypeDef,
     ProvisioningParameterTypeDef,
     ProvisioningPreferencesTypeDef,
     ProvisionProductOutputTypeDef,
+    RecordOutputTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     SearchProductsAsAdminOutputTypeDef,
     SearchProductsOutputTypeDef,
     SearchProvisionedProductsOutputTypeDef,
     ServiceActionAssociationTypeDef,
     SourceConnectionTypeDef,
     TagTypeDef,
@@ -608,15 +611,16 @@
         self,
         *,
         AcceptLanguage: str = ...,
         ProvisioningArtifactId: str = ...,
         ProductId: str = ...,
         ProvisioningArtifactName: str = ...,
         ProductName: str = ...,
-        Verbose: bool = ...
+        Verbose: bool = ...,
+        IncludeProvisioningArtifactParameters: bool = ...
     ) -> DescribeProvisioningArtifactOutputTypeDef:
         """
         Gets information about the specified provisioning artifact (also known as a
         version) for the specified product.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.describe_provisioning_artifact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#describe_provisioning_artifact)
@@ -798,15 +802,15 @@
         ProvisionedProductId: str = ...,
         ProvisionedProductName: str = ...,
         OutputKeys: Sequence[str] = ...,
         PageSize: int = ...,
         PageToken: str = ...
     ) -> GetProvisionedProductOutputsOutputTypeDef:
         """
-        This API takes either a `ProvisonedProductId` or a `ProvisionedProductName` ,
+        This API takes either a `ProvisonedProductId` or a `ProvisionedProductName`,
         along with a list of one or more output keys, and responds with the key/value
         pairs of those outputs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.get_provisioned_product_outputs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#get_provisioned_product_outputs)
         """
     async def import_as_provisioned_product(
@@ -942,16 +946,16 @@
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
         PageSize: int = ...,
         PageToken: str = ...
     ) -> ListPrincipalsForPortfolioOutputTypeDef:
         """
-        Lists all `PrincipalARN` s and corresponding `PrincipalType` s associated with
-        the specified portfolio.
+        Lists all `PrincipalARN`s and corresponding `PrincipalType`s associated with the
+        specified portfolio.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.list_principals_for_portfolio)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#list_principals_for_portfolio)
         """
     async def list_provisioned_product_plans(
         self,
         *,
@@ -1071,14 +1075,62 @@
     ) -> ListTagOptionsOutputTypeDef:
         """
         Lists the specified TagOptions or all TagOptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.list_tag_options)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#list_tag_options)
         """
+    async def notify_provision_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...,
+        ResourceIdentifier: EngineWorkflowResourceIdentifierTypeDef = ...,
+        Outputs: Sequence[RecordOutputTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the provisioning engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_provision_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_provision_product_engine_workflow_result)
+        """
+    async def notify_terminate_provisioned_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the terminate engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_terminate_provisioned_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_terminate_provisioned_product_engine_workflow_result)
+        """
+    async def notify_update_provisioned_product_engine_workflow_result(
+        self,
+        *,
+        WorkflowToken: str,
+        RecordId: str,
+        Status: EngineWorkflowStatusType,
+        IdempotencyToken: str,
+        FailureReason: str = ...,
+        Outputs: Sequence[RecordOutputTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Notifies the result of the update engine execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Client.notify_update_provisioned_product_engine_workflow_result)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/client/#notify_update_provisioned_product_engine_workflow_result)
+        """
     async def provision_product(
         self,
         *,
         ProvisionedProductName: str,
         ProvisionToken: str,
         AcceptLanguage: str = ...,
         ProductId: str = ...,
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/literals.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 __all__ = (
     "AccessLevelFilterKeyType",
     "AccessStatusType",
     "ChangeActionType",
     "CopyOptionType",
     "CopyProductStatusType",
     "DescribePortfolioShareTypeType",
+    "EngineWorkflowStatusType",
     "EvaluationTypeType",
     "LastSyncStatusType",
     "ListAcceptedPortfolioSharesPaginatorName",
     "ListConstraintsForPortfolioPaginatorName",
     "ListLaunchPathsPaginatorName",
     "ListOrganizationPortfolioAccessPaginatorName",
     "ListPortfoliosForProductPaginatorName",
@@ -84,14 +85,15 @@
 AccessStatusType = Literal["DISABLED", "ENABLED", "UNDER_CHANGE"]
 ChangeActionType = Literal["ADD", "MODIFY", "REMOVE"]
 CopyOptionType = Literal["CopyTags"]
 CopyProductStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 DescribePortfolioShareTypeType = Literal[
     "ACCOUNT", "ORGANIZATION", "ORGANIZATIONAL_UNIT", "ORGANIZATION_MEMBER_ACCOUNT"
 ]
+EngineWorkflowStatusType = Literal["FAILED", "SUCCEEDED"]
 EvaluationTypeType = Literal["DYNAMIC", "STATIC"]
 LastSyncStatusType = Literal["FAILED", "SUCCEEDED"]
 ListAcceptedPortfolioSharesPaginatorName = Literal["list_accepted_portfolio_shares"]
 ListConstraintsForPortfolioPaginatorName = Literal["list_constraints_for_portfolio"]
 ListLaunchPathsPaginatorName = Literal["list_launch_paths"]
 ListOrganizationPortfolioAccessPaginatorName = Literal["list_organization_portfolio_access"]
 ListPortfoliosForProductPaginatorName = Literal["list_portfolios_for_product"]
@@ -108,15 +110,15 @@
 ]
 ListServiceActionsPaginatorName = Literal["list_service_actions"]
 ListTagOptionsPaginatorName = Literal["list_tag_options"]
 OrganizationNodeTypeType = Literal["ACCOUNT", "ORGANIZATION", "ORGANIZATIONAL_UNIT"]
 PortfolioShareTypeType = Literal["AWS_ORGANIZATIONS", "AWS_SERVICECATALOG", "IMPORTED"]
 PrincipalTypeType = Literal["IAM", "IAM_PATTERN"]
 ProductSourceType = Literal["ACCOUNT"]
-ProductTypeType = Literal["CLOUD_FORMATION_TEMPLATE", "MARKETPLACE"]
+ProductTypeType = Literal["CLOUD_FORMATION_TEMPLATE", "MARKETPLACE", "TERRAFORM_OPEN_SOURCE"]
 ProductViewFilterByType = Literal["FullTextSearch", "Owner", "ProductType", "SourceProductId"]
 ProductViewSortByType = Literal["CreationDate", "Title", "VersionCount"]
 PropertyKeyType = Literal["LAUNCH_ROLE", "OWNER"]
 ProvisionedProductPlanStatusType = Literal[
     "CREATE_FAILED",
     "CREATE_IN_PROGRESS",
     "CREATE_SUCCESS",
@@ -128,26 +130,31 @@
 ProvisionedProductStatusType = Literal[
     "AVAILABLE", "ERROR", "PLAN_IN_PROGRESS", "TAINTED", "UNDER_CHANGE"
 ]
 ProvisionedProductViewFilterByType = Literal["SearchQuery"]
 ProvisioningArtifactGuidanceType = Literal["DEFAULT", "DEPRECATED"]
 ProvisioningArtifactPropertyNameType = Literal["Id"]
 ProvisioningArtifactTypeType = Literal[
-    "CLOUD_FORMATION_TEMPLATE", "MARKETPLACE_AMI", "MARKETPLACE_CAR"
+    "CLOUD_FORMATION_TEMPLATE", "MARKETPLACE_AMI", "MARKETPLACE_CAR", "TERRAFORM_OPEN_SOURCE"
 ]
 RecordStatusType = Literal["CREATED", "FAILED", "IN_PROGRESS", "IN_PROGRESS_IN_ERROR", "SUCCEEDED"]
 ReplacementType = Literal["CONDITIONAL", "FALSE", "TRUE"]
 RequiresRecreationType = Literal["ALWAYS", "CONDITIONALLY", "NEVER"]
 ResourceAttributeType = Literal[
     "CREATIONPOLICY", "DELETIONPOLICY", "METADATA", "PROPERTIES", "TAGS", "UPDATEPOLICY"
 ]
 ScanProvisionedProductsPaginatorName = Literal["scan_provisioned_products"]
 SearchProductsAsAdminPaginatorName = Literal["search_products_as_admin"]
 ServiceActionAssociationErrorCodeType = Literal[
-    "DUPLICATE_RESOURCE", "INTERNAL_FAILURE", "LIMIT_EXCEEDED", "RESOURCE_NOT_FOUND", "THROTTLING"
+    "DUPLICATE_RESOURCE",
+    "INTERNAL_FAILURE",
+    "INVALID_PARAMETER",
+    "LIMIT_EXCEEDED",
+    "RESOURCE_NOT_FOUND",
+    "THROTTLING",
 ]
 ServiceActionDefinitionKeyType = Literal["AssumeRole", "Name", "Parameters", "Version"]
 ServiceActionDefinitionTypeType = Literal["SSM_AUTOMATION"]
 ShareStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "ERROR", "IN_PROGRESS", "NOT_STARTED"
 ]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
@@ -214,14 +221,15 @@
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
@@ -300,14 +308,15 @@
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
@@ -318,14 +327,15 @@
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
@@ -361,14 +371,15 @@
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
@@ -387,16 +398,19 @@
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
@@ -480,15 +494,17 @@
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
@@ -531,24 +547,29 @@
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
+    "ap-southeast-4",
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/literals.pyi` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/literals.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 __all__ = (
     "AccessLevelFilterKeyType",
     "AccessStatusType",
     "ChangeActionType",
     "CopyOptionType",
     "CopyProductStatusType",
     "DescribePortfolioShareTypeType",
+    "EngineWorkflowStatusType",
     "EvaluationTypeType",
     "LastSyncStatusType",
     "ListAcceptedPortfolioSharesPaginatorName",
     "ListConstraintsForPortfolioPaginatorName",
     "ListLaunchPathsPaginatorName",
     "ListOrganizationPortfolioAccessPaginatorName",
     "ListPortfoliosForProductPaginatorName",
@@ -82,14 +83,15 @@
 AccessStatusType = Literal["DISABLED", "ENABLED", "UNDER_CHANGE"]
 ChangeActionType = Literal["ADD", "MODIFY", "REMOVE"]
 CopyOptionType = Literal["CopyTags"]
 CopyProductStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 DescribePortfolioShareTypeType = Literal[
     "ACCOUNT", "ORGANIZATION", "ORGANIZATIONAL_UNIT", "ORGANIZATION_MEMBER_ACCOUNT"
 ]
+EngineWorkflowStatusType = Literal["FAILED", "SUCCEEDED"]
 EvaluationTypeType = Literal["DYNAMIC", "STATIC"]
 LastSyncStatusType = Literal["FAILED", "SUCCEEDED"]
 ListAcceptedPortfolioSharesPaginatorName = Literal["list_accepted_portfolio_shares"]
 ListConstraintsForPortfolioPaginatorName = Literal["list_constraints_for_portfolio"]
 ListLaunchPathsPaginatorName = Literal["list_launch_paths"]
 ListOrganizationPortfolioAccessPaginatorName = Literal["list_organization_portfolio_access"]
 ListPortfoliosForProductPaginatorName = Literal["list_portfolios_for_product"]
@@ -106,15 +108,15 @@
 ]
 ListServiceActionsPaginatorName = Literal["list_service_actions"]
 ListTagOptionsPaginatorName = Literal["list_tag_options"]
 OrganizationNodeTypeType = Literal["ACCOUNT", "ORGANIZATION", "ORGANIZATIONAL_UNIT"]
 PortfolioShareTypeType = Literal["AWS_ORGANIZATIONS", "AWS_SERVICECATALOG", "IMPORTED"]
 PrincipalTypeType = Literal["IAM", "IAM_PATTERN"]
 ProductSourceType = Literal["ACCOUNT"]
-ProductTypeType = Literal["CLOUD_FORMATION_TEMPLATE", "MARKETPLACE"]
+ProductTypeType = Literal["CLOUD_FORMATION_TEMPLATE", "MARKETPLACE", "TERRAFORM_OPEN_SOURCE"]
 ProductViewFilterByType = Literal["FullTextSearch", "Owner", "ProductType", "SourceProductId"]
 ProductViewSortByType = Literal["CreationDate", "Title", "VersionCount"]
 PropertyKeyType = Literal["LAUNCH_ROLE", "OWNER"]
 ProvisionedProductPlanStatusType = Literal[
     "CREATE_FAILED",
     "CREATE_IN_PROGRESS",
     "CREATE_SUCCESS",
@@ -126,26 +128,31 @@
 ProvisionedProductStatusType = Literal[
     "AVAILABLE", "ERROR", "PLAN_IN_PROGRESS", "TAINTED", "UNDER_CHANGE"
 ]
 ProvisionedProductViewFilterByType = Literal["SearchQuery"]
 ProvisioningArtifactGuidanceType = Literal["DEFAULT", "DEPRECATED"]
 ProvisioningArtifactPropertyNameType = Literal["Id"]
 ProvisioningArtifactTypeType = Literal[
-    "CLOUD_FORMATION_TEMPLATE", "MARKETPLACE_AMI", "MARKETPLACE_CAR"
+    "CLOUD_FORMATION_TEMPLATE", "MARKETPLACE_AMI", "MARKETPLACE_CAR", "TERRAFORM_OPEN_SOURCE"
 ]
 RecordStatusType = Literal["CREATED", "FAILED", "IN_PROGRESS", "IN_PROGRESS_IN_ERROR", "SUCCEEDED"]
 ReplacementType = Literal["CONDITIONAL", "FALSE", "TRUE"]
 RequiresRecreationType = Literal["ALWAYS", "CONDITIONALLY", "NEVER"]
 ResourceAttributeType = Literal[
     "CREATIONPOLICY", "DELETIONPOLICY", "METADATA", "PROPERTIES", "TAGS", "UPDATEPOLICY"
 ]
 ScanProvisionedProductsPaginatorName = Literal["scan_provisioned_products"]
 SearchProductsAsAdminPaginatorName = Literal["search_products_as_admin"]
 ServiceActionAssociationErrorCodeType = Literal[
-    "DUPLICATE_RESOURCE", "INTERNAL_FAILURE", "LIMIT_EXCEEDED", "RESOURCE_NOT_FOUND", "THROTTLING"
+    "DUPLICATE_RESOURCE",
+    "INTERNAL_FAILURE",
+    "INVALID_PARAMETER",
+    "LIMIT_EXCEEDED",
+    "RESOURCE_NOT_FOUND",
+    "THROTTLING",
 ]
 ServiceActionDefinitionKeyType = Literal["AssumeRole", "Name", "Parameters", "Version"]
 ServiceActionDefinitionTypeType = Literal["SSM_AUTOMATION"]
 ShareStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "ERROR", "IN_PROGRESS", "NOT_STARTED"
 ]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
@@ -212,14 +219,15 @@
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
@@ -298,14 +306,15 @@
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
@@ -316,14 +325,15 @@
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
@@ -359,14 +369,15 @@
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
@@ -385,16 +396,19 @@
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
@@ -478,15 +492,17 @@
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
@@ -529,24 +545,29 @@
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
+    "ap-southeast-4",
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/paginator.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -47,15 +47,15 @@
         list_service_actions_for_provisioning_artifact_paginator: ListServiceActionsForProvisioningArtifactPaginator = client.get_paginator("list_service_actions_for_provisioning_artifact")
         list_tag_options_paginator: ListTagOptionsPaginator = client.get_paginator("list_tag_options")
         scan_provisioned_products_paginator: ScanProvisionedProductsPaginator = client.get_paginator("scan_provisioned_products")
         search_products_as_admin_paginator: SearchProductsAsAdminPaginator = client.get_paginator("search_products_as_admin")
     ```
 """
 import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
@@ -82,24 +82,19 @@
     ListTagOptionsFiltersTypeDef,
     ListTagOptionsOutputTypeDef,
     PaginatorConfigTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     SearchProductsAsAdminOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ListAcceptedPortfolioSharesPaginator",
     "ListConstraintsForPortfolioPaginator",
     "ListLaunchPathsPaginator",
     "ListOrganizationPortfolioAccessPaginator",
     "ListPortfoliosPaginator",
     "ListPortfoliosForProductPaginator",
@@ -111,306 +106,288 @@
     "ListServiceActionsPaginator",
     "ListServiceActionsForProvisioningArtifactPaginator",
     "ListTagOptionsPaginator",
     "ScanProvisionedProductsPaginator",
     "SearchProductsAsAdminPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListAcceptedPortfolioSharesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListAcceptedPortfolioShares)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listacceptedportfoliosharespaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         PortfolioShareType: PortfolioShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAcceptedPortfolioSharesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListAcceptedPortfolioShares.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listacceptedportfoliosharespaginator)
         """
 
-
 class ListConstraintsForPortfolioPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListConstraintsForPortfolio)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listconstraintsforportfoliopaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
         ProductId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConstraintsForPortfolioOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListConstraintsForPortfolio.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listconstraintsforportfoliopaginator)
         """
 
-
 class ListLaunchPathsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListLaunchPaths)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listlaunchpathspaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchPathsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListLaunchPaths.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listlaunchpathspaginator)
         """
 
-
 class ListOrganizationPortfolioAccessPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListOrganizationPortfolioAccess)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listorganizationportfolioaccesspaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         OrganizationNodeType: OrganizationNodeTypeType,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationPortfolioAccessOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListOrganizationPortfolioAccess.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listorganizationportfolioaccesspaginator)
         """
 
-
 class ListPortfoliosPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfolios)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliospaginator)
     """
 
     def paginate(
-        self, *, AcceptLanguage: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceptLanguage: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortfoliosOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfolios.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliospaginator)
         """
 
-
 class ListPortfoliosForProductPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfoliosForProduct)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliosforproductpaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortfoliosForProductOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfoliosForProduct.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliosforproductpaginator)
         """
 
-
 class ListPrincipalsForPortfolioPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPrincipalsForPortfolio)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprincipalsforportfoliopaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalsForPortfolioOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPrincipalsForPortfolio.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprincipalsforportfoliopaginator)
         """
 
-
 class ListProvisionedProductPlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisionedProductPlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisionedproductplanspaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         ProvisionProductId: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisionedProductPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisionedProductPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisionedproductplanspaginator)
         """
 
-
 class ListProvisioningArtifactsForServiceActionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisioningArtifactsForServiceAction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisioningartifactsforserviceactionpaginator)
     """
 
     def paginate(
         self,
         *,
         ServiceActionId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningArtifactsForServiceActionOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisioningArtifactsForServiceAction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisioningartifactsforserviceactionpaginator)
         """
 
-
 class ListRecordHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListRecordHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listrecordhistorypaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
         SearchFilter: ListRecordHistorySearchFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecordHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListRecordHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listrecordhistorypaginator)
         """
 
-
 class ListResourcesForTagOptionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListResourcesForTagOption)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listresourcesfortagoptionpaginator)
     """
 
     def paginate(
         self,
         *,
         TagOptionId: str,
         ResourceType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesForTagOptionOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListResourcesForTagOption.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listresourcesfortagoptionpaginator)
         """
 
-
 class ListServiceActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionspaginator)
     """
 
     def paginate(
-        self, *, AcceptLanguage: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceptLanguage: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceActionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionspaginator)
         """
 
-
 class ListServiceActionsForProvisioningArtifactPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActionsForProvisioningArtifact)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionsforprovisioningartifactpaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         ProvisioningArtifactId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceActionsForProvisioningArtifactOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActionsForProvisioningArtifact.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionsforprovisioningartifactpaginator)
         """
 
-
 class ListTagOptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListTagOptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listtagoptionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: ListTagOptionsFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagOptionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListTagOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listtagoptionspaginator)
         """
 
-
 class ScanProvisionedProductsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ScanProvisionedProducts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#scanprovisionedproductspaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScanProvisionedProductsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ScanProvisionedProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#scanprovisionedproductspaginator)
         """
 
-
 class SearchProductsAsAdminPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.SearchProductsAsAdmin)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#searchproductsasadminpaginator)
     """
 
     def paginate(
@@ -418,13 +395,13 @@
         *,
         AcceptLanguage: str = ...,
         PortfolioId: str = ...,
         Filters: Mapping[ProductViewFilterByType, Sequence[str]] = ...,
         SortBy: ProductViewSortByType = ...,
         SortOrder: SortOrderType = ...,
         ProductSource: Literal["ACCOUNT"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchProductsAsAdminOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.SearchProductsAsAdmin.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#searchproductsasadminpaginator)
         """
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/paginator.pyi` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -47,15 +47,15 @@
         list_service_actions_for_provisioning_artifact_paginator: ListServiceActionsForProvisioningArtifactPaginator = client.get_paginator("list_service_actions_for_provisioning_artifact")
         list_tag_options_paginator: ListTagOptionsPaginator = client.get_paginator("list_tag_options")
         scan_provisioned_products_paginator: ScanProvisionedProductsPaginator = client.get_paginator("scan_provisioned_products")
         search_products_as_admin_paginator: SearchProductsAsAdminPaginator = client.get_paginator("search_products_as_admin")
     ```
 """
 import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
@@ -82,23 +82,20 @@
     ListTagOptionsFiltersTypeDef,
     ListTagOptionsOutputTypeDef,
     PaginatorConfigTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     SearchProductsAsAdminOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ListAcceptedPortfolioSharesPaginator",
     "ListConstraintsForPortfolioPaginator",
     "ListLaunchPathsPaginator",
     "ListOrganizationPortfolioAccessPaginator",
     "ListPortfoliosPaginator",
     "ListPortfoliosForProductPaginator",
@@ -110,288 +107,306 @@
     "ListServiceActionsPaginator",
     "ListServiceActionsForProvisioningArtifactPaginator",
     "ListTagOptionsPaginator",
     "ScanProvisionedProductsPaginator",
     "SearchProductsAsAdminPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListAcceptedPortfolioSharesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListAcceptedPortfolioShares)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listacceptedportfoliosharespaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         PortfolioShareType: PortfolioShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAcceptedPortfolioSharesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListAcceptedPortfolioShares.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listacceptedportfoliosharespaginator)
         """
 
+
 class ListConstraintsForPortfolioPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListConstraintsForPortfolio)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listconstraintsforportfoliopaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
         ProductId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConstraintsForPortfolioOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListConstraintsForPortfolio.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listconstraintsforportfoliopaginator)
         """
 
+
 class ListLaunchPathsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListLaunchPaths)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listlaunchpathspaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchPathsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListLaunchPaths.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listlaunchpathspaginator)
         """
 
+
 class ListOrganizationPortfolioAccessPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListOrganizationPortfolioAccess)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listorganizationportfolioaccesspaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         OrganizationNodeType: OrganizationNodeTypeType,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationPortfolioAccessOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListOrganizationPortfolioAccess.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listorganizationportfolioaccesspaginator)
         """
 
+
 class ListPortfoliosPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfolios)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliospaginator)
     """
 
     def paginate(
-        self, *, AcceptLanguage: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceptLanguage: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortfoliosOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfolios.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliospaginator)
         """
 
+
 class ListPortfoliosForProductPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfoliosForProduct)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliosforproductpaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortfoliosForProductOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPortfoliosForProduct.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listportfoliosforproductpaginator)
         """
 
+
 class ListPrincipalsForPortfolioPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPrincipalsForPortfolio)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprincipalsforportfoliopaginator)
     """
 
     def paginate(
         self,
         *,
         PortfolioId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalsForPortfolioOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListPrincipalsForPortfolio.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprincipalsforportfoliopaginator)
         """
 
+
 class ListProvisionedProductPlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisionedProductPlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisionedproductplanspaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         ProvisionProductId: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisionedProductPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisionedProductPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisionedproductplanspaginator)
         """
 
+
 class ListProvisioningArtifactsForServiceActionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisioningArtifactsForServiceAction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisioningartifactsforserviceactionpaginator)
     """
 
     def paginate(
         self,
         *,
         ServiceActionId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningArtifactsForServiceActionOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListProvisioningArtifactsForServiceAction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listprovisioningartifactsforserviceactionpaginator)
         """
 
+
 class ListRecordHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListRecordHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listrecordhistorypaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
         SearchFilter: ListRecordHistorySearchFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecordHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListRecordHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listrecordhistorypaginator)
         """
 
+
 class ListResourcesForTagOptionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListResourcesForTagOption)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listresourcesfortagoptionpaginator)
     """
 
     def paginate(
         self,
         *,
         TagOptionId: str,
         ResourceType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesForTagOptionOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListResourcesForTagOption.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listresourcesfortagoptionpaginator)
         """
 
+
 class ListServiceActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionspaginator)
     """
 
     def paginate(
-        self, *, AcceptLanguage: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceptLanguage: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceActionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionspaginator)
         """
 
+
 class ListServiceActionsForProvisioningArtifactPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActionsForProvisioningArtifact)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionsforprovisioningartifactpaginator)
     """
 
     def paginate(
         self,
         *,
         ProductId: str,
         ProvisioningArtifactId: str,
         AcceptLanguage: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceActionsForProvisioningArtifactOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListServiceActionsForProvisioningArtifact.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listserviceactionsforprovisioningartifactpaginator)
         """
 
+
 class ListTagOptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListTagOptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listtagoptionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: ListTagOptionsFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagOptionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ListTagOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#listtagoptionspaginator)
         """
 
+
 class ScanProvisionedProductsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ScanProvisionedProducts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#scanprovisionedproductspaginator)
     """
 
     def paginate(
         self,
         *,
         AcceptLanguage: str = ...,
         AccessLevelFilter: AccessLevelFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScanProvisionedProductsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.ScanProvisionedProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#scanprovisionedproductspaginator)
         """
 
+
 class SearchProductsAsAdminPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.SearchProductsAsAdmin)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#searchproductsasadminpaginator)
     """
 
     def paginate(
@@ -399,13 +414,13 @@
         *,
         AcceptLanguage: str = ...,
         PortfolioId: str = ...,
         Filters: Mapping[ProductViewFilterByType, Sequence[str]] = ...,
         SortBy: ProductViewSortByType = ...,
         SortOrder: SortOrderType = ...,
         ProductSource: Literal["ACCOUNT"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchProductsAsAdminOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog.Paginator.SearchProductsAsAdmin.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/paginators/#searchproductsasadminpaginator)
         """
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/type_defs.py` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 
 from .literals import (
     AccessLevelFilterKeyType,
     AccessStatusType,
     ChangeActionType,
     CopyProductStatusType,
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     EvaluationTypeType,
     LastSyncStatusType,
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
     PrincipalTypeType,
     ProductTypeType,
     ProductViewFilterByType,
@@ -52,51 +53,54 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AcceptPortfolioShareInputRequestTypeDef",
     "AccessLevelFilterTypeDef",
     "AssociateBudgetWithResourceInputRequestTypeDef",
     "AssociatePrincipalWithPortfolioInputRequestTypeDef",
     "AssociateProductWithPortfolioInputRequestTypeDef",
     "AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     "AssociateTagOptionWithResourceInputRequestTypeDef",
     "ServiceActionAssociationTypeDef",
     "FailedServiceActionAssociationTypeDef",
-    "ResponseMetadataTypeDef",
     "BudgetDetailTypeDef",
     "CloudWatchDashboardTypeDef",
     "CodeStarParametersTypeDef",
     "ConstraintDetailTypeDef",
     "ConstraintSummaryTypeDef",
     "CopyProductInputRequestTypeDef",
+    "CopyProductOutputTypeDef",
     "CreateConstraintInputRequestTypeDef",
     "TagTypeDef",
     "PortfolioDetailTypeDef",
     "OrganizationNodeTypeDef",
+    "CreatePortfolioShareOutputTypeDef",
     "ProvisioningArtifactPropertiesTypeDef",
     "ProvisioningArtifactDetailTypeDef",
     "UpdateProvisioningParameterTypeDef",
+    "CreateProvisionedProductPlanOutputTypeDef",
     "CreateServiceActionInputRequestTypeDef",
     "CreateTagOptionInputRequestTypeDef",
     "TagOptionDetailTypeDef",
     "DeleteConstraintInputRequestTypeDef",
     "DeletePortfolioInputRequestTypeDef",
+    "DeletePortfolioShareOutputTypeDef",
     "DeleteProductInputRequestTypeDef",
     "DeleteProvisionedProductPlanInputRequestTypeDef",
     "DeleteProvisioningArtifactInputRequestTypeDef",
     "DeleteServiceActionInputRequestTypeDef",
     "DeleteTagOptionInputRequestTypeDef",
     "DescribeConstraintInputRequestTypeDef",
     "DescribeCopyProductStatusInputRequestTypeDef",
+    "DescribeCopyProductStatusOutputTypeDef",
     "DescribePortfolioInputRequestTypeDef",
     "DescribePortfolioShareStatusInputRequestTypeDef",
     "DescribePortfolioSharesInputRequestTypeDef",
     "PortfolioShareDetailTypeDef",
     "DescribeProductAsAdminInputRequestTypeDef",
     "ProvisioningArtifactSummaryTypeDef",
     "DescribeProductInputRequestTypeDef",
@@ -120,76 +124,88 @@
     "DescribeServiceActionInputRequestTypeDef",
     "DescribeTagOptionInputRequestTypeDef",
     "DisassociateBudgetFromResourceInputRequestTypeDef",
     "DisassociatePrincipalFromPortfolioInputRequestTypeDef",
     "DisassociateProductFromPortfolioInputRequestTypeDef",
     "DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     "DisassociateTagOptionFromResourceInputRequestTypeDef",
+    "UniqueTagResourceIdentifierTypeDef",
     "ExecuteProvisionedProductPlanInputRequestTypeDef",
     "ExecuteProvisionedProductServiceActionInputRequestTypeDef",
+    "GetAWSOrganizationsAccessStatusOutputTypeDef",
     "GetProvisionedProductOutputsInputRequestTypeDef",
     "ImportAsProvisionedProductInputRequestTypeDef",
     "LastSyncTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
     "ListAcceptedPortfolioSharesInputRequestTypeDef",
     "ListBudgetsForResourceInputRequestTypeDef",
+    "ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
     "ListConstraintsForPortfolioInputRequestTypeDef",
+    "ListLaunchPathsInputListLaunchPathsPaginateTypeDef",
     "ListLaunchPathsInputRequestTypeDef",
+    "ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
     "ListOrganizationPortfolioAccessInputRequestTypeDef",
     "ListPortfolioAccessInputRequestTypeDef",
+    "ListPortfolioAccessOutputTypeDef",
+    "ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
     "ListPortfoliosForProductInputRequestTypeDef",
+    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
     "ListPortfoliosInputRequestTypeDef",
+    "ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
     "ListPrincipalsForPortfolioInputRequestTypeDef",
     "PrincipalTypeDef",
     "ProvisionedProductPlanSummaryTypeDef",
+    "ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
     "ListProvisioningArtifactsForServiceActionInputRequestTypeDef",
     "ListProvisioningArtifactsInputRequestTypeDef",
     "ListRecordHistorySearchFilterTypeDef",
+    "ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
     "ListResourcesForTagOptionInputRequestTypeDef",
     "ResourceDetailTypeDef",
+    "ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
     "ListServiceActionsForProvisioningArtifactInputRequestTypeDef",
     "ServiceActionSummaryTypeDef",
+    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
     "ListServiceActionsInputRequestTypeDef",
     "ListStackInstancesForProvisionedProductInputRequestTypeDef",
     "StackInstanceTypeDef",
     "ListTagOptionsFiltersTypeDef",
+    "NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterConstraintsTypeDef",
     "ProductViewAggregationValueTypeDef",
     "ProvisioningParameterTypeDef",
     "ProvisioningPreferencesTypeDef",
     "RecordErrorTypeDef",
     "RecordTagTypeDef",
     "RejectPortfolioShareInputRequestTypeDef",
     "ResourceTargetDefinitionTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchProductsAsAdminInputRequestTypeDef",
+    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
     "SearchProductsInputRequestTypeDef",
     "ShareErrorTypeDef",
     "TerminateProvisionedProductInputRequestTypeDef",
     "UpdateConstraintInputRequestTypeDef",
+    "UpdatePortfolioShareOutputTypeDef",
     "UpdateProvisioningPreferencesTypeDef",
     "UpdateProvisionedProductPropertiesInputRequestTypeDef",
+    "UpdateProvisionedProductPropertiesOutputTypeDef",
     "UpdateProvisioningArtifactInputRequestTypeDef",
     "UpdateServiceActionInputRequestTypeDef",
     "UpdateTagOptionInputRequestTypeDef",
+    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
     "ListProvisionedProductPlansInputRequestTypeDef",
     "ScanProvisionedProductsInputRequestTypeDef",
+    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
     "SearchProvisionedProductsInputRequestTypeDef",
     "BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     "BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     "BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef",
     "BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef",
-    "CopyProductOutputTypeDef",
-    "CreatePortfolioShareOutputTypeDef",
-    "CreateProvisionedProductPlanOutputTypeDef",
-    "DeletePortfolioShareOutputTypeDef",
-    "DescribeCopyProductStatusOutputTypeDef",
-    "GetAWSOrganizationsAccessStatusOutputTypeDef",
-    "ListPortfolioAccessOutputTypeDef",
-    "UpdatePortfolioShareOutputTypeDef",
-    "UpdateProvisionedProductPropertiesOutputTypeDef",
     "ListBudgetsForResourceOutputTypeDef",
     "SourceConnectionParametersTypeDef",
     "CreateConstraintOutputTypeDef",
     "DescribeConstraintOutputTypeDef",
     "ListConstraintsForPortfolioOutputTypeDef",
     "UpdateConstraintOutputTypeDef",
     "CreatePortfolioInputRequestTypeDef",
@@ -203,15 +219,14 @@
     "UpdatePortfolioOutputTypeDef",
     "CreatePortfolioShareInputRequestTypeDef",
     "DeletePortfolioShareInputRequestTypeDef",
     "ListOrganizationPortfolioAccessOutputTypeDef",
     "UpdatePortfolioShareInputRequestTypeDef",
     "CreateProvisioningArtifactInputRequestTypeDef",
     "CreateProvisioningArtifactOutputTypeDef",
-    "DescribeProvisioningArtifactOutputTypeDef",
     "ListProvisioningArtifactsOutputTypeDef",
     "UpdateProvisioningArtifactOutputTypeDef",
     "CreateProvisionedProductPlanInputRequestTypeDef",
     "ProvisionedProductPlanDetailsTypeDef",
     "CreateTagOptionOutputTypeDef",
     "DescribePortfolioOutputTypeDef",
     "DescribeTagOptionOutputTypeDef",
@@ -220,29 +235,17 @@
     "DescribePortfolioSharesOutputTypeDef",
     "DescribeProductOutputTypeDef",
     "DescribeProductViewOutputTypeDef",
     "ProvisioningArtifactViewTypeDef",
     "DescribeProvisionedProductOutputTypeDef",
     "ScanProvisionedProductsOutputTypeDef",
     "GetProvisionedProductOutputsOutputTypeDef",
+    "NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     "DescribeServiceActionExecutionParametersOutputTypeDef",
-    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
-    "ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    "ListLaunchPathsInputListLaunchPathsPaginateTypeDef",
-    "ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    "ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
-    "ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
-    "ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    "ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
-    "ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
-    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
-    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
-    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+    "EngineWorkflowResourceIdentifierTypeDef",
     "ListPrincipalsForPortfolioOutputTypeDef",
     "ListProvisionedProductPlansOutputTypeDef",
     "ListRecordHistoryInputListRecordHistoryPaginateTypeDef",
     "ListRecordHistoryInputRequestTypeDef",
     "ListResourcesForTagOptionOutputTypeDef",
     "ListServiceActionsForProvisioningArtifactOutputTypeDef",
     "ListServiceActionsOutputTypeDef",
@@ -258,17 +261,19 @@
     "ShareDetailsTypeDef",
     "UpdateProvisionedProductInputRequestTypeDef",
     "SourceConnectionDetailTypeDef",
     "SourceConnectionTypeDef",
     "ListLaunchPathsOutputTypeDef",
     "SearchProvisionedProductsOutputTypeDef",
     "ListProvisioningArtifactsForServiceActionOutputTypeDef",
+    "NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
     "CreateServiceActionOutputTypeDef",
     "DescribeServiceActionOutputTypeDef",
     "UpdateServiceActionOutputTypeDef",
+    "DescribeProvisioningArtifactOutputTypeDef",
     "DescribeProvisioningParametersOutputTypeDef",
     "DescribeRecordOutputTypeDef",
     "ExecuteProvisionedProductPlanOutputTypeDef",
     "ExecuteProvisionedProductServiceActionOutputTypeDef",
     "ImportAsProvisionedProductOutputTypeDef",
     "ListRecordHistoryOutputTypeDef",
     "ProvisionProductOutputTypeDef",
@@ -297,22 +302,20 @@
     {
         "AcceptLanguage": str,
         "PortfolioShareType": PortfolioShareTypeType,
     },
     total=False,
 )
 
-
 class AcceptPortfolioShareInputRequestTypeDef(
     _RequiredAcceptPortfolioShareInputRequestTypeDef,
     _OptionalAcceptPortfolioShareInputRequestTypeDef,
 ):
     pass
 
-
 AccessLevelFilterTypeDef = TypedDict(
     "AccessLevelFilterTypeDef",
     {
         "Key": AccessLevelFilterKeyType,
         "Value": str,
     },
     total=False,
@@ -338,22 +341,20 @@
     "_OptionalAssociatePrincipalWithPortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class AssociatePrincipalWithPortfolioInputRequestTypeDef(
     _RequiredAssociatePrincipalWithPortfolioInputRequestTypeDef,
     _OptionalAssociatePrincipalWithPortfolioInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredAssociateProductWithPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredAssociateProductWithPortfolioInputRequestTypeDef",
     {
         "ProductId": str,
         "PortfolioId": str,
     },
 )
@@ -362,22 +363,20 @@
     {
         "AcceptLanguage": str,
         "SourcePortfolioId": str,
     },
     total=False,
 )
 
-
 class AssociateProductWithPortfolioInputRequestTypeDef(
     _RequiredAssociateProductWithPortfolioInputRequestTypeDef,
     _OptionalAssociateProductWithPortfolioInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
         "ServiceActionId": str,
     },
@@ -386,22 +385,20 @@
     "_OptionalAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef(
     _RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     _OptionalAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 AssociateTagOptionWithResourceInputRequestTypeDef = TypedDict(
     "AssociateTagOptionWithResourceInputRequestTypeDef",
     {
         "ResourceId": str,
         "TagOptionId": str,
     },
 )
@@ -423,25 +420,14 @@
         "ProvisioningArtifactId": str,
         "ErrorCode": ServiceActionAssociationErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
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
 BudgetDetailTypeDef = TypedDict(
     "BudgetDetailTypeDef",
     {
         "BudgetName": str,
     },
     total=False,
 )
@@ -501,20 +487,26 @@
         "TargetProductName": str,
         "SourceProvisioningArtifactIdentifiers": Sequence[Mapping[Literal["Id"], str]],
         "CopyOptions": Sequence[Literal["CopyTags"]],
     },
     total=False,
 )
 
-
 class CopyProductInputRequestTypeDef(
     _RequiredCopyProductInputRequestTypeDef, _OptionalCopyProductInputRequestTypeDef
 ):
     pass
 
+CopyProductOutputTypeDef = TypedDict(
+    "CopyProductOutputTypeDef",
+    {
+        "CopyProductToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateConstraintInputRequestTypeDef = TypedDict(
     "_RequiredCreateConstraintInputRequestTypeDef",
     {
         "PortfolioId": str,
         "ProductId": str,
         "Parameters": str,
@@ -527,21 +519,19 @@
     {
         "AcceptLanguage": str,
         "Description": str,
     },
     total=False,
 )
 
-
 class CreateConstraintInputRequestTypeDef(
     _RequiredCreateConstraintInputRequestTypeDef, _OptionalCreateConstraintInputRequestTypeDef
 ):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -564,14 +554,22 @@
     {
         "Type": OrganizationNodeTypeType,
         "Value": str,
     },
     total=False,
 )
 
+CreatePortfolioShareOutputTypeDef = TypedDict(
+    "CreatePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ProvisioningArtifactPropertiesTypeDef = TypedDict(
     "ProvisioningArtifactPropertiesTypeDef",
     {
         "Name": str,
         "Description": str,
         "Info": Mapping[str, str],
         "Type": ProvisioningArtifactTypeType,
@@ -601,14 +599,26 @@
         "Key": str,
         "Value": str,
         "UsePreviousValue": bool,
     },
     total=False,
 )
 
+CreateProvisionedProductPlanOutputTypeDef = TypedDict(
+    "CreateProvisionedProductPlanOutputTypeDef",
+    {
+        "PlanName": str,
+        "PlanId": str,
+        "ProvisionProductId": str,
+        "ProvisionedProductName": str,
+        "ProvisioningArtifactId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredCreateServiceActionInputRequestTypeDef",
     {
         "Name": str,
         "DefinitionType": Literal["SSM_AUTOMATION"],
         "Definition": Mapping[ServiceActionDefinitionKeyType, str],
         "IdempotencyToken": str,
@@ -619,21 +629,19 @@
     {
         "Description": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class CreateServiceActionInputRequestTypeDef(
     _RequiredCreateServiceActionInputRequestTypeDef, _OptionalCreateServiceActionInputRequestTypeDef
 ):
     pass
 
-
 CreateTagOptionInputRequestTypeDef = TypedDict(
     "CreateTagOptionInputRequestTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -660,41 +668,45 @@
     "_OptionalDeleteConstraintInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DeleteConstraintInputRequestTypeDef(
     _RequiredDeleteConstraintInputRequestTypeDef, _OptionalDeleteConstraintInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDeletePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDeletePortfolioInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDeletePortfolioInputRequestTypeDef = TypedDict(
     "_OptionalDeletePortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DeletePortfolioInputRequestTypeDef(
     _RequiredDeletePortfolioInputRequestTypeDef, _OptionalDeletePortfolioInputRequestTypeDef
 ):
     pass
 
+DeletePortfolioShareOutputTypeDef = TypedDict(
+    "DeletePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDeleteProductInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProductInputRequestTypeDef",
     {
         "Id": str,
     },
 )
@@ -702,21 +714,19 @@
     "_OptionalDeleteProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DeleteProductInputRequestTypeDef(
     _RequiredDeleteProductInputRequestTypeDef, _OptionalDeleteProductInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDeleteProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanId": str,
     },
 )
 _OptionalDeleteProvisionedProductPlanInputRequestTypeDef = TypedDict(
@@ -724,22 +734,20 @@
     {
         "AcceptLanguage": str,
         "IgnoreErrors": bool,
     },
     total=False,
 )
 
-
 class DeleteProvisionedProductPlanInputRequestTypeDef(
     _RequiredDeleteProvisionedProductPlanInputRequestTypeDef,
     _OptionalDeleteProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeleteProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
 )
@@ -747,43 +755,39 @@
     "_OptionalDeleteProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DeleteProvisioningArtifactInputRequestTypeDef(
     _RequiredDeleteProvisioningArtifactInputRequestTypeDef,
     _OptionalDeleteProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeleteServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredDeleteServiceActionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDeleteServiceActionInputRequestTypeDef = TypedDict(
     "_OptionalDeleteServiceActionInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DeleteServiceActionInputRequestTypeDef(
     _RequiredDeleteServiceActionInputRequestTypeDef, _OptionalDeleteServiceActionInputRequestTypeDef
 ):
     pass
 
-
 DeleteTagOptionInputRequestTypeDef = TypedDict(
     "DeleteTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -797,42 +801,48 @@
     "_OptionalDescribeConstraintInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribeConstraintInputRequestTypeDef(
     _RequiredDescribeConstraintInputRequestTypeDef, _OptionalDescribeConstraintInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDescribeCopyProductStatusInputRequestTypeDef = TypedDict(
     "_RequiredDescribeCopyProductStatusInputRequestTypeDef",
     {
         "CopyProductToken": str,
     },
 )
 _OptionalDescribeCopyProductStatusInputRequestTypeDef = TypedDict(
     "_OptionalDescribeCopyProductStatusInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribeCopyProductStatusInputRequestTypeDef(
     _RequiredDescribeCopyProductStatusInputRequestTypeDef,
     _OptionalDescribeCopyProductStatusInputRequestTypeDef,
 ):
     pass
 
+DescribeCopyProductStatusOutputTypeDef = TypedDict(
+    "DescribeCopyProductStatusOutputTypeDef",
+    {
+        "CopyProductStatus": CopyProductStatusType,
+        "TargetProductId": str,
+        "StatusDetail": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDescribePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDescribePortfolioInputRequestTypeDef",
     {
         "Id": str,
     },
 )
@@ -840,21 +850,19 @@
     "_OptionalDescribePortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribePortfolioInputRequestTypeDef(
     _RequiredDescribePortfolioInputRequestTypeDef, _OptionalDescribePortfolioInputRequestTypeDef
 ):
     pass
 
-
 DescribePortfolioShareStatusInputRequestTypeDef = TypedDict(
     "DescribePortfolioShareStatusInputRequestTypeDef",
     {
         "PortfolioShareToken": str,
     },
 )
 
@@ -870,22 +878,20 @@
     {
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class DescribePortfolioSharesInputRequestTypeDef(
     _RequiredDescribePortfolioSharesInputRequestTypeDef,
     _OptionalDescribePortfolioSharesInputRequestTypeDef,
 ):
     pass
 
-
 PortfolioShareDetailTypeDef = TypedDict(
     "PortfolioShareDetailTypeDef",
     {
         "PrincipalId": str,
         "Type": DescribePortfolioShareTypeType,
         "Accepted": bool,
         "ShareTagOptions": bool,
@@ -976,21 +982,19 @@
     "_OptionalDescribeProductViewInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribeProductViewInputRequestTypeDef(
     _RequiredDescribeProductViewInputRequestTypeDef, _OptionalDescribeProductViewInputRequestTypeDef
 ):
     pass
 
-
 DescribeProvisionedProductInputRequestTypeDef = TypedDict(
     "DescribeProvisionedProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "Id": str,
         "Name": str,
     },
@@ -1030,31 +1034,30 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class DescribeProvisionedProductPlanInputRequestTypeDef(
     _RequiredDescribeProvisionedProductPlanInputRequestTypeDef,
     _OptionalDescribeProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
-
 DescribeProvisioningArtifactInputRequestTypeDef = TypedDict(
     "DescribeProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisioningArtifactId": str,
         "ProductId": str,
         "ProvisioningArtifactName": str,
         "ProductName": str,
         "Verbose": bool,
+        "IncludeProvisioningArtifactParameters": bool,
     },
     total=False,
 )
 
 DescribeProvisioningParametersInputRequestTypeDef = TypedDict(
     "DescribeProvisioningParametersInputRequestTypeDef",
     {
@@ -1117,21 +1120,19 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class DescribeRecordInputRequestTypeDef(
     _RequiredDescribeRecordInputRequestTypeDef, _OptionalDescribeRecordInputRequestTypeDef
 ):
     pass
 
-
 RecordOutputTypeDef = TypedDict(
     "RecordOutputTypeDef",
     {
         "OutputKey": str,
         "OutputValue": str,
         "Description": str,
     },
@@ -1149,22 +1150,20 @@
     "_OptionalDescribeServiceActionExecutionParametersInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribeServiceActionExecutionParametersInputRequestTypeDef(
     _RequiredDescribeServiceActionExecutionParametersInputRequestTypeDef,
     _OptionalDescribeServiceActionExecutionParametersInputRequestTypeDef,
 ):
     pass
 
-
 ExecutionParameterTypeDef = TypedDict(
     "ExecutionParameterTypeDef",
     {
         "Name": str,
         "Type": str,
         "DefaultValues": List[str],
     },
@@ -1181,22 +1180,20 @@
     "_OptionalDescribeServiceActionInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DescribeServiceActionInputRequestTypeDef(
     _RequiredDescribeServiceActionInputRequestTypeDef,
     _OptionalDescribeServiceActionInputRequestTypeDef,
 ):
     pass
 
-
 DescribeTagOptionInputRequestTypeDef = TypedDict(
     "DescribeTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1220,22 +1217,20 @@
     {
         "AcceptLanguage": str,
         "PrincipalType": PrincipalTypeType,
     },
     total=False,
 )
 
-
 class DisassociatePrincipalFromPortfolioInputRequestTypeDef(
     _RequiredDisassociatePrincipalFromPortfolioInputRequestTypeDef,
     _OptionalDisassociatePrincipalFromPortfolioInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDisassociateProductFromPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDisassociateProductFromPortfolioInputRequestTypeDef",
     {
         "ProductId": str,
         "PortfolioId": str,
     },
 )
@@ -1243,22 +1238,20 @@
     "_OptionalDisassociateProductFromPortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DisassociateProductFromPortfolioInputRequestTypeDef(
     _RequiredDisassociateProductFromPortfolioInputRequestTypeDef,
     _OptionalDisassociateProductFromPortfolioInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
         "ServiceActionId": str,
     },
@@ -1267,30 +1260,37 @@
     "_OptionalDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef(
     _RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     _OptionalDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 DisassociateTagOptionFromResourceInputRequestTypeDef = TypedDict(
     "DisassociateTagOptionFromResourceInputRequestTypeDef",
     {
         "ResourceId": str,
         "TagOptionId": str,
     },
 )
 
+UniqueTagResourceIdentifierTypeDef = TypedDict(
+    "UniqueTagResourceIdentifierTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+    },
+    total=False,
+)
+
 _RequiredExecuteProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredExecuteProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanId": str,
         "IdempotencyToken": str,
     },
 )
@@ -1298,22 +1298,20 @@
     "_OptionalExecuteProvisionedProductPlanInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class ExecuteProvisionedProductPlanInputRequestTypeDef(
     _RequiredExecuteProvisionedProductPlanInputRequestTypeDef,
     _OptionalExecuteProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef",
     {
         "ProvisionedProductId": str,
         "ServiceActionId": str,
         "ExecuteToken": str,
     },
@@ -1323,21 +1321,27 @@
     {
         "AcceptLanguage": str,
         "Parameters": Mapping[str, Sequence[str]],
     },
     total=False,
 )
 
-
 class ExecuteProvisionedProductServiceActionInputRequestTypeDef(
     _RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef,
     _OptionalExecuteProvisionedProductServiceActionInputRequestTypeDef,
 ):
     pass
 
+GetAWSOrganizationsAccessStatusOutputTypeDef = TypedDict(
+    "GetAWSOrganizationsAccessStatusOutputTypeDef",
+    {
+        "AccessStatus": AccessStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 GetProvisionedProductOutputsInputRequestTypeDef = TypedDict(
     "GetProvisionedProductOutputsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisionedProductId": str,
         "ProvisionedProductName": str,
@@ -1362,40 +1366,38 @@
     "_OptionalImportAsProvisionedProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class ImportAsProvisionedProductInputRequestTypeDef(
     _RequiredImportAsProvisionedProductInputRequestTypeDef,
     _OptionalImportAsProvisionedProductInputRequestTypeDef,
 ):
     pass
 
-
 LastSyncTypeDef = TypedDict(
     "LastSyncTypeDef",
     {
         "LastSyncTime": datetime,
         "LastSyncStatus": LastSyncStatusType,
         "LastSyncStatusMessage": str,
         "LastSuccessfulSyncTime": datetime,
         "LastSuccessfulSyncProvisioningArtifactId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef = TypedDict(
+    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AcceptLanguage": str,
+        "PortfolioShareType": PortfolioShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAcceptedPortfolioSharesInputRequestTypeDef = TypedDict(
     "ListAcceptedPortfolioSharesInputRequestTypeDef",
     {
@@ -1419,21 +1421,41 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class ListBudgetsForResourceInputRequestTypeDef(
     _RequiredListBudgetsForResourceInputRequestTypeDef,
     _OptionalListBudgetsForResourceInputRequestTypeDef,
 ):
     pass
 
+_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
+    "_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
+    {
+        "PortfolioId": str,
+    },
+)
+_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
+    "_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "ProductId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef(
+    _RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
+    _OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
+):
+    pass
 
 _RequiredListConstraintsForPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredListConstraintsForPortfolioInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
@@ -1444,21 +1466,40 @@
         "ProductId": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class ListConstraintsForPortfolioInputRequestTypeDef(
     _RequiredListConstraintsForPortfolioInputRequestTypeDef,
     _OptionalListConstraintsForPortfolioInputRequestTypeDef,
 ):
     pass
 
+_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef",
+    {
+        "ProductId": str,
+    },
+)
+_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLaunchPathsInputListLaunchPathsPaginateTypeDef(
+    _RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef,
+    _OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef,
+):
+    pass
 
 _RequiredListLaunchPathsInputRequestTypeDef = TypedDict(
     "_RequiredListLaunchPathsInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
@@ -1468,20 +1509,40 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class ListLaunchPathsInputRequestTypeDef(
     _RequiredListLaunchPathsInputRequestTypeDef, _OptionalListLaunchPathsInputRequestTypeDef
 ):
     pass
 
+_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
+    "_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
+    {
+        "PortfolioId": str,
+        "OrganizationNodeType": OrganizationNodeTypeType,
+    },
+)
+_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
+    "_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef(
+    _RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
+    _OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
+):
+    pass
 
 _RequiredListOrganizationPortfolioAccessInputRequestTypeDef = TypedDict(
     "_RequiredListOrganizationPortfolioAccessInputRequestTypeDef",
     {
         "PortfolioId": str,
         "OrganizationNodeType": OrganizationNodeTypeType,
     },
@@ -1492,22 +1553,20 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class ListOrganizationPortfolioAccessInputRequestTypeDef(
     _RequiredListOrganizationPortfolioAccessInputRequestTypeDef,
     _OptionalListOrganizationPortfolioAccessInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredListPortfolioAccessInputRequestTypeDef = TypedDict(
     "_RequiredListPortfolioAccessInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalListPortfolioAccessInputRequestTypeDef = TypedDict(
@@ -1517,20 +1576,48 @@
         "OrganizationParentId": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class ListPortfolioAccessInputRequestTypeDef(
     _RequiredListPortfolioAccessInputRequestTypeDef, _OptionalListPortfolioAccessInputRequestTypeDef
 ):
     pass
 
+ListPortfolioAccessOutputTypeDef = TypedDict(
+    "ListPortfolioAccessOutputTypeDef",
+    {
+        "AccountIds": List[str],
+        "NextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
+    "_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
+    {
+        "ProductId": str,
+    },
+)
+_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
+    "_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef(
+    _RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
+    _OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
+):
+    pass
 
 _RequiredListPortfoliosForProductInputRequestTypeDef = TypedDict(
     "_RequiredListPortfoliosForProductInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
@@ -1540,32 +1627,60 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class ListPortfoliosForProductInputRequestTypeDef(
     _RequiredListPortfoliosForProductInputRequestTypeDef,
     _OptionalListPortfoliosForProductInputRequestTypeDef,
 ):
     pass
 
+ListPortfoliosInputListPortfoliosPaginateTypeDef = TypedDict(
+    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListPortfoliosInputRequestTypeDef = TypedDict(
     "ListPortfoliosInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
+    {
+        "PortfolioId": str,
+    },
+)
+_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef(
+    _RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
+    _OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
+):
+    pass
+
 _RequiredListPrincipalsForPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredListPrincipalsForPortfolioInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalListPrincipalsForPortfolioInputRequestTypeDef = TypedDict(
@@ -1574,22 +1689,20 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class ListPrincipalsForPortfolioInputRequestTypeDef(
     _RequiredListPrincipalsForPortfolioInputRequestTypeDef,
     _OptionalListPrincipalsForPortfolioInputRequestTypeDef,
 ):
     pass
 
-
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "PrincipalARN": str,
         "PrincipalType": PrincipalTypeType,
     },
     total=False,
@@ -1604,14 +1717,35 @@
         "ProvisionProductName": str,
         "PlanType": Literal["CLOUDFORMATION"],
         "ProvisioningArtifactId": str,
     },
     total=False,
 )
 
+_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
+    "_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
+    {
+        "ServiceActionId": str,
+    },
+)
+_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
+    "_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef(
+    _RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
+    _OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
+):
+    pass
+
 _RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef",
     {
         "ServiceActionId": str,
     },
 )
 _OptionalListProvisioningArtifactsForServiceActionInputRequestTypeDef = TypedDict(
@@ -1620,53 +1754,70 @@
         "PageSize": int,
         "PageToken": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class ListProvisioningArtifactsForServiceActionInputRequestTypeDef(
     _RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef,
     _OptionalListProvisioningArtifactsForServiceActionInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredListProvisioningArtifactsInputRequestTypeDef = TypedDict(
     "_RequiredListProvisioningArtifactsInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
 _OptionalListProvisioningArtifactsInputRequestTypeDef = TypedDict(
     "_OptionalListProvisioningArtifactsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class ListProvisioningArtifactsInputRequestTypeDef(
     _RequiredListProvisioningArtifactsInputRequestTypeDef,
     _OptionalListProvisioningArtifactsInputRequestTypeDef,
 ):
     pass
 
-
 ListRecordHistorySearchFilterTypeDef = TypedDict(
     "ListRecordHistorySearchFilterTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+    {
+        "TagOptionId": str,
+    },
+)
+_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef(
+    _RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
+    _OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourcesForTagOptionInputRequestTypeDef = TypedDict(
     "_RequiredListResourcesForTagOptionInputRequestTypeDef",
     {
         "TagOptionId": str,
     },
 )
 _OptionalListResourcesForTagOptionInputRequestTypeDef = TypedDict(
@@ -1675,34 +1826,54 @@
         "ResourceType": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
-
 class ListResourcesForTagOptionInputRequestTypeDef(
     _RequiredListResourcesForTagOptionInputRequestTypeDef,
     _OptionalListResourcesForTagOptionInputRequestTypeDef,
 ):
     pass
 
-
 ResourceDetailTypeDef = TypedDict(
     "ResourceDetailTypeDef",
     {
         "Id": str,
         "ARN": str,
         "Name": str,
         "Description": str,
         "CreatedTime": datetime,
     },
     total=False,
 )
 
+_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
+    "_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
+    {
+        "ProductId": str,
+        "ProvisioningArtifactId": str,
+    },
+)
+_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
+    "_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef(
+    _RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+    _OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+):
+    pass
+
 _RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
 )
@@ -1712,33 +1883,40 @@
         "PageSize": int,
         "PageToken": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class ListServiceActionsForProvisioningArtifactInputRequestTypeDef(
     _RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef,
     _OptionalListServiceActionsForProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 ServiceActionSummaryTypeDef = TypedDict(
     "ServiceActionSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "DefinitionType": Literal["SSM_AUTOMATION"],
     },
     total=False,
 )
 
+ListServiceActionsInputListServiceActionsPaginateTypeDef = TypedDict(
+    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceActionsInputRequestTypeDef = TypedDict(
     "ListServiceActionsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
@@ -1757,22 +1935,20 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
-
 class ListStackInstancesForProvisionedProductInputRequestTypeDef(
     _RequiredListStackInstancesForProvisionedProductInputRequestTypeDef,
     _OptionalListStackInstancesForProvisionedProductInputRequestTypeDef,
 ):
     pass
 
-
 StackInstanceTypeDef = TypedDict(
     "StackInstanceTypeDef",
     {
         "Account": str,
         "Region": str,
         "StackInstanceStatus": StackInstanceStatusType,
     },
@@ -1785,14 +1961,47 @@
         "Key": str,
         "Value": str,
         "Active": bool,
     },
     total=False,
 )
 
+_RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
+    },
+)
+_OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "FailureReason": str,
+    },
+    total=False,
+)
+
+class NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+):
+    pass
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
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "AllowedValues": List[str],
         "AllowedPattern": str,
         "ConstraintDescription": str,
         "MaxLength": str,
@@ -1863,32 +2072,41 @@
     {
         "AcceptLanguage": str,
         "PortfolioShareType": PortfolioShareTypeType,
     },
     total=False,
 )
 
-
 class RejectPortfolioShareInputRequestTypeDef(
     _RequiredRejectPortfolioShareInputRequestTypeDef,
     _OptionalRejectPortfolioShareInputRequestTypeDef,
 ):
     pass
 
-
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
 SearchProductsAsAdminInputRequestTypeDef = TypedDict(
     "SearchProductsAsAdminInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PortfolioId": str,
         "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
         "SortBy": ProductViewSortByType,
@@ -1896,14 +2114,28 @@
         "PageToken": str,
         "PageSize": int,
         "ProductSource": Literal["ACCOUNT"],
     },
     total=False,
 )
 
+SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef = TypedDict(
+    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PortfolioId": str,
+        "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
+        "SortBy": ProductViewSortByType,
+        "SortOrder": SortOrderType,
+        "ProductSource": Literal["ACCOUNT"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 SearchProductsInputRequestTypeDef = TypedDict(
     "SearchProductsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
         "PageSize": int,
         "SortBy": ProductViewSortByType,
@@ -1937,22 +2169,20 @@
         "IgnoreErrors": bool,
         "AcceptLanguage": str,
         "RetainPhysicalResources": bool,
     },
     total=False,
 )
 
-
 class TerminateProvisionedProductInputRequestTypeDef(
     _RequiredTerminateProvisionedProductInputRequestTypeDef,
     _OptionalTerminateProvisionedProductInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateConstraintInputRequestTypeDef = TypedDict(
     "_RequiredUpdateConstraintInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateConstraintInputRequestTypeDef = TypedDict(
@@ -1961,20 +2191,27 @@
         "AcceptLanguage": str,
         "Description": str,
         "Parameters": str,
     },
     total=False,
 )
 
-
 class UpdateConstraintInputRequestTypeDef(
     _RequiredUpdateConstraintInputRequestTypeDef, _OptionalUpdateConstraintInputRequestTypeDef
 ):
     pass
 
+UpdatePortfolioShareOutputTypeDef = TypedDict(
+    "UpdatePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "Status": ShareStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 UpdateProvisioningPreferencesTypeDef = TypedDict(
     "UpdateProvisioningPreferencesTypeDef",
     {
         "StackSetAccounts": Sequence[str],
         "StackSetRegions": Sequence[str],
         "StackSetFailureToleranceCount": int,
@@ -1998,21 +2235,30 @@
     "_OptionalUpdateProvisionedProductPropertiesInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class UpdateProvisionedProductPropertiesInputRequestTypeDef(
     _RequiredUpdateProvisionedProductPropertiesInputRequestTypeDef,
     _OptionalUpdateProvisionedProductPropertiesInputRequestTypeDef,
 ):
     pass
 
+UpdateProvisionedProductPropertiesOutputTypeDef = TypedDict(
+    "UpdateProvisionedProductPropertiesOutputTypeDef",
+    {
+        "ProvisionedProductId": str,
+        "ProvisionedProductProperties": Dict[PropertyKeyType, str],
+        "RecordId": str,
+        "Status": RecordStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
@@ -2025,22 +2271,20 @@
         "Description": str,
         "Active": bool,
         "Guidance": ProvisioningArtifactGuidanceType,
     },
     total=False,
 )
 
-
 class UpdateProvisioningArtifactInputRequestTypeDef(
     _RequiredUpdateProvisioningArtifactInputRequestTypeDef,
     _OptionalUpdateProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceActionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateServiceActionInputRequestTypeDef = TypedDict(
@@ -2050,21 +2294,19 @@
         "Definition": Mapping[ServiceActionDefinitionKeyType, str],
         "Description": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class UpdateServiceActionInputRequestTypeDef(
     _RequiredUpdateServiceActionInputRequestTypeDef, _OptionalUpdateServiceActionInputRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateTagOptionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateTagOptionInputRequestTypeDef = TypedDict(
@@ -2072,20 +2314,29 @@
     {
         "Value": str,
         "Active": bool,
     },
     total=False,
 )
 
-
 class UpdateTagOptionInputRequestTypeDef(
     _RequiredUpdateTagOptionInputRequestTypeDef, _OptionalUpdateTagOptionInputRequestTypeDef
 ):
     pass
 
+ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef = TypedDict(
+    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "ProvisionProductId": str,
+        "AccessLevelFilter": AccessLevelFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListProvisionedProductPlansInputRequestTypeDef = TypedDict(
     "ListProvisionedProductPlansInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisionProductId": str,
         "PageSize": int,
@@ -2102,14 +2353,24 @@
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef = TypedDict(
+    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "AccessLevelFilter": AccessLevelFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 SearchProvisionedProductsInputRequestTypeDef = TypedDict(
     "SearchProvisionedProductsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "Filters": Mapping[Literal["SearchQuery"], Sequence[str]],
         "SortBy": str,
@@ -2130,149 +2391,62 @@
     "_OptionalBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef(
     _RequiredBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     _OptionalBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "ServiceActionAssociations": Sequence[ServiceActionAssociationTypeDef],
     },
 )
 _OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef(
     _RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     _OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef = TypedDict(
     "BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef",
     {
         "FailedServiceActionAssociations": List[FailedServiceActionAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef = TypedDict(
     "BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef",
     {
         "FailedServiceActionAssociations": List[FailedServiceActionAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CopyProductOutputTypeDef = TypedDict(
-    "CopyProductOutputTypeDef",
-    {
-        "CopyProductToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePortfolioShareOutputTypeDef = TypedDict(
-    "CreatePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProvisionedProductPlanOutputTypeDef = TypedDict(
-    "CreateProvisionedProductPlanOutputTypeDef",
-    {
-        "PlanName": str,
-        "PlanId": str,
-        "ProvisionProductId": str,
-        "ProvisionedProductName": str,
-        "ProvisioningArtifactId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePortfolioShareOutputTypeDef = TypedDict(
-    "DeletePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCopyProductStatusOutputTypeDef = TypedDict(
-    "DescribeCopyProductStatusOutputTypeDef",
-    {
-        "CopyProductStatus": CopyProductStatusType,
-        "TargetProductId": str,
-        "StatusDetail": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAWSOrganizationsAccessStatusOutputTypeDef = TypedDict(
-    "GetAWSOrganizationsAccessStatusOutputTypeDef",
-    {
-        "AccessStatus": AccessStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPortfolioAccessOutputTypeDef = TypedDict(
-    "ListPortfolioAccessOutputTypeDef",
-    {
-        "AccountIds": List[str],
-        "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePortfolioShareOutputTypeDef = TypedDict(
-    "UpdatePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "Status": ShareStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProvisionedProductPropertiesOutputTypeDef = TypedDict(
-    "UpdateProvisionedProductPropertiesOutputTypeDef",
-    {
-        "ProvisionedProductId": str,
-        "ProvisionedProductProperties": Dict[PropertyKeyType, str],
-        "RecordId": str,
-        "Status": RecordStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBudgetsForResourceOutputTypeDef = TypedDict(
     "ListBudgetsForResourceOutputTypeDef",
     {
         "Budgets": List[BudgetDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceConnectionParametersTypeDef = TypedDict(
     "SourceConnectionParametersTypeDef",
     {
         "CodeStar": CodeStarParametersTypeDef,
@@ -2282,44 +2456,44 @@
 
 CreateConstraintOutputTypeDef = TypedDict(
     "CreateConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConstraintOutputTypeDef = TypedDict(
     "DescribeConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConstraintsForPortfolioOutputTypeDef = TypedDict(
     "ListConstraintsForPortfolioOutputTypeDef",
     {
         "ConstraintDetails": List[ConstraintDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConstraintOutputTypeDef = TypedDict(
     "UpdateConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredCreatePortfolioInputRequestTypeDef",
     {
         "DisplayName": str,
@@ -2333,21 +2507,19 @@
         "AcceptLanguage": str,
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreatePortfolioInputRequestTypeDef(
     _RequiredCreatePortfolioInputRequestTypeDef, _OptionalCreatePortfolioInputRequestTypeDef
 ):
     pass
 
-
 LaunchPathSummaryTypeDef = TypedDict(
     "LaunchPathSummaryTypeDef",
     {
         "Id": str,
         "ConstraintSummaries": List[ConstraintSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "Name": str,
@@ -2396,63 +2568,61 @@
         "ProviderName": str,
         "AddTags": Sequence[TagTypeDef],
         "RemoveTags": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdatePortfolioInputRequestTypeDef(
     _RequiredUpdatePortfolioInputRequestTypeDef, _OptionalUpdatePortfolioInputRequestTypeDef
 ):
     pass
 
-
 CreatePortfolioOutputTypeDef = TypedDict(
     "CreatePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAcceptedPortfolioSharesOutputTypeDef = TypedDict(
     "ListAcceptedPortfolioSharesOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortfoliosForProductOutputTypeDef = TypedDict(
     "ListPortfoliosForProductOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortfoliosOutputTypeDef = TypedDict(
     "ListPortfoliosOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePortfolioOutputTypeDef = TypedDict(
     "UpdatePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredCreatePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
@@ -2466,22 +2636,20 @@
         "OrganizationNode": OrganizationNodeTypeDef,
         "ShareTagOptions": bool,
         "SharePrincipals": bool,
     },
     total=False,
 )
 
-
 class CreatePortfolioShareInputRequestTypeDef(
     _RequiredCreatePortfolioShareInputRequestTypeDef,
     _OptionalCreatePortfolioShareInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeletePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredDeletePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalDeletePortfolioShareInputRequestTypeDef = TypedDict(
@@ -2490,28 +2658,26 @@
         "AcceptLanguage": str,
         "AccountId": str,
         "OrganizationNode": OrganizationNodeTypeDef,
     },
     total=False,
 )
 
-
 class DeletePortfolioShareInputRequestTypeDef(
     _RequiredDeletePortfolioShareInputRequestTypeDef,
     _OptionalDeletePortfolioShareInputRequestTypeDef,
 ):
     pass
 
-
 ListOrganizationPortfolioAccessOutputTypeDef = TypedDict(
     "ListOrganizationPortfolioAccessOutputTypeDef",
     {
         "OrganizationNodes": List[OrganizationNodeTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredUpdatePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
@@ -2525,22 +2691,20 @@
         "OrganizationNode": OrganizationNodeTypeDef,
         "ShareTagOptions": bool,
         "SharePrincipals": bool,
     },
     total=False,
 )
 
-
 class UpdatePortfolioShareInputRequestTypeDef(
     _RequiredUpdatePortfolioShareInputRequestTypeDef,
     _OptionalUpdatePortfolioShareInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "Parameters": ProvisioningArtifactPropertiesTypeDef,
         "IdempotencyToken": str,
     },
@@ -2549,58 +2713,46 @@
     "_OptionalCreateProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
-
 class CreateProvisioningArtifactInputRequestTypeDef(
     _RequiredCreateProvisioningArtifactInputRequestTypeDef,
     _OptionalCreateProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
-
 CreateProvisioningArtifactOutputTypeDef = TypedDict(
     "CreateProvisioningArtifactOutputTypeDef",
     {
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Info": Dict[str, str],
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProvisioningArtifactOutputTypeDef = TypedDict(
-    "DescribeProvisioningArtifactOutputTypeDef",
-    {
-        "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
-        "Info": Dict[str, str],
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningArtifactsOutputTypeDef = TypedDict(
     "ListProvisioningArtifactsOutputTypeDef",
     {
         "ProvisioningArtifactDetails": List[ProvisioningArtifactDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProvisioningArtifactOutputTypeDef = TypedDict(
     "UpdateProvisioningArtifactOutputTypeDef",
     {
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Info": Dict[str, str],
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanName": str,
@@ -2619,22 +2771,20 @@
         "PathId": str,
         "ProvisioningParameters": Sequence[UpdateProvisioningParameterTypeDef],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateProvisionedProductPlanInputRequestTypeDef(
     _RequiredCreateProvisionedProductPlanInputRequestTypeDef,
     _OptionalCreateProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
-
 ProvisionedProductPlanDetailsTypeDef = TypedDict(
     "ProvisionedProductPlanDetailsTypeDef",
     {
         "CreatedTime": datetime,
         "PathId": str,
         "ProductId": str,
         "PlanName": str,
@@ -2653,80 +2803,80 @@
     total=False,
 )
 
 CreateTagOptionOutputTypeDef = TypedDict(
     "CreateTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortfolioOutputTypeDef = TypedDict(
     "DescribePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
         "TagOptions": List[TagOptionDetailTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagOptionOutputTypeDef = TypedDict(
     "DescribeTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagOptionsOutputTypeDef = TypedDict(
     "ListTagOptionsOutputTypeDef",
     {
         "TagOptionDetails": List[TagOptionDetailTypeDef],
         "PageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTagOptionOutputTypeDef = TypedDict(
     "UpdateTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortfolioSharesOutputTypeDef = TypedDict(
     "DescribePortfolioSharesOutputTypeDef",
     {
         "NextPageToken": str,
         "PortfolioShareDetails": List[PortfolioShareDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductOutputTypeDef = TypedDict(
     "DescribeProductOutputTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
         "ProvisioningArtifacts": List[ProvisioningArtifactTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
         "LaunchPaths": List[LaunchPathTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductViewOutputTypeDef = TypedDict(
     "DescribeProductViewOutputTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
         "ProvisioningArtifacts": List[ProvisioningArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisioningArtifactViewTypeDef = TypedDict(
     "ProvisioningArtifactViewTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
@@ -2736,319 +2886,101 @@
 )
 
 DescribeProvisionedProductOutputTypeDef = TypedDict(
     "DescribeProvisionedProductOutputTypeDef",
     {
         "ProvisionedProductDetail": ProvisionedProductDetailTypeDef,
         "CloudWatchDashboards": List[CloudWatchDashboardTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanProvisionedProductsOutputTypeDef = TypedDict(
     "ScanProvisionedProductsOutputTypeDef",
     {
         "ProvisionedProducts": List[ProvisionedProductDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProvisionedProductOutputsOutputTypeDef = TypedDict(
     "GetProvisionedProductOutputsOutputTypeDef",
     {
         "Outputs": List[RecordOutputTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeServiceActionExecutionParametersOutputTypeDef = TypedDict(
-    "DescribeServiceActionExecutionParametersOutputTypeDef",
-    {
-        "ServiceActionParameters": List[ExecutionParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef = TypedDict(
-    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PortfolioShareType": PortfolioShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
-    "_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    {
-        "PortfolioId": str,
-    },
-)
-_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
-    "_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "ProductId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef(
-    _RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-    _OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef",
+_RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     {
-        "ProductId": str,
-    },
-)
-_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLaunchPathsInputListLaunchPathsPaginateTypeDef(
-    _RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-    _OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
-    "_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    {
-        "PortfolioId": str,
-        "OrganizationNodeType": OrganizationNodeTypeType,
-    },
-)
-_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
-    "_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef(
-    _RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-    _OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
-    "_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    {
-        "ProductId": str,
-    },
-)
-_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
-    "_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef(
-    _RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-    _OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-):
-    pass
-
-
-ListPortfoliosInputListPortfoliosPaginateTypeDef = TypedDict(
-    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    {
-        "PortfolioId": str,
-    },
-)
-_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef(
-    _RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-    _OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-):
-    pass
-
-
-ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef = TypedDict(
-    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "ProvisionProductId": str,
-        "AccessLevelFilter": AccessLevelFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
-    "_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    {
-        "ServiceActionId": str,
-    },
-)
-_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
-    "_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef(
-    _RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-    _OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
-    {
-        "TagOptionId": str,
-    },
-)
-_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
-    {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef(
-    _RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-    _OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
-    "_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
-    {
-        "ProductId": str,
-        "ProvisioningArtifactId": str,
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
     },
 )
-_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
-    "_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
+_OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FailureReason": str,
+        "Outputs": Sequence[RecordOutputTypeDef],
     },
     total=False,
 )
 
-
-class ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef(
-    _RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
-    _OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+class NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
 ):
     pass
 
-
-ListServiceActionsInputListServiceActionsPaginateTypeDef = TypedDict(
-    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef = TypedDict(
-    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
+DescribeServiceActionExecutionParametersOutputTypeDef = TypedDict(
+    "DescribeServiceActionExecutionParametersOutputTypeDef",
     {
-        "AcceptLanguage": str,
-        "AccessLevelFilter": AccessLevelFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ServiceActionParameters": List[ExecutionParameterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef = TypedDict(
-    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+EngineWorkflowResourceIdentifierTypeDef = TypedDict(
+    "EngineWorkflowResourceIdentifierTypeDef",
     {
-        "AcceptLanguage": str,
-        "PortfolioId": str,
-        "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
-        "SortBy": ProductViewSortByType,
-        "SortOrder": SortOrderType,
-        "ProductSource": Literal["ACCOUNT"],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "UniqueTag": UniqueTagResourceIdentifierTypeDef,
     },
     total=False,
 )
 
 ListPrincipalsForPortfolioOutputTypeDef = TypedDict(
     "ListPrincipalsForPortfolioOutputTypeDef",
     {
         "Principals": List[PrincipalTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisionedProductPlansOutputTypeDef = TypedDict(
     "ListProvisionedProductPlansOutputTypeDef",
     {
         "ProvisionedProductPlans": List[ProvisionedProductPlanSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordHistoryInputListRecordHistoryPaginateTypeDef = TypedDict(
     "ListRecordHistoryInputListRecordHistoryPaginateTypeDef",
     {
         "AcceptLanguage": str,
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "SearchFilter": ListRecordHistorySearchFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRecordHistoryInputRequestTypeDef = TypedDict(
     "ListRecordHistoryInputRequestTypeDef",
     {
@@ -3062,33 +2994,33 @@
 )
 
 ListResourcesForTagOptionOutputTypeDef = TypedDict(
     "ListResourcesForTagOptionOutputTypeDef",
     {
         "ResourceDetails": List[ResourceDetailTypeDef],
         "PageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceActionsForProvisioningArtifactOutputTypeDef = TypedDict(
     "ListServiceActionsForProvisioningArtifactOutputTypeDef",
     {
         "ServiceActionSummaries": List[ServiceActionSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceActionsOutputTypeDef = TypedDict(
     "ListServiceActionsOutputTypeDef",
     {
         "ServiceActionSummaries": List[ServiceActionSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceActionDetailTypeDef = TypedDict(
     "ServiceActionDetailTypeDef",
     {
         "ServiceActionSummary": ServiceActionSummaryTypeDef,
@@ -3098,23 +3030,23 @@
 )
 
 ListStackInstancesForProvisionedProductOutputTypeDef = TypedDict(
     "ListStackInstancesForProvisionedProductOutputTypeDef",
     {
         "StackInstances": List[StackInstanceTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagOptionsInputListTagOptionsPaginateTypeDef = TypedDict(
     "ListTagOptionsInputListTagOptionsPaginateTypeDef",
     {
         "Filters": ListTagOptionsFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTagOptionsInputRequestTypeDef = TypedDict(
     "ListTagOptionsInputRequestTypeDef",
     {
@@ -3140,15 +3072,15 @@
 
 SearchProductsOutputTypeDef = TypedDict(
     "SearchProductsOutputTypeDef",
     {
         "ProductViewSummaries": List[ProductViewSummaryTypeDef],
         "ProductViewAggregations": Dict[str, List[ProductViewAggregationValueTypeDef]],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredProvisionProductInputRequestTypeDef = TypedDict(
     "_RequiredProvisionProductInputRequestTypeDef",
     {
         "ProvisionedProductName": str,
@@ -3169,21 +3101,19 @@
         "ProvisioningPreferences": ProvisioningPreferencesTypeDef,
         "Tags": Sequence[TagTypeDef],
         "NotificationArns": Sequence[str],
     },
     total=False,
 )
 
-
 class ProvisionProductInputRequestTypeDef(
     _RequiredProvisionProductInputRequestTypeDef, _OptionalProvisionProductInputRequestTypeDef
 ):
     pass
 
-
 RecordDetailTypeDef = TypedDict(
     "RecordDetailTypeDef",
     {
         "RecordId": str,
         "ProvisionedProductName": str,
         "Status": RecordStatusType,
         "CreatedTime": datetime,
@@ -3241,22 +3171,20 @@
         "ProvisioningParameters": Sequence[UpdateProvisioningParameterTypeDef],
         "ProvisioningPreferences": UpdateProvisioningPreferencesTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class UpdateProvisionedProductInputRequestTypeDef(
     _RequiredUpdateProvisionedProductInputRequestTypeDef,
     _OptionalUpdateProvisionedProductInputRequestTypeDef,
 ):
     pass
 
-
 SourceConnectionDetailTypeDef = TypedDict(
     "SourceConnectionDetailTypeDef",
     {
         "Type": Literal["CODESTAR"],
         "ConnectionParameters": SourceConnectionParametersTypeDef,
         "LastSync": LastSyncTypeDef,
     },
@@ -3273,149 +3201,183 @@
     "_OptionalSourceConnectionTypeDef",
     {
         "Type": Literal["CODESTAR"],
     },
     total=False,
 )
 
-
 class SourceConnectionTypeDef(_RequiredSourceConnectionTypeDef, _OptionalSourceConnectionTypeDef):
     pass
 
-
 ListLaunchPathsOutputTypeDef = TypedDict(
     "ListLaunchPathsOutputTypeDef",
     {
         "LaunchPathSummaries": List[LaunchPathSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchProvisionedProductsOutputTypeDef = TypedDict(
     "SearchProvisionedProductsOutputTypeDef",
     {
         "ProvisionedProducts": List[ProvisionedProductAttributeTypeDef],
         "TotalResultsCount": int,
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningArtifactsForServiceActionOutputTypeDef = TypedDict(
     "ListProvisioningArtifactsForServiceActionOutputTypeDef",
     {
         "ProvisioningArtifactViews": List[ProvisioningArtifactViewTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
+    },
+)
+_OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "FailureReason": str,
+        "ResourceIdentifier": EngineWorkflowResourceIdentifierTypeDef,
+        "Outputs": Sequence[RecordOutputTypeDef],
+    },
+    total=False,
+)
+
+class NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
+):
+    pass
+
 CreateServiceActionOutputTypeDef = TypedDict(
     "CreateServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceActionOutputTypeDef = TypedDict(
     "DescribeServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceActionOutputTypeDef = TypedDict(
     "UpdateServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProvisioningArtifactOutputTypeDef = TypedDict(
+    "DescribeProvisioningArtifactOutputTypeDef",
+    {
+        "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
+        "Info": Dict[str, str],
+        "Status": StatusType,
+        "ProvisioningArtifactParameters": List[ProvisioningArtifactParameterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProvisioningParametersOutputTypeDef = TypedDict(
     "DescribeProvisioningParametersOutputTypeDef",
     {
         "ProvisioningArtifactParameters": List[ProvisioningArtifactParameterTypeDef],
         "ConstraintSummaries": List[ConstraintSummaryTypeDef],
         "UsageInstructions": List[UsageInstructionTypeDef],
         "TagOptions": List[TagOptionSummaryTypeDef],
         "ProvisioningArtifactPreferences": ProvisioningArtifactPreferencesTypeDef,
         "ProvisioningArtifactOutputs": List[ProvisioningArtifactOutputTypeDef],
         "ProvisioningArtifactOutputKeys": List[ProvisioningArtifactOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecordOutputTypeDef = TypedDict(
     "DescribeRecordOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
         "RecordOutputs": List[RecordOutputTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteProvisionedProductPlanOutputTypeDef = TypedDict(
     "ExecuteProvisionedProductPlanOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteProvisionedProductServiceActionOutputTypeDef = TypedDict(
     "ExecuteProvisionedProductServiceActionOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportAsProvisionedProductOutputTypeDef = TypedDict(
     "ImportAsProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordHistoryOutputTypeDef = TypedDict(
     "ListRecordHistoryOutputTypeDef",
     {
         "RecordDetails": List[RecordDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionProductOutputTypeDef = TypedDict(
     "ProvisionProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TerminateProvisionedProductOutputTypeDef = TypedDict(
     "TerminateProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProvisionedProductOutputTypeDef = TypedDict(
     "UpdateProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceChangeTypeDef = TypedDict(
     "ResourceChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -3433,15 +3395,15 @@
     "DescribePortfolioShareStatusOutputTypeDef",
     {
         "PortfolioShareToken": str,
         "PortfolioId": str,
         "OrganizationNodeValue": str,
         "Status": ShareStatusType,
         "ShareDetails": ShareDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProductViewDetailTypeDef = TypedDict(
     "ProductViewDetailTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
@@ -3474,21 +3436,19 @@
         "Tags": Sequence[TagTypeDef],
         "ProvisioningArtifactParameters": ProvisioningArtifactPropertiesTypeDef,
         "SourceConnection": SourceConnectionTypeDef,
     },
     total=False,
 )
 
-
 class CreateProductInputRequestTypeDef(
     _RequiredCreateProductInputRequestTypeDef, _OptionalCreateProductInputRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateProductInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProductInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateProductInputRequestTypeDef = TypedDict(
@@ -3505,63 +3465,61 @@
         "AddTags": Sequence[TagTypeDef],
         "RemoveTags": Sequence[str],
         "SourceConnection": SourceConnectionTypeDef,
     },
     total=False,
 )
 
-
 class UpdateProductInputRequestTypeDef(
     _RequiredUpdateProductInputRequestTypeDef, _OptionalUpdateProductInputRequestTypeDef
 ):
     pass
 
-
 DescribeProvisionedProductPlanOutputTypeDef = TypedDict(
     "DescribeProvisionedProductPlanOutputTypeDef",
     {
         "ProvisionedProductPlanDetails": ProvisionedProductPlanDetailsTypeDef,
         "ResourceChanges": List[ResourceChangeTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProductOutputTypeDef = TypedDict(
     "CreateProductOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductAsAdminOutputTypeDef = TypedDict(
     "DescribeProductAsAdminOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "ProvisioningArtifactSummaries": List[ProvisioningArtifactSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "TagOptions": List[TagOptionDetailTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchProductsAsAdminOutputTypeDef = TypedDict(
     "SearchProductsAsAdminOutputTypeDef",
     {
         "ProductViewDetails": List[ProductViewDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProductOutputTypeDef = TypedDict(
     "UpdateProductOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog/type_defs.pyi` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 
 from .literals import (
     AccessLevelFilterKeyType,
     AccessStatusType,
     ChangeActionType,
     CopyProductStatusType,
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     EvaluationTypeType,
     LastSyncStatusType,
     OrganizationNodeTypeType,
     PortfolioShareTypeType,
     PrincipalTypeType,
     ProductTypeType,
     ProductViewFilterByType,
@@ -52,50 +53,55 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AcceptPortfolioShareInputRequestTypeDef",
     "AccessLevelFilterTypeDef",
     "AssociateBudgetWithResourceInputRequestTypeDef",
     "AssociatePrincipalWithPortfolioInputRequestTypeDef",
     "AssociateProductWithPortfolioInputRequestTypeDef",
     "AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     "AssociateTagOptionWithResourceInputRequestTypeDef",
     "ServiceActionAssociationTypeDef",
     "FailedServiceActionAssociationTypeDef",
-    "ResponseMetadataTypeDef",
     "BudgetDetailTypeDef",
     "CloudWatchDashboardTypeDef",
     "CodeStarParametersTypeDef",
     "ConstraintDetailTypeDef",
     "ConstraintSummaryTypeDef",
     "CopyProductInputRequestTypeDef",
+    "CopyProductOutputTypeDef",
     "CreateConstraintInputRequestTypeDef",
     "TagTypeDef",
     "PortfolioDetailTypeDef",
     "OrganizationNodeTypeDef",
+    "CreatePortfolioShareOutputTypeDef",
     "ProvisioningArtifactPropertiesTypeDef",
     "ProvisioningArtifactDetailTypeDef",
     "UpdateProvisioningParameterTypeDef",
+    "CreateProvisionedProductPlanOutputTypeDef",
     "CreateServiceActionInputRequestTypeDef",
     "CreateTagOptionInputRequestTypeDef",
     "TagOptionDetailTypeDef",
     "DeleteConstraintInputRequestTypeDef",
     "DeletePortfolioInputRequestTypeDef",
+    "DeletePortfolioShareOutputTypeDef",
     "DeleteProductInputRequestTypeDef",
     "DeleteProvisionedProductPlanInputRequestTypeDef",
     "DeleteProvisioningArtifactInputRequestTypeDef",
     "DeleteServiceActionInputRequestTypeDef",
     "DeleteTagOptionInputRequestTypeDef",
     "DescribeConstraintInputRequestTypeDef",
     "DescribeCopyProductStatusInputRequestTypeDef",
+    "DescribeCopyProductStatusOutputTypeDef",
     "DescribePortfolioInputRequestTypeDef",
     "DescribePortfolioShareStatusInputRequestTypeDef",
     "DescribePortfolioSharesInputRequestTypeDef",
     "PortfolioShareDetailTypeDef",
     "DescribeProductAsAdminInputRequestTypeDef",
     "ProvisioningArtifactSummaryTypeDef",
     "DescribeProductInputRequestTypeDef",
@@ -119,76 +125,88 @@
     "DescribeServiceActionInputRequestTypeDef",
     "DescribeTagOptionInputRequestTypeDef",
     "DisassociateBudgetFromResourceInputRequestTypeDef",
     "DisassociatePrincipalFromPortfolioInputRequestTypeDef",
     "DisassociateProductFromPortfolioInputRequestTypeDef",
     "DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     "DisassociateTagOptionFromResourceInputRequestTypeDef",
+    "UniqueTagResourceIdentifierTypeDef",
     "ExecuteProvisionedProductPlanInputRequestTypeDef",
     "ExecuteProvisionedProductServiceActionInputRequestTypeDef",
+    "GetAWSOrganizationsAccessStatusOutputTypeDef",
     "GetProvisionedProductOutputsInputRequestTypeDef",
     "ImportAsProvisionedProductInputRequestTypeDef",
     "LastSyncTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
     "ListAcceptedPortfolioSharesInputRequestTypeDef",
     "ListBudgetsForResourceInputRequestTypeDef",
+    "ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
     "ListConstraintsForPortfolioInputRequestTypeDef",
+    "ListLaunchPathsInputListLaunchPathsPaginateTypeDef",
     "ListLaunchPathsInputRequestTypeDef",
+    "ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
     "ListOrganizationPortfolioAccessInputRequestTypeDef",
     "ListPortfolioAccessInputRequestTypeDef",
+    "ListPortfolioAccessOutputTypeDef",
+    "ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
     "ListPortfoliosForProductInputRequestTypeDef",
+    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
     "ListPortfoliosInputRequestTypeDef",
+    "ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
     "ListPrincipalsForPortfolioInputRequestTypeDef",
     "PrincipalTypeDef",
     "ProvisionedProductPlanSummaryTypeDef",
+    "ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
     "ListProvisioningArtifactsForServiceActionInputRequestTypeDef",
     "ListProvisioningArtifactsInputRequestTypeDef",
     "ListRecordHistorySearchFilterTypeDef",
+    "ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
     "ListResourcesForTagOptionInputRequestTypeDef",
     "ResourceDetailTypeDef",
+    "ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
     "ListServiceActionsForProvisioningArtifactInputRequestTypeDef",
     "ServiceActionSummaryTypeDef",
+    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
     "ListServiceActionsInputRequestTypeDef",
     "ListStackInstancesForProvisionedProductInputRequestTypeDef",
     "StackInstanceTypeDef",
     "ListTagOptionsFiltersTypeDef",
+    "NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterConstraintsTypeDef",
     "ProductViewAggregationValueTypeDef",
     "ProvisioningParameterTypeDef",
     "ProvisioningPreferencesTypeDef",
     "RecordErrorTypeDef",
     "RecordTagTypeDef",
     "RejectPortfolioShareInputRequestTypeDef",
     "ResourceTargetDefinitionTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchProductsAsAdminInputRequestTypeDef",
+    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
     "SearchProductsInputRequestTypeDef",
     "ShareErrorTypeDef",
     "TerminateProvisionedProductInputRequestTypeDef",
     "UpdateConstraintInputRequestTypeDef",
+    "UpdatePortfolioShareOutputTypeDef",
     "UpdateProvisioningPreferencesTypeDef",
     "UpdateProvisionedProductPropertiesInputRequestTypeDef",
+    "UpdateProvisionedProductPropertiesOutputTypeDef",
     "UpdateProvisioningArtifactInputRequestTypeDef",
     "UpdateServiceActionInputRequestTypeDef",
     "UpdateTagOptionInputRequestTypeDef",
+    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
     "ListProvisionedProductPlansInputRequestTypeDef",
     "ScanProvisionedProductsInputRequestTypeDef",
+    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
     "SearchProvisionedProductsInputRequestTypeDef",
     "BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     "BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     "BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef",
     "BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef",
-    "CopyProductOutputTypeDef",
-    "CreatePortfolioShareOutputTypeDef",
-    "CreateProvisionedProductPlanOutputTypeDef",
-    "DeletePortfolioShareOutputTypeDef",
-    "DescribeCopyProductStatusOutputTypeDef",
-    "GetAWSOrganizationsAccessStatusOutputTypeDef",
-    "ListPortfolioAccessOutputTypeDef",
-    "UpdatePortfolioShareOutputTypeDef",
-    "UpdateProvisionedProductPropertiesOutputTypeDef",
     "ListBudgetsForResourceOutputTypeDef",
     "SourceConnectionParametersTypeDef",
     "CreateConstraintOutputTypeDef",
     "DescribeConstraintOutputTypeDef",
     "ListConstraintsForPortfolioOutputTypeDef",
     "UpdateConstraintOutputTypeDef",
     "CreatePortfolioInputRequestTypeDef",
@@ -202,15 +220,14 @@
     "UpdatePortfolioOutputTypeDef",
     "CreatePortfolioShareInputRequestTypeDef",
     "DeletePortfolioShareInputRequestTypeDef",
     "ListOrganizationPortfolioAccessOutputTypeDef",
     "UpdatePortfolioShareInputRequestTypeDef",
     "CreateProvisioningArtifactInputRequestTypeDef",
     "CreateProvisioningArtifactOutputTypeDef",
-    "DescribeProvisioningArtifactOutputTypeDef",
     "ListProvisioningArtifactsOutputTypeDef",
     "UpdateProvisioningArtifactOutputTypeDef",
     "CreateProvisionedProductPlanInputRequestTypeDef",
     "ProvisionedProductPlanDetailsTypeDef",
     "CreateTagOptionOutputTypeDef",
     "DescribePortfolioOutputTypeDef",
     "DescribeTagOptionOutputTypeDef",
@@ -219,29 +236,17 @@
     "DescribePortfolioSharesOutputTypeDef",
     "DescribeProductOutputTypeDef",
     "DescribeProductViewOutputTypeDef",
     "ProvisioningArtifactViewTypeDef",
     "DescribeProvisionedProductOutputTypeDef",
     "ScanProvisionedProductsOutputTypeDef",
     "GetProvisionedProductOutputsOutputTypeDef",
+    "NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     "DescribeServiceActionExecutionParametersOutputTypeDef",
-    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
-    "ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    "ListLaunchPathsInputListLaunchPathsPaginateTypeDef",
-    "ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    "ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
-    "ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
-    "ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    "ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
-    "ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
-    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
-    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
-    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+    "EngineWorkflowResourceIdentifierTypeDef",
     "ListPrincipalsForPortfolioOutputTypeDef",
     "ListProvisionedProductPlansOutputTypeDef",
     "ListRecordHistoryInputListRecordHistoryPaginateTypeDef",
     "ListRecordHistoryInputRequestTypeDef",
     "ListResourcesForTagOptionOutputTypeDef",
     "ListServiceActionsForProvisioningArtifactOutputTypeDef",
     "ListServiceActionsOutputTypeDef",
@@ -257,17 +262,19 @@
     "ShareDetailsTypeDef",
     "UpdateProvisionedProductInputRequestTypeDef",
     "SourceConnectionDetailTypeDef",
     "SourceConnectionTypeDef",
     "ListLaunchPathsOutputTypeDef",
     "SearchProvisionedProductsOutputTypeDef",
     "ListProvisioningArtifactsForServiceActionOutputTypeDef",
+    "NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
     "CreateServiceActionOutputTypeDef",
     "DescribeServiceActionOutputTypeDef",
     "UpdateServiceActionOutputTypeDef",
+    "DescribeProvisioningArtifactOutputTypeDef",
     "DescribeProvisioningParametersOutputTypeDef",
     "DescribeRecordOutputTypeDef",
     "ExecuteProvisionedProductPlanOutputTypeDef",
     "ExecuteProvisionedProductServiceActionOutputTypeDef",
     "ImportAsProvisionedProductOutputTypeDef",
     "ListRecordHistoryOutputTypeDef",
     "ProvisionProductOutputTypeDef",
@@ -296,20 +303,22 @@
     {
         "AcceptLanguage": str,
         "PortfolioShareType": PortfolioShareTypeType,
     },
     total=False,
 )
 
+
 class AcceptPortfolioShareInputRequestTypeDef(
     _RequiredAcceptPortfolioShareInputRequestTypeDef,
     _OptionalAcceptPortfolioShareInputRequestTypeDef,
 ):
     pass
 
+
 AccessLevelFilterTypeDef = TypedDict(
     "AccessLevelFilterTypeDef",
     {
         "Key": AccessLevelFilterKeyType,
         "Value": str,
     },
     total=False,
@@ -335,20 +344,22 @@
     "_OptionalAssociatePrincipalWithPortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class AssociatePrincipalWithPortfolioInputRequestTypeDef(
     _RequiredAssociatePrincipalWithPortfolioInputRequestTypeDef,
     _OptionalAssociatePrincipalWithPortfolioInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredAssociateProductWithPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredAssociateProductWithPortfolioInputRequestTypeDef",
     {
         "ProductId": str,
         "PortfolioId": str,
     },
 )
@@ -357,20 +368,22 @@
     {
         "AcceptLanguage": str,
         "SourcePortfolioId": str,
     },
     total=False,
 )
 
+
 class AssociateProductWithPortfolioInputRequestTypeDef(
     _RequiredAssociateProductWithPortfolioInputRequestTypeDef,
     _OptionalAssociateProductWithPortfolioInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
         "ServiceActionId": str,
     },
@@ -379,20 +392,22 @@
     "_OptionalAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef(
     _RequiredAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     _OptionalAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 AssociateTagOptionWithResourceInputRequestTypeDef = TypedDict(
     "AssociateTagOptionWithResourceInputRequestTypeDef",
     {
         "ResourceId": str,
         "TagOptionId": str,
     },
 )
@@ -414,25 +429,14 @@
         "ProvisioningArtifactId": str,
         "ErrorCode": ServiceActionAssociationErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
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
 BudgetDetailTypeDef = TypedDict(
     "BudgetDetailTypeDef",
     {
         "BudgetName": str,
     },
     total=False,
 )
@@ -492,19 +496,29 @@
         "TargetProductName": str,
         "SourceProvisioningArtifactIdentifiers": Sequence[Mapping[Literal["Id"], str]],
         "CopyOptions": Sequence[Literal["CopyTags"]],
     },
     total=False,
 )
 
+
 class CopyProductInputRequestTypeDef(
     _RequiredCopyProductInputRequestTypeDef, _OptionalCopyProductInputRequestTypeDef
 ):
     pass
 
+
+CopyProductOutputTypeDef = TypedDict(
+    "CopyProductOutputTypeDef",
+    {
+        "CopyProductToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateConstraintInputRequestTypeDef = TypedDict(
     "_RequiredCreateConstraintInputRequestTypeDef",
     {
         "PortfolioId": str,
         "ProductId": str,
         "Parameters": str,
         "Type": str,
@@ -516,19 +530,21 @@
     {
         "AcceptLanguage": str,
         "Description": str,
     },
     total=False,
 )
 
+
 class CreateConstraintInputRequestTypeDef(
     _RequiredCreateConstraintInputRequestTypeDef, _OptionalCreateConstraintInputRequestTypeDef
 ):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -551,14 +567,22 @@
     {
         "Type": OrganizationNodeTypeType,
         "Value": str,
     },
     total=False,
 )
 
+CreatePortfolioShareOutputTypeDef = TypedDict(
+    "CreatePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ProvisioningArtifactPropertiesTypeDef = TypedDict(
     "ProvisioningArtifactPropertiesTypeDef",
     {
         "Name": str,
         "Description": str,
         "Info": Mapping[str, str],
         "Type": ProvisioningArtifactTypeType,
@@ -588,14 +612,26 @@
         "Key": str,
         "Value": str,
         "UsePreviousValue": bool,
     },
     total=False,
 )
 
+CreateProvisionedProductPlanOutputTypeDef = TypedDict(
+    "CreateProvisionedProductPlanOutputTypeDef",
+    {
+        "PlanName": str,
+        "PlanId": str,
+        "ProvisionProductId": str,
+        "ProvisionedProductName": str,
+        "ProvisioningArtifactId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredCreateServiceActionInputRequestTypeDef",
     {
         "Name": str,
         "DefinitionType": Literal["SSM_AUTOMATION"],
         "Definition": Mapping[ServiceActionDefinitionKeyType, str],
         "IdempotencyToken": str,
@@ -606,19 +642,21 @@
     {
         "Description": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class CreateServiceActionInputRequestTypeDef(
     _RequiredCreateServiceActionInputRequestTypeDef, _OptionalCreateServiceActionInputRequestTypeDef
 ):
     pass
 
+
 CreateTagOptionInputRequestTypeDef = TypedDict(
     "CreateTagOptionInputRequestTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -645,57 +683,71 @@
     "_OptionalDeleteConstraintInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DeleteConstraintInputRequestTypeDef(
     _RequiredDeleteConstraintInputRequestTypeDef, _OptionalDeleteConstraintInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDeletePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDeletePortfolioInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDeletePortfolioInputRequestTypeDef = TypedDict(
     "_OptionalDeletePortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DeletePortfolioInputRequestTypeDef(
     _RequiredDeletePortfolioInputRequestTypeDef, _OptionalDeletePortfolioInputRequestTypeDef
 ):
     pass
 
+
+DeletePortfolioShareOutputTypeDef = TypedDict(
+    "DeletePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteProductInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProductInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDeleteProductInputRequestTypeDef = TypedDict(
     "_OptionalDeleteProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DeleteProductInputRequestTypeDef(
     _RequiredDeleteProductInputRequestTypeDef, _OptionalDeleteProductInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDeleteProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanId": str,
     },
 )
 _OptionalDeleteProvisionedProductPlanInputRequestTypeDef = TypedDict(
@@ -703,20 +755,22 @@
     {
         "AcceptLanguage": str,
         "IgnoreErrors": bool,
     },
     total=False,
 )
 
+
 class DeleteProvisionedProductPlanInputRequestTypeDef(
     _RequiredDeleteProvisionedProductPlanInputRequestTypeDef,
     _OptionalDeleteProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeleteProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredDeleteProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
 )
@@ -724,39 +778,43 @@
     "_OptionalDeleteProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DeleteProvisioningArtifactInputRequestTypeDef(
     _RequiredDeleteProvisioningArtifactInputRequestTypeDef,
     _OptionalDeleteProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeleteServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredDeleteServiceActionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDeleteServiceActionInputRequestTypeDef = TypedDict(
     "_OptionalDeleteServiceActionInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DeleteServiceActionInputRequestTypeDef(
     _RequiredDeleteServiceActionInputRequestTypeDef, _OptionalDeleteServiceActionInputRequestTypeDef
 ):
     pass
 
+
 DeleteTagOptionInputRequestTypeDef = TypedDict(
     "DeleteTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -770,58 +828,74 @@
     "_OptionalDescribeConstraintInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribeConstraintInputRequestTypeDef(
     _RequiredDescribeConstraintInputRequestTypeDef, _OptionalDescribeConstraintInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDescribeCopyProductStatusInputRequestTypeDef = TypedDict(
     "_RequiredDescribeCopyProductStatusInputRequestTypeDef",
     {
         "CopyProductToken": str,
     },
 )
 _OptionalDescribeCopyProductStatusInputRequestTypeDef = TypedDict(
     "_OptionalDescribeCopyProductStatusInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribeCopyProductStatusInputRequestTypeDef(
     _RequiredDescribeCopyProductStatusInputRequestTypeDef,
     _OptionalDescribeCopyProductStatusInputRequestTypeDef,
 ):
     pass
 
+
+DescribeCopyProductStatusOutputTypeDef = TypedDict(
+    "DescribeCopyProductStatusOutputTypeDef",
+    {
+        "CopyProductStatus": CopyProductStatusType,
+        "TargetProductId": str,
+        "StatusDetail": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDescribePortfolioInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalDescribePortfolioInputRequestTypeDef = TypedDict(
     "_OptionalDescribePortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribePortfolioInputRequestTypeDef(
     _RequiredDescribePortfolioInputRequestTypeDef, _OptionalDescribePortfolioInputRequestTypeDef
 ):
     pass
 
+
 DescribePortfolioShareStatusInputRequestTypeDef = TypedDict(
     "DescribePortfolioShareStatusInputRequestTypeDef",
     {
         "PortfolioShareToken": str,
     },
 )
 
@@ -837,20 +911,22 @@
     {
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class DescribePortfolioSharesInputRequestTypeDef(
     _RequiredDescribePortfolioSharesInputRequestTypeDef,
     _OptionalDescribePortfolioSharesInputRequestTypeDef,
 ):
     pass
 
+
 PortfolioShareDetailTypeDef = TypedDict(
     "PortfolioShareDetailTypeDef",
     {
         "PrincipalId": str,
         "Type": DescribePortfolioShareTypeType,
         "Accepted": bool,
         "ShareTagOptions": bool,
@@ -941,19 +1017,21 @@
     "_OptionalDescribeProductViewInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribeProductViewInputRequestTypeDef(
     _RequiredDescribeProductViewInputRequestTypeDef, _OptionalDescribeProductViewInputRequestTypeDef
 ):
     pass
 
+
 DescribeProvisionedProductInputRequestTypeDef = TypedDict(
     "DescribeProvisionedProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "Id": str,
         "Name": str,
     },
@@ -993,29 +1071,32 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class DescribeProvisionedProductPlanInputRequestTypeDef(
     _RequiredDescribeProvisionedProductPlanInputRequestTypeDef,
     _OptionalDescribeProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
+
 DescribeProvisioningArtifactInputRequestTypeDef = TypedDict(
     "DescribeProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisioningArtifactId": str,
         "ProductId": str,
         "ProvisioningArtifactName": str,
         "ProductName": str,
         "Verbose": bool,
+        "IncludeProvisioningArtifactParameters": bool,
     },
     total=False,
 )
 
 DescribeProvisioningParametersInputRequestTypeDef = TypedDict(
     "DescribeProvisioningParametersInputRequestTypeDef",
     {
@@ -1078,19 +1159,21 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class DescribeRecordInputRequestTypeDef(
     _RequiredDescribeRecordInputRequestTypeDef, _OptionalDescribeRecordInputRequestTypeDef
 ):
     pass
 
+
 RecordOutputTypeDef = TypedDict(
     "RecordOutputTypeDef",
     {
         "OutputKey": str,
         "OutputValue": str,
         "Description": str,
     },
@@ -1108,20 +1191,22 @@
     "_OptionalDescribeServiceActionExecutionParametersInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribeServiceActionExecutionParametersInputRequestTypeDef(
     _RequiredDescribeServiceActionExecutionParametersInputRequestTypeDef,
     _OptionalDescribeServiceActionExecutionParametersInputRequestTypeDef,
 ):
     pass
 
+
 ExecutionParameterTypeDef = TypedDict(
     "ExecutionParameterTypeDef",
     {
         "Name": str,
         "Type": str,
         "DefaultValues": List[str],
     },
@@ -1138,20 +1223,22 @@
     "_OptionalDescribeServiceActionInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DescribeServiceActionInputRequestTypeDef(
     _RequiredDescribeServiceActionInputRequestTypeDef,
     _OptionalDescribeServiceActionInputRequestTypeDef,
 ):
     pass
 
+
 DescribeTagOptionInputRequestTypeDef = TypedDict(
     "DescribeTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1175,20 +1262,22 @@
     {
         "AcceptLanguage": str,
         "PrincipalType": PrincipalTypeType,
     },
     total=False,
 )
 
+
 class DisassociatePrincipalFromPortfolioInputRequestTypeDef(
     _RequiredDisassociatePrincipalFromPortfolioInputRequestTypeDef,
     _OptionalDisassociatePrincipalFromPortfolioInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDisassociateProductFromPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredDisassociateProductFromPortfolioInputRequestTypeDef",
     {
         "ProductId": str,
         "PortfolioId": str,
     },
 )
@@ -1196,20 +1285,22 @@
     "_OptionalDisassociateProductFromPortfolioInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DisassociateProductFromPortfolioInputRequestTypeDef(
     _RequiredDisassociateProductFromPortfolioInputRequestTypeDef,
     _OptionalDisassociateProductFromPortfolioInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
         "ServiceActionId": str,
     },
@@ -1218,28 +1309,39 @@
     "_OptionalDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef(
     _RequiredDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     _OptionalDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 DisassociateTagOptionFromResourceInputRequestTypeDef = TypedDict(
     "DisassociateTagOptionFromResourceInputRequestTypeDef",
     {
         "ResourceId": str,
         "TagOptionId": str,
     },
 )
 
+UniqueTagResourceIdentifierTypeDef = TypedDict(
+    "UniqueTagResourceIdentifierTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+    },
+    total=False,
+)
+
 _RequiredExecuteProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredExecuteProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanId": str,
         "IdempotencyToken": str,
     },
 )
@@ -1247,20 +1349,22 @@
     "_OptionalExecuteProvisionedProductPlanInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class ExecuteProvisionedProductPlanInputRequestTypeDef(
     _RequiredExecuteProvisionedProductPlanInputRequestTypeDef,
     _OptionalExecuteProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef",
     {
         "ProvisionedProductId": str,
         "ServiceActionId": str,
         "ExecuteToken": str,
     },
@@ -1270,20 +1374,30 @@
     {
         "AcceptLanguage": str,
         "Parameters": Mapping[str, Sequence[str]],
     },
     total=False,
 )
 
+
 class ExecuteProvisionedProductServiceActionInputRequestTypeDef(
     _RequiredExecuteProvisionedProductServiceActionInputRequestTypeDef,
     _OptionalExecuteProvisionedProductServiceActionInputRequestTypeDef,
 ):
     pass
 
+
+GetAWSOrganizationsAccessStatusOutputTypeDef = TypedDict(
+    "GetAWSOrganizationsAccessStatusOutputTypeDef",
+    {
+        "AccessStatus": AccessStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetProvisionedProductOutputsInputRequestTypeDef = TypedDict(
     "GetProvisionedProductOutputsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisionedProductId": str,
         "ProvisionedProductName": str,
         "OutputKeys": Sequence[str],
@@ -1307,38 +1421,40 @@
     "_OptionalImportAsProvisionedProductInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class ImportAsProvisionedProductInputRequestTypeDef(
     _RequiredImportAsProvisionedProductInputRequestTypeDef,
     _OptionalImportAsProvisionedProductInputRequestTypeDef,
 ):
     pass
 
+
 LastSyncTypeDef = TypedDict(
     "LastSyncTypeDef",
     {
         "LastSyncTime": datetime,
         "LastSyncStatus": LastSyncStatusType,
         "LastSyncStatusMessage": str,
         "LastSuccessfulSyncTime": datetime,
         "LastSuccessfulSyncProvisioningArtifactId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef = TypedDict(
+    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AcceptLanguage": str,
+        "PortfolioShareType": PortfolioShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAcceptedPortfolioSharesInputRequestTypeDef = TypedDict(
     "ListAcceptedPortfolioSharesInputRequestTypeDef",
     {
@@ -1362,20 +1478,46 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class ListBudgetsForResourceInputRequestTypeDef(
     _RequiredListBudgetsForResourceInputRequestTypeDef,
     _OptionalListBudgetsForResourceInputRequestTypeDef,
 ):
     pass
 
+
+_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
+    "_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
+    {
+        "PortfolioId": str,
+    },
+)
+_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
+    "_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "ProductId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef(
+    _RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
+    _OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListConstraintsForPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredListConstraintsForPortfolioInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalListConstraintsForPortfolioInputRequestTypeDef = TypedDict(
@@ -1385,20 +1527,45 @@
         "ProductId": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class ListConstraintsForPortfolioInputRequestTypeDef(
     _RequiredListConstraintsForPortfolioInputRequestTypeDef,
     _OptionalListConstraintsForPortfolioInputRequestTypeDef,
 ):
     pass
 
+
+_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef",
+    {
+        "ProductId": str,
+    },
+)
+_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLaunchPathsInputListLaunchPathsPaginateTypeDef(
+    _RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef,
+    _OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLaunchPathsInputRequestTypeDef = TypedDict(
     "_RequiredListLaunchPathsInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
 _OptionalListLaunchPathsInputRequestTypeDef = TypedDict(
@@ -1407,19 +1574,45 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class ListLaunchPathsInputRequestTypeDef(
     _RequiredListLaunchPathsInputRequestTypeDef, _OptionalListLaunchPathsInputRequestTypeDef
 ):
     pass
 
+
+_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
+    "_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
+    {
+        "PortfolioId": str,
+        "OrganizationNodeType": OrganizationNodeTypeType,
+    },
+)
+_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
+    "_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef(
+    _RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
+    _OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListOrganizationPortfolioAccessInputRequestTypeDef = TypedDict(
     "_RequiredListOrganizationPortfolioAccessInputRequestTypeDef",
     {
         "PortfolioId": str,
         "OrganizationNodeType": OrganizationNodeTypeType,
     },
 )
@@ -1429,20 +1622,22 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class ListOrganizationPortfolioAccessInputRequestTypeDef(
     _RequiredListOrganizationPortfolioAccessInputRequestTypeDef,
     _OptionalListOrganizationPortfolioAccessInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredListPortfolioAccessInputRequestTypeDef = TypedDict(
     "_RequiredListPortfolioAccessInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalListPortfolioAccessInputRequestTypeDef = TypedDict(
@@ -1452,19 +1647,53 @@
         "OrganizationParentId": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class ListPortfolioAccessInputRequestTypeDef(
     _RequiredListPortfolioAccessInputRequestTypeDef, _OptionalListPortfolioAccessInputRequestTypeDef
 ):
     pass
 
+
+ListPortfolioAccessOutputTypeDef = TypedDict(
+    "ListPortfolioAccessOutputTypeDef",
+    {
+        "AccountIds": List[str],
+        "NextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
+    "_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
+    {
+        "ProductId": str,
+    },
+)
+_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
+    "_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef(
+    _RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
+    _OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPortfoliosForProductInputRequestTypeDef = TypedDict(
     "_RequiredListPortfoliosForProductInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
 _OptionalListPortfoliosForProductInputRequestTypeDef = TypedDict(
@@ -1473,30 +1702,64 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class ListPortfoliosForProductInputRequestTypeDef(
     _RequiredListPortfoliosForProductInputRequestTypeDef,
     _OptionalListPortfoliosForProductInputRequestTypeDef,
 ):
     pass
 
+
+ListPortfoliosInputListPortfoliosPaginateTypeDef = TypedDict(
+    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPortfoliosInputRequestTypeDef = TypedDict(
     "ListPortfoliosInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
+    {
+        "PortfolioId": str,
+    },
+)
+_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef(
+    _RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
+    _OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPrincipalsForPortfolioInputRequestTypeDef = TypedDict(
     "_RequiredListPrincipalsForPortfolioInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalListPrincipalsForPortfolioInputRequestTypeDef = TypedDict(
@@ -1505,20 +1768,22 @@
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class ListPrincipalsForPortfolioInputRequestTypeDef(
     _RequiredListPrincipalsForPortfolioInputRequestTypeDef,
     _OptionalListPrincipalsForPortfolioInputRequestTypeDef,
 ):
     pass
 
+
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "PrincipalARN": str,
         "PrincipalType": PrincipalTypeType,
     },
     total=False,
@@ -1533,14 +1798,37 @@
         "ProvisionProductName": str,
         "PlanType": Literal["CLOUDFORMATION"],
         "ProvisioningArtifactId": str,
     },
     total=False,
 )
 
+_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
+    "_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
+    {
+        "ServiceActionId": str,
+    },
+)
+_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
+    "_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef(
+    _RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
+    _OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef",
     {
         "ServiceActionId": str,
     },
 )
 _OptionalListProvisioningArtifactsForServiceActionInputRequestTypeDef = TypedDict(
@@ -1549,49 +1837,76 @@
         "PageSize": int,
         "PageToken": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class ListProvisioningArtifactsForServiceActionInputRequestTypeDef(
     _RequiredListProvisioningArtifactsForServiceActionInputRequestTypeDef,
     _OptionalListProvisioningArtifactsForServiceActionInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredListProvisioningArtifactsInputRequestTypeDef = TypedDict(
     "_RequiredListProvisioningArtifactsInputRequestTypeDef",
     {
         "ProductId": str,
     },
 )
 _OptionalListProvisioningArtifactsInputRequestTypeDef = TypedDict(
     "_OptionalListProvisioningArtifactsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class ListProvisioningArtifactsInputRequestTypeDef(
     _RequiredListProvisioningArtifactsInputRequestTypeDef,
     _OptionalListProvisioningArtifactsInputRequestTypeDef,
 ):
     pass
 
+
 ListRecordHistorySearchFilterTypeDef = TypedDict(
     "ListRecordHistorySearchFilterTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+    {
+        "TagOptionId": str,
+    },
+)
+_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef(
+    _RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
+    _OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourcesForTagOptionInputRequestTypeDef = TypedDict(
     "_RequiredListResourcesForTagOptionInputRequestTypeDef",
     {
         "TagOptionId": str,
     },
 )
 _OptionalListResourcesForTagOptionInputRequestTypeDef = TypedDict(
@@ -1600,32 +1915,58 @@
         "ResourceType": str,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+
 class ListResourcesForTagOptionInputRequestTypeDef(
     _RequiredListResourcesForTagOptionInputRequestTypeDef,
     _OptionalListResourcesForTagOptionInputRequestTypeDef,
 ):
     pass
 
+
 ResourceDetailTypeDef = TypedDict(
     "ResourceDetailTypeDef",
     {
         "Id": str,
         "ARN": str,
         "Name": str,
         "Description": str,
         "CreatedTime": datetime,
     },
     total=False,
 )
 
+_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
+    "_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
+    {
+        "ProductId": str,
+        "ProvisioningArtifactId": str,
+    },
+)
+_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
+    "_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef(
+    _RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+    _OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
 )
@@ -1635,31 +1976,42 @@
         "PageSize": int,
         "PageToken": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class ListServiceActionsForProvisioningArtifactInputRequestTypeDef(
     _RequiredListServiceActionsForProvisioningArtifactInputRequestTypeDef,
     _OptionalListServiceActionsForProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 ServiceActionSummaryTypeDef = TypedDict(
     "ServiceActionSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "DefinitionType": Literal["SSM_AUTOMATION"],
     },
     total=False,
 )
 
+ListServiceActionsInputListServiceActionsPaginateTypeDef = TypedDict(
+    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceActionsInputRequestTypeDef = TypedDict(
     "ListServiceActionsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PageSize": int,
         "PageToken": str,
     },
@@ -1678,20 +2030,22 @@
         "AcceptLanguage": str,
         "PageToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+
 class ListStackInstancesForProvisionedProductInputRequestTypeDef(
     _RequiredListStackInstancesForProvisionedProductInputRequestTypeDef,
     _OptionalListStackInstancesForProvisionedProductInputRequestTypeDef,
 ):
     pass
 
+
 StackInstanceTypeDef = TypedDict(
     "StackInstanceTypeDef",
     {
         "Account": str,
         "Region": str,
         "StackInstanceStatus": StackInstanceStatusType,
     },
@@ -1704,14 +2058,49 @@
         "Key": str,
         "Value": str,
         "Active": bool,
     },
     total=False,
 )
 
+_RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
+    },
+)
+_OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "FailureReason": str,
+    },
+    total=False,
+)
+
+
+class NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+):
+    pass
+
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
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "AllowedValues": List[str],
         "AllowedPattern": str,
         "ConstraintDescription": str,
         "MaxLength": str,
@@ -1782,30 +2171,43 @@
     {
         "AcceptLanguage": str,
         "PortfolioShareType": PortfolioShareTypeType,
     },
     total=False,
 )
 
+
 class RejectPortfolioShareInputRequestTypeDef(
     _RequiredRejectPortfolioShareInputRequestTypeDef,
     _OptionalRejectPortfolioShareInputRequestTypeDef,
 ):
     pass
 
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
 SearchProductsAsAdminInputRequestTypeDef = TypedDict(
     "SearchProductsAsAdminInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "PortfolioId": str,
         "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
         "SortBy": ProductViewSortByType,
@@ -1813,14 +2215,28 @@
         "PageToken": str,
         "PageSize": int,
         "ProductSource": Literal["ACCOUNT"],
     },
     total=False,
 )
 
+SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef = TypedDict(
+    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "PortfolioId": str,
+        "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
+        "SortBy": ProductViewSortByType,
+        "SortOrder": SortOrderType,
+        "ProductSource": Literal["ACCOUNT"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 SearchProductsInputRequestTypeDef = TypedDict(
     "SearchProductsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
         "PageSize": int,
         "SortBy": ProductViewSortByType,
@@ -1854,20 +2270,22 @@
         "IgnoreErrors": bool,
         "AcceptLanguage": str,
         "RetainPhysicalResources": bool,
     },
     total=False,
 )
 
+
 class TerminateProvisionedProductInputRequestTypeDef(
     _RequiredTerminateProvisionedProductInputRequestTypeDef,
     _OptionalTerminateProvisionedProductInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateConstraintInputRequestTypeDef = TypedDict(
     "_RequiredUpdateConstraintInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateConstraintInputRequestTypeDef = TypedDict(
@@ -1876,19 +2294,30 @@
         "AcceptLanguage": str,
         "Description": str,
         "Parameters": str,
     },
     total=False,
 )
 
+
 class UpdateConstraintInputRequestTypeDef(
     _RequiredUpdateConstraintInputRequestTypeDef, _OptionalUpdateConstraintInputRequestTypeDef
 ):
     pass
 
+
+UpdatePortfolioShareOutputTypeDef = TypedDict(
+    "UpdatePortfolioShareOutputTypeDef",
+    {
+        "PortfolioShareToken": str,
+        "Status": ShareStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateProvisioningPreferencesTypeDef = TypedDict(
     "UpdateProvisioningPreferencesTypeDef",
     {
         "StackSetAccounts": Sequence[str],
         "StackSetRegions": Sequence[str],
         "StackSetFailureToleranceCount": int,
         "StackSetFailureTolerancePercentage": int,
@@ -1911,20 +2340,33 @@
     "_OptionalUpdateProvisionedProductPropertiesInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class UpdateProvisionedProductPropertiesInputRequestTypeDef(
     _RequiredUpdateProvisionedProductPropertiesInputRequestTypeDef,
     _OptionalUpdateProvisionedProductPropertiesInputRequestTypeDef,
 ):
     pass
 
+
+UpdateProvisionedProductPropertiesOutputTypeDef = TypedDict(
+    "UpdateProvisionedProductPropertiesOutputTypeDef",
+    {
+        "ProvisionedProductId": str,
+        "ProvisionedProductProperties": Dict[PropertyKeyType, str],
+        "RecordId": str,
+        "Status": RecordStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "ProvisioningArtifactId": str,
     },
 )
@@ -1936,20 +2378,22 @@
         "Description": str,
         "Active": bool,
         "Guidance": ProvisioningArtifactGuidanceType,
     },
     total=False,
 )
 
+
 class UpdateProvisioningArtifactInputRequestTypeDef(
     _RequiredUpdateProvisioningArtifactInputRequestTypeDef,
     _OptionalUpdateProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateServiceActionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceActionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateServiceActionInputRequestTypeDef = TypedDict(
@@ -1959,19 +2403,21 @@
         "Definition": Mapping[ServiceActionDefinitionKeyType, str],
         "Description": str,
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class UpdateServiceActionInputRequestTypeDef(
     _RequiredUpdateServiceActionInputRequestTypeDef, _OptionalUpdateServiceActionInputRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateTagOptionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTagOptionInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateTagOptionInputRequestTypeDef = TypedDict(
@@ -1979,19 +2425,32 @@
     {
         "Value": str,
         "Active": bool,
     },
     total=False,
 )
 
+
 class UpdateTagOptionInputRequestTypeDef(
     _RequiredUpdateTagOptionInputRequestTypeDef, _OptionalUpdateTagOptionInputRequestTypeDef
 ):
     pass
 
+
+ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef = TypedDict(
+    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "ProvisionProductId": str,
+        "AccessLevelFilter": AccessLevelFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProvisionedProductPlansInputRequestTypeDef = TypedDict(
     "ListProvisionedProductPlansInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "ProvisionProductId": str,
         "PageSize": int,
         "PageToken": str,
@@ -2007,14 +2466,24 @@
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "PageSize": int,
         "PageToken": str,
     },
     total=False,
 )
 
+ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef = TypedDict(
+    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
+    {
+        "AcceptLanguage": str,
+        "AccessLevelFilter": AccessLevelFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 SearchProvisionedProductsInputRequestTypeDef = TypedDict(
     "SearchProvisionedProductsInputRequestTypeDef",
     {
         "AcceptLanguage": str,
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "Filters": Mapping[Literal["SearchQuery"], Sequence[str]],
         "SortBy": str,
@@ -2035,145 +2504,66 @@
     "_OptionalBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef(
     _RequiredBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     _OptionalBatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "ServiceActionAssociations": Sequence[ServiceActionAssociationTypeDef],
     },
 )
 _OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef(
     _RequiredBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     _OptionalBatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef = TypedDict(
     "BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef",
     {
         "FailedServiceActionAssociations": List[FailedServiceActionAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef = TypedDict(
     "BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef",
     {
         "FailedServiceActionAssociations": List[FailedServiceActionAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CopyProductOutputTypeDef = TypedDict(
-    "CopyProductOutputTypeDef",
-    {
-        "CopyProductToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePortfolioShareOutputTypeDef = TypedDict(
-    "CreatePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProvisionedProductPlanOutputTypeDef = TypedDict(
-    "CreateProvisionedProductPlanOutputTypeDef",
-    {
-        "PlanName": str,
-        "PlanId": str,
-        "ProvisionProductId": str,
-        "ProvisionedProductName": str,
-        "ProvisioningArtifactId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePortfolioShareOutputTypeDef = TypedDict(
-    "DeletePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCopyProductStatusOutputTypeDef = TypedDict(
-    "DescribeCopyProductStatusOutputTypeDef",
-    {
-        "CopyProductStatus": CopyProductStatusType,
-        "TargetProductId": str,
-        "StatusDetail": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAWSOrganizationsAccessStatusOutputTypeDef = TypedDict(
-    "GetAWSOrganizationsAccessStatusOutputTypeDef",
-    {
-        "AccessStatus": AccessStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPortfolioAccessOutputTypeDef = TypedDict(
-    "ListPortfolioAccessOutputTypeDef",
-    {
-        "AccountIds": List[str],
-        "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePortfolioShareOutputTypeDef = TypedDict(
-    "UpdatePortfolioShareOutputTypeDef",
-    {
-        "PortfolioShareToken": str,
-        "Status": ShareStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProvisionedProductPropertiesOutputTypeDef = TypedDict(
-    "UpdateProvisionedProductPropertiesOutputTypeDef",
-    {
-        "ProvisionedProductId": str,
-        "ProvisionedProductProperties": Dict[PropertyKeyType, str],
-        "RecordId": str,
-        "Status": RecordStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBudgetsForResourceOutputTypeDef = TypedDict(
     "ListBudgetsForResourceOutputTypeDef",
     {
         "Budgets": List[BudgetDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceConnectionParametersTypeDef = TypedDict(
     "SourceConnectionParametersTypeDef",
     {
         "CodeStar": CodeStarParametersTypeDef,
@@ -2183,44 +2573,44 @@
 
 CreateConstraintOutputTypeDef = TypedDict(
     "CreateConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConstraintOutputTypeDef = TypedDict(
     "DescribeConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConstraintsForPortfolioOutputTypeDef = TypedDict(
     "ListConstraintsForPortfolioOutputTypeDef",
     {
         "ConstraintDetails": List[ConstraintDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConstraintOutputTypeDef = TypedDict(
     "UpdateConstraintOutputTypeDef",
     {
         "ConstraintDetail": ConstraintDetailTypeDef,
         "ConstraintParameters": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePortfolioInputRequestTypeDef = TypedDict(
     "_RequiredCreatePortfolioInputRequestTypeDef",
     {
         "DisplayName": str,
@@ -2234,19 +2624,21 @@
         "AcceptLanguage": str,
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreatePortfolioInputRequestTypeDef(
     _RequiredCreatePortfolioInputRequestTypeDef, _OptionalCreatePortfolioInputRequestTypeDef
 ):
     pass
 
+
 LaunchPathSummaryTypeDef = TypedDict(
     "LaunchPathSummaryTypeDef",
     {
         "Id": str,
         "ConstraintSummaries": List[ConstraintSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "Name": str,
@@ -2295,61 +2687,63 @@
         "ProviderName": str,
         "AddTags": Sequence[TagTypeDef],
         "RemoveTags": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdatePortfolioInputRequestTypeDef(
     _RequiredUpdatePortfolioInputRequestTypeDef, _OptionalUpdatePortfolioInputRequestTypeDef
 ):
     pass
 
+
 CreatePortfolioOutputTypeDef = TypedDict(
     "CreatePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAcceptedPortfolioSharesOutputTypeDef = TypedDict(
     "ListAcceptedPortfolioSharesOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortfoliosForProductOutputTypeDef = TypedDict(
     "ListPortfoliosForProductOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortfoliosOutputTypeDef = TypedDict(
     "ListPortfoliosOutputTypeDef",
     {
         "PortfolioDetails": List[PortfolioDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePortfolioOutputTypeDef = TypedDict(
     "UpdatePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredCreatePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
@@ -2363,20 +2757,22 @@
         "OrganizationNode": OrganizationNodeTypeDef,
         "ShareTagOptions": bool,
         "SharePrincipals": bool,
     },
     total=False,
 )
 
+
 class CreatePortfolioShareInputRequestTypeDef(
     _RequiredCreatePortfolioShareInputRequestTypeDef,
     _OptionalCreatePortfolioShareInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeletePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredDeletePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
     },
 )
 _OptionalDeletePortfolioShareInputRequestTypeDef = TypedDict(
@@ -2385,26 +2781,28 @@
         "AcceptLanguage": str,
         "AccountId": str,
         "OrganizationNode": OrganizationNodeTypeDef,
     },
     total=False,
 )
 
+
 class DeletePortfolioShareInputRequestTypeDef(
     _RequiredDeletePortfolioShareInputRequestTypeDef,
     _OptionalDeletePortfolioShareInputRequestTypeDef,
 ):
     pass
 
+
 ListOrganizationPortfolioAccessOutputTypeDef = TypedDict(
     "ListOrganizationPortfolioAccessOutputTypeDef",
     {
         "OrganizationNodes": List[OrganizationNodeTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePortfolioShareInputRequestTypeDef = TypedDict(
     "_RequiredUpdatePortfolioShareInputRequestTypeDef",
     {
         "PortfolioId": str,
@@ -2418,20 +2816,22 @@
         "OrganizationNode": OrganizationNodeTypeDef,
         "ShareTagOptions": bool,
         "SharePrincipals": bool,
     },
     total=False,
 )
 
+
 class UpdatePortfolioShareInputRequestTypeDef(
     _RequiredUpdatePortfolioShareInputRequestTypeDef,
     _OptionalUpdatePortfolioShareInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateProvisioningArtifactInputRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningArtifactInputRequestTypeDef",
     {
         "ProductId": str,
         "Parameters": ProvisioningArtifactPropertiesTypeDef,
         "IdempotencyToken": str,
     },
@@ -2440,56 +2840,48 @@
     "_OptionalCreateProvisioningArtifactInputRequestTypeDef",
     {
         "AcceptLanguage": str,
     },
     total=False,
 )
 
+
 class CreateProvisioningArtifactInputRequestTypeDef(
     _RequiredCreateProvisioningArtifactInputRequestTypeDef,
     _OptionalCreateProvisioningArtifactInputRequestTypeDef,
 ):
     pass
 
+
 CreateProvisioningArtifactOutputTypeDef = TypedDict(
     "CreateProvisioningArtifactOutputTypeDef",
     {
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Info": Dict[str, str],
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProvisioningArtifactOutputTypeDef = TypedDict(
-    "DescribeProvisioningArtifactOutputTypeDef",
-    {
-        "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
-        "Info": Dict[str, str],
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningArtifactsOutputTypeDef = TypedDict(
     "ListProvisioningArtifactsOutputTypeDef",
     {
         "ProvisioningArtifactDetails": List[ProvisioningArtifactDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProvisioningArtifactOutputTypeDef = TypedDict(
     "UpdateProvisioningArtifactOutputTypeDef",
     {
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Info": Dict[str, str],
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProvisionedProductPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateProvisionedProductPlanInputRequestTypeDef",
     {
         "PlanName": str,
@@ -2508,20 +2900,22 @@
         "PathId": str,
         "ProvisioningParameters": Sequence[UpdateProvisioningParameterTypeDef],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateProvisionedProductPlanInputRequestTypeDef(
     _RequiredCreateProvisionedProductPlanInputRequestTypeDef,
     _OptionalCreateProvisionedProductPlanInputRequestTypeDef,
 ):
     pass
 
+
 ProvisionedProductPlanDetailsTypeDef = TypedDict(
     "ProvisionedProductPlanDetailsTypeDef",
     {
         "CreatedTime": datetime,
         "PathId": str,
         "ProductId": str,
         "PlanName": str,
@@ -2540,80 +2934,80 @@
     total=False,
 )
 
 CreateTagOptionOutputTypeDef = TypedDict(
     "CreateTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortfolioOutputTypeDef = TypedDict(
     "DescribePortfolioOutputTypeDef",
     {
         "PortfolioDetail": PortfolioDetailTypeDef,
         "Tags": List[TagTypeDef],
         "TagOptions": List[TagOptionDetailTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTagOptionOutputTypeDef = TypedDict(
     "DescribeTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagOptionsOutputTypeDef = TypedDict(
     "ListTagOptionsOutputTypeDef",
     {
         "TagOptionDetails": List[TagOptionDetailTypeDef],
         "PageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTagOptionOutputTypeDef = TypedDict(
     "UpdateTagOptionOutputTypeDef",
     {
         "TagOptionDetail": TagOptionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortfolioSharesOutputTypeDef = TypedDict(
     "DescribePortfolioSharesOutputTypeDef",
     {
         "NextPageToken": str,
         "PortfolioShareDetails": List[PortfolioShareDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductOutputTypeDef = TypedDict(
     "DescribeProductOutputTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
         "ProvisioningArtifacts": List[ProvisioningArtifactTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
         "LaunchPaths": List[LaunchPathTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductViewOutputTypeDef = TypedDict(
     "DescribeProductViewOutputTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
         "ProvisioningArtifacts": List[ProvisioningArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisioningArtifactViewTypeDef = TypedDict(
     "ProvisioningArtifactViewTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
@@ -2623,303 +3017,103 @@
 )
 
 DescribeProvisionedProductOutputTypeDef = TypedDict(
     "DescribeProvisionedProductOutputTypeDef",
     {
         "ProvisionedProductDetail": ProvisionedProductDetailTypeDef,
         "CloudWatchDashboards": List[CloudWatchDashboardTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanProvisionedProductsOutputTypeDef = TypedDict(
     "ScanProvisionedProductsOutputTypeDef",
     {
         "ProvisionedProducts": List[ProvisionedProductDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProvisionedProductOutputsOutputTypeDef = TypedDict(
     "GetProvisionedProductOutputsOutputTypeDef",
     {
         "Outputs": List[RecordOutputTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeServiceActionExecutionParametersOutputTypeDef = TypedDict(
-    "DescribeServiceActionExecutionParametersOutputTypeDef",
-    {
-        "ServiceActionParameters": List[ExecutionParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef = TypedDict(
-    "ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PortfolioShareType": PortfolioShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
-    "_RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    {
-        "PortfolioId": str,
-    },
-)
-_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef = TypedDict(
-    "_OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "ProductId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef(
-    _RequiredListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-    _OptionalListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-):
-    pass
-
-_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef",
-    {
-        "ProductId": str,
-    },
-)
-_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLaunchPathsInputListLaunchPathsPaginateTypeDef(
-    _RequiredListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-    _OptionalListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-):
-    pass
-
-_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
-    "_RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    {
-        "PortfolioId": str,
-        "OrganizationNodeType": OrganizationNodeTypeType,
-    },
-)
-_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef = TypedDict(
-    "_OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef(
-    _RequiredListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-    _OptionalListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-):
-    pass
-
-_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
-    "_RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    {
-        "ProductId": str,
-    },
-)
-_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef = TypedDict(
-    "_OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef(
-    _RequiredListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-    _OptionalListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-):
-    pass
-
-ListPortfoliosInputListPortfoliosPaginateTypeDef = TypedDict(
-    "ListPortfoliosInputListPortfoliosPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    {
-        "PortfolioId": str,
-    },
-)
-_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef(
-    _RequiredListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-    _OptionalListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-):
-    pass
-
-ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef = TypedDict(
-    "ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "ProvisionProductId": str,
-        "AccessLevelFilter": AccessLevelFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
-    "_RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    {
-        "ServiceActionId": str,
-    },
-)
-_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef = TypedDict(
-    "_OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef(
-    _RequiredListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-    _OptionalListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-):
-    pass
-
-_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+_RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     {
-        "TagOptionId": str,
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
     },
 )
-_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef",
+_OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef",
     {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FailureReason": str,
+        "Outputs": Sequence[RecordOutputTypeDef],
     },
     total=False,
 )
 
-class ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef(
-    _RequiredListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-    _OptionalListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-):
-    pass
-
-_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
-    "_RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
-    {
-        "ProductId": str,
-        "ProvisioningArtifactId": str,
-    },
-)
-_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef = TypedDict(
-    "_OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-class ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef(
-    _RequiredListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
-    _OptionalListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
+class NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
 ):
     pass
 
-ListServiceActionsInputListServiceActionsPaginateTypeDef = TypedDict(
-    "ListServiceActionsInputListServiceActionsPaginateTypeDef",
-    {
-        "AcceptLanguage": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef = TypedDict(
-    "ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef",
+DescribeServiceActionExecutionParametersOutputTypeDef = TypedDict(
+    "DescribeServiceActionExecutionParametersOutputTypeDef",
     {
-        "AcceptLanguage": str,
-        "AccessLevelFilter": AccessLevelFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ServiceActionParameters": List[ExecutionParameterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef = TypedDict(
-    "SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef",
+EngineWorkflowResourceIdentifierTypeDef = TypedDict(
+    "EngineWorkflowResourceIdentifierTypeDef",
     {
-        "AcceptLanguage": str,
-        "PortfolioId": str,
-        "Filters": Mapping[ProductViewFilterByType, Sequence[str]],
-        "SortBy": ProductViewSortByType,
-        "SortOrder": SortOrderType,
-        "ProductSource": Literal["ACCOUNT"],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "UniqueTag": UniqueTagResourceIdentifierTypeDef,
     },
     total=False,
 )
 
 ListPrincipalsForPortfolioOutputTypeDef = TypedDict(
     "ListPrincipalsForPortfolioOutputTypeDef",
     {
         "Principals": List[PrincipalTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisionedProductPlansOutputTypeDef = TypedDict(
     "ListProvisionedProductPlansOutputTypeDef",
     {
         "ProvisionedProductPlans": List[ProvisionedProductPlanSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordHistoryInputListRecordHistoryPaginateTypeDef = TypedDict(
     "ListRecordHistoryInputListRecordHistoryPaginateTypeDef",
     {
         "AcceptLanguage": str,
         "AccessLevelFilter": AccessLevelFilterTypeDef,
         "SearchFilter": ListRecordHistorySearchFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRecordHistoryInputRequestTypeDef = TypedDict(
     "ListRecordHistoryInputRequestTypeDef",
     {
@@ -2933,33 +3127,33 @@
 )
 
 ListResourcesForTagOptionOutputTypeDef = TypedDict(
     "ListResourcesForTagOptionOutputTypeDef",
     {
         "ResourceDetails": List[ResourceDetailTypeDef],
         "PageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceActionsForProvisioningArtifactOutputTypeDef = TypedDict(
     "ListServiceActionsForProvisioningArtifactOutputTypeDef",
     {
         "ServiceActionSummaries": List[ServiceActionSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceActionsOutputTypeDef = TypedDict(
     "ListServiceActionsOutputTypeDef",
     {
         "ServiceActionSummaries": List[ServiceActionSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceActionDetailTypeDef = TypedDict(
     "ServiceActionDetailTypeDef",
     {
         "ServiceActionSummary": ServiceActionSummaryTypeDef,
@@ -2969,23 +3163,23 @@
 )
 
 ListStackInstancesForProvisionedProductOutputTypeDef = TypedDict(
     "ListStackInstancesForProvisionedProductOutputTypeDef",
     {
         "StackInstances": List[StackInstanceTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagOptionsInputListTagOptionsPaginateTypeDef = TypedDict(
     "ListTagOptionsInputListTagOptionsPaginateTypeDef",
     {
         "Filters": ListTagOptionsFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTagOptionsInputRequestTypeDef = TypedDict(
     "ListTagOptionsInputRequestTypeDef",
     {
@@ -3011,15 +3205,15 @@
 
 SearchProductsOutputTypeDef = TypedDict(
     "SearchProductsOutputTypeDef",
     {
         "ProductViewSummaries": List[ProductViewSummaryTypeDef],
         "ProductViewAggregations": Dict[str, List[ProductViewAggregationValueTypeDef]],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredProvisionProductInputRequestTypeDef = TypedDict(
     "_RequiredProvisionProductInputRequestTypeDef",
     {
         "ProvisionedProductName": str,
@@ -3040,19 +3234,21 @@
         "ProvisioningPreferences": ProvisioningPreferencesTypeDef,
         "Tags": Sequence[TagTypeDef],
         "NotificationArns": Sequence[str],
     },
     total=False,
 )
 
+
 class ProvisionProductInputRequestTypeDef(
     _RequiredProvisionProductInputRequestTypeDef, _OptionalProvisionProductInputRequestTypeDef
 ):
     pass
 
+
 RecordDetailTypeDef = TypedDict(
     "RecordDetailTypeDef",
     {
         "RecordId": str,
         "ProvisionedProductName": str,
         "Status": RecordStatusType,
         "CreatedTime": datetime,
@@ -3110,20 +3306,22 @@
         "ProvisioningParameters": Sequence[UpdateProvisioningParameterTypeDef],
         "ProvisioningPreferences": UpdateProvisioningPreferencesTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class UpdateProvisionedProductInputRequestTypeDef(
     _RequiredUpdateProvisionedProductInputRequestTypeDef,
     _OptionalUpdateProvisionedProductInputRequestTypeDef,
 ):
     pass
 
+
 SourceConnectionDetailTypeDef = TypedDict(
     "SourceConnectionDetailTypeDef",
     {
         "Type": Literal["CODESTAR"],
         "ConnectionParameters": SourceConnectionParametersTypeDef,
         "LastSync": LastSyncTypeDef,
     },
@@ -3140,147 +3338,187 @@
     "_OptionalSourceConnectionTypeDef",
     {
         "Type": Literal["CODESTAR"],
     },
     total=False,
 )
 
+
 class SourceConnectionTypeDef(_RequiredSourceConnectionTypeDef, _OptionalSourceConnectionTypeDef):
     pass
 
+
 ListLaunchPathsOutputTypeDef = TypedDict(
     "ListLaunchPathsOutputTypeDef",
     {
         "LaunchPathSummaries": List[LaunchPathSummaryTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchProvisionedProductsOutputTypeDef = TypedDict(
     "SearchProvisionedProductsOutputTypeDef",
     {
         "ProvisionedProducts": List[ProvisionedProductAttributeTypeDef],
         "TotalResultsCount": int,
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningArtifactsForServiceActionOutputTypeDef = TypedDict(
     "ListProvisioningArtifactsForServiceActionOutputTypeDef",
     {
         "ProvisioningArtifactViews": List[ProvisioningArtifactViewTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "WorkflowToken": str,
+        "RecordId": str,
+        "Status": EngineWorkflowStatusType,
+        "IdempotencyToken": str,
+    },
+)
+_OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef = TypedDict(
+    "_OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef",
+    {
+        "FailureReason": str,
+        "ResourceIdentifier": EngineWorkflowResourceIdentifierTypeDef,
+        "Outputs": Sequence[RecordOutputTypeDef],
+    },
+    total=False,
+)
+
+
+class NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef(
+    _RequiredNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
+    _OptionalNotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
+):
+    pass
+
+
 CreateServiceActionOutputTypeDef = TypedDict(
     "CreateServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceActionOutputTypeDef = TypedDict(
     "DescribeServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceActionOutputTypeDef = TypedDict(
     "UpdateServiceActionOutputTypeDef",
     {
         "ServiceActionDetail": ServiceActionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProvisioningArtifactOutputTypeDef = TypedDict(
+    "DescribeProvisioningArtifactOutputTypeDef",
+    {
+        "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
+        "Info": Dict[str, str],
+        "Status": StatusType,
+        "ProvisioningArtifactParameters": List[ProvisioningArtifactParameterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProvisioningParametersOutputTypeDef = TypedDict(
     "DescribeProvisioningParametersOutputTypeDef",
     {
         "ProvisioningArtifactParameters": List[ProvisioningArtifactParameterTypeDef],
         "ConstraintSummaries": List[ConstraintSummaryTypeDef],
         "UsageInstructions": List[UsageInstructionTypeDef],
         "TagOptions": List[TagOptionSummaryTypeDef],
         "ProvisioningArtifactPreferences": ProvisioningArtifactPreferencesTypeDef,
         "ProvisioningArtifactOutputs": List[ProvisioningArtifactOutputTypeDef],
         "ProvisioningArtifactOutputKeys": List[ProvisioningArtifactOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecordOutputTypeDef = TypedDict(
     "DescribeRecordOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
         "RecordOutputs": List[RecordOutputTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteProvisionedProductPlanOutputTypeDef = TypedDict(
     "ExecuteProvisionedProductPlanOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteProvisionedProductServiceActionOutputTypeDef = TypedDict(
     "ExecuteProvisionedProductServiceActionOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportAsProvisionedProductOutputTypeDef = TypedDict(
     "ImportAsProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordHistoryOutputTypeDef = TypedDict(
     "ListRecordHistoryOutputTypeDef",
     {
         "RecordDetails": List[RecordDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionProductOutputTypeDef = TypedDict(
     "ProvisionProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TerminateProvisionedProductOutputTypeDef = TypedDict(
     "TerminateProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProvisionedProductOutputTypeDef = TypedDict(
     "UpdateProvisionedProductOutputTypeDef",
     {
         "RecordDetail": RecordDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceChangeTypeDef = TypedDict(
     "ResourceChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -3298,15 +3536,15 @@
     "DescribePortfolioShareStatusOutputTypeDef",
     {
         "PortfolioShareToken": str,
         "PortfolioId": str,
         "OrganizationNodeValue": str,
         "Status": ShareStatusType,
         "ShareDetails": ShareDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProductViewDetailTypeDef = TypedDict(
     "ProductViewDetailTypeDef",
     {
         "ProductViewSummary": ProductViewSummaryTypeDef,
@@ -3339,19 +3577,21 @@
         "Tags": Sequence[TagTypeDef],
         "ProvisioningArtifactParameters": ProvisioningArtifactPropertiesTypeDef,
         "SourceConnection": SourceConnectionTypeDef,
     },
     total=False,
 )
 
+
 class CreateProductInputRequestTypeDef(
     _RequiredCreateProductInputRequestTypeDef, _OptionalCreateProductInputRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateProductInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProductInputRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateProductInputRequestTypeDef = TypedDict(
@@ -3368,61 +3608,63 @@
         "AddTags": Sequence[TagTypeDef],
         "RemoveTags": Sequence[str],
         "SourceConnection": SourceConnectionTypeDef,
     },
     total=False,
 )
 
+
 class UpdateProductInputRequestTypeDef(
     _RequiredUpdateProductInputRequestTypeDef, _OptionalUpdateProductInputRequestTypeDef
 ):
     pass
 
+
 DescribeProvisionedProductPlanOutputTypeDef = TypedDict(
     "DescribeProvisionedProductPlanOutputTypeDef",
     {
         "ProvisionedProductPlanDetails": ProvisionedProductPlanDetailsTypeDef,
         "ResourceChanges": List[ResourceChangeTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProductOutputTypeDef = TypedDict(
     "CreateProductOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "ProvisioningArtifactDetail": ProvisioningArtifactDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProductAsAdminOutputTypeDef = TypedDict(
     "DescribeProductAsAdminOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "ProvisioningArtifactSummaries": List[ProvisioningArtifactSummaryTypeDef],
         "Tags": List[TagTypeDef],
         "TagOptions": List[TagOptionDetailTypeDef],
         "Budgets": List[BudgetDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchProductsAsAdminOutputTypeDef = TypedDict(
     "SearchProductsAsAdminOutputTypeDef",
     {
         "ProductViewDetails": List[ProductViewDetailTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProductOutputTypeDef = TypedDict(
     "UpdateProductOutputTypeDef",
     {
         "ProductViewDetail": ProductViewDetailTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/PKG-INFO` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicecatalog
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceCatalog 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceCatalog 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicecatalog"></a>
 
 # types-aiobotocore-servicecatalog
 
 [![PyPI - types-aiobotocore-servicecatalog](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
+[aiobotocore.ServiceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog.html#ServiceCatalog)
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
 [types-aiobotocore-servicecatalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,14 +358,15 @@
 from types_aiobotocore_servicecatalog.literals import (
     AccessLevelFilterKeyType,
     AccessStatusType,
     ChangeActionType,
     CopyOptionType,
     CopyProductStatusType,
     DescribePortfolioShareTypeType,
+    EngineWorkflowStatusType,
     EvaluationTypeType,
     LastSyncStatusType,
     ListAcceptedPortfolioSharesPaginatorName,
     ListConstraintsForPortfolioPaginatorName,
     ListLaunchPathsPaginatorName,
     ListOrganizationPortfolioAccessPaginatorName,
     ListPortfoliosForProductPaginatorName,
@@ -434,40 +435,44 @@
     AssociateBudgetWithResourceInputRequestTypeDef,
     AssociatePrincipalWithPortfolioInputRequestTypeDef,
     AssociateProductWithPortfolioInputRequestTypeDef,
     AssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     AssociateTagOptionWithResourceInputRequestTypeDef,
     ServiceActionAssociationTypeDef,
     FailedServiceActionAssociationTypeDef,
-    ResponseMetadataTypeDef,
     BudgetDetailTypeDef,
     CloudWatchDashboardTypeDef,
     CodeStarParametersTypeDef,
     ConstraintDetailTypeDef,
     ConstraintSummaryTypeDef,
     CopyProductInputRequestTypeDef,
+    CopyProductOutputTypeDef,
     CreateConstraintInputRequestTypeDef,
     TagTypeDef,
     PortfolioDetailTypeDef,
     OrganizationNodeTypeDef,
+    CreatePortfolioShareOutputTypeDef,
     ProvisioningArtifactPropertiesTypeDef,
     ProvisioningArtifactDetailTypeDef,
     UpdateProvisioningParameterTypeDef,
+    CreateProvisionedProductPlanOutputTypeDef,
     CreateServiceActionInputRequestTypeDef,
     CreateTagOptionInputRequestTypeDef,
     TagOptionDetailTypeDef,
     DeleteConstraintInputRequestTypeDef,
     DeletePortfolioInputRequestTypeDef,
+    DeletePortfolioShareOutputTypeDef,
     DeleteProductInputRequestTypeDef,
     DeleteProvisionedProductPlanInputRequestTypeDef,
     DeleteProvisioningArtifactInputRequestTypeDef,
     DeleteServiceActionInputRequestTypeDef,
     DeleteTagOptionInputRequestTypeDef,
     DescribeConstraintInputRequestTypeDef,
     DescribeCopyProductStatusInputRequestTypeDef,
+    DescribeCopyProductStatusOutputTypeDef,
     DescribePortfolioInputRequestTypeDef,
     DescribePortfolioShareStatusInputRequestTypeDef,
     DescribePortfolioSharesInputRequestTypeDef,
     PortfolioShareDetailTypeDef,
     DescribeProductAsAdminInputRequestTypeDef,
     ProvisioningArtifactSummaryTypeDef,
     DescribeProductInputRequestTypeDef,
@@ -491,76 +496,88 @@
     DescribeServiceActionInputRequestTypeDef,
     DescribeTagOptionInputRequestTypeDef,
     DisassociateBudgetFromResourceInputRequestTypeDef,
     DisassociatePrincipalFromPortfolioInputRequestTypeDef,
     DisassociateProductFromPortfolioInputRequestTypeDef,
     DisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     DisassociateTagOptionFromResourceInputRequestTypeDef,
+    UniqueTagResourceIdentifierTypeDef,
     ExecuteProvisionedProductPlanInputRequestTypeDef,
     ExecuteProvisionedProductServiceActionInputRequestTypeDef,
+    GetAWSOrganizationsAccessStatusOutputTypeDef,
     GetProvisionedProductOutputsInputRequestTypeDef,
     ImportAsProvisionedProductInputRequestTypeDef,
     LastSyncTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
     ListAcceptedPortfolioSharesInputRequestTypeDef,
     ListBudgetsForResourceInputRequestTypeDef,
+    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
     ListConstraintsForPortfolioInputRequestTypeDef,
+    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
     ListLaunchPathsInputRequestTypeDef,
+    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
     ListOrganizationPortfolioAccessInputRequestTypeDef,
     ListPortfolioAccessInputRequestTypeDef,
+    ListPortfolioAccessOutputTypeDef,
+    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
     ListPortfoliosForProductInputRequestTypeDef,
+    ListPortfoliosInputListPortfoliosPaginateTypeDef,
     ListPortfoliosInputRequestTypeDef,
+    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
     ListPrincipalsForPortfolioInputRequestTypeDef,
     PrincipalTypeDef,
     ProvisionedProductPlanSummaryTypeDef,
+    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
     ListProvisioningArtifactsForServiceActionInputRequestTypeDef,
     ListProvisioningArtifactsInputRequestTypeDef,
     ListRecordHistorySearchFilterTypeDef,
+    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
     ListResourcesForTagOptionInputRequestTypeDef,
     ResourceDetailTypeDef,
+    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
     ListServiceActionsForProvisioningArtifactInputRequestTypeDef,
     ServiceActionSummaryTypeDef,
+    ListServiceActionsInputListServiceActionsPaginateTypeDef,
     ListServiceActionsInputRequestTypeDef,
     ListStackInstancesForProvisionedProductInputRequestTypeDef,
     StackInstanceTypeDef,
     ListTagOptionsFiltersTypeDef,
+    NotifyTerminateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterConstraintsTypeDef,
     ProductViewAggregationValueTypeDef,
     ProvisioningParameterTypeDef,
     ProvisioningPreferencesTypeDef,
     RecordErrorTypeDef,
     RecordTagTypeDef,
     RejectPortfolioShareInputRequestTypeDef,
     ResourceTargetDefinitionTypeDef,
+    ResponseMetadataTypeDef,
     SearchProductsAsAdminInputRequestTypeDef,
+    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
     SearchProductsInputRequestTypeDef,
     ShareErrorTypeDef,
     TerminateProvisionedProductInputRequestTypeDef,
     UpdateConstraintInputRequestTypeDef,
+    UpdatePortfolioShareOutputTypeDef,
     UpdateProvisioningPreferencesTypeDef,
     UpdateProvisionedProductPropertiesInputRequestTypeDef,
+    UpdateProvisionedProductPropertiesOutputTypeDef,
     UpdateProvisioningArtifactInputRequestTypeDef,
     UpdateServiceActionInputRequestTypeDef,
     UpdateTagOptionInputRequestTypeDef,
+    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
     ListProvisionedProductPlansInputRequestTypeDef,
     ScanProvisionedProductsInputRequestTypeDef,
+    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
     SearchProvisionedProductsInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactInputRequestTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactInputRequestTypeDef,
     BatchAssociateServiceActionWithProvisioningArtifactOutputTypeDef,
     BatchDisassociateServiceActionFromProvisioningArtifactOutputTypeDef,
-    CopyProductOutputTypeDef,
-    CreatePortfolioShareOutputTypeDef,
-    CreateProvisionedProductPlanOutputTypeDef,
-    DeletePortfolioShareOutputTypeDef,
-    DescribeCopyProductStatusOutputTypeDef,
-    GetAWSOrganizationsAccessStatusOutputTypeDef,
-    ListPortfolioAccessOutputTypeDef,
-    UpdatePortfolioShareOutputTypeDef,
-    UpdateProvisionedProductPropertiesOutputTypeDef,
     ListBudgetsForResourceOutputTypeDef,
     SourceConnectionParametersTypeDef,
     CreateConstraintOutputTypeDef,
     DescribeConstraintOutputTypeDef,
     ListConstraintsForPortfolioOutputTypeDef,
     UpdateConstraintOutputTypeDef,
     CreatePortfolioInputRequestTypeDef,
@@ -574,15 +591,14 @@
     UpdatePortfolioOutputTypeDef,
     CreatePortfolioShareInputRequestTypeDef,
     DeletePortfolioShareInputRequestTypeDef,
     ListOrganizationPortfolioAccessOutputTypeDef,
     UpdatePortfolioShareInputRequestTypeDef,
     CreateProvisioningArtifactInputRequestTypeDef,
     CreateProvisioningArtifactOutputTypeDef,
-    DescribeProvisioningArtifactOutputTypeDef,
     ListProvisioningArtifactsOutputTypeDef,
     UpdateProvisioningArtifactOutputTypeDef,
     CreateProvisionedProductPlanInputRequestTypeDef,
     ProvisionedProductPlanDetailsTypeDef,
     CreateTagOptionOutputTypeDef,
     DescribePortfolioOutputTypeDef,
     DescribeTagOptionOutputTypeDef,
@@ -591,29 +607,17 @@
     DescribePortfolioSharesOutputTypeDef,
     DescribeProductOutputTypeDef,
     DescribeProductViewOutputTypeDef,
     ProvisioningArtifactViewTypeDef,
     DescribeProvisionedProductOutputTypeDef,
     ScanProvisionedProductsOutputTypeDef,
     GetProvisionedProductOutputsOutputTypeDef,
+    NotifyUpdateProvisionedProductEngineWorkflowResultInputRequestTypeDef,
     DescribeServiceActionExecutionParametersOutputTypeDef,
-    ListAcceptedPortfolioSharesInputListAcceptedPortfolioSharesPaginateTypeDef,
-    ListConstraintsForPortfolioInputListConstraintsForPortfolioPaginateTypeDef,
-    ListLaunchPathsInputListLaunchPathsPaginateTypeDef,
-    ListOrganizationPortfolioAccessInputListOrganizationPortfolioAccessPaginateTypeDef,
-    ListPortfoliosForProductInputListPortfoliosForProductPaginateTypeDef,
-    ListPortfoliosInputListPortfoliosPaginateTypeDef,
-    ListPrincipalsForPortfolioInputListPrincipalsForPortfolioPaginateTypeDef,
-    ListProvisionedProductPlansInputListProvisionedProductPlansPaginateTypeDef,
-    ListProvisioningArtifactsForServiceActionInputListProvisioningArtifactsForServiceActionPaginateTypeDef,
-    ListResourcesForTagOptionInputListResourcesForTagOptionPaginateTypeDef,
-    ListServiceActionsForProvisioningArtifactInputListServiceActionsForProvisioningArtifactPaginateTypeDef,
-    ListServiceActionsInputListServiceActionsPaginateTypeDef,
-    ScanProvisionedProductsInputScanProvisionedProductsPaginateTypeDef,
-    SearchProductsAsAdminInputSearchProductsAsAdminPaginateTypeDef,
+    EngineWorkflowResourceIdentifierTypeDef,
     ListPrincipalsForPortfolioOutputTypeDef,
     ListProvisionedProductPlansOutputTypeDef,
     ListRecordHistoryInputListRecordHistoryPaginateTypeDef,
     ListRecordHistoryInputRequestTypeDef,
     ListResourcesForTagOptionOutputTypeDef,
     ListServiceActionsForProvisioningArtifactOutputTypeDef,
     ListServiceActionsOutputTypeDef,
@@ -629,17 +633,19 @@
     ShareDetailsTypeDef,
     UpdateProvisionedProductInputRequestTypeDef,
     SourceConnectionDetailTypeDef,
     SourceConnectionTypeDef,
     ListLaunchPathsOutputTypeDef,
     SearchProvisionedProductsOutputTypeDef,
     ListProvisioningArtifactsForServiceActionOutputTypeDef,
+    NotifyProvisionProductEngineWorkflowResultInputRequestTypeDef,
     CreateServiceActionOutputTypeDef,
     DescribeServiceActionOutputTypeDef,
     UpdateServiceActionOutputTypeDef,
+    DescribeProvisioningArtifactOutputTypeDef,
     DescribeProvisioningParametersOutputTypeDef,
     DescribeRecordOutputTypeDef,
     ExecuteProvisionedProductPlanOutputTypeDef,
     ExecuteProvisionedProductServiceActionOutputTypeDef,
     ImportAsProvisionedProductOutputTypeDef,
     ListRecordHistoryOutputTypeDef,
     ProvisionProductOutputTypeDef,
@@ -665,43 +671,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-2.5.0.post1/types_aiobotocore_servicecatalog.egg-info/SOURCES.txt` & `types-aiobotocore-servicecatalog-2.5.1/types_aiobotocore_servicecatalog.egg-info/SOURCES.txt`

 * *Files identical despite different names*

