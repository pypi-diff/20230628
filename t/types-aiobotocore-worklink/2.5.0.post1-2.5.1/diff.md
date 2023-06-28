# Comparing `tmp/types-aiobotocore-worklink-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-worklink-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-worklink-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-worklink-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-worklink-2.5.0.post1.tar` & `types-aiobotocore-worklink-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.295721 types-aiobotocore-worklink-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14849 2023-03-11 12:27:30.295721 types-aiobotocore-worklink-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13274 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.295721 types-aiobotocore-worklink-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.295721 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23834 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23792 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7940 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7938 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21239 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21208 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:40.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.295721 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14849 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:30.000000 types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.398232 types-aiobotocore-worklink-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14842 2023-06-28 01:44:20.398232 types-aiobotocore-worklink-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13273 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.398232 types-aiobotocore-worklink-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.398232 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23834 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23792 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8149 2023-06-28 01:42:34.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8147 2023-06-28 01:42:34.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21273 2023-06-28 01:42:34.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21242 2023-06-28 01:42:34.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:33.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.398232 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14842 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:20.000000 types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-worklink-2.5.0.post1/LICENSE` & `types-aiobotocore-worklink-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/PKG-INFO` & `types-aiobotocore-worklink-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-worklink
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkLink 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkLink 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-worklink"></a>
 
 # types-aiobotocore-worklink
 
 [![PyPI - types-aiobotocore-worklink](https://img.shields.io/pypi/v/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-worklink?color=blue)](https://pypistats.org/packages/types-aiobotocore-worklink)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkLink 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
+[aiobotocore.WorkLink 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
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
 [types-aiobotocore-worklink docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,63 +294,63 @@
 `types_aiobotocore_worklink.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_worklink.type_defs import (
     AssociateDomainRequestRequestTypeDef,
     AssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateWebsiteAuthorizationProviderResponseTypeDef,
     AssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
+    AssociateWebsiteCertificateAuthorityResponseTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DescribeAuditStreamConfigurationRequestRequestTypeDef,
+    DescribeAuditStreamConfigurationResponseTypeDef,
     DescribeCompanyNetworkConfigurationRequestRequestTypeDef,
+    DescribeCompanyNetworkConfigurationResponseTypeDef,
     DescribeDevicePolicyConfigurationRequestRequestTypeDef,
+    DescribeDevicePolicyConfigurationResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
+    DescribeDeviceResponseTypeDef,
     DescribeDomainRequestRequestTypeDef,
+    DescribeDomainResponseTypeDef,
     DescribeFleetMetadataRequestRequestTypeDef,
+    DescribeFleetMetadataResponseTypeDef,
     DescribeIdentityProviderConfigurationRequestRequestTypeDef,
+    DescribeIdentityProviderConfigurationResponseTypeDef,
     DescribeWebsiteCertificateAuthorityRequestRequestTypeDef,
+    DescribeWebsiteCertificateAuthorityResponseTypeDef,
     DeviceSummaryTypeDef,
     DisassociateDomainRequestRequestTypeDef,
     DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef,
     DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef,
     DomainSummaryTypeDef,
     FleetSummaryTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFleetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWebsiteAuthorizationProvidersRequestRequestTypeDef,
     WebsiteAuthorizationProviderSummaryTypeDef,
     ListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
     WebsiteCaSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDomainAccessRequestRequestTypeDef,
     RevokeDomainAccessRequestRequestTypeDef,
     SignOutUserRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuditStreamConfigurationRequestRequestTypeDef,
     UpdateCompanyNetworkConfigurationRequestRequestTypeDef,
     UpdateDevicePolicyConfigurationRequestRequestTypeDef,
     UpdateDomainMetadataRequestRequestTypeDef,
     UpdateFleetMetadataRequestRequestTypeDef,
     UpdateIdentityProviderConfigurationRequestRequestTypeDef,
-    AssociateWebsiteAuthorizationProviderResponseTypeDef,
-    AssociateWebsiteCertificateAuthorityResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    DescribeAuditStreamConfigurationResponseTypeDef,
-    DescribeCompanyNetworkConfigurationResponseTypeDef,
-    DescribeDevicePolicyConfigurationResponseTypeDef,
-    DescribeDeviceResponseTypeDef,
-    DescribeDomainResponseTypeDef,
-    DescribeFleetMetadataResponseTypeDef,
-    DescribeIdentityProviderConfigurationResponseTypeDef,
-    DescribeWebsiteCertificateAuthorityResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ListDevicesResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ListWebsiteAuthorizationProvidersResponseTypeDef,
     ListWebsiteCertificateAuthoritiesResponseTypeDef,
 )
 
@@ -362,43 +362,43 @@
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/README.md` & `types-aiobotocore-worklink-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-worklink"></a>
 
 # types-aiobotocore-worklink
 
 [![PyPI - types-aiobotocore-worklink](https://img.shields.io/pypi/v/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-worklink?color=blue)](https://pypistats.org/packages/types-aiobotocore-worklink)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkLink 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
+[aiobotocore.WorkLink 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
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
 [types-aiobotocore-worklink docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,63 +261,63 @@
 `types_aiobotocore_worklink.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_worklink.type_defs import (
     AssociateDomainRequestRequestTypeDef,
     AssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateWebsiteAuthorizationProviderResponseTypeDef,
     AssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
+    AssociateWebsiteCertificateAuthorityResponseTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DescribeAuditStreamConfigurationRequestRequestTypeDef,
+    DescribeAuditStreamConfigurationResponseTypeDef,
     DescribeCompanyNetworkConfigurationRequestRequestTypeDef,
+    DescribeCompanyNetworkConfigurationResponseTypeDef,
     DescribeDevicePolicyConfigurationRequestRequestTypeDef,
+    DescribeDevicePolicyConfigurationResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
+    DescribeDeviceResponseTypeDef,
     DescribeDomainRequestRequestTypeDef,
+    DescribeDomainResponseTypeDef,
     DescribeFleetMetadataRequestRequestTypeDef,
+    DescribeFleetMetadataResponseTypeDef,
     DescribeIdentityProviderConfigurationRequestRequestTypeDef,
+    DescribeIdentityProviderConfigurationResponseTypeDef,
     DescribeWebsiteCertificateAuthorityRequestRequestTypeDef,
+    DescribeWebsiteCertificateAuthorityResponseTypeDef,
     DeviceSummaryTypeDef,
     DisassociateDomainRequestRequestTypeDef,
     DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef,
     DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef,
     DomainSummaryTypeDef,
     FleetSummaryTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFleetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWebsiteAuthorizationProvidersRequestRequestTypeDef,
     WebsiteAuthorizationProviderSummaryTypeDef,
     ListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
     WebsiteCaSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDomainAccessRequestRequestTypeDef,
     RevokeDomainAccessRequestRequestTypeDef,
     SignOutUserRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuditStreamConfigurationRequestRequestTypeDef,
     UpdateCompanyNetworkConfigurationRequestRequestTypeDef,
     UpdateDevicePolicyConfigurationRequestRequestTypeDef,
     UpdateDomainMetadataRequestRequestTypeDef,
     UpdateFleetMetadataRequestRequestTypeDef,
     UpdateIdentityProviderConfigurationRequestRequestTypeDef,
-    AssociateWebsiteAuthorizationProviderResponseTypeDef,
-    AssociateWebsiteCertificateAuthorityResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    DescribeAuditStreamConfigurationResponseTypeDef,
-    DescribeCompanyNetworkConfigurationResponseTypeDef,
-    DescribeDevicePolicyConfigurationResponseTypeDef,
-    DescribeDeviceResponseTypeDef,
-    DescribeDomainResponseTypeDef,
-    DescribeFleetMetadataResponseTypeDef,
-    DescribeIdentityProviderConfigurationResponseTypeDef,
-    DescribeWebsiteCertificateAuthorityResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ListDevicesResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ListWebsiteAuthorizationProvidersResponseTypeDef,
     ListWebsiteCertificateAuthoritiesResponseTypeDef,
 )
 
@@ -329,43 +329,43 @@
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/setup.py` & `types-aiobotocore-worklink-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-worklink.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-worklink",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_worklink"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WorkLink 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.WorkLink 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/"
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/__main__.py` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WorkLink 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WorkLink 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink\nOther"
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/client.py` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/client.pyi` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/literals.py` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -106,14 +106,15 @@
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
@@ -192,14 +193,15 @@
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
@@ -210,14 +212,15 @@
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
@@ -253,14 +256,15 @@
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
@@ -279,16 +283,19 @@
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
@@ -372,15 +379,17 @@
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/literals.pyi` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -104,14 +104,15 @@
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
@@ -190,14 +191,15 @@
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
@@ -208,14 +210,15 @@
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
@@ -251,14 +254,15 @@
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
@@ -277,16 +281,19 @@
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
@@ -370,15 +377,17 @@
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/type_defs.py` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/type_defs.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -22,67 +22,66 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AssociateDomainRequestRequestTypeDef",
     "AssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
     "AssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
+    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
     "CreateFleetRequestRequestTypeDef",
+    "CreateFleetResponseTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DescribeAuditStreamConfigurationRequestRequestTypeDef",
+    "DescribeAuditStreamConfigurationResponseTypeDef",
     "DescribeCompanyNetworkConfigurationRequestRequestTypeDef",
+    "DescribeCompanyNetworkConfigurationResponseTypeDef",
     "DescribeDevicePolicyConfigurationRequestRequestTypeDef",
+    "DescribeDevicePolicyConfigurationResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
+    "DescribeDeviceResponseTypeDef",
     "DescribeDomainRequestRequestTypeDef",
+    "DescribeDomainResponseTypeDef",
     "DescribeFleetMetadataRequestRequestTypeDef",
+    "DescribeFleetMetadataResponseTypeDef",
     "DescribeIdentityProviderConfigurationRequestRequestTypeDef",
+    "DescribeIdentityProviderConfigurationResponseTypeDef",
     "DescribeWebsiteCertificateAuthorityRequestRequestTypeDef",
+    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
     "DeviceSummaryTypeDef",
     "DisassociateDomainRequestRequestTypeDef",
     "DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     "DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     "DomainSummaryTypeDef",
     "FleetSummaryTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListFleetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWebsiteAuthorizationProvidersRequestRequestTypeDef",
     "WebsiteAuthorizationProviderSummaryTypeDef",
     "ListWebsiteCertificateAuthoritiesRequestRequestTypeDef",
     "WebsiteCaSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreDomainAccessRequestRequestTypeDef",
     "RevokeDomainAccessRequestRequestTypeDef",
     "SignOutUserRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAuditStreamConfigurationRequestRequestTypeDef",
     "UpdateCompanyNetworkConfigurationRequestRequestTypeDef",
     "UpdateDevicePolicyConfigurationRequestRequestTypeDef",
     "UpdateDomainMetadataRequestRequestTypeDef",
     "UpdateFleetMetadataRequestRequestTypeDef",
     "UpdateIdentityProviderConfigurationRequestRequestTypeDef",
-    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
-    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "DescribeAuditStreamConfigurationResponseTypeDef",
-    "DescribeCompanyNetworkConfigurationResponseTypeDef",
-    "DescribeDevicePolicyConfigurationResponseTypeDef",
-    "DescribeDeviceResponseTypeDef",
-    "DescribeDomainResponseTypeDef",
-    "DescribeFleetMetadataResponseTypeDef",
-    "DescribeIdentityProviderConfigurationResponseTypeDef",
-    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "ListDevicesResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "ListFleetsResponseTypeDef",
     "ListWebsiteAuthorizationProvidersResponseTypeDef",
     "ListWebsiteCertificateAuthoritiesResponseTypeDef",
 )
 
@@ -98,21 +97,19 @@
     "_OptionalAssociateDomainRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
-
 class AssociateDomainRequestRequestTypeDef(
     _RequiredAssociateDomainRequestRequestTypeDef, _OptionalAssociateDomainRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     {
         "FleetArn": str,
         "AuthorizationProviderType": Literal["SAML"],
     },
 )
@@ -120,30 +117,25 @@
     "_OptionalAssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
 
-
 class AssociateWebsiteAuthorizationProviderRequestRequestTypeDef(
     _RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
     _OptionalAssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateWebsiteAuthorizationProviderResponseTypeDef = TypedDict(
+    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AuthorizationProviderId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "FleetArn": str,
@@ -154,21 +146,27 @@
     "_OptionalAssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
-
 class AssociateWebsiteCertificateAuthorityRequestRequestTypeDef(
     _RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
     _OptionalAssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
 ):
     pass
 
+AssociateWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
+    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
+    {
+        "WebsiteCaId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateFleetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFleetRequestRequestTypeDef",
     {
         "FleetName": str,
     },
 )
@@ -178,20 +176,26 @@
         "DisplayName": str,
         "OptimizeForEndUserLocation": bool,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateFleetRequestRequestTypeDef(
     _RequiredCreateFleetRequestRequestTypeDef, _OptionalCreateFleetRequestRequestTypeDef
 ):
     pass
 
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteFleetRequestRequestTypeDef = TypedDict(
     "DeleteFleetRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
@@ -199,66 +203,155 @@
 DescribeAuditStreamConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeAuditStreamConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeAuditStreamConfigurationResponseTypeDef = TypedDict(
+    "DescribeAuditStreamConfigurationResponseTypeDef",
+    {
+        "AuditStreamArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeCompanyNetworkConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeCompanyNetworkConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeCompanyNetworkConfigurationResponseTypeDef = TypedDict(
+    "DescribeCompanyNetworkConfigurationResponseTypeDef",
+    {
+        "VpcId": str,
+        "SubnetIds": List[str],
+        "SecurityGroupIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDevicePolicyConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeDevicePolicyConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeDevicePolicyConfigurationResponseTypeDef = TypedDict(
+    "DescribeDevicePolicyConfigurationResponseTypeDef",
+    {
+        "DeviceCaCertificate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DeviceId": str,
     },
 )
 
+DescribeDeviceResponseTypeDef = TypedDict(
+    "DescribeDeviceResponseTypeDef",
+    {
+        "Status": DeviceStatusType,
+        "Model": str,
+        "Manufacturer": str,
+        "OperatingSystem": str,
+        "OperatingSystemVersion": str,
+        "PatchLevel": str,
+        "FirstAccessedTime": datetime,
+        "LastAccessedTime": datetime,
+        "Username": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
 
+DescribeDomainResponseTypeDef = TypedDict(
+    "DescribeDomainResponseTypeDef",
+    {
+        "DomainName": str,
+        "DisplayName": str,
+        "CreatedTime": datetime,
+        "DomainStatus": DomainStatusType,
+        "AcmCertificateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeFleetMetadataRequestRequestTypeDef = TypedDict(
     "DescribeFleetMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeFleetMetadataResponseTypeDef = TypedDict(
+    "DescribeFleetMetadataResponseTypeDef",
+    {
+        "CreatedTime": datetime,
+        "LastUpdatedTime": datetime,
+        "FleetName": str,
+        "DisplayName": str,
+        "OptimizeForEndUserLocation": bool,
+        "CompanyCode": str,
+        "FleetStatus": FleetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeIdentityProviderConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeIdentityProviderConfigurationResponseTypeDef = TypedDict(
+    "DescribeIdentityProviderConfigurationResponseTypeDef",
+    {
+        "IdentityProviderType": Literal["SAML"],
+        "ServiceProviderSamlMetadata": str,
+        "IdentityProviderSamlMetadata": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWebsiteCertificateAuthorityRequestRequestTypeDef = TypedDict(
     "DescribeWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "FleetArn": str,
         "WebsiteCaId": str,
     },
 )
 
+DescribeWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
+    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
+    {
+        "Certificate": str,
+        "CreatedTime": datetime,
+        "DisplayName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceSummaryTypeDef = TypedDict(
     "DeviceSummaryTypeDef",
     {
         "DeviceId": str,
         "DeviceStatus": DeviceStatusType,
     },
     total=False,
@@ -300,19 +393,17 @@
     "_OptionalDomainSummaryTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
-
 class DomainSummaryTypeDef(_RequiredDomainSummaryTypeDef, _OptionalDomainSummaryTypeDef):
     pass
 
-
 FleetSummaryTypeDef = TypedDict(
     "FleetSummaryTypeDef",
     {
         "FleetArn": str,
         "CreatedTime": datetime,
         "LastUpdatedTime": datetime,
         "FleetName": str,
@@ -335,21 +426,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDevicesRequestRequestTypeDef(
     _RequiredListDevicesRequestRequestTypeDef, _OptionalListDevicesRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredListDomainsRequestRequestTypeDef = TypedDict(
     "_RequiredListDomainsRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListDomainsRequestRequestTypeDef = TypedDict(
@@ -357,21 +446,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDomainsRequestRequestTypeDef(
     _RequiredListDomainsRequestRequestTypeDef, _OptionalListDomainsRequestRequestTypeDef
 ):
     pass
 
-
 ListFleetsRequestRequestTypeDef = TypedDict(
     "ListFleetsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -380,14 +467,22 @@
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
 _RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef = TypedDict(
     "_RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListWebsiteAuthorizationProvidersRequestRequestTypeDef = TypedDict(
@@ -395,22 +490,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListWebsiteAuthorizationProvidersRequestRequestTypeDef(
     _RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef,
     _OptionalListWebsiteAuthorizationProvidersRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredWebsiteAuthorizationProviderSummaryTypeDef = TypedDict(
     "_RequiredWebsiteAuthorizationProviderSummaryTypeDef",
     {
         "AuthorizationProviderType": Literal["SAML"],
     },
 )
 _OptionalWebsiteAuthorizationProviderSummaryTypeDef = TypedDict(
@@ -419,22 +512,20 @@
         "AuthorizationProviderId": str,
         "DomainName": str,
         "CreatedTime": datetime,
     },
     total=False,
 )
 
-
 class WebsiteAuthorizationProviderSummaryTypeDef(
     _RequiredWebsiteAuthorizationProviderSummaryTypeDef,
     _OptionalWebsiteAuthorizationProviderSummaryTypeDef,
 ):
     pass
 
-
 _RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef = TypedDict(
     "_RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListWebsiteCertificateAuthoritiesRequestRequestTypeDef = TypedDict(
@@ -442,32 +533,41 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListWebsiteCertificateAuthoritiesRequestRequestTypeDef(
     _RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
     _OptionalListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
 ):
     pass
 
-
 WebsiteCaSummaryTypeDef = TypedDict(
     "WebsiteCaSummaryTypeDef",
     {
         "WebsiteCaId": str,
         "CreatedTime": datetime,
         "DisplayName": str,
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
 RestoreDomainAccessRequestRequestTypeDef = TypedDict(
     "RestoreDomainAccessRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
@@ -514,22 +614,20 @@
     "_OptionalUpdateAuditStreamConfigurationRequestRequestTypeDef",
     {
         "AuditStreamArn": str,
     },
     total=False,
 )
 
-
 class UpdateAuditStreamConfigurationRequestRequestTypeDef(
     _RequiredUpdateAuditStreamConfigurationRequestRequestTypeDef,
     _OptionalUpdateAuditStreamConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateCompanyNetworkConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateCompanyNetworkConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
@@ -546,22 +644,20 @@
     "_OptionalUpdateDevicePolicyConfigurationRequestRequestTypeDef",
     {
         "DeviceCaCertificate": str,
     },
     total=False,
 )
 
-
 class UpdateDevicePolicyConfigurationRequestRequestTypeDef(
     _RequiredUpdateDevicePolicyConfigurationRequestRequestTypeDef,
     _OptionalUpdateDevicePolicyConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateDomainMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
@@ -569,22 +665,20 @@
     "_OptionalUpdateDomainMetadataRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
-
 class UpdateDomainMetadataRequestRequestTypeDef(
     _RequiredUpdateDomainMetadataRequestRequestTypeDef,
     _OptionalUpdateDomainMetadataRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateFleetMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalUpdateFleetMetadataRequestRequestTypeDef = TypedDict(
@@ -592,22 +686,20 @@
     {
         "DisplayName": str,
         "OptimizeForEndUserLocation": bool,
     },
     total=False,
 )
 
-
 class UpdateFleetMetadataRequestRequestTypeDef(
     _RequiredUpdateFleetMetadataRequestRequestTypeDef,
     _OptionalUpdateFleetMetadataRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
         "IdentityProviderType": Literal["SAML"],
     },
 )
@@ -615,180 +707,57 @@
     "_OptionalUpdateIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "IdentityProviderSamlMetadata": str,
     },
     total=False,
 )
 
-
 class UpdateIdentityProviderConfigurationRequestRequestTypeDef(
     _RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef,
     _OptionalUpdateIdentityProviderConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
-AssociateWebsiteAuthorizationProviderResponseTypeDef = TypedDict(
-    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
-    {
-        "AuthorizationProviderId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
-    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
-    {
-        "WebsiteCaId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAuditStreamConfigurationResponseTypeDef = TypedDict(
-    "DescribeAuditStreamConfigurationResponseTypeDef",
-    {
-        "AuditStreamArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCompanyNetworkConfigurationResponseTypeDef = TypedDict(
-    "DescribeCompanyNetworkConfigurationResponseTypeDef",
-    {
-        "VpcId": str,
-        "SubnetIds": List[str],
-        "SecurityGroupIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDevicePolicyConfigurationResponseTypeDef = TypedDict(
-    "DescribeDevicePolicyConfigurationResponseTypeDef",
-    {
-        "DeviceCaCertificate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDeviceResponseTypeDef = TypedDict(
-    "DescribeDeviceResponseTypeDef",
-    {
-        "Status": DeviceStatusType,
-        "Model": str,
-        "Manufacturer": str,
-        "OperatingSystem": str,
-        "OperatingSystemVersion": str,
-        "PatchLevel": str,
-        "FirstAccessedTime": datetime,
-        "LastAccessedTime": datetime,
-        "Username": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDomainResponseTypeDef = TypedDict(
-    "DescribeDomainResponseTypeDef",
-    {
-        "DomainName": str,
-        "DisplayName": str,
-        "CreatedTime": datetime,
-        "DomainStatus": DomainStatusType,
-        "AcmCertificateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFleetMetadataResponseTypeDef = TypedDict(
-    "DescribeFleetMetadataResponseTypeDef",
-    {
-        "CreatedTime": datetime,
-        "LastUpdatedTime": datetime,
-        "FleetName": str,
-        "DisplayName": str,
-        "OptimizeForEndUserLocation": bool,
-        "CompanyCode": str,
-        "FleetStatus": FleetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeIdentityProviderConfigurationResponseTypeDef = TypedDict(
-    "DescribeIdentityProviderConfigurationResponseTypeDef",
-    {
-        "IdentityProviderType": Literal["SAML"],
-        "ServiceProviderSamlMetadata": str,
-        "IdentityProviderSamlMetadata": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
-    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
-    {
-        "Certificate": str,
-        "CreatedTime": datetime,
-        "DisplayName": str,
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
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Domains": List[DomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFleetsResponseTypeDef = TypedDict(
     "ListFleetsResponseTypeDef",
     {
         "FleetSummaryList": List[FleetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebsiteAuthorizationProvidersResponseTypeDef = TypedDict(
     "ListWebsiteAuthorizationProvidersResponseTypeDef",
     {
         "WebsiteAuthorizationProviders": List[WebsiteAuthorizationProviderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebsiteCertificateAuthoritiesResponseTypeDef = TypedDict(
     "ListWebsiteCertificateAuthoritiesResponseTypeDef",
     {
         "WebsiteCertificateAuthorities": List[WebsiteCaSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink/type_defs.pyi` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink/type_defs.py`

 * *Files 12% similar despite different names*

```diff
@@ -22,66 +22,67 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AssociateDomainRequestRequestTypeDef",
     "AssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
     "AssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
+    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
     "CreateFleetRequestRequestTypeDef",
+    "CreateFleetResponseTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DescribeAuditStreamConfigurationRequestRequestTypeDef",
+    "DescribeAuditStreamConfigurationResponseTypeDef",
     "DescribeCompanyNetworkConfigurationRequestRequestTypeDef",
+    "DescribeCompanyNetworkConfigurationResponseTypeDef",
     "DescribeDevicePolicyConfigurationRequestRequestTypeDef",
+    "DescribeDevicePolicyConfigurationResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
+    "DescribeDeviceResponseTypeDef",
     "DescribeDomainRequestRequestTypeDef",
+    "DescribeDomainResponseTypeDef",
     "DescribeFleetMetadataRequestRequestTypeDef",
+    "DescribeFleetMetadataResponseTypeDef",
     "DescribeIdentityProviderConfigurationRequestRequestTypeDef",
+    "DescribeIdentityProviderConfigurationResponseTypeDef",
     "DescribeWebsiteCertificateAuthorityRequestRequestTypeDef",
+    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
     "DeviceSummaryTypeDef",
     "DisassociateDomainRequestRequestTypeDef",
     "DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     "DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     "DomainSummaryTypeDef",
     "FleetSummaryTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListFleetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWebsiteAuthorizationProvidersRequestRequestTypeDef",
     "WebsiteAuthorizationProviderSummaryTypeDef",
     "ListWebsiteCertificateAuthoritiesRequestRequestTypeDef",
     "WebsiteCaSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreDomainAccessRequestRequestTypeDef",
     "RevokeDomainAccessRequestRequestTypeDef",
     "SignOutUserRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAuditStreamConfigurationRequestRequestTypeDef",
     "UpdateCompanyNetworkConfigurationRequestRequestTypeDef",
     "UpdateDevicePolicyConfigurationRequestRequestTypeDef",
     "UpdateDomainMetadataRequestRequestTypeDef",
     "UpdateFleetMetadataRequestRequestTypeDef",
     "UpdateIdentityProviderConfigurationRequestRequestTypeDef",
-    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
-    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "DescribeAuditStreamConfigurationResponseTypeDef",
-    "DescribeCompanyNetworkConfigurationResponseTypeDef",
-    "DescribeDevicePolicyConfigurationResponseTypeDef",
-    "DescribeDeviceResponseTypeDef",
-    "DescribeDomainResponseTypeDef",
-    "DescribeFleetMetadataResponseTypeDef",
-    "DescribeIdentityProviderConfigurationResponseTypeDef",
-    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "ListDevicesResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "ListFleetsResponseTypeDef",
     "ListWebsiteAuthorizationProvidersResponseTypeDef",
     "ListWebsiteCertificateAuthoritiesResponseTypeDef",
 )
 
@@ -97,19 +98,21 @@
     "_OptionalAssociateDomainRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
+
 class AssociateDomainRequestRequestTypeDef(
     _RequiredAssociateDomainRequestRequestTypeDef, _OptionalAssociateDomainRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     {
         "FleetArn": str,
         "AuthorizationProviderType": Literal["SAML"],
     },
 )
@@ -117,28 +120,27 @@
     "_OptionalAssociateWebsiteAuthorizationProviderRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
 
+
 class AssociateWebsiteAuthorizationProviderRequestRequestTypeDef(
     _RequiredAssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
     _OptionalAssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+AssociateWebsiteAuthorizationProviderResponseTypeDef = TypedDict(
+    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AuthorizationProviderId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "FleetArn": str,
@@ -149,20 +151,30 @@
     "_OptionalAssociateWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
+
 class AssociateWebsiteCertificateAuthorityRequestRequestTypeDef(
     _RequiredAssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
     _OptionalAssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
 ):
     pass
 
+
+AssociateWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
+    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
+    {
+        "WebsiteCaId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFleetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFleetRequestRequestTypeDef",
     {
         "FleetName": str,
     },
 )
 _OptionalCreateFleetRequestRequestTypeDef = TypedDict(
@@ -171,85 +183,184 @@
         "DisplayName": str,
         "OptimizeForEndUserLocation": bool,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateFleetRequestRequestTypeDef(
     _RequiredCreateFleetRequestRequestTypeDef, _OptionalCreateFleetRequestRequestTypeDef
 ):
     pass
 
+
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFleetRequestRequestTypeDef = TypedDict(
     "DeleteFleetRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
 DescribeAuditStreamConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeAuditStreamConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeAuditStreamConfigurationResponseTypeDef = TypedDict(
+    "DescribeAuditStreamConfigurationResponseTypeDef",
+    {
+        "AuditStreamArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeCompanyNetworkConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeCompanyNetworkConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeCompanyNetworkConfigurationResponseTypeDef = TypedDict(
+    "DescribeCompanyNetworkConfigurationResponseTypeDef",
+    {
+        "VpcId": str,
+        "SubnetIds": List[str],
+        "SecurityGroupIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDevicePolicyConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeDevicePolicyConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeDevicePolicyConfigurationResponseTypeDef = TypedDict(
+    "DescribeDevicePolicyConfigurationResponseTypeDef",
+    {
+        "DeviceCaCertificate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DeviceId": str,
     },
 )
 
+DescribeDeviceResponseTypeDef = TypedDict(
+    "DescribeDeviceResponseTypeDef",
+    {
+        "Status": DeviceStatusType,
+        "Model": str,
+        "Manufacturer": str,
+        "OperatingSystem": str,
+        "OperatingSystemVersion": str,
+        "PatchLevel": str,
+        "FirstAccessedTime": datetime,
+        "LastAccessedTime": datetime,
+        "Username": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
 
+DescribeDomainResponseTypeDef = TypedDict(
+    "DescribeDomainResponseTypeDef",
+    {
+        "DomainName": str,
+        "DisplayName": str,
+        "CreatedTime": datetime,
+        "DomainStatus": DomainStatusType,
+        "AcmCertificateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeFleetMetadataRequestRequestTypeDef = TypedDict(
     "DescribeFleetMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeFleetMetadataResponseTypeDef = TypedDict(
+    "DescribeFleetMetadataResponseTypeDef",
+    {
+        "CreatedTime": datetime,
+        "LastUpdatedTime": datetime,
+        "FleetName": str,
+        "DisplayName": str,
+        "OptimizeForEndUserLocation": bool,
+        "CompanyCode": str,
+        "FleetStatus": FleetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeIdentityProviderConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 
+DescribeIdentityProviderConfigurationResponseTypeDef = TypedDict(
+    "DescribeIdentityProviderConfigurationResponseTypeDef",
+    {
+        "IdentityProviderType": Literal["SAML"],
+        "ServiceProviderSamlMetadata": str,
+        "IdentityProviderSamlMetadata": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWebsiteCertificateAuthorityRequestRequestTypeDef = TypedDict(
     "DescribeWebsiteCertificateAuthorityRequestRequestTypeDef",
     {
         "FleetArn": str,
         "WebsiteCaId": str,
     },
 )
 
+DescribeWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
+    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
+    {
+        "Certificate": str,
+        "CreatedTime": datetime,
+        "DisplayName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceSummaryTypeDef = TypedDict(
     "DeviceSummaryTypeDef",
     {
         "DeviceId": str,
         "DeviceStatus": DeviceStatusType,
     },
     total=False,
@@ -291,17 +402,19 @@
     "_OptionalDomainSummaryTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
+
 class DomainSummaryTypeDef(_RequiredDomainSummaryTypeDef, _OptionalDomainSummaryTypeDef):
     pass
 
+
 FleetSummaryTypeDef = TypedDict(
     "FleetSummaryTypeDef",
     {
         "FleetArn": str,
         "CreatedTime": datetime,
         "LastUpdatedTime": datetime,
         "FleetName": str,
@@ -324,19 +437,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDevicesRequestRequestTypeDef(
     _RequiredListDevicesRequestRequestTypeDef, _OptionalListDevicesRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredListDomainsRequestRequestTypeDef = TypedDict(
     "_RequiredListDomainsRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListDomainsRequestRequestTypeDef = TypedDict(
@@ -344,19 +459,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDomainsRequestRequestTypeDef(
     _RequiredListDomainsRequestRequestTypeDef, _OptionalListDomainsRequestRequestTypeDef
 ):
     pass
 
+
 ListFleetsRequestRequestTypeDef = TypedDict(
     "ListFleetsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -365,14 +482,22 @@
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
 _RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef = TypedDict(
     "_RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListWebsiteAuthorizationProvidersRequestRequestTypeDef = TypedDict(
@@ -380,20 +505,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListWebsiteAuthorizationProvidersRequestRequestTypeDef(
     _RequiredListWebsiteAuthorizationProvidersRequestRequestTypeDef,
     _OptionalListWebsiteAuthorizationProvidersRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredWebsiteAuthorizationProviderSummaryTypeDef = TypedDict(
     "_RequiredWebsiteAuthorizationProviderSummaryTypeDef",
     {
         "AuthorizationProviderType": Literal["SAML"],
     },
 )
 _OptionalWebsiteAuthorizationProviderSummaryTypeDef = TypedDict(
@@ -402,20 +529,22 @@
         "AuthorizationProviderId": str,
         "DomainName": str,
         "CreatedTime": datetime,
     },
     total=False,
 )
 
+
 class WebsiteAuthorizationProviderSummaryTypeDef(
     _RequiredWebsiteAuthorizationProviderSummaryTypeDef,
     _OptionalWebsiteAuthorizationProviderSummaryTypeDef,
 ):
     pass
 
+
 _RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef = TypedDict(
     "_RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalListWebsiteCertificateAuthoritiesRequestRequestTypeDef = TypedDict(
@@ -423,30 +552,43 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListWebsiteCertificateAuthoritiesRequestRequestTypeDef(
     _RequiredListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
     _OptionalListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
 ):
     pass
 
+
 WebsiteCaSummaryTypeDef = TypedDict(
     "WebsiteCaSummaryTypeDef",
     {
         "WebsiteCaId": str,
         "CreatedTime": datetime,
         "DisplayName": str,
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
 RestoreDomainAccessRequestRequestTypeDef = TypedDict(
     "RestoreDomainAccessRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
@@ -493,20 +635,22 @@
     "_OptionalUpdateAuditStreamConfigurationRequestRequestTypeDef",
     {
         "AuditStreamArn": str,
     },
     total=False,
 )
 
+
 class UpdateAuditStreamConfigurationRequestRequestTypeDef(
     _RequiredUpdateAuditStreamConfigurationRequestRequestTypeDef,
     _OptionalUpdateAuditStreamConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateCompanyNetworkConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateCompanyNetworkConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
@@ -523,20 +667,22 @@
     "_OptionalUpdateDevicePolicyConfigurationRequestRequestTypeDef",
     {
         "DeviceCaCertificate": str,
     },
     total=False,
 )
 
+
 class UpdateDevicePolicyConfigurationRequestRequestTypeDef(
     _RequiredUpdateDevicePolicyConfigurationRequestRequestTypeDef,
     _OptionalUpdateDevicePolicyConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateDomainMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
         "DomainName": str,
     },
 )
@@ -544,20 +690,22 @@
     "_OptionalUpdateDomainMetadataRequestRequestTypeDef",
     {
         "DisplayName": str,
     },
     total=False,
 )
 
+
 class UpdateDomainMetadataRequestRequestTypeDef(
     _RequiredUpdateDomainMetadataRequestRequestTypeDef,
     _OptionalUpdateDomainMetadataRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateFleetMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetMetadataRequestRequestTypeDef",
     {
         "FleetArn": str,
     },
 )
 _OptionalUpdateFleetMetadataRequestRequestTypeDef = TypedDict(
@@ -565,20 +713,22 @@
     {
         "DisplayName": str,
         "OptimizeForEndUserLocation": bool,
     },
     total=False,
 )
 
+
 class UpdateFleetMetadataRequestRequestTypeDef(
     _RequiredUpdateFleetMetadataRequestRequestTypeDef,
     _OptionalUpdateFleetMetadataRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "FleetArn": str,
         "IdentityProviderType": Literal["SAML"],
     },
 )
@@ -586,178 +736,59 @@
     "_OptionalUpdateIdentityProviderConfigurationRequestRequestTypeDef",
     {
         "IdentityProviderSamlMetadata": str,
     },
     total=False,
 )
 
+
 class UpdateIdentityProviderConfigurationRequestRequestTypeDef(
     _RequiredUpdateIdentityProviderConfigurationRequestRequestTypeDef,
     _OptionalUpdateIdentityProviderConfigurationRequestRequestTypeDef,
 ):
     pass
 
-AssociateWebsiteAuthorizationProviderResponseTypeDef = TypedDict(
-    "AssociateWebsiteAuthorizationProviderResponseTypeDef",
-    {
-        "AuthorizationProviderId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
-    "AssociateWebsiteCertificateAuthorityResponseTypeDef",
-    {
-        "WebsiteCaId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAuditStreamConfigurationResponseTypeDef = TypedDict(
-    "DescribeAuditStreamConfigurationResponseTypeDef",
-    {
-        "AuditStreamArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCompanyNetworkConfigurationResponseTypeDef = TypedDict(
-    "DescribeCompanyNetworkConfigurationResponseTypeDef",
-    {
-        "VpcId": str,
-        "SubnetIds": List[str],
-        "SecurityGroupIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDevicePolicyConfigurationResponseTypeDef = TypedDict(
-    "DescribeDevicePolicyConfigurationResponseTypeDef",
-    {
-        "DeviceCaCertificate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDeviceResponseTypeDef = TypedDict(
-    "DescribeDeviceResponseTypeDef",
-    {
-        "Status": DeviceStatusType,
-        "Model": str,
-        "Manufacturer": str,
-        "OperatingSystem": str,
-        "OperatingSystemVersion": str,
-        "PatchLevel": str,
-        "FirstAccessedTime": datetime,
-        "LastAccessedTime": datetime,
-        "Username": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDomainResponseTypeDef = TypedDict(
-    "DescribeDomainResponseTypeDef",
-    {
-        "DomainName": str,
-        "DisplayName": str,
-        "CreatedTime": datetime,
-        "DomainStatus": DomainStatusType,
-        "AcmCertificateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFleetMetadataResponseTypeDef = TypedDict(
-    "DescribeFleetMetadataResponseTypeDef",
-    {
-        "CreatedTime": datetime,
-        "LastUpdatedTime": datetime,
-        "FleetName": str,
-        "DisplayName": str,
-        "OptimizeForEndUserLocation": bool,
-        "CompanyCode": str,
-        "FleetStatus": FleetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeIdentityProviderConfigurationResponseTypeDef = TypedDict(
-    "DescribeIdentityProviderConfigurationResponseTypeDef",
-    {
-        "IdentityProviderType": Literal["SAML"],
-        "ServiceProviderSamlMetadata": str,
-        "IdentityProviderSamlMetadata": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWebsiteCertificateAuthorityResponseTypeDef = TypedDict(
-    "DescribeWebsiteCertificateAuthorityResponseTypeDef",
-    {
-        "Certificate": str,
-        "CreatedTime": datetime,
-        "DisplayName": str,
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
 
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Domains": List[DomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFleetsResponseTypeDef = TypedDict(
     "ListFleetsResponseTypeDef",
     {
         "FleetSummaryList": List[FleetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebsiteAuthorizationProvidersResponseTypeDef = TypedDict(
     "ListWebsiteAuthorizationProvidersResponseTypeDef",
     {
         "WebsiteAuthorizationProviders": List[WebsiteAuthorizationProviderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWebsiteCertificateAuthoritiesResponseTypeDef = TypedDict(
     "ListWebsiteCertificateAuthoritiesResponseTypeDef",
     {
         "WebsiteCertificateAuthorities": List[WebsiteCaSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/PKG-INFO` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-worklink
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkLink 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkLink 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-worklink"></a>
 
 # types-aiobotocore-worklink
 
 [![PyPI - types-aiobotocore-worklink](https://img.shields.io/pypi/v/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-worklink.svg?color=blue)](https://pypi.org/project/types-aiobotocore-worklink)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-worklink?color=blue)](https://pypistats.org/packages/types-aiobotocore-worklink)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkLink 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
+[aiobotocore.WorkLink 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/worklink.html#WorkLink)
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
 [types-aiobotocore-worklink docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_worklink/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,63 +294,63 @@
 `types_aiobotocore_worklink.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_worklink.type_defs import (
     AssociateDomainRequestRequestTypeDef,
     AssociateWebsiteAuthorizationProviderRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateWebsiteAuthorizationProviderResponseTypeDef,
     AssociateWebsiteCertificateAuthorityRequestRequestTypeDef,
+    AssociateWebsiteCertificateAuthorityResponseTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DescribeAuditStreamConfigurationRequestRequestTypeDef,
+    DescribeAuditStreamConfigurationResponseTypeDef,
     DescribeCompanyNetworkConfigurationRequestRequestTypeDef,
+    DescribeCompanyNetworkConfigurationResponseTypeDef,
     DescribeDevicePolicyConfigurationRequestRequestTypeDef,
+    DescribeDevicePolicyConfigurationResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
+    DescribeDeviceResponseTypeDef,
     DescribeDomainRequestRequestTypeDef,
+    DescribeDomainResponseTypeDef,
     DescribeFleetMetadataRequestRequestTypeDef,
+    DescribeFleetMetadataResponseTypeDef,
     DescribeIdentityProviderConfigurationRequestRequestTypeDef,
+    DescribeIdentityProviderConfigurationResponseTypeDef,
     DescribeWebsiteCertificateAuthorityRequestRequestTypeDef,
+    DescribeWebsiteCertificateAuthorityResponseTypeDef,
     DeviceSummaryTypeDef,
     DisassociateDomainRequestRequestTypeDef,
     DisassociateWebsiteAuthorizationProviderRequestRequestTypeDef,
     DisassociateWebsiteCertificateAuthorityRequestRequestTypeDef,
     DomainSummaryTypeDef,
     FleetSummaryTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFleetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWebsiteAuthorizationProvidersRequestRequestTypeDef,
     WebsiteAuthorizationProviderSummaryTypeDef,
     ListWebsiteCertificateAuthoritiesRequestRequestTypeDef,
     WebsiteCaSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDomainAccessRequestRequestTypeDef,
     RevokeDomainAccessRequestRequestTypeDef,
     SignOutUserRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuditStreamConfigurationRequestRequestTypeDef,
     UpdateCompanyNetworkConfigurationRequestRequestTypeDef,
     UpdateDevicePolicyConfigurationRequestRequestTypeDef,
     UpdateDomainMetadataRequestRequestTypeDef,
     UpdateFleetMetadataRequestRequestTypeDef,
     UpdateIdentityProviderConfigurationRequestRequestTypeDef,
-    AssociateWebsiteAuthorizationProviderResponseTypeDef,
-    AssociateWebsiteCertificateAuthorityResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    DescribeAuditStreamConfigurationResponseTypeDef,
-    DescribeCompanyNetworkConfigurationResponseTypeDef,
-    DescribeDevicePolicyConfigurationResponseTypeDef,
-    DescribeDeviceResponseTypeDef,
-    DescribeDomainResponseTypeDef,
-    DescribeFleetMetadataResponseTypeDef,
-    DescribeIdentityProviderConfigurationResponseTypeDef,
-    DescribeWebsiteCertificateAuthorityResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ListDevicesResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ListWebsiteAuthorizationProvidersResponseTypeDef,
     ListWebsiteCertificateAuthoritiesResponseTypeDef,
 )
 
@@ -362,43 +362,43 @@
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

### Comparing `types-aiobotocore-worklink-2.5.0.post1/types_aiobotocore_worklink.egg-info/SOURCES.txt` & `types-aiobotocore-worklink-2.5.1/types_aiobotocore_worklink.egg-info/SOURCES.txt`

 * *Files identical despite different names*

