# Comparing `tmp/types-aiobotocore-rekognition-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rekognition-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rekognition-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:11 2023, max compression
+gzip compressed data, was "types-aiobotocore-rekognition-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-rekognition-2.5.0.post1.tar` & `types-aiobotocore-rekognition-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.267539 types-aiobotocore-rekognition-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    25234 2023-03-11 12:27:11.267539 types-aiobotocore-rekognition-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    23647 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:11.267539 types-aiobotocore-rekognition-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.267539 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/
--rw-r--r--   0 runner    (1001) docker     (123)     2699 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2698 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    53879 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    53797 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13183 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13181 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10420 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10409 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    83722 2023-03-11 12:22:21.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    83621 2023-03-11 12:22:20.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3088 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3086 2023-03-11 12:22:19.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.267539 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    25234 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:27:11.000000 types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.058200 types-aiobotocore-rekognition-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    26915 2023-06-28 01:44:03.058200 types-aiobotocore-rekognition-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    25334 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.058200 types-aiobotocore-rekognition-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.058200 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/
+-rw-r--r--   0 runner    (1001) docker     (123)     2859 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2858 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60517 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60425 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14761 2023-06-28 01:39:08.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14759 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11448 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11437 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    97151 2023-06-28 01:39:09.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    97032 2023-06-28 01:39:08.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:04.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3088 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3086 2023-06-28 01:39:07.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.058200 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    26915 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:44:02.000000 types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/LICENSE` & `types-aiobotocore-rekognition-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rekognition-2.5.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rekognition
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Rekognition 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Rekognition 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rekognition"></a>
 
 # types-aiobotocore-rekognition
 
 [![PyPI - types-aiobotocore-rekognition](https://img.shields.io/pypi/v/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rekognition?color=blue)](https://pypistats.org/packages/types-aiobotocore-rekognition)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Rekognition 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
+[aiobotocore.Rekognition 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
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
 [types-aiobotocore-rekognition docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,14 +282,15 @@
     DescribeProjectsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 
 session = get_session()
 async with session.create_client("rekognition") as client:
     client: RekognitionClient
 
     # Explicit type annotations are optional here
@@ -310,14 +311,15 @@
     list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
     list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator(
         "list_project_policies"
     )
     list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator(
         "list_stream_processors"
     )
+    list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
 ```
 
 <a id="waiters-annotations"></a>
 
 ### Waiters annotations
 
 `types_aiobotocore_rekognition.waiter` module contains type annotations for all
@@ -355,14 +357,15 @@
 
 ```python
 from types_aiobotocore_rekognition.literals import (
     AttributeType,
     BodyPartType,
     CelebrityRecognitionSortByType,
     ContentClassifierType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetStatusMessageCodeType,
     DatasetStatusType,
     DatasetTypeType,
     DescribeProjectVersionsPaginatorName,
     DescribeProjectsPaginatorName,
     DetectLabelsFeatureNameType,
@@ -377,28 +380,35 @@
     LandmarkTypeType,
     ListCollectionsPaginatorName,
     ListDatasetEntriesPaginatorName,
     ListDatasetLabelsPaginatorName,
     ListFacesPaginatorName,
     ListProjectPoliciesPaginatorName,
     ListStreamProcessorsPaginatorName,
+    ListUsersPaginatorName,
+    LivenessSessionStatusType,
     OrientationCorrectionType,
     PersonTrackingSortByType,
     ProjectStatusType,
     ProjectVersionRunningWaiterName,
     ProjectVersionStatusType,
     ProjectVersionTrainingCompletedWaiterName,
     ProtectiveEquipmentTypeType,
     QualityFilterType,
     ReasonType,
     SegmentTypeType,
     StreamProcessorParameterToDeleteType,
     StreamProcessorStatusType,
     TechnicalCueTypeType,
     TextTypesType,
+    UnsearchedFaceReasonType,
+    UnsuccessfulFaceAssociationReasonType,
+    UnsuccessfulFaceDeletionReasonType,
+    UnsuccessfulFaceDisassociationReasonType,
+    UserStatusType,
     VideoColorRangeType,
     VideoJobStatusType,
     RekognitionServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
@@ -416,257 +426,293 @@
 
 `types_aiobotocore_rekognition.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rekognition.type_defs import (
     AgeRangeTypeDef,
+    AssociateFacesRequestRequestTypeDef,
+    AssociatedFaceTypeDef,
+    UnsuccessfulFaceAssociationTypeDef,
     AudioMetadataTypeDef,
+    BoundingBoxTypeDef,
+    S3ObjectTypeDef,
     BeardTypeDef,
     BlackFrameTypeDef,
-    BoundingBoxTypeDef,
     KnownGenderTypeDef,
-    ResponseMetadataTypeDef,
     EmotionTypeDef,
     ImageQualityTypeDef,
     LandmarkTypeDef,
     PoseTypeDef,
     SmileTypeDef,
     ConnectedHomeSettingsForUpdateTypeDef,
     ConnectedHomeSettingsTypeDef,
     ModerationLabelTypeDef,
     OutputConfigTypeDef,
+    CopyProjectVersionResponseTypeDef,
     CoversBodyPartTypeDef,
     CreateCollectionRequestRequestTypeDef,
+    CreateCollectionResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    LivenessOutputConfigTypeDef,
+    CreateFaceLivenessSessionResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
+    CreateProjectVersionResponseTypeDef,
     StreamProcessorDataSharingPreferenceTypeDef,
     StreamProcessorNotificationChannelTypeDef,
+    CreateStreamProcessorResponseTypeDef,
+    CreateUserRequestRequestTypeDef,
     DatasetChangesTypeDef,
     DatasetStatsTypeDef,
     DatasetLabelStatsTypeDef,
     DatasetMetadataTypeDef,
     DeleteCollectionRequestRequestTypeDef,
+    DeleteCollectionResponseTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteFacesRequestRequestTypeDef,
+    UnsuccessfulFaceDeletionTypeDef,
     DeleteProjectPolicyRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DeleteProjectVersionRequestRequestTypeDef,
+    DeleteProjectVersionResponseTypeDef,
     DeleteStreamProcessorRequestRequestTypeDef,
+    DeleteUserRequestRequestTypeDef,
     DescribeCollectionRequestRequestTypeDef,
+    DescribeCollectionResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeProjectVersionsRequestRequestTypeDef,
+    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
     DescribeProjectsRequestRequestTypeDef,
     DescribeStreamProcessorRequestRequestTypeDef,
     DetectLabelsImageQualityTypeDef,
     DominantColorTypeDef,
     DetectLabelsImagePropertiesSettingsTypeDef,
     GeneralLabelsSettingsTypeDef,
     HumanLoopActivationOutputTypeDef,
     ProtectiveEquipmentSummarizationAttributesTypeDef,
     ProtectiveEquipmentSummaryTypeDef,
     DetectionFilterTypeDef,
+    DisassociateFacesRequestRequestTypeDef,
+    DisassociatedFaceTypeDef,
+    UnsuccessfulFaceDisassociationTypeDef,
     DistributeDatasetTypeDef,
+    EyeDirectionTypeDef,
     EyeOpenTypeDef,
     EyeglassesTypeDef,
+    FaceOccludedTypeDef,
     GenderTypeDef,
     MouthOpenTypeDef,
     MustacheTypeDef,
     SunglassesTypeDef,
     FaceSearchSettingsTypeDef,
     PointTypeDef,
     GetCelebrityInfoRequestRequestTypeDef,
     GetCelebrityRecognitionRequestRequestTypeDef,
     VideoMetadataTypeDef,
+    GetContentModerationRequestMetadataTypeDef,
     GetContentModerationRequestRequestTypeDef,
     GetFaceDetectionRequestRequestTypeDef,
+    GetFaceLivenessSessionResultsRequestRequestTypeDef,
     GetFaceSearchRequestRequestTypeDef,
+    GetLabelDetectionRequestMetadataTypeDef,
     GetLabelDetectionRequestRequestTypeDef,
     GetPersonTrackingRequestRequestTypeDef,
     GetSegmentDetectionRequestRequestTypeDef,
     SegmentTypeInfoTypeDef,
     GetTextDetectionRequestRequestTypeDef,
-    S3ObjectTypeDef,
     HumanLoopDataAttributesTypeDef,
     KinesisDataStreamTypeDef,
     KinesisVideoStreamStartSelectorTypeDef,
     KinesisVideoStreamTypeDef,
     LabelAliasTypeDef,
     LabelCategoryTypeDef,
     ParentTypeDef,
+    ListCollectionsRequestListCollectionsPaginateTypeDef,
     ListCollectionsRequestRequestTypeDef,
+    ListCollectionsResponseTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
     ListDatasetLabelsRequestRequestTypeDef,
+    ListFacesRequestListFacesPaginateTypeDef,
     ListFacesRequestRequestTypeDef,
+    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
     ListProjectPoliciesRequestRequestTypeDef,
     ProjectPolicyTypeDef,
+    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
     ListStreamProcessorsRequestRequestTypeDef,
     StreamProcessorTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
+    UserTypeDef,
+    MatchedUserTypeDef,
     NotificationChannelTypeDef,
+    PaginatorConfigTypeDef,
     PutProjectPolicyRequestRequestTypeDef,
+    PutProjectPolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationTypeDef,
     SearchFacesRequestRequestTypeDef,
+    SearchUsersRequestRequestTypeDef,
+    SearchedFaceTypeDef,
+    SearchedUserTypeDef,
     ShotSegmentTypeDef,
     TechnicalCueSegmentTypeDef,
-    StartProjectVersionRequestRequestTypeDef,
-    StartShotDetectionFilterTypeDef,
-    StreamProcessingStopSelectorTypeDef,
-    StopProjectVersionRequestRequestTypeDef,
-    StopStreamProcessorRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    StartTechnicalCueDetectionFilterTypeDef,
-    ComparedSourceImageFaceTypeDef,
-    FaceTypeDef,
-    CopyProjectVersionResponseTypeDef,
-    CreateCollectionResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateProjectVersionResponseTypeDef,
-    CreateStreamProcessorResponseTypeDef,
-    DeleteCollectionResponseTypeDef,
-    DeleteFacesResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    DeleteProjectVersionResponseTypeDef,
-    DescribeCollectionResponseTypeDef,
-    GetCelebrityInfoResponseTypeDef,
-    ListCollectionsResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutProjectPolicyResponseTypeDef,
     StartCelebrityRecognitionResponseTypeDef,
     StartContentModerationResponseTypeDef,
     StartFaceDetectionResponseTypeDef,
     StartFaceSearchResponseTypeDef,
     StartLabelDetectionResponseTypeDef,
     StartPersonTrackingResponseTypeDef,
+    StartProjectVersionRequestRequestTypeDef,
     StartProjectVersionResponseTypeDef,
+    StartShotDetectionFilterTypeDef,
     StartSegmentDetectionResponseTypeDef,
+    StreamProcessingStopSelectorTypeDef,
     StartStreamProcessorResponseTypeDef,
     StartTextDetectionResponseTypeDef,
+    StopProjectVersionRequestRequestTypeDef,
     StopProjectVersionResponseTypeDef,
+    StopStreamProcessorRequestRequestTypeDef,
+    TagResourceRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    AssociateFacesResponseTypeDef,
+    ComparedSourceImageFaceTypeDef,
+    FaceTypeDef,
+    AuditImageTypeDef,
+    GroundTruthManifestTypeDef,
+    ImageTypeDef,
+    SummaryTypeDef,
+    VideoTypeDef,
+    StartTechnicalCueDetectionFilterTypeDef,
+    GetCelebrityInfoResponseTypeDef,
     ComparedFaceTypeDef,
     StreamProcessorSettingsForUpdateTypeDef,
     ContentModerationDetectionTypeDef,
     CopyProjectVersionRequestRequestTypeDef,
     EquipmentDetectionTypeDef,
+    CreateFaceLivenessSessionRequestSettingsTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
     DatasetDescriptionTypeDef,
     DatasetLabelDescriptionTypeDef,
     ProjectDescriptionTypeDef,
-    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
-    ListCollectionsRequestListCollectionsPaginateTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-    ListFacesRequestListFacesPaginateTypeDef,
-    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
+    DeleteFacesResponseTypeDef,
     DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
     DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
     DetectLabelsImageBackgroundTypeDef,
     DetectLabelsImageForegroundTypeDef,
     InstanceTypeDef,
     DetectLabelsSettingsTypeDef,
     LabelDetectionSettingsTypeDef,
     DetectModerationLabelsResponseTypeDef,
+    DisassociateFacesResponseTypeDef,
     DistributeDatasetEntriesRequestRequestTypeDef,
     FaceDetailTypeDef,
     StreamProcessorSettingsTypeDef,
     GeometryTypeDef,
     RegionOfInterestTypeDef,
-    GroundTruthManifestTypeDef,
-    ImageTypeDef,
-    SummaryTypeDef,
-    VideoTypeDef,
     HumanLoopConfigTypeDef,
     StreamProcessingStartSelectorTypeDef,
     StreamProcessorInputTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
+    ListUsersResponseTypeDef,
+    UserMatchTypeDef,
     StreamProcessorOutputTypeDef,
     SegmentDetectionTypeDef,
-    StartSegmentDetectionFiltersTypeDef,
     FaceMatchTypeDef,
     ListFacesResponseTypeDef,
+    GetFaceLivenessSessionResultsResponseTypeDef,
+    AssetTypeDef,
+    DatasetSourceTypeDef,
+    CompareFacesRequestRequestTypeDef,
+    DetectCustomLabelsRequestRequestTypeDef,
+    DetectFacesRequestRequestTypeDef,
+    DetectProtectiveEquipmentRequestRequestTypeDef,
+    IndexFacesRequestRequestTypeDef,
+    RecognizeCelebritiesRequestRequestTypeDef,
+    SearchFacesByImageRequestRequestTypeDef,
+    SearchUsersByImageRequestRequestTypeDef,
+    EvaluationResultTypeDef,
+    StartCelebrityRecognitionRequestRequestTypeDef,
+    StartContentModerationRequestRequestTypeDef,
+    StartFaceDetectionRequestRequestTypeDef,
+    StartFaceSearchRequestRequestTypeDef,
+    StartPersonTrackingRequestRequestTypeDef,
+    StartSegmentDetectionFiltersTypeDef,
     CelebrityTypeDef,
     CompareFacesMatchTypeDef,
     GetContentModerationResponseTypeDef,
     ProtectiveEquipmentBodyPartTypeDef,
+    CreateFaceLivenessSessionRequestRequestTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     DescribeProjectsResponseTypeDef,
     DetectLabelsImagePropertiesTypeDef,
     LabelTypeDef,
+    DetectLabelsRequestRequestTypeDef,
+    StartLabelDetectionRequestRequestTypeDef,
     CelebrityDetailTypeDef,
     DetectFacesResponseTypeDef,
     FaceDetectionTypeDef,
     FaceRecordTypeDef,
     PersonDetailTypeDef,
+    SearchedFaceDetailsTypeDef,
     UnindexedFaceTypeDef,
+    UnsearchedFaceTypeDef,
     CustomLabelTypeDef,
     TextDetectionTypeDef,
     DetectTextFiltersTypeDef,
     StartTextDetectionFiltersTypeDef,
     UpdateStreamProcessorRequestRequestTypeDef,
-    AssetTypeDef,
-    DatasetSourceTypeDef,
-    CompareFacesRequestRequestTypeDef,
-    DetectCustomLabelsRequestRequestTypeDef,
-    DetectFacesRequestRequestTypeDef,
-    DetectLabelsRequestRequestTypeDef,
-    DetectProtectiveEquipmentRequestRequestTypeDef,
-    IndexFacesRequestRequestTypeDef,
-    RecognizeCelebritiesRequestRequestTypeDef,
-    SearchFacesByImageRequestRequestTypeDef,
-    EvaluationResultTypeDef,
-    StartCelebrityRecognitionRequestRequestTypeDef,
-    StartContentModerationRequestRequestTypeDef,
-    StartFaceDetectionRequestRequestTypeDef,
-    StartFaceSearchRequestRequestTypeDef,
-    StartLabelDetectionRequestRequestTypeDef,
-    StartPersonTrackingRequestRequestTypeDef,
     DetectModerationLabelsRequestRequestTypeDef,
     StartStreamProcessorRequestRequestTypeDef,
+    SearchUsersResponseTypeDef,
     CreateStreamProcessorRequestRequestTypeDef,
     DescribeStreamProcessorResponseTypeDef,
     GetSegmentDetectionResponseTypeDef,
-    StartSegmentDetectionRequestRequestTypeDef,
     SearchFacesByImageResponseTypeDef,
     SearchFacesResponseTypeDef,
+    TestingDataTypeDef,
+    TrainingDataTypeDef,
+    ValidationDataTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    StartSegmentDetectionRequestRequestTypeDef,
     RecognizeCelebritiesResponseTypeDef,
     CompareFacesResponseTypeDef,
     ProtectiveEquipmentPersonTypeDef,
     DetectLabelsResponseTypeDef,
     LabelDetectionTypeDef,
     CelebrityRecognitionTypeDef,
     GetFaceDetectionResponseTypeDef,
     PersonDetectionTypeDef,
     PersonMatchTypeDef,
     IndexFacesResponseTypeDef,
+    SearchUsersByImageResponseTypeDef,
     DetectCustomLabelsResponseTypeDef,
     DetectTextResponseTypeDef,
     TextDetectionResultTypeDef,
     DetectTextRequestRequestTypeDef,
     StartTextDetectionRequestRequestTypeDef,
-    TestingDataTypeDef,
-    TrainingDataTypeDef,
-    ValidationDataTypeDef,
-    CreateDatasetRequestRequestTypeDef,
+    CreateProjectVersionRequestRequestTypeDef,
+    TestingDataResultTypeDef,
+    TrainingDataResultTypeDef,
     DetectProtectiveEquipmentResponseTypeDef,
     GetLabelDetectionResponseTypeDef,
     GetCelebrityRecognitionResponseTypeDef,
     GetPersonTrackingResponseTypeDef,
     GetFaceSearchResponseTypeDef,
     GetTextDetectionResponseTypeDef,
-    CreateProjectVersionRequestRequestTypeDef,
-    TestingDataResultTypeDef,
-    TrainingDataResultTypeDef,
     ProjectVersionDescriptionTypeDef,
     DescribeProjectVersionsResponseTypeDef,
 )
 
 
 def get_structure() -> AgeRangeTypeDef:
     return {...}
@@ -675,43 +721,43 @@
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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/README.md` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-rekognition
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Rekognition 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore rekognition type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-rekognition"></a>
 
 # types-aiobotocore-rekognition
 
 [![PyPI - types-aiobotocore-rekognition](https://img.shields.io/pypi/v/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rekognition?color=blue)](https://pypistats.org/packages/types-aiobotocore-rekognition)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Rekognition 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
+[aiobotocore.Rekognition 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
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
 [types-aiobotocore-rekognition docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/).
 
 See how it helps to find and fix potential bugs:
 
@@ -249,14 +282,15 @@
     DescribeProjectsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 
 session = get_session()
 async with session.create_client("rekognition") as client:
     client: RekognitionClient
 
     # Explicit type annotations are optional here
@@ -277,14 +311,15 @@
     list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
     list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator(
         "list_project_policies"
     )
     list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator(
         "list_stream_processors"
     )
+    list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
 ```
 
 <a id="waiters-annotations"></a>
 
 ### Waiters annotations
 
 `types_aiobotocore_rekognition.waiter` module contains type annotations for all
@@ -322,14 +357,15 @@
 
 ```python
 from types_aiobotocore_rekognition.literals import (
     AttributeType,
     BodyPartType,
     CelebrityRecognitionSortByType,
     ContentClassifierType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetStatusMessageCodeType,
     DatasetStatusType,
     DatasetTypeType,
     DescribeProjectVersionsPaginatorName,
     DescribeProjectsPaginatorName,
     DetectLabelsFeatureNameType,
@@ -344,28 +380,35 @@
     LandmarkTypeType,
     ListCollectionsPaginatorName,
     ListDatasetEntriesPaginatorName,
     ListDatasetLabelsPaginatorName,
     ListFacesPaginatorName,
     ListProjectPoliciesPaginatorName,
     ListStreamProcessorsPaginatorName,
+    ListUsersPaginatorName,
+    LivenessSessionStatusType,
     OrientationCorrectionType,
     PersonTrackingSortByType,
     ProjectStatusType,
     ProjectVersionRunningWaiterName,
     ProjectVersionStatusType,
     ProjectVersionTrainingCompletedWaiterName,
     ProtectiveEquipmentTypeType,
     QualityFilterType,
     ReasonType,
     SegmentTypeType,
     StreamProcessorParameterToDeleteType,
     StreamProcessorStatusType,
     TechnicalCueTypeType,
     TextTypesType,
+    UnsearchedFaceReasonType,
+    UnsuccessfulFaceAssociationReasonType,
+    UnsuccessfulFaceDeletionReasonType,
+    UnsuccessfulFaceDisassociationReasonType,
+    UserStatusType,
     VideoColorRangeType,
     VideoJobStatusType,
     RekognitionServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
@@ -383,257 +426,293 @@
 
 `types_aiobotocore_rekognition.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rekognition.type_defs import (
     AgeRangeTypeDef,
+    AssociateFacesRequestRequestTypeDef,
+    AssociatedFaceTypeDef,
+    UnsuccessfulFaceAssociationTypeDef,
     AudioMetadataTypeDef,
+    BoundingBoxTypeDef,
+    S3ObjectTypeDef,
     BeardTypeDef,
     BlackFrameTypeDef,
-    BoundingBoxTypeDef,
     KnownGenderTypeDef,
-    ResponseMetadataTypeDef,
     EmotionTypeDef,
     ImageQualityTypeDef,
     LandmarkTypeDef,
     PoseTypeDef,
     SmileTypeDef,
     ConnectedHomeSettingsForUpdateTypeDef,
     ConnectedHomeSettingsTypeDef,
     ModerationLabelTypeDef,
     OutputConfigTypeDef,
+    CopyProjectVersionResponseTypeDef,
     CoversBodyPartTypeDef,
     CreateCollectionRequestRequestTypeDef,
+    CreateCollectionResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    LivenessOutputConfigTypeDef,
+    CreateFaceLivenessSessionResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
+    CreateProjectVersionResponseTypeDef,
     StreamProcessorDataSharingPreferenceTypeDef,
     StreamProcessorNotificationChannelTypeDef,
+    CreateStreamProcessorResponseTypeDef,
+    CreateUserRequestRequestTypeDef,
     DatasetChangesTypeDef,
     DatasetStatsTypeDef,
     DatasetLabelStatsTypeDef,
     DatasetMetadataTypeDef,
     DeleteCollectionRequestRequestTypeDef,
+    DeleteCollectionResponseTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteFacesRequestRequestTypeDef,
+    UnsuccessfulFaceDeletionTypeDef,
     DeleteProjectPolicyRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DeleteProjectVersionRequestRequestTypeDef,
+    DeleteProjectVersionResponseTypeDef,
     DeleteStreamProcessorRequestRequestTypeDef,
+    DeleteUserRequestRequestTypeDef,
     DescribeCollectionRequestRequestTypeDef,
+    DescribeCollectionResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeProjectVersionsRequestRequestTypeDef,
+    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
     DescribeProjectsRequestRequestTypeDef,
     DescribeStreamProcessorRequestRequestTypeDef,
     DetectLabelsImageQualityTypeDef,
     DominantColorTypeDef,
     DetectLabelsImagePropertiesSettingsTypeDef,
     GeneralLabelsSettingsTypeDef,
     HumanLoopActivationOutputTypeDef,
     ProtectiveEquipmentSummarizationAttributesTypeDef,
     ProtectiveEquipmentSummaryTypeDef,
     DetectionFilterTypeDef,
+    DisassociateFacesRequestRequestTypeDef,
+    DisassociatedFaceTypeDef,
+    UnsuccessfulFaceDisassociationTypeDef,
     DistributeDatasetTypeDef,
+    EyeDirectionTypeDef,
     EyeOpenTypeDef,
     EyeglassesTypeDef,
+    FaceOccludedTypeDef,
     GenderTypeDef,
     MouthOpenTypeDef,
     MustacheTypeDef,
     SunglassesTypeDef,
     FaceSearchSettingsTypeDef,
     PointTypeDef,
     GetCelebrityInfoRequestRequestTypeDef,
     GetCelebrityRecognitionRequestRequestTypeDef,
     VideoMetadataTypeDef,
+    GetContentModerationRequestMetadataTypeDef,
     GetContentModerationRequestRequestTypeDef,
     GetFaceDetectionRequestRequestTypeDef,
+    GetFaceLivenessSessionResultsRequestRequestTypeDef,
     GetFaceSearchRequestRequestTypeDef,
+    GetLabelDetectionRequestMetadataTypeDef,
     GetLabelDetectionRequestRequestTypeDef,
     GetPersonTrackingRequestRequestTypeDef,
     GetSegmentDetectionRequestRequestTypeDef,
     SegmentTypeInfoTypeDef,
     GetTextDetectionRequestRequestTypeDef,
-    S3ObjectTypeDef,
     HumanLoopDataAttributesTypeDef,
     KinesisDataStreamTypeDef,
     KinesisVideoStreamStartSelectorTypeDef,
     KinesisVideoStreamTypeDef,
     LabelAliasTypeDef,
     LabelCategoryTypeDef,
     ParentTypeDef,
+    ListCollectionsRequestListCollectionsPaginateTypeDef,
     ListCollectionsRequestRequestTypeDef,
+    ListCollectionsResponseTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
     ListDatasetLabelsRequestRequestTypeDef,
+    ListFacesRequestListFacesPaginateTypeDef,
     ListFacesRequestRequestTypeDef,
+    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
     ListProjectPoliciesRequestRequestTypeDef,
     ProjectPolicyTypeDef,
+    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
     ListStreamProcessorsRequestRequestTypeDef,
     StreamProcessorTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
+    UserTypeDef,
+    MatchedUserTypeDef,
     NotificationChannelTypeDef,
+    PaginatorConfigTypeDef,
     PutProjectPolicyRequestRequestTypeDef,
+    PutProjectPolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationTypeDef,
     SearchFacesRequestRequestTypeDef,
+    SearchUsersRequestRequestTypeDef,
+    SearchedFaceTypeDef,
+    SearchedUserTypeDef,
     ShotSegmentTypeDef,
     TechnicalCueSegmentTypeDef,
-    StartProjectVersionRequestRequestTypeDef,
-    StartShotDetectionFilterTypeDef,
-    StreamProcessingStopSelectorTypeDef,
-    StopProjectVersionRequestRequestTypeDef,
-    StopStreamProcessorRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    StartTechnicalCueDetectionFilterTypeDef,
-    ComparedSourceImageFaceTypeDef,
-    FaceTypeDef,
-    CopyProjectVersionResponseTypeDef,
-    CreateCollectionResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateProjectVersionResponseTypeDef,
-    CreateStreamProcessorResponseTypeDef,
-    DeleteCollectionResponseTypeDef,
-    DeleteFacesResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    DeleteProjectVersionResponseTypeDef,
-    DescribeCollectionResponseTypeDef,
-    GetCelebrityInfoResponseTypeDef,
-    ListCollectionsResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutProjectPolicyResponseTypeDef,
     StartCelebrityRecognitionResponseTypeDef,
     StartContentModerationResponseTypeDef,
     StartFaceDetectionResponseTypeDef,
     StartFaceSearchResponseTypeDef,
     StartLabelDetectionResponseTypeDef,
     StartPersonTrackingResponseTypeDef,
+    StartProjectVersionRequestRequestTypeDef,
     StartProjectVersionResponseTypeDef,
+    StartShotDetectionFilterTypeDef,
     StartSegmentDetectionResponseTypeDef,
+    StreamProcessingStopSelectorTypeDef,
     StartStreamProcessorResponseTypeDef,
     StartTextDetectionResponseTypeDef,
+    StopProjectVersionRequestRequestTypeDef,
     StopProjectVersionResponseTypeDef,
+    StopStreamProcessorRequestRequestTypeDef,
+    TagResourceRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    AssociateFacesResponseTypeDef,
+    ComparedSourceImageFaceTypeDef,
+    FaceTypeDef,
+    AuditImageTypeDef,
+    GroundTruthManifestTypeDef,
+    ImageTypeDef,
+    SummaryTypeDef,
+    VideoTypeDef,
+    StartTechnicalCueDetectionFilterTypeDef,
+    GetCelebrityInfoResponseTypeDef,
     ComparedFaceTypeDef,
     StreamProcessorSettingsForUpdateTypeDef,
     ContentModerationDetectionTypeDef,
     CopyProjectVersionRequestRequestTypeDef,
     EquipmentDetectionTypeDef,
+    CreateFaceLivenessSessionRequestSettingsTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
     DatasetDescriptionTypeDef,
     DatasetLabelDescriptionTypeDef,
     ProjectDescriptionTypeDef,
-    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
-    ListCollectionsRequestListCollectionsPaginateTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-    ListFacesRequestListFacesPaginateTypeDef,
-    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
+    DeleteFacesResponseTypeDef,
     DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
     DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
     DetectLabelsImageBackgroundTypeDef,
     DetectLabelsImageForegroundTypeDef,
     InstanceTypeDef,
     DetectLabelsSettingsTypeDef,
     LabelDetectionSettingsTypeDef,
     DetectModerationLabelsResponseTypeDef,
+    DisassociateFacesResponseTypeDef,
     DistributeDatasetEntriesRequestRequestTypeDef,
     FaceDetailTypeDef,
     StreamProcessorSettingsTypeDef,
     GeometryTypeDef,
     RegionOfInterestTypeDef,
-    GroundTruthManifestTypeDef,
-    ImageTypeDef,
-    SummaryTypeDef,
-    VideoTypeDef,
     HumanLoopConfigTypeDef,
     StreamProcessingStartSelectorTypeDef,
     StreamProcessorInputTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
+    ListUsersResponseTypeDef,
+    UserMatchTypeDef,
     StreamProcessorOutputTypeDef,
     SegmentDetectionTypeDef,
-    StartSegmentDetectionFiltersTypeDef,
     FaceMatchTypeDef,
     ListFacesResponseTypeDef,
+    GetFaceLivenessSessionResultsResponseTypeDef,
+    AssetTypeDef,
+    DatasetSourceTypeDef,
+    CompareFacesRequestRequestTypeDef,
+    DetectCustomLabelsRequestRequestTypeDef,
+    DetectFacesRequestRequestTypeDef,
+    DetectProtectiveEquipmentRequestRequestTypeDef,
+    IndexFacesRequestRequestTypeDef,
+    RecognizeCelebritiesRequestRequestTypeDef,
+    SearchFacesByImageRequestRequestTypeDef,
+    SearchUsersByImageRequestRequestTypeDef,
+    EvaluationResultTypeDef,
+    StartCelebrityRecognitionRequestRequestTypeDef,
+    StartContentModerationRequestRequestTypeDef,
+    StartFaceDetectionRequestRequestTypeDef,
+    StartFaceSearchRequestRequestTypeDef,
+    StartPersonTrackingRequestRequestTypeDef,
+    StartSegmentDetectionFiltersTypeDef,
     CelebrityTypeDef,
     CompareFacesMatchTypeDef,
     GetContentModerationResponseTypeDef,
     ProtectiveEquipmentBodyPartTypeDef,
+    CreateFaceLivenessSessionRequestRequestTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     DescribeProjectsResponseTypeDef,
     DetectLabelsImagePropertiesTypeDef,
     LabelTypeDef,
+    DetectLabelsRequestRequestTypeDef,
+    StartLabelDetectionRequestRequestTypeDef,
     CelebrityDetailTypeDef,
     DetectFacesResponseTypeDef,
     FaceDetectionTypeDef,
     FaceRecordTypeDef,
     PersonDetailTypeDef,
+    SearchedFaceDetailsTypeDef,
     UnindexedFaceTypeDef,
+    UnsearchedFaceTypeDef,
     CustomLabelTypeDef,
     TextDetectionTypeDef,
     DetectTextFiltersTypeDef,
     StartTextDetectionFiltersTypeDef,
     UpdateStreamProcessorRequestRequestTypeDef,
-    AssetTypeDef,
-    DatasetSourceTypeDef,
-    CompareFacesRequestRequestTypeDef,
-    DetectCustomLabelsRequestRequestTypeDef,
-    DetectFacesRequestRequestTypeDef,
-    DetectLabelsRequestRequestTypeDef,
-    DetectProtectiveEquipmentRequestRequestTypeDef,
-    IndexFacesRequestRequestTypeDef,
-    RecognizeCelebritiesRequestRequestTypeDef,
-    SearchFacesByImageRequestRequestTypeDef,
-    EvaluationResultTypeDef,
-    StartCelebrityRecognitionRequestRequestTypeDef,
-    StartContentModerationRequestRequestTypeDef,
-    StartFaceDetectionRequestRequestTypeDef,
-    StartFaceSearchRequestRequestTypeDef,
-    StartLabelDetectionRequestRequestTypeDef,
-    StartPersonTrackingRequestRequestTypeDef,
     DetectModerationLabelsRequestRequestTypeDef,
     StartStreamProcessorRequestRequestTypeDef,
+    SearchUsersResponseTypeDef,
     CreateStreamProcessorRequestRequestTypeDef,
     DescribeStreamProcessorResponseTypeDef,
     GetSegmentDetectionResponseTypeDef,
-    StartSegmentDetectionRequestRequestTypeDef,
     SearchFacesByImageResponseTypeDef,
     SearchFacesResponseTypeDef,
+    TestingDataTypeDef,
+    TrainingDataTypeDef,
+    ValidationDataTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    StartSegmentDetectionRequestRequestTypeDef,
     RecognizeCelebritiesResponseTypeDef,
     CompareFacesResponseTypeDef,
     ProtectiveEquipmentPersonTypeDef,
     DetectLabelsResponseTypeDef,
     LabelDetectionTypeDef,
     CelebrityRecognitionTypeDef,
     GetFaceDetectionResponseTypeDef,
     PersonDetectionTypeDef,
     PersonMatchTypeDef,
     IndexFacesResponseTypeDef,
+    SearchUsersByImageResponseTypeDef,
     DetectCustomLabelsResponseTypeDef,
     DetectTextResponseTypeDef,
     TextDetectionResultTypeDef,
     DetectTextRequestRequestTypeDef,
     StartTextDetectionRequestRequestTypeDef,
-    TestingDataTypeDef,
-    TrainingDataTypeDef,
-    ValidationDataTypeDef,
-    CreateDatasetRequestRequestTypeDef,
+    CreateProjectVersionRequestRequestTypeDef,
+    TestingDataResultTypeDef,
+    TrainingDataResultTypeDef,
     DetectProtectiveEquipmentResponseTypeDef,
     GetLabelDetectionResponseTypeDef,
     GetCelebrityRecognitionResponseTypeDef,
     GetPersonTrackingResponseTypeDef,
     GetFaceSearchResponseTypeDef,
     GetTextDetectionResponseTypeDef,
-    CreateProjectVersionRequestRequestTypeDef,
-    TestingDataResultTypeDef,
-    TrainingDataResultTypeDef,
     ProjectVersionDescriptionTypeDef,
     DescribeProjectVersionsResponseTypeDef,
 )
 
 
 def get_structure() -> AgeRangeTypeDef:
     return {...}
@@ -642,43 +721,43 @@
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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/setup.py` & `types-aiobotocore-rekognition-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rekognition.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rekognition",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rekognition"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Rekognition 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Rekognition 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/"
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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__init__.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__init__.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -11,14 +11,15 @@
         DescribeProjectsPaginator,
         ListCollectionsPaginator,
         ListDatasetEntriesPaginator,
         ListDatasetLabelsPaginator,
         ListFacesPaginator,
         ListProjectPoliciesPaginator,
         ListStreamProcessorsPaginator,
+        ListUsersPaginator,
         ProjectVersionRunningWaiter,
         ProjectVersionTrainingCompletedWaiter,
         RekognitionClient,
     )
 
     session = get_session()
     async with session.create_client("rekognition") as client:
@@ -33,39 +34,41 @@
     describe_projects_paginator: DescribeProjectsPaginator = client.get_paginator("describe_projects")
     list_collections_paginator: ListCollectionsPaginator = client.get_paginator("list_collections")
     list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
     list_dataset_labels_paginator: ListDatasetLabelsPaginator = client.get_paginator("list_dataset_labels")
     list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
     list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator("list_project_policies")
     list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator("list_stream_processors")
+    list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
 from .client import RekognitionClient
 from .paginator import (
     DescribeProjectsPaginator,
     DescribeProjectVersionsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 from .waiter import ProjectVersionRunningWaiter, ProjectVersionTrainingCompletedWaiter
 
 Client = RekognitionClient
 
-
 __all__ = (
     "Client",
     "DescribeProjectVersionsPaginator",
     "DescribeProjectsPaginator",
     "ListCollectionsPaginator",
     "ListDatasetEntriesPaginator",
     "ListDatasetLabelsPaginator",
     "ListFacesPaginator",
     "ListProjectPoliciesPaginator",
     "ListStreamProcessorsPaginator",
+    "ListUsersPaginator",
     "ProjectVersionRunningWaiter",
     "ProjectVersionTrainingCompletedWaiter",
     "RekognitionClient",
 )
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__init__.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,14 +11,15 @@
         DescribeProjectsPaginator,
         ListCollectionsPaginator,
         ListDatasetEntriesPaginator,
         ListDatasetLabelsPaginator,
         ListFacesPaginator,
         ListProjectPoliciesPaginator,
         ListStreamProcessorsPaginator,
+        ListUsersPaginator,
         ProjectVersionRunningWaiter,
         ProjectVersionTrainingCompletedWaiter,
         RekognitionClient,
     )
 
     session = get_session()
     async with session.create_client("rekognition") as client:
@@ -33,38 +34,42 @@
     describe_projects_paginator: DescribeProjectsPaginator = client.get_paginator("describe_projects")
     list_collections_paginator: ListCollectionsPaginator = client.get_paginator("list_collections")
     list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
     list_dataset_labels_paginator: ListDatasetLabelsPaginator = client.get_paginator("list_dataset_labels")
     list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
     list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator("list_project_policies")
     list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator("list_stream_processors")
+    list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
 from .client import RekognitionClient
 from .paginator import (
     DescribeProjectsPaginator,
     DescribeProjectVersionsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 from .waiter import ProjectVersionRunningWaiter, ProjectVersionTrainingCompletedWaiter
 
 Client = RekognitionClient
 
+
 __all__ = (
     "Client",
     "DescribeProjectVersionsPaginator",
     "DescribeProjectsPaginator",
     "ListCollectionsPaginator",
     "ListDatasetEntriesPaginator",
     "ListDatasetLabelsPaginator",
     "ListFacesPaginator",
     "ListProjectPoliciesPaginator",
     "ListStreamProcessorsPaginator",
+    "ListUsersPaginator",
     "ProjectVersionRunningWaiter",
     "ProjectVersionTrainingCompletedWaiter",
     "RekognitionClient",
 )
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/__main__.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Rekognition 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Rekognition 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition\nOther"
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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/client.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/client.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AttributeType,
     CelebrityRecognitionSortByType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetTypeType,
     DetectLabelsFeatureNameType,
     FaceAttributesType,
     FaceSearchSortByType,
     LabelDetectionAggregateByType,
     LabelDetectionSortByType,
@@ -40,20 +41,24 @@
     DescribeProjectVersionsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 from .type_defs import (
+    AssociateFacesResponseTypeDef,
     CompareFacesResponseTypeDef,
     CopyProjectVersionResponseTypeDef,
     CreateCollectionResponseTypeDef,
     CreateDatasetResponseTypeDef,
+    CreateFaceLivenessSessionRequestSettingsTypeDef,
+    CreateFaceLivenessSessionResponseTypeDef,
     CreateProjectResponseTypeDef,
     CreateProjectVersionResponseTypeDef,
     CreateStreamProcessorResponseTypeDef,
     DatasetChangesTypeDef,
     DatasetSourceTypeDef,
     DeleteCollectionResponseTypeDef,
     DeleteFacesResponseTypeDef,
@@ -68,19 +73,21 @@
     DetectFacesResponseTypeDef,
     DetectLabelsResponseTypeDef,
     DetectLabelsSettingsTypeDef,
     DetectModerationLabelsResponseTypeDef,
     DetectProtectiveEquipmentResponseTypeDef,
     DetectTextFiltersTypeDef,
     DetectTextResponseTypeDef,
+    DisassociateFacesResponseTypeDef,
     DistributeDatasetTypeDef,
     GetCelebrityInfoResponseTypeDef,
     GetCelebrityRecognitionResponseTypeDef,
     GetContentModerationResponseTypeDef,
     GetFaceDetectionResponseTypeDef,
+    GetFaceLivenessSessionResultsResponseTypeDef,
     GetFaceSearchResponseTypeDef,
     GetLabelDetectionResponseTypeDef,
     GetPersonTrackingResponseTypeDef,
     GetSegmentDetectionResponseTypeDef,
     GetTextDetectionResponseTypeDef,
     HumanLoopConfigTypeDef,
     ImageTypeDef,
@@ -89,22 +96,25 @@
     ListCollectionsResponseTypeDef,
     ListDatasetEntriesResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     ListFacesResponseTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListUsersResponseTypeDef,
     NotificationChannelTypeDef,
     OutputConfigTypeDef,
     ProtectiveEquipmentSummarizationAttributesTypeDef,
     PutProjectPolicyResponseTypeDef,
     RecognizeCelebritiesResponseTypeDef,
     RegionOfInterestTypeDef,
     SearchFacesByImageResponseTypeDef,
     SearchFacesResponseTypeDef,
+    SearchUsersByImageResponseTypeDef,
+    SearchUsersResponseTypeDef,
     StartCelebrityRecognitionResponseTypeDef,
     StartContentModerationResponseTypeDef,
     StartFaceDetectionResponseTypeDef,
     StartFaceSearchResponseTypeDef,
     StartLabelDetectionResponseTypeDef,
     StartPersonTrackingResponseTypeDef,
     StartProjectVersionResponseTypeDef,
@@ -144,14 +154,15 @@
         self.response: Dict[str, Any]
         self.operation_name: str
 
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     HumanLoopQuotaExceededException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     ImageTooLargeException: Type[BotocoreClientError]
     InternalServerError: Type[BotocoreClientError]
     InvalidImageFormatException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
@@ -161,14 +172,15 @@
     MalformedPolicyDocumentException: Type[BotocoreClientError]
     ProvisionedThroughputExceededException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceNotReadyException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    SessionNotFoundException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     VideoTooLargeException: Type[BotocoreClientError]
 
 
 class RekognitionClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client)
@@ -182,14 +194,30 @@
         """
         RekognitionClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#exceptions)
         """
 
+    async def associate_faces(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str,
+        FaceIds: Sequence[str],
+        UserMatchThreshold: float = ...,
+        ClientRequestToken: str = ...
+    ) -> AssociateFacesResponseTypeDef:
+        """
+        Associates one or more faces with an existing UserID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.associate_faces)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#associate_faces)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#can_paginate)
         """
@@ -257,14 +285,28 @@
         """
         Creates a new Amazon Rekognition Custom Labels dataset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_dataset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_dataset)
         """
 
+    async def create_face_liveness_session(
+        self,
+        *,
+        KmsKeyId: str = ...,
+        Settings: CreateFaceLivenessSessionRequestSettingsTypeDef = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateFaceLivenessSessionResponseTypeDef:
+        """
+        This API operation initiates a Face Liveness session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_face_liveness_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_face_liveness_session)
+        """
+
     async def create_project(self, *, ProjectName: str) -> CreateProjectResponseTypeDef:
         """
         Creates a new Amazon Rekognition Custom Labels project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_project)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_project)
         """
@@ -305,14 +347,24 @@
         Creates an Amazon Rekognition stream processor that you can use to detect and
         recognize faces or to detect labels in a streaming video.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_stream_processor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_stream_processor)
         """
 
+    async def create_user(
+        self, *, CollectionId: str, UserId: str, ClientRequestToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Creates a new User within a collection specified by `CollectionId`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_user)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_user)
+        """
+
     async def delete_collection(self, *, CollectionId: str) -> DeleteCollectionResponseTypeDef:
         """
         Deletes the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_collection)
         """
@@ -367,14 +419,24 @@
         """
         Deletes the stream processor identified by `Name`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_stream_processor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_stream_processor)
         """
 
+    async def delete_user(
+        self, *, CollectionId: str, UserId: str, ClientRequestToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Deletes the specified UserID within the collection.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_user)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_user)
+        """
+
     async def describe_collection(self, *, CollectionId: str) -> DescribeCollectionResponseTypeDef:
         """
         Describes the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.describe_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#describe_collection)
         """
@@ -499,14 +561,30 @@
         """
         Detects text in the input image and converts it into machine-readable text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.detect_text)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#detect_text)
         """
 
+    async def disassociate_faces(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str,
+        FaceIds: Sequence[str],
+        ClientRequestToken: str = ...
+    ) -> DisassociateFacesResponseTypeDef:
+        """
+        Removes the association between a `Face` supplied in an array of `FaceIds` and
+        the User.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.disassociate_faces)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#disassociate_faces)
+        """
+
     async def distribute_dataset_entries(
         self, *, Datasets: Sequence[DistributeDatasetTypeDef]
     ) -> Dict[str, Any]:
         """
         Distributes the entries (images) in a training dataset across the training
         dataset and the test dataset for a project.
 
@@ -555,15 +633,16 @@
 
     async def get_content_moderation(
         self,
         *,
         JobId: str,
         MaxResults: int = ...,
         NextToken: str = ...,
-        SortBy: ContentModerationSortByType = ...
+        SortBy: ContentModerationSortByType = ...,
+        AggregateBy: ContentModerationAggregateByType = ...
     ) -> GetContentModerationResponseTypeDef:
         """
         Gets the inappropriate, unwanted, or offensive content analysis results for a
         Amazon Rekognition Video analysis started by  StartContentModeration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_content_moderation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_content_moderation)
@@ -576,14 +655,24 @@
         Gets face detection results for a Amazon Rekognition Video analysis started by
         StartFaceDetection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_face_detection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_face_detection)
         """
 
+    async def get_face_liveness_session_results(
+        self, *, SessionId: str
+    ) -> GetFaceLivenessSessionResultsResponseTypeDef:
+        """
+        Retrieves the results of a specific Face Liveness session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_face_liveness_session_results)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_face_liveness_session_results)
+        """
+
     async def get_face_search(
         self,
         *,
         JobId: str,
         MaxResults: int = ...,
         NextToken: str = ...,
         SortBy: FaceSearchSortByType = ...
@@ -703,15 +792,21 @@
         Lists the labels in a dataset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_dataset_labels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_dataset_labels)
         """
 
     async def list_faces(
-        self, *, CollectionId: str, NextToken: str = ..., MaxResults: int = ...
+        self,
+        *,
+        CollectionId: str,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        UserId: str = ...,
+        FaceIds: Sequence[str] = ...
     ) -> ListFacesResponseTypeDef:
         """
         Returns metadata for faces in the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_faces)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_faces)
         """
@@ -744,14 +839,24 @@
         Returns a list of tags in an Amazon Rekognition collection, stream processor, or
         Custom Labels model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_tags_for_resource)
         """
 
+    async def list_users(
+        self, *, CollectionId: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListUsersResponseTypeDef:
+        """
+        Returns metadata of the User such as `UserID` in the specified collection.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_users)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_users)
+        """
+
     async def put_project_policy(
         self, *, ProjectArn: str, PolicyName: str, PolicyDocument: str, PolicyRevisionId: str = ...
     ) -> PutProjectPolicyResponseTypeDef:
         """
         Attaches a project policy to a Amazon Rekognition Custom Labels project in a
         trusting AWS account.
 
@@ -798,14 +903,46 @@
         For a given input image, first detects the largest face in the image, and then
         searches the specified collection for matching faces.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_faces_by_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_faces_by_image)
         """
 
+    async def search_users(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str = ...,
+        FaceId: str = ...,
+        UserMatchThreshold: float = ...,
+        MaxUsers: int = ...
+    ) -> SearchUsersResponseTypeDef:
+        """
+        Searches for UserIDs within a collection based on a `FaceId` or `UserId`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_users)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_users)
+        """
+
+    async def search_users_by_image(
+        self,
+        *,
+        CollectionId: str,
+        Image: ImageTypeDef,
+        UserMatchThreshold: float = ...,
+        MaxUsers: int = ...,
+        QualityFilter: QualityFilterType = ...
+    ) -> SearchUsersByImageResponseTypeDef:
+        """
+        Searches for UserIDs using a supplied image.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_users_by_image)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_users_by_image)
+        """
+
     async def start_celebrity_recognition(
         self,
         *,
         Video: VideoTypeDef,
         ClientRequestToken: str = ...,
         NotificationChannel: NotificationChannelTypeDef = ...,
         JobTag: str = ...
@@ -1087,14 +1224,21 @@
     ) -> ListStreamProcessorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(self, operation_name: Literal["list_users"]) -> ListUsersPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_paginator)
+        """
+
+    @overload
     def get_waiter(
         self, waiter_name: Literal["project_version_running"]
     ) -> ProjectVersionRunningWaiter:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_waiter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_waiter)
         """
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/client.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/client.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AttributeType,
     CelebrityRecognitionSortByType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetTypeType,
     DetectLabelsFeatureNameType,
     FaceAttributesType,
     FaceSearchSortByType,
     LabelDetectionAggregateByType,
     LabelDetectionSortByType,
@@ -40,20 +41,24 @@
     DescribeProjectVersionsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 from .type_defs import (
+    AssociateFacesResponseTypeDef,
     CompareFacesResponseTypeDef,
     CopyProjectVersionResponseTypeDef,
     CreateCollectionResponseTypeDef,
     CreateDatasetResponseTypeDef,
+    CreateFaceLivenessSessionRequestSettingsTypeDef,
+    CreateFaceLivenessSessionResponseTypeDef,
     CreateProjectResponseTypeDef,
     CreateProjectVersionResponseTypeDef,
     CreateStreamProcessorResponseTypeDef,
     DatasetChangesTypeDef,
     DatasetSourceTypeDef,
     DeleteCollectionResponseTypeDef,
     DeleteFacesResponseTypeDef,
@@ -68,19 +73,21 @@
     DetectFacesResponseTypeDef,
     DetectLabelsResponseTypeDef,
     DetectLabelsSettingsTypeDef,
     DetectModerationLabelsResponseTypeDef,
     DetectProtectiveEquipmentResponseTypeDef,
     DetectTextFiltersTypeDef,
     DetectTextResponseTypeDef,
+    DisassociateFacesResponseTypeDef,
     DistributeDatasetTypeDef,
     GetCelebrityInfoResponseTypeDef,
     GetCelebrityRecognitionResponseTypeDef,
     GetContentModerationResponseTypeDef,
     GetFaceDetectionResponseTypeDef,
+    GetFaceLivenessSessionResultsResponseTypeDef,
     GetFaceSearchResponseTypeDef,
     GetLabelDetectionResponseTypeDef,
     GetPersonTrackingResponseTypeDef,
     GetSegmentDetectionResponseTypeDef,
     GetTextDetectionResponseTypeDef,
     HumanLoopConfigTypeDef,
     ImageTypeDef,
@@ -89,22 +96,25 @@
     ListCollectionsResponseTypeDef,
     ListDatasetEntriesResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     ListFacesResponseTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListUsersResponseTypeDef,
     NotificationChannelTypeDef,
     OutputConfigTypeDef,
     ProtectiveEquipmentSummarizationAttributesTypeDef,
     PutProjectPolicyResponseTypeDef,
     RecognizeCelebritiesResponseTypeDef,
     RegionOfInterestTypeDef,
     SearchFacesByImageResponseTypeDef,
     SearchFacesResponseTypeDef,
+    SearchUsersByImageResponseTypeDef,
+    SearchUsersResponseTypeDef,
     StartCelebrityRecognitionResponseTypeDef,
     StartContentModerationResponseTypeDef,
     StartFaceDetectionResponseTypeDef,
     StartFaceSearchResponseTypeDef,
     StartLabelDetectionResponseTypeDef,
     StartPersonTrackingResponseTypeDef,
     StartProjectVersionResponseTypeDef,
@@ -141,14 +151,15 @@
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     HumanLoopQuotaExceededException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     ImageTooLargeException: Type[BotocoreClientError]
     InternalServerError: Type[BotocoreClientError]
     InvalidImageFormatException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
@@ -158,14 +169,15 @@
     MalformedPolicyDocumentException: Type[BotocoreClientError]
     ProvisionedThroughputExceededException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceNotReadyException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    SessionNotFoundException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     VideoTooLargeException: Type[BotocoreClientError]
 
 class RekognitionClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/)
@@ -177,14 +189,29 @@
     def exceptions(self) -> Exceptions:
         """
         RekognitionClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#exceptions)
         """
+    async def associate_faces(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str,
+        FaceIds: Sequence[str],
+        UserMatchThreshold: float = ...,
+        ClientRequestToken: str = ...
+    ) -> AssociateFacesResponseTypeDef:
+        """
+        Associates one or more faces with an existing UserID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.associate_faces)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#associate_faces)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#can_paginate)
         """
@@ -246,14 +273,27 @@
     ) -> CreateDatasetResponseTypeDef:
         """
         Creates a new Amazon Rekognition Custom Labels dataset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_dataset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_dataset)
         """
+    async def create_face_liveness_session(
+        self,
+        *,
+        KmsKeyId: str = ...,
+        Settings: CreateFaceLivenessSessionRequestSettingsTypeDef = ...,
+        ClientRequestToken: str = ...
+    ) -> CreateFaceLivenessSessionResponseTypeDef:
+        """
+        This API operation initiates a Face Liveness session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_face_liveness_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_face_liveness_session)
+        """
     async def create_project(self, *, ProjectName: str) -> CreateProjectResponseTypeDef:
         """
         Creates a new Amazon Rekognition Custom Labels project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_project)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_project)
         """
@@ -291,14 +331,23 @@
         """
         Creates an Amazon Rekognition stream processor that you can use to detect and
         recognize faces or to detect labels in a streaming video.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_stream_processor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_stream_processor)
         """
+    async def create_user(
+        self, *, CollectionId: str, UserId: str, ClientRequestToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Creates a new User within a collection specified by `CollectionId`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.create_user)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#create_user)
+        """
     async def delete_collection(self, *, CollectionId: str) -> DeleteCollectionResponseTypeDef:
         """
         Deletes the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_collection)
         """
@@ -346,14 +395,23 @@
     async def delete_stream_processor(self, *, Name: str) -> Dict[str, Any]:
         """
         Deletes the stream processor identified by `Name`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_stream_processor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_stream_processor)
         """
+    async def delete_user(
+        self, *, CollectionId: str, UserId: str, ClientRequestToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Deletes the specified UserID within the collection.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.delete_user)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#delete_user)
+        """
     async def describe_collection(self, *, CollectionId: str) -> DescribeCollectionResponseTypeDef:
         """
         Describes the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.describe_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#describe_collection)
         """
@@ -467,14 +525,29 @@
     ) -> DetectTextResponseTypeDef:
         """
         Detects text in the input image and converts it into machine-readable text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.detect_text)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#detect_text)
         """
+    async def disassociate_faces(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str,
+        FaceIds: Sequence[str],
+        ClientRequestToken: str = ...
+    ) -> DisassociateFacesResponseTypeDef:
+        """
+        Removes the association between a `Face` supplied in an array of `FaceIds` and
+        the User.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.disassociate_faces)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#disassociate_faces)
+        """
     async def distribute_dataset_entries(
         self, *, Datasets: Sequence[DistributeDatasetTypeDef]
     ) -> Dict[str, Any]:
         """
         Distributes the entries (images) in a training dataset across the training
         dataset and the test dataset for a project.
 
@@ -519,15 +592,16 @@
         """
     async def get_content_moderation(
         self,
         *,
         JobId: str,
         MaxResults: int = ...,
         NextToken: str = ...,
-        SortBy: ContentModerationSortByType = ...
+        SortBy: ContentModerationSortByType = ...,
+        AggregateBy: ContentModerationAggregateByType = ...
     ) -> GetContentModerationResponseTypeDef:
         """
         Gets the inappropriate, unwanted, or offensive content analysis results for a
         Amazon Rekognition Video analysis started by  StartContentModeration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_content_moderation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_content_moderation)
@@ -538,14 +612,23 @@
         """
         Gets face detection results for a Amazon Rekognition Video analysis started by
         StartFaceDetection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_face_detection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_face_detection)
         """
+    async def get_face_liveness_session_results(
+        self, *, SessionId: str
+    ) -> GetFaceLivenessSessionResultsResponseTypeDef:
+        """
+        Retrieves the results of a specific Face Liveness session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_face_liveness_session_results)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_face_liveness_session_results)
+        """
     async def get_face_search(
         self,
         *,
         JobId: str,
         MaxResults: int = ...,
         NextToken: str = ...,
         SortBy: FaceSearchSortByType = ...
@@ -656,15 +739,21 @@
         """
         Lists the labels in a dataset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_dataset_labels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_dataset_labels)
         """
     async def list_faces(
-        self, *, CollectionId: str, NextToken: str = ..., MaxResults: int = ...
+        self,
+        *,
+        CollectionId: str,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        UserId: str = ...,
+        FaceIds: Sequence[str] = ...
     ) -> ListFacesResponseTypeDef:
         """
         Returns metadata for faces in the specified collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_faces)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_faces)
         """
@@ -693,14 +782,23 @@
         """
         Returns a list of tags in an Amazon Rekognition collection, stream processor, or
         Custom Labels model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_tags_for_resource)
         """
+    async def list_users(
+        self, *, CollectionId: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListUsersResponseTypeDef:
+        """
+        Returns metadata of the User such as `UserID` in the specified collection.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.list_users)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#list_users)
+        """
     async def put_project_policy(
         self, *, ProjectArn: str, PolicyName: str, PolicyDocument: str, PolicyRevisionId: str = ...
     ) -> PutProjectPolicyResponseTypeDef:
         """
         Attaches a project policy to a Amazon Rekognition Custom Labels project in a
         trusting AWS account.
 
@@ -743,14 +841,44 @@
         """
         For a given input image, first detects the largest face in the image, and then
         searches the specified collection for matching faces.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_faces_by_image)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_faces_by_image)
         """
+    async def search_users(
+        self,
+        *,
+        CollectionId: str,
+        UserId: str = ...,
+        FaceId: str = ...,
+        UserMatchThreshold: float = ...,
+        MaxUsers: int = ...
+    ) -> SearchUsersResponseTypeDef:
+        """
+        Searches for UserIDs within a collection based on a `FaceId` or `UserId`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_users)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_users)
+        """
+    async def search_users_by_image(
+        self,
+        *,
+        CollectionId: str,
+        Image: ImageTypeDef,
+        UserMatchThreshold: float = ...,
+        MaxUsers: int = ...,
+        QualityFilter: QualityFilterType = ...
+    ) -> SearchUsersByImageResponseTypeDef:
+        """
+        Searches for UserIDs using a supplied image.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.search_users_by_image)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#search_users_by_image)
+        """
     async def start_celebrity_recognition(
         self,
         *,
         Video: VideoTypeDef,
         ClientRequestToken: str = ...,
         NotificationChannel: NotificationChannelTypeDef = ...,
         JobTag: str = ...
@@ -1008,14 +1136,20 @@
         self, operation_name: Literal["list_stream_processors"]
     ) -> ListStreamProcessorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_paginator)
         """
     @overload
+    def get_paginator(self, operation_name: Literal["list_users"]) -> ListUsersPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_paginator)
+        """
+    @overload
     def get_waiter(
         self, waiter_name: Literal["project_version_running"]
     ) -> ProjectVersionRunningWaiter:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Client.get_waiter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/client/#get_waiter)
         """
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/literals.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -4,30 +4,30 @@
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/literals/)
 
 Usage::
 
     ```python
     from types_aiobotocore_rekognition.literals import AttributeType
 
-    data: AttributeType = "ALL"
+    data: AttributeType = "AGE_RANGE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AttributeType",
     "BodyPartType",
     "CelebrityRecognitionSortByType",
     "ContentClassifierType",
+    "ContentModerationAggregateByType",
     "ContentModerationSortByType",
     "DatasetStatusMessageCodeType",
     "DatasetStatusType",
     "DatasetTypeType",
     "DescribeProjectVersionsPaginatorName",
     "DescribeProjectsPaginatorName",
     "DetectLabelsFeatureNameType",
@@ -42,43 +42,65 @@
     "LandmarkTypeType",
     "ListCollectionsPaginatorName",
     "ListDatasetEntriesPaginatorName",
     "ListDatasetLabelsPaginatorName",
     "ListFacesPaginatorName",
     "ListProjectPoliciesPaginatorName",
     "ListStreamProcessorsPaginatorName",
+    "ListUsersPaginatorName",
+    "LivenessSessionStatusType",
     "OrientationCorrectionType",
     "PersonTrackingSortByType",
     "ProjectStatusType",
     "ProjectVersionRunningWaiterName",
     "ProjectVersionStatusType",
     "ProjectVersionTrainingCompletedWaiterName",
     "ProtectiveEquipmentTypeType",
     "QualityFilterType",
     "ReasonType",
     "SegmentTypeType",
     "StreamProcessorParameterToDeleteType",
     "StreamProcessorStatusType",
     "TechnicalCueTypeType",
     "TextTypesType",
+    "UnsearchedFaceReasonType",
+    "UnsuccessfulFaceAssociationReasonType",
+    "UnsuccessfulFaceDeletionReasonType",
+    "UnsuccessfulFaceDisassociationReasonType",
+    "UserStatusType",
     "VideoColorRangeType",
     "VideoJobStatusType",
     "RekognitionServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
-AttributeType = Literal["ALL", "DEFAULT"]
+AttributeType = Literal[
+    "AGE_RANGE",
+    "ALL",
+    "BEARD",
+    "DEFAULT",
+    "EMOTIONS",
+    "EYEGLASSES",
+    "EYES_OPEN",
+    "EYE_DIRECTION",
+    "FACE_OCCLUDED",
+    "GENDER",
+    "MOUTH_OPEN",
+    "MUSTACHE",
+    "SMILE",
+    "SUNGLASSES",
+]
 BodyPartType = Literal["FACE", "HEAD", "LEFT_HAND", "RIGHT_HAND"]
 CelebrityRecognitionSortByType = Literal["ID", "TIMESTAMP"]
 ContentClassifierType = Literal["FreeOfAdultContent", "FreeOfPersonallyIdentifiableInformation"]
+ContentModerationAggregateByType = Literal["SEGMENTS", "TIMESTAMPS"]
 ContentModerationSortByType = Literal["NAME", "TIMESTAMP"]
 DatasetStatusMessageCodeType = Literal["CLIENT_ERROR", "SERVICE_ERROR", "SUCCESS"]
 DatasetStatusType = Literal[
     "CREATE_COMPLETE",
     "CREATE_FAILED",
     "CREATE_IN_PROGRESS",
     "DELETE_IN_PROGRESS",
@@ -134,14 +156,16 @@
 ]
 ListCollectionsPaginatorName = Literal["list_collections"]
 ListDatasetEntriesPaginatorName = Literal["list_dataset_entries"]
 ListDatasetLabelsPaginatorName = Literal["list_dataset_labels"]
 ListFacesPaginatorName = Literal["list_faces"]
 ListProjectPoliciesPaginatorName = Literal["list_project_policies"]
 ListStreamProcessorsPaginatorName = Literal["list_stream_processors"]
+ListUsersPaginatorName = Literal["list_users"]
+LivenessSessionStatusType = Literal["CREATED", "EXPIRED", "FAILED", "IN_PROGRESS", "SUCCEEDED"]
 OrientationCorrectionType = Literal["ROTATE_0", "ROTATE_180", "ROTATE_270", "ROTATE_90"]
 PersonTrackingSortByType = Literal["INDEX", "TIMESTAMP"]
 ProjectStatusType = Literal["CREATED", "CREATING", "DELETING"]
 ProjectVersionRunningWaiterName = Literal["project_version_running"]
 ProjectVersionStatusType = Literal[
     "COPYING_COMPLETED",
     "COPYING_FAILED",
@@ -173,14 +197,32 @@
 StreamProcessorStatusType = Literal[
     "FAILED", "RUNNING", "STARTING", "STOPPED", "STOPPING", "UPDATING"
 ]
 TechnicalCueTypeType = Literal[
     "BlackFrames", "ColorBars", "Content", "EndCredits", "OpeningCredits", "Slate", "StudioLogo"
 ]
 TextTypesType = Literal["LINE", "WORD"]
+UnsearchedFaceReasonType = Literal[
+    "EXCEEDS_MAX_FACES",
+    "EXTREME_POSE",
+    "FACE_NOT_LARGEST",
+    "LOW_BRIGHTNESS",
+    "LOW_CONFIDENCE",
+    "LOW_FACE_QUALITY",
+    "LOW_SHARPNESS",
+    "SMALL_BOUNDING_BOX",
+]
+UnsuccessfulFaceAssociationReasonType = Literal[
+    "ASSOCIATED_TO_A_DIFFERENT_USER", "FACE_NOT_FOUND", "LOW_MATCH_CONFIDENCE"
+]
+UnsuccessfulFaceDeletionReasonType = Literal["ASSOCIATED_TO_AN_EXISTING_USER", "FACE_NOT_FOUND"]
+UnsuccessfulFaceDisassociationReasonType = Literal[
+    "ASSOCIATED_TO_A_DIFFERENT_USER", "FACE_NOT_FOUND"
+]
+UserStatusType = Literal["ACTIVE", "CREATED", "CREATING", "UPDATING"]
 VideoColorRangeType = Literal["FULL", "LIMITED"]
 VideoJobStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 RekognitionServiceName = Literal["rekognition"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -238,14 +280,15 @@
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
@@ -324,14 +367,15 @@
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
@@ -342,14 +386,15 @@
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
@@ -385,14 +430,15 @@
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
@@ -411,16 +457,19 @@
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
@@ -504,15 +553,17 @@
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
@@ -539,14 +590,15 @@
     "describe_projects",
     "list_collections",
     "list_dataset_entries",
     "list_dataset_labels",
     "list_faces",
     "list_project_policies",
     "list_stream_processors",
+    "list_users",
 ]
 WaiterName = Literal["project_version_running", "project_version_training_completed"]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/literals.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/literals.py`

 * *Files 9% similar despite different names*

```diff
@@ -4,29 +4,31 @@
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/literals/)
 
 Usage::
 
     ```python
     from types_aiobotocore_rekognition.literals import AttributeType
 
-    data: AttributeType = "ALL"
+    data: AttributeType = "AGE_RANGE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AttributeType",
     "BodyPartType",
     "CelebrityRecognitionSortByType",
     "ContentClassifierType",
+    "ContentModerationAggregateByType",
     "ContentModerationSortByType",
     "DatasetStatusMessageCodeType",
     "DatasetStatusType",
     "DatasetTypeType",
     "DescribeProjectVersionsPaginatorName",
     "DescribeProjectsPaginatorName",
     "DetectLabelsFeatureNameType",
@@ -41,42 +43,66 @@
     "LandmarkTypeType",
     "ListCollectionsPaginatorName",
     "ListDatasetEntriesPaginatorName",
     "ListDatasetLabelsPaginatorName",
     "ListFacesPaginatorName",
     "ListProjectPoliciesPaginatorName",
     "ListStreamProcessorsPaginatorName",
+    "ListUsersPaginatorName",
+    "LivenessSessionStatusType",
     "OrientationCorrectionType",
     "PersonTrackingSortByType",
     "ProjectStatusType",
     "ProjectVersionRunningWaiterName",
     "ProjectVersionStatusType",
     "ProjectVersionTrainingCompletedWaiterName",
     "ProtectiveEquipmentTypeType",
     "QualityFilterType",
     "ReasonType",
     "SegmentTypeType",
     "StreamProcessorParameterToDeleteType",
     "StreamProcessorStatusType",
     "TechnicalCueTypeType",
     "TextTypesType",
+    "UnsearchedFaceReasonType",
+    "UnsuccessfulFaceAssociationReasonType",
+    "UnsuccessfulFaceDeletionReasonType",
+    "UnsuccessfulFaceDisassociationReasonType",
+    "UserStatusType",
     "VideoColorRangeType",
     "VideoJobStatusType",
     "RekognitionServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-AttributeType = Literal["ALL", "DEFAULT"]
+
+AttributeType = Literal[
+    "AGE_RANGE",
+    "ALL",
+    "BEARD",
+    "DEFAULT",
+    "EMOTIONS",
+    "EYEGLASSES",
+    "EYES_OPEN",
+    "EYE_DIRECTION",
+    "FACE_OCCLUDED",
+    "GENDER",
+    "MOUTH_OPEN",
+    "MUSTACHE",
+    "SMILE",
+    "SUNGLASSES",
+]
 BodyPartType = Literal["FACE", "HEAD", "LEFT_HAND", "RIGHT_HAND"]
 CelebrityRecognitionSortByType = Literal["ID", "TIMESTAMP"]
 ContentClassifierType = Literal["FreeOfAdultContent", "FreeOfPersonallyIdentifiableInformation"]
+ContentModerationAggregateByType = Literal["SEGMENTS", "TIMESTAMPS"]
 ContentModerationSortByType = Literal["NAME", "TIMESTAMP"]
 DatasetStatusMessageCodeType = Literal["CLIENT_ERROR", "SERVICE_ERROR", "SUCCESS"]
 DatasetStatusType = Literal[
     "CREATE_COMPLETE",
     "CREATE_FAILED",
     "CREATE_IN_PROGRESS",
     "DELETE_IN_PROGRESS",
@@ -132,14 +158,16 @@
 ]
 ListCollectionsPaginatorName = Literal["list_collections"]
 ListDatasetEntriesPaginatorName = Literal["list_dataset_entries"]
 ListDatasetLabelsPaginatorName = Literal["list_dataset_labels"]
 ListFacesPaginatorName = Literal["list_faces"]
 ListProjectPoliciesPaginatorName = Literal["list_project_policies"]
 ListStreamProcessorsPaginatorName = Literal["list_stream_processors"]
+ListUsersPaginatorName = Literal["list_users"]
+LivenessSessionStatusType = Literal["CREATED", "EXPIRED", "FAILED", "IN_PROGRESS", "SUCCEEDED"]
 OrientationCorrectionType = Literal["ROTATE_0", "ROTATE_180", "ROTATE_270", "ROTATE_90"]
 PersonTrackingSortByType = Literal["INDEX", "TIMESTAMP"]
 ProjectStatusType = Literal["CREATED", "CREATING", "DELETING"]
 ProjectVersionRunningWaiterName = Literal["project_version_running"]
 ProjectVersionStatusType = Literal[
     "COPYING_COMPLETED",
     "COPYING_FAILED",
@@ -171,14 +199,32 @@
 StreamProcessorStatusType = Literal[
     "FAILED", "RUNNING", "STARTING", "STOPPED", "STOPPING", "UPDATING"
 ]
 TechnicalCueTypeType = Literal[
     "BlackFrames", "ColorBars", "Content", "EndCredits", "OpeningCredits", "Slate", "StudioLogo"
 ]
 TextTypesType = Literal["LINE", "WORD"]
+UnsearchedFaceReasonType = Literal[
+    "EXCEEDS_MAX_FACES",
+    "EXTREME_POSE",
+    "FACE_NOT_LARGEST",
+    "LOW_BRIGHTNESS",
+    "LOW_CONFIDENCE",
+    "LOW_FACE_QUALITY",
+    "LOW_SHARPNESS",
+    "SMALL_BOUNDING_BOX",
+]
+UnsuccessfulFaceAssociationReasonType = Literal[
+    "ASSOCIATED_TO_A_DIFFERENT_USER", "FACE_NOT_FOUND", "LOW_MATCH_CONFIDENCE"
+]
+UnsuccessfulFaceDeletionReasonType = Literal["ASSOCIATED_TO_AN_EXISTING_USER", "FACE_NOT_FOUND"]
+UnsuccessfulFaceDisassociationReasonType = Literal[
+    "ASSOCIATED_TO_A_DIFFERENT_USER", "FACE_NOT_FOUND"
+]
+UserStatusType = Literal["ACTIVE", "CREATED", "CREATING", "UPDATING"]
 VideoColorRangeType = Literal["FULL", "LIMITED"]
 VideoJobStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 RekognitionServiceName = Literal["rekognition"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -236,14 +282,15 @@
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
@@ -322,14 +369,15 @@
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
@@ -340,14 +388,15 @@
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
@@ -383,14 +432,15 @@
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
@@ -409,16 +459,19 @@
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
@@ -502,15 +555,17 @@
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
@@ -537,14 +592,15 @@
     "describe_projects",
     "list_collections",
     "list_dataset_entries",
     "list_dataset_labels",
     "list_faces",
     "list_project_policies",
     "list_stream_processors",
+    "list_users",
 ]
 WaiterName = Literal["project_version_running", "project_version_training_completed"]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/paginator.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,63 +14,60 @@
         DescribeProjectsPaginator,
         ListCollectionsPaginator,
         ListDatasetEntriesPaginator,
         ListDatasetLabelsPaginator,
         ListFacesPaginator,
         ListProjectPoliciesPaginator,
         ListStreamProcessorsPaginator,
+        ListUsersPaginator,
     )
 
     session = get_session()
     with session.create_client("rekognition") as client:
         client: RekognitionClient
 
         describe_project_versions_paginator: DescribeProjectVersionsPaginator = client.get_paginator("describe_project_versions")
         describe_projects_paginator: DescribeProjectsPaginator = client.get_paginator("describe_projects")
         list_collections_paginator: ListCollectionsPaginator = client.get_paginator("list_collections")
         list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
         list_dataset_labels_paginator: ListDatasetLabelsPaginator = client.get_paginator("list_dataset_labels")
         list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
         list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator("list_project_policies")
         list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator("list_stream_processors")
+        list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeProjectsResponseTypeDef,
     DescribeProjectVersionsResponseTypeDef,
     ListCollectionsResponseTypeDef,
     ListDatasetEntriesResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     ListFacesResponseTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
+    ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeProjectVersionsPaginator",
     "DescribeProjectsPaginator",
     "ListCollectionsPaginator",
     "ListDatasetEntriesPaginator",
     "ListDatasetLabelsPaginator",
     "ListFacesPaginator",
     "ListProjectPoliciesPaginator",
     "ListStreamProcessorsPaginator",
+    "ListUsersPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -87,45 +84,45 @@
     """
 
     def paginate(
         self,
         *,
         ProjectArn: str,
         VersionNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProjectVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjectVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectversionspaginator)
         """
 
 
 class DescribeProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectspaginator)
     """
 
     def paginate(
-        self, *, ProjectNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectNames: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectspaginator)
         """
 
 
 class ListCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listcollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listcollectionspaginator)
         """
 
 
@@ -139,73 +136,93 @@
         self,
         *,
         DatasetArn: str,
         ContainsLabels: Sequence[str] = ...,
         Labeled: bool = ...,
         SourceRefContains: str = ...,
         HasErrors: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetEntriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetEntries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetentriespaginator)
         """
 
 
 class ListDatasetLabelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetLabels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetlabelspaginator)
     """
 
     def paginate(
-        self, *, DatasetArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DatasetArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetLabelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetLabels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetlabelspaginator)
         """
 
 
 class ListFacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListFaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listfacespaginator)
     """
 
     def paginate(
-        self, *, CollectionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        CollectionId: str,
+        UserId: str = ...,
+        FaceIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListFaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listfacespaginator)
         """
 
 
 class ListProjectPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListProjectPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listprojectpoliciespaginator)
     """
 
     def paginate(
-        self, *, ProjectArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListProjectPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listprojectpoliciespaginator)
         """
 
 
 class ListStreamProcessorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListStreamProcessors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#liststreamprocessorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamProcessorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListStreamProcessors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#liststreamprocessorspaginator)
         """
+
+
+class ListUsersPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListUsers)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listuserspaginator)
+    """
+
+    def paginate(
+        self, *, CollectionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListUsersResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListUsers.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listuserspaginator)
+        """
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/paginator.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,62 +14,60 @@
         DescribeProjectsPaginator,
         ListCollectionsPaginator,
         ListDatasetEntriesPaginator,
         ListDatasetLabelsPaginator,
         ListFacesPaginator,
         ListProjectPoliciesPaginator,
         ListStreamProcessorsPaginator,
+        ListUsersPaginator,
     )
 
     session = get_session()
     with session.create_client("rekognition") as client:
         client: RekognitionClient
 
         describe_project_versions_paginator: DescribeProjectVersionsPaginator = client.get_paginator("describe_project_versions")
         describe_projects_paginator: DescribeProjectsPaginator = client.get_paginator("describe_projects")
         list_collections_paginator: ListCollectionsPaginator = client.get_paginator("list_collections")
         list_dataset_entries_paginator: ListDatasetEntriesPaginator = client.get_paginator("list_dataset_entries")
         list_dataset_labels_paginator: ListDatasetLabelsPaginator = client.get_paginator("list_dataset_labels")
         list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
         list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator("list_project_policies")
         list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator("list_stream_processors")
+        list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeProjectsResponseTypeDef,
     DescribeProjectVersionsResponseTypeDef,
     ListCollectionsResponseTypeDef,
     ListDatasetEntriesResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     ListFacesResponseTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
+    ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeProjectVersionsPaginator",
     "DescribeProjectsPaginator",
     "ListCollectionsPaginator",
     "ListDatasetEntriesPaginator",
     "ListDatasetLabelsPaginator",
     "ListFacesPaginator",
     "ListProjectPoliciesPaginator",
     "ListStreamProcessorsPaginator",
+    "ListUsersPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -83,43 +81,43 @@
     """
 
     def paginate(
         self,
         *,
         ProjectArn: str,
         VersionNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProjectVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjectVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectversionspaginator)
         """
 
 class DescribeProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectspaginator)
     """
 
     def paginate(
-        self, *, ProjectNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectNames: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.DescribeProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#describeprojectspaginator)
         """
 
 class ListCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listcollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listcollectionspaginator)
         """
 
 class ListDatasetEntriesPaginator(AioPaginator):
@@ -132,69 +130,88 @@
         self,
         *,
         DatasetArn: str,
         ContainsLabels: Sequence[str] = ...,
         Labeled: bool = ...,
         SourceRefContains: str = ...,
         HasErrors: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetEntriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetEntries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetentriespaginator)
         """
 
 class ListDatasetLabelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetLabels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetlabelspaginator)
     """
 
     def paginate(
-        self, *, DatasetArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DatasetArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetLabelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListDatasetLabels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listdatasetlabelspaginator)
         """
 
 class ListFacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListFaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listfacespaginator)
     """
 
     def paginate(
-        self, *, CollectionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        CollectionId: str,
+        UserId: str = ...,
+        FaceIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListFaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listfacespaginator)
         """
 
 class ListProjectPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListProjectPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listprojectpoliciespaginator)
     """
 
     def paginate(
-        self, *, ProjectArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProjectArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListProjectPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listprojectpoliciespaginator)
         """
 
 class ListStreamProcessorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListStreamProcessors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#liststreamprocessorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamProcessorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListStreamProcessors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#liststreamprocessorspaginator)
         """
+
+class ListUsersPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListUsers)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listuserspaginator)
+    """
+
+    def paginate(
+        self, *, CollectionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListUsersResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition.Paginator.ListUsers.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/paginators/#listuserspaginator)
+        """
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/type_defs.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,322 +18,426 @@
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AttributeType,
     BodyPartType,
     CelebrityRecognitionSortByType,
     ContentClassifierType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetStatusMessageCodeType,
     DatasetStatusType,
     DatasetTypeType,
     DetectLabelsFeatureNameType,
     EmotionNameType,
     FaceAttributesType,
     FaceSearchSortByType,
     GenderTypeType,
     KnownGenderTypeType,
     LabelDetectionAggregateByType,
     LabelDetectionSortByType,
     LandmarkTypeType,
+    LivenessSessionStatusType,
     OrientationCorrectionType,
     PersonTrackingSortByType,
     ProjectStatusType,
     ProjectVersionStatusType,
     ProtectiveEquipmentTypeType,
     QualityFilterType,
     ReasonType,
     SegmentTypeType,
     StreamProcessorParameterToDeleteType,
     StreamProcessorStatusType,
     TechnicalCueTypeType,
     TextTypesType,
+    UnsearchedFaceReasonType,
+    UnsuccessfulFaceAssociationReasonType,
+    UnsuccessfulFaceDeletionReasonType,
+    UnsuccessfulFaceDisassociationReasonType,
+    UserStatusType,
     VideoColorRangeType,
     VideoJobStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AgeRangeTypeDef",
+    "AssociateFacesRequestRequestTypeDef",
+    "AssociatedFaceTypeDef",
+    "UnsuccessfulFaceAssociationTypeDef",
     "AudioMetadataTypeDef",
+    "BoundingBoxTypeDef",
+    "S3ObjectTypeDef",
     "BeardTypeDef",
     "BlackFrameTypeDef",
-    "BoundingBoxTypeDef",
     "KnownGenderTypeDef",
-    "ResponseMetadataTypeDef",
     "EmotionTypeDef",
     "ImageQualityTypeDef",
     "LandmarkTypeDef",
     "PoseTypeDef",
     "SmileTypeDef",
     "ConnectedHomeSettingsForUpdateTypeDef",
     "ConnectedHomeSettingsTypeDef",
     "ModerationLabelTypeDef",
     "OutputConfigTypeDef",
+    "CopyProjectVersionResponseTypeDef",
     "CoversBodyPartTypeDef",
     "CreateCollectionRequestRequestTypeDef",
+    "CreateCollectionResponseTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "LivenessOutputConfigTypeDef",
+    "CreateFaceLivenessSessionResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
+    "CreateProjectVersionResponseTypeDef",
     "StreamProcessorDataSharingPreferenceTypeDef",
     "StreamProcessorNotificationChannelTypeDef",
+    "CreateStreamProcessorResponseTypeDef",
+    "CreateUserRequestRequestTypeDef",
     "DatasetChangesTypeDef",
     "DatasetStatsTypeDef",
     "DatasetLabelStatsTypeDef",
     "DatasetMetadataTypeDef",
     "DeleteCollectionRequestRequestTypeDef",
+    "DeleteCollectionResponseTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteFacesRequestRequestTypeDef",
+    "UnsuccessfulFaceDeletionTypeDef",
     "DeleteProjectPolicyRequestRequestTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResponseTypeDef",
     "DeleteProjectVersionRequestRequestTypeDef",
+    "DeleteProjectVersionResponseTypeDef",
     "DeleteStreamProcessorRequestRequestTypeDef",
+    "DeleteUserRequestRequestTypeDef",
     "DescribeCollectionRequestRequestTypeDef",
+    "DescribeCollectionResponseTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeProjectVersionsRequestRequestTypeDef",
+    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
     "DescribeProjectsRequestRequestTypeDef",
     "DescribeStreamProcessorRequestRequestTypeDef",
     "DetectLabelsImageQualityTypeDef",
     "DominantColorTypeDef",
     "DetectLabelsImagePropertiesSettingsTypeDef",
     "GeneralLabelsSettingsTypeDef",
     "HumanLoopActivationOutputTypeDef",
     "ProtectiveEquipmentSummarizationAttributesTypeDef",
     "ProtectiveEquipmentSummaryTypeDef",
     "DetectionFilterTypeDef",
+    "DisassociateFacesRequestRequestTypeDef",
+    "DisassociatedFaceTypeDef",
+    "UnsuccessfulFaceDisassociationTypeDef",
     "DistributeDatasetTypeDef",
+    "EyeDirectionTypeDef",
     "EyeOpenTypeDef",
     "EyeglassesTypeDef",
+    "FaceOccludedTypeDef",
     "GenderTypeDef",
     "MouthOpenTypeDef",
     "MustacheTypeDef",
     "SunglassesTypeDef",
     "FaceSearchSettingsTypeDef",
     "PointTypeDef",
     "GetCelebrityInfoRequestRequestTypeDef",
     "GetCelebrityRecognitionRequestRequestTypeDef",
     "VideoMetadataTypeDef",
+    "GetContentModerationRequestMetadataTypeDef",
     "GetContentModerationRequestRequestTypeDef",
     "GetFaceDetectionRequestRequestTypeDef",
+    "GetFaceLivenessSessionResultsRequestRequestTypeDef",
     "GetFaceSearchRequestRequestTypeDef",
+    "GetLabelDetectionRequestMetadataTypeDef",
     "GetLabelDetectionRequestRequestTypeDef",
     "GetPersonTrackingRequestRequestTypeDef",
     "GetSegmentDetectionRequestRequestTypeDef",
     "SegmentTypeInfoTypeDef",
     "GetTextDetectionRequestRequestTypeDef",
-    "S3ObjectTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "KinesisDataStreamTypeDef",
     "KinesisVideoStreamStartSelectorTypeDef",
     "KinesisVideoStreamTypeDef",
     "LabelAliasTypeDef",
     "LabelCategoryTypeDef",
     "ParentTypeDef",
+    "ListCollectionsRequestListCollectionsPaginateTypeDef",
     "ListCollectionsRequestRequestTypeDef",
+    "ListCollectionsResponseTypeDef",
+    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     "ListDatasetEntriesRequestRequestTypeDef",
+    "ListDatasetEntriesResponseTypeDef",
+    "ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
     "ListDatasetLabelsRequestRequestTypeDef",
+    "ListFacesRequestListFacesPaginateTypeDef",
     "ListFacesRequestRequestTypeDef",
+    "ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
     "ListProjectPoliciesRequestRequestTypeDef",
     "ProjectPolicyTypeDef",
+    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
     "ListStreamProcessorsRequestRequestTypeDef",
     "StreamProcessorTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
+    "ListUsersRequestRequestTypeDef",
+    "UserTypeDef",
+    "MatchedUserTypeDef",
     "NotificationChannelTypeDef",
+    "PaginatorConfigTypeDef",
     "PutProjectPolicyRequestRequestTypeDef",
+    "PutProjectPolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3DestinationTypeDef",
     "SearchFacesRequestRequestTypeDef",
+    "SearchUsersRequestRequestTypeDef",
+    "SearchedFaceTypeDef",
+    "SearchedUserTypeDef",
     "ShotSegmentTypeDef",
     "TechnicalCueSegmentTypeDef",
-    "StartProjectVersionRequestRequestTypeDef",
-    "StartShotDetectionFilterTypeDef",
-    "StreamProcessingStopSelectorTypeDef",
-    "StopProjectVersionRequestRequestTypeDef",
-    "StopStreamProcessorRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "StartTechnicalCueDetectionFilterTypeDef",
-    "ComparedSourceImageFaceTypeDef",
-    "FaceTypeDef",
-    "CopyProjectVersionResponseTypeDef",
-    "CreateCollectionResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "CreateProjectVersionResponseTypeDef",
-    "CreateStreamProcessorResponseTypeDef",
-    "DeleteCollectionResponseTypeDef",
-    "DeleteFacesResponseTypeDef",
-    "DeleteProjectResponseTypeDef",
-    "DeleteProjectVersionResponseTypeDef",
-    "DescribeCollectionResponseTypeDef",
-    "GetCelebrityInfoResponseTypeDef",
-    "ListCollectionsResponseTypeDef",
-    "ListDatasetEntriesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutProjectPolicyResponseTypeDef",
     "StartCelebrityRecognitionResponseTypeDef",
     "StartContentModerationResponseTypeDef",
     "StartFaceDetectionResponseTypeDef",
     "StartFaceSearchResponseTypeDef",
     "StartLabelDetectionResponseTypeDef",
     "StartPersonTrackingResponseTypeDef",
+    "StartProjectVersionRequestRequestTypeDef",
     "StartProjectVersionResponseTypeDef",
+    "StartShotDetectionFilterTypeDef",
     "StartSegmentDetectionResponseTypeDef",
+    "StreamProcessingStopSelectorTypeDef",
     "StartStreamProcessorResponseTypeDef",
     "StartTextDetectionResponseTypeDef",
+    "StopProjectVersionRequestRequestTypeDef",
     "StopProjectVersionResponseTypeDef",
+    "StopStreamProcessorRequestRequestTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "AssociateFacesResponseTypeDef",
+    "ComparedSourceImageFaceTypeDef",
+    "FaceTypeDef",
+    "AuditImageTypeDef",
+    "GroundTruthManifestTypeDef",
+    "ImageTypeDef",
+    "SummaryTypeDef",
+    "VideoTypeDef",
+    "StartTechnicalCueDetectionFilterTypeDef",
+    "GetCelebrityInfoResponseTypeDef",
     "ComparedFaceTypeDef",
     "StreamProcessorSettingsForUpdateTypeDef",
     "ContentModerationDetectionTypeDef",
     "CopyProjectVersionRequestRequestTypeDef",
     "EquipmentDetectionTypeDef",
+    "CreateFaceLivenessSessionRequestSettingsTypeDef",
     "UpdateDatasetEntriesRequestRequestTypeDef",
     "DatasetDescriptionTypeDef",
     "DatasetLabelDescriptionTypeDef",
     "ProjectDescriptionTypeDef",
-    "DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
-    "ListCollectionsRequestListCollectionsPaginateTypeDef",
-    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    "ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    "ListFacesRequestListFacesPaginateTypeDef",
-    "ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+    "DeleteFacesResponseTypeDef",
     "DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef",
     "DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef",
     "DetectLabelsImageBackgroundTypeDef",
     "DetectLabelsImageForegroundTypeDef",
     "InstanceTypeDef",
     "DetectLabelsSettingsTypeDef",
     "LabelDetectionSettingsTypeDef",
     "DetectModerationLabelsResponseTypeDef",
+    "DisassociateFacesResponseTypeDef",
     "DistributeDatasetEntriesRequestRequestTypeDef",
     "FaceDetailTypeDef",
     "StreamProcessorSettingsTypeDef",
     "GeometryTypeDef",
     "RegionOfInterestTypeDef",
-    "GroundTruthManifestTypeDef",
-    "ImageTypeDef",
-    "SummaryTypeDef",
-    "VideoTypeDef",
     "HumanLoopConfigTypeDef",
     "StreamProcessingStartSelectorTypeDef",
     "StreamProcessorInputTypeDef",
     "ListProjectPoliciesResponseTypeDef",
     "ListStreamProcessorsResponseTypeDef",
+    "ListUsersResponseTypeDef",
+    "UserMatchTypeDef",
     "StreamProcessorOutputTypeDef",
     "SegmentDetectionTypeDef",
-    "StartSegmentDetectionFiltersTypeDef",
     "FaceMatchTypeDef",
     "ListFacesResponseTypeDef",
+    "GetFaceLivenessSessionResultsResponseTypeDef",
+    "AssetTypeDef",
+    "DatasetSourceTypeDef",
+    "CompareFacesRequestRequestTypeDef",
+    "DetectCustomLabelsRequestRequestTypeDef",
+    "DetectFacesRequestRequestTypeDef",
+    "DetectProtectiveEquipmentRequestRequestTypeDef",
+    "IndexFacesRequestRequestTypeDef",
+    "RecognizeCelebritiesRequestRequestTypeDef",
+    "SearchFacesByImageRequestRequestTypeDef",
+    "SearchUsersByImageRequestRequestTypeDef",
+    "EvaluationResultTypeDef",
+    "StartCelebrityRecognitionRequestRequestTypeDef",
+    "StartContentModerationRequestRequestTypeDef",
+    "StartFaceDetectionRequestRequestTypeDef",
+    "StartFaceSearchRequestRequestTypeDef",
+    "StartPersonTrackingRequestRequestTypeDef",
+    "StartSegmentDetectionFiltersTypeDef",
     "CelebrityTypeDef",
     "CompareFacesMatchTypeDef",
     "GetContentModerationResponseTypeDef",
     "ProtectiveEquipmentBodyPartTypeDef",
+    "CreateFaceLivenessSessionRequestRequestTypeDef",
     "DescribeDatasetResponseTypeDef",
     "ListDatasetLabelsResponseTypeDef",
     "DescribeProjectsResponseTypeDef",
     "DetectLabelsImagePropertiesTypeDef",
     "LabelTypeDef",
+    "DetectLabelsRequestRequestTypeDef",
+    "StartLabelDetectionRequestRequestTypeDef",
     "CelebrityDetailTypeDef",
     "DetectFacesResponseTypeDef",
     "FaceDetectionTypeDef",
     "FaceRecordTypeDef",
     "PersonDetailTypeDef",
+    "SearchedFaceDetailsTypeDef",
     "UnindexedFaceTypeDef",
+    "UnsearchedFaceTypeDef",
     "CustomLabelTypeDef",
     "TextDetectionTypeDef",
     "DetectTextFiltersTypeDef",
     "StartTextDetectionFiltersTypeDef",
     "UpdateStreamProcessorRequestRequestTypeDef",
-    "AssetTypeDef",
-    "DatasetSourceTypeDef",
-    "CompareFacesRequestRequestTypeDef",
-    "DetectCustomLabelsRequestRequestTypeDef",
-    "DetectFacesRequestRequestTypeDef",
-    "DetectLabelsRequestRequestTypeDef",
-    "DetectProtectiveEquipmentRequestRequestTypeDef",
-    "IndexFacesRequestRequestTypeDef",
-    "RecognizeCelebritiesRequestRequestTypeDef",
-    "SearchFacesByImageRequestRequestTypeDef",
-    "EvaluationResultTypeDef",
-    "StartCelebrityRecognitionRequestRequestTypeDef",
-    "StartContentModerationRequestRequestTypeDef",
-    "StartFaceDetectionRequestRequestTypeDef",
-    "StartFaceSearchRequestRequestTypeDef",
-    "StartLabelDetectionRequestRequestTypeDef",
-    "StartPersonTrackingRequestRequestTypeDef",
     "DetectModerationLabelsRequestRequestTypeDef",
     "StartStreamProcessorRequestRequestTypeDef",
+    "SearchUsersResponseTypeDef",
     "CreateStreamProcessorRequestRequestTypeDef",
     "DescribeStreamProcessorResponseTypeDef",
     "GetSegmentDetectionResponseTypeDef",
-    "StartSegmentDetectionRequestRequestTypeDef",
     "SearchFacesByImageResponseTypeDef",
     "SearchFacesResponseTypeDef",
+    "TestingDataTypeDef",
+    "TrainingDataTypeDef",
+    "ValidationDataTypeDef",
+    "CreateDatasetRequestRequestTypeDef",
+    "StartSegmentDetectionRequestRequestTypeDef",
     "RecognizeCelebritiesResponseTypeDef",
     "CompareFacesResponseTypeDef",
     "ProtectiveEquipmentPersonTypeDef",
     "DetectLabelsResponseTypeDef",
     "LabelDetectionTypeDef",
     "CelebrityRecognitionTypeDef",
     "GetFaceDetectionResponseTypeDef",
     "PersonDetectionTypeDef",
     "PersonMatchTypeDef",
     "IndexFacesResponseTypeDef",
+    "SearchUsersByImageResponseTypeDef",
     "DetectCustomLabelsResponseTypeDef",
     "DetectTextResponseTypeDef",
     "TextDetectionResultTypeDef",
     "DetectTextRequestRequestTypeDef",
     "StartTextDetectionRequestRequestTypeDef",
-    "TestingDataTypeDef",
-    "TrainingDataTypeDef",
-    "ValidationDataTypeDef",
-    "CreateDatasetRequestRequestTypeDef",
+    "CreateProjectVersionRequestRequestTypeDef",
+    "TestingDataResultTypeDef",
+    "TrainingDataResultTypeDef",
     "DetectProtectiveEquipmentResponseTypeDef",
     "GetLabelDetectionResponseTypeDef",
     "GetCelebrityRecognitionResponseTypeDef",
     "GetPersonTrackingResponseTypeDef",
     "GetFaceSearchResponseTypeDef",
     "GetTextDetectionResponseTypeDef",
-    "CreateProjectVersionRequestRequestTypeDef",
-    "TestingDataResultTypeDef",
-    "TrainingDataResultTypeDef",
     "ProjectVersionDescriptionTypeDef",
     "DescribeProjectVersionsResponseTypeDef",
 )
 
 AgeRangeTypeDef = TypedDict(
     "AgeRangeTypeDef",
     {
         "Low": int,
         "High": int,
     },
     total=False,
 )
 
+_RequiredAssociateFacesRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateFacesRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+        "FaceIds": Sequence[str],
+    },
+)
+_OptionalAssociateFacesRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateFacesRequestRequestTypeDef",
+    {
+        "UserMatchThreshold": float,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+class AssociateFacesRequestRequestTypeDef(
+    _RequiredAssociateFacesRequestRequestTypeDef, _OptionalAssociateFacesRequestRequestTypeDef
+):
+    pass
+
+AssociatedFaceTypeDef = TypedDict(
+    "AssociatedFaceTypeDef",
+    {
+        "FaceId": str,
+    },
+    total=False,
+)
+
+UnsuccessfulFaceAssociationTypeDef = TypedDict(
+    "UnsuccessfulFaceAssociationTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Confidence": float,
+        "Reasons": List[UnsuccessfulFaceAssociationReasonType],
+    },
+    total=False,
+)
+
 AudioMetadataTypeDef = TypedDict(
     "AudioMetadataTypeDef",
     {
         "Codec": str,
         "DurationMillis": int,
         "SampleRate": int,
         "NumberOfChannels": int,
     },
     total=False,
 )
 
+BoundingBoxTypeDef = TypedDict(
+    "BoundingBoxTypeDef",
+    {
+        "Width": float,
+        "Height": float,
+        "Left": float,
+        "Top": float,
+    },
+    total=False,
+)
+
+S3ObjectTypeDef = TypedDict(
+    "S3ObjectTypeDef",
+    {
+        "Bucket": str,
+        "Name": str,
+        "Version": str,
+    },
+    total=False,
+)
+
 BeardTypeDef = TypedDict(
     "BeardTypeDef",
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
@@ -344,44 +448,22 @@
     {
         "MaxPixelThreshold": float,
         "MinCoveragePercentage": float,
     },
     total=False,
 )
 
-BoundingBoxTypeDef = TypedDict(
-    "BoundingBoxTypeDef",
-    {
-        "Width": float,
-        "Height": float,
-        "Left": float,
-        "Top": float,
-    },
-    total=False,
-)
-
 KnownGenderTypeDef = TypedDict(
     "KnownGenderTypeDef",
     {
         "Type": KnownGenderTypeType,
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
 EmotionTypeDef = TypedDict(
     "EmotionTypeDef",
     {
         "Type": EmotionNameType,
         "Confidence": float,
     },
     total=False,
@@ -444,21 +526,19 @@
     "_OptionalConnectedHomeSettingsTypeDef",
     {
         "MinConfidence": float,
     },
     total=False,
 )
 
-
 class ConnectedHomeSettingsTypeDef(
     _RequiredConnectedHomeSettingsTypeDef, _OptionalConnectedHomeSettingsTypeDef
 ):
     pass
 
-
 ModerationLabelTypeDef = TypedDict(
     "ModerationLabelTypeDef",
     {
         "Confidence": float,
         "Name": str,
         "ParentName": str,
     },
@@ -470,14 +550,22 @@
     {
         "S3Bucket": str,
         "S3KeyPrefix": str,
     },
     total=False,
 )
 
+CopyProjectVersionResponseTypeDef = TypedDict(
+    "CopyProjectVersionResponseTypeDef",
+    {
+        "ProjectVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CoversBodyPartTypeDef = TypedDict(
     "CoversBodyPartTypeDef",
     {
         "Confidence": float,
         "Value": bool,
     },
     total=False,
@@ -493,42 +581,129 @@
     "_OptionalCreateCollectionRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateCollectionRequestRequestTypeDef(
     _RequiredCreateCollectionRequestRequestTypeDef, _OptionalCreateCollectionRequestRequestTypeDef
 ):
     pass
 
+CreateCollectionResponseTypeDef = TypedDict(
+    "CreateCollectionResponseTypeDef",
+    {
+        "StatusCode": int,
+        "CollectionArn": str,
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "DatasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredLivenessOutputConfigTypeDef = TypedDict(
+    "_RequiredLivenessOutputConfigTypeDef",
+    {
+        "S3Bucket": str,
+    },
+)
+_OptionalLivenessOutputConfigTypeDef = TypedDict(
+    "_OptionalLivenessOutputConfigTypeDef",
+    {
+        "S3KeyPrefix": str,
+    },
+    total=False,
+)
+
+class LivenessOutputConfigTypeDef(
+    _RequiredLivenessOutputConfigTypeDef, _OptionalLivenessOutputConfigTypeDef
+):
+    pass
+
+CreateFaceLivenessSessionResponseTypeDef = TypedDict(
+    "CreateFaceLivenessSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 CreateProjectRequestRequestTypeDef = TypedDict(
     "CreateProjectRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "ProjectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProjectVersionResponseTypeDef = TypedDict(
+    "CreateProjectVersionResponseTypeDef",
+    {
+        "ProjectVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StreamProcessorDataSharingPreferenceTypeDef = TypedDict(
     "StreamProcessorDataSharingPreferenceTypeDef",
     {
         "OptIn": bool,
     },
 )
 
 StreamProcessorNotificationChannelTypeDef = TypedDict(
     "StreamProcessorNotificationChannelTypeDef",
     {
         "SNSTopicArn": str,
     },
 )
 
+CreateStreamProcessorResponseTypeDef = TypedDict(
+    "CreateStreamProcessorResponseTypeDef",
+    {
+        "StreamProcessorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateUserRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateUserRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+    },
+)
+_OptionalCreateUserRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateUserRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+class CreateUserRequestRequestTypeDef(
+    _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
+):
+    pass
+
 DatasetChangesTypeDef = TypedDict(
     "DatasetChangesTypeDef",
     {
         "GroundTruth": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
@@ -568,14 +743,22 @@
 DeleteCollectionRequestRequestTypeDef = TypedDict(
     "DeleteCollectionRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 
+DeleteCollectionResponseTypeDef = TypedDict(
+    "DeleteCollectionResponseTypeDef",
+    {
+        "StatusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDatasetRequestRequestTypeDef = TypedDict(
     "DeleteDatasetRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 
@@ -583,14 +766,24 @@
     "DeleteFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
         "FaceIds": Sequence[str],
     },
 )
 
+UnsuccessfulFaceDeletionTypeDef = TypedDict(
+    "UnsuccessfulFaceDeletionTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Reasons": List[UnsuccessfulFaceDeletionReasonType],
+    },
+    total=False,
+)
+
 _RequiredDeleteProjectPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectPolicyRequestRequestTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
     },
 )
@@ -598,67 +791,124 @@
     "_OptionalDeleteProjectPolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
-
 class DeleteProjectPolicyRequestRequestTypeDef(
     _RequiredDeleteProjectPolicyRequestRequestTypeDef,
     _OptionalDeleteProjectPolicyRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteProjectRequestRequestTypeDef = TypedDict(
     "DeleteProjectRequestRequestTypeDef",
     {
         "ProjectArn": str,
     },
 )
 
+DeleteProjectResponseTypeDef = TypedDict(
+    "DeleteProjectResponseTypeDef",
+    {
+        "Status": ProjectStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProjectVersionRequestRequestTypeDef = TypedDict(
     "DeleteProjectVersionRequestRequestTypeDef",
     {
         "ProjectVersionArn": str,
     },
 )
 
+DeleteProjectVersionResponseTypeDef = TypedDict(
+    "DeleteProjectVersionResponseTypeDef",
+    {
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteStreamProcessorRequestRequestTypeDef = TypedDict(
     "DeleteStreamProcessorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+_RequiredDeleteUserRequestRequestTypeDef = TypedDict(
+    "_RequiredDeleteUserRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+    },
+)
+_OptionalDeleteUserRequestRequestTypeDef = TypedDict(
+    "_OptionalDeleteUserRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+class DeleteUserRequestRequestTypeDef(
+    _RequiredDeleteUserRequestRequestTypeDef, _OptionalDeleteUserRequestRequestTypeDef
+):
+    pass
+
 DescribeCollectionRequestRequestTypeDef = TypedDict(
     "DescribeCollectionRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 
+DescribeCollectionResponseTypeDef = TypedDict(
+    "DescribeCollectionResponseTypeDef",
+    {
+        "FaceCount": int,
+        "FaceModelVersion": str,
+        "CollectionARN": str,
+        "CreationTimestamp": datetime,
+        "UserCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDatasetRequestRequestTypeDef = TypedDict(
     "DescribeDatasetRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProjectArn": str,
+    },
+)
+_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
+    {
+        "VersionNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef(
+    _RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
+    _OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
+):
+    pass
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -676,21 +926,28 @@
         "VersionNames": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class DescribeProjectVersionsRequestRequestTypeDef(
     _RequiredDescribeProjectVersionsRequestRequestTypeDef,
     _OptionalDescribeProjectVersionsRequestRequestTypeDef,
 ):
     pass
 
+DescribeProjectsRequestDescribeProjectsPaginateTypeDef = TypedDict(
+    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
+    {
+        "ProjectNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeProjectsRequestRequestTypeDef = TypedDict(
     "DescribeProjectsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ProjectNames": Sequence[str],
@@ -782,21 +1039,70 @@
         "MinConfidence": float,
         "MinBoundingBoxHeight": float,
         "MinBoundingBoxWidth": float,
     },
     total=False,
 )
 
+_RequiredDisassociateFacesRequestRequestTypeDef = TypedDict(
+    "_RequiredDisassociateFacesRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+        "FaceIds": Sequence[str],
+    },
+)
+_OptionalDisassociateFacesRequestRequestTypeDef = TypedDict(
+    "_OptionalDisassociateFacesRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+class DisassociateFacesRequestRequestTypeDef(
+    _RequiredDisassociateFacesRequestRequestTypeDef, _OptionalDisassociateFacesRequestRequestTypeDef
+):
+    pass
+
+DisassociatedFaceTypeDef = TypedDict(
+    "DisassociatedFaceTypeDef",
+    {
+        "FaceId": str,
+    },
+    total=False,
+)
+
+UnsuccessfulFaceDisassociationTypeDef = TypedDict(
+    "UnsuccessfulFaceDisassociationTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Reasons": List[UnsuccessfulFaceDisassociationReasonType],
+    },
+    total=False,
+)
+
 DistributeDatasetTypeDef = TypedDict(
     "DistributeDatasetTypeDef",
     {
         "Arn": str,
     },
 )
 
+EyeDirectionTypeDef = TypedDict(
+    "EyeDirectionTypeDef",
+    {
+        "Yaw": float,
+        "Pitch": float,
+        "Confidence": float,
+    },
+    total=False,
+)
+
 EyeOpenTypeDef = TypedDict(
     "EyeOpenTypeDef",
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
@@ -807,14 +1113,23 @@
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
 )
 
+FaceOccludedTypeDef = TypedDict(
+    "FaceOccludedTypeDef",
+    {
+        "Value": bool,
+        "Confidence": float,
+    },
+    total=False,
+)
+
 GenderTypeDef = TypedDict(
     "GenderTypeDef",
     {
         "Value": GenderTypeType,
         "Confidence": float,
     },
     total=False,
@@ -884,60 +1199,66 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": CelebrityRecognitionSortByType,
     },
     total=False,
 )
 
-
 class GetCelebrityRecognitionRequestRequestTypeDef(
     _RequiredGetCelebrityRecognitionRequestRequestTypeDef,
     _OptionalGetCelebrityRecognitionRequestRequestTypeDef,
 ):
     pass
 
-
 VideoMetadataTypeDef = TypedDict(
     "VideoMetadataTypeDef",
     {
         "Codec": str,
         "DurationMillis": int,
         "Format": str,
         "FrameRate": float,
         "FrameHeight": int,
         "FrameWidth": int,
         "ColorRange": VideoColorRangeType,
     },
     total=False,
 )
 
+GetContentModerationRequestMetadataTypeDef = TypedDict(
+    "GetContentModerationRequestMetadataTypeDef",
+    {
+        "SortBy": ContentModerationSortByType,
+        "AggregateBy": ContentModerationAggregateByType,
+    },
+    total=False,
+)
+
 _RequiredGetContentModerationRequestRequestTypeDef = TypedDict(
     "_RequiredGetContentModerationRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetContentModerationRequestRequestTypeDef = TypedDict(
     "_OptionalGetContentModerationRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "SortBy": ContentModerationSortByType,
+        "AggregateBy": ContentModerationAggregateByType,
     },
     total=False,
 )
 
-
 class GetContentModerationRequestRequestTypeDef(
     _RequiredGetContentModerationRequestRequestTypeDef,
     _OptionalGetContentModerationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetFaceDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetFaceDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetFaceDetectionRequestRequestTypeDef = TypedDict(
@@ -945,20 +1266,25 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetFaceDetectionRequestRequestTypeDef(
     _RequiredGetFaceDetectionRequestRequestTypeDef, _OptionalGetFaceDetectionRequestRequestTypeDef
 ):
     pass
 
+GetFaceLivenessSessionResultsRequestRequestTypeDef = TypedDict(
+    "GetFaceLivenessSessionResultsRequestRequestTypeDef",
+    {
+        "SessionId": str,
+    },
+)
 
 _RequiredGetFaceSearchRequestRequestTypeDef = TypedDict(
     "_RequiredGetFaceSearchRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
@@ -968,20 +1294,27 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": FaceSearchSortByType,
     },
     total=False,
 )
 
-
 class GetFaceSearchRequestRequestTypeDef(
     _RequiredGetFaceSearchRequestRequestTypeDef, _OptionalGetFaceSearchRequestRequestTypeDef
 ):
     pass
 
+GetLabelDetectionRequestMetadataTypeDef = TypedDict(
+    "GetLabelDetectionRequestMetadataTypeDef",
+    {
+        "SortBy": LabelDetectionSortByType,
+        "AggregateBy": LabelDetectionAggregateByType,
+    },
+    total=False,
+)
 
 _RequiredGetLabelDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetLabelDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
@@ -992,21 +1325,19 @@
         "NextToken": str,
         "SortBy": LabelDetectionSortByType,
         "AggregateBy": LabelDetectionAggregateByType,
     },
     total=False,
 )
 
-
 class GetLabelDetectionRequestRequestTypeDef(
     _RequiredGetLabelDetectionRequestRequestTypeDef, _OptionalGetLabelDetectionRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetPersonTrackingRequestRequestTypeDef = TypedDict(
     "_RequiredGetPersonTrackingRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetPersonTrackingRequestRequestTypeDef = TypedDict(
@@ -1015,21 +1346,19 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": PersonTrackingSortByType,
     },
     total=False,
 )
 
-
 class GetPersonTrackingRequestRequestTypeDef(
     _RequiredGetPersonTrackingRequestRequestTypeDef, _OptionalGetPersonTrackingRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetSegmentDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetSegmentDetectionRequestRequestTypeDef = TypedDict(
@@ -1037,22 +1366,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetSegmentDetectionRequestRequestTypeDef(
     _RequiredGetSegmentDetectionRequestRequestTypeDef,
     _OptionalGetSegmentDetectionRequestRequestTypeDef,
 ):
     pass
 
-
 SegmentTypeInfoTypeDef = TypedDict(
     "SegmentTypeInfoTypeDef",
     {
         "Type": SegmentTypeType,
         "ModelVersion": str,
     },
     total=False,
@@ -1069,31 +1396,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetTextDetectionRequestRequestTypeDef(
     _RequiredGetTextDetectionRequestRequestTypeDef, _OptionalGetTextDetectionRequestRequestTypeDef
 ):
     pass
 
-
-S3ObjectTypeDef = TypedDict(
-    "S3ObjectTypeDef",
-    {
-        "Bucket": str,
-        "Name": str,
-        "Version": str,
-    },
-    total=False,
-)
-
 HumanLoopDataAttributesTypeDef = TypedDict(
     "HumanLoopDataAttributesTypeDef",
     {
         "ContentClassifiers": Sequence[ContentClassifierType],
     },
     total=False,
 )
@@ -1143,23 +1458,65 @@
     "ParentTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+ListCollectionsRequestListCollectionsPaginateTypeDef = TypedDict(
+    "ListCollectionsRequestListCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCollectionsRequestRequestTypeDef = TypedDict(
     "ListCollectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListCollectionsResponseTypeDef = TypedDict(
+    "ListCollectionsResponseTypeDef",
+    {
+        "CollectionIds": List[str],
+        "NextToken": str,
+        "FaceModelVersions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
+_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "ContainsLabels": Sequence[str],
+        "Labeled": bool,
+        "SourceRefContains": str,
+        "HasErrors": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
+    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDatasetEntriesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetEntriesRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 _OptionalListDatasetEntriesRequestRequestTypeDef = TypedDict(
@@ -1171,21 +1528,48 @@
         "HasErrors": bool,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDatasetEntriesRequestRequestTypeDef(
     _RequiredListDatasetEntriesRequestRequestTypeDef,
     _OptionalListDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
+ListDatasetEntriesResponseTypeDef = TypedDict(
+    "ListDatasetEntriesResponseTypeDef",
+    {
+        "DatasetEntries": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
+_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef(
+    _RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
+    _OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
+):
+    pass
 
 _RequiredListDatasetLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetLabelsRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
@@ -1194,42 +1578,82 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDatasetLabelsRequestRequestTypeDef(
     _RequiredListDatasetLabelsRequestRequestTypeDef, _OptionalListDatasetLabelsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListFacesRequestListFacesPaginateTypeDef = TypedDict(
+    "_RequiredListFacesRequestListFacesPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListFacesRequestListFacesPaginateTypeDef = TypedDict(
+    "_OptionalListFacesRequestListFacesPaginateTypeDef",
+    {
+        "UserId": str,
+        "FaceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFacesRequestListFacesPaginateTypeDef(
+    _RequiredListFacesRequestListFacesPaginateTypeDef,
+    _OptionalListFacesRequestListFacesPaginateTypeDef,
+):
+    pass
 
 _RequiredListFacesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListFacesRequestRequestTypeDef = TypedDict(
     "_OptionalListFacesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "UserId": str,
+        "FaceIds": Sequence[str],
     },
     total=False,
 )
 
-
 class ListFacesRequestRequestTypeDef(
     _RequiredListFacesRequestRequestTypeDef, _OptionalListFacesRequestRequestTypeDef
 ):
     pass
 
+_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
+    {
+        "ProjectArn": str,
+    },
+)
+_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef(
+    _RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
+    _OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
+):
+    pass
 
 _RequiredListProjectPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectPoliciesRequestRequestTypeDef",
     {
         "ProjectArn": str,
     },
 )
@@ -1238,35 +1662,41 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListProjectPoliciesRequestRequestTypeDef(
     _RequiredListProjectPoliciesRequestRequestTypeDef,
     _OptionalListProjectPoliciesRequestRequestTypeDef,
 ):
     pass
 
-
 ProjectPolicyTypeDef = TypedDict(
     "ProjectPolicyTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
         "PolicyRevisionId": str,
         "PolicyDocument": str,
         "CreationTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
+ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef = TypedDict(
+    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamProcessorsRequestRequestTypeDef = TypedDict(
     "ListStreamProcessorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1284,22 +1714,98 @@
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
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
+_RequiredListUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsersRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsersRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class ListUsersRequestRequestTypeDef(
+    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
+):
+    pass
+
+UserTypeDef = TypedDict(
+    "UserTypeDef",
+    {
+        "UserId": str,
+        "UserStatus": UserStatusType,
+    },
+    total=False,
+)
+
+MatchedUserTypeDef = TypedDict(
+    "MatchedUserTypeDef",
+    {
+        "UserId": str,
+        "UserStatus": UserStatusType,
+    },
+    total=False,
+)
+
 NotificationChannelTypeDef = TypedDict(
     "NotificationChannelTypeDef",
     {
         "SNSTopicArn": str,
         "RoleArn": str,
     },
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
 _RequiredPutProjectPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutProjectPolicyRequestRequestTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
         "PolicyDocument": str,
     },
@@ -1308,20 +1814,37 @@
     "_OptionalPutProjectPolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
-
 class PutProjectPolicyRequestRequestTypeDef(
     _RequiredPutProjectPolicyRequestRequestTypeDef, _OptionalPutProjectPolicyRequestRequestTypeDef
 ):
     pass
 
+PutProjectPolicyResponseTypeDef = TypedDict(
+    "PutProjectPolicyResponseTypeDef",
+    {
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 
 S3DestinationTypeDef = TypedDict(
     "S3DestinationTypeDef",
     {
         "Bucket": str,
         "KeyPrefix": str,
     },
@@ -1340,362 +1863,322 @@
     {
         "MaxFaces": int,
         "FaceMatchThreshold": float,
     },
     total=False,
 )
 
-
 class SearchFacesRequestRequestTypeDef(
     _RequiredSearchFacesRequestRequestTypeDef, _OptionalSearchFacesRequestRequestTypeDef
 ):
     pass
 
-
-ShotSegmentTypeDef = TypedDict(
-    "ShotSegmentTypeDef",
-    {
-        "Index": int,
-        "Confidence": float,
-    },
-    total=False,
-)
-
-TechnicalCueSegmentTypeDef = TypedDict(
-    "TechnicalCueSegmentTypeDef",
-    {
-        "Type": TechnicalCueTypeType,
-        "Confidence": float,
-    },
-    total=False,
-)
-
-_RequiredStartProjectVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredStartProjectVersionRequestRequestTypeDef",
+_RequiredSearchUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchUsersRequestRequestTypeDef",
     {
-        "ProjectVersionArn": str,
-        "MinInferenceUnits": int,
+        "CollectionId": str,
     },
 )
-_OptionalStartProjectVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalStartProjectVersionRequestRequestTypeDef",
+_OptionalSearchUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchUsersRequestRequestTypeDef",
     {
-        "MaxInferenceUnits": int,
+        "UserId": str,
+        "FaceId": str,
+        "UserMatchThreshold": float,
+        "MaxUsers": int,
     },
     total=False,
 )
 
-
-class StartProjectVersionRequestRequestTypeDef(
-    _RequiredStartProjectVersionRequestRequestTypeDef,
-    _OptionalStartProjectVersionRequestRequestTypeDef,
+class SearchUsersRequestRequestTypeDef(
+    _RequiredSearchUsersRequestRequestTypeDef, _OptionalSearchUsersRequestRequestTypeDef
 ):
     pass
 
-
-StartShotDetectionFilterTypeDef = TypedDict(
-    "StartShotDetectionFilterTypeDef",
+SearchedFaceTypeDef = TypedDict(
+    "SearchedFaceTypeDef",
     {
-        "MinSegmentConfidence": float,
+        "FaceId": str,
     },
     total=False,
 )
 
-StreamProcessingStopSelectorTypeDef = TypedDict(
-    "StreamProcessingStopSelectorTypeDef",
+SearchedUserTypeDef = TypedDict(
+    "SearchedUserTypeDef",
     {
-        "MaxDurationInSeconds": int,
+        "UserId": str,
     },
     total=False,
 )
 
-StopProjectVersionRequestRequestTypeDef = TypedDict(
-    "StopProjectVersionRequestRequestTypeDef",
-    {
-        "ProjectVersionArn": str,
-    },
-)
-
-StopStreamProcessorRequestRequestTypeDef = TypedDict(
-    "StopStreamProcessorRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-)
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Mapping[str, str],
-    },
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+ShotSegmentTypeDef = TypedDict(
+    "ShotSegmentTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "Index": int,
+        "Confidence": float,
     },
+    total=False,
 )
 
-StartTechnicalCueDetectionFilterTypeDef = TypedDict(
-    "StartTechnicalCueDetectionFilterTypeDef",
+TechnicalCueSegmentTypeDef = TypedDict(
+    "TechnicalCueSegmentTypeDef",
     {
-        "MinSegmentConfidence": float,
-        "BlackFrame": BlackFrameTypeDef,
+        "Type": TechnicalCueTypeType,
+        "Confidence": float,
     },
     total=False,
 )
 
-ComparedSourceImageFaceTypeDef = TypedDict(
-    "ComparedSourceImageFaceTypeDef",
+StartCelebrityRecognitionResponseTypeDef = TypedDict(
+    "StartCelebrityRecognitionResponseTypeDef",
     {
-        "BoundingBox": BoundingBoxTypeDef,
-        "Confidence": float,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-FaceTypeDef = TypedDict(
-    "FaceTypeDef",
+StartContentModerationResponseTypeDef = TypedDict(
+    "StartContentModerationResponseTypeDef",
     {
-        "FaceId": str,
-        "BoundingBox": BoundingBoxTypeDef,
-        "ImageId": str,
-        "ExternalImageId": str,
-        "Confidence": float,
-        "IndexFacesModelVersion": str,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CopyProjectVersionResponseTypeDef = TypedDict(
-    "CopyProjectVersionResponseTypeDef",
+StartFaceDetectionResponseTypeDef = TypedDict(
+    "StartFaceDetectionResponseTypeDef",
     {
-        "ProjectVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateCollectionResponseTypeDef = TypedDict(
-    "CreateCollectionResponseTypeDef",
+StartFaceSearchResponseTypeDef = TypedDict(
+    "StartFaceSearchResponseTypeDef",
     {
-        "StatusCode": int,
-        "CollectionArn": str,
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
+StartLabelDetectionResponseTypeDef = TypedDict(
+    "StartLabelDetectionResponseTypeDef",
     {
-        "DatasetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
+StartPersonTrackingResponseTypeDef = TypedDict(
+    "StartPersonTrackingResponseTypeDef",
     {
-        "ProjectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateProjectVersionResponseTypeDef = TypedDict(
-    "CreateProjectVersionResponseTypeDef",
+_RequiredStartProjectVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredStartProjectVersionRequestRequestTypeDef",
     {
         "ProjectVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MinInferenceUnits": int,
     },
 )
-
-CreateStreamProcessorResponseTypeDef = TypedDict(
-    "CreateStreamProcessorResponseTypeDef",
+_OptionalStartProjectVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalStartProjectVersionRequestRequestTypeDef",
     {
-        "StreamProcessorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxInferenceUnits": int,
     },
+    total=False,
 )
 
-DeleteCollectionResponseTypeDef = TypedDict(
-    "DeleteCollectionResponseTypeDef",
+class StartProjectVersionRequestRequestTypeDef(
+    _RequiredStartProjectVersionRequestRequestTypeDef,
+    _OptionalStartProjectVersionRequestRequestTypeDef,
+):
+    pass
+
+StartProjectVersionResponseTypeDef = TypedDict(
+    "StartProjectVersionResponseTypeDef",
     {
-        "StatusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFacesResponseTypeDef = TypedDict(
-    "DeleteFacesResponseTypeDef",
+StartShotDetectionFilterTypeDef = TypedDict(
+    "StartShotDetectionFilterTypeDef",
     {
-        "DeletedFaces": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MinSegmentConfidence": float,
     },
+    total=False,
 )
 
-DeleteProjectResponseTypeDef = TypedDict(
-    "DeleteProjectResponseTypeDef",
+StartSegmentDetectionResponseTypeDef = TypedDict(
+    "StartSegmentDetectionResponseTypeDef",
     {
-        "Status": ProjectStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteProjectVersionResponseTypeDef = TypedDict(
-    "DeleteProjectVersionResponseTypeDef",
+StreamProcessingStopSelectorTypeDef = TypedDict(
+    "StreamProcessingStopSelectorTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxDurationInSeconds": int,
     },
+    total=False,
 )
 
-DescribeCollectionResponseTypeDef = TypedDict(
-    "DescribeCollectionResponseTypeDef",
+StartStreamProcessorResponseTypeDef = TypedDict(
+    "StartStreamProcessorResponseTypeDef",
     {
-        "FaceCount": int,
-        "FaceModelVersion": str,
-        "CollectionARN": str,
-        "CreationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetCelebrityInfoResponseTypeDef = TypedDict(
-    "GetCelebrityInfoResponseTypeDef",
+StartTextDetectionResponseTypeDef = TypedDict(
+    "StartTextDetectionResponseTypeDef",
     {
-        "Urls": List[str],
-        "Name": str,
-        "KnownGender": KnownGenderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListCollectionsResponseTypeDef = TypedDict(
-    "ListCollectionsResponseTypeDef",
+StopProjectVersionRequestRequestTypeDef = TypedDict(
+    "StopProjectVersionRequestRequestTypeDef",
     {
-        "CollectionIds": List[str],
-        "NextToken": str,
-        "FaceModelVersions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProjectVersionArn": str,
     },
 )
 
-ListDatasetEntriesResponseTypeDef = TypedDict(
-    "ListDatasetEntriesResponseTypeDef",
+StopProjectVersionResponseTypeDef = TypedDict(
+    "StopProjectVersionResponseTypeDef",
     {
-        "DatasetEntries": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+StopStreamProcessorRequestRequestTypeDef = TypedDict(
+    "StopStreamProcessorRequestRequestTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
 
-PutProjectPolicyResponseTypeDef = TypedDict(
-    "PutProjectPolicyResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Mapping[str, str],
     },
 )
 
-StartCelebrityRecognitionResponseTypeDef = TypedDict(
-    "StartCelebrityRecognitionResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-StartContentModerationResponseTypeDef = TypedDict(
-    "StartContentModerationResponseTypeDef",
+AssociateFacesResponseTypeDef = TypedDict(
+    "AssociateFacesResponseTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AssociatedFaces": List[AssociatedFaceTypeDef],
+        "UnsuccessfulFaceAssociations": List[UnsuccessfulFaceAssociationTypeDef],
+        "UserStatus": UserStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartFaceDetectionResponseTypeDef = TypedDict(
-    "StartFaceDetectionResponseTypeDef",
+ComparedSourceImageFaceTypeDef = TypedDict(
+    "ComparedSourceImageFaceTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Confidence": float,
     },
+    total=False,
 )
 
-StartFaceSearchResponseTypeDef = TypedDict(
-    "StartFaceSearchResponseTypeDef",
+FaceTypeDef = TypedDict(
+    "FaceTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FaceId": str,
+        "BoundingBox": BoundingBoxTypeDef,
+        "ImageId": str,
+        "ExternalImageId": str,
+        "Confidence": float,
+        "IndexFacesModelVersion": str,
+        "UserId": str,
     },
+    total=False,
 )
 
-StartLabelDetectionResponseTypeDef = TypedDict(
-    "StartLabelDetectionResponseTypeDef",
+AuditImageTypeDef = TypedDict(
+    "AuditImageTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Bytes": bytes,
+        "S3Object": S3ObjectTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
     },
+    total=False,
 )
 
-StartPersonTrackingResponseTypeDef = TypedDict(
-    "StartPersonTrackingResponseTypeDef",
+GroundTruthManifestTypeDef = TypedDict(
+    "GroundTruthManifestTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartProjectVersionResponseTypeDef = TypedDict(
-    "StartProjectVersionResponseTypeDef",
+ImageTypeDef = TypedDict(
+    "ImageTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Bytes": Union[str, bytes, IO[Any], StreamingBody],
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartSegmentDetectionResponseTypeDef = TypedDict(
-    "StartSegmentDetectionResponseTypeDef",
+SummaryTypeDef = TypedDict(
+    "SummaryTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartStreamProcessorResponseTypeDef = TypedDict(
-    "StartStreamProcessorResponseTypeDef",
+VideoTypeDef = TypedDict(
+    "VideoTypeDef",
     {
-        "SessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartTextDetectionResponseTypeDef = TypedDict(
-    "StartTextDetectionResponseTypeDef",
+StartTechnicalCueDetectionFilterTypeDef = TypedDict(
+    "StartTechnicalCueDetectionFilterTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MinSegmentConfidence": float,
+        "BlackFrame": BlackFrameTypeDef,
     },
+    total=False,
 )
 
-StopProjectVersionResponseTypeDef = TypedDict(
-    "StopProjectVersionResponseTypeDef",
+GetCelebrityInfoResponseTypeDef = TypedDict(
+    "GetCelebrityInfoResponseTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Urls": List[str],
+        "Name": str,
+        "KnownGender": KnownGenderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComparedFaceTypeDef = TypedDict(
     "ComparedFaceTypeDef",
     {
         "BoundingBox": BoundingBoxTypeDef,
@@ -1718,14 +2201,17 @@
 )
 
 ContentModerationDetectionTypeDef = TypedDict(
     "ContentModerationDetectionTypeDef",
     {
         "Timestamp": int,
         "ModerationLabel": ModerationLabelTypeDef,
+        "StartTimestampMillis": int,
+        "EndTimestampMillis": int,
+        "DurationMillis": int,
     },
     total=False,
 )
 
 _RequiredCopyProjectVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCopyProjectVersionRequestRequestTypeDef",
     {
@@ -1741,33 +2227,40 @@
     {
         "Tags": Mapping[str, str],
         "KmsKeyId": str,
     },
     total=False,
 )
 
-
 class CopyProjectVersionRequestRequestTypeDef(
     _RequiredCopyProjectVersionRequestRequestTypeDef,
     _OptionalCopyProjectVersionRequestRequestTypeDef,
 ):
     pass
 
-
 EquipmentDetectionTypeDef = TypedDict(
     "EquipmentDetectionTypeDef",
     {
         "BoundingBox": BoundingBoxTypeDef,
         "Confidence": float,
         "Type": ProtectiveEquipmentTypeType,
         "CoversBodyPart": CoversBodyPartTypeDef,
     },
     total=False,
 )
 
+CreateFaceLivenessSessionRequestSettingsTypeDef = TypedDict(
+    "CreateFaceLivenessSessionRequestSettingsTypeDef",
+    {
+        "OutputConfig": LivenessOutputConfigTypeDef,
+        "AuditImagesLimit": int,
+    },
+    total=False,
+)
+
 UpdateDatasetEntriesRequestRequestTypeDef = TypedDict(
     "UpdateDatasetEntriesRequestRequestTypeDef",
     {
         "DatasetArn": str,
         "Changes": DatasetChangesTypeDef,
     },
 )
@@ -1801,152 +2294,21 @@
         "CreationTimestamp": datetime,
         "Status": ProjectStatusType,
         "Datasets": List[DatasetMetadataTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    {
-        "ProjectArn": str,
-    },
-)
-_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    {
-        "VersionNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef(
-    _RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-    _OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-):
-    pass
-
-
-DescribeProjectsRequestDescribeProjectsPaginateTypeDef = TypedDict(
-    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
-    {
-        "ProjectNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCollectionsRequestListCollectionsPaginateTypeDef = TypedDict(
-    "ListCollectionsRequestListCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "DatasetArn": str,
-    },
-)
-_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "ContainsLabels": Sequence[str],
-        "Labeled": bool,
-        "SourceRefContains": str,
-        "HasErrors": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
-    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    {
-        "DatasetArn": str,
-    },
-)
-_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef(
-    _RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-    _OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFacesRequestListFacesPaginateTypeDef = TypedDict(
-    "_RequiredListFacesRequestListFacesPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListFacesRequestListFacesPaginateTypeDef = TypedDict(
-    "_OptionalListFacesRequestListFacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFacesRequestListFacesPaginateTypeDef(
-    _RequiredListFacesRequestListFacesPaginateTypeDef,
-    _OptionalListFacesRequestListFacesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    {
-        "ProjectArn": str,
-    },
-)
-_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef(
-    _RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-    _OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-):
-    pass
-
-
-ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef = TypedDict(
-    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+DeleteFacesResponseTypeDef = TypedDict(
+    "DeleteFacesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "DeletedFaces": List[str],
+        "UnsuccessfulFaceDeletions": List[UnsuccessfulFaceDeletionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef = TypedDict(
     "_RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef",
     {
         "ProjectArn": str,
     },
@@ -1958,22 +2320,20 @@
         "NextToken": str,
         "MaxResults": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef(
     _RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
     _OptionalDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef",
     {
         "ProjectArn": str,
     },
 )
 _OptionalDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef = TypedDict(
@@ -1983,22 +2343,20 @@
         "NextToken": str,
         "MaxResults": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef(
     _RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
     _OptionalDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
 ):
     pass
 
-
 DetectLabelsImageBackgroundTypeDef = TypedDict(
     "DetectLabelsImageBackgroundTypeDef",
     {
         "Quality": DetectLabelsImageQualityTypeDef,
         "DominantColors": List[DominantColorTypeDef],
     },
     total=False,
@@ -2042,15 +2400,25 @@
 
 DetectModerationLabelsResponseTypeDef = TypedDict(
     "DetectModerationLabelsResponseTypeDef",
     {
         "ModerationLabels": List[ModerationLabelTypeDef],
         "ModerationModelVersion": str,
         "HumanLoopActivationOutput": HumanLoopActivationOutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateFacesResponseTypeDef = TypedDict(
+    "DisassociateFacesResponseTypeDef",
+    {
+        "DisassociatedFaces": List[DisassociatedFaceTypeDef],
+        "UnsuccessfulFaceDisassociations": List[UnsuccessfulFaceDisassociationTypeDef],
+        "UserStatus": UserStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DistributeDatasetEntriesRequestRequestTypeDef = TypedDict(
     "DistributeDatasetEntriesRequestRequestTypeDef",
     {
         "Datasets": Sequence[DistributeDatasetTypeDef],
@@ -2071,14 +2439,16 @@
         "EyesOpen": EyeOpenTypeDef,
         "MouthOpen": MouthOpenTypeDef,
         "Emotions": List[EmotionTypeDef],
         "Landmarks": List[LandmarkTypeDef],
         "Pose": PoseTypeDef,
         "Quality": ImageQualityTypeDef,
         "Confidence": float,
+        "FaceOccluded": FaceOccludedTypeDef,
+        "EyeDirection": EyeDirectionTypeDef,
     },
     total=False,
 )
 
 StreamProcessorSettingsTypeDef = TypedDict(
     "StreamProcessorSettingsTypeDef",
     {
@@ -2102,47 +2472,14 @@
     {
         "BoundingBox": BoundingBoxTypeDef,
         "Polygon": Sequence[PointTypeDef],
     },
     total=False,
 )
 
-GroundTruthManifestTypeDef = TypedDict(
-    "GroundTruthManifestTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-ImageTypeDef = TypedDict(
-    "ImageTypeDef",
-    {
-        "Bytes": Union[str, bytes, IO[Any], StreamingBody],
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-SummaryTypeDef = TypedDict(
-    "SummaryTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-VideoTypeDef = TypedDict(
-    "VideoTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
 _RequiredHumanLoopConfigTypeDef = TypedDict(
     "_RequiredHumanLoopConfigTypeDef",
     {
         "HumanLoopName": str,
         "FlowDefinitionArn": str,
     },
 )
@@ -2150,19 +2487,17 @@
     "_OptionalHumanLoopConfigTypeDef",
     {
         "DataAttributes": HumanLoopDataAttributesTypeDef,
     },
     total=False,
 )
 
-
 class HumanLoopConfigTypeDef(_RequiredHumanLoopConfigTypeDef, _OptionalHumanLoopConfigTypeDef):
     pass
 
-
 StreamProcessingStartSelectorTypeDef = TypedDict(
     "StreamProcessingStartSelectorTypeDef",
     {
         "KVSStreamStartSelector": KinesisVideoStreamStartSelectorTypeDef,
     },
     total=False,
 )
@@ -2176,25 +2511,43 @@
 )
 
 ListProjectPoliciesResponseTypeDef = TypedDict(
     "ListProjectPoliciesResponseTypeDef",
     {
         "ProjectPolicies": List[ProjectPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamProcessorsResponseTypeDef = TypedDict(
     "ListStreamProcessorsResponseTypeDef",
     {
         "NextToken": str,
         "StreamProcessors": List[StreamProcessorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListUsersResponseTypeDef = TypedDict(
+    "ListUsersResponseTypeDef",
+    {
+        "Users": List[UserTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UserMatchTypeDef = TypedDict(
+    "UserMatchTypeDef",
+    {
+        "Similarity": float,
+        "User": MatchedUserTypeDef,
     },
+    total=False,
 )
 
 StreamProcessorOutputTypeDef = TypedDict(
     "StreamProcessorOutputTypeDef",
     {
         "KinesisDataStream": KinesisDataStreamTypeDef,
         "S3Destination": S3DestinationTypeDef,
@@ -2217,23 +2570,14 @@
         "StartFrameNumber": int,
         "EndFrameNumber": int,
         "DurationFrames": int,
     },
     total=False,
 )
 
-StartSegmentDetectionFiltersTypeDef = TypedDict(
-    "StartSegmentDetectionFiltersTypeDef",
-    {
-        "TechnicalCueFilter": StartTechnicalCueDetectionFilterTypeDef,
-        "ShotFilter": StartShotDetectionFilterTypeDef,
-    },
-    total=False,
-)
-
 FaceMatchTypeDef = TypedDict(
     "FaceMatchTypeDef",
     {
         "Similarity": float,
         "Face": FaceTypeDef,
     },
     total=False,
@@ -2241,239 +2585,30 @@
 
 ListFacesResponseTypeDef = TypedDict(
     "ListFacesResponseTypeDef",
     {
         "Faces": List[FaceTypeDef],
         "NextToken": str,
         "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CelebrityTypeDef = TypedDict(
-    "CelebrityTypeDef",
-    {
-        "Urls": List[str],
-        "Name": str,
-        "Id": str,
-        "Face": ComparedFaceTypeDef,
-        "MatchConfidence": float,
-        "KnownGender": KnownGenderTypeDef,
-    },
-    total=False,
-)
-
-CompareFacesMatchTypeDef = TypedDict(
-    "CompareFacesMatchTypeDef",
-    {
-        "Similarity": float,
-        "Face": ComparedFaceTypeDef,
-    },
-    total=False,
-)
-
-GetContentModerationResponseTypeDef = TypedDict(
-    "GetContentModerationResponseTypeDef",
-    {
-        "JobStatus": VideoJobStatusType,
-        "StatusMessage": str,
-        "VideoMetadata": VideoMetadataTypeDef,
-        "ModerationLabels": List[ContentModerationDetectionTypeDef],
-        "NextToken": str,
-        "ModerationModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProtectiveEquipmentBodyPartTypeDef = TypedDict(
-    "ProtectiveEquipmentBodyPartTypeDef",
-    {
-        "Name": BodyPartType,
-        "Confidence": float,
-        "EquipmentDetections": List[EquipmentDetectionTypeDef],
-    },
-    total=False,
-)
-
-DescribeDatasetResponseTypeDef = TypedDict(
-    "DescribeDatasetResponseTypeDef",
-    {
-        "DatasetDescription": DatasetDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatasetLabelsResponseTypeDef = TypedDict(
-    "ListDatasetLabelsResponseTypeDef",
-    {
-        "DatasetLabelDescriptions": List[DatasetLabelDescriptionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProjectsResponseTypeDef = TypedDict(
-    "DescribeProjectsResponseTypeDef",
-    {
-        "ProjectDescriptions": List[ProjectDescriptionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectLabelsImagePropertiesTypeDef = TypedDict(
-    "DetectLabelsImagePropertiesTypeDef",
-    {
-        "Quality": DetectLabelsImageQualityTypeDef,
-        "DominantColors": List[DominantColorTypeDef],
-        "Foreground": DetectLabelsImageForegroundTypeDef,
-        "Background": DetectLabelsImageBackgroundTypeDef,
-    },
-    total=False,
-)
-
-LabelTypeDef = TypedDict(
-    "LabelTypeDef",
-    {
-        "Name": str,
-        "Confidence": float,
-        "Instances": List[InstanceTypeDef],
-        "Parents": List[ParentTypeDef],
-        "Aliases": List[LabelAliasTypeDef],
-        "Categories": List[LabelCategoryTypeDef],
-    },
-    total=False,
-)
-
-CelebrityDetailTypeDef = TypedDict(
-    "CelebrityDetailTypeDef",
-    {
-        "Urls": List[str],
-        "Name": str,
-        "Id": str,
-        "Confidence": float,
-        "BoundingBox": BoundingBoxTypeDef,
-        "Face": FaceDetailTypeDef,
-        "KnownGender": KnownGenderTypeDef,
-    },
-    total=False,
-)
-
-DetectFacesResponseTypeDef = TypedDict(
-    "DetectFacesResponseTypeDef",
-    {
-        "FaceDetails": List[FaceDetailTypeDef],
-        "OrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-FaceDetectionTypeDef = TypedDict(
-    "FaceDetectionTypeDef",
-    {
-        "Timestamp": int,
-        "Face": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-FaceRecordTypeDef = TypedDict(
-    "FaceRecordTypeDef",
-    {
-        "Face": FaceTypeDef,
-        "FaceDetail": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-PersonDetailTypeDef = TypedDict(
-    "PersonDetailTypeDef",
-    {
-        "Index": int,
-        "BoundingBox": BoundingBoxTypeDef,
-        "Face": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-UnindexedFaceTypeDef = TypedDict(
-    "UnindexedFaceTypeDef",
-    {
-        "Reasons": List[ReasonType],
-        "FaceDetail": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-CustomLabelTypeDef = TypedDict(
-    "CustomLabelTypeDef",
-    {
-        "Name": str,
-        "Confidence": float,
-        "Geometry": GeometryTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-TextDetectionTypeDef = TypedDict(
-    "TextDetectionTypeDef",
+GetFaceLivenessSessionResultsResponseTypeDef = TypedDict(
+    "GetFaceLivenessSessionResultsResponseTypeDef",
     {
-        "DetectedText": str,
-        "Type": TextTypesType,
-        "Id": int,
-        "ParentId": int,
+        "SessionId": str,
+        "Status": LivenessSessionStatusType,
         "Confidence": float,
-        "Geometry": GeometryTypeDef,
-    },
-    total=False,
-)
-
-DetectTextFiltersTypeDef = TypedDict(
-    "DetectTextFiltersTypeDef",
-    {
-        "WordFilter": DetectionFilterTypeDef,
-        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
+        "ReferenceImage": AuditImageTypeDef,
+        "AuditImages": List[AuditImageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-StartTextDetectionFiltersTypeDef = TypedDict(
-    "StartTextDetectionFiltersTypeDef",
-    {
-        "WordFilter": DetectionFilterTypeDef,
-        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
-    },
-    total=False,
-)
-
-_RequiredUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateStreamProcessorRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateStreamProcessorRequestRequestTypeDef",
-    {
-        "SettingsForUpdate": StreamProcessorSettingsForUpdateTypeDef,
-        "RegionsOfInterestForUpdate": Sequence[RegionOfInterestTypeDef],
-        "DataSharingPreferenceForUpdate": StreamProcessorDataSharingPreferenceTypeDef,
-        "ParametersToDelete": Sequence[StreamProcessorParameterToDeleteType],
-    },
-    total=False,
-)
-
-
-class UpdateStreamProcessorRequestRequestTypeDef(
-    _RequiredUpdateStreamProcessorRequestRequestTypeDef,
-    _OptionalUpdateStreamProcessorRequestRequestTypeDef,
-):
-    pass
-
-
 AssetTypeDef = TypedDict(
     "AssetTypeDef",
     {
         "GroundTruthManifest": GroundTruthManifestTypeDef,
     },
     total=False,
 )
@@ -2499,21 +2634,19 @@
     {
         "SimilarityThreshold": float,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
-
 class CompareFacesRequestRequestTypeDef(
     _RequiredCompareFacesRequestRequestTypeDef, _OptionalCompareFacesRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredDetectCustomLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredDetectCustomLabelsRequestRequestTypeDef",
     {
         "ProjectVersionArn": str,
         "Image": ImageTypeDef,
     },
 )
@@ -2522,89 +2655,59 @@
     {
         "MaxResults": int,
         "MinConfidence": float,
     },
     total=False,
 )
 
-
 class DetectCustomLabelsRequestRequestTypeDef(
     _RequiredDetectCustomLabelsRequestRequestTypeDef,
     _OptionalDetectCustomLabelsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDetectFacesRequestRequestTypeDef = TypedDict(
     "_RequiredDetectFacesRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 _OptionalDetectFacesRequestRequestTypeDef = TypedDict(
     "_OptionalDetectFacesRequestRequestTypeDef",
     {
         "Attributes": Sequence[AttributeType],
     },
     total=False,
 )
 
-
 class DetectFacesRequestRequestTypeDef(
     _RequiredDetectFacesRequestRequestTypeDef, _OptionalDetectFacesRequestRequestTypeDef
 ):
     pass
 
-
-_RequiredDetectLabelsRequestRequestTypeDef = TypedDict(
-    "_RequiredDetectLabelsRequestRequestTypeDef",
-    {
-        "Image": ImageTypeDef,
-    },
-)
-_OptionalDetectLabelsRequestRequestTypeDef = TypedDict(
-    "_OptionalDetectLabelsRequestRequestTypeDef",
-    {
-        "MaxLabels": int,
-        "MinConfidence": float,
-        "Features": Sequence[DetectLabelsFeatureNameType],
-        "Settings": DetectLabelsSettingsTypeDef,
-    },
-    total=False,
-)
-
-
-class DetectLabelsRequestRequestTypeDef(
-    _RequiredDetectLabelsRequestRequestTypeDef, _OptionalDetectLabelsRequestRequestTypeDef
-):
-    pass
-
-
 _RequiredDetectProtectiveEquipmentRequestRequestTypeDef = TypedDict(
     "_RequiredDetectProtectiveEquipmentRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 _OptionalDetectProtectiveEquipmentRequestRequestTypeDef = TypedDict(
     "_OptionalDetectProtectiveEquipmentRequestRequestTypeDef",
     {
         "SummarizationAttributes": ProtectiveEquipmentSummarizationAttributesTypeDef,
     },
     total=False,
 )
 
-
 class DetectProtectiveEquipmentRequestRequestTypeDef(
     _RequiredDetectProtectiveEquipmentRequestRequestTypeDef,
     _OptionalDetectProtectiveEquipmentRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredIndexFacesRequestRequestTypeDef = TypedDict(
     "_RequiredIndexFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
         "Image": ImageTypeDef,
     },
 )
@@ -2615,21 +2718,19 @@
         "DetectionAttributes": Sequence[AttributeType],
         "MaxFaces": int,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
-
 class IndexFacesRequestRequestTypeDef(
     _RequiredIndexFacesRequestRequestTypeDef, _OptionalIndexFacesRequestRequestTypeDef
 ):
     pass
 
-
 RecognizeCelebritiesRequestRequestTypeDef = TypedDict(
     "RecognizeCelebritiesRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 
@@ -2646,21 +2747,42 @@
         "MaxFaces": int,
         "FaceMatchThreshold": float,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
-
 class SearchFacesByImageRequestRequestTypeDef(
     _RequiredSearchFacesByImageRequestRequestTypeDef,
     _OptionalSearchFacesByImageRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSearchUsersByImageRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchUsersByImageRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "Image": ImageTypeDef,
+    },
+)
+_OptionalSearchUsersByImageRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchUsersByImageRequestRequestTypeDef",
+    {
+        "UserMatchThreshold": float,
+        "MaxUsers": int,
+        "QualityFilter": QualityFilterType,
+    },
+    total=False,
+)
+
+class SearchUsersByImageRequestRequestTypeDef(
+    _RequiredSearchUsersByImageRequestRequestTypeDef,
+    _OptionalSearchUsersByImageRequestRequestTypeDef,
+):
+    pass
 
 EvaluationResultTypeDef = TypedDict(
     "EvaluationResultTypeDef",
     {
         "F1Score": float,
         "Summary": SummaryTypeDef,
     },
@@ -2679,22 +2801,20 @@
         "ClientRequestToken": str,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
-
 class StartCelebrityRecognitionRequestRequestTypeDef(
     _RequiredStartCelebrityRecognitionRequestRequestTypeDef,
     _OptionalStartCelebrityRecognitionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartContentModerationRequestRequestTypeDef = TypedDict(
     "_RequiredStartContentModerationRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartContentModerationRequestRequestTypeDef = TypedDict(
@@ -2704,22 +2824,20 @@
         "ClientRequestToken": str,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
-
 class StartContentModerationRequestRequestTypeDef(
     _RequiredStartContentModerationRequestRequestTypeDef,
     _OptionalStartContentModerationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartFaceDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartFaceDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartFaceDetectionRequestRequestTypeDef = TypedDict(
@@ -2729,22 +2847,20 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "FaceAttributes": FaceAttributesType,
         "JobTag": str,
     },
     total=False,
 )
 
-
 class StartFaceDetectionRequestRequestTypeDef(
     _RequiredStartFaceDetectionRequestRequestTypeDef,
     _OptionalStartFaceDetectionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartFaceSearchRequestRequestTypeDef = TypedDict(
     "_RequiredStartFaceSearchRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
         "CollectionId": str,
     },
 )
@@ -2755,20 +2871,180 @@
         "FaceMatchThreshold": float,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
-
 class StartFaceSearchRequestRequestTypeDef(
     _RequiredStartFaceSearchRequestRequestTypeDef, _OptionalStartFaceSearchRequestRequestTypeDef
 ):
     pass
 
+_RequiredStartPersonTrackingRequestRequestTypeDef = TypedDict(
+    "_RequiredStartPersonTrackingRequestRequestTypeDef",
+    {
+        "Video": VideoTypeDef,
+    },
+)
+_OptionalStartPersonTrackingRequestRequestTypeDef = TypedDict(
+    "_OptionalStartPersonTrackingRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "NotificationChannel": NotificationChannelTypeDef,
+        "JobTag": str,
+    },
+    total=False,
+)
+
+class StartPersonTrackingRequestRequestTypeDef(
+    _RequiredStartPersonTrackingRequestRequestTypeDef,
+    _OptionalStartPersonTrackingRequestRequestTypeDef,
+):
+    pass
+
+StartSegmentDetectionFiltersTypeDef = TypedDict(
+    "StartSegmentDetectionFiltersTypeDef",
+    {
+        "TechnicalCueFilter": StartTechnicalCueDetectionFilterTypeDef,
+        "ShotFilter": StartShotDetectionFilterTypeDef,
+    },
+    total=False,
+)
+
+CelebrityTypeDef = TypedDict(
+    "CelebrityTypeDef",
+    {
+        "Urls": List[str],
+        "Name": str,
+        "Id": str,
+        "Face": ComparedFaceTypeDef,
+        "MatchConfidence": float,
+        "KnownGender": KnownGenderTypeDef,
+    },
+    total=False,
+)
+
+CompareFacesMatchTypeDef = TypedDict(
+    "CompareFacesMatchTypeDef",
+    {
+        "Similarity": float,
+        "Face": ComparedFaceTypeDef,
+    },
+    total=False,
+)
+
+GetContentModerationResponseTypeDef = TypedDict(
+    "GetContentModerationResponseTypeDef",
+    {
+        "JobStatus": VideoJobStatusType,
+        "StatusMessage": str,
+        "VideoMetadata": VideoMetadataTypeDef,
+        "ModerationLabels": List[ContentModerationDetectionTypeDef],
+        "NextToken": str,
+        "ModerationModelVersion": str,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "GetRequestMetadata": GetContentModerationRequestMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ProtectiveEquipmentBodyPartTypeDef = TypedDict(
+    "ProtectiveEquipmentBodyPartTypeDef",
+    {
+        "Name": BodyPartType,
+        "Confidence": float,
+        "EquipmentDetections": List[EquipmentDetectionTypeDef],
+    },
+    total=False,
+)
+
+CreateFaceLivenessSessionRequestRequestTypeDef = TypedDict(
+    "CreateFaceLivenessSessionRequestRequestTypeDef",
+    {
+        "KmsKeyId": str,
+        "Settings": CreateFaceLivenessSessionRequestSettingsTypeDef,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+DescribeDatasetResponseTypeDef = TypedDict(
+    "DescribeDatasetResponseTypeDef",
+    {
+        "DatasetDescription": DatasetDescriptionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDatasetLabelsResponseTypeDef = TypedDict(
+    "ListDatasetLabelsResponseTypeDef",
+    {
+        "DatasetLabelDescriptions": List[DatasetLabelDescriptionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProjectsResponseTypeDef = TypedDict(
+    "DescribeProjectsResponseTypeDef",
+    {
+        "ProjectDescriptions": List[ProjectDescriptionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DetectLabelsImagePropertiesTypeDef = TypedDict(
+    "DetectLabelsImagePropertiesTypeDef",
+    {
+        "Quality": DetectLabelsImageQualityTypeDef,
+        "DominantColors": List[DominantColorTypeDef],
+        "Foreground": DetectLabelsImageForegroundTypeDef,
+        "Background": DetectLabelsImageBackgroundTypeDef,
+    },
+    total=False,
+)
+
+LabelTypeDef = TypedDict(
+    "LabelTypeDef",
+    {
+        "Name": str,
+        "Confidence": float,
+        "Instances": List[InstanceTypeDef],
+        "Parents": List[ParentTypeDef],
+        "Aliases": List[LabelAliasTypeDef],
+        "Categories": List[LabelCategoryTypeDef],
+    },
+    total=False,
+)
+
+_RequiredDetectLabelsRequestRequestTypeDef = TypedDict(
+    "_RequiredDetectLabelsRequestRequestTypeDef",
+    {
+        "Image": ImageTypeDef,
+    },
+)
+_OptionalDetectLabelsRequestRequestTypeDef = TypedDict(
+    "_OptionalDetectLabelsRequestRequestTypeDef",
+    {
+        "MaxLabels": int,
+        "MinConfidence": float,
+        "Features": Sequence[DetectLabelsFeatureNameType],
+        "Settings": DetectLabelsSettingsTypeDef,
+    },
+    total=False,
+)
+
+class DetectLabelsRequestRequestTypeDef(
+    _RequiredDetectLabelsRequestRequestTypeDef, _OptionalDetectLabelsRequestRequestTypeDef
+):
+    pass
 
 _RequiredStartLabelDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartLabelDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
@@ -2781,46 +3057,161 @@
         "JobTag": str,
         "Features": Sequence[Literal["GENERAL_LABELS"]],
         "Settings": LabelDetectionSettingsTypeDef,
     },
     total=False,
 )
 
-
 class StartLabelDetectionRequestRequestTypeDef(
     _RequiredStartLabelDetectionRequestRequestTypeDef,
     _OptionalStartLabelDetectionRequestRequestTypeDef,
 ):
     pass
 
+CelebrityDetailTypeDef = TypedDict(
+    "CelebrityDetailTypeDef",
+    {
+        "Urls": List[str],
+        "Name": str,
+        "Id": str,
+        "Confidence": float,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Face": FaceDetailTypeDef,
+        "KnownGender": KnownGenderTypeDef,
+    },
+    total=False,
+)
 
-_RequiredStartPersonTrackingRequestRequestTypeDef = TypedDict(
-    "_RequiredStartPersonTrackingRequestRequestTypeDef",
+DetectFacesResponseTypeDef = TypedDict(
+    "DetectFacesResponseTypeDef",
     {
-        "Video": VideoTypeDef,
+        "FaceDetails": List[FaceDetailTypeDef],
+        "OrientationCorrection": OrientationCorrectionType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalStartPersonTrackingRequestRequestTypeDef = TypedDict(
-    "_OptionalStartPersonTrackingRequestRequestTypeDef",
+
+FaceDetectionTypeDef = TypedDict(
+    "FaceDetectionTypeDef",
     {
-        "ClientRequestToken": str,
-        "NotificationChannel": NotificationChannelTypeDef,
-        "JobTag": str,
+        "Timestamp": int,
+        "Face": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+FaceRecordTypeDef = TypedDict(
+    "FaceRecordTypeDef",
+    {
+        "Face": FaceTypeDef,
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+PersonDetailTypeDef = TypedDict(
+    "PersonDetailTypeDef",
+    {
+        "Index": int,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Face": FaceDetailTypeDef,
     },
     total=False,
 )
 
+SearchedFaceDetailsTypeDef = TypedDict(
+    "SearchedFaceDetailsTypeDef",
+    {
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
 
-class StartPersonTrackingRequestRequestTypeDef(
-    _RequiredStartPersonTrackingRequestRequestTypeDef,
-    _OptionalStartPersonTrackingRequestRequestTypeDef,
+UnindexedFaceTypeDef = TypedDict(
+    "UnindexedFaceTypeDef",
+    {
+        "Reasons": List[ReasonType],
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+UnsearchedFaceTypeDef = TypedDict(
+    "UnsearchedFaceTypeDef",
+    {
+        "FaceDetails": FaceDetailTypeDef,
+        "Reasons": List[UnsearchedFaceReasonType],
+    },
+    total=False,
+)
+
+CustomLabelTypeDef = TypedDict(
+    "CustomLabelTypeDef",
+    {
+        "Name": str,
+        "Confidence": float,
+        "Geometry": GeometryTypeDef,
+    },
+    total=False,
+)
+
+TextDetectionTypeDef = TypedDict(
+    "TextDetectionTypeDef",
+    {
+        "DetectedText": str,
+        "Type": TextTypesType,
+        "Id": int,
+        "ParentId": int,
+        "Confidence": float,
+        "Geometry": GeometryTypeDef,
+    },
+    total=False,
+)
+
+DetectTextFiltersTypeDef = TypedDict(
+    "DetectTextFiltersTypeDef",
+    {
+        "WordFilter": DetectionFilterTypeDef,
+        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
+    },
+    total=False,
+)
+
+StartTextDetectionFiltersTypeDef = TypedDict(
+    "StartTextDetectionFiltersTypeDef",
+    {
+        "WordFilter": DetectionFilterTypeDef,
+        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
+    },
+    total=False,
+)
+
+_RequiredUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateStreamProcessorRequestRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateStreamProcessorRequestRequestTypeDef",
+    {
+        "SettingsForUpdate": StreamProcessorSettingsForUpdateTypeDef,
+        "RegionsOfInterestForUpdate": Sequence[RegionOfInterestTypeDef],
+        "DataSharingPreferenceForUpdate": StreamProcessorDataSharingPreferenceTypeDef,
+        "ParametersToDelete": Sequence[StreamProcessorParameterToDeleteType],
+    },
+    total=False,
+)
+
+class UpdateStreamProcessorRequestRequestTypeDef(
+    _RequiredUpdateStreamProcessorRequestRequestTypeDef,
+    _OptionalUpdateStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDetectModerationLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredDetectModerationLabelsRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 _OptionalDetectModerationLabelsRequestRequestTypeDef = TypedDict(
@@ -2828,22 +3219,20 @@
     {
         "MinConfidence": float,
         "HumanLoopConfig": HumanLoopConfigTypeDef,
     },
     total=False,
 )
 
-
 class DetectModerationLabelsRequestRequestTypeDef(
     _RequiredDetectModerationLabelsRequestRequestTypeDef,
     _OptionalDetectModerationLabelsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartStreamProcessorRequestRequestTypeDef = TypedDict(
     "_RequiredStartStreamProcessorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalStartStreamProcessorRequestRequestTypeDef = TypedDict(
@@ -2851,21 +3240,30 @@
     {
         "StartSelector": StreamProcessingStartSelectorTypeDef,
         "StopSelector": StreamProcessingStopSelectorTypeDef,
     },
     total=False,
 )
 
-
 class StartStreamProcessorRequestRequestTypeDef(
     _RequiredStartStreamProcessorRequestRequestTypeDef,
     _OptionalStartStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
+SearchUsersResponseTypeDef = TypedDict(
+    "SearchUsersResponseTypeDef",
+    {
+        "UserMatches": List[UserMatchTypeDef],
+        "FaceModelVersion": str,
+        "SearchedFace": SearchedFaceTypeDef,
+        "SearchedUser": SearchedUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateStreamProcessorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStreamProcessorRequestRequestTypeDef",
     {
         "Input": StreamProcessorInputTypeDef,
         "Output": StreamProcessorOutputTypeDef,
         "Name": str,
@@ -2881,22 +3279,20 @@
         "KmsKeyId": str,
         "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
         "DataSharingPreference": StreamProcessorDataSharingPreferenceTypeDef,
     },
     total=False,
 )
 
-
 class CreateStreamProcessorRequestRequestTypeDef(
     _RequiredCreateStreamProcessorRequestRequestTypeDef,
     _OptionalCreateStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeStreamProcessorResponseTypeDef = TypedDict(
     "DescribeStreamProcessorResponseTypeDef",
     {
         "Name": str,
         "StreamProcessorArn": str,
         "Status": StreamProcessorStatusType,
         "StatusMessage": str,
@@ -2906,32 +3302,101 @@
         "Output": StreamProcessorOutputTypeDef,
         "RoleArn": str,
         "Settings": StreamProcessorSettingsTypeDef,
         "NotificationChannel": StreamProcessorNotificationChannelTypeDef,
         "KmsKeyId": str,
         "RegionsOfInterest": List[RegionOfInterestTypeDef],
         "DataSharingPreference": StreamProcessorDataSharingPreferenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentDetectionResponseTypeDef = TypedDict(
     "GetSegmentDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": List[VideoMetadataTypeDef],
         "AudioMetadata": List[AudioMetadataTypeDef],
         "NextToken": str,
         "Segments": List[SegmentDetectionTypeDef],
         "SelectedSegmentTypes": List[SegmentTypeInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchFacesByImageResponseTypeDef = TypedDict(
+    "SearchFacesByImageResponseTypeDef",
+    {
+        "SearchedFaceBoundingBox": BoundingBoxTypeDef,
+        "SearchedFaceConfidence": float,
+        "FaceMatches": List[FaceMatchTypeDef],
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchFacesResponseTypeDef = TypedDict(
+    "SearchFacesResponseTypeDef",
+    {
+        "SearchedFaceId": str,
+        "FaceMatches": List[FaceMatchTypeDef],
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestingDataTypeDef = TypedDict(
+    "TestingDataTypeDef",
+    {
+        "Assets": Sequence[AssetTypeDef],
+        "AutoCreate": bool,
+    },
+    total=False,
+)
+
+TrainingDataTypeDef = TypedDict(
+    "TrainingDataTypeDef",
+    {
+        "Assets": Sequence[AssetTypeDef],
+    },
+    total=False,
+)
+
+ValidationDataTypeDef = TypedDict(
+    "ValidationDataTypeDef",
+    {
+        "Assets": List[AssetTypeDef],
+    },
+    total=False,
+)
+
+_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetType": DatasetTypeType,
+        "ProjectArn": str,
+    },
+)
+_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetSource": DatasetSourceTypeDef,
     },
+    total=False,
 )
 
+class CreateDatasetRequestRequestTypeDef(
+    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
+):
+    pass
+
 _RequiredStartSegmentDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartSegmentDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
         "SegmentTypes": Sequence[SegmentTypeType],
     },
 )
@@ -2942,62 +3407,39 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
         "Filters": StartSegmentDetectionFiltersTypeDef,
     },
     total=False,
 )
 
-
 class StartSegmentDetectionRequestRequestTypeDef(
     _RequiredStartSegmentDetectionRequestRequestTypeDef,
     _OptionalStartSegmentDetectionRequestRequestTypeDef,
 ):
     pass
 
-
-SearchFacesByImageResponseTypeDef = TypedDict(
-    "SearchFacesByImageResponseTypeDef",
-    {
-        "SearchedFaceBoundingBox": BoundingBoxTypeDef,
-        "SearchedFaceConfidence": float,
-        "FaceMatches": List[FaceMatchTypeDef],
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFacesResponseTypeDef = TypedDict(
-    "SearchFacesResponseTypeDef",
-    {
-        "SearchedFaceId": str,
-        "FaceMatches": List[FaceMatchTypeDef],
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 RecognizeCelebritiesResponseTypeDef = TypedDict(
     "RecognizeCelebritiesResponseTypeDef",
     {
         "CelebrityFaces": List[CelebrityTypeDef],
         "UnrecognizedFaces": List[ComparedFaceTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompareFacesResponseTypeDef = TypedDict(
     "CompareFacesResponseTypeDef",
     {
         "SourceImageFace": ComparedSourceImageFaceTypeDef,
         "FaceMatches": List[CompareFacesMatchTypeDef],
         "UnmatchedFaces": List[ComparedFaceTypeDef],
         "SourceImageOrientationCorrection": OrientationCorrectionType,
         "TargetImageOrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProtectiveEquipmentPersonTypeDef = TypedDict(
     "ProtectiveEquipmentPersonTypeDef",
     {
         "BodyParts": List[ProtectiveEquipmentBodyPartTypeDef],
@@ -3011,15 +3453,15 @@
 DetectLabelsResponseTypeDef = TypedDict(
     "DetectLabelsResponseTypeDef",
     {
         "Labels": List[LabelTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
         "LabelModelVersion": str,
         "ImageProperties": DetectLabelsImagePropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelDetectionTypeDef = TypedDict(
     "LabelDetectionTypeDef",
     {
         "Timestamp": int,
@@ -3044,15 +3486,18 @@
     "GetFaceDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Faces": List[FaceDetectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PersonDetectionTypeDef = TypedDict(
     "PersonDetectionTypeDef",
     {
         "Timestamp": int,
@@ -3074,32 +3519,43 @@
 IndexFacesResponseTypeDef = TypedDict(
     "IndexFacesResponseTypeDef",
     {
         "FaceRecords": List[FaceRecordTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
         "FaceModelVersion": str,
         "UnindexedFaces": List[UnindexedFaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchUsersByImageResponseTypeDef = TypedDict(
+    "SearchUsersByImageResponseTypeDef",
+    {
+        "UserMatches": List[UserMatchTypeDef],
+        "FaceModelVersion": str,
+        "SearchedFace": SearchedFaceDetailsTypeDef,
+        "UnsearchedFaces": List[UnsearchedFaceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectCustomLabelsResponseTypeDef = TypedDict(
     "DetectCustomLabelsResponseTypeDef",
     {
         "CustomLabels": List[CustomLabelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectTextResponseTypeDef = TypedDict(
     "DetectTextResponseTypeDef",
     {
         "TextDetections": List[TextDetectionTypeDef],
         "TextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TextDetectionResultTypeDef = TypedDict(
     "TextDetectionResultTypeDef",
     {
         "Timestamp": int,
@@ -3118,21 +3574,19 @@
     "_OptionalDetectTextRequestRequestTypeDef",
     {
         "Filters": DetectTextFiltersTypeDef,
     },
     total=False,
 )
 
-
 class DetectTextRequestRequestTypeDef(
     _RequiredDetectTextRequestRequestTypeDef, _OptionalDetectTextRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredStartTextDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartTextDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartTextDetectionRequestRequestTypeDef = TypedDict(
@@ -3142,186 +3596,151 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
         "Filters": StartTextDetectionFiltersTypeDef,
     },
     total=False,
 )
 
-
 class StartTextDetectionRequestRequestTypeDef(
     _RequiredStartTextDetectionRequestRequestTypeDef,
     _OptionalStartTextDetectionRequestRequestTypeDef,
 ):
     pass
 
-
-TestingDataTypeDef = TypedDict(
-    "TestingDataTypeDef",
+_RequiredCreateProjectVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateProjectVersionRequestRequestTypeDef",
     {
-        "Assets": Sequence[AssetTypeDef],
-        "AutoCreate": bool,
+        "ProjectArn": str,
+        "VersionName": str,
+        "OutputConfig": OutputConfigTypeDef,
     },
-    total=False,
 )
-
-TrainingDataTypeDef = TypedDict(
-    "TrainingDataTypeDef",
+_OptionalCreateProjectVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateProjectVersionRequestRequestTypeDef",
     {
-        "Assets": Sequence[AssetTypeDef],
+        "TrainingData": TrainingDataTypeDef,
+        "TestingData": TestingDataTypeDef,
+        "Tags": Mapping[str, str],
+        "KmsKeyId": str,
     },
     total=False,
 )
 
-ValidationDataTypeDef = TypedDict(
-    "ValidationDataTypeDef",
+class CreateProjectVersionRequestRequestTypeDef(
+    _RequiredCreateProjectVersionRequestRequestTypeDef,
+    _OptionalCreateProjectVersionRequestRequestTypeDef,
+):
+    pass
+
+TestingDataResultTypeDef = TypedDict(
+    "TestingDataResultTypeDef",
     {
-        "Assets": List[AssetTypeDef],
+        "Input": TestingDataTypeDef,
+        "Output": TestingDataTypeDef,
+        "Validation": ValidationDataTypeDef,
     },
     total=False,
 )
 
-_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDatasetRequestRequestTypeDef",
-    {
-        "DatasetType": DatasetTypeType,
-        "ProjectArn": str,
-    },
-)
-_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDatasetRequestRequestTypeDef",
+TrainingDataResultTypeDef = TypedDict(
+    "TrainingDataResultTypeDef",
     {
-        "DatasetSource": DatasetSourceTypeDef,
+        "Input": TrainingDataTypeDef,
+        "Output": TrainingDataTypeDef,
+        "Validation": ValidationDataTypeDef,
     },
     total=False,
 )
 
-
-class CreateDatasetRequestRequestTypeDef(
-    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
-):
-    pass
-
-
 DetectProtectiveEquipmentResponseTypeDef = TypedDict(
     "DetectProtectiveEquipmentResponseTypeDef",
     {
         "ProtectiveEquipmentModelVersion": str,
         "Persons": List[ProtectiveEquipmentPersonTypeDef],
         "Summary": ProtectiveEquipmentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLabelDetectionResponseTypeDef = TypedDict(
     "GetLabelDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Labels": List[LabelDetectionTypeDef],
         "LabelModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "GetRequestMetadata": GetLabelDetectionRequestMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCelebrityRecognitionResponseTypeDef = TypedDict(
     "GetCelebrityRecognitionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Celebrities": List[CelebrityRecognitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPersonTrackingResponseTypeDef = TypedDict(
     "GetPersonTrackingResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Persons": List[PersonDetectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFaceSearchResponseTypeDef = TypedDict(
     "GetFaceSearchResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "NextToken": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "Persons": List[PersonMatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTextDetectionResponseTypeDef = TypedDict(
     "GetTextDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "TextDetections": List[TextDetectionResultTypeDef],
         "NextToken": str,
         "TextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateProjectVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateProjectVersionRequestRequestTypeDef",
-    {
-        "ProjectArn": str,
-        "VersionName": str,
-        "OutputConfig": OutputConfigTypeDef,
-    },
-)
-_OptionalCreateProjectVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateProjectVersionRequestRequestTypeDef",
-    {
-        "TrainingData": TrainingDataTypeDef,
-        "TestingData": TestingDataTypeDef,
-        "Tags": Mapping[str, str],
-        "KmsKeyId": str,
-    },
-    total=False,
-)
-
-
-class CreateProjectVersionRequestRequestTypeDef(
-    _RequiredCreateProjectVersionRequestRequestTypeDef,
-    _OptionalCreateProjectVersionRequestRequestTypeDef,
-):
-    pass
-
-
-TestingDataResultTypeDef = TypedDict(
-    "TestingDataResultTypeDef",
-    {
-        "Input": TestingDataTypeDef,
-        "Output": TestingDataTypeDef,
-        "Validation": ValidationDataTypeDef,
-    },
-    total=False,
-)
-
-TrainingDataResultTypeDef = TypedDict(
-    "TrainingDataResultTypeDef",
-    {
-        "Input": TrainingDataTypeDef,
-        "Output": TrainingDataTypeDef,
-        "Validation": ValidationDataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ProjectVersionDescriptionTypeDef = TypedDict(
     "ProjectVersionDescriptionTypeDef",
     {
         "ProjectVersionArn": str,
         "CreationTimestamp": datetime,
@@ -3343,10 +3762,10 @@
 )
 
 DescribeProjectVersionsResponseTypeDef = TypedDict(
     "DescribeProjectVersionsResponseTypeDef",
     {
         "ProjectVersionDescriptions": List[ProjectVersionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/type_defs.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,321 +18,429 @@
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AttributeType,
     BodyPartType,
     CelebrityRecognitionSortByType,
     ContentClassifierType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetStatusMessageCodeType,
     DatasetStatusType,
     DatasetTypeType,
     DetectLabelsFeatureNameType,
     EmotionNameType,
     FaceAttributesType,
     FaceSearchSortByType,
     GenderTypeType,
     KnownGenderTypeType,
     LabelDetectionAggregateByType,
     LabelDetectionSortByType,
     LandmarkTypeType,
+    LivenessSessionStatusType,
     OrientationCorrectionType,
     PersonTrackingSortByType,
     ProjectStatusType,
     ProjectVersionStatusType,
     ProtectiveEquipmentTypeType,
     QualityFilterType,
     ReasonType,
     SegmentTypeType,
     StreamProcessorParameterToDeleteType,
     StreamProcessorStatusType,
     TechnicalCueTypeType,
     TextTypesType,
+    UnsearchedFaceReasonType,
+    UnsuccessfulFaceAssociationReasonType,
+    UnsuccessfulFaceDeletionReasonType,
+    UnsuccessfulFaceDisassociationReasonType,
+    UserStatusType,
     VideoColorRangeType,
     VideoJobStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AgeRangeTypeDef",
+    "AssociateFacesRequestRequestTypeDef",
+    "AssociatedFaceTypeDef",
+    "UnsuccessfulFaceAssociationTypeDef",
     "AudioMetadataTypeDef",
+    "BoundingBoxTypeDef",
+    "S3ObjectTypeDef",
     "BeardTypeDef",
     "BlackFrameTypeDef",
-    "BoundingBoxTypeDef",
     "KnownGenderTypeDef",
-    "ResponseMetadataTypeDef",
     "EmotionTypeDef",
     "ImageQualityTypeDef",
     "LandmarkTypeDef",
     "PoseTypeDef",
     "SmileTypeDef",
     "ConnectedHomeSettingsForUpdateTypeDef",
     "ConnectedHomeSettingsTypeDef",
     "ModerationLabelTypeDef",
     "OutputConfigTypeDef",
+    "CopyProjectVersionResponseTypeDef",
     "CoversBodyPartTypeDef",
     "CreateCollectionRequestRequestTypeDef",
+    "CreateCollectionResponseTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "LivenessOutputConfigTypeDef",
+    "CreateFaceLivenessSessionResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
+    "CreateProjectVersionResponseTypeDef",
     "StreamProcessorDataSharingPreferenceTypeDef",
     "StreamProcessorNotificationChannelTypeDef",
+    "CreateStreamProcessorResponseTypeDef",
+    "CreateUserRequestRequestTypeDef",
     "DatasetChangesTypeDef",
     "DatasetStatsTypeDef",
     "DatasetLabelStatsTypeDef",
     "DatasetMetadataTypeDef",
     "DeleteCollectionRequestRequestTypeDef",
+    "DeleteCollectionResponseTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteFacesRequestRequestTypeDef",
+    "UnsuccessfulFaceDeletionTypeDef",
     "DeleteProjectPolicyRequestRequestTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResponseTypeDef",
     "DeleteProjectVersionRequestRequestTypeDef",
+    "DeleteProjectVersionResponseTypeDef",
     "DeleteStreamProcessorRequestRequestTypeDef",
+    "DeleteUserRequestRequestTypeDef",
     "DescribeCollectionRequestRequestTypeDef",
+    "DescribeCollectionResponseTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeProjectVersionsRequestRequestTypeDef",
+    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
     "DescribeProjectsRequestRequestTypeDef",
     "DescribeStreamProcessorRequestRequestTypeDef",
     "DetectLabelsImageQualityTypeDef",
     "DominantColorTypeDef",
     "DetectLabelsImagePropertiesSettingsTypeDef",
     "GeneralLabelsSettingsTypeDef",
     "HumanLoopActivationOutputTypeDef",
     "ProtectiveEquipmentSummarizationAttributesTypeDef",
     "ProtectiveEquipmentSummaryTypeDef",
     "DetectionFilterTypeDef",
+    "DisassociateFacesRequestRequestTypeDef",
+    "DisassociatedFaceTypeDef",
+    "UnsuccessfulFaceDisassociationTypeDef",
     "DistributeDatasetTypeDef",
+    "EyeDirectionTypeDef",
     "EyeOpenTypeDef",
     "EyeglassesTypeDef",
+    "FaceOccludedTypeDef",
     "GenderTypeDef",
     "MouthOpenTypeDef",
     "MustacheTypeDef",
     "SunglassesTypeDef",
     "FaceSearchSettingsTypeDef",
     "PointTypeDef",
     "GetCelebrityInfoRequestRequestTypeDef",
     "GetCelebrityRecognitionRequestRequestTypeDef",
     "VideoMetadataTypeDef",
+    "GetContentModerationRequestMetadataTypeDef",
     "GetContentModerationRequestRequestTypeDef",
     "GetFaceDetectionRequestRequestTypeDef",
+    "GetFaceLivenessSessionResultsRequestRequestTypeDef",
     "GetFaceSearchRequestRequestTypeDef",
+    "GetLabelDetectionRequestMetadataTypeDef",
     "GetLabelDetectionRequestRequestTypeDef",
     "GetPersonTrackingRequestRequestTypeDef",
     "GetSegmentDetectionRequestRequestTypeDef",
     "SegmentTypeInfoTypeDef",
     "GetTextDetectionRequestRequestTypeDef",
-    "S3ObjectTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "KinesisDataStreamTypeDef",
     "KinesisVideoStreamStartSelectorTypeDef",
     "KinesisVideoStreamTypeDef",
     "LabelAliasTypeDef",
     "LabelCategoryTypeDef",
     "ParentTypeDef",
+    "ListCollectionsRequestListCollectionsPaginateTypeDef",
     "ListCollectionsRequestRequestTypeDef",
+    "ListCollectionsResponseTypeDef",
+    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
     "ListDatasetEntriesRequestRequestTypeDef",
+    "ListDatasetEntriesResponseTypeDef",
+    "ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
     "ListDatasetLabelsRequestRequestTypeDef",
+    "ListFacesRequestListFacesPaginateTypeDef",
     "ListFacesRequestRequestTypeDef",
+    "ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
     "ListProjectPoliciesRequestRequestTypeDef",
     "ProjectPolicyTypeDef",
+    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
     "ListStreamProcessorsRequestRequestTypeDef",
     "StreamProcessorTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
+    "ListUsersRequestRequestTypeDef",
+    "UserTypeDef",
+    "MatchedUserTypeDef",
     "NotificationChannelTypeDef",
+    "PaginatorConfigTypeDef",
     "PutProjectPolicyRequestRequestTypeDef",
+    "PutProjectPolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3DestinationTypeDef",
     "SearchFacesRequestRequestTypeDef",
+    "SearchUsersRequestRequestTypeDef",
+    "SearchedFaceTypeDef",
+    "SearchedUserTypeDef",
     "ShotSegmentTypeDef",
     "TechnicalCueSegmentTypeDef",
-    "StartProjectVersionRequestRequestTypeDef",
-    "StartShotDetectionFilterTypeDef",
-    "StreamProcessingStopSelectorTypeDef",
-    "StopProjectVersionRequestRequestTypeDef",
-    "StopStreamProcessorRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "StartTechnicalCueDetectionFilterTypeDef",
-    "ComparedSourceImageFaceTypeDef",
-    "FaceTypeDef",
-    "CopyProjectVersionResponseTypeDef",
-    "CreateCollectionResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "CreateProjectVersionResponseTypeDef",
-    "CreateStreamProcessorResponseTypeDef",
-    "DeleteCollectionResponseTypeDef",
-    "DeleteFacesResponseTypeDef",
-    "DeleteProjectResponseTypeDef",
-    "DeleteProjectVersionResponseTypeDef",
-    "DescribeCollectionResponseTypeDef",
-    "GetCelebrityInfoResponseTypeDef",
-    "ListCollectionsResponseTypeDef",
-    "ListDatasetEntriesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutProjectPolicyResponseTypeDef",
     "StartCelebrityRecognitionResponseTypeDef",
     "StartContentModerationResponseTypeDef",
     "StartFaceDetectionResponseTypeDef",
     "StartFaceSearchResponseTypeDef",
     "StartLabelDetectionResponseTypeDef",
     "StartPersonTrackingResponseTypeDef",
+    "StartProjectVersionRequestRequestTypeDef",
     "StartProjectVersionResponseTypeDef",
+    "StartShotDetectionFilterTypeDef",
     "StartSegmentDetectionResponseTypeDef",
+    "StreamProcessingStopSelectorTypeDef",
     "StartStreamProcessorResponseTypeDef",
     "StartTextDetectionResponseTypeDef",
+    "StopProjectVersionRequestRequestTypeDef",
     "StopProjectVersionResponseTypeDef",
+    "StopStreamProcessorRequestRequestTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "AssociateFacesResponseTypeDef",
+    "ComparedSourceImageFaceTypeDef",
+    "FaceTypeDef",
+    "AuditImageTypeDef",
+    "GroundTruthManifestTypeDef",
+    "ImageTypeDef",
+    "SummaryTypeDef",
+    "VideoTypeDef",
+    "StartTechnicalCueDetectionFilterTypeDef",
+    "GetCelebrityInfoResponseTypeDef",
     "ComparedFaceTypeDef",
     "StreamProcessorSettingsForUpdateTypeDef",
     "ContentModerationDetectionTypeDef",
     "CopyProjectVersionRequestRequestTypeDef",
     "EquipmentDetectionTypeDef",
+    "CreateFaceLivenessSessionRequestSettingsTypeDef",
     "UpdateDatasetEntriesRequestRequestTypeDef",
     "DatasetDescriptionTypeDef",
     "DatasetLabelDescriptionTypeDef",
     "ProjectDescriptionTypeDef",
-    "DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
-    "ListCollectionsRequestListCollectionsPaginateTypeDef",
-    "ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    "ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    "ListFacesRequestListFacesPaginateTypeDef",
-    "ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+    "DeleteFacesResponseTypeDef",
     "DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef",
     "DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef",
     "DetectLabelsImageBackgroundTypeDef",
     "DetectLabelsImageForegroundTypeDef",
     "InstanceTypeDef",
     "DetectLabelsSettingsTypeDef",
     "LabelDetectionSettingsTypeDef",
     "DetectModerationLabelsResponseTypeDef",
+    "DisassociateFacesResponseTypeDef",
     "DistributeDatasetEntriesRequestRequestTypeDef",
     "FaceDetailTypeDef",
     "StreamProcessorSettingsTypeDef",
     "GeometryTypeDef",
     "RegionOfInterestTypeDef",
-    "GroundTruthManifestTypeDef",
-    "ImageTypeDef",
-    "SummaryTypeDef",
-    "VideoTypeDef",
     "HumanLoopConfigTypeDef",
     "StreamProcessingStartSelectorTypeDef",
     "StreamProcessorInputTypeDef",
     "ListProjectPoliciesResponseTypeDef",
     "ListStreamProcessorsResponseTypeDef",
+    "ListUsersResponseTypeDef",
+    "UserMatchTypeDef",
     "StreamProcessorOutputTypeDef",
     "SegmentDetectionTypeDef",
-    "StartSegmentDetectionFiltersTypeDef",
     "FaceMatchTypeDef",
     "ListFacesResponseTypeDef",
+    "GetFaceLivenessSessionResultsResponseTypeDef",
+    "AssetTypeDef",
+    "DatasetSourceTypeDef",
+    "CompareFacesRequestRequestTypeDef",
+    "DetectCustomLabelsRequestRequestTypeDef",
+    "DetectFacesRequestRequestTypeDef",
+    "DetectProtectiveEquipmentRequestRequestTypeDef",
+    "IndexFacesRequestRequestTypeDef",
+    "RecognizeCelebritiesRequestRequestTypeDef",
+    "SearchFacesByImageRequestRequestTypeDef",
+    "SearchUsersByImageRequestRequestTypeDef",
+    "EvaluationResultTypeDef",
+    "StartCelebrityRecognitionRequestRequestTypeDef",
+    "StartContentModerationRequestRequestTypeDef",
+    "StartFaceDetectionRequestRequestTypeDef",
+    "StartFaceSearchRequestRequestTypeDef",
+    "StartPersonTrackingRequestRequestTypeDef",
+    "StartSegmentDetectionFiltersTypeDef",
     "CelebrityTypeDef",
     "CompareFacesMatchTypeDef",
     "GetContentModerationResponseTypeDef",
     "ProtectiveEquipmentBodyPartTypeDef",
+    "CreateFaceLivenessSessionRequestRequestTypeDef",
     "DescribeDatasetResponseTypeDef",
     "ListDatasetLabelsResponseTypeDef",
     "DescribeProjectsResponseTypeDef",
     "DetectLabelsImagePropertiesTypeDef",
     "LabelTypeDef",
+    "DetectLabelsRequestRequestTypeDef",
+    "StartLabelDetectionRequestRequestTypeDef",
     "CelebrityDetailTypeDef",
     "DetectFacesResponseTypeDef",
     "FaceDetectionTypeDef",
     "FaceRecordTypeDef",
     "PersonDetailTypeDef",
+    "SearchedFaceDetailsTypeDef",
     "UnindexedFaceTypeDef",
+    "UnsearchedFaceTypeDef",
     "CustomLabelTypeDef",
     "TextDetectionTypeDef",
     "DetectTextFiltersTypeDef",
     "StartTextDetectionFiltersTypeDef",
     "UpdateStreamProcessorRequestRequestTypeDef",
-    "AssetTypeDef",
-    "DatasetSourceTypeDef",
-    "CompareFacesRequestRequestTypeDef",
-    "DetectCustomLabelsRequestRequestTypeDef",
-    "DetectFacesRequestRequestTypeDef",
-    "DetectLabelsRequestRequestTypeDef",
-    "DetectProtectiveEquipmentRequestRequestTypeDef",
-    "IndexFacesRequestRequestTypeDef",
-    "RecognizeCelebritiesRequestRequestTypeDef",
-    "SearchFacesByImageRequestRequestTypeDef",
-    "EvaluationResultTypeDef",
-    "StartCelebrityRecognitionRequestRequestTypeDef",
-    "StartContentModerationRequestRequestTypeDef",
-    "StartFaceDetectionRequestRequestTypeDef",
-    "StartFaceSearchRequestRequestTypeDef",
-    "StartLabelDetectionRequestRequestTypeDef",
-    "StartPersonTrackingRequestRequestTypeDef",
     "DetectModerationLabelsRequestRequestTypeDef",
     "StartStreamProcessorRequestRequestTypeDef",
+    "SearchUsersResponseTypeDef",
     "CreateStreamProcessorRequestRequestTypeDef",
     "DescribeStreamProcessorResponseTypeDef",
     "GetSegmentDetectionResponseTypeDef",
-    "StartSegmentDetectionRequestRequestTypeDef",
     "SearchFacesByImageResponseTypeDef",
     "SearchFacesResponseTypeDef",
+    "TestingDataTypeDef",
+    "TrainingDataTypeDef",
+    "ValidationDataTypeDef",
+    "CreateDatasetRequestRequestTypeDef",
+    "StartSegmentDetectionRequestRequestTypeDef",
     "RecognizeCelebritiesResponseTypeDef",
     "CompareFacesResponseTypeDef",
     "ProtectiveEquipmentPersonTypeDef",
     "DetectLabelsResponseTypeDef",
     "LabelDetectionTypeDef",
     "CelebrityRecognitionTypeDef",
     "GetFaceDetectionResponseTypeDef",
     "PersonDetectionTypeDef",
     "PersonMatchTypeDef",
     "IndexFacesResponseTypeDef",
+    "SearchUsersByImageResponseTypeDef",
     "DetectCustomLabelsResponseTypeDef",
     "DetectTextResponseTypeDef",
     "TextDetectionResultTypeDef",
     "DetectTextRequestRequestTypeDef",
     "StartTextDetectionRequestRequestTypeDef",
-    "TestingDataTypeDef",
-    "TrainingDataTypeDef",
-    "ValidationDataTypeDef",
-    "CreateDatasetRequestRequestTypeDef",
+    "CreateProjectVersionRequestRequestTypeDef",
+    "TestingDataResultTypeDef",
+    "TrainingDataResultTypeDef",
     "DetectProtectiveEquipmentResponseTypeDef",
     "GetLabelDetectionResponseTypeDef",
     "GetCelebrityRecognitionResponseTypeDef",
     "GetPersonTrackingResponseTypeDef",
     "GetFaceSearchResponseTypeDef",
     "GetTextDetectionResponseTypeDef",
-    "CreateProjectVersionRequestRequestTypeDef",
-    "TestingDataResultTypeDef",
-    "TrainingDataResultTypeDef",
     "ProjectVersionDescriptionTypeDef",
     "DescribeProjectVersionsResponseTypeDef",
 )
 
 AgeRangeTypeDef = TypedDict(
     "AgeRangeTypeDef",
     {
         "Low": int,
         "High": int,
     },
     total=False,
 )
 
+_RequiredAssociateFacesRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateFacesRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+        "FaceIds": Sequence[str],
+    },
+)
+_OptionalAssociateFacesRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateFacesRequestRequestTypeDef",
+    {
+        "UserMatchThreshold": float,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+
+class AssociateFacesRequestRequestTypeDef(
+    _RequiredAssociateFacesRequestRequestTypeDef, _OptionalAssociateFacesRequestRequestTypeDef
+):
+    pass
+
+
+AssociatedFaceTypeDef = TypedDict(
+    "AssociatedFaceTypeDef",
+    {
+        "FaceId": str,
+    },
+    total=False,
+)
+
+UnsuccessfulFaceAssociationTypeDef = TypedDict(
+    "UnsuccessfulFaceAssociationTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Confidence": float,
+        "Reasons": List[UnsuccessfulFaceAssociationReasonType],
+    },
+    total=False,
+)
+
 AudioMetadataTypeDef = TypedDict(
     "AudioMetadataTypeDef",
     {
         "Codec": str,
         "DurationMillis": int,
         "SampleRate": int,
         "NumberOfChannels": int,
     },
     total=False,
 )
 
+BoundingBoxTypeDef = TypedDict(
+    "BoundingBoxTypeDef",
+    {
+        "Width": float,
+        "Height": float,
+        "Left": float,
+        "Top": float,
+    },
+    total=False,
+)
+
+S3ObjectTypeDef = TypedDict(
+    "S3ObjectTypeDef",
+    {
+        "Bucket": str,
+        "Name": str,
+        "Version": str,
+    },
+    total=False,
+)
+
 BeardTypeDef = TypedDict(
     "BeardTypeDef",
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
@@ -343,44 +451,22 @@
     {
         "MaxPixelThreshold": float,
         "MinCoveragePercentage": float,
     },
     total=False,
 )
 
-BoundingBoxTypeDef = TypedDict(
-    "BoundingBoxTypeDef",
-    {
-        "Width": float,
-        "Height": float,
-        "Left": float,
-        "Top": float,
-    },
-    total=False,
-)
-
 KnownGenderTypeDef = TypedDict(
     "KnownGenderTypeDef",
     {
         "Type": KnownGenderTypeType,
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
 EmotionTypeDef = TypedDict(
     "EmotionTypeDef",
     {
         "Type": EmotionNameType,
         "Confidence": float,
     },
     total=False,
@@ -443,19 +529,21 @@
     "_OptionalConnectedHomeSettingsTypeDef",
     {
         "MinConfidence": float,
     },
     total=False,
 )
 
+
 class ConnectedHomeSettingsTypeDef(
     _RequiredConnectedHomeSettingsTypeDef, _OptionalConnectedHomeSettingsTypeDef
 ):
     pass
 
+
 ModerationLabelTypeDef = TypedDict(
     "ModerationLabelTypeDef",
     {
         "Confidence": float,
         "Name": str,
         "ParentName": str,
     },
@@ -467,14 +555,22 @@
     {
         "S3Bucket": str,
         "S3KeyPrefix": str,
     },
     total=False,
 )
 
+CopyProjectVersionResponseTypeDef = TypedDict(
+    "CopyProjectVersionResponseTypeDef",
+    {
+        "ProjectVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CoversBodyPartTypeDef = TypedDict(
     "CoversBodyPartTypeDef",
     {
         "Confidence": float,
         "Value": bool,
     },
     total=False,
@@ -490,40 +586,135 @@
     "_OptionalCreateCollectionRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateCollectionRequestRequestTypeDef(
     _RequiredCreateCollectionRequestRequestTypeDef, _OptionalCreateCollectionRequestRequestTypeDef
 ):
     pass
 
+
+CreateCollectionResponseTypeDef = TypedDict(
+    "CreateCollectionResponseTypeDef",
+    {
+        "StatusCode": int,
+        "CollectionArn": str,
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "DatasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredLivenessOutputConfigTypeDef = TypedDict(
+    "_RequiredLivenessOutputConfigTypeDef",
+    {
+        "S3Bucket": str,
+    },
+)
+_OptionalLivenessOutputConfigTypeDef = TypedDict(
+    "_OptionalLivenessOutputConfigTypeDef",
+    {
+        "S3KeyPrefix": str,
+    },
+    total=False,
+)
+
+
+class LivenessOutputConfigTypeDef(
+    _RequiredLivenessOutputConfigTypeDef, _OptionalLivenessOutputConfigTypeDef
+):
+    pass
+
+
+CreateFaceLivenessSessionResponseTypeDef = TypedDict(
+    "CreateFaceLivenessSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateProjectRequestRequestTypeDef = TypedDict(
     "CreateProjectRequestRequestTypeDef",
     {
         "ProjectName": str,
     },
 )
 
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "ProjectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProjectVersionResponseTypeDef = TypedDict(
+    "CreateProjectVersionResponseTypeDef",
+    {
+        "ProjectVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StreamProcessorDataSharingPreferenceTypeDef = TypedDict(
     "StreamProcessorDataSharingPreferenceTypeDef",
     {
         "OptIn": bool,
     },
 )
 
 StreamProcessorNotificationChannelTypeDef = TypedDict(
     "StreamProcessorNotificationChannelTypeDef",
     {
         "SNSTopicArn": str,
     },
 )
 
+CreateStreamProcessorResponseTypeDef = TypedDict(
+    "CreateStreamProcessorResponseTypeDef",
+    {
+        "StreamProcessorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateUserRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateUserRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+    },
+)
+_OptionalCreateUserRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateUserRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+
+class CreateUserRequestRequestTypeDef(
+    _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
+):
+    pass
+
+
 DatasetChangesTypeDef = TypedDict(
     "DatasetChangesTypeDef",
     {
         "GroundTruth": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
@@ -563,14 +754,22 @@
 DeleteCollectionRequestRequestTypeDef = TypedDict(
     "DeleteCollectionRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 
+DeleteCollectionResponseTypeDef = TypedDict(
+    "DeleteCollectionResponseTypeDef",
+    {
+        "StatusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDatasetRequestRequestTypeDef = TypedDict(
     "DeleteDatasetRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 
@@ -578,14 +777,24 @@
     "DeleteFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
         "FaceIds": Sequence[str],
     },
 )
 
+UnsuccessfulFaceDeletionTypeDef = TypedDict(
+    "UnsuccessfulFaceDeletionTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Reasons": List[UnsuccessfulFaceDeletionReasonType],
+    },
+    total=False,
+)
+
 _RequiredDeleteProjectPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectPolicyRequestRequestTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
     },
 )
@@ -593,65 +802,130 @@
     "_OptionalDeleteProjectPolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
+
 class DeleteProjectPolicyRequestRequestTypeDef(
     _RequiredDeleteProjectPolicyRequestRequestTypeDef,
     _OptionalDeleteProjectPolicyRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteProjectRequestRequestTypeDef = TypedDict(
     "DeleteProjectRequestRequestTypeDef",
     {
         "ProjectArn": str,
     },
 )
 
+DeleteProjectResponseTypeDef = TypedDict(
+    "DeleteProjectResponseTypeDef",
+    {
+        "Status": ProjectStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProjectVersionRequestRequestTypeDef = TypedDict(
     "DeleteProjectVersionRequestRequestTypeDef",
     {
         "ProjectVersionArn": str,
     },
 )
 
+DeleteProjectVersionResponseTypeDef = TypedDict(
+    "DeleteProjectVersionResponseTypeDef",
+    {
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteStreamProcessorRequestRequestTypeDef = TypedDict(
     "DeleteStreamProcessorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+_RequiredDeleteUserRequestRequestTypeDef = TypedDict(
+    "_RequiredDeleteUserRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+    },
+)
+_OptionalDeleteUserRequestRequestTypeDef = TypedDict(
+    "_OptionalDeleteUserRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+
+class DeleteUserRequestRequestTypeDef(
+    _RequiredDeleteUserRequestRequestTypeDef, _OptionalDeleteUserRequestRequestTypeDef
+):
+    pass
+
+
 DescribeCollectionRequestRequestTypeDef = TypedDict(
     "DescribeCollectionRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 
+DescribeCollectionResponseTypeDef = TypedDict(
+    "DescribeCollectionResponseTypeDef",
+    {
+        "FaceCount": int,
+        "FaceModelVersion": str,
+        "CollectionARN": str,
+        "CreationTimestamp": datetime,
+        "UserCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDatasetRequestRequestTypeDef = TypedDict(
     "DescribeDatasetRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProjectArn": str,
+    },
+)
+_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
+    {
+        "VersionNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef(
+    _RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
+    _OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
+):
+    pass
+
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -669,20 +943,31 @@
         "VersionNames": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class DescribeProjectVersionsRequestRequestTypeDef(
     _RequiredDescribeProjectVersionsRequestRequestTypeDef,
     _OptionalDescribeProjectVersionsRequestRequestTypeDef,
 ):
     pass
 
+
+DescribeProjectsRequestDescribeProjectsPaginateTypeDef = TypedDict(
+    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
+    {
+        "ProjectNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeProjectsRequestRequestTypeDef = TypedDict(
     "DescribeProjectsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ProjectNames": Sequence[str],
     },
@@ -773,21 +1058,72 @@
         "MinConfidence": float,
         "MinBoundingBoxHeight": float,
         "MinBoundingBoxWidth": float,
     },
     total=False,
 )
 
+_RequiredDisassociateFacesRequestRequestTypeDef = TypedDict(
+    "_RequiredDisassociateFacesRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "UserId": str,
+        "FaceIds": Sequence[str],
+    },
+)
+_OptionalDisassociateFacesRequestRequestTypeDef = TypedDict(
+    "_OptionalDisassociateFacesRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+
+class DisassociateFacesRequestRequestTypeDef(
+    _RequiredDisassociateFacesRequestRequestTypeDef, _OptionalDisassociateFacesRequestRequestTypeDef
+):
+    pass
+
+
+DisassociatedFaceTypeDef = TypedDict(
+    "DisassociatedFaceTypeDef",
+    {
+        "FaceId": str,
+    },
+    total=False,
+)
+
+UnsuccessfulFaceDisassociationTypeDef = TypedDict(
+    "UnsuccessfulFaceDisassociationTypeDef",
+    {
+        "FaceId": str,
+        "UserId": str,
+        "Reasons": List[UnsuccessfulFaceDisassociationReasonType],
+    },
+    total=False,
+)
+
 DistributeDatasetTypeDef = TypedDict(
     "DistributeDatasetTypeDef",
     {
         "Arn": str,
     },
 )
 
+EyeDirectionTypeDef = TypedDict(
+    "EyeDirectionTypeDef",
+    {
+        "Yaw": float,
+        "Pitch": float,
+        "Confidence": float,
+    },
+    total=False,
+)
+
 EyeOpenTypeDef = TypedDict(
     "EyeOpenTypeDef",
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
@@ -798,14 +1134,23 @@
     {
         "Value": bool,
         "Confidence": float,
     },
     total=False,
 )
 
+FaceOccludedTypeDef = TypedDict(
+    "FaceOccludedTypeDef",
+    {
+        "Value": bool,
+        "Confidence": float,
+    },
+    total=False,
+)
+
 GenderTypeDef = TypedDict(
     "GenderTypeDef",
     {
         "Value": GenderTypeType,
         "Confidence": float,
     },
     total=False,
@@ -875,56 +1220,70 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": CelebrityRecognitionSortByType,
     },
     total=False,
 )
 
+
 class GetCelebrityRecognitionRequestRequestTypeDef(
     _RequiredGetCelebrityRecognitionRequestRequestTypeDef,
     _OptionalGetCelebrityRecognitionRequestRequestTypeDef,
 ):
     pass
 
+
 VideoMetadataTypeDef = TypedDict(
     "VideoMetadataTypeDef",
     {
         "Codec": str,
         "DurationMillis": int,
         "Format": str,
         "FrameRate": float,
         "FrameHeight": int,
         "FrameWidth": int,
         "ColorRange": VideoColorRangeType,
     },
     total=False,
 )
 
+GetContentModerationRequestMetadataTypeDef = TypedDict(
+    "GetContentModerationRequestMetadataTypeDef",
+    {
+        "SortBy": ContentModerationSortByType,
+        "AggregateBy": ContentModerationAggregateByType,
+    },
+    total=False,
+)
+
 _RequiredGetContentModerationRequestRequestTypeDef = TypedDict(
     "_RequiredGetContentModerationRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetContentModerationRequestRequestTypeDef = TypedDict(
     "_OptionalGetContentModerationRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "SortBy": ContentModerationSortByType,
+        "AggregateBy": ContentModerationAggregateByType,
     },
     total=False,
 )
 
+
 class GetContentModerationRequestRequestTypeDef(
     _RequiredGetContentModerationRequestRequestTypeDef,
     _OptionalGetContentModerationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetFaceDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetFaceDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetFaceDetectionRequestRequestTypeDef = TypedDict(
@@ -932,19 +1291,28 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetFaceDetectionRequestRequestTypeDef(
     _RequiredGetFaceDetectionRequestRequestTypeDef, _OptionalGetFaceDetectionRequestRequestTypeDef
 ):
     pass
 
+
+GetFaceLivenessSessionResultsRequestRequestTypeDef = TypedDict(
+    "GetFaceLivenessSessionResultsRequestRequestTypeDef",
+    {
+        "SessionId": str,
+    },
+)
+
 _RequiredGetFaceSearchRequestRequestTypeDef = TypedDict(
     "_RequiredGetFaceSearchRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetFaceSearchRequestRequestTypeDef = TypedDict(
@@ -953,19 +1321,30 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": FaceSearchSortByType,
     },
     total=False,
 )
 
+
 class GetFaceSearchRequestRequestTypeDef(
     _RequiredGetFaceSearchRequestRequestTypeDef, _OptionalGetFaceSearchRequestRequestTypeDef
 ):
     pass
 
+
+GetLabelDetectionRequestMetadataTypeDef = TypedDict(
+    "GetLabelDetectionRequestMetadataTypeDef",
+    {
+        "SortBy": LabelDetectionSortByType,
+        "AggregateBy": LabelDetectionAggregateByType,
+    },
+    total=False,
+)
+
 _RequiredGetLabelDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetLabelDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetLabelDetectionRequestRequestTypeDef = TypedDict(
@@ -975,19 +1354,21 @@
         "NextToken": str,
         "SortBy": LabelDetectionSortByType,
         "AggregateBy": LabelDetectionAggregateByType,
     },
     total=False,
 )
 
+
 class GetLabelDetectionRequestRequestTypeDef(
     _RequiredGetLabelDetectionRequestRequestTypeDef, _OptionalGetLabelDetectionRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetPersonTrackingRequestRequestTypeDef = TypedDict(
     "_RequiredGetPersonTrackingRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetPersonTrackingRequestRequestTypeDef = TypedDict(
@@ -996,19 +1377,21 @@
         "MaxResults": int,
         "NextToken": str,
         "SortBy": PersonTrackingSortByType,
     },
     total=False,
 )
 
+
 class GetPersonTrackingRequestRequestTypeDef(
     _RequiredGetPersonTrackingRequestRequestTypeDef, _OptionalGetPersonTrackingRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetSegmentDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentDetectionRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetSegmentDetectionRequestRequestTypeDef = TypedDict(
@@ -1016,20 +1399,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetSegmentDetectionRequestRequestTypeDef(
     _RequiredGetSegmentDetectionRequestRequestTypeDef,
     _OptionalGetSegmentDetectionRequestRequestTypeDef,
 ):
     pass
 
+
 SegmentTypeInfoTypeDef = TypedDict(
     "SegmentTypeInfoTypeDef",
     {
         "Type": SegmentTypeType,
         "ModelVersion": str,
     },
     total=False,
@@ -1046,28 +1431,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetTextDetectionRequestRequestTypeDef(
     _RequiredGetTextDetectionRequestRequestTypeDef, _OptionalGetTextDetectionRequestRequestTypeDef
 ):
     pass
 
-S3ObjectTypeDef = TypedDict(
-    "S3ObjectTypeDef",
-    {
-        "Bucket": str,
-        "Name": str,
-        "Version": str,
-    },
-    total=False,
-)
 
 HumanLoopDataAttributesTypeDef = TypedDict(
     "HumanLoopDataAttributesTypeDef",
     {
         "ContentClassifiers": Sequence[ContentClassifierType],
     },
     total=False,
@@ -1118,23 +1495,67 @@
     "ParentTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+ListCollectionsRequestListCollectionsPaginateTypeDef = TypedDict(
+    "ListCollectionsRequestListCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCollectionsRequestRequestTypeDef = TypedDict(
     "ListCollectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListCollectionsResponseTypeDef = TypedDict(
+    "ListCollectionsResponseTypeDef",
+    {
+        "CollectionIds": List[str],
+        "NextToken": str,
+        "FaceModelVersions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
+_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
+    {
+        "ContainsLabels": Sequence[str],
+        "Labeled": bool,
+        "SourceRefContains": str,
+        "HasErrors": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
+    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatasetEntriesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetEntriesRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 _OptionalListDatasetEntriesRequestRequestTypeDef = TypedDict(
@@ -1146,20 +1567,53 @@
         "HasErrors": bool,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDatasetEntriesRequestRequestTypeDef(
     _RequiredListDatasetEntriesRequestRequestTypeDef,
     _OptionalListDatasetEntriesRequestRequestTypeDef,
 ):
     pass
 
+
+ListDatasetEntriesResponseTypeDef = TypedDict(
+    "ListDatasetEntriesResponseTypeDef",
+    {
+        "DatasetEntries": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
+_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef(
+    _RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
+    _OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatasetLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetLabelsRequestRequestTypeDef",
     {
         "DatasetArn": str,
     },
 )
 _OptionalListDatasetLabelsRequestRequestTypeDef = TypedDict(
@@ -1167,39 +1621,91 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDatasetLabelsRequestRequestTypeDef(
     _RequiredListDatasetLabelsRequestRequestTypeDef, _OptionalListDatasetLabelsRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredListFacesRequestListFacesPaginateTypeDef = TypedDict(
+    "_RequiredListFacesRequestListFacesPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListFacesRequestListFacesPaginateTypeDef = TypedDict(
+    "_OptionalListFacesRequestListFacesPaginateTypeDef",
+    {
+        "UserId": str,
+        "FaceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFacesRequestListFacesPaginateTypeDef(
+    _RequiredListFacesRequestListFacesPaginateTypeDef,
+    _OptionalListFacesRequestListFacesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFacesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListFacesRequestRequestTypeDef = TypedDict(
     "_OptionalListFacesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "UserId": str,
+        "FaceIds": Sequence[str],
     },
     total=False,
 )
 
+
 class ListFacesRequestRequestTypeDef(
     _RequiredListFacesRequestRequestTypeDef, _OptionalListFacesRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
+    {
+        "ProjectArn": str,
+    },
+)
+_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef(
+    _RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
+    _OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProjectPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectPoliciesRequestRequestTypeDef",
     {
         "ProjectArn": str,
     },
 )
 _OptionalListProjectPoliciesRequestRequestTypeDef = TypedDict(
@@ -1207,33 +1713,43 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListProjectPoliciesRequestRequestTypeDef(
     _RequiredListProjectPoliciesRequestRequestTypeDef,
     _OptionalListProjectPoliciesRequestRequestTypeDef,
 ):
     pass
 
+
 ProjectPolicyTypeDef = TypedDict(
     "ProjectPolicyTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
         "PolicyRevisionId": str,
         "PolicyDocument": str,
         "CreationTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
+ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef = TypedDict(
+    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamProcessorsRequestRequestTypeDef = TypedDict(
     "ListStreamProcessorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1251,22 +1767,102 @@
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
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsersRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsersRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class ListUsersRequestRequestTypeDef(
+    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
+):
+    pass
+
+
+UserTypeDef = TypedDict(
+    "UserTypeDef",
+    {
+        "UserId": str,
+        "UserStatus": UserStatusType,
+    },
+    total=False,
+)
+
+MatchedUserTypeDef = TypedDict(
+    "MatchedUserTypeDef",
+    {
+        "UserId": str,
+        "UserStatus": UserStatusType,
+    },
+    total=False,
+)
+
 NotificationChannelTypeDef = TypedDict(
     "NotificationChannelTypeDef",
     {
         "SNSTopicArn": str,
         "RoleArn": str,
     },
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
 _RequiredPutProjectPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutProjectPolicyRequestRequestTypeDef",
     {
         "ProjectArn": str,
         "PolicyName": str,
         "PolicyDocument": str,
     },
@@ -1275,19 +1871,40 @@
     "_OptionalPutProjectPolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
+
 class PutProjectPolicyRequestRequestTypeDef(
     _RequiredPutProjectPolicyRequestRequestTypeDef, _OptionalPutProjectPolicyRequestRequestTypeDef
 ):
     pass
 
+
+PutProjectPolicyResponseTypeDef = TypedDict(
+    "PutProjectPolicyResponseTypeDef",
+    {
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 S3DestinationTypeDef = TypedDict(
     "S3DestinationTypeDef",
     {
         "Bucket": str,
         "KeyPrefix": str,
     },
     total=False,
@@ -1305,358 +1922,328 @@
     {
         "MaxFaces": int,
         "FaceMatchThreshold": float,
     },
     total=False,
 )
 
+
 class SearchFacesRequestRequestTypeDef(
     _RequiredSearchFacesRequestRequestTypeDef, _OptionalSearchFacesRequestRequestTypeDef
 ):
     pass
 
-ShotSegmentTypeDef = TypedDict(
-    "ShotSegmentTypeDef",
-    {
-        "Index": int,
-        "Confidence": float,
-    },
-    total=False,
-)
 
-TechnicalCueSegmentTypeDef = TypedDict(
-    "TechnicalCueSegmentTypeDef",
+_RequiredSearchUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchUsersRequestRequestTypeDef",
     {
-        "Type": TechnicalCueTypeType,
-        "Confidence": float,
-    },
-    total=False,
-)
-
-_RequiredStartProjectVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredStartProjectVersionRequestRequestTypeDef",
-    {
-        "ProjectVersionArn": str,
-        "MinInferenceUnits": int,
+        "CollectionId": str,
     },
 )
-_OptionalStartProjectVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalStartProjectVersionRequestRequestTypeDef",
+_OptionalSearchUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchUsersRequestRequestTypeDef",
     {
-        "MaxInferenceUnits": int,
+        "UserId": str,
+        "FaceId": str,
+        "UserMatchThreshold": float,
+        "MaxUsers": int,
     },
     total=False,
 )
 
-class StartProjectVersionRequestRequestTypeDef(
-    _RequiredStartProjectVersionRequestRequestTypeDef,
-    _OptionalStartProjectVersionRequestRequestTypeDef,
+
+class SearchUsersRequestRequestTypeDef(
+    _RequiredSearchUsersRequestRequestTypeDef, _OptionalSearchUsersRequestRequestTypeDef
 ):
     pass
 
-StartShotDetectionFilterTypeDef = TypedDict(
-    "StartShotDetectionFilterTypeDef",
+
+SearchedFaceTypeDef = TypedDict(
+    "SearchedFaceTypeDef",
     {
-        "MinSegmentConfidence": float,
+        "FaceId": str,
     },
     total=False,
 )
 
-StreamProcessingStopSelectorTypeDef = TypedDict(
-    "StreamProcessingStopSelectorTypeDef",
+SearchedUserTypeDef = TypedDict(
+    "SearchedUserTypeDef",
     {
-        "MaxDurationInSeconds": int,
+        "UserId": str,
     },
     total=False,
 )
 
-StopProjectVersionRequestRequestTypeDef = TypedDict(
-    "StopProjectVersionRequestRequestTypeDef",
+ShotSegmentTypeDef = TypedDict(
+    "ShotSegmentTypeDef",
     {
-        "ProjectVersionArn": str,
+        "Index": int,
+        "Confidence": float,
     },
+    total=False,
 )
 
-StopStreamProcessorRequestRequestTypeDef = TypedDict(
-    "StopStreamProcessorRequestRequestTypeDef",
+TechnicalCueSegmentTypeDef = TypedDict(
+    "TechnicalCueSegmentTypeDef",
     {
-        "Name": str,
+        "Type": TechnicalCueTypeType,
+        "Confidence": float,
     },
+    total=False,
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+StartCelebrityRecognitionResponseTypeDef = TypedDict(
+    "StartCelebrityRecognitionResponseTypeDef",
     {
-        "ResourceArn": str,
-        "Tags": Mapping[str, str],
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+StartContentModerationResponseTypeDef = TypedDict(
+    "StartContentModerationResponseTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartTechnicalCueDetectionFilterTypeDef = TypedDict(
-    "StartTechnicalCueDetectionFilterTypeDef",
+StartFaceDetectionResponseTypeDef = TypedDict(
+    "StartFaceDetectionResponseTypeDef",
     {
-        "MinSegmentConfidence": float,
-        "BlackFrame": BlackFrameTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ComparedSourceImageFaceTypeDef = TypedDict(
-    "ComparedSourceImageFaceTypeDef",
+StartFaceSearchResponseTypeDef = TypedDict(
+    "StartFaceSearchResponseTypeDef",
     {
-        "BoundingBox": BoundingBoxTypeDef,
-        "Confidence": float,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-FaceTypeDef = TypedDict(
-    "FaceTypeDef",
+StartLabelDetectionResponseTypeDef = TypedDict(
+    "StartLabelDetectionResponseTypeDef",
     {
-        "FaceId": str,
-        "BoundingBox": BoundingBoxTypeDef,
-        "ImageId": str,
-        "ExternalImageId": str,
-        "Confidence": float,
-        "IndexFacesModelVersion": str,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CopyProjectVersionResponseTypeDef = TypedDict(
-    "CopyProjectVersionResponseTypeDef",
+StartPersonTrackingResponseTypeDef = TypedDict(
+    "StartPersonTrackingResponseTypeDef",
     {
-        "ProjectVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateCollectionResponseTypeDef = TypedDict(
-    "CreateCollectionResponseTypeDef",
+_RequiredStartProjectVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredStartProjectVersionRequestRequestTypeDef",
     {
-        "StatusCode": int,
-        "CollectionArn": str,
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProjectVersionArn": str,
+        "MinInferenceUnits": int,
     },
 )
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
+_OptionalStartProjectVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalStartProjectVersionRequestRequestTypeDef",
     {
-        "DatasetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxInferenceUnits": int,
     },
+    total=False,
 )
 
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
-    {
-        "ProjectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateProjectVersionResponseTypeDef = TypedDict(
-    "CreateProjectVersionResponseTypeDef",
-    {
-        "ProjectVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class StartProjectVersionRequestRequestTypeDef(
+    _RequiredStartProjectVersionRequestRequestTypeDef,
+    _OptionalStartProjectVersionRequestRequestTypeDef,
+):
+    pass
 
-CreateStreamProcessorResponseTypeDef = TypedDict(
-    "CreateStreamProcessorResponseTypeDef",
-    {
-        "StreamProcessorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-DeleteCollectionResponseTypeDef = TypedDict(
-    "DeleteCollectionResponseTypeDef",
+StartProjectVersionResponseTypeDef = TypedDict(
+    "StartProjectVersionResponseTypeDef",
     {
-        "StatusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFacesResponseTypeDef = TypedDict(
-    "DeleteFacesResponseTypeDef",
+StartShotDetectionFilterTypeDef = TypedDict(
+    "StartShotDetectionFilterTypeDef",
     {
-        "DeletedFaces": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MinSegmentConfidence": float,
     },
+    total=False,
 )
 
-DeleteProjectResponseTypeDef = TypedDict(
-    "DeleteProjectResponseTypeDef",
+StartSegmentDetectionResponseTypeDef = TypedDict(
+    "StartSegmentDetectionResponseTypeDef",
     {
-        "Status": ProjectStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteProjectVersionResponseTypeDef = TypedDict(
-    "DeleteProjectVersionResponseTypeDef",
+StreamProcessingStopSelectorTypeDef = TypedDict(
+    "StreamProcessingStopSelectorTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxDurationInSeconds": int,
     },
+    total=False,
 )
 
-DescribeCollectionResponseTypeDef = TypedDict(
-    "DescribeCollectionResponseTypeDef",
+StartStreamProcessorResponseTypeDef = TypedDict(
+    "StartStreamProcessorResponseTypeDef",
     {
-        "FaceCount": int,
-        "FaceModelVersion": str,
-        "CollectionARN": str,
-        "CreationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetCelebrityInfoResponseTypeDef = TypedDict(
-    "GetCelebrityInfoResponseTypeDef",
+StartTextDetectionResponseTypeDef = TypedDict(
+    "StartTextDetectionResponseTypeDef",
     {
-        "Urls": List[str],
-        "Name": str,
-        "KnownGender": KnownGenderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListCollectionsResponseTypeDef = TypedDict(
-    "ListCollectionsResponseTypeDef",
+StopProjectVersionRequestRequestTypeDef = TypedDict(
+    "StopProjectVersionRequestRequestTypeDef",
     {
-        "CollectionIds": List[str],
-        "NextToken": str,
-        "FaceModelVersions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProjectVersionArn": str,
     },
 )
 
-ListDatasetEntriesResponseTypeDef = TypedDict(
-    "ListDatasetEntriesResponseTypeDef",
+StopProjectVersionResponseTypeDef = TypedDict(
+    "StopProjectVersionResponseTypeDef",
     {
-        "DatasetEntries": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ProjectVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+StopStreamProcessorRequestRequestTypeDef = TypedDict(
+    "StopStreamProcessorRequestRequestTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
 
-PutProjectPolicyResponseTypeDef = TypedDict(
-    "PutProjectPolicyResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Mapping[str, str],
     },
 )
 
-StartCelebrityRecognitionResponseTypeDef = TypedDict(
-    "StartCelebrityRecognitionResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-StartContentModerationResponseTypeDef = TypedDict(
-    "StartContentModerationResponseTypeDef",
+AssociateFacesResponseTypeDef = TypedDict(
+    "AssociateFacesResponseTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AssociatedFaces": List[AssociatedFaceTypeDef],
+        "UnsuccessfulFaceAssociations": List[UnsuccessfulFaceAssociationTypeDef],
+        "UserStatus": UserStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartFaceDetectionResponseTypeDef = TypedDict(
-    "StartFaceDetectionResponseTypeDef",
+ComparedSourceImageFaceTypeDef = TypedDict(
+    "ComparedSourceImageFaceTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Confidence": float,
     },
+    total=False,
 )
 
-StartFaceSearchResponseTypeDef = TypedDict(
-    "StartFaceSearchResponseTypeDef",
+FaceTypeDef = TypedDict(
+    "FaceTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FaceId": str,
+        "BoundingBox": BoundingBoxTypeDef,
+        "ImageId": str,
+        "ExternalImageId": str,
+        "Confidence": float,
+        "IndexFacesModelVersion": str,
+        "UserId": str,
     },
+    total=False,
 )
 
-StartLabelDetectionResponseTypeDef = TypedDict(
-    "StartLabelDetectionResponseTypeDef",
+AuditImageTypeDef = TypedDict(
+    "AuditImageTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Bytes": bytes,
+        "S3Object": S3ObjectTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
     },
+    total=False,
 )
 
-StartPersonTrackingResponseTypeDef = TypedDict(
-    "StartPersonTrackingResponseTypeDef",
+GroundTruthManifestTypeDef = TypedDict(
+    "GroundTruthManifestTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartProjectVersionResponseTypeDef = TypedDict(
-    "StartProjectVersionResponseTypeDef",
+ImageTypeDef = TypedDict(
+    "ImageTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Bytes": Union[str, bytes, IO[Any], StreamingBody],
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartSegmentDetectionResponseTypeDef = TypedDict(
-    "StartSegmentDetectionResponseTypeDef",
+SummaryTypeDef = TypedDict(
+    "SummaryTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartStreamProcessorResponseTypeDef = TypedDict(
-    "StartStreamProcessorResponseTypeDef",
+VideoTypeDef = TypedDict(
+    "VideoTypeDef",
     {
-        "SessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "S3Object": S3ObjectTypeDef,
     },
+    total=False,
 )
 
-StartTextDetectionResponseTypeDef = TypedDict(
-    "StartTextDetectionResponseTypeDef",
+StartTechnicalCueDetectionFilterTypeDef = TypedDict(
+    "StartTechnicalCueDetectionFilterTypeDef",
     {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MinSegmentConfidence": float,
+        "BlackFrame": BlackFrameTypeDef,
     },
+    total=False,
 )
 
-StopProjectVersionResponseTypeDef = TypedDict(
-    "StopProjectVersionResponseTypeDef",
+GetCelebrityInfoResponseTypeDef = TypedDict(
+    "GetCelebrityInfoResponseTypeDef",
     {
-        "Status": ProjectVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Urls": List[str],
+        "Name": str,
+        "KnownGender": KnownGenderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComparedFaceTypeDef = TypedDict(
     "ComparedFaceTypeDef",
     {
         "BoundingBox": BoundingBoxTypeDef,
@@ -1679,14 +2266,17 @@
 )
 
 ContentModerationDetectionTypeDef = TypedDict(
     "ContentModerationDetectionTypeDef",
     {
         "Timestamp": int,
         "ModerationLabel": ModerationLabelTypeDef,
+        "StartTimestampMillis": int,
+        "EndTimestampMillis": int,
+        "DurationMillis": int,
     },
     total=False,
 )
 
 _RequiredCopyProjectVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCopyProjectVersionRequestRequestTypeDef",
     {
@@ -1702,31 +2292,42 @@
     {
         "Tags": Mapping[str, str],
         "KmsKeyId": str,
     },
     total=False,
 )
 
+
 class CopyProjectVersionRequestRequestTypeDef(
     _RequiredCopyProjectVersionRequestRequestTypeDef,
     _OptionalCopyProjectVersionRequestRequestTypeDef,
 ):
     pass
 
+
 EquipmentDetectionTypeDef = TypedDict(
     "EquipmentDetectionTypeDef",
     {
         "BoundingBox": BoundingBoxTypeDef,
         "Confidence": float,
         "Type": ProtectiveEquipmentTypeType,
         "CoversBodyPart": CoversBodyPartTypeDef,
     },
     total=False,
 )
 
+CreateFaceLivenessSessionRequestSettingsTypeDef = TypedDict(
+    "CreateFaceLivenessSessionRequestSettingsTypeDef",
+    {
+        "OutputConfig": LivenessOutputConfigTypeDef,
+        "AuditImagesLimit": int,
+    },
+    total=False,
+)
+
 UpdateDatasetEntriesRequestRequestTypeDef = TypedDict(
     "UpdateDatasetEntriesRequestRequestTypeDef",
     {
         "DatasetArn": str,
         "Changes": DatasetChangesTypeDef,
     },
 )
@@ -1760,142 +2361,21 @@
         "CreationTimestamp": datetime,
         "Status": ProjectStatusType,
         "Datasets": List[DatasetMetadataTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    {
-        "ProjectArn": str,
-    },
-)
-_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef",
-    {
-        "VersionNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef(
-    _RequiredDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-    _OptionalDescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-):
-    pass
-
-DescribeProjectsRequestDescribeProjectsPaginateTypeDef = TypedDict(
-    "DescribeProjectsRequestDescribeProjectsPaginateTypeDef",
-    {
-        "ProjectNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCollectionsRequestListCollectionsPaginateTypeDef = TypedDict(
-    "ListCollectionsRequestListCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "DatasetArn": str,
-    },
-)
-_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef",
-    {
-        "ContainsLabels": Sequence[str],
-        "Labeled": bool,
-        "SourceRefContains": str,
-        "HasErrors": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef(
-    _RequiredListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    _OptionalListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-):
-    pass
-
-_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    {
-        "DatasetArn": str,
-    },
-)
-_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef(
-    _RequiredListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-    _OptionalListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-):
-    pass
-
-_RequiredListFacesRequestListFacesPaginateTypeDef = TypedDict(
-    "_RequiredListFacesRequestListFacesPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListFacesRequestListFacesPaginateTypeDef = TypedDict(
-    "_OptionalListFacesRequestListFacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFacesRequestListFacesPaginateTypeDef(
-    _RequiredListFacesRequestListFacesPaginateTypeDef,
-    _OptionalListFacesRequestListFacesPaginateTypeDef,
-):
-    pass
-
-_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    {
-        "ProjectArn": str,
-    },
-)
-_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef(
-    _RequiredListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-    _OptionalListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-):
-    pass
-
-ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef = TypedDict(
-    "ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef",
+DeleteFacesResponseTypeDef = TypedDict(
+    "DeleteFacesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "DeletedFaces": List[str],
+        "UnsuccessfulFaceDeletions": List[UnsuccessfulFaceDeletionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef = TypedDict(
     "_RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef",
     {
         "ProjectArn": str,
     },
@@ -1907,20 +2387,22 @@
         "NextToken": str,
         "MaxResults": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef(
     _RequiredDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
     _OptionalDescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef",
     {
         "ProjectArn": str,
     },
 )
 _OptionalDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef = TypedDict(
@@ -1930,20 +2412,22 @@
         "NextToken": str,
         "MaxResults": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef(
     _RequiredDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
     _OptionalDescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
 ):
     pass
 
+
 DetectLabelsImageBackgroundTypeDef = TypedDict(
     "DetectLabelsImageBackgroundTypeDef",
     {
         "Quality": DetectLabelsImageQualityTypeDef,
         "DominantColors": List[DominantColorTypeDef],
     },
     total=False,
@@ -1987,15 +2471,25 @@
 
 DetectModerationLabelsResponseTypeDef = TypedDict(
     "DetectModerationLabelsResponseTypeDef",
     {
         "ModerationLabels": List[ModerationLabelTypeDef],
         "ModerationModelVersion": str,
         "HumanLoopActivationOutput": HumanLoopActivationOutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateFacesResponseTypeDef = TypedDict(
+    "DisassociateFacesResponseTypeDef",
+    {
+        "DisassociatedFaces": List[DisassociatedFaceTypeDef],
+        "UnsuccessfulFaceDisassociations": List[UnsuccessfulFaceDisassociationTypeDef],
+        "UserStatus": UserStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DistributeDatasetEntriesRequestRequestTypeDef = TypedDict(
     "DistributeDatasetEntriesRequestRequestTypeDef",
     {
         "Datasets": Sequence[DistributeDatasetTypeDef],
@@ -2016,14 +2510,16 @@
         "EyesOpen": EyeOpenTypeDef,
         "MouthOpen": MouthOpenTypeDef,
         "Emotions": List[EmotionTypeDef],
         "Landmarks": List[LandmarkTypeDef],
         "Pose": PoseTypeDef,
         "Quality": ImageQualityTypeDef,
         "Confidence": float,
+        "FaceOccluded": FaceOccludedTypeDef,
+        "EyeDirection": EyeDirectionTypeDef,
     },
     total=False,
 )
 
 StreamProcessorSettingsTypeDef = TypedDict(
     "StreamProcessorSettingsTypeDef",
     {
@@ -2047,47 +2543,14 @@
     {
         "BoundingBox": BoundingBoxTypeDef,
         "Polygon": Sequence[PointTypeDef],
     },
     total=False,
 )
 
-GroundTruthManifestTypeDef = TypedDict(
-    "GroundTruthManifestTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-ImageTypeDef = TypedDict(
-    "ImageTypeDef",
-    {
-        "Bytes": Union[str, bytes, IO[Any], StreamingBody],
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-SummaryTypeDef = TypedDict(
-    "SummaryTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
-VideoTypeDef = TypedDict(
-    "VideoTypeDef",
-    {
-        "S3Object": S3ObjectTypeDef,
-    },
-    total=False,
-)
-
 _RequiredHumanLoopConfigTypeDef = TypedDict(
     "_RequiredHumanLoopConfigTypeDef",
     {
         "HumanLoopName": str,
         "FlowDefinitionArn": str,
     },
 )
@@ -2095,17 +2558,19 @@
     "_OptionalHumanLoopConfigTypeDef",
     {
         "DataAttributes": HumanLoopDataAttributesTypeDef,
     },
     total=False,
 )
 
+
 class HumanLoopConfigTypeDef(_RequiredHumanLoopConfigTypeDef, _OptionalHumanLoopConfigTypeDef):
     pass
 
+
 StreamProcessingStartSelectorTypeDef = TypedDict(
     "StreamProcessingStartSelectorTypeDef",
     {
         "KVSStreamStartSelector": KinesisVideoStreamStartSelectorTypeDef,
     },
     total=False,
 )
@@ -2119,25 +2584,43 @@
 )
 
 ListProjectPoliciesResponseTypeDef = TypedDict(
     "ListProjectPoliciesResponseTypeDef",
     {
         "ProjectPolicies": List[ProjectPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamProcessorsResponseTypeDef = TypedDict(
     "ListStreamProcessorsResponseTypeDef",
     {
         "NextToken": str,
         "StreamProcessors": List[StreamProcessorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListUsersResponseTypeDef = TypedDict(
+    "ListUsersResponseTypeDef",
+    {
+        "Users": List[UserTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UserMatchTypeDef = TypedDict(
+    "UserMatchTypeDef",
+    {
+        "Similarity": float,
+        "User": MatchedUserTypeDef,
     },
+    total=False,
 )
 
 StreamProcessorOutputTypeDef = TypedDict(
     "StreamProcessorOutputTypeDef",
     {
         "KinesisDataStream": KinesisDataStreamTypeDef,
         "S3Destination": S3DestinationTypeDef,
@@ -2160,23 +2643,14 @@
         "StartFrameNumber": int,
         "EndFrameNumber": int,
         "DurationFrames": int,
     },
     total=False,
 )
 
-StartSegmentDetectionFiltersTypeDef = TypedDict(
-    "StartSegmentDetectionFiltersTypeDef",
-    {
-        "TechnicalCueFilter": StartTechnicalCueDetectionFilterTypeDef,
-        "ShotFilter": StartShotDetectionFilterTypeDef,
-    },
-    total=False,
-)
-
 FaceMatchTypeDef = TypedDict(
     "FaceMatchTypeDef",
     {
         "Similarity": float,
         "Face": FaceTypeDef,
     },
     total=False,
@@ -2184,237 +2658,30 @@
 
 ListFacesResponseTypeDef = TypedDict(
     "ListFacesResponseTypeDef",
     {
         "Faces": List[FaceTypeDef],
         "NextToken": str,
         "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CelebrityTypeDef = TypedDict(
-    "CelebrityTypeDef",
-    {
-        "Urls": List[str],
-        "Name": str,
-        "Id": str,
-        "Face": ComparedFaceTypeDef,
-        "MatchConfidence": float,
-        "KnownGender": KnownGenderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CompareFacesMatchTypeDef = TypedDict(
-    "CompareFacesMatchTypeDef",
+GetFaceLivenessSessionResultsResponseTypeDef = TypedDict(
+    "GetFaceLivenessSessionResultsResponseTypeDef",
     {
-        "Similarity": float,
-        "Face": ComparedFaceTypeDef,
-    },
-    total=False,
-)
-
-GetContentModerationResponseTypeDef = TypedDict(
-    "GetContentModerationResponseTypeDef",
-    {
-        "JobStatus": VideoJobStatusType,
-        "StatusMessage": str,
-        "VideoMetadata": VideoMetadataTypeDef,
-        "ModerationLabels": List[ContentModerationDetectionTypeDef],
-        "NextToken": str,
-        "ModerationModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProtectiveEquipmentBodyPartTypeDef = TypedDict(
-    "ProtectiveEquipmentBodyPartTypeDef",
-    {
-        "Name": BodyPartType,
-        "Confidence": float,
-        "EquipmentDetections": List[EquipmentDetectionTypeDef],
-    },
-    total=False,
-)
-
-DescribeDatasetResponseTypeDef = TypedDict(
-    "DescribeDatasetResponseTypeDef",
-    {
-        "DatasetDescription": DatasetDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatasetLabelsResponseTypeDef = TypedDict(
-    "ListDatasetLabelsResponseTypeDef",
-    {
-        "DatasetLabelDescriptions": List[DatasetLabelDescriptionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProjectsResponseTypeDef = TypedDict(
-    "DescribeProjectsResponseTypeDef",
-    {
-        "ProjectDescriptions": List[ProjectDescriptionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetectLabelsImagePropertiesTypeDef = TypedDict(
-    "DetectLabelsImagePropertiesTypeDef",
-    {
-        "Quality": DetectLabelsImageQualityTypeDef,
-        "DominantColors": List[DominantColorTypeDef],
-        "Foreground": DetectLabelsImageForegroundTypeDef,
-        "Background": DetectLabelsImageBackgroundTypeDef,
-    },
-    total=False,
-)
-
-LabelTypeDef = TypedDict(
-    "LabelTypeDef",
-    {
-        "Name": str,
-        "Confidence": float,
-        "Instances": List[InstanceTypeDef],
-        "Parents": List[ParentTypeDef],
-        "Aliases": List[LabelAliasTypeDef],
-        "Categories": List[LabelCategoryTypeDef],
-    },
-    total=False,
-)
-
-CelebrityDetailTypeDef = TypedDict(
-    "CelebrityDetailTypeDef",
-    {
-        "Urls": List[str],
-        "Name": str,
-        "Id": str,
-        "Confidence": float,
-        "BoundingBox": BoundingBoxTypeDef,
-        "Face": FaceDetailTypeDef,
-        "KnownGender": KnownGenderTypeDef,
-    },
-    total=False,
-)
-
-DetectFacesResponseTypeDef = TypedDict(
-    "DetectFacesResponseTypeDef",
-    {
-        "FaceDetails": List[FaceDetailTypeDef],
-        "OrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-FaceDetectionTypeDef = TypedDict(
-    "FaceDetectionTypeDef",
-    {
-        "Timestamp": int,
-        "Face": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-FaceRecordTypeDef = TypedDict(
-    "FaceRecordTypeDef",
-    {
-        "Face": FaceTypeDef,
-        "FaceDetail": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-PersonDetailTypeDef = TypedDict(
-    "PersonDetailTypeDef",
-    {
-        "Index": int,
-        "BoundingBox": BoundingBoxTypeDef,
-        "Face": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-UnindexedFaceTypeDef = TypedDict(
-    "UnindexedFaceTypeDef",
-    {
-        "Reasons": List[ReasonType],
-        "FaceDetail": FaceDetailTypeDef,
-    },
-    total=False,
-)
-
-CustomLabelTypeDef = TypedDict(
-    "CustomLabelTypeDef",
-    {
-        "Name": str,
-        "Confidence": float,
-        "Geometry": GeometryTypeDef,
-    },
-    total=False,
-)
-
-TextDetectionTypeDef = TypedDict(
-    "TextDetectionTypeDef",
-    {
-        "DetectedText": str,
-        "Type": TextTypesType,
-        "Id": int,
-        "ParentId": int,
+        "SessionId": str,
+        "Status": LivenessSessionStatusType,
         "Confidence": float,
-        "Geometry": GeometryTypeDef,
+        "ReferenceImage": AuditImageTypeDef,
+        "AuditImages": List[AuditImageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-DetectTextFiltersTypeDef = TypedDict(
-    "DetectTextFiltersTypeDef",
-    {
-        "WordFilter": DetectionFilterTypeDef,
-        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
-    },
-    total=False,
-)
-
-StartTextDetectionFiltersTypeDef = TypedDict(
-    "StartTextDetectionFiltersTypeDef",
-    {
-        "WordFilter": DetectionFilterTypeDef,
-        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
-    },
-    total=False,
-)
-
-_RequiredUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateStreamProcessorRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateStreamProcessorRequestRequestTypeDef",
-    {
-        "SettingsForUpdate": StreamProcessorSettingsForUpdateTypeDef,
-        "RegionsOfInterestForUpdate": Sequence[RegionOfInterestTypeDef],
-        "DataSharingPreferenceForUpdate": StreamProcessorDataSharingPreferenceTypeDef,
-        "ParametersToDelete": Sequence[StreamProcessorParameterToDeleteType],
-    },
-    total=False,
-)
-
-class UpdateStreamProcessorRequestRequestTypeDef(
-    _RequiredUpdateStreamProcessorRequestRequestTypeDef,
-    _OptionalUpdateStreamProcessorRequestRequestTypeDef,
-):
-    pass
-
 AssetTypeDef = TypedDict(
     "AssetTypeDef",
     {
         "GroundTruthManifest": GroundTruthManifestTypeDef,
     },
     total=False,
 )
@@ -2440,19 +2707,21 @@
     {
         "SimilarityThreshold": float,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
+
 class CompareFacesRequestRequestTypeDef(
     _RequiredCompareFacesRequestRequestTypeDef, _OptionalCompareFacesRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredDetectCustomLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredDetectCustomLabelsRequestRequestTypeDef",
     {
         "ProjectVersionArn": str,
         "Image": ImageTypeDef,
     },
 )
@@ -2461,60 +2730,42 @@
     {
         "MaxResults": int,
         "MinConfidence": float,
     },
     total=False,
 )
 
+
 class DetectCustomLabelsRequestRequestTypeDef(
     _RequiredDetectCustomLabelsRequestRequestTypeDef,
     _OptionalDetectCustomLabelsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDetectFacesRequestRequestTypeDef = TypedDict(
     "_RequiredDetectFacesRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 _OptionalDetectFacesRequestRequestTypeDef = TypedDict(
     "_OptionalDetectFacesRequestRequestTypeDef",
     {
         "Attributes": Sequence[AttributeType],
     },
     total=False,
 )
 
+
 class DetectFacesRequestRequestTypeDef(
     _RequiredDetectFacesRequestRequestTypeDef, _OptionalDetectFacesRequestRequestTypeDef
 ):
     pass
 
-_RequiredDetectLabelsRequestRequestTypeDef = TypedDict(
-    "_RequiredDetectLabelsRequestRequestTypeDef",
-    {
-        "Image": ImageTypeDef,
-    },
-)
-_OptionalDetectLabelsRequestRequestTypeDef = TypedDict(
-    "_OptionalDetectLabelsRequestRequestTypeDef",
-    {
-        "MaxLabels": int,
-        "MinConfidence": float,
-        "Features": Sequence[DetectLabelsFeatureNameType],
-        "Settings": DetectLabelsSettingsTypeDef,
-    },
-    total=False,
-)
-
-class DetectLabelsRequestRequestTypeDef(
-    _RequiredDetectLabelsRequestRequestTypeDef, _OptionalDetectLabelsRequestRequestTypeDef
-):
-    pass
 
 _RequiredDetectProtectiveEquipmentRequestRequestTypeDef = TypedDict(
     "_RequiredDetectProtectiveEquipmentRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
@@ -2522,20 +2773,22 @@
     "_OptionalDetectProtectiveEquipmentRequestRequestTypeDef",
     {
         "SummarizationAttributes": ProtectiveEquipmentSummarizationAttributesTypeDef,
     },
     total=False,
 )
 
+
 class DetectProtectiveEquipmentRequestRequestTypeDef(
     _RequiredDetectProtectiveEquipmentRequestRequestTypeDef,
     _OptionalDetectProtectiveEquipmentRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredIndexFacesRequestRequestTypeDef = TypedDict(
     "_RequiredIndexFacesRequestRequestTypeDef",
     {
         "CollectionId": str,
         "Image": ImageTypeDef,
     },
 )
@@ -2546,19 +2799,21 @@
         "DetectionAttributes": Sequence[AttributeType],
         "MaxFaces": int,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
+
 class IndexFacesRequestRequestTypeDef(
     _RequiredIndexFacesRequestRequestTypeDef, _OptionalIndexFacesRequestRequestTypeDef
 ):
     pass
 
+
 RecognizeCelebritiesRequestRequestTypeDef = TypedDict(
     "RecognizeCelebritiesRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 
@@ -2575,20 +2830,47 @@
         "MaxFaces": int,
         "FaceMatchThreshold": float,
         "QualityFilter": QualityFilterType,
     },
     total=False,
 )
 
+
 class SearchFacesByImageRequestRequestTypeDef(
     _RequiredSearchFacesByImageRequestRequestTypeDef,
     _OptionalSearchFacesByImageRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredSearchUsersByImageRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchUsersByImageRequestRequestTypeDef",
+    {
+        "CollectionId": str,
+        "Image": ImageTypeDef,
+    },
+)
+_OptionalSearchUsersByImageRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchUsersByImageRequestRequestTypeDef",
+    {
+        "UserMatchThreshold": float,
+        "MaxUsers": int,
+        "QualityFilter": QualityFilterType,
+    },
+    total=False,
+)
+
+
+class SearchUsersByImageRequestRequestTypeDef(
+    _RequiredSearchUsersByImageRequestRequestTypeDef,
+    _OptionalSearchUsersByImageRequestRequestTypeDef,
+):
+    pass
+
+
 EvaluationResultTypeDef = TypedDict(
     "EvaluationResultTypeDef",
     {
         "F1Score": float,
         "Summary": SummaryTypeDef,
     },
     total=False,
@@ -2606,20 +2888,22 @@
         "ClientRequestToken": str,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
+
 class StartCelebrityRecognitionRequestRequestTypeDef(
     _RequiredStartCelebrityRecognitionRequestRequestTypeDef,
     _OptionalStartCelebrityRecognitionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartContentModerationRequestRequestTypeDef = TypedDict(
     "_RequiredStartContentModerationRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartContentModerationRequestRequestTypeDef = TypedDict(
@@ -2629,20 +2913,22 @@
         "ClientRequestToken": str,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
+
 class StartContentModerationRequestRequestTypeDef(
     _RequiredStartContentModerationRequestRequestTypeDef,
     _OptionalStartContentModerationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartFaceDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartFaceDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartFaceDetectionRequestRequestTypeDef = TypedDict(
@@ -2652,20 +2938,22 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "FaceAttributes": FaceAttributesType,
         "JobTag": str,
     },
     total=False,
 )
 
+
 class StartFaceDetectionRequestRequestTypeDef(
     _RequiredStartFaceDetectionRequestRequestTypeDef,
     _OptionalStartFaceDetectionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartFaceSearchRequestRequestTypeDef = TypedDict(
     "_RequiredStartFaceSearchRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
         "CollectionId": str,
     },
 )
@@ -2676,19 +2964,187 @@
         "FaceMatchThreshold": float,
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
     },
     total=False,
 )
 
+
 class StartFaceSearchRequestRequestTypeDef(
     _RequiredStartFaceSearchRequestRequestTypeDef, _OptionalStartFaceSearchRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredStartPersonTrackingRequestRequestTypeDef = TypedDict(
+    "_RequiredStartPersonTrackingRequestRequestTypeDef",
+    {
+        "Video": VideoTypeDef,
+    },
+)
+_OptionalStartPersonTrackingRequestRequestTypeDef = TypedDict(
+    "_OptionalStartPersonTrackingRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "NotificationChannel": NotificationChannelTypeDef,
+        "JobTag": str,
+    },
+    total=False,
+)
+
+
+class StartPersonTrackingRequestRequestTypeDef(
+    _RequiredStartPersonTrackingRequestRequestTypeDef,
+    _OptionalStartPersonTrackingRequestRequestTypeDef,
+):
+    pass
+
+
+StartSegmentDetectionFiltersTypeDef = TypedDict(
+    "StartSegmentDetectionFiltersTypeDef",
+    {
+        "TechnicalCueFilter": StartTechnicalCueDetectionFilterTypeDef,
+        "ShotFilter": StartShotDetectionFilterTypeDef,
+    },
+    total=False,
+)
+
+CelebrityTypeDef = TypedDict(
+    "CelebrityTypeDef",
+    {
+        "Urls": List[str],
+        "Name": str,
+        "Id": str,
+        "Face": ComparedFaceTypeDef,
+        "MatchConfidence": float,
+        "KnownGender": KnownGenderTypeDef,
+    },
+    total=False,
+)
+
+CompareFacesMatchTypeDef = TypedDict(
+    "CompareFacesMatchTypeDef",
+    {
+        "Similarity": float,
+        "Face": ComparedFaceTypeDef,
+    },
+    total=False,
+)
+
+GetContentModerationResponseTypeDef = TypedDict(
+    "GetContentModerationResponseTypeDef",
+    {
+        "JobStatus": VideoJobStatusType,
+        "StatusMessage": str,
+        "VideoMetadata": VideoMetadataTypeDef,
+        "ModerationLabels": List[ContentModerationDetectionTypeDef],
+        "NextToken": str,
+        "ModerationModelVersion": str,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "GetRequestMetadata": GetContentModerationRequestMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ProtectiveEquipmentBodyPartTypeDef = TypedDict(
+    "ProtectiveEquipmentBodyPartTypeDef",
+    {
+        "Name": BodyPartType,
+        "Confidence": float,
+        "EquipmentDetections": List[EquipmentDetectionTypeDef],
+    },
+    total=False,
+)
+
+CreateFaceLivenessSessionRequestRequestTypeDef = TypedDict(
+    "CreateFaceLivenessSessionRequestRequestTypeDef",
+    {
+        "KmsKeyId": str,
+        "Settings": CreateFaceLivenessSessionRequestSettingsTypeDef,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+DescribeDatasetResponseTypeDef = TypedDict(
+    "DescribeDatasetResponseTypeDef",
+    {
+        "DatasetDescription": DatasetDescriptionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDatasetLabelsResponseTypeDef = TypedDict(
+    "ListDatasetLabelsResponseTypeDef",
+    {
+        "DatasetLabelDescriptions": List[DatasetLabelDescriptionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProjectsResponseTypeDef = TypedDict(
+    "DescribeProjectsResponseTypeDef",
+    {
+        "ProjectDescriptions": List[ProjectDescriptionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DetectLabelsImagePropertiesTypeDef = TypedDict(
+    "DetectLabelsImagePropertiesTypeDef",
+    {
+        "Quality": DetectLabelsImageQualityTypeDef,
+        "DominantColors": List[DominantColorTypeDef],
+        "Foreground": DetectLabelsImageForegroundTypeDef,
+        "Background": DetectLabelsImageBackgroundTypeDef,
+    },
+    total=False,
+)
+
+LabelTypeDef = TypedDict(
+    "LabelTypeDef",
+    {
+        "Name": str,
+        "Confidence": float,
+        "Instances": List[InstanceTypeDef],
+        "Parents": List[ParentTypeDef],
+        "Aliases": List[LabelAliasTypeDef],
+        "Categories": List[LabelCategoryTypeDef],
+    },
+    total=False,
+)
+
+_RequiredDetectLabelsRequestRequestTypeDef = TypedDict(
+    "_RequiredDetectLabelsRequestRequestTypeDef",
+    {
+        "Image": ImageTypeDef,
+    },
+)
+_OptionalDetectLabelsRequestRequestTypeDef = TypedDict(
+    "_OptionalDetectLabelsRequestRequestTypeDef",
+    {
+        "MaxLabels": int,
+        "MinConfidence": float,
+        "Features": Sequence[DetectLabelsFeatureNameType],
+        "Settings": DetectLabelsSettingsTypeDef,
+    },
+    total=False,
+)
+
+
+class DetectLabelsRequestRequestTypeDef(
+    _RequiredDetectLabelsRequestRequestTypeDef, _OptionalDetectLabelsRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredStartLabelDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartLabelDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartLabelDetectionRequestRequestTypeDef = TypedDict(
@@ -2700,42 +3156,165 @@
         "JobTag": str,
         "Features": Sequence[Literal["GENERAL_LABELS"]],
         "Settings": LabelDetectionSettingsTypeDef,
     },
     total=False,
 )
 
+
 class StartLabelDetectionRequestRequestTypeDef(
     _RequiredStartLabelDetectionRequestRequestTypeDef,
     _OptionalStartLabelDetectionRequestRequestTypeDef,
 ):
     pass
 
-_RequiredStartPersonTrackingRequestRequestTypeDef = TypedDict(
-    "_RequiredStartPersonTrackingRequestRequestTypeDef",
+
+CelebrityDetailTypeDef = TypedDict(
+    "CelebrityDetailTypeDef",
     {
-        "Video": VideoTypeDef,
+        "Urls": List[str],
+        "Name": str,
+        "Id": str,
+        "Confidence": float,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Face": FaceDetailTypeDef,
+        "KnownGender": KnownGenderTypeDef,
     },
+    total=False,
 )
-_OptionalStartPersonTrackingRequestRequestTypeDef = TypedDict(
-    "_OptionalStartPersonTrackingRequestRequestTypeDef",
+
+DetectFacesResponseTypeDef = TypedDict(
+    "DetectFacesResponseTypeDef",
     {
-        "ClientRequestToken": str,
-        "NotificationChannel": NotificationChannelTypeDef,
-        "JobTag": str,
+        "FaceDetails": List[FaceDetailTypeDef],
+        "OrientationCorrection": OrientationCorrectionType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FaceDetectionTypeDef = TypedDict(
+    "FaceDetectionTypeDef",
+    {
+        "Timestamp": int,
+        "Face": FaceDetailTypeDef,
     },
     total=False,
 )
 
-class StartPersonTrackingRequestRequestTypeDef(
-    _RequiredStartPersonTrackingRequestRequestTypeDef,
-    _OptionalStartPersonTrackingRequestRequestTypeDef,
+FaceRecordTypeDef = TypedDict(
+    "FaceRecordTypeDef",
+    {
+        "Face": FaceTypeDef,
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+PersonDetailTypeDef = TypedDict(
+    "PersonDetailTypeDef",
+    {
+        "Index": int,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Face": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+SearchedFaceDetailsTypeDef = TypedDict(
+    "SearchedFaceDetailsTypeDef",
+    {
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+UnindexedFaceTypeDef = TypedDict(
+    "UnindexedFaceTypeDef",
+    {
+        "Reasons": List[ReasonType],
+        "FaceDetail": FaceDetailTypeDef,
+    },
+    total=False,
+)
+
+UnsearchedFaceTypeDef = TypedDict(
+    "UnsearchedFaceTypeDef",
+    {
+        "FaceDetails": FaceDetailTypeDef,
+        "Reasons": List[UnsearchedFaceReasonType],
+    },
+    total=False,
+)
+
+CustomLabelTypeDef = TypedDict(
+    "CustomLabelTypeDef",
+    {
+        "Name": str,
+        "Confidence": float,
+        "Geometry": GeometryTypeDef,
+    },
+    total=False,
+)
+
+TextDetectionTypeDef = TypedDict(
+    "TextDetectionTypeDef",
+    {
+        "DetectedText": str,
+        "Type": TextTypesType,
+        "Id": int,
+        "ParentId": int,
+        "Confidence": float,
+        "Geometry": GeometryTypeDef,
+    },
+    total=False,
+)
+
+DetectTextFiltersTypeDef = TypedDict(
+    "DetectTextFiltersTypeDef",
+    {
+        "WordFilter": DetectionFilterTypeDef,
+        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
+    },
+    total=False,
+)
+
+StartTextDetectionFiltersTypeDef = TypedDict(
+    "StartTextDetectionFiltersTypeDef",
+    {
+        "WordFilter": DetectionFilterTypeDef,
+        "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
+    },
+    total=False,
+)
+
+_RequiredUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateStreamProcessorRequestRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalUpdateStreamProcessorRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateStreamProcessorRequestRequestTypeDef",
+    {
+        "SettingsForUpdate": StreamProcessorSettingsForUpdateTypeDef,
+        "RegionsOfInterestForUpdate": Sequence[RegionOfInterestTypeDef],
+        "DataSharingPreferenceForUpdate": StreamProcessorDataSharingPreferenceTypeDef,
+        "ParametersToDelete": Sequence[StreamProcessorParameterToDeleteType],
+    },
+    total=False,
+)
+
+
+class UpdateStreamProcessorRequestRequestTypeDef(
+    _RequiredUpdateStreamProcessorRequestRequestTypeDef,
+    _OptionalUpdateStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDetectModerationLabelsRequestRequestTypeDef = TypedDict(
     "_RequiredDetectModerationLabelsRequestRequestTypeDef",
     {
         "Image": ImageTypeDef,
     },
 )
 _OptionalDetectModerationLabelsRequestRequestTypeDef = TypedDict(
@@ -2743,20 +3322,22 @@
     {
         "MinConfidence": float,
         "HumanLoopConfig": HumanLoopConfigTypeDef,
     },
     total=False,
 )
 
+
 class DetectModerationLabelsRequestRequestTypeDef(
     _RequiredDetectModerationLabelsRequestRequestTypeDef,
     _OptionalDetectModerationLabelsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartStreamProcessorRequestRequestTypeDef = TypedDict(
     "_RequiredStartStreamProcessorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalStartStreamProcessorRequestRequestTypeDef = TypedDict(
@@ -2764,20 +3345,33 @@
     {
         "StartSelector": StreamProcessingStartSelectorTypeDef,
         "StopSelector": StreamProcessingStopSelectorTypeDef,
     },
     total=False,
 )
 
+
 class StartStreamProcessorRequestRequestTypeDef(
     _RequiredStartStreamProcessorRequestRequestTypeDef,
     _OptionalStartStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
+
+SearchUsersResponseTypeDef = TypedDict(
+    "SearchUsersResponseTypeDef",
+    {
+        "UserMatches": List[UserMatchTypeDef],
+        "FaceModelVersion": str,
+        "SearchedFace": SearchedFaceTypeDef,
+        "SearchedUser": SearchedUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateStreamProcessorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStreamProcessorRequestRequestTypeDef",
     {
         "Input": StreamProcessorInputTypeDef,
         "Output": StreamProcessorOutputTypeDef,
         "Name": str,
         "Settings": StreamProcessorSettingsTypeDef,
@@ -2792,20 +3386,22 @@
         "KmsKeyId": str,
         "RegionsOfInterest": Sequence[RegionOfInterestTypeDef],
         "DataSharingPreference": StreamProcessorDataSharingPreferenceTypeDef,
     },
     total=False,
 )
 
+
 class CreateStreamProcessorRequestRequestTypeDef(
     _RequiredCreateStreamProcessorRequestRequestTypeDef,
     _OptionalCreateStreamProcessorRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeStreamProcessorResponseTypeDef = TypedDict(
     "DescribeStreamProcessorResponseTypeDef",
     {
         "Name": str,
         "StreamProcessorArn": str,
         "Status": StreamProcessorStatusType,
         "StatusMessage": str,
@@ -2815,32 +3411,103 @@
         "Output": StreamProcessorOutputTypeDef,
         "RoleArn": str,
         "Settings": StreamProcessorSettingsTypeDef,
         "NotificationChannel": StreamProcessorNotificationChannelTypeDef,
         "KmsKeyId": str,
         "RegionsOfInterest": List[RegionOfInterestTypeDef],
         "DataSharingPreference": StreamProcessorDataSharingPreferenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentDetectionResponseTypeDef = TypedDict(
     "GetSegmentDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": List[VideoMetadataTypeDef],
         "AudioMetadata": List[AudioMetadataTypeDef],
         "NextToken": str,
         "Segments": List[SegmentDetectionTypeDef],
         "SelectedSegmentTypes": List[SegmentTypeInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchFacesByImageResponseTypeDef = TypedDict(
+    "SearchFacesByImageResponseTypeDef",
+    {
+        "SearchedFaceBoundingBox": BoundingBoxTypeDef,
+        "SearchedFaceConfidence": float,
+        "FaceMatches": List[FaceMatchTypeDef],
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchFacesResponseTypeDef = TypedDict(
+    "SearchFacesResponseTypeDef",
+    {
+        "SearchedFaceId": str,
+        "FaceMatches": List[FaceMatchTypeDef],
+        "FaceModelVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestingDataTypeDef = TypedDict(
+    "TestingDataTypeDef",
+    {
+        "Assets": Sequence[AssetTypeDef],
+        "AutoCreate": bool,
+    },
+    total=False,
+)
+
+TrainingDataTypeDef = TypedDict(
+    "TrainingDataTypeDef",
+    {
+        "Assets": Sequence[AssetTypeDef],
+    },
+    total=False,
+)
+
+ValidationDataTypeDef = TypedDict(
+    "ValidationDataTypeDef",
+    {
+        "Assets": List[AssetTypeDef],
     },
+    total=False,
 )
 
+_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetType": DatasetTypeType,
+        "ProjectArn": str,
+    },
+)
+_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetSource": DatasetSourceTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateDatasetRequestRequestTypeDef(
+    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredStartSegmentDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartSegmentDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
         "SegmentTypes": Sequence[SegmentTypeType],
     },
 )
@@ -2851,60 +3518,41 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
         "Filters": StartSegmentDetectionFiltersTypeDef,
     },
     total=False,
 )
 
+
 class StartSegmentDetectionRequestRequestTypeDef(
     _RequiredStartSegmentDetectionRequestRequestTypeDef,
     _OptionalStartSegmentDetectionRequestRequestTypeDef,
 ):
     pass
 
-SearchFacesByImageResponseTypeDef = TypedDict(
-    "SearchFacesByImageResponseTypeDef",
-    {
-        "SearchedFaceBoundingBox": BoundingBoxTypeDef,
-        "SearchedFaceConfidence": float,
-        "FaceMatches": List[FaceMatchTypeDef],
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFacesResponseTypeDef = TypedDict(
-    "SearchFacesResponseTypeDef",
-    {
-        "SearchedFaceId": str,
-        "FaceMatches": List[FaceMatchTypeDef],
-        "FaceModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 RecognizeCelebritiesResponseTypeDef = TypedDict(
     "RecognizeCelebritiesResponseTypeDef",
     {
         "CelebrityFaces": List[CelebrityTypeDef],
         "UnrecognizedFaces": List[ComparedFaceTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompareFacesResponseTypeDef = TypedDict(
     "CompareFacesResponseTypeDef",
     {
         "SourceImageFace": ComparedSourceImageFaceTypeDef,
         "FaceMatches": List[CompareFacesMatchTypeDef],
         "UnmatchedFaces": List[ComparedFaceTypeDef],
         "SourceImageOrientationCorrection": OrientationCorrectionType,
         "TargetImageOrientationCorrection": OrientationCorrectionType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProtectiveEquipmentPersonTypeDef = TypedDict(
     "ProtectiveEquipmentPersonTypeDef",
     {
         "BodyParts": List[ProtectiveEquipmentBodyPartTypeDef],
@@ -2918,15 +3566,15 @@
 DetectLabelsResponseTypeDef = TypedDict(
     "DetectLabelsResponseTypeDef",
     {
         "Labels": List[LabelTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
         "LabelModelVersion": str,
         "ImageProperties": DetectLabelsImagePropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelDetectionTypeDef = TypedDict(
     "LabelDetectionTypeDef",
     {
         "Timestamp": int,
@@ -2951,15 +3599,18 @@
     "GetFaceDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Faces": List[FaceDetectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PersonDetectionTypeDef = TypedDict(
     "PersonDetectionTypeDef",
     {
         "Timestamp": int,
@@ -2981,32 +3632,43 @@
 IndexFacesResponseTypeDef = TypedDict(
     "IndexFacesResponseTypeDef",
     {
         "FaceRecords": List[FaceRecordTypeDef],
         "OrientationCorrection": OrientationCorrectionType,
         "FaceModelVersion": str,
         "UnindexedFaces": List[UnindexedFaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchUsersByImageResponseTypeDef = TypedDict(
+    "SearchUsersByImageResponseTypeDef",
+    {
+        "UserMatches": List[UserMatchTypeDef],
+        "FaceModelVersion": str,
+        "SearchedFace": SearchedFaceDetailsTypeDef,
+        "UnsearchedFaces": List[UnsearchedFaceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectCustomLabelsResponseTypeDef = TypedDict(
     "DetectCustomLabelsResponseTypeDef",
     {
         "CustomLabels": List[CustomLabelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectTextResponseTypeDef = TypedDict(
     "DetectTextResponseTypeDef",
     {
         "TextDetections": List[TextDetectionTypeDef],
         "TextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TextDetectionResultTypeDef = TypedDict(
     "TextDetectionResultTypeDef",
     {
         "Timestamp": int,
@@ -3025,19 +3687,21 @@
     "_OptionalDetectTextRequestRequestTypeDef",
     {
         "Filters": DetectTextFiltersTypeDef,
     },
     total=False,
 )
 
+
 class DetectTextRequestRequestTypeDef(
     _RequiredDetectTextRequestRequestTypeDef, _OptionalDetectTextRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredStartTextDetectionRequestRequestTypeDef = TypedDict(
     "_RequiredStartTextDetectionRequestRequestTypeDef",
     {
         "Video": VideoTypeDef,
     },
 )
 _OptionalStartTextDetectionRequestRequestTypeDef = TypedDict(
@@ -3047,180 +3711,155 @@
         "NotificationChannel": NotificationChannelTypeDef,
         "JobTag": str,
         "Filters": StartTextDetectionFiltersTypeDef,
     },
     total=False,
 )
 
+
 class StartTextDetectionRequestRequestTypeDef(
     _RequiredStartTextDetectionRequestRequestTypeDef,
     _OptionalStartTextDetectionRequestRequestTypeDef,
 ):
     pass
 
-TestingDataTypeDef = TypedDict(
-    "TestingDataTypeDef",
+
+_RequiredCreateProjectVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateProjectVersionRequestRequestTypeDef",
     {
-        "Assets": Sequence[AssetTypeDef],
-        "AutoCreate": bool,
+        "ProjectArn": str,
+        "VersionName": str,
+        "OutputConfig": OutputConfigTypeDef,
     },
-    total=False,
 )
-
-TrainingDataTypeDef = TypedDict(
-    "TrainingDataTypeDef",
+_OptionalCreateProjectVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateProjectVersionRequestRequestTypeDef",
     {
-        "Assets": Sequence[AssetTypeDef],
+        "TrainingData": TrainingDataTypeDef,
+        "TestingData": TestingDataTypeDef,
+        "Tags": Mapping[str, str],
+        "KmsKeyId": str,
     },
     total=False,
 )
 
-ValidationDataTypeDef = TypedDict(
-    "ValidationDataTypeDef",
+
+class CreateProjectVersionRequestRequestTypeDef(
+    _RequiredCreateProjectVersionRequestRequestTypeDef,
+    _OptionalCreateProjectVersionRequestRequestTypeDef,
+):
+    pass
+
+
+TestingDataResultTypeDef = TypedDict(
+    "TestingDataResultTypeDef",
     {
-        "Assets": List[AssetTypeDef],
+        "Input": TestingDataTypeDef,
+        "Output": TestingDataTypeDef,
+        "Validation": ValidationDataTypeDef,
     },
     total=False,
 )
 
-_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDatasetRequestRequestTypeDef",
-    {
-        "DatasetType": DatasetTypeType,
-        "ProjectArn": str,
-    },
-)
-_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDatasetRequestRequestTypeDef",
+TrainingDataResultTypeDef = TypedDict(
+    "TrainingDataResultTypeDef",
     {
-        "DatasetSource": DatasetSourceTypeDef,
+        "Input": TrainingDataTypeDef,
+        "Output": TrainingDataTypeDef,
+        "Validation": ValidationDataTypeDef,
     },
     total=False,
 )
 
-class CreateDatasetRequestRequestTypeDef(
-    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
-):
-    pass
-
 DetectProtectiveEquipmentResponseTypeDef = TypedDict(
     "DetectProtectiveEquipmentResponseTypeDef",
     {
         "ProtectiveEquipmentModelVersion": str,
         "Persons": List[ProtectiveEquipmentPersonTypeDef],
         "Summary": ProtectiveEquipmentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLabelDetectionResponseTypeDef = TypedDict(
     "GetLabelDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Labels": List[LabelDetectionTypeDef],
         "LabelModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "GetRequestMetadata": GetLabelDetectionRequestMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCelebrityRecognitionResponseTypeDef = TypedDict(
     "GetCelebrityRecognitionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Celebrities": List[CelebrityRecognitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPersonTrackingResponseTypeDef = TypedDict(
     "GetPersonTrackingResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "NextToken": str,
         "Persons": List[PersonDetectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFaceSearchResponseTypeDef = TypedDict(
     "GetFaceSearchResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "NextToken": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "Persons": List[PersonMatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTextDetectionResponseTypeDef = TypedDict(
     "GetTextDetectionResponseTypeDef",
     {
         "JobStatus": VideoJobStatusType,
         "StatusMessage": str,
         "VideoMetadata": VideoMetadataTypeDef,
         "TextDetections": List[TextDetectionResultTypeDef],
         "NextToken": str,
         "TextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateProjectVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateProjectVersionRequestRequestTypeDef",
-    {
-        "ProjectArn": str,
-        "VersionName": str,
-        "OutputConfig": OutputConfigTypeDef,
-    },
-)
-_OptionalCreateProjectVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateProjectVersionRequestRequestTypeDef",
-    {
-        "TrainingData": TrainingDataTypeDef,
-        "TestingData": TestingDataTypeDef,
-        "Tags": Mapping[str, str],
-        "KmsKeyId": str,
-    },
-    total=False,
-)
-
-class CreateProjectVersionRequestRequestTypeDef(
-    _RequiredCreateProjectVersionRequestRequestTypeDef,
-    _OptionalCreateProjectVersionRequestRequestTypeDef,
-):
-    pass
-
-TestingDataResultTypeDef = TypedDict(
-    "TestingDataResultTypeDef",
-    {
-        "Input": TestingDataTypeDef,
-        "Output": TestingDataTypeDef,
-        "Validation": ValidationDataTypeDef,
-    },
-    total=False,
-)
-
-TrainingDataResultTypeDef = TypedDict(
-    "TrainingDataResultTypeDef",
-    {
-        "Input": TrainingDataTypeDef,
-        "Output": TrainingDataTypeDef,
-        "Validation": ValidationDataTypeDef,
+        "JobId": str,
+        "Video": VideoTypeDef,
+        "JobTag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ProjectVersionDescriptionTypeDef = TypedDict(
     "ProjectVersionDescriptionTypeDef",
     {
         "ProjectVersionArn": str,
         "CreationTimestamp": datetime,
@@ -3242,10 +3881,10 @@
 )
 
 DescribeProjectVersionsResponseTypeDef = TypedDict(
     "DescribeProjectVersionsResponseTypeDef",
     {
         "ProjectVersionDescriptions": List[ProjectVersionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/waiter.py` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition/waiter.pyi` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/PKG-INFO` & `types-aiobotocore-rekognition-2.5.1/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-rekognition
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Rekognition 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore rekognition type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-rekognition"></a>
 
 # types-aiobotocore-rekognition
 
 [![PyPI - types-aiobotocore-rekognition](https://img.shields.io/pypi/v/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rekognition.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rekognition)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rekognition?color=blue)](https://pypistats.org/packages/types-aiobotocore-rekognition)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Rekognition 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
+[aiobotocore.Rekognition 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html#Rekognition)
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
 [types-aiobotocore-rekognition docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rekognition/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,14 +249,15 @@
     DescribeProjectsPaginator,
     ListCollectionsPaginator,
     ListDatasetEntriesPaginator,
     ListDatasetLabelsPaginator,
     ListFacesPaginator,
     ListProjectPoliciesPaginator,
     ListStreamProcessorsPaginator,
+    ListUsersPaginator,
 )
 
 session = get_session()
 async with session.create_client("rekognition") as client:
     client: RekognitionClient
 
     # Explicit type annotations are optional here
@@ -310,14 +278,15 @@
     list_faces_paginator: ListFacesPaginator = client.get_paginator("list_faces")
     list_project_policies_paginator: ListProjectPoliciesPaginator = client.get_paginator(
         "list_project_policies"
     )
     list_stream_processors_paginator: ListStreamProcessorsPaginator = client.get_paginator(
         "list_stream_processors"
     )
+    list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
 ```
 
 <a id="waiters-annotations"></a>
 
 ### Waiters annotations
 
 `types_aiobotocore_rekognition.waiter` module contains type annotations for all
@@ -355,14 +324,15 @@
 
 ```python
 from types_aiobotocore_rekognition.literals import (
     AttributeType,
     BodyPartType,
     CelebrityRecognitionSortByType,
     ContentClassifierType,
+    ContentModerationAggregateByType,
     ContentModerationSortByType,
     DatasetStatusMessageCodeType,
     DatasetStatusType,
     DatasetTypeType,
     DescribeProjectVersionsPaginatorName,
     DescribeProjectsPaginatorName,
     DetectLabelsFeatureNameType,
@@ -377,28 +347,35 @@
     LandmarkTypeType,
     ListCollectionsPaginatorName,
     ListDatasetEntriesPaginatorName,
     ListDatasetLabelsPaginatorName,
     ListFacesPaginatorName,
     ListProjectPoliciesPaginatorName,
     ListStreamProcessorsPaginatorName,
+    ListUsersPaginatorName,
+    LivenessSessionStatusType,
     OrientationCorrectionType,
     PersonTrackingSortByType,
     ProjectStatusType,
     ProjectVersionRunningWaiterName,
     ProjectVersionStatusType,
     ProjectVersionTrainingCompletedWaiterName,
     ProtectiveEquipmentTypeType,
     QualityFilterType,
     ReasonType,
     SegmentTypeType,
     StreamProcessorParameterToDeleteType,
     StreamProcessorStatusType,
     TechnicalCueTypeType,
     TextTypesType,
+    UnsearchedFaceReasonType,
+    UnsuccessfulFaceAssociationReasonType,
+    UnsuccessfulFaceDeletionReasonType,
+    UnsuccessfulFaceDisassociationReasonType,
+    UserStatusType,
     VideoColorRangeType,
     VideoJobStatusType,
     RekognitionServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
@@ -416,257 +393,293 @@
 
 `types_aiobotocore_rekognition.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rekognition.type_defs import (
     AgeRangeTypeDef,
+    AssociateFacesRequestRequestTypeDef,
+    AssociatedFaceTypeDef,
+    UnsuccessfulFaceAssociationTypeDef,
     AudioMetadataTypeDef,
+    BoundingBoxTypeDef,
+    S3ObjectTypeDef,
     BeardTypeDef,
     BlackFrameTypeDef,
-    BoundingBoxTypeDef,
     KnownGenderTypeDef,
-    ResponseMetadataTypeDef,
     EmotionTypeDef,
     ImageQualityTypeDef,
     LandmarkTypeDef,
     PoseTypeDef,
     SmileTypeDef,
     ConnectedHomeSettingsForUpdateTypeDef,
     ConnectedHomeSettingsTypeDef,
     ModerationLabelTypeDef,
     OutputConfigTypeDef,
+    CopyProjectVersionResponseTypeDef,
     CoversBodyPartTypeDef,
     CreateCollectionRequestRequestTypeDef,
+    CreateCollectionResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    LivenessOutputConfigTypeDef,
+    CreateFaceLivenessSessionResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
+    CreateProjectVersionResponseTypeDef,
     StreamProcessorDataSharingPreferenceTypeDef,
     StreamProcessorNotificationChannelTypeDef,
+    CreateStreamProcessorResponseTypeDef,
+    CreateUserRequestRequestTypeDef,
     DatasetChangesTypeDef,
     DatasetStatsTypeDef,
     DatasetLabelStatsTypeDef,
     DatasetMetadataTypeDef,
     DeleteCollectionRequestRequestTypeDef,
+    DeleteCollectionResponseTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteFacesRequestRequestTypeDef,
+    UnsuccessfulFaceDeletionTypeDef,
     DeleteProjectPolicyRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResponseTypeDef,
     DeleteProjectVersionRequestRequestTypeDef,
+    DeleteProjectVersionResponseTypeDef,
     DeleteStreamProcessorRequestRequestTypeDef,
+    DeleteUserRequestRequestTypeDef,
     DescribeCollectionRequestRequestTypeDef,
+    DescribeCollectionResponseTypeDef,
     DescribeDatasetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeProjectVersionsRequestRequestTypeDef,
+    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
     DescribeProjectsRequestRequestTypeDef,
     DescribeStreamProcessorRequestRequestTypeDef,
     DetectLabelsImageQualityTypeDef,
     DominantColorTypeDef,
     DetectLabelsImagePropertiesSettingsTypeDef,
     GeneralLabelsSettingsTypeDef,
     HumanLoopActivationOutputTypeDef,
     ProtectiveEquipmentSummarizationAttributesTypeDef,
     ProtectiveEquipmentSummaryTypeDef,
     DetectionFilterTypeDef,
+    DisassociateFacesRequestRequestTypeDef,
+    DisassociatedFaceTypeDef,
+    UnsuccessfulFaceDisassociationTypeDef,
     DistributeDatasetTypeDef,
+    EyeDirectionTypeDef,
     EyeOpenTypeDef,
     EyeglassesTypeDef,
+    FaceOccludedTypeDef,
     GenderTypeDef,
     MouthOpenTypeDef,
     MustacheTypeDef,
     SunglassesTypeDef,
     FaceSearchSettingsTypeDef,
     PointTypeDef,
     GetCelebrityInfoRequestRequestTypeDef,
     GetCelebrityRecognitionRequestRequestTypeDef,
     VideoMetadataTypeDef,
+    GetContentModerationRequestMetadataTypeDef,
     GetContentModerationRequestRequestTypeDef,
     GetFaceDetectionRequestRequestTypeDef,
+    GetFaceLivenessSessionResultsRequestRequestTypeDef,
     GetFaceSearchRequestRequestTypeDef,
+    GetLabelDetectionRequestMetadataTypeDef,
     GetLabelDetectionRequestRequestTypeDef,
     GetPersonTrackingRequestRequestTypeDef,
     GetSegmentDetectionRequestRequestTypeDef,
     SegmentTypeInfoTypeDef,
     GetTextDetectionRequestRequestTypeDef,
-    S3ObjectTypeDef,
     HumanLoopDataAttributesTypeDef,
     KinesisDataStreamTypeDef,
     KinesisVideoStreamStartSelectorTypeDef,
     KinesisVideoStreamTypeDef,
     LabelAliasTypeDef,
     LabelCategoryTypeDef,
     ParentTypeDef,
+    ListCollectionsRequestListCollectionsPaginateTypeDef,
     ListCollectionsRequestRequestTypeDef,
+    ListCollectionsResponseTypeDef,
+    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
     ListDatasetEntriesRequestRequestTypeDef,
+    ListDatasetEntriesResponseTypeDef,
+    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
     ListDatasetLabelsRequestRequestTypeDef,
+    ListFacesRequestListFacesPaginateTypeDef,
     ListFacesRequestRequestTypeDef,
+    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
     ListProjectPoliciesRequestRequestTypeDef,
     ProjectPolicyTypeDef,
+    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
     ListStreamProcessorsRequestRequestTypeDef,
     StreamProcessorTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
+    UserTypeDef,
+    MatchedUserTypeDef,
     NotificationChannelTypeDef,
+    PaginatorConfigTypeDef,
     PutProjectPolicyRequestRequestTypeDef,
+    PutProjectPolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3DestinationTypeDef,
     SearchFacesRequestRequestTypeDef,
+    SearchUsersRequestRequestTypeDef,
+    SearchedFaceTypeDef,
+    SearchedUserTypeDef,
     ShotSegmentTypeDef,
     TechnicalCueSegmentTypeDef,
-    StartProjectVersionRequestRequestTypeDef,
-    StartShotDetectionFilterTypeDef,
-    StreamProcessingStopSelectorTypeDef,
-    StopProjectVersionRequestRequestTypeDef,
-    StopStreamProcessorRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    StartTechnicalCueDetectionFilterTypeDef,
-    ComparedSourceImageFaceTypeDef,
-    FaceTypeDef,
-    CopyProjectVersionResponseTypeDef,
-    CreateCollectionResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateProjectVersionResponseTypeDef,
-    CreateStreamProcessorResponseTypeDef,
-    DeleteCollectionResponseTypeDef,
-    DeleteFacesResponseTypeDef,
-    DeleteProjectResponseTypeDef,
-    DeleteProjectVersionResponseTypeDef,
-    DescribeCollectionResponseTypeDef,
-    GetCelebrityInfoResponseTypeDef,
-    ListCollectionsResponseTypeDef,
-    ListDatasetEntriesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutProjectPolicyResponseTypeDef,
     StartCelebrityRecognitionResponseTypeDef,
     StartContentModerationResponseTypeDef,
     StartFaceDetectionResponseTypeDef,
     StartFaceSearchResponseTypeDef,
     StartLabelDetectionResponseTypeDef,
     StartPersonTrackingResponseTypeDef,
+    StartProjectVersionRequestRequestTypeDef,
     StartProjectVersionResponseTypeDef,
+    StartShotDetectionFilterTypeDef,
     StartSegmentDetectionResponseTypeDef,
+    StreamProcessingStopSelectorTypeDef,
     StartStreamProcessorResponseTypeDef,
     StartTextDetectionResponseTypeDef,
+    StopProjectVersionRequestRequestTypeDef,
     StopProjectVersionResponseTypeDef,
+    StopStreamProcessorRequestRequestTypeDef,
+    TagResourceRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    AssociateFacesResponseTypeDef,
+    ComparedSourceImageFaceTypeDef,
+    FaceTypeDef,
+    AuditImageTypeDef,
+    GroundTruthManifestTypeDef,
+    ImageTypeDef,
+    SummaryTypeDef,
+    VideoTypeDef,
+    StartTechnicalCueDetectionFilterTypeDef,
+    GetCelebrityInfoResponseTypeDef,
     ComparedFaceTypeDef,
     StreamProcessorSettingsForUpdateTypeDef,
     ContentModerationDetectionTypeDef,
     CopyProjectVersionRequestRequestTypeDef,
     EquipmentDetectionTypeDef,
+    CreateFaceLivenessSessionRequestSettingsTypeDef,
     UpdateDatasetEntriesRequestRequestTypeDef,
     DatasetDescriptionTypeDef,
     DatasetLabelDescriptionTypeDef,
     ProjectDescriptionTypeDef,
-    DescribeProjectVersionsRequestDescribeProjectVersionsPaginateTypeDef,
-    DescribeProjectsRequestDescribeProjectsPaginateTypeDef,
-    ListCollectionsRequestListCollectionsPaginateTypeDef,
-    ListDatasetEntriesRequestListDatasetEntriesPaginateTypeDef,
-    ListDatasetLabelsRequestListDatasetLabelsPaginateTypeDef,
-    ListFacesRequestListFacesPaginateTypeDef,
-    ListProjectPoliciesRequestListProjectPoliciesPaginateTypeDef,
-    ListStreamProcessorsRequestListStreamProcessorsPaginateTypeDef,
+    DeleteFacesResponseTypeDef,
     DescribeProjectVersionsRequestProjectVersionRunningWaitTypeDef,
     DescribeProjectVersionsRequestProjectVersionTrainingCompletedWaitTypeDef,
     DetectLabelsImageBackgroundTypeDef,
     DetectLabelsImageForegroundTypeDef,
     InstanceTypeDef,
     DetectLabelsSettingsTypeDef,
     LabelDetectionSettingsTypeDef,
     DetectModerationLabelsResponseTypeDef,
+    DisassociateFacesResponseTypeDef,
     DistributeDatasetEntriesRequestRequestTypeDef,
     FaceDetailTypeDef,
     StreamProcessorSettingsTypeDef,
     GeometryTypeDef,
     RegionOfInterestTypeDef,
-    GroundTruthManifestTypeDef,
-    ImageTypeDef,
-    SummaryTypeDef,
-    VideoTypeDef,
     HumanLoopConfigTypeDef,
     StreamProcessingStartSelectorTypeDef,
     StreamProcessorInputTypeDef,
     ListProjectPoliciesResponseTypeDef,
     ListStreamProcessorsResponseTypeDef,
+    ListUsersResponseTypeDef,
+    UserMatchTypeDef,
     StreamProcessorOutputTypeDef,
     SegmentDetectionTypeDef,
-    StartSegmentDetectionFiltersTypeDef,
     FaceMatchTypeDef,
     ListFacesResponseTypeDef,
+    GetFaceLivenessSessionResultsResponseTypeDef,
+    AssetTypeDef,
+    DatasetSourceTypeDef,
+    CompareFacesRequestRequestTypeDef,
+    DetectCustomLabelsRequestRequestTypeDef,
+    DetectFacesRequestRequestTypeDef,
+    DetectProtectiveEquipmentRequestRequestTypeDef,
+    IndexFacesRequestRequestTypeDef,
+    RecognizeCelebritiesRequestRequestTypeDef,
+    SearchFacesByImageRequestRequestTypeDef,
+    SearchUsersByImageRequestRequestTypeDef,
+    EvaluationResultTypeDef,
+    StartCelebrityRecognitionRequestRequestTypeDef,
+    StartContentModerationRequestRequestTypeDef,
+    StartFaceDetectionRequestRequestTypeDef,
+    StartFaceSearchRequestRequestTypeDef,
+    StartPersonTrackingRequestRequestTypeDef,
+    StartSegmentDetectionFiltersTypeDef,
     CelebrityTypeDef,
     CompareFacesMatchTypeDef,
     GetContentModerationResponseTypeDef,
     ProtectiveEquipmentBodyPartTypeDef,
+    CreateFaceLivenessSessionRequestRequestTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetLabelsResponseTypeDef,
     DescribeProjectsResponseTypeDef,
     DetectLabelsImagePropertiesTypeDef,
     LabelTypeDef,
+    DetectLabelsRequestRequestTypeDef,
+    StartLabelDetectionRequestRequestTypeDef,
     CelebrityDetailTypeDef,
     DetectFacesResponseTypeDef,
     FaceDetectionTypeDef,
     FaceRecordTypeDef,
     PersonDetailTypeDef,
+    SearchedFaceDetailsTypeDef,
     UnindexedFaceTypeDef,
+    UnsearchedFaceTypeDef,
     CustomLabelTypeDef,
     TextDetectionTypeDef,
     DetectTextFiltersTypeDef,
     StartTextDetectionFiltersTypeDef,
     UpdateStreamProcessorRequestRequestTypeDef,
-    AssetTypeDef,
-    DatasetSourceTypeDef,
-    CompareFacesRequestRequestTypeDef,
-    DetectCustomLabelsRequestRequestTypeDef,
-    DetectFacesRequestRequestTypeDef,
-    DetectLabelsRequestRequestTypeDef,
-    DetectProtectiveEquipmentRequestRequestTypeDef,
-    IndexFacesRequestRequestTypeDef,
-    RecognizeCelebritiesRequestRequestTypeDef,
-    SearchFacesByImageRequestRequestTypeDef,
-    EvaluationResultTypeDef,
-    StartCelebrityRecognitionRequestRequestTypeDef,
-    StartContentModerationRequestRequestTypeDef,
-    StartFaceDetectionRequestRequestTypeDef,
-    StartFaceSearchRequestRequestTypeDef,
-    StartLabelDetectionRequestRequestTypeDef,
-    StartPersonTrackingRequestRequestTypeDef,
     DetectModerationLabelsRequestRequestTypeDef,
     StartStreamProcessorRequestRequestTypeDef,
+    SearchUsersResponseTypeDef,
     CreateStreamProcessorRequestRequestTypeDef,
     DescribeStreamProcessorResponseTypeDef,
     GetSegmentDetectionResponseTypeDef,
-    StartSegmentDetectionRequestRequestTypeDef,
     SearchFacesByImageResponseTypeDef,
     SearchFacesResponseTypeDef,
+    TestingDataTypeDef,
+    TrainingDataTypeDef,
+    ValidationDataTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    StartSegmentDetectionRequestRequestTypeDef,
     RecognizeCelebritiesResponseTypeDef,
     CompareFacesResponseTypeDef,
     ProtectiveEquipmentPersonTypeDef,
     DetectLabelsResponseTypeDef,
     LabelDetectionTypeDef,
     CelebrityRecognitionTypeDef,
     GetFaceDetectionResponseTypeDef,
     PersonDetectionTypeDef,
     PersonMatchTypeDef,
     IndexFacesResponseTypeDef,
+    SearchUsersByImageResponseTypeDef,
     DetectCustomLabelsResponseTypeDef,
     DetectTextResponseTypeDef,
     TextDetectionResultTypeDef,
     DetectTextRequestRequestTypeDef,
     StartTextDetectionRequestRequestTypeDef,
-    TestingDataTypeDef,
-    TrainingDataTypeDef,
-    ValidationDataTypeDef,
-    CreateDatasetRequestRequestTypeDef,
+    CreateProjectVersionRequestRequestTypeDef,
+    TestingDataResultTypeDef,
+    TrainingDataResultTypeDef,
     DetectProtectiveEquipmentResponseTypeDef,
     GetLabelDetectionResponseTypeDef,
     GetCelebrityRecognitionResponseTypeDef,
     GetPersonTrackingResponseTypeDef,
     GetFaceSearchResponseTypeDef,
     GetTextDetectionResponseTypeDef,
-    CreateProjectVersionRequestRequestTypeDef,
-    TestingDataResultTypeDef,
-    TrainingDataResultTypeDef,
     ProjectVersionDescriptionTypeDef,
     DescribeProjectVersionsResponseTypeDef,
 )
 
 
 def get_structure() -> AgeRangeTypeDef:
     return {...}
@@ -675,43 +688,43 @@
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

### Comparing `types-aiobotocore-rekognition-2.5.0.post1/types_aiobotocore_rekognition.egg-info/SOURCES.txt` & `types-aiobotocore-rekognition-2.5.1/types_aiobotocore_rekognition.egg-info/SOURCES.txt`

 * *Files identical despite different names*

