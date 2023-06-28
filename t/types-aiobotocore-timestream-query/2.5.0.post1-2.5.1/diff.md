# Comparing `tmp/types-aiobotocore-timestream-query-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-timestream-query-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-timestream-query-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-timestream-query-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-timestream-query-2.5.0.post1.tar` & `types-aiobotocore-timestream-query-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.307693 types-aiobotocore-timestream-query-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15753 2023-03-11 12:27:27.299693 types-aiobotocore-timestream-query-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14147 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:27.307693 types-aiobotocore-timestream-query-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.299693 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/
--rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1116 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14555 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14530 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8674 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8672 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4556 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4550 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19453 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19422 2023-03-11 12:25:05.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:04.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.299693 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15753 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:27:27.000000 types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.882226 types-aiobotocore-timestream-query-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15754 2023-06-28 01:44:16.882226 types-aiobotocore-timestream-query-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14154 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.882226 types-aiobotocore-timestream-query-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.882226 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/
+-rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1116 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14555 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14530 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8883 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8881 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4442 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4437 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19477 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19446 2023-06-28 01:41:53.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:52.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.882226 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15754 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:44:16.000000 types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/LICENSE` & `types-aiobotocore-timestream-query-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/PKG-INFO` & `types-aiobotocore-timestream-query-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-timestream-query
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TimestreamQuery 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TimestreamQuery 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-timestream-query"></a>
 
 # types-aiobotocore-timestream-query
 
 [![PyPI - types-aiobotocore-timestream-query](https://img.shields.io/pypi/v/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-query?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-query)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamQuery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
+[aiobotocore.TimestreamQuery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
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
 [types-aiobotocore-timestream-query docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/).
 
 See how it helps to find and fix potential bugs:
 
@@ -333,54 +333,54 @@
 
 `types_aiobotocore_timestream_query.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_query.type_defs import (
     CancelQueryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelQueryResponseTypeDef,
     ColumnInfoTypeDef,
     ScheduleConfigurationTypeDef,
     TagTypeDef,
+    CreateScheduledQueryResponseTypeDef,
     RowTypeDef,
     TimeSeriesDataPointTypeDef,
     DeleteScheduledQueryRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeScheduledQueryRequestRequestTypeDef,
     DimensionMappingTypeDef,
+    EmptyResponseMetadataTypeDef,
     S3ConfigurationTypeDef,
     S3ReportLocationTypeDef,
     ExecuteScheduledQueryRequestRequestTypeDef,
     ExecutionStatsTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
     ListScheduledQueriesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MultiMeasureAttributeMappingTypeDef,
     SnsConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMappingTypeDef,
     PrepareQueryRequestRequestTypeDef,
     SelectColumnTypeDef,
+    QueryRequestQueryPaginateTypeDef,
     QueryRequestRequestTypeDef,
     QueryStatusTypeDef,
+    ResponseMetadataTypeDef,
     TimestreamDestinationTypeDef,
     TypeTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateScheduledQueryRequestRequestTypeDef,
-    CancelQueryResponseTypeDef,
-    CreateScheduledQueryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     DatumTypeDef,
     DescribeEndpointsResponseTypeDef,
     ErrorReportConfigurationTypeDef,
     ErrorReportLocationTypeDef,
-    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    QueryRequestQueryPaginateTypeDef,
     MixedMeasureMappingTypeDef,
     MultiMeasureMappingsTypeDef,
     NotificationConfigurationTypeDef,
     PrepareQueryResponseTypeDef,
     QueryResponseTypeDef,
     TargetDestinationTypeDef,
     ScheduledQueryRunSummaryTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/README.md` & `types-aiobotocore-timestream-query-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-timestream-query"></a>
 
 # types-aiobotocore-timestream-query
 
 [![PyPI - types-aiobotocore-timestream-query](https://img.shields.io/pypi/v/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-query?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-query)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamQuery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
+[aiobotocore.TimestreamQuery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
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
 [types-aiobotocore-timestream-query docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/).
 
 See how it helps to find and fix potential bugs:
 
@@ -300,54 +300,54 @@
 
 `types_aiobotocore_timestream_query.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_query.type_defs import (
     CancelQueryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelQueryResponseTypeDef,
     ColumnInfoTypeDef,
     ScheduleConfigurationTypeDef,
     TagTypeDef,
+    CreateScheduledQueryResponseTypeDef,
     RowTypeDef,
     TimeSeriesDataPointTypeDef,
     DeleteScheduledQueryRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeScheduledQueryRequestRequestTypeDef,
     DimensionMappingTypeDef,
+    EmptyResponseMetadataTypeDef,
     S3ConfigurationTypeDef,
     S3ReportLocationTypeDef,
     ExecuteScheduledQueryRequestRequestTypeDef,
     ExecutionStatsTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
     ListScheduledQueriesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MultiMeasureAttributeMappingTypeDef,
     SnsConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMappingTypeDef,
     PrepareQueryRequestRequestTypeDef,
     SelectColumnTypeDef,
+    QueryRequestQueryPaginateTypeDef,
     QueryRequestRequestTypeDef,
     QueryStatusTypeDef,
+    ResponseMetadataTypeDef,
     TimestreamDestinationTypeDef,
     TypeTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateScheduledQueryRequestRequestTypeDef,
-    CancelQueryResponseTypeDef,
-    CreateScheduledQueryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     DatumTypeDef,
     DescribeEndpointsResponseTypeDef,
     ErrorReportConfigurationTypeDef,
     ErrorReportLocationTypeDef,
-    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    QueryRequestQueryPaginateTypeDef,
     MixedMeasureMappingTypeDef,
     MultiMeasureMappingsTypeDef,
     NotificationConfigurationTypeDef,
     PrepareQueryResponseTypeDef,
     QueryResponseTypeDef,
     TargetDestinationTypeDef,
     ScheduledQueryRunSummaryTypeDef,
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/setup.py` & `types-aiobotocore-timestream-query-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-timestream-query.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-timestream-query",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_timestream_query"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.TimestreamQuery 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.TimestreamQuery 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/"
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/__init__.py` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/__init__.pyi` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/client.py` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/client.pyi` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/literals.py` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -123,14 +123,15 @@
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
@@ -209,14 +210,15 @@
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
@@ -227,14 +229,15 @@
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
@@ -270,14 +273,15 @@
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
@@ -296,16 +300,19 @@
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
@@ -389,15 +396,17 @@
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/literals.pyi` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -121,14 +121,15 @@
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
@@ -207,14 +208,15 @@
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
@@ -225,14 +227,15 @@
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
@@ -268,14 +271,15 @@
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
@@ -294,16 +298,19 @@
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
@@ -387,15 +394,17 @@
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/paginator.py` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: TimestreamQueryClient
 
         list_scheduled_queries_paginator: ListScheduledQueriesPaginator = client.get_paginator("list_scheduled_queries")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         query_paginator: QueryPaginator = client.get_paginator("query")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListScheduledQueriesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     QueryResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListScheduledQueriesPaginator", "ListTagsForResourcePaginator", "QueryPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,30 +52,30 @@
 class ListScheduledQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListScheduledQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listscheduledqueriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduledQueriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListScheduledQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listscheduledqueriespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listtagsforresourcepaginator)
         """
 
 
@@ -93,13 +86,13 @@
     """
 
     def paginate(
         self,
         *,
         QueryString: str,
         ClientToken: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.Query.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#querypaginator)
         """
```

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/paginator.pyi` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: TimestreamQueryClient
 
         list_scheduled_queries_paginator: ListScheduledQueriesPaginator = client.get_paginator("list_scheduled_queries")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         query_paginator: QueryPaginator = client.get_paginator("query")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListScheduledQueriesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     QueryResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListScheduledQueriesPaginator", "ListTagsForResourcePaginator", "QueryPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,29 +49,29 @@
 class ListScheduledQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListScheduledQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listscheduledqueriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduledQueriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListScheduledQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listscheduledqueriespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#listtagsforresourcepaginator)
         """
 
 class QueryPaginator(AioPaginator):
@@ -87,13 +81,13 @@
     """
 
     def paginate(
         self,
         *,
         QueryString: str,
         ClientToken: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery.Paginator.Query.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/paginators/#querypaginator)
         """
```

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/type_defs.py` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -32,54 +32,54 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelQueryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelQueryResponseTypeDef",
     "ColumnInfoTypeDef",
     "ScheduleConfigurationTypeDef",
     "TagTypeDef",
+    "CreateScheduledQueryResponseTypeDef",
     "RowTypeDef",
     "TimeSeriesDataPointTypeDef",
     "DeleteScheduledQueryRequestRequestTypeDef",
     "EndpointTypeDef",
     "DescribeScheduledQueryRequestRequestTypeDef",
     "DimensionMappingTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "S3ConfigurationTypeDef",
     "S3ReportLocationTypeDef",
     "ExecuteScheduledQueryRequestRequestTypeDef",
     "ExecutionStatsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
     "ListScheduledQueriesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MultiMeasureAttributeMappingTypeDef",
     "SnsConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterMappingTypeDef",
     "PrepareQueryRequestRequestTypeDef",
     "SelectColumnTypeDef",
+    "QueryRequestQueryPaginateTypeDef",
     "QueryRequestRequestTypeDef",
     "QueryStatusTypeDef",
+    "ResponseMetadataTypeDef",
     "TimestreamDestinationTypeDef",
     "TypeTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateScheduledQueryRequestRequestTypeDef",
-    "CancelQueryResponseTypeDef",
-    "CreateScheduledQueryResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "DatumTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "ErrorReportConfigurationTypeDef",
     "ErrorReportLocationTypeDef",
-    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "QueryRequestQueryPaginateTypeDef",
     "MixedMeasureMappingTypeDef",
     "MultiMeasureMappingsTypeDef",
     "NotificationConfigurationTypeDef",
     "PrepareQueryResponseTypeDef",
     "QueryResponseTypeDef",
     "TargetDestinationTypeDef",
     "ScheduledQueryRunSummaryTypeDef",
@@ -95,22 +95,19 @@
 CancelQueryRequestRequestTypeDef = TypedDict(
     "CancelQueryRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelQueryResponseTypeDef = TypedDict(
+    "CancelQueryResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CancellationMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredColumnInfoTypeDef = TypedDict(
     "_RequiredColumnInfoTypeDef",
     {
         "Type": Dict[str, Any],
@@ -140,18 +137,26 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateScheduledQueryResponseTypeDef = TypedDict(
+    "CreateScheduledQueryResponseTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RowTypeDef = TypedDict(
     "RowTypeDef",
     {
-        "Data": List[Dict[str, Any]],
+        "Data": List["DatumTypeDef"],
     },
 )
 
 TimeSeriesDataPointTypeDef = TypedDict(
     "TimeSeriesDataPointTypeDef",
     {
         "Time": str,
@@ -185,14 +190,21 @@
     "DimensionMappingTypeDef",
     {
         "Name": str,
         "DimensionValueType": Literal["VARCHAR"],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3ConfigurationTypeDef = TypedDict(
     "_RequiredS3ConfigurationTypeDef",
     {
         "BucketName": str,
     },
 )
 _OptionalS3ConfigurationTypeDef = TypedDict(
@@ -249,33 +261,53 @@
         "BytesMetered": int,
         "RecordsIngested": int,
         "QueryResultRows": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef = TypedDict(
+    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListScheduledQueriesRequestRequestTypeDef = TypedDict(
     "ListScheduledQueriesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -320,14 +352,24 @@
 SnsConfigurationTypeDef = TypedDict(
     "SnsConfigurationTypeDef",
     {
         "TopicArn": str,
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
 ParameterMappingTypeDef = TypedDict(
     "ParameterMappingTypeDef",
     {
         "Name": str,
         "Type": "TypeTypeDef",
     },
 )
@@ -361,14 +403,36 @@
         "DatabaseName": str,
         "TableName": str,
         "Aliased": bool,
     },
     total=False,
 )
 
+_RequiredQueryRequestQueryPaginateTypeDef = TypedDict(
+    "_RequiredQueryRequestQueryPaginateTypeDef",
+    {
+        "QueryString": str,
+    },
+)
+_OptionalQueryRequestQueryPaginateTypeDef = TypedDict(
+    "_OptionalQueryRequestQueryPaginateTypeDef",
+    {
+        "ClientToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class QueryRequestQueryPaginateTypeDef(
+    _RequiredQueryRequestQueryPaginateTypeDef, _OptionalQueryRequestQueryPaginateTypeDef
+):
+    pass
+
+
 _RequiredQueryRequestRequestTypeDef = TypedDict(
     "_RequiredQueryRequestRequestTypeDef",
     {
         "QueryString": str,
     },
 )
 _OptionalQueryRequestRequestTypeDef = TypedDict(
@@ -394,14 +458,25 @@
         "ProgressPercentage": float,
         "CumulativeBytesScanned": int,
         "CumulativeBytesMetered": int,
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
 TimestreamDestinationTypeDef = TypedDict(
     "TimestreamDestinationTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
     total=False,
@@ -430,43 +505,20 @@
     "UpdateScheduledQueryRequestRequestTypeDef",
     {
         "ScheduledQueryArn": str,
         "State": ScheduledQueryStateType,
     },
 )
 
-CancelQueryResponseTypeDef = TypedDict(
-    "CancelQueryResponseTypeDef",
-    {
-        "CancellationMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScheduledQueryResponseTypeDef = TypedDict(
-    "CreateScheduledQueryResponseTypeDef",
-    {
-        "Arn": str,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -486,15 +538,15 @@
     total=False,
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorReportConfigurationTypeDef = TypedDict(
     "ErrorReportConfigurationTypeDef",
     {
         "S3Configuration": S3ConfigurationTypeDef,
@@ -505,66 +557,14 @@
     "ErrorReportLocationTypeDef",
     {
         "S3ReportLocation": S3ReportLocationTypeDef,
     },
     total=False,
 )
 
-ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef = TypedDict(
-    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredQueryRequestQueryPaginateTypeDef = TypedDict(
-    "_RequiredQueryRequestQueryPaginateTypeDef",
-    {
-        "QueryString": str,
-    },
-)
-_OptionalQueryRequestQueryPaginateTypeDef = TypedDict(
-    "_OptionalQueryRequestQueryPaginateTypeDef",
-    {
-        "ClientToken": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class QueryRequestQueryPaginateTypeDef(
-    _RequiredQueryRequestQueryPaginateTypeDef, _OptionalQueryRequestQueryPaginateTypeDef
-):
-    pass
-
-
 _RequiredMixedMeasureMappingTypeDef = TypedDict(
     "_RequiredMixedMeasureMappingTypeDef",
     {
         "MeasureValueType": MeasureValueTypeType,
     },
 )
 _OptionalMixedMeasureMappingTypeDef = TypedDict(
@@ -615,27 +615,27 @@
 
 PrepareQueryResponseTypeDef = TypedDict(
     "PrepareQueryResponseTypeDef",
     {
         "QueryString": str,
         "Columns": List[SelectColumnTypeDef],
         "Parameters": List[ParameterMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryResponseTypeDef = TypedDict(
     "QueryResponseTypeDef",
     {
         "QueryId": str,
         "NextToken": str,
         "Rows": List[RowTypeDef],
         "ColumnInfo": List["ColumnInfoTypeDef"],
         "QueryStatus": QueryStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetDestinationTypeDef = TypedDict(
     "TargetDestinationTypeDef",
     {
         "TimestreamDestination": TimestreamDestinationTypeDef,
@@ -716,15 +716,15 @@
 )
 
 ListScheduledQueriesResponseTypeDef = TypedDict(
     "ListScheduledQueriesResponseTypeDef",
     {
         "ScheduledQueries": List[ScheduledQueryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateScheduledQueryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateScheduledQueryRequestRequestTypeDef",
     {
         "Name": str,
@@ -788,10 +788,10 @@
     pass
 
 
 DescribeScheduledQueryResponseTypeDef = TypedDict(
     "DescribeScheduledQueryResponseTypeDef",
     {
         "ScheduledQuery": ScheduledQueryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query/type_defs.pyi` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -31,54 +31,54 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelQueryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelQueryResponseTypeDef",
     "ColumnInfoTypeDef",
     "ScheduleConfigurationTypeDef",
     "TagTypeDef",
+    "CreateScheduledQueryResponseTypeDef",
     "RowTypeDef",
     "TimeSeriesDataPointTypeDef",
     "DeleteScheduledQueryRequestRequestTypeDef",
     "EndpointTypeDef",
     "DescribeScheduledQueryRequestRequestTypeDef",
     "DimensionMappingTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "S3ConfigurationTypeDef",
     "S3ReportLocationTypeDef",
     "ExecuteScheduledQueryRequestRequestTypeDef",
     "ExecutionStatsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
     "ListScheduledQueriesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MultiMeasureAttributeMappingTypeDef",
     "SnsConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterMappingTypeDef",
     "PrepareQueryRequestRequestTypeDef",
     "SelectColumnTypeDef",
+    "QueryRequestQueryPaginateTypeDef",
     "QueryRequestRequestTypeDef",
     "QueryStatusTypeDef",
+    "ResponseMetadataTypeDef",
     "TimestreamDestinationTypeDef",
     "TypeTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateScheduledQueryRequestRequestTypeDef",
-    "CancelQueryResponseTypeDef",
-    "CreateScheduledQueryResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "DatumTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "ErrorReportConfigurationTypeDef",
     "ErrorReportLocationTypeDef",
-    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "QueryRequestQueryPaginateTypeDef",
     "MixedMeasureMappingTypeDef",
     "MultiMeasureMappingsTypeDef",
     "NotificationConfigurationTypeDef",
     "PrepareQueryResponseTypeDef",
     "QueryResponseTypeDef",
     "TargetDestinationTypeDef",
     "ScheduledQueryRunSummaryTypeDef",
@@ -94,22 +94,19 @@
 CancelQueryRequestRequestTypeDef = TypedDict(
     "CancelQueryRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelQueryResponseTypeDef = TypedDict(
+    "CancelQueryResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CancellationMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredColumnInfoTypeDef = TypedDict(
     "_RequiredColumnInfoTypeDef",
     {
         "Type": Dict[str, Any],
@@ -137,18 +134,26 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateScheduledQueryResponseTypeDef = TypedDict(
+    "CreateScheduledQueryResponseTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RowTypeDef = TypedDict(
     "RowTypeDef",
     {
-        "Data": List[Dict[str, Any]],
+        "Data": List["DatumTypeDef"],
     },
 )
 
 TimeSeriesDataPointTypeDef = TypedDict(
     "TimeSeriesDataPointTypeDef",
     {
         "Time": str,
@@ -182,14 +187,21 @@
     "DimensionMappingTypeDef",
     {
         "Name": str,
         "DimensionValueType": Literal["VARCHAR"],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3ConfigurationTypeDef = TypedDict(
     "_RequiredS3ConfigurationTypeDef",
     {
         "BucketName": str,
     },
 )
 _OptionalS3ConfigurationTypeDef = TypedDict(
@@ -242,33 +254,51 @@
         "BytesMetered": int,
         "RecordsIngested": int,
         "QueryResultRows": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef = TypedDict(
+    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListScheduledQueriesRequestRequestTypeDef = TypedDict(
     "ListScheduledQueriesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -309,14 +339,24 @@
 SnsConfigurationTypeDef = TypedDict(
     "SnsConfigurationTypeDef",
     {
         "TopicArn": str,
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
 ParameterMappingTypeDef = TypedDict(
     "ParameterMappingTypeDef",
     {
         "Name": str,
         "Type": "TypeTypeDef",
     },
 )
@@ -348,14 +388,34 @@
         "DatabaseName": str,
         "TableName": str,
         "Aliased": bool,
     },
     total=False,
 )
 
+_RequiredQueryRequestQueryPaginateTypeDef = TypedDict(
+    "_RequiredQueryRequestQueryPaginateTypeDef",
+    {
+        "QueryString": str,
+    },
+)
+_OptionalQueryRequestQueryPaginateTypeDef = TypedDict(
+    "_OptionalQueryRequestQueryPaginateTypeDef",
+    {
+        "ClientToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class QueryRequestQueryPaginateTypeDef(
+    _RequiredQueryRequestQueryPaginateTypeDef, _OptionalQueryRequestQueryPaginateTypeDef
+):
+    pass
+
 _RequiredQueryRequestRequestTypeDef = TypedDict(
     "_RequiredQueryRequestRequestTypeDef",
     {
         "QueryString": str,
     },
 )
 _OptionalQueryRequestRequestTypeDef = TypedDict(
@@ -379,14 +439,25 @@
         "ProgressPercentage": float,
         "CumulativeBytesScanned": int,
         "CumulativeBytesMetered": int,
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
 TimestreamDestinationTypeDef = TypedDict(
     "TimestreamDestinationTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
     total=False,
@@ -415,43 +486,20 @@
     "UpdateScheduledQueryRequestRequestTypeDef",
     {
         "ScheduledQueryArn": str,
         "State": ScheduledQueryStateType,
     },
 )
 
-CancelQueryResponseTypeDef = TypedDict(
-    "CancelQueryResponseTypeDef",
-    {
-        "CancellationMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScheduledQueryResponseTypeDef = TypedDict(
-    "CreateScheduledQueryResponseTypeDef",
-    {
-        "Arn": str,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -471,15 +519,15 @@
     total=False,
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorReportConfigurationTypeDef = TypedDict(
     "ErrorReportConfigurationTypeDef",
     {
         "S3Configuration": S3ConfigurationTypeDef,
@@ -490,62 +538,14 @@
     "ErrorReportLocationTypeDef",
     {
         "S3ReportLocation": S3ReportLocationTypeDef,
     },
     total=False,
 )
 
-ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef = TypedDict(
-    "ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredQueryRequestQueryPaginateTypeDef = TypedDict(
-    "_RequiredQueryRequestQueryPaginateTypeDef",
-    {
-        "QueryString": str,
-    },
-)
-_OptionalQueryRequestQueryPaginateTypeDef = TypedDict(
-    "_OptionalQueryRequestQueryPaginateTypeDef",
-    {
-        "ClientToken": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class QueryRequestQueryPaginateTypeDef(
-    _RequiredQueryRequestQueryPaginateTypeDef, _OptionalQueryRequestQueryPaginateTypeDef
-):
-    pass
-
 _RequiredMixedMeasureMappingTypeDef = TypedDict(
     "_RequiredMixedMeasureMappingTypeDef",
     {
         "MeasureValueType": MeasureValueTypeType,
     },
 )
 _OptionalMixedMeasureMappingTypeDef = TypedDict(
@@ -592,27 +592,27 @@
 
 PrepareQueryResponseTypeDef = TypedDict(
     "PrepareQueryResponseTypeDef",
     {
         "QueryString": str,
         "Columns": List[SelectColumnTypeDef],
         "Parameters": List[ParameterMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryResponseTypeDef = TypedDict(
     "QueryResponseTypeDef",
     {
         "QueryId": str,
         "NextToken": str,
         "Rows": List[RowTypeDef],
         "ColumnInfo": List["ColumnInfoTypeDef"],
         "QueryStatus": QueryStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetDestinationTypeDef = TypedDict(
     "TargetDestinationTypeDef",
     {
         "TimestreamDestination": TimestreamDestinationTypeDef,
@@ -689,15 +689,15 @@
 )
 
 ListScheduledQueriesResponseTypeDef = TypedDict(
     "ListScheduledQueriesResponseTypeDef",
     {
         "ScheduledQueries": List[ScheduledQueryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateScheduledQueryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateScheduledQueryRequestRequestTypeDef",
     {
         "Name": str,
@@ -757,10 +757,10 @@
 ):
     pass
 
 DescribeScheduledQueryResponseTypeDef = TypedDict(
     "DescribeScheduledQueryResponseTypeDef",
     {
         "ScheduledQuery": ScheduledQueryDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/PKG-INFO` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-timestream-query
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TimestreamQuery 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TimestreamQuery 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-timestream-query"></a>
 
 # types-aiobotocore-timestream-query
 
 [![PyPI - types-aiobotocore-timestream-query](https://img.shields.io/pypi/v/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-timestream-query.svg?color=blue)](https://pypi.org/project/types-aiobotocore-timestream-query)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-timestream-query?color=blue)](https://pypistats.org/packages/types-aiobotocore-timestream-query)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TimestreamQuery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
+[aiobotocore.TimestreamQuery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/timestream-query.html#TimestreamQuery)
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
 [types-aiobotocore-timestream-query docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_timestream_query/).
 
 See how it helps to find and fix potential bugs:
 
@@ -333,54 +333,54 @@
 
 `types_aiobotocore_timestream_query.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_timestream_query.type_defs import (
     CancelQueryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelQueryResponseTypeDef,
     ColumnInfoTypeDef,
     ScheduleConfigurationTypeDef,
     TagTypeDef,
+    CreateScheduledQueryResponseTypeDef,
     RowTypeDef,
     TimeSeriesDataPointTypeDef,
     DeleteScheduledQueryRequestRequestTypeDef,
     EndpointTypeDef,
     DescribeScheduledQueryRequestRequestTypeDef,
     DimensionMappingTypeDef,
+    EmptyResponseMetadataTypeDef,
     S3ConfigurationTypeDef,
     S3ReportLocationTypeDef,
     ExecuteScheduledQueryRequestRequestTypeDef,
     ExecutionStatsTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
     ListScheduledQueriesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MultiMeasureAttributeMappingTypeDef,
     SnsConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMappingTypeDef,
     PrepareQueryRequestRequestTypeDef,
     SelectColumnTypeDef,
+    QueryRequestQueryPaginateTypeDef,
     QueryRequestRequestTypeDef,
     QueryStatusTypeDef,
+    ResponseMetadataTypeDef,
     TimestreamDestinationTypeDef,
     TypeTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateScheduledQueryRequestRequestTypeDef,
-    CancelQueryResponseTypeDef,
-    CreateScheduledQueryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     DatumTypeDef,
     DescribeEndpointsResponseTypeDef,
     ErrorReportConfigurationTypeDef,
     ErrorReportLocationTypeDef,
-    ListScheduledQueriesRequestListScheduledQueriesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    QueryRequestQueryPaginateTypeDef,
     MixedMeasureMappingTypeDef,
     MultiMeasureMappingsTypeDef,
     NotificationConfigurationTypeDef,
     PrepareQueryResponseTypeDef,
     QueryResponseTypeDef,
     TargetDestinationTypeDef,
     ScheduledQueryRunSummaryTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-timestream-query-2.5.0.post1/types_aiobotocore_timestream_query.egg-info/SOURCES.txt` & `types-aiobotocore-timestream-query-2.5.1/types_aiobotocore_timestream_query.egg-info/SOURCES.txt`

 * *Files identical despite different names*

