# Comparing `tmp/types-aiobotocore-qldb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-qldb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-qldb-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-qldb-2.5.1.tar", last modified: Wed Jun 28 01:44:00 2023, max compression
```

## Comparing `types-aiobotocore-qldb-2.5.0.post1.tar` & `types-aiobotocore-qldb-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.711514 types-aiobotocore-qldb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14009 2023-03-11 12:27:08.711514 types-aiobotocore-qldb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12450 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.711514 types-aiobotocore-qldb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.707514 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      417 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      920 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16731 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16703 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8329 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8327 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17773 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17746 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:13.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.711514 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14009 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      683 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-03-11 12:27:08.000000 types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.714195 types-aiobotocore-qldb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13998 2023-06-28 01:44:00.714195 types-aiobotocore-qldb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12445 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:00.714195 types-aiobotocore-qldb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.710195 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/
+-rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16643 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16615 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8538 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8536 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    17809 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17782 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:59.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.714195 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13998 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      683 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 01:44:00.000000 types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-qldb-2.5.0.post1/LICENSE` & `types-aiobotocore-qldb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-qldb-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-qldb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.QLDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.QLDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-qldb"></a>
 
 # types-aiobotocore-qldb
 
 [![PyPI - types-aiobotocore-qldb](https://img.shields.io/pypi/v/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-qldb?color=blue)](https://pypistats.org/packages/types-aiobotocore-qldb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.QLDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
+[aiobotocore.QLDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
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
 [types-aiobotocore-qldb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,42 +296,42 @@
 
 `types_aiobotocore_qldb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_qldb.type_defs import (
     CancelJournalKinesisStreamRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJournalKinesisStreamResponseTypeDef,
     CreateLedgerRequestRequestTypeDef,
+    CreateLedgerResponseTypeDef,
     DeleteLedgerRequestRequestTypeDef,
     DescribeJournalKinesisStreamRequestRequestTypeDef,
     DescribeJournalS3ExportRequestRequestTypeDef,
     DescribeLedgerRequestRequestTypeDef,
     LedgerEncryptionDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportJournalToS3ResponseTypeDef,
     ValueHolderTypeDef,
     GetDigestRequestRequestTypeDef,
     KinesisConfigurationTypeDef,
     LedgerSummaryTypeDef,
     ListJournalKinesisStreamsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsRequestRequestTypeDef,
     ListLedgersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3EncryptionConfigurationTypeDef,
+    StreamJournalToKinesisResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLedgerPermissionsModeRequestRequestTypeDef,
-    UpdateLedgerRequestRequestTypeDef,
-    CancelJournalKinesisStreamResponseTypeDef,
-    CreateLedgerResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportJournalToS3ResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StreamJournalToKinesisResponseTypeDef,
     UpdateLedgerPermissionsModeResponseTypeDef,
+    UpdateLedgerRequestRequestTypeDef,
     DescribeLedgerResponseTypeDef,
     UpdateLedgerResponseTypeDef,
     GetBlockRequestRequestTypeDef,
     GetBlockResponseTypeDef,
     GetDigestResponseTypeDef,
     GetRevisionRequestRequestTypeDef,
     GetRevisionResponseTypeDef,
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/README.md` & `types-aiobotocore-qldb-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-qldb"></a>
 
 # types-aiobotocore-qldb
 
 [![PyPI - types-aiobotocore-qldb](https://img.shields.io/pypi/v/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-qldb?color=blue)](https://pypistats.org/packages/types-aiobotocore-qldb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.QLDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
+[aiobotocore.QLDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
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
 [types-aiobotocore-qldb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -263,42 +263,42 @@
 
 `types_aiobotocore_qldb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_qldb.type_defs import (
     CancelJournalKinesisStreamRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJournalKinesisStreamResponseTypeDef,
     CreateLedgerRequestRequestTypeDef,
+    CreateLedgerResponseTypeDef,
     DeleteLedgerRequestRequestTypeDef,
     DescribeJournalKinesisStreamRequestRequestTypeDef,
     DescribeJournalS3ExportRequestRequestTypeDef,
     DescribeLedgerRequestRequestTypeDef,
     LedgerEncryptionDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportJournalToS3ResponseTypeDef,
     ValueHolderTypeDef,
     GetDigestRequestRequestTypeDef,
     KinesisConfigurationTypeDef,
     LedgerSummaryTypeDef,
     ListJournalKinesisStreamsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsRequestRequestTypeDef,
     ListLedgersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3EncryptionConfigurationTypeDef,
+    StreamJournalToKinesisResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLedgerPermissionsModeRequestRequestTypeDef,
-    UpdateLedgerRequestRequestTypeDef,
-    CancelJournalKinesisStreamResponseTypeDef,
-    CreateLedgerResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportJournalToS3ResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StreamJournalToKinesisResponseTypeDef,
     UpdateLedgerPermissionsModeResponseTypeDef,
+    UpdateLedgerRequestRequestTypeDef,
     DescribeLedgerResponseTypeDef,
     UpdateLedgerResponseTypeDef,
     GetBlockRequestRequestTypeDef,
     GetBlockResponseTypeDef,
     GetDigestResponseTypeDef,
     GetRevisionRequestRequestTypeDef,
     GetRevisionResponseTypeDef,
@@ -323,43 +323,43 @@
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/setup.py` & `types-aiobotocore-qldb-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-qldb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-qldb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_qldb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.QLDB 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.QLDB 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/",
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/__main__.py` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.QLDB 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.QLDB 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb//\nBoto3 docs:   "
         "   https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB\nOther"
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/client.py` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -233,48 +233,47 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#get_revision)
         """
 
     async def list_journal_kinesis_streams_for_ledger(
         self, *, LedgerName: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalKinesisStreamsForLedgerResponseTypeDef:
         """
-        Returns an array of all Amazon QLDB journal stream descriptors for a given
-        ledger.
+        Returns all Amazon QLDB journal streams for a given ledger.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_kinesis_streams_for_ledger)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_kinesis_streams_for_ledger)
         """
 
     async def list_journal_s3_exports(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalS3ExportsResponseTypeDef:
         """
-        Returns an array of journal export job descriptions for all ledgers that are
-        associated with the current Amazon Web Services account and Region.
+        Returns all journal export jobs for all ledgers that are associated with the
+        current Amazon Web Services account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_s3_exports)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_s3_exports)
         """
 
     async def list_journal_s3_exports_for_ledger(
         self, *, Name: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalS3ExportsForLedgerResponseTypeDef:
         """
-        Returns an array of journal export job descriptions for a specified ledger.
+        Returns all journal export jobs for a specified ledger.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_s3_exports_for_ledger)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_s3_exports_for_ledger)
         """
 
     async def list_ledgers(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListLedgersResponseTypeDef:
         """
-        Returns an array of ledger summaries that are associated with the current Amazon
-        Web Services account and Region.
+        Returns all ledgers that are associated with the current Amazon Web Services
+        account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_ledgers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_ledgers)
         """
 
     async def list_tags_for_resource(
         self, *, ResourceArn: str
```

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/client.pyi` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -216,45 +216,44 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.get_revision)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#get_revision)
         """
     async def list_journal_kinesis_streams_for_ledger(
         self, *, LedgerName: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalKinesisStreamsForLedgerResponseTypeDef:
         """
-        Returns an array of all Amazon QLDB journal stream descriptors for a given
-        ledger.
+        Returns all Amazon QLDB journal streams for a given ledger.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_kinesis_streams_for_ledger)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_kinesis_streams_for_ledger)
         """
     async def list_journal_s3_exports(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalS3ExportsResponseTypeDef:
         """
-        Returns an array of journal export job descriptions for all ledgers that are
-        associated with the current Amazon Web Services account and Region.
+        Returns all journal export jobs for all ledgers that are associated with the
+        current Amazon Web Services account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_s3_exports)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_s3_exports)
         """
     async def list_journal_s3_exports_for_ledger(
         self, *, Name: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListJournalS3ExportsForLedgerResponseTypeDef:
         """
-        Returns an array of journal export job descriptions for a specified ledger.
+        Returns all journal export jobs for a specified ledger.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_journal_s3_exports_for_ledger)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_journal_s3_exports_for_ledger)
         """
     async def list_ledgers(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListLedgersResponseTypeDef:
         """
-        Returns an array of ledger summaries that are associated with the current Amazon
-        Web Services account and Region.
+        Returns all ledgers that are associated with the current Amazon Web Services
+        account and Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB.Client.list_ledgers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/client/#list_ledgers)
         """
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
```

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/literals.py` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -102,14 +102,15 @@
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
@@ -188,14 +189,15 @@
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
@@ -206,14 +208,15 @@
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
@@ -249,14 +252,15 @@
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
@@ -275,16 +279,19 @@
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
@@ -368,15 +375,17 @@
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/literals.pyi` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -100,14 +100,15 @@
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
@@ -186,14 +187,15 @@
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
@@ -204,14 +206,15 @@
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
@@ -247,14 +250,15 @@
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
@@ -273,16 +277,19 @@
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
@@ -366,15 +373,17 @@
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/type_defs.py` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -30,42 +30,42 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelJournalKinesisStreamRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJournalKinesisStreamResponseTypeDef",
     "CreateLedgerRequestRequestTypeDef",
+    "CreateLedgerResponseTypeDef",
     "DeleteLedgerRequestRequestTypeDef",
     "DescribeJournalKinesisStreamRequestRequestTypeDef",
     "DescribeJournalS3ExportRequestRequestTypeDef",
     "DescribeLedgerRequestRequestTypeDef",
     "LedgerEncryptionDescriptionTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ExportJournalToS3ResponseTypeDef",
     "ValueHolderTypeDef",
     "GetDigestRequestRequestTypeDef",
     "KinesisConfigurationTypeDef",
     "LedgerSummaryTypeDef",
     "ListJournalKinesisStreamsForLedgerRequestRequestTypeDef",
     "ListJournalS3ExportsForLedgerRequestRequestTypeDef",
     "ListJournalS3ExportsRequestRequestTypeDef",
     "ListLedgersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3EncryptionConfigurationTypeDef",
+    "StreamJournalToKinesisResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLedgerPermissionsModeRequestRequestTypeDef",
-    "UpdateLedgerRequestRequestTypeDef",
-    "CancelJournalKinesisStreamResponseTypeDef",
-    "CreateLedgerResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportJournalToS3ResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StreamJournalToKinesisResponseTypeDef",
     "UpdateLedgerPermissionsModeResponseTypeDef",
+    "UpdateLedgerRequestRequestTypeDef",
     "DescribeLedgerResponseTypeDef",
     "UpdateLedgerResponseTypeDef",
     "GetBlockRequestRequestTypeDef",
     "GetBlockResponseTypeDef",
     "GetDigestResponseTypeDef",
     "GetRevisionRequestRequestTypeDef",
     "GetRevisionResponseTypeDef",
@@ -86,22 +86,19 @@
     "CancelJournalKinesisStreamRequestRequestTypeDef",
     {
         "LedgerName": str,
         "StreamId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJournalKinesisStreamResponseTypeDef = TypedDict(
+    "CancelJournalKinesisStreamResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "StreamId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLedgerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLedgerRequestRequestTypeDef",
     {
         "Name": str,
@@ -121,14 +118,28 @@
 
 class CreateLedgerRequestRequestTypeDef(
     _RequiredCreateLedgerRequestRequestTypeDef, _OptionalCreateLedgerRequestRequestTypeDef
 ):
     pass
 
 
+CreateLedgerResponseTypeDef = TypedDict(
+    "CreateLedgerResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "State": LedgerStateType,
+        "CreationDateTime": datetime,
+        "PermissionsMode": PermissionsModeType,
+        "DeletionProtection": bool,
+        "KmsKeyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLedgerRequestRequestTypeDef = TypedDict(
     "DeleteLedgerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -173,14 +184,29 @@
 
 class LedgerEncryptionDescriptionTypeDef(
     _RequiredLedgerEncryptionDescriptionTypeDef, _OptionalLedgerEncryptionDescriptionTypeDef
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportJournalToS3ResponseTypeDef = TypedDict(
+    "ExportJournalToS3ResponseTypeDef",
+    {
+        "ExportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ValueHolderTypeDef = TypedDict(
     "ValueHolderTypeDef",
     {
         "IonText": str,
     },
     total=False,
 )
@@ -290,14 +316,33 @@
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
 _RequiredS3EncryptionConfigurationTypeDef = TypedDict(
     "_RequiredS3EncryptionConfigurationTypeDef",
     {
         "ObjectEncryptionType": S3ObjectEncryptionTypeType,
     },
 )
 _OptionalS3EncryptionConfigurationTypeDef = TypedDict(
@@ -311,14 +356,22 @@
 
 class S3EncryptionConfigurationTypeDef(
     _RequiredS3EncryptionConfigurationTypeDef, _OptionalS3EncryptionConfigurationTypeDef
 ):
     pass
 
 
+StreamJournalToKinesisResponseTypeDef = TypedDict(
+    "StreamJournalToKinesisResponseTypeDef",
+    {
+        "StreamId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -335,14 +388,24 @@
     "UpdateLedgerPermissionsModeRequestRequestTypeDef",
     {
         "Name": str,
         "PermissionsMode": PermissionsModeType,
     },
 )
 
+UpdateLedgerPermissionsModeResponseTypeDef = TypedDict(
+    "UpdateLedgerPermissionsModeResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "PermissionsMode": PermissionsModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateLedgerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLedgerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateLedgerRequestRequestTypeDef = TypedDict(
@@ -357,101 +420,38 @@
 
 class UpdateLedgerRequestRequestTypeDef(
     _RequiredUpdateLedgerRequestRequestTypeDef, _OptionalUpdateLedgerRequestRequestTypeDef
 ):
     pass
 
 
-CancelJournalKinesisStreamResponseTypeDef = TypedDict(
-    "CancelJournalKinesisStreamResponseTypeDef",
-    {
-        "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLedgerResponseTypeDef = TypedDict(
-    "CreateLedgerResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "State": LedgerStateType,
-        "CreationDateTime": datetime,
-        "PermissionsMode": PermissionsModeType,
-        "DeletionProtection": bool,
-        "KmsKeyArn": str,
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
-ExportJournalToS3ResponseTypeDef = TypedDict(
-    "ExportJournalToS3ResponseTypeDef",
-    {
-        "ExportId": str,
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
-StreamJournalToKinesisResponseTypeDef = TypedDict(
-    "StreamJournalToKinesisResponseTypeDef",
-    {
-        "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateLedgerPermissionsModeResponseTypeDef = TypedDict(
-    "UpdateLedgerPermissionsModeResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "PermissionsMode": PermissionsModeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeLedgerResponseTypeDef = TypedDict(
     "DescribeLedgerResponseTypeDef",
     {
         "Name": str,
         "Arn": str,
         "State": LedgerStateType,
         "CreationDateTime": datetime,
         "PermissionsMode": PermissionsModeType,
         "DeletionProtection": bool,
         "EncryptionDescription": LedgerEncryptionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLedgerResponseTypeDef = TypedDict(
     "UpdateLedgerResponseTypeDef",
     {
         "Name": str,
         "Arn": str,
         "State": LedgerStateType,
         "CreationDateTime": datetime,
         "DeletionProtection": bool,
         "EncryptionDescription": LedgerEncryptionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetBlockRequestRequestTypeDef = TypedDict(
     "_RequiredGetBlockRequestRequestTypeDef",
     {
         "Name": str,
@@ -474,24 +474,24 @@
 
 
 GetBlockResponseTypeDef = TypedDict(
     "GetBlockResponseTypeDef",
     {
         "Block": ValueHolderTypeDef,
         "Proof": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDigestResponseTypeDef = TypedDict(
     "GetDigestResponseTypeDef",
     {
         "Digest": bytes,
         "DigestTipAddress": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetRevisionRequestRequestTypeDef = TypedDict(
     "_RequiredGetRevisionRequestRequestTypeDef",
     {
         "Name": str,
@@ -515,15 +515,15 @@
 
 
 GetRevisionResponseTypeDef = TypedDict(
     "GetRevisionResponseTypeDef",
     {
         "Proof": ValueHolderTypeDef,
         "Revision": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJournalKinesisStreamDescriptionTypeDef = TypedDict(
     "_RequiredJournalKinesisStreamDescriptionTypeDef",
     {
         "LedgerName": str,
@@ -581,15 +581,15 @@
 
 
 ListLedgersResponseTypeDef = TypedDict(
     "ListLedgersResponseTypeDef",
     {
         "Ledgers": List[LedgerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3ExportConfigurationTypeDef = TypedDict(
     "S3ExportConfigurationTypeDef",
     {
         "Bucket": str,
@@ -598,24 +598,24 @@
     },
 )
 
 DescribeJournalKinesisStreamResponseTypeDef = TypedDict(
     "DescribeJournalKinesisStreamResponseTypeDef",
     {
         "Stream": JournalKinesisStreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalKinesisStreamsForLedgerResponseTypeDef = TypedDict(
     "ListJournalKinesisStreamsForLedgerResponseTypeDef",
     {
         "Streams": List[JournalKinesisStreamDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExportJournalToS3RequestRequestTypeDef = TypedDict(
     "_RequiredExportJournalToS3RequestRequestTypeDef",
     {
         "Name": str,
@@ -668,28 +668,28 @@
     pass
 
 
 DescribeJournalS3ExportResponseTypeDef = TypedDict(
     "DescribeJournalS3ExportResponseTypeDef",
     {
         "ExportDescription": JournalS3ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalS3ExportsForLedgerResponseTypeDef = TypedDict(
     "ListJournalS3ExportsForLedgerResponseTypeDef",
     {
         "JournalS3Exports": List[JournalS3ExportDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalS3ExportsResponseTypeDef = TypedDict(
     "ListJournalS3ExportsResponseTypeDef",
     {
         "JournalS3Exports": List[JournalS3ExportDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb/type_defs.pyi` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -29,42 +29,42 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelJournalKinesisStreamRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJournalKinesisStreamResponseTypeDef",
     "CreateLedgerRequestRequestTypeDef",
+    "CreateLedgerResponseTypeDef",
     "DeleteLedgerRequestRequestTypeDef",
     "DescribeJournalKinesisStreamRequestRequestTypeDef",
     "DescribeJournalS3ExportRequestRequestTypeDef",
     "DescribeLedgerRequestRequestTypeDef",
     "LedgerEncryptionDescriptionTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ExportJournalToS3ResponseTypeDef",
     "ValueHolderTypeDef",
     "GetDigestRequestRequestTypeDef",
     "KinesisConfigurationTypeDef",
     "LedgerSummaryTypeDef",
     "ListJournalKinesisStreamsForLedgerRequestRequestTypeDef",
     "ListJournalS3ExportsForLedgerRequestRequestTypeDef",
     "ListJournalS3ExportsRequestRequestTypeDef",
     "ListLedgersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3EncryptionConfigurationTypeDef",
+    "StreamJournalToKinesisResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLedgerPermissionsModeRequestRequestTypeDef",
-    "UpdateLedgerRequestRequestTypeDef",
-    "CancelJournalKinesisStreamResponseTypeDef",
-    "CreateLedgerResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportJournalToS3ResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StreamJournalToKinesisResponseTypeDef",
     "UpdateLedgerPermissionsModeResponseTypeDef",
+    "UpdateLedgerRequestRequestTypeDef",
     "DescribeLedgerResponseTypeDef",
     "UpdateLedgerResponseTypeDef",
     "GetBlockRequestRequestTypeDef",
     "GetBlockResponseTypeDef",
     "GetDigestResponseTypeDef",
     "GetRevisionRequestRequestTypeDef",
     "GetRevisionResponseTypeDef",
@@ -85,22 +85,19 @@
     "CancelJournalKinesisStreamRequestRequestTypeDef",
     {
         "LedgerName": str,
         "StreamId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJournalKinesisStreamResponseTypeDef = TypedDict(
+    "CancelJournalKinesisStreamResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "StreamId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLedgerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLedgerRequestRequestTypeDef",
     {
         "Name": str,
@@ -118,14 +115,28 @@
 )
 
 class CreateLedgerRequestRequestTypeDef(
     _RequiredCreateLedgerRequestRequestTypeDef, _OptionalCreateLedgerRequestRequestTypeDef
 ):
     pass
 
+CreateLedgerResponseTypeDef = TypedDict(
+    "CreateLedgerResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "State": LedgerStateType,
+        "CreationDateTime": datetime,
+        "PermissionsMode": PermissionsModeType,
+        "DeletionProtection": bool,
+        "KmsKeyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLedgerRequestRequestTypeDef = TypedDict(
     "DeleteLedgerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -168,14 +179,29 @@
 )
 
 class LedgerEncryptionDescriptionTypeDef(
     _RequiredLedgerEncryptionDescriptionTypeDef, _OptionalLedgerEncryptionDescriptionTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportJournalToS3ResponseTypeDef = TypedDict(
+    "ExportJournalToS3ResponseTypeDef",
+    {
+        "ExportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ValueHolderTypeDef = TypedDict(
     "ValueHolderTypeDef",
     {
         "IonText": str,
     },
     total=False,
 )
@@ -279,14 +305,33 @@
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
 _RequiredS3EncryptionConfigurationTypeDef = TypedDict(
     "_RequiredS3EncryptionConfigurationTypeDef",
     {
         "ObjectEncryptionType": S3ObjectEncryptionTypeType,
     },
 )
 _OptionalS3EncryptionConfigurationTypeDef = TypedDict(
@@ -298,14 +343,22 @@
 )
 
 class S3EncryptionConfigurationTypeDef(
     _RequiredS3EncryptionConfigurationTypeDef, _OptionalS3EncryptionConfigurationTypeDef
 ):
     pass
 
+StreamJournalToKinesisResponseTypeDef = TypedDict(
+    "StreamJournalToKinesisResponseTypeDef",
+    {
+        "StreamId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -322,14 +375,24 @@
     "UpdateLedgerPermissionsModeRequestRequestTypeDef",
     {
         "Name": str,
         "PermissionsMode": PermissionsModeType,
     },
 )
 
+UpdateLedgerPermissionsModeResponseTypeDef = TypedDict(
+    "UpdateLedgerPermissionsModeResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "PermissionsMode": PermissionsModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateLedgerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLedgerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateLedgerRequestRequestTypeDef = TypedDict(
@@ -342,101 +405,38 @@
 )
 
 class UpdateLedgerRequestRequestTypeDef(
     _RequiredUpdateLedgerRequestRequestTypeDef, _OptionalUpdateLedgerRequestRequestTypeDef
 ):
     pass
 
-CancelJournalKinesisStreamResponseTypeDef = TypedDict(
-    "CancelJournalKinesisStreamResponseTypeDef",
-    {
-        "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLedgerResponseTypeDef = TypedDict(
-    "CreateLedgerResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "State": LedgerStateType,
-        "CreationDateTime": datetime,
-        "PermissionsMode": PermissionsModeType,
-        "DeletionProtection": bool,
-        "KmsKeyArn": str,
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
-ExportJournalToS3ResponseTypeDef = TypedDict(
-    "ExportJournalToS3ResponseTypeDef",
-    {
-        "ExportId": str,
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
-StreamJournalToKinesisResponseTypeDef = TypedDict(
-    "StreamJournalToKinesisResponseTypeDef",
-    {
-        "StreamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateLedgerPermissionsModeResponseTypeDef = TypedDict(
-    "UpdateLedgerPermissionsModeResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "PermissionsMode": PermissionsModeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeLedgerResponseTypeDef = TypedDict(
     "DescribeLedgerResponseTypeDef",
     {
         "Name": str,
         "Arn": str,
         "State": LedgerStateType,
         "CreationDateTime": datetime,
         "PermissionsMode": PermissionsModeType,
         "DeletionProtection": bool,
         "EncryptionDescription": LedgerEncryptionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLedgerResponseTypeDef = TypedDict(
     "UpdateLedgerResponseTypeDef",
     {
         "Name": str,
         "Arn": str,
         "State": LedgerStateType,
         "CreationDateTime": datetime,
         "DeletionProtection": bool,
         "EncryptionDescription": LedgerEncryptionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetBlockRequestRequestTypeDef = TypedDict(
     "_RequiredGetBlockRequestRequestTypeDef",
     {
         "Name": str,
@@ -457,24 +457,24 @@
     pass
 
 GetBlockResponseTypeDef = TypedDict(
     "GetBlockResponseTypeDef",
     {
         "Block": ValueHolderTypeDef,
         "Proof": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDigestResponseTypeDef = TypedDict(
     "GetDigestResponseTypeDef",
     {
         "Digest": bytes,
         "DigestTipAddress": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetRevisionRequestRequestTypeDef = TypedDict(
     "_RequiredGetRevisionRequestRequestTypeDef",
     {
         "Name": str,
@@ -496,15 +496,15 @@
     pass
 
 GetRevisionResponseTypeDef = TypedDict(
     "GetRevisionResponseTypeDef",
     {
         "Proof": ValueHolderTypeDef,
         "Revision": ValueHolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJournalKinesisStreamDescriptionTypeDef = TypedDict(
     "_RequiredJournalKinesisStreamDescriptionTypeDef",
     {
         "LedgerName": str,
@@ -558,15 +558,15 @@
     pass
 
 ListLedgersResponseTypeDef = TypedDict(
     "ListLedgersResponseTypeDef",
     {
         "Ledgers": List[LedgerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3ExportConfigurationTypeDef = TypedDict(
     "S3ExportConfigurationTypeDef",
     {
         "Bucket": str,
@@ -575,24 +575,24 @@
     },
 )
 
 DescribeJournalKinesisStreamResponseTypeDef = TypedDict(
     "DescribeJournalKinesisStreamResponseTypeDef",
     {
         "Stream": JournalKinesisStreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalKinesisStreamsForLedgerResponseTypeDef = TypedDict(
     "ListJournalKinesisStreamsForLedgerResponseTypeDef",
     {
         "Streams": List[JournalKinesisStreamDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExportJournalToS3RequestRequestTypeDef = TypedDict(
     "_RequiredExportJournalToS3RequestRequestTypeDef",
     {
         "Name": str,
@@ -641,28 +641,28 @@
 ):
     pass
 
 DescribeJournalS3ExportResponseTypeDef = TypedDict(
     "DescribeJournalS3ExportResponseTypeDef",
     {
         "ExportDescription": JournalS3ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalS3ExportsForLedgerResponseTypeDef = TypedDict(
     "ListJournalS3ExportsForLedgerResponseTypeDef",
     {
         "JournalS3Exports": List[JournalS3ExportDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJournalS3ExportsResponseTypeDef = TypedDict(
     "ListJournalS3ExportsResponseTypeDef",
     {
         "JournalS3Exports": List[JournalS3ExportDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/PKG-INFO` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-qldb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.QLDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.QLDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-qldb"></a>
 
 # types-aiobotocore-qldb
 
 [![PyPI - types-aiobotocore-qldb](https://img.shields.io/pypi/v/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-qldb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-qldb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-qldb?color=blue)](https://pypistats.org/packages/types-aiobotocore-qldb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.QLDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
+[aiobotocore.QLDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/qldb.html#QLDB)
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
 [types-aiobotocore-qldb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_qldb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,42 +296,42 @@
 
 `types_aiobotocore_qldb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_qldb.type_defs import (
     CancelJournalKinesisStreamRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJournalKinesisStreamResponseTypeDef,
     CreateLedgerRequestRequestTypeDef,
+    CreateLedgerResponseTypeDef,
     DeleteLedgerRequestRequestTypeDef,
     DescribeJournalKinesisStreamRequestRequestTypeDef,
     DescribeJournalS3ExportRequestRequestTypeDef,
     DescribeLedgerRequestRequestTypeDef,
     LedgerEncryptionDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportJournalToS3ResponseTypeDef,
     ValueHolderTypeDef,
     GetDigestRequestRequestTypeDef,
     KinesisConfigurationTypeDef,
     LedgerSummaryTypeDef,
     ListJournalKinesisStreamsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsForLedgerRequestRequestTypeDef,
     ListJournalS3ExportsRequestRequestTypeDef,
     ListLedgersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3EncryptionConfigurationTypeDef,
+    StreamJournalToKinesisResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLedgerPermissionsModeRequestRequestTypeDef,
-    UpdateLedgerRequestRequestTypeDef,
-    CancelJournalKinesisStreamResponseTypeDef,
-    CreateLedgerResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportJournalToS3ResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StreamJournalToKinesisResponseTypeDef,
     UpdateLedgerPermissionsModeResponseTypeDef,
+    UpdateLedgerRequestRequestTypeDef,
     DescribeLedgerResponseTypeDef,
     UpdateLedgerResponseTypeDef,
     GetBlockRequestRequestTypeDef,
     GetBlockResponseTypeDef,
     GetDigestResponseTypeDef,
     GetRevisionRequestRequestTypeDef,
     GetRevisionResponseTypeDef,
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-qldb-2.5.0.post1/types_aiobotocore_qldb.egg-info/SOURCES.txt` & `types-aiobotocore-qldb-2.5.1/types_aiobotocore_qldb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

