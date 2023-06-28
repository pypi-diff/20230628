# Comparing `tmp/types-aiobotocore-route53-recovery-control-config-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53-recovery-control-config-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53-recovery-control-config-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53-recovery-control-config-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1.tar` & `types-aiobotocore-route53-recovery-control-config-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.775563 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19513 2023-03-11 12:27:13.775563 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17849 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.775563 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2292 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.775563 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/
--rw-r--r--   0 runner    (1001) docker     (123)     2985 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2984 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25723 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25680 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9157 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9155 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7617 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7609 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23236 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23205 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     7506 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     7500 2023-03-11 12:22:40.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.775563 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19513 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.278204 types-aiobotocore-route53-recovery-control-config-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19529 2023-06-28 01:44:05.278204 types-aiobotocore-route53-recovery-control-config-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17871 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.278204 types-aiobotocore-route53-recovery-control-config-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2286 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.274204 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/
+-rw-r--r--   0 runner    (1001) docker     (123)     2985 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2984 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25723 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25680 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9366 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9364 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7507 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7500 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    23280 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23249 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7506 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7500 2023-06-28 01:39:27.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.278204 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19529 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/LICENSE` & `types-aiobotocore-route53-recovery-control-config-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53-recovery-control-config-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-control-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-control-config"></a>
 
 # types-aiobotocore-route53-recovery-control-config
 
 [![PyPI - types-aiobotocore-route53-recovery-control-config](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-control-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-control-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryControlConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
+[aiobotocore.Route53RecoveryControlConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
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
 [types-aiobotocore-route53-recovery-control-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,66 +399,66 @@
 ```python
 from types_aiobotocore_route53_recovery_control_config.type_defs import (
     RuleConfigTypeDef,
     AssertionRuleUpdateTypeDef,
     ClusterEndpointTypeDef,
     ControlPanelTypeDef,
     CreateClusterRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateControlPanelRequestRequestTypeDef,
     CreateRoutingControlRequestRequestTypeDef,
     RoutingControlTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteControlPanelRequestRequestTypeDef,
     DeleteRoutingControlRequestRequestTypeDef,
     DeleteSafetyRuleRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeControlPanelRequestRequestTypeDef,
     DescribeRoutingControlRequestRequestTypeDef,
     DescribeSafetyRuleRequestRequestTypeDef,
     GatingRuleUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
     ListAssociatedRoute53HealthChecksRequestRequestTypeDef,
+    ListAssociatedRoute53HealthChecksResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
     ListControlPanelsRequestRequestTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
+    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     ListSafetyRulesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateControlPanelRequestRequestTypeDef,
     UpdateRoutingControlRequestRequestTypeDef,
     AssertionRuleTypeDef,
     GatingRuleTypeDef,
     NewAssertionRuleTypeDef,
     NewGatingRuleTypeDef,
     ClusterTypeDef,
     CreateControlPanelResponseTypeDef,
     DescribeControlPanelResponseTypeDef,
-    ListAssociatedRoute53HealthChecksResponseTypeDef,
     ListControlPanelsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateControlPanelResponseTypeDef,
     CreateRoutingControlResponseTypeDef,
     DescribeRoutingControlResponseTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlResponseTypeDef,
     DescribeClusterRequestClusterCreatedWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeControlPanelRequestControlPanelCreatedWaitTypeDef,
     DescribeControlPanelRequestControlPanelDeletedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlCreatedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlDeletedWaitTypeDef,
     UpdateSafetyRuleRequestRequestTypeDef,
-    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     CreateSafetyRuleResponseTypeDef,
     DescribeSafetyRuleResponseTypeDef,
     RuleTypeDef,
     UpdateSafetyRuleResponseTypeDef,
     CreateSafetyRuleRequestRequestTypeDef,
     CreateClusterResponseTypeDef,
     DescribeClusterResponseTypeDef,
@@ -474,43 +474,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/README.md` & `types-aiobotocore-route53-recovery-control-config-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53-recovery-control-config"></a>
 
 # types-aiobotocore-route53-recovery-control-config
 
 [![PyPI - types-aiobotocore-route53-recovery-control-config](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-control-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-control-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryControlConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
+[aiobotocore.Route53RecoveryControlConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
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
 [types-aiobotocore-route53-recovery-control-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,66 +366,66 @@
 ```python
 from types_aiobotocore_route53_recovery_control_config.type_defs import (
     RuleConfigTypeDef,
     AssertionRuleUpdateTypeDef,
     ClusterEndpointTypeDef,
     ControlPanelTypeDef,
     CreateClusterRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateControlPanelRequestRequestTypeDef,
     CreateRoutingControlRequestRequestTypeDef,
     RoutingControlTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteControlPanelRequestRequestTypeDef,
     DeleteRoutingControlRequestRequestTypeDef,
     DeleteSafetyRuleRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeControlPanelRequestRequestTypeDef,
     DescribeRoutingControlRequestRequestTypeDef,
     DescribeSafetyRuleRequestRequestTypeDef,
     GatingRuleUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
     ListAssociatedRoute53HealthChecksRequestRequestTypeDef,
+    ListAssociatedRoute53HealthChecksResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
     ListControlPanelsRequestRequestTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
+    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     ListSafetyRulesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateControlPanelRequestRequestTypeDef,
     UpdateRoutingControlRequestRequestTypeDef,
     AssertionRuleTypeDef,
     GatingRuleTypeDef,
     NewAssertionRuleTypeDef,
     NewGatingRuleTypeDef,
     ClusterTypeDef,
     CreateControlPanelResponseTypeDef,
     DescribeControlPanelResponseTypeDef,
-    ListAssociatedRoute53HealthChecksResponseTypeDef,
     ListControlPanelsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateControlPanelResponseTypeDef,
     CreateRoutingControlResponseTypeDef,
     DescribeRoutingControlResponseTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlResponseTypeDef,
     DescribeClusterRequestClusterCreatedWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeControlPanelRequestControlPanelCreatedWaitTypeDef,
     DescribeControlPanelRequestControlPanelDeletedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlCreatedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlDeletedWaitTypeDef,
     UpdateSafetyRuleRequestRequestTypeDef,
-    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     CreateSafetyRuleResponseTypeDef,
     DescribeSafetyRuleResponseTypeDef,
     RuleTypeDef,
     UpdateSafetyRuleResponseTypeDef,
     CreateSafetyRuleRequestRequestTypeDef,
     CreateClusterResponseTypeDef,
     DescribeClusterResponseTypeDef,
@@ -441,43 +441,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/setup.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53-recovery-control-config.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53-recovery-control-config",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53_recovery_control_config"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/",
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__init__.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__init__.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/__main__.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig\nOther"
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/client.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/client.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/literals.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/literals.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -111,14 +111,15 @@
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
@@ -197,14 +198,15 @@
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
@@ -215,14 +217,15 @@
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
@@ -258,14 +261,15 @@
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
@@ -284,16 +288,19 @@
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
@@ -377,15 +384,17 @@
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/paginator.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_associated_route53_health_checks_paginator: ListAssociatedRoute53HealthChecksPaginator = client.get_paginator("list_associated_route53_health_checks")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_control_panels_paginator: ListControlPanelsPaginator = client.get_paginator("list_control_panels")
         list_routing_controls_paginator: ListRoutingControlsPaginator = client.get_paginator("list_routing_controls")
         list_safety_rules_paginator: ListSafetyRulesPaginator = client.get_paginator("list_safety_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssociatedRoute53HealthChecksResponseTypeDef,
     ListClustersResponseTypeDef,
     ListControlPanelsResponseTypeDef,
     ListRoutingControlsResponseTypeDef,
     ListSafetyRulesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssociatedRoute53HealthChecksPaginator",
     "ListClustersPaginator",
     "ListControlPanelsPaginator",
     "ListRoutingControlsPaginator",
     "ListSafetyRulesPaginator",
 )
@@ -71,73 +64,73 @@
 class ListAssociatedRoute53HealthChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListAssociatedRoute53HealthChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listassociatedroute53healthcheckspaginator)
     """
 
     def paginate(
-        self, *, RoutingControlArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoutingControlArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedRoute53HealthChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListAssociatedRoute53HealthChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listassociatedroute53healthcheckspaginator)
         """
 
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listclusterspaginator)
         """
 
 
 class ListControlPanelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListControlPanels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listcontrolpanelspaginator)
     """
 
     def paginate(
-        self, *, ClusterArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListControlPanelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListControlPanels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listcontrolpanelspaginator)
         """
 
 
 class ListRoutingControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListRoutingControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listroutingcontrolspaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutingControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListRoutingControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listroutingcontrolspaginator)
         """
 
 
 class ListSafetyRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListSafetyRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listsafetyrulespaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSafetyRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListSafetyRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listsafetyrulespaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/paginator.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_associated_route53_health_checks_paginator: ListAssociatedRoute53HealthChecksPaginator = client.get_paginator("list_associated_route53_health_checks")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_control_panels_paginator: ListControlPanelsPaginator = client.get_paginator("list_control_panels")
         list_routing_controls_paginator: ListRoutingControlsPaginator = client.get_paginator("list_routing_controls")
         list_safety_rules_paginator: ListSafetyRulesPaginator = client.get_paginator("list_safety_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssociatedRoute53HealthChecksResponseTypeDef,
     ListClustersResponseTypeDef,
     ListControlPanelsResponseTypeDef,
     ListRoutingControlsResponseTypeDef,
     ListSafetyRulesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssociatedRoute53HealthChecksPaginator",
     "ListClustersPaginator",
     "ListControlPanelsPaginator",
     "ListRoutingControlsPaginator",
     "ListSafetyRulesPaginator",
 )
@@ -67,69 +61,69 @@
 class ListAssociatedRoute53HealthChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListAssociatedRoute53HealthChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listassociatedroute53healthcheckspaginator)
     """
 
     def paginate(
-        self, *, RoutingControlArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RoutingControlArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedRoute53HealthChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListAssociatedRoute53HealthChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listassociatedroute53healthcheckspaginator)
         """
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listclusterspaginator)
         """
 
 class ListControlPanelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListControlPanels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listcontrolpanelspaginator)
     """
 
     def paginate(
-        self, *, ClusterArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListControlPanelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListControlPanels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listcontrolpanelspaginator)
         """
 
 class ListRoutingControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListRoutingControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listroutingcontrolspaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutingControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListRoutingControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listroutingcontrolspaginator)
         """
 
 class ListSafetyRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListSafetyRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listsafetyrulespaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSafetyRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig.Paginator.ListSafetyRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/paginators/#listsafetyrulespaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/type_defs.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,66 +24,66 @@
 
 __all__ = (
     "RuleConfigTypeDef",
     "AssertionRuleUpdateTypeDef",
     "ClusterEndpointTypeDef",
     "ControlPanelTypeDef",
     "CreateClusterRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateControlPanelRequestRequestTypeDef",
     "CreateRoutingControlRequestRequestTypeDef",
     "RoutingControlTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteControlPanelRequestRequestTypeDef",
     "DeleteRoutingControlRequestRequestTypeDef",
     "DeleteSafetyRuleRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeControlPanelRequestRequestTypeDef",
     "DescribeRoutingControlRequestRequestTypeDef",
     "DescribeSafetyRuleRequestRequestTypeDef",
     "GatingRuleUpdateTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
     "ListAssociatedRoute53HealthChecksRequestRequestTypeDef",
+    "ListAssociatedRoute53HealthChecksResponseTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
     "ListControlPanelsRequestRequestTypeDef",
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsRequestRequestTypeDef",
+    "ListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
     "ListSafetyRulesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateControlPanelRequestRequestTypeDef",
     "UpdateRoutingControlRequestRequestTypeDef",
     "AssertionRuleTypeDef",
     "GatingRuleTypeDef",
     "NewAssertionRuleTypeDef",
     "NewGatingRuleTypeDef",
     "ClusterTypeDef",
     "CreateControlPanelResponseTypeDef",
     "DescribeControlPanelResponseTypeDef",
-    "ListAssociatedRoute53HealthChecksResponseTypeDef",
     "ListControlPanelsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateControlPanelResponseTypeDef",
     "CreateRoutingControlResponseTypeDef",
     "DescribeRoutingControlResponseTypeDef",
     "ListRoutingControlsResponseTypeDef",
     "UpdateRoutingControlResponseTypeDef",
     "DescribeClusterRequestClusterCreatedWaitTypeDef",
     "DescribeClusterRequestClusterDeletedWaitTypeDef",
     "DescribeControlPanelRequestControlPanelCreatedWaitTypeDef",
     "DescribeControlPanelRequestControlPanelDeletedWaitTypeDef",
     "DescribeRoutingControlRequestRoutingControlCreatedWaitTypeDef",
     "DescribeRoutingControlRequestRoutingControlDeletedWaitTypeDef",
     "UpdateSafetyRuleRequestRequestTypeDef",
-    "ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    "ListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
     "CreateSafetyRuleResponseTypeDef",
     "DescribeSafetyRuleResponseTypeDef",
     "RuleTypeDef",
     "UpdateSafetyRuleResponseTypeDef",
     "CreateSafetyRuleRequestRequestTypeDef",
     "CreateClusterResponseTypeDef",
     "DescribeClusterResponseTypeDef",
@@ -149,25 +149,14 @@
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
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
 _RequiredCreateControlPanelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateControlPanelRequestRequestTypeDef",
     {
         "ClusterArn": str,
         "ControlPanelName": str,
     },
 )
@@ -293,24 +282,36 @@
     {
         "Name": str,
         "SafetyRuleArn": str,
         "WaitPeriodMs": int,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "RoutingControlArn": str,
+    },
+)
+_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef(
+    _RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
+    _OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef",
     {
         "RoutingControlArn": str,
     },
 )
 _OptionalListAssociatedRoute53HealthChecksRequestRequestTypeDef = TypedDict(
@@ -326,33 +327,81 @@
 class ListAssociatedRoute53HealthChecksRequestRequestTypeDef(
     _RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef,
     _OptionalListAssociatedRoute53HealthChecksRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssociatedRoute53HealthChecksResponseTypeDef = TypedDict(
+    "ListAssociatedRoute53HealthChecksResponseTypeDef",
+    {
+        "HealthCheckIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListControlPanelsRequestListControlPanelsPaginateTypeDef = TypedDict(
+    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
+    {
+        "ClusterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListControlPanelsRequestRequestTypeDef = TypedDict(
     "ListControlPanelsRequestRequestTypeDef",
     {
         "ClusterArn": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
+    {
+        "ControlPanelArn": str,
+    },
+)
+_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRoutingControlsRequestListRoutingControlsPaginateTypeDef(
+    _RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
+    _OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRoutingControlsRequestRequestTypeDef = TypedDict(
     "_RequiredListRoutingControlsRequestRequestTypeDef",
     {
         "ControlPanelArn": str,
     },
 )
 _OptionalListRoutingControlsRequestRequestTypeDef = TypedDict(
@@ -368,14 +417,36 @@
 class ListRoutingControlsRequestRequestTypeDef(
     _RequiredListRoutingControlsRequestRequestTypeDef,
     _OptionalListRoutingControlsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
+    "_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
+    {
+        "ControlPanelArn": str,
+    },
+)
+_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
+    "_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSafetyRulesRequestListSafetyRulesPaginateTypeDef(
+    _RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
+    _OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSafetyRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListSafetyRulesRequestRequestTypeDef",
     {
         "ControlPanelArn": str,
     },
 )
 _OptionalListSafetyRulesRequestRequestTypeDef = TypedDict(
@@ -397,14 +468,43 @@
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
@@ -494,90 +594,73 @@
     total=False,
 )
 
 CreateControlPanelResponseTypeDef = TypedDict(
     "CreateControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeControlPanelResponseTypeDef = TypedDict(
     "DescribeControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedRoute53HealthChecksResponseTypeDef = TypedDict(
-    "ListAssociatedRoute53HealthChecksResponseTypeDef",
-    {
-        "HealthCheckIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlPanelsResponseTypeDef = TypedDict(
     "ListControlPanelsResponseTypeDef",
     {
         "ControlPanels": List[ControlPanelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateControlPanelResponseTypeDef = TypedDict(
     "UpdateControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRoutingControlResponseTypeDef = TypedDict(
     "CreateRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRoutingControlResponseTypeDef = TypedDict(
     "DescribeRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutingControlsResponseTypeDef = TypedDict(
     "ListRoutingControlsResponseTypeDef",
     {
         "NextToken": str,
         "RoutingControls": List[RoutingControlTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoutingControlResponseTypeDef = TypedDict(
     "UpdateRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeClusterRequestClusterCreatedWaitTypeDef = TypedDict(
     "_RequiredDescribeClusterRequestClusterCreatedWaitTypeDef",
     {
         "ClusterArn": str,
@@ -714,112 +797,29 @@
     {
         "AssertionRuleUpdate": AssertionRuleUpdateTypeDef,
         "GatingRuleUpdate": GatingRuleUpdateTypeDef,
     },
     total=False,
 )
 
-_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    {
-        "RoutingControlArn": str,
-    },
-)
-_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef(
-    _RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-    _OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-):
-    pass
-
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListControlPanelsRequestListControlPanelsPaginateTypeDef = TypedDict(
-    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
-    {
-        "ClusterArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-    },
-)
-_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRoutingControlsRequestListRoutingControlsPaginateTypeDef(
-    _RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-    _OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
-    "_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-    },
-)
-_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
-    "_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSafetyRulesRequestListSafetyRulesPaginateTypeDef(
-    _RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
-    _OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
-):
-    pass
-
-
 CreateSafetyRuleResponseTypeDef = TypedDict(
     "CreateSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSafetyRuleResponseTypeDef = TypedDict(
     "DescribeSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "ASSERTION": AssertionRuleTypeDef,
@@ -829,15 +829,15 @@
 )
 
 UpdateSafetyRuleResponseTypeDef = TypedDict(
     "UpdateSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSafetyRuleRequestRequestTypeDef = TypedDict(
     "CreateSafetyRuleRequestRequestTypeDef",
     {
         "AssertionRule": NewAssertionRuleTypeDef,
@@ -848,36 +848,36 @@
     total=False,
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClusterResponseTypeDef = TypedDict(
     "DescribeClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClustersResponseTypeDef = TypedDict(
     "ListClustersResponseTypeDef",
     {
         "Clusters": List[ClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSafetyRulesResponseTypeDef = TypedDict(
     "ListSafetyRulesResponseTypeDef",
     {
         "NextToken": str,
         "SafetyRules": List[RuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/type_defs.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -23,66 +23,66 @@
 
 __all__ = (
     "RuleConfigTypeDef",
     "AssertionRuleUpdateTypeDef",
     "ClusterEndpointTypeDef",
     "ControlPanelTypeDef",
     "CreateClusterRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateControlPanelRequestRequestTypeDef",
     "CreateRoutingControlRequestRequestTypeDef",
     "RoutingControlTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteControlPanelRequestRequestTypeDef",
     "DeleteRoutingControlRequestRequestTypeDef",
     "DeleteSafetyRuleRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeControlPanelRequestRequestTypeDef",
     "DescribeRoutingControlRequestRequestTypeDef",
     "DescribeSafetyRuleRequestRequestTypeDef",
     "GatingRuleUpdateTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
     "ListAssociatedRoute53HealthChecksRequestRequestTypeDef",
+    "ListAssociatedRoute53HealthChecksResponseTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
     "ListControlPanelsRequestRequestTypeDef",
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsRequestRequestTypeDef",
+    "ListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
     "ListSafetyRulesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateControlPanelRequestRequestTypeDef",
     "UpdateRoutingControlRequestRequestTypeDef",
     "AssertionRuleTypeDef",
     "GatingRuleTypeDef",
     "NewAssertionRuleTypeDef",
     "NewGatingRuleTypeDef",
     "ClusterTypeDef",
     "CreateControlPanelResponseTypeDef",
     "DescribeControlPanelResponseTypeDef",
-    "ListAssociatedRoute53HealthChecksResponseTypeDef",
     "ListControlPanelsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateControlPanelResponseTypeDef",
     "CreateRoutingControlResponseTypeDef",
     "DescribeRoutingControlResponseTypeDef",
     "ListRoutingControlsResponseTypeDef",
     "UpdateRoutingControlResponseTypeDef",
     "DescribeClusterRequestClusterCreatedWaitTypeDef",
     "DescribeClusterRequestClusterDeletedWaitTypeDef",
     "DescribeControlPanelRequestControlPanelCreatedWaitTypeDef",
     "DescribeControlPanelRequestControlPanelDeletedWaitTypeDef",
     "DescribeRoutingControlRequestRoutingControlCreatedWaitTypeDef",
     "DescribeRoutingControlRequestRoutingControlDeletedWaitTypeDef",
     "UpdateSafetyRuleRequestRequestTypeDef",
-    "ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    "ListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
     "CreateSafetyRuleResponseTypeDef",
     "DescribeSafetyRuleResponseTypeDef",
     "RuleTypeDef",
     "UpdateSafetyRuleResponseTypeDef",
     "CreateSafetyRuleRequestRequestTypeDef",
     "CreateClusterResponseTypeDef",
     "DescribeClusterResponseTypeDef",
@@ -146,25 +146,14 @@
 )
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
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
 _RequiredCreateControlPanelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateControlPanelRequestRequestTypeDef",
     {
         "ClusterArn": str,
         "ControlPanelName": str,
     },
 )
@@ -286,24 +275,34 @@
     {
         "Name": str,
         "SafetyRuleArn": str,
         "WaitPeriodMs": int,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "RoutingControlArn": str,
+    },
+)
+_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef(
+    _RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
+    _OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef",
     {
         "RoutingControlArn": str,
     },
 )
 _OptionalListAssociatedRoute53HealthChecksRequestRequestTypeDef = TypedDict(
@@ -317,33 +316,79 @@
 
 class ListAssociatedRoute53HealthChecksRequestRequestTypeDef(
     _RequiredListAssociatedRoute53HealthChecksRequestRequestTypeDef,
     _OptionalListAssociatedRoute53HealthChecksRequestRequestTypeDef,
 ):
     pass
 
+ListAssociatedRoute53HealthChecksResponseTypeDef = TypedDict(
+    "ListAssociatedRoute53HealthChecksResponseTypeDef",
+    {
+        "HealthCheckIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListControlPanelsRequestListControlPanelsPaginateTypeDef = TypedDict(
+    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
+    {
+        "ClusterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListControlPanelsRequestRequestTypeDef = TypedDict(
     "ListControlPanelsRequestRequestTypeDef",
     {
         "ClusterArn": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
+    {
+        "ControlPanelArn": str,
+    },
+)
+_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRoutingControlsRequestListRoutingControlsPaginateTypeDef(
+    _RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
+    _OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRoutingControlsRequestRequestTypeDef = TypedDict(
     "_RequiredListRoutingControlsRequestRequestTypeDef",
     {
         "ControlPanelArn": str,
     },
 )
 _OptionalListRoutingControlsRequestRequestTypeDef = TypedDict(
@@ -357,14 +402,34 @@
 
 class ListRoutingControlsRequestRequestTypeDef(
     _RequiredListRoutingControlsRequestRequestTypeDef,
     _OptionalListRoutingControlsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
+    "_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
+    {
+        "ControlPanelArn": str,
+    },
+)
+_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
+    "_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSafetyRulesRequestListSafetyRulesPaginateTypeDef(
+    _RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
+    _OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
+):
+    pass
+
 _RequiredListSafetyRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListSafetyRulesRequestRequestTypeDef",
     {
         "ControlPanelArn": str,
     },
 )
 _OptionalListSafetyRulesRequestRequestTypeDef = TypedDict(
@@ -384,14 +449,43 @@
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
@@ -481,90 +575,73 @@
     total=False,
 )
 
 CreateControlPanelResponseTypeDef = TypedDict(
     "CreateControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeControlPanelResponseTypeDef = TypedDict(
     "DescribeControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedRoute53HealthChecksResponseTypeDef = TypedDict(
-    "ListAssociatedRoute53HealthChecksResponseTypeDef",
-    {
-        "HealthCheckIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlPanelsResponseTypeDef = TypedDict(
     "ListControlPanelsResponseTypeDef",
     {
         "ControlPanels": List[ControlPanelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateControlPanelResponseTypeDef = TypedDict(
     "UpdateControlPanelResponseTypeDef",
     {
         "ControlPanel": ControlPanelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRoutingControlResponseTypeDef = TypedDict(
     "CreateRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRoutingControlResponseTypeDef = TypedDict(
     "DescribeRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutingControlsResponseTypeDef = TypedDict(
     "ListRoutingControlsResponseTypeDef",
     {
         "NextToken": str,
         "RoutingControls": List[RoutingControlTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoutingControlResponseTypeDef = TypedDict(
     "UpdateRoutingControlResponseTypeDef",
     {
         "RoutingControl": RoutingControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeClusterRequestClusterCreatedWaitTypeDef = TypedDict(
     "_RequiredDescribeClusterRequestClusterCreatedWaitTypeDef",
     {
         "ClusterArn": str,
@@ -689,106 +766,29 @@
     {
         "AssertionRuleUpdate": AssertionRuleUpdateTypeDef,
         "GatingRuleUpdate": GatingRuleUpdateTypeDef,
     },
     total=False,
 )
 
-_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    {
-        "RoutingControlArn": str,
-    },
-)
-_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef(
-    _RequiredListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-    _OptionalListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-):
-    pass
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListControlPanelsRequestListControlPanelsPaginateTypeDef = TypedDict(
-    "ListControlPanelsRequestListControlPanelsPaginateTypeDef",
-    {
-        "ClusterArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "_RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-    },
-)
-_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "_OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRoutingControlsRequestListRoutingControlsPaginateTypeDef(
-    _RequiredListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-    _OptionalListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-):
-    pass
-
-_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
-    "_RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-    },
-)
-_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef = TypedDict(
-    "_OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSafetyRulesRequestListSafetyRulesPaginateTypeDef(
-    _RequiredListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
-    _OptionalListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
-):
-    pass
-
 CreateSafetyRuleResponseTypeDef = TypedDict(
     "CreateSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSafetyRuleResponseTypeDef = TypedDict(
     "DescribeSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "ASSERTION": AssertionRuleTypeDef,
@@ -798,15 +798,15 @@
 )
 
 UpdateSafetyRuleResponseTypeDef = TypedDict(
     "UpdateSafetyRuleResponseTypeDef",
     {
         "AssertionRule": AssertionRuleTypeDef,
         "GatingRule": GatingRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSafetyRuleRequestRequestTypeDef = TypedDict(
     "CreateSafetyRuleRequestRequestTypeDef",
     {
         "AssertionRule": NewAssertionRuleTypeDef,
@@ -817,36 +817,36 @@
     total=False,
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClusterResponseTypeDef = TypedDict(
     "DescribeClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClustersResponseTypeDef = TypedDict(
     "ListClustersResponseTypeDef",
     {
         "Clusters": List[ClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSafetyRulesResponseTypeDef = TypedDict(
     "ListSafetyRulesResponseTypeDef",
     {
         "NextToken": str,
         "SafetyRules": List[RuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/waiter.py` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config/waiter.pyi` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/PKG-INFO` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-control-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryControlConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-control-config"></a>
 
 # types-aiobotocore-route53-recovery-control-config
 
 [![PyPI - types-aiobotocore-route53-recovery-control-config](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-control-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-control-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-control-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-control-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryControlConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
+[aiobotocore.Route53RecoveryControlConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-control-config.html#Route53RecoveryControlConfig)
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
 [types-aiobotocore-route53-recovery-control-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_control_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,66 +399,66 @@
 ```python
 from types_aiobotocore_route53_recovery_control_config.type_defs import (
     RuleConfigTypeDef,
     AssertionRuleUpdateTypeDef,
     ClusterEndpointTypeDef,
     ControlPanelTypeDef,
     CreateClusterRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateControlPanelRequestRequestTypeDef,
     CreateRoutingControlRequestRequestTypeDef,
     RoutingControlTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteControlPanelRequestRequestTypeDef,
     DeleteRoutingControlRequestRequestTypeDef,
     DeleteSafetyRuleRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeControlPanelRequestRequestTypeDef,
     DescribeRoutingControlRequestRequestTypeDef,
     DescribeSafetyRuleRequestRequestTypeDef,
     GatingRuleUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
     ListAssociatedRoute53HealthChecksRequestRequestTypeDef,
+    ListAssociatedRoute53HealthChecksResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
     ListControlPanelsRequestRequestTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
+    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     ListSafetyRulesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateControlPanelRequestRequestTypeDef,
     UpdateRoutingControlRequestRequestTypeDef,
     AssertionRuleTypeDef,
     GatingRuleTypeDef,
     NewAssertionRuleTypeDef,
     NewGatingRuleTypeDef,
     ClusterTypeDef,
     CreateControlPanelResponseTypeDef,
     DescribeControlPanelResponseTypeDef,
-    ListAssociatedRoute53HealthChecksResponseTypeDef,
     ListControlPanelsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateControlPanelResponseTypeDef,
     CreateRoutingControlResponseTypeDef,
     DescribeRoutingControlResponseTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlResponseTypeDef,
     DescribeClusterRequestClusterCreatedWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeControlPanelRequestControlPanelCreatedWaitTypeDef,
     DescribeControlPanelRequestControlPanelDeletedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlCreatedWaitTypeDef,
     DescribeRoutingControlRequestRoutingControlDeletedWaitTypeDef,
     UpdateSafetyRuleRequestRequestTypeDef,
-    ListAssociatedRoute53HealthChecksRequestListAssociatedRoute53HealthChecksPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListControlPanelsRequestListControlPanelsPaginateTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
-    ListSafetyRulesRequestListSafetyRulesPaginateTypeDef,
     CreateSafetyRuleResponseTypeDef,
     DescribeSafetyRuleResponseTypeDef,
     RuleTypeDef,
     UpdateSafetyRuleResponseTypeDef,
     CreateSafetyRuleRequestRequestTypeDef,
     CreateClusterResponseTypeDef,
     DescribeClusterResponseTypeDef,
@@ -474,43 +474,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-control-config-2.5.0.post1/types_aiobotocore_route53_recovery_control_config.egg-info/SOURCES.txt` & `types-aiobotocore-route53-recovery-control-config-2.5.1/types_aiobotocore_route53_recovery_control_config.egg-info/SOURCES.txt`

 * *Files identical despite different names*

