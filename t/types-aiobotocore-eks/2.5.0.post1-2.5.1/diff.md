# Comparing `tmp/types-aiobotocore-eks-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-eks-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-eks-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-eks-2.5.1.tar", last modified: Wed Jun 28 01:43:26 2023, max compression
```

## Comparing `types-aiobotocore-eks-2.5.0.post1.tar` & `types-aiobotocore-eks-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.515173 types-aiobotocore-eks-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21127 2023-03-11 12:26:34.507173 types-aiobotocore-eks-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19572 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.515173 types-aiobotocore-eks-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.507173 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/
--rw-r--r--   0 runner    (1001) docker     (123)     3348 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3347 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35154 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35095 2023-03-11 12:13:57.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13982 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13980 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8879 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8869 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    50620 2023-03-11 12:13:59.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    50547 2023-03-11 12:13:59.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:13:56.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     8176 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     8168 2023-03-11 12:13:58.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.507173 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21127 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:34.000000 types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.966132 types-aiobotocore-eks-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21115 2023-06-28 01:43:26.962132 types-aiobotocore-eks-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19566 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:26.966132 types-aiobotocore-eks-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.962132 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/
+-rw-r--r--   0 runner    (1001) docker     (123)     3348 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3347 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35154 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35095 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14213 2023-06-28 01:30:35.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14211 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8773 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8764 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    50700 2023-06-28 01:30:36.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50627 2023-06-28 01:30:35.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8176 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8168 2023-06-28 01:30:34.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.962132 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21115 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:26.000000 types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/LICENSE` & `types-aiobotocore-eks-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-eks-2.5.0.post1/PKG-INFO` & `types-aiobotocore-eks-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-eks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EKS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EKS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-eks"></a>
 
 # types-aiobotocore-eks
 
 [![PyPI - types-aiobotocore-eks](https://img.shields.io/pypi/v/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-eks?color=blue)](https://pypistats.org/packages/types-aiobotocore-eks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EKS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
+[aiobotocore.EKS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
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
 [types-aiobotocore-eks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -412,15 +412,14 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_eks.type_defs import (
     AddonIssueTypeDef,
     MarketplaceInformationTypeDef,
     CompatibilityTypeDef,
-    ResponseMetadataTypeDef,
     OidcIdentityProviderConfigRequestTypeDef,
     AutoScalingGroupTypeDef,
     CertificateTypeDef,
     ClusterIssueTypeDef,
     ConnectorConfigResponseTypeDef,
     KubernetesNetworkConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
@@ -438,51 +437,59 @@
     TaintTypeDef,
     DeleteAddonRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteFargateProfileRequestRequestTypeDef,
     DeleteNodegroupRequestRequestTypeDef,
     DeregisterClusterRequestRequestTypeDef,
     DescribeAddonConfigurationRequestRequestTypeDef,
+    DescribeAddonConfigurationResponseTypeDef,
     WaiterConfigTypeDef,
     DescribeAddonRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
     DescribeAddonVersionsRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeFargateProfileRequestRequestTypeDef,
     IdentityProviderConfigTypeDef,
     DescribeNodegroupRequestRequestTypeDef,
     DescribeUpdateRequestRequestTypeDef,
     ProviderTypeDef,
     ErrorDetailTypeDef,
     OidcIdentityProviderConfigTypeDef,
     OIDCTypeDef,
     IssueTypeDef,
+    ListAddonsRequestListAddonsPaginateTypeDef,
     ListAddonsRequestRequestTypeDef,
+    ListAddonsResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
     ListFargateProfilesRequestRequestTypeDef,
+    ListFargateProfilesResponseTypeDef,
+    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
     ListIdentityProviderConfigsRequestRequestTypeDef,
+    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
     ListNodegroupsRequestRequestTypeDef,
+    ListNodegroupsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUpdatesRequestListUpdatesPaginateTypeDef,
     ListUpdatesRequestRequestTypeDef,
+    ListUpdatesResponseTypeDef,
     LogSetupTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddonRequestRequestTypeDef,
     UpdateClusterVersionRequestRequestTypeDef,
     UpdateLabelsPayloadTypeDef,
     UpdateParamTypeDef,
     AddonHealthTypeDef,
     AddonVersionInfoTypeDef,
-    DescribeAddonConfigurationResponseTypeDef,
-    ListAddonsResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListFargateProfilesResponseTypeDef,
-    ListNodegroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListUpdatesResponseTypeDef,
     AssociateIdentityProviderConfigRequestRequestTypeDef,
     NodegroupResourcesTypeDef,
     ClusterHealthTypeDef,
     RegisterClusterRequestRequestTypeDef,
     OutpostConfigRequestTypeDef,
     OutpostConfigResponseTypeDef,
     CreateFargateProfileRequestRequestTypeDef,
@@ -494,21 +501,14 @@
     DescribeAddonRequestAddonDeletedWaitTypeDef,
     DescribeClusterRequestClusterActiveWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileActiveWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileDeletedWaitTypeDef,
     DescribeNodegroupRequestNodegroupActiveWaitTypeDef,
     DescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
-    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
-    ListAddonsRequestListAddonsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
-    ListUpdatesRequestListUpdatesPaginateTypeDef,
     DescribeIdentityProviderConfigRequestRequestTypeDef,
     DisassociateIdentityProviderConfigRequestRequestTypeDef,
     ListIdentityProviderConfigsResponseTypeDef,
     EncryptionConfigTypeDef,
     IdentityProviderConfigResponseTypeDef,
     IdentityTypeDef,
     NodegroupHealthTypeDef,
@@ -557,43 +557,43 @@
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

### Comparing `types-aiobotocore-eks-2.5.0.post1/README.md` & `types-aiobotocore-eks-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-eks"></a>
 
 # types-aiobotocore-eks
 
 [![PyPI - types-aiobotocore-eks](https://img.shields.io/pypi/v/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-eks?color=blue)](https://pypistats.org/packages/types-aiobotocore-eks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EKS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
+[aiobotocore.EKS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
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
 [types-aiobotocore-eks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -379,15 +379,14 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_eks.type_defs import (
     AddonIssueTypeDef,
     MarketplaceInformationTypeDef,
     CompatibilityTypeDef,
-    ResponseMetadataTypeDef,
     OidcIdentityProviderConfigRequestTypeDef,
     AutoScalingGroupTypeDef,
     CertificateTypeDef,
     ClusterIssueTypeDef,
     ConnectorConfigResponseTypeDef,
     KubernetesNetworkConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
@@ -405,51 +404,59 @@
     TaintTypeDef,
     DeleteAddonRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteFargateProfileRequestRequestTypeDef,
     DeleteNodegroupRequestRequestTypeDef,
     DeregisterClusterRequestRequestTypeDef,
     DescribeAddonConfigurationRequestRequestTypeDef,
+    DescribeAddonConfigurationResponseTypeDef,
     WaiterConfigTypeDef,
     DescribeAddonRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
     DescribeAddonVersionsRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeFargateProfileRequestRequestTypeDef,
     IdentityProviderConfigTypeDef,
     DescribeNodegroupRequestRequestTypeDef,
     DescribeUpdateRequestRequestTypeDef,
     ProviderTypeDef,
     ErrorDetailTypeDef,
     OidcIdentityProviderConfigTypeDef,
     OIDCTypeDef,
     IssueTypeDef,
+    ListAddonsRequestListAddonsPaginateTypeDef,
     ListAddonsRequestRequestTypeDef,
+    ListAddonsResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
     ListFargateProfilesRequestRequestTypeDef,
+    ListFargateProfilesResponseTypeDef,
+    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
     ListIdentityProviderConfigsRequestRequestTypeDef,
+    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
     ListNodegroupsRequestRequestTypeDef,
+    ListNodegroupsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUpdatesRequestListUpdatesPaginateTypeDef,
     ListUpdatesRequestRequestTypeDef,
+    ListUpdatesResponseTypeDef,
     LogSetupTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddonRequestRequestTypeDef,
     UpdateClusterVersionRequestRequestTypeDef,
     UpdateLabelsPayloadTypeDef,
     UpdateParamTypeDef,
     AddonHealthTypeDef,
     AddonVersionInfoTypeDef,
-    DescribeAddonConfigurationResponseTypeDef,
-    ListAddonsResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListFargateProfilesResponseTypeDef,
-    ListNodegroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListUpdatesResponseTypeDef,
     AssociateIdentityProviderConfigRequestRequestTypeDef,
     NodegroupResourcesTypeDef,
     ClusterHealthTypeDef,
     RegisterClusterRequestRequestTypeDef,
     OutpostConfigRequestTypeDef,
     OutpostConfigResponseTypeDef,
     CreateFargateProfileRequestRequestTypeDef,
@@ -461,21 +468,14 @@
     DescribeAddonRequestAddonDeletedWaitTypeDef,
     DescribeClusterRequestClusterActiveWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileActiveWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileDeletedWaitTypeDef,
     DescribeNodegroupRequestNodegroupActiveWaitTypeDef,
     DescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
-    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
-    ListAddonsRequestListAddonsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
-    ListUpdatesRequestListUpdatesPaginateTypeDef,
     DescribeIdentityProviderConfigRequestRequestTypeDef,
     DisassociateIdentityProviderConfigRequestRequestTypeDef,
     ListIdentityProviderConfigsResponseTypeDef,
     EncryptionConfigTypeDef,
     IdentityProviderConfigResponseTypeDef,
     IdentityTypeDef,
     NodegroupHealthTypeDef,
@@ -524,43 +524,43 @@
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

### Comparing `types-aiobotocore-eks-2.5.0.post1/setup.py` & `types-aiobotocore-eks-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-eks.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-eks",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_eks"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EKS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.EKS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/",
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

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__init__.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__init__.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/__main__.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EKS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EKS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS\nOther"
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

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/client.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/client.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/literals.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -271,14 +271,15 @@
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
@@ -357,14 +358,15 @@
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
@@ -375,14 +377,15 @@
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
@@ -418,14 +421,15 @@
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
@@ -444,16 +448,19 @@
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
@@ -537,15 +544,17 @@
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
@@ -593,14 +602,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/literals.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -269,14 +269,15 @@
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
@@ -355,14 +356,15 @@
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
@@ -373,14 +375,15 @@
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
@@ -416,14 +419,15 @@
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
@@ -442,16 +446,19 @@
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
@@ -535,15 +542,17 @@
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
@@ -591,14 +600,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/paginator.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_fargate_profiles_paginator: ListFargateProfilesPaginator = client.get_paginator("list_fargate_profiles")
         list_identity_provider_configs_paginator: ListIdentityProviderConfigsPaginator = client.get_paginator("list_identity_provider_configs")
         list_nodegroups_paginator: ListNodegroupsPaginator = client.get_paginator("list_nodegroups")
         list_updates_paginator: ListUpdatesPaginator = client.get_paginator("list_updates")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAddonVersionsResponseTypeDef,
     ListAddonsResponseTypeDef,
@@ -45,20 +44,14 @@
     ListFargateProfilesResponseTypeDef,
     ListIdentityProviderConfigsResponseTypeDef,
     ListNodegroupsResponseTypeDef,
     ListUpdatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAddonVersionsPaginator",
     "ListAddonsPaginator",
     "ListClustersPaginator",
     "ListFargateProfilesPaginator",
     "ListIdentityProviderConfigsPaginator",
     "ListNodegroupsPaginator",
@@ -86,90 +79,90 @@
         self,
         *,
         kubernetesVersion: str = ...,
         addonName: str = ...,
         types: Sequence[str] = ...,
         publishers: Sequence[str] = ...,
         owners: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAddonVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.DescribeAddonVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#describeaddonversionspaginator)
         """
 
 
 class ListAddonsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListAddons)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listaddonspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAddonsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListAddons.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listaddonspaginator)
         """
 
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, include: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, include: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listclusterspaginator)
         """
 
 
 class ListFargateProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListFargateProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listfargateprofilespaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFargateProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListFargateProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listfargateprofilespaginator)
         """
 
 
 class ListIdentityProviderConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListIdentityProviderConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listidentityproviderconfigspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityProviderConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListIdentityProviderConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listidentityproviderconfigspaginator)
         """
 
 
 class ListNodegroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListNodegroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listnodegroupspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNodegroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListNodegroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listnodegroupspaginator)
         """
 
 
@@ -181,13 +174,13 @@
 
     def paginate(
         self,
         *,
         name: str,
         nodegroupName: str = ...,
         addonName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listupdatespaginator)
         """
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/paginator.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_fargate_profiles_paginator: ListFargateProfilesPaginator = client.get_paginator("list_fargate_profiles")
         list_identity_provider_configs_paginator: ListIdentityProviderConfigsPaginator = client.get_paginator("list_identity_provider_configs")
         list_nodegroups_paginator: ListNodegroupsPaginator = client.get_paginator("list_nodegroups")
         list_updates_paginator: ListUpdatesPaginator = client.get_paginator("list_updates")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAddonVersionsResponseTypeDef,
     ListAddonsResponseTypeDef,
@@ -45,19 +44,14 @@
     ListFargateProfilesResponseTypeDef,
     ListIdentityProviderConfigsResponseTypeDef,
     ListNodegroupsResponseTypeDef,
     ListUpdatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAddonVersionsPaginator",
     "ListAddonsPaginator",
     "ListClustersPaginator",
     "ListFargateProfilesPaginator",
     "ListIdentityProviderConfigsPaginator",
     "ListNodegroupsPaginator",
@@ -82,85 +76,85 @@
         self,
         *,
         kubernetesVersion: str = ...,
         addonName: str = ...,
         types: Sequence[str] = ...,
         publishers: Sequence[str] = ...,
         owners: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAddonVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.DescribeAddonVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#describeaddonversionspaginator)
         """
 
 class ListAddonsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListAddons)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listaddonspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAddonsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListAddons.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listaddonspaginator)
         """
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, include: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, include: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listclusterspaginator)
         """
 
 class ListFargateProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListFargateProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listfargateprofilespaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFargateProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListFargateProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listfargateprofilespaginator)
         """
 
 class ListIdentityProviderConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListIdentityProviderConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listidentityproviderconfigspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityProviderConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListIdentityProviderConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listidentityproviderconfigspaginator)
         """
 
 class ListNodegroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListNodegroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listnodegroupspaginator)
     """
 
     def paginate(
-        self, *, clusterName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNodegroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListNodegroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listnodegroupspaginator)
         """
 
 class ListUpdatesPaginator(AioPaginator):
@@ -171,13 +165,13 @@
 
     def paginate(
         self,
         *,
         name: str,
         nodegroupName: str = ...,
         addonName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS.Paginator.ListUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/paginators/#listupdatespaginator)
         """
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/type_defs.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -43,15 +43,14 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddonIssueTypeDef",
     "MarketplaceInformationTypeDef",
     "CompatibilityTypeDef",
-    "ResponseMetadataTypeDef",
     "OidcIdentityProviderConfigRequestTypeDef",
     "AutoScalingGroupTypeDef",
     "CertificateTypeDef",
     "ClusterIssueTypeDef",
     "ConnectorConfigResponseTypeDef",
     "KubernetesNetworkConfigResponseTypeDef",
     "VpcConfigResponseTypeDef",
@@ -69,51 +68,59 @@
     "TaintTypeDef",
     "DeleteAddonRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteFargateProfileRequestRequestTypeDef",
     "DeleteNodegroupRequestRequestTypeDef",
     "DeregisterClusterRequestRequestTypeDef",
     "DescribeAddonConfigurationRequestRequestTypeDef",
+    "DescribeAddonConfigurationResponseTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAddonRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
     "DescribeAddonVersionsRequestRequestTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeFargateProfileRequestRequestTypeDef",
     "IdentityProviderConfigTypeDef",
     "DescribeNodegroupRequestRequestTypeDef",
     "DescribeUpdateRequestRequestTypeDef",
     "ProviderTypeDef",
     "ErrorDetailTypeDef",
     "OidcIdentityProviderConfigTypeDef",
     "OIDCTypeDef",
     "IssueTypeDef",
+    "ListAddonsRequestListAddonsPaginateTypeDef",
     "ListAddonsRequestRequestTypeDef",
+    "ListAddonsResponseTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListClustersResponseTypeDef",
+    "ListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
     "ListFargateProfilesRequestRequestTypeDef",
+    "ListFargateProfilesResponseTypeDef",
+    "ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
     "ListIdentityProviderConfigsRequestRequestTypeDef",
+    "ListNodegroupsRequestListNodegroupsPaginateTypeDef",
     "ListNodegroupsRequestRequestTypeDef",
+    "ListNodegroupsResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListUpdatesRequestListUpdatesPaginateTypeDef",
     "ListUpdatesRequestRequestTypeDef",
+    "ListUpdatesResponseTypeDef",
     "LogSetupTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddonRequestRequestTypeDef",
     "UpdateClusterVersionRequestRequestTypeDef",
     "UpdateLabelsPayloadTypeDef",
     "UpdateParamTypeDef",
     "AddonHealthTypeDef",
     "AddonVersionInfoTypeDef",
-    "DescribeAddonConfigurationResponseTypeDef",
-    "ListAddonsResponseTypeDef",
-    "ListClustersResponseTypeDef",
-    "ListFargateProfilesResponseTypeDef",
-    "ListNodegroupsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListUpdatesResponseTypeDef",
     "AssociateIdentityProviderConfigRequestRequestTypeDef",
     "NodegroupResourcesTypeDef",
     "ClusterHealthTypeDef",
     "RegisterClusterRequestRequestTypeDef",
     "OutpostConfigRequestTypeDef",
     "OutpostConfigResponseTypeDef",
     "CreateFargateProfileRequestRequestTypeDef",
@@ -125,21 +132,14 @@
     "DescribeAddonRequestAddonDeletedWaitTypeDef",
     "DescribeClusterRequestClusterActiveWaitTypeDef",
     "DescribeClusterRequestClusterDeletedWaitTypeDef",
     "DescribeFargateProfileRequestFargateProfileActiveWaitTypeDef",
     "DescribeFargateProfileRequestFargateProfileDeletedWaitTypeDef",
     "DescribeNodegroupRequestNodegroupActiveWaitTypeDef",
     "DescribeNodegroupRequestNodegroupDeletedWaitTypeDef",
-    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
-    "ListAddonsRequestListAddonsPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    "ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    "ListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    "ListUpdatesRequestListUpdatesPaginateTypeDef",
     "DescribeIdentityProviderConfigRequestRequestTypeDef",
     "DisassociateIdentityProviderConfigRequestRequestTypeDef",
     "ListIdentityProviderConfigsResponseTypeDef",
     "EncryptionConfigTypeDef",
     "IdentityProviderConfigResponseTypeDef",
     "IdentityTypeDef",
     "NodegroupHealthTypeDef",
@@ -205,25 +205,14 @@
         "clusterVersion": str,
         "platformVersions": List[str],
         "defaultVersion": bool,
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
 _RequiredOidcIdentityProviderConfigRequestTypeDef = TypedDict(
     "_RequiredOidcIdentityProviderConfigRequestTypeDef",
     {
         "identityProviderConfigName": str,
         "issuerUrl": str,
         "clientId": str,
     },
@@ -495,14 +484,24 @@
     "DescribeAddonConfigurationRequestRequestTypeDef",
     {
         "addonName": str,
         "addonVersion": str,
     },
 )
 
+DescribeAddonConfigurationResponseTypeDef = TypedDict(
+    "DescribeAddonConfigurationResponseTypeDef",
+    {
+        "addonName": str,
+        "addonVersion": str,
+        "configurationSchema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -512,20 +511,23 @@
     "DescribeAddonRequestRequestTypeDef",
     {
         "clusterName": str,
         "addonName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef = TypedDict(
+    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "kubernetesVersion": str,
+        "addonName": str,
+        "types": Sequence[str],
+        "publishers": Sequence[str],
+        "owners": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAddonVersionsRequestRequestTypeDef = TypedDict(
     "DescribeAddonVersionsRequestRequestTypeDef",
     {
@@ -645,14 +647,36 @@
         "code": NodegroupIssueCodeType,
         "message": str,
         "resourceIds": List[str],
     },
     total=False,
 )
 
+_RequiredListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
+    "_RequiredListAddonsRequestListAddonsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
+    "_OptionalListAddonsRequestListAddonsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAddonsRequestListAddonsPaginateTypeDef(
+    _RequiredListAddonsRequestListAddonsPaginateTypeDef,
+    _OptionalListAddonsRequestListAddonsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAddonsRequestRequestTypeDef = TypedDict(
     "_RequiredListAddonsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListAddonsRequestRequestTypeDef = TypedDict(
@@ -667,24 +691,73 @@
 
 class ListAddonsRequestRequestTypeDef(
     _RequiredListAddonsRequestRequestTypeDef, _OptionalListAddonsRequestRequestTypeDef
 ):
     pass
 
 
+ListAddonsResponseTypeDef = TypedDict(
+    "ListAddonsResponseTypeDef",
+    {
+        "addons": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "include": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "include": Sequence[str],
     },
     total=False,
 )
 
+ListClustersResponseTypeDef = TypedDict(
+    "ListClustersResponseTypeDef",
+    {
+        "clusters": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFargateProfilesRequestListFargateProfilesPaginateTypeDef(
+    _RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
+    _OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFargateProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListFargateProfilesRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListFargateProfilesRequestRequestTypeDef = TypedDict(
@@ -700,14 +773,45 @@
 class ListFargateProfilesRequestRequestTypeDef(
     _RequiredListFargateProfilesRequestRequestTypeDef,
     _OptionalListFargateProfilesRequestRequestTypeDef,
 ):
     pass
 
 
+ListFargateProfilesResponseTypeDef = TypedDict(
+    "ListFargateProfilesResponseTypeDef",
+    {
+        "fargateProfileNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef(
+    _RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
+    _OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListIdentityProviderConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListIdentityProviderConfigsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListIdentityProviderConfigsRequestRequestTypeDef = TypedDict(
@@ -723,14 +827,36 @@
 class ListIdentityProviderConfigsRequestRequestTypeDef(
     _RequiredListIdentityProviderConfigsRequestRequestTypeDef,
     _OptionalListIdentityProviderConfigsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
+    "_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
+    "_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListNodegroupsRequestListNodegroupsPaginateTypeDef(
+    _RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef,
+    _OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListNodegroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListNodegroupsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListNodegroupsRequestRequestTypeDef = TypedDict(
@@ -745,21 +871,62 @@
 
 class ListNodegroupsRequestRequestTypeDef(
     _RequiredListNodegroupsRequestRequestTypeDef, _OptionalListNodegroupsRequestRequestTypeDef
 ):
     pass
 
 
+ListNodegroupsResponseTypeDef = TypedDict(
+    "ListNodegroupsResponseTypeDef",
+    {
+        "nodegroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
+    "_RequiredListUpdatesRequestListUpdatesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
+    "_OptionalListUpdatesRequestListUpdatesPaginateTypeDef",
+    {
+        "nodegroupName": str,
+        "addonName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUpdatesRequestListUpdatesPaginateTypeDef(
+    _RequiredListUpdatesRequestListUpdatesPaginateTypeDef,
+    _OptionalListUpdatesRequestListUpdatesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUpdatesRequestRequestTypeDef = TypedDict(
     "_RequiredListUpdatesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListUpdatesRequestRequestTypeDef = TypedDict(
@@ -776,23 +943,53 @@
 
 class ListUpdatesRequestRequestTypeDef(
     _RequiredListUpdatesRequestRequestTypeDef, _OptionalListUpdatesRequestRequestTypeDef
 ):
     pass
 
 
+ListUpdatesResponseTypeDef = TypedDict(
+    "ListUpdatesResponseTypeDef",
+    {
+        "updateIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LogSetupTypeDef = TypedDict(
     "LogSetupTypeDef",
     {
         "types": Sequence[LogTypeType],
         "enabled": bool,
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -887,77 +1084,14 @@
         "architecture": List[str],
         "compatibilities": List[CompatibilityTypeDef],
         "requiresConfiguration": bool,
     },
     total=False,
 )
 
-DescribeAddonConfigurationResponseTypeDef = TypedDict(
-    "DescribeAddonConfigurationResponseTypeDef",
-    {
-        "addonName": str,
-        "addonVersion": str,
-        "configurationSchema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAddonsResponseTypeDef = TypedDict(
-    "ListAddonsResponseTypeDef",
-    {
-        "addons": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClustersResponseTypeDef = TypedDict(
-    "ListClustersResponseTypeDef",
-    {
-        "clusters": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFargateProfilesResponseTypeDef = TypedDict(
-    "ListFargateProfilesResponseTypeDef",
-    {
-        "fargateProfileNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNodegroupsResponseTypeDef = TypedDict(
-    "ListNodegroupsResponseTypeDef",
-    {
-        "nodegroups": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListUpdatesResponseTypeDef = TypedDict(
-    "ListUpdatesResponseTypeDef",
-    {
-        "updateIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredAssociateIdentityProviderConfigRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateIdentityProviderConfigRequestRequestTypeDef",
     {
         "clusterName": str,
         "oidc": OidcIdentityProviderConfigRequestTypeDef,
     },
 )
@@ -1356,148 +1490,14 @@
 class DescribeNodegroupRequestNodegroupDeletedWaitTypeDef(
     _RequiredDescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
     _OptionalDescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
 ):
     pass
 
 
-DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef = TypedDict(
-    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
-    {
-        "kubernetesVersion": str,
-        "addonName": str,
-        "types": Sequence[str],
-        "publishers": Sequence[str],
-        "owners": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
-    "_RequiredListAddonsRequestListAddonsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
-    "_OptionalListAddonsRequestListAddonsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAddonsRequestListAddonsPaginateTypeDef(
-    _RequiredListAddonsRequestListAddonsPaginateTypeDef,
-    _OptionalListAddonsRequestListAddonsPaginateTypeDef,
-):
-    pass
-
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "include": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFargateProfilesRequestListFargateProfilesPaginateTypeDef(
-    _RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-    _OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef(
-    _RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-    _OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
-    "_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
-    "_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListNodegroupsRequestListNodegroupsPaginateTypeDef(
-    _RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef,
-    _OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
-    "_RequiredListUpdatesRequestListUpdatesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
-    "_OptionalListUpdatesRequestListUpdatesPaginateTypeDef",
-    {
-        "nodegroupName": str,
-        "addonName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUpdatesRequestListUpdatesPaginateTypeDef(
-    _RequiredListUpdatesRequestListUpdatesPaginateTypeDef,
-    _OptionalListUpdatesRequestListUpdatesPaginateTypeDef,
-):
-    pass
-
-
 DescribeIdentityProviderConfigRequestRequestTypeDef = TypedDict(
     "DescribeIdentityProviderConfigRequestRequestTypeDef",
     {
         "clusterName": str,
         "identityProviderConfig": IdentityProviderConfigTypeDef,
     },
 )
@@ -1526,15 +1526,15 @@
 
 
 ListIdentityProviderConfigsResponseTypeDef = TypedDict(
     "ListIdentityProviderConfigsResponseTypeDef",
     {
         "identityProviderConfigs": List[IdentityProviderConfigTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EncryptionConfigTypeDef = TypedDict(
     "EncryptionConfigTypeDef",
     {
         "resources": Sequence[str],
@@ -1622,31 +1622,31 @@
     total=False,
 )
 
 CreateFargateProfileResponseTypeDef = TypedDict(
     "CreateFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFargateProfileResponseTypeDef = TypedDict(
     "DeleteFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFargateProfileResponseTypeDef = TypedDict(
     "DescribeFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateNodegroupConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNodegroupConfigRequestRequestTypeDef",
     {
         "clusterName": str,
@@ -1696,15 +1696,15 @@
     pass
 
 
 DescribeIdentityProviderConfigResponseTypeDef = TypedDict(
     "DescribeIdentityProviderConfigResponseTypeDef",
     {
         "identityProviderConfig": IdentityProviderConfigResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodegroupTypeDef = TypedDict(
     "NodegroupTypeDef",
     {
         "nodegroupName": str,
@@ -1814,172 +1814,172 @@
     pass
 
 
 AssociateEncryptionConfigResponseTypeDef = TypedDict(
     "AssociateEncryptionConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateIdentityProviderConfigResponseTypeDef = TypedDict(
     "AssociateIdentityProviderConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUpdateResponseTypeDef = TypedDict(
     "DescribeUpdateResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateIdentityProviderConfigResponseTypeDef = TypedDict(
     "DisassociateIdentityProviderConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAddonResponseTypeDef = TypedDict(
     "UpdateAddonResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterConfigResponseTypeDef = TypedDict(
     "UpdateClusterConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterVersionResponseTypeDef = TypedDict(
     "UpdateClusterVersionResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNodegroupConfigResponseTypeDef = TypedDict(
     "UpdateNodegroupConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNodegroupVersionResponseTypeDef = TypedDict(
     "UpdateNodegroupVersionResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAddonResponseTypeDef = TypedDict(
     "CreateAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAddonResponseTypeDef = TypedDict(
     "DeleteAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddonResponseTypeDef = TypedDict(
     "DescribeAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddonVersionsResponseTypeDef = TypedDict(
     "DescribeAddonVersionsResponseTypeDef",
     {
         "addons": List[AddonInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNodegroupResponseTypeDef = TypedDict(
     "CreateNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNodegroupResponseTypeDef = TypedDict(
     "DeleteNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNodegroupResponseTypeDef = TypedDict(
     "DescribeNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterClusterResponseTypeDef = TypedDict(
     "DeregisterClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClusterResponseTypeDef = TypedDict(
     "DescribeClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterClusterResponseTypeDef = TypedDict(
     "RegisterClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/type_defs.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -42,15 +42,14 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddonIssueTypeDef",
     "MarketplaceInformationTypeDef",
     "CompatibilityTypeDef",
-    "ResponseMetadataTypeDef",
     "OidcIdentityProviderConfigRequestTypeDef",
     "AutoScalingGroupTypeDef",
     "CertificateTypeDef",
     "ClusterIssueTypeDef",
     "ConnectorConfigResponseTypeDef",
     "KubernetesNetworkConfigResponseTypeDef",
     "VpcConfigResponseTypeDef",
@@ -68,51 +67,59 @@
     "TaintTypeDef",
     "DeleteAddonRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteFargateProfileRequestRequestTypeDef",
     "DeleteNodegroupRequestRequestTypeDef",
     "DeregisterClusterRequestRequestTypeDef",
     "DescribeAddonConfigurationRequestRequestTypeDef",
+    "DescribeAddonConfigurationResponseTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAddonRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
     "DescribeAddonVersionsRequestRequestTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeFargateProfileRequestRequestTypeDef",
     "IdentityProviderConfigTypeDef",
     "DescribeNodegroupRequestRequestTypeDef",
     "DescribeUpdateRequestRequestTypeDef",
     "ProviderTypeDef",
     "ErrorDetailTypeDef",
     "OidcIdentityProviderConfigTypeDef",
     "OIDCTypeDef",
     "IssueTypeDef",
+    "ListAddonsRequestListAddonsPaginateTypeDef",
     "ListAddonsRequestRequestTypeDef",
+    "ListAddonsResponseTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListClustersResponseTypeDef",
+    "ListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
     "ListFargateProfilesRequestRequestTypeDef",
+    "ListFargateProfilesResponseTypeDef",
+    "ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
     "ListIdentityProviderConfigsRequestRequestTypeDef",
+    "ListNodegroupsRequestListNodegroupsPaginateTypeDef",
     "ListNodegroupsRequestRequestTypeDef",
+    "ListNodegroupsResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListUpdatesRequestListUpdatesPaginateTypeDef",
     "ListUpdatesRequestRequestTypeDef",
+    "ListUpdatesResponseTypeDef",
     "LogSetupTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddonRequestRequestTypeDef",
     "UpdateClusterVersionRequestRequestTypeDef",
     "UpdateLabelsPayloadTypeDef",
     "UpdateParamTypeDef",
     "AddonHealthTypeDef",
     "AddonVersionInfoTypeDef",
-    "DescribeAddonConfigurationResponseTypeDef",
-    "ListAddonsResponseTypeDef",
-    "ListClustersResponseTypeDef",
-    "ListFargateProfilesResponseTypeDef",
-    "ListNodegroupsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListUpdatesResponseTypeDef",
     "AssociateIdentityProviderConfigRequestRequestTypeDef",
     "NodegroupResourcesTypeDef",
     "ClusterHealthTypeDef",
     "RegisterClusterRequestRequestTypeDef",
     "OutpostConfigRequestTypeDef",
     "OutpostConfigResponseTypeDef",
     "CreateFargateProfileRequestRequestTypeDef",
@@ -124,21 +131,14 @@
     "DescribeAddonRequestAddonDeletedWaitTypeDef",
     "DescribeClusterRequestClusterActiveWaitTypeDef",
     "DescribeClusterRequestClusterDeletedWaitTypeDef",
     "DescribeFargateProfileRequestFargateProfileActiveWaitTypeDef",
     "DescribeFargateProfileRequestFargateProfileDeletedWaitTypeDef",
     "DescribeNodegroupRequestNodegroupActiveWaitTypeDef",
     "DescribeNodegroupRequestNodegroupDeletedWaitTypeDef",
-    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
-    "ListAddonsRequestListAddonsPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    "ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    "ListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    "ListUpdatesRequestListUpdatesPaginateTypeDef",
     "DescribeIdentityProviderConfigRequestRequestTypeDef",
     "DisassociateIdentityProviderConfigRequestRequestTypeDef",
     "ListIdentityProviderConfigsResponseTypeDef",
     "EncryptionConfigTypeDef",
     "IdentityProviderConfigResponseTypeDef",
     "IdentityTypeDef",
     "NodegroupHealthTypeDef",
@@ -204,25 +204,14 @@
         "clusterVersion": str,
         "platformVersions": List[str],
         "defaultVersion": bool,
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
 _RequiredOidcIdentityProviderConfigRequestTypeDef = TypedDict(
     "_RequiredOidcIdentityProviderConfigRequestTypeDef",
     {
         "identityProviderConfigName": str,
         "issuerUrl": str,
         "clientId": str,
     },
@@ -488,14 +477,24 @@
     "DescribeAddonConfigurationRequestRequestTypeDef",
     {
         "addonName": str,
         "addonVersion": str,
     },
 )
 
+DescribeAddonConfigurationResponseTypeDef = TypedDict(
+    "DescribeAddonConfigurationResponseTypeDef",
+    {
+        "addonName": str,
+        "addonVersion": str,
+        "configurationSchema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -505,20 +504,23 @@
     "DescribeAddonRequestRequestTypeDef",
     {
         "clusterName": str,
         "addonName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef = TypedDict(
+    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "kubernetesVersion": str,
+        "addonName": str,
+        "types": Sequence[str],
+        "publishers": Sequence[str],
+        "owners": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAddonVersionsRequestRequestTypeDef = TypedDict(
     "DescribeAddonVersionsRequestRequestTypeDef",
     {
@@ -636,14 +638,34 @@
         "code": NodegroupIssueCodeType,
         "message": str,
         "resourceIds": List[str],
     },
     total=False,
 )
 
+_RequiredListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
+    "_RequiredListAddonsRequestListAddonsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
+    "_OptionalListAddonsRequestListAddonsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAddonsRequestListAddonsPaginateTypeDef(
+    _RequiredListAddonsRequestListAddonsPaginateTypeDef,
+    _OptionalListAddonsRequestListAddonsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAddonsRequestRequestTypeDef = TypedDict(
     "_RequiredListAddonsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListAddonsRequestRequestTypeDef = TypedDict(
@@ -656,24 +678,71 @@
 )
 
 class ListAddonsRequestRequestTypeDef(
     _RequiredListAddonsRequestRequestTypeDef, _OptionalListAddonsRequestRequestTypeDef
 ):
     pass
 
+ListAddonsResponseTypeDef = TypedDict(
+    "ListAddonsResponseTypeDef",
+    {
+        "addons": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "include": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "include": Sequence[str],
     },
     total=False,
 )
 
+ListClustersResponseTypeDef = TypedDict(
+    "ListClustersResponseTypeDef",
+    {
+        "clusters": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFargateProfilesRequestListFargateProfilesPaginateTypeDef(
+    _RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
+    _OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
+):
+    pass
+
 _RequiredListFargateProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListFargateProfilesRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListFargateProfilesRequestRequestTypeDef = TypedDict(
@@ -687,14 +756,43 @@
 
 class ListFargateProfilesRequestRequestTypeDef(
     _RequiredListFargateProfilesRequestRequestTypeDef,
     _OptionalListFargateProfilesRequestRequestTypeDef,
 ):
     pass
 
+ListFargateProfilesResponseTypeDef = TypedDict(
+    "ListFargateProfilesResponseTypeDef",
+    {
+        "fargateProfileNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef(
+    _RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
+    _OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
+):
+    pass
+
 _RequiredListIdentityProviderConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListIdentityProviderConfigsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListIdentityProviderConfigsRequestRequestTypeDef = TypedDict(
@@ -708,14 +806,34 @@
 
 class ListIdentityProviderConfigsRequestRequestTypeDef(
     _RequiredListIdentityProviderConfigsRequestRequestTypeDef,
     _OptionalListIdentityProviderConfigsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
+    "_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef",
+    {
+        "clusterName": str,
+    },
+)
+_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
+    "_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListNodegroupsRequestListNodegroupsPaginateTypeDef(
+    _RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef,
+    _OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListNodegroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListNodegroupsRequestRequestTypeDef",
     {
         "clusterName": str,
     },
 )
 _OptionalListNodegroupsRequestRequestTypeDef = TypedDict(
@@ -728,21 +846,60 @@
 )
 
 class ListNodegroupsRequestRequestTypeDef(
     _RequiredListNodegroupsRequestRequestTypeDef, _OptionalListNodegroupsRequestRequestTypeDef
 ):
     pass
 
+ListNodegroupsResponseTypeDef = TypedDict(
+    "ListNodegroupsResponseTypeDef",
+    {
+        "nodegroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
+    "_RequiredListUpdatesRequestListUpdatesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
+    "_OptionalListUpdatesRequestListUpdatesPaginateTypeDef",
+    {
+        "nodegroupName": str,
+        "addonName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUpdatesRequestListUpdatesPaginateTypeDef(
+    _RequiredListUpdatesRequestListUpdatesPaginateTypeDef,
+    _OptionalListUpdatesRequestListUpdatesPaginateTypeDef,
+):
+    pass
+
 _RequiredListUpdatesRequestRequestTypeDef = TypedDict(
     "_RequiredListUpdatesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListUpdatesRequestRequestTypeDef = TypedDict(
@@ -757,23 +914,53 @@
 )
 
 class ListUpdatesRequestRequestTypeDef(
     _RequiredListUpdatesRequestRequestTypeDef, _OptionalListUpdatesRequestRequestTypeDef
 ):
     pass
 
+ListUpdatesResponseTypeDef = TypedDict(
+    "ListUpdatesResponseTypeDef",
+    {
+        "updateIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LogSetupTypeDef = TypedDict(
     "LogSetupTypeDef",
     {
         "types": Sequence[LogTypeType],
         "enabled": bool,
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -864,77 +1051,14 @@
         "architecture": List[str],
         "compatibilities": List[CompatibilityTypeDef],
         "requiresConfiguration": bool,
     },
     total=False,
 )
 
-DescribeAddonConfigurationResponseTypeDef = TypedDict(
-    "DescribeAddonConfigurationResponseTypeDef",
-    {
-        "addonName": str,
-        "addonVersion": str,
-        "configurationSchema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAddonsResponseTypeDef = TypedDict(
-    "ListAddonsResponseTypeDef",
-    {
-        "addons": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClustersResponseTypeDef = TypedDict(
-    "ListClustersResponseTypeDef",
-    {
-        "clusters": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFargateProfilesResponseTypeDef = TypedDict(
-    "ListFargateProfilesResponseTypeDef",
-    {
-        "fargateProfileNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNodegroupsResponseTypeDef = TypedDict(
-    "ListNodegroupsResponseTypeDef",
-    {
-        "nodegroups": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListUpdatesResponseTypeDef = TypedDict(
-    "ListUpdatesResponseTypeDef",
-    {
-        "updateIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredAssociateIdentityProviderConfigRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateIdentityProviderConfigRequestRequestTypeDef",
     {
         "clusterName": str,
         "oidc": OidcIdentityProviderConfigRequestTypeDef,
     },
 )
@@ -1303,138 +1427,14 @@
 
 class DescribeNodegroupRequestNodegroupDeletedWaitTypeDef(
     _RequiredDescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
     _OptionalDescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
 ):
     pass
 
-DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef = TypedDict(
-    "DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef",
-    {
-        "kubernetesVersion": str,
-        "addonName": str,
-        "types": Sequence[str],
-        "publishers": Sequence[str],
-        "owners": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
-    "_RequiredListAddonsRequestListAddonsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListAddonsRequestListAddonsPaginateTypeDef = TypedDict(
-    "_OptionalListAddonsRequestListAddonsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAddonsRequestListAddonsPaginateTypeDef(
-    _RequiredListAddonsRequestListAddonsPaginateTypeDef,
-    _OptionalListAddonsRequestListAddonsPaginateTypeDef,
-):
-    pass
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "include": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFargateProfilesRequestListFargateProfilesPaginateTypeDef(
-    _RequiredListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-    _OptionalListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-):
-    pass
-
-_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef(
-    _RequiredListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-    _OptionalListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-):
-    pass
-
-_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
-    "_RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    {
-        "clusterName": str,
-    },
-)
-_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef = TypedDict(
-    "_OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListNodegroupsRequestListNodegroupsPaginateTypeDef(
-    _RequiredListNodegroupsRequestListNodegroupsPaginateTypeDef,
-    _OptionalListNodegroupsRequestListNodegroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
-    "_RequiredListUpdatesRequestListUpdatesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListUpdatesRequestListUpdatesPaginateTypeDef = TypedDict(
-    "_OptionalListUpdatesRequestListUpdatesPaginateTypeDef",
-    {
-        "nodegroupName": str,
-        "addonName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUpdatesRequestListUpdatesPaginateTypeDef(
-    _RequiredListUpdatesRequestListUpdatesPaginateTypeDef,
-    _OptionalListUpdatesRequestListUpdatesPaginateTypeDef,
-):
-    pass
-
 DescribeIdentityProviderConfigRequestRequestTypeDef = TypedDict(
     "DescribeIdentityProviderConfigRequestRequestTypeDef",
     {
         "clusterName": str,
         "identityProviderConfig": IdentityProviderConfigTypeDef,
     },
 )
@@ -1461,15 +1461,15 @@
     pass
 
 ListIdentityProviderConfigsResponseTypeDef = TypedDict(
     "ListIdentityProviderConfigsResponseTypeDef",
     {
         "identityProviderConfigs": List[IdentityProviderConfigTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EncryptionConfigTypeDef = TypedDict(
     "EncryptionConfigTypeDef",
     {
         "resources": Sequence[str],
@@ -1557,31 +1557,31 @@
     total=False,
 )
 
 CreateFargateProfileResponseTypeDef = TypedDict(
     "CreateFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFargateProfileResponseTypeDef = TypedDict(
     "DeleteFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFargateProfileResponseTypeDef = TypedDict(
     "DescribeFargateProfileResponseTypeDef",
     {
         "fargateProfile": FargateProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateNodegroupConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNodegroupConfigRequestRequestTypeDef",
     {
         "clusterName": str,
@@ -1627,15 +1627,15 @@
 ):
     pass
 
 DescribeIdentityProviderConfigResponseTypeDef = TypedDict(
     "DescribeIdentityProviderConfigResponseTypeDef",
     {
         "identityProviderConfig": IdentityProviderConfigResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodegroupTypeDef = TypedDict(
     "NodegroupTypeDef",
     {
         "nodegroupName": str,
@@ -1741,172 +1741,172 @@
 ):
     pass
 
 AssociateEncryptionConfigResponseTypeDef = TypedDict(
     "AssociateEncryptionConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateIdentityProviderConfigResponseTypeDef = TypedDict(
     "AssociateIdentityProviderConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUpdateResponseTypeDef = TypedDict(
     "DescribeUpdateResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateIdentityProviderConfigResponseTypeDef = TypedDict(
     "DisassociateIdentityProviderConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAddonResponseTypeDef = TypedDict(
     "UpdateAddonResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterConfigResponseTypeDef = TypedDict(
     "UpdateClusterConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterVersionResponseTypeDef = TypedDict(
     "UpdateClusterVersionResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNodegroupConfigResponseTypeDef = TypedDict(
     "UpdateNodegroupConfigResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNodegroupVersionResponseTypeDef = TypedDict(
     "UpdateNodegroupVersionResponseTypeDef",
     {
         "update": UpdateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAddonResponseTypeDef = TypedDict(
     "CreateAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAddonResponseTypeDef = TypedDict(
     "DeleteAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddonResponseTypeDef = TypedDict(
     "DescribeAddonResponseTypeDef",
     {
         "addon": AddonTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddonVersionsResponseTypeDef = TypedDict(
     "DescribeAddonVersionsResponseTypeDef",
     {
         "addons": List[AddonInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNodegroupResponseTypeDef = TypedDict(
     "CreateNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNodegroupResponseTypeDef = TypedDict(
     "DeleteNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNodegroupResponseTypeDef = TypedDict(
     "DescribeNodegroupResponseTypeDef",
     {
         "nodegroup": NodegroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterClusterResponseTypeDef = TypedDict(
     "DeregisterClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClusterResponseTypeDef = TypedDict(
     "DescribeClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterClusterResponseTypeDef = TypedDict(
     "RegisterClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/waiter.py` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks/waiter.pyi` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/PKG-INFO` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-eks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EKS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EKS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-eks"></a>
 
 # types-aiobotocore-eks
 
 [![PyPI - types-aiobotocore-eks](https://img.shields.io/pypi/v/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-eks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-eks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-eks?color=blue)](https://pypistats.org/packages/types-aiobotocore-eks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EKS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
+[aiobotocore.EKS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/eks.html#EKS)
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
 [types-aiobotocore-eks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_eks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -412,15 +412,14 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_eks.type_defs import (
     AddonIssueTypeDef,
     MarketplaceInformationTypeDef,
     CompatibilityTypeDef,
-    ResponseMetadataTypeDef,
     OidcIdentityProviderConfigRequestTypeDef,
     AutoScalingGroupTypeDef,
     CertificateTypeDef,
     ClusterIssueTypeDef,
     ConnectorConfigResponseTypeDef,
     KubernetesNetworkConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
@@ -438,51 +437,59 @@
     TaintTypeDef,
     DeleteAddonRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteFargateProfileRequestRequestTypeDef,
     DeleteNodegroupRequestRequestTypeDef,
     DeregisterClusterRequestRequestTypeDef,
     DescribeAddonConfigurationRequestRequestTypeDef,
+    DescribeAddonConfigurationResponseTypeDef,
     WaiterConfigTypeDef,
     DescribeAddonRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
     DescribeAddonVersionsRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeFargateProfileRequestRequestTypeDef,
     IdentityProviderConfigTypeDef,
     DescribeNodegroupRequestRequestTypeDef,
     DescribeUpdateRequestRequestTypeDef,
     ProviderTypeDef,
     ErrorDetailTypeDef,
     OidcIdentityProviderConfigTypeDef,
     OIDCTypeDef,
     IssueTypeDef,
+    ListAddonsRequestListAddonsPaginateTypeDef,
     ListAddonsRequestRequestTypeDef,
+    ListAddonsResponseTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
     ListFargateProfilesRequestRequestTypeDef,
+    ListFargateProfilesResponseTypeDef,
+    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
     ListIdentityProviderConfigsRequestRequestTypeDef,
+    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
     ListNodegroupsRequestRequestTypeDef,
+    ListNodegroupsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUpdatesRequestListUpdatesPaginateTypeDef,
     ListUpdatesRequestRequestTypeDef,
+    ListUpdatesResponseTypeDef,
     LogSetupTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddonRequestRequestTypeDef,
     UpdateClusterVersionRequestRequestTypeDef,
     UpdateLabelsPayloadTypeDef,
     UpdateParamTypeDef,
     AddonHealthTypeDef,
     AddonVersionInfoTypeDef,
-    DescribeAddonConfigurationResponseTypeDef,
-    ListAddonsResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListFargateProfilesResponseTypeDef,
-    ListNodegroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListUpdatesResponseTypeDef,
     AssociateIdentityProviderConfigRequestRequestTypeDef,
     NodegroupResourcesTypeDef,
     ClusterHealthTypeDef,
     RegisterClusterRequestRequestTypeDef,
     OutpostConfigRequestTypeDef,
     OutpostConfigResponseTypeDef,
     CreateFargateProfileRequestRequestTypeDef,
@@ -494,21 +501,14 @@
     DescribeAddonRequestAddonDeletedWaitTypeDef,
     DescribeClusterRequestClusterActiveWaitTypeDef,
     DescribeClusterRequestClusterDeletedWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileActiveWaitTypeDef,
     DescribeFargateProfileRequestFargateProfileDeletedWaitTypeDef,
     DescribeNodegroupRequestNodegroupActiveWaitTypeDef,
     DescribeNodegroupRequestNodegroupDeletedWaitTypeDef,
-    DescribeAddonVersionsRequestDescribeAddonVersionsPaginateTypeDef,
-    ListAddonsRequestListAddonsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListFargateProfilesRequestListFargateProfilesPaginateTypeDef,
-    ListIdentityProviderConfigsRequestListIdentityProviderConfigsPaginateTypeDef,
-    ListNodegroupsRequestListNodegroupsPaginateTypeDef,
-    ListUpdatesRequestListUpdatesPaginateTypeDef,
     DescribeIdentityProviderConfigRequestRequestTypeDef,
     DisassociateIdentityProviderConfigRequestRequestTypeDef,
     ListIdentityProviderConfigsResponseTypeDef,
     EncryptionConfigTypeDef,
     IdentityProviderConfigResponseTypeDef,
     IdentityTypeDef,
     NodegroupHealthTypeDef,
@@ -557,43 +557,43 @@
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

### Comparing `types-aiobotocore-eks-2.5.0.post1/types_aiobotocore_eks.egg-info/SOURCES.txt` & `types-aiobotocore-eks-2.5.1/types_aiobotocore_eks.egg-info/SOURCES.txt`

 * *Files identical despite different names*

