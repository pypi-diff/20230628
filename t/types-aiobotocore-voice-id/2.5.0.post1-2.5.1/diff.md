# Comparing `tmp/types-aiobotocore-voice-id-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-voice-id-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-voice-id-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:28 2023, max compression
+gzip compressed data, was "types-aiobotocore-voice-id-2.5.1.tar", last modified: Wed Jun 28 01:44:18 2023, max compression
```

## Comparing `types-aiobotocore-voice-id-2.5.0.post1.tar` & `types-aiobotocore-voice-id-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.231702 types-aiobotocore-voice-id-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16631 2023-03-11 12:27:28.227702 types-aiobotocore-voice-id-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15057 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:28.231702 types-aiobotocore-voice-id-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2130 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.215702 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/
--rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1377 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      945 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19481 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    19447 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9619 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9617 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5873 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5866 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    24876 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24851 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:17.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.227702 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16631 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:28.000000 types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.846229 types-aiobotocore-voice-id-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17774 2023-06-28 01:44:18.846229 types-aiobotocore-voice-id-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16206 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:18.846229 types-aiobotocore-voice-id-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.846229 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/
+-rw-r--r--   0 runner    (1001) docker     (123)     1758 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1757 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      933 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25008 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24964 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10058 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10056 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7975 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7967 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    32507 2023-06-28 01:42:07.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32470 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:06.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.846229 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17774 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:18.000000 types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/LICENSE` & `types-aiobotocore-voice-id-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/PKG-INFO` & `types-aiobotocore-voice-id-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-voice-id
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.VoiceID 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore voice-id type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-voice-id"></a>
 
 # types-aiobotocore-voice-id
 
 [![PyPI - types-aiobotocore-voice-id](https://img.shields.io/pypi/v/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-voice-id?color=blue)](https://pypistats.org/packages/types-aiobotocore-voice-id)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.VoiceID 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
+[aiobotocore.VoiceID 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
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
 [types-aiobotocore-voice-id docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,32 +241,36 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_voice_id import VoiceIDClient
 from types_aiobotocore_voice_id.paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 
 session = get_session()
 async with session.create_client("voice-id") as client:
     client: VoiceIDClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
     list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = (
         client.get_paginator("list_fraudster_registration_jobs")
     )
+    list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
     list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = (
         client.get_paginator("list_speaker_enrollment_jobs")
     )
     list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+    list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_voice_id.literals` module contains literals extracted from
@@ -313,16 +284,18 @@
     ExistingEnrollmentActionType,
     FraudDetectionActionType,
     FraudDetectionDecisionType,
     FraudDetectionReasonType,
     FraudsterRegistrationJobStatusType,
     ListDomainsPaginatorName,
     ListFraudsterRegistrationJobsPaginatorName,
+    ListFraudstersPaginatorName,
     ListSpeakerEnrollmentJobsPaginatorName,
     ListSpeakersPaginatorName,
+    ListWatchlistsPaginatorName,
     ServerSideEncryptionUpdateStatusType,
     SpeakerEnrollmentJobStatusType,
     SpeakerStatusType,
     StreamingStatusType,
     VoiceIDServiceName,
     ServiceName,
     ResourceServiceName,
@@ -340,70 +313,91 @@
 ### Typed dictionaries
 
 `types_aiobotocore_voice_id.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_voice_id.type_defs import (
+    AssociateFraudsterRequestRequestTypeDef,
+    FraudsterTypeDef,
     AuthenticationConfigurationTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateWatchlistRequestRequestTypeDef,
+    WatchlistTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteFraudsterRequestRequestTypeDef,
     DeleteSpeakerRequestRequestTypeDef,
+    DeleteWatchlistRequestRequestTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeFraudsterRegistrationJobRequestRequestTypeDef,
     DescribeFraudsterRequestRequestTypeDef,
-    FraudsterTypeDef,
     DescribeSpeakerEnrollmentJobRequestRequestTypeDef,
     DescribeSpeakerRequestRequestTypeDef,
     SpeakerTypeDef,
+    DescribeWatchlistRequestRequestTypeDef,
+    DisassociateFraudsterRequestRequestTypeDef,
     ServerSideEncryptionUpdateDetailsTypeDef,
+    WatchlistDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnrollmentJobFraudDetectionConfigTypeDef,
     EvaluateSessionRequestRequestTypeDef,
     FailureDetailsTypeDef,
     FraudDetectionConfigurationTypeDef,
     KnownFraudsterRiskTypeDef,
     VoiceSpoofingRiskTypeDef,
     JobProgressTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     RegistrationConfigTypeDef,
-    PaginatorConfigTypeDef,
+    FraudsterSummaryTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
     ListFraudsterRegistrationJobsRequestRequestTypeDef,
+    ListFraudstersRequestListFraudstersPaginateTypeDef,
+    ListFraudstersRequestRequestTypeDef,
+    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
     ListSpeakerEnrollmentJobsRequestRequestTypeDef,
+    ListSpeakersRequestListSpeakersPaginateTypeDef,
     ListSpeakersRequestRequestTypeDef,
     SpeakerSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWatchlistsRequestListWatchlistsPaginateTypeDef,
+    ListWatchlistsRequestRequestTypeDef,
+    WatchlistSummaryTypeDef,
     OptOutSpeakerRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateWatchlistRequestRequestTypeDef,
+    AssociateFraudsterResponseTypeDef,
+    DescribeFraudsterResponseTypeDef,
+    DisassociateFraudsterResponseTypeDef,
     AuthenticationResultTypeDef,
     UpdateDomainRequestRequestTypeDef,
     CreateDomainRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    DescribeFraudsterResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    CreateWatchlistResponseTypeDef,
+    DescribeWatchlistResponseTypeDef,
+    UpdateWatchlistResponseTypeDef,
     DescribeSpeakerResponseTypeDef,
     OptOutSpeakerResponseTypeDef,
     DomainSummaryTypeDef,
     DomainTypeDef,
     EnrollmentConfigTypeDef,
     FraudRiskDetailsTypeDef,
     FraudsterRegistrationJobSummaryTypeDef,
     SpeakerEnrollmentJobSummaryTypeDef,
     FraudsterRegistrationJobTypeDef,
     StartFraudsterRegistrationJobRequestRequestTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-    ListSpeakersRequestListSpeakersPaginateTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakersResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     ListDomainsResponseTypeDef,
     CreateDomainResponseTypeDef,
     DescribeDomainResponseTypeDef,
     UpdateDomainResponseTypeDef,
     SpeakerEnrollmentJobTypeDef,
     StartSpeakerEnrollmentJobRequestRequestTypeDef,
     FraudDetectionResultTypeDef,
@@ -413,54 +407,54 @@
     StartFraudsterRegistrationJobResponseTypeDef,
     DescribeSpeakerEnrollmentJobResponseTypeDef,
     StartSpeakerEnrollmentJobResponseTypeDef,
     EvaluateSessionResponseTypeDef,
 )
 
 
-def get_structure() -> AuthenticationConfigurationTypeDef:
+def get_structure() -> AssociateFraudsterRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/README.md` & `types-aiobotocore-voice-id-2.5.1/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-voice-id
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.VoiceID 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore voice-id type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-voice-id"></a>
 
 # types-aiobotocore-voice-id
 
 [![PyPI - types-aiobotocore-voice-id](https://img.shields.io/pypi/v/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-voice-id?color=blue)](https://pypistats.org/packages/types-aiobotocore-voice-id)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.VoiceID 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
+[aiobotocore.VoiceID 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
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
 [types-aiobotocore-voice-id docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,32 +274,36 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_voice_id import VoiceIDClient
 from types_aiobotocore_voice_id.paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 
 session = get_session()
 async with session.create_client("voice-id") as client:
     client: VoiceIDClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
     list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = (
         client.get_paginator("list_fraudster_registration_jobs")
     )
+    list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
     list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = (
         client.get_paginator("list_speaker_enrollment_jobs")
     )
     list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+    list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_voice_id.literals` module contains literals extracted from
@@ -280,16 +317,18 @@
     ExistingEnrollmentActionType,
     FraudDetectionActionType,
     FraudDetectionDecisionType,
     FraudDetectionReasonType,
     FraudsterRegistrationJobStatusType,
     ListDomainsPaginatorName,
     ListFraudsterRegistrationJobsPaginatorName,
+    ListFraudstersPaginatorName,
     ListSpeakerEnrollmentJobsPaginatorName,
     ListSpeakersPaginatorName,
+    ListWatchlistsPaginatorName,
     ServerSideEncryptionUpdateStatusType,
     SpeakerEnrollmentJobStatusType,
     SpeakerStatusType,
     StreamingStatusType,
     VoiceIDServiceName,
     ServiceName,
     ResourceServiceName,
@@ -307,70 +346,91 @@
 ### Typed dictionaries
 
 `types_aiobotocore_voice_id.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_voice_id.type_defs import (
+    AssociateFraudsterRequestRequestTypeDef,
+    FraudsterTypeDef,
     AuthenticationConfigurationTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateWatchlistRequestRequestTypeDef,
+    WatchlistTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteFraudsterRequestRequestTypeDef,
     DeleteSpeakerRequestRequestTypeDef,
+    DeleteWatchlistRequestRequestTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeFraudsterRegistrationJobRequestRequestTypeDef,
     DescribeFraudsterRequestRequestTypeDef,
-    FraudsterTypeDef,
     DescribeSpeakerEnrollmentJobRequestRequestTypeDef,
     DescribeSpeakerRequestRequestTypeDef,
     SpeakerTypeDef,
+    DescribeWatchlistRequestRequestTypeDef,
+    DisassociateFraudsterRequestRequestTypeDef,
     ServerSideEncryptionUpdateDetailsTypeDef,
+    WatchlistDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnrollmentJobFraudDetectionConfigTypeDef,
     EvaluateSessionRequestRequestTypeDef,
     FailureDetailsTypeDef,
     FraudDetectionConfigurationTypeDef,
     KnownFraudsterRiskTypeDef,
     VoiceSpoofingRiskTypeDef,
     JobProgressTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     RegistrationConfigTypeDef,
-    PaginatorConfigTypeDef,
+    FraudsterSummaryTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
     ListFraudsterRegistrationJobsRequestRequestTypeDef,
+    ListFraudstersRequestListFraudstersPaginateTypeDef,
+    ListFraudstersRequestRequestTypeDef,
+    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
     ListSpeakerEnrollmentJobsRequestRequestTypeDef,
+    ListSpeakersRequestListSpeakersPaginateTypeDef,
     ListSpeakersRequestRequestTypeDef,
     SpeakerSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWatchlistsRequestListWatchlistsPaginateTypeDef,
+    ListWatchlistsRequestRequestTypeDef,
+    WatchlistSummaryTypeDef,
     OptOutSpeakerRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateWatchlistRequestRequestTypeDef,
+    AssociateFraudsterResponseTypeDef,
+    DescribeFraudsterResponseTypeDef,
+    DisassociateFraudsterResponseTypeDef,
     AuthenticationResultTypeDef,
     UpdateDomainRequestRequestTypeDef,
     CreateDomainRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    DescribeFraudsterResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    CreateWatchlistResponseTypeDef,
+    DescribeWatchlistResponseTypeDef,
+    UpdateWatchlistResponseTypeDef,
     DescribeSpeakerResponseTypeDef,
     OptOutSpeakerResponseTypeDef,
     DomainSummaryTypeDef,
     DomainTypeDef,
     EnrollmentConfigTypeDef,
     FraudRiskDetailsTypeDef,
     FraudsterRegistrationJobSummaryTypeDef,
     SpeakerEnrollmentJobSummaryTypeDef,
     FraudsterRegistrationJobTypeDef,
     StartFraudsterRegistrationJobRequestRequestTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-    ListSpeakersRequestListSpeakersPaginateTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakersResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     ListDomainsResponseTypeDef,
     CreateDomainResponseTypeDef,
     DescribeDomainResponseTypeDef,
     UpdateDomainResponseTypeDef,
     SpeakerEnrollmentJobTypeDef,
     StartSpeakerEnrollmentJobRequestRequestTypeDef,
     FraudDetectionResultTypeDef,
@@ -380,54 +440,54 @@
     StartFraudsterRegistrationJobResponseTypeDef,
     DescribeSpeakerEnrollmentJobResponseTypeDef,
     StartSpeakerEnrollmentJobResponseTypeDef,
     EvaluateSessionResponseTypeDef,
 )
 
 
-def get_structure() -> AuthenticationConfigurationTypeDef:
+def get_structure() -> AssociateFraudsterRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/setup.py` & `types-aiobotocore-voice-id-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-voice-id.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-voice-id",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_voice_id"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.VoiceID 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.VoiceID 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/"
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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__init__.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__init__.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -5,43 +5,50 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_voice_id import (
         Client,
         ListDomainsPaginator,
         ListFraudsterRegistrationJobsPaginator,
+        ListFraudstersPaginator,
         ListSpeakerEnrollmentJobsPaginator,
         ListSpeakersPaginator,
+        ListWatchlistsPaginator,
         VoiceIDClient,
     )
 
     session = get_session()
     async with session.create_client("voice-id") as client:
         client: VoiceIDClient
         ...
 
 
     list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
     list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = client.get_paginator("list_fraudster_registration_jobs")
+    list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
     list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = client.get_paginator("list_speaker_enrollment_jobs")
     list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+    list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
     ```
 """
 from .client import VoiceIDClient
 from .paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 
 Client = VoiceIDClient
 
-
 __all__ = (
     "Client",
     "ListDomainsPaginator",
     "ListFraudsterRegistrationJobsPaginator",
+    "ListFraudstersPaginator",
     "ListSpeakerEnrollmentJobsPaginator",
     "ListSpeakersPaginator",
+    "ListWatchlistsPaginator",
     "VoiceIDClient",
 )
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__init__.pyi` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__init__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,42 +5,51 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_voice_id import (
         Client,
         ListDomainsPaginator,
         ListFraudsterRegistrationJobsPaginator,
+        ListFraudstersPaginator,
         ListSpeakerEnrollmentJobsPaginator,
         ListSpeakersPaginator,
+        ListWatchlistsPaginator,
         VoiceIDClient,
     )
 
     session = get_session()
     async with session.create_client("voice-id") as client:
         client: VoiceIDClient
         ...
 
 
     list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
     list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = client.get_paginator("list_fraudster_registration_jobs")
+    list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
     list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = client.get_paginator("list_speaker_enrollment_jobs")
     list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+    list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
     ```
 """
 from .client import VoiceIDClient
 from .paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 
 Client = VoiceIDClient
 
+
 __all__ = (
     "Client",
     "ListDomainsPaginator",
     "ListFraudsterRegistrationJobsPaginator",
+    "ListFraudstersPaginator",
     "ListSpeakerEnrollmentJobsPaginator",
     "ListSpeakersPaginator",
+    "ListWatchlistsPaginator",
     "VoiceIDClient",
 )
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/__main__.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.VoiceID 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.VoiceID 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID\nOther"
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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/client.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/client.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -20,71 +20,76 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import FraudsterRegistrationJobStatusType, SpeakerEnrollmentJobStatusType
 from .paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 from .type_defs import (
+    AssociateFraudsterResponseTypeDef,
     CreateDomainResponseTypeDef,
+    CreateWatchlistResponseTypeDef,
     DescribeDomainResponseTypeDef,
     DescribeFraudsterRegistrationJobResponseTypeDef,
     DescribeFraudsterResponseTypeDef,
     DescribeSpeakerEnrollmentJobResponseTypeDef,
     DescribeSpeakerResponseTypeDef,
+    DescribeWatchlistResponseTypeDef,
+    DisassociateFraudsterResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     EnrollmentConfigTypeDef,
     EvaluateSessionResponseTypeDef,
     InputDataConfigTypeDef,
     ListDomainsResponseTypeDef,
     ListFraudsterRegistrationJobsResponseTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakerEnrollmentJobsResponseTypeDef,
     ListSpeakersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     OptOutSpeakerResponseTypeDef,
     OutputDataConfigTypeDef,
     RegistrationConfigTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     StartFraudsterRegistrationJobResponseTypeDef,
     StartSpeakerEnrollmentJobResponseTypeDef,
     TagTypeDef,
     UpdateDomainResponseTypeDef,
+    UpdateWatchlistResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("VoiceIDClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class VoiceIDClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
     """
 
     meta: ClientMeta
@@ -93,31 +98,37 @@
     def exceptions(self) -> Exceptions:
         """
         VoiceIDClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#exceptions)
         """
+    async def associate_fraudster(
+        self, *, DomainId: str, FraudsterId: str, WatchlistId: str
+    ) -> AssociateFraudsterResponseTypeDef:
+        """
+        Associates the fraudsters with the watchlist specified in the same domain.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.associate_fraudster)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#associate_fraudster)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#close)
         """
-
     async def create_domain(
         self,
         *,
         Name: str,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         ClientToken: str = ...,
         Description: str = ...,
@@ -126,126 +137,150 @@
         """
         Creates a domain that contains all Amazon Connect Voice ID data, such as
         speakers, fraudsters, customer audio, and voiceprints.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#create_domain)
         """
+    async def create_watchlist(
+        self, *, DomainId: str, Name: str, ClientToken: str = ..., Description: str = ...
+    ) -> CreateWatchlistResponseTypeDef:
+        """
+        Creates a watchlist that fraudsters can be a part of.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.create_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#create_watchlist)
+        """
     async def delete_domain(self, *, DomainId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified domain from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_domain)
         """
-
     async def delete_fraudster(
         self, *, DomainId: str, FraudsterId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified fraudster from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_fraudster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_fraudster)
         """
-
     async def delete_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified speaker from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_speaker)
         """
+    async def delete_watchlist(
+        self, *, DomainId: str, WatchlistId: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the specified watchlist from Voice ID.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_watchlist)
+        """
     async def describe_domain(self, *, DomainId: str) -> DescribeDomainResponseTypeDef:
         """
         Describes the specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_domain)
         """
-
     async def describe_fraudster(
         self, *, DomainId: str, FraudsterId: str
     ) -> DescribeFraudsterResponseTypeDef:
         """
         Describes the specified fraudster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_fraudster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_fraudster)
         """
-
     async def describe_fraudster_registration_job(
         self, *, DomainId: str, JobId: str
     ) -> DescribeFraudsterRegistrationJobResponseTypeDef:
         """
         Describes the specified fraudster registration job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_fraudster_registration_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_fraudster_registration_job)
         """
-
     async def describe_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> DescribeSpeakerResponseTypeDef:
         """
         Describes the specified speaker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_speaker)
         """
-
     async def describe_speaker_enrollment_job(
         self, *, DomainId: str, JobId: str
     ) -> DescribeSpeakerEnrollmentJobResponseTypeDef:
         """
         Describes the specified speaker enrollment job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_speaker_enrollment_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_speaker_enrollment_job)
         """
+    async def describe_watchlist(
+        self, *, DomainId: str, WatchlistId: str
+    ) -> DescribeWatchlistResponseTypeDef:
+        """
+        Describes the specified watchlist.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_watchlist)
+        """
+    async def disassociate_fraudster(
+        self, *, DomainId: str, FraudsterId: str, WatchlistId: str
+    ) -> DisassociateFraudsterResponseTypeDef:
+        """
+        Disassociates the fraudsters from the watchlist specified.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.disassociate_fraudster)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#disassociate_fraudster)
+        """
     async def evaluate_session(
         self, *, DomainId: str, SessionNameOrId: str
     ) -> EvaluateSessionResponseTypeDef:
         """
         Evaluates a specified session based on audio data accumulated during a streaming
         Amazon Connect Voice ID call.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.evaluate_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#evaluate_session)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#generate_presigned_url)
         """
-
     async def list_domains(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListDomainsResponseTypeDef:
         """
         Lists all the domains in the Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_domains)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_domains)
         """
-
     async def list_fraudster_registration_jobs(
         self,
         *,
         DomainId: str,
         JobStatus: FraudsterRegistrationJobStatusType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -253,15 +288,23 @@
         """
         Lists all the fraudster registration jobs in the domain with the given
         `JobStatus`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_fraudster_registration_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_fraudster_registration_jobs)
         """
+    async def list_fraudsters(
+        self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ..., WatchlistId: str = ...
+    ) -> ListFraudstersResponseTypeDef:
+        """
+        Lists all fraudsters in a specified watchlist or domain.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_fraudsters)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_fraudsters)
+        """
     async def list_speaker_enrollment_jobs(
         self,
         *,
         DomainId: str,
         JobStatus: SpeakerEnrollmentJobStatusType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -269,45 +312,50 @@
         """
         Lists all the speaker enrollment jobs in the domain with the specified
         `JobStatus`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_speaker_enrollment_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_speaker_enrollment_jobs)
         """
-
     async def list_speakers(
         self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListSpeakersResponseTypeDef:
         """
         Lists all speakers in a specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_speakers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_speakers)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a specified Voice ID resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_tags_for_resource)
         """
+    async def list_watchlists(
+        self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListWatchlistsResponseTypeDef:
+        """
+        Lists all watchlists in a specified domain.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_watchlists)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_watchlists)
+        """
     async def opt_out_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> OptOutSpeakerResponseTypeDef:
         """
         Opts out a speaker from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.opt_out_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#opt_out_speaker)
         """
-
     async def start_fraudster_registration_job(
         self,
         *,
         DataAccessRoleArn: str,
         DomainId: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
@@ -317,15 +365,14 @@
     ) -> StartFraudsterRegistrationJobResponseTypeDef:
         """
         Starts a new batch fraudster registration job using provided details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.start_fraudster_registration_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#start_fraudster_registration_job)
         """
-
     async def start_speaker_enrollment_job(
         self,
         *,
         DataAccessRoleArn: str,
         DomainId: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
@@ -335,82 +382,94 @@
     ) -> StartSpeakerEnrollmentJobResponseTypeDef:
         """
         Starts a new batch speaker enrollment job using specified details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.start_speaker_enrollment_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#start_speaker_enrollment_job)
         """
-
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a Voice ID resource with the provided list of tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#tag_resource)
         """
-
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes specified tags from a specified Amazon Connect Voice ID resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#untag_resource)
         """
-
     async def update_domain(
         self,
         *,
         DomainId: str,
         Name: str,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         Description: str = ...
     ) -> UpdateDomainResponseTypeDef:
         """
         Updates the specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.update_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#update_domain)
         """
+    async def update_watchlist(
+        self, *, DomainId: str, WatchlistId: str, Description: str = ..., Name: str = ...
+    ) -> UpdateWatchlistResponseTypeDef:
+        """
+        Updates the specified watchlist.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.update_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#update_watchlist)
+        """
     @overload
     def get_paginator(self, operation_name: Literal["list_domains"]) -> ListDomainsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_fraudster_registration_jobs"]
     ) -> ListFraudsterRegistrationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
-
+    @overload
+    def get_paginator(self, operation_name: Literal["list_fraudsters"]) -> ListFraudstersPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_speaker_enrollment_jobs"]
     ) -> ListSpeakerEnrollmentJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_speakers"]) -> ListSpeakersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
-
+    @overload
+    def get_paginator(self, operation_name: Literal["list_watchlists"]) -> ListWatchlistsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
+        """
     async def __aenter__(self) -> "VoiceIDClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
         """
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/client.pyi` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/client.py`

 * *Files 20% similar despite different names*

```diff
@@ -20,67 +20,80 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import FraudsterRegistrationJobStatusType, SpeakerEnrollmentJobStatusType
 from .paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 from .type_defs import (
+    AssociateFraudsterResponseTypeDef,
     CreateDomainResponseTypeDef,
+    CreateWatchlistResponseTypeDef,
     DescribeDomainResponseTypeDef,
     DescribeFraudsterRegistrationJobResponseTypeDef,
     DescribeFraudsterResponseTypeDef,
     DescribeSpeakerEnrollmentJobResponseTypeDef,
     DescribeSpeakerResponseTypeDef,
+    DescribeWatchlistResponseTypeDef,
+    DisassociateFraudsterResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     EnrollmentConfigTypeDef,
     EvaluateSessionResponseTypeDef,
     InputDataConfigTypeDef,
     ListDomainsResponseTypeDef,
     ListFraudsterRegistrationJobsResponseTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakerEnrollmentJobsResponseTypeDef,
     ListSpeakersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     OptOutSpeakerResponseTypeDef,
     OutputDataConfigTypeDef,
     RegistrationConfigTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     StartFraudsterRegistrationJobResponseTypeDef,
     StartSpeakerEnrollmentJobResponseTypeDef,
     TagTypeDef,
     UpdateDomainResponseTypeDef,
+    UpdateWatchlistResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("VoiceIDClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class VoiceIDClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
     """
 
     meta: ClientMeta
@@ -89,28 +102,41 @@
     def exceptions(self) -> Exceptions:
         """
         VoiceIDClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#exceptions)
         """
+
+    async def associate_fraudster(
+        self, *, DomainId: str, FraudsterId: str, WatchlistId: str
+    ) -> AssociateFraudsterResponseTypeDef:
+        """
+        Associates the fraudsters with the watchlist specified in the same domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.associate_fraudster)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#associate_fraudster)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#close)
         """
+
     async def create_domain(
         self,
         *,
         Name: str,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         ClientToken: str = ...,
         Description: str = ...,
@@ -119,114 +145,166 @@
         """
         Creates a domain that contains all Amazon Connect Voice ID data, such as
         speakers, fraudsters, customer audio, and voiceprints.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#create_domain)
         """
+
+    async def create_watchlist(
+        self, *, DomainId: str, Name: str, ClientToken: str = ..., Description: str = ...
+    ) -> CreateWatchlistResponseTypeDef:
+        """
+        Creates a watchlist that fraudsters can be a part of.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.create_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#create_watchlist)
+        """
+
     async def delete_domain(self, *, DomainId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified domain from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_domain)
         """
+
     async def delete_fraudster(
         self, *, DomainId: str, FraudsterId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified fraudster from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_fraudster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_fraudster)
         """
+
     async def delete_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified speaker from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_speaker)
         """
+
+    async def delete_watchlist(
+        self, *, DomainId: str, WatchlistId: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the specified watchlist from Voice ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.delete_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#delete_watchlist)
+        """
+
     async def describe_domain(self, *, DomainId: str) -> DescribeDomainResponseTypeDef:
         """
         Describes the specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_domain)
         """
+
     async def describe_fraudster(
         self, *, DomainId: str, FraudsterId: str
     ) -> DescribeFraudsterResponseTypeDef:
         """
         Describes the specified fraudster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_fraudster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_fraudster)
         """
+
     async def describe_fraudster_registration_job(
         self, *, DomainId: str, JobId: str
     ) -> DescribeFraudsterRegistrationJobResponseTypeDef:
         """
         Describes the specified fraudster registration job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_fraudster_registration_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_fraudster_registration_job)
         """
+
     async def describe_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> DescribeSpeakerResponseTypeDef:
         """
         Describes the specified speaker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_speaker)
         """
+
     async def describe_speaker_enrollment_job(
         self, *, DomainId: str, JobId: str
     ) -> DescribeSpeakerEnrollmentJobResponseTypeDef:
         """
         Describes the specified speaker enrollment job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_speaker_enrollment_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_speaker_enrollment_job)
         """
+
+    async def describe_watchlist(
+        self, *, DomainId: str, WatchlistId: str
+    ) -> DescribeWatchlistResponseTypeDef:
+        """
+        Describes the specified watchlist.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.describe_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#describe_watchlist)
+        """
+
+    async def disassociate_fraudster(
+        self, *, DomainId: str, FraudsterId: str, WatchlistId: str
+    ) -> DisassociateFraudsterResponseTypeDef:
+        """
+        Disassociates the fraudsters from the watchlist specified.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.disassociate_fraudster)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#disassociate_fraudster)
+        """
+
     async def evaluate_session(
         self, *, DomainId: str, SessionNameOrId: str
     ) -> EvaluateSessionResponseTypeDef:
         """
         Evaluates a specified session based on audio data accumulated during a streaming
         Amazon Connect Voice ID call.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.evaluate_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#evaluate_session)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#generate_presigned_url)
         """
+
     async def list_domains(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListDomainsResponseTypeDef:
         """
         Lists all the domains in the Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_domains)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_domains)
         """
+
     async def list_fraudster_registration_jobs(
         self,
         *,
         DomainId: str,
         JobStatus: FraudsterRegistrationJobStatusType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -234,14 +312,25 @@
         """
         Lists all the fraudster registration jobs in the domain with the given
         `JobStatus`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_fraudster_registration_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_fraudster_registration_jobs)
         """
+
+    async def list_fraudsters(
+        self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ..., WatchlistId: str = ...
+    ) -> ListFraudstersResponseTypeDef:
+        """
+        Lists all fraudsters in a specified watchlist or domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_fraudsters)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_fraudsters)
+        """
+
     async def list_speaker_enrollment_jobs(
         self,
         *,
         DomainId: str,
         JobStatus: SpeakerEnrollmentJobStatusType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -249,41 +338,55 @@
         """
         Lists all the speaker enrollment jobs in the domain with the specified
         `JobStatus`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_speaker_enrollment_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_speaker_enrollment_jobs)
         """
+
     async def list_speakers(
         self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListSpeakersResponseTypeDef:
         """
         Lists all speakers in a specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_speakers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_speakers)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a specified Voice ID resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_tags_for_resource)
         """
+
+    async def list_watchlists(
+        self, *, DomainId: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListWatchlistsResponseTypeDef:
+        """
+        Lists all watchlists in a specified domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.list_watchlists)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#list_watchlists)
+        """
+
     async def opt_out_speaker(
         self, *, DomainId: str, SpeakerId: str
     ) -> OptOutSpeakerResponseTypeDef:
         """
         Opts out a speaker from Voice ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.opt_out_speaker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#opt_out_speaker)
         """
+
     async def start_fraudster_registration_job(
         self,
         *,
         DataAccessRoleArn: str,
         DomainId: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
@@ -293,14 +396,15 @@
     ) -> StartFraudsterRegistrationJobResponseTypeDef:
         """
         Starts a new batch fraudster registration job using provided details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.start_fraudster_registration_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#start_fraudster_registration_job)
         """
+
     async def start_speaker_enrollment_job(
         self,
         *,
         DataAccessRoleArn: str,
         DomainId: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
@@ -310,73 +414,106 @@
     ) -> StartSpeakerEnrollmentJobResponseTypeDef:
         """
         Starts a new batch speaker enrollment job using specified details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.start_speaker_enrollment_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#start_speaker_enrollment_job)
         """
+
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a Voice ID resource with the provided list of tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#tag_resource)
         """
+
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes specified tags from a specified Amazon Connect Voice ID resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#untag_resource)
         """
+
     async def update_domain(
         self,
         *,
         DomainId: str,
         Name: str,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef,
         Description: str = ...
     ) -> UpdateDomainResponseTypeDef:
         """
         Updates the specified domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.update_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#update_domain)
         """
+
+    async def update_watchlist(
+        self, *, DomainId: str, WatchlistId: str, Description: str = ..., Name: str = ...
+    ) -> UpdateWatchlistResponseTypeDef:
+        """
+        Updates the specified watchlist.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.update_watchlist)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#update_watchlist)
+        """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_domains"]) -> ListDomainsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_fraudster_registration_jobs"]
     ) -> ListFraudsterRegistrationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_fraudsters"]) -> ListFraudstersPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_speaker_enrollment_jobs"]
     ) -> ListSpeakerEnrollmentJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_speakers"]) -> ListSpeakersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
         """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_watchlists"]) -> ListWatchlistsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "VoiceIDClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/client/)
         """
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/literals.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,16 +26,18 @@
     "ExistingEnrollmentActionType",
     "FraudDetectionActionType",
     "FraudDetectionDecisionType",
     "FraudDetectionReasonType",
     "FraudsterRegistrationJobStatusType",
     "ListDomainsPaginatorName",
     "ListFraudsterRegistrationJobsPaginatorName",
+    "ListFraudstersPaginatorName",
     "ListSpeakerEnrollmentJobsPaginatorName",
     "ListSpeakersPaginatorName",
+    "ListWatchlistsPaginatorName",
     "ServerSideEncryptionUpdateStatusType",
     "SpeakerEnrollmentJobStatusType",
     "SpeakerStatusType",
     "StreamingStatusType",
     "VoiceIDServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -60,16 +62,18 @@
 FraudDetectionDecisionType = Literal["HIGH_RISK", "LOW_RISK", "NOT_ENOUGH_SPEECH"]
 FraudDetectionReasonType = Literal["KNOWN_FRAUDSTER", "VOICE_SPOOFING"]
 FraudsterRegistrationJobStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"
 ]
 ListDomainsPaginatorName = Literal["list_domains"]
 ListFraudsterRegistrationJobsPaginatorName = Literal["list_fraudster_registration_jobs"]
+ListFraudstersPaginatorName = Literal["list_fraudsters"]
 ListSpeakerEnrollmentJobsPaginatorName = Literal["list_speaker_enrollment_jobs"]
 ListSpeakersPaginatorName = Literal["list_speakers"]
+ListWatchlistsPaginatorName = Literal["list_watchlists"]
 ServerSideEncryptionUpdateStatusType = Literal["COMPLETED", "FAILED", "IN_PROGRESS"]
 SpeakerEnrollmentJobStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"
 ]
 SpeakerStatusType = Literal["ENROLLED", "EXPIRED", "OPTED_OUT", "PENDING"]
 StreamingStatusType = Literal["ENDED", "ONGOING", "PENDING_CONFIGURATION"]
 VoiceIDServiceName = Literal["voice-id"]
@@ -131,14 +135,15 @@
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
@@ -217,14 +222,15 @@
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
@@ -235,14 +241,15 @@
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
@@ -278,14 +285,15 @@
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
@@ -304,16 +312,19 @@
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
@@ -397,15 +408,17 @@
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
@@ -426,16 +439,18 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_domains",
     "list_fraudster_registration_jobs",
+    "list_fraudsters",
     "list_speaker_enrollment_jobs",
     "list_speakers",
+    "list_watchlists",
 ]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/literals.pyi` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -25,16 +25,18 @@
     "ExistingEnrollmentActionType",
     "FraudDetectionActionType",
     "FraudDetectionDecisionType",
     "FraudDetectionReasonType",
     "FraudsterRegistrationJobStatusType",
     "ListDomainsPaginatorName",
     "ListFraudsterRegistrationJobsPaginatorName",
+    "ListFraudstersPaginatorName",
     "ListSpeakerEnrollmentJobsPaginatorName",
     "ListSpeakersPaginatorName",
+    "ListWatchlistsPaginatorName",
     "ServerSideEncryptionUpdateStatusType",
     "SpeakerEnrollmentJobStatusType",
     "SpeakerStatusType",
     "StreamingStatusType",
     "VoiceIDServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -58,16 +60,18 @@
 FraudDetectionDecisionType = Literal["HIGH_RISK", "LOW_RISK", "NOT_ENOUGH_SPEECH"]
 FraudDetectionReasonType = Literal["KNOWN_FRAUDSTER", "VOICE_SPOOFING"]
 FraudsterRegistrationJobStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"
 ]
 ListDomainsPaginatorName = Literal["list_domains"]
 ListFraudsterRegistrationJobsPaginatorName = Literal["list_fraudster_registration_jobs"]
+ListFraudstersPaginatorName = Literal["list_fraudsters"]
 ListSpeakerEnrollmentJobsPaginatorName = Literal["list_speaker_enrollment_jobs"]
 ListSpeakersPaginatorName = Literal["list_speakers"]
+ListWatchlistsPaginatorName = Literal["list_watchlists"]
 ServerSideEncryptionUpdateStatusType = Literal["COMPLETED", "FAILED", "IN_PROGRESS"]
 SpeakerEnrollmentJobStatusType = Literal[
     "COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"
 ]
 SpeakerStatusType = Literal["ENROLLED", "EXPIRED", "OPTED_OUT", "PENDING"]
 StreamingStatusType = Literal["ENDED", "ONGOING", "PENDING_CONFIGURATION"]
 VoiceIDServiceName = Literal["voice-id"]
@@ -129,14 +133,15 @@
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
@@ -215,14 +220,15 @@
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
@@ -233,14 +239,15 @@
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
@@ -276,14 +283,15 @@
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
@@ -302,16 +310,19 @@
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
@@ -395,15 +406,17 @@
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
@@ -424,16 +437,18 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_domains",
     "list_fraudster_registration_jobs",
+    "list_fraudsters",
     "list_speaker_enrollment_jobs",
     "list_speakers",
+    "list_watchlists",
 ]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/paginator.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/paginator.py`

 * *Files 19% similar despite different names*

```diff
@@ -8,54 +8,55 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_voice_id.client import VoiceIDClient
     from types_aiobotocore_voice_id.paginator import (
         ListDomainsPaginator,
         ListFraudsterRegistrationJobsPaginator,
+        ListFraudstersPaginator,
         ListSpeakerEnrollmentJobsPaginator,
         ListSpeakersPaginator,
+        ListWatchlistsPaginator,
     )
 
     session = get_session()
     with session.create_client("voice-id") as client:
         client: VoiceIDClient
 
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = client.get_paginator("list_fraudster_registration_jobs")
+        list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
         list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = client.get_paginator("list_speaker_enrollment_jobs")
         list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+        list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FraudsterRegistrationJobStatusType, SpeakerEnrollmentJobStatusType
 from .type_defs import (
     ListDomainsResponseTypeDef,
     ListFraudsterRegistrationJobsResponseTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakerEnrollmentJobsResponseTypeDef,
     ListSpeakersResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDomainsPaginator",
     "ListFraudsterRegistrationJobsPaginator",
+    "ListFraudstersPaginator",
     "ListSpeakerEnrollmentJobsPaginator",
     "ListSpeakersPaginator",
+    "ListWatchlistsPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -68,15 +69,15 @@
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listdomainspaginator)
         """
 
 
@@ -87,47 +88,81 @@
     """
 
     def paginate(
         self,
         *,
         DomainId: str,
         JobStatus: FraudsterRegistrationJobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFraudsterRegistrationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsterRegistrationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterregistrationjobspaginator)
         """
 
 
+class ListFraudstersPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsters)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        DomainId: str,
+        WatchlistId: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListFraudstersResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsters.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterspaginator)
+        """
+
+
 class ListSpeakerEnrollmentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakerEnrollmentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerenrollmentjobspaginator)
     """
 
     def paginate(
         self,
         *,
         DomainId: str,
         JobStatus: SpeakerEnrollmentJobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeakerEnrollmentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakerEnrollmentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerenrollmentjobspaginator)
         """
 
 
 class ListSpeakersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerspaginator)
     """
 
     def paginate(
-        self, *, DomainId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DomainId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeakersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerspaginator)
         """
+
+
+class ListWatchlistsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListWatchlists)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listwatchlistspaginator)
+    """
+
+    def paginate(
+        self, *, DomainId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListWatchlistsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListWatchlists.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listwatchlistspaginator)
+        """
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/paginator.pyi` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/paginator.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -8,53 +8,55 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_voice_id.client import VoiceIDClient
     from types_aiobotocore_voice_id.paginator import (
         ListDomainsPaginator,
         ListFraudsterRegistrationJobsPaginator,
+        ListFraudstersPaginator,
         ListSpeakerEnrollmentJobsPaginator,
         ListSpeakersPaginator,
+        ListWatchlistsPaginator,
     )
 
     session = get_session()
     with session.create_client("voice-id") as client:
         client: VoiceIDClient
 
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = client.get_paginator("list_fraudster_registration_jobs")
+        list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
         list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = client.get_paginator("list_speaker_enrollment_jobs")
         list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+        list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FraudsterRegistrationJobStatusType, SpeakerEnrollmentJobStatusType
 from .type_defs import (
     ListDomainsResponseTypeDef,
     ListFraudsterRegistrationJobsResponseTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakerEnrollmentJobsResponseTypeDef,
     ListSpeakersResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDomainsPaginator",
     "ListFraudsterRegistrationJobsPaginator",
+    "ListFraudstersPaginator",
     "ListSpeakerEnrollmentJobsPaginator",
     "ListSpeakersPaginator",
+    "ListWatchlistsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -64,15 +66,15 @@
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listdomainspaginator)
         """
 
 class ListFraudsterRegistrationJobsPaginator(AioPaginator):
@@ -82,45 +84,77 @@
     """
 
     def paginate(
         self,
         *,
         DomainId: str,
         JobStatus: FraudsterRegistrationJobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFraudsterRegistrationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsterRegistrationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterregistrationjobspaginator)
         """
 
+class ListFraudstersPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsters)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        DomainId: str,
+        WatchlistId: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListFraudstersResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListFraudsters.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listfraudsterspaginator)
+        """
+
 class ListSpeakerEnrollmentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakerEnrollmentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerenrollmentjobspaginator)
     """
 
     def paginate(
         self,
         *,
         DomainId: str,
         JobStatus: SpeakerEnrollmentJobStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeakerEnrollmentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakerEnrollmentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerenrollmentjobspaginator)
         """
 
 class ListSpeakersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerspaginator)
     """
 
     def paginate(
-        self, *, DomainId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DomainId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeakersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListSpeakers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listspeakerspaginator)
         """
+
+class ListWatchlistsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListWatchlists)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listwatchlistspaginator)
+    """
+
+    def paginate(
+        self, *, DomainId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListWatchlistsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID.Paginator.ListWatchlists.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/paginators/#listwatchlistspaginator)
+        """
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/type_defs.py` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for voice-id service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_voice_id.type_defs import AuthenticationConfigurationTypeDef
+    from types_aiobotocore_voice_id.type_defs import AssociateFraudsterRequestRequestTypeDef
 
-    data: AuthenticationConfigurationTypeDef = {...}
+    data: AssociateFraudsterRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
@@ -31,72 +31,92 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
+    "AssociateFraudsterRequestRequestTypeDef",
+    "FraudsterTypeDef",
     "AuthenticationConfigurationTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateWatchlistRequestRequestTypeDef",
+    "WatchlistTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteFraudsterRequestRequestTypeDef",
     "DeleteSpeakerRequestRequestTypeDef",
+    "DeleteWatchlistRequestRequestTypeDef",
     "DescribeDomainRequestRequestTypeDef",
     "DescribeFraudsterRegistrationJobRequestRequestTypeDef",
     "DescribeFraudsterRequestRequestTypeDef",
-    "FraudsterTypeDef",
     "DescribeSpeakerEnrollmentJobRequestRequestTypeDef",
     "DescribeSpeakerRequestRequestTypeDef",
     "SpeakerTypeDef",
+    "DescribeWatchlistRequestRequestTypeDef",
+    "DisassociateFraudsterRequestRequestTypeDef",
     "ServerSideEncryptionUpdateDetailsTypeDef",
+    "WatchlistDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnrollmentJobFraudDetectionConfigTypeDef",
     "EvaluateSessionRequestRequestTypeDef",
     "FailureDetailsTypeDef",
     "FraudDetectionConfigurationTypeDef",
     "KnownFraudsterRiskTypeDef",
     "VoiceSpoofingRiskTypeDef",
     "JobProgressTypeDef",
     "InputDataConfigTypeDef",
     "OutputDataConfigTypeDef",
     "RegistrationConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "FraudsterSummaryTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
     "ListFraudsterRegistrationJobsRequestRequestTypeDef",
+    "ListFraudstersRequestListFraudstersPaginateTypeDef",
+    "ListFraudstersRequestRequestTypeDef",
+    "ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
     "ListSpeakerEnrollmentJobsRequestRequestTypeDef",
+    "ListSpeakersRequestListSpeakersPaginateTypeDef",
     "ListSpeakersRequestRequestTypeDef",
     "SpeakerSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    "ListWatchlistsRequestRequestTypeDef",
+    "WatchlistSummaryTypeDef",
     "OptOutSpeakerRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateWatchlistRequestRequestTypeDef",
+    "AssociateFraudsterResponseTypeDef",
+    "DescribeFraudsterResponseTypeDef",
+    "DisassociateFraudsterResponseTypeDef",
     "AuthenticationResultTypeDef",
     "UpdateDomainRequestRequestTypeDef",
     "CreateDomainRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "DescribeFraudsterResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "CreateWatchlistResponseTypeDef",
+    "DescribeWatchlistResponseTypeDef",
+    "UpdateWatchlistResponseTypeDef",
     "DescribeSpeakerResponseTypeDef",
     "OptOutSpeakerResponseTypeDef",
     "DomainSummaryTypeDef",
     "DomainTypeDef",
     "EnrollmentConfigTypeDef",
     "FraudRiskDetailsTypeDef",
     "FraudsterRegistrationJobSummaryTypeDef",
     "SpeakerEnrollmentJobSummaryTypeDef",
     "FraudsterRegistrationJobTypeDef",
     "StartFraudsterRegistrationJobRequestRequestTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-    "ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
-    "ListSpeakersRequestListSpeakersPaginateTypeDef",
+    "ListFraudstersResponseTypeDef",
     "ListSpeakersResponseTypeDef",
+    "ListWatchlistsResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "CreateDomainResponseTypeDef",
     "DescribeDomainResponseTypeDef",
     "UpdateDomainResponseTypeDef",
     "SpeakerEnrollmentJobTypeDef",
     "StartSpeakerEnrollmentJobRequestRequestTypeDef",
     "FraudDetectionResultTypeDef",
@@ -105,14 +125,34 @@
     "DescribeFraudsterRegistrationJobResponseTypeDef",
     "StartFraudsterRegistrationJobResponseTypeDef",
     "DescribeSpeakerEnrollmentJobResponseTypeDef",
     "StartSpeakerEnrollmentJobResponseTypeDef",
     "EvaluateSessionResponseTypeDef",
 )
 
+AssociateFraudsterRequestRequestTypeDef = TypedDict(
+    "AssociateFraudsterRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "FraudsterId": str,
+        "WatchlistId": str,
+    },
+)
+
+FraudsterTypeDef = TypedDict(
+    "FraudsterTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DomainId": str,
+        "GeneratedFraudsterId": str,
+        "WatchlistIds": List[str],
+    },
+    total=False,
+)
+
 AuthenticationConfigurationTypeDef = TypedDict(
     "AuthenticationConfigurationTypeDef",
     {
         "AcceptanceThreshold": int,
     },
 )
 
@@ -127,23 +167,47 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+_RequiredCreateWatchlistRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateWatchlistRequestRequestTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DomainId": str,
+        "Name": str,
+    },
+)
+_OptionalCreateWatchlistRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateWatchlistRequestRequestTypeDef",
+    {
+        "ClientToken": str,
+        "Description": str,
     },
+    total=False,
+)
+
+class CreateWatchlistRequestRequestTypeDef(
+    _RequiredCreateWatchlistRequestRequestTypeDef, _OptionalCreateWatchlistRequestRequestTypeDef
+):
+    pass
+
+WatchlistTypeDef = TypedDict(
+    "WatchlistTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DefaultWatchlist": bool,
+        "Description": str,
+        "DomainId": str,
+        "Name": str,
+        "UpdatedAt": datetime,
+        "WatchlistId": str,
+    },
+    total=False,
 )
 
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainId": str,
     },
@@ -161,14 +225,22 @@
     "DeleteSpeakerRequestRequestTypeDef",
     {
         "DomainId": str,
         "SpeakerId": str,
     },
 )
 
+DeleteWatchlistRequestRequestTypeDef = TypedDict(
+    "DeleteWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 
@@ -184,24 +256,14 @@
     "DescribeFraudsterRequestRequestTypeDef",
     {
         "DomainId": str,
         "FraudsterId": str,
     },
 )
 
-FraudsterTypeDef = TypedDict(
-    "FraudsterTypeDef",
-    {
-        "CreatedAt": datetime,
-        "DomainId": str,
-        "GeneratedFraudsterId": str,
-    },
-    total=False,
-)
-
 DescribeSpeakerEnrollmentJobRequestRequestTypeDef = TypedDict(
     "DescribeSpeakerEnrollmentJobRequestRequestTypeDef",
     {
         "DomainId": str,
         "JobId": str,
     },
 )
@@ -224,29 +286,61 @@
         "LastAccessedAt": datetime,
         "Status": SpeakerStatusType,
         "UpdatedAt": datetime,
     },
     total=False,
 )
 
+DescribeWatchlistRequestRequestTypeDef = TypedDict(
+    "DescribeWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+
+DisassociateFraudsterRequestRequestTypeDef = TypedDict(
+    "DisassociateFraudsterRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "FraudsterId": str,
+        "WatchlistId": str,
+    },
+)
+
 ServerSideEncryptionUpdateDetailsTypeDef = TypedDict(
     "ServerSideEncryptionUpdateDetailsTypeDef",
     {
         "Message": str,
         "OldKmsKeyId": str,
         "UpdateStatus": ServerSideEncryptionUpdateStatusType,
     },
     total=False,
 )
 
+WatchlistDetailsTypeDef = TypedDict(
+    "WatchlistDetailsTypeDef",
+    {
+        "DefaultWatchlistId": str,
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnrollmentJobFraudDetectionConfigTypeDef = TypedDict(
     "EnrollmentJobFraudDetectionConfigTypeDef",
     {
         "FraudDetectionAction": FraudDetectionActionType,
         "RiskThreshold": int,
+        "WatchlistIds": List[str],
     },
     total=False,
 )
 
 EvaluateSessionRequestRequestTypeDef = TypedDict(
     "EvaluateSessionRequestRequestTypeDef",
     {
@@ -264,15 +358,17 @@
     total=False,
 )
 
 FraudDetectionConfigurationTypeDef = TypedDict(
     "FraudDetectionConfigurationTypeDef",
     {
         "RiskThreshold": int,
+        "WatchlistId": str,
     },
+    total=False,
 )
 
 _RequiredKnownFraudsterRiskTypeDef = TypedDict(
     "_RequiredKnownFraudsterRiskTypeDef",
     {
         "RiskScore": int,
     },
@@ -281,21 +377,19 @@
     "_OptionalKnownFraudsterRiskTypeDef",
     {
         "GeneratedFraudsterId": str,
     },
     total=False,
 )
 
-
 class KnownFraudsterRiskTypeDef(
     _RequiredKnownFraudsterRiskTypeDef, _OptionalKnownFraudsterRiskTypeDef
 ):
     pass
 
-
 VoiceSpoofingRiskTypeDef = TypedDict(
     "VoiceSpoofingRiskTypeDef",
     {
         "RiskScore": int,
     },
 )
 
@@ -324,47 +418,80 @@
     "_OptionalOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
-
 class OutputDataConfigTypeDef(_RequiredOutputDataConfigTypeDef, _OptionalOutputDataConfigTypeDef):
     pass
 
-
 RegistrationConfigTypeDef = TypedDict(
     "RegistrationConfigTypeDef",
     {
         "DuplicateRegistrationAction": DuplicateRegistrationActionType,
         "FraudsterSimilarityThreshold": int,
+        "WatchlistIds": List[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FraudsterSummaryTypeDef = TypedDict(
+    "FraudsterSummaryTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CreatedAt": datetime,
+        "DomainId": str,
+        "GeneratedFraudsterId": str,
+        "WatchlistIds": List[str],
+    },
+    total=False,
+)
+
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
+        {
+            "DomainId": str,
+        },
+    )
+)
+_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
+        {
+            "JobStatus": FraudsterRegistrationJobStatusType,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef(
+    _RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
+    _OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListFraudsterRegistrationJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListFraudsterRegistrationJobsRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 _OptionalListFraudsterRegistrationJobsRequestRequestTypeDef = TypedDict(
@@ -373,21 +500,82 @@
         "JobStatus": FraudsterRegistrationJobStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListFraudsterRegistrationJobsRequestRequestTypeDef(
     _RequiredListFraudsterRegistrationJobsRequestRequestTypeDef,
     _OptionalListFraudsterRegistrationJobsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListFraudstersRequestListFraudstersPaginateTypeDef = TypedDict(
+    "_RequiredListFraudstersRequestListFraudstersPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListFraudstersRequestListFraudstersPaginateTypeDef = TypedDict(
+    "_OptionalListFraudstersRequestListFraudstersPaginateTypeDef",
+    {
+        "WatchlistId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFraudstersRequestListFraudstersPaginateTypeDef(
+    _RequiredListFraudstersRequestListFraudstersPaginateTypeDef,
+    _OptionalListFraudstersRequestListFraudstersPaginateTypeDef,
+):
+    pass
+
+_RequiredListFraudstersRequestRequestTypeDef = TypedDict(
+    "_RequiredListFraudstersRequestRequestTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListFraudstersRequestRequestTypeDef = TypedDict(
+    "_OptionalListFraudstersRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+        "WatchlistId": str,
+    },
+    total=False,
+)
+
+class ListFraudstersRequestRequestTypeDef(
+    _RequiredListFraudstersRequestRequestTypeDef, _OptionalListFraudstersRequestRequestTypeDef
+):
+    pass
+
+_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
+    "_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
+    "_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
+    {
+        "JobStatus": SpeakerEnrollmentJobStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef(
+    _RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
+    _OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
+):
+    pass
 
 _RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
@@ -397,21 +585,39 @@
         "JobStatus": SpeakerEnrollmentJobStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListSpeakerEnrollmentJobsRequestRequestTypeDef(
     _RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef,
     _OptionalListSpeakerEnrollmentJobsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
+    "_RequiredListSpeakersRequestListSpeakersPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
+    "_OptionalListSpeakersRequestListSpeakersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSpeakersRequestListSpeakersPaginateTypeDef(
+    _RequiredListSpeakersRequestListSpeakersPaginateTypeDef,
+    _OptionalListSpeakersRequestListSpeakersPaginateTypeDef,
+):
+    pass
 
 _RequiredListSpeakersRequestRequestTypeDef = TypedDict(
     "_RequiredListSpeakersRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
@@ -420,21 +626,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListSpeakersRequestRequestTypeDef(
     _RequiredListSpeakersRequestRequestTypeDef, _OptionalListSpeakersRequestRequestTypeDef
 ):
     pass
 
-
 SpeakerSummaryTypeDef = TypedDict(
     "SpeakerSummaryTypeDef",
     {
         "CreatedAt": datetime,
         "CustomerSpeakerId": str,
         "DomainId": str,
         "GeneratedSpeakerId": str,
@@ -448,30 +652,150 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+_RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef = TypedDict(
+    "_RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef = TypedDict(
+    "_OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWatchlistsRequestListWatchlistsPaginateTypeDef(
+    _RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef,
+    _OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef,
+):
+    pass
+
+_RequiredListWatchlistsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWatchlistsRequestRequestTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListWatchlistsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWatchlistsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class ListWatchlistsRequestRequestTypeDef(
+    _RequiredListWatchlistsRequestRequestTypeDef, _OptionalListWatchlistsRequestRequestTypeDef
+):
+    pass
+
+WatchlistSummaryTypeDef = TypedDict(
+    "WatchlistSummaryTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DefaultWatchlist": bool,
+        "Description": str,
+        "DomainId": str,
+        "Name": str,
+        "UpdatedAt": datetime,
+        "WatchlistId": str,
+    },
+    total=False,
+)
+
 OptOutSpeakerRequestRequestTypeDef = TypedDict(
     "OptOutSpeakerRequestRequestTypeDef",
     {
         "DomainId": str,
         "SpeakerId": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+_RequiredUpdateWatchlistRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+_OptionalUpdateWatchlistRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateWatchlistRequestRequestTypeDef",
+    {
+        "Description": str,
+        "Name": str,
+    },
+    total=False,
+)
+
+class UpdateWatchlistRequestRequestTypeDef(
+    _RequiredUpdateWatchlistRequestRequestTypeDef, _OptionalUpdateWatchlistRequestRequestTypeDef
+):
+    pass
+
+AssociateFraudsterResponseTypeDef = TypedDict(
+    "AssociateFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeFraudsterResponseTypeDef = TypedDict(
+    "DescribeFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateFraudsterResponseTypeDef = TypedDict(
+    "DisassociateFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AuthenticationResultTypeDef = TypedDict(
     "AuthenticationResultTypeDef",
     {
         "AudioAggregationEndedAt": datetime,
         "AudioAggregationStartedAt": datetime,
         "AuthenticationResultId": str,
         "Configuration": AuthenticationConfigurationTypeDef,
@@ -495,21 +819,19 @@
     "_OptionalUpdateDomainRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateDomainRequestRequestTypeDef(
     _RequiredUpdateDomainRequestRequestTypeDef, _OptionalUpdateDomainRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
     },
 )
@@ -519,65 +841,72 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+CreateWatchlistResponseTypeDef = TypedDict(
+    "CreateWatchlistResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+DescribeWatchlistResponseTypeDef = TypedDict(
+    "DescribeWatchlistResponseTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeFraudsterResponseTypeDef = TypedDict(
-    "DescribeFraudsterResponseTypeDef",
+UpdateWatchlistResponseTypeDef = TypedDict(
+    "UpdateWatchlistResponseTypeDef",
     {
-        "Fraudster": FraudsterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSpeakerResponseTypeDef = TypedDict(
     "DescribeSpeakerResponseTypeDef",
     {
         "Speaker": SpeakerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptOutSpeakerResponseTypeDef = TypedDict(
     "OptOutSpeakerResponseTypeDef",
     {
         "Speaker": SpeakerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainSummaryTypeDef = TypedDict(
     "DomainSummaryTypeDef",
     {
         "Arn": str,
@@ -585,14 +914,15 @@
         "Description": str,
         "DomainId": str,
         "DomainStatus": DomainStatusType,
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
         "ServerSideEncryptionUpdateDetails": ServerSideEncryptionUpdateDetailsTypeDef,
         "UpdatedAt": datetime,
+        "WatchlistDetails": WatchlistDetailsTypeDef,
     },
     total=False,
 )
 
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
@@ -601,14 +931,15 @@
         "Description": str,
         "DomainId": str,
         "DomainStatus": DomainStatusType,
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
         "ServerSideEncryptionUpdateDetails": ServerSideEncryptionUpdateDetailsTypeDef,
         "UpdatedAt": datetime,
+        "WatchlistDetails": WatchlistDetailsTypeDef,
     },
     total=False,
 )
 
 EnrollmentConfigTypeDef = TypedDict(
     "EnrollmentConfigTypeDef",
     {
@@ -690,141 +1021,77 @@
         "ClientToken": str,
         "JobName": str,
         "RegistrationConfig": RegistrationConfigTypeDef,
     },
     total=False,
 )
 
-
 class StartFraudsterRegistrationJobRequestRequestTypeDef(
     _RequiredStartFraudsterRegistrationJobRequestRequestTypeDef,
     _OptionalStartFraudsterRegistrationJobRequestRequestTypeDef,
 ):
     pass
 
-
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
+ListFraudstersResponseTypeDef = TypedDict(
+    "ListFraudstersResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-        {
-            "DomainId": str,
-        },
-    )
-)
-_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-        {
-            "JobStatus": FraudsterRegistrationJobStatusType,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef(
-    _RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-    _OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
-    "_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
-    {
-        "DomainId": str,
-    },
-)
-_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
-    "_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
-    {
-        "JobStatus": SpeakerEnrollmentJobStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FraudsterSummaries": List[FraudsterSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef(
-    _RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-    _OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
-    "_RequiredListSpeakersRequestListSpeakersPaginateTypeDef",
-    {
-        "DomainId": str,
-    },
-)
-_OptionalListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
-    "_OptionalListSpeakersRequestListSpeakersPaginateTypeDef",
+ListSpeakersResponseTypeDef = TypedDict(
+    "ListSpeakersResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "SpeakerSummaries": List[SpeakerSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListSpeakersRequestListSpeakersPaginateTypeDef(
-    _RequiredListSpeakersRequestListSpeakersPaginateTypeDef,
-    _OptionalListSpeakersRequestListSpeakersPaginateTypeDef,
-):
-    pass
-
-
-ListSpeakersResponseTypeDef = TypedDict(
-    "ListSpeakersResponseTypeDef",
+ListWatchlistsResponseTypeDef = TypedDict(
+    "ListWatchlistsResponseTypeDef",
     {
         "NextToken": str,
-        "SpeakerSummaries": List[SpeakerSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "WatchlistSummaries": List[WatchlistSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "DomainSummaries": List[DomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResponseTypeDef = TypedDict(
     "DescribeDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainResponseTypeDef = TypedDict(
     "UpdateDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SpeakerEnrollmentJobTypeDef = TypedDict(
     "SpeakerEnrollmentJobTypeDef",
     {
         "CreatedAt": datetime,
@@ -858,22 +1125,20 @@
         "ClientToken": str,
         "EnrollmentConfig": EnrollmentConfigTypeDef,
         "JobName": str,
     },
     total=False,
 )
 
-
 class StartSpeakerEnrollmentJobRequestRequestTypeDef(
     _RequiredStartSpeakerEnrollmentJobRequestRequestTypeDef,
     _OptionalStartSpeakerEnrollmentJobRequestRequestTypeDef,
 ):
     pass
 
-
 FraudDetectionResultTypeDef = TypedDict(
     "FraudDetectionResultTypeDef",
     {
         "AudioAggregationEndedAt": datetime,
         "AudioAggregationStartedAt": datetime,
         "Configuration": FraudDetectionConfigurationTypeDef,
         "Decision": FraudDetectionDecisionType,
@@ -885,64 +1150,64 @@
 )
 
 ListFraudsterRegistrationJobsResponseTypeDef = TypedDict(
     "ListFraudsterRegistrationJobsResponseTypeDef",
     {
         "JobSummaries": List[FraudsterRegistrationJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpeakerEnrollmentJobsResponseTypeDef = TypedDict(
     "ListSpeakerEnrollmentJobsResponseTypeDef",
     {
         "JobSummaries": List[SpeakerEnrollmentJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFraudsterRegistrationJobResponseTypeDef = TypedDict(
     "DescribeFraudsterRegistrationJobResponseTypeDef",
     {
         "Job": FraudsterRegistrationJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartFraudsterRegistrationJobResponseTypeDef = TypedDict(
     "StartFraudsterRegistrationJobResponseTypeDef",
     {
         "Job": FraudsterRegistrationJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSpeakerEnrollmentJobResponseTypeDef = TypedDict(
     "DescribeSpeakerEnrollmentJobResponseTypeDef",
     {
         "Job": SpeakerEnrollmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSpeakerEnrollmentJobResponseTypeDef = TypedDict(
     "StartSpeakerEnrollmentJobResponseTypeDef",
     {
         "Job": SpeakerEnrollmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EvaluateSessionResponseTypeDef = TypedDict(
     "EvaluateSessionResponseTypeDef",
     {
         "AuthenticationResult": AuthenticationResultTypeDef,
         "DomainId": str,
         "FraudDetectionResult": FraudDetectionResultTypeDef,
         "SessionId": str,
         "SessionName": str,
         "StreamingStatus": StreamingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id/type_defs.pyi` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id/type_defs.py`

 * *Files 22% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for voice-id service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_voice_id.type_defs import AuthenticationConfigurationTypeDef
+    from types_aiobotocore_voice_id.type_defs import AssociateFraudsterRequestRequestTypeDef
 
-    data: AuthenticationConfigurationTypeDef = {...}
+    data: AssociateFraudsterRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
@@ -31,71 +31,93 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
+    "AssociateFraudsterRequestRequestTypeDef",
+    "FraudsterTypeDef",
     "AuthenticationConfigurationTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateWatchlistRequestRequestTypeDef",
+    "WatchlistTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteFraudsterRequestRequestTypeDef",
     "DeleteSpeakerRequestRequestTypeDef",
+    "DeleteWatchlistRequestRequestTypeDef",
     "DescribeDomainRequestRequestTypeDef",
     "DescribeFraudsterRegistrationJobRequestRequestTypeDef",
     "DescribeFraudsterRequestRequestTypeDef",
-    "FraudsterTypeDef",
     "DescribeSpeakerEnrollmentJobRequestRequestTypeDef",
     "DescribeSpeakerRequestRequestTypeDef",
     "SpeakerTypeDef",
+    "DescribeWatchlistRequestRequestTypeDef",
+    "DisassociateFraudsterRequestRequestTypeDef",
     "ServerSideEncryptionUpdateDetailsTypeDef",
+    "WatchlistDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnrollmentJobFraudDetectionConfigTypeDef",
     "EvaluateSessionRequestRequestTypeDef",
     "FailureDetailsTypeDef",
     "FraudDetectionConfigurationTypeDef",
     "KnownFraudsterRiskTypeDef",
     "VoiceSpoofingRiskTypeDef",
     "JobProgressTypeDef",
     "InputDataConfigTypeDef",
     "OutputDataConfigTypeDef",
     "RegistrationConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "FraudsterSummaryTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
     "ListFraudsterRegistrationJobsRequestRequestTypeDef",
+    "ListFraudstersRequestListFraudstersPaginateTypeDef",
+    "ListFraudstersRequestRequestTypeDef",
+    "ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
     "ListSpeakerEnrollmentJobsRequestRequestTypeDef",
+    "ListSpeakersRequestListSpeakersPaginateTypeDef",
     "ListSpeakersRequestRequestTypeDef",
     "SpeakerSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    "ListWatchlistsRequestRequestTypeDef",
+    "WatchlistSummaryTypeDef",
     "OptOutSpeakerRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateWatchlistRequestRequestTypeDef",
+    "AssociateFraudsterResponseTypeDef",
+    "DescribeFraudsterResponseTypeDef",
+    "DisassociateFraudsterResponseTypeDef",
     "AuthenticationResultTypeDef",
     "UpdateDomainRequestRequestTypeDef",
     "CreateDomainRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "DescribeFraudsterResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "CreateWatchlistResponseTypeDef",
+    "DescribeWatchlistResponseTypeDef",
+    "UpdateWatchlistResponseTypeDef",
     "DescribeSpeakerResponseTypeDef",
     "OptOutSpeakerResponseTypeDef",
     "DomainSummaryTypeDef",
     "DomainTypeDef",
     "EnrollmentConfigTypeDef",
     "FraudRiskDetailsTypeDef",
     "FraudsterRegistrationJobSummaryTypeDef",
     "SpeakerEnrollmentJobSummaryTypeDef",
     "FraudsterRegistrationJobTypeDef",
     "StartFraudsterRegistrationJobRequestRequestTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-    "ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
-    "ListSpeakersRequestListSpeakersPaginateTypeDef",
+    "ListFraudstersResponseTypeDef",
     "ListSpeakersResponseTypeDef",
+    "ListWatchlistsResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "CreateDomainResponseTypeDef",
     "DescribeDomainResponseTypeDef",
     "UpdateDomainResponseTypeDef",
     "SpeakerEnrollmentJobTypeDef",
     "StartSpeakerEnrollmentJobRequestRequestTypeDef",
     "FraudDetectionResultTypeDef",
@@ -104,14 +126,34 @@
     "DescribeFraudsterRegistrationJobResponseTypeDef",
     "StartFraudsterRegistrationJobResponseTypeDef",
     "DescribeSpeakerEnrollmentJobResponseTypeDef",
     "StartSpeakerEnrollmentJobResponseTypeDef",
     "EvaluateSessionResponseTypeDef",
 )
 
+AssociateFraudsterRequestRequestTypeDef = TypedDict(
+    "AssociateFraudsterRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "FraudsterId": str,
+        "WatchlistId": str,
+    },
+)
+
+FraudsterTypeDef = TypedDict(
+    "FraudsterTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DomainId": str,
+        "GeneratedFraudsterId": str,
+        "WatchlistIds": List[str],
+    },
+    total=False,
+)
+
 AuthenticationConfigurationTypeDef = TypedDict(
     "AuthenticationConfigurationTypeDef",
     {
         "AcceptanceThreshold": int,
     },
 )
 
@@ -126,23 +168,49 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+_RequiredCreateWatchlistRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateWatchlistRequestRequestTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DomainId": str,
+        "Name": str,
+    },
+)
+_OptionalCreateWatchlistRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateWatchlistRequestRequestTypeDef",
+    {
+        "ClientToken": str,
+        "Description": str,
+    },
+    total=False,
+)
+
+
+class CreateWatchlistRequestRequestTypeDef(
+    _RequiredCreateWatchlistRequestRequestTypeDef, _OptionalCreateWatchlistRequestRequestTypeDef
+):
+    pass
+
+
+WatchlistTypeDef = TypedDict(
+    "WatchlistTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DefaultWatchlist": bool,
+        "Description": str,
+        "DomainId": str,
+        "Name": str,
+        "UpdatedAt": datetime,
+        "WatchlistId": str,
     },
+    total=False,
 )
 
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainId": str,
     },
@@ -160,14 +228,22 @@
     "DeleteSpeakerRequestRequestTypeDef",
     {
         "DomainId": str,
         "SpeakerId": str,
     },
 )
 
+DeleteWatchlistRequestRequestTypeDef = TypedDict(
+    "DeleteWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 
@@ -183,24 +259,14 @@
     "DescribeFraudsterRequestRequestTypeDef",
     {
         "DomainId": str,
         "FraudsterId": str,
     },
 )
 
-FraudsterTypeDef = TypedDict(
-    "FraudsterTypeDef",
-    {
-        "CreatedAt": datetime,
-        "DomainId": str,
-        "GeneratedFraudsterId": str,
-    },
-    total=False,
-)
-
 DescribeSpeakerEnrollmentJobRequestRequestTypeDef = TypedDict(
     "DescribeSpeakerEnrollmentJobRequestRequestTypeDef",
     {
         "DomainId": str,
         "JobId": str,
     },
 )
@@ -223,29 +289,61 @@
         "LastAccessedAt": datetime,
         "Status": SpeakerStatusType,
         "UpdatedAt": datetime,
     },
     total=False,
 )
 
+DescribeWatchlistRequestRequestTypeDef = TypedDict(
+    "DescribeWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+
+DisassociateFraudsterRequestRequestTypeDef = TypedDict(
+    "DisassociateFraudsterRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "FraudsterId": str,
+        "WatchlistId": str,
+    },
+)
+
 ServerSideEncryptionUpdateDetailsTypeDef = TypedDict(
     "ServerSideEncryptionUpdateDetailsTypeDef",
     {
         "Message": str,
         "OldKmsKeyId": str,
         "UpdateStatus": ServerSideEncryptionUpdateStatusType,
     },
     total=False,
 )
 
+WatchlistDetailsTypeDef = TypedDict(
+    "WatchlistDetailsTypeDef",
+    {
+        "DefaultWatchlistId": str,
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnrollmentJobFraudDetectionConfigTypeDef = TypedDict(
     "EnrollmentJobFraudDetectionConfigTypeDef",
     {
         "FraudDetectionAction": FraudDetectionActionType,
         "RiskThreshold": int,
+        "WatchlistIds": List[str],
     },
     total=False,
 )
 
 EvaluateSessionRequestRequestTypeDef = TypedDict(
     "EvaluateSessionRequestRequestTypeDef",
     {
@@ -263,15 +361,17 @@
     total=False,
 )
 
 FraudDetectionConfigurationTypeDef = TypedDict(
     "FraudDetectionConfigurationTypeDef",
     {
         "RiskThreshold": int,
+        "WatchlistId": str,
     },
+    total=False,
 )
 
 _RequiredKnownFraudsterRiskTypeDef = TypedDict(
     "_RequiredKnownFraudsterRiskTypeDef",
     {
         "RiskScore": int,
     },
@@ -280,19 +380,21 @@
     "_OptionalKnownFraudsterRiskTypeDef",
     {
         "GeneratedFraudsterId": str,
     },
     total=False,
 )
 
+
 class KnownFraudsterRiskTypeDef(
     _RequiredKnownFraudsterRiskTypeDef, _OptionalKnownFraudsterRiskTypeDef
 ):
     pass
 
+
 VoiceSpoofingRiskTypeDef = TypedDict(
     "VoiceSpoofingRiskTypeDef",
     {
         "RiskScore": int,
     },
 )
 
@@ -321,45 +423,84 @@
     "_OptionalOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
+
 class OutputDataConfigTypeDef(_RequiredOutputDataConfigTypeDef, _OptionalOutputDataConfigTypeDef):
     pass
 
+
 RegistrationConfigTypeDef = TypedDict(
     "RegistrationConfigTypeDef",
     {
         "DuplicateRegistrationAction": DuplicateRegistrationActionType,
         "FraudsterSimilarityThreshold": int,
+        "WatchlistIds": List[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FraudsterSummaryTypeDef = TypedDict(
+    "FraudsterSummaryTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CreatedAt": datetime,
+        "DomainId": str,
+        "GeneratedFraudsterId": str,
+        "WatchlistIds": List[str],
+    },
+    total=False,
+)
+
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
+        {
+            "DomainId": str,
+        },
+    )
+)
+_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
+        {
+            "JobStatus": FraudsterRegistrationJobStatusType,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef(
+    _RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
+    _OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFraudsterRegistrationJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListFraudsterRegistrationJobsRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 _OptionalListFraudsterRegistrationJobsRequestRequestTypeDef = TypedDict(
@@ -368,20 +509,91 @@
         "JobStatus": FraudsterRegistrationJobStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListFraudsterRegistrationJobsRequestRequestTypeDef(
     _RequiredListFraudsterRegistrationJobsRequestRequestTypeDef,
     _OptionalListFraudsterRegistrationJobsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListFraudstersRequestListFraudstersPaginateTypeDef = TypedDict(
+    "_RequiredListFraudstersRequestListFraudstersPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListFraudstersRequestListFraudstersPaginateTypeDef = TypedDict(
+    "_OptionalListFraudstersRequestListFraudstersPaginateTypeDef",
+    {
+        "WatchlistId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFraudstersRequestListFraudstersPaginateTypeDef(
+    _RequiredListFraudstersRequestListFraudstersPaginateTypeDef,
+    _OptionalListFraudstersRequestListFraudstersPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListFraudstersRequestRequestTypeDef = TypedDict(
+    "_RequiredListFraudstersRequestRequestTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListFraudstersRequestRequestTypeDef = TypedDict(
+    "_OptionalListFraudstersRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+        "WatchlistId": str,
+    },
+    total=False,
+)
+
+
+class ListFraudstersRequestRequestTypeDef(
+    _RequiredListFraudstersRequestRequestTypeDef, _OptionalListFraudstersRequestRequestTypeDef
+):
+    pass
+
+
+_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
+    "_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
+    "_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
+    {
+        "JobStatus": SpeakerEnrollmentJobStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef(
+    _RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
+    _OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 _OptionalListSpeakerEnrollmentJobsRequestRequestTypeDef = TypedDict(
@@ -390,20 +602,44 @@
         "JobStatus": SpeakerEnrollmentJobStatusType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListSpeakerEnrollmentJobsRequestRequestTypeDef(
     _RequiredListSpeakerEnrollmentJobsRequestRequestTypeDef,
     _OptionalListSpeakerEnrollmentJobsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
+    "_RequiredListSpeakersRequestListSpeakersPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
+    "_OptionalListSpeakersRequestListSpeakersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSpeakersRequestListSpeakersPaginateTypeDef(
+    _RequiredListSpeakersRequestListSpeakersPaginateTypeDef,
+    _OptionalListSpeakersRequestListSpeakersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSpeakersRequestRequestTypeDef = TypedDict(
     "_RequiredListSpeakersRequestRequestTypeDef",
     {
         "DomainId": str,
     },
 )
 _OptionalListSpeakersRequestRequestTypeDef = TypedDict(
@@ -411,19 +647,21 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListSpeakersRequestRequestTypeDef(
     _RequiredListSpeakersRequestRequestTypeDef, _OptionalListSpeakersRequestRequestTypeDef
 ):
     pass
 
+
 SpeakerSummaryTypeDef = TypedDict(
     "SpeakerSummaryTypeDef",
     {
         "CreatedAt": datetime,
         "CustomerSpeakerId": str,
         "DomainId": str,
         "GeneratedSpeakerId": str,
@@ -437,30 +675,156 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+_RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef = TypedDict(
+    "_RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef = TypedDict(
+    "_OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWatchlistsRequestListWatchlistsPaginateTypeDef(
+    _RequiredListWatchlistsRequestListWatchlistsPaginateTypeDef,
+    _OptionalListWatchlistsRequestListWatchlistsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListWatchlistsRequestRequestTypeDef = TypedDict(
+    "_RequiredListWatchlistsRequestRequestTypeDef",
+    {
+        "DomainId": str,
+    },
+)
+_OptionalListWatchlistsRequestRequestTypeDef = TypedDict(
+    "_OptionalListWatchlistsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class ListWatchlistsRequestRequestTypeDef(
+    _RequiredListWatchlistsRequestRequestTypeDef, _OptionalListWatchlistsRequestRequestTypeDef
+):
+    pass
+
+
+WatchlistSummaryTypeDef = TypedDict(
+    "WatchlistSummaryTypeDef",
+    {
+        "CreatedAt": datetime,
+        "DefaultWatchlist": bool,
+        "Description": str,
+        "DomainId": str,
+        "Name": str,
+        "UpdatedAt": datetime,
+        "WatchlistId": str,
+    },
+    total=False,
+)
+
 OptOutSpeakerRequestRequestTypeDef = TypedDict(
     "OptOutSpeakerRequestRequestTypeDef",
     {
         "DomainId": str,
         "SpeakerId": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+_RequiredUpdateWatchlistRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateWatchlistRequestRequestTypeDef",
+    {
+        "DomainId": str,
+        "WatchlistId": str,
+    },
+)
+_OptionalUpdateWatchlistRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateWatchlistRequestRequestTypeDef",
+    {
+        "Description": str,
+        "Name": str,
+    },
+    total=False,
+)
+
+
+class UpdateWatchlistRequestRequestTypeDef(
+    _RequiredUpdateWatchlistRequestRequestTypeDef, _OptionalUpdateWatchlistRequestRequestTypeDef
+):
+    pass
+
+
+AssociateFraudsterResponseTypeDef = TypedDict(
+    "AssociateFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeFraudsterResponseTypeDef = TypedDict(
+    "DescribeFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateFraudsterResponseTypeDef = TypedDict(
+    "DisassociateFraudsterResponseTypeDef",
+    {
+        "Fraudster": FraudsterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AuthenticationResultTypeDef = TypedDict(
     "AuthenticationResultTypeDef",
     {
         "AudioAggregationEndedAt": datetime,
         "AudioAggregationStartedAt": datetime,
         "AuthenticationResultId": str,
         "Configuration": AuthenticationConfigurationTypeDef,
@@ -484,19 +848,21 @@
     "_OptionalUpdateDomainRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateDomainRequestRequestTypeDef(
     _RequiredUpdateDomainRequestRequestTypeDef, _OptionalUpdateDomainRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
     },
 )
@@ -506,63 +872,74 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+CreateWatchlistResponseTypeDef = TypedDict(
+    "CreateWatchlistResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+DescribeWatchlistResponseTypeDef = TypedDict(
+    "DescribeWatchlistResponseTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeFraudsterResponseTypeDef = TypedDict(
-    "DescribeFraudsterResponseTypeDef",
+UpdateWatchlistResponseTypeDef = TypedDict(
+    "UpdateWatchlistResponseTypeDef",
     {
-        "Fraudster": FraudsterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Watchlist": WatchlistTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSpeakerResponseTypeDef = TypedDict(
     "DescribeSpeakerResponseTypeDef",
     {
         "Speaker": SpeakerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptOutSpeakerResponseTypeDef = TypedDict(
     "OptOutSpeakerResponseTypeDef",
     {
         "Speaker": SpeakerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainSummaryTypeDef = TypedDict(
     "DomainSummaryTypeDef",
     {
         "Arn": str,
@@ -570,14 +947,15 @@
         "Description": str,
         "DomainId": str,
         "DomainStatus": DomainStatusType,
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
         "ServerSideEncryptionUpdateDetails": ServerSideEncryptionUpdateDetailsTypeDef,
         "UpdatedAt": datetime,
+        "WatchlistDetails": WatchlistDetailsTypeDef,
     },
     total=False,
 )
 
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
@@ -586,14 +964,15 @@
         "Description": str,
         "DomainId": str,
         "DomainStatus": DomainStatusType,
         "Name": str,
         "ServerSideEncryptionConfiguration": ServerSideEncryptionConfigurationTypeDef,
         "ServerSideEncryptionUpdateDetails": ServerSideEncryptionUpdateDetailsTypeDef,
         "UpdatedAt": datetime,
+        "WatchlistDetails": WatchlistDetailsTypeDef,
     },
     total=False,
 )
 
 EnrollmentConfigTypeDef = TypedDict(
     "EnrollmentConfigTypeDef",
     {
@@ -675,133 +1054,79 @@
         "ClientToken": str,
         "JobName": str,
         "RegistrationConfig": RegistrationConfigTypeDef,
     },
     total=False,
 )
 
+
 class StartFraudsterRegistrationJobRequestRequestTypeDef(
     _RequiredStartFraudsterRegistrationJobRequestRequestTypeDef,
     _OptionalStartFraudsterRegistrationJobRequestRequestTypeDef,
 ):
     pass
 
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-        {
-            "DomainId": str,
-        },
-    )
-)
-_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef",
-        {
-            "JobStatus": FraudsterRegistrationJobStatusType,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef(
-    _RequiredListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-    _OptionalListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
-    "_RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
-    {
-        "DomainId": str,
-    },
-)
-_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef = TypedDict(
-    "_OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef",
+ListFraudstersResponseTypeDef = TypedDict(
+    "ListFraudstersResponseTypeDef",
     {
-        "JobStatus": SpeakerEnrollmentJobStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FraudsterSummaries": List[FraudsterSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef(
-    _RequiredListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-    _OptionalListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
-    "_RequiredListSpeakersRequestListSpeakersPaginateTypeDef",
+ListSpeakersResponseTypeDef = TypedDict(
+    "ListSpeakersResponseTypeDef",
     {
-        "DomainId": str,
+        "NextToken": str,
+        "SpeakerSummaries": List[SpeakerSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListSpeakersRequestListSpeakersPaginateTypeDef = TypedDict(
-    "_OptionalListSpeakersRequestListSpeakersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSpeakersRequestListSpeakersPaginateTypeDef(
-    _RequiredListSpeakersRequestListSpeakersPaginateTypeDef,
-    _OptionalListSpeakersRequestListSpeakersPaginateTypeDef,
-):
-    pass
 
-ListSpeakersResponseTypeDef = TypedDict(
-    "ListSpeakersResponseTypeDef",
+ListWatchlistsResponseTypeDef = TypedDict(
+    "ListWatchlistsResponseTypeDef",
     {
         "NextToken": str,
-        "SpeakerSummaries": List[SpeakerSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "WatchlistSummaries": List[WatchlistSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "DomainSummaries": List[DomainSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResponseTypeDef = TypedDict(
     "DescribeDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainResponseTypeDef = TypedDict(
     "UpdateDomainResponseTypeDef",
     {
         "Domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SpeakerEnrollmentJobTypeDef = TypedDict(
     "SpeakerEnrollmentJobTypeDef",
     {
         "CreatedAt": datetime,
@@ -835,20 +1160,22 @@
         "ClientToken": str,
         "EnrollmentConfig": EnrollmentConfigTypeDef,
         "JobName": str,
     },
     total=False,
 )
 
+
 class StartSpeakerEnrollmentJobRequestRequestTypeDef(
     _RequiredStartSpeakerEnrollmentJobRequestRequestTypeDef,
     _OptionalStartSpeakerEnrollmentJobRequestRequestTypeDef,
 ):
     pass
 
+
 FraudDetectionResultTypeDef = TypedDict(
     "FraudDetectionResultTypeDef",
     {
         "AudioAggregationEndedAt": datetime,
         "AudioAggregationStartedAt": datetime,
         "Configuration": FraudDetectionConfigurationTypeDef,
         "Decision": FraudDetectionDecisionType,
@@ -860,64 +1187,64 @@
 )
 
 ListFraudsterRegistrationJobsResponseTypeDef = TypedDict(
     "ListFraudsterRegistrationJobsResponseTypeDef",
     {
         "JobSummaries": List[FraudsterRegistrationJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpeakerEnrollmentJobsResponseTypeDef = TypedDict(
     "ListSpeakerEnrollmentJobsResponseTypeDef",
     {
         "JobSummaries": List[SpeakerEnrollmentJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFraudsterRegistrationJobResponseTypeDef = TypedDict(
     "DescribeFraudsterRegistrationJobResponseTypeDef",
     {
         "Job": FraudsterRegistrationJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartFraudsterRegistrationJobResponseTypeDef = TypedDict(
     "StartFraudsterRegistrationJobResponseTypeDef",
     {
         "Job": FraudsterRegistrationJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSpeakerEnrollmentJobResponseTypeDef = TypedDict(
     "DescribeSpeakerEnrollmentJobResponseTypeDef",
     {
         "Job": SpeakerEnrollmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSpeakerEnrollmentJobResponseTypeDef = TypedDict(
     "StartSpeakerEnrollmentJobResponseTypeDef",
     {
         "Job": SpeakerEnrollmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EvaluateSessionResponseTypeDef = TypedDict(
     "EvaluateSessionResponseTypeDef",
     {
         "AuthenticationResult": AuthenticationResultTypeDef,
         "DomainId": str,
         "FraudDetectionResult": FraudDetectionResultTypeDef,
         "SessionId": str,
         "SessionName": str,
         "StreamingStatus": StreamingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/PKG-INFO` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-voice-id
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.VoiceID 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.VoiceID 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-voice-id"></a>
 
 # types-aiobotocore-voice-id
 
 [![PyPI - types-aiobotocore-voice-id](https://img.shields.io/pypi/v/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-voice-id.svg?color=blue)](https://pypi.org/project/types-aiobotocore-voice-id)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-voice-id?color=blue)](https://pypistats.org/packages/types-aiobotocore-voice-id)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.VoiceID 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
+[aiobotocore.VoiceID 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/voice-id.html#VoiceID)
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
 [types-aiobotocore-voice-id docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,32 +274,36 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_voice_id import VoiceIDClient
 from types_aiobotocore_voice_id.paginator import (
     ListDomainsPaginator,
     ListFraudsterRegistrationJobsPaginator,
+    ListFraudstersPaginator,
     ListSpeakerEnrollmentJobsPaginator,
     ListSpeakersPaginator,
+    ListWatchlistsPaginator,
 )
 
 session = get_session()
 async with session.create_client("voice-id") as client:
     client: VoiceIDClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
     list_fraudster_registration_jobs_paginator: ListFraudsterRegistrationJobsPaginator = (
         client.get_paginator("list_fraudster_registration_jobs")
     )
+    list_fraudsters_paginator: ListFraudstersPaginator = client.get_paginator("list_fraudsters")
     list_speaker_enrollment_jobs_paginator: ListSpeakerEnrollmentJobsPaginator = (
         client.get_paginator("list_speaker_enrollment_jobs")
     )
     list_speakers_paginator: ListSpeakersPaginator = client.get_paginator("list_speakers")
+    list_watchlists_paginator: ListWatchlistsPaginator = client.get_paginator("list_watchlists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_voice_id.literals` module contains literals extracted from
@@ -313,16 +317,18 @@
     ExistingEnrollmentActionType,
     FraudDetectionActionType,
     FraudDetectionDecisionType,
     FraudDetectionReasonType,
     FraudsterRegistrationJobStatusType,
     ListDomainsPaginatorName,
     ListFraudsterRegistrationJobsPaginatorName,
+    ListFraudstersPaginatorName,
     ListSpeakerEnrollmentJobsPaginatorName,
     ListSpeakersPaginatorName,
+    ListWatchlistsPaginatorName,
     ServerSideEncryptionUpdateStatusType,
     SpeakerEnrollmentJobStatusType,
     SpeakerStatusType,
     StreamingStatusType,
     VoiceIDServiceName,
     ServiceName,
     ResourceServiceName,
@@ -340,70 +346,91 @@
 ### Typed dictionaries
 
 `types_aiobotocore_voice_id.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_voice_id.type_defs import (
+    AssociateFraudsterRequestRequestTypeDef,
+    FraudsterTypeDef,
     AuthenticationConfigurationTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateWatchlistRequestRequestTypeDef,
+    WatchlistTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteFraudsterRequestRequestTypeDef,
     DeleteSpeakerRequestRequestTypeDef,
+    DeleteWatchlistRequestRequestTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeFraudsterRegistrationJobRequestRequestTypeDef,
     DescribeFraudsterRequestRequestTypeDef,
-    FraudsterTypeDef,
     DescribeSpeakerEnrollmentJobRequestRequestTypeDef,
     DescribeSpeakerRequestRequestTypeDef,
     SpeakerTypeDef,
+    DescribeWatchlistRequestRequestTypeDef,
+    DisassociateFraudsterRequestRequestTypeDef,
     ServerSideEncryptionUpdateDetailsTypeDef,
+    WatchlistDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnrollmentJobFraudDetectionConfigTypeDef,
     EvaluateSessionRequestRequestTypeDef,
     FailureDetailsTypeDef,
     FraudDetectionConfigurationTypeDef,
     KnownFraudsterRiskTypeDef,
     VoiceSpoofingRiskTypeDef,
     JobProgressTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     RegistrationConfigTypeDef,
-    PaginatorConfigTypeDef,
+    FraudsterSummaryTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
     ListFraudsterRegistrationJobsRequestRequestTypeDef,
+    ListFraudstersRequestListFraudstersPaginateTypeDef,
+    ListFraudstersRequestRequestTypeDef,
+    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
     ListSpeakerEnrollmentJobsRequestRequestTypeDef,
+    ListSpeakersRequestListSpeakersPaginateTypeDef,
     ListSpeakersRequestRequestTypeDef,
     SpeakerSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWatchlistsRequestListWatchlistsPaginateTypeDef,
+    ListWatchlistsRequestRequestTypeDef,
+    WatchlistSummaryTypeDef,
     OptOutSpeakerRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateWatchlistRequestRequestTypeDef,
+    AssociateFraudsterResponseTypeDef,
+    DescribeFraudsterResponseTypeDef,
+    DisassociateFraudsterResponseTypeDef,
     AuthenticationResultTypeDef,
     UpdateDomainRequestRequestTypeDef,
     CreateDomainRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    DescribeFraudsterResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    CreateWatchlistResponseTypeDef,
+    DescribeWatchlistResponseTypeDef,
+    UpdateWatchlistResponseTypeDef,
     DescribeSpeakerResponseTypeDef,
     OptOutSpeakerResponseTypeDef,
     DomainSummaryTypeDef,
     DomainTypeDef,
     EnrollmentConfigTypeDef,
     FraudRiskDetailsTypeDef,
     FraudsterRegistrationJobSummaryTypeDef,
     SpeakerEnrollmentJobSummaryTypeDef,
     FraudsterRegistrationJobTypeDef,
     StartFraudsterRegistrationJobRequestRequestTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    ListFraudsterRegistrationJobsRequestListFraudsterRegistrationJobsPaginateTypeDef,
-    ListSpeakerEnrollmentJobsRequestListSpeakerEnrollmentJobsPaginateTypeDef,
-    ListSpeakersRequestListSpeakersPaginateTypeDef,
+    ListFraudstersResponseTypeDef,
     ListSpeakersResponseTypeDef,
+    ListWatchlistsResponseTypeDef,
     ListDomainsResponseTypeDef,
     CreateDomainResponseTypeDef,
     DescribeDomainResponseTypeDef,
     UpdateDomainResponseTypeDef,
     SpeakerEnrollmentJobTypeDef,
     StartSpeakerEnrollmentJobRequestRequestTypeDef,
     FraudDetectionResultTypeDef,
@@ -413,54 +440,54 @@
     StartFraudsterRegistrationJobResponseTypeDef,
     DescribeSpeakerEnrollmentJobResponseTypeDef,
     StartSpeakerEnrollmentJobResponseTypeDef,
     EvaluateSessionResponseTypeDef,
 )
 
 
-def get_structure() -> AuthenticationConfigurationTypeDef:
+def get_structure() -> AssociateFraudsterRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-voice-id-2.5.0.post1/types_aiobotocore_voice_id.egg-info/SOURCES.txt` & `types-aiobotocore-voice-id-2.5.1/types_aiobotocore_voice_id.egg-info/SOURCES.txt`

 * *Files identical despite different names*

