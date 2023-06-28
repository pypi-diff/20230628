# Comparing `tmp/types-aiobotocore-s3outposts-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-s3outposts-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-s3outposts-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-s3outposts-2.5.1.tar", last modified: Wed Jun 28 01:44:06 2023, max compression
```

## Comparing `types-aiobotocore-s3outposts-2.5.0.post1.tar` & `types-aiobotocore-s3outposts-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.827583 types-aiobotocore-s3outposts-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13756 2023-03-11 12:27:15.827583 types-aiobotocore-s3outposts-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12173 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.827583 types-aiobotocore-s3outposts-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.827583 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/
--rw-r--r--   0 runner    (1001) docker     (123)      879 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      878 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7785 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7770 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8271 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8269 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3280 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3275 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5298 2023-03-11 12:23:04.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5291 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:03.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.827583 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13756 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:27:15.000000 types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.838207 types-aiobotocore-s3outposts-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14139 2023-06-28 01:44:06.838207 types-aiobotocore-s3outposts-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12562 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:06.838207 types-aiobotocore-s3outposts-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.838207 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/
+-rw-r--r--   0 runner    (1001) docker     (123)     1129 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1128 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9035 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9018 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8645 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8643 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4286 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4281 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6525 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6518 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:49.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.838207 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14139 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:44:06.000000 types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/LICENSE` & `types-aiobotocore-s3outposts-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/PKG-INFO` & `types-aiobotocore-s3outposts-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3outposts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3Outposts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3Outposts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3outposts"></a>
 
 # types-aiobotocore-s3outposts
 
 [![PyPI - types-aiobotocore-s3outposts](https://img.shields.io/pypi/v/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
+[aiobotocore.S3Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
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
 [types-aiobotocore-s3outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,24 +274,28 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_s3outposts import S3OutpostsClient
 from types_aiobotocore_s3outposts.paginator import (
     ListEndpointsPaginator,
+    ListOutpostsWithS3Paginator,
     ListSharedEndpointsPaginator,
 )
 
 session = get_session()
 async with session.create_client("s3outposts") as client:
     client: S3OutpostsClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_endpoints_paginator: ListEndpointsPaginator = client.get_paginator("list_endpoints")
+    list_outposts_with_s3_paginator: ListOutpostsWithS3Paginator = client.get_paginator(
+        "list_outposts_with_s3"
+    )
     list_shared_endpoints_paginator: ListSharedEndpointsPaginator = client.get_paginator(
         "list_shared_endpoints"
     )
 ```
 
 <a id="literals"></a>
 
@@ -301,14 +305,15 @@
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_s3outposts.literals import (
     EndpointAccessTypeType,
     EndpointStatusType,
     ListEndpointsPaginatorName,
+    ListOutpostsWithS3PaginatorName,
     ListSharedEndpointsPaginatorName,
     S3OutpostsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -324,25 +329,30 @@
 
 `types_aiobotocore_s3outposts.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3outposts.type_defs import (
     CreateEndpointRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEndpointResultTypeDef,
     DeleteEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    FailedReasonTypeDef,
     NetworkInterfaceTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef,
+    ListOutpostsWithS3RequestRequestTypeDef,
+    OutpostTypeDef,
+    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
     ListSharedEndpointsRequestRequestTypeDef,
-    CreateEndpointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     EndpointTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListEndpointsResultTypeDef,
     ListSharedEndpointsResultTypeDef,
 )
 
 
 def get_structure() -> CreateEndpointRequestRequestTypeDef:
     return {...}
@@ -351,43 +361,43 @@
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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/README.md` & `types-aiobotocore-s3outposts-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-s3outposts"></a>
 
 # types-aiobotocore-s3outposts
 
 [![PyPI - types-aiobotocore-s3outposts](https://img.shields.io/pypi/v/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
+[aiobotocore.S3Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
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
 [types-aiobotocore-s3outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,24 +241,28 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_s3outposts import S3OutpostsClient
 from types_aiobotocore_s3outposts.paginator import (
     ListEndpointsPaginator,
+    ListOutpostsWithS3Paginator,
     ListSharedEndpointsPaginator,
 )
 
 session = get_session()
 async with session.create_client("s3outposts") as client:
     client: S3OutpostsClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_endpoints_paginator: ListEndpointsPaginator = client.get_paginator("list_endpoints")
+    list_outposts_with_s3_paginator: ListOutpostsWithS3Paginator = client.get_paginator(
+        "list_outposts_with_s3"
+    )
     list_shared_endpoints_paginator: ListSharedEndpointsPaginator = client.get_paginator(
         "list_shared_endpoints"
     )
 ```
 
 <a id="literals"></a>
 
@@ -268,14 +272,15 @@
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_s3outposts.literals import (
     EndpointAccessTypeType,
     EndpointStatusType,
     ListEndpointsPaginatorName,
+    ListOutpostsWithS3PaginatorName,
     ListSharedEndpointsPaginatorName,
     S3OutpostsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -291,25 +296,30 @@
 
 `types_aiobotocore_s3outposts.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3outposts.type_defs import (
     CreateEndpointRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEndpointResultTypeDef,
     DeleteEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    FailedReasonTypeDef,
     NetworkInterfaceTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef,
+    ListOutpostsWithS3RequestRequestTypeDef,
+    OutpostTypeDef,
+    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
     ListSharedEndpointsRequestRequestTypeDef,
-    CreateEndpointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     EndpointTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListEndpointsResultTypeDef,
     ListSharedEndpointsResultTypeDef,
 )
 
 
 def get_structure() -> CreateEndpointRequestRequestTypeDef:
     return {...}
@@ -318,43 +328,43 @@
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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/setup.py` & `types-aiobotocore-s3outposts-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-s3outposts.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-s3outposts",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_s3outposts"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.S3Outposts 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.S3Outposts 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/"
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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/__main__.py` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.S3Outposts 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.S3Outposts 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts\nOther"
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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/client.py` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/client.py`

 * *Files 9% similar despite different names*

```diff
@@ -17,19 +17,24 @@
 import sys
 from typing import Any, Dict, Mapping, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import EndpointAccessTypeType
-from .paginator import ListEndpointsPaginator, ListSharedEndpointsPaginator
+from .paginator import (
+    ListEndpointsPaginator,
+    ListOutpostsWithS3Paginator,
+    ListSharedEndpointsPaginator,
+)
 from .type_defs import (
     CreateEndpointResultTypeDef,
     EmptyResponseMetadataTypeDef,
     ListEndpointsResultTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListSharedEndpointsResultTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -47,15 +52,17 @@
 
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    OutpostOfflineException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 
 class S3OutpostsClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/)
@@ -134,14 +141,25 @@
         """
         Lists endpoints associated with the specified Outpost.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.list_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#list_endpoints)
         """
 
+    async def list_outposts_with_s3(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListOutpostsWithS3ResultTypeDef:
+        """
+        Lists the Outposts with S3 on Outposts capacity for your Amazon Web Services
+        account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.list_outposts_with_s3)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#list_outposts_with_s3)
+        """
+
     async def list_shared_endpoints(
         self, *, OutpostId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListSharedEndpointsResultTypeDef:
         """
         Lists all endpoints associated with an Outpost that has been shared by Amazon
         Web Services Resource Access Manager (RAM).
 
@@ -154,14 +172,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_outposts_with_s3"]
+    ) -> ListOutpostsWithS3Paginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_shared_endpoints"]
     ) -> ListSharedEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/client.pyi` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/client.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -17,19 +17,24 @@
 import sys
 from typing import Any, Dict, Mapping, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import EndpointAccessTypeType
-from .paginator import ListEndpointsPaginator, ListSharedEndpointsPaginator
+from .paginator import (
+    ListEndpointsPaginator,
+    ListOutpostsWithS3Paginator,
+    ListSharedEndpointsPaginator,
+)
 from .type_defs import (
     CreateEndpointResultTypeDef,
     EmptyResponseMetadataTypeDef,
     ListEndpointsResultTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListSharedEndpointsResultTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -44,15 +49,17 @@
         self.operation_name: str
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    OutpostOfflineException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 class S3OutpostsClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/)
     """
@@ -123,14 +130,24 @@
     ) -> ListEndpointsResultTypeDef:
         """
         Lists endpoints associated with the specified Outpost.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.list_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#list_endpoints)
         """
+    async def list_outposts_with_s3(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListOutpostsWithS3ResultTypeDef:
+        """
+        Lists the Outposts with S3 on Outposts capacity for your Amazon Web Services
+        account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.list_outposts_with_s3)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#list_outposts_with_s3)
+        """
     async def list_shared_endpoints(
         self, *, OutpostId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListSharedEndpointsResultTypeDef:
         """
         Lists all endpoints associated with an Outpost that has been shared by Amazon
         Web Services Resource Access Manager (RAM).
 
@@ -141,14 +158,22 @@
     def get_paginator(self, operation_name: Literal["list_endpoints"]) -> ListEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_outposts_with_s3"]
+    ) -> ListOutpostsWithS3Paginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_shared_endpoints"]
     ) -> ListSharedEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/client/#get_paginator)
         """
     async def __aenter__(self) -> "S3OutpostsClient":
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/literals.py` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/literals.py`

 * *Files 9% similar despite different names*

```diff
@@ -19,26 +19,28 @@
     from typing_extensions import Literal
 
 
 __all__ = (
     "EndpointAccessTypeType",
     "EndpointStatusType",
     "ListEndpointsPaginatorName",
+    "ListOutpostsWithS3PaginatorName",
     "ListSharedEndpointsPaginatorName",
     "S3OutpostsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 EndpointAccessTypeType = Literal["CustomerOwnedIp", "Private"]
-EndpointStatusType = Literal["Available", "Deleting", "Pending"]
+EndpointStatusType = Literal["Available", "Create_Failed", "Delete_Failed", "Deleting", "Pending"]
 ListEndpointsPaginatorName = Literal["list_endpoints"]
+ListOutpostsWithS3PaginatorName = Literal["list_outposts_with_s3"]
 ListSharedEndpointsPaginatorName = Literal["list_shared_endpoints"]
 S3OutpostsServiceName = Literal["s3outposts"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -95,14 +97,15 @@
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
@@ -181,14 +184,15 @@
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
@@ -199,14 +203,15 @@
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
@@ -242,14 +247,15 @@
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
@@ -268,16 +274,19 @@
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
@@ -361,15 +370,17 @@
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
@@ -387,15 +398,15 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["list_endpoints", "list_shared_endpoints"]
+PaginatorName = Literal["list_endpoints", "list_outposts_with_s3", "list_shared_endpoints"]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/literals.pyi` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/literals.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -18,25 +18,27 @@
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "EndpointAccessTypeType",
     "EndpointStatusType",
     "ListEndpointsPaginatorName",
+    "ListOutpostsWithS3PaginatorName",
     "ListSharedEndpointsPaginatorName",
     "S3OutpostsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 EndpointAccessTypeType = Literal["CustomerOwnedIp", "Private"]
-EndpointStatusType = Literal["Available", "Deleting", "Pending"]
+EndpointStatusType = Literal["Available", "Create_Failed", "Delete_Failed", "Deleting", "Pending"]
 ListEndpointsPaginatorName = Literal["list_endpoints"]
+ListOutpostsWithS3PaginatorName = Literal["list_outposts_with_s3"]
 ListSharedEndpointsPaginatorName = Literal["list_shared_endpoints"]
 S3OutpostsServiceName = Literal["s3outposts"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -93,14 +95,15 @@
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
@@ -179,14 +182,15 @@
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
@@ -197,14 +201,15 @@
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
@@ -240,14 +245,15 @@
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
@@ -266,16 +272,19 @@
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
@@ -359,15 +368,17 @@
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
@@ -385,15 +396,15 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["list_endpoints", "list_shared_endpoints"]
+PaginatorName = Literal["list_endpoints", "list_outposts_with_s3", "list_shared_endpoints"]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/paginator.py` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/paginator.py`

 * *Files 16% similar despite different names*

```diff
@@ -7,44 +7,40 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_s3outposts.client import S3OutpostsClient
     from types_aiobotocore_s3outposts.paginator import (
         ListEndpointsPaginator,
+        ListOutpostsWithS3Paginator,
         ListSharedEndpointsPaginator,
     )
 
     session = get_session()
     with session.create_client("s3outposts") as client:
         client: S3OutpostsClient
 
         list_endpoints_paginator: ListEndpointsPaginator = client.get_paginator("list_endpoints")
+        list_outposts_with_s3_paginator: ListOutpostsWithS3Paginator = client.get_paginator("list_outposts_with_s3")
         list_shared_endpoints_paginator: ListSharedEndpointsPaginator = client.get_paginator("list_shared_endpoints")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListEndpointsResultTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListSharedEndpointsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
-__all__ = ("ListEndpointsPaginator", "ListSharedEndpointsPaginator")
+__all__ = ("ListEndpointsPaginator", "ListOutpostsWithS3Paginator", "ListSharedEndpointsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
@@ -56,28 +52,43 @@
 class ListEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listendpointspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listendpointspaginator)
         """
 
 
+class ListOutpostsWithS3Paginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListOutpostsWithS3)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listoutpostswiths3paginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListOutpostsWithS3ResultTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListOutpostsWithS3.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listoutpostswiths3paginator)
+        """
+
+
 class ListSharedEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListSharedEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listsharedendpointspaginator)
     """
 
     def paginate(
-        self, *, OutpostId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OutpostId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedEndpointsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListSharedEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listsharedendpointspaginator)
         """
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/paginator.pyi` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/paginator.pyi`

 * *Files 24% similar despite different names*

```diff
@@ -7,43 +7,40 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_s3outposts.client import S3OutpostsClient
     from types_aiobotocore_s3outposts.paginator import (
         ListEndpointsPaginator,
+        ListOutpostsWithS3Paginator,
         ListSharedEndpointsPaginator,
     )
 
     session = get_session()
     with session.create_client("s3outposts") as client:
         client: S3OutpostsClient
 
         list_endpoints_paginator: ListEndpointsPaginator = client.get_paginator("list_endpoints")
+        list_outposts_with_s3_paginator: ListOutpostsWithS3Paginator = client.get_paginator("list_outposts_with_s3")
         list_shared_endpoints_paginator: ListSharedEndpointsPaginator = client.get_paginator("list_shared_endpoints")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListEndpointsResultTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListSharedEndpointsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-__all__ = ("ListEndpointsPaginator", "ListSharedEndpointsPaginator")
+__all__ = ("ListEndpointsPaginator", "ListOutpostsWithS3Paginator", "ListSharedEndpointsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
@@ -52,27 +49,41 @@
 class ListEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listendpointspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listendpointspaginator)
         """
 
+class ListOutpostsWithS3Paginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListOutpostsWithS3)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listoutpostswiths3paginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListOutpostsWithS3ResultTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListOutpostsWithS3.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listoutpostswiths3paginator)
+        """
+
 class ListSharedEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListSharedEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listsharedendpointspaginator)
     """
 
     def paginate(
-        self, *, OutpostId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OutpostId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedEndpointsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts.Paginator.ListSharedEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/paginators/#listsharedendpointspaginator)
         """
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts/type_defs.pyi` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts/type_defs.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -20,25 +20,30 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateEndpointRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateEndpointResultTypeDef",
     "DeleteEndpointRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "FailedReasonTypeDef",
     "NetworkInterfaceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
     "ListEndpointsRequestRequestTypeDef",
+    "ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef",
+    "ListOutpostsWithS3RequestRequestTypeDef",
+    "OutpostTypeDef",
+    "ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
     "ListSharedEndpointsRequestRequestTypeDef",
-    "CreateEndpointResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "EndpointTypeDef",
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
-    "ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
+    "ListOutpostsWithS3ResultTypeDef",
     "ListEndpointsResultTypeDef",
     "ListSharedEndpointsResultTypeDef",
 )
 
 _RequiredCreateEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEndpointRequestRequestTypeDef",
     {
@@ -57,60 +62,119 @@
 )
 
 class CreateEndpointRequestRequestTypeDef(
     _RequiredCreateEndpointRequestRequestTypeDef, _OptionalCreateEndpointRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateEndpointResultTypeDef = TypedDict(
+    "CreateEndpointResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "EndpointArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEndpointRequestRequestTypeDef = TypedDict(
     "DeleteEndpointRequestRequestTypeDef",
     {
         "EndpointId": str,
         "OutpostId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FailedReasonTypeDef = TypedDict(
+    "FailedReasonTypeDef",
+    {
+        "ErrorCode": str,
+        "Message": str,
+    },
+    total=False,
+)
+
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "NetworkInterfaceId": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEndpointsRequestRequestTypeDef = TypedDict(
     "ListEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef = TypedDict(
+    "ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListOutpostsWithS3RequestRequestTypeDef = TypedDict(
+    "ListOutpostsWithS3RequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+OutpostTypeDef = TypedDict(
+    "OutpostTypeDef",
+    {
+        "OutpostArn": str,
+        "OutpostId": str,
+        "OwnerId": str,
+        "CapacityInBytes": int,
+    },
+    total=False,
+)
+
+_RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef = TypedDict(
+    "_RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
+    {
+        "OutpostId": str,
+    },
+)
+_OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef = TypedDict(
+    "_OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef(
+    _RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
+    _OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
+):
+    pass
+
 _RequiredListSharedEndpointsRequestRequestTypeDef = TypedDict(
     "_RequiredListSharedEndpointsRequestRequestTypeDef",
     {
         "OutpostId": str,
     },
 )
 _OptionalListSharedEndpointsRequestRequestTypeDef = TypedDict(
@@ -124,26 +188,32 @@
 
 class ListSharedEndpointsRequestRequestTypeDef(
     _RequiredListSharedEndpointsRequestRequestTypeDef,
     _OptionalListSharedEndpointsRequestRequestTypeDef,
 ):
     pass
 
-CreateEndpointResultTypeDef = TypedDict(
-    "CreateEndpointResultTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "EndpointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 EndpointTypeDef = TypedDict(
     "EndpointTypeDef",
     {
         "EndpointArn": str,
@@ -153,56 +223,38 @@
         "CreationTime": datetime,
         "NetworkInterfaces": List[NetworkInterfaceTypeDef],
         "VpcId": str,
         "SubnetId": str,
         "SecurityGroupId": str,
         "AccessType": EndpointAccessTypeType,
         "CustomerOwnedIpv4Pool": str,
+        "FailedReason": FailedReasonTypeDef,
     },
     total=False,
 )
 
-ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef = TypedDict(
-    "_RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
+ListOutpostsWithS3ResultTypeDef = TypedDict(
+    "ListOutpostsWithS3ResultTypeDef",
     {
-        "OutpostId": str,
-    },
-)
-_OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef = TypedDict(
-    "_OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Outposts": List[OutpostTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef(
-    _RequiredListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
-    _OptionalListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
-):
-    pass
-
 ListEndpointsResultTypeDef = TypedDict(
     "ListEndpointsResultTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSharedEndpointsResultTypeDef = TypedDict(
     "ListSharedEndpointsResultTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/PKG-INFO` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3outposts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3Outposts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3Outposts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3outposts"></a>
 
 # types-aiobotocore-s3outposts
 
 [![PyPI - types-aiobotocore-s3outposts](https://img.shields.io/pypi/v/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
+[aiobotocore.S3Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3outposts.html#S3Outposts)
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
 [types-aiobotocore-s3outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,24 +274,28 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_s3outposts import S3OutpostsClient
 from types_aiobotocore_s3outposts.paginator import (
     ListEndpointsPaginator,
+    ListOutpostsWithS3Paginator,
     ListSharedEndpointsPaginator,
 )
 
 session = get_session()
 async with session.create_client("s3outposts") as client:
     client: S3OutpostsClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_endpoints_paginator: ListEndpointsPaginator = client.get_paginator("list_endpoints")
+    list_outposts_with_s3_paginator: ListOutpostsWithS3Paginator = client.get_paginator(
+        "list_outposts_with_s3"
+    )
     list_shared_endpoints_paginator: ListSharedEndpointsPaginator = client.get_paginator(
         "list_shared_endpoints"
     )
 ```
 
 <a id="literals"></a>
 
@@ -301,14 +305,15 @@
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_s3outposts.literals import (
     EndpointAccessTypeType,
     EndpointStatusType,
     ListEndpointsPaginatorName,
+    ListOutpostsWithS3PaginatorName,
     ListSharedEndpointsPaginatorName,
     S3OutpostsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -324,25 +329,30 @@
 
 `types_aiobotocore_s3outposts.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3outposts.type_defs import (
     CreateEndpointRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEndpointResultTypeDef,
     DeleteEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    FailedReasonTypeDef,
     NetworkInterfaceTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListOutpostsWithS3RequestListOutpostsWithS3PaginateTypeDef,
+    ListOutpostsWithS3RequestRequestTypeDef,
+    OutpostTypeDef,
+    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
     ListSharedEndpointsRequestRequestTypeDef,
-    CreateEndpointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     EndpointTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListSharedEndpointsRequestListSharedEndpointsPaginateTypeDef,
+    ListOutpostsWithS3ResultTypeDef,
     ListEndpointsResultTypeDef,
     ListSharedEndpointsResultTypeDef,
 )
 
 
 def get_structure() -> CreateEndpointRequestRequestTypeDef:
     return {...}
@@ -351,43 +361,43 @@
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

### Comparing `types-aiobotocore-s3outposts-2.5.0.post1/types_aiobotocore_s3outposts.egg-info/SOURCES.txt` & `types-aiobotocore-s3outposts-2.5.1/types_aiobotocore_s3outposts.egg-info/SOURCES.txt`

 * *Files identical despite different names*

