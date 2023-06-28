# Comparing `tmp/types-aiobotocore-firehose-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-firehose-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-firehose-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:38 2023, max compression
+gzip compressed data, was "types-aiobotocore-firehose-2.5.1.tar", last modified: Wed Jun 28 01:43:30 2023, max compression
```

## Comparing `types-aiobotocore-firehose-2.5.0.post1.tar` & `types-aiobotocore-firehose-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:38.983219 types-aiobotocore-firehose-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16447 2023-03-11 12:26:38.979220 types-aiobotocore-firehose-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14872 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:38.983219 types-aiobotocore-firehose-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:38.979220 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14113 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14093 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11077 2023-03-11 12:14:36.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11075 2023-03-11 12:14:36.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    45019 2023-03-11 12:14:36.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44970 2023-03-11 12:14:36.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:35.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:38.979220 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16447 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:38.000000 types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.590139 types-aiobotocore-firehose-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16440 2023-06-28 01:43:30.590139 types-aiobotocore-firehose-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14871 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:30.590139 types-aiobotocore-firehose-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.590139 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14113 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14093 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11308 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11306 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    45031 2023-06-28 01:31:13.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44982 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:12.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.590139 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16440 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:30.000000 types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-firehose-2.5.0.post1/LICENSE` & `types-aiobotocore-firehose-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/PKG-INFO` & `types-aiobotocore-firehose-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-firehose
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Firehose 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Firehose 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-firehose"></a>
 
 # types-aiobotocore-firehose
 
 [![PyPI - types-aiobotocore-firehose](https://img.shields.io/pypi/v/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-firehose?color=blue)](https://pypistats.org/packages/types-aiobotocore-firehose)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Firehose 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
+[aiobotocore.Firehose 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
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
 [types-aiobotocore-firehose docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/).
 
 See how it helps to find and fix potential bugs:
 
@@ -324,15 +324,15 @@
     AmazonopensearchserviceBufferingHintsTypeDef,
     AmazonopensearchserviceRetryOptionsTypeDef,
     BufferingHintsTypeDef,
     CopyCommandTypeDef,
     DeliveryStreamEncryptionConfigurationInputTypeDef,
     KinesisStreamSourceConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliveryStreamOutputTypeDef,
     SchemaConfigurationTypeDef,
     DeleteDeliveryStreamInputRequestTypeDef,
     FailureDescriptionTypeDef,
     DescribeDeliveryStreamInputRequestTypeDef,
     HiveJsonSerDeTypeDef,
     OpenXJsonSerDeTypeDef,
     RetryOptionsTypeDef,
@@ -342,30 +342,30 @@
     HttpEndpointBufferingHintsTypeDef,
     HttpEndpointCommonAttributeTypeDef,
     HttpEndpointConfigurationTypeDef,
     HttpEndpointDescriptionTypeDef,
     HttpEndpointRetryOptionsTypeDef,
     KinesisStreamSourceDescriptionTypeDef,
     ListDeliveryStreamsInputRequestTypeDef,
+    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamInputRequestTypeDef,
     OrcSerDeTypeDef,
     ParquetSerDeTypeDef,
     ProcessorParameterTypeDef,
     RecordTypeDef,
     PutRecordBatchResponseEntryTypeDef,
+    PutRecordOutputTypeDef,
     RedshiftRetryOptionsTypeDef,
+    ResponseMetadataTypeDef,
     SplunkRetryOptionsTypeDef,
     StopDeliveryStreamEncryptionInputRequestTypeDef,
     UntagDeliveryStreamInputRequestTypeDef,
     StartDeliveryStreamEncryptionInputRequestTypeDef,
-    TagDeliveryStreamInputRequestTypeDef,
-    CreateDeliveryStreamOutputTypeDef,
-    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamOutputTypeDef,
-    PutRecordOutputTypeDef,
+    TagDeliveryStreamInputRequestTypeDef,
     DeliveryStreamEncryptionConfigurationTypeDef,
     DeserializerTypeDef,
     DynamicPartitioningConfigurationTypeDef,
     EncryptionConfigurationTypeDef,
     HttpEndpointRequestConfigurationTypeDef,
     SourceDescriptionTypeDef,
     SerializerTypeDef,
@@ -416,43 +416,43 @@
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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/README.md` & `types-aiobotocore-firehose-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-firehose"></a>
 
 # types-aiobotocore-firehose
 
 [![PyPI - types-aiobotocore-firehose](https://img.shields.io/pypi/v/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-firehose?color=blue)](https://pypistats.org/packages/types-aiobotocore-firehose)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Firehose 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
+[aiobotocore.Firehose 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
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
 [types-aiobotocore-firehose docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,15 +291,15 @@
     AmazonopensearchserviceBufferingHintsTypeDef,
     AmazonopensearchserviceRetryOptionsTypeDef,
     BufferingHintsTypeDef,
     CopyCommandTypeDef,
     DeliveryStreamEncryptionConfigurationInputTypeDef,
     KinesisStreamSourceConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliveryStreamOutputTypeDef,
     SchemaConfigurationTypeDef,
     DeleteDeliveryStreamInputRequestTypeDef,
     FailureDescriptionTypeDef,
     DescribeDeliveryStreamInputRequestTypeDef,
     HiveJsonSerDeTypeDef,
     OpenXJsonSerDeTypeDef,
     RetryOptionsTypeDef,
@@ -309,30 +309,30 @@
     HttpEndpointBufferingHintsTypeDef,
     HttpEndpointCommonAttributeTypeDef,
     HttpEndpointConfigurationTypeDef,
     HttpEndpointDescriptionTypeDef,
     HttpEndpointRetryOptionsTypeDef,
     KinesisStreamSourceDescriptionTypeDef,
     ListDeliveryStreamsInputRequestTypeDef,
+    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamInputRequestTypeDef,
     OrcSerDeTypeDef,
     ParquetSerDeTypeDef,
     ProcessorParameterTypeDef,
     RecordTypeDef,
     PutRecordBatchResponseEntryTypeDef,
+    PutRecordOutputTypeDef,
     RedshiftRetryOptionsTypeDef,
+    ResponseMetadataTypeDef,
     SplunkRetryOptionsTypeDef,
     StopDeliveryStreamEncryptionInputRequestTypeDef,
     UntagDeliveryStreamInputRequestTypeDef,
     StartDeliveryStreamEncryptionInputRequestTypeDef,
-    TagDeliveryStreamInputRequestTypeDef,
-    CreateDeliveryStreamOutputTypeDef,
-    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamOutputTypeDef,
-    PutRecordOutputTypeDef,
+    TagDeliveryStreamInputRequestTypeDef,
     DeliveryStreamEncryptionConfigurationTypeDef,
     DeserializerTypeDef,
     DynamicPartitioningConfigurationTypeDef,
     EncryptionConfigurationTypeDef,
     HttpEndpointRequestConfigurationTypeDef,
     SourceDescriptionTypeDef,
     SerializerTypeDef,
@@ -383,43 +383,43 @@
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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/setup.py` & `types-aiobotocore-firehose-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-firehose.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-firehose",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_firehose"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Firehose 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Firehose 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/"
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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/__main__.py` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Firehose 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Firehose 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose\nOther"
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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/client.py` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/client.pyi` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/literals.py` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -170,14 +170,15 @@
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
@@ -256,14 +257,15 @@
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
@@ -274,14 +276,15 @@
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
@@ -317,14 +320,15 @@
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
@@ -343,16 +347,19 @@
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
@@ -436,15 +443,17 @@
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
@@ -473,14 +482,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/literals.pyi` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -168,14 +168,15 @@
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
@@ -254,14 +255,15 @@
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
@@ -272,14 +274,15 @@
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
@@ -315,14 +318,15 @@
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
@@ -341,16 +345,19 @@
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
@@ -434,15 +441,17 @@
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
@@ -471,14 +480,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/type_defs.py` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -62,15 +62,15 @@
     "AmazonopensearchserviceBufferingHintsTypeDef",
     "AmazonopensearchserviceRetryOptionsTypeDef",
     "BufferingHintsTypeDef",
     "CopyCommandTypeDef",
     "DeliveryStreamEncryptionConfigurationInputTypeDef",
     "KinesisStreamSourceConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDeliveryStreamOutputTypeDef",
     "SchemaConfigurationTypeDef",
     "DeleteDeliveryStreamInputRequestTypeDef",
     "FailureDescriptionTypeDef",
     "DescribeDeliveryStreamInputRequestTypeDef",
     "HiveJsonSerDeTypeDef",
     "OpenXJsonSerDeTypeDef",
     "RetryOptionsTypeDef",
@@ -80,30 +80,30 @@
     "HttpEndpointBufferingHintsTypeDef",
     "HttpEndpointCommonAttributeTypeDef",
     "HttpEndpointConfigurationTypeDef",
     "HttpEndpointDescriptionTypeDef",
     "HttpEndpointRetryOptionsTypeDef",
     "KinesisStreamSourceDescriptionTypeDef",
     "ListDeliveryStreamsInputRequestTypeDef",
+    "ListDeliveryStreamsOutputTypeDef",
     "ListTagsForDeliveryStreamInputRequestTypeDef",
     "OrcSerDeTypeDef",
     "ParquetSerDeTypeDef",
     "ProcessorParameterTypeDef",
     "RecordTypeDef",
     "PutRecordBatchResponseEntryTypeDef",
+    "PutRecordOutputTypeDef",
     "RedshiftRetryOptionsTypeDef",
+    "ResponseMetadataTypeDef",
     "SplunkRetryOptionsTypeDef",
     "StopDeliveryStreamEncryptionInputRequestTypeDef",
     "UntagDeliveryStreamInputRequestTypeDef",
     "StartDeliveryStreamEncryptionInputRequestTypeDef",
-    "TagDeliveryStreamInputRequestTypeDef",
-    "CreateDeliveryStreamOutputTypeDef",
-    "ListDeliveryStreamsOutputTypeDef",
     "ListTagsForDeliveryStreamOutputTypeDef",
-    "PutRecordOutputTypeDef",
+    "TagDeliveryStreamInputRequestTypeDef",
     "DeliveryStreamEncryptionConfigurationTypeDef",
     "DeserializerTypeDef",
     "DynamicPartitioningConfigurationTypeDef",
     "EncryptionConfigurationTypeDef",
     "HttpEndpointRequestConfigurationTypeDef",
     "SourceDescriptionTypeDef",
     "SerializerTypeDef",
@@ -283,22 +283,19 @@
 )
 
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDeliveryStreamOutputTypeDef = TypedDict(
+    "CreateDeliveryStreamOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DeliveryStreamARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaConfigurationTypeDef = TypedDict(
     "SchemaConfigurationTypeDef",
     {
         "RoleARN": str,
@@ -486,14 +483,23 @@
         "Limit": int,
         "DeliveryStreamType": DeliveryStreamTypeType,
         "ExclusiveStartDeliveryStreamName": str,
     },
     total=False,
 )
 
+ListDeliveryStreamsOutputTypeDef = TypedDict(
+    "ListDeliveryStreamsOutputTypeDef",
+    {
+        "DeliveryStreamNames": List[str],
+        "HasMoreDeliveryStreams": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListTagsForDeliveryStreamInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForDeliveryStreamInputRequestTypeDef",
     {
         "DeliveryStreamName": str,
     },
 )
 _OptionalListTagsForDeliveryStreamInputRequestTypeDef = TypedDict(
@@ -564,22 +570,42 @@
         "RecordId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+PutRecordOutputTypeDef = TypedDict(
+    "PutRecordOutputTypeDef",
+    {
+        "RecordId": str,
+        "Encrypted": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedshiftRetryOptionsTypeDef = TypedDict(
     "RedshiftRetryOptionsTypeDef",
     {
         "DurationInSeconds": int,
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
 SplunkRetryOptionsTypeDef = TypedDict(
     "SplunkRetryOptionsTypeDef",
     {
         "DurationInSeconds": int,
     },
     total=False,
 )
@@ -619,54 +645,28 @@
 class StartDeliveryStreamEncryptionInputRequestTypeDef(
     _RequiredStartDeliveryStreamEncryptionInputRequestTypeDef,
     _OptionalStartDeliveryStreamEncryptionInputRequestTypeDef,
 ):
     pass
 
 
-TagDeliveryStreamInputRequestTypeDef = TypedDict(
-    "TagDeliveryStreamInputRequestTypeDef",
-    {
-        "DeliveryStreamName": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateDeliveryStreamOutputTypeDef = TypedDict(
-    "CreateDeliveryStreamOutputTypeDef",
-    {
-        "DeliveryStreamARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeliveryStreamsOutputTypeDef = TypedDict(
-    "ListDeliveryStreamsOutputTypeDef",
-    {
-        "DeliveryStreamNames": List[str],
-        "HasMoreDeliveryStreams": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForDeliveryStreamOutputTypeDef = TypedDict(
     "ListTagsForDeliveryStreamOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "HasMoreTags": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutRecordOutputTypeDef = TypedDict(
-    "PutRecordOutputTypeDef",
+TagDeliveryStreamInputRequestTypeDef = TypedDict(
+    "TagDeliveryStreamInputRequestTypeDef",
     {
-        "RecordId": str,
-        "Encrypted": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeliveryStreamName": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 DeliveryStreamEncryptionConfigurationTypeDef = TypedDict(
     "DeliveryStreamEncryptionConfigurationTypeDef",
     {
         "KeyARN": str,
@@ -767,15 +767,15 @@
 
 PutRecordBatchOutputTypeDef = TypedDict(
     "PutRecordBatchOutputTypeDef",
     {
         "FailedPutCount": int,
         "Encrypted": bool,
         "RequestResponses": List[PutRecordBatchResponseEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputFormatConfigurationTypeDef = TypedDict(
     "InputFormatConfigurationTypeDef",
     {
         "Deserializer": DeserializerTypeDef,
@@ -1503,10 +1503,10 @@
     pass
 
 
 DescribeDeliveryStreamOutputTypeDef = TypedDict(
     "DescribeDeliveryStreamOutputTypeDef",
     {
         "DeliveryStreamDescription": DeliveryStreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose/type_defs.pyi` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -61,15 +61,15 @@
     "AmazonopensearchserviceBufferingHintsTypeDef",
     "AmazonopensearchserviceRetryOptionsTypeDef",
     "BufferingHintsTypeDef",
     "CopyCommandTypeDef",
     "DeliveryStreamEncryptionConfigurationInputTypeDef",
     "KinesisStreamSourceConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDeliveryStreamOutputTypeDef",
     "SchemaConfigurationTypeDef",
     "DeleteDeliveryStreamInputRequestTypeDef",
     "FailureDescriptionTypeDef",
     "DescribeDeliveryStreamInputRequestTypeDef",
     "HiveJsonSerDeTypeDef",
     "OpenXJsonSerDeTypeDef",
     "RetryOptionsTypeDef",
@@ -79,30 +79,30 @@
     "HttpEndpointBufferingHintsTypeDef",
     "HttpEndpointCommonAttributeTypeDef",
     "HttpEndpointConfigurationTypeDef",
     "HttpEndpointDescriptionTypeDef",
     "HttpEndpointRetryOptionsTypeDef",
     "KinesisStreamSourceDescriptionTypeDef",
     "ListDeliveryStreamsInputRequestTypeDef",
+    "ListDeliveryStreamsOutputTypeDef",
     "ListTagsForDeliveryStreamInputRequestTypeDef",
     "OrcSerDeTypeDef",
     "ParquetSerDeTypeDef",
     "ProcessorParameterTypeDef",
     "RecordTypeDef",
     "PutRecordBatchResponseEntryTypeDef",
+    "PutRecordOutputTypeDef",
     "RedshiftRetryOptionsTypeDef",
+    "ResponseMetadataTypeDef",
     "SplunkRetryOptionsTypeDef",
     "StopDeliveryStreamEncryptionInputRequestTypeDef",
     "UntagDeliveryStreamInputRequestTypeDef",
     "StartDeliveryStreamEncryptionInputRequestTypeDef",
-    "TagDeliveryStreamInputRequestTypeDef",
-    "CreateDeliveryStreamOutputTypeDef",
-    "ListDeliveryStreamsOutputTypeDef",
     "ListTagsForDeliveryStreamOutputTypeDef",
-    "PutRecordOutputTypeDef",
+    "TagDeliveryStreamInputRequestTypeDef",
     "DeliveryStreamEncryptionConfigurationTypeDef",
     "DeserializerTypeDef",
     "DynamicPartitioningConfigurationTypeDef",
     "EncryptionConfigurationTypeDef",
     "HttpEndpointRequestConfigurationTypeDef",
     "SourceDescriptionTypeDef",
     "SerializerTypeDef",
@@ -276,22 +276,19 @@
     },
     total=False,
 )
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDeliveryStreamOutputTypeDef = TypedDict(
+    "CreateDeliveryStreamOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DeliveryStreamARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaConfigurationTypeDef = TypedDict(
     "SchemaConfigurationTypeDef",
     {
         "RoleARN": str,
@@ -473,14 +470,23 @@
         "Limit": int,
         "DeliveryStreamType": DeliveryStreamTypeType,
         "ExclusiveStartDeliveryStreamName": str,
     },
     total=False,
 )
 
+ListDeliveryStreamsOutputTypeDef = TypedDict(
+    "ListDeliveryStreamsOutputTypeDef",
+    {
+        "DeliveryStreamNames": List[str],
+        "HasMoreDeliveryStreams": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListTagsForDeliveryStreamInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForDeliveryStreamInputRequestTypeDef",
     {
         "DeliveryStreamName": str,
     },
 )
 _OptionalListTagsForDeliveryStreamInputRequestTypeDef = TypedDict(
@@ -549,22 +555,42 @@
         "RecordId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+PutRecordOutputTypeDef = TypedDict(
+    "PutRecordOutputTypeDef",
+    {
+        "RecordId": str,
+        "Encrypted": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedshiftRetryOptionsTypeDef = TypedDict(
     "RedshiftRetryOptionsTypeDef",
     {
         "DurationInSeconds": int,
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
 SplunkRetryOptionsTypeDef = TypedDict(
     "SplunkRetryOptionsTypeDef",
     {
         "DurationInSeconds": int,
     },
     total=False,
 )
@@ -602,54 +628,28 @@
 
 class StartDeliveryStreamEncryptionInputRequestTypeDef(
     _RequiredStartDeliveryStreamEncryptionInputRequestTypeDef,
     _OptionalStartDeliveryStreamEncryptionInputRequestTypeDef,
 ):
     pass
 
-TagDeliveryStreamInputRequestTypeDef = TypedDict(
-    "TagDeliveryStreamInputRequestTypeDef",
-    {
-        "DeliveryStreamName": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateDeliveryStreamOutputTypeDef = TypedDict(
-    "CreateDeliveryStreamOutputTypeDef",
-    {
-        "DeliveryStreamARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeliveryStreamsOutputTypeDef = TypedDict(
-    "ListDeliveryStreamsOutputTypeDef",
-    {
-        "DeliveryStreamNames": List[str],
-        "HasMoreDeliveryStreams": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForDeliveryStreamOutputTypeDef = TypedDict(
     "ListTagsForDeliveryStreamOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "HasMoreTags": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutRecordOutputTypeDef = TypedDict(
-    "PutRecordOutputTypeDef",
+TagDeliveryStreamInputRequestTypeDef = TypedDict(
+    "TagDeliveryStreamInputRequestTypeDef",
     {
-        "RecordId": str,
-        "Encrypted": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeliveryStreamName": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 DeliveryStreamEncryptionConfigurationTypeDef = TypedDict(
     "DeliveryStreamEncryptionConfigurationTypeDef",
     {
         "KeyARN": str,
@@ -748,15 +748,15 @@
 
 PutRecordBatchOutputTypeDef = TypedDict(
     "PutRecordBatchOutputTypeDef",
     {
         "FailedPutCount": int,
         "Encrypted": bool,
         "RequestResponses": List[PutRecordBatchResponseEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputFormatConfigurationTypeDef = TypedDict(
     "InputFormatConfigurationTypeDef",
     {
         "Deserializer": DeserializerTypeDef,
@@ -1454,10 +1454,10 @@
 ):
     pass
 
 DescribeDeliveryStreamOutputTypeDef = TypedDict(
     "DescribeDeliveryStreamOutputTypeDef",
     {
         "DeliveryStreamDescription": DeliveryStreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/PKG-INFO` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-firehose
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Firehose 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Firehose 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-firehose"></a>
 
 # types-aiobotocore-firehose
 
 [![PyPI - types-aiobotocore-firehose](https://img.shields.io/pypi/v/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-firehose.svg?color=blue)](https://pypi.org/project/types-aiobotocore-firehose)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-firehose?color=blue)](https://pypistats.org/packages/types-aiobotocore-firehose)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Firehose 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
+[aiobotocore.Firehose 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/firehose.html#Firehose)
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
 [types-aiobotocore-firehose docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_firehose/).
 
 See how it helps to find and fix potential bugs:
 
@@ -324,15 +324,15 @@
     AmazonopensearchserviceBufferingHintsTypeDef,
     AmazonopensearchserviceRetryOptionsTypeDef,
     BufferingHintsTypeDef,
     CopyCommandTypeDef,
     DeliveryStreamEncryptionConfigurationInputTypeDef,
     KinesisStreamSourceConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliveryStreamOutputTypeDef,
     SchemaConfigurationTypeDef,
     DeleteDeliveryStreamInputRequestTypeDef,
     FailureDescriptionTypeDef,
     DescribeDeliveryStreamInputRequestTypeDef,
     HiveJsonSerDeTypeDef,
     OpenXJsonSerDeTypeDef,
     RetryOptionsTypeDef,
@@ -342,30 +342,30 @@
     HttpEndpointBufferingHintsTypeDef,
     HttpEndpointCommonAttributeTypeDef,
     HttpEndpointConfigurationTypeDef,
     HttpEndpointDescriptionTypeDef,
     HttpEndpointRetryOptionsTypeDef,
     KinesisStreamSourceDescriptionTypeDef,
     ListDeliveryStreamsInputRequestTypeDef,
+    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamInputRequestTypeDef,
     OrcSerDeTypeDef,
     ParquetSerDeTypeDef,
     ProcessorParameterTypeDef,
     RecordTypeDef,
     PutRecordBatchResponseEntryTypeDef,
+    PutRecordOutputTypeDef,
     RedshiftRetryOptionsTypeDef,
+    ResponseMetadataTypeDef,
     SplunkRetryOptionsTypeDef,
     StopDeliveryStreamEncryptionInputRequestTypeDef,
     UntagDeliveryStreamInputRequestTypeDef,
     StartDeliveryStreamEncryptionInputRequestTypeDef,
-    TagDeliveryStreamInputRequestTypeDef,
-    CreateDeliveryStreamOutputTypeDef,
-    ListDeliveryStreamsOutputTypeDef,
     ListTagsForDeliveryStreamOutputTypeDef,
-    PutRecordOutputTypeDef,
+    TagDeliveryStreamInputRequestTypeDef,
     DeliveryStreamEncryptionConfigurationTypeDef,
     DeserializerTypeDef,
     DynamicPartitioningConfigurationTypeDef,
     EncryptionConfigurationTypeDef,
     HttpEndpointRequestConfigurationTypeDef,
     SourceDescriptionTypeDef,
     SerializerTypeDef,
@@ -416,43 +416,43 @@
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

### Comparing `types-aiobotocore-firehose-2.5.0.post1/types_aiobotocore_firehose.egg-info/SOURCES.txt` & `types-aiobotocore-firehose-2.5.1/types_aiobotocore_firehose.egg-info/SOURCES.txt`

 * *Files identical despite different names*

