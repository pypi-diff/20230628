# Comparing `tmp/types-aiobotocore-s3control-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-s3control-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-s3control-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-s3control-2.5.1.tar", last modified: Wed Jun 28 01:44:06 2023, max compression
```

## Comparing `types-aiobotocore-s3control-2.5.0.post1.tar` & `types-aiobotocore-s3control-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.755583 types-aiobotocore-s3control-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21964 2023-03-11 12:27:15.751583 types-aiobotocore-s3control-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20385 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.755583 types-aiobotocore-s3control-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.747583 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/
--rw-r--r--   0 runner    (1001) docker     (123)      773 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      772 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    44052 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43981 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12283 2023-03-11 12:23:02.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12281 2023-03-11 12:23:02.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2349 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    63948 2023-03-11 12:23:03.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    63879 2023-03-11 12:23:02.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:01.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.751583 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21964 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:27:15.000000 types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.162205 types-aiobotocore-s3control-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23015 2023-06-28 01:44:06.162205 types-aiobotocore-s3control-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21442 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:06.162205 types-aiobotocore-s3control-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.162205 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/
+-rw-r--r--   0 runner    (1001) docker     (123)      773 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      772 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45691 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45617 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13619 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13617 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2231 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2228 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    70264 2023-06-28 01:39:49.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70187 2023-06-28 01:39:48.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:47.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:06.162205 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23015 2023-06-28 01:44:05.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:44:06.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:44:05.000000 types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/LICENSE` & `types-aiobotocore-s3control-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/PKG-INFO` & `types-aiobotocore-s3control-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3control
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3Control 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3Control 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3control"></a>
 
 # types-aiobotocore-s3control
 
 [![PyPI - types-aiobotocore-s3control](https://img.shields.io/pypi/v/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3control?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3control)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Control 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
+[aiobotocore.S3Control 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
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
 [types-aiobotocore-s3control docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,44 +298,54 @@
 
 ```python
 from types_aiobotocore_s3control.literals import (
     AsyncOperationNameType,
     BucketCannedACLType,
     BucketLocationConstraintType,
     BucketVersioningStatusType,
+    DeleteMarkerReplicationStatusType,
+    ExistingObjectReplicationStatusType,
     ExpirationStatusType,
     FormatType,
     GeneratedManifestFormatType,
     JobManifestFieldNameType,
     JobManifestFormatType,
     JobReportFormatType,
     JobReportScopeType,
     JobStatusType,
     ListAccessPointsForObjectLambdaPaginatorName,
     MFADeleteStatusType,
     MFADeleteType,
+    MetricsStatusType,
     MultiRegionAccessPointStatusType,
     NetworkOriginType,
+    ObjectLambdaAccessPointAliasStatusType,
     ObjectLambdaAllowedFeatureType,
     ObjectLambdaTransformationConfigurationActionType,
     OperationNameType,
     OutputSchemaVersionType,
+    OwnerOverrideType,
+    ReplicaModificationsStatusType,
+    ReplicationRuleStatusType,
     ReplicationStatusType,
+    ReplicationStorageClassType,
+    ReplicationTimeStatusType,
     RequestedJobStatusType,
     S3CannedAccessControlListType,
     S3ChecksumAlgorithmType,
     S3GlacierJobTierType,
     S3GranteeTypeIdentifierType,
     S3MetadataDirectiveType,
     S3ObjectLockLegalHoldStatusType,
     S3ObjectLockModeType,
     S3ObjectLockRetentionModeType,
     S3PermissionType,
     S3SSEAlgorithmType,
     S3StorageClassType,
+    SseKmsEncryptedObjectsStatusType,
     TransitionStorageClassType,
     S3ControlServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -351,60 +361,77 @@
 
 `types_aiobotocore_s3control.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3control.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
+    AccessControlTranslationTypeDef,
     VpcConfigurationTypeDef,
     ActivityMetricsTypeDef,
     AdvancedCostOptimizationMetricsTypeDef,
     AdvancedDataProtectionMetricsTypeDef,
     DetailedStatusCodesMetricsTypeDef,
     AsyncErrorDetailsTypeDef,
     DeleteMultiRegionAccessPointInputTypeDef,
     PutMultiRegionAccessPointPolicyInputTypeDef,
     AwsLambdaTransformationTypeDef,
     CloudWatchMetricsTypeDef,
-    ResponseMetadataTypeDef,
+    ObjectLambdaAccessPointAliasTypeDef,
     PublicAccessBlockConfigurationTypeDef,
+    CreateAccessPointResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketResultTypeDef,
     JobReportTypeDef,
     S3TagTypeDef,
+    CreateJobResultTypeDef,
     RegionTypeDef,
+    CreateMultiRegionAccessPointResultTypeDef,
     DeleteAccessPointForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyRequestRequestTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteBucketLifecycleConfigurationRequestRequestTypeDef,
     DeleteBucketPolicyRequestRequestTypeDef,
+    DeleteBucketReplicationRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteJobTaggingRequestRequestTypeDef,
+    DeleteMarkerReplicationTypeDef,
+    DeleteMultiRegionAccessPointResultTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     DeleteStorageLensConfigurationRequestRequestTypeDef,
     DeleteStorageLensConfigurationTaggingRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeMultiRegionAccessPointOperationRequestRequestTypeDef,
+    EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EstablishedMultiRegionAccessPointPolicyTypeDef,
     ExcludeTypeDef,
+    ExistingObjectReplicationTypeDef,
     SSEKMSEncryptionTypeDef,
     GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
+    GetAccessPointPolicyForObjectLambdaResultTypeDef,
     GetAccessPointPolicyRequestRequestTypeDef,
+    GetAccessPointPolicyResultTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetAccessPointPolicyStatusRequestRequestTypeDef,
     GetAccessPointRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
+    GetBucketPolicyResultTypeDef,
+    GetBucketReplicationRequestRequestTypeDef,
     GetBucketRequestRequestTypeDef,
+    GetBucketResultTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
+    GetBucketVersioningResultTypeDef,
     GetJobTaggingRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef,
     GetMultiRegionAccessPointRequestRequestTypeDef,
     GetMultiRegionAccessPointRoutesRequestRequestTypeDef,
     MultiRegionAccessPointRouteTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
@@ -419,131 +446,134 @@
     LambdaInvokeOperationTypeDef,
     S3InitiateRestoreObjectOperationTypeDef,
     JobTimersTypeDef,
     LifecycleExpirationTypeDef,
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
     ListAccessPointsForObjectLambdaRequestRequestTypeDef,
-    ObjectLambdaAccessPointTypeDef,
     ListAccessPointsRequestRequestTypeDef,
     ListJobsRequestRequestTypeDef,
     ListMultiRegionAccessPointsRequestRequestTypeDef,
     ListRegionalBucketsRequestRequestTypeDef,
     RegionalBucketTypeDef,
     ListStorageLensConfigurationEntryTypeDef,
     ListStorageLensConfigurationsRequestRequestTypeDef,
+    ReplicationTimeValueTypeDef,
     ProposedMultiRegionAccessPointPolicyTypeDef,
     MultiRegionAccessPointRegionalResponseTypeDef,
     RegionReportTypeDef,
+    PaginatorConfigTypeDef,
     SelectionCriteriaTypeDef,
     PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     PutAccessPointPolicyRequestRequestTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     VersioningConfigurationTypeDef,
+    PutMultiRegionAccessPointPolicyResultTypeDef,
+    ReplicaModificationsTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectOwnerTypeDef,
     S3ObjectMetadataTypeDef,
     S3GranteeTypeDef,
     S3ObjectLockLegalHoldTypeDef,
     S3RetentionTypeDef,
     SSEKMSTypeDef,
+    SseKmsEncryptedObjectsTypeDef,
     StorageLensAwsOrgTypeDef,
     UpdateJobPriorityRequestRequestTypeDef,
+    UpdateJobPriorityResultTypeDef,
     UpdateJobStatusRequestRequestTypeDef,
+    UpdateJobStatusResultTypeDef,
     AccessPointTypeDef,
     DeleteMultiRegionAccessPointRequestRequestTypeDef,
     PutMultiRegionAccessPointPolicyRequestRequestTypeDef,
     ObjectLambdaContentTransformationTypeDef,
     CreateAccessPointForObjectLambdaResultTypeDef,
-    CreateAccessPointResultTypeDef,
-    CreateBucketResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateMultiRegionAccessPointResultTypeDef,
-    DeleteMultiRegionAccessPointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccessPointPolicyForObjectLambdaResultTypeDef,
-    GetAccessPointPolicyResultTypeDef,
-    GetBucketPolicyResultTypeDef,
-    GetBucketResultTypeDef,
-    GetBucketVersioningResultTypeDef,
-    PutMultiRegionAccessPointPolicyResultTypeDef,
-    UpdateJobPriorityResultTypeDef,
-    UpdateJobStatusResultTypeDef,
+    ObjectLambdaAccessPointTypeDef,
     CreateAccessPointRequestRequestTypeDef,
     GetAccessPointForObjectLambdaResultTypeDef,
     GetAccessPointResultTypeDef,
     GetPublicAccessBlockOutputTypeDef,
     PutPublicAccessBlockRequestRequestTypeDef,
     CreateBucketRequestRequestTypeDef,
     GetBucketTaggingResultTypeDef,
     GetJobTaggingResultTypeDef,
     LifecycleRuleAndOperatorTypeDef,
     PutJobTaggingRequestRequestTypeDef,
+    ReplicationRuleAndOperatorTypeDef,
     S3SetObjectTaggingOperationTypeDef,
     TaggingTypeDef,
     CreateMultiRegionAccessPointInputTypeDef,
     GeneratedManifestEncryptionTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaResultTypeDef,
     GetAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointRoutesResultTypeDef,
     SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef,
     GetStorageLensConfigurationTaggingResultTypeDef,
     PutStorageLensConfigurationTaggingRequestRequestTypeDef,
     S3GeneratedManifestDescriptorTypeDef,
     JobManifestTypeDef,
     JobProgressSummaryTypeDef,
-    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-    ListAccessPointsForObjectLambdaResultTypeDef,
     ListRegionalBucketsResultTypeDef,
     ListStorageLensConfigurationsResultTypeDef,
+    MetricsTypeDef,
+    ReplicationTimeTypeDef,
     MultiRegionAccessPointPolicyDocumentTypeDef,
     MultiRegionAccessPointsAsyncResponseTypeDef,
     MultiRegionAccessPointReportTypeDef,
     PrefixLevelStorageMetricsTypeDef,
     PutBucketVersioningRequestRequestTypeDef,
     S3GrantTypeDef,
     S3SetObjectLegalHoldOperationTypeDef,
     S3SetObjectRetentionOperationTypeDef,
     StorageLensDataExportEncryptionTypeDef,
+    SourceSelectionCriteriaTypeDef,
     ListAccessPointsResultTypeDef,
     ObjectLambdaTransformationConfigurationTypeDef,
+    ListAccessPointsForObjectLambdaResultTypeDef,
     LifecycleRuleFilterTypeDef,
+    ReplicationRuleFilterTypeDef,
     PutBucketTaggingRequestRequestTypeDef,
     AsyncRequestParametersTypeDef,
     CreateMultiRegionAccessPointRequestRequestTypeDef,
     S3ManifestOutputLocationTypeDef,
     JobListDescriptorTypeDef,
+    DestinationTypeDef,
     GetMultiRegionAccessPointPolicyResultTypeDef,
     AsyncResponseDetailsTypeDef,
     GetMultiRegionAccessPointResultTypeDef,
     ListMultiRegionAccessPointsResultTypeDef,
     PrefixLevelTypeDef,
     S3AccessControlListTypeDef,
     S3CopyObjectOperationTypeDef,
     S3BucketDestinationTypeDef,
     ObjectLambdaConfigurationTypeDef,
     LifecycleRuleTypeDef,
     S3JobManifestGeneratorTypeDef,
     ListJobsResultTypeDef,
+    ReplicationRuleTypeDef,
     AsyncOperationTypeDef,
     BucketLevelTypeDef,
     S3AccessControlPolicyTypeDef,
     StorageLensDataExportTypeDef,
     CreateAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointConfigurationForObjectLambdaResultTypeDef,
     PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetBucketLifecycleConfigurationResultTypeDef,
     LifecycleConfigurationTypeDef,
     JobManifestGeneratorTypeDef,
+    ReplicationConfigurationTypeDef,
     DescribeMultiRegionAccessPointOperationResultTypeDef,
     AccountLevelTypeDef,
     S3SetObjectAclOperationTypeDef,
     PutBucketLifecycleConfigurationRequestRequestTypeDef,
+    GetBucketReplicationResultTypeDef,
+    PutBucketReplicationRequestRequestTypeDef,
     StorageLensConfigurationTypeDef,
     JobOperationTypeDef,
     GetStorageLensConfigurationResultTypeDef,
     PutStorageLensConfigurationRequestRequestTypeDef,
     CreateJobRequestRequestTypeDef,
     JobDescriptorTypeDef,
     DescribeJobResultTypeDef,
@@ -557,43 +587,43 @@
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/README.md` & `types-aiobotocore-s3control-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-s3control"></a>
 
 # types-aiobotocore-s3control
 
 [![PyPI - types-aiobotocore-s3control](https://img.shields.io/pypi/v/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3control?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3control)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Control 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
+[aiobotocore.S3Control 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
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
 [types-aiobotocore-s3control docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,44 +265,54 @@
 
 ```python
 from types_aiobotocore_s3control.literals import (
     AsyncOperationNameType,
     BucketCannedACLType,
     BucketLocationConstraintType,
     BucketVersioningStatusType,
+    DeleteMarkerReplicationStatusType,
+    ExistingObjectReplicationStatusType,
     ExpirationStatusType,
     FormatType,
     GeneratedManifestFormatType,
     JobManifestFieldNameType,
     JobManifestFormatType,
     JobReportFormatType,
     JobReportScopeType,
     JobStatusType,
     ListAccessPointsForObjectLambdaPaginatorName,
     MFADeleteStatusType,
     MFADeleteType,
+    MetricsStatusType,
     MultiRegionAccessPointStatusType,
     NetworkOriginType,
+    ObjectLambdaAccessPointAliasStatusType,
     ObjectLambdaAllowedFeatureType,
     ObjectLambdaTransformationConfigurationActionType,
     OperationNameType,
     OutputSchemaVersionType,
+    OwnerOverrideType,
+    ReplicaModificationsStatusType,
+    ReplicationRuleStatusType,
     ReplicationStatusType,
+    ReplicationStorageClassType,
+    ReplicationTimeStatusType,
     RequestedJobStatusType,
     S3CannedAccessControlListType,
     S3ChecksumAlgorithmType,
     S3GlacierJobTierType,
     S3GranteeTypeIdentifierType,
     S3MetadataDirectiveType,
     S3ObjectLockLegalHoldStatusType,
     S3ObjectLockModeType,
     S3ObjectLockRetentionModeType,
     S3PermissionType,
     S3SSEAlgorithmType,
     S3StorageClassType,
+    SseKmsEncryptedObjectsStatusType,
     TransitionStorageClassType,
     S3ControlServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -318,60 +328,77 @@
 
 `types_aiobotocore_s3control.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3control.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
+    AccessControlTranslationTypeDef,
     VpcConfigurationTypeDef,
     ActivityMetricsTypeDef,
     AdvancedCostOptimizationMetricsTypeDef,
     AdvancedDataProtectionMetricsTypeDef,
     DetailedStatusCodesMetricsTypeDef,
     AsyncErrorDetailsTypeDef,
     DeleteMultiRegionAccessPointInputTypeDef,
     PutMultiRegionAccessPointPolicyInputTypeDef,
     AwsLambdaTransformationTypeDef,
     CloudWatchMetricsTypeDef,
-    ResponseMetadataTypeDef,
+    ObjectLambdaAccessPointAliasTypeDef,
     PublicAccessBlockConfigurationTypeDef,
+    CreateAccessPointResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketResultTypeDef,
     JobReportTypeDef,
     S3TagTypeDef,
+    CreateJobResultTypeDef,
     RegionTypeDef,
+    CreateMultiRegionAccessPointResultTypeDef,
     DeleteAccessPointForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyRequestRequestTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteBucketLifecycleConfigurationRequestRequestTypeDef,
     DeleteBucketPolicyRequestRequestTypeDef,
+    DeleteBucketReplicationRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteJobTaggingRequestRequestTypeDef,
+    DeleteMarkerReplicationTypeDef,
+    DeleteMultiRegionAccessPointResultTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     DeleteStorageLensConfigurationRequestRequestTypeDef,
     DeleteStorageLensConfigurationTaggingRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeMultiRegionAccessPointOperationRequestRequestTypeDef,
+    EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EstablishedMultiRegionAccessPointPolicyTypeDef,
     ExcludeTypeDef,
+    ExistingObjectReplicationTypeDef,
     SSEKMSEncryptionTypeDef,
     GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
+    GetAccessPointPolicyForObjectLambdaResultTypeDef,
     GetAccessPointPolicyRequestRequestTypeDef,
+    GetAccessPointPolicyResultTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetAccessPointPolicyStatusRequestRequestTypeDef,
     GetAccessPointRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
+    GetBucketPolicyResultTypeDef,
+    GetBucketReplicationRequestRequestTypeDef,
     GetBucketRequestRequestTypeDef,
+    GetBucketResultTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
+    GetBucketVersioningResultTypeDef,
     GetJobTaggingRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef,
     GetMultiRegionAccessPointRequestRequestTypeDef,
     GetMultiRegionAccessPointRoutesRequestRequestTypeDef,
     MultiRegionAccessPointRouteTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
@@ -386,131 +413,134 @@
     LambdaInvokeOperationTypeDef,
     S3InitiateRestoreObjectOperationTypeDef,
     JobTimersTypeDef,
     LifecycleExpirationTypeDef,
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
     ListAccessPointsForObjectLambdaRequestRequestTypeDef,
-    ObjectLambdaAccessPointTypeDef,
     ListAccessPointsRequestRequestTypeDef,
     ListJobsRequestRequestTypeDef,
     ListMultiRegionAccessPointsRequestRequestTypeDef,
     ListRegionalBucketsRequestRequestTypeDef,
     RegionalBucketTypeDef,
     ListStorageLensConfigurationEntryTypeDef,
     ListStorageLensConfigurationsRequestRequestTypeDef,
+    ReplicationTimeValueTypeDef,
     ProposedMultiRegionAccessPointPolicyTypeDef,
     MultiRegionAccessPointRegionalResponseTypeDef,
     RegionReportTypeDef,
+    PaginatorConfigTypeDef,
     SelectionCriteriaTypeDef,
     PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     PutAccessPointPolicyRequestRequestTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     VersioningConfigurationTypeDef,
+    PutMultiRegionAccessPointPolicyResultTypeDef,
+    ReplicaModificationsTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectOwnerTypeDef,
     S3ObjectMetadataTypeDef,
     S3GranteeTypeDef,
     S3ObjectLockLegalHoldTypeDef,
     S3RetentionTypeDef,
     SSEKMSTypeDef,
+    SseKmsEncryptedObjectsTypeDef,
     StorageLensAwsOrgTypeDef,
     UpdateJobPriorityRequestRequestTypeDef,
+    UpdateJobPriorityResultTypeDef,
     UpdateJobStatusRequestRequestTypeDef,
+    UpdateJobStatusResultTypeDef,
     AccessPointTypeDef,
     DeleteMultiRegionAccessPointRequestRequestTypeDef,
     PutMultiRegionAccessPointPolicyRequestRequestTypeDef,
     ObjectLambdaContentTransformationTypeDef,
     CreateAccessPointForObjectLambdaResultTypeDef,
-    CreateAccessPointResultTypeDef,
-    CreateBucketResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateMultiRegionAccessPointResultTypeDef,
-    DeleteMultiRegionAccessPointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccessPointPolicyForObjectLambdaResultTypeDef,
-    GetAccessPointPolicyResultTypeDef,
-    GetBucketPolicyResultTypeDef,
-    GetBucketResultTypeDef,
-    GetBucketVersioningResultTypeDef,
-    PutMultiRegionAccessPointPolicyResultTypeDef,
-    UpdateJobPriorityResultTypeDef,
-    UpdateJobStatusResultTypeDef,
+    ObjectLambdaAccessPointTypeDef,
     CreateAccessPointRequestRequestTypeDef,
     GetAccessPointForObjectLambdaResultTypeDef,
     GetAccessPointResultTypeDef,
     GetPublicAccessBlockOutputTypeDef,
     PutPublicAccessBlockRequestRequestTypeDef,
     CreateBucketRequestRequestTypeDef,
     GetBucketTaggingResultTypeDef,
     GetJobTaggingResultTypeDef,
     LifecycleRuleAndOperatorTypeDef,
     PutJobTaggingRequestRequestTypeDef,
+    ReplicationRuleAndOperatorTypeDef,
     S3SetObjectTaggingOperationTypeDef,
     TaggingTypeDef,
     CreateMultiRegionAccessPointInputTypeDef,
     GeneratedManifestEncryptionTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaResultTypeDef,
     GetAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointRoutesResultTypeDef,
     SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef,
     GetStorageLensConfigurationTaggingResultTypeDef,
     PutStorageLensConfigurationTaggingRequestRequestTypeDef,
     S3GeneratedManifestDescriptorTypeDef,
     JobManifestTypeDef,
     JobProgressSummaryTypeDef,
-    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-    ListAccessPointsForObjectLambdaResultTypeDef,
     ListRegionalBucketsResultTypeDef,
     ListStorageLensConfigurationsResultTypeDef,
+    MetricsTypeDef,
+    ReplicationTimeTypeDef,
     MultiRegionAccessPointPolicyDocumentTypeDef,
     MultiRegionAccessPointsAsyncResponseTypeDef,
     MultiRegionAccessPointReportTypeDef,
     PrefixLevelStorageMetricsTypeDef,
     PutBucketVersioningRequestRequestTypeDef,
     S3GrantTypeDef,
     S3SetObjectLegalHoldOperationTypeDef,
     S3SetObjectRetentionOperationTypeDef,
     StorageLensDataExportEncryptionTypeDef,
+    SourceSelectionCriteriaTypeDef,
     ListAccessPointsResultTypeDef,
     ObjectLambdaTransformationConfigurationTypeDef,
+    ListAccessPointsForObjectLambdaResultTypeDef,
     LifecycleRuleFilterTypeDef,
+    ReplicationRuleFilterTypeDef,
     PutBucketTaggingRequestRequestTypeDef,
     AsyncRequestParametersTypeDef,
     CreateMultiRegionAccessPointRequestRequestTypeDef,
     S3ManifestOutputLocationTypeDef,
     JobListDescriptorTypeDef,
+    DestinationTypeDef,
     GetMultiRegionAccessPointPolicyResultTypeDef,
     AsyncResponseDetailsTypeDef,
     GetMultiRegionAccessPointResultTypeDef,
     ListMultiRegionAccessPointsResultTypeDef,
     PrefixLevelTypeDef,
     S3AccessControlListTypeDef,
     S3CopyObjectOperationTypeDef,
     S3BucketDestinationTypeDef,
     ObjectLambdaConfigurationTypeDef,
     LifecycleRuleTypeDef,
     S3JobManifestGeneratorTypeDef,
     ListJobsResultTypeDef,
+    ReplicationRuleTypeDef,
     AsyncOperationTypeDef,
     BucketLevelTypeDef,
     S3AccessControlPolicyTypeDef,
     StorageLensDataExportTypeDef,
     CreateAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointConfigurationForObjectLambdaResultTypeDef,
     PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetBucketLifecycleConfigurationResultTypeDef,
     LifecycleConfigurationTypeDef,
     JobManifestGeneratorTypeDef,
+    ReplicationConfigurationTypeDef,
     DescribeMultiRegionAccessPointOperationResultTypeDef,
     AccountLevelTypeDef,
     S3SetObjectAclOperationTypeDef,
     PutBucketLifecycleConfigurationRequestRequestTypeDef,
+    GetBucketReplicationResultTypeDef,
+    PutBucketReplicationRequestRequestTypeDef,
     StorageLensConfigurationTypeDef,
     JobOperationTypeDef,
     GetStorageLensConfigurationResultTypeDef,
     PutStorageLensConfigurationRequestRequestTypeDef,
     CreateJobRequestRequestTypeDef,
     JobDescriptorTypeDef,
     DescribeJobResultTypeDef,
@@ -524,43 +554,43 @@
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/setup.py` & `types-aiobotocore-s3control-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-s3control.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-s3control",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_s3control"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.S3Control 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.S3Control 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/"
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__init__.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__init__.pyi` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/__main__.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.S3Control 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.S3Control 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control\nOther"
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/client.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,14 +40,15 @@
     GetAccessPointPolicyForObjectLambdaResultTypeDef,
     GetAccessPointPolicyResultTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaResultTypeDef,
     GetAccessPointPolicyStatusResultTypeDef,
     GetAccessPointResultTypeDef,
     GetBucketLifecycleConfigurationResultTypeDef,
     GetBucketPolicyResultTypeDef,
+    GetBucketReplicationResultTypeDef,
     GetBucketResultTypeDef,
     GetBucketTaggingResultTypeDef,
     GetBucketVersioningResultTypeDef,
     GetJobTaggingResultTypeDef,
     GetMultiRegionAccessPointPolicyResultTypeDef,
     GetMultiRegionAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointResultTypeDef,
@@ -67,14 +68,15 @@
     ListRegionalBucketsResultTypeDef,
     ListStorageLensConfigurationsResultTypeDef,
     MultiRegionAccessPointRouteTypeDef,
     ObjectLambdaConfigurationTypeDef,
     PublicAccessBlockConfigurationTypeDef,
     PutMultiRegionAccessPointPolicyInputTypeDef,
     PutMultiRegionAccessPointPolicyResultTypeDef,
+    ReplicationConfigurationTypeDef,
     S3TagTypeDef,
     StorageLensConfigurationTypeDef,
     StorageLensTagTypeDef,
     TaggingTypeDef,
     UpdateJobPriorityResultTypeDef,
     UpdateJobStatusResultTypeDef,
     VersioningConfigurationTypeDef,
@@ -293,14 +295,24 @@
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#delete_bucket_policy)
         """
 
+    async def delete_bucket_replication(
+        self, *, AccountId: str, Bucket: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#delete_bucket_replication)
+        """
+
     async def delete_bucket_tagging(
         self, *, AccountId: str, Bucket: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_tagging)
@@ -406,17 +418,17 @@
         """
 
     async def get_access_point_for_object_lambda(
         self, *, AccountId: str, Name: str
     ) -> GetAccessPointForObjectLambdaResultTypeDef:
         """
         Returns configuration information about the specified Object Lambda Access Point
-        The following actions are related to `GetAccessPointForObjectLambda`  *
+        The following actions are related to `GetAccessPointForObjectLambda`: *
         `CreateAccessPointForObjectLambda
-        <https://docs.aws.amazon.com/AmazonS3/latest/API/API_control_CreateAccessPointForObjectLambda.htm...`.
+        <https://docs.aws.amazon.com/AmazonS3/latest/API/API_control_CreateAccessPointForObjectLambda.html>...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_for_object_lambda)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_access_point_for_object_lambda)
         """
 
     async def get_access_point_policy(
         self, *, AccountId: str, Name: str
@@ -484,14 +496,24 @@
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_bucket_policy)
         """
 
+    async def get_bucket_replication(
+        self, *, AccountId: str, Bucket: str
+    ) -> GetBucketReplicationResultTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_bucket_replication)
+        """
+
     async def get_bucket_tagging(
         self, *, AccountId: str, Bucket: str
     ) -> GetBucketTaggingResultTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_tagging)
@@ -587,16 +609,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_storage_lens_configuration_tagging)
         """
 
     async def list_access_points(
         self, *, AccountId: str, Bucket: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListAccessPointsResultTypeDef:
         """
-        Returns a list of the access points owned by the current account associated with
-        the specified bucket.
+        Returns a list of the access points that are owned by the current account that's
+        associated with the specified bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_access_points)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#list_access_points)
         """
 
     async def list_access_points_for_object_lambda(
         self, *, AccountId: str, NextToken: str = ..., MaxResults: int = ...
@@ -707,14 +729,28 @@
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#put_bucket_policy)
         """
 
+    async def put_bucket_replication(
+        self,
+        *,
+        AccountId: str,
+        Bucket: str,
+        ReplicationConfiguration: ReplicationConfigurationTypeDef
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#put_bucket_replication)
+        """
+
     async def put_bucket_tagging(
         self, *, AccountId: str, Bucket: str, Tagging: TaggingTypeDef
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_tagging)
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/client.pyi` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -40,14 +40,15 @@
     GetAccessPointPolicyForObjectLambdaResultTypeDef,
     GetAccessPointPolicyResultTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaResultTypeDef,
     GetAccessPointPolicyStatusResultTypeDef,
     GetAccessPointResultTypeDef,
     GetBucketLifecycleConfigurationResultTypeDef,
     GetBucketPolicyResultTypeDef,
+    GetBucketReplicationResultTypeDef,
     GetBucketResultTypeDef,
     GetBucketTaggingResultTypeDef,
     GetBucketVersioningResultTypeDef,
     GetJobTaggingResultTypeDef,
     GetMultiRegionAccessPointPolicyResultTypeDef,
     GetMultiRegionAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointResultTypeDef,
@@ -67,14 +68,15 @@
     ListRegionalBucketsResultTypeDef,
     ListStorageLensConfigurationsResultTypeDef,
     MultiRegionAccessPointRouteTypeDef,
     ObjectLambdaConfigurationTypeDef,
     PublicAccessBlockConfigurationTypeDef,
     PutMultiRegionAccessPointPolicyInputTypeDef,
     PutMultiRegionAccessPointPolicyResultTypeDef,
+    ReplicationConfigurationTypeDef,
     S3TagTypeDef,
     StorageLensConfigurationTypeDef,
     StorageLensTagTypeDef,
     TaggingTypeDef,
     UpdateJobPriorityResultTypeDef,
     UpdateJobStatusResultTypeDef,
     VersioningConfigurationTypeDef,
@@ -274,14 +276,23 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#delete_bucket_policy)
         """
+    async def delete_bucket_replication(
+        self, *, AccountId: str, Bucket: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#delete_bucket_replication)
+        """
     async def delete_bucket_tagging(
         self, *, AccountId: str, Bucket: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.delete_bucket_tagging)
@@ -376,17 +387,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_access_point_configuration_for_object_lambda)
         """
     async def get_access_point_for_object_lambda(
         self, *, AccountId: str, Name: str
     ) -> GetAccessPointForObjectLambdaResultTypeDef:
         """
         Returns configuration information about the specified Object Lambda Access Point
-        The following actions are related to `GetAccessPointForObjectLambda`  *
+        The following actions are related to `GetAccessPointForObjectLambda`: *
         `CreateAccessPointForObjectLambda
-        <https://docs.aws.amazon.com/AmazonS3/latest/API/API_control_CreateAccessPointForObjectLambda.htm...`.
+        <https://docs.aws.amazon.com/AmazonS3/latest/API/API_control_CreateAccessPointForObjectLambda.html>...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_access_point_for_object_lambda)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_access_point_for_object_lambda)
         """
     async def get_access_point_policy(
         self, *, AccountId: str, Name: str
     ) -> GetAccessPointPolicyResultTypeDef:
@@ -446,14 +457,23 @@
     ) -> GetBucketPolicyResultTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_bucket_policy)
         """
+    async def get_bucket_replication(
+        self, *, AccountId: str, Bucket: str
+    ) -> GetBucketReplicationResultTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_bucket_replication)
+        """
     async def get_bucket_tagging(
         self, *, AccountId: str, Bucket: str
     ) -> GetBucketTaggingResultTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_bucket_tagging)
@@ -539,16 +559,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.get_storage_lens_configuration_tagging)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#get_storage_lens_configuration_tagging)
         """
     async def list_access_points(
         self, *, AccountId: str, Bucket: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListAccessPointsResultTypeDef:
         """
-        Returns a list of the access points owned by the current account associated with
-        the specified bucket.
+        Returns a list of the access points that are owned by the current account that's
+        associated with the specified bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.list_access_points)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#list_access_points)
         """
     async def list_access_points_for_object_lambda(
         self, *, AccountId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListAccessPointsForObjectLambdaResultTypeDef:
@@ -648,14 +668,27 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#put_bucket_policy)
         """
+    async def put_bucket_replication(
+        self,
+        *,
+        AccountId: str,
+        Bucket: str,
+        ReplicationConfiguration: ReplicationConfigurationTypeDef
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        .
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/client/#put_bucket_replication)
+        """
     async def put_bucket_tagging(
         self, *, AccountId: str, Bucket: str, Tagging: TaggingTypeDef
     ) -> EmptyResponseMetadataTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Client.put_bucket_tagging)
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/literals.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/literals.py`

 * *Files 11% similar despite different names*

```diff
@@ -20,44 +20,54 @@
 
 
 __all__ = (
     "AsyncOperationNameType",
     "BucketCannedACLType",
     "BucketLocationConstraintType",
     "BucketVersioningStatusType",
+    "DeleteMarkerReplicationStatusType",
+    "ExistingObjectReplicationStatusType",
     "ExpirationStatusType",
     "FormatType",
     "GeneratedManifestFormatType",
     "JobManifestFieldNameType",
     "JobManifestFormatType",
     "JobReportFormatType",
     "JobReportScopeType",
     "JobStatusType",
     "ListAccessPointsForObjectLambdaPaginatorName",
     "MFADeleteStatusType",
     "MFADeleteType",
+    "MetricsStatusType",
     "MultiRegionAccessPointStatusType",
     "NetworkOriginType",
+    "ObjectLambdaAccessPointAliasStatusType",
     "ObjectLambdaAllowedFeatureType",
     "ObjectLambdaTransformationConfigurationActionType",
     "OperationNameType",
     "OutputSchemaVersionType",
+    "OwnerOverrideType",
+    "ReplicaModificationsStatusType",
+    "ReplicationRuleStatusType",
     "ReplicationStatusType",
+    "ReplicationStorageClassType",
+    "ReplicationTimeStatusType",
     "RequestedJobStatusType",
     "S3CannedAccessControlListType",
     "S3ChecksumAlgorithmType",
     "S3GlacierJobTierType",
     "S3GranteeTypeIdentifierType",
     "S3MetadataDirectiveType",
     "S3ObjectLockLegalHoldStatusType",
     "S3ObjectLockModeType",
     "S3ObjectLockRetentionModeType",
     "S3PermissionType",
     "S3SSEAlgorithmType",
     "S3StorageClassType",
+    "SseKmsEncryptedObjectsStatusType",
     "TransitionStorageClassType",
     "S3ControlServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -79,14 +89,16 @@
     "eu-central-1",
     "eu-west-1",
     "sa-east-1",
     "us-west-1",
     "us-west-2",
 ]
 BucketVersioningStatusType = Literal["Enabled", "Suspended"]
+DeleteMarkerReplicationStatusType = Literal["Disabled", "Enabled"]
+ExistingObjectReplicationStatusType = Literal["Disabled", "Enabled"]
 ExpirationStatusType = Literal["Disabled", "Enabled"]
 FormatType = Literal["CSV", "Parquet"]
 GeneratedManifestFormatType = Literal["S3InventoryReport_CSV_20211130"]
 JobManifestFieldNameType = Literal["Bucket", "Ignore", "Key", "VersionId"]
 JobManifestFormatType = Literal["S3BatchOperations_CSV_20180820", "S3InventoryReport_CSV_20161130"]
 JobReportFormatType = Literal["Report_CSV_20180820"]
 JobReportScopeType = Literal["AllTasks", "FailedTasksOnly"]
@@ -104,23 +116,25 @@
     "Preparing",
     "Ready",
     "Suspended",
 ]
 ListAccessPointsForObjectLambdaPaginatorName = Literal["list_access_points_for_object_lambda"]
 MFADeleteStatusType = Literal["Disabled", "Enabled"]
 MFADeleteType = Literal["Disabled", "Enabled"]
+MetricsStatusType = Literal["Disabled", "Enabled"]
 MultiRegionAccessPointStatusType = Literal[
     "CREATING",
     "DELETING",
     "INCONSISTENT_ACROSS_REGIONS",
     "PARTIALLY_CREATED",
     "PARTIALLY_DELETED",
     "READY",
 ]
 NetworkOriginType = Literal["Internet", "VPC"]
+ObjectLambdaAccessPointAliasStatusType = Literal["PROVISIONING", "READY"]
 ObjectLambdaAllowedFeatureType = Literal[
     "GetObject-PartNumber", "GetObject-Range", "HeadObject-PartNumber", "HeadObject-Range"
 ]
 ObjectLambdaTransformationConfigurationActionType = Literal[
     "GetObject", "HeadObject", "ListObjects", "ListObjectsV2"
 ]
 OperationNameType = Literal[
@@ -131,15 +145,30 @@
     "S3PutObjectCopy",
     "S3PutObjectLegalHold",
     "S3PutObjectRetention",
     "S3PutObjectTagging",
     "S3ReplicateObject",
 ]
 OutputSchemaVersionType = Literal["V_1"]
+OwnerOverrideType = Literal["Destination"]
+ReplicaModificationsStatusType = Literal["Disabled", "Enabled"]
+ReplicationRuleStatusType = Literal["Disabled", "Enabled"]
 ReplicationStatusType = Literal["COMPLETED", "FAILED", "NONE", "REPLICA"]
+ReplicationStorageClassType = Literal[
+    "DEEP_ARCHIVE",
+    "GLACIER",
+    "GLACIER_IR",
+    "INTELLIGENT_TIERING",
+    "ONEZONE_IA",
+    "OUTPOSTS",
+    "REDUCED_REDUNDANCY",
+    "STANDARD",
+    "STANDARD_IA",
+]
+ReplicationTimeStatusType = Literal["Disabled", "Enabled"]
 RequestedJobStatusType = Literal["Cancelled", "Ready"]
 S3CannedAccessControlListType = Literal[
     "authenticated-read",
     "aws-exec-read",
     "bucket-owner-full-control",
     "bucket-owner-read",
     "private",
@@ -160,14 +189,15 @@
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "STANDARD",
     "STANDARD_IA",
 ]
+SseKmsEncryptedObjectsStatusType = Literal["Disabled", "Enabled"]
 TransitionStorageClassType = Literal[
     "DEEP_ARCHIVE", "GLACIER", "INTELLIGENT_TIERING", "ONEZONE_IA", "STANDARD_IA"
 ]
 S3ControlServiceName = Literal["s3control"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -226,14 +256,15 @@
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
@@ -312,14 +343,15 @@
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
@@ -330,14 +362,15 @@
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
@@ -373,14 +406,15 @@
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
@@ -399,16 +433,19 @@
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
@@ -492,15 +529,17 @@
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/literals.pyi` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/literals.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -19,44 +19,54 @@
     from typing_extensions import Literal
 
 __all__ = (
     "AsyncOperationNameType",
     "BucketCannedACLType",
     "BucketLocationConstraintType",
     "BucketVersioningStatusType",
+    "DeleteMarkerReplicationStatusType",
+    "ExistingObjectReplicationStatusType",
     "ExpirationStatusType",
     "FormatType",
     "GeneratedManifestFormatType",
     "JobManifestFieldNameType",
     "JobManifestFormatType",
     "JobReportFormatType",
     "JobReportScopeType",
     "JobStatusType",
     "ListAccessPointsForObjectLambdaPaginatorName",
     "MFADeleteStatusType",
     "MFADeleteType",
+    "MetricsStatusType",
     "MultiRegionAccessPointStatusType",
     "NetworkOriginType",
+    "ObjectLambdaAccessPointAliasStatusType",
     "ObjectLambdaAllowedFeatureType",
     "ObjectLambdaTransformationConfigurationActionType",
     "OperationNameType",
     "OutputSchemaVersionType",
+    "OwnerOverrideType",
+    "ReplicaModificationsStatusType",
+    "ReplicationRuleStatusType",
     "ReplicationStatusType",
+    "ReplicationStorageClassType",
+    "ReplicationTimeStatusType",
     "RequestedJobStatusType",
     "S3CannedAccessControlListType",
     "S3ChecksumAlgorithmType",
     "S3GlacierJobTierType",
     "S3GranteeTypeIdentifierType",
     "S3MetadataDirectiveType",
     "S3ObjectLockLegalHoldStatusType",
     "S3ObjectLockModeType",
     "S3ObjectLockRetentionModeType",
     "S3PermissionType",
     "S3SSEAlgorithmType",
     "S3StorageClassType",
+    "SseKmsEncryptedObjectsStatusType",
     "TransitionStorageClassType",
     "S3ControlServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -77,14 +87,16 @@
     "eu-central-1",
     "eu-west-1",
     "sa-east-1",
     "us-west-1",
     "us-west-2",
 ]
 BucketVersioningStatusType = Literal["Enabled", "Suspended"]
+DeleteMarkerReplicationStatusType = Literal["Disabled", "Enabled"]
+ExistingObjectReplicationStatusType = Literal["Disabled", "Enabled"]
 ExpirationStatusType = Literal["Disabled", "Enabled"]
 FormatType = Literal["CSV", "Parquet"]
 GeneratedManifestFormatType = Literal["S3InventoryReport_CSV_20211130"]
 JobManifestFieldNameType = Literal["Bucket", "Ignore", "Key", "VersionId"]
 JobManifestFormatType = Literal["S3BatchOperations_CSV_20180820", "S3InventoryReport_CSV_20161130"]
 JobReportFormatType = Literal["Report_CSV_20180820"]
 JobReportScopeType = Literal["AllTasks", "FailedTasksOnly"]
@@ -102,23 +114,25 @@
     "Preparing",
     "Ready",
     "Suspended",
 ]
 ListAccessPointsForObjectLambdaPaginatorName = Literal["list_access_points_for_object_lambda"]
 MFADeleteStatusType = Literal["Disabled", "Enabled"]
 MFADeleteType = Literal["Disabled", "Enabled"]
+MetricsStatusType = Literal["Disabled", "Enabled"]
 MultiRegionAccessPointStatusType = Literal[
     "CREATING",
     "DELETING",
     "INCONSISTENT_ACROSS_REGIONS",
     "PARTIALLY_CREATED",
     "PARTIALLY_DELETED",
     "READY",
 ]
 NetworkOriginType = Literal["Internet", "VPC"]
+ObjectLambdaAccessPointAliasStatusType = Literal["PROVISIONING", "READY"]
 ObjectLambdaAllowedFeatureType = Literal[
     "GetObject-PartNumber", "GetObject-Range", "HeadObject-PartNumber", "HeadObject-Range"
 ]
 ObjectLambdaTransformationConfigurationActionType = Literal[
     "GetObject", "HeadObject", "ListObjects", "ListObjectsV2"
 ]
 OperationNameType = Literal[
@@ -129,15 +143,30 @@
     "S3PutObjectCopy",
     "S3PutObjectLegalHold",
     "S3PutObjectRetention",
     "S3PutObjectTagging",
     "S3ReplicateObject",
 ]
 OutputSchemaVersionType = Literal["V_1"]
+OwnerOverrideType = Literal["Destination"]
+ReplicaModificationsStatusType = Literal["Disabled", "Enabled"]
+ReplicationRuleStatusType = Literal["Disabled", "Enabled"]
 ReplicationStatusType = Literal["COMPLETED", "FAILED", "NONE", "REPLICA"]
+ReplicationStorageClassType = Literal[
+    "DEEP_ARCHIVE",
+    "GLACIER",
+    "GLACIER_IR",
+    "INTELLIGENT_TIERING",
+    "ONEZONE_IA",
+    "OUTPOSTS",
+    "REDUCED_REDUNDANCY",
+    "STANDARD",
+    "STANDARD_IA",
+]
+ReplicationTimeStatusType = Literal["Disabled", "Enabled"]
 RequestedJobStatusType = Literal["Cancelled", "Ready"]
 S3CannedAccessControlListType = Literal[
     "authenticated-read",
     "aws-exec-read",
     "bucket-owner-full-control",
     "bucket-owner-read",
     "private",
@@ -158,14 +187,15 @@
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "STANDARD",
     "STANDARD_IA",
 ]
+SseKmsEncryptedObjectsStatusType = Literal["Disabled", "Enabled"]
 TransitionStorageClassType = Literal[
     "DEEP_ARCHIVE", "GLACIER", "INTELLIGENT_TIERING", "ONEZONE_IA", "STANDARD_IA"
 ]
 S3ControlServiceName = Literal["s3control"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -224,14 +254,15 @@
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
@@ -310,14 +341,15 @@
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
@@ -328,14 +360,15 @@
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
@@ -371,14 +404,15 @@
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
@@ -397,16 +431,19 @@
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
@@ -490,15 +527,17 @@
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/paginator.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("s3control") as client:
         client: S3ControlClient
 
         list_access_points_for_object_lambda_paginator: ListAccessPointsForObjectLambdaPaginator = client.get_paginator("list_access_points_for_object_lambda")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListAccessPointsForObjectLambdaResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAccessPointsForObjectLambdaPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListAccessPointsForObjectLambdaPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Paginator.ListAccessPointsForObjectLambda)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/paginators/#listaccesspointsforobjectlambdapaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessPointsForObjectLambdaResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Paginator.ListAccessPointsForObjectLambda.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/paginators/#listaccesspointsforobjectlambdapaginator)
         """
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/paginator.pyi` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/paginator.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("s3control") as client:
         client: S3ControlClient
 
         list_access_points_for_object_lambda_paginator: ListAccessPointsForObjectLambdaPaginator = client.get_paginator("list_access_points_for_object_lambda")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListAccessPointsForObjectLambdaResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAccessPointsForObjectLambdaPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListAccessPointsForObjectLambdaPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Paginator.ListAccessPointsForObjectLambda)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/paginators/#listaccesspointsforobjectlambdapaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessPointsForObjectLambdaResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control.Paginator.ListAccessPointsForObjectLambda.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/paginators/#listaccesspointsforobjectlambdapaginator)
         """
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/type_defs.py` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,40 +16,49 @@
 from typing import Any, Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AsyncOperationNameType,
     BucketCannedACLType,
     BucketLocationConstraintType,
     BucketVersioningStatusType,
+    DeleteMarkerReplicationStatusType,
+    ExistingObjectReplicationStatusType,
     ExpirationStatusType,
     FormatType,
     JobManifestFieldNameType,
     JobManifestFormatType,
     JobReportScopeType,
     JobStatusType,
+    MetricsStatusType,
     MFADeleteStatusType,
     MFADeleteType,
     MultiRegionAccessPointStatusType,
     NetworkOriginType,
+    ObjectLambdaAccessPointAliasStatusType,
     ObjectLambdaAllowedFeatureType,
     ObjectLambdaTransformationConfigurationActionType,
     OperationNameType,
+    ReplicaModificationsStatusType,
+    ReplicationRuleStatusType,
     ReplicationStatusType,
+    ReplicationStorageClassType,
+    ReplicationTimeStatusType,
     RequestedJobStatusType,
     S3CannedAccessControlListType,
     S3ChecksumAlgorithmType,
     S3GlacierJobTierType,
     S3GranteeTypeIdentifierType,
     S3MetadataDirectiveType,
     S3ObjectLockLegalHoldStatusType,
     S3ObjectLockModeType,
     S3ObjectLockRetentionModeType,
     S3PermissionType,
     S3SSEAlgorithmType,
     S3StorageClassType,
+    SseKmsEncryptedObjectsStatusType,
     TransitionStorageClassType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -57,60 +66,77 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AbortIncompleteMultipartUploadTypeDef",
+    "AccessControlTranslationTypeDef",
     "VpcConfigurationTypeDef",
     "ActivityMetricsTypeDef",
     "AdvancedCostOptimizationMetricsTypeDef",
     "AdvancedDataProtectionMetricsTypeDef",
     "DetailedStatusCodesMetricsTypeDef",
     "AsyncErrorDetailsTypeDef",
     "DeleteMultiRegionAccessPointInputTypeDef",
     "PutMultiRegionAccessPointPolicyInputTypeDef",
     "AwsLambdaTransformationTypeDef",
     "CloudWatchMetricsTypeDef",
-    "ResponseMetadataTypeDef",
+    "ObjectLambdaAccessPointAliasTypeDef",
     "PublicAccessBlockConfigurationTypeDef",
+    "CreateAccessPointResultTypeDef",
     "CreateBucketConfigurationTypeDef",
+    "CreateBucketResultTypeDef",
     "JobReportTypeDef",
     "S3TagTypeDef",
+    "CreateJobResultTypeDef",
     "RegionTypeDef",
+    "CreateMultiRegionAccessPointResultTypeDef",
     "DeleteAccessPointForObjectLambdaRequestRequestTypeDef",
     "DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     "DeleteAccessPointPolicyRequestRequestTypeDef",
     "DeleteAccessPointRequestRequestTypeDef",
     "DeleteBucketLifecycleConfigurationRequestRequestTypeDef",
     "DeleteBucketPolicyRequestRequestTypeDef",
+    "DeleteBucketReplicationRequestRequestTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteBucketTaggingRequestRequestTypeDef",
     "DeleteJobTaggingRequestRequestTypeDef",
+    "DeleteMarkerReplicationTypeDef",
+    "DeleteMultiRegionAccessPointResultTypeDef",
     "DeletePublicAccessBlockRequestRequestTypeDef",
     "DeleteStorageLensConfigurationRequestRequestTypeDef",
     "DeleteStorageLensConfigurationTaggingRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeMultiRegionAccessPointOperationRequestRequestTypeDef",
+    "EncryptionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EstablishedMultiRegionAccessPointPolicyTypeDef",
     "ExcludeTypeDef",
+    "ExistingObjectReplicationTypeDef",
     "SSEKMSEncryptionTypeDef",
     "GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
+    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
     "GetAccessPointPolicyRequestRequestTypeDef",
+    "GetAccessPointPolicyResultTypeDef",
     "GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef",
     "PolicyStatusTypeDef",
     "GetAccessPointPolicyStatusRequestRequestTypeDef",
     "GetAccessPointRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationRequestRequestTypeDef",
     "GetBucketPolicyRequestRequestTypeDef",
+    "GetBucketPolicyResultTypeDef",
+    "GetBucketReplicationRequestRequestTypeDef",
     "GetBucketRequestRequestTypeDef",
+    "GetBucketResultTypeDef",
     "GetBucketTaggingRequestRequestTypeDef",
     "GetBucketVersioningRequestRequestTypeDef",
+    "GetBucketVersioningResultTypeDef",
     "GetJobTaggingRequestRequestTypeDef",
     "GetMultiRegionAccessPointPolicyRequestRequestTypeDef",
     "GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef",
     "GetMultiRegionAccessPointRequestRequestTypeDef",
     "GetMultiRegionAccessPointRoutesRequestRequestTypeDef",
     "MultiRegionAccessPointRouteTypeDef",
     "GetPublicAccessBlockRequestRequestTypeDef",
@@ -125,131 +151,134 @@
     "LambdaInvokeOperationTypeDef",
     "S3InitiateRestoreObjectOperationTypeDef",
     "JobTimersTypeDef",
     "LifecycleExpirationTypeDef",
     "NoncurrentVersionExpirationTypeDef",
     "NoncurrentVersionTransitionTypeDef",
     "TransitionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
     "ListAccessPointsForObjectLambdaRequestRequestTypeDef",
-    "ObjectLambdaAccessPointTypeDef",
     "ListAccessPointsRequestRequestTypeDef",
     "ListJobsRequestRequestTypeDef",
     "ListMultiRegionAccessPointsRequestRequestTypeDef",
     "ListRegionalBucketsRequestRequestTypeDef",
     "RegionalBucketTypeDef",
     "ListStorageLensConfigurationEntryTypeDef",
     "ListStorageLensConfigurationsRequestRequestTypeDef",
+    "ReplicationTimeValueTypeDef",
     "ProposedMultiRegionAccessPointPolicyTypeDef",
     "MultiRegionAccessPointRegionalResponseTypeDef",
     "RegionReportTypeDef",
+    "PaginatorConfigTypeDef",
     "SelectionCriteriaTypeDef",
     "PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     "PutAccessPointPolicyRequestRequestTypeDef",
     "PutBucketPolicyRequestRequestTypeDef",
     "VersioningConfigurationTypeDef",
+    "PutMultiRegionAccessPointPolicyResultTypeDef",
+    "ReplicaModificationsTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ObjectOwnerTypeDef",
     "S3ObjectMetadataTypeDef",
     "S3GranteeTypeDef",
     "S3ObjectLockLegalHoldTypeDef",
     "S3RetentionTypeDef",
     "SSEKMSTypeDef",
+    "SseKmsEncryptedObjectsTypeDef",
     "StorageLensAwsOrgTypeDef",
     "UpdateJobPriorityRequestRequestTypeDef",
+    "UpdateJobPriorityResultTypeDef",
     "UpdateJobStatusRequestRequestTypeDef",
+    "UpdateJobStatusResultTypeDef",
     "AccessPointTypeDef",
     "DeleteMultiRegionAccessPointRequestRequestTypeDef",
     "PutMultiRegionAccessPointPolicyRequestRequestTypeDef",
     "ObjectLambdaContentTransformationTypeDef",
     "CreateAccessPointForObjectLambdaResultTypeDef",
-    "CreateAccessPointResultTypeDef",
-    "CreateBucketResultTypeDef",
-    "CreateJobResultTypeDef",
-    "CreateMultiRegionAccessPointResultTypeDef",
-    "DeleteMultiRegionAccessPointResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
-    "GetAccessPointPolicyResultTypeDef",
-    "GetBucketPolicyResultTypeDef",
-    "GetBucketResultTypeDef",
-    "GetBucketVersioningResultTypeDef",
-    "PutMultiRegionAccessPointPolicyResultTypeDef",
-    "UpdateJobPriorityResultTypeDef",
-    "UpdateJobStatusResultTypeDef",
+    "ObjectLambdaAccessPointTypeDef",
     "CreateAccessPointRequestRequestTypeDef",
     "GetAccessPointForObjectLambdaResultTypeDef",
     "GetAccessPointResultTypeDef",
     "GetPublicAccessBlockOutputTypeDef",
     "PutPublicAccessBlockRequestRequestTypeDef",
     "CreateBucketRequestRequestTypeDef",
     "GetBucketTaggingResultTypeDef",
     "GetJobTaggingResultTypeDef",
     "LifecycleRuleAndOperatorTypeDef",
     "PutJobTaggingRequestRequestTypeDef",
+    "ReplicationRuleAndOperatorTypeDef",
     "S3SetObjectTaggingOperationTypeDef",
     "TaggingTypeDef",
     "CreateMultiRegionAccessPointInputTypeDef",
     "GeneratedManifestEncryptionTypeDef",
     "GetAccessPointPolicyStatusForObjectLambdaResultTypeDef",
     "GetAccessPointPolicyStatusResultTypeDef",
     "GetMultiRegionAccessPointPolicyStatusResultTypeDef",
     "GetMultiRegionAccessPointRoutesResultTypeDef",
     "SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef",
     "GetStorageLensConfigurationTaggingResultTypeDef",
     "PutStorageLensConfigurationTaggingRequestRequestTypeDef",
     "S3GeneratedManifestDescriptorTypeDef",
     "JobManifestTypeDef",
     "JobProgressSummaryTypeDef",
-    "ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
-    "ListAccessPointsForObjectLambdaResultTypeDef",
     "ListRegionalBucketsResultTypeDef",
     "ListStorageLensConfigurationsResultTypeDef",
+    "MetricsTypeDef",
+    "ReplicationTimeTypeDef",
     "MultiRegionAccessPointPolicyDocumentTypeDef",
     "MultiRegionAccessPointsAsyncResponseTypeDef",
     "MultiRegionAccessPointReportTypeDef",
     "PrefixLevelStorageMetricsTypeDef",
     "PutBucketVersioningRequestRequestTypeDef",
     "S3GrantTypeDef",
     "S3SetObjectLegalHoldOperationTypeDef",
     "S3SetObjectRetentionOperationTypeDef",
     "StorageLensDataExportEncryptionTypeDef",
+    "SourceSelectionCriteriaTypeDef",
     "ListAccessPointsResultTypeDef",
     "ObjectLambdaTransformationConfigurationTypeDef",
+    "ListAccessPointsForObjectLambdaResultTypeDef",
     "LifecycleRuleFilterTypeDef",
+    "ReplicationRuleFilterTypeDef",
     "PutBucketTaggingRequestRequestTypeDef",
     "AsyncRequestParametersTypeDef",
     "CreateMultiRegionAccessPointRequestRequestTypeDef",
     "S3ManifestOutputLocationTypeDef",
     "JobListDescriptorTypeDef",
+    "DestinationTypeDef",
     "GetMultiRegionAccessPointPolicyResultTypeDef",
     "AsyncResponseDetailsTypeDef",
     "GetMultiRegionAccessPointResultTypeDef",
     "ListMultiRegionAccessPointsResultTypeDef",
     "PrefixLevelTypeDef",
     "S3AccessControlListTypeDef",
     "S3CopyObjectOperationTypeDef",
     "S3BucketDestinationTypeDef",
     "ObjectLambdaConfigurationTypeDef",
     "LifecycleRuleTypeDef",
     "S3JobManifestGeneratorTypeDef",
     "ListJobsResultTypeDef",
+    "ReplicationRuleTypeDef",
     "AsyncOperationTypeDef",
     "BucketLevelTypeDef",
     "S3AccessControlPolicyTypeDef",
     "StorageLensDataExportTypeDef",
     "CreateAccessPointForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointConfigurationForObjectLambdaResultTypeDef",
     "PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationResultTypeDef",
     "LifecycleConfigurationTypeDef",
     "JobManifestGeneratorTypeDef",
+    "ReplicationConfigurationTypeDef",
     "DescribeMultiRegionAccessPointOperationResultTypeDef",
     "AccountLevelTypeDef",
     "S3SetObjectAclOperationTypeDef",
     "PutBucketLifecycleConfigurationRequestRequestTypeDef",
+    "GetBucketReplicationResultTypeDef",
+    "PutBucketReplicationRequestRequestTypeDef",
     "StorageLensConfigurationTypeDef",
     "JobOperationTypeDef",
     "GetStorageLensConfigurationResultTypeDef",
     "PutStorageLensConfigurationRequestRequestTypeDef",
     "CreateJobRequestRequestTypeDef",
     "JobDescriptorTypeDef",
     "DescribeJobResultTypeDef",
@@ -259,14 +288,21 @@
     "AbortIncompleteMultipartUploadTypeDef",
     {
         "DaysAfterInitiation": int,
     },
     total=False,
 )
 
+AccessControlTranslationTypeDef = TypedDict(
+    "AccessControlTranslationTypeDef",
+    {
+        "Owner": Literal["Destination"],
+    },
+)
+
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "VpcId": str,
     },
 )
 
@@ -352,44 +388,60 @@
 CloudWatchMetricsTypeDef = TypedDict(
     "CloudWatchMetricsTypeDef",
     {
         "IsEnabled": bool,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ObjectLambdaAccessPointAliasTypeDef = TypedDict(
+    "ObjectLambdaAccessPointAliasTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Value": str,
+        "Status": ObjectLambdaAccessPointAliasStatusType,
     },
+    total=False,
 )
 
 PublicAccessBlockConfigurationTypeDef = TypedDict(
     "PublicAccessBlockConfigurationTypeDef",
     {
         "BlockPublicAcls": bool,
         "IgnorePublicAcls": bool,
         "BlockPublicPolicy": bool,
         "RestrictPublicBuckets": bool,
     },
     total=False,
 )
 
+CreateAccessPointResultTypeDef = TypedDict(
+    "CreateAccessPointResultTypeDef",
+    {
+        "AccessPointArn": str,
+        "Alias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateBucketConfigurationTypeDef = TypedDict(
     "CreateBucketConfigurationTypeDef",
     {
         "LocationConstraint": BucketLocationConstraintType,
     },
     total=False,
 )
 
+CreateBucketResultTypeDef = TypedDict(
+    "CreateBucketResultTypeDef",
+    {
+        "Location": str,
+        "BucketArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredJobReportTypeDef = TypedDict(
     "_RequiredJobReportTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalJobReportTypeDef = TypedDict(
@@ -412,20 +464,48 @@
     "S3TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-RegionTypeDef = TypedDict(
-    "RegionTypeDef",
+CreateJobResultTypeDef = TypedDict(
+    "CreateJobResultTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredRegionTypeDef = TypedDict(
+    "_RequiredRegionTypeDef",
     {
         "Bucket": str,
     },
 )
+_OptionalRegionTypeDef = TypedDict(
+    "_OptionalRegionTypeDef",
+    {
+        "BucketAccountId": str,
+    },
+    total=False,
+)
+
+
+class RegionTypeDef(_RequiredRegionTypeDef, _OptionalRegionTypeDef):
+    pass
+
+
+CreateMultiRegionAccessPointResultTypeDef = TypedDict(
+    "CreateMultiRegionAccessPointResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteAccessPointForObjectLambdaRequestRequestTypeDef = TypedDict(
     "DeleteAccessPointForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
@@ -467,14 +547,22 @@
     "DeleteBucketPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+DeleteBucketReplicationRequestRequestTypeDef = TypedDict(
+    "DeleteBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+    },
+)
+
 DeleteBucketRequestRequestTypeDef = TypedDict(
     "DeleteBucketRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
@@ -491,14 +579,29 @@
     "DeleteJobTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
     },
 )
 
+DeleteMarkerReplicationTypeDef = TypedDict(
+    "DeleteMarkerReplicationTypeDef",
+    {
+        "Status": DeleteMarkerReplicationStatusType,
+    },
+)
+
+DeleteMultiRegionAccessPointResultTypeDef = TypedDict(
+    "DeleteMultiRegionAccessPointResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePublicAccessBlockRequestRequestTypeDef = TypedDict(
     "DeletePublicAccessBlockRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 
@@ -530,14 +633,29 @@
     "DescribeMultiRegionAccessPointOperationRequestRequestTypeDef",
     {
         "AccountId": str,
         "RequestTokenARN": str,
     },
 )
 
+EncryptionConfigurationTypeDef = TypedDict(
+    "EncryptionConfigurationTypeDef",
+    {
+        "ReplicaKmsKeyID": str,
+    },
+    total=False,
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EstablishedMultiRegionAccessPointPolicyTypeDef = TypedDict(
     "EstablishedMultiRegionAccessPointPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -547,14 +665,21 @@
     {
         "Buckets": List[str],
         "Regions": List[str],
     },
     total=False,
 )
 
+ExistingObjectReplicationTypeDef = TypedDict(
+    "ExistingObjectReplicationTypeDef",
+    {
+        "Status": ExistingObjectReplicationStatusType,
+    },
+)
+
 SSEKMSEncryptionTypeDef = TypedDict(
     "SSEKMSEncryptionTypeDef",
     {
         "KeyId": str,
     },
 )
 
@@ -578,22 +703,38 @@
     "GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
 
+GetAccessPointPolicyForObjectLambdaResultTypeDef = TypedDict(
+    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessPointPolicyRequestRequestTypeDef = TypedDict(
     "GetAccessPointPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
 
+GetAccessPointPolicyResultTypeDef = TypedDict(
+    "GetAccessPointPolicyResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef = TypedDict(
     "GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
@@ -634,22 +775,48 @@
     "GetBucketPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketPolicyResultTypeDef = TypedDict(
+    "GetBucketPolicyResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetBucketReplicationRequestRequestTypeDef = TypedDict(
+    "GetBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+    },
+)
+
 GetBucketRequestRequestTypeDef = TypedDict(
     "GetBucketRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketResultTypeDef = TypedDict(
+    "GetBucketResultTypeDef",
+    {
+        "Bucket": str,
+        "PublicAccessBlockEnabled": bool,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBucketTaggingRequestRequestTypeDef = TypedDict(
     "GetBucketTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
@@ -658,14 +825,23 @@
     "GetBucketVersioningRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketVersioningResultTypeDef = TypedDict(
+    "GetBucketVersioningResultTypeDef",
+    {
+        "Status": BucketVersioningStatusType,
+        "MFADelete": MFADeleteStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobTaggingRequestRequestTypeDef = TypedDict(
     "GetJobTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
     },
 )
@@ -884,24 +1060,36 @@
         "Date": datetime,
         "Days": int,
         "StorageClass": TransitionStorageClassType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
+    "_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AccountId": str,
+    },
+)
+_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
+    "_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef(
+    _RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
+    _OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListAccessPointsForObjectLambdaRequestRequestTypeDef = TypedDict(
@@ -917,35 +1105,14 @@
 class ListAccessPointsForObjectLambdaRequestRequestTypeDef(
     _RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef,
     _OptionalListAccessPointsForObjectLambdaRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredObjectLambdaAccessPointTypeDef = TypedDict(
-    "_RequiredObjectLambdaAccessPointTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalObjectLambdaAccessPointTypeDef = TypedDict(
-    "_OptionalObjectLambdaAccessPointTypeDef",
-    {
-        "ObjectLambdaAccessPointArn": str,
-    },
-    total=False,
-)
-
-
-class ObjectLambdaAccessPointTypeDef(
-    _RequiredObjectLambdaAccessPointTypeDef, _OptionalObjectLambdaAccessPointTypeDef
-):
-    pass
-
-
 _RequiredListAccessPointsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessPointsRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListAccessPointsRequestRequestTypeDef = TypedDict(
@@ -1099,14 +1266,22 @@
 class ListStorageLensConfigurationsRequestRequestTypeDef(
     _RequiredListStorageLensConfigurationsRequestRequestTypeDef,
     _OptionalListStorageLensConfigurationsRequestRequestTypeDef,
 ):
     pass
 
 
+ReplicationTimeValueTypeDef = TypedDict(
+    "ReplicationTimeValueTypeDef",
+    {
+        "Minutes": int,
+    },
+    total=False,
+)
+
 ProposedMultiRegionAccessPointPolicyTypeDef = TypedDict(
     "ProposedMultiRegionAccessPointPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -1121,14 +1296,25 @@
 )
 
 RegionReportTypeDef = TypedDict(
     "RegionReportTypeDef",
     {
         "Bucket": str,
         "Region": str,
+        "BucketAccountId": str,
+    },
+    total=False,
+)
+
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
     total=False,
 )
 
 SelectionCriteriaTypeDef = TypedDict(
     "SelectionCriteriaTypeDef",
     {
@@ -1185,14 +1371,40 @@
     {
         "MFADelete": MFADeleteType,
         "Status": BucketVersioningStatusType,
     },
     total=False,
 )
 
+PutMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
+    "PutMultiRegionAccessPointPolicyResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ReplicaModificationsTypeDef = TypedDict(
+    "ReplicaModificationsTypeDef",
+    {
+        "Status": ReplicaModificationsStatusType,
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
 S3ObjectOwnerTypeDef = TypedDict(
     "S3ObjectOwnerTypeDef",
     {
         "ID": str,
         "DisplayName": str,
     },
     total=False,
@@ -1245,14 +1457,21 @@
 SSEKMSTypeDef = TypedDict(
     "SSEKMSTypeDef",
     {
         "KeyId": str,
     },
 )
 
+SseKmsEncryptedObjectsTypeDef = TypedDict(
+    "SseKmsEncryptedObjectsTypeDef",
+    {
+        "Status": SseKmsEncryptedObjectsStatusType,
+    },
+)
+
 StorageLensAwsOrgTypeDef = TypedDict(
     "StorageLensAwsOrgTypeDef",
     {
         "Arn": str,
     },
 )
 
@@ -1261,14 +1480,23 @@
     {
         "AccountId": str,
         "JobId": str,
         "Priority": int,
     },
 )
 
+UpdateJobPriorityResultTypeDef = TypedDict(
+    "UpdateJobPriorityResultTypeDef",
+    {
+        "JobId": str,
+        "Priority": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateJobStatusRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateJobStatusRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
         "RequestedJobStatus": RequestedJobStatusType,
     },
@@ -1284,14 +1512,24 @@
 
 class UpdateJobStatusRequestRequestTypeDef(
     _RequiredUpdateJobStatusRequestRequestTypeDef, _OptionalUpdateJobStatusRequestRequestTypeDef
 ):
     pass
 
 
+UpdateJobStatusResultTypeDef = TypedDict(
+    "UpdateJobStatusResultTypeDef",
+    {
+        "JobId": str,
+        "Status": JobStatusType,
+        "StatusUpdateReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAccessPointTypeDef = TypedDict(
     "_RequiredAccessPointTypeDef",
     {
         "Name": str,
         "NetworkOrigin": NetworkOriginType,
         "Bucket": str,
     },
@@ -1338,136 +1576,40 @@
     total=False,
 )
 
 CreateAccessPointForObjectLambdaResultTypeDef = TypedDict(
     "CreateAccessPointForObjectLambdaResultTypeDef",
     {
         "ObjectLambdaAccessPointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateAccessPointResultTypeDef = TypedDict(
-    "CreateAccessPointResultTypeDef",
-    {
-        "AccessPointArn": str,
-        "Alias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBucketResultTypeDef = TypedDict(
-    "CreateBucketResultTypeDef",
-    {
-        "Location": str,
-        "BucketArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResultTypeDef = TypedDict(
-    "CreateJobResultTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMultiRegionAccessPointResultTypeDef = TypedDict(
-    "CreateMultiRegionAccessPointResultTypeDef",
-    {
-        "RequestTokenARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMultiRegionAccessPointResultTypeDef = TypedDict(
-    "DeleteMultiRegionAccessPointResultTypeDef",
-    {
-        "RequestTokenARN": str,
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
-GetAccessPointPolicyForObjectLambdaResultTypeDef = TypedDict(
-    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessPointPolicyResultTypeDef = TypedDict(
-    "GetAccessPointPolicyResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketPolicyResultTypeDef = TypedDict(
-    "GetBucketPolicyResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketResultTypeDef = TypedDict(
-    "GetBucketResultTypeDef",
+_RequiredObjectLambdaAccessPointTypeDef = TypedDict(
+    "_RequiredObjectLambdaAccessPointTypeDef",
     {
-        "Bucket": str,
-        "PublicAccessBlockEnabled": bool,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
-
-GetBucketVersioningResultTypeDef = TypedDict(
-    "GetBucketVersioningResultTypeDef",
+_OptionalObjectLambdaAccessPointTypeDef = TypedDict(
+    "_OptionalObjectLambdaAccessPointTypeDef",
     {
-        "Status": BucketVersioningStatusType,
-        "MFADelete": MFADeleteStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ObjectLambdaAccessPointArn": str,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
     },
+    total=False,
 )
 
-PutMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
-    "PutMultiRegionAccessPointPolicyResultTypeDef",
-    {
-        "RequestTokenARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateJobPriorityResultTypeDef = TypedDict(
-    "UpdateJobPriorityResultTypeDef",
-    {
-        "JobId": str,
-        "Priority": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ObjectLambdaAccessPointTypeDef(
+    _RequiredObjectLambdaAccessPointTypeDef, _OptionalObjectLambdaAccessPointTypeDef
+):
+    pass
 
-UpdateJobStatusResultTypeDef = TypedDict(
-    "UpdateJobStatusResultTypeDef",
-    {
-        "JobId": str,
-        "Status": JobStatusType,
-        "StatusUpdateReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 _RequiredCreateAccessPointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccessPointRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
         "Bucket": str,
@@ -1492,15 +1634,16 @@
 
 GetAccessPointForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointForObjectLambdaResultTypeDef",
     {
         "Name": str,
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
         "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessPointResultTypeDef = TypedDict(
     "GetAccessPointResultTypeDef",
     {
         "Name": str,
@@ -1509,23 +1652,23 @@
         "VpcConfiguration": VpcConfigurationTypeDef,
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
         "CreationDate": datetime,
         "Alias": str,
         "AccessPointArn": str,
         "Endpoints": Dict[str, str],
         "BucketAccountId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPublicAccessBlockOutputTypeDef = TypedDict(
     "GetPublicAccessBlockOutputTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPublicAccessBlockRequestRequestTypeDef = TypedDict(
     "PutPublicAccessBlockRequestRequestTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
@@ -1562,23 +1705,23 @@
     pass
 
 
 GetBucketTaggingResultTypeDef = TypedDict(
     "GetBucketTaggingResultTypeDef",
     {
         "TagSet": List[S3TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobTaggingResultTypeDef = TypedDict(
     "GetJobTaggingResultTypeDef",
     {
         "Tags": List[S3TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleRuleAndOperatorTypeDef = TypedDict(
     "LifecycleRuleAndOperatorTypeDef",
     {
         "Prefix": str,
@@ -1594,14 +1737,23 @@
     {
         "AccountId": str,
         "JobId": str,
         "Tags": Sequence[S3TagTypeDef],
     },
 )
 
+ReplicationRuleAndOperatorTypeDef = TypedDict(
+    "ReplicationRuleAndOperatorTypeDef",
+    {
+        "Prefix": str,
+        "Tags": List[S3TagTypeDef],
+    },
+    total=False,
+)
+
 S3SetObjectTaggingOperationTypeDef = TypedDict(
     "S3SetObjectTaggingOperationTypeDef",
     {
         "TagSet": Sequence[S3TagTypeDef],
     },
     total=False,
 )
@@ -1645,40 +1797,40 @@
     total=False,
 )
 
 GetAccessPointPolicyStatusForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointPolicyStatusForObjectLambdaResultTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessPointPolicyStatusResultTypeDef = TypedDict(
     "GetAccessPointPolicyStatusResultTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMultiRegionAccessPointPolicyStatusResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointPolicyStatusResultTypeDef",
     {
         "Established": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMultiRegionAccessPointRoutesResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointRoutesResultTypeDef",
     {
         "Mrap": str,
         "Routes": List[MultiRegionAccessPointRouteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef = TypedDict(
     "SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -1687,15 +1839,15 @@
     },
 )
 
 GetStorageLensConfigurationTaggingResultTypeDef = TypedDict(
     "GetStorageLensConfigurationTaggingResultTypeDef",
     {
         "Tags": List[StorageLensTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutStorageLensConfigurationTaggingRequestRequestTypeDef = TypedDict(
     "PutStorageLensConfigurationTaggingRequestRequestTypeDef",
     {
         "ConfigId": str,
@@ -1728,60 +1880,56 @@
         "NumberOfTasksSucceeded": int,
         "NumberOfTasksFailed": int,
         "Timers": JobTimersTypeDef,
     },
     total=False,
 )
 
-_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
-    "_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+ListRegionalBucketsResultTypeDef = TypedDict(
+    "ListRegionalBucketsResultTypeDef",
     {
-        "AccountId": str,
+        "RegionalBucketList": List[RegionalBucketTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
-    "_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+
+ListStorageLensConfigurationsResultTypeDef = TypedDict(
+    "ListStorageLensConfigurationsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "StorageLensConfigurationList": List[ListStorageLensConfigurationEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef(
-    _RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-    _OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-):
-    pass
-
-
-ListAccessPointsForObjectLambdaResultTypeDef = TypedDict(
-    "ListAccessPointsForObjectLambdaResultTypeDef",
+_RequiredMetricsTypeDef = TypedDict(
+    "_RequiredMetricsTypeDef",
     {
-        "ObjectLambdaAccessPointList": List[ObjectLambdaAccessPointTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": MetricsStatusType,
     },
 )
-
-ListRegionalBucketsResultTypeDef = TypedDict(
-    "ListRegionalBucketsResultTypeDef",
+_OptionalMetricsTypeDef = TypedDict(
+    "_OptionalMetricsTypeDef",
     {
-        "RegionalBucketList": List[RegionalBucketTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EventThreshold": ReplicationTimeValueTypeDef,
     },
+    total=False,
 )
 
-ListStorageLensConfigurationsResultTypeDef = TypedDict(
-    "ListStorageLensConfigurationsResultTypeDef",
+
+class MetricsTypeDef(_RequiredMetricsTypeDef, _OptionalMetricsTypeDef):
+    pass
+
+
+ReplicationTimeTypeDef = TypedDict(
+    "ReplicationTimeTypeDef",
     {
-        "NextToken": str,
-        "StorageLensConfigurationList": List[ListStorageLensConfigurationEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ReplicationTimeStatusType,
+        "Time": ReplicationTimeValueTypeDef,
     },
 )
 
 MultiRegionAccessPointPolicyDocumentTypeDef = TypedDict(
     "MultiRegionAccessPointPolicyDocumentTypeDef",
     {
         "Established": EstablishedMultiRegionAccessPointPolicyTypeDef,
@@ -1886,43 +2034,71 @@
     {
         "SSES3": Dict[str, Any],
         "SSEKMS": SSEKMSTypeDef,
     },
     total=False,
 )
 
+SourceSelectionCriteriaTypeDef = TypedDict(
+    "SourceSelectionCriteriaTypeDef",
+    {
+        "SseKmsEncryptedObjects": SseKmsEncryptedObjectsTypeDef,
+        "ReplicaModifications": ReplicaModificationsTypeDef,
+    },
+    total=False,
+)
+
 ListAccessPointsResultTypeDef = TypedDict(
     "ListAccessPointsResultTypeDef",
     {
         "AccessPointList": List[AccessPointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ObjectLambdaTransformationConfigurationTypeDef = TypedDict(
     "ObjectLambdaTransformationConfigurationTypeDef",
     {
         "Actions": Sequence[ObjectLambdaTransformationConfigurationActionType],
         "ContentTransformation": ObjectLambdaContentTransformationTypeDef,
     },
 )
 
+ListAccessPointsForObjectLambdaResultTypeDef = TypedDict(
+    "ListAccessPointsForObjectLambdaResultTypeDef",
+    {
+        "ObjectLambdaAccessPointList": List[ObjectLambdaAccessPointTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecycleRuleFilterTypeDef = TypedDict(
     "LifecycleRuleFilterTypeDef",
     {
         "Prefix": str,
         "Tag": S3TagTypeDef,
         "And": LifecycleRuleAndOperatorTypeDef,
         "ObjectSizeGreaterThan": int,
         "ObjectSizeLessThan": int,
     },
     total=False,
 )
 
+ReplicationRuleFilterTypeDef = TypedDict(
+    "ReplicationRuleFilterTypeDef",
+    {
+        "Prefix": str,
+        "Tag": S3TagTypeDef,
+        "And": ReplicationRuleAndOperatorTypeDef,
+    },
+    total=False,
+)
+
 PutBucketTaggingRequestRequestTypeDef = TypedDict(
     "PutBucketTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
         "Tagging": TaggingTypeDef,
     },
@@ -1982,19 +2158,43 @@
         "CreationTime": datetime,
         "TerminationDate": datetime,
         "ProgressSummary": JobProgressSummaryTypeDef,
     },
     total=False,
 )
 
+_RequiredDestinationTypeDef = TypedDict(
+    "_RequiredDestinationTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalDestinationTypeDef = TypedDict(
+    "_OptionalDestinationTypeDef",
+    {
+        "Account": str,
+        "ReplicationTime": ReplicationTimeTypeDef,
+        "AccessControlTranslation": AccessControlTranslationTypeDef,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+        "Metrics": MetricsTypeDef,
+        "StorageClass": ReplicationStorageClassType,
+    },
+    total=False,
+)
+
+
+class DestinationTypeDef(_RequiredDestinationTypeDef, _OptionalDestinationTypeDef):
+    pass
+
+
 GetMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointPolicyResultTypeDef",
     {
         "Policy": MultiRegionAccessPointPolicyDocumentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AsyncResponseDetailsTypeDef = TypedDict(
     "AsyncResponseDetailsTypeDef",
     {
         "MultiRegionAccessPointDetails": MultiRegionAccessPointsAsyncResponseTypeDef,
@@ -2003,24 +2203,24 @@
     total=False,
 )
 
 GetMultiRegionAccessPointResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointResultTypeDef",
     {
         "AccessPoint": MultiRegionAccessPointReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiRegionAccessPointsResultTypeDef = TypedDict(
     "ListMultiRegionAccessPointsResultTypeDef",
     {
         "AccessPoints": List[MultiRegionAccessPointReportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PrefixLevelTypeDef = TypedDict(
     "PrefixLevelTypeDef",
     {
         "StorageMetrics": PrefixLevelStorageMetricsTypeDef,
@@ -2171,18 +2371,45 @@
 
 
 ListJobsResultTypeDef = TypedDict(
     "ListJobsResultTypeDef",
     {
         "NextToken": str,
         "Jobs": List[JobListDescriptorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredReplicationRuleTypeDef = TypedDict(
+    "_RequiredReplicationRuleTypeDef",
+    {
+        "Status": ReplicationRuleStatusType,
+        "Destination": DestinationTypeDef,
+        "Bucket": str,
+    },
+)
+_OptionalReplicationRuleTypeDef = TypedDict(
+    "_OptionalReplicationRuleTypeDef",
+    {
+        "ID": str,
+        "Priority": int,
+        "Prefix": str,
+        "Filter": ReplicationRuleFilterTypeDef,
+        "SourceSelectionCriteria": SourceSelectionCriteriaTypeDef,
+        "ExistingObjectReplication": ExistingObjectReplicationTypeDef,
+        "DeleteMarkerReplication": DeleteMarkerReplicationTypeDef,
+    },
+    total=False,
+)
+
+
+class ReplicationRuleTypeDef(_RequiredReplicationRuleTypeDef, _OptionalReplicationRuleTypeDef):
+    pass
+
+
 AsyncOperationTypeDef = TypedDict(
     "AsyncOperationTypeDef",
     {
         "CreationTime": datetime,
         "Operation": AsyncOperationNameType,
         "RequestTokenARN": str,
         "RequestParameters": AsyncRequestParametersTypeDef,
@@ -2231,15 +2458,15 @@
     },
 )
 
 GetAccessPointConfigurationForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointConfigurationForObjectLambdaResultTypeDef",
     {
         "Configuration": ObjectLambdaConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef = TypedDict(
     "PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -2248,15 +2475,15 @@
     },
 )
 
 GetBucketLifecycleConfigurationResultTypeDef = TypedDict(
     "GetBucketLifecycleConfigurationResultTypeDef",
     {
         "Rules": List[LifecycleRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleConfigurationTypeDef = TypedDict(
     "LifecycleConfigurationTypeDef",
     {
         "Rules": Sequence[LifecycleRuleTypeDef],
@@ -2268,19 +2495,27 @@
     "JobManifestGeneratorTypeDef",
     {
         "S3JobManifestGenerator": S3JobManifestGeneratorTypeDef,
     },
     total=False,
 )
 
+ReplicationConfigurationTypeDef = TypedDict(
+    "ReplicationConfigurationTypeDef",
+    {
+        "Role": str,
+        "Rules": List[ReplicationRuleTypeDef],
+    },
+)
+
 DescribeMultiRegionAccessPointOperationResultTypeDef = TypedDict(
     "DescribeMultiRegionAccessPointOperationResultTypeDef",
     {
         "AsyncOperation": AsyncOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAccountLevelTypeDef = TypedDict(
     "_RequiredAccountLevelTypeDef",
     {
         "BucketLevel": BucketLevelTypeDef,
@@ -2329,14 +2564,31 @@
 class PutBucketLifecycleConfigurationRequestRequestTypeDef(
     _RequiredPutBucketLifecycleConfigurationRequestRequestTypeDef,
     _OptionalPutBucketLifecycleConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
+GetBucketReplicationResultTypeDef = TypedDict(
+    "GetBucketReplicationResultTypeDef",
+    {
+        "ReplicationConfiguration": ReplicationConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutBucketReplicationRequestRequestTypeDef = TypedDict(
+    "PutBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+        "ReplicationConfiguration": ReplicationConfigurationTypeDef,
+    },
+)
+
 _RequiredStorageLensConfigurationTypeDef = TypedDict(
     "_RequiredStorageLensConfigurationTypeDef",
     {
         "Id": str,
         "AccountLevel": AccountLevelTypeDef,
         "IsEnabled": bool,
     },
@@ -2376,15 +2628,15 @@
     total=False,
 )
 
 GetStorageLensConfigurationResultTypeDef = TypedDict(
     "GetStorageLensConfigurationResultTypeDef",
     {
         "StorageLensConfiguration": StorageLensConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutStorageLensConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutStorageLensConfigurationRequestRequestTypeDef",
     {
         "ConfigId": str,
@@ -2464,10 +2716,10 @@
     total=False,
 )
 
 DescribeJobResultTypeDef = TypedDict(
     "DescribeJobResultTypeDef",
     {
         "Job": JobDescriptorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control/type_defs.pyi` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,100 +16,126 @@
 from typing import Any, Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AsyncOperationNameType,
     BucketCannedACLType,
     BucketLocationConstraintType,
     BucketVersioningStatusType,
+    DeleteMarkerReplicationStatusType,
+    ExistingObjectReplicationStatusType,
     ExpirationStatusType,
     FormatType,
     JobManifestFieldNameType,
     JobManifestFormatType,
     JobReportScopeType,
     JobStatusType,
+    MetricsStatusType,
     MFADeleteStatusType,
     MFADeleteType,
     MultiRegionAccessPointStatusType,
     NetworkOriginType,
+    ObjectLambdaAccessPointAliasStatusType,
     ObjectLambdaAllowedFeatureType,
     ObjectLambdaTransformationConfigurationActionType,
     OperationNameType,
+    ReplicaModificationsStatusType,
+    ReplicationRuleStatusType,
     ReplicationStatusType,
+    ReplicationStorageClassType,
+    ReplicationTimeStatusType,
     RequestedJobStatusType,
     S3CannedAccessControlListType,
     S3ChecksumAlgorithmType,
     S3GlacierJobTierType,
     S3GranteeTypeIdentifierType,
     S3MetadataDirectiveType,
     S3ObjectLockLegalHoldStatusType,
     S3ObjectLockModeType,
     S3ObjectLockRetentionModeType,
     S3PermissionType,
     S3SSEAlgorithmType,
     S3StorageClassType,
+    SseKmsEncryptedObjectsStatusType,
     TransitionStorageClassType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AbortIncompleteMultipartUploadTypeDef",
+    "AccessControlTranslationTypeDef",
     "VpcConfigurationTypeDef",
     "ActivityMetricsTypeDef",
     "AdvancedCostOptimizationMetricsTypeDef",
     "AdvancedDataProtectionMetricsTypeDef",
     "DetailedStatusCodesMetricsTypeDef",
     "AsyncErrorDetailsTypeDef",
     "DeleteMultiRegionAccessPointInputTypeDef",
     "PutMultiRegionAccessPointPolicyInputTypeDef",
     "AwsLambdaTransformationTypeDef",
     "CloudWatchMetricsTypeDef",
-    "ResponseMetadataTypeDef",
+    "ObjectLambdaAccessPointAliasTypeDef",
     "PublicAccessBlockConfigurationTypeDef",
+    "CreateAccessPointResultTypeDef",
     "CreateBucketConfigurationTypeDef",
+    "CreateBucketResultTypeDef",
     "JobReportTypeDef",
     "S3TagTypeDef",
+    "CreateJobResultTypeDef",
     "RegionTypeDef",
+    "CreateMultiRegionAccessPointResultTypeDef",
     "DeleteAccessPointForObjectLambdaRequestRequestTypeDef",
     "DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     "DeleteAccessPointPolicyRequestRequestTypeDef",
     "DeleteAccessPointRequestRequestTypeDef",
     "DeleteBucketLifecycleConfigurationRequestRequestTypeDef",
     "DeleteBucketPolicyRequestRequestTypeDef",
+    "DeleteBucketReplicationRequestRequestTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteBucketTaggingRequestRequestTypeDef",
     "DeleteJobTaggingRequestRequestTypeDef",
+    "DeleteMarkerReplicationTypeDef",
+    "DeleteMultiRegionAccessPointResultTypeDef",
     "DeletePublicAccessBlockRequestRequestTypeDef",
     "DeleteStorageLensConfigurationRequestRequestTypeDef",
     "DeleteStorageLensConfigurationTaggingRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeMultiRegionAccessPointOperationRequestRequestTypeDef",
+    "EncryptionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EstablishedMultiRegionAccessPointPolicyTypeDef",
     "ExcludeTypeDef",
+    "ExistingObjectReplicationTypeDef",
     "SSEKMSEncryptionTypeDef",
     "GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
+    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
     "GetAccessPointPolicyRequestRequestTypeDef",
+    "GetAccessPointPolicyResultTypeDef",
     "GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef",
     "PolicyStatusTypeDef",
     "GetAccessPointPolicyStatusRequestRequestTypeDef",
     "GetAccessPointRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationRequestRequestTypeDef",
     "GetBucketPolicyRequestRequestTypeDef",
+    "GetBucketPolicyResultTypeDef",
+    "GetBucketReplicationRequestRequestTypeDef",
     "GetBucketRequestRequestTypeDef",
+    "GetBucketResultTypeDef",
     "GetBucketTaggingRequestRequestTypeDef",
     "GetBucketVersioningRequestRequestTypeDef",
+    "GetBucketVersioningResultTypeDef",
     "GetJobTaggingRequestRequestTypeDef",
     "GetMultiRegionAccessPointPolicyRequestRequestTypeDef",
     "GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef",
     "GetMultiRegionAccessPointRequestRequestTypeDef",
     "GetMultiRegionAccessPointRoutesRequestRequestTypeDef",
     "MultiRegionAccessPointRouteTypeDef",
     "GetPublicAccessBlockRequestRequestTypeDef",
@@ -124,131 +150,134 @@
     "LambdaInvokeOperationTypeDef",
     "S3InitiateRestoreObjectOperationTypeDef",
     "JobTimersTypeDef",
     "LifecycleExpirationTypeDef",
     "NoncurrentVersionExpirationTypeDef",
     "NoncurrentVersionTransitionTypeDef",
     "TransitionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
     "ListAccessPointsForObjectLambdaRequestRequestTypeDef",
-    "ObjectLambdaAccessPointTypeDef",
     "ListAccessPointsRequestRequestTypeDef",
     "ListJobsRequestRequestTypeDef",
     "ListMultiRegionAccessPointsRequestRequestTypeDef",
     "ListRegionalBucketsRequestRequestTypeDef",
     "RegionalBucketTypeDef",
     "ListStorageLensConfigurationEntryTypeDef",
     "ListStorageLensConfigurationsRequestRequestTypeDef",
+    "ReplicationTimeValueTypeDef",
     "ProposedMultiRegionAccessPointPolicyTypeDef",
     "MultiRegionAccessPointRegionalResponseTypeDef",
     "RegionReportTypeDef",
+    "PaginatorConfigTypeDef",
     "SelectionCriteriaTypeDef",
     "PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     "PutAccessPointPolicyRequestRequestTypeDef",
     "PutBucketPolicyRequestRequestTypeDef",
     "VersioningConfigurationTypeDef",
+    "PutMultiRegionAccessPointPolicyResultTypeDef",
+    "ReplicaModificationsTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ObjectOwnerTypeDef",
     "S3ObjectMetadataTypeDef",
     "S3GranteeTypeDef",
     "S3ObjectLockLegalHoldTypeDef",
     "S3RetentionTypeDef",
     "SSEKMSTypeDef",
+    "SseKmsEncryptedObjectsTypeDef",
     "StorageLensAwsOrgTypeDef",
     "UpdateJobPriorityRequestRequestTypeDef",
+    "UpdateJobPriorityResultTypeDef",
     "UpdateJobStatusRequestRequestTypeDef",
+    "UpdateJobStatusResultTypeDef",
     "AccessPointTypeDef",
     "DeleteMultiRegionAccessPointRequestRequestTypeDef",
     "PutMultiRegionAccessPointPolicyRequestRequestTypeDef",
     "ObjectLambdaContentTransformationTypeDef",
     "CreateAccessPointForObjectLambdaResultTypeDef",
-    "CreateAccessPointResultTypeDef",
-    "CreateBucketResultTypeDef",
-    "CreateJobResultTypeDef",
-    "CreateMultiRegionAccessPointResultTypeDef",
-    "DeleteMultiRegionAccessPointResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
-    "GetAccessPointPolicyResultTypeDef",
-    "GetBucketPolicyResultTypeDef",
-    "GetBucketResultTypeDef",
-    "GetBucketVersioningResultTypeDef",
-    "PutMultiRegionAccessPointPolicyResultTypeDef",
-    "UpdateJobPriorityResultTypeDef",
-    "UpdateJobStatusResultTypeDef",
+    "ObjectLambdaAccessPointTypeDef",
     "CreateAccessPointRequestRequestTypeDef",
     "GetAccessPointForObjectLambdaResultTypeDef",
     "GetAccessPointResultTypeDef",
     "GetPublicAccessBlockOutputTypeDef",
     "PutPublicAccessBlockRequestRequestTypeDef",
     "CreateBucketRequestRequestTypeDef",
     "GetBucketTaggingResultTypeDef",
     "GetJobTaggingResultTypeDef",
     "LifecycleRuleAndOperatorTypeDef",
     "PutJobTaggingRequestRequestTypeDef",
+    "ReplicationRuleAndOperatorTypeDef",
     "S3SetObjectTaggingOperationTypeDef",
     "TaggingTypeDef",
     "CreateMultiRegionAccessPointInputTypeDef",
     "GeneratedManifestEncryptionTypeDef",
     "GetAccessPointPolicyStatusForObjectLambdaResultTypeDef",
     "GetAccessPointPolicyStatusResultTypeDef",
     "GetMultiRegionAccessPointPolicyStatusResultTypeDef",
     "GetMultiRegionAccessPointRoutesResultTypeDef",
     "SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef",
     "GetStorageLensConfigurationTaggingResultTypeDef",
     "PutStorageLensConfigurationTaggingRequestRequestTypeDef",
     "S3GeneratedManifestDescriptorTypeDef",
     "JobManifestTypeDef",
     "JobProgressSummaryTypeDef",
-    "ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
-    "ListAccessPointsForObjectLambdaResultTypeDef",
     "ListRegionalBucketsResultTypeDef",
     "ListStorageLensConfigurationsResultTypeDef",
+    "MetricsTypeDef",
+    "ReplicationTimeTypeDef",
     "MultiRegionAccessPointPolicyDocumentTypeDef",
     "MultiRegionAccessPointsAsyncResponseTypeDef",
     "MultiRegionAccessPointReportTypeDef",
     "PrefixLevelStorageMetricsTypeDef",
     "PutBucketVersioningRequestRequestTypeDef",
     "S3GrantTypeDef",
     "S3SetObjectLegalHoldOperationTypeDef",
     "S3SetObjectRetentionOperationTypeDef",
     "StorageLensDataExportEncryptionTypeDef",
+    "SourceSelectionCriteriaTypeDef",
     "ListAccessPointsResultTypeDef",
     "ObjectLambdaTransformationConfigurationTypeDef",
+    "ListAccessPointsForObjectLambdaResultTypeDef",
     "LifecycleRuleFilterTypeDef",
+    "ReplicationRuleFilterTypeDef",
     "PutBucketTaggingRequestRequestTypeDef",
     "AsyncRequestParametersTypeDef",
     "CreateMultiRegionAccessPointRequestRequestTypeDef",
     "S3ManifestOutputLocationTypeDef",
     "JobListDescriptorTypeDef",
+    "DestinationTypeDef",
     "GetMultiRegionAccessPointPolicyResultTypeDef",
     "AsyncResponseDetailsTypeDef",
     "GetMultiRegionAccessPointResultTypeDef",
     "ListMultiRegionAccessPointsResultTypeDef",
     "PrefixLevelTypeDef",
     "S3AccessControlListTypeDef",
     "S3CopyObjectOperationTypeDef",
     "S3BucketDestinationTypeDef",
     "ObjectLambdaConfigurationTypeDef",
     "LifecycleRuleTypeDef",
     "S3JobManifestGeneratorTypeDef",
     "ListJobsResultTypeDef",
+    "ReplicationRuleTypeDef",
     "AsyncOperationTypeDef",
     "BucketLevelTypeDef",
     "S3AccessControlPolicyTypeDef",
     "StorageLensDataExportTypeDef",
     "CreateAccessPointForObjectLambdaRequestRequestTypeDef",
     "GetAccessPointConfigurationForObjectLambdaResultTypeDef",
     "PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationResultTypeDef",
     "LifecycleConfigurationTypeDef",
     "JobManifestGeneratorTypeDef",
+    "ReplicationConfigurationTypeDef",
     "DescribeMultiRegionAccessPointOperationResultTypeDef",
     "AccountLevelTypeDef",
     "S3SetObjectAclOperationTypeDef",
     "PutBucketLifecycleConfigurationRequestRequestTypeDef",
+    "GetBucketReplicationResultTypeDef",
+    "PutBucketReplicationRequestRequestTypeDef",
     "StorageLensConfigurationTypeDef",
     "JobOperationTypeDef",
     "GetStorageLensConfigurationResultTypeDef",
     "PutStorageLensConfigurationRequestRequestTypeDef",
     "CreateJobRequestRequestTypeDef",
     "JobDescriptorTypeDef",
     "DescribeJobResultTypeDef",
@@ -258,14 +287,21 @@
     "AbortIncompleteMultipartUploadTypeDef",
     {
         "DaysAfterInitiation": int,
     },
     total=False,
 )
 
+AccessControlTranslationTypeDef = TypedDict(
+    "AccessControlTranslationTypeDef",
+    {
+        "Owner": Literal["Destination"],
+    },
+)
+
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "VpcId": str,
     },
 )
 
@@ -349,44 +385,60 @@
 CloudWatchMetricsTypeDef = TypedDict(
     "CloudWatchMetricsTypeDef",
     {
         "IsEnabled": bool,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ObjectLambdaAccessPointAliasTypeDef = TypedDict(
+    "ObjectLambdaAccessPointAliasTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Value": str,
+        "Status": ObjectLambdaAccessPointAliasStatusType,
     },
+    total=False,
 )
 
 PublicAccessBlockConfigurationTypeDef = TypedDict(
     "PublicAccessBlockConfigurationTypeDef",
     {
         "BlockPublicAcls": bool,
         "IgnorePublicAcls": bool,
         "BlockPublicPolicy": bool,
         "RestrictPublicBuckets": bool,
     },
     total=False,
 )
 
+CreateAccessPointResultTypeDef = TypedDict(
+    "CreateAccessPointResultTypeDef",
+    {
+        "AccessPointArn": str,
+        "Alias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateBucketConfigurationTypeDef = TypedDict(
     "CreateBucketConfigurationTypeDef",
     {
         "LocationConstraint": BucketLocationConstraintType,
     },
     total=False,
 )
 
+CreateBucketResultTypeDef = TypedDict(
+    "CreateBucketResultTypeDef",
+    {
+        "Location": str,
+        "BucketArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredJobReportTypeDef = TypedDict(
     "_RequiredJobReportTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalJobReportTypeDef = TypedDict(
@@ -407,20 +459,46 @@
     "S3TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-RegionTypeDef = TypedDict(
-    "RegionTypeDef",
+CreateJobResultTypeDef = TypedDict(
+    "CreateJobResultTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredRegionTypeDef = TypedDict(
+    "_RequiredRegionTypeDef",
     {
         "Bucket": str,
     },
 )
+_OptionalRegionTypeDef = TypedDict(
+    "_OptionalRegionTypeDef",
+    {
+        "BucketAccountId": str,
+    },
+    total=False,
+)
+
+class RegionTypeDef(_RequiredRegionTypeDef, _OptionalRegionTypeDef):
+    pass
+
+CreateMultiRegionAccessPointResultTypeDef = TypedDict(
+    "CreateMultiRegionAccessPointResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteAccessPointForObjectLambdaRequestRequestTypeDef = TypedDict(
     "DeleteAccessPointForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
@@ -462,14 +540,22 @@
     "DeleteBucketPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+DeleteBucketReplicationRequestRequestTypeDef = TypedDict(
+    "DeleteBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+    },
+)
+
 DeleteBucketRequestRequestTypeDef = TypedDict(
     "DeleteBucketRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
@@ -486,14 +572,29 @@
     "DeleteJobTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
     },
 )
 
+DeleteMarkerReplicationTypeDef = TypedDict(
+    "DeleteMarkerReplicationTypeDef",
+    {
+        "Status": DeleteMarkerReplicationStatusType,
+    },
+)
+
+DeleteMultiRegionAccessPointResultTypeDef = TypedDict(
+    "DeleteMultiRegionAccessPointResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePublicAccessBlockRequestRequestTypeDef = TypedDict(
     "DeletePublicAccessBlockRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 
@@ -525,14 +626,29 @@
     "DescribeMultiRegionAccessPointOperationRequestRequestTypeDef",
     {
         "AccountId": str,
         "RequestTokenARN": str,
     },
 )
 
+EncryptionConfigurationTypeDef = TypedDict(
+    "EncryptionConfigurationTypeDef",
+    {
+        "ReplicaKmsKeyID": str,
+    },
+    total=False,
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EstablishedMultiRegionAccessPointPolicyTypeDef = TypedDict(
     "EstablishedMultiRegionAccessPointPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -542,14 +658,21 @@
     {
         "Buckets": List[str],
         "Regions": List[str],
     },
     total=False,
 )
 
+ExistingObjectReplicationTypeDef = TypedDict(
+    "ExistingObjectReplicationTypeDef",
+    {
+        "Status": ExistingObjectReplicationStatusType,
+    },
+)
+
 SSEKMSEncryptionTypeDef = TypedDict(
     "SSEKMSEncryptionTypeDef",
     {
         "KeyId": str,
     },
 )
 
@@ -573,22 +696,38 @@
     "GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
 
+GetAccessPointPolicyForObjectLambdaResultTypeDef = TypedDict(
+    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessPointPolicyRequestRequestTypeDef = TypedDict(
     "GetAccessPointPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
 
+GetAccessPointPolicyResultTypeDef = TypedDict(
+    "GetAccessPointPolicyResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef = TypedDict(
     "GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
     },
 )
@@ -629,22 +768,48 @@
     "GetBucketPolicyRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketPolicyResultTypeDef = TypedDict(
+    "GetBucketPolicyResultTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetBucketReplicationRequestRequestTypeDef = TypedDict(
+    "GetBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+    },
+)
+
 GetBucketRequestRequestTypeDef = TypedDict(
     "GetBucketRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketResultTypeDef = TypedDict(
+    "GetBucketResultTypeDef",
+    {
+        "Bucket": str,
+        "PublicAccessBlockEnabled": bool,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBucketTaggingRequestRequestTypeDef = TypedDict(
     "GetBucketTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
@@ -653,14 +818,23 @@
     "GetBucketVersioningRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
     },
 )
 
+GetBucketVersioningResultTypeDef = TypedDict(
+    "GetBucketVersioningResultTypeDef",
+    {
+        "Status": BucketVersioningStatusType,
+        "MFADelete": MFADeleteStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobTaggingRequestRequestTypeDef = TypedDict(
     "GetJobTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
     },
 )
@@ -873,24 +1047,34 @@
         "Date": datetime,
         "Days": int,
         "StorageClass": TransitionStorageClassType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
+    "_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AccountId": str,
+    },
+)
+_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
+    "_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef(
+    _RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
+    _OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListAccessPointsForObjectLambdaRequestRequestTypeDef = TypedDict(
@@ -904,33 +1088,14 @@
 
 class ListAccessPointsForObjectLambdaRequestRequestTypeDef(
     _RequiredListAccessPointsForObjectLambdaRequestRequestTypeDef,
     _OptionalListAccessPointsForObjectLambdaRequestRequestTypeDef,
 ):
     pass
 
-_RequiredObjectLambdaAccessPointTypeDef = TypedDict(
-    "_RequiredObjectLambdaAccessPointTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalObjectLambdaAccessPointTypeDef = TypedDict(
-    "_OptionalObjectLambdaAccessPointTypeDef",
-    {
-        "ObjectLambdaAccessPointArn": str,
-    },
-    total=False,
-)
-
-class ObjectLambdaAccessPointTypeDef(
-    _RequiredObjectLambdaAccessPointTypeDef, _OptionalObjectLambdaAccessPointTypeDef
-):
-    pass
-
 _RequiredListAccessPointsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccessPointsRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListAccessPointsRequestRequestTypeDef = TypedDict(
@@ -1070,14 +1235,22 @@
 
 class ListStorageLensConfigurationsRequestRequestTypeDef(
     _RequiredListStorageLensConfigurationsRequestRequestTypeDef,
     _OptionalListStorageLensConfigurationsRequestRequestTypeDef,
 ):
     pass
 
+ReplicationTimeValueTypeDef = TypedDict(
+    "ReplicationTimeValueTypeDef",
+    {
+        "Minutes": int,
+    },
+    total=False,
+)
+
 ProposedMultiRegionAccessPointPolicyTypeDef = TypedDict(
     "ProposedMultiRegionAccessPointPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -1092,14 +1265,25 @@
 )
 
 RegionReportTypeDef = TypedDict(
     "RegionReportTypeDef",
     {
         "Bucket": str,
         "Region": str,
+        "BucketAccountId": str,
+    },
+    total=False,
+)
+
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
     total=False,
 )
 
 SelectionCriteriaTypeDef = TypedDict(
     "SelectionCriteriaTypeDef",
     {
@@ -1154,14 +1338,40 @@
     {
         "MFADelete": MFADeleteType,
         "Status": BucketVersioningStatusType,
     },
     total=False,
 )
 
+PutMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
+    "PutMultiRegionAccessPointPolicyResultTypeDef",
+    {
+        "RequestTokenARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ReplicaModificationsTypeDef = TypedDict(
+    "ReplicaModificationsTypeDef",
+    {
+        "Status": ReplicaModificationsStatusType,
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
 S3ObjectOwnerTypeDef = TypedDict(
     "S3ObjectOwnerTypeDef",
     {
         "ID": str,
         "DisplayName": str,
     },
     total=False,
@@ -1214,14 +1424,21 @@
 SSEKMSTypeDef = TypedDict(
     "SSEKMSTypeDef",
     {
         "KeyId": str,
     },
 )
 
+SseKmsEncryptedObjectsTypeDef = TypedDict(
+    "SseKmsEncryptedObjectsTypeDef",
+    {
+        "Status": SseKmsEncryptedObjectsStatusType,
+    },
+)
+
 StorageLensAwsOrgTypeDef = TypedDict(
     "StorageLensAwsOrgTypeDef",
     {
         "Arn": str,
     },
 )
 
@@ -1230,14 +1447,23 @@
     {
         "AccountId": str,
         "JobId": str,
         "Priority": int,
     },
 )
 
+UpdateJobPriorityResultTypeDef = TypedDict(
+    "UpdateJobPriorityResultTypeDef",
+    {
+        "JobId": str,
+        "Priority": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateJobStatusRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateJobStatusRequestRequestTypeDef",
     {
         "AccountId": str,
         "JobId": str,
         "RequestedJobStatus": RequestedJobStatusType,
     },
@@ -1251,14 +1477,24 @@
 )
 
 class UpdateJobStatusRequestRequestTypeDef(
     _RequiredUpdateJobStatusRequestRequestTypeDef, _OptionalUpdateJobStatusRequestRequestTypeDef
 ):
     pass
 
+UpdateJobStatusResultTypeDef = TypedDict(
+    "UpdateJobStatusResultTypeDef",
+    {
+        "JobId": str,
+        "Status": JobStatusType,
+        "StatusUpdateReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAccessPointTypeDef = TypedDict(
     "_RequiredAccessPointTypeDef",
     {
         "Name": str,
         "NetworkOrigin": NetworkOriginType,
         "Bucket": str,
     },
@@ -1303,136 +1539,38 @@
     total=False,
 )
 
 CreateAccessPointForObjectLambdaResultTypeDef = TypedDict(
     "CreateAccessPointForObjectLambdaResultTypeDef",
     {
         "ObjectLambdaAccessPointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessPointResultTypeDef = TypedDict(
-    "CreateAccessPointResultTypeDef",
-    {
-        "AccessPointArn": str,
-        "Alias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBucketResultTypeDef = TypedDict(
-    "CreateBucketResultTypeDef",
-    {
-        "Location": str,
-        "BucketArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResultTypeDef = TypedDict(
-    "CreateJobResultTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMultiRegionAccessPointResultTypeDef = TypedDict(
-    "CreateMultiRegionAccessPointResultTypeDef",
-    {
-        "RequestTokenARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMultiRegionAccessPointResultTypeDef = TypedDict(
-    "DeleteMultiRegionAccessPointResultTypeDef",
-    {
-        "RequestTokenARN": str,
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
-GetAccessPointPolicyForObjectLambdaResultTypeDef = TypedDict(
-    "GetAccessPointPolicyForObjectLambdaResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessPointPolicyResultTypeDef = TypedDict(
-    "GetAccessPointPolicyResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketPolicyResultTypeDef = TypedDict(
-    "GetBucketPolicyResultTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetBucketResultTypeDef = TypedDict(
-    "GetBucketResultTypeDef",
-    {
-        "Bucket": str,
-        "PublicAccessBlockEnabled": bool,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketVersioningResultTypeDef = TypedDict(
-    "GetBucketVersioningResultTypeDef",
-    {
-        "Status": BucketVersioningStatusType,
-        "MFADelete": MFADeleteStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
-    "PutMultiRegionAccessPointPolicyResultTypeDef",
+_RequiredObjectLambdaAccessPointTypeDef = TypedDict(
+    "_RequiredObjectLambdaAccessPointTypeDef",
     {
-        "RequestTokenARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
-
-UpdateJobPriorityResultTypeDef = TypedDict(
-    "UpdateJobPriorityResultTypeDef",
+_OptionalObjectLambdaAccessPointTypeDef = TypedDict(
+    "_OptionalObjectLambdaAccessPointTypeDef",
     {
-        "JobId": str,
-        "Priority": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ObjectLambdaAccessPointArn": str,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
     },
+    total=False,
 )
 
-UpdateJobStatusResultTypeDef = TypedDict(
-    "UpdateJobStatusResultTypeDef",
-    {
-        "JobId": str,
-        "Status": JobStatusType,
-        "StatusUpdateReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ObjectLambdaAccessPointTypeDef(
+    _RequiredObjectLambdaAccessPointTypeDef, _OptionalObjectLambdaAccessPointTypeDef
+):
+    pass
 
 _RequiredCreateAccessPointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccessPointRequestRequestTypeDef",
     {
         "AccountId": str,
         "Name": str,
         "Bucket": str,
@@ -1455,15 +1593,16 @@
 
 GetAccessPointForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointForObjectLambdaResultTypeDef",
     {
         "Name": str,
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
         "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Alias": ObjectLambdaAccessPointAliasTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessPointResultTypeDef = TypedDict(
     "GetAccessPointResultTypeDef",
     {
         "Name": str,
@@ -1472,23 +1611,23 @@
         "VpcConfiguration": VpcConfigurationTypeDef,
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
         "CreationDate": datetime,
         "Alias": str,
         "AccessPointArn": str,
         "Endpoints": Dict[str, str],
         "BucketAccountId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPublicAccessBlockOutputTypeDef = TypedDict(
     "GetPublicAccessBlockOutputTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPublicAccessBlockRequestRequestTypeDef = TypedDict(
     "PutPublicAccessBlockRequestRequestTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
@@ -1523,23 +1662,23 @@
 ):
     pass
 
 GetBucketTaggingResultTypeDef = TypedDict(
     "GetBucketTaggingResultTypeDef",
     {
         "TagSet": List[S3TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobTaggingResultTypeDef = TypedDict(
     "GetJobTaggingResultTypeDef",
     {
         "Tags": List[S3TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleRuleAndOperatorTypeDef = TypedDict(
     "LifecycleRuleAndOperatorTypeDef",
     {
         "Prefix": str,
@@ -1555,14 +1694,23 @@
     {
         "AccountId": str,
         "JobId": str,
         "Tags": Sequence[S3TagTypeDef],
     },
 )
 
+ReplicationRuleAndOperatorTypeDef = TypedDict(
+    "ReplicationRuleAndOperatorTypeDef",
+    {
+        "Prefix": str,
+        "Tags": List[S3TagTypeDef],
+    },
+    total=False,
+)
+
 S3SetObjectTaggingOperationTypeDef = TypedDict(
     "S3SetObjectTaggingOperationTypeDef",
     {
         "TagSet": Sequence[S3TagTypeDef],
     },
     total=False,
 )
@@ -1604,40 +1752,40 @@
     total=False,
 )
 
 GetAccessPointPolicyStatusForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointPolicyStatusForObjectLambdaResultTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessPointPolicyStatusResultTypeDef = TypedDict(
     "GetAccessPointPolicyStatusResultTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMultiRegionAccessPointPolicyStatusResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointPolicyStatusResultTypeDef",
     {
         "Established": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMultiRegionAccessPointRoutesResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointRoutesResultTypeDef",
     {
         "Mrap": str,
         "Routes": List[MultiRegionAccessPointRouteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef = TypedDict(
     "SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -1646,15 +1794,15 @@
     },
 )
 
 GetStorageLensConfigurationTaggingResultTypeDef = TypedDict(
     "GetStorageLensConfigurationTaggingResultTypeDef",
     {
         "Tags": List[StorageLensTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutStorageLensConfigurationTaggingRequestRequestTypeDef = TypedDict(
     "PutStorageLensConfigurationTaggingRequestRequestTypeDef",
     {
         "ConfigId": str,
@@ -1687,58 +1835,54 @@
         "NumberOfTasksSucceeded": int,
         "NumberOfTasksFailed": int,
         "Timers": JobTimersTypeDef,
     },
     total=False,
 )
 
-_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
-    "_RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+ListRegionalBucketsResultTypeDef = TypedDict(
+    "ListRegionalBucketsResultTypeDef",
     {
-        "AccountId": str,
+        "RegionalBucketList": List[RegionalBucketTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef = TypedDict(
-    "_OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef",
+
+ListStorageLensConfigurationsResultTypeDef = TypedDict(
+    "ListStorageLensConfigurationsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "StorageLensConfigurationList": List[ListStorageLensConfigurationEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef(
-    _RequiredListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-    _OptionalListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-):
-    pass
-
-ListAccessPointsForObjectLambdaResultTypeDef = TypedDict(
-    "ListAccessPointsForObjectLambdaResultTypeDef",
+_RequiredMetricsTypeDef = TypedDict(
+    "_RequiredMetricsTypeDef",
     {
-        "ObjectLambdaAccessPointList": List[ObjectLambdaAccessPointTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": MetricsStatusType,
     },
 )
-
-ListRegionalBucketsResultTypeDef = TypedDict(
-    "ListRegionalBucketsResultTypeDef",
+_OptionalMetricsTypeDef = TypedDict(
+    "_OptionalMetricsTypeDef",
     {
-        "RegionalBucketList": List[RegionalBucketTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EventThreshold": ReplicationTimeValueTypeDef,
     },
+    total=False,
 )
 
-ListStorageLensConfigurationsResultTypeDef = TypedDict(
-    "ListStorageLensConfigurationsResultTypeDef",
+class MetricsTypeDef(_RequiredMetricsTypeDef, _OptionalMetricsTypeDef):
+    pass
+
+ReplicationTimeTypeDef = TypedDict(
+    "ReplicationTimeTypeDef",
     {
-        "NextToken": str,
-        "StorageLensConfigurationList": List[ListStorageLensConfigurationEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Status": ReplicationTimeStatusType,
+        "Time": ReplicationTimeValueTypeDef,
     },
 )
 
 MultiRegionAccessPointPolicyDocumentTypeDef = TypedDict(
     "MultiRegionAccessPointPolicyDocumentTypeDef",
     {
         "Established": EstablishedMultiRegionAccessPointPolicyTypeDef,
@@ -1839,43 +1983,71 @@
     {
         "SSES3": Dict[str, Any],
         "SSEKMS": SSEKMSTypeDef,
     },
     total=False,
 )
 
+SourceSelectionCriteriaTypeDef = TypedDict(
+    "SourceSelectionCriteriaTypeDef",
+    {
+        "SseKmsEncryptedObjects": SseKmsEncryptedObjectsTypeDef,
+        "ReplicaModifications": ReplicaModificationsTypeDef,
+    },
+    total=False,
+)
+
 ListAccessPointsResultTypeDef = TypedDict(
     "ListAccessPointsResultTypeDef",
     {
         "AccessPointList": List[AccessPointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ObjectLambdaTransformationConfigurationTypeDef = TypedDict(
     "ObjectLambdaTransformationConfigurationTypeDef",
     {
         "Actions": Sequence[ObjectLambdaTransformationConfigurationActionType],
         "ContentTransformation": ObjectLambdaContentTransformationTypeDef,
     },
 )
 
+ListAccessPointsForObjectLambdaResultTypeDef = TypedDict(
+    "ListAccessPointsForObjectLambdaResultTypeDef",
+    {
+        "ObjectLambdaAccessPointList": List[ObjectLambdaAccessPointTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecycleRuleFilterTypeDef = TypedDict(
     "LifecycleRuleFilterTypeDef",
     {
         "Prefix": str,
         "Tag": S3TagTypeDef,
         "And": LifecycleRuleAndOperatorTypeDef,
         "ObjectSizeGreaterThan": int,
         "ObjectSizeLessThan": int,
     },
     total=False,
 )
 
+ReplicationRuleFilterTypeDef = TypedDict(
+    "ReplicationRuleFilterTypeDef",
+    {
+        "Prefix": str,
+        "Tag": S3TagTypeDef,
+        "And": ReplicationRuleAndOperatorTypeDef,
+    },
+    total=False,
+)
+
 PutBucketTaggingRequestRequestTypeDef = TypedDict(
     "PutBucketTaggingRequestRequestTypeDef",
     {
         "AccountId": str,
         "Bucket": str,
         "Tagging": TaggingTypeDef,
     },
@@ -1933,19 +2105,41 @@
         "CreationTime": datetime,
         "TerminationDate": datetime,
         "ProgressSummary": JobProgressSummaryTypeDef,
     },
     total=False,
 )
 
+_RequiredDestinationTypeDef = TypedDict(
+    "_RequiredDestinationTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalDestinationTypeDef = TypedDict(
+    "_OptionalDestinationTypeDef",
+    {
+        "Account": str,
+        "ReplicationTime": ReplicationTimeTypeDef,
+        "AccessControlTranslation": AccessControlTranslationTypeDef,
+        "EncryptionConfiguration": EncryptionConfigurationTypeDef,
+        "Metrics": MetricsTypeDef,
+        "StorageClass": ReplicationStorageClassType,
+    },
+    total=False,
+)
+
+class DestinationTypeDef(_RequiredDestinationTypeDef, _OptionalDestinationTypeDef):
+    pass
+
 GetMultiRegionAccessPointPolicyResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointPolicyResultTypeDef",
     {
         "Policy": MultiRegionAccessPointPolicyDocumentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AsyncResponseDetailsTypeDef = TypedDict(
     "AsyncResponseDetailsTypeDef",
     {
         "MultiRegionAccessPointDetails": MultiRegionAccessPointsAsyncResponseTypeDef,
@@ -1954,24 +2148,24 @@
     total=False,
 )
 
 GetMultiRegionAccessPointResultTypeDef = TypedDict(
     "GetMultiRegionAccessPointResultTypeDef",
     {
         "AccessPoint": MultiRegionAccessPointReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiRegionAccessPointsResultTypeDef = TypedDict(
     "ListMultiRegionAccessPointsResultTypeDef",
     {
         "AccessPoints": List[MultiRegionAccessPointReportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PrefixLevelTypeDef = TypedDict(
     "PrefixLevelTypeDef",
     {
         "StorageMetrics": PrefixLevelStorageMetricsTypeDef,
@@ -2112,17 +2306,42 @@
     pass
 
 ListJobsResultTypeDef = TypedDict(
     "ListJobsResultTypeDef",
     {
         "NextToken": str,
         "Jobs": List[JobListDescriptorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredReplicationRuleTypeDef = TypedDict(
+    "_RequiredReplicationRuleTypeDef",
+    {
+        "Status": ReplicationRuleStatusType,
+        "Destination": DestinationTypeDef,
+        "Bucket": str,
     },
 )
+_OptionalReplicationRuleTypeDef = TypedDict(
+    "_OptionalReplicationRuleTypeDef",
+    {
+        "ID": str,
+        "Priority": int,
+        "Prefix": str,
+        "Filter": ReplicationRuleFilterTypeDef,
+        "SourceSelectionCriteria": SourceSelectionCriteriaTypeDef,
+        "ExistingObjectReplication": ExistingObjectReplicationTypeDef,
+        "DeleteMarkerReplication": DeleteMarkerReplicationTypeDef,
+    },
+    total=False,
+)
+
+class ReplicationRuleTypeDef(_RequiredReplicationRuleTypeDef, _OptionalReplicationRuleTypeDef):
+    pass
 
 AsyncOperationTypeDef = TypedDict(
     "AsyncOperationTypeDef",
     {
         "CreationTime": datetime,
         "Operation": AsyncOperationNameType,
         "RequestTokenARN": str,
@@ -2172,15 +2391,15 @@
     },
 )
 
 GetAccessPointConfigurationForObjectLambdaResultTypeDef = TypedDict(
     "GetAccessPointConfigurationForObjectLambdaResultTypeDef",
     {
         "Configuration": ObjectLambdaConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef = TypedDict(
     "PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -2189,15 +2408,15 @@
     },
 )
 
 GetBucketLifecycleConfigurationResultTypeDef = TypedDict(
     "GetBucketLifecycleConfigurationResultTypeDef",
     {
         "Rules": List[LifecycleRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleConfigurationTypeDef = TypedDict(
     "LifecycleConfigurationTypeDef",
     {
         "Rules": Sequence[LifecycleRuleTypeDef],
@@ -2209,19 +2428,27 @@
     "JobManifestGeneratorTypeDef",
     {
         "S3JobManifestGenerator": S3JobManifestGeneratorTypeDef,
     },
     total=False,
 )
 
+ReplicationConfigurationTypeDef = TypedDict(
+    "ReplicationConfigurationTypeDef",
+    {
+        "Role": str,
+        "Rules": List[ReplicationRuleTypeDef],
+    },
+)
+
 DescribeMultiRegionAccessPointOperationResultTypeDef = TypedDict(
     "DescribeMultiRegionAccessPointOperationResultTypeDef",
     {
         "AsyncOperation": AsyncOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAccountLevelTypeDef = TypedDict(
     "_RequiredAccountLevelTypeDef",
     {
         "BucketLevel": BucketLevelTypeDef,
@@ -2266,14 +2493,31 @@
 
 class PutBucketLifecycleConfigurationRequestRequestTypeDef(
     _RequiredPutBucketLifecycleConfigurationRequestRequestTypeDef,
     _OptionalPutBucketLifecycleConfigurationRequestRequestTypeDef,
 ):
     pass
 
+GetBucketReplicationResultTypeDef = TypedDict(
+    "GetBucketReplicationResultTypeDef",
+    {
+        "ReplicationConfiguration": ReplicationConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutBucketReplicationRequestRequestTypeDef = TypedDict(
+    "PutBucketReplicationRequestRequestTypeDef",
+    {
+        "AccountId": str,
+        "Bucket": str,
+        "ReplicationConfiguration": ReplicationConfigurationTypeDef,
+    },
+)
+
 _RequiredStorageLensConfigurationTypeDef = TypedDict(
     "_RequiredStorageLensConfigurationTypeDef",
     {
         "Id": str,
         "AccountLevel": AccountLevelTypeDef,
         "IsEnabled": bool,
     },
@@ -2311,15 +2555,15 @@
     total=False,
 )
 
 GetStorageLensConfigurationResultTypeDef = TypedDict(
     "GetStorageLensConfigurationResultTypeDef",
     {
         "StorageLensConfiguration": StorageLensConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutStorageLensConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutStorageLensConfigurationRequestRequestTypeDef",
     {
         "ConfigId": str,
@@ -2395,10 +2639,10 @@
     total=False,
 )
 
 DescribeJobResultTypeDef = TypedDict(
     "DescribeJobResultTypeDef",
     {
         "Job": JobDescriptorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/PKG-INFO` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3control
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3Control 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3Control 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3control"></a>
 
 # types-aiobotocore-s3control
 
 [![PyPI - types-aiobotocore-s3control](https://img.shields.io/pypi/v/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3control.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3control)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3control?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3control)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3Control 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
+[aiobotocore.S3Control 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3control.html#S3Control)
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
 [types-aiobotocore-s3control docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3control/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,44 +298,54 @@
 
 ```python
 from types_aiobotocore_s3control.literals import (
     AsyncOperationNameType,
     BucketCannedACLType,
     BucketLocationConstraintType,
     BucketVersioningStatusType,
+    DeleteMarkerReplicationStatusType,
+    ExistingObjectReplicationStatusType,
     ExpirationStatusType,
     FormatType,
     GeneratedManifestFormatType,
     JobManifestFieldNameType,
     JobManifestFormatType,
     JobReportFormatType,
     JobReportScopeType,
     JobStatusType,
     ListAccessPointsForObjectLambdaPaginatorName,
     MFADeleteStatusType,
     MFADeleteType,
+    MetricsStatusType,
     MultiRegionAccessPointStatusType,
     NetworkOriginType,
+    ObjectLambdaAccessPointAliasStatusType,
     ObjectLambdaAllowedFeatureType,
     ObjectLambdaTransformationConfigurationActionType,
     OperationNameType,
     OutputSchemaVersionType,
+    OwnerOverrideType,
+    ReplicaModificationsStatusType,
+    ReplicationRuleStatusType,
     ReplicationStatusType,
+    ReplicationStorageClassType,
+    ReplicationTimeStatusType,
     RequestedJobStatusType,
     S3CannedAccessControlListType,
     S3ChecksumAlgorithmType,
     S3GlacierJobTierType,
     S3GranteeTypeIdentifierType,
     S3MetadataDirectiveType,
     S3ObjectLockLegalHoldStatusType,
     S3ObjectLockModeType,
     S3ObjectLockRetentionModeType,
     S3PermissionType,
     S3SSEAlgorithmType,
     S3StorageClassType,
+    SseKmsEncryptedObjectsStatusType,
     TransitionStorageClassType,
     S3ControlServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -351,60 +361,77 @@
 
 `types_aiobotocore_s3control.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3control.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
+    AccessControlTranslationTypeDef,
     VpcConfigurationTypeDef,
     ActivityMetricsTypeDef,
     AdvancedCostOptimizationMetricsTypeDef,
     AdvancedDataProtectionMetricsTypeDef,
     DetailedStatusCodesMetricsTypeDef,
     AsyncErrorDetailsTypeDef,
     DeleteMultiRegionAccessPointInputTypeDef,
     PutMultiRegionAccessPointPolicyInputTypeDef,
     AwsLambdaTransformationTypeDef,
     CloudWatchMetricsTypeDef,
-    ResponseMetadataTypeDef,
+    ObjectLambdaAccessPointAliasTypeDef,
     PublicAccessBlockConfigurationTypeDef,
+    CreateAccessPointResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketResultTypeDef,
     JobReportTypeDef,
     S3TagTypeDef,
+    CreateJobResultTypeDef,
     RegionTypeDef,
+    CreateMultiRegionAccessPointResultTypeDef,
     DeleteAccessPointForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     DeleteAccessPointPolicyRequestRequestTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteBucketLifecycleConfigurationRequestRequestTypeDef,
     DeleteBucketPolicyRequestRequestTypeDef,
+    DeleteBucketReplicationRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteJobTaggingRequestRequestTypeDef,
+    DeleteMarkerReplicationTypeDef,
+    DeleteMultiRegionAccessPointResultTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     DeleteStorageLensConfigurationRequestRequestTypeDef,
     DeleteStorageLensConfigurationTaggingRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeMultiRegionAccessPointOperationRequestRequestTypeDef,
+    EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EstablishedMultiRegionAccessPointPolicyTypeDef,
     ExcludeTypeDef,
+    ExistingObjectReplicationTypeDef,
     SSEKMSEncryptionTypeDef,
     GetAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
+    GetAccessPointPolicyForObjectLambdaResultTypeDef,
     GetAccessPointPolicyRequestRequestTypeDef,
+    GetAccessPointPolicyResultTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetAccessPointPolicyStatusRequestRequestTypeDef,
     GetAccessPointRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
+    GetBucketPolicyResultTypeDef,
+    GetBucketReplicationRequestRequestTypeDef,
     GetBucketRequestRequestTypeDef,
+    GetBucketResultTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
+    GetBucketVersioningResultTypeDef,
     GetJobTaggingRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyRequestRequestTypeDef,
     GetMultiRegionAccessPointPolicyStatusRequestRequestTypeDef,
     GetMultiRegionAccessPointRequestRequestTypeDef,
     GetMultiRegionAccessPointRoutesRequestRequestTypeDef,
     MultiRegionAccessPointRouteTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
@@ -419,131 +446,134 @@
     LambdaInvokeOperationTypeDef,
     S3InitiateRestoreObjectOperationTypeDef,
     JobTimersTypeDef,
     LifecycleExpirationTypeDef,
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
     ListAccessPointsForObjectLambdaRequestRequestTypeDef,
-    ObjectLambdaAccessPointTypeDef,
     ListAccessPointsRequestRequestTypeDef,
     ListJobsRequestRequestTypeDef,
     ListMultiRegionAccessPointsRequestRequestTypeDef,
     ListRegionalBucketsRequestRequestTypeDef,
     RegionalBucketTypeDef,
     ListStorageLensConfigurationEntryTypeDef,
     ListStorageLensConfigurationsRequestRequestTypeDef,
+    ReplicationTimeValueTypeDef,
     ProposedMultiRegionAccessPointPolicyTypeDef,
     MultiRegionAccessPointRegionalResponseTypeDef,
     RegionReportTypeDef,
+    PaginatorConfigTypeDef,
     SelectionCriteriaTypeDef,
     PutAccessPointPolicyForObjectLambdaRequestRequestTypeDef,
     PutAccessPointPolicyRequestRequestTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     VersioningConfigurationTypeDef,
+    PutMultiRegionAccessPointPolicyResultTypeDef,
+    ReplicaModificationsTypeDef,
+    ResponseMetadataTypeDef,
     S3ObjectOwnerTypeDef,
     S3ObjectMetadataTypeDef,
     S3GranteeTypeDef,
     S3ObjectLockLegalHoldTypeDef,
     S3RetentionTypeDef,
     SSEKMSTypeDef,
+    SseKmsEncryptedObjectsTypeDef,
     StorageLensAwsOrgTypeDef,
     UpdateJobPriorityRequestRequestTypeDef,
+    UpdateJobPriorityResultTypeDef,
     UpdateJobStatusRequestRequestTypeDef,
+    UpdateJobStatusResultTypeDef,
     AccessPointTypeDef,
     DeleteMultiRegionAccessPointRequestRequestTypeDef,
     PutMultiRegionAccessPointPolicyRequestRequestTypeDef,
     ObjectLambdaContentTransformationTypeDef,
     CreateAccessPointForObjectLambdaResultTypeDef,
-    CreateAccessPointResultTypeDef,
-    CreateBucketResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateMultiRegionAccessPointResultTypeDef,
-    DeleteMultiRegionAccessPointResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccessPointPolicyForObjectLambdaResultTypeDef,
-    GetAccessPointPolicyResultTypeDef,
-    GetBucketPolicyResultTypeDef,
-    GetBucketResultTypeDef,
-    GetBucketVersioningResultTypeDef,
-    PutMultiRegionAccessPointPolicyResultTypeDef,
-    UpdateJobPriorityResultTypeDef,
-    UpdateJobStatusResultTypeDef,
+    ObjectLambdaAccessPointTypeDef,
     CreateAccessPointRequestRequestTypeDef,
     GetAccessPointForObjectLambdaResultTypeDef,
     GetAccessPointResultTypeDef,
     GetPublicAccessBlockOutputTypeDef,
     PutPublicAccessBlockRequestRequestTypeDef,
     CreateBucketRequestRequestTypeDef,
     GetBucketTaggingResultTypeDef,
     GetJobTaggingResultTypeDef,
     LifecycleRuleAndOperatorTypeDef,
     PutJobTaggingRequestRequestTypeDef,
+    ReplicationRuleAndOperatorTypeDef,
     S3SetObjectTaggingOperationTypeDef,
     TaggingTypeDef,
     CreateMultiRegionAccessPointInputTypeDef,
     GeneratedManifestEncryptionTypeDef,
     GetAccessPointPolicyStatusForObjectLambdaResultTypeDef,
     GetAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointPolicyStatusResultTypeDef,
     GetMultiRegionAccessPointRoutesResultTypeDef,
     SubmitMultiRegionAccessPointRoutesRequestRequestTypeDef,
     GetStorageLensConfigurationTaggingResultTypeDef,
     PutStorageLensConfigurationTaggingRequestRequestTypeDef,
     S3GeneratedManifestDescriptorTypeDef,
     JobManifestTypeDef,
     JobProgressSummaryTypeDef,
-    ListAccessPointsForObjectLambdaRequestListAccessPointsForObjectLambdaPaginateTypeDef,
-    ListAccessPointsForObjectLambdaResultTypeDef,
     ListRegionalBucketsResultTypeDef,
     ListStorageLensConfigurationsResultTypeDef,
+    MetricsTypeDef,
+    ReplicationTimeTypeDef,
     MultiRegionAccessPointPolicyDocumentTypeDef,
     MultiRegionAccessPointsAsyncResponseTypeDef,
     MultiRegionAccessPointReportTypeDef,
     PrefixLevelStorageMetricsTypeDef,
     PutBucketVersioningRequestRequestTypeDef,
     S3GrantTypeDef,
     S3SetObjectLegalHoldOperationTypeDef,
     S3SetObjectRetentionOperationTypeDef,
     StorageLensDataExportEncryptionTypeDef,
+    SourceSelectionCriteriaTypeDef,
     ListAccessPointsResultTypeDef,
     ObjectLambdaTransformationConfigurationTypeDef,
+    ListAccessPointsForObjectLambdaResultTypeDef,
     LifecycleRuleFilterTypeDef,
+    ReplicationRuleFilterTypeDef,
     PutBucketTaggingRequestRequestTypeDef,
     AsyncRequestParametersTypeDef,
     CreateMultiRegionAccessPointRequestRequestTypeDef,
     S3ManifestOutputLocationTypeDef,
     JobListDescriptorTypeDef,
+    DestinationTypeDef,
     GetMultiRegionAccessPointPolicyResultTypeDef,
     AsyncResponseDetailsTypeDef,
     GetMultiRegionAccessPointResultTypeDef,
     ListMultiRegionAccessPointsResultTypeDef,
     PrefixLevelTypeDef,
     S3AccessControlListTypeDef,
     S3CopyObjectOperationTypeDef,
     S3BucketDestinationTypeDef,
     ObjectLambdaConfigurationTypeDef,
     LifecycleRuleTypeDef,
     S3JobManifestGeneratorTypeDef,
     ListJobsResultTypeDef,
+    ReplicationRuleTypeDef,
     AsyncOperationTypeDef,
     BucketLevelTypeDef,
     S3AccessControlPolicyTypeDef,
     StorageLensDataExportTypeDef,
     CreateAccessPointForObjectLambdaRequestRequestTypeDef,
     GetAccessPointConfigurationForObjectLambdaResultTypeDef,
     PutAccessPointConfigurationForObjectLambdaRequestRequestTypeDef,
     GetBucketLifecycleConfigurationResultTypeDef,
     LifecycleConfigurationTypeDef,
     JobManifestGeneratorTypeDef,
+    ReplicationConfigurationTypeDef,
     DescribeMultiRegionAccessPointOperationResultTypeDef,
     AccountLevelTypeDef,
     S3SetObjectAclOperationTypeDef,
     PutBucketLifecycleConfigurationRequestRequestTypeDef,
+    GetBucketReplicationResultTypeDef,
+    PutBucketReplicationRequestRequestTypeDef,
     StorageLensConfigurationTypeDef,
     JobOperationTypeDef,
     GetStorageLensConfigurationResultTypeDef,
     PutStorageLensConfigurationRequestRequestTypeDef,
     CreateJobRequestRequestTypeDef,
     JobDescriptorTypeDef,
     DescribeJobResultTypeDef,
@@ -557,43 +587,43 @@
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

### Comparing `types-aiobotocore-s3control-2.5.0.post1/types_aiobotocore_s3control.egg-info/SOURCES.txt` & `types-aiobotocore-s3control-2.5.1/types_aiobotocore_s3control.egg-info/SOURCES.txt`

 * *Files identical despite different names*

