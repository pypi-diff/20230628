# Comparing `tmp/types-aiobotocore-detective-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-detective-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-detective-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-detective-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-detective-2.5.0.post1.tar` & `types-aiobotocore-detective-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.643122 types-aiobotocore-detective-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14232 2023-03-11 12:26:29.643122 types-aiobotocore-detective-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12653 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.643122 types-aiobotocore-detective-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.643122 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      457 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18241 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18209 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8318 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8316 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14288 2023-03-11 12:12:19.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14279 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:18.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.643122 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14232 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:29.000000 types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.462123 types-aiobotocore-detective-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14226 2023-06-28 01:43:22.462123 types-aiobotocore-detective-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12653 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.462123 types-aiobotocore-detective-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.458123 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18240 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18208 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8555 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8553 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14316 2023-06-28 01:28:58.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14307 2023-06-28 01:28:58.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:57.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.462123 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14226 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:22.000000 types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-detective-2.5.0.post1/LICENSE` & `types-aiobotocore-detective-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-detective-2.5.0.post1/PKG-INFO` & `types-aiobotocore-detective-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-detective
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Detective 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Detective 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-detective"></a>
 
 # types-aiobotocore-detective
 
 [![PyPI - types-aiobotocore-detective](https://img.shields.io/pypi/v/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-detective?color=blue)](https://pypistats.org/packages/types-aiobotocore-detective)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Detective 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
+[aiobotocore.Detective 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
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
 [types-aiobotocore-detective docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,46 +298,46 @@
 
 ```python
 from types_aiobotocore_detective.type_defs import (
     AcceptInvitationRequestRequestTypeDef,
     AccountTypeDef,
     AdministratorTypeDef,
     BatchGetGraphMemberDatasourcesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedAccountTypeDef,
     BatchGetMembershipDatasourcesRequestRequestTypeDef,
     UnprocessedGraphTypeDef,
     CreateGraphRequestRequestTypeDef,
+    CreateGraphResponseTypeDef,
     TimestampForCollectionTypeDef,
     DatasourcePackageUsageInfoTypeDef,
     DeleteGraphRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DisassociateMembershipRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     GraphTypeDef,
     ListDatasourcePackagesRequestRequestTypeDef,
     ListGraphsRequestRequestTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListMembersRequestRequestTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RejectInvitationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMonitoringMemberRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasourcePackagesRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
-    CreateGraphResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DatasourcePackageIngestDetailTypeDef,
     MembershipDatasourcesTypeDef,
     MemberDetailTypeDef,
     ListGraphsResponseTypeDef,
     ListDatasourcePackagesResponseTypeDef,
     BatchGetGraphMemberDatasourcesResponseTypeDef,
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/README.md` & `types-aiobotocore-detective-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-detective"></a>
 
 # types-aiobotocore-detective
 
 [![PyPI - types-aiobotocore-detective](https://img.shields.io/pypi/v/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-detective?color=blue)](https://pypistats.org/packages/types-aiobotocore-detective)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Detective 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
+[aiobotocore.Detective 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
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
 [types-aiobotocore-detective docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,46 +265,46 @@
 
 ```python
 from types_aiobotocore_detective.type_defs import (
     AcceptInvitationRequestRequestTypeDef,
     AccountTypeDef,
     AdministratorTypeDef,
     BatchGetGraphMemberDatasourcesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedAccountTypeDef,
     BatchGetMembershipDatasourcesRequestRequestTypeDef,
     UnprocessedGraphTypeDef,
     CreateGraphRequestRequestTypeDef,
+    CreateGraphResponseTypeDef,
     TimestampForCollectionTypeDef,
     DatasourcePackageUsageInfoTypeDef,
     DeleteGraphRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DisassociateMembershipRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     GraphTypeDef,
     ListDatasourcePackagesRequestRequestTypeDef,
     ListGraphsRequestRequestTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListMembersRequestRequestTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RejectInvitationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMonitoringMemberRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasourcePackagesRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
-    CreateGraphResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DatasourcePackageIngestDetailTypeDef,
     MembershipDatasourcesTypeDef,
     MemberDetailTypeDef,
     ListGraphsResponseTypeDef,
     ListDatasourcePackagesResponseTypeDef,
     BatchGetGraphMemberDatasourcesResponseTypeDef,
@@ -323,43 +323,43 @@
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/setup.py` & `types-aiobotocore-detective-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-detective.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-detective",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_detective"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Detective 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Detective 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/"
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/__main__.py` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Detective 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Detective 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective\nOther"
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/client.py` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -298,15 +298,15 @@
         """
 
     async def start_monitoring_member(
         self, *, GraphArn: str, AccountId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Sends a request to enable data ingest for a member account that has a status of
-        `ACCEPTED_BUT_DISABLED` .
+        `ACCEPTED_BUT_DISABLED`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective.Client.start_monitoring_member)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/client/#start_monitoring_member)
         """
 
     async def tag_resource(self, *, ResourceArn: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
         """
```

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/client.pyi` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -272,15 +272,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/client/#reject_invitation)
         """
     async def start_monitoring_member(
         self, *, GraphArn: str, AccountId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Sends a request to enable data ingest for a member account that has a status of
-        `ACCEPTED_BUT_DISABLED` .
+        `ACCEPTED_BUT_DISABLED`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective.Client.start_monitoring_member)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/client/#start_monitoring_member)
         """
     async def tag_resource(self, *, ResourceArn: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Applies tag values to a behavior graph.
```

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/literals.py` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,30 +14,28 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DatasourcePackageIngestStateType",
     "DatasourcePackageType",
     "InvitationTypeType",
     "MemberDisabledReasonType",
     "MemberStatusType",
     "DetectiveServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 DatasourcePackageIngestStateType = Literal["DISABLED", "STARTED", "STOPPED"]
-DatasourcePackageType = Literal["DETECTIVE_CORE", "EKS_AUDIT"]
+DatasourcePackageType = Literal["ASFF_SECURITYHUB_FINDING", "DETECTIVE_CORE", "EKS_AUDIT"]
 InvitationTypeType = Literal["INVITATION", "ORGANIZATION"]
 MemberDisabledReasonType = Literal["VOLUME_TOO_HIGH", "VOLUME_UNKNOWN"]
 MemberStatusType = Literal[
     "ACCEPTED_BUT_DISABLED", "ENABLED", "INVITED", "VERIFICATION_FAILED", "VERIFICATION_IN_PROGRESS"
 ]
 DetectiveServiceName = Literal["detective"]
 ServiceName = Literal[
@@ -98,14 +96,15 @@
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
@@ -184,14 +183,15 @@
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
@@ -202,14 +202,15 @@
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
@@ -245,14 +246,15 @@
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
@@ -271,16 +273,19 @@
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
@@ -364,15 +369,17 @@
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/literals.pyi` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,28 +14,30 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DatasourcePackageIngestStateType",
     "DatasourcePackageType",
     "InvitationTypeType",
     "MemberDisabledReasonType",
     "MemberStatusType",
     "DetectiveServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 DatasourcePackageIngestStateType = Literal["DISABLED", "STARTED", "STOPPED"]
-DatasourcePackageType = Literal["DETECTIVE_CORE", "EKS_AUDIT"]
+DatasourcePackageType = Literal["ASFF_SECURITYHUB_FINDING", "DETECTIVE_CORE", "EKS_AUDIT"]
 InvitationTypeType = Literal["INVITATION", "ORGANIZATION"]
 MemberDisabledReasonType = Literal["VOLUME_TOO_HIGH", "VOLUME_UNKNOWN"]
 MemberStatusType = Literal[
     "ACCEPTED_BUT_DISABLED", "ENABLED", "INVITED", "VERIFICATION_FAILED", "VERIFICATION_IN_PROGRESS"
 ]
 DetectiveServiceName = Literal["detective"]
 ServiceName = Literal[
@@ -96,14 +98,15 @@
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
@@ -182,14 +185,15 @@
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
@@ -200,14 +204,15 @@
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
@@ -243,14 +248,15 @@
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
@@ -269,16 +275,19 @@
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
@@ -362,15 +371,17 @@
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/type_defs.py` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -30,46 +30,46 @@
 
 
 __all__ = (
     "AcceptInvitationRequestRequestTypeDef",
     "AccountTypeDef",
     "AdministratorTypeDef",
     "BatchGetGraphMemberDatasourcesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedAccountTypeDef",
     "BatchGetMembershipDatasourcesRequestRequestTypeDef",
     "UnprocessedGraphTypeDef",
     "CreateGraphRequestRequestTypeDef",
+    "CreateGraphResponseTypeDef",
     "TimestampForCollectionTypeDef",
     "DatasourcePackageUsageInfoTypeDef",
     "DeleteGraphRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
     "DisassociateMembershipRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "GetMembersRequestRequestTypeDef",
     "GraphTypeDef",
     "ListDatasourcePackagesRequestRequestTypeDef",
     "ListGraphsRequestRequestTypeDef",
     "ListInvitationsRequestRequestTypeDef",
     "ListMembersRequestRequestTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RejectInvitationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartMonitoringMemberRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDatasourcePackagesRequestRequestTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "CreateMembersRequestRequestTypeDef",
-    "CreateGraphResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "DatasourcePackageIngestDetailTypeDef",
     "MembershipDatasourcesTypeDef",
     "MemberDetailTypeDef",
     "ListGraphsResponseTypeDef",
     "ListDatasourcePackagesResponseTypeDef",
     "BatchGetGraphMemberDatasourcesResponseTypeDef",
@@ -109,25 +109,14 @@
     "BatchGetGraphMemberDatasourcesRequestRequestTypeDef",
     {
         "GraphArn": str,
         "AccountIds": Sequence[str],
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
 UnprocessedAccountTypeDef = TypedDict(
     "UnprocessedAccountTypeDef",
     {
         "AccountId": str,
         "Reason": str,
     },
     total=False,
@@ -153,14 +142,22 @@
     "CreateGraphRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGraphResponseTypeDef = TypedDict(
+    "CreateGraphResponseTypeDef",
+    {
+        "GraphArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimestampForCollectionTypeDef = TypedDict(
     "TimestampForCollectionTypeDef",
     {
         "Timestamp": datetime,
     },
     total=False,
 )
@@ -192,21 +189,36 @@
 DescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
 )
 
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "AutoEnable": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateMembershipRequestRequestTypeDef = TypedDict(
     "DisassociateMembershipRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 
@@ -302,21 +314,40 @@
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
 RejectInvitationRequestRequestTypeDef = TypedDict(
     "RejectInvitationRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
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
 StartMonitoringMemberRequestRequestTypeDef = TypedDict(
     "StartMonitoringMemberRequestRequestTypeDef",
     {
         "GraphArn": str,
         "AccountId": str,
     },
 )
@@ -386,60 +417,29 @@
 
 class CreateMembersRequestRequestTypeDef(
     _RequiredCreateMembersRequestRequestTypeDef, _OptionalCreateMembersRequestRequestTypeDef
 ):
     pass
 
 
-CreateGraphResponseTypeDef = TypedDict(
-    "CreateGraphResponseTypeDef",
-    {
-        "GraphArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    {
-        "AutoEnable": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
     "ListOrganizationAdminAccountsResponseTypeDef",
     {
         "Administrators": List[AdministratorTypeDef],
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
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "AccountIds": List[str],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasourcePackageIngestDetailTypeDef = TypedDict(
     "DatasourcePackageIngestDetailTypeDef",
     {
         "DatasourcePackageIngestState": DatasourcePackageIngestStateType,
@@ -491,73 +491,73 @@
 )
 
 ListGraphsResponseTypeDef = TypedDict(
     "ListGraphsResponseTypeDef",
     {
         "GraphList": List[GraphTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasourcePackagesResponseTypeDef = TypedDict(
     "ListDatasourcePackagesResponseTypeDef",
     {
         "DatasourcePackages": Dict[DatasourcePackageType, DatasourcePackageIngestDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetGraphMemberDatasourcesResponseTypeDef = TypedDict(
     "BatchGetGraphMemberDatasourcesResponseTypeDef",
     {
         "MemberDatasources": List[MembershipDatasourcesTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetMembershipDatasourcesResponseTypeDef = TypedDict(
     "BatchGetMembershipDatasourcesResponseTypeDef",
     {
         "MembershipDatasources": List[MembershipDatasourcesTypeDef],
         "UnprocessedGraphs": List[UnprocessedGraphTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "Members": List[MemberDetailTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "MemberDetails": List[MemberDetailTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "Invitations": List[MemberDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "MemberDetails": List[MemberDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective/type_defs.pyi` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -29,46 +29,46 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptInvitationRequestRequestTypeDef",
     "AccountTypeDef",
     "AdministratorTypeDef",
     "BatchGetGraphMemberDatasourcesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedAccountTypeDef",
     "BatchGetMembershipDatasourcesRequestRequestTypeDef",
     "UnprocessedGraphTypeDef",
     "CreateGraphRequestRequestTypeDef",
+    "CreateGraphResponseTypeDef",
     "TimestampForCollectionTypeDef",
     "DatasourcePackageUsageInfoTypeDef",
     "DeleteGraphRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
     "DisassociateMembershipRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "GetMembersRequestRequestTypeDef",
     "GraphTypeDef",
     "ListDatasourcePackagesRequestRequestTypeDef",
     "ListGraphsRequestRequestTypeDef",
     "ListInvitationsRequestRequestTypeDef",
     "ListMembersRequestRequestTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RejectInvitationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartMonitoringMemberRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDatasourcePackagesRequestRequestTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "CreateMembersRequestRequestTypeDef",
-    "CreateGraphResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "DatasourcePackageIngestDetailTypeDef",
     "MembershipDatasourcesTypeDef",
     "MemberDetailTypeDef",
     "ListGraphsResponseTypeDef",
     "ListDatasourcePackagesResponseTypeDef",
     "BatchGetGraphMemberDatasourcesResponseTypeDef",
@@ -108,25 +108,14 @@
     "BatchGetGraphMemberDatasourcesRequestRequestTypeDef",
     {
         "GraphArn": str,
         "AccountIds": Sequence[str],
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
 UnprocessedAccountTypeDef = TypedDict(
     "UnprocessedAccountTypeDef",
     {
         "AccountId": str,
         "Reason": str,
     },
     total=False,
@@ -152,14 +141,22 @@
     "CreateGraphRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGraphResponseTypeDef = TypedDict(
+    "CreateGraphResponseTypeDef",
+    {
+        "GraphArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimestampForCollectionTypeDef = TypedDict(
     "TimestampForCollectionTypeDef",
     {
         "Timestamp": datetime,
     },
     total=False,
 )
@@ -191,21 +188,36 @@
 DescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
 )
 
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "AutoEnable": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateMembershipRequestRequestTypeDef = TypedDict(
     "DisassociateMembershipRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 
@@ -297,21 +309,40 @@
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
 RejectInvitationRequestRequestTypeDef = TypedDict(
     "RejectInvitationRequestRequestTypeDef",
     {
         "GraphArn": str,
     },
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
 StartMonitoringMemberRequestRequestTypeDef = TypedDict(
     "StartMonitoringMemberRequestRequestTypeDef",
     {
         "GraphArn": str,
         "AccountId": str,
     },
 )
@@ -377,60 +408,29 @@
 )
 
 class CreateMembersRequestRequestTypeDef(
     _RequiredCreateMembersRequestRequestTypeDef, _OptionalCreateMembersRequestRequestTypeDef
 ):
     pass
 
-CreateGraphResponseTypeDef = TypedDict(
-    "CreateGraphResponseTypeDef",
-    {
-        "GraphArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    {
-        "AutoEnable": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
     "ListOrganizationAdminAccountsResponseTypeDef",
     {
         "Administrators": List[AdministratorTypeDef],
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
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "AccountIds": List[str],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasourcePackageIngestDetailTypeDef = TypedDict(
     "DatasourcePackageIngestDetailTypeDef",
     {
         "DatasourcePackageIngestState": DatasourcePackageIngestStateType,
@@ -482,73 +482,73 @@
 )
 
 ListGraphsResponseTypeDef = TypedDict(
     "ListGraphsResponseTypeDef",
     {
         "GraphList": List[GraphTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasourcePackagesResponseTypeDef = TypedDict(
     "ListDatasourcePackagesResponseTypeDef",
     {
         "DatasourcePackages": Dict[DatasourcePackageType, DatasourcePackageIngestDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetGraphMemberDatasourcesResponseTypeDef = TypedDict(
     "BatchGetGraphMemberDatasourcesResponseTypeDef",
     {
         "MemberDatasources": List[MembershipDatasourcesTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetMembershipDatasourcesResponseTypeDef = TypedDict(
     "BatchGetMembershipDatasourcesResponseTypeDef",
     {
         "MembershipDatasources": List[MembershipDatasourcesTypeDef],
         "UnprocessedGraphs": List[UnprocessedGraphTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "Members": List[MemberDetailTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "MemberDetails": List[MemberDetailTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "Invitations": List[MemberDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "MemberDetails": List[MemberDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/PKG-INFO` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-detective
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Detective 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Detective 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-detective"></a>
 
 # types-aiobotocore-detective
 
 [![PyPI - types-aiobotocore-detective](https://img.shields.io/pypi/v/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-detective.svg?color=blue)](https://pypi.org/project/types-aiobotocore-detective)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-detective?color=blue)](https://pypistats.org/packages/types-aiobotocore-detective)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Detective 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
+[aiobotocore.Detective 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/detective.html#Detective)
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
 [types-aiobotocore-detective docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_detective/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,46 +298,46 @@
 
 ```python
 from types_aiobotocore_detective.type_defs import (
     AcceptInvitationRequestRequestTypeDef,
     AccountTypeDef,
     AdministratorTypeDef,
     BatchGetGraphMemberDatasourcesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedAccountTypeDef,
     BatchGetMembershipDatasourcesRequestRequestTypeDef,
     UnprocessedGraphTypeDef,
     CreateGraphRequestRequestTypeDef,
+    CreateGraphResponseTypeDef,
     TimestampForCollectionTypeDef,
     DatasourcePackageUsageInfoTypeDef,
     DeleteGraphRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DisassociateMembershipRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     GraphTypeDef,
     ListDatasourcePackagesRequestRequestTypeDef,
     ListGraphsRequestRequestTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListMembersRequestRequestTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RejectInvitationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartMonitoringMemberRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasourcePackagesRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
-    CreateGraphResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DatasourcePackageIngestDetailTypeDef,
     MembershipDatasourcesTypeDef,
     MemberDetailTypeDef,
     ListGraphsResponseTypeDef,
     ListDatasourcePackagesResponseTypeDef,
     BatchGetGraphMemberDatasourcesResponseTypeDef,
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-detective-2.5.0.post1/types_aiobotocore_detective.egg-info/SOURCES.txt` & `types-aiobotocore-detective-2.5.1/types_aiobotocore_detective.egg-info/SOURCES.txt`

 * *Files identical despite different names*

