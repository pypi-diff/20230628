# Comparing `tmp/types-aiobotocore-workspaces-web-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-workspaces-web-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-workspaces-web-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-workspaces-web-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-workspaces-web-2.5.0.post1.tar` & `types-aiobotocore-workspaces-web-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.687724 types-aiobotocore-workspaces-web-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17024 2023-03-11 12:27:30.683724 types-aiobotocore-workspaces-web-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15426 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.687724 types-aiobotocore-workspaces-web-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.683724 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      492 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35960 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35901 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8133 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8131 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    36127 2023-03-11 12:25:47.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    36084 2023-03-11 12:25:47.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:46.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.683724 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17024 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:30.000000 types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.970233 types-aiobotocore-workspaces-web-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17667 2023-06-28 01:44:20.966233 types-aiobotocore-workspaces-web-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16075 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.970233 types-aiobotocore-workspaces-web-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.966233 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/
+-rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40444 2023-06-28 01:42:43.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40378 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8342 2023-06-28 01:42:43.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8340 2023-06-28 01:42:43.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    41413 2023-06-28 01:42:43.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41362 2023-06-28 01:42:43.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:42.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.966233 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17667 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:20.000000 types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/LICENSE` & `types-aiobotocore-workspaces-web-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/PKG-INFO` & `types-aiobotocore-workspaces-web-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workspaces-web
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkSpacesWeb 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkSpacesWeb 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workspaces-web"></a>
 
 # types-aiobotocore-workspaces-web
 
 [![PyPI - types-aiobotocore-workspaces-web](https://img.shields.io/pypi/v/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workspaces-web?color=blue)](https://pypistats.org/packages/types-aiobotocore-workspaces-web)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkSpacesWeb 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
+[aiobotocore.WorkSpacesWeb 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
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
 [types-aiobotocore-workspaces-web docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,162 +296,177 @@
 
 `types_aiobotocore_workspaces_web.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workspaces_web.type_defs import (
     AssociateBrowserSettingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateBrowserSettingsResponseTypeDef,
+    AssociateIpAccessSettingsRequestRequestTypeDef,
+    AssociateIpAccessSettingsResponseTypeDef,
     AssociateNetworkSettingsRequestRequestTypeDef,
+    AssociateNetworkSettingsResponseTypeDef,
     AssociateTrustStoreRequestRequestTypeDef,
+    AssociateTrustStoreResponseTypeDef,
     AssociateUserAccessLoggingSettingsRequestRequestTypeDef,
+    AssociateUserAccessLoggingSettingsResponseTypeDef,
     AssociateUserSettingsRequestRequestTypeDef,
+    AssociateUserSettingsResponseTypeDef,
     BrowserSettingsSummaryTypeDef,
     BrowserSettingsTypeDef,
     CertificateSummaryTypeDef,
     CertificateTypeDef,
     TagTypeDef,
+    CreateBrowserSettingsResponseTypeDef,
     CreateIdentityProviderRequestRequestTypeDef,
+    CreateIdentityProviderResponseTypeDef,
+    IpRuleTypeDef,
+    CreateIpAccessSettingsResponseTypeDef,
+    CreateNetworkSettingsResponseTypeDef,
+    CreatePortalResponseTypeDef,
+    CreateTrustStoreResponseTypeDef,
+    CreateUserAccessLoggingSettingsResponseTypeDef,
+    CreateUserSettingsResponseTypeDef,
     DeleteBrowserSettingsRequestRequestTypeDef,
     DeleteIdentityProviderRequestRequestTypeDef,
+    DeleteIpAccessSettingsRequestRequestTypeDef,
     DeleteNetworkSettingsRequestRequestTypeDef,
     DeletePortalRequestRequestTypeDef,
     DeleteTrustStoreRequestRequestTypeDef,
     DeleteUserAccessLoggingSettingsRequestRequestTypeDef,
     DeleteUserSettingsRequestRequestTypeDef,
     DisassociateBrowserSettingsRequestRequestTypeDef,
+    DisassociateIpAccessSettingsRequestRequestTypeDef,
     DisassociateNetworkSettingsRequestRequestTypeDef,
     DisassociateTrustStoreRequestRequestTypeDef,
     DisassociateUserAccessLoggingSettingsRequestRequestTypeDef,
     DisassociateUserSettingsRequestRequestTypeDef,
     GetBrowserSettingsRequestRequestTypeDef,
     GetIdentityProviderRequestRequestTypeDef,
     IdentityProviderTypeDef,
+    GetIpAccessSettingsRequestRequestTypeDef,
     GetNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsTypeDef,
     GetPortalRequestRequestTypeDef,
     PortalTypeDef,
     GetPortalServiceProviderMetadataRequestRequestTypeDef,
+    GetPortalServiceProviderMetadataResponseTypeDef,
     GetTrustStoreCertificateRequestRequestTypeDef,
     GetTrustStoreRequestRequestTypeDef,
     TrustStoreTypeDef,
     GetUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsTypeDef,
     GetUserSettingsRequestRequestTypeDef,
     UserSettingsTypeDef,
     IdentityProviderSummaryTypeDef,
+    IpAccessSettingsSummaryTypeDef,
     ListBrowserSettingsRequestRequestTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    ListIpAccessSettingsRequestRequestTypeDef,
     ListNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsSummaryTypeDef,
     ListPortalsRequestRequestTypeDef,
     PortalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTrustStoreCertificatesRequestRequestTypeDef,
     ListTrustStoresRequestRequestTypeDef,
     TrustStoreSummaryTypeDef,
     ListUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsSummaryTypeDef,
     ListUserSettingsRequestRequestTypeDef,
     UserSettingsSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBrowserSettingsRequestRequestTypeDef,
     UpdateIdentityProviderRequestRequestTypeDef,
     UpdateNetworkSettingsRequestRequestTypeDef,
     UpdatePortalRequestRequestTypeDef,
     UpdateTrustStoreRequestRequestTypeDef,
+    UpdateTrustStoreResponseTypeDef,
     UpdateUserAccessLoggingSettingsRequestRequestTypeDef,
     UpdateUserSettingsRequestRequestTypeDef,
-    AssociateBrowserSettingsResponseTypeDef,
-    AssociateNetworkSettingsResponseTypeDef,
-    AssociateTrustStoreResponseTypeDef,
-    AssociateUserAccessLoggingSettingsResponseTypeDef,
-    AssociateUserSettingsResponseTypeDef,
-    CreateBrowserSettingsResponseTypeDef,
-    CreateIdentityProviderResponseTypeDef,
-    CreateNetworkSettingsResponseTypeDef,
-    CreatePortalResponseTypeDef,
-    CreateTrustStoreResponseTypeDef,
-    CreateUserAccessLoggingSettingsResponseTypeDef,
-    CreateUserSettingsResponseTypeDef,
-    GetPortalServiceProviderMetadataResponseTypeDef,
-    UpdateTrustStoreResponseTypeDef,
     ListBrowserSettingsResponseTypeDef,
     GetBrowserSettingsResponseTypeDef,
     UpdateBrowserSettingsResponseTypeDef,
     ListTrustStoreCertificatesResponseTypeDef,
     GetTrustStoreCertificateResponseTypeDef,
     CreateBrowserSettingsRequestRequestTypeDef,
     CreateNetworkSettingsRequestRequestTypeDef,
     CreatePortalRequestRequestTypeDef,
     CreateTrustStoreRequestRequestTypeDef,
     CreateUserAccessLoggingSettingsRequestRequestTypeDef,
     CreateUserSettingsRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateIpAccessSettingsRequestRequestTypeDef,
+    IpAccessSettingsTypeDef,
+    UpdateIpAccessSettingsRequestRequestTypeDef,
     GetIdentityProviderResponseTypeDef,
     UpdateIdentityProviderResponseTypeDef,
     GetNetworkSettingsResponseTypeDef,
     UpdateNetworkSettingsResponseTypeDef,
     GetPortalResponseTypeDef,
     UpdatePortalResponseTypeDef,
     GetTrustStoreResponseTypeDef,
     GetUserAccessLoggingSettingsResponseTypeDef,
     UpdateUserAccessLoggingSettingsResponseTypeDef,
     GetUserSettingsResponseTypeDef,
     UpdateUserSettingsResponseTypeDef,
     ListIdentityProvidersResponseTypeDef,
+    ListIpAccessSettingsResponseTypeDef,
     ListNetworkSettingsResponseTypeDef,
     ListPortalsResponseTypeDef,
     ListTrustStoresResponseTypeDef,
     ListUserAccessLoggingSettingsResponseTypeDef,
     ListUserSettingsResponseTypeDef,
+    GetIpAccessSettingsResponseTypeDef,
+    UpdateIpAccessSettingsResponseTypeDef,
 )
 
 
 def get_structure() -> AssociateBrowserSettingsRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/README.md` & `types-aiobotocore-workspaces-web-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-workspaces-web"></a>
 
 # types-aiobotocore-workspaces-web
 
 [![PyPI - types-aiobotocore-workspaces-web](https://img.shields.io/pypi/v/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workspaces-web?color=blue)](https://pypistats.org/packages/types-aiobotocore-workspaces-web)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkSpacesWeb 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
+[aiobotocore.WorkSpacesWeb 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
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
 [types-aiobotocore-workspaces-web docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/).
 
 See how it helps to find and fix potential bugs:
 
@@ -263,162 +263,177 @@
 
 `types_aiobotocore_workspaces_web.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workspaces_web.type_defs import (
     AssociateBrowserSettingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateBrowserSettingsResponseTypeDef,
+    AssociateIpAccessSettingsRequestRequestTypeDef,
+    AssociateIpAccessSettingsResponseTypeDef,
     AssociateNetworkSettingsRequestRequestTypeDef,
+    AssociateNetworkSettingsResponseTypeDef,
     AssociateTrustStoreRequestRequestTypeDef,
+    AssociateTrustStoreResponseTypeDef,
     AssociateUserAccessLoggingSettingsRequestRequestTypeDef,
+    AssociateUserAccessLoggingSettingsResponseTypeDef,
     AssociateUserSettingsRequestRequestTypeDef,
+    AssociateUserSettingsResponseTypeDef,
     BrowserSettingsSummaryTypeDef,
     BrowserSettingsTypeDef,
     CertificateSummaryTypeDef,
     CertificateTypeDef,
     TagTypeDef,
+    CreateBrowserSettingsResponseTypeDef,
     CreateIdentityProviderRequestRequestTypeDef,
+    CreateIdentityProviderResponseTypeDef,
+    IpRuleTypeDef,
+    CreateIpAccessSettingsResponseTypeDef,
+    CreateNetworkSettingsResponseTypeDef,
+    CreatePortalResponseTypeDef,
+    CreateTrustStoreResponseTypeDef,
+    CreateUserAccessLoggingSettingsResponseTypeDef,
+    CreateUserSettingsResponseTypeDef,
     DeleteBrowserSettingsRequestRequestTypeDef,
     DeleteIdentityProviderRequestRequestTypeDef,
+    DeleteIpAccessSettingsRequestRequestTypeDef,
     DeleteNetworkSettingsRequestRequestTypeDef,
     DeletePortalRequestRequestTypeDef,
     DeleteTrustStoreRequestRequestTypeDef,
     DeleteUserAccessLoggingSettingsRequestRequestTypeDef,
     DeleteUserSettingsRequestRequestTypeDef,
     DisassociateBrowserSettingsRequestRequestTypeDef,
+    DisassociateIpAccessSettingsRequestRequestTypeDef,
     DisassociateNetworkSettingsRequestRequestTypeDef,
     DisassociateTrustStoreRequestRequestTypeDef,
     DisassociateUserAccessLoggingSettingsRequestRequestTypeDef,
     DisassociateUserSettingsRequestRequestTypeDef,
     GetBrowserSettingsRequestRequestTypeDef,
     GetIdentityProviderRequestRequestTypeDef,
     IdentityProviderTypeDef,
+    GetIpAccessSettingsRequestRequestTypeDef,
     GetNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsTypeDef,
     GetPortalRequestRequestTypeDef,
     PortalTypeDef,
     GetPortalServiceProviderMetadataRequestRequestTypeDef,
+    GetPortalServiceProviderMetadataResponseTypeDef,
     GetTrustStoreCertificateRequestRequestTypeDef,
     GetTrustStoreRequestRequestTypeDef,
     TrustStoreTypeDef,
     GetUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsTypeDef,
     GetUserSettingsRequestRequestTypeDef,
     UserSettingsTypeDef,
     IdentityProviderSummaryTypeDef,
+    IpAccessSettingsSummaryTypeDef,
     ListBrowserSettingsRequestRequestTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    ListIpAccessSettingsRequestRequestTypeDef,
     ListNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsSummaryTypeDef,
     ListPortalsRequestRequestTypeDef,
     PortalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTrustStoreCertificatesRequestRequestTypeDef,
     ListTrustStoresRequestRequestTypeDef,
     TrustStoreSummaryTypeDef,
     ListUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsSummaryTypeDef,
     ListUserSettingsRequestRequestTypeDef,
     UserSettingsSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBrowserSettingsRequestRequestTypeDef,
     UpdateIdentityProviderRequestRequestTypeDef,
     UpdateNetworkSettingsRequestRequestTypeDef,
     UpdatePortalRequestRequestTypeDef,
     UpdateTrustStoreRequestRequestTypeDef,
+    UpdateTrustStoreResponseTypeDef,
     UpdateUserAccessLoggingSettingsRequestRequestTypeDef,
     UpdateUserSettingsRequestRequestTypeDef,
-    AssociateBrowserSettingsResponseTypeDef,
-    AssociateNetworkSettingsResponseTypeDef,
-    AssociateTrustStoreResponseTypeDef,
-    AssociateUserAccessLoggingSettingsResponseTypeDef,
-    AssociateUserSettingsResponseTypeDef,
-    CreateBrowserSettingsResponseTypeDef,
-    CreateIdentityProviderResponseTypeDef,
-    CreateNetworkSettingsResponseTypeDef,
-    CreatePortalResponseTypeDef,
-    CreateTrustStoreResponseTypeDef,
-    CreateUserAccessLoggingSettingsResponseTypeDef,
-    CreateUserSettingsResponseTypeDef,
-    GetPortalServiceProviderMetadataResponseTypeDef,
-    UpdateTrustStoreResponseTypeDef,
     ListBrowserSettingsResponseTypeDef,
     GetBrowserSettingsResponseTypeDef,
     UpdateBrowserSettingsResponseTypeDef,
     ListTrustStoreCertificatesResponseTypeDef,
     GetTrustStoreCertificateResponseTypeDef,
     CreateBrowserSettingsRequestRequestTypeDef,
     CreateNetworkSettingsRequestRequestTypeDef,
     CreatePortalRequestRequestTypeDef,
     CreateTrustStoreRequestRequestTypeDef,
     CreateUserAccessLoggingSettingsRequestRequestTypeDef,
     CreateUserSettingsRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateIpAccessSettingsRequestRequestTypeDef,
+    IpAccessSettingsTypeDef,
+    UpdateIpAccessSettingsRequestRequestTypeDef,
     GetIdentityProviderResponseTypeDef,
     UpdateIdentityProviderResponseTypeDef,
     GetNetworkSettingsResponseTypeDef,
     UpdateNetworkSettingsResponseTypeDef,
     GetPortalResponseTypeDef,
     UpdatePortalResponseTypeDef,
     GetTrustStoreResponseTypeDef,
     GetUserAccessLoggingSettingsResponseTypeDef,
     UpdateUserAccessLoggingSettingsResponseTypeDef,
     GetUserSettingsResponseTypeDef,
     UpdateUserSettingsResponseTypeDef,
     ListIdentityProvidersResponseTypeDef,
+    ListIpAccessSettingsResponseTypeDef,
     ListNetworkSettingsResponseTypeDef,
     ListPortalsResponseTypeDef,
     ListTrustStoresResponseTypeDef,
     ListUserAccessLoggingSettingsResponseTypeDef,
     ListUserSettingsResponseTypeDef,
+    GetIpAccessSettingsResponseTypeDef,
+    UpdateIpAccessSettingsResponseTypeDef,
 )
 
 
 def get_structure() -> AssociateBrowserSettingsRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/setup.py` & `types-aiobotocore-workspaces-web-2.5.1/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-workspaces-web.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-workspaces-web",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_workspaces_web"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WorkSpacesWeb 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.WorkSpacesWeb 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/"
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/__main__.py` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WorkSpacesWeb 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WorkSpacesWeb 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb\nOther"
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/client.py` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/client.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,46 +19,52 @@
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import AuthenticationTypeType, EnabledTypeType, IdentityProviderTypeType
 from .type_defs import (
     AssociateBrowserSettingsResponseTypeDef,
+    AssociateIpAccessSettingsResponseTypeDef,
     AssociateNetworkSettingsResponseTypeDef,
     AssociateTrustStoreResponseTypeDef,
     AssociateUserAccessLoggingSettingsResponseTypeDef,
     AssociateUserSettingsResponseTypeDef,
     CreateBrowserSettingsResponseTypeDef,
     CreateIdentityProviderResponseTypeDef,
+    CreateIpAccessSettingsResponseTypeDef,
     CreateNetworkSettingsResponseTypeDef,
     CreatePortalResponseTypeDef,
     CreateTrustStoreResponseTypeDef,
     CreateUserAccessLoggingSettingsResponseTypeDef,
     CreateUserSettingsResponseTypeDef,
     GetBrowserSettingsResponseTypeDef,
     GetIdentityProviderResponseTypeDef,
+    GetIpAccessSettingsResponseTypeDef,
     GetNetworkSettingsResponseTypeDef,
     GetPortalResponseTypeDef,
     GetPortalServiceProviderMetadataResponseTypeDef,
     GetTrustStoreCertificateResponseTypeDef,
     GetTrustStoreResponseTypeDef,
     GetUserAccessLoggingSettingsResponseTypeDef,
     GetUserSettingsResponseTypeDef,
+    IpRuleTypeDef,
     ListBrowserSettingsResponseTypeDef,
     ListIdentityProvidersResponseTypeDef,
+    ListIpAccessSettingsResponseTypeDef,
     ListNetworkSettingsResponseTypeDef,
     ListPortalsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrustStoreCertificatesResponseTypeDef,
     ListTrustStoresResponseTypeDef,
     ListUserAccessLoggingSettingsResponseTypeDef,
     ListUserSettingsResponseTypeDef,
     TagTypeDef,
     UpdateBrowserSettingsResponseTypeDef,
     UpdateIdentityProviderResponseTypeDef,
+    UpdateIpAccessSettingsResponseTypeDef,
     UpdateNetworkSettingsResponseTypeDef,
     UpdatePortalResponseTypeDef,
     UpdateTrustStoreResponseTypeDef,
     UpdateUserAccessLoggingSettingsResponseTypeDef,
     UpdateUserSettingsResponseTypeDef,
 )
 
@@ -108,14 +114,24 @@
         """
         Associates a browser settings resource with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_browser_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#associate_browser_settings)
         """
 
+    async def associate_ip_access_settings(
+        self, *, ipAccessSettingsArn: str, portalArn: str
+    ) -> AssociateIpAccessSettingsResponseTypeDef:
+        """
+        Associates an IP access settings resource with a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#associate_ip_access_settings)
+        """
+
     async def associate_network_settings(
         self, *, networkSettingsArn: str, portalArn: str
     ) -> AssociateNetworkSettingsResponseTypeDef:
         """
         Associates a network settings resource with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_network_settings)
@@ -196,14 +212,32 @@
         """
         Creates an identity provider resource that is then associated with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.create_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#create_identity_provider)
         """
 
+    async def create_ip_access_settings(
+        self,
+        *,
+        ipRules: Sequence[IpRuleTypeDef],
+        additionalEncryptionContext: Mapping[str, str] = ...,
+        clientToken: str = ...,
+        customerManagedKey: str = ...,
+        description: str = ...,
+        displayName: str = ...,
+        tags: Sequence[TagTypeDef] = ...
+    ) -> CreateIpAccessSettingsResponseTypeDef:
+        """
+        Creates an IP access settings resource that can be associated with a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.create_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#create_ip_access_settings)
+        """
+
     async def create_network_settings(
         self,
         *,
         securityGroupIds: Sequence[str],
         subnetIds: Sequence[str],
         vpcId: str,
         clientToken: str = ...,
@@ -290,14 +324,22 @@
         """
         Deletes the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_identity_provider)
         """
 
+    async def delete_ip_access_settings(self, *, ipAccessSettingsArn: str) -> Dict[str, Any]:
+        """
+        Deletes IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_ip_access_settings)
+        """
+
     async def delete_network_settings(self, *, networkSettingsArn: str) -> Dict[str, Any]:
         """
         Deletes network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_network_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_network_settings)
         """
@@ -340,14 +382,22 @@
         """
         Disassociates browser settings from a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_browser_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_browser_settings)
         """
 
+    async def disassociate_ip_access_settings(self, *, portalArn: str) -> Dict[str, Any]:
+        """
+        Disassociates IP access settings from a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_ip_access_settings)
+        """
+
     async def disassociate_network_settings(self, *, portalArn: str) -> Dict[str, Any]:
         """
         Disassociates network settings from a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_network_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_network_settings)
         """
@@ -406,14 +456,24 @@
         """
         Gets the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#get_identity_provider)
         """
 
+    async def get_ip_access_settings(
+        self, *, ipAccessSettingsArn: str
+    ) -> GetIpAccessSettingsResponseTypeDef:
+        """
+        Gets the IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#get_ip_access_settings)
+        """
+
     async def get_network_settings(
         self, *, networkSettingsArn: str
     ) -> GetNetworkSettingsResponseTypeDef:
         """
         Gets the network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_network_settings)
@@ -490,14 +550,24 @@
         """
         Retrieves a list of identity providers for a specific web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_identity_providers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#list_identity_providers)
         """
 
+    async def list_ip_access_settings(
+        self, *, maxResults: int = ..., nextToken: str = ...
+    ) -> ListIpAccessSettingsResponseTypeDef:
+        """
+        Retrieves a list of IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#list_ip_access_settings)
+        """
+
     async def list_network_settings(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListNetworkSettingsResponseTypeDef:
         """
         Retrieves a list of network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_network_settings)
@@ -604,14 +674,30 @@
         """
         Updates the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.update_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#update_identity_provider)
         """
 
+    async def update_ip_access_settings(
+        self,
+        *,
+        ipAccessSettingsArn: str,
+        clientToken: str = ...,
+        description: str = ...,
+        displayName: str = ...,
+        ipRules: Sequence[IpRuleTypeDef] = ...
+    ) -> UpdateIpAccessSettingsResponseTypeDef:
+        """
+        Updates IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.update_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#update_ip_access_settings)
+        """
+
     async def update_network_settings(
         self,
         *,
         networkSettingsArn: str,
         clientToken: str = ...,
         securityGroupIds: Sequence[str] = ...,
         subnetIds: Sequence[str] = ...,
```

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/client.pyi` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/client.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -19,46 +19,52 @@
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import AuthenticationTypeType, EnabledTypeType, IdentityProviderTypeType
 from .type_defs import (
     AssociateBrowserSettingsResponseTypeDef,
+    AssociateIpAccessSettingsResponseTypeDef,
     AssociateNetworkSettingsResponseTypeDef,
     AssociateTrustStoreResponseTypeDef,
     AssociateUserAccessLoggingSettingsResponseTypeDef,
     AssociateUserSettingsResponseTypeDef,
     CreateBrowserSettingsResponseTypeDef,
     CreateIdentityProviderResponseTypeDef,
+    CreateIpAccessSettingsResponseTypeDef,
     CreateNetworkSettingsResponseTypeDef,
     CreatePortalResponseTypeDef,
     CreateTrustStoreResponseTypeDef,
     CreateUserAccessLoggingSettingsResponseTypeDef,
     CreateUserSettingsResponseTypeDef,
     GetBrowserSettingsResponseTypeDef,
     GetIdentityProviderResponseTypeDef,
+    GetIpAccessSettingsResponseTypeDef,
     GetNetworkSettingsResponseTypeDef,
     GetPortalResponseTypeDef,
     GetPortalServiceProviderMetadataResponseTypeDef,
     GetTrustStoreCertificateResponseTypeDef,
     GetTrustStoreResponseTypeDef,
     GetUserAccessLoggingSettingsResponseTypeDef,
     GetUserSettingsResponseTypeDef,
+    IpRuleTypeDef,
     ListBrowserSettingsResponseTypeDef,
     ListIdentityProvidersResponseTypeDef,
+    ListIpAccessSettingsResponseTypeDef,
     ListNetworkSettingsResponseTypeDef,
     ListPortalsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrustStoreCertificatesResponseTypeDef,
     ListTrustStoresResponseTypeDef,
     ListUserAccessLoggingSettingsResponseTypeDef,
     ListUserSettingsResponseTypeDef,
     TagTypeDef,
     UpdateBrowserSettingsResponseTypeDef,
     UpdateIdentityProviderResponseTypeDef,
+    UpdateIpAccessSettingsResponseTypeDef,
     UpdateNetworkSettingsResponseTypeDef,
     UpdatePortalResponseTypeDef,
     UpdateTrustStoreResponseTypeDef,
     UpdateUserAccessLoggingSettingsResponseTypeDef,
     UpdateUserSettingsResponseTypeDef,
 )
 
@@ -103,14 +109,23 @@
     ) -> AssociateBrowserSettingsResponseTypeDef:
         """
         Associates a browser settings resource with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_browser_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#associate_browser_settings)
         """
+    async def associate_ip_access_settings(
+        self, *, ipAccessSettingsArn: str, portalArn: str
+    ) -> AssociateIpAccessSettingsResponseTypeDef:
+        """
+        Associates an IP access settings resource with a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#associate_ip_access_settings)
+        """
     async def associate_network_settings(
         self, *, networkSettingsArn: str, portalArn: str
     ) -> AssociateNetworkSettingsResponseTypeDef:
         """
         Associates a network settings resource with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.associate_network_settings)
@@ -183,14 +198,31 @@
     ) -> CreateIdentityProviderResponseTypeDef:
         """
         Creates an identity provider resource that is then associated with a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.create_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#create_identity_provider)
         """
+    async def create_ip_access_settings(
+        self,
+        *,
+        ipRules: Sequence[IpRuleTypeDef],
+        additionalEncryptionContext: Mapping[str, str] = ...,
+        clientToken: str = ...,
+        customerManagedKey: str = ...,
+        description: str = ...,
+        displayName: str = ...,
+        tags: Sequence[TagTypeDef] = ...
+    ) -> CreateIpAccessSettingsResponseTypeDef:
+        """
+        Creates an IP access settings resource that can be associated with a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.create_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#create_ip_access_settings)
+        """
     async def create_network_settings(
         self,
         *,
         securityGroupIds: Sequence[str],
         subnetIds: Sequence[str],
         vpcId: str,
         clientToken: str = ...,
@@ -270,14 +302,21 @@
     async def delete_identity_provider(self, *, identityProviderArn: str) -> Dict[str, Any]:
         """
         Deletes the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_identity_provider)
         """
+    async def delete_ip_access_settings(self, *, ipAccessSettingsArn: str) -> Dict[str, Any]:
+        """
+        Deletes IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_ip_access_settings)
+        """
     async def delete_network_settings(self, *, networkSettingsArn: str) -> Dict[str, Any]:
         """
         Deletes network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.delete_network_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#delete_network_settings)
         """
@@ -314,14 +353,21 @@
     async def disassociate_browser_settings(self, *, portalArn: str) -> Dict[str, Any]:
         """
         Disassociates browser settings from a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_browser_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_browser_settings)
         """
+    async def disassociate_ip_access_settings(self, *, portalArn: str) -> Dict[str, Any]:
+        """
+        Disassociates IP access settings from a web portal.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_ip_access_settings)
+        """
     async def disassociate_network_settings(self, *, portalArn: str) -> Dict[str, Any]:
         """
         Disassociates network settings from a web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.disassociate_network_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#disassociate_network_settings)
         """
@@ -373,14 +419,23 @@
     ) -> GetIdentityProviderResponseTypeDef:
         """
         Gets the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#get_identity_provider)
         """
+    async def get_ip_access_settings(
+        self, *, ipAccessSettingsArn: str
+    ) -> GetIpAccessSettingsResponseTypeDef:
+        """
+        Gets the IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#get_ip_access_settings)
+        """
     async def get_network_settings(
         self, *, networkSettingsArn: str
     ) -> GetNetworkSettingsResponseTypeDef:
         """
         Gets the network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.get_network_settings)
@@ -448,14 +503,23 @@
     ) -> ListIdentityProvidersResponseTypeDef:
         """
         Retrieves a list of identity providers for a specific web portal.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_identity_providers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#list_identity_providers)
         """
+    async def list_ip_access_settings(
+        self, *, maxResults: int = ..., nextToken: str = ...
+    ) -> ListIpAccessSettingsResponseTypeDef:
+        """
+        Retrieves a list of IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#list_ip_access_settings)
+        """
     async def list_network_settings(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListNetworkSettingsResponseTypeDef:
         """
         Retrieves a list of network settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.list_network_settings)
@@ -551,14 +615,29 @@
     ) -> UpdateIdentityProviderResponseTypeDef:
         """
         Updates the identity provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.update_identity_provider)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#update_identity_provider)
         """
+    async def update_ip_access_settings(
+        self,
+        *,
+        ipAccessSettingsArn: str,
+        clientToken: str = ...,
+        description: str = ...,
+        displayName: str = ...,
+        ipRules: Sequence[IpRuleTypeDef] = ...
+    ) -> UpdateIpAccessSettingsResponseTypeDef:
+        """
+        Updates IP access settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb.Client.update_ip_access_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/client/#update_ip_access_settings)
+        """
     async def update_network_settings(
         self,
         *,
         networkSettingsArn: str,
         clientToken: str = ...,
         securityGroupIds: Sequence[str] = ...,
         subnetIds: Sequence[str] = ...,
```

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/literals.py` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,29 +14,27 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AuthenticationTypeType",
     "BrowserTypeType",
     "EnabledTypeType",
     "IdentityProviderTypeType",
     "PortalStatusType",
     "RendererTypeType",
     "WorkSpacesWebServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 AuthenticationTypeType = Literal["IAM_Identity_Center", "Standard"]
 BrowserTypeType = Literal["Chrome"]
 EnabledTypeType = Literal["Disabled", "Enabled"]
 IdentityProviderTypeType = Literal[
     "Facebook", "Google", "LoginWithAmazon", "OIDC", "SAML", "SignInWithApple"
 ]
 PortalStatusType = Literal["Active", "Incomplete", "Pending"]
@@ -100,14 +98,15 @@
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
@@ -186,14 +185,15 @@
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
@@ -204,14 +204,15 @@
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
@@ -247,14 +248,15 @@
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
@@ -273,16 +275,19 @@
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
@@ -366,15 +371,17 @@
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/literals.pyi` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,27 +14,29 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AuthenticationTypeType",
     "BrowserTypeType",
     "EnabledTypeType",
     "IdentityProviderTypeType",
     "PortalStatusType",
     "RendererTypeType",
     "WorkSpacesWebServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 AuthenticationTypeType = Literal["IAM_Identity_Center", "Standard"]
 BrowserTypeType = Literal["Chrome"]
 EnabledTypeType = Literal["Disabled", "Enabled"]
 IdentityProviderTypeType = Literal[
     "Facebook", "Google", "LoginWithAmazon", "OIDC", "SAML", "SignInWithApple"
 ]
 PortalStatusType = Literal["Active", "Incomplete", "Pending"]
@@ -98,14 +100,15 @@
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
@@ -184,14 +187,15 @@
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
@@ -202,14 +206,15 @@
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
@@ -245,14 +250,15 @@
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
@@ -271,16 +277,19 @@
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
@@ -364,15 +373,17 @@
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/type_defs.py` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -32,172 +32,238 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateBrowserSettingsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateBrowserSettingsResponseTypeDef",
+    "AssociateIpAccessSettingsRequestRequestTypeDef",
+    "AssociateIpAccessSettingsResponseTypeDef",
     "AssociateNetworkSettingsRequestRequestTypeDef",
+    "AssociateNetworkSettingsResponseTypeDef",
     "AssociateTrustStoreRequestRequestTypeDef",
+    "AssociateTrustStoreResponseTypeDef",
     "AssociateUserAccessLoggingSettingsRequestRequestTypeDef",
+    "AssociateUserAccessLoggingSettingsResponseTypeDef",
     "AssociateUserSettingsRequestRequestTypeDef",
+    "AssociateUserSettingsResponseTypeDef",
     "BrowserSettingsSummaryTypeDef",
     "BrowserSettingsTypeDef",
     "CertificateSummaryTypeDef",
     "CertificateTypeDef",
     "TagTypeDef",
+    "CreateBrowserSettingsResponseTypeDef",
     "CreateIdentityProviderRequestRequestTypeDef",
+    "CreateIdentityProviderResponseTypeDef",
+    "IpRuleTypeDef",
+    "CreateIpAccessSettingsResponseTypeDef",
+    "CreateNetworkSettingsResponseTypeDef",
+    "CreatePortalResponseTypeDef",
+    "CreateTrustStoreResponseTypeDef",
+    "CreateUserAccessLoggingSettingsResponseTypeDef",
+    "CreateUserSettingsResponseTypeDef",
     "DeleteBrowserSettingsRequestRequestTypeDef",
     "DeleteIdentityProviderRequestRequestTypeDef",
+    "DeleteIpAccessSettingsRequestRequestTypeDef",
     "DeleteNetworkSettingsRequestRequestTypeDef",
     "DeletePortalRequestRequestTypeDef",
     "DeleteTrustStoreRequestRequestTypeDef",
     "DeleteUserAccessLoggingSettingsRequestRequestTypeDef",
     "DeleteUserSettingsRequestRequestTypeDef",
     "DisassociateBrowserSettingsRequestRequestTypeDef",
+    "DisassociateIpAccessSettingsRequestRequestTypeDef",
     "DisassociateNetworkSettingsRequestRequestTypeDef",
     "DisassociateTrustStoreRequestRequestTypeDef",
     "DisassociateUserAccessLoggingSettingsRequestRequestTypeDef",
     "DisassociateUserSettingsRequestRequestTypeDef",
     "GetBrowserSettingsRequestRequestTypeDef",
     "GetIdentityProviderRequestRequestTypeDef",
     "IdentityProviderTypeDef",
+    "GetIpAccessSettingsRequestRequestTypeDef",
     "GetNetworkSettingsRequestRequestTypeDef",
     "NetworkSettingsTypeDef",
     "GetPortalRequestRequestTypeDef",
     "PortalTypeDef",
     "GetPortalServiceProviderMetadataRequestRequestTypeDef",
+    "GetPortalServiceProviderMetadataResponseTypeDef",
     "GetTrustStoreCertificateRequestRequestTypeDef",
     "GetTrustStoreRequestRequestTypeDef",
     "TrustStoreTypeDef",
     "GetUserAccessLoggingSettingsRequestRequestTypeDef",
     "UserAccessLoggingSettingsTypeDef",
     "GetUserSettingsRequestRequestTypeDef",
     "UserSettingsTypeDef",
     "IdentityProviderSummaryTypeDef",
+    "IpAccessSettingsSummaryTypeDef",
     "ListBrowserSettingsRequestRequestTypeDef",
     "ListIdentityProvidersRequestRequestTypeDef",
+    "ListIpAccessSettingsRequestRequestTypeDef",
     "ListNetworkSettingsRequestRequestTypeDef",
     "NetworkSettingsSummaryTypeDef",
     "ListPortalsRequestRequestTypeDef",
     "PortalSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListTrustStoreCertificatesRequestRequestTypeDef",
     "ListTrustStoresRequestRequestTypeDef",
     "TrustStoreSummaryTypeDef",
     "ListUserAccessLoggingSettingsRequestRequestTypeDef",
     "UserAccessLoggingSettingsSummaryTypeDef",
     "ListUserSettingsRequestRequestTypeDef",
     "UserSettingsSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBrowserSettingsRequestRequestTypeDef",
     "UpdateIdentityProviderRequestRequestTypeDef",
     "UpdateNetworkSettingsRequestRequestTypeDef",
     "UpdatePortalRequestRequestTypeDef",
     "UpdateTrustStoreRequestRequestTypeDef",
+    "UpdateTrustStoreResponseTypeDef",
     "UpdateUserAccessLoggingSettingsRequestRequestTypeDef",
     "UpdateUserSettingsRequestRequestTypeDef",
-    "AssociateBrowserSettingsResponseTypeDef",
-    "AssociateNetworkSettingsResponseTypeDef",
-    "AssociateTrustStoreResponseTypeDef",
-    "AssociateUserAccessLoggingSettingsResponseTypeDef",
-    "AssociateUserSettingsResponseTypeDef",
-    "CreateBrowserSettingsResponseTypeDef",
-    "CreateIdentityProviderResponseTypeDef",
-    "CreateNetworkSettingsResponseTypeDef",
-    "CreatePortalResponseTypeDef",
-    "CreateTrustStoreResponseTypeDef",
-    "CreateUserAccessLoggingSettingsResponseTypeDef",
-    "CreateUserSettingsResponseTypeDef",
-    "GetPortalServiceProviderMetadataResponseTypeDef",
-    "UpdateTrustStoreResponseTypeDef",
     "ListBrowserSettingsResponseTypeDef",
     "GetBrowserSettingsResponseTypeDef",
     "UpdateBrowserSettingsResponseTypeDef",
     "ListTrustStoreCertificatesResponseTypeDef",
     "GetTrustStoreCertificateResponseTypeDef",
     "CreateBrowserSettingsRequestRequestTypeDef",
     "CreateNetworkSettingsRequestRequestTypeDef",
     "CreatePortalRequestRequestTypeDef",
     "CreateTrustStoreRequestRequestTypeDef",
     "CreateUserAccessLoggingSettingsRequestRequestTypeDef",
     "CreateUserSettingsRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateIpAccessSettingsRequestRequestTypeDef",
+    "IpAccessSettingsTypeDef",
+    "UpdateIpAccessSettingsRequestRequestTypeDef",
     "GetIdentityProviderResponseTypeDef",
     "UpdateIdentityProviderResponseTypeDef",
     "GetNetworkSettingsResponseTypeDef",
     "UpdateNetworkSettingsResponseTypeDef",
     "GetPortalResponseTypeDef",
     "UpdatePortalResponseTypeDef",
     "GetTrustStoreResponseTypeDef",
     "GetUserAccessLoggingSettingsResponseTypeDef",
     "UpdateUserAccessLoggingSettingsResponseTypeDef",
     "GetUserSettingsResponseTypeDef",
     "UpdateUserSettingsResponseTypeDef",
     "ListIdentityProvidersResponseTypeDef",
+    "ListIpAccessSettingsResponseTypeDef",
     "ListNetworkSettingsResponseTypeDef",
     "ListPortalsResponseTypeDef",
     "ListTrustStoresResponseTypeDef",
     "ListUserAccessLoggingSettingsResponseTypeDef",
     "ListUserSettingsResponseTypeDef",
+    "GetIpAccessSettingsResponseTypeDef",
+    "UpdateIpAccessSettingsResponseTypeDef",
 )
 
 AssociateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "AssociateBrowserSettingsRequestRequestTypeDef",
     {
         "browserSettingsArn": str,
         "portalArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateBrowserSettingsResponseTypeDef = TypedDict(
+    "AssociateBrowserSettingsResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "browserSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "AssociateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "portalArn": str,
+    },
+)
+
+AssociateIpAccessSettingsResponseTypeDef = TypedDict(
+    "AssociateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateNetworkSettingsRequestRequestTypeDef = TypedDict(
     "AssociateNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
         "portalArn": str,
     },
 )
 
+AssociateNetworkSettingsResponseTypeDef = TypedDict(
+    "AssociateNetworkSettingsResponseTypeDef",
+    {
+        "networkSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateTrustStoreRequestRequestTypeDef = TypedDict(
     "AssociateTrustStoreRequestRequestTypeDef",
     {
         "portalArn": str,
         "trustStoreArn": str,
     },
 )
 
+AssociateTrustStoreResponseTypeDef = TypedDict(
+    "AssociateTrustStoreResponseTypeDef",
+    {
+        "portalArn": str,
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
     "AssociateUserAccessLoggingSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
         "userAccessLoggingSettingsArn": str,
     },
 )
 
+AssociateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
+    "AssociateUserAccessLoggingSettingsResponseTypeDef",
+    {
+        "portalArn": str,
+        "userAccessLoggingSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateUserSettingsRequestRequestTypeDef = TypedDict(
     "AssociateUserSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
         "userSettingsArn": str,
     },
 )
 
+AssociateUserSettingsResponseTypeDef = TypedDict(
+    "AssociateUserSettingsResponseTypeDef",
+    {
+        "portalArn": str,
+        "userSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BrowserSettingsSummaryTypeDef = TypedDict(
     "BrowserSettingsSummaryTypeDef",
     {
         "browserSettingsArn": str,
     },
     total=False,
 )
@@ -251,14 +317,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateBrowserSettingsResponseTypeDef = TypedDict(
+    "CreateBrowserSettingsResponseTypeDef",
+    {
+        "browserSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateIdentityProviderRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIdentityProviderRequestRequestTypeDef",
     {
         "identityProviderDetails": Mapping[str, str],
         "identityProviderName": str,
         "identityProviderType": IdentityProviderTypeType,
         "portalArn": str,
@@ -276,28 +350,111 @@
 class CreateIdentityProviderRequestRequestTypeDef(
     _RequiredCreateIdentityProviderRequestRequestTypeDef,
     _OptionalCreateIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
 
+CreateIdentityProviderResponseTypeDef = TypedDict(
+    "CreateIdentityProviderResponseTypeDef",
+    {
+        "identityProviderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredIpRuleTypeDef = TypedDict(
+    "_RequiredIpRuleTypeDef",
+    {
+        "ipRange": str,
+    },
+)
+_OptionalIpRuleTypeDef = TypedDict(
+    "_OptionalIpRuleTypeDef",
+    {
+        "description": str,
+    },
+    total=False,
+)
+
+
+class IpRuleTypeDef(_RequiredIpRuleTypeDef, _OptionalIpRuleTypeDef):
+    pass
+
+
+CreateIpAccessSettingsResponseTypeDef = TypedDict(
+    "CreateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNetworkSettingsResponseTypeDef = TypedDict(
+    "CreateNetworkSettingsResponseTypeDef",
+    {
+        "networkSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePortalResponseTypeDef = TypedDict(
+    "CreatePortalResponseTypeDef",
+    {
+        "portalArn": str,
+        "portalEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateTrustStoreResponseTypeDef = TypedDict(
+    "CreateTrustStoreResponseTypeDef",
+    {
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
+    "CreateUserAccessLoggingSettingsResponseTypeDef",
+    {
+        "userAccessLoggingSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserSettingsResponseTypeDef = TypedDict(
+    "CreateUserSettingsResponseTypeDef",
+    {
+        "userSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteBrowserSettingsRequestRequestTypeDef = TypedDict(
     "DeleteBrowserSettingsRequestRequestTypeDef",
     {
         "browserSettingsArn": str,
     },
 )
 
 DeleteIdentityProviderRequestRequestTypeDef = TypedDict(
     "DeleteIdentityProviderRequestRequestTypeDef",
     {
         "identityProviderArn": str,
     },
 )
 
+DeleteIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "DeleteIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+
 DeleteNetworkSettingsRequestRequestTypeDef = TypedDict(
     "DeleteNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
     },
 )
 
@@ -332,14 +489,21 @@
 DisassociateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "DisassociateBrowserSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
+DisassociateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "DisassociateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "portalArn": str,
+    },
+)
+
 DisassociateNetworkSettingsRequestRequestTypeDef = TypedDict(
     "DisassociateNetworkSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
@@ -395,14 +559,21 @@
 )
 
 
 class IdentityProviderTypeDef(_RequiredIdentityProviderTypeDef, _OptionalIdentityProviderTypeDef):
     pass
 
 
+GetIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "GetIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+
 GetNetworkSettingsRequestRequestTypeDef = TypedDict(
     "GetNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
     },
 )
 
@@ -439,14 +610,15 @@
     "PortalTypeDef",
     {
         "authenticationType": AuthenticationTypeType,
         "browserSettingsArn": str,
         "browserType": Literal["Chrome"],
         "creationDate": datetime,
         "displayName": str,
+        "ipAccessSettingsArn": str,
         "networkSettingsArn": str,
         "portalArn": str,
         "portalEndpoint": str,
         "portalStatus": PortalStatusType,
         "rendererType": Literal["AppStream"],
         "statusReason": str,
         "trustStoreArn": str,
@@ -459,14 +631,23 @@
 GetPortalServiceProviderMetadataRequestRequestTypeDef = TypedDict(
     "GetPortalServiceProviderMetadataRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
+GetPortalServiceProviderMetadataResponseTypeDef = TypedDict(
+    "GetPortalServiceProviderMetadataResponseTypeDef",
+    {
+        "portalArn": str,
+        "serviceProviderSamlMetadata": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTrustStoreCertificateRequestRequestTypeDef = TypedDict(
     "GetTrustStoreCertificateRequestRequestTypeDef",
     {
         "thumbprint": str,
         "trustStoreArn": str,
     },
 )
@@ -555,14 +736,25 @@
         "identityProviderArn": str,
         "identityProviderName": str,
         "identityProviderType": IdentityProviderTypeType,
     },
     total=False,
 )
 
+IpAccessSettingsSummaryTypeDef = TypedDict(
+    "IpAccessSettingsSummaryTypeDef",
+    {
+        "creationDate": datetime,
+        "description": str,
+        "displayName": str,
+        "ipAccessSettingsArn": str,
+    },
+    total=False,
+)
+
 ListBrowserSettingsRequestRequestTypeDef = TypedDict(
     "ListBrowserSettingsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -587,14 +779,23 @@
 class ListIdentityProvidersRequestRequestTypeDef(
     _RequiredListIdentityProvidersRequestRequestTypeDef,
     _OptionalListIdentityProvidersRequestRequestTypeDef,
 ):
     pass
 
 
+ListIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "ListIpAccessSettingsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListNetworkSettingsRequestRequestTypeDef = TypedDict(
     "ListNetworkSettingsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -622,14 +823,15 @@
     "PortalSummaryTypeDef",
     {
         "authenticationType": AuthenticationTypeType,
         "browserSettingsArn": str,
         "browserType": Literal["Chrome"],
         "creationDate": datetime,
         "displayName": str,
+        "ipAccessSettingsArn": str,
         "networkSettingsArn": str,
         "portalArn": str,
         "portalEndpoint": str,
         "portalStatus": PortalStatusType,
         "rendererType": Literal["AppStream"],
         "trustStoreArn": str,
         "userAccessLoggingSettingsArn": str,
@@ -723,14 +925,25 @@
         "printAllowed": EnabledTypeType,
         "uploadAllowed": EnabledTypeType,
         "userSettingsArn": str,
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
@@ -849,14 +1062,22 @@
 
 class UpdateTrustStoreRequestRequestTypeDef(
     _RequiredUpdateTrustStoreRequestRequestTypeDef, _OptionalUpdateTrustStoreRequestRequestTypeDef
 ):
     pass
 
 
+UpdateTrustStoreResponseTypeDef = TypedDict(
+    "UpdateTrustStoreResponseTypeDef",
+    {
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserAccessLoggingSettingsRequestRequestTypeDef",
     {
         "userAccessLoggingSettingsArn": str,
     },
 )
 _OptionalUpdateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
@@ -901,174 +1122,55 @@
 class UpdateUserSettingsRequestRequestTypeDef(
     _RequiredUpdateUserSettingsRequestRequestTypeDef,
     _OptionalUpdateUserSettingsRequestRequestTypeDef,
 ):
     pass
 
 
-AssociateBrowserSettingsResponseTypeDef = TypedDict(
-    "AssociateBrowserSettingsResponseTypeDef",
-    {
-        "browserSettingsArn": str,
-        "portalArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateNetworkSettingsResponseTypeDef = TypedDict(
-    "AssociateNetworkSettingsResponseTypeDef",
-    {
-        "networkSettingsArn": str,
-        "portalArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateTrustStoreResponseTypeDef = TypedDict(
-    "AssociateTrustStoreResponseTypeDef",
-    {
-        "portalArn": str,
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
-    "AssociateUserAccessLoggingSettingsResponseTypeDef",
-    {
-        "portalArn": str,
-        "userAccessLoggingSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateUserSettingsResponseTypeDef = TypedDict(
-    "AssociateUserSettingsResponseTypeDef",
-    {
-        "portalArn": str,
-        "userSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBrowserSettingsResponseTypeDef = TypedDict(
-    "CreateBrowserSettingsResponseTypeDef",
-    {
-        "browserSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIdentityProviderResponseTypeDef = TypedDict(
-    "CreateIdentityProviderResponseTypeDef",
-    {
-        "identityProviderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkSettingsResponseTypeDef = TypedDict(
-    "CreateNetworkSettingsResponseTypeDef",
-    {
-        "networkSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePortalResponseTypeDef = TypedDict(
-    "CreatePortalResponseTypeDef",
-    {
-        "portalArn": str,
-        "portalEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTrustStoreResponseTypeDef = TypedDict(
-    "CreateTrustStoreResponseTypeDef",
-    {
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
-    "CreateUserAccessLoggingSettingsResponseTypeDef",
-    {
-        "userAccessLoggingSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserSettingsResponseTypeDef = TypedDict(
-    "CreateUserSettingsResponseTypeDef",
-    {
-        "userSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPortalServiceProviderMetadataResponseTypeDef = TypedDict(
-    "GetPortalServiceProviderMetadataResponseTypeDef",
-    {
-        "portalArn": str,
-        "serviceProviderSamlMetadata": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTrustStoreResponseTypeDef = TypedDict(
-    "UpdateTrustStoreResponseTypeDef",
-    {
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListBrowserSettingsResponseTypeDef = TypedDict(
     "ListBrowserSettingsResponseTypeDef",
     {
         "browserSettings": List[BrowserSettingsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBrowserSettingsResponseTypeDef = TypedDict(
     "GetBrowserSettingsResponseTypeDef",
     {
         "browserSettings": BrowserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBrowserSettingsResponseTypeDef = TypedDict(
     "UpdateBrowserSettingsResponseTypeDef",
     {
         "browserSettings": BrowserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrustStoreCertificatesResponseTypeDef = TypedDict(
     "ListTrustStoreCertificatesResponseTypeDef",
     {
         "certificateList": List[CertificateSummaryTypeDef],
         "nextToken": str,
         "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrustStoreCertificateResponseTypeDef = TypedDict(
     "GetTrustStoreCertificateResponseTypeDef",
     {
         "certificate": CertificateTypeDef,
         "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBrowserSettingsRequestRequestTypeDef",
     {
         "browserPolicy": str,
@@ -1205,15 +1307,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTagResourceRequestRequestTypeDef = TypedDict(
     "_RequiredTagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1231,148 +1333,248 @@
 
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredCreateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipRules": Sequence[IpRuleTypeDef],
+    },
+)
+_OptionalCreateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "additionalEncryptionContext": Mapping[str, str],
+        "clientToken": str,
+        "customerManagedKey": str,
+        "description": str,
+        "displayName": str,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateIpAccessSettingsRequestRequestTypeDef(
+    _RequiredCreateIpAccessSettingsRequestRequestTypeDef,
+    _OptionalCreateIpAccessSettingsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredIpAccessSettingsTypeDef = TypedDict(
+    "_RequiredIpAccessSettingsTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+_OptionalIpAccessSettingsTypeDef = TypedDict(
+    "_OptionalIpAccessSettingsTypeDef",
+    {
+        "associatedPortalArns": List[str],
+        "creationDate": datetime,
+        "description": str,
+        "displayName": str,
+        "ipRules": List[IpRuleTypeDef],
+    },
+    total=False,
+)
+
+
+class IpAccessSettingsTypeDef(_RequiredIpAccessSettingsTypeDef, _OptionalIpAccessSettingsTypeDef):
+    pass
+
+
+_RequiredUpdateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+_OptionalUpdateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "description": str,
+        "displayName": str,
+        "ipRules": Sequence[IpRuleTypeDef],
+    },
+    total=False,
+)
+
+
+class UpdateIpAccessSettingsRequestRequestTypeDef(
+    _RequiredUpdateIpAccessSettingsRequestRequestTypeDef,
+    _OptionalUpdateIpAccessSettingsRequestRequestTypeDef,
+):
+    pass
+
+
 GetIdentityProviderResponseTypeDef = TypedDict(
     "GetIdentityProviderResponseTypeDef",
     {
         "identityProvider": IdentityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIdentityProviderResponseTypeDef = TypedDict(
     "UpdateIdentityProviderResponseTypeDef",
     {
         "identityProvider": IdentityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkSettingsResponseTypeDef = TypedDict(
     "GetNetworkSettingsResponseTypeDef",
     {
         "networkSettings": NetworkSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkSettingsResponseTypeDef = TypedDict(
     "UpdateNetworkSettingsResponseTypeDef",
     {
         "networkSettings": NetworkSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPortalResponseTypeDef = TypedDict(
     "GetPortalResponseTypeDef",
     {
         "portal": PortalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePortalResponseTypeDef = TypedDict(
     "UpdatePortalResponseTypeDef",
     {
         "portal": PortalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrustStoreResponseTypeDef = TypedDict(
     "GetTrustStoreResponseTypeDef",
     {
         "trustStore": TrustStoreTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "GetUserAccessLoggingSettingsResponseTypeDef",
     {
         "userAccessLoggingSettings": UserAccessLoggingSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "UpdateUserAccessLoggingSettingsResponseTypeDef",
     {
         "userAccessLoggingSettings": UserAccessLoggingSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserSettingsResponseTypeDef = TypedDict(
     "GetUserSettingsResponseTypeDef",
     {
         "userSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserSettingsResponseTypeDef = TypedDict(
     "UpdateUserSettingsResponseTypeDef",
     {
         "userSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityProvidersResponseTypeDef = TypedDict(
     "ListIdentityProvidersResponseTypeDef",
     {
         "identityProviders": List[IdentityProviderSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListIpAccessSettingsResponseTypeDef = TypedDict(
+    "ListIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": List[IpAccessSettingsSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkSettingsResponseTypeDef = TypedDict(
     "ListNetworkSettingsResponseTypeDef",
     {
         "networkSettings": List[NetworkSettingsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortalsResponseTypeDef = TypedDict(
     "ListPortalsResponseTypeDef",
     {
         "nextToken": str,
         "portals": List[PortalSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrustStoresResponseTypeDef = TypedDict(
     "ListTrustStoresResponseTypeDef",
     {
         "nextToken": str,
         "trustStores": List[TrustStoreSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "ListUserAccessLoggingSettingsResponseTypeDef",
     {
         "nextToken": str,
         "userAccessLoggingSettings": List[UserAccessLoggingSettingsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserSettingsResponseTypeDef = TypedDict(
     "ListUserSettingsResponseTypeDef",
     {
         "nextToken": str,
         "userSettings": List[UserSettingsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetIpAccessSettingsResponseTypeDef = TypedDict(
+    "GetIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": IpAccessSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateIpAccessSettingsResponseTypeDef = TypedDict(
+    "UpdateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": IpAccessSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web/type_defs.pyi` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -31,172 +31,238 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateBrowserSettingsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateBrowserSettingsResponseTypeDef",
+    "AssociateIpAccessSettingsRequestRequestTypeDef",
+    "AssociateIpAccessSettingsResponseTypeDef",
     "AssociateNetworkSettingsRequestRequestTypeDef",
+    "AssociateNetworkSettingsResponseTypeDef",
     "AssociateTrustStoreRequestRequestTypeDef",
+    "AssociateTrustStoreResponseTypeDef",
     "AssociateUserAccessLoggingSettingsRequestRequestTypeDef",
+    "AssociateUserAccessLoggingSettingsResponseTypeDef",
     "AssociateUserSettingsRequestRequestTypeDef",
+    "AssociateUserSettingsResponseTypeDef",
     "BrowserSettingsSummaryTypeDef",
     "BrowserSettingsTypeDef",
     "CertificateSummaryTypeDef",
     "CertificateTypeDef",
     "TagTypeDef",
+    "CreateBrowserSettingsResponseTypeDef",
     "CreateIdentityProviderRequestRequestTypeDef",
+    "CreateIdentityProviderResponseTypeDef",
+    "IpRuleTypeDef",
+    "CreateIpAccessSettingsResponseTypeDef",
+    "CreateNetworkSettingsResponseTypeDef",
+    "CreatePortalResponseTypeDef",
+    "CreateTrustStoreResponseTypeDef",
+    "CreateUserAccessLoggingSettingsResponseTypeDef",
+    "CreateUserSettingsResponseTypeDef",
     "DeleteBrowserSettingsRequestRequestTypeDef",
     "DeleteIdentityProviderRequestRequestTypeDef",
+    "DeleteIpAccessSettingsRequestRequestTypeDef",
     "DeleteNetworkSettingsRequestRequestTypeDef",
     "DeletePortalRequestRequestTypeDef",
     "DeleteTrustStoreRequestRequestTypeDef",
     "DeleteUserAccessLoggingSettingsRequestRequestTypeDef",
     "DeleteUserSettingsRequestRequestTypeDef",
     "DisassociateBrowserSettingsRequestRequestTypeDef",
+    "DisassociateIpAccessSettingsRequestRequestTypeDef",
     "DisassociateNetworkSettingsRequestRequestTypeDef",
     "DisassociateTrustStoreRequestRequestTypeDef",
     "DisassociateUserAccessLoggingSettingsRequestRequestTypeDef",
     "DisassociateUserSettingsRequestRequestTypeDef",
     "GetBrowserSettingsRequestRequestTypeDef",
     "GetIdentityProviderRequestRequestTypeDef",
     "IdentityProviderTypeDef",
+    "GetIpAccessSettingsRequestRequestTypeDef",
     "GetNetworkSettingsRequestRequestTypeDef",
     "NetworkSettingsTypeDef",
     "GetPortalRequestRequestTypeDef",
     "PortalTypeDef",
     "GetPortalServiceProviderMetadataRequestRequestTypeDef",
+    "GetPortalServiceProviderMetadataResponseTypeDef",
     "GetTrustStoreCertificateRequestRequestTypeDef",
     "GetTrustStoreRequestRequestTypeDef",
     "TrustStoreTypeDef",
     "GetUserAccessLoggingSettingsRequestRequestTypeDef",
     "UserAccessLoggingSettingsTypeDef",
     "GetUserSettingsRequestRequestTypeDef",
     "UserSettingsTypeDef",
     "IdentityProviderSummaryTypeDef",
+    "IpAccessSettingsSummaryTypeDef",
     "ListBrowserSettingsRequestRequestTypeDef",
     "ListIdentityProvidersRequestRequestTypeDef",
+    "ListIpAccessSettingsRequestRequestTypeDef",
     "ListNetworkSettingsRequestRequestTypeDef",
     "NetworkSettingsSummaryTypeDef",
     "ListPortalsRequestRequestTypeDef",
     "PortalSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListTrustStoreCertificatesRequestRequestTypeDef",
     "ListTrustStoresRequestRequestTypeDef",
     "TrustStoreSummaryTypeDef",
     "ListUserAccessLoggingSettingsRequestRequestTypeDef",
     "UserAccessLoggingSettingsSummaryTypeDef",
     "ListUserSettingsRequestRequestTypeDef",
     "UserSettingsSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBrowserSettingsRequestRequestTypeDef",
     "UpdateIdentityProviderRequestRequestTypeDef",
     "UpdateNetworkSettingsRequestRequestTypeDef",
     "UpdatePortalRequestRequestTypeDef",
     "UpdateTrustStoreRequestRequestTypeDef",
+    "UpdateTrustStoreResponseTypeDef",
     "UpdateUserAccessLoggingSettingsRequestRequestTypeDef",
     "UpdateUserSettingsRequestRequestTypeDef",
-    "AssociateBrowserSettingsResponseTypeDef",
-    "AssociateNetworkSettingsResponseTypeDef",
-    "AssociateTrustStoreResponseTypeDef",
-    "AssociateUserAccessLoggingSettingsResponseTypeDef",
-    "AssociateUserSettingsResponseTypeDef",
-    "CreateBrowserSettingsResponseTypeDef",
-    "CreateIdentityProviderResponseTypeDef",
-    "CreateNetworkSettingsResponseTypeDef",
-    "CreatePortalResponseTypeDef",
-    "CreateTrustStoreResponseTypeDef",
-    "CreateUserAccessLoggingSettingsResponseTypeDef",
-    "CreateUserSettingsResponseTypeDef",
-    "GetPortalServiceProviderMetadataResponseTypeDef",
-    "UpdateTrustStoreResponseTypeDef",
     "ListBrowserSettingsResponseTypeDef",
     "GetBrowserSettingsResponseTypeDef",
     "UpdateBrowserSettingsResponseTypeDef",
     "ListTrustStoreCertificatesResponseTypeDef",
     "GetTrustStoreCertificateResponseTypeDef",
     "CreateBrowserSettingsRequestRequestTypeDef",
     "CreateNetworkSettingsRequestRequestTypeDef",
     "CreatePortalRequestRequestTypeDef",
     "CreateTrustStoreRequestRequestTypeDef",
     "CreateUserAccessLoggingSettingsRequestRequestTypeDef",
     "CreateUserSettingsRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateIpAccessSettingsRequestRequestTypeDef",
+    "IpAccessSettingsTypeDef",
+    "UpdateIpAccessSettingsRequestRequestTypeDef",
     "GetIdentityProviderResponseTypeDef",
     "UpdateIdentityProviderResponseTypeDef",
     "GetNetworkSettingsResponseTypeDef",
     "UpdateNetworkSettingsResponseTypeDef",
     "GetPortalResponseTypeDef",
     "UpdatePortalResponseTypeDef",
     "GetTrustStoreResponseTypeDef",
     "GetUserAccessLoggingSettingsResponseTypeDef",
     "UpdateUserAccessLoggingSettingsResponseTypeDef",
     "GetUserSettingsResponseTypeDef",
     "UpdateUserSettingsResponseTypeDef",
     "ListIdentityProvidersResponseTypeDef",
+    "ListIpAccessSettingsResponseTypeDef",
     "ListNetworkSettingsResponseTypeDef",
     "ListPortalsResponseTypeDef",
     "ListTrustStoresResponseTypeDef",
     "ListUserAccessLoggingSettingsResponseTypeDef",
     "ListUserSettingsResponseTypeDef",
+    "GetIpAccessSettingsResponseTypeDef",
+    "UpdateIpAccessSettingsResponseTypeDef",
 )
 
 AssociateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "AssociateBrowserSettingsRequestRequestTypeDef",
     {
         "browserSettingsArn": str,
         "portalArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateBrowserSettingsResponseTypeDef = TypedDict(
+    "AssociateBrowserSettingsResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "browserSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "AssociateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "portalArn": str,
+    },
+)
+
+AssociateIpAccessSettingsResponseTypeDef = TypedDict(
+    "AssociateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateNetworkSettingsRequestRequestTypeDef = TypedDict(
     "AssociateNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
         "portalArn": str,
     },
 )
 
+AssociateNetworkSettingsResponseTypeDef = TypedDict(
+    "AssociateNetworkSettingsResponseTypeDef",
+    {
+        "networkSettingsArn": str,
+        "portalArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateTrustStoreRequestRequestTypeDef = TypedDict(
     "AssociateTrustStoreRequestRequestTypeDef",
     {
         "portalArn": str,
         "trustStoreArn": str,
     },
 )
 
+AssociateTrustStoreResponseTypeDef = TypedDict(
+    "AssociateTrustStoreResponseTypeDef",
+    {
+        "portalArn": str,
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
     "AssociateUserAccessLoggingSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
         "userAccessLoggingSettingsArn": str,
     },
 )
 
+AssociateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
+    "AssociateUserAccessLoggingSettingsResponseTypeDef",
+    {
+        "portalArn": str,
+        "userAccessLoggingSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateUserSettingsRequestRequestTypeDef = TypedDict(
     "AssociateUserSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
         "userSettingsArn": str,
     },
 )
 
+AssociateUserSettingsResponseTypeDef = TypedDict(
+    "AssociateUserSettingsResponseTypeDef",
+    {
+        "portalArn": str,
+        "userSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BrowserSettingsSummaryTypeDef = TypedDict(
     "BrowserSettingsSummaryTypeDef",
     {
         "browserSettingsArn": str,
     },
     total=False,
 )
@@ -248,14 +314,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateBrowserSettingsResponseTypeDef = TypedDict(
+    "CreateBrowserSettingsResponseTypeDef",
+    {
+        "browserSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateIdentityProviderRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIdentityProviderRequestRequestTypeDef",
     {
         "identityProviderDetails": Mapping[str, str],
         "identityProviderName": str,
         "identityProviderType": IdentityProviderTypeType,
         "portalArn": str,
@@ -271,28 +345,109 @@
 
 class CreateIdentityProviderRequestRequestTypeDef(
     _RequiredCreateIdentityProviderRequestRequestTypeDef,
     _OptionalCreateIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
+CreateIdentityProviderResponseTypeDef = TypedDict(
+    "CreateIdentityProviderResponseTypeDef",
+    {
+        "identityProviderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredIpRuleTypeDef = TypedDict(
+    "_RequiredIpRuleTypeDef",
+    {
+        "ipRange": str,
+    },
+)
+_OptionalIpRuleTypeDef = TypedDict(
+    "_OptionalIpRuleTypeDef",
+    {
+        "description": str,
+    },
+    total=False,
+)
+
+class IpRuleTypeDef(_RequiredIpRuleTypeDef, _OptionalIpRuleTypeDef):
+    pass
+
+CreateIpAccessSettingsResponseTypeDef = TypedDict(
+    "CreateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNetworkSettingsResponseTypeDef = TypedDict(
+    "CreateNetworkSettingsResponseTypeDef",
+    {
+        "networkSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePortalResponseTypeDef = TypedDict(
+    "CreatePortalResponseTypeDef",
+    {
+        "portalArn": str,
+        "portalEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateTrustStoreResponseTypeDef = TypedDict(
+    "CreateTrustStoreResponseTypeDef",
+    {
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
+    "CreateUserAccessLoggingSettingsResponseTypeDef",
+    {
+        "userAccessLoggingSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateUserSettingsResponseTypeDef = TypedDict(
+    "CreateUserSettingsResponseTypeDef",
+    {
+        "userSettingsArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteBrowserSettingsRequestRequestTypeDef = TypedDict(
     "DeleteBrowserSettingsRequestRequestTypeDef",
     {
         "browserSettingsArn": str,
     },
 )
 
 DeleteIdentityProviderRequestRequestTypeDef = TypedDict(
     "DeleteIdentityProviderRequestRequestTypeDef",
     {
         "identityProviderArn": str,
     },
 )
 
+DeleteIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "DeleteIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+
 DeleteNetworkSettingsRequestRequestTypeDef = TypedDict(
     "DeleteNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
     },
 )
 
@@ -327,14 +482,21 @@
 DisassociateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "DisassociateBrowserSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
+DisassociateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "DisassociateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "portalArn": str,
+    },
+)
+
 DisassociateNetworkSettingsRequestRequestTypeDef = TypedDict(
     "DisassociateNetworkSettingsRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
@@ -388,14 +550,21 @@
     },
     total=False,
 )
 
 class IdentityProviderTypeDef(_RequiredIdentityProviderTypeDef, _OptionalIdentityProviderTypeDef):
     pass
 
+GetIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "GetIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+
 GetNetworkSettingsRequestRequestTypeDef = TypedDict(
     "GetNetworkSettingsRequestRequestTypeDef",
     {
         "networkSettingsArn": str,
     },
 )
 
@@ -430,14 +599,15 @@
     "PortalTypeDef",
     {
         "authenticationType": AuthenticationTypeType,
         "browserSettingsArn": str,
         "browserType": Literal["Chrome"],
         "creationDate": datetime,
         "displayName": str,
+        "ipAccessSettingsArn": str,
         "networkSettingsArn": str,
         "portalArn": str,
         "portalEndpoint": str,
         "portalStatus": PortalStatusType,
         "rendererType": Literal["AppStream"],
         "statusReason": str,
         "trustStoreArn": str,
@@ -450,14 +620,23 @@
 GetPortalServiceProviderMetadataRequestRequestTypeDef = TypedDict(
     "GetPortalServiceProviderMetadataRequestRequestTypeDef",
     {
         "portalArn": str,
     },
 )
 
+GetPortalServiceProviderMetadataResponseTypeDef = TypedDict(
+    "GetPortalServiceProviderMetadataResponseTypeDef",
+    {
+        "portalArn": str,
+        "serviceProviderSamlMetadata": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTrustStoreCertificateRequestRequestTypeDef = TypedDict(
     "GetTrustStoreCertificateRequestRequestTypeDef",
     {
         "thumbprint": str,
         "trustStoreArn": str,
     },
 )
@@ -542,14 +721,25 @@
         "identityProviderArn": str,
         "identityProviderName": str,
         "identityProviderType": IdentityProviderTypeType,
     },
     total=False,
 )
 
+IpAccessSettingsSummaryTypeDef = TypedDict(
+    "IpAccessSettingsSummaryTypeDef",
+    {
+        "creationDate": datetime,
+        "description": str,
+        "displayName": str,
+        "ipAccessSettingsArn": str,
+    },
+    total=False,
+)
+
 ListBrowserSettingsRequestRequestTypeDef = TypedDict(
     "ListBrowserSettingsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -572,14 +762,23 @@
 
 class ListIdentityProvidersRequestRequestTypeDef(
     _RequiredListIdentityProvidersRequestRequestTypeDef,
     _OptionalListIdentityProvidersRequestRequestTypeDef,
 ):
     pass
 
+ListIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "ListIpAccessSettingsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 ListNetworkSettingsRequestRequestTypeDef = TypedDict(
     "ListNetworkSettingsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -607,14 +806,15 @@
     "PortalSummaryTypeDef",
     {
         "authenticationType": AuthenticationTypeType,
         "browserSettingsArn": str,
         "browserType": Literal["Chrome"],
         "creationDate": datetime,
         "displayName": str,
+        "ipAccessSettingsArn": str,
         "networkSettingsArn": str,
         "portalArn": str,
         "portalEndpoint": str,
         "portalStatus": PortalStatusType,
         "rendererType": Literal["AppStream"],
         "trustStoreArn": str,
         "userAccessLoggingSettingsArn": str,
@@ -706,14 +906,25 @@
         "printAllowed": EnabledTypeType,
         "uploadAllowed": EnabledTypeType,
         "userSettingsArn": str,
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
@@ -822,14 +1033,22 @@
 )
 
 class UpdateTrustStoreRequestRequestTypeDef(
     _RequiredUpdateTrustStoreRequestRequestTypeDef, _OptionalUpdateTrustStoreRequestRequestTypeDef
 ):
     pass
 
+UpdateTrustStoreResponseTypeDef = TypedDict(
+    "UpdateTrustStoreResponseTypeDef",
+    {
+        "trustStoreArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserAccessLoggingSettingsRequestRequestTypeDef",
     {
         "userAccessLoggingSettingsArn": str,
     },
 )
 _OptionalUpdateUserAccessLoggingSettingsRequestRequestTypeDef = TypedDict(
@@ -870,174 +1089,55 @@
 
 class UpdateUserSettingsRequestRequestTypeDef(
     _RequiredUpdateUserSettingsRequestRequestTypeDef,
     _OptionalUpdateUserSettingsRequestRequestTypeDef,
 ):
     pass
 
-AssociateBrowserSettingsResponseTypeDef = TypedDict(
-    "AssociateBrowserSettingsResponseTypeDef",
-    {
-        "browserSettingsArn": str,
-        "portalArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateNetworkSettingsResponseTypeDef = TypedDict(
-    "AssociateNetworkSettingsResponseTypeDef",
-    {
-        "networkSettingsArn": str,
-        "portalArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateTrustStoreResponseTypeDef = TypedDict(
-    "AssociateTrustStoreResponseTypeDef",
-    {
-        "portalArn": str,
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
-    "AssociateUserAccessLoggingSettingsResponseTypeDef",
-    {
-        "portalArn": str,
-        "userAccessLoggingSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateUserSettingsResponseTypeDef = TypedDict(
-    "AssociateUserSettingsResponseTypeDef",
-    {
-        "portalArn": str,
-        "userSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBrowserSettingsResponseTypeDef = TypedDict(
-    "CreateBrowserSettingsResponseTypeDef",
-    {
-        "browserSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIdentityProviderResponseTypeDef = TypedDict(
-    "CreateIdentityProviderResponseTypeDef",
-    {
-        "identityProviderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkSettingsResponseTypeDef = TypedDict(
-    "CreateNetworkSettingsResponseTypeDef",
-    {
-        "networkSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePortalResponseTypeDef = TypedDict(
-    "CreatePortalResponseTypeDef",
-    {
-        "portalArn": str,
-        "portalEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTrustStoreResponseTypeDef = TypedDict(
-    "CreateTrustStoreResponseTypeDef",
-    {
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
-    "CreateUserAccessLoggingSettingsResponseTypeDef",
-    {
-        "userAccessLoggingSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserSettingsResponseTypeDef = TypedDict(
-    "CreateUserSettingsResponseTypeDef",
-    {
-        "userSettingsArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPortalServiceProviderMetadataResponseTypeDef = TypedDict(
-    "GetPortalServiceProviderMetadataResponseTypeDef",
-    {
-        "portalArn": str,
-        "serviceProviderSamlMetadata": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTrustStoreResponseTypeDef = TypedDict(
-    "UpdateTrustStoreResponseTypeDef",
-    {
-        "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListBrowserSettingsResponseTypeDef = TypedDict(
     "ListBrowserSettingsResponseTypeDef",
     {
         "browserSettings": List[BrowserSettingsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBrowserSettingsResponseTypeDef = TypedDict(
     "GetBrowserSettingsResponseTypeDef",
     {
         "browserSettings": BrowserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBrowserSettingsResponseTypeDef = TypedDict(
     "UpdateBrowserSettingsResponseTypeDef",
     {
         "browserSettings": BrowserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrustStoreCertificatesResponseTypeDef = TypedDict(
     "ListTrustStoreCertificatesResponseTypeDef",
     {
         "certificateList": List[CertificateSummaryTypeDef],
         "nextToken": str,
         "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrustStoreCertificateResponseTypeDef = TypedDict(
     "GetTrustStoreCertificateResponseTypeDef",
     {
         "certificate": CertificateTypeDef,
         "trustStoreArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBrowserSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBrowserSettingsRequestRequestTypeDef",
     {
         "browserPolicy": str,
@@ -1164,15 +1264,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTagResourceRequestRequestTypeDef = TypedDict(
     "_RequiredTagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1188,148 +1288,242 @@
 )
 
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
+_RequiredCreateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipRules": Sequence[IpRuleTypeDef],
+    },
+)
+_OptionalCreateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "additionalEncryptionContext": Mapping[str, str],
+        "clientToken": str,
+        "customerManagedKey": str,
+        "description": str,
+        "displayName": str,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateIpAccessSettingsRequestRequestTypeDef(
+    _RequiredCreateIpAccessSettingsRequestRequestTypeDef,
+    _OptionalCreateIpAccessSettingsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredIpAccessSettingsTypeDef = TypedDict(
+    "_RequiredIpAccessSettingsTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+_OptionalIpAccessSettingsTypeDef = TypedDict(
+    "_OptionalIpAccessSettingsTypeDef",
+    {
+        "associatedPortalArns": List[str],
+        "creationDate": datetime,
+        "description": str,
+        "displayName": str,
+        "ipRules": List[IpRuleTypeDef],
+    },
+    total=False,
+)
+
+class IpAccessSettingsTypeDef(_RequiredIpAccessSettingsTypeDef, _OptionalIpAccessSettingsTypeDef):
+    pass
+
+_RequiredUpdateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "ipAccessSettingsArn": str,
+    },
+)
+_OptionalUpdateIpAccessSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateIpAccessSettingsRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "description": str,
+        "displayName": str,
+        "ipRules": Sequence[IpRuleTypeDef],
+    },
+    total=False,
+)
+
+class UpdateIpAccessSettingsRequestRequestTypeDef(
+    _RequiredUpdateIpAccessSettingsRequestRequestTypeDef,
+    _OptionalUpdateIpAccessSettingsRequestRequestTypeDef,
+):
+    pass
+
 GetIdentityProviderResponseTypeDef = TypedDict(
     "GetIdentityProviderResponseTypeDef",
     {
         "identityProvider": IdentityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIdentityProviderResponseTypeDef = TypedDict(
     "UpdateIdentityProviderResponseTypeDef",
     {
         "identityProvider": IdentityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkSettingsResponseTypeDef = TypedDict(
     "GetNetworkSettingsResponseTypeDef",
     {
         "networkSettings": NetworkSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkSettingsResponseTypeDef = TypedDict(
     "UpdateNetworkSettingsResponseTypeDef",
     {
         "networkSettings": NetworkSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPortalResponseTypeDef = TypedDict(
     "GetPortalResponseTypeDef",
     {
         "portal": PortalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePortalResponseTypeDef = TypedDict(
     "UpdatePortalResponseTypeDef",
     {
         "portal": PortalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrustStoreResponseTypeDef = TypedDict(
     "GetTrustStoreResponseTypeDef",
     {
         "trustStore": TrustStoreTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "GetUserAccessLoggingSettingsResponseTypeDef",
     {
         "userAccessLoggingSettings": UserAccessLoggingSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "UpdateUserAccessLoggingSettingsResponseTypeDef",
     {
         "userAccessLoggingSettings": UserAccessLoggingSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserSettingsResponseTypeDef = TypedDict(
     "GetUserSettingsResponseTypeDef",
     {
         "userSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserSettingsResponseTypeDef = TypedDict(
     "UpdateUserSettingsResponseTypeDef",
     {
         "userSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityProvidersResponseTypeDef = TypedDict(
     "ListIdentityProvidersResponseTypeDef",
     {
         "identityProviders": List[IdentityProviderSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListIpAccessSettingsResponseTypeDef = TypedDict(
+    "ListIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": List[IpAccessSettingsSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkSettingsResponseTypeDef = TypedDict(
     "ListNetworkSettingsResponseTypeDef",
     {
         "networkSettings": List[NetworkSettingsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPortalsResponseTypeDef = TypedDict(
     "ListPortalsResponseTypeDef",
     {
         "nextToken": str,
         "portals": List[PortalSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrustStoresResponseTypeDef = TypedDict(
     "ListTrustStoresResponseTypeDef",
     {
         "nextToken": str,
         "trustStores": List[TrustStoreSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserAccessLoggingSettingsResponseTypeDef = TypedDict(
     "ListUserAccessLoggingSettingsResponseTypeDef",
     {
         "nextToken": str,
         "userAccessLoggingSettings": List[UserAccessLoggingSettingsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserSettingsResponseTypeDef = TypedDict(
     "ListUserSettingsResponseTypeDef",
     {
         "nextToken": str,
         "userSettings": List[UserSettingsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetIpAccessSettingsResponseTypeDef = TypedDict(
+    "GetIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": IpAccessSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateIpAccessSettingsResponseTypeDef = TypedDict(
+    "UpdateIpAccessSettingsResponseTypeDef",
+    {
+        "ipAccessSettings": IpAccessSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/PKG-INFO` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workspaces-web
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkSpacesWeb 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkSpacesWeb 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workspaces-web"></a>
 
 # types-aiobotocore-workspaces-web
 
 [![PyPI - types-aiobotocore-workspaces-web](https://img.shields.io/pypi/v/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workspaces-web.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workspaces-web)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workspaces-web?color=blue)](https://pypistats.org/packages/types-aiobotocore-workspaces-web)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkSpacesWeb 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
+[aiobotocore.WorkSpacesWeb 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workspaces-web.html#WorkSpacesWeb)
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
 [types-aiobotocore-workspaces-web docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workspaces_web/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,162 +296,177 @@
 
 `types_aiobotocore_workspaces_web.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workspaces_web.type_defs import (
     AssociateBrowserSettingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateBrowserSettingsResponseTypeDef,
+    AssociateIpAccessSettingsRequestRequestTypeDef,
+    AssociateIpAccessSettingsResponseTypeDef,
     AssociateNetworkSettingsRequestRequestTypeDef,
+    AssociateNetworkSettingsResponseTypeDef,
     AssociateTrustStoreRequestRequestTypeDef,
+    AssociateTrustStoreResponseTypeDef,
     AssociateUserAccessLoggingSettingsRequestRequestTypeDef,
+    AssociateUserAccessLoggingSettingsResponseTypeDef,
     AssociateUserSettingsRequestRequestTypeDef,
+    AssociateUserSettingsResponseTypeDef,
     BrowserSettingsSummaryTypeDef,
     BrowserSettingsTypeDef,
     CertificateSummaryTypeDef,
     CertificateTypeDef,
     TagTypeDef,
+    CreateBrowserSettingsResponseTypeDef,
     CreateIdentityProviderRequestRequestTypeDef,
+    CreateIdentityProviderResponseTypeDef,
+    IpRuleTypeDef,
+    CreateIpAccessSettingsResponseTypeDef,
+    CreateNetworkSettingsResponseTypeDef,
+    CreatePortalResponseTypeDef,
+    CreateTrustStoreResponseTypeDef,
+    CreateUserAccessLoggingSettingsResponseTypeDef,
+    CreateUserSettingsResponseTypeDef,
     DeleteBrowserSettingsRequestRequestTypeDef,
     DeleteIdentityProviderRequestRequestTypeDef,
+    DeleteIpAccessSettingsRequestRequestTypeDef,
     DeleteNetworkSettingsRequestRequestTypeDef,
     DeletePortalRequestRequestTypeDef,
     DeleteTrustStoreRequestRequestTypeDef,
     DeleteUserAccessLoggingSettingsRequestRequestTypeDef,
     DeleteUserSettingsRequestRequestTypeDef,
     DisassociateBrowserSettingsRequestRequestTypeDef,
+    DisassociateIpAccessSettingsRequestRequestTypeDef,
     DisassociateNetworkSettingsRequestRequestTypeDef,
     DisassociateTrustStoreRequestRequestTypeDef,
     DisassociateUserAccessLoggingSettingsRequestRequestTypeDef,
     DisassociateUserSettingsRequestRequestTypeDef,
     GetBrowserSettingsRequestRequestTypeDef,
     GetIdentityProviderRequestRequestTypeDef,
     IdentityProviderTypeDef,
+    GetIpAccessSettingsRequestRequestTypeDef,
     GetNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsTypeDef,
     GetPortalRequestRequestTypeDef,
     PortalTypeDef,
     GetPortalServiceProviderMetadataRequestRequestTypeDef,
+    GetPortalServiceProviderMetadataResponseTypeDef,
     GetTrustStoreCertificateRequestRequestTypeDef,
     GetTrustStoreRequestRequestTypeDef,
     TrustStoreTypeDef,
     GetUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsTypeDef,
     GetUserSettingsRequestRequestTypeDef,
     UserSettingsTypeDef,
     IdentityProviderSummaryTypeDef,
+    IpAccessSettingsSummaryTypeDef,
     ListBrowserSettingsRequestRequestTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    ListIpAccessSettingsRequestRequestTypeDef,
     ListNetworkSettingsRequestRequestTypeDef,
     NetworkSettingsSummaryTypeDef,
     ListPortalsRequestRequestTypeDef,
     PortalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTrustStoreCertificatesRequestRequestTypeDef,
     ListTrustStoresRequestRequestTypeDef,
     TrustStoreSummaryTypeDef,
     ListUserAccessLoggingSettingsRequestRequestTypeDef,
     UserAccessLoggingSettingsSummaryTypeDef,
     ListUserSettingsRequestRequestTypeDef,
     UserSettingsSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBrowserSettingsRequestRequestTypeDef,
     UpdateIdentityProviderRequestRequestTypeDef,
     UpdateNetworkSettingsRequestRequestTypeDef,
     UpdatePortalRequestRequestTypeDef,
     UpdateTrustStoreRequestRequestTypeDef,
+    UpdateTrustStoreResponseTypeDef,
     UpdateUserAccessLoggingSettingsRequestRequestTypeDef,
     UpdateUserSettingsRequestRequestTypeDef,
-    AssociateBrowserSettingsResponseTypeDef,
-    AssociateNetworkSettingsResponseTypeDef,
-    AssociateTrustStoreResponseTypeDef,
-    AssociateUserAccessLoggingSettingsResponseTypeDef,
-    AssociateUserSettingsResponseTypeDef,
-    CreateBrowserSettingsResponseTypeDef,
-    CreateIdentityProviderResponseTypeDef,
-    CreateNetworkSettingsResponseTypeDef,
-    CreatePortalResponseTypeDef,
-    CreateTrustStoreResponseTypeDef,
-    CreateUserAccessLoggingSettingsResponseTypeDef,
-    CreateUserSettingsResponseTypeDef,
-    GetPortalServiceProviderMetadataResponseTypeDef,
-    UpdateTrustStoreResponseTypeDef,
     ListBrowserSettingsResponseTypeDef,
     GetBrowserSettingsResponseTypeDef,
     UpdateBrowserSettingsResponseTypeDef,
     ListTrustStoreCertificatesResponseTypeDef,
     GetTrustStoreCertificateResponseTypeDef,
     CreateBrowserSettingsRequestRequestTypeDef,
     CreateNetworkSettingsRequestRequestTypeDef,
     CreatePortalRequestRequestTypeDef,
     CreateTrustStoreRequestRequestTypeDef,
     CreateUserAccessLoggingSettingsRequestRequestTypeDef,
     CreateUserSettingsRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateIpAccessSettingsRequestRequestTypeDef,
+    IpAccessSettingsTypeDef,
+    UpdateIpAccessSettingsRequestRequestTypeDef,
     GetIdentityProviderResponseTypeDef,
     UpdateIdentityProviderResponseTypeDef,
     GetNetworkSettingsResponseTypeDef,
     UpdateNetworkSettingsResponseTypeDef,
     GetPortalResponseTypeDef,
     UpdatePortalResponseTypeDef,
     GetTrustStoreResponseTypeDef,
     GetUserAccessLoggingSettingsResponseTypeDef,
     UpdateUserAccessLoggingSettingsResponseTypeDef,
     GetUserSettingsResponseTypeDef,
     UpdateUserSettingsResponseTypeDef,
     ListIdentityProvidersResponseTypeDef,
+    ListIpAccessSettingsResponseTypeDef,
     ListNetworkSettingsResponseTypeDef,
     ListPortalsResponseTypeDef,
     ListTrustStoresResponseTypeDef,
     ListUserAccessLoggingSettingsResponseTypeDef,
     ListUserSettingsResponseTypeDef,
+    GetIpAccessSettingsResponseTypeDef,
+    UpdateIpAccessSettingsResponseTypeDef,
 )
 
 
 def get_structure() -> AssociateBrowserSettingsRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-workspaces-web-2.5.0.post1/types_aiobotocore_workspaces_web.egg-info/SOURCES.txt` & `types-aiobotocore-workspaces-web-2.5.1/types_aiobotocore_workspaces_web.egg-info/SOURCES.txt`

 * *Files identical despite different names*

