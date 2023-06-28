# Comparing `tmp/types-aiobotocore-elb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-elb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-elb-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:36 2023, max compression
+gzip compressed data, was "types-aiobotocore-elb-2.5.1.tar", last modified: Wed Jun 28 01:43:28 2023, max compression
```

## Comparing `types-aiobotocore-elb-2.5.0.post1.tar` & `types-aiobotocore-elb-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.555195 types-aiobotocore-elb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17473 2023-03-11 12:26:36.555195 types-aiobotocore-elb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15901 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:36.555195 types-aiobotocore-elb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2089 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.555195 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/
--rw-r--r--   0 runner    (1001) docker     (123)     1609 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1608 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      950 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26720 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    26677 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8663 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8661 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3427 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3422 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    24575 2023-03-11 12:14:13.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24552 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3913 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3910 2023-03-11 12:14:12.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.555195 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17473 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:36.000000 types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:28.370134 types-aiobotocore-elb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17461 2023-06-28 01:43:28.366134 types-aiobotocore-elb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15895 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:28.370134 types-aiobotocore-elb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2083 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:28.366134 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/
+-rw-r--r--   0 runner    (1001) docker     (123)     1609 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1608 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26720 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26677 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8872 2023-06-28 01:30:48.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8870 2023-06-28 01:30:48.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3311 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3307 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    24613 2023-06-28 01:30:48.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24590 2023-06-28 01:30:48.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3913 2023-06-28 01:30:48.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3910 2023-06-28 01:30:47.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:28.366134 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17461 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:28.000000 types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-elb-2.5.0.post1/LICENSE` & `types-aiobotocore-elb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-elb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-elb-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticLoadBalancing 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticLoadBalancing 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elb"></a>
 
 # types-aiobotocore-elb
 
 [![PyPI - types-aiobotocore-elb](https://img.shields.io/pypi/v/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elb?color=blue)](https://pypistats.org/packages/types-aiobotocore-elb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticLoadBalancing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
+[aiobotocore.ElasticLoadBalancing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
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
 [types-aiobotocore-elb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -361,75 +361,75 @@
 `types_aiobotocore_elb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elb.type_defs import (
     AccessLogTypeDef,
     AddAvailabilityZonesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddAvailabilityZonesOutputTypeDef,
     TagTypeDef,
     AdditionalAttributeTypeDef,
     AppCookieStickinessPolicyTypeDef,
     ApplySecurityGroupsToLoadBalancerInputRequestTypeDef,
+    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
     AttachLoadBalancerToSubnetsInputRequestTypeDef,
+    AttachLoadBalancerToSubnetsOutputTypeDef,
     BackendServerDescriptionTypeDef,
     HealthCheckTypeDef,
     ConnectionDrainingTypeDef,
     ConnectionSettingsTypeDef,
     ListenerTypeDef,
+    CreateAccessPointOutputTypeDef,
     CreateAppCookieStickinessPolicyInputRequestTypeDef,
     CreateLBCookieStickinessPolicyInputRequestTypeDef,
     PolicyAttributeTypeDef,
     CrossZoneLoadBalancingTypeDef,
     DeleteAccessPointInputRequestTypeDef,
     DeleteLoadBalancerListenerInputRequestTypeDef,
     DeleteLoadBalancerPolicyInputRequestTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
     DescribeAccessPointsInputRequestTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     LimitTypeDef,
     WaiterConfigTypeDef,
     InstanceStateTypeDef,
     DescribeLoadBalancerAttributesInputRequestTypeDef,
     DescribeLoadBalancerPoliciesInputRequestTypeDef,
     DescribeLoadBalancerPolicyTypesInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     DetachLoadBalancerFromSubnetsInputRequestTypeDef,
+    DetachLoadBalancerFromSubnetsOutputTypeDef,
     LBCookieStickinessPolicyTypeDef,
     SourceSecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttributeDescriptionTypeDef,
     PolicyAttributeTypeDescriptionTypeDef,
     RemoveAvailabilityZonesInputRequestTypeDef,
+    RemoveAvailabilityZonesOutputTypeDef,
     TagKeyOnlyTypeDef,
+    ResponseMetadataTypeDef,
     SetLoadBalancerListenerSSLCertificateInputRequestTypeDef,
     SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef,
     SetLoadBalancerPoliciesOfListenerInputRequestTypeDef,
-    AddAvailabilityZonesOutputTypeDef,
-    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
-    AttachLoadBalancerToSubnetsOutputTypeDef,
-    CreateAccessPointOutputTypeDef,
-    DetachLoadBalancerFromSubnetsOutputTypeDef,
-    RemoveAvailabilityZonesOutputTypeDef,
     AddTagsInputRequestTypeDef,
     TagDescriptionTypeDef,
     ConfigureHealthCheckInputRequestTypeDef,
     ConfigureHealthCheckOutputTypeDef,
     CreateAccessPointInputRequestTypeDef,
     CreateLoadBalancerListenerInputRequestTypeDef,
     ListenerDescriptionTypeDef,
     CreateLoadBalancerPolicyInputRequestTypeDef,
     LoadBalancerAttributesTypeDef,
     DeregisterEndPointsInputRequestTypeDef,
     DeregisterEndPointsOutputTypeDef,
     DescribeEndPointStateInputRequestTypeDef,
     RegisterEndPointsInputRequestTypeDef,
     RegisterEndPointsOutputTypeDef,
-    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     DescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef,
     DescribeEndPointStateInputInstanceDeregisteredWaitTypeDef,
     DescribeEndPointStateInputInstanceInServiceWaitTypeDef,
     DescribeEndPointStateOutputTypeDef,
     PoliciesTypeDef,
     PolicyDescriptionTypeDef,
@@ -453,43 +453,43 @@
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/README.md` & `types-aiobotocore-elb-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-elb"></a>
 
 # types-aiobotocore-elb
 
 [![PyPI - types-aiobotocore-elb](https://img.shields.io/pypi/v/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elb?color=blue)](https://pypistats.org/packages/types-aiobotocore-elb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticLoadBalancing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
+[aiobotocore.ElasticLoadBalancing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
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
 [types-aiobotocore-elb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -328,75 +328,75 @@
 `types_aiobotocore_elb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elb.type_defs import (
     AccessLogTypeDef,
     AddAvailabilityZonesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddAvailabilityZonesOutputTypeDef,
     TagTypeDef,
     AdditionalAttributeTypeDef,
     AppCookieStickinessPolicyTypeDef,
     ApplySecurityGroupsToLoadBalancerInputRequestTypeDef,
+    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
     AttachLoadBalancerToSubnetsInputRequestTypeDef,
+    AttachLoadBalancerToSubnetsOutputTypeDef,
     BackendServerDescriptionTypeDef,
     HealthCheckTypeDef,
     ConnectionDrainingTypeDef,
     ConnectionSettingsTypeDef,
     ListenerTypeDef,
+    CreateAccessPointOutputTypeDef,
     CreateAppCookieStickinessPolicyInputRequestTypeDef,
     CreateLBCookieStickinessPolicyInputRequestTypeDef,
     PolicyAttributeTypeDef,
     CrossZoneLoadBalancingTypeDef,
     DeleteAccessPointInputRequestTypeDef,
     DeleteLoadBalancerListenerInputRequestTypeDef,
     DeleteLoadBalancerPolicyInputRequestTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
     DescribeAccessPointsInputRequestTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     LimitTypeDef,
     WaiterConfigTypeDef,
     InstanceStateTypeDef,
     DescribeLoadBalancerAttributesInputRequestTypeDef,
     DescribeLoadBalancerPoliciesInputRequestTypeDef,
     DescribeLoadBalancerPolicyTypesInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     DetachLoadBalancerFromSubnetsInputRequestTypeDef,
+    DetachLoadBalancerFromSubnetsOutputTypeDef,
     LBCookieStickinessPolicyTypeDef,
     SourceSecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttributeDescriptionTypeDef,
     PolicyAttributeTypeDescriptionTypeDef,
     RemoveAvailabilityZonesInputRequestTypeDef,
+    RemoveAvailabilityZonesOutputTypeDef,
     TagKeyOnlyTypeDef,
+    ResponseMetadataTypeDef,
     SetLoadBalancerListenerSSLCertificateInputRequestTypeDef,
     SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef,
     SetLoadBalancerPoliciesOfListenerInputRequestTypeDef,
-    AddAvailabilityZonesOutputTypeDef,
-    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
-    AttachLoadBalancerToSubnetsOutputTypeDef,
-    CreateAccessPointOutputTypeDef,
-    DetachLoadBalancerFromSubnetsOutputTypeDef,
-    RemoveAvailabilityZonesOutputTypeDef,
     AddTagsInputRequestTypeDef,
     TagDescriptionTypeDef,
     ConfigureHealthCheckInputRequestTypeDef,
     ConfigureHealthCheckOutputTypeDef,
     CreateAccessPointInputRequestTypeDef,
     CreateLoadBalancerListenerInputRequestTypeDef,
     ListenerDescriptionTypeDef,
     CreateLoadBalancerPolicyInputRequestTypeDef,
     LoadBalancerAttributesTypeDef,
     DeregisterEndPointsInputRequestTypeDef,
     DeregisterEndPointsOutputTypeDef,
     DescribeEndPointStateInputRequestTypeDef,
     RegisterEndPointsInputRequestTypeDef,
     RegisterEndPointsOutputTypeDef,
-    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     DescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef,
     DescribeEndPointStateInputInstanceDeregisteredWaitTypeDef,
     DescribeEndPointStateInputInstanceInServiceWaitTypeDef,
     DescribeEndPointStateOutputTypeDef,
     PoliciesTypeDef,
     PolicyDescriptionTypeDef,
@@ -420,43 +420,43 @@
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/setup.py` & `types-aiobotocore-elb-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-elb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-elb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_elb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElasticLoadBalancing 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElasticLoadBalancing 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/",
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__init__.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__init__.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/__main__.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElasticLoadBalancing 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElasticLoadBalancing 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing\nOther"
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/client.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/client.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/literals.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -98,14 +98,15 @@
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
@@ -184,14 +185,15 @@
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
@@ -202,14 +204,15 @@
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
@@ -245,14 +248,15 @@
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
@@ -271,16 +275,19 @@
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
@@ -364,15 +371,17 @@
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/literals.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -96,14 +96,15 @@
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
@@ -182,14 +183,15 @@
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
@@ -200,14 +202,15 @@
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
@@ -243,14 +246,15 @@
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
@@ -269,16 +273,19 @@
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
@@ -362,15 +369,17 @@
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/paginator.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,69 +18,58 @@
     with session.create_client("elb") as client:
         client: ElasticLoadBalancingClient
 
         describe_account_limits_paginator: DescribeAccountLimitsPaginator = client.get_paginator("describe_account_limits")
         describe_load_balancers_paginator: DescribeLoadBalancersPaginator = client.get_paginator("describe_load_balancers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAccessPointsOutputTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeAccountLimitsPaginator", "DescribeLoadBalancersPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeAccountLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeAccountLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeaccountlimitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccountLimitsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeAccountLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeaccountlimitspaginator)
         """
 
-
 class DescribeLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeloadbalancerspaginator)
     """
 
     def paginate(
         self,
         *,
         LoadBalancerNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccessPointsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeloadbalancerspaginator)
         """
```

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/paginator.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/paginator.py`

 * *Files 9% similar despite different names*

```diff
@@ -18,64 +18,62 @@
     with session.create_client("elb") as client:
         client: ElasticLoadBalancingClient
 
         describe_account_limits_paginator: DescribeAccountLimitsPaginator = client.get_paginator("describe_account_limits")
         describe_load_balancers_paginator: DescribeLoadBalancersPaginator = client.get_paginator("describe_load_balancers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAccessPointsOutputTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeAccountLimitsPaginator", "DescribeLoadBalancersPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeAccountLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeAccountLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeaccountlimitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccountLimitsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeAccountLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeaccountlimitspaginator)
         """
 
+
 class DescribeLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeloadbalancerspaginator)
     """
 
     def paginate(
         self,
         *,
         LoadBalancerNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAccessPointsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing.Paginator.DescribeLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/paginators/#describeloadbalancerspaginator)
         """
```

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/type_defs.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -20,75 +20,75 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccessLogTypeDef",
     "AddAvailabilityZonesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddAvailabilityZonesOutputTypeDef",
     "TagTypeDef",
     "AdditionalAttributeTypeDef",
     "AppCookieStickinessPolicyTypeDef",
     "ApplySecurityGroupsToLoadBalancerInputRequestTypeDef",
+    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
     "AttachLoadBalancerToSubnetsInputRequestTypeDef",
+    "AttachLoadBalancerToSubnetsOutputTypeDef",
     "BackendServerDescriptionTypeDef",
     "HealthCheckTypeDef",
     "ConnectionDrainingTypeDef",
     "ConnectionSettingsTypeDef",
     "ListenerTypeDef",
+    "CreateAccessPointOutputTypeDef",
     "CreateAppCookieStickinessPolicyInputRequestTypeDef",
     "CreateLBCookieStickinessPolicyInputRequestTypeDef",
     "PolicyAttributeTypeDef",
     "CrossZoneLoadBalancingTypeDef",
     "DeleteAccessPointInputRequestTypeDef",
     "DeleteLoadBalancerListenerInputRequestTypeDef",
     "DeleteLoadBalancerPolicyInputRequestTypeDef",
     "InstanceTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
     "DescribeAccessPointsInputRequestTypeDef",
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsInputRequestTypeDef",
     "LimitTypeDef",
     "WaiterConfigTypeDef",
     "InstanceStateTypeDef",
     "DescribeLoadBalancerAttributesInputRequestTypeDef",
     "DescribeLoadBalancerPoliciesInputRequestTypeDef",
     "DescribeLoadBalancerPolicyTypesInputRequestTypeDef",
     "DescribeTagsInputRequestTypeDef",
     "DetachLoadBalancerFromSubnetsInputRequestTypeDef",
+    "DetachLoadBalancerFromSubnetsOutputTypeDef",
     "LBCookieStickinessPolicyTypeDef",
     "SourceSecurityGroupTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyAttributeDescriptionTypeDef",
     "PolicyAttributeTypeDescriptionTypeDef",
     "RemoveAvailabilityZonesInputRequestTypeDef",
+    "RemoveAvailabilityZonesOutputTypeDef",
     "TagKeyOnlyTypeDef",
+    "ResponseMetadataTypeDef",
     "SetLoadBalancerListenerSSLCertificateInputRequestTypeDef",
     "SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef",
     "SetLoadBalancerPoliciesOfListenerInputRequestTypeDef",
-    "AddAvailabilityZonesOutputTypeDef",
-    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
-    "AttachLoadBalancerToSubnetsOutputTypeDef",
-    "CreateAccessPointOutputTypeDef",
-    "DetachLoadBalancerFromSubnetsOutputTypeDef",
-    "RemoveAvailabilityZonesOutputTypeDef",
     "AddTagsInputRequestTypeDef",
     "TagDescriptionTypeDef",
     "ConfigureHealthCheckInputRequestTypeDef",
     "ConfigureHealthCheckOutputTypeDef",
     "CreateAccessPointInputRequestTypeDef",
     "CreateLoadBalancerListenerInputRequestTypeDef",
     "ListenerDescriptionTypeDef",
     "CreateLoadBalancerPolicyInputRequestTypeDef",
     "LoadBalancerAttributesTypeDef",
     "DeregisterEndPointsInputRequestTypeDef",
     "DeregisterEndPointsOutputTypeDef",
     "DescribeEndPointStateInputRequestTypeDef",
     "RegisterEndPointsInputRequestTypeDef",
     "RegisterEndPointsOutputTypeDef",
-    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsOutputTypeDef",
     "DescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef",
     "DescribeEndPointStateInputInstanceDeregisteredWaitTypeDef",
     "DescribeEndPointStateInputInstanceInServiceWaitTypeDef",
     "DescribeEndPointStateOutputTypeDef",
     "PoliciesTypeDef",
     "PolicyDescriptionTypeDef",
@@ -129,22 +129,19 @@
     "AddAvailabilityZonesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "AvailabilityZones": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddAvailabilityZonesOutputTypeDef = TypedDict(
+    "AddAvailabilityZonesOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AvailabilityZones": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
@@ -185,22 +182,38 @@
     "ApplySecurityGroupsToLoadBalancerInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "SecurityGroups": Sequence[str],
     },
 )
 
+ApplySecurityGroupsToLoadBalancerOutputTypeDef = TypedDict(
+    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
+    {
+        "SecurityGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttachLoadBalancerToSubnetsInputRequestTypeDef = TypedDict(
     "AttachLoadBalancerToSubnetsInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "Subnets": Sequence[str],
     },
 )
 
+AttachLoadBalancerToSubnetsOutputTypeDef = TypedDict(
+    "AttachLoadBalancerToSubnetsOutputTypeDef",
+    {
+        "Subnets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackendServerDescriptionTypeDef = TypedDict(
     "BackendServerDescriptionTypeDef",
     {
         "InstancePort": int,
         "PolicyNames": List[str],
     },
     total=False,
@@ -263,14 +276,22 @@
 )
 
 
 class ListenerTypeDef(_RequiredListenerTypeDef, _OptionalListenerTypeDef):
     pass
 
 
+CreateAccessPointOutputTypeDef = TypedDict(
+    "CreateAccessPointOutputTypeDef",
+    {
+        "DNSName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateAppCookieStickinessPolicyInputRequestTypeDef = TypedDict(
     "CreateAppCookieStickinessPolicyInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "PolicyName": str,
         "CookieName": str,
     },
@@ -342,34 +363,41 @@
     "InstanceTypeDef",
     {
         "InstanceId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "LoadBalancerNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAccessPointsInputRequestTypeDef = TypedDict(
     "DescribeAccessPointsInputRequestTypeDef",
     {
         "LoadBalancerNames": Sequence[str],
         "Marker": str,
         "PageSize": int,
     },
     total=False,
 )
 
+DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAccountLimitsInputRequestTypeDef = TypedDict(
     "DescribeAccountLimitsInputRequestTypeDef",
     {
         "Marker": str,
         "PageSize": int,
     },
     total=False,
@@ -439,14 +467,22 @@
     "DetachLoadBalancerFromSubnetsInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "Subnets": Sequence[str],
     },
 )
 
+DetachLoadBalancerFromSubnetsOutputTypeDef = TypedDict(
+    "DetachLoadBalancerFromSubnetsOutputTypeDef",
+    {
+        "Subnets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LBCookieStickinessPolicyTypeDef = TypedDict(
     "LBCookieStickinessPolicyTypeDef",
     {
         "PolicyName": str,
         "CookieExpirationPeriod": int,
     },
     total=False,
@@ -457,14 +493,24 @@
     {
         "OwnerAlias": str,
         "GroupName": str,
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
 PolicyAttributeDescriptionTypeDef = TypedDict(
     "PolicyAttributeDescriptionTypeDef",
     {
         "AttributeName": str,
         "AttributeValue": str,
     },
     total=False,
@@ -486,22 +532,41 @@
     "RemoveAvailabilityZonesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "AvailabilityZones": Sequence[str],
     },
 )
 
+RemoveAvailabilityZonesOutputTypeDef = TypedDict(
+    "RemoveAvailabilityZonesOutputTypeDef",
+    {
+        "AvailabilityZones": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagKeyOnlyTypeDef = TypedDict(
     "TagKeyOnlyTypeDef",
     {
         "Key": str,
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
 SetLoadBalancerListenerSSLCertificateInputRequestTypeDef = TypedDict(
     "SetLoadBalancerListenerSSLCertificateInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "LoadBalancerPort": int,
         "SSLCertificateId": str,
     },
@@ -521,62 +586,14 @@
     {
         "LoadBalancerName": str,
         "LoadBalancerPort": int,
         "PolicyNames": Sequence[str],
     },
 )
 
-AddAvailabilityZonesOutputTypeDef = TypedDict(
-    "AddAvailabilityZonesOutputTypeDef",
-    {
-        "AvailabilityZones": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ApplySecurityGroupsToLoadBalancerOutputTypeDef = TypedDict(
-    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
-    {
-        "SecurityGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachLoadBalancerToSubnetsOutputTypeDef = TypedDict(
-    "AttachLoadBalancerToSubnetsOutputTypeDef",
-    {
-        "Subnets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessPointOutputTypeDef = TypedDict(
-    "CreateAccessPointOutputTypeDef",
-    {
-        "DNSName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachLoadBalancerFromSubnetsOutputTypeDef = TypedDict(
-    "DetachLoadBalancerFromSubnetsOutputTypeDef",
-    {
-        "Subnets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveAvailabilityZonesOutputTypeDef = TypedDict(
-    "RemoveAvailabilityZonesOutputTypeDef",
-    {
-        "AvailabilityZones": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AddTagsInputRequestTypeDef = TypedDict(
     "AddTagsInputRequestTypeDef",
     {
         "LoadBalancerNames": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -598,15 +615,15 @@
     },
 )
 
 ConfigureHealthCheckOutputTypeDef = TypedDict(
     "ConfigureHealthCheckOutputTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAccessPointInputRequestTypeDef = TypedDict(
     "_RequiredCreateAccessPointInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -693,15 +710,15 @@
     },
 )
 
 DeregisterEndPointsOutputTypeDef = TypedDict(
     "DeregisterEndPointsOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeEndPointStateInputRequestTypeDef = TypedDict(
     "_RequiredDescribeEndPointStateInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -731,41 +748,24 @@
     },
 )
 
 RegisterEndPointsOutputTypeDef = TypedDict(
     "RegisterEndPointsOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
-    {
-        "LoadBalancerNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeAccountLimitsOutputTypeDef = TypedDict(
     "DescribeAccountLimitsOutputTypeDef",
     {
         "Limits": List[LimitTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef = TypedDict(
     "_RequiredDescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef",
     {
         "LoadBalancerName": str,
@@ -834,15 +834,15 @@
     pass
 
 
 DescribeEndPointStateOutputTypeDef = TypedDict(
     "DescribeEndPointStateOutputTypeDef",
     {
         "InstanceStates": List[InstanceStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PoliciesTypeDef = TypedDict(
     "PoliciesTypeDef",
     {
         "AppCookieStickinessPolicies": List[AppCookieStickinessPolicyTypeDef],
@@ -880,23 +880,23 @@
     },
 )
 
 DescribeTagsOutputTypeDef = TypedDict(
     "DescribeTagsOutputTypeDef",
     {
         "TagDescriptions": List[TagDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerAttributesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerAttributesOutputTypeDef",
     {
         "LoadBalancerAttributes": LoadBalancerAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyLoadBalancerAttributesInputRequestTypeDef = TypedDict(
     "ModifyLoadBalancerAttributesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -905,15 +905,15 @@
 )
 
 ModifyLoadBalancerAttributesOutputTypeDef = TypedDict(
     "ModifyLoadBalancerAttributesOutputTypeDef",
     {
         "LoadBalancerName": str,
         "LoadBalancerAttributes": LoadBalancerAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoadBalancerDescriptionTypeDef = TypedDict(
     "LoadBalancerDescriptionTypeDef",
     {
         "LoadBalancerName": str,
@@ -936,27 +936,27 @@
     total=False,
 )
 
 DescribeLoadBalancerPoliciesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerPoliciesOutputTypeDef",
     {
         "PolicyDescriptions": List[PolicyDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerPolicyTypesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerPolicyTypesOutputTypeDef",
     {
         "PolicyTypeDescriptions": List[PolicyTypeDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccessPointsOutputTypeDef = TypedDict(
     "DescribeAccessPointsOutputTypeDef",
     {
         "LoadBalancerDescriptions": List[LoadBalancerDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/type_defs.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -19,75 +19,75 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccessLogTypeDef",
     "AddAvailabilityZonesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddAvailabilityZonesOutputTypeDef",
     "TagTypeDef",
     "AdditionalAttributeTypeDef",
     "AppCookieStickinessPolicyTypeDef",
     "ApplySecurityGroupsToLoadBalancerInputRequestTypeDef",
+    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
     "AttachLoadBalancerToSubnetsInputRequestTypeDef",
+    "AttachLoadBalancerToSubnetsOutputTypeDef",
     "BackendServerDescriptionTypeDef",
     "HealthCheckTypeDef",
     "ConnectionDrainingTypeDef",
     "ConnectionSettingsTypeDef",
     "ListenerTypeDef",
+    "CreateAccessPointOutputTypeDef",
     "CreateAppCookieStickinessPolicyInputRequestTypeDef",
     "CreateLBCookieStickinessPolicyInputRequestTypeDef",
     "PolicyAttributeTypeDef",
     "CrossZoneLoadBalancingTypeDef",
     "DeleteAccessPointInputRequestTypeDef",
     "DeleteLoadBalancerListenerInputRequestTypeDef",
     "DeleteLoadBalancerPolicyInputRequestTypeDef",
     "InstanceTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
     "DescribeAccessPointsInputRequestTypeDef",
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsInputRequestTypeDef",
     "LimitTypeDef",
     "WaiterConfigTypeDef",
     "InstanceStateTypeDef",
     "DescribeLoadBalancerAttributesInputRequestTypeDef",
     "DescribeLoadBalancerPoliciesInputRequestTypeDef",
     "DescribeLoadBalancerPolicyTypesInputRequestTypeDef",
     "DescribeTagsInputRequestTypeDef",
     "DetachLoadBalancerFromSubnetsInputRequestTypeDef",
+    "DetachLoadBalancerFromSubnetsOutputTypeDef",
     "LBCookieStickinessPolicyTypeDef",
     "SourceSecurityGroupTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyAttributeDescriptionTypeDef",
     "PolicyAttributeTypeDescriptionTypeDef",
     "RemoveAvailabilityZonesInputRequestTypeDef",
+    "RemoveAvailabilityZonesOutputTypeDef",
     "TagKeyOnlyTypeDef",
+    "ResponseMetadataTypeDef",
     "SetLoadBalancerListenerSSLCertificateInputRequestTypeDef",
     "SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef",
     "SetLoadBalancerPoliciesOfListenerInputRequestTypeDef",
-    "AddAvailabilityZonesOutputTypeDef",
-    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
-    "AttachLoadBalancerToSubnetsOutputTypeDef",
-    "CreateAccessPointOutputTypeDef",
-    "DetachLoadBalancerFromSubnetsOutputTypeDef",
-    "RemoveAvailabilityZonesOutputTypeDef",
     "AddTagsInputRequestTypeDef",
     "TagDescriptionTypeDef",
     "ConfigureHealthCheckInputRequestTypeDef",
     "ConfigureHealthCheckOutputTypeDef",
     "CreateAccessPointInputRequestTypeDef",
     "CreateLoadBalancerListenerInputRequestTypeDef",
     "ListenerDescriptionTypeDef",
     "CreateLoadBalancerPolicyInputRequestTypeDef",
     "LoadBalancerAttributesTypeDef",
     "DeregisterEndPointsInputRequestTypeDef",
     "DeregisterEndPointsOutputTypeDef",
     "DescribeEndPointStateInputRequestTypeDef",
     "RegisterEndPointsInputRequestTypeDef",
     "RegisterEndPointsOutputTypeDef",
-    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
     "DescribeAccountLimitsOutputTypeDef",
     "DescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef",
     "DescribeEndPointStateInputInstanceDeregisteredWaitTypeDef",
     "DescribeEndPointStateInputInstanceInServiceWaitTypeDef",
     "DescribeEndPointStateOutputTypeDef",
     "PoliciesTypeDef",
     "PolicyDescriptionTypeDef",
@@ -126,22 +126,19 @@
     "AddAvailabilityZonesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "AvailabilityZones": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddAvailabilityZonesOutputTypeDef = TypedDict(
+    "AddAvailabilityZonesOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AvailabilityZones": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
@@ -180,22 +177,38 @@
     "ApplySecurityGroupsToLoadBalancerInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "SecurityGroups": Sequence[str],
     },
 )
 
+ApplySecurityGroupsToLoadBalancerOutputTypeDef = TypedDict(
+    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
+    {
+        "SecurityGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttachLoadBalancerToSubnetsInputRequestTypeDef = TypedDict(
     "AttachLoadBalancerToSubnetsInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "Subnets": Sequence[str],
     },
 )
 
+AttachLoadBalancerToSubnetsOutputTypeDef = TypedDict(
+    "AttachLoadBalancerToSubnetsOutputTypeDef",
+    {
+        "Subnets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackendServerDescriptionTypeDef = TypedDict(
     "BackendServerDescriptionTypeDef",
     {
         "InstancePort": int,
         "PolicyNames": List[str],
     },
     total=False,
@@ -254,14 +267,22 @@
     },
     total=False,
 )
 
 class ListenerTypeDef(_RequiredListenerTypeDef, _OptionalListenerTypeDef):
     pass
 
+CreateAccessPointOutputTypeDef = TypedDict(
+    "CreateAccessPointOutputTypeDef",
+    {
+        "DNSName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateAppCookieStickinessPolicyInputRequestTypeDef = TypedDict(
     "CreateAppCookieStickinessPolicyInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "PolicyName": str,
         "CookieName": str,
     },
@@ -331,34 +352,41 @@
     "InstanceTypeDef",
     {
         "InstanceId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "LoadBalancerNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAccessPointsInputRequestTypeDef = TypedDict(
     "DescribeAccessPointsInputRequestTypeDef",
     {
         "LoadBalancerNames": Sequence[str],
         "Marker": str,
         "PageSize": int,
     },
     total=False,
 )
 
+DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
+    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAccountLimitsInputRequestTypeDef = TypedDict(
     "DescribeAccountLimitsInputRequestTypeDef",
     {
         "Marker": str,
         "PageSize": int,
     },
     total=False,
@@ -428,14 +456,22 @@
     "DetachLoadBalancerFromSubnetsInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "Subnets": Sequence[str],
     },
 )
 
+DetachLoadBalancerFromSubnetsOutputTypeDef = TypedDict(
+    "DetachLoadBalancerFromSubnetsOutputTypeDef",
+    {
+        "Subnets": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LBCookieStickinessPolicyTypeDef = TypedDict(
     "LBCookieStickinessPolicyTypeDef",
     {
         "PolicyName": str,
         "CookieExpirationPeriod": int,
     },
     total=False,
@@ -446,14 +482,24 @@
     {
         "OwnerAlias": str,
         "GroupName": str,
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
 PolicyAttributeDescriptionTypeDef = TypedDict(
     "PolicyAttributeDescriptionTypeDef",
     {
         "AttributeName": str,
         "AttributeValue": str,
     },
     total=False,
@@ -475,22 +521,41 @@
     "RemoveAvailabilityZonesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "AvailabilityZones": Sequence[str],
     },
 )
 
+RemoveAvailabilityZonesOutputTypeDef = TypedDict(
+    "RemoveAvailabilityZonesOutputTypeDef",
+    {
+        "AvailabilityZones": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagKeyOnlyTypeDef = TypedDict(
     "TagKeyOnlyTypeDef",
     {
         "Key": str,
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
 SetLoadBalancerListenerSSLCertificateInputRequestTypeDef = TypedDict(
     "SetLoadBalancerListenerSSLCertificateInputRequestTypeDef",
     {
         "LoadBalancerName": str,
         "LoadBalancerPort": int,
         "SSLCertificateId": str,
     },
@@ -510,62 +575,14 @@
     {
         "LoadBalancerName": str,
         "LoadBalancerPort": int,
         "PolicyNames": Sequence[str],
     },
 )
 
-AddAvailabilityZonesOutputTypeDef = TypedDict(
-    "AddAvailabilityZonesOutputTypeDef",
-    {
-        "AvailabilityZones": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ApplySecurityGroupsToLoadBalancerOutputTypeDef = TypedDict(
-    "ApplySecurityGroupsToLoadBalancerOutputTypeDef",
-    {
-        "SecurityGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachLoadBalancerToSubnetsOutputTypeDef = TypedDict(
-    "AttachLoadBalancerToSubnetsOutputTypeDef",
-    {
-        "Subnets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessPointOutputTypeDef = TypedDict(
-    "CreateAccessPointOutputTypeDef",
-    {
-        "DNSName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachLoadBalancerFromSubnetsOutputTypeDef = TypedDict(
-    "DetachLoadBalancerFromSubnetsOutputTypeDef",
-    {
-        "Subnets": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveAvailabilityZonesOutputTypeDef = TypedDict(
-    "RemoveAvailabilityZonesOutputTypeDef",
-    {
-        "AvailabilityZones": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AddTagsInputRequestTypeDef = TypedDict(
     "AddTagsInputRequestTypeDef",
     {
         "LoadBalancerNames": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -587,15 +604,15 @@
     },
 )
 
 ConfigureHealthCheckOutputTypeDef = TypedDict(
     "ConfigureHealthCheckOutputTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAccessPointInputRequestTypeDef = TypedDict(
     "_RequiredCreateAccessPointInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -678,15 +695,15 @@
     },
 )
 
 DeregisterEndPointsOutputTypeDef = TypedDict(
     "DeregisterEndPointsOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeEndPointStateInputRequestTypeDef = TypedDict(
     "_RequiredDescribeEndPointStateInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -714,41 +731,24 @@
     },
 )
 
 RegisterEndPointsOutputTypeDef = TypedDict(
     "RegisterEndPointsOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef",
-    {
-        "LoadBalancerNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef = TypedDict(
-    "DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeAccountLimitsOutputTypeDef = TypedDict(
     "DescribeAccountLimitsOutputTypeDef",
     {
         "Limits": List[LimitTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef = TypedDict(
     "_RequiredDescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef",
     {
         "LoadBalancerName": str,
@@ -811,15 +811,15 @@
 ):
     pass
 
 DescribeEndPointStateOutputTypeDef = TypedDict(
     "DescribeEndPointStateOutputTypeDef",
     {
         "InstanceStates": List[InstanceStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PoliciesTypeDef = TypedDict(
     "PoliciesTypeDef",
     {
         "AppCookieStickinessPolicies": List[AppCookieStickinessPolicyTypeDef],
@@ -857,23 +857,23 @@
     },
 )
 
 DescribeTagsOutputTypeDef = TypedDict(
     "DescribeTagsOutputTypeDef",
     {
         "TagDescriptions": List[TagDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerAttributesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerAttributesOutputTypeDef",
     {
         "LoadBalancerAttributes": LoadBalancerAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyLoadBalancerAttributesInputRequestTypeDef = TypedDict(
     "ModifyLoadBalancerAttributesInputRequestTypeDef",
     {
         "LoadBalancerName": str,
@@ -882,15 +882,15 @@
 )
 
 ModifyLoadBalancerAttributesOutputTypeDef = TypedDict(
     "ModifyLoadBalancerAttributesOutputTypeDef",
     {
         "LoadBalancerName": str,
         "LoadBalancerAttributes": LoadBalancerAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoadBalancerDescriptionTypeDef = TypedDict(
     "LoadBalancerDescriptionTypeDef",
     {
         "LoadBalancerName": str,
@@ -913,27 +913,27 @@
     total=False,
 )
 
 DescribeLoadBalancerPoliciesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerPoliciesOutputTypeDef",
     {
         "PolicyDescriptions": List[PolicyDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerPolicyTypesOutputTypeDef = TypedDict(
     "DescribeLoadBalancerPolicyTypesOutputTypeDef",
     {
         "PolicyTypeDescriptions": List[PolicyTypeDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccessPointsOutputTypeDef = TypedDict(
     "DescribeAccessPointsOutputTypeDef",
     {
         "LoadBalancerDescriptions": List[LoadBalancerDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/waiter.py` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb/waiter.pyi` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/PKG-INFO` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticLoadBalancing 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticLoadBalancing 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elb"></a>
 
 # types-aiobotocore-elb
 
 [![PyPI - types-aiobotocore-elb](https://img.shields.io/pypi/v/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elb?color=blue)](https://pypistats.org/packages/types-aiobotocore-elb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticLoadBalancing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
+[aiobotocore.ElasticLoadBalancing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elb.html#ElasticLoadBalancing)
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
 [types-aiobotocore-elb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -361,75 +361,75 @@
 `types_aiobotocore_elb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elb.type_defs import (
     AccessLogTypeDef,
     AddAvailabilityZonesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddAvailabilityZonesOutputTypeDef,
     TagTypeDef,
     AdditionalAttributeTypeDef,
     AppCookieStickinessPolicyTypeDef,
     ApplySecurityGroupsToLoadBalancerInputRequestTypeDef,
+    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
     AttachLoadBalancerToSubnetsInputRequestTypeDef,
+    AttachLoadBalancerToSubnetsOutputTypeDef,
     BackendServerDescriptionTypeDef,
     HealthCheckTypeDef,
     ConnectionDrainingTypeDef,
     ConnectionSettingsTypeDef,
     ListenerTypeDef,
+    CreateAccessPointOutputTypeDef,
     CreateAppCookieStickinessPolicyInputRequestTypeDef,
     CreateLBCookieStickinessPolicyInputRequestTypeDef,
     PolicyAttributeTypeDef,
     CrossZoneLoadBalancingTypeDef,
     DeleteAccessPointInputRequestTypeDef,
     DeleteLoadBalancerListenerInputRequestTypeDef,
     DeleteLoadBalancerPolicyInputRequestTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
     DescribeAccessPointsInputRequestTypeDef,
+    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsInputRequestTypeDef,
     LimitTypeDef,
     WaiterConfigTypeDef,
     InstanceStateTypeDef,
     DescribeLoadBalancerAttributesInputRequestTypeDef,
     DescribeLoadBalancerPoliciesInputRequestTypeDef,
     DescribeLoadBalancerPolicyTypesInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     DetachLoadBalancerFromSubnetsInputRequestTypeDef,
+    DetachLoadBalancerFromSubnetsOutputTypeDef,
     LBCookieStickinessPolicyTypeDef,
     SourceSecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttributeDescriptionTypeDef,
     PolicyAttributeTypeDescriptionTypeDef,
     RemoveAvailabilityZonesInputRequestTypeDef,
+    RemoveAvailabilityZonesOutputTypeDef,
     TagKeyOnlyTypeDef,
+    ResponseMetadataTypeDef,
     SetLoadBalancerListenerSSLCertificateInputRequestTypeDef,
     SetLoadBalancerPoliciesForBackendServerInputRequestTypeDef,
     SetLoadBalancerPoliciesOfListenerInputRequestTypeDef,
-    AddAvailabilityZonesOutputTypeDef,
-    ApplySecurityGroupsToLoadBalancerOutputTypeDef,
-    AttachLoadBalancerToSubnetsOutputTypeDef,
-    CreateAccessPointOutputTypeDef,
-    DetachLoadBalancerFromSubnetsOutputTypeDef,
-    RemoveAvailabilityZonesOutputTypeDef,
     AddTagsInputRequestTypeDef,
     TagDescriptionTypeDef,
     ConfigureHealthCheckInputRequestTypeDef,
     ConfigureHealthCheckOutputTypeDef,
     CreateAccessPointInputRequestTypeDef,
     CreateLoadBalancerListenerInputRequestTypeDef,
     ListenerDescriptionTypeDef,
     CreateLoadBalancerPolicyInputRequestTypeDef,
     LoadBalancerAttributesTypeDef,
     DeregisterEndPointsInputRequestTypeDef,
     DeregisterEndPointsOutputTypeDef,
     DescribeEndPointStateInputRequestTypeDef,
     RegisterEndPointsInputRequestTypeDef,
     RegisterEndPointsOutputTypeDef,
-    DescribeAccessPointsInputDescribeLoadBalancersPaginateTypeDef,
-    DescribeAccountLimitsInputDescribeAccountLimitsPaginateTypeDef,
     DescribeAccountLimitsOutputTypeDef,
     DescribeEndPointStateInputAnyInstanceInServiceWaitTypeDef,
     DescribeEndPointStateInputInstanceDeregisteredWaitTypeDef,
     DescribeEndPointStateInputInstanceInServiceWaitTypeDef,
     DescribeEndPointStateOutputTypeDef,
     PoliciesTypeDef,
     PolicyDescriptionTypeDef,
@@ -453,43 +453,43 @@
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

### Comparing `types-aiobotocore-elb-2.5.0.post1/types_aiobotocore_elb.egg-info/SOURCES.txt` & `types-aiobotocore-elb-2.5.1/types_aiobotocore_elb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

