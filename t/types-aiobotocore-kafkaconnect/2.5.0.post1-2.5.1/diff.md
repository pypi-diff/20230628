# Comparing `tmp/types-aiobotocore-kafkaconnect-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kafkaconnect-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kafkaconnect-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-kafkaconnect-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1.tar` & `types-aiobotocore-kafkaconnect-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.295323 types-aiobotocore-kafkaconnect-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16769 2023-03-11 12:26:49.295323 types-aiobotocore-kafkaconnect-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15178 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.295323 types-aiobotocore-kafkaconnect-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.283322 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/
--rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1172 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14157 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14133 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8695 2023-03-11 12:16:45.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8693 2023-03-11 12:16:45.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4551 2023-03-11 12:16:45.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4545 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25534 2023-03-11 12:16:47.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25513 2023-03-11 12:16:45.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:44.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.295323 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16769 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:49.000000 types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.770158 types-aiobotocore-kafkaconnect-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16766 2023-06-28 01:43:40.770158 types-aiobotocore-kafkaconnect-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15181 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.770158 types-aiobotocore-kafkaconnect-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.770158 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/
+-rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1172 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14157 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14133 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8904 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8902 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4437 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4432 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25564 2023-06-28 01:33:26.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25543 2023-06-28 01:33:26.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:25.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.770158 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16766 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:40.000000 types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/LICENSE` & `types-aiobotocore-kafkaconnect-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kafkaconnect-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kafkaconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KafkaConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KafkaConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kafkaconnect"></a>
 
 # types-aiobotocore-kafkaconnect
 
 [![PyPI - types-aiobotocore-kafkaconnect](https://img.shields.io/pypi/v/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kafkaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-kafkaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KafkaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
+[aiobotocore.KafkaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
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
 [types-aiobotocore-kafkaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,57 +350,57 @@
     CloudWatchLogsLogDeliveryTypeDef,
     KafkaClusterClientAuthenticationDescriptionTypeDef,
     KafkaClusterEncryptionInTransitDescriptionTypeDef,
     WorkerConfigurationDescriptionTypeDef,
     KafkaClusterClientAuthenticationTypeDef,
     KafkaClusterEncryptionInTransitTypeDef,
     WorkerConfigurationTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateCustomPluginResponseTypeDef,
     CreateWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionSummaryTypeDef,
     CustomPluginDescriptionTypeDef,
     CustomPluginFileDescriptionTypeDef,
     S3LocationDescriptionTypeDef,
     S3LocationTypeDef,
     CustomPluginTypeDef,
     DeleteConnectorRequestRequestTypeDef,
+    DeleteConnectorResponseTypeDef,
     DeleteCustomPluginRequestRequestTypeDef,
+    DeleteCustomPluginResponseTypeDef,
     DescribeConnectorRequestRequestTypeDef,
     StateDescriptionTypeDef,
     DescribeCustomPluginRequestRequestTypeDef,
     DescribeWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionDescriptionTypeDef,
     FirehoseLogDeliveryDescriptionTypeDef,
     FirehoseLogDeliveryTypeDef,
-    PaginatorConfigTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
+    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
     ListCustomPluginsRequestRequestTypeDef,
+    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     ListWorkerConfigurationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3LogDeliveryDescriptionTypeDef,
     S3LogDeliveryTypeDef,
+    UpdateConnectorResponseTypeDef,
     ApacheKafkaClusterDescriptionTypeDef,
     ApacheKafkaClusterTypeDef,
     AutoScalingDescriptionTypeDef,
     AutoScalingTypeDef,
     AutoScalingUpdateTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateCustomPluginResponseTypeDef,
-    DeleteConnectorResponseTypeDef,
-    DeleteCustomPluginResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
     CreateWorkerConfigurationResponseTypeDef,
     WorkerConfigurationSummaryTypeDef,
     PluginDescriptionTypeDef,
     CustomPluginLocationDescriptionTypeDef,
     CustomPluginLocationTypeDef,
     PluginTypeDef,
     DescribeWorkerConfigurationResponseTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
-    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     WorkerLogDeliveryDescriptionTypeDef,
     WorkerLogDeliveryTypeDef,
     KafkaClusterDescriptionTypeDef,
     KafkaClusterTypeDef,
     CapacityDescriptionTypeDef,
     CapacityTypeDef,
     CapacityUpdateTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/README.md` & `types-aiobotocore-kafkaconnect-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kafkaconnect"></a>
 
 # types-aiobotocore-kafkaconnect
 
 [![PyPI - types-aiobotocore-kafkaconnect](https://img.shields.io/pypi/v/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kafkaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-kafkaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KafkaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
+[aiobotocore.KafkaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
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
 [types-aiobotocore-kafkaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,57 +317,57 @@
     CloudWatchLogsLogDeliveryTypeDef,
     KafkaClusterClientAuthenticationDescriptionTypeDef,
     KafkaClusterEncryptionInTransitDescriptionTypeDef,
     WorkerConfigurationDescriptionTypeDef,
     KafkaClusterClientAuthenticationTypeDef,
     KafkaClusterEncryptionInTransitTypeDef,
     WorkerConfigurationTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateCustomPluginResponseTypeDef,
     CreateWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionSummaryTypeDef,
     CustomPluginDescriptionTypeDef,
     CustomPluginFileDescriptionTypeDef,
     S3LocationDescriptionTypeDef,
     S3LocationTypeDef,
     CustomPluginTypeDef,
     DeleteConnectorRequestRequestTypeDef,
+    DeleteConnectorResponseTypeDef,
     DeleteCustomPluginRequestRequestTypeDef,
+    DeleteCustomPluginResponseTypeDef,
     DescribeConnectorRequestRequestTypeDef,
     StateDescriptionTypeDef,
     DescribeCustomPluginRequestRequestTypeDef,
     DescribeWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionDescriptionTypeDef,
     FirehoseLogDeliveryDescriptionTypeDef,
     FirehoseLogDeliveryTypeDef,
-    PaginatorConfigTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
+    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
     ListCustomPluginsRequestRequestTypeDef,
+    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     ListWorkerConfigurationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3LogDeliveryDescriptionTypeDef,
     S3LogDeliveryTypeDef,
+    UpdateConnectorResponseTypeDef,
     ApacheKafkaClusterDescriptionTypeDef,
     ApacheKafkaClusterTypeDef,
     AutoScalingDescriptionTypeDef,
     AutoScalingTypeDef,
     AutoScalingUpdateTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateCustomPluginResponseTypeDef,
-    DeleteConnectorResponseTypeDef,
-    DeleteCustomPluginResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
     CreateWorkerConfigurationResponseTypeDef,
     WorkerConfigurationSummaryTypeDef,
     PluginDescriptionTypeDef,
     CustomPluginLocationDescriptionTypeDef,
     CustomPluginLocationTypeDef,
     PluginTypeDef,
     DescribeWorkerConfigurationResponseTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
-    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     WorkerLogDeliveryDescriptionTypeDef,
     WorkerLogDeliveryTypeDef,
     KafkaClusterDescriptionTypeDef,
     KafkaClusterTypeDef,
     CapacityDescriptionTypeDef,
     CapacityTypeDef,
     CapacityUpdateTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/setup.py` & `types-aiobotocore-kafkaconnect-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kafkaconnect.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kafkaconnect",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kafkaconnect"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KafkaConnect 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KafkaConnect 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/"
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__init__.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__init__.pyi` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/__main__.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KafkaConnect 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KafkaConnect 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect\nOther"
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/client.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/client.pyi` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/literals.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/literals.pyi`

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
     "ConnectorStateType",
     "CustomPluginContentTypeType",
     "CustomPluginStateType",
     "KafkaClusterClientAuthenticationTypeType",
     "KafkaClusterEncryptionInTransitTypeType",
     "ListConnectorsPaginatorName",
@@ -31,15 +30,14 @@
     "KafkaConnectServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ConnectorStateType = Literal["CREATING", "DELETING", "FAILED", "RUNNING", "UPDATING"]
 CustomPluginContentTypeType = Literal["JAR", "ZIP"]
 CustomPluginStateType = Literal[
     "ACTIVE", "CREATE_FAILED", "CREATING", "DELETING", "UPDATE_FAILED", "UPDATING"
 ]
 KafkaClusterClientAuthenticationTypeType = Literal["IAM", "NONE"]
 KafkaClusterEncryptionInTransitTypeType = Literal["PLAINTEXT", "TLS"]
@@ -105,14 +103,15 @@
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
@@ -191,14 +190,15 @@
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
@@ -209,14 +209,15 @@
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
@@ -252,14 +253,15 @@
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
@@ -278,16 +280,19 @@
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
@@ -371,15 +376,17 @@
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/literals.pyi` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/literals.py`

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
     "ConnectorStateType",
     "CustomPluginContentTypeType",
     "CustomPluginStateType",
     "KafkaClusterClientAuthenticationTypeType",
     "KafkaClusterEncryptionInTransitTypeType",
     "ListConnectorsPaginatorName",
@@ -30,14 +31,15 @@
     "KafkaConnectServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ConnectorStateType = Literal["CREATING", "DELETING", "FAILED", "RUNNING", "UPDATING"]
 CustomPluginContentTypeType = Literal["JAR", "ZIP"]
 CustomPluginStateType = Literal[
     "ACTIVE", "CREATE_FAILED", "CREATING", "DELETING", "UPDATE_FAILED", "UPDATING"
 ]
 KafkaClusterClientAuthenticationTypeType = Literal["IAM", "NONE"]
 KafkaClusterEncryptionInTransitTypeType = Literal["PLAINTEXT", "TLS"]
@@ -103,14 +105,15 @@
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
@@ -189,14 +192,15 @@
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
@@ -207,14 +211,15 @@
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
@@ -250,14 +255,15 @@
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
@@ -276,16 +282,19 @@
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
@@ -369,15 +378,17 @@
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/paginator.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: KafkaConnectClient
 
         list_connectors_paginator: ListConnectorsPaginator = client.get_paginator("list_connectors")
         list_custom_plugins_paginator: ListCustomPluginsPaginator = client.get_paginator("list_custom_plugins")
         list_worker_configurations_paginator: ListWorkerConfigurationsPaginator = client.get_paginator("list_worker_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListConnectorsResponseTypeDef,
     ListCustomPluginsResponseTypeDef,
     ListWorkerConfigurationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListConnectorsPaginator",
     "ListCustomPluginsPaginator",
     "ListWorkerConfigurationsPaginator",
 )
 
 
@@ -63,43 +56,43 @@
 class ListConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listconnectorspaginator)
     """
 
     def paginate(
-        self, *, connectorNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, connectorNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listconnectorspaginator)
         """
 
 
 class ListCustomPluginsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListCustomPlugins)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listcustompluginspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomPluginsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListCustomPlugins.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listcustompluginspaginator)
         """
 
 
 class ListWorkerConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListWorkerConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listworkerconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListWorkerConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listworkerconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/paginator.pyi` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: KafkaConnectClient
 
         list_connectors_paginator: ListConnectorsPaginator = client.get_paginator("list_connectors")
         list_custom_plugins_paginator: ListCustomPluginsPaginator = client.get_paginator("list_custom_plugins")
         list_worker_configurations_paginator: ListWorkerConfigurationsPaginator = client.get_paginator("list_worker_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListConnectorsResponseTypeDef,
     ListCustomPluginsResponseTypeDef,
     ListWorkerConfigurationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListConnectorsPaginator",
     "ListCustomPluginsPaginator",
     "ListWorkerConfigurationsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -59,41 +53,41 @@
 class ListConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listconnectorspaginator)
     """
 
     def paginate(
-        self, *, connectorNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, connectorNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listconnectorspaginator)
         """
 
 class ListCustomPluginsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListCustomPlugins)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listcustompluginspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomPluginsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListCustomPlugins.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listcustompluginspaginator)
         """
 
 class ListWorkerConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListWorkerConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listworkerconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect.Paginator.ListWorkerConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/paginators/#listworkerconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/type_defs.py` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -45,57 +45,57 @@
     "CloudWatchLogsLogDeliveryTypeDef",
     "KafkaClusterClientAuthenticationDescriptionTypeDef",
     "KafkaClusterEncryptionInTransitDescriptionTypeDef",
     "WorkerConfigurationDescriptionTypeDef",
     "KafkaClusterClientAuthenticationTypeDef",
     "KafkaClusterEncryptionInTransitTypeDef",
     "WorkerConfigurationTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateConnectorResponseTypeDef",
+    "CreateCustomPluginResponseTypeDef",
     "CreateWorkerConfigurationRequestRequestTypeDef",
     "WorkerConfigurationRevisionSummaryTypeDef",
     "CustomPluginDescriptionTypeDef",
     "CustomPluginFileDescriptionTypeDef",
     "S3LocationDescriptionTypeDef",
     "S3LocationTypeDef",
     "CustomPluginTypeDef",
     "DeleteConnectorRequestRequestTypeDef",
+    "DeleteConnectorResponseTypeDef",
     "DeleteCustomPluginRequestRequestTypeDef",
+    "DeleteCustomPluginResponseTypeDef",
     "DescribeConnectorRequestRequestTypeDef",
     "StateDescriptionTypeDef",
     "DescribeCustomPluginRequestRequestTypeDef",
     "DescribeWorkerConfigurationRequestRequestTypeDef",
     "WorkerConfigurationRevisionDescriptionTypeDef",
     "FirehoseLogDeliveryDescriptionTypeDef",
     "FirehoseLogDeliveryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     "ListConnectorsRequestRequestTypeDef",
+    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
     "ListCustomPluginsRequestRequestTypeDef",
+    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
     "ListWorkerConfigurationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3LogDeliveryDescriptionTypeDef",
     "S3LogDeliveryTypeDef",
+    "UpdateConnectorResponseTypeDef",
     "ApacheKafkaClusterDescriptionTypeDef",
     "ApacheKafkaClusterTypeDef",
     "AutoScalingDescriptionTypeDef",
     "AutoScalingTypeDef",
     "AutoScalingUpdateTypeDef",
-    "CreateConnectorResponseTypeDef",
-    "CreateCustomPluginResponseTypeDef",
-    "DeleteConnectorResponseTypeDef",
-    "DeleteCustomPluginResponseTypeDef",
-    "UpdateConnectorResponseTypeDef",
     "CreateWorkerConfigurationResponseTypeDef",
     "WorkerConfigurationSummaryTypeDef",
     "PluginDescriptionTypeDef",
     "CustomPluginLocationDescriptionTypeDef",
     "CustomPluginLocationTypeDef",
     "PluginTypeDef",
     "DescribeWorkerConfigurationResponseTypeDef",
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
-    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
     "WorkerLogDeliveryDescriptionTypeDef",
     "WorkerLogDeliveryTypeDef",
     "KafkaClusterDescriptionTypeDef",
     "KafkaClusterTypeDef",
     "CapacityDescriptionTypeDef",
     "CapacityTypeDef",
     "CapacityUpdateTypeDef",
@@ -284,22 +284,32 @@
     "WorkerConfigurationTypeDef",
     {
         "revision": int,
         "workerConfigurationArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateConnectorResponseTypeDef = TypedDict(
+    "CreateConnectorResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "connectorArn": str,
+        "connectorName": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomPluginResponseTypeDef = TypedDict(
+    "CreateCustomPluginResponseTypeDef",
+    {
+        "customPluginArn": str,
+        "customPluginState": CustomPluginStateType,
+        "name": str,
+        "revision": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerConfigurationRequestRequestTypeDef",
     {
         "name": str,
@@ -405,21 +415,39 @@
 
 class DeleteConnectorRequestRequestTypeDef(
     _RequiredDeleteConnectorRequestRequestTypeDef, _OptionalDeleteConnectorRequestRequestTypeDef
 ):
     pass
 
 
+DeleteConnectorResponseTypeDef = TypedDict(
+    "DeleteConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCustomPluginRequestRequestTypeDef = TypedDict(
     "DeleteCustomPluginRequestRequestTypeDef",
     {
         "customPluginArn": str,
     },
 )
 
+DeleteCustomPluginResponseTypeDef = TypedDict(
+    "DeleteCustomPluginResponseTypeDef",
+    {
+        "customPluginArn": str,
+        "customPluginState": CustomPluginStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeConnectorRequestRequestTypeDef = TypedDict(
     "DescribeConnectorRequestRequestTypeDef",
     {
         "connectorArn": str,
     },
 )
 
@@ -483,52 +511,88 @@
 
 class FirehoseLogDeliveryTypeDef(
     _RequiredFirehoseLogDeliveryTypeDef, _OptionalFirehoseLogDeliveryTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "connectorNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListConnectorsRequestRequestTypeDef = TypedDict(
     "ListConnectorsRequestRequestTypeDef",
     {
         "connectorNamePrefix": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCustomPluginsRequestListCustomPluginsPaginateTypeDef = TypedDict(
+    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomPluginsRequestRequestTypeDef = TypedDict(
     "ListCustomPluginsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef = TypedDict(
+    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkerConfigurationsRequestRequestTypeDef = TypedDict(
     "ListWorkerConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
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
 S3LogDeliveryDescriptionTypeDef = TypedDict(
     "S3LogDeliveryDescriptionTypeDef",
     {
         "bucket": str,
         "enabled": bool,
         "prefix": str,
     },
@@ -551,14 +615,23 @@
 )
 
 
 class S3LogDeliveryTypeDef(_RequiredS3LogDeliveryTypeDef, _OptionalS3LogDeliveryTypeDef):
     pass
 
 
+UpdateConnectorResponseTypeDef = TypedDict(
+    "UpdateConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ApacheKafkaClusterDescriptionTypeDef = TypedDict(
     "ApacheKafkaClusterDescriptionTypeDef",
     {
         "bootstrapServers": str,
         "vpc": VpcDescriptionTypeDef,
     },
     total=False,
@@ -613,70 +686,22 @@
         "mcuCount": int,
         "minWorkerCount": int,
         "scaleInPolicy": ScaleInPolicyUpdateTypeDef,
         "scaleOutPolicy": ScaleOutPolicyUpdateTypeDef,
     },
 )
 
-CreateConnectorResponseTypeDef = TypedDict(
-    "CreateConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorName": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomPluginResponseTypeDef = TypedDict(
-    "CreateCustomPluginResponseTypeDef",
-    {
-        "customPluginArn": str,
-        "customPluginState": CustomPluginStateType,
-        "name": str,
-        "revision": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteConnectorResponseTypeDef = TypedDict(
-    "DeleteConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomPluginResponseTypeDef = TypedDict(
-    "DeleteCustomPluginResponseTypeDef",
-    {
-        "customPluginArn": str,
-        "customPluginState": CustomPluginStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorResponseTypeDef = TypedDict(
-    "UpdateConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateWorkerConfigurationResponseTypeDef = TypedDict(
     "CreateWorkerConfigurationResponseTypeDef",
     {
         "creationTime": datetime,
         "latestRevision": WorkerConfigurationRevisionSummaryTypeDef,
         "name": str,
         "workerConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkerConfigurationSummaryTypeDef = TypedDict(
     "WorkerConfigurationSummaryTypeDef",
     {
         "creationTime": datetime,
@@ -722,43 +747,18 @@
     "DescribeWorkerConfigurationResponseTypeDef",
     {
         "creationTime": datetime,
         "description": str,
         "latestRevision": WorkerConfigurationRevisionDescriptionTypeDef,
         "name": str,
         "workerConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    {
-        "connectorNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomPluginsRequestListCustomPluginsPaginateTypeDef = TypedDict(
-    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef = TypedDict(
-    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 WorkerLogDeliveryDescriptionTypeDef = TypedDict(
     "WorkerLogDeliveryDescriptionTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsLogDeliveryDescriptionTypeDef,
         "firehose": FirehoseLogDeliveryDescriptionTypeDef,
         "s3": S3LogDeliveryDescriptionTypeDef,
     },
@@ -818,15 +818,15 @@
 )
 
 ListWorkerConfigurationsResponseTypeDef = TypedDict(
     "ListWorkerConfigurationsResponseTypeDef",
     {
         "nextToken": str,
         "workerConfigurations": List[WorkerConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomPluginRevisionSummaryTypeDef = TypedDict(
     "CustomPluginRevisionSummaryTypeDef",
     {
         "contentType": CustomPluginContentTypeType,
@@ -906,15 +906,15 @@
         "creationTime": datetime,
         "customPluginArn": str,
         "customPluginState": CustomPluginStateType,
         "description": str,
         "latestRevision": CustomPluginRevisionSummaryTypeDef,
         "name": str,
         "stateDescription": StateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectorSummaryTypeDef = TypedDict(
     "ConnectorSummaryTypeDef",
     {
         "capacity": CapacityDescriptionTypeDef,
@@ -952,15 +952,15 @@
         "kafkaClusterEncryptionInTransit": KafkaClusterEncryptionInTransitDescriptionTypeDef,
         "kafkaConnectVersion": str,
         "logDelivery": LogDeliveryDescriptionTypeDef,
         "plugins": List[PluginDescriptionTypeDef],
         "serviceExecutionRoleArn": str,
         "stateDescription": StateDescriptionTypeDef,
         "workerConfiguration": WorkerConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConnectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectorRequestRequestTypeDef",
     {
         "capacity": CapacityTypeDef,
@@ -992,19 +992,19 @@
 
 
 ListCustomPluginsResponseTypeDef = TypedDict(
     "ListCustomPluginsResponseTypeDef",
     {
         "customPlugins": List[CustomPluginSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectorsResponseTypeDef = TypedDict(
     "ListConnectorsResponseTypeDef",
     {
         "connectors": List[ConnectorSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect/type_defs.pyi` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -44,57 +44,57 @@
     "CloudWatchLogsLogDeliveryTypeDef",
     "KafkaClusterClientAuthenticationDescriptionTypeDef",
     "KafkaClusterEncryptionInTransitDescriptionTypeDef",
     "WorkerConfigurationDescriptionTypeDef",
     "KafkaClusterClientAuthenticationTypeDef",
     "KafkaClusterEncryptionInTransitTypeDef",
     "WorkerConfigurationTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateConnectorResponseTypeDef",
+    "CreateCustomPluginResponseTypeDef",
     "CreateWorkerConfigurationRequestRequestTypeDef",
     "WorkerConfigurationRevisionSummaryTypeDef",
     "CustomPluginDescriptionTypeDef",
     "CustomPluginFileDescriptionTypeDef",
     "S3LocationDescriptionTypeDef",
     "S3LocationTypeDef",
     "CustomPluginTypeDef",
     "DeleteConnectorRequestRequestTypeDef",
+    "DeleteConnectorResponseTypeDef",
     "DeleteCustomPluginRequestRequestTypeDef",
+    "DeleteCustomPluginResponseTypeDef",
     "DescribeConnectorRequestRequestTypeDef",
     "StateDescriptionTypeDef",
     "DescribeCustomPluginRequestRequestTypeDef",
     "DescribeWorkerConfigurationRequestRequestTypeDef",
     "WorkerConfigurationRevisionDescriptionTypeDef",
     "FirehoseLogDeliveryDescriptionTypeDef",
     "FirehoseLogDeliveryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     "ListConnectorsRequestRequestTypeDef",
+    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
     "ListCustomPluginsRequestRequestTypeDef",
+    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
     "ListWorkerConfigurationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3LogDeliveryDescriptionTypeDef",
     "S3LogDeliveryTypeDef",
+    "UpdateConnectorResponseTypeDef",
     "ApacheKafkaClusterDescriptionTypeDef",
     "ApacheKafkaClusterTypeDef",
     "AutoScalingDescriptionTypeDef",
     "AutoScalingTypeDef",
     "AutoScalingUpdateTypeDef",
-    "CreateConnectorResponseTypeDef",
-    "CreateCustomPluginResponseTypeDef",
-    "DeleteConnectorResponseTypeDef",
-    "DeleteCustomPluginResponseTypeDef",
-    "UpdateConnectorResponseTypeDef",
     "CreateWorkerConfigurationResponseTypeDef",
     "WorkerConfigurationSummaryTypeDef",
     "PluginDescriptionTypeDef",
     "CustomPluginLocationDescriptionTypeDef",
     "CustomPluginLocationTypeDef",
     "PluginTypeDef",
     "DescribeWorkerConfigurationResponseTypeDef",
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
-    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
     "WorkerLogDeliveryDescriptionTypeDef",
     "WorkerLogDeliveryTypeDef",
     "KafkaClusterDescriptionTypeDef",
     "KafkaClusterTypeDef",
     "CapacityDescriptionTypeDef",
     "CapacityTypeDef",
     "CapacityUpdateTypeDef",
@@ -279,22 +279,32 @@
     "WorkerConfigurationTypeDef",
     {
         "revision": int,
         "workerConfigurationArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateConnectorResponseTypeDef = TypedDict(
+    "CreateConnectorResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "connectorArn": str,
+        "connectorName": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomPluginResponseTypeDef = TypedDict(
+    "CreateCustomPluginResponseTypeDef",
+    {
+        "customPluginArn": str,
+        "customPluginState": CustomPluginStateType,
+        "name": str,
+        "revision": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerConfigurationRequestRequestTypeDef",
     {
         "name": str,
@@ -394,21 +404,39 @@
 )
 
 class DeleteConnectorRequestRequestTypeDef(
     _RequiredDeleteConnectorRequestRequestTypeDef, _OptionalDeleteConnectorRequestRequestTypeDef
 ):
     pass
 
+DeleteConnectorResponseTypeDef = TypedDict(
+    "DeleteConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCustomPluginRequestRequestTypeDef = TypedDict(
     "DeleteCustomPluginRequestRequestTypeDef",
     {
         "customPluginArn": str,
     },
 )
 
+DeleteCustomPluginResponseTypeDef = TypedDict(
+    "DeleteCustomPluginResponseTypeDef",
+    {
+        "customPluginArn": str,
+        "customPluginState": CustomPluginStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeConnectorRequestRequestTypeDef = TypedDict(
     "DescribeConnectorRequestRequestTypeDef",
     {
         "connectorArn": str,
     },
 )
 
@@ -470,52 +498,88 @@
 )
 
 class FirehoseLogDeliveryTypeDef(
     _RequiredFirehoseLogDeliveryTypeDef, _OptionalFirehoseLogDeliveryTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
+    "ListConnectorsRequestListConnectorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "connectorNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListConnectorsRequestRequestTypeDef = TypedDict(
     "ListConnectorsRequestRequestTypeDef",
     {
         "connectorNamePrefix": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCustomPluginsRequestListCustomPluginsPaginateTypeDef = TypedDict(
+    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomPluginsRequestRequestTypeDef = TypedDict(
     "ListCustomPluginsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef = TypedDict(
+    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkerConfigurationsRequestRequestTypeDef = TypedDict(
     "ListWorkerConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
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
 S3LogDeliveryDescriptionTypeDef = TypedDict(
     "S3LogDeliveryDescriptionTypeDef",
     {
         "bucket": str,
         "enabled": bool,
         "prefix": str,
     },
@@ -536,14 +600,23 @@
     },
     total=False,
 )
 
 class S3LogDeliveryTypeDef(_RequiredS3LogDeliveryTypeDef, _OptionalS3LogDeliveryTypeDef):
     pass
 
+UpdateConnectorResponseTypeDef = TypedDict(
+    "UpdateConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "connectorState": ConnectorStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ApacheKafkaClusterDescriptionTypeDef = TypedDict(
     "ApacheKafkaClusterDescriptionTypeDef",
     {
         "bootstrapServers": str,
         "vpc": VpcDescriptionTypeDef,
     },
     total=False,
@@ -596,70 +669,22 @@
         "mcuCount": int,
         "minWorkerCount": int,
         "scaleInPolicy": ScaleInPolicyUpdateTypeDef,
         "scaleOutPolicy": ScaleOutPolicyUpdateTypeDef,
     },
 )
 
-CreateConnectorResponseTypeDef = TypedDict(
-    "CreateConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorName": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomPluginResponseTypeDef = TypedDict(
-    "CreateCustomPluginResponseTypeDef",
-    {
-        "customPluginArn": str,
-        "customPluginState": CustomPluginStateType,
-        "name": str,
-        "revision": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteConnectorResponseTypeDef = TypedDict(
-    "DeleteConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomPluginResponseTypeDef = TypedDict(
-    "DeleteCustomPluginResponseTypeDef",
-    {
-        "customPluginArn": str,
-        "customPluginState": CustomPluginStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorResponseTypeDef = TypedDict(
-    "UpdateConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "connectorState": ConnectorStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateWorkerConfigurationResponseTypeDef = TypedDict(
     "CreateWorkerConfigurationResponseTypeDef",
     {
         "creationTime": datetime,
         "latestRevision": WorkerConfigurationRevisionSummaryTypeDef,
         "name": str,
         "workerConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkerConfigurationSummaryTypeDef = TypedDict(
     "WorkerConfigurationSummaryTypeDef",
     {
         "creationTime": datetime,
@@ -705,43 +730,18 @@
     "DescribeWorkerConfigurationResponseTypeDef",
     {
         "creationTime": datetime,
         "description": str,
         "latestRevision": WorkerConfigurationRevisionDescriptionTypeDef,
         "name": str,
         "workerConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListConnectorsRequestListConnectorsPaginateTypeDef = TypedDict(
-    "ListConnectorsRequestListConnectorsPaginateTypeDef",
-    {
-        "connectorNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomPluginsRequestListCustomPluginsPaginateTypeDef = TypedDict(
-    "ListCustomPluginsRequestListCustomPluginsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef = TypedDict(
-    "ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 WorkerLogDeliveryDescriptionTypeDef = TypedDict(
     "WorkerLogDeliveryDescriptionTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsLogDeliveryDescriptionTypeDef,
         "firehose": FirehoseLogDeliveryDescriptionTypeDef,
         "s3": S3LogDeliveryDescriptionTypeDef,
     },
@@ -801,15 +801,15 @@
 )
 
 ListWorkerConfigurationsResponseTypeDef = TypedDict(
     "ListWorkerConfigurationsResponseTypeDef",
     {
         "nextToken": str,
         "workerConfigurations": List[WorkerConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomPluginRevisionSummaryTypeDef = TypedDict(
     "CustomPluginRevisionSummaryTypeDef",
     {
         "contentType": CustomPluginContentTypeType,
@@ -887,15 +887,15 @@
         "creationTime": datetime,
         "customPluginArn": str,
         "customPluginState": CustomPluginStateType,
         "description": str,
         "latestRevision": CustomPluginRevisionSummaryTypeDef,
         "name": str,
         "stateDescription": StateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectorSummaryTypeDef = TypedDict(
     "ConnectorSummaryTypeDef",
     {
         "capacity": CapacityDescriptionTypeDef,
@@ -933,15 +933,15 @@
         "kafkaClusterEncryptionInTransit": KafkaClusterEncryptionInTransitDescriptionTypeDef,
         "kafkaConnectVersion": str,
         "logDelivery": LogDeliveryDescriptionTypeDef,
         "plugins": List[PluginDescriptionTypeDef],
         "serviceExecutionRoleArn": str,
         "stateDescription": StateDescriptionTypeDef,
         "workerConfiguration": WorkerConfigurationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConnectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectorRequestRequestTypeDef",
     {
         "capacity": CapacityTypeDef,
@@ -971,19 +971,19 @@
     pass
 
 ListCustomPluginsResponseTypeDef = TypedDict(
     "ListCustomPluginsResponseTypeDef",
     {
         "customPlugins": List[CustomPluginSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectorsResponseTypeDef = TypedDict(
     "ListConnectorsResponseTypeDef",
     {
         "connectors": List[ConnectorSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/PKG-INFO` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kafkaconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KafkaConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KafkaConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kafkaconnect"></a>
 
 # types-aiobotocore-kafkaconnect
 
 [![PyPI - types-aiobotocore-kafkaconnect](https://img.shields.io/pypi/v/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kafkaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kafkaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kafkaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-kafkaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KafkaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
+[aiobotocore.KafkaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kafkaconnect.html#KafkaConnect)
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
 [types-aiobotocore-kafkaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafkaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,57 +350,57 @@
     CloudWatchLogsLogDeliveryTypeDef,
     KafkaClusterClientAuthenticationDescriptionTypeDef,
     KafkaClusterEncryptionInTransitDescriptionTypeDef,
     WorkerConfigurationDescriptionTypeDef,
     KafkaClusterClientAuthenticationTypeDef,
     KafkaClusterEncryptionInTransitTypeDef,
     WorkerConfigurationTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorResponseTypeDef,
+    CreateCustomPluginResponseTypeDef,
     CreateWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionSummaryTypeDef,
     CustomPluginDescriptionTypeDef,
     CustomPluginFileDescriptionTypeDef,
     S3LocationDescriptionTypeDef,
     S3LocationTypeDef,
     CustomPluginTypeDef,
     DeleteConnectorRequestRequestTypeDef,
+    DeleteConnectorResponseTypeDef,
     DeleteCustomPluginRequestRequestTypeDef,
+    DeleteCustomPluginResponseTypeDef,
     DescribeConnectorRequestRequestTypeDef,
     StateDescriptionTypeDef,
     DescribeCustomPluginRequestRequestTypeDef,
     DescribeWorkerConfigurationRequestRequestTypeDef,
     WorkerConfigurationRevisionDescriptionTypeDef,
     FirehoseLogDeliveryDescriptionTypeDef,
     FirehoseLogDeliveryTypeDef,
-    PaginatorConfigTypeDef,
+    ListConnectorsRequestListConnectorsPaginateTypeDef,
     ListConnectorsRequestRequestTypeDef,
+    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
     ListCustomPluginsRequestRequestTypeDef,
+    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     ListWorkerConfigurationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3LogDeliveryDescriptionTypeDef,
     S3LogDeliveryTypeDef,
+    UpdateConnectorResponseTypeDef,
     ApacheKafkaClusterDescriptionTypeDef,
     ApacheKafkaClusterTypeDef,
     AutoScalingDescriptionTypeDef,
     AutoScalingTypeDef,
     AutoScalingUpdateTypeDef,
-    CreateConnectorResponseTypeDef,
-    CreateCustomPluginResponseTypeDef,
-    DeleteConnectorResponseTypeDef,
-    DeleteCustomPluginResponseTypeDef,
-    UpdateConnectorResponseTypeDef,
     CreateWorkerConfigurationResponseTypeDef,
     WorkerConfigurationSummaryTypeDef,
     PluginDescriptionTypeDef,
     CustomPluginLocationDescriptionTypeDef,
     CustomPluginLocationTypeDef,
     PluginTypeDef,
     DescribeWorkerConfigurationResponseTypeDef,
-    ListConnectorsRequestListConnectorsPaginateTypeDef,
-    ListCustomPluginsRequestListCustomPluginsPaginateTypeDef,
-    ListWorkerConfigurationsRequestListWorkerConfigurationsPaginateTypeDef,
     WorkerLogDeliveryDescriptionTypeDef,
     WorkerLogDeliveryTypeDef,
     KafkaClusterDescriptionTypeDef,
     KafkaClusterTypeDef,
     CapacityDescriptionTypeDef,
     CapacityTypeDef,
     CapacityUpdateTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-kafkaconnect-2.5.0.post1/types_aiobotocore_kafkaconnect.egg-info/SOURCES.txt` & `types-aiobotocore-kafkaconnect-2.5.1/types_aiobotocore_kafkaconnect.egg-info/SOURCES.txt`

 * *Files identical despite different names*

