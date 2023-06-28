# Comparing `tmp/types-aiobotocore-chime-sdk-meetings-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-chime-sdk-meetings-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-chime-sdk-meetings-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-chime-sdk-meetings-2.5.1.tar", last modified: Wed Jun 28 01:43:11 2023, max compression
```

## Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1.tar` & `types-aiobotocore-chime-sdk-meetings-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.671000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14593 2023-03-11 12:26:17.667000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12980 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.671000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2215 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.667000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/
--rw-r--r--   0 runner    (1001) docker     (123)      520 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15502 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15478 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9284 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9282 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14192 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14179 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.667000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14593 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.126103 types-aiobotocore-chime-sdk-meetings-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14596 2023-06-28 01:43:11.126103 types-aiobotocore-chime-sdk-meetings-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12989 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.126103 types-aiobotocore-chime-sdk-meetings-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.110103 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/
+-rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15503 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15479 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9519 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9517 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14282 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14269 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:05.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.126103 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14596 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/LICENSE` & `types-aiobotocore-chime-sdk-meetings-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/PKG-INFO` & `types-aiobotocore-chime-sdk-meetings-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime-sdk-meetings
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKMeetings 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKMeetings 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime-sdk-meetings"></a>
 
 # types-aiobotocore-chime-sdk-meetings
 
 [![PyPI - types-aiobotocore-chime-sdk-meetings](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-meetings?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-meetings)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMeetings 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
+[aiobotocore.ChimeSDKMeetings 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
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
 [types-aiobotocore-chime-sdk-meetings docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,35 +306,35 @@
 
 ```python
 from types_aiobotocore_chime_sdk_meetings.type_defs import (
     AttendeeCapabilitiesTypeDef,
     AttendeeIdItemTypeDef,
     AudioFeaturesTypeDef,
     CreateAttendeeErrorTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsConfigurationTypeDef,
     TagTypeDef,
     DeleteAttendeeRequestRequestTypeDef,
     DeleteMeetingRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     GetAttendeeRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MediaPlacementTypeDef,
+    ResponseMetadataTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeRequestItemTypeDef,
     CreateAttendeeRequestRequestTypeDef,
     UpdateAttendeeCapabilitiesRequestRequestTypeDef,
     BatchUpdateAttendeeCapabilitiesExceptRequestRequestTypeDef,
     MeetingFeaturesConfigurationTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TranscriptionConfigurationTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/README.md` & `types-aiobotocore-chime-sdk-meetings-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-chime-sdk-meetings"></a>
 
 # types-aiobotocore-chime-sdk-meetings
 
 [![PyPI - types-aiobotocore-chime-sdk-meetings](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-meetings?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-meetings)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMeetings 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
+[aiobotocore.ChimeSDKMeetings 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
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
 [types-aiobotocore-chime-sdk-meetings docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,35 +273,35 @@
 
 ```python
 from types_aiobotocore_chime_sdk_meetings.type_defs import (
     AttendeeCapabilitiesTypeDef,
     AttendeeIdItemTypeDef,
     AudioFeaturesTypeDef,
     CreateAttendeeErrorTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsConfigurationTypeDef,
     TagTypeDef,
     DeleteAttendeeRequestRequestTypeDef,
     DeleteMeetingRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     GetAttendeeRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MediaPlacementTypeDef,
+    ResponseMetadataTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeRequestItemTypeDef,
     CreateAttendeeRequestRequestTypeDef,
     UpdateAttendeeCapabilitiesRequestRequestTypeDef,
     BatchUpdateAttendeeCapabilitiesExceptRequestRequestTypeDef,
     MeetingFeaturesConfigurationTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TranscriptionConfigurationTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
@@ -324,43 +324,43 @@
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/setup.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-chime-sdk-meetings.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-chime-sdk-meetings",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_chime_sdk_meetings"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ChimeSDKMeetings 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ChimeSDKMeetings 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/"
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__init__.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__init__.pyi` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/__main__.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ChimeSDKMeetings 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ChimeSDKMeetings 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings\nOther"
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/client.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -285,15 +285,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/client/#untag_resource)
         """
 
     async def update_attendee_capabilities(
         self, *, MeetingId: str, AttendeeId: str, Capabilities: AttendeeCapabilitiesTypeDef
     ) -> UpdateAttendeeCapabilitiesResponseTypeDef:
         """
-        The capabilties that you want to update.
+        The capabilities that you want to update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.update_attendee_capabilities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/client/#update_attendee_capabilities)
         """
 
     async def __aenter__(self) -> "ChimeSDKMeetingsClient":
         """
```

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/client.pyi` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -263,15 +263,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/client/#untag_resource)
         """
     async def update_attendee_capabilities(
         self, *, MeetingId: str, AttendeeId: str, Capabilities: AttendeeCapabilitiesTypeDef
     ) -> UpdateAttendeeCapabilitiesResponseTypeDef:
         """
-        The capabilties that you want to update.
+        The capabilities that you want to update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client.update_attendee_capabilities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/client/#update_attendee_capabilities)
         """
     async def __aenter__(self) -> "ChimeSDKMeetingsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings.Client)
```

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/literals.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -48,18 +48,20 @@
     "de-DE",
     "en-AU",
     "en-GB",
     "en-US",
     "es-US",
     "fr-CA",
     "fr-FR",
+    "hi-IN",
     "it-IT",
     "ja-JP",
     "ko-KR",
     "pt-BR",
+    "th-TH",
     "zh-CN",
 ]
 TranscribeMedicalContentIdentificationTypeType = Literal["PHI"]
 TranscribeMedicalLanguageCodeType = Literal["en-US"]
 TranscribeMedicalRegionType = Literal[
     "ap-southeast-2", "auto", "ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"
 ]
@@ -143,14 +145,15 @@
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
@@ -229,14 +232,15 @@
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
@@ -247,14 +251,15 @@
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
@@ -290,14 +295,15 @@
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
@@ -316,16 +322,19 @@
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
@@ -409,15 +418,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/literals.pyi` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -46,18 +46,20 @@
     "de-DE",
     "en-AU",
     "en-GB",
     "en-US",
     "es-US",
     "fr-CA",
     "fr-FR",
+    "hi-IN",
     "it-IT",
     "ja-JP",
     "ko-KR",
     "pt-BR",
+    "th-TH",
     "zh-CN",
 ]
 TranscribeMedicalContentIdentificationTypeType = Literal["PHI"]
 TranscribeMedicalLanguageCodeType = Literal["en-US"]
 TranscribeMedicalRegionType = Literal[
     "ap-southeast-2", "auto", "ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"
 ]
@@ -141,14 +143,15 @@
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
@@ -227,14 +230,15 @@
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
@@ -245,14 +249,15 @@
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
@@ -288,14 +293,15 @@
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
@@ -314,16 +320,19 @@
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
@@ -407,15 +416,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/type_defs.py` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -37,35 +37,35 @@
 
 
 __all__ = (
     "AttendeeCapabilitiesTypeDef",
     "AttendeeIdItemTypeDef",
     "AudioFeaturesTypeDef",
     "CreateAttendeeErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "NotificationsConfigurationTypeDef",
     "TagTypeDef",
     "DeleteAttendeeRequestRequestTypeDef",
     "DeleteMeetingRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EngineTranscribeMedicalSettingsTypeDef",
     "EngineTranscribeSettingsTypeDef",
     "GetAttendeeRequestRequestTypeDef",
     "GetMeetingRequestRequestTypeDef",
     "ListAttendeesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MediaPlacementTypeDef",
+    "ResponseMetadataTypeDef",
     "StopMeetingTranscriptionRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AttendeeTypeDef",
     "CreateAttendeeRequestItemTypeDef",
     "CreateAttendeeRequestRequestTypeDef",
     "UpdateAttendeeCapabilitiesRequestRequestTypeDef",
     "BatchUpdateAttendeeCapabilitiesExceptRequestRequestTypeDef",
     "MeetingFeaturesConfigurationTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TranscriptionConfigurationTypeDef",
     "BatchCreateAttendeeResponseTypeDef",
     "CreateAttendeeResponseTypeDef",
     "GetAttendeeResponseTypeDef",
     "ListAttendeesResponseTypeDef",
@@ -110,25 +110,14 @@
         "ExternalUserId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 NotificationsConfigurationTypeDef = TypedDict(
     "NotificationsConfigurationTypeDef",
     {
         "LambdaFunctionArn": str,
         "SnsTopicArn": str,
         "SqsQueueArn": str,
     },
@@ -154,14 +143,21 @@
 DeleteMeetingRequestRequestTypeDef = TypedDict(
     "DeleteMeetingRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEngineTranscribeMedicalSettingsTypeDef = TypedDict(
     "_RequiredEngineTranscribeMedicalSettingsTypeDef",
     {
         "LanguageCode": Literal["en-US"],
         "Specialty": TranscribeMedicalSpecialtyType,
         "Type": TranscribeMedicalTypeType,
     },
@@ -196,14 +192,16 @@
         "ContentIdentificationType": Literal["PII"],
         "ContentRedactionType": Literal["PII"],
         "PiiEntityTypes": str,
         "LanguageModelName": str,
         "IdentifyLanguage": bool,
         "LanguageOptions": str,
         "PreferredLanguage": TranscribeLanguageCodeType,
+        "VocabularyNames": str,
+        "VocabularyFilterNames": str,
     },
     total=False,
 )
 
 GetAttendeeRequestRequestTypeDef = TypedDict(
     "GetAttendeeRequestRequestTypeDef",
     {
@@ -259,14 +257,25 @@
         "ScreenViewingUrl": str,
         "ScreenSharingUrl": str,
         "EventIngestionUrl": str,
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
 StopMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StopMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
@@ -354,26 +363,19 @@
     "MeetingFeaturesConfigurationTypeDef",
     {
         "Audio": AudioFeaturesTypeDef,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
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
@@ -391,48 +393,48 @@
 )
 
 BatchCreateAttendeeResponseTypeDef = TypedDict(
     "BatchCreateAttendeeResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttendeeResponseTypeDef = TypedDict(
     "CreateAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAttendeeResponseTypeDef = TypedDict(
     "GetAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttendeesResponseTypeDef = TypedDict(
     "ListAttendeesResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAttendeeCapabilitiesResponseTypeDef = TypedDict(
     "UpdateAttendeeCapabilitiesResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateAttendeeRequestRequestTypeDef = TypedDict(
     "BatchCreateAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -522,28 +524,28 @@
     },
 )
 
 CreateMeetingResponseTypeDef = TypedDict(
     "CreateMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMeetingWithAttendeesResponseTypeDef = TypedDict(
     "CreateMeetingWithAttendeesResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMeetingResponseTypeDef = TypedDict(
     "GetMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings/type_defs.pyi` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -36,35 +36,35 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AttendeeCapabilitiesTypeDef",
     "AttendeeIdItemTypeDef",
     "AudioFeaturesTypeDef",
     "CreateAttendeeErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "NotificationsConfigurationTypeDef",
     "TagTypeDef",
     "DeleteAttendeeRequestRequestTypeDef",
     "DeleteMeetingRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EngineTranscribeMedicalSettingsTypeDef",
     "EngineTranscribeSettingsTypeDef",
     "GetAttendeeRequestRequestTypeDef",
     "GetMeetingRequestRequestTypeDef",
     "ListAttendeesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MediaPlacementTypeDef",
+    "ResponseMetadataTypeDef",
     "StopMeetingTranscriptionRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AttendeeTypeDef",
     "CreateAttendeeRequestItemTypeDef",
     "CreateAttendeeRequestRequestTypeDef",
     "UpdateAttendeeCapabilitiesRequestRequestTypeDef",
     "BatchUpdateAttendeeCapabilitiesExceptRequestRequestTypeDef",
     "MeetingFeaturesConfigurationTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TranscriptionConfigurationTypeDef",
     "BatchCreateAttendeeResponseTypeDef",
     "CreateAttendeeResponseTypeDef",
     "GetAttendeeResponseTypeDef",
     "ListAttendeesResponseTypeDef",
@@ -109,25 +109,14 @@
         "ExternalUserId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 NotificationsConfigurationTypeDef = TypedDict(
     "NotificationsConfigurationTypeDef",
     {
         "LambdaFunctionArn": str,
         "SnsTopicArn": str,
         "SqsQueueArn": str,
     },
@@ -153,14 +142,21 @@
 DeleteMeetingRequestRequestTypeDef = TypedDict(
     "DeleteMeetingRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEngineTranscribeMedicalSettingsTypeDef = TypedDict(
     "_RequiredEngineTranscribeMedicalSettingsTypeDef",
     {
         "LanguageCode": Literal["en-US"],
         "Specialty": TranscribeMedicalSpecialtyType,
         "Type": TranscribeMedicalTypeType,
     },
@@ -193,14 +189,16 @@
         "ContentIdentificationType": Literal["PII"],
         "ContentRedactionType": Literal["PII"],
         "PiiEntityTypes": str,
         "LanguageModelName": str,
         "IdentifyLanguage": bool,
         "LanguageOptions": str,
         "PreferredLanguage": TranscribeLanguageCodeType,
+        "VocabularyNames": str,
+        "VocabularyFilterNames": str,
     },
     total=False,
 )
 
 GetAttendeeRequestRequestTypeDef = TypedDict(
     "GetAttendeeRequestRequestTypeDef",
     {
@@ -254,14 +252,25 @@
         "ScreenViewingUrl": str,
         "ScreenSharingUrl": str,
         "EventIngestionUrl": str,
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
 StopMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StopMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
@@ -345,26 +354,19 @@
     "MeetingFeaturesConfigurationTypeDef",
     {
         "Audio": AudioFeaturesTypeDef,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
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
@@ -382,48 +384,48 @@
 )
 
 BatchCreateAttendeeResponseTypeDef = TypedDict(
     "BatchCreateAttendeeResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttendeeResponseTypeDef = TypedDict(
     "CreateAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAttendeeResponseTypeDef = TypedDict(
     "GetAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttendeesResponseTypeDef = TypedDict(
     "ListAttendeesResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAttendeeCapabilitiesResponseTypeDef = TypedDict(
     "UpdateAttendeeCapabilitiesResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateAttendeeRequestRequestTypeDef = TypedDict(
     "BatchCreateAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -509,28 +511,28 @@
     },
 )
 
 CreateMeetingResponseTypeDef = TypedDict(
     "CreateMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMeetingWithAttendeesResponseTypeDef = TypedDict(
     "CreateMeetingWithAttendeesResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMeetingResponseTypeDef = TypedDict(
     "GetMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/PKG-INFO` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime-sdk-meetings
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKMeetings 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKMeetings 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime-sdk-meetings"></a>
 
 # types-aiobotocore-chime-sdk-meetings
 
 [![PyPI - types-aiobotocore-chime-sdk-meetings](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-meetings.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-meetings)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-meetings?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-meetings)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMeetings 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
+[aiobotocore.ChimeSDKMeetings 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-meetings.html#ChimeSDKMeetings)
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
 [types-aiobotocore-chime-sdk-meetings docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_meetings/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,35 +306,35 @@
 
 ```python
 from types_aiobotocore_chime_sdk_meetings.type_defs import (
     AttendeeCapabilitiesTypeDef,
     AttendeeIdItemTypeDef,
     AudioFeaturesTypeDef,
     CreateAttendeeErrorTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsConfigurationTypeDef,
     TagTypeDef,
     DeleteAttendeeRequestRequestTypeDef,
     DeleteMeetingRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     GetAttendeeRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MediaPlacementTypeDef,
+    ResponseMetadataTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeRequestItemTypeDef,
     CreateAttendeeRequestRequestTypeDef,
     UpdateAttendeeCapabilitiesRequestRequestTypeDef,
     BatchUpdateAttendeeCapabilitiesExceptRequestRequestTypeDef,
     MeetingFeaturesConfigurationTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TranscriptionConfigurationTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-chime-sdk-meetings-2.5.0.post1/types_aiobotocore_chime_sdk_meetings.egg-info/SOURCES.txt` & `types-aiobotocore-chime-sdk-meetings-2.5.1/types_aiobotocore_chime_sdk_meetings.egg-info/SOURCES.txt`

 * *Files identical despite different names*

