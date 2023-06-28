# Comparing `tmp/types-aiobotocore-docdb-elastic-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-docdb-elastic-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-docdb-elastic-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:31 2023, max compression
+gzip compressed data, was "types-aiobotocore-docdb-elastic-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1.tar` & `types-aiobotocore-docdb-elastic-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.875145 types-aiobotocore-docdb-elastic-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14531 2023-03-11 12:26:31.875145 types-aiobotocore-docdb-elastic-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12937 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:31.875145 types-aiobotocore-docdb-elastic-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2165 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.863145 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/
--rw-r--r--   0 runner    (1001) docker     (123)      898 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      897 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14230 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14206 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7943 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7941 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3338 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10287 2023-03-11 12:12:42.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10278 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.875145 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14531 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.222127 types-aiobotocore-docdb-elastic-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14529 2023-06-28 01:43:24.222127 types-aiobotocore-docdb-elastic-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12941 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.222127 types-aiobotocore-docdb-elastic-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.222127 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/
+-rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      897 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14230 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14206 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8152 2023-06-28 01:29:20.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8150 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3222 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3218 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10313 2023-06-28 01:29:21.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10304 2023-06-28 01:29:20.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.222127 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14529 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/LICENSE` & `types-aiobotocore-docdb-elastic-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/PKG-INFO` & `types-aiobotocore-docdb-elastic-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-docdb-elastic
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DocDBElastic 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DocDBElastic 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-docdb-elastic"></a>
 
 # types-aiobotocore-docdb-elastic
 
 [![PyPI - types-aiobotocore-docdb-elastic](https://img.shields.io/pypi/v/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb-elastic?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb-elastic)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDBElastic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
+[aiobotocore.DocDBElastic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
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
 [types-aiobotocore-docdb-elastic docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,84 +327,84 @@
 ```python
 from types_aiobotocore_docdb_elastic.type_defs import (
     ClusterInListTypeDef,
     ClusterSnapshotInListTypeDef,
     ClusterSnapshotTypeDef,
     ClusterTypeDef,
     CreateClusterInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateClusterSnapshotInputRequestTypeDef,
     DeleteClusterInputRequestTypeDef,
     DeleteClusterSnapshotInputRequestTypeDef,
     GetClusterInputRequestTypeDef,
     GetClusterSnapshotInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
     ListClusterSnapshotsInputRequestTypeDef,
+    ListClustersInputListClustersPaginateTypeDef,
     ListClustersInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreClusterFromSnapshotInputRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterInputRequestTypeDef,
-    CreateClusterOutputTypeDef,
+    ListClustersOutputTypeDef,
+    ListClusterSnapshotsOutputTypeDef,
     CreateClusterSnapshotOutputTypeDef,
-    DeleteClusterOutputTypeDef,
     DeleteClusterSnapshotOutputTypeDef,
-    GetClusterOutputTypeDef,
     GetClusterSnapshotOutputTypeDef,
-    ListClusterSnapshotsOutputTypeDef,
-    ListClustersOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    CreateClusterOutputTypeDef,
+    DeleteClusterOutputTypeDef,
+    GetClusterOutputTypeDef,
     RestoreClusterFromSnapshotOutputTypeDef,
     UpdateClusterOutputTypeDef,
-    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
-    ListClustersInputListClustersPaginateTypeDef,
 )
 
 
 def get_structure() -> ClusterInListTypeDef:
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/README.md` & `types-aiobotocore-docdb-elastic-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-docdb-elastic"></a>
 
 # types-aiobotocore-docdb-elastic
 
 [![PyPI - types-aiobotocore-docdb-elastic](https://img.shields.io/pypi/v/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb-elastic?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb-elastic)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDBElastic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
+[aiobotocore.DocDBElastic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
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
 [types-aiobotocore-docdb-elastic docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,84 +294,84 @@
 ```python
 from types_aiobotocore_docdb_elastic.type_defs import (
     ClusterInListTypeDef,
     ClusterSnapshotInListTypeDef,
     ClusterSnapshotTypeDef,
     ClusterTypeDef,
     CreateClusterInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateClusterSnapshotInputRequestTypeDef,
     DeleteClusterInputRequestTypeDef,
     DeleteClusterSnapshotInputRequestTypeDef,
     GetClusterInputRequestTypeDef,
     GetClusterSnapshotInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
     ListClusterSnapshotsInputRequestTypeDef,
+    ListClustersInputListClustersPaginateTypeDef,
     ListClustersInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreClusterFromSnapshotInputRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterInputRequestTypeDef,
-    CreateClusterOutputTypeDef,
+    ListClustersOutputTypeDef,
+    ListClusterSnapshotsOutputTypeDef,
     CreateClusterSnapshotOutputTypeDef,
-    DeleteClusterOutputTypeDef,
     DeleteClusterSnapshotOutputTypeDef,
-    GetClusterOutputTypeDef,
     GetClusterSnapshotOutputTypeDef,
-    ListClusterSnapshotsOutputTypeDef,
-    ListClustersOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    CreateClusterOutputTypeDef,
+    DeleteClusterOutputTypeDef,
+    GetClusterOutputTypeDef,
     RestoreClusterFromSnapshotOutputTypeDef,
     UpdateClusterOutputTypeDef,
-    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
-    ListClustersInputListClustersPaginateTypeDef,
 )
 
 
 def get_structure() -> ClusterInListTypeDef:
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/setup.py` & `types-aiobotocore-docdb-elastic-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-docdb-elastic.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-docdb-elastic",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_docdb_elastic"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DocDBElastic 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DocDBElastic 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/"
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__init__.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__init__.pyi` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/__main__.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DocDBElastic 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DocDBElastic 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic\nOther"
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/client.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/client.pyi` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/literals.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/literals.py`

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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/literals.pyi` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -102,14 +102,15 @@
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
@@ -188,14 +189,15 @@
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
@@ -206,14 +208,15 @@
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
@@ -249,14 +252,15 @@
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
@@ -275,16 +279,19 @@
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
@@ -368,15 +375,17 @@
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/paginator.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("docdb-elastic") as client:
         client: DocDBElasticClient
 
         list_cluster_snapshots_paginator: ListClusterSnapshotsPaginator = client.get_paginator("list_cluster_snapshots")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListClusterSnapshotsOutputTypeDef,
     ListClustersOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListClusterSnapshotsPaginator", "ListClustersPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,28 +49,28 @@
 class ListClusterSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusterSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclustersnapshotspaginator)
     """
 
     def paginate(
-        self, *, clusterArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClusterSnapshotsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclustersnapshotspaginator)
         """
 
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclusterspaginator)
         """
```

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/paginator.pyi` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("docdb-elastic") as client:
         client: DocDBElasticClient
 
         list_cluster_snapshots_paginator: ListClusterSnapshotsPaginator = client.get_paginator("list_cluster_snapshots")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListClusterSnapshotsOutputTypeDef,
     ListClustersOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListClusterSnapshotsPaginator", "ListClustersPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,27 +46,27 @@
 class ListClusterSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusterSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclustersnapshotspaginator)
     """
 
     def paginate(
-        self, *, clusterArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, clusterArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClusterSnapshotsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclustersnapshotspaginator)
         """
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/paginators/#listclusterspaginator)
         """
```

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/type_defs.py` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -17,48 +17,47 @@
 from .literals import AuthType, StatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ClusterInListTypeDef",
     "ClusterSnapshotInListTypeDef",
     "ClusterSnapshotTypeDef",
     "ClusterTypeDef",
     "CreateClusterInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateClusterSnapshotInputRequestTypeDef",
     "DeleteClusterInputRequestTypeDef",
     "DeleteClusterSnapshotInputRequestTypeDef",
     "GetClusterInputRequestTypeDef",
     "GetClusterSnapshotInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
     "ListClusterSnapshotsInputRequestTypeDef",
+    "ListClustersInputListClustersPaginateTypeDef",
     "ListClustersInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreClusterFromSnapshotInputRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateClusterInputRequestTypeDef",
-    "CreateClusterOutputTypeDef",
+    "ListClustersOutputTypeDef",
+    "ListClusterSnapshotsOutputTypeDef",
     "CreateClusterSnapshotOutputTypeDef",
-    "DeleteClusterOutputTypeDef",
     "DeleteClusterSnapshotOutputTypeDef",
-    "GetClusterOutputTypeDef",
     "GetClusterSnapshotOutputTypeDef",
-    "ListClusterSnapshotsOutputTypeDef",
-    "ListClustersOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "CreateClusterOutputTypeDef",
+    "DeleteClusterOutputTypeDef",
+    "GetClusterOutputTypeDef",
     "RestoreClusterFromSnapshotOutputTypeDef",
     "UpdateClusterOutputTypeDef",
-    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
-    "ListClustersInputListClustersPaginateTypeDef",
 )
 
 ClusterInListTypeDef = TypedDict(
     "ClusterInListTypeDef",
     {
         "clusterArn": str,
         "clusterName": str,
@@ -132,32 +131,19 @@
         "subnetIds": Sequence[str],
         "tags": Mapping[str, str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class CreateClusterInputRequestTypeDef(
     _RequiredCreateClusterInputRequestTypeDef, _OptionalCreateClusterInputRequestTypeDef
 ):
     pass
 
-
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
 _RequiredCreateClusterSnapshotInputRequestTypeDef = TypedDict(
     "_RequiredCreateClusterSnapshotInputRequestTypeDef",
     {
         "clusterArn": str,
         "snapshotName": str,
     },
 )
@@ -165,22 +151,20 @@
     "_OptionalCreateClusterSnapshotInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateClusterSnapshotInputRequestTypeDef(
     _RequiredCreateClusterSnapshotInputRequestTypeDef,
     _OptionalCreateClusterSnapshotInputRequestTypeDef,
 ):
     pass
 
-
 DeleteClusterInputRequestTypeDef = TypedDict(
     "DeleteClusterInputRequestTypeDef",
     {
         "clusterArn": str,
     },
 )
 
@@ -201,34 +185,41 @@
 GetClusterSnapshotInputRequestTypeDef = TypedDict(
     "GetClusterSnapshotInputRequestTypeDef",
     {
         "snapshotArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef = TypedDict(
+    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "clusterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListClusterSnapshotsInputRequestTypeDef = TypedDict(
     "ListClusterSnapshotsInputRequestTypeDef",
     {
         "clusterArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListClustersInputListClustersPaginateTypeDef = TypedDict(
+    "ListClustersInputListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersInputRequestTypeDef = TypedDict(
     "ListClustersInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -237,14 +228,43 @@
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
 _RequiredRestoreClusterFromSnapshotInputRequestTypeDef = TypedDict(
     "_RequiredRestoreClusterFromSnapshotInputRequestTypeDef",
     {
         "clusterName": str,
         "snapshotArn": str,
     },
 )
@@ -255,22 +275,20 @@
         "subnetIds": Sequence[str],
         "tags": Mapping[str, str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class RestoreClusterFromSnapshotInputRequestTypeDef(
     _RequiredRestoreClusterFromSnapshotInputRequestTypeDef,
     _OptionalRestoreClusterFromSnapshotInputRequestTypeDef,
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -300,120 +318,93 @@
         "shardCount": int,
         "subnetIds": Sequence[str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateClusterInputRequestTypeDef(
     _RequiredUpdateClusterInputRequestTypeDef, _OptionalUpdateClusterInputRequestTypeDef
 ):
     pass
 
-
-CreateClusterOutputTypeDef = TypedDict(
-    "CreateClusterOutputTypeDef",
+ListClustersOutputTypeDef = TypedDict(
+    "ListClustersOutputTypeDef",
     {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clusters": List[ClusterInListTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateClusterSnapshotOutputTypeDef = TypedDict(
-    "CreateClusterSnapshotOutputTypeDef",
+ListClusterSnapshotsOutputTypeDef = TypedDict(
+    "ListClusterSnapshotsOutputTypeDef",
     {
-        "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "snapshots": List[ClusterSnapshotInListTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteClusterOutputTypeDef = TypedDict(
-    "DeleteClusterOutputTypeDef",
+CreateClusterSnapshotOutputTypeDef = TypedDict(
+    "CreateClusterSnapshotOutputTypeDef",
     {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "snapshot": ClusterSnapshotTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterSnapshotOutputTypeDef = TypedDict(
     "DeleteClusterSnapshotOutputTypeDef",
     {
         "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetClusterOutputTypeDef = TypedDict(
-    "GetClusterOutputTypeDef",
-    {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClusterSnapshotOutputTypeDef = TypedDict(
     "GetClusterSnapshotOutputTypeDef",
     {
         "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListClusterSnapshotsOutputTypeDef = TypedDict(
-    "ListClusterSnapshotsOutputTypeDef",
+CreateClusterOutputTypeDef = TypedDict(
+    "CreateClusterOutputTypeDef",
     {
-        "nextToken": str,
-        "snapshots": List[ClusterSnapshotInListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListClustersOutputTypeDef = TypedDict(
-    "ListClustersOutputTypeDef",
+DeleteClusterOutputTypeDef = TypedDict(
+    "DeleteClusterOutputTypeDef",
     {
-        "clusters": List[ClusterInListTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+GetClusterOutputTypeDef = TypedDict(
+    "GetClusterOutputTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreClusterFromSnapshotOutputTypeDef = TypedDict(
     "RestoreClusterFromSnapshotOutputTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterOutputTypeDef = TypedDict(
     "UpdateClusterOutputTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef = TypedDict(
-    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
-    {
-        "clusterArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListClustersInputListClustersPaginateTypeDef = TypedDict(
-    "ListClustersInputListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
```

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic/type_defs.pyi` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -17,47 +17,48 @@
 from .literals import AuthType, StatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ClusterInListTypeDef",
     "ClusterSnapshotInListTypeDef",
     "ClusterSnapshotTypeDef",
     "ClusterTypeDef",
     "CreateClusterInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateClusterSnapshotInputRequestTypeDef",
     "DeleteClusterInputRequestTypeDef",
     "DeleteClusterSnapshotInputRequestTypeDef",
     "GetClusterInputRequestTypeDef",
     "GetClusterSnapshotInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
     "ListClusterSnapshotsInputRequestTypeDef",
+    "ListClustersInputListClustersPaginateTypeDef",
     "ListClustersInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreClusterFromSnapshotInputRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateClusterInputRequestTypeDef",
-    "CreateClusterOutputTypeDef",
+    "ListClustersOutputTypeDef",
+    "ListClusterSnapshotsOutputTypeDef",
     "CreateClusterSnapshotOutputTypeDef",
-    "DeleteClusterOutputTypeDef",
     "DeleteClusterSnapshotOutputTypeDef",
-    "GetClusterOutputTypeDef",
     "GetClusterSnapshotOutputTypeDef",
-    "ListClusterSnapshotsOutputTypeDef",
-    "ListClustersOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "CreateClusterOutputTypeDef",
+    "DeleteClusterOutputTypeDef",
+    "GetClusterOutputTypeDef",
     "RestoreClusterFromSnapshotOutputTypeDef",
     "UpdateClusterOutputTypeDef",
-    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
-    "ListClustersInputListClustersPaginateTypeDef",
 )
 
 ClusterInListTypeDef = TypedDict(
     "ClusterInListTypeDef",
     {
         "clusterArn": str,
         "clusterName": str,
@@ -131,29 +132,20 @@
         "subnetIds": Sequence[str],
         "tags": Mapping[str, str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class CreateClusterInputRequestTypeDef(
     _RequiredCreateClusterInputRequestTypeDef, _OptionalCreateClusterInputRequestTypeDef
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
 
 _RequiredCreateClusterSnapshotInputRequestTypeDef = TypedDict(
     "_RequiredCreateClusterSnapshotInputRequestTypeDef",
     {
         "clusterArn": str,
         "snapshotName": str,
     },
@@ -162,20 +154,22 @@
     "_OptionalCreateClusterSnapshotInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateClusterSnapshotInputRequestTypeDef(
     _RequiredCreateClusterSnapshotInputRequestTypeDef,
     _OptionalCreateClusterSnapshotInputRequestTypeDef,
 ):
     pass
 
+
 DeleteClusterInputRequestTypeDef = TypedDict(
     "DeleteClusterInputRequestTypeDef",
     {
         "clusterArn": str,
     },
 )
 
@@ -196,34 +190,41 @@
 GetClusterSnapshotInputRequestTypeDef = TypedDict(
     "GetClusterSnapshotInputRequestTypeDef",
     {
         "snapshotArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef = TypedDict(
+    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "clusterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListClusterSnapshotsInputRequestTypeDef = TypedDict(
     "ListClusterSnapshotsInputRequestTypeDef",
     {
         "clusterArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListClustersInputListClustersPaginateTypeDef = TypedDict(
+    "ListClustersInputListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersInputRequestTypeDef = TypedDict(
     "ListClustersInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -232,14 +233,43 @@
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
 _RequiredRestoreClusterFromSnapshotInputRequestTypeDef = TypedDict(
     "_RequiredRestoreClusterFromSnapshotInputRequestTypeDef",
     {
         "clusterName": str,
         "snapshotArn": str,
     },
 )
@@ -250,20 +280,22 @@
         "subnetIds": Sequence[str],
         "tags": Mapping[str, str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class RestoreClusterFromSnapshotInputRequestTypeDef(
     _RequiredRestoreClusterFromSnapshotInputRequestTypeDef,
     _OptionalRestoreClusterFromSnapshotInputRequestTypeDef,
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -293,118 +325,95 @@
         "shardCount": int,
         "subnetIds": Sequence[str],
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateClusterInputRequestTypeDef(
     _RequiredUpdateClusterInputRequestTypeDef, _OptionalUpdateClusterInputRequestTypeDef
 ):
     pass
 
-CreateClusterOutputTypeDef = TypedDict(
-    "CreateClusterOutputTypeDef",
+
+ListClustersOutputTypeDef = TypedDict(
+    "ListClustersOutputTypeDef",
     {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clusters": List[ClusterInListTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateClusterSnapshotOutputTypeDef = TypedDict(
-    "CreateClusterSnapshotOutputTypeDef",
+ListClusterSnapshotsOutputTypeDef = TypedDict(
+    "ListClusterSnapshotsOutputTypeDef",
     {
-        "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "snapshots": List[ClusterSnapshotInListTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteClusterOutputTypeDef = TypedDict(
-    "DeleteClusterOutputTypeDef",
+CreateClusterSnapshotOutputTypeDef = TypedDict(
+    "CreateClusterSnapshotOutputTypeDef",
     {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "snapshot": ClusterSnapshotTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterSnapshotOutputTypeDef = TypedDict(
     "DeleteClusterSnapshotOutputTypeDef",
     {
         "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetClusterOutputTypeDef = TypedDict(
-    "GetClusterOutputTypeDef",
-    {
-        "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClusterSnapshotOutputTypeDef = TypedDict(
     "GetClusterSnapshotOutputTypeDef",
     {
         "snapshot": ClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListClusterSnapshotsOutputTypeDef = TypedDict(
-    "ListClusterSnapshotsOutputTypeDef",
+CreateClusterOutputTypeDef = TypedDict(
+    "CreateClusterOutputTypeDef",
     {
-        "nextToken": str,
-        "snapshots": List[ClusterSnapshotInListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListClustersOutputTypeDef = TypedDict(
-    "ListClustersOutputTypeDef",
+DeleteClusterOutputTypeDef = TypedDict(
+    "DeleteClusterOutputTypeDef",
     {
-        "clusters": List[ClusterInListTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+GetClusterOutputTypeDef = TypedDict(
+    "GetClusterOutputTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cluster": ClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreClusterFromSnapshotOutputTypeDef = TypedDict(
     "RestoreClusterFromSnapshotOutputTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterOutputTypeDef = TypedDict(
     "UpdateClusterOutputTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef = TypedDict(
-    "ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef",
-    {
-        "clusterArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListClustersInputListClustersPaginateTypeDef = TypedDict(
-    "ListClustersInputListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
```

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/PKG-INFO` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-docdb-elastic
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DocDBElastic 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DocDBElastic 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-docdb-elastic"></a>
 
 # types-aiobotocore-docdb-elastic
 
 [![PyPI - types-aiobotocore-docdb-elastic](https://img.shields.io/pypi/v/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb-elastic.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb-elastic)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb-elastic?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb-elastic)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDBElastic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
+[aiobotocore.DocDBElastic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb-elastic.html#DocDBElastic)
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
 [types-aiobotocore-docdb-elastic docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb_elastic/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,84 +327,84 @@
 ```python
 from types_aiobotocore_docdb_elastic.type_defs import (
     ClusterInListTypeDef,
     ClusterSnapshotInListTypeDef,
     ClusterSnapshotTypeDef,
     ClusterTypeDef,
     CreateClusterInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateClusterSnapshotInputRequestTypeDef,
     DeleteClusterInputRequestTypeDef,
     DeleteClusterSnapshotInputRequestTypeDef,
     GetClusterInputRequestTypeDef,
     GetClusterSnapshotInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
     ListClusterSnapshotsInputRequestTypeDef,
+    ListClustersInputListClustersPaginateTypeDef,
     ListClustersInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreClusterFromSnapshotInputRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateClusterInputRequestTypeDef,
-    CreateClusterOutputTypeDef,
+    ListClustersOutputTypeDef,
+    ListClusterSnapshotsOutputTypeDef,
     CreateClusterSnapshotOutputTypeDef,
-    DeleteClusterOutputTypeDef,
     DeleteClusterSnapshotOutputTypeDef,
-    GetClusterOutputTypeDef,
     GetClusterSnapshotOutputTypeDef,
-    ListClusterSnapshotsOutputTypeDef,
-    ListClustersOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    CreateClusterOutputTypeDef,
+    DeleteClusterOutputTypeDef,
+    GetClusterOutputTypeDef,
     RestoreClusterFromSnapshotOutputTypeDef,
     UpdateClusterOutputTypeDef,
-    ListClusterSnapshotsInputListClusterSnapshotsPaginateTypeDef,
-    ListClustersInputListClustersPaginateTypeDef,
 )
 
 
 def get_structure() -> ClusterInListTypeDef:
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

### Comparing `types-aiobotocore-docdb-elastic-2.5.0.post1/types_aiobotocore_docdb_elastic.egg-info/SOURCES.txt` & `types-aiobotocore-docdb-elastic-2.5.1/types_aiobotocore_docdb_elastic.egg-info/SOURCES.txt`

 * *Files identical despite different names*

