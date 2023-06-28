# Comparing `tmp/types-aiobotocore-mq-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mq-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mq-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-mq-2.5.1.tar", last modified: Wed Jun 28 01:43:53 2023, max compression
```

## Comparing `types-aiobotocore-mq-2.5.0.post1.tar` & `types-aiobotocore-mq-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.947449 types-aiobotocore-mq-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14996 2023-03-11 12:27:01.947449 types-aiobotocore-mq-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13445 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.947449 types-aiobotocore-mq-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2054 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.943448 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/
--rw-r--r--   0 runner    (1001) docker     (123)      589 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      588 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      912 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17934 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17902 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8861 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8859 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1998 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     1994 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    26001 2023-03-11 12:18:58.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25956 2023-03-11 12:18:57.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:55.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.947449 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14996 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      718 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:27:01.000000 types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.914182 types-aiobotocore-mq-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15176 2023-06-28 01:43:53.906182 types-aiobotocore-mq-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13631 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:53.914182 types-aiobotocore-mq-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2048 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.906182 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/
+-rw-r--r--   0 runner    (1001) docker     (123)      589 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      588 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18730 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18697 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9319 2023-06-28 01:35:41.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9317 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1880 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1877 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    28077 2023-06-28 01:35:41.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28030 2023-06-28 01:35:41.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:40.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.906182 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15176 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:43:53.000000 types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/LICENSE` & `types-aiobotocore-mq-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mq-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mq-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mq
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MQ 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MQ 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mq"></a>
 
 # types-aiobotocore-mq
 
 [![PyPI - types-aiobotocore-mq](https://img.shields.io/pypi/v/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mq?color=blue)](https://pypistats.org/packages/types-aiobotocore-mq)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MQ 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
+[aiobotocore.MQ 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
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
 [types-aiobotocore-mq docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,18 +294,20 @@
 
 ```python
 from types_aiobotocore_mq.literals import (
     AuthenticationStrategyType,
     BrokerStateType,
     BrokerStorageTypeType,
     ChangeTypeType,
+    DataReplicationModeType,
     DayOfWeekType,
     DeploymentModeType,
     EngineTypeType,
     ListBrokersPaginatorName,
+    PromoteModeType,
     SanitizationWarningReasonType,
     MQServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -332,65 +334,69 @@
     ConfigurationIdTypeDef,
     ConfigurationRevisionTypeDef,
     EncryptionOptionsTypeDef,
     LdapServerMetadataInputTypeDef,
     LogsTypeDef,
     UserTypeDef,
     WeeklyStartTimeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBrokerResponseTypeDef,
     CreateConfigurationRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
+    DataReplicationCounterpartTypeDef,
     DeleteBrokerRequestRequestTypeDef,
+    DeleteBrokerResponseTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeBrokerEngineTypesRequestRequestTypeDef,
     DescribeBrokerInstanceOptionsRequestRequestTypeDef,
     DescribeBrokerRequestRequestTypeDef,
     LdapServerMetadataOutputTypeDef,
     UserSummaryTypeDef,
     DescribeConfigurationRequestRequestTypeDef,
     DescribeConfigurationRevisionRequestRequestTypeDef,
+    DescribeConfigurationRevisionResponseTypeDef,
     DescribeUserRequestRequestTypeDef,
     UserPendingChangesTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBrokersRequestListBrokersPaginateTypeDef,
     ListBrokersRequestRequestTypeDef,
     ListConfigurationRevisionsRequestRequestTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     ListUsersRequestRequestTypeDef,
     PendingLogsTypeDef,
+    PaginatorConfigTypeDef,
+    PromoteRequestRequestTypeDef,
+    PromoteResponseTypeDef,
     RebootBrokerRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SanitizationWarningTypeDef,
     UpdateConfigurationRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     BrokerInstanceOptionTypeDef,
     BrokerEngineTypeTypeDef,
+    ListBrokersResponseTypeDef,
     ConfigurationsTypeDef,
     ConfigurationTypeDef,
-    CreateBrokerRequestRequestTypeDef,
-    UpdateBrokerRequestRequestTypeDef,
-    CreateBrokerResponseTypeDef,
     CreateConfigurationResponseTypeDef,
-    DeleteBrokerResponseTypeDef,
     DescribeConfigurationResponseTypeDef,
-    DescribeConfigurationRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListBrokersResponseTypeDef,
     ListConfigurationRevisionsResponseTypeDef,
-    ListTagsResponseTypeDef,
-    UpdateBrokerResponseTypeDef,
+    CreateBrokerRequestRequestTypeDef,
+    UpdateBrokerRequestRequestTypeDef,
+    DataReplicationMetadataOutputTypeDef,
     ListUsersResponseTypeDef,
     DescribeUserResponseTypeDef,
-    ListBrokersRequestListBrokersPaginateTypeDef,
     LogsSummaryTypeDef,
     UpdateConfigurationResponseTypeDef,
     DescribeBrokerInstanceOptionsResponseTypeDef,
     DescribeBrokerEngineTypesResponseTypeDef,
     ListConfigurationsResponseTypeDef,
+    UpdateBrokerResponseTypeDef,
     DescribeBrokerResponseTypeDef,
 )
 
 
 def get_structure() -> ActionRequiredTypeDef:
     return {...}
 ```
@@ -398,43 +404,43 @@
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

### Comparing `types-aiobotocore-mq-2.5.0.post1/README.md` & `types-aiobotocore-mq-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mq"></a>
 
 # types-aiobotocore-mq
 
 [![PyPI - types-aiobotocore-mq](https://img.shields.io/pypi/v/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mq?color=blue)](https://pypistats.org/packages/types-aiobotocore-mq)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MQ 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
+[aiobotocore.MQ 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
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
 [types-aiobotocore-mq docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,18 +261,20 @@
 
 ```python
 from types_aiobotocore_mq.literals import (
     AuthenticationStrategyType,
     BrokerStateType,
     BrokerStorageTypeType,
     ChangeTypeType,
+    DataReplicationModeType,
     DayOfWeekType,
     DeploymentModeType,
     EngineTypeType,
     ListBrokersPaginatorName,
+    PromoteModeType,
     SanitizationWarningReasonType,
     MQServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -299,65 +301,69 @@
     ConfigurationIdTypeDef,
     ConfigurationRevisionTypeDef,
     EncryptionOptionsTypeDef,
     LdapServerMetadataInputTypeDef,
     LogsTypeDef,
     UserTypeDef,
     WeeklyStartTimeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBrokerResponseTypeDef,
     CreateConfigurationRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
+    DataReplicationCounterpartTypeDef,
     DeleteBrokerRequestRequestTypeDef,
+    DeleteBrokerResponseTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeBrokerEngineTypesRequestRequestTypeDef,
     DescribeBrokerInstanceOptionsRequestRequestTypeDef,
     DescribeBrokerRequestRequestTypeDef,
     LdapServerMetadataOutputTypeDef,
     UserSummaryTypeDef,
     DescribeConfigurationRequestRequestTypeDef,
     DescribeConfigurationRevisionRequestRequestTypeDef,
+    DescribeConfigurationRevisionResponseTypeDef,
     DescribeUserRequestRequestTypeDef,
     UserPendingChangesTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBrokersRequestListBrokersPaginateTypeDef,
     ListBrokersRequestRequestTypeDef,
     ListConfigurationRevisionsRequestRequestTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     ListUsersRequestRequestTypeDef,
     PendingLogsTypeDef,
+    PaginatorConfigTypeDef,
+    PromoteRequestRequestTypeDef,
+    PromoteResponseTypeDef,
     RebootBrokerRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SanitizationWarningTypeDef,
     UpdateConfigurationRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     BrokerInstanceOptionTypeDef,
     BrokerEngineTypeTypeDef,
+    ListBrokersResponseTypeDef,
     ConfigurationsTypeDef,
     ConfigurationTypeDef,
-    CreateBrokerRequestRequestTypeDef,
-    UpdateBrokerRequestRequestTypeDef,
-    CreateBrokerResponseTypeDef,
     CreateConfigurationResponseTypeDef,
-    DeleteBrokerResponseTypeDef,
     DescribeConfigurationResponseTypeDef,
-    DescribeConfigurationRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListBrokersResponseTypeDef,
     ListConfigurationRevisionsResponseTypeDef,
-    ListTagsResponseTypeDef,
-    UpdateBrokerResponseTypeDef,
+    CreateBrokerRequestRequestTypeDef,
+    UpdateBrokerRequestRequestTypeDef,
+    DataReplicationMetadataOutputTypeDef,
     ListUsersResponseTypeDef,
     DescribeUserResponseTypeDef,
-    ListBrokersRequestListBrokersPaginateTypeDef,
     LogsSummaryTypeDef,
     UpdateConfigurationResponseTypeDef,
     DescribeBrokerInstanceOptionsResponseTypeDef,
     DescribeBrokerEngineTypesResponseTypeDef,
     ListConfigurationsResponseTypeDef,
+    UpdateBrokerResponseTypeDef,
     DescribeBrokerResponseTypeDef,
 )
 
 
 def get_structure() -> ActionRequiredTypeDef:
     return {...}
 ```
@@ -365,43 +371,43 @@
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

### Comparing `types-aiobotocore-mq-2.5.0.post1/setup.py` & `types-aiobotocore-mq-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 """
 Setup script for types-aiobotocore-mq.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mq",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mq"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MQ 2.5.0 service generated with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MQ 2.5.1 service generated with mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/",
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

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__init__.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__init__.pyi` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/__main__.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MQ 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MQ 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ\nOther"
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

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/client.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,16 +19,18 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AuthenticationStrategyType,
     BrokerStorageTypeType,
+    DataReplicationModeType,
     DeploymentModeType,
     EngineTypeType,
+    PromoteModeType,
 )
 from .paginator import ListBrokersPaginator
 from .type_defs import (
     ConfigurationIdTypeDef,
     CreateBrokerResponseTypeDef,
     CreateConfigurationResponseTypeDef,
     DeleteBrokerResponseTypeDef,
@@ -43,14 +45,15 @@
     LdapServerMetadataInputTypeDef,
     ListBrokersResponseTypeDef,
     ListConfigurationRevisionsResponseTypeDef,
     ListConfigurationsResponseTypeDef,
     ListTagsResponseTypeDef,
     ListUsersResponseTypeDef,
     LogsTypeDef,
+    PromoteResponseTypeDef,
     UpdateBrokerResponseTypeDef,
     UpdateConfigurationResponseTypeDef,
     UserTypeDef,
     WeeklyStartTimeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -130,15 +133,17 @@
         EncryptionOptions: EncryptionOptionsTypeDef = ...,
         LdapServerMetadata: LdapServerMetadataInputTypeDef = ...,
         Logs: LogsTypeDef = ...,
         MaintenanceWindowStartTime: WeeklyStartTimeTypeDef = ...,
         SecurityGroups: Sequence[str] = ...,
         StorageType: BrokerStorageTypeType = ...,
         SubnetIds: Sequence[str] = ...,
-        Tags: Mapping[str, str] = ...
+        Tags: Mapping[str, str] = ...,
+        DataReplicationMode: DataReplicationModeType = ...,
+        DataReplicationPrimaryBrokerArn: str = ...
     ) -> CreateBrokerResponseTypeDef:
         """
         Creates a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.create_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#create_broker)
         """
@@ -172,15 +177,16 @@
     async def create_user(
         self,
         *,
         BrokerId: str,
         Password: str,
         Username: str,
         ConsoleAccess: bool = ...,
-        Groups: Sequence[str] = ...
+        Groups: Sequence[str] = ...,
+        ReplicationUser: bool = ...
     ) -> Dict[str, Any]:
         """
         Creates an ActiveMQ user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.create_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#create_user)
         """
@@ -331,14 +337,22 @@
         """
         Returns a list of all ActiveMQ users.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.list_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#list_users)
         """
 
+    async def promote(self, *, BrokerId: str, Mode: PromoteModeType) -> PromoteResponseTypeDef:
+        """
+        Promotes a data replication replica broker to the primary broker role.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.promote)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#promote)
+        """
+
     async def reboot_broker(self, *, BrokerId: str) -> Dict[str, Any]:
         """
         Reboots a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.reboot_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#reboot_broker)
         """
@@ -351,15 +365,16 @@
         AutoMinorVersionUpgrade: bool = ...,
         Configuration: ConfigurationIdTypeDef = ...,
         EngineVersion: str = ...,
         HostInstanceType: str = ...,
         LdapServerMetadata: LdapServerMetadataInputTypeDef = ...,
         Logs: LogsTypeDef = ...,
         MaintenanceWindowStartTime: WeeklyStartTimeTypeDef = ...,
-        SecurityGroups: Sequence[str] = ...
+        SecurityGroups: Sequence[str] = ...,
+        DataReplicationMode: DataReplicationModeType = ...
     ) -> UpdateBrokerResponseTypeDef:
         """
         Adds a pending configuration change to a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.update_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#update_broker)
         """
@@ -377,15 +392,16 @@
     async def update_user(
         self,
         *,
         BrokerId: str,
         Username: str,
         ConsoleAccess: bool = ...,
         Groups: Sequence[str] = ...,
-        Password: str = ...
+        Password: str = ...,
+        ReplicationUser: bool = ...
     ) -> Dict[str, Any]:
         """
         Updates the information for an ActiveMQ user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.update_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#update_user)
         """
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/client.pyi` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -19,16 +19,18 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AuthenticationStrategyType,
     BrokerStorageTypeType,
+    DataReplicationModeType,
     DeploymentModeType,
     EngineTypeType,
+    PromoteModeType,
 )
 from .paginator import ListBrokersPaginator
 from .type_defs import (
     ConfigurationIdTypeDef,
     CreateBrokerResponseTypeDef,
     CreateConfigurationResponseTypeDef,
     DeleteBrokerResponseTypeDef,
@@ -43,14 +45,15 @@
     LdapServerMetadataInputTypeDef,
     ListBrokersResponseTypeDef,
     ListConfigurationRevisionsResponseTypeDef,
     ListConfigurationsResponseTypeDef,
     ListTagsResponseTypeDef,
     ListUsersResponseTypeDef,
     LogsTypeDef,
+    PromoteResponseTypeDef,
     UpdateBrokerResponseTypeDef,
     UpdateConfigurationResponseTypeDef,
     UserTypeDef,
     WeeklyStartTimeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -123,15 +126,17 @@
         EncryptionOptions: EncryptionOptionsTypeDef = ...,
         LdapServerMetadata: LdapServerMetadataInputTypeDef = ...,
         Logs: LogsTypeDef = ...,
         MaintenanceWindowStartTime: WeeklyStartTimeTypeDef = ...,
         SecurityGroups: Sequence[str] = ...,
         StorageType: BrokerStorageTypeType = ...,
         SubnetIds: Sequence[str] = ...,
-        Tags: Mapping[str, str] = ...
+        Tags: Mapping[str, str] = ...,
+        DataReplicationMode: DataReplicationModeType = ...,
+        DataReplicationPrimaryBrokerArn: str = ...
     ) -> CreateBrokerResponseTypeDef:
         """
         Creates a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.create_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#create_broker)
         """
@@ -162,15 +167,16 @@
     async def create_user(
         self,
         *,
         BrokerId: str,
         Password: str,
         Username: str,
         ConsoleAccess: bool = ...,
-        Groups: Sequence[str] = ...
+        Groups: Sequence[str] = ...,
+        ReplicationUser: bool = ...
     ) -> Dict[str, Any]:
         """
         Creates an ActiveMQ user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.create_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#create_user)
         """
@@ -305,14 +311,21 @@
     ) -> ListUsersResponseTypeDef:
         """
         Returns a list of all ActiveMQ users.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.list_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#list_users)
         """
+    async def promote(self, *, BrokerId: str, Mode: PromoteModeType) -> PromoteResponseTypeDef:
+        """
+        Promotes a data replication replica broker to the primary broker role.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.promote)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#promote)
+        """
     async def reboot_broker(self, *, BrokerId: str) -> Dict[str, Any]:
         """
         Reboots a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.reboot_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#reboot_broker)
         """
@@ -324,15 +337,16 @@
         AutoMinorVersionUpgrade: bool = ...,
         Configuration: ConfigurationIdTypeDef = ...,
         EngineVersion: str = ...,
         HostInstanceType: str = ...,
         LdapServerMetadata: LdapServerMetadataInputTypeDef = ...,
         Logs: LogsTypeDef = ...,
         MaintenanceWindowStartTime: WeeklyStartTimeTypeDef = ...,
-        SecurityGroups: Sequence[str] = ...
+        SecurityGroups: Sequence[str] = ...,
+        DataReplicationMode: DataReplicationModeType = ...
     ) -> UpdateBrokerResponseTypeDef:
         """
         Adds a pending configuration change to a broker.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.update_broker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#update_broker)
         """
@@ -348,15 +362,16 @@
     async def update_user(
         self,
         *,
         BrokerId: str,
         Username: str,
         ConsoleAccess: bool = ...,
         Groups: Sequence[str] = ...,
-        Password: str = ...
+        Password: str = ...,
+        ReplicationUser: bool = ...
     ) -> Dict[str, Any]:
         """
         Updates the information for an ActiveMQ user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Client.update_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/client/#update_user)
         """
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/literals.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/literals.py`

 * *Files 8% similar despite different names*

```diff
@@ -20,18 +20,20 @@
 
 
 __all__ = (
     "AuthenticationStrategyType",
     "BrokerStateType",
     "BrokerStorageTypeType",
     "ChangeTypeType",
+    "DataReplicationModeType",
     "DayOfWeekType",
     "DeploymentModeType",
     "EngineTypeType",
     "ListBrokersPaginatorName",
+    "PromoteModeType",
     "SanitizationWarningReasonType",
     "MQServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -40,24 +42,27 @@
 AuthenticationStrategyType = Literal["LDAP", "SIMPLE"]
 BrokerStateType = Literal[
     "CREATION_FAILED",
     "CREATION_IN_PROGRESS",
     "CRITICAL_ACTION_REQUIRED",
     "DELETION_IN_PROGRESS",
     "REBOOT_IN_PROGRESS",
+    "REPLICA",
     "RUNNING",
 ]
 BrokerStorageTypeType = Literal["EBS", "EFS"]
 ChangeTypeType = Literal["CREATE", "DELETE", "UPDATE"]
+DataReplicationModeType = Literal["CRDR", "NONE"]
 DayOfWeekType = Literal[
     "FRIDAY", "MONDAY", "SATURDAY", "SUNDAY", "THURSDAY", "TUESDAY", "WEDNESDAY"
 ]
 DeploymentModeType = Literal["ACTIVE_STANDBY_MULTI_AZ", "CLUSTER_MULTI_AZ", "SINGLE_INSTANCE"]
 EngineTypeType = Literal["ACTIVEMQ", "RABBITMQ"]
 ListBrokersPaginatorName = Literal["list_brokers"]
+PromoteModeType = Literal["FAILOVER", "SWITCHOVER"]
 SanitizationWarningReasonType = Literal[
     "DISALLOWED_ATTRIBUTE_REMOVED", "DISALLOWED_ELEMENT_REMOVED", "INVALID_ATTRIBUTE_VALUE_REMOVED"
 ]
 MQServiceName = Literal["mq"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -116,14 +121,15 @@
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
@@ -202,14 +208,15 @@
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
@@ -220,14 +227,15 @@
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
@@ -263,14 +271,15 @@
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
@@ -289,16 +298,19 @@
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
@@ -382,15 +394,17 @@
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
@@ -416,21 +430,25 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/literals.pyi` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -19,18 +19,20 @@
     from typing_extensions import Literal
 
 __all__ = (
     "AuthenticationStrategyType",
     "BrokerStateType",
     "BrokerStorageTypeType",
     "ChangeTypeType",
+    "DataReplicationModeType",
     "DayOfWeekType",
     "DeploymentModeType",
     "EngineTypeType",
     "ListBrokersPaginatorName",
+    "PromoteModeType",
     "SanitizationWarningReasonType",
     "MQServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -38,24 +40,27 @@
 AuthenticationStrategyType = Literal["LDAP", "SIMPLE"]
 BrokerStateType = Literal[
     "CREATION_FAILED",
     "CREATION_IN_PROGRESS",
     "CRITICAL_ACTION_REQUIRED",
     "DELETION_IN_PROGRESS",
     "REBOOT_IN_PROGRESS",
+    "REPLICA",
     "RUNNING",
 ]
 BrokerStorageTypeType = Literal["EBS", "EFS"]
 ChangeTypeType = Literal["CREATE", "DELETE", "UPDATE"]
+DataReplicationModeType = Literal["CRDR", "NONE"]
 DayOfWeekType = Literal[
     "FRIDAY", "MONDAY", "SATURDAY", "SUNDAY", "THURSDAY", "TUESDAY", "WEDNESDAY"
 ]
 DeploymentModeType = Literal["ACTIVE_STANDBY_MULTI_AZ", "CLUSTER_MULTI_AZ", "SINGLE_INSTANCE"]
 EngineTypeType = Literal["ACTIVEMQ", "RABBITMQ"]
 ListBrokersPaginatorName = Literal["list_brokers"]
+PromoteModeType = Literal["FAILOVER", "SWITCHOVER"]
 SanitizationWarningReasonType = Literal[
     "DISALLOWED_ATTRIBUTE_REMOVED", "DISALLOWED_ELEMENT_REMOVED", "INVALID_ATTRIBUTE_VALUE_REMOVED"
 ]
 MQServiceName = Literal["mq"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -114,14 +119,15 @@
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
@@ -200,14 +206,15 @@
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
@@ -218,14 +225,15 @@
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
@@ -261,14 +269,15 @@
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
@@ -287,16 +296,19 @@
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
@@ -380,15 +392,17 @@
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
@@ -414,21 +428,25 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/paginator.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("mq") as client:
         client: MQClient
 
         list_brokers_paginator: ListBrokersPaginator = client.get_paginator("list_brokers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListBrokersResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListBrokersPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListBrokersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Paginator.ListBrokers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/paginators/#listbrokerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBrokersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Paginator.ListBrokers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/paginators/#listbrokerspaginator)
         """
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/paginator.pyi` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/paginator.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("mq") as client:
         client: MQClient
 
         list_brokers_paginator: ListBrokersPaginator = client.get_paginator("list_brokers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListBrokersResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListBrokersPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListBrokersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Paginator.ListBrokers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/paginators/#listbrokerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBrokersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ.Paginator.ListBrokers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/paginators/#listbrokerspaginator)
         """
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/type_defs.py` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,17 +16,19 @@
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AuthenticationStrategyType,
     BrokerStateType,
     BrokerStorageTypeType,
     ChangeTypeType,
+    DataReplicationModeType,
     DayOfWeekType,
     DeploymentModeType,
     EngineTypeType,
+    PromoteModeType,
     SanitizationWarningReasonType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
@@ -41,65 +43,69 @@
     "ConfigurationIdTypeDef",
     "ConfigurationRevisionTypeDef",
     "EncryptionOptionsTypeDef",
     "LdapServerMetadataInputTypeDef",
     "LogsTypeDef",
     "UserTypeDef",
     "WeeklyStartTimeTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBrokerResponseTypeDef",
     "CreateConfigurationRequestRequestTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "DataReplicationCounterpartTypeDef",
     "DeleteBrokerRequestRequestTypeDef",
+    "DeleteBrokerResponseTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeBrokerEngineTypesRequestRequestTypeDef",
     "DescribeBrokerInstanceOptionsRequestRequestTypeDef",
     "DescribeBrokerRequestRequestTypeDef",
     "LdapServerMetadataOutputTypeDef",
     "UserSummaryTypeDef",
     "DescribeConfigurationRequestRequestTypeDef",
     "DescribeConfigurationRevisionRequestRequestTypeDef",
+    "DescribeConfigurationRevisionResponseTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "UserPendingChangesTypeDef",
-    "PaginatorConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ListBrokersRequestListBrokersPaginateTypeDef",
     "ListBrokersRequestRequestTypeDef",
     "ListConfigurationRevisionsRequestRequestTypeDef",
     "ListConfigurationsRequestRequestTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
     "ListUsersRequestRequestTypeDef",
     "PendingLogsTypeDef",
+    "PaginatorConfigTypeDef",
+    "PromoteRequestRequestTypeDef",
+    "PromoteResponseTypeDef",
     "RebootBrokerRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SanitizationWarningTypeDef",
     "UpdateConfigurationRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "BrokerInstanceOptionTypeDef",
     "BrokerEngineTypeTypeDef",
+    "ListBrokersResponseTypeDef",
     "ConfigurationsTypeDef",
     "ConfigurationTypeDef",
-    "CreateBrokerRequestRequestTypeDef",
-    "UpdateBrokerRequestRequestTypeDef",
-    "CreateBrokerResponseTypeDef",
     "CreateConfigurationResponseTypeDef",
-    "DeleteBrokerResponseTypeDef",
     "DescribeConfigurationResponseTypeDef",
-    "DescribeConfigurationRevisionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListBrokersResponseTypeDef",
     "ListConfigurationRevisionsResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "UpdateBrokerResponseTypeDef",
+    "CreateBrokerRequestRequestTypeDef",
+    "UpdateBrokerRequestRequestTypeDef",
+    "DataReplicationMetadataOutputTypeDef",
     "ListUsersResponseTypeDef",
     "DescribeUserResponseTypeDef",
-    "ListBrokersRequestListBrokersPaginateTypeDef",
     "LogsSummaryTypeDef",
     "UpdateConfigurationResponseTypeDef",
     "DescribeBrokerInstanceOptionsResponseTypeDef",
     "DescribeBrokerEngineTypesResponseTypeDef",
     "ListConfigurationsResponseTypeDef",
+    "UpdateBrokerResponseTypeDef",
     "DescribeBrokerResponseTypeDef",
 )
 
 ActionRequiredTypeDef = TypedDict(
     "ActionRequiredTypeDef",
     {
         "ActionRequiredCode": str,
@@ -268,14 +274,15 @@
     },
 )
 _OptionalUserTypeDef = TypedDict(
     "_OptionalUserTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 
 class UserTypeDef(_RequiredUserTypeDef, _OptionalUserTypeDef):
     pass
@@ -297,22 +304,20 @@
 )
 
 
 class WeeklyStartTimeTypeDef(_RequiredWeeklyStartTimeTypeDef, _OptionalWeeklyStartTimeTypeDef):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBrokerResponseTypeDef = TypedDict(
+    "CreateBrokerResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "BrokerArn": str,
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConfigurationRequestRequestTypeDef",
     {
         "EngineType": EngineTypeType,
@@ -367,32 +372,49 @@
     },
 )
 _OptionalCreateUserRequestRequestTypeDef = TypedDict(
     "_OptionalCreateUserRequestRequestTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 
 class CreateUserRequestRequestTypeDef(
     _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
 ):
     pass
 
 
+DataReplicationCounterpartTypeDef = TypedDict(
+    "DataReplicationCounterpartTypeDef",
+    {
+        "BrokerId": str,
+        "Region": str,
+    },
+)
+
 DeleteBrokerRequestRequestTypeDef = TypedDict(
     "DeleteBrokerRequestRequestTypeDef",
     {
         "BrokerId": str,
     },
 )
 
+DeleteBrokerResponseTypeDef = TypedDict(
+    "DeleteBrokerResponseTypeDef",
+    {
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTagsRequestRequestTypeDef = TypedDict(
     "DeleteTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -493,14 +515,25 @@
     "DescribeConfigurationRevisionRequestRequestTypeDef",
     {
         "ConfigurationId": str,
         "ConfigurationRevision": str,
     },
 )
 
+DescribeConfigurationRevisionResponseTypeDef = TypedDict(
+    "DescribeConfigurationRevisionResponseTypeDef",
+    {
+        "ConfigurationId": str,
+        "Created": datetime,
+        "Data": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeUserRequestRequestTypeDef = TypedDict(
     "DescribeUserRequestRequestTypeDef",
     {
         "BrokerId": str,
         "Username": str,
     },
 )
@@ -523,20 +556,25 @@
 
 class UserPendingChangesTypeDef(
     _RequiredUserPendingChangesTypeDef, _OptionalUserPendingChangesTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBrokersRequestListBrokersPaginateTypeDef = TypedDict(
+    "ListBrokersRequestListBrokersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBrokersRequestRequestTypeDef = TypedDict(
     "ListBrokersRequestRequestTypeDef",
     {
@@ -581,14 +619,22 @@
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "BrokerId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -612,21 +658,58 @@
     {
         "Audit": bool,
         "General": bool,
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
+PromoteRequestRequestTypeDef = TypedDict(
+    "PromoteRequestRequestTypeDef",
+    {
+        "BrokerId": str,
+        "Mode": PromoteModeType,
+    },
+)
+
+PromoteResponseTypeDef = TypedDict(
+    "PromoteResponseTypeDef",
+    {
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RebootBrokerRequestRequestTypeDef = TypedDict(
     "RebootBrokerRequestRequestTypeDef",
     {
         "BrokerId": str,
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
 _RequiredSanitizationWarningTypeDef = TypedDict(
     "_RequiredSanitizationWarningTypeDef",
     {
         "Reason": SanitizationWarningReasonType,
     },
 )
 _OptionalSanitizationWarningTypeDef = TypedDict(
@@ -677,14 +760,15 @@
 )
 _OptionalUpdateUserRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateUserRequestRequestTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
         "Password": str,
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
@@ -710,14 +794,23 @@
     {
         "EngineType": EngineTypeType,
         "EngineVersions": List[EngineVersionTypeDef],
     },
     total=False,
 )
 
+ListBrokersResponseTypeDef = TypedDict(
+    "ListBrokersResponseTypeDef",
+    {
+        "BrokerSummaries": List[BrokerSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfigurationsTypeDef = TypedDict(
     "ConfigurationsTypeDef",
     {
         "Current": ConfigurationIdTypeDef,
         "History": List[ConfigurationIdTypeDef],
         "Pending": ConfigurationIdTypeDef,
     },
@@ -747,14 +840,55 @@
 )
 
 
 class ConfigurationTypeDef(_RequiredConfigurationTypeDef, _OptionalConfigurationTypeDef):
     pass
 
 
+CreateConfigurationResponseTypeDef = TypedDict(
+    "CreateConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "Created": datetime,
+        "Id": str,
+        "LatestRevision": ConfigurationRevisionTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeConfigurationResponseTypeDef = TypedDict(
+    "DescribeConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "Created": datetime,
+        "Description": str,
+        "EngineType": EngineTypeType,
+        "EngineVersion": str,
+        "Id": str,
+        "LatestRevision": ConfigurationRevisionTypeDef,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConfigurationRevisionsResponseTypeDef = TypedDict(
+    "ListConfigurationRevisionsResponseTypeDef",
+    {
+        "ConfigurationId": str,
+        "MaxResults": int,
+        "NextToken": str,
+        "Revisions": List[ConfigurationRevisionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBrokerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBrokerRequestRequestTypeDef",
     {
         "AutoMinorVersionUpgrade": bool,
         "BrokerName": str,
         "DeploymentMode": DeploymentModeType,
         "EngineType": EngineTypeType,
@@ -774,14 +908,16 @@
         "LdapServerMetadata": LdapServerMetadataInputTypeDef,
         "Logs": LogsTypeDef,
         "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
         "SecurityGroups": Sequence[str],
         "StorageType": BrokerStorageTypeType,
         "SubnetIds": Sequence[str],
         "Tags": Mapping[str, str],
+        "DataReplicationMode": DataReplicationModeType,
+        "DataReplicationPrimaryBrokerArn": str,
     },
     total=False,
 )
 
 
 class CreateBrokerRequestRequestTypeDef(
     _RequiredCreateBrokerRequestRequestTypeDef, _OptionalCreateBrokerRequestRequestTypeDef
@@ -803,164 +939,69 @@
         "Configuration": ConfigurationIdTypeDef,
         "EngineVersion": str,
         "HostInstanceType": str,
         "LdapServerMetadata": LdapServerMetadataInputTypeDef,
         "Logs": LogsTypeDef,
         "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
         "SecurityGroups": Sequence[str],
+        "DataReplicationMode": DataReplicationModeType,
     },
     total=False,
 )
 
 
 class UpdateBrokerRequestRequestTypeDef(
     _RequiredUpdateBrokerRequestRequestTypeDef, _OptionalUpdateBrokerRequestRequestTypeDef
 ):
     pass
 
 
-CreateBrokerResponseTypeDef = TypedDict(
-    "CreateBrokerResponseTypeDef",
-    {
-        "BrokerArn": str,
-        "BrokerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConfigurationResponseTypeDef = TypedDict(
-    "CreateConfigurationResponseTypeDef",
-    {
-        "Arn": str,
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "Created": datetime,
-        "Id": str,
-        "LatestRevision": ConfigurationRevisionTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBrokerResponseTypeDef = TypedDict(
-    "DeleteBrokerResponseTypeDef",
-    {
-        "BrokerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationResponseTypeDef = TypedDict(
-    "DescribeConfigurationResponseTypeDef",
+_RequiredDataReplicationMetadataOutputTypeDef = TypedDict(
+    "_RequiredDataReplicationMetadataOutputTypeDef",
     {
-        "Arn": str,
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "Created": datetime,
-        "Description": str,
-        "EngineType": EngineTypeType,
-        "EngineVersion": str,
-        "Id": str,
-        "LatestRevision": ConfigurationRevisionTypeDef,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationRole": str,
     },
 )
-
-DescribeConfigurationRevisionResponseTypeDef = TypedDict(
-    "DescribeConfigurationRevisionResponseTypeDef",
+_OptionalDataReplicationMetadataOutputTypeDef = TypedDict(
+    "_OptionalDataReplicationMetadataOutputTypeDef",
     {
-        "ConfigurationId": str,
-        "Created": datetime,
-        "Data": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationCounterpart": DataReplicationCounterpartTypeDef,
     },
+    total=False,
 )
 
-ListBrokersResponseTypeDef = TypedDict(
-    "ListBrokersResponseTypeDef",
-    {
-        "BrokerSummaries": List[BrokerSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListConfigurationRevisionsResponseTypeDef = TypedDict(
-    "ListConfigurationRevisionsResponseTypeDef",
-    {
-        "ConfigurationId": str,
-        "MaxResults": int,
-        "NextToken": str,
-        "Revisions": List[ConfigurationRevisionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class DataReplicationMetadataOutputTypeDef(
+    _RequiredDataReplicationMetadataOutputTypeDef, _OptionalDataReplicationMetadataOutputTypeDef
+):
+    pass
 
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBrokerResponseTypeDef = TypedDict(
-    "UpdateBrokerResponseTypeDef",
-    {
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "AutoMinorVersionUpgrade": bool,
-        "BrokerId": str,
-        "Configuration": ConfigurationIdTypeDef,
-        "EngineVersion": str,
-        "HostInstanceType": str,
-        "LdapServerMetadata": LdapServerMetadataOutputTypeDef,
-        "Logs": LogsTypeDef,
-        "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
-        "SecurityGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "BrokerId": str,
         "MaxResults": int,
         "NextToken": str,
         "Users": List[UserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserResponseTypeDef = TypedDict(
     "DescribeUserResponseTypeDef",
     {
         "BrokerId": str,
         "ConsoleAccess": bool,
         "Groups": List[str],
         "Pending": UserPendingChangesTypeDef,
         "Username": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBrokersRequestListBrokersPaginateTypeDef = TypedDict(
-    "ListBrokersRequestListBrokersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ReplicationUser": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredLogsSummaryTypeDef = TypedDict(
     "_RequiredLogsSummaryTypeDef",
     {
         "General": bool,
         "GeneralLogGroup": str,
@@ -986,45 +1027,66 @@
     {
         "Arn": str,
         "Created": datetime,
         "Id": str,
         "LatestRevision": ConfigurationRevisionTypeDef,
         "Name": str,
         "Warnings": List[SanitizationWarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerInstanceOptionsResponseTypeDef = TypedDict(
     "DescribeBrokerInstanceOptionsResponseTypeDef",
     {
         "BrokerInstanceOptions": List[BrokerInstanceOptionTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerEngineTypesResponseTypeDef = TypedDict(
     "DescribeBrokerEngineTypesResponseTypeDef",
     {
         "BrokerEngineTypes": List[BrokerEngineTypeTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfigurationsResponseTypeDef = TypedDict(
     "ListConfigurationsResponseTypeDef",
     {
         "Configurations": List[ConfigurationTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBrokerResponseTypeDef = TypedDict(
+    "UpdateBrokerResponseTypeDef",
+    {
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "AutoMinorVersionUpgrade": bool,
+        "BrokerId": str,
+        "Configuration": ConfigurationIdTypeDef,
+        "EngineVersion": str,
+        "HostInstanceType": str,
+        "LdapServerMetadata": LdapServerMetadataOutputTypeDef,
+        "Logs": LogsTypeDef,
+        "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
+        "SecurityGroups": List[str],
+        "DataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "DataReplicationMode": DataReplicationModeType,
+        "PendingDataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "PendingDataReplicationMode": DataReplicationModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerResponseTypeDef = TypedDict(
     "DescribeBrokerResponseTypeDef",
     {
         "ActionsRequired": List[ActionRequiredTypeDef],
@@ -1052,10 +1114,14 @@
         "PendingSecurityGroups": List[str],
         "PubliclyAccessible": bool,
         "SecurityGroups": List[str],
         "StorageType": BrokerStorageTypeType,
         "SubnetIds": List[str],
         "Tags": Dict[str, str],
         "Users": List[UserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "DataReplicationMode": DataReplicationModeType,
+        "PendingDataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "PendingDataReplicationMode": DataReplicationModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq/type_defs.pyi` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,17 +16,19 @@
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AuthenticationStrategyType,
     BrokerStateType,
     BrokerStorageTypeType,
     ChangeTypeType,
+    DataReplicationModeType,
     DayOfWeekType,
     DeploymentModeType,
     EngineTypeType,
+    PromoteModeType,
     SanitizationWarningReasonType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
@@ -40,65 +42,69 @@
     "ConfigurationIdTypeDef",
     "ConfigurationRevisionTypeDef",
     "EncryptionOptionsTypeDef",
     "LdapServerMetadataInputTypeDef",
     "LogsTypeDef",
     "UserTypeDef",
     "WeeklyStartTimeTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBrokerResponseTypeDef",
     "CreateConfigurationRequestRequestTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "DataReplicationCounterpartTypeDef",
     "DeleteBrokerRequestRequestTypeDef",
+    "DeleteBrokerResponseTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeBrokerEngineTypesRequestRequestTypeDef",
     "DescribeBrokerInstanceOptionsRequestRequestTypeDef",
     "DescribeBrokerRequestRequestTypeDef",
     "LdapServerMetadataOutputTypeDef",
     "UserSummaryTypeDef",
     "DescribeConfigurationRequestRequestTypeDef",
     "DescribeConfigurationRevisionRequestRequestTypeDef",
+    "DescribeConfigurationRevisionResponseTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "UserPendingChangesTypeDef",
-    "PaginatorConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ListBrokersRequestListBrokersPaginateTypeDef",
     "ListBrokersRequestRequestTypeDef",
     "ListConfigurationRevisionsRequestRequestTypeDef",
     "ListConfigurationsRequestRequestTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
     "ListUsersRequestRequestTypeDef",
     "PendingLogsTypeDef",
+    "PaginatorConfigTypeDef",
+    "PromoteRequestRequestTypeDef",
+    "PromoteResponseTypeDef",
     "RebootBrokerRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SanitizationWarningTypeDef",
     "UpdateConfigurationRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "BrokerInstanceOptionTypeDef",
     "BrokerEngineTypeTypeDef",
+    "ListBrokersResponseTypeDef",
     "ConfigurationsTypeDef",
     "ConfigurationTypeDef",
-    "CreateBrokerRequestRequestTypeDef",
-    "UpdateBrokerRequestRequestTypeDef",
-    "CreateBrokerResponseTypeDef",
     "CreateConfigurationResponseTypeDef",
-    "DeleteBrokerResponseTypeDef",
     "DescribeConfigurationResponseTypeDef",
-    "DescribeConfigurationRevisionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListBrokersResponseTypeDef",
     "ListConfigurationRevisionsResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "UpdateBrokerResponseTypeDef",
+    "CreateBrokerRequestRequestTypeDef",
+    "UpdateBrokerRequestRequestTypeDef",
+    "DataReplicationMetadataOutputTypeDef",
     "ListUsersResponseTypeDef",
     "DescribeUserResponseTypeDef",
-    "ListBrokersRequestListBrokersPaginateTypeDef",
     "LogsSummaryTypeDef",
     "UpdateConfigurationResponseTypeDef",
     "DescribeBrokerInstanceOptionsResponseTypeDef",
     "DescribeBrokerEngineTypesResponseTypeDef",
     "ListConfigurationsResponseTypeDef",
+    "UpdateBrokerResponseTypeDef",
     "DescribeBrokerResponseTypeDef",
 )
 
 ActionRequiredTypeDef = TypedDict(
     "ActionRequiredTypeDef",
     {
         "ActionRequiredCode": str,
@@ -257,14 +263,15 @@
     },
 )
 _OptionalUserTypeDef = TypedDict(
     "_OptionalUserTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 class UserTypeDef(_RequiredUserTypeDef, _OptionalUserTypeDef):
     pass
 
@@ -282,22 +289,20 @@
     },
     total=False,
 )
 
 class WeeklyStartTimeTypeDef(_RequiredWeeklyStartTimeTypeDef, _OptionalWeeklyStartTimeTypeDef):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBrokerResponseTypeDef = TypedDict(
+    "CreateBrokerResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "BrokerArn": str,
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConfigurationRequestRequestTypeDef",
     {
         "EngineType": EngineTypeType,
@@ -348,30 +353,47 @@
     },
 )
 _OptionalCreateUserRequestRequestTypeDef = TypedDict(
     "_OptionalCreateUserRequestRequestTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 class CreateUserRequestRequestTypeDef(
     _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
 ):
     pass
 
+DataReplicationCounterpartTypeDef = TypedDict(
+    "DataReplicationCounterpartTypeDef",
+    {
+        "BrokerId": str,
+        "Region": str,
+    },
+)
+
 DeleteBrokerRequestRequestTypeDef = TypedDict(
     "DeleteBrokerRequestRequestTypeDef",
     {
         "BrokerId": str,
     },
 )
 
+DeleteBrokerResponseTypeDef = TypedDict(
+    "DeleteBrokerResponseTypeDef",
+    {
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTagsRequestRequestTypeDef = TypedDict(
     "DeleteTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -468,14 +490,25 @@
     "DescribeConfigurationRevisionRequestRequestTypeDef",
     {
         "ConfigurationId": str,
         "ConfigurationRevision": str,
     },
 )
 
+DescribeConfigurationRevisionResponseTypeDef = TypedDict(
+    "DescribeConfigurationRevisionResponseTypeDef",
+    {
+        "ConfigurationId": str,
+        "Created": datetime,
+        "Data": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeUserRequestRequestTypeDef = TypedDict(
     "DescribeUserRequestRequestTypeDef",
     {
         "BrokerId": str,
         "Username": str,
     },
 )
@@ -496,20 +529,25 @@
 )
 
 class UserPendingChangesTypeDef(
     _RequiredUserPendingChangesTypeDef, _OptionalUserPendingChangesTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBrokersRequestListBrokersPaginateTypeDef = TypedDict(
+    "ListBrokersRequestListBrokersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBrokersRequestRequestTypeDef = TypedDict(
     "ListBrokersRequestRequestTypeDef",
     {
@@ -552,14 +590,22 @@
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "BrokerId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -581,21 +627,58 @@
     {
         "Audit": bool,
         "General": bool,
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
+PromoteRequestRequestTypeDef = TypedDict(
+    "PromoteRequestRequestTypeDef",
+    {
+        "BrokerId": str,
+        "Mode": PromoteModeType,
+    },
+)
+
+PromoteResponseTypeDef = TypedDict(
+    "PromoteResponseTypeDef",
+    {
+        "BrokerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RebootBrokerRequestRequestTypeDef = TypedDict(
     "RebootBrokerRequestRequestTypeDef",
     {
         "BrokerId": str,
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
 _RequiredSanitizationWarningTypeDef = TypedDict(
     "_RequiredSanitizationWarningTypeDef",
     {
         "Reason": SanitizationWarningReasonType,
     },
 )
 _OptionalSanitizationWarningTypeDef = TypedDict(
@@ -642,14 +725,15 @@
 )
 _OptionalUpdateUserRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateUserRequestRequestTypeDef",
     {
         "ConsoleAccess": bool,
         "Groups": Sequence[str],
         "Password": str,
+        "ReplicationUser": bool,
     },
     total=False,
 )
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
 ):
@@ -673,14 +757,23 @@
     {
         "EngineType": EngineTypeType,
         "EngineVersions": List[EngineVersionTypeDef],
     },
     total=False,
 )
 
+ListBrokersResponseTypeDef = TypedDict(
+    "ListBrokersResponseTypeDef",
+    {
+        "BrokerSummaries": List[BrokerSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfigurationsTypeDef = TypedDict(
     "ConfigurationsTypeDef",
     {
         "Current": ConfigurationIdTypeDef,
         "History": List[ConfigurationIdTypeDef],
         "Pending": ConfigurationIdTypeDef,
     },
@@ -708,14 +801,55 @@
     },
     total=False,
 )
 
 class ConfigurationTypeDef(_RequiredConfigurationTypeDef, _OptionalConfigurationTypeDef):
     pass
 
+CreateConfigurationResponseTypeDef = TypedDict(
+    "CreateConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "Created": datetime,
+        "Id": str,
+        "LatestRevision": ConfigurationRevisionTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeConfigurationResponseTypeDef = TypedDict(
+    "DescribeConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "Created": datetime,
+        "Description": str,
+        "EngineType": EngineTypeType,
+        "EngineVersion": str,
+        "Id": str,
+        "LatestRevision": ConfigurationRevisionTypeDef,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConfigurationRevisionsResponseTypeDef = TypedDict(
+    "ListConfigurationRevisionsResponseTypeDef",
+    {
+        "ConfigurationId": str,
+        "MaxResults": int,
+        "NextToken": str,
+        "Revisions": List[ConfigurationRevisionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBrokerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBrokerRequestRequestTypeDef",
     {
         "AutoMinorVersionUpgrade": bool,
         "BrokerName": str,
         "DeploymentMode": DeploymentModeType,
         "EngineType": EngineTypeType,
@@ -735,14 +869,16 @@
         "LdapServerMetadata": LdapServerMetadataInputTypeDef,
         "Logs": LogsTypeDef,
         "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
         "SecurityGroups": Sequence[str],
         "StorageType": BrokerStorageTypeType,
         "SubnetIds": Sequence[str],
         "Tags": Mapping[str, str],
+        "DataReplicationMode": DataReplicationModeType,
+        "DataReplicationPrimaryBrokerArn": str,
     },
     total=False,
 )
 
 class CreateBrokerRequestRequestTypeDef(
     _RequiredCreateBrokerRequestRequestTypeDef, _OptionalCreateBrokerRequestRequestTypeDef
 ):
@@ -762,162 +898,65 @@
         "Configuration": ConfigurationIdTypeDef,
         "EngineVersion": str,
         "HostInstanceType": str,
         "LdapServerMetadata": LdapServerMetadataInputTypeDef,
         "Logs": LogsTypeDef,
         "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
         "SecurityGroups": Sequence[str],
+        "DataReplicationMode": DataReplicationModeType,
     },
     total=False,
 )
 
 class UpdateBrokerRequestRequestTypeDef(
     _RequiredUpdateBrokerRequestRequestTypeDef, _OptionalUpdateBrokerRequestRequestTypeDef
 ):
     pass
 
-CreateBrokerResponseTypeDef = TypedDict(
-    "CreateBrokerResponseTypeDef",
-    {
-        "BrokerArn": str,
-        "BrokerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConfigurationResponseTypeDef = TypedDict(
-    "CreateConfigurationResponseTypeDef",
-    {
-        "Arn": str,
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "Created": datetime,
-        "Id": str,
-        "LatestRevision": ConfigurationRevisionTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBrokerResponseTypeDef = TypedDict(
-    "DeleteBrokerResponseTypeDef",
-    {
-        "BrokerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationResponseTypeDef = TypedDict(
-    "DescribeConfigurationResponseTypeDef",
-    {
-        "Arn": str,
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "Created": datetime,
-        "Description": str,
-        "EngineType": EngineTypeType,
-        "EngineVersion": str,
-        "Id": str,
-        "LatestRevision": ConfigurationRevisionTypeDef,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationRevisionResponseTypeDef = TypedDict(
-    "DescribeConfigurationRevisionResponseTypeDef",
-    {
-        "ConfigurationId": str,
-        "Created": datetime,
-        "Data": str,
-        "Description": str,
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
-ListBrokersResponseTypeDef = TypedDict(
-    "ListBrokersResponseTypeDef",
-    {
-        "BrokerSummaries": List[BrokerSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationRevisionsResponseTypeDef = TypedDict(
-    "ListConfigurationRevisionsResponseTypeDef",
+_RequiredDataReplicationMetadataOutputTypeDef = TypedDict(
+    "_RequiredDataReplicationMetadataOutputTypeDef",
     {
-        "ConfigurationId": str,
-        "MaxResults": int,
-        "NextToken": str,
-        "Revisions": List[ConfigurationRevisionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationRole": str,
     },
 )
-
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
+_OptionalDataReplicationMetadataOutputTypeDef = TypedDict(
+    "_OptionalDataReplicationMetadataOutputTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationCounterpart": DataReplicationCounterpartTypeDef,
     },
+    total=False,
 )
 
-UpdateBrokerResponseTypeDef = TypedDict(
-    "UpdateBrokerResponseTypeDef",
-    {
-        "AuthenticationStrategy": AuthenticationStrategyType,
-        "AutoMinorVersionUpgrade": bool,
-        "BrokerId": str,
-        "Configuration": ConfigurationIdTypeDef,
-        "EngineVersion": str,
-        "HostInstanceType": str,
-        "LdapServerMetadata": LdapServerMetadataOutputTypeDef,
-        "Logs": LogsTypeDef,
-        "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
-        "SecurityGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class DataReplicationMetadataOutputTypeDef(
+    _RequiredDataReplicationMetadataOutputTypeDef, _OptionalDataReplicationMetadataOutputTypeDef
+):
+    pass
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "BrokerId": str,
         "MaxResults": int,
         "NextToken": str,
         "Users": List[UserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserResponseTypeDef = TypedDict(
     "DescribeUserResponseTypeDef",
     {
         "BrokerId": str,
         "ConsoleAccess": bool,
         "Groups": List[str],
         "Pending": UserPendingChangesTypeDef,
         "Username": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBrokersRequestListBrokersPaginateTypeDef = TypedDict(
-    "ListBrokersRequestListBrokersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ReplicationUser": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredLogsSummaryTypeDef = TypedDict(
     "_RequiredLogsSummaryTypeDef",
     {
         "General": bool,
         "GeneralLogGroup": str,
@@ -941,45 +980,66 @@
     {
         "Arn": str,
         "Created": datetime,
         "Id": str,
         "LatestRevision": ConfigurationRevisionTypeDef,
         "Name": str,
         "Warnings": List[SanitizationWarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerInstanceOptionsResponseTypeDef = TypedDict(
     "DescribeBrokerInstanceOptionsResponseTypeDef",
     {
         "BrokerInstanceOptions": List[BrokerInstanceOptionTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerEngineTypesResponseTypeDef = TypedDict(
     "DescribeBrokerEngineTypesResponseTypeDef",
     {
         "BrokerEngineTypes": List[BrokerEngineTypeTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfigurationsResponseTypeDef = TypedDict(
     "ListConfigurationsResponseTypeDef",
     {
         "Configurations": List[ConfigurationTypeDef],
         "MaxResults": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBrokerResponseTypeDef = TypedDict(
+    "UpdateBrokerResponseTypeDef",
+    {
+        "AuthenticationStrategy": AuthenticationStrategyType,
+        "AutoMinorVersionUpgrade": bool,
+        "BrokerId": str,
+        "Configuration": ConfigurationIdTypeDef,
+        "EngineVersion": str,
+        "HostInstanceType": str,
+        "LdapServerMetadata": LdapServerMetadataOutputTypeDef,
+        "Logs": LogsTypeDef,
+        "MaintenanceWindowStartTime": WeeklyStartTimeTypeDef,
+        "SecurityGroups": List[str],
+        "DataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "DataReplicationMode": DataReplicationModeType,
+        "PendingDataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "PendingDataReplicationMode": DataReplicationModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBrokerResponseTypeDef = TypedDict(
     "DescribeBrokerResponseTypeDef",
     {
         "ActionsRequired": List[ActionRequiredTypeDef],
@@ -1007,10 +1067,14 @@
         "PendingSecurityGroups": List[str],
         "PubliclyAccessible": bool,
         "SecurityGroups": List[str],
         "StorageType": BrokerStorageTypeType,
         "SubnetIds": List[str],
         "Tags": Dict[str, str],
         "Users": List[UserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "DataReplicationMode": DataReplicationModeType,
+        "PendingDataReplicationMetadata": DataReplicationMetadataOutputTypeDef,
+        "PendingDataReplicationMode": DataReplicationModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/PKG-INFO` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mq
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MQ 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MQ 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mq"></a>
 
 # types-aiobotocore-mq
 
 [![PyPI - types-aiobotocore-mq](https://img.shields.io/pypi/v/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mq.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mq)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mq?color=blue)](https://pypistats.org/packages/types-aiobotocore-mq)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MQ 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
+[aiobotocore.MQ 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
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
 [types-aiobotocore-mq docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mq/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,18 +294,20 @@
 
 ```python
 from types_aiobotocore_mq.literals import (
     AuthenticationStrategyType,
     BrokerStateType,
     BrokerStorageTypeType,
     ChangeTypeType,
+    DataReplicationModeType,
     DayOfWeekType,
     DeploymentModeType,
     EngineTypeType,
     ListBrokersPaginatorName,
+    PromoteModeType,
     SanitizationWarningReasonType,
     MQServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -332,65 +334,69 @@
     ConfigurationIdTypeDef,
     ConfigurationRevisionTypeDef,
     EncryptionOptionsTypeDef,
     LdapServerMetadataInputTypeDef,
     LogsTypeDef,
     UserTypeDef,
     WeeklyStartTimeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBrokerResponseTypeDef,
     CreateConfigurationRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     CreateUserRequestRequestTypeDef,
+    DataReplicationCounterpartTypeDef,
     DeleteBrokerRequestRequestTypeDef,
+    DeleteBrokerResponseTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeBrokerEngineTypesRequestRequestTypeDef,
     DescribeBrokerInstanceOptionsRequestRequestTypeDef,
     DescribeBrokerRequestRequestTypeDef,
     LdapServerMetadataOutputTypeDef,
     UserSummaryTypeDef,
     DescribeConfigurationRequestRequestTypeDef,
     DescribeConfigurationRevisionRequestRequestTypeDef,
+    DescribeConfigurationRevisionResponseTypeDef,
     DescribeUserRequestRequestTypeDef,
     UserPendingChangesTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListBrokersRequestListBrokersPaginateTypeDef,
     ListBrokersRequestRequestTypeDef,
     ListConfigurationRevisionsRequestRequestTypeDef,
     ListConfigurationsRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     ListUsersRequestRequestTypeDef,
     PendingLogsTypeDef,
+    PaginatorConfigTypeDef,
+    PromoteRequestRequestTypeDef,
+    PromoteResponseTypeDef,
     RebootBrokerRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SanitizationWarningTypeDef,
     UpdateConfigurationRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     BrokerInstanceOptionTypeDef,
     BrokerEngineTypeTypeDef,
+    ListBrokersResponseTypeDef,
     ConfigurationsTypeDef,
     ConfigurationTypeDef,
-    CreateBrokerRequestRequestTypeDef,
-    UpdateBrokerRequestRequestTypeDef,
-    CreateBrokerResponseTypeDef,
     CreateConfigurationResponseTypeDef,
-    DeleteBrokerResponseTypeDef,
     DescribeConfigurationResponseTypeDef,
-    DescribeConfigurationRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListBrokersResponseTypeDef,
     ListConfigurationRevisionsResponseTypeDef,
-    ListTagsResponseTypeDef,
-    UpdateBrokerResponseTypeDef,
+    CreateBrokerRequestRequestTypeDef,
+    UpdateBrokerRequestRequestTypeDef,
+    DataReplicationMetadataOutputTypeDef,
     ListUsersResponseTypeDef,
     DescribeUserResponseTypeDef,
-    ListBrokersRequestListBrokersPaginateTypeDef,
     LogsSummaryTypeDef,
     UpdateConfigurationResponseTypeDef,
     DescribeBrokerInstanceOptionsResponseTypeDef,
     DescribeBrokerEngineTypesResponseTypeDef,
     ListConfigurationsResponseTypeDef,
+    UpdateBrokerResponseTypeDef,
     DescribeBrokerResponseTypeDef,
 )
 
 
 def get_structure() -> ActionRequiredTypeDef:
     return {...}
 ```
@@ -398,43 +404,43 @@
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

### Comparing `types-aiobotocore-mq-2.5.0.post1/types_aiobotocore_mq.egg-info/SOURCES.txt` & `types-aiobotocore-mq-2.5.1/types_aiobotocore_mq.egg-info/SOURCES.txt`

 * *Files identical despite different names*

