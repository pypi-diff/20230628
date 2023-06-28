# Comparing `tmp/types-aiobotocore-dax-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dax-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dax-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-dax-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-dax-2.5.0.post1.tar` & `types-aiobotocore-dax-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.547120 types-aiobotocore-dax-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16504 2023-03-11 12:26:29.547120 types-aiobotocore-dax-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14949 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.547120 types-aiobotocore-dax-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.539121 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/
--rw-r--r--   0 runner    (1001) docker     (123)     1941 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1940 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22015 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    21978 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9060 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9058 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9141 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9131 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22351 2023-03-11 12:12:18.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22328 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:16.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.547120 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16504 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:29.000000 types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.406123 types-aiobotocore-dax-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16492 2023-06-28 01:43:22.402123 types-aiobotocore-dax-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14943 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.406123 types-aiobotocore-dax-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.402123 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/
+-rw-r--r--   0 runner    (1001) docker     (123)     1941 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1940 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22015 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21978 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9269 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9267 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9035 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9026 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22407 2023-06-28 01:28:57.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22384 2023-06-28 01:28:57.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:56.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.402123 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16492 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:22.000000 types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dax-2.5.0.post1/LICENSE` & `types-aiobotocore-dax-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dax-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dax-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dax
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DAX 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DAX 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dax"></a>
 
 # types-aiobotocore-dax
 
 [![PyPI - types-aiobotocore-dax](https://img.shields.io/pypi/v/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dax?color=blue)](https://pypistats.org/packages/types-aiobotocore-dax)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DAX 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
+[aiobotocore.DAX 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
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
 [types-aiobotocore-dax docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,57 +355,57 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     ParameterGroupStatusTypeDef,
     SSEDescriptionTypeDef,
     SecurityGroupMembershipTypeDef,
     SSESpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     ParameterGroupTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
     DecreaseReplicationFactorRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
+    DeleteParameterGroupResponseTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteSubnetGroupResponseTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
     DescribeDefaultParametersRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     IncreaseReplicationFactorRequestRequestTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     NodeTypeSpecificValueTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RebootNodeRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SubnetTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     NodeTypeDef,
     CreateClusterRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    DeleteParameterGroupResponseTypeDef,
-    DeleteSubnetGroupResponseTypeDef,
     ListTagsResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
     DescribeEventsResponseTypeDef,
     ParameterTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
     SubnetGroupTypeDef,
     ClusterTypeDef,
     DescribeDefaultParametersResponseTypeDef,
     DescribeParametersResponseTypeDef,
@@ -429,43 +429,43 @@
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

### Comparing `types-aiobotocore-dax-2.5.0.post1/README.md` & `types-aiobotocore-dax-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-dax"></a>
 
 # types-aiobotocore-dax
 
 [![PyPI - types-aiobotocore-dax](https://img.shields.io/pypi/v/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dax?color=blue)](https://pypistats.org/packages/types-aiobotocore-dax)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DAX 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
+[aiobotocore.DAX 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
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
 [types-aiobotocore-dax docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,57 +322,57 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     ParameterGroupStatusTypeDef,
     SSEDescriptionTypeDef,
     SecurityGroupMembershipTypeDef,
     SSESpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     ParameterGroupTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
     DecreaseReplicationFactorRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
+    DeleteParameterGroupResponseTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteSubnetGroupResponseTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
     DescribeDefaultParametersRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     IncreaseReplicationFactorRequestRequestTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     NodeTypeSpecificValueTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RebootNodeRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SubnetTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     NodeTypeDef,
     CreateClusterRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    DeleteParameterGroupResponseTypeDef,
-    DeleteSubnetGroupResponseTypeDef,
     ListTagsResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
     DescribeEventsResponseTypeDef,
     ParameterTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
     SubnetGroupTypeDef,
     ClusterTypeDef,
     DescribeDefaultParametersResponseTypeDef,
     DescribeParametersResponseTypeDef,
@@ -396,43 +396,43 @@
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

### Comparing `types-aiobotocore-dax-2.5.0.post1/setup.py` & `types-aiobotocore-dax-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dax.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dax",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dax"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DAX 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.DAX 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/",
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

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__init__.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__init__.pyi` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/__main__.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/__main__.py`

 * *Files 8% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DAX 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DAX 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX\nOther"
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

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/client.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/client.pyi` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/literals.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/literals.py`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/literals.pyi` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/literals.pyi`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/paginator.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,17 +28,16 @@
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_parameter_groups_paginator: DescribeParameterGroupsPaginator = client.get_paginator("describe_parameter_groups")
         describe_parameters_paginator: DescribeParametersPaginator = client.get_paginator("describe_parameters")
         describe_subnet_groups_paginator: DescribeSubnetGroupsPaginator = client.get_paginator("describe_subnet_groups")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SourceTypeType
 from .type_defs import (
     DescribeClustersResponseTypeDef,
@@ -47,154 +46,139 @@
     DescribeParameterGroupsResponseTypeDef,
     DescribeParametersResponseTypeDef,
     DescribeSubnetGroupsResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeClustersPaginator",
     "DescribeDefaultParametersPaginator",
     "DescribeEventsPaginator",
     "DescribeParameterGroupsPaginator",
     "DescribeParametersPaginator",
     "DescribeSubnetGroupsPaginator",
     "ListTagsPaginator",
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
 class DescribeClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeclusterspaginator)
     """
 
     def paginate(
-        self, *, ClusterNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterNames: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeclusterspaginator)
         """
 
-
 class DescribeDefaultParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeDefaultParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describedefaultparameterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDefaultParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describedefaultparameterspaginator)
         """
 
-
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         SourceName: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeeventspaginator)
         """
 
-
 class DescribeParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparametergroupspaginator)
     """
 
     def paginate(
         self,
         *,
         ParameterGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParameterGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparametergroupspaginator)
         """
 
-
 class DescribeParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparameterspaginator)
     """
 
     def paginate(
         self,
         *,
         ParameterGroupName: str,
         Source: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparameterspaginator)
         """
 
-
 class DescribeSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describesubnetgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         SubnetGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describesubnetgroupspaginator)
         """
 
-
 class ListTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.ListTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#listtagspaginator)
     """
 
     def paginate(
-        self, *, ResourceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.ListTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#listtagspaginator)
         """
```

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/paginator.pyi` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -28,17 +28,16 @@
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_parameter_groups_paginator: DescribeParameterGroupsPaginator = client.get_paginator("describe_parameter_groups")
         describe_parameters_paginator: DescribeParametersPaginator = client.get_paginator("describe_parameters")
         describe_subnet_groups_paginator: DescribeSubnetGroupsPaginator = client.get_paginator("describe_subnet_groups")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SourceTypeType
 from .type_defs import (
     DescribeClustersResponseTypeDef,
@@ -47,144 +46,148 @@
     DescribeParameterGroupsResponseTypeDef,
     DescribeParametersResponseTypeDef,
     DescribeSubnetGroupsResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeClustersPaginator",
     "DescribeDefaultParametersPaginator",
     "DescribeEventsPaginator",
     "DescribeParameterGroupsPaginator",
     "DescribeParametersPaginator",
     "DescribeSubnetGroupsPaginator",
     "ListTagsPaginator",
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
 class DescribeClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeclusterspaginator)
     """
 
     def paginate(
-        self, *, ClusterNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterNames: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeclusterspaginator)
         """
 
+
 class DescribeDefaultParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeDefaultParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describedefaultparameterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDefaultParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describedefaultparameterspaginator)
         """
 
+
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         SourceName: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeeventspaginator)
         """
 
+
 class DescribeParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparametergroupspaginator)
     """
 
     def paginate(
         self,
         *,
         ParameterGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParameterGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparametergroupspaginator)
         """
 
+
 class DescribeParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparameterspaginator)
     """
 
     def paginate(
         self,
         *,
         ParameterGroupName: str,
         Source: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describeparameterspaginator)
         """
 
+
 class DescribeSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describesubnetgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         SubnetGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.DescribeSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#describesubnetgroupspaginator)
         """
 
+
 class ListTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.ListTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#listtagspaginator)
     """
 
     def paginate(
-        self, *, ResourceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX.Paginator.ListTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/paginators/#listtagspaginator)
         """
```

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/type_defs.py` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -25,66 +25,65 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "EndpointTypeDef",
     "NotificationConfigurationTypeDef",
     "ParameterGroupStatusTypeDef",
     "SSEDescriptionTypeDef",
     "SecurityGroupMembershipTypeDef",
     "SSESpecificationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateParameterGroupRequestRequestTypeDef",
     "ParameterGroupTypeDef",
     "CreateSubnetGroupRequestRequestTypeDef",
     "DecreaseReplicationFactorRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteParameterGroupRequestRequestTypeDef",
+    "DeleteParameterGroupResponseTypeDef",
     "DeleteSubnetGroupRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeleteSubnetGroupResponseTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
+    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
     "DescribeDefaultParametersRequestRequestTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "EventTypeDef",
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
     "DescribeParameterGroupsRequestRequestTypeDef",
+    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     "DescribeParametersRequestRequestTypeDef",
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeSubnetGroupsRequestRequestTypeDef",
     "IncreaseReplicationFactorRequestRequestTypeDef",
+    "ListTagsRequestListTagsPaginateTypeDef",
     "ListTagsRequestRequestTypeDef",
     "NodeTypeSpecificValueTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterNameValueTypeDef",
     "RebootNodeRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SubnetTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateClusterRequestRequestTypeDef",
     "UpdateSubnetGroupRequestRequestTypeDef",
     "NodeTypeDef",
     "CreateClusterRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "DeleteParameterGroupResponseTypeDef",
-    "DeleteSubnetGroupResponseTypeDef",
     "ListTagsResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "TagResourceResponseTypeDef",
     "UntagResourceResponseTypeDef",
     "CreateParameterGroupResponseTypeDef",
     "DescribeParameterGroupsResponseTypeDef",
     "UpdateParameterGroupResponseTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    "ListTagsRequestListTagsPaginateTypeDef",
     "DescribeEventsResponseTypeDef",
     "ParameterTypeDef",
     "UpdateParameterGroupRequestRequestTypeDef",
     "SubnetGroupTypeDef",
     "ClusterTypeDef",
     "DescribeDefaultParametersResponseTypeDef",
     "DescribeParametersResponseTypeDef",
@@ -158,47 +157,34 @@
     {
         "Key": str,
         "Value": str,
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
 _RequiredCreateParameterGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateParameterGroupRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalCreateParameterGroupRequestRequestTypeDef = TypedDict(
     "_OptionalCreateParameterGroupRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class CreateParameterGroupRequestRequestTypeDef(
     _RequiredCreateParameterGroupRequestRequestTypeDef,
     _OptionalCreateParameterGroupRequestRequestTypeDef,
 ):
     pass
 
-
 ParameterGroupTypeDef = TypedDict(
     "ParameterGroupTypeDef",
     {
         "ParameterGroupName": str,
         "Description": str,
     },
     total=False,
@@ -215,21 +201,19 @@
     "_OptionalCreateSubnetGroupRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class CreateSubnetGroupRequestRequestTypeDef(
     _RequiredCreateSubnetGroupRequestRequestTypeDef, _OptionalCreateSubnetGroupRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredDecreaseReplicationFactorRequestRequestTypeDef = TypedDict(
     "_RequiredDecreaseReplicationFactorRequestRequestTypeDef",
     {
         "ClusterName": str,
         "NewReplicationFactor": int,
     },
 )
@@ -238,72 +222,106 @@
     {
         "AvailabilityZones": Sequence[str],
         "NodeIdsToRemove": Sequence[str],
     },
     total=False,
 )
 
-
 class DecreaseReplicationFactorRequestRequestTypeDef(
     _RequiredDecreaseReplicationFactorRequestRequestTypeDef,
     _OptionalDecreaseReplicationFactorRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteClusterRequestRequestTypeDef = TypedDict(
     "DeleteClusterRequestRequestTypeDef",
     {
         "ClusterName": str,
     },
 )
 
 DeleteParameterGroupRequestRequestTypeDef = TypedDict(
     "DeleteParameterGroupRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 
+DeleteParameterGroupResponseTypeDef = TypedDict(
+    "DeleteParameterGroupResponseTypeDef",
+    {
+        "DeletionMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSubnetGroupRequestRequestTypeDef = TypedDict(
     "DeleteSubnetGroupRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeleteSubnetGroupResponseTypeDef = TypedDict(
+    "DeleteSubnetGroupResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DeletionMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "ClusterNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "ClusterNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef = TypedDict(
+    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDefaultParametersRequestRequestTypeDef = TypedDict(
     "DescribeDefaultParametersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "SourceName": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
         "SourceName": str,
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -321,24 +339,54 @@
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
     },
     total=False,
 )
 
+DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
+    {
+        "ParameterGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeParameterGroupsRequestRequestTypeDef = TypedDict(
     "DescribeParameterGroupsRequestRequestTypeDef",
     {
         "ParameterGroupNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+    },
+)
+_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeParametersRequestDescribeParametersPaginateTypeDef(
+    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
+    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeParametersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeParametersRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalDescribeParametersRequestRequestTypeDef = TypedDict(
@@ -347,21 +395,28 @@
         "Source": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeParametersRequestRequestTypeDef(
     _RequiredDescribeParametersRequestRequestTypeDef,
     _OptionalDescribeParametersRequestRequestTypeDef,
 ):
     pass
 
+DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
+    {
+        "SubnetGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeSubnetGroupsRequestRequestTypeDef = TypedDict(
     "DescribeSubnetGroupsRequestRequestTypeDef",
     {
         "SubnetGroupNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
@@ -380,21 +435,38 @@
     "_OptionalIncreaseReplicationFactorRequestRequestTypeDef",
     {
         "AvailabilityZones": Sequence[str],
     },
     total=False,
 )
 
-
 class IncreaseReplicationFactorRequestRequestTypeDef(
     _RequiredIncreaseReplicationFactorRequestRequestTypeDef,
     _OptionalIncreaseReplicationFactorRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_RequiredListTagsRequestListTagsPaginateTypeDef",
+    {
+        "ResourceName": str,
+    },
+)
+_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsRequestListTagsPaginateTypeDef(
+    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
+):
+    pass
 
 _RequiredListTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsRequestRequestTypeDef",
     {
         "ResourceName": str,
     },
 )
@@ -402,30 +474,38 @@
     "_OptionalListTagsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
-
 NodeTypeSpecificValueTypeDef = TypedDict(
     "NodeTypeSpecificValueTypeDef",
     {
         "NodeType": str,
         "Value": str,
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
 ParameterNameValueTypeDef = TypedDict(
     "ParameterNameValueTypeDef",
     {
         "ParameterName": str,
         "ParameterValue": str,
     },
     total=False,
@@ -435,14 +515,25 @@
     "RebootNodeRequestRequestTypeDef",
     {
         "ClusterName": str,
         "NodeId": str,
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
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
         "SubnetAvailabilityZone": str,
     },
     total=False,
@@ -471,21 +562,19 @@
         "NotificationTopicStatus": str,
         "ParameterGroupName": str,
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateClusterRequestRequestTypeDef(
     _RequiredUpdateClusterRequestRequestTypeDef, _OptionalUpdateClusterRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateSubnetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubnetGroupRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
     },
 )
 _OptionalUpdateSubnetGroupRequestRequestTypeDef = TypedDict(
@@ -493,21 +582,19 @@
     {
         "Description": str,
         "SubnetIds": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateSubnetGroupRequestRequestTypeDef(
     _RequiredUpdateSubnetGroupRequestRequestTypeDef, _OptionalUpdateSubnetGroupRequestRequestTypeDef
 ):
     pass
 
-
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "NodeId": str,
         "Endpoint": EndpointTypeDef,
         "NodeCreateTime": datetime,
         "AvailabilityZone": str,
@@ -539,193 +626,83 @@
         "Tags": Sequence[TagTypeDef],
         "SSESpecification": SSESpecificationTypeDef,
         "ClusterEndpointEncryptionType": ClusterEndpointEncryptionTypeType,
     },
     total=False,
 )
 
-
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
 ):
     pass
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceName": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-DeleteParameterGroupResponseTypeDef = TypedDict(
-    "DeleteParameterGroupResponseTypeDef",
-    {
-        "DeletionMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSubnetGroupResponseTypeDef = TypedDict(
-    "DeleteSubnetGroupResponseTypeDef",
-    {
-        "DeletionMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 TagResourceResponseTypeDef = TypedDict(
     "TagResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResponseTypeDef = TypedDict(
     "UntagResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateParameterGroupResponseTypeDef = TypedDict(
     "CreateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParameterGroupsResponseTypeDef = TypedDict(
     "DescribeParameterGroupsResponseTypeDef",
     {
         "NextToken": str,
         "ParameterGroups": List[ParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateParameterGroupResponseTypeDef = TypedDict(
     "UpdateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "ClusterNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef = TypedDict(
-    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "SourceName": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    {
-        "ParameterGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-    },
-)
-_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeParametersRequestDescribeParametersPaginateTypeDef(
-    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
-    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    {
-        "SubnetGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_RequiredListTagsRequestListTagsPaginateTypeDef",
-    {
-        "ResourceName": str,
-    },
-)
-_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_OptionalListTagsRequestListTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsRequestListTagsPaginateTypeDef(
-    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
-):
-    pass
-
-
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "NextToken": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParameterTypeDef = TypedDict(
     "ParameterTypeDef",
     {
         "ParameterName": str,
@@ -787,101 +764,101 @@
 )
 
 DescribeDefaultParametersResponseTypeDef = TypedDict(
     "DescribeDefaultParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResponseTypeDef = TypedDict(
     "DescribeParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSubnetGroupResponseTypeDef = TypedDict(
     "CreateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeSubnetGroupsResponseTypeDef",
     {
         "NextToken": str,
         "SubnetGroups": List[SubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubnetGroupResponseTypeDef = TypedDict(
     "UpdateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseReplicationFactorResponseTypeDef = TypedDict(
     "DecreaseReplicationFactorResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "NextToken": str,
         "Clusters": List[ClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseReplicationFactorResponseTypeDef = TypedDict(
     "IncreaseReplicationFactorResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootNodeResponseTypeDef = TypedDict(
     "RebootNodeResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax/type_defs.pyi` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -25,65 +25,66 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "EndpointTypeDef",
     "NotificationConfigurationTypeDef",
     "ParameterGroupStatusTypeDef",
     "SSEDescriptionTypeDef",
     "SecurityGroupMembershipTypeDef",
     "SSESpecificationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateParameterGroupRequestRequestTypeDef",
     "ParameterGroupTypeDef",
     "CreateSubnetGroupRequestRequestTypeDef",
     "DecreaseReplicationFactorRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteParameterGroupRequestRequestTypeDef",
+    "DeleteParameterGroupResponseTypeDef",
     "DeleteSubnetGroupRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeleteSubnetGroupResponseTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
+    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
     "DescribeDefaultParametersRequestRequestTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "EventTypeDef",
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
     "DescribeParameterGroupsRequestRequestTypeDef",
+    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     "DescribeParametersRequestRequestTypeDef",
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeSubnetGroupsRequestRequestTypeDef",
     "IncreaseReplicationFactorRequestRequestTypeDef",
+    "ListTagsRequestListTagsPaginateTypeDef",
     "ListTagsRequestRequestTypeDef",
     "NodeTypeSpecificValueTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterNameValueTypeDef",
     "RebootNodeRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SubnetTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateClusterRequestRequestTypeDef",
     "UpdateSubnetGroupRequestRequestTypeDef",
     "NodeTypeDef",
     "CreateClusterRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "DeleteParameterGroupResponseTypeDef",
-    "DeleteSubnetGroupResponseTypeDef",
     "ListTagsResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "TagResourceResponseTypeDef",
     "UntagResourceResponseTypeDef",
     "CreateParameterGroupResponseTypeDef",
     "DescribeParameterGroupsResponseTypeDef",
     "UpdateParameterGroupResponseTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    "ListTagsRequestListTagsPaginateTypeDef",
     "DescribeEventsResponseTypeDef",
     "ParameterTypeDef",
     "UpdateParameterGroupRequestRequestTypeDef",
     "SubnetGroupTypeDef",
     "ClusterTypeDef",
     "DescribeDefaultParametersResponseTypeDef",
     "DescribeParametersResponseTypeDef",
@@ -157,45 +158,36 @@
     {
         "Key": str,
         "Value": str,
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
 _RequiredCreateParameterGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateParameterGroupRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalCreateParameterGroupRequestRequestTypeDef = TypedDict(
     "_OptionalCreateParameterGroupRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class CreateParameterGroupRequestRequestTypeDef(
     _RequiredCreateParameterGroupRequestRequestTypeDef,
     _OptionalCreateParameterGroupRequestRequestTypeDef,
 ):
     pass
 
+
 ParameterGroupTypeDef = TypedDict(
     "ParameterGroupTypeDef",
     {
         "ParameterGroupName": str,
         "Description": str,
     },
     total=False,
@@ -212,19 +204,21 @@
     "_OptionalCreateSubnetGroupRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class CreateSubnetGroupRequestRequestTypeDef(
     _RequiredCreateSubnetGroupRequestRequestTypeDef, _OptionalCreateSubnetGroupRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredDecreaseReplicationFactorRequestRequestTypeDef = TypedDict(
     "_RequiredDecreaseReplicationFactorRequestRequestTypeDef",
     {
         "ClusterName": str,
         "NewReplicationFactor": int,
     },
 )
@@ -233,70 +227,108 @@
     {
         "AvailabilityZones": Sequence[str],
         "NodeIdsToRemove": Sequence[str],
     },
     total=False,
 )
 
+
 class DecreaseReplicationFactorRequestRequestTypeDef(
     _RequiredDecreaseReplicationFactorRequestRequestTypeDef,
     _OptionalDecreaseReplicationFactorRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteClusterRequestRequestTypeDef = TypedDict(
     "DeleteClusterRequestRequestTypeDef",
     {
         "ClusterName": str,
     },
 )
 
 DeleteParameterGroupRequestRequestTypeDef = TypedDict(
     "DeleteParameterGroupRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 
+DeleteParameterGroupResponseTypeDef = TypedDict(
+    "DeleteParameterGroupResponseTypeDef",
+    {
+        "DeletionMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSubnetGroupRequestRequestTypeDef = TypedDict(
     "DeleteSubnetGroupRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeleteSubnetGroupResponseTypeDef = TypedDict(
+    "DeleteSubnetGroupResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DeletionMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "ClusterNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "ClusterNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef = TypedDict(
+    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDefaultParametersRequestRequestTypeDef = TypedDict(
     "DescribeDefaultParametersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "SourceName": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
         "SourceName": str,
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -314,24 +346,56 @@
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
     },
     total=False,
 )
 
+DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
+    {
+        "ParameterGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeParameterGroupsRequestRequestTypeDef = TypedDict(
     "DescribeParameterGroupsRequestRequestTypeDef",
     {
         "ParameterGroupNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+    },
+)
+_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeParametersRequestDescribeParametersPaginateTypeDef(
+    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
+    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeParametersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeParametersRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalDescribeParametersRequestRequestTypeDef = TypedDict(
@@ -340,20 +404,31 @@
         "Source": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeParametersRequestRequestTypeDef(
     _RequiredDescribeParametersRequestRequestTypeDef,
     _OptionalDescribeParametersRequestRequestTypeDef,
 ):
     pass
 
+
+DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
+    {
+        "SubnetGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSubnetGroupsRequestRequestTypeDef = TypedDict(
     "DescribeSubnetGroupsRequestRequestTypeDef",
     {
         "SubnetGroupNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -371,48 +446,83 @@
     "_OptionalIncreaseReplicationFactorRequestRequestTypeDef",
     {
         "AvailabilityZones": Sequence[str],
     },
     total=False,
 )
 
+
 class IncreaseReplicationFactorRequestRequestTypeDef(
     _RequiredIncreaseReplicationFactorRequestRequestTypeDef,
     _OptionalIncreaseReplicationFactorRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_RequiredListTagsRequestListTagsPaginateTypeDef",
+    {
+        "ResourceName": str,
+    },
+)
+_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsRequestListTagsPaginateTypeDef(
+    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
+):
+    pass
+
+
 _RequiredListTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsRequestRequestTypeDef",
     {
         "ResourceName": str,
     },
 )
 _OptionalListTagsRequestRequestTypeDef = TypedDict(
     "_OptionalListTagsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
+
 NodeTypeSpecificValueTypeDef = TypedDict(
     "NodeTypeSpecificValueTypeDef",
     {
         "NodeType": str,
         "Value": str,
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
 ParameterNameValueTypeDef = TypedDict(
     "ParameterNameValueTypeDef",
     {
         "ParameterName": str,
         "ParameterValue": str,
     },
     total=False,
@@ -422,14 +532,25 @@
     "RebootNodeRequestRequestTypeDef",
     {
         "ClusterName": str,
         "NodeId": str,
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
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
         "SubnetAvailabilityZone": str,
     },
     total=False,
@@ -458,19 +579,21 @@
         "NotificationTopicStatus": str,
         "ParameterGroupName": str,
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateClusterRequestRequestTypeDef(
     _RequiredUpdateClusterRequestRequestTypeDef, _OptionalUpdateClusterRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateSubnetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubnetGroupRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
     },
 )
 _OptionalUpdateSubnetGroupRequestRequestTypeDef = TypedDict(
@@ -478,19 +601,21 @@
     {
         "Description": str,
         "SubnetIds": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateSubnetGroupRequestRequestTypeDef(
     _RequiredUpdateSubnetGroupRequestRequestTypeDef, _OptionalUpdateSubnetGroupRequestRequestTypeDef
 ):
     pass
 
+
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "NodeId": str,
         "Endpoint": EndpointTypeDef,
         "NodeCreateTime": datetime,
         "AvailabilityZone": str,
@@ -522,187 +647,85 @@
         "Tags": Sequence[TagTypeDef],
         "SSESpecification": SSESpecificationTypeDef,
         "ClusterEndpointEncryptionType": ClusterEndpointEncryptionTypeType,
     },
     total=False,
 )
 
+
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceName": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-DeleteParameterGroupResponseTypeDef = TypedDict(
-    "DeleteParameterGroupResponseTypeDef",
-    {
-        "DeletionMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSubnetGroupResponseTypeDef = TypedDict(
-    "DeleteSubnetGroupResponseTypeDef",
-    {
-        "DeletionMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
+    {
+        "ResourceName": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 TagResourceResponseTypeDef = TypedDict(
     "TagResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResponseTypeDef = TypedDict(
     "UntagResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateParameterGroupResponseTypeDef = TypedDict(
     "CreateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParameterGroupsResponseTypeDef = TypedDict(
     "DescribeParameterGroupsResponseTypeDef",
     {
         "NextToken": str,
         "ParameterGroups": List[ParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateParameterGroupResponseTypeDef = TypedDict(
     "UpdateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "ClusterNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef = TypedDict(
-    "DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "SourceName": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    {
-        "ParameterGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-    },
-)
-_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeParametersRequestDescribeParametersPaginateTypeDef(
-    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
-    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
-):
-    pass
-
-DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    {
-        "SubnetGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_RequiredListTagsRequestListTagsPaginateTypeDef",
-    {
-        "ResourceName": str,
-    },
-)
-_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_OptionalListTagsRequestListTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsRequestListTagsPaginateTypeDef(
-    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
-):
-    pass
-
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "NextToken": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParameterTypeDef = TypedDict(
     "ParameterTypeDef",
     {
         "ParameterName": str,
@@ -764,101 +787,101 @@
 )
 
 DescribeDefaultParametersResponseTypeDef = TypedDict(
     "DescribeDefaultParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResponseTypeDef = TypedDict(
     "DescribeParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSubnetGroupResponseTypeDef = TypedDict(
     "CreateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeSubnetGroupsResponseTypeDef",
     {
         "NextToken": str,
         "SubnetGroups": List[SubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubnetGroupResponseTypeDef = TypedDict(
     "UpdateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseReplicationFactorResponseTypeDef = TypedDict(
     "DecreaseReplicationFactorResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "NextToken": str,
         "Clusters": List[ClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseReplicationFactorResponseTypeDef = TypedDict(
     "IncreaseReplicationFactorResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootNodeResponseTypeDef = TypedDict(
     "RebootNodeResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/PKG-INFO` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dax
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DAX 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DAX 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dax"></a>
 
 # types-aiobotocore-dax
 
 [![PyPI - types-aiobotocore-dax](https://img.shields.io/pypi/v/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dax.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dax)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dax?color=blue)](https://pypistats.org/packages/types-aiobotocore-dax)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DAX 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
+[aiobotocore.DAX 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dax.html#DAX)
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
 [types-aiobotocore-dax docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dax/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,57 +355,57 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     ParameterGroupStatusTypeDef,
     SSEDescriptionTypeDef,
     SecurityGroupMembershipTypeDef,
     SSESpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     ParameterGroupTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
     DecreaseReplicationFactorRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
+    DeleteParameterGroupResponseTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteSubnetGroupResponseTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
     DescribeDefaultParametersRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     IncreaseReplicationFactorRequestRequestTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     NodeTypeSpecificValueTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RebootNodeRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SubnetTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     NodeTypeDef,
     CreateClusterRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    DeleteParameterGroupResponseTypeDef,
-    DeleteSubnetGroupResponseTypeDef,
     ListTagsResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeDefaultParametersRequestDescribeDefaultParametersPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
     DescribeEventsResponseTypeDef,
     ParameterTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
     SubnetGroupTypeDef,
     ClusterTypeDef,
     DescribeDefaultParametersResponseTypeDef,
     DescribeParametersResponseTypeDef,
@@ -429,43 +429,43 @@
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

### Comparing `types-aiobotocore-dax-2.5.0.post1/types_aiobotocore_dax.egg-info/SOURCES.txt` & `types-aiobotocore-dax-2.5.1/types_aiobotocore_dax.egg-info/SOURCES.txt`

 * *Files identical despite different names*

