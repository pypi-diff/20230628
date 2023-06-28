# Comparing `tmp/types-aiobotocore-timestream-write-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-timestream-write-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-timestream-write-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-timestream-write-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-timestream-write-2.5.0.post1.tar` & `types-aiobotocore-timestream-write-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.591696 types-aiobotocore-timestream-write-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13890 2023-03-11 12:27:27.587696 types-aiobotocore-timestream-write-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12284 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:27.591696 types-aiobotocore-timestream-write-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.579696 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      508 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13880 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13857 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7998 2023-03-11 12:25:06.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7996 2023-03-11 12:25:06.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    11653 2023-03-11 12:25:06.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    11640 2023-03-11 12:25:06.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.587696 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13890 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      887 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.966226 types-aiobotocore-timestream-write-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14909 2023-06-28 01:44:16.966226 types-aiobotocore-timestream-write-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13309 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.966226 types-aiobotocore-timestream-write-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-write-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.966226 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      508 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16894 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16867 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8756 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8754 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21359 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21328 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:54.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.966226 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14909 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      887 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/LICENSE` & `types-aiobotocore-timestream-write-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/PKG-INFO` & `types-aiobotocore-timestream-write-2.5.1/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-timestream-write
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TimestreamWrite 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TimestreamWrite 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-timestream-write"></a>
 
 # types-aiobotocore-timestream-write
 
 [![PyPI - types-aiobotocore-timestream-write](https://img.shields.io/pypi/v/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-write?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-write)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamWrite 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
+[aiobotocore.TimestreamWrite 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
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
 [types-aiobotocore-timestream-write docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,121 +269,150 @@
 ### Literals
 
 `types_aiobotocore_timestream_write.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_timestream_write.literals import (
+    BatchLoadDataFormatType,
+    BatchLoadStatusType,
     DimensionValueTypeType,
     MeasureValueTypeType,
+    PartitionKeyEnforcementLevelType,
+    PartitionKeyTypeType,
     S3EncryptionOptionType,
+    ScalarMeasureValueTypeType,
     TableStatusType,
     TimeUnitType,
     TimestreamWriteServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: DimensionValueTypeType) -> bool:
+def check_value(value: BatchLoadDataFormatType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_timestream_write.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_write.type_defs import (
+    BatchLoadProgressReportTypeDef,
+    BatchLoadTaskTypeDef,
+    CreateBatchLoadTaskResponseTypeDef,
     TagTypeDef,
     DatabaseTypeDef,
-    ResponseMetadataTypeDef,
     RetentionPropertiesTypeDef,
+    CsvConfigurationTypeDef,
+    DataModelS3ConfigurationTypeDef,
+    DimensionMappingTypeDef,
+    DataSourceS3ConfigurationTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
+    DescribeBatchLoadTaskRequestRequestTypeDef,
     DescribeDatabaseRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeTableRequestRequestTypeDef,
     DimensionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBatchLoadTasksRequestRequestTypeDef,
     ListDatabasesRequestRequestTypeDef,
     ListTablesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
     MeasureValueTypeDef,
+    MultiMeasureAttributeMappingTypeDef,
+    PartitionKeyTypeDef,
     RecordsIngestedTypeDef,
+    ReportS3ConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    ResumeBatchLoadTaskRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatabaseRequestRequestTypeDef,
+    ListBatchLoadTasksResponseTypeDef,
     CreateDatabaseRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateDatabaseResponseTypeDef,
     DescribeDatabaseResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListDatabasesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateDatabaseResponseTypeDef,
+    DataSourceConfigurationTypeDef,
     DescribeEndpointsResponseTypeDef,
     MagneticStoreRejectedDataLocationTypeDef,
     RecordTypeDef,
+    MixedMeasureMappingTypeDef,
+    MultiMeasureMappingsTypeDef,
+    SchemaTypeDef,
     WriteRecordsResponseTypeDef,
+    ReportConfigurationTypeDef,
     MagneticStoreWritePropertiesTypeDef,
     WriteRecordsRequestRequestTypeDef,
+    DataModelTypeDef,
     CreateTableRequestRequestTypeDef,
     TableTypeDef,
     UpdateTableRequestRequestTypeDef,
+    DataModelConfigurationTypeDef,
     CreateTableResponseTypeDef,
     DescribeTableResponseTypeDef,
     ListTablesResponseTypeDef,
     UpdateTableResponseTypeDef,
+    BatchLoadTaskDescriptionTypeDef,
+    CreateBatchLoadTaskRequestRequestTypeDef,
+    DescribeBatchLoadTaskResponseTypeDef,
 )
 
 
-def get_structure() -> TagTypeDef:
+def get_structure() -> BatchLoadProgressReportTypeDef:
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/README.md` & `types-aiobotocore-timestream-write-2.5.1/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-timestream-write"></a>
 
 # types-aiobotocore-timestream-write
 
 [![PyPI - types-aiobotocore-timestream-write](https://img.shields.io/pypi/v/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-write?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-write)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamWrite 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
+[aiobotocore.TimestreamWrite 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
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
 [types-aiobotocore-timestream-write docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/).
 
 See how it helps to find and fix potential bugs:
 
@@ -236,121 +236,150 @@
 ### Literals
 
 `types_aiobotocore_timestream_write.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_timestream_write.literals import (
+    BatchLoadDataFormatType,
+    BatchLoadStatusType,
     DimensionValueTypeType,
     MeasureValueTypeType,
+    PartitionKeyEnforcementLevelType,
+    PartitionKeyTypeType,
     S3EncryptionOptionType,
+    ScalarMeasureValueTypeType,
     TableStatusType,
     TimeUnitType,
     TimestreamWriteServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: DimensionValueTypeType) -> bool:
+def check_value(value: BatchLoadDataFormatType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_timestream_write.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_write.type_defs import (
+    BatchLoadProgressReportTypeDef,
+    BatchLoadTaskTypeDef,
+    CreateBatchLoadTaskResponseTypeDef,
     TagTypeDef,
     DatabaseTypeDef,
-    ResponseMetadataTypeDef,
     RetentionPropertiesTypeDef,
+    CsvConfigurationTypeDef,
+    DataModelS3ConfigurationTypeDef,
+    DimensionMappingTypeDef,
+    DataSourceS3ConfigurationTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
+    DescribeBatchLoadTaskRequestRequestTypeDef,
     DescribeDatabaseRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeTableRequestRequestTypeDef,
     DimensionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBatchLoadTasksRequestRequestTypeDef,
     ListDatabasesRequestRequestTypeDef,
     ListTablesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
     MeasureValueTypeDef,
+    MultiMeasureAttributeMappingTypeDef,
+    PartitionKeyTypeDef,
     RecordsIngestedTypeDef,
+    ReportS3ConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    ResumeBatchLoadTaskRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatabaseRequestRequestTypeDef,
+    ListBatchLoadTasksResponseTypeDef,
     CreateDatabaseRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateDatabaseResponseTypeDef,
     DescribeDatabaseResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListDatabasesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateDatabaseResponseTypeDef,
+    DataSourceConfigurationTypeDef,
     DescribeEndpointsResponseTypeDef,
     MagneticStoreRejectedDataLocationTypeDef,
     RecordTypeDef,
+    MixedMeasureMappingTypeDef,
+    MultiMeasureMappingsTypeDef,
+    SchemaTypeDef,
     WriteRecordsResponseTypeDef,
+    ReportConfigurationTypeDef,
     MagneticStoreWritePropertiesTypeDef,
     WriteRecordsRequestRequestTypeDef,
+    DataModelTypeDef,
     CreateTableRequestRequestTypeDef,
     TableTypeDef,
     UpdateTableRequestRequestTypeDef,
+    DataModelConfigurationTypeDef,
     CreateTableResponseTypeDef,
     DescribeTableResponseTypeDef,
     ListTablesResponseTypeDef,
     UpdateTableResponseTypeDef,
+    BatchLoadTaskDescriptionTypeDef,
+    CreateBatchLoadTaskRequestRequestTypeDef,
+    DescribeBatchLoadTaskResponseTypeDef,
 )
 
 
-def get_structure() -> TagTypeDef:
+def get_structure() -> BatchLoadProgressReportTypeDef:
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/setup.py` & `types-aiobotocore-timestream-write-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-timestream-write.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-timestream-write",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_timestream_write"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.TimestreamWrite 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.TimestreamWrite 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/"
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/__main__.py` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.TimestreamWrite 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.TimestreamWrite 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite\nOther"
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/client.py` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/client.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -15,57 +15,62 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import BatchLoadStatusType
 from .type_defs import (
+    CreateBatchLoadTaskResponseTypeDef,
     CreateDatabaseResponseTypeDef,
     CreateTableResponseTypeDef,
+    DataModelConfigurationTypeDef,
+    DataSourceConfigurationTypeDef,
+    DescribeBatchLoadTaskResponseTypeDef,
     DescribeDatabaseResponseTypeDef,
     DescribeEndpointsResponseTypeDef,
     DescribeTableResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    ListBatchLoadTasksResponseTypeDef,
     ListDatabasesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MagneticStoreWritePropertiesTypeDef,
     RecordTypeDef,
+    ReportConfigurationTypeDef,
     RetentionPropertiesTypeDef,
+    SchemaTypeDef,
     TagTypeDef,
     UpdateDatabaseResponseTypeDef,
     UpdateTableResponseTypeDef,
     WriteRecordsResponseTypeDef,
 )
 
 __all__ = ("TimestreamWriteClient",)
 
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
     InvalidEndpointException: Type[BotocoreClientError]
     RejectedRecordsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class TimestreamWriteClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
     """
 
     meta: ClientMeta
@@ -74,213 +79,238 @@
     def exceptions(self) -> Exceptions:
         """
         TimestreamWriteClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#close)
         """
+    async def create_batch_load_task(
+        self,
+        *,
+        DataSourceConfiguration: DataSourceConfigurationTypeDef,
+        ReportConfiguration: ReportConfigurationTypeDef,
+        TargetDatabaseName: str,
+        TargetTableName: str,
+        ClientToken: str = ...,
+        DataModelConfiguration: DataModelConfigurationTypeDef = ...,
+        RecordVersion: int = ...
+    ) -> CreateBatchLoadTaskResponseTypeDef:
+        """
+        Creates a new Timestream batch load task.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_batch_load_task)
+        """
     async def create_database(
         self, *, DatabaseName: str, KmsKeyId: str = ..., Tags: Sequence[TagTypeDef] = ...
     ) -> CreateDatabaseResponseTypeDef:
         """
         Creates a new Timestream database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_database)
         """
-
     async def create_table(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         RetentionProperties: RetentionPropertiesTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...
+        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...,
+        Schema: SchemaTypeDef = ...
     ) -> CreateTableResponseTypeDef:
         """
-        The CreateTable operation adds a new table to an existing database in your
-        account.
+        Adds a new table to an existing database in your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_table)
         """
-
     async def delete_database(self, *, DatabaseName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a given Timestream database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.delete_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#delete_database)
         """
-
     async def delete_table(
         self, *, DatabaseName: str, TableName: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a given Timestream table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.delete_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#delete_table)
         """
+    async def describe_batch_load_task(
+        self, *, TaskId: str
+    ) -> DescribeBatchLoadTaskResponseTypeDef:
+        """
+        Returns information about the batch load task, including configurations,
+        mappings, progress, and other details.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_batch_load_task)
+        """
     async def describe_database(self, *, DatabaseName: str) -> DescribeDatabaseResponseTypeDef:
         """
         Returns information about the database, including the database name, time that
         the database was created, and the total number of tables found within the
         database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_database)
         """
-
     async def describe_endpoints(self) -> DescribeEndpointsResponseTypeDef:
         """
-        DescribeEndpoints returns a list of available endpoints to make Timestream API
-        calls against.
+        Returns a list of available endpoints to make Timestream API calls against.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_endpoints)
         """
-
     async def describe_table(
         self, *, DatabaseName: str, TableName: str
     ) -> DescribeTableResponseTypeDef:
         """
         Returns information about the table, including the table name, database name,
         retention duration of the memory store and the magnetic store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_table)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#generate_presigned_url)
         """
+    async def list_batch_load_tasks(
+        self, *, NextToken: str = ..., MaxResults: int = ..., TaskStatus: BatchLoadStatusType = ...
+    ) -> ListBatchLoadTasksResponseTypeDef:
+        """
+        Provides a list of batch load tasks, along with the name, status, when the task
+        is resumable until, and other details.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_batch_load_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_batch_load_tasks)
+        """
     async def list_databases(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDatabasesResponseTypeDef:
         """
         Returns a list of your Timestream databases.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_databases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_databases)
         """
-
     async def list_tables(
         self, *, DatabaseName: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListTablesResponseTypeDef:
         """
-        A list of tables, along with the name, status and retention properties of each
-        table.
+        Provides a list of tables, along with the name, status, and retention properties
+        of each table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_tables)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_tables)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        List all tags on a Timestream resource.
+        Lists all tags on a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_tags_for_resource)
         """
+    async def resume_batch_load_task(self, *, TaskId: str) -> Dict[str, Any]:
+        """
+        See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/timestream-
+        write-2018-11-01/ResumeBatchLoadTask).
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.resume_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#resume_batch_load_task)
+        """
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Associate a set of tags with a Timestream resource.
+        Associates a set of tags with a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#tag_resource)
         """
-
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes the association of tags from a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#untag_resource)
         """
-
     async def update_database(
         self, *, DatabaseName: str, KmsKeyId: str
     ) -> UpdateDatabaseResponseTypeDef:
         """
         Modifies the KMS key for an existing database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.update_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#update_database)
         """
-
     async def update_table(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         RetentionProperties: RetentionPropertiesTypeDef = ...,
-        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...
+        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...,
+        Schema: SchemaTypeDef = ...
     ) -> UpdateTableResponseTypeDef:
         """
         Modifies the retention duration of the memory store and magnetic store for your
         Timestream table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#update_table)
         """
-
     async def write_records(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         Records: Sequence[RecordTypeDef],
         CommonAttributes: RecordTypeDef = ...
     ) -> WriteRecordsResponseTypeDef:
         """
-        The WriteRecords operation enables you to write your time series data into
-        Timestream.
+        Enables you to write your time-series data into Timestream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.write_records)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#write_records)
         """
-
     async def __aenter__(self) -> "TimestreamWriteClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
         """
```

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/client.pyi` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -15,54 +15,65 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import BatchLoadStatusType
 from .type_defs import (
+    CreateBatchLoadTaskResponseTypeDef,
     CreateDatabaseResponseTypeDef,
     CreateTableResponseTypeDef,
+    DataModelConfigurationTypeDef,
+    DataSourceConfigurationTypeDef,
+    DescribeBatchLoadTaskResponseTypeDef,
     DescribeDatabaseResponseTypeDef,
     DescribeEndpointsResponseTypeDef,
     DescribeTableResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    ListBatchLoadTasksResponseTypeDef,
     ListDatabasesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MagneticStoreWritePropertiesTypeDef,
     RecordTypeDef,
+    ReportConfigurationTypeDef,
     RetentionPropertiesTypeDef,
+    SchemaTypeDef,
     TagTypeDef,
     UpdateDatabaseResponseTypeDef,
     UpdateTableResponseTypeDef,
     WriteRecordsResponseTypeDef,
 )
 
 __all__ = ("TimestreamWriteClient",)
 
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
     InvalidEndpointException: Type[BotocoreClientError]
     RejectedRecordsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class TimestreamWriteClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
     """
 
     meta: ClientMeta
@@ -71,193 +82,262 @@
     def exceptions(self) -> Exceptions:
         """
         TimestreamWriteClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#close)
         """
+
+    async def create_batch_load_task(
+        self,
+        *,
+        DataSourceConfiguration: DataSourceConfigurationTypeDef,
+        ReportConfiguration: ReportConfigurationTypeDef,
+        TargetDatabaseName: str,
+        TargetTableName: str,
+        ClientToken: str = ...,
+        DataModelConfiguration: DataModelConfigurationTypeDef = ...,
+        RecordVersion: int = ...
+    ) -> CreateBatchLoadTaskResponseTypeDef:
+        """
+        Creates a new Timestream batch load task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_batch_load_task)
+        """
+
     async def create_database(
         self, *, DatabaseName: str, KmsKeyId: str = ..., Tags: Sequence[TagTypeDef] = ...
     ) -> CreateDatabaseResponseTypeDef:
         """
         Creates a new Timestream database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_database)
         """
+
     async def create_table(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         RetentionProperties: RetentionPropertiesTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...
+        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...,
+        Schema: SchemaTypeDef = ...
     ) -> CreateTableResponseTypeDef:
         """
-        The CreateTable operation adds a new table to an existing database in your
-        account.
+        Adds a new table to an existing database in your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#create_table)
         """
+
     async def delete_database(self, *, DatabaseName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a given Timestream database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.delete_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#delete_database)
         """
+
     async def delete_table(
         self, *, DatabaseName: str, TableName: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a given Timestream table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.delete_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#delete_table)
         """
+
+    async def describe_batch_load_task(
+        self, *, TaskId: str
+    ) -> DescribeBatchLoadTaskResponseTypeDef:
+        """
+        Returns information about the batch load task, including configurations,
+        mappings, progress, and other details.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_batch_load_task)
+        """
+
     async def describe_database(self, *, DatabaseName: str) -> DescribeDatabaseResponseTypeDef:
         """
         Returns information about the database, including the database name, time that
         the database was created, and the total number of tables found within the
         database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_database)
         """
+
     async def describe_endpoints(self) -> DescribeEndpointsResponseTypeDef:
         """
-        DescribeEndpoints returns a list of available endpoints to make Timestream API
-        calls against.
+        Returns a list of available endpoints to make Timestream API calls against.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_endpoints)
         """
+
     async def describe_table(
         self, *, DatabaseName: str, TableName: str
     ) -> DescribeTableResponseTypeDef:
         """
         Returns information about the table, including the table name, database name,
         retention duration of the memory store and the magnetic store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.describe_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#describe_table)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#generate_presigned_url)
         """
+
+    async def list_batch_load_tasks(
+        self, *, NextToken: str = ..., MaxResults: int = ..., TaskStatus: BatchLoadStatusType = ...
+    ) -> ListBatchLoadTasksResponseTypeDef:
+        """
+        Provides a list of batch load tasks, along with the name, status, when the task
+        is resumable until, and other details.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_batch_load_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_batch_load_tasks)
+        """
+
     async def list_databases(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDatabasesResponseTypeDef:
         """
         Returns a list of your Timestream databases.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_databases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_databases)
         """
+
     async def list_tables(
         self, *, DatabaseName: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListTablesResponseTypeDef:
         """
-        A list of tables, along with the name, status and retention properties of each
-        table.
+        Provides a list of tables, along with the name, status, and retention properties
+        of each table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_tables)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_tables)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        List all tags on a Timestream resource.
+        Lists all tags on a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#list_tags_for_resource)
         """
+
+    async def resume_batch_load_task(self, *, TaskId: str) -> Dict[str, Any]:
+        """
+        See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/timestream-
+        write-2018-11-01/ResumeBatchLoadTask).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.resume_batch_load_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#resume_batch_load_task)
+        """
+
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Associate a set of tags with a Timestream resource.
+        Associates a set of tags with a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#tag_resource)
         """
+
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes the association of tags from a Timestream resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#untag_resource)
         """
+
     async def update_database(
         self, *, DatabaseName: str, KmsKeyId: str
     ) -> UpdateDatabaseResponseTypeDef:
         """
         Modifies the KMS key for an existing database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.update_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#update_database)
         """
+
     async def update_table(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         RetentionProperties: RetentionPropertiesTypeDef = ...,
-        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...
+        MagneticStoreWriteProperties: MagneticStoreWritePropertiesTypeDef = ...,
+        Schema: SchemaTypeDef = ...
     ) -> UpdateTableResponseTypeDef:
         """
         Modifies the retention duration of the memory store and magnetic store for your
         Timestream table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#update_table)
         """
+
     async def write_records(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         Records: Sequence[RecordTypeDef],
         CommonAttributes: RecordTypeDef = ...
     ) -> WriteRecordsResponseTypeDef:
         """
-        The WriteRecords operation enables you to write your time series data into
-        Timestream.
+        Enables you to write your time-series data into Timestream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client.write_records)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/#write_records)
         """
+
     async def __aenter__(self) -> "TimestreamWriteClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/client/)
         """
```

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/literals.py` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/literals.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,44 +2,56 @@
 Type annotations for timestream-write service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_timestream_write.literals import DimensionValueTypeType
+    from types_aiobotocore_timestream_write.literals import BatchLoadDataFormatType
 
-    data: DimensionValueTypeType = "VARCHAR"
+    data: BatchLoadDataFormatType = "CSV"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "BatchLoadDataFormatType",
+    "BatchLoadStatusType",
     "DimensionValueTypeType",
     "MeasureValueTypeType",
+    "PartitionKeyEnforcementLevelType",
+    "PartitionKeyTypeType",
     "S3EncryptionOptionType",
+    "ScalarMeasureValueTypeType",
     "TableStatusType",
     "TimeUnitType",
     "TimestreamWriteServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
+BatchLoadDataFormatType = Literal["CSV"]
+BatchLoadStatusType = Literal[
+    "CREATED", "FAILED", "IN_PROGRESS", "PENDING_RESUME", "PROGRESS_STOPPED", "SUCCEEDED"
+]
 DimensionValueTypeType = Literal["VARCHAR"]
 MeasureValueTypeType = Literal["BIGINT", "BOOLEAN", "DOUBLE", "MULTI", "TIMESTAMP", "VARCHAR"]
+PartitionKeyEnforcementLevelType = Literal["OPTIONAL", "REQUIRED"]
+PartitionKeyTypeType = Literal["DIMENSION", "MEASURE"]
 S3EncryptionOptionType = Literal["SSE_KMS", "SSE_S3"]
-TableStatusType = Literal["ACTIVE", "DELETING"]
+ScalarMeasureValueTypeType = Literal["BIGINT", "BOOLEAN", "DOUBLE", "TIMESTAMP", "VARCHAR"]
+TableStatusType = Literal["ACTIVE", "DELETING", "RESTORING"]
 TimeUnitType = Literal["MICROSECONDS", "MILLISECONDS", "NANOSECONDS", "SECONDS"]
 TimestreamWriteServiceName = Literal["timestream-write"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -96,14 +108,15 @@
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
@@ -182,14 +195,15 @@
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
@@ -200,14 +214,15 @@
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
@@ -243,14 +258,15 @@
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
@@ -269,16 +285,19 @@
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
@@ -362,15 +381,17 @@
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write/literals.pyi` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -2,42 +2,54 @@
 Type annotations for timestream-write service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_timestream_write.literals import DimensionValueTypeType
+    from types_aiobotocore_timestream_write.literals import BatchLoadDataFormatType
 
-    data: DimensionValueTypeType = "VARCHAR"
+    data: BatchLoadDataFormatType = "CSV"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "BatchLoadDataFormatType",
+    "BatchLoadStatusType",
     "DimensionValueTypeType",
     "MeasureValueTypeType",
+    "PartitionKeyEnforcementLevelType",
+    "PartitionKeyTypeType",
     "S3EncryptionOptionType",
+    "ScalarMeasureValueTypeType",
     "TableStatusType",
     "TimeUnitType",
     "TimestreamWriteServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+BatchLoadDataFormatType = Literal["CSV"]
+BatchLoadStatusType = Literal[
+    "CREATED", "FAILED", "IN_PROGRESS", "PENDING_RESUME", "PROGRESS_STOPPED", "SUCCEEDED"
+]
 DimensionValueTypeType = Literal["VARCHAR"]
 MeasureValueTypeType = Literal["BIGINT", "BOOLEAN", "DOUBLE", "MULTI", "TIMESTAMP", "VARCHAR"]
+PartitionKeyEnforcementLevelType = Literal["OPTIONAL", "REQUIRED"]
+PartitionKeyTypeType = Literal["DIMENSION", "MEASURE"]
 S3EncryptionOptionType = Literal["SSE_KMS", "SSE_S3"]
-TableStatusType = Literal["ACTIVE", "DELETING"]
+ScalarMeasureValueTypeType = Literal["BIGINT", "BOOLEAN", "DOUBLE", "TIMESTAMP", "VARCHAR"]
+TableStatusType = Literal["ACTIVE", "DELETING", "RESTORING"]
 TimeUnitType = Literal["MICROSECONDS", "MILLISECONDS", "NANOSECONDS", "SECONDS"]
 TimestreamWriteServiceName = Literal["timestream-write"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -94,14 +106,15 @@
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
@@ -180,14 +193,15 @@
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
@@ -198,14 +212,15 @@
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
@@ -241,14 +256,15 @@
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
@@ -267,16 +283,19 @@
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
@@ -360,15 +379,17 @@
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/PKG-INFO` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-timestream-write
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TimestreamWrite 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TimestreamWrite 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-timestream-write"></a>
 
 # types-aiobotocore-timestream-write
 
 [![PyPI - types-aiobotocore-timestream-write](https://img.shields.io/pypi/v/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-write.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-write)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-write?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-write)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamWrite 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
+[aiobotocore.TimestreamWrite 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-write.html#TimestreamWrite)
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
 [types-aiobotocore-timestream-write docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_write/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,121 +269,150 @@
 ### Literals
 
 `types_aiobotocore_timestream_write.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_timestream_write.literals import (
+    BatchLoadDataFormatType,
+    BatchLoadStatusType,
     DimensionValueTypeType,
     MeasureValueTypeType,
+    PartitionKeyEnforcementLevelType,
+    PartitionKeyTypeType,
     S3EncryptionOptionType,
+    ScalarMeasureValueTypeType,
     TableStatusType,
     TimeUnitType,
     TimestreamWriteServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: DimensionValueTypeType) -> bool:
+def check_value(value: BatchLoadDataFormatType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_timestream_write.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_write.type_defs import (
+    BatchLoadProgressReportTypeDef,
+    BatchLoadTaskTypeDef,
+    CreateBatchLoadTaskResponseTypeDef,
     TagTypeDef,
     DatabaseTypeDef,
-    ResponseMetadataTypeDef,
     RetentionPropertiesTypeDef,
+    CsvConfigurationTypeDef,
+    DataModelS3ConfigurationTypeDef,
+    DimensionMappingTypeDef,
+    DataSourceS3ConfigurationTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
+    DescribeBatchLoadTaskRequestRequestTypeDef,
     DescribeDatabaseRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeTableRequestRequestTypeDef,
     DimensionTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBatchLoadTasksRequestRequestTypeDef,
     ListDatabasesRequestRequestTypeDef,
     ListTablesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
     MeasureValueTypeDef,
+    MultiMeasureAttributeMappingTypeDef,
+    PartitionKeyTypeDef,
     RecordsIngestedTypeDef,
+    ReportS3ConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    ResumeBatchLoadTaskRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDatabaseRequestRequestTypeDef,
+    ListBatchLoadTasksResponseTypeDef,
     CreateDatabaseRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateDatabaseResponseTypeDef,
     DescribeDatabaseResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListDatabasesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateDatabaseResponseTypeDef,
+    DataSourceConfigurationTypeDef,
     DescribeEndpointsResponseTypeDef,
     MagneticStoreRejectedDataLocationTypeDef,
     RecordTypeDef,
+    MixedMeasureMappingTypeDef,
+    MultiMeasureMappingsTypeDef,
+    SchemaTypeDef,
     WriteRecordsResponseTypeDef,
+    ReportConfigurationTypeDef,
     MagneticStoreWritePropertiesTypeDef,
     WriteRecordsRequestRequestTypeDef,
+    DataModelTypeDef,
     CreateTableRequestRequestTypeDef,
     TableTypeDef,
     UpdateTableRequestRequestTypeDef,
+    DataModelConfigurationTypeDef,
     CreateTableResponseTypeDef,
     DescribeTableResponseTypeDef,
     ListTablesResponseTypeDef,
     UpdateTableResponseTypeDef,
+    BatchLoadTaskDescriptionTypeDef,
+    CreateBatchLoadTaskRequestRequestTypeDef,
+    DescribeBatchLoadTaskResponseTypeDef,
 )
 
 
-def get_structure() -> TagTypeDef:
+def get_structure() -> BatchLoadProgressReportTypeDef:
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

### Comparing `types-aiobotocore-timestream-write-2.5.0.post1/types_aiobotocore_timestream_write.egg-info/SOURCES.txt` & `types-aiobotocore-timestream-write-2.5.1/types_aiobotocore_timestream_write.egg-info/SOURCES.txt`

 * *Files identical despite different names*

