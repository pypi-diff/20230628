# Comparing `tmp/types-aiobotocore-omics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-omics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-omics-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-omics-2.5.1.tar", last modified: Wed Jun 28 01:43:55 2023, max compression
```

## Comparing `types-aiobotocore-omics-2.5.0.post1.tar` & `types-aiobotocore-omics-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.835467 types-aiobotocore-omics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28329 2023-03-11 12:27:03.835467 types-aiobotocore-omics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    26766 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.835467 types-aiobotocore-omics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.835467 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/
--rw-r--r--   0 runner    (1001) docker     (123)     7056 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7055 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    58948 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    58842 2023-03-11 12:19:18.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14923 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14921 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20452 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    20433 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    87487 2023-03-11 12:19:22.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    87347 2023-03-11 12:19:21.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:17.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    15908 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    15892 2023-03-11 12:19:20.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.835467 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28329 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      844 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:03.000000 types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.694186 types-aiobotocore-omics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    29712 2023-06-28 01:43:55.694186 types-aiobotocore-omics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    28155 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:55.694186 types-aiobotocore-omics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.682186 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/
+-rw-r--r--   0 runner    (1001) docker     (123)     7574 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7573 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    64784 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    64670 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15766 2023-06-28 01:36:04.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15764 2023-06-28 01:36:04.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    22937 2023-06-28 01:36:04.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22917 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    97569 2023-06-28 01:36:06.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    97413 2023-06-28 01:36:05.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:03.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15945 2023-06-28 01:36:04.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15929 2023-06-28 01:36:04.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.694186 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    29712 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      844 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:55.000000 types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/LICENSE` & `types-aiobotocore-omics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-omics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-omics-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-omics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Omics 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore omics type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-omics"></a>
 
 # types-aiobotocore-omics
 
 [![PyPI - types-aiobotocore-omics](https://img.shields.io/pypi/v/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-omics?color=blue)](https://pypistats.org/packages/types-aiobotocore-omics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Omics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
+[aiobotocore.Omics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
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
 [types-aiobotocore-omics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,17 +241,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_omics import OmicsClient
 from types_aiobotocore_omics.paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReadSetsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferenceStoresPaginator,
     ListReferencesPaginator,
     ListRunGroupsPaginator,
     ListRunTasksPaginator,
     ListRunsPaginator,
@@ -302,23 +271,29 @@
     # Types should be correctly discovered by mypy and IDEs
     list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator(
         "list_annotation_import_jobs"
     )
     list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator(
         "list_annotation_stores"
     )
+    list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = (
+        client.get_paginator("list_multipart_read_set_uploads")
+    )
     list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = (
         client.get_paginator("list_read_set_activation_jobs")
     )
     list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator(
         "list_read_set_export_jobs"
     )
     list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator(
         "list_read_set_import_jobs"
     )
+    list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator(
+        "list_read_set_upload_parts"
+    )
     list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
     list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator(
         "list_reference_import_jobs"
     )
     list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator(
         "list_reference_stores"
     )
@@ -415,27 +390,30 @@
 ### Literals
 
 `types_aiobotocore_omics.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_omics.literals import (
+    AcceleratorsType,
     AnnotationImportJobCreatedWaiterName,
     AnnotationStoreCreatedWaiterName,
     AnnotationStoreDeletedWaiterName,
     AnnotationTypeType,
     EncryptionTypeType,
     FileTypeType,
     FormatToHeaderKeyType,
     JobStatusType,
     ListAnnotationImportJobsPaginatorName,
     ListAnnotationStoresPaginatorName,
+    ListMultipartReadSetUploadsPaginatorName,
     ListReadSetActivationJobsPaginatorName,
     ListReadSetExportJobsPaginatorName,
     ListReadSetImportJobsPaginatorName,
+    ListReadSetUploadPartsPaginatorName,
     ListReadSetsPaginatorName,
     ListReferenceImportJobsPaginatorName,
     ListReferenceStoresPaginatorName,
     ListReferencesPaginatorName,
     ListRunGroupsPaginatorName,
     ListRunTasksPaginatorName,
     ListRunsPaginatorName,
@@ -449,14 +427,15 @@
     ReadSetExportJobCompletedWaiterName,
     ReadSetExportJobItemStatusType,
     ReadSetExportJobStatusType,
     ReadSetFileType,
     ReadSetImportJobCompletedWaiterName,
     ReadSetImportJobItemStatusType,
     ReadSetImportJobStatusType,
+    ReadSetPartSourceType,
     ReadSetStatusType,
     ReferenceFileType,
     ReferenceImportJobCompletedWaiterName,
     ReferenceImportJobItemStatusType,
     ReferenceImportJobStatusType,
     ReferenceStatusType,
     RunCompletedWaiterName,
@@ -479,54 +458,64 @@
     WorkflowStatusType,
     WorkflowTypeType,
     OmicsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
-def check_value(value: AnnotationImportJobCreatedWaiterName) -> bool:
+def check_value(value: AcceleratorsType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_omics.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_omics.type_defs import (
+    AbortMultipartReadSetUploadRequestRequestTypeDef,
     ActivateReadSetFilterTypeDef,
     ActivateReadSetJobItemTypeDef,
     ActivateReadSetSourceItemTypeDef,
     AnnotationImportItemDetailTypeDef,
     AnnotationImportItemSourceTypeDef,
     AnnotationImportJobItemTypeDef,
     ReferenceItemTypeDef,
     SseConfigTypeDef,
     BatchDeleteReadSetRequestRequestTypeDef,
     ReadSetBatchErrorTypeDef,
-    ResponseMetadataTypeDef,
     CancelAnnotationImportRequestRequestTypeDef,
     CancelRunRequestRequestTypeDef,
     CancelVariantImportRequestRequestTypeDef,
+    CompleteReadSetUploadPartListItemTypeDef,
+    CompleteMultipartReadSetUploadResponseTypeDef,
+    CreateMultipartReadSetUploadRequestRequestTypeDef,
+    CreateMultipartReadSetUploadResponseTypeDef,
     CreateRunGroupRequestRequestTypeDef,
+    CreateRunGroupResponseTypeDef,
     WorkflowParameterTypeDef,
+    CreateWorkflowResponseTypeDef,
     DeleteAnnotationStoreRequestRequestTypeDef,
+    DeleteAnnotationStoreResponseTypeDef,
     DeleteReferenceRequestRequestTypeDef,
     DeleteReferenceStoreRequestRequestTypeDef,
     DeleteRunGroupRequestRequestTypeDef,
     DeleteRunRequestRequestTypeDef,
     DeleteSequenceStoreRequestRequestTypeDef,
     DeleteVariantStoreRequestRequestTypeDef,
+    DeleteVariantStoreResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportReadSetDetailTypeDef,
     ExportReadSetFilterTypeDef,
     ExportReadSetJobDetailTypeDef,
     ExportReadSetTypeDef,
     FileInformationTypeDef,
     VcfOptionsTypeDef,
     WaiterConfigTypeDef,
@@ -534,104 +523,114 @@
     GetAnnotationStoreRequestRequestTypeDef,
     GetReadSetActivationJobRequestRequestTypeDef,
     GetReadSetExportJobRequestRequestTypeDef,
     GetReadSetImportJobRequestRequestTypeDef,
     GetReadSetMetadataRequestRequestTypeDef,
     SequenceInformationTypeDef,
     GetReadSetRequestRequestTypeDef,
+    GetReadSetResponseTypeDef,
     GetReferenceImportJobRequestRequestTypeDef,
     ImportReferenceSourceItemTypeDef,
     GetReferenceMetadataRequestRequestTypeDef,
     GetReferenceRequestRequestTypeDef,
+    GetReferenceResponseTypeDef,
     GetReferenceStoreRequestRequestTypeDef,
     GetRunGroupRequestRequestTypeDef,
+    GetRunGroupResponseTypeDef,
     GetRunRequestRequestTypeDef,
+    GetRunResponseTypeDef,
     GetRunTaskRequestRequestTypeDef,
+    GetRunTaskResponseTypeDef,
     GetSequenceStoreRequestRequestTypeDef,
     GetVariantImportRequestRequestTypeDef,
     VariantImportItemDetailTypeDef,
     GetVariantStoreRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReadSetJobItemTypeDef,
     SourceFilesTypeDef,
     ImportReferenceFilterTypeDef,
     ImportReferenceJobItemTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListAnnotationStoresFilterTypeDef,
+    ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+    ListMultipartReadSetUploadsRequestRequestTypeDef,
+    MultipartReadSetUploadListItemTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
+    ReadSetUploadPartListItemTypeDef,
     ReadSetFilterTypeDef,
     ReferenceStoreFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceListItemTypeDef,
+    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
     ListRunGroupsRequestRequestTypeDef,
     RunGroupListItemTypeDef,
+    ListRunTasksRequestListRunTasksPaginateTypeDef,
     ListRunTasksRequestRequestTypeDef,
     TaskListItemTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
     RunListItemTypeDef,
     SequenceStoreFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     VariantImportJobItemTypeDef,
     ListVariantStoresFilterTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     WorkflowListItemTypeDef,
+    PaginatorConfigTypeDef,
     ReadOptionsTypeDef,
+    ResponseMetadataTypeDef,
+    StartAnnotationImportResponseTypeDef,
     StartReadSetActivationJobSourceItemTypeDef,
+    StartReadSetActivationJobResponseTypeDef,
+    StartReadSetExportJobResponseTypeDef,
+    StartReadSetImportJobResponseTypeDef,
     StartReferenceImportJobSourceItemTypeDef,
+    StartReferenceImportJobResponseTypeDef,
     StartRunRequestRequestTypeDef,
+    StartRunResponseTypeDef,
     VariantImportItemSourceTypeDef,
+    StartVariantImportResponseTypeDef,
     TsvStoreOptionsTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAnnotationStoreRequestRequestTypeDef,
     UpdateRunGroupRequestRequestTypeDef,
     UpdateVariantStoreRequestRequestTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UploadReadSetPartRequestRequestTypeDef,
+    UploadReadSetPartResponseTypeDef,
+    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
     ListReadSetActivationJobsRequestRequestTypeDef,
+    ListReadSetActivationJobsResponseTypeDef,
+    GetReadSetActivationJobResponseTypeDef,
+    ListAnnotationImportJobsResponseTypeDef,
+    CreateVariantStoreResponseTypeDef,
+    UpdateVariantStoreResponseTypeDef,
     AnnotationStoreItemTypeDef,
     CreateReferenceStoreRequestRequestTypeDef,
+    CreateReferenceStoreResponseTypeDef,
     CreateSequenceStoreRequestRequestTypeDef,
+    CreateSequenceStoreResponseTypeDef,
     CreateVariantStoreRequestRequestTypeDef,
+    GetReferenceStoreResponseTypeDef,
+    GetSequenceStoreResponseTypeDef,
+    GetVariantStoreResponseTypeDef,
     ReferenceStoreDetailTypeDef,
     SequenceStoreDetailTypeDef,
     VariantStoreItemTypeDef,
     BatchDeleteReadSetResponseTypeDef,
-    CreateReferenceStoreResponseTypeDef,
-    CreateRunGroupResponseTypeDef,
-    CreateSequenceStoreResponseTypeDef,
-    CreateVariantStoreResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteAnnotationStoreResponseTypeDef,
-    DeleteVariantStoreResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetReadSetActivationJobResponseTypeDef,
-    GetReadSetResponseTypeDef,
-    GetReferenceResponseTypeDef,
-    GetReferenceStoreResponseTypeDef,
-    GetRunGroupResponseTypeDef,
-    GetRunResponseTypeDef,
-    GetRunTaskResponseTypeDef,
-    GetSequenceStoreResponseTypeDef,
-    GetVariantStoreResponseTypeDef,
-    ListAnnotationImportJobsResponseTypeDef,
-    ListReadSetActivationJobsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartAnnotationImportResponseTypeDef,
-    StartReadSetActivationJobResponseTypeDef,
-    StartReadSetExportJobResponseTypeDef,
-    StartReadSetImportJobResponseTypeDef,
-    StartReferenceImportJobResponseTypeDef,
-    StartRunResponseTypeDef,
-    StartVariantImportResponseTypeDef,
-    UpdateVariantStoreResponseTypeDef,
+    CompleteMultipartReadSetUploadRequestRequestTypeDef,
     CreateWorkflowRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetReadSetExportJobResponseTypeDef,
+    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
     ListReadSetExportJobsRequestRequestTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     StartReadSetExportJobRequestRequestTypeDef,
     ReadSetFilesTypeDef,
     ReferenceFilesTypeDef,
     GetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef,
     GetAnnotationStoreRequestAnnotationStoreCreatedWaitTypeDef,
@@ -647,32 +646,30 @@
     GetVariantImportRequestVariantImportJobCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreDeletedWaitTypeDef,
     GetWorkflowRequestWorkflowActiveWaitTypeDef,
     ReadSetListItemTypeDef,
     GetReferenceImportJobResponseTypeDef,
     GetVariantImportResponseTypeDef,
+    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
     ListReadSetImportJobsRequestRequestTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ImportReadSetSourceItemTypeDef,
     StartReadSetImportJobSourceItemTypeDef,
+    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
     ListReferenceImportJobsRequestRequestTypeDef,
     ListReferenceImportJobsResponseTypeDef,
-    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef,
-    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
-    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
-    ListRunTasksRequestListRunTasksPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
+    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef,
     ListAnnotationStoresRequestRequestTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
+    ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
+    ListReadSetUploadPartsRequestRequestTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReadSetsRequestListReadSetsPaginateTypeDef,
     ListReadSetsRequestRequestTypeDef,
     ListReferenceStoresRequestListReferenceStoresPaginateTypeDef,
     ListReferenceStoresRequestRequestTypeDef,
     ListReferencesRequestListReferencesPaginateTypeDef,
     ListReferencesRequestRequestTypeDef,
     ListReferencesResponseTypeDef,
@@ -707,54 +704,54 @@
     GetAnnotationStoreResponseTypeDef,
     UpdateAnnotationStoreResponseTypeDef,
     GetAnnotationImportResponseTypeDef,
     StartAnnotationImportRequestRequestTypeDef,
 )
 
 
-def get_structure() -> ActivateReadSetFilterTypeDef:
+def get_structure() -> AbortMultipartReadSetUploadRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-omics-2.5.0.post1/README.md` & `types-aiobotocore-omics-2.5.1/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-omics
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Omics 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore omics type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-omics"></a>
 
 # types-aiobotocore-omics
 
 [![PyPI - types-aiobotocore-omics](https://img.shields.io/pypi/v/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-omics?color=blue)](https://pypistats.org/packages/types-aiobotocore-omics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Omics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
+[aiobotocore.Omics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
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
 [types-aiobotocore-omics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,17 +274,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_omics import OmicsClient
 from types_aiobotocore_omics.paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReadSetsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferenceStoresPaginator,
     ListReferencesPaginator,
     ListRunGroupsPaginator,
     ListRunTasksPaginator,
     ListRunsPaginator,
@@ -269,23 +304,29 @@
     # Types should be correctly discovered by mypy and IDEs
     list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator(
         "list_annotation_import_jobs"
     )
     list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator(
         "list_annotation_stores"
     )
+    list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = (
+        client.get_paginator("list_multipart_read_set_uploads")
+    )
     list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = (
         client.get_paginator("list_read_set_activation_jobs")
     )
     list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator(
         "list_read_set_export_jobs"
     )
     list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator(
         "list_read_set_import_jobs"
     )
+    list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator(
+        "list_read_set_upload_parts"
+    )
     list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
     list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator(
         "list_reference_import_jobs"
     )
     list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator(
         "list_reference_stores"
     )
@@ -382,27 +423,30 @@
 ### Literals
 
 `types_aiobotocore_omics.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_omics.literals import (
+    AcceleratorsType,
     AnnotationImportJobCreatedWaiterName,
     AnnotationStoreCreatedWaiterName,
     AnnotationStoreDeletedWaiterName,
     AnnotationTypeType,
     EncryptionTypeType,
     FileTypeType,
     FormatToHeaderKeyType,
     JobStatusType,
     ListAnnotationImportJobsPaginatorName,
     ListAnnotationStoresPaginatorName,
+    ListMultipartReadSetUploadsPaginatorName,
     ListReadSetActivationJobsPaginatorName,
     ListReadSetExportJobsPaginatorName,
     ListReadSetImportJobsPaginatorName,
+    ListReadSetUploadPartsPaginatorName,
     ListReadSetsPaginatorName,
     ListReferenceImportJobsPaginatorName,
     ListReferenceStoresPaginatorName,
     ListReferencesPaginatorName,
     ListRunGroupsPaginatorName,
     ListRunTasksPaginatorName,
     ListRunsPaginatorName,
@@ -416,14 +460,15 @@
     ReadSetExportJobCompletedWaiterName,
     ReadSetExportJobItemStatusType,
     ReadSetExportJobStatusType,
     ReadSetFileType,
     ReadSetImportJobCompletedWaiterName,
     ReadSetImportJobItemStatusType,
     ReadSetImportJobStatusType,
+    ReadSetPartSourceType,
     ReadSetStatusType,
     ReferenceFileType,
     ReferenceImportJobCompletedWaiterName,
     ReferenceImportJobItemStatusType,
     ReferenceImportJobStatusType,
     ReferenceStatusType,
     RunCompletedWaiterName,
@@ -446,54 +491,64 @@
     WorkflowStatusType,
     WorkflowTypeType,
     OmicsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
-def check_value(value: AnnotationImportJobCreatedWaiterName) -> bool:
+def check_value(value: AcceleratorsType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_omics.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_omics.type_defs import (
+    AbortMultipartReadSetUploadRequestRequestTypeDef,
     ActivateReadSetFilterTypeDef,
     ActivateReadSetJobItemTypeDef,
     ActivateReadSetSourceItemTypeDef,
     AnnotationImportItemDetailTypeDef,
     AnnotationImportItemSourceTypeDef,
     AnnotationImportJobItemTypeDef,
     ReferenceItemTypeDef,
     SseConfigTypeDef,
     BatchDeleteReadSetRequestRequestTypeDef,
     ReadSetBatchErrorTypeDef,
-    ResponseMetadataTypeDef,
     CancelAnnotationImportRequestRequestTypeDef,
     CancelRunRequestRequestTypeDef,
     CancelVariantImportRequestRequestTypeDef,
+    CompleteReadSetUploadPartListItemTypeDef,
+    CompleteMultipartReadSetUploadResponseTypeDef,
+    CreateMultipartReadSetUploadRequestRequestTypeDef,
+    CreateMultipartReadSetUploadResponseTypeDef,
     CreateRunGroupRequestRequestTypeDef,
+    CreateRunGroupResponseTypeDef,
     WorkflowParameterTypeDef,
+    CreateWorkflowResponseTypeDef,
     DeleteAnnotationStoreRequestRequestTypeDef,
+    DeleteAnnotationStoreResponseTypeDef,
     DeleteReferenceRequestRequestTypeDef,
     DeleteReferenceStoreRequestRequestTypeDef,
     DeleteRunGroupRequestRequestTypeDef,
     DeleteRunRequestRequestTypeDef,
     DeleteSequenceStoreRequestRequestTypeDef,
     DeleteVariantStoreRequestRequestTypeDef,
+    DeleteVariantStoreResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportReadSetDetailTypeDef,
     ExportReadSetFilterTypeDef,
     ExportReadSetJobDetailTypeDef,
     ExportReadSetTypeDef,
     FileInformationTypeDef,
     VcfOptionsTypeDef,
     WaiterConfigTypeDef,
@@ -501,104 +556,114 @@
     GetAnnotationStoreRequestRequestTypeDef,
     GetReadSetActivationJobRequestRequestTypeDef,
     GetReadSetExportJobRequestRequestTypeDef,
     GetReadSetImportJobRequestRequestTypeDef,
     GetReadSetMetadataRequestRequestTypeDef,
     SequenceInformationTypeDef,
     GetReadSetRequestRequestTypeDef,
+    GetReadSetResponseTypeDef,
     GetReferenceImportJobRequestRequestTypeDef,
     ImportReferenceSourceItemTypeDef,
     GetReferenceMetadataRequestRequestTypeDef,
     GetReferenceRequestRequestTypeDef,
+    GetReferenceResponseTypeDef,
     GetReferenceStoreRequestRequestTypeDef,
     GetRunGroupRequestRequestTypeDef,
+    GetRunGroupResponseTypeDef,
     GetRunRequestRequestTypeDef,
+    GetRunResponseTypeDef,
     GetRunTaskRequestRequestTypeDef,
+    GetRunTaskResponseTypeDef,
     GetSequenceStoreRequestRequestTypeDef,
     GetVariantImportRequestRequestTypeDef,
     VariantImportItemDetailTypeDef,
     GetVariantStoreRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReadSetJobItemTypeDef,
     SourceFilesTypeDef,
     ImportReferenceFilterTypeDef,
     ImportReferenceJobItemTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListAnnotationStoresFilterTypeDef,
+    ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+    ListMultipartReadSetUploadsRequestRequestTypeDef,
+    MultipartReadSetUploadListItemTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
+    ReadSetUploadPartListItemTypeDef,
     ReadSetFilterTypeDef,
     ReferenceStoreFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceListItemTypeDef,
+    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
     ListRunGroupsRequestRequestTypeDef,
     RunGroupListItemTypeDef,
+    ListRunTasksRequestListRunTasksPaginateTypeDef,
     ListRunTasksRequestRequestTypeDef,
     TaskListItemTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
     RunListItemTypeDef,
     SequenceStoreFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     VariantImportJobItemTypeDef,
     ListVariantStoresFilterTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     WorkflowListItemTypeDef,
+    PaginatorConfigTypeDef,
     ReadOptionsTypeDef,
+    ResponseMetadataTypeDef,
+    StartAnnotationImportResponseTypeDef,
     StartReadSetActivationJobSourceItemTypeDef,
+    StartReadSetActivationJobResponseTypeDef,
+    StartReadSetExportJobResponseTypeDef,
+    StartReadSetImportJobResponseTypeDef,
     StartReferenceImportJobSourceItemTypeDef,
+    StartReferenceImportJobResponseTypeDef,
     StartRunRequestRequestTypeDef,
+    StartRunResponseTypeDef,
     VariantImportItemSourceTypeDef,
+    StartVariantImportResponseTypeDef,
     TsvStoreOptionsTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAnnotationStoreRequestRequestTypeDef,
     UpdateRunGroupRequestRequestTypeDef,
     UpdateVariantStoreRequestRequestTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UploadReadSetPartRequestRequestTypeDef,
+    UploadReadSetPartResponseTypeDef,
+    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
     ListReadSetActivationJobsRequestRequestTypeDef,
+    ListReadSetActivationJobsResponseTypeDef,
+    GetReadSetActivationJobResponseTypeDef,
+    ListAnnotationImportJobsResponseTypeDef,
+    CreateVariantStoreResponseTypeDef,
+    UpdateVariantStoreResponseTypeDef,
     AnnotationStoreItemTypeDef,
     CreateReferenceStoreRequestRequestTypeDef,
+    CreateReferenceStoreResponseTypeDef,
     CreateSequenceStoreRequestRequestTypeDef,
+    CreateSequenceStoreResponseTypeDef,
     CreateVariantStoreRequestRequestTypeDef,
+    GetReferenceStoreResponseTypeDef,
+    GetSequenceStoreResponseTypeDef,
+    GetVariantStoreResponseTypeDef,
     ReferenceStoreDetailTypeDef,
     SequenceStoreDetailTypeDef,
     VariantStoreItemTypeDef,
     BatchDeleteReadSetResponseTypeDef,
-    CreateReferenceStoreResponseTypeDef,
-    CreateRunGroupResponseTypeDef,
-    CreateSequenceStoreResponseTypeDef,
-    CreateVariantStoreResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteAnnotationStoreResponseTypeDef,
-    DeleteVariantStoreResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetReadSetActivationJobResponseTypeDef,
-    GetReadSetResponseTypeDef,
-    GetReferenceResponseTypeDef,
-    GetReferenceStoreResponseTypeDef,
-    GetRunGroupResponseTypeDef,
-    GetRunResponseTypeDef,
-    GetRunTaskResponseTypeDef,
-    GetSequenceStoreResponseTypeDef,
-    GetVariantStoreResponseTypeDef,
-    ListAnnotationImportJobsResponseTypeDef,
-    ListReadSetActivationJobsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartAnnotationImportResponseTypeDef,
-    StartReadSetActivationJobResponseTypeDef,
-    StartReadSetExportJobResponseTypeDef,
-    StartReadSetImportJobResponseTypeDef,
-    StartReferenceImportJobResponseTypeDef,
-    StartRunResponseTypeDef,
-    StartVariantImportResponseTypeDef,
-    UpdateVariantStoreResponseTypeDef,
+    CompleteMultipartReadSetUploadRequestRequestTypeDef,
     CreateWorkflowRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetReadSetExportJobResponseTypeDef,
+    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
     ListReadSetExportJobsRequestRequestTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     StartReadSetExportJobRequestRequestTypeDef,
     ReadSetFilesTypeDef,
     ReferenceFilesTypeDef,
     GetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef,
     GetAnnotationStoreRequestAnnotationStoreCreatedWaitTypeDef,
@@ -614,32 +679,30 @@
     GetVariantImportRequestVariantImportJobCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreDeletedWaitTypeDef,
     GetWorkflowRequestWorkflowActiveWaitTypeDef,
     ReadSetListItemTypeDef,
     GetReferenceImportJobResponseTypeDef,
     GetVariantImportResponseTypeDef,
+    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
     ListReadSetImportJobsRequestRequestTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ImportReadSetSourceItemTypeDef,
     StartReadSetImportJobSourceItemTypeDef,
+    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
     ListReferenceImportJobsRequestRequestTypeDef,
     ListReferenceImportJobsResponseTypeDef,
-    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef,
-    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
-    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
-    ListRunTasksRequestListRunTasksPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
+    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef,
     ListAnnotationStoresRequestRequestTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
+    ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
+    ListReadSetUploadPartsRequestRequestTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReadSetsRequestListReadSetsPaginateTypeDef,
     ListReadSetsRequestRequestTypeDef,
     ListReferenceStoresRequestListReferenceStoresPaginateTypeDef,
     ListReferenceStoresRequestRequestTypeDef,
     ListReferencesRequestListReferencesPaginateTypeDef,
     ListReferencesRequestRequestTypeDef,
     ListReferencesResponseTypeDef,
@@ -674,54 +737,54 @@
     GetAnnotationStoreResponseTypeDef,
     UpdateAnnotationStoreResponseTypeDef,
     GetAnnotationImportResponseTypeDef,
     StartAnnotationImportRequestRequestTypeDef,
 )
 
 
-def get_structure() -> ActivateReadSetFilterTypeDef:
+def get_structure() -> AbortMultipartReadSetUploadRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-omics-2.5.0.post1/setup.py` & `types-aiobotocore-omics-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-omics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-omics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_omics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Omics 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Omics 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/"
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

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__init__.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -8,17 +8,19 @@
     from types_aiobotocore_omics import (
         AnnotationImportJobCreatedWaiter,
         AnnotationStoreCreatedWaiter,
         AnnotationStoreDeletedWaiter,
         Client,
         ListAnnotationImportJobsPaginator,
         ListAnnotationStoresPaginator,
+        ListMultipartReadSetUploadsPaginator,
         ListReadSetActivationJobsPaginator,
         ListReadSetExportJobsPaginator,
         ListReadSetImportJobsPaginator,
+        ListReadSetUploadPartsPaginator,
         ListReadSetsPaginator,
         ListReferenceImportJobsPaginator,
         ListReferenceStoresPaginator,
         ListReferencesPaginator,
         ListRunGroupsPaginator,
         ListRunTasksPaginator,
         ListRunsPaginator,
@@ -61,17 +63,19 @@
     variant_import_job_created_waiter: VariantImportJobCreatedWaiter = client.get_waiter("variant_import_job_created")
     variant_store_created_waiter: VariantStoreCreatedWaiter = client.get_waiter("variant_store_created")
     variant_store_deleted_waiter: VariantStoreDeletedWaiter = client.get_waiter("variant_store_deleted")
     workflow_active_waiter: WorkflowActiveWaiter = client.get_waiter("workflow_active")
 
     list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator("list_annotation_import_jobs")
     list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator("list_annotation_stores")
+    list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = client.get_paginator("list_multipart_read_set_uploads")
     list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = client.get_paginator("list_read_set_activation_jobs")
     list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator("list_read_set_export_jobs")
     list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator("list_read_set_import_jobs")
+    list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator("list_read_set_upload_parts")
     list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
     list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator("list_reference_import_jobs")
     list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator("list_reference_stores")
     list_references_paginator: ListReferencesPaginator = client.get_paginator("list_references")
     list_run_groups_paginator: ListRunGroupsPaginator = client.get_paginator("list_run_groups")
     list_run_tasks_paginator: ListRunTasksPaginator = client.get_paginator("list_run_tasks")
     list_runs_paginator: ListRunsPaginator = client.get_paginator("list_runs")
@@ -81,18 +85,20 @@
     list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
 from .client import OmicsClient
 from .paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
     ListReadSetsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferencesPaginator,
     ListReferenceStoresPaginator,
     ListRunGroupsPaginator,
     ListRunsPaginator,
     ListRunTasksPaginator,
     ListSequenceStoresPaginator,
@@ -124,17 +130,19 @@
 __all__ = (
     "AnnotationImportJobCreatedWaiter",
     "AnnotationStoreCreatedWaiter",
     "AnnotationStoreDeletedWaiter",
     "Client",
     "ListAnnotationImportJobsPaginator",
     "ListAnnotationStoresPaginator",
+    "ListMultipartReadSetUploadsPaginator",
     "ListReadSetActivationJobsPaginator",
     "ListReadSetExportJobsPaginator",
     "ListReadSetImportJobsPaginator",
+    "ListReadSetUploadPartsPaginator",
     "ListReadSetsPaginator",
     "ListReferenceImportJobsPaginator",
     "ListReferenceStoresPaginator",
     "ListReferencesPaginator",
     "ListRunGroupsPaginator",
     "ListRunTasksPaginator",
     "ListRunsPaginator",
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__init__.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__init__.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -8,17 +8,19 @@
     from types_aiobotocore_omics import (
         AnnotationImportJobCreatedWaiter,
         AnnotationStoreCreatedWaiter,
         AnnotationStoreDeletedWaiter,
         Client,
         ListAnnotationImportJobsPaginator,
         ListAnnotationStoresPaginator,
+        ListMultipartReadSetUploadsPaginator,
         ListReadSetActivationJobsPaginator,
         ListReadSetExportJobsPaginator,
         ListReadSetImportJobsPaginator,
+        ListReadSetUploadPartsPaginator,
         ListReadSetsPaginator,
         ListReferenceImportJobsPaginator,
         ListReferenceStoresPaginator,
         ListReferencesPaginator,
         ListRunGroupsPaginator,
         ListRunTasksPaginator,
         ListRunsPaginator,
@@ -61,17 +63,19 @@
     variant_import_job_created_waiter: VariantImportJobCreatedWaiter = client.get_waiter("variant_import_job_created")
     variant_store_created_waiter: VariantStoreCreatedWaiter = client.get_waiter("variant_store_created")
     variant_store_deleted_waiter: VariantStoreDeletedWaiter = client.get_waiter("variant_store_deleted")
     workflow_active_waiter: WorkflowActiveWaiter = client.get_waiter("workflow_active")
 
     list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator("list_annotation_import_jobs")
     list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator("list_annotation_stores")
+    list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = client.get_paginator("list_multipart_read_set_uploads")
     list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = client.get_paginator("list_read_set_activation_jobs")
     list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator("list_read_set_export_jobs")
     list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator("list_read_set_import_jobs")
+    list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator("list_read_set_upload_parts")
     list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
     list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator("list_reference_import_jobs")
     list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator("list_reference_stores")
     list_references_paginator: ListReferencesPaginator = client.get_paginator("list_references")
     list_run_groups_paginator: ListRunGroupsPaginator = client.get_paginator("list_run_groups")
     list_run_tasks_paginator: ListRunTasksPaginator = client.get_paginator("list_run_tasks")
     list_runs_paginator: ListRunsPaginator = client.get_paginator("list_runs")
@@ -81,18 +85,20 @@
     list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
 from .client import OmicsClient
 from .paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
     ListReadSetsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferencesPaginator,
     ListReferenceStoresPaginator,
     ListRunGroupsPaginator,
     ListRunsPaginator,
     ListRunTasksPaginator,
     ListSequenceStoresPaginator,
@@ -123,17 +129,19 @@
 __all__ = (
     "AnnotationImportJobCreatedWaiter",
     "AnnotationStoreCreatedWaiter",
     "AnnotationStoreDeletedWaiter",
     "Client",
     "ListAnnotationImportJobsPaginator",
     "ListAnnotationStoresPaginator",
+    "ListMultipartReadSetUploadsPaginator",
     "ListReadSetActivationJobsPaginator",
     "ListReadSetExportJobsPaginator",
     "ListReadSetImportJobsPaginator",
+    "ListReadSetUploadPartsPaginator",
     "ListReadSetsPaginator",
     "ListReferenceImportJobsPaginator",
     "ListReferenceStoresPaginator",
     "ListReferencesPaginator",
     "ListRunGroupsPaginator",
     "ListRunTasksPaginator",
     "ListRunsPaginator",
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/__main__.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Omics 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Omics 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics\nOther"
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

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/client.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,28 +18,34 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    FileTypeType,
     ReadSetFileType,
+    ReadSetPartSourceType,
     ReferenceFileType,
     RunLogLevelType,
+    RunStatusType,
     StoreFormatType,
     TaskStatusType,
     WorkflowEngineType,
+    WorkflowTypeType,
 )
 from .paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
     ListReadSetsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferencesPaginator,
     ListReferenceStoresPaginator,
     ListRunGroupsPaginator,
     ListRunsPaginator,
     ListRunTasksPaginator,
     ListSequenceStoresPaginator,
@@ -47,15 +53,18 @@
     ListVariantStoresPaginator,
     ListWorkflowsPaginator,
 )
 from .type_defs import (
     ActivateReadSetFilterTypeDef,
     AnnotationImportItemSourceTypeDef,
     BatchDeleteReadSetResponseTypeDef,
+    CompleteMultipartReadSetUploadResponseTypeDef,
+    CompleteReadSetUploadPartListItemTypeDef,
     CreateAnnotationStoreResponseTypeDef,
+    CreateMultipartReadSetUploadResponseTypeDef,
     CreateReferenceStoreResponseTypeDef,
     CreateRunGroupResponseTypeDef,
     CreateSequenceStoreResponseTypeDef,
     CreateVariantStoreResponseTypeDef,
     CreateWorkflowResponseTypeDef,
     DeleteAnnotationStoreResponseTypeDef,
     DeleteVariantStoreResponseTypeDef,
@@ -83,32 +92,35 @@
     GetWorkflowResponseTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReferenceFilterTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
     ListAnnotationImportJobsResponseTypeDef,
     ListAnnotationStoresFilterTypeDef,
     ListAnnotationStoresResponseTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
     ListReadSetActivationJobsResponseTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ListReadSetsResponseTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReferenceImportJobsResponseTypeDef,
     ListReferencesResponseTypeDef,
     ListReferenceStoresResponseTypeDef,
     ListRunGroupsResponseTypeDef,
     ListRunsResponseTypeDef,
     ListRunTasksResponseTypeDef,
     ListSequenceStoresResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     ListVariantImportJobsResponseTypeDef,
     ListVariantStoresFilterTypeDef,
     ListVariantStoresResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     ReadSetFilterTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceItemTypeDef,
     ReferenceStoreFilterTypeDef,
     SequenceStoreFilterTypeDef,
     SseConfigTypeDef,
     StartAnnotationImportResponseTypeDef,
     StartReadSetActivationJobResponseTypeDef,
@@ -119,14 +131,15 @@
     StartReferenceImportJobResponseTypeDef,
     StartReferenceImportJobSourceItemTypeDef,
     StartRunResponseTypeDef,
     StartVariantImportResponseTypeDef,
     StoreOptionsTypeDef,
     UpdateAnnotationStoreResponseTypeDef,
     UpdateVariantStoreResponseTypeDef,
+    UploadReadSetPartResponseTypeDef,
     VariantImportItemSourceTypeDef,
     WorkflowParameterTypeDef,
 )
 from .waiter import (
     AnnotationImportJobCreatedWaiter,
     AnnotationStoreCreatedWaiter,
     AnnotationStoreDeletedWaiter,
@@ -162,14 +175,15 @@
 
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    NotSupportedOperationException: Type[BotocoreClientError]
     RangeNotSatisfiableException: Type[BotocoreClientError]
     RequestTimeoutException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
@@ -187,14 +201,24 @@
         """
         OmicsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#exceptions)
         """
 
+    async def abort_multipart_read_set_upload(
+        self, *, sequenceStoreId: str, uploadId: str
+    ) -> Dict[str, Any]:
+        """
+        Stops a multipart upload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.abort_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#abort_multipart_read_set_upload)
+        """
+
     async def batch_delete_read_set(
         self, *, ids: Sequence[str], sequenceStoreId: str
     ) -> BatchDeleteReadSetResponseTypeDef:
         """
         Deletes one or more read sets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.batch_delete_read_set)
@@ -237,110 +261,148 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#close)
         """
 
+    async def complete_multipart_read_set_upload(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        parts: Sequence[CompleteReadSetUploadPartListItemTypeDef]
+    ) -> CompleteMultipartReadSetUploadResponseTypeDef:
+        """
+        Concludes a multipart upload once you have uploaded all the components.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.complete_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#complete_multipart_read_set_upload)
+        """
+
     async def create_annotation_store(
         self,
         *,
         storeFormat: StoreFormatType,
-        description: str = ...,
-        name: str = ...,
         reference: ReferenceItemTypeDef = ...,
+        name: str = ...,
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
         sseConfig: SseConfigTypeDef = ...,
-        storeOptions: StoreOptionsTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        storeOptions: StoreOptionsTypeDef = ...
     ) -> CreateAnnotationStoreResponseTypeDef:
         """
         Creates an annotation store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_annotation_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_annotation_store)
         """
 
-    async def create_reference_store(
+    async def create_multipart_read_set_upload(
         self,
         *,
+        sequenceStoreId: str,
+        sourceFileType: FileTypeType,
+        subjectId: str,
+        sampleId: str,
+        referenceArn: str,
         name: str,
         clientToken: str = ...,
+        generatedFrom: str = ...,
         description: str = ...,
-        sseConfig: SseConfigTypeDef = ...,
         tags: Mapping[str, str] = ...
+    ) -> CreateMultipartReadSetUploadResponseTypeDef:
+        """
+        Begins a multipart read set upload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_multipart_read_set_upload)
+        """
+
+    async def create_reference_store(
+        self,
+        *,
+        name: str,
+        description: str = ...,
+        sseConfig: SseConfigTypeDef = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
     ) -> CreateReferenceStoreResponseTypeDef:
         """
         Creates a reference store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_reference_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_reference_store)
         """
 
     async def create_run_group(
         self,
         *,
         requestId: str,
+        name: str = ...,
         maxCpus: int = ...,
-        maxDuration: int = ...,
         maxRuns: int = ...,
-        name: str = ...,
-        tags: Mapping[str, str] = ...
+        maxDuration: int = ...,
+        tags: Mapping[str, str] = ...,
+        maxGpus: int = ...
     ) -> CreateRunGroupResponseTypeDef:
         """
         Creates a run group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_run_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_run_group)
         """
 
     async def create_sequence_store(
         self,
         *,
         name: str,
-        clientToken: str = ...,
         description: str = ...,
         sseConfig: SseConfigTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...,
+        fallbackLocation: str = ...
     ) -> CreateSequenceStoreResponseTypeDef:
         """
         Creates a sequence store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_sequence_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_sequence_store)
         """
 
     async def create_variant_store(
         self,
         *,
         reference: ReferenceItemTypeDef,
-        description: str = ...,
         name: str = ...,
-        sseConfig: SseConfigTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
+        sseConfig: SseConfigTypeDef = ...
     ) -> CreateVariantStoreResponseTypeDef:
         """
         Creates a variant store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_variant_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_variant_store)
         """
 
     async def create_workflow(
         self,
         *,
         requestId: str,
-        definitionUri: str = ...,
-        definitionZip: Union[str, bytes, IO[Any], StreamingBody] = ...,
+        name: str = ...,
         description: str = ...,
         engine: WorkflowEngineType = ...,
+        definitionZip: Union[str, bytes, IO[Any], StreamingBody] = ...,
+        definitionUri: str = ...,
         main: str = ...,
-        name: str = ...,
         parameterTemplate: Mapping[str, WorkflowParameterTypeDef] = ...,
         storageCapacity: int = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        accelerators: Literal["GPU"] = ...
     ) -> CreateWorkflowResponseTypeDef:
         """
         Creates a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_workflow)
         """
@@ -440,15 +502,15 @@
         Gets information about an annotation store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_annotation_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_annotation_store)
         """
 
     async def get_read_set(
-        self, *, id: str, partNumber: int, sequenceStoreId: str, file: ReadSetFileType = ...
+        self, *, id: str, sequenceStoreId: str, partNumber: int, file: ReadSetFileType = ...
     ) -> GetReadSetResponseTypeDef:
         """
         Gets a file from a read set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set)
         """
@@ -460,15 +522,15 @@
         Gets information about a read set activation job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set_activation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_activation_job)
         """
 
     async def get_read_set_export_job(
-        self, *, id: str, sequenceStoreId: str
+        self, *, sequenceStoreId: str, id: str
     ) -> GetReadSetExportJobResponseTypeDef:
         """
         Gets information about a read set export job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set_export_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_export_job)
         """
@@ -493,18 +555,18 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_metadata)
         """
 
     async def get_reference(
         self,
         *,
         id: str,
-        partNumber: int,
         referenceStoreId: str,
-        file: ReferenceFileType = ...,
-        range: str = ...
+        partNumber: int,
+        range: str = ...,
+        file: ReferenceFileType = ...
     ) -> GetReferenceResponseTypeDef:
         """
         Gets a reference file.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_reference)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_reference)
         """
@@ -587,204 +649,233 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_variant_store)
         """
 
     async def get_workflow(
         self,
         *,
         id: str,
-        export: Sequence[Literal["DEFINITION"]] = ...,
-        type: Literal["PRIVATE"] = ...
+        type: WorkflowTypeType = ...,
+        export: Sequence[Literal["DEFINITION"]] = ...
     ) -> GetWorkflowResponseTypeDef:
         """
         Gets information about a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_workflow)
         """
 
     async def list_annotation_import_jobs(
         self,
         *,
-        filter: ListAnnotationImportJobsFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListAnnotationImportJobsFilterTypeDef = ...
     ) -> ListAnnotationImportJobsResponseTypeDef:
         """
         Retrieves a list of annotation import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_annotation_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_annotation_import_jobs)
         """
 
     async def list_annotation_stores(
         self,
         *,
-        filter: ListAnnotationStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ListAnnotationStoresFilterTypeDef = ...
     ) -> ListAnnotationStoresResponseTypeDef:
         """
         Retrieves a list of annotation stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_annotation_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_annotation_stores)
         """
 
+    async def list_multipart_read_set_uploads(
+        self, *, sequenceStoreId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListMultipartReadSetUploadsResponseTypeDef:
+        """
+        Lists all multipart read set uploads and their statuses.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_multipart_read_set_uploads)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_multipart_read_set_uploads)
+        """
+
     async def list_read_set_activation_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ActivateReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ActivateReadSetFilterTypeDef = ...
     ) -> ListReadSetActivationJobsResponseTypeDef:
         """
         Retrieves a list of read set activation jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_activation_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_activation_jobs)
         """
 
     async def list_read_set_export_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ExportReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ExportReadSetFilterTypeDef = ...
     ) -> ListReadSetExportJobsResponseTypeDef:
         """
         Retrieves a list of read set export jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_export_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_export_jobs)
         """
 
     async def list_read_set_import_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ImportReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ImportReadSetFilterTypeDef = ...
     ) -> ListReadSetImportJobsResponseTypeDef:
         """
         Retrieves a list of read set import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_import_jobs)
         """
 
+    async def list_read_set_upload_parts(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        maxResults: int = ...,
+        nextToken: str = ...,
+        filter: ReadSetUploadPartListFilterTypeDef = ...
+    ) -> ListReadSetUploadPartsResponseTypeDef:
+        """
+        This operation will list all parts in a requested multipart upload for a
+        sequence store.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_upload_parts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_upload_parts)
+        """
+
     async def list_read_sets(
         self,
         *,
         sequenceStoreId: str,
-        filter: ReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReadSetFilterTypeDef = ...
     ) -> ListReadSetsResponseTypeDef:
         """
         Retrieves a list of read sets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_sets)
         """
 
     async def list_reference_import_jobs(
         self,
         *,
         referenceStoreId: str,
-        filter: ImportReferenceFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ImportReferenceFilterTypeDef = ...
     ) -> ListReferenceImportJobsResponseTypeDef:
         """
         Retrieves a list of reference import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_reference_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_reference_import_jobs)
         """
 
     async def list_reference_stores(
         self,
         *,
-        filter: ReferenceStoreFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReferenceStoreFilterTypeDef = ...
     ) -> ListReferenceStoresResponseTypeDef:
         """
         Retrieves a list of reference stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_reference_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_reference_stores)
         """
 
     async def list_references(
         self,
         *,
         referenceStoreId: str,
-        filter: ReferenceFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReferenceFilterTypeDef = ...
     ) -> ListReferencesResponseTypeDef:
         """
         Retrieves a list of references.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_references)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_references)
         """
 
     async def list_run_groups(
-        self, *, maxResults: int = ..., name: str = ..., startingToken: str = ...
+        self, *, name: str = ..., startingToken: str = ..., maxResults: int = ...
     ) -> ListRunGroupsResponseTypeDef:
         """
         Retrieves a list of run groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_run_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_run_groups)
         """
 
     async def list_run_tasks(
         self,
         *,
         id: str,
-        maxResults: int = ...,
+        status: TaskStatusType = ...,
         startingToken: str = ...,
-        status: TaskStatusType = ...
+        maxResults: int = ...
     ) -> ListRunTasksResponseTypeDef:
         """
         Retrieves a list of tasks for a run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_run_tasks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_run_tasks)
         """
 
     async def list_runs(
         self,
         *,
-        maxResults: int = ...,
         name: str = ...,
         runGroupId: str = ...,
-        startingToken: str = ...
+        startingToken: str = ...,
+        maxResults: int = ...,
+        status: RunStatusType = ...
     ) -> ListRunsResponseTypeDef:
         """
         Retrieves a list of runs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_runs)
         """
 
     async def list_sequence_stores(
         self,
         *,
-        filter: SequenceStoreFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: SequenceStoreFilterTypeDef = ...
     ) -> ListSequenceStoresResponseTypeDef:
         """
         Retrieves a list of sequence stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_sequence_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_sequence_stores)
         """
@@ -798,64 +889,65 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_tags_for_resource)
         """
 
     async def list_variant_import_jobs(
         self,
         *,
-        filter: ListVariantImportJobsFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListVariantImportJobsFilterTypeDef = ...
     ) -> ListVariantImportJobsResponseTypeDef:
         """
         Retrieves a list of variant import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_variant_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_variant_import_jobs)
         """
 
     async def list_variant_stores(
         self,
         *,
-        filter: ListVariantStoresFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListVariantStoresFilterTypeDef = ...
     ) -> ListVariantStoresResponseTypeDef:
         """
         Retrieves a list of variant stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_variant_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_variant_stores)
         """
 
     async def list_workflows(
         self,
         *,
-        maxResults: int = ...,
+        type: WorkflowTypeType = ...,
         name: str = ...,
         startingToken: str = ...,
-        type: Literal["PRIVATE"] = ...
+        maxResults: int = ...
     ) -> ListWorkflowsResponseTypeDef:
         """
         Retrieves a list of workflows.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_workflows)
         """
 
     async def start_annotation_import_job(
         self,
         *,
         destinationName: str,
-        items: Sequence[AnnotationImportItemSourceTypeDef],
         roleArn: str,
+        items: Sequence[AnnotationImportItemSourceTypeDef],
         formatOptions: FormatOptionsTypeDef = ...,
-        runLeftNormalization: bool = ...
+        runLeftNormalization: bool = ...,
+        annotationFields: Mapping[str, str] = ...
     ) -> StartAnnotationImportResponseTypeDef:
         """
         Starts an annotation import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_annotation_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_annotation_import_job)
         """
@@ -864,41 +956,41 @@
         self,
         *,
         sequenceStoreId: str,
         sources: Sequence[StartReadSetActivationJobSourceItemTypeDef],
         clientToken: str = ...
     ) -> StartReadSetActivationJobResponseTypeDef:
         """
-        Starts a read set activation job.
+        Activates an archived read set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_activation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_read_set_activation_job)
         """
 
     async def start_read_set_export_job(
         self,
         *,
+        sequenceStoreId: str,
         destination: str,
         roleArn: str,
-        sequenceStoreId: str,
         sources: Sequence[ExportReadSetTypeDef],
         clientToken: str = ...
     ) -> StartReadSetExportJobResponseTypeDef:
         """
-        Starts a read set export job.
+        Exports a read set to Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_export_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_read_set_export_job)
         """
 
     async def start_read_set_import_job(
         self,
         *,
-        roleArn: str,
         sequenceStoreId: str,
+        roleArn: str,
         sources: Sequence[StartReadSetImportJobSourceItemTypeDef],
         clientToken: str = ...
     ) -> StartReadSetImportJobResponseTypeDef:
         """
         Starts a read set import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_import_job)
@@ -919,42 +1011,43 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_reference_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_reference_import_job)
         """
 
     async def start_run(
         self,
         *,
-        requestId: str,
         roleArn: str,
-        logLevel: RunLogLevelType = ...,
+        requestId: str,
+        workflowId: str = ...,
+        workflowType: WorkflowTypeType = ...,
+        runId: str = ...,
         name: str = ...,
-        outputUri: str = ...,
-        parameters: Mapping[str, Any] = ...,
-        priority: int = ...,
         runGroupId: str = ...,
-        runId: str = ...,
+        priority: int = ...,
+        parameters: Mapping[str, Any] = ...,
         storageCapacity: int = ...,
-        tags: Mapping[str, str] = ...,
-        workflowId: str = ...,
-        workflowType: Literal["PRIVATE"] = ...
+        outputUri: str = ...,
+        logLevel: RunLogLevelType = ...,
+        tags: Mapping[str, str] = ...
     ) -> StartRunResponseTypeDef:
         """
         Starts a run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_run)
         """
 
     async def start_variant_import_job(
         self,
         *,
         destinationName: str,
-        items: Sequence[VariantImportItemSourceTypeDef],
         roleArn: str,
-        runLeftNormalization: bool = ...
+        items: Sequence[VariantImportItemSourceTypeDef],
+        runLeftNormalization: bool = ...,
+        annotationFields: Mapping[str, str] = ...
     ) -> StartVariantImportResponseTypeDef:
         """
         Starts a variant import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_variant_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_variant_import_job)
         """
@@ -985,18 +1078,19 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_annotation_store)
         """
 
     async def update_run_group(
         self,
         *,
         id: str,
+        name: str = ...,
         maxCpus: int = ...,
-        maxDuration: int = ...,
         maxRuns: int = ...,
-        name: str = ...
+        maxDuration: int = ...,
+        maxGpus: int = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a run group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_run_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_run_group)
         """
@@ -1008,23 +1102,39 @@
         Updates a variant store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_variant_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_variant_store)
         """
 
     async def update_workflow(
-        self, *, id: str, description: str = ..., name: str = ...
+        self, *, id: str, name: str = ..., description: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_workflow)
         """
 
+    async def upload_read_set_part(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        partNumber: int,
+        payload: Union[str, bytes, IO[Any], StreamingBody]
+    ) -> UploadReadSetPartResponseTypeDef:
+        """
+        This operation uploads a specific part of a read set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.upload_read_set_part)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#upload_read_set_part)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_annotation_import_jobs"]
     ) -> ListAnnotationImportJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
@@ -1037,14 +1147,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_multipart_read_set_uploads"]
+    ) -> ListMultipartReadSetUploadsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_read_set_activation_jobs"]
     ) -> ListReadSetActivationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
 
@@ -1063,14 +1182,23 @@
     ) -> ListReadSetImportJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_read_set_upload_parts"]
+    ) -> ListReadSetUploadPartsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_read_sets"]) -> ListReadSetsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/client.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/client.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,28 +18,34 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    FileTypeType,
     ReadSetFileType,
+    ReadSetPartSourceType,
     ReferenceFileType,
     RunLogLevelType,
+    RunStatusType,
     StoreFormatType,
     TaskStatusType,
     WorkflowEngineType,
+    WorkflowTypeType,
 )
 from .paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
     ListReadSetsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferencesPaginator,
     ListReferenceStoresPaginator,
     ListRunGroupsPaginator,
     ListRunsPaginator,
     ListRunTasksPaginator,
     ListSequenceStoresPaginator,
@@ -47,15 +53,18 @@
     ListVariantStoresPaginator,
     ListWorkflowsPaginator,
 )
 from .type_defs import (
     ActivateReadSetFilterTypeDef,
     AnnotationImportItemSourceTypeDef,
     BatchDeleteReadSetResponseTypeDef,
+    CompleteMultipartReadSetUploadResponseTypeDef,
+    CompleteReadSetUploadPartListItemTypeDef,
     CreateAnnotationStoreResponseTypeDef,
+    CreateMultipartReadSetUploadResponseTypeDef,
     CreateReferenceStoreResponseTypeDef,
     CreateRunGroupResponseTypeDef,
     CreateSequenceStoreResponseTypeDef,
     CreateVariantStoreResponseTypeDef,
     CreateWorkflowResponseTypeDef,
     DeleteAnnotationStoreResponseTypeDef,
     DeleteVariantStoreResponseTypeDef,
@@ -83,32 +92,35 @@
     GetWorkflowResponseTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReferenceFilterTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
     ListAnnotationImportJobsResponseTypeDef,
     ListAnnotationStoresFilterTypeDef,
     ListAnnotationStoresResponseTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
     ListReadSetActivationJobsResponseTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ListReadSetsResponseTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReferenceImportJobsResponseTypeDef,
     ListReferencesResponseTypeDef,
     ListReferenceStoresResponseTypeDef,
     ListRunGroupsResponseTypeDef,
     ListRunsResponseTypeDef,
     ListRunTasksResponseTypeDef,
     ListSequenceStoresResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     ListVariantImportJobsResponseTypeDef,
     ListVariantStoresFilterTypeDef,
     ListVariantStoresResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     ReadSetFilterTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceItemTypeDef,
     ReferenceStoreFilterTypeDef,
     SequenceStoreFilterTypeDef,
     SseConfigTypeDef,
     StartAnnotationImportResponseTypeDef,
     StartReadSetActivationJobResponseTypeDef,
@@ -119,14 +131,15 @@
     StartReferenceImportJobResponseTypeDef,
     StartReferenceImportJobSourceItemTypeDef,
     StartRunResponseTypeDef,
     StartVariantImportResponseTypeDef,
     StoreOptionsTypeDef,
     UpdateAnnotationStoreResponseTypeDef,
     UpdateVariantStoreResponseTypeDef,
+    UploadReadSetPartResponseTypeDef,
     VariantImportItemSourceTypeDef,
     WorkflowParameterTypeDef,
 )
 from .waiter import (
     AnnotationImportJobCreatedWaiter,
     AnnotationStoreCreatedWaiter,
     AnnotationStoreDeletedWaiter,
@@ -159,14 +172,15 @@
         self.operation_name: str
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    NotSupportedOperationException: Type[BotocoreClientError]
     RangeNotSatisfiableException: Type[BotocoreClientError]
     RequestTimeoutException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
@@ -182,14 +196,23 @@
     def exceptions(self) -> Exceptions:
         """
         OmicsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#exceptions)
         """
+    async def abort_multipart_read_set_upload(
+        self, *, sequenceStoreId: str, uploadId: str
+    ) -> Dict[str, Any]:
+        """
+        Stops a multipart upload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.abort_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#abort_multipart_read_set_upload)
+        """
     async def batch_delete_read_set(
         self, *, ids: Sequence[str], sequenceStoreId: str
     ) -> BatchDeleteReadSetResponseTypeDef:
         """
         Deletes one or more read sets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.batch_delete_read_set)
@@ -226,105 +249,141 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#close)
         """
+    async def complete_multipart_read_set_upload(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        parts: Sequence[CompleteReadSetUploadPartListItemTypeDef]
+    ) -> CompleteMultipartReadSetUploadResponseTypeDef:
+        """
+        Concludes a multipart upload once you have uploaded all the components.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.complete_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#complete_multipart_read_set_upload)
+        """
     async def create_annotation_store(
         self,
         *,
         storeFormat: StoreFormatType,
-        description: str = ...,
-        name: str = ...,
         reference: ReferenceItemTypeDef = ...,
+        name: str = ...,
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
         sseConfig: SseConfigTypeDef = ...,
-        storeOptions: StoreOptionsTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        storeOptions: StoreOptionsTypeDef = ...
     ) -> CreateAnnotationStoreResponseTypeDef:
         """
         Creates an annotation store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_annotation_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_annotation_store)
         """
-    async def create_reference_store(
+    async def create_multipart_read_set_upload(
         self,
         *,
+        sequenceStoreId: str,
+        sourceFileType: FileTypeType,
+        subjectId: str,
+        sampleId: str,
+        referenceArn: str,
         name: str,
         clientToken: str = ...,
+        generatedFrom: str = ...,
         description: str = ...,
-        sseConfig: SseConfigTypeDef = ...,
         tags: Mapping[str, str] = ...
+    ) -> CreateMultipartReadSetUploadResponseTypeDef:
+        """
+        Begins a multipart read set upload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_multipart_read_set_upload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_multipart_read_set_upload)
+        """
+    async def create_reference_store(
+        self,
+        *,
+        name: str,
+        description: str = ...,
+        sseConfig: SseConfigTypeDef = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
     ) -> CreateReferenceStoreResponseTypeDef:
         """
         Creates a reference store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_reference_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_reference_store)
         """
     async def create_run_group(
         self,
         *,
         requestId: str,
+        name: str = ...,
         maxCpus: int = ...,
-        maxDuration: int = ...,
         maxRuns: int = ...,
-        name: str = ...,
-        tags: Mapping[str, str] = ...
+        maxDuration: int = ...,
+        tags: Mapping[str, str] = ...,
+        maxGpus: int = ...
     ) -> CreateRunGroupResponseTypeDef:
         """
         Creates a run group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_run_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_run_group)
         """
     async def create_sequence_store(
         self,
         *,
         name: str,
-        clientToken: str = ...,
         description: str = ...,
         sseConfig: SseConfigTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...,
+        fallbackLocation: str = ...
     ) -> CreateSequenceStoreResponseTypeDef:
         """
         Creates a sequence store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_sequence_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_sequence_store)
         """
     async def create_variant_store(
         self,
         *,
         reference: ReferenceItemTypeDef,
-        description: str = ...,
         name: str = ...,
-        sseConfig: SseConfigTypeDef = ...,
-        tags: Mapping[str, str] = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
+        sseConfig: SseConfigTypeDef = ...
     ) -> CreateVariantStoreResponseTypeDef:
         """
         Creates a variant store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_variant_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_variant_store)
         """
     async def create_workflow(
         self,
         *,
         requestId: str,
-        definitionUri: str = ...,
-        definitionZip: Union[str, bytes, IO[Any], StreamingBody] = ...,
+        name: str = ...,
         description: str = ...,
         engine: WorkflowEngineType = ...,
+        definitionZip: Union[str, bytes, IO[Any], StreamingBody] = ...,
+        definitionUri: str = ...,
         main: str = ...,
-        name: str = ...,
         parameterTemplate: Mapping[str, WorkflowParameterTypeDef] = ...,
         storageCapacity: int = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        accelerators: Literal["GPU"] = ...
     ) -> CreateWorkflowResponseTypeDef:
         """
         Creates a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.create_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#create_workflow)
         """
@@ -412,15 +471,15 @@
         """
         Gets information about an annotation store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_annotation_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_annotation_store)
         """
     async def get_read_set(
-        self, *, id: str, partNumber: int, sequenceStoreId: str, file: ReadSetFileType = ...
+        self, *, id: str, sequenceStoreId: str, partNumber: int, file: ReadSetFileType = ...
     ) -> GetReadSetResponseTypeDef:
         """
         Gets a file from a read set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set)
         """
@@ -430,15 +489,15 @@
         """
         Gets information about a read set activation job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set_activation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_activation_job)
         """
     async def get_read_set_export_job(
-        self, *, id: str, sequenceStoreId: str
+        self, *, sequenceStoreId: str, id: str
     ) -> GetReadSetExportJobResponseTypeDef:
         """
         Gets information about a read set export job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set_export_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_export_job)
         """
@@ -460,18 +519,18 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_read_set_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_read_set_metadata)
         """
     async def get_reference(
         self,
         *,
         id: str,
-        partNumber: int,
         referenceStoreId: str,
-        file: ReferenceFileType = ...,
-        range: str = ...
+        partNumber: int,
+        range: str = ...,
+        file: ReferenceFileType = ...
     ) -> GetReferenceResponseTypeDef:
         """
         Gets a reference file.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_reference)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_reference)
         """
@@ -544,191 +603,218 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_variant_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_variant_store)
         """
     async def get_workflow(
         self,
         *,
         id: str,
-        export: Sequence[Literal["DEFINITION"]] = ...,
-        type: Literal["PRIVATE"] = ...
+        type: WorkflowTypeType = ...,
+        export: Sequence[Literal["DEFINITION"]] = ...
     ) -> GetWorkflowResponseTypeDef:
         """
         Gets information about a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_workflow)
         """
     async def list_annotation_import_jobs(
         self,
         *,
-        filter: ListAnnotationImportJobsFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListAnnotationImportJobsFilterTypeDef = ...
     ) -> ListAnnotationImportJobsResponseTypeDef:
         """
         Retrieves a list of annotation import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_annotation_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_annotation_import_jobs)
         """
     async def list_annotation_stores(
         self,
         *,
-        filter: ListAnnotationStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ListAnnotationStoresFilterTypeDef = ...
     ) -> ListAnnotationStoresResponseTypeDef:
         """
         Retrieves a list of annotation stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_annotation_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_annotation_stores)
         """
+    async def list_multipart_read_set_uploads(
+        self, *, sequenceStoreId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListMultipartReadSetUploadsResponseTypeDef:
+        """
+        Lists all multipart read set uploads and their statuses.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_multipart_read_set_uploads)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_multipart_read_set_uploads)
+        """
     async def list_read_set_activation_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ActivateReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ActivateReadSetFilterTypeDef = ...
     ) -> ListReadSetActivationJobsResponseTypeDef:
         """
         Retrieves a list of read set activation jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_activation_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_activation_jobs)
         """
     async def list_read_set_export_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ExportReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ExportReadSetFilterTypeDef = ...
     ) -> ListReadSetExportJobsResponseTypeDef:
         """
         Retrieves a list of read set export jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_export_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_export_jobs)
         """
     async def list_read_set_import_jobs(
         self,
         *,
         sequenceStoreId: str,
-        filter: ImportReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ImportReadSetFilterTypeDef = ...
     ) -> ListReadSetImportJobsResponseTypeDef:
         """
         Retrieves a list of read set import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_import_jobs)
         """
+    async def list_read_set_upload_parts(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        maxResults: int = ...,
+        nextToken: str = ...,
+        filter: ReadSetUploadPartListFilterTypeDef = ...
+    ) -> ListReadSetUploadPartsResponseTypeDef:
+        """
+        This operation will list all parts in a requested multipart upload for a
+        sequence store.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_set_upload_parts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_set_upload_parts)
+        """
     async def list_read_sets(
         self,
         *,
         sequenceStoreId: str,
-        filter: ReadSetFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReadSetFilterTypeDef = ...
     ) -> ListReadSetsResponseTypeDef:
         """
         Retrieves a list of read sets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_read_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_read_sets)
         """
     async def list_reference_import_jobs(
         self,
         *,
         referenceStoreId: str,
-        filter: ImportReferenceFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ImportReferenceFilterTypeDef = ...
     ) -> ListReferenceImportJobsResponseTypeDef:
         """
         Retrieves a list of reference import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_reference_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_reference_import_jobs)
         """
     async def list_reference_stores(
         self,
         *,
-        filter: ReferenceStoreFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReferenceStoreFilterTypeDef = ...
     ) -> ListReferenceStoresResponseTypeDef:
         """
         Retrieves a list of reference stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_reference_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_reference_stores)
         """
     async def list_references(
         self,
         *,
         referenceStoreId: str,
-        filter: ReferenceFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: ReferenceFilterTypeDef = ...
     ) -> ListReferencesResponseTypeDef:
         """
         Retrieves a list of references.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_references)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_references)
         """
     async def list_run_groups(
-        self, *, maxResults: int = ..., name: str = ..., startingToken: str = ...
+        self, *, name: str = ..., startingToken: str = ..., maxResults: int = ...
     ) -> ListRunGroupsResponseTypeDef:
         """
         Retrieves a list of run groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_run_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_run_groups)
         """
     async def list_run_tasks(
         self,
         *,
         id: str,
-        maxResults: int = ...,
+        status: TaskStatusType = ...,
         startingToken: str = ...,
-        status: TaskStatusType = ...
+        maxResults: int = ...
     ) -> ListRunTasksResponseTypeDef:
         """
         Retrieves a list of tasks for a run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_run_tasks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_run_tasks)
         """
     async def list_runs(
         self,
         *,
-        maxResults: int = ...,
         name: str = ...,
         runGroupId: str = ...,
-        startingToken: str = ...
+        startingToken: str = ...,
+        maxResults: int = ...,
+        status: RunStatusType = ...
     ) -> ListRunsResponseTypeDef:
         """
         Retrieves a list of runs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_runs)
         """
     async def list_sequence_stores(
         self,
         *,
-        filter: SequenceStoreFilterTypeDef = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        filter: SequenceStoreFilterTypeDef = ...
     ) -> ListSequenceStoresResponseTypeDef:
         """
         Retrieves a list of sequence stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_sequence_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_sequence_stores)
         """
@@ -740,61 +826,62 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_tags_for_resource)
         """
     async def list_variant_import_jobs(
         self,
         *,
-        filter: ListVariantImportJobsFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListVariantImportJobsFilterTypeDef = ...
     ) -> ListVariantImportJobsResponseTypeDef:
         """
         Retrieves a list of variant import jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_variant_import_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_variant_import_jobs)
         """
     async def list_variant_stores(
         self,
         *,
-        filter: ListVariantStoresFilterTypeDef = ...,
-        ids: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        ids: Sequence[str] = ...,
+        nextToken: str = ...,
+        filter: ListVariantStoresFilterTypeDef = ...
     ) -> ListVariantStoresResponseTypeDef:
         """
         Retrieves a list of variant stores.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_variant_stores)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_variant_stores)
         """
     async def list_workflows(
         self,
         *,
-        maxResults: int = ...,
+        type: WorkflowTypeType = ...,
         name: str = ...,
         startingToken: str = ...,
-        type: Literal["PRIVATE"] = ...
+        maxResults: int = ...
     ) -> ListWorkflowsResponseTypeDef:
         """
         Retrieves a list of workflows.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#list_workflows)
         """
     async def start_annotation_import_job(
         self,
         *,
         destinationName: str,
-        items: Sequence[AnnotationImportItemSourceTypeDef],
         roleArn: str,
+        items: Sequence[AnnotationImportItemSourceTypeDef],
         formatOptions: FormatOptionsTypeDef = ...,
-        runLeftNormalization: bool = ...
+        runLeftNormalization: bool = ...,
+        annotationFields: Mapping[str, str] = ...
     ) -> StartAnnotationImportResponseTypeDef:
         """
         Starts an annotation import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_annotation_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_annotation_import_job)
         """
@@ -802,39 +889,39 @@
         self,
         *,
         sequenceStoreId: str,
         sources: Sequence[StartReadSetActivationJobSourceItemTypeDef],
         clientToken: str = ...
     ) -> StartReadSetActivationJobResponseTypeDef:
         """
-        Starts a read set activation job.
+        Activates an archived read set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_activation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_read_set_activation_job)
         """
     async def start_read_set_export_job(
         self,
         *,
+        sequenceStoreId: str,
         destination: str,
         roleArn: str,
-        sequenceStoreId: str,
         sources: Sequence[ExportReadSetTypeDef],
         clientToken: str = ...
     ) -> StartReadSetExportJobResponseTypeDef:
         """
-        Starts a read set export job.
+        Exports a read set to Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_export_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_read_set_export_job)
         """
     async def start_read_set_import_job(
         self,
         *,
-        roleArn: str,
         sequenceStoreId: str,
+        roleArn: str,
         sources: Sequence[StartReadSetImportJobSourceItemTypeDef],
         clientToken: str = ...
     ) -> StartReadSetImportJobResponseTypeDef:
         """
         Starts a read set import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_read_set_import_job)
@@ -853,41 +940,42 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_reference_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_reference_import_job)
         """
     async def start_run(
         self,
         *,
-        requestId: str,
         roleArn: str,
-        logLevel: RunLogLevelType = ...,
+        requestId: str,
+        workflowId: str = ...,
+        workflowType: WorkflowTypeType = ...,
+        runId: str = ...,
         name: str = ...,
-        outputUri: str = ...,
-        parameters: Mapping[str, Any] = ...,
-        priority: int = ...,
         runGroupId: str = ...,
-        runId: str = ...,
+        priority: int = ...,
+        parameters: Mapping[str, Any] = ...,
         storageCapacity: int = ...,
-        tags: Mapping[str, str] = ...,
-        workflowId: str = ...,
-        workflowType: Literal["PRIVATE"] = ...
+        outputUri: str = ...,
+        logLevel: RunLogLevelType = ...,
+        tags: Mapping[str, str] = ...
     ) -> StartRunResponseTypeDef:
         """
         Starts a run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_run)
         """
     async def start_variant_import_job(
         self,
         *,
         destinationName: str,
-        items: Sequence[VariantImportItemSourceTypeDef],
         roleArn: str,
-        runLeftNormalization: bool = ...
+        items: Sequence[VariantImportItemSourceTypeDef],
+        runLeftNormalization: bool = ...,
+        annotationFields: Mapping[str, str] = ...
     ) -> StartVariantImportResponseTypeDef:
         """
         Starts a variant import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.start_variant_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#start_variant_import_job)
         """
@@ -914,18 +1002,19 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_annotation_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_annotation_store)
         """
     async def update_run_group(
         self,
         *,
         id: str,
+        name: str = ...,
         maxCpus: int = ...,
-        maxDuration: int = ...,
         maxRuns: int = ...,
-        name: str = ...
+        maxDuration: int = ...,
+        maxGpus: int = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a run group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_run_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_run_group)
         """
@@ -935,22 +1024,37 @@
         """
         Updates a variant store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_variant_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_variant_store)
         """
     async def update_workflow(
-        self, *, id: str, description: str = ..., name: str = ...
+        self, *, id: str, name: str = ..., description: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.update_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#update_workflow)
         """
+    async def upload_read_set_part(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        partNumber: int,
+        payload: Union[str, bytes, IO[Any], StreamingBody]
+    ) -> UploadReadSetPartResponseTypeDef:
+        """
+        This operation uploads a specific part of a read set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.upload_read_set_part)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#upload_read_set_part)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_annotation_import_jobs"]
     ) -> ListAnnotationImportJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
@@ -961,14 +1065,22 @@
     ) -> ListAnnotationStoresPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_multipart_read_set_uploads"]
+    ) -> ListMultipartReadSetUploadsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_read_set_activation_jobs"]
     ) -> ListReadSetActivationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
     @overload
@@ -984,14 +1096,22 @@
         self, operation_name: Literal["list_read_set_import_jobs"]
     ) -> ListReadSetImportJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_read_set_upload_parts"]
+    ) -> ListReadSetUploadPartsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_read_sets"]) -> ListReadSetsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/client/#get_paginator)
         """
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/literals.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,41 +2,44 @@
 Type annotations for omics service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_omics.literals import AnnotationImportJobCreatedWaiterName
+    from types_aiobotocore_omics.literals import AcceleratorsType
 
-    data: AnnotationImportJobCreatedWaiterName = "annotation_import_job_created"
+    data: AcceleratorsType = "GPU"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AcceleratorsType",
     "AnnotationImportJobCreatedWaiterName",
     "AnnotationStoreCreatedWaiterName",
     "AnnotationStoreDeletedWaiterName",
     "AnnotationTypeType",
     "EncryptionTypeType",
     "FileTypeType",
     "FormatToHeaderKeyType",
     "JobStatusType",
     "ListAnnotationImportJobsPaginatorName",
     "ListAnnotationStoresPaginatorName",
+    "ListMultipartReadSetUploadsPaginatorName",
     "ListReadSetActivationJobsPaginatorName",
     "ListReadSetExportJobsPaginatorName",
     "ListReadSetImportJobsPaginatorName",
+    "ListReadSetUploadPartsPaginatorName",
     "ListReadSetsPaginatorName",
     "ListReferenceImportJobsPaginatorName",
     "ListReferenceStoresPaginatorName",
     "ListReferencesPaginatorName",
     "ListRunGroupsPaginatorName",
     "ListRunTasksPaginatorName",
     "ListRunsPaginatorName",
@@ -50,14 +53,15 @@
     "ReadSetExportJobCompletedWaiterName",
     "ReadSetExportJobItemStatusType",
     "ReadSetExportJobStatusType",
     "ReadSetFileType",
     "ReadSetImportJobCompletedWaiterName",
     "ReadSetImportJobItemStatusType",
     "ReadSetImportJobStatusType",
+    "ReadSetPartSourceType",
     "ReadSetStatusType",
     "ReferenceFileType",
     "ReferenceImportJobCompletedWaiterName",
     "ReferenceImportJobItemStatusType",
     "ReferenceImportJobStatusType",
     "ReferenceStatusType",
     "RunCompletedWaiterName",
@@ -80,17 +84,19 @@
     "WorkflowStatusType",
     "WorkflowTypeType",
     "OmicsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
+    "RegionName",
 )
 
 
+AcceleratorsType = Literal["GPU"]
 AnnotationImportJobCreatedWaiterName = Literal["annotation_import_job_created"]
 AnnotationStoreCreatedWaiterName = Literal["annotation_store_created"]
 AnnotationStoreDeletedWaiterName = Literal["annotation_store_deleted"]
 AnnotationTypeType = Literal[
     "CHR_POS",
     "CHR_POS_REF_ALT",
     "CHR_START_END_ONE_BASE",
@@ -98,20 +104,24 @@
     "CHR_START_END_REF_ALT_ZERO_BASE",
     "CHR_START_END_ZERO_BASE",
     "GENERIC",
 ]
 EncryptionTypeType = Literal["KMS"]
 FileTypeType = Literal["BAM", "CRAM", "FASTQ"]
 FormatToHeaderKeyType = Literal["ALT", "CHR", "END", "POS", "REF", "START"]
-JobStatusType = Literal["CANCELLED", "COMPLETED", "FAILED", "IN_PROGRESS", "SUBMITTED"]
+JobStatusType = Literal[
+    "CANCELLED", "COMPLETED", "COMPLETED_WITH_FAILURES", "FAILED", "IN_PROGRESS", "SUBMITTED"
+]
 ListAnnotationImportJobsPaginatorName = Literal["list_annotation_import_jobs"]
 ListAnnotationStoresPaginatorName = Literal["list_annotation_stores"]
+ListMultipartReadSetUploadsPaginatorName = Literal["list_multipart_read_set_uploads"]
 ListReadSetActivationJobsPaginatorName = Literal["list_read_set_activation_jobs"]
 ListReadSetExportJobsPaginatorName = Literal["list_read_set_export_jobs"]
 ListReadSetImportJobsPaginatorName = Literal["list_read_set_import_jobs"]
+ListReadSetUploadPartsPaginatorName = Literal["list_read_set_upload_parts"]
 ListReadSetsPaginatorName = Literal["list_read_sets"]
 ListReferenceImportJobsPaginatorName = Literal["list_reference_import_jobs"]
 ListReferenceStoresPaginatorName = Literal["list_reference_stores"]
 ListReferencesPaginatorName = Literal["list_references"]
 ListRunGroupsPaginatorName = Literal["list_run_groups"]
 ListRunTasksPaginatorName = Literal["list_run_tasks"]
 ListRunsPaginatorName = Literal["list_runs"]
@@ -149,15 +159,18 @@
     "CANCELLING",
     "COMPLETED",
     "COMPLETED_WITH_FAILURES",
     "FAILED",
     "IN_PROGRESS",
     "SUBMITTED",
 ]
-ReadSetStatusType = Literal["ACTIVATING", "ACTIVE", "ARCHIVED", "DELETED", "DELETING"]
+ReadSetPartSourceType = Literal["SOURCE1", "SOURCE2"]
+ReadSetStatusType = Literal[
+    "ACTIVATING", "ACTIVE", "ARCHIVED", "DELETED", "DELETING", "PROCESSING_UPLOAD", "UPLOAD_FAILED"
+]
 ReferenceFileType = Literal["INDEX", "SOURCE"]
 ReferenceImportJobCompletedWaiterName = Literal["reference_import_job_completed"]
 ReferenceImportJobItemStatusType = Literal["FAILED", "FINISHED", "IN_PROGRESS", "NOT_STARTED"]
 ReferenceImportJobStatusType = Literal[
     "CANCELLED",
     "CANCELLING",
     "COMPLETED",
@@ -184,16 +197,16 @@
 ]
 VariantImportJobCreatedWaiterName = Literal["variant_import_job_created"]
 VariantStoreCreatedWaiterName = Literal["variant_store_created"]
 VariantStoreDeletedWaiterName = Literal["variant_store_deleted"]
 WorkflowActiveWaiterName = Literal["workflow_active"]
 WorkflowEngineType = Literal["NEXTFLOW", "WDL"]
 WorkflowExportType = Literal["DEFINITION"]
-WorkflowStatusType = Literal["ACTIVE", "CREATING", "DELETED", "FAILED", "UPDATING"]
-WorkflowTypeType = Literal["PRIVATE"]
+WorkflowStatusType = Literal["ACTIVE", "CREATING", "DELETED", "FAILED", "INACTIVE", "UPDATING"]
+WorkflowTypeType = Literal["PRIVATE", "READY2RUN"]
 OmicsServiceName = Literal["omics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -249,14 +262,15 @@
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
@@ -335,14 +349,15 @@
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
@@ -353,14 +368,15 @@
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
@@ -396,14 +412,15 @@
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
@@ -422,16 +439,19 @@
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
@@ -515,15 +535,17 @@
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
@@ -544,17 +566,19 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_annotation_import_jobs",
     "list_annotation_stores",
+    "list_multipart_read_set_uploads",
     "list_read_set_activation_jobs",
     "list_read_set_export_jobs",
     "list_read_set_import_jobs",
+    "list_read_set_upload_parts",
     "list_read_sets",
     "list_reference_import_jobs",
     "list_reference_stores",
     "list_references",
     "list_run_groups",
     "list_run_tasks",
     "list_runs",
@@ -576,7 +600,10 @@
     "task_completed",
     "task_running",
     "variant_import_job_created",
     "variant_store_created",
     "variant_store_deleted",
     "workflow_active",
 ]
+RegionName = Literal[
+    "ap-southeast-1", "eu-central-1", "eu-west-1", "eu-west-2", "us-east-1", "us-west-2"
+]
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/literals.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/literals.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -2,40 +2,43 @@
 Type annotations for omics service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_omics.literals import AnnotationImportJobCreatedWaiterName
+    from types_aiobotocore_omics.literals import AcceleratorsType
 
-    data: AnnotationImportJobCreatedWaiterName = "annotation_import_job_created"
+    data: AcceleratorsType = "GPU"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AcceleratorsType",
     "AnnotationImportJobCreatedWaiterName",
     "AnnotationStoreCreatedWaiterName",
     "AnnotationStoreDeletedWaiterName",
     "AnnotationTypeType",
     "EncryptionTypeType",
     "FileTypeType",
     "FormatToHeaderKeyType",
     "JobStatusType",
     "ListAnnotationImportJobsPaginatorName",
     "ListAnnotationStoresPaginatorName",
+    "ListMultipartReadSetUploadsPaginatorName",
     "ListReadSetActivationJobsPaginatorName",
     "ListReadSetExportJobsPaginatorName",
     "ListReadSetImportJobsPaginatorName",
+    "ListReadSetUploadPartsPaginatorName",
     "ListReadSetsPaginatorName",
     "ListReferenceImportJobsPaginatorName",
     "ListReferenceStoresPaginatorName",
     "ListReferencesPaginatorName",
     "ListRunGroupsPaginatorName",
     "ListRunTasksPaginatorName",
     "ListRunsPaginatorName",
@@ -49,14 +52,15 @@
     "ReadSetExportJobCompletedWaiterName",
     "ReadSetExportJobItemStatusType",
     "ReadSetExportJobStatusType",
     "ReadSetFileType",
     "ReadSetImportJobCompletedWaiterName",
     "ReadSetImportJobItemStatusType",
     "ReadSetImportJobStatusType",
+    "ReadSetPartSourceType",
     "ReadSetStatusType",
     "ReferenceFileType",
     "ReferenceImportJobCompletedWaiterName",
     "ReferenceImportJobItemStatusType",
     "ReferenceImportJobStatusType",
     "ReferenceStatusType",
     "RunCompletedWaiterName",
@@ -79,16 +83,18 @@
     "WorkflowStatusType",
     "WorkflowTypeType",
     "OmicsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
+    "RegionName",
 )
 
+AcceleratorsType = Literal["GPU"]
 AnnotationImportJobCreatedWaiterName = Literal["annotation_import_job_created"]
 AnnotationStoreCreatedWaiterName = Literal["annotation_store_created"]
 AnnotationStoreDeletedWaiterName = Literal["annotation_store_deleted"]
 AnnotationTypeType = Literal[
     "CHR_POS",
     "CHR_POS_REF_ALT",
     "CHR_START_END_ONE_BASE",
@@ -96,20 +102,24 @@
     "CHR_START_END_REF_ALT_ZERO_BASE",
     "CHR_START_END_ZERO_BASE",
     "GENERIC",
 ]
 EncryptionTypeType = Literal["KMS"]
 FileTypeType = Literal["BAM", "CRAM", "FASTQ"]
 FormatToHeaderKeyType = Literal["ALT", "CHR", "END", "POS", "REF", "START"]
-JobStatusType = Literal["CANCELLED", "COMPLETED", "FAILED", "IN_PROGRESS", "SUBMITTED"]
+JobStatusType = Literal[
+    "CANCELLED", "COMPLETED", "COMPLETED_WITH_FAILURES", "FAILED", "IN_PROGRESS", "SUBMITTED"
+]
 ListAnnotationImportJobsPaginatorName = Literal["list_annotation_import_jobs"]
 ListAnnotationStoresPaginatorName = Literal["list_annotation_stores"]
+ListMultipartReadSetUploadsPaginatorName = Literal["list_multipart_read_set_uploads"]
 ListReadSetActivationJobsPaginatorName = Literal["list_read_set_activation_jobs"]
 ListReadSetExportJobsPaginatorName = Literal["list_read_set_export_jobs"]
 ListReadSetImportJobsPaginatorName = Literal["list_read_set_import_jobs"]
+ListReadSetUploadPartsPaginatorName = Literal["list_read_set_upload_parts"]
 ListReadSetsPaginatorName = Literal["list_read_sets"]
 ListReferenceImportJobsPaginatorName = Literal["list_reference_import_jobs"]
 ListReferenceStoresPaginatorName = Literal["list_reference_stores"]
 ListReferencesPaginatorName = Literal["list_references"]
 ListRunGroupsPaginatorName = Literal["list_run_groups"]
 ListRunTasksPaginatorName = Literal["list_run_tasks"]
 ListRunsPaginatorName = Literal["list_runs"]
@@ -147,15 +157,18 @@
     "CANCELLING",
     "COMPLETED",
     "COMPLETED_WITH_FAILURES",
     "FAILED",
     "IN_PROGRESS",
     "SUBMITTED",
 ]
-ReadSetStatusType = Literal["ACTIVATING", "ACTIVE", "ARCHIVED", "DELETED", "DELETING"]
+ReadSetPartSourceType = Literal["SOURCE1", "SOURCE2"]
+ReadSetStatusType = Literal[
+    "ACTIVATING", "ACTIVE", "ARCHIVED", "DELETED", "DELETING", "PROCESSING_UPLOAD", "UPLOAD_FAILED"
+]
 ReferenceFileType = Literal["INDEX", "SOURCE"]
 ReferenceImportJobCompletedWaiterName = Literal["reference_import_job_completed"]
 ReferenceImportJobItemStatusType = Literal["FAILED", "FINISHED", "IN_PROGRESS", "NOT_STARTED"]
 ReferenceImportJobStatusType = Literal[
     "CANCELLED",
     "CANCELLING",
     "COMPLETED",
@@ -182,16 +195,16 @@
 ]
 VariantImportJobCreatedWaiterName = Literal["variant_import_job_created"]
 VariantStoreCreatedWaiterName = Literal["variant_store_created"]
 VariantStoreDeletedWaiterName = Literal["variant_store_deleted"]
 WorkflowActiveWaiterName = Literal["workflow_active"]
 WorkflowEngineType = Literal["NEXTFLOW", "WDL"]
 WorkflowExportType = Literal["DEFINITION"]
-WorkflowStatusType = Literal["ACTIVE", "CREATING", "DELETED", "FAILED", "UPDATING"]
-WorkflowTypeType = Literal["PRIVATE"]
+WorkflowStatusType = Literal["ACTIVE", "CREATING", "DELETED", "FAILED", "INACTIVE", "UPDATING"]
+WorkflowTypeType = Literal["PRIVATE", "READY2RUN"]
 OmicsServiceName = Literal["omics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -247,14 +260,15 @@
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
@@ -333,14 +347,15 @@
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
@@ -351,14 +366,15 @@
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
@@ -394,14 +410,15 @@
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
@@ -420,16 +437,19 @@
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
@@ -513,15 +533,17 @@
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
@@ -542,17 +564,19 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_annotation_import_jobs",
     "list_annotation_stores",
+    "list_multipart_read_set_uploads",
     "list_read_set_activation_jobs",
     "list_read_set_export_jobs",
     "list_read_set_import_jobs",
+    "list_read_set_upload_parts",
     "list_read_sets",
     "list_reference_import_jobs",
     "list_reference_stores",
     "list_references",
     "list_run_groups",
     "list_run_tasks",
     "list_runs",
@@ -574,7 +598,10 @@
     "task_completed",
     "task_running",
     "variant_import_job_created",
     "variant_store_created",
     "variant_store_deleted",
     "workflow_active",
 ]
+RegionName = Literal[
+    "ap-southeast-1", "eu-central-1", "eu-west-1", "eu-west-2", "us-east-1", "us-west-2"
+]
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/paginator.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,17 +8,19 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_omics.client import OmicsClient
     from types_aiobotocore_omics.paginator import (
         ListAnnotationImportJobsPaginator,
         ListAnnotationStoresPaginator,
+        ListMultipartReadSetUploadsPaginator,
         ListReadSetActivationJobsPaginator,
         ListReadSetExportJobsPaginator,
         ListReadSetImportJobsPaginator,
+        ListReadSetUploadPartsPaginator,
         ListReadSetsPaginator,
         ListReferenceImportJobsPaginator,
         ListReferenceStoresPaginator,
         ListReferencesPaginator,
         ListRunGroupsPaginator,
         ListRunTasksPaginator,
         ListRunsPaginator,
@@ -30,85 +32,81 @@
 
     session = get_session()
     with session.create_client("omics") as client:
         client: OmicsClient
 
         list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator("list_annotation_import_jobs")
         list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator("list_annotation_stores")
+        list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = client.get_paginator("list_multipart_read_set_uploads")
         list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = client.get_paginator("list_read_set_activation_jobs")
         list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator("list_read_set_export_jobs")
         list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator("list_read_set_import_jobs")
+        list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator("list_read_set_upload_parts")
         list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
         list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator("list_reference_import_jobs")
         list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator("list_reference_stores")
         list_references_paginator: ListReferencesPaginator = client.get_paginator("list_references")
         list_run_groups_paginator: ListRunGroupsPaginator = client.get_paginator("list_run_groups")
         list_run_tasks_paginator: ListRunTasksPaginator = client.get_paginator("list_run_tasks")
         list_runs_paginator: ListRunsPaginator = client.get_paginator("list_runs")
         list_sequence_stores_paginator: ListSequenceStoresPaginator = client.get_paginator("list_sequence_stores")
         list_variant_import_jobs_paginator: ListVariantImportJobsPaginator = client.get_paginator("list_variant_import_jobs")
         list_variant_stores_paginator: ListVariantStoresPaginator = client.get_paginator("list_variant_stores")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import TaskStatusType
+from .literals import ReadSetPartSourceType, RunStatusType, TaskStatusType, WorkflowTypeType
 from .type_defs import (
     ActivateReadSetFilterTypeDef,
     ExportReadSetFilterTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReferenceFilterTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
     ListAnnotationImportJobsResponseTypeDef,
     ListAnnotationStoresFilterTypeDef,
     ListAnnotationStoresResponseTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
     ListReadSetActivationJobsResponseTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ListReadSetsResponseTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReferenceImportJobsResponseTypeDef,
     ListReferencesResponseTypeDef,
     ListReferenceStoresResponseTypeDef,
     ListRunGroupsResponseTypeDef,
     ListRunsResponseTypeDef,
     ListRunTasksResponseTypeDef,
     ListSequenceStoresResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     ListVariantImportJobsResponseTypeDef,
     ListVariantStoresFilterTypeDef,
     ListVariantStoresResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     PaginatorConfigTypeDef,
     ReadSetFilterTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceStoreFilterTypeDef,
     SequenceStoreFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-
-
 __all__ = (
     "ListAnnotationImportJobsPaginator",
     "ListAnnotationStoresPaginator",
+    "ListMultipartReadSetUploadsPaginator",
     "ListReadSetActivationJobsPaginator",
     "ListReadSetExportJobsPaginator",
     "ListReadSetImportJobsPaginator",
+    "ListReadSetUploadPartsPaginator",
     "ListReadSetsPaginator",
     "ListReferenceImportJobsPaginator",
     "ListReferenceStoresPaginator",
     "ListReferencesPaginator",
     "ListRunGroupsPaginator",
     "ListRunTasksPaginator",
     "ListRunsPaginator",
@@ -134,17 +132,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListAnnotationImportJobsFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListAnnotationImportJobsFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAnnotationImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationimportjobspaginator)
         """
 
 
@@ -153,36 +151,51 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationStores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationstorespaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListAnnotationStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListAnnotationStoresFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAnnotationStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationstorespaginator)
         """
 
 
+class ListMultipartReadSetUploadsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListMultipartReadSetUploads)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listmultipartreadsetuploadspaginator)
+    """
+
+    def paginate(
+        self, *, sequenceStoreId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListMultipartReadSetUploadsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListMultipartReadSetUploads.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listmultipartreadsetuploadspaginator)
+        """
+
+
 class ListReadSetActivationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetActivationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetactivationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ActivateReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetActivationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetActivationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetactivationjobspaginator)
         """
 
 
@@ -193,15 +206,15 @@
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ExportReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetexportjobspaginator)
         """
 
 
@@ -212,34 +225,55 @@
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ImportReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetimportjobspaginator)
         """
 
 
+class ListReadSetUploadPartsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetUploadParts)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetuploadpartspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        filter: ReadSetUploadPartListFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListReadSetUploadPartsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetUploadParts.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetuploadpartspaginator)
+        """
+
+
 class ListReadSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetspaginator)
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetspaginator)
         """
 
 
@@ -250,15 +284,15 @@
     """
 
     def paginate(
         self,
         *,
         referenceStoreId: str,
         filter: ImportReferenceFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferenceImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferenceImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferenceimportjobspaginator)
         """
 
 
@@ -268,15 +302,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencestorespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: ReferenceStoreFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferenceStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferenceStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencestorespaginator)
         """
 
 
@@ -287,30 +321,30 @@
     """
 
     def paginate(
         self,
         *,
         referenceStoreId: str,
         filter: ReferenceFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferencesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferences.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencespaginator)
         """
 
 
 class ListRunGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrungroupspaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrungroupspaginator)
         """
 
 
@@ -321,15 +355,15 @@
     """
 
     def paginate(
         self,
         *,
         id: str,
         status: TaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listruntaskspaginator)
         """
 
 
@@ -340,15 +374,16 @@
     """
 
     def paginate(
         self,
         *,
         name: str = ...,
         runGroupId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        status: RunStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrunspaginator)
         """
 
 
@@ -358,15 +393,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listsequencestorespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: SequenceStoreFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSequenceStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListSequenceStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listsequencestorespaginator)
         """
 
 
@@ -375,17 +410,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListVariantImportJobsFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListVariantImportJobsFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVariantImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantimportjobspaginator)
         """
 
 
@@ -394,17 +429,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantStores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantstorespaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListVariantStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListVariantStoresFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVariantStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantstorespaginator)
         """
 
 
@@ -413,15 +448,15 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListWorkflows)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listworkflowspaginator)
     """
 
     def paginate(
         self,
         *,
+        type: WorkflowTypeType = ...,
         name: str = ...,
-        type: Literal["PRIVATE"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/paginator.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -8,17 +8,19 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_omics.client import OmicsClient
     from types_aiobotocore_omics.paginator import (
         ListAnnotationImportJobsPaginator,
         ListAnnotationStoresPaginator,
+        ListMultipartReadSetUploadsPaginator,
         ListReadSetActivationJobsPaginator,
         ListReadSetExportJobsPaginator,
         ListReadSetImportJobsPaginator,
+        ListReadSetUploadPartsPaginator,
         ListReadSetsPaginator,
         ListReferenceImportJobsPaginator,
         ListReferenceStoresPaginator,
         ListReferencesPaginator,
         ListRunGroupsPaginator,
         ListRunTasksPaginator,
         ListRunsPaginator,
@@ -30,84 +32,81 @@
 
     session = get_session()
     with session.create_client("omics") as client:
         client: OmicsClient
 
         list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator("list_annotation_import_jobs")
         list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator("list_annotation_stores")
+        list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = client.get_paginator("list_multipart_read_set_uploads")
         list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = client.get_paginator("list_read_set_activation_jobs")
         list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator("list_read_set_export_jobs")
         list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator("list_read_set_import_jobs")
+        list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator("list_read_set_upload_parts")
         list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
         list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator("list_reference_import_jobs")
         list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator("list_reference_stores")
         list_references_paginator: ListReferencesPaginator = client.get_paginator("list_references")
         list_run_groups_paginator: ListRunGroupsPaginator = client.get_paginator("list_run_groups")
         list_run_tasks_paginator: ListRunTasksPaginator = client.get_paginator("list_run_tasks")
         list_runs_paginator: ListRunsPaginator = client.get_paginator("list_runs")
         list_sequence_stores_paginator: ListSequenceStoresPaginator = client.get_paginator("list_sequence_stores")
         list_variant_import_jobs_paginator: ListVariantImportJobsPaginator = client.get_paginator("list_variant_import_jobs")
         list_variant_stores_paginator: ListVariantStoresPaginator = client.get_paginator("list_variant_stores")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import TaskStatusType
+from .literals import ReadSetPartSourceType, RunStatusType, TaskStatusType, WorkflowTypeType
 from .type_defs import (
     ActivateReadSetFilterTypeDef,
     ExportReadSetFilterTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReferenceFilterTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
     ListAnnotationImportJobsResponseTypeDef,
     ListAnnotationStoresFilterTypeDef,
     ListAnnotationStoresResponseTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
     ListReadSetActivationJobsResponseTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ListReadSetsResponseTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReferenceImportJobsResponseTypeDef,
     ListReferencesResponseTypeDef,
     ListReferenceStoresResponseTypeDef,
     ListRunGroupsResponseTypeDef,
     ListRunsResponseTypeDef,
     ListRunTasksResponseTypeDef,
     ListSequenceStoresResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     ListVariantImportJobsResponseTypeDef,
     ListVariantStoresFilterTypeDef,
     ListVariantStoresResponseTypeDef,
     ListWorkflowsResponseTypeDef,
     PaginatorConfigTypeDef,
     ReadSetFilterTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceStoreFilterTypeDef,
     SequenceStoreFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-
 __all__ = (
     "ListAnnotationImportJobsPaginator",
     "ListAnnotationStoresPaginator",
+    "ListMultipartReadSetUploadsPaginator",
     "ListReadSetActivationJobsPaginator",
     "ListReadSetExportJobsPaginator",
     "ListReadSetImportJobsPaginator",
+    "ListReadSetUploadPartsPaginator",
     "ListReadSetsPaginator",
     "ListReferenceImportJobsPaginator",
     "ListReferenceStoresPaginator",
     "ListReferencesPaginator",
     "ListRunGroupsPaginator",
     "ListRunTasksPaginator",
     "ListRunsPaginator",
@@ -130,17 +129,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListAnnotationImportJobsFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListAnnotationImportJobsFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAnnotationImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationimportjobspaginator)
         """
 
 class ListAnnotationStoresPaginator(AioPaginator):
@@ -148,35 +147,49 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationStores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationstorespaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListAnnotationStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListAnnotationStoresFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAnnotationStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListAnnotationStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listannotationstorespaginator)
         """
 
+class ListMultipartReadSetUploadsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListMultipartReadSetUploads)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listmultipartreadsetuploadspaginator)
+    """
+
+    def paginate(
+        self, *, sequenceStoreId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListMultipartReadSetUploadsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListMultipartReadSetUploads.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listmultipartreadsetuploadspaginator)
+        """
+
 class ListReadSetActivationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetActivationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetactivationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ActivateReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetActivationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetActivationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetactivationjobspaginator)
         """
 
 class ListReadSetExportJobsPaginator(AioPaginator):
@@ -186,15 +199,15 @@
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ExportReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetexportjobspaginator)
         """
 
 class ListReadSetImportJobsPaginator(AioPaginator):
@@ -204,33 +217,53 @@
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ImportReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetimportjobspaginator)
         """
 
+class ListReadSetUploadPartsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetUploadParts)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetuploadpartspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        sequenceStoreId: str,
+        uploadId: str,
+        partSource: ReadSetPartSourceType,
+        filter: ReadSetUploadPartListFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListReadSetUploadPartsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSetUploadParts.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetuploadpartspaginator)
+        """
+
 class ListReadSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetspaginator)
     """
 
     def paginate(
         self,
         *,
         sequenceStoreId: str,
         filter: ReadSetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReadSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreadsetspaginator)
         """
 
 class ListReferenceImportJobsPaginator(AioPaginator):
@@ -240,15 +273,15 @@
     """
 
     def paginate(
         self,
         *,
         referenceStoreId: str,
         filter: ImportReferenceFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferenceImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferenceImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferenceimportjobspaginator)
         """
 
 class ListReferenceStoresPaginator(AioPaginator):
@@ -257,15 +290,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencestorespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: ReferenceStoreFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferenceStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferenceStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencestorespaginator)
         """
 
 class ListReferencesPaginator(AioPaginator):
@@ -275,29 +308,29 @@
     """
 
     def paginate(
         self,
         *,
         referenceStoreId: str,
         filter: ReferenceFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReferencesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListReferences.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listreferencespaginator)
         """
 
 class ListRunGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrungroupspaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrungroupspaginator)
         """
 
 class ListRunTasksPaginator(AioPaginator):
@@ -307,15 +340,15 @@
     """
 
     def paginate(
         self,
         *,
         id: str,
         status: TaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRunTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listruntaskspaginator)
         """
 
 class ListRunsPaginator(AioPaginator):
@@ -325,15 +358,16 @@
     """
 
     def paginate(
         self,
         *,
         name: str = ...,
         runGroupId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        status: RunStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listrunspaginator)
         """
 
 class ListSequenceStoresPaginator(AioPaginator):
@@ -342,15 +376,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listsequencestorespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: SequenceStoreFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSequenceStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListSequenceStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listsequencestorespaginator)
         """
 
 class ListVariantImportJobsPaginator(AioPaginator):
@@ -358,17 +392,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListVariantImportJobsFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListVariantImportJobsFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVariantImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantimportjobspaginator)
         """
 
 class ListVariantStoresPaginator(AioPaginator):
@@ -376,17 +410,17 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantStores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantstorespaginator)
     """
 
     def paginate(
         self,
         *,
-        filter: ListVariantStoresFilterTypeDef = ...,
         ids: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        filter: ListVariantStoresFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVariantStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListVariantStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listvariantstorespaginator)
         """
 
 class ListWorkflowsPaginator(AioPaginator):
@@ -394,15 +428,15 @@
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListWorkflows)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listworkflowspaginator)
     """
 
     def paginate(
         self,
         *,
+        type: WorkflowTypeType = ...,
         name: str = ...,
-        type: Literal["PRIVATE"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/type_defs.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for omics service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_omics.type_defs import ActivateReadSetFilterTypeDef
+    from types_aiobotocore_omics.type_defs import AbortMultipartReadSetUploadRequestRequestTypeDef
 
-    data: ActivateReadSetFilterTypeDef = {...}
+    data: AbortMultipartReadSetUploadRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -25,64 +25,75 @@
     ReadSetActivationJobItemStatusType,
     ReadSetActivationJobStatusType,
     ReadSetExportJobItemStatusType,
     ReadSetExportJobStatusType,
     ReadSetFileType,
     ReadSetImportJobItemStatusType,
     ReadSetImportJobStatusType,
+    ReadSetPartSourceType,
     ReadSetStatusType,
     ReferenceFileType,
     ReferenceImportJobItemStatusType,
     ReferenceImportJobStatusType,
     ReferenceStatusType,
     RunLogLevelType,
     RunStatusType,
     SchemaValueTypeType,
     StoreFormatType,
     StoreStatusType,
     TaskStatusType,
     WorkflowEngineType,
     WorkflowStatusType,
+    WorkflowTypeType,
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
+    "AbortMultipartReadSetUploadRequestRequestTypeDef",
     "ActivateReadSetFilterTypeDef",
     "ActivateReadSetJobItemTypeDef",
     "ActivateReadSetSourceItemTypeDef",
     "AnnotationImportItemDetailTypeDef",
     "AnnotationImportItemSourceTypeDef",
     "AnnotationImportJobItemTypeDef",
     "ReferenceItemTypeDef",
     "SseConfigTypeDef",
     "BatchDeleteReadSetRequestRequestTypeDef",
     "ReadSetBatchErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "CancelAnnotationImportRequestRequestTypeDef",
     "CancelRunRequestRequestTypeDef",
     "CancelVariantImportRequestRequestTypeDef",
+    "CompleteReadSetUploadPartListItemTypeDef",
+    "CompleteMultipartReadSetUploadResponseTypeDef",
+    "CreateMultipartReadSetUploadRequestRequestTypeDef",
+    "CreateMultipartReadSetUploadResponseTypeDef",
     "CreateRunGroupRequestRequestTypeDef",
+    "CreateRunGroupResponseTypeDef",
     "WorkflowParameterTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "DeleteAnnotationStoreRequestRequestTypeDef",
+    "DeleteAnnotationStoreResponseTypeDef",
     "DeleteReferenceRequestRequestTypeDef",
     "DeleteReferenceStoreRequestRequestTypeDef",
     "DeleteRunGroupRequestRequestTypeDef",
     "DeleteRunRequestRequestTypeDef",
     "DeleteSequenceStoreRequestRequestTypeDef",
     "DeleteVariantStoreRequestRequestTypeDef",
+    "DeleteVariantStoreResponseTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportReadSetDetailTypeDef",
     "ExportReadSetFilterTypeDef",
     "ExportReadSetJobDetailTypeDef",
     "ExportReadSetTypeDef",
     "FileInformationTypeDef",
     "VcfOptionsTypeDef",
     "WaiterConfigTypeDef",
@@ -90,104 +101,114 @@
     "GetAnnotationStoreRequestRequestTypeDef",
     "GetReadSetActivationJobRequestRequestTypeDef",
     "GetReadSetExportJobRequestRequestTypeDef",
     "GetReadSetImportJobRequestRequestTypeDef",
     "GetReadSetMetadataRequestRequestTypeDef",
     "SequenceInformationTypeDef",
     "GetReadSetRequestRequestTypeDef",
+    "GetReadSetResponseTypeDef",
     "GetReferenceImportJobRequestRequestTypeDef",
     "ImportReferenceSourceItemTypeDef",
     "GetReferenceMetadataRequestRequestTypeDef",
     "GetReferenceRequestRequestTypeDef",
+    "GetReferenceResponseTypeDef",
     "GetReferenceStoreRequestRequestTypeDef",
     "GetRunGroupRequestRequestTypeDef",
+    "GetRunGroupResponseTypeDef",
     "GetRunRequestRequestTypeDef",
+    "GetRunResponseTypeDef",
     "GetRunTaskRequestRequestTypeDef",
+    "GetRunTaskResponseTypeDef",
     "GetSequenceStoreRequestRequestTypeDef",
     "GetVariantImportRequestRequestTypeDef",
     "VariantImportItemDetailTypeDef",
     "GetVariantStoreRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "ImportReadSetFilterTypeDef",
     "ImportReadSetJobItemTypeDef",
     "SourceFilesTypeDef",
     "ImportReferenceFilterTypeDef",
     "ImportReferenceJobItemTypeDef",
     "ListAnnotationImportJobsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListAnnotationStoresFilterTypeDef",
+    "ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
+    "ListMultipartReadSetUploadsRequestRequestTypeDef",
+    "MultipartReadSetUploadListItemTypeDef",
+    "ReadSetUploadPartListFilterTypeDef",
+    "ReadSetUploadPartListItemTypeDef",
     "ReadSetFilterTypeDef",
     "ReferenceStoreFilterTypeDef",
     "ReferenceFilterTypeDef",
     "ReferenceListItemTypeDef",
+    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
     "ListRunGroupsRequestRequestTypeDef",
     "RunGroupListItemTypeDef",
+    "ListRunTasksRequestListRunTasksPaginateTypeDef",
     "ListRunTasksRequestRequestTypeDef",
     "TaskListItemTypeDef",
+    "ListRunsRequestListRunsPaginateTypeDef",
     "ListRunsRequestRequestTypeDef",
     "RunListItemTypeDef",
     "SequenceStoreFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListVariantImportJobsFilterTypeDef",
     "VariantImportJobItemTypeDef",
     "ListVariantStoresFilterTypeDef",
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "WorkflowListItemTypeDef",
+    "PaginatorConfigTypeDef",
     "ReadOptionsTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartAnnotationImportResponseTypeDef",
     "StartReadSetActivationJobSourceItemTypeDef",
+    "StartReadSetActivationJobResponseTypeDef",
+    "StartReadSetExportJobResponseTypeDef",
+    "StartReadSetImportJobResponseTypeDef",
     "StartReferenceImportJobSourceItemTypeDef",
+    "StartReferenceImportJobResponseTypeDef",
     "StartRunRequestRequestTypeDef",
+    "StartRunResponseTypeDef",
     "VariantImportItemSourceTypeDef",
+    "StartVariantImportResponseTypeDef",
     "TsvStoreOptionsTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAnnotationStoreRequestRequestTypeDef",
     "UpdateRunGroupRequestRequestTypeDef",
     "UpdateVariantStoreRequestRequestTypeDef",
     "UpdateWorkflowRequestRequestTypeDef",
+    "UploadReadSetPartRequestRequestTypeDef",
+    "UploadReadSetPartResponseTypeDef",
+    "ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
     "ListReadSetActivationJobsRequestRequestTypeDef",
+    "ListReadSetActivationJobsResponseTypeDef",
+    "GetReadSetActivationJobResponseTypeDef",
+    "ListAnnotationImportJobsResponseTypeDef",
+    "CreateVariantStoreResponseTypeDef",
+    "UpdateVariantStoreResponseTypeDef",
     "AnnotationStoreItemTypeDef",
     "CreateReferenceStoreRequestRequestTypeDef",
+    "CreateReferenceStoreResponseTypeDef",
     "CreateSequenceStoreRequestRequestTypeDef",
+    "CreateSequenceStoreResponseTypeDef",
     "CreateVariantStoreRequestRequestTypeDef",
+    "GetReferenceStoreResponseTypeDef",
+    "GetSequenceStoreResponseTypeDef",
+    "GetVariantStoreResponseTypeDef",
     "ReferenceStoreDetailTypeDef",
     "SequenceStoreDetailTypeDef",
     "VariantStoreItemTypeDef",
     "BatchDeleteReadSetResponseTypeDef",
-    "CreateReferenceStoreResponseTypeDef",
-    "CreateRunGroupResponseTypeDef",
-    "CreateSequenceStoreResponseTypeDef",
-    "CreateVariantStoreResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "DeleteAnnotationStoreResponseTypeDef",
-    "DeleteVariantStoreResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetReadSetActivationJobResponseTypeDef",
-    "GetReadSetResponseTypeDef",
-    "GetReferenceResponseTypeDef",
-    "GetReferenceStoreResponseTypeDef",
-    "GetRunGroupResponseTypeDef",
-    "GetRunResponseTypeDef",
-    "GetRunTaskResponseTypeDef",
-    "GetSequenceStoreResponseTypeDef",
-    "GetVariantStoreResponseTypeDef",
-    "ListAnnotationImportJobsResponseTypeDef",
-    "ListReadSetActivationJobsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartAnnotationImportResponseTypeDef",
-    "StartReadSetActivationJobResponseTypeDef",
-    "StartReadSetExportJobResponseTypeDef",
-    "StartReadSetImportJobResponseTypeDef",
-    "StartReferenceImportJobResponseTypeDef",
-    "StartRunResponseTypeDef",
-    "StartVariantImportResponseTypeDef",
-    "UpdateVariantStoreResponseTypeDef",
+    "CompleteMultipartReadSetUploadRequestRequestTypeDef",
     "CreateWorkflowRequestRequestTypeDef",
     "GetWorkflowResponseTypeDef",
     "GetReadSetExportJobResponseTypeDef",
+    "ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
     "ListReadSetExportJobsRequestRequestTypeDef",
     "ListReadSetExportJobsResponseTypeDef",
     "StartReadSetExportJobRequestRequestTypeDef",
     "ReadSetFilesTypeDef",
     "ReferenceFilesTypeDef",
     "GetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef",
     "GetAnnotationStoreRequestAnnotationStoreCreatedWaitTypeDef",
@@ -203,32 +224,30 @@
     "GetVariantImportRequestVariantImportJobCreatedWaitTypeDef",
     "GetVariantStoreRequestVariantStoreCreatedWaitTypeDef",
     "GetVariantStoreRequestVariantStoreDeletedWaitTypeDef",
     "GetWorkflowRequestWorkflowActiveWaitTypeDef",
     "ReadSetListItemTypeDef",
     "GetReferenceImportJobResponseTypeDef",
     "GetVariantImportResponseTypeDef",
+    "ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
     "ListReadSetImportJobsRequestRequestTypeDef",
     "ListReadSetImportJobsResponseTypeDef",
     "ImportReadSetSourceItemTypeDef",
     "StartReadSetImportJobSourceItemTypeDef",
+    "ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
     "ListReferenceImportJobsRequestRequestTypeDef",
     "ListReferenceImportJobsResponseTypeDef",
-    "ListAnnotationImportJobsRequestRequestTypeDef",
     "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
-    "ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
-    "ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
-    "ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
-    "ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
-    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
-    "ListRunTasksRequestListRunTasksPaginateTypeDef",
-    "ListRunsRequestListRunsPaginateTypeDef",
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    "ListAnnotationImportJobsRequestRequestTypeDef",
     "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
     "ListAnnotationStoresRequestRequestTypeDef",
+    "ListMultipartReadSetUploadsResponseTypeDef",
+    "ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
+    "ListReadSetUploadPartsRequestRequestTypeDef",
+    "ListReadSetUploadPartsResponseTypeDef",
     "ListReadSetsRequestListReadSetsPaginateTypeDef",
     "ListReadSetsRequestRequestTypeDef",
     "ListReferenceStoresRequestListReferenceStoresPaginateTypeDef",
     "ListReferenceStoresRequestRequestTypeDef",
     "ListReferencesRequestListReferencesPaginateTypeDef",
     "ListReferencesRequestRequestTypeDef",
     "ListReferencesResponseTypeDef",
@@ -262,31 +281,39 @@
     "CreateAnnotationStoreResponseTypeDef",
     "GetAnnotationStoreResponseTypeDef",
     "UpdateAnnotationStoreResponseTypeDef",
     "GetAnnotationImportResponseTypeDef",
     "StartAnnotationImportRequestRequestTypeDef",
 )
 
+AbortMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "AbortMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+    },
+)
+
 ActivateReadSetFilterTypeDef = TypedDict(
     "ActivateReadSetFilterTypeDef",
     {
+        "status": ReadSetActivationJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetActivationJobStatusType,
     },
     total=False,
 )
 
 _RequiredActivateReadSetJobItemTypeDef = TypedDict(
     "_RequiredActivateReadSetJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
         "sequenceStoreId": str,
         "status": ReadSetActivationJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalActivateReadSetJobItemTypeDef = TypedDict(
     "_OptionalActivateReadSetJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -321,42 +348,43 @@
 ):
     pass
 
 
 AnnotationImportItemDetailTypeDef = TypedDict(
     "AnnotationImportItemDetailTypeDef",
     {
-        "jobStatus": JobStatusType,
         "source": str,
+        "jobStatus": JobStatusType,
     },
 )
 
 AnnotationImportItemSourceTypeDef = TypedDict(
     "AnnotationImportItemSourceTypeDef",
     {
         "source": str,
     },
 )
 
 _RequiredAnnotationImportJobItemTypeDef = TypedDict(
     "_RequiredAnnotationImportJobItemTypeDef",
     {
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
+        "destinationName": str,
         "roleArn": str,
         "status": JobStatusType,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalAnnotationImportJobItemTypeDef = TypedDict(
     "_OptionalAnnotationImportJobItemTypeDef",
     {
         "completionTime": datetime,
         "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
     },
     total=False,
 )
 
 
 class AnnotationImportJobItemTypeDef(
     _RequiredAnnotationImportJobItemTypeDef, _OptionalAnnotationImportJobItemTypeDef
@@ -398,31 +426,20 @@
         "sequenceStoreId": str,
     },
 )
 
 ReadSetBatchErrorTypeDef = TypedDict(
     "ReadSetBatchErrorTypeDef",
     {
-        "code": str,
         "id": str,
+        "code": str,
         "message": str,
     },
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
 CancelAnnotationImportRequestRequestTypeDef = TypedDict(
     "CancelAnnotationImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
@@ -436,48 +453,135 @@
 CancelVariantImportRequestRequestTypeDef = TypedDict(
     "CancelVariantImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
+CompleteReadSetUploadPartListItemTypeDef = TypedDict(
+    "CompleteReadSetUploadPartListItemTypeDef",
+    {
+        "partNumber": int,
+        "partSource": ReadSetPartSourceType,
+        "checksum": str,
+    },
+)
+
+CompleteMultipartReadSetUploadResponseTypeDef = TypedDict(
+    "CompleteMultipartReadSetUploadResponseTypeDef",
+    {
+        "readSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "referenceArn": str,
+        "name": str,
+    },
+)
+_OptionalCreateMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "generatedFrom": str,
+        "description": str,
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class CreateMultipartReadSetUploadRequestRequestTypeDef(
+    _RequiredCreateMultipartReadSetUploadRequestRequestTypeDef,
+    _OptionalCreateMultipartReadSetUploadRequestRequestTypeDef,
+):
+    pass
+
+
+CreateMultipartReadSetUploadResponseTypeDef = TypedDict(
+    "CreateMultipartReadSetUploadResponseTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "generatedFrom": str,
+        "referenceArn": str,
+        "name": str,
+        "description": str,
+        "tags": Dict[str, str],
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRunGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRunGroupRequestRequestTypeDef",
     {
         "requestId": str,
     },
 )
 _OptionalCreateRunGroupRequestRequestTypeDef = TypedDict(
     "_OptionalCreateRunGroupRequestRequestTypeDef",
     {
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
         "tags": Mapping[str, str],
+        "maxGpus": int,
     },
     total=False,
 )
 
 
 class CreateRunGroupRequestRequestTypeDef(
     _RequiredCreateRunGroupRequestRequestTypeDef, _OptionalCreateRunGroupRequestRequestTypeDef
 ):
     pass
 
 
+CreateRunGroupResponseTypeDef = TypedDict(
+    "CreateRunGroupResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowParameterTypeDef = TypedDict(
     "WorkflowParameterTypeDef",
     {
         "description": str,
         "optional": bool,
     },
     total=False,
 )
 
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": WorkflowStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAnnotationStoreRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAnnotationStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalDeleteAnnotationStoreRequestRequestTypeDef = TypedDict(
@@ -492,14 +596,22 @@
 class DeleteAnnotationStoreRequestRequestTypeDef(
     _RequiredDeleteAnnotationStoreRequestRequestTypeDef,
     _OptionalDeleteAnnotationStoreRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteAnnotationStoreResponseTypeDef = TypedDict(
+    "DeleteAnnotationStoreResponseTypeDef",
+    {
+        "status": StoreStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteReferenceRequestRequestTypeDef = TypedDict(
     "DeleteReferenceRequestRequestTypeDef",
     {
         "id": str,
         "referenceStoreId": str,
     },
 )
@@ -550,21 +662,36 @@
 class DeleteVariantStoreRequestRequestTypeDef(
     _RequiredDeleteVariantStoreRequestRequestTypeDef,
     _OptionalDeleteVariantStoreRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteVariantStoreResponseTypeDef = TypedDict(
+    "DeleteVariantStoreResponseTypeDef",
+    {
+        "status": StoreStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExportReadSetDetailTypeDef = TypedDict(
     "_RequiredExportReadSetDetailTypeDef",
     {
         "id": str,
         "status": ReadSetExportJobItemStatusType,
     },
 )
@@ -582,29 +709,29 @@
 ):
     pass
 
 
 ExportReadSetFilterTypeDef = TypedDict(
     "ExportReadSetFilterTypeDef",
     {
+        "status": ReadSetExportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetExportJobStatusType,
     },
     total=False,
 )
 
 _RequiredExportReadSetJobDetailTypeDef = TypedDict(
     "_RequiredExportReadSetJobDetailTypeDef",
     {
-        "creationTime": datetime,
-        "destination": str,
         "id": str,
         "sequenceStoreId": str,
+        "destination": str,
         "status": ReadSetExportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalExportReadSetJobDetailTypeDef = TypedDict(
     "_OptionalExportReadSetJobDetailTypeDef",
     {
         "completionTime": datetime,
     },
@@ -624,26 +751,26 @@
         "readSetId": str,
     },
 )
 
 FileInformationTypeDef = TypedDict(
     "FileInformationTypeDef",
     {
-        "contentLength": int,
-        "partSize": int,
         "totalParts": int,
+        "partSize": int,
+        "contentLength": int,
     },
     total=False,
 )
 
 VcfOptionsTypeDef = TypedDict(
     "VcfOptionsTypeDef",
     {
-        "ignoreFilterField": bool,
         "ignoreQualField": bool,
+        "ignoreFilterField": bool,
     },
     total=False,
 )
 
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
@@ -674,16 +801,16 @@
         "sequenceStoreId": str,
     },
 )
 
 GetReadSetExportJobRequestRequestTypeDef = TypedDict(
     "GetReadSetExportJobRequestRequestTypeDef",
     {
-        "id": str,
         "sequenceStoreId": str,
+        "id": str,
     },
 )
 
 GetReadSetImportJobRequestRequestTypeDef = TypedDict(
     "GetReadSetImportJobRequestRequestTypeDef",
     {
         "id": str,
@@ -698,28 +825,28 @@
         "sequenceStoreId": str,
     },
 )
 
 SequenceInformationTypeDef = TypedDict(
     "SequenceInformationTypeDef",
     {
-        "alignment": str,
-        "generatedFrom": str,
-        "totalBaseCount": int,
         "totalReadCount": int,
+        "totalBaseCount": int,
+        "generatedFrom": str,
+        "alignment": str,
     },
     total=False,
 )
 
 _RequiredGetReadSetRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadSetRequestRequestTypeDef",
     {
         "id": str,
-        "partNumber": int,
         "sequenceStoreId": str,
+        "partNumber": int,
     },
 )
 _OptionalGetReadSetRequestRequestTypeDef = TypedDict(
     "_OptionalGetReadSetRequestRequestTypeDef",
     {
         "file": ReadSetFileType,
     },
@@ -729,14 +856,22 @@
 
 class GetReadSetRequestRequestTypeDef(
     _RequiredGetReadSetRequestRequestTypeDef, _OptionalGetReadSetRequestRequestTypeDef
 ):
     pass
 
 
+GetReadSetResponseTypeDef = TypedDict(
+    "GetReadSetResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReferenceImportJobRequestRequestTypeDef = TypedDict(
     "GetReferenceImportJobRequestRequestTypeDef",
     {
         "id": str,
         "referenceStoreId": str,
     },
 )
@@ -746,18 +881,18 @@
     {
         "status": ReferenceImportJobItemStatusType,
     },
 )
 _OptionalImportReferenceSourceItemTypeDef = TypedDict(
     "_OptionalImportReferenceSourceItemTypeDef",
     {
-        "description": str,
-        "name": str,
         "sourceFile": str,
         "statusMessage": str,
+        "name": str,
+        "description": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
 
 class ImportReferenceSourceItemTypeDef(
@@ -774,48 +909,72 @@
     },
 )
 
 _RequiredGetReferenceRequestRequestTypeDef = TypedDict(
     "_RequiredGetReferenceRequestRequestTypeDef",
     {
         "id": str,
-        "partNumber": int,
         "referenceStoreId": str,
+        "partNumber": int,
     },
 )
 _OptionalGetReferenceRequestRequestTypeDef = TypedDict(
     "_OptionalGetReferenceRequestRequestTypeDef",
     {
-        "file": ReferenceFileType,
         "range": str,
+        "file": ReferenceFileType,
     },
     total=False,
 )
 
 
 class GetReferenceRequestRequestTypeDef(
     _RequiredGetReferenceRequestRequestTypeDef, _OptionalGetReferenceRequestRequestTypeDef
 ):
     pass
 
 
+GetReferenceResponseTypeDef = TypedDict(
+    "GetReferenceResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReferenceStoreRequestRequestTypeDef = TypedDict(
     "GetReferenceStoreRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
 GetRunGroupRequestRequestTypeDef = TypedDict(
     "GetRunGroupRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetRunGroupResponseTypeDef = TypedDict(
+    "GetRunGroupResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "maxCpus": int,
+        "maxRuns": int,
+        "maxDuration": int,
+        "creationTime": datetime,
+        "tags": Dict[str, str],
+        "maxGpus": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRunRequestRequestTypeDef = TypedDict(
     "_RequiredGetRunRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetRunRequestRequestTypeDef = TypedDict(
@@ -829,43 +988,106 @@
 
 class GetRunRequestRequestTypeDef(
     _RequiredGetRunRequestRequestTypeDef, _OptionalGetRunRequestRequestTypeDef
 ):
     pass
 
 
+GetRunResponseTypeDef = TypedDict(
+    "GetRunResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": RunStatusType,
+        "workflowId": str,
+        "workflowType": WorkflowTypeType,
+        "runId": str,
+        "roleArn": str,
+        "name": str,
+        "runGroupId": str,
+        "priority": int,
+        "definition": str,
+        "digest": str,
+        "parameters": Dict[str, Any],
+        "storageCapacity": int,
+        "outputUri": str,
+        "logLevel": RunLogLevelType,
+        "resourceDigests": Dict[str, str],
+        "startedBy": str,
+        "creationTime": datetime,
+        "startTime": datetime,
+        "stopTime": datetime,
+        "statusMessage": str,
+        "tags": Dict[str, str],
+        "accelerators": Literal["GPU"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRunTaskRequestRequestTypeDef = TypedDict(
     "GetRunTaskRequestRequestTypeDef",
     {
         "id": str,
         "taskId": str,
     },
 )
 
+GetRunTaskResponseTypeDef = TypedDict(
+    "GetRunTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "status": TaskStatusType,
+        "name": str,
+        "cpus": int,
+        "memory": int,
+        "creationTime": datetime,
+        "startTime": datetime,
+        "stopTime": datetime,
+        "statusMessage": str,
+        "logStream": str,
+        "gpus": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSequenceStoreRequestRequestTypeDef = TypedDict(
     "GetSequenceStoreRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
 GetVariantImportRequestRequestTypeDef = TypedDict(
     "GetVariantImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
-VariantImportItemDetailTypeDef = TypedDict(
-    "VariantImportItemDetailTypeDef",
+_RequiredVariantImportItemDetailTypeDef = TypedDict(
+    "_RequiredVariantImportItemDetailTypeDef",
     {
-        "jobStatus": JobStatusType,
         "source": str,
+        "jobStatus": JobStatusType,
     },
 )
+_OptionalVariantImportItemDetailTypeDef = TypedDict(
+    "_OptionalVariantImportItemDetailTypeDef",
+    {
+        "statusMessage": str,
+    },
+    total=False,
+)
+
+
+class VariantImportItemDetailTypeDef(
+    _RequiredVariantImportItemDetailTypeDef, _OptionalVariantImportItemDetailTypeDef
+):
+    pass
+
 
 GetVariantStoreRequestRequestTypeDef = TypedDict(
     "GetVariantStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
@@ -875,45 +1097,45 @@
     {
         "id": str,
     },
 )
 _OptionalGetWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalGetWorkflowRequestRequestTypeDef",
     {
+        "type": WorkflowTypeType,
         "export": Sequence[Literal["DEFINITION"]],
-        "type": Literal["PRIVATE"],
     },
     total=False,
 )
 
 
 class GetWorkflowRequestRequestTypeDef(
     _RequiredGetWorkflowRequestRequestTypeDef, _OptionalGetWorkflowRequestRequestTypeDef
 ):
     pass
 
 
 ImportReadSetFilterTypeDef = TypedDict(
     "ImportReadSetFilterTypeDef",
     {
+        "status": ReadSetImportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetImportJobStatusType,
     },
     total=False,
 )
 
 _RequiredImportReadSetJobItemTypeDef = TypedDict(
     "_RequiredImportReadSetJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
+        "roleArn": str,
         "status": ReadSetImportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalImportReadSetJobItemTypeDef = TypedDict(
     "_OptionalImportReadSetJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -945,29 +1167,29 @@
 class SourceFilesTypeDef(_RequiredSourceFilesTypeDef, _OptionalSourceFilesTypeDef):
     pass
 
 
 ImportReferenceFilterTypeDef = TypedDict(
     "ImportReferenceFilterTypeDef",
     {
+        "status": ReferenceImportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReferenceImportJobStatusType,
     },
     total=False,
 )
 
 _RequiredImportReferenceJobItemTypeDef = TypedDict(
     "_RequiredImportReferenceJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
         "referenceStoreId": str,
         "roleArn": str,
         "status": ReferenceImportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalImportReferenceJobItemTypeDef = TypedDict(
     "_OptionalImportReferenceJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -986,225 +1208,382 @@
     {
         "status": JobStatusType,
         "storeName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAnnotationStoresFilterTypeDef = TypedDict(
+    "ListAnnotationStoresFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "status": StoreStatusType,
     },
     total=False,
 )
 
-ListAnnotationStoresFilterTypeDef = TypedDict(
-    "ListAnnotationStoresFilterTypeDef",
+_RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
     {
-        "status": StoreStatusType,
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ReadSetFilterTypeDef = TypedDict(
-    "ReadSetFilterTypeDef",
+
+class ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef(
+    _RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+    _OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListMultipartReadSetUploadsRequestRequestTypeDef = TypedDict(
+    "_RequiredListMultipartReadSetUploadsRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListMultipartReadSetUploadsRequestRequestTypeDef = TypedDict(
+    "_OptionalListMultipartReadSetUploadsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListMultipartReadSetUploadsRequestRequestTypeDef(
+    _RequiredListMultipartReadSetUploadsRequestRequestTypeDef,
+    _OptionalListMultipartReadSetUploadsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredMultipartReadSetUploadListItemTypeDef = TypedDict(
+    "_RequiredMultipartReadSetUploadListItemTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "generatedFrom": str,
+        "referenceArn": str,
+        "creationTime": datetime,
+    },
+)
+_OptionalMultipartReadSetUploadListItemTypeDef = TypedDict(
+    "_OptionalMultipartReadSetUploadListItemTypeDef",
+    {
+        "name": str,
+        "description": str,
+        "tags": Dict[str, str],
+    },
+    total=False,
+)
+
+
+class MultipartReadSetUploadListItemTypeDef(
+    _RequiredMultipartReadSetUploadListItemTypeDef, _OptionalMultipartReadSetUploadListItemTypeDef
+):
+    pass
+
+
+ReadSetUploadPartListFilterTypeDef = TypedDict(
+    "ReadSetUploadPartListFilterTypeDef",
     {
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+_RequiredReadSetUploadPartListItemTypeDef = TypedDict(
+    "_RequiredReadSetUploadPartListItemTypeDef",
+    {
+        "partNumber": int,
+        "partSize": int,
+        "partSource": ReadSetPartSourceType,
+        "checksum": str,
+    },
+)
+_OptionalReadSetUploadPartListItemTypeDef = TypedDict(
+    "_OptionalReadSetUploadPartListItemTypeDef",
+    {
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+    },
+    total=False,
+)
+
+
+class ReadSetUploadPartListItemTypeDef(
+    _RequiredReadSetUploadPartListItemTypeDef, _OptionalReadSetUploadPartListItemTypeDef
+):
+    pass
+
+
+ReadSetFilterTypeDef = TypedDict(
+    "ReadSetFilterTypeDef",
+    {
         "name": str,
-        "referenceArn": str,
         "status": ReadSetStatusType,
+        "referenceArn": str,
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "sampleId": str,
+        "subjectId": str,
+        "generatedFrom": str,
     },
     total=False,
 )
 
 ReferenceStoreFilterTypeDef = TypedDict(
     "ReferenceStoreFilterTypeDef",
     {
+        "name": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "name": str,
     },
     total=False,
 )
 
 ReferenceFilterTypeDef = TypedDict(
     "ReferenceFilterTypeDef",
     {
+        "name": str,
+        "md5": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "md5": str,
-        "name": str,
     },
     total=False,
 )
 
 _RequiredReferenceListItemTypeDef = TypedDict(
     "_RequiredReferenceListItemTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
         "id": str,
-        "md5": str,
+        "arn": str,
         "referenceStoreId": str,
+        "md5": str,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalReferenceListItemTypeDef = TypedDict(
     "_OptionalReferenceListItemTypeDef",
     {
-        "description": str,
-        "name": str,
         "status": ReferenceStatusType,
+        "name": str,
+        "description": str,
     },
     total=False,
 )
 
 
 class ReferenceListItemTypeDef(
     _RequiredReferenceListItemTypeDef, _OptionalReferenceListItemTypeDef
 ):
     pass
 
 
+ListRunGroupsRequestListRunGroupsPaginateTypeDef = TypedDict(
+    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
+    {
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRunGroupsRequestRequestTypeDef = TypedDict(
     "ListRunGroupsRequestRequestTypeDef",
     {
-        "maxResults": int,
         "name": str,
         "startingToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
 RunGroupListItemTypeDef = TypedDict(
     "RunGroupListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
+        "creationTime": datetime,
+        "maxGpus": int,
+    },
+    total=False,
+)
+
+_RequiredListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
+    "_RequiredListRunTasksRequestListRunTasksPaginateTypeDef",
+    {
+        "id": str,
+    },
+)
+_OptionalListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
+    "_OptionalListRunTasksRequestListRunTasksPaginateTypeDef",
+    {
+        "status": TaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListRunTasksRequestListRunTasksPaginateTypeDef(
+    _RequiredListRunTasksRequestListRunTasksPaginateTypeDef,
+    _OptionalListRunTasksRequestListRunTasksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRunTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListRunTasksRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalListRunTasksRequestRequestTypeDef = TypedDict(
     "_OptionalListRunTasksRequestRequestTypeDef",
     {
-        "maxResults": int,
-        "startingToken": str,
         "status": TaskStatusType,
+        "startingToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
 
 class ListRunTasksRequestRequestTypeDef(
     _RequiredListRunTasksRequestRequestTypeDef, _OptionalListRunTasksRequestRequestTypeDef
 ):
     pass
 
 
 TaskListItemTypeDef = TypedDict(
     "TaskListItemTypeDef",
     {
+        "taskId": str,
+        "status": TaskStatusType,
+        "name": str,
         "cpus": int,
-        "creationTime": datetime,
         "memory": int,
-        "name": str,
+        "creationTime": datetime,
         "startTime": datetime,
-        "status": TaskStatusType,
         "stopTime": datetime,
-        "taskId": str,
+        "gpus": int,
+    },
+    total=False,
+)
+
+ListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "ListRunsRequestListRunsPaginateTypeDef",
+    {
+        "name": str,
+        "runGroupId": str,
+        "status": RunStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRunsRequestRequestTypeDef = TypedDict(
     "ListRunsRequestRequestTypeDef",
     {
-        "maxResults": int,
         "name": str,
         "runGroupId": str,
         "startingToken": str,
+        "maxResults": int,
+        "status": RunStatusType,
     },
     total=False,
 )
 
 RunListItemTypeDef = TypedDict(
     "RunListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "status": RunStatusType,
+        "workflowId": str,
         "name": str,
         "priority": int,
+        "storageCapacity": int,
+        "creationTime": datetime,
         "startTime": datetime,
-        "status": RunStatusType,
         "stopTime": datetime,
-        "storageCapacity": int,
-        "workflowId": str,
     },
     total=False,
 )
 
 SequenceStoreFilterTypeDef = TypedDict(
     "SequenceStoreFilterTypeDef",
     {
+        "name": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "name": str,
     },
     total=False,
 )
 
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListVariantImportJobsFilterTypeDef = TypedDict(
     "ListVariantImportJobsFilterTypeDef",
     {
         "status": JobStatusType,
         "storeName": str,
     },
     total=False,
 )
 
 _RequiredVariantImportJobItemTypeDef = TypedDict(
     "_RequiredVariantImportJobItemTypeDef",
     {
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
+        "destinationName": str,
         "roleArn": str,
         "status": JobStatusType,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalVariantImportJobItemTypeDef = TypedDict(
     "_OptionalVariantImportJobItemTypeDef",
     {
         "completionTime": datetime,
         "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
     },
     total=False,
 )
 
 
 class VariantImportJobItemTypeDef(
     _RequiredVariantImportJobItemTypeDef, _OptionalVariantImportJobItemTypeDef
@@ -1216,67 +1595,142 @@
     "ListVariantStoresFilterTypeDef",
     {
         "status": StoreStatusType,
     },
     total=False,
 )
 
+ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "type": WorkflowTypeType,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
-        "maxResults": int,
+        "type": WorkflowTypeType,
         "name": str,
         "startingToken": str,
-        "type": Literal["PRIVATE"],
+        "maxResults": int,
     },
     total=False,
 )
 
 WorkflowListItemTypeDef = TypedDict(
     "WorkflowListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
-        "digest": str,
         "id": str,
         "name": str,
         "status": WorkflowStatusType,
-        "type": Literal["PRIVATE"],
+        "type": WorkflowTypeType,
+        "digest": str,
+        "creationTime": datetime,
+        "metadata": Dict[str, str],
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
 
 ReadOptionsTypeDef = TypedDict(
     "ReadOptionsTypeDef",
     {
-        "comment": str,
+        "sep": str,
         "encoding": str,
+        "quote": str,
+        "quoteAll": bool,
         "escape": str,
         "escapeQuotes": bool,
+        "comment": str,
         "header": bool,
         "lineSep": str,
-        "quote": str,
-        "quoteAll": bool,
-        "sep": str,
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
+StartAnnotationImportResponseTypeDef = TypedDict(
+    "StartAnnotationImportResponseTypeDef",
+    {
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartReadSetActivationJobSourceItemTypeDef = TypedDict(
     "StartReadSetActivationJobSourceItemTypeDef",
     {
         "readSetId": str,
     },
 )
 
+StartReadSetActivationJobResponseTypeDef = TypedDict(
+    "StartReadSetActivationJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "status": ReadSetActivationJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartReadSetExportJobResponseTypeDef = TypedDict(
+    "StartReadSetExportJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "destination": str,
+        "status": ReadSetExportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartReadSetImportJobResponseTypeDef = TypedDict(
+    "StartReadSetImportJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "roleArn": str,
+        "status": ReadSetImportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartReferenceImportJobSourceItemTypeDef = TypedDict(
     "_RequiredStartReferenceImportJobSourceItemTypeDef",
     {
-        "name": str,
         "sourceFile": str,
+        "name": str,
     },
 )
 _OptionalStartReferenceImportJobSourceItemTypeDef = TypedDict(
     "_OptionalStartReferenceImportJobSourceItemTypeDef",
     {
         "description": str,
         "tags": Mapping[str, str],
@@ -1288,53 +1742,84 @@
 class StartReferenceImportJobSourceItemTypeDef(
     _RequiredStartReferenceImportJobSourceItemTypeDef,
     _OptionalStartReferenceImportJobSourceItemTypeDef,
 ):
     pass
 
 
+StartReferenceImportJobResponseTypeDef = TypedDict(
+    "StartReferenceImportJobResponseTypeDef",
+    {
+        "id": str,
+        "referenceStoreId": str,
+        "roleArn": str,
+        "status": ReferenceImportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartRunRequestRequestTypeDef",
     {
-        "requestId": str,
         "roleArn": str,
+        "requestId": str,
     },
 )
 _OptionalStartRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartRunRequestRequestTypeDef",
     {
-        "logLevel": RunLogLevelType,
+        "workflowId": str,
+        "workflowType": WorkflowTypeType,
+        "runId": str,
         "name": str,
-        "outputUri": str,
-        "parameters": Mapping[str, Any],
-        "priority": int,
         "runGroupId": str,
-        "runId": str,
+        "priority": int,
+        "parameters": Mapping[str, Any],
         "storageCapacity": int,
+        "outputUri": str,
+        "logLevel": RunLogLevelType,
         "tags": Mapping[str, str],
-        "workflowId": str,
-        "workflowType": Literal["PRIVATE"],
     },
     total=False,
 )
 
 
 class StartRunRequestRequestTypeDef(
     _RequiredStartRunRequestRequestTypeDef, _OptionalStartRunRequestRequestTypeDef
 ):
     pass
 
 
+StartRunResponseTypeDef = TypedDict(
+    "StartRunResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": RunStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VariantImportItemSourceTypeDef = TypedDict(
     "VariantImportItemSourceTypeDef",
     {
         "source": str,
     },
 )
 
+StartVariantImportResponseTypeDef = TypedDict(
+    "StartVariantImportResponseTypeDef",
+    {
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TsvStoreOptionsTypeDef = TypedDict(
     "TsvStoreOptionsTypeDef",
     {
         "annotationType": AnnotationTypeType,
         "formatToHeader": Mapping[FormatToHeaderKeyType, str],
         "schema": Sequence[Mapping[str, SchemaValueTypeType]],
     },
@@ -1384,18 +1869,19 @@
     {
         "id": str,
     },
 )
 _OptionalUpdateRunGroupRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateRunGroupRequestRequestTypeDef",
     {
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
+        "maxGpus": int,
     },
     total=False,
 )
 
 
 class UpdateRunGroupRequestRequestTypeDef(
     _RequiredUpdateRunGroupRequestRequestTypeDef, _OptionalUpdateRunGroupRequestRequestTypeDef
@@ -1430,157 +1916,331 @@
     {
         "id": str,
     },
 )
 _OptionalUpdateWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateWorkflowRequestRequestTypeDef",
     {
-        "description": str,
         "name": str,
+        "description": str,
     },
     total=False,
 )
 
 
 class UpdateWorkflowRequestRequestTypeDef(
     _RequiredUpdateWorkflowRequestRequestTypeDef, _OptionalUpdateWorkflowRequestRequestTypeDef
 ):
     pass
 
 
+UploadReadSetPartRequestRequestTypeDef = TypedDict(
+    "UploadReadSetPartRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
+        "partNumber": int,
+        "payload": Union[str, bytes, IO[Any], StreamingBody],
+    },
+)
+
+UploadReadSetPartResponseTypeDef = TypedDict(
+    "UploadReadSetPartResponseTypeDef",
+    {
+        "checksum": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+    {
+        "filter": ActivateReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef(
+    _RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
+    _OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListReadSetActivationJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetActivationJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetActivationJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetActivationJobsRequestRequestTypeDef",
     {
-        "filter": ActivateReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ActivateReadSetFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReadSetActivationJobsRequestRequestTypeDef(
     _RequiredListReadSetActivationJobsRequestRequestTypeDef,
     _OptionalListReadSetActivationJobsRequestRequestTypeDef,
 ):
     pass
 
 
-AnnotationStoreItemTypeDef = TypedDict(
-    "AnnotationStoreItemTypeDef",
+ListReadSetActivationJobsResponseTypeDef = TypedDict(
+    "ListReadSetActivationJobsResponseTypeDef",
     {
+        "nextToken": str,
+        "activationJobs": List[ActivateReadSetJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetReadSetActivationJobResponseTypeDef = TypedDict(
+    "GetReadSetActivationJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "status": ReadSetActivationJobStatusType,
+        "statusMessage": str,
         "creationTime": datetime,
-        "description": str,
+        "completionTime": datetime,
+        "sources": List[ActivateReadSetSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAnnotationImportJobsResponseTypeDef = TypedDict(
+    "ListAnnotationImportJobsResponseTypeDef",
+    {
+        "annotationImportJobs": List[AnnotationImportJobItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVariantStoreResponseTypeDef = TypedDict(
+    "CreateVariantStoreResponseTypeDef",
+    {
         "id": str,
+        "reference": ReferenceItemTypeDef,
+        "status": StoreStatusType,
         "name": str,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateVariantStoreResponseTypeDef = TypedDict(
+    "UpdateVariantStoreResponseTypeDef",
+    {
+        "id": str,
+        "reference": ReferenceItemTypeDef,
+        "status": StoreStatusType,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
+        "updateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AnnotationStoreItemTypeDef = TypedDict(
+    "AnnotationStoreItemTypeDef",
+    {
+        "id": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
+        "name": str,
         "storeFormat": StoreFormatType,
-        "storeSizeBytes": int,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
         "updateTime": datetime,
+        "statusMessage": str,
+        "storeSizeBytes": int,
     },
 )
 
 _RequiredCreateReferenceStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReferenceStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateReferenceStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateReferenceStoreRequestRequestTypeDef",
     {
-        "clientToken": str,
         "description": str,
         "sseConfig": SseConfigTypeDef,
         "tags": Mapping[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
 
 class CreateReferenceStoreRequestRequestTypeDef(
     _RequiredCreateReferenceStoreRequestRequestTypeDef,
     _OptionalCreateReferenceStoreRequestRequestTypeDef,
 ):
     pass
 
 
+CreateReferenceStoreResponseTypeDef = TypedDict(
+    "CreateReferenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSequenceStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSequenceStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateSequenceStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSequenceStoreRequestRequestTypeDef",
     {
-        "clientToken": str,
         "description": str,
         "sseConfig": SseConfigTypeDef,
         "tags": Mapping[str, str],
+        "clientToken": str,
+        "fallbackLocation": str,
     },
     total=False,
 )
 
 
 class CreateSequenceStoreRequestRequestTypeDef(
     _RequiredCreateSequenceStoreRequestRequestTypeDef,
     _OptionalCreateSequenceStoreRequestRequestTypeDef,
 ):
     pass
 
 
+CreateSequenceStoreResponseTypeDef = TypedDict(
+    "CreateSequenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "fallbackLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateVariantStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVariantStoreRequestRequestTypeDef",
     {
         "reference": ReferenceItemTypeDef,
     },
 )
 _OptionalCreateVariantStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVariantStoreRequestRequestTypeDef",
     {
-        "description": str,
         "name": str,
-        "sseConfig": SseConfigTypeDef,
+        "description": str,
         "tags": Mapping[str, str],
+        "sseConfig": SseConfigTypeDef,
     },
     total=False,
 )
 
 
 class CreateVariantStoreRequestRequestTypeDef(
     _RequiredCreateVariantStoreRequestRequestTypeDef,
     _OptionalCreateVariantStoreRequestRequestTypeDef,
 ):
     pass
 
 
+GetReferenceStoreResponseTypeDef = TypedDict(
+    "GetReferenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSequenceStoreResponseTypeDef = TypedDict(
+    "GetSequenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "fallbackLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetVariantStoreResponseTypeDef = TypedDict(
+    "GetVariantStoreResponseTypeDef",
+    {
+        "id": str,
+        "reference": ReferenceItemTypeDef,
+        "status": StoreStatusType,
+        "storeArn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "updateTime": datetime,
+        "tags": Dict[str, str],
+        "statusMessage": str,
+        "storeSizeBytes": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredReferenceStoreDetailTypeDef = TypedDict(
     "_RequiredReferenceStoreDetailTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "creationTime": datetime,
     },
 )
 _OptionalReferenceStoreDetailTypeDef = TypedDict(
     "_OptionalReferenceStoreDetailTypeDef",
     {
-        "description": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
     },
     total=False,
 )
 
 
 class ReferenceStoreDetailTypeDef(
@@ -1589,411 +2249,89 @@
     pass
 
 
 _RequiredSequenceStoreDetailTypeDef = TypedDict(
     "_RequiredSequenceStoreDetailTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "creationTime": datetime,
     },
 )
 _OptionalSequenceStoreDetailTypeDef = TypedDict(
     "_OptionalSequenceStoreDetailTypeDef",
     {
-        "description": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
+        "fallbackLocation": str,
     },
     total=False,
 )
 
 
 class SequenceStoreDetailTypeDef(
     _RequiredSequenceStoreDetailTypeDef, _OptionalSequenceStoreDetailTypeDef
 ):
     pass
 
 
 VariantStoreItemTypeDef = TypedDict(
     "VariantStoreItemTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
-        "storeSizeBytes": int,
-        "updateTime": datetime,
-    },
-)
-
-BatchDeleteReadSetResponseTypeDef = TypedDict(
-    "BatchDeleteReadSetResponseTypeDef",
-    {
-        "errors": List[ReadSetBatchErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReferenceStoreResponseTypeDef = TypedDict(
-    "CreateReferenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRunGroupResponseTypeDef = TypedDict(
-    "CreateRunGroupResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSequenceStoreResponseTypeDef = TypedDict(
-    "CreateSequenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVariantStoreResponseTypeDef = TypedDict(
-    "CreateVariantStoreResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "id": str,
-        "name": str,
-        "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "status": WorkflowStatusType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteAnnotationStoreResponseTypeDef = TypedDict(
-    "DeleteAnnotationStoreResponseTypeDef",
-    {
-        "status": StoreStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteVariantStoreResponseTypeDef = TypedDict(
-    "DeleteVariantStoreResponseTypeDef",
-    {
-        "status": StoreStatusType,
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
-GetReadSetActivationJobResponseTypeDef = TypedDict(
-    "GetReadSetActivationJobResponseTypeDef",
-    {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "id": str,
-        "sequenceStoreId": str,
-        "sources": List[ActivateReadSetSourceItemTypeDef],
-        "status": ReadSetActivationJobStatusType,
-        "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReadSetResponseTypeDef = TypedDict(
-    "GetReadSetResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReferenceResponseTypeDef = TypedDict(
-    "GetReferenceResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReferenceStoreResponseTypeDef = TypedDict(
-    "GetReferenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRunGroupResponseTypeDef = TypedDict(
-    "GetRunGroupResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "id": str,
-        "maxCpus": int,
-        "maxDuration": int,
-        "maxRuns": int,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRunResponseTypeDef = TypedDict(
-    "GetRunResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "definition": str,
-        "digest": str,
-        "id": str,
-        "logLevel": RunLogLevelType,
         "name": str,
-        "outputUri": str,
-        "parameters": Dict[str, Any],
-        "priority": int,
-        "resourceDigests": Dict[str, str],
-        "roleArn": str,
-        "runGroupId": str,
-        "runId": str,
-        "startTime": datetime,
-        "startedBy": str,
-        "status": RunStatusType,
-        "statusMessage": str,
-        "stopTime": datetime,
-        "storageCapacity": int,
-        "tags": Dict[str, str],
-        "workflowId": str,
-        "workflowType": Literal["PRIVATE"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRunTaskResponseTypeDef = TypedDict(
-    "GetRunTaskResponseTypeDef",
-    {
-        "cpus": int,
-        "creationTime": datetime,
-        "logStream": str,
-        "memory": int,
-        "name": str,
-        "startTime": datetime,
-        "status": TaskStatusType,
-        "statusMessage": str,
-        "stopTime": datetime,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSequenceStoreResponseTypeDef = TypedDict(
-    "GetSequenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
         "description": str,
-        "id": str,
-        "name": str,
         "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVariantStoreResponseTypeDef = TypedDict(
-    "GetVariantStoreResponseTypeDef",
-    {
         "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
-        "status": StoreStatusType,
+        "updateTime": datetime,
         "statusMessage": str,
-        "storeArn": str,
         "storeSizeBytes": int,
-        "tags": Dict[str, str],
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAnnotationImportJobsResponseTypeDef = TypedDict(
-    "ListAnnotationImportJobsResponseTypeDef",
-    {
-        "annotationImportJobs": List[AnnotationImportJobItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReadSetActivationJobsResponseTypeDef = TypedDict(
-    "ListReadSetActivationJobsResponseTypeDef",
-    {
-        "activationJobs": List[ActivateReadSetJobItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAnnotationImportResponseTypeDef = TypedDict(
-    "StartAnnotationImportResponseTypeDef",
-    {
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReadSetActivationJobResponseTypeDef = TypedDict(
-    "StartReadSetActivationJobResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "id": str,
-        "sequenceStoreId": str,
-        "status": ReadSetActivationJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartReadSetExportJobResponseTypeDef = TypedDict(
-    "StartReadSetExportJobResponseTypeDef",
+BatchDeleteReadSetResponseTypeDef = TypedDict(
+    "BatchDeleteReadSetResponseTypeDef",
     {
-        "creationTime": datetime,
-        "destination": str,
-        "id": str,
-        "sequenceStoreId": str,
-        "status": ReadSetExportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[ReadSetBatchErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartReadSetImportJobResponseTypeDef = TypedDict(
-    "StartReadSetImportJobResponseTypeDef",
+CompleteMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "CompleteMultipartReadSetUploadRequestRequestTypeDef",
     {
-        "creationTime": datetime,
-        "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
-        "status": ReadSetImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReferenceImportJobResponseTypeDef = TypedDict(
-    "StartReferenceImportJobResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "id": str,
-        "referenceStoreId": str,
-        "roleArn": str,
-        "status": ReferenceImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRunResponseTypeDef = TypedDict(
-    "StartRunResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "status": RunStatusType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartVariantImportResponseTypeDef = TypedDict(
-    "StartVariantImportResponseTypeDef",
-    {
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVariantStoreResponseTypeDef = TypedDict(
-    "UpdateVariantStoreResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "uploadId": str,
+        "parts": Sequence[CompleteReadSetUploadPartListItemTypeDef],
     },
 )
 
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "requestId": str,
     },
 )
 _OptionalCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalCreateWorkflowRequestRequestTypeDef",
     {
-        "definitionUri": str,
-        "definitionZip": Union[str, bytes, IO[Any], StreamingBody],
+        "name": str,
         "description": str,
         "engine": WorkflowEngineType,
+        "definitionZip": Union[str, bytes, IO[Any], StreamingBody],
+        "definitionUri": str,
         "main": str,
-        "name": str,
         "parameterTemplate": Mapping[str, WorkflowParameterTypeDef],
         "storageCapacity": int,
         "tags": Mapping[str, str],
+        "accelerators": Literal["GPU"],
     },
     total=False,
 )
 
 
 class CreateWorkflowRequestRequestTypeDef(
     _RequiredCreateWorkflowRequestRequestTypeDef, _OptionalCreateWorkflowRequestRequestTypeDef
@@ -2001,59 +2339,84 @@
     pass
 
 
 GetWorkflowResponseTypeDef = TypedDict(
     "GetWorkflowResponseTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
-        "definition": str,
+        "id": str,
+        "status": WorkflowStatusType,
+        "type": WorkflowTypeType,
+        "name": str,
         "description": str,
-        "digest": str,
         "engine": WorkflowEngineType,
-        "id": str,
+        "definition": str,
         "main": str,
-        "name": str,
+        "digest": str,
         "parameterTemplate": Dict[str, WorkflowParameterTypeDef],
-        "status": WorkflowStatusType,
-        "statusMessage": str,
         "storageCapacity": int,
+        "creationTime": datetime,
+        "statusMessage": str,
         "tags": Dict[str, str],
-        "type": Literal["PRIVATE"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "metadata": Dict[str, str],
+        "accelerators": Literal["GPU"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetExportJobResponseTypeDef = TypedDict(
     "GetReadSetExportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destination": str,
         "id": str,
-        "readSets": List[ExportReadSetDetailTypeDef],
         "sequenceStoreId": str,
+        "destination": str,
         "status": ReadSetExportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "readSets": List[ExportReadSetDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
     },
 )
+_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+    {
+        "filter": ExportReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef(
+    _RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
+    _OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
+):
+    pass
+
 
 _RequiredListReadSetExportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetExportJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetExportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetExportJobsRequestRequestTypeDef",
     {
-        "filter": ExportReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ExportReadSetFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReadSetExportJobsRequestRequestTypeDef(
     _RequiredListReadSetExportJobsRequestRequestTypeDef,
@@ -2061,26 +2424,26 @@
 ):
     pass
 
 
 ListReadSetExportJobsResponseTypeDef = TypedDict(
     "ListReadSetExportJobsResponseTypeDef",
     {
-        "exportJobs": List[ExportReadSetJobDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "exportJobs": List[ExportReadSetJobDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReadSetExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartReadSetExportJobRequestRequestTypeDef",
     {
+        "sequenceStoreId": str,
         "destination": str,
         "roleArn": str,
-        "sequenceStoreId": str,
         "sources": Sequence[ExportReadSetTypeDef],
     },
 )
 _OptionalStartReadSetExportJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartReadSetExportJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -2095,26 +2458,26 @@
 ):
     pass
 
 
 ReadSetFilesTypeDef = TypedDict(
     "ReadSetFilesTypeDef",
     {
-        "index": FileInformationTypeDef,
         "source1": FileInformationTypeDef,
         "source2": FileInformationTypeDef,
+        "index": FileInformationTypeDef,
     },
     total=False,
 )
 
 ReferenceFilesTypeDef = TypedDict(
     "ReferenceFilesTypeDef",
     {
-        "index": FileInformationTypeDef,
         "source": FileInformationTypeDef,
+        "index": FileInformationTypeDef,
     },
     total=False,
 )
 
 _RequiredGetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef = TypedDict(
     "_RequiredGetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef",
     {
@@ -2203,16 +2566,16 @@
 ):
     pass
 
 
 _RequiredGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef = TypedDict(
     "_RequiredGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef",
     {
-        "id": str,
         "sequenceStoreId": str,
+        "id": str,
     },
 )
 _OptionalGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef = TypedDict(
     "_OptionalGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
@@ -2434,16 +2797,16 @@
     {
         "id": str,
     },
 )
 _OptionalGetWorkflowRequestWorkflowActiveWaitTypeDef = TypedDict(
     "_OptionalGetWorkflowRequestWorkflowActiveWaitTypeDef",
     {
+        "type": WorkflowTypeType,
         "export": Sequence[Literal["DEFINITION"]],
-        "type": Literal["PRIVATE"],
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
 
 class GetWorkflowRequestWorkflowActiveWaitTypeDef(
@@ -2452,84 +2815,109 @@
 ):
     pass
 
 
 _RequiredReadSetListItemTypeDef = TypedDict(
     "_RequiredReadSetListItemTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "fileType": FileTypeType,
         "id": str,
+        "arn": str,
         "sequenceStoreId": str,
         "status": ReadSetStatusType,
+        "fileType": FileTypeType,
+        "creationTime": datetime,
     },
 )
 _OptionalReadSetListItemTypeDef = TypedDict(
     "_OptionalReadSetListItemTypeDef",
     {
-        "description": str,
+        "subjectId": str,
+        "sampleId": str,
         "name": str,
+        "description": str,
         "referenceArn": str,
-        "sampleId": str,
         "sequenceInformation": SequenceInformationTypeDef,
-        "subjectId": str,
+        "statusMessage": str,
     },
     total=False,
 )
 
 
 class ReadSetListItemTypeDef(_RequiredReadSetListItemTypeDef, _OptionalReadSetListItemTypeDef):
     pass
 
 
 GetReferenceImportJobResponseTypeDef = TypedDict(
     "GetReferenceImportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
         "id": str,
         "referenceStoreId": str,
         "roleArn": str,
-        "sources": List[ImportReferenceSourceItemTypeDef],
         "status": ReferenceImportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "sources": List[ImportReferenceSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVariantImportResponseTypeDef = TypedDict(
     "GetVariantImportResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
-        "items": List[VariantImportItemDetailTypeDef],
+        "destinationName": str,
         "roleArn": str,
-        "runLeftNormalization": bool,
         "status": JobStatusType,
         "statusMessage": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "completionTime": datetime,
+        "items": List[VariantImportItemDetailTypeDef],
+        "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+    {
+        "filter": ImportReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
+
+class ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef(
+    _RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
+    _OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListReadSetImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetImportJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetImportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetImportJobsRequestRequestTypeDef",
     {
-        "filter": ImportReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ImportReadSetFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReadSetImportJobsRequestRequestTypeDef(
     _RequiredListReadSetImportJobsRequestRequestTypeDef,
@@ -2537,38 +2925,38 @@
 ):
     pass
 
 
 ListReadSetImportJobsResponseTypeDef = TypedDict(
     "ListReadSetImportJobsResponseTypeDef",
     {
-        "importJobs": List[ImportReadSetJobItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "importJobs": List[ImportReadSetJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportReadSetSourceItemTypeDef = TypedDict(
     "_RequiredImportReadSetSourceItemTypeDef",
     {
-        "sampleId": str,
-        "sourceFileType": FileTypeType,
         "sourceFiles": SourceFilesTypeDef,
+        "sourceFileType": FileTypeType,
         "status": ReadSetImportJobItemStatusType,
         "subjectId": str,
+        "sampleId": str,
     },
 )
 _OptionalImportReadSetSourceItemTypeDef = TypedDict(
     "_OptionalImportReadSetSourceItemTypeDef",
     {
-        "description": str,
+        "statusMessage": str,
         "generatedFrom": str,
-        "name": str,
         "referenceArn": str,
-        "statusMessage": str,
+        "name": str,
+        "description": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
 
 class ImportReadSetSourceItemTypeDef(
@@ -2576,51 +2964,74 @@
 ):
     pass
 
 
 _RequiredStartReadSetImportJobSourceItemTypeDef = TypedDict(
     "_RequiredStartReadSetImportJobSourceItemTypeDef",
     {
-        "referenceArn": str,
-        "sampleId": str,
-        "sourceFileType": FileTypeType,
         "sourceFiles": SourceFilesTypeDef,
+        "sourceFileType": FileTypeType,
         "subjectId": str,
+        "sampleId": str,
+        "referenceArn": str,
     },
 )
 _OptionalStartReadSetImportJobSourceItemTypeDef = TypedDict(
     "_OptionalStartReadSetImportJobSourceItemTypeDef",
     {
-        "description": str,
         "generatedFrom": str,
         "name": str,
+        "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class StartReadSetImportJobSourceItemTypeDef(
     _RequiredStartReadSetImportJobSourceItemTypeDef, _OptionalStartReadSetImportJobSourceItemTypeDef
 ):
     pass
 
 
+_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+    {
+        "referenceStoreId": str,
+    },
+)
+_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+    {
+        "filter": ImportReferenceFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef(
+    _RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+    _OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListReferenceImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReferenceImportJobsRequestRequestTypeDef",
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferenceImportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReferenceImportJobsRequestRequestTypeDef",
     {
-        "filter": ImportReferenceFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ImportReferenceFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReferenceImportJobsRequestRequestTypeDef(
     _RequiredListReferenceImportJobsRequestRequestTypeDef,
@@ -2628,217 +3039,142 @@
 ):
     pass
 
 
 ListReferenceImportJobsResponseTypeDef = TypedDict(
     "ListReferenceImportJobsResponseTypeDef",
     {
-        "importJobs": List[ImportReferenceJobItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "importJobs": List[ImportReferenceJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAnnotationImportJobsRequestRequestTypeDef = TypedDict(
-    "ListAnnotationImportJobsRequestRequestTypeDef",
+ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef = TypedDict(
+    "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
     {
-        "filter": ListAnnotationImportJobsFilterTypeDef,
         "ids": Sequence[str],
-        "maxResults": int,
-        "nextToken": str,
+        "filter": ListAnnotationImportJobsFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef = TypedDict(
-    "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
+ListAnnotationImportJobsRequestRequestTypeDef = TypedDict(
+    "ListAnnotationImportJobsRequestRequestTypeDef",
     {
-        "filter": ListAnnotationImportJobsFilterTypeDef,
+        "maxResults": int,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "filter": ListAnnotationImportJobsFilterTypeDef,
     },
     total=False,
 )
 
-_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef = TypedDict(
+    "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
     {
-        "filter": ActivateReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ids": Sequence[str],
+        "filter": ListAnnotationStoresFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef(
-    _RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-    _OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+ListAnnotationStoresRequestRequestTypeDef = TypedDict(
+    "ListAnnotationStoresRequestRequestTypeDef",
     {
-        "filter": ExportReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ids": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+        "filter": ListAnnotationStoresFilterTypeDef,
     },
     total=False,
 )
 
-
-class ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef(
-    _RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-    _OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+ListMultipartReadSetUploadsResponseTypeDef = TypedDict(
+    "ListMultipartReadSetUploadsResponseTypeDef",
     {
-        "filter": ImportReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "uploads": List[MultipartReadSetUploadListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef(
-    _RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-    _OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+_RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
     {
-        "referenceStoreId": str,
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
     },
 )
-_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+_OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
     {
-        "filter": ImportReferenceFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ReadSetUploadPartListFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef(
-    _RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
-    _OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+class ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef(
+    _RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
+    _OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
 ):
     pass
 
 
-ListRunGroupsRequestListRunGroupsPaginateTypeDef = TypedDict(
-    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
+_RequiredListReadSetUploadPartsRequestRequestTypeDef = TypedDict(
+    "_RequiredListReadSetUploadPartsRequestRequestTypeDef",
     {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
-    "_RequiredListRunTasksRequestListRunTasksPaginateTypeDef",
-    {
-        "id": str,
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
     },
 )
-_OptionalListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
-    "_OptionalListRunTasksRequestListRunTasksPaginateTypeDef",
+_OptionalListReadSetUploadPartsRequestRequestTypeDef = TypedDict(
+    "_OptionalListReadSetUploadPartsRequestRequestTypeDef",
     {
-        "status": TaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+        "filter": ReadSetUploadPartListFilterTypeDef,
     },
     total=False,
 )
 
 
-class ListRunTasksRequestListRunTasksPaginateTypeDef(
-    _RequiredListRunTasksRequestListRunTasksPaginateTypeDef,
-    _OptionalListRunTasksRequestListRunTasksPaginateTypeDef,
+class ListReadSetUploadPartsRequestRequestTypeDef(
+    _RequiredListReadSetUploadPartsRequestRequestTypeDef,
+    _OptionalListReadSetUploadPartsRequestRequestTypeDef,
 ):
     pass
 
 
-ListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "ListRunsRequestListRunsPaginateTypeDef",
+ListReadSetUploadPartsResponseTypeDef = TypedDict(
+    "ListReadSetUploadPartsResponseTypeDef",
     {
-        "name": str,
-        "runGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "name": str,
-        "type": Literal["PRIVATE"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef = TypedDict(
-    "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
-    {
-        "filter": ListAnnotationStoresFilterTypeDef,
-        "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAnnotationStoresRequestRequestTypeDef = TypedDict(
-    "ListAnnotationStoresRequestRequestTypeDef",
-    {
-        "filter": ListAnnotationStoresFilterTypeDef,
-        "ids": Sequence[str],
-        "maxResults": int,
         "nextToken": str,
+        "parts": List[ReadSetUploadPartListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredListReadSetsRequestListReadSetsPaginateTypeDef = TypedDict(
     "_RequiredListReadSetsRequestListReadSetsPaginateTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetsRequestListReadSetsPaginateTypeDef = TypedDict(
     "_OptionalListReadSetsRequestListReadSetsPaginateTypeDef",
     {
         "filter": ReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListReadSetsRequestListReadSetsPaginateTypeDef(
     _RequiredListReadSetsRequestListReadSetsPaginateTypeDef,
@@ -2852,17 +3188,17 @@
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetsRequestRequestTypeDef",
     {
-        "filter": ReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReadSetFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReadSetsRequestRequestTypeDef(
     _RequiredListReadSetsRequestRequestTypeDef, _OptionalListReadSetsRequestRequestTypeDef
@@ -2870,40 +3206,40 @@
     pass
 
 
 ListReferenceStoresRequestListReferenceStoresPaginateTypeDef = TypedDict(
     "ListReferenceStoresRequestListReferenceStoresPaginateTypeDef",
     {
         "filter": ReferenceStoreFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReferenceStoresRequestRequestTypeDef = TypedDict(
     "ListReferenceStoresRequestRequestTypeDef",
     {
-        "filter": ReferenceStoreFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReferenceStoreFilterTypeDef,
     },
     total=False,
 )
 
 _RequiredListReferencesRequestListReferencesPaginateTypeDef = TypedDict(
     "_RequiredListReferencesRequestListReferencesPaginateTypeDef",
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferencesRequestListReferencesPaginateTypeDef = TypedDict(
     "_OptionalListReferencesRequestListReferencesPaginateTypeDef",
     {
         "filter": ReferenceFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListReferencesRequestListReferencesPaginateTypeDef(
     _RequiredListReferencesRequestListReferencesPaginateTypeDef,
@@ -2917,17 +3253,17 @@
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferencesRequestRequestTypeDef = TypedDict(
     "_OptionalListReferencesRequestRequestTypeDef",
     {
-        "filter": ReferenceFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReferenceFilterTypeDef,
     },
     total=False,
 )
 
 
 class ListReferencesRequestRequestTypeDef(
     _RequiredListReferencesRequestRequestTypeDef, _OptionalListReferencesRequestRequestTypeDef
@@ -2936,121 +3272,121 @@
 
 
 ListReferencesResponseTypeDef = TypedDict(
     "ListReferencesResponseTypeDef",
     {
         "nextToken": str,
         "references": List[ReferenceListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunGroupsResponseTypeDef = TypedDict(
     "ListRunGroupsResponseTypeDef",
     {
         "items": List[RunGroupListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunTasksResponseTypeDef = TypedDict(
     "ListRunTasksResponseTypeDef",
     {
         "items": List[TaskListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunsResponseTypeDef = TypedDict(
     "ListRunsResponseTypeDef",
     {
         "items": List[RunListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSequenceStoresRequestListSequenceStoresPaginateTypeDef = TypedDict(
     "ListSequenceStoresRequestListSequenceStoresPaginateTypeDef",
     {
         "filter": SequenceStoreFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSequenceStoresRequestRequestTypeDef = TypedDict(
     "ListSequenceStoresRequestRequestTypeDef",
     {
-        "filter": SequenceStoreFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": SequenceStoreFilterTypeDef,
     },
     total=False,
 )
 
 ListVariantImportJobsRequestListVariantImportJobsPaginateTypeDef = TypedDict(
     "ListVariantImportJobsRequestListVariantImportJobsPaginateTypeDef",
     {
-        "filter": ListVariantImportJobsFilterTypeDef,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ListVariantImportJobsFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListVariantImportJobsRequestRequestTypeDef = TypedDict(
     "ListVariantImportJobsRequestRequestTypeDef",
     {
-        "filter": ListVariantImportJobsFilterTypeDef,
-        "ids": Sequence[str],
         "maxResults": int,
+        "ids": Sequence[str],
         "nextToken": str,
+        "filter": ListVariantImportJobsFilterTypeDef,
     },
     total=False,
 )
 
 ListVariantImportJobsResponseTypeDef = TypedDict(
     "ListVariantImportJobsResponseTypeDef",
     {
-        "nextToken": str,
         "variantImportJobs": List[VariantImportJobItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVariantStoresRequestListVariantStoresPaginateTypeDef = TypedDict(
     "ListVariantStoresRequestListVariantStoresPaginateTypeDef",
     {
-        "filter": ListVariantStoresFilterTypeDef,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ListVariantStoresFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListVariantStoresRequestRequestTypeDef = TypedDict(
     "ListVariantStoresRequestRequestTypeDef",
     {
-        "filter": ListVariantStoresFilterTypeDef,
-        "ids": Sequence[str],
         "maxResults": int,
+        "ids": Sequence[str],
         "nextToken": str,
+        "filter": ListVariantStoresFilterTypeDef,
     },
     total=False,
 )
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "items": List[WorkflowListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TsvOptionsTypeDef = TypedDict(
     "TsvOptionsTypeDef",
     {
         "readOptions": ReadOptionsTypeDef,
@@ -3105,22 +3441,23 @@
     pass
 
 
 _RequiredStartVariantImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartVariantImportRequestRequestTypeDef",
     {
         "destinationName": str,
-        "items": Sequence[VariantImportItemSourceTypeDef],
         "roleArn": str,
+        "items": Sequence[VariantImportItemSourceTypeDef],
     },
 )
 _OptionalStartVariantImportRequestRequestTypeDef = TypedDict(
     "_OptionalStartVariantImportRequestRequestTypeDef",
     {
         "runLeftNormalization": bool,
+        "annotationFields": Mapping[str, str],
     },
     total=False,
 )
 
 
 class StartVariantImportRequestRequestTypeDef(
     _RequiredStartVariantImportRequestRequestTypeDef,
@@ -3138,111 +3475,112 @@
 )
 
 ListAnnotationStoresResponseTypeDef = TypedDict(
     "ListAnnotationStoresResponseTypeDef",
     {
         "annotationStores": List[AnnotationStoreItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReferenceStoresResponseTypeDef = TypedDict(
     "ListReferenceStoresResponseTypeDef",
     {
         "nextToken": str,
         "referenceStores": List[ReferenceStoreDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSequenceStoresResponseTypeDef = TypedDict(
     "ListSequenceStoresResponseTypeDef",
     {
         "nextToken": str,
         "sequenceStores": List[SequenceStoreDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVariantStoresResponseTypeDef = TypedDict(
     "ListVariantStoresResponseTypeDef",
     {
-        "nextToken": str,
         "variantStores": List[VariantStoreItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetMetadataResponseTypeDef = TypedDict(
     "GetReadSetMetadataResponseTypeDef",
     {
+        "id": str,
         "arn": str,
-        "creationTime": datetime,
+        "sequenceStoreId": str,
+        "subjectId": str,
+        "sampleId": str,
+        "status": ReadSetStatusType,
+        "name": str,
         "description": str,
         "fileType": FileTypeType,
-        "files": ReadSetFilesTypeDef,
-        "id": str,
-        "name": str,
-        "referenceArn": str,
-        "sampleId": str,
+        "creationTime": datetime,
         "sequenceInformation": SequenceInformationTypeDef,
-        "sequenceStoreId": str,
-        "status": ReadSetStatusType,
-        "subjectId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "referenceArn": str,
+        "files": ReadSetFilesTypeDef,
+        "statusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReferenceMetadataResponseTypeDef = TypedDict(
     "GetReferenceMetadataResponseTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "files": ReferenceFilesTypeDef,
         "id": str,
-        "md5": str,
-        "name": str,
+        "arn": str,
         "referenceStoreId": str,
+        "md5": str,
         "status": ReferenceStatusType,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "files": ReferenceFilesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReadSetsResponseTypeDef = TypedDict(
     "ListReadSetsResponseTypeDef",
     {
         "nextToken": str,
         "readSets": List[ReadSetListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetImportJobResponseTypeDef = TypedDict(
     "GetReadSetImportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
         "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
-        "sources": List[ImportReadSetSourceItemTypeDef],
+        "roleArn": str,
         "status": ReadSetImportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "sources": List[ImportReadSetSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReadSetImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartReadSetImportJobRequestRequestTypeDef",
     {
-        "roleArn": str,
         "sequenceStoreId": str,
+        "roleArn": str,
         "sources": Sequence[StartReadSetImportJobSourceItemTypeDef],
     },
 )
 _OptionalStartReadSetImportJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartReadSetImportJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -3272,20 +3610,20 @@
     {
         "storeFormat": StoreFormatType,
     },
 )
 _OptionalCreateAnnotationStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAnnotationStoreRequestRequestTypeDef",
     {
-        "description": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
+        "name": str,
+        "description": str,
+        "tags": Mapping[str, str],
         "sseConfig": SseConfigTypeDef,
         "storeOptions": StoreOptionsTypeDef,
-        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateAnnotationStoreRequestRequestTypeDef(
     _RequiredCreateAnnotationStoreRequestRequestTypeDef,
@@ -3293,93 +3631,95 @@
 ):
     pass
 
 
 CreateAnnotationStoreResponseTypeDef = TypedDict(
     "CreateAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
         "storeFormat": StoreFormatType,
         "storeOptions": StoreOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": StoreStatusType,
+        "name": str,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnnotationStoreResponseTypeDef = TypedDict(
     "GetAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
-        "storeFormat": StoreFormatType,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "updateTime": datetime,
+        "tags": Dict[str, str],
         "storeOptions": StoreOptionsTypeDef,
+        "storeFormat": StoreFormatType,
+        "statusMessage": str,
         "storeSizeBytes": int,
-        "tags": Dict[str, str],
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAnnotationStoreResponseTypeDef = TypedDict(
     "UpdateAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
         "status": StoreStatusType,
-        "storeFormat": StoreFormatType,
-        "storeOptions": StoreOptionsTypeDef,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "storeOptions": StoreOptionsTypeDef,
+        "storeFormat": StoreFormatType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnnotationImportResponseTypeDef = TypedDict(
     "GetAnnotationImportResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destinationName": str,
-        "formatOptions": FormatOptionsTypeDef,
         "id": str,
-        "items": List[AnnotationImportItemDetailTypeDef],
+        "destinationName": str,
         "roleArn": str,
-        "runLeftNormalization": bool,
         "status": JobStatusType,
         "statusMessage": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "completionTime": datetime,
+        "items": List[AnnotationImportItemDetailTypeDef],
+        "runLeftNormalization": bool,
+        "formatOptions": FormatOptionsTypeDef,
+        "annotationFields": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartAnnotationImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartAnnotationImportRequestRequestTypeDef",
     {
         "destinationName": str,
-        "items": Sequence[AnnotationImportItemSourceTypeDef],
         "roleArn": str,
+        "items": Sequence[AnnotationImportItemSourceTypeDef],
     },
 )
 _OptionalStartAnnotationImportRequestRequestTypeDef = TypedDict(
     "_OptionalStartAnnotationImportRequestRequestTypeDef",
     {
         "formatOptions": FormatOptionsTypeDef,
         "runLeftNormalization": bool,
+        "annotationFields": Mapping[str, str],
     },
     total=False,
 )
 
 
 class StartAnnotationImportRequestRequestTypeDef(
     _RequiredStartAnnotationImportRequestRequestTypeDef,
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/type_defs.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for omics service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_omics.type_defs import ActivateReadSetFilterTypeDef
+    from types_aiobotocore_omics.type_defs import AbortMultipartReadSetUploadRequestRequestTypeDef
 
-    data: ActivateReadSetFilterTypeDef = {...}
+    data: AbortMultipartReadSetUploadRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -25,63 +25,74 @@
     ReadSetActivationJobItemStatusType,
     ReadSetActivationJobStatusType,
     ReadSetExportJobItemStatusType,
     ReadSetExportJobStatusType,
     ReadSetFileType,
     ReadSetImportJobItemStatusType,
     ReadSetImportJobStatusType,
+    ReadSetPartSourceType,
     ReadSetStatusType,
     ReferenceFileType,
     ReferenceImportJobItemStatusType,
     ReferenceImportJobStatusType,
     ReferenceStatusType,
     RunLogLevelType,
     RunStatusType,
     SchemaValueTypeType,
     StoreFormatType,
     StoreStatusType,
     TaskStatusType,
     WorkflowEngineType,
     WorkflowStatusType,
+    WorkflowTypeType,
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
+    "AbortMultipartReadSetUploadRequestRequestTypeDef",
     "ActivateReadSetFilterTypeDef",
     "ActivateReadSetJobItemTypeDef",
     "ActivateReadSetSourceItemTypeDef",
     "AnnotationImportItemDetailTypeDef",
     "AnnotationImportItemSourceTypeDef",
     "AnnotationImportJobItemTypeDef",
     "ReferenceItemTypeDef",
     "SseConfigTypeDef",
     "BatchDeleteReadSetRequestRequestTypeDef",
     "ReadSetBatchErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "CancelAnnotationImportRequestRequestTypeDef",
     "CancelRunRequestRequestTypeDef",
     "CancelVariantImportRequestRequestTypeDef",
+    "CompleteReadSetUploadPartListItemTypeDef",
+    "CompleteMultipartReadSetUploadResponseTypeDef",
+    "CreateMultipartReadSetUploadRequestRequestTypeDef",
+    "CreateMultipartReadSetUploadResponseTypeDef",
     "CreateRunGroupRequestRequestTypeDef",
+    "CreateRunGroupResponseTypeDef",
     "WorkflowParameterTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "DeleteAnnotationStoreRequestRequestTypeDef",
+    "DeleteAnnotationStoreResponseTypeDef",
     "DeleteReferenceRequestRequestTypeDef",
     "DeleteReferenceStoreRequestRequestTypeDef",
     "DeleteRunGroupRequestRequestTypeDef",
     "DeleteRunRequestRequestTypeDef",
     "DeleteSequenceStoreRequestRequestTypeDef",
     "DeleteVariantStoreRequestRequestTypeDef",
+    "DeleteVariantStoreResponseTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportReadSetDetailTypeDef",
     "ExportReadSetFilterTypeDef",
     "ExportReadSetJobDetailTypeDef",
     "ExportReadSetTypeDef",
     "FileInformationTypeDef",
     "VcfOptionsTypeDef",
     "WaiterConfigTypeDef",
@@ -89,104 +100,114 @@
     "GetAnnotationStoreRequestRequestTypeDef",
     "GetReadSetActivationJobRequestRequestTypeDef",
     "GetReadSetExportJobRequestRequestTypeDef",
     "GetReadSetImportJobRequestRequestTypeDef",
     "GetReadSetMetadataRequestRequestTypeDef",
     "SequenceInformationTypeDef",
     "GetReadSetRequestRequestTypeDef",
+    "GetReadSetResponseTypeDef",
     "GetReferenceImportJobRequestRequestTypeDef",
     "ImportReferenceSourceItemTypeDef",
     "GetReferenceMetadataRequestRequestTypeDef",
     "GetReferenceRequestRequestTypeDef",
+    "GetReferenceResponseTypeDef",
     "GetReferenceStoreRequestRequestTypeDef",
     "GetRunGroupRequestRequestTypeDef",
+    "GetRunGroupResponseTypeDef",
     "GetRunRequestRequestTypeDef",
+    "GetRunResponseTypeDef",
     "GetRunTaskRequestRequestTypeDef",
+    "GetRunTaskResponseTypeDef",
     "GetSequenceStoreRequestRequestTypeDef",
     "GetVariantImportRequestRequestTypeDef",
     "VariantImportItemDetailTypeDef",
     "GetVariantStoreRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "ImportReadSetFilterTypeDef",
     "ImportReadSetJobItemTypeDef",
     "SourceFilesTypeDef",
     "ImportReferenceFilterTypeDef",
     "ImportReferenceJobItemTypeDef",
     "ListAnnotationImportJobsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListAnnotationStoresFilterTypeDef",
+    "ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
+    "ListMultipartReadSetUploadsRequestRequestTypeDef",
+    "MultipartReadSetUploadListItemTypeDef",
+    "ReadSetUploadPartListFilterTypeDef",
+    "ReadSetUploadPartListItemTypeDef",
     "ReadSetFilterTypeDef",
     "ReferenceStoreFilterTypeDef",
     "ReferenceFilterTypeDef",
     "ReferenceListItemTypeDef",
+    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
     "ListRunGroupsRequestRequestTypeDef",
     "RunGroupListItemTypeDef",
+    "ListRunTasksRequestListRunTasksPaginateTypeDef",
     "ListRunTasksRequestRequestTypeDef",
     "TaskListItemTypeDef",
+    "ListRunsRequestListRunsPaginateTypeDef",
     "ListRunsRequestRequestTypeDef",
     "RunListItemTypeDef",
     "SequenceStoreFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListVariantImportJobsFilterTypeDef",
     "VariantImportJobItemTypeDef",
     "ListVariantStoresFilterTypeDef",
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "WorkflowListItemTypeDef",
+    "PaginatorConfigTypeDef",
     "ReadOptionsTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartAnnotationImportResponseTypeDef",
     "StartReadSetActivationJobSourceItemTypeDef",
+    "StartReadSetActivationJobResponseTypeDef",
+    "StartReadSetExportJobResponseTypeDef",
+    "StartReadSetImportJobResponseTypeDef",
     "StartReferenceImportJobSourceItemTypeDef",
+    "StartReferenceImportJobResponseTypeDef",
     "StartRunRequestRequestTypeDef",
+    "StartRunResponseTypeDef",
     "VariantImportItemSourceTypeDef",
+    "StartVariantImportResponseTypeDef",
     "TsvStoreOptionsTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAnnotationStoreRequestRequestTypeDef",
     "UpdateRunGroupRequestRequestTypeDef",
     "UpdateVariantStoreRequestRequestTypeDef",
     "UpdateWorkflowRequestRequestTypeDef",
+    "UploadReadSetPartRequestRequestTypeDef",
+    "UploadReadSetPartResponseTypeDef",
+    "ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
     "ListReadSetActivationJobsRequestRequestTypeDef",
+    "ListReadSetActivationJobsResponseTypeDef",
+    "GetReadSetActivationJobResponseTypeDef",
+    "ListAnnotationImportJobsResponseTypeDef",
+    "CreateVariantStoreResponseTypeDef",
+    "UpdateVariantStoreResponseTypeDef",
     "AnnotationStoreItemTypeDef",
     "CreateReferenceStoreRequestRequestTypeDef",
+    "CreateReferenceStoreResponseTypeDef",
     "CreateSequenceStoreRequestRequestTypeDef",
+    "CreateSequenceStoreResponseTypeDef",
     "CreateVariantStoreRequestRequestTypeDef",
+    "GetReferenceStoreResponseTypeDef",
+    "GetSequenceStoreResponseTypeDef",
+    "GetVariantStoreResponseTypeDef",
     "ReferenceStoreDetailTypeDef",
     "SequenceStoreDetailTypeDef",
     "VariantStoreItemTypeDef",
     "BatchDeleteReadSetResponseTypeDef",
-    "CreateReferenceStoreResponseTypeDef",
-    "CreateRunGroupResponseTypeDef",
-    "CreateSequenceStoreResponseTypeDef",
-    "CreateVariantStoreResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "DeleteAnnotationStoreResponseTypeDef",
-    "DeleteVariantStoreResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetReadSetActivationJobResponseTypeDef",
-    "GetReadSetResponseTypeDef",
-    "GetReferenceResponseTypeDef",
-    "GetReferenceStoreResponseTypeDef",
-    "GetRunGroupResponseTypeDef",
-    "GetRunResponseTypeDef",
-    "GetRunTaskResponseTypeDef",
-    "GetSequenceStoreResponseTypeDef",
-    "GetVariantStoreResponseTypeDef",
-    "ListAnnotationImportJobsResponseTypeDef",
-    "ListReadSetActivationJobsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartAnnotationImportResponseTypeDef",
-    "StartReadSetActivationJobResponseTypeDef",
-    "StartReadSetExportJobResponseTypeDef",
-    "StartReadSetImportJobResponseTypeDef",
-    "StartReferenceImportJobResponseTypeDef",
-    "StartRunResponseTypeDef",
-    "StartVariantImportResponseTypeDef",
-    "UpdateVariantStoreResponseTypeDef",
+    "CompleteMultipartReadSetUploadRequestRequestTypeDef",
     "CreateWorkflowRequestRequestTypeDef",
     "GetWorkflowResponseTypeDef",
     "GetReadSetExportJobResponseTypeDef",
+    "ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
     "ListReadSetExportJobsRequestRequestTypeDef",
     "ListReadSetExportJobsResponseTypeDef",
     "StartReadSetExportJobRequestRequestTypeDef",
     "ReadSetFilesTypeDef",
     "ReferenceFilesTypeDef",
     "GetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef",
     "GetAnnotationStoreRequestAnnotationStoreCreatedWaitTypeDef",
@@ -202,32 +223,30 @@
     "GetVariantImportRequestVariantImportJobCreatedWaitTypeDef",
     "GetVariantStoreRequestVariantStoreCreatedWaitTypeDef",
     "GetVariantStoreRequestVariantStoreDeletedWaitTypeDef",
     "GetWorkflowRequestWorkflowActiveWaitTypeDef",
     "ReadSetListItemTypeDef",
     "GetReferenceImportJobResponseTypeDef",
     "GetVariantImportResponseTypeDef",
+    "ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
     "ListReadSetImportJobsRequestRequestTypeDef",
     "ListReadSetImportJobsResponseTypeDef",
     "ImportReadSetSourceItemTypeDef",
     "StartReadSetImportJobSourceItemTypeDef",
+    "ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
     "ListReferenceImportJobsRequestRequestTypeDef",
     "ListReferenceImportJobsResponseTypeDef",
-    "ListAnnotationImportJobsRequestRequestTypeDef",
     "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
-    "ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
-    "ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
-    "ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
-    "ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
-    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
-    "ListRunTasksRequestListRunTasksPaginateTypeDef",
-    "ListRunsRequestListRunsPaginateTypeDef",
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    "ListAnnotationImportJobsRequestRequestTypeDef",
     "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
     "ListAnnotationStoresRequestRequestTypeDef",
+    "ListMultipartReadSetUploadsResponseTypeDef",
+    "ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
+    "ListReadSetUploadPartsRequestRequestTypeDef",
+    "ListReadSetUploadPartsResponseTypeDef",
     "ListReadSetsRequestListReadSetsPaginateTypeDef",
     "ListReadSetsRequestRequestTypeDef",
     "ListReferenceStoresRequestListReferenceStoresPaginateTypeDef",
     "ListReferenceStoresRequestRequestTypeDef",
     "ListReferencesRequestListReferencesPaginateTypeDef",
     "ListReferencesRequestRequestTypeDef",
     "ListReferencesResponseTypeDef",
@@ -261,31 +280,39 @@
     "CreateAnnotationStoreResponseTypeDef",
     "GetAnnotationStoreResponseTypeDef",
     "UpdateAnnotationStoreResponseTypeDef",
     "GetAnnotationImportResponseTypeDef",
     "StartAnnotationImportRequestRequestTypeDef",
 )
 
+AbortMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "AbortMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+    },
+)
+
 ActivateReadSetFilterTypeDef = TypedDict(
     "ActivateReadSetFilterTypeDef",
     {
+        "status": ReadSetActivationJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetActivationJobStatusType,
     },
     total=False,
 )
 
 _RequiredActivateReadSetJobItemTypeDef = TypedDict(
     "_RequiredActivateReadSetJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
         "sequenceStoreId": str,
         "status": ReadSetActivationJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalActivateReadSetJobItemTypeDef = TypedDict(
     "_OptionalActivateReadSetJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -316,42 +343,43 @@
     _RequiredActivateReadSetSourceItemTypeDef, _OptionalActivateReadSetSourceItemTypeDef
 ):
     pass
 
 AnnotationImportItemDetailTypeDef = TypedDict(
     "AnnotationImportItemDetailTypeDef",
     {
-        "jobStatus": JobStatusType,
         "source": str,
+        "jobStatus": JobStatusType,
     },
 )
 
 AnnotationImportItemSourceTypeDef = TypedDict(
     "AnnotationImportItemSourceTypeDef",
     {
         "source": str,
     },
 )
 
 _RequiredAnnotationImportJobItemTypeDef = TypedDict(
     "_RequiredAnnotationImportJobItemTypeDef",
     {
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
+        "destinationName": str,
         "roleArn": str,
         "status": JobStatusType,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalAnnotationImportJobItemTypeDef = TypedDict(
     "_OptionalAnnotationImportJobItemTypeDef",
     {
         "completionTime": datetime,
         "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
     },
     total=False,
 )
 
 class AnnotationImportJobItemTypeDef(
     _RequiredAnnotationImportJobItemTypeDef, _OptionalAnnotationImportJobItemTypeDef
 ):
@@ -389,31 +417,20 @@
         "sequenceStoreId": str,
     },
 )
 
 ReadSetBatchErrorTypeDef = TypedDict(
     "ReadSetBatchErrorTypeDef",
     {
-        "code": str,
         "id": str,
+        "code": str,
         "message": str,
     },
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
 CancelAnnotationImportRequestRequestTypeDef = TypedDict(
     "CancelAnnotationImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
@@ -427,46 +444,131 @@
 CancelVariantImportRequestRequestTypeDef = TypedDict(
     "CancelVariantImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
+CompleteReadSetUploadPartListItemTypeDef = TypedDict(
+    "CompleteReadSetUploadPartListItemTypeDef",
+    {
+        "partNumber": int,
+        "partSource": ReadSetPartSourceType,
+        "checksum": str,
+    },
+)
+
+CompleteMultipartReadSetUploadResponseTypeDef = TypedDict(
+    "CompleteMultipartReadSetUploadResponseTypeDef",
+    {
+        "readSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "referenceArn": str,
+        "name": str,
+    },
+)
+_OptionalCreateMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateMultipartReadSetUploadRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "generatedFrom": str,
+        "description": str,
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class CreateMultipartReadSetUploadRequestRequestTypeDef(
+    _RequiredCreateMultipartReadSetUploadRequestRequestTypeDef,
+    _OptionalCreateMultipartReadSetUploadRequestRequestTypeDef,
+):
+    pass
+
+CreateMultipartReadSetUploadResponseTypeDef = TypedDict(
+    "CreateMultipartReadSetUploadResponseTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "generatedFrom": str,
+        "referenceArn": str,
+        "name": str,
+        "description": str,
+        "tags": Dict[str, str],
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRunGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRunGroupRequestRequestTypeDef",
     {
         "requestId": str,
     },
 )
 _OptionalCreateRunGroupRequestRequestTypeDef = TypedDict(
     "_OptionalCreateRunGroupRequestRequestTypeDef",
     {
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
         "tags": Mapping[str, str],
+        "maxGpus": int,
     },
     total=False,
 )
 
 class CreateRunGroupRequestRequestTypeDef(
     _RequiredCreateRunGroupRequestRequestTypeDef, _OptionalCreateRunGroupRequestRequestTypeDef
 ):
     pass
 
+CreateRunGroupResponseTypeDef = TypedDict(
+    "CreateRunGroupResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowParameterTypeDef = TypedDict(
     "WorkflowParameterTypeDef",
     {
         "description": str,
         "optional": bool,
     },
     total=False,
 )
 
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": WorkflowStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAnnotationStoreRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAnnotationStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalDeleteAnnotationStoreRequestRequestTypeDef = TypedDict(
@@ -479,14 +581,22 @@
 
 class DeleteAnnotationStoreRequestRequestTypeDef(
     _RequiredDeleteAnnotationStoreRequestRequestTypeDef,
     _OptionalDeleteAnnotationStoreRequestRequestTypeDef,
 ):
     pass
 
+DeleteAnnotationStoreResponseTypeDef = TypedDict(
+    "DeleteAnnotationStoreResponseTypeDef",
+    {
+        "status": StoreStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteReferenceRequestRequestTypeDef = TypedDict(
     "DeleteReferenceRequestRequestTypeDef",
     {
         "id": str,
         "referenceStoreId": str,
     },
 )
@@ -535,21 +645,36 @@
 
 class DeleteVariantStoreRequestRequestTypeDef(
     _RequiredDeleteVariantStoreRequestRequestTypeDef,
     _OptionalDeleteVariantStoreRequestRequestTypeDef,
 ):
     pass
 
+DeleteVariantStoreResponseTypeDef = TypedDict(
+    "DeleteVariantStoreResponseTypeDef",
+    {
+        "status": StoreStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExportReadSetDetailTypeDef = TypedDict(
     "_RequiredExportReadSetDetailTypeDef",
     {
         "id": str,
         "status": ReadSetExportJobItemStatusType,
     },
 )
@@ -565,29 +690,29 @@
     _RequiredExportReadSetDetailTypeDef, _OptionalExportReadSetDetailTypeDef
 ):
     pass
 
 ExportReadSetFilterTypeDef = TypedDict(
     "ExportReadSetFilterTypeDef",
     {
+        "status": ReadSetExportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetExportJobStatusType,
     },
     total=False,
 )
 
 _RequiredExportReadSetJobDetailTypeDef = TypedDict(
     "_RequiredExportReadSetJobDetailTypeDef",
     {
-        "creationTime": datetime,
-        "destination": str,
         "id": str,
         "sequenceStoreId": str,
+        "destination": str,
         "status": ReadSetExportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalExportReadSetJobDetailTypeDef = TypedDict(
     "_OptionalExportReadSetJobDetailTypeDef",
     {
         "completionTime": datetime,
     },
@@ -605,26 +730,26 @@
         "readSetId": str,
     },
 )
 
 FileInformationTypeDef = TypedDict(
     "FileInformationTypeDef",
     {
-        "contentLength": int,
-        "partSize": int,
         "totalParts": int,
+        "partSize": int,
+        "contentLength": int,
     },
     total=False,
 )
 
 VcfOptionsTypeDef = TypedDict(
     "VcfOptionsTypeDef",
     {
-        "ignoreFilterField": bool,
         "ignoreQualField": bool,
+        "ignoreFilterField": bool,
     },
     total=False,
 )
 
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
@@ -655,16 +780,16 @@
         "sequenceStoreId": str,
     },
 )
 
 GetReadSetExportJobRequestRequestTypeDef = TypedDict(
     "GetReadSetExportJobRequestRequestTypeDef",
     {
-        "id": str,
         "sequenceStoreId": str,
+        "id": str,
     },
 )
 
 GetReadSetImportJobRequestRequestTypeDef = TypedDict(
     "GetReadSetImportJobRequestRequestTypeDef",
     {
         "id": str,
@@ -679,28 +804,28 @@
         "sequenceStoreId": str,
     },
 )
 
 SequenceInformationTypeDef = TypedDict(
     "SequenceInformationTypeDef",
     {
-        "alignment": str,
-        "generatedFrom": str,
-        "totalBaseCount": int,
         "totalReadCount": int,
+        "totalBaseCount": int,
+        "generatedFrom": str,
+        "alignment": str,
     },
     total=False,
 )
 
 _RequiredGetReadSetRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadSetRequestRequestTypeDef",
     {
         "id": str,
-        "partNumber": int,
         "sequenceStoreId": str,
+        "partNumber": int,
     },
 )
 _OptionalGetReadSetRequestRequestTypeDef = TypedDict(
     "_OptionalGetReadSetRequestRequestTypeDef",
     {
         "file": ReadSetFileType,
     },
@@ -708,14 +833,22 @@
 )
 
 class GetReadSetRequestRequestTypeDef(
     _RequiredGetReadSetRequestRequestTypeDef, _OptionalGetReadSetRequestRequestTypeDef
 ):
     pass
 
+GetReadSetResponseTypeDef = TypedDict(
+    "GetReadSetResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReferenceImportJobRequestRequestTypeDef = TypedDict(
     "GetReferenceImportJobRequestRequestTypeDef",
     {
         "id": str,
         "referenceStoreId": str,
     },
 )
@@ -725,18 +858,18 @@
     {
         "status": ReferenceImportJobItemStatusType,
     },
 )
 _OptionalImportReferenceSourceItemTypeDef = TypedDict(
     "_OptionalImportReferenceSourceItemTypeDef",
     {
-        "description": str,
-        "name": str,
         "sourceFile": str,
         "statusMessage": str,
+        "name": str,
+        "description": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
 class ImportReferenceSourceItemTypeDef(
     _RequiredImportReferenceSourceItemTypeDef, _OptionalImportReferenceSourceItemTypeDef
@@ -751,46 +884,70 @@
     },
 )
 
 _RequiredGetReferenceRequestRequestTypeDef = TypedDict(
     "_RequiredGetReferenceRequestRequestTypeDef",
     {
         "id": str,
-        "partNumber": int,
         "referenceStoreId": str,
+        "partNumber": int,
     },
 )
 _OptionalGetReferenceRequestRequestTypeDef = TypedDict(
     "_OptionalGetReferenceRequestRequestTypeDef",
     {
-        "file": ReferenceFileType,
         "range": str,
+        "file": ReferenceFileType,
     },
     total=False,
 )
 
 class GetReferenceRequestRequestTypeDef(
     _RequiredGetReferenceRequestRequestTypeDef, _OptionalGetReferenceRequestRequestTypeDef
 ):
     pass
 
+GetReferenceResponseTypeDef = TypedDict(
+    "GetReferenceResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReferenceStoreRequestRequestTypeDef = TypedDict(
     "GetReferenceStoreRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
 GetRunGroupRequestRequestTypeDef = TypedDict(
     "GetRunGroupRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetRunGroupResponseTypeDef = TypedDict(
+    "GetRunGroupResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "maxCpus": int,
+        "maxRuns": int,
+        "maxDuration": int,
+        "creationTime": datetime,
+        "tags": Dict[str, str],
+        "maxGpus": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRunRequestRequestTypeDef = TypedDict(
     "_RequiredGetRunRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetRunRequestRequestTypeDef = TypedDict(
@@ -802,44 +959,105 @@
 )
 
 class GetRunRequestRequestTypeDef(
     _RequiredGetRunRequestRequestTypeDef, _OptionalGetRunRequestRequestTypeDef
 ):
     pass
 
+GetRunResponseTypeDef = TypedDict(
+    "GetRunResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": RunStatusType,
+        "workflowId": str,
+        "workflowType": WorkflowTypeType,
+        "runId": str,
+        "roleArn": str,
+        "name": str,
+        "runGroupId": str,
+        "priority": int,
+        "definition": str,
+        "digest": str,
+        "parameters": Dict[str, Any],
+        "storageCapacity": int,
+        "outputUri": str,
+        "logLevel": RunLogLevelType,
+        "resourceDigests": Dict[str, str],
+        "startedBy": str,
+        "creationTime": datetime,
+        "startTime": datetime,
+        "stopTime": datetime,
+        "statusMessage": str,
+        "tags": Dict[str, str],
+        "accelerators": Literal["GPU"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRunTaskRequestRequestTypeDef = TypedDict(
     "GetRunTaskRequestRequestTypeDef",
     {
         "id": str,
         "taskId": str,
     },
 )
 
+GetRunTaskResponseTypeDef = TypedDict(
+    "GetRunTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "status": TaskStatusType,
+        "name": str,
+        "cpus": int,
+        "memory": int,
+        "creationTime": datetime,
+        "startTime": datetime,
+        "stopTime": datetime,
+        "statusMessage": str,
+        "logStream": str,
+        "gpus": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSequenceStoreRequestRequestTypeDef = TypedDict(
     "GetSequenceStoreRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
 GetVariantImportRequestRequestTypeDef = TypedDict(
     "GetVariantImportRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
-VariantImportItemDetailTypeDef = TypedDict(
-    "VariantImportItemDetailTypeDef",
+_RequiredVariantImportItemDetailTypeDef = TypedDict(
+    "_RequiredVariantImportItemDetailTypeDef",
     {
-        "jobStatus": JobStatusType,
         "source": str,
+        "jobStatus": JobStatusType,
+    },
+)
+_OptionalVariantImportItemDetailTypeDef = TypedDict(
+    "_OptionalVariantImportItemDetailTypeDef",
+    {
+        "statusMessage": str,
     },
+    total=False,
 )
 
+class VariantImportItemDetailTypeDef(
+    _RequiredVariantImportItemDetailTypeDef, _OptionalVariantImportItemDetailTypeDef
+):
+    pass
+
 GetVariantStoreRequestRequestTypeDef = TypedDict(
     "GetVariantStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
@@ -848,43 +1066,43 @@
     {
         "id": str,
     },
 )
 _OptionalGetWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalGetWorkflowRequestRequestTypeDef",
     {
+        "type": WorkflowTypeType,
         "export": Sequence[Literal["DEFINITION"]],
-        "type": Literal["PRIVATE"],
     },
     total=False,
 )
 
 class GetWorkflowRequestRequestTypeDef(
     _RequiredGetWorkflowRequestRequestTypeDef, _OptionalGetWorkflowRequestRequestTypeDef
 ):
     pass
 
 ImportReadSetFilterTypeDef = TypedDict(
     "ImportReadSetFilterTypeDef",
     {
+        "status": ReadSetImportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReadSetImportJobStatusType,
     },
     total=False,
 )
 
 _RequiredImportReadSetJobItemTypeDef = TypedDict(
     "_RequiredImportReadSetJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
+        "roleArn": str,
         "status": ReadSetImportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalImportReadSetJobItemTypeDef = TypedDict(
     "_OptionalImportReadSetJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -912,29 +1130,29 @@
 
 class SourceFilesTypeDef(_RequiredSourceFilesTypeDef, _OptionalSourceFilesTypeDef):
     pass
 
 ImportReferenceFilterTypeDef = TypedDict(
     "ImportReferenceFilterTypeDef",
     {
+        "status": ReferenceImportJobStatusType,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "status": ReferenceImportJobStatusType,
     },
     total=False,
 )
 
 _RequiredImportReferenceJobItemTypeDef = TypedDict(
     "_RequiredImportReferenceJobItemTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
         "referenceStoreId": str,
         "roleArn": str,
         "status": ReferenceImportJobStatusType,
+        "creationTime": datetime,
     },
 )
 _OptionalImportReferenceJobItemTypeDef = TypedDict(
     "_OptionalImportReferenceJobItemTypeDef",
     {
         "completionTime": datetime,
     },
@@ -951,221 +1169,368 @@
     {
         "status": JobStatusType,
         "storeName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAnnotationStoresFilterTypeDef = TypedDict(
+    "ListAnnotationStoresFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "status": StoreStatusType,
     },
     total=False,
 )
 
-ListAnnotationStoresFilterTypeDef = TypedDict(
-    "ListAnnotationStoresFilterTypeDef",
+_RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
     {
-        "status": StoreStatusType,
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ReadSetFilterTypeDef = TypedDict(
-    "ReadSetFilterTypeDef",
+class ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef(
+    _RequiredListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+    _OptionalListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+):
+    pass
+
+_RequiredListMultipartReadSetUploadsRequestRequestTypeDef = TypedDict(
+    "_RequiredListMultipartReadSetUploadsRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListMultipartReadSetUploadsRequestRequestTypeDef = TypedDict(
+    "_OptionalListMultipartReadSetUploadsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListMultipartReadSetUploadsRequestRequestTypeDef(
+    _RequiredListMultipartReadSetUploadsRequestRequestTypeDef,
+    _OptionalListMultipartReadSetUploadsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredMultipartReadSetUploadListItemTypeDef = TypedDict(
+    "_RequiredMultipartReadSetUploadListItemTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "sourceFileType": FileTypeType,
+        "subjectId": str,
+        "sampleId": str,
+        "generatedFrom": str,
+        "referenceArn": str,
+        "creationTime": datetime,
+    },
+)
+_OptionalMultipartReadSetUploadListItemTypeDef = TypedDict(
+    "_OptionalMultipartReadSetUploadListItemTypeDef",
+    {
+        "name": str,
+        "description": str,
+        "tags": Dict[str, str],
+    },
+    total=False,
+)
+
+class MultipartReadSetUploadListItemTypeDef(
+    _RequiredMultipartReadSetUploadListItemTypeDef, _OptionalMultipartReadSetUploadListItemTypeDef
+):
+    pass
+
+ReadSetUploadPartListFilterTypeDef = TypedDict(
+    "ReadSetUploadPartListFilterTypeDef",
     {
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+_RequiredReadSetUploadPartListItemTypeDef = TypedDict(
+    "_RequiredReadSetUploadPartListItemTypeDef",
+    {
+        "partNumber": int,
+        "partSize": int,
+        "partSource": ReadSetPartSourceType,
+        "checksum": str,
+    },
+)
+_OptionalReadSetUploadPartListItemTypeDef = TypedDict(
+    "_OptionalReadSetUploadPartListItemTypeDef",
+    {
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+    },
+    total=False,
+)
+
+class ReadSetUploadPartListItemTypeDef(
+    _RequiredReadSetUploadPartListItemTypeDef, _OptionalReadSetUploadPartListItemTypeDef
+):
+    pass
+
+ReadSetFilterTypeDef = TypedDict(
+    "ReadSetFilterTypeDef",
+    {
         "name": str,
-        "referenceArn": str,
         "status": ReadSetStatusType,
+        "referenceArn": str,
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "sampleId": str,
+        "subjectId": str,
+        "generatedFrom": str,
     },
     total=False,
 )
 
 ReferenceStoreFilterTypeDef = TypedDict(
     "ReferenceStoreFilterTypeDef",
     {
+        "name": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "name": str,
     },
     total=False,
 )
 
 ReferenceFilterTypeDef = TypedDict(
     "ReferenceFilterTypeDef",
     {
+        "name": str,
+        "md5": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "md5": str,
-        "name": str,
     },
     total=False,
 )
 
 _RequiredReferenceListItemTypeDef = TypedDict(
     "_RequiredReferenceListItemTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
         "id": str,
-        "md5": str,
+        "arn": str,
         "referenceStoreId": str,
+        "md5": str,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalReferenceListItemTypeDef = TypedDict(
     "_OptionalReferenceListItemTypeDef",
     {
-        "description": str,
-        "name": str,
         "status": ReferenceStatusType,
+        "name": str,
+        "description": str,
     },
     total=False,
 )
 
 class ReferenceListItemTypeDef(
     _RequiredReferenceListItemTypeDef, _OptionalReferenceListItemTypeDef
 ):
     pass
 
+ListRunGroupsRequestListRunGroupsPaginateTypeDef = TypedDict(
+    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
+    {
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRunGroupsRequestRequestTypeDef = TypedDict(
     "ListRunGroupsRequestRequestTypeDef",
     {
-        "maxResults": int,
         "name": str,
         "startingToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
 RunGroupListItemTypeDef = TypedDict(
     "RunGroupListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
+        "creationTime": datetime,
+        "maxGpus": int,
+    },
+    total=False,
+)
+
+_RequiredListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
+    "_RequiredListRunTasksRequestListRunTasksPaginateTypeDef",
+    {
+        "id": str,
+    },
+)
+_OptionalListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
+    "_OptionalListRunTasksRequestListRunTasksPaginateTypeDef",
+    {
+        "status": TaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListRunTasksRequestListRunTasksPaginateTypeDef(
+    _RequiredListRunTasksRequestListRunTasksPaginateTypeDef,
+    _OptionalListRunTasksRequestListRunTasksPaginateTypeDef,
+):
+    pass
+
 _RequiredListRunTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListRunTasksRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalListRunTasksRequestRequestTypeDef = TypedDict(
     "_OptionalListRunTasksRequestRequestTypeDef",
     {
-        "maxResults": int,
-        "startingToken": str,
         "status": TaskStatusType,
+        "startingToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
 class ListRunTasksRequestRequestTypeDef(
     _RequiredListRunTasksRequestRequestTypeDef, _OptionalListRunTasksRequestRequestTypeDef
 ):
     pass
 
 TaskListItemTypeDef = TypedDict(
     "TaskListItemTypeDef",
     {
+        "taskId": str,
+        "status": TaskStatusType,
+        "name": str,
         "cpus": int,
-        "creationTime": datetime,
         "memory": int,
-        "name": str,
+        "creationTime": datetime,
         "startTime": datetime,
-        "status": TaskStatusType,
         "stopTime": datetime,
-        "taskId": str,
+        "gpus": int,
+    },
+    total=False,
+)
+
+ListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "ListRunsRequestListRunsPaginateTypeDef",
+    {
+        "name": str,
+        "runGroupId": str,
+        "status": RunStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRunsRequestRequestTypeDef = TypedDict(
     "ListRunsRequestRequestTypeDef",
     {
-        "maxResults": int,
         "name": str,
         "runGroupId": str,
         "startingToken": str,
+        "maxResults": int,
+        "status": RunStatusType,
     },
     total=False,
 )
 
 RunListItemTypeDef = TypedDict(
     "RunListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
         "id": str,
+        "status": RunStatusType,
+        "workflowId": str,
         "name": str,
         "priority": int,
+        "storageCapacity": int,
+        "creationTime": datetime,
         "startTime": datetime,
-        "status": RunStatusType,
         "stopTime": datetime,
-        "storageCapacity": int,
-        "workflowId": str,
     },
     total=False,
 )
 
 SequenceStoreFilterTypeDef = TypedDict(
     "SequenceStoreFilterTypeDef",
     {
+        "name": str,
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
-        "name": str,
     },
     total=False,
 )
 
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListVariantImportJobsFilterTypeDef = TypedDict(
     "ListVariantImportJobsFilterTypeDef",
     {
         "status": JobStatusType,
         "storeName": str,
     },
     total=False,
 )
 
 _RequiredVariantImportJobItemTypeDef = TypedDict(
     "_RequiredVariantImportJobItemTypeDef",
     {
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
+        "destinationName": str,
         "roleArn": str,
         "status": JobStatusType,
+        "creationTime": datetime,
         "updateTime": datetime,
     },
 )
 _OptionalVariantImportJobItemTypeDef = TypedDict(
     "_OptionalVariantImportJobItemTypeDef",
     {
         "completionTime": datetime,
         "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
     },
     total=False,
 )
 
 class VariantImportJobItemTypeDef(
     _RequiredVariantImportJobItemTypeDef, _OptionalVariantImportJobItemTypeDef
 ):
@@ -1175,67 +1540,142 @@
     "ListVariantStoresFilterTypeDef",
     {
         "status": StoreStatusType,
     },
     total=False,
 )
 
+ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "type": WorkflowTypeType,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
-        "maxResults": int,
+        "type": WorkflowTypeType,
         "name": str,
         "startingToken": str,
-        "type": Literal["PRIVATE"],
+        "maxResults": int,
     },
     total=False,
 )
 
 WorkflowListItemTypeDef = TypedDict(
     "WorkflowListItemTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
-        "digest": str,
         "id": str,
         "name": str,
         "status": WorkflowStatusType,
-        "type": Literal["PRIVATE"],
+        "type": WorkflowTypeType,
+        "digest": str,
+        "creationTime": datetime,
+        "metadata": Dict[str, str],
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
 
 ReadOptionsTypeDef = TypedDict(
     "ReadOptionsTypeDef",
     {
-        "comment": str,
+        "sep": str,
         "encoding": str,
+        "quote": str,
+        "quoteAll": bool,
         "escape": str,
         "escapeQuotes": bool,
+        "comment": str,
         "header": bool,
         "lineSep": str,
-        "quote": str,
-        "quoteAll": bool,
-        "sep": str,
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
+StartAnnotationImportResponseTypeDef = TypedDict(
+    "StartAnnotationImportResponseTypeDef",
+    {
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartReadSetActivationJobSourceItemTypeDef = TypedDict(
     "StartReadSetActivationJobSourceItemTypeDef",
     {
         "readSetId": str,
     },
 )
 
+StartReadSetActivationJobResponseTypeDef = TypedDict(
+    "StartReadSetActivationJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "status": ReadSetActivationJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartReadSetExportJobResponseTypeDef = TypedDict(
+    "StartReadSetExportJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "destination": str,
+        "status": ReadSetExportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartReadSetImportJobResponseTypeDef = TypedDict(
+    "StartReadSetImportJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "roleArn": str,
+        "status": ReadSetImportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartReferenceImportJobSourceItemTypeDef = TypedDict(
     "_RequiredStartReferenceImportJobSourceItemTypeDef",
     {
-        "name": str,
         "sourceFile": str,
+        "name": str,
     },
 )
 _OptionalStartReferenceImportJobSourceItemTypeDef = TypedDict(
     "_OptionalStartReferenceImportJobSourceItemTypeDef",
     {
         "description": str,
         "tags": Mapping[str, str],
@@ -1245,51 +1685,82 @@
 
 class StartReferenceImportJobSourceItemTypeDef(
     _RequiredStartReferenceImportJobSourceItemTypeDef,
     _OptionalStartReferenceImportJobSourceItemTypeDef,
 ):
     pass
 
+StartReferenceImportJobResponseTypeDef = TypedDict(
+    "StartReferenceImportJobResponseTypeDef",
+    {
+        "id": str,
+        "referenceStoreId": str,
+        "roleArn": str,
+        "status": ReferenceImportJobStatusType,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartRunRequestRequestTypeDef",
     {
-        "requestId": str,
         "roleArn": str,
+        "requestId": str,
     },
 )
 _OptionalStartRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartRunRequestRequestTypeDef",
     {
-        "logLevel": RunLogLevelType,
+        "workflowId": str,
+        "workflowType": WorkflowTypeType,
+        "runId": str,
         "name": str,
-        "outputUri": str,
-        "parameters": Mapping[str, Any],
-        "priority": int,
         "runGroupId": str,
-        "runId": str,
+        "priority": int,
+        "parameters": Mapping[str, Any],
         "storageCapacity": int,
+        "outputUri": str,
+        "logLevel": RunLogLevelType,
         "tags": Mapping[str, str],
-        "workflowId": str,
-        "workflowType": Literal["PRIVATE"],
     },
     total=False,
 )
 
 class StartRunRequestRequestTypeDef(
     _RequiredStartRunRequestRequestTypeDef, _OptionalStartRunRequestRequestTypeDef
 ):
     pass
 
+StartRunResponseTypeDef = TypedDict(
+    "StartRunResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "status": RunStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VariantImportItemSourceTypeDef = TypedDict(
     "VariantImportItemSourceTypeDef",
     {
         "source": str,
     },
 )
 
+StartVariantImportResponseTypeDef = TypedDict(
+    "StartVariantImportResponseTypeDef",
+    {
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TsvStoreOptionsTypeDef = TypedDict(
     "TsvStoreOptionsTypeDef",
     {
         "annotationType": AnnotationTypeType,
         "formatToHeader": Mapping[FormatToHeaderKeyType, str],
         "schema": Sequence[Mapping[str, SchemaValueTypeType]],
     },
@@ -1337,18 +1808,19 @@
     {
         "id": str,
     },
 )
 _OptionalUpdateRunGroupRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateRunGroupRequestRequestTypeDef",
     {
+        "name": str,
         "maxCpus": int,
-        "maxDuration": int,
         "maxRuns": int,
-        "name": str,
+        "maxDuration": int,
+        "maxGpus": int,
     },
     total=False,
 )
 
 class UpdateRunGroupRequestRequestTypeDef(
     _RequiredUpdateRunGroupRequestRequestTypeDef, _OptionalUpdateRunGroupRequestRequestTypeDef
 ):
@@ -1379,639 +1851,512 @@
     {
         "id": str,
     },
 )
 _OptionalUpdateWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateWorkflowRequestRequestTypeDef",
     {
-        "description": str,
         "name": str,
+        "description": str,
     },
     total=False,
 )
 
 class UpdateWorkflowRequestRequestTypeDef(
     _RequiredUpdateWorkflowRequestRequestTypeDef, _OptionalUpdateWorkflowRequestRequestTypeDef
 ):
     pass
 
+UploadReadSetPartRequestRequestTypeDef = TypedDict(
+    "UploadReadSetPartRequestRequestTypeDef",
+    {
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
+        "partNumber": int,
+        "payload": Union[str, bytes, IO[Any], StreamingBody],
+    },
+)
+
+UploadReadSetPartResponseTypeDef = TypedDict(
+    "UploadReadSetPartResponseTypeDef",
+    {
+        "checksum": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+    {
+        "filter": ActivateReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef(
+    _RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
+    _OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListReadSetActivationJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetActivationJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetActivationJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetActivationJobsRequestRequestTypeDef",
     {
-        "filter": ActivateReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ActivateReadSetFilterTypeDef,
     },
     total=False,
 )
 
 class ListReadSetActivationJobsRequestRequestTypeDef(
     _RequiredListReadSetActivationJobsRequestRequestTypeDef,
     _OptionalListReadSetActivationJobsRequestRequestTypeDef,
 ):
     pass
 
-AnnotationStoreItemTypeDef = TypedDict(
-    "AnnotationStoreItemTypeDef",
+ListReadSetActivationJobsResponseTypeDef = TypedDict(
+    "ListReadSetActivationJobsResponseTypeDef",
     {
+        "nextToken": str,
+        "activationJobs": List[ActivateReadSetJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetReadSetActivationJobResponseTypeDef = TypedDict(
+    "GetReadSetActivationJobResponseTypeDef",
+    {
+        "id": str,
+        "sequenceStoreId": str,
+        "status": ReadSetActivationJobStatusType,
+        "statusMessage": str,
         "creationTime": datetime,
-        "description": str,
+        "completionTime": datetime,
+        "sources": List[ActivateReadSetSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAnnotationImportJobsResponseTypeDef = TypedDict(
+    "ListAnnotationImportJobsResponseTypeDef",
+    {
+        "annotationImportJobs": List[AnnotationImportJobItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVariantStoreResponseTypeDef = TypedDict(
+    "CreateVariantStoreResponseTypeDef",
+    {
         "id": str,
+        "reference": ReferenceItemTypeDef,
+        "status": StoreStatusType,
         "name": str,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateVariantStoreResponseTypeDef = TypedDict(
+    "UpdateVariantStoreResponseTypeDef",
+    {
+        "id": str,
+        "reference": ReferenceItemTypeDef,
+        "status": StoreStatusType,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
+        "updateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AnnotationStoreItemTypeDef = TypedDict(
+    "AnnotationStoreItemTypeDef",
+    {
+        "id": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
+        "name": str,
         "storeFormat": StoreFormatType,
-        "storeSizeBytes": int,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
         "updateTime": datetime,
+        "statusMessage": str,
+        "storeSizeBytes": int,
     },
 )
 
 _RequiredCreateReferenceStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReferenceStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateReferenceStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateReferenceStoreRequestRequestTypeDef",
     {
-        "clientToken": str,
         "description": str,
         "sseConfig": SseConfigTypeDef,
         "tags": Mapping[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
 class CreateReferenceStoreRequestRequestTypeDef(
     _RequiredCreateReferenceStoreRequestRequestTypeDef,
     _OptionalCreateReferenceStoreRequestRequestTypeDef,
 ):
     pass
 
+CreateReferenceStoreResponseTypeDef = TypedDict(
+    "CreateReferenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSequenceStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSequenceStoreRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateSequenceStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSequenceStoreRequestRequestTypeDef",
     {
-        "clientToken": str,
         "description": str,
         "sseConfig": SseConfigTypeDef,
         "tags": Mapping[str, str],
+        "clientToken": str,
+        "fallbackLocation": str,
     },
     total=False,
 )
 
 class CreateSequenceStoreRequestRequestTypeDef(
     _RequiredCreateSequenceStoreRequestRequestTypeDef,
     _OptionalCreateSequenceStoreRequestRequestTypeDef,
 ):
     pass
 
+CreateSequenceStoreResponseTypeDef = TypedDict(
+    "CreateSequenceStoreResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "fallbackLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateVariantStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVariantStoreRequestRequestTypeDef",
     {
         "reference": ReferenceItemTypeDef,
     },
 )
 _OptionalCreateVariantStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVariantStoreRequestRequestTypeDef",
     {
-        "description": str,
         "name": str,
-        "sseConfig": SseConfigTypeDef,
+        "description": str,
         "tags": Mapping[str, str],
+        "sseConfig": SseConfigTypeDef,
     },
     total=False,
 )
 
 class CreateVariantStoreRequestRequestTypeDef(
     _RequiredCreateVariantStoreRequestRequestTypeDef,
     _OptionalCreateVariantStoreRequestRequestTypeDef,
 ):
     pass
 
-_RequiredReferenceStoreDetailTypeDef = TypedDict(
-    "_RequiredReferenceStoreDetailTypeDef",
+GetReferenceStoreResponseTypeDef = TypedDict(
+    "GetReferenceStoreResponseTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
         "id": str,
-    },
-)
-_OptionalReferenceStoreDetailTypeDef = TypedDict(
-    "_OptionalReferenceStoreDetailTypeDef",
-    {
-        "description": str,
+        "arn": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ReferenceStoreDetailTypeDef(
-    _RequiredReferenceStoreDetailTypeDef, _OptionalReferenceStoreDetailTypeDef
-):
-    pass
-
-_RequiredSequenceStoreDetailTypeDef = TypedDict(
-    "_RequiredSequenceStoreDetailTypeDef",
+GetSequenceStoreResponseTypeDef = TypedDict(
+    "GetSequenceStoreResponseTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
         "id": str,
-    },
-)
-_OptionalSequenceStoreDetailTypeDef = TypedDict(
-    "_OptionalSequenceStoreDetailTypeDef",
-    {
-        "description": str,
+        "arn": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "fallbackLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class SequenceStoreDetailTypeDef(
-    _RequiredSequenceStoreDetailTypeDef, _OptionalSequenceStoreDetailTypeDef
-):
-    pass
-
-VariantStoreItemTypeDef = TypedDict(
-    "VariantStoreItemTypeDef",
+GetVariantStoreResponseTypeDef = TypedDict(
+    "GetVariantStoreResponseTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
-        "storeSizeBytes": int,
-        "updateTime": datetime,
-    },
-)
-
-BatchDeleteReadSetResponseTypeDef = TypedDict(
-    "BatchDeleteReadSetResponseTypeDef",
-    {
-        "errors": List[ReadSetBatchErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReferenceStoreResponseTypeDef = TypedDict(
-    "CreateReferenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
         "name": str,
-        "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRunGroupResponseTypeDef = TypedDict(
-    "CreateRunGroupResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSequenceStoreResponseTypeDef = TypedDict(
-    "CreateSequenceStoreResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
         "description": str,
-        "id": str,
-        "name": str,
         "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVariantStoreResponseTypeDef = TypedDict(
-    "CreateVariantStoreResponseTypeDef",
-    {
         "creationTime": datetime,
-        "id": str,
-        "name": str,
-        "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "updateTime": datetime,
+        "tags": Dict[str, str],
+        "statusMessage": str,
+        "storeSizeBytes": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
+_RequiredReferenceStoreDetailTypeDef = TypedDict(
+    "_RequiredReferenceStoreDetailTypeDef",
     {
         "arn": str,
         "id": str,
-        "status": WorkflowStatusType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteAnnotationStoreResponseTypeDef = TypedDict(
-    "DeleteAnnotationStoreResponseTypeDef",
-    {
-        "status": StoreStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteVariantStoreResponseTypeDef = TypedDict(
-    "DeleteVariantStoreResponseTypeDef",
-    {
-        "status": StoreStatusType,
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
-GetReadSetActivationJobResponseTypeDef = TypedDict(
-    "GetReadSetActivationJobResponseTypeDef",
-    {
-        "completionTime": datetime,
         "creationTime": datetime,
-        "id": str,
-        "sequenceStoreId": str,
-        "sources": List[ActivateReadSetSourceItemTypeDef],
-        "status": ReadSetActivationJobStatusType,
-        "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-GetReadSetResponseTypeDef = TypedDict(
-    "GetReadSetResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReferenceResponseTypeDef = TypedDict(
-    "GetReferenceResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReferenceStoreResponseTypeDef = TypedDict(
-    "GetReferenceStoreResponseTypeDef",
+_OptionalReferenceStoreDetailTypeDef = TypedDict(
+    "_OptionalReferenceStoreDetailTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-GetRunGroupResponseTypeDef = TypedDict(
-    "GetRunGroupResponseTypeDef",
-    {
-        "arn": str,
-        "creationTime": datetime,
-        "id": str,
-        "maxCpus": int,
-        "maxDuration": int,
-        "maxRuns": int,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ReferenceStoreDetailTypeDef(
+    _RequiredReferenceStoreDetailTypeDef, _OptionalReferenceStoreDetailTypeDef
+):
+    pass
 
-GetRunResponseTypeDef = TypedDict(
-    "GetRunResponseTypeDef",
+_RequiredSequenceStoreDetailTypeDef = TypedDict(
+    "_RequiredSequenceStoreDetailTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
-        "definition": str,
-        "digest": str,
         "id": str,
-        "logLevel": RunLogLevelType,
-        "name": str,
-        "outputUri": str,
-        "parameters": Dict[str, Any],
-        "priority": int,
-        "resourceDigests": Dict[str, str],
-        "roleArn": str,
-        "runGroupId": str,
-        "runId": str,
-        "startTime": datetime,
-        "startedBy": str,
-        "status": RunStatusType,
-        "statusMessage": str,
-        "stopTime": datetime,
-        "storageCapacity": int,
-        "tags": Dict[str, str],
-        "workflowId": str,
-        "workflowType": Literal["PRIVATE"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRunTaskResponseTypeDef = TypedDict(
-    "GetRunTaskResponseTypeDef",
-    {
-        "cpus": int,
         "creationTime": datetime,
-        "logStream": str,
-        "memory": int,
-        "name": str,
-        "startTime": datetime,
-        "status": TaskStatusType,
-        "statusMessage": str,
-        "stopTime": datetime,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-GetSequenceStoreResponseTypeDef = TypedDict(
-    "GetSequenceStoreResponseTypeDef",
+_OptionalSequenceStoreDetailTypeDef = TypedDict(
+    "_OptionalSequenceStoreDetailTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
         "name": str,
+        "description": str,
         "sseConfig": SseConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "fallbackLocation": str,
     },
+    total=False,
 )
 
-GetVariantStoreResponseTypeDef = TypedDict(
-    "GetVariantStoreResponseTypeDef",
+class SequenceStoreDetailTypeDef(
+    _RequiredSequenceStoreDetailTypeDef, _OptionalSequenceStoreDetailTypeDef
+):
+    pass
+
+VariantStoreItemTypeDef = TypedDict(
+    "VariantStoreItemTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
-        "storeSizeBytes": int,
-        "tags": Dict[str, str],
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAnnotationImportJobsResponseTypeDef = TypedDict(
-    "ListAnnotationImportJobsResponseTypeDef",
-    {
-        "annotationImportJobs": List[AnnotationImportJobItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReadSetActivationJobsResponseTypeDef = TypedDict(
-    "ListReadSetActivationJobsResponseTypeDef",
-    {
-        "activationJobs": List[ActivateReadSetJobItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAnnotationImportResponseTypeDef = TypedDict(
-    "StartAnnotationImportResponseTypeDef",
-    {
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReadSetActivationJobResponseTypeDef = TypedDict(
-    "StartReadSetActivationJobResponseTypeDef",
-    {
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
         "creationTime": datetime,
-        "id": str,
-        "sequenceStoreId": str,
-        "status": ReadSetActivationJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "updateTime": datetime,
+        "statusMessage": str,
+        "storeSizeBytes": int,
     },
 )
 
-StartReadSetExportJobResponseTypeDef = TypedDict(
-    "StartReadSetExportJobResponseTypeDef",
+BatchDeleteReadSetResponseTypeDef = TypedDict(
+    "BatchDeleteReadSetResponseTypeDef",
     {
-        "creationTime": datetime,
-        "destination": str,
-        "id": str,
-        "sequenceStoreId": str,
-        "status": ReadSetExportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[ReadSetBatchErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartReadSetImportJobResponseTypeDef = TypedDict(
-    "StartReadSetImportJobResponseTypeDef",
+CompleteMultipartReadSetUploadRequestRequestTypeDef = TypedDict(
+    "CompleteMultipartReadSetUploadRequestRequestTypeDef",
     {
-        "creationTime": datetime,
-        "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
-        "status": ReadSetImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReferenceImportJobResponseTypeDef = TypedDict(
-    "StartReferenceImportJobResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "id": str,
-        "referenceStoreId": str,
-        "roleArn": str,
-        "status": ReferenceImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRunResponseTypeDef = TypedDict(
-    "StartRunResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "status": RunStatusType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartVariantImportResponseTypeDef = TypedDict(
-    "StartVariantImportResponseTypeDef",
-    {
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVariantStoreResponseTypeDef = TypedDict(
-    "UpdateVariantStoreResponseTypeDef",
-    {
-        "creationTime": datetime,
-        "description": str,
-        "id": str,
-        "name": str,
-        "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "uploadId": str,
+        "parts": Sequence[CompleteReadSetUploadPartListItemTypeDef],
     },
 )
 
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "requestId": str,
     },
 )
 _OptionalCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_OptionalCreateWorkflowRequestRequestTypeDef",
     {
-        "definitionUri": str,
-        "definitionZip": Union[str, bytes, IO[Any], StreamingBody],
+        "name": str,
         "description": str,
         "engine": WorkflowEngineType,
+        "definitionZip": Union[str, bytes, IO[Any], StreamingBody],
+        "definitionUri": str,
         "main": str,
-        "name": str,
         "parameterTemplate": Mapping[str, WorkflowParameterTypeDef],
         "storageCapacity": int,
         "tags": Mapping[str, str],
+        "accelerators": Literal["GPU"],
     },
     total=False,
 )
 
 class CreateWorkflowRequestRequestTypeDef(
     _RequiredCreateWorkflowRequestRequestTypeDef, _OptionalCreateWorkflowRequestRequestTypeDef
 ):
     pass
 
 GetWorkflowResponseTypeDef = TypedDict(
     "GetWorkflowResponseTypeDef",
     {
         "arn": str,
-        "creationTime": datetime,
-        "definition": str,
+        "id": str,
+        "status": WorkflowStatusType,
+        "type": WorkflowTypeType,
+        "name": str,
         "description": str,
-        "digest": str,
         "engine": WorkflowEngineType,
-        "id": str,
+        "definition": str,
         "main": str,
-        "name": str,
+        "digest": str,
         "parameterTemplate": Dict[str, WorkflowParameterTypeDef],
-        "status": WorkflowStatusType,
-        "statusMessage": str,
         "storageCapacity": int,
+        "creationTime": datetime,
+        "statusMessage": str,
         "tags": Dict[str, str],
-        "type": Literal["PRIVATE"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "metadata": Dict[str, str],
+        "accelerators": Literal["GPU"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetExportJobResponseTypeDef = TypedDict(
     "GetReadSetExportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destination": str,
         "id": str,
-        "readSets": List[ExportReadSetDetailTypeDef],
         "sequenceStoreId": str,
+        "destination": str,
         "status": ReadSetExportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "readSets": List[ExportReadSetDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+    {
+        "filter": ExportReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
+class ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef(
+    _RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
+    _OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListReadSetExportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetExportJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetExportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetExportJobsRequestRequestTypeDef",
     {
-        "filter": ExportReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ExportReadSetFilterTypeDef,
     },
     total=False,
 )
 
 class ListReadSetExportJobsRequestRequestTypeDef(
     _RequiredListReadSetExportJobsRequestRequestTypeDef,
     _OptionalListReadSetExportJobsRequestRequestTypeDef,
 ):
     pass
 
 ListReadSetExportJobsResponseTypeDef = TypedDict(
     "ListReadSetExportJobsResponseTypeDef",
     {
-        "exportJobs": List[ExportReadSetJobDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "exportJobs": List[ExportReadSetJobDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReadSetExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartReadSetExportJobRequestRequestTypeDef",
     {
+        "sequenceStoreId": str,
         "destination": str,
         "roleArn": str,
-        "sequenceStoreId": str,
         "sources": Sequence[ExportReadSetTypeDef],
     },
 )
 _OptionalStartReadSetExportJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartReadSetExportJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -2024,26 +2369,26 @@
     _OptionalStartReadSetExportJobRequestRequestTypeDef,
 ):
     pass
 
 ReadSetFilesTypeDef = TypedDict(
     "ReadSetFilesTypeDef",
     {
-        "index": FileInformationTypeDef,
         "source1": FileInformationTypeDef,
         "source2": FileInformationTypeDef,
+        "index": FileInformationTypeDef,
     },
     total=False,
 )
 
 ReferenceFilesTypeDef = TypedDict(
     "ReferenceFilesTypeDef",
     {
-        "index": FileInformationTypeDef,
         "source": FileInformationTypeDef,
+        "index": FileInformationTypeDef,
     },
     total=False,
 )
 
 _RequiredGetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef = TypedDict(
     "_RequiredGetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef",
     {
@@ -2124,16 +2469,16 @@
     _OptionalGetReadSetActivationJobRequestReadSetActivationJobCompletedWaitTypeDef,
 ):
     pass
 
 _RequiredGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef = TypedDict(
     "_RequiredGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef",
     {
-        "id": str,
         "sequenceStoreId": str,
+        "id": str,
     },
 )
 _OptionalGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef = TypedDict(
     "_OptionalGetReadSetExportJobRequestReadSetExportJobCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
@@ -2335,389 +2680,364 @@
     {
         "id": str,
     },
 )
 _OptionalGetWorkflowRequestWorkflowActiveWaitTypeDef = TypedDict(
     "_OptionalGetWorkflowRequestWorkflowActiveWaitTypeDef",
     {
+        "type": WorkflowTypeType,
         "export": Sequence[Literal["DEFINITION"]],
-        "type": Literal["PRIVATE"],
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
 class GetWorkflowRequestWorkflowActiveWaitTypeDef(
     _RequiredGetWorkflowRequestWorkflowActiveWaitTypeDef,
     _OptionalGetWorkflowRequestWorkflowActiveWaitTypeDef,
 ):
     pass
 
 _RequiredReadSetListItemTypeDef = TypedDict(
     "_RequiredReadSetListItemTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "fileType": FileTypeType,
         "id": str,
+        "arn": str,
         "sequenceStoreId": str,
         "status": ReadSetStatusType,
+        "fileType": FileTypeType,
+        "creationTime": datetime,
     },
 )
 _OptionalReadSetListItemTypeDef = TypedDict(
     "_OptionalReadSetListItemTypeDef",
     {
-        "description": str,
+        "subjectId": str,
+        "sampleId": str,
         "name": str,
+        "description": str,
         "referenceArn": str,
-        "sampleId": str,
         "sequenceInformation": SequenceInformationTypeDef,
-        "subjectId": str,
+        "statusMessage": str,
     },
     total=False,
 )
 
 class ReadSetListItemTypeDef(_RequiredReadSetListItemTypeDef, _OptionalReadSetListItemTypeDef):
     pass
 
 GetReferenceImportJobResponseTypeDef = TypedDict(
     "GetReferenceImportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
         "id": str,
         "referenceStoreId": str,
         "roleArn": str,
-        "sources": List[ImportReferenceSourceItemTypeDef],
         "status": ReferenceImportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "sources": List[ImportReferenceSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVariantImportResponseTypeDef = TypedDict(
     "GetVariantImportResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destinationName": str,
         "id": str,
-        "items": List[VariantImportItemDetailTypeDef],
+        "destinationName": str,
         "roleArn": str,
-        "runLeftNormalization": bool,
         "status": JobStatusType,
         "statusMessage": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "completionTime": datetime,
+        "items": List[VariantImportItemDetailTypeDef],
+        "runLeftNormalization": bool,
+        "annotationFields": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+    {
+        "sequenceStoreId": str,
+    },
+)
+_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+    {
+        "filter": ImportReadSetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef(
+    _RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
+    _OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListReadSetImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReadSetImportJobsRequestRequestTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetImportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetImportJobsRequestRequestTypeDef",
     {
-        "filter": ImportReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ImportReadSetFilterTypeDef,
     },
     total=False,
 )
 
 class ListReadSetImportJobsRequestRequestTypeDef(
     _RequiredListReadSetImportJobsRequestRequestTypeDef,
     _OptionalListReadSetImportJobsRequestRequestTypeDef,
 ):
     pass
 
 ListReadSetImportJobsResponseTypeDef = TypedDict(
     "ListReadSetImportJobsResponseTypeDef",
     {
-        "importJobs": List[ImportReadSetJobItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "importJobs": List[ImportReadSetJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportReadSetSourceItemTypeDef = TypedDict(
     "_RequiredImportReadSetSourceItemTypeDef",
     {
-        "sampleId": str,
-        "sourceFileType": FileTypeType,
         "sourceFiles": SourceFilesTypeDef,
+        "sourceFileType": FileTypeType,
         "status": ReadSetImportJobItemStatusType,
         "subjectId": str,
+        "sampleId": str,
     },
 )
 _OptionalImportReadSetSourceItemTypeDef = TypedDict(
     "_OptionalImportReadSetSourceItemTypeDef",
     {
-        "description": str,
+        "statusMessage": str,
         "generatedFrom": str,
-        "name": str,
         "referenceArn": str,
-        "statusMessage": str,
+        "name": str,
+        "description": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
 class ImportReadSetSourceItemTypeDef(
     _RequiredImportReadSetSourceItemTypeDef, _OptionalImportReadSetSourceItemTypeDef
 ):
     pass
 
 _RequiredStartReadSetImportJobSourceItemTypeDef = TypedDict(
     "_RequiredStartReadSetImportJobSourceItemTypeDef",
     {
-        "referenceArn": str,
-        "sampleId": str,
-        "sourceFileType": FileTypeType,
         "sourceFiles": SourceFilesTypeDef,
+        "sourceFileType": FileTypeType,
         "subjectId": str,
+        "sampleId": str,
+        "referenceArn": str,
     },
 )
 _OptionalStartReadSetImportJobSourceItemTypeDef = TypedDict(
     "_OptionalStartReadSetImportJobSourceItemTypeDef",
     {
-        "description": str,
         "generatedFrom": str,
         "name": str,
+        "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class StartReadSetImportJobSourceItemTypeDef(
     _RequiredStartReadSetImportJobSourceItemTypeDef, _OptionalStartReadSetImportJobSourceItemTypeDef
 ):
     pass
 
+_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
+    "_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+    {
+        "referenceStoreId": str,
+    },
+)
+_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
+    "_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+    {
+        "filter": ImportReferenceFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef(
+    _RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+    _OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListReferenceImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListReferenceImportJobsRequestRequestTypeDef",
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferenceImportJobsRequestRequestTypeDef = TypedDict(
     "_OptionalListReferenceImportJobsRequestRequestTypeDef",
     {
-        "filter": ImportReferenceFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ImportReferenceFilterTypeDef,
     },
     total=False,
 )
 
 class ListReferenceImportJobsRequestRequestTypeDef(
     _RequiredListReferenceImportJobsRequestRequestTypeDef,
     _OptionalListReferenceImportJobsRequestRequestTypeDef,
 ):
     pass
 
 ListReferenceImportJobsResponseTypeDef = TypedDict(
     "ListReferenceImportJobsResponseTypeDef",
     {
-        "importJobs": List[ImportReferenceJobItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "importJobs": List[ImportReferenceJobItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAnnotationImportJobsRequestRequestTypeDef = TypedDict(
-    "ListAnnotationImportJobsRequestRequestTypeDef",
+ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef = TypedDict(
+    "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
     {
-        "filter": ListAnnotationImportJobsFilterTypeDef,
         "ids": Sequence[str],
-        "maxResults": int,
-        "nextToken": str,
+        "filter": ListAnnotationImportJobsFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef = TypedDict(
-    "ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef",
+ListAnnotationImportJobsRequestRequestTypeDef = TypedDict(
+    "ListAnnotationImportJobsRequestRequestTypeDef",
     {
-        "filter": ListAnnotationImportJobsFilterTypeDef,
+        "maxResults": int,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "filter": ListAnnotationImportJobsFilterTypeDef,
     },
     total=False,
 )
 
-_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef",
+ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef = TypedDict(
+    "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
     {
-        "filter": ActivateReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ids": Sequence[str],
+        "filter": ListAnnotationStoresFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef(
-    _RequiredListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-    _OptionalListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef",
+ListAnnotationStoresRequestRequestTypeDef = TypedDict(
+    "ListAnnotationStoresRequestRequestTypeDef",
     {
-        "filter": ExportReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ids": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+        "filter": ListAnnotationStoresFilterTypeDef,
     },
     total=False,
 )
 
-class ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef(
-    _RequiredListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-    _OptionalListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
-    {
-        "sequenceStoreId": str,
-    },
-)
-_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef",
+ListMultipartReadSetUploadsResponseTypeDef = TypedDict(
+    "ListMultipartReadSetUploadsResponseTypeDef",
     {
-        "filter": ImportReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "uploads": List[MultipartReadSetUploadListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef(
-    _RequiredListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-    _OptionalListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
-    "_RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+_RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef = TypedDict(
+    "_RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
     {
-        "referenceStoreId": str,
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
     },
 )
-_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef = TypedDict(
-    "_OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef",
+_OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef = TypedDict(
+    "_OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef",
     {
-        "filter": ImportReferenceFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ReadSetUploadPartListFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef(
-    _RequiredListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
-    _OptionalListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
+class ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef(
+    _RequiredListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
+    _OptionalListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
 ):
     pass
 
-ListRunGroupsRequestListRunGroupsPaginateTypeDef = TypedDict(
-    "ListRunGroupsRequestListRunGroupsPaginateTypeDef",
-    {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
-    "_RequiredListRunTasksRequestListRunTasksPaginateTypeDef",
+_RequiredListReadSetUploadPartsRequestRequestTypeDef = TypedDict(
+    "_RequiredListReadSetUploadPartsRequestRequestTypeDef",
     {
-        "id": str,
+        "sequenceStoreId": str,
+        "uploadId": str,
+        "partSource": ReadSetPartSourceType,
     },
 )
-_OptionalListRunTasksRequestListRunTasksPaginateTypeDef = TypedDict(
-    "_OptionalListRunTasksRequestListRunTasksPaginateTypeDef",
+_OptionalListReadSetUploadPartsRequestRequestTypeDef = TypedDict(
+    "_OptionalListReadSetUploadPartsRequestRequestTypeDef",
     {
-        "status": TaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+        "filter": ReadSetUploadPartListFilterTypeDef,
     },
     total=False,
 )
 
-class ListRunTasksRequestListRunTasksPaginateTypeDef(
-    _RequiredListRunTasksRequestListRunTasksPaginateTypeDef,
-    _OptionalListRunTasksRequestListRunTasksPaginateTypeDef,
+class ListReadSetUploadPartsRequestRequestTypeDef(
+    _RequiredListReadSetUploadPartsRequestRequestTypeDef,
+    _OptionalListReadSetUploadPartsRequestRequestTypeDef,
 ):
     pass
 
-ListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "ListRunsRequestListRunsPaginateTypeDef",
+ListReadSetUploadPartsResponseTypeDef = TypedDict(
+    "ListReadSetUploadPartsResponseTypeDef",
     {
-        "name": str,
-        "runGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "name": str,
-        "type": Literal["PRIVATE"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef = TypedDict(
-    "ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef",
-    {
-        "filter": ListAnnotationStoresFilterTypeDef,
-        "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAnnotationStoresRequestRequestTypeDef = TypedDict(
-    "ListAnnotationStoresRequestRequestTypeDef",
-    {
-        "filter": ListAnnotationStoresFilterTypeDef,
-        "ids": Sequence[str],
-        "maxResults": int,
         "nextToken": str,
+        "parts": List[ReadSetUploadPartListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredListReadSetsRequestListReadSetsPaginateTypeDef = TypedDict(
     "_RequiredListReadSetsRequestListReadSetsPaginateTypeDef",
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetsRequestListReadSetsPaginateTypeDef = TypedDict(
     "_OptionalListReadSetsRequestListReadSetsPaginateTypeDef",
     {
         "filter": ReadSetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListReadSetsRequestListReadSetsPaginateTypeDef(
     _RequiredListReadSetsRequestListReadSetsPaginateTypeDef,
     _OptionalListReadSetsRequestListReadSetsPaginateTypeDef,
@@ -2729,56 +3049,56 @@
     {
         "sequenceStoreId": str,
     },
 )
 _OptionalListReadSetsRequestRequestTypeDef = TypedDict(
     "_OptionalListReadSetsRequestRequestTypeDef",
     {
-        "filter": ReadSetFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReadSetFilterTypeDef,
     },
     total=False,
 )
 
 class ListReadSetsRequestRequestTypeDef(
     _RequiredListReadSetsRequestRequestTypeDef, _OptionalListReadSetsRequestRequestTypeDef
 ):
     pass
 
 ListReferenceStoresRequestListReferenceStoresPaginateTypeDef = TypedDict(
     "ListReferenceStoresRequestListReferenceStoresPaginateTypeDef",
     {
         "filter": ReferenceStoreFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReferenceStoresRequestRequestTypeDef = TypedDict(
     "ListReferenceStoresRequestRequestTypeDef",
     {
-        "filter": ReferenceStoreFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReferenceStoreFilterTypeDef,
     },
     total=False,
 )
 
 _RequiredListReferencesRequestListReferencesPaginateTypeDef = TypedDict(
     "_RequiredListReferencesRequestListReferencesPaginateTypeDef",
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferencesRequestListReferencesPaginateTypeDef = TypedDict(
     "_OptionalListReferencesRequestListReferencesPaginateTypeDef",
     {
         "filter": ReferenceFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListReferencesRequestListReferencesPaginateTypeDef(
     _RequiredListReferencesRequestListReferencesPaginateTypeDef,
     _OptionalListReferencesRequestListReferencesPaginateTypeDef,
@@ -2790,138 +3110,138 @@
     {
         "referenceStoreId": str,
     },
 )
 _OptionalListReferencesRequestRequestTypeDef = TypedDict(
     "_OptionalListReferencesRequestRequestTypeDef",
     {
-        "filter": ReferenceFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": ReferenceFilterTypeDef,
     },
     total=False,
 )
 
 class ListReferencesRequestRequestTypeDef(
     _RequiredListReferencesRequestRequestTypeDef, _OptionalListReferencesRequestRequestTypeDef
 ):
     pass
 
 ListReferencesResponseTypeDef = TypedDict(
     "ListReferencesResponseTypeDef",
     {
         "nextToken": str,
         "references": List[ReferenceListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunGroupsResponseTypeDef = TypedDict(
     "ListRunGroupsResponseTypeDef",
     {
         "items": List[RunGroupListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunTasksResponseTypeDef = TypedDict(
     "ListRunTasksResponseTypeDef",
     {
         "items": List[TaskListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunsResponseTypeDef = TypedDict(
     "ListRunsResponseTypeDef",
     {
         "items": List[RunListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSequenceStoresRequestListSequenceStoresPaginateTypeDef = TypedDict(
     "ListSequenceStoresRequestListSequenceStoresPaginateTypeDef",
     {
         "filter": SequenceStoreFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSequenceStoresRequestRequestTypeDef = TypedDict(
     "ListSequenceStoresRequestRequestTypeDef",
     {
-        "filter": SequenceStoreFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
+        "filter": SequenceStoreFilterTypeDef,
     },
     total=False,
 )
 
 ListVariantImportJobsRequestListVariantImportJobsPaginateTypeDef = TypedDict(
     "ListVariantImportJobsRequestListVariantImportJobsPaginateTypeDef",
     {
-        "filter": ListVariantImportJobsFilterTypeDef,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ListVariantImportJobsFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListVariantImportJobsRequestRequestTypeDef = TypedDict(
     "ListVariantImportJobsRequestRequestTypeDef",
     {
-        "filter": ListVariantImportJobsFilterTypeDef,
-        "ids": Sequence[str],
         "maxResults": int,
+        "ids": Sequence[str],
         "nextToken": str,
+        "filter": ListVariantImportJobsFilterTypeDef,
     },
     total=False,
 )
 
 ListVariantImportJobsResponseTypeDef = TypedDict(
     "ListVariantImportJobsResponseTypeDef",
     {
-        "nextToken": str,
         "variantImportJobs": List[VariantImportJobItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVariantStoresRequestListVariantStoresPaginateTypeDef = TypedDict(
     "ListVariantStoresRequestListVariantStoresPaginateTypeDef",
     {
-        "filter": ListVariantStoresFilterTypeDef,
         "ids": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filter": ListVariantStoresFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListVariantStoresRequestRequestTypeDef = TypedDict(
     "ListVariantStoresRequestRequestTypeDef",
     {
-        "filter": ListVariantStoresFilterTypeDef,
-        "ids": Sequence[str],
         "maxResults": int,
+        "ids": Sequence[str],
         "nextToken": str,
+        "filter": ListVariantStoresFilterTypeDef,
     },
     total=False,
 )
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "items": List[WorkflowListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TsvOptionsTypeDef = TypedDict(
     "TsvOptionsTypeDef",
     {
         "readOptions": ReadOptionsTypeDef,
@@ -2972,22 +3292,23 @@
 ):
     pass
 
 _RequiredStartVariantImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartVariantImportRequestRequestTypeDef",
     {
         "destinationName": str,
-        "items": Sequence[VariantImportItemSourceTypeDef],
         "roleArn": str,
+        "items": Sequence[VariantImportItemSourceTypeDef],
     },
 )
 _OptionalStartVariantImportRequestRequestTypeDef = TypedDict(
     "_OptionalStartVariantImportRequestRequestTypeDef",
     {
         "runLeftNormalization": bool,
+        "annotationFields": Mapping[str, str],
     },
     total=False,
 )
 
 class StartVariantImportRequestRequestTypeDef(
     _RequiredStartVariantImportRequestRequestTypeDef,
     _OptionalStartVariantImportRequestRequestTypeDef,
@@ -3003,111 +3324,112 @@
 )
 
 ListAnnotationStoresResponseTypeDef = TypedDict(
     "ListAnnotationStoresResponseTypeDef",
     {
         "annotationStores": List[AnnotationStoreItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReferenceStoresResponseTypeDef = TypedDict(
     "ListReferenceStoresResponseTypeDef",
     {
         "nextToken": str,
         "referenceStores": List[ReferenceStoreDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSequenceStoresResponseTypeDef = TypedDict(
     "ListSequenceStoresResponseTypeDef",
     {
         "nextToken": str,
         "sequenceStores": List[SequenceStoreDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVariantStoresResponseTypeDef = TypedDict(
     "ListVariantStoresResponseTypeDef",
     {
-        "nextToken": str,
         "variantStores": List[VariantStoreItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetMetadataResponseTypeDef = TypedDict(
     "GetReadSetMetadataResponseTypeDef",
     {
+        "id": str,
         "arn": str,
-        "creationTime": datetime,
+        "sequenceStoreId": str,
+        "subjectId": str,
+        "sampleId": str,
+        "status": ReadSetStatusType,
+        "name": str,
         "description": str,
         "fileType": FileTypeType,
-        "files": ReadSetFilesTypeDef,
-        "id": str,
-        "name": str,
-        "referenceArn": str,
-        "sampleId": str,
+        "creationTime": datetime,
         "sequenceInformation": SequenceInformationTypeDef,
-        "sequenceStoreId": str,
-        "status": ReadSetStatusType,
-        "subjectId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "referenceArn": str,
+        "files": ReadSetFilesTypeDef,
+        "statusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReferenceMetadataResponseTypeDef = TypedDict(
     "GetReferenceMetadataResponseTypeDef",
     {
-        "arn": str,
-        "creationTime": datetime,
-        "description": str,
-        "files": ReferenceFilesTypeDef,
         "id": str,
-        "md5": str,
-        "name": str,
+        "arn": str,
         "referenceStoreId": str,
+        "md5": str,
         "status": ReferenceStatusType,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "files": ReferenceFilesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReadSetsResponseTypeDef = TypedDict(
     "ListReadSetsResponseTypeDef",
     {
         "nextToken": str,
         "readSets": List[ReadSetListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReadSetImportJobResponseTypeDef = TypedDict(
     "GetReadSetImportJobResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
         "id": str,
-        "roleArn": str,
         "sequenceStoreId": str,
-        "sources": List[ImportReadSetSourceItemTypeDef],
+        "roleArn": str,
         "status": ReadSetImportJobStatusType,
         "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "creationTime": datetime,
+        "completionTime": datetime,
+        "sources": List[ImportReadSetSourceItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReadSetImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartReadSetImportJobRequestRequestTypeDef",
     {
-        "roleArn": str,
         "sequenceStoreId": str,
+        "roleArn": str,
         "sources": Sequence[StartReadSetImportJobSourceItemTypeDef],
     },
 )
 _OptionalStartReadSetImportJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartReadSetImportJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -3135,112 +3457,114 @@
     {
         "storeFormat": StoreFormatType,
     },
 )
 _OptionalCreateAnnotationStoreRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAnnotationStoreRequestRequestTypeDef",
     {
-        "description": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
+        "name": str,
+        "description": str,
+        "tags": Mapping[str, str],
         "sseConfig": SseConfigTypeDef,
         "storeOptions": StoreOptionsTypeDef,
-        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateAnnotationStoreRequestRequestTypeDef(
     _RequiredCreateAnnotationStoreRequestRequestTypeDef,
     _OptionalCreateAnnotationStoreRequestRequestTypeDef,
 ):
     pass
 
 CreateAnnotationStoreResponseTypeDef = TypedDict(
     "CreateAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "status": StoreStatusType,
         "storeFormat": StoreFormatType,
         "storeOptions": StoreOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": StoreStatusType,
+        "name": str,
+        "creationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnnotationStoreResponseTypeDef = TypedDict(
     "GetAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
-        "sseConfig": SseConfigTypeDef,
         "status": StoreStatusType,
-        "statusMessage": str,
         "storeArn": str,
-        "storeFormat": StoreFormatType,
+        "name": str,
+        "description": str,
+        "sseConfig": SseConfigTypeDef,
+        "creationTime": datetime,
+        "updateTime": datetime,
+        "tags": Dict[str, str],
         "storeOptions": StoreOptionsTypeDef,
+        "storeFormat": StoreFormatType,
+        "statusMessage": str,
         "storeSizeBytes": int,
-        "tags": Dict[str, str],
-        "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAnnotationStoreResponseTypeDef = TypedDict(
     "UpdateAnnotationStoreResponseTypeDef",
     {
-        "creationTime": datetime,
-        "description": str,
         "id": str,
-        "name": str,
         "reference": ReferenceItemTypeDef,
         "status": StoreStatusType,
-        "storeFormat": StoreFormatType,
-        "storeOptions": StoreOptionsTypeDef,
+        "name": str,
+        "description": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "storeOptions": StoreOptionsTypeDef,
+        "storeFormat": StoreFormatType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnnotationImportResponseTypeDef = TypedDict(
     "GetAnnotationImportResponseTypeDef",
     {
-        "completionTime": datetime,
-        "creationTime": datetime,
-        "destinationName": str,
-        "formatOptions": FormatOptionsTypeDef,
         "id": str,
-        "items": List[AnnotationImportItemDetailTypeDef],
+        "destinationName": str,
         "roleArn": str,
-        "runLeftNormalization": bool,
         "status": JobStatusType,
         "statusMessage": str,
+        "creationTime": datetime,
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "completionTime": datetime,
+        "items": List[AnnotationImportItemDetailTypeDef],
+        "runLeftNormalization": bool,
+        "formatOptions": FormatOptionsTypeDef,
+        "annotationFields": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartAnnotationImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartAnnotationImportRequestRequestTypeDef",
     {
         "destinationName": str,
-        "items": Sequence[AnnotationImportItemSourceTypeDef],
         "roleArn": str,
+        "items": Sequence[AnnotationImportItemSourceTypeDef],
     },
 )
 _OptionalStartAnnotationImportRequestRequestTypeDef = TypedDict(
     "_OptionalStartAnnotationImportRequestRequestTypeDef",
     {
         "formatOptions": FormatOptionsTypeDef,
         "runLeftNormalization": bool,
+        "annotationFields": Mapping[str, str],
     },
     total=False,
 )
 
 class StartAnnotationImportRequestRequestTypeDef(
     _RequiredStartAnnotationImportRequestRequestTypeDef,
     _OptionalStartAnnotationImportRequestRequestTypeDef,
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/waiter.py` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/waiter.py`

 * *Files 0% similar despite different names*

```diff
@@ -49,14 +49,15 @@
     ```
 """
 import sys
 from typing import Sequence
 
 from aiobotocore.waiter import AIOWaiter
 
+from .literals import WorkflowTypeType
 from .type_defs import WaiterConfigTypeDef
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -137,15 +138,15 @@
 class ReadSetExportJobCompletedWaiter(AIOWaiter):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.ReadSetExportJobCompleted)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#readsetexportjobcompletedwaiter)
     """
 
     async def wait(
-        self, *, id: str, sequenceStoreId: str, WaiterConfig: WaiterConfigTypeDef = ...
+        self, *, sequenceStoreId: str, id: str, WaiterConfig: WaiterConfigTypeDef = ...
     ) -> None:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.ReadSetExportJobCompleted.wait)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#readsetexportjobcompletedwaiter)
         """
 
 
@@ -288,15 +289,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#workflowactivewaiter)
     """
 
     async def wait(
         self,
         *,
         id: str,
+        type: WorkflowTypeType = ...,
         export: Sequence[Literal["DEFINITION"]] = ...,
-        type: Literal["PRIVATE"] = ...,
         WaiterConfig: WaiterConfigTypeDef = ...
     ) -> None:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.WorkflowActive.wait)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#workflowactivewaiter)
         """
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics/waiter.pyi` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics/waiter.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -49,14 +49,15 @@
     ```
 """
 import sys
 from typing import Sequence
 
 from aiobotocore.waiter import AIOWaiter
 
+from .literals import WorkflowTypeType
 from .type_defs import WaiterConfigTypeDef
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -131,15 +132,15 @@
 class ReadSetExportJobCompletedWaiter(AIOWaiter):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.ReadSetExportJobCompleted)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#readsetexportjobcompletedwaiter)
     """
 
     async def wait(
-        self, *, id: str, sequenceStoreId: str, WaiterConfig: WaiterConfigTypeDef = ...
+        self, *, sequenceStoreId: str, id: str, WaiterConfig: WaiterConfigTypeDef = ...
     ) -> None:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.ReadSetExportJobCompleted.wait)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#readsetexportjobcompletedwaiter)
         """
 
 class ReadSetImportJobCompletedWaiter(AIOWaiter):
@@ -272,15 +273,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#workflowactivewaiter)
     """
 
     async def wait(
         self,
         *,
         id: str,
+        type: WorkflowTypeType = ...,
         export: Sequence[Literal["DEFINITION"]] = ...,
-        type: Literal["PRIVATE"] = ...,
         WaiterConfig: WaiterConfigTypeDef = ...
     ) -> None:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics.Waiter.WorkflowActive.wait)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/waiters/#workflowactivewaiter)
         """
```

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/PKG-INFO` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-omics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Omics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Omics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-omics"></a>
 
 # types-aiobotocore-omics
 
 [![PyPI - types-aiobotocore-omics](https://img.shields.io/pypi/v/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-omics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-omics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-omics?color=blue)](https://pypistats.org/packages/types-aiobotocore-omics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Omics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
+[aiobotocore.Omics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/omics.html#Omics)
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
 [types-aiobotocore-omics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_omics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,17 +274,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_omics import OmicsClient
 from types_aiobotocore_omics.paginator import (
     ListAnnotationImportJobsPaginator,
     ListAnnotationStoresPaginator,
+    ListMultipartReadSetUploadsPaginator,
     ListReadSetActivationJobsPaginator,
     ListReadSetExportJobsPaginator,
     ListReadSetImportJobsPaginator,
+    ListReadSetUploadPartsPaginator,
     ListReadSetsPaginator,
     ListReferenceImportJobsPaginator,
     ListReferenceStoresPaginator,
     ListReferencesPaginator,
     ListRunGroupsPaginator,
     ListRunTasksPaginator,
     ListRunsPaginator,
@@ -302,23 +304,29 @@
     # Types should be correctly discovered by mypy and IDEs
     list_annotation_import_jobs_paginator: ListAnnotationImportJobsPaginator = client.get_paginator(
         "list_annotation_import_jobs"
     )
     list_annotation_stores_paginator: ListAnnotationStoresPaginator = client.get_paginator(
         "list_annotation_stores"
     )
+    list_multipart_read_set_uploads_paginator: ListMultipartReadSetUploadsPaginator = (
+        client.get_paginator("list_multipart_read_set_uploads")
+    )
     list_read_set_activation_jobs_paginator: ListReadSetActivationJobsPaginator = (
         client.get_paginator("list_read_set_activation_jobs")
     )
     list_read_set_export_jobs_paginator: ListReadSetExportJobsPaginator = client.get_paginator(
         "list_read_set_export_jobs"
     )
     list_read_set_import_jobs_paginator: ListReadSetImportJobsPaginator = client.get_paginator(
         "list_read_set_import_jobs"
     )
+    list_read_set_upload_parts_paginator: ListReadSetUploadPartsPaginator = client.get_paginator(
+        "list_read_set_upload_parts"
+    )
     list_read_sets_paginator: ListReadSetsPaginator = client.get_paginator("list_read_sets")
     list_reference_import_jobs_paginator: ListReferenceImportJobsPaginator = client.get_paginator(
         "list_reference_import_jobs"
     )
     list_reference_stores_paginator: ListReferenceStoresPaginator = client.get_paginator(
         "list_reference_stores"
     )
@@ -415,27 +423,30 @@
 ### Literals
 
 `types_aiobotocore_omics.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_omics.literals import (
+    AcceleratorsType,
     AnnotationImportJobCreatedWaiterName,
     AnnotationStoreCreatedWaiterName,
     AnnotationStoreDeletedWaiterName,
     AnnotationTypeType,
     EncryptionTypeType,
     FileTypeType,
     FormatToHeaderKeyType,
     JobStatusType,
     ListAnnotationImportJobsPaginatorName,
     ListAnnotationStoresPaginatorName,
+    ListMultipartReadSetUploadsPaginatorName,
     ListReadSetActivationJobsPaginatorName,
     ListReadSetExportJobsPaginatorName,
     ListReadSetImportJobsPaginatorName,
+    ListReadSetUploadPartsPaginatorName,
     ListReadSetsPaginatorName,
     ListReferenceImportJobsPaginatorName,
     ListReferenceStoresPaginatorName,
     ListReferencesPaginatorName,
     ListRunGroupsPaginatorName,
     ListRunTasksPaginatorName,
     ListRunsPaginatorName,
@@ -449,14 +460,15 @@
     ReadSetExportJobCompletedWaiterName,
     ReadSetExportJobItemStatusType,
     ReadSetExportJobStatusType,
     ReadSetFileType,
     ReadSetImportJobCompletedWaiterName,
     ReadSetImportJobItemStatusType,
     ReadSetImportJobStatusType,
+    ReadSetPartSourceType,
     ReadSetStatusType,
     ReferenceFileType,
     ReferenceImportJobCompletedWaiterName,
     ReferenceImportJobItemStatusType,
     ReferenceImportJobStatusType,
     ReferenceStatusType,
     RunCompletedWaiterName,
@@ -479,54 +491,64 @@
     WorkflowStatusType,
     WorkflowTypeType,
     OmicsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
-def check_value(value: AnnotationImportJobCreatedWaiterName) -> bool:
+def check_value(value: AcceleratorsType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_omics.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_omics.type_defs import (
+    AbortMultipartReadSetUploadRequestRequestTypeDef,
     ActivateReadSetFilterTypeDef,
     ActivateReadSetJobItemTypeDef,
     ActivateReadSetSourceItemTypeDef,
     AnnotationImportItemDetailTypeDef,
     AnnotationImportItemSourceTypeDef,
     AnnotationImportJobItemTypeDef,
     ReferenceItemTypeDef,
     SseConfigTypeDef,
     BatchDeleteReadSetRequestRequestTypeDef,
     ReadSetBatchErrorTypeDef,
-    ResponseMetadataTypeDef,
     CancelAnnotationImportRequestRequestTypeDef,
     CancelRunRequestRequestTypeDef,
     CancelVariantImportRequestRequestTypeDef,
+    CompleteReadSetUploadPartListItemTypeDef,
+    CompleteMultipartReadSetUploadResponseTypeDef,
+    CreateMultipartReadSetUploadRequestRequestTypeDef,
+    CreateMultipartReadSetUploadResponseTypeDef,
     CreateRunGroupRequestRequestTypeDef,
+    CreateRunGroupResponseTypeDef,
     WorkflowParameterTypeDef,
+    CreateWorkflowResponseTypeDef,
     DeleteAnnotationStoreRequestRequestTypeDef,
+    DeleteAnnotationStoreResponseTypeDef,
     DeleteReferenceRequestRequestTypeDef,
     DeleteReferenceStoreRequestRequestTypeDef,
     DeleteRunGroupRequestRequestTypeDef,
     DeleteRunRequestRequestTypeDef,
     DeleteSequenceStoreRequestRequestTypeDef,
     DeleteVariantStoreRequestRequestTypeDef,
+    DeleteVariantStoreResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportReadSetDetailTypeDef,
     ExportReadSetFilterTypeDef,
     ExportReadSetJobDetailTypeDef,
     ExportReadSetTypeDef,
     FileInformationTypeDef,
     VcfOptionsTypeDef,
     WaiterConfigTypeDef,
@@ -534,104 +556,114 @@
     GetAnnotationStoreRequestRequestTypeDef,
     GetReadSetActivationJobRequestRequestTypeDef,
     GetReadSetExportJobRequestRequestTypeDef,
     GetReadSetImportJobRequestRequestTypeDef,
     GetReadSetMetadataRequestRequestTypeDef,
     SequenceInformationTypeDef,
     GetReadSetRequestRequestTypeDef,
+    GetReadSetResponseTypeDef,
     GetReferenceImportJobRequestRequestTypeDef,
     ImportReferenceSourceItemTypeDef,
     GetReferenceMetadataRequestRequestTypeDef,
     GetReferenceRequestRequestTypeDef,
+    GetReferenceResponseTypeDef,
     GetReferenceStoreRequestRequestTypeDef,
     GetRunGroupRequestRequestTypeDef,
+    GetRunGroupResponseTypeDef,
     GetRunRequestRequestTypeDef,
+    GetRunResponseTypeDef,
     GetRunTaskRequestRequestTypeDef,
+    GetRunTaskResponseTypeDef,
     GetSequenceStoreRequestRequestTypeDef,
     GetVariantImportRequestRequestTypeDef,
     VariantImportItemDetailTypeDef,
     GetVariantStoreRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     ImportReadSetFilterTypeDef,
     ImportReadSetJobItemTypeDef,
     SourceFilesTypeDef,
     ImportReferenceFilterTypeDef,
     ImportReferenceJobItemTypeDef,
     ListAnnotationImportJobsFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListAnnotationStoresFilterTypeDef,
+    ListMultipartReadSetUploadsRequestListMultipartReadSetUploadsPaginateTypeDef,
+    ListMultipartReadSetUploadsRequestRequestTypeDef,
+    MultipartReadSetUploadListItemTypeDef,
+    ReadSetUploadPartListFilterTypeDef,
+    ReadSetUploadPartListItemTypeDef,
     ReadSetFilterTypeDef,
     ReferenceStoreFilterTypeDef,
     ReferenceFilterTypeDef,
     ReferenceListItemTypeDef,
+    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
     ListRunGroupsRequestRequestTypeDef,
     RunGroupListItemTypeDef,
+    ListRunTasksRequestListRunTasksPaginateTypeDef,
     ListRunTasksRequestRequestTypeDef,
     TaskListItemTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
     RunListItemTypeDef,
     SequenceStoreFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListVariantImportJobsFilterTypeDef,
     VariantImportJobItemTypeDef,
     ListVariantStoresFilterTypeDef,
+    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     WorkflowListItemTypeDef,
+    PaginatorConfigTypeDef,
     ReadOptionsTypeDef,
+    ResponseMetadataTypeDef,
+    StartAnnotationImportResponseTypeDef,
     StartReadSetActivationJobSourceItemTypeDef,
+    StartReadSetActivationJobResponseTypeDef,
+    StartReadSetExportJobResponseTypeDef,
+    StartReadSetImportJobResponseTypeDef,
     StartReferenceImportJobSourceItemTypeDef,
+    StartReferenceImportJobResponseTypeDef,
     StartRunRequestRequestTypeDef,
+    StartRunResponseTypeDef,
     VariantImportItemSourceTypeDef,
+    StartVariantImportResponseTypeDef,
     TsvStoreOptionsTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAnnotationStoreRequestRequestTypeDef,
     UpdateRunGroupRequestRequestTypeDef,
     UpdateVariantStoreRequestRequestTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UploadReadSetPartRequestRequestTypeDef,
+    UploadReadSetPartResponseTypeDef,
+    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
     ListReadSetActivationJobsRequestRequestTypeDef,
+    ListReadSetActivationJobsResponseTypeDef,
+    GetReadSetActivationJobResponseTypeDef,
+    ListAnnotationImportJobsResponseTypeDef,
+    CreateVariantStoreResponseTypeDef,
+    UpdateVariantStoreResponseTypeDef,
     AnnotationStoreItemTypeDef,
     CreateReferenceStoreRequestRequestTypeDef,
+    CreateReferenceStoreResponseTypeDef,
     CreateSequenceStoreRequestRequestTypeDef,
+    CreateSequenceStoreResponseTypeDef,
     CreateVariantStoreRequestRequestTypeDef,
+    GetReferenceStoreResponseTypeDef,
+    GetSequenceStoreResponseTypeDef,
+    GetVariantStoreResponseTypeDef,
     ReferenceStoreDetailTypeDef,
     SequenceStoreDetailTypeDef,
     VariantStoreItemTypeDef,
     BatchDeleteReadSetResponseTypeDef,
-    CreateReferenceStoreResponseTypeDef,
-    CreateRunGroupResponseTypeDef,
-    CreateSequenceStoreResponseTypeDef,
-    CreateVariantStoreResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteAnnotationStoreResponseTypeDef,
-    DeleteVariantStoreResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetReadSetActivationJobResponseTypeDef,
-    GetReadSetResponseTypeDef,
-    GetReferenceResponseTypeDef,
-    GetReferenceStoreResponseTypeDef,
-    GetRunGroupResponseTypeDef,
-    GetRunResponseTypeDef,
-    GetRunTaskResponseTypeDef,
-    GetSequenceStoreResponseTypeDef,
-    GetVariantStoreResponseTypeDef,
-    ListAnnotationImportJobsResponseTypeDef,
-    ListReadSetActivationJobsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartAnnotationImportResponseTypeDef,
-    StartReadSetActivationJobResponseTypeDef,
-    StartReadSetExportJobResponseTypeDef,
-    StartReadSetImportJobResponseTypeDef,
-    StartReferenceImportJobResponseTypeDef,
-    StartRunResponseTypeDef,
-    StartVariantImportResponseTypeDef,
-    UpdateVariantStoreResponseTypeDef,
+    CompleteMultipartReadSetUploadRequestRequestTypeDef,
     CreateWorkflowRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetReadSetExportJobResponseTypeDef,
+    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
     ListReadSetExportJobsRequestRequestTypeDef,
     ListReadSetExportJobsResponseTypeDef,
     StartReadSetExportJobRequestRequestTypeDef,
     ReadSetFilesTypeDef,
     ReferenceFilesTypeDef,
     GetAnnotationImportRequestAnnotationImportJobCreatedWaitTypeDef,
     GetAnnotationStoreRequestAnnotationStoreCreatedWaitTypeDef,
@@ -647,32 +679,30 @@
     GetVariantImportRequestVariantImportJobCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreCreatedWaitTypeDef,
     GetVariantStoreRequestVariantStoreDeletedWaitTypeDef,
     GetWorkflowRequestWorkflowActiveWaitTypeDef,
     ReadSetListItemTypeDef,
     GetReferenceImportJobResponseTypeDef,
     GetVariantImportResponseTypeDef,
+    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
     ListReadSetImportJobsRequestRequestTypeDef,
     ListReadSetImportJobsResponseTypeDef,
     ImportReadSetSourceItemTypeDef,
     StartReadSetImportJobSourceItemTypeDef,
+    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
     ListReferenceImportJobsRequestRequestTypeDef,
     ListReferenceImportJobsResponseTypeDef,
-    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationImportJobsRequestListAnnotationImportJobsPaginateTypeDef,
-    ListReadSetActivationJobsRequestListReadSetActivationJobsPaginateTypeDef,
-    ListReadSetExportJobsRequestListReadSetExportJobsPaginateTypeDef,
-    ListReadSetImportJobsRequestListReadSetImportJobsPaginateTypeDef,
-    ListReferenceImportJobsRequestListReferenceImportJobsPaginateTypeDef,
-    ListRunGroupsRequestListRunGroupsPaginateTypeDef,
-    ListRunTasksRequestListRunTasksPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListWorkflowsRequestListWorkflowsPaginateTypeDef,
+    ListAnnotationImportJobsRequestRequestTypeDef,
     ListAnnotationStoresRequestListAnnotationStoresPaginateTypeDef,
     ListAnnotationStoresRequestRequestTypeDef,
+    ListMultipartReadSetUploadsResponseTypeDef,
+    ListReadSetUploadPartsRequestListReadSetUploadPartsPaginateTypeDef,
+    ListReadSetUploadPartsRequestRequestTypeDef,
+    ListReadSetUploadPartsResponseTypeDef,
     ListReadSetsRequestListReadSetsPaginateTypeDef,
     ListReadSetsRequestRequestTypeDef,
     ListReferenceStoresRequestListReferenceStoresPaginateTypeDef,
     ListReferenceStoresRequestRequestTypeDef,
     ListReferencesRequestListReferencesPaginateTypeDef,
     ListReferencesRequestRequestTypeDef,
     ListReferencesResponseTypeDef,
@@ -707,54 +737,54 @@
     GetAnnotationStoreResponseTypeDef,
     UpdateAnnotationStoreResponseTypeDef,
     GetAnnotationImportResponseTypeDef,
     StartAnnotationImportRequestRequestTypeDef,
 )
 
 
-def get_structure() -> ActivateReadSetFilterTypeDef:
+def get_structure() -> AbortMultipartReadSetUploadRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-omics-2.5.0.post1/types_aiobotocore_omics.egg-info/SOURCES.txt` & `types-aiobotocore-omics-2.5.1/types_aiobotocore_omics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

