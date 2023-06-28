# Comparing `tmp/types-aiobotocore-mediaconvert-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediaconvert-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediaconvert-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediaconvert-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-mediaconvert-2.5.0.post1.tar` & `types-aiobotocore-mediaconvert-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.603416 types-aiobotocore-mediaconvert-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    33160 2023-03-11 12:26:58.603416 types-aiobotocore-mediaconvert-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    31569 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.603416 types-aiobotocore-mediaconvert-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.603416 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/
--rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1424 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24276 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24234 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    54340 2023-03-11 12:18:19.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    54338 2023-03-11 12:18:19.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7102 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7094 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   101659 2023-03-11 12:18:21.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   101634 2023-03-11 12:18:20.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:18.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.603416 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    33160 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.586174 types-aiobotocore-mediaconvert-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    33561 2023-06-28 01:43:49.586174 types-aiobotocore-mediaconvert-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    31976 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.586174 types-aiobotocore-mediaconvert-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.586174 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/
+-rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1424 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24276 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24234 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    55531 2023-06-28 01:35:01.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55529 2023-06-28 01:35:01.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6992 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6985 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   103387 2023-06-28 01:35:04.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   103362 2023-06-28 01:35:03.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:00.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.586174 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    33561 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/LICENSE` & `types-aiobotocore-mediaconvert-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediaconvert-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediaconvert
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaConvert 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaConvert 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediaconvert"></a>
 
 # types-aiobotocore-mediaconvert
 
 [![PyPI - types-aiobotocore-mediaconvert](https://img.shields.io/pypi/v/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconvert?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconvert)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConvert 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
+[aiobotocore.MediaConvert 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
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
 [types-aiobotocore-mediaconvert docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,14 +322,17 @@
     Ac3DynamicRangeCompressionLineType,
     Ac3DynamicRangeCompressionProfileType,
     Ac3DynamicRangeCompressionRfType,
     Ac3LfeFilterType,
     Ac3MetadataControlType,
     AccelerationModeType,
     AccelerationStatusType,
+    AdvancedInputFilterAddTextureType,
+    AdvancedInputFilterSharpenType,
+    AdvancedInputFilterType,
     AfdSignalingType,
     AlphaBehaviorType,
     AncillaryConvert608To708Type,
     AncillaryTerminateCaptionsType,
     AntiAliasType,
     AudioChannelTagType,
     AudioCodecType,
@@ -352,25 +355,28 @@
     AvcIntraFramerateControlType,
     AvcIntraFramerateConversionAlgorithmType,
     AvcIntraInterlaceModeType,
     AvcIntraScanTypeConversionModeType,
     AvcIntraSlowPalType,
     AvcIntraTelecineType,
     AvcIntraUhdQualityTuningLevelType,
+    BandwidthReductionFilterSharpeningType,
+    BandwidthReductionFilterStrengthType,
     BillingTagsSourceType,
     BurnInSubtitleStylePassthroughType,
     BurninSubtitleAlignmentType,
     BurninSubtitleApplyFontColorType,
     BurninSubtitleBackgroundColorType,
     BurninSubtitleFallbackFontType,
     BurninSubtitleFontColorType,
     BurninSubtitleOutlineColorType,
     BurninSubtitleShadowColorType,
     BurninSubtitleTeletextSpacingType,
     CaptionDestinationTypeType,
+    CaptionSourceConvertPaintOnToPopOnType,
     CaptionSourceTypeType,
     CmafClientCacheType,
     CmafCodecSpecificationType,
     CmafEncryptionTypeType,
     CmafImageBasedTrickPlayType,
     CmafInitializationVectorInManifestType,
     CmafIntervalCadenceType,
@@ -515,14 +521,15 @@
     H265SpatialAdaptiveQuantizationType,
     H265TelecineType,
     H265TemporalAdaptiveQuantizationType,
     H265TemporalIdsType,
     H265TilesType,
     H265UnregisteredSeiTimecodeType,
     H265WriteMp4PackagingTypeType,
+    HDRToSDRToneMapperType,
     HlsAdMarkersType,
     HlsAudioOnlyContainerType,
     HlsAudioOnlyHeaderType,
     HlsAudioTrackTypeType,
     HlsCaptionLanguageSettingType,
     HlsCaptionSegmentLengthControlType,
     HlsClientCacheType,
@@ -536,14 +543,15 @@
     HlsIntervalCadenceType,
     HlsKeyProviderTypeType,
     HlsManifestCompressionType,
     HlsManifestDurationFormatType,
     HlsOfflineEncryptedType,
     HlsOutputSelectionType,
     HlsProgramDateTimeType,
+    HlsProgressiveWriteHlsManifestType,
     HlsSegmentControlType,
     HlsSegmentLengthControlType,
     HlsStreamInfResolutionType,
     HlsTargetDurationCompatibilityModeType,
     HlsTimedMetadataId3FrameType,
     ImscAccessibilitySubsType,
     ImscStylePassthroughType,
@@ -735,14 +743,15 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconvert.type_defs import (
     AacSettingsTypeDef,
     Ac3SettingsTypeDef,
     AccelerationSettingsTypeDef,
+    AdvancedInputFilterSettingsTypeDef,
     AiffSettingsTypeDef,
     AllowedRenditionSizeTypeDef,
     AncillarySourceSettingsTypeDef,
     AssociateCertificateRequestRequestTypeDef,
     AudioChannelTaggingSettingsTypeDef,
     Eac3AtmosSettingsTypeDef,
     Eac3SettingsTypeDef,
@@ -756,14 +765,15 @@
     HlsRenditionGroupSettingsTypeDef,
     ForceIncludeRenditionSizeTypeDef,
     MinBottomRenditionSizeTypeDef,
     MinTopRenditionSizeTypeDef,
     Av1QvbrSettingsTypeDef,
     AvailBlankingTypeDef,
     AvcIntraUhdSettingsTypeDef,
+    BandwidthReductionFilterTypeDef,
     BurninDestinationSettingsTypeDef,
     CancelJobRequestRequestTypeDef,
     DvbSubDestinationSettingsTypeDef,
     EmbeddedDestinationSettingsTypeDef,
     ImscDestinationSettingsTypeDef,
     SccDestinationSettingsTypeDef,
     SrtDestinationSettingsTypeDef,
@@ -786,24 +796,23 @@
     Hdr10MetadataTypeDef,
     F4vSettingsTypeDef,
     M3u8SettingsTypeDef,
     MovSettingsTypeDef,
     Mp4SettingsTypeDef,
     MpdSettingsTypeDef,
     HopDestinationTypeDef,
-    ResponseMetadataTypeDef,
     ReservationPlanSettingsTypeDef,
     DashAdditionalManifestTypeDef,
     SpekeKeyProviderTypeDef,
     DashIsoImageBasedTrickPlaySettingsTypeDef,
     DeinterlacerTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsRequestRequestTypeDef,
     EndpointTypeDef,
     DisassociateCertificateRequestRequestTypeDef,
     DolbyVisionLevel6MetadataTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
@@ -832,33 +841,40 @@
     JobMessagesTypeDef,
     KantarWatermarkSettingsTypeDef,
     NielsenConfigurationTypeDef,
     NielsenNonLinearWatermarkSettingsTypeDef,
     TimecodeConfigTypeDef,
     QueueTransitionTypeDef,
     TimingTypeDef,
+    WarningGroupTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ResourceTagsTypeDef,
     M2tsScte35EsamTypeDef,
     MotionImageInsertionFramerateTypeDef,
     MotionImageInsertionOffsetTypeDef,
     Mpeg2SettingsTypeDef,
     MsSmoothAdditionalManifestTypeDef,
     MxfXavcProfileSettingsTypeDef,
     NexGuardFileMarkerSettingsTypeDef,
     NoiseReducerFilterSettingsTypeDef,
     NoiseReducerSpatialFilterSettingsTypeDef,
     NoiseReducerTemporalFilterSettingsTypeDef,
     VideoDetailTypeDef,
+    PaginatorConfigTypeDef,
     ProresSettingsTypeDef,
     ReservationPlanTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationAccessControlTypeDef,
     S3EncryptionSettingsTypeDef,
     TagResourceRequestRequestTypeDef,
     TimecodeBurninTypeDef,
     UntagResourceRequestRequestTypeDef,
     Vc3SettingsTypeDef,
     Vp8SettingsTypeDef,
@@ -879,19 +895,14 @@
     ColorCorrectorTypeDef,
     VideoSelectorTypeDef,
     CreateQueueRequestRequestTypeDef,
     UpdateQueueRequestRequestTypeDef,
     DashIsoEncryptionSettingsTypeDef,
     HlsEncryptionSettingsTypeDef,
     MsSmoothEncryptionSettingsTypeDef,
-    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
     DescribeEndpointsResponseTypeDef,
     DolbyVisionTypeDef,
     EsamSettingsTypeDef,
     GetPolicyResponseTypeDef,
     PutPolicyRequestRequestTypeDef,
     PutPolicyResponseTypeDef,
     H264SettingsTypeDef,
@@ -970,43 +981,43 @@
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/README.md` & `types-aiobotocore-mediaconvert-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediaconvert"></a>
 
 # types-aiobotocore-mediaconvert
 
 [![PyPI - types-aiobotocore-mediaconvert](https://img.shields.io/pypi/v/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconvert?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconvert)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConvert 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
+[aiobotocore.MediaConvert 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
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
 [types-aiobotocore-mediaconvert docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,14 +289,17 @@
     Ac3DynamicRangeCompressionLineType,
     Ac3DynamicRangeCompressionProfileType,
     Ac3DynamicRangeCompressionRfType,
     Ac3LfeFilterType,
     Ac3MetadataControlType,
     AccelerationModeType,
     AccelerationStatusType,
+    AdvancedInputFilterAddTextureType,
+    AdvancedInputFilterSharpenType,
+    AdvancedInputFilterType,
     AfdSignalingType,
     AlphaBehaviorType,
     AncillaryConvert608To708Type,
     AncillaryTerminateCaptionsType,
     AntiAliasType,
     AudioChannelTagType,
     AudioCodecType,
@@ -319,25 +322,28 @@
     AvcIntraFramerateControlType,
     AvcIntraFramerateConversionAlgorithmType,
     AvcIntraInterlaceModeType,
     AvcIntraScanTypeConversionModeType,
     AvcIntraSlowPalType,
     AvcIntraTelecineType,
     AvcIntraUhdQualityTuningLevelType,
+    BandwidthReductionFilterSharpeningType,
+    BandwidthReductionFilterStrengthType,
     BillingTagsSourceType,
     BurnInSubtitleStylePassthroughType,
     BurninSubtitleAlignmentType,
     BurninSubtitleApplyFontColorType,
     BurninSubtitleBackgroundColorType,
     BurninSubtitleFallbackFontType,
     BurninSubtitleFontColorType,
     BurninSubtitleOutlineColorType,
     BurninSubtitleShadowColorType,
     BurninSubtitleTeletextSpacingType,
     CaptionDestinationTypeType,
+    CaptionSourceConvertPaintOnToPopOnType,
     CaptionSourceTypeType,
     CmafClientCacheType,
     CmafCodecSpecificationType,
     CmafEncryptionTypeType,
     CmafImageBasedTrickPlayType,
     CmafInitializationVectorInManifestType,
     CmafIntervalCadenceType,
@@ -482,14 +488,15 @@
     H265SpatialAdaptiveQuantizationType,
     H265TelecineType,
     H265TemporalAdaptiveQuantizationType,
     H265TemporalIdsType,
     H265TilesType,
     H265UnregisteredSeiTimecodeType,
     H265WriteMp4PackagingTypeType,
+    HDRToSDRToneMapperType,
     HlsAdMarkersType,
     HlsAudioOnlyContainerType,
     HlsAudioOnlyHeaderType,
     HlsAudioTrackTypeType,
     HlsCaptionLanguageSettingType,
     HlsCaptionSegmentLengthControlType,
     HlsClientCacheType,
@@ -503,14 +510,15 @@
     HlsIntervalCadenceType,
     HlsKeyProviderTypeType,
     HlsManifestCompressionType,
     HlsManifestDurationFormatType,
     HlsOfflineEncryptedType,
     HlsOutputSelectionType,
     HlsProgramDateTimeType,
+    HlsProgressiveWriteHlsManifestType,
     HlsSegmentControlType,
     HlsSegmentLengthControlType,
     HlsStreamInfResolutionType,
     HlsTargetDurationCompatibilityModeType,
     HlsTimedMetadataId3FrameType,
     ImscAccessibilitySubsType,
     ImscStylePassthroughType,
@@ -702,14 +710,15 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconvert.type_defs import (
     AacSettingsTypeDef,
     Ac3SettingsTypeDef,
     AccelerationSettingsTypeDef,
+    AdvancedInputFilterSettingsTypeDef,
     AiffSettingsTypeDef,
     AllowedRenditionSizeTypeDef,
     AncillarySourceSettingsTypeDef,
     AssociateCertificateRequestRequestTypeDef,
     AudioChannelTaggingSettingsTypeDef,
     Eac3AtmosSettingsTypeDef,
     Eac3SettingsTypeDef,
@@ -723,14 +732,15 @@
     HlsRenditionGroupSettingsTypeDef,
     ForceIncludeRenditionSizeTypeDef,
     MinBottomRenditionSizeTypeDef,
     MinTopRenditionSizeTypeDef,
     Av1QvbrSettingsTypeDef,
     AvailBlankingTypeDef,
     AvcIntraUhdSettingsTypeDef,
+    BandwidthReductionFilterTypeDef,
     BurninDestinationSettingsTypeDef,
     CancelJobRequestRequestTypeDef,
     DvbSubDestinationSettingsTypeDef,
     EmbeddedDestinationSettingsTypeDef,
     ImscDestinationSettingsTypeDef,
     SccDestinationSettingsTypeDef,
     SrtDestinationSettingsTypeDef,
@@ -753,24 +763,23 @@
     Hdr10MetadataTypeDef,
     F4vSettingsTypeDef,
     M3u8SettingsTypeDef,
     MovSettingsTypeDef,
     Mp4SettingsTypeDef,
     MpdSettingsTypeDef,
     HopDestinationTypeDef,
-    ResponseMetadataTypeDef,
     ReservationPlanSettingsTypeDef,
     DashAdditionalManifestTypeDef,
     SpekeKeyProviderTypeDef,
     DashIsoImageBasedTrickPlaySettingsTypeDef,
     DeinterlacerTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsRequestRequestTypeDef,
     EndpointTypeDef,
     DisassociateCertificateRequestRequestTypeDef,
     DolbyVisionLevel6MetadataTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
@@ -799,33 +808,40 @@
     JobMessagesTypeDef,
     KantarWatermarkSettingsTypeDef,
     NielsenConfigurationTypeDef,
     NielsenNonLinearWatermarkSettingsTypeDef,
     TimecodeConfigTypeDef,
     QueueTransitionTypeDef,
     TimingTypeDef,
+    WarningGroupTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ResourceTagsTypeDef,
     M2tsScte35EsamTypeDef,
     MotionImageInsertionFramerateTypeDef,
     MotionImageInsertionOffsetTypeDef,
     Mpeg2SettingsTypeDef,
     MsSmoothAdditionalManifestTypeDef,
     MxfXavcProfileSettingsTypeDef,
     NexGuardFileMarkerSettingsTypeDef,
     NoiseReducerFilterSettingsTypeDef,
     NoiseReducerSpatialFilterSettingsTypeDef,
     NoiseReducerTemporalFilterSettingsTypeDef,
     VideoDetailTypeDef,
+    PaginatorConfigTypeDef,
     ProresSettingsTypeDef,
     ReservationPlanTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationAccessControlTypeDef,
     S3EncryptionSettingsTypeDef,
     TagResourceRequestRequestTypeDef,
     TimecodeBurninTypeDef,
     UntagResourceRequestRequestTypeDef,
     Vc3SettingsTypeDef,
     Vp8SettingsTypeDef,
@@ -846,19 +862,14 @@
     ColorCorrectorTypeDef,
     VideoSelectorTypeDef,
     CreateQueueRequestRequestTypeDef,
     UpdateQueueRequestRequestTypeDef,
     DashIsoEncryptionSettingsTypeDef,
     HlsEncryptionSettingsTypeDef,
     MsSmoothEncryptionSettingsTypeDef,
-    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
     DescribeEndpointsResponseTypeDef,
     DolbyVisionTypeDef,
     EsamSettingsTypeDef,
     GetPolicyResponseTypeDef,
     PutPolicyRequestRequestTypeDef,
     PutPolicyResponseTypeDef,
     H264SettingsTypeDef,
@@ -937,43 +948,43 @@
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/setup.py` & `types-aiobotocore-mediaconvert-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediaconvert.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediaconvert",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediaconvert"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaConvert 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaConvert 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/"
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__init__.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__init__.pyi` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/__main__.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaConvert 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaConvert 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert\nOther"
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/client.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/client.pyi` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/literals.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -32,14 +32,17 @@
     "Ac3DynamicRangeCompressionLineType",
     "Ac3DynamicRangeCompressionProfileType",
     "Ac3DynamicRangeCompressionRfType",
     "Ac3LfeFilterType",
     "Ac3MetadataControlType",
     "AccelerationModeType",
     "AccelerationStatusType",
+    "AdvancedInputFilterAddTextureType",
+    "AdvancedInputFilterSharpenType",
+    "AdvancedInputFilterType",
     "AfdSignalingType",
     "AlphaBehaviorType",
     "AncillaryConvert608To708Type",
     "AncillaryTerminateCaptionsType",
     "AntiAliasType",
     "AudioChannelTagType",
     "AudioCodecType",
@@ -62,25 +65,28 @@
     "AvcIntraFramerateControlType",
     "AvcIntraFramerateConversionAlgorithmType",
     "AvcIntraInterlaceModeType",
     "AvcIntraScanTypeConversionModeType",
     "AvcIntraSlowPalType",
     "AvcIntraTelecineType",
     "AvcIntraUhdQualityTuningLevelType",
+    "BandwidthReductionFilterSharpeningType",
+    "BandwidthReductionFilterStrengthType",
     "BillingTagsSourceType",
     "BurnInSubtitleStylePassthroughType",
     "BurninSubtitleAlignmentType",
     "BurninSubtitleApplyFontColorType",
     "BurninSubtitleBackgroundColorType",
     "BurninSubtitleFallbackFontType",
     "BurninSubtitleFontColorType",
     "BurninSubtitleOutlineColorType",
     "BurninSubtitleShadowColorType",
     "BurninSubtitleTeletextSpacingType",
     "CaptionDestinationTypeType",
+    "CaptionSourceConvertPaintOnToPopOnType",
     "CaptionSourceTypeType",
     "CmafClientCacheType",
     "CmafCodecSpecificationType",
     "CmafEncryptionTypeType",
     "CmafImageBasedTrickPlayType",
     "CmafInitializationVectorInManifestType",
     "CmafIntervalCadenceType",
@@ -225,14 +231,15 @@
     "H265SpatialAdaptiveQuantizationType",
     "H265TelecineType",
     "H265TemporalAdaptiveQuantizationType",
     "H265TemporalIdsType",
     "H265TilesType",
     "H265UnregisteredSeiTimecodeType",
     "H265WriteMp4PackagingTypeType",
+    "HDRToSDRToneMapperType",
     "HlsAdMarkersType",
     "HlsAudioOnlyContainerType",
     "HlsAudioOnlyHeaderType",
     "HlsAudioTrackTypeType",
     "HlsCaptionLanguageSettingType",
     "HlsCaptionSegmentLengthControlType",
     "HlsClientCacheType",
@@ -246,14 +253,15 @@
     "HlsIntervalCadenceType",
     "HlsKeyProviderTypeType",
     "HlsManifestCompressionType",
     "HlsManifestDurationFormatType",
     "HlsOfflineEncryptedType",
     "HlsOutputSelectionType",
     "HlsProgramDateTimeType",
+    "HlsProgressiveWriteHlsManifestType",
     "HlsSegmentControlType",
     "HlsSegmentLengthControlType",
     "HlsStreamInfResolutionType",
     "HlsTargetDurationCompatibilityModeType",
     "HlsTimedMetadataId3FrameType",
     "ImscAccessibilitySubsType",
     "ImscStylePassthroughType",
@@ -462,14 +470,17 @@
 Ac3DynamicRangeCompressionRfType = Literal[
     "FILM_LIGHT", "FILM_STANDARD", "MUSIC_LIGHT", "MUSIC_STANDARD", "NONE", "SPEECH"
 ]
 Ac3LfeFilterType = Literal["DISABLED", "ENABLED"]
 Ac3MetadataControlType = Literal["FOLLOW_INPUT", "USE_CONFIGURED"]
 AccelerationModeType = Literal["DISABLED", "ENABLED", "PREFERRED"]
 AccelerationStatusType = Literal["ACCELERATED", "IN_PROGRESS", "NOT_ACCELERATED", "NOT_APPLICABLE"]
+AdvancedInputFilterAddTextureType = Literal["DISABLED", "ENABLED"]
+AdvancedInputFilterSharpenType = Literal["HIGH", "LOW", "OFF"]
+AdvancedInputFilterType = Literal["DISABLED", "ENABLED"]
 AfdSignalingType = Literal["AUTO", "FIXED", "NONE"]
 AlphaBehaviorType = Literal["DISCARD", "REMAP_TO_LUMA"]
 AncillaryConvert608To708Type = Literal["DISABLED", "UPCONVERT"]
 AncillaryTerminateCaptionsType = Literal["DISABLED", "END_OF_INPUT"]
 AntiAliasType = Literal["DISABLED", "ENABLED"]
 AudioChannelTagType = Literal[
     "C", "CS", "L", "LC", "LFE", "LS", "LSD", "R", "RC", "RS", "RSD", "TCS", "VHC", "VHL", "VHR"
@@ -500,14 +511,16 @@
 AvcIntraInterlaceModeType = Literal[
     "BOTTOM_FIELD", "FOLLOW_BOTTOM_FIELD", "FOLLOW_TOP_FIELD", "PROGRESSIVE", "TOP_FIELD"
 ]
 AvcIntraScanTypeConversionModeType = Literal["INTERLACED", "INTERLACED_OPTIMIZE"]
 AvcIntraSlowPalType = Literal["DISABLED", "ENABLED"]
 AvcIntraTelecineType = Literal["HARD", "NONE"]
 AvcIntraUhdQualityTuningLevelType = Literal["MULTI_PASS", "SINGLE_PASS"]
+BandwidthReductionFilterSharpeningType = Literal["HIGH", "LOW", "MEDIUM", "OFF"]
+BandwidthReductionFilterStrengthType = Literal["AUTO", "HIGH", "LOW", "MEDIUM", "OFF"]
 BillingTagsSourceType = Literal["JOB", "JOB_TEMPLATE", "PRESET", "QUEUE"]
 BurnInSubtitleStylePassthroughType = Literal["DISABLED", "ENABLED"]
 BurninSubtitleAlignmentType = Literal["AUTO", "CENTERED", "LEFT"]
 BurninSubtitleApplyFontColorType = Literal["ALL_TEXT", "WHITE_TEXT_ONLY"]
 BurninSubtitleBackgroundColorType = Literal["AUTO", "BLACK", "NONE", "WHITE"]
 BurninSubtitleFallbackFontType = Literal[
     "BEST_MATCH",
@@ -532,14 +545,15 @@
     "SCTE20_PLUS_EMBEDDED",
     "SMI",
     "SRT",
     "TELETEXT",
     "TTML",
     "WEBVTT",
 ]
+CaptionSourceConvertPaintOnToPopOnType = Literal["DISABLED", "ENABLED"]
 CaptionSourceTypeType = Literal[
     "ANCILLARY",
     "DVB_SUB",
     "EMBEDDED",
     "IMSC",
     "NULL_SOURCE",
     "SCC",
@@ -588,19 +602,22 @@
 CmfcTimedMetadataType = Literal["NONE", "PASSTHROUGH"]
 ColorMetadataType = Literal["IGNORE", "INSERT"]
 ColorSpaceConversionType = Literal[
     "FORCE_601",
     "FORCE_709",
     "FORCE_HDR10",
     "FORCE_HLG_2020",
+    "FORCE_P3D65_HDR",
     "FORCE_P3D65_SDR",
     "FORCE_P3DCI",
     "NONE",
 ]
-ColorSpaceType = Literal["FOLLOW", "HDR10", "HLG_2020", "P3D65_SDR", "P3DCI", "REC_601", "REC_709"]
+ColorSpaceType = Literal[
+    "FOLLOW", "HDR10", "HLG_2020", "P3D65_HDR", "P3D65_SDR", "P3DCI", "REC_601", "REC_709"
+]
 ColorSpaceUsageType = Literal["FALLBACK", "FORCE"]
 CommitmentType = Literal["ONE_YEAR"]
 ContainerTypeType = Literal[
     "CMFC", "F4V", "ISMV", "M2TS", "M3U8", "MOV", "MP4", "MPD", "MXF", "RAW", "WEBM"
 ]
 CopyProtectionActionType = Literal["PASSTHROUGH", "STRIP"]
 DashIsoGroupAudioChannelConfigSchemeIdUriType = Literal[
@@ -615,15 +632,17 @@
 DashIsoPtsOffsetHandlingForBFramesType = Literal["MATCH_INITIAL_PTS", "ZERO_BASED"]
 DashIsoSegmentControlType = Literal["SEGMENTED_FILES", "SINGLE_FILE"]
 DashIsoSegmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 DashIsoVideoCompositionOffsetsType = Literal["SIGNED", "UNSIGNED"]
 DashIsoWriteSegmentTimelineInRepresentationType = Literal["DISABLED", "ENABLED"]
 DashManifestStyleType = Literal["BASIC", "COMPACT", "DISTINCT"]
 DecryptionModeType = Literal["AES_CBC", "AES_CTR", "AES_GCM"]
-DeinterlaceAlgorithmType = Literal["BLEND", "BLEND_TICKER", "INTERPOLATE", "INTERPOLATE_TICKER"]
+DeinterlaceAlgorithmType = Literal[
+    "BLEND", "BLEND_TICKER", "INTERPOLATE", "INTERPOLATE_TICKER", "LINEAR_INTERPOLATION"
+]
 DeinterlacerControlType = Literal["FORCE_ALL_FRAMES", "NORMAL"]
 DeinterlacerModeType = Literal["ADAPTIVE", "DEINTERLACE", "INVERSE_TELECINE"]
 DescribeEndpointsModeType = Literal["DEFAULT", "GET_ONLY"]
 DescribeEndpointsPaginatorName = Literal["describe_endpoints"]
 DolbyVisionLevel6ModeType = Literal["PASSTHROUGH", "RECALCULATE", "SPECIFY"]
 DolbyVisionMappingType = Literal["HDR10_1000", "HDR10_NOMAP"]
 DolbyVisionProfileType = Literal["PROFILE_5", "PROFILE_8_1"]
@@ -785,14 +804,15 @@
 H265SpatialAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 H265TelecineType = Literal["HARD", "NONE", "SOFT"]
 H265TemporalAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 H265TemporalIdsType = Literal["DISABLED", "ENABLED"]
 H265TilesType = Literal["DISABLED", "ENABLED"]
 H265UnregisteredSeiTimecodeType = Literal["DISABLED", "ENABLED"]
 H265WriteMp4PackagingTypeType = Literal["HEV1", "HVC1"]
+HDRToSDRToneMapperType = Literal["PRESERVE_DETAILS", "VIBRANT"]
 HlsAdMarkersType = Literal["ELEMENTAL", "ELEMENTAL_SCTE35"]
 HlsAudioOnlyContainerType = Literal["AUTOMATIC", "M2TS"]
 HlsAudioOnlyHeaderType = Literal["EXCLUDE", "INCLUDE"]
 HlsAudioTrackTypeType = Literal[
     "ALTERNATE_AUDIO_AUTO_SELECT",
     "ALTERNATE_AUDIO_AUTO_SELECT_DEFAULT",
     "ALTERNATE_AUDIO_NOT_AUTO_SELECT",
@@ -811,14 +831,15 @@
 HlsIntervalCadenceType = Literal["FOLLOW_CUSTOM", "FOLLOW_IFRAME"]
 HlsKeyProviderTypeType = Literal["SPEKE", "STATIC_KEY"]
 HlsManifestCompressionType = Literal["GZIP", "NONE"]
 HlsManifestDurationFormatType = Literal["FLOATING_POINT", "INTEGER"]
 HlsOfflineEncryptedType = Literal["DISABLED", "ENABLED"]
 HlsOutputSelectionType = Literal["MANIFESTS_AND_SEGMENTS", "SEGMENTS_ONLY"]
 HlsProgramDateTimeType = Literal["EXCLUDE", "INCLUDE"]
+HlsProgressiveWriteHlsManifestType = Literal["DISABLED", "ENABLED"]
 HlsSegmentControlType = Literal["SEGMENTED_FILES", "SINGLE_FILE"]
 HlsSegmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 HlsStreamInfResolutionType = Literal["EXCLUDE", "INCLUDE"]
 HlsTargetDurationCompatibilityModeType = Literal["LEGACY", "SPEC_COMPLIANT"]
 HlsTimedMetadataId3FrameType = Literal["NONE", "PRIV", "TDRL"]
 ImscAccessibilitySubsType = Literal["DISABLED", "ENABLED"]
 ImscStylePassthroughType = Literal["DISABLED", "ENABLED"]
@@ -1101,15 +1122,15 @@
 Mpeg2SyntaxType = Literal["DEFAULT", "D_10"]
 Mpeg2TelecineType = Literal["HARD", "NONE", "SOFT"]
 Mpeg2TemporalAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 MsSmoothAudioDeduplicationType = Literal["COMBINE_DUPLICATE_STREAMS", "NONE"]
 MsSmoothFragmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 MsSmoothManifestEncodingType = Literal["UTF16", "UTF8"]
 MxfAfdSignalingType = Literal["COPY_FROM_VIDEO", "NO_COPY"]
-MxfProfileType = Literal["D_10", "OP1A", "XAVC", "XDCAM"]
+MxfProfileType = Literal["D_10", "OP1A", "XAVC", "XDCAM", "XDCAM_RDD9"]
 MxfXavcDurationModeType = Literal["ALLOW_ANY_DURATION", "DROP_FRAMES_FOR_COMPLIANCE"]
 NielsenActiveWatermarkProcessTypeType = Literal["CBET", "NAES2_AND_NW", "NAES2_AND_NW_AND_CBET"]
 NielsenSourceWatermarkStatusTypeType = Literal["CLEAN", "WATERMARKED"]
 NielsenUniqueTicPerAudioTrackTypeType = Literal[
     "RESERVE_UNIQUE_TICS_PER_TRACK", "SAME_TICS_PER_TRACK"
 ]
 NoiseFilterPostTemporalSharpeningStrengthType = Literal["HIGH", "LOW", "MEDIUM"]
@@ -1224,14 +1245,15 @@
 VideoCodecType = Literal[
     "AV1",
     "AVC_INTRA",
     "FRAME_CAPTURE",
     "H_264",
     "H_265",
     "MPEG2",
+    "PASSTHROUGH",
     "PRORES",
     "VC3",
     "VP8",
     "VP9",
     "XAVC",
 ]
 VideoTimecodeInsertionType = Literal["DISABLED", "PIC_TIMING_SEI"]
@@ -1334,14 +1356,15 @@
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
@@ -1420,14 +1443,15 @@
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
@@ -1438,14 +1462,15 @@
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
@@ -1481,14 +1506,15 @@
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
@@ -1507,16 +1533,19 @@
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
@@ -1600,15 +1629,17 @@
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/literals.pyi` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -31,14 +31,17 @@
     "Ac3DynamicRangeCompressionLineType",
     "Ac3DynamicRangeCompressionProfileType",
     "Ac3DynamicRangeCompressionRfType",
     "Ac3LfeFilterType",
     "Ac3MetadataControlType",
     "AccelerationModeType",
     "AccelerationStatusType",
+    "AdvancedInputFilterAddTextureType",
+    "AdvancedInputFilterSharpenType",
+    "AdvancedInputFilterType",
     "AfdSignalingType",
     "AlphaBehaviorType",
     "AncillaryConvert608To708Type",
     "AncillaryTerminateCaptionsType",
     "AntiAliasType",
     "AudioChannelTagType",
     "AudioCodecType",
@@ -61,25 +64,28 @@
     "AvcIntraFramerateControlType",
     "AvcIntraFramerateConversionAlgorithmType",
     "AvcIntraInterlaceModeType",
     "AvcIntraScanTypeConversionModeType",
     "AvcIntraSlowPalType",
     "AvcIntraTelecineType",
     "AvcIntraUhdQualityTuningLevelType",
+    "BandwidthReductionFilterSharpeningType",
+    "BandwidthReductionFilterStrengthType",
     "BillingTagsSourceType",
     "BurnInSubtitleStylePassthroughType",
     "BurninSubtitleAlignmentType",
     "BurninSubtitleApplyFontColorType",
     "BurninSubtitleBackgroundColorType",
     "BurninSubtitleFallbackFontType",
     "BurninSubtitleFontColorType",
     "BurninSubtitleOutlineColorType",
     "BurninSubtitleShadowColorType",
     "BurninSubtitleTeletextSpacingType",
     "CaptionDestinationTypeType",
+    "CaptionSourceConvertPaintOnToPopOnType",
     "CaptionSourceTypeType",
     "CmafClientCacheType",
     "CmafCodecSpecificationType",
     "CmafEncryptionTypeType",
     "CmafImageBasedTrickPlayType",
     "CmafInitializationVectorInManifestType",
     "CmafIntervalCadenceType",
@@ -224,14 +230,15 @@
     "H265SpatialAdaptiveQuantizationType",
     "H265TelecineType",
     "H265TemporalAdaptiveQuantizationType",
     "H265TemporalIdsType",
     "H265TilesType",
     "H265UnregisteredSeiTimecodeType",
     "H265WriteMp4PackagingTypeType",
+    "HDRToSDRToneMapperType",
     "HlsAdMarkersType",
     "HlsAudioOnlyContainerType",
     "HlsAudioOnlyHeaderType",
     "HlsAudioTrackTypeType",
     "HlsCaptionLanguageSettingType",
     "HlsCaptionSegmentLengthControlType",
     "HlsClientCacheType",
@@ -245,14 +252,15 @@
     "HlsIntervalCadenceType",
     "HlsKeyProviderTypeType",
     "HlsManifestCompressionType",
     "HlsManifestDurationFormatType",
     "HlsOfflineEncryptedType",
     "HlsOutputSelectionType",
     "HlsProgramDateTimeType",
+    "HlsProgressiveWriteHlsManifestType",
     "HlsSegmentControlType",
     "HlsSegmentLengthControlType",
     "HlsStreamInfResolutionType",
     "HlsTargetDurationCompatibilityModeType",
     "HlsTimedMetadataId3FrameType",
     "ImscAccessibilitySubsType",
     "ImscStylePassthroughType",
@@ -460,14 +468,17 @@
 Ac3DynamicRangeCompressionRfType = Literal[
     "FILM_LIGHT", "FILM_STANDARD", "MUSIC_LIGHT", "MUSIC_STANDARD", "NONE", "SPEECH"
 ]
 Ac3LfeFilterType = Literal["DISABLED", "ENABLED"]
 Ac3MetadataControlType = Literal["FOLLOW_INPUT", "USE_CONFIGURED"]
 AccelerationModeType = Literal["DISABLED", "ENABLED", "PREFERRED"]
 AccelerationStatusType = Literal["ACCELERATED", "IN_PROGRESS", "NOT_ACCELERATED", "NOT_APPLICABLE"]
+AdvancedInputFilterAddTextureType = Literal["DISABLED", "ENABLED"]
+AdvancedInputFilterSharpenType = Literal["HIGH", "LOW", "OFF"]
+AdvancedInputFilterType = Literal["DISABLED", "ENABLED"]
 AfdSignalingType = Literal["AUTO", "FIXED", "NONE"]
 AlphaBehaviorType = Literal["DISCARD", "REMAP_TO_LUMA"]
 AncillaryConvert608To708Type = Literal["DISABLED", "UPCONVERT"]
 AncillaryTerminateCaptionsType = Literal["DISABLED", "END_OF_INPUT"]
 AntiAliasType = Literal["DISABLED", "ENABLED"]
 AudioChannelTagType = Literal[
     "C", "CS", "L", "LC", "LFE", "LS", "LSD", "R", "RC", "RS", "RSD", "TCS", "VHC", "VHL", "VHR"
@@ -498,14 +509,16 @@
 AvcIntraInterlaceModeType = Literal[
     "BOTTOM_FIELD", "FOLLOW_BOTTOM_FIELD", "FOLLOW_TOP_FIELD", "PROGRESSIVE", "TOP_FIELD"
 ]
 AvcIntraScanTypeConversionModeType = Literal["INTERLACED", "INTERLACED_OPTIMIZE"]
 AvcIntraSlowPalType = Literal["DISABLED", "ENABLED"]
 AvcIntraTelecineType = Literal["HARD", "NONE"]
 AvcIntraUhdQualityTuningLevelType = Literal["MULTI_PASS", "SINGLE_PASS"]
+BandwidthReductionFilterSharpeningType = Literal["HIGH", "LOW", "MEDIUM", "OFF"]
+BandwidthReductionFilterStrengthType = Literal["AUTO", "HIGH", "LOW", "MEDIUM", "OFF"]
 BillingTagsSourceType = Literal["JOB", "JOB_TEMPLATE", "PRESET", "QUEUE"]
 BurnInSubtitleStylePassthroughType = Literal["DISABLED", "ENABLED"]
 BurninSubtitleAlignmentType = Literal["AUTO", "CENTERED", "LEFT"]
 BurninSubtitleApplyFontColorType = Literal["ALL_TEXT", "WHITE_TEXT_ONLY"]
 BurninSubtitleBackgroundColorType = Literal["AUTO", "BLACK", "NONE", "WHITE"]
 BurninSubtitleFallbackFontType = Literal[
     "BEST_MATCH",
@@ -530,14 +543,15 @@
     "SCTE20_PLUS_EMBEDDED",
     "SMI",
     "SRT",
     "TELETEXT",
     "TTML",
     "WEBVTT",
 ]
+CaptionSourceConvertPaintOnToPopOnType = Literal["DISABLED", "ENABLED"]
 CaptionSourceTypeType = Literal[
     "ANCILLARY",
     "DVB_SUB",
     "EMBEDDED",
     "IMSC",
     "NULL_SOURCE",
     "SCC",
@@ -586,19 +600,22 @@
 CmfcTimedMetadataType = Literal["NONE", "PASSTHROUGH"]
 ColorMetadataType = Literal["IGNORE", "INSERT"]
 ColorSpaceConversionType = Literal[
     "FORCE_601",
     "FORCE_709",
     "FORCE_HDR10",
     "FORCE_HLG_2020",
+    "FORCE_P3D65_HDR",
     "FORCE_P3D65_SDR",
     "FORCE_P3DCI",
     "NONE",
 ]
-ColorSpaceType = Literal["FOLLOW", "HDR10", "HLG_2020", "P3D65_SDR", "P3DCI", "REC_601", "REC_709"]
+ColorSpaceType = Literal[
+    "FOLLOW", "HDR10", "HLG_2020", "P3D65_HDR", "P3D65_SDR", "P3DCI", "REC_601", "REC_709"
+]
 ColorSpaceUsageType = Literal["FALLBACK", "FORCE"]
 CommitmentType = Literal["ONE_YEAR"]
 ContainerTypeType = Literal[
     "CMFC", "F4V", "ISMV", "M2TS", "M3U8", "MOV", "MP4", "MPD", "MXF", "RAW", "WEBM"
 ]
 CopyProtectionActionType = Literal["PASSTHROUGH", "STRIP"]
 DashIsoGroupAudioChannelConfigSchemeIdUriType = Literal[
@@ -613,15 +630,17 @@
 DashIsoPtsOffsetHandlingForBFramesType = Literal["MATCH_INITIAL_PTS", "ZERO_BASED"]
 DashIsoSegmentControlType = Literal["SEGMENTED_FILES", "SINGLE_FILE"]
 DashIsoSegmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 DashIsoVideoCompositionOffsetsType = Literal["SIGNED", "UNSIGNED"]
 DashIsoWriteSegmentTimelineInRepresentationType = Literal["DISABLED", "ENABLED"]
 DashManifestStyleType = Literal["BASIC", "COMPACT", "DISTINCT"]
 DecryptionModeType = Literal["AES_CBC", "AES_CTR", "AES_GCM"]
-DeinterlaceAlgorithmType = Literal["BLEND", "BLEND_TICKER", "INTERPOLATE", "INTERPOLATE_TICKER"]
+DeinterlaceAlgorithmType = Literal[
+    "BLEND", "BLEND_TICKER", "INTERPOLATE", "INTERPOLATE_TICKER", "LINEAR_INTERPOLATION"
+]
 DeinterlacerControlType = Literal["FORCE_ALL_FRAMES", "NORMAL"]
 DeinterlacerModeType = Literal["ADAPTIVE", "DEINTERLACE", "INVERSE_TELECINE"]
 DescribeEndpointsModeType = Literal["DEFAULT", "GET_ONLY"]
 DescribeEndpointsPaginatorName = Literal["describe_endpoints"]
 DolbyVisionLevel6ModeType = Literal["PASSTHROUGH", "RECALCULATE", "SPECIFY"]
 DolbyVisionMappingType = Literal["HDR10_1000", "HDR10_NOMAP"]
 DolbyVisionProfileType = Literal["PROFILE_5", "PROFILE_8_1"]
@@ -783,14 +802,15 @@
 H265SpatialAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 H265TelecineType = Literal["HARD", "NONE", "SOFT"]
 H265TemporalAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 H265TemporalIdsType = Literal["DISABLED", "ENABLED"]
 H265TilesType = Literal["DISABLED", "ENABLED"]
 H265UnregisteredSeiTimecodeType = Literal["DISABLED", "ENABLED"]
 H265WriteMp4PackagingTypeType = Literal["HEV1", "HVC1"]
+HDRToSDRToneMapperType = Literal["PRESERVE_DETAILS", "VIBRANT"]
 HlsAdMarkersType = Literal["ELEMENTAL", "ELEMENTAL_SCTE35"]
 HlsAudioOnlyContainerType = Literal["AUTOMATIC", "M2TS"]
 HlsAudioOnlyHeaderType = Literal["EXCLUDE", "INCLUDE"]
 HlsAudioTrackTypeType = Literal[
     "ALTERNATE_AUDIO_AUTO_SELECT",
     "ALTERNATE_AUDIO_AUTO_SELECT_DEFAULT",
     "ALTERNATE_AUDIO_NOT_AUTO_SELECT",
@@ -809,14 +829,15 @@
 HlsIntervalCadenceType = Literal["FOLLOW_CUSTOM", "FOLLOW_IFRAME"]
 HlsKeyProviderTypeType = Literal["SPEKE", "STATIC_KEY"]
 HlsManifestCompressionType = Literal["GZIP", "NONE"]
 HlsManifestDurationFormatType = Literal["FLOATING_POINT", "INTEGER"]
 HlsOfflineEncryptedType = Literal["DISABLED", "ENABLED"]
 HlsOutputSelectionType = Literal["MANIFESTS_AND_SEGMENTS", "SEGMENTS_ONLY"]
 HlsProgramDateTimeType = Literal["EXCLUDE", "INCLUDE"]
+HlsProgressiveWriteHlsManifestType = Literal["DISABLED", "ENABLED"]
 HlsSegmentControlType = Literal["SEGMENTED_FILES", "SINGLE_FILE"]
 HlsSegmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 HlsStreamInfResolutionType = Literal["EXCLUDE", "INCLUDE"]
 HlsTargetDurationCompatibilityModeType = Literal["LEGACY", "SPEC_COMPLIANT"]
 HlsTimedMetadataId3FrameType = Literal["NONE", "PRIV", "TDRL"]
 ImscAccessibilitySubsType = Literal["DISABLED", "ENABLED"]
 ImscStylePassthroughType = Literal["DISABLED", "ENABLED"]
@@ -1099,15 +1120,15 @@
 Mpeg2SyntaxType = Literal["DEFAULT", "D_10"]
 Mpeg2TelecineType = Literal["HARD", "NONE", "SOFT"]
 Mpeg2TemporalAdaptiveQuantizationType = Literal["DISABLED", "ENABLED"]
 MsSmoothAudioDeduplicationType = Literal["COMBINE_DUPLICATE_STREAMS", "NONE"]
 MsSmoothFragmentLengthControlType = Literal["EXACT", "GOP_MULTIPLE"]
 MsSmoothManifestEncodingType = Literal["UTF16", "UTF8"]
 MxfAfdSignalingType = Literal["COPY_FROM_VIDEO", "NO_COPY"]
-MxfProfileType = Literal["D_10", "OP1A", "XAVC", "XDCAM"]
+MxfProfileType = Literal["D_10", "OP1A", "XAVC", "XDCAM", "XDCAM_RDD9"]
 MxfXavcDurationModeType = Literal["ALLOW_ANY_DURATION", "DROP_FRAMES_FOR_COMPLIANCE"]
 NielsenActiveWatermarkProcessTypeType = Literal["CBET", "NAES2_AND_NW", "NAES2_AND_NW_AND_CBET"]
 NielsenSourceWatermarkStatusTypeType = Literal["CLEAN", "WATERMARKED"]
 NielsenUniqueTicPerAudioTrackTypeType = Literal[
     "RESERVE_UNIQUE_TICS_PER_TRACK", "SAME_TICS_PER_TRACK"
 ]
 NoiseFilterPostTemporalSharpeningStrengthType = Literal["HIGH", "LOW", "MEDIUM"]
@@ -1222,14 +1243,15 @@
 VideoCodecType = Literal[
     "AV1",
     "AVC_INTRA",
     "FRAME_CAPTURE",
     "H_264",
     "H_265",
     "MPEG2",
+    "PASSTHROUGH",
     "PRORES",
     "VC3",
     "VP8",
     "VP9",
     "XAVC",
 ]
 VideoTimecodeInsertionType = Literal["DISABLED", "PIC_TIMING_SEI"]
@@ -1332,14 +1354,15 @@
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
@@ -1418,14 +1441,15 @@
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
@@ -1436,14 +1460,15 @@
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
@@ -1479,14 +1504,15 @@
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
@@ -1505,16 +1531,19 @@
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
@@ -1598,15 +1627,17 @@
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/paginator.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_endpoints_paginator: DescribeEndpointsPaginator = client.get_paginator("describe_endpoints")
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_presets_paginator: ListPresetsPaginator = client.get_paginator("list_presets")
         list_queues_paginator: ListQueuesPaginator = client.get_paginator("list_queues")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     DescribeEndpointsModeType,
     JobStatusType,
@@ -47,20 +46,14 @@
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListPresetsResponseTypeDef,
     ListQueuesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeEndpointsPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
     "ListPresetsPaginator",
     "ListQueuesPaginator",
 )
@@ -82,15 +75,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#describeendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Mode: DescribeEndpointsModeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.DescribeEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#describeendpointspaginator)
         """
 
 
@@ -102,15 +95,15 @@
 
     def paginate(
         self,
         *,
         Category: str = ...,
         ListBy: JobTemplateListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listjobtemplatespaginator)
         """
 
 
@@ -122,15 +115,15 @@
 
     def paginate(
         self,
         *,
         Order: OrderType = ...,
         Queue: str = ...,
         Status: JobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listjobspaginator)
         """
 
 
@@ -142,15 +135,15 @@
 
     def paginate(
         self,
         *,
         Category: str = ...,
         ListBy: PresetListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPresetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListPresets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listpresetspaginator)
         """
 
 
@@ -161,13 +154,13 @@
     """
 
     def paginate(
         self,
         *,
         ListBy: QueueListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listqueuespaginator)
         """
```

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/paginator.pyi` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_endpoints_paginator: DescribeEndpointsPaginator = client.get_paginator("describe_endpoints")
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_presets_paginator: ListPresetsPaginator = client.get_paginator("list_presets")
         list_queues_paginator: ListQueuesPaginator = client.get_paginator("list_queues")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     DescribeEndpointsModeType,
     JobStatusType,
@@ -47,19 +46,14 @@
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListPresetsResponseTypeDef,
     ListQueuesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeEndpointsPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
     "ListPresetsPaginator",
     "ListQueuesPaginator",
 )
@@ -78,15 +72,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#describeendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Mode: DescribeEndpointsModeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.DescribeEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#describeendpointspaginator)
         """
 
 class ListJobTemplatesPaginator(AioPaginator):
@@ -97,15 +91,15 @@
 
     def paginate(
         self,
         *,
         Category: str = ...,
         ListBy: JobTemplateListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listjobtemplatespaginator)
         """
 
 class ListJobsPaginator(AioPaginator):
@@ -116,15 +110,15 @@
 
     def paginate(
         self,
         *,
         Order: OrderType = ...,
         Queue: str = ...,
         Status: JobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listjobspaginator)
         """
 
 class ListPresetsPaginator(AioPaginator):
@@ -135,15 +129,15 @@
 
     def paginate(
         self,
         *,
         Category: str = ...,
         ListBy: PresetListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPresetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListPresets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listpresetspaginator)
         """
 
 class ListQueuesPaginator(AioPaginator):
@@ -153,13 +147,13 @@
     """
 
     def paginate(
         self,
         *,
         ListBy: QueueListByType = ...,
         Order: OrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert.Paginator.ListQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/paginators/#listqueuespaginator)
         """
```

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/type_defs.py` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -28,14 +28,17 @@
     Ac3DynamicRangeCompressionLineType,
     Ac3DynamicRangeCompressionProfileType,
     Ac3DynamicRangeCompressionRfType,
     Ac3LfeFilterType,
     Ac3MetadataControlType,
     AccelerationModeType,
     AccelerationStatusType,
+    AdvancedInputFilterAddTextureType,
+    AdvancedInputFilterSharpenType,
+    AdvancedInputFilterType,
     AfdSignalingType,
     AlphaBehaviorType,
     AncillaryConvert608To708Type,
     AncillaryTerminateCaptionsType,
     AntiAliasType,
     AudioChannelTagType,
     AudioCodecType,
@@ -57,25 +60,28 @@
     AvcIntraFramerateControlType,
     AvcIntraFramerateConversionAlgorithmType,
     AvcIntraInterlaceModeType,
     AvcIntraScanTypeConversionModeType,
     AvcIntraSlowPalType,
     AvcIntraTelecineType,
     AvcIntraUhdQualityTuningLevelType,
+    BandwidthReductionFilterSharpeningType,
+    BandwidthReductionFilterStrengthType,
     BillingTagsSourceType,
     BurninSubtitleAlignmentType,
     BurninSubtitleApplyFontColorType,
     BurninSubtitleBackgroundColorType,
     BurninSubtitleFallbackFontType,
     BurninSubtitleFontColorType,
     BurninSubtitleOutlineColorType,
     BurninSubtitleShadowColorType,
     BurnInSubtitleStylePassthroughType,
     BurninSubtitleTeletextSpacingType,
     CaptionDestinationTypeType,
+    CaptionSourceConvertPaintOnToPopOnType,
     CaptionSourceTypeType,
     CmafClientCacheType,
     CmafCodecSpecificationType,
     CmafEncryptionTypeType,
     CmafImageBasedTrickPlayType,
     CmafInitializationVectorInManifestType,
     CmafIntervalCadenceType,
@@ -217,14 +223,15 @@
     H265SpatialAdaptiveQuantizationType,
     H265TelecineType,
     H265TemporalAdaptiveQuantizationType,
     H265TemporalIdsType,
     H265TilesType,
     H265UnregisteredSeiTimecodeType,
     H265WriteMp4PackagingTypeType,
+    HDRToSDRToneMapperType,
     HlsAdMarkersType,
     HlsAudioOnlyContainerType,
     HlsAudioOnlyHeaderType,
     HlsAudioTrackTypeType,
     HlsCaptionLanguageSettingType,
     HlsCaptionSegmentLengthControlType,
     HlsClientCacheType,
@@ -238,14 +245,15 @@
     HlsIntervalCadenceType,
     HlsKeyProviderTypeType,
     HlsManifestCompressionType,
     HlsManifestDurationFormatType,
     HlsOfflineEncryptedType,
     HlsOutputSelectionType,
     HlsProgramDateTimeType,
+    HlsProgressiveWriteHlsManifestType,
     HlsSegmentControlType,
     HlsSegmentLengthControlType,
     HlsStreamInfResolutionType,
     HlsTargetDurationCompatibilityModeType,
     HlsTimedMetadataId3FrameType,
     ImscAccessibilitySubsType,
     ImscStylePassthroughType,
@@ -423,14 +431,15 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AacSettingsTypeDef",
     "Ac3SettingsTypeDef",
     "AccelerationSettingsTypeDef",
+    "AdvancedInputFilterSettingsTypeDef",
     "AiffSettingsTypeDef",
     "AllowedRenditionSizeTypeDef",
     "AncillarySourceSettingsTypeDef",
     "AssociateCertificateRequestRequestTypeDef",
     "AudioChannelTaggingSettingsTypeDef",
     "Eac3AtmosSettingsTypeDef",
     "Eac3SettingsTypeDef",
@@ -444,14 +453,15 @@
     "HlsRenditionGroupSettingsTypeDef",
     "ForceIncludeRenditionSizeTypeDef",
     "MinBottomRenditionSizeTypeDef",
     "MinTopRenditionSizeTypeDef",
     "Av1QvbrSettingsTypeDef",
     "AvailBlankingTypeDef",
     "AvcIntraUhdSettingsTypeDef",
+    "BandwidthReductionFilterTypeDef",
     "BurninDestinationSettingsTypeDef",
     "CancelJobRequestRequestTypeDef",
     "DvbSubDestinationSettingsTypeDef",
     "EmbeddedDestinationSettingsTypeDef",
     "ImscDestinationSettingsTypeDef",
     "SccDestinationSettingsTypeDef",
     "SrtDestinationSettingsTypeDef",
@@ -474,24 +484,23 @@
     "Hdr10MetadataTypeDef",
     "F4vSettingsTypeDef",
     "M3u8SettingsTypeDef",
     "MovSettingsTypeDef",
     "Mp4SettingsTypeDef",
     "MpdSettingsTypeDef",
     "HopDestinationTypeDef",
-    "ResponseMetadataTypeDef",
     "ReservationPlanSettingsTypeDef",
     "DashAdditionalManifestTypeDef",
     "SpekeKeyProviderTypeDef",
     "DashIsoImageBasedTrickPlaySettingsTypeDef",
     "DeinterlacerTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
     "DeletePresetRequestRequestTypeDef",
     "DeleteQueueRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
     "DescribeEndpointsRequestRequestTypeDef",
     "EndpointTypeDef",
     "DisassociateCertificateRequestRequestTypeDef",
     "DolbyVisionLevel6MetadataTypeDef",
     "DvbNitSettingsTypeDef",
     "DvbSdtSettingsTypeDef",
     "DvbTdtSettingsTypeDef",
@@ -520,33 +529,40 @@
     "JobMessagesTypeDef",
     "KantarWatermarkSettingsTypeDef",
     "NielsenConfigurationTypeDef",
     "NielsenNonLinearWatermarkSettingsTypeDef",
     "TimecodeConfigTypeDef",
     "QueueTransitionTypeDef",
     "TimingTypeDef",
+    "WarningGroupTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListPresetsRequestListPresetsPaginateTypeDef",
     "ListPresetsRequestRequestTypeDef",
+    "ListQueuesRequestListQueuesPaginateTypeDef",
     "ListQueuesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ResourceTagsTypeDef",
     "M2tsScte35EsamTypeDef",
     "MotionImageInsertionFramerateTypeDef",
     "MotionImageInsertionOffsetTypeDef",
     "Mpeg2SettingsTypeDef",
     "MsSmoothAdditionalManifestTypeDef",
     "MxfXavcProfileSettingsTypeDef",
     "NexGuardFileMarkerSettingsTypeDef",
     "NoiseReducerFilterSettingsTypeDef",
     "NoiseReducerSpatialFilterSettingsTypeDef",
     "NoiseReducerTemporalFilterSettingsTypeDef",
     "VideoDetailTypeDef",
+    "PaginatorConfigTypeDef",
     "ProresSettingsTypeDef",
     "ReservationPlanTypeDef",
+    "ResponseMetadataTypeDef",
     "S3DestinationAccessControlTypeDef",
     "S3EncryptionSettingsTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TimecodeBurninTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "Vc3SettingsTypeDef",
     "Vp8SettingsTypeDef",
@@ -567,19 +583,14 @@
     "ColorCorrectorTypeDef",
     "VideoSelectorTypeDef",
     "CreateQueueRequestRequestTypeDef",
     "UpdateQueueRequestRequestTypeDef",
     "DashIsoEncryptionSettingsTypeDef",
     "HlsEncryptionSettingsTypeDef",
     "MsSmoothEncryptionSettingsTypeDef",
-    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    "ListQueuesRequestListQueuesPaginateTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "DolbyVisionTypeDef",
     "EsamSettingsTypeDef",
     "GetPolicyResponseTypeDef",
     "PutPolicyRequestRequestTypeDef",
     "PutPolicyResponseTypeDef",
     "H264SettingsTypeDef",
@@ -686,14 +697,23 @@
 AccelerationSettingsTypeDef = TypedDict(
     "AccelerationSettingsTypeDef",
     {
         "Mode": AccelerationModeType,
     },
 )
 
+AdvancedInputFilterSettingsTypeDef = TypedDict(
+    "AdvancedInputFilterSettingsTypeDef",
+    {
+        "AddTexture": AdvancedInputFilterAddTextureType,
+        "Sharpening": AdvancedInputFilterSharpenType,
+    },
+    total=False,
+)
+
 AiffSettingsTypeDef = TypedDict(
     "AiffSettingsTypeDef",
     {
         "BitDepth": int,
         "Channels": int,
         "SampleRate": int,
     },
@@ -920,14 +940,23 @@
     "AvcIntraUhdSettingsTypeDef",
     {
         "QualityTuningLevel": AvcIntraUhdQualityTuningLevelType,
     },
     total=False,
 )
 
+BandwidthReductionFilterTypeDef = TypedDict(
+    "BandwidthReductionFilterTypeDef",
+    {
+        "Sharpening": BandwidthReductionFilterSharpeningType,
+        "Strength": BandwidthReductionFilterStrengthType,
+    },
+    total=False,
+)
+
 BurninDestinationSettingsTypeDef = TypedDict(
     "BurninDestinationSettingsTypeDef",
     {
         "Alignment": BurninSubtitleAlignmentType,
         "ApplyFontColor": BurninSubtitleApplyFontColorType,
         "BackgroundColor": BurninSubtitleBackgroundColorType,
         "BackgroundOpacity": int,
@@ -1295,25 +1324,14 @@
         "Priority": int,
         "Queue": str,
         "WaitMinutes": int,
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
 ReservationPlanSettingsTypeDef = TypedDict(
     "ReservationPlanSettingsTypeDef",
     {
         "Commitment": Literal["ONE_YEAR"],
         "RenewalType": RenewalTypeType,
         "ReservedSlots": int,
     },
@@ -1379,20 +1397,19 @@
 DeleteQueueRequestRequestTypeDef = TypedDict(
     "DeleteQueueRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef = TypedDict(
+    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Mode": DescribeEndpointsModeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEndpointsRequestRequestTypeDef = TypedDict(
     "DescribeEndpointsRequestRequestTypeDef",
     {
@@ -1755,50 +1772,101 @@
         "FinishTime": datetime,
         "StartTime": datetime,
         "SubmitTime": datetime,
     },
     total=False,
 )
 
+WarningGroupTypeDef = TypedDict(
+    "WarningGroupTypeDef",
+    {
+        "Code": int,
+        "Count": int,
+    },
+)
+
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "Category": str,
+        "ListBy": JobTemplateListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "Category": str,
         "ListBy": JobTemplateListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "Order": OrderType,
+        "Queue": str,
+        "Status": JobStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
         "Queue": str,
         "Status": JobStatusType,
     },
     total=False,
 )
 
+ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
+    "ListPresetsRequestListPresetsPaginateTypeDef",
+    {
+        "Category": str,
+        "ListBy": PresetListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPresetsRequestRequestTypeDef = TypedDict(
     "ListPresetsRequestRequestTypeDef",
     {
         "Category": str,
         "ListBy": PresetListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
     },
     total=False,
 )
 
+ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
+    "ListQueuesRequestListQueuesPaginateTypeDef",
+    {
+        "ListBy": QueueListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueuesRequestRequestTypeDef = TypedDict(
     "ListQueuesRequestRequestTypeDef",
     {
         "ListBy": QueueListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
@@ -1952,14 +2020,24 @@
     {
         "HeightInPx": int,
         "WidthInPx": int,
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
 ProresSettingsTypeDef = TypedDict(
     "ProresSettingsTypeDef",
     {
         "ChromaSampling": ProresChromaSamplingType,
         "CodecProfile": ProresCodecProfileType,
         "FramerateControl": ProresFramerateControlType,
         "FramerateConversionAlgorithm": ProresFramerateConversionAlgorithmType,
@@ -1985,14 +2063,25 @@
         "RenewalType": RenewalTypeType,
         "ReservedSlots": int,
         "Status": ReservationPlanStatusType,
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
 S3DestinationAccessControlTypeDef = TypedDict(
     "S3DestinationAccessControlTypeDef",
     {
         "CannedAcl": S3ObjectCannedAclType,
     },
     total=False,
 )
@@ -2241,14 +2330,15 @@
     total=False,
 )
 
 FileSourceSettingsTypeDef = TypedDict(
     "FileSourceSettingsTypeDef",
     {
         "Convert608To708": FileSourceConvert608To708Type,
+        "ConvertPaintToPop": CaptionSourceConvertPaintOnToPopOnType,
         "Framerate": CaptionSourceFramerateTypeDef,
         "SourceFile": str,
         "TimeDelta": int,
         "TimeDeltaUnits": FileSourceTimeDeltaUnitsType,
     },
     total=False,
 )
@@ -2278,14 +2368,15 @@
     "ColorCorrectorTypeDef",
     {
         "Brightness": int,
         "ClipLimits": ClipLimitsTypeDef,
         "ColorSpaceConversion": ColorSpaceConversionType,
         "Contrast": int,
         "Hdr10Metadata": Hdr10MetadataTypeDef,
+        "HdrToSdrToneMapper": HDRToSDRToneMapperType,
         "Hue": int,
         "SampleRangeConversion": SampleRangeConversionType,
         "Saturation": int,
         "SdrReferenceWhiteLevel": int,
     },
     total=False,
 )
@@ -2382,72 +2473,20 @@
     "MsSmoothEncryptionSettingsTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
     },
     total=False,
 )
 
-DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef = TypedDict(
-    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
-    {
-        "Mode": DescribeEndpointsModeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "Category": str,
-        "ListBy": JobTemplateListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "Order": OrderType,
-        "Queue": str,
-        "Status": JobStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    {
-        "Category": str,
-        "ListBy": PresetListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
-    "ListQueuesRequestListQueuesPaginateTypeDef",
-    {
-        "ListBy": QueueListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DolbyVisionTypeDef = TypedDict(
     "DolbyVisionTypeDef",
     {
         "L6Metadata": DolbyVisionLevel6MetadataTypeDef,
@@ -2468,37 +2507,38 @@
     total=False,
 )
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPolicyRequestRequestTypeDef = TypedDict(
     "PutPolicyRequestRequestTypeDef",
     {
         "Policy": PolicyTypeDef,
     },
 )
 
 PutPolicyResponseTypeDef = TypedDict(
     "PutPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 H264SettingsTypeDef = TypedDict(
     "H264SettingsTypeDef",
     {
         "AdaptiveQuantization": H264AdaptiveQuantizationType,
+        "BandwidthReductionFilter": BandwidthReductionFilterTypeDef,
         "Bitrate": int,
         "CodecLevel": H264CodecLevelType,
         "CodecProfile": H264CodecProfileType,
         "DynamicSubGop": H264DynamicSubGopType,
         "EntropyEncoding": H264EntropyEncodingType,
         "FieldEncoding": H264FieldEncodingType,
         "FlickerAdaptiveQuantization": H264FlickerAdaptiveQuantizationType,
@@ -2540,14 +2580,15 @@
 )
 
 H265SettingsTypeDef = TypedDict(
     "H265SettingsTypeDef",
     {
         "AdaptiveQuantization": H265AdaptiveQuantizationType,
         "AlternateTransferFunctionSei": H265AlternateTransferFunctionSeiType,
+        "BandwidthReductionFilter": BandwidthReductionFilterTypeDef,
         "Bitrate": int,
         "CodecLevel": H265CodecLevelType,
         "CodecProfile": H265CodecProfileType,
         "DynamicSubGop": H265DynamicSubGopType,
         "FlickerAdaptiveQuantization": H265FlickerAdaptiveQuantizationType,
         "FramerateControl": H265FramerateControlType,
         "FramerateConversionAlgorithm": H265FramerateConversionAlgorithmType,
@@ -2612,15 +2653,15 @@
     total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceTags": ResourceTagsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 M2tsSettingsTypeDef = TypedDict(
     "M2tsSettingsTypeDef",
     {
         "AudioBufferModel": M2tsAudioBufferModelType,
@@ -2875,40 +2916,40 @@
     total=False,
 )
 
 CreateQueueResponseTypeDef = TypedDict(
     "CreateQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueueResponseTypeDef = TypedDict(
     "GetQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueuesResponseTypeDef = TypedDict(
     "ListQueuesResponseTypeDef",
     {
         "NextToken": str,
         "Queues": List[QueueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateQueueResponseTypeDef = TypedDict(
     "UpdateQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationSettingsTypeDef = TypedDict(
     "DestinationSettingsTypeDef",
     {
         "S3Settings": S3DestinationSettingsTypeDef,
@@ -3082,14 +3123,15 @@
         "ManifestCompression": HlsManifestCompressionType,
         "ManifestDurationFormat": HlsManifestDurationFormatType,
         "MinFinalSegmentLength": float,
         "MinSegmentLength": int,
         "OutputSelection": HlsOutputSelectionType,
         "ProgramDateTime": HlsProgramDateTimeType,
         "ProgramDateTimePeriod": int,
+        "ProgressiveWriteHlsManifest": HlsProgressiveWriteHlsManifestType,
         "SegmentControl": HlsSegmentControlType,
         "SegmentLength": int,
         "SegmentLengthControl": HlsSegmentLengthControlType,
         "SegmentsPerSubdirectory": int,
         "StreamInfResolution": HlsStreamInfResolutionType,
         "TargetDurationCompatibilityMode": HlsTargetDurationCompatibilityModeType,
         "TimedMetadataId3Frame": HlsTimedMetadataId3FrameType,
@@ -3135,14 +3177,16 @@
     },
     total=False,
 )
 
 InputTemplateTypeDef = TypedDict(
     "InputTemplateTypeDef",
     {
+        "AdvancedInputFilter": AdvancedInputFilterType,
+        "AdvancedInputFilterSettings": AdvancedInputFilterSettingsTypeDef,
         "AudioSelectorGroups": Mapping[str, AudioSelectorGroupTypeDef],
         "AudioSelectors": Mapping[str, AudioSelectorTypeDef],
         "CaptionSelectors": Mapping[str, CaptionSelectorTypeDef],
         "Crop": RectangleTypeDef,
         "DeblockFilter": InputDeblockFilterType,
         "DenoiseFilter": InputDenoiseFilterType,
         "DolbyVisionMetadataXml": str,
@@ -3160,14 +3204,16 @@
     },
     total=False,
 )
 
 InputTypeDef = TypedDict(
     "InputTypeDef",
     {
+        "AdvancedInputFilter": AdvancedInputFilterType,
+        "AdvancedInputFilterSettings": AdvancedInputFilterSettingsTypeDef,
         "AudioSelectorGroups": Mapping[str, AudioSelectorGroupTypeDef],
         "AudioSelectors": Mapping[str, AudioSelectorTypeDef],
         "CaptionSelectors": Mapping[str, CaptionSelectorTypeDef],
         "Crop": RectangleTypeDef,
         "DeblockFilter": InputDeblockFilterType,
         "DecryptionSettings": InputDecryptionSettingsTypeDef,
         "DenoiseFilter": InputDenoiseFilterType,
@@ -3351,40 +3397,40 @@
     total=False,
 )
 
 CreatePresetResponseTypeDef = TypedDict(
     "CreatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPresetResponseTypeDef = TypedDict(
     "GetPresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPresetsResponseTypeDef = TypedDict(
     "ListPresetsResponseTypeDef",
     {
         "NextToken": str,
         "Presets": List[PresetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePresetResponseTypeDef = TypedDict(
     "UpdatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "Role": str,
@@ -3426,14 +3472,15 @@
 _OptionalJobTypeDef = TypedDict(
     "_OptionalJobTypeDef",
     {
         "AccelerationSettings": AccelerationSettingsTypeDef,
         "AccelerationStatus": AccelerationStatusType,
         "Arn": str,
         "BillingTagsSource": BillingTagsSourceType,
+        "ClientRequestToken": str,
         "CreatedAt": datetime,
         "CurrentPhase": JobPhaseType,
         "ErrorCode": int,
         "ErrorMessage": str,
         "HopDestinations": List[HopDestinationTypeDef],
         "Id": str,
         "JobPercentComplete": int,
@@ -3445,14 +3492,15 @@
         "QueueTransitions": List[QueueTransitionTypeDef],
         "RetryCount": int,
         "SimulateReservedQueue": SimulateReservedQueueType,
         "Status": JobStatusType,
         "StatusUpdateInterval": StatusUpdateIntervalType,
         "Timing": TimingTypeDef,
         "UserMetadata": Dict[str, str],
+        "Warnings": List[WarningGroupTypeDef],
     },
     total=False,
 )
 
 
 class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
     pass
@@ -3545,60 +3593,60 @@
     pass
 
 
 CreateJobResponseTypeDef = TypedDict(
     "CreateJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJobTemplateResponseTypeDef = TypedDict(
     "CreateJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobTemplateResponseTypeDef = TypedDict(
     "GetJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "JobTemplates": List[JobTemplateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobTemplateResponseTypeDef = TypedDict(
     "UpdateJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert/type_defs.pyi` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -28,14 +28,17 @@
     Ac3DynamicRangeCompressionLineType,
     Ac3DynamicRangeCompressionProfileType,
     Ac3DynamicRangeCompressionRfType,
     Ac3LfeFilterType,
     Ac3MetadataControlType,
     AccelerationModeType,
     AccelerationStatusType,
+    AdvancedInputFilterAddTextureType,
+    AdvancedInputFilterSharpenType,
+    AdvancedInputFilterType,
     AfdSignalingType,
     AlphaBehaviorType,
     AncillaryConvert608To708Type,
     AncillaryTerminateCaptionsType,
     AntiAliasType,
     AudioChannelTagType,
     AudioCodecType,
@@ -57,25 +60,28 @@
     AvcIntraFramerateControlType,
     AvcIntraFramerateConversionAlgorithmType,
     AvcIntraInterlaceModeType,
     AvcIntraScanTypeConversionModeType,
     AvcIntraSlowPalType,
     AvcIntraTelecineType,
     AvcIntraUhdQualityTuningLevelType,
+    BandwidthReductionFilterSharpeningType,
+    BandwidthReductionFilterStrengthType,
     BillingTagsSourceType,
     BurninSubtitleAlignmentType,
     BurninSubtitleApplyFontColorType,
     BurninSubtitleBackgroundColorType,
     BurninSubtitleFallbackFontType,
     BurninSubtitleFontColorType,
     BurninSubtitleOutlineColorType,
     BurninSubtitleShadowColorType,
     BurnInSubtitleStylePassthroughType,
     BurninSubtitleTeletextSpacingType,
     CaptionDestinationTypeType,
+    CaptionSourceConvertPaintOnToPopOnType,
     CaptionSourceTypeType,
     CmafClientCacheType,
     CmafCodecSpecificationType,
     CmafEncryptionTypeType,
     CmafImageBasedTrickPlayType,
     CmafInitializationVectorInManifestType,
     CmafIntervalCadenceType,
@@ -217,14 +223,15 @@
     H265SpatialAdaptiveQuantizationType,
     H265TelecineType,
     H265TemporalAdaptiveQuantizationType,
     H265TemporalIdsType,
     H265TilesType,
     H265UnregisteredSeiTimecodeType,
     H265WriteMp4PackagingTypeType,
+    HDRToSDRToneMapperType,
     HlsAdMarkersType,
     HlsAudioOnlyContainerType,
     HlsAudioOnlyHeaderType,
     HlsAudioTrackTypeType,
     HlsCaptionLanguageSettingType,
     HlsCaptionSegmentLengthControlType,
     HlsClientCacheType,
@@ -238,14 +245,15 @@
     HlsIntervalCadenceType,
     HlsKeyProviderTypeType,
     HlsManifestCompressionType,
     HlsManifestDurationFormatType,
     HlsOfflineEncryptedType,
     HlsOutputSelectionType,
     HlsProgramDateTimeType,
+    HlsProgressiveWriteHlsManifestType,
     HlsSegmentControlType,
     HlsSegmentLengthControlType,
     HlsStreamInfResolutionType,
     HlsTargetDurationCompatibilityModeType,
     HlsTimedMetadataId3FrameType,
     ImscAccessibilitySubsType,
     ImscStylePassthroughType,
@@ -422,14 +430,15 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AacSettingsTypeDef",
     "Ac3SettingsTypeDef",
     "AccelerationSettingsTypeDef",
+    "AdvancedInputFilterSettingsTypeDef",
     "AiffSettingsTypeDef",
     "AllowedRenditionSizeTypeDef",
     "AncillarySourceSettingsTypeDef",
     "AssociateCertificateRequestRequestTypeDef",
     "AudioChannelTaggingSettingsTypeDef",
     "Eac3AtmosSettingsTypeDef",
     "Eac3SettingsTypeDef",
@@ -443,14 +452,15 @@
     "HlsRenditionGroupSettingsTypeDef",
     "ForceIncludeRenditionSizeTypeDef",
     "MinBottomRenditionSizeTypeDef",
     "MinTopRenditionSizeTypeDef",
     "Av1QvbrSettingsTypeDef",
     "AvailBlankingTypeDef",
     "AvcIntraUhdSettingsTypeDef",
+    "BandwidthReductionFilterTypeDef",
     "BurninDestinationSettingsTypeDef",
     "CancelJobRequestRequestTypeDef",
     "DvbSubDestinationSettingsTypeDef",
     "EmbeddedDestinationSettingsTypeDef",
     "ImscDestinationSettingsTypeDef",
     "SccDestinationSettingsTypeDef",
     "SrtDestinationSettingsTypeDef",
@@ -473,24 +483,23 @@
     "Hdr10MetadataTypeDef",
     "F4vSettingsTypeDef",
     "M3u8SettingsTypeDef",
     "MovSettingsTypeDef",
     "Mp4SettingsTypeDef",
     "MpdSettingsTypeDef",
     "HopDestinationTypeDef",
-    "ResponseMetadataTypeDef",
     "ReservationPlanSettingsTypeDef",
     "DashAdditionalManifestTypeDef",
     "SpekeKeyProviderTypeDef",
     "DashIsoImageBasedTrickPlaySettingsTypeDef",
     "DeinterlacerTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
     "DeletePresetRequestRequestTypeDef",
     "DeleteQueueRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
     "DescribeEndpointsRequestRequestTypeDef",
     "EndpointTypeDef",
     "DisassociateCertificateRequestRequestTypeDef",
     "DolbyVisionLevel6MetadataTypeDef",
     "DvbNitSettingsTypeDef",
     "DvbSdtSettingsTypeDef",
     "DvbTdtSettingsTypeDef",
@@ -519,33 +528,40 @@
     "JobMessagesTypeDef",
     "KantarWatermarkSettingsTypeDef",
     "NielsenConfigurationTypeDef",
     "NielsenNonLinearWatermarkSettingsTypeDef",
     "TimecodeConfigTypeDef",
     "QueueTransitionTypeDef",
     "TimingTypeDef",
+    "WarningGroupTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListPresetsRequestListPresetsPaginateTypeDef",
     "ListPresetsRequestRequestTypeDef",
+    "ListQueuesRequestListQueuesPaginateTypeDef",
     "ListQueuesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ResourceTagsTypeDef",
     "M2tsScte35EsamTypeDef",
     "MotionImageInsertionFramerateTypeDef",
     "MotionImageInsertionOffsetTypeDef",
     "Mpeg2SettingsTypeDef",
     "MsSmoothAdditionalManifestTypeDef",
     "MxfXavcProfileSettingsTypeDef",
     "NexGuardFileMarkerSettingsTypeDef",
     "NoiseReducerFilterSettingsTypeDef",
     "NoiseReducerSpatialFilterSettingsTypeDef",
     "NoiseReducerTemporalFilterSettingsTypeDef",
     "VideoDetailTypeDef",
+    "PaginatorConfigTypeDef",
     "ProresSettingsTypeDef",
     "ReservationPlanTypeDef",
+    "ResponseMetadataTypeDef",
     "S3DestinationAccessControlTypeDef",
     "S3EncryptionSettingsTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TimecodeBurninTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "Vc3SettingsTypeDef",
     "Vp8SettingsTypeDef",
@@ -566,19 +582,14 @@
     "ColorCorrectorTypeDef",
     "VideoSelectorTypeDef",
     "CreateQueueRequestRequestTypeDef",
     "UpdateQueueRequestRequestTypeDef",
     "DashIsoEncryptionSettingsTypeDef",
     "HlsEncryptionSettingsTypeDef",
     "MsSmoothEncryptionSettingsTypeDef",
-    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    "ListQueuesRequestListQueuesPaginateTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "DolbyVisionTypeDef",
     "EsamSettingsTypeDef",
     "GetPolicyResponseTypeDef",
     "PutPolicyRequestRequestTypeDef",
     "PutPolicyResponseTypeDef",
     "H264SettingsTypeDef",
@@ -685,14 +696,23 @@
 AccelerationSettingsTypeDef = TypedDict(
     "AccelerationSettingsTypeDef",
     {
         "Mode": AccelerationModeType,
     },
 )
 
+AdvancedInputFilterSettingsTypeDef = TypedDict(
+    "AdvancedInputFilterSettingsTypeDef",
+    {
+        "AddTexture": AdvancedInputFilterAddTextureType,
+        "Sharpening": AdvancedInputFilterSharpenType,
+    },
+    total=False,
+)
+
 AiffSettingsTypeDef = TypedDict(
     "AiffSettingsTypeDef",
     {
         "BitDepth": int,
         "Channels": int,
         "SampleRate": int,
     },
@@ -919,14 +939,23 @@
     "AvcIntraUhdSettingsTypeDef",
     {
         "QualityTuningLevel": AvcIntraUhdQualityTuningLevelType,
     },
     total=False,
 )
 
+BandwidthReductionFilterTypeDef = TypedDict(
+    "BandwidthReductionFilterTypeDef",
+    {
+        "Sharpening": BandwidthReductionFilterSharpeningType,
+        "Strength": BandwidthReductionFilterStrengthType,
+    },
+    total=False,
+)
+
 BurninDestinationSettingsTypeDef = TypedDict(
     "BurninDestinationSettingsTypeDef",
     {
         "Alignment": BurninSubtitleAlignmentType,
         "ApplyFontColor": BurninSubtitleApplyFontColorType,
         "BackgroundColor": BurninSubtitleBackgroundColorType,
         "BackgroundOpacity": int,
@@ -1294,25 +1323,14 @@
         "Priority": int,
         "Queue": str,
         "WaitMinutes": int,
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
 ReservationPlanSettingsTypeDef = TypedDict(
     "ReservationPlanSettingsTypeDef",
     {
         "Commitment": Literal["ONE_YEAR"],
         "RenewalType": RenewalTypeType,
         "ReservedSlots": int,
     },
@@ -1378,20 +1396,19 @@
 DeleteQueueRequestRequestTypeDef = TypedDict(
     "DeleteQueueRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef = TypedDict(
+    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Mode": DescribeEndpointsModeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEndpointsRequestRequestTypeDef = TypedDict(
     "DescribeEndpointsRequestRequestTypeDef",
     {
@@ -1754,50 +1771,101 @@
         "FinishTime": datetime,
         "StartTime": datetime,
         "SubmitTime": datetime,
     },
     total=False,
 )
 
+WarningGroupTypeDef = TypedDict(
+    "WarningGroupTypeDef",
+    {
+        "Code": int,
+        "Count": int,
+    },
+)
+
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "Category": str,
+        "ListBy": JobTemplateListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "Category": str,
         "ListBy": JobTemplateListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "Order": OrderType,
+        "Queue": str,
+        "Status": JobStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
         "Queue": str,
         "Status": JobStatusType,
     },
     total=False,
 )
 
+ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
+    "ListPresetsRequestListPresetsPaginateTypeDef",
+    {
+        "Category": str,
+        "ListBy": PresetListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPresetsRequestRequestTypeDef = TypedDict(
     "ListPresetsRequestRequestTypeDef",
     {
         "Category": str,
         "ListBy": PresetListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
     },
     total=False,
 )
 
+ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
+    "ListQueuesRequestListQueuesPaginateTypeDef",
+    {
+        "ListBy": QueueListByType,
+        "Order": OrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueuesRequestRequestTypeDef = TypedDict(
     "ListQueuesRequestRequestTypeDef",
     {
         "ListBy": QueueListByType,
         "MaxResults": int,
         "NextToken": str,
         "Order": OrderType,
@@ -1951,14 +2019,24 @@
     {
         "HeightInPx": int,
         "WidthInPx": int,
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
 ProresSettingsTypeDef = TypedDict(
     "ProresSettingsTypeDef",
     {
         "ChromaSampling": ProresChromaSamplingType,
         "CodecProfile": ProresCodecProfileType,
         "FramerateControl": ProresFramerateControlType,
         "FramerateConversionAlgorithm": ProresFramerateConversionAlgorithmType,
@@ -1984,14 +2062,25 @@
         "RenewalType": RenewalTypeType,
         "ReservedSlots": int,
         "Status": ReservationPlanStatusType,
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
 S3DestinationAccessControlTypeDef = TypedDict(
     "S3DestinationAccessControlTypeDef",
     {
         "CannedAcl": S3ObjectCannedAclType,
     },
     total=False,
 )
@@ -2238,14 +2327,15 @@
     total=False,
 )
 
 FileSourceSettingsTypeDef = TypedDict(
     "FileSourceSettingsTypeDef",
     {
         "Convert608To708": FileSourceConvert608To708Type,
+        "ConvertPaintToPop": CaptionSourceConvertPaintOnToPopOnType,
         "Framerate": CaptionSourceFramerateTypeDef,
         "SourceFile": str,
         "TimeDelta": int,
         "TimeDeltaUnits": FileSourceTimeDeltaUnitsType,
     },
     total=False,
 )
@@ -2275,14 +2365,15 @@
     "ColorCorrectorTypeDef",
     {
         "Brightness": int,
         "ClipLimits": ClipLimitsTypeDef,
         "ColorSpaceConversion": ColorSpaceConversionType,
         "Contrast": int,
         "Hdr10Metadata": Hdr10MetadataTypeDef,
+        "HdrToSdrToneMapper": HDRToSDRToneMapperType,
         "Hue": int,
         "SampleRangeConversion": SampleRangeConversionType,
         "Saturation": int,
         "SdrReferenceWhiteLevel": int,
     },
     total=False,
 )
@@ -2375,72 +2466,20 @@
     "MsSmoothEncryptionSettingsTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
     },
     total=False,
 )
 
-DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef = TypedDict(
-    "DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef",
-    {
-        "Mode": DescribeEndpointsModeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "Category": str,
-        "ListBy": JobTemplateListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "Order": OrderType,
-        "Queue": str,
-        "Status": JobStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    {
-        "Category": str,
-        "ListBy": PresetListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
-    "ListQueuesRequestListQueuesPaginateTypeDef",
-    {
-        "ListBy": QueueListByType,
-        "Order": OrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DolbyVisionTypeDef = TypedDict(
     "DolbyVisionTypeDef",
     {
         "L6Metadata": DolbyVisionLevel6MetadataTypeDef,
@@ -2461,37 +2500,38 @@
     total=False,
 )
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPolicyRequestRequestTypeDef = TypedDict(
     "PutPolicyRequestRequestTypeDef",
     {
         "Policy": PolicyTypeDef,
     },
 )
 
 PutPolicyResponseTypeDef = TypedDict(
     "PutPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 H264SettingsTypeDef = TypedDict(
     "H264SettingsTypeDef",
     {
         "AdaptiveQuantization": H264AdaptiveQuantizationType,
+        "BandwidthReductionFilter": BandwidthReductionFilterTypeDef,
         "Bitrate": int,
         "CodecLevel": H264CodecLevelType,
         "CodecProfile": H264CodecProfileType,
         "DynamicSubGop": H264DynamicSubGopType,
         "EntropyEncoding": H264EntropyEncodingType,
         "FieldEncoding": H264FieldEncodingType,
         "FlickerAdaptiveQuantization": H264FlickerAdaptiveQuantizationType,
@@ -2533,14 +2573,15 @@
 )
 
 H265SettingsTypeDef = TypedDict(
     "H265SettingsTypeDef",
     {
         "AdaptiveQuantization": H265AdaptiveQuantizationType,
         "AlternateTransferFunctionSei": H265AlternateTransferFunctionSeiType,
+        "BandwidthReductionFilter": BandwidthReductionFilterTypeDef,
         "Bitrate": int,
         "CodecLevel": H265CodecLevelType,
         "CodecProfile": H265CodecProfileType,
         "DynamicSubGop": H265DynamicSubGopType,
         "FlickerAdaptiveQuantization": H265FlickerAdaptiveQuantizationType,
         "FramerateControl": H265FramerateControlType,
         "FramerateConversionAlgorithm": H265FramerateConversionAlgorithmType,
@@ -2605,15 +2646,15 @@
     total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceTags": ResourceTagsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 M2tsSettingsTypeDef = TypedDict(
     "M2tsSettingsTypeDef",
     {
         "AudioBufferModel": M2tsAudioBufferModelType,
@@ -2866,40 +2907,40 @@
     total=False,
 )
 
 CreateQueueResponseTypeDef = TypedDict(
     "CreateQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueueResponseTypeDef = TypedDict(
     "GetQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueuesResponseTypeDef = TypedDict(
     "ListQueuesResponseTypeDef",
     {
         "NextToken": str,
         "Queues": List[QueueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateQueueResponseTypeDef = TypedDict(
     "UpdateQueueResponseTypeDef",
     {
         "Queue": QueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationSettingsTypeDef = TypedDict(
     "DestinationSettingsTypeDef",
     {
         "S3Settings": S3DestinationSettingsTypeDef,
@@ -3073,14 +3114,15 @@
         "ManifestCompression": HlsManifestCompressionType,
         "ManifestDurationFormat": HlsManifestDurationFormatType,
         "MinFinalSegmentLength": float,
         "MinSegmentLength": int,
         "OutputSelection": HlsOutputSelectionType,
         "ProgramDateTime": HlsProgramDateTimeType,
         "ProgramDateTimePeriod": int,
+        "ProgressiveWriteHlsManifest": HlsProgressiveWriteHlsManifestType,
         "SegmentControl": HlsSegmentControlType,
         "SegmentLength": int,
         "SegmentLengthControl": HlsSegmentLengthControlType,
         "SegmentsPerSubdirectory": int,
         "StreamInfResolution": HlsStreamInfResolutionType,
         "TargetDurationCompatibilityMode": HlsTargetDurationCompatibilityModeType,
         "TimedMetadataId3Frame": HlsTimedMetadataId3FrameType,
@@ -3126,14 +3168,16 @@
     },
     total=False,
 )
 
 InputTemplateTypeDef = TypedDict(
     "InputTemplateTypeDef",
     {
+        "AdvancedInputFilter": AdvancedInputFilterType,
+        "AdvancedInputFilterSettings": AdvancedInputFilterSettingsTypeDef,
         "AudioSelectorGroups": Mapping[str, AudioSelectorGroupTypeDef],
         "AudioSelectors": Mapping[str, AudioSelectorTypeDef],
         "CaptionSelectors": Mapping[str, CaptionSelectorTypeDef],
         "Crop": RectangleTypeDef,
         "DeblockFilter": InputDeblockFilterType,
         "DenoiseFilter": InputDenoiseFilterType,
         "DolbyVisionMetadataXml": str,
@@ -3151,14 +3195,16 @@
     },
     total=False,
 )
 
 InputTypeDef = TypedDict(
     "InputTypeDef",
     {
+        "AdvancedInputFilter": AdvancedInputFilterType,
+        "AdvancedInputFilterSettings": AdvancedInputFilterSettingsTypeDef,
         "AudioSelectorGroups": Mapping[str, AudioSelectorGroupTypeDef],
         "AudioSelectors": Mapping[str, AudioSelectorTypeDef],
         "CaptionSelectors": Mapping[str, CaptionSelectorTypeDef],
         "Crop": RectangleTypeDef,
         "DeblockFilter": InputDeblockFilterType,
         "DecryptionSettings": InputDecryptionSettingsTypeDef,
         "DenoiseFilter": InputDenoiseFilterType,
@@ -3336,40 +3382,40 @@
     total=False,
 )
 
 CreatePresetResponseTypeDef = TypedDict(
     "CreatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPresetResponseTypeDef = TypedDict(
     "GetPresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPresetsResponseTypeDef = TypedDict(
     "ListPresetsResponseTypeDef",
     {
         "NextToken": str,
         "Presets": List[PresetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePresetResponseTypeDef = TypedDict(
     "UpdatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "Role": str,
@@ -3409,14 +3455,15 @@
 _OptionalJobTypeDef = TypedDict(
     "_OptionalJobTypeDef",
     {
         "AccelerationSettings": AccelerationSettingsTypeDef,
         "AccelerationStatus": AccelerationStatusType,
         "Arn": str,
         "BillingTagsSource": BillingTagsSourceType,
+        "ClientRequestToken": str,
         "CreatedAt": datetime,
         "CurrentPhase": JobPhaseType,
         "ErrorCode": int,
         "ErrorMessage": str,
         "HopDestinations": List[HopDestinationTypeDef],
         "Id": str,
         "JobPercentComplete": int,
@@ -3428,14 +3475,15 @@
         "QueueTransitions": List[QueueTransitionTypeDef],
         "RetryCount": int,
         "SimulateReservedQueue": SimulateReservedQueueType,
         "Status": JobStatusType,
         "StatusUpdateInterval": StatusUpdateIntervalType,
         "Timing": TimingTypeDef,
         "UserMetadata": Dict[str, str],
+        "Warnings": List[WarningGroupTypeDef],
     },
     total=False,
 )
 
 class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
     pass
 
@@ -3520,60 +3568,60 @@
 ):
     pass
 
 CreateJobResponseTypeDef = TypedDict(
     "CreateJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJobTemplateResponseTypeDef = TypedDict(
     "CreateJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobTemplateResponseTypeDef = TypedDict(
     "GetJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "JobTemplates": List[JobTemplateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobTemplateResponseTypeDef = TypedDict(
     "UpdateJobTemplateResponseTypeDef",
     {
         "JobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/PKG-INFO` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediaconvert
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaConvert 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaConvert 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediaconvert"></a>
 
 # types-aiobotocore-mediaconvert
 
 [![PyPI - types-aiobotocore-mediaconvert](https://img.shields.io/pypi/v/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconvert.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconvert)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconvert?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconvert)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConvert 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
+[aiobotocore.MediaConvert 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconvert.html#MediaConvert)
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
 [types-aiobotocore-mediaconvert docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconvert/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,14 +322,17 @@
     Ac3DynamicRangeCompressionLineType,
     Ac3DynamicRangeCompressionProfileType,
     Ac3DynamicRangeCompressionRfType,
     Ac3LfeFilterType,
     Ac3MetadataControlType,
     AccelerationModeType,
     AccelerationStatusType,
+    AdvancedInputFilterAddTextureType,
+    AdvancedInputFilterSharpenType,
+    AdvancedInputFilterType,
     AfdSignalingType,
     AlphaBehaviorType,
     AncillaryConvert608To708Type,
     AncillaryTerminateCaptionsType,
     AntiAliasType,
     AudioChannelTagType,
     AudioCodecType,
@@ -352,25 +355,28 @@
     AvcIntraFramerateControlType,
     AvcIntraFramerateConversionAlgorithmType,
     AvcIntraInterlaceModeType,
     AvcIntraScanTypeConversionModeType,
     AvcIntraSlowPalType,
     AvcIntraTelecineType,
     AvcIntraUhdQualityTuningLevelType,
+    BandwidthReductionFilterSharpeningType,
+    BandwidthReductionFilterStrengthType,
     BillingTagsSourceType,
     BurnInSubtitleStylePassthroughType,
     BurninSubtitleAlignmentType,
     BurninSubtitleApplyFontColorType,
     BurninSubtitleBackgroundColorType,
     BurninSubtitleFallbackFontType,
     BurninSubtitleFontColorType,
     BurninSubtitleOutlineColorType,
     BurninSubtitleShadowColorType,
     BurninSubtitleTeletextSpacingType,
     CaptionDestinationTypeType,
+    CaptionSourceConvertPaintOnToPopOnType,
     CaptionSourceTypeType,
     CmafClientCacheType,
     CmafCodecSpecificationType,
     CmafEncryptionTypeType,
     CmafImageBasedTrickPlayType,
     CmafInitializationVectorInManifestType,
     CmafIntervalCadenceType,
@@ -515,14 +521,15 @@
     H265SpatialAdaptiveQuantizationType,
     H265TelecineType,
     H265TemporalAdaptiveQuantizationType,
     H265TemporalIdsType,
     H265TilesType,
     H265UnregisteredSeiTimecodeType,
     H265WriteMp4PackagingTypeType,
+    HDRToSDRToneMapperType,
     HlsAdMarkersType,
     HlsAudioOnlyContainerType,
     HlsAudioOnlyHeaderType,
     HlsAudioTrackTypeType,
     HlsCaptionLanguageSettingType,
     HlsCaptionSegmentLengthControlType,
     HlsClientCacheType,
@@ -536,14 +543,15 @@
     HlsIntervalCadenceType,
     HlsKeyProviderTypeType,
     HlsManifestCompressionType,
     HlsManifestDurationFormatType,
     HlsOfflineEncryptedType,
     HlsOutputSelectionType,
     HlsProgramDateTimeType,
+    HlsProgressiveWriteHlsManifestType,
     HlsSegmentControlType,
     HlsSegmentLengthControlType,
     HlsStreamInfResolutionType,
     HlsTargetDurationCompatibilityModeType,
     HlsTimedMetadataId3FrameType,
     ImscAccessibilitySubsType,
     ImscStylePassthroughType,
@@ -735,14 +743,15 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconvert.type_defs import (
     AacSettingsTypeDef,
     Ac3SettingsTypeDef,
     AccelerationSettingsTypeDef,
+    AdvancedInputFilterSettingsTypeDef,
     AiffSettingsTypeDef,
     AllowedRenditionSizeTypeDef,
     AncillarySourceSettingsTypeDef,
     AssociateCertificateRequestRequestTypeDef,
     AudioChannelTaggingSettingsTypeDef,
     Eac3AtmosSettingsTypeDef,
     Eac3SettingsTypeDef,
@@ -756,14 +765,15 @@
     HlsRenditionGroupSettingsTypeDef,
     ForceIncludeRenditionSizeTypeDef,
     MinBottomRenditionSizeTypeDef,
     MinTopRenditionSizeTypeDef,
     Av1QvbrSettingsTypeDef,
     AvailBlankingTypeDef,
     AvcIntraUhdSettingsTypeDef,
+    BandwidthReductionFilterTypeDef,
     BurninDestinationSettingsTypeDef,
     CancelJobRequestRequestTypeDef,
     DvbSubDestinationSettingsTypeDef,
     EmbeddedDestinationSettingsTypeDef,
     ImscDestinationSettingsTypeDef,
     SccDestinationSettingsTypeDef,
     SrtDestinationSettingsTypeDef,
@@ -786,24 +796,23 @@
     Hdr10MetadataTypeDef,
     F4vSettingsTypeDef,
     M3u8SettingsTypeDef,
     MovSettingsTypeDef,
     Mp4SettingsTypeDef,
     MpdSettingsTypeDef,
     HopDestinationTypeDef,
-    ResponseMetadataTypeDef,
     ReservationPlanSettingsTypeDef,
     DashAdditionalManifestTypeDef,
     SpekeKeyProviderTypeDef,
     DashIsoImageBasedTrickPlaySettingsTypeDef,
     DeinterlacerTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsRequestRequestTypeDef,
     EndpointTypeDef,
     DisassociateCertificateRequestRequestTypeDef,
     DolbyVisionLevel6MetadataTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
@@ -832,33 +841,40 @@
     JobMessagesTypeDef,
     KantarWatermarkSettingsTypeDef,
     NielsenConfigurationTypeDef,
     NielsenNonLinearWatermarkSettingsTypeDef,
     TimecodeConfigTypeDef,
     QueueTransitionTypeDef,
     TimingTypeDef,
+    WarningGroupTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ResourceTagsTypeDef,
     M2tsScte35EsamTypeDef,
     MotionImageInsertionFramerateTypeDef,
     MotionImageInsertionOffsetTypeDef,
     Mpeg2SettingsTypeDef,
     MsSmoothAdditionalManifestTypeDef,
     MxfXavcProfileSettingsTypeDef,
     NexGuardFileMarkerSettingsTypeDef,
     NoiseReducerFilterSettingsTypeDef,
     NoiseReducerSpatialFilterSettingsTypeDef,
     NoiseReducerTemporalFilterSettingsTypeDef,
     VideoDetailTypeDef,
+    PaginatorConfigTypeDef,
     ProresSettingsTypeDef,
     ReservationPlanTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationAccessControlTypeDef,
     S3EncryptionSettingsTypeDef,
     TagResourceRequestRequestTypeDef,
     TimecodeBurninTypeDef,
     UntagResourceRequestRequestTypeDef,
     Vc3SettingsTypeDef,
     Vp8SettingsTypeDef,
@@ -879,19 +895,14 @@
     ColorCorrectorTypeDef,
     VideoSelectorTypeDef,
     CreateQueueRequestRequestTypeDef,
     UpdateQueueRequestRequestTypeDef,
     DashIsoEncryptionSettingsTypeDef,
     HlsEncryptionSettingsTypeDef,
     MsSmoothEncryptionSettingsTypeDef,
-    DescribeEndpointsRequestDescribeEndpointsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
     DescribeEndpointsResponseTypeDef,
     DolbyVisionTypeDef,
     EsamSettingsTypeDef,
     GetPolicyResponseTypeDef,
     PutPolicyRequestRequestTypeDef,
     PutPolicyResponseTypeDef,
     H264SettingsTypeDef,
@@ -970,43 +981,43 @@
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

### Comparing `types-aiobotocore-mediaconvert-2.5.0.post1/types_aiobotocore_mediaconvert.egg-info/SOURCES.txt` & `types-aiobotocore-mediaconvert-2.5.1/types_aiobotocore_mediaconvert.egg-info/SOURCES.txt`

 * *Files identical despite different names*

