# Comparing `tmp/types-aiobotocore-kinesisanalytics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesisanalytics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesisanalytics-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesisanalytics-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1.tar` & `types-aiobotocore-kinesisanalytics-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.603346 types-aiobotocore-kinesisanalytics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15620 2023-03-11 12:26:51.603346 types-aiobotocore-kinesisanalytics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14013 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.607346 types-aiobotocore-kinesisanalytics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.603346 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/
--rw-r--r--   0 runner    (1001) docker     (123)      514 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17044 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17016 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8166 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8164 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25963 2023-03-11 12:17:00.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25932 2023-03-11 12:17:00.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:58.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.603346 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15620 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      887 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.938162 types-aiobotocore-kinesisanalytics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15621 2023-06-28 01:43:42.938162 types-aiobotocore-kinesisanalytics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14020 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.938162 types-aiobotocore-kinesisanalytics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:33:39.000000 types-aiobotocore-kinesisanalytics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.934162 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/
+-rw-r--r--   0 runner    (1001) docker     (123)      514 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17044 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17016 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8453 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8451 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25973 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25942 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:40.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.938162 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15621 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      887 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesisanalytics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesisanalytics-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisanalytics"></a>
 
 # types-aiobotocore-kinesisanalytics
 
 [![PyPI - types-aiobotocore-kinesisanalytics](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
+[aiobotocore.KinesisAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
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
 [types-aiobotocore-kinesisanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,15 +298,14 @@
 from types_aiobotocore_kinesisanalytics.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
     ApplicationSummaryTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     CSVMappingParametersTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DestinationSchemaTypeDef,
@@ -335,21 +334,22 @@
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
     CreateApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     InputConfigurationTypeDef,
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/README.md` & `types-aiobotocore-kinesisanalytics-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesisanalytics"></a>
 
 # types-aiobotocore-kinesisanalytics
 
 [![PyPI - types-aiobotocore-kinesisanalytics](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
+[aiobotocore.KinesisAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
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
 [types-aiobotocore-kinesisanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,15 +265,14 @@
 from types_aiobotocore_kinesisanalytics.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
     ApplicationSummaryTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     CSVMappingParametersTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DestinationSchemaTypeDef,
@@ -302,21 +301,22 @@
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
     CreateApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     InputConfigurationTypeDef,
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
@@ -352,43 +352,43 @@
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/setup.py` & `types-aiobotocore-kinesisanalytics-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesisanalytics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesisanalytics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesisanalytics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisAnalytics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisAnalytics 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/"
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__init__.py` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__init__.pyi` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/__main__.py` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KinesisAnalytics 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KinesisAnalytics 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics\nOther"
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/client.py` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/client.pyi` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/literals.py` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,26 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationStatusType",
     "InputStartingPositionType",
     "RecordFormatTypeType",
     "KinesisAnalyticsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ApplicationStatusType = Literal["DELETING", "READY", "RUNNING", "STARTING", "STOPPING", "UPDATING"]
 InputStartingPositionType = Literal["LAST_STOPPED_POINT", "NOW", "TRIM_HORIZON"]
 RecordFormatTypeType = Literal["CSV", "JSON"]
 KinesisAnalyticsServiceName = Literal["kinesisanalytics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -92,14 +90,15 @@
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
@@ -178,14 +177,15 @@
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
@@ -196,14 +196,15 @@
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
@@ -239,14 +240,15 @@
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
@@ -265,16 +267,19 @@
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
@@ -358,15 +363,17 @@
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
@@ -391,21 +398,25 @@
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/literals.pyi` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -14,24 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApplicationStatusType",
     "InputStartingPositionType",
     "RecordFormatTypeType",
     "KinesisAnalyticsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ApplicationStatusType = Literal["DELETING", "READY", "RUNNING", "STARTING", "STOPPING", "UPDATING"]
 InputStartingPositionType = Literal["LAST_STOPPED_POINT", "NOW", "TRIM_HORIZON"]
 RecordFormatTypeType = Literal["CSV", "JSON"]
 KinesisAnalyticsServiceName = Literal["kinesisanalytics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -90,14 +92,15 @@
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
@@ -176,14 +179,15 @@
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
@@ -194,14 +198,15 @@
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
@@ -237,14 +242,15 @@
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
@@ -263,16 +269,19 @@
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
@@ -356,15 +365,17 @@
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
@@ -389,21 +400,25 @@
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/type_defs.py` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,15 +26,14 @@
 __all__ = (
     "CloudWatchLoggingOptionTypeDef",
     "CloudWatchLoggingOptionDescriptionTypeDef",
     "ApplicationSummaryTypeDef",
     "CloudWatchLoggingOptionUpdateTypeDef",
     "CSVMappingParametersTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef",
     "DeleteApplicationOutputRequestRequestTypeDef",
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DestinationSchemaTypeDef",
@@ -63,21 +62,22 @@
     "LambdaOutputTypeDef",
     "LambdaOutputUpdateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "S3ReferenceDataSourceDescriptionTypeDef",
     "S3ReferenceDataSourceTypeDef",
     "S3ReferenceDataSourceUpdateTypeDef",
+    "ResponseMetadataTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
     "CreateApplicationResponseTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "InputConfigurationTypeDef",
     "InputProcessingConfigurationDescriptionTypeDef",
     "InputProcessingConfigurationTypeDef",
     "InputProcessingConfigurationUpdateTypeDef",
     "MappingParametersTypeDef",
     "OutputDescriptionTypeDef",
     "OutputTypeDef",
@@ -190,25 +190,14 @@
 )
 
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
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
 DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef = TypedDict(
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "CloudWatchLoggingOptionId": str,
     },
@@ -519,14 +508,25 @@
         "BucketARNUpdate": str,
         "FileKeyUpdate": str,
         "ReferenceRoleARNUpdate": str,
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
 StopApplicationRequestRequestTypeDef = TypedDict(
     "StopApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
     },
 )
 
@@ -543,44 +543,44 @@
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "CloudWatchLoggingOption": CloudWatchLoggingOptionTypeDef,
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationSummary": ApplicationSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaries": List[ApplicationSummaryTypeDef],
         "HasMoreApplications": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
+    {
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 InputConfigurationTypeDef = TypedDict(
     "InputConfigurationTypeDef",
     {
         "Id": str,
@@ -792,15 +792,15 @@
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
@@ -994,15 +994,15 @@
     total=False,
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationRequestRequestTypeDef = TypedDict(
     "UpdateApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
```

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics/type_defs.pyi` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -25,15 +25,14 @@
 __all__ = (
     "CloudWatchLoggingOptionTypeDef",
     "CloudWatchLoggingOptionDescriptionTypeDef",
     "ApplicationSummaryTypeDef",
     "CloudWatchLoggingOptionUpdateTypeDef",
     "CSVMappingParametersTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     "DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef",
     "DeleteApplicationOutputRequestRequestTypeDef",
     "DeleteApplicationReferenceDataSourceRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DestinationSchemaTypeDef",
@@ -62,21 +61,22 @@
     "LambdaOutputTypeDef",
     "LambdaOutputUpdateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "S3ReferenceDataSourceDescriptionTypeDef",
     "S3ReferenceDataSourceTypeDef",
     "S3ReferenceDataSourceUpdateTypeDef",
+    "ResponseMetadataTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
     "CreateApplicationResponseTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "InputConfigurationTypeDef",
     "InputProcessingConfigurationDescriptionTypeDef",
     "InputProcessingConfigurationTypeDef",
     "InputProcessingConfigurationUpdateTypeDef",
     "MappingParametersTypeDef",
     "OutputDescriptionTypeDef",
     "OutputTypeDef",
@@ -183,25 +183,14 @@
     },
     total=False,
 )
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
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
 DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef = TypedDict(
     "DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef",
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "CloudWatchLoggingOptionId": str,
     },
@@ -510,14 +499,25 @@
         "BucketARNUpdate": str,
         "FileKeyUpdate": str,
         "ReferenceRoleARNUpdate": str,
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
 StopApplicationRequestRequestTypeDef = TypedDict(
     "StopApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
     },
 )
 
@@ -534,44 +534,44 @@
     {
         "ApplicationName": str,
         "CurrentApplicationVersionId": int,
         "CloudWatchLoggingOption": CloudWatchLoggingOptionTypeDef,
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationSummary": ApplicationSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaries": List[ApplicationSummaryTypeDef],
         "HasMoreApplications": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
+    {
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 InputConfigurationTypeDef = TypedDict(
     "InputConfigurationTypeDef",
     {
         "Id": str,
@@ -773,15 +773,15 @@
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
@@ -963,15 +963,15 @@
     total=False,
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationDetail": ApplicationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationRequestRequestTypeDef = TypedDict(
     "UpdateApplicationRequestRequestTypeDef",
     {
         "ApplicationName": str,
```

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/PKG-INFO` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisanalytics"></a>
 
 # types-aiobotocore-kinesisanalytics
 
 [![PyPI - types-aiobotocore-kinesisanalytics](https://img.shields.io/pypi/v/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
+[aiobotocore.KinesisAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
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
 [types-aiobotocore-kinesisanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,15 +298,14 @@
 from types_aiobotocore_kinesisanalytics.type_defs import (
     CloudWatchLoggingOptionTypeDef,
     CloudWatchLoggingOptionDescriptionTypeDef,
     ApplicationSummaryTypeDef,
     CloudWatchLoggingOptionUpdateTypeDef,
     CSVMappingParametersTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
     DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef,
     DeleteApplicationOutputRequestRequestTypeDef,
     DeleteApplicationReferenceDataSourceRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DestinationSchemaTypeDef,
@@ -335,21 +334,22 @@
     LambdaOutputTypeDef,
     LambdaOutputUpdateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ReferenceDataSourceDescriptionTypeDef,
     S3ReferenceDataSourceTypeDef,
     S3ReferenceDataSourceUpdateTypeDef,
+    ResponseMetadataTypeDef,
     StopApplicationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
     CreateApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     InputConfigurationTypeDef,
     InputProcessingConfigurationDescriptionTypeDef,
     InputProcessingConfigurationTypeDef,
     InputProcessingConfigurationUpdateTypeDef,
     MappingParametersTypeDef,
     OutputDescriptionTypeDef,
     OutputTypeDef,
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-kinesisanalytics-2.5.0.post1/types_aiobotocore_kinesisanalytics.egg-info/SOURCES.txt` & `types-aiobotocore-kinesisanalytics-2.5.1/types_aiobotocore_kinesisanalytics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

