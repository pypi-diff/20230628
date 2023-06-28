# Comparing `tmp/types-aiobotocore-securitylake-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-securitylake-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-securitylake-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-securitylake-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-securitylake-2.5.0.post1.tar` & `types-aiobotocore-securitylake-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.691611 types-aiobotocore-securitylake-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16567 2023-03-11 12:27:18.691611 types-aiobotocore-securitylake-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14976 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.691611 types-aiobotocore-securitylake-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.671611 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/
--rw-r--r--   0 runner    (1001) docker     (123)     1359 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1358 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28023 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27980 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10111 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10109 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6015 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6008 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20942 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20925 2023-03-11 12:23:54.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:53.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.691611 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16567 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:27:18.000000 types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.910212 types-aiobotocore-securitylake-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16914 2023-06-28 01:44:09.902212 types-aiobotocore-securitylake-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15329 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.910212 types-aiobotocore-securitylake-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.902212 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/
+-rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1368 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25766 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25725 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9004 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5754 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5748 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    24192 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24169 2023-06-28 01:40:43.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:42.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.902212 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16914 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:44:09.000000 types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/LICENSE` & `types-aiobotocore-securitylake-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/PKG-INFO` & `types-aiobotocore-securitylake-2.5.1/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-securitylake
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecurityLake 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore securitylake type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-securitylake"></a>
 
 # types-aiobotocore-securitylake
 
 [![PyPI - types-aiobotocore-securitylake](https://img.shields.io/pypi/v/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securitylake?color=blue)](https://pypistats.org/packages/types-aiobotocore-securitylake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
+[aiobotocore.SecurityLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
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
 [types-aiobotocore-securitylake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,31 +240,31 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_securitylake import SecurityLakeClient
 from types_aiobotocore_securitylake.paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 
 session = get_session()
 async with session.create_client("securitylake") as client:
     client: SecurityLakeClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
-    get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator(
-        "get_datalake_status"
+    get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator(
+        "get_data_lake_sources"
     )
-    list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator(
-        "list_datalake_exceptions"
+    list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator(
+        "list_data_lake_exceptions"
     )
     list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
     list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
 ```
 
 <a id="literals"></a>
 
@@ -305,29 +272,23 @@
 
 `types_aiobotocore_securitylake.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securitylake.literals import (
     AccessTypeType,
-    AwsLogSourceTypeType,
-    DimensionType,
-    EndpointProtocolType,
-    GetDatalakeStatusPaginatorName,
-    HttpsMethodType,
-    ListDatalakeExceptionsPaginatorName,
+    AwsLogSourceNameType,
+    DataLakeStatusType,
+    GetDataLakeSourcesPaginatorName,
+    HttpMethodType,
+    ListDataLakeExceptionsPaginatorName,
     ListLogSourcesPaginatorName,
     ListSubscribersPaginatorName,
-    OcsfEventClassType,
-    RegionType,
-    SourceStatusType,
-    StorageClassType,
-    SubscriptionProtocolTypeType,
-    SubscriptionStatusType,
-    settingsStatusType,
+    SourceCollectionStatusType,
+    SubscriberStatusType,
     SecurityLakeServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -341,116 +302,130 @@
 ### Typed dictionaries
 
 `types_aiobotocore_securitylake.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_securitylake.type_defs import (
-    LogsStatusTypeDef,
-    AutoEnableNewRegionConfigurationTypeDef,
-    CreateAwsLogSourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    CreateCustomLogSourceRequestRequestTypeDef,
-    CreateDatalakeDelegatedAdminRequestRequestTypeDef,
-    CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    SourceTypeTypeDef,
-    CreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    DeleteAwsLogSourceRequestRequestTypeDef,
+    AwsIdentityTypeDef,
+    AwsLogSourceConfigurationTypeDef,
+    AwsLogSourceResourceTypeDef,
+    CreateAwsLogSourceResponseTypeDef,
+    CreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    CreateSubscriberNotificationResponseTypeDef,
+    CustomLogSourceAttributesTypeDef,
+    CustomLogSourceCrawlerConfigurationTypeDef,
+    CustomLogSourceProviderTypeDef,
+    DataLakeEncryptionConfigurationTypeDef,
+    DataLakeReplicationConfigurationTypeDef,
+    DataLakeExceptionTypeDef,
+    DataLakeLifecycleExpirationTypeDef,
+    DataLakeLifecycleTransitionTypeDef,
+    DataLakeSourceStatusTypeDef,
+    DataLakeUpdateExceptionTypeDef,
+    DeleteAwsLogSourceResponseTypeDef,
     DeleteCustomLogSourceRequestRequestTypeDef,
-    DeleteDatalakeDelegatedAdminRequestRequestTypeDef,
+    DeleteDataLakeRequestRequestTypeDef,
+    DeleteSubscriberNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
-    DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    FailuresTypeDef,
-    ProtocolAndNotificationEndpointTypeDef,
-    PaginatorConfigTypeDef,
-    GetDatalakeStatusRequestRequestTypeDef,
+    GetDataLakeExceptionSubscriptionResponseTypeDef,
+    GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef,
+    GetDataLakeSourcesRequestRequestTypeDef,
     GetSubscriberRequestRequestTypeDef,
-    RetentionSettingTypeDef,
-    ListDatalakeExceptionsRequestRequestTypeDef,
-    ListLogSourcesRequestRequestTypeDef,
+    HttpsNotificationConfigurationTypeDef,
+    ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef,
+    ListDataLakeExceptionsRequestRequestTypeDef,
+    ListDataLakesRequestRequestTypeDef,
+    ListSubscribersRequestListSubscribersPaginateTypeDef,
     ListSubscribersRequestRequestTypeDef,
-    UpdateDatalakeExceptionsExpiryRequestRequestTypeDef,
-    UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    AccountSourcesTypeDef,
-    CreateDatalakeAutoEnableRequestRequestTypeDef,
-    DeleteDatalakeAutoEnableRequestRequestTypeDef,
-    CreateAwsLogSourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    UpdateSubscriberNotificationResponseTypeDef,
+    CreateAwsLogSourceRequestRequestTypeDef,
+    DeleteAwsLogSourceRequestRequestTypeDef,
+    DataLakeAutoEnableNewAccountConfigurationTypeDef,
+    CustomLogSourceConfigurationTypeDef,
+    CustomLogSourceResourceTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
+    DataLakeLifecycleConfigurationTypeDef,
+    DataLakeSourceTypeDef,
+    DataLakeUpdateStatusTypeDef,
+    NotificationConfigurationTypeDef,
+    CreateDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    GetDataLakeOrganizationConfigurationResponseTypeDef,
+    CreateCustomLogSourceRequestRequestTypeDef,
     CreateCustomLogSourceResponseTypeDef,
-    CreateSubscriberResponseTypeDef,
-    CreateSubscriptionNotificationConfigurationResponseTypeDef,
-    DeleteAwsLogSourceResponseTypeDef,
-    DeleteCustomLogSourceResponseTypeDef,
-    DeleteDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeAutoEnableResponseTypeDef,
-    GetDatalakeExceptionsExpiryResponseTypeDef,
-    ListLogSourcesResponseTypeDef,
-    UpdateSubscriptionNotificationConfigurationResponseTypeDef,
+    LogSourceResourceTypeDef,
+    DataLakeConfigurationTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
+    DataLakeResourceTypeDef,
+    CreateSubscriberNotificationRequestRequestTypeDef,
+    UpdateSubscriberNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
+    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
+    ListLogSourcesRequestRequestTypeDef,
+    LogSourceTypeDef,
     SubscriberResourceTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
-    FailuresResponseTypeDef,
-    GetDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef,
-    ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef,
-    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
-    ListSubscribersRequestListSubscribersPaginateTypeDef,
-    LakeConfigurationRequestTypeDef,
-    LakeConfigurationResponseTypeDef,
-    GetDatalakeStatusResponseTypeDef,
+    CreateDataLakeRequestRequestTypeDef,
+    UpdateDataLakeRequestRequestTypeDef,
+    CreateDataLakeResponseTypeDef,
+    ListDataLakesResponseTypeDef,
+    UpdateDataLakeResponseTypeDef,
+    ListLogSourcesResponseTypeDef,
+    CreateSubscriberResponseTypeDef,
     GetSubscriberResponseTypeDef,
     ListSubscribersResponseTypeDef,
     UpdateSubscriberResponseTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
-    CreateDatalakeRequestRequestTypeDef,
-    UpdateDatalakeRequestRequestTypeDef,
-    GetDatalakeResponseTypeDef,
 )
 
 
-def get_structure() -> LogsStatusTypeDef:
+def get_structure() -> AwsIdentityTypeDef:
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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/README.md` & `types-aiobotocore-securitylake-2.5.1/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-securitylake
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecurityLake 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore securitylake type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-securitylake"></a>
 
 # types-aiobotocore-securitylake
 
 [![PyPI - types-aiobotocore-securitylake](https://img.shields.io/pypi/v/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securitylake?color=blue)](https://pypistats.org/packages/types-aiobotocore-securitylake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
+[aiobotocore.SecurityLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
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
 [types-aiobotocore-securitylake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -240,31 +273,31 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_securitylake import SecurityLakeClient
 from types_aiobotocore_securitylake.paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 
 session = get_session()
 async with session.create_client("securitylake") as client:
     client: SecurityLakeClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
-    get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator(
-        "get_datalake_status"
+    get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator(
+        "get_data_lake_sources"
     )
-    list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator(
-        "list_datalake_exceptions"
+    list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator(
+        "list_data_lake_exceptions"
     )
     list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
     list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
 ```
 
 <a id="literals"></a>
 
@@ -272,29 +305,23 @@
 
 `types_aiobotocore_securitylake.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securitylake.literals import (
     AccessTypeType,
-    AwsLogSourceTypeType,
-    DimensionType,
-    EndpointProtocolType,
-    GetDatalakeStatusPaginatorName,
-    HttpsMethodType,
-    ListDatalakeExceptionsPaginatorName,
+    AwsLogSourceNameType,
+    DataLakeStatusType,
+    GetDataLakeSourcesPaginatorName,
+    HttpMethodType,
+    ListDataLakeExceptionsPaginatorName,
     ListLogSourcesPaginatorName,
     ListSubscribersPaginatorName,
-    OcsfEventClassType,
-    RegionType,
-    SourceStatusType,
-    StorageClassType,
-    SubscriptionProtocolTypeType,
-    SubscriptionStatusType,
-    settingsStatusType,
+    SourceCollectionStatusType,
+    SubscriberStatusType,
     SecurityLakeServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -308,116 +335,130 @@
 ### Typed dictionaries
 
 `types_aiobotocore_securitylake.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_securitylake.type_defs import (
-    LogsStatusTypeDef,
-    AutoEnableNewRegionConfigurationTypeDef,
-    CreateAwsLogSourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    CreateCustomLogSourceRequestRequestTypeDef,
-    CreateDatalakeDelegatedAdminRequestRequestTypeDef,
-    CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    SourceTypeTypeDef,
-    CreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    DeleteAwsLogSourceRequestRequestTypeDef,
+    AwsIdentityTypeDef,
+    AwsLogSourceConfigurationTypeDef,
+    AwsLogSourceResourceTypeDef,
+    CreateAwsLogSourceResponseTypeDef,
+    CreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    CreateSubscriberNotificationResponseTypeDef,
+    CustomLogSourceAttributesTypeDef,
+    CustomLogSourceCrawlerConfigurationTypeDef,
+    CustomLogSourceProviderTypeDef,
+    DataLakeEncryptionConfigurationTypeDef,
+    DataLakeReplicationConfigurationTypeDef,
+    DataLakeExceptionTypeDef,
+    DataLakeLifecycleExpirationTypeDef,
+    DataLakeLifecycleTransitionTypeDef,
+    DataLakeSourceStatusTypeDef,
+    DataLakeUpdateExceptionTypeDef,
+    DeleteAwsLogSourceResponseTypeDef,
     DeleteCustomLogSourceRequestRequestTypeDef,
-    DeleteDatalakeDelegatedAdminRequestRequestTypeDef,
+    DeleteDataLakeRequestRequestTypeDef,
+    DeleteSubscriberNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
-    DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    FailuresTypeDef,
-    ProtocolAndNotificationEndpointTypeDef,
-    PaginatorConfigTypeDef,
-    GetDatalakeStatusRequestRequestTypeDef,
+    GetDataLakeExceptionSubscriptionResponseTypeDef,
+    GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef,
+    GetDataLakeSourcesRequestRequestTypeDef,
     GetSubscriberRequestRequestTypeDef,
-    RetentionSettingTypeDef,
-    ListDatalakeExceptionsRequestRequestTypeDef,
-    ListLogSourcesRequestRequestTypeDef,
+    HttpsNotificationConfigurationTypeDef,
+    ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef,
+    ListDataLakeExceptionsRequestRequestTypeDef,
+    ListDataLakesRequestRequestTypeDef,
+    ListSubscribersRequestListSubscribersPaginateTypeDef,
     ListSubscribersRequestRequestTypeDef,
-    UpdateDatalakeExceptionsExpiryRequestRequestTypeDef,
-    UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    AccountSourcesTypeDef,
-    CreateDatalakeAutoEnableRequestRequestTypeDef,
-    DeleteDatalakeAutoEnableRequestRequestTypeDef,
-    CreateAwsLogSourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    UpdateSubscriberNotificationResponseTypeDef,
+    CreateAwsLogSourceRequestRequestTypeDef,
+    DeleteAwsLogSourceRequestRequestTypeDef,
+    DataLakeAutoEnableNewAccountConfigurationTypeDef,
+    CustomLogSourceConfigurationTypeDef,
+    CustomLogSourceResourceTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
+    DataLakeLifecycleConfigurationTypeDef,
+    DataLakeSourceTypeDef,
+    DataLakeUpdateStatusTypeDef,
+    NotificationConfigurationTypeDef,
+    CreateDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    GetDataLakeOrganizationConfigurationResponseTypeDef,
+    CreateCustomLogSourceRequestRequestTypeDef,
     CreateCustomLogSourceResponseTypeDef,
-    CreateSubscriberResponseTypeDef,
-    CreateSubscriptionNotificationConfigurationResponseTypeDef,
-    DeleteAwsLogSourceResponseTypeDef,
-    DeleteCustomLogSourceResponseTypeDef,
-    DeleteDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeAutoEnableResponseTypeDef,
-    GetDatalakeExceptionsExpiryResponseTypeDef,
-    ListLogSourcesResponseTypeDef,
-    UpdateSubscriptionNotificationConfigurationResponseTypeDef,
+    LogSourceResourceTypeDef,
+    DataLakeConfigurationTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
+    DataLakeResourceTypeDef,
+    CreateSubscriberNotificationRequestRequestTypeDef,
+    UpdateSubscriberNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
+    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
+    ListLogSourcesRequestRequestTypeDef,
+    LogSourceTypeDef,
     SubscriberResourceTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
-    FailuresResponseTypeDef,
-    GetDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef,
-    ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef,
-    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
-    ListSubscribersRequestListSubscribersPaginateTypeDef,
-    LakeConfigurationRequestTypeDef,
-    LakeConfigurationResponseTypeDef,
-    GetDatalakeStatusResponseTypeDef,
+    CreateDataLakeRequestRequestTypeDef,
+    UpdateDataLakeRequestRequestTypeDef,
+    CreateDataLakeResponseTypeDef,
+    ListDataLakesResponseTypeDef,
+    UpdateDataLakeResponseTypeDef,
+    ListLogSourcesResponseTypeDef,
+    CreateSubscriberResponseTypeDef,
     GetSubscriberResponseTypeDef,
     ListSubscribersResponseTypeDef,
     UpdateSubscriberResponseTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
-    CreateDatalakeRequestRequestTypeDef,
-    UpdateDatalakeRequestRequestTypeDef,
-    GetDatalakeResponseTypeDef,
 )
 
 
-def get_structure() -> LogsStatusTypeDef:
+def get_structure() -> AwsIdentityTypeDef:
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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/setup.py` & `types-aiobotocore-securitylake-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-securitylake.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-securitylake",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_securitylake"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SecurityLake 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SecurityLake 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/"
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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__init__.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__init__.pyi`

 * *Files 19% similar despite different names*

```diff
@@ -3,45 +3,44 @@
 
 Usage::
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_securitylake import (
         Client,
-        GetDatalakeStatusPaginator,
-        ListDatalakeExceptionsPaginator,
+        GetDataLakeSourcesPaginator,
+        ListDataLakeExceptionsPaginator,
         ListLogSourcesPaginator,
         ListSubscribersPaginator,
         SecurityLakeClient,
     )
 
     session = get_session()
     async with session.create_client("securitylake") as client:
         client: SecurityLakeClient
         ...
 
 
-    get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator("get_datalake_status")
-    list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator("list_datalake_exceptions")
+    get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator("get_data_lake_sources")
+    list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator("list_data_lake_exceptions")
     list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
     list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
     ```
 """
 from .client import SecurityLakeClient
 from .paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 
 Client = SecurityLakeClient
 
-
 __all__ = (
     "Client",
-    "GetDatalakeStatusPaginator",
-    "ListDatalakeExceptionsPaginator",
+    "GetDataLakeSourcesPaginator",
+    "ListDataLakeExceptionsPaginator",
     "ListLogSourcesPaginator",
     "ListSubscribersPaginator",
     "SecurityLakeClient",
 )
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__init__.pyi` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__init__.py`

 * *Files 14% similar despite different names*

```diff
@@ -3,44 +3,45 @@
 
 Usage::
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_securitylake import (
         Client,
-        GetDatalakeStatusPaginator,
-        ListDatalakeExceptionsPaginator,
+        GetDataLakeSourcesPaginator,
+        ListDataLakeExceptionsPaginator,
         ListLogSourcesPaginator,
         ListSubscribersPaginator,
         SecurityLakeClient,
     )
 
     session = get_session()
     async with session.create_client("securitylake") as client:
         client: SecurityLakeClient
         ...
 
 
-    get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator("get_datalake_status")
-    list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator("list_datalake_exceptions")
+    get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator("get_data_lake_sources")
+    list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator("list_data_lake_exceptions")
     list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
     list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
     ```
 """
 from .client import SecurityLakeClient
 from .paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 
 Client = SecurityLakeClient
 
+
 __all__ = (
     "Client",
-    "GetDatalakeStatusPaginator",
-    "ListDatalakeExceptionsPaginator",
+    "GetDataLakeSourcesPaginator",
+    "ListDataLakeExceptionsPaginator",
     "ListLogSourcesPaginator",
     "ListSubscribersPaginator",
     "SecurityLakeClient",
 )
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/__main__.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SecurityLake 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SecurityLake 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake\nOther"
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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/client.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/client.py`

 * *Files 12% similar despite different names*

```diff
@@ -16,50 +16,46 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import (
-    AccessTypeType,
-    DimensionType,
-    HttpsMethodType,
-    OcsfEventClassType,
-    RegionType,
-    SubscriptionProtocolTypeType,
-)
+from .literals import AccessTypeType
 from .paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 from .type_defs import (
-    AutoEnableNewRegionConfigurationTypeDef,
+    AwsIdentityTypeDef,
+    AwsLogSourceConfigurationTypeDef,
     CreateAwsLogSourceResponseTypeDef,
     CreateCustomLogSourceResponseTypeDef,
+    CreateDataLakeResponseTypeDef,
+    CreateSubscriberNotificationResponseTypeDef,
     CreateSubscriberResponseTypeDef,
-    CreateSubscriptionNotificationConfigurationResponseTypeDef,
+    CustomLogSourceConfigurationTypeDef,
+    DataLakeAutoEnableNewAccountConfigurationTypeDef,
+    DataLakeConfigurationTypeDef,
     DeleteAwsLogSourceResponseTypeDef,
-    DeleteCustomLogSourceResponseTypeDef,
-    DeleteDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeAutoEnableResponseTypeDef,
-    GetDatalakeExceptionsExpiryResponseTypeDef,
-    GetDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeResponseTypeDef,
-    GetDatalakeStatusResponseTypeDef,
+    GetDataLakeExceptionSubscriptionResponseTypeDef,
+    GetDataLakeOrganizationConfigurationResponseTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
     GetSubscriberResponseTypeDef,
-    LakeConfigurationRequestTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
+    ListDataLakesResponseTypeDef,
     ListLogSourcesResponseTypeDef,
     ListSubscribersResponseTypeDef,
-    SourceTypeTypeDef,
+    LogSourceResourceTypeDef,
+    NotificationConfigurationTypeDef,
+    UpdateDataLakeResponseTypeDef,
+    UpdateSubscriberNotificationResponseTypeDef,
     UpdateSubscriberResponseTypeDef,
-    UpdateSubscriptionNotificationConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -73,29 +69,20 @@
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
-    AccountNotFoundException: Type[BotocoreClientError]
-    BucketNotFoundException: Type[BotocoreClientError]
+    BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
-    ConcurrentModificationException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
-    ConflictSourceNamesException: Type[BotocoreClientError]
-    ConflictSubscriptionException: Type[BotocoreClientError]
-    EventBridgeException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
-    InvalidInputException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
-    S3Exception: Type[BotocoreClientError]
-    ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
-    ValidationException: Type[BotocoreClientError]
 
 
 class SecurityLakeClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/)
     """
@@ -124,213 +111,185 @@
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#close)
         """
 
     async def create_aws_log_source(
-        self,
-        *,
-        inputOrder: Sequence[DimensionType],
-        enableAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        enableSingleDimension: Sequence[str] = ...,
-        enableTwoDimensions: Mapping[str, Sequence[str]] = ...
+        self, *, sources: Sequence[AwsLogSourceConfigurationTypeDef]
     ) -> CreateAwsLogSourceResponseTypeDef:
         """
         Adds a natively supported Amazon Web Service as an Amazon Security Lake source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_aws_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_aws_log_source)
         """
 
     async def create_custom_log_source(
         self,
         *,
-        customSourceName: str,
-        eventClass: OcsfEventClassType,
-        glueInvocationRoleArn: str,
-        logProviderAccountId: str
+        sourceName: str,
+        configuration: CustomLogSourceConfigurationTypeDef = ...,
+        eventClasses: Sequence[str] = ...,
+        sourceVersion: str = ...
     ) -> CreateCustomLogSourceResponseTypeDef:
         """
         Adds a third-party custom source in Amazon Security Lake, from the Amazon Web
         Services Region where you want to create a custom source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_custom_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_custom_log_source)
         """
 
-    async def create_datalake(
+    async def create_data_lake(
         self,
         *,
-        configurations: Mapping[RegionType, LakeConfigurationRequestTypeDef] = ...,
-        enableAll: bool = ...,
-        metaStoreManagerRoleArn: str = ...,
-        regions: Sequence[RegionType] = ...
-    ) -> Dict[str, Any]:
+        configurations: Sequence[DataLakeConfigurationTypeDef],
+        metaStoreManagerRoleArn: str
+    ) -> CreateDataLakeResponseTypeDef:
         """
         Initializes an Amazon Security Lake instance with the provided (or default)
         configuration.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake)
         """
 
-    async def create_datalake_auto_enable(
-        self, *, configurationForNewAccounts: Sequence[AutoEnableNewRegionConfigurationTypeDef]
+    async def create_data_lake_exception_subscription(
+        self,
+        *,
+        notificationEndpoint: str,
+        subscriptionProtocol: str,
+        exceptionTimeToLive: int = ...
     ) -> Dict[str, Any]:
         """
-        Automatically enables Amazon Security Lake for new member accounts in your
-        organization.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_auto_enable)
-        """
-
-    async def create_datalake_delegated_admin(self, *, account: str) -> Dict[str, Any]:
-        """
-        Designates the Amazon Security Lake delegated administrator account for the
-        organization.
+        Creates the specified notification subscription in Amazon Security Lake for the
+        organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_delegated_admin)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_delegated_admin)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake_exception_subscription)
         """
 
-    async def create_datalake_exceptions_subscription(
-        self, *, notificationEndpoint: str, subscriptionProtocol: SubscriptionProtocolTypeType
+    async def create_data_lake_organization_configuration(
+        self, *, autoEnableNewAccount: Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef]
     ) -> Dict[str, Any]:
         """
-        Creates the specified notification subscription in Amazon Security Lake for the
-        organization you specify.
+        Automatically enables Amazon Security Lake for new member accounts in your
+        organization.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake_organization_configuration)
         """
 
     async def create_subscriber(
         self,
         *,
-        accountId: str,
-        externalId: str,
-        sourceTypes: Sequence[SourceTypeTypeDef],
+        sources: Sequence[LogSourceResourceTypeDef],
+        subscriberIdentity: AwsIdentityTypeDef,
         subscriberName: str,
         accessTypes: Sequence[AccessTypeType] = ...,
         subscriberDescription: str = ...
     ) -> CreateSubscriberResponseTypeDef:
         """
         Creates a subscription permission for accounts that are already enabled in
         Amazon Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscriber)
         """
 
-    async def create_subscription_notification_configuration(
-        self,
-        *,
-        subscriptionId: str,
-        createSqs: bool = ...,
-        httpsApiKeyName: str = ...,
-        httpsApiKeyValue: str = ...,
-        httpsMethod: HttpsMethodType = ...,
-        roleArn: str = ...,
-        subscriptionEndpoint: str = ...
-    ) -> CreateSubscriptionNotificationConfigurationResponseTypeDef:
+    async def create_subscriber_notification(
+        self, *, configuration: NotificationConfigurationTypeDef, subscriberId: str
+    ) -> CreateSubscriberNotificationResponseTypeDef:
         """
         Notifies the subscriber when new data is written to the data lake for the
         sources that the subscriber consumes in Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscriber_notification)
         """
 
     async def delete_aws_log_source(
-        self,
-        *,
-        inputOrder: Sequence[DimensionType],
-        disableAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        disableSingleDimension: Sequence[str] = ...,
-        disableTwoDimensions: Mapping[str, Sequence[str]] = ...
+        self, *, sources: Sequence[AwsLogSourceConfigurationTypeDef]
     ) -> DeleteAwsLogSourceResponseTypeDef:
         """
         Removes a natively supported Amazon Web Service as an Amazon Security Lake
         source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_aws_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_aws_log_source)
         """
 
     async def delete_custom_log_source(
-        self, *, customSourceName: str
-    ) -> DeleteCustomLogSourceResponseTypeDef:
+        self, *, sourceName: str, sourceVersion: str = ...
+    ) -> Dict[str, Any]:
         """
-        Removes a custom log source from Amazon Security Lake.
+        Removes a custom log source from Amazon Security Lake, to stop sending data from
+        the custom source to Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_custom_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_custom_log_source)
         """
 
-    async def delete_datalake(self) -> Dict[str, Any]:
-        """
-        When you delete Amazon Security Lake from your account, Security Lake is
-        disabled in all Amazon Web Services Regions.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake)
-        """
-
-    async def delete_datalake_auto_enable(
-        self,
-        *,
-        removeFromConfigurationForNewAccounts: Sequence[AutoEnableNewRegionConfigurationTypeDef]
-    ) -> Dict[str, Any]:
+    async def delete_data_lake(self, *, regions: Sequence[str]) -> Dict[str, Any]:
         """
-        Automatically deletes Amazon Security Lake to stop collecting security data.
+        When you disable Amazon Security Lake from your account, Security Lake is
+        disabled in all Amazon Web Services Regions and it stops collecting data from
+        your sources.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_auto_enable)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake)
         """
 
-    async def delete_datalake_delegated_admin(self, *, account: str) -> Dict[str, Any]:
+    async def delete_data_lake_exception_subscription(self) -> Dict[str, Any]:
         """
-        Deletes the Amazon Security Lake delegated administrator account for the
-        organization.
+        Deletes the specified notification subscription in Amazon Security Lake for the
+        organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_delegated_admin)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_delegated_admin)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake_exception_subscription)
         """
 
-    async def delete_datalake_exceptions_subscription(
-        self,
-    ) -> DeleteDatalakeExceptionsSubscriptionResponseTypeDef:
+    async def delete_data_lake_organization_configuration(
+        self, *, autoEnableNewAccount: Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef]
+    ) -> Dict[str, Any]:
         """
-        Deletes the specified notification subscription in Amazon Security Lake for the
-        organization you specify.
+        Removes automatic the enablement of configuration settings for new member
+        accounts (but retains the settings for the delegated administrator) from Amazon
+        Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake_organization_configuration)
         """
 
-    async def delete_subscriber(self, *, id: str) -> Dict[str, Any]:
+    async def delete_subscriber(self, *, subscriberId: str) -> Dict[str, Any]:
         """
-        Deletes the subscription permission for accounts that are already enabled in
-        Amazon Security Lake.
+        Deletes the subscription permission and all notification settings for accounts
+        that are already enabled in Amazon Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscriber)
         """
 
-    async def delete_subscription_notification_configuration(
-        self, *, subscriptionId: str
-    ) -> Dict[str, Any]:
+    async def delete_subscriber_notification(self, *, subscriberId: str) -> Dict[str, Any]:
         """
         Deletes the specified notification subscription in Amazon Security Lake for the
         organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscriber_notification)
+        """
+
+    async def deregister_data_lake_delegated_administrator(self) -> Dict[str, Any]:
+        """
+        Deletes the Amazon Security Lake delegated administrator account for the
+        organization.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.deregister_data_lake_delegated_administrator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#deregister_data_lake_delegated_administrator)
         """
 
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
@@ -339,93 +298,87 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#generate_presigned_url)
         """
 
-    async def get_datalake(self) -> GetDatalakeResponseTypeDef:
+    async def get_data_lake_exception_subscription(
+        self,
+    ) -> GetDataLakeExceptionSubscriptionResponseTypeDef:
         """
-        Retrieves the Amazon Security Lake configuration object for the specified Amazon
-        Web Services account ID.
+        Retrieves the details of exception notifications for the account in Amazon
+        Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_exception_subscription)
         """
 
-    async def get_datalake_auto_enable(self) -> GetDatalakeAutoEnableResponseTypeDef:
+    async def get_data_lake_organization_configuration(
+        self,
+    ) -> GetDataLakeOrganizationConfigurationResponseTypeDef:
         """
         Retrieves the configuration that will be automatically set up for accounts added
         to the organization after the organization has onboarded to Amazon Security
         Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_auto_enable)
-        """
-
-    async def get_datalake_exceptions_expiry(self) -> GetDatalakeExceptionsExpiryResponseTypeDef:
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_organization_configuration)
         """
-        Retrieves the expiration period and time-to-live (TTL) for which the exception
-        message will remain.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_exceptions_expiry)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_exceptions_expiry)
-        """
-
-    async def get_datalake_exceptions_subscription(
-        self,
-    ) -> GetDatalakeExceptionsSubscriptionResponseTypeDef:
-        """
-        Retrieves the details of exception notifications for the account in Amazon
-        Security Lake.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_exceptions_subscription)
-        """
-
-    async def get_datalake_status(
-        self, *, accountSet: Sequence[str] = ..., maxAccountResults: int = ..., nextToken: str = ...
-    ) -> GetDatalakeStatusResponseTypeDef:
+    async def get_data_lake_sources(
+        self, *, accounts: Sequence[str] = ..., maxResults: int = ..., nextToken: str = ...
+    ) -> GetDataLakeSourcesResponseTypeDef:
         """
         Retrieves a snapshot of the current Region, including whether Amazon Security
         Lake is enabled for those accounts and which sources Security Lake is collecting
         data from.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_status)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_status)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_sources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_sources)
         """
 
-    async def get_subscriber(self, *, id: str) -> GetSubscriberResponseTypeDef:
+    async def get_subscriber(self, *, subscriberId: str) -> GetSubscriberResponseTypeDef:
         """
         Retrieves the subscription information for the specified subscription ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_subscriber)
         """
 
-    async def list_datalake_exceptions(
-        self, *, maxFailures: int = ..., nextToken: str = ..., regionSet: Sequence[RegionType] = ...
-    ) -> ListDatalakeExceptionsResponseTypeDef:
+    async def list_data_lake_exceptions(
+        self, *, maxResults: int = ..., nextToken: str = ..., regions: Sequence[str] = ...
+    ) -> ListDataLakeExceptionsResponseTypeDef:
         """
         Lists the Amazon Security Lake exceptions that you can use to find the source of
         problems and fix them.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_datalake_exceptions)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_datalake_exceptions)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_data_lake_exceptions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_data_lake_exceptions)
+        """
+
+    async def list_data_lakes(
+        self, *, regions: Sequence[str] = ...
+    ) -> ListDataLakesResponseTypeDef:
+        """
+        Retrieves the Amazon Security Lake configuration object for the specified Amazon
+        Web Services account ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_data_lakes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_data_lakes)
         """
 
     async def list_log_sources(
         self,
         *,
-        inputOrder: Sequence[DimensionType] = ...,
-        listAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        listSingleDimension: Sequence[str] = ...,
-        listTwoDimensions: Mapping[str, Sequence[str]] = ...,
+        accounts: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        regions: Sequence[str] = ...,
+        sources: Sequence[LogSourceResourceTypeDef] = ...
     ) -> ListLogSourcesResponseTypeDef:
         """
         Retrieves the log sources in the current Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_log_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_log_sources)
         """
@@ -436,94 +389,88 @@
         """
         List all subscribers for the specific Amazon Security Lake account ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_subscribers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_subscribers)
         """
 
-    async def update_datalake(
-        self, *, configurations: Mapping[RegionType, LakeConfigurationRequestTypeDef]
-    ) -> Dict[str, Any]:
+    async def register_data_lake_delegated_administrator(self, *, accountId: str) -> Dict[str, Any]:
         """
-        Specifies where to store your security data and for how long.
+        Designates the Amazon Security Lake delegated administrator account for the
+        organization.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.register_data_lake_delegated_administrator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#register_data_lake_delegated_administrator)
         """
 
-    async def update_datalake_exceptions_expiry(
-        self, *, exceptionMessageExpiry: int
-    ) -> Dict[str, Any]:
+    async def update_data_lake(
+        self, *, configurations: Sequence[DataLakeConfigurationTypeDef]
+    ) -> UpdateDataLakeResponseTypeDef:
         """
-        Update the expiration period for the exception message to your preferred time,
-        and control the time-to-live (TTL) for the exception message to remain.
+        Specifies where to store your security data and for how long.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake_exceptions_expiry)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake_exceptions_expiry)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_data_lake)
         """
 
-    async def update_datalake_exceptions_subscription(
-        self, *, notificationEndpoint: str, subscriptionProtocol: SubscriptionProtocolTypeType
+    async def update_data_lake_exception_subscription(
+        self,
+        *,
+        notificationEndpoint: str,
+        subscriptionProtocol: str,
+        exceptionTimeToLive: int = ...
     ) -> Dict[str, Any]:
         """
         Updates the specified notification subscription in Amazon Security Lake for the
         organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_data_lake_exception_subscription)
         """
 
     async def update_subscriber(
         self,
         *,
-        id: str,
-        sourceTypes: Sequence[SourceTypeTypeDef],
-        externalId: str = ...,
+        subscriberId: str,
+        sources: Sequence[LogSourceResourceTypeDef] = ...,
         subscriberDescription: str = ...,
+        subscriberIdentity: AwsIdentityTypeDef = ...,
         subscriberName: str = ...
     ) -> UpdateSubscriberResponseTypeDef:
         """
         Updates an existing subscription for the given Amazon Security Lake account ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscriber)
         """
 
-    async def update_subscription_notification_configuration(
-        self,
-        *,
-        subscriptionId: str,
-        createSqs: bool = ...,
-        httpsApiKeyName: str = ...,
-        httpsApiKeyValue: str = ...,
-        httpsMethod: HttpsMethodType = ...,
-        roleArn: str = ...,
-        subscriptionEndpoint: str = ...
-    ) -> UpdateSubscriptionNotificationConfigurationResponseTypeDef:
+    async def update_subscriber_notification(
+        self, *, configuration: NotificationConfigurationTypeDef, subscriberId: str
+    ) -> UpdateSubscriberNotificationResponseTypeDef:
         """
-        Creates a new subscription notification or adds the existing subscription
-        notification setting for the specified subscription ID.
+        Updates an existing notification method for the subscription (SQS or HTTPs
+        endpoint) or switches the notification subscription endpoint for a subscriber.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscriber_notification)
         """
 
     @overload
     def get_paginator(
-        self, operation_name: Literal["get_datalake_status"]
-    ) -> GetDatalakeStatusPaginator:
+        self, operation_name: Literal["get_data_lake_sources"]
+    ) -> GetDataLakeSourcesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
-        self, operation_name: Literal["list_datalake_exceptions"]
-    ) -> ListDatalakeExceptionsPaginator:
+        self, operation_name: Literal["list_data_lake_exceptions"]
+    ) -> ListDataLakeExceptionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_paginator)
         """
 
     @overload
     def get_paginator(self, operation_name: Literal["list_log_sources"]) -> ListLogSourcesPaginator:
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/client.pyi` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/client.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -16,50 +16,46 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import (
-    AccessTypeType,
-    DimensionType,
-    HttpsMethodType,
-    OcsfEventClassType,
-    RegionType,
-    SubscriptionProtocolTypeType,
-)
+from .literals import AccessTypeType
 from .paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 from .type_defs import (
-    AutoEnableNewRegionConfigurationTypeDef,
+    AwsIdentityTypeDef,
+    AwsLogSourceConfigurationTypeDef,
     CreateAwsLogSourceResponseTypeDef,
     CreateCustomLogSourceResponseTypeDef,
+    CreateDataLakeResponseTypeDef,
+    CreateSubscriberNotificationResponseTypeDef,
     CreateSubscriberResponseTypeDef,
-    CreateSubscriptionNotificationConfigurationResponseTypeDef,
+    CustomLogSourceConfigurationTypeDef,
+    DataLakeAutoEnableNewAccountConfigurationTypeDef,
+    DataLakeConfigurationTypeDef,
     DeleteAwsLogSourceResponseTypeDef,
-    DeleteCustomLogSourceResponseTypeDef,
-    DeleteDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeAutoEnableResponseTypeDef,
-    GetDatalakeExceptionsExpiryResponseTypeDef,
-    GetDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeResponseTypeDef,
-    GetDatalakeStatusResponseTypeDef,
+    GetDataLakeExceptionSubscriptionResponseTypeDef,
+    GetDataLakeOrganizationConfigurationResponseTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
     GetSubscriberResponseTypeDef,
-    LakeConfigurationRequestTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
+    ListDataLakesResponseTypeDef,
     ListLogSourcesResponseTypeDef,
     ListSubscribersResponseTypeDef,
-    SourceTypeTypeDef,
+    LogSourceResourceTypeDef,
+    NotificationConfigurationTypeDef,
+    UpdateDataLakeResponseTypeDef,
+    UpdateSubscriberNotificationResponseTypeDef,
     UpdateSubscriberResponseTypeDef,
-    UpdateSubscriptionNotificationConfigurationResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -70,29 +66,20 @@
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
-    AccountNotFoundException: Type[BotocoreClientError]
-    BucketNotFoundException: Type[BotocoreClientError]
+    BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
-    ConcurrentModificationException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
-    ConflictSourceNamesException: Type[BotocoreClientError]
-    ConflictSubscriptionException: Type[BotocoreClientError]
-    EventBridgeException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
-    InvalidInputException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
-    S3Exception: Type[BotocoreClientError]
-    ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
-    ValidationException: Type[BotocoreClientError]
 
 class SecurityLakeClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/)
     """
 
@@ -117,284 +104,252 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#close)
         """
     async def create_aws_log_source(
-        self,
-        *,
-        inputOrder: Sequence[DimensionType],
-        enableAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        enableSingleDimension: Sequence[str] = ...,
-        enableTwoDimensions: Mapping[str, Sequence[str]] = ...
+        self, *, sources: Sequence[AwsLogSourceConfigurationTypeDef]
     ) -> CreateAwsLogSourceResponseTypeDef:
         """
         Adds a natively supported Amazon Web Service as an Amazon Security Lake source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_aws_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_aws_log_source)
         """
     async def create_custom_log_source(
         self,
         *,
-        customSourceName: str,
-        eventClass: OcsfEventClassType,
-        glueInvocationRoleArn: str,
-        logProviderAccountId: str
+        sourceName: str,
+        configuration: CustomLogSourceConfigurationTypeDef = ...,
+        eventClasses: Sequence[str] = ...,
+        sourceVersion: str = ...
     ) -> CreateCustomLogSourceResponseTypeDef:
         """
         Adds a third-party custom source in Amazon Security Lake, from the Amazon Web
         Services Region where you want to create a custom source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_custom_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_custom_log_source)
         """
-    async def create_datalake(
+    async def create_data_lake(
         self,
         *,
-        configurations: Mapping[RegionType, LakeConfigurationRequestTypeDef] = ...,
-        enableAll: bool = ...,
-        metaStoreManagerRoleArn: str = ...,
-        regions: Sequence[RegionType] = ...
-    ) -> Dict[str, Any]:
+        configurations: Sequence[DataLakeConfigurationTypeDef],
+        metaStoreManagerRoleArn: str
+    ) -> CreateDataLakeResponseTypeDef:
         """
         Initializes an Amazon Security Lake instance with the provided (or default)
         configuration.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake)
         """
-    async def create_datalake_auto_enable(
-        self, *, configurationForNewAccounts: Sequence[AutoEnableNewRegionConfigurationTypeDef]
+    async def create_data_lake_exception_subscription(
+        self,
+        *,
+        notificationEndpoint: str,
+        subscriptionProtocol: str,
+        exceptionTimeToLive: int = ...
     ) -> Dict[str, Any]:
         """
-        Automatically enables Amazon Security Lake for new member accounts in your
-        organization.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_auto_enable)
-        """
-    async def create_datalake_delegated_admin(self, *, account: str) -> Dict[str, Any]:
-        """
-        Designates the Amazon Security Lake delegated administrator account for the
-        organization.
+        Creates the specified notification subscription in Amazon Security Lake for the
+        organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_delegated_admin)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_delegated_admin)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake_exception_subscription)
         """
-    async def create_datalake_exceptions_subscription(
-        self, *, notificationEndpoint: str, subscriptionProtocol: SubscriptionProtocolTypeType
+    async def create_data_lake_organization_configuration(
+        self, *, autoEnableNewAccount: Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef]
     ) -> Dict[str, Any]:
         """
-        Creates the specified notification subscription in Amazon Security Lake for the
-        organization you specify.
+        Automatically enables Amazon Security Lake for new member accounts in your
+        organization.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_data_lake_organization_configuration)
         """
     async def create_subscriber(
         self,
         *,
-        accountId: str,
-        externalId: str,
-        sourceTypes: Sequence[SourceTypeTypeDef],
+        sources: Sequence[LogSourceResourceTypeDef],
+        subscriberIdentity: AwsIdentityTypeDef,
         subscriberName: str,
         accessTypes: Sequence[AccessTypeType] = ...,
         subscriberDescription: str = ...
     ) -> CreateSubscriberResponseTypeDef:
         """
         Creates a subscription permission for accounts that are already enabled in
         Amazon Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscriber)
         """
-    async def create_subscription_notification_configuration(
-        self,
-        *,
-        subscriptionId: str,
-        createSqs: bool = ...,
-        httpsApiKeyName: str = ...,
-        httpsApiKeyValue: str = ...,
-        httpsMethod: HttpsMethodType = ...,
-        roleArn: str = ...,
-        subscriptionEndpoint: str = ...
-    ) -> CreateSubscriptionNotificationConfigurationResponseTypeDef:
+    async def create_subscriber_notification(
+        self, *, configuration: NotificationConfigurationTypeDef, subscriberId: str
+    ) -> CreateSubscriberNotificationResponseTypeDef:
         """
         Notifies the subscriber when new data is written to the data lake for the
         sources that the subscriber consumes in Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.create_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#create_subscriber_notification)
         """
     async def delete_aws_log_source(
-        self,
-        *,
-        inputOrder: Sequence[DimensionType],
-        disableAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        disableSingleDimension: Sequence[str] = ...,
-        disableTwoDimensions: Mapping[str, Sequence[str]] = ...
+        self, *, sources: Sequence[AwsLogSourceConfigurationTypeDef]
     ) -> DeleteAwsLogSourceResponseTypeDef:
         """
         Removes a natively supported Amazon Web Service as an Amazon Security Lake
         source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_aws_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_aws_log_source)
         """
     async def delete_custom_log_source(
-        self, *, customSourceName: str
-    ) -> DeleteCustomLogSourceResponseTypeDef:
+        self, *, sourceName: str, sourceVersion: str = ...
+    ) -> Dict[str, Any]:
         """
-        Removes a custom log source from Amazon Security Lake.
+        Removes a custom log source from Amazon Security Lake, to stop sending data from
+        the custom source to Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_custom_log_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_custom_log_source)
         """
-    async def delete_datalake(self) -> Dict[str, Any]:
+    async def delete_data_lake(self, *, regions: Sequence[str]) -> Dict[str, Any]:
         """
-        When you delete Amazon Security Lake from your account, Security Lake is
-        disabled in all Amazon Web Services Regions.
+        When you disable Amazon Security Lake from your account, Security Lake is
+        disabled in all Amazon Web Services Regions and it stops collecting data from
+        your sources.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake)
         """
-    async def delete_datalake_auto_enable(
-        self,
-        *,
-        removeFromConfigurationForNewAccounts: Sequence[AutoEnableNewRegionConfigurationTypeDef]
-    ) -> Dict[str, Any]:
-        """
-        Automatically deletes Amazon Security Lake to stop collecting security data.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_auto_enable)
+    async def delete_data_lake_exception_subscription(self) -> Dict[str, Any]:
         """
-    async def delete_datalake_delegated_admin(self, *, account: str) -> Dict[str, Any]:
-        """
-        Deletes the Amazon Security Lake delegated administrator account for the
-        organization.
+        Deletes the specified notification subscription in Amazon Security Lake for the
+        organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_delegated_admin)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_delegated_admin)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake_exception_subscription)
         """
-    async def delete_datalake_exceptions_subscription(
-        self,
-    ) -> DeleteDatalakeExceptionsSubscriptionResponseTypeDef:
+    async def delete_data_lake_organization_configuration(
+        self, *, autoEnableNewAccount: Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef]
+    ) -> Dict[str, Any]:
         """
-        Deletes the specified notification subscription in Amazon Security Lake for the
-        organization you specify.
+        Removes automatic the enablement of configuration settings for new member
+        accounts (but retains the settings for the delegated administrator) from Amazon
+        Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_data_lake_organization_configuration)
         """
-    async def delete_subscriber(self, *, id: str) -> Dict[str, Any]:
+    async def delete_subscriber(self, *, subscriberId: str) -> Dict[str, Any]:
         """
-        Deletes the subscription permission for accounts that are already enabled in
-        Amazon Security Lake.
+        Deletes the subscription permission and all notification settings for accounts
+        that are already enabled in Amazon Security Lake.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscriber)
         """
-    async def delete_subscription_notification_configuration(
-        self, *, subscriptionId: str
-    ) -> Dict[str, Any]:
+    async def delete_subscriber_notification(self, *, subscriberId: str) -> Dict[str, Any]:
         """
         Deletes the specified notification subscription in Amazon Security Lake for the
         organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.delete_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#delete_subscriber_notification)
+        """
+    async def deregister_data_lake_delegated_administrator(self) -> Dict[str, Any]:
+        """
+        Deletes the Amazon Security Lake delegated administrator account for the
+        organization.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.deregister_data_lake_delegated_administrator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#deregister_data_lake_delegated_administrator)
         """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#generate_presigned_url)
         """
-    async def get_datalake(self) -> GetDatalakeResponseTypeDef:
+    async def get_data_lake_exception_subscription(
+        self,
+    ) -> GetDataLakeExceptionSubscriptionResponseTypeDef:
         """
-        Retrieves the Amazon Security Lake configuration object for the specified Amazon
-        Web Services account ID.
+        Retrieves the details of exception notifications for the account in Amazon
+        Security Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_exception_subscription)
         """
-    async def get_datalake_auto_enable(self) -> GetDatalakeAutoEnableResponseTypeDef:
+    async def get_data_lake_organization_configuration(
+        self,
+    ) -> GetDataLakeOrganizationConfigurationResponseTypeDef:
         """
         Retrieves the configuration that will be automatically set up for accounts added
         to the organization after the organization has onboarded to Amazon Security
         Lake.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_auto_enable)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_auto_enable)
-        """
-    async def get_datalake_exceptions_expiry(self) -> GetDatalakeExceptionsExpiryResponseTypeDef:
-        """
-        Retrieves the expiration period and time-to-live (TTL) for which the exception
-        message will remain.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_exceptions_expiry)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_exceptions_expiry)
-        """
-    async def get_datalake_exceptions_subscription(
-        self,
-    ) -> GetDatalakeExceptionsSubscriptionResponseTypeDef:
-        """
-        Retrieves the details of exception notifications for the account in Amazon
-        Security Lake.
-
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_organization_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_organization_configuration)
         """
-    async def get_datalake_status(
-        self, *, accountSet: Sequence[str] = ..., maxAccountResults: int = ..., nextToken: str = ...
-    ) -> GetDatalakeStatusResponseTypeDef:
+    async def get_data_lake_sources(
+        self, *, accounts: Sequence[str] = ..., maxResults: int = ..., nextToken: str = ...
+    ) -> GetDataLakeSourcesResponseTypeDef:
         """
         Retrieves a snapshot of the current Region, including whether Amazon Security
         Lake is enabled for those accounts and which sources Security Lake is collecting
         data from.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_datalake_status)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_datalake_status)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_data_lake_sources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_data_lake_sources)
         """
-    async def get_subscriber(self, *, id: str) -> GetSubscriberResponseTypeDef:
+    async def get_subscriber(self, *, subscriberId: str) -> GetSubscriberResponseTypeDef:
         """
         Retrieves the subscription information for the specified subscription ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_subscriber)
         """
-    async def list_datalake_exceptions(
-        self, *, maxFailures: int = ..., nextToken: str = ..., regionSet: Sequence[RegionType] = ...
-    ) -> ListDatalakeExceptionsResponseTypeDef:
+    async def list_data_lake_exceptions(
+        self, *, maxResults: int = ..., nextToken: str = ..., regions: Sequence[str] = ...
+    ) -> ListDataLakeExceptionsResponseTypeDef:
         """
         Lists the Amazon Security Lake exceptions that you can use to find the source of
         problems and fix them.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_datalake_exceptions)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_datalake_exceptions)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_data_lake_exceptions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_data_lake_exceptions)
+        """
+    async def list_data_lakes(
+        self, *, regions: Sequence[str] = ...
+    ) -> ListDataLakesResponseTypeDef:
+        """
+        Retrieves the Amazon Security Lake configuration object for the specified Amazon
+        Web Services account ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_data_lakes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_data_lakes)
         """
     async def list_log_sources(
         self,
         *,
-        inputOrder: Sequence[DimensionType] = ...,
-        listAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        listSingleDimension: Sequence[str] = ...,
-        listTwoDimensions: Mapping[str, Sequence[str]] = ...,
+        accounts: Sequence[str] = ...,
         maxResults: int = ...,
-        nextToken: str = ...
+        nextToken: str = ...,
+        regions: Sequence[str] = ...,
+        sources: Sequence[LogSourceResourceTypeDef] = ...
     ) -> ListLogSourcesResponseTypeDef:
         """
         Retrieves the log sources in the current Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_log_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_log_sources)
         """
@@ -403,88 +358,82 @@
     ) -> ListSubscribersResponseTypeDef:
         """
         List all subscribers for the specific Amazon Security Lake account ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.list_subscribers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#list_subscribers)
         """
-    async def update_datalake(
-        self, *, configurations: Mapping[RegionType, LakeConfigurationRequestTypeDef]
-    ) -> Dict[str, Any]:
+    async def register_data_lake_delegated_administrator(self, *, accountId: str) -> Dict[str, Any]:
         """
-        Specifies where to store your security data and for how long.
+        Designates the Amazon Security Lake delegated administrator account for the
+        organization.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.register_data_lake_delegated_administrator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#register_data_lake_delegated_administrator)
         """
-    async def update_datalake_exceptions_expiry(
-        self, *, exceptionMessageExpiry: int
-    ) -> Dict[str, Any]:
+    async def update_data_lake(
+        self, *, configurations: Sequence[DataLakeConfigurationTypeDef]
+    ) -> UpdateDataLakeResponseTypeDef:
         """
-        Update the expiration period for the exception message to your preferred time,
-        and control the time-to-live (TTL) for the exception message to remain.
+        Specifies where to store your security data and for how long.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake_exceptions_expiry)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake_exceptions_expiry)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_data_lake)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_data_lake)
         """
-    async def update_datalake_exceptions_subscription(
-        self, *, notificationEndpoint: str, subscriptionProtocol: SubscriptionProtocolTypeType
+    async def update_data_lake_exception_subscription(
+        self,
+        *,
+        notificationEndpoint: str,
+        subscriptionProtocol: str,
+        exceptionTimeToLive: int = ...
     ) -> Dict[str, Any]:
         """
         Updates the specified notification subscription in Amazon Security Lake for the
         organization you specify.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_datalake_exceptions_subscription)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_datalake_exceptions_subscription)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_data_lake_exception_subscription)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_data_lake_exception_subscription)
         """
     async def update_subscriber(
         self,
         *,
-        id: str,
-        sourceTypes: Sequence[SourceTypeTypeDef],
-        externalId: str = ...,
+        subscriberId: str,
+        sources: Sequence[LogSourceResourceTypeDef] = ...,
         subscriberDescription: str = ...,
+        subscriberIdentity: AwsIdentityTypeDef = ...,
         subscriberName: str = ...
     ) -> UpdateSubscriberResponseTypeDef:
         """
         Updates an existing subscription for the given Amazon Security Lake account ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscriber)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscriber)
         """
-    async def update_subscription_notification_configuration(
-        self,
-        *,
-        subscriptionId: str,
-        createSqs: bool = ...,
-        httpsApiKeyName: str = ...,
-        httpsApiKeyValue: str = ...,
-        httpsMethod: HttpsMethodType = ...,
-        roleArn: str = ...,
-        subscriptionEndpoint: str = ...
-    ) -> UpdateSubscriptionNotificationConfigurationResponseTypeDef:
+    async def update_subscriber_notification(
+        self, *, configuration: NotificationConfigurationTypeDef, subscriberId: str
+    ) -> UpdateSubscriberNotificationResponseTypeDef:
         """
-        Creates a new subscription notification or adds the existing subscription
-        notification setting for the specified subscription ID.
+        Updates an existing notification method for the subscription (SQS or HTTPs
+        endpoint) or switches the notification subscription endpoint for a subscriber.
 
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscription_notification_configuration)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscription_notification_configuration)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.update_subscriber_notification)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#update_subscriber_notification)
         """
     @overload
     def get_paginator(
-        self, operation_name: Literal["get_datalake_status"]
-    ) -> GetDatalakeStatusPaginator:
+        self, operation_name: Literal["get_data_lake_sources"]
+    ) -> GetDataLakeSourcesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_paginator)
         """
     @overload
     def get_paginator(
-        self, operation_name: Literal["list_datalake_exceptions"]
-    ) -> ListDatalakeExceptionsPaginator:
+        self, operation_name: Literal["list_data_lake_exceptions"]
+    ) -> ListDataLakeExceptionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/client/#get_paginator)
         """
     @overload
     def get_paginator(self, operation_name: Literal["list_log_sources"]) -> ListLogSourcesPaginator:
         """
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/literals.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/literals.py`

 * *Files 18% similar despite different names*

```diff
@@ -17,105 +17,43 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AccessTypeType",
-    "AwsLogSourceTypeType",
-    "DimensionType",
-    "EndpointProtocolType",
-    "GetDatalakeStatusPaginatorName",
-    "HttpsMethodType",
-    "ListDatalakeExceptionsPaginatorName",
+    "AwsLogSourceNameType",
+    "DataLakeStatusType",
+    "GetDataLakeSourcesPaginatorName",
+    "HttpMethodType",
+    "ListDataLakeExceptionsPaginatorName",
     "ListLogSourcesPaginatorName",
     "ListSubscribersPaginatorName",
-    "OcsfEventClassType",
-    "RegionType",
-    "SourceStatusType",
-    "StorageClassType",
-    "SubscriptionProtocolTypeType",
-    "SubscriptionStatusType",
-    "settingsStatusType",
+    "SourceCollectionStatusType",
+    "SubscriberStatusType",
     "SecurityLakeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 AccessTypeType = Literal["LAKEFORMATION", "S3"]
-AwsLogSourceTypeType = Literal["CLOUD_TRAIL", "ROUTE53", "SH_FINDINGS", "VPC_FLOW"]
-DimensionType = Literal["MEMBER", "REGION", "SOURCE_TYPE"]
-EndpointProtocolType = Literal["HTTPS", "SQS"]
-GetDatalakeStatusPaginatorName = Literal["get_datalake_status"]
-HttpsMethodType = Literal["POST", "PUT"]
-ListDatalakeExceptionsPaginatorName = Literal["list_datalake_exceptions"]
+AwsLogSourceNameType = Literal[
+    "CLOUD_TRAIL_MGMT", "LAMBDA_EXECUTION", "ROUTE53", "S3_DATA", "SH_FINDINGS", "VPC_FLOW"
+]
+DataLakeStatusType = Literal["COMPLETED", "FAILED", "INITIALIZED", "PENDING"]
+GetDataLakeSourcesPaginatorName = Literal["get_data_lake_sources"]
+HttpMethodType = Literal["POST", "PUT"]
+ListDataLakeExceptionsPaginatorName = Literal["list_data_lake_exceptions"]
 ListLogSourcesPaginatorName = Literal["list_log_sources"]
 ListSubscribersPaginatorName = Literal["list_subscribers"]
-OcsfEventClassType = Literal[
-    "ACCESS_ACTIVITY",
-    "ACCOUNT_CHANGE",
-    "AUTHENTICATION",
-    "AUTHORIZATION",
-    "CLOUD_API",
-    "CLOUD_STORAGE",
-    "CONFIG_STATE",
-    "CONTAINER_LIFECYCLE",
-    "DATABASE_LIFECYCLE",
-    "DHCP_ACTIVITY",
-    "DNS_ACTIVITY",
-    "ENTITY_MANAGEMENT_AUDIT",
-    "FILE_ACTIVITY",
-    "FTP_ACTIVITY",
-    "HTTP_ACTIVITY",
-    "INVENTORY_INFO",
-    "KERNEL_ACTIVITY",
-    "KERNEL_EXTENSION",
-    "MEMORY_ACTIVITY",
-    "MODULE_ACTIVITY",
-    "NETWORK_ACTIVITY",
-    "PROCESS_ACTIVITY",
-    "RDP_ACTIVITY",
-    "REGISTRY_KEY_ACTIVITY",
-    "REGISTRY_VALUE_ACTIVITY",
-    "RESOURCE_ACTIVITY",
-    "RFB_ACTIVITY",
-    "SCHEDULED_JOB_ACTIVITY",
-    "SECURITY_FINDING",
-    "SMB_ACTIVITY",
-    "SMTP_ACTIVITY",
-    "SSH_ACTIVITY",
-    "VIRTUAL_MACHINE_ACTIVITY",
-]
-RegionType = Literal[
-    "ap-northeast-1",
-    "ap-southeast-2",
-    "eu-central-1",
-    "eu-west-1",
-    "us-east-1",
-    "us-east-2",
-    "us-west-2",
-]
-SourceStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING"]
-StorageClassType = Literal[
-    "DEEP_ARCHIVE",
-    "EXPIRE",
-    "GLACIER",
-    "GLACIER_IR",
-    "INTELLIGENT_TIERING",
-    "ONEZONE_IA",
-    "STANDARD_IA",
-]
-SubscriptionProtocolTypeType = Literal[
-    "APP", "EMAIL", "EMAIL_JSON", "FIREHOSE", "HTTP", "HTTPS", "LAMBDA", "SMS", "SQS"
-]
-SubscriptionStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING", "READY"]
-settingsStatusType = Literal["COMPLETED", "FAILED", "INITIALIZED", "PENDING"]
+SourceCollectionStatusType = Literal["COLLECTING", "MISCONFIGURED", "NOT_COLLECTING"]
+SubscriberStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING", "READY"]
 SecurityLakeServiceName = Literal["securitylake"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -171,14 +109,15 @@
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
@@ -257,14 +196,15 @@
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
@@ -275,14 +215,15 @@
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
@@ -318,14 +259,15 @@
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
@@ -344,16 +286,19 @@
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
@@ -437,15 +382,17 @@
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
@@ -464,18 +411,24 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
-    "get_datalake_status", "list_datalake_exceptions", "list_log_sources", "list_subscribers"
+    "get_data_lake_sources", "list_data_lake_exceptions", "list_log_sources", "list_subscribers"
 ]
 RegionName = Literal[
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
+    "ap-southeast-1",
     "ap-southeast-2",
     "eu-central-1",
     "eu-west-1",
+    "eu-west-2",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/literals.pyi` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/literals.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -16,104 +16,42 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AccessTypeType",
-    "AwsLogSourceTypeType",
-    "DimensionType",
-    "EndpointProtocolType",
-    "GetDatalakeStatusPaginatorName",
-    "HttpsMethodType",
-    "ListDatalakeExceptionsPaginatorName",
+    "AwsLogSourceNameType",
+    "DataLakeStatusType",
+    "GetDataLakeSourcesPaginatorName",
+    "HttpMethodType",
+    "ListDataLakeExceptionsPaginatorName",
     "ListLogSourcesPaginatorName",
     "ListSubscribersPaginatorName",
-    "OcsfEventClassType",
-    "RegionType",
-    "SourceStatusType",
-    "StorageClassType",
-    "SubscriptionProtocolTypeType",
-    "SubscriptionStatusType",
-    "settingsStatusType",
+    "SourceCollectionStatusType",
+    "SubscriberStatusType",
     "SecurityLakeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AccessTypeType = Literal["LAKEFORMATION", "S3"]
-AwsLogSourceTypeType = Literal["CLOUD_TRAIL", "ROUTE53", "SH_FINDINGS", "VPC_FLOW"]
-DimensionType = Literal["MEMBER", "REGION", "SOURCE_TYPE"]
-EndpointProtocolType = Literal["HTTPS", "SQS"]
-GetDatalakeStatusPaginatorName = Literal["get_datalake_status"]
-HttpsMethodType = Literal["POST", "PUT"]
-ListDatalakeExceptionsPaginatorName = Literal["list_datalake_exceptions"]
+AwsLogSourceNameType = Literal[
+    "CLOUD_TRAIL_MGMT", "LAMBDA_EXECUTION", "ROUTE53", "S3_DATA", "SH_FINDINGS", "VPC_FLOW"
+]
+DataLakeStatusType = Literal["COMPLETED", "FAILED", "INITIALIZED", "PENDING"]
+GetDataLakeSourcesPaginatorName = Literal["get_data_lake_sources"]
+HttpMethodType = Literal["POST", "PUT"]
+ListDataLakeExceptionsPaginatorName = Literal["list_data_lake_exceptions"]
 ListLogSourcesPaginatorName = Literal["list_log_sources"]
 ListSubscribersPaginatorName = Literal["list_subscribers"]
-OcsfEventClassType = Literal[
-    "ACCESS_ACTIVITY",
-    "ACCOUNT_CHANGE",
-    "AUTHENTICATION",
-    "AUTHORIZATION",
-    "CLOUD_API",
-    "CLOUD_STORAGE",
-    "CONFIG_STATE",
-    "CONTAINER_LIFECYCLE",
-    "DATABASE_LIFECYCLE",
-    "DHCP_ACTIVITY",
-    "DNS_ACTIVITY",
-    "ENTITY_MANAGEMENT_AUDIT",
-    "FILE_ACTIVITY",
-    "FTP_ACTIVITY",
-    "HTTP_ACTIVITY",
-    "INVENTORY_INFO",
-    "KERNEL_ACTIVITY",
-    "KERNEL_EXTENSION",
-    "MEMORY_ACTIVITY",
-    "MODULE_ACTIVITY",
-    "NETWORK_ACTIVITY",
-    "PROCESS_ACTIVITY",
-    "RDP_ACTIVITY",
-    "REGISTRY_KEY_ACTIVITY",
-    "REGISTRY_VALUE_ACTIVITY",
-    "RESOURCE_ACTIVITY",
-    "RFB_ACTIVITY",
-    "SCHEDULED_JOB_ACTIVITY",
-    "SECURITY_FINDING",
-    "SMB_ACTIVITY",
-    "SMTP_ACTIVITY",
-    "SSH_ACTIVITY",
-    "VIRTUAL_MACHINE_ACTIVITY",
-]
-RegionType = Literal[
-    "ap-northeast-1",
-    "ap-southeast-2",
-    "eu-central-1",
-    "eu-west-1",
-    "us-east-1",
-    "us-east-2",
-    "us-west-2",
-]
-SourceStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING"]
-StorageClassType = Literal[
-    "DEEP_ARCHIVE",
-    "EXPIRE",
-    "GLACIER",
-    "GLACIER_IR",
-    "INTELLIGENT_TIERING",
-    "ONEZONE_IA",
-    "STANDARD_IA",
-]
-SubscriptionProtocolTypeType = Literal[
-    "APP", "EMAIL", "EMAIL_JSON", "FIREHOSE", "HTTP", "HTTPS", "LAMBDA", "SMS", "SQS"
-]
-SubscriptionStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING", "READY"]
-settingsStatusType = Literal["COMPLETED", "FAILED", "INITIALIZED", "PENDING"]
+SourceCollectionStatusType = Literal["COLLECTING", "MISCONFIGURED", "NOT_COLLECTING"]
+SubscriberStatusType = Literal["ACTIVE", "DEACTIVATED", "PENDING", "READY"]
 SecurityLakeServiceName = Literal["securitylake"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -169,14 +107,15 @@
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
@@ -255,14 +194,15 @@
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
@@ -273,14 +213,15 @@
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
@@ -316,14 +257,15 @@
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
@@ -342,16 +284,19 @@
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
@@ -435,15 +380,17 @@
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
@@ -462,18 +409,24 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
-    "get_datalake_status", "list_datalake_exceptions", "list_log_sources", "list_subscribers"
+    "get_data_lake_sources", "list_data_lake_exceptions", "list_log_sources", "list_subscribers"
 ]
 RegionName = Literal[
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
+    "ap-southeast-1",
     "ap-southeast-2",
     "eu-central-1",
     "eu-west-1",
+    "eu-west-2",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/paginator.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/paginator.py`

 * *Files 14% similar despite different names*

```diff
@@ -6,54 +6,47 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_securitylake.client import SecurityLakeClient
     from types_aiobotocore_securitylake.paginator import (
-        GetDatalakeStatusPaginator,
-        ListDatalakeExceptionsPaginator,
+        GetDataLakeSourcesPaginator,
+        ListDataLakeExceptionsPaginator,
         ListLogSourcesPaginator,
         ListSubscribersPaginator,
     )
 
     session = get_session()
     with session.create_client("securitylake") as client:
         client: SecurityLakeClient
 
-        get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator("get_datalake_status")
-        list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator("list_datalake_exceptions")
+        get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator("get_data_lake_sources")
+        list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator("list_data_lake_exceptions")
         list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
         list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import DimensionType, RegionType
 from .type_defs import (
-    GetDatalakeStatusResponseTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
     ListLogSourcesResponseTypeDef,
     ListSubscribersResponseTypeDef,
+    LogSourceResourceTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
-    "GetDatalakeStatusPaginator",
-    "ListDatalakeExceptionsPaginator",
+    "GetDataLakeSourcesPaginator",
+    "ListDataLakeExceptionsPaginator",
     "ListLogSourcesPaginator",
     "ListSubscribersPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
@@ -61,74 +54,70 @@
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
 
-class GetDatalakeStatusPaginator(AioPaginator):
+class GetDataLakeSourcesPaginator(AioPaginator):
     """
-    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDatalakeStatus)
-    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakestatuspaginator)
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDataLakeSources)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakesourcespaginator)
     """
 
     def paginate(
-        self, *, accountSet: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
-    ) -> AsyncIterator[GetDatalakeStatusResponseTypeDef]:
+        self, *, accounts: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[GetDataLakeSourcesResponseTypeDef]:
         """
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDatalakeStatus.paginate)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakestatuspaginator)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDataLakeSources.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakesourcespaginator)
         """
 
 
-class ListDatalakeExceptionsPaginator(AioPaginator):
+class ListDataLakeExceptionsPaginator(AioPaginator):
     """
-    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDatalakeExceptions)
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDataLakeExceptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listdatalakeexceptionspaginator)
     """
 
     def paginate(
-        self,
-        *,
-        regionSet: Sequence[RegionType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
-    ) -> AsyncIterator[ListDatalakeExceptionsResponseTypeDef]:
+        self, *, regions: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListDataLakeExceptionsResponseTypeDef]:
         """
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDatalakeExceptions.paginate)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDataLakeExceptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listdatalakeexceptionspaginator)
         """
 
 
 class ListLogSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListLogSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listlogsourcespaginator)
     """
 
     def paginate(
         self,
         *,
-        inputOrder: Sequence[DimensionType] = ...,
-        listAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        listSingleDimension: Sequence[str] = ...,
-        listTwoDimensions: Mapping[str, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        accounts: Sequence[str] = ...,
+        regions: Sequence[str] = ...,
+        sources: Sequence[LogSourceResourceTypeDef] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLogSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListLogSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listlogsourcespaginator)
         """
 
 
 class ListSubscribersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListSubscribers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listsubscriberspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSubscribersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListSubscribers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listsubscriberspaginator)
         """
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/paginator.pyi` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/paginator.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -6,122 +6,112 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_securitylake.client import SecurityLakeClient
     from types_aiobotocore_securitylake.paginator import (
-        GetDatalakeStatusPaginator,
-        ListDatalakeExceptionsPaginator,
+        GetDataLakeSourcesPaginator,
+        ListDataLakeExceptionsPaginator,
         ListLogSourcesPaginator,
         ListSubscribersPaginator,
     )
 
     session = get_session()
     with session.create_client("securitylake") as client:
         client: SecurityLakeClient
 
-        get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator("get_datalake_status")
-        list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator("list_datalake_exceptions")
+        get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator("get_data_lake_sources")
+        list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator("list_data_lake_exceptions")
         list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
         list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import DimensionType, RegionType
 from .type_defs import (
-    GetDatalakeStatusResponseTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
     ListLogSourcesResponseTypeDef,
     ListSubscribersResponseTypeDef,
+    LogSourceResourceTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
-    "GetDatalakeStatusPaginator",
-    "ListDatalakeExceptionsPaginator",
+    "GetDataLakeSourcesPaginator",
+    "ListDataLakeExceptionsPaginator",
     "ListLogSourcesPaginator",
     "ListSubscribersPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-class GetDatalakeStatusPaginator(AioPaginator):
+class GetDataLakeSourcesPaginator(AioPaginator):
     """
-    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDatalakeStatus)
-    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakestatuspaginator)
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDataLakeSources)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakesourcespaginator)
     """
 
     def paginate(
-        self, *, accountSet: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
-    ) -> AsyncIterator[GetDatalakeStatusResponseTypeDef]:
+        self, *, accounts: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[GetDataLakeSourcesResponseTypeDef]:
         """
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDatalakeStatus.paginate)
-        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakestatuspaginator)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.GetDataLakeSources.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#getdatalakesourcespaginator)
         """
 
-class ListDatalakeExceptionsPaginator(AioPaginator):
+class ListDataLakeExceptionsPaginator(AioPaginator):
     """
-    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDatalakeExceptions)
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDataLakeExceptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listdatalakeexceptionspaginator)
     """
 
     def paginate(
-        self,
-        *,
-        regionSet: Sequence[RegionType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
-    ) -> AsyncIterator[ListDatalakeExceptionsResponseTypeDef]:
+        self, *, regions: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListDataLakeExceptionsResponseTypeDef]:
         """
-        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDatalakeExceptions.paginate)
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListDataLakeExceptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listdatalakeexceptionspaginator)
         """
 
 class ListLogSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListLogSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listlogsourcespaginator)
     """
 
     def paginate(
         self,
         *,
-        inputOrder: Sequence[DimensionType] = ...,
-        listAllDimensions: Mapping[str, Mapping[str, Sequence[str]]] = ...,
-        listSingleDimension: Sequence[str] = ...,
-        listTwoDimensions: Mapping[str, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        accounts: Sequence[str] = ...,
+        regions: Sequence[str] = ...,
+        sources: Sequence[LogSourceResourceTypeDef] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLogSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListLogSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listlogsourcespaginator)
         """
 
 class ListSubscribersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListSubscribers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listsubscriberspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSubscribersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake.Paginator.ListSubscribers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/paginators/#listsubscriberspaginator)
         """
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/type_defs.py` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/type_defs.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -2,756 +2,887 @@
 Type annotations for securitylake service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_securitylake.type_defs import LogsStatusTypeDef
+    from types_aiobotocore_securitylake.type_defs import AwsIdentityTypeDef
 
-    data: LogsStatusTypeDef = {...}
+    data: AwsIdentityTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
     AccessTypeType,
-    AwsLogSourceTypeType,
-    DimensionType,
-    EndpointProtocolType,
-    HttpsMethodType,
-    OcsfEventClassType,
-    RegionType,
-    SourceStatusType,
-    StorageClassType,
-    SubscriptionProtocolTypeType,
-    SubscriptionStatusType,
-    settingsStatusType,
+    AwsLogSourceNameType,
+    DataLakeStatusType,
+    HttpMethodType,
+    SourceCollectionStatusType,
+    SubscriberStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
-    "LogsStatusTypeDef",
-    "AutoEnableNewRegionConfigurationTypeDef",
-    "CreateAwsLogSourceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "CreateCustomLogSourceRequestRequestTypeDef",
-    "CreateDatalakeDelegatedAdminRequestRequestTypeDef",
-    "CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
-    "SourceTypeTypeDef",
-    "CreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "DeleteAwsLogSourceRequestRequestTypeDef",
+    "AwsIdentityTypeDef",
+    "AwsLogSourceConfigurationTypeDef",
+    "AwsLogSourceResourceTypeDef",
+    "CreateAwsLogSourceResponseTypeDef",
+    "CreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    "CreateSubscriberNotificationResponseTypeDef",
+    "CustomLogSourceAttributesTypeDef",
+    "CustomLogSourceCrawlerConfigurationTypeDef",
+    "CustomLogSourceProviderTypeDef",
+    "DataLakeEncryptionConfigurationTypeDef",
+    "DataLakeReplicationConfigurationTypeDef",
+    "DataLakeExceptionTypeDef",
+    "DataLakeLifecycleExpirationTypeDef",
+    "DataLakeLifecycleTransitionTypeDef",
+    "DataLakeSourceStatusTypeDef",
+    "DataLakeUpdateExceptionTypeDef",
+    "DeleteAwsLogSourceResponseTypeDef",
     "DeleteCustomLogSourceRequestRequestTypeDef",
-    "DeleteDatalakeDelegatedAdminRequestRequestTypeDef",
+    "DeleteDataLakeRequestRequestTypeDef",
+    "DeleteSubscriberNotificationRequestRequestTypeDef",
     "DeleteSubscriberRequestRequestTypeDef",
-    "DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "FailuresTypeDef",
-    "ProtocolAndNotificationEndpointTypeDef",
-    "PaginatorConfigTypeDef",
-    "GetDatalakeStatusRequestRequestTypeDef",
+    "GetDataLakeExceptionSubscriptionResponseTypeDef",
+    "GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef",
+    "GetDataLakeSourcesRequestRequestTypeDef",
     "GetSubscriberRequestRequestTypeDef",
-    "RetentionSettingTypeDef",
-    "ListDatalakeExceptionsRequestRequestTypeDef",
-    "ListLogSourcesRequestRequestTypeDef",
+    "HttpsNotificationConfigurationTypeDef",
+    "ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef",
+    "ListDataLakeExceptionsRequestRequestTypeDef",
+    "ListDataLakesRequestRequestTypeDef",
+    "ListSubscribersRequestListSubscribersPaginateTypeDef",
     "ListSubscribersRequestRequestTypeDef",
-    "UpdateDatalakeExceptionsExpiryRequestRequestTypeDef",
-    "UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
-    "UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "AccountSourcesTypeDef",
-    "CreateDatalakeAutoEnableRequestRequestTypeDef",
-    "DeleteDatalakeAutoEnableRequestRequestTypeDef",
-    "CreateAwsLogSourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    "UpdateSubscriberNotificationResponseTypeDef",
+    "CreateAwsLogSourceRequestRequestTypeDef",
+    "DeleteAwsLogSourceRequestRequestTypeDef",
+    "DataLakeAutoEnableNewAccountConfigurationTypeDef",
+    "CustomLogSourceConfigurationTypeDef",
+    "CustomLogSourceResourceTypeDef",
+    "ListDataLakeExceptionsResponseTypeDef",
+    "DataLakeLifecycleConfigurationTypeDef",
+    "DataLakeSourceTypeDef",
+    "DataLakeUpdateStatusTypeDef",
+    "NotificationConfigurationTypeDef",
+    "CreateDataLakeOrganizationConfigurationRequestRequestTypeDef",
+    "DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef",
+    "GetDataLakeOrganizationConfigurationResponseTypeDef",
+    "CreateCustomLogSourceRequestRequestTypeDef",
     "CreateCustomLogSourceResponseTypeDef",
-    "CreateSubscriberResponseTypeDef",
-    "CreateSubscriptionNotificationConfigurationResponseTypeDef",
-    "DeleteAwsLogSourceResponseTypeDef",
-    "DeleteCustomLogSourceResponseTypeDef",
-    "DeleteDatalakeExceptionsSubscriptionResponseTypeDef",
-    "GetDatalakeAutoEnableResponseTypeDef",
-    "GetDatalakeExceptionsExpiryResponseTypeDef",
-    "ListLogSourcesResponseTypeDef",
-    "UpdateSubscriptionNotificationConfigurationResponseTypeDef",
+    "LogSourceResourceTypeDef",
+    "DataLakeConfigurationTypeDef",
+    "GetDataLakeSourcesResponseTypeDef",
+    "DataLakeResourceTypeDef",
+    "CreateSubscriberNotificationRequestRequestTypeDef",
+    "UpdateSubscriberNotificationRequestRequestTypeDef",
     "CreateSubscriberRequestRequestTypeDef",
+    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+    "ListLogSourcesRequestRequestTypeDef",
+    "LogSourceTypeDef",
     "SubscriberResourceTypeDef",
     "UpdateSubscriberRequestRequestTypeDef",
-    "FailuresResponseTypeDef",
-    "GetDatalakeExceptionsSubscriptionResponseTypeDef",
-    "GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef",
-    "ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef",
-    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
-    "ListSubscribersRequestListSubscribersPaginateTypeDef",
-    "LakeConfigurationRequestTypeDef",
-    "LakeConfigurationResponseTypeDef",
-    "GetDatalakeStatusResponseTypeDef",
+    "CreateDataLakeRequestRequestTypeDef",
+    "UpdateDataLakeRequestRequestTypeDef",
+    "CreateDataLakeResponseTypeDef",
+    "ListDataLakesResponseTypeDef",
+    "UpdateDataLakeResponseTypeDef",
+    "ListLogSourcesResponseTypeDef",
+    "CreateSubscriberResponseTypeDef",
     "GetSubscriberResponseTypeDef",
     "ListSubscribersResponseTypeDef",
     "UpdateSubscriberResponseTypeDef",
-    "ListDatalakeExceptionsResponseTypeDef",
-    "CreateDatalakeRequestRequestTypeDef",
-    "UpdateDatalakeRequestRequestTypeDef",
-    "GetDatalakeResponseTypeDef",
 )
 
-LogsStatusTypeDef = TypedDict(
-    "LogsStatusTypeDef",
+AwsIdentityTypeDef = TypedDict(
+    "AwsIdentityTypeDef",
     {
-        "healthStatus": SourceStatusType,
-        "pathToLogs": str,
+        "externalId": str,
+        "principal": str,
     },
 )
 
-AutoEnableNewRegionConfigurationTypeDef = TypedDict(
-    "AutoEnableNewRegionConfigurationTypeDef",
+_RequiredAwsLogSourceConfigurationTypeDef = TypedDict(
+    "_RequiredAwsLogSourceConfigurationTypeDef",
     {
-        "region": RegionType,
-        "sources": Sequence[AwsLogSourceTypeType],
+        "regions": Sequence[str],
+        "sourceName": AwsLogSourceNameType,
     },
 )
-
-_RequiredCreateAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateAwsLogSourceRequestRequestTypeDef",
+_OptionalAwsLogSourceConfigurationTypeDef = TypedDict(
+    "_OptionalAwsLogSourceConfigurationTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
+        "accounts": Sequence[str],
+        "sourceVersion": str,
     },
+    total=False,
 )
-_OptionalCreateAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateAwsLogSourceRequestRequestTypeDef",
+
+class AwsLogSourceConfigurationTypeDef(
+    _RequiredAwsLogSourceConfigurationTypeDef, _OptionalAwsLogSourceConfigurationTypeDef
+):
+    pass
+
+AwsLogSourceResourceTypeDef = TypedDict(
+    "AwsLogSourceResourceTypeDef",
     {
-        "enableAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "enableSingleDimension": Sequence[str],
-        "enableTwoDimensions": Mapping[str, Sequence[str]],
+        "sourceName": AwsLogSourceNameType,
+        "sourceVersion": str,
     },
     total=False,
 )
 
+CreateAwsLogSourceResponseTypeDef = TypedDict(
+    "CreateAwsLogSourceResponseTypeDef",
+    {
+        "failed": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-class CreateAwsLogSourceRequestRequestTypeDef(
-    _RequiredCreateAwsLogSourceRequestRequestTypeDef,
-    _OptionalCreateAwsLogSourceRequestRequestTypeDef,
+_RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    {
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
+    },
+)
+_OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    {
+        "exceptionTimeToLive": int,
+    },
+    total=False,
+)
+
+class CreateDataLakeExceptionSubscriptionRequestRequestTypeDef(
+    _RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    _OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
 ):
     pass
 
+CreateSubscriberNotificationResponseTypeDef = TypedDict(
+    "CreateSubscriberNotificationResponseTypeDef",
+    {
+        "subscriberEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CustomLogSourceAttributesTypeDef = TypedDict(
+    "CustomLogSourceAttributesTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "crawlerArn": str,
+        "databaseArn": str,
+        "tableArn": str,
     },
+    total=False,
 )
 
-CreateCustomLogSourceRequestRequestTypeDef = TypedDict(
-    "CreateCustomLogSourceRequestRequestTypeDef",
+CustomLogSourceCrawlerConfigurationTypeDef = TypedDict(
+    "CustomLogSourceCrawlerConfigurationTypeDef",
     {
-        "customSourceName": str,
-        "eventClass": OcsfEventClassType,
-        "glueInvocationRoleArn": str,
-        "logProviderAccountId": str,
+        "roleArn": str,
     },
 )
 
-CreateDatalakeDelegatedAdminRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeDelegatedAdminRequestRequestTypeDef",
+CustomLogSourceProviderTypeDef = TypedDict(
+    "CustomLogSourceProviderTypeDef",
     {
-        "account": str,
+        "location": str,
+        "roleArn": str,
     },
+    total=False,
 )
 
-CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
+DataLakeEncryptionConfigurationTypeDef = TypedDict(
+    "DataLakeEncryptionConfigurationTypeDef",
     {
-        "notificationEndpoint": str,
-        "subscriptionProtocol": SubscriptionProtocolTypeType,
+        "kmsKeyId": str,
     },
+    total=False,
 )
 
-SourceTypeTypeDef = TypedDict(
-    "SourceTypeTypeDef",
+DataLakeReplicationConfigurationTypeDef = TypedDict(
+    "DataLakeReplicationConfigurationTypeDef",
     {
-        "awsSourceType": AwsLogSourceTypeType,
-        "customSourceType": str,
+        "regions": Sequence[str],
+        "roleArn": str,
     },
     total=False,
 )
 
-_RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+DataLakeExceptionTypeDef = TypedDict(
+    "DataLakeExceptionTypeDef",
     {
-        "subscriptionId": str,
+        "exception": str,
+        "region": str,
+        "remediation": str,
+        "timestamp": datetime,
     },
+    total=False,
 )
-_OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+
+DataLakeLifecycleExpirationTypeDef = TypedDict(
+    "DataLakeLifecycleExpirationTypeDef",
     {
-        "createSqs": bool,
-        "httpsApiKeyName": str,
-        "httpsApiKeyValue": str,
-        "httpsMethod": HttpsMethodType,
-        "roleArn": str,
-        "subscriptionEndpoint": str,
+        "days": int,
     },
     total=False,
 )
 
+DataLakeLifecycleTransitionTypeDef = TypedDict(
+    "DataLakeLifecycleTransitionTypeDef",
+    {
+        "days": int,
+        "storageClass": str,
+    },
+    total=False,
+)
 
-class CreateSubscriptionNotificationConfigurationRequestRequestTypeDef(
-    _RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    _OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-):
-    pass
+DataLakeSourceStatusTypeDef = TypedDict(
+    "DataLakeSourceStatusTypeDef",
+    {
+        "resource": str,
+        "status": SourceCollectionStatusType,
+    },
+    total=False,
+)
+
+DataLakeUpdateExceptionTypeDef = TypedDict(
+    "DataLakeUpdateExceptionTypeDef",
+    {
+        "code": str,
+        "reason": str,
+    },
+    total=False,
+)
 
+DeleteAwsLogSourceResponseTypeDef = TypedDict(
+    "DeleteAwsLogSourceResponseTypeDef",
+    {
+        "failed": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-_RequiredDeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_RequiredDeleteAwsLogSourceRequestRequestTypeDef",
+_RequiredDeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeleteCustomLogSourceRequestRequestTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
+        "sourceName": str,
     },
 )
-_OptionalDeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_OptionalDeleteAwsLogSourceRequestRequestTypeDef",
+_OptionalDeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeleteCustomLogSourceRequestRequestTypeDef",
     {
-        "disableAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "disableSingleDimension": Sequence[str],
-        "disableTwoDimensions": Mapping[str, Sequence[str]],
+        "sourceVersion": str,
     },
     total=False,
 )
 
-
-class DeleteAwsLogSourceRequestRequestTypeDef(
-    _RequiredDeleteAwsLogSourceRequestRequestTypeDef,
-    _OptionalDeleteAwsLogSourceRequestRequestTypeDef,
+class DeleteCustomLogSourceRequestRequestTypeDef(
+    _RequiredDeleteCustomLogSourceRequestRequestTypeDef,
+    _OptionalDeleteCustomLogSourceRequestRequestTypeDef,
 ):
     pass
 
-
-DeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
-    "DeleteCustomLogSourceRequestRequestTypeDef",
+DeleteDataLakeRequestRequestTypeDef = TypedDict(
+    "DeleteDataLakeRequestRequestTypeDef",
     {
-        "customSourceName": str,
+        "regions": Sequence[str],
     },
 )
 
-DeleteDatalakeDelegatedAdminRequestRequestTypeDef = TypedDict(
-    "DeleteDatalakeDelegatedAdminRequestRequestTypeDef",
+DeleteSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "DeleteSubscriberNotificationRequestRequestTypeDef",
     {
-        "account": str,
+        "subscriberId": str,
     },
 )
 
 DeleteSubscriberRequestRequestTypeDef = TypedDict(
     "DeleteSubscriberRequestRequestTypeDef",
     {
-        "id": str,
+        "subscriberId": str,
     },
 )
 
-DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef",
+GetDataLakeExceptionSubscriptionResponseTypeDef = TypedDict(
+    "GetDataLakeExceptionSubscriptionResponseTypeDef",
     {
-        "subscriptionId": str,
+        "exceptionTimeToLive": int,
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-FailuresTypeDef = TypedDict(
-    "FailuresTypeDef",
+GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef = TypedDict(
+    "GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef",
     {
-        "exceptionMessage": str,
-        "remediation": str,
-        "timestamp": datetime,
+        "accounts": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-ProtocolAndNotificationEndpointTypeDef = TypedDict(
-    "ProtocolAndNotificationEndpointTypeDef",
+GetDataLakeSourcesRequestRequestTypeDef = TypedDict(
+    "GetDataLakeSourcesRequestRequestTypeDef",
     {
-        "endpoint": str,
-        "protocol": str,
+        "accounts": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetSubscriberRequestRequestTypeDef = TypedDict(
+    "GetSubscriberRequestRequestTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "subscriberId": str,
     },
-    total=False,
 )
 
-GetDatalakeStatusRequestRequestTypeDef = TypedDict(
-    "GetDatalakeStatusRequestRequestTypeDef",
+_RequiredHttpsNotificationConfigurationTypeDef = TypedDict(
+    "_RequiredHttpsNotificationConfigurationTypeDef",
     {
-        "accountSet": Sequence[str],
-        "maxAccountResults": int,
-        "nextToken": str,
+        "endpoint": str,
+        "targetRoleArn": str,
+    },
+)
+_OptionalHttpsNotificationConfigurationTypeDef = TypedDict(
+    "_OptionalHttpsNotificationConfigurationTypeDef",
+    {
+        "authorizationApiKeyName": str,
+        "authorizationApiKeyValue": str,
+        "httpMethod": HttpMethodType,
     },
     total=False,
 )
 
-GetSubscriberRequestRequestTypeDef = TypedDict(
-    "GetSubscriberRequestRequestTypeDef",
+class HttpsNotificationConfigurationTypeDef(
+    _RequiredHttpsNotificationConfigurationTypeDef, _OptionalHttpsNotificationConfigurationTypeDef
+):
+    pass
+
+ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef = TypedDict(
+    "ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef",
     {
-        "id": str,
+        "regions": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-RetentionSettingTypeDef = TypedDict(
-    "RetentionSettingTypeDef",
+ListDataLakeExceptionsRequestRequestTypeDef = TypedDict(
+    "ListDataLakeExceptionsRequestRequestTypeDef",
     {
-        "retentionPeriod": int,
-        "storageClass": StorageClassType,
+        "maxResults": int,
+        "nextToken": str,
+        "regions": Sequence[str],
     },
     total=False,
 )
 
-ListDatalakeExceptionsRequestRequestTypeDef = TypedDict(
-    "ListDatalakeExceptionsRequestRequestTypeDef",
+ListDataLakesRequestRequestTypeDef = TypedDict(
+    "ListDataLakesRequestRequestTypeDef",
     {
-        "maxFailures": int,
-        "nextToken": str,
-        "regionSet": Sequence[RegionType],
+        "regions": Sequence[str],
     },
     total=False,
 )
 
-ListLogSourcesRequestRequestTypeDef = TypedDict(
-    "ListLogSourcesRequestRequestTypeDef",
+ListSubscribersRequestListSubscribersPaginateTypeDef = TypedDict(
+    "ListSubscribersRequestListSubscribersPaginateTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
-        "listAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "listSingleDimension": Sequence[str],
-        "listTwoDimensions": Mapping[str, Sequence[str]],
-        "maxResults": int,
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSubscribersRequestRequestTypeDef = TypedDict(
     "ListSubscribersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-UpdateDatalakeExceptionsExpiryRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeExceptionsExpiryRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "exceptionMessageExpiry": int,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
+RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef = TypedDict(
+    "RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef",
     {
-        "notificationEndpoint": str,
-        "subscriptionProtocol": SubscriptionProtocolTypeType,
+        "accountId": str,
     },
 )
 
-_RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "subscriptionId": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
-_OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+
+_RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
     {
-        "createSqs": bool,
-        "httpsApiKeyName": str,
-        "httpsApiKeyValue": str,
-        "httpsMethod": HttpsMethodType,
-        "roleArn": str,
-        "subscriptionEndpoint": str,
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
+    },
+)
+_OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    {
+        "exceptionTimeToLive": int,
     },
     total=False,
 )
 
-
-class UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef(
-    _RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    _OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
+class UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef(
+    _RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    _OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
 ):
     pass
 
+UpdateSubscriberNotificationResponseTypeDef = TypedDict(
+    "UpdateSubscriberNotificationResponseTypeDef",
+    {
+        "subscriberEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAwsLogSourceRequestRequestTypeDef = TypedDict(
+    "CreateAwsLogSourceRequestRequestTypeDef",
+    {
+        "sources": Sequence[AwsLogSourceConfigurationTypeDef],
+    },
+)
 
-_RequiredAccountSourcesTypeDef = TypedDict(
-    "_RequiredAccountSourcesTypeDef",
+DeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
+    "DeleteAwsLogSourceRequestRequestTypeDef",
     {
-        "account": str,
-        "sourceType": str,
+        "sources": Sequence[AwsLogSourceConfigurationTypeDef],
     },
 )
-_OptionalAccountSourcesTypeDef = TypedDict(
-    "_OptionalAccountSourcesTypeDef",
+
+DataLakeAutoEnableNewAccountConfigurationTypeDef = TypedDict(
+    "DataLakeAutoEnableNewAccountConfigurationTypeDef",
     {
-        "eventClass": OcsfEventClassType,
-        "logsStatus": List[LogsStatusTypeDef],
+        "region": str,
+        "sources": Sequence[AwsLogSourceResourceTypeDef],
     },
-    total=False,
 )
 
+CustomLogSourceConfigurationTypeDef = TypedDict(
+    "CustomLogSourceConfigurationTypeDef",
+    {
+        "crawlerConfiguration": CustomLogSourceCrawlerConfigurationTypeDef,
+        "providerIdentity": AwsIdentityTypeDef,
+    },
+)
 
-class AccountSourcesTypeDef(_RequiredAccountSourcesTypeDef, _OptionalAccountSourcesTypeDef):
-    pass
+CustomLogSourceResourceTypeDef = TypedDict(
+    "CustomLogSourceResourceTypeDef",
+    {
+        "attributes": CustomLogSourceAttributesTypeDef,
+        "provider": CustomLogSourceProviderTypeDef,
+        "sourceName": str,
+        "sourceVersion": str,
+    },
+    total=False,
+)
 
+ListDataLakeExceptionsResponseTypeDef = TypedDict(
+    "ListDataLakeExceptionsResponseTypeDef",
+    {
+        "exceptions": List[DataLakeExceptionTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-CreateDatalakeAutoEnableRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeAutoEnableRequestRequestTypeDef",
+DataLakeLifecycleConfigurationTypeDef = TypedDict(
+    "DataLakeLifecycleConfigurationTypeDef",
     {
-        "configurationForNewAccounts": Sequence[AutoEnableNewRegionConfigurationTypeDef],
+        "expiration": DataLakeLifecycleExpirationTypeDef,
+        "transitions": Sequence[DataLakeLifecycleTransitionTypeDef],
     },
+    total=False,
 )
 
-DeleteDatalakeAutoEnableRequestRequestTypeDef = TypedDict(
-    "DeleteDatalakeAutoEnableRequestRequestTypeDef",
+DataLakeSourceTypeDef = TypedDict(
+    "DataLakeSourceTypeDef",
     {
-        "removeFromConfigurationForNewAccounts": Sequence[AutoEnableNewRegionConfigurationTypeDef],
+        "account": str,
+        "eventClasses": List[str],
+        "sourceName": str,
+        "sourceStatuses": List[DataLakeSourceStatusTypeDef],
     },
+    total=False,
 )
 
-CreateAwsLogSourceResponseTypeDef = TypedDict(
-    "CreateAwsLogSourceResponseTypeDef",
+DataLakeUpdateStatusTypeDef = TypedDict(
+    "DataLakeUpdateStatusTypeDef",
     {
-        "failed": List[str],
-        "processing": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "exception": DataLakeUpdateExceptionTypeDef,
+        "requestId": str,
+        "status": DataLakeStatusType,
     },
+    total=False,
 )
 
-CreateCustomLogSourceResponseTypeDef = TypedDict(
-    "CreateCustomLogSourceResponseTypeDef",
+NotificationConfigurationTypeDef = TypedDict(
+    "NotificationConfigurationTypeDef",
     {
-        "customDataLocation": str,
-        "glueCrawlerName": str,
-        "glueDatabaseName": str,
-        "glueTableName": str,
-        "logProviderAccessRoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "httpsNotificationConfiguration": HttpsNotificationConfigurationTypeDef,
+        "sqsNotificationConfiguration": Mapping[str, Any],
     },
+    total=False,
 )
 
-CreateSubscriberResponseTypeDef = TypedDict(
-    "CreateSubscriberResponseTypeDef",
+CreateDataLakeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "CreateDataLakeOrganizationConfigurationRequestRequestTypeDef",
     {
-        "roleArn": str,
-        "s3BucketArn": str,
-        "snsArn": str,
-        "subscriptionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef],
     },
 )
 
-CreateSubscriptionNotificationConfigurationResponseTypeDef = TypedDict(
-    "CreateSubscriptionNotificationConfigurationResponseTypeDef",
+DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef",
     {
-        "queueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef],
     },
 )
 
-DeleteAwsLogSourceResponseTypeDef = TypedDict(
-    "DeleteAwsLogSourceResponseTypeDef",
+GetDataLakeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "GetDataLakeOrganizationConfigurationResponseTypeDef",
     {
-        "failed": List[str],
-        "processing": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": List[DataLakeAutoEnableNewAccountConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteCustomLogSourceResponseTypeDef = TypedDict(
-    "DeleteCustomLogSourceResponseTypeDef",
+_RequiredCreateCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateCustomLogSourceRequestRequestTypeDef",
     {
-        "customDataLocation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceName": str,
     },
 )
+_OptionalCreateCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateCustomLogSourceRequestRequestTypeDef",
+    {
+        "configuration": CustomLogSourceConfigurationTypeDef,
+        "eventClasses": Sequence[str],
+        "sourceVersion": str,
+    },
+    total=False,
+)
+
+class CreateCustomLogSourceRequestRequestTypeDef(
+    _RequiredCreateCustomLogSourceRequestRequestTypeDef,
+    _OptionalCreateCustomLogSourceRequestRequestTypeDef,
+):
+    pass
 
-DeleteDatalakeExceptionsSubscriptionResponseTypeDef = TypedDict(
-    "DeleteDatalakeExceptionsSubscriptionResponseTypeDef",
+CreateCustomLogSourceResponseTypeDef = TypedDict(
+    "CreateCustomLogSourceResponseTypeDef",
     {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "source": CustomLogSourceResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetDatalakeAutoEnableResponseTypeDef = TypedDict(
-    "GetDatalakeAutoEnableResponseTypeDef",
+LogSourceResourceTypeDef = TypedDict(
+    "LogSourceResourceTypeDef",
     {
-        "autoEnableNewAccounts": List[AutoEnableNewRegionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "awsLogSource": AwsLogSourceResourceTypeDef,
+        "customLogSource": CustomLogSourceResourceTypeDef,
     },
+    total=False,
 )
 
-GetDatalakeExceptionsExpiryResponseTypeDef = TypedDict(
-    "GetDatalakeExceptionsExpiryResponseTypeDef",
+_RequiredDataLakeConfigurationTypeDef = TypedDict(
+    "_RequiredDataLakeConfigurationTypeDef",
+    {
+        "region": str,
+    },
+)
+_OptionalDataLakeConfigurationTypeDef = TypedDict(
+    "_OptionalDataLakeConfigurationTypeDef",
     {
-        "exceptionMessageExpiry": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "encryptionConfiguration": DataLakeEncryptionConfigurationTypeDef,
+        "lifecycleConfiguration": DataLakeLifecycleConfigurationTypeDef,
+        "replicationConfiguration": DataLakeReplicationConfigurationTypeDef,
     },
+    total=False,
 )
 
-ListLogSourcesResponseTypeDef = TypedDict(
-    "ListLogSourcesResponseTypeDef",
+class DataLakeConfigurationTypeDef(
+    _RequiredDataLakeConfigurationTypeDef, _OptionalDataLakeConfigurationTypeDef
+):
+    pass
+
+GetDataLakeSourcesResponseTypeDef = TypedDict(
+    "GetDataLakeSourcesResponseTypeDef",
     {
+        "dataLakeArn": str,
+        "dataLakeSources": List[DataLakeSourceTypeDef],
         "nextToken": str,
-        "regionSourceTypesAccountsList": List[Dict[str, Dict[str, List[str]]]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateSubscriptionNotificationConfigurationResponseTypeDef = TypedDict(
-    "UpdateSubscriptionNotificationConfigurationResponseTypeDef",
+_RequiredDataLakeResourceTypeDef = TypedDict(
+    "_RequiredDataLakeResourceTypeDef",
     {
-        "queueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "dataLakeArn": str,
+        "region": str,
+    },
+)
+_OptionalDataLakeResourceTypeDef = TypedDict(
+    "_OptionalDataLakeResourceTypeDef",
+    {
+        "createStatus": DataLakeStatusType,
+        "encryptionConfiguration": DataLakeEncryptionConfigurationTypeDef,
+        "lifecycleConfiguration": DataLakeLifecycleConfigurationTypeDef,
+        "replicationConfiguration": DataLakeReplicationConfigurationTypeDef,
+        "s3BucketArn": str,
+        "updateStatus": DataLakeUpdateStatusTypeDef,
+    },
+    total=False,
+)
+
+class DataLakeResourceTypeDef(_RequiredDataLakeResourceTypeDef, _OptionalDataLakeResourceTypeDef):
+    pass
+
+CreateSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "CreateSubscriberNotificationRequestRequestTypeDef",
+    {
+        "configuration": NotificationConfigurationTypeDef,
+        "subscriberId": str,
+    },
+)
+
+UpdateSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "UpdateSubscriberNotificationRequestRequestTypeDef",
+    {
+        "configuration": NotificationConfigurationTypeDef,
+        "subscriberId": str,
     },
 )
 
 _RequiredCreateSubscriberRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSubscriberRequestRequestTypeDef",
     {
-        "accountId": str,
-        "externalId": str,
-        "sourceTypes": Sequence[SourceTypeTypeDef],
+        "sources": Sequence[LogSourceResourceTypeDef],
+        "subscriberIdentity": AwsIdentityTypeDef,
         "subscriberName": str,
     },
 )
 _OptionalCreateSubscriberRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSubscriberRequestRequestTypeDef",
     {
         "accessTypes": Sequence[AccessTypeType],
         "subscriberDescription": str,
     },
     total=False,
 )
 
-
 class CreateSubscriberRequestRequestTypeDef(
     _RequiredCreateSubscriberRequestRequestTypeDef, _OptionalCreateSubscriberRequestRequestTypeDef
 ):
     pass
 
+ListLogSourcesRequestListLogSourcesPaginateTypeDef = TypedDict(
+    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+    {
+        "accounts": Sequence[str],
+        "regions": Sequence[str],
+        "sources": Sequence[LogSourceResourceTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListLogSourcesRequestRequestTypeDef = TypedDict(
+    "ListLogSourcesRequestRequestTypeDef",
+    {
+        "accounts": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+        "regions": Sequence[str],
+        "sources": Sequence[LogSourceResourceTypeDef],
+    },
+    total=False,
+)
+
+LogSourceTypeDef = TypedDict(
+    "LogSourceTypeDef",
+    {
+        "account": str,
+        "region": str,
+        "sources": List[LogSourceResourceTypeDef],
+    },
+    total=False,
+)
 
 _RequiredSubscriberResourceTypeDef = TypedDict(
     "_RequiredSubscriberResourceTypeDef",
     {
-        "accountId": str,
-        "sourceTypes": List[SourceTypeTypeDef],
-        "subscriptionId": str,
+        "sources": List[LogSourceResourceTypeDef],
+        "subscriberArn": str,
+        "subscriberId": str,
+        "subscriberIdentity": AwsIdentityTypeDef,
+        "subscriberName": str,
     },
 )
 _OptionalSubscriberResourceTypeDef = TypedDict(
     "_OptionalSubscriberResourceTypeDef",
     {
         "accessTypes": List[AccessTypeType],
         "createdAt": datetime,
-        "externalId": str,
+        "resourceShareArn": str,
+        "resourceShareName": str,
         "roleArn": str,
         "s3BucketArn": str,
-        "snsArn": str,
         "subscriberDescription": str,
-        "subscriberName": str,
-        "subscriptionEndpoint": str,
-        "subscriptionProtocol": EndpointProtocolType,
-        "subscriptionStatus": SubscriptionStatusType,
+        "subscriberEndpoint": str,
+        "subscriberStatus": SubscriberStatusType,
         "updatedAt": datetime,
     },
     total=False,
 )
 
-
 class SubscriberResourceTypeDef(
     _RequiredSubscriberResourceTypeDef, _OptionalSubscriberResourceTypeDef
 ):
     pass
 
-
 _RequiredUpdateSubscriberRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubscriberRequestRequestTypeDef",
     {
-        "id": str,
-        "sourceTypes": Sequence[SourceTypeTypeDef],
+        "subscriberId": str,
     },
 )
 _OptionalUpdateSubscriberRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSubscriberRequestRequestTypeDef",
     {
-        "externalId": str,
+        "sources": Sequence[LogSourceResourceTypeDef],
         "subscriberDescription": str,
+        "subscriberIdentity": AwsIdentityTypeDef,
         "subscriberName": str,
     },
     total=False,
 )
 
-
 class UpdateSubscriberRequestRequestTypeDef(
     _RequiredUpdateSubscriberRequestRequestTypeDef, _OptionalUpdateSubscriberRequestRequestTypeDef
 ):
     pass
 
-
-FailuresResponseTypeDef = TypedDict(
-    "FailuresResponseTypeDef",
-    {
-        "failures": List[FailuresTypeDef],
-        "region": str,
-    },
-    total=False,
-)
-
-GetDatalakeExceptionsSubscriptionResponseTypeDef = TypedDict(
-    "GetDatalakeExceptionsSubscriptionResponseTypeDef",
-    {
-        "protocolAndNotificationEndpoint": ProtocolAndNotificationEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef = TypedDict(
-    "GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef",
+CreateDataLakeRequestRequestTypeDef = TypedDict(
+    "CreateDataLakeRequestRequestTypeDef",
     {
-        "accountSet": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "configurations": Sequence[DataLakeConfigurationTypeDef],
+        "metaStoreManagerRoleArn": str,
     },
-    total=False,
 )
 
-ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef = TypedDict(
-    "ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef",
+UpdateDataLakeRequestRequestTypeDef = TypedDict(
+    "UpdateDataLakeRequestRequestTypeDef",
     {
-        "regionSet": Sequence[RegionType],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "configurations": Sequence[DataLakeConfigurationTypeDef],
     },
-    total=False,
 )
 
-ListLogSourcesRequestListLogSourcesPaginateTypeDef = TypedDict(
-    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+CreateDataLakeResponseTypeDef = TypedDict(
+    "CreateDataLakeResponseTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
-        "listAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "listSingleDimension": Sequence[str],
-        "listTwoDimensions": Mapping[str, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListSubscribersRequestListSubscribersPaginateTypeDef = TypedDict(
-    "ListSubscribersRequestListSubscribersPaginateTypeDef",
+ListDataLakesResponseTypeDef = TypedDict(
+    "ListDataLakesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-LakeConfigurationRequestTypeDef = TypedDict(
-    "LakeConfigurationRequestTypeDef",
+UpdateDataLakeResponseTypeDef = TypedDict(
+    "UpdateDataLakeResponseTypeDef",
     {
-        "encryptionKey": str,
-        "replicationDestinationRegions": Sequence[RegionType],
-        "replicationRoleArn": str,
-        "retentionSettings": Sequence[RetentionSettingTypeDef],
-        "tagsMap": Mapping[str, str],
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-LakeConfigurationResponseTypeDef = TypedDict(
-    "LakeConfigurationResponseTypeDef",
+ListLogSourcesResponseTypeDef = TypedDict(
+    "ListLogSourcesResponseTypeDef",
     {
-        "encryptionKey": str,
-        "replicationDestinationRegions": List[RegionType],
-        "replicationRoleArn": str,
-        "retentionSettings": List[RetentionSettingTypeDef],
-        "s3BucketArn": str,
-        "status": settingsStatusType,
-        "tagsMap": Dict[str, str],
+        "nextToken": str,
+        "sources": List[LogSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-GetDatalakeStatusResponseTypeDef = TypedDict(
-    "GetDatalakeStatusResponseTypeDef",
+CreateSubscriberResponseTypeDef = TypedDict(
+    "CreateSubscriberResponseTypeDef",
     {
-        "accountSourcesList": List[AccountSourcesTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "subscriber": SubscriberResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSubscriberResponseTypeDef = TypedDict(
     "GetSubscriberResponseTypeDef",
     {
         "subscriber": SubscriberResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSubscribersResponseTypeDef = TypedDict(
     "ListSubscribersResponseTypeDef",
     {
         "nextToken": str,
         "subscribers": List[SubscriberResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubscriberResponseTypeDef = TypedDict(
     "UpdateSubscriberResponseTypeDef",
     {
         "subscriber": SubscriberResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatalakeExceptionsResponseTypeDef = TypedDict(
-    "ListDatalakeExceptionsResponseTypeDef",
-    {
-        "nextToken": str,
-        "nonRetryableFailures": List[FailuresResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatalakeRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeRequestRequestTypeDef",
-    {
-        "configurations": Mapping[RegionType, LakeConfigurationRequestTypeDef],
-        "enableAll": bool,
-        "metaStoreManagerRoleArn": str,
-        "regions": Sequence[RegionType],
-    },
-    total=False,
-)
-
-UpdateDatalakeRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeRequestRequestTypeDef",
-    {
-        "configurations": Mapping[RegionType, LakeConfigurationRequestTypeDef],
-    },
-)
-
-GetDatalakeResponseTypeDef = TypedDict(
-    "GetDatalakeResponseTypeDef",
-    {
-        "configurations": Dict[RegionType, LakeConfigurationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake/type_defs.pyi` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake/type_defs.py`

 * *Files 24% similar despite different names*

```diff
@@ -2,739 +2,910 @@
 Type annotations for securitylake service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_securitylake.type_defs import LogsStatusTypeDef
+    from types_aiobotocore_securitylake.type_defs import AwsIdentityTypeDef
 
-    data: LogsStatusTypeDef = {...}
+    data: AwsIdentityTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
     AccessTypeType,
-    AwsLogSourceTypeType,
-    DimensionType,
-    EndpointProtocolType,
-    HttpsMethodType,
-    OcsfEventClassType,
-    RegionType,
-    SourceStatusType,
-    StorageClassType,
-    SubscriptionProtocolTypeType,
-    SubscriptionStatusType,
-    settingsStatusType,
+    AwsLogSourceNameType,
+    DataLakeStatusType,
+    HttpMethodType,
+    SourceCollectionStatusType,
+    SubscriberStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
-    "LogsStatusTypeDef",
-    "AutoEnableNewRegionConfigurationTypeDef",
-    "CreateAwsLogSourceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "CreateCustomLogSourceRequestRequestTypeDef",
-    "CreateDatalakeDelegatedAdminRequestRequestTypeDef",
-    "CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
-    "SourceTypeTypeDef",
-    "CreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "DeleteAwsLogSourceRequestRequestTypeDef",
+    "AwsIdentityTypeDef",
+    "AwsLogSourceConfigurationTypeDef",
+    "AwsLogSourceResourceTypeDef",
+    "CreateAwsLogSourceResponseTypeDef",
+    "CreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    "CreateSubscriberNotificationResponseTypeDef",
+    "CustomLogSourceAttributesTypeDef",
+    "CustomLogSourceCrawlerConfigurationTypeDef",
+    "CustomLogSourceProviderTypeDef",
+    "DataLakeEncryptionConfigurationTypeDef",
+    "DataLakeReplicationConfigurationTypeDef",
+    "DataLakeExceptionTypeDef",
+    "DataLakeLifecycleExpirationTypeDef",
+    "DataLakeLifecycleTransitionTypeDef",
+    "DataLakeSourceStatusTypeDef",
+    "DataLakeUpdateExceptionTypeDef",
+    "DeleteAwsLogSourceResponseTypeDef",
     "DeleteCustomLogSourceRequestRequestTypeDef",
-    "DeleteDatalakeDelegatedAdminRequestRequestTypeDef",
+    "DeleteDataLakeRequestRequestTypeDef",
+    "DeleteSubscriberNotificationRequestRequestTypeDef",
     "DeleteSubscriberRequestRequestTypeDef",
-    "DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "FailuresTypeDef",
-    "ProtocolAndNotificationEndpointTypeDef",
-    "PaginatorConfigTypeDef",
-    "GetDatalakeStatusRequestRequestTypeDef",
+    "GetDataLakeExceptionSubscriptionResponseTypeDef",
+    "GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef",
+    "GetDataLakeSourcesRequestRequestTypeDef",
     "GetSubscriberRequestRequestTypeDef",
-    "RetentionSettingTypeDef",
-    "ListDatalakeExceptionsRequestRequestTypeDef",
-    "ListLogSourcesRequestRequestTypeDef",
+    "HttpsNotificationConfigurationTypeDef",
+    "ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef",
+    "ListDataLakeExceptionsRequestRequestTypeDef",
+    "ListDataLakesRequestRequestTypeDef",
+    "ListSubscribersRequestListSubscribersPaginateTypeDef",
     "ListSubscribersRequestRequestTypeDef",
-    "UpdateDatalakeExceptionsExpiryRequestRequestTypeDef",
-    "UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
-    "UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
-    "AccountSourcesTypeDef",
-    "CreateDatalakeAutoEnableRequestRequestTypeDef",
-    "DeleteDatalakeAutoEnableRequestRequestTypeDef",
-    "CreateAwsLogSourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
+    "UpdateSubscriberNotificationResponseTypeDef",
+    "CreateAwsLogSourceRequestRequestTypeDef",
+    "DeleteAwsLogSourceRequestRequestTypeDef",
+    "DataLakeAutoEnableNewAccountConfigurationTypeDef",
+    "CustomLogSourceConfigurationTypeDef",
+    "CustomLogSourceResourceTypeDef",
+    "ListDataLakeExceptionsResponseTypeDef",
+    "DataLakeLifecycleConfigurationTypeDef",
+    "DataLakeSourceTypeDef",
+    "DataLakeUpdateStatusTypeDef",
+    "NotificationConfigurationTypeDef",
+    "CreateDataLakeOrganizationConfigurationRequestRequestTypeDef",
+    "DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef",
+    "GetDataLakeOrganizationConfigurationResponseTypeDef",
+    "CreateCustomLogSourceRequestRequestTypeDef",
     "CreateCustomLogSourceResponseTypeDef",
-    "CreateSubscriberResponseTypeDef",
-    "CreateSubscriptionNotificationConfigurationResponseTypeDef",
-    "DeleteAwsLogSourceResponseTypeDef",
-    "DeleteCustomLogSourceResponseTypeDef",
-    "DeleteDatalakeExceptionsSubscriptionResponseTypeDef",
-    "GetDatalakeAutoEnableResponseTypeDef",
-    "GetDatalakeExceptionsExpiryResponseTypeDef",
-    "ListLogSourcesResponseTypeDef",
-    "UpdateSubscriptionNotificationConfigurationResponseTypeDef",
+    "LogSourceResourceTypeDef",
+    "DataLakeConfigurationTypeDef",
+    "GetDataLakeSourcesResponseTypeDef",
+    "DataLakeResourceTypeDef",
+    "CreateSubscriberNotificationRequestRequestTypeDef",
+    "UpdateSubscriberNotificationRequestRequestTypeDef",
     "CreateSubscriberRequestRequestTypeDef",
+    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+    "ListLogSourcesRequestRequestTypeDef",
+    "LogSourceTypeDef",
     "SubscriberResourceTypeDef",
     "UpdateSubscriberRequestRequestTypeDef",
-    "FailuresResponseTypeDef",
-    "GetDatalakeExceptionsSubscriptionResponseTypeDef",
-    "GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef",
-    "ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef",
-    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
-    "ListSubscribersRequestListSubscribersPaginateTypeDef",
-    "LakeConfigurationRequestTypeDef",
-    "LakeConfigurationResponseTypeDef",
-    "GetDatalakeStatusResponseTypeDef",
+    "CreateDataLakeRequestRequestTypeDef",
+    "UpdateDataLakeRequestRequestTypeDef",
+    "CreateDataLakeResponseTypeDef",
+    "ListDataLakesResponseTypeDef",
+    "UpdateDataLakeResponseTypeDef",
+    "ListLogSourcesResponseTypeDef",
+    "CreateSubscriberResponseTypeDef",
     "GetSubscriberResponseTypeDef",
     "ListSubscribersResponseTypeDef",
     "UpdateSubscriberResponseTypeDef",
-    "ListDatalakeExceptionsResponseTypeDef",
-    "CreateDatalakeRequestRequestTypeDef",
-    "UpdateDatalakeRequestRequestTypeDef",
-    "GetDatalakeResponseTypeDef",
 )
 
-LogsStatusTypeDef = TypedDict(
-    "LogsStatusTypeDef",
+AwsIdentityTypeDef = TypedDict(
+    "AwsIdentityTypeDef",
+    {
+        "externalId": str,
+        "principal": str,
+    },
+)
+
+_RequiredAwsLogSourceConfigurationTypeDef = TypedDict(
+    "_RequiredAwsLogSourceConfigurationTypeDef",
+    {
+        "regions": Sequence[str],
+        "sourceName": AwsLogSourceNameType,
+    },
+)
+_OptionalAwsLogSourceConfigurationTypeDef = TypedDict(
+    "_OptionalAwsLogSourceConfigurationTypeDef",
+    {
+        "accounts": Sequence[str],
+        "sourceVersion": str,
+    },
+    total=False,
+)
+
+
+class AwsLogSourceConfigurationTypeDef(
+    _RequiredAwsLogSourceConfigurationTypeDef, _OptionalAwsLogSourceConfigurationTypeDef
+):
+    pass
+
+
+AwsLogSourceResourceTypeDef = TypedDict(
+    "AwsLogSourceResourceTypeDef",
     {
-        "healthStatus": SourceStatusType,
-        "pathToLogs": str,
+        "sourceName": AwsLogSourceNameType,
+        "sourceVersion": str,
     },
+    total=False,
 )
 
-AutoEnableNewRegionConfigurationTypeDef = TypedDict(
-    "AutoEnableNewRegionConfigurationTypeDef",
+CreateAwsLogSourceResponseTypeDef = TypedDict(
+    "CreateAwsLogSourceResponseTypeDef",
     {
-        "region": RegionType,
-        "sources": Sequence[AwsLogSourceTypeType],
+        "failed": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredCreateAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateAwsLogSourceRequestRequestTypeDef",
+_RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
     },
 )
-_OptionalCreateAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateAwsLogSourceRequestRequestTypeDef",
+_OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef",
     {
-        "enableAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "enableSingleDimension": Sequence[str],
-        "enableTwoDimensions": Mapping[str, Sequence[str]],
+        "exceptionTimeToLive": int,
     },
     total=False,
 )
 
-class CreateAwsLogSourceRequestRequestTypeDef(
-    _RequiredCreateAwsLogSourceRequestRequestTypeDef,
-    _OptionalCreateAwsLogSourceRequestRequestTypeDef,
+
+class CreateDataLakeExceptionSubscriptionRequestRequestTypeDef(
+    _RequiredCreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    _OptionalCreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+CreateSubscriberNotificationResponseTypeDef = TypedDict(
+    "CreateSubscriberNotificationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "subscriberEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateCustomLogSourceRequestRequestTypeDef = TypedDict(
-    "CreateCustomLogSourceRequestRequestTypeDef",
+CustomLogSourceAttributesTypeDef = TypedDict(
+    "CustomLogSourceAttributesTypeDef",
     {
-        "customSourceName": str,
-        "eventClass": OcsfEventClassType,
-        "glueInvocationRoleArn": str,
-        "logProviderAccountId": str,
+        "crawlerArn": str,
+        "databaseArn": str,
+        "tableArn": str,
     },
+    total=False,
 )
 
-CreateDatalakeDelegatedAdminRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeDelegatedAdminRequestRequestTypeDef",
+CustomLogSourceCrawlerConfigurationTypeDef = TypedDict(
+    "CustomLogSourceCrawlerConfigurationTypeDef",
     {
-        "account": str,
+        "roleArn": str,
     },
 )
 
-CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
+CustomLogSourceProviderTypeDef = TypedDict(
+    "CustomLogSourceProviderTypeDef",
     {
-        "notificationEndpoint": str,
-        "subscriptionProtocol": SubscriptionProtocolTypeType,
+        "location": str,
+        "roleArn": str,
     },
+    total=False,
 )
 
-SourceTypeTypeDef = TypedDict(
-    "SourceTypeTypeDef",
+DataLakeEncryptionConfigurationTypeDef = TypedDict(
+    "DataLakeEncryptionConfigurationTypeDef",
     {
-        "awsSourceType": AwsLogSourceTypeType,
-        "customSourceType": str,
+        "kmsKeyId": str,
     },
     total=False,
 )
 
-_RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+DataLakeReplicationConfigurationTypeDef = TypedDict(
+    "DataLakeReplicationConfigurationTypeDef",
     {
-        "subscriptionId": str,
+        "regions": Sequence[str],
+        "roleArn": str,
     },
+    total=False,
 )
-_OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+
+DataLakeExceptionTypeDef = TypedDict(
+    "DataLakeExceptionTypeDef",
     {
-        "createSqs": bool,
-        "httpsApiKeyName": str,
-        "httpsApiKeyValue": str,
-        "httpsMethod": HttpsMethodType,
-        "roleArn": str,
-        "subscriptionEndpoint": str,
+        "exception": str,
+        "region": str,
+        "remediation": str,
+        "timestamp": datetime,
     },
     total=False,
 )
 
-class CreateSubscriptionNotificationConfigurationRequestRequestTypeDef(
-    _RequiredCreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    _OptionalCreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-):
-    pass
+DataLakeLifecycleExpirationTypeDef = TypedDict(
+    "DataLakeLifecycleExpirationTypeDef",
+    {
+        "days": int,
+    },
+    total=False,
+)
 
-_RequiredDeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_RequiredDeleteAwsLogSourceRequestRequestTypeDef",
+DataLakeLifecycleTransitionTypeDef = TypedDict(
+    "DataLakeLifecycleTransitionTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
+        "days": int,
+        "storageClass": str,
     },
+    total=False,
 )
-_OptionalDeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
-    "_OptionalDeleteAwsLogSourceRequestRequestTypeDef",
+
+DataLakeSourceStatusTypeDef = TypedDict(
+    "DataLakeSourceStatusTypeDef",
     {
-        "disableAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "disableSingleDimension": Sequence[str],
-        "disableTwoDimensions": Mapping[str, Sequence[str]],
+        "resource": str,
+        "status": SourceCollectionStatusType,
     },
     total=False,
 )
 
-class DeleteAwsLogSourceRequestRequestTypeDef(
-    _RequiredDeleteAwsLogSourceRequestRequestTypeDef,
-    _OptionalDeleteAwsLogSourceRequestRequestTypeDef,
-):
-    pass
+DataLakeUpdateExceptionTypeDef = TypedDict(
+    "DataLakeUpdateExceptionTypeDef",
+    {
+        "code": str,
+        "reason": str,
+    },
+    total=False,
+)
 
-DeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
-    "DeleteCustomLogSourceRequestRequestTypeDef",
+DeleteAwsLogSourceResponseTypeDef = TypedDict(
+    "DeleteAwsLogSourceResponseTypeDef",
     {
-        "customSourceName": str,
+        "failed": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteDatalakeDelegatedAdminRequestRequestTypeDef = TypedDict(
-    "DeleteDatalakeDelegatedAdminRequestRequestTypeDef",
+_RequiredDeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeleteCustomLogSourceRequestRequestTypeDef",
     {
-        "account": str,
+        "sourceName": str,
     },
 )
+_OptionalDeleteCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeleteCustomLogSourceRequestRequestTypeDef",
+    {
+        "sourceVersion": str,
+    },
+    total=False,
+)
 
-DeleteSubscriberRequestRequestTypeDef = TypedDict(
-    "DeleteSubscriberRequestRequestTypeDef",
+
+class DeleteCustomLogSourceRequestRequestTypeDef(
+    _RequiredDeleteCustomLogSourceRequestRequestTypeDef,
+    _OptionalDeleteCustomLogSourceRequestRequestTypeDef,
+):
+    pass
+
+
+DeleteDataLakeRequestRequestTypeDef = TypedDict(
+    "DeleteDataLakeRequestRequestTypeDef",
     {
-        "id": str,
+        "regions": Sequence[str],
     },
 )
 
-DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef",
+DeleteSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "DeleteSubscriberNotificationRequestRequestTypeDef",
     {
-        "subscriptionId": str,
+        "subscriberId": str,
     },
 )
 
-FailuresTypeDef = TypedDict(
-    "FailuresTypeDef",
+DeleteSubscriberRequestRequestTypeDef = TypedDict(
+    "DeleteSubscriberRequestRequestTypeDef",
     {
-        "exceptionMessage": str,
-        "remediation": str,
-        "timestamp": datetime,
+        "subscriberId": str,
     },
 )
 
-ProtocolAndNotificationEndpointTypeDef = TypedDict(
-    "ProtocolAndNotificationEndpointTypeDef",
+GetDataLakeExceptionSubscriptionResponseTypeDef = TypedDict(
+    "GetDataLakeExceptionSubscriptionResponseTypeDef",
     {
-        "endpoint": str,
-        "protocol": str,
+        "exceptionTimeToLive": int,
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef = TypedDict(
+    "GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "accounts": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-GetDatalakeStatusRequestRequestTypeDef = TypedDict(
-    "GetDatalakeStatusRequestRequestTypeDef",
+GetDataLakeSourcesRequestRequestTypeDef = TypedDict(
+    "GetDataLakeSourcesRequestRequestTypeDef",
     {
-        "accountSet": Sequence[str],
-        "maxAccountResults": int,
+        "accounts": Sequence[str],
+        "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
 GetSubscriberRequestRequestTypeDef = TypedDict(
     "GetSubscriberRequestRequestTypeDef",
     {
-        "id": str,
+        "subscriberId": str,
     },
 )
 
-RetentionSettingTypeDef = TypedDict(
-    "RetentionSettingTypeDef",
+_RequiredHttpsNotificationConfigurationTypeDef = TypedDict(
+    "_RequiredHttpsNotificationConfigurationTypeDef",
+    {
+        "endpoint": str,
+        "targetRoleArn": str,
+    },
+)
+_OptionalHttpsNotificationConfigurationTypeDef = TypedDict(
+    "_OptionalHttpsNotificationConfigurationTypeDef",
     {
-        "retentionPeriod": int,
-        "storageClass": StorageClassType,
+        "authorizationApiKeyName": str,
+        "authorizationApiKeyValue": str,
+        "httpMethod": HttpMethodType,
     },
     total=False,
 )
 
-ListDatalakeExceptionsRequestRequestTypeDef = TypedDict(
-    "ListDatalakeExceptionsRequestRequestTypeDef",
+
+class HttpsNotificationConfigurationTypeDef(
+    _RequiredHttpsNotificationConfigurationTypeDef, _OptionalHttpsNotificationConfigurationTypeDef
+):
+    pass
+
+
+ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef = TypedDict(
+    "ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef",
     {
-        "maxFailures": int,
-        "nextToken": str,
-        "regionSet": Sequence[RegionType],
+        "regions": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListLogSourcesRequestRequestTypeDef = TypedDict(
-    "ListLogSourcesRequestRequestTypeDef",
+ListDataLakeExceptionsRequestRequestTypeDef = TypedDict(
+    "ListDataLakeExceptionsRequestRequestTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
-        "listAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "listSingleDimension": Sequence[str],
-        "listTwoDimensions": Mapping[str, Sequence[str]],
         "maxResults": int,
         "nextToken": str,
+        "regions": Sequence[str],
+    },
+    total=False,
+)
+
+ListDataLakesRequestRequestTypeDef = TypedDict(
+    "ListDataLakesRequestRequestTypeDef",
+    {
+        "regions": Sequence[str],
+    },
+    total=False,
+)
+
+ListSubscribersRequestListSubscribersPaginateTypeDef = TypedDict(
+    "ListSubscribersRequestListSubscribersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSubscribersRequestRequestTypeDef = TypedDict(
     "ListSubscribersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-UpdateDatalakeExceptionsExpiryRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeExceptionsExpiryRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "exceptionMessageExpiry": int,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef",
+RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef = TypedDict(
+    "RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef",
     {
-        "notificationEndpoint": str,
-        "subscriptionProtocol": SubscriptionProtocolTypeType,
+        "accountId": str,
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
     },
 )
 
-_RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+_RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
     {
-        "subscriptionId": str,
+        "notificationEndpoint": str,
+        "subscriptionProtocol": str,
     },
 )
-_OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef",
+_OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef",
     {
-        "createSqs": bool,
-        "httpsApiKeyName": str,
-        "httpsApiKeyValue": str,
-        "httpsMethod": HttpsMethodType,
-        "roleArn": str,
-        "subscriptionEndpoint": str,
+        "exceptionTimeToLive": int,
     },
     total=False,
 )
 
-class UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef(
-    _RequiredUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    _OptionalUpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
+
+class UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef(
+    _RequiredUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    _OptionalUpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
 ):
     pass
 
-_RequiredAccountSourcesTypeDef = TypedDict(
-    "_RequiredAccountSourcesTypeDef",
+
+UpdateSubscriberNotificationResponseTypeDef = TypedDict(
+    "UpdateSubscriberNotificationResponseTypeDef",
     {
-        "account": str,
-        "sourceType": str,
+        "subscriberEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAwsLogSourceRequestRequestTypeDef = TypedDict(
+    "CreateAwsLogSourceRequestRequestTypeDef",
+    {
+        "sources": Sequence[AwsLogSourceConfigurationTypeDef],
     },
 )
-_OptionalAccountSourcesTypeDef = TypedDict(
-    "_OptionalAccountSourcesTypeDef",
+
+DeleteAwsLogSourceRequestRequestTypeDef = TypedDict(
+    "DeleteAwsLogSourceRequestRequestTypeDef",
     {
-        "eventClass": OcsfEventClassType,
-        "logsStatus": List[LogsStatusTypeDef],
+        "sources": Sequence[AwsLogSourceConfigurationTypeDef],
+    },
+)
+
+DataLakeAutoEnableNewAccountConfigurationTypeDef = TypedDict(
+    "DataLakeAutoEnableNewAccountConfigurationTypeDef",
+    {
+        "region": str,
+        "sources": Sequence[AwsLogSourceResourceTypeDef],
+    },
+)
+
+CustomLogSourceConfigurationTypeDef = TypedDict(
+    "CustomLogSourceConfigurationTypeDef",
+    {
+        "crawlerConfiguration": CustomLogSourceCrawlerConfigurationTypeDef,
+        "providerIdentity": AwsIdentityTypeDef,
+    },
+)
+
+CustomLogSourceResourceTypeDef = TypedDict(
+    "CustomLogSourceResourceTypeDef",
+    {
+        "attributes": CustomLogSourceAttributesTypeDef,
+        "provider": CustomLogSourceProviderTypeDef,
+        "sourceName": str,
+        "sourceVersion": str,
     },
     total=False,
 )
 
-class AccountSourcesTypeDef(_RequiredAccountSourcesTypeDef, _OptionalAccountSourcesTypeDef):
-    pass
+ListDataLakeExceptionsResponseTypeDef = TypedDict(
+    "ListDataLakeExceptionsResponseTypeDef",
+    {
+        "exceptions": List[DataLakeExceptionTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-CreateDatalakeAutoEnableRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeAutoEnableRequestRequestTypeDef",
+DataLakeLifecycleConfigurationTypeDef = TypedDict(
+    "DataLakeLifecycleConfigurationTypeDef",
     {
-        "configurationForNewAccounts": Sequence[AutoEnableNewRegionConfigurationTypeDef],
+        "expiration": DataLakeLifecycleExpirationTypeDef,
+        "transitions": Sequence[DataLakeLifecycleTransitionTypeDef],
     },
+    total=False,
 )
 
-DeleteDatalakeAutoEnableRequestRequestTypeDef = TypedDict(
-    "DeleteDatalakeAutoEnableRequestRequestTypeDef",
+DataLakeSourceTypeDef = TypedDict(
+    "DataLakeSourceTypeDef",
     {
-        "removeFromConfigurationForNewAccounts": Sequence[AutoEnableNewRegionConfigurationTypeDef],
+        "account": str,
+        "eventClasses": List[str],
+        "sourceName": str,
+        "sourceStatuses": List[DataLakeSourceStatusTypeDef],
     },
+    total=False,
 )
 
-CreateAwsLogSourceResponseTypeDef = TypedDict(
-    "CreateAwsLogSourceResponseTypeDef",
+DataLakeUpdateStatusTypeDef = TypedDict(
+    "DataLakeUpdateStatusTypeDef",
     {
-        "failed": List[str],
-        "processing": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "exception": DataLakeUpdateExceptionTypeDef,
+        "requestId": str,
+        "status": DataLakeStatusType,
     },
+    total=False,
 )
 
-CreateCustomLogSourceResponseTypeDef = TypedDict(
-    "CreateCustomLogSourceResponseTypeDef",
+NotificationConfigurationTypeDef = TypedDict(
+    "NotificationConfigurationTypeDef",
     {
-        "customDataLocation": str,
-        "glueCrawlerName": str,
-        "glueDatabaseName": str,
-        "glueTableName": str,
-        "logProviderAccessRoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "httpsNotificationConfiguration": HttpsNotificationConfigurationTypeDef,
+        "sqsNotificationConfiguration": Mapping[str, Any],
     },
+    total=False,
 )
 
-CreateSubscriberResponseTypeDef = TypedDict(
-    "CreateSubscriberResponseTypeDef",
+CreateDataLakeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "CreateDataLakeOrganizationConfigurationRequestRequestTypeDef",
     {
-        "roleArn": str,
-        "s3BucketArn": str,
-        "snsArn": str,
-        "subscriptionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef],
     },
 )
 
-CreateSubscriptionNotificationConfigurationResponseTypeDef = TypedDict(
-    "CreateSubscriptionNotificationConfigurationResponseTypeDef",
+DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef",
     {
-        "queueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": Sequence[DataLakeAutoEnableNewAccountConfigurationTypeDef],
     },
 )
 
-DeleteAwsLogSourceResponseTypeDef = TypedDict(
-    "DeleteAwsLogSourceResponseTypeDef",
+GetDataLakeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "GetDataLakeOrganizationConfigurationResponseTypeDef",
     {
-        "failed": List[str],
-        "processing": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "autoEnableNewAccount": List[DataLakeAutoEnableNewAccountConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteCustomLogSourceResponseTypeDef = TypedDict(
-    "DeleteCustomLogSourceResponseTypeDef",
+_RequiredCreateCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateCustomLogSourceRequestRequestTypeDef",
+    {
+        "sourceName": str,
+    },
+)
+_OptionalCreateCustomLogSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateCustomLogSourceRequestRequestTypeDef",
     {
-        "customDataLocation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "configuration": CustomLogSourceConfigurationTypeDef,
+        "eventClasses": Sequence[str],
+        "sourceVersion": str,
     },
+    total=False,
 )
 
-DeleteDatalakeExceptionsSubscriptionResponseTypeDef = TypedDict(
-    "DeleteDatalakeExceptionsSubscriptionResponseTypeDef",
+
+class CreateCustomLogSourceRequestRequestTypeDef(
+    _RequiredCreateCustomLogSourceRequestRequestTypeDef,
+    _OptionalCreateCustomLogSourceRequestRequestTypeDef,
+):
+    pass
+
+
+CreateCustomLogSourceResponseTypeDef = TypedDict(
+    "CreateCustomLogSourceResponseTypeDef",
     {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "source": CustomLogSourceResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetDatalakeAutoEnableResponseTypeDef = TypedDict(
-    "GetDatalakeAutoEnableResponseTypeDef",
+LogSourceResourceTypeDef = TypedDict(
+    "LogSourceResourceTypeDef",
     {
-        "autoEnableNewAccounts": List[AutoEnableNewRegionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "awsLogSource": AwsLogSourceResourceTypeDef,
+        "customLogSource": CustomLogSourceResourceTypeDef,
     },
+    total=False,
 )
 
-GetDatalakeExceptionsExpiryResponseTypeDef = TypedDict(
-    "GetDatalakeExceptionsExpiryResponseTypeDef",
+_RequiredDataLakeConfigurationTypeDef = TypedDict(
+    "_RequiredDataLakeConfigurationTypeDef",
     {
-        "exceptionMessageExpiry": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "region": str,
     },
 )
+_OptionalDataLakeConfigurationTypeDef = TypedDict(
+    "_OptionalDataLakeConfigurationTypeDef",
+    {
+        "encryptionConfiguration": DataLakeEncryptionConfigurationTypeDef,
+        "lifecycleConfiguration": DataLakeLifecycleConfigurationTypeDef,
+        "replicationConfiguration": DataLakeReplicationConfigurationTypeDef,
+    },
+    total=False,
+)
 
-ListLogSourcesResponseTypeDef = TypedDict(
-    "ListLogSourcesResponseTypeDef",
+
+class DataLakeConfigurationTypeDef(
+    _RequiredDataLakeConfigurationTypeDef, _OptionalDataLakeConfigurationTypeDef
+):
+    pass
+
+
+GetDataLakeSourcesResponseTypeDef = TypedDict(
+    "GetDataLakeSourcesResponseTypeDef",
     {
+        "dataLakeArn": str,
+        "dataLakeSources": List[DataLakeSourceTypeDef],
         "nextToken": str,
-        "regionSourceTypesAccountsList": List[Dict[str, Dict[str, List[str]]]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDataLakeResourceTypeDef = TypedDict(
+    "_RequiredDataLakeResourceTypeDef",
+    {
+        "dataLakeArn": str,
+        "region": str,
+    },
+)
+_OptionalDataLakeResourceTypeDef = TypedDict(
+    "_OptionalDataLakeResourceTypeDef",
+    {
+        "createStatus": DataLakeStatusType,
+        "encryptionConfiguration": DataLakeEncryptionConfigurationTypeDef,
+        "lifecycleConfiguration": DataLakeLifecycleConfigurationTypeDef,
+        "replicationConfiguration": DataLakeReplicationConfigurationTypeDef,
+        "s3BucketArn": str,
+        "updateStatus": DataLakeUpdateStatusTypeDef,
+    },
+    total=False,
+)
+
+
+class DataLakeResourceTypeDef(_RequiredDataLakeResourceTypeDef, _OptionalDataLakeResourceTypeDef):
+    pass
+
+
+CreateSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "CreateSubscriberNotificationRequestRequestTypeDef",
+    {
+        "configuration": NotificationConfigurationTypeDef,
+        "subscriberId": str,
     },
 )
 
-UpdateSubscriptionNotificationConfigurationResponseTypeDef = TypedDict(
-    "UpdateSubscriptionNotificationConfigurationResponseTypeDef",
+UpdateSubscriberNotificationRequestRequestTypeDef = TypedDict(
+    "UpdateSubscriberNotificationRequestRequestTypeDef",
     {
-        "queueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "configuration": NotificationConfigurationTypeDef,
+        "subscriberId": str,
     },
 )
 
 _RequiredCreateSubscriberRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSubscriberRequestRequestTypeDef",
     {
-        "accountId": str,
-        "externalId": str,
-        "sourceTypes": Sequence[SourceTypeTypeDef],
+        "sources": Sequence[LogSourceResourceTypeDef],
+        "subscriberIdentity": AwsIdentityTypeDef,
         "subscriberName": str,
     },
 )
 _OptionalCreateSubscriberRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSubscriberRequestRequestTypeDef",
     {
         "accessTypes": Sequence[AccessTypeType],
         "subscriberDescription": str,
     },
     total=False,
 )
 
+
 class CreateSubscriberRequestRequestTypeDef(
     _RequiredCreateSubscriberRequestRequestTypeDef, _OptionalCreateSubscriberRequestRequestTypeDef
 ):
     pass
 
+
+ListLogSourcesRequestListLogSourcesPaginateTypeDef = TypedDict(
+    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+    {
+        "accounts": Sequence[str],
+        "regions": Sequence[str],
+        "sources": Sequence[LogSourceResourceTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListLogSourcesRequestRequestTypeDef = TypedDict(
+    "ListLogSourcesRequestRequestTypeDef",
+    {
+        "accounts": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+        "regions": Sequence[str],
+        "sources": Sequence[LogSourceResourceTypeDef],
+    },
+    total=False,
+)
+
+LogSourceTypeDef = TypedDict(
+    "LogSourceTypeDef",
+    {
+        "account": str,
+        "region": str,
+        "sources": List[LogSourceResourceTypeDef],
+    },
+    total=False,
+)
+
 _RequiredSubscriberResourceTypeDef = TypedDict(
     "_RequiredSubscriberResourceTypeDef",
     {
-        "accountId": str,
-        "sourceTypes": List[SourceTypeTypeDef],
-        "subscriptionId": str,
+        "sources": List[LogSourceResourceTypeDef],
+        "subscriberArn": str,
+        "subscriberId": str,
+        "subscriberIdentity": AwsIdentityTypeDef,
+        "subscriberName": str,
     },
 )
 _OptionalSubscriberResourceTypeDef = TypedDict(
     "_OptionalSubscriberResourceTypeDef",
     {
         "accessTypes": List[AccessTypeType],
         "createdAt": datetime,
-        "externalId": str,
+        "resourceShareArn": str,
+        "resourceShareName": str,
         "roleArn": str,
         "s3BucketArn": str,
-        "snsArn": str,
         "subscriberDescription": str,
-        "subscriberName": str,
-        "subscriptionEndpoint": str,
-        "subscriptionProtocol": EndpointProtocolType,
-        "subscriptionStatus": SubscriptionStatusType,
+        "subscriberEndpoint": str,
+        "subscriberStatus": SubscriberStatusType,
         "updatedAt": datetime,
     },
     total=False,
 )
 
+
 class SubscriberResourceTypeDef(
     _RequiredSubscriberResourceTypeDef, _OptionalSubscriberResourceTypeDef
 ):
     pass
 
+
 _RequiredUpdateSubscriberRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSubscriberRequestRequestTypeDef",
     {
-        "id": str,
-        "sourceTypes": Sequence[SourceTypeTypeDef],
+        "subscriberId": str,
     },
 )
 _OptionalUpdateSubscriberRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSubscriberRequestRequestTypeDef",
     {
-        "externalId": str,
+        "sources": Sequence[LogSourceResourceTypeDef],
         "subscriberDescription": str,
+        "subscriberIdentity": AwsIdentityTypeDef,
         "subscriberName": str,
     },
     total=False,
 )
 
+
 class UpdateSubscriberRequestRequestTypeDef(
     _RequiredUpdateSubscriberRequestRequestTypeDef, _OptionalUpdateSubscriberRequestRequestTypeDef
 ):
     pass
 
-FailuresResponseTypeDef = TypedDict(
-    "FailuresResponseTypeDef",
-    {
-        "failures": List[FailuresTypeDef],
-        "region": str,
-    },
-    total=False,
-)
-
-GetDatalakeExceptionsSubscriptionResponseTypeDef = TypedDict(
-    "GetDatalakeExceptionsSubscriptionResponseTypeDef",
-    {
-        "protocolAndNotificationEndpoint": ProtocolAndNotificationEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef = TypedDict(
-    "GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef",
+CreateDataLakeRequestRequestTypeDef = TypedDict(
+    "CreateDataLakeRequestRequestTypeDef",
     {
-        "accountSet": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "configurations": Sequence[DataLakeConfigurationTypeDef],
+        "metaStoreManagerRoleArn": str,
     },
-    total=False,
 )
 
-ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef = TypedDict(
-    "ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef",
+UpdateDataLakeRequestRequestTypeDef = TypedDict(
+    "UpdateDataLakeRequestRequestTypeDef",
     {
-        "regionSet": Sequence[RegionType],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "configurations": Sequence[DataLakeConfigurationTypeDef],
     },
-    total=False,
 )
 
-ListLogSourcesRequestListLogSourcesPaginateTypeDef = TypedDict(
-    "ListLogSourcesRequestListLogSourcesPaginateTypeDef",
+CreateDataLakeResponseTypeDef = TypedDict(
+    "CreateDataLakeResponseTypeDef",
     {
-        "inputOrder": Sequence[DimensionType],
-        "listAllDimensions": Mapping[str, Mapping[str, Sequence[str]]],
-        "listSingleDimension": Sequence[str],
-        "listTwoDimensions": Mapping[str, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListSubscribersRequestListSubscribersPaginateTypeDef = TypedDict(
-    "ListSubscribersRequestListSubscribersPaginateTypeDef",
+ListDataLakesResponseTypeDef = TypedDict(
+    "ListDataLakesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-LakeConfigurationRequestTypeDef = TypedDict(
-    "LakeConfigurationRequestTypeDef",
+UpdateDataLakeResponseTypeDef = TypedDict(
+    "UpdateDataLakeResponseTypeDef",
     {
-        "encryptionKey": str,
-        "replicationDestinationRegions": Sequence[RegionType],
-        "replicationRoleArn": str,
-        "retentionSettings": Sequence[RetentionSettingTypeDef],
-        "tagsMap": Mapping[str, str],
+        "dataLakes": List[DataLakeResourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-LakeConfigurationResponseTypeDef = TypedDict(
-    "LakeConfigurationResponseTypeDef",
+ListLogSourcesResponseTypeDef = TypedDict(
+    "ListLogSourcesResponseTypeDef",
     {
-        "encryptionKey": str,
-        "replicationDestinationRegions": List[RegionType],
-        "replicationRoleArn": str,
-        "retentionSettings": List[RetentionSettingTypeDef],
-        "s3BucketArn": str,
-        "status": settingsStatusType,
-        "tagsMap": Dict[str, str],
+        "nextToken": str,
+        "sources": List[LogSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-GetDatalakeStatusResponseTypeDef = TypedDict(
-    "GetDatalakeStatusResponseTypeDef",
+CreateSubscriberResponseTypeDef = TypedDict(
+    "CreateSubscriberResponseTypeDef",
     {
-        "accountSourcesList": List[AccountSourcesTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "subscriber": SubscriberResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSubscriberResponseTypeDef = TypedDict(
     "GetSubscriberResponseTypeDef",
     {
         "subscriber": SubscriberResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSubscribersResponseTypeDef = TypedDict(
     "ListSubscribersResponseTypeDef",
     {
         "nextToken": str,
         "subscribers": List[SubscriberResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubscriberResponseTypeDef = TypedDict(
     "UpdateSubscriberResponseTypeDef",
     {
         "subscriber": SubscriberResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatalakeExceptionsResponseTypeDef = TypedDict(
-    "ListDatalakeExceptionsResponseTypeDef",
-    {
-        "nextToken": str,
-        "nonRetryableFailures": List[FailuresResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatalakeRequestRequestTypeDef = TypedDict(
-    "CreateDatalakeRequestRequestTypeDef",
-    {
-        "configurations": Mapping[RegionType, LakeConfigurationRequestTypeDef],
-        "enableAll": bool,
-        "metaStoreManagerRoleArn": str,
-        "regions": Sequence[RegionType],
-    },
-    total=False,
-)
-
-UpdateDatalakeRequestRequestTypeDef = TypedDict(
-    "UpdateDatalakeRequestRequestTypeDef",
-    {
-        "configurations": Mapping[RegionType, LakeConfigurationRequestTypeDef],
-    },
-)
-
-GetDatalakeResponseTypeDef = TypedDict(
-    "GetDatalakeResponseTypeDef",
-    {
-        "configurations": Dict[RegionType, LakeConfigurationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/PKG-INFO` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-securitylake
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecurityLake 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecurityLake 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-securitylake"></a>
 
 # types-aiobotocore-securitylake
 
 [![PyPI - types-aiobotocore-securitylake](https://img.shields.io/pypi/v/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securitylake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securitylake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securitylake?color=blue)](https://pypistats.org/packages/types-aiobotocore-securitylake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
+[aiobotocore.SecurityLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securitylake.html#SecurityLake)
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
 [types-aiobotocore-securitylake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securitylake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,31 +273,31 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_securitylake import SecurityLakeClient
 from types_aiobotocore_securitylake.paginator import (
-    GetDatalakeStatusPaginator,
-    ListDatalakeExceptionsPaginator,
+    GetDataLakeSourcesPaginator,
+    ListDataLakeExceptionsPaginator,
     ListLogSourcesPaginator,
     ListSubscribersPaginator,
 )
 
 session = get_session()
 async with session.create_client("securitylake") as client:
     client: SecurityLakeClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
-    get_datalake_status_paginator: GetDatalakeStatusPaginator = client.get_paginator(
-        "get_datalake_status"
+    get_data_lake_sources_paginator: GetDataLakeSourcesPaginator = client.get_paginator(
+        "get_data_lake_sources"
     )
-    list_datalake_exceptions_paginator: ListDatalakeExceptionsPaginator = client.get_paginator(
-        "list_datalake_exceptions"
+    list_data_lake_exceptions_paginator: ListDataLakeExceptionsPaginator = client.get_paginator(
+        "list_data_lake_exceptions"
     )
     list_log_sources_paginator: ListLogSourcesPaginator = client.get_paginator("list_log_sources")
     list_subscribers_paginator: ListSubscribersPaginator = client.get_paginator("list_subscribers")
 ```
 
 <a id="literals"></a>
 
@@ -305,29 +305,23 @@
 
 `types_aiobotocore_securitylake.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securitylake.literals import (
     AccessTypeType,
-    AwsLogSourceTypeType,
-    DimensionType,
-    EndpointProtocolType,
-    GetDatalakeStatusPaginatorName,
-    HttpsMethodType,
-    ListDatalakeExceptionsPaginatorName,
+    AwsLogSourceNameType,
+    DataLakeStatusType,
+    GetDataLakeSourcesPaginatorName,
+    HttpMethodType,
+    ListDataLakeExceptionsPaginatorName,
     ListLogSourcesPaginatorName,
     ListSubscribersPaginatorName,
-    OcsfEventClassType,
-    RegionType,
-    SourceStatusType,
-    StorageClassType,
-    SubscriptionProtocolTypeType,
-    SubscriptionStatusType,
-    settingsStatusType,
+    SourceCollectionStatusType,
+    SubscriberStatusType,
     SecurityLakeServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -341,116 +335,130 @@
 ### Typed dictionaries
 
 `types_aiobotocore_securitylake.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_securitylake.type_defs import (
-    LogsStatusTypeDef,
-    AutoEnableNewRegionConfigurationTypeDef,
-    CreateAwsLogSourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    CreateCustomLogSourceRequestRequestTypeDef,
-    CreateDatalakeDelegatedAdminRequestRequestTypeDef,
-    CreateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    SourceTypeTypeDef,
-    CreateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    DeleteAwsLogSourceRequestRequestTypeDef,
+    AwsIdentityTypeDef,
+    AwsLogSourceConfigurationTypeDef,
+    AwsLogSourceResourceTypeDef,
+    CreateAwsLogSourceResponseTypeDef,
+    CreateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    CreateSubscriberNotificationResponseTypeDef,
+    CustomLogSourceAttributesTypeDef,
+    CustomLogSourceCrawlerConfigurationTypeDef,
+    CustomLogSourceProviderTypeDef,
+    DataLakeEncryptionConfigurationTypeDef,
+    DataLakeReplicationConfigurationTypeDef,
+    DataLakeExceptionTypeDef,
+    DataLakeLifecycleExpirationTypeDef,
+    DataLakeLifecycleTransitionTypeDef,
+    DataLakeSourceStatusTypeDef,
+    DataLakeUpdateExceptionTypeDef,
+    DeleteAwsLogSourceResponseTypeDef,
     DeleteCustomLogSourceRequestRequestTypeDef,
-    DeleteDatalakeDelegatedAdminRequestRequestTypeDef,
+    DeleteDataLakeRequestRequestTypeDef,
+    DeleteSubscriberNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
-    DeleteSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    FailuresTypeDef,
-    ProtocolAndNotificationEndpointTypeDef,
-    PaginatorConfigTypeDef,
-    GetDatalakeStatusRequestRequestTypeDef,
+    GetDataLakeExceptionSubscriptionResponseTypeDef,
+    GetDataLakeSourcesRequestGetDataLakeSourcesPaginateTypeDef,
+    GetDataLakeSourcesRequestRequestTypeDef,
     GetSubscriberRequestRequestTypeDef,
-    RetentionSettingTypeDef,
-    ListDatalakeExceptionsRequestRequestTypeDef,
-    ListLogSourcesRequestRequestTypeDef,
+    HttpsNotificationConfigurationTypeDef,
+    ListDataLakeExceptionsRequestListDataLakeExceptionsPaginateTypeDef,
+    ListDataLakeExceptionsRequestRequestTypeDef,
+    ListDataLakesRequestRequestTypeDef,
+    ListSubscribersRequestListSubscribersPaginateTypeDef,
     ListSubscribersRequestRequestTypeDef,
-    UpdateDatalakeExceptionsExpiryRequestRequestTypeDef,
-    UpdateDatalakeExceptionsSubscriptionRequestRequestTypeDef,
-    UpdateSubscriptionNotificationConfigurationRequestRequestTypeDef,
-    AccountSourcesTypeDef,
-    CreateDatalakeAutoEnableRequestRequestTypeDef,
-    DeleteDatalakeAutoEnableRequestRequestTypeDef,
-    CreateAwsLogSourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterDataLakeDelegatedAdministratorRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateDataLakeExceptionSubscriptionRequestRequestTypeDef,
+    UpdateSubscriberNotificationResponseTypeDef,
+    CreateAwsLogSourceRequestRequestTypeDef,
+    DeleteAwsLogSourceRequestRequestTypeDef,
+    DataLakeAutoEnableNewAccountConfigurationTypeDef,
+    CustomLogSourceConfigurationTypeDef,
+    CustomLogSourceResourceTypeDef,
+    ListDataLakeExceptionsResponseTypeDef,
+    DataLakeLifecycleConfigurationTypeDef,
+    DataLakeSourceTypeDef,
+    DataLakeUpdateStatusTypeDef,
+    NotificationConfigurationTypeDef,
+    CreateDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    DeleteDataLakeOrganizationConfigurationRequestRequestTypeDef,
+    GetDataLakeOrganizationConfigurationResponseTypeDef,
+    CreateCustomLogSourceRequestRequestTypeDef,
     CreateCustomLogSourceResponseTypeDef,
-    CreateSubscriberResponseTypeDef,
-    CreateSubscriptionNotificationConfigurationResponseTypeDef,
-    DeleteAwsLogSourceResponseTypeDef,
-    DeleteCustomLogSourceResponseTypeDef,
-    DeleteDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeAutoEnableResponseTypeDef,
-    GetDatalakeExceptionsExpiryResponseTypeDef,
-    ListLogSourcesResponseTypeDef,
-    UpdateSubscriptionNotificationConfigurationResponseTypeDef,
+    LogSourceResourceTypeDef,
+    DataLakeConfigurationTypeDef,
+    GetDataLakeSourcesResponseTypeDef,
+    DataLakeResourceTypeDef,
+    CreateSubscriberNotificationRequestRequestTypeDef,
+    UpdateSubscriberNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
+    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
+    ListLogSourcesRequestRequestTypeDef,
+    LogSourceTypeDef,
     SubscriberResourceTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
-    FailuresResponseTypeDef,
-    GetDatalakeExceptionsSubscriptionResponseTypeDef,
-    GetDatalakeStatusRequestGetDatalakeStatusPaginateTypeDef,
-    ListDatalakeExceptionsRequestListDatalakeExceptionsPaginateTypeDef,
-    ListLogSourcesRequestListLogSourcesPaginateTypeDef,
-    ListSubscribersRequestListSubscribersPaginateTypeDef,
-    LakeConfigurationRequestTypeDef,
-    LakeConfigurationResponseTypeDef,
-    GetDatalakeStatusResponseTypeDef,
+    CreateDataLakeRequestRequestTypeDef,
+    UpdateDataLakeRequestRequestTypeDef,
+    CreateDataLakeResponseTypeDef,
+    ListDataLakesResponseTypeDef,
+    UpdateDataLakeResponseTypeDef,
+    ListLogSourcesResponseTypeDef,
+    CreateSubscriberResponseTypeDef,
     GetSubscriberResponseTypeDef,
     ListSubscribersResponseTypeDef,
     UpdateSubscriberResponseTypeDef,
-    ListDatalakeExceptionsResponseTypeDef,
-    CreateDatalakeRequestRequestTypeDef,
-    UpdateDatalakeRequestRequestTypeDef,
-    GetDatalakeResponseTypeDef,
 )
 
 
-def get_structure() -> LogsStatusTypeDef:
+def get_structure() -> AwsIdentityTypeDef:
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

### Comparing `types-aiobotocore-securitylake-2.5.0.post1/types_aiobotocore_securitylake.egg-info/SOURCES.txt` & `types-aiobotocore-securitylake-2.5.1/types_aiobotocore_securitylake.egg-info/SOURCES.txt`

 * *Files identical despite different names*

