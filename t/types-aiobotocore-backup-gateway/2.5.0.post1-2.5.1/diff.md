# Comparing `tmp/types-aiobotocore-backup-gateway-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-backup-gateway-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-backup-gateway-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-backup-gateway-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-backup-gateway-2.5.0.post1.tar` & `types-aiobotocore-backup-gateway-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.166973 types-aiobotocore-backup-gateway-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16232 2023-03-11 12:26:15.158973 types-aiobotocore-backup-gateway-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14634 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.166973 types-aiobotocore-backup-gateway-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:10:05.000000 types-aiobotocore-backup-gateway-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.158973 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/
--rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21669 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8466 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8464 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4450 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4444 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19656 2023-03-11 12:10:07.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19639 2023-03-11 12:10:07.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:06.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.158973 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16232 2023-03-11 12:26:14.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:15.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:14.000000 types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.862099 types-aiobotocore-backup-gateway-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16231 2023-06-28 01:43:08.862099 types-aiobotocore-backup-gateway-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14639 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.862099 types-aiobotocore-backup-gateway-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.858099 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/
+-rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21669 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8675 2023-06-28 01:26:43.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8673 2023-06-28 01:26:43.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4336 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4331 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19710 2023-06-28 01:26:43.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19693 2023-06-28 01:26:43.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:42.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.862099 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16231 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:08.000000 types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/LICENSE` & `types-aiobotocore-backup-gateway-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/PKG-INFO` & `types-aiobotocore-backup-gateway-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backup-gateway
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BackupGateway 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BackupGateway 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backup-gateway"></a>
 
 # types-aiobotocore-backup-gateway
 
 [![PyPI - types-aiobotocore-backup-gateway](https://img.shields.io/pypi/v/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup-gateway?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup-gateway)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupGateway 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
+[aiobotocore.BackupGateway 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
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
 [types-aiobotocore-backup-gateway docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/).
 
 See how it helps to find and fix potential bugs:
 
@@ -328,74 +328,74 @@
 
 `types_aiobotocore_backup_gateway.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backup_gateway.type_defs import (
     AssociateGatewayToServerInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateGatewayToServerOutputTypeDef,
     BandwidthRateLimitIntervalTypeDef,
     TagTypeDef,
+    CreateGatewayOutputTypeDef,
     DeleteGatewayInputRequestTypeDef,
+    DeleteGatewayOutputTypeDef,
     DeleteHypervisorInputRequestTypeDef,
+    DeleteHypervisorOutputTypeDef,
     DisassociateGatewayFromServerInputRequestTypeDef,
+    DisassociateGatewayFromServerOutputTypeDef,
     MaintenanceStartTimeTypeDef,
     GatewayTypeDef,
     GetBandwidthRateLimitScheduleInputRequestTypeDef,
     GetGatewayInputRequestTypeDef,
     GetHypervisorInputRequestTypeDef,
     HypervisorDetailsTypeDef,
     GetHypervisorPropertyMappingsInputRequestTypeDef,
     VmwareToAwsTagMappingTypeDef,
     GetVirtualMachineInputRequestTypeDef,
     HypervisorTypeDef,
-    PaginatorConfigTypeDef,
+    ImportHypervisorConfigurationOutputTypeDef,
+    ListGatewaysInputListGatewaysPaginateTypeDef,
     ListGatewaysInputRequestTypeDef,
+    ListHypervisorsInputListHypervisorsPaginateTypeDef,
     ListHypervisorsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesInputRequestTypeDef,
     VirtualMachineTypeDef,
-    PutMaintenanceStartTimeInputRequestTypeDef,
-    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
-    TestHypervisorConfigurationInputRequestTypeDef,
-    UntagResourceInputRequestTypeDef,
-    UpdateGatewayInformationInputRequestTypeDef,
-    UpdateGatewaySoftwareNowInputRequestTypeDef,
-    UpdateHypervisorInputRequestTypeDef,
-    VmwareTagTypeDef,
-    AssociateGatewayToServerOutputTypeDef,
-    CreateGatewayOutputTypeDef,
-    DeleteGatewayOutputTypeDef,
-    DeleteHypervisorOutputTypeDef,
-    DisassociateGatewayFromServerOutputTypeDef,
-    ImportHypervisorConfigurationOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBandwidthRateLimitScheduleOutputTypeDef,
     PutHypervisorPropertyMappingsOutputTypeDef,
+    PutMaintenanceStartTimeInputRequestTypeDef,
     PutMaintenanceStartTimeOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
     StartVirtualMachinesMetadataSyncOutputTypeDef,
     TagResourceOutputTypeDef,
+    TestHypervisorConfigurationInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UntagResourceOutputTypeDef,
+    UpdateGatewayInformationInputRequestTypeDef,
     UpdateGatewayInformationOutputTypeDef,
+    UpdateGatewaySoftwareNowInputRequestTypeDef,
     UpdateGatewaySoftwareNowOutputTypeDef,
+    UpdateHypervisorInputRequestTypeDef,
     UpdateHypervisorOutputTypeDef,
+    VmwareTagTypeDef,
     GetBandwidthRateLimitScheduleOutputTypeDef,
     PutBandwidthRateLimitScheduleInputRequestTypeDef,
     CreateGatewayInputRequestTypeDef,
     ImportHypervisorConfigurationInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     GatewayDetailsTypeDef,
     ListGatewaysOutputTypeDef,
     GetHypervisorOutputTypeDef,
     GetHypervisorPropertyMappingsOutputTypeDef,
     PutHypervisorPropertyMappingsInputRequestTypeDef,
     ListHypervisorsOutputTypeDef,
-    ListGatewaysInputListGatewaysPaginateTypeDef,
-    ListHypervisorsInputListHypervisorsPaginateTypeDef,
-    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesOutputTypeDef,
     VirtualMachineDetailsTypeDef,
     GetGatewayOutputTypeDef,
     GetVirtualMachineOutputTypeDef,
 )
 
 
@@ -406,43 +406,43 @@
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/README.md` & `types-aiobotocore-backup-gateway-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-backup-gateway"></a>
 
 # types-aiobotocore-backup-gateway
 
 [![PyPI - types-aiobotocore-backup-gateway](https://img.shields.io/pypi/v/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup-gateway?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup-gateway)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupGateway 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
+[aiobotocore.BackupGateway 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
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
 [types-aiobotocore-backup-gateway docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,74 +295,74 @@
 
 `types_aiobotocore_backup_gateway.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backup_gateway.type_defs import (
     AssociateGatewayToServerInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateGatewayToServerOutputTypeDef,
     BandwidthRateLimitIntervalTypeDef,
     TagTypeDef,
+    CreateGatewayOutputTypeDef,
     DeleteGatewayInputRequestTypeDef,
+    DeleteGatewayOutputTypeDef,
     DeleteHypervisorInputRequestTypeDef,
+    DeleteHypervisorOutputTypeDef,
     DisassociateGatewayFromServerInputRequestTypeDef,
+    DisassociateGatewayFromServerOutputTypeDef,
     MaintenanceStartTimeTypeDef,
     GatewayTypeDef,
     GetBandwidthRateLimitScheduleInputRequestTypeDef,
     GetGatewayInputRequestTypeDef,
     GetHypervisorInputRequestTypeDef,
     HypervisorDetailsTypeDef,
     GetHypervisorPropertyMappingsInputRequestTypeDef,
     VmwareToAwsTagMappingTypeDef,
     GetVirtualMachineInputRequestTypeDef,
     HypervisorTypeDef,
-    PaginatorConfigTypeDef,
+    ImportHypervisorConfigurationOutputTypeDef,
+    ListGatewaysInputListGatewaysPaginateTypeDef,
     ListGatewaysInputRequestTypeDef,
+    ListHypervisorsInputListHypervisorsPaginateTypeDef,
     ListHypervisorsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesInputRequestTypeDef,
     VirtualMachineTypeDef,
-    PutMaintenanceStartTimeInputRequestTypeDef,
-    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
-    TestHypervisorConfigurationInputRequestTypeDef,
-    UntagResourceInputRequestTypeDef,
-    UpdateGatewayInformationInputRequestTypeDef,
-    UpdateGatewaySoftwareNowInputRequestTypeDef,
-    UpdateHypervisorInputRequestTypeDef,
-    VmwareTagTypeDef,
-    AssociateGatewayToServerOutputTypeDef,
-    CreateGatewayOutputTypeDef,
-    DeleteGatewayOutputTypeDef,
-    DeleteHypervisorOutputTypeDef,
-    DisassociateGatewayFromServerOutputTypeDef,
-    ImportHypervisorConfigurationOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBandwidthRateLimitScheduleOutputTypeDef,
     PutHypervisorPropertyMappingsOutputTypeDef,
+    PutMaintenanceStartTimeInputRequestTypeDef,
     PutMaintenanceStartTimeOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
     StartVirtualMachinesMetadataSyncOutputTypeDef,
     TagResourceOutputTypeDef,
+    TestHypervisorConfigurationInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UntagResourceOutputTypeDef,
+    UpdateGatewayInformationInputRequestTypeDef,
     UpdateGatewayInformationOutputTypeDef,
+    UpdateGatewaySoftwareNowInputRequestTypeDef,
     UpdateGatewaySoftwareNowOutputTypeDef,
+    UpdateHypervisorInputRequestTypeDef,
     UpdateHypervisorOutputTypeDef,
+    VmwareTagTypeDef,
     GetBandwidthRateLimitScheduleOutputTypeDef,
     PutBandwidthRateLimitScheduleInputRequestTypeDef,
     CreateGatewayInputRequestTypeDef,
     ImportHypervisorConfigurationInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     GatewayDetailsTypeDef,
     ListGatewaysOutputTypeDef,
     GetHypervisorOutputTypeDef,
     GetHypervisorPropertyMappingsOutputTypeDef,
     PutHypervisorPropertyMappingsInputRequestTypeDef,
     ListHypervisorsOutputTypeDef,
-    ListGatewaysInputListGatewaysPaginateTypeDef,
-    ListHypervisorsInputListHypervisorsPaginateTypeDef,
-    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesOutputTypeDef,
     VirtualMachineDetailsTypeDef,
     GetGatewayOutputTypeDef,
     GetVirtualMachineOutputTypeDef,
 )
 
 
@@ -373,43 +373,43 @@
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/setup.py` & `types-aiobotocore-backup-gateway-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-backup-gateway.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-backup-gateway",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_backup_gateway"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.BackupGateway 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.BackupGateway 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/"
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__init__.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__init__.pyi` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/__main__.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.BackupGateway 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.BackupGateway 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway\nOther"
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/client.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/client.pyi` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/literals.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -99,14 +99,15 @@
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
@@ -185,14 +186,15 @@
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
@@ -203,14 +205,15 @@
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
@@ -246,14 +249,15 @@
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
@@ -272,16 +276,19 @@
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
@@ -365,15 +372,17 @@
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/literals.pyi` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/paginator.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: BackupGatewayClient
 
         list_gateways_paginator: ListGatewaysPaginator = client.get_paginator("list_gateways")
         list_hypervisors_paginator: ListHypervisorsPaginator = client.get_paginator("list_hypervisors")
         list_virtual_machines_paginator: ListVirtualMachinesPaginator = client.get_paginator("list_virtual_machines")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListGatewaysOutputTypeDef,
     ListHypervisorsOutputTypeDef,
     ListVirtualMachinesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListGatewaysPaginator", "ListHypervisorsPaginator", "ListVirtualMachinesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,43 +52,43 @@
 class ListGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listgatewayspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewaysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listgatewayspaginator)
         """
 
 
 class ListHypervisorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListHypervisors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listhypervisorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHypervisorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListHypervisors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listhypervisorspaginator)
         """
 
 
 class ListVirtualMachinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListVirtualMachines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listvirtualmachinespaginator)
     """
 
     def paginate(
-        self, *, HypervisorArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HypervisorArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualMachinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListVirtualMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listvirtualmachinespaginator)
         """
```

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/paginator.pyi` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: BackupGatewayClient
 
         list_gateways_paginator: ListGatewaysPaginator = client.get_paginator("list_gateways")
         list_hypervisors_paginator: ListHypervisorsPaginator = client.get_paginator("list_hypervisors")
         list_virtual_machines_paginator: ListVirtualMachinesPaginator = client.get_paginator("list_virtual_machines")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListGatewaysOutputTypeDef,
     ListHypervisorsOutputTypeDef,
     ListVirtualMachinesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListGatewaysPaginator", "ListHypervisorsPaginator", "ListVirtualMachinesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,41 +49,41 @@
 class ListGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listgatewayspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewaysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listgatewayspaginator)
         """
 
 class ListHypervisorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListHypervisors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listhypervisorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHypervisorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListHypervisors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listhypervisorspaginator)
         """
 
 class ListVirtualMachinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListVirtualMachines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listvirtualmachinespaginator)
     """
 
     def paginate(
-        self, *, HypervisorArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HypervisorArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualMachinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway.Paginator.ListVirtualMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/paginators/#listvirtualmachinespaginator)
         """
```

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/type_defs.py` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -22,99 +22,95 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AssociateGatewayToServerInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateGatewayToServerOutputTypeDef",
     "BandwidthRateLimitIntervalTypeDef",
     "TagTypeDef",
+    "CreateGatewayOutputTypeDef",
     "DeleteGatewayInputRequestTypeDef",
+    "DeleteGatewayOutputTypeDef",
     "DeleteHypervisorInputRequestTypeDef",
+    "DeleteHypervisorOutputTypeDef",
     "DisassociateGatewayFromServerInputRequestTypeDef",
+    "DisassociateGatewayFromServerOutputTypeDef",
     "MaintenanceStartTimeTypeDef",
     "GatewayTypeDef",
     "GetBandwidthRateLimitScheduleInputRequestTypeDef",
     "GetGatewayInputRequestTypeDef",
     "GetHypervisorInputRequestTypeDef",
     "HypervisorDetailsTypeDef",
     "GetHypervisorPropertyMappingsInputRequestTypeDef",
     "VmwareToAwsTagMappingTypeDef",
     "GetVirtualMachineInputRequestTypeDef",
     "HypervisorTypeDef",
-    "PaginatorConfigTypeDef",
+    "ImportHypervisorConfigurationOutputTypeDef",
+    "ListGatewaysInputListGatewaysPaginateTypeDef",
     "ListGatewaysInputRequestTypeDef",
+    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
     "ListHypervisorsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
     "ListVirtualMachinesInputRequestTypeDef",
     "VirtualMachineTypeDef",
-    "PutMaintenanceStartTimeInputRequestTypeDef",
-    "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
-    "TestHypervisorConfigurationInputRequestTypeDef",
-    "UntagResourceInputRequestTypeDef",
-    "UpdateGatewayInformationInputRequestTypeDef",
-    "UpdateGatewaySoftwareNowInputRequestTypeDef",
-    "UpdateHypervisorInputRequestTypeDef",
-    "VmwareTagTypeDef",
-    "AssociateGatewayToServerOutputTypeDef",
-    "CreateGatewayOutputTypeDef",
-    "DeleteGatewayOutputTypeDef",
-    "DeleteHypervisorOutputTypeDef",
-    "DisassociateGatewayFromServerOutputTypeDef",
-    "ImportHypervisorConfigurationOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutBandwidthRateLimitScheduleOutputTypeDef",
     "PutHypervisorPropertyMappingsOutputTypeDef",
+    "PutMaintenanceStartTimeInputRequestTypeDef",
     "PutMaintenanceStartTimeOutputTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
     "StartVirtualMachinesMetadataSyncOutputTypeDef",
     "TagResourceOutputTypeDef",
+    "TestHypervisorConfigurationInputRequestTypeDef",
+    "UntagResourceInputRequestTypeDef",
     "UntagResourceOutputTypeDef",
+    "UpdateGatewayInformationInputRequestTypeDef",
     "UpdateGatewayInformationOutputTypeDef",
+    "UpdateGatewaySoftwareNowInputRequestTypeDef",
     "UpdateGatewaySoftwareNowOutputTypeDef",
+    "UpdateHypervisorInputRequestTypeDef",
     "UpdateHypervisorOutputTypeDef",
+    "VmwareTagTypeDef",
     "GetBandwidthRateLimitScheduleOutputTypeDef",
     "PutBandwidthRateLimitScheduleInputRequestTypeDef",
     "CreateGatewayInputRequestTypeDef",
     "ImportHypervisorConfigurationInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "GatewayDetailsTypeDef",
     "ListGatewaysOutputTypeDef",
     "GetHypervisorOutputTypeDef",
     "GetHypervisorPropertyMappingsOutputTypeDef",
     "PutHypervisorPropertyMappingsInputRequestTypeDef",
     "ListHypervisorsOutputTypeDef",
-    "ListGatewaysInputListGatewaysPaginateTypeDef",
-    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
-    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
     "ListVirtualMachinesOutputTypeDef",
     "VirtualMachineDetailsTypeDef",
     "GetGatewayOutputTypeDef",
     "GetVirtualMachineOutputTypeDef",
 )
 
 AssociateGatewayToServerInputRequestTypeDef = TypedDict(
     "AssociateGatewayToServerInputRequestTypeDef",
     {
         "GatewayArn": str,
         "ServerArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateGatewayToServerOutputTypeDef = TypedDict(
+    "AssociateGatewayToServerOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBandwidthRateLimitIntervalTypeDef = TypedDict(
     "_RequiredBandwidthRateLimitIntervalTypeDef",
     {
         "DaysOfWeek": List[int],
@@ -128,50 +124,80 @@
     "_OptionalBandwidthRateLimitIntervalTypeDef",
     {
         "AverageUploadRateLimitInBitsPerSec": int,
     },
     total=False,
 )
 
-
 class BandwidthRateLimitIntervalTypeDef(
     _RequiredBandwidthRateLimitIntervalTypeDef, _OptionalBandwidthRateLimitIntervalTypeDef
 ):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateGatewayOutputTypeDef = TypedDict(
+    "CreateGatewayOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteGatewayInputRequestTypeDef = TypedDict(
     "DeleteGatewayInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+DeleteGatewayOutputTypeDef = TypedDict(
+    "DeleteGatewayOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHypervisorInputRequestTypeDef = TypedDict(
     "DeleteHypervisorInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 
+DeleteHypervisorOutputTypeDef = TypedDict(
+    "DeleteHypervisorOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateGatewayFromServerInputRequestTypeDef = TypedDict(
     "DisassociateGatewayFromServerInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+DisassociateGatewayFromServerOutputTypeDef = TypedDict(
+    "DisassociateGatewayFromServerOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMaintenanceStartTimeTypeDef = TypedDict(
     "_RequiredMaintenanceStartTimeTypeDef",
     {
         "HourOfDay": int,
         "MinuteOfHour": int,
     },
 )
@@ -180,21 +206,19 @@
     {
         "DayOfMonth": int,
         "DayOfWeek": int,
     },
     total=False,
 )
 
-
 class MaintenanceStartTimeTypeDef(
     _RequiredMaintenanceStartTimeTypeDef, _OptionalMaintenanceStartTimeTypeDef
 ):
     pass
 
-
 GatewayTypeDef = TypedDict(
     "GatewayTypeDef",
     {
         "GatewayArn": str,
         "GatewayDisplayName": str,
         "GatewayType": Literal["BACKUP_VM"],
         "HypervisorId": str,
@@ -272,33 +296,47 @@
         "KmsKeyArn": str,
         "Name": str,
         "State": HypervisorStateType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ImportHypervisorConfigurationOutputTypeDef = TypedDict(
+    "ImportHypervisorConfigurationOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGatewaysInputListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysInputListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListGatewaysInputRequestTypeDef = TypedDict(
     "ListGatewaysInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListHypervisorsInputListHypervisorsPaginateTypeDef = TypedDict(
+    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHypervisorsInputRequestTypeDef = TypedDict(
     "ListHypervisorsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -307,14 +345,23 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef = TypedDict(
+    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
+    {
+        "HypervisorArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualMachinesInputRequestTypeDef = TypedDict(
     "ListVirtualMachinesInputRequestTypeDef",
     {
         "HypervisorArn": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -330,14 +377,40 @@
         "Name": str,
         "Path": str,
         "ResourceArn": str,
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
+PutBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
+    "PutBandwidthRateLimitScheduleOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutHypervisorPropertyMappingsOutputTypeDef = TypedDict(
+    "PutHypervisorPropertyMappingsOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutMaintenanceStartTimeInputRequestTypeDef = TypedDict(
     "_RequiredPutMaintenanceStartTimeInputRequestTypeDef",
     {
         "GatewayArn": str,
         "HourOfDay": int,
         "MinuteOfHour": int,
     },
@@ -347,29 +420,62 @@
     {
         "DayOfMonth": int,
         "DayOfWeek": int,
     },
     total=False,
 )
 
-
 class PutMaintenanceStartTimeInputRequestTypeDef(
     _RequiredPutMaintenanceStartTimeInputRequestTypeDef,
     _OptionalPutMaintenanceStartTimeInputRequestTypeDef,
 ):
     pass
 
+PutMaintenanceStartTimeOutputTypeDef = TypedDict(
+    "PutMaintenanceStartTimeOutputTypeDef",
+    {
+        "GatewayArn": str,
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
 
 StartVirtualMachinesMetadataSyncInputRequestTypeDef = TypedDict(
     "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 
+StartVirtualMachinesMetadataSyncOutputTypeDef = TypedDict(
+    "StartVirtualMachinesMetadataSyncOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceOutputTypeDef = TypedDict(
+    "TagResourceOutputTypeDef",
+    {
+        "ResourceARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredTestHypervisorConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredTestHypervisorConfigurationInputRequestTypeDef",
     {
         "GatewayArn": str,
         "Host": str,
     },
 )
@@ -378,59 +484,79 @@
     {
         "Password": str,
         "Username": str,
     },
     total=False,
 )
 
-
 class TestHypervisorConfigurationInputRequestTypeDef(
     _RequiredTestHypervisorConfigurationInputRequestTypeDef,
     _OptionalTestHypervisorConfigurationInputRequestTypeDef,
 ):
     pass
 
-
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UntagResourceOutputTypeDef = TypedDict(
+    "UntagResourceOutputTypeDef",
+    {
+        "ResourceARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateGatewayInformationInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGatewayInformationInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 _OptionalUpdateGatewayInformationInputRequestTypeDef = TypedDict(
     "_OptionalUpdateGatewayInformationInputRequestTypeDef",
     {
         "GatewayDisplayName": str,
     },
     total=False,
 )
 
-
 class UpdateGatewayInformationInputRequestTypeDef(
     _RequiredUpdateGatewayInformationInputRequestTypeDef,
     _OptionalUpdateGatewayInformationInputRequestTypeDef,
 ):
     pass
 
+UpdateGatewayInformationOutputTypeDef = TypedDict(
+    "UpdateGatewayInformationOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 UpdateGatewaySoftwareNowInputRequestTypeDef = TypedDict(
     "UpdateGatewaySoftwareNowInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+UpdateGatewaySoftwareNowOutputTypeDef = TypedDict(
+    "UpdateGatewaySoftwareNowOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateHypervisorInputRequestTypeDef = TypedDict(
     "_RequiredUpdateHypervisorInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 _OptionalUpdateHypervisorInputRequestTypeDef = TypedDict(
@@ -441,157 +567,43 @@
         "Name": str,
         "Password": str,
         "Username": str,
     },
     total=False,
 )
 
-
 class UpdateHypervisorInputRequestTypeDef(
     _RequiredUpdateHypervisorInputRequestTypeDef, _OptionalUpdateHypervisorInputRequestTypeDef
 ):
     pass
 
+UpdateHypervisorOutputTypeDef = TypedDict(
+    "UpdateHypervisorOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 VmwareTagTypeDef = TypedDict(
     "VmwareTagTypeDef",
     {
         "VmwareCategory": str,
         "VmwareTagDescription": str,
         "VmwareTagName": str,
     },
     total=False,
 )
 
-AssociateGatewayToServerOutputTypeDef = TypedDict(
-    "AssociateGatewayToServerOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGatewayOutputTypeDef = TypedDict(
-    "CreateGatewayOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGatewayOutputTypeDef = TypedDict(
-    "DeleteGatewayOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHypervisorOutputTypeDef = TypedDict(
-    "DeleteHypervisorOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateGatewayFromServerOutputTypeDef = TypedDict(
-    "DisassociateGatewayFromServerOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportHypervisorConfigurationOutputTypeDef = TypedDict(
-    "ImportHypervisorConfigurationOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
-    "PutBandwidthRateLimitScheduleOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutHypervisorPropertyMappingsOutputTypeDef = TypedDict(
-    "PutHypervisorPropertyMappingsOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutMaintenanceStartTimeOutputTypeDef = TypedDict(
-    "PutMaintenanceStartTimeOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartVirtualMachinesMetadataSyncOutputTypeDef = TypedDict(
-    "StartVirtualMachinesMetadataSyncOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagResourceOutputTypeDef = TypedDict(
-    "TagResourceOutputTypeDef",
-    {
-        "ResourceARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UntagResourceOutputTypeDef = TypedDict(
-    "UntagResourceOutputTypeDef",
-    {
-        "ResourceARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateGatewayInformationOutputTypeDef = TypedDict(
-    "UpdateGatewayInformationOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateGatewaySoftwareNowOutputTypeDef = TypedDict(
-    "UpdateGatewaySoftwareNowOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateHypervisorOutputTypeDef = TypedDict(
-    "UpdateHypervisorOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
     "GetBandwidthRateLimitScheduleOutputTypeDef",
     {
         "BandwidthRateLimitIntervals": List[BandwidthRateLimitIntervalTypeDef],
         "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBandwidthRateLimitScheduleInputRequestTypeDef = TypedDict(
     "PutBandwidthRateLimitScheduleInputRequestTypeDef",
     {
         "BandwidthRateLimitIntervals": Sequence[BandwidthRateLimitIntervalTypeDef],
@@ -611,21 +623,19 @@
     "_OptionalCreateGatewayInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateGatewayInputRequestTypeDef(
     _RequiredCreateGatewayInputRequestTypeDef, _OptionalCreateGatewayInputRequestTypeDef
 ):
     pass
 
-
 _RequiredImportHypervisorConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredImportHypervisorConfigurationInputRequestTypeDef",
     {
         "Host": str,
         "Name": str,
     },
 )
@@ -636,28 +646,26 @@
         "Password": str,
         "Tags": Sequence[TagTypeDef],
         "Username": str,
     },
     total=False,
 )
 
-
 class ImportHypervisorConfigurationInputRequestTypeDef(
     _RequiredImportHypervisorConfigurationInputRequestTypeDef,
     _OptionalImportHypervisorConfigurationInputRequestTypeDef,
 ):
     pass
 
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
@@ -681,33 +689,33 @@
 )
 
 ListGatewaysOutputTypeDef = TypedDict(
     "ListGatewaysOutputTypeDef",
     {
         "Gateways": List[GatewayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHypervisorOutputTypeDef = TypedDict(
     "GetHypervisorOutputTypeDef",
     {
         "Hypervisor": HypervisorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHypervisorPropertyMappingsOutputTypeDef = TypedDict(
     "GetHypervisorPropertyMappingsOutputTypeDef",
     {
         "HypervisorArn": str,
         "IamRoleArn": str,
         "VmwareToAwsTagMappings": List[VmwareToAwsTagMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutHypervisorPropertyMappingsInputRequestTypeDef = TypedDict(
     "PutHypervisorPropertyMappingsInputRequestTypeDef",
     {
         "HypervisorArn": str,
@@ -717,49 +725,24 @@
 )
 
 ListHypervisorsOutputTypeDef = TypedDict(
     "ListHypervisorsOutputTypeDef",
     {
         "Hypervisors": List[HypervisorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGatewaysInputListGatewaysPaginateTypeDef = TypedDict(
-    "ListGatewaysInputListGatewaysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHypervisorsInputListHypervisorsPaginateTypeDef = TypedDict(
-    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef = TypedDict(
-    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
-    {
-        "HypervisorArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListVirtualMachinesOutputTypeDef = TypedDict(
     "ListVirtualMachinesOutputTypeDef",
     {
         "NextToken": str,
         "VirtualMachines": List[VirtualMachineTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualMachineDetailsTypeDef = TypedDict(
     "VirtualMachineDetailsTypeDef",
     {
         "HostName": str,
@@ -773,18 +756,18 @@
     total=False,
 )
 
 GetGatewayOutputTypeDef = TypedDict(
     "GetGatewayOutputTypeDef",
     {
         "Gateway": GatewayDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVirtualMachineOutputTypeDef = TypedDict(
     "GetVirtualMachineOutputTypeDef",
     {
         "VirtualMachine": VirtualMachineDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway/type_defs.pyi` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,98 +22,96 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AssociateGatewayToServerInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateGatewayToServerOutputTypeDef",
     "BandwidthRateLimitIntervalTypeDef",
     "TagTypeDef",
+    "CreateGatewayOutputTypeDef",
     "DeleteGatewayInputRequestTypeDef",
+    "DeleteGatewayOutputTypeDef",
     "DeleteHypervisorInputRequestTypeDef",
+    "DeleteHypervisorOutputTypeDef",
     "DisassociateGatewayFromServerInputRequestTypeDef",
+    "DisassociateGatewayFromServerOutputTypeDef",
     "MaintenanceStartTimeTypeDef",
     "GatewayTypeDef",
     "GetBandwidthRateLimitScheduleInputRequestTypeDef",
     "GetGatewayInputRequestTypeDef",
     "GetHypervisorInputRequestTypeDef",
     "HypervisorDetailsTypeDef",
     "GetHypervisorPropertyMappingsInputRequestTypeDef",
     "VmwareToAwsTagMappingTypeDef",
     "GetVirtualMachineInputRequestTypeDef",
     "HypervisorTypeDef",
-    "PaginatorConfigTypeDef",
+    "ImportHypervisorConfigurationOutputTypeDef",
+    "ListGatewaysInputListGatewaysPaginateTypeDef",
     "ListGatewaysInputRequestTypeDef",
+    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
     "ListHypervisorsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
     "ListVirtualMachinesInputRequestTypeDef",
     "VirtualMachineTypeDef",
-    "PutMaintenanceStartTimeInputRequestTypeDef",
-    "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
-    "TestHypervisorConfigurationInputRequestTypeDef",
-    "UntagResourceInputRequestTypeDef",
-    "UpdateGatewayInformationInputRequestTypeDef",
-    "UpdateGatewaySoftwareNowInputRequestTypeDef",
-    "UpdateHypervisorInputRequestTypeDef",
-    "VmwareTagTypeDef",
-    "AssociateGatewayToServerOutputTypeDef",
-    "CreateGatewayOutputTypeDef",
-    "DeleteGatewayOutputTypeDef",
-    "DeleteHypervisorOutputTypeDef",
-    "DisassociateGatewayFromServerOutputTypeDef",
-    "ImportHypervisorConfigurationOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutBandwidthRateLimitScheduleOutputTypeDef",
     "PutHypervisorPropertyMappingsOutputTypeDef",
+    "PutMaintenanceStartTimeInputRequestTypeDef",
     "PutMaintenanceStartTimeOutputTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
     "StartVirtualMachinesMetadataSyncOutputTypeDef",
     "TagResourceOutputTypeDef",
+    "TestHypervisorConfigurationInputRequestTypeDef",
+    "UntagResourceInputRequestTypeDef",
     "UntagResourceOutputTypeDef",
+    "UpdateGatewayInformationInputRequestTypeDef",
     "UpdateGatewayInformationOutputTypeDef",
+    "UpdateGatewaySoftwareNowInputRequestTypeDef",
     "UpdateGatewaySoftwareNowOutputTypeDef",
+    "UpdateHypervisorInputRequestTypeDef",
     "UpdateHypervisorOutputTypeDef",
+    "VmwareTagTypeDef",
     "GetBandwidthRateLimitScheduleOutputTypeDef",
     "PutBandwidthRateLimitScheduleInputRequestTypeDef",
     "CreateGatewayInputRequestTypeDef",
     "ImportHypervisorConfigurationInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "GatewayDetailsTypeDef",
     "ListGatewaysOutputTypeDef",
     "GetHypervisorOutputTypeDef",
     "GetHypervisorPropertyMappingsOutputTypeDef",
     "PutHypervisorPropertyMappingsInputRequestTypeDef",
     "ListHypervisorsOutputTypeDef",
-    "ListGatewaysInputListGatewaysPaginateTypeDef",
-    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
-    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
     "ListVirtualMachinesOutputTypeDef",
     "VirtualMachineDetailsTypeDef",
     "GetGatewayOutputTypeDef",
     "GetVirtualMachineOutputTypeDef",
 )
 
 AssociateGatewayToServerInputRequestTypeDef = TypedDict(
     "AssociateGatewayToServerInputRequestTypeDef",
     {
         "GatewayArn": str,
         "ServerArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateGatewayToServerOutputTypeDef = TypedDict(
+    "AssociateGatewayToServerOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBandwidthRateLimitIntervalTypeDef = TypedDict(
     "_RequiredBandwidthRateLimitIntervalTypeDef",
     {
         "DaysOfWeek": List[int],
@@ -127,48 +125,82 @@
     "_OptionalBandwidthRateLimitIntervalTypeDef",
     {
         "AverageUploadRateLimitInBitsPerSec": int,
     },
     total=False,
 )
 
+
 class BandwidthRateLimitIntervalTypeDef(
     _RequiredBandwidthRateLimitIntervalTypeDef, _OptionalBandwidthRateLimitIntervalTypeDef
 ):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateGatewayOutputTypeDef = TypedDict(
+    "CreateGatewayOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteGatewayInputRequestTypeDef = TypedDict(
     "DeleteGatewayInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+DeleteGatewayOutputTypeDef = TypedDict(
+    "DeleteGatewayOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHypervisorInputRequestTypeDef = TypedDict(
     "DeleteHypervisorInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 
+DeleteHypervisorOutputTypeDef = TypedDict(
+    "DeleteHypervisorOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateGatewayFromServerInputRequestTypeDef = TypedDict(
     "DisassociateGatewayFromServerInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+DisassociateGatewayFromServerOutputTypeDef = TypedDict(
+    "DisassociateGatewayFromServerOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMaintenanceStartTimeTypeDef = TypedDict(
     "_RequiredMaintenanceStartTimeTypeDef",
     {
         "HourOfDay": int,
         "MinuteOfHour": int,
     },
 )
@@ -177,19 +209,21 @@
     {
         "DayOfMonth": int,
         "DayOfWeek": int,
     },
     total=False,
 )
 
+
 class MaintenanceStartTimeTypeDef(
     _RequiredMaintenanceStartTimeTypeDef, _OptionalMaintenanceStartTimeTypeDef
 ):
     pass
 
+
 GatewayTypeDef = TypedDict(
     "GatewayTypeDef",
     {
         "GatewayArn": str,
         "GatewayDisplayName": str,
         "GatewayType": Literal["BACKUP_VM"],
         "HypervisorId": str,
@@ -267,33 +301,47 @@
         "KmsKeyArn": str,
         "Name": str,
         "State": HypervisorStateType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ImportHypervisorConfigurationOutputTypeDef = TypedDict(
+    "ImportHypervisorConfigurationOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGatewaysInputListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysInputListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListGatewaysInputRequestTypeDef = TypedDict(
     "ListGatewaysInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListHypervisorsInputListHypervisorsPaginateTypeDef = TypedDict(
+    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHypervisorsInputRequestTypeDef = TypedDict(
     "ListHypervisorsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -302,14 +350,23 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef = TypedDict(
+    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
+    {
+        "HypervisorArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualMachinesInputRequestTypeDef = TypedDict(
     "ListVirtualMachinesInputRequestTypeDef",
     {
         "HypervisorArn": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -325,14 +382,40 @@
         "Name": str,
         "Path": str,
         "ResourceArn": str,
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
+PutBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
+    "PutBandwidthRateLimitScheduleOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutHypervisorPropertyMappingsOutputTypeDef = TypedDict(
+    "PutHypervisorPropertyMappingsOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutMaintenanceStartTimeInputRequestTypeDef = TypedDict(
     "_RequiredPutMaintenanceStartTimeInputRequestTypeDef",
     {
         "GatewayArn": str,
         "HourOfDay": int,
         "MinuteOfHour": int,
     },
@@ -342,27 +425,64 @@
     {
         "DayOfMonth": int,
         "DayOfWeek": int,
     },
     total=False,
 )
 
+
 class PutMaintenanceStartTimeInputRequestTypeDef(
     _RequiredPutMaintenanceStartTimeInputRequestTypeDef,
     _OptionalPutMaintenanceStartTimeInputRequestTypeDef,
 ):
     pass
 
+
+PutMaintenanceStartTimeOutputTypeDef = TypedDict(
+    "PutMaintenanceStartTimeOutputTypeDef",
+    {
+        "GatewayArn": str,
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
 StartVirtualMachinesMetadataSyncInputRequestTypeDef = TypedDict(
     "StartVirtualMachinesMetadataSyncInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 
+StartVirtualMachinesMetadataSyncOutputTypeDef = TypedDict(
+    "StartVirtualMachinesMetadataSyncOutputTypeDef",
+    {
+        "HypervisorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceOutputTypeDef = TypedDict(
+    "TagResourceOutputTypeDef",
+    {
+        "ResourceARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredTestHypervisorConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredTestHypervisorConfigurationInputRequestTypeDef",
     {
         "GatewayArn": str,
         "Host": str,
     },
 )
@@ -371,55 +491,83 @@
     {
         "Password": str,
         "Username": str,
     },
     total=False,
 )
 
+
 class TestHypervisorConfigurationInputRequestTypeDef(
     _RequiredTestHypervisorConfigurationInputRequestTypeDef,
     _OptionalTestHypervisorConfigurationInputRequestTypeDef,
 ):
     pass
 
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UntagResourceOutputTypeDef = TypedDict(
+    "UntagResourceOutputTypeDef",
+    {
+        "ResourceARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateGatewayInformationInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGatewayInformationInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 _OptionalUpdateGatewayInformationInputRequestTypeDef = TypedDict(
     "_OptionalUpdateGatewayInformationInputRequestTypeDef",
     {
         "GatewayDisplayName": str,
     },
     total=False,
 )
 
+
 class UpdateGatewayInformationInputRequestTypeDef(
     _RequiredUpdateGatewayInformationInputRequestTypeDef,
     _OptionalUpdateGatewayInformationInputRequestTypeDef,
 ):
     pass
 
+
+UpdateGatewayInformationOutputTypeDef = TypedDict(
+    "UpdateGatewayInformationOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateGatewaySoftwareNowInputRequestTypeDef = TypedDict(
     "UpdateGatewaySoftwareNowInputRequestTypeDef",
     {
         "GatewayArn": str,
     },
 )
 
+UpdateGatewaySoftwareNowOutputTypeDef = TypedDict(
+    "UpdateGatewaySoftwareNowOutputTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateHypervisorInputRequestTypeDef = TypedDict(
     "_RequiredUpdateHypervisorInputRequestTypeDef",
     {
         "HypervisorArn": str,
     },
 )
 _OptionalUpdateHypervisorInputRequestTypeDef = TypedDict(
@@ -430,155 +578,45 @@
         "Name": str,
         "Password": str,
         "Username": str,
     },
     total=False,
 )
 
+
 class UpdateHypervisorInputRequestTypeDef(
     _RequiredUpdateHypervisorInputRequestTypeDef, _OptionalUpdateHypervisorInputRequestTypeDef
 ):
     pass
 
-VmwareTagTypeDef = TypedDict(
-    "VmwareTagTypeDef",
-    {
-        "VmwareCategory": str,
-        "VmwareTagDescription": str,
-        "VmwareTagName": str,
-    },
-    total=False,
-)
-
-AssociateGatewayToServerOutputTypeDef = TypedDict(
-    "AssociateGatewayToServerOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGatewayOutputTypeDef = TypedDict(
-    "CreateGatewayOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGatewayOutputTypeDef = TypedDict(
-    "DeleteGatewayOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHypervisorOutputTypeDef = TypedDict(
-    "DeleteHypervisorOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateGatewayFromServerOutputTypeDef = TypedDict(
-    "DisassociateGatewayFromServerOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportHypervisorConfigurationOutputTypeDef = TypedDict(
-    "ImportHypervisorConfigurationOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
-    "PutBandwidthRateLimitScheduleOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutHypervisorPropertyMappingsOutputTypeDef = TypedDict(
-    "PutHypervisorPropertyMappingsOutputTypeDef",
-    {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-PutMaintenanceStartTimeOutputTypeDef = TypedDict(
-    "PutMaintenanceStartTimeOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartVirtualMachinesMetadataSyncOutputTypeDef = TypedDict(
-    "StartVirtualMachinesMetadataSyncOutputTypeDef",
+UpdateHypervisorOutputTypeDef = TypedDict(
+    "UpdateHypervisorOutputTypeDef",
     {
         "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagResourceOutputTypeDef = TypedDict(
-    "TagResourceOutputTypeDef",
-    {
-        "ResourceARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UntagResourceOutputTypeDef = TypedDict(
-    "UntagResourceOutputTypeDef",
-    {
-        "ResourceARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateGatewayInformationOutputTypeDef = TypedDict(
-    "UpdateGatewayInformationOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateGatewaySoftwareNowOutputTypeDef = TypedDict(
-    "UpdateGatewaySoftwareNowOutputTypeDef",
-    {
-        "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateHypervisorOutputTypeDef = TypedDict(
-    "UpdateHypervisorOutputTypeDef",
+VmwareTagTypeDef = TypedDict(
+    "VmwareTagTypeDef",
     {
-        "HypervisorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "VmwareCategory": str,
+        "VmwareTagDescription": str,
+        "VmwareTagName": str,
     },
+    total=False,
 )
 
 GetBandwidthRateLimitScheduleOutputTypeDef = TypedDict(
     "GetBandwidthRateLimitScheduleOutputTypeDef",
     {
         "BandwidthRateLimitIntervals": List[BandwidthRateLimitIntervalTypeDef],
         "GatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBandwidthRateLimitScheduleInputRequestTypeDef = TypedDict(
     "PutBandwidthRateLimitScheduleInputRequestTypeDef",
     {
         "BandwidthRateLimitIntervals": Sequence[BandwidthRateLimitIntervalTypeDef],
@@ -598,19 +636,21 @@
     "_OptionalCreateGatewayInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateGatewayInputRequestTypeDef(
     _RequiredCreateGatewayInputRequestTypeDef, _OptionalCreateGatewayInputRequestTypeDef
 ):
     pass
 
+
 _RequiredImportHypervisorConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredImportHypervisorConfigurationInputRequestTypeDef",
     {
         "Host": str,
         "Name": str,
     },
 )
@@ -621,26 +661,28 @@
         "Password": str,
         "Tags": Sequence[TagTypeDef],
         "Username": str,
     },
     total=False,
 )
 
+
 class ImportHypervisorConfigurationInputRequestTypeDef(
     _RequiredImportHypervisorConfigurationInputRequestTypeDef,
     _OptionalImportHypervisorConfigurationInputRequestTypeDef,
 ):
     pass
 
+
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
@@ -664,33 +706,33 @@
 )
 
 ListGatewaysOutputTypeDef = TypedDict(
     "ListGatewaysOutputTypeDef",
     {
         "Gateways": List[GatewayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHypervisorOutputTypeDef = TypedDict(
     "GetHypervisorOutputTypeDef",
     {
         "Hypervisor": HypervisorDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHypervisorPropertyMappingsOutputTypeDef = TypedDict(
     "GetHypervisorPropertyMappingsOutputTypeDef",
     {
         "HypervisorArn": str,
         "IamRoleArn": str,
         "VmwareToAwsTagMappings": List[VmwareToAwsTagMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutHypervisorPropertyMappingsInputRequestTypeDef = TypedDict(
     "PutHypervisorPropertyMappingsInputRequestTypeDef",
     {
         "HypervisorArn": str,
@@ -700,49 +742,24 @@
 )
 
 ListHypervisorsOutputTypeDef = TypedDict(
     "ListHypervisorsOutputTypeDef",
     {
         "Hypervisors": List[HypervisorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListGatewaysInputListGatewaysPaginateTypeDef = TypedDict(
-    "ListGatewaysInputListGatewaysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHypervisorsInputListHypervisorsPaginateTypeDef = TypedDict(
-    "ListHypervisorsInputListHypervisorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef = TypedDict(
-    "ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef",
-    {
-        "HypervisorArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListVirtualMachinesOutputTypeDef = TypedDict(
     "ListVirtualMachinesOutputTypeDef",
     {
         "NextToken": str,
         "VirtualMachines": List[VirtualMachineTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualMachineDetailsTypeDef = TypedDict(
     "VirtualMachineDetailsTypeDef",
     {
         "HostName": str,
@@ -756,18 +773,18 @@
     total=False,
 )
 
 GetGatewayOutputTypeDef = TypedDict(
     "GetGatewayOutputTypeDef",
     {
         "Gateway": GatewayDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVirtualMachineOutputTypeDef = TypedDict(
     "GetVirtualMachineOutputTypeDef",
     {
         "VirtualMachine": VirtualMachineDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/PKG-INFO` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backup-gateway
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BackupGateway 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BackupGateway 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backup-gateway"></a>
 
 # types-aiobotocore-backup-gateway
 
 [![PyPI - types-aiobotocore-backup-gateway](https://img.shields.io/pypi/v/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup-gateway.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup-gateway)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup-gateway?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup-gateway)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupGateway 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
+[aiobotocore.BackupGateway 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup-gateway.html#BackupGateway)
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
 [types-aiobotocore-backup-gateway docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup_gateway/).
 
 See how it helps to find and fix potential bugs:
 
@@ -328,74 +328,74 @@
 
 `types_aiobotocore_backup_gateway.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backup_gateway.type_defs import (
     AssociateGatewayToServerInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateGatewayToServerOutputTypeDef,
     BandwidthRateLimitIntervalTypeDef,
     TagTypeDef,
+    CreateGatewayOutputTypeDef,
     DeleteGatewayInputRequestTypeDef,
+    DeleteGatewayOutputTypeDef,
     DeleteHypervisorInputRequestTypeDef,
+    DeleteHypervisorOutputTypeDef,
     DisassociateGatewayFromServerInputRequestTypeDef,
+    DisassociateGatewayFromServerOutputTypeDef,
     MaintenanceStartTimeTypeDef,
     GatewayTypeDef,
     GetBandwidthRateLimitScheduleInputRequestTypeDef,
     GetGatewayInputRequestTypeDef,
     GetHypervisorInputRequestTypeDef,
     HypervisorDetailsTypeDef,
     GetHypervisorPropertyMappingsInputRequestTypeDef,
     VmwareToAwsTagMappingTypeDef,
     GetVirtualMachineInputRequestTypeDef,
     HypervisorTypeDef,
-    PaginatorConfigTypeDef,
+    ImportHypervisorConfigurationOutputTypeDef,
+    ListGatewaysInputListGatewaysPaginateTypeDef,
     ListGatewaysInputRequestTypeDef,
+    ListHypervisorsInputListHypervisorsPaginateTypeDef,
     ListHypervisorsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesInputRequestTypeDef,
     VirtualMachineTypeDef,
-    PutMaintenanceStartTimeInputRequestTypeDef,
-    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
-    TestHypervisorConfigurationInputRequestTypeDef,
-    UntagResourceInputRequestTypeDef,
-    UpdateGatewayInformationInputRequestTypeDef,
-    UpdateGatewaySoftwareNowInputRequestTypeDef,
-    UpdateHypervisorInputRequestTypeDef,
-    VmwareTagTypeDef,
-    AssociateGatewayToServerOutputTypeDef,
-    CreateGatewayOutputTypeDef,
-    DeleteGatewayOutputTypeDef,
-    DeleteHypervisorOutputTypeDef,
-    DisassociateGatewayFromServerOutputTypeDef,
-    ImportHypervisorConfigurationOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBandwidthRateLimitScheduleOutputTypeDef,
     PutHypervisorPropertyMappingsOutputTypeDef,
+    PutMaintenanceStartTimeInputRequestTypeDef,
     PutMaintenanceStartTimeOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartVirtualMachinesMetadataSyncInputRequestTypeDef,
     StartVirtualMachinesMetadataSyncOutputTypeDef,
     TagResourceOutputTypeDef,
+    TestHypervisorConfigurationInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UntagResourceOutputTypeDef,
+    UpdateGatewayInformationInputRequestTypeDef,
     UpdateGatewayInformationOutputTypeDef,
+    UpdateGatewaySoftwareNowInputRequestTypeDef,
     UpdateGatewaySoftwareNowOutputTypeDef,
+    UpdateHypervisorInputRequestTypeDef,
     UpdateHypervisorOutputTypeDef,
+    VmwareTagTypeDef,
     GetBandwidthRateLimitScheduleOutputTypeDef,
     PutBandwidthRateLimitScheduleInputRequestTypeDef,
     CreateGatewayInputRequestTypeDef,
     ImportHypervisorConfigurationInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     GatewayDetailsTypeDef,
     ListGatewaysOutputTypeDef,
     GetHypervisorOutputTypeDef,
     GetHypervisorPropertyMappingsOutputTypeDef,
     PutHypervisorPropertyMappingsInputRequestTypeDef,
     ListHypervisorsOutputTypeDef,
-    ListGatewaysInputListGatewaysPaginateTypeDef,
-    ListHypervisorsInputListHypervisorsPaginateTypeDef,
-    ListVirtualMachinesInputListVirtualMachinesPaginateTypeDef,
     ListVirtualMachinesOutputTypeDef,
     VirtualMachineDetailsTypeDef,
     GetGatewayOutputTypeDef,
     GetVirtualMachineOutputTypeDef,
 )
 
 
@@ -406,43 +406,43 @@
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

### Comparing `types-aiobotocore-backup-gateway-2.5.0.post1/types_aiobotocore_backup_gateway.egg-info/SOURCES.txt` & `types-aiobotocore-backup-gateway-2.5.1/types_aiobotocore_backup_gateway.egg-info/SOURCES.txt`

 * *Files identical despite different names*

