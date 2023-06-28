# Comparing `tmp/types-aiobotocore-mediatailor-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediatailor-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediatailor-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:59 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediatailor-2.5.1.tar", last modified: Wed Jun 28 01:43:51 2023, max compression
```

## Comparing `types-aiobotocore-mediatailor-2.5.0.post1.tar` & `types-aiobotocore-mediatailor-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.531425 types-aiobotocore-mediatailor-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19677 2023-03-11 12:26:59.531425 types-aiobotocore-mediatailor-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18090 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:59.531425 types-aiobotocore-mediatailor-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.531425 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/
--rw-r--r--   0 runner    (1001) docker     (123)     2183 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2182 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35826 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35765 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9496 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9494 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10263 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10252 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    51819 2023-03-11 12:18:38.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    51754 2023-03-11 12:18:38.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:37.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.531425 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19677 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      889 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:59.000000 types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.666178 types-aiobotocore-mediatailor-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19693 2023-06-28 01:43:51.666178 types-aiobotocore-mediatailor-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18112 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.666178 types-aiobotocore-mediatailor-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:35:21.000000 types-aiobotocore-mediatailor-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.662178 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/
+-rw-r--r--   0 runner    (1001) docker     (123)     2183 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2182 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35826 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35765 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9807 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9805 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10159 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10149 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    51957 2023-06-28 01:35:23.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51892 2023-06-28 01:35:23.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:22.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.666178 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19693 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      889 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:51.000000 types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/LICENSE` & `types-aiobotocore-mediatailor-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediatailor-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediatailor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaTailor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaTailor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediatailor"></a>
 
 # types-aiobotocore-mediatailor
 
 [![PyPI - types-aiobotocore-mediatailor](https://img.shields.io/pypi/v/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediatailor?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediatailor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaTailor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
+[aiobotocore.MediaTailor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
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
 [types-aiobotocore-mediatailor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,14 +320,15 @@
 `types_aiobotocore_mediatailor.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediatailor.literals import (
     AccessTypeType,
     ChannelStateType,
+    FillPolicyType,
     GetChannelSchedulePaginatorName,
     ListAlertsPaginatorName,
     ListChannelsPaginatorName,
     ListLiveSourcesPaginatorName,
     ListPlaybackConfigurationsPaginatorName,
     ListPrefetchSchedulesPaginatorName,
     ListSourceLocationsPaginatorName,
@@ -371,16 +372,17 @@
     AvailMatchingCriteriaTypeDef,
     AvailSuppressionTypeDef,
     BumperTypeDef,
     CdnConfigurationTypeDef,
     LogConfigurationForChannelTypeDef,
     ClipRangeTypeDef,
     ConfigureLogsForChannelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ConfigureLogsForChannelResponseTypeDef,
     ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef,
+    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
     HttpPackageConfigurationTypeDef,
     PrefetchRetrievalTypeDef,
     DefaultSegmentDeliveryConfigurationTypeDef,
     HttpConfigurationTypeDef,
     SegmentDeliveryConfigurationTypeDef,
     DashConfigurationForPutTypeDef,
     DashConfigurationTypeDef,
@@ -394,69 +396,68 @@
     DeleteSourceLocationRequestRequestTypeDef,
     DeleteVodSourceRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeLiveSourceRequestRequestTypeDef,
     DescribeProgramRequestRequestTypeDef,
     DescribeSourceLocationRequestRequestTypeDef,
     DescribeVodSourceRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetChannelPolicyResponseTypeDef,
+    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
     GetChannelScheduleRequestRequestTypeDef,
     GetPlaybackConfigurationRequestRequestTypeDef,
     HlsConfigurationTypeDef,
     LivePreRollConfigurationTypeDef,
     LogConfigurationTypeDef,
     GetPrefetchScheduleRequestRequestTypeDef,
     HlsPlaylistSettingsTypeDef,
+    ListAlertsRequestListAlertsPaginateTypeDef,
     ListAlertsRequestRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
     ListLiveSourcesRequestRequestTypeDef,
+    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
     ListPlaybackConfigurationsRequestRequestTypeDef,
+    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
     ListPrefetchSchedulesRequestRequestTypeDef,
+    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
     ListSourceLocationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     ListVodSourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutChannelPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ScheduleAdBreakTypeDef,
     TransitionTypeDef,
     SegmentationDescriptorTypeDef,
     StartChannelRequestRequestTypeDef,
     StopChannelRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProgramTransitionTypeDef,
     AccessConfigurationTypeDef,
     ManifestProcessingRulesTypeDef,
-    PrefetchConsumptionTypeDef,
-    ConfigureLogsForChannelResponseTypeDef,
-    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChannelPolicyResponseTypeDef,
     ListAlertsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PrefetchConsumptionTypeDef,
     CreateLiveSourceRequestRequestTypeDef,
     CreateLiveSourceResponseTypeDef,
     CreateVodSourceRequestRequestTypeDef,
     CreateVodSourceResponseTypeDef,
     DescribeLiveSourceResponseTypeDef,
     DescribeVodSourceResponseTypeDef,
     LiveSourceTypeDef,
     UpdateLiveSourceRequestRequestTypeDef,
     UpdateLiveSourceResponseTypeDef,
     UpdateVodSourceRequestRequestTypeDef,
     UpdateVodSourceResponseTypeDef,
     VodSourceTypeDef,
-    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-    ListAlertsRequestListAlertsPaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
-    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
-    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     RequestOutputItemTypeDef,
     ResponseOutputItemTypeDef,
     ScheduleEntryTypeDef,
     ScheduleConfigurationTypeDef,
     TimeSignalMessageTypeDef,
     UpdateProgramScheduleConfigurationTypeDef,
     CreateSourceLocationRequestRequestTypeDef,
@@ -502,43 +503,43 @@
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/README.md` & `types-aiobotocore-mediatailor-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediatailor"></a>
 
 # types-aiobotocore-mediatailor
 
 [![PyPI - types-aiobotocore-mediatailor](https://img.shields.io/pypi/v/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediatailor?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediatailor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaTailor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
+[aiobotocore.MediaTailor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
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
 [types-aiobotocore-mediatailor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,14 +287,15 @@
 `types_aiobotocore_mediatailor.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediatailor.literals import (
     AccessTypeType,
     ChannelStateType,
+    FillPolicyType,
     GetChannelSchedulePaginatorName,
     ListAlertsPaginatorName,
     ListChannelsPaginatorName,
     ListLiveSourcesPaginatorName,
     ListPlaybackConfigurationsPaginatorName,
     ListPrefetchSchedulesPaginatorName,
     ListSourceLocationsPaginatorName,
@@ -338,16 +339,17 @@
     AvailMatchingCriteriaTypeDef,
     AvailSuppressionTypeDef,
     BumperTypeDef,
     CdnConfigurationTypeDef,
     LogConfigurationForChannelTypeDef,
     ClipRangeTypeDef,
     ConfigureLogsForChannelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ConfigureLogsForChannelResponseTypeDef,
     ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef,
+    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
     HttpPackageConfigurationTypeDef,
     PrefetchRetrievalTypeDef,
     DefaultSegmentDeliveryConfigurationTypeDef,
     HttpConfigurationTypeDef,
     SegmentDeliveryConfigurationTypeDef,
     DashConfigurationForPutTypeDef,
     DashConfigurationTypeDef,
@@ -361,69 +363,68 @@
     DeleteSourceLocationRequestRequestTypeDef,
     DeleteVodSourceRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeLiveSourceRequestRequestTypeDef,
     DescribeProgramRequestRequestTypeDef,
     DescribeSourceLocationRequestRequestTypeDef,
     DescribeVodSourceRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetChannelPolicyResponseTypeDef,
+    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
     GetChannelScheduleRequestRequestTypeDef,
     GetPlaybackConfigurationRequestRequestTypeDef,
     HlsConfigurationTypeDef,
     LivePreRollConfigurationTypeDef,
     LogConfigurationTypeDef,
     GetPrefetchScheduleRequestRequestTypeDef,
     HlsPlaylistSettingsTypeDef,
+    ListAlertsRequestListAlertsPaginateTypeDef,
     ListAlertsRequestRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
     ListLiveSourcesRequestRequestTypeDef,
+    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
     ListPlaybackConfigurationsRequestRequestTypeDef,
+    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
     ListPrefetchSchedulesRequestRequestTypeDef,
+    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
     ListSourceLocationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     ListVodSourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutChannelPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ScheduleAdBreakTypeDef,
     TransitionTypeDef,
     SegmentationDescriptorTypeDef,
     StartChannelRequestRequestTypeDef,
     StopChannelRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProgramTransitionTypeDef,
     AccessConfigurationTypeDef,
     ManifestProcessingRulesTypeDef,
-    PrefetchConsumptionTypeDef,
-    ConfigureLogsForChannelResponseTypeDef,
-    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChannelPolicyResponseTypeDef,
     ListAlertsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PrefetchConsumptionTypeDef,
     CreateLiveSourceRequestRequestTypeDef,
     CreateLiveSourceResponseTypeDef,
     CreateVodSourceRequestRequestTypeDef,
     CreateVodSourceResponseTypeDef,
     DescribeLiveSourceResponseTypeDef,
     DescribeVodSourceResponseTypeDef,
     LiveSourceTypeDef,
     UpdateLiveSourceRequestRequestTypeDef,
     UpdateLiveSourceResponseTypeDef,
     UpdateVodSourceRequestRequestTypeDef,
     UpdateVodSourceResponseTypeDef,
     VodSourceTypeDef,
-    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-    ListAlertsRequestListAlertsPaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
-    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
-    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     RequestOutputItemTypeDef,
     ResponseOutputItemTypeDef,
     ScheduleEntryTypeDef,
     ScheduleConfigurationTypeDef,
     TimeSignalMessageTypeDef,
     UpdateProgramScheduleConfigurationTypeDef,
     CreateSourceLocationRequestRequestTypeDef,
@@ -469,43 +470,43 @@
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/setup.py` & `types-aiobotocore-mediatailor-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediatailor.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediatailor",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediatailor"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaTailor 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaTailor 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/"
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__init__.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__init__.pyi` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/__main__.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaTailor 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaTailor 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor\nOther"
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/client.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/client.pyi` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/literals.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AccessTypeType",
     "ChannelStateType",
+    "FillPolicyType",
     "GetChannelSchedulePaginatorName",
     "ListAlertsPaginatorName",
     "ListChannelsPaginatorName",
     "ListLiveSourcesPaginatorName",
     "ListPlaybackConfigurationsPaginatorName",
     "ListPrefetchSchedulesPaginatorName",
     "ListSourceLocationsPaginatorName",
@@ -46,25 +47,26 @@
     "PaginatorName",
     "RegionName",
 )
 
 
 AccessTypeType = Literal["S3_SIGV4", "SECRETS_MANAGER_ACCESS_TOKEN"]
 ChannelStateType = Literal["RUNNING", "STOPPED"]
+FillPolicyType = Literal["FULL_AVAIL_ONLY", "PARTIAL_AVAIL"]
 GetChannelSchedulePaginatorName = Literal["get_channel_schedule"]
 ListAlertsPaginatorName = Literal["list_alerts"]
 ListChannelsPaginatorName = Literal["list_channels"]
 ListLiveSourcesPaginatorName = Literal["list_live_sources"]
 ListPlaybackConfigurationsPaginatorName = Literal["list_playback_configurations"]
 ListPrefetchSchedulesPaginatorName = Literal["list_prefetch_schedules"]
 ListSourceLocationsPaginatorName = Literal["list_source_locations"]
 ListVodSourcesPaginatorName = Literal["list_vod_sources"]
 LogTypeType = Literal["AS_RUN"]
 MessageTypeType = Literal["SPLICE_INSERT", "TIME_SIGNAL"]
-ModeType = Literal["BEHIND_LIVE_EDGE", "OFF"]
+ModeType = Literal["AFTER_LIVE_EDGE", "BEHIND_LIVE_EDGE", "OFF"]
 OperatorType = Literal["EQUALS"]
 OriginManifestTypeType = Literal["MULTI_PERIOD", "SINGLE_PERIOD"]
 PlaybackModeType = Literal["LINEAR", "LOOP"]
 RelativePositionType = Literal["AFTER_PROGRAM", "BEFORE_PROGRAM"]
 ScheduleEntryTypeType = Literal["FILLER_SLATE", "PROGRAM"]
 TierType = Literal["BASIC", "STANDARD"]
 TypeType = Literal["DASH", "HLS"]
@@ -127,14 +129,15 @@
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
@@ -213,14 +216,15 @@
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
@@ -231,14 +235,15 @@
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
@@ -274,14 +279,15 @@
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
@@ -300,16 +306,19 @@
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
@@ -393,15 +402,17 @@
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/literals.pyi` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -17,14 +17,15 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AccessTypeType",
     "ChannelStateType",
+    "FillPolicyType",
     "GetChannelSchedulePaginatorName",
     "ListAlertsPaginatorName",
     "ListChannelsPaginatorName",
     "ListLiveSourcesPaginatorName",
     "ListPlaybackConfigurationsPaginatorName",
     "ListPrefetchSchedulesPaginatorName",
     "ListSourceLocationsPaginatorName",
@@ -44,25 +45,26 @@
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AccessTypeType = Literal["S3_SIGV4", "SECRETS_MANAGER_ACCESS_TOKEN"]
 ChannelStateType = Literal["RUNNING", "STOPPED"]
+FillPolicyType = Literal["FULL_AVAIL_ONLY", "PARTIAL_AVAIL"]
 GetChannelSchedulePaginatorName = Literal["get_channel_schedule"]
 ListAlertsPaginatorName = Literal["list_alerts"]
 ListChannelsPaginatorName = Literal["list_channels"]
 ListLiveSourcesPaginatorName = Literal["list_live_sources"]
 ListPlaybackConfigurationsPaginatorName = Literal["list_playback_configurations"]
 ListPrefetchSchedulesPaginatorName = Literal["list_prefetch_schedules"]
 ListSourceLocationsPaginatorName = Literal["list_source_locations"]
 ListVodSourcesPaginatorName = Literal["list_vod_sources"]
 LogTypeType = Literal["AS_RUN"]
 MessageTypeType = Literal["SPLICE_INSERT", "TIME_SIGNAL"]
-ModeType = Literal["BEHIND_LIVE_EDGE", "OFF"]
+ModeType = Literal["AFTER_LIVE_EDGE", "BEHIND_LIVE_EDGE", "OFF"]
 OperatorType = Literal["EQUALS"]
 OriginManifestTypeType = Literal["MULTI_PERIOD", "SINGLE_PERIOD"]
 PlaybackModeType = Literal["LINEAR", "LOOP"]
 RelativePositionType = Literal["AFTER_PROGRAM", "BEFORE_PROGRAM"]
 ScheduleEntryTypeType = Literal["FILLER_SLATE", "PROGRAM"]
 TierType = Literal["BASIC", "STANDARD"]
 TypeType = Literal["DASH", "HLS"]
@@ -125,14 +127,15 @@
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
@@ -211,14 +214,15 @@
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
@@ -229,14 +233,15 @@
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
@@ -272,14 +277,15 @@
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
@@ -298,16 +304,19 @@
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
@@ -391,15 +400,17 @@
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/paginator.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_live_sources_paginator: ListLiveSourcesPaginator = client.get_paginator("list_live_sources")
         list_playback_configurations_paginator: ListPlaybackConfigurationsPaginator = client.get_paginator("list_playback_configurations")
         list_prefetch_schedules_paginator: ListPrefetchSchedulesPaginator = client.get_paginator("list_prefetch_schedules")
         list_source_locations_paginator: ListSourceLocationsPaginator = client.get_paginator("list_source_locations")
         list_vod_sources_paginator: ListVodSourcesPaginator = client.get_paginator("list_vod_sources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetChannelScheduleResponseTypeDef,
     ListAlertsResponseTypeDef,
@@ -48,20 +47,14 @@
     ListPlaybackConfigurationsResponseTypeDef,
     ListPrefetchSchedulesResponseTypeDef,
     ListSourceLocationsResponseTypeDef,
     ListVodSourcesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetChannelSchedulePaginator",
     "ListAlertsPaginator",
     "ListChannelsPaginator",
     "ListLiveSourcesPaginator",
     "ListPlaybackConfigurationsPaginator",
     "ListPrefetchSchedulesPaginator",
@@ -87,75 +80,75 @@
     """
 
     def paginate(
         self,
         *,
         ChannelName: str,
         DurationMinutes: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetChannelScheduleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.GetChannelSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#getchannelschedulepaginator)
         """
 
 
 class ListAlertsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListAlerts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listalertspaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAlertsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListAlerts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listalertspaginator)
         """
 
 
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listchannelspaginator)
         """
 
 
 class ListLiveSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListLiveSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listlivesourcespaginator)
     """
 
     def paginate(
-        self, *, SourceLocationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SourceLocationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLiveSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListLiveSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listlivesourcespaginator)
         """
 
 
 class ListPlaybackConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPlaybackConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listplaybackconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaybackConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPlaybackConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listplaybackconfigurationspaginator)
         """
 
 
@@ -166,43 +159,43 @@
     """
 
     def paginate(
         self,
         *,
         PlaybackConfigurationName: str,
         StreamId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrefetchSchedulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPrefetchSchedules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listprefetchschedulespaginator)
         """
 
 
 class ListSourceLocationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListSourceLocations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listsourcelocationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceLocationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListSourceLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listsourcelocationspaginator)
         """
 
 
 class ListVodSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListVodSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listvodsourcespaginator)
     """
 
     def paginate(
-        self, *, SourceLocationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SourceLocationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVodSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListVodSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listvodsourcespaginator)
         """
```

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/paginator.pyi` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_live_sources_paginator: ListLiveSourcesPaginator = client.get_paginator("list_live_sources")
         list_playback_configurations_paginator: ListPlaybackConfigurationsPaginator = client.get_paginator("list_playback_configurations")
         list_prefetch_schedules_paginator: ListPrefetchSchedulesPaginator = client.get_paginator("list_prefetch_schedules")
         list_source_locations_paginator: ListSourceLocationsPaginator = client.get_paginator("list_source_locations")
         list_vod_sources_paginator: ListVodSourcesPaginator = client.get_paginator("list_vod_sources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetChannelScheduleResponseTypeDef,
     ListAlertsResponseTypeDef,
@@ -48,19 +47,14 @@
     ListPlaybackConfigurationsResponseTypeDef,
     ListPrefetchSchedulesResponseTypeDef,
     ListSourceLocationsResponseTypeDef,
     ListVodSourcesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetChannelSchedulePaginator",
     "ListAlertsPaginator",
     "ListChannelsPaginator",
     "ListLiveSourcesPaginator",
     "ListPlaybackConfigurationsPaginator",
     "ListPrefetchSchedulesPaginator",
@@ -83,71 +77,71 @@
     """
 
     def paginate(
         self,
         *,
         ChannelName: str,
         DurationMinutes: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetChannelScheduleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.GetChannelSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#getchannelschedulepaginator)
         """
 
 class ListAlertsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListAlerts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listalertspaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAlertsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListAlerts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listalertspaginator)
         """
 
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listchannelspaginator)
         """
 
 class ListLiveSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListLiveSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listlivesourcespaginator)
     """
 
     def paginate(
-        self, *, SourceLocationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SourceLocationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLiveSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListLiveSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listlivesourcespaginator)
         """
 
 class ListPlaybackConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPlaybackConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listplaybackconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaybackConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPlaybackConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listplaybackconfigurationspaginator)
         """
 
 class ListPrefetchSchedulesPaginator(AioPaginator):
@@ -157,41 +151,41 @@
     """
 
     def paginate(
         self,
         *,
         PlaybackConfigurationName: str,
         StreamId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrefetchSchedulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListPrefetchSchedules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listprefetchschedulespaginator)
         """
 
 class ListSourceLocationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListSourceLocations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listsourcelocationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceLocationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListSourceLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listsourcelocationspaginator)
         """
 
 class ListVodSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListVodSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listvodsourcespaginator)
     """
 
     def paginate(
-        self, *, SourceLocationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SourceLocationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVodSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor.Paginator.ListVodSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/paginators/#listvodsourcespaginator)
         """
```

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/type_defs.py` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AccessTypeType,
     ChannelStateType,
+    FillPolicyType,
     MessageTypeType,
     ModeType,
     OriginManifestTypeType,
     PlaybackModeType,
     RelativePositionType,
     ScheduleEntryTypeType,
     TierType,
@@ -47,16 +48,17 @@
     "AvailMatchingCriteriaTypeDef",
     "AvailSuppressionTypeDef",
     "BumperTypeDef",
     "CdnConfigurationTypeDef",
     "LogConfigurationForChannelTypeDef",
     "ClipRangeTypeDef",
     "ConfigureLogsForChannelRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ConfigureLogsForChannelResponseTypeDef",
     "ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef",
+    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
     "HttpPackageConfigurationTypeDef",
     "PrefetchRetrievalTypeDef",
     "DefaultSegmentDeliveryConfigurationTypeDef",
     "HttpConfigurationTypeDef",
     "SegmentDeliveryConfigurationTypeDef",
     "DashConfigurationForPutTypeDef",
     "DashConfigurationTypeDef",
@@ -70,69 +72,68 @@
     "DeleteSourceLocationRequestRequestTypeDef",
     "DeleteVodSourceRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeLiveSourceRequestRequestTypeDef",
     "DescribeProgramRequestRequestTypeDef",
     "DescribeSourceLocationRequestRequestTypeDef",
     "DescribeVodSourceRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelPolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetChannelPolicyResponseTypeDef",
+    "GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
     "GetChannelScheduleRequestRequestTypeDef",
     "GetPlaybackConfigurationRequestRequestTypeDef",
     "HlsConfigurationTypeDef",
     "LivePreRollConfigurationTypeDef",
     "LogConfigurationTypeDef",
     "GetPrefetchScheduleRequestRequestTypeDef",
     "HlsPlaylistSettingsTypeDef",
+    "ListAlertsRequestListAlertsPaginateTypeDef",
     "ListAlertsRequestRequestTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
     "ListLiveSourcesRequestRequestTypeDef",
+    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
     "ListPlaybackConfigurationsRequestRequestTypeDef",
+    "ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
     "ListPrefetchSchedulesRequestRequestTypeDef",
+    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
     "ListSourceLocationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListVodSourcesRequestListVodSourcesPaginateTypeDef",
     "ListVodSourcesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutChannelPolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ScheduleAdBreakTypeDef",
     "TransitionTypeDef",
     "SegmentationDescriptorTypeDef",
     "StartChannelRequestRequestTypeDef",
     "StopChannelRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateProgramTransitionTypeDef",
     "AccessConfigurationTypeDef",
     "ManifestProcessingRulesTypeDef",
-    "PrefetchConsumptionTypeDef",
-    "ConfigureLogsForChannelResponseTypeDef",
-    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetChannelPolicyResponseTypeDef",
     "ListAlertsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "PrefetchConsumptionTypeDef",
     "CreateLiveSourceRequestRequestTypeDef",
     "CreateLiveSourceResponseTypeDef",
     "CreateVodSourceRequestRequestTypeDef",
     "CreateVodSourceResponseTypeDef",
     "DescribeLiveSourceResponseTypeDef",
     "DescribeVodSourceResponseTypeDef",
     "LiveSourceTypeDef",
     "UpdateLiveSourceRequestRequestTypeDef",
     "UpdateLiveSourceResponseTypeDef",
     "UpdateVodSourceRequestRequestTypeDef",
     "UpdateVodSourceResponseTypeDef",
     "VodSourceTypeDef",
-    "GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    "ListAlertsRequestListAlertsPaginateTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
-    "ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
-    "ListVodSourcesRequestListVodSourcesPaginateTypeDef",
     "RequestOutputItemTypeDef",
     "ResponseOutputItemTypeDef",
     "ScheduleEntryTypeDef",
     "ScheduleConfigurationTypeDef",
     "TimeSignalMessageTypeDef",
     "UpdateProgramScheduleConfigurationTypeDef",
     "CreateSourceLocationRequestRequestTypeDef",
@@ -226,14 +227,15 @@
         "Operator": Literal["EQUALS"],
     },
 )
 
 AvailSuppressionTypeDef = TypedDict(
     "AvailSuppressionTypeDef",
     {
+        "FillPolicy": FillPolicyType,
         "Mode": ModeType,
         "Value": str,
     },
     total=False,
 )
 
 BumperTypeDef = TypedDict(
@@ -273,33 +275,40 @@
     "ConfigureLogsForChannelRequestRequestTypeDef",
     {
         "ChannelName": str,
         "LogTypes": Sequence[Literal["AS_RUN"]],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ConfigureLogsForChannelResponseTypeDef = TypedDict(
+    "ConfigureLogsForChannelResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChannelName": str,
+        "LogTypes": List[Literal["AS_RUN"]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef = TypedDict(
     "ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef",
     {
         "PercentEnabled": int,
         "PlaybackConfigurationName": str,
     },
 )
 
+ConfigureLogsForPlaybackConfigurationResponseTypeDef = TypedDict(
+    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
+    {
+        "PercentEnabled": int,
+        "PlaybackConfigurationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HttpPackageConfigurationTypeDef = TypedDict(
     "HttpPackageConfigurationTypeDef",
     {
         "Path": str,
         "SourceGroup": str,
         "Type": TypeType,
     },
@@ -475,31 +484,59 @@
     "DescribeVodSourceRequestRequestTypeDef",
     {
         "SourceLocationName": str,
         "VodSourceName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelPolicyRequestRequestTypeDef = TypedDict(
     "GetChannelPolicyRequestRequestTypeDef",
     {
         "ChannelName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetChannelPolicyResponseTypeDef = TypedDict(
+    "GetChannelPolicyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
+    "_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
+    {
+        "ChannelName": str,
+    },
+)
+_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
+    "_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
+    {
+        "DurationMinutes": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef(
+    _RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
+    _OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetChannelScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredGetChannelScheduleRequestRequestTypeDef",
     {
         "ChannelName": str,
     },
 )
 _OptionalGetChannelScheduleRequestRequestTypeDef = TypedDict(
@@ -563,14 +600,36 @@
     "HlsPlaylistSettingsTypeDef",
     {
         "ManifestWindowSeconds": int,
     },
     total=False,
 )
 
+_RequiredListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
+    "_RequiredListAlertsRequestListAlertsPaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
+    "_OptionalListAlertsRequestListAlertsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAlertsRequestListAlertsPaginateTypeDef(
+    _RequiredListAlertsRequestListAlertsPaginateTypeDef,
+    _OptionalListAlertsRequestListAlertsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAlertsRequestRequestTypeDef = TypedDict(
     "_RequiredListAlertsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListAlertsRequestRequestTypeDef = TypedDict(
@@ -585,23 +644,53 @@
 
 class ListAlertsRequestRequestTypeDef(
     _RequiredListAlertsRequestRequestTypeDef, _OptionalListAlertsRequestRequestTypeDef
 ):
     pass
 
 
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
+    {
+        "SourceLocationName": str,
+    },
+)
+_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLiveSourcesRequestListLiveSourcesPaginateTypeDef(
+    _RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
+    _OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLiveSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListLiveSourcesRequestRequestTypeDef",
     {
         "SourceLocationName": str,
     },
 )
 _OptionalListLiveSourcesRequestRequestTypeDef = TypedDict(
@@ -616,23 +705,54 @@
 
 class ListLiveSourcesRequestRequestTypeDef(
     _RequiredListLiveSourcesRequestRequestTypeDef, _OptionalListLiveSourcesRequestRequestTypeDef
 ):
     pass
 
 
+ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef = TypedDict(
+    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPlaybackConfigurationsRequestRequestTypeDef = TypedDict(
     "ListPlaybackConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
+    "_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
+    {
+        "PlaybackConfigurationName": str,
+    },
+)
+_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
+    "_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
+    {
+        "StreamId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef(
+    _RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
+    _OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPrefetchSchedulesRequestRequestTypeDef = TypedDict(
     "_RequiredListPrefetchSchedulesRequestRequestTypeDef",
     {
         "PlaybackConfigurationName": str,
     },
 )
 _OptionalListPrefetchSchedulesRequestRequestTypeDef = TypedDict(
@@ -649,14 +769,22 @@
 class ListPrefetchSchedulesRequestRequestTypeDef(
     _RequiredListPrefetchSchedulesRequestRequestTypeDef,
     _OptionalListPrefetchSchedulesRequestRequestTypeDef,
 ):
     pass
 
 
+ListSourceLocationsRequestListSourceLocationsPaginateTypeDef = TypedDict(
+    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSourceLocationsRequestRequestTypeDef = TypedDict(
     "ListSourceLocationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -665,14 +793,44 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef",
+    {
+        "SourceLocationName": str,
+    },
+)
+_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVodSourcesRequestListVodSourcesPaginateTypeDef(
+    _RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef,
+    _OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVodSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListVodSourcesRequestRequestTypeDef",
     {
         "SourceLocationName": str,
     },
 )
 _OptionalListVodSourcesRequestRequestTypeDef = TypedDict(
@@ -687,22 +845,43 @@
 
 class ListVodSourcesRequestRequestTypeDef(
     _RequiredListVodSourcesRequestRequestTypeDef, _OptionalListVodSourcesRequestRequestTypeDef
 ):
     pass
 
 
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
 PutChannelPolicyRequestRequestTypeDef = TypedDict(
     "PutChannelPolicyRequestRequestTypeDef",
     {
         "ChannelName": str,
         "Policy": str,
     },
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
 ScheduleAdBreakTypeDef = TypedDict(
     "ScheduleAdBreakTypeDef",
     {
         "ApproximateDurationSeconds": int,
         "ApproximateStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
@@ -799,14 +978,23 @@
     "ManifestProcessingRulesTypeDef",
     {
         "AdMarkerPassthrough": AdMarkerPassthroughTypeDef,
     },
     total=False,
 )
 
+ListAlertsResponseTypeDef = TypedDict(
+    "ListAlertsResponseTypeDef",
+    {
+        "Items": List[AlertTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPrefetchConsumptionTypeDef = TypedDict(
     "_RequiredPrefetchConsumptionTypeDef",
     {
         "EndTime": Union[datetime, str],
     },
 )
 _OptionalPrefetchConsumptionTypeDef = TypedDict(
@@ -821,64 +1009,14 @@
 
 class PrefetchConsumptionTypeDef(
     _RequiredPrefetchConsumptionTypeDef, _OptionalPrefetchConsumptionTypeDef
 ):
     pass
 
 
-ConfigureLogsForChannelResponseTypeDef = TypedDict(
-    "ConfigureLogsForChannelResponseTypeDef",
-    {
-        "ChannelName": str,
-        "LogTypes": List[Literal["AS_RUN"]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfigureLogsForPlaybackConfigurationResponseTypeDef = TypedDict(
-    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
-    {
-        "PercentEnabled": int,
-        "PlaybackConfigurationName": str,
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
-GetChannelPolicyResponseTypeDef = TypedDict(
-    "GetChannelPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlertsResponseTypeDef = TypedDict(
-    "ListAlertsResponseTypeDef",
-    {
-        "Items": List[AlertTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateLiveSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLiveSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
         "LiveSourceName": str,
         "SourceLocationName": str,
     },
@@ -904,15 +1042,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateVodSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVodSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
@@ -941,43 +1079,43 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLiveSourceResponseTypeDef = TypedDict(
     "DescribeLiveSourceResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVodSourceResponseTypeDef = TypedDict(
     "DescribeVodSourceResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLiveSourceTypeDef = TypedDict(
     "_RequiredLiveSourceTypeDef",
     {
         "Arn": str,
@@ -1016,15 +1154,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVodSourceRequestRequestTypeDef = TypedDict(
     "UpdateVodSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
@@ -1039,15 +1177,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVodSourceTypeDef = TypedDict(
     "_RequiredVodSourceTypeDef",
     {
         "Arn": str,
@@ -1067,150 +1205,14 @@
 )
 
 
 class VodSourceTypeDef(_RequiredVodSourceTypeDef, _OptionalVodSourceTypeDef):
     pass
 
 
-_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
-    "_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    {
-        "ChannelName": str,
-    },
-)
-_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
-    "_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    {
-        "DurationMinutes": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef(
-    _RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-    _OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
-    "_RequiredListAlertsRequestListAlertsPaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
-    "_OptionalListAlertsRequestListAlertsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAlertsRequestListAlertsPaginateTypeDef(
-    _RequiredListAlertsRequestListAlertsPaginateTypeDef,
-    _OptionalListAlertsRequestListAlertsPaginateTypeDef,
-):
-    pass
-
-
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    {
-        "SourceLocationName": str,
-    },
-)
-_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLiveSourcesRequestListLiveSourcesPaginateTypeDef(
-    _RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-    _OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-):
-    pass
-
-
-ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef = TypedDict(
-    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
-    "_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    {
-        "PlaybackConfigurationName": str,
-    },
-)
-_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
-    "_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    {
-        "StreamId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef(
-    _RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-    _OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-):
-    pass
-
-
-ListSourceLocationsRequestListSourceLocationsPaginateTypeDef = TypedDict(
-    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef",
-    {
-        "SourceLocationName": str,
-    },
-)
-_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVodSourcesRequestListVodSourcesPaginateTypeDef(
-    _RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef,
-    _OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef,
-):
-    pass
-
-
 _RequiredRequestOutputItemTypeDef = TypedDict(
     "_RequiredRequestOutputItemTypeDef",
     {
         "ManifestName": str,
         "SourceGroup": str,
     },
 )
@@ -1353,15 +1355,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceLocationResponseTypeDef = TypedDict(
     "DescribeSourceLocationResponseTypeDef",
     {
         "AccessConfiguration": AccessConfigurationTypeDef,
@@ -1369,15 +1371,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSourceLocationTypeDef = TypedDict(
     "_RequiredSourceLocationTypeDef",
     {
         "Arn": str,
@@ -1436,15 +1438,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPlaybackConfigurationResponseTypeDef = TypedDict(
     "GetPlaybackConfigurationResponseTypeDef",
     {
         "AdDecisionServerUrl": str,
@@ -1462,15 +1464,15 @@
         "PlaybackConfigurationArn": str,
         "PlaybackEndpointPrefix": str,
         "SessionInitializationEndpointPrefix": str,
         "SlateAdUrl": str,
         "Tags": Dict[str, str],
         "TranscodeProfileName": str,
         "VideoContentSourceUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PlaybackConfigurationTypeDef = TypedDict(
     "PlaybackConfigurationTypeDef",
     {
         "AdDecisionServerUrl": str,
@@ -1548,15 +1550,15 @@
         "PlaybackConfigurationArn": str,
         "PlaybackEndpointPrefix": str,
         "SessionInitializationEndpointPrefix": str,
         "SlateAdUrl": str,
         "Tags": Dict[str, str],
         "TranscodeProfileName": str,
         "VideoContentSourceUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePrefetchScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePrefetchScheduleRequestRequestTypeDef",
     {
         "Consumption": PrefetchConsumptionTypeDef,
@@ -1586,28 +1588,28 @@
     {
         "Arn": str,
         "Consumption": PrefetchConsumptionTypeDef,
         "Name": str,
         "PlaybackConfigurationName": str,
         "Retrieval": PrefetchRetrievalTypeDef,
         "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPrefetchScheduleResponseTypeDef = TypedDict(
     "GetPrefetchScheduleResponseTypeDef",
     {
         "Arn": str,
         "Consumption": PrefetchConsumptionTypeDef,
         "Name": str,
         "PlaybackConfigurationName": str,
         "Retrieval": PrefetchRetrievalTypeDef,
         "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPrefetchScheduleTypeDef = TypedDict(
     "_RequiredPrefetchScheduleTypeDef",
     {
         "Arn": str,
@@ -1631,24 +1633,24 @@
 
 
 ListLiveSourcesResponseTypeDef = TypedDict(
     "ListLiveSourcesResponseTypeDef",
     {
         "Items": List[LiveSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVodSourcesResponseTypeDef = TypedDict(
     "ListVodSourcesResponseTypeDef",
     {
         "Items": List[VodSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1732,15 +1734,15 @@
         "CreationTime": datetime,
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
@@ -1750,15 +1752,15 @@
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "LogConfiguration": LogConfigurationForChannelTypeDef,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Arn": str,
@@ -1767,24 +1769,24 @@
         "CreationTime": datetime,
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelScheduleResponseTypeDef = TypedDict(
     "GetChannelScheduleResponseTypeDef",
     {
         "Items": List[ScheduleEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdBreakTypeDef = TypedDict(
     "AdBreakTypeDef",
     {
         "MessageType": MessageTypeType,
@@ -1797,42 +1799,42 @@
 )
 
 ListSourceLocationsResponseTypeDef = TypedDict(
     "ListSourceLocationsResponseTypeDef",
     {
         "Items": List[SourceLocationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlaybackConfigurationsResponseTypeDef = TypedDict(
     "ListPlaybackConfigurationsResponseTypeDef",
     {
         "Items": List[PlaybackConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPrefetchSchedulesResponseTypeDef = TypedDict(
     "ListPrefetchSchedulesResponseTypeDef",
     {
         "Items": List[PrefetchScheduleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Items": List[ChannelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProgramRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProgramRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1868,15 +1870,15 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProgramResponseTypeDef = TypedDict(
     "DescribeProgramResponseTypeDef",
     {
         "AdBreaks": List[AdBreakTypeDef],
@@ -1886,15 +1888,15 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateProgramRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProgramRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1927,10 +1929,10 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor/type_defs.pyi` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AccessTypeType,
     ChannelStateType,
+    FillPolicyType,
     MessageTypeType,
     ModeType,
     OriginManifestTypeType,
     PlaybackModeType,
     RelativePositionType,
     ScheduleEntryTypeType,
     TierType,
@@ -46,16 +47,17 @@
     "AvailMatchingCriteriaTypeDef",
     "AvailSuppressionTypeDef",
     "BumperTypeDef",
     "CdnConfigurationTypeDef",
     "LogConfigurationForChannelTypeDef",
     "ClipRangeTypeDef",
     "ConfigureLogsForChannelRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ConfigureLogsForChannelResponseTypeDef",
     "ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef",
+    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
     "HttpPackageConfigurationTypeDef",
     "PrefetchRetrievalTypeDef",
     "DefaultSegmentDeliveryConfigurationTypeDef",
     "HttpConfigurationTypeDef",
     "SegmentDeliveryConfigurationTypeDef",
     "DashConfigurationForPutTypeDef",
     "DashConfigurationTypeDef",
@@ -69,69 +71,68 @@
     "DeleteSourceLocationRequestRequestTypeDef",
     "DeleteVodSourceRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeLiveSourceRequestRequestTypeDef",
     "DescribeProgramRequestRequestTypeDef",
     "DescribeSourceLocationRequestRequestTypeDef",
     "DescribeVodSourceRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelPolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetChannelPolicyResponseTypeDef",
+    "GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
     "GetChannelScheduleRequestRequestTypeDef",
     "GetPlaybackConfigurationRequestRequestTypeDef",
     "HlsConfigurationTypeDef",
     "LivePreRollConfigurationTypeDef",
     "LogConfigurationTypeDef",
     "GetPrefetchScheduleRequestRequestTypeDef",
     "HlsPlaylistSettingsTypeDef",
+    "ListAlertsRequestListAlertsPaginateTypeDef",
     "ListAlertsRequestRequestTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
     "ListLiveSourcesRequestRequestTypeDef",
+    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
     "ListPlaybackConfigurationsRequestRequestTypeDef",
+    "ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
     "ListPrefetchSchedulesRequestRequestTypeDef",
+    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
     "ListSourceLocationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListVodSourcesRequestListVodSourcesPaginateTypeDef",
     "ListVodSourcesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutChannelPolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ScheduleAdBreakTypeDef",
     "TransitionTypeDef",
     "SegmentationDescriptorTypeDef",
     "StartChannelRequestRequestTypeDef",
     "StopChannelRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateProgramTransitionTypeDef",
     "AccessConfigurationTypeDef",
     "ManifestProcessingRulesTypeDef",
-    "PrefetchConsumptionTypeDef",
-    "ConfigureLogsForChannelResponseTypeDef",
-    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetChannelPolicyResponseTypeDef",
     "ListAlertsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "PrefetchConsumptionTypeDef",
     "CreateLiveSourceRequestRequestTypeDef",
     "CreateLiveSourceResponseTypeDef",
     "CreateVodSourceRequestRequestTypeDef",
     "CreateVodSourceResponseTypeDef",
     "DescribeLiveSourceResponseTypeDef",
     "DescribeVodSourceResponseTypeDef",
     "LiveSourceTypeDef",
     "UpdateLiveSourceRequestRequestTypeDef",
     "UpdateLiveSourceResponseTypeDef",
     "UpdateVodSourceRequestRequestTypeDef",
     "UpdateVodSourceResponseTypeDef",
     "VodSourceTypeDef",
-    "GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    "ListAlertsRequestListAlertsPaginateTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
-    "ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
-    "ListVodSourcesRequestListVodSourcesPaginateTypeDef",
     "RequestOutputItemTypeDef",
     "ResponseOutputItemTypeDef",
     "ScheduleEntryTypeDef",
     "ScheduleConfigurationTypeDef",
     "TimeSignalMessageTypeDef",
     "UpdateProgramScheduleConfigurationTypeDef",
     "CreateSourceLocationRequestRequestTypeDef",
@@ -225,14 +226,15 @@
         "Operator": Literal["EQUALS"],
     },
 )
 
 AvailSuppressionTypeDef = TypedDict(
     "AvailSuppressionTypeDef",
     {
+        "FillPolicy": FillPolicyType,
         "Mode": ModeType,
         "Value": str,
     },
     total=False,
 )
 
 BumperTypeDef = TypedDict(
@@ -272,33 +274,40 @@
     "ConfigureLogsForChannelRequestRequestTypeDef",
     {
         "ChannelName": str,
         "LogTypes": Sequence[Literal["AS_RUN"]],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ConfigureLogsForChannelResponseTypeDef = TypedDict(
+    "ConfigureLogsForChannelResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChannelName": str,
+        "LogTypes": List[Literal["AS_RUN"]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef = TypedDict(
     "ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef",
     {
         "PercentEnabled": int,
         "PlaybackConfigurationName": str,
     },
 )
 
+ConfigureLogsForPlaybackConfigurationResponseTypeDef = TypedDict(
+    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
+    {
+        "PercentEnabled": int,
+        "PlaybackConfigurationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HttpPackageConfigurationTypeDef = TypedDict(
     "HttpPackageConfigurationTypeDef",
     {
         "Path": str,
         "SourceGroup": str,
         "Type": TypeType,
     },
@@ -472,31 +481,57 @@
     "DescribeVodSourceRequestRequestTypeDef",
     {
         "SourceLocationName": str,
         "VodSourceName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelPolicyRequestRequestTypeDef = TypedDict(
     "GetChannelPolicyRequestRequestTypeDef",
     {
         "ChannelName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetChannelPolicyResponseTypeDef = TypedDict(
+    "GetChannelPolicyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
+    "_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
+    {
+        "ChannelName": str,
+    },
+)
+_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
+    "_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
+    {
+        "DurationMinutes": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef(
+    _RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
+    _OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
+):
+    pass
+
 _RequiredGetChannelScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredGetChannelScheduleRequestRequestTypeDef",
     {
         "ChannelName": str,
     },
 )
 _OptionalGetChannelScheduleRequestRequestTypeDef = TypedDict(
@@ -558,14 +593,34 @@
     "HlsPlaylistSettingsTypeDef",
     {
         "ManifestWindowSeconds": int,
     },
     total=False,
 )
 
+_RequiredListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
+    "_RequiredListAlertsRequestListAlertsPaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
+    "_OptionalListAlertsRequestListAlertsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAlertsRequestListAlertsPaginateTypeDef(
+    _RequiredListAlertsRequestListAlertsPaginateTypeDef,
+    _OptionalListAlertsRequestListAlertsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAlertsRequestRequestTypeDef = TypedDict(
     "_RequiredListAlertsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListAlertsRequestRequestTypeDef = TypedDict(
@@ -578,23 +633,51 @@
 )
 
 class ListAlertsRequestRequestTypeDef(
     _RequiredListAlertsRequestRequestTypeDef, _OptionalListAlertsRequestRequestTypeDef
 ):
     pass
 
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
+    {
+        "SourceLocationName": str,
+    },
+)
+_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLiveSourcesRequestListLiveSourcesPaginateTypeDef(
+    _RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
+    _OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListLiveSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListLiveSourcesRequestRequestTypeDef",
     {
         "SourceLocationName": str,
     },
 )
 _OptionalListLiveSourcesRequestRequestTypeDef = TypedDict(
@@ -607,23 +690,52 @@
 )
 
 class ListLiveSourcesRequestRequestTypeDef(
     _RequiredListLiveSourcesRequestRequestTypeDef, _OptionalListLiveSourcesRequestRequestTypeDef
 ):
     pass
 
+ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef = TypedDict(
+    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPlaybackConfigurationsRequestRequestTypeDef = TypedDict(
     "ListPlaybackConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
+    "_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
+    {
+        "PlaybackConfigurationName": str,
+    },
+)
+_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
+    "_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
+    {
+        "StreamId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef(
+    _RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
+    _OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
+):
+    pass
+
 _RequiredListPrefetchSchedulesRequestRequestTypeDef = TypedDict(
     "_RequiredListPrefetchSchedulesRequestRequestTypeDef",
     {
         "PlaybackConfigurationName": str,
     },
 )
 _OptionalListPrefetchSchedulesRequestRequestTypeDef = TypedDict(
@@ -638,14 +750,22 @@
 
 class ListPrefetchSchedulesRequestRequestTypeDef(
     _RequiredListPrefetchSchedulesRequestRequestTypeDef,
     _OptionalListPrefetchSchedulesRequestRequestTypeDef,
 ):
     pass
 
+ListSourceLocationsRequestListSourceLocationsPaginateTypeDef = TypedDict(
+    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSourceLocationsRequestRequestTypeDef = TypedDict(
     "ListSourceLocationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -654,14 +774,42 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef",
+    {
+        "SourceLocationName": str,
+    },
+)
+_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVodSourcesRequestListVodSourcesPaginateTypeDef(
+    _RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef,
+    _OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListVodSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListVodSourcesRequestRequestTypeDef",
     {
         "SourceLocationName": str,
     },
 )
 _OptionalListVodSourcesRequestRequestTypeDef = TypedDict(
@@ -674,22 +822,43 @@
 )
 
 class ListVodSourcesRequestRequestTypeDef(
     _RequiredListVodSourcesRequestRequestTypeDef, _OptionalListVodSourcesRequestRequestTypeDef
 ):
     pass
 
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
 PutChannelPolicyRequestRequestTypeDef = TypedDict(
     "PutChannelPolicyRequestRequestTypeDef",
     {
         "ChannelName": str,
         "Policy": str,
     },
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
 ScheduleAdBreakTypeDef = TypedDict(
     "ScheduleAdBreakTypeDef",
     {
         "ApproximateDurationSeconds": int,
         "ApproximateStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
@@ -784,14 +953,23 @@
     "ManifestProcessingRulesTypeDef",
     {
         "AdMarkerPassthrough": AdMarkerPassthroughTypeDef,
     },
     total=False,
 )
 
+ListAlertsResponseTypeDef = TypedDict(
+    "ListAlertsResponseTypeDef",
+    {
+        "Items": List[AlertTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPrefetchConsumptionTypeDef = TypedDict(
     "_RequiredPrefetchConsumptionTypeDef",
     {
         "EndTime": Union[datetime, str],
     },
 )
 _OptionalPrefetchConsumptionTypeDef = TypedDict(
@@ -804,64 +982,14 @@
 )
 
 class PrefetchConsumptionTypeDef(
     _RequiredPrefetchConsumptionTypeDef, _OptionalPrefetchConsumptionTypeDef
 ):
     pass
 
-ConfigureLogsForChannelResponseTypeDef = TypedDict(
-    "ConfigureLogsForChannelResponseTypeDef",
-    {
-        "ChannelName": str,
-        "LogTypes": List[Literal["AS_RUN"]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfigureLogsForPlaybackConfigurationResponseTypeDef = TypedDict(
-    "ConfigureLogsForPlaybackConfigurationResponseTypeDef",
-    {
-        "PercentEnabled": int,
-        "PlaybackConfigurationName": str,
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
-GetChannelPolicyResponseTypeDef = TypedDict(
-    "GetChannelPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlertsResponseTypeDef = TypedDict(
-    "ListAlertsResponseTypeDef",
-    {
-        "Items": List[AlertTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateLiveSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLiveSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
         "LiveSourceName": str,
         "SourceLocationName": str,
     },
@@ -885,15 +1013,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateVodSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVodSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
@@ -920,43 +1048,43 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLiveSourceResponseTypeDef = TypedDict(
     "DescribeLiveSourceResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVodSourceResponseTypeDef = TypedDict(
     "DescribeVodSourceResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLiveSourceTypeDef = TypedDict(
     "_RequiredLiveSourceTypeDef",
     {
         "Arn": str,
@@ -993,15 +1121,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "LiveSourceName": str,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVodSourceRequestRequestTypeDef = TypedDict(
     "UpdateVodSourceRequestRequestTypeDef",
     {
         "HttpPackageConfigurations": Sequence[HttpPackageConfigurationTypeDef],
@@ -1016,15 +1144,15 @@
         "Arn": str,
         "CreationTime": datetime,
         "HttpPackageConfigurations": List[HttpPackageConfigurationTypeDef],
         "LastModifiedTime": datetime,
         "SourceLocationName": str,
         "Tags": Dict[str, str],
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVodSourceTypeDef = TypedDict(
     "_RequiredVodSourceTypeDef",
     {
         "Arn": str,
@@ -1042,140 +1170,14 @@
     },
     total=False,
 )
 
 class VodSourceTypeDef(_RequiredVodSourceTypeDef, _OptionalVodSourceTypeDef):
     pass
 
-_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
-    "_RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    {
-        "ChannelName": str,
-    },
-)
-_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef = TypedDict(
-    "_OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef",
-    {
-        "DurationMinutes": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef(
-    _RequiredGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-    _OptionalGetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-):
-    pass
-
-_RequiredListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
-    "_RequiredListAlertsRequestListAlertsPaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListAlertsRequestListAlertsPaginateTypeDef = TypedDict(
-    "_OptionalListAlertsRequestListAlertsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAlertsRequestListAlertsPaginateTypeDef(
-    _RequiredListAlertsRequestListAlertsPaginateTypeDef,
-    _OptionalListAlertsRequestListAlertsPaginateTypeDef,
-):
-    pass
-
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    {
-        "SourceLocationName": str,
-    },
-)
-_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLiveSourcesRequestListLiveSourcesPaginateTypeDef(
-    _RequiredListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-    _OptionalListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-):
-    pass
-
-ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef = TypedDict(
-    "ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
-    "_RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    {
-        "PlaybackConfigurationName": str,
-    },
-)
-_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef = TypedDict(
-    "_OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef",
-    {
-        "StreamId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef(
-    _RequiredListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-    _OptionalListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-):
-    pass
-
-ListSourceLocationsRequestListSourceLocationsPaginateTypeDef = TypedDict(
-    "ListSourceLocationsRequestListSourceLocationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef",
-    {
-        "SourceLocationName": str,
-    },
-)
-_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVodSourcesRequestListVodSourcesPaginateTypeDef(
-    _RequiredListVodSourcesRequestListVodSourcesPaginateTypeDef,
-    _OptionalListVodSourcesRequestListVodSourcesPaginateTypeDef,
-):
-    pass
-
 _RequiredRequestOutputItemTypeDef = TypedDict(
     "_RequiredRequestOutputItemTypeDef",
     {
         "ManifestName": str,
         "SourceGroup": str,
     },
 )
@@ -1308,15 +1310,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceLocationResponseTypeDef = TypedDict(
     "DescribeSourceLocationResponseTypeDef",
     {
         "AccessConfiguration": AccessConfigurationTypeDef,
@@ -1324,15 +1326,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSourceLocationTypeDef = TypedDict(
     "_RequiredSourceLocationTypeDef",
     {
         "Arn": str,
@@ -1387,15 +1389,15 @@
         "CreationTime": datetime,
         "DefaultSegmentDeliveryConfiguration": DefaultSegmentDeliveryConfigurationTypeDef,
         "HttpConfiguration": HttpConfigurationTypeDef,
         "LastModifiedTime": datetime,
         "SegmentDeliveryConfigurations": List[SegmentDeliveryConfigurationTypeDef],
         "SourceLocationName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPlaybackConfigurationResponseTypeDef = TypedDict(
     "GetPlaybackConfigurationResponseTypeDef",
     {
         "AdDecisionServerUrl": str,
@@ -1413,15 +1415,15 @@
         "PlaybackConfigurationArn": str,
         "PlaybackEndpointPrefix": str,
         "SessionInitializationEndpointPrefix": str,
         "SlateAdUrl": str,
         "Tags": Dict[str, str],
         "TranscodeProfileName": str,
         "VideoContentSourceUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PlaybackConfigurationTypeDef = TypedDict(
     "PlaybackConfigurationTypeDef",
     {
         "AdDecisionServerUrl": str,
@@ -1497,15 +1499,15 @@
         "PlaybackConfigurationArn": str,
         "PlaybackEndpointPrefix": str,
         "SessionInitializationEndpointPrefix": str,
         "SlateAdUrl": str,
         "Tags": Dict[str, str],
         "TranscodeProfileName": str,
         "VideoContentSourceUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePrefetchScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePrefetchScheduleRequestRequestTypeDef",
     {
         "Consumption": PrefetchConsumptionTypeDef,
@@ -1533,28 +1535,28 @@
     {
         "Arn": str,
         "Consumption": PrefetchConsumptionTypeDef,
         "Name": str,
         "PlaybackConfigurationName": str,
         "Retrieval": PrefetchRetrievalTypeDef,
         "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPrefetchScheduleResponseTypeDef = TypedDict(
     "GetPrefetchScheduleResponseTypeDef",
     {
         "Arn": str,
         "Consumption": PrefetchConsumptionTypeDef,
         "Name": str,
         "PlaybackConfigurationName": str,
         "Retrieval": PrefetchRetrievalTypeDef,
         "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPrefetchScheduleTypeDef = TypedDict(
     "_RequiredPrefetchScheduleTypeDef",
     {
         "Arn": str,
@@ -1576,24 +1578,24 @@
     pass
 
 ListLiveSourcesResponseTypeDef = TypedDict(
     "ListLiveSourcesResponseTypeDef",
     {
         "Items": List[LiveSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVodSourcesResponseTypeDef = TypedDict(
     "ListVodSourcesResponseTypeDef",
     {
         "Items": List[VodSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1671,15 +1673,15 @@
         "CreationTime": datetime,
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
@@ -1689,15 +1691,15 @@
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "LogConfiguration": LogConfigurationForChannelTypeDef,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Arn": str,
@@ -1706,24 +1708,24 @@
         "CreationTime": datetime,
         "FillerSlate": SlateSourceTypeDef,
         "LastModifiedTime": datetime,
         "Outputs": List[ResponseOutputItemTypeDef],
         "PlaybackMode": str,
         "Tags": Dict[str, str],
         "Tier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelScheduleResponseTypeDef = TypedDict(
     "GetChannelScheduleResponseTypeDef",
     {
         "Items": List[ScheduleEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdBreakTypeDef = TypedDict(
     "AdBreakTypeDef",
     {
         "MessageType": MessageTypeType,
@@ -1736,42 +1738,42 @@
 )
 
 ListSourceLocationsResponseTypeDef = TypedDict(
     "ListSourceLocationsResponseTypeDef",
     {
         "Items": List[SourceLocationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlaybackConfigurationsResponseTypeDef = TypedDict(
     "ListPlaybackConfigurationsResponseTypeDef",
     {
         "Items": List[PlaybackConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPrefetchSchedulesResponseTypeDef = TypedDict(
     "ListPrefetchSchedulesResponseTypeDef",
     {
         "Items": List[PrefetchScheduleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Items": List[ChannelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProgramRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProgramRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1805,15 +1807,15 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProgramResponseTypeDef = TypedDict(
     "DescribeProgramResponseTypeDef",
     {
         "AdBreaks": List[AdBreakTypeDef],
@@ -1823,15 +1825,15 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateProgramRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProgramRequestRequestTypeDef",
     {
         "ChannelName": str,
@@ -1862,10 +1864,10 @@
         "CreationTime": datetime,
         "DurationMillis": int,
         "LiveSourceName": str,
         "ProgramName": str,
         "ScheduledStartTime": datetime,
         "SourceLocationName": str,
         "VodSourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/PKG-INFO` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediatailor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaTailor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaTailor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediatailor"></a>
 
 # types-aiobotocore-mediatailor
 
 [![PyPI - types-aiobotocore-mediatailor](https://img.shields.io/pypi/v/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediatailor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediatailor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediatailor?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediatailor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaTailor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
+[aiobotocore.MediaTailor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediatailor.html#MediaTailor)
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
 [types-aiobotocore-mediatailor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediatailor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,14 +320,15 @@
 `types_aiobotocore_mediatailor.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediatailor.literals import (
     AccessTypeType,
     ChannelStateType,
+    FillPolicyType,
     GetChannelSchedulePaginatorName,
     ListAlertsPaginatorName,
     ListChannelsPaginatorName,
     ListLiveSourcesPaginatorName,
     ListPlaybackConfigurationsPaginatorName,
     ListPrefetchSchedulesPaginatorName,
     ListSourceLocationsPaginatorName,
@@ -371,16 +372,17 @@
     AvailMatchingCriteriaTypeDef,
     AvailSuppressionTypeDef,
     BumperTypeDef,
     CdnConfigurationTypeDef,
     LogConfigurationForChannelTypeDef,
     ClipRangeTypeDef,
     ConfigureLogsForChannelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ConfigureLogsForChannelResponseTypeDef,
     ConfigureLogsForPlaybackConfigurationRequestRequestTypeDef,
+    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
     HttpPackageConfigurationTypeDef,
     PrefetchRetrievalTypeDef,
     DefaultSegmentDeliveryConfigurationTypeDef,
     HttpConfigurationTypeDef,
     SegmentDeliveryConfigurationTypeDef,
     DashConfigurationForPutTypeDef,
     DashConfigurationTypeDef,
@@ -394,69 +396,68 @@
     DeleteSourceLocationRequestRequestTypeDef,
     DeleteVodSourceRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeLiveSourceRequestRequestTypeDef,
     DescribeProgramRequestRequestTypeDef,
     DescribeSourceLocationRequestRequestTypeDef,
     DescribeVodSourceRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetChannelPolicyResponseTypeDef,
+    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
     GetChannelScheduleRequestRequestTypeDef,
     GetPlaybackConfigurationRequestRequestTypeDef,
     HlsConfigurationTypeDef,
     LivePreRollConfigurationTypeDef,
     LogConfigurationTypeDef,
     GetPrefetchScheduleRequestRequestTypeDef,
     HlsPlaylistSettingsTypeDef,
+    ListAlertsRequestListAlertsPaginateTypeDef,
     ListAlertsRequestRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
     ListLiveSourcesRequestRequestTypeDef,
+    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
     ListPlaybackConfigurationsRequestRequestTypeDef,
+    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
     ListPrefetchSchedulesRequestRequestTypeDef,
+    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
     ListSourceLocationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     ListVodSourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutChannelPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ScheduleAdBreakTypeDef,
     TransitionTypeDef,
     SegmentationDescriptorTypeDef,
     StartChannelRequestRequestTypeDef,
     StopChannelRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProgramTransitionTypeDef,
     AccessConfigurationTypeDef,
     ManifestProcessingRulesTypeDef,
-    PrefetchConsumptionTypeDef,
-    ConfigureLogsForChannelResponseTypeDef,
-    ConfigureLogsForPlaybackConfigurationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChannelPolicyResponseTypeDef,
     ListAlertsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PrefetchConsumptionTypeDef,
     CreateLiveSourceRequestRequestTypeDef,
     CreateLiveSourceResponseTypeDef,
     CreateVodSourceRequestRequestTypeDef,
     CreateVodSourceResponseTypeDef,
     DescribeLiveSourceResponseTypeDef,
     DescribeVodSourceResponseTypeDef,
     LiveSourceTypeDef,
     UpdateLiveSourceRequestRequestTypeDef,
     UpdateLiveSourceResponseTypeDef,
     UpdateVodSourceRequestRequestTypeDef,
     UpdateVodSourceResponseTypeDef,
     VodSourceTypeDef,
-    GetChannelScheduleRequestGetChannelSchedulePaginateTypeDef,
-    ListAlertsRequestListAlertsPaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListLiveSourcesRequestListLiveSourcesPaginateTypeDef,
-    ListPlaybackConfigurationsRequestListPlaybackConfigurationsPaginateTypeDef,
-    ListPrefetchSchedulesRequestListPrefetchSchedulesPaginateTypeDef,
-    ListSourceLocationsRequestListSourceLocationsPaginateTypeDef,
-    ListVodSourcesRequestListVodSourcesPaginateTypeDef,
     RequestOutputItemTypeDef,
     ResponseOutputItemTypeDef,
     ScheduleEntryTypeDef,
     ScheduleConfigurationTypeDef,
     TimeSignalMessageTypeDef,
     UpdateProgramScheduleConfigurationTypeDef,
     CreateSourceLocationRequestRequestTypeDef,
@@ -502,43 +503,43 @@
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

### Comparing `types-aiobotocore-mediatailor-2.5.0.post1/types_aiobotocore_mediatailor.egg-info/SOURCES.txt` & `types-aiobotocore-mediatailor-2.5.1/types_aiobotocore_mediatailor.egg-info/SOURCES.txt`

 * *Files identical despite different names*

