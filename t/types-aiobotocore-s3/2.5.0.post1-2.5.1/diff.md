# Comparing `tmp/types-aiobotocore-s3-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-s3-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-s3-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-s3-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-s3-2.5.0.post1.tar` & `types-aiobotocore-s3-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.679582 types-aiobotocore-s3-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    35284 2023-03-11 12:27:15.679582 types-aiobotocore-s3-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    33733 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.679582 types-aiobotocore-s3-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2054 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.675582 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/
--rw-r--r--   0 runner    (1001) docker     (123)     2256 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2255 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      912 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    87118 2023-03-11 12:22:53.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    86997 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    16180 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    16178 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7430 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7422 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   124694 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)   124473 2023-03-11 12:22:53.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)   188471 2023-03-11 12:23:00.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   188159 2023-03-11 12:22:59.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:52.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     5614 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     5609 2023-03-11 12:22:54.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.679582 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    35284 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      864 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:27:15.000000 types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.714204 types-aiobotocore-s3-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    34160 2023-06-28 01:44:05.710204 types-aiobotocore-s3-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    32615 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.714204 types-aiobotocore-s3-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2048 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.702204 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/
+-rw-r--r--   0 runner    (1001) docker     (123)     2256 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2255 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    87383 2023-06-28 01:39:39.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    87262 2023-06-28 01:39:39.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    16429 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16427 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7433 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7425 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   124738 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)   124517 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)   184232 2023-06-28 01:39:46.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   183920 2023-06-28 01:39:44.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:38.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5614 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5609 2023-06-28 01:39:40.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.710204 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    34160 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      864 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:44:05.000000 types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/LICENSE` & `types-aiobotocore-s3-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-s3-2.5.0.post1/PKG-INFO` & `types-aiobotocore-s3-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3"></a>
 
 # types-aiobotocore-s3
 
 [![PyPI - types-aiobotocore-s3](https://img.shields.io/pypi/v/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
+[aiobotocore.S3 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
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
 [types-aiobotocore-s3 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/).
 
 See how it helps to find and fix potential bugs:
 
@@ -526,47 +526,49 @@
 
 `types_aiobotocore_s3.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
-    ResponseMetadataTypeDef,
+    AbortMultipartUploadOutputTypeDef,
     AbortMultipartUploadRequestMultipartUploadAbortTypeDef,
     AbortMultipartUploadRequestRequestTypeDef,
     AccelerateConfigurationTypeDef,
     OwnerTypeDef,
     AccessControlTranslationTypeDef,
     TagTypeDef,
     AnalyticsS3BucketDestinationTypeDef,
     CopySourceTypeDef,
     BucketDownloadFileRequestTypeDef,
     BucketDownloadFileobjRequestTypeDef,
-    BucketObjectRequestTypeDef,
     BucketTypeDef,
     BucketUploadFileRequestTypeDef,
     BucketUploadFileobjRequestTypeDef,
     CORSRuleTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     ChecksumTypeDef,
     ClientDownloadFileRequestTypeDef,
     ClientDownloadFileobjRequestTypeDef,
     ClientGeneratePresignedPostRequestTypeDef,
     ClientUploadFileRequestTypeDef,
     ClientUploadFileobjRequestTypeDef,
     CloudFunctionConfigurationTypeDef,
     CommonPrefixTypeDef,
+    CompleteMultipartUploadOutputTypeDef,
     CompletedPartTypeDef,
     ConditionTypeDef,
     CopyObjectResultTypeDef,
     CopyObjectRequestObjectCopyFromTypeDef,
     CopyObjectRequestObjectSummaryCopyFromTypeDef,
     CopyPartResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketOutputTypeDef,
+    CreateMultipartUploadOutputTypeDef,
     CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestObjectSummaryInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestRequestTypeDef,
     DefaultRetentionTypeDef,
     DeleteBucketAnalyticsConfigurationRequestRequestTypeDef,
     DeleteBucketCorsRequestBucketCorsDeleteTypeDef,
     DeleteBucketCorsRequestRequestTypeDef,
@@ -584,74 +586,88 @@
     DeleteBucketRequestBucketDeleteTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestBucketTaggingDeleteTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteBucketWebsiteRequestBucketWebsiteDeleteTypeDef,
     DeleteBucketWebsiteRequestRequestTypeDef,
     DeleteMarkerReplicationTypeDef,
+    DeleteObjectOutputTypeDef,
     DeleteObjectRequestObjectDeleteTypeDef,
     DeleteObjectRequestObjectSummaryDeleteTypeDef,
     DeleteObjectRequestObjectVersionDeleteTypeDef,
     DeleteObjectRequestRequestTypeDef,
+    DeleteObjectTaggingOutputTypeDef,
     DeleteObjectTaggingRequestRequestTypeDef,
     DeletedObjectTypeDef,
     ErrorTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     ObjectIdentifierTypeDef,
     EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
+    ErrorDocumentResponseMetadataTypeDef,
     ErrorDocumentTypeDef,
     ExistingObjectReplicationTypeDef,
     FilterRuleTypeDef,
+    GetBucketAccelerateConfigurationOutputTypeDef,
     GetBucketAccelerateConfigurationRequestRequestTypeDef,
     GetBucketAclRequestRequestTypeDef,
     GetBucketAnalyticsConfigurationRequestRequestTypeDef,
     GetBucketCorsRequestRequestTypeDef,
     GetBucketEncryptionRequestRequestTypeDef,
     GetBucketIntelligentTieringConfigurationRequestRequestTypeDef,
     GetBucketInventoryConfigurationRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketLifecycleRequestRequestTypeDef,
+    GetBucketLocationOutputTypeDef,
     GetBucketLocationRequestRequestTypeDef,
     GetBucketLoggingRequestRequestTypeDef,
     GetBucketMetricsConfigurationRequestRequestTypeDef,
     GetBucketNotificationConfigurationRequestRequestTypeDef,
     GetBucketOwnershipControlsRequestRequestTypeDef,
+    GetBucketPolicyOutputTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetBucketPolicyStatusRequestRequestTypeDef,
     GetBucketReplicationRequestRequestTypeDef,
+    GetBucketRequestPaymentOutputTypeDef,
     GetBucketRequestPaymentRequestRequestTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
+    GetBucketVersioningOutputTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
     IndexDocumentTypeDef,
     RedirectAllRequestsToTypeDef,
     GetBucketWebsiteRequestRequestTypeDef,
     GetObjectAclRequestRequestTypeDef,
     ObjectPartTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
     ObjectLockLegalHoldTypeDef,
     GetObjectLegalHoldRequestRequestTypeDef,
     GetObjectLockConfigurationRequestRequestTypeDef,
+    GetObjectOutputTypeDef,
     GetObjectRequestObjectGetTypeDef,
     GetObjectRequestObjectSummaryGetTypeDef,
     GetObjectRequestObjectVersionGetTypeDef,
     GetObjectRequestRequestTypeDef,
     ObjectLockRetentionTypeDef,
     GetObjectRetentionRequestRequestTypeDef,
     GetObjectTaggingRequestRequestTypeDef,
+    GetObjectTorrentOutputTypeDef,
     GetObjectTorrentRequestRequestTypeDef,
     PublicAccessBlockConfigurationTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
     GlacierJobParametersTypeDef,
     GranteeTypeDef,
     WaiterConfigTypeDef,
     HeadBucketRequestRequestTypeDef,
+    HeadObjectOutputTypeDef,
     HeadObjectRequestObjectVersionHeadTypeDef,
     HeadObjectRequestRequestTypeDef,
+    IndexDocumentResponseMetadataTypeDef,
+    InitiatorResponseMetadataTypeDef,
     InitiatorTypeDef,
     JSONInputTypeDef,
     TieringTypeDef,
     InventoryFilterTypeDef,
     InventoryScheduleTypeDef,
     SSEKMSTypeDef,
     JSONOutputTypeDef,
@@ -659,103 +675,68 @@
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
     ListBucketAnalyticsConfigurationsRequestRequestTypeDef,
     ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef,
     ListBucketInventoryConfigurationsRequestRequestTypeDef,
     ListBucketMetricsConfigurationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsRequestRequestTypeDef,
+    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
     ListObjectVersionsRequestRequestTypeDef,
+    ListObjectsRequestListObjectsPaginateTypeDef,
     ListObjectsRequestRequestTypeDef,
+    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
     ListObjectsV2RequestRequestTypeDef,
     PartTypeDef,
+    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsRequestRequestTypeDef,
     MetadataEntryTypeDef,
     ReplicationTimeValueTypeDef,
-    MultipartUploadPartRequestTypeDef,
     QueueConfigurationDeprecatedTypeDef,
     TopicConfigurationDeprecatedTypeDef,
     ObjectDownloadFileRequestTypeDef,
     ObjectDownloadFileobjRequestTypeDef,
-    ObjectMultipartUploadRequestTypeDef,
-    ObjectSummaryMultipartUploadRequestTypeDef,
-    ObjectSummaryVersionRequestTypeDef,
     ObjectUploadFileRequestTypeDef,
     ObjectUploadFileobjRequestTypeDef,
-    ObjectVersionRequestTypeDef,
+    OwnerResponseMetadataTypeDef,
     OwnershipControlsRuleTypeDef,
+    PaginatorConfigTypeDef,
     ProgressTypeDef,
     PutBucketPolicyRequestBucketPolicyPutTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     RequestPaymentConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningEnableTypeDef,
     VersioningConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningSuspendTypeDef,
+    PutObjectAclOutputTypeDef,
+    PutObjectLegalHoldOutputTypeDef,
+    PutObjectLockConfigurationOutputTypeDef,
+    PutObjectOutputTypeDef,
     PutObjectRequestBucketPutObjectTypeDef,
     PutObjectRequestObjectPutTypeDef,
     PutObjectRequestObjectSummaryPutTypeDef,
     PutObjectRequestRequestTypeDef,
+    PutObjectRetentionOutputTypeDef,
+    PutObjectTaggingOutputTypeDef,
     RecordsEventTypeDef,
+    RedirectAllRequestsToResponseMetadataTypeDef,
     RedirectTypeDef,
     ReplicaModificationsTypeDef,
     RequestProgressTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreObjectOutputTypeDef,
     ScanRangeTypeDef,
     ServerSideEncryptionByDefaultTypeDef,
-    ServiceResourceBucketAclRequestTypeDef,
-    ServiceResourceBucketCorsRequestTypeDef,
-    ServiceResourceBucketLifecycleConfigurationRequestTypeDef,
-    ServiceResourceBucketLifecycleRequestTypeDef,
-    ServiceResourceBucketLoggingRequestTypeDef,
-    ServiceResourceBucketNotificationRequestTypeDef,
-    ServiceResourceBucketPolicyRequestTypeDef,
-    ServiceResourceBucketRequestPaymentRequestTypeDef,
-    ServiceResourceBucketRequestTypeDef,
-    ServiceResourceBucketTaggingRequestTypeDef,
-    ServiceResourceBucketVersioningRequestTypeDef,
-    ServiceResourceBucketWebsiteRequestTypeDef,
-    ServiceResourceMultipartUploadPartRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceObjectAclRequestTypeDef,
-    ServiceResourceObjectRequestTypeDef,
-    ServiceResourceObjectSummaryRequestTypeDef,
-    ServiceResourceObjectVersionRequestTypeDef,
     SseKmsEncryptedObjectsTypeDef,
     StatsTypeDef,
+    UploadPartOutputTypeDef,
     UploadPartRequestMultipartUploadPartUploadTypeDef,
     UploadPartRequestRequestTypeDef,
     WriteGetObjectResponseRequestRequestTypeDef,
-    AbortMultipartUploadOutputTypeDef,
-    CompleteMultipartUploadOutputTypeDef,
-    CreateBucketOutputTypeDef,
-    CreateMultipartUploadOutputTypeDef,
-    DeleteObjectOutputTypeDef,
-    DeleteObjectTaggingOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ErrorDocumentResponseMetadataTypeDef,
-    GetBucketAccelerateConfigurationOutputTypeDef,
-    GetBucketLocationOutputTypeDef,
-    GetBucketPolicyOutputTypeDef,
-    GetBucketRequestPaymentOutputTypeDef,
-    GetBucketVersioningOutputTypeDef,
-    GetObjectOutputTypeDef,
-    GetObjectTorrentOutputTypeDef,
-    HeadObjectOutputTypeDef,
-    IndexDocumentResponseMetadataTypeDef,
-    InitiatorResponseMetadataTypeDef,
-    OwnerResponseMetadataTypeDef,
-    PutObjectAclOutputTypeDef,
-    PutObjectLegalHoldOutputTypeDef,
-    PutObjectLockConfigurationOutputTypeDef,
-    PutObjectOutputTypeDef,
-    PutObjectRetentionOutputTypeDef,
-    PutObjectTaggingOutputTypeDef,
-    RedirectAllRequestsToResponseMetadataTypeDef,
-    RestoreObjectOutputTypeDef,
-    UploadPartOutputTypeDef,
     PutBucketAccelerateConfigurationRequestRequestTypeDef,
     DeleteMarkerEntryTypeDef,
     ObjectTypeDef,
     ObjectVersionTypeDef,
     AnalyticsAndOperatorTypeDef,
     GetBucketTaggingOutputTypeDef,
     GetObjectTaggingOutputTypeDef,
@@ -799,19 +780,14 @@
     HeadObjectRequestObjectExistsWaitTypeDef,
     HeadObjectRequestObjectNotExistsWaitTypeDef,
     MultipartUploadTypeDef,
     InputSerializationTypeDef,
     InventoryEncryptionTypeDef,
     OutputSerializationTypeDef,
     RuleTypeDef,
-    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-    ListObjectsRequestListObjectsPaginateTypeDef,
-    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
-    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsOutputTypeDef,
     MetricsTypeDef,
     ReplicationTimeTypeDef,
     NotificationConfigurationDeprecatedResponseMetadataTypeDef,
     NotificationConfigurationDeprecatedTypeDef,
     OwnershipControlsTypeDef,
     ProgressEventTypeDef,
@@ -930,43 +906,43 @@
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/README.md` & `types-aiobotocore-s3-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-s3"></a>
 
 # types-aiobotocore-s3
 
 [![PyPI - types-aiobotocore-s3](https://img.shields.io/pypi/v/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
+[aiobotocore.S3 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
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
 [types-aiobotocore-s3 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/).
 
 See how it helps to find and fix potential bugs:
 
@@ -493,47 +493,49 @@
 
 `types_aiobotocore_s3.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
-    ResponseMetadataTypeDef,
+    AbortMultipartUploadOutputTypeDef,
     AbortMultipartUploadRequestMultipartUploadAbortTypeDef,
     AbortMultipartUploadRequestRequestTypeDef,
     AccelerateConfigurationTypeDef,
     OwnerTypeDef,
     AccessControlTranslationTypeDef,
     TagTypeDef,
     AnalyticsS3BucketDestinationTypeDef,
     CopySourceTypeDef,
     BucketDownloadFileRequestTypeDef,
     BucketDownloadFileobjRequestTypeDef,
-    BucketObjectRequestTypeDef,
     BucketTypeDef,
     BucketUploadFileRequestTypeDef,
     BucketUploadFileobjRequestTypeDef,
     CORSRuleTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     ChecksumTypeDef,
     ClientDownloadFileRequestTypeDef,
     ClientDownloadFileobjRequestTypeDef,
     ClientGeneratePresignedPostRequestTypeDef,
     ClientUploadFileRequestTypeDef,
     ClientUploadFileobjRequestTypeDef,
     CloudFunctionConfigurationTypeDef,
     CommonPrefixTypeDef,
+    CompleteMultipartUploadOutputTypeDef,
     CompletedPartTypeDef,
     ConditionTypeDef,
     CopyObjectResultTypeDef,
     CopyObjectRequestObjectCopyFromTypeDef,
     CopyObjectRequestObjectSummaryCopyFromTypeDef,
     CopyPartResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketOutputTypeDef,
+    CreateMultipartUploadOutputTypeDef,
     CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestObjectSummaryInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestRequestTypeDef,
     DefaultRetentionTypeDef,
     DeleteBucketAnalyticsConfigurationRequestRequestTypeDef,
     DeleteBucketCorsRequestBucketCorsDeleteTypeDef,
     DeleteBucketCorsRequestRequestTypeDef,
@@ -551,74 +553,88 @@
     DeleteBucketRequestBucketDeleteTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestBucketTaggingDeleteTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteBucketWebsiteRequestBucketWebsiteDeleteTypeDef,
     DeleteBucketWebsiteRequestRequestTypeDef,
     DeleteMarkerReplicationTypeDef,
+    DeleteObjectOutputTypeDef,
     DeleteObjectRequestObjectDeleteTypeDef,
     DeleteObjectRequestObjectSummaryDeleteTypeDef,
     DeleteObjectRequestObjectVersionDeleteTypeDef,
     DeleteObjectRequestRequestTypeDef,
+    DeleteObjectTaggingOutputTypeDef,
     DeleteObjectTaggingRequestRequestTypeDef,
     DeletedObjectTypeDef,
     ErrorTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     ObjectIdentifierTypeDef,
     EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
+    ErrorDocumentResponseMetadataTypeDef,
     ErrorDocumentTypeDef,
     ExistingObjectReplicationTypeDef,
     FilterRuleTypeDef,
+    GetBucketAccelerateConfigurationOutputTypeDef,
     GetBucketAccelerateConfigurationRequestRequestTypeDef,
     GetBucketAclRequestRequestTypeDef,
     GetBucketAnalyticsConfigurationRequestRequestTypeDef,
     GetBucketCorsRequestRequestTypeDef,
     GetBucketEncryptionRequestRequestTypeDef,
     GetBucketIntelligentTieringConfigurationRequestRequestTypeDef,
     GetBucketInventoryConfigurationRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketLifecycleRequestRequestTypeDef,
+    GetBucketLocationOutputTypeDef,
     GetBucketLocationRequestRequestTypeDef,
     GetBucketLoggingRequestRequestTypeDef,
     GetBucketMetricsConfigurationRequestRequestTypeDef,
     GetBucketNotificationConfigurationRequestRequestTypeDef,
     GetBucketOwnershipControlsRequestRequestTypeDef,
+    GetBucketPolicyOutputTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetBucketPolicyStatusRequestRequestTypeDef,
     GetBucketReplicationRequestRequestTypeDef,
+    GetBucketRequestPaymentOutputTypeDef,
     GetBucketRequestPaymentRequestRequestTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
+    GetBucketVersioningOutputTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
     IndexDocumentTypeDef,
     RedirectAllRequestsToTypeDef,
     GetBucketWebsiteRequestRequestTypeDef,
     GetObjectAclRequestRequestTypeDef,
     ObjectPartTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
     ObjectLockLegalHoldTypeDef,
     GetObjectLegalHoldRequestRequestTypeDef,
     GetObjectLockConfigurationRequestRequestTypeDef,
+    GetObjectOutputTypeDef,
     GetObjectRequestObjectGetTypeDef,
     GetObjectRequestObjectSummaryGetTypeDef,
     GetObjectRequestObjectVersionGetTypeDef,
     GetObjectRequestRequestTypeDef,
     ObjectLockRetentionTypeDef,
     GetObjectRetentionRequestRequestTypeDef,
     GetObjectTaggingRequestRequestTypeDef,
+    GetObjectTorrentOutputTypeDef,
     GetObjectTorrentRequestRequestTypeDef,
     PublicAccessBlockConfigurationTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
     GlacierJobParametersTypeDef,
     GranteeTypeDef,
     WaiterConfigTypeDef,
     HeadBucketRequestRequestTypeDef,
+    HeadObjectOutputTypeDef,
     HeadObjectRequestObjectVersionHeadTypeDef,
     HeadObjectRequestRequestTypeDef,
+    IndexDocumentResponseMetadataTypeDef,
+    InitiatorResponseMetadataTypeDef,
     InitiatorTypeDef,
     JSONInputTypeDef,
     TieringTypeDef,
     InventoryFilterTypeDef,
     InventoryScheduleTypeDef,
     SSEKMSTypeDef,
     JSONOutputTypeDef,
@@ -626,103 +642,68 @@
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
     ListBucketAnalyticsConfigurationsRequestRequestTypeDef,
     ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef,
     ListBucketInventoryConfigurationsRequestRequestTypeDef,
     ListBucketMetricsConfigurationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsRequestRequestTypeDef,
+    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
     ListObjectVersionsRequestRequestTypeDef,
+    ListObjectsRequestListObjectsPaginateTypeDef,
     ListObjectsRequestRequestTypeDef,
+    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
     ListObjectsV2RequestRequestTypeDef,
     PartTypeDef,
+    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsRequestRequestTypeDef,
     MetadataEntryTypeDef,
     ReplicationTimeValueTypeDef,
-    MultipartUploadPartRequestTypeDef,
     QueueConfigurationDeprecatedTypeDef,
     TopicConfigurationDeprecatedTypeDef,
     ObjectDownloadFileRequestTypeDef,
     ObjectDownloadFileobjRequestTypeDef,
-    ObjectMultipartUploadRequestTypeDef,
-    ObjectSummaryMultipartUploadRequestTypeDef,
-    ObjectSummaryVersionRequestTypeDef,
     ObjectUploadFileRequestTypeDef,
     ObjectUploadFileobjRequestTypeDef,
-    ObjectVersionRequestTypeDef,
+    OwnerResponseMetadataTypeDef,
     OwnershipControlsRuleTypeDef,
+    PaginatorConfigTypeDef,
     ProgressTypeDef,
     PutBucketPolicyRequestBucketPolicyPutTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     RequestPaymentConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningEnableTypeDef,
     VersioningConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningSuspendTypeDef,
+    PutObjectAclOutputTypeDef,
+    PutObjectLegalHoldOutputTypeDef,
+    PutObjectLockConfigurationOutputTypeDef,
+    PutObjectOutputTypeDef,
     PutObjectRequestBucketPutObjectTypeDef,
     PutObjectRequestObjectPutTypeDef,
     PutObjectRequestObjectSummaryPutTypeDef,
     PutObjectRequestRequestTypeDef,
+    PutObjectRetentionOutputTypeDef,
+    PutObjectTaggingOutputTypeDef,
     RecordsEventTypeDef,
+    RedirectAllRequestsToResponseMetadataTypeDef,
     RedirectTypeDef,
     ReplicaModificationsTypeDef,
     RequestProgressTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreObjectOutputTypeDef,
     ScanRangeTypeDef,
     ServerSideEncryptionByDefaultTypeDef,
-    ServiceResourceBucketAclRequestTypeDef,
-    ServiceResourceBucketCorsRequestTypeDef,
-    ServiceResourceBucketLifecycleConfigurationRequestTypeDef,
-    ServiceResourceBucketLifecycleRequestTypeDef,
-    ServiceResourceBucketLoggingRequestTypeDef,
-    ServiceResourceBucketNotificationRequestTypeDef,
-    ServiceResourceBucketPolicyRequestTypeDef,
-    ServiceResourceBucketRequestPaymentRequestTypeDef,
-    ServiceResourceBucketRequestTypeDef,
-    ServiceResourceBucketTaggingRequestTypeDef,
-    ServiceResourceBucketVersioningRequestTypeDef,
-    ServiceResourceBucketWebsiteRequestTypeDef,
-    ServiceResourceMultipartUploadPartRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceObjectAclRequestTypeDef,
-    ServiceResourceObjectRequestTypeDef,
-    ServiceResourceObjectSummaryRequestTypeDef,
-    ServiceResourceObjectVersionRequestTypeDef,
     SseKmsEncryptedObjectsTypeDef,
     StatsTypeDef,
+    UploadPartOutputTypeDef,
     UploadPartRequestMultipartUploadPartUploadTypeDef,
     UploadPartRequestRequestTypeDef,
     WriteGetObjectResponseRequestRequestTypeDef,
-    AbortMultipartUploadOutputTypeDef,
-    CompleteMultipartUploadOutputTypeDef,
-    CreateBucketOutputTypeDef,
-    CreateMultipartUploadOutputTypeDef,
-    DeleteObjectOutputTypeDef,
-    DeleteObjectTaggingOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ErrorDocumentResponseMetadataTypeDef,
-    GetBucketAccelerateConfigurationOutputTypeDef,
-    GetBucketLocationOutputTypeDef,
-    GetBucketPolicyOutputTypeDef,
-    GetBucketRequestPaymentOutputTypeDef,
-    GetBucketVersioningOutputTypeDef,
-    GetObjectOutputTypeDef,
-    GetObjectTorrentOutputTypeDef,
-    HeadObjectOutputTypeDef,
-    IndexDocumentResponseMetadataTypeDef,
-    InitiatorResponseMetadataTypeDef,
-    OwnerResponseMetadataTypeDef,
-    PutObjectAclOutputTypeDef,
-    PutObjectLegalHoldOutputTypeDef,
-    PutObjectLockConfigurationOutputTypeDef,
-    PutObjectOutputTypeDef,
-    PutObjectRetentionOutputTypeDef,
-    PutObjectTaggingOutputTypeDef,
-    RedirectAllRequestsToResponseMetadataTypeDef,
-    RestoreObjectOutputTypeDef,
-    UploadPartOutputTypeDef,
     PutBucketAccelerateConfigurationRequestRequestTypeDef,
     DeleteMarkerEntryTypeDef,
     ObjectTypeDef,
     ObjectVersionTypeDef,
     AnalyticsAndOperatorTypeDef,
     GetBucketTaggingOutputTypeDef,
     GetObjectTaggingOutputTypeDef,
@@ -766,19 +747,14 @@
     HeadObjectRequestObjectExistsWaitTypeDef,
     HeadObjectRequestObjectNotExistsWaitTypeDef,
     MultipartUploadTypeDef,
     InputSerializationTypeDef,
     InventoryEncryptionTypeDef,
     OutputSerializationTypeDef,
     RuleTypeDef,
-    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-    ListObjectsRequestListObjectsPaginateTypeDef,
-    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
-    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsOutputTypeDef,
     MetricsTypeDef,
     ReplicationTimeTypeDef,
     NotificationConfigurationDeprecatedResponseMetadataTypeDef,
     NotificationConfigurationDeprecatedTypeDef,
     OwnershipControlsTypeDef,
     ProgressEventTypeDef,
@@ -897,43 +873,43 @@
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/setup.py` & `types-aiobotocore-s3-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 """
 Setup script for types-aiobotocore-s3.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-s3",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_s3"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.S3 2.5.0 service generated with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.S3 2.5.1 service generated with mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -45,11 +45,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/",
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__init__.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__init__.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/__main__.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.S3 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.S3 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3\nOther"
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/client.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -413,16 +413,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#delete_bucket_cors)
         """
 
     async def delete_bucket_encryption(
         self, *, Bucket: str, ExpectedBucketOwner: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        This implementation of the DELETE action removes default encryption from the
-        bucket.
+        This implementation of the DELETE action resets the default encryption for the
+        bucket as server-side encryption with Amazon S3 managed keys (SSE-S3).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_encryption)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#delete_bucket_encryption)
         """
 
     async def delete_bucket_intelligent_tiering_configuration(
         self, *, Bucket: str, Id: str
@@ -608,15 +608,15 @@
         """
 
     async def generate_presigned_post(
         self,
         Bucket: str,
         Key: str,
         Fields: Dict[str, Any] = ...,
-        Conditions: List[Any] = ...,
+        Conditions: Union[List[Any], Dict[str, Any]] = ...,
         ExpiresIn: int = 3600,
     ) -> Dict[str, Any]:
         """
         Builds the url and the form fields used for a presigned s3 post.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_post)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#generate_presigned_post)
@@ -633,15 +633,19 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#generate_presigned_url)
         """
 
     async def get_bucket_accelerate_configuration(
-        self, *, Bucket: str, ExpectedBucketOwner: str = ...
+        self,
+        *,
+        Bucket: str,
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> GetBucketAccelerateConfigurationOutputTypeDef:
         """
         This implementation of the GET action uses the `accelerate` subresource to
         return the Transfer Acceleration state of a bucket, which is either `Enabled` or
         `Suspended`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_accelerate_configuration)
@@ -1046,15 +1050,15 @@
         SSECustomerKeyMD5: str = ...,
         RequestPayer: Literal["requester"] = ...,
         PartNumber: int = ...,
         ExpectedBucketOwner: str = ...,
         ChecksumMode: Literal["ENABLED"] = ...
     ) -> HeadObjectOutputTypeDef:
         """
-        The HEAD action retrieves metadata from an object without returning the object
+        The `HEAD` action retrieves metadata from an object without returning the object
         itself.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.head_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#head_object)
         """
 
     async def list_bucket_analytics_configurations(
@@ -1111,15 +1115,16 @@
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxUploads: int = ...,
         Prefix: str = ...,
         UploadIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> ListMultipartUploadsOutputTypeDef:
         """
         This action lists in-progress multipart uploads.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_multipart_uploads)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#list_multipart_uploads)
         """
@@ -1130,15 +1135,16 @@
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxKeys: int = ...,
         Prefix: str = ...,
         VersionIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> ListObjectVersionsOutputTypeDef:
         """
         Returns metadata about all versions of the objects in a bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_object_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#list_object_versions)
         """
@@ -1278,15 +1284,15 @@
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         ContentMD5: str = ...,
         ChecksumAlgorithm: ChecksumAlgorithmType = ...,
         ExpectedBucketOwner: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         This action uses the `encryption` subresource to configure default encryption
-        and Amazon S3 Bucket Key for an existing bucket.
+        and Amazon S3 Bucket Keys for an existing bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_encryption)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#put_bucket_encryption)
         """
 
     async def put_bucket_intelligent_tiering_configuration(
         self,
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/client.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -397,16 +397,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_cors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#delete_bucket_cors)
         """
     async def delete_bucket_encryption(
         self, *, Bucket: str, ExpectedBucketOwner: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        This implementation of the DELETE action removes default encryption from the
-        bucket.
+        This implementation of the DELETE action resets the default encryption for the
+        bucket as server-side encryption with Amazon S3 managed keys (SSE-S3).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.delete_bucket_encryption)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#delete_bucket_encryption)
         """
     async def delete_bucket_intelligent_tiering_configuration(
         self, *, Bucket: str, Id: str
     ) -> EmptyResponseMetadataTypeDef:
@@ -576,15 +576,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#download_fileobj)
         """
     async def generate_presigned_post(
         self,
         Bucket: str,
         Key: str,
         Fields: Dict[str, Any] = ...,
-        Conditions: List[Any] = ...,
+        Conditions: Union[List[Any], Dict[str, Any]] = ...,
         ExpiresIn: int = 3600,
     ) -> Dict[str, Any]:
         """
         Builds the url and the form fields used for a presigned s3 post.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_post)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#generate_presigned_post)
@@ -599,15 +599,19 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#generate_presigned_url)
         """
     async def get_bucket_accelerate_configuration(
-        self, *, Bucket: str, ExpectedBucketOwner: str = ...
+        self,
+        *,
+        Bucket: str,
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> GetBucketAccelerateConfigurationOutputTypeDef:
         """
         This implementation of the GET action uses the `accelerate` subresource to
         return the Transfer Acceleration state of a bucket, which is either `Enabled` or
         `Suspended`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.get_bucket_accelerate_configuration)
@@ -980,15 +984,15 @@
         SSECustomerKeyMD5: str = ...,
         RequestPayer: Literal["requester"] = ...,
         PartNumber: int = ...,
         ExpectedBucketOwner: str = ...,
         ChecksumMode: Literal["ENABLED"] = ...
     ) -> HeadObjectOutputTypeDef:
         """
-        The HEAD action retrieves metadata from an object without returning the object
+        The `HEAD` action retrieves metadata from an object without returning the object
         itself.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.head_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#head_object)
         """
     async def list_bucket_analytics_configurations(
         self, *, Bucket: str, ContinuationToken: str = ..., ExpectedBucketOwner: str = ...
@@ -1039,15 +1043,16 @@
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxUploads: int = ...,
         Prefix: str = ...,
         UploadIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> ListMultipartUploadsOutputTypeDef:
         """
         This action lists in-progress multipart uploads.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_multipart_uploads)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#list_multipart_uploads)
         """
@@ -1057,15 +1062,16 @@
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxKeys: int = ...,
         Prefix: str = ...,
         VersionIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> ListObjectVersionsOutputTypeDef:
         """
         Returns metadata about all versions of the objects in a bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.list_object_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#list_object_versions)
         """
@@ -1197,15 +1203,15 @@
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         ContentMD5: str = ...,
         ChecksumAlgorithm: ChecksumAlgorithmType = ...,
         ExpectedBucketOwner: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         This action uses the `encryption` subresource to configure default encryption
-        and Amazon S3 Bucket Key for an existing bucket.
+        and Amazon S3 Bucket Keys for an existing bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.put_bucket_encryption)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/client/#put_bucket_encryption)
         """
     async def put_bucket_intelligent_tiering_configuration(
         self,
         *,
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/literals.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AnalyticsS3ExportFileFormatType",
     "ArchiveStatusType",
     "BucketAccelerateStatusType",
     "BucketCannedACLType",
     "BucketExistsWaiterName",
     "BucketLocationConstraintType",
@@ -91,15 +90,14 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
 AnalyticsS3ExportFileFormatType = Literal["CSV"]
 ArchiveStatusType = Literal["ARCHIVE_ACCESS", "DEEP_ARCHIVE_ACCESS"]
 BucketAccelerateStatusType = Literal["Enabled", "Suspended"]
 BucketCannedACLType = Literal["authenticated-read", "private", "public-read", "public-read-write"]
 BucketExistsWaiterName = Literal["bucket_exists"]
 BucketLocationConstraintType = Literal[
     "EU",
@@ -222,14 +220,15 @@
     "DEEP_ARCHIVE",
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "OUTPOSTS",
     "REDUCED_REDUNDANCY",
+    "SNOW",
     "STANDARD",
     "STANDARD_IA",
 ]
 ObjectVersionStorageClassType = Literal["STANDARD"]
 OwnerOverrideType = Literal["Destination"]
 PayerType = Literal["BucketOwner", "Requester"]
 PermissionType = Literal["FULL_CONTROL", "READ", "READ_ACP", "WRITE", "WRITE_ACP"]
@@ -238,25 +237,26 @@
 ReplicaModificationsStatusType = Literal["Disabled", "Enabled"]
 ReplicationRuleStatusType = Literal["Disabled", "Enabled"]
 ReplicationStatusType = Literal["COMPLETE", "FAILED", "PENDING", "REPLICA"]
 ReplicationTimeStatusType = Literal["Disabled", "Enabled"]
 RequestChargedType = Literal["requester"]
 RequestPayerType = Literal["requester"]
 RestoreRequestTypeType = Literal["SELECT"]
-ServerSideEncryptionType = Literal["AES256", "aws:kms"]
+ServerSideEncryptionType = Literal["AES256", "aws:kms", "aws:kms:dsse"]
 SseKmsEncryptedObjectsStatusType = Literal["Disabled", "Enabled"]
 StorageClassAnalysisSchemaVersionType = Literal["V_1"]
 StorageClassType = Literal[
     "DEEP_ARCHIVE",
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "OUTPOSTS",
     "REDUCED_REDUNDANCY",
+    "SNOW",
     "STANDARD",
     "STANDARD_IA",
 ]
 TaggingDirectiveType = Literal["COPY", "REPLACE"]
 TierType = Literal["Bulk", "Expedited", "Standard"]
 TransitionStorageClassType = Literal[
     "DEEP_ARCHIVE", "GLACIER", "GLACIER_IR", "INTELLIGENT_TIERING", "ONEZONE_IA", "STANDARD_IA"
@@ -321,14 +321,15 @@
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
@@ -407,14 +408,15 @@
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
@@ -425,14 +427,15 @@
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
@@ -468,14 +471,15 @@
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
@@ -494,16 +498,19 @@
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
@@ -587,15 +594,17 @@
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/literals.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AnalyticsS3ExportFileFormatType",
     "ArchiveStatusType",
     "BucketAccelerateStatusType",
     "BucketCannedACLType",
     "BucketExistsWaiterName",
     "BucketLocationConstraintType",
@@ -90,14 +91,15 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+
 AnalyticsS3ExportFileFormatType = Literal["CSV"]
 ArchiveStatusType = Literal["ARCHIVE_ACCESS", "DEEP_ARCHIVE_ACCESS"]
 BucketAccelerateStatusType = Literal["Enabled", "Suspended"]
 BucketCannedACLType = Literal["authenticated-read", "private", "public-read", "public-read-write"]
 BucketExistsWaiterName = Literal["bucket_exists"]
 BucketLocationConstraintType = Literal[
     "EU",
@@ -220,14 +222,15 @@
     "DEEP_ARCHIVE",
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "OUTPOSTS",
     "REDUCED_REDUNDANCY",
+    "SNOW",
     "STANDARD",
     "STANDARD_IA",
 ]
 ObjectVersionStorageClassType = Literal["STANDARD"]
 OwnerOverrideType = Literal["Destination"]
 PayerType = Literal["BucketOwner", "Requester"]
 PermissionType = Literal["FULL_CONTROL", "READ", "READ_ACP", "WRITE", "WRITE_ACP"]
@@ -236,25 +239,26 @@
 ReplicaModificationsStatusType = Literal["Disabled", "Enabled"]
 ReplicationRuleStatusType = Literal["Disabled", "Enabled"]
 ReplicationStatusType = Literal["COMPLETE", "FAILED", "PENDING", "REPLICA"]
 ReplicationTimeStatusType = Literal["Disabled", "Enabled"]
 RequestChargedType = Literal["requester"]
 RequestPayerType = Literal["requester"]
 RestoreRequestTypeType = Literal["SELECT"]
-ServerSideEncryptionType = Literal["AES256", "aws:kms"]
+ServerSideEncryptionType = Literal["AES256", "aws:kms", "aws:kms:dsse"]
 SseKmsEncryptedObjectsStatusType = Literal["Disabled", "Enabled"]
 StorageClassAnalysisSchemaVersionType = Literal["V_1"]
 StorageClassType = Literal[
     "DEEP_ARCHIVE",
     "GLACIER",
     "GLACIER_IR",
     "INTELLIGENT_TIERING",
     "ONEZONE_IA",
     "OUTPOSTS",
     "REDUCED_REDUNDANCY",
+    "SNOW",
     "STANDARD",
     "STANDARD_IA",
 ]
 TaggingDirectiveType = Literal["COPY", "REPLACE"]
 TierType = Literal["Bulk", "Expedited", "Standard"]
 TransitionStorageClassType = Literal[
     "DEEP_ARCHIVE", "GLACIER", "GLACIER_IR", "INTELLIGENT_TIERING", "ONEZONE_IA", "STANDARD_IA"
@@ -319,14 +323,15 @@
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
@@ -405,14 +410,15 @@
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
@@ -423,14 +429,15 @@
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
@@ -466,14 +473,15 @@
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
@@ -492,16 +500,19 @@
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
@@ -585,15 +596,17 @@
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/paginator.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -25,32 +25,28 @@
         list_object_versions_paginator: ListObjectVersionsPaginator = client.get_paginator("list_object_versions")
         list_objects_paginator: ListObjectsPaginator = client.get_paginator("list_objects")
         list_objects_v2_paginator: ListObjectsV2Paginator = client.get_paginator("list_objects_v2")
         list_parts_paginator: ListPartsPaginator = client.get_paginator("list_parts")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListMultipartUploadsOutputTypeDef,
     ListObjectsOutputTypeDef,
     ListObjectsV2OutputTypeDef,
     ListObjectVersionsOutputTypeDef,
     ListPartsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -82,15 +78,16 @@
         self,
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        RequestPayer: Literal["requester"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultipartUploadsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListMultipartUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listmultipartuploadspaginator)
         """
 
 
@@ -104,15 +101,16 @@
         self,
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        RequestPayer: Literal["requester"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjectVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectversionspaginator)
         """
 
 
@@ -127,15 +125,15 @@
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectspaginator)
         """
 
 
@@ -152,15 +150,15 @@
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         FetchOwner: bool = ...,
         StartAfter: str = ...,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectsV2OutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjectsV2.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectsv2paginator)
         """
 
 
@@ -177,13 +175,13 @@
         Key: str,
         UploadId: str,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
         SSECustomerAlgorithm: str = ...,
         SSECustomerKey: str = ...,
         SSECustomerKeyMD5: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPartsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListParts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listpartspaginator)
         """
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/paginator.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/paginator.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -25,32 +25,28 @@
         list_object_versions_paginator: ListObjectVersionsPaginator = client.get_paginator("list_object_versions")
         list_objects_paginator: ListObjectsPaginator = client.get_paginator("list_objects")
         list_objects_v2_paginator: ListObjectsV2Paginator = client.get_paginator("list_objects_v2")
         list_parts_paginator: ListPartsPaginator = client.get_paginator("list_parts")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListMultipartUploadsOutputTypeDef,
     ListObjectsOutputTypeDef,
     ListObjectsV2OutputTypeDef,
     ListObjectVersionsOutputTypeDef,
     ListPartsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ListMultipartUploadsPaginator",
@@ -78,15 +74,16 @@
         self,
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        RequestPayer: Literal["requester"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultipartUploadsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListMultipartUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listmultipartuploadspaginator)
         """
 
 class ListObjectVersionsPaginator(AioPaginator):
@@ -99,15 +96,16 @@
         self,
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        RequestPayer: Literal["requester"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjectVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectversionspaginator)
         """
 
 class ListObjectsPaginator(AioPaginator):
@@ -121,15 +119,15 @@
         *,
         Bucket: str,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectspaginator)
         """
 
 class ListObjectsV2Paginator(AioPaginator):
@@ -145,15 +143,15 @@
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         Prefix: str = ...,
         FetchOwner: bool = ...,
         StartAfter: str = ...,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectsV2OutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListObjectsV2.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listobjectsv2paginator)
         """
 
 class ListPartsPaginator(AioPaginator):
@@ -169,13 +167,13 @@
         Key: str,
         UploadId: str,
         RequestPayer: Literal["requester"] = ...,
         ExpectedBucketOwner: str = ...,
         SSECustomerAlgorithm: str = ...,
         SSECustomerKey: str = ...,
         SSECustomerKeyMD5: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPartsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Paginator.ListParts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/paginators/#listpartspaginator)
         """
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/service_resource.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/service_resource.py`

 * *Files 2% similar despite different names*

```diff
@@ -33,15 +33,27 @@
         my_object_acl: s3_resources.ObjectAcl = resource.ObjectAcl(...)
         my_object_summary: s3_resources.ObjectSummary = resource.ObjectSummary(...)
         my_object_version: s3_resources.ObjectVersion = resource.ObjectVersion(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import IO, Any, Awaitable, Callable, Dict, List, Mapping, NoReturn, Sequence, Union
+from typing import (
+    IO,
+    Any,
+    AsyncIterator,
+    Awaitable,
+    Callable,
+    Dict,
+    List,
+    Mapping,
+    NoReturn,
+    Sequence,
+    Union,
+)
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 
 from .client import S3Client
 from .literals import (
     ArchiveStatusType,
@@ -110,18 +122,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
@@ -234,15 +242,16 @@
         *,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxUploads: int = ...,
         Prefix: str = ...,
         UploadIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> "BucketMultipartUploadsCollection":
         """
         Get items from the collection, passing keyword arguments along as parameters to the underlying service operation, which are typically used to filter the results.
         """
 
     def limit(self, count: int) -> "BucketMultipartUploadsCollection":
         """
@@ -281,15 +290,16 @@
         *,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxKeys: int = ...,
         Prefix: str = ...,
         VersionIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> "BucketObjectVersionsCollection":
         """
         Get items from the collection, passing keyword arguments along as parameters to the underlying service operation, which are typically used to filter the results.
         """
 
     async def delete(
         self,
@@ -1458,15 +1468,15 @@
         SSECustomerKeyMD5: str = ...,
         RequestPayer: Literal["requester"] = ...,
         PartNumber: int = ...,
         ExpectedBucketOwner: str = ...,
         ChecksumMode: Literal["ENABLED"] = ...
     ) -> HeadObjectOutputTypeDef:
         """
-        The HEAD action retrieves metadata from an object without returning the object
+        The `HEAD` action retrieves metadata from an object without returning the object
         itself.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.ObjectVersion.head)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/service_resource/#objectversionhead-method)
         """
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/service_resource.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/service_resource.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -33,15 +33,27 @@
         my_object_acl: s3_resources.ObjectAcl = resource.ObjectAcl(...)
         my_object_summary: s3_resources.ObjectSummary = resource.ObjectSummary(...)
         my_object_version: s3_resources.ObjectVersion = resource.ObjectVersion(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import IO, Any, Awaitable, Callable, Dict, List, Mapping, NoReturn, Sequence, Union
+from typing import (
+    IO,
+    Any,
+    AsyncIterator,
+    Awaitable,
+    Callable,
+    Dict,
+    List,
+    Mapping,
+    NoReturn,
+    Sequence,
+    Union,
+)
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 
 from .client import S3Client
 from .literals import (
     ArchiveStatusType,
@@ -110,18 +122,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
@@ -224,15 +232,16 @@
         *,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxUploads: int = ...,
         Prefix: str = ...,
         UploadIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> "BucketMultipartUploadsCollection":
         """
         Get items from the collection, passing keyword arguments along as parameters to the underlying service operation, which are typically used to filter the results.
         """
     def limit(self, count: int) -> "BucketMultipartUploadsCollection":
         """
         Return at most this many MultipartUploads.
@@ -264,15 +273,16 @@
         *,
         Delimiter: str = ...,
         EncodingType: Literal["url"] = ...,
         KeyMarker: str = ...,
         MaxKeys: int = ...,
         Prefix: str = ...,
         VersionIdMarker: str = ...,
-        ExpectedBucketOwner: str = ...
+        ExpectedBucketOwner: str = ...,
+        RequestPayer: Literal["requester"] = ...
     ) -> "BucketObjectVersionsCollection":
         """
         Get items from the collection, passing keyword arguments along as parameters to the underlying service operation, which are typically used to filter the results.
         """
     async def delete(
         self,
         *,
@@ -1330,15 +1340,15 @@
         SSECustomerKeyMD5: str = ...,
         RequestPayer: Literal["requester"] = ...,
         PartNumber: int = ...,
         ExpectedBucketOwner: str = ...,
         ChecksumMode: Literal["ENABLED"] = ...
     ) -> HeadObjectOutputTypeDef:
         """
-        The HEAD action retrieves metadata from an object without returning the object
+        The `HEAD` action retrieves metadata from an object without returning the object
         itself.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.ObjectVersion.head)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/service_resource/#objectversionhead-method)
         """
 
 _ObjectVersion = ObjectVersion
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/type_defs.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -80,47 +80,49 @@
     from boto3.s3.transfer import TransferConfig
 except (ModuleNotFoundError, ImportError):
     from builtins import object as TransferConfig
 
 
 __all__ = (
     "AbortIncompleteMultipartUploadTypeDef",
-    "ResponseMetadataTypeDef",
+    "AbortMultipartUploadOutputTypeDef",
     "AbortMultipartUploadRequestMultipartUploadAbortTypeDef",
     "AbortMultipartUploadRequestRequestTypeDef",
     "AccelerateConfigurationTypeDef",
     "OwnerTypeDef",
     "AccessControlTranslationTypeDef",
     "TagTypeDef",
     "AnalyticsS3BucketDestinationTypeDef",
     "CopySourceTypeDef",
     "BucketDownloadFileRequestTypeDef",
     "BucketDownloadFileobjRequestTypeDef",
-    "BucketObjectRequestTypeDef",
     "BucketTypeDef",
     "BucketUploadFileRequestTypeDef",
     "BucketUploadFileobjRequestTypeDef",
     "CORSRuleTypeDef",
     "CSVInputTypeDef",
     "CSVOutputTypeDef",
     "ChecksumTypeDef",
     "ClientDownloadFileRequestTypeDef",
     "ClientDownloadFileobjRequestTypeDef",
     "ClientGeneratePresignedPostRequestTypeDef",
     "ClientUploadFileRequestTypeDef",
     "ClientUploadFileobjRequestTypeDef",
     "CloudFunctionConfigurationTypeDef",
     "CommonPrefixTypeDef",
+    "CompleteMultipartUploadOutputTypeDef",
     "CompletedPartTypeDef",
     "ConditionTypeDef",
     "CopyObjectResultTypeDef",
     "CopyObjectRequestObjectCopyFromTypeDef",
     "CopyObjectRequestObjectSummaryCopyFromTypeDef",
     "CopyPartResultTypeDef",
     "CreateBucketConfigurationTypeDef",
+    "CreateBucketOutputTypeDef",
+    "CreateMultipartUploadOutputTypeDef",
     "CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef",
     "CreateMultipartUploadRequestObjectSummaryInitiateMultipartUploadTypeDef",
     "CreateMultipartUploadRequestRequestTypeDef",
     "DefaultRetentionTypeDef",
     "DeleteBucketAnalyticsConfigurationRequestRequestTypeDef",
     "DeleteBucketCorsRequestBucketCorsDeleteTypeDef",
     "DeleteBucketCorsRequestRequestTypeDef",
@@ -138,74 +140,88 @@
     "DeleteBucketRequestBucketDeleteTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteBucketTaggingRequestBucketTaggingDeleteTypeDef",
     "DeleteBucketTaggingRequestRequestTypeDef",
     "DeleteBucketWebsiteRequestBucketWebsiteDeleteTypeDef",
     "DeleteBucketWebsiteRequestRequestTypeDef",
     "DeleteMarkerReplicationTypeDef",
+    "DeleteObjectOutputTypeDef",
     "DeleteObjectRequestObjectDeleteTypeDef",
     "DeleteObjectRequestObjectSummaryDeleteTypeDef",
     "DeleteObjectRequestObjectVersionDeleteTypeDef",
     "DeleteObjectRequestRequestTypeDef",
+    "DeleteObjectTaggingOutputTypeDef",
     "DeleteObjectTaggingRequestRequestTypeDef",
     "DeletedObjectTypeDef",
     "ErrorTypeDef",
     "DeletePublicAccessBlockRequestRequestTypeDef",
     "ObjectIdentifierTypeDef",
     "EncryptionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionTypeDef",
+    "ErrorDocumentResponseMetadataTypeDef",
     "ErrorDocumentTypeDef",
     "ExistingObjectReplicationTypeDef",
     "FilterRuleTypeDef",
+    "GetBucketAccelerateConfigurationOutputTypeDef",
     "GetBucketAccelerateConfigurationRequestRequestTypeDef",
     "GetBucketAclRequestRequestTypeDef",
     "GetBucketAnalyticsConfigurationRequestRequestTypeDef",
     "GetBucketCorsRequestRequestTypeDef",
     "GetBucketEncryptionRequestRequestTypeDef",
     "GetBucketIntelligentTieringConfigurationRequestRequestTypeDef",
     "GetBucketInventoryConfigurationRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationRequestRequestTypeDef",
     "GetBucketLifecycleRequestRequestTypeDef",
+    "GetBucketLocationOutputTypeDef",
     "GetBucketLocationRequestRequestTypeDef",
     "GetBucketLoggingRequestRequestTypeDef",
     "GetBucketMetricsConfigurationRequestRequestTypeDef",
     "GetBucketNotificationConfigurationRequestRequestTypeDef",
     "GetBucketOwnershipControlsRequestRequestTypeDef",
+    "GetBucketPolicyOutputTypeDef",
     "GetBucketPolicyRequestRequestTypeDef",
     "PolicyStatusTypeDef",
     "GetBucketPolicyStatusRequestRequestTypeDef",
     "GetBucketReplicationRequestRequestTypeDef",
+    "GetBucketRequestPaymentOutputTypeDef",
     "GetBucketRequestPaymentRequestRequestTypeDef",
     "GetBucketTaggingRequestRequestTypeDef",
+    "GetBucketVersioningOutputTypeDef",
     "GetBucketVersioningRequestRequestTypeDef",
     "IndexDocumentTypeDef",
     "RedirectAllRequestsToTypeDef",
     "GetBucketWebsiteRequestRequestTypeDef",
     "GetObjectAclRequestRequestTypeDef",
     "ObjectPartTypeDef",
     "GetObjectAttributesRequestRequestTypeDef",
     "ObjectLockLegalHoldTypeDef",
     "GetObjectLegalHoldRequestRequestTypeDef",
     "GetObjectLockConfigurationRequestRequestTypeDef",
+    "GetObjectOutputTypeDef",
     "GetObjectRequestObjectGetTypeDef",
     "GetObjectRequestObjectSummaryGetTypeDef",
     "GetObjectRequestObjectVersionGetTypeDef",
     "GetObjectRequestRequestTypeDef",
     "ObjectLockRetentionTypeDef",
     "GetObjectRetentionRequestRequestTypeDef",
     "GetObjectTaggingRequestRequestTypeDef",
+    "GetObjectTorrentOutputTypeDef",
     "GetObjectTorrentRequestRequestTypeDef",
     "PublicAccessBlockConfigurationTypeDef",
     "GetPublicAccessBlockRequestRequestTypeDef",
     "GlacierJobParametersTypeDef",
     "GranteeTypeDef",
     "WaiterConfigTypeDef",
     "HeadBucketRequestRequestTypeDef",
+    "HeadObjectOutputTypeDef",
     "HeadObjectRequestObjectVersionHeadTypeDef",
     "HeadObjectRequestRequestTypeDef",
+    "IndexDocumentResponseMetadataTypeDef",
+    "InitiatorResponseMetadataTypeDef",
     "InitiatorTypeDef",
     "JSONInputTypeDef",
     "TieringTypeDef",
     "InventoryFilterTypeDef",
     "InventoryScheduleTypeDef",
     "SSEKMSTypeDef",
     "JSONOutputTypeDef",
@@ -213,103 +229,68 @@
     "NoncurrentVersionExpirationTypeDef",
     "NoncurrentVersionTransitionTypeDef",
     "TransitionTypeDef",
     "ListBucketAnalyticsConfigurationsRequestRequestTypeDef",
     "ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef",
     "ListBucketInventoryConfigurationsRequestRequestTypeDef",
     "ListBucketMetricsConfigurationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
     "ListMultipartUploadsRequestRequestTypeDef",
+    "ListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
     "ListObjectVersionsRequestRequestTypeDef",
+    "ListObjectsRequestListObjectsPaginateTypeDef",
     "ListObjectsRequestRequestTypeDef",
+    "ListObjectsV2RequestListObjectsV2PaginateTypeDef",
     "ListObjectsV2RequestRequestTypeDef",
     "PartTypeDef",
+    "ListPartsRequestListPartsPaginateTypeDef",
     "ListPartsRequestRequestTypeDef",
     "MetadataEntryTypeDef",
     "ReplicationTimeValueTypeDef",
-    "MultipartUploadPartRequestTypeDef",
     "QueueConfigurationDeprecatedTypeDef",
     "TopicConfigurationDeprecatedTypeDef",
     "ObjectDownloadFileRequestTypeDef",
     "ObjectDownloadFileobjRequestTypeDef",
-    "ObjectMultipartUploadRequestTypeDef",
-    "ObjectSummaryMultipartUploadRequestTypeDef",
-    "ObjectSummaryVersionRequestTypeDef",
     "ObjectUploadFileRequestTypeDef",
     "ObjectUploadFileobjRequestTypeDef",
-    "ObjectVersionRequestTypeDef",
+    "OwnerResponseMetadataTypeDef",
     "OwnershipControlsRuleTypeDef",
+    "PaginatorConfigTypeDef",
     "ProgressTypeDef",
     "PutBucketPolicyRequestBucketPolicyPutTypeDef",
     "PutBucketPolicyRequestRequestTypeDef",
     "RequestPaymentConfigurationTypeDef",
     "PutBucketVersioningRequestBucketVersioningEnableTypeDef",
     "VersioningConfigurationTypeDef",
     "PutBucketVersioningRequestBucketVersioningSuspendTypeDef",
+    "PutObjectAclOutputTypeDef",
+    "PutObjectLegalHoldOutputTypeDef",
+    "PutObjectLockConfigurationOutputTypeDef",
+    "PutObjectOutputTypeDef",
     "PutObjectRequestBucketPutObjectTypeDef",
     "PutObjectRequestObjectPutTypeDef",
     "PutObjectRequestObjectSummaryPutTypeDef",
     "PutObjectRequestRequestTypeDef",
+    "PutObjectRetentionOutputTypeDef",
+    "PutObjectTaggingOutputTypeDef",
     "RecordsEventTypeDef",
+    "RedirectAllRequestsToResponseMetadataTypeDef",
     "RedirectTypeDef",
     "ReplicaModificationsTypeDef",
     "RequestProgressTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreObjectOutputTypeDef",
     "ScanRangeTypeDef",
     "ServerSideEncryptionByDefaultTypeDef",
-    "ServiceResourceBucketAclRequestTypeDef",
-    "ServiceResourceBucketCorsRequestTypeDef",
-    "ServiceResourceBucketLifecycleConfigurationRequestTypeDef",
-    "ServiceResourceBucketLifecycleRequestTypeDef",
-    "ServiceResourceBucketLoggingRequestTypeDef",
-    "ServiceResourceBucketNotificationRequestTypeDef",
-    "ServiceResourceBucketPolicyRequestTypeDef",
-    "ServiceResourceBucketRequestPaymentRequestTypeDef",
-    "ServiceResourceBucketRequestTypeDef",
-    "ServiceResourceBucketTaggingRequestTypeDef",
-    "ServiceResourceBucketVersioningRequestTypeDef",
-    "ServiceResourceBucketWebsiteRequestTypeDef",
-    "ServiceResourceMultipartUploadPartRequestTypeDef",
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    "ServiceResourceObjectAclRequestTypeDef",
-    "ServiceResourceObjectRequestTypeDef",
-    "ServiceResourceObjectSummaryRequestTypeDef",
-    "ServiceResourceObjectVersionRequestTypeDef",
     "SseKmsEncryptedObjectsTypeDef",
     "StatsTypeDef",
+    "UploadPartOutputTypeDef",
     "UploadPartRequestMultipartUploadPartUploadTypeDef",
     "UploadPartRequestRequestTypeDef",
     "WriteGetObjectResponseRequestRequestTypeDef",
-    "AbortMultipartUploadOutputTypeDef",
-    "CompleteMultipartUploadOutputTypeDef",
-    "CreateBucketOutputTypeDef",
-    "CreateMultipartUploadOutputTypeDef",
-    "DeleteObjectOutputTypeDef",
-    "DeleteObjectTaggingOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ErrorDocumentResponseMetadataTypeDef",
-    "GetBucketAccelerateConfigurationOutputTypeDef",
-    "GetBucketLocationOutputTypeDef",
-    "GetBucketPolicyOutputTypeDef",
-    "GetBucketRequestPaymentOutputTypeDef",
-    "GetBucketVersioningOutputTypeDef",
-    "GetObjectOutputTypeDef",
-    "GetObjectTorrentOutputTypeDef",
-    "HeadObjectOutputTypeDef",
-    "IndexDocumentResponseMetadataTypeDef",
-    "InitiatorResponseMetadataTypeDef",
-    "OwnerResponseMetadataTypeDef",
-    "PutObjectAclOutputTypeDef",
-    "PutObjectLegalHoldOutputTypeDef",
-    "PutObjectLockConfigurationOutputTypeDef",
-    "PutObjectOutputTypeDef",
-    "PutObjectRetentionOutputTypeDef",
-    "PutObjectTaggingOutputTypeDef",
-    "RedirectAllRequestsToResponseMetadataTypeDef",
-    "RestoreObjectOutputTypeDef",
-    "UploadPartOutputTypeDef",
     "PutBucketAccelerateConfigurationRequestRequestTypeDef",
     "DeleteMarkerEntryTypeDef",
     "ObjectTypeDef",
     "ObjectVersionTypeDef",
     "AnalyticsAndOperatorTypeDef",
     "GetBucketTaggingOutputTypeDef",
     "GetObjectTaggingOutputTypeDef",
@@ -353,19 +334,14 @@
     "HeadObjectRequestObjectExistsWaitTypeDef",
     "HeadObjectRequestObjectNotExistsWaitTypeDef",
     "MultipartUploadTypeDef",
     "InputSerializationTypeDef",
     "InventoryEncryptionTypeDef",
     "OutputSerializationTypeDef",
     "RuleTypeDef",
-    "ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    "ListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    "ListObjectsRequestListObjectsPaginateTypeDef",
-    "ListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    "ListPartsRequestListPartsPaginateTypeDef",
     "ListPartsOutputTypeDef",
     "MetricsTypeDef",
     "ReplicationTimeTypeDef",
     "NotificationConfigurationDeprecatedResponseMetadataTypeDef",
     "NotificationConfigurationDeprecatedTypeDef",
     "OwnershipControlsTypeDef",
     "ProgressEventTypeDef",
@@ -480,22 +456,19 @@
     "AbortIncompleteMultipartUploadTypeDef",
     {
         "DaysAfterInitiation": int,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AbortMultipartUploadOutputTypeDef = TypedDict(
+    "AbortMultipartUploadOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AbortMultipartUploadRequestMultipartUploadAbortTypeDef = TypedDict(
     "AbortMultipartUploadRequestMultipartUploadAbortTypeDef",
     {
         "RequestPayer": Literal["requester"],
@@ -648,21 +621,14 @@
 
 class BucketDownloadFileobjRequestTypeDef(
     _RequiredBucketDownloadFileobjRequestTypeDef, _OptionalBucketDownloadFileobjRequestTypeDef
 ):
     pass
 
 
-BucketObjectRequestTypeDef = TypedDict(
-    "BucketObjectRequestTypeDef",
-    {
-        "key": str,
-    },
-)
-
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
     {
         "Name": str,
         "CreationDate": datetime,
     },
     total=False,
@@ -833,15 +799,15 @@
         "Key": str,
     },
 )
 _OptionalClientGeneratePresignedPostRequestTypeDef = TypedDict(
     "_OptionalClientGeneratePresignedPostRequestTypeDef",
     {
         "Fields": Dict[str, Any],
-        "Conditions": List[Any],
+        "Conditions": Union[List[Any], Dict[str, Any]],
         "ExpiresIn": int,
     },
     total=False,
 )
 
 
 class ClientGeneratePresignedPostRequestTypeDef(
@@ -917,14 +883,35 @@
     "CommonPrefixTypeDef",
     {
         "Prefix": str,
     },
     total=False,
 )
 
+CompleteMultipartUploadOutputTypeDef = TypedDict(
+    "CompleteMultipartUploadOutputTypeDef",
+    {
+        "Location": str,
+        "Bucket": str,
+        "Key": str,
+        "Expiration": str,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "VersionId": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CompletedPartTypeDef = TypedDict(
     "CompletedPartTypeDef",
     {
         "ETag": str,
         "ChecksumCRC32": str,
         "ChecksumCRC32C": str,
         "ChecksumSHA1": str,
@@ -1090,14 +1077,42 @@
     "CreateBucketConfigurationTypeDef",
     {
         "LocationConstraint": BucketLocationConstraintType,
     },
     total=False,
 )
 
+CreateBucketOutputTypeDef = TypedDict(
+    "CreateBucketOutputTypeDef",
+    {
+        "Location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateMultipartUploadOutputTypeDef = TypedDict(
+    "CreateMultipartUploadOutputTypeDef",
+    {
+        "AbortDate": datetime,
+        "AbortRuleId": str,
+        "Bucket": str,
+        "Key": str,
+        "UploadId": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "SSEKMSEncryptionContext": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ChecksumAlgorithm": ChecksumAlgorithmType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef = TypedDict(
     "CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef",
     {
         "ACL": ObjectCannedACLType,
         "CacheControl": str,
         "ContentDisposition": str,
         "ContentEncoding": str,
@@ -1557,14 +1572,24 @@
     "DeleteMarkerReplicationTypeDef",
     {
         "Status": DeleteMarkerReplicationStatusType,
     },
     total=False,
 )
 
+DeleteObjectOutputTypeDef = TypedDict(
+    "DeleteObjectOutputTypeDef",
+    {
+        "DeleteMarker": bool,
+        "VersionId": str,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteObjectRequestObjectDeleteTypeDef = TypedDict(
     "DeleteObjectRequestObjectDeleteTypeDef",
     {
         "MFA": str,
         "VersionId": str,
         "RequestPayer": Literal["requester"],
         "BypassGovernanceRetention": bool,
@@ -1618,14 +1643,22 @@
 
 class DeleteObjectRequestRequestTypeDef(
     _RequiredDeleteObjectRequestRequestTypeDef, _OptionalDeleteObjectRequestRequestTypeDef
 ):
     pass
 
 
+DeleteObjectTaggingOutputTypeDef = TypedDict(
+    "DeleteObjectTaggingOutputTypeDef",
+    {
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteObjectTaggingRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteObjectTaggingRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
 )
@@ -1713,14 +1746,21 @@
     "EncryptionConfigurationTypeDef",
     {
         "ReplicaKmsKeyID": str,
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
 _RequiredEncryptionTypeDef = TypedDict(
     "_RequiredEncryptionTypeDef",
     {
         "EncryptionType": ServerSideEncryptionType,
     },
 )
 _OptionalEncryptionTypeDef = TypedDict(
@@ -1733,14 +1773,22 @@
 )
 
 
 class EncryptionTypeDef(_RequiredEncryptionTypeDef, _OptionalEncryptionTypeDef):
     pass
 
 
+ErrorDocumentResponseMetadataTypeDef = TypedDict(
+    "ErrorDocumentResponseMetadataTypeDef",
+    {
+        "Key": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorDocumentTypeDef = TypedDict(
     "ErrorDocumentTypeDef",
     {
         "Key": str,
     },
 )
 
@@ -1756,24 +1804,34 @@
     {
         "Name": FilterRuleNameType,
         "Value": str,
     },
     total=False,
 )
 
+GetBucketAccelerateConfigurationOutputTypeDef = TypedDict(
+    "GetBucketAccelerateConfigurationOutputTypeDef",
+    {
+        "Status": BucketAccelerateStatusType,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalGetBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 
 class GetBucketAccelerateConfigurationRequestRequestTypeDef(
     _RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef,
@@ -1940,14 +1998,22 @@
 class GetBucketLifecycleRequestRequestTypeDef(
     _RequiredGetBucketLifecycleRequestRequestTypeDef,
     _OptionalGetBucketLifecycleRequestRequestTypeDef,
 ):
     pass
 
 
+GetBucketLocationOutputTypeDef = TypedDict(
+    "GetBucketLocationOutputTypeDef",
+    {
+        "LocationConstraint": BucketLocationConstraintType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketLocationRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketLocationRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketLocationRequestRequestTypeDef = TypedDict(
@@ -2049,14 +2115,22 @@
 class GetBucketOwnershipControlsRequestRequestTypeDef(
     _RequiredGetBucketOwnershipControlsRequestRequestTypeDef,
     _OptionalGetBucketOwnershipControlsRequestRequestTypeDef,
 ):
     pass
 
 
+GetBucketPolicyOutputTypeDef = TypedDict(
+    "GetBucketPolicyOutputTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketPolicyRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketPolicyRequestRequestTypeDef = TypedDict(
@@ -2122,14 +2196,22 @@
 class GetBucketReplicationRequestRequestTypeDef(
     _RequiredGetBucketReplicationRequestRequestTypeDef,
     _OptionalGetBucketReplicationRequestRequestTypeDef,
 ):
     pass
 
 
+GetBucketRequestPaymentOutputTypeDef = TypedDict(
+    "GetBucketRequestPaymentOutputTypeDef",
+    {
+        "Payer": PayerType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketRequestPaymentRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketRequestPaymentRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketRequestPaymentRequestRequestTypeDef = TypedDict(
@@ -2165,14 +2247,23 @@
 
 class GetBucketTaggingRequestRequestTypeDef(
     _RequiredGetBucketTaggingRequestRequestTypeDef, _OptionalGetBucketTaggingRequestRequestTypeDef
 ):
     pass
 
 
+GetBucketVersioningOutputTypeDef = TypedDict(
+    "GetBucketVersioningOutputTypeDef",
+    {
+        "Status": BucketVersioningStatusType,
+        "MFADelete": MFADeleteStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketVersioningRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketVersioningRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketVersioningRequestRequestTypeDef = TypedDict(
@@ -2359,14 +2450,57 @@
 class GetObjectLockConfigurationRequestRequestTypeDef(
     _RequiredGetObjectLockConfigurationRequestRequestTypeDef,
     _OptionalGetObjectLockConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
+GetObjectOutputTypeDef = TypedDict(
+    "GetObjectOutputTypeDef",
+    {
+        "Body": StreamingBody,
+        "DeleteMarker": bool,
+        "AcceptRanges": str,
+        "Expiration": str,
+        "Restore": str,
+        "LastModified": datetime,
+        "ContentLength": int,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "MissingMeta": int,
+        "VersionId": str,
+        "CacheControl": str,
+        "ContentDisposition": str,
+        "ContentEncoding": str,
+        "ContentLanguage": str,
+        "ContentRange": str,
+        "ContentType": str,
+        "Expires": datetime,
+        "WebsiteRedirectLocation": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "Metadata": Dict[str, str],
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "StorageClass": StorageClassType,
+        "RequestCharged": Literal["requester"],
+        "ReplicationStatus": ReplicationStatusType,
+        "PartsCount": int,
+        "TagCount": int,
+        "ObjectLockMode": ObjectLockModeType,
+        "ObjectLockRetainUntilDate": datetime,
+        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetObjectRequestObjectGetTypeDef = TypedDict(
     "GetObjectRequestObjectGetTypeDef",
     {
         "IfMatch": str,
         "IfModifiedSince": Union[datetime, str],
         "IfNoneMatch": str,
         "IfUnmodifiedSince": Union[datetime, str],
@@ -2534,14 +2668,23 @@
 
 class GetObjectTaggingRequestRequestTypeDef(
     _RequiredGetObjectTaggingRequestRequestTypeDef, _OptionalGetObjectTaggingRequestRequestTypeDef
 ):
     pass
 
 
+GetObjectTorrentOutputTypeDef = TypedDict(
+    "GetObjectTorrentOutputTypeDef",
+    {
+        "Body": StreamingBody,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetObjectTorrentRequestRequestTypeDef = TypedDict(
     "_RequiredGetObjectTorrentRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
 )
@@ -2649,14 +2792,55 @@
 
 class HeadBucketRequestRequestTypeDef(
     _RequiredHeadBucketRequestRequestTypeDef, _OptionalHeadBucketRequestRequestTypeDef
 ):
     pass
 
 
+HeadObjectOutputTypeDef = TypedDict(
+    "HeadObjectOutputTypeDef",
+    {
+        "DeleteMarker": bool,
+        "AcceptRanges": str,
+        "Expiration": str,
+        "Restore": str,
+        "ArchiveStatus": ArchiveStatusType,
+        "LastModified": datetime,
+        "ContentLength": int,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ETag": str,
+        "MissingMeta": int,
+        "VersionId": str,
+        "CacheControl": str,
+        "ContentDisposition": str,
+        "ContentEncoding": str,
+        "ContentLanguage": str,
+        "ContentType": str,
+        "Expires": datetime,
+        "WebsiteRedirectLocation": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "Metadata": Dict[str, str],
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "StorageClass": StorageClassType,
+        "RequestCharged": Literal["requester"],
+        "ReplicationStatus": ReplicationStatusType,
+        "PartsCount": int,
+        "ObjectLockMode": ObjectLockModeType,
+        "ObjectLockRetainUntilDate": datetime,
+        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HeadObjectRequestObjectVersionHeadTypeDef = TypedDict(
     "HeadObjectRequestObjectVersionHeadTypeDef",
     {
         "IfMatch": str,
         "IfModifiedSince": Union[datetime, str],
         "IfNoneMatch": str,
         "IfUnmodifiedSince": Union[datetime, str],
@@ -2702,14 +2886,31 @@
 
 class HeadObjectRequestRequestTypeDef(
     _RequiredHeadObjectRequestRequestTypeDef, _OptionalHeadObjectRequestRequestTypeDef
 ):
     pass
 
 
+IndexDocumentResponseMetadataTypeDef = TypedDict(
+    "IndexDocumentResponseMetadataTypeDef",
+    {
+        "Suffix": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InitiatorResponseMetadataTypeDef = TypedDict(
+    "InitiatorResponseMetadataTypeDef",
+    {
+        "ID": str,
+        "DisplayName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InitiatorTypeDef = TypedDict(
     "InitiatorTypeDef",
     {
         "ID": str,
         "DisplayName": str,
     },
     total=False,
@@ -2886,24 +3087,41 @@
 class ListBucketMetricsConfigurationsRequestRequestTypeDef(
     _RequiredListBucketMetricsConfigurationsRequestRequestTypeDef,
     _OptionalListBucketMetricsConfigurationsRequestRequestTypeDef,
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Bucket": str,
+    },
+)
+_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef(
+    _RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
+    _OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMultipartUploadsRequestRequestTypeDef = TypedDict(
     "_RequiredListMultipartUploadsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListMultipartUploadsRequestRequestTypeDef = TypedDict(
@@ -2912,26 +3130,54 @@
         "Delimiter": str,
         "EncodingType": Literal["url"],
         "KeyMarker": str,
         "MaxUploads": int,
         "Prefix": str,
         "UploadIdMarker": str,
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 
 class ListMultipartUploadsRequestRequestTypeDef(
     _RequiredListMultipartUploadsRequestRequestTypeDef,
     _OptionalListMultipartUploadsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListObjectVersionsRequestListObjectVersionsPaginateTypeDef(
+    _RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
+    _OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListObjectVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectVersionsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectVersionsRequestRequestTypeDef = TypedDict(
@@ -2940,26 +3186,54 @@
         "Delimiter": str,
         "EncodingType": Literal["url"],
         "KeyMarker": str,
         "MaxKeys": int,
         "Prefix": str,
         "VersionIdMarker": str,
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 
 class ListObjectVersionsRequestRequestTypeDef(
     _RequiredListObjectVersionsRequestRequestTypeDef,
     _OptionalListObjectVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectsRequestListObjectsPaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectsRequestListObjectsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListObjectsRequestListObjectsPaginateTypeDef(
+    _RequiredListObjectsRequestListObjectsPaginateTypeDef,
+    _OptionalListObjectsRequestListObjectsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectsRequestRequestTypeDef = TypedDict(
@@ -2979,14 +3253,43 @@
 
 class ListObjectsRequestRequestTypeDef(
     _RequiredListObjectsRequestRequestTypeDef, _OptionalListObjectsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
+    "_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
+    "_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "FetchOwner": bool,
+        "StartAfter": str,
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListObjectsV2RequestListObjectsV2PaginateTypeDef(
+    _RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef,
+    _OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef,
+):
+    pass
+
+
 _RequiredListObjectsV2RequestRequestTypeDef = TypedDict(
     "_RequiredListObjectsV2RequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectsV2RequestRequestTypeDef = TypedDict(
@@ -3023,14 +3326,43 @@
         "ChecksumCRC32C": str,
         "ChecksumSHA1": str,
         "ChecksumSHA256": str,
     },
     total=False,
 )
 
+_RequiredListPartsRequestListPartsPaginateTypeDef = TypedDict(
+    "_RequiredListPartsRequestListPartsPaginateTypeDef",
+    {
+        "Bucket": str,
+        "Key": str,
+        "UploadId": str,
+    },
+)
+_OptionalListPartsRequestListPartsPaginateTypeDef = TypedDict(
+    "_OptionalListPartsRequestListPartsPaginateTypeDef",
+    {
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKey": str,
+        "SSECustomerKeyMD5": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPartsRequestListPartsPaginateTypeDef(
+    _RequiredListPartsRequestListPartsPaginateTypeDef,
+    _OptionalListPartsRequestListPartsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPartsRequestRequestTypeDef = TypedDict(
     "_RequiredListPartsRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
         "UploadId": str,
     },
@@ -3069,21 +3401,14 @@
     "ReplicationTimeValueTypeDef",
     {
         "Minutes": int,
     },
     total=False,
 )
 
-MultipartUploadPartRequestTypeDef = TypedDict(
-    "MultipartUploadPartRequestTypeDef",
-    {
-        "part_number": str,
-    },
-)
-
 QueueConfigurationDeprecatedTypeDef = TypedDict(
     "QueueConfigurationDeprecatedTypeDef",
     {
         "Id": str,
         "Event": EventType,
         "Events": List[EventType],
         "Queue": str,
@@ -3144,35 +3469,14 @@
 
 class ObjectDownloadFileobjRequestTypeDef(
     _RequiredObjectDownloadFileobjRequestTypeDef, _OptionalObjectDownloadFileobjRequestTypeDef
 ):
     pass
 
 
-ObjectMultipartUploadRequestTypeDef = TypedDict(
-    "ObjectMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ObjectSummaryMultipartUploadRequestTypeDef = TypedDict(
-    "ObjectSummaryMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ObjectSummaryVersionRequestTypeDef = TypedDict(
-    "ObjectSummaryVersionRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
 _RequiredObjectUploadFileRequestTypeDef = TypedDict(
     "_RequiredObjectUploadFileRequestTypeDef",
     {
         "Filename": str,
     },
 )
 _OptionalObjectUploadFileRequestTypeDef = TypedDict(
@@ -3211,28 +3515,40 @@
 
 class ObjectUploadFileobjRequestTypeDef(
     _RequiredObjectUploadFileobjRequestTypeDef, _OptionalObjectUploadFileobjRequestTypeDef
 ):
     pass
 
 
-ObjectVersionRequestTypeDef = TypedDict(
-    "ObjectVersionRequestTypeDef",
+OwnerResponseMetadataTypeDef = TypedDict(
+    "OwnerResponseMetadataTypeDef",
     {
-        "id": str,
+        "DisplayName": str,
+        "ID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OwnershipControlsRuleTypeDef = TypedDict(
     "OwnershipControlsRuleTypeDef",
     {
         "ObjectOwnership": ObjectOwnershipType,
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
 ProgressTypeDef = TypedDict(
     "ProgressTypeDef",
     {
         "BytesScanned": int,
         "BytesProcessed": int,
         "BytesReturned": int,
     },
@@ -3319,14 +3635,59 @@
         "ChecksumAlgorithm": ChecksumAlgorithmType,
         "MFA": str,
         "ExpectedBucketOwner": str,
     },
     total=False,
 )
 
+PutObjectAclOutputTypeDef = TypedDict(
+    "PutObjectAclOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectLegalHoldOutputTypeDef = TypedDict(
+    "PutObjectLegalHoldOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectLockConfigurationOutputTypeDef = TypedDict(
+    "PutObjectLockConfigurationOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectOutputTypeDef = TypedDict(
+    "PutObjectOutputTypeDef",
+    {
+        "Expiration": str,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "VersionId": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "SSEKMSEncryptionContext": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutObjectRequestBucketPutObjectTypeDef = TypedDict(
     "_RequiredPutObjectRequestBucketPutObjectTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalPutObjectRequestBucketPutObjectTypeDef = TypedDict(
@@ -3514,22 +3875,47 @@
 
 class PutObjectRequestRequestTypeDef(
     _RequiredPutObjectRequestRequestTypeDef, _OptionalPutObjectRequestRequestTypeDef
 ):
     pass
 
 
+PutObjectRetentionOutputTypeDef = TypedDict(
+    "PutObjectRetentionOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectTaggingOutputTypeDef = TypedDict(
+    "PutObjectTaggingOutputTypeDef",
+    {
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecordsEventTypeDef = TypedDict(
     "RecordsEventTypeDef",
     {
         "Payload": bytes,
     },
     total=False,
 )
 
+RedirectAllRequestsToResponseMetadataTypeDef = TypedDict(
+    "RedirectAllRequestsToResponseMetadataTypeDef",
+    {
+        "HostName": str,
+        "Protocol": ProtocolType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedirectTypeDef = TypedDict(
     "RedirectTypeDef",
     {
         "HostName": str,
         "HttpRedirectCode": str,
         "Protocol": ProtocolType,
         "ReplaceKeyPrefixWith": str,
@@ -3549,14 +3935,34 @@
     "RequestProgressTypeDef",
     {
         "Enabled": bool,
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
+RestoreObjectOutputTypeDef = TypedDict(
+    "RestoreObjectOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "RestoreOutputPath": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ScanRangeTypeDef = TypedDict(
     "ScanRangeTypeDef",
     {
         "Start": int,
         "End": int,
     },
     total=False,
@@ -3579,150 +3985,14 @@
 
 class ServerSideEncryptionByDefaultTypeDef(
     _RequiredServerSideEncryptionByDefaultTypeDef, _OptionalServerSideEncryptionByDefaultTypeDef
 ):
     pass
 
 
-ServiceResourceBucketAclRequestTypeDef = TypedDict(
-    "ServiceResourceBucketAclRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketCorsRequestTypeDef = TypedDict(
-    "ServiceResourceBucketCorsRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLifecycleConfigurationRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLifecycleConfigurationRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLifecycleRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLifecycleRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLoggingRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLoggingRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketNotificationRequestTypeDef = TypedDict(
-    "ServiceResourceBucketNotificationRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceBucketPolicyRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketRequestPaymentRequestTypeDef = TypedDict(
-    "ServiceResourceBucketRequestPaymentRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketRequestTypeDef = TypedDict(
-    "ServiceResourceBucketRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceBucketTaggingRequestTypeDef = TypedDict(
-    "ServiceResourceBucketTaggingRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketVersioningRequestTypeDef = TypedDict(
-    "ServiceResourceBucketVersioningRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketWebsiteRequestTypeDef = TypedDict(
-    "ServiceResourceBucketWebsiteRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceMultipartUploadPartRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadPartRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "multipart_upload_id": str,
-        "part_number": str,
-    },
-)
-
-ServiceResourceMultipartUploadRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "id": str,
-    },
-)
-
-ServiceResourceObjectAclRequestTypeDef = TypedDict(
-    "ServiceResourceObjectAclRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-    },
-)
-
-ServiceResourceObjectRequestTypeDef = TypedDict(
-    "ServiceResourceObjectRequestTypeDef",
-    {
-        "bucket_name": str,
-        "key": str,
-    },
-)
-
-ServiceResourceObjectSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceObjectSummaryRequestTypeDef",
-    {
-        "bucket_name": str,
-        "key": str,
-    },
-)
-
-ServiceResourceObjectVersionRequestTypeDef = TypedDict(
-    "ServiceResourceObjectVersionRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "id": str,
-    },
-)
-
 SseKmsEncryptedObjectsTypeDef = TypedDict(
     "SseKmsEncryptedObjectsTypeDef",
     {
         "Status": SseKmsEncryptedObjectsStatusType,
     },
 )
 
@@ -3732,14 +4002,32 @@
         "BytesScanned": int,
         "BytesProcessed": int,
         "BytesReturned": int,
     },
     total=False,
 )
 
+UploadPartOutputTypeDef = TypedDict(
+    "UploadPartOutputTypeDef",
+    {
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UploadPartRequestMultipartUploadPartUploadTypeDef = TypedDict(
     "UploadPartRequestMultipartUploadPartUploadTypeDef",
     {
         "Body": Union[str, bytes, IO[Any], StreamingBody],
         "ContentLength": int,
         "ContentMD5": str,
         "ChecksumAlgorithm": ChecksumAlgorithmType,
@@ -3848,361 +4136,14 @@
 class WriteGetObjectResponseRequestRequestTypeDef(
     _RequiredWriteGetObjectResponseRequestRequestTypeDef,
     _OptionalWriteGetObjectResponseRequestRequestTypeDef,
 ):
     pass
 
 
-AbortMultipartUploadOutputTypeDef = TypedDict(
-    "AbortMultipartUploadOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteMultipartUploadOutputTypeDef = TypedDict(
-    "CompleteMultipartUploadOutputTypeDef",
-    {
-        "Location": str,
-        "Bucket": str,
-        "Key": str,
-        "Expiration": str,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "VersionId": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBucketOutputTypeDef = TypedDict(
-    "CreateBucketOutputTypeDef",
-    {
-        "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMultipartUploadOutputTypeDef = TypedDict(
-    "CreateMultipartUploadOutputTypeDef",
-    {
-        "AbortDate": datetime,
-        "AbortRuleId": str,
-        "Bucket": str,
-        "Key": str,
-        "UploadId": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "SSEKMSEncryptionContext": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ChecksumAlgorithm": ChecksumAlgorithmType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteObjectOutputTypeDef = TypedDict(
-    "DeleteObjectOutputTypeDef",
-    {
-        "DeleteMarker": bool,
-        "VersionId": str,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteObjectTaggingOutputTypeDef = TypedDict(
-    "DeleteObjectTaggingOutputTypeDef",
-    {
-        "VersionId": str,
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
-ErrorDocumentResponseMetadataTypeDef = TypedDict(
-    "ErrorDocumentResponseMetadataTypeDef",
-    {
-        "Key": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketAccelerateConfigurationOutputTypeDef = TypedDict(
-    "GetBucketAccelerateConfigurationOutputTypeDef",
-    {
-        "Status": BucketAccelerateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketLocationOutputTypeDef = TypedDict(
-    "GetBucketLocationOutputTypeDef",
-    {
-        "LocationConstraint": BucketLocationConstraintType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketPolicyOutputTypeDef = TypedDict(
-    "GetBucketPolicyOutputTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketRequestPaymentOutputTypeDef = TypedDict(
-    "GetBucketRequestPaymentOutputTypeDef",
-    {
-        "Payer": PayerType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketVersioningOutputTypeDef = TypedDict(
-    "GetBucketVersioningOutputTypeDef",
-    {
-        "Status": BucketVersioningStatusType,
-        "MFADelete": MFADeleteStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectOutputTypeDef = TypedDict(
-    "GetObjectOutputTypeDef",
-    {
-        "Body": StreamingBody,
-        "DeleteMarker": bool,
-        "AcceptRanges": str,
-        "Expiration": str,
-        "Restore": str,
-        "LastModified": datetime,
-        "ContentLength": int,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "MissingMeta": int,
-        "VersionId": str,
-        "CacheControl": str,
-        "ContentDisposition": str,
-        "ContentEncoding": str,
-        "ContentLanguage": str,
-        "ContentRange": str,
-        "ContentType": str,
-        "Expires": datetime,
-        "WebsiteRedirectLocation": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "Metadata": Dict[str, str],
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "StorageClass": StorageClassType,
-        "RequestCharged": Literal["requester"],
-        "ReplicationStatus": ReplicationStatusType,
-        "PartsCount": int,
-        "TagCount": int,
-        "ObjectLockMode": ObjectLockModeType,
-        "ObjectLockRetainUntilDate": datetime,
-        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectTorrentOutputTypeDef = TypedDict(
-    "GetObjectTorrentOutputTypeDef",
-    {
-        "Body": StreamingBody,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-HeadObjectOutputTypeDef = TypedDict(
-    "HeadObjectOutputTypeDef",
-    {
-        "DeleteMarker": bool,
-        "AcceptRanges": str,
-        "Expiration": str,
-        "Restore": str,
-        "ArchiveStatus": ArchiveStatusType,
-        "LastModified": datetime,
-        "ContentLength": int,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ETag": str,
-        "MissingMeta": int,
-        "VersionId": str,
-        "CacheControl": str,
-        "ContentDisposition": str,
-        "ContentEncoding": str,
-        "ContentLanguage": str,
-        "ContentType": str,
-        "Expires": datetime,
-        "WebsiteRedirectLocation": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "Metadata": Dict[str, str],
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "StorageClass": StorageClassType,
-        "RequestCharged": Literal["requester"],
-        "ReplicationStatus": ReplicationStatusType,
-        "PartsCount": int,
-        "ObjectLockMode": ObjectLockModeType,
-        "ObjectLockRetainUntilDate": datetime,
-        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IndexDocumentResponseMetadataTypeDef = TypedDict(
-    "IndexDocumentResponseMetadataTypeDef",
-    {
-        "Suffix": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiatorResponseMetadataTypeDef = TypedDict(
-    "InitiatorResponseMetadataTypeDef",
-    {
-        "ID": str,
-        "DisplayName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-OwnerResponseMetadataTypeDef = TypedDict(
-    "OwnerResponseMetadataTypeDef",
-    {
-        "DisplayName": str,
-        "ID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectAclOutputTypeDef = TypedDict(
-    "PutObjectAclOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectLegalHoldOutputTypeDef = TypedDict(
-    "PutObjectLegalHoldOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectLockConfigurationOutputTypeDef = TypedDict(
-    "PutObjectLockConfigurationOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectOutputTypeDef = TypedDict(
-    "PutObjectOutputTypeDef",
-    {
-        "Expiration": str,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "VersionId": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "SSEKMSEncryptionContext": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectRetentionOutputTypeDef = TypedDict(
-    "PutObjectRetentionOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectTaggingOutputTypeDef = TypedDict(
-    "PutObjectTaggingOutputTypeDef",
-    {
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RedirectAllRequestsToResponseMetadataTypeDef = TypedDict(
-    "RedirectAllRequestsToResponseMetadataTypeDef",
-    {
-        "HostName": str,
-        "Protocol": ProtocolType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreObjectOutputTypeDef = TypedDict(
-    "RestoreObjectOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "RestoreOutputPath": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadPartOutputTypeDef = TypedDict(
-    "UploadPartOutputTypeDef",
-    {
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPutBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
         "AccelerateConfiguration": AccelerateConfigurationTypeDef,
     },
 )
@@ -4274,24 +4215,24 @@
     total=False,
 )
 
 GetBucketTaggingOutputTypeDef = TypedDict(
     "GetBucketTaggingOutputTypeDef",
     {
         "TagSet": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectTaggingOutputTypeDef = TypedDict(
     "GetObjectTaggingOutputTypeDef",
     {
         "VersionId": str,
         "TagSet": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntelligentTieringAndOperatorTypeDef = TypedDict(
     "IntelligentTieringAndOperatorTypeDef",
     {
         "Prefix": str,
@@ -4553,30 +4494,30 @@
 
 
 ListBucketsOutputTypeDef = TypedDict(
     "ListBucketsOutputTypeDef",
     {
         "Buckets": List[BucketTypeDef],
         "Owner": OwnerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CORSConfigurationTypeDef = TypedDict(
     "CORSConfigurationTypeDef",
     {
         "CORSRules": Sequence[CORSRuleTypeDef],
     },
 )
 
 GetBucketCorsOutputTypeDef = TypedDict(
     "GetBucketCorsOutputTypeDef",
     {
         "CORSRules": List[CORSRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompletedMultipartUploadTypeDef = TypedDict(
     "CompletedMultipartUploadTypeDef",
     {
         "Parts": Sequence[CompletedPartTypeDef],
@@ -4594,30 +4535,30 @@
         "ServerSideEncryption": ServerSideEncryptionType,
         "SSECustomerAlgorithm": str,
         "SSECustomerKeyMD5": str,
         "SSEKMSKeyId": str,
         "SSEKMSEncryptionContext": str,
         "BucketKeyEnabled": bool,
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadPartCopyOutputTypeDef = TypedDict(
     "UploadPartCopyOutputTypeDef",
     {
         "CopySourceVersionId": str,
         "CopyPartResult": CopyPartResultTypeDef,
         "ServerSideEncryption": ServerSideEncryptionType,
         "SSECustomerAlgorithm": str,
         "SSECustomerKeyMD5": str,
         "SSEKMSKeyId": str,
         "BucketKeyEnabled": bool,
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketRequestBucketCreateTypeDef = TypedDict(
     "CreateBucketRequestBucketCreateTypeDef",
     {
         "ACL": BucketCannedACLType,
@@ -4702,15 +4643,15 @@
 
 DeleteObjectsOutputTypeDef = TypedDict(
     "DeleteObjectsOutputTypeDef",
     {
         "Deleted": List[DeletedObjectTypeDef],
         "RequestCharged": Literal["requester"],
         "Errors": List[ErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteTypeDef = TypedDict(
     "_RequiredDeleteTypeDef",
     {
         "Objects": Sequence[ObjectIdentifierTypeDef],
@@ -4737,15 +4678,15 @@
     total=False,
 )
 
 GetBucketPolicyStatusOutputTypeDef = TypedDict(
     "GetBucketPolicyStatusOutputTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAttributesPartsTypeDef = TypedDict(
     "GetObjectAttributesPartsTypeDef",
     {
         "TotalPartsCount": int,
@@ -4758,15 +4699,15 @@
     total=False,
 )
 
 GetObjectLegalHoldOutputTypeDef = TypedDict(
     "GetObjectLegalHoldOutputTypeDef",
     {
         "LegalHold": ObjectLockLegalHoldTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectLegalHoldRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectLegalHoldRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -4794,15 +4735,15 @@
     pass
 
 
 GetObjectRetentionOutputTypeDef = TypedDict(
     "GetObjectRetentionOutputTypeDef",
     {
         "Retention": ObjectLockRetentionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectRetentionRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectRetentionRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -4831,15 +4772,15 @@
     pass
 
 
 GetPublicAccessBlockOutputTypeDef = TypedDict(
     "GetPublicAccessBlockOutputTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPublicAccessBlockRequestRequestTypeDef = TypedDict(
     "_RequiredPutPublicAccessBlockRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -5064,151 +5005,14 @@
 )
 
 
 class RuleTypeDef(_RequiredRuleTypeDef, _OptionalRuleTypeDef):
     pass
 
 
-_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef(
-    _RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-    _OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectVersionsRequestListObjectVersionsPaginateTypeDef(
-    _RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-    _OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectsRequestListObjectsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectsRequestListObjectsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectsRequestListObjectsPaginateTypeDef(
-    _RequiredListObjectsRequestListObjectsPaginateTypeDef,
-    _OptionalListObjectsRequestListObjectsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
-    "_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
-    "_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "FetchOwner": bool,
-        "StartAfter": str,
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectsV2RequestListObjectsV2PaginateTypeDef(
-    _RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef,
-    _OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPartsRequestListPartsPaginateTypeDef = TypedDict(
-    "_RequiredListPartsRequestListPartsPaginateTypeDef",
-    {
-        "Bucket": str,
-        "Key": str,
-        "UploadId": str,
-    },
-)
-_OptionalListPartsRequestListPartsPaginateTypeDef = TypedDict(
-    "_OptionalListPartsRequestListPartsPaginateTypeDef",
-    {
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKey": str,
-        "SSECustomerKeyMD5": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPartsRequestListPartsPaginateTypeDef(
-    _RequiredListPartsRequestListPartsPaginateTypeDef,
-    _OptionalListPartsRequestListPartsPaginateTypeDef,
-):
-    pass
-
-
 ListPartsOutputTypeDef = TypedDict(
     "ListPartsOutputTypeDef",
     {
         "AbortDate": datetime,
         "AbortRuleId": str,
         "Bucket": str,
         "Key": str,
@@ -5219,15 +5023,15 @@
         "IsTruncated": bool,
         "Parts": List[PartTypeDef],
         "Initiator": InitiatorTypeDef,
         "Owner": OwnerTypeDef,
         "StorageClass": StorageClassType,
         "RequestCharged": Literal["requester"],
         "ChecksumAlgorithm": ChecksumAlgorithmType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricsTypeDef = TypedDict(
     "_RequiredMetricsTypeDef",
     {
         "Status": MetricsStatusType,
@@ -5256,15 +5060,15 @@
 
 NotificationConfigurationDeprecatedResponseMetadataTypeDef = TypedDict(
     "NotificationConfigurationDeprecatedResponseMetadataTypeDef",
     {
         "TopicConfiguration": TopicConfigurationDeprecatedTypeDef,
         "QueueConfiguration": QueueConfigurationDeprecatedTypeDef,
         "CloudFunctionConfiguration": CloudFunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationConfigurationDeprecatedTypeDef = TypedDict(
     "NotificationConfigurationDeprecatedTypeDef",
     {
         "TopicConfiguration": TopicConfigurationDeprecatedTypeDef,
@@ -5439,15 +5243,16 @@
         "Contents": List[ObjectTypeDef],
         "Name": str,
         "Prefix": str,
         "Delimiter": str,
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectsV2OutputTypeDef = TypedDict(
     "ListObjectsV2OutputTypeDef",
     {
         "IsTruncated": bool,
@@ -5458,15 +5263,16 @@
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
         "KeyCount": int,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "StartAfter": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectVersionsOutputTypeDef = TypedDict(
     "ListObjectVersionsOutputTypeDef",
     {
         "IsTruncated": bool,
@@ -5478,15 +5284,16 @@
         "DeleteMarkers": List[DeleteMarkerEntryTypeDef],
         "Name": str,
         "Prefix": str,
         "Delimiter": str,
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalyticsFilterTypeDef = TypedDict(
     "AnalyticsFilterTypeDef",
     {
         "Prefix": str,
@@ -5793,15 +5600,15 @@
         "VersionId": str,
         "RequestCharged": Literal["requester"],
         "ETag": str,
         "Checksum": ChecksumTypeDef,
         "ObjectParts": GetObjectAttributesPartsTypeDef,
         "StorageClass": StorageClassType,
         "ObjectSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccessControlPolicyTypeDef = TypedDict(
     "AccessControlPolicyTypeDef",
     {
         "Grants": Sequence[GrantTypeDef],
@@ -5811,25 +5618,25 @@
 )
 
 GetBucketAclOutputTypeDef = TypedDict(
     "GetBucketAclOutputTypeDef",
     {
         "Owner": OwnerTypeDef,
         "Grants": List[GrantTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAclOutputTypeDef = TypedDict(
     "GetObjectAclOutputTypeDef",
     {
         "Owner": OwnerTypeDef,
         "Grants": List[GrantTypeDef],
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3LocationTypeDef = TypedDict(
     "_RequiredS3LocationTypeDef",
     {
         "BucketName": str,
@@ -5856,15 +5663,15 @@
 
 LoggingEnabledResponseMetadataTypeDef = TypedDict(
     "LoggingEnabledResponseMetadataTypeDef",
     {
         "TargetBucket": str,
         "TargetGrants": List[TargetGrantTypeDef],
         "TargetPrefix": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLoggingEnabledTypeDef = TypedDict(
     "_RequiredLoggingEnabledTypeDef",
     {
         "TargetBucket": str,
@@ -5895,15 +5702,16 @@
         "Delimiter": str,
         "NextUploadIdMarker": str,
         "MaxUploads": int,
         "IsTruncated": bool,
         "Uploads": List[MultipartUploadTypeDef],
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInventoryS3BucketDestinationTypeDef = TypedDict(
     "_RequiredInventoryS3BucketDestinationTypeDef",
     {
         "Bucket": str,
@@ -5969,15 +5777,15 @@
     },
 )
 
 GetBucketLifecycleOutputTypeDef = TypedDict(
     "GetBucketLifecycleOutputTypeDef",
     {
         "Rules": List[RuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleConfigurationTypeDef = TypedDict(
     "LifecycleConfigurationTypeDef",
     {
         "Rules": Sequence[RuleTypeDef],
@@ -6032,15 +5840,15 @@
     pass
 
 
 GetBucketOwnershipControlsOutputTypeDef = TypedDict(
     "GetBucketOwnershipControlsOutputTypeDef",
     {
         "OwnershipControls": OwnershipControlsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketOwnershipControlsRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketOwnershipControlsRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6067,15 +5875,15 @@
 GetBucketWebsiteOutputTypeDef = TypedDict(
     "GetBucketWebsiteOutputTypeDef",
     {
         "RedirectAllRequestsTo": RedirectAllRequestsToTypeDef,
         "IndexDocument": IndexDocumentTypeDef,
         "ErrorDocument": ErrorDocumentTypeDef,
         "RoutingRules": List[RoutingRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WebsiteConfigurationTypeDef = TypedDict(
     "WebsiteConfigurationTypeDef",
     {
         "ErrorDocument": ErrorDocumentTypeDef,
@@ -6183,15 +5991,15 @@
     total=False,
 )
 
 GetObjectLockConfigurationOutputTypeDef = TypedDict(
     "GetObjectLockConfigurationOutputTypeDef",
     {
         "ObjectLockConfiguration": ObjectLockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectLockConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectLockConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6398,15 +6206,15 @@
     total=False,
 )
 
 GetBucketLoggingOutputTypeDef = TypedDict(
     "GetBucketLoggingOutputTypeDef",
     {
         "LoggingEnabled": LoggingEnabledTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryDestinationTypeDef = TypedDict(
     "InventoryDestinationTypeDef",
     {
         "S3BucketDestination": InventoryS3BucketDestinationTypeDef,
@@ -6519,15 +6327,15 @@
     pass
 
 
 GetBucketEncryptionOutputTypeDef = TypedDict(
     "GetBucketEncryptionOutputTypeDef",
     {
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketEncryptionRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketEncryptionRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6552,34 +6360,34 @@
     pass
 
 
 SelectObjectContentOutputTypeDef = TypedDict(
     "SelectObjectContentOutputTypeDef",
     {
         "Payload": SelectObjectContentEventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketIntelligentTieringConfigurationOutputTypeDef = TypedDict(
     "GetBucketIntelligentTieringConfigurationOutputTypeDef",
     {
         "IntelligentTieringConfiguration": IntelligentTieringConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketIntelligentTieringConfigurationsOutputTypeDef = TypedDict(
     "ListBucketIntelligentTieringConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "IntelligentTieringConfigurationList": List[IntelligentTieringConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBucketIntelligentTieringConfigurationRequestRequestTypeDef = TypedDict(
     "PutBucketIntelligentTieringConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6595,34 +6403,34 @@
     },
 )
 
 GetBucketLifecycleConfigurationOutputTypeDef = TypedDict(
     "GetBucketLifecycleConfigurationOutputTypeDef",
     {
         "Rules": List[LifecycleRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketMetricsConfigurationOutputTypeDef = TypedDict(
     "GetBucketMetricsConfigurationOutputTypeDef",
     {
         "MetricsConfiguration": MetricsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketMetricsConfigurationsOutputTypeDef = TypedDict(
     "ListBucketMetricsConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "MetricsConfigurationList": List[MetricsConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketMetricsConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketMetricsConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6671,15 +6479,15 @@
 NotificationConfigurationResponseMetadataTypeDef = TypedDict(
     "NotificationConfigurationResponseMetadataTypeDef",
     {
         "TopicConfigurations": List[TopicConfigurationTypeDef],
         "QueueConfigurations": List[QueueConfigurationTypeDef],
         "LambdaFunctionConfigurations": List[LambdaFunctionConfigurationTypeDef],
         "EventBridgeConfiguration": Dict[str, Any],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationConfigurationTypeDef = TypedDict(
     "NotificationConfigurationTypeDef",
     {
         "TopicConfigurations": Sequence[TopicConfigurationTypeDef],
@@ -6818,26 +6626,26 @@
     pass
 
 
 GetBucketAnalyticsConfigurationOutputTypeDef = TypedDict(
     "GetBucketAnalyticsConfigurationOutputTypeDef",
     {
         "AnalyticsConfiguration": AnalyticsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketAnalyticsConfigurationsOutputTypeDef = TypedDict(
     "ListBucketAnalyticsConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "AnalyticsConfigurationList": List[AnalyticsConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketAnalyticsConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketAnalyticsConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6958,26 +6766,26 @@
     pass
 
 
 GetBucketInventoryConfigurationOutputTypeDef = TypedDict(
     "GetBucketInventoryConfigurationOutputTypeDef",
     {
         "InventoryConfiguration": InventoryConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketInventoryConfigurationsOutputTypeDef = TypedDict(
     "ListBucketInventoryConfigurationsOutputTypeDef",
     {
         "ContinuationToken": str,
         "InventoryConfigurationList": List[InventoryConfigurationTypeDef],
         "IsTruncated": bool,
         "NextContinuationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketInventoryConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketInventoryConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -7001,15 +6809,15 @@
     pass
 
 
 GetBucketReplicationOutputTypeDef = TypedDict(
     "GetBucketReplicationOutputTypeDef",
     {
         "ReplicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketReplicationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketReplicationRequestRequestTypeDef",
     {
         "Bucket": str,
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/type_defs.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -79,47 +79,49 @@
 try:
     from boto3.s3.transfer import TransferConfig
 except (ModuleNotFoundError, ImportError):
     from builtins import object as TransferConfig
 
 __all__ = (
     "AbortIncompleteMultipartUploadTypeDef",
-    "ResponseMetadataTypeDef",
+    "AbortMultipartUploadOutputTypeDef",
     "AbortMultipartUploadRequestMultipartUploadAbortTypeDef",
     "AbortMultipartUploadRequestRequestTypeDef",
     "AccelerateConfigurationTypeDef",
     "OwnerTypeDef",
     "AccessControlTranslationTypeDef",
     "TagTypeDef",
     "AnalyticsS3BucketDestinationTypeDef",
     "CopySourceTypeDef",
     "BucketDownloadFileRequestTypeDef",
     "BucketDownloadFileobjRequestTypeDef",
-    "BucketObjectRequestTypeDef",
     "BucketTypeDef",
     "BucketUploadFileRequestTypeDef",
     "BucketUploadFileobjRequestTypeDef",
     "CORSRuleTypeDef",
     "CSVInputTypeDef",
     "CSVOutputTypeDef",
     "ChecksumTypeDef",
     "ClientDownloadFileRequestTypeDef",
     "ClientDownloadFileobjRequestTypeDef",
     "ClientGeneratePresignedPostRequestTypeDef",
     "ClientUploadFileRequestTypeDef",
     "ClientUploadFileobjRequestTypeDef",
     "CloudFunctionConfigurationTypeDef",
     "CommonPrefixTypeDef",
+    "CompleteMultipartUploadOutputTypeDef",
     "CompletedPartTypeDef",
     "ConditionTypeDef",
     "CopyObjectResultTypeDef",
     "CopyObjectRequestObjectCopyFromTypeDef",
     "CopyObjectRequestObjectSummaryCopyFromTypeDef",
     "CopyPartResultTypeDef",
     "CreateBucketConfigurationTypeDef",
+    "CreateBucketOutputTypeDef",
+    "CreateMultipartUploadOutputTypeDef",
     "CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef",
     "CreateMultipartUploadRequestObjectSummaryInitiateMultipartUploadTypeDef",
     "CreateMultipartUploadRequestRequestTypeDef",
     "DefaultRetentionTypeDef",
     "DeleteBucketAnalyticsConfigurationRequestRequestTypeDef",
     "DeleteBucketCorsRequestBucketCorsDeleteTypeDef",
     "DeleteBucketCorsRequestRequestTypeDef",
@@ -137,74 +139,88 @@
     "DeleteBucketRequestBucketDeleteTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteBucketTaggingRequestBucketTaggingDeleteTypeDef",
     "DeleteBucketTaggingRequestRequestTypeDef",
     "DeleteBucketWebsiteRequestBucketWebsiteDeleteTypeDef",
     "DeleteBucketWebsiteRequestRequestTypeDef",
     "DeleteMarkerReplicationTypeDef",
+    "DeleteObjectOutputTypeDef",
     "DeleteObjectRequestObjectDeleteTypeDef",
     "DeleteObjectRequestObjectSummaryDeleteTypeDef",
     "DeleteObjectRequestObjectVersionDeleteTypeDef",
     "DeleteObjectRequestRequestTypeDef",
+    "DeleteObjectTaggingOutputTypeDef",
     "DeleteObjectTaggingRequestRequestTypeDef",
     "DeletedObjectTypeDef",
     "ErrorTypeDef",
     "DeletePublicAccessBlockRequestRequestTypeDef",
     "ObjectIdentifierTypeDef",
     "EncryptionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionTypeDef",
+    "ErrorDocumentResponseMetadataTypeDef",
     "ErrorDocumentTypeDef",
     "ExistingObjectReplicationTypeDef",
     "FilterRuleTypeDef",
+    "GetBucketAccelerateConfigurationOutputTypeDef",
     "GetBucketAccelerateConfigurationRequestRequestTypeDef",
     "GetBucketAclRequestRequestTypeDef",
     "GetBucketAnalyticsConfigurationRequestRequestTypeDef",
     "GetBucketCorsRequestRequestTypeDef",
     "GetBucketEncryptionRequestRequestTypeDef",
     "GetBucketIntelligentTieringConfigurationRequestRequestTypeDef",
     "GetBucketInventoryConfigurationRequestRequestTypeDef",
     "GetBucketLifecycleConfigurationRequestRequestTypeDef",
     "GetBucketLifecycleRequestRequestTypeDef",
+    "GetBucketLocationOutputTypeDef",
     "GetBucketLocationRequestRequestTypeDef",
     "GetBucketLoggingRequestRequestTypeDef",
     "GetBucketMetricsConfigurationRequestRequestTypeDef",
     "GetBucketNotificationConfigurationRequestRequestTypeDef",
     "GetBucketOwnershipControlsRequestRequestTypeDef",
+    "GetBucketPolicyOutputTypeDef",
     "GetBucketPolicyRequestRequestTypeDef",
     "PolicyStatusTypeDef",
     "GetBucketPolicyStatusRequestRequestTypeDef",
     "GetBucketReplicationRequestRequestTypeDef",
+    "GetBucketRequestPaymentOutputTypeDef",
     "GetBucketRequestPaymentRequestRequestTypeDef",
     "GetBucketTaggingRequestRequestTypeDef",
+    "GetBucketVersioningOutputTypeDef",
     "GetBucketVersioningRequestRequestTypeDef",
     "IndexDocumentTypeDef",
     "RedirectAllRequestsToTypeDef",
     "GetBucketWebsiteRequestRequestTypeDef",
     "GetObjectAclRequestRequestTypeDef",
     "ObjectPartTypeDef",
     "GetObjectAttributesRequestRequestTypeDef",
     "ObjectLockLegalHoldTypeDef",
     "GetObjectLegalHoldRequestRequestTypeDef",
     "GetObjectLockConfigurationRequestRequestTypeDef",
+    "GetObjectOutputTypeDef",
     "GetObjectRequestObjectGetTypeDef",
     "GetObjectRequestObjectSummaryGetTypeDef",
     "GetObjectRequestObjectVersionGetTypeDef",
     "GetObjectRequestRequestTypeDef",
     "ObjectLockRetentionTypeDef",
     "GetObjectRetentionRequestRequestTypeDef",
     "GetObjectTaggingRequestRequestTypeDef",
+    "GetObjectTorrentOutputTypeDef",
     "GetObjectTorrentRequestRequestTypeDef",
     "PublicAccessBlockConfigurationTypeDef",
     "GetPublicAccessBlockRequestRequestTypeDef",
     "GlacierJobParametersTypeDef",
     "GranteeTypeDef",
     "WaiterConfigTypeDef",
     "HeadBucketRequestRequestTypeDef",
+    "HeadObjectOutputTypeDef",
     "HeadObjectRequestObjectVersionHeadTypeDef",
     "HeadObjectRequestRequestTypeDef",
+    "IndexDocumentResponseMetadataTypeDef",
+    "InitiatorResponseMetadataTypeDef",
     "InitiatorTypeDef",
     "JSONInputTypeDef",
     "TieringTypeDef",
     "InventoryFilterTypeDef",
     "InventoryScheduleTypeDef",
     "SSEKMSTypeDef",
     "JSONOutputTypeDef",
@@ -212,103 +228,68 @@
     "NoncurrentVersionExpirationTypeDef",
     "NoncurrentVersionTransitionTypeDef",
     "TransitionTypeDef",
     "ListBucketAnalyticsConfigurationsRequestRequestTypeDef",
     "ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef",
     "ListBucketInventoryConfigurationsRequestRequestTypeDef",
     "ListBucketMetricsConfigurationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
     "ListMultipartUploadsRequestRequestTypeDef",
+    "ListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
     "ListObjectVersionsRequestRequestTypeDef",
+    "ListObjectsRequestListObjectsPaginateTypeDef",
     "ListObjectsRequestRequestTypeDef",
+    "ListObjectsV2RequestListObjectsV2PaginateTypeDef",
     "ListObjectsV2RequestRequestTypeDef",
     "PartTypeDef",
+    "ListPartsRequestListPartsPaginateTypeDef",
     "ListPartsRequestRequestTypeDef",
     "MetadataEntryTypeDef",
     "ReplicationTimeValueTypeDef",
-    "MultipartUploadPartRequestTypeDef",
     "QueueConfigurationDeprecatedTypeDef",
     "TopicConfigurationDeprecatedTypeDef",
     "ObjectDownloadFileRequestTypeDef",
     "ObjectDownloadFileobjRequestTypeDef",
-    "ObjectMultipartUploadRequestTypeDef",
-    "ObjectSummaryMultipartUploadRequestTypeDef",
-    "ObjectSummaryVersionRequestTypeDef",
     "ObjectUploadFileRequestTypeDef",
     "ObjectUploadFileobjRequestTypeDef",
-    "ObjectVersionRequestTypeDef",
+    "OwnerResponseMetadataTypeDef",
     "OwnershipControlsRuleTypeDef",
+    "PaginatorConfigTypeDef",
     "ProgressTypeDef",
     "PutBucketPolicyRequestBucketPolicyPutTypeDef",
     "PutBucketPolicyRequestRequestTypeDef",
     "RequestPaymentConfigurationTypeDef",
     "PutBucketVersioningRequestBucketVersioningEnableTypeDef",
     "VersioningConfigurationTypeDef",
     "PutBucketVersioningRequestBucketVersioningSuspendTypeDef",
+    "PutObjectAclOutputTypeDef",
+    "PutObjectLegalHoldOutputTypeDef",
+    "PutObjectLockConfigurationOutputTypeDef",
+    "PutObjectOutputTypeDef",
     "PutObjectRequestBucketPutObjectTypeDef",
     "PutObjectRequestObjectPutTypeDef",
     "PutObjectRequestObjectSummaryPutTypeDef",
     "PutObjectRequestRequestTypeDef",
+    "PutObjectRetentionOutputTypeDef",
+    "PutObjectTaggingOutputTypeDef",
     "RecordsEventTypeDef",
+    "RedirectAllRequestsToResponseMetadataTypeDef",
     "RedirectTypeDef",
     "ReplicaModificationsTypeDef",
     "RequestProgressTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreObjectOutputTypeDef",
     "ScanRangeTypeDef",
     "ServerSideEncryptionByDefaultTypeDef",
-    "ServiceResourceBucketAclRequestTypeDef",
-    "ServiceResourceBucketCorsRequestTypeDef",
-    "ServiceResourceBucketLifecycleConfigurationRequestTypeDef",
-    "ServiceResourceBucketLifecycleRequestTypeDef",
-    "ServiceResourceBucketLoggingRequestTypeDef",
-    "ServiceResourceBucketNotificationRequestTypeDef",
-    "ServiceResourceBucketPolicyRequestTypeDef",
-    "ServiceResourceBucketRequestPaymentRequestTypeDef",
-    "ServiceResourceBucketRequestTypeDef",
-    "ServiceResourceBucketTaggingRequestTypeDef",
-    "ServiceResourceBucketVersioningRequestTypeDef",
-    "ServiceResourceBucketWebsiteRequestTypeDef",
-    "ServiceResourceMultipartUploadPartRequestTypeDef",
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    "ServiceResourceObjectAclRequestTypeDef",
-    "ServiceResourceObjectRequestTypeDef",
-    "ServiceResourceObjectSummaryRequestTypeDef",
-    "ServiceResourceObjectVersionRequestTypeDef",
     "SseKmsEncryptedObjectsTypeDef",
     "StatsTypeDef",
+    "UploadPartOutputTypeDef",
     "UploadPartRequestMultipartUploadPartUploadTypeDef",
     "UploadPartRequestRequestTypeDef",
     "WriteGetObjectResponseRequestRequestTypeDef",
-    "AbortMultipartUploadOutputTypeDef",
-    "CompleteMultipartUploadOutputTypeDef",
-    "CreateBucketOutputTypeDef",
-    "CreateMultipartUploadOutputTypeDef",
-    "DeleteObjectOutputTypeDef",
-    "DeleteObjectTaggingOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ErrorDocumentResponseMetadataTypeDef",
-    "GetBucketAccelerateConfigurationOutputTypeDef",
-    "GetBucketLocationOutputTypeDef",
-    "GetBucketPolicyOutputTypeDef",
-    "GetBucketRequestPaymentOutputTypeDef",
-    "GetBucketVersioningOutputTypeDef",
-    "GetObjectOutputTypeDef",
-    "GetObjectTorrentOutputTypeDef",
-    "HeadObjectOutputTypeDef",
-    "IndexDocumentResponseMetadataTypeDef",
-    "InitiatorResponseMetadataTypeDef",
-    "OwnerResponseMetadataTypeDef",
-    "PutObjectAclOutputTypeDef",
-    "PutObjectLegalHoldOutputTypeDef",
-    "PutObjectLockConfigurationOutputTypeDef",
-    "PutObjectOutputTypeDef",
-    "PutObjectRetentionOutputTypeDef",
-    "PutObjectTaggingOutputTypeDef",
-    "RedirectAllRequestsToResponseMetadataTypeDef",
-    "RestoreObjectOutputTypeDef",
-    "UploadPartOutputTypeDef",
     "PutBucketAccelerateConfigurationRequestRequestTypeDef",
     "DeleteMarkerEntryTypeDef",
     "ObjectTypeDef",
     "ObjectVersionTypeDef",
     "AnalyticsAndOperatorTypeDef",
     "GetBucketTaggingOutputTypeDef",
     "GetObjectTaggingOutputTypeDef",
@@ -352,19 +333,14 @@
     "HeadObjectRequestObjectExistsWaitTypeDef",
     "HeadObjectRequestObjectNotExistsWaitTypeDef",
     "MultipartUploadTypeDef",
     "InputSerializationTypeDef",
     "InventoryEncryptionTypeDef",
     "OutputSerializationTypeDef",
     "RuleTypeDef",
-    "ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    "ListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    "ListObjectsRequestListObjectsPaginateTypeDef",
-    "ListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    "ListPartsRequestListPartsPaginateTypeDef",
     "ListPartsOutputTypeDef",
     "MetricsTypeDef",
     "ReplicationTimeTypeDef",
     "NotificationConfigurationDeprecatedResponseMetadataTypeDef",
     "NotificationConfigurationDeprecatedTypeDef",
     "OwnershipControlsTypeDef",
     "ProgressEventTypeDef",
@@ -479,22 +455,19 @@
     "AbortIncompleteMultipartUploadTypeDef",
     {
         "DaysAfterInitiation": int,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AbortMultipartUploadOutputTypeDef = TypedDict(
+    "AbortMultipartUploadOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AbortMultipartUploadRequestMultipartUploadAbortTypeDef = TypedDict(
     "AbortMultipartUploadRequestMultipartUploadAbortTypeDef",
     {
         "RequestPayer": Literal["requester"],
@@ -637,21 +610,14 @@
 )
 
 class BucketDownloadFileobjRequestTypeDef(
     _RequiredBucketDownloadFileobjRequestTypeDef, _OptionalBucketDownloadFileobjRequestTypeDef
 ):
     pass
 
-BucketObjectRequestTypeDef = TypedDict(
-    "BucketObjectRequestTypeDef",
-    {
-        "key": str,
-    },
-)
-
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
     {
         "Name": str,
         "CreationDate": datetime,
     },
     total=False,
@@ -812,15 +778,15 @@
         "Key": str,
     },
 )
 _OptionalClientGeneratePresignedPostRequestTypeDef = TypedDict(
     "_OptionalClientGeneratePresignedPostRequestTypeDef",
     {
         "Fields": Dict[str, Any],
-        "Conditions": List[Any],
+        "Conditions": Union[List[Any], Dict[str, Any]],
         "ExpiresIn": int,
     },
     total=False,
 )
 
 class ClientGeneratePresignedPostRequestTypeDef(
     _RequiredClientGeneratePresignedPostRequestTypeDef,
@@ -890,14 +856,35 @@
     "CommonPrefixTypeDef",
     {
         "Prefix": str,
     },
     total=False,
 )
 
+CompleteMultipartUploadOutputTypeDef = TypedDict(
+    "CompleteMultipartUploadOutputTypeDef",
+    {
+        "Location": str,
+        "Bucket": str,
+        "Key": str,
+        "Expiration": str,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "VersionId": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CompletedPartTypeDef = TypedDict(
     "CompletedPartTypeDef",
     {
         "ETag": str,
         "ChecksumCRC32": str,
         "ChecksumCRC32C": str,
         "ChecksumSHA1": str,
@@ -1059,14 +1046,42 @@
     "CreateBucketConfigurationTypeDef",
     {
         "LocationConstraint": BucketLocationConstraintType,
     },
     total=False,
 )
 
+CreateBucketOutputTypeDef = TypedDict(
+    "CreateBucketOutputTypeDef",
+    {
+        "Location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateMultipartUploadOutputTypeDef = TypedDict(
+    "CreateMultipartUploadOutputTypeDef",
+    {
+        "AbortDate": datetime,
+        "AbortRuleId": str,
+        "Bucket": str,
+        "Key": str,
+        "UploadId": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "SSEKMSEncryptionContext": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ChecksumAlgorithm": ChecksumAlgorithmType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef = TypedDict(
     "CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef",
     {
         "ACL": ObjectCannedACLType,
         "CacheControl": str,
         "ContentDisposition": str,
         "ContentEncoding": str,
@@ -1500,14 +1515,24 @@
     "DeleteMarkerReplicationTypeDef",
     {
         "Status": DeleteMarkerReplicationStatusType,
     },
     total=False,
 )
 
+DeleteObjectOutputTypeDef = TypedDict(
+    "DeleteObjectOutputTypeDef",
+    {
+        "DeleteMarker": bool,
+        "VersionId": str,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteObjectRequestObjectDeleteTypeDef = TypedDict(
     "DeleteObjectRequestObjectDeleteTypeDef",
     {
         "MFA": str,
         "VersionId": str,
         "RequestPayer": Literal["requester"],
         "BypassGovernanceRetention": bool,
@@ -1559,14 +1584,22 @@
 )
 
 class DeleteObjectRequestRequestTypeDef(
     _RequiredDeleteObjectRequestRequestTypeDef, _OptionalDeleteObjectRequestRequestTypeDef
 ):
     pass
 
+DeleteObjectTaggingOutputTypeDef = TypedDict(
+    "DeleteObjectTaggingOutputTypeDef",
+    {
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteObjectTaggingRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteObjectTaggingRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
 )
@@ -1648,14 +1681,21 @@
     "EncryptionConfigurationTypeDef",
     {
         "ReplicaKmsKeyID": str,
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
 _RequiredEncryptionTypeDef = TypedDict(
     "_RequiredEncryptionTypeDef",
     {
         "EncryptionType": ServerSideEncryptionType,
     },
 )
 _OptionalEncryptionTypeDef = TypedDict(
@@ -1666,14 +1706,22 @@
     },
     total=False,
 )
 
 class EncryptionTypeDef(_RequiredEncryptionTypeDef, _OptionalEncryptionTypeDef):
     pass
 
+ErrorDocumentResponseMetadataTypeDef = TypedDict(
+    "ErrorDocumentResponseMetadataTypeDef",
+    {
+        "Key": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorDocumentTypeDef = TypedDict(
     "ErrorDocumentTypeDef",
     {
         "Key": str,
     },
 )
 
@@ -1689,24 +1737,34 @@
     {
         "Name": FilterRuleNameType,
         "Value": str,
     },
     total=False,
 )
 
+GetBucketAccelerateConfigurationOutputTypeDef = TypedDict(
+    "GetBucketAccelerateConfigurationOutputTypeDef",
+    {
+        "Status": BucketAccelerateStatusType,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalGetBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 class GetBucketAccelerateConfigurationRequestRequestTypeDef(
     _RequiredGetBucketAccelerateConfigurationRequestRequestTypeDef,
     _OptionalGetBucketAccelerateConfigurationRequestRequestTypeDef,
@@ -1857,14 +1915,22 @@
 
 class GetBucketLifecycleRequestRequestTypeDef(
     _RequiredGetBucketLifecycleRequestRequestTypeDef,
     _OptionalGetBucketLifecycleRequestRequestTypeDef,
 ):
     pass
 
+GetBucketLocationOutputTypeDef = TypedDict(
+    "GetBucketLocationOutputTypeDef",
+    {
+        "LocationConstraint": BucketLocationConstraintType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketLocationRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketLocationRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketLocationRequestRequestTypeDef = TypedDict(
@@ -1956,14 +2022,22 @@
 
 class GetBucketOwnershipControlsRequestRequestTypeDef(
     _RequiredGetBucketOwnershipControlsRequestRequestTypeDef,
     _OptionalGetBucketOwnershipControlsRequestRequestTypeDef,
 ):
     pass
 
+GetBucketPolicyOutputTypeDef = TypedDict(
+    "GetBucketPolicyOutputTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketPolicyRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketPolicyRequestRequestTypeDef = TypedDict(
@@ -2023,14 +2097,22 @@
 
 class GetBucketReplicationRequestRequestTypeDef(
     _RequiredGetBucketReplicationRequestRequestTypeDef,
     _OptionalGetBucketReplicationRequestRequestTypeDef,
 ):
     pass
 
+GetBucketRequestPaymentOutputTypeDef = TypedDict(
+    "GetBucketRequestPaymentOutputTypeDef",
+    {
+        "Payer": PayerType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketRequestPaymentRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketRequestPaymentRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketRequestPaymentRequestRequestTypeDef = TypedDict(
@@ -2062,14 +2144,23 @@
 )
 
 class GetBucketTaggingRequestRequestTypeDef(
     _RequiredGetBucketTaggingRequestRequestTypeDef, _OptionalGetBucketTaggingRequestRequestTypeDef
 ):
     pass
 
+GetBucketVersioningOutputTypeDef = TypedDict(
+    "GetBucketVersioningOutputTypeDef",
+    {
+        "Status": BucketVersioningStatusType,
+        "MFADelete": MFADeleteStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetBucketVersioningRequestRequestTypeDef = TypedDict(
     "_RequiredGetBucketVersioningRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalGetBucketVersioningRequestRequestTypeDef = TypedDict(
@@ -2242,14 +2333,57 @@
 
 class GetObjectLockConfigurationRequestRequestTypeDef(
     _RequiredGetObjectLockConfigurationRequestRequestTypeDef,
     _OptionalGetObjectLockConfigurationRequestRequestTypeDef,
 ):
     pass
 
+GetObjectOutputTypeDef = TypedDict(
+    "GetObjectOutputTypeDef",
+    {
+        "Body": StreamingBody,
+        "DeleteMarker": bool,
+        "AcceptRanges": str,
+        "Expiration": str,
+        "Restore": str,
+        "LastModified": datetime,
+        "ContentLength": int,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "MissingMeta": int,
+        "VersionId": str,
+        "CacheControl": str,
+        "ContentDisposition": str,
+        "ContentEncoding": str,
+        "ContentLanguage": str,
+        "ContentRange": str,
+        "ContentType": str,
+        "Expires": datetime,
+        "WebsiteRedirectLocation": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "Metadata": Dict[str, str],
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "StorageClass": StorageClassType,
+        "RequestCharged": Literal["requester"],
+        "ReplicationStatus": ReplicationStatusType,
+        "PartsCount": int,
+        "TagCount": int,
+        "ObjectLockMode": ObjectLockModeType,
+        "ObjectLockRetainUntilDate": datetime,
+        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetObjectRequestObjectGetTypeDef = TypedDict(
     "GetObjectRequestObjectGetTypeDef",
     {
         "IfMatch": str,
         "IfModifiedSince": Union[datetime, str],
         "IfNoneMatch": str,
         "IfUnmodifiedSince": Union[datetime, str],
@@ -2411,14 +2545,23 @@
 )
 
 class GetObjectTaggingRequestRequestTypeDef(
     _RequiredGetObjectTaggingRequestRequestTypeDef, _OptionalGetObjectTaggingRequestRequestTypeDef
 ):
     pass
 
+GetObjectTorrentOutputTypeDef = TypedDict(
+    "GetObjectTorrentOutputTypeDef",
+    {
+        "Body": StreamingBody,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetObjectTorrentRequestRequestTypeDef = TypedDict(
     "_RequiredGetObjectTorrentRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
     },
 )
@@ -2518,14 +2661,55 @@
 )
 
 class HeadBucketRequestRequestTypeDef(
     _RequiredHeadBucketRequestRequestTypeDef, _OptionalHeadBucketRequestRequestTypeDef
 ):
     pass
 
+HeadObjectOutputTypeDef = TypedDict(
+    "HeadObjectOutputTypeDef",
+    {
+        "DeleteMarker": bool,
+        "AcceptRanges": str,
+        "Expiration": str,
+        "Restore": str,
+        "ArchiveStatus": ArchiveStatusType,
+        "LastModified": datetime,
+        "ContentLength": int,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ETag": str,
+        "MissingMeta": int,
+        "VersionId": str,
+        "CacheControl": str,
+        "ContentDisposition": str,
+        "ContentEncoding": str,
+        "ContentLanguage": str,
+        "ContentType": str,
+        "Expires": datetime,
+        "WebsiteRedirectLocation": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "Metadata": Dict[str, str],
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "StorageClass": StorageClassType,
+        "RequestCharged": Literal["requester"],
+        "ReplicationStatus": ReplicationStatusType,
+        "PartsCount": int,
+        "ObjectLockMode": ObjectLockModeType,
+        "ObjectLockRetainUntilDate": datetime,
+        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HeadObjectRequestObjectVersionHeadTypeDef = TypedDict(
     "HeadObjectRequestObjectVersionHeadTypeDef",
     {
         "IfMatch": str,
         "IfModifiedSince": Union[datetime, str],
         "IfNoneMatch": str,
         "IfUnmodifiedSince": Union[datetime, str],
@@ -2569,14 +2753,31 @@
 )
 
 class HeadObjectRequestRequestTypeDef(
     _RequiredHeadObjectRequestRequestTypeDef, _OptionalHeadObjectRequestRequestTypeDef
 ):
     pass
 
+IndexDocumentResponseMetadataTypeDef = TypedDict(
+    "IndexDocumentResponseMetadataTypeDef",
+    {
+        "Suffix": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InitiatorResponseMetadataTypeDef = TypedDict(
+    "InitiatorResponseMetadataTypeDef",
+    {
+        "ID": str,
+        "DisplayName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InitiatorTypeDef = TypedDict(
     "InitiatorTypeDef",
     {
         "ID": str,
         "DisplayName": str,
     },
     total=False,
@@ -2745,24 +2946,39 @@
 
 class ListBucketMetricsConfigurationsRequestRequestTypeDef(
     _RequiredListBucketMetricsConfigurationsRequestRequestTypeDef,
     _OptionalListBucketMetricsConfigurationsRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Bucket": str,
+    },
+)
+_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef(
+    _RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
+    _OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
+):
+    pass
+
 _RequiredListMultipartUploadsRequestRequestTypeDef = TypedDict(
     "_RequiredListMultipartUploadsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListMultipartUploadsRequestRequestTypeDef = TypedDict(
@@ -2771,24 +2987,50 @@
         "Delimiter": str,
         "EncodingType": Literal["url"],
         "KeyMarker": str,
         "MaxUploads": int,
         "Prefix": str,
         "UploadIdMarker": str,
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 class ListMultipartUploadsRequestRequestTypeDef(
     _RequiredListMultipartUploadsRequestRequestTypeDef,
     _OptionalListMultipartUploadsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectVersionsRequestListObjectVersionsPaginateTypeDef(
+    _RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
+    _OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListObjectVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectVersionsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectVersionsRequestRequestTypeDef = TypedDict(
@@ -2797,24 +3039,50 @@
         "Delimiter": str,
         "EncodingType": Literal["url"],
         "KeyMarker": str,
         "MaxKeys": int,
         "Prefix": str,
         "VersionIdMarker": str,
         "ExpectedBucketOwner": str,
+        "RequestPayer": Literal["requester"],
     },
     total=False,
 )
 
 class ListObjectVersionsRequestRequestTypeDef(
     _RequiredListObjectVersionsRequestRequestTypeDef,
     _OptionalListObjectVersionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectsRequestListObjectsPaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectsRequestListObjectsPaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectsRequestListObjectsPaginateTypeDef(
+    _RequiredListObjectsRequestListObjectsPaginateTypeDef,
+    _OptionalListObjectsRequestListObjectsPaginateTypeDef,
+):
+    pass
+
 _RequiredListObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectsRequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectsRequestRequestTypeDef = TypedDict(
@@ -2832,14 +3100,41 @@
 )
 
 class ListObjectsRequestRequestTypeDef(
     _RequiredListObjectsRequestRequestTypeDef, _OptionalListObjectsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
+    "_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef",
+    {
+        "Bucket": str,
+    },
+)
+_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
+    "_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef",
+    {
+        "Delimiter": str,
+        "EncodingType": Literal["url"],
+        "Prefix": str,
+        "FetchOwner": bool,
+        "StartAfter": str,
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectsV2RequestListObjectsV2PaginateTypeDef(
+    _RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef,
+    _OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef,
+):
+    pass
+
 _RequiredListObjectsV2RequestRequestTypeDef = TypedDict(
     "_RequiredListObjectsV2RequestRequestTypeDef",
     {
         "Bucket": str,
     },
 )
 _OptionalListObjectsV2RequestRequestTypeDef = TypedDict(
@@ -2874,14 +3169,41 @@
         "ChecksumCRC32C": str,
         "ChecksumSHA1": str,
         "ChecksumSHA256": str,
     },
     total=False,
 )
 
+_RequiredListPartsRequestListPartsPaginateTypeDef = TypedDict(
+    "_RequiredListPartsRequestListPartsPaginateTypeDef",
+    {
+        "Bucket": str,
+        "Key": str,
+        "UploadId": str,
+    },
+)
+_OptionalListPartsRequestListPartsPaginateTypeDef = TypedDict(
+    "_OptionalListPartsRequestListPartsPaginateTypeDef",
+    {
+        "RequestPayer": Literal["requester"],
+        "ExpectedBucketOwner": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKey": str,
+        "SSECustomerKeyMD5": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPartsRequestListPartsPaginateTypeDef(
+    _RequiredListPartsRequestListPartsPaginateTypeDef,
+    _OptionalListPartsRequestListPartsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPartsRequestRequestTypeDef = TypedDict(
     "_RequiredListPartsRequestRequestTypeDef",
     {
         "Bucket": str,
         "Key": str,
         "UploadId": str,
     },
@@ -2918,21 +3240,14 @@
     "ReplicationTimeValueTypeDef",
     {
         "Minutes": int,
     },
     total=False,
 )
 
-MultipartUploadPartRequestTypeDef = TypedDict(
-    "MultipartUploadPartRequestTypeDef",
-    {
-        "part_number": str,
-    },
-)
-
 QueueConfigurationDeprecatedTypeDef = TypedDict(
     "QueueConfigurationDeprecatedTypeDef",
     {
         "Id": str,
         "Event": EventType,
         "Events": List[EventType],
         "Queue": str,
@@ -2989,35 +3304,14 @@
 )
 
 class ObjectDownloadFileobjRequestTypeDef(
     _RequiredObjectDownloadFileobjRequestTypeDef, _OptionalObjectDownloadFileobjRequestTypeDef
 ):
     pass
 
-ObjectMultipartUploadRequestTypeDef = TypedDict(
-    "ObjectMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ObjectSummaryMultipartUploadRequestTypeDef = TypedDict(
-    "ObjectSummaryMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ObjectSummaryVersionRequestTypeDef = TypedDict(
-    "ObjectSummaryVersionRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
 _RequiredObjectUploadFileRequestTypeDef = TypedDict(
     "_RequiredObjectUploadFileRequestTypeDef",
     {
         "Filename": str,
     },
 )
 _OptionalObjectUploadFileRequestTypeDef = TypedDict(
@@ -3052,28 +3346,40 @@
 )
 
 class ObjectUploadFileobjRequestTypeDef(
     _RequiredObjectUploadFileobjRequestTypeDef, _OptionalObjectUploadFileobjRequestTypeDef
 ):
     pass
 
-ObjectVersionRequestTypeDef = TypedDict(
-    "ObjectVersionRequestTypeDef",
+OwnerResponseMetadataTypeDef = TypedDict(
+    "OwnerResponseMetadataTypeDef",
     {
-        "id": str,
+        "DisplayName": str,
+        "ID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OwnershipControlsRuleTypeDef = TypedDict(
     "OwnershipControlsRuleTypeDef",
     {
         "ObjectOwnership": ObjectOwnershipType,
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
 ProgressTypeDef = TypedDict(
     "ProgressTypeDef",
     {
         "BytesScanned": int,
         "BytesProcessed": int,
         "BytesReturned": int,
     },
@@ -3156,14 +3462,59 @@
         "ChecksumAlgorithm": ChecksumAlgorithmType,
         "MFA": str,
         "ExpectedBucketOwner": str,
     },
     total=False,
 )
 
+PutObjectAclOutputTypeDef = TypedDict(
+    "PutObjectAclOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectLegalHoldOutputTypeDef = TypedDict(
+    "PutObjectLegalHoldOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectLockConfigurationOutputTypeDef = TypedDict(
+    "PutObjectLockConfigurationOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectOutputTypeDef = TypedDict(
+    "PutObjectOutputTypeDef",
+    {
+        "Expiration": str,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "VersionId": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "SSEKMSEncryptionContext": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutObjectRequestBucketPutObjectTypeDef = TypedDict(
     "_RequiredPutObjectRequestBucketPutObjectTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalPutObjectRequestBucketPutObjectTypeDef = TypedDict(
@@ -3347,22 +3698,47 @@
 )
 
 class PutObjectRequestRequestTypeDef(
     _RequiredPutObjectRequestRequestTypeDef, _OptionalPutObjectRequestRequestTypeDef
 ):
     pass
 
+PutObjectRetentionOutputTypeDef = TypedDict(
+    "PutObjectRetentionOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutObjectTaggingOutputTypeDef = TypedDict(
+    "PutObjectTaggingOutputTypeDef",
+    {
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecordsEventTypeDef = TypedDict(
     "RecordsEventTypeDef",
     {
         "Payload": bytes,
     },
     total=False,
 )
 
+RedirectAllRequestsToResponseMetadataTypeDef = TypedDict(
+    "RedirectAllRequestsToResponseMetadataTypeDef",
+    {
+        "HostName": str,
+        "Protocol": ProtocolType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedirectTypeDef = TypedDict(
     "RedirectTypeDef",
     {
         "HostName": str,
         "HttpRedirectCode": str,
         "Protocol": ProtocolType,
         "ReplaceKeyPrefixWith": str,
@@ -3382,14 +3758,34 @@
     "RequestProgressTypeDef",
     {
         "Enabled": bool,
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
+RestoreObjectOutputTypeDef = TypedDict(
+    "RestoreObjectOutputTypeDef",
+    {
+        "RequestCharged": Literal["requester"],
+        "RestoreOutputPath": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ScanRangeTypeDef = TypedDict(
     "ScanRangeTypeDef",
     {
         "Start": int,
         "End": int,
     },
     total=False,
@@ -3410,150 +3806,14 @@
 )
 
 class ServerSideEncryptionByDefaultTypeDef(
     _RequiredServerSideEncryptionByDefaultTypeDef, _OptionalServerSideEncryptionByDefaultTypeDef
 ):
     pass
 
-ServiceResourceBucketAclRequestTypeDef = TypedDict(
-    "ServiceResourceBucketAclRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketCorsRequestTypeDef = TypedDict(
-    "ServiceResourceBucketCorsRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLifecycleConfigurationRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLifecycleConfigurationRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLifecycleRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLifecycleRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketLoggingRequestTypeDef = TypedDict(
-    "ServiceResourceBucketLoggingRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketNotificationRequestTypeDef = TypedDict(
-    "ServiceResourceBucketNotificationRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketPolicyRequestTypeDef = TypedDict(
-    "ServiceResourceBucketPolicyRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketRequestPaymentRequestTypeDef = TypedDict(
-    "ServiceResourceBucketRequestPaymentRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketRequestTypeDef = TypedDict(
-    "ServiceResourceBucketRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
-ServiceResourceBucketTaggingRequestTypeDef = TypedDict(
-    "ServiceResourceBucketTaggingRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketVersioningRequestTypeDef = TypedDict(
-    "ServiceResourceBucketVersioningRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceBucketWebsiteRequestTypeDef = TypedDict(
-    "ServiceResourceBucketWebsiteRequestTypeDef",
-    {
-        "bucket_name": str,
-    },
-)
-
-ServiceResourceMultipartUploadPartRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadPartRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "multipart_upload_id": str,
-        "part_number": str,
-    },
-)
-
-ServiceResourceMultipartUploadRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "id": str,
-    },
-)
-
-ServiceResourceObjectAclRequestTypeDef = TypedDict(
-    "ServiceResourceObjectAclRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-    },
-)
-
-ServiceResourceObjectRequestTypeDef = TypedDict(
-    "ServiceResourceObjectRequestTypeDef",
-    {
-        "bucket_name": str,
-        "key": str,
-    },
-)
-
-ServiceResourceObjectSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceObjectSummaryRequestTypeDef",
-    {
-        "bucket_name": str,
-        "key": str,
-    },
-)
-
-ServiceResourceObjectVersionRequestTypeDef = TypedDict(
-    "ServiceResourceObjectVersionRequestTypeDef",
-    {
-        "bucket_name": str,
-        "object_key": str,
-        "id": str,
-    },
-)
-
 SseKmsEncryptedObjectsTypeDef = TypedDict(
     "SseKmsEncryptedObjectsTypeDef",
     {
         "Status": SseKmsEncryptedObjectsStatusType,
     },
 )
 
@@ -3563,14 +3823,32 @@
         "BytesScanned": int,
         "BytesProcessed": int,
         "BytesReturned": int,
     },
     total=False,
 )
 
+UploadPartOutputTypeDef = TypedDict(
+    "UploadPartOutputTypeDef",
+    {
+        "ServerSideEncryption": ServerSideEncryptionType,
+        "ETag": str,
+        "ChecksumCRC32": str,
+        "ChecksumCRC32C": str,
+        "ChecksumSHA1": str,
+        "ChecksumSHA256": str,
+        "SSECustomerAlgorithm": str,
+        "SSECustomerKeyMD5": str,
+        "SSEKMSKeyId": str,
+        "BucketKeyEnabled": bool,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UploadPartRequestMultipartUploadPartUploadTypeDef = TypedDict(
     "UploadPartRequestMultipartUploadPartUploadTypeDef",
     {
         "Body": Union[str, bytes, IO[Any], StreamingBody],
         "ContentLength": int,
         "ContentMD5": str,
         "ChecksumAlgorithm": ChecksumAlgorithmType,
@@ -3675,361 +3953,14 @@
 
 class WriteGetObjectResponseRequestRequestTypeDef(
     _RequiredWriteGetObjectResponseRequestRequestTypeDef,
     _OptionalWriteGetObjectResponseRequestRequestTypeDef,
 ):
     pass
 
-AbortMultipartUploadOutputTypeDef = TypedDict(
-    "AbortMultipartUploadOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteMultipartUploadOutputTypeDef = TypedDict(
-    "CompleteMultipartUploadOutputTypeDef",
-    {
-        "Location": str,
-        "Bucket": str,
-        "Key": str,
-        "Expiration": str,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "VersionId": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBucketOutputTypeDef = TypedDict(
-    "CreateBucketOutputTypeDef",
-    {
-        "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMultipartUploadOutputTypeDef = TypedDict(
-    "CreateMultipartUploadOutputTypeDef",
-    {
-        "AbortDate": datetime,
-        "AbortRuleId": str,
-        "Bucket": str,
-        "Key": str,
-        "UploadId": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "SSEKMSEncryptionContext": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ChecksumAlgorithm": ChecksumAlgorithmType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteObjectOutputTypeDef = TypedDict(
-    "DeleteObjectOutputTypeDef",
-    {
-        "DeleteMarker": bool,
-        "VersionId": str,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteObjectTaggingOutputTypeDef = TypedDict(
-    "DeleteObjectTaggingOutputTypeDef",
-    {
-        "VersionId": str,
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
-ErrorDocumentResponseMetadataTypeDef = TypedDict(
-    "ErrorDocumentResponseMetadataTypeDef",
-    {
-        "Key": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketAccelerateConfigurationOutputTypeDef = TypedDict(
-    "GetBucketAccelerateConfigurationOutputTypeDef",
-    {
-        "Status": BucketAccelerateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketLocationOutputTypeDef = TypedDict(
-    "GetBucketLocationOutputTypeDef",
-    {
-        "LocationConstraint": BucketLocationConstraintType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketPolicyOutputTypeDef = TypedDict(
-    "GetBucketPolicyOutputTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketRequestPaymentOutputTypeDef = TypedDict(
-    "GetBucketRequestPaymentOutputTypeDef",
-    {
-        "Payer": PayerType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBucketVersioningOutputTypeDef = TypedDict(
-    "GetBucketVersioningOutputTypeDef",
-    {
-        "Status": BucketVersioningStatusType,
-        "MFADelete": MFADeleteStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectOutputTypeDef = TypedDict(
-    "GetObjectOutputTypeDef",
-    {
-        "Body": StreamingBody,
-        "DeleteMarker": bool,
-        "AcceptRanges": str,
-        "Expiration": str,
-        "Restore": str,
-        "LastModified": datetime,
-        "ContentLength": int,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "MissingMeta": int,
-        "VersionId": str,
-        "CacheControl": str,
-        "ContentDisposition": str,
-        "ContentEncoding": str,
-        "ContentLanguage": str,
-        "ContentRange": str,
-        "ContentType": str,
-        "Expires": datetime,
-        "WebsiteRedirectLocation": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "Metadata": Dict[str, str],
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "StorageClass": StorageClassType,
-        "RequestCharged": Literal["requester"],
-        "ReplicationStatus": ReplicationStatusType,
-        "PartsCount": int,
-        "TagCount": int,
-        "ObjectLockMode": ObjectLockModeType,
-        "ObjectLockRetainUntilDate": datetime,
-        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectTorrentOutputTypeDef = TypedDict(
-    "GetObjectTorrentOutputTypeDef",
-    {
-        "Body": StreamingBody,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-HeadObjectOutputTypeDef = TypedDict(
-    "HeadObjectOutputTypeDef",
-    {
-        "DeleteMarker": bool,
-        "AcceptRanges": str,
-        "Expiration": str,
-        "Restore": str,
-        "ArchiveStatus": ArchiveStatusType,
-        "LastModified": datetime,
-        "ContentLength": int,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ETag": str,
-        "MissingMeta": int,
-        "VersionId": str,
-        "CacheControl": str,
-        "ContentDisposition": str,
-        "ContentEncoding": str,
-        "ContentLanguage": str,
-        "ContentType": str,
-        "Expires": datetime,
-        "WebsiteRedirectLocation": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "Metadata": Dict[str, str],
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "StorageClass": StorageClassType,
-        "RequestCharged": Literal["requester"],
-        "ReplicationStatus": ReplicationStatusType,
-        "PartsCount": int,
-        "ObjectLockMode": ObjectLockModeType,
-        "ObjectLockRetainUntilDate": datetime,
-        "ObjectLockLegalHoldStatus": ObjectLockLegalHoldStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IndexDocumentResponseMetadataTypeDef = TypedDict(
-    "IndexDocumentResponseMetadataTypeDef",
-    {
-        "Suffix": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiatorResponseMetadataTypeDef = TypedDict(
-    "InitiatorResponseMetadataTypeDef",
-    {
-        "ID": str,
-        "DisplayName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-OwnerResponseMetadataTypeDef = TypedDict(
-    "OwnerResponseMetadataTypeDef",
-    {
-        "DisplayName": str,
-        "ID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectAclOutputTypeDef = TypedDict(
-    "PutObjectAclOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectLegalHoldOutputTypeDef = TypedDict(
-    "PutObjectLegalHoldOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectLockConfigurationOutputTypeDef = TypedDict(
-    "PutObjectLockConfigurationOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectOutputTypeDef = TypedDict(
-    "PutObjectOutputTypeDef",
-    {
-        "Expiration": str,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "VersionId": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "SSEKMSEncryptionContext": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectRetentionOutputTypeDef = TypedDict(
-    "PutObjectRetentionOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutObjectTaggingOutputTypeDef = TypedDict(
-    "PutObjectTaggingOutputTypeDef",
-    {
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RedirectAllRequestsToResponseMetadataTypeDef = TypedDict(
-    "RedirectAllRequestsToResponseMetadataTypeDef",
-    {
-        "HostName": str,
-        "Protocol": ProtocolType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreObjectOutputTypeDef = TypedDict(
-    "RestoreObjectOutputTypeDef",
-    {
-        "RequestCharged": Literal["requester"],
-        "RestoreOutputPath": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadPartOutputTypeDef = TypedDict(
-    "UploadPartOutputTypeDef",
-    {
-        "ServerSideEncryption": ServerSideEncryptionType,
-        "ETag": str,
-        "ChecksumCRC32": str,
-        "ChecksumCRC32C": str,
-        "ChecksumSHA1": str,
-        "ChecksumSHA256": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKeyMD5": str,
-        "SSEKMSKeyId": str,
-        "BucketKeyEnabled": bool,
-        "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPutBucketAccelerateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketAccelerateConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
         "AccelerateConfiguration": AccelerateConfigurationTypeDef,
     },
 )
@@ -4099,24 +4030,24 @@
     total=False,
 )
 
 GetBucketTaggingOutputTypeDef = TypedDict(
     "GetBucketTaggingOutputTypeDef",
     {
         "TagSet": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectTaggingOutputTypeDef = TypedDict(
     "GetObjectTaggingOutputTypeDef",
     {
         "VersionId": str,
         "TagSet": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntelligentTieringAndOperatorTypeDef = TypedDict(
     "IntelligentTieringAndOperatorTypeDef",
     {
         "Prefix": str,
@@ -4366,30 +4297,30 @@
     pass
 
 ListBucketsOutputTypeDef = TypedDict(
     "ListBucketsOutputTypeDef",
     {
         "Buckets": List[BucketTypeDef],
         "Owner": OwnerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CORSConfigurationTypeDef = TypedDict(
     "CORSConfigurationTypeDef",
     {
         "CORSRules": Sequence[CORSRuleTypeDef],
     },
 )
 
 GetBucketCorsOutputTypeDef = TypedDict(
     "GetBucketCorsOutputTypeDef",
     {
         "CORSRules": List[CORSRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompletedMultipartUploadTypeDef = TypedDict(
     "CompletedMultipartUploadTypeDef",
     {
         "Parts": Sequence[CompletedPartTypeDef],
@@ -4407,30 +4338,30 @@
         "ServerSideEncryption": ServerSideEncryptionType,
         "SSECustomerAlgorithm": str,
         "SSECustomerKeyMD5": str,
         "SSEKMSKeyId": str,
         "SSEKMSEncryptionContext": str,
         "BucketKeyEnabled": bool,
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UploadPartCopyOutputTypeDef = TypedDict(
     "UploadPartCopyOutputTypeDef",
     {
         "CopySourceVersionId": str,
         "CopyPartResult": CopyPartResultTypeDef,
         "ServerSideEncryption": ServerSideEncryptionType,
         "SSECustomerAlgorithm": str,
         "SSECustomerKeyMD5": str,
         "SSEKMSKeyId": str,
         "BucketKeyEnabled": bool,
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketRequestBucketCreateTypeDef = TypedDict(
     "CreateBucketRequestBucketCreateTypeDef",
     {
         "ACL": BucketCannedACLType,
@@ -4511,15 +4442,15 @@
 
 DeleteObjectsOutputTypeDef = TypedDict(
     "DeleteObjectsOutputTypeDef",
     {
         "Deleted": List[DeletedObjectTypeDef],
         "RequestCharged": Literal["requester"],
         "Errors": List[ErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteTypeDef = TypedDict(
     "_RequiredDeleteTypeDef",
     {
         "Objects": Sequence[ObjectIdentifierTypeDef],
@@ -4544,15 +4475,15 @@
     total=False,
 )
 
 GetBucketPolicyStatusOutputTypeDef = TypedDict(
     "GetBucketPolicyStatusOutputTypeDef",
     {
         "PolicyStatus": PolicyStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAttributesPartsTypeDef = TypedDict(
     "GetObjectAttributesPartsTypeDef",
     {
         "TotalPartsCount": int,
@@ -4565,15 +4496,15 @@
     total=False,
 )
 
 GetObjectLegalHoldOutputTypeDef = TypedDict(
     "GetObjectLegalHoldOutputTypeDef",
     {
         "LegalHold": ObjectLockLegalHoldTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectLegalHoldRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectLegalHoldRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -4599,15 +4530,15 @@
 ):
     pass
 
 GetObjectRetentionOutputTypeDef = TypedDict(
     "GetObjectRetentionOutputTypeDef",
     {
         "Retention": ObjectLockRetentionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectRetentionRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectRetentionRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -4634,15 +4565,15 @@
 ):
     pass
 
 GetPublicAccessBlockOutputTypeDef = TypedDict(
     "GetPublicAccessBlockOutputTypeDef",
     {
         "PublicAccessBlockConfiguration": PublicAccessBlockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPublicAccessBlockRequestRequestTypeDef = TypedDict(
     "_RequiredPutPublicAccessBlockRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -4855,141 +4786,14 @@
     },
     total=False,
 )
 
 class RuleTypeDef(_RequiredRuleTypeDef, _OptionalRuleTypeDef):
     pass
 
-_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef(
-    _RequiredListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-    _OptionalListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-):
-    pass
-
-_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectVersionsRequestListObjectVersionsPaginateTypeDef(
-    _RequiredListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-    _OptionalListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectsRequestListObjectsPaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectsRequestListObjectsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectsRequestListObjectsPaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectsRequestListObjectsPaginateTypeDef(
-    _RequiredListObjectsRequestListObjectsPaginateTypeDef,
-    _OptionalListObjectsRequestListObjectsPaginateTypeDef,
-):
-    pass
-
-_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
-    "_RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef = TypedDict(
-    "_OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef",
-    {
-        "Delimiter": str,
-        "EncodingType": Literal["url"],
-        "Prefix": str,
-        "FetchOwner": bool,
-        "StartAfter": str,
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectsV2RequestListObjectsV2PaginateTypeDef(
-    _RequiredListObjectsV2RequestListObjectsV2PaginateTypeDef,
-    _OptionalListObjectsV2RequestListObjectsV2PaginateTypeDef,
-):
-    pass
-
-_RequiredListPartsRequestListPartsPaginateTypeDef = TypedDict(
-    "_RequiredListPartsRequestListPartsPaginateTypeDef",
-    {
-        "Bucket": str,
-        "Key": str,
-        "UploadId": str,
-    },
-)
-_OptionalListPartsRequestListPartsPaginateTypeDef = TypedDict(
-    "_OptionalListPartsRequestListPartsPaginateTypeDef",
-    {
-        "RequestPayer": Literal["requester"],
-        "ExpectedBucketOwner": str,
-        "SSECustomerAlgorithm": str,
-        "SSECustomerKey": str,
-        "SSECustomerKeyMD5": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPartsRequestListPartsPaginateTypeDef(
-    _RequiredListPartsRequestListPartsPaginateTypeDef,
-    _OptionalListPartsRequestListPartsPaginateTypeDef,
-):
-    pass
-
 ListPartsOutputTypeDef = TypedDict(
     "ListPartsOutputTypeDef",
     {
         "AbortDate": datetime,
         "AbortRuleId": str,
         "Bucket": str,
         "Key": str,
@@ -5000,15 +4804,15 @@
         "IsTruncated": bool,
         "Parts": List[PartTypeDef],
         "Initiator": InitiatorTypeDef,
         "Owner": OwnerTypeDef,
         "StorageClass": StorageClassType,
         "RequestCharged": Literal["requester"],
         "ChecksumAlgorithm": ChecksumAlgorithmType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricsTypeDef = TypedDict(
     "_RequiredMetricsTypeDef",
     {
         "Status": MetricsStatusType,
@@ -5035,15 +4839,15 @@
 
 NotificationConfigurationDeprecatedResponseMetadataTypeDef = TypedDict(
     "NotificationConfigurationDeprecatedResponseMetadataTypeDef",
     {
         "TopicConfiguration": TopicConfigurationDeprecatedTypeDef,
         "QueueConfiguration": QueueConfigurationDeprecatedTypeDef,
         "CloudFunctionConfiguration": CloudFunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationConfigurationDeprecatedTypeDef = TypedDict(
     "NotificationConfigurationDeprecatedTypeDef",
     {
         "TopicConfiguration": TopicConfigurationDeprecatedTypeDef,
@@ -5208,15 +5012,16 @@
         "Contents": List[ObjectTypeDef],
         "Name": str,
         "Prefix": str,
         "Delimiter": str,
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectsV2OutputTypeDef = TypedDict(
     "ListObjectsV2OutputTypeDef",
     {
         "IsTruncated": bool,
@@ -5227,15 +5032,16 @@
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
         "KeyCount": int,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "StartAfter": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectVersionsOutputTypeDef = TypedDict(
     "ListObjectVersionsOutputTypeDef",
     {
         "IsTruncated": bool,
@@ -5247,15 +5053,16 @@
         "DeleteMarkers": List[DeleteMarkerEntryTypeDef],
         "Name": str,
         "Prefix": str,
         "Delimiter": str,
         "MaxKeys": int,
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalyticsFilterTypeDef = TypedDict(
     "AnalyticsFilterTypeDef",
     {
         "Prefix": str,
@@ -5546,15 +5353,15 @@
         "VersionId": str,
         "RequestCharged": Literal["requester"],
         "ETag": str,
         "Checksum": ChecksumTypeDef,
         "ObjectParts": GetObjectAttributesPartsTypeDef,
         "StorageClass": StorageClassType,
         "ObjectSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccessControlPolicyTypeDef = TypedDict(
     "AccessControlPolicyTypeDef",
     {
         "Grants": Sequence[GrantTypeDef],
@@ -5564,25 +5371,25 @@
 )
 
 GetBucketAclOutputTypeDef = TypedDict(
     "GetBucketAclOutputTypeDef",
     {
         "Owner": OwnerTypeDef,
         "Grants": List[GrantTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAclOutputTypeDef = TypedDict(
     "GetObjectAclOutputTypeDef",
     {
         "Owner": OwnerTypeDef,
         "Grants": List[GrantTypeDef],
         "RequestCharged": Literal["requester"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3LocationTypeDef = TypedDict(
     "_RequiredS3LocationTypeDef",
     {
         "BucketName": str,
@@ -5607,15 +5414,15 @@
 
 LoggingEnabledResponseMetadataTypeDef = TypedDict(
     "LoggingEnabledResponseMetadataTypeDef",
     {
         "TargetBucket": str,
         "TargetGrants": List[TargetGrantTypeDef],
         "TargetPrefix": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLoggingEnabledTypeDef = TypedDict(
     "_RequiredLoggingEnabledTypeDef",
     {
         "TargetBucket": str,
@@ -5644,15 +5451,16 @@
         "Delimiter": str,
         "NextUploadIdMarker": str,
         "MaxUploads": int,
         "IsTruncated": bool,
         "Uploads": List[MultipartUploadTypeDef],
         "CommonPrefixes": List[CommonPrefixTypeDef],
         "EncodingType": Literal["url"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestCharged": Literal["requester"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInventoryS3BucketDestinationTypeDef = TypedDict(
     "_RequiredInventoryS3BucketDestinationTypeDef",
     {
         "Bucket": str,
@@ -5714,15 +5522,15 @@
     },
 )
 
 GetBucketLifecycleOutputTypeDef = TypedDict(
     "GetBucketLifecycleOutputTypeDef",
     {
         "Rules": List[RuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleConfigurationTypeDef = TypedDict(
     "LifecycleConfigurationTypeDef",
     {
         "Rules": Sequence[RuleTypeDef],
@@ -5773,15 +5581,15 @@
 ):
     pass
 
 GetBucketOwnershipControlsOutputTypeDef = TypedDict(
     "GetBucketOwnershipControlsOutputTypeDef",
     {
         "OwnershipControls": OwnershipControlsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketOwnershipControlsRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketOwnershipControlsRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -5806,15 +5614,15 @@
 GetBucketWebsiteOutputTypeDef = TypedDict(
     "GetBucketWebsiteOutputTypeDef",
     {
         "RedirectAllRequestsTo": RedirectAllRequestsToTypeDef,
         "IndexDocument": IndexDocumentTypeDef,
         "ErrorDocument": ErrorDocumentTypeDef,
         "RoutingRules": List[RoutingRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WebsiteConfigurationTypeDef = TypedDict(
     "WebsiteConfigurationTypeDef",
     {
         "ErrorDocument": ErrorDocumentTypeDef,
@@ -5916,15 +5724,15 @@
     total=False,
 )
 
 GetObjectLockConfigurationOutputTypeDef = TypedDict(
     "GetObjectLockConfigurationOutputTypeDef",
     {
         "ObjectLockConfiguration": ObjectLockConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutObjectLockConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectLockConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6119,15 +5927,15 @@
     total=False,
 )
 
 GetBucketLoggingOutputTypeDef = TypedDict(
     "GetBucketLoggingOutputTypeDef",
     {
         "LoggingEnabled": LoggingEnabledTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryDestinationTypeDef = TypedDict(
     "InventoryDestinationTypeDef",
     {
         "S3BucketDestination": InventoryS3BucketDestinationTypeDef,
@@ -6232,15 +6040,15 @@
 ):
     pass
 
 GetBucketEncryptionOutputTypeDef = TypedDict(
     "GetBucketEncryptionOutputTypeDef",
     {
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketEncryptionRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketEncryptionRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6263,34 +6071,34 @@
 ):
     pass
 
 SelectObjectContentOutputTypeDef = TypedDict(
     "SelectObjectContentOutputTypeDef",
     {
         "Payload": SelectObjectContentEventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketIntelligentTieringConfigurationOutputTypeDef = TypedDict(
     "GetBucketIntelligentTieringConfigurationOutputTypeDef",
     {
         "IntelligentTieringConfiguration": IntelligentTieringConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketIntelligentTieringConfigurationsOutputTypeDef = TypedDict(
     "ListBucketIntelligentTieringConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "IntelligentTieringConfigurationList": List[IntelligentTieringConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBucketIntelligentTieringConfigurationRequestRequestTypeDef = TypedDict(
     "PutBucketIntelligentTieringConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6306,34 +6114,34 @@
     },
 )
 
 GetBucketLifecycleConfigurationOutputTypeDef = TypedDict(
     "GetBucketLifecycleConfigurationOutputTypeDef",
     {
         "Rules": List[LifecycleRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketMetricsConfigurationOutputTypeDef = TypedDict(
     "GetBucketMetricsConfigurationOutputTypeDef",
     {
         "MetricsConfiguration": MetricsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketMetricsConfigurationsOutputTypeDef = TypedDict(
     "ListBucketMetricsConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "MetricsConfigurationList": List[MetricsConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketMetricsConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketMetricsConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6378,15 +6186,15 @@
 NotificationConfigurationResponseMetadataTypeDef = TypedDict(
     "NotificationConfigurationResponseMetadataTypeDef",
     {
         "TopicConfigurations": List[TopicConfigurationTypeDef],
         "QueueConfigurations": List[QueueConfigurationTypeDef],
         "LambdaFunctionConfigurations": List[LambdaFunctionConfigurationTypeDef],
         "EventBridgeConfiguration": Dict[str, Any],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationConfigurationTypeDef = TypedDict(
     "NotificationConfigurationTypeDef",
     {
         "TopicConfigurations": Sequence[TopicConfigurationTypeDef],
@@ -6517,26 +6325,26 @@
 ):
     pass
 
 GetBucketAnalyticsConfigurationOutputTypeDef = TypedDict(
     "GetBucketAnalyticsConfigurationOutputTypeDef",
     {
         "AnalyticsConfiguration": AnalyticsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketAnalyticsConfigurationsOutputTypeDef = TypedDict(
     "ListBucketAnalyticsConfigurationsOutputTypeDef",
     {
         "IsTruncated": bool,
         "ContinuationToken": str,
         "NextContinuationToken": str,
         "AnalyticsConfigurationList": List[AnalyticsConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketAnalyticsConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketAnalyticsConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6649,26 +6457,26 @@
 ):
     pass
 
 GetBucketInventoryConfigurationOutputTypeDef = TypedDict(
     "GetBucketInventoryConfigurationOutputTypeDef",
     {
         "InventoryConfiguration": InventoryConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBucketInventoryConfigurationsOutputTypeDef = TypedDict(
     "ListBucketInventoryConfigurationsOutputTypeDef",
     {
         "ContinuationToken": str,
         "InventoryConfigurationList": List[InventoryConfigurationTypeDef],
         "IsTruncated": bool,
         "NextContinuationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketInventoryConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketInventoryConfigurationRequestRequestTypeDef",
     {
         "Bucket": str,
@@ -6690,15 +6498,15 @@
 ):
     pass
 
 GetBucketReplicationOutputTypeDef = TypedDict(
     "GetBucketReplicationOutputTypeDef",
     {
         "ReplicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBucketReplicationRequestRequestTypeDef = TypedDict(
     "_RequiredPutBucketReplicationRequestRequestTypeDef",
     {
         "Bucket": str,
```

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/waiter.py` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3/waiter.pyi` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/PKG-INFO` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-s3
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.S3 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.S3 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-s3"></a>
 
 # types-aiobotocore-s3
 
 [![PyPI - types-aiobotocore-s3](https://img.shields.io/pypi/v/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-s3.svg?color=blue)](https://pypi.org/project/types-aiobotocore-s3)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-s3?color=blue)](https://pypistats.org/packages/types-aiobotocore-s3)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.S3 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
+[aiobotocore.S3 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3)
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
 [types-aiobotocore-s3 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/).
 
 See how it helps to find and fix potential bugs:
 
@@ -526,47 +526,49 @@
 
 `types_aiobotocore_s3.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_s3.type_defs import (
     AbortIncompleteMultipartUploadTypeDef,
-    ResponseMetadataTypeDef,
+    AbortMultipartUploadOutputTypeDef,
     AbortMultipartUploadRequestMultipartUploadAbortTypeDef,
     AbortMultipartUploadRequestRequestTypeDef,
     AccelerateConfigurationTypeDef,
     OwnerTypeDef,
     AccessControlTranslationTypeDef,
     TagTypeDef,
     AnalyticsS3BucketDestinationTypeDef,
     CopySourceTypeDef,
     BucketDownloadFileRequestTypeDef,
     BucketDownloadFileobjRequestTypeDef,
-    BucketObjectRequestTypeDef,
     BucketTypeDef,
     BucketUploadFileRequestTypeDef,
     BucketUploadFileobjRequestTypeDef,
     CORSRuleTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     ChecksumTypeDef,
     ClientDownloadFileRequestTypeDef,
     ClientDownloadFileobjRequestTypeDef,
     ClientGeneratePresignedPostRequestTypeDef,
     ClientUploadFileRequestTypeDef,
     ClientUploadFileobjRequestTypeDef,
     CloudFunctionConfigurationTypeDef,
     CommonPrefixTypeDef,
+    CompleteMultipartUploadOutputTypeDef,
     CompletedPartTypeDef,
     ConditionTypeDef,
     CopyObjectResultTypeDef,
     CopyObjectRequestObjectCopyFromTypeDef,
     CopyObjectRequestObjectSummaryCopyFromTypeDef,
     CopyPartResultTypeDef,
     CreateBucketConfigurationTypeDef,
+    CreateBucketOutputTypeDef,
+    CreateMultipartUploadOutputTypeDef,
     CreateMultipartUploadRequestObjectInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestObjectSummaryInitiateMultipartUploadTypeDef,
     CreateMultipartUploadRequestRequestTypeDef,
     DefaultRetentionTypeDef,
     DeleteBucketAnalyticsConfigurationRequestRequestTypeDef,
     DeleteBucketCorsRequestBucketCorsDeleteTypeDef,
     DeleteBucketCorsRequestRequestTypeDef,
@@ -584,74 +586,88 @@
     DeleteBucketRequestBucketDeleteTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteBucketTaggingRequestBucketTaggingDeleteTypeDef,
     DeleteBucketTaggingRequestRequestTypeDef,
     DeleteBucketWebsiteRequestBucketWebsiteDeleteTypeDef,
     DeleteBucketWebsiteRequestRequestTypeDef,
     DeleteMarkerReplicationTypeDef,
+    DeleteObjectOutputTypeDef,
     DeleteObjectRequestObjectDeleteTypeDef,
     DeleteObjectRequestObjectSummaryDeleteTypeDef,
     DeleteObjectRequestObjectVersionDeleteTypeDef,
     DeleteObjectRequestRequestTypeDef,
+    DeleteObjectTaggingOutputTypeDef,
     DeleteObjectTaggingRequestRequestTypeDef,
     DeletedObjectTypeDef,
     ErrorTypeDef,
     DeletePublicAccessBlockRequestRequestTypeDef,
     ObjectIdentifierTypeDef,
     EncryptionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
+    ErrorDocumentResponseMetadataTypeDef,
     ErrorDocumentTypeDef,
     ExistingObjectReplicationTypeDef,
     FilterRuleTypeDef,
+    GetBucketAccelerateConfigurationOutputTypeDef,
     GetBucketAccelerateConfigurationRequestRequestTypeDef,
     GetBucketAclRequestRequestTypeDef,
     GetBucketAnalyticsConfigurationRequestRequestTypeDef,
     GetBucketCorsRequestRequestTypeDef,
     GetBucketEncryptionRequestRequestTypeDef,
     GetBucketIntelligentTieringConfigurationRequestRequestTypeDef,
     GetBucketInventoryConfigurationRequestRequestTypeDef,
     GetBucketLifecycleConfigurationRequestRequestTypeDef,
     GetBucketLifecycleRequestRequestTypeDef,
+    GetBucketLocationOutputTypeDef,
     GetBucketLocationRequestRequestTypeDef,
     GetBucketLoggingRequestRequestTypeDef,
     GetBucketMetricsConfigurationRequestRequestTypeDef,
     GetBucketNotificationConfigurationRequestRequestTypeDef,
     GetBucketOwnershipControlsRequestRequestTypeDef,
+    GetBucketPolicyOutputTypeDef,
     GetBucketPolicyRequestRequestTypeDef,
     PolicyStatusTypeDef,
     GetBucketPolicyStatusRequestRequestTypeDef,
     GetBucketReplicationRequestRequestTypeDef,
+    GetBucketRequestPaymentOutputTypeDef,
     GetBucketRequestPaymentRequestRequestTypeDef,
     GetBucketTaggingRequestRequestTypeDef,
+    GetBucketVersioningOutputTypeDef,
     GetBucketVersioningRequestRequestTypeDef,
     IndexDocumentTypeDef,
     RedirectAllRequestsToTypeDef,
     GetBucketWebsiteRequestRequestTypeDef,
     GetObjectAclRequestRequestTypeDef,
     ObjectPartTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
     ObjectLockLegalHoldTypeDef,
     GetObjectLegalHoldRequestRequestTypeDef,
     GetObjectLockConfigurationRequestRequestTypeDef,
+    GetObjectOutputTypeDef,
     GetObjectRequestObjectGetTypeDef,
     GetObjectRequestObjectSummaryGetTypeDef,
     GetObjectRequestObjectVersionGetTypeDef,
     GetObjectRequestRequestTypeDef,
     ObjectLockRetentionTypeDef,
     GetObjectRetentionRequestRequestTypeDef,
     GetObjectTaggingRequestRequestTypeDef,
+    GetObjectTorrentOutputTypeDef,
     GetObjectTorrentRequestRequestTypeDef,
     PublicAccessBlockConfigurationTypeDef,
     GetPublicAccessBlockRequestRequestTypeDef,
     GlacierJobParametersTypeDef,
     GranteeTypeDef,
     WaiterConfigTypeDef,
     HeadBucketRequestRequestTypeDef,
+    HeadObjectOutputTypeDef,
     HeadObjectRequestObjectVersionHeadTypeDef,
     HeadObjectRequestRequestTypeDef,
+    IndexDocumentResponseMetadataTypeDef,
+    InitiatorResponseMetadataTypeDef,
     InitiatorTypeDef,
     JSONInputTypeDef,
     TieringTypeDef,
     InventoryFilterTypeDef,
     InventoryScheduleTypeDef,
     SSEKMSTypeDef,
     JSONOutputTypeDef,
@@ -659,103 +675,68 @@
     NoncurrentVersionExpirationTypeDef,
     NoncurrentVersionTransitionTypeDef,
     TransitionTypeDef,
     ListBucketAnalyticsConfigurationsRequestRequestTypeDef,
     ListBucketIntelligentTieringConfigurationsRequestRequestTypeDef,
     ListBucketInventoryConfigurationsRequestRequestTypeDef,
     ListBucketMetricsConfigurationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsRequestRequestTypeDef,
+    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
     ListObjectVersionsRequestRequestTypeDef,
+    ListObjectsRequestListObjectsPaginateTypeDef,
     ListObjectsRequestRequestTypeDef,
+    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
     ListObjectsV2RequestRequestTypeDef,
     PartTypeDef,
+    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsRequestRequestTypeDef,
     MetadataEntryTypeDef,
     ReplicationTimeValueTypeDef,
-    MultipartUploadPartRequestTypeDef,
     QueueConfigurationDeprecatedTypeDef,
     TopicConfigurationDeprecatedTypeDef,
     ObjectDownloadFileRequestTypeDef,
     ObjectDownloadFileobjRequestTypeDef,
-    ObjectMultipartUploadRequestTypeDef,
-    ObjectSummaryMultipartUploadRequestTypeDef,
-    ObjectSummaryVersionRequestTypeDef,
     ObjectUploadFileRequestTypeDef,
     ObjectUploadFileobjRequestTypeDef,
-    ObjectVersionRequestTypeDef,
+    OwnerResponseMetadataTypeDef,
     OwnershipControlsRuleTypeDef,
+    PaginatorConfigTypeDef,
     ProgressTypeDef,
     PutBucketPolicyRequestBucketPolicyPutTypeDef,
     PutBucketPolicyRequestRequestTypeDef,
     RequestPaymentConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningEnableTypeDef,
     VersioningConfigurationTypeDef,
     PutBucketVersioningRequestBucketVersioningSuspendTypeDef,
+    PutObjectAclOutputTypeDef,
+    PutObjectLegalHoldOutputTypeDef,
+    PutObjectLockConfigurationOutputTypeDef,
+    PutObjectOutputTypeDef,
     PutObjectRequestBucketPutObjectTypeDef,
     PutObjectRequestObjectPutTypeDef,
     PutObjectRequestObjectSummaryPutTypeDef,
     PutObjectRequestRequestTypeDef,
+    PutObjectRetentionOutputTypeDef,
+    PutObjectTaggingOutputTypeDef,
     RecordsEventTypeDef,
+    RedirectAllRequestsToResponseMetadataTypeDef,
     RedirectTypeDef,
     ReplicaModificationsTypeDef,
     RequestProgressTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreObjectOutputTypeDef,
     ScanRangeTypeDef,
     ServerSideEncryptionByDefaultTypeDef,
-    ServiceResourceBucketAclRequestTypeDef,
-    ServiceResourceBucketCorsRequestTypeDef,
-    ServiceResourceBucketLifecycleConfigurationRequestTypeDef,
-    ServiceResourceBucketLifecycleRequestTypeDef,
-    ServiceResourceBucketLoggingRequestTypeDef,
-    ServiceResourceBucketNotificationRequestTypeDef,
-    ServiceResourceBucketPolicyRequestTypeDef,
-    ServiceResourceBucketRequestPaymentRequestTypeDef,
-    ServiceResourceBucketRequestTypeDef,
-    ServiceResourceBucketTaggingRequestTypeDef,
-    ServiceResourceBucketVersioningRequestTypeDef,
-    ServiceResourceBucketWebsiteRequestTypeDef,
-    ServiceResourceMultipartUploadPartRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceObjectAclRequestTypeDef,
-    ServiceResourceObjectRequestTypeDef,
-    ServiceResourceObjectSummaryRequestTypeDef,
-    ServiceResourceObjectVersionRequestTypeDef,
     SseKmsEncryptedObjectsTypeDef,
     StatsTypeDef,
+    UploadPartOutputTypeDef,
     UploadPartRequestMultipartUploadPartUploadTypeDef,
     UploadPartRequestRequestTypeDef,
     WriteGetObjectResponseRequestRequestTypeDef,
-    AbortMultipartUploadOutputTypeDef,
-    CompleteMultipartUploadOutputTypeDef,
-    CreateBucketOutputTypeDef,
-    CreateMultipartUploadOutputTypeDef,
-    DeleteObjectOutputTypeDef,
-    DeleteObjectTaggingOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ErrorDocumentResponseMetadataTypeDef,
-    GetBucketAccelerateConfigurationOutputTypeDef,
-    GetBucketLocationOutputTypeDef,
-    GetBucketPolicyOutputTypeDef,
-    GetBucketRequestPaymentOutputTypeDef,
-    GetBucketVersioningOutputTypeDef,
-    GetObjectOutputTypeDef,
-    GetObjectTorrentOutputTypeDef,
-    HeadObjectOutputTypeDef,
-    IndexDocumentResponseMetadataTypeDef,
-    InitiatorResponseMetadataTypeDef,
-    OwnerResponseMetadataTypeDef,
-    PutObjectAclOutputTypeDef,
-    PutObjectLegalHoldOutputTypeDef,
-    PutObjectLockConfigurationOutputTypeDef,
-    PutObjectOutputTypeDef,
-    PutObjectRetentionOutputTypeDef,
-    PutObjectTaggingOutputTypeDef,
-    RedirectAllRequestsToResponseMetadataTypeDef,
-    RestoreObjectOutputTypeDef,
-    UploadPartOutputTypeDef,
     PutBucketAccelerateConfigurationRequestRequestTypeDef,
     DeleteMarkerEntryTypeDef,
     ObjectTypeDef,
     ObjectVersionTypeDef,
     AnalyticsAndOperatorTypeDef,
     GetBucketTaggingOutputTypeDef,
     GetObjectTaggingOutputTypeDef,
@@ -799,19 +780,14 @@
     HeadObjectRequestObjectExistsWaitTypeDef,
     HeadObjectRequestObjectNotExistsWaitTypeDef,
     MultipartUploadTypeDef,
     InputSerializationTypeDef,
     InventoryEncryptionTypeDef,
     OutputSerializationTypeDef,
     RuleTypeDef,
-    ListMultipartUploadsRequestListMultipartUploadsPaginateTypeDef,
-    ListObjectVersionsRequestListObjectVersionsPaginateTypeDef,
-    ListObjectsRequestListObjectsPaginateTypeDef,
-    ListObjectsV2RequestListObjectsV2PaginateTypeDef,
-    ListPartsRequestListPartsPaginateTypeDef,
     ListPartsOutputTypeDef,
     MetricsTypeDef,
     ReplicationTimeTypeDef,
     NotificationConfigurationDeprecatedResponseMetadataTypeDef,
     NotificationConfigurationDeprecatedTypeDef,
     OwnershipControlsTypeDef,
     ProgressEventTypeDef,
@@ -930,43 +906,43 @@
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

### Comparing `types-aiobotocore-s3-2.5.0.post1/types_aiobotocore_s3.egg-info/SOURCES.txt` & `types-aiobotocore-s3-2.5.1/types_aiobotocore_s3.egg-info/SOURCES.txt`

 * *Files identical despite different names*

