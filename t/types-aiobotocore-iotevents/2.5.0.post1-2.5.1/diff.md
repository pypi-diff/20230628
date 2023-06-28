# Comparing `tmp/types-aiobotocore-iotevents-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotevents-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotevents-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotevents-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotevents-2.5.0.post1.tar` & `types-aiobotocore-iotevents-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.763297 types-aiobotocore-iotevents-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16154 2023-03-11 12:26:46.759297 types-aiobotocore-iotevents-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14575 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.763297 types-aiobotocore-iotevents-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.759297 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      457 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20395 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20361 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8545 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8543 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    37372 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    37307 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:18.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.759297 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16154 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.418153 types-aiobotocore-iotevents-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16148 2023-06-28 01:43:38.410153 types-aiobotocore-iotevents-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14575 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.418153 types-aiobotocore-iotevents-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.406153 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20395 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20361 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8754 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8752 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    37414 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37349 2023-06-28 01:32:57.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:56.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.410153 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16148 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/LICENSE` & `types-aiobotocore-iotevents-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotevents-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotevents
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTEvents 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTEvents 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotevents"></a>
 
 # types-aiobotocore-iotevents
 
 [![PyPI - types-aiobotocore-iotevents](https://img.shields.io/pypi/v/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEvents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
+[aiobotocore.IoTEvents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
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
 [types-aiobotocore-iotevents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,56 +312,56 @@
     AlarmModelVersionSummaryTypeDef,
     SimpleRuleTypeDef,
     AnalysisResultLocationTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AttributeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlarmModelResponseTypeDef,
     DetectorModelConfigurationTypeDef,
     InputConfigurationTypeDef,
     DeleteAlarmModelRequestRequestTypeDef,
     DeleteDetectorModelRequestRequestTypeDef,
     DeleteInputRequestRequestTypeDef,
     DescribeAlarmModelRequestRequestTypeDef,
     DescribeDetectorModelAnalysisRequestRequestTypeDef,
+    DescribeDetectorModelAnalysisResponseTypeDef,
     DescribeDetectorModelRequestRequestTypeDef,
     DescribeInputRequestRequestTypeDef,
     DetectorDebugOptionTypeDef,
     DetectorModelSummaryTypeDef,
     DetectorModelVersionSummaryTypeDef,
     PayloadTypeDef,
     EmailContentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDetectorModelAnalysisResultsRequestRequestTypeDef,
     IotEventsInputIdentifierTypeDef,
     InputSummaryTypeDef,
     IotSiteWiseAssetModelPropertyIdentifierTypeDef,
     ListAlarmModelVersionsRequestRequestTypeDef,
     ListAlarmModelsRequestRequestTypeDef,
     ListDetectorModelVersionsRequestRequestTypeDef,
     ListDetectorModelsRequestRequestTypeDef,
     RoutedResourceTypeDef,
     ListInputsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     SSOIdentityTypeDef,
+    ResponseMetadataTypeDef,
+    StartDetectorModelAnalysisResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlarmModelResponseTypeDef,
     AlarmCapabilitiesTypeDef,
+    ListAlarmModelsResponseTypeDef,
+    ListAlarmModelVersionsResponseTypeDef,
     AlarmRuleTypeDef,
     AnalysisResultTypeDef,
     AssetPropertyValueTypeDef,
     InputDefinitionTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateAlarmModelResponseTypeDef,
-    DescribeDetectorModelAnalysisResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAlarmModelVersionsResponseTypeDef,
-    ListAlarmModelsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDetectorModelAnalysisResponseTypeDef,
-    UpdateAlarmModelResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDetectorModelResponseTypeDef,
     UpdateDetectorModelResponseTypeDef,
     CreateInputResponseTypeDef,
     UpdateInputResponseTypeDef,
     LoggingOptionsTypeDef,
     ListDetectorModelsResponseTypeDef,
     ListDetectorModelVersionsResponseTypeDef,
@@ -421,43 +421,43 @@
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/README.md` & `types-aiobotocore-iotevents-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotevents"></a>
 
 # types-aiobotocore-iotevents
 
 [![PyPI - types-aiobotocore-iotevents](https://img.shields.io/pypi/v/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEvents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
+[aiobotocore.IoTEvents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
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
 [types-aiobotocore-iotevents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -279,56 +279,56 @@
     AlarmModelVersionSummaryTypeDef,
     SimpleRuleTypeDef,
     AnalysisResultLocationTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AttributeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlarmModelResponseTypeDef,
     DetectorModelConfigurationTypeDef,
     InputConfigurationTypeDef,
     DeleteAlarmModelRequestRequestTypeDef,
     DeleteDetectorModelRequestRequestTypeDef,
     DeleteInputRequestRequestTypeDef,
     DescribeAlarmModelRequestRequestTypeDef,
     DescribeDetectorModelAnalysisRequestRequestTypeDef,
+    DescribeDetectorModelAnalysisResponseTypeDef,
     DescribeDetectorModelRequestRequestTypeDef,
     DescribeInputRequestRequestTypeDef,
     DetectorDebugOptionTypeDef,
     DetectorModelSummaryTypeDef,
     DetectorModelVersionSummaryTypeDef,
     PayloadTypeDef,
     EmailContentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDetectorModelAnalysisResultsRequestRequestTypeDef,
     IotEventsInputIdentifierTypeDef,
     InputSummaryTypeDef,
     IotSiteWiseAssetModelPropertyIdentifierTypeDef,
     ListAlarmModelVersionsRequestRequestTypeDef,
     ListAlarmModelsRequestRequestTypeDef,
     ListDetectorModelVersionsRequestRequestTypeDef,
     ListDetectorModelsRequestRequestTypeDef,
     RoutedResourceTypeDef,
     ListInputsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     SSOIdentityTypeDef,
+    ResponseMetadataTypeDef,
+    StartDetectorModelAnalysisResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlarmModelResponseTypeDef,
     AlarmCapabilitiesTypeDef,
+    ListAlarmModelsResponseTypeDef,
+    ListAlarmModelVersionsResponseTypeDef,
     AlarmRuleTypeDef,
     AnalysisResultTypeDef,
     AssetPropertyValueTypeDef,
     InputDefinitionTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateAlarmModelResponseTypeDef,
-    DescribeDetectorModelAnalysisResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAlarmModelVersionsResponseTypeDef,
-    ListAlarmModelsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDetectorModelAnalysisResponseTypeDef,
-    UpdateAlarmModelResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDetectorModelResponseTypeDef,
     UpdateDetectorModelResponseTypeDef,
     CreateInputResponseTypeDef,
     UpdateInputResponseTypeDef,
     LoggingOptionsTypeDef,
     ListDetectorModelsResponseTypeDef,
     ListDetectorModelVersionsResponseTypeDef,
@@ -388,43 +388,43 @@
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/setup.py` & `types-aiobotocore-iotevents-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotevents.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotevents",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotevents"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTEvents 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.IoTEvents 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/"
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/__main__.py` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTEvents 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTEvents 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents\nOther"
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/client.py` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/client.pyi` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/literals.py` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -108,14 +108,15 @@
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
@@ -194,14 +195,15 @@
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
@@ -212,14 +214,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -281,16 +285,19 @@
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
@@ -374,15 +381,17 @@
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/literals.pyi` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -106,14 +106,15 @@
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
@@ -192,14 +193,15 @@
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
@@ -210,14 +212,15 @@
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
@@ -253,14 +256,15 @@
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
@@ -279,16 +283,19 @@
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
@@ -372,15 +379,17 @@
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/type_defs.py` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -44,56 +44,56 @@
     "AlarmModelVersionSummaryTypeDef",
     "SimpleRuleTypeDef",
     "AnalysisResultLocationTypeDef",
     "AssetPropertyTimestampTypeDef",
     "AssetPropertyVariantTypeDef",
     "AttributeTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAlarmModelResponseTypeDef",
     "DetectorModelConfigurationTypeDef",
     "InputConfigurationTypeDef",
     "DeleteAlarmModelRequestRequestTypeDef",
     "DeleteDetectorModelRequestRequestTypeDef",
     "DeleteInputRequestRequestTypeDef",
     "DescribeAlarmModelRequestRequestTypeDef",
     "DescribeDetectorModelAnalysisRequestRequestTypeDef",
+    "DescribeDetectorModelAnalysisResponseTypeDef",
     "DescribeDetectorModelRequestRequestTypeDef",
     "DescribeInputRequestRequestTypeDef",
     "DetectorDebugOptionTypeDef",
     "DetectorModelSummaryTypeDef",
     "DetectorModelVersionSummaryTypeDef",
     "PayloadTypeDef",
     "EmailContentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetDetectorModelAnalysisResultsRequestRequestTypeDef",
     "IotEventsInputIdentifierTypeDef",
     "InputSummaryTypeDef",
     "IotSiteWiseAssetModelPropertyIdentifierTypeDef",
     "ListAlarmModelVersionsRequestRequestTypeDef",
     "ListAlarmModelsRequestRequestTypeDef",
     "ListDetectorModelVersionsRequestRequestTypeDef",
     "ListDetectorModelsRequestRequestTypeDef",
     "RoutedResourceTypeDef",
     "ListInputsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "SSOIdentityTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDetectorModelAnalysisResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAlarmModelResponseTypeDef",
     "AlarmCapabilitiesTypeDef",
+    "ListAlarmModelsResponseTypeDef",
+    "ListAlarmModelVersionsResponseTypeDef",
     "AlarmRuleTypeDef",
     "AnalysisResultTypeDef",
     "AssetPropertyValueTypeDef",
     "InputDefinitionTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateAlarmModelResponseTypeDef",
-    "DescribeDetectorModelAnalysisResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAlarmModelVersionsResponseTypeDef",
-    "ListAlarmModelsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartDetectorModelAnalysisResponseTypeDef",
-    "UpdateAlarmModelResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateDetectorModelResponseTypeDef",
     "UpdateDetectorModelResponseTypeDef",
     "CreateInputResponseTypeDef",
     "UpdateInputResponseTypeDef",
     "LoggingOptionsTypeDef",
     "ListDetectorModelsResponseTypeDef",
     "ListDetectorModelVersionsResponseTypeDef",
@@ -286,22 +286,23 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAlarmModelResponseTypeDef = TypedDict(
+    "CreateAlarmModelResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "creationTime": datetime,
+        "alarmModelArn": str,
+        "alarmModelVersion": str,
+        "lastUpdateTime": datetime,
+        "status": AlarmModelVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectorModelConfigurationTypeDef = TypedDict(
     "DetectorModelConfigurationTypeDef",
     {
         "detectorModelName": str,
@@ -389,14 +390,22 @@
 DescribeDetectorModelAnalysisRequestRequestTypeDef = TypedDict(
     "DescribeDetectorModelAnalysisRequestRequestTypeDef",
     {
         "analysisId": str,
     },
 )
 
+DescribeDetectorModelAnalysisResponseTypeDef = TypedDict(
+    "DescribeDetectorModelAnalysisResponseTypeDef",
+    {
+        "status": AnalysisStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeDetectorModelRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDetectorModelRequestRequestTypeDef",
     {
         "detectorModelName": str,
     },
 )
 _OptionalDescribeDetectorModelRequestRequestTypeDef = TypedDict(
@@ -481,14 +490,21 @@
     {
         "subject": str,
         "additionalMessage": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDetectorModelAnalysisResultsRequestRequestTypeDef = TypedDict(
     "_RequiredGetDetectorModelAnalysisResultsRequestRequestTypeDef",
     {
         "analysisId": str,
     },
 )
 _OptionalGetDetectorModelAnalysisResultsRequestRequestTypeDef = TypedDict(
@@ -640,31 +656,80 @@
 )
 
 
 class SSOIdentityTypeDef(_RequiredSSOIdentityTypeDef, _OptionalSSOIdentityTypeDef):
     pass
 
 
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
+StartDetectorModelAnalysisResponseTypeDef = TypedDict(
+    "StartDetectorModelAnalysisResponseTypeDef",
+    {
+        "analysisId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateAlarmModelResponseTypeDef = TypedDict(
+    "UpdateAlarmModelResponseTypeDef",
+    {
+        "creationTime": datetime,
+        "alarmModelArn": str,
+        "alarmModelVersion": str,
+        "lastUpdateTime": datetime,
+        "status": AlarmModelVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AlarmCapabilitiesTypeDef = TypedDict(
     "AlarmCapabilitiesTypeDef",
     {
         "initializationConfiguration": InitializationConfigurationTypeDef,
         "acknowledgeFlow": AcknowledgeFlowTypeDef,
     },
     total=False,
 )
 
+ListAlarmModelsResponseTypeDef = TypedDict(
+    "ListAlarmModelsResponseTypeDef",
+    {
+        "alarmModelSummaries": List[AlarmModelSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAlarmModelVersionsResponseTypeDef = TypedDict(
+    "ListAlarmModelVersionsResponseTypeDef",
+    {
+        "alarmModelVersionSummaries": List[AlarmModelVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AlarmRuleTypeDef = TypedDict(
     "AlarmRuleTypeDef",
     {
         "simpleRule": SimpleRuleTypeDef,
     },
     total=False,
 )
@@ -693,124 +758,59 @@
 InputDefinitionTypeDef = TypedDict(
     "InputDefinitionTypeDef",
     {
         "attributes": Sequence[AttributeTypeDef],
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateAlarmModelResponseTypeDef = TypedDict(
-    "CreateAlarmModelResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "alarmModelArn": str,
-        "alarmModelVersion": str,
-        "lastUpdateTime": datetime,
-        "status": AlarmModelVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDetectorModelAnalysisResponseTypeDef = TypedDict(
-    "DescribeDetectorModelAnalysisResponseTypeDef",
-    {
-        "status": AnalysisStatusType,
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
-ListAlarmModelVersionsResponseTypeDef = TypedDict(
-    "ListAlarmModelVersionsResponseTypeDef",
-    {
-        "alarmModelVersionSummaries": List[AlarmModelVersionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlarmModelsResponseTypeDef = TypedDict(
-    "ListAlarmModelsResponseTypeDef",
-    {
-        "alarmModelSummaries": List[AlarmModelSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDetectorModelAnalysisResponseTypeDef = TypedDict(
-    "StartDetectorModelAnalysisResponseTypeDef",
-    {
-        "analysisId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAlarmModelResponseTypeDef = TypedDict(
-    "UpdateAlarmModelResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "creationTime": datetime,
-        "alarmModelArn": str,
-        "alarmModelVersion": str,
-        "lastUpdateTime": datetime,
-        "status": AlarmModelVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 CreateDetectorModelResponseTypeDef = TypedDict(
     "CreateDetectorModelResponseTypeDef",
     {
         "detectorModelConfiguration": DetectorModelConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDetectorModelResponseTypeDef = TypedDict(
     "UpdateDetectorModelResponseTypeDef",
     {
         "detectorModelConfiguration": DetectorModelConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInputResponseTypeDef = TypedDict(
     "CreateInputResponseTypeDef",
     {
         "inputConfiguration": InputConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputResponseTypeDef = TypedDict(
     "UpdateInputResponseTypeDef",
     {
         "inputConfiguration": InputConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLoggingOptionsTypeDef = TypedDict(
     "_RequiredLoggingOptionsTypeDef",
     {
         "roleArn": str,
@@ -832,24 +832,24 @@
 
 
 ListDetectorModelsResponseTypeDef = TypedDict(
     "ListDetectorModelsResponseTypeDef",
     {
         "detectorModelSummaries": List[DetectorModelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDetectorModelVersionsResponseTypeDef = TypedDict(
     "ListDetectorModelVersionsResponseTypeDef",
     {
         "detectorModelVersionSummaries": List[DetectorModelVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDynamoDBActionTypeDef = TypedDict(
     "_RequiredDynamoDBActionTypeDef",
     {
         "hashKeyField": str,
@@ -1016,15 +1016,15 @@
 
 
 ListInputsResponseTypeDef = TypedDict(
     "ListInputsResponseTypeDef",
     {
         "inputSummaries": List[InputSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IotSiteWiseInputIdentifierTypeDef = TypedDict(
     "IotSiteWiseInputIdentifierTypeDef",
     {
         "iotSiteWiseAssetModelPropertyIdentifier": IotSiteWiseAssetModelPropertyIdentifierTypeDef,
@@ -1033,15 +1033,15 @@
 )
 
 ListInputRoutingsResponseTypeDef = TypedDict(
     "ListInputRoutingsResponseTypeDef",
     {
         "routedResources": List[RoutedResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecipientDetailTypeDef = TypedDict(
     "RecipientDetailTypeDef",
     {
         "ssoIdentity": SSOIdentityTypeDef,
@@ -1050,15 +1050,15 @@
 )
 
 GetDetectorModelAnalysisResultsResponseTypeDef = TypedDict(
     "GetDetectorModelAnalysisResultsResponseTypeDef",
     {
         "analysisResults": List[AnalysisResultTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IotSiteWiseActionTypeDef = TypedDict(
     "IotSiteWiseActionTypeDef",
     {
         "entryId": str,
@@ -1124,15 +1124,15 @@
     pass
 
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -1220,15 +1220,15 @@
     total=False,
 )
 
 DescribeInputResponseTypeDef = TypedDict(
     "DescribeInputResponseTypeDef",
     {
         "input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListInputRoutingsRequestRequestTypeDef = TypedDict(
     "_RequiredListInputRoutingsRequestRequestTypeDef",
     {
         "inputIdentifier": InputIdentifierTypeDef,
@@ -1440,15 +1440,15 @@
         "roleArn": str,
         "key": str,
         "severity": int,
         "alarmRule": AlarmRuleTypeDef,
         "alarmNotification": AlarmNotificationTypeDef,
         "alarmEventActions": AlarmEventActionsTypeDef,
         "alarmCapabilities": AlarmCapabilitiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAlarmModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAlarmModelRequestRequestTypeDef",
     {
         "alarmModelName": str,
@@ -1551,10 +1551,10 @@
     pass
 
 
 DescribeDetectorModelResponseTypeDef = TypedDict(
     "DescribeDetectorModelResponseTypeDef",
     {
         "detectorModel": DetectorModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents/type_defs.pyi` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -43,56 +43,56 @@
     "AlarmModelVersionSummaryTypeDef",
     "SimpleRuleTypeDef",
     "AnalysisResultLocationTypeDef",
     "AssetPropertyTimestampTypeDef",
     "AssetPropertyVariantTypeDef",
     "AttributeTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAlarmModelResponseTypeDef",
     "DetectorModelConfigurationTypeDef",
     "InputConfigurationTypeDef",
     "DeleteAlarmModelRequestRequestTypeDef",
     "DeleteDetectorModelRequestRequestTypeDef",
     "DeleteInputRequestRequestTypeDef",
     "DescribeAlarmModelRequestRequestTypeDef",
     "DescribeDetectorModelAnalysisRequestRequestTypeDef",
+    "DescribeDetectorModelAnalysisResponseTypeDef",
     "DescribeDetectorModelRequestRequestTypeDef",
     "DescribeInputRequestRequestTypeDef",
     "DetectorDebugOptionTypeDef",
     "DetectorModelSummaryTypeDef",
     "DetectorModelVersionSummaryTypeDef",
     "PayloadTypeDef",
     "EmailContentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetDetectorModelAnalysisResultsRequestRequestTypeDef",
     "IotEventsInputIdentifierTypeDef",
     "InputSummaryTypeDef",
     "IotSiteWiseAssetModelPropertyIdentifierTypeDef",
     "ListAlarmModelVersionsRequestRequestTypeDef",
     "ListAlarmModelsRequestRequestTypeDef",
     "ListDetectorModelVersionsRequestRequestTypeDef",
     "ListDetectorModelsRequestRequestTypeDef",
     "RoutedResourceTypeDef",
     "ListInputsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "SSOIdentityTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDetectorModelAnalysisResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAlarmModelResponseTypeDef",
     "AlarmCapabilitiesTypeDef",
+    "ListAlarmModelsResponseTypeDef",
+    "ListAlarmModelVersionsResponseTypeDef",
     "AlarmRuleTypeDef",
     "AnalysisResultTypeDef",
     "AssetPropertyValueTypeDef",
     "InputDefinitionTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateAlarmModelResponseTypeDef",
-    "DescribeDetectorModelAnalysisResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAlarmModelVersionsResponseTypeDef",
-    "ListAlarmModelsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartDetectorModelAnalysisResponseTypeDef",
-    "UpdateAlarmModelResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateDetectorModelResponseTypeDef",
     "UpdateDetectorModelResponseTypeDef",
     "CreateInputResponseTypeDef",
     "UpdateInputResponseTypeDef",
     "LoggingOptionsTypeDef",
     "ListDetectorModelsResponseTypeDef",
     "ListDetectorModelVersionsResponseTypeDef",
@@ -281,22 +281,23 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAlarmModelResponseTypeDef = TypedDict(
+    "CreateAlarmModelResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "creationTime": datetime,
+        "alarmModelArn": str,
+        "alarmModelVersion": str,
+        "lastUpdateTime": datetime,
+        "status": AlarmModelVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectorModelConfigurationTypeDef = TypedDict(
     "DetectorModelConfigurationTypeDef",
     {
         "detectorModelName": str,
@@ -380,14 +381,22 @@
 DescribeDetectorModelAnalysisRequestRequestTypeDef = TypedDict(
     "DescribeDetectorModelAnalysisRequestRequestTypeDef",
     {
         "analysisId": str,
     },
 )
 
+DescribeDetectorModelAnalysisResponseTypeDef = TypedDict(
+    "DescribeDetectorModelAnalysisResponseTypeDef",
+    {
+        "status": AnalysisStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeDetectorModelRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDetectorModelRequestRequestTypeDef",
     {
         "detectorModelName": str,
     },
 )
 _OptionalDescribeDetectorModelRequestRequestTypeDef = TypedDict(
@@ -468,14 +477,21 @@
     {
         "subject": str,
         "additionalMessage": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDetectorModelAnalysisResultsRequestRequestTypeDef = TypedDict(
     "_RequiredGetDetectorModelAnalysisResultsRequestRequestTypeDef",
     {
         "analysisId": str,
     },
 )
 _OptionalGetDetectorModelAnalysisResultsRequestRequestTypeDef = TypedDict(
@@ -619,31 +635,80 @@
     },
     total=False,
 )
 
 class SSOIdentityTypeDef(_RequiredSSOIdentityTypeDef, _OptionalSSOIdentityTypeDef):
     pass
 
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
+StartDetectorModelAnalysisResponseTypeDef = TypedDict(
+    "StartDetectorModelAnalysisResponseTypeDef",
+    {
+        "analysisId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateAlarmModelResponseTypeDef = TypedDict(
+    "UpdateAlarmModelResponseTypeDef",
+    {
+        "creationTime": datetime,
+        "alarmModelArn": str,
+        "alarmModelVersion": str,
+        "lastUpdateTime": datetime,
+        "status": AlarmModelVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AlarmCapabilitiesTypeDef = TypedDict(
     "AlarmCapabilitiesTypeDef",
     {
         "initializationConfiguration": InitializationConfigurationTypeDef,
         "acknowledgeFlow": AcknowledgeFlowTypeDef,
     },
     total=False,
 )
 
+ListAlarmModelsResponseTypeDef = TypedDict(
+    "ListAlarmModelsResponseTypeDef",
+    {
+        "alarmModelSummaries": List[AlarmModelSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAlarmModelVersionsResponseTypeDef = TypedDict(
+    "ListAlarmModelVersionsResponseTypeDef",
+    {
+        "alarmModelVersionSummaries": List[AlarmModelVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AlarmRuleTypeDef = TypedDict(
     "AlarmRuleTypeDef",
     {
         "simpleRule": SimpleRuleTypeDef,
     },
     total=False,
 )
@@ -672,124 +737,59 @@
 InputDefinitionTypeDef = TypedDict(
     "InputDefinitionTypeDef",
     {
         "attributes": Sequence[AttributeTypeDef],
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateAlarmModelResponseTypeDef = TypedDict(
-    "CreateAlarmModelResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "alarmModelArn": str,
-        "alarmModelVersion": str,
-        "lastUpdateTime": datetime,
-        "status": AlarmModelVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDetectorModelAnalysisResponseTypeDef = TypedDict(
-    "DescribeDetectorModelAnalysisResponseTypeDef",
-    {
-        "status": AnalysisStatusType,
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
-ListAlarmModelVersionsResponseTypeDef = TypedDict(
-    "ListAlarmModelVersionsResponseTypeDef",
-    {
-        "alarmModelVersionSummaries": List[AlarmModelVersionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlarmModelsResponseTypeDef = TypedDict(
-    "ListAlarmModelsResponseTypeDef",
-    {
-        "alarmModelSummaries": List[AlarmModelSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDetectorModelAnalysisResponseTypeDef = TypedDict(
-    "StartDetectorModelAnalysisResponseTypeDef",
-    {
-        "analysisId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAlarmModelResponseTypeDef = TypedDict(
-    "UpdateAlarmModelResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "creationTime": datetime,
-        "alarmModelArn": str,
-        "alarmModelVersion": str,
-        "lastUpdateTime": datetime,
-        "status": AlarmModelVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 CreateDetectorModelResponseTypeDef = TypedDict(
     "CreateDetectorModelResponseTypeDef",
     {
         "detectorModelConfiguration": DetectorModelConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDetectorModelResponseTypeDef = TypedDict(
     "UpdateDetectorModelResponseTypeDef",
     {
         "detectorModelConfiguration": DetectorModelConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInputResponseTypeDef = TypedDict(
     "CreateInputResponseTypeDef",
     {
         "inputConfiguration": InputConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputResponseTypeDef = TypedDict(
     "UpdateInputResponseTypeDef",
     {
         "inputConfiguration": InputConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLoggingOptionsTypeDef = TypedDict(
     "_RequiredLoggingOptionsTypeDef",
     {
         "roleArn": str,
@@ -809,24 +809,24 @@
     pass
 
 ListDetectorModelsResponseTypeDef = TypedDict(
     "ListDetectorModelsResponseTypeDef",
     {
         "detectorModelSummaries": List[DetectorModelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDetectorModelVersionsResponseTypeDef = TypedDict(
     "ListDetectorModelVersionsResponseTypeDef",
     {
         "detectorModelVersionSummaries": List[DetectorModelVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDynamoDBActionTypeDef = TypedDict(
     "_RequiredDynamoDBActionTypeDef",
     {
         "hashKeyField": str,
@@ -977,15 +977,15 @@
     pass
 
 ListInputsResponseTypeDef = TypedDict(
     "ListInputsResponseTypeDef",
     {
         "inputSummaries": List[InputSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IotSiteWiseInputIdentifierTypeDef = TypedDict(
     "IotSiteWiseInputIdentifierTypeDef",
     {
         "iotSiteWiseAssetModelPropertyIdentifier": IotSiteWiseAssetModelPropertyIdentifierTypeDef,
@@ -994,15 +994,15 @@
 )
 
 ListInputRoutingsResponseTypeDef = TypedDict(
     "ListInputRoutingsResponseTypeDef",
     {
         "routedResources": List[RoutedResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecipientDetailTypeDef = TypedDict(
     "RecipientDetailTypeDef",
     {
         "ssoIdentity": SSOIdentityTypeDef,
@@ -1011,15 +1011,15 @@
 )
 
 GetDetectorModelAnalysisResultsResponseTypeDef = TypedDict(
     "GetDetectorModelAnalysisResultsResponseTypeDef",
     {
         "analysisResults": List[AnalysisResultTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IotSiteWiseActionTypeDef = TypedDict(
     "IotSiteWiseActionTypeDef",
     {
         "entryId": str,
@@ -1081,15 +1081,15 @@
 ):
     pass
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -1175,15 +1175,15 @@
     total=False,
 )
 
 DescribeInputResponseTypeDef = TypedDict(
     "DescribeInputResponseTypeDef",
     {
         "input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListInputRoutingsRequestRequestTypeDef = TypedDict(
     "_RequiredListInputRoutingsRequestRequestTypeDef",
     {
         "inputIdentifier": InputIdentifierTypeDef,
@@ -1381,15 +1381,15 @@
         "roleArn": str,
         "key": str,
         "severity": int,
         "alarmRule": AlarmRuleTypeDef,
         "alarmNotification": AlarmNotificationTypeDef,
         "alarmEventActions": AlarmEventActionsTypeDef,
         "alarmCapabilities": AlarmCapabilitiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAlarmModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAlarmModelRequestRequestTypeDef",
     {
         "alarmModelName": str,
@@ -1486,10 +1486,10 @@
 ):
     pass
 
 DescribeDetectorModelResponseTypeDef = TypedDict(
     "DescribeDetectorModelResponseTypeDef",
     {
         "detectorModel": DetectorModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/PKG-INFO` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotevents
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTEvents 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTEvents 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotevents"></a>
 
 # types-aiobotocore-iotevents
 
 [![PyPI - types-aiobotocore-iotevents](https://img.shields.io/pypi/v/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEvents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
+[aiobotocore.IoTEvents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents.html#IoTEvents)
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
 [types-aiobotocore-iotevents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,56 +312,56 @@
     AlarmModelVersionSummaryTypeDef,
     SimpleRuleTypeDef,
     AnalysisResultLocationTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AttributeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlarmModelResponseTypeDef,
     DetectorModelConfigurationTypeDef,
     InputConfigurationTypeDef,
     DeleteAlarmModelRequestRequestTypeDef,
     DeleteDetectorModelRequestRequestTypeDef,
     DeleteInputRequestRequestTypeDef,
     DescribeAlarmModelRequestRequestTypeDef,
     DescribeDetectorModelAnalysisRequestRequestTypeDef,
+    DescribeDetectorModelAnalysisResponseTypeDef,
     DescribeDetectorModelRequestRequestTypeDef,
     DescribeInputRequestRequestTypeDef,
     DetectorDebugOptionTypeDef,
     DetectorModelSummaryTypeDef,
     DetectorModelVersionSummaryTypeDef,
     PayloadTypeDef,
     EmailContentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDetectorModelAnalysisResultsRequestRequestTypeDef,
     IotEventsInputIdentifierTypeDef,
     InputSummaryTypeDef,
     IotSiteWiseAssetModelPropertyIdentifierTypeDef,
     ListAlarmModelVersionsRequestRequestTypeDef,
     ListAlarmModelsRequestRequestTypeDef,
     ListDetectorModelVersionsRequestRequestTypeDef,
     ListDetectorModelsRequestRequestTypeDef,
     RoutedResourceTypeDef,
     ListInputsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     SSOIdentityTypeDef,
+    ResponseMetadataTypeDef,
+    StartDetectorModelAnalysisResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlarmModelResponseTypeDef,
     AlarmCapabilitiesTypeDef,
+    ListAlarmModelsResponseTypeDef,
+    ListAlarmModelVersionsResponseTypeDef,
     AlarmRuleTypeDef,
     AnalysisResultTypeDef,
     AssetPropertyValueTypeDef,
     InputDefinitionTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateAlarmModelResponseTypeDef,
-    DescribeDetectorModelAnalysisResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAlarmModelVersionsResponseTypeDef,
-    ListAlarmModelsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDetectorModelAnalysisResponseTypeDef,
-    UpdateAlarmModelResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDetectorModelResponseTypeDef,
     UpdateDetectorModelResponseTypeDef,
     CreateInputResponseTypeDef,
     UpdateInputResponseTypeDef,
     LoggingOptionsTypeDef,
     ListDetectorModelsResponseTypeDef,
     ListDetectorModelVersionsResponseTypeDef,
@@ -421,43 +421,43 @@
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

### Comparing `types-aiobotocore-iotevents-2.5.0.post1/types_aiobotocore_iotevents.egg-info/SOURCES.txt` & `types-aiobotocore-iotevents-2.5.1/types_aiobotocore_iotevents.egg-info/SOURCES.txt`

 * *Files identical despite different names*

