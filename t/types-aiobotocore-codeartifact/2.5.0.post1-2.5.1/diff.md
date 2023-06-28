# Comparing `tmp/types-aiobotocore-codeartifact-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codeartifact-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codeartifact-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-codeartifact-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-codeartifact-2.5.0.post1.tar` & `types-aiobotocore-codeartifact-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.351048 types-aiobotocore-codeartifact-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18622 2023-03-11 12:26:22.351048 types-aiobotocore-codeartifact-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17031 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.351048 types-aiobotocore-codeartifact-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.343048 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/
--rw-r--r--   0 runner    (1001) docker     (123)     1803 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1802 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35446 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35394 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9479 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9477 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9144 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9135 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    45493 2023-03-11 12:11:07.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    45416 2023-03-11 12:11:06.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:05.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.351048 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18622 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:22.000000 types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.574111 types-aiobotocore-codeartifact-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18707 2023-06-28 01:43:15.574111 types-aiobotocore-codeartifact-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17122 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.574111 types-aiobotocore-codeartifact-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.566111 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/
+-rw-r--r--   0 runner    (1001) docker     (123)     1803 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1802 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36432 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36379 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9699 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9697 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9049 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9040 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    46955 2023-06-28 01:27:43.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46876 2023-06-28 01:27:43.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:42.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.574111 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18707 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:15.000000 types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/LICENSE` & `types-aiobotocore-codeartifact-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codeartifact-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeartifact
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeArtifact 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeArtifact 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeartifact"></a>
 
 # types-aiobotocore-codeartifact
 
 [![PyPI - types-aiobotocore-codeartifact](https://img.shields.io/pypi/v/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeartifact?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeartifact)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeArtifact 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
+[aiobotocore.CodeArtifact 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
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
 [types-aiobotocore-codeartifact docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,15 +351,14 @@
 `types_aiobotocore_codeartifact.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeartifact.type_defs import (
     AssetSummaryTypeDef,
     AssociateExternalConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CopyPackageVersionsRequestRequestTypeDef,
     PackageVersionErrorTypeDef,
     SuccessfulPackageVersionInfoTypeDef,
     TagTypeDef,
     DomainDescriptionTypeDef,
     UpstreamRepositoryTypeDef,
     DeleteDomainPermissionsPolicyRequestRequestTypeDef,
@@ -374,43 +373,52 @@
     DescribePackageVersionRequestRequestTypeDef,
     DescribeRepositoryRequestRequestTypeDef,
     DisassociateExternalConnectionRequestRequestTypeDef,
     DisposePackageVersionsRequestRequestTypeDef,
     DomainEntryPointTypeDef,
     DomainSummaryTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
+    GetAuthorizationTokenResultTypeDef,
     GetDomainPermissionsPolicyRequestRequestTypeDef,
     GetPackageVersionAssetRequestRequestTypeDef,
+    GetPackageVersionAssetResultTypeDef,
     GetPackageVersionReadmeRequestRequestTypeDef,
+    GetPackageVersionReadmeResultTypeDef,
     GetRepositoryEndpointRequestRequestTypeDef,
+    GetRepositoryEndpointResultTypeDef,
     GetRepositoryPermissionsPolicyRequestRequestTypeDef,
     LicenseInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
     ListPackageVersionAssetsRequestRequestTypeDef,
     ListPackageVersionDependenciesRequestRequestTypeDef,
     PackageDependencyTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
     ListPackageVersionsRequestRequestTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
     ListPackagesRequestRequestTypeDef,
+    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
     ListRepositoriesInDomainRequestRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListRepositoriesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PackageOriginRestrictionsTypeDef,
+    PaginatorConfigTypeDef,
+    PublishPackageVersionRequestRequestTypeDef,
     PutDomainPermissionsPolicyRequestRequestTypeDef,
     PutRepositoryPermissionsPolicyRequestRequestTypeDef,
     RepositoryExternalConnectionInfoTypeDef,
     UpstreamRepositoryInfoTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePackageVersionsStatusRequestRequestTypeDef,
-    GetAuthorizationTokenResultTypeDef,
-    GetPackageVersionAssetResultTypeDef,
-    GetPackageVersionReadmeResultTypeDef,
-    GetRepositoryEndpointResultTypeDef,
     ListPackageVersionAssetsResultTypeDef,
+    PublishPackageVersionResultTypeDef,
     CopyPackageVersionsResultTypeDef,
     DeletePackageVersionsResultTypeDef,
     DisposePackageVersionsResultTypeDef,
     UpdatePackageVersionsStatusResultTypeDef,
     CreateDomainRequestRequestTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -423,20 +431,14 @@
     DeleteRepositoryPermissionsPolicyResultTypeDef,
     GetDomainPermissionsPolicyResultTypeDef,
     GetRepositoryPermissionsPolicyResultTypeDef,
     PutDomainPermissionsPolicyResultTypeDef,
     PutRepositoryPermissionsPolicyResultTypeDef,
     PackageVersionOriginTypeDef,
     ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-    ListPackagesRequestListPackagesPaginateTypeDef,
-    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListPackageVersionDependenciesResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     PackageOriginConfigurationTypeDef,
     PutPackageOriginConfigurationRequestRequestTypeDef,
     RepositoryDescriptionTypeDef,
     PackageVersionDescriptionTypeDef,
@@ -465,43 +467,43 @@
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/README.md` & `types-aiobotocore-codeartifact-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codeartifact"></a>
 
 # types-aiobotocore-codeartifact
 
 [![PyPI - types-aiobotocore-codeartifact](https://img.shields.io/pypi/v/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeartifact?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeartifact)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeArtifact 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
+[aiobotocore.CodeArtifact 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
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
 [types-aiobotocore-codeartifact docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,15 +318,14 @@
 `types_aiobotocore_codeartifact.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeartifact.type_defs import (
     AssetSummaryTypeDef,
     AssociateExternalConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CopyPackageVersionsRequestRequestTypeDef,
     PackageVersionErrorTypeDef,
     SuccessfulPackageVersionInfoTypeDef,
     TagTypeDef,
     DomainDescriptionTypeDef,
     UpstreamRepositoryTypeDef,
     DeleteDomainPermissionsPolicyRequestRequestTypeDef,
@@ -341,43 +340,52 @@
     DescribePackageVersionRequestRequestTypeDef,
     DescribeRepositoryRequestRequestTypeDef,
     DisassociateExternalConnectionRequestRequestTypeDef,
     DisposePackageVersionsRequestRequestTypeDef,
     DomainEntryPointTypeDef,
     DomainSummaryTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
+    GetAuthorizationTokenResultTypeDef,
     GetDomainPermissionsPolicyRequestRequestTypeDef,
     GetPackageVersionAssetRequestRequestTypeDef,
+    GetPackageVersionAssetResultTypeDef,
     GetPackageVersionReadmeRequestRequestTypeDef,
+    GetPackageVersionReadmeResultTypeDef,
     GetRepositoryEndpointRequestRequestTypeDef,
+    GetRepositoryEndpointResultTypeDef,
     GetRepositoryPermissionsPolicyRequestRequestTypeDef,
     LicenseInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
     ListPackageVersionAssetsRequestRequestTypeDef,
     ListPackageVersionDependenciesRequestRequestTypeDef,
     PackageDependencyTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
     ListPackageVersionsRequestRequestTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
     ListPackagesRequestRequestTypeDef,
+    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
     ListRepositoriesInDomainRequestRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListRepositoriesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PackageOriginRestrictionsTypeDef,
+    PaginatorConfigTypeDef,
+    PublishPackageVersionRequestRequestTypeDef,
     PutDomainPermissionsPolicyRequestRequestTypeDef,
     PutRepositoryPermissionsPolicyRequestRequestTypeDef,
     RepositoryExternalConnectionInfoTypeDef,
     UpstreamRepositoryInfoTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePackageVersionsStatusRequestRequestTypeDef,
-    GetAuthorizationTokenResultTypeDef,
-    GetPackageVersionAssetResultTypeDef,
-    GetPackageVersionReadmeResultTypeDef,
-    GetRepositoryEndpointResultTypeDef,
     ListPackageVersionAssetsResultTypeDef,
+    PublishPackageVersionResultTypeDef,
     CopyPackageVersionsResultTypeDef,
     DeletePackageVersionsResultTypeDef,
     DisposePackageVersionsResultTypeDef,
     UpdatePackageVersionsStatusResultTypeDef,
     CreateDomainRequestRequestTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -390,20 +398,14 @@
     DeleteRepositoryPermissionsPolicyResultTypeDef,
     GetDomainPermissionsPolicyResultTypeDef,
     GetRepositoryPermissionsPolicyResultTypeDef,
     PutDomainPermissionsPolicyResultTypeDef,
     PutRepositoryPermissionsPolicyResultTypeDef,
     PackageVersionOriginTypeDef,
     ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-    ListPackagesRequestListPackagesPaginateTypeDef,
-    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListPackageVersionDependenciesResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     PackageOriginConfigurationTypeDef,
     PutPackageOriginConfigurationRequestRequestTypeDef,
     RepositoryDescriptionTypeDef,
     PackageVersionDescriptionTypeDef,
@@ -432,43 +434,43 @@
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/setup.py` & `types-aiobotocore-codeartifact-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codeartifact.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codeartifact",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codeartifact"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeArtifact 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeArtifact 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/"
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__init__.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__init__.pyi` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/__main__.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeArtifact 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeArtifact 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact\nOther"
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/client.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,17 +11,18 @@
 
     session = get_session()
     async with session.create_client("codeartifact") as client:
         client: CodeArtifactClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
+from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
     PackageFormatType,
     PackageVersionOriginTypeType,
@@ -63,14 +64,15 @@
     ListPackageVersionAssetsResultTypeDef,
     ListPackageVersionDependenciesResultTypeDef,
     ListPackageVersionsResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PackageOriginRestrictionsTypeDef,
+    PublishPackageVersionResultTypeDef,
     PutDomainPermissionsPolicyResultTypeDef,
     PutPackageOriginConfigurationResultTypeDef,
     PutRepositoryPermissionsPolicyResultTypeDef,
     TagTypeDef,
     UpdatePackageVersionsStatusResultTypeDef,
     UpdateRepositoryResultTypeDef,
     UpstreamRepositoryTypeDef,
@@ -596,14 +598,36 @@
         Gets information about Amazon Web Services tags for a specified Amazon Resource
         Name (ARN) in CodeArtifact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/client/#list_tags_for_resource)
         """
 
+    async def publish_package_version(
+        self,
+        *,
+        domain: str,
+        repository: str,
+        format: PackageFormatType,
+        package: str,
+        packageVersion: str,
+        assetContent: Union[str, bytes, IO[Any], StreamingBody],
+        assetName: str,
+        assetSHA256: str,
+        domainOwner: str = ...,
+        namespace: str = ...,
+        unfinished: bool = ...
+    ) -> PublishPackageVersionResultTypeDef:
+        """
+        Creates a new package version containing one or more assets (or files).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.publish_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/client/#publish_package_version)
+        """
+
     async def put_domain_permissions_policy(
         self, *, domain: str, policyDocument: str, domainOwner: str = ..., policyRevision: str = ...
     ) -> PutDomainPermissionsPolicyResultTypeDef:
         """
         Sets a resource policy on a domain that specifies permissions to access it.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.put_domain_permissions_policy)
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/client.pyi` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -11,17 +11,18 @@
 
     session = get_session()
     async with session.create_client("codeartifact") as client:
         client: CodeArtifactClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
+from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
     PackageFormatType,
     PackageVersionOriginTypeType,
@@ -63,14 +64,15 @@
     ListPackageVersionAssetsResultTypeDef,
     ListPackageVersionDependenciesResultTypeDef,
     ListPackageVersionsResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PackageOriginRestrictionsTypeDef,
+    PublishPackageVersionResultTypeDef,
     PutDomainPermissionsPolicyResultTypeDef,
     PutPackageOriginConfigurationResultTypeDef,
     PutRepositoryPermissionsPolicyResultTypeDef,
     TagTypeDef,
     UpdatePackageVersionsStatusResultTypeDef,
     UpdateRepositoryResultTypeDef,
     UpstreamRepositoryTypeDef,
@@ -558,14 +560,35 @@
         """
         Gets information about Amazon Web Services tags for a specified Amazon Resource
         Name (ARN) in CodeArtifact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/client/#list_tags_for_resource)
         """
+    async def publish_package_version(
+        self,
+        *,
+        domain: str,
+        repository: str,
+        format: PackageFormatType,
+        package: str,
+        packageVersion: str,
+        assetContent: Union[str, bytes, IO[Any], StreamingBody],
+        assetName: str,
+        assetSHA256: str,
+        domainOwner: str = ...,
+        namespace: str = ...,
+        unfinished: bool = ...
+    ) -> PublishPackageVersionResultTypeDef:
+        """
+        Creates a new package version containing one or more assets (or files).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.publish_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/client/#publish_package_version)
+        """
     async def put_domain_permissions_policy(
         self, *, domain: str, policyDocument: str, domainOwner: str = ..., policyRevision: str = ...
     ) -> PutDomainPermissionsPolicyResultTypeDef:
         """
         Sets a resource policy on a domain that specifies permissions to access it.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Client.put_domain_permissions_policy)
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/literals.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -51,15 +51,15 @@
 HashAlgorithmType = Literal["MD5", "SHA-1", "SHA-256", "SHA-512"]
 ListDomainsPaginatorName = Literal["list_domains"]
 ListPackageVersionAssetsPaginatorName = Literal["list_package_version_assets"]
 ListPackageVersionsPaginatorName = Literal["list_package_versions"]
 ListPackagesPaginatorName = Literal["list_packages"]
 ListRepositoriesInDomainPaginatorName = Literal["list_repositories_in_domain"]
 ListRepositoriesPaginatorName = Literal["list_repositories"]
-PackageFormatType = Literal["maven", "npm", "nuget", "pypi"]
+PackageFormatType = Literal["generic", "maven", "npm", "nuget", "pypi"]
 PackageVersionErrorCodeType = Literal[
     "ALREADY_EXISTS",
     "MISMATCHED_REVISION",
     "MISMATCHED_STATUS",
     "NOT_ALLOWED",
     "NOT_FOUND",
     "SKIPPED",
@@ -128,14 +128,15 @@
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
@@ -214,14 +215,15 @@
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
@@ -232,14 +234,15 @@
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
@@ -275,14 +278,15 @@
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
@@ -301,16 +305,19 @@
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
@@ -394,15 +401,17 @@
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/literals.pyi` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -49,15 +49,15 @@
 HashAlgorithmType = Literal["MD5", "SHA-1", "SHA-256", "SHA-512"]
 ListDomainsPaginatorName = Literal["list_domains"]
 ListPackageVersionAssetsPaginatorName = Literal["list_package_version_assets"]
 ListPackageVersionsPaginatorName = Literal["list_package_versions"]
 ListPackagesPaginatorName = Literal["list_packages"]
 ListRepositoriesInDomainPaginatorName = Literal["list_repositories_in_domain"]
 ListRepositoriesPaginatorName = Literal["list_repositories"]
-PackageFormatType = Literal["maven", "npm", "nuget", "pypi"]
+PackageFormatType = Literal["generic", "maven", "npm", "nuget", "pypi"]
 PackageVersionErrorCodeType = Literal[
     "ALREADY_EXISTS",
     "MISMATCHED_REVISION",
     "MISMATCHED_STATUS",
     "NOT_ALLOWED",
     "NOT_FOUND",
     "SKIPPED",
@@ -126,14 +126,15 @@
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
@@ -212,14 +213,15 @@
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
@@ -230,14 +232,15 @@
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
@@ -273,14 +276,15 @@
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
@@ -299,16 +303,19 @@
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
@@ -392,15 +399,17 @@
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/paginator.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -27,15 +27,15 @@
         list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
         list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
         list_repositories_paginator: ListRepositoriesPaginator = client.get_paginator("list_repositories")
         list_repositories_in_domain_paginator: ListRepositoriesInDomainPaginator = client.get_paginator("list_repositories_in_domain")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
@@ -49,59 +49,50 @@
     ListPackageVersionAssetsResultTypeDef,
     ListPackageVersionsResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     PaginatorConfigTypeDef,
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
     "ListDomainsPaginator",
     "ListPackageVersionAssetsPaginator",
     "ListPackageVersionsPaginator",
     "ListPackagesPaginator",
     "ListRepositoriesPaginator",
     "ListRepositoriesInDomainPaginator",
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
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listdomainspaginator)
         """
 
-
 class ListPackageVersionAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersionAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionassetspaginator)
     """
 
     def paginate(
@@ -110,22 +101,21 @@
         domain: str,
         repository: str,
         format: PackageFormatType,
         package: str,
         packageVersion: str,
         domainOwner: str = ...,
         namespace: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackageVersionAssetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersionAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionassetspaginator)
         """
 
-
 class ListPackageVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionspaginator)
     """
 
     def paginate(
@@ -136,22 +126,21 @@
         format: PackageFormatType,
         package: str,
         domainOwner: str = ...,
         namespace: str = ...,
         status: PackageVersionStatusType = ...,
         sortBy: Literal["PUBLISHED_TIME"] = ...,
         originType: PackageVersionOriginTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackageVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionspaginator)
         """
 
-
 class ListPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackagespaginator)
     """
 
     def paginate(
@@ -161,49 +150,47 @@
         repository: str,
         domainOwner: str = ...,
         format: PackageFormatType = ...,
         namespace: str = ...,
         packagePrefix: str = ...,
         publish: AllowPublishType = ...,
         upstream: AllowUpstreamType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackagespaginator)
         """
 
-
 class ListRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriespaginator)
     """
 
     def paginate(
-        self, *, repositoryPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, repositoryPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriespaginator)
         """
 
-
 class ListRepositoriesInDomainPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositoriesInDomain)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriesindomainpaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         domainOwner: str = ...,
         administratorAccount: str = ...,
         repositoryPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesInDomainResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositoriesInDomain.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriesindomainpaginator)
         """
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/paginator.pyi` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,15 +27,15 @@
         list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
         list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
         list_repositories_paginator: ListRepositoriesPaginator = client.get_paginator("list_repositories")
         list_repositories_in_domain_paginator: ListRepositoriesInDomainPaginator = client.get_paginator("list_repositories_in_domain")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
@@ -49,54 +49,55 @@
     ListPackageVersionAssetsResultTypeDef,
     ListPackageVersionsResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     PaginatorConfigTypeDef,
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
     "ListDomainsPaginator",
     "ListPackageVersionAssetsPaginator",
     "ListPackageVersionsPaginator",
     "ListPackagesPaginator",
     "ListRepositoriesPaginator",
     "ListRepositoriesInDomainPaginator",
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
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listdomainspaginator)
         """
 
+
 class ListPackageVersionAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersionAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionassetspaginator)
     """
 
     def paginate(
@@ -105,21 +106,22 @@
         domain: str,
         repository: str,
         format: PackageFormatType,
         package: str,
         packageVersion: str,
         domainOwner: str = ...,
         namespace: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackageVersionAssetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersionAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionassetspaginator)
         """
 
+
 class ListPackageVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionspaginator)
     """
 
     def paginate(
@@ -130,21 +132,22 @@
         format: PackageFormatType,
         package: str,
         domainOwner: str = ...,
         namespace: str = ...,
         status: PackageVersionStatusType = ...,
         sortBy: Literal["PUBLISHED_TIME"] = ...,
         originType: PackageVersionOriginTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackageVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackageVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackageversionspaginator)
         """
 
+
 class ListPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackagespaginator)
     """
 
     def paginate(
@@ -154,47 +157,49 @@
         repository: str,
         domainOwner: str = ...,
         format: PackageFormatType = ...,
         namespace: str = ...,
         packagePrefix: str = ...,
         publish: AllowPublishType = ...,
         upstream: AllowUpstreamType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listpackagespaginator)
         """
 
+
 class ListRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriespaginator)
     """
 
     def paginate(
-        self, *, repositoryPrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, repositoryPrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriespaginator)
         """
 
+
 class ListRepositoriesInDomainPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositoriesInDomain)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriesindomainpaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         domainOwner: str = ...,
         administratorAccount: str = ...,
         repositoryPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoriesInDomainResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact.Paginator.ListRepositoriesInDomain.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/paginators/#listrepositoriesindomainpaginator)
         """
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/type_defs.py` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_codeartifact.type_defs import AssetSummaryTypeDef
 
     data: AssetSummaryTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
     DomainStatusType,
@@ -37,15 +37,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssetSummaryTypeDef",
     "AssociateExternalConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CopyPackageVersionsRequestRequestTypeDef",
     "PackageVersionErrorTypeDef",
     "SuccessfulPackageVersionInfoTypeDef",
     "TagTypeDef",
     "DomainDescriptionTypeDef",
     "UpstreamRepositoryTypeDef",
     "DeleteDomainPermissionsPolicyRequestRequestTypeDef",
@@ -60,43 +59,52 @@
     "DescribePackageVersionRequestRequestTypeDef",
     "DescribeRepositoryRequestRequestTypeDef",
     "DisassociateExternalConnectionRequestRequestTypeDef",
     "DisposePackageVersionsRequestRequestTypeDef",
     "DomainEntryPointTypeDef",
     "DomainSummaryTypeDef",
     "GetAuthorizationTokenRequestRequestTypeDef",
+    "GetAuthorizationTokenResultTypeDef",
     "GetDomainPermissionsPolicyRequestRequestTypeDef",
     "GetPackageVersionAssetRequestRequestTypeDef",
+    "GetPackageVersionAssetResultTypeDef",
     "GetPackageVersionReadmeRequestRequestTypeDef",
+    "GetPackageVersionReadmeResultTypeDef",
     "GetRepositoryEndpointRequestRequestTypeDef",
+    "GetRepositoryEndpointResultTypeDef",
     "GetRepositoryPermissionsPolicyRequestRequestTypeDef",
     "LicenseInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
     "ListPackageVersionAssetsRequestRequestTypeDef",
     "ListPackageVersionDependenciesRequestRequestTypeDef",
     "PackageDependencyTypeDef",
+    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
     "ListPackageVersionsRequestRequestTypeDef",
+    "ListPackagesRequestListPackagesPaginateTypeDef",
     "ListPackagesRequestRequestTypeDef",
+    "ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
     "ListRepositoriesInDomainRequestRequestTypeDef",
     "RepositorySummaryTypeDef",
+    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
     "ListRepositoriesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "PackageOriginRestrictionsTypeDef",
+    "PaginatorConfigTypeDef",
+    "PublishPackageVersionRequestRequestTypeDef",
     "PutDomainPermissionsPolicyRequestRequestTypeDef",
     "PutRepositoryPermissionsPolicyRequestRequestTypeDef",
     "RepositoryExternalConnectionInfoTypeDef",
     "UpstreamRepositoryInfoTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePackageVersionsStatusRequestRequestTypeDef",
-    "GetAuthorizationTokenResultTypeDef",
-    "GetPackageVersionAssetResultTypeDef",
-    "GetPackageVersionReadmeResultTypeDef",
-    "GetRepositoryEndpointResultTypeDef",
     "ListPackageVersionAssetsResultTypeDef",
+    "PublishPackageVersionResultTypeDef",
     "CopyPackageVersionsResultTypeDef",
     "DeletePackageVersionsResultTypeDef",
     "DisposePackageVersionsResultTypeDef",
     "UpdatePackageVersionsStatusResultTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "ListTagsForResourceResultTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -109,20 +117,14 @@
     "DeleteRepositoryPermissionsPolicyResultTypeDef",
     "GetDomainPermissionsPolicyResultTypeDef",
     "GetRepositoryPermissionsPolicyResultTypeDef",
     "PutDomainPermissionsPolicyResultTypeDef",
     "PutRepositoryPermissionsPolicyResultTypeDef",
     "PackageVersionOriginTypeDef",
     "ListDomainsResultTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    "ListPackagesRequestListPackagesPaginateTypeDef",
-    "ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
     "ListPackageVersionDependenciesResultTypeDef",
     "ListRepositoriesInDomainResultTypeDef",
     "ListRepositoriesResultTypeDef",
     "PackageOriginConfigurationTypeDef",
     "PutPackageOriginConfigurationRequestRequestTypeDef",
     "RepositoryDescriptionTypeDef",
     "PackageVersionDescriptionTypeDef",
@@ -183,25 +185,14 @@
 class AssociateExternalConnectionRequestRequestTypeDef(
     _RequiredAssociateExternalConnectionRequestRequestTypeDef,
     _OptionalAssociateExternalConnectionRequestRequestTypeDef,
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
 _RequiredCopyPackageVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredCopyPackageVersionsRequestRequestTypeDef",
     {
         "domain": str,
         "sourceRepository": str,
         "destinationRepository": str,
         "format": PackageFormatType,
@@ -621,14 +612,23 @@
 class GetAuthorizationTokenRequestRequestTypeDef(
     _RequiredGetAuthorizationTokenRequestRequestTypeDef,
     _OptionalGetAuthorizationTokenRequestRequestTypeDef,
 ):
     pass
 
 
+GetAuthorizationTokenResultTypeDef = TypedDict(
+    "GetAuthorizationTokenResultTypeDef",
+    {
+        "authorizationToken": str,
+        "expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetDomainPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalGetDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
@@ -672,14 +672,25 @@
 class GetPackageVersionAssetRequestRequestTypeDef(
     _RequiredGetPackageVersionAssetRequestRequestTypeDef,
     _OptionalGetPackageVersionAssetRequestRequestTypeDef,
 ):
     pass
 
 
+GetPackageVersionAssetResultTypeDef = TypedDict(
+    "GetPackageVersionAssetResultTypeDef",
+    {
+        "asset": StreamingBody,
+        "assetName": str,
+        "packageVersion": str,
+        "packageVersionRevision": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPackageVersionReadmeRequestRequestTypeDef = TypedDict(
     "_RequiredGetPackageVersionReadmeRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -699,14 +710,27 @@
 class GetPackageVersionReadmeRequestRequestTypeDef(
     _RequiredGetPackageVersionReadmeRequestRequestTypeDef,
     _OptionalGetPackageVersionReadmeRequestRequestTypeDef,
 ):
     pass
 
 
+GetPackageVersionReadmeResultTypeDef = TypedDict(
+    "GetPackageVersionReadmeResultTypeDef",
+    {
+        "format": PackageFormatType,
+        "namespace": str,
+        "package": str,
+        "version": str,
+        "versionRevision": str,
+        "readme": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryEndpointRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
     },
@@ -723,14 +747,22 @@
 class GetRepositoryEndpointRequestRequestTypeDef(
     _RequiredGetRepositoryEndpointRequestRequestTypeDef,
     _OptionalGetRepositoryEndpointRequestRequestTypeDef,
 ):
     pass
 
 
+GetRepositoryEndpointResultTypeDef = TypedDict(
+    "GetRepositoryEndpointResultTypeDef",
+    {
+        "repositoryEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
     },
 )
@@ -755,33 +787,59 @@
     {
         "name": str,
         "url": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+        "packageVersion": str,
+    },
+)
+_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef(
+    _RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
+    _OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPackageVersionAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListPackageVersionAssetsRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -842,14 +900,44 @@
         "package": str,
         "dependencyType": str,
         "versionRequirement": str,
     },
     total=False,
 )
 
+_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+    },
+)
+_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "status": PackageVersionStatusType,
+        "sortBy": Literal["PUBLISHED_TIME"],
+        "originType": PackageVersionOriginTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
+    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPackageVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPackageVersionsRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -873,14 +961,43 @@
 class ListPackageVersionsRequestRequestTypeDef(
     _RequiredListPackageVersionsRequestRequestTypeDef,
     _OptionalListPackageVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "_RequiredListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+    },
+)
+_OptionalListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "_OptionalListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "format": PackageFormatType,
+        "namespace": str,
+        "packagePrefix": str,
+        "publish": AllowPublishType,
+        "upstream": AllowUpstreamType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPackagesRequestListPackagesPaginateTypeDef(
+    _RequiredListPackagesRequestListPackagesPaginateTypeDef,
+    _OptionalListPackagesRequestListPackagesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPackagesRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
     },
 )
@@ -902,14 +1019,39 @@
 
 class ListPackagesRequestRequestTypeDef(
     _RequiredListPackagesRequestRequestTypeDef, _OptionalListPackagesRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
+    "_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
+    {
+        "domain": str,
+    },
+)
+_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
+    "_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "administratorAccount": str,
+        "repositoryPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef(
+    _RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
+    _OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRepositoriesInDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListRepositoriesInDomainRequestRequestTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalListRepositoriesInDomainRequestRequestTypeDef = TypedDict(
@@ -937,14 +1079,24 @@
     {
         "name": str,
         "administratorAccount": str,
         "domainName": str,
         "domainOwner": str,
         "arn": str,
         "description": str,
+        "createdTime": datetime,
+    },
+    total=False,
+)
+
+ListRepositoriesRequestListRepositoriesPaginateTypeDef = TypedDict(
+    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
+    {
+        "repositoryPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRepositoriesRequestRequestTypeDef = TypedDict(
     "ListRepositoriesRequestRequestTypeDef",
     {
@@ -966,14 +1118,55 @@
     "PackageOriginRestrictionsTypeDef",
     {
         "publish": AllowPublishType,
         "upstream": AllowUpstreamType,
     },
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
+_RequiredPublishPackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredPublishPackageVersionRequestRequestTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+        "packageVersion": str,
+        "assetContent": Union[str, bytes, IO[Any], StreamingBody],
+        "assetName": str,
+        "assetSHA256": str,
+    },
+)
+_OptionalPublishPackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalPublishPackageVersionRequestRequestTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "unfinished": bool,
+    },
+    total=False,
+)
+
+
+class PublishPackageVersionRequestRequestTypeDef(
+    _RequiredPublishPackageVersionRequestRequestTypeDef,
+    _OptionalPublishPackageVersionRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredPutDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutDomainPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
         "policyDocument": str,
     },
 )
@@ -1033,14 +1226,25 @@
     "UpstreamRepositoryInfoTypeDef",
     {
         "repositoryName": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1071,102 +1275,75 @@
 class UpdatePackageVersionsStatusRequestRequestTypeDef(
     _RequiredUpdatePackageVersionsStatusRequestRequestTypeDef,
     _OptionalUpdatePackageVersionsStatusRequestRequestTypeDef,
 ):
     pass
 
 
-GetAuthorizationTokenResultTypeDef = TypedDict(
-    "GetAuthorizationTokenResultTypeDef",
-    {
-        "authorizationToken": str,
-        "expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPackageVersionAssetResultTypeDef = TypedDict(
-    "GetPackageVersionAssetResultTypeDef",
-    {
-        "asset": StreamingBody,
-        "assetName": str,
-        "packageVersion": str,
-        "packageVersionRevision": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPackageVersionReadmeResultTypeDef = TypedDict(
-    "GetPackageVersionReadmeResultTypeDef",
+ListPackageVersionAssetsResultTypeDef = TypedDict(
+    "ListPackageVersionAssetsResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
-        "readme": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRepositoryEndpointResultTypeDef = TypedDict(
-    "GetRepositoryEndpointResultTypeDef",
-    {
-        "repositoryEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "assets": List[AssetSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPackageVersionAssetsResultTypeDef = TypedDict(
-    "ListPackageVersionAssetsResultTypeDef",
+PublishPackageVersionResultTypeDef = TypedDict(
+    "PublishPackageVersionResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
-        "nextToken": str,
-        "assets": List[AssetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": PackageVersionStatusType,
+        "asset": AssetSummaryTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyPackageVersionsResultTypeDef = TypedDict(
     "CopyPackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageVersionsResultTypeDef = TypedDict(
     "DeletePackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisposePackageVersionsResultTypeDef = TypedDict(
     "DisposePackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageVersionsStatusResultTypeDef = TypedDict(
     "UpdatePackageVersionsStatusResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "domain": str,
@@ -1188,15 +1365,15 @@
     pass
 
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1204,31 +1381,31 @@
     },
 )
 
 CreateDomainResultTypeDef = TypedDict(
     "CreateDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResultTypeDef = TypedDict(
     "DeleteDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResultTypeDef = TypedDict(
     "DescribeDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRepositoryRequestRequestTypeDef",
     {
         "domain": str,
@@ -1277,55 +1454,55 @@
     pass
 
 
 DeleteDomainPermissionsPolicyResultTypeDef = TypedDict(
     "DeleteDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "DeleteRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainPermissionsPolicyResultTypeDef = TypedDict(
     "GetDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "GetRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDomainPermissionsPolicyResultTypeDef = TypedDict(
     "PutDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "PutRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageVersionOriginTypeDef = TypedDict(
     "PackageVersionOriginTypeDef",
     {
         "domainEntryPoint": DomainEntryPointTypeDef,
@@ -1335,176 +1512,47 @@
 )
 
 ListDomainsResultTypeDef = TypedDict(
     "ListDomainsResultTypeDef",
     {
         "domains": List[DomainSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-        "format": PackageFormatType,
-        "package": str,
-        "packageVersion": str,
-    },
-)
-_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "namespace": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef(
-    _RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-    _OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-        "format": PackageFormatType,
-        "package": str,
-    },
-)
-_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "namespace": str,
-        "status": PackageVersionStatusType,
-        "sortBy": Literal["PUBLISHED_TIME"],
-        "originType": PackageVersionOriginTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
-    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
-    "_RequiredListPackagesRequestListPackagesPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-    },
-)
-_OptionalListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
-    "_OptionalListPackagesRequestListPackagesPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "format": PackageFormatType,
-        "namespace": str,
-        "packagePrefix": str,
-        "publish": AllowPublishType,
-        "upstream": AllowUpstreamType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPackagesRequestListPackagesPaginateTypeDef(
-    _RequiredListPackagesRequestListPackagesPaginateTypeDef,
-    _OptionalListPackagesRequestListPackagesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
-    "_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    {
-        "domain": str,
-    },
-)
-_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
-    "_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "administratorAccount": str,
-        "repositoryPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef(
-    _RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-    _OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-):
-    pass
-
-
-ListRepositoriesRequestListRepositoriesPaginateTypeDef = TypedDict(
-    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
-    {
-        "repositoryPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPackageVersionDependenciesResultTypeDef = TypedDict(
     "ListPackageVersionDependenciesResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
         "nextToken": str,
         "dependencies": List[PackageDependencyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesInDomainResultTypeDef = TypedDict(
     "ListRepositoriesInDomainResultTypeDef",
     {
         "repositories": List[RepositorySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesResultTypeDef = TypedDict(
     "ListRepositoriesResultTypeDef",
     {
         "repositories": List[RepositorySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageOriginConfigurationTypeDef = TypedDict(
     "PackageOriginConfigurationTypeDef",
     {
         "restrictions": PackageOriginRestrictionsTypeDef,
@@ -1546,14 +1594,15 @@
         "administratorAccount": str,
         "domainName": str,
         "domainOwner": str,
         "arn": str,
         "description": str,
         "upstreams": List[UpstreamRepositoryInfoTypeDef],
         "externalConnections": List[RepositoryExternalConnectionInfoTypeDef],
+        "createdTime": datetime,
     },
     total=False,
 )
 
 PackageVersionDescriptionTypeDef = TypedDict(
     "PackageVersionDescriptionTypeDef",
     {
@@ -1619,104 +1668,104 @@
     total=False,
 )
 
 PutPackageOriginConfigurationResultTypeDef = TypedDict(
     "PutPackageOriginConfigurationResultTypeDef",
     {
         "originConfiguration": PackageOriginConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateExternalConnectionResultTypeDef = TypedDict(
     "AssociateExternalConnectionResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResultTypeDef = TypedDict(
     "CreateRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResultTypeDef = TypedDict(
     "DeleteRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoryResultTypeDef = TypedDict(
     "DescribeRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateExternalConnectionResultTypeDef = TypedDict(
     "DisassociateExternalConnectionResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRepositoryResultTypeDef = TypedDict(
     "UpdateRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageVersionResultTypeDef = TypedDict(
     "DescribePackageVersionResultTypeDef",
     {
         "packageVersion": PackageVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackageVersionsResultTypeDef = TypedDict(
     "ListPackageVersionsResultTypeDef",
     {
         "defaultDisplayVersion": str,
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "versions": List[PackageVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageResultTypeDef = TypedDict(
     "DescribePackageResultTypeDef",
     {
         "package": PackageDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResultTypeDef = TypedDict(
     "DeletePackageResultTypeDef",
     {
         "deletedPackage": PackageSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesResultTypeDef = TypedDict(
     "ListPackagesResultTypeDef",
     {
         "packages": List[PackageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact/type_defs.pyi` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_codeartifact.type_defs import AssetSummaryTypeDef
 
     data: AssetSummaryTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AllowPublishType,
     AllowUpstreamType,
     DomainStatusType,
@@ -36,15 +36,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssetSummaryTypeDef",
     "AssociateExternalConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CopyPackageVersionsRequestRequestTypeDef",
     "PackageVersionErrorTypeDef",
     "SuccessfulPackageVersionInfoTypeDef",
     "TagTypeDef",
     "DomainDescriptionTypeDef",
     "UpstreamRepositoryTypeDef",
     "DeleteDomainPermissionsPolicyRequestRequestTypeDef",
@@ -59,43 +58,52 @@
     "DescribePackageVersionRequestRequestTypeDef",
     "DescribeRepositoryRequestRequestTypeDef",
     "DisassociateExternalConnectionRequestRequestTypeDef",
     "DisposePackageVersionsRequestRequestTypeDef",
     "DomainEntryPointTypeDef",
     "DomainSummaryTypeDef",
     "GetAuthorizationTokenRequestRequestTypeDef",
+    "GetAuthorizationTokenResultTypeDef",
     "GetDomainPermissionsPolicyRequestRequestTypeDef",
     "GetPackageVersionAssetRequestRequestTypeDef",
+    "GetPackageVersionAssetResultTypeDef",
     "GetPackageVersionReadmeRequestRequestTypeDef",
+    "GetPackageVersionReadmeResultTypeDef",
     "GetRepositoryEndpointRequestRequestTypeDef",
+    "GetRepositoryEndpointResultTypeDef",
     "GetRepositoryPermissionsPolicyRequestRequestTypeDef",
     "LicenseInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
     "ListPackageVersionAssetsRequestRequestTypeDef",
     "ListPackageVersionDependenciesRequestRequestTypeDef",
     "PackageDependencyTypeDef",
+    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
     "ListPackageVersionsRequestRequestTypeDef",
+    "ListPackagesRequestListPackagesPaginateTypeDef",
     "ListPackagesRequestRequestTypeDef",
+    "ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
     "ListRepositoriesInDomainRequestRequestTypeDef",
     "RepositorySummaryTypeDef",
+    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
     "ListRepositoriesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "PackageOriginRestrictionsTypeDef",
+    "PaginatorConfigTypeDef",
+    "PublishPackageVersionRequestRequestTypeDef",
     "PutDomainPermissionsPolicyRequestRequestTypeDef",
     "PutRepositoryPermissionsPolicyRequestRequestTypeDef",
     "RepositoryExternalConnectionInfoTypeDef",
     "UpstreamRepositoryInfoTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePackageVersionsStatusRequestRequestTypeDef",
-    "GetAuthorizationTokenResultTypeDef",
-    "GetPackageVersionAssetResultTypeDef",
-    "GetPackageVersionReadmeResultTypeDef",
-    "GetRepositoryEndpointResultTypeDef",
     "ListPackageVersionAssetsResultTypeDef",
+    "PublishPackageVersionResultTypeDef",
     "CopyPackageVersionsResultTypeDef",
     "DeletePackageVersionsResultTypeDef",
     "DisposePackageVersionsResultTypeDef",
     "UpdatePackageVersionsStatusResultTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "ListTagsForResourceResultTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -108,20 +116,14 @@
     "DeleteRepositoryPermissionsPolicyResultTypeDef",
     "GetDomainPermissionsPolicyResultTypeDef",
     "GetRepositoryPermissionsPolicyResultTypeDef",
     "PutDomainPermissionsPolicyResultTypeDef",
     "PutRepositoryPermissionsPolicyResultTypeDef",
     "PackageVersionOriginTypeDef",
     "ListDomainsResultTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    "ListPackagesRequestListPackagesPaginateTypeDef",
-    "ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
     "ListPackageVersionDependenciesResultTypeDef",
     "ListRepositoriesInDomainResultTypeDef",
     "ListRepositoriesResultTypeDef",
     "PackageOriginConfigurationTypeDef",
     "PutPackageOriginConfigurationRequestRequestTypeDef",
     "RepositoryDescriptionTypeDef",
     "PackageVersionDescriptionTypeDef",
@@ -178,25 +180,14 @@
 
 class AssociateExternalConnectionRequestRequestTypeDef(
     _RequiredAssociateExternalConnectionRequestRequestTypeDef,
     _OptionalAssociateExternalConnectionRequestRequestTypeDef,
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
 _RequiredCopyPackageVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredCopyPackageVersionsRequestRequestTypeDef",
     {
         "domain": str,
         "sourceRepository": str,
         "destinationRepository": str,
         "format": PackageFormatType,
@@ -588,14 +579,23 @@
 
 class GetAuthorizationTokenRequestRequestTypeDef(
     _RequiredGetAuthorizationTokenRequestRequestTypeDef,
     _OptionalGetAuthorizationTokenRequestRequestTypeDef,
 ):
     pass
 
+GetAuthorizationTokenResultTypeDef = TypedDict(
+    "GetAuthorizationTokenResultTypeDef",
+    {
+        "authorizationToken": str,
+        "expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetDomainPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalGetDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
@@ -635,14 +635,25 @@
 
 class GetPackageVersionAssetRequestRequestTypeDef(
     _RequiredGetPackageVersionAssetRequestRequestTypeDef,
     _OptionalGetPackageVersionAssetRequestRequestTypeDef,
 ):
     pass
 
+GetPackageVersionAssetResultTypeDef = TypedDict(
+    "GetPackageVersionAssetResultTypeDef",
+    {
+        "asset": StreamingBody,
+        "assetName": str,
+        "packageVersion": str,
+        "packageVersionRevision": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPackageVersionReadmeRequestRequestTypeDef = TypedDict(
     "_RequiredGetPackageVersionReadmeRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -660,14 +671,27 @@
 
 class GetPackageVersionReadmeRequestRequestTypeDef(
     _RequiredGetPackageVersionReadmeRequestRequestTypeDef,
     _OptionalGetPackageVersionReadmeRequestRequestTypeDef,
 ):
     pass
 
+GetPackageVersionReadmeResultTypeDef = TypedDict(
+    "GetPackageVersionReadmeResultTypeDef",
+    {
+        "format": PackageFormatType,
+        "namespace": str,
+        "package": str,
+        "version": str,
+        "versionRevision": str,
+        "readme": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryEndpointRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
     },
@@ -682,14 +706,22 @@
 
 class GetRepositoryEndpointRequestRequestTypeDef(
     _RequiredGetRepositoryEndpointRequestRequestTypeDef,
     _OptionalGetRepositoryEndpointRequestRequestTypeDef,
 ):
     pass
 
+GetRepositoryEndpointResultTypeDef = TypedDict(
+    "GetRepositoryEndpointResultTypeDef",
+    {
+        "repositoryEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
     },
 )
@@ -712,33 +744,57 @@
     {
         "name": str,
         "url": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+        "packageVersion": str,
+    },
+)
+_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef(
+    _RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
+    _OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPackageVersionAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListPackageVersionAssetsRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -795,14 +851,42 @@
         "package": str,
         "dependencyType": str,
         "versionRequirement": str,
     },
     total=False,
 )
 
+_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+    },
+)
+_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "status": PackageVersionStatusType,
+        "sortBy": Literal["PUBLISHED_TIME"],
+        "originType": PackageVersionOriginTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
+    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPackageVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPackageVersionsRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
         "format": PackageFormatType,
         "package": str,
@@ -824,14 +908,41 @@
 
 class ListPackageVersionsRequestRequestTypeDef(
     _RequiredListPackageVersionsRequestRequestTypeDef,
     _OptionalListPackageVersionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "_RequiredListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+    },
+)
+_OptionalListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "_OptionalListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "format": PackageFormatType,
+        "namespace": str,
+        "packagePrefix": str,
+        "publish": AllowPublishType,
+        "upstream": AllowUpstreamType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPackagesRequestListPackagesPaginateTypeDef(
+    _RequiredListPackagesRequestListPackagesPaginateTypeDef,
+    _OptionalListPackagesRequestListPackagesPaginateTypeDef,
+):
+    pass
+
 _RequiredListPackagesRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesRequestRequestTypeDef",
     {
         "domain": str,
         "repository": str,
     },
 )
@@ -851,14 +962,37 @@
 )
 
 class ListPackagesRequestRequestTypeDef(
     _RequiredListPackagesRequestRequestTypeDef, _OptionalListPackagesRequestRequestTypeDef
 ):
     pass
 
+_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
+    "_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
+    {
+        "domain": str,
+    },
+)
+_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
+    "_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
+    {
+        "domainOwner": str,
+        "administratorAccount": str,
+        "repositoryPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef(
+    _RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
+    _OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
+):
+    pass
+
 _RequiredListRepositoriesInDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListRepositoriesInDomainRequestRequestTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalListRepositoriesInDomainRequestRequestTypeDef = TypedDict(
@@ -884,14 +1018,24 @@
     {
         "name": str,
         "administratorAccount": str,
         "domainName": str,
         "domainOwner": str,
         "arn": str,
         "description": str,
+        "createdTime": datetime,
+    },
+    total=False,
+)
+
+ListRepositoriesRequestListRepositoriesPaginateTypeDef = TypedDict(
+    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
+    {
+        "repositoryPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRepositoriesRequestRequestTypeDef = TypedDict(
     "ListRepositoriesRequestRequestTypeDef",
     {
@@ -913,14 +1057,53 @@
     "PackageOriginRestrictionsTypeDef",
     {
         "publish": AllowPublishType,
         "upstream": AllowUpstreamType,
     },
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
+_RequiredPublishPackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredPublishPackageVersionRequestRequestTypeDef",
+    {
+        "domain": str,
+        "repository": str,
+        "format": PackageFormatType,
+        "package": str,
+        "packageVersion": str,
+        "assetContent": Union[str, bytes, IO[Any], StreamingBody],
+        "assetName": str,
+        "assetSHA256": str,
+    },
+)
+_OptionalPublishPackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalPublishPackageVersionRequestRequestTypeDef",
+    {
+        "domainOwner": str,
+        "namespace": str,
+        "unfinished": bool,
+    },
+    total=False,
+)
+
+class PublishPackageVersionRequestRequestTypeDef(
+    _RequiredPublishPackageVersionRequestRequestTypeDef,
+    _OptionalPublishPackageVersionRequestRequestTypeDef,
+):
+    pass
+
 _RequiredPutDomainPermissionsPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutDomainPermissionsPolicyRequestRequestTypeDef",
     {
         "domain": str,
         "policyDocument": str,
     },
 )
@@ -976,14 +1159,25 @@
     "UpstreamRepositoryInfoTypeDef",
     {
         "repositoryName": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1012,102 +1206,75 @@
 
 class UpdatePackageVersionsStatusRequestRequestTypeDef(
     _RequiredUpdatePackageVersionsStatusRequestRequestTypeDef,
     _OptionalUpdatePackageVersionsStatusRequestRequestTypeDef,
 ):
     pass
 
-GetAuthorizationTokenResultTypeDef = TypedDict(
-    "GetAuthorizationTokenResultTypeDef",
-    {
-        "authorizationToken": str,
-        "expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPackageVersionAssetResultTypeDef = TypedDict(
-    "GetPackageVersionAssetResultTypeDef",
-    {
-        "asset": StreamingBody,
-        "assetName": str,
-        "packageVersion": str,
-        "packageVersionRevision": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPackageVersionReadmeResultTypeDef = TypedDict(
-    "GetPackageVersionReadmeResultTypeDef",
+ListPackageVersionAssetsResultTypeDef = TypedDict(
+    "ListPackageVersionAssetsResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
-        "readme": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRepositoryEndpointResultTypeDef = TypedDict(
-    "GetRepositoryEndpointResultTypeDef",
-    {
-        "repositoryEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "assets": List[AssetSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPackageVersionAssetsResultTypeDef = TypedDict(
-    "ListPackageVersionAssetsResultTypeDef",
+PublishPackageVersionResultTypeDef = TypedDict(
+    "PublishPackageVersionResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
-        "nextToken": str,
-        "assets": List[AssetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": PackageVersionStatusType,
+        "asset": AssetSummaryTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyPackageVersionsResultTypeDef = TypedDict(
     "CopyPackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageVersionsResultTypeDef = TypedDict(
     "DeletePackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisposePackageVersionsResultTypeDef = TypedDict(
     "DisposePackageVersionsResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageVersionsStatusResultTypeDef = TypedDict(
     "UpdatePackageVersionsStatusResultTypeDef",
     {
         "successfulVersions": Dict[str, SuccessfulPackageVersionInfoTypeDef],
         "failedVersions": Dict[str, PackageVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "domain": str,
@@ -1127,15 +1294,15 @@
 ):
     pass
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1143,31 +1310,31 @@
     },
 )
 
 CreateDomainResultTypeDef = TypedDict(
     "CreateDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResultTypeDef = TypedDict(
     "DeleteDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResultTypeDef = TypedDict(
     "DescribeDomainResultTypeDef",
     {
         "domain": DomainDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRepositoryRequestRequestTypeDef",
     {
         "domain": str,
@@ -1212,55 +1379,55 @@
 ):
     pass
 
 DeleteDomainPermissionsPolicyResultTypeDef = TypedDict(
     "DeleteDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "DeleteRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainPermissionsPolicyResultTypeDef = TypedDict(
     "GetDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "GetRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDomainPermissionsPolicyResultTypeDef = TypedDict(
     "PutDomainPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRepositoryPermissionsPolicyResultTypeDef = TypedDict(
     "PutRepositoryPermissionsPolicyResultTypeDef",
     {
         "policy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageVersionOriginTypeDef = TypedDict(
     "PackageVersionOriginTypeDef",
     {
         "domainEntryPoint": DomainEntryPointTypeDef,
@@ -1270,168 +1437,47 @@
 )
 
 ListDomainsResultTypeDef = TypedDict(
     "ListDomainsResultTypeDef",
     {
         "domains": List[DomainSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-        "format": PackageFormatType,
-        "package": str,
-        "packageVersion": str,
-    },
-)
-_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "namespace": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef(
-    _RequiredListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-    _OptionalListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-        "format": PackageFormatType,
-        "package": str,
-    },
-)
-_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "namespace": str,
-        "status": PackageVersionStatusType,
-        "sortBy": Literal["PUBLISHED_TIME"],
-        "originType": PackageVersionOriginTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
-    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
-    "_RequiredListPackagesRequestListPackagesPaginateTypeDef",
-    {
-        "domain": str,
-        "repository": str,
-    },
-)
-_OptionalListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
-    "_OptionalListPackagesRequestListPackagesPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "format": PackageFormatType,
-        "namespace": str,
-        "packagePrefix": str,
-        "publish": AllowPublishType,
-        "upstream": AllowUpstreamType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPackagesRequestListPackagesPaginateTypeDef(
-    _RequiredListPackagesRequestListPackagesPaginateTypeDef,
-    _OptionalListPackagesRequestListPackagesPaginateTypeDef,
-):
-    pass
-
-_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
-    "_RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    {
-        "domain": str,
-    },
-)
-_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef = TypedDict(
-    "_OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef",
-    {
-        "domainOwner": str,
-        "administratorAccount": str,
-        "repositoryPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef(
-    _RequiredListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-    _OptionalListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-):
-    pass
-
-ListRepositoriesRequestListRepositoriesPaginateTypeDef = TypedDict(
-    "ListRepositoriesRequestListRepositoriesPaginateTypeDef",
-    {
-        "repositoryPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListPackageVersionDependenciesResultTypeDef = TypedDict(
     "ListPackageVersionDependenciesResultTypeDef",
     {
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "version": str,
         "versionRevision": str,
         "nextToken": str,
         "dependencies": List[PackageDependencyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesInDomainResultTypeDef = TypedDict(
     "ListRepositoriesInDomainResultTypeDef",
     {
         "repositories": List[RepositorySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRepositoriesResultTypeDef = TypedDict(
     "ListRepositoriesResultTypeDef",
     {
         "repositories": List[RepositorySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageOriginConfigurationTypeDef = TypedDict(
     "PackageOriginConfigurationTypeDef",
     {
         "restrictions": PackageOriginRestrictionsTypeDef,
@@ -1471,14 +1517,15 @@
         "administratorAccount": str,
         "domainName": str,
         "domainOwner": str,
         "arn": str,
         "description": str,
         "upstreams": List[UpstreamRepositoryInfoTypeDef],
         "externalConnections": List[RepositoryExternalConnectionInfoTypeDef],
+        "createdTime": datetime,
     },
     total=False,
 )
 
 PackageVersionDescriptionTypeDef = TypedDict(
     "PackageVersionDescriptionTypeDef",
     {
@@ -1542,104 +1589,104 @@
     total=False,
 )
 
 PutPackageOriginConfigurationResultTypeDef = TypedDict(
     "PutPackageOriginConfigurationResultTypeDef",
     {
         "originConfiguration": PackageOriginConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateExternalConnectionResultTypeDef = TypedDict(
     "AssociateExternalConnectionResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResultTypeDef = TypedDict(
     "CreateRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResultTypeDef = TypedDict(
     "DeleteRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoryResultTypeDef = TypedDict(
     "DescribeRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateExternalConnectionResultTypeDef = TypedDict(
     "DisassociateExternalConnectionResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRepositoryResultTypeDef = TypedDict(
     "UpdateRepositoryResultTypeDef",
     {
         "repository": RepositoryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageVersionResultTypeDef = TypedDict(
     "DescribePackageVersionResultTypeDef",
     {
         "packageVersion": PackageVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackageVersionsResultTypeDef = TypedDict(
     "ListPackageVersionsResultTypeDef",
     {
         "defaultDisplayVersion": str,
         "format": PackageFormatType,
         "namespace": str,
         "package": str,
         "versions": List[PackageVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageResultTypeDef = TypedDict(
     "DescribePackageResultTypeDef",
     {
         "package": PackageDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResultTypeDef = TypedDict(
     "DeletePackageResultTypeDef",
     {
         "deletedPackage": PackageSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesResultTypeDef = TypedDict(
     "ListPackagesResultTypeDef",
     {
         "packages": List[PackageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/PKG-INFO` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeartifact
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeArtifact 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeArtifact 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeartifact"></a>
 
 # types-aiobotocore-codeartifact
 
 [![PyPI - types-aiobotocore-codeartifact](https://img.shields.io/pypi/v/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeartifact.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeartifact)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeartifact?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeartifact)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeArtifact 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
+[aiobotocore.CodeArtifact 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeartifact.html#CodeArtifact)
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
 [types-aiobotocore-codeartifact docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeartifact/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,15 +351,14 @@
 `types_aiobotocore_codeartifact.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeartifact.type_defs import (
     AssetSummaryTypeDef,
     AssociateExternalConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CopyPackageVersionsRequestRequestTypeDef,
     PackageVersionErrorTypeDef,
     SuccessfulPackageVersionInfoTypeDef,
     TagTypeDef,
     DomainDescriptionTypeDef,
     UpstreamRepositoryTypeDef,
     DeleteDomainPermissionsPolicyRequestRequestTypeDef,
@@ -374,43 +373,52 @@
     DescribePackageVersionRequestRequestTypeDef,
     DescribeRepositoryRequestRequestTypeDef,
     DisassociateExternalConnectionRequestRequestTypeDef,
     DisposePackageVersionsRequestRequestTypeDef,
     DomainEntryPointTypeDef,
     DomainSummaryTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
+    GetAuthorizationTokenResultTypeDef,
     GetDomainPermissionsPolicyRequestRequestTypeDef,
     GetPackageVersionAssetRequestRequestTypeDef,
+    GetPackageVersionAssetResultTypeDef,
     GetPackageVersionReadmeRequestRequestTypeDef,
+    GetPackageVersionReadmeResultTypeDef,
     GetRepositoryEndpointRequestRequestTypeDef,
+    GetRepositoryEndpointResultTypeDef,
     GetRepositoryPermissionsPolicyRequestRequestTypeDef,
     LicenseInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
     ListPackageVersionAssetsRequestRequestTypeDef,
     ListPackageVersionDependenciesRequestRequestTypeDef,
     PackageDependencyTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
     ListPackageVersionsRequestRequestTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
     ListPackagesRequestRequestTypeDef,
+    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
     ListRepositoriesInDomainRequestRequestTypeDef,
     RepositorySummaryTypeDef,
+    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListRepositoriesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PackageOriginRestrictionsTypeDef,
+    PaginatorConfigTypeDef,
+    PublishPackageVersionRequestRequestTypeDef,
     PutDomainPermissionsPolicyRequestRequestTypeDef,
     PutRepositoryPermissionsPolicyRequestRequestTypeDef,
     RepositoryExternalConnectionInfoTypeDef,
     UpstreamRepositoryInfoTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePackageVersionsStatusRequestRequestTypeDef,
-    GetAuthorizationTokenResultTypeDef,
-    GetPackageVersionAssetResultTypeDef,
-    GetPackageVersionReadmeResultTypeDef,
-    GetRepositoryEndpointResultTypeDef,
     ListPackageVersionAssetsResultTypeDef,
+    PublishPackageVersionResultTypeDef,
     CopyPackageVersionsResultTypeDef,
     DeletePackageVersionsResultTypeDef,
     DisposePackageVersionsResultTypeDef,
     UpdatePackageVersionsStatusResultTypeDef,
     CreateDomainRequestRequestTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -423,20 +431,14 @@
     DeleteRepositoryPermissionsPolicyResultTypeDef,
     GetDomainPermissionsPolicyResultTypeDef,
     GetRepositoryPermissionsPolicyResultTypeDef,
     PutDomainPermissionsPolicyResultTypeDef,
     PutRepositoryPermissionsPolicyResultTypeDef,
     PackageVersionOriginTypeDef,
     ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListPackageVersionAssetsRequestListPackageVersionAssetsPaginateTypeDef,
-    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
-    ListPackagesRequestListPackagesPaginateTypeDef,
-    ListRepositoriesInDomainRequestListRepositoriesInDomainPaginateTypeDef,
-    ListRepositoriesRequestListRepositoriesPaginateTypeDef,
     ListPackageVersionDependenciesResultTypeDef,
     ListRepositoriesInDomainResultTypeDef,
     ListRepositoriesResultTypeDef,
     PackageOriginConfigurationTypeDef,
     PutPackageOriginConfigurationRequestRequestTypeDef,
     RepositoryDescriptionTypeDef,
     PackageVersionDescriptionTypeDef,
@@ -465,43 +467,43 @@
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

### Comparing `types-aiobotocore-codeartifact-2.5.0.post1/types_aiobotocore_codeartifact.egg-info/SOURCES.txt` & `types-aiobotocore-codeartifact-2.5.1/types_aiobotocore_codeartifact.egg-info/SOURCES.txt`

 * *Files identical despite different names*

