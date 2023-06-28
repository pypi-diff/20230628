# Comparing `tmp/types-aiobotocore-lookoutvision-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lookoutvision-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lookoutvision-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-lookoutvision-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-lookoutvision-2.5.0.post1.tar` & `types-aiobotocore-lookoutvision-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.199391 types-aiobotocore-lookoutvision-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16573 2023-03-11 12:26:56.199391 types-aiobotocore-lookoutvision-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14975 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.199391 types-aiobotocore-lookoutvision-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.195392 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/
--rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20628 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20593 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9192 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9190 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5938 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5931 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    26177 2023-03-11 12:17:55.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    26136 2023-03-11 12:17:55.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:53.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.199391 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16573 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:56.000000 types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.318170 types-aiobotocore-lookoutvision-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16571 2023-06-28 01:43:47.318170 types-aiobotocore-lookoutvision-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14979 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.318170 types-aiobotocore-lookoutvision-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2163 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.318170 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/
+-rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20626 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20591 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9401 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9399 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5826 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5820 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    26223 2023-06-28 01:34:36.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26182 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:35.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.318170 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16571 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/LICENSE` & `types-aiobotocore-lookoutvision-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lookoutvision-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutvision
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutforVision 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutforVision 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutvision"></a>
 
 # types-aiobotocore-lookoutvision
 
 [![PyPI - types-aiobotocore-lookoutvision](https://img.shields.io/pypi/v/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutvision?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutvision)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutforVision 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
+[aiobotocore.LookoutforVision 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
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
 [types-aiobotocore-lookoutvision docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,68 +339,68 @@
 `types_aiobotocore_lookoutvision.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lookoutvision.type_defs import (
     PixelAnomalyTypeDef,
     DatasetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectMetadataTypeDef,
     DatasetImageStatsTypeDef,
     InputS3ObjectTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
+    DeleteModelResponseTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeModelPackagingJobRequestRequestTypeDef,
     DescribeModelRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DetectAnomaliesRequestRequestTypeDef,
     ImageSourceTypeDef,
     S3LocationTypeDef,
     TargetPlatformTypeDef,
     GreengrassOutputDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
     ListModelPackagingJobsRequestRequestTypeDef,
     ModelPackagingJobMetadataTypeDef,
+    ListModelsRequestListModelsPaginateTypeDef,
     ListModelsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModelPerformanceTypeDef,
     OutputS3ObjectTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartModelPackagingJobResponseTypeDef,
     StartModelRequestRequestTypeDef,
+    StartModelResponseTypeDef,
     StopModelRequestRequestTypeDef,
+    StopModelResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
+    UpdateDatasetEntriesResponseTypeDef,
     AnomalyTypeDef,
-    ProjectDescriptionTypeDef,
     CreateDatasetResponseTypeDef,
-    DeleteModelResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    StartModelPackagingJobResponseTypeDef,
-    StartModelResponseTypeDef,
-    StopModelResponseTypeDef,
-    UpdateDatasetEntriesResponseTypeDef,
+    ProjectDescriptionTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateProjectResponseTypeDef,
     ListProjectsResponseTypeDef,
     DatasetDescriptionTypeDef,
     DatasetGroundTruthManifestTypeDef,
     OutputConfigTypeDef,
     GreengrassConfigurationTypeDef,
     ModelPackagingOutputDetailsTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-    ListModelsRequestListModelsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListModelPackagingJobsResponseTypeDef,
     ModelMetadataTypeDef,
     DetectAnomalyResultTypeDef,
     DescribeProjectResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     DatasetSourceTypeDef,
     CreateModelRequestRequestTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/README.md` & `types-aiobotocore-lookoutvision-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lookoutvision"></a>
 
 # types-aiobotocore-lookoutvision
 
 [![PyPI - types-aiobotocore-lookoutvision](https://img.shields.io/pypi/v/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutvision?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutvision)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutforVision 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
+[aiobotocore.LookoutforVision 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
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
 [types-aiobotocore-lookoutvision docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,68 +306,68 @@
 `types_aiobotocore_lookoutvision.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lookoutvision.type_defs import (
     PixelAnomalyTypeDef,
     DatasetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectMetadataTypeDef,
     DatasetImageStatsTypeDef,
     InputS3ObjectTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
+    DeleteModelResponseTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeModelPackagingJobRequestRequestTypeDef,
     DescribeModelRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DetectAnomaliesRequestRequestTypeDef,
     ImageSourceTypeDef,
     S3LocationTypeDef,
     TargetPlatformTypeDef,
     GreengrassOutputDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
     ListModelPackagingJobsRequestRequestTypeDef,
     ModelPackagingJobMetadataTypeDef,
+    ListModelsRequestListModelsPaginateTypeDef,
     ListModelsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModelPerformanceTypeDef,
     OutputS3ObjectTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartModelPackagingJobResponseTypeDef,
     StartModelRequestRequestTypeDef,
+    StartModelResponseTypeDef,
     StopModelRequestRequestTypeDef,
+    StopModelResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
+    UpdateDatasetEntriesResponseTypeDef,
     AnomalyTypeDef,
-    ProjectDescriptionTypeDef,
     CreateDatasetResponseTypeDef,
-    DeleteModelResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    StartModelPackagingJobResponseTypeDef,
-    StartModelResponseTypeDef,
-    StopModelResponseTypeDef,
-    UpdateDatasetEntriesResponseTypeDef,
+    ProjectDescriptionTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateProjectResponseTypeDef,
     ListProjectsResponseTypeDef,
     DatasetDescriptionTypeDef,
     DatasetGroundTruthManifestTypeDef,
     OutputConfigTypeDef,
     GreengrassConfigurationTypeDef,
     ModelPackagingOutputDetailsTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-    ListModelsRequestListModelsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListModelPackagingJobsResponseTypeDef,
     ModelMetadataTypeDef,
     DetectAnomalyResultTypeDef,
     DescribeProjectResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     DatasetSourceTypeDef,
     CreateModelRequestRequestTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/setup.py` & `types-aiobotocore-lookoutvision-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lookoutvision.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lookoutvision",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lookoutvision"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LookoutforVision 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LookoutforVision 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/"
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__init__.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__init__.pyi` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/__main__.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LookoutforVision 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LookoutforVision 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision\nOther"
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/client.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -157,15 +157,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#create_project)
         """
 
     async def delete_dataset(
         self, *, ProjectName: str, DatasetType: str, ClientToken: str = ...
     ) -> Dict[str, Any]:
         """
-        Deletes an existing Amazon Lookout for Vision `dataset` .
+        Deletes an existing Amazon Lookout for Vision `dataset`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Client.delete_dataset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#delete_dataset)
         """
 
     async def delete_model(
         self, *, ProjectName: str, ModelVersion: str, ClientToken: str = ...
@@ -295,15 +295,15 @@
         """
 
     async def list_projects(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProjectsResponseTypeDef:
         """
         Lists the Amazon Lookout for Vision projects in your AWS account that are in the
-        AWS Region in which you call `ListProjects` .
+        AWS Region in which you call `ListProjects`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Client.list_projects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#list_projects)
         """
 
     async def list_tags_for_resource(
         self, *, ResourceArn: str
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/client.pyi` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -147,15 +147,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Client.create_project)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#create_project)
         """
     async def delete_dataset(
         self, *, ProjectName: str, DatasetType: str, ClientToken: str = ...
     ) -> Dict[str, Any]:
         """
-        Deletes an existing Amazon Lookout for Vision `dataset` .
+        Deletes an existing Amazon Lookout for Vision `dataset`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Client.delete_dataset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#delete_dataset)
         """
     async def delete_model(
         self, *, ProjectName: str, ModelVersion: str, ClientToken: str = ...
     ) -> DeleteModelResponseTypeDef:
@@ -273,15 +273,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#list_models)
         """
     async def list_projects(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProjectsResponseTypeDef:
         """
         Lists the Amazon Lookout for Vision projects in your AWS account that are in the
-        AWS Region in which you call `ListProjects` .
+        AWS Region in which you call `ListProjects`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Client.list_projects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/client/#list_projects)
         """
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/literals.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -134,14 +134,15 @@
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
@@ -220,14 +221,15 @@
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
@@ -238,14 +240,15 @@
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
@@ -281,14 +284,15 @@
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
@@ -307,16 +311,19 @@
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
@@ -400,15 +407,17 @@
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/literals.pyi` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -132,14 +132,15 @@
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
@@ -218,14 +219,15 @@
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
@@ -236,14 +238,15 @@
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
@@ -279,14 +282,15 @@
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
@@ -305,16 +309,19 @@
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
@@ -398,15 +405,17 @@
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/paginator.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
         list_model_packaging_jobs_paginator: ListModelPackagingJobsPaginator = client.get_paginator("list_model_packaging_jobs")
         list_models_paginator: ListModelsPaginator = client.get_paginator("list_models")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDatasetEntriesResponseTypeDef,
     ListModelPackagingJobsResponseTypeDef,
     ListModelsResponseTypeDef,
     ListProjectsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDatasetEntriesPaginator",
     "ListModelPackagingJobsPaginator",
     "ListModelsPaginator",
     "ListProjectsPaginator",
 )
 
@@ -77,58 +70,58 @@
         ProjectName: str,
         DatasetType: str,
         Labeled: bool = ...,
         AnomalyClass: str = ...,
         BeforeCreationDate: Union[datetime, str] = ...,
         AfterCreationDate: Union[datetime, str] = ...,
         SourceRefContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetEntriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListDatasetEntries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listdatasetentriespaginator)
         """
 
 
 class ListModelPackagingJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModelPackagingJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelpackagingjobspaginator)
     """
 
     def paginate(
-        self, *, ProjectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelPackagingJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModelPackagingJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelpackagingjobspaginator)
         """
 
 
 class ListModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelspaginator)
     """
 
     def paginate(
-        self, *, ProjectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelspaginator)
         """
 
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/paginator.pyi` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
         list_model_packaging_jobs_paginator: ListModelPackagingJobsPaginator = client.get_paginator("list_model_packaging_jobs")
         list_models_paginator: ListModelsPaginator = client.get_paginator("list_models")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDatasetEntriesResponseTypeDef,
     ListModelPackagingJobsResponseTypeDef,
     ListModelsResponseTypeDef,
     ListProjectsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDatasetEntriesPaginator",
     "ListModelPackagingJobsPaginator",
     "ListModelsPaginator",
     "ListProjectsPaginator",
 )
 
@@ -73,55 +67,55 @@
         ProjectName: str,
         DatasetType: str,
         Labeled: bool = ...,
         AnomalyClass: str = ...,
         BeforeCreationDate: Union[datetime, str] = ...,
         AfterCreationDate: Union[datetime, str] = ...,
         SourceRefContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetEntriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListDatasetEntries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listdatasetentriespaginator)
         """
 
 class ListModelPackagingJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModelPackagingJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelpackagingjobspaginator)
     """
 
     def paginate(
-        self, *, ProjectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelPackagingJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModelPackagingJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelpackagingjobspaginator)
         """
 
 class ListModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelspaginator)
     """
 
     def paginate(
-        self, *, ProjectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listmodelspaginator)
         """
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/type_defs.py` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -34,68 +34,68 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "PixelAnomalyTypeDef",
     "DatasetMetadataTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "CreateProjectRequestRequestTypeDef",
     "ProjectMetadataTypeDef",
     "DatasetImageStatsTypeDef",
     "InputS3ObjectTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
+    "DeleteModelResponseTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResponseTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeModelPackagingJobRequestRequestTypeDef",
     "DescribeModelRequestRequestTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "DetectAnomaliesRequestRequestTypeDef",
     "ImageSourceTypeDef",
     "S3LocationTypeDef",
     "TargetPlatformTypeDef",
     "GreengrassOutputDetailsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     "ListDatasetEntriesRequestRequestTypeDef",
+    "ListDatasetEntriesResponseTypeDef",
+    "ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
     "ListModelPackagingJobsRequestRequestTypeDef",
     "ModelPackagingJobMetadataTypeDef",
+    "ListModelsRequestListModelsPaginateTypeDef",
     "ListModelsRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModelPerformanceTypeDef",
     "OutputS3ObjectTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartModelPackagingJobResponseTypeDef",
     "StartModelRequestRequestTypeDef",
+    "StartModelResponseTypeDef",
     "StopModelRequestRequestTypeDef",
+    "StopModelResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDatasetEntriesRequestRequestTypeDef",
+    "UpdateDatasetEntriesResponseTypeDef",
     "AnomalyTypeDef",
-    "ProjectDescriptionTypeDef",
     "CreateDatasetResponseTypeDef",
-    "DeleteModelResponseTypeDef",
-    "DeleteProjectResponseTypeDef",
-    "ListDatasetEntriesResponseTypeDef",
-    "StartModelPackagingJobResponseTypeDef",
-    "StartModelResponseTypeDef",
-    "StopModelResponseTypeDef",
-    "UpdateDatasetEntriesResponseTypeDef",
+    "ProjectDescriptionTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateProjectResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "DatasetDescriptionTypeDef",
     "DatasetGroundTruthManifestTypeDef",
     "OutputConfigTypeDef",
     "GreengrassConfigurationTypeDef",
     "ModelPackagingOutputDetailsTypeDef",
-    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    "ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    "ListModelsRequestListModelsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListModelPackagingJobsResponseTypeDef",
     "ModelMetadataTypeDef",
     "DetectAnomalyResultTypeDef",
     "DescribeProjectResponseTypeDef",
     "DescribeDatasetResponseTypeDef",
     "DatasetSourceTypeDef",
     "CreateModelRequestRequestTypeDef",
@@ -127,25 +127,14 @@
         "CreationTimestamp": datetime,
         "Status": DatasetStatusType,
         "StatusMessage": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -252,14 +241,22 @@
 
 class DeleteModelRequestRequestTypeDef(
     _RequiredDeleteModelRequestRequestTypeDef, _OptionalDeleteModelRequestRequestTypeDef
 ):
     pass
 
 
+DeleteModelResponseTypeDef = TypedDict(
+    "DeleteModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteProjectRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalDeleteProjectRequestRequestTypeDef = TypedDict(
@@ -273,14 +270,22 @@
 
 class DeleteProjectRequestRequestTypeDef(
     _RequiredDeleteProjectRequestRequestTypeDef, _OptionalDeleteProjectRequestRequestTypeDef
 ):
     pass
 
 
+DeleteProjectResponseTypeDef = TypedDict(
+    "DeleteProjectResponseTypeDef",
+    {
+        "ProjectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDatasetRequestRequestTypeDef = TypedDict(
     "DescribeDatasetRequestRequestTypeDef",
     {
         "ProjectName": str,
         "DatasetType": str,
     },
 )
@@ -371,24 +376,42 @@
         "ComponentVersionArn": str,
         "ComponentName": str,
         "ComponentVersion": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProjectName": str,
+        "DatasetType": str,
+    },
+)
+_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "Labeled": bool,
+        "AnomalyClass": str,
+        "BeforeCreationDate": Union[datetime, str],
+        "AfterCreationDate": Union[datetime, str],
+        "SourceRefContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
+    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatasetEntriesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetEntriesRequestRequestTypeDef",
     {
         "ProjectName": str,
         "DatasetType": str,
     },
 )
@@ -410,14 +433,45 @@
 class ListDatasetEntriesRequestRequestTypeDef(
     _RequiredListDatasetEntriesRequestRequestTypeDef,
     _OptionalListDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
 
+ListDatasetEntriesResponseTypeDef = TypedDict(
+    "ListDatasetEntriesResponseTypeDef",
+    {
+        "DatasetEntries": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
+    "_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
+    {
+        "ProjectName": str,
+    },
+)
+_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
+    "_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef(
+    _RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
+    _OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListModelPackagingJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListModelPackagingJobsRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalListModelPackagingJobsRequestRequestTypeDef = TypedDict(
@@ -449,14 +503,36 @@
         "StatusMessage": str,
         "CreationTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
+_RequiredListModelsRequestListModelsPaginateTypeDef = TypedDict(
+    "_RequiredListModelsRequestListModelsPaginateTypeDef",
+    {
+        "ProjectName": str,
+    },
+)
+_OptionalListModelsRequestListModelsPaginateTypeDef = TypedDict(
+    "_OptionalListModelsRequestListModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListModelsRequestListModelsPaginateTypeDef(
+    _RequiredListModelsRequestListModelsPaginateTypeDef,
+    _OptionalListModelsRequestListModelsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListModelsRequestRequestTypeDef = TypedDict(
     "_RequiredListModelsRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalListModelsRequestRequestTypeDef = TypedDict(
@@ -471,14 +547,22 @@
 
 class ListModelsRequestRequestTypeDef(
     _RequiredListModelsRequestRequestTypeDef, _OptionalListModelsRequestRequestTypeDef
 ):
     pass
 
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -505,14 +589,43 @@
     "OutputS3ObjectTypeDef",
     {
         "Bucket": str,
         "Key": str,
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
+StartModelPackagingJobResponseTypeDef = TypedDict(
+    "StartModelPackagingJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartModelRequestRequestTypeDef = TypedDict(
     "_RequiredStartModelRequestRequestTypeDef",
     {
         "ProjectName": str,
         "ModelVersion": str,
         "MinInferenceUnits": int,
     },
@@ -529,14 +642,22 @@
 
 class StartModelRequestRequestTypeDef(
     _RequiredStartModelRequestRequestTypeDef, _OptionalStartModelRequestRequestTypeDef
 ):
     pass
 
 
+StartModelResponseTypeDef = TypedDict(
+    "StartModelResponseTypeDef",
+    {
+        "Status": ModelHostingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopModelRequestRequestTypeDef = TypedDict(
     "_RequiredStopModelRequestRequestTypeDef",
     {
         "ProjectName": str,
         "ModelVersion": str,
     },
 )
@@ -551,14 +672,22 @@
 
 class StopModelRequestRequestTypeDef(
     _RequiredStopModelRequestRequestTypeDef, _OptionalStopModelRequestRequestTypeDef
 ):
     pass
 
 
+StopModelResponseTypeDef = TypedDict(
+    "StopModelResponseTypeDef",
+    {
+        "Status": ModelHostingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -583,104 +712,55 @@
 class UpdateDatasetEntriesRequestRequestTypeDef(
     _RequiredUpdateDatasetEntriesRequestRequestTypeDef,
     _OptionalUpdateDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
 
-AnomalyTypeDef = TypedDict(
-    "AnomalyTypeDef",
+UpdateDatasetEntriesResponseTypeDef = TypedDict(
+    "UpdateDatasetEntriesResponseTypeDef",
     {
-        "Name": str,
-        "PixelAnomaly": PixelAnomalyTypeDef,
+        "Status": DatasetStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ProjectDescriptionTypeDef = TypedDict(
-    "ProjectDescriptionTypeDef",
+AnomalyTypeDef = TypedDict(
+    "AnomalyTypeDef",
     {
-        "ProjectArn": str,
-        "ProjectName": str,
-        "CreationTimestamp": datetime,
-        "Datasets": List[DatasetMetadataTypeDef],
+        "Name": str,
+        "PixelAnomaly": PixelAnomalyTypeDef,
     },
     total=False,
 )
 
 CreateDatasetResponseTypeDef = TypedDict(
     "CreateDatasetResponseTypeDef",
     {
         "DatasetMetadata": DatasetMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteModelResponseTypeDef = TypedDict(
-    "DeleteModelResponseTypeDef",
-    {
-        "ModelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProjectResponseTypeDef = TypedDict(
-    "DeleteProjectResponseTypeDef",
+ProjectDescriptionTypeDef = TypedDict(
+    "ProjectDescriptionTypeDef",
     {
         "ProjectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatasetEntriesResponseTypeDef = TypedDict(
-    "ListDatasetEntriesResponseTypeDef",
-    {
-        "DatasetEntries": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartModelPackagingJobResponseTypeDef = TypedDict(
-    "StartModelPackagingJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartModelResponseTypeDef = TypedDict(
-    "StartModelResponseTypeDef",
-    {
-        "Status": ModelHostingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopModelResponseTypeDef = TypedDict(
-    "StopModelResponseTypeDef",
-    {
-        "Status": ModelHostingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDatasetEntriesResponseTypeDef = TypedDict(
-    "UpdateDatasetEntriesResponseTypeDef",
-    {
-        "Status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProjectName": str,
+        "CreationTimestamp": datetime,
+        "Datasets": List[DatasetMetadataTypeDef],
     },
+    total=False,
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
         "ResourceArn": str,
@@ -688,24 +768,24 @@
     },
 )
 
 CreateProjectResponseTypeDef = TypedDict(
     "CreateProjectResponseTypeDef",
     {
         "ProjectMetadata": ProjectMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "Projects": List[ProjectMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetDescriptionTypeDef = TypedDict(
     "DatasetDescriptionTypeDef",
     {
         "ProjectName": str,
@@ -765,100 +845,20 @@
     "ModelPackagingOutputDetailsTypeDef",
     {
         "Greengrass": GreengrassOutputDetailsTypeDef,
     },
     total=False,
 )
 
-_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "ProjectName": str,
-        "DatasetType": str,
-    },
-)
-_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "Labeled": bool,
-        "AnomalyClass": str,
-        "BeforeCreationDate": Union[datetime, str],
-        "AfterCreationDate": Union[datetime, str],
-        "SourceRefContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
-    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
-    "_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    {
-        "ProjectName": str,
-    },
-)
-_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
-    "_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef(
-    _RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-    _OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListModelsRequestListModelsPaginateTypeDef = TypedDict(
-    "_RequiredListModelsRequestListModelsPaginateTypeDef",
-    {
-        "ProjectName": str,
-    },
-)
-_OptionalListModelsRequestListModelsPaginateTypeDef = TypedDict(
-    "_OptionalListModelsRequestListModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListModelsRequestListModelsPaginateTypeDef(
-    _RequiredListModelsRequestListModelsPaginateTypeDef,
-    _OptionalListModelsRequestListModelsPaginateTypeDef,
-):
-    pass
-
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListModelPackagingJobsResponseTypeDef = TypedDict(
     "ListModelPackagingJobsResponseTypeDef",
     {
         "ModelPackagingJobs": List[ModelPackagingJobMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelMetadataTypeDef = TypedDict(
     "ModelMetadataTypeDef",
     {
         "CreationTimestamp": datetime,
@@ -884,23 +884,23 @@
     total=False,
 )
 
 DescribeProjectResponseTypeDef = TypedDict(
     "DescribeProjectResponseTypeDef",
     {
         "ProjectDescription": ProjectDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "DatasetDescription": DatasetDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetSourceTypeDef = TypedDict(
     "DatasetSourceTypeDef",
     {
         "GroundTruthManifest": DatasetGroundTruthManifestTypeDef,
@@ -961,32 +961,32 @@
     },
 )
 
 CreateModelResponseTypeDef = TypedDict(
     "CreateModelResponseTypeDef",
     {
         "ModelMetadata": ModelMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListModelsResponseTypeDef = TypedDict(
     "ListModelsResponseTypeDef",
     {
         "Models": List[ModelMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectAnomaliesResponseTypeDef = TypedDict(
     "DetectAnomaliesResponseTypeDef",
     {
         "DetectAnomalyResult": DetectAnomalyResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "ProjectName": str,
@@ -1009,15 +1009,15 @@
     pass
 
 
 DescribeModelResponseTypeDef = TypedDict(
     "DescribeModelResponseTypeDef",
     {
         "ModelDescription": ModelDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelPackagingDescriptionTypeDef = TypedDict(
     "ModelPackagingDescriptionTypeDef",
     {
         "JobName": str,
@@ -1061,10 +1061,10 @@
     pass
 
 
 DescribeModelPackagingJobResponseTypeDef = TypedDict(
     "DescribeModelPackagingJobResponseTypeDef",
     {
         "ModelPackagingDescription": ModelPackagingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision/type_defs.pyi` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -33,68 +33,68 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "PixelAnomalyTypeDef",
     "DatasetMetadataTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "CreateProjectRequestRequestTypeDef",
     "ProjectMetadataTypeDef",
     "DatasetImageStatsTypeDef",
     "InputS3ObjectTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
+    "DeleteModelResponseTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResponseTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeModelPackagingJobRequestRequestTypeDef",
     "DescribeModelRequestRequestTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "DetectAnomaliesRequestRequestTypeDef",
     "ImageSourceTypeDef",
     "S3LocationTypeDef",
     "TargetPlatformTypeDef",
     "GreengrassOutputDetailsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     "ListDatasetEntriesRequestRequestTypeDef",
+    "ListDatasetEntriesResponseTypeDef",
+    "ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
     "ListModelPackagingJobsRequestRequestTypeDef",
     "ModelPackagingJobMetadataTypeDef",
+    "ListModelsRequestListModelsPaginateTypeDef",
     "ListModelsRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModelPerformanceTypeDef",
     "OutputS3ObjectTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartModelPackagingJobResponseTypeDef",
     "StartModelRequestRequestTypeDef",
+    "StartModelResponseTypeDef",
     "StopModelRequestRequestTypeDef",
+    "StopModelResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDatasetEntriesRequestRequestTypeDef",
+    "UpdateDatasetEntriesResponseTypeDef",
     "AnomalyTypeDef",
-    "ProjectDescriptionTypeDef",
     "CreateDatasetResponseTypeDef",
-    "DeleteModelResponseTypeDef",
-    "DeleteProjectResponseTypeDef",
-    "ListDatasetEntriesResponseTypeDef",
-    "StartModelPackagingJobResponseTypeDef",
-    "StartModelResponseTypeDef",
-    "StopModelResponseTypeDef",
-    "UpdateDatasetEntriesResponseTypeDef",
+    "ProjectDescriptionTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateProjectResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "DatasetDescriptionTypeDef",
     "DatasetGroundTruthManifestTypeDef",
     "OutputConfigTypeDef",
     "GreengrassConfigurationTypeDef",
     "ModelPackagingOutputDetailsTypeDef",
-    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    "ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    "ListModelsRequestListModelsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListModelPackagingJobsResponseTypeDef",
     "ModelMetadataTypeDef",
     "DetectAnomalyResultTypeDef",
     "DescribeProjectResponseTypeDef",
     "DescribeDatasetResponseTypeDef",
     "DatasetSourceTypeDef",
     "CreateModelRequestRequestTypeDef",
@@ -126,25 +126,14 @@
         "CreationTimestamp": datetime,
         "Status": DatasetStatusType,
         "StatusMessage": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -243,14 +232,22 @@
 )
 
 class DeleteModelRequestRequestTypeDef(
     _RequiredDeleteModelRequestRequestTypeDef, _OptionalDeleteModelRequestRequestTypeDef
 ):
     pass
 
+DeleteModelResponseTypeDef = TypedDict(
+    "DeleteModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteProjectRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalDeleteProjectRequestRequestTypeDef = TypedDict(
@@ -262,14 +259,22 @@
 )
 
 class DeleteProjectRequestRequestTypeDef(
     _RequiredDeleteProjectRequestRequestTypeDef, _OptionalDeleteProjectRequestRequestTypeDef
 ):
     pass
 
+DeleteProjectResponseTypeDef = TypedDict(
+    "DeleteProjectResponseTypeDef",
+    {
+        "ProjectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDatasetRequestRequestTypeDef = TypedDict(
     "DescribeDatasetRequestRequestTypeDef",
     {
         "ProjectName": str,
         "DatasetType": str,
     },
 )
@@ -356,24 +361,40 @@
         "ComponentVersionArn": str,
         "ComponentName": str,
         "ComponentVersion": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProjectName": str,
+        "DatasetType": str,
+    },
+)
+_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "Labeled": bool,
+        "AnomalyClass": str,
+        "BeforeCreationDate": Union[datetime, str],
+        "AfterCreationDate": Union[datetime, str],
+        "SourceRefContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
+    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDatasetEntriesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetEntriesRequestRequestTypeDef",
     {
         "ProjectName": str,
         "DatasetType": str,
     },
 )
@@ -393,14 +414,43 @@
 
 class ListDatasetEntriesRequestRequestTypeDef(
     _RequiredListDatasetEntriesRequestRequestTypeDef,
     _OptionalListDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
+ListDatasetEntriesResponseTypeDef = TypedDict(
+    "ListDatasetEntriesResponseTypeDef",
+    {
+        "DatasetEntries": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
+    "_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
+    {
+        "ProjectName": str,
+    },
+)
+_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
+    "_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef(
+    _RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
+    _OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListModelPackagingJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListModelPackagingJobsRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalListModelPackagingJobsRequestRequestTypeDef = TypedDict(
@@ -430,14 +480,34 @@
         "StatusMessage": str,
         "CreationTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
+_RequiredListModelsRequestListModelsPaginateTypeDef = TypedDict(
+    "_RequiredListModelsRequestListModelsPaginateTypeDef",
+    {
+        "ProjectName": str,
+    },
+)
+_OptionalListModelsRequestListModelsPaginateTypeDef = TypedDict(
+    "_OptionalListModelsRequestListModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListModelsRequestListModelsPaginateTypeDef(
+    _RequiredListModelsRequestListModelsPaginateTypeDef,
+    _OptionalListModelsRequestListModelsPaginateTypeDef,
+):
+    pass
+
 _RequiredListModelsRequestRequestTypeDef = TypedDict(
     "_RequiredListModelsRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 _OptionalListModelsRequestRequestTypeDef = TypedDict(
@@ -450,14 +520,22 @@
 )
 
 class ListModelsRequestRequestTypeDef(
     _RequiredListModelsRequestRequestTypeDef, _OptionalListModelsRequestRequestTypeDef
 ):
     pass
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -484,14 +562,43 @@
     "OutputS3ObjectTypeDef",
     {
         "Bucket": str,
         "Key": str,
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
+StartModelPackagingJobResponseTypeDef = TypedDict(
+    "StartModelPackagingJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartModelRequestRequestTypeDef = TypedDict(
     "_RequiredStartModelRequestRequestTypeDef",
     {
         "ProjectName": str,
         "ModelVersion": str,
         "MinInferenceUnits": int,
     },
@@ -506,14 +613,22 @@
 )
 
 class StartModelRequestRequestTypeDef(
     _RequiredStartModelRequestRequestTypeDef, _OptionalStartModelRequestRequestTypeDef
 ):
     pass
 
+StartModelResponseTypeDef = TypedDict(
+    "StartModelResponseTypeDef",
+    {
+        "Status": ModelHostingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopModelRequestRequestTypeDef = TypedDict(
     "_RequiredStopModelRequestRequestTypeDef",
     {
         "ProjectName": str,
         "ModelVersion": str,
     },
 )
@@ -526,14 +641,22 @@
 )
 
 class StopModelRequestRequestTypeDef(
     _RequiredStopModelRequestRequestTypeDef, _OptionalStopModelRequestRequestTypeDef
 ):
     pass
 
+StopModelResponseTypeDef = TypedDict(
+    "StopModelResponseTypeDef",
+    {
+        "Status": ModelHostingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -556,104 +679,55 @@
 
 class UpdateDatasetEntriesRequestRequestTypeDef(
     _RequiredUpdateDatasetEntriesRequestRequestTypeDef,
     _OptionalUpdateDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
-AnomalyTypeDef = TypedDict(
-    "AnomalyTypeDef",
+UpdateDatasetEntriesResponseTypeDef = TypedDict(
+    "UpdateDatasetEntriesResponseTypeDef",
     {
-        "Name": str,
-        "PixelAnomaly": PixelAnomalyTypeDef,
+        "Status": DatasetStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ProjectDescriptionTypeDef = TypedDict(
-    "ProjectDescriptionTypeDef",
+AnomalyTypeDef = TypedDict(
+    "AnomalyTypeDef",
     {
-        "ProjectArn": str,
-        "ProjectName": str,
-        "CreationTimestamp": datetime,
-        "Datasets": List[DatasetMetadataTypeDef],
+        "Name": str,
+        "PixelAnomaly": PixelAnomalyTypeDef,
     },
     total=False,
 )
 
 CreateDatasetResponseTypeDef = TypedDict(
     "CreateDatasetResponseTypeDef",
     {
         "DatasetMetadata": DatasetMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteModelResponseTypeDef = TypedDict(
-    "DeleteModelResponseTypeDef",
-    {
-        "ModelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteProjectResponseTypeDef = TypedDict(
-    "DeleteProjectResponseTypeDef",
+ProjectDescriptionTypeDef = TypedDict(
+    "ProjectDescriptionTypeDef",
     {
         "ProjectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatasetEntriesResponseTypeDef = TypedDict(
-    "ListDatasetEntriesResponseTypeDef",
-    {
-        "DatasetEntries": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartModelPackagingJobResponseTypeDef = TypedDict(
-    "StartModelPackagingJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartModelResponseTypeDef = TypedDict(
-    "StartModelResponseTypeDef",
-    {
-        "Status": ModelHostingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopModelResponseTypeDef = TypedDict(
-    "StopModelResponseTypeDef",
-    {
-        "Status": ModelHostingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDatasetEntriesResponseTypeDef = TypedDict(
-    "UpdateDatasetEntriesResponseTypeDef",
-    {
-        "Status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProjectName": str,
+        "CreationTimestamp": datetime,
+        "Datasets": List[DatasetMetadataTypeDef],
     },
+    total=False,
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
         "ResourceArn": str,
@@ -661,24 +735,24 @@
     },
 )
 
 CreateProjectResponseTypeDef = TypedDict(
     "CreateProjectResponseTypeDef",
     {
         "ProjectMetadata": ProjectMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "Projects": List[ProjectMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetDescriptionTypeDef = TypedDict(
     "DatasetDescriptionTypeDef",
     {
         "ProjectName": str,
@@ -736,94 +810,20 @@
     "ModelPackagingOutputDetailsTypeDef",
     {
         "Greengrass": GreengrassOutputDetailsTypeDef,
     },
     total=False,
 )
 
-_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "ProjectName": str,
-        "DatasetType": str,
-    },
-)
-_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "Labeled": bool,
-        "AnomalyClass": str,
-        "BeforeCreationDate": Union[datetime, str],
-        "AfterCreationDate": Union[datetime, str],
-        "SourceRefContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
-    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-):
-    pass
-
-_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
-    "_RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    {
-        "ProjectName": str,
-    },
-)
-_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef = TypedDict(
-    "_OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef(
-    _RequiredListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-    _OptionalListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListModelsRequestListModelsPaginateTypeDef = TypedDict(
-    "_RequiredListModelsRequestListModelsPaginateTypeDef",
-    {
-        "ProjectName": str,
-    },
-)
-_OptionalListModelsRequestListModelsPaginateTypeDef = TypedDict(
-    "_OptionalListModelsRequestListModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListModelsRequestListModelsPaginateTypeDef(
-    _RequiredListModelsRequestListModelsPaginateTypeDef,
-    _OptionalListModelsRequestListModelsPaginateTypeDef,
-):
-    pass
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListModelPackagingJobsResponseTypeDef = TypedDict(
     "ListModelPackagingJobsResponseTypeDef",
     {
         "ModelPackagingJobs": List[ModelPackagingJobMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelMetadataTypeDef = TypedDict(
     "ModelMetadataTypeDef",
     {
         "CreationTimestamp": datetime,
@@ -849,23 +849,23 @@
     total=False,
 )
 
 DescribeProjectResponseTypeDef = TypedDict(
     "DescribeProjectResponseTypeDef",
     {
         "ProjectDescription": ProjectDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "DatasetDescription": DatasetDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetSourceTypeDef = TypedDict(
     "DatasetSourceTypeDef",
     {
         "GroundTruthManifest": DatasetGroundTruthManifestTypeDef,
@@ -924,32 +924,32 @@
     },
 )
 
 CreateModelResponseTypeDef = TypedDict(
     "CreateModelResponseTypeDef",
     {
         "ModelMetadata": ModelMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListModelsResponseTypeDef = TypedDict(
     "ListModelsResponseTypeDef",
     {
         "Models": List[ModelMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectAnomaliesResponseTypeDef = TypedDict(
     "DetectAnomaliesResponseTypeDef",
     {
         "DetectAnomalyResult": DetectAnomalyResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "ProjectName": str,
@@ -970,15 +970,15 @@
 ):
     pass
 
 DescribeModelResponseTypeDef = TypedDict(
     "DescribeModelResponseTypeDef",
     {
         "ModelDescription": ModelDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelPackagingDescriptionTypeDef = TypedDict(
     "ModelPackagingDescriptionTypeDef",
     {
         "JobName": str,
@@ -1020,10 +1020,10 @@
 ):
     pass
 
 DescribeModelPackagingJobResponseTypeDef = TypedDict(
     "DescribeModelPackagingJobResponseTypeDef",
     {
         "ModelPackagingDescription": ModelPackagingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/PKG-INFO` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutvision
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutforVision 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutforVision 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutvision"></a>
 
 # types-aiobotocore-lookoutvision
 
 [![PyPI - types-aiobotocore-lookoutvision](https://img.shields.io/pypi/v/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutvision.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutvision)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutvision?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutvision)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutforVision 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
+[aiobotocore.LookoutforVision 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutvision.html#LookoutforVision)
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
 [types-aiobotocore-lookoutvision docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutvision/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,68 +339,68 @@
 `types_aiobotocore_lookoutvision.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lookoutvision.type_defs import (
     PixelAnomalyTypeDef,
     DatasetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectMetadataTypeDef,
     DatasetImageStatsTypeDef,
     InputS3ObjectTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
+    DeleteModelResponseTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeModelPackagingJobRequestRequestTypeDef,
     DescribeModelRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DetectAnomaliesRequestRequestTypeDef,
     ImageSourceTypeDef,
     S3LocationTypeDef,
     TargetPlatformTypeDef,
     GreengrassOutputDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
     ListModelPackagingJobsRequestRequestTypeDef,
     ModelPackagingJobMetadataTypeDef,
+    ListModelsRequestListModelsPaginateTypeDef,
     ListModelsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModelPerformanceTypeDef,
     OutputS3ObjectTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartModelPackagingJobResponseTypeDef,
     StartModelRequestRequestTypeDef,
+    StartModelResponseTypeDef,
     StopModelRequestRequestTypeDef,
+    StopModelResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
+    UpdateDatasetEntriesResponseTypeDef,
     AnomalyTypeDef,
-    ProjectDescriptionTypeDef,
     CreateDatasetResponseTypeDef,
-    DeleteModelResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    StartModelPackagingJobResponseTypeDef,
-    StartModelResponseTypeDef,
-    StopModelResponseTypeDef,
-    UpdateDatasetEntriesResponseTypeDef,
+    ProjectDescriptionTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateProjectResponseTypeDef,
     ListProjectsResponseTypeDef,
     DatasetDescriptionTypeDef,
     DatasetGroundTruthManifestTypeDef,
     OutputConfigTypeDef,
     GreengrassConfigurationTypeDef,
     ModelPackagingOutputDetailsTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListModelPackagingJobsRequestListModelPackagingJobsPaginateTypeDef,
-    ListModelsRequestListModelsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListModelPackagingJobsResponseTypeDef,
     ModelMetadataTypeDef,
     DetectAnomalyResultTypeDef,
     DescribeProjectResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     DatasetSourceTypeDef,
     CreateModelRequestRequestTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-lookoutvision-2.5.0.post1/types_aiobotocore_lookoutvision.egg-info/SOURCES.txt` & `types-aiobotocore-lookoutvision-2.5.1/types_aiobotocore_lookoutvision.egg-info/SOURCES.txt`

 * *Files identical despite different names*

