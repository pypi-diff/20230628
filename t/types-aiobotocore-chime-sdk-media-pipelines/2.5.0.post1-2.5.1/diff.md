# Comparing `tmp/types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-chime-sdk-media-pipelines-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-chime-sdk-media-pipelines-2.5.1.tar", last modified: Wed Jun 28 01:43:11 2023, max compression
```

## Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1.tar` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.634999 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15877 2023-03-11 12:26:17.634999 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14237 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.634999 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2250 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.634999 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/
--rw-r--r--   0 runner    (1001) docker     (123)      571 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      570 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12962 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12941 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9303 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9301 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19985 2023-03-11 12:10:28.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19964 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.634999 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15877 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1040 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.114103 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18208 2023-06-28 01:43:11.110103 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16574 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.114103 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2244 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.106103 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/
+-rw-r--r--   0 runner    (1001) docker     (123)      571 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      570 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      997 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19230 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19202 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11118 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11116 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    38659 2023-06-28 01:27:04.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38614 2023-06-28 01:27:04.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.106103 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18208 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1040 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/LICENSE` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/PKG-INFO` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/README.md`

 * *Files 26% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-chime-sdk-media-pipelines
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKMediaPipelines 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore chime-sdk-media-pipelines type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-chime-sdk-media-pipelines"></a>
 
 # types-aiobotocore-chime-sdk-media-pipelines
 
 [![PyPI - types-aiobotocore-chime-sdk-media-pipelines](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-media-pipelines.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-media-pipelines)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-media-pipelines.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-media-pipelines)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-media-pipelines?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-media-pipelines)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMediaPipelines 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines)
+[aiobotocore.ChimeSDKMediaPipelines 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines)
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
 [types-aiobotocore-chime-sdk-media-pipelines docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/).
 
 See how it helps to find and fix potential bugs:
 
@@ -275,28 +242,42 @@
 ```python
 from types_aiobotocore_chime_sdk_media_pipelines.literals import (
     ArtifactsConcatenationStateType,
     ArtifactsStateType,
     AudioArtifactsConcatenationStateType,
     AudioChannelsOptionType,
     AudioMuxTypeType,
+    CallAnalyticsLanguageCodeType,
     ConcatenationSinkTypeType,
     ConcatenationSourceTypeType,
     ContentMuxTypeType,
+    ContentRedactionOutputType,
     ContentShareLayoutOptionType,
+    ContentTypeType,
+    FragmentSelectorTypeType,
     LayoutOptionType,
     LiveConnectorMuxTypeType,
     LiveConnectorSinkTypeType,
     LiveConnectorSourceTypeType,
+    MediaEncodingType,
+    MediaInsightsPipelineConfigurationElementTypeType,
     MediaPipelineSinkTypeType,
     MediaPipelineSourceTypeType,
     MediaPipelineStatusType,
+    MediaPipelineStatusUpdateType,
+    PartialResultsStabilityType,
+    ParticipantRoleType,
     PresenterPositionType,
+    RealTimeAlertRuleTypeType,
+    RecordingFileFormatType,
     ResolutionOptionType,
+    SentimentTypeType,
     VideoMuxTypeType,
+    VocabularyFilterMethodType,
+    VoiceAnalyticsConfigurationStatusType,
     ChimeSDKMediaPipelinesServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
@@ -310,113 +291,152 @@
 
 `types_aiobotocore_chime_sdk_media_pipelines.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_chime_sdk_media_pipelines.type_defs import (
+    PostCallAnalyticsSettingsTypeDef,
+    AmazonTranscribeProcessorConfigurationTypeDef,
     AudioConcatenationConfigurationTypeDef,
     CompositedVideoConcatenationConfigurationTypeDef,
     ContentConcatenationConfigurationTypeDef,
     DataChannelConcatenationConfigurationTypeDef,
     MeetingEventsConcatenationConfigurationTypeDef,
     TranscriptionMessagesConcatenationConfigurationTypeDef,
     VideoConcatenationConfigurationTypeDef,
     AudioArtifactsConfigurationTypeDef,
     ContentArtifactsConfigurationTypeDef,
     VideoArtifactsConfigurationTypeDef,
+    ChannelDefinitionTypeDef,
     S3BucketSinkConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    S3RecordingSinkRuntimeConfigurationTypeDef,
     DeleteMediaCapturePipelineRequestRequestTypeDef,
+    DeleteMediaInsightsPipelineConfigurationRequestRequestTypeDef,
     DeleteMediaPipelineRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    TimestampRangeTypeDef,
     GetMediaCapturePipelineRequestRequestTypeDef,
+    GetMediaInsightsPipelineConfigurationRequestRequestTypeDef,
     GetMediaPipelineRequestRequestTypeDef,
     PresenterOnlyConfigurationTypeDef,
+    IssueDetectionConfigurationTypeDef,
+    KeywordMatchConfigurationTypeDef,
+    KinesisDataStreamSinkConfigurationTypeDef,
+    RecordingStreamConfigurationTypeDef,
+    LambdaFunctionSinkConfigurationTypeDef,
     ListMediaCapturePipelinesRequestRequestTypeDef,
     MediaCapturePipelineSummaryTypeDef,
+    ListMediaInsightsPipelineConfigurationsRequestRequestTypeDef,
+    MediaInsightsPipelineConfigurationSummaryTypeDef,
     ListMediaPipelinesRequestRequestTypeDef,
     MediaPipelineSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     LiveConnectorRTMPConfigurationTypeDef,
+    S3RecordingSinkConfigurationTypeDef,
+    SnsTopicSinkConfigurationTypeDef,
+    SqsQueueSinkConfigurationTypeDef,
+    VoiceAnalyticsProcessorConfigurationTypeDef,
+    SentimentConfigurationTypeDef,
+    ResponseMetadataTypeDef,
     SelectedVideoStreamsTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateMediaInsightsPipelineStatusRequestRequestTypeDef,
+    AmazonTranscribeCallAnalyticsProcessorConfigurationTypeDef,
     ArtifactsConcatenationConfigurationTypeDef,
+    StreamChannelDefinitionTypeDef,
     ConcatenationSinkTypeDef,
-    TagResourceRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    FragmentSelectorTypeDef,
     GridViewConfigurationTypeDef,
     ListMediaCapturePipelinesResponseTypeDef,
+    ListMediaInsightsPipelineConfigurationsResponseTypeDef,
     ListMediaPipelinesResponseTypeDef,
     LiveConnectorSinkConfigurationTypeDef,
+    RealTimeAlertRuleTypeDef,
     SourceConfigurationTypeDef,
+    MediaInsightsPipelineConfigurationElementTypeDef,
     ChimeSdkMeetingConcatenationConfigurationTypeDef,
+    StreamConfigurationTypeDef,
+    KinesisVideoStreamRecordingSourceRuntimeConfigurationTypeDef,
     CompositedVideoArtifactsConfigurationTypeDef,
+    RealTimeAlertConfigurationTypeDef,
     MediaCapturePipelineSourceConfigurationTypeDef,
+    KinesisVideoStreamSourceRuntimeConfigurationTypeDef,
     ArtifactsConfigurationTypeDef,
     ChimeSdkMeetingLiveConnectorConfigurationTypeDef,
+    CreateMediaInsightsPipelineConfigurationRequestRequestTypeDef,
+    MediaInsightsPipelineConfigurationTypeDef,
+    UpdateMediaInsightsPipelineConfigurationRequestRequestTypeDef,
     ConcatenationSourceTypeDef,
+    CreateMediaInsightsPipelineRequestRequestTypeDef,
+    MediaInsightsPipelineTypeDef,
     ChimeSdkMeetingConfigurationTypeDef,
     LiveConnectorSourceConfigurationTypeDef,
+    CreateMediaInsightsPipelineConfigurationResponseTypeDef,
+    GetMediaInsightsPipelineConfigurationResponseTypeDef,
+    UpdateMediaInsightsPipelineConfigurationResponseTypeDef,
     CreateMediaConcatenationPipelineRequestRequestTypeDef,
     MediaConcatenationPipelineTypeDef,
+    CreateMediaInsightsPipelineResponseTypeDef,
     CreateMediaCapturePipelineRequestRequestTypeDef,
     MediaCapturePipelineTypeDef,
     CreateMediaLiveConnectorPipelineRequestRequestTypeDef,
     MediaLiveConnectorPipelineTypeDef,
     CreateMediaConcatenationPipelineResponseTypeDef,
     CreateMediaCapturePipelineResponseTypeDef,
     GetMediaCapturePipelineResponseTypeDef,
     CreateMediaLiveConnectorPipelineResponseTypeDef,
     MediaPipelineTypeDef,
     GetMediaPipelineResponseTypeDef,
 )
 
 
-def get_structure() -> AudioConcatenationConfigurationTypeDef:
+def get_structure() -> PostCallAnalyticsSettingsTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/setup.py` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-chime-sdk-media-pipelines.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-chime-sdk-media-pipelines",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_chime_sdk_media_pipelines"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ChimeSDKMediaPipelines 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ChimeSDKMediaPipelines 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/",
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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__init__.py` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__init__.pyi` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/__main__.py` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ChimeSDKMediaPipelines 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ChimeSDKMediaPipelines 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines\nOther"
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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/client.py` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/client.py`

 * *Files 20% similar despite different names*

```diff
@@ -16,30 +16,41 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import MediaPipelineStatusUpdateType
 from .type_defs import (
     ChimeSdkMeetingConfigurationTypeDef,
     ConcatenationSinkTypeDef,
     ConcatenationSourceTypeDef,
     CreateMediaCapturePipelineResponseTypeDef,
     CreateMediaConcatenationPipelineResponseTypeDef,
+    CreateMediaInsightsPipelineConfigurationResponseTypeDef,
+    CreateMediaInsightsPipelineResponseTypeDef,
     CreateMediaLiveConnectorPipelineResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     GetMediaCapturePipelineResponseTypeDef,
+    GetMediaInsightsPipelineConfigurationResponseTypeDef,
     GetMediaPipelineResponseTypeDef,
+    KinesisVideoStreamRecordingSourceRuntimeConfigurationTypeDef,
+    KinesisVideoStreamSourceRuntimeConfigurationTypeDef,
     ListMediaCapturePipelinesResponseTypeDef,
+    ListMediaInsightsPipelineConfigurationsResponseTypeDef,
     ListMediaPipelinesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     LiveConnectorSinkConfigurationTypeDef,
     LiveConnectorSourceConfigurationTypeDef,
+    MediaInsightsPipelineConfigurationElementTypeDef,
+    RealTimeAlertConfigurationTypeDef,
+    S3RecordingSinkRuntimeConfigurationTypeDef,
     TagTypeDef,
+    UpdateMediaInsightsPipelineConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -54,14 +65,15 @@
         self.response: Dict[str, Any]
         self.operation_name: str
 
 
 class Exceptions:
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
     ResourceLimitExceededException: Type[BotocoreClientError]
     ServiceFailureException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     ThrottledClientException: Type[BotocoreClientError]
     UnauthorizedClientException: Type[BotocoreClientError]
@@ -129,24 +141,60 @@
         """
         Creates a media concatenation pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_concatenation_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_concatenation_pipeline)
         """
 
+    async def create_media_insights_pipeline(
+        self,
+        *,
+        MediaInsightsPipelineConfigurationArn: str,
+        KinesisVideoStreamSourceRuntimeConfiguration: KinesisVideoStreamSourceRuntimeConfigurationTypeDef = ...,
+        MediaInsightsRuntimeMetadata: Mapping[str, str] = ...,
+        KinesisVideoStreamRecordingSourceRuntimeConfiguration: KinesisVideoStreamRecordingSourceRuntimeConfigurationTypeDef = ...,
+        S3RecordingSinkRuntimeConfiguration: S3RecordingSinkRuntimeConfigurationTypeDef = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateMediaInsightsPipelineResponseTypeDef:
+        """
+        Creates a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_insights_pipeline)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_insights_pipeline)
+        """
+
+    async def create_media_insights_pipeline_configuration(
+        self,
+        *,
+        MediaInsightsPipelineConfigurationName: str,
+        ResourceAccessRoleArn: str,
+        Elements: Sequence[MediaInsightsPipelineConfigurationElementTypeDef],
+        RealTimeAlertConfiguration: RealTimeAlertConfigurationTypeDef = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        A structure that contains the static configurations for a media insights
+        pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_insights_pipeline_configuration)
+        """
+
     async def create_media_live_connector_pipeline(
         self,
         *,
         Sources: Sequence[LiveConnectorSourceConfigurationTypeDef],
         Sinks: Sequence[LiveConnectorSinkConfigurationTypeDef],
         ClientRequestToken: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateMediaLiveConnectorPipelineResponseTypeDef:
         """
-        Creates a streaming media pipeline in an Amazon Chime SDK meeting.
+        Creates a media live connector pipeline in an Amazon Chime SDK meeting.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_live_connector_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_live_connector_pipeline)
         """
 
     async def delete_media_capture_pipeline(
         self, *, MediaPipelineId: str
@@ -154,14 +202,24 @@
         """
         Deletes the media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_capture_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_capture_pipeline)
         """
 
+    async def delete_media_insights_pipeline_configuration(
+        self, *, Identifier: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the specified configuration settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_insights_pipeline_configuration)
+        """
+
     async def delete_media_pipeline(self, *, MediaPipelineId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_pipeline)
         """
@@ -186,14 +244,24 @@
         """
         Gets an existing media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_capture_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_capture_pipeline)
         """
 
+    async def get_media_insights_pipeline_configuration(
+        self, *, Identifier: str
+    ) -> GetMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        Gets the configuration settings for a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_insights_pipeline_configuration)
+        """
+
     async def get_media_pipeline(self, *, MediaPipelineId: str) -> GetMediaPipelineResponseTypeDef:
         """
         Gets an existing media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_pipeline)
         """
@@ -204,14 +272,24 @@
         """
         Returns a list of media pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_capture_pipelines)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#list_media_capture_pipelines)
         """
 
+    async def list_media_insights_pipeline_configurations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListMediaInsightsPipelineConfigurationsResponseTypeDef:
+        """
+        Lists the available media insights pipeline configurations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_insights_pipeline_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#list_media_insights_pipeline_configurations)
+        """
+
     async def list_media_pipelines(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListMediaPipelinesResponseTypeDef:
         """
         Returns a list of media pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_pipelines)
@@ -240,14 +318,39 @@
         """
         Removes any tags from a media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#untag_resource)
         """
 
+    async def update_media_insights_pipeline_configuration(
+        self,
+        *,
+        Identifier: str,
+        ResourceAccessRoleArn: str,
+        Elements: Sequence[MediaInsightsPipelineConfigurationElementTypeDef],
+        RealTimeAlertConfiguration: RealTimeAlertConfigurationTypeDef = ...
+    ) -> UpdateMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        Updates the media insights pipeline's configuration settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.update_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#update_media_insights_pipeline_configuration)
+        """
+
+    async def update_media_insights_pipeline_status(
+        self, *, Identifier: str, UpdateStatus: MediaPipelineStatusUpdateType
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Updates the status of a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.update_media_insights_pipeline_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#update_media_insights_pipeline_status)
+        """
+
     async def __aenter__(self) -> "ChimeSDKMediaPipelinesClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/client.pyi` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/client.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -16,30 +16,41 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import MediaPipelineStatusUpdateType
 from .type_defs import (
     ChimeSdkMeetingConfigurationTypeDef,
     ConcatenationSinkTypeDef,
     ConcatenationSourceTypeDef,
     CreateMediaCapturePipelineResponseTypeDef,
     CreateMediaConcatenationPipelineResponseTypeDef,
+    CreateMediaInsightsPipelineConfigurationResponseTypeDef,
+    CreateMediaInsightsPipelineResponseTypeDef,
     CreateMediaLiveConnectorPipelineResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     GetMediaCapturePipelineResponseTypeDef,
+    GetMediaInsightsPipelineConfigurationResponseTypeDef,
     GetMediaPipelineResponseTypeDef,
+    KinesisVideoStreamRecordingSourceRuntimeConfigurationTypeDef,
+    KinesisVideoStreamSourceRuntimeConfigurationTypeDef,
     ListMediaCapturePipelinesResponseTypeDef,
+    ListMediaInsightsPipelineConfigurationsResponseTypeDef,
     ListMediaPipelinesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     LiveConnectorSinkConfigurationTypeDef,
     LiveConnectorSourceConfigurationTypeDef,
+    MediaInsightsPipelineConfigurationElementTypeDef,
+    RealTimeAlertConfigurationTypeDef,
+    S3RecordingSinkRuntimeConfigurationTypeDef,
     TagTypeDef,
+    UpdateMediaInsightsPipelineConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -51,14 +62,15 @@
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
     ResourceLimitExceededException: Type[BotocoreClientError]
     ServiceFailureException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     ThrottledClientException: Type[BotocoreClientError]
     UnauthorizedClientException: Type[BotocoreClientError]
@@ -120,37 +132,80 @@
     ) -> CreateMediaConcatenationPipelineResponseTypeDef:
         """
         Creates a media concatenation pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_concatenation_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_concatenation_pipeline)
         """
+    async def create_media_insights_pipeline(
+        self,
+        *,
+        MediaInsightsPipelineConfigurationArn: str,
+        KinesisVideoStreamSourceRuntimeConfiguration: KinesisVideoStreamSourceRuntimeConfigurationTypeDef = ...,
+        MediaInsightsRuntimeMetadata: Mapping[str, str] = ...,
+        KinesisVideoStreamRecordingSourceRuntimeConfiguration: KinesisVideoStreamRecordingSourceRuntimeConfigurationTypeDef = ...,
+        S3RecordingSinkRuntimeConfiguration: S3RecordingSinkRuntimeConfigurationTypeDef = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateMediaInsightsPipelineResponseTypeDef:
+        """
+        Creates a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_insights_pipeline)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_insights_pipeline)
+        """
+    async def create_media_insights_pipeline_configuration(
+        self,
+        *,
+        MediaInsightsPipelineConfigurationName: str,
+        ResourceAccessRoleArn: str,
+        Elements: Sequence[MediaInsightsPipelineConfigurationElementTypeDef],
+        RealTimeAlertConfiguration: RealTimeAlertConfigurationTypeDef = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        A structure that contains the static configurations for a media insights
+        pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_insights_pipeline_configuration)
+        """
     async def create_media_live_connector_pipeline(
         self,
         *,
         Sources: Sequence[LiveConnectorSourceConfigurationTypeDef],
         Sinks: Sequence[LiveConnectorSinkConfigurationTypeDef],
         ClientRequestToken: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateMediaLiveConnectorPipelineResponseTypeDef:
         """
-        Creates a streaming media pipeline in an Amazon Chime SDK meeting.
+        Creates a media live connector pipeline in an Amazon Chime SDK meeting.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.create_media_live_connector_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#create_media_live_connector_pipeline)
         """
     async def delete_media_capture_pipeline(
         self, *, MediaPipelineId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_capture_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_capture_pipeline)
         """
+    async def delete_media_insights_pipeline_configuration(
+        self, *, Identifier: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the specified configuration settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_insights_pipeline_configuration)
+        """
     async def delete_media_pipeline(self, *, MediaPipelineId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.delete_media_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#delete_media_pipeline)
         """
@@ -172,14 +227,23 @@
     ) -> GetMediaCapturePipelineResponseTypeDef:
         """
         Gets an existing media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_capture_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_capture_pipeline)
         """
+    async def get_media_insights_pipeline_configuration(
+        self, *, Identifier: str
+    ) -> GetMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        Gets the configuration settings for a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_insights_pipeline_configuration)
+        """
     async def get_media_pipeline(self, *, MediaPipelineId: str) -> GetMediaPipelineResponseTypeDef:
         """
         Gets an existing media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.get_media_pipeline)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#get_media_pipeline)
         """
@@ -188,14 +252,23 @@
     ) -> ListMediaCapturePipelinesResponseTypeDef:
         """
         Returns a list of media pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_capture_pipelines)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#list_media_capture_pipelines)
         """
+    async def list_media_insights_pipeline_configurations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListMediaInsightsPipelineConfigurationsResponseTypeDef:
+        """
+        Lists the available media insights pipeline configurations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_insights_pipeline_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#list_media_insights_pipeline_configurations)
+        """
     async def list_media_pipelines(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListMediaPipelinesResponseTypeDef:
         """
         Returns a list of media pipelines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.list_media_pipelines)
@@ -220,14 +293,37 @@
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes any tags from a media pipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#untag_resource)
         """
+    async def update_media_insights_pipeline_configuration(
+        self,
+        *,
+        Identifier: str,
+        ResourceAccessRoleArn: str,
+        Elements: Sequence[MediaInsightsPipelineConfigurationElementTypeDef],
+        RealTimeAlertConfiguration: RealTimeAlertConfigurationTypeDef = ...
+    ) -> UpdateMediaInsightsPipelineConfigurationResponseTypeDef:
+        """
+        Updates the media insights pipeline's configuration settings.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.update_media_insights_pipeline_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#update_media_insights_pipeline_configuration)
+        """
+    async def update_media_insights_pipeline_status(
+        self, *, Identifier: str, UpdateStatus: MediaPipelineStatusUpdateType
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Updates the status of a media insights pipeline.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client.update_media_insights_pipeline_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/#update_media_insights_pipeline_status)
+        """
     async def __aenter__(self) -> "ChimeSDKMediaPipelinesClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-media-pipelines.html#ChimeSDKMediaPipelines.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_media_pipelines/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/literals.py` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/literals.py`

 * *Files 14% similar despite different names*

```diff
@@ -21,54 +21,95 @@
 
 __all__ = (
     "ArtifactsConcatenationStateType",
     "ArtifactsStateType",
     "AudioArtifactsConcatenationStateType",
     "AudioChannelsOptionType",
     "AudioMuxTypeType",
+    "CallAnalyticsLanguageCodeType",
     "ConcatenationSinkTypeType",
     "ConcatenationSourceTypeType",
     "ContentMuxTypeType",
+    "ContentRedactionOutputType",
     "ContentShareLayoutOptionType",
+    "ContentTypeType",
+    "FragmentSelectorTypeType",
     "LayoutOptionType",
     "LiveConnectorMuxTypeType",
     "LiveConnectorSinkTypeType",
     "LiveConnectorSourceTypeType",
+    "MediaEncodingType",
+    "MediaInsightsPipelineConfigurationElementTypeType",
     "MediaPipelineSinkTypeType",
     "MediaPipelineSourceTypeType",
     "MediaPipelineStatusType",
+    "MediaPipelineStatusUpdateType",
+    "PartialResultsStabilityType",
+    "ParticipantRoleType",
     "PresenterPositionType",
+    "RealTimeAlertRuleTypeType",
+    "RecordingFileFormatType",
     "ResolutionOptionType",
+    "SentimentTypeType",
     "VideoMuxTypeType",
+    "VocabularyFilterMethodType",
+    "VoiceAnalyticsConfigurationStatusType",
     "ChimeSDKMediaPipelinesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
 ArtifactsConcatenationStateType = Literal["Disabled", "Enabled"]
 ArtifactsStateType = Literal["Disabled", "Enabled"]
 AudioArtifactsConcatenationStateType = Literal["Enabled"]
 AudioChannelsOptionType = Literal["Mono", "Stereo"]
 AudioMuxTypeType = Literal["AudioOnly", "AudioWithActiveSpeakerVideo", "AudioWithCompositedVideo"]
+CallAnalyticsLanguageCodeType = Literal[
+    "de-DE", "en-AU", "en-GB", "en-US", "es-US", "fr-CA", "fr-FR", "it-IT", "pt-BR"
+]
 ConcatenationSinkTypeType = Literal["S3Bucket"]
 ConcatenationSourceTypeType = Literal["MediaCapturePipeline"]
 ContentMuxTypeType = Literal["ContentOnly"]
+ContentRedactionOutputType = Literal["redacted", "redacted_and_unredacted"]
 ContentShareLayoutOptionType = Literal["Horizontal", "PresenterOnly", "Vertical"]
+ContentTypeType = Literal["PII"]
+FragmentSelectorTypeType = Literal["ProducerTimestamp", "ServerTimestamp"]
 LayoutOptionType = Literal["GridView"]
 LiveConnectorMuxTypeType = Literal["AudioWithActiveSpeakerVideo", "AudioWithCompositedVideo"]
 LiveConnectorSinkTypeType = Literal["RTMP"]
 LiveConnectorSourceTypeType = Literal["ChimeSdkMeeting"]
+MediaEncodingType = Literal["pcm"]
+MediaInsightsPipelineConfigurationElementTypeType = Literal[
+    "AmazonTranscribeCallAnalyticsProcessor",
+    "AmazonTranscribeProcessor",
+    "KinesisDataStreamSink",
+    "LambdaFunctionSink",
+    "S3RecordingSink",
+    "SnsTopicSink",
+    "SqsQueueSink",
+    "VoiceAnalyticsProcessor",
+]
 MediaPipelineSinkTypeType = Literal["S3Bucket"]
 MediaPipelineSourceTypeType = Literal["ChimeSdkMeeting"]
-MediaPipelineStatusType = Literal["Failed", "InProgress", "Initializing", "Stopped", "Stopping"]
+MediaPipelineStatusType = Literal[
+    "Failed", "InProgress", "Initializing", "Paused", "Stopped", "Stopping"
+]
+MediaPipelineStatusUpdateType = Literal["Pause", "Resume"]
+PartialResultsStabilityType = Literal["high", "low", "medium"]
+ParticipantRoleType = Literal["AGENT", "CUSTOMER"]
 PresenterPositionType = Literal["BottomLeft", "BottomRight", "TopLeft", "TopRight"]
+RealTimeAlertRuleTypeType = Literal["IssueDetection", "KeywordMatch", "Sentiment"]
+RecordingFileFormatType = Literal["Opus", "Wav"]
 ResolutionOptionType = Literal["FHD", "HD"]
+SentimentTypeType = Literal["NEGATIVE"]
 VideoMuxTypeType = Literal["VideoOnly"]
+VocabularyFilterMethodType = Literal["mask", "remove", "tag"]
+VoiceAnalyticsConfigurationStatusType = Literal["Disabled", "Enabled"]
 ChimeSDKMediaPipelinesServiceName = Literal["chime-sdk-media-pipelines"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -124,14 +165,15 @@
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
@@ -210,14 +252,15 @@
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
@@ -228,14 +271,15 @@
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
@@ -271,14 +315,15 @@
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
@@ -297,16 +342,19 @@
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
@@ -390,15 +438,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines/literals.pyi` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines/literals.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -20,53 +20,94 @@
 
 __all__ = (
     "ArtifactsConcatenationStateType",
     "ArtifactsStateType",
     "AudioArtifactsConcatenationStateType",
     "AudioChannelsOptionType",
     "AudioMuxTypeType",
+    "CallAnalyticsLanguageCodeType",
     "ConcatenationSinkTypeType",
     "ConcatenationSourceTypeType",
     "ContentMuxTypeType",
+    "ContentRedactionOutputType",
     "ContentShareLayoutOptionType",
+    "ContentTypeType",
+    "FragmentSelectorTypeType",
     "LayoutOptionType",
     "LiveConnectorMuxTypeType",
     "LiveConnectorSinkTypeType",
     "LiveConnectorSourceTypeType",
+    "MediaEncodingType",
+    "MediaInsightsPipelineConfigurationElementTypeType",
     "MediaPipelineSinkTypeType",
     "MediaPipelineSourceTypeType",
     "MediaPipelineStatusType",
+    "MediaPipelineStatusUpdateType",
+    "PartialResultsStabilityType",
+    "ParticipantRoleType",
     "PresenterPositionType",
+    "RealTimeAlertRuleTypeType",
+    "RecordingFileFormatType",
     "ResolutionOptionType",
+    "SentimentTypeType",
     "VideoMuxTypeType",
+    "VocabularyFilterMethodType",
+    "VoiceAnalyticsConfigurationStatusType",
     "ChimeSDKMediaPipelinesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 ArtifactsConcatenationStateType = Literal["Disabled", "Enabled"]
 ArtifactsStateType = Literal["Disabled", "Enabled"]
 AudioArtifactsConcatenationStateType = Literal["Enabled"]
 AudioChannelsOptionType = Literal["Mono", "Stereo"]
 AudioMuxTypeType = Literal["AudioOnly", "AudioWithActiveSpeakerVideo", "AudioWithCompositedVideo"]
+CallAnalyticsLanguageCodeType = Literal[
+    "de-DE", "en-AU", "en-GB", "en-US", "es-US", "fr-CA", "fr-FR", "it-IT", "pt-BR"
+]
 ConcatenationSinkTypeType = Literal["S3Bucket"]
 ConcatenationSourceTypeType = Literal["MediaCapturePipeline"]
 ContentMuxTypeType = Literal["ContentOnly"]
+ContentRedactionOutputType = Literal["redacted", "redacted_and_unredacted"]
 ContentShareLayoutOptionType = Literal["Horizontal", "PresenterOnly", "Vertical"]
+ContentTypeType = Literal["PII"]
+FragmentSelectorTypeType = Literal["ProducerTimestamp", "ServerTimestamp"]
 LayoutOptionType = Literal["GridView"]
 LiveConnectorMuxTypeType = Literal["AudioWithActiveSpeakerVideo", "AudioWithCompositedVideo"]
 LiveConnectorSinkTypeType = Literal["RTMP"]
 LiveConnectorSourceTypeType = Literal["ChimeSdkMeeting"]
+MediaEncodingType = Literal["pcm"]
+MediaInsightsPipelineConfigurationElementTypeType = Literal[
+    "AmazonTranscribeCallAnalyticsProcessor",
+    "AmazonTranscribeProcessor",
+    "KinesisDataStreamSink",
+    "LambdaFunctionSink",
+    "S3RecordingSink",
+    "SnsTopicSink",
+    "SqsQueueSink",
+    "VoiceAnalyticsProcessor",
+]
 MediaPipelineSinkTypeType = Literal["S3Bucket"]
 MediaPipelineSourceTypeType = Literal["ChimeSdkMeeting"]
-MediaPipelineStatusType = Literal["Failed", "InProgress", "Initializing", "Stopped", "Stopping"]
+MediaPipelineStatusType = Literal[
+    "Failed", "InProgress", "Initializing", "Paused", "Stopped", "Stopping"
+]
+MediaPipelineStatusUpdateType = Literal["Pause", "Resume"]
+PartialResultsStabilityType = Literal["high", "low", "medium"]
+ParticipantRoleType = Literal["AGENT", "CUSTOMER"]
 PresenterPositionType = Literal["BottomLeft", "BottomRight", "TopLeft", "TopRight"]
+RealTimeAlertRuleTypeType = Literal["IssueDetection", "KeywordMatch", "Sentiment"]
+RecordingFileFormatType = Literal["Opus", "Wav"]
 ResolutionOptionType = Literal["FHD", "HD"]
+SentimentTypeType = Literal["NEGATIVE"]
 VideoMuxTypeType = Literal["VideoOnly"]
+VocabularyFilterMethodType = Literal["mask", "remove", "tag"]
+VoiceAnalyticsConfigurationStatusType = Literal["Disabled", "Enabled"]
 ChimeSDKMediaPipelinesServiceName = Literal["chime-sdk-media-pipelines"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -122,14 +163,15 @@
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
@@ -208,14 +250,15 @@
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
@@ -226,14 +269,15 @@
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
@@ -269,14 +313,15 @@
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
@@ -295,16 +340,19 @@
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
@@ -388,15 +436,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-media-pipelines-2.5.0.post1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/SOURCES.txt` & `types-aiobotocore-chime-sdk-media-pipelines-2.5.1/types_aiobotocore_chime_sdk_media_pipelines.egg-info/SOURCES.txt`

 * *Files identical despite different names*

