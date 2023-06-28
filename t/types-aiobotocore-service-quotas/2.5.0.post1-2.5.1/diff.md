# Comparing `tmp/types-aiobotocore-service-quotas-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-service-quotas-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-service-quotas-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-service-quotas-2.5.1.tar", last modified: Wed Jun 28 01:44:10 2023, max compression
```

## Comparing `types-aiobotocore-service-quotas-2.5.0.post1.tar` & `types-aiobotocore-service-quotas-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.331627 types-aiobotocore-service-quotas-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17115 2023-03-11 12:27:20.331627 types-aiobotocore-service-quotas-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15517 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.331627 types-aiobotocore-service-quotas-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:23:55.000000 types-aiobotocore-service-quotas-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.331627 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/
--rw-r--r--   0 runner    (1001) docker     (123)     2292 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2291 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21026 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20992 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9585 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9583 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9247 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9238 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17542 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17529 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:56.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.331627 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17115 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:20.000000 types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.146213 types-aiobotocore-service-quotas-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17114 2023-06-28 01:44:10.142213 types-aiobotocore-service-quotas-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15522 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:10.146213 types-aiobotocore-service-quotas-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.142213 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/
+-rw-r--r--   0 runner    (1001) docker     (123)     2292 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2291 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21026 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20992 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9872 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9870 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9139 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9131 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    17582 2023-06-28 01:40:46.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17569 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:45.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.142213 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17114 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:09.000000 types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/LICENSE` & `types-aiobotocore-service-quotas-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/PKG-INFO` & `types-aiobotocore-service-quotas-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-service-quotas
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceQuotas 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceQuotas 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-service-quotas"></a>
 
 # types-aiobotocore-service-quotas
 
 [![PyPI - types-aiobotocore-service-quotas](https://img.shields.io/pypi/v/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-service-quotas?color=blue)](https://pypistats.org/packages/types-aiobotocore-service-quotas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceQuotas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
+[aiobotocore.ServiceQuotas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
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
 [types-aiobotocore-service-quotas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,49 +348,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_service_quotas.type_defs import (
     DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ErrorReasonTypeDef,
     GetAWSDefaultServiceQuotaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeRequestRequestTypeDef,
     RequestedServiceQuotaChangeTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ServiceQuotaIncreaseRequestInTemplateTypeDef,
     GetServiceQuotaRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
     ListAWSDefaultServiceQuotasRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef,
+    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef,
+    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
     ListServiceQuotasRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ServiceInfoTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MetricInfoTypeDef,
+    PaginatorConfigTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef,
     QuotaPeriodTypeDef,
     RequestServiceQuotaIncreaseRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryResponseTypeDef,
     RequestServiceQuotaIncreaseResponseTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef,
-    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
-    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
-    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ServiceQuotaTypeDef,
     GetAWSDefaultServiceQuotaResponseTypeDef,
     GetServiceQuotaResponseTypeDef,
     ListAWSDefaultServiceQuotasResponseTypeDef,
@@ -405,43 +405,43 @@
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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/README.md` & `types-aiobotocore-service-quotas-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-service-quotas"></a>
 
 # types-aiobotocore-service-quotas
 
 [![PyPI - types-aiobotocore-service-quotas](https://img.shields.io/pypi/v/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-service-quotas?color=blue)](https://pypistats.org/packages/types-aiobotocore-service-quotas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceQuotas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
+[aiobotocore.ServiceQuotas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
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
 [types-aiobotocore-service-quotas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,49 +315,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_service_quotas.type_defs import (
     DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ErrorReasonTypeDef,
     GetAWSDefaultServiceQuotaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeRequestRequestTypeDef,
     RequestedServiceQuotaChangeTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ServiceQuotaIncreaseRequestInTemplateTypeDef,
     GetServiceQuotaRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
     ListAWSDefaultServiceQuotasRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef,
+    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef,
+    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
     ListServiceQuotasRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ServiceInfoTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MetricInfoTypeDef,
+    PaginatorConfigTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef,
     QuotaPeriodTypeDef,
     RequestServiceQuotaIncreaseRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryResponseTypeDef,
     RequestServiceQuotaIncreaseResponseTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef,
-    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
-    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
-    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ServiceQuotaTypeDef,
     GetAWSDefaultServiceQuotaResponseTypeDef,
     GetServiceQuotaResponseTypeDef,
     ListAWSDefaultServiceQuotasResponseTypeDef,
@@ -372,43 +372,43 @@
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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/setup.py` & `types-aiobotocore-service-quotas-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-service-quotas.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-service-quotas",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_service_quotas"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ServiceQuotas 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ServiceQuotas 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/"
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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__init__.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__init__.pyi` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/__main__.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ServiceQuotas 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ServiceQuotas 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas\nOther"
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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/client.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/client.pyi` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/literals.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -118,14 +118,15 @@
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
@@ -204,14 +205,15 @@
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
@@ -222,14 +224,15 @@
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
@@ -265,14 +268,15 @@
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
@@ -291,16 +295,19 @@
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
@@ -384,15 +391,17 @@
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
@@ -425,21 +434,25 @@
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
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/literals.pyi` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -116,14 +116,15 @@
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
@@ -202,14 +203,15 @@
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
@@ -220,14 +222,15 @@
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
@@ -263,14 +266,15 @@
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
@@ -289,16 +293,19 @@
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
@@ -382,15 +389,17 @@
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
@@ -423,21 +432,25 @@
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
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/paginator.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         list_requested_service_quota_change_history_paginator: ListRequestedServiceQuotaChangeHistoryPaginator = client.get_paginator("list_requested_service_quota_change_history")
         list_requested_service_quota_change_history_by_quota_paginator: ListRequestedServiceQuotaChangeHistoryByQuotaPaginator = client.get_paginator("list_requested_service_quota_change_history_by_quota")
         list_service_quota_increase_requests_in_template_paginator: ListServiceQuotaIncreaseRequestsInTemplatePaginator = client.get_paginator("list_service_quota_increase_requests_in_template")
         list_service_quotas_paginator: ListServiceQuotasPaginator = client.get_paginator("list_service_quotas")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RequestStatusType
 from .type_defs import (
     ListAWSDefaultServiceQuotasResponseTypeDef,
@@ -43,20 +42,14 @@
     ListRequestedServiceQuotaChangeHistoryResponseTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef,
     ListServiceQuotasResponseTypeDef,
     ListServicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAWSDefaultServiceQuotasPaginator",
     "ListRequestedServiceQuotaChangeHistoryPaginator",
     "ListRequestedServiceQuotaChangeHistoryByQuotaPaginator",
     "ListServiceQuotaIncreaseRequestsInTemplatePaginator",
     "ListServiceQuotasPaginator",
     "ListServicesPaginator",
@@ -76,15 +69,15 @@
 class ListAWSDefaultServiceQuotasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListAWSDefaultServiceQuotas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listawsdefaultservicequotaspaginator)
     """
 
     def paginate(
-        self, *, ServiceCode: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceCode: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAWSDefaultServiceQuotasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListAWSDefaultServiceQuotas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listawsdefaultservicequotaspaginator)
         """
 
 
@@ -95,15 +88,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         Status: RequestStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRequestedServiceQuotaChangeHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListRequestedServiceQuotaChangeHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listrequestedservicequotachangehistorypaginator)
         """
 
 
@@ -115,15 +108,15 @@
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         QuotaCode: str,
         Status: RequestStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListRequestedServiceQuotaChangeHistoryByQuota.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listrequestedservicequotachangehistorybyquotapaginator)
         """
 
 
@@ -134,43 +127,43 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         AwsRegion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotaIncreaseRequestsInTemplate.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaincreaserequestsintemplatepaginator)
         """
 
 
 class ListServiceQuotasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaspaginator)
     """
 
     def paginate(
-        self, *, ServiceCode: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceCode: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceQuotasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaspaginator)
         """
 
 
 class ListServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/paginator.pyi` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         list_requested_service_quota_change_history_paginator: ListRequestedServiceQuotaChangeHistoryPaginator = client.get_paginator("list_requested_service_quota_change_history")
         list_requested_service_quota_change_history_by_quota_paginator: ListRequestedServiceQuotaChangeHistoryByQuotaPaginator = client.get_paginator("list_requested_service_quota_change_history_by_quota")
         list_service_quota_increase_requests_in_template_paginator: ListServiceQuotaIncreaseRequestsInTemplatePaginator = client.get_paginator("list_service_quota_increase_requests_in_template")
         list_service_quotas_paginator: ListServiceQuotasPaginator = client.get_paginator("list_service_quotas")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RequestStatusType
 from .type_defs import (
     ListAWSDefaultServiceQuotasResponseTypeDef,
@@ -43,19 +42,14 @@
     ListRequestedServiceQuotaChangeHistoryResponseTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef,
     ListServiceQuotasResponseTypeDef,
     ListServicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAWSDefaultServiceQuotasPaginator",
     "ListRequestedServiceQuotaChangeHistoryPaginator",
     "ListRequestedServiceQuotaChangeHistoryByQuotaPaginator",
     "ListServiceQuotaIncreaseRequestsInTemplatePaginator",
     "ListServiceQuotasPaginator",
     "ListServicesPaginator",
@@ -72,15 +66,15 @@
 class ListAWSDefaultServiceQuotasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListAWSDefaultServiceQuotas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listawsdefaultservicequotaspaginator)
     """
 
     def paginate(
-        self, *, ServiceCode: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceCode: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAWSDefaultServiceQuotasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListAWSDefaultServiceQuotas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listawsdefaultservicequotaspaginator)
         """
 
 class ListRequestedServiceQuotaChangeHistoryPaginator(AioPaginator):
@@ -90,15 +84,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         Status: RequestStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRequestedServiceQuotaChangeHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListRequestedServiceQuotaChangeHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listrequestedservicequotachangehistorypaginator)
         """
 
 class ListRequestedServiceQuotaChangeHistoryByQuotaPaginator(AioPaginator):
@@ -109,15 +103,15 @@
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         QuotaCode: str,
         Status: RequestStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListRequestedServiceQuotaChangeHistoryByQuota.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listrequestedservicequotachangehistorybyquotapaginator)
         """
 
 class ListServiceQuotaIncreaseRequestsInTemplatePaginator(AioPaginator):
@@ -127,41 +121,41 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         AwsRegion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotaIncreaseRequestsInTemplate.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaincreaserequestsintemplatepaginator)
         """
 
 class ListServiceQuotasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaspaginator)
     """
 
     def paginate(
-        self, *, ServiceCode: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceCode: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServiceQuotasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServiceQuotas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicequotaspaginator)
         """
 
 class ListServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/type_defs.py` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,49 +28,49 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef",
     "ErrorReasonTypeDef",
     "GetAWSDefaultServiceQuotaRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     "GetRequestedServiceQuotaChangeRequestRequestTypeDef",
     "RequestedServiceQuotaChangeTypeDef",
     "GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef",
     "ServiceQuotaIncreaseRequestInTemplateTypeDef",
     "GetServiceQuotaRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
     "ListAWSDefaultServiceQuotasRequestRequestTypeDef",
+    "ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
     "ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef",
+    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
     "ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef",
+    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
     "ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef",
+    "ListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
     "ListServiceQuotasRequestRequestTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
     "ServiceInfoTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "MetricInfoTypeDef",
+    "PaginatorConfigTypeDef",
     "PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef",
     "QuotaPeriodTypeDef",
     "RequestServiceQuotaIncreaseRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     "GetRequestedServiceQuotaChangeResponseTypeDef",
     "ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef",
     "ListRequestedServiceQuotaChangeHistoryResponseTypeDef",
     "RequestServiceQuotaIncreaseResponseTypeDef",
     "GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef",
     "ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef",
     "PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef",
-    "ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    "ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
-    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
-    "ListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ServiceQuotaTypeDef",
     "GetAWSDefaultServiceQuotaResponseTypeDef",
     "GetServiceQuotaResponseTypeDef",
     "ListAWSDefaultServiceQuotasResponseTypeDef",
@@ -99,22 +99,19 @@
     "GetAWSDefaultServiceQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetAssociationForServiceQuotaTemplateResponseTypeDef = TypedDict(
+    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServiceQuotaTemplateAssociationStatus": ServiceQuotaTemplateAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRequestedServiceQuotaChangeRequestRequestTypeDef = TypedDict(
     "GetRequestedServiceQuotaChangeRequestRequestTypeDef",
     {
         "RequestId": str,
@@ -170,24 +167,36 @@
     "GetServiceQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
+    "_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceCode": str,
+    },
+)
+_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
+    "_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef(
+    _RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
+    _OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef = TypedDict(
     "_RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef",
     {
         "ServiceCode": str,
     },
 )
 _OptionalListAWSDefaultServiceQuotasRequestRequestTypeDef = TypedDict(
@@ -203,14 +212,38 @@
 class ListAWSDefaultServiceQuotasRequestRequestTypeDef(
     _RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef,
     _OptionalListAWSDefaultServiceQuotasRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
+    "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "QuotaCode": str,
+    },
+)
+_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
+    "_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
+    {
+        "Status": RequestStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef(
+    _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
+    _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef = TypedDict(
     "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
@@ -228,36 +261,78 @@
 class ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef(
     _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
     _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
 ):
     pass
 
 
+ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef = TypedDict(
+    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "Status": RequestStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "Status": RequestStatusType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef = TypedDict(
+    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "AwsRegion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef = TypedDict(
     "ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "AwsRegion": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
+    "_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
+    {
+        "ServiceCode": str,
+    },
+)
+_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
+    "_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServiceQuotasRequestListServiceQuotasPaginateTypeDef(
+    _RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
+    _OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServiceQuotasRequestRequestTypeDef = TypedDict(
     "_RequiredListServiceQuotasRequestRequestTypeDef",
     {
         "ServiceCode": str,
     },
 )
 _OptionalListServiceQuotasRequestRequestTypeDef = TypedDict(
@@ -272,14 +347,22 @@
 
 class ListServiceQuotasRequestRequestTypeDef(
     _RequiredListServiceQuotasRequestRequestTypeDef, _OptionalListServiceQuotasRequestRequestTypeDef
 ):
     pass
 
 
+ListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "ListServicesRequestListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -316,14 +399,24 @@
         "MetricName": str,
         "MetricDimensions": Dict[str, str],
         "MetricStatisticRecommendation": str,
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
 PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef = TypedDict(
     "PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef",
     {
         "QuotaCode": str,
         "ServiceCode": str,
         "AwsRegion": str,
         "DesiredValue": float,
@@ -344,201 +437,108 @@
     {
         "ServiceCode": str,
         "QuotaCode": str,
         "DesiredValue": float,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetAssociationForServiceQuotaTemplateResponseTypeDef = TypedDict(
-    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "ServiceQuotaTemplateAssociationStatus": ServiceQuotaTemplateAssociationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 GetRequestedServiceQuotaChangeResponseTypeDef = TypedDict(
     "GetRequestedServiceQuotaChangeResponseTypeDef",
     {
         "RequestedQuota": RequestedServiceQuotaChangeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef",
     {
         "NextToken": str,
         "RequestedQuotas": List[RequestedServiceQuotaChangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRequestedServiceQuotaChangeHistoryResponseTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryResponseTypeDef",
     {
         "NextToken": str,
         "RequestedQuotas": List[RequestedServiceQuotaChangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestServiceQuotaIncreaseResponseTypeDef = TypedDict(
     "RequestServiceQuotaIncreaseResponseTypeDef",
     {
         "RequestedQuota": RequestedServiceQuotaChangeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef = TypedDict(
     "GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplate": ServiceQuotaIncreaseRequestInTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef = TypedDict(
     "ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplateList": List[
             ServiceQuotaIncreaseRequestInTemplateTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef = TypedDict(
     "PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplate": ServiceQuotaIncreaseRequestInTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
-    "_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    {
-        "ServiceCode": str,
-    },
-)
-_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
-    "_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef(
-    _RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-    _OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
-    "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "QuotaCode": str,
-    },
-)
-_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
-    "_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    {
-        "Status": RequestStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef(
-    _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-    _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-):
-    pass
-
-
-ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef = TypedDict(
-    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "Status": RequestStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef = TypedDict(
-    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "AwsRegion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
-    "_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    {
-        "ServiceCode": str,
-    },
-)
-_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
-    "_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServiceQuotasRequestListServiceQuotasPaginateTypeDef(
-    _RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-    _OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-):
-    pass
-
-
-ListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "ListServicesRequestListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "NextToken": str,
         "Services": List[ServiceInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -565,36 +565,36 @@
     total=False,
 )
 
 GetAWSDefaultServiceQuotaResponseTypeDef = TypedDict(
     "GetAWSDefaultServiceQuotaResponseTypeDef",
     {
         "Quota": ServiceQuotaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceQuotaResponseTypeDef = TypedDict(
     "GetServiceQuotaResponseTypeDef",
     {
         "Quota": ServiceQuotaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAWSDefaultServiceQuotasResponseTypeDef = TypedDict(
     "ListAWSDefaultServiceQuotasResponseTypeDef",
     {
         "NextToken": str,
         "Quotas": List[ServiceQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceQuotasResponseTypeDef = TypedDict(
     "ListServiceQuotasResponseTypeDef",
     {
         "NextToken": str,
         "Quotas": List[ServiceQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas/type_defs.pyi` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -27,49 +27,49 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef",
     "ErrorReasonTypeDef",
     "GetAWSDefaultServiceQuotaRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     "GetRequestedServiceQuotaChangeRequestRequestTypeDef",
     "RequestedServiceQuotaChangeTypeDef",
     "GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef",
     "ServiceQuotaIncreaseRequestInTemplateTypeDef",
     "GetServiceQuotaRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
     "ListAWSDefaultServiceQuotasRequestRequestTypeDef",
+    "ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
     "ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef",
+    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
     "ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef",
+    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
     "ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef",
+    "ListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
     "ListServiceQuotasRequestRequestTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
     "ServiceInfoTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "MetricInfoTypeDef",
+    "PaginatorConfigTypeDef",
     "PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef",
     "QuotaPeriodTypeDef",
     "RequestServiceQuotaIncreaseRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     "GetRequestedServiceQuotaChangeResponseTypeDef",
     "ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef",
     "ListRequestedServiceQuotaChangeHistoryResponseTypeDef",
     "RequestServiceQuotaIncreaseResponseTypeDef",
     "GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef",
     "ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef",
     "PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef",
-    "ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    "ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
-    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
-    "ListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ServiceQuotaTypeDef",
     "GetAWSDefaultServiceQuotaResponseTypeDef",
     "GetServiceQuotaResponseTypeDef",
     "ListAWSDefaultServiceQuotasResponseTypeDef",
@@ -98,22 +98,19 @@
     "GetAWSDefaultServiceQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetAssociationForServiceQuotaTemplateResponseTypeDef = TypedDict(
+    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServiceQuotaTemplateAssociationStatus": ServiceQuotaTemplateAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRequestedServiceQuotaChangeRequestRequestTypeDef = TypedDict(
     "GetRequestedServiceQuotaChangeRequestRequestTypeDef",
     {
         "RequestId": str,
@@ -169,24 +166,34 @@
     "GetServiceQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
+    "_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceCode": str,
+    },
+)
+_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
+    "_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef(
+    _RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
+    _OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
+):
+    pass
+
 _RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef = TypedDict(
     "_RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef",
     {
         "ServiceCode": str,
     },
 )
 _OptionalListAWSDefaultServiceQuotasRequestRequestTypeDef = TypedDict(
@@ -200,14 +207,36 @@
 
 class ListAWSDefaultServiceQuotasRequestRequestTypeDef(
     _RequiredListAWSDefaultServiceQuotasRequestRequestTypeDef,
     _OptionalListAWSDefaultServiceQuotasRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
+    "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "QuotaCode": str,
+    },
+)
+_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
+    "_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
+    {
+        "Status": RequestStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef(
+    _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
+    _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
+):
+    pass
+
 _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef = TypedDict(
     "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "QuotaCode": str,
     },
 )
@@ -223,36 +252,76 @@
 
 class ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef(
     _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
     _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
 ):
     pass
 
+ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef = TypedDict(
+    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "Status": RequestStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "Status": RequestStatusType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef = TypedDict(
+    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
+    {
+        "ServiceCode": str,
+        "AwsRegion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef = TypedDict(
     "ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef",
     {
         "ServiceCode": str,
         "AwsRegion": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
+    "_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
+    {
+        "ServiceCode": str,
+    },
+)
+_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
+    "_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServiceQuotasRequestListServiceQuotasPaginateTypeDef(
+    _RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
+    _OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
+):
+    pass
+
 _RequiredListServiceQuotasRequestRequestTypeDef = TypedDict(
     "_RequiredListServiceQuotasRequestRequestTypeDef",
     {
         "ServiceCode": str,
     },
 )
 _OptionalListServiceQuotasRequestRequestTypeDef = TypedDict(
@@ -265,14 +334,22 @@
 )
 
 class ListServiceQuotasRequestRequestTypeDef(
     _RequiredListServiceQuotasRequestRequestTypeDef, _OptionalListServiceQuotasRequestRequestTypeDef
 ):
     pass
 
+ListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "ListServicesRequestListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -309,14 +386,24 @@
         "MetricName": str,
         "MetricDimensions": Dict[str, str],
         "MetricStatisticRecommendation": str,
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
 PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef = TypedDict(
     "PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef",
     {
         "QuotaCode": str,
         "ServiceCode": str,
         "AwsRegion": str,
         "DesiredValue": float,
@@ -337,195 +424,108 @@
     {
         "ServiceCode": str,
         "QuotaCode": str,
         "DesiredValue": float,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetAssociationForServiceQuotaTemplateResponseTypeDef = TypedDict(
-    "GetAssociationForServiceQuotaTemplateResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "ServiceQuotaTemplateAssociationStatus": ServiceQuotaTemplateAssociationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 GetRequestedServiceQuotaChangeResponseTypeDef = TypedDict(
     "GetRequestedServiceQuotaChangeResponseTypeDef",
     {
         "RequestedQuota": RequestedServiceQuotaChangeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef",
     {
         "NextToken": str,
         "RequestedQuotas": List[RequestedServiceQuotaChangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRequestedServiceQuotaChangeHistoryResponseTypeDef = TypedDict(
     "ListRequestedServiceQuotaChangeHistoryResponseTypeDef",
     {
         "NextToken": str,
         "RequestedQuotas": List[RequestedServiceQuotaChangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestServiceQuotaIncreaseResponseTypeDef = TypedDict(
     "RequestServiceQuotaIncreaseResponseTypeDef",
     {
         "RequestedQuota": RequestedServiceQuotaChangeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef = TypedDict(
     "GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplate": ServiceQuotaIncreaseRequestInTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef = TypedDict(
     "ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplateList": List[
             ServiceQuotaIncreaseRequestInTemplateTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef = TypedDict(
     "PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef",
     {
         "ServiceQuotaIncreaseRequestInTemplate": ServiceQuotaIncreaseRequestInTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
-    "_RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    {
-        "ServiceCode": str,
-    },
-)
-_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef = TypedDict(
-    "_OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef(
-    _RequiredListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-    _OptionalListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-):
-    pass
-
-_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
-    "_RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "QuotaCode": str,
-    },
-)
-_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef = TypedDict(
-    "_OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef",
-    {
-        "Status": RequestStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef(
-    _RequiredListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-    _OptionalListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-):
-    pass
-
-ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef = TypedDict(
-    "ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "Status": RequestStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef = TypedDict(
-    "ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef",
-    {
-        "ServiceCode": str,
-        "AwsRegion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
-    "_RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    {
-        "ServiceCode": str,
-    },
-)
-_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef = TypedDict(
-    "_OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-class ListServiceQuotasRequestListServiceQuotasPaginateTypeDef(
-    _RequiredListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-    _OptionalListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-):
-    pass
-
-ListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "ListServicesRequestListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "NextToken": str,
         "Services": List[ServiceInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -552,36 +552,36 @@
     total=False,
 )
 
 GetAWSDefaultServiceQuotaResponseTypeDef = TypedDict(
     "GetAWSDefaultServiceQuotaResponseTypeDef",
     {
         "Quota": ServiceQuotaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceQuotaResponseTypeDef = TypedDict(
     "GetServiceQuotaResponseTypeDef",
     {
         "Quota": ServiceQuotaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAWSDefaultServiceQuotasResponseTypeDef = TypedDict(
     "ListAWSDefaultServiceQuotasResponseTypeDef",
     {
         "NextToken": str,
         "Quotas": List[ServiceQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceQuotasResponseTypeDef = TypedDict(
     "ListServiceQuotasResponseTypeDef",
     {
         "NextToken": str,
         "Quotas": List[ServiceQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/PKG-INFO` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-service-quotas
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceQuotas 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceQuotas 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-service-quotas"></a>
 
 # types-aiobotocore-service-quotas
 
 [![PyPI - types-aiobotocore-service-quotas](https://img.shields.io/pypi/v/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-service-quotas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-service-quotas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-service-quotas?color=blue)](https://pypistats.org/packages/types-aiobotocore-service-quotas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceQuotas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
+[aiobotocore.ServiceQuotas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/service-quotas.html#ServiceQuotas)
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
 [types-aiobotocore-service-quotas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_service_quotas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,49 +348,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_service_quotas.type_defs import (
     DeleteServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ErrorReasonTypeDef,
     GetAWSDefaultServiceQuotaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeRequestRequestTypeDef,
     RequestedServiceQuotaChangeTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateRequestRequestTypeDef,
     ServiceQuotaIncreaseRequestInTemplateTypeDef,
     GetServiceQuotaRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
     ListAWSDefaultServiceQuotasRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaRequestRequestTypeDef,
+    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
     ListRequestedServiceQuotaChangeHistoryRequestRequestTypeDef,
+    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateRequestRequestTypeDef,
+    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
     ListServiceQuotasRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ServiceInfoTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MetricInfoTypeDef,
+    PaginatorConfigTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateRequestRequestTypeDef,
     QuotaPeriodTypeDef,
     RequestServiceQuotaIncreaseRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
-    GetAssociationForServiceQuotaTemplateResponseTypeDef,
     GetRequestedServiceQuotaChangeResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryByQuotaResponseTypeDef,
     ListRequestedServiceQuotaChangeHistoryResponseTypeDef,
     RequestServiceQuotaIncreaseResponseTypeDef,
     GetServiceQuotaIncreaseRequestFromTemplateResponseTypeDef,
     ListServiceQuotaIncreaseRequestsInTemplateResponseTypeDef,
     PutServiceQuotaIncreaseRequestIntoTemplateResponseTypeDef,
-    ListAWSDefaultServiceQuotasRequestListAWSDefaultServiceQuotasPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryByQuotaRequestListRequestedServiceQuotaChangeHistoryByQuotaPaginateTypeDef,
-    ListRequestedServiceQuotaChangeHistoryRequestListRequestedServiceQuotaChangeHistoryPaginateTypeDef,
-    ListServiceQuotaIncreaseRequestsInTemplateRequestListServiceQuotaIncreaseRequestsInTemplatePaginateTypeDef,
-    ListServiceQuotasRequestListServiceQuotasPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ServiceQuotaTypeDef,
     GetAWSDefaultServiceQuotaResponseTypeDef,
     GetServiceQuotaResponseTypeDef,
     ListAWSDefaultServiceQuotasResponseTypeDef,
@@ -405,43 +405,43 @@
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

### Comparing `types-aiobotocore-service-quotas-2.5.0.post1/types_aiobotocore_service_quotas.egg-info/SOURCES.txt` & `types-aiobotocore-service-quotas-2.5.1/types_aiobotocore_service_quotas.egg-info/SOURCES.txt`

 * *Files identical despite different names*

