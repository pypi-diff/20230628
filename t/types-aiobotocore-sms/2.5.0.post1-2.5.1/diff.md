# Comparing `tmp/types-aiobotocore-sms-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sms-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sms-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-sms-2.5.1.tar", last modified: Wed Jun 28 01:44:12 2023, max compression
```

## Comparing `types-aiobotocore-sms-2.5.0.post1.tar` & `types-aiobotocore-sms-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.259636 types-aiobotocore-sms-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17146 2023-03-11 12:27:21.259636 types-aiobotocore-sms-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15591 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:21.259636 types-aiobotocore-sms-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.255636 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/
--rw-r--r--   0 runner    (1001) docker     (123)     1385 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1384 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27758 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27709 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11133 2023-03-11 12:24:18.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11131 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6374 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6366 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    28482 2023-03-11 12:24:18.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    28465 2023-03-11 12:24:18.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:17.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.259636 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17146 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:21.000000 types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.298217 types-aiobotocore-sms-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17134 2023-06-28 01:44:12.298217 types-aiobotocore-sms-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15585 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:12.298217 types-aiobotocore-sms-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.298217 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/
+-rw-r--r--   0 runner    (1001) docker     (123)     1385 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1384 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27758 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27709 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11342 2023-06-28 01:41:06.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11340 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6264 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6257 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    28524 2023-06-28 01:41:06.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28507 2023-06-28 01:41:06.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:05.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.298217 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17134 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:12.000000 types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sms-2.5.0.post1/LICENSE` & `types-aiobotocore-sms-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sms-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sms-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sms"></a>
 
 # types-aiobotocore-sms
 
 [![PyPI - types-aiobotocore-sms](https://img.shields.io/pypi/v/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sms?color=blue)](https://pypistats.org/packages/types-aiobotocore-sms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
+[aiobotocore.SMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
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
 [types-aiobotocore-sms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -352,60 +352,60 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sms.type_defs import (
     LaunchDetailsTypeDef,
     ConnectorTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateReplicationJobRequestRequestTypeDef,
+    CreateReplicationJobResponseTypeDef,
     DeleteAppLaunchConfigurationRequestRequestTypeDef,
     DeleteAppReplicationConfigurationRequestRequestTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteAppValidationConfigurationRequestRequestTypeDef,
     DeleteReplicationJobRequestRequestTypeDef,
     DisassociateConnectorRequestRequestTypeDef,
     GenerateChangeSetRequestRequestTypeDef,
     S3LocationTypeDef,
     GenerateTemplateRequestRequestTypeDef,
     GetAppLaunchConfigurationRequestRequestTypeDef,
     GetAppReplicationConfigurationRequestRequestTypeDef,
     GetAppRequestRequestTypeDef,
     GetAppValidationConfigurationRequestRequestTypeDef,
     GetAppValidationOutputRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConnectorsRequestGetConnectorsPaginateTypeDef,
     GetConnectorsRequestRequestTypeDef,
+    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
     GetReplicationJobsRequestRequestTypeDef,
+    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
     GetReplicationRunsRequestRequestTypeDef,
     VmServerAddressTypeDef,
     ImportAppCatalogRequestRequestTypeDef,
     LaunchAppRequestRequestTypeDef,
+    ListAppsRequestListAppsPaginateTypeDef,
     ListAppsRequestRequestTypeDef,
     NotificationContextTypeDef,
+    PaginatorConfigTypeDef,
     ReplicationRunStageDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ServerReplicationParametersTypeDef,
     StartAppReplicationRequestRequestTypeDef,
     StartOnDemandAppReplicationRequestRequestTypeDef,
     StartOnDemandReplicationRunRequestRequestTypeDef,
+    StartOnDemandReplicationRunResponseTypeDef,
     StopAppReplicationRequestRequestTypeDef,
     TerminateAppRequestRequestTypeDef,
     UpdateReplicationJobRequestRequestTypeDef,
     AppSummaryTypeDef,
-    CreateReplicationJobResponseTypeDef,
     GetConnectorsResponseTypeDef,
-    StartOnDemandReplicationRunResponseTypeDef,
     GenerateChangeSetResponseTypeDef,
     GenerateTemplateResponseTypeDef,
     SSMOutputTypeDef,
     SourceTypeDef,
     UserDataTypeDef,
-    GetConnectorsRequestGetConnectorsPaginateTypeDef,
-    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
-    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-    ListAppsRequestListAppsPaginateTypeDef,
     GetServersRequestGetServersPaginateTypeDef,
     GetServersRequestRequestTypeDef,
     VmServerTypeDef,
     NotifyAppValidationOutputRequestRequestTypeDef,
     ReplicationRunTypeDef,
     ListAppsResponseTypeDef,
     AppValidationOutputTypeDef,
@@ -448,43 +448,43 @@
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/README.md` & `types-aiobotocore-sms-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sms"></a>
 
 # types-aiobotocore-sms
 
 [![PyPI - types-aiobotocore-sms](https://img.shields.io/pypi/v/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sms?color=blue)](https://pypistats.org/packages/types-aiobotocore-sms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
+[aiobotocore.SMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
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
 [types-aiobotocore-sms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,60 +319,60 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sms.type_defs import (
     LaunchDetailsTypeDef,
     ConnectorTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateReplicationJobRequestRequestTypeDef,
+    CreateReplicationJobResponseTypeDef,
     DeleteAppLaunchConfigurationRequestRequestTypeDef,
     DeleteAppReplicationConfigurationRequestRequestTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteAppValidationConfigurationRequestRequestTypeDef,
     DeleteReplicationJobRequestRequestTypeDef,
     DisassociateConnectorRequestRequestTypeDef,
     GenerateChangeSetRequestRequestTypeDef,
     S3LocationTypeDef,
     GenerateTemplateRequestRequestTypeDef,
     GetAppLaunchConfigurationRequestRequestTypeDef,
     GetAppReplicationConfigurationRequestRequestTypeDef,
     GetAppRequestRequestTypeDef,
     GetAppValidationConfigurationRequestRequestTypeDef,
     GetAppValidationOutputRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConnectorsRequestGetConnectorsPaginateTypeDef,
     GetConnectorsRequestRequestTypeDef,
+    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
     GetReplicationJobsRequestRequestTypeDef,
+    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
     GetReplicationRunsRequestRequestTypeDef,
     VmServerAddressTypeDef,
     ImportAppCatalogRequestRequestTypeDef,
     LaunchAppRequestRequestTypeDef,
+    ListAppsRequestListAppsPaginateTypeDef,
     ListAppsRequestRequestTypeDef,
     NotificationContextTypeDef,
+    PaginatorConfigTypeDef,
     ReplicationRunStageDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ServerReplicationParametersTypeDef,
     StartAppReplicationRequestRequestTypeDef,
     StartOnDemandAppReplicationRequestRequestTypeDef,
     StartOnDemandReplicationRunRequestRequestTypeDef,
+    StartOnDemandReplicationRunResponseTypeDef,
     StopAppReplicationRequestRequestTypeDef,
     TerminateAppRequestRequestTypeDef,
     UpdateReplicationJobRequestRequestTypeDef,
     AppSummaryTypeDef,
-    CreateReplicationJobResponseTypeDef,
     GetConnectorsResponseTypeDef,
-    StartOnDemandReplicationRunResponseTypeDef,
     GenerateChangeSetResponseTypeDef,
     GenerateTemplateResponseTypeDef,
     SSMOutputTypeDef,
     SourceTypeDef,
     UserDataTypeDef,
-    GetConnectorsRequestGetConnectorsPaginateTypeDef,
-    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
-    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-    ListAppsRequestListAppsPaginateTypeDef,
     GetServersRequestGetServersPaginateTypeDef,
     GetServersRequestRequestTypeDef,
     VmServerTypeDef,
     NotifyAppValidationOutputRequestRequestTypeDef,
     ReplicationRunTypeDef,
     ListAppsResponseTypeDef,
     AppValidationOutputTypeDef,
@@ -415,43 +415,43 @@
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/setup.py` & `types-aiobotocore-sms-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sms.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sms",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sms"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SMS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SMS 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/",
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__init__.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__init__.pyi` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/__main__.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SMS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SMS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS\nOther"
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/client.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/client.pyi` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/literals.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/literals.pyi`

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
     "AppLaunchConfigurationStatusType",
     "AppLaunchStatusType",
     "AppReplicationConfigurationStatusType",
     "AppReplicationStatusType",
     "AppStatusType",
     "AppValidationStrategyType",
@@ -47,15 +46,14 @@
     "SMSServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 AppLaunchConfigurationStatusType = Literal["CONFIGURED", "NOT_CONFIGURED"]
 AppLaunchStatusType = Literal[
     "CONFIGURATION_INVALID",
     "CONFIGURATION_IN_PROGRESS",
     "DELTA_LAUNCH_FAILED",
     "DELTA_LAUNCH_IN_PROGRESS",
     "LAUNCHED",
@@ -183,14 +181,15 @@
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
@@ -269,14 +268,15 @@
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
@@ -287,14 +287,15 @@
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
@@ -330,14 +331,15 @@
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
@@ -356,16 +358,19 @@
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
@@ -449,15 +454,17 @@
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/literals.pyi` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AppLaunchConfigurationStatusType",
     "AppLaunchStatusType",
     "AppReplicationConfigurationStatusType",
     "AppReplicationStatusType",
     "AppStatusType",
     "AppValidationStrategyType",
@@ -46,14 +47,15 @@
     "SMSServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 AppLaunchConfigurationStatusType = Literal["CONFIGURED", "NOT_CONFIGURED"]
 AppLaunchStatusType = Literal[
     "CONFIGURATION_INVALID",
     "CONFIGURATION_IN_PROGRESS",
     "DELTA_LAUNCH_FAILED",
     "DELTA_LAUNCH_IN_PROGRESS",
     "LAUNCHED",
@@ -181,14 +183,15 @@
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
@@ -267,14 +270,15 @@
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
@@ -285,14 +289,15 @@
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
@@ -328,14 +333,15 @@
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
@@ -354,16 +360,19 @@
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
@@ -447,15 +456,17 @@
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/paginator.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,124 +24,110 @@
         get_connectors_paginator: GetConnectorsPaginator = client.get_paginator("get_connectors")
         get_replication_jobs_paginator: GetReplicationJobsPaginator = client.get_paginator("get_replication_jobs")
         get_replication_runs_paginator: GetReplicationRunsPaginator = client.get_paginator("get_replication_runs")
         get_servers_paginator: GetServersPaginator = client.get_paginator("get_servers")
         list_apps_paginator: ListAppsPaginator = client.get_paginator("list_apps")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetConnectorsResponseTypeDef,
     GetReplicationJobsResponseTypeDef,
     GetReplicationRunsResponseTypeDef,
     GetServersResponseTypeDef,
     ListAppsResponseTypeDef,
     PaginatorConfigTypeDef,
     VmServerAddressTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetConnectorsPaginator",
     "GetReplicationJobsPaginator",
     "GetReplicationRunsPaginator",
     "GetServersPaginator",
     "ListAppsPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class GetConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getconnectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getconnectorspaginator)
         """
 
-
 class GetReplicationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationjobspaginator)
     """
 
     def paginate(
-        self, *, replicationJobId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, replicationJobId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReplicationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationjobspaginator)
         """
 
-
 class GetReplicationRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationrunspaginator)
     """
 
     def paginate(
-        self, *, replicationJobId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, replicationJobId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReplicationRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationrunspaginator)
         """
 
-
 class GetServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getserverspaginator)
     """
 
     def paginate(
         self,
         *,
         vmServerAddressList: Sequence[VmServerAddressTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getserverspaginator)
         """
 
-
 class ListAppsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.ListApps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#listappspaginator)
     """
 
     def paginate(
-        self, *, appIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.ListApps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#listappspaginator)
         """
```

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/paginator.pyi` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,116 +24,117 @@
         get_connectors_paginator: GetConnectorsPaginator = client.get_paginator("get_connectors")
         get_replication_jobs_paginator: GetReplicationJobsPaginator = client.get_paginator("get_replication_jobs")
         get_replication_runs_paginator: GetReplicationRunsPaginator = client.get_paginator("get_replication_runs")
         get_servers_paginator: GetServersPaginator = client.get_paginator("get_servers")
         list_apps_paginator: ListAppsPaginator = client.get_paginator("list_apps")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetConnectorsResponseTypeDef,
     GetReplicationJobsResponseTypeDef,
     GetReplicationRunsResponseTypeDef,
     GetServersResponseTypeDef,
     ListAppsResponseTypeDef,
     PaginatorConfigTypeDef,
     VmServerAddressTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetConnectorsPaginator",
     "GetReplicationJobsPaginator",
     "GetReplicationRunsPaginator",
     "GetServersPaginator",
     "ListAppsPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class GetConnectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetConnectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getconnectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetConnectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getconnectorspaginator)
         """
 
+
 class GetReplicationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationjobspaginator)
     """
 
     def paginate(
-        self, *, replicationJobId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, replicationJobId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReplicationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationjobspaginator)
         """
 
+
 class GetReplicationRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationrunspaginator)
     """
 
     def paginate(
-        self, *, replicationJobId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, replicationJobId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReplicationRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetReplicationRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getreplicationrunspaginator)
         """
 
+
 class GetServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getserverspaginator)
     """
 
     def paginate(
         self,
         *,
         vmServerAddressList: Sequence[VmServerAddressTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.GetServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#getserverspaginator)
         """
 
+
 class ListAppsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.ListApps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#listappspaginator)
     """
 
     def paginate(
-        self, *, appIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS.Paginator.ListApps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/paginators/#listappspaginator)
         """
```

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/type_defs.py` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -44,60 +44,60 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "LaunchDetailsTypeDef",
     "ConnectorTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateReplicationJobRequestRequestTypeDef",
+    "CreateReplicationJobResponseTypeDef",
     "DeleteAppLaunchConfigurationRequestRequestTypeDef",
     "DeleteAppReplicationConfigurationRequestRequestTypeDef",
     "DeleteAppRequestRequestTypeDef",
     "DeleteAppValidationConfigurationRequestRequestTypeDef",
     "DeleteReplicationJobRequestRequestTypeDef",
     "DisassociateConnectorRequestRequestTypeDef",
     "GenerateChangeSetRequestRequestTypeDef",
     "S3LocationTypeDef",
     "GenerateTemplateRequestRequestTypeDef",
     "GetAppLaunchConfigurationRequestRequestTypeDef",
     "GetAppReplicationConfigurationRequestRequestTypeDef",
     "GetAppRequestRequestTypeDef",
     "GetAppValidationConfigurationRequestRequestTypeDef",
     "GetAppValidationOutputRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
     "GetConnectorsRequestRequestTypeDef",
+    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
     "GetReplicationJobsRequestRequestTypeDef",
+    "GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
     "GetReplicationRunsRequestRequestTypeDef",
     "VmServerAddressTypeDef",
     "ImportAppCatalogRequestRequestTypeDef",
     "LaunchAppRequestRequestTypeDef",
+    "ListAppsRequestListAppsPaginateTypeDef",
     "ListAppsRequestRequestTypeDef",
     "NotificationContextTypeDef",
+    "PaginatorConfigTypeDef",
     "ReplicationRunStageDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "ServerReplicationParametersTypeDef",
     "StartAppReplicationRequestRequestTypeDef",
     "StartOnDemandAppReplicationRequestRequestTypeDef",
     "StartOnDemandReplicationRunRequestRequestTypeDef",
+    "StartOnDemandReplicationRunResponseTypeDef",
     "StopAppReplicationRequestRequestTypeDef",
     "TerminateAppRequestRequestTypeDef",
     "UpdateReplicationJobRequestRequestTypeDef",
     "AppSummaryTypeDef",
-    "CreateReplicationJobResponseTypeDef",
     "GetConnectorsResponseTypeDef",
-    "StartOnDemandReplicationRunResponseTypeDef",
     "GenerateChangeSetResponseTypeDef",
     "GenerateTemplateResponseTypeDef",
     "SSMOutputTypeDef",
     "SourceTypeDef",
     "UserDataTypeDef",
-    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
-    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
-    "GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    "ListAppsRequestListAppsPaginateTypeDef",
     "GetServersRequestGetServersPaginateTypeDef",
     "GetServersRequestRequestTypeDef",
     "VmServerTypeDef",
     "NotifyAppValidationOutputRequestRequestTypeDef",
     "ReplicationRunTypeDef",
     "ListAppsResponseTypeDef",
     "AppValidationOutputTypeDef",
@@ -164,25 +164,14 @@
     {
         "key": str,
         "value": str,
     },
     total=False,
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
 _RequiredCreateReplicationJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReplicationJobRequestRequestTypeDef",
     {
         "serverId": str,
         "seedReplicationTime": Union[datetime, str],
     },
 )
@@ -205,14 +194,22 @@
 class CreateReplicationJobRequestRequestTypeDef(
     _RequiredCreateReplicationJobRequestRequestTypeDef,
     _OptionalCreateReplicationJobRequestRequestTypeDef,
 ):
     pass
 
 
+CreateReplicationJobResponseTypeDef = TypedDict(
+    "CreateReplicationJobResponseTypeDef",
+    {
+        "replicationJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteAppLaunchConfigurationRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
@@ -317,43 +314,72 @@
 GetAppValidationOutputRequestRequestTypeDef = TypedDict(
     "GetAppValidationOutputRequestRequestTypeDef",
     {
         "appId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetConnectorsRequestGetConnectorsPaginateTypeDef = TypedDict(
+    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetConnectorsRequestRequestTypeDef = TypedDict(
     "GetConnectorsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef = TypedDict(
+    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
+    {
+        "replicationJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetReplicationJobsRequestRequestTypeDef = TypedDict(
     "GetReplicationJobsRequestRequestTypeDef",
     {
         "replicationJobId": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
+    "_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
+    {
+        "replicationJobId": str,
+    },
+)
+_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
+    "_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef(
+    _RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
+    _OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetReplicationRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetReplicationRunsRequestRequestTypeDef",
     {
         "replicationJobId": str,
     },
 )
 _OptionalGetReplicationRunsRequestRequestTypeDef = TypedDict(
@@ -394,14 +420,23 @@
     "LaunchAppRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
 
+ListAppsRequestListAppsPaginateTypeDef = TypedDict(
+    "ListAppsRequestListAppsPaginateTypeDef",
+    {
+        "appIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAppsRequestRequestTypeDef = TypedDict(
     "ListAppsRequestRequestTypeDef",
     {
         "appIds": Sequence[str],
         "nextToken": str,
         "maxResults": int,
     },
@@ -414,23 +449,44 @@
         "validationId": str,
         "status": ValidationStatusType,
         "statusMessage": str,
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
 ReplicationRunStageDetailsTypeDef = TypedDict(
     "ReplicationRunStageDetailsTypeDef",
     {
         "stage": str,
         "stageProgress": str,
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
 ServerReplicationParametersTypeDef = TypedDict(
     "ServerReplicationParametersTypeDef",
     {
         "seedTime": datetime,
         "frequency": int,
         "runOnce": bool,
         "licenseType": LicenseTypeType,
@@ -489,14 +545,22 @@
 class StartOnDemandReplicationRunRequestRequestTypeDef(
     _RequiredStartOnDemandReplicationRunRequestRequestTypeDef,
     _OptionalStartOnDemandReplicationRunRequestRequestTypeDef,
 ):
     pass
 
 
+StartOnDemandReplicationRunResponseTypeDef = TypedDict(
+    "StartOnDemandReplicationRunResponseTypeDef",
+    {
+        "replicationRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAppReplicationRequestRequestTypeDef = TypedDict(
     "StopAppReplicationRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
@@ -560,52 +624,36 @@
         "roleName": str,
         "totalServerGroups": int,
         "totalServers": int,
     },
     total=False,
 )
 
-CreateReplicationJobResponseTypeDef = TypedDict(
-    "CreateReplicationJobResponseTypeDef",
-    {
-        "replicationJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetConnectorsResponseTypeDef = TypedDict(
     "GetConnectorsResponseTypeDef",
     {
         "connectorList": List[ConnectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartOnDemandReplicationRunResponseTypeDef = TypedDict(
-    "StartOnDemandReplicationRunResponseTypeDef",
-    {
-        "replicationRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GenerateChangeSetResponseTypeDef = TypedDict(
     "GenerateChangeSetResponseTypeDef",
     {
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GenerateTemplateResponseTypeDef = TypedDict(
     "GenerateTemplateResponseTypeDef",
     {
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SSMOutputTypeDef = TypedDict(
     "SSMOutputTypeDef",
     {
         "s3Location": S3LocationTypeDef,
@@ -625,67 +673,19 @@
     "UserDataTypeDef",
     {
         "s3Location": S3LocationTypeDef,
     },
     total=False,
 )
 
-GetConnectorsRequestGetConnectorsPaginateTypeDef = TypedDict(
-    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef = TypedDict(
-    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
-    {
-        "replicationJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
-    "_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    {
-        "replicationJobId": str,
-    },
-)
-_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
-    "_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef(
-    _RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-    _OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-):
-    pass
-
-
-ListAppsRequestListAppsPaginateTypeDef = TypedDict(
-    "ListAppsRequestListAppsPaginateTypeDef",
-    {
-        "appIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetServersRequestGetServersPaginateTypeDef = TypedDict(
     "GetServersRequestGetServersPaginateTypeDef",
     {
         "vmServerAddressList": Sequence[VmServerAddressTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetServersRequestRequestTypeDef = TypedDict(
     "GetServersRequestRequestTypeDef",
     {
@@ -749,15 +749,15 @@
 )
 
 ListAppsResponseTypeDef = TypedDict(
     "ListAppsResponseTypeDef",
     {
         "apps": List[AppSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AppValidationOutputTypeDef = TypedDict(
     "AppValidationOutputTypeDef",
     {
         "ssmOutput": SSMOutputTypeDef,
@@ -838,15 +838,15 @@
 GetServersResponseTypeDef = TypedDict(
     "GetServersResponseTypeDef",
     {
         "lastModifiedOn": datetime,
         "serverCatalogStatus": ServerCatalogStatusType,
         "serverList": List[ServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServerGroupTypeDef = TypedDict(
     "ServerGroupTypeDef",
     {
         "serverGroupId": str,
@@ -905,25 +905,25 @@
 )
 
 GetReplicationJobsResponseTypeDef = TypedDict(
     "GetReplicationJobsResponseTypeDef",
     {
         "replicationJobList": List[ReplicationJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReplicationRunsResponseTypeDef = TypedDict(
     "GetReplicationRunsResponseTypeDef",
     {
         "replicationJob": ReplicationJobTypeDef,
         "replicationRunList": List[ReplicationRunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppRequestRequestTypeDef = TypedDict(
     "CreateAppRequestRequestTypeDef",
     {
         "name": str,
@@ -938,25 +938,25 @@
 
 CreateAppResponseTypeDef = TypedDict(
     "CreateAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppResponseTypeDef = TypedDict(
     "GetAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppRequestRequestTypeDef = TypedDict(
     "UpdateAppRequestRequestTypeDef",
     {
         "appId": str,
@@ -971,15 +971,15 @@
 
 UpdateAppResponseTypeDef = TypedDict(
     "UpdateAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServerGroupLaunchConfigurationTypeDef = TypedDict(
     "ServerGroupLaunchConfigurationTypeDef",
     {
         "serverGroupId": str,
@@ -1024,15 +1024,15 @@
 GetAppLaunchConfigurationResponseTypeDef = TypedDict(
     "GetAppLaunchConfigurationResponseTypeDef",
     {
         "appId": str,
         "roleName": str,
         "autoLaunch": bool,
         "serverGroupLaunchConfigurations": List[ServerGroupLaunchConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "PutAppLaunchConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1043,15 +1043,15 @@
     total=False,
 )
 
 GetAppReplicationConfigurationResponseTypeDef = TypedDict(
     "GetAppReplicationConfigurationResponseTypeDef",
     {
         "serverGroupReplicationConfigurations": List[ServerGroupReplicationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutAppReplicationConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1063,15 +1063,15 @@
 )
 
 GetAppValidationConfigurationResponseTypeDef = TypedDict(
     "GetAppValidationConfigurationResponseTypeDef",
     {
         "appValidationConfigurations": List[AppValidationConfigurationTypeDef],
         "serverGroupValidationConfigurations": List[ServerGroupValidationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAppValidationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutAppValidationConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1094,10 +1094,10 @@
     pass
 
 
 GetAppValidationOutputResponseTypeDef = TypedDict(
     "GetAppValidationOutputResponseTypeDef",
     {
         "validationOutputList": List[ValidationOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms/type_defs.pyi` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -43,60 +43,60 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "LaunchDetailsTypeDef",
     "ConnectorTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateReplicationJobRequestRequestTypeDef",
+    "CreateReplicationJobResponseTypeDef",
     "DeleteAppLaunchConfigurationRequestRequestTypeDef",
     "DeleteAppReplicationConfigurationRequestRequestTypeDef",
     "DeleteAppRequestRequestTypeDef",
     "DeleteAppValidationConfigurationRequestRequestTypeDef",
     "DeleteReplicationJobRequestRequestTypeDef",
     "DisassociateConnectorRequestRequestTypeDef",
     "GenerateChangeSetRequestRequestTypeDef",
     "S3LocationTypeDef",
     "GenerateTemplateRequestRequestTypeDef",
     "GetAppLaunchConfigurationRequestRequestTypeDef",
     "GetAppReplicationConfigurationRequestRequestTypeDef",
     "GetAppRequestRequestTypeDef",
     "GetAppValidationConfigurationRequestRequestTypeDef",
     "GetAppValidationOutputRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
     "GetConnectorsRequestRequestTypeDef",
+    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
     "GetReplicationJobsRequestRequestTypeDef",
+    "GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
     "GetReplicationRunsRequestRequestTypeDef",
     "VmServerAddressTypeDef",
     "ImportAppCatalogRequestRequestTypeDef",
     "LaunchAppRequestRequestTypeDef",
+    "ListAppsRequestListAppsPaginateTypeDef",
     "ListAppsRequestRequestTypeDef",
     "NotificationContextTypeDef",
+    "PaginatorConfigTypeDef",
     "ReplicationRunStageDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "ServerReplicationParametersTypeDef",
     "StartAppReplicationRequestRequestTypeDef",
     "StartOnDemandAppReplicationRequestRequestTypeDef",
     "StartOnDemandReplicationRunRequestRequestTypeDef",
+    "StartOnDemandReplicationRunResponseTypeDef",
     "StopAppReplicationRequestRequestTypeDef",
     "TerminateAppRequestRequestTypeDef",
     "UpdateReplicationJobRequestRequestTypeDef",
     "AppSummaryTypeDef",
-    "CreateReplicationJobResponseTypeDef",
     "GetConnectorsResponseTypeDef",
-    "StartOnDemandReplicationRunResponseTypeDef",
     "GenerateChangeSetResponseTypeDef",
     "GenerateTemplateResponseTypeDef",
     "SSMOutputTypeDef",
     "SourceTypeDef",
     "UserDataTypeDef",
-    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
-    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
-    "GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    "ListAppsRequestListAppsPaginateTypeDef",
     "GetServersRequestGetServersPaginateTypeDef",
     "GetServersRequestRequestTypeDef",
     "VmServerTypeDef",
     "NotifyAppValidationOutputRequestRequestTypeDef",
     "ReplicationRunTypeDef",
     "ListAppsResponseTypeDef",
     "AppValidationOutputTypeDef",
@@ -163,25 +163,14 @@
     {
         "key": str,
         "value": str,
     },
     total=False,
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
 _RequiredCreateReplicationJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReplicationJobRequestRequestTypeDef",
     {
         "serverId": str,
         "seedReplicationTime": Union[datetime, str],
     },
 )
@@ -202,14 +191,22 @@
 
 class CreateReplicationJobRequestRequestTypeDef(
     _RequiredCreateReplicationJobRequestRequestTypeDef,
     _OptionalCreateReplicationJobRequestRequestTypeDef,
 ):
     pass
 
+CreateReplicationJobResponseTypeDef = TypedDict(
+    "CreateReplicationJobResponseTypeDef",
+    {
+        "replicationJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteAppLaunchConfigurationRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
@@ -314,43 +311,70 @@
 GetAppValidationOutputRequestRequestTypeDef = TypedDict(
     "GetAppValidationOutputRequestRequestTypeDef",
     {
         "appId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetConnectorsRequestGetConnectorsPaginateTypeDef = TypedDict(
+    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetConnectorsRequestRequestTypeDef = TypedDict(
     "GetConnectorsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef = TypedDict(
+    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
+    {
+        "replicationJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetReplicationJobsRequestRequestTypeDef = TypedDict(
     "GetReplicationJobsRequestRequestTypeDef",
     {
         "replicationJobId": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
+    "_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
+    {
+        "replicationJobId": str,
+    },
+)
+_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
+    "_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef(
+    _RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
+    _OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetReplicationRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetReplicationRunsRequestRequestTypeDef",
     {
         "replicationJobId": str,
     },
 )
 _OptionalGetReplicationRunsRequestRequestTypeDef = TypedDict(
@@ -389,14 +413,23 @@
     "LaunchAppRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
 
+ListAppsRequestListAppsPaginateTypeDef = TypedDict(
+    "ListAppsRequestListAppsPaginateTypeDef",
+    {
+        "appIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAppsRequestRequestTypeDef = TypedDict(
     "ListAppsRequestRequestTypeDef",
     {
         "appIds": Sequence[str],
         "nextToken": str,
         "maxResults": int,
     },
@@ -409,23 +442,44 @@
         "validationId": str,
         "status": ValidationStatusType,
         "statusMessage": str,
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
 ReplicationRunStageDetailsTypeDef = TypedDict(
     "ReplicationRunStageDetailsTypeDef",
     {
         "stage": str,
         "stageProgress": str,
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
 ServerReplicationParametersTypeDef = TypedDict(
     "ServerReplicationParametersTypeDef",
     {
         "seedTime": datetime,
         "frequency": int,
         "runOnce": bool,
         "licenseType": LicenseTypeType,
@@ -480,14 +534,22 @@
 
 class StartOnDemandReplicationRunRequestRequestTypeDef(
     _RequiredStartOnDemandReplicationRunRequestRequestTypeDef,
     _OptionalStartOnDemandReplicationRunRequestRequestTypeDef,
 ):
     pass
 
+StartOnDemandReplicationRunResponseTypeDef = TypedDict(
+    "StartOnDemandReplicationRunResponseTypeDef",
+    {
+        "replicationRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAppReplicationRequestRequestTypeDef = TypedDict(
     "StopAppReplicationRequestRequestTypeDef",
     {
         "appId": str,
     },
     total=False,
 )
@@ -549,52 +611,36 @@
         "roleName": str,
         "totalServerGroups": int,
         "totalServers": int,
     },
     total=False,
 )
 
-CreateReplicationJobResponseTypeDef = TypedDict(
-    "CreateReplicationJobResponseTypeDef",
-    {
-        "replicationJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetConnectorsResponseTypeDef = TypedDict(
     "GetConnectorsResponseTypeDef",
     {
         "connectorList": List[ConnectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartOnDemandReplicationRunResponseTypeDef = TypedDict(
-    "StartOnDemandReplicationRunResponseTypeDef",
-    {
-        "replicationRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GenerateChangeSetResponseTypeDef = TypedDict(
     "GenerateChangeSetResponseTypeDef",
     {
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GenerateTemplateResponseTypeDef = TypedDict(
     "GenerateTemplateResponseTypeDef",
     {
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SSMOutputTypeDef = TypedDict(
     "SSMOutputTypeDef",
     {
         "s3Location": S3LocationTypeDef,
@@ -614,65 +660,19 @@
     "UserDataTypeDef",
     {
         "s3Location": S3LocationTypeDef,
     },
     total=False,
 )
 
-GetConnectorsRequestGetConnectorsPaginateTypeDef = TypedDict(
-    "GetConnectorsRequestGetConnectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef = TypedDict(
-    "GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef",
-    {
-        "replicationJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
-    "_RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    {
-        "replicationJobId": str,
-    },
-)
-_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef = TypedDict(
-    "_OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef(
-    _RequiredGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-    _OptionalGetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-):
-    pass
-
-ListAppsRequestListAppsPaginateTypeDef = TypedDict(
-    "ListAppsRequestListAppsPaginateTypeDef",
-    {
-        "appIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetServersRequestGetServersPaginateTypeDef = TypedDict(
     "GetServersRequestGetServersPaginateTypeDef",
     {
         "vmServerAddressList": Sequence[VmServerAddressTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetServersRequestRequestTypeDef = TypedDict(
     "GetServersRequestRequestTypeDef",
     {
@@ -734,15 +734,15 @@
 )
 
 ListAppsResponseTypeDef = TypedDict(
     "ListAppsResponseTypeDef",
     {
         "apps": List[AppSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AppValidationOutputTypeDef = TypedDict(
     "AppValidationOutputTypeDef",
     {
         "ssmOutput": SSMOutputTypeDef,
@@ -823,15 +823,15 @@
 GetServersResponseTypeDef = TypedDict(
     "GetServersResponseTypeDef",
     {
         "lastModifiedOn": datetime,
         "serverCatalogStatus": ServerCatalogStatusType,
         "serverList": List[ServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServerGroupTypeDef = TypedDict(
     "ServerGroupTypeDef",
     {
         "serverGroupId": str,
@@ -890,25 +890,25 @@
 )
 
 GetReplicationJobsResponseTypeDef = TypedDict(
     "GetReplicationJobsResponseTypeDef",
     {
         "replicationJobList": List[ReplicationJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReplicationRunsResponseTypeDef = TypedDict(
     "GetReplicationRunsResponseTypeDef",
     {
         "replicationJob": ReplicationJobTypeDef,
         "replicationRunList": List[ReplicationRunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppRequestRequestTypeDef = TypedDict(
     "CreateAppRequestRequestTypeDef",
     {
         "name": str,
@@ -923,25 +923,25 @@
 
 CreateAppResponseTypeDef = TypedDict(
     "CreateAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppResponseTypeDef = TypedDict(
     "GetAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppRequestRequestTypeDef = TypedDict(
     "UpdateAppRequestRequestTypeDef",
     {
         "appId": str,
@@ -956,15 +956,15 @@
 
 UpdateAppResponseTypeDef = TypedDict(
     "UpdateAppResponseTypeDef",
     {
         "appSummary": AppSummaryTypeDef,
         "serverGroups": List[ServerGroupTypeDef],
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServerGroupLaunchConfigurationTypeDef = TypedDict(
     "ServerGroupLaunchConfigurationTypeDef",
     {
         "serverGroupId": str,
@@ -1009,15 +1009,15 @@
 GetAppLaunchConfigurationResponseTypeDef = TypedDict(
     "GetAppLaunchConfigurationResponseTypeDef",
     {
         "appId": str,
         "roleName": str,
         "autoLaunch": bool,
         "serverGroupLaunchConfigurations": List[ServerGroupLaunchConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "PutAppLaunchConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1028,15 +1028,15 @@
     total=False,
 )
 
 GetAppReplicationConfigurationResponseTypeDef = TypedDict(
     "GetAppReplicationConfigurationResponseTypeDef",
     {
         "serverGroupReplicationConfigurations": List[ServerGroupReplicationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutAppReplicationConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1048,15 +1048,15 @@
 )
 
 GetAppValidationConfigurationResponseTypeDef = TypedDict(
     "GetAppValidationConfigurationResponseTypeDef",
     {
         "appValidationConfigurations": List[AppValidationConfigurationTypeDef],
         "serverGroupValidationConfigurations": List[ServerGroupValidationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAppValidationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutAppValidationConfigurationRequestRequestTypeDef",
     {
         "appId": str,
@@ -1077,10 +1077,10 @@
 ):
     pass
 
 GetAppValidationOutputResponseTypeDef = TypedDict(
     "GetAppValidationOutputResponseTypeDef",
     {
         "validationOutputList": List[ValidationOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/PKG-INFO` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sms"></a>
 
 # types-aiobotocore-sms
 
 [![PyPI - types-aiobotocore-sms](https://img.shields.io/pypi/v/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sms?color=blue)](https://pypistats.org/packages/types-aiobotocore-sms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
+[aiobotocore.SMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms.html#SMS)
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
 [types-aiobotocore-sms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -352,60 +352,60 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sms.type_defs import (
     LaunchDetailsTypeDef,
     ConnectorTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateReplicationJobRequestRequestTypeDef,
+    CreateReplicationJobResponseTypeDef,
     DeleteAppLaunchConfigurationRequestRequestTypeDef,
     DeleteAppReplicationConfigurationRequestRequestTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteAppValidationConfigurationRequestRequestTypeDef,
     DeleteReplicationJobRequestRequestTypeDef,
     DisassociateConnectorRequestRequestTypeDef,
     GenerateChangeSetRequestRequestTypeDef,
     S3LocationTypeDef,
     GenerateTemplateRequestRequestTypeDef,
     GetAppLaunchConfigurationRequestRequestTypeDef,
     GetAppReplicationConfigurationRequestRequestTypeDef,
     GetAppRequestRequestTypeDef,
     GetAppValidationConfigurationRequestRequestTypeDef,
     GetAppValidationOutputRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConnectorsRequestGetConnectorsPaginateTypeDef,
     GetConnectorsRequestRequestTypeDef,
+    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
     GetReplicationJobsRequestRequestTypeDef,
+    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
     GetReplicationRunsRequestRequestTypeDef,
     VmServerAddressTypeDef,
     ImportAppCatalogRequestRequestTypeDef,
     LaunchAppRequestRequestTypeDef,
+    ListAppsRequestListAppsPaginateTypeDef,
     ListAppsRequestRequestTypeDef,
     NotificationContextTypeDef,
+    PaginatorConfigTypeDef,
     ReplicationRunStageDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ServerReplicationParametersTypeDef,
     StartAppReplicationRequestRequestTypeDef,
     StartOnDemandAppReplicationRequestRequestTypeDef,
     StartOnDemandReplicationRunRequestRequestTypeDef,
+    StartOnDemandReplicationRunResponseTypeDef,
     StopAppReplicationRequestRequestTypeDef,
     TerminateAppRequestRequestTypeDef,
     UpdateReplicationJobRequestRequestTypeDef,
     AppSummaryTypeDef,
-    CreateReplicationJobResponseTypeDef,
     GetConnectorsResponseTypeDef,
-    StartOnDemandReplicationRunResponseTypeDef,
     GenerateChangeSetResponseTypeDef,
     GenerateTemplateResponseTypeDef,
     SSMOutputTypeDef,
     SourceTypeDef,
     UserDataTypeDef,
-    GetConnectorsRequestGetConnectorsPaginateTypeDef,
-    GetReplicationJobsRequestGetReplicationJobsPaginateTypeDef,
-    GetReplicationRunsRequestGetReplicationRunsPaginateTypeDef,
-    ListAppsRequestListAppsPaginateTypeDef,
     GetServersRequestGetServersPaginateTypeDef,
     GetServersRequestRequestTypeDef,
     VmServerTypeDef,
     NotifyAppValidationOutputRequestRequestTypeDef,
     ReplicationRunTypeDef,
     ListAppsResponseTypeDef,
     AppValidationOutputTypeDef,
@@ -448,43 +448,43 @@
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

### Comparing `types-aiobotocore-sms-2.5.0.post1/types_aiobotocore_sms.egg-info/SOURCES.txt` & `types-aiobotocore-sms-2.5.1/types_aiobotocore_sms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

