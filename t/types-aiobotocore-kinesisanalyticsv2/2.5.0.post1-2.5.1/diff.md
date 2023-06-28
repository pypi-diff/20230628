# Comparing `tmp/types-aiobotocore-kinesisanalyticsv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesisanalyticsv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesisanalyticsv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesisanalyticsv2-2.5.1.tar", last modified: Wed Jun 28 01:43:43 2023, max compression
```

## Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1.tar` & `types-aiobotocore-kinesisanalyticsv2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.679346 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21576 2023-03-11 12:26:51.671346 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19961 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.679346 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2217 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.667346 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/
--rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29390 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    29348 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9695 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9693 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3542 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3537 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    69067 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    68966 2023-03-11 12:17:02.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:01.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.671346 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21576 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.982162 types-aiobotocore-kinesisanalyticsv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21579 2023-06-28 01:43:42.982162 types-aiobotocore-kinesisanalyticsv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19970 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.982162 types-aiobotocore-kinesisanalyticsv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.978162 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29390 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29348 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9982 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9980 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3426 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3422 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    69119 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69018 2023-06-28 01:33:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:41.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.982162 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21579 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisanalyticsv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisanalyticsv2"></a>
 
 # types-aiobotocore-kinesisanalyticsv2
 
 [![PyPI - types-aiobotocore-kinesisanalyticsv2](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalyticsv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalyticsv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalyticsV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
+[aiobotocore.KinesisAnalyticsV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
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
 [types-aiobotocore-kinesisanalyticsv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -338,15 +338,14 @@
 `types_aiobotocore_kinesisanalyticsv2.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisanalyticsv2.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     VpcConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationTypeDef,
     ApplicationSnapshotConfigurationUpdateTypeDef,
     VpcConfigurationUpdateTypeDef,
     ApplicationMaintenanceConfigurationDescriptionTypeDef,
@@ -362,24 +361,29 @@
     CheckpointConfigurationTypeDef,
     CheckpointConfigurationUpdateTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     S3ApplicationCodeLocationDescriptionTypeDef,
     S3ContentLocationTypeDef,
     S3ContentLocationUpdateTypeDef,
     CreateApplicationPresignedUrlRequestRequestTypeDef,
+    CreateApplicationPresignedUrlResponseTypeDef,
     TagTypeDef,
     CreateApplicationSnapshotRequestRequestTypeDef,
     MavenReferenceTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
+    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
+    DeleteApplicationOutputResponseTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
+    DeleteApplicationReferenceDataSourceResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteApplicationSnapshotRequestRequestTypeDef,
     DeleteApplicationVpcConfigurationRequestRequestTypeDef,
+    DeleteApplicationVpcConfigurationResponseTypeDef,
     S3ContentBaseLocationDescriptionTypeDef,
     S3ContentBaseLocationTypeDef,
     S3ContentBaseLocationUpdateTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeApplicationSnapshotRequestRequestTypeDef,
     SnapshotDetailsTypeDef,
     DescribeApplicationVersionRequestRequestTypeDef,
@@ -412,36 +416,34 @@
     KinesisFirehoseOutputUpdateTypeDef,
     KinesisStreamsOutputDescriptionTypeDef,
     KinesisStreamsOutputTypeDef,
     KinesisStreamsOutputUpdateTypeDef,
     LambdaOutputDescriptionTypeDef,
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
     ListApplicationSnapshotsRequestRequestTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     RollbackApplicationRequestRequestTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ZeppelinMonitoringConfigurationDescriptionTypeDef,
     ZeppelinMonitoringConfigurationTypeDef,
     ZeppelinMonitoringConfigurationUpdateTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionResponseTypeDef,
-    CreateApplicationPresignedUrlResponseTypeDef,
     DeleteApplicationCloudWatchLoggingOptionResponseTypeDef,
-    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
-    DeleteApplicationOutputResponseTypeDef,
-    DeleteApplicationReferenceDataSourceResponseTypeDef,
-    DeleteApplicationVpcConfigurationResponseTypeDef,
     AddApplicationVpcConfigurationRequestRequestTypeDef,
     AddApplicationVpcConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef,
     ListApplicationsResponseTypeDef,
     ListApplicationVersionsResponseTypeDef,
     CatalogConfigurationDescriptionTypeDef,
@@ -471,16 +473,14 @@
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
     OutputUpdateTypeDef,
-    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ApplicationCodeConfigurationDescriptionTypeDef,
     ApplicationCodeConfigurationTypeDef,
     ApplicationCodeConfigurationUpdateTypeDef,
     ZeppelinApplicationConfigurationDescriptionTypeDef,
     ZeppelinApplicationConfigurationTypeDef,
     ZeppelinApplicationConfigurationUpdateTypeDef,
     RunConfigurationTypeDef,
@@ -528,43 +528,43 @@
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/README.md` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesisanalyticsv2"></a>
 
 # types-aiobotocore-kinesisanalyticsv2
 
 [![PyPI - types-aiobotocore-kinesisanalyticsv2](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalyticsv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalyticsv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalyticsV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
+[aiobotocore.KinesisAnalyticsV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
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
 [types-aiobotocore-kinesisanalyticsv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -305,15 +305,14 @@
 `types_aiobotocore_kinesisanalyticsv2.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisanalyticsv2.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     VpcConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationTypeDef,
     ApplicationSnapshotConfigurationUpdateTypeDef,
     VpcConfigurationUpdateTypeDef,
     ApplicationMaintenanceConfigurationDescriptionTypeDef,
@@ -329,24 +328,29 @@
     CheckpointConfigurationTypeDef,
     CheckpointConfigurationUpdateTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     S3ApplicationCodeLocationDescriptionTypeDef,
     S3ContentLocationTypeDef,
     S3ContentLocationUpdateTypeDef,
     CreateApplicationPresignedUrlRequestRequestTypeDef,
+    CreateApplicationPresignedUrlResponseTypeDef,
     TagTypeDef,
     CreateApplicationSnapshotRequestRequestTypeDef,
     MavenReferenceTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
+    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
+    DeleteApplicationOutputResponseTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
+    DeleteApplicationReferenceDataSourceResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteApplicationSnapshotRequestRequestTypeDef,
     DeleteApplicationVpcConfigurationRequestRequestTypeDef,
+    DeleteApplicationVpcConfigurationResponseTypeDef,
     S3ContentBaseLocationDescriptionTypeDef,
     S3ContentBaseLocationTypeDef,
     S3ContentBaseLocationUpdateTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeApplicationSnapshotRequestRequestTypeDef,
     SnapshotDetailsTypeDef,
     DescribeApplicationVersionRequestRequestTypeDef,
@@ -379,36 +383,34 @@
     KinesisFirehoseOutputUpdateTypeDef,
     KinesisStreamsOutputDescriptionTypeDef,
     KinesisStreamsOutputTypeDef,
     KinesisStreamsOutputUpdateTypeDef,
     LambdaOutputDescriptionTypeDef,
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
     ListApplicationSnapshotsRequestRequestTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     RollbackApplicationRequestRequestTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ZeppelinMonitoringConfigurationDescriptionTypeDef,
     ZeppelinMonitoringConfigurationTypeDef,
     ZeppelinMonitoringConfigurationUpdateTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionResponseTypeDef,
-    CreateApplicationPresignedUrlResponseTypeDef,
     DeleteApplicationCloudWatchLoggingOptionResponseTypeDef,
-    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
-    DeleteApplicationOutputResponseTypeDef,
-    DeleteApplicationReferenceDataSourceResponseTypeDef,
-    DeleteApplicationVpcConfigurationResponseTypeDef,
     AddApplicationVpcConfigurationRequestRequestTypeDef,
     AddApplicationVpcConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef,
     ListApplicationsResponseTypeDef,
     ListApplicationVersionsResponseTypeDef,
     CatalogConfigurationDescriptionTypeDef,
@@ -438,16 +440,14 @@
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
     OutputUpdateTypeDef,
-    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ApplicationCodeConfigurationDescriptionTypeDef,
     ApplicationCodeConfigurationTypeDef,
     ApplicationCodeConfigurationUpdateTypeDef,
     ZeppelinApplicationConfigurationDescriptionTypeDef,
     ZeppelinApplicationConfigurationTypeDef,
     ZeppelinApplicationConfigurationUpdateTypeDef,
     RunConfigurationTypeDef,
@@ -495,43 +495,43 @@
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/setup.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesisanalyticsv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesisanalyticsv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesisanalyticsv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/"
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__init__.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__init__.pyi` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/__main__.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2\nOther"
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/client.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/client.pyi` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/literals.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationModeType",
     "ApplicationRestoreTypeType",
     "ApplicationStatusType",
     "ArtifactTypeType",
     "CodeContentTypeType",
     "ConfigurationTypeType",
@@ -38,15 +37,14 @@
     "KinesisAnalyticsV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ApplicationModeType = Literal["INTERACTIVE", "STREAMING"]
 ApplicationRestoreTypeType = Literal[
     "RESTORE_FROM_CUSTOM_SNAPSHOT", "RESTORE_FROM_LATEST_SNAPSHOT", "SKIP_RESTORE_FROM_SNAPSHOT"
 ]
 ApplicationStatusType = Literal[
     "AUTOSCALING",
     "DELETING",
@@ -140,14 +138,15 @@
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
@@ -226,14 +225,15 @@
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
@@ -244,14 +244,15 @@
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
@@ -287,14 +288,15 @@
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
@@ -313,16 +315,19 @@
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
@@ -406,15 +411,17 @@
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
@@ -440,21 +447,25 @@
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/literals.pyi` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApplicationModeType",
     "ApplicationRestoreTypeType",
     "ApplicationStatusType",
     "ArtifactTypeType",
     "CodeContentTypeType",
     "ConfigurationTypeType",
@@ -37,14 +38,15 @@
     "KinesisAnalyticsV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ApplicationModeType = Literal["INTERACTIVE", "STREAMING"]
 ApplicationRestoreTypeType = Literal[
     "RESTORE_FROM_CUSTOM_SNAPSHOT", "RESTORE_FROM_LATEST_SNAPSHOT", "SKIP_RESTORE_FROM_SNAPSHOT"
 ]
 ApplicationStatusType = Literal[
     "AUTOSCALING",
     "DELETING",
@@ -138,14 +140,15 @@
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
@@ -224,14 +227,15 @@
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
@@ -242,14 +246,15 @@
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
@@ -285,14 +290,15 @@
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
@@ -311,16 +317,19 @@
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
@@ -404,15 +413,17 @@
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
@@ -438,21 +449,25 @@
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/paginator.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("kinesisanalyticsv2") as client:
         client: KinesisAnalyticsV2Client
 
         list_application_snapshots_paginator: ListApplicationSnapshotsPaginator = client.get_paginator("list_application_snapshots")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationSnapshotsResponseTypeDef,
     ListApplicationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListApplicationSnapshotsPaginator", "ListApplicationsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,28 +49,28 @@
 class ListApplicationSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplicationSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationsnapshotspaginator)
     """
 
     def paginate(
-        self, *, ApplicationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplicationSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationsnapshotspaginator)
         """
 
 
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/paginator.pyi` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("kinesisanalyticsv2") as client:
         client: KinesisAnalyticsV2Client
 
         list_application_snapshots_paginator: ListApplicationSnapshotsPaginator = client.get_paginator("list_application_snapshots")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationSnapshotsResponseTypeDef,
     ListApplicationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListApplicationSnapshotsPaginator", "ListApplicationsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,27 +46,27 @@
 class ListApplicationSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplicationSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationsnapshotspaginator)
     """
 
     def paginate(
-        self, *, ApplicationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplicationSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationsnapshotspaginator)
         """
 
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/type_defs.py` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -38,15 +38,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CloudWatchLoggingOptionTypeDef",
     "CloudWatchLoggingOptionDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcConfigurationTypeDef",
     "VpcConfigurationDescriptionTypeDef",
     "ApplicationSnapshotConfigurationDescriptionTypeDef",
     "ApplicationSnapshotConfigurationTypeDef",
     "ApplicationSnapshotConfigurationUpdateTypeDef",
     "VpcConfigurationUpdateTypeDef",
     "ApplicationMaintenanceConfigurationDescriptionTypeDef",
@@ -62,24 +61,29 @@
     "CheckpointConfigurationTypeDef",
     "CheckpointConfigurationUpdateTypeDef",
     "CloudWatchLoggingOptionUpdateTypeDef",
     "S3ApplicationCodeLocationDescriptionTypeDef",
     "S3ContentLocationTypeDef",
     "S3ContentLocationUpdateTypeDef",
     "CreateApplicationPresignedUrlRequestRequestTypeDef",
+    "CreateApplicationPresignedUrlResponseTypeDef",
     "TagTypeDef",
     "CreateApplicationSnapshotRequestRequestTypeDef",
     "MavenReferenceTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef",
+    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
     "DeleteApplicationOutputRequestRequestTypeDef",
+    "DeleteApplicationOutputResponseTypeDef",
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
+    "DeleteApplicationReferenceDataSourceResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteApplicationSnapshotRequestRequestTypeDef",
     "DeleteApplicationVpcConfigurationRequestRequestTypeDef",
+    "DeleteApplicationVpcConfigurationResponseTypeDef",
     "S3ContentBaseLocationDescriptionTypeDef",
     "S3ContentBaseLocationTypeDef",
     "S3ContentBaseLocationUpdateTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DescribeApplicationSnapshotRequestRequestTypeDef",
     "SnapshotDetailsTypeDef",
     "DescribeApplicationVersionRequestRequestTypeDef",
@@ -112,36 +116,34 @@
     "KinesisFirehoseOutputUpdateTypeDef",
     "KinesisStreamsOutputDescriptionTypeDef",
     "KinesisStreamsOutputTypeDef",
     "KinesisStreamsOutputUpdateTypeDef",
     "LambdaOutputDescriptionTypeDef",
     "LambdaOutputTypeDef",
     "LambdaOutputUpdateTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
     "ListApplicationSnapshotsRequestRequestTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "S3ReferenceDataSourceDescriptionTypeDef",
     "S3ReferenceDataSourceTypeDef",
     "S3ReferenceDataSourceUpdateTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackApplicationRequestRequestTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ZeppelinMonitoringConfigurationDescriptionTypeDef",
     "ZeppelinMonitoringConfigurationTypeDef",
     "ZeppelinMonitoringConfigurationUpdateTypeDef",
     "AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "AddApplicationCloudWatchLoggingOptionResponseTypeDef",
-    "CreateApplicationPresignedUrlResponseTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionResponseTypeDef",
-    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
-    "DeleteApplicationOutputResponseTypeDef",
-    "DeleteApplicationReferenceDataSourceResponseTypeDef",
-    "DeleteApplicationVpcConfigurationResponseTypeDef",
     "AddApplicationVpcConfigurationRequestRequestTypeDef",
     "AddApplicationVpcConfigurationResponseTypeDef",
     "UpdateApplicationMaintenanceConfigurationResponseTypeDef",
     "UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListApplicationVersionsResponseTypeDef",
     "CatalogConfigurationDescriptionTypeDef",
@@ -171,16 +173,14 @@
     "InputProcessingConfigurationDescriptionTypeDef",
     "InputProcessingConfigurationTypeDef",
     "InputProcessingConfigurationUpdateTypeDef",
     "MappingParametersTypeDef",
     "OutputDescriptionTypeDef",
     "OutputTypeDef",
     "OutputUpdateTypeDef",
-    "ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ApplicationCodeConfigurationDescriptionTypeDef",
     "ApplicationCodeConfigurationTypeDef",
     "ApplicationCodeConfigurationUpdateTypeDef",
     "ZeppelinApplicationConfigurationDescriptionTypeDef",
     "ZeppelinApplicationConfigurationTypeDef",
     "ZeppelinApplicationConfigurationUpdateTypeDef",
     "RunConfigurationTypeDef",
@@ -246,25 +246,14 @@
 class CloudWatchLoggingOptionDescriptionTypeDef(
     _RequiredCloudWatchLoggingOptionDescriptionTypeDef,
     _OptionalCloudWatchLoggingOptionDescriptionTypeDef,
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
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
 )
@@ -560,14 +549,22 @@
 class CreateApplicationPresignedUrlRequestRequestTypeDef(
     _RequiredCreateApplicationPresignedUrlRequestRequestTypeDef,
     _OptionalCreateApplicationPresignedUrlRequestRequestTypeDef,
 ):
     pass
 
 
+CreateApplicationPresignedUrlResponseTypeDef = TypedDict(
+    "CreateApplicationPresignedUrlResponseTypeDef",
+    {
+        "AuthorizedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
@@ -629,32 +626,59 @@
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "InputId": str,
     },
 )
 
+DeleteApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
+    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationOutputRequestRequestTypeDef = TypedDict(
     "DeleteApplicationOutputRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "OutputId": str,
     },
 )
 
+DeleteApplicationOutputResponseTypeDef = TypedDict(
+    "DeleteApplicationOutputResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationReferenceDataSourceRequestRequestTypeDef = TypedDict(
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "ReferenceId": str,
     },
 )
 
+DeleteApplicationReferenceDataSourceResponseTypeDef = TypedDict(
+    "DeleteApplicationReferenceDataSourceResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CreateTimestamp": Union[datetime, str],
     },
 )
@@ -688,14 +712,23 @@
 class DeleteApplicationVpcConfigurationRequestRequestTypeDef(
     _RequiredDeleteApplicationVpcConfigurationRequestRequestTypeDef,
     _OptionalDeleteApplicationVpcConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteApplicationVpcConfigurationResponseTypeDef = TypedDict(
+    "DeleteApplicationVpcConfigurationResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3ContentBaseLocationDescriptionTypeDef = TypedDict(
     "_RequiredS3ContentBaseLocationDescriptionTypeDef",
     {
         "BucketARN": str,
     },
 )
 _OptionalS3ContentBaseLocationDescriptionTypeDef = TypedDict(
@@ -1179,24 +1212,36 @@
 LambdaOutputUpdateTypeDef = TypedDict(
     "LambdaOutputUpdateTypeDef",
     {
         "ResourceARNUpdate": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationName": str,
+    },
+)
+_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef(
+    _RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
+    _OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationSnapshotsRequestRequestTypeDef",
     {
         "ApplicationName": str,
     },
 )
 _OptionalListApplicationSnapshotsRequestRequestTypeDef = TypedDict(
@@ -1235,14 +1280,22 @@
 class ListApplicationVersionsRequestRequestTypeDef(
     _RequiredListApplicationVersionsRequestRequestTypeDef,
     _OptionalListApplicationVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1251,14 +1304,24 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 _RequiredS3ReferenceDataSourceDescriptionTypeDef = TypedDict(
     "_RequiredS3ReferenceDataSourceDescriptionTypeDef",
     {
         "BucketARN": str,
         "FileKey": str,
     },
 )
@@ -1292,14 +1355,25 @@
     {
         "BucketARNUpdate": str,
         "FileKeyUpdate": str,
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
 RollbackApplicationRequestRequestTypeDef = TypedDict(
     "RollbackApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
     },
 )
@@ -1381,69 +1455,25 @@
 
 AddApplicationCloudWatchLoggingOptionResponseTypeDef = TypedDict(
     "AddApplicationCloudWatchLoggingOptionResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "CloudWatchLoggingOptionDescriptions": List[CloudWatchLoggingOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationPresignedUrlResponseTypeDef = TypedDict(
-    "CreateApplicationPresignedUrlResponseTypeDef",
-    {
-        "AuthorizedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteApplicationCloudWatchLoggingOptionResponseTypeDef = TypedDict(
     "DeleteApplicationCloudWatchLoggingOptionResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "CloudWatchLoggingOptionDescriptions": List[CloudWatchLoggingOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
-    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationOutputResponseTypeDef = TypedDict(
-    "DeleteApplicationOutputResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationReferenceDataSourceResponseTypeDef = TypedDict(
-    "DeleteApplicationReferenceDataSourceResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationVpcConfigurationResponseTypeDef = TypedDict(
-    "DeleteApplicationVpcConfigurationResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddApplicationVpcConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredAddApplicationVpcConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1469,26 +1499,26 @@
 
 AddApplicationVpcConfigurationResponseTypeDef = TypedDict(
     "AddApplicationVpcConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "VpcConfigurationDescription": VpcConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationMaintenanceConfigurationResponseTypeDef = TypedDict(
     "UpdateApplicationMaintenanceConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationMaintenanceConfigurationDescription": (
             ApplicationMaintenanceConfigurationDescriptionTypeDef
         ),
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1499,24 +1529,24 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaries": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationVersionsResponseTypeDef = TypedDict(
     "ListApplicationVersionsResponseTypeDef",
     {
         "ApplicationVersionSummaries": List[ApplicationVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CatalogConfigurationDescriptionTypeDef = TypedDict(
     "CatalogConfigurationDescriptionTypeDef",
     {
         "GlueDataCatalogConfigurationDescription": GlueDataCatalogConfigurationDescriptionTypeDef,
@@ -1568,15 +1598,15 @@
     total=False,
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
@@ -1638,24 +1668,24 @@
     total=False,
 )
 
 DescribeApplicationSnapshotResponseTypeDef = TypedDict(
     "DescribeApplicationSnapshotResponseTypeDef",
     {
         "SnapshotDetails": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationSnapshotsResponseTypeDef = TypedDict(
     "ListApplicationSnapshotsResponseTypeDef",
     {
         "SnapshotSummaries": List[SnapshotDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlRunConfigurationTypeDef = TypedDict(
     "SqlRunConfigurationTypeDef",
     {
         "InputId": str,
@@ -1819,44 +1849,14 @@
 )
 
 
 class OutputUpdateTypeDef(_RequiredOutputUpdateTypeDef, _OptionalOutputUpdateTypeDef):
     pass
 
 
-_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-    },
-)
-_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef(
-    _RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-    _OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-):
-    pass
-
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredApplicationCodeConfigurationDescriptionTypeDef = TypedDict(
     "_RequiredApplicationCodeConfigurationDescriptionTypeDef",
     {
         "CodeContentType": CodeContentTypeType,
     },
 )
 _OptionalApplicationCodeConfigurationDescriptionTypeDef = TypedDict(
@@ -1968,15 +1968,15 @@
 AddApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
     "AddApplicationInputProcessingConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "InputId": str,
         "InputProcessingConfigurationDescription": InputProcessingConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationInputProcessingConfigurationRequestRequestTypeDef = TypedDict(
     "AddApplicationInputProcessingConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -2032,15 +2032,15 @@
 
 AddApplicationOutputResponseTypeDef = TypedDict(
     "AddApplicationOutputResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "OutputDescriptions": List[OutputDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationOutputRequestRequestTypeDef = TypedDict(
     "AddApplicationOutputRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -2127,15 +2127,15 @@
 DiscoverInputSchemaResponseTypeDef = TypedDict(
     "DiscoverInputSchemaResponseTypeDef",
     {
         "InputSchema": SourceSchemaTypeDef,
         "ParsedInputRecords": List[List[str]],
         "ProcessedInputRecords": List[str],
         "RawInputRecords": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputDescriptionTypeDef = TypedDict(
     "InputDescriptionTypeDef",
     {
         "InputId": str,
@@ -2244,15 +2244,15 @@
 
 AddApplicationInputResponseTypeDef = TypedDict(
     "AddApplicationInputResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "InputDescriptions": List[InputDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationInputRequestRequestTypeDef = TypedDict(
     "AddApplicationInputRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -2263,15 +2263,15 @@
 
 AddApplicationReferenceDataSourceResponseTypeDef = TypedDict(
     "AddApplicationReferenceDataSourceResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "ReferenceDataSourceDescriptions": List[ReferenceDataSourceDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlApplicationConfigurationDescriptionTypeDef = TypedDict(
     "SqlApplicationConfigurationDescriptionTypeDef",
     {
         "InputDescriptions": List[InputDescriptionTypeDef],
@@ -2448,42 +2448,42 @@
     pass
 
 
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationVersionResponseTypeDef = TypedDict(
     "DescribeApplicationVersionResponseTypeDef",
     {
         "ApplicationVersionDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackApplicationResponseTypeDef = TypedDict(
     "RollbackApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2/type_defs.pyi` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -37,15 +37,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CloudWatchLoggingOptionTypeDef",
     "CloudWatchLoggingOptionDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcConfigurationTypeDef",
     "VpcConfigurationDescriptionTypeDef",
     "ApplicationSnapshotConfigurationDescriptionTypeDef",
     "ApplicationSnapshotConfigurationTypeDef",
     "ApplicationSnapshotConfigurationUpdateTypeDef",
     "VpcConfigurationUpdateTypeDef",
     "ApplicationMaintenanceConfigurationDescriptionTypeDef",
@@ -61,24 +60,29 @@
     "CheckpointConfigurationTypeDef",
     "CheckpointConfigurationUpdateTypeDef",
     "CloudWatchLoggingOptionUpdateTypeDef",
     "S3ApplicationCodeLocationDescriptionTypeDef",
     "S3ContentLocationTypeDef",
     "S3ContentLocationUpdateTypeDef",
     "CreateApplicationPresignedUrlRequestRequestTypeDef",
+    "CreateApplicationPresignedUrlResponseTypeDef",
     "TagTypeDef",
     "CreateApplicationSnapshotRequestRequestTypeDef",
     "MavenReferenceTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef",
+    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
     "DeleteApplicationOutputRequestRequestTypeDef",
+    "DeleteApplicationOutputResponseTypeDef",
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
+    "DeleteApplicationReferenceDataSourceResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteApplicationSnapshotRequestRequestTypeDef",
     "DeleteApplicationVpcConfigurationRequestRequestTypeDef",
+    "DeleteApplicationVpcConfigurationResponseTypeDef",
     "S3ContentBaseLocationDescriptionTypeDef",
     "S3ContentBaseLocationTypeDef",
     "S3ContentBaseLocationUpdateTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DescribeApplicationSnapshotRequestRequestTypeDef",
     "SnapshotDetailsTypeDef",
     "DescribeApplicationVersionRequestRequestTypeDef",
@@ -111,36 +115,34 @@
     "KinesisFirehoseOutputUpdateTypeDef",
     "KinesisStreamsOutputDescriptionTypeDef",
     "KinesisStreamsOutputTypeDef",
     "KinesisStreamsOutputUpdateTypeDef",
     "LambdaOutputDescriptionTypeDef",
     "LambdaOutputTypeDef",
     "LambdaOutputUpdateTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
     "ListApplicationSnapshotsRequestRequestTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "S3ReferenceDataSourceDescriptionTypeDef",
     "S3ReferenceDataSourceTypeDef",
     "S3ReferenceDataSourceUpdateTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackApplicationRequestRequestTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ZeppelinMonitoringConfigurationDescriptionTypeDef",
     "ZeppelinMonitoringConfigurationTypeDef",
     "ZeppelinMonitoringConfigurationUpdateTypeDef",
     "AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "AddApplicationCloudWatchLoggingOptionResponseTypeDef",
-    "CreateApplicationPresignedUrlResponseTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionResponseTypeDef",
-    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
-    "DeleteApplicationOutputResponseTypeDef",
-    "DeleteApplicationReferenceDataSourceResponseTypeDef",
-    "DeleteApplicationVpcConfigurationResponseTypeDef",
     "AddApplicationVpcConfigurationRequestRequestTypeDef",
     "AddApplicationVpcConfigurationResponseTypeDef",
     "UpdateApplicationMaintenanceConfigurationResponseTypeDef",
     "UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListApplicationVersionsResponseTypeDef",
     "CatalogConfigurationDescriptionTypeDef",
@@ -170,16 +172,14 @@
     "InputProcessingConfigurationDescriptionTypeDef",
     "InputProcessingConfigurationTypeDef",
     "InputProcessingConfigurationUpdateTypeDef",
     "MappingParametersTypeDef",
     "OutputDescriptionTypeDef",
     "OutputTypeDef",
     "OutputUpdateTypeDef",
-    "ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ApplicationCodeConfigurationDescriptionTypeDef",
     "ApplicationCodeConfigurationTypeDef",
     "ApplicationCodeConfigurationUpdateTypeDef",
     "ZeppelinApplicationConfigurationDescriptionTypeDef",
     "ZeppelinApplicationConfigurationTypeDef",
     "ZeppelinApplicationConfigurationUpdateTypeDef",
     "RunConfigurationTypeDef",
@@ -243,25 +243,14 @@
 
 class CloudWatchLoggingOptionDescriptionTypeDef(
     _RequiredCloudWatchLoggingOptionDescriptionTypeDef,
     _OptionalCloudWatchLoggingOptionDescriptionTypeDef,
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
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
 )
@@ -541,14 +530,22 @@
 
 class CreateApplicationPresignedUrlRequestRequestTypeDef(
     _RequiredCreateApplicationPresignedUrlRequestRequestTypeDef,
     _OptionalCreateApplicationPresignedUrlRequestRequestTypeDef,
 ):
     pass
 
+CreateApplicationPresignedUrlResponseTypeDef = TypedDict(
+    "CreateApplicationPresignedUrlResponseTypeDef",
+    {
+        "AuthorizedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
@@ -606,32 +603,59 @@
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "InputId": str,
     },
 )
 
+DeleteApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
+    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationOutputRequestRequestTypeDef = TypedDict(
     "DeleteApplicationOutputRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "OutputId": str,
     },
 )
 
+DeleteApplicationOutputResponseTypeDef = TypedDict(
+    "DeleteApplicationOutputResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationReferenceDataSourceRequestRequestTypeDef = TypedDict(
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "ReferenceId": str,
     },
 )
 
+DeleteApplicationReferenceDataSourceResponseTypeDef = TypedDict(
+    "DeleteApplicationReferenceDataSourceResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CreateTimestamp": Union[datetime, str],
     },
 )
@@ -663,14 +687,23 @@
 
 class DeleteApplicationVpcConfigurationRequestRequestTypeDef(
     _RequiredDeleteApplicationVpcConfigurationRequestRequestTypeDef,
     _OptionalDeleteApplicationVpcConfigurationRequestRequestTypeDef,
 ):
     pass
 
+DeleteApplicationVpcConfigurationResponseTypeDef = TypedDict(
+    "DeleteApplicationVpcConfigurationResponseTypeDef",
+    {
+        "ApplicationARN": str,
+        "ApplicationVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3ContentBaseLocationDescriptionTypeDef = TypedDict(
     "_RequiredS3ContentBaseLocationDescriptionTypeDef",
     {
         "BucketARN": str,
     },
 )
 _OptionalS3ContentBaseLocationDescriptionTypeDef = TypedDict(
@@ -1128,24 +1161,34 @@
 LambdaOutputUpdateTypeDef = TypedDict(
     "LambdaOutputUpdateTypeDef",
     {
         "ResourceARNUpdate": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationName": str,
+    },
+)
+_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef(
+    _RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
+    _OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationSnapshotsRequestRequestTypeDef",
     {
         "ApplicationName": str,
     },
 )
 _OptionalListApplicationSnapshotsRequestRequestTypeDef = TypedDict(
@@ -1180,14 +1223,22 @@
 
 class ListApplicationVersionsRequestRequestTypeDef(
     _RequiredListApplicationVersionsRequestRequestTypeDef,
     _OptionalListApplicationVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1196,14 +1247,24 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 _RequiredS3ReferenceDataSourceDescriptionTypeDef = TypedDict(
     "_RequiredS3ReferenceDataSourceDescriptionTypeDef",
     {
         "BucketARN": str,
         "FileKey": str,
     },
 )
@@ -1235,14 +1296,25 @@
     {
         "BucketARNUpdate": str,
         "FileKeyUpdate": str,
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
 RollbackApplicationRequestRequestTypeDef = TypedDict(
     "RollbackApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
     },
 )
@@ -1320,69 +1392,25 @@
 
 AddApplicationCloudWatchLoggingOptionResponseTypeDef = TypedDict(
     "AddApplicationCloudWatchLoggingOptionResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "CloudWatchLoggingOptionDescriptions": List[CloudWatchLoggingOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationPresignedUrlResponseTypeDef = TypedDict(
-    "CreateApplicationPresignedUrlResponseTypeDef",
-    {
-        "AuthorizedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteApplicationCloudWatchLoggingOptionResponseTypeDef = TypedDict(
     "DeleteApplicationCloudWatchLoggingOptionResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "CloudWatchLoggingOptionDescriptions": List[CloudWatchLoggingOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
-    "DeleteApplicationInputProcessingConfigurationResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationOutputResponseTypeDef = TypedDict(
-    "DeleteApplicationOutputResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationReferenceDataSourceResponseTypeDef = TypedDict(
-    "DeleteApplicationReferenceDataSourceResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationVpcConfigurationResponseTypeDef = TypedDict(
-    "DeleteApplicationVpcConfigurationResponseTypeDef",
-    {
-        "ApplicationARN": str,
-        "ApplicationVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddApplicationVpcConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredAddApplicationVpcConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1406,26 +1434,26 @@
 
 AddApplicationVpcConfigurationResponseTypeDef = TypedDict(
     "AddApplicationVpcConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "VpcConfigurationDescription": VpcConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationMaintenanceConfigurationResponseTypeDef = TypedDict(
     "UpdateApplicationMaintenanceConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationMaintenanceConfigurationDescription": (
             ApplicationMaintenanceConfigurationDescriptionTypeDef
         ),
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1436,24 +1464,24 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaries": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationVersionsResponseTypeDef = TypedDict(
     "ListApplicationVersionsResponseTypeDef",
     {
         "ApplicationVersionSummaries": List[ApplicationVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CatalogConfigurationDescriptionTypeDef = TypedDict(
     "CatalogConfigurationDescriptionTypeDef",
     {
         "GlueDataCatalogConfigurationDescription": GlueDataCatalogConfigurationDescriptionTypeDef,
@@ -1505,15 +1533,15 @@
     total=False,
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
@@ -1573,24 +1601,24 @@
     total=False,
 )
 
 DescribeApplicationSnapshotResponseTypeDef = TypedDict(
     "DescribeApplicationSnapshotResponseTypeDef",
     {
         "SnapshotDetails": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationSnapshotsResponseTypeDef = TypedDict(
     "ListApplicationSnapshotsResponseTypeDef",
     {
         "SnapshotSummaries": List[SnapshotDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlRunConfigurationTypeDef = TypedDict(
     "SqlRunConfigurationTypeDef",
     {
         "InputId": str,
@@ -1750,42 +1778,14 @@
     },
     total=False,
 )
 
 class OutputUpdateTypeDef(_RequiredOutputUpdateTypeDef, _OptionalOutputUpdateTypeDef):
     pass
 
-_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-    },
-)
-_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef(
-    _RequiredListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-    _OptionalListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-):
-    pass
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredApplicationCodeConfigurationDescriptionTypeDef = TypedDict(
     "_RequiredApplicationCodeConfigurationDescriptionTypeDef",
     {
         "CodeContentType": CodeContentTypeType,
     },
 )
 _OptionalApplicationCodeConfigurationDescriptionTypeDef = TypedDict(
@@ -1891,15 +1891,15 @@
 AddApplicationInputProcessingConfigurationResponseTypeDef = TypedDict(
     "AddApplicationInputProcessingConfigurationResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "InputId": str,
         "InputProcessingConfigurationDescription": InputProcessingConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationInputProcessingConfigurationRequestRequestTypeDef = TypedDict(
     "AddApplicationInputProcessingConfigurationRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1951,15 +1951,15 @@
 
 AddApplicationOutputResponseTypeDef = TypedDict(
     "AddApplicationOutputResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "OutputDescriptions": List[OutputDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationOutputRequestRequestTypeDef = TypedDict(
     "AddApplicationOutputRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -2040,15 +2040,15 @@
 DiscoverInputSchemaResponseTypeDef = TypedDict(
     "DiscoverInputSchemaResponseTypeDef",
     {
         "InputSchema": SourceSchemaTypeDef,
         "ParsedInputRecords": List[List[str]],
         "ProcessedInputRecords": List[str],
         "RawInputRecords": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputDescriptionTypeDef = TypedDict(
     "InputDescriptionTypeDef",
     {
         "InputId": str,
@@ -2149,15 +2149,15 @@
 
 AddApplicationInputResponseTypeDef = TypedDict(
     "AddApplicationInputResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "InputDescriptions": List[InputDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddApplicationInputRequestRequestTypeDef = TypedDict(
     "AddApplicationInputRequestRequestTypeDef",
     {
         "ApplicationName": str,
@@ -2168,15 +2168,15 @@
 
 AddApplicationReferenceDataSourceResponseTypeDef = TypedDict(
     "AddApplicationReferenceDataSourceResponseTypeDef",
     {
         "ApplicationARN": str,
         "ApplicationVersionId": int,
         "ReferenceDataSourceDescriptions": List[ReferenceDataSourceDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlApplicationConfigurationDescriptionTypeDef = TypedDict(
     "SqlApplicationConfigurationDescriptionTypeDef",
     {
         "InputDescriptions": List[InputDescriptionTypeDef],
@@ -2347,42 +2347,42 @@
 ):
     pass
 
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationVersionResponseTypeDef = TypedDict(
     "DescribeApplicationVersionResponseTypeDef",
     {
         "ApplicationVersionDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackApplicationResponseTypeDef = TypedDict(
     "RollbackApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/PKG-INFO` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisanalyticsv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisAnalyticsV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisanalyticsv2"></a>
 
 # types-aiobotocore-kinesisanalyticsv2
 
 [![PyPI - types-aiobotocore-kinesisanalyticsv2](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalyticsv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalyticsv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalyticsv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalyticsv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalyticsV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
+[aiobotocore.KinesisAnalyticsV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalyticsv2.html#KinesisAnalyticsV2)
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
 [types-aiobotocore-kinesisanalyticsv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalyticsv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -338,15 +338,14 @@
 `types_aiobotocore_kinesisanalyticsv2.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisanalyticsv2.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     VpcConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationDescriptionTypeDef,
     ApplicationSnapshotConfigurationTypeDef,
     ApplicationSnapshotConfigurationUpdateTypeDef,
     VpcConfigurationUpdateTypeDef,
     ApplicationMaintenanceConfigurationDescriptionTypeDef,
@@ -362,24 +361,29 @@
     CheckpointConfigurationTypeDef,
     CheckpointConfigurationUpdateTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     S3ApplicationCodeLocationDescriptionTypeDef,
     S3ContentLocationTypeDef,
     S3ContentLocationUpdateTypeDef,
     CreateApplicationPresignedUrlRequestRequestTypeDef,
+    CreateApplicationPresignedUrlResponseTypeDef,
     TagTypeDef,
     CreateApplicationSnapshotRequestRequestTypeDef,
     MavenReferenceTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
+    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
+    DeleteApplicationOutputResponseTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
+    DeleteApplicationReferenceDataSourceResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteApplicationSnapshotRequestRequestTypeDef,
     DeleteApplicationVpcConfigurationRequestRequestTypeDef,
+    DeleteApplicationVpcConfigurationResponseTypeDef,
     S3ContentBaseLocationDescriptionTypeDef,
     S3ContentBaseLocationTypeDef,
     S3ContentBaseLocationUpdateTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeApplicationSnapshotRequestRequestTypeDef,
     SnapshotDetailsTypeDef,
     DescribeApplicationVersionRequestRequestTypeDef,
@@ -412,36 +416,34 @@
     KinesisFirehoseOutputUpdateTypeDef,
     KinesisStreamsOutputDescriptionTypeDef,
     KinesisStreamsOutputTypeDef,
     KinesisStreamsOutputUpdateTypeDef,
     LambdaOutputDescriptionTypeDef,
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
     ListApplicationSnapshotsRequestRequestTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     RollbackApplicationRequestRequestTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ZeppelinMonitoringConfigurationDescriptionTypeDef,
     ZeppelinMonitoringConfigurationTypeDef,
     ZeppelinMonitoringConfigurationUpdateTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionResponseTypeDef,
-    CreateApplicationPresignedUrlResponseTypeDef,
     DeleteApplicationCloudWatchLoggingOptionResponseTypeDef,
-    DeleteApplicationInputProcessingConfigurationResponseTypeDef,
-    DeleteApplicationOutputResponseTypeDef,
-    DeleteApplicationReferenceDataSourceResponseTypeDef,
-    DeleteApplicationVpcConfigurationResponseTypeDef,
     AddApplicationVpcConfigurationRequestRequestTypeDef,
     AddApplicationVpcConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationResponseTypeDef,
     UpdateApplicationMaintenanceConfigurationRequestRequestTypeDef,
     ListApplicationsResponseTypeDef,
     ListApplicationVersionsResponseTypeDef,
     CatalogConfigurationDescriptionTypeDef,
@@ -471,16 +473,14 @@
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
     OutputUpdateTypeDef,
-    ListApplicationSnapshotsRequestListApplicationSnapshotsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ApplicationCodeConfigurationDescriptionTypeDef,
     ApplicationCodeConfigurationTypeDef,
     ApplicationCodeConfigurationUpdateTypeDef,
     ZeppelinApplicationConfigurationDescriptionTypeDef,
     ZeppelinApplicationConfigurationTypeDef,
     ZeppelinApplicationConfigurationUpdateTypeDef,
     RunConfigurationTypeDef,
@@ -528,43 +528,43 @@
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

### Comparing `types-aiobotocore-kinesisanalyticsv2-2.5.0.post1/types_aiobotocore_kinesisanalyticsv2.egg-info/SOURCES.txt` & `types-aiobotocore-kinesisanalyticsv2-2.5.1/types_aiobotocore_kinesisanalyticsv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

