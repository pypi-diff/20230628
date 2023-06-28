# Comparing `tmp/types-aiobotocore-servicecatalog-appregistry-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-servicecatalog-appregistry-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-servicecatalog-appregistry-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-servicecatalog-appregistry-2.5.1.tar", last modified: Wed Jun 28 01:44:10 2023, max compression
```

## Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1.tar` & `types-aiobotocore-servicecatalog-appregistry-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.519629 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17519 2023-03-11 12:27:20.519629 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15887 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.519629 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2245 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.511629 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/
--rw-r--r--   0 runner    (1001) docker     (123)     1822 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1821 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22778 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22740 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9066 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9064 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7541 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7533 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21610 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21589 2023-03-11 12:24:04.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:03.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.519629 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17519 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-03-11 12:27:20.000000 types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.386213 types-aiobotocore-servicecatalog-appregistry-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17530 2023-06-28 01:44:10.386213 types-aiobotocore-servicecatalog-appregistry-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15904 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:10.386213 types-aiobotocore-servicecatalog-appregistry-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.386213 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/
+-rw-r--r--   0 runner    (1001) docker     (123)     1822 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1821 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22851 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22813 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9275 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9273 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7431 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7424 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21742 2023-06-28 01:40:53.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21721 2023-06-28 01:40:53.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:52.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:10.386213 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17530 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 01:44:10.000000 types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/LICENSE` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/PKG-INFO` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicecatalog-appregistry
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppRegistry 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppRegistry 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicecatalog-appregistry"></a>
 
 # types-aiobotocore-servicecatalog-appregistry
 
 [![PyPI - types-aiobotocore-servicecatalog-appregistry](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog-appregistry?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog-appregistry)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRegistry 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
+[aiobotocore.AppRegistry 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
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
 [types-aiobotocore-servicecatalog-appregistry docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,68 +347,68 @@
 
 ```python
 from types_aiobotocore_servicecatalog_appregistry.type_defs import (
     TagQueryConfigurationTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     AssociateAttributeGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAttributeGroupResponseTypeDef,
     AssociateResourceRequestRequestTypeDef,
+    AssociateResourceResponseTypeDef,
     AttributeGroupDetailsTypeDef,
     AttributeGroupSummaryTypeDef,
     AttributeGroupTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateAttributeGroupRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteAttributeGroupRequestRequestTypeDef,
     DisassociateAttributeGroupRequestRequestTypeDef,
+    DisassociateAttributeGroupResponseTypeDef,
     DisassociateResourceRequestRequestTypeDef,
+    DisassociateResourceResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetAssociatedResourceRequestRequestTypeDef,
     GetAttributeGroupRequestRequestTypeDef,
+    GetAttributeGroupResponseTypeDef,
     ResourceGroupTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
     ListAssociatedAttributeGroupsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsResponseTypeDef,
+    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
     ListAssociatedResourcesRequestRequestTypeDef,
+    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
     ListAttributeGroupsForApplicationRequestRequestTypeDef,
+    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ListAttributeGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     SyncResourceRequestRequestTypeDef,
+    SyncResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateAttributeGroupRequestRequestTypeDef,
     AppRegistryConfigurationTypeDef,
-    AssociateAttributeGroupResponseTypeDef,
-    AssociateResourceResponseTypeDef,
-    CreateApplicationResponseTypeDef,
     DeleteApplicationResponseTypeDef,
-    DisassociateAttributeGroupResponseTypeDef,
-    DisassociateResourceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributeGroupResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListAssociatedAttributeGroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SyncResourceResponseTypeDef,
+    CreateApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     ListAttributeGroupsForApplicationResponseTypeDef,
     DeleteAttributeGroupResponseTypeDef,
     ListAttributeGroupsResponseTypeDef,
     CreateAttributeGroupResponseTypeDef,
     UpdateAttributeGroupResponseTypeDef,
     IntegrationsTypeDef,
     ResourceIntegrationsTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ResourceInfoTypeDef,
     GetConfigurationResponseTypeDef,
     PutConfigurationRequestRequestTypeDef,
     GetApplicationResponseTypeDef,
     ResourceTypeDef,
     ListAssociatedResourcesResponseTypeDef,
     GetAssociatedResourceResponseTypeDef,
@@ -422,43 +422,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/README.md` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-servicecatalog-appregistry"></a>
 
 # types-aiobotocore-servicecatalog-appregistry
 
 [![PyPI - types-aiobotocore-servicecatalog-appregistry](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog-appregistry?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog-appregistry)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRegistry 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
+[aiobotocore.AppRegistry 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
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
 [types-aiobotocore-servicecatalog-appregistry docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/).
 
 See how it helps to find and fix potential bugs:
 
@@ -314,68 +314,68 @@
 
 ```python
 from types_aiobotocore_servicecatalog_appregistry.type_defs import (
     TagQueryConfigurationTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     AssociateAttributeGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAttributeGroupResponseTypeDef,
     AssociateResourceRequestRequestTypeDef,
+    AssociateResourceResponseTypeDef,
     AttributeGroupDetailsTypeDef,
     AttributeGroupSummaryTypeDef,
     AttributeGroupTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateAttributeGroupRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteAttributeGroupRequestRequestTypeDef,
     DisassociateAttributeGroupRequestRequestTypeDef,
+    DisassociateAttributeGroupResponseTypeDef,
     DisassociateResourceRequestRequestTypeDef,
+    DisassociateResourceResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetAssociatedResourceRequestRequestTypeDef,
     GetAttributeGroupRequestRequestTypeDef,
+    GetAttributeGroupResponseTypeDef,
     ResourceGroupTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
     ListAssociatedAttributeGroupsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsResponseTypeDef,
+    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
     ListAssociatedResourcesRequestRequestTypeDef,
+    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
     ListAttributeGroupsForApplicationRequestRequestTypeDef,
+    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ListAttributeGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     SyncResourceRequestRequestTypeDef,
+    SyncResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateAttributeGroupRequestRequestTypeDef,
     AppRegistryConfigurationTypeDef,
-    AssociateAttributeGroupResponseTypeDef,
-    AssociateResourceResponseTypeDef,
-    CreateApplicationResponseTypeDef,
     DeleteApplicationResponseTypeDef,
-    DisassociateAttributeGroupResponseTypeDef,
-    DisassociateResourceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributeGroupResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListAssociatedAttributeGroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SyncResourceResponseTypeDef,
+    CreateApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     ListAttributeGroupsForApplicationResponseTypeDef,
     DeleteAttributeGroupResponseTypeDef,
     ListAttributeGroupsResponseTypeDef,
     CreateAttributeGroupResponseTypeDef,
     UpdateAttributeGroupResponseTypeDef,
     IntegrationsTypeDef,
     ResourceIntegrationsTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ResourceInfoTypeDef,
     GetConfigurationResponseTypeDef,
     PutConfigurationRequestRequestTypeDef,
     GetApplicationResponseTypeDef,
     ResourceTypeDef,
     ListAssociatedResourcesResponseTypeDef,
     GetAssociatedResourceResponseTypeDef,
@@ -389,43 +389,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/setup.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-servicecatalog-appregistry.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-servicecatalog-appregistry",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_servicecatalog_appregistry"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppRegistry 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AppRegistry 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/",
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__init__.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__init__.pyi` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/__main__.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppRegistry 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppRegistry 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry\nOther"
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/client.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -73,14 +73,15 @@
 
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 
 class AppRegistryClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/)
@@ -159,25 +160,27 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.create_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#create_attribute_group)
         """
 
     async def delete_application(self, *, application: str) -> DeleteApplicationResponseTypeDef:
         """
-        Deletes an application that is specified either by its application ID or name.
+        Deletes an application that is specified either by its application ID, name, or
+        ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.delete_application)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#delete_application)
         """
 
     async def delete_attribute_group(
         self, *, attributeGroup: str
     ) -> DeleteAttributeGroupResponseTypeDef:
         """
-        Deletes an attribute group, specified either by its attribute group ID or name.
+        Deletes an attribute group, specified either by its attribute group ID, name, or
+        ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.delete_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#delete_attribute_group)
         """
 
     async def disassociate_attribute_group(
         self, *, application: str, attributeGroup: str
@@ -230,15 +233,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.get_associated_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#get_associated_resource)
         """
 
     async def get_attribute_group(self, *, attributeGroup: str) -> GetAttributeGroupResponseTypeDef:
         """
-        Retrieves an attribute group, either by its name or its ID.
+        Retrieves an attribute group by its ARN, ID, or name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.get_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#get_attribute_group)
         """
 
     async def get_configuration(self) -> GetConfigurationResponseTypeDef:
         """
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/client.pyi` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -70,14 +70,15 @@
 
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 class AppRegistryClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/)
     """
@@ -148,24 +149,26 @@
         Creates a new attribute group as a container for user-defined attributes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.create_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#create_attribute_group)
         """
     async def delete_application(self, *, application: str) -> DeleteApplicationResponseTypeDef:
         """
-        Deletes an application that is specified either by its application ID or name.
+        Deletes an application that is specified either by its application ID, name, or
+        ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.delete_application)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#delete_application)
         """
     async def delete_attribute_group(
         self, *, attributeGroup: str
     ) -> DeleteAttributeGroupResponseTypeDef:
         """
-        Deletes an attribute group, specified either by its attribute group ID or name.
+        Deletes an attribute group, specified either by its attribute group ID, name, or
+        ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.delete_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#delete_attribute_group)
         """
     async def disassociate_attribute_group(
         self, *, application: str, attributeGroup: str
     ) -> DisassociateAttributeGroupResponseTypeDef:
@@ -212,15 +215,15 @@
         Gets the resource associated with the application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.get_associated_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#get_associated_resource)
         """
     async def get_attribute_group(self, *, attributeGroup: str) -> GetAttributeGroupResponseTypeDef:
         """
-        Retrieves an attribute group, either by its name or its ID.
+        Retrieves an attribute group by its ARN, ID, or name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Client.get_attribute_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/client/#get_attribute_group)
         """
     async def get_configuration(self) -> GetConfigurationResponseTypeDef:
         """
         Retrieves a `TagKey` configuration from an account.
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/literals.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -105,14 +105,15 @@
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
@@ -191,14 +192,15 @@
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
@@ -209,14 +211,15 @@
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
@@ -252,14 +255,15 @@
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
@@ -278,16 +282,19 @@
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
@@ -371,15 +378,17 @@
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/literals.pyi` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -103,14 +103,15 @@
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
@@ -189,14 +190,15 @@
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
@@ -207,14 +209,15 @@
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
@@ -250,14 +253,15 @@
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
@@ -276,16 +280,19 @@
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
@@ -369,15 +376,17 @@
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/paginator.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,120 +24,106 @@
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_associated_attribute_groups_paginator: ListAssociatedAttributeGroupsPaginator = client.get_paginator("list_associated_attribute_groups")
         list_associated_resources_paginator: ListAssociatedResourcesPaginator = client.get_paginator("list_associated_resources")
         list_attribute_groups_paginator: ListAttributeGroupsPaginator = client.get_paginator("list_attribute_groups")
         list_attribute_groups_for_application_paginator: ListAttributeGroupsForApplicationPaginator = client.get_paginator("list_attribute_groups_for_application")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListAssociatedAttributeGroupsResponseTypeDef,
     ListAssociatedResourcesResponseTypeDef,
     ListAttributeGroupsForApplicationResponseTypeDef,
     ListAttributeGroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListAssociatedAttributeGroupsPaginator",
     "ListAssociatedResourcesPaginator",
     "ListAttributeGroupsPaginator",
     "ListAttributeGroupsForApplicationPaginator",
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
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listapplicationspaginator)
         """
 
-
 class ListAssociatedAttributeGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedAttributeGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedattributegroupspaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedAttributeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedAttributeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedattributegroupspaginator)
         """
 
-
 class ListAssociatedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedresourcespaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedresourcespaginator)
         """
 
-
 class ListAttributeGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupspaginator)
         """
 
-
 class ListAttributeGroupsForApplicationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroupsForApplication)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupsforapplicationpaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributeGroupsForApplicationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroupsForApplication.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupsforapplicationpaginator)
         """
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/paginator.pyi` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -24,112 +24,113 @@
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_associated_attribute_groups_paginator: ListAssociatedAttributeGroupsPaginator = client.get_paginator("list_associated_attribute_groups")
         list_associated_resources_paginator: ListAssociatedResourcesPaginator = client.get_paginator("list_associated_resources")
         list_attribute_groups_paginator: ListAttributeGroupsPaginator = client.get_paginator("list_attribute_groups")
         list_attribute_groups_for_application_paginator: ListAttributeGroupsForApplicationPaginator = client.get_paginator("list_attribute_groups_for_application")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListAssociatedAttributeGroupsResponseTypeDef,
     ListAssociatedResourcesResponseTypeDef,
     ListAttributeGroupsForApplicationResponseTypeDef,
     ListAttributeGroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListAssociatedAttributeGroupsPaginator",
     "ListAssociatedResourcesPaginator",
     "ListAttributeGroupsPaginator",
     "ListAttributeGroupsForApplicationPaginator",
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
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listapplicationspaginator)
         """
 
+
 class ListAssociatedAttributeGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedAttributeGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedattributegroupspaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedAttributeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedAttributeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedattributegroupspaginator)
         """
 
+
 class ListAssociatedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedresourcespaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAssociatedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listassociatedresourcespaginator)
         """
 
+
 class ListAttributeGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupspaginator)
         """
 
+
 class ListAttributeGroupsForApplicationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroupsForApplication)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupsforapplicationpaginator)
     """
 
     def paginate(
-        self, *, application: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, application: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributeGroupsForApplicationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry.Paginator.ListAttributeGroupsForApplication.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/paginators/#listattributegroupsforapplicationpaginator)
         """
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/type_defs.py` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,68 +24,68 @@
 
 
 __all__ = (
     "TagQueryConfigurationTypeDef",
     "ApplicationSummaryTypeDef",
     "ApplicationTypeDef",
     "AssociateAttributeGroupRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateAttributeGroupResponseTypeDef",
     "AssociateResourceRequestRequestTypeDef",
+    "AssociateResourceResponseTypeDef",
     "AttributeGroupDetailsTypeDef",
     "AttributeGroupSummaryTypeDef",
     "AttributeGroupTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "CreateAttributeGroupRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteAttributeGroupRequestRequestTypeDef",
     "DisassociateAttributeGroupRequestRequestTypeDef",
+    "DisassociateAttributeGroupResponseTypeDef",
     "DisassociateResourceRequestRequestTypeDef",
+    "DisassociateResourceResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetAssociatedResourceRequestRequestTypeDef",
     "GetAttributeGroupRequestRequestTypeDef",
+    "GetAttributeGroupResponseTypeDef",
     "ResourceGroupTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
     "ListAssociatedAttributeGroupsRequestRequestTypeDef",
+    "ListAssociatedAttributeGroupsResponseTypeDef",
+    "ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
     "ListAssociatedResourcesRequestRequestTypeDef",
+    "ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
     "ListAttributeGroupsForApplicationRequestRequestTypeDef",
+    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
     "ListAttributeGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "SyncResourceRequestRequestTypeDef",
+    "SyncResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateAttributeGroupRequestRequestTypeDef",
     "AppRegistryConfigurationTypeDef",
-    "AssociateAttributeGroupResponseTypeDef",
-    "AssociateResourceResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
     "DeleteApplicationResponseTypeDef",
-    "DisassociateAttributeGroupResponseTypeDef",
-    "DisassociateResourceResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAttributeGroupResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListAssociatedAttributeGroupsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SyncResourceResponseTypeDef",
+    "CreateApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
     "ListAttributeGroupsForApplicationResponseTypeDef",
     "DeleteAttributeGroupResponseTypeDef",
     "ListAttributeGroupsResponseTypeDef",
     "CreateAttributeGroupResponseTypeDef",
     "UpdateAttributeGroupResponseTypeDef",
     "IntegrationsTypeDef",
     "ResourceIntegrationsTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-    "ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    "ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
     "ResourceInfoTypeDef",
     "GetConfigurationResponseTypeDef",
     "PutConfigurationRequestRequestTypeDef",
     "GetApplicationResponseTypeDef",
     "ResourceTypeDef",
     "ListAssociatedResourcesResponseTypeDef",
     "GetAssociatedResourceResponseTypeDef",
@@ -130,53 +130,62 @@
     "AssociateAttributeGroupRequestRequestTypeDef",
     {
         "application": str,
         "attributeGroup": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateAttributeGroupResponseTypeDef = TypedDict(
+    "AssociateAttributeGroupResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationArn": str,
+        "attributeGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResourceRequestRequestTypeDef = TypedDict(
     "AssociateResourceRequestRequestTypeDef",
     {
         "application": str,
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+AssociateResourceResponseTypeDef = TypedDict(
+    "AssociateResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttributeGroupDetailsTypeDef = TypedDict(
     "AttributeGroupDetailsTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
+        "createdBy": str,
     },
     total=False,
 )
 
 AttributeGroupSummaryTypeDef = TypedDict(
     "AttributeGroupSummaryTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "description": str,
         "creationTime": datetime,
         "lastUpdateTime": datetime,
+        "createdBy": str,
     },
     total=False,
 )
 
 AttributeGroupTypeDef = TypedDict(
     "AttributeGroupTypeDef",
     {
@@ -257,23 +266,48 @@
     "DisassociateAttributeGroupRequestRequestTypeDef",
     {
         "application": str,
         "attributeGroup": str,
     },
 )
 
+DisassociateAttributeGroupResponseTypeDef = TypedDict(
+    "DisassociateAttributeGroupResponseTypeDef",
+    {
+        "applicationArn": str,
+        "attributeGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateResourceRequestRequestTypeDef = TypedDict(
     "DisassociateResourceRequestRequestTypeDef",
     {
         "application": str,
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+DisassociateResourceResponseTypeDef = TypedDict(
+    "DisassociateResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetApplicationRequestRequestTypeDef = TypedDict(
     "GetApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 
@@ -289,43 +323,83 @@
 GetAttributeGroupRequestRequestTypeDef = TypedDict(
     "GetAttributeGroupRequestRequestTypeDef",
     {
         "attributeGroup": str,
     },
 )
 
+GetAttributeGroupResponseTypeDef = TypedDict(
+    "GetAttributeGroupResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "attributes": str,
+        "creationTime": datetime,
+        "lastUpdateTime": datetime,
+        "tags": Dict[str, str],
+        "createdBy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceGroupTypeDef = TypedDict(
     "ResourceGroupTypeDef",
     {
         "state": ResourceGroupStateType,
         "arn": str,
         "errorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
+        {
+            "application": str,
+        },
+    )
+)
+_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef(
+    _RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
+    _OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedAttributeGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedAttributeGroupsRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAssociatedAttributeGroupsRequestRequestTypeDef = TypedDict(
@@ -341,14 +415,45 @@
 class ListAssociatedAttributeGroupsRequestRequestTypeDef(
     _RequiredListAssociatedAttributeGroupsRequestRequestTypeDef,
     _OptionalListAssociatedAttributeGroupsRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssociatedAttributeGroupsResponseTypeDef = TypedDict(
+    "ListAssociatedAttributeGroupsResponseTypeDef",
+    {
+        "attributeGroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
+    {
+        "application": str,
+    },
+)
+_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef(
+    _RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
+    _OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedResourcesRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAssociatedResourcesRequestRequestTypeDef = TypedDict(
@@ -364,14 +469,36 @@
 class ListAssociatedResourcesRequestRequestTypeDef(
     _RequiredListAssociatedResourcesRequestRequestTypeDef,
     _OptionalListAssociatedResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
+    "_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
+    {
+        "application": str,
+    },
+)
+_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
+    "_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef(
+    _RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
+    _OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttributeGroupsForApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredListAttributeGroupsForApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAttributeGroupsForApplicationRequestRequestTypeDef = TypedDict(
@@ -387,14 +514,22 @@
 class ListAttributeGroupsForApplicationRequestRequestTypeDef(
     _RequiredListAttributeGroupsForApplicationRequestRequestTypeDef,
     _OptionalListAttributeGroupsForApplicationRequestRequestTypeDef,
 ):
     pass
 
 
+ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef = TypedDict(
+    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAttributeGroupsRequestRequestTypeDef = TypedDict(
     "ListAttributeGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -403,30 +538,69 @@
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
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "tagValue": str,
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
 SyncResourceRequestRequestTypeDef = TypedDict(
     "SyncResourceRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+SyncResourceResponseTypeDef = TypedDict(
+    "SyncResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "actionTaken": SyncActionType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -489,171 +663,86 @@
     "AppRegistryConfigurationTypeDef",
     {
         "tagQueryConfiguration": TagQueryConfigurationTypeDef,
     },
     total=False,
 )
 
-AssociateAttributeGroupResponseTypeDef = TypedDict(
-    "AssociateAttributeGroupResponseTypeDef",
-    {
-        "applicationArn": str,
-        "attributeGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateResourceResponseTypeDef = TypedDict(
-    "AssociateResourceResponseTypeDef",
-    {
-        "applicationArn": str,
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeleteApplicationResponseTypeDef = TypedDict(
     "DeleteApplicationResponseTypeDef",
     {
         "application": ApplicationSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateAttributeGroupResponseTypeDef = TypedDict(
-    "DisassociateAttributeGroupResponseTypeDef",
-    {
-        "applicationArn": str,
-        "attributeGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateResourceResponseTypeDef = TypedDict(
-    "DisassociateResourceResponseTypeDef",
-    {
-        "applicationArn": str,
-        "resourceArn": str,
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
-GetAttributeGroupResponseTypeDef = TypedDict(
-    "GetAttributeGroupResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "name": str,
-        "description": str,
-        "attributes": str,
-        "creationTime": datetime,
-        "lastUpdateTime": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applications": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAssociatedAttributeGroupsResponseTypeDef = TypedDict(
-    "ListAssociatedAttributeGroupsResponseTypeDef",
-    {
-        "attributeGroups": List[str],
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
-SyncResourceResponseTypeDef = TypedDict(
-    "SyncResourceResponseTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "applicationArn": str,
-        "resourceArn": str,
-        "actionTaken": SyncActionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "application": ApplicationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttributeGroupsForApplicationResponseTypeDef = TypedDict(
     "ListAttributeGroupsForApplicationResponseTypeDef",
     {
         "attributeGroupsDetails": List[AttributeGroupDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAttributeGroupResponseTypeDef = TypedDict(
     "DeleteAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttributeGroupsResponseTypeDef = TypedDict(
     "ListAttributeGroupsResponseTypeDef",
     {
         "attributeGroups": List[AttributeGroupSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttributeGroupResponseTypeDef = TypedDict(
     "CreateAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAttributeGroupResponseTypeDef = TypedDict(
     "UpdateAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntegrationsTypeDef = TypedDict(
     "IntegrationsTypeDef",
     {
         "resourceGroup": ResourceGroupTypeDef,
@@ -665,100 +754,14 @@
     "ResourceIntegrationsTypeDef",
     {
         "resourceGroup": ResourceGroupTypeDef,
     },
     total=False,
 )
 
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-        {
-            "application": str,
-        },
-    )
-)
-_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef(
-    _RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-    _OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    {
-        "application": str,
-    },
-)
-_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef(
-    _RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-    _OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
-    "_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    {
-        "application": str,
-    },
-)
-_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
-    "_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef(
-    _RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-    _OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-):
-    pass
-
-
-ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef = TypedDict(
-    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ResourceInfoTypeDef = TypedDict(
     "ResourceInfoTypeDef",
     {
         "name": str,
         "arn": str,
         "resourceType": ResourceTypeType,
         "resourceDetails": ResourceDetailsTypeDef,
@@ -766,15 +769,15 @@
     total=False,
 )
 
 GetConfigurationResponseTypeDef = TypedDict(
     "GetConfigurationResponseTypeDef",
     {
         "configuration": AppRegistryConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutConfigurationRequestRequestTypeDef = TypedDict(
     "PutConfigurationRequestRequestTypeDef",
     {
         "configuration": AppRegistryConfigurationTypeDef,
@@ -789,15 +792,15 @@
         "name": str,
         "description": str,
         "creationTime": datetime,
         "lastUpdateTime": datetime,
         "associatedResourceCount": int,
         "tags": Dict[str, str],
         "integrations": IntegrationsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
         "name": str,
@@ -809,18 +812,18 @@
 )
 
 ListAssociatedResourcesResponseTypeDef = TypedDict(
     "ListAssociatedResourcesResponseTypeDef",
     {
         "resources": List[ResourceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssociatedResourceResponseTypeDef = TypedDict(
     "GetAssociatedResourceResponseTypeDef",
     {
         "resource": ResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry/type_defs.pyi` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -23,68 +23,68 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagQueryConfigurationTypeDef",
     "ApplicationSummaryTypeDef",
     "ApplicationTypeDef",
     "AssociateAttributeGroupRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateAttributeGroupResponseTypeDef",
     "AssociateResourceRequestRequestTypeDef",
+    "AssociateResourceResponseTypeDef",
     "AttributeGroupDetailsTypeDef",
     "AttributeGroupSummaryTypeDef",
     "AttributeGroupTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "CreateAttributeGroupRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteAttributeGroupRequestRequestTypeDef",
     "DisassociateAttributeGroupRequestRequestTypeDef",
+    "DisassociateAttributeGroupResponseTypeDef",
     "DisassociateResourceRequestRequestTypeDef",
+    "DisassociateResourceResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetAssociatedResourceRequestRequestTypeDef",
     "GetAttributeGroupRequestRequestTypeDef",
+    "GetAttributeGroupResponseTypeDef",
     "ResourceGroupTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
     "ListAssociatedAttributeGroupsRequestRequestTypeDef",
+    "ListAssociatedAttributeGroupsResponseTypeDef",
+    "ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
     "ListAssociatedResourcesRequestRequestTypeDef",
+    "ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
     "ListAttributeGroupsForApplicationRequestRequestTypeDef",
+    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
     "ListAttributeGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "SyncResourceRequestRequestTypeDef",
+    "SyncResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateAttributeGroupRequestRequestTypeDef",
     "AppRegistryConfigurationTypeDef",
-    "AssociateAttributeGroupResponseTypeDef",
-    "AssociateResourceResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
     "DeleteApplicationResponseTypeDef",
-    "DisassociateAttributeGroupResponseTypeDef",
-    "DisassociateResourceResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAttributeGroupResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListAssociatedAttributeGroupsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SyncResourceResponseTypeDef",
+    "CreateApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
     "ListAttributeGroupsForApplicationResponseTypeDef",
     "DeleteAttributeGroupResponseTypeDef",
     "ListAttributeGroupsResponseTypeDef",
     "CreateAttributeGroupResponseTypeDef",
     "UpdateAttributeGroupResponseTypeDef",
     "IntegrationsTypeDef",
     "ResourceIntegrationsTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-    "ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    "ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
     "ResourceInfoTypeDef",
     "GetConfigurationResponseTypeDef",
     "PutConfigurationRequestRequestTypeDef",
     "GetApplicationResponseTypeDef",
     "ResourceTypeDef",
     "ListAssociatedResourcesResponseTypeDef",
     "GetAssociatedResourceResponseTypeDef",
@@ -129,53 +129,62 @@
     "AssociateAttributeGroupRequestRequestTypeDef",
     {
         "application": str,
         "attributeGroup": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateAttributeGroupResponseTypeDef = TypedDict(
+    "AssociateAttributeGroupResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationArn": str,
+        "attributeGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateResourceRequestRequestTypeDef = TypedDict(
     "AssociateResourceRequestRequestTypeDef",
     {
         "application": str,
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+AssociateResourceResponseTypeDef = TypedDict(
+    "AssociateResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttributeGroupDetailsTypeDef = TypedDict(
     "AttributeGroupDetailsTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
+        "createdBy": str,
     },
     total=False,
 )
 
 AttributeGroupSummaryTypeDef = TypedDict(
     "AttributeGroupSummaryTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "description": str,
         "creationTime": datetime,
         "lastUpdateTime": datetime,
+        "createdBy": str,
     },
     total=False,
 )
 
 AttributeGroupTypeDef = TypedDict(
     "AttributeGroupTypeDef",
     {
@@ -252,23 +261,48 @@
     "DisassociateAttributeGroupRequestRequestTypeDef",
     {
         "application": str,
         "attributeGroup": str,
     },
 )
 
+DisassociateAttributeGroupResponseTypeDef = TypedDict(
+    "DisassociateAttributeGroupResponseTypeDef",
+    {
+        "applicationArn": str,
+        "attributeGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateResourceRequestRequestTypeDef = TypedDict(
     "DisassociateResourceRequestRequestTypeDef",
     {
         "application": str,
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+DisassociateResourceResponseTypeDef = TypedDict(
+    "DisassociateResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetApplicationRequestRequestTypeDef = TypedDict(
     "GetApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 
@@ -284,43 +318,81 @@
 GetAttributeGroupRequestRequestTypeDef = TypedDict(
     "GetAttributeGroupRequestRequestTypeDef",
     {
         "attributeGroup": str,
     },
 )
 
+GetAttributeGroupResponseTypeDef = TypedDict(
+    "GetAttributeGroupResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "attributes": str,
+        "creationTime": datetime,
+        "lastUpdateTime": datetime,
+        "tags": Dict[str, str],
+        "createdBy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceGroupTypeDef = TypedDict(
     "ResourceGroupTypeDef",
     {
         "state": ResourceGroupStateType,
         "arn": str,
         "errorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
+        {
+            "application": str,
+        },
+    )
+)
+_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef(
+    _RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
+    _OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedAttributeGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedAttributeGroupsRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAssociatedAttributeGroupsRequestRequestTypeDef = TypedDict(
@@ -334,14 +406,43 @@
 
 class ListAssociatedAttributeGroupsRequestRequestTypeDef(
     _RequiredListAssociatedAttributeGroupsRequestRequestTypeDef,
     _OptionalListAssociatedAttributeGroupsRequestRequestTypeDef,
 ):
     pass
 
+ListAssociatedAttributeGroupsResponseTypeDef = TypedDict(
+    "ListAssociatedAttributeGroupsResponseTypeDef",
+    {
+        "attributeGroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
+    {
+        "application": str,
+    },
+)
+_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef(
+    _RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
+    _OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedResourcesRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAssociatedResourcesRequestRequestTypeDef = TypedDict(
@@ -355,14 +456,34 @@
 
 class ListAssociatedResourcesRequestRequestTypeDef(
     _RequiredListAssociatedResourcesRequestRequestTypeDef,
     _OptionalListAssociatedResourcesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
+    "_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
+    {
+        "application": str,
+    },
+)
+_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
+    "_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef(
+    _RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
+    _OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttributeGroupsForApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredListAttributeGroupsForApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalListAttributeGroupsForApplicationRequestRequestTypeDef = TypedDict(
@@ -376,14 +497,22 @@
 
 class ListAttributeGroupsForApplicationRequestRequestTypeDef(
     _RequiredListAttributeGroupsForApplicationRequestRequestTypeDef,
     _OptionalListAttributeGroupsForApplicationRequestRequestTypeDef,
 ):
     pass
 
+ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef = TypedDict(
+    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAttributeGroupsRequestRequestTypeDef = TypedDict(
     "ListAttributeGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -392,30 +521,69 @@
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
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "tagValue": str,
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
 SyncResourceRequestRequestTypeDef = TypedDict(
     "SyncResourceRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resource": str,
     },
 )
 
+SyncResourceResponseTypeDef = TypedDict(
+    "SyncResourceResponseTypeDef",
+    {
+        "applicationArn": str,
+        "resourceArn": str,
+        "actionTaken": SyncActionType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -474,171 +642,86 @@
     "AppRegistryConfigurationTypeDef",
     {
         "tagQueryConfiguration": TagQueryConfigurationTypeDef,
     },
     total=False,
 )
 
-AssociateAttributeGroupResponseTypeDef = TypedDict(
-    "AssociateAttributeGroupResponseTypeDef",
-    {
-        "applicationArn": str,
-        "attributeGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateResourceResponseTypeDef = TypedDict(
-    "AssociateResourceResponseTypeDef",
-    {
-        "applicationArn": str,
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeleteApplicationResponseTypeDef = TypedDict(
     "DeleteApplicationResponseTypeDef",
     {
         "application": ApplicationSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateAttributeGroupResponseTypeDef = TypedDict(
-    "DisassociateAttributeGroupResponseTypeDef",
-    {
-        "applicationArn": str,
-        "attributeGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateResourceResponseTypeDef = TypedDict(
-    "DisassociateResourceResponseTypeDef",
-    {
-        "applicationArn": str,
-        "resourceArn": str,
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
-GetAttributeGroupResponseTypeDef = TypedDict(
-    "GetAttributeGroupResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "name": str,
-        "description": str,
-        "attributes": str,
-        "creationTime": datetime,
-        "lastUpdateTime": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applications": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAssociatedAttributeGroupsResponseTypeDef = TypedDict(
-    "ListAssociatedAttributeGroupsResponseTypeDef",
-    {
-        "attributeGroups": List[str],
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
-SyncResourceResponseTypeDef = TypedDict(
-    "SyncResourceResponseTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "applicationArn": str,
-        "resourceArn": str,
-        "actionTaken": SyncActionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "application": ApplicationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttributeGroupsForApplicationResponseTypeDef = TypedDict(
     "ListAttributeGroupsForApplicationResponseTypeDef",
     {
         "attributeGroupsDetails": List[AttributeGroupDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAttributeGroupResponseTypeDef = TypedDict(
     "DeleteAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttributeGroupsResponseTypeDef = TypedDict(
     "ListAttributeGroupsResponseTypeDef",
     {
         "attributeGroups": List[AttributeGroupSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttributeGroupResponseTypeDef = TypedDict(
     "CreateAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAttributeGroupResponseTypeDef = TypedDict(
     "UpdateAttributeGroupResponseTypeDef",
     {
         "attributeGroup": AttributeGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntegrationsTypeDef = TypedDict(
     "IntegrationsTypeDef",
     {
         "resourceGroup": ResourceGroupTypeDef,
@@ -650,94 +733,14 @@
     "ResourceIntegrationsTypeDef",
     {
         "resourceGroup": ResourceGroupTypeDef,
     },
     total=False,
 )
 
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-        {
-            "application": str,
-        },
-    )
-)
-_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef(
-    _RequiredListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-    _OptionalListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    {
-        "application": str,
-    },
-)
-_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef(
-    _RequiredListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-    _OptionalListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
-    "_RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    {
-        "application": str,
-    },
-)
-_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef = TypedDict(
-    "_OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef(
-    _RequiredListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-    _OptionalListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-):
-    pass
-
-ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef = TypedDict(
-    "ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ResourceInfoTypeDef = TypedDict(
     "ResourceInfoTypeDef",
     {
         "name": str,
         "arn": str,
         "resourceType": ResourceTypeType,
         "resourceDetails": ResourceDetailsTypeDef,
@@ -745,15 +748,15 @@
     total=False,
 )
 
 GetConfigurationResponseTypeDef = TypedDict(
     "GetConfigurationResponseTypeDef",
     {
         "configuration": AppRegistryConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutConfigurationRequestRequestTypeDef = TypedDict(
     "PutConfigurationRequestRequestTypeDef",
     {
         "configuration": AppRegistryConfigurationTypeDef,
@@ -768,15 +771,15 @@
         "name": str,
         "description": str,
         "creationTime": datetime,
         "lastUpdateTime": datetime,
         "associatedResourceCount": int,
         "tags": Dict[str, str],
         "integrations": IntegrationsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
         "name": str,
@@ -788,18 +791,18 @@
 )
 
 ListAssociatedResourcesResponseTypeDef = TypedDict(
     "ListAssociatedResourcesResponseTypeDef",
     {
         "resources": List[ResourceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssociatedResourceResponseTypeDef = TypedDict(
     "GetAssociatedResourceResponseTypeDef",
     {
         "resource": ResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/PKG-INFO` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicecatalog-appregistry
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppRegistry 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppRegistry 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicecatalog-appregistry"></a>
 
 # types-aiobotocore-servicecatalog-appregistry
 
 [![PyPI - types-aiobotocore-servicecatalog-appregistry](https://img.shields.io/pypi/v/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicecatalog-appregistry.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicecatalog-appregistry)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicecatalog-appregistry?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicecatalog-appregistry)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRegistry 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
+[aiobotocore.AppRegistry 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicecatalog-appregistry.html#AppRegistry)
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
 [types-aiobotocore-servicecatalog-appregistry docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicecatalog_appregistry/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,68 +347,68 @@
 
 ```python
 from types_aiobotocore_servicecatalog_appregistry.type_defs import (
     TagQueryConfigurationTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     AssociateAttributeGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateAttributeGroupResponseTypeDef,
     AssociateResourceRequestRequestTypeDef,
+    AssociateResourceResponseTypeDef,
     AttributeGroupDetailsTypeDef,
     AttributeGroupSummaryTypeDef,
     AttributeGroupTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateAttributeGroupRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteAttributeGroupRequestRequestTypeDef,
     DisassociateAttributeGroupRequestRequestTypeDef,
+    DisassociateAttributeGroupResponseTypeDef,
     DisassociateResourceRequestRequestTypeDef,
+    DisassociateResourceResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetAssociatedResourceRequestRequestTypeDef,
     GetAttributeGroupRequestRequestTypeDef,
+    GetAttributeGroupResponseTypeDef,
     ResourceGroupTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
     ListAssociatedAttributeGroupsRequestRequestTypeDef,
+    ListAssociatedAttributeGroupsResponseTypeDef,
+    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
     ListAssociatedResourcesRequestRequestTypeDef,
+    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
     ListAttributeGroupsForApplicationRequestRequestTypeDef,
+    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ListAttributeGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     SyncResourceRequestRequestTypeDef,
+    SyncResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateAttributeGroupRequestRequestTypeDef,
     AppRegistryConfigurationTypeDef,
-    AssociateAttributeGroupResponseTypeDef,
-    AssociateResourceResponseTypeDef,
-    CreateApplicationResponseTypeDef,
     DeleteApplicationResponseTypeDef,
-    DisassociateAttributeGroupResponseTypeDef,
-    DisassociateResourceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributeGroupResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListAssociatedAttributeGroupsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SyncResourceResponseTypeDef,
+    CreateApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     ListAttributeGroupsForApplicationResponseTypeDef,
     DeleteAttributeGroupResponseTypeDef,
     ListAttributeGroupsResponseTypeDef,
     CreateAttributeGroupResponseTypeDef,
     UpdateAttributeGroupResponseTypeDef,
     IntegrationsTypeDef,
     ResourceIntegrationsTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListAssociatedAttributeGroupsRequestListAssociatedAttributeGroupsPaginateTypeDef,
-    ListAssociatedResourcesRequestListAssociatedResourcesPaginateTypeDef,
-    ListAttributeGroupsForApplicationRequestListAttributeGroupsForApplicationPaginateTypeDef,
-    ListAttributeGroupsRequestListAttributeGroupsPaginateTypeDef,
     ResourceInfoTypeDef,
     GetConfigurationResponseTypeDef,
     PutConfigurationRequestRequestTypeDef,
     GetApplicationResponseTypeDef,
     ResourceTypeDef,
     ListAssociatedResourcesResponseTypeDef,
     GetAssociatedResourceResponseTypeDef,
@@ -422,43 +422,43 @@
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

### Comparing `types-aiobotocore-servicecatalog-appregistry-2.5.0.post1/types_aiobotocore_servicecatalog_appregistry.egg-info/SOURCES.txt` & `types-aiobotocore-servicecatalog-appregistry-2.5.1/types_aiobotocore_servicecatalog_appregistry.egg-info/SOURCES.txt`

 * *Files identical despite different names*

