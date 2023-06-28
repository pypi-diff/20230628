# Comparing `tmp/types-aiobotocore-iotevents-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotevents-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotevents-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotevents-data-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotevents-data-2.5.0.post1.tar` & `types-aiobotocore-iotevents-data-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.747297 types-aiobotocore-iotevents-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14598 2023-03-11 12:26:46.743297 types-aiobotocore-iotevents-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13000 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.747297 types-aiobotocore-iotevents-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.739297 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      492 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11762 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    11742 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8094 2023-03-11 12:16:20.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8092 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18845 2023-03-11 12:16:22.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18820 2023-03-11 12:16:20.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:19.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.743297 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14598 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:46.000000 types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.310153 types-aiobotocore-iotevents-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14597 2023-06-28 01:43:38.310153 types-aiobotocore-iotevents-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13005 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.310153 types-aiobotocore-iotevents-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.310153 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11762 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11742 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8303 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8301 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18869 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18844 2023-06-28 01:32:59.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:58.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.310153 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14597 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:38.000000 types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/LICENSE` & `types-aiobotocore-iotevents-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotevents-data-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotevents-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTEventsData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTEventsData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotevents-data"></a>
 
 # types-aiobotocore-iotevents-data
 
 [![PyPI - types-aiobotocore-iotevents-data](https://img.shields.io/pypi/v/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEventsData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
+[aiobotocore.IoTEventsData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
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
 [types-aiobotocore-iotevents-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,15 +298,14 @@
 
 ```python
 from types_aiobotocore_iotevents_data.type_defs import (
     AcknowledgeActionConfigurationTypeDef,
     AcknowledgeAlarmActionRequestTypeDef,
     AlarmSummaryTypeDef,
     BatchAlarmActionErrorEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteDetectorErrorEntryTypeDef,
     DeleteDetectorRequestTypeDef,
     DisableAlarmActionRequestTypeDef,
     EnableAlarmActionRequestTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     ResetAlarmActionRequestTypeDef,
     SnoozeAlarmActionRequestTypeDef,
@@ -321,23 +320,24 @@
     VariableDefinitionTypeDef,
     DetectorStateSummaryTypeDef,
     TimerTypeDef,
     VariableTypeDef,
     ListAlarmsRequestRequestTypeDef,
     ListDetectorsRequestRequestTypeDef,
     TimestampValueTypeDef,
+    ResponseMetadataTypeDef,
     SimpleRuleEvaluationTypeDef,
     StateChangeConfigurationTypeDef,
     BatchAcknowledgeAlarmRequestRequestTypeDef,
+    ListAlarmsResponseTypeDef,
     BatchAcknowledgeAlarmResponseTypeDef,
     BatchDisableAlarmResponseTypeDef,
     BatchEnableAlarmResponseTypeDef,
     BatchResetAlarmResponseTypeDef,
     BatchSnoozeAlarmResponseTypeDef,
-    ListAlarmsResponseTypeDef,
     BatchDeleteDetectorResponseTypeDef,
     BatchDeleteDetectorRequestRequestTypeDef,
     BatchDisableAlarmRequestRequestTypeDef,
     BatchEnableAlarmRequestRequestTypeDef,
     BatchPutMessageResponseTypeDef,
     BatchResetAlarmRequestRequestTypeDef,
     BatchSnoozeAlarmRequestRequestTypeDef,
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/README.md` & `types-aiobotocore-iotevents-data-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotevents-data"></a>
 
 # types-aiobotocore-iotevents-data
 
 [![PyPI - types-aiobotocore-iotevents-data](https://img.shields.io/pypi/v/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEventsData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
+[aiobotocore.IoTEventsData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
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
 [types-aiobotocore-iotevents-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,15 +265,14 @@
 
 ```python
 from types_aiobotocore_iotevents_data.type_defs import (
     AcknowledgeActionConfigurationTypeDef,
     AcknowledgeAlarmActionRequestTypeDef,
     AlarmSummaryTypeDef,
     BatchAlarmActionErrorEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteDetectorErrorEntryTypeDef,
     DeleteDetectorRequestTypeDef,
     DisableAlarmActionRequestTypeDef,
     EnableAlarmActionRequestTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     ResetAlarmActionRequestTypeDef,
     SnoozeAlarmActionRequestTypeDef,
@@ -288,23 +287,24 @@
     VariableDefinitionTypeDef,
     DetectorStateSummaryTypeDef,
     TimerTypeDef,
     VariableTypeDef,
     ListAlarmsRequestRequestTypeDef,
     ListDetectorsRequestRequestTypeDef,
     TimestampValueTypeDef,
+    ResponseMetadataTypeDef,
     SimpleRuleEvaluationTypeDef,
     StateChangeConfigurationTypeDef,
     BatchAcknowledgeAlarmRequestRequestTypeDef,
+    ListAlarmsResponseTypeDef,
     BatchAcknowledgeAlarmResponseTypeDef,
     BatchDisableAlarmResponseTypeDef,
     BatchEnableAlarmResponseTypeDef,
     BatchResetAlarmResponseTypeDef,
     BatchSnoozeAlarmResponseTypeDef,
-    ListAlarmsResponseTypeDef,
     BatchDeleteDetectorResponseTypeDef,
     BatchDeleteDetectorRequestRequestTypeDef,
     BatchDisableAlarmRequestRequestTypeDef,
     BatchEnableAlarmRequestRequestTypeDef,
     BatchPutMessageResponseTypeDef,
     BatchResetAlarmRequestRequestTypeDef,
     BatchSnoozeAlarmRequestRequestTypeDef,
@@ -335,43 +335,43 @@
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/setup.py` & `types-aiobotocore-iotevents-data-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotevents-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotevents-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotevents_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTEventsData 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTEventsData 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/"
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/__main__.py` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTEventsData 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTEventsData 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData\nOther"
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/client.py` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/client.pyi` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/literals.py` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -107,14 +107,15 @@
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
@@ -193,14 +194,15 @@
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
@@ -211,14 +213,15 @@
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
@@ -254,14 +257,15 @@
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
@@ -280,16 +284,19 @@
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
@@ -373,15 +380,17 @@
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/literals.pyi` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/literals.pyi`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/type_defs.py` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -35,15 +35,14 @@
 
 
 __all__ = (
     "AcknowledgeActionConfigurationTypeDef",
     "AcknowledgeAlarmActionRequestTypeDef",
     "AlarmSummaryTypeDef",
     "BatchAlarmActionErrorEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteDetectorErrorEntryTypeDef",
     "DeleteDetectorRequestTypeDef",
     "DisableAlarmActionRequestTypeDef",
     "EnableAlarmActionRequestTypeDef",
     "BatchPutMessageErrorEntryTypeDef",
     "ResetAlarmActionRequestTypeDef",
     "SnoozeAlarmActionRequestTypeDef",
@@ -58,23 +57,24 @@
     "VariableDefinitionTypeDef",
     "DetectorStateSummaryTypeDef",
     "TimerTypeDef",
     "VariableTypeDef",
     "ListAlarmsRequestRequestTypeDef",
     "ListDetectorsRequestRequestTypeDef",
     "TimestampValueTypeDef",
+    "ResponseMetadataTypeDef",
     "SimpleRuleEvaluationTypeDef",
     "StateChangeConfigurationTypeDef",
     "BatchAcknowledgeAlarmRequestRequestTypeDef",
+    "ListAlarmsResponseTypeDef",
     "BatchAcknowledgeAlarmResponseTypeDef",
     "BatchDisableAlarmResponseTypeDef",
     "BatchEnableAlarmResponseTypeDef",
     "BatchResetAlarmResponseTypeDef",
     "BatchSnoozeAlarmResponseTypeDef",
-    "ListAlarmsResponseTypeDef",
     "BatchDeleteDetectorResponseTypeDef",
     "BatchDeleteDetectorRequestRequestTypeDef",
     "BatchDisableAlarmRequestRequestTypeDef",
     "BatchEnableAlarmRequestRequestTypeDef",
     "BatchPutMessageResponseTypeDef",
     "BatchResetAlarmRequestRequestTypeDef",
     "BatchSnoozeAlarmRequestRequestTypeDef",
@@ -147,25 +147,14 @@
         "requestId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
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
 BatchDeleteDetectorErrorEntryTypeDef = TypedDict(
     "BatchDeleteDetectorErrorEntryTypeDef",
     {
         "messageId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
     },
@@ -471,14 +460,25 @@
     "TimestampValueTypeDef",
     {
         "timeInMillis": int,
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
 SimpleRuleEvaluationTypeDef = TypedDict(
     "SimpleRuleEvaluationTypeDef",
     {
         "inputPropertyValue": str,
         "operator": ComparisonOperatorType,
         "thresholdValue": str,
     },
@@ -496,68 +496,68 @@
 BatchAcknowledgeAlarmRequestRequestTypeDef = TypedDict(
     "BatchAcknowledgeAlarmRequestRequestTypeDef",
     {
         "acknowledgeActionRequests": Sequence[AcknowledgeAlarmActionRequestTypeDef],
     },
 )
 
+ListAlarmsResponseTypeDef = TypedDict(
+    "ListAlarmsResponseTypeDef",
+    {
+        "alarmSummaries": List[AlarmSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchAcknowledgeAlarmResponseTypeDef = TypedDict(
     "BatchAcknowledgeAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisableAlarmResponseTypeDef = TypedDict(
     "BatchDisableAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEnableAlarmResponseTypeDef = TypedDict(
     "BatchEnableAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchResetAlarmResponseTypeDef = TypedDict(
     "BatchResetAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchSnoozeAlarmResponseTypeDef = TypedDict(
     "BatchSnoozeAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlarmsResponseTypeDef = TypedDict(
-    "ListAlarmsResponseTypeDef",
-    {
-        "alarmSummaries": List[AlarmSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDetectorResponseTypeDef = TypedDict(
     "BatchDeleteDetectorResponseTypeDef",
     {
         "batchDeleteDetectorErrorEntries": List[BatchDeleteDetectorErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDetectorRequestRequestTypeDef = TypedDict(
     "BatchDeleteDetectorRequestRequestTypeDef",
     {
         "detectors": Sequence[DeleteDetectorRequestTypeDef],
@@ -578,15 +578,15 @@
     },
 )
 
 BatchPutMessageResponseTypeDef = TypedDict(
     "BatchPutMessageResponseTypeDef",
     {
         "BatchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchResetAlarmRequestRequestTypeDef = TypedDict(
     "BatchResetAlarmRequestRequestTypeDef",
     {
         "resetActionRequests": Sequence[ResetAlarmActionRequestTypeDef],
@@ -600,15 +600,15 @@
     },
 )
 
 BatchUpdateDetectorResponseTypeDef = TypedDict(
     "BatchUpdateDetectorResponseTypeDef",
     {
         "batchUpdateDetectorErrorEntries": List[BatchUpdateDetectorErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomerActionTypeDef = TypedDict(
     "CustomerActionTypeDef",
     {
         "actionName": CustomerActionNameType,
@@ -714,15 +714,15 @@
 
 
 ListDetectorsResponseTypeDef = TypedDict(
     "ListDetectorsResponseTypeDef",
     {
         "detectorSummaries": List[DetectorSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectorTypeDef = TypedDict(
     "DetectorTypeDef",
     {
         "detectorModelName": str,
@@ -760,15 +760,15 @@
     },
 )
 
 DescribeDetectorResponseTypeDef = TypedDict(
     "DescribeDetectorResponseTypeDef",
     {
         "detector": DetectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
     {
         "alarmModelName": str,
@@ -782,10 +782,10 @@
     total=False,
 )
 
 DescribeAlarmResponseTypeDef = TypedDict(
     "DescribeAlarmResponseTypeDef",
     {
         "alarm": AlarmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data/type_defs.pyi` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -34,15 +34,14 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcknowledgeActionConfigurationTypeDef",
     "AcknowledgeAlarmActionRequestTypeDef",
     "AlarmSummaryTypeDef",
     "BatchAlarmActionErrorEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteDetectorErrorEntryTypeDef",
     "DeleteDetectorRequestTypeDef",
     "DisableAlarmActionRequestTypeDef",
     "EnableAlarmActionRequestTypeDef",
     "BatchPutMessageErrorEntryTypeDef",
     "ResetAlarmActionRequestTypeDef",
     "SnoozeAlarmActionRequestTypeDef",
@@ -57,23 +56,24 @@
     "VariableDefinitionTypeDef",
     "DetectorStateSummaryTypeDef",
     "TimerTypeDef",
     "VariableTypeDef",
     "ListAlarmsRequestRequestTypeDef",
     "ListDetectorsRequestRequestTypeDef",
     "TimestampValueTypeDef",
+    "ResponseMetadataTypeDef",
     "SimpleRuleEvaluationTypeDef",
     "StateChangeConfigurationTypeDef",
     "BatchAcknowledgeAlarmRequestRequestTypeDef",
+    "ListAlarmsResponseTypeDef",
     "BatchAcknowledgeAlarmResponseTypeDef",
     "BatchDisableAlarmResponseTypeDef",
     "BatchEnableAlarmResponseTypeDef",
     "BatchResetAlarmResponseTypeDef",
     "BatchSnoozeAlarmResponseTypeDef",
-    "ListAlarmsResponseTypeDef",
     "BatchDeleteDetectorResponseTypeDef",
     "BatchDeleteDetectorRequestRequestTypeDef",
     "BatchDisableAlarmRequestRequestTypeDef",
     "BatchEnableAlarmRequestRequestTypeDef",
     "BatchPutMessageResponseTypeDef",
     "BatchResetAlarmRequestRequestTypeDef",
     "BatchSnoozeAlarmRequestRequestTypeDef",
@@ -144,25 +144,14 @@
         "requestId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
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
 BatchDeleteDetectorErrorEntryTypeDef = TypedDict(
     "BatchDeleteDetectorErrorEntryTypeDef",
     {
         "messageId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
     },
@@ -450,14 +439,25 @@
     "TimestampValueTypeDef",
     {
         "timeInMillis": int,
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
 SimpleRuleEvaluationTypeDef = TypedDict(
     "SimpleRuleEvaluationTypeDef",
     {
         "inputPropertyValue": str,
         "operator": ComparisonOperatorType,
         "thresholdValue": str,
     },
@@ -475,68 +475,68 @@
 BatchAcknowledgeAlarmRequestRequestTypeDef = TypedDict(
     "BatchAcknowledgeAlarmRequestRequestTypeDef",
     {
         "acknowledgeActionRequests": Sequence[AcknowledgeAlarmActionRequestTypeDef],
     },
 )
 
+ListAlarmsResponseTypeDef = TypedDict(
+    "ListAlarmsResponseTypeDef",
+    {
+        "alarmSummaries": List[AlarmSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchAcknowledgeAlarmResponseTypeDef = TypedDict(
     "BatchAcknowledgeAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisableAlarmResponseTypeDef = TypedDict(
     "BatchDisableAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEnableAlarmResponseTypeDef = TypedDict(
     "BatchEnableAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchResetAlarmResponseTypeDef = TypedDict(
     "BatchResetAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchSnoozeAlarmResponseTypeDef = TypedDict(
     "BatchSnoozeAlarmResponseTypeDef",
     {
         "errorEntries": List[BatchAlarmActionErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlarmsResponseTypeDef = TypedDict(
-    "ListAlarmsResponseTypeDef",
-    {
-        "alarmSummaries": List[AlarmSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDetectorResponseTypeDef = TypedDict(
     "BatchDeleteDetectorResponseTypeDef",
     {
         "batchDeleteDetectorErrorEntries": List[BatchDeleteDetectorErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDetectorRequestRequestTypeDef = TypedDict(
     "BatchDeleteDetectorRequestRequestTypeDef",
     {
         "detectors": Sequence[DeleteDetectorRequestTypeDef],
@@ -557,15 +557,15 @@
     },
 )
 
 BatchPutMessageResponseTypeDef = TypedDict(
     "BatchPutMessageResponseTypeDef",
     {
         "BatchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchResetAlarmRequestRequestTypeDef = TypedDict(
     "BatchResetAlarmRequestRequestTypeDef",
     {
         "resetActionRequests": Sequence[ResetAlarmActionRequestTypeDef],
@@ -579,15 +579,15 @@
     },
 )
 
 BatchUpdateDetectorResponseTypeDef = TypedDict(
     "BatchUpdateDetectorResponseTypeDef",
     {
         "batchUpdateDetectorErrorEntries": List[BatchUpdateDetectorErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomerActionTypeDef = TypedDict(
     "CustomerActionTypeDef",
     {
         "actionName": CustomerActionNameType,
@@ -689,15 +689,15 @@
     pass
 
 ListDetectorsResponseTypeDef = TypedDict(
     "ListDetectorsResponseTypeDef",
     {
         "detectorSummaries": List[DetectorSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectorTypeDef = TypedDict(
     "DetectorTypeDef",
     {
         "detectorModelName": str,
@@ -735,15 +735,15 @@
     },
 )
 
 DescribeDetectorResponseTypeDef = TypedDict(
     "DescribeDetectorResponseTypeDef",
     {
         "detector": DetectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
     {
         "alarmModelName": str,
@@ -757,10 +757,10 @@
     total=False,
 )
 
 DescribeAlarmResponseTypeDef = TypedDict(
     "DescribeAlarmResponseTypeDef",
     {
         "alarm": AlarmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/PKG-INFO` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotevents-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTEventsData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTEventsData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotevents-data"></a>
 
 # types-aiobotocore-iotevents-data
 
 [![PyPI - types-aiobotocore-iotevents-data](https://img.shields.io/pypi/v/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotevents-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotevents-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotevents-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotevents-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTEventsData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
+[aiobotocore.IoTEventsData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotevents-data.html#IoTEventsData)
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
 [types-aiobotocore-iotevents-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotevents_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,15 +298,14 @@
 
 ```python
 from types_aiobotocore_iotevents_data.type_defs import (
     AcknowledgeActionConfigurationTypeDef,
     AcknowledgeAlarmActionRequestTypeDef,
     AlarmSummaryTypeDef,
     BatchAlarmActionErrorEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteDetectorErrorEntryTypeDef,
     DeleteDetectorRequestTypeDef,
     DisableAlarmActionRequestTypeDef,
     EnableAlarmActionRequestTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     ResetAlarmActionRequestTypeDef,
     SnoozeAlarmActionRequestTypeDef,
@@ -321,23 +320,24 @@
     VariableDefinitionTypeDef,
     DetectorStateSummaryTypeDef,
     TimerTypeDef,
     VariableTypeDef,
     ListAlarmsRequestRequestTypeDef,
     ListDetectorsRequestRequestTypeDef,
     TimestampValueTypeDef,
+    ResponseMetadataTypeDef,
     SimpleRuleEvaluationTypeDef,
     StateChangeConfigurationTypeDef,
     BatchAcknowledgeAlarmRequestRequestTypeDef,
+    ListAlarmsResponseTypeDef,
     BatchAcknowledgeAlarmResponseTypeDef,
     BatchDisableAlarmResponseTypeDef,
     BatchEnableAlarmResponseTypeDef,
     BatchResetAlarmResponseTypeDef,
     BatchSnoozeAlarmResponseTypeDef,
-    ListAlarmsResponseTypeDef,
     BatchDeleteDetectorResponseTypeDef,
     BatchDeleteDetectorRequestRequestTypeDef,
     BatchDisableAlarmRequestRequestTypeDef,
     BatchEnableAlarmRequestRequestTypeDef,
     BatchPutMessageResponseTypeDef,
     BatchResetAlarmRequestRequestTypeDef,
     BatchSnoozeAlarmRequestRequestTypeDef,
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-iotevents-data-2.5.0.post1/types_aiobotocore_iotevents_data.egg-info/SOURCES.txt` & `types-aiobotocore-iotevents-data-2.5.1/types_aiobotocore_iotevents_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

