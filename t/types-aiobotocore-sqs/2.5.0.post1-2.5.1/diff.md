# Comparing `tmp/types-aiobotocore-sqs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sqs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sqs-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-sqs-2.5.1.tar", last modified: Wed Jun 28 01:44:13 2023, max compression
```

## Comparing `types-aiobotocore-sqs-2.5.0.post1.tar` & `types-aiobotocore-sqs-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.159654 types-aiobotocore-sqs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17532 2023-03-11 12:27:23.159654 types-aiobotocore-sqs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15977 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.159654 types-aiobotocore-sqs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.151654 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/
--rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17577 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17546 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10131 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10129 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3226 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3221 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20803 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    20762 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    22442 2023-03-11 12:24:28.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22409 2023-03-11 12:24:28.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:27.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.159654 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17532 2023-03-11 12:27:22.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      822 2023-03-11 12:27:23.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:22.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:22.000000 types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.610219 types-aiobotocore-sqs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17710 2023-06-28 01:44:13.606219 types-aiobotocore-sqs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16161 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:13.610219 types-aiobotocore-sqs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.606219 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19613 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19579 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10372 2023-06-28 01:41:15.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10370 2023-06-28 01:41:15.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3110 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3106 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20842 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20801 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    24559 2023-06-28 01:41:15.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24522 2023-06-28 01:41:15.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:14.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.606219 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17710 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      822 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:13.000000 types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/LICENSE` & `types-aiobotocore-sqs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sqs-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sqs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SQS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SQS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sqs"></a>
 
 # types-aiobotocore-sqs
 
 [![PyPI - types-aiobotocore-sqs](https://img.shields.io/pypi/v/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sqs?color=blue)](https://pypistats.org/packages/types-aiobotocore-sqs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SQS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
+[aiobotocore.SQS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
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
 [types-aiobotocore-sqs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -388,63 +388,67 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sqs.type_defs import (
     AddPermissionRequestQueueAddPermissionTypeDef,
     AddPermissionRequestRequestTypeDef,
     BatchResultErrorEntryTypeDef,
+    CancelMessageMoveTaskRequestRequestTypeDef,
+    CancelMessageMoveTaskResultTypeDef,
     ChangeMessageVisibilityBatchRequestEntryTypeDef,
     ChangeMessageVisibilityBatchResultEntryTypeDef,
-    ResponseMetadataTypeDef,
     ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef,
     ChangeMessageVisibilityRequestRequestTypeDef,
     CreateQueueRequestRequestTypeDef,
     CreateQueueRequestServiceResourceCreateQueueTypeDef,
+    CreateQueueResultTypeDef,
     DeleteMessageBatchRequestEntryTypeDef,
     DeleteMessageBatchResultEntryTypeDef,
     DeleteMessageRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetQueueAttributesRequestRequestTypeDef,
+    GetQueueAttributesResultTypeDef,
     GetQueueUrlRequestRequestTypeDef,
     GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueueUrlResultTypeDef,
+    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
     ListDeadLetterSourceQueuesRequestRequestTypeDef,
+    ListDeadLetterSourceQueuesResultTypeDef,
+    ListMessageMoveTasksRequestRequestTypeDef,
+    ListMessageMoveTasksResultEntryTypeDef,
     ListQueueTagsRequestRequestTypeDef,
+    ListQueueTagsResultTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
+    ListQueuesResultTypeDef,
     MessageAttributeValueTypeDef,
     MessageSystemAttributeValueTypeDef,
+    PaginatorConfigTypeDef,
     PurgeQueueRequestRequestTypeDef,
-    QueueMessageRequestTypeDef,
     ReceiveMessageRequestQueueReceiveMessagesTypeDef,
     ReceiveMessageRequestRequestTypeDef,
     RemovePermissionRequestQueueRemovePermissionTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendMessageBatchResultEntryTypeDef,
-    ServiceResourceMessageRequestTypeDef,
-    ServiceResourceQueueRequestTypeDef,
+    SendMessageResultTypeDef,
     SetQueueAttributesRequestQueueSetAttributesTypeDef,
     SetQueueAttributesRequestRequestTypeDef,
+    StartMessageMoveTaskRequestRequestTypeDef,
+    StartMessageMoveTaskResultTypeDef,
     TagQueueRequestRequestTypeDef,
     UntagQueueRequestRequestTypeDef,
     ChangeMessageVisibilityBatchRequestQueueChangeMessageVisibilityBatchTypeDef,
     ChangeMessageVisibilityBatchRequestRequestTypeDef,
     ChangeMessageVisibilityBatchResultTypeDef,
-    CreateQueueResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetQueueAttributesResultTypeDef,
-    GetQueueUrlResultTypeDef,
-    ListDeadLetterSourceQueuesResultTypeDef,
-    ListQueueTagsResultTypeDef,
-    ListQueuesResultTypeDef,
-    SendMessageResultTypeDef,
     DeleteMessageBatchRequestQueueDeleteMessagesTypeDef,
     DeleteMessageBatchRequestRequestTypeDef,
     DeleteMessageBatchResultTypeDef,
-    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
+    ListMessageMoveTasksResultTypeDef,
     MessageTypeDef,
     SendMessageBatchRequestEntryTypeDef,
     SendMessageRequestQueueSendMessageTypeDef,
     SendMessageRequestRequestTypeDef,
     SendMessageBatchResultTypeDef,
     ReceiveMessageResultTypeDef,
     SendMessageBatchRequestQueueSendMessagesTypeDef,
@@ -459,43 +463,43 @@
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/README.md` & `types-aiobotocore-sqs-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sqs"></a>
 
 # types-aiobotocore-sqs
 
 [![PyPI - types-aiobotocore-sqs](https://img.shields.io/pypi/v/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sqs?color=blue)](https://pypistats.org/packages/types-aiobotocore-sqs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SQS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
+[aiobotocore.SQS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
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
 [types-aiobotocore-sqs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,63 +355,67 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sqs.type_defs import (
     AddPermissionRequestQueueAddPermissionTypeDef,
     AddPermissionRequestRequestTypeDef,
     BatchResultErrorEntryTypeDef,
+    CancelMessageMoveTaskRequestRequestTypeDef,
+    CancelMessageMoveTaskResultTypeDef,
     ChangeMessageVisibilityBatchRequestEntryTypeDef,
     ChangeMessageVisibilityBatchResultEntryTypeDef,
-    ResponseMetadataTypeDef,
     ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef,
     ChangeMessageVisibilityRequestRequestTypeDef,
     CreateQueueRequestRequestTypeDef,
     CreateQueueRequestServiceResourceCreateQueueTypeDef,
+    CreateQueueResultTypeDef,
     DeleteMessageBatchRequestEntryTypeDef,
     DeleteMessageBatchResultEntryTypeDef,
     DeleteMessageRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetQueueAttributesRequestRequestTypeDef,
+    GetQueueAttributesResultTypeDef,
     GetQueueUrlRequestRequestTypeDef,
     GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueueUrlResultTypeDef,
+    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
     ListDeadLetterSourceQueuesRequestRequestTypeDef,
+    ListDeadLetterSourceQueuesResultTypeDef,
+    ListMessageMoveTasksRequestRequestTypeDef,
+    ListMessageMoveTasksResultEntryTypeDef,
     ListQueueTagsRequestRequestTypeDef,
+    ListQueueTagsResultTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
+    ListQueuesResultTypeDef,
     MessageAttributeValueTypeDef,
     MessageSystemAttributeValueTypeDef,
+    PaginatorConfigTypeDef,
     PurgeQueueRequestRequestTypeDef,
-    QueueMessageRequestTypeDef,
     ReceiveMessageRequestQueueReceiveMessagesTypeDef,
     ReceiveMessageRequestRequestTypeDef,
     RemovePermissionRequestQueueRemovePermissionTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendMessageBatchResultEntryTypeDef,
-    ServiceResourceMessageRequestTypeDef,
-    ServiceResourceQueueRequestTypeDef,
+    SendMessageResultTypeDef,
     SetQueueAttributesRequestQueueSetAttributesTypeDef,
     SetQueueAttributesRequestRequestTypeDef,
+    StartMessageMoveTaskRequestRequestTypeDef,
+    StartMessageMoveTaskResultTypeDef,
     TagQueueRequestRequestTypeDef,
     UntagQueueRequestRequestTypeDef,
     ChangeMessageVisibilityBatchRequestQueueChangeMessageVisibilityBatchTypeDef,
     ChangeMessageVisibilityBatchRequestRequestTypeDef,
     ChangeMessageVisibilityBatchResultTypeDef,
-    CreateQueueResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetQueueAttributesResultTypeDef,
-    GetQueueUrlResultTypeDef,
-    ListDeadLetterSourceQueuesResultTypeDef,
-    ListQueueTagsResultTypeDef,
-    ListQueuesResultTypeDef,
-    SendMessageResultTypeDef,
     DeleteMessageBatchRequestQueueDeleteMessagesTypeDef,
     DeleteMessageBatchRequestRequestTypeDef,
     DeleteMessageBatchResultTypeDef,
-    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
+    ListMessageMoveTasksResultTypeDef,
     MessageTypeDef,
     SendMessageBatchRequestEntryTypeDef,
     SendMessageRequestQueueSendMessageTypeDef,
     SendMessageRequestRequestTypeDef,
     SendMessageBatchResultTypeDef,
     ReceiveMessageResultTypeDef,
     SendMessageBatchRequestQueueSendMessagesTypeDef,
@@ -426,43 +430,43 @@
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/setup.py` & `types-aiobotocore-sqs-2.5.1/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sqs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sqs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sqs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SQS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SQS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/",
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__init__.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__init__.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/__main__.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SQS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SQS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS\nOther"
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/client.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/client.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,31 +19,34 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import QueueAttributeFilterType, QueueAttributeNameType
 from .paginator import ListDeadLetterSourceQueuesPaginator, ListQueuesPaginator
 from .type_defs import (
+    CancelMessageMoveTaskResultTypeDef,
     ChangeMessageVisibilityBatchRequestEntryTypeDef,
     ChangeMessageVisibilityBatchResultTypeDef,
     CreateQueueResultTypeDef,
     DeleteMessageBatchRequestEntryTypeDef,
     DeleteMessageBatchResultTypeDef,
     EmptyResponseMetadataTypeDef,
     GetQueueAttributesResultTypeDef,
     GetQueueUrlResultTypeDef,
     ListDeadLetterSourceQueuesResultTypeDef,
+    ListMessageMoveTasksResultTypeDef,
     ListQueuesResultTypeDef,
     ListQueueTagsResultTypeDef,
     MessageAttributeValueTypeDef,
     MessageSystemAttributeValueTypeDef,
     ReceiveMessageResultTypeDef,
     SendMessageBatchRequestEntryTypeDef,
     SendMessageBatchResultTypeDef,
     SendMessageResultTypeDef,
+    StartMessageMoveTaskResultTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -71,14 +74,15 @@
     MessageNotInflight: Type[BotocoreClientError]
     OverLimit: Type[BotocoreClientError]
     PurgeQueueInProgress: Type[BotocoreClientError]
     QueueDeletedRecently: Type[BotocoreClientError]
     QueueDoesNotExist: Type[BotocoreClientError]
     QueueNameExists: Type[BotocoreClientError]
     ReceiptHandleIsInvalid: Type[BotocoreClientError]
+    ResourceNotFoundException: Type[BotocoreClientError]
     TooManyEntriesInBatchRequest: Type[BotocoreClientError]
     UnsupportedOperation: Type[BotocoreClientError]
 
 
 class SQSClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client)
@@ -111,14 +115,24 @@
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#can_paginate)
         """
 
+    async def cancel_message_move_task(
+        self, *, TaskHandle: str
+    ) -> CancelMessageMoveTaskResultTypeDef:
+        """
+        Cancels a specified message movement task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.cancel_message_move_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#cancel_message_move_task)
+        """
+
     async def change_message_visibility(
         self, *, QueueUrl: str, ReceiptHandle: str, VisibilityTimeout: int
     ) -> EmptyResponseMetadataTypeDef:
         """
         Changes the visibility timeout of a specified message in a queue to a new value.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.change_message_visibility)
@@ -175,15 +189,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_message_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#delete_message_batch)
         """
 
     async def delete_queue(self, *, QueueUrl: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the queue specified by the `QueueUrl` , regardless of the queue's
+        Deletes the queue specified by the `QueueUrl`, regardless of the queue's
         contents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_queue)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#delete_queue)
         """
 
     async def generate_presigned_url(
@@ -227,14 +241,25 @@
         Returns a list of your queues that have the `RedrivePolicy` queue attribute
         configured with a dead-letter queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_dead_letter_source_queues)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_dead_letter_source_queues)
         """
 
+    async def list_message_move_tasks(
+        self, *, SourceArn: str, MaxResults: int = ...
+    ) -> ListMessageMoveTasksResultTypeDef:
+        """
+        Gets the most recent message movement tasks (up to 10) under a specific source
+        queue.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_message_move_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_message_move_tasks)
+        """
+
     async def list_queue_tags(self, *, QueueUrl: str) -> ListQueueTagsResultTypeDef:
         """
         List all cost allocation tags added to the specified Amazon SQS queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_queue_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_queue_tags)
         """
@@ -304,15 +329,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#send_message)
         """
 
     async def send_message_batch(
         self, *, QueueUrl: str, Entries: Sequence[SendMessageBatchRequestEntryTypeDef]
     ) -> SendMessageBatchResultTypeDef:
         """
-        Delivers up to ten messages to the specified queue.
+        You can use `SendMessageBatch` to send up to 10 messages to the specified queue
+        by assigning either identical or different values to each message (or by not
+        assigning values at all).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.send_message_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#send_message_batch)
         """
 
     async def set_queue_attributes(
         self, *, QueueUrl: str, Attributes: Mapping[QueueAttributeNameType, str]
@@ -320,14 +347,25 @@
         """
         Sets the value of one or more queue attributes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.set_queue_attributes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#set_queue_attributes)
         """
 
+    async def start_message_move_task(
+        self, *, SourceArn: str, DestinationArn: str = ..., MaxNumberOfMessagesPerSecond: int = ...
+    ) -> StartMessageMoveTaskResultTypeDef:
+        """
+        Starts an asynchronous task to move messages from a specified source queue to a
+        specified destination queue.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.start_message_move_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#start_message_move_task)
+        """
+
     async def tag_queue(
         self, *, QueueUrl: str, Tags: Mapping[str, str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Add cost allocation tags to the specified Amazon SQS queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.tag_queue)
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/client.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/client.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -19,31 +19,34 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import QueueAttributeFilterType, QueueAttributeNameType
 from .paginator import ListDeadLetterSourceQueuesPaginator, ListQueuesPaginator
 from .type_defs import (
+    CancelMessageMoveTaskResultTypeDef,
     ChangeMessageVisibilityBatchRequestEntryTypeDef,
     ChangeMessageVisibilityBatchResultTypeDef,
     CreateQueueResultTypeDef,
     DeleteMessageBatchRequestEntryTypeDef,
     DeleteMessageBatchResultTypeDef,
     EmptyResponseMetadataTypeDef,
     GetQueueAttributesResultTypeDef,
     GetQueueUrlResultTypeDef,
     ListDeadLetterSourceQueuesResultTypeDef,
+    ListMessageMoveTasksResultTypeDef,
     ListQueuesResultTypeDef,
     ListQueueTagsResultTypeDef,
     MessageAttributeValueTypeDef,
     MessageSystemAttributeValueTypeDef,
     ReceiveMessageResultTypeDef,
     SendMessageBatchRequestEntryTypeDef,
     SendMessageBatchResultTypeDef,
     SendMessageResultTypeDef,
+    StartMessageMoveTaskResultTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -68,14 +71,15 @@
     MessageNotInflight: Type[BotocoreClientError]
     OverLimit: Type[BotocoreClientError]
     PurgeQueueInProgress: Type[BotocoreClientError]
     QueueDeletedRecently: Type[BotocoreClientError]
     QueueDoesNotExist: Type[BotocoreClientError]
     QueueNameExists: Type[BotocoreClientError]
     ReceiptHandleIsInvalid: Type[BotocoreClientError]
+    ResourceNotFoundException: Type[BotocoreClientError]
     TooManyEntriesInBatchRequest: Type[BotocoreClientError]
     UnsupportedOperation: Type[BotocoreClientError]
 
 class SQSClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/)
@@ -104,14 +108,23 @@
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#can_paginate)
         """
+    async def cancel_message_move_task(
+        self, *, TaskHandle: str
+    ) -> CancelMessageMoveTaskResultTypeDef:
+        """
+        Cancels a specified message movement task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.cancel_message_move_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#cancel_message_move_task)
+        """
     async def change_message_visibility(
         self, *, QueueUrl: str, ReceiptHandle: str, VisibilityTimeout: int
     ) -> EmptyResponseMetadataTypeDef:
         """
         Changes the visibility timeout of a specified message in a queue to a new value.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.change_message_visibility)
@@ -162,15 +175,15 @@
         Deletes up to ten messages from the specified queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_message_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#delete_message_batch)
         """
     async def delete_queue(self, *, QueueUrl: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the queue specified by the `QueueUrl` , regardless of the queue's
+        Deletes the queue specified by the `QueueUrl`, regardless of the queue's
         contents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.delete_queue)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#delete_queue)
         """
     async def generate_presigned_url(
         self,
@@ -209,14 +222,24 @@
         """
         Returns a list of your queues that have the `RedrivePolicy` queue attribute
         configured with a dead-letter queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_dead_letter_source_queues)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_dead_letter_source_queues)
         """
+    async def list_message_move_tasks(
+        self, *, SourceArn: str, MaxResults: int = ...
+    ) -> ListMessageMoveTasksResultTypeDef:
+        """
+        Gets the most recent message movement tasks (up to 10) under a specific source
+        queue.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_message_move_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_message_move_tasks)
+        """
     async def list_queue_tags(self, *, QueueUrl: str) -> ListQueueTagsResultTypeDef:
         """
         List all cost allocation tags added to the specified Amazon SQS queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.list_queue_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#list_queue_tags)
         """
@@ -280,28 +303,40 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.send_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#send_message)
         """
     async def send_message_batch(
         self, *, QueueUrl: str, Entries: Sequence[SendMessageBatchRequestEntryTypeDef]
     ) -> SendMessageBatchResultTypeDef:
         """
-        Delivers up to ten messages to the specified queue.
+        You can use `SendMessageBatch` to send up to 10 messages to the specified queue
+        by assigning either identical or different values to each message (or by not
+        assigning values at all).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.send_message_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#send_message_batch)
         """
     async def set_queue_attributes(
         self, *, QueueUrl: str, Attributes: Mapping[QueueAttributeNameType, str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Sets the value of one or more queue attributes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.set_queue_attributes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#set_queue_attributes)
         """
+    async def start_message_move_task(
+        self, *, SourceArn: str, DestinationArn: str = ..., MaxNumberOfMessagesPerSecond: int = ...
+    ) -> StartMessageMoveTaskResultTypeDef:
+        """
+        Starts an asynchronous task to move messages from a specified source queue to a
+        specified destination queue.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.start_message_move_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/client/#start_message_move_task)
+        """
     async def tag_queue(
         self, *, QueueUrl: str, Tags: Mapping[str, str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Add cost allocation tags to the specified Amazon SQS queue.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Client.tag_queue)
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/literals.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -37,14 +37,15 @@
 ListDeadLetterSourceQueuesPaginatorName = Literal["list_dead_letter_source_queues"]
 ListQueuesPaginatorName = Literal["list_queues"]
 MessageSystemAttributeNameForSendsType = Literal["AWSTraceHeader"]
 MessageSystemAttributeNameType = Literal[
     "AWSTraceHeader",
     "ApproximateFirstReceiveTimestamp",
     "ApproximateReceiveCount",
+    "DeadLetterQueueSourceArn",
     "MessageDeduplicationId",
     "MessageGroupId",
     "SenderId",
     "SentTimestamp",
     "SequenceNumber",
 ]
 QueueAttributeFilterType = Literal[
@@ -162,14 +163,15 @@
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
@@ -248,14 +250,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -309,14 +313,15 @@
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
@@ -335,16 +340,19 @@
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
@@ -428,15 +436,17 @@
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/literals.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/literals.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -35,14 +35,15 @@
 ListDeadLetterSourceQueuesPaginatorName = Literal["list_dead_letter_source_queues"]
 ListQueuesPaginatorName = Literal["list_queues"]
 MessageSystemAttributeNameForSendsType = Literal["AWSTraceHeader"]
 MessageSystemAttributeNameType = Literal[
     "AWSTraceHeader",
     "ApproximateFirstReceiveTimestamp",
     "ApproximateReceiveCount",
+    "DeadLetterQueueSourceArn",
     "MessageDeduplicationId",
     "MessageGroupId",
     "SenderId",
     "SentTimestamp",
     "SequenceNumber",
 ]
 QueueAttributeFilterType = Literal[
@@ -160,14 +161,15 @@
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
@@ -246,14 +248,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -307,14 +311,15 @@
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
@@ -333,16 +338,19 @@
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
@@ -426,15 +434,17 @@
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/paginator.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("sqs") as client:
         client: SQSClient
 
         list_dead_letter_source_queues_paginator: ListDeadLetterSourceQueuesPaginator = client.get_paginator("list_dead_letter_source_queues")
         list_queues_paginator: ListQueuesPaginator = client.get_paginator("list_queues")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDeadLetterSourceQueuesResultTypeDef,
     ListQueuesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListDeadLetterSourceQueuesPaginator", "ListQueuesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,28 +49,28 @@
 class ListDeadLetterSourceQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListDeadLetterSourceQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listdeadlettersourcequeuespaginator)
     """
 
     def paginate(
-        self, *, QueueUrl: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueueUrl: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeadLetterSourceQueuesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListDeadLetterSourceQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listdeadlettersourcequeuespaginator)
         """
 
 
 class ListQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listqueuespaginator)
     """
 
     def paginate(
-        self, *, QueueNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueueNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueuesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listqueuespaginator)
         """
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/paginator.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("sqs") as client:
         client: SQSClient
 
         list_dead_letter_source_queues_paginator: ListDeadLetterSourceQueuesPaginator = client.get_paginator("list_dead_letter_source_queues")
         list_queues_paginator: ListQueuesPaginator = client.get_paginator("list_queues")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDeadLetterSourceQueuesResultTypeDef,
     ListQueuesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListDeadLetterSourceQueuesPaginator", "ListQueuesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,27 +46,27 @@
 class ListDeadLetterSourceQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListDeadLetterSourceQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listdeadlettersourcequeuespaginator)
     """
 
     def paginate(
-        self, *, QueueUrl: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueueUrl: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeadLetterSourceQueuesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListDeadLetterSourceQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listdeadlettersourcequeuespaginator)
         """
 
 class ListQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listqueuespaginator)
     """
 
     def paginate(
-        self, *, QueueNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueueNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueuesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Paginator.ListQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/paginators/#listqueuespaginator)
         """
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/service_resource.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/service_resource.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,15 +16,15 @@
         resource: SQSServiceResource
 
         my_message: sqs_resources.Message = resource.Message(...)
         my_queue: sqs_resources.Queue = resource.Queue(...)
 ```
 """
 import sys
-from typing import Awaitable, Dict, List, Mapping, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, Mapping, NoReturn, Sequence
 
 from .client import SQSClient
 from .literals import (
     MessageSystemAttributeNameType,
     QueueAttributeFilterType,
     QueueAttributeNameType,
 )
@@ -44,18 +44,14 @@
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
@@ -263,15 +259,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.change_message_visibility_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuechange_message_visibility_batch-method)
         """
 
     async def delete(self) -> None:
         """
-        Deletes the queue specified by the `QueueUrl` , regardless of the queue's
+        Deletes the queue specified by the `QueueUrl`, regardless of the queue's
         contents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.delete)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuedelete-method)
         """
 
     async def delete_messages(
@@ -363,15 +359,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuesend_message-method)
         """
 
     async def send_messages(
         self, *, Entries: Sequence[SendMessageBatchRequestEntryTypeDef]
     ) -> SendMessageBatchResultTypeDef:
         """
-        Delivers up to ten messages to the specified queue.
+        You can use `SendMessageBatch` to send up to 10 messages to the specified queue
+        by assigning either identical or different values to each message (or by not
+        assigning values at all).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.send_messages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuesend_messages-method)
         """
 
     async def set_attributes(self, *, Attributes: Mapping[QueueAttributeNameType, str]) -> None:
         """
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/service_resource.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/service_resource.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -16,15 +16,15 @@
         resource: SQSServiceResource
 
         my_message: sqs_resources.Message = resource.Message(...)
         my_queue: sqs_resources.Queue = resource.Queue(...)
 ```
 """
 import sys
-from typing import Awaitable, Dict, List, Mapping, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, Mapping, NoReturn, Sequence
 
 from .client import SQSClient
 from .literals import (
     MessageSystemAttributeNameType,
     QueueAttributeFilterType,
     QueueAttributeNameType,
 )
@@ -44,18 +44,14 @@
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
@@ -239,15 +235,15 @@
         Changes the visibility timeout of multiple messages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.change_message_visibility_batch)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuechange_message_visibility_batch-method)
         """
     async def delete(self) -> None:
         """
-        Deletes the queue specified by the `QueueUrl` , regardless of the queue's
+        Deletes the queue specified by the `QueueUrl`, regardless of the queue's
         contents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.delete)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuedelete-method)
         """
     async def delete_messages(
         self, *, Entries: Sequence[DeleteMessageBatchRequestEntryTypeDef]
@@ -330,15 +326,17 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.send_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuesend_message-method)
         """
     async def send_messages(
         self, *, Entries: Sequence[SendMessageBatchRequestEntryTypeDef]
     ) -> SendMessageBatchResultTypeDef:
         """
-        Delivers up to ten messages to the specified queue.
+        You can use `SendMessageBatch` to send up to 10 messages to the specified queue
+        by assigning either identical or different values to each message (or by not
+        assigning values at all).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS.Queue.send_messages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/service_resource/#queuesend_messages-method)
         """
     async def set_attributes(self, *, Attributes: Mapping[QueueAttributeNameType, str]) -> None:
         """
         Sets the value of one or more queue attributes.
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/type_defs.py` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -32,63 +32,67 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddPermissionRequestQueueAddPermissionTypeDef",
     "AddPermissionRequestRequestTypeDef",
     "BatchResultErrorEntryTypeDef",
+    "CancelMessageMoveTaskRequestRequestTypeDef",
+    "CancelMessageMoveTaskResultTypeDef",
     "ChangeMessageVisibilityBatchRequestEntryTypeDef",
     "ChangeMessageVisibilityBatchResultEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef",
     "ChangeMessageVisibilityRequestRequestTypeDef",
     "CreateQueueRequestRequestTypeDef",
     "CreateQueueRequestServiceResourceCreateQueueTypeDef",
+    "CreateQueueResultTypeDef",
     "DeleteMessageBatchRequestEntryTypeDef",
     "DeleteMessageBatchResultEntryTypeDef",
     "DeleteMessageRequestRequestTypeDef",
     "DeleteQueueRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetQueueAttributesRequestRequestTypeDef",
+    "GetQueueAttributesResultTypeDef",
     "GetQueueUrlRequestRequestTypeDef",
     "GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetQueueUrlResultTypeDef",
+    "ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
     "ListDeadLetterSourceQueuesRequestRequestTypeDef",
+    "ListDeadLetterSourceQueuesResultTypeDef",
+    "ListMessageMoveTasksRequestRequestTypeDef",
+    "ListMessageMoveTasksResultEntryTypeDef",
     "ListQueueTagsRequestRequestTypeDef",
+    "ListQueueTagsResultTypeDef",
+    "ListQueuesRequestListQueuesPaginateTypeDef",
     "ListQueuesRequestRequestTypeDef",
+    "ListQueuesResultTypeDef",
     "MessageAttributeValueTypeDef",
     "MessageSystemAttributeValueTypeDef",
+    "PaginatorConfigTypeDef",
     "PurgeQueueRequestRequestTypeDef",
-    "QueueMessageRequestTypeDef",
     "ReceiveMessageRequestQueueReceiveMessagesTypeDef",
     "ReceiveMessageRequestRequestTypeDef",
     "RemovePermissionRequestQueueRemovePermissionTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SendMessageBatchResultEntryTypeDef",
-    "ServiceResourceMessageRequestTypeDef",
-    "ServiceResourceQueueRequestTypeDef",
+    "SendMessageResultTypeDef",
     "SetQueueAttributesRequestQueueSetAttributesTypeDef",
     "SetQueueAttributesRequestRequestTypeDef",
+    "StartMessageMoveTaskRequestRequestTypeDef",
+    "StartMessageMoveTaskResultTypeDef",
     "TagQueueRequestRequestTypeDef",
     "UntagQueueRequestRequestTypeDef",
     "ChangeMessageVisibilityBatchRequestQueueChangeMessageVisibilityBatchTypeDef",
     "ChangeMessageVisibilityBatchRequestRequestTypeDef",
     "ChangeMessageVisibilityBatchResultTypeDef",
-    "CreateQueueResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetQueueAttributesResultTypeDef",
-    "GetQueueUrlResultTypeDef",
-    "ListDeadLetterSourceQueuesResultTypeDef",
-    "ListQueueTagsResultTypeDef",
-    "ListQueuesResultTypeDef",
-    "SendMessageResultTypeDef",
     "DeleteMessageBatchRequestQueueDeleteMessagesTypeDef",
     "DeleteMessageBatchRequestRequestTypeDef",
     "DeleteMessageBatchResultTypeDef",
-    "ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
-    "ListQueuesRequestListQueuesPaginateTypeDef",
+    "ListMessageMoveTasksResultTypeDef",
     "MessageTypeDef",
     "SendMessageBatchRequestEntryTypeDef",
     "SendMessageRequestQueueSendMessageTypeDef",
     "SendMessageRequestRequestTypeDef",
     "SendMessageBatchResultTypeDef",
     "ReceiveMessageResultTypeDef",
     "SendMessageBatchRequestQueueSendMessagesTypeDef",
@@ -133,14 +137,29 @@
 
 class BatchResultErrorEntryTypeDef(
     _RequiredBatchResultErrorEntryTypeDef, _OptionalBatchResultErrorEntryTypeDef
 ):
     pass
 
 
+CancelMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "CancelMessageMoveTaskRequestRequestTypeDef",
+    {
+        "TaskHandle": str,
+    },
+)
+
+CancelMessageMoveTaskResultTypeDef = TypedDict(
+    "CancelMessageMoveTaskResultTypeDef",
+    {
+        "ApproximateNumberOfMessagesMoved": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredChangeMessageVisibilityBatchRequestEntryTypeDef = TypedDict(
     "_RequiredChangeMessageVisibilityBatchRequestEntryTypeDef",
     {
         "Id": str,
         "ReceiptHandle": str,
     },
 )
@@ -163,25 +182,14 @@
 ChangeMessageVisibilityBatchResultEntryTypeDef = TypedDict(
     "ChangeMessageVisibilityBatchResultEntryTypeDef",
     {
         "Id": str,
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
 ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef = TypedDict(
     "ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef",
     {
         "VisibilityTimeout": int,
     },
 )
 
@@ -235,14 +243,22 @@
 class CreateQueueRequestServiceResourceCreateQueueTypeDef(
     _RequiredCreateQueueRequestServiceResourceCreateQueueTypeDef,
     _OptionalCreateQueueRequestServiceResourceCreateQueueTypeDef,
 ):
     pass
 
 
+CreateQueueResultTypeDef = TypedDict(
+    "CreateQueueResultTypeDef",
+    {
+        "QueueUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMessageBatchRequestEntryTypeDef = TypedDict(
     "DeleteMessageBatchRequestEntryTypeDef",
     {
         "Id": str,
         "ReceiptHandle": str,
     },
 )
@@ -265,14 +281,21 @@
 DeleteQueueRequestRequestTypeDef = TypedDict(
     "DeleteQueueRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetQueueAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredGetQueueAttributesRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 _OptionalGetQueueAttributesRequestRequestTypeDef = TypedDict(
@@ -287,14 +310,22 @@
 class GetQueueAttributesRequestRequestTypeDef(
     _RequiredGetQueueAttributesRequestRequestTypeDef,
     _OptionalGetQueueAttributesRequestRequestTypeDef,
 ):
     pass
 
 
+GetQueueAttributesResultTypeDef = TypedDict(
+    "GetQueueAttributesResultTypeDef",
+    {
+        "Attributes": Dict[QueueAttributeNameType, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetQueueUrlRequestRequestTypeDef = TypedDict(
     "_RequiredGetQueueUrlRequestRequestTypeDef",
     {
         "QueueName": str,
     },
 )
 _OptionalGetQueueUrlRequestRequestTypeDef = TypedDict(
@@ -330,24 +361,44 @@
 class GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef(
     _RequiredGetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
     _OptionalGetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetQueueUrlResultTypeDef = TypedDict(
+    "GetQueueUrlResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "QueueUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
+    "_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
+    {
+        "QueueUrl": str,
+    },
+)
+_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
+    "_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef(
+    _RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
+    _OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeadLetterSourceQueuesRequestRequestTypeDef = TypedDict(
     "_RequiredListDeadLetterSourceQueuesRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 _OptionalListDeadLetterSourceQueuesRequestRequestTypeDef = TypedDict(
@@ -363,31 +414,104 @@
 class ListDeadLetterSourceQueuesRequestRequestTypeDef(
     _RequiredListDeadLetterSourceQueuesRequestRequestTypeDef,
     _OptionalListDeadLetterSourceQueuesRequestRequestTypeDef,
 ):
     pass
 
 
+ListDeadLetterSourceQueuesResultTypeDef = TypedDict(
+    "ListDeadLetterSourceQueuesResultTypeDef",
+    {
+        "queueUrls": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListMessageMoveTasksRequestRequestTypeDef = TypedDict(
+    "_RequiredListMessageMoveTasksRequestRequestTypeDef",
+    {
+        "SourceArn": str,
+    },
+)
+_OptionalListMessageMoveTasksRequestRequestTypeDef = TypedDict(
+    "_OptionalListMessageMoveTasksRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListMessageMoveTasksRequestRequestTypeDef(
+    _RequiredListMessageMoveTasksRequestRequestTypeDef,
+    _OptionalListMessageMoveTasksRequestRequestTypeDef,
+):
+    pass
+
+
+ListMessageMoveTasksResultEntryTypeDef = TypedDict(
+    "ListMessageMoveTasksResultEntryTypeDef",
+    {
+        "TaskHandle": str,
+        "Status": str,
+        "SourceArn": str,
+        "DestinationArn": str,
+        "MaxNumberOfMessagesPerSecond": int,
+        "ApproximateNumberOfMessagesMoved": int,
+        "ApproximateNumberOfMessagesToMove": int,
+        "FailureReason": str,
+        "StartedTimestamp": int,
+    },
+    total=False,
+)
+
 ListQueueTagsRequestRequestTypeDef = TypedDict(
     "ListQueueTagsRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 
+ListQueueTagsResultTypeDef = TypedDict(
+    "ListQueueTagsResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
+    "ListQueuesRequestListQueuesPaginateTypeDef",
+    {
+        "QueueNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueuesRequestRequestTypeDef = TypedDict(
     "ListQueuesRequestRequestTypeDef",
     {
         "QueueNamePrefix": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListQueuesResultTypeDef = TypedDict(
+    "ListQueuesResultTypeDef",
+    {
+        "QueueUrls": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMessageAttributeValueTypeDef = TypedDict(
     "_RequiredMessageAttributeValueTypeDef",
     {
         "DataType": str,
     },
 )
 _OptionalMessageAttributeValueTypeDef = TypedDict(
@@ -428,25 +552,28 @@
 
 class MessageSystemAttributeValueTypeDef(
     _RequiredMessageSystemAttributeValueTypeDef, _OptionalMessageSystemAttributeValueTypeDef
 ):
     pass
 
 
-PurgeQueueRequestRequestTypeDef = TypedDict(
-    "PurgeQueueRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "QueueUrl": str,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-QueueMessageRequestTypeDef = TypedDict(
-    "QueueMessageRequestTypeDef",
+PurgeQueueRequestRequestTypeDef = TypedDict(
+    "PurgeQueueRequestRequestTypeDef",
     {
-        "receipt_handle": str,
+        "QueueUrl": str,
     },
 )
 
 ReceiveMessageRequestQueueReceiveMessagesTypeDef = TypedDict(
     "ReceiveMessageRequestQueueReceiveMessagesTypeDef",
     {
         "AttributeNames": Sequence[QueueAttributeFilterType],
@@ -496,14 +623,25 @@
     "RemovePermissionRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Label": str,
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
 _RequiredSendMessageBatchResultEntryTypeDef = TypedDict(
     "_RequiredSendMessageBatchResultEntryTypeDef",
     {
         "Id": str,
         "MessageId": str,
         "MD5OfMessageBody": str,
     },
@@ -521,26 +659,23 @@
 
 class SendMessageBatchResultEntryTypeDef(
     _RequiredSendMessageBatchResultEntryTypeDef, _OptionalSendMessageBatchResultEntryTypeDef
 ):
     pass
 
 
-ServiceResourceMessageRequestTypeDef = TypedDict(
-    "ServiceResourceMessageRequestTypeDef",
-    {
-        "queue_url": str,
-        "receipt_handle": str,
-    },
-)
-
-ServiceResourceQueueRequestTypeDef = TypedDict(
-    "ServiceResourceQueueRequestTypeDef",
+SendMessageResultTypeDef = TypedDict(
+    "SendMessageResultTypeDef",
     {
-        "url": str,
+        "MD5OfMessageBody": str,
+        "MD5OfMessageAttributes": str,
+        "MD5OfMessageSystemAttributes": str,
+        "MessageId": str,
+        "SequenceNumber": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetQueueAttributesRequestQueueSetAttributesTypeDef = TypedDict(
     "SetQueueAttributesRequestQueueSetAttributesTypeDef",
     {
         "Attributes": Mapping[QueueAttributeNameType, str],
@@ -551,14 +686,45 @@
     "SetQueueAttributesRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Attributes": Mapping[QueueAttributeNameType, str],
     },
 )
 
+_RequiredStartMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartMessageMoveTaskRequestRequestTypeDef",
+    {
+        "SourceArn": str,
+    },
+)
+_OptionalStartMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartMessageMoveTaskRequestRequestTypeDef",
+    {
+        "DestinationArn": str,
+        "MaxNumberOfMessagesPerSecond": int,
+    },
+    total=False,
+)
+
+
+class StartMessageMoveTaskRequestRequestTypeDef(
+    _RequiredStartMessageMoveTaskRequestRequestTypeDef,
+    _OptionalStartMessageMoveTaskRequestRequestTypeDef,
+):
+    pass
+
+
+StartMessageMoveTaskResultTypeDef = TypedDict(
+    "StartMessageMoveTaskResultTypeDef",
+    {
+        "TaskHandle": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagQueueRequestRequestTypeDef = TypedDict(
     "TagQueueRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -587,84 +753,15 @@
 )
 
 ChangeMessageVisibilityBatchResultTypeDef = TypedDict(
     "ChangeMessageVisibilityBatchResultTypeDef",
     {
         "Successful": List[ChangeMessageVisibilityBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQueueResultTypeDef = TypedDict(
-    "CreateQueueResultTypeDef",
-    {
-        "QueueUrl": str,
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
-GetQueueAttributesResultTypeDef = TypedDict(
-    "GetQueueAttributesResultTypeDef",
-    {
-        "Attributes": Dict[QueueAttributeNameType, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQueueUrlResultTypeDef = TypedDict(
-    "GetQueueUrlResultTypeDef",
-    {
-        "QueueUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeadLetterSourceQueuesResultTypeDef = TypedDict(
-    "ListDeadLetterSourceQueuesResultTypeDef",
-    {
-        "queueUrls": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueueTagsResultTypeDef = TypedDict(
-    "ListQueueTagsResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueuesResultTypeDef = TypedDict(
-    "ListQueuesResultTypeDef",
-    {
-        "QueueUrls": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendMessageResultTypeDef = TypedDict(
-    "SendMessageResultTypeDef",
-    {
-        "MD5OfMessageBody": str,
-        "MD5OfMessageAttributes": str,
-        "MD5OfMessageSystemAttributes": str,
-        "MessageId": str,
-        "SequenceNumber": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMessageBatchRequestQueueDeleteMessagesTypeDef = TypedDict(
     "DeleteMessageBatchRequestQueueDeleteMessagesTypeDef",
     {
         "Entries": Sequence[DeleteMessageBatchRequestEntryTypeDef],
@@ -680,47 +777,24 @@
 )
 
 DeleteMessageBatchResultTypeDef = TypedDict(
     "DeleteMessageBatchResultTypeDef",
     {
         "Successful": List[DeleteMessageBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
-    "_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
-    {
-        "QueueUrl": str,
-    },
-)
-_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
-    "_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef(
-    _RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-    _OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-):
-    pass
-
-
-ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
-    "ListQueuesRequestListQueuesPaginateTypeDef",
+ListMessageMoveTasksResultTypeDef = TypedDict(
+    "ListMessageMoveTasksResultTypeDef",
     {
-        "QueueNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Results": List[ListMessageMoveTasksResultEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 MessageTypeDef = TypedDict(
     "MessageTypeDef",
     {
         "MessageId": str,
         "ReceiptHandle": str,
@@ -818,23 +892,23 @@
 
 
 SendMessageBatchResultTypeDef = TypedDict(
     "SendMessageBatchResultTypeDef",
     {
         "Successful": List[SendMessageBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReceiveMessageResultTypeDef = TypedDict(
     "ReceiveMessageResultTypeDef",
     {
         "Messages": List[MessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendMessageBatchRequestQueueSendMessagesTypeDef = TypedDict(
     "SendMessageBatchRequestQueueSendMessagesTypeDef",
     {
         "Entries": Sequence[SendMessageBatchRequestEntryTypeDef],
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs/type_defs.pyi` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs/type_defs.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -31,63 +31,67 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddPermissionRequestQueueAddPermissionTypeDef",
     "AddPermissionRequestRequestTypeDef",
     "BatchResultErrorEntryTypeDef",
+    "CancelMessageMoveTaskRequestRequestTypeDef",
+    "CancelMessageMoveTaskResultTypeDef",
     "ChangeMessageVisibilityBatchRequestEntryTypeDef",
     "ChangeMessageVisibilityBatchResultEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef",
     "ChangeMessageVisibilityRequestRequestTypeDef",
     "CreateQueueRequestRequestTypeDef",
     "CreateQueueRequestServiceResourceCreateQueueTypeDef",
+    "CreateQueueResultTypeDef",
     "DeleteMessageBatchRequestEntryTypeDef",
     "DeleteMessageBatchResultEntryTypeDef",
     "DeleteMessageRequestRequestTypeDef",
     "DeleteQueueRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetQueueAttributesRequestRequestTypeDef",
+    "GetQueueAttributesResultTypeDef",
     "GetQueueUrlRequestRequestTypeDef",
     "GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetQueueUrlResultTypeDef",
+    "ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
     "ListDeadLetterSourceQueuesRequestRequestTypeDef",
+    "ListDeadLetterSourceQueuesResultTypeDef",
+    "ListMessageMoveTasksRequestRequestTypeDef",
+    "ListMessageMoveTasksResultEntryTypeDef",
     "ListQueueTagsRequestRequestTypeDef",
+    "ListQueueTagsResultTypeDef",
+    "ListQueuesRequestListQueuesPaginateTypeDef",
     "ListQueuesRequestRequestTypeDef",
+    "ListQueuesResultTypeDef",
     "MessageAttributeValueTypeDef",
     "MessageSystemAttributeValueTypeDef",
+    "PaginatorConfigTypeDef",
     "PurgeQueueRequestRequestTypeDef",
-    "QueueMessageRequestTypeDef",
     "ReceiveMessageRequestQueueReceiveMessagesTypeDef",
     "ReceiveMessageRequestRequestTypeDef",
     "RemovePermissionRequestQueueRemovePermissionTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SendMessageBatchResultEntryTypeDef",
-    "ServiceResourceMessageRequestTypeDef",
-    "ServiceResourceQueueRequestTypeDef",
+    "SendMessageResultTypeDef",
     "SetQueueAttributesRequestQueueSetAttributesTypeDef",
     "SetQueueAttributesRequestRequestTypeDef",
+    "StartMessageMoveTaskRequestRequestTypeDef",
+    "StartMessageMoveTaskResultTypeDef",
     "TagQueueRequestRequestTypeDef",
     "UntagQueueRequestRequestTypeDef",
     "ChangeMessageVisibilityBatchRequestQueueChangeMessageVisibilityBatchTypeDef",
     "ChangeMessageVisibilityBatchRequestRequestTypeDef",
     "ChangeMessageVisibilityBatchResultTypeDef",
-    "CreateQueueResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetQueueAttributesResultTypeDef",
-    "GetQueueUrlResultTypeDef",
-    "ListDeadLetterSourceQueuesResultTypeDef",
-    "ListQueueTagsResultTypeDef",
-    "ListQueuesResultTypeDef",
-    "SendMessageResultTypeDef",
     "DeleteMessageBatchRequestQueueDeleteMessagesTypeDef",
     "DeleteMessageBatchRequestRequestTypeDef",
     "DeleteMessageBatchResultTypeDef",
-    "ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
-    "ListQueuesRequestListQueuesPaginateTypeDef",
+    "ListMessageMoveTasksResultTypeDef",
     "MessageTypeDef",
     "SendMessageBatchRequestEntryTypeDef",
     "SendMessageRequestQueueSendMessageTypeDef",
     "SendMessageRequestRequestTypeDef",
     "SendMessageBatchResultTypeDef",
     "ReceiveMessageResultTypeDef",
     "SendMessageBatchRequestQueueSendMessagesTypeDef",
@@ -130,14 +134,29 @@
 )
 
 class BatchResultErrorEntryTypeDef(
     _RequiredBatchResultErrorEntryTypeDef, _OptionalBatchResultErrorEntryTypeDef
 ):
     pass
 
+CancelMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "CancelMessageMoveTaskRequestRequestTypeDef",
+    {
+        "TaskHandle": str,
+    },
+)
+
+CancelMessageMoveTaskResultTypeDef = TypedDict(
+    "CancelMessageMoveTaskResultTypeDef",
+    {
+        "ApproximateNumberOfMessagesMoved": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredChangeMessageVisibilityBatchRequestEntryTypeDef = TypedDict(
     "_RequiredChangeMessageVisibilityBatchRequestEntryTypeDef",
     {
         "Id": str,
         "ReceiptHandle": str,
     },
 )
@@ -158,25 +177,14 @@
 ChangeMessageVisibilityBatchResultEntryTypeDef = TypedDict(
     "ChangeMessageVisibilityBatchResultEntryTypeDef",
     {
         "Id": str,
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
 ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef = TypedDict(
     "ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef",
     {
         "VisibilityTimeout": int,
     },
 )
 
@@ -226,14 +234,22 @@
 
 class CreateQueueRequestServiceResourceCreateQueueTypeDef(
     _RequiredCreateQueueRequestServiceResourceCreateQueueTypeDef,
     _OptionalCreateQueueRequestServiceResourceCreateQueueTypeDef,
 ):
     pass
 
+CreateQueueResultTypeDef = TypedDict(
+    "CreateQueueResultTypeDef",
+    {
+        "QueueUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMessageBatchRequestEntryTypeDef = TypedDict(
     "DeleteMessageBatchRequestEntryTypeDef",
     {
         "Id": str,
         "ReceiptHandle": str,
     },
 )
@@ -256,14 +272,21 @@
 DeleteQueueRequestRequestTypeDef = TypedDict(
     "DeleteQueueRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetQueueAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredGetQueueAttributesRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 _OptionalGetQueueAttributesRequestRequestTypeDef = TypedDict(
@@ -276,14 +299,22 @@
 
 class GetQueueAttributesRequestRequestTypeDef(
     _RequiredGetQueueAttributesRequestRequestTypeDef,
     _OptionalGetQueueAttributesRequestRequestTypeDef,
 ):
     pass
 
+GetQueueAttributesResultTypeDef = TypedDict(
+    "GetQueueAttributesResultTypeDef",
+    {
+        "Attributes": Dict[QueueAttributeNameType, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetQueueUrlRequestRequestTypeDef = TypedDict(
     "_RequiredGetQueueUrlRequestRequestTypeDef",
     {
         "QueueName": str,
     },
 )
 _OptionalGetQueueUrlRequestRequestTypeDef = TypedDict(
@@ -315,24 +346,42 @@
 
 class GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef(
     _RequiredGetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
     _OptionalGetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetQueueUrlResultTypeDef = TypedDict(
+    "GetQueueUrlResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "QueueUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
+    "_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
+    {
+        "QueueUrl": str,
+    },
+)
+_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
+    "_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef(
+    _RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
+    _OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeadLetterSourceQueuesRequestRequestTypeDef = TypedDict(
     "_RequiredListDeadLetterSourceQueuesRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 _OptionalListDeadLetterSourceQueuesRequestRequestTypeDef = TypedDict(
@@ -346,31 +395,102 @@
 
 class ListDeadLetterSourceQueuesRequestRequestTypeDef(
     _RequiredListDeadLetterSourceQueuesRequestRequestTypeDef,
     _OptionalListDeadLetterSourceQueuesRequestRequestTypeDef,
 ):
     pass
 
+ListDeadLetterSourceQueuesResultTypeDef = TypedDict(
+    "ListDeadLetterSourceQueuesResultTypeDef",
+    {
+        "queueUrls": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListMessageMoveTasksRequestRequestTypeDef = TypedDict(
+    "_RequiredListMessageMoveTasksRequestRequestTypeDef",
+    {
+        "SourceArn": str,
+    },
+)
+_OptionalListMessageMoveTasksRequestRequestTypeDef = TypedDict(
+    "_OptionalListMessageMoveTasksRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListMessageMoveTasksRequestRequestTypeDef(
+    _RequiredListMessageMoveTasksRequestRequestTypeDef,
+    _OptionalListMessageMoveTasksRequestRequestTypeDef,
+):
+    pass
+
+ListMessageMoveTasksResultEntryTypeDef = TypedDict(
+    "ListMessageMoveTasksResultEntryTypeDef",
+    {
+        "TaskHandle": str,
+        "Status": str,
+        "SourceArn": str,
+        "DestinationArn": str,
+        "MaxNumberOfMessagesPerSecond": int,
+        "ApproximateNumberOfMessagesMoved": int,
+        "ApproximateNumberOfMessagesToMove": int,
+        "FailureReason": str,
+        "StartedTimestamp": int,
+    },
+    total=False,
+)
+
 ListQueueTagsRequestRequestTypeDef = TypedDict(
     "ListQueueTagsRequestRequestTypeDef",
     {
         "QueueUrl": str,
     },
 )
 
+ListQueueTagsResultTypeDef = TypedDict(
+    "ListQueueTagsResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
+    "ListQueuesRequestListQueuesPaginateTypeDef",
+    {
+        "QueueNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueuesRequestRequestTypeDef = TypedDict(
     "ListQueuesRequestRequestTypeDef",
     {
         "QueueNamePrefix": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListQueuesResultTypeDef = TypedDict(
+    "ListQueuesResultTypeDef",
+    {
+        "QueueUrls": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMessageAttributeValueTypeDef = TypedDict(
     "_RequiredMessageAttributeValueTypeDef",
     {
         "DataType": str,
     },
 )
 _OptionalMessageAttributeValueTypeDef = TypedDict(
@@ -407,25 +527,28 @@
 )
 
 class MessageSystemAttributeValueTypeDef(
     _RequiredMessageSystemAttributeValueTypeDef, _OptionalMessageSystemAttributeValueTypeDef
 ):
     pass
 
-PurgeQueueRequestRequestTypeDef = TypedDict(
-    "PurgeQueueRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "QueueUrl": str,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-QueueMessageRequestTypeDef = TypedDict(
-    "QueueMessageRequestTypeDef",
+PurgeQueueRequestRequestTypeDef = TypedDict(
+    "PurgeQueueRequestRequestTypeDef",
     {
-        "receipt_handle": str,
+        "QueueUrl": str,
     },
 )
 
 ReceiveMessageRequestQueueReceiveMessagesTypeDef = TypedDict(
     "ReceiveMessageRequestQueueReceiveMessagesTypeDef",
     {
         "AttributeNames": Sequence[QueueAttributeFilterType],
@@ -473,14 +596,25 @@
     "RemovePermissionRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Label": str,
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
 _RequiredSendMessageBatchResultEntryTypeDef = TypedDict(
     "_RequiredSendMessageBatchResultEntryTypeDef",
     {
         "Id": str,
         "MessageId": str,
         "MD5OfMessageBody": str,
     },
@@ -496,26 +630,23 @@
 )
 
 class SendMessageBatchResultEntryTypeDef(
     _RequiredSendMessageBatchResultEntryTypeDef, _OptionalSendMessageBatchResultEntryTypeDef
 ):
     pass
 
-ServiceResourceMessageRequestTypeDef = TypedDict(
-    "ServiceResourceMessageRequestTypeDef",
-    {
-        "queue_url": str,
-        "receipt_handle": str,
-    },
-)
-
-ServiceResourceQueueRequestTypeDef = TypedDict(
-    "ServiceResourceQueueRequestTypeDef",
+SendMessageResultTypeDef = TypedDict(
+    "SendMessageResultTypeDef",
     {
-        "url": str,
+        "MD5OfMessageBody": str,
+        "MD5OfMessageAttributes": str,
+        "MD5OfMessageSystemAttributes": str,
+        "MessageId": str,
+        "SequenceNumber": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetQueueAttributesRequestQueueSetAttributesTypeDef = TypedDict(
     "SetQueueAttributesRequestQueueSetAttributesTypeDef",
     {
         "Attributes": Mapping[QueueAttributeNameType, str],
@@ -526,14 +657,43 @@
     "SetQueueAttributesRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Attributes": Mapping[QueueAttributeNameType, str],
     },
 )
 
+_RequiredStartMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartMessageMoveTaskRequestRequestTypeDef",
+    {
+        "SourceArn": str,
+    },
+)
+_OptionalStartMessageMoveTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartMessageMoveTaskRequestRequestTypeDef",
+    {
+        "DestinationArn": str,
+        "MaxNumberOfMessagesPerSecond": int,
+    },
+    total=False,
+)
+
+class StartMessageMoveTaskRequestRequestTypeDef(
+    _RequiredStartMessageMoveTaskRequestRequestTypeDef,
+    _OptionalStartMessageMoveTaskRequestRequestTypeDef,
+):
+    pass
+
+StartMessageMoveTaskResultTypeDef = TypedDict(
+    "StartMessageMoveTaskResultTypeDef",
+    {
+        "TaskHandle": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagQueueRequestRequestTypeDef = TypedDict(
     "TagQueueRequestRequestTypeDef",
     {
         "QueueUrl": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -562,84 +722,15 @@
 )
 
 ChangeMessageVisibilityBatchResultTypeDef = TypedDict(
     "ChangeMessageVisibilityBatchResultTypeDef",
     {
         "Successful": List[ChangeMessageVisibilityBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQueueResultTypeDef = TypedDict(
-    "CreateQueueResultTypeDef",
-    {
-        "QueueUrl": str,
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
-GetQueueAttributesResultTypeDef = TypedDict(
-    "GetQueueAttributesResultTypeDef",
-    {
-        "Attributes": Dict[QueueAttributeNameType, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQueueUrlResultTypeDef = TypedDict(
-    "GetQueueUrlResultTypeDef",
-    {
-        "QueueUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeadLetterSourceQueuesResultTypeDef = TypedDict(
-    "ListDeadLetterSourceQueuesResultTypeDef",
-    {
-        "queueUrls": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueueTagsResultTypeDef = TypedDict(
-    "ListQueueTagsResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueuesResultTypeDef = TypedDict(
-    "ListQueuesResultTypeDef",
-    {
-        "QueueUrls": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendMessageResultTypeDef = TypedDict(
-    "SendMessageResultTypeDef",
-    {
-        "MD5OfMessageBody": str,
-        "MD5OfMessageAttributes": str,
-        "MD5OfMessageSystemAttributes": str,
-        "MessageId": str,
-        "SequenceNumber": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMessageBatchRequestQueueDeleteMessagesTypeDef = TypedDict(
     "DeleteMessageBatchRequestQueueDeleteMessagesTypeDef",
     {
         "Entries": Sequence[DeleteMessageBatchRequestEntryTypeDef],
@@ -655,46 +746,25 @@
 )
 
 DeleteMessageBatchResultTypeDef = TypedDict(
     "DeleteMessageBatchResultTypeDef",
     {
         "Successful": List[DeleteMessageBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
-    "_RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
+ListMessageMoveTasksResultTypeDef = TypedDict(
+    "ListMessageMoveTasksResultTypeDef",
     {
-        "QueueUrl": str,
+        "Results": List[ListMessageMoveTasksResultEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef = TypedDict(
-    "_OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef(
-    _RequiredListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-    _OptionalListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-):
-    pass
-
-ListQueuesRequestListQueuesPaginateTypeDef = TypedDict(
-    "ListQueuesRequestListQueuesPaginateTypeDef",
-    {
-        "QueueNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 MessageTypeDef = TypedDict(
     "MessageTypeDef",
     {
         "MessageId": str,
         "ReceiptHandle": str,
         "MD5OfBody": str,
@@ -785,23 +855,23 @@
     pass
 
 SendMessageBatchResultTypeDef = TypedDict(
     "SendMessageBatchResultTypeDef",
     {
         "Successful": List[SendMessageBatchResultEntryTypeDef],
         "Failed": List[BatchResultErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReceiveMessageResultTypeDef = TypedDict(
     "ReceiveMessageResultTypeDef",
     {
         "Messages": List[MessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendMessageBatchRequestQueueSendMessagesTypeDef = TypedDict(
     "SendMessageBatchRequestQueueSendMessagesTypeDef",
     {
         "Entries": Sequence[SendMessageBatchRequestEntryTypeDef],
```

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/PKG-INFO` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sqs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SQS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SQS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sqs"></a>
 
 # types-aiobotocore-sqs
 
 [![PyPI - types-aiobotocore-sqs](https://img.shields.io/pypi/v/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sqs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sqs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sqs?color=blue)](https://pypistats.org/packages/types-aiobotocore-sqs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SQS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
+[aiobotocore.SQS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html#SQS)
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
 [types-aiobotocore-sqs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sqs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -388,63 +388,67 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sqs.type_defs import (
     AddPermissionRequestQueueAddPermissionTypeDef,
     AddPermissionRequestRequestTypeDef,
     BatchResultErrorEntryTypeDef,
+    CancelMessageMoveTaskRequestRequestTypeDef,
+    CancelMessageMoveTaskResultTypeDef,
     ChangeMessageVisibilityBatchRequestEntryTypeDef,
     ChangeMessageVisibilityBatchResultEntryTypeDef,
-    ResponseMetadataTypeDef,
     ChangeMessageVisibilityRequestMessageChangeVisibilityTypeDef,
     ChangeMessageVisibilityRequestRequestTypeDef,
     CreateQueueRequestRequestTypeDef,
     CreateQueueRequestServiceResourceCreateQueueTypeDef,
+    CreateQueueResultTypeDef,
     DeleteMessageBatchRequestEntryTypeDef,
     DeleteMessageBatchResultEntryTypeDef,
     DeleteMessageRequestRequestTypeDef,
     DeleteQueueRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetQueueAttributesRequestRequestTypeDef,
+    GetQueueAttributesResultTypeDef,
     GetQueueUrlRequestRequestTypeDef,
     GetQueueUrlRequestServiceResourceGetQueueByNameTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueueUrlResultTypeDef,
+    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
     ListDeadLetterSourceQueuesRequestRequestTypeDef,
+    ListDeadLetterSourceQueuesResultTypeDef,
+    ListMessageMoveTasksRequestRequestTypeDef,
+    ListMessageMoveTasksResultEntryTypeDef,
     ListQueueTagsRequestRequestTypeDef,
+    ListQueueTagsResultTypeDef,
+    ListQueuesRequestListQueuesPaginateTypeDef,
     ListQueuesRequestRequestTypeDef,
+    ListQueuesResultTypeDef,
     MessageAttributeValueTypeDef,
     MessageSystemAttributeValueTypeDef,
+    PaginatorConfigTypeDef,
     PurgeQueueRequestRequestTypeDef,
-    QueueMessageRequestTypeDef,
     ReceiveMessageRequestQueueReceiveMessagesTypeDef,
     ReceiveMessageRequestRequestTypeDef,
     RemovePermissionRequestQueueRemovePermissionTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendMessageBatchResultEntryTypeDef,
-    ServiceResourceMessageRequestTypeDef,
-    ServiceResourceQueueRequestTypeDef,
+    SendMessageResultTypeDef,
     SetQueueAttributesRequestQueueSetAttributesTypeDef,
     SetQueueAttributesRequestRequestTypeDef,
+    StartMessageMoveTaskRequestRequestTypeDef,
+    StartMessageMoveTaskResultTypeDef,
     TagQueueRequestRequestTypeDef,
     UntagQueueRequestRequestTypeDef,
     ChangeMessageVisibilityBatchRequestQueueChangeMessageVisibilityBatchTypeDef,
     ChangeMessageVisibilityBatchRequestRequestTypeDef,
     ChangeMessageVisibilityBatchResultTypeDef,
-    CreateQueueResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetQueueAttributesResultTypeDef,
-    GetQueueUrlResultTypeDef,
-    ListDeadLetterSourceQueuesResultTypeDef,
-    ListQueueTagsResultTypeDef,
-    ListQueuesResultTypeDef,
-    SendMessageResultTypeDef,
     DeleteMessageBatchRequestQueueDeleteMessagesTypeDef,
     DeleteMessageBatchRequestRequestTypeDef,
     DeleteMessageBatchResultTypeDef,
-    ListDeadLetterSourceQueuesRequestListDeadLetterSourceQueuesPaginateTypeDef,
-    ListQueuesRequestListQueuesPaginateTypeDef,
+    ListMessageMoveTasksResultTypeDef,
     MessageTypeDef,
     SendMessageBatchRequestEntryTypeDef,
     SendMessageRequestQueueSendMessageTypeDef,
     SendMessageRequestRequestTypeDef,
     SendMessageBatchResultTypeDef,
     ReceiveMessageResultTypeDef,
     SendMessageBatchRequestQueueSendMessagesTypeDef,
@@ -459,43 +463,43 @@
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

### Comparing `types-aiobotocore-sqs-2.5.0.post1/types_aiobotocore_sqs.egg-info/SOURCES.txt` & `types-aiobotocore-sqs-2.5.1/types_aiobotocore_sqs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

