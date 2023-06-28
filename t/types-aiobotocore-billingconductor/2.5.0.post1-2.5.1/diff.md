# Comparing `tmp/types-aiobotocore-billingconductor-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-billingconductor-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-billingconductor-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-billingconductor-2.5.1.tar", last modified: Wed Jun 28 01:43:10 2023, max compression
```

## Comparing `types-aiobotocore-billingconductor-2.5.0.post1.tar` & `types-aiobotocore-billingconductor-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.394997 types-aiobotocore-billingconductor-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20858 2023-03-11 12:26:17.394997 types-aiobotocore-billingconductor-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19251 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.394997 types-aiobotocore-billingconductor-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.394997 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/
--rw-r--r--   0 runner    (1001) docker     (123)     3245 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3244 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    33540 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    33490 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9935 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9933 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15115 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    15102 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    42545 2023-03-11 12:10:12.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    42498 2023-03-11 12:10:12.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:11.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.394997 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20858 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:17.000000 types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.178101 types-aiobotocore-billingconductor-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20859 2023-06-28 01:43:10.178101 types-aiobotocore-billingconductor-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19258 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:10.178101 types-aiobotocore-billingconductor-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.166101 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/
+-rw-r--r--   0 runner    (1001) docker     (123)     3245 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3244 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33540 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33490 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10151 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10149 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15015 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15003 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    42812 2023-06-28 01:26:49.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42765 2023-06-28 01:26:48.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:47.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.178101 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20859 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:10.000000 types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/LICENSE` & `types-aiobotocore-billingconductor-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/PKG-INFO` & `types-aiobotocore-billingconductor-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-billingconductor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BillingConductor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BillingConductor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-billingconductor"></a>
 
 # types-aiobotocore-billingconductor
 
 [![PyPI - types-aiobotocore-billingconductor](https://img.shields.io/pypi/v/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-billingconductor?color=blue)](https://pypistats.org/packages/types-aiobotocore-billingconductor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BillingConductor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
+[aiobotocore.BillingConductor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
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
 [types-aiobotocore-billingconductor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -372,86 +372,86 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_billingconductor.type_defs import (
     AccountAssociationsListElementTypeDef,
     AccountGroupingTypeDef,
     AssociateAccountsInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAccountsOutputTypeDef,
     AssociatePricingRulesInputRequestTypeDef,
+    AssociatePricingRulesOutputTypeDef,
     AssociateResourceErrorTypeDef,
     CustomLineItemBillingPeriodRangeTypeDef,
     BillingGroupCostReportElementTypeDef,
     ComputationPreferenceTypeDef,
+    CreateBillingGroupOutputTypeDef,
+    CreateCustomLineItemOutputTypeDef,
     CreateFreeTierConfigTypeDef,
     CreatePricingPlanInputRequestTypeDef,
+    CreatePricingPlanOutputTypeDef,
+    CreatePricingRuleOutputTypeDef,
     CustomLineItemFlatChargeDetailsTypeDef,
     CustomLineItemPercentageChargeDetailsTypeDef,
     DeleteBillingGroupInputRequestTypeDef,
+    DeleteBillingGroupOutputTypeDef,
+    DeleteCustomLineItemOutputTypeDef,
     DeletePricingPlanInputRequestTypeDef,
+    DeletePricingPlanOutputTypeDef,
     DeletePricingRuleInputRequestTypeDef,
+    DeletePricingRuleOutputTypeDef,
     DisassociateAccountsInputRequestTypeDef,
+    DisassociateAccountsOutputTypeDef,
     DisassociatePricingRulesInputRequestTypeDef,
+    DisassociatePricingRulesOutputTypeDef,
     FreeTierConfigTypeDef,
     ListAccountAssociationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListBillingGroupCostReportsFilterTypeDef,
     ListBillingGroupsFilterTypeDef,
     ListCustomLineItemFlatChargeDetailsTypeDef,
     ListCustomLineItemPercentageChargeDetailsTypeDef,
     ListCustomLineItemVersionsBillingPeriodRangeFilterTypeDef,
     ListCustomLineItemsFilterTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
     ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
     ListPricingPlansFilterTypeDef,
     PricingPlanListElementTypeDef,
+    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
     ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
+    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
     ListPricingRulesFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemResponseElementTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBillingGroupOutputTypeDef,
     UpdateCustomLineItemFlatChargeDetailsTypeDef,
     UpdateCustomLineItemPercentageChargeDetailsTypeDef,
     UpdateFreeTierConfigTypeDef,
     UpdatePricingPlanInputRequestTypeDef,
-    AssociateAccountsOutputTypeDef,
-    AssociatePricingRulesOutputTypeDef,
-    CreateBillingGroupOutputTypeDef,
-    CreateCustomLineItemOutputTypeDef,
-    CreatePricingPlanOutputTypeDef,
-    CreatePricingRuleOutputTypeDef,
-    DeleteBillingGroupOutputTypeDef,
-    DeleteCustomLineItemOutputTypeDef,
-    DeletePricingPlanOutputTypeDef,
-    DeletePricingRuleOutputTypeDef,
-    DisassociateAccountsOutputTypeDef,
-    DisassociatePricingRulesOutputTypeDef,
-    ListAccountAssociationsOutputTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
-    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateBillingGroupOutputTypeDef,
     UpdatePricingPlanOutputTypeDef,
+    ListAccountAssociationsOutputTypeDef,
     AssociateResourceResponseElementTypeDef,
     DisassociateResourceResponseElementTypeDef,
     BatchAssociateResourcesToCustomLineItemInputRequestTypeDef,
     BatchDisassociateResourcesFromCustomLineItemInputRequestTypeDef,
     DeleteCustomLineItemInputRequestTypeDef,
     ListBillingGroupCostReportsOutputTypeDef,
     BillingGroupListElementTypeDef,
     CreateBillingGroupInputRequestTypeDef,
     UpdateBillingGroupInputRequestTypeDef,
     CreateTieringInputTypeDef,
     CustomLineItemChargeDetailsTypeDef,
     TieringTypeDef,
-    ListAccountAssociationsInputRequestTypeDef,
     ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+    ListAccountAssociationsInputRequestTypeDef,
     ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef,
     ListBillingGroupCostReportsInputRequestTypeDef,
     ListBillingGroupsInputListBillingGroupsPaginateTypeDef,
     ListBillingGroupsInputRequestTypeDef,
     ListCustomLineItemChargeDetailsTypeDef,
     ListCustomLineItemVersionsFilterTypeDef,
     ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef,
@@ -493,43 +493,43 @@
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/README.md` & `types-aiobotocore-billingconductor-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-billingconductor"></a>
 
 # types-aiobotocore-billingconductor
 
 [![PyPI - types-aiobotocore-billingconductor](https://img.shields.io/pypi/v/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-billingconductor?color=blue)](https://pypistats.org/packages/types-aiobotocore-billingconductor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BillingConductor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
+[aiobotocore.BillingConductor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
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
 [types-aiobotocore-billingconductor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,86 +339,86 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_billingconductor.type_defs import (
     AccountAssociationsListElementTypeDef,
     AccountGroupingTypeDef,
     AssociateAccountsInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAccountsOutputTypeDef,
     AssociatePricingRulesInputRequestTypeDef,
+    AssociatePricingRulesOutputTypeDef,
     AssociateResourceErrorTypeDef,
     CustomLineItemBillingPeriodRangeTypeDef,
     BillingGroupCostReportElementTypeDef,
     ComputationPreferenceTypeDef,
+    CreateBillingGroupOutputTypeDef,
+    CreateCustomLineItemOutputTypeDef,
     CreateFreeTierConfigTypeDef,
     CreatePricingPlanInputRequestTypeDef,
+    CreatePricingPlanOutputTypeDef,
+    CreatePricingRuleOutputTypeDef,
     CustomLineItemFlatChargeDetailsTypeDef,
     CustomLineItemPercentageChargeDetailsTypeDef,
     DeleteBillingGroupInputRequestTypeDef,
+    DeleteBillingGroupOutputTypeDef,
+    DeleteCustomLineItemOutputTypeDef,
     DeletePricingPlanInputRequestTypeDef,
+    DeletePricingPlanOutputTypeDef,
     DeletePricingRuleInputRequestTypeDef,
+    DeletePricingRuleOutputTypeDef,
     DisassociateAccountsInputRequestTypeDef,
+    DisassociateAccountsOutputTypeDef,
     DisassociatePricingRulesInputRequestTypeDef,
+    DisassociatePricingRulesOutputTypeDef,
     FreeTierConfigTypeDef,
     ListAccountAssociationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListBillingGroupCostReportsFilterTypeDef,
     ListBillingGroupsFilterTypeDef,
     ListCustomLineItemFlatChargeDetailsTypeDef,
     ListCustomLineItemPercentageChargeDetailsTypeDef,
     ListCustomLineItemVersionsBillingPeriodRangeFilterTypeDef,
     ListCustomLineItemsFilterTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
     ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
     ListPricingPlansFilterTypeDef,
     PricingPlanListElementTypeDef,
+    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
     ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
+    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
     ListPricingRulesFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemResponseElementTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBillingGroupOutputTypeDef,
     UpdateCustomLineItemFlatChargeDetailsTypeDef,
     UpdateCustomLineItemPercentageChargeDetailsTypeDef,
     UpdateFreeTierConfigTypeDef,
     UpdatePricingPlanInputRequestTypeDef,
-    AssociateAccountsOutputTypeDef,
-    AssociatePricingRulesOutputTypeDef,
-    CreateBillingGroupOutputTypeDef,
-    CreateCustomLineItemOutputTypeDef,
-    CreatePricingPlanOutputTypeDef,
-    CreatePricingRuleOutputTypeDef,
-    DeleteBillingGroupOutputTypeDef,
-    DeleteCustomLineItemOutputTypeDef,
-    DeletePricingPlanOutputTypeDef,
-    DeletePricingRuleOutputTypeDef,
-    DisassociateAccountsOutputTypeDef,
-    DisassociatePricingRulesOutputTypeDef,
-    ListAccountAssociationsOutputTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
-    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateBillingGroupOutputTypeDef,
     UpdatePricingPlanOutputTypeDef,
+    ListAccountAssociationsOutputTypeDef,
     AssociateResourceResponseElementTypeDef,
     DisassociateResourceResponseElementTypeDef,
     BatchAssociateResourcesToCustomLineItemInputRequestTypeDef,
     BatchDisassociateResourcesFromCustomLineItemInputRequestTypeDef,
     DeleteCustomLineItemInputRequestTypeDef,
     ListBillingGroupCostReportsOutputTypeDef,
     BillingGroupListElementTypeDef,
     CreateBillingGroupInputRequestTypeDef,
     UpdateBillingGroupInputRequestTypeDef,
     CreateTieringInputTypeDef,
     CustomLineItemChargeDetailsTypeDef,
     TieringTypeDef,
-    ListAccountAssociationsInputRequestTypeDef,
     ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+    ListAccountAssociationsInputRequestTypeDef,
     ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef,
     ListBillingGroupCostReportsInputRequestTypeDef,
     ListBillingGroupsInputListBillingGroupsPaginateTypeDef,
     ListBillingGroupsInputRequestTypeDef,
     ListCustomLineItemChargeDetailsTypeDef,
     ListCustomLineItemVersionsFilterTypeDef,
     ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef,
@@ -460,43 +460,43 @@
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/setup.py` & `types-aiobotocore-billingconductor-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-billingconductor.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-billingconductor",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_billingconductor"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.BillingConductor 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.BillingConductor 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/"
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__init__.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__init__.pyi` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/__main__.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/__main__.py`

 * *Files 7% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.BillingConductor 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.BillingConductor 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor\nOther"
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/client.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/client.pyi` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/literals.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -67,15 +67,15 @@
 ListPricingRulesAssociatedToPricingPlanPaginatorName = Literal[
     "list_pricing_rules_associated_to_pricing_plan"
 ]
 ListPricingRulesPaginatorName = Literal["list_pricing_rules"]
 ListResourcesAssociatedToCustomLineItemPaginatorName = Literal[
     "list_resources_associated_to_custom_line_item"
 ]
-PricingRuleScopeType = Literal["BILLING_ENTITY", "GLOBAL", "SERVICE"]
+PricingRuleScopeType = Literal["BILLING_ENTITY", "GLOBAL", "SERVICE", "SKU"]
 PricingRuleTypeType = Literal["DISCOUNT", "MARKUP", "TIERING"]
 BillingConductorServiceName = Literal["billingconductor"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -132,14 +132,15 @@
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
@@ -218,14 +219,15 @@
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
@@ -236,14 +238,15 @@
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
@@ -279,14 +282,15 @@
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
@@ -305,16 +309,19 @@
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
@@ -398,15 +405,17 @@
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/literals.pyi` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -65,15 +65,15 @@
 ListPricingRulesAssociatedToPricingPlanPaginatorName = Literal[
     "list_pricing_rules_associated_to_pricing_plan"
 ]
 ListPricingRulesPaginatorName = Literal["list_pricing_rules"]
 ListResourcesAssociatedToCustomLineItemPaginatorName = Literal[
     "list_resources_associated_to_custom_line_item"
 ]
-PricingRuleScopeType = Literal["BILLING_ENTITY", "GLOBAL", "SERVICE"]
+PricingRuleScopeType = Literal["BILLING_ENTITY", "GLOBAL", "SERVICE", "SKU"]
 PricingRuleTypeType = Literal["DISCOUNT", "MARKUP", "TIERING"]
 BillingConductorServiceName = Literal["billingconductor"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -130,14 +130,15 @@
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
@@ -216,14 +217,15 @@
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
@@ -234,14 +236,15 @@
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
@@ -277,14 +280,15 @@
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
@@ -303,16 +307,19 @@
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
@@ -396,15 +403,17 @@
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/paginator.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_pricing_plans_paginator: ListPricingPlansPaginator = client.get_paginator("list_pricing_plans")
         list_pricing_plans_associated_with_pricing_rule_paginator: ListPricingPlansAssociatedWithPricingRulePaginator = client.get_paginator("list_pricing_plans_associated_with_pricing_rule")
         list_pricing_rules_paginator: ListPricingRulesPaginator = client.get_paginator("list_pricing_rules")
         list_pricing_rules_associated_to_pricing_plan_paginator: ListPricingRulesAssociatedToPricingPlanPaginator = client.get_paginator("list_pricing_rules_associated_to_pricing_plan")
         list_resources_associated_to_custom_line_item_paginator: ListResourcesAssociatedToCustomLineItemPaginator = client.get_paginator("list_resources_associated_to_custom_line_item")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAccountAssociationsFilterTypeDef,
     ListAccountAssociationsOutputTypeDef,
@@ -62,20 +61,14 @@
     ListPricingRulesFilterTypeDef,
     ListPricingRulesOutputTypeDef,
     ListResourcesAssociatedToCustomLineItemFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAccountAssociationsPaginator",
     "ListBillingGroupCostReportsPaginator",
     "ListBillingGroupsPaginator",
     "ListCustomLineItemVersionsPaginator",
     "ListCustomLineItemsPaginator",
     "ListPricingPlansPaginator",
@@ -103,15 +96,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListAccountAssociationsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssociationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListAccountAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listaccountassociationspaginator)
         """
 
 
@@ -122,15 +115,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListBillingGroupCostReportsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupCostReportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListBillingGroupCostReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listbillinggroupcostreportspaginator)
         """
 
 
@@ -141,15 +134,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListBillingGroupsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListBillingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listbillinggroupspaginator)
         """
 
 
@@ -160,15 +153,15 @@
     """
 
     def paginate(
         self,
         *,
         Arn: str,
         Filters: ListCustomLineItemVersionsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomLineItemVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListCustomLineItemVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listcustomlineitemversionspaginator)
         """
 
 
@@ -179,15 +172,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListCustomLineItemsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomLineItemsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListCustomLineItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listcustomlineitemspaginator)
         """
 
 
@@ -198,15 +191,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListPricingPlansFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingplanspaginator)
         """
 
 
@@ -217,15 +210,15 @@
     """
 
     def paginate(
         self,
         *,
         PricingRuleArn: str,
         BillingPeriod: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingPlansAssociatedWithPricingRuleOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingPlansAssociatedWithPricingRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingplansassociatedwithpricingrulepaginator)
         """
 
 
@@ -236,15 +229,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListPricingRulesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingRulesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingrulespaginator)
         """
 
 
@@ -255,15 +248,15 @@
     """
 
     def paginate(
         self,
         *,
         PricingPlanArn: str,
         BillingPeriod: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingRulesAssociatedToPricingPlanOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingRulesAssociatedToPricingPlan.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingrulesassociatedtopricingplanpaginator)
         """
 
 
@@ -275,13 +268,13 @@
 
     def paginate(
         self,
         *,
         Arn: str,
         BillingPeriod: str = ...,
         Filters: ListResourcesAssociatedToCustomLineItemFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesAssociatedToCustomLineItemOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListResourcesAssociatedToCustomLineItem.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listresourcesassociatedtocustomlineitempaginator)
         """
```

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/paginator.pyi` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_pricing_plans_paginator: ListPricingPlansPaginator = client.get_paginator("list_pricing_plans")
         list_pricing_plans_associated_with_pricing_rule_paginator: ListPricingPlansAssociatedWithPricingRulePaginator = client.get_paginator("list_pricing_plans_associated_with_pricing_rule")
         list_pricing_rules_paginator: ListPricingRulesPaginator = client.get_paginator("list_pricing_rules")
         list_pricing_rules_associated_to_pricing_plan_paginator: ListPricingRulesAssociatedToPricingPlanPaginator = client.get_paginator("list_pricing_rules_associated_to_pricing_plan")
         list_resources_associated_to_custom_line_item_paginator: ListResourcesAssociatedToCustomLineItemPaginator = client.get_paginator("list_resources_associated_to_custom_line_item")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAccountAssociationsFilterTypeDef,
     ListAccountAssociationsOutputTypeDef,
@@ -62,19 +61,14 @@
     ListPricingRulesFilterTypeDef,
     ListPricingRulesOutputTypeDef,
     ListResourcesAssociatedToCustomLineItemFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAccountAssociationsPaginator",
     "ListBillingGroupCostReportsPaginator",
     "ListBillingGroupsPaginator",
     "ListCustomLineItemVersionsPaginator",
     "ListCustomLineItemsPaginator",
     "ListPricingPlansPaginator",
@@ -99,15 +93,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListAccountAssociationsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountAssociationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListAccountAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listaccountassociationspaginator)
         """
 
 class ListBillingGroupCostReportsPaginator(AioPaginator):
@@ -117,15 +111,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListBillingGroupCostReportsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupCostReportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListBillingGroupCostReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listbillinggroupcostreportspaginator)
         """
 
 class ListBillingGroupsPaginator(AioPaginator):
@@ -135,15 +129,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListBillingGroupsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListBillingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listbillinggroupspaginator)
         """
 
 class ListCustomLineItemVersionsPaginator(AioPaginator):
@@ -153,15 +147,15 @@
     """
 
     def paginate(
         self,
         *,
         Arn: str,
         Filters: ListCustomLineItemVersionsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomLineItemVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListCustomLineItemVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listcustomlineitemversionspaginator)
         """
 
 class ListCustomLineItemsPaginator(AioPaginator):
@@ -171,15 +165,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListCustomLineItemsFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomLineItemsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListCustomLineItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listcustomlineitemspaginator)
         """
 
 class ListPricingPlansPaginator(AioPaginator):
@@ -189,15 +183,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListPricingPlansFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingplanspaginator)
         """
 
 class ListPricingPlansAssociatedWithPricingRulePaginator(AioPaginator):
@@ -207,15 +201,15 @@
     """
 
     def paginate(
         self,
         *,
         PricingRuleArn: str,
         BillingPeriod: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingPlansAssociatedWithPricingRuleOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingPlansAssociatedWithPricingRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingplansassociatedwithpricingrulepaginator)
         """
 
 class ListPricingRulesPaginator(AioPaginator):
@@ -225,15 +219,15 @@
     """
 
     def paginate(
         self,
         *,
         BillingPeriod: str = ...,
         Filters: ListPricingRulesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingRulesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingrulespaginator)
         """
 
 class ListPricingRulesAssociatedToPricingPlanPaginator(AioPaginator):
@@ -243,15 +237,15 @@
     """
 
     def paginate(
         self,
         *,
         PricingPlanArn: str,
         BillingPeriod: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricingRulesAssociatedToPricingPlanOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListPricingRulesAssociatedToPricingPlan.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listpricingrulesassociatedtopricingplanpaginator)
         """
 
 class ListResourcesAssociatedToCustomLineItemPaginator(AioPaginator):
@@ -262,13 +256,13 @@
 
     def paginate(
         self,
         *,
         Arn: str,
         BillingPeriod: str = ...,
         Filters: ListResourcesAssociatedToCustomLineItemFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesAssociatedToCustomLineItemOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor.Paginator.ListResourcesAssociatedToCustomLineItem.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/paginators/#listresourcesassociatedtocustomlineitempaginator)
         """
```

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/type_defs.py` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,86 +30,86 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountAssociationsListElementTypeDef",
     "AccountGroupingTypeDef",
     "AssociateAccountsInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateAccountsOutputTypeDef",
     "AssociatePricingRulesInputRequestTypeDef",
+    "AssociatePricingRulesOutputTypeDef",
     "AssociateResourceErrorTypeDef",
     "CustomLineItemBillingPeriodRangeTypeDef",
     "BillingGroupCostReportElementTypeDef",
     "ComputationPreferenceTypeDef",
+    "CreateBillingGroupOutputTypeDef",
+    "CreateCustomLineItemOutputTypeDef",
     "CreateFreeTierConfigTypeDef",
     "CreatePricingPlanInputRequestTypeDef",
+    "CreatePricingPlanOutputTypeDef",
+    "CreatePricingRuleOutputTypeDef",
     "CustomLineItemFlatChargeDetailsTypeDef",
     "CustomLineItemPercentageChargeDetailsTypeDef",
     "DeleteBillingGroupInputRequestTypeDef",
+    "DeleteBillingGroupOutputTypeDef",
+    "DeleteCustomLineItemOutputTypeDef",
     "DeletePricingPlanInputRequestTypeDef",
+    "DeletePricingPlanOutputTypeDef",
     "DeletePricingRuleInputRequestTypeDef",
+    "DeletePricingRuleOutputTypeDef",
     "DisassociateAccountsInputRequestTypeDef",
+    "DisassociateAccountsOutputTypeDef",
     "DisassociatePricingRulesInputRequestTypeDef",
+    "DisassociatePricingRulesOutputTypeDef",
     "FreeTierConfigTypeDef",
     "ListAccountAssociationsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListBillingGroupCostReportsFilterTypeDef",
     "ListBillingGroupsFilterTypeDef",
     "ListCustomLineItemFlatChargeDetailsTypeDef",
     "ListCustomLineItemPercentageChargeDetailsTypeDef",
     "ListCustomLineItemVersionsBillingPeriodRangeFilterTypeDef",
     "ListCustomLineItemsFilterTypeDef",
+    "ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
     "ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef",
+    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
     "ListPricingPlansFilterTypeDef",
     "PricingPlanListElementTypeDef",
+    "ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
     "ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef",
+    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
     "ListPricingRulesFilterTypeDef",
     "ListResourcesAssociatedToCustomLineItemFilterTypeDef",
     "ListResourcesAssociatedToCustomLineItemResponseElementTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateBillingGroupOutputTypeDef",
     "UpdateCustomLineItemFlatChargeDetailsTypeDef",
     "UpdateCustomLineItemPercentageChargeDetailsTypeDef",
     "UpdateFreeTierConfigTypeDef",
     "UpdatePricingPlanInputRequestTypeDef",
-    "AssociateAccountsOutputTypeDef",
-    "AssociatePricingRulesOutputTypeDef",
-    "CreateBillingGroupOutputTypeDef",
-    "CreateCustomLineItemOutputTypeDef",
-    "CreatePricingPlanOutputTypeDef",
-    "CreatePricingRuleOutputTypeDef",
-    "DeleteBillingGroupOutputTypeDef",
-    "DeleteCustomLineItemOutputTypeDef",
-    "DeletePricingPlanOutputTypeDef",
-    "DeletePricingRuleOutputTypeDef",
-    "DisassociateAccountsOutputTypeDef",
-    "DisassociatePricingRulesOutputTypeDef",
-    "ListAccountAssociationsOutputTypeDef",
-    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
-    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateBillingGroupOutputTypeDef",
     "UpdatePricingPlanOutputTypeDef",
+    "ListAccountAssociationsOutputTypeDef",
     "AssociateResourceResponseElementTypeDef",
     "DisassociateResourceResponseElementTypeDef",
     "BatchAssociateResourcesToCustomLineItemInputRequestTypeDef",
     "BatchDisassociateResourcesFromCustomLineItemInputRequestTypeDef",
     "DeleteCustomLineItemInputRequestTypeDef",
     "ListBillingGroupCostReportsOutputTypeDef",
     "BillingGroupListElementTypeDef",
     "CreateBillingGroupInputRequestTypeDef",
     "UpdateBillingGroupInputRequestTypeDef",
     "CreateTieringInputTypeDef",
     "CustomLineItemChargeDetailsTypeDef",
     "TieringTypeDef",
-    "ListAccountAssociationsInputRequestTypeDef",
     "ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef",
-    "ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    "ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    "ListAccountAssociationsInputRequestTypeDef",
     "ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef",
     "ListBillingGroupCostReportsInputRequestTypeDef",
     "ListBillingGroupsInputListBillingGroupsPaginateTypeDef",
     "ListBillingGroupsInputRequestTypeDef",
     "ListCustomLineItemChargeDetailsTypeDef",
     "ListCustomLineItemVersionsFilterTypeDef",
     "ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef",
@@ -165,33 +165,38 @@
     "AssociateAccountsInputRequestTypeDef",
     {
         "Arn": str,
         "AccountIds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateAccountsOutputTypeDef = TypedDict(
+    "AssociateAccountsOutputTypeDef",
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
 
 AssociatePricingRulesInputRequestTypeDef = TypedDict(
     "AssociatePricingRulesInputRequestTypeDef",
     {
         "Arn": str,
         "PricingRuleArns": Sequence[str],
     },
 )
 
+AssociatePricingRulesOutputTypeDef = TypedDict(
+    "AssociatePricingRulesOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateResourceErrorTypeDef = TypedDict(
     "AssociateResourceErrorTypeDef",
     {
         "Message": str,
         "Reason": AssociateResourceErrorReasonType,
     },
     total=False,
@@ -235,14 +240,30 @@
 ComputationPreferenceTypeDef = TypedDict(
     "ComputationPreferenceTypeDef",
     {
         "PricingPlanArn": str,
     },
 )
 
+CreateBillingGroupOutputTypeDef = TypedDict(
+    "CreateBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomLineItemOutputTypeDef = TypedDict(
+    "CreateCustomLineItemOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateFreeTierConfigTypeDef = TypedDict(
     "CreateFreeTierConfigTypeDef",
     {
         "Activated": bool,
     },
 )
 
@@ -266,14 +287,30 @@
 
 class CreatePricingPlanInputRequestTypeDef(
     _RequiredCreatePricingPlanInputRequestTypeDef, _OptionalCreatePricingPlanInputRequestTypeDef
 ):
     pass
 
 
+CreatePricingPlanOutputTypeDef = TypedDict(
+    "CreatePricingPlanOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePricingRuleOutputTypeDef = TypedDict(
+    "CreatePricingRuleOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "CustomLineItemFlatChargeDetailsTypeDef",
     {
         "ChargeValue": float,
     },
 )
 
@@ -302,66 +339,105 @@
 DeleteBillingGroupInputRequestTypeDef = TypedDict(
     "DeleteBillingGroupInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteBillingGroupOutputTypeDef = TypedDict(
+    "DeleteBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteCustomLineItemOutputTypeDef = TypedDict(
+    "DeleteCustomLineItemOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePricingPlanInputRequestTypeDef = TypedDict(
     "DeletePricingPlanInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeletePricingPlanOutputTypeDef = TypedDict(
+    "DeletePricingPlanOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePricingRuleInputRequestTypeDef = TypedDict(
     "DeletePricingRuleInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeletePricingRuleOutputTypeDef = TypedDict(
+    "DeletePricingRuleOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateAccountsInputRequestTypeDef = TypedDict(
     "DisassociateAccountsInputRequestTypeDef",
     {
         "Arn": str,
         "AccountIds": Sequence[str],
     },
 )
 
+DisassociateAccountsOutputTypeDef = TypedDict(
+    "DisassociateAccountsOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociatePricingRulesInputRequestTypeDef = TypedDict(
     "DisassociatePricingRulesInputRequestTypeDef",
     {
         "Arn": str,
         "PricingRuleArns": Sequence[str],
     },
 )
 
+DisassociatePricingRulesOutputTypeDef = TypedDict(
+    "DisassociatePricingRulesOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FreeTierConfigTypeDef = TypedDict(
     "FreeTierConfigTypeDef",
     {
         "Activated": bool,
     },
 )
 
 ListAccountAssociationsFilterTypeDef = TypedDict(
     "ListAccountAssociationsFilterTypeDef",
     {
         "Association": str,
         "AccountId": str,
-    },
-    total=False,
-)
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AccountIds": Sequence[str],
     },
     total=False,
 )
 
 ListBillingGroupCostReportsFilterTypeDef = TypedDict(
     "ListBillingGroupCostReportsFilterTypeDef",
     {
@@ -371,14 +447,15 @@
 )
 
 ListBillingGroupsFilterTypeDef = TypedDict(
     "ListBillingGroupsFilterTypeDef",
     {
         "Arns": Sequence[str],
         "PricingPlan": str,
+        "Statuses": Sequence[BillingGroupStatusType],
     },
     total=False,
 )
 
 ListCustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "ListCustomLineItemFlatChargeDetailsTypeDef",
     {
@@ -408,14 +485,37 @@
         "Names": Sequence[str],
         "BillingGroups": Sequence[str],
         "Arns": Sequence[str],
     },
     total=False,
 )
 
+_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
+    "_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
+    {
+        "PricingRuleArn": str,
+    },
+)
+_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
+    "_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
+    {
+        "BillingPeriod": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef(
+    _RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
+    _OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef = TypedDict(
     "_RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef",
     {
         "PricingRuleArn": str,
     },
 )
 _OptionalListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef = TypedDict(
@@ -432,14 +532,25 @@
 class ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef(
     _RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
     _OptionalListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
 ):
     pass
 
 
+ListPricingPlansAssociatedWithPricingRuleOutputTypeDef = TypedDict(
+    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
+    {
+        "BillingPeriod": str,
+        "PricingRuleArn": str,
+        "PricingPlanArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPricingPlansFilterTypeDef = TypedDict(
     "ListPricingPlansFilterTypeDef",
     {
         "Arns": Sequence[str],
     },
     total=False,
 )
@@ -453,14 +564,37 @@
         "Size": int,
         "CreationTime": int,
         "LastModifiedTime": int,
     },
     total=False,
 )
 
+_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
+    "_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    {
+        "PricingPlanArn": str,
+    },
+)
+_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
+    "_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    {
+        "BillingPeriod": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef(
+    _RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+    _OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef = TypedDict(
     "_RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef",
     {
         "PricingPlanArn": str,
     },
 )
 _OptionalListPricingRulesAssociatedToPricingPlanInputRequestTypeDef = TypedDict(
@@ -477,14 +611,25 @@
 class ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef(
     _RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
     _OptionalListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
 ):
     pass
 
 
+ListPricingRulesAssociatedToPricingPlanOutputTypeDef = TypedDict(
+    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
+    {
+        "BillingPeriod": str,
+        "PricingPlanArn": str,
+        "PricingRuleArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPricingRulesFilterTypeDef = TypedDict(
     "ListPricingRulesFilterTypeDef",
     {
         "Arns": Sequence[str],
     },
     total=False,
 )
@@ -510,14 +655,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -526,14 +700,30 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateBillingGroupOutputTypeDef = TypedDict(
+    "UpdateBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Description": str,
+        "PrimaryAccountId": str,
+        "PricingPlanArn": str,
+        "Size": int,
+        "LastModifiedTime": int,
+        "Status": BillingGroupStatusType,
+        "StatusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateCustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "UpdateCustomLineItemFlatChargeDetailsTypeDef",
     {
         "ChargeValue": float,
     },
 )
 
@@ -569,174 +759,32 @@
 
 class UpdatePricingPlanInputRequestTypeDef(
     _RequiredUpdatePricingPlanInputRequestTypeDef, _OptionalUpdatePricingPlanInputRequestTypeDef
 ):
     pass
 
 
-AssociateAccountsOutputTypeDef = TypedDict(
-    "AssociateAccountsOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociatePricingRulesOutputTypeDef = TypedDict(
-    "AssociatePricingRulesOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBillingGroupOutputTypeDef = TypedDict(
-    "CreateBillingGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomLineItemOutputTypeDef = TypedDict(
-    "CreateCustomLineItemOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePricingPlanOutputTypeDef = TypedDict(
-    "CreatePricingPlanOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePricingRuleOutputTypeDef = TypedDict(
-    "CreatePricingRuleOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBillingGroupOutputTypeDef = TypedDict(
-    "DeleteBillingGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomLineItemOutputTypeDef = TypedDict(
-    "DeleteCustomLineItemOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePricingPlanOutputTypeDef = TypedDict(
-    "DeletePricingPlanOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePricingRuleOutputTypeDef = TypedDict(
-    "DeletePricingRuleOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateAccountsOutputTypeDef = TypedDict(
-    "DisassociateAccountsOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePricingRulesOutputTypeDef = TypedDict(
-    "DisassociatePricingRulesOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssociationsOutputTypeDef = TypedDict(
-    "ListAccountAssociationsOutputTypeDef",
-    {
-        "LinkedAccounts": List[AccountAssociationsListElementTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPricingPlansAssociatedWithPricingRuleOutputTypeDef = TypedDict(
-    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
-    {
-        "BillingPeriod": str,
-        "PricingRuleArn": str,
-        "PricingPlanArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPricingRulesAssociatedToPricingPlanOutputTypeDef = TypedDict(
-    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
-    {
-        "BillingPeriod": str,
-        "PricingPlanArn": str,
-        "PricingRuleArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBillingGroupOutputTypeDef = TypedDict(
-    "UpdateBillingGroupOutputTypeDef",
+UpdatePricingPlanOutputTypeDef = TypedDict(
+    "UpdatePricingPlanOutputTypeDef",
     {
         "Arn": str,
         "Name": str,
         "Description": str,
-        "PrimaryAccountId": str,
-        "PricingPlanArn": str,
         "Size": int,
         "LastModifiedTime": int,
-        "Status": BillingGroupStatusType,
-        "StatusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdatePricingPlanOutputTypeDef = TypedDict(
-    "UpdatePricingPlanOutputTypeDef",
+ListAccountAssociationsOutputTypeDef = TypedDict(
+    "ListAccountAssociationsOutputTypeDef",
     {
-        "Arn": str,
-        "Name": str,
-        "Description": str,
-        "Size": int,
-        "LastModifiedTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "LinkedAccounts": List[AccountAssociationsListElementTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResourceResponseElementTypeDef = TypedDict(
     "AssociateResourceResponseElementTypeDef",
     {
         "Arn": str,
@@ -823,15 +871,15 @@
 
 
 ListBillingGroupCostReportsOutputTypeDef = TypedDict(
     "ListBillingGroupCostReportsOutputTypeDef",
     {
         "BillingGroupCostReports": List[BillingGroupCostReportElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BillingGroupListElementTypeDef = TypedDict(
     "BillingGroupListElementTypeDef",
     {
         "Name": str,
@@ -930,86 +978,40 @@
 TieringTypeDef = TypedDict(
     "TieringTypeDef",
     {
         "FreeTier": FreeTierConfigTypeDef,
     },
 )
 
-ListAccountAssociationsInputRequestTypeDef = TypedDict(
-    "ListAccountAssociationsInputRequestTypeDef",
-    {
-        "BillingPeriod": str,
-        "Filters": ListAccountAssociationsFilterTypeDef,
-        "NextToken": str,
-    },
-    total=False,
-)
-
 ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef = TypedDict(
     "ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListAccountAssociationsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
-    "_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    {
-        "PricingRuleArn": str,
-    },
-)
-_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
-    "_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    {
-        "BillingPeriod": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef(
-    _RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-    _OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
-    "_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
-    {
-        "PricingPlanArn": str,
-    },
-)
-_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
-    "_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+ListAccountAssociationsInputRequestTypeDef = TypedDict(
+    "ListAccountAssociationsInputRequestTypeDef",
     {
         "BillingPeriod": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": ListAccountAssociationsFilterTypeDef,
+        "NextToken": str,
     },
     total=False,
 )
 
-
-class ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef(
-    _RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
-    _OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
-):
-    pass
-
-
 ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef = TypedDict(
     "ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListBillingGroupCostReportsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBillingGroupCostReportsInputRequestTypeDef = TypedDict(
     "ListBillingGroupCostReportsInputRequestTypeDef",
     {
@@ -1022,15 +1024,15 @@
 )
 
 ListBillingGroupsInputListBillingGroupsPaginateTypeDef = TypedDict(
     "ListBillingGroupsInputListBillingGroupsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListBillingGroupsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBillingGroupsInputRequestTypeDef = TypedDict(
     "ListBillingGroupsInputRequestTypeDef",
     {
@@ -1073,15 +1075,15 @@
 )
 
 ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef = TypedDict(
     "ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListCustomLineItemsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCustomLineItemsInputRequestTypeDef = TypedDict(
     "ListCustomLineItemsInputRequestTypeDef",
     {
@@ -1094,15 +1096,15 @@
 )
 
 ListPricingPlansInputListPricingPlansPaginateTypeDef = TypedDict(
     "ListPricingPlansInputListPricingPlansPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListPricingPlansFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPricingPlansInputRequestTypeDef = TypedDict(
     "ListPricingPlansInputRequestTypeDef",
     {
@@ -1116,24 +1118,24 @@
 
 ListPricingPlansOutputTypeDef = TypedDict(
     "ListPricingPlansOutputTypeDef",
     {
         "BillingPeriod": str,
         "PricingPlans": List[PricingPlanListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPricingRulesInputListPricingRulesPaginateTypeDef = TypedDict(
     "ListPricingRulesInputListPricingRulesPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListPricingRulesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPricingRulesInputRequestTypeDef = TypedDict(
     "ListPricingRulesInputRequestTypeDef",
     {
@@ -1152,15 +1154,15 @@
     },
 )
 _OptionalListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef = TypedDict(
     "_OptionalListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListResourcesAssociatedToCustomLineItemFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef(
     _RequiredListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef,
@@ -1196,15 +1198,15 @@
 
 ListResourcesAssociatedToCustomLineItemOutputTypeDef = TypedDict(
     "ListResourcesAssociatedToCustomLineItemOutputTypeDef",
     {
         "Arn": str,
         "AssociatedResources": List[ListResourcesAssociatedToCustomLineItemResponseElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomLineItemChargeDetailsTypeDef = TypedDict(
     "UpdateCustomLineItemChargeDetailsTypeDef",
     {
         "Flat": UpdateCustomLineItemFlatChargeDetailsTypeDef,
@@ -1221,33 +1223,33 @@
 )
 
 BatchAssociateResourcesToCustomLineItemOutputTypeDef = TypedDict(
     "BatchAssociateResourcesToCustomLineItemOutputTypeDef",
     {
         "SuccessfullyAssociatedResources": List[AssociateResourceResponseElementTypeDef],
         "FailedAssociatedResources": List[AssociateResourceResponseElementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateResourcesFromCustomLineItemOutputTypeDef = TypedDict(
     "BatchDisassociateResourcesFromCustomLineItemOutputTypeDef",
     {
         "SuccessfullyDisassociatedResources": List[DisassociateResourceResponseElementTypeDef],
         "FailedDisassociatedResources": List[DisassociateResourceResponseElementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBillingGroupsOutputTypeDef = TypedDict(
     "ListBillingGroupsOutputTypeDef",
     {
         "BillingGroups": List[BillingGroupListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePricingRuleInputRequestTypeDef = TypedDict(
     "_RequiredCreatePricingRuleInputRequestTypeDef",
     {
         "Name": str,
@@ -1316,14 +1318,16 @@
         "ModifierPercentage": float,
         "Service": str,
         "AssociatedPricingPlanCount": int,
         "CreationTime": int,
         "LastModifiedTime": int,
         "BillingEntity": str,
         "Tiering": TieringTypeDef,
+        "UsageType": str,
+        "Operation": str,
     },
     total=False,
 )
 
 CustomLineItemListElementTypeDef = TypedDict(
     "CustomLineItemListElementTypeDef",
     {
@@ -1351,43 +1355,45 @@
         "ProductCode": str,
         "BillingGroupArn": str,
         "CreationTime": int,
         "LastModifiedTime": int,
         "AssociationSize": int,
         "StartBillingPeriod": str,
         "EndBillingPeriod": str,
+        "Arn": str,
+        "StartTime": int,
     },
     total=False,
 )
 
 UpdateCustomLineItemOutputTypeDef = TypedDict(
     "UpdateCustomLineItemOutputTypeDef",
     {
         "Arn": str,
         "BillingGroupArn": str,
         "Name": str,
         "Description": str,
         "ChargeDetails": ListCustomLineItemChargeDetailsTypeDef,
         "LastModifiedTime": int,
         "AssociationSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef = TypedDict(
     "_RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef",
     {
         "Arn": str,
     },
 )
 _OptionalListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef = TypedDict(
     "_OptionalListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef",
     {
         "Filters": ListCustomLineItemVersionsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef(
     _RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef,
@@ -1482,38 +1488,38 @@
         "Service": str,
         "AssociatedPricingPlanCount": int,
         "LastModifiedTime": int,
         "BillingEntity": str,
         "Tiering": UpdateTieringInputTypeDef,
         "UsageType": str,
         "Operation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPricingRulesOutputTypeDef = TypedDict(
     "ListPricingRulesOutputTypeDef",
     {
         "BillingPeriod": str,
         "PricingRules": List[PricingRuleListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomLineItemsOutputTypeDef = TypedDict(
     "ListCustomLineItemsOutputTypeDef",
     {
         "CustomLineItems": List[CustomLineItemListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomLineItemVersionsOutputTypeDef = TypedDict(
     "ListCustomLineItemVersionsOutputTypeDef",
     {
         "CustomLineItemVersions": List[CustomLineItemVersionListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor/type_defs.pyi` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -29,86 +29,86 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountAssociationsListElementTypeDef",
     "AccountGroupingTypeDef",
     "AssociateAccountsInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateAccountsOutputTypeDef",
     "AssociatePricingRulesInputRequestTypeDef",
+    "AssociatePricingRulesOutputTypeDef",
     "AssociateResourceErrorTypeDef",
     "CustomLineItemBillingPeriodRangeTypeDef",
     "BillingGroupCostReportElementTypeDef",
     "ComputationPreferenceTypeDef",
+    "CreateBillingGroupOutputTypeDef",
+    "CreateCustomLineItemOutputTypeDef",
     "CreateFreeTierConfigTypeDef",
     "CreatePricingPlanInputRequestTypeDef",
+    "CreatePricingPlanOutputTypeDef",
+    "CreatePricingRuleOutputTypeDef",
     "CustomLineItemFlatChargeDetailsTypeDef",
     "CustomLineItemPercentageChargeDetailsTypeDef",
     "DeleteBillingGroupInputRequestTypeDef",
+    "DeleteBillingGroupOutputTypeDef",
+    "DeleteCustomLineItemOutputTypeDef",
     "DeletePricingPlanInputRequestTypeDef",
+    "DeletePricingPlanOutputTypeDef",
     "DeletePricingRuleInputRequestTypeDef",
+    "DeletePricingRuleOutputTypeDef",
     "DisassociateAccountsInputRequestTypeDef",
+    "DisassociateAccountsOutputTypeDef",
     "DisassociatePricingRulesInputRequestTypeDef",
+    "DisassociatePricingRulesOutputTypeDef",
     "FreeTierConfigTypeDef",
     "ListAccountAssociationsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListBillingGroupCostReportsFilterTypeDef",
     "ListBillingGroupsFilterTypeDef",
     "ListCustomLineItemFlatChargeDetailsTypeDef",
     "ListCustomLineItemPercentageChargeDetailsTypeDef",
     "ListCustomLineItemVersionsBillingPeriodRangeFilterTypeDef",
     "ListCustomLineItemsFilterTypeDef",
+    "ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
     "ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef",
+    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
     "ListPricingPlansFilterTypeDef",
     "PricingPlanListElementTypeDef",
+    "ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
     "ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef",
+    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
     "ListPricingRulesFilterTypeDef",
     "ListResourcesAssociatedToCustomLineItemFilterTypeDef",
     "ListResourcesAssociatedToCustomLineItemResponseElementTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateBillingGroupOutputTypeDef",
     "UpdateCustomLineItemFlatChargeDetailsTypeDef",
     "UpdateCustomLineItemPercentageChargeDetailsTypeDef",
     "UpdateFreeTierConfigTypeDef",
     "UpdatePricingPlanInputRequestTypeDef",
-    "AssociateAccountsOutputTypeDef",
-    "AssociatePricingRulesOutputTypeDef",
-    "CreateBillingGroupOutputTypeDef",
-    "CreateCustomLineItemOutputTypeDef",
-    "CreatePricingPlanOutputTypeDef",
-    "CreatePricingRuleOutputTypeDef",
-    "DeleteBillingGroupOutputTypeDef",
-    "DeleteCustomLineItemOutputTypeDef",
-    "DeletePricingPlanOutputTypeDef",
-    "DeletePricingRuleOutputTypeDef",
-    "DisassociateAccountsOutputTypeDef",
-    "DisassociatePricingRulesOutputTypeDef",
-    "ListAccountAssociationsOutputTypeDef",
-    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
-    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateBillingGroupOutputTypeDef",
     "UpdatePricingPlanOutputTypeDef",
+    "ListAccountAssociationsOutputTypeDef",
     "AssociateResourceResponseElementTypeDef",
     "DisassociateResourceResponseElementTypeDef",
     "BatchAssociateResourcesToCustomLineItemInputRequestTypeDef",
     "BatchDisassociateResourcesFromCustomLineItemInputRequestTypeDef",
     "DeleteCustomLineItemInputRequestTypeDef",
     "ListBillingGroupCostReportsOutputTypeDef",
     "BillingGroupListElementTypeDef",
     "CreateBillingGroupInputRequestTypeDef",
     "UpdateBillingGroupInputRequestTypeDef",
     "CreateTieringInputTypeDef",
     "CustomLineItemChargeDetailsTypeDef",
     "TieringTypeDef",
-    "ListAccountAssociationsInputRequestTypeDef",
     "ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef",
-    "ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    "ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    "ListAccountAssociationsInputRequestTypeDef",
     "ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef",
     "ListBillingGroupCostReportsInputRequestTypeDef",
     "ListBillingGroupsInputListBillingGroupsPaginateTypeDef",
     "ListBillingGroupsInputRequestTypeDef",
     "ListCustomLineItemChargeDetailsTypeDef",
     "ListCustomLineItemVersionsFilterTypeDef",
     "ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef",
@@ -164,33 +164,38 @@
     "AssociateAccountsInputRequestTypeDef",
     {
         "Arn": str,
         "AccountIds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateAccountsOutputTypeDef = TypedDict(
+    "AssociateAccountsOutputTypeDef",
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
 
 AssociatePricingRulesInputRequestTypeDef = TypedDict(
     "AssociatePricingRulesInputRequestTypeDef",
     {
         "Arn": str,
         "PricingRuleArns": Sequence[str],
     },
 )
 
+AssociatePricingRulesOutputTypeDef = TypedDict(
+    "AssociatePricingRulesOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateResourceErrorTypeDef = TypedDict(
     "AssociateResourceErrorTypeDef",
     {
         "Message": str,
         "Reason": AssociateResourceErrorReasonType,
     },
     total=False,
@@ -232,14 +237,30 @@
 ComputationPreferenceTypeDef = TypedDict(
     "ComputationPreferenceTypeDef",
     {
         "PricingPlanArn": str,
     },
 )
 
+CreateBillingGroupOutputTypeDef = TypedDict(
+    "CreateBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomLineItemOutputTypeDef = TypedDict(
+    "CreateCustomLineItemOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateFreeTierConfigTypeDef = TypedDict(
     "CreateFreeTierConfigTypeDef",
     {
         "Activated": bool,
     },
 )
 
@@ -261,14 +282,30 @@
 )
 
 class CreatePricingPlanInputRequestTypeDef(
     _RequiredCreatePricingPlanInputRequestTypeDef, _OptionalCreatePricingPlanInputRequestTypeDef
 ):
     pass
 
+CreatePricingPlanOutputTypeDef = TypedDict(
+    "CreatePricingPlanOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePricingRuleOutputTypeDef = TypedDict(
+    "CreatePricingRuleOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "CustomLineItemFlatChargeDetailsTypeDef",
     {
         "ChargeValue": float,
     },
 )
 
@@ -295,66 +332,105 @@
 DeleteBillingGroupInputRequestTypeDef = TypedDict(
     "DeleteBillingGroupInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteBillingGroupOutputTypeDef = TypedDict(
+    "DeleteBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteCustomLineItemOutputTypeDef = TypedDict(
+    "DeleteCustomLineItemOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePricingPlanInputRequestTypeDef = TypedDict(
     "DeletePricingPlanInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeletePricingPlanOutputTypeDef = TypedDict(
+    "DeletePricingPlanOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePricingRuleInputRequestTypeDef = TypedDict(
     "DeletePricingRuleInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeletePricingRuleOutputTypeDef = TypedDict(
+    "DeletePricingRuleOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateAccountsInputRequestTypeDef = TypedDict(
     "DisassociateAccountsInputRequestTypeDef",
     {
         "Arn": str,
         "AccountIds": Sequence[str],
     },
 )
 
+DisassociateAccountsOutputTypeDef = TypedDict(
+    "DisassociateAccountsOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociatePricingRulesInputRequestTypeDef = TypedDict(
     "DisassociatePricingRulesInputRequestTypeDef",
     {
         "Arn": str,
         "PricingRuleArns": Sequence[str],
     },
 )
 
+DisassociatePricingRulesOutputTypeDef = TypedDict(
+    "DisassociatePricingRulesOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FreeTierConfigTypeDef = TypedDict(
     "FreeTierConfigTypeDef",
     {
         "Activated": bool,
     },
 )
 
 ListAccountAssociationsFilterTypeDef = TypedDict(
     "ListAccountAssociationsFilterTypeDef",
     {
         "Association": str,
         "AccountId": str,
-    },
-    total=False,
-)
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AccountIds": Sequence[str],
     },
     total=False,
 )
 
 ListBillingGroupCostReportsFilterTypeDef = TypedDict(
     "ListBillingGroupCostReportsFilterTypeDef",
     {
@@ -364,14 +440,15 @@
 )
 
 ListBillingGroupsFilterTypeDef = TypedDict(
     "ListBillingGroupsFilterTypeDef",
     {
         "Arns": Sequence[str],
         "PricingPlan": str,
+        "Statuses": Sequence[BillingGroupStatusType],
     },
     total=False,
 )
 
 ListCustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "ListCustomLineItemFlatChargeDetailsTypeDef",
     {
@@ -401,14 +478,35 @@
         "Names": Sequence[str],
         "BillingGroups": Sequence[str],
         "Arns": Sequence[str],
     },
     total=False,
 )
 
+_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
+    "_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
+    {
+        "PricingRuleArn": str,
+    },
+)
+_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
+    "_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
+    {
+        "BillingPeriod": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef(
+    _RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
+    _OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
+):
+    pass
+
 _RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef = TypedDict(
     "_RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef",
     {
         "PricingRuleArn": str,
     },
 )
 _OptionalListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef = TypedDict(
@@ -423,14 +521,25 @@
 
 class ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef(
     _RequiredListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
     _OptionalListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
 ):
     pass
 
+ListPricingPlansAssociatedWithPricingRuleOutputTypeDef = TypedDict(
+    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
+    {
+        "BillingPeriod": str,
+        "PricingRuleArn": str,
+        "PricingPlanArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPricingPlansFilterTypeDef = TypedDict(
     "ListPricingPlansFilterTypeDef",
     {
         "Arns": Sequence[str],
     },
     total=False,
 )
@@ -444,14 +553,35 @@
         "Size": int,
         "CreationTime": int,
         "LastModifiedTime": int,
     },
     total=False,
 )
 
+_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
+    "_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    {
+        "PricingPlanArn": str,
+    },
+)
+_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
+    "_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+    {
+        "BillingPeriod": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef(
+    _RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+    _OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+):
+    pass
+
 _RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef = TypedDict(
     "_RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef",
     {
         "PricingPlanArn": str,
     },
 )
 _OptionalListPricingRulesAssociatedToPricingPlanInputRequestTypeDef = TypedDict(
@@ -466,14 +596,25 @@
 
 class ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef(
     _RequiredListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
     _OptionalListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
 ):
     pass
 
+ListPricingRulesAssociatedToPricingPlanOutputTypeDef = TypedDict(
+    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
+    {
+        "BillingPeriod": str,
+        "PricingPlanArn": str,
+        "PricingRuleArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPricingRulesFilterTypeDef = TypedDict(
     "ListPricingRulesFilterTypeDef",
     {
         "Arns": Sequence[str],
     },
     total=False,
 )
@@ -499,14 +640,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -515,14 +685,30 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateBillingGroupOutputTypeDef = TypedDict(
+    "UpdateBillingGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Description": str,
+        "PrimaryAccountId": str,
+        "PricingPlanArn": str,
+        "Size": int,
+        "LastModifiedTime": int,
+        "Status": BillingGroupStatusType,
+        "StatusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateCustomLineItemFlatChargeDetailsTypeDef = TypedDict(
     "UpdateCustomLineItemFlatChargeDetailsTypeDef",
     {
         "ChargeValue": float,
     },
 )
 
@@ -556,174 +742,32 @@
 )
 
 class UpdatePricingPlanInputRequestTypeDef(
     _RequiredUpdatePricingPlanInputRequestTypeDef, _OptionalUpdatePricingPlanInputRequestTypeDef
 ):
     pass
 
-AssociateAccountsOutputTypeDef = TypedDict(
-    "AssociateAccountsOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociatePricingRulesOutputTypeDef = TypedDict(
-    "AssociatePricingRulesOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBillingGroupOutputTypeDef = TypedDict(
-    "CreateBillingGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomLineItemOutputTypeDef = TypedDict(
-    "CreateCustomLineItemOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePricingPlanOutputTypeDef = TypedDict(
-    "CreatePricingPlanOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePricingRuleOutputTypeDef = TypedDict(
-    "CreatePricingRuleOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBillingGroupOutputTypeDef = TypedDict(
-    "DeleteBillingGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomLineItemOutputTypeDef = TypedDict(
-    "DeleteCustomLineItemOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePricingPlanOutputTypeDef = TypedDict(
-    "DeletePricingPlanOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePricingRuleOutputTypeDef = TypedDict(
-    "DeletePricingRuleOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateAccountsOutputTypeDef = TypedDict(
-    "DisassociateAccountsOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePricingRulesOutputTypeDef = TypedDict(
-    "DisassociatePricingRulesOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountAssociationsOutputTypeDef = TypedDict(
-    "ListAccountAssociationsOutputTypeDef",
-    {
-        "LinkedAccounts": List[AccountAssociationsListElementTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPricingPlansAssociatedWithPricingRuleOutputTypeDef = TypedDict(
-    "ListPricingPlansAssociatedWithPricingRuleOutputTypeDef",
-    {
-        "BillingPeriod": str,
-        "PricingRuleArn": str,
-        "PricingPlanArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPricingRulesAssociatedToPricingPlanOutputTypeDef = TypedDict(
-    "ListPricingRulesAssociatedToPricingPlanOutputTypeDef",
-    {
-        "BillingPeriod": str,
-        "PricingPlanArn": str,
-        "PricingRuleArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBillingGroupOutputTypeDef = TypedDict(
-    "UpdateBillingGroupOutputTypeDef",
+UpdatePricingPlanOutputTypeDef = TypedDict(
+    "UpdatePricingPlanOutputTypeDef",
     {
         "Arn": str,
         "Name": str,
         "Description": str,
-        "PrimaryAccountId": str,
-        "PricingPlanArn": str,
         "Size": int,
         "LastModifiedTime": int,
-        "Status": BillingGroupStatusType,
-        "StatusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdatePricingPlanOutputTypeDef = TypedDict(
-    "UpdatePricingPlanOutputTypeDef",
+ListAccountAssociationsOutputTypeDef = TypedDict(
+    "ListAccountAssociationsOutputTypeDef",
     {
-        "Arn": str,
-        "Name": str,
-        "Description": str,
-        "Size": int,
-        "LastModifiedTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "LinkedAccounts": List[AccountAssociationsListElementTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResourceResponseElementTypeDef = TypedDict(
     "AssociateResourceResponseElementTypeDef",
     {
         "Arn": str,
@@ -804,15 +848,15 @@
     pass
 
 ListBillingGroupCostReportsOutputTypeDef = TypedDict(
     "ListBillingGroupCostReportsOutputTypeDef",
     {
         "BillingGroupCostReports": List[BillingGroupCostReportElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BillingGroupListElementTypeDef = TypedDict(
     "BillingGroupListElementTypeDef",
     {
         "Name": str,
@@ -905,82 +949,40 @@
 TieringTypeDef = TypedDict(
     "TieringTypeDef",
     {
         "FreeTier": FreeTierConfigTypeDef,
     },
 )
 
-ListAccountAssociationsInputRequestTypeDef = TypedDict(
-    "ListAccountAssociationsInputRequestTypeDef",
-    {
-        "BillingPeriod": str,
-        "Filters": ListAccountAssociationsFilterTypeDef,
-        "NextToken": str,
-    },
-    total=False,
-)
-
 ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef = TypedDict(
     "ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListAccountAssociationsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
-    "_RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    {
-        "PricingRuleArn": str,
-    },
-)
-_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef = TypedDict(
-    "_OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef",
-    {
-        "BillingPeriod": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef(
-    _RequiredListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-    _OptionalListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-):
-    pass
-
-_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
-    "_RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
-    {
-        "PricingPlanArn": str,
-    },
-)
-_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef = TypedDict(
-    "_OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef",
+ListAccountAssociationsInputRequestTypeDef = TypedDict(
+    "ListAccountAssociationsInputRequestTypeDef",
     {
         "BillingPeriod": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": ListAccountAssociationsFilterTypeDef,
+        "NextToken": str,
     },
     total=False,
 )
 
-class ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef(
-    _RequiredListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
-    _OptionalListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
-):
-    pass
-
 ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef = TypedDict(
     "ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListBillingGroupCostReportsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBillingGroupCostReportsInputRequestTypeDef = TypedDict(
     "ListBillingGroupCostReportsInputRequestTypeDef",
     {
@@ -993,15 +995,15 @@
 )
 
 ListBillingGroupsInputListBillingGroupsPaginateTypeDef = TypedDict(
     "ListBillingGroupsInputListBillingGroupsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListBillingGroupsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBillingGroupsInputRequestTypeDef = TypedDict(
     "ListBillingGroupsInputRequestTypeDef",
     {
@@ -1042,15 +1044,15 @@
 )
 
 ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef = TypedDict(
     "ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListCustomLineItemsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCustomLineItemsInputRequestTypeDef = TypedDict(
     "ListCustomLineItemsInputRequestTypeDef",
     {
@@ -1063,15 +1065,15 @@
 )
 
 ListPricingPlansInputListPricingPlansPaginateTypeDef = TypedDict(
     "ListPricingPlansInputListPricingPlansPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListPricingPlansFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPricingPlansInputRequestTypeDef = TypedDict(
     "ListPricingPlansInputRequestTypeDef",
     {
@@ -1085,24 +1087,24 @@
 
 ListPricingPlansOutputTypeDef = TypedDict(
     "ListPricingPlansOutputTypeDef",
     {
         "BillingPeriod": str,
         "PricingPlans": List[PricingPlanListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPricingRulesInputListPricingRulesPaginateTypeDef = TypedDict(
     "ListPricingRulesInputListPricingRulesPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListPricingRulesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPricingRulesInputRequestTypeDef = TypedDict(
     "ListPricingRulesInputRequestTypeDef",
     {
@@ -1121,15 +1123,15 @@
     },
 )
 _OptionalListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef = TypedDict(
     "_OptionalListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef",
     {
         "BillingPeriod": str,
         "Filters": ListResourcesAssociatedToCustomLineItemFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef(
     _RequiredListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef,
     _OptionalListResourcesAssociatedToCustomLineItemInputListResourcesAssociatedToCustomLineItemPaginateTypeDef,
@@ -1161,15 +1163,15 @@
 
 ListResourcesAssociatedToCustomLineItemOutputTypeDef = TypedDict(
     "ListResourcesAssociatedToCustomLineItemOutputTypeDef",
     {
         "Arn": str,
         "AssociatedResources": List[ListResourcesAssociatedToCustomLineItemResponseElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomLineItemChargeDetailsTypeDef = TypedDict(
     "UpdateCustomLineItemChargeDetailsTypeDef",
     {
         "Flat": UpdateCustomLineItemFlatChargeDetailsTypeDef,
@@ -1186,33 +1188,33 @@
 )
 
 BatchAssociateResourcesToCustomLineItemOutputTypeDef = TypedDict(
     "BatchAssociateResourcesToCustomLineItemOutputTypeDef",
     {
         "SuccessfullyAssociatedResources": List[AssociateResourceResponseElementTypeDef],
         "FailedAssociatedResources": List[AssociateResourceResponseElementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateResourcesFromCustomLineItemOutputTypeDef = TypedDict(
     "BatchDisassociateResourcesFromCustomLineItemOutputTypeDef",
     {
         "SuccessfullyDisassociatedResources": List[DisassociateResourceResponseElementTypeDef],
         "FailedDisassociatedResources": List[DisassociateResourceResponseElementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBillingGroupsOutputTypeDef = TypedDict(
     "ListBillingGroupsOutputTypeDef",
     {
         "BillingGroups": List[BillingGroupListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePricingRuleInputRequestTypeDef = TypedDict(
     "_RequiredCreatePricingRuleInputRequestTypeDef",
     {
         "Name": str,
@@ -1277,14 +1279,16 @@
         "ModifierPercentage": float,
         "Service": str,
         "AssociatedPricingPlanCount": int,
         "CreationTime": int,
         "LastModifiedTime": int,
         "BillingEntity": str,
         "Tiering": TieringTypeDef,
+        "UsageType": str,
+        "Operation": str,
     },
     total=False,
 )
 
 CustomLineItemListElementTypeDef = TypedDict(
     "CustomLineItemListElementTypeDef",
     {
@@ -1312,43 +1316,45 @@
         "ProductCode": str,
         "BillingGroupArn": str,
         "CreationTime": int,
         "LastModifiedTime": int,
         "AssociationSize": int,
         "StartBillingPeriod": str,
         "EndBillingPeriod": str,
+        "Arn": str,
+        "StartTime": int,
     },
     total=False,
 )
 
 UpdateCustomLineItemOutputTypeDef = TypedDict(
     "UpdateCustomLineItemOutputTypeDef",
     {
         "Arn": str,
         "BillingGroupArn": str,
         "Name": str,
         "Description": str,
         "ChargeDetails": ListCustomLineItemChargeDetailsTypeDef,
         "LastModifiedTime": int,
         "AssociationSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef = TypedDict(
     "_RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef",
     {
         "Arn": str,
     },
 )
 _OptionalListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef = TypedDict(
     "_OptionalListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef",
     {
         "Filters": ListCustomLineItemVersionsFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef(
     _RequiredListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef,
     _OptionalListCustomLineItemVersionsInputListCustomLineItemVersionsPaginateTypeDef,
@@ -1435,38 +1441,38 @@
         "Service": str,
         "AssociatedPricingPlanCount": int,
         "LastModifiedTime": int,
         "BillingEntity": str,
         "Tiering": UpdateTieringInputTypeDef,
         "UsageType": str,
         "Operation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPricingRulesOutputTypeDef = TypedDict(
     "ListPricingRulesOutputTypeDef",
     {
         "BillingPeriod": str,
         "PricingRules": List[PricingRuleListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomLineItemsOutputTypeDef = TypedDict(
     "ListCustomLineItemsOutputTypeDef",
     {
         "CustomLineItems": List[CustomLineItemListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomLineItemVersionsOutputTypeDef = TypedDict(
     "ListCustomLineItemVersionsOutputTypeDef",
     {
         "CustomLineItemVersions": List[CustomLineItemVersionListElementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/PKG-INFO` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-billingconductor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BillingConductor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BillingConductor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-billingconductor"></a>
 
 # types-aiobotocore-billingconductor
 
 [![PyPI - types-aiobotocore-billingconductor](https://img.shields.io/pypi/v/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-billingconductor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-billingconductor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-billingconductor?color=blue)](https://pypistats.org/packages/types-aiobotocore-billingconductor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BillingConductor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
+[aiobotocore.BillingConductor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/billingconductor.html#BillingConductor)
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
 [types-aiobotocore-billingconductor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_billingconductor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -372,86 +372,86 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_billingconductor.type_defs import (
     AccountAssociationsListElementTypeDef,
     AccountGroupingTypeDef,
     AssociateAccountsInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAccountsOutputTypeDef,
     AssociatePricingRulesInputRequestTypeDef,
+    AssociatePricingRulesOutputTypeDef,
     AssociateResourceErrorTypeDef,
     CustomLineItemBillingPeriodRangeTypeDef,
     BillingGroupCostReportElementTypeDef,
     ComputationPreferenceTypeDef,
+    CreateBillingGroupOutputTypeDef,
+    CreateCustomLineItemOutputTypeDef,
     CreateFreeTierConfigTypeDef,
     CreatePricingPlanInputRequestTypeDef,
+    CreatePricingPlanOutputTypeDef,
+    CreatePricingRuleOutputTypeDef,
     CustomLineItemFlatChargeDetailsTypeDef,
     CustomLineItemPercentageChargeDetailsTypeDef,
     DeleteBillingGroupInputRequestTypeDef,
+    DeleteBillingGroupOutputTypeDef,
+    DeleteCustomLineItemOutputTypeDef,
     DeletePricingPlanInputRequestTypeDef,
+    DeletePricingPlanOutputTypeDef,
     DeletePricingRuleInputRequestTypeDef,
+    DeletePricingRuleOutputTypeDef,
     DisassociateAccountsInputRequestTypeDef,
+    DisassociateAccountsOutputTypeDef,
     DisassociatePricingRulesInputRequestTypeDef,
+    DisassociatePricingRulesOutputTypeDef,
     FreeTierConfigTypeDef,
     ListAccountAssociationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListBillingGroupCostReportsFilterTypeDef,
     ListBillingGroupsFilterTypeDef,
     ListCustomLineItemFlatChargeDetailsTypeDef,
     ListCustomLineItemPercentageChargeDetailsTypeDef,
     ListCustomLineItemVersionsBillingPeriodRangeFilterTypeDef,
     ListCustomLineItemsFilterTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
     ListPricingPlansAssociatedWithPricingRuleInputRequestTypeDef,
+    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
     ListPricingPlansFilterTypeDef,
     PricingPlanListElementTypeDef,
+    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
     ListPricingRulesAssociatedToPricingPlanInputRequestTypeDef,
+    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
     ListPricingRulesFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemFilterTypeDef,
     ListResourcesAssociatedToCustomLineItemResponseElementTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBillingGroupOutputTypeDef,
     UpdateCustomLineItemFlatChargeDetailsTypeDef,
     UpdateCustomLineItemPercentageChargeDetailsTypeDef,
     UpdateFreeTierConfigTypeDef,
     UpdatePricingPlanInputRequestTypeDef,
-    AssociateAccountsOutputTypeDef,
-    AssociatePricingRulesOutputTypeDef,
-    CreateBillingGroupOutputTypeDef,
-    CreateCustomLineItemOutputTypeDef,
-    CreatePricingPlanOutputTypeDef,
-    CreatePricingRuleOutputTypeDef,
-    DeleteBillingGroupOutputTypeDef,
-    DeleteCustomLineItemOutputTypeDef,
-    DeletePricingPlanOutputTypeDef,
-    DeletePricingRuleOutputTypeDef,
-    DisassociateAccountsOutputTypeDef,
-    DisassociatePricingRulesOutputTypeDef,
-    ListAccountAssociationsOutputTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleOutputTypeDef,
-    ListPricingRulesAssociatedToPricingPlanOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateBillingGroupOutputTypeDef,
     UpdatePricingPlanOutputTypeDef,
+    ListAccountAssociationsOutputTypeDef,
     AssociateResourceResponseElementTypeDef,
     DisassociateResourceResponseElementTypeDef,
     BatchAssociateResourcesToCustomLineItemInputRequestTypeDef,
     BatchDisassociateResourcesFromCustomLineItemInputRequestTypeDef,
     DeleteCustomLineItemInputRequestTypeDef,
     ListBillingGroupCostReportsOutputTypeDef,
     BillingGroupListElementTypeDef,
     CreateBillingGroupInputRequestTypeDef,
     UpdateBillingGroupInputRequestTypeDef,
     CreateTieringInputTypeDef,
     CustomLineItemChargeDetailsTypeDef,
     TieringTypeDef,
-    ListAccountAssociationsInputRequestTypeDef,
     ListAccountAssociationsInputListAccountAssociationsPaginateTypeDef,
-    ListPricingPlansAssociatedWithPricingRuleInputListPricingPlansAssociatedWithPricingRulePaginateTypeDef,
-    ListPricingRulesAssociatedToPricingPlanInputListPricingRulesAssociatedToPricingPlanPaginateTypeDef,
+    ListAccountAssociationsInputRequestTypeDef,
     ListBillingGroupCostReportsInputListBillingGroupCostReportsPaginateTypeDef,
     ListBillingGroupCostReportsInputRequestTypeDef,
     ListBillingGroupsInputListBillingGroupsPaginateTypeDef,
     ListBillingGroupsInputRequestTypeDef,
     ListCustomLineItemChargeDetailsTypeDef,
     ListCustomLineItemVersionsFilterTypeDef,
     ListCustomLineItemsInputListCustomLineItemsPaginateTypeDef,
@@ -493,43 +493,43 @@
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

### Comparing `types-aiobotocore-billingconductor-2.5.0.post1/types_aiobotocore_billingconductor.egg-info/SOURCES.txt` & `types-aiobotocore-billingconductor-2.5.1/types_aiobotocore_billingconductor.egg-info/SOURCES.txt`

 * *Files identical despite different names*

