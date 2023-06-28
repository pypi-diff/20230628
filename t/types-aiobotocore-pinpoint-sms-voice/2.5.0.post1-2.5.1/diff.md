# Comparing `tmp/types-aiobotocore-pinpoint-sms-voice-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pinpoint-sms-voice-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pinpoint-sms-voice-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-pinpoint-sms-voice-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1.tar` & `types-aiobotocore-pinpoint-sms-voice-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.019507 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13383 2023-03-11 12:27:08.019507 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11770 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.019507 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2215 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.015507 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/
--rw-r--r--   0 runner    (1001) docker     (123)      520 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9226 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9211 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7486 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7484 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6708 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6703 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.019507 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13383 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.922192 types-aiobotocore-pinpoint-sms-voice-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13386 2023-06-28 01:43:58.922192 types-aiobotocore-pinpoint-sms-voice-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11779 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.922192 types-aiobotocore-pinpoint-sms-voice-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.922192 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/
+-rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9226 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9211 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7695 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7693 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6712 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6707 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.922192 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13386 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/LICENSE` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint-sms-voice
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PinpointSMSVoice 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PinpointSMSVoice 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint-sms-voice"></a>
 
 # types-aiobotocore-pinpoint-sms-voice
 
 [![PyPI - types-aiobotocore-pinpoint-sms-voice](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-sms-voice?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-sms-voice)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointSMSVoice 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
+[aiobotocore.PinpointSMSVoice 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
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
 [types-aiobotocore-pinpoint-sms-voice docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,20 +297,20 @@
     CloudWatchLogsDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SnsDestinationTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     PlainTextMessageTypeTypeDef,
+    ResponseMetadataTypeDef,
     SSMLMessageTypeTypeDef,
+    SendVoiceMessageResponseTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
-    SendVoiceMessageResponseTypeDef,
     VoiceMessageContentTypeDef,
     CreateConfigurationSetEventDestinationRequestRequestTypeDef,
     UpdateConfigurationSetEventDestinationRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsResponseTypeDef,
     SendVoiceMessageRequestRequestTypeDef,
 )
 
@@ -322,43 +322,43 @@
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/README.md` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pinpoint-sms-voice"></a>
 
 # types-aiobotocore-pinpoint-sms-voice
 
 [![PyPI - types-aiobotocore-pinpoint-sms-voice](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-sms-voice?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-sms-voice)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointSMSVoice 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
+[aiobotocore.PinpointSMSVoice 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
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
 [types-aiobotocore-pinpoint-sms-voice docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/).
 
 See how it helps to find and fix potential bugs:
 
@@ -264,20 +264,20 @@
     CloudWatchLogsDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SnsDestinationTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     PlainTextMessageTypeTypeDef,
+    ResponseMetadataTypeDef,
     SSMLMessageTypeTypeDef,
+    SendVoiceMessageResponseTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
-    SendVoiceMessageResponseTypeDef,
     VoiceMessageContentTypeDef,
     CreateConfigurationSetEventDestinationRequestRequestTypeDef,
     UpdateConfigurationSetEventDestinationRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsResponseTypeDef,
     SendVoiceMessageRequestRequestTypeDef,
 )
 
@@ -289,43 +289,43 @@
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/setup.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-pinpoint-sms-voice.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pinpoint-sms-voice",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pinpoint_sms_voice"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.PinpointSMSVoice 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.PinpointSMSVoice 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/"
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__init__.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__init__.pyi` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/__main__.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/__main__.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.PinpointSMSVoice 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.PinpointSMSVoice 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice\nOther"
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/client.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/client.pyi` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/literals.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -84,14 +84,15 @@
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
@@ -170,14 +171,15 @@
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
@@ -188,14 +190,15 @@
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
@@ -231,14 +234,15 @@
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
@@ -257,16 +261,19 @@
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
@@ -350,15 +357,17 @@
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/literals.pyi` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -82,14 +82,15 @@
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
@@ -168,14 +169,15 @@
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
@@ -186,14 +188,15 @@
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
@@ -229,14 +232,15 @@
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
@@ -255,16 +259,19 @@
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
@@ -348,15 +355,17 @@
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/type_defs.py` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,20 +27,20 @@
     "CloudWatchLogsDestinationTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
     "DeleteConfigurationSetEventDestinationRequestRequestTypeDef",
     "DeleteConfigurationSetRequestRequestTypeDef",
     "KinesisFirehoseDestinationTypeDef",
     "SnsDestinationTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "PlainTextMessageTypeTypeDef",
+    "ResponseMetadataTypeDef",
     "SSMLMessageTypeTypeDef",
+    "SendVoiceMessageResponseTypeDef",
     "EventDestinationDefinitionTypeDef",
     "EventDestinationTypeDef",
-    "SendVoiceMessageResponseTypeDef",
     "VoiceMessageContentTypeDef",
     "CreateConfigurationSetEventDestinationRequestRequestTypeDef",
     "UpdateConfigurationSetEventDestinationRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     "SendVoiceMessageRequestRequestTypeDef",
 )
 
@@ -104,43 +104,51 @@
 GetConfigurationSetEventDestinationsRequestRequestTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 
+PlainTextMessageTypeTypeDef = TypedDict(
+    "PlainTextMessageTypeTypeDef",
+    {
+        "LanguageCode": str,
+        "Text": str,
+        "VoiceId": str,
+    },
+    total=False,
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
         "RetryAttempts": int,
     },
 )
 
-PlainTextMessageTypeTypeDef = TypedDict(
-    "PlainTextMessageTypeTypeDef",
+SSMLMessageTypeTypeDef = TypedDict(
+    "SSMLMessageTypeTypeDef",
     {
         "LanguageCode": str,
         "Text": str,
         "VoiceId": str,
     },
     total=False,
 )
 
-SSMLMessageTypeTypeDef = TypedDict(
-    "SSMLMessageTypeTypeDef",
+SendVoiceMessageResponseTypeDef = TypedDict(
+    "SendVoiceMessageResponseTypeDef",
     {
-        "LanguageCode": str,
-        "Text": str,
-        "VoiceId": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 EventDestinationDefinitionTypeDef = TypedDict(
     "EventDestinationDefinitionTypeDef",
     {
         "CloudWatchLogsDestination": CloudWatchLogsDestinationTypeDef,
         "Enabled": bool,
@@ -160,22 +168,14 @@
         "MatchingEventTypes": List[EventTypeType],
         "Name": str,
         "SnsDestination": SnsDestinationTypeDef,
     },
     total=False,
 )
 
-SendVoiceMessageResponseTypeDef = TypedDict(
-    "SendVoiceMessageResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 VoiceMessageContentTypeDef = TypedDict(
     "VoiceMessageContentTypeDef",
     {
         "CallInstructionsMessage": CallInstructionsMessageTypeTypeDef,
         "PlainTextMessage": PlainTextMessageTypeTypeDef,
         "SSMLMessage": SSMLMessageTypeTypeDef,
     },
@@ -228,15 +228,15 @@
     pass
 
 
 GetConfigurationSetEventDestinationsResponseTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     {
         "EventDestinations": List[EventDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendVoiceMessageRequestRequestTypeDef = TypedDict(
     "SendVoiceMessageRequestRequestTypeDef",
     {
         "CallerId": str,
```

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice/type_defs.pyi` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,20 +26,20 @@
     "CloudWatchLogsDestinationTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
     "DeleteConfigurationSetEventDestinationRequestRequestTypeDef",
     "DeleteConfigurationSetRequestRequestTypeDef",
     "KinesisFirehoseDestinationTypeDef",
     "SnsDestinationTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "PlainTextMessageTypeTypeDef",
+    "ResponseMetadataTypeDef",
     "SSMLMessageTypeTypeDef",
+    "SendVoiceMessageResponseTypeDef",
     "EventDestinationDefinitionTypeDef",
     "EventDestinationTypeDef",
-    "SendVoiceMessageResponseTypeDef",
     "VoiceMessageContentTypeDef",
     "CreateConfigurationSetEventDestinationRequestRequestTypeDef",
     "UpdateConfigurationSetEventDestinationRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     "SendVoiceMessageRequestRequestTypeDef",
 )
 
@@ -103,43 +103,51 @@
 GetConfigurationSetEventDestinationsRequestRequestTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 
+PlainTextMessageTypeTypeDef = TypedDict(
+    "PlainTextMessageTypeTypeDef",
+    {
+        "LanguageCode": str,
+        "Text": str,
+        "VoiceId": str,
+    },
+    total=False,
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
         "RetryAttempts": int,
     },
 )
 
-PlainTextMessageTypeTypeDef = TypedDict(
-    "PlainTextMessageTypeTypeDef",
+SSMLMessageTypeTypeDef = TypedDict(
+    "SSMLMessageTypeTypeDef",
     {
         "LanguageCode": str,
         "Text": str,
         "VoiceId": str,
     },
     total=False,
 )
 
-SSMLMessageTypeTypeDef = TypedDict(
-    "SSMLMessageTypeTypeDef",
+SendVoiceMessageResponseTypeDef = TypedDict(
+    "SendVoiceMessageResponseTypeDef",
     {
-        "LanguageCode": str,
-        "Text": str,
-        "VoiceId": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 EventDestinationDefinitionTypeDef = TypedDict(
     "EventDestinationDefinitionTypeDef",
     {
         "CloudWatchLogsDestination": CloudWatchLogsDestinationTypeDef,
         "Enabled": bool,
@@ -159,22 +167,14 @@
         "MatchingEventTypes": List[EventTypeType],
         "Name": str,
         "SnsDestination": SnsDestinationTypeDef,
     },
     total=False,
 )
 
-SendVoiceMessageResponseTypeDef = TypedDict(
-    "SendVoiceMessageResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 VoiceMessageContentTypeDef = TypedDict(
     "VoiceMessageContentTypeDef",
     {
         "CallInstructionsMessage": CallInstructionsMessageTypeTypeDef,
         "PlainTextMessage": PlainTextMessageTypeTypeDef,
         "SSMLMessage": SSMLMessageTypeTypeDef,
     },
@@ -223,15 +223,15 @@
 ):
     pass
 
 GetConfigurationSetEventDestinationsResponseTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     {
         "EventDestinations": List[EventDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendVoiceMessageRequestRequestTypeDef = TypedDict(
     "SendVoiceMessageRequestRequestTypeDef",
     {
         "CallerId": str,
```

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/PKG-INFO` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint-sms-voice
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PinpointSMSVoice 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PinpointSMSVoice 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint-sms-voice"></a>
 
 # types-aiobotocore-pinpoint-sms-voice
 
 [![PyPI - types-aiobotocore-pinpoint-sms-voice](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-sms-voice.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-sms-voice)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-sms-voice?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-sms-voice)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointSMSVoice 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
+[aiobotocore.PinpointSMSVoice 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-sms-voice.html#PinpointSMSVoice)
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
 [types-aiobotocore-pinpoint-sms-voice docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_sms_voice/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,20 +297,20 @@
     CloudWatchLogsDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SnsDestinationTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     PlainTextMessageTypeTypeDef,
+    ResponseMetadataTypeDef,
     SSMLMessageTypeTypeDef,
+    SendVoiceMessageResponseTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
-    SendVoiceMessageResponseTypeDef,
     VoiceMessageContentTypeDef,
     CreateConfigurationSetEventDestinationRequestRequestTypeDef,
     UpdateConfigurationSetEventDestinationRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsResponseTypeDef,
     SendVoiceMessageRequestRequestTypeDef,
 )
 
@@ -322,43 +322,43 @@
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

### Comparing `types-aiobotocore-pinpoint-sms-voice-2.5.0.post1/types_aiobotocore_pinpoint_sms_voice.egg-info/SOURCES.txt` & `types-aiobotocore-pinpoint-sms-voice-2.5.1/types_aiobotocore_pinpoint_sms_voice.egg-info/SOURCES.txt`

 * *Files identical despite different names*

