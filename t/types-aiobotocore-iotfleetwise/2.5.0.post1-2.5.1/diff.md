# Comparing `tmp/types-aiobotocore-iotfleetwise-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotfleetwise-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotfleetwise-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotfleetwise-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1.tar` & `types-aiobotocore-iotfleetwise-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.971300 types-aiobotocore-iotfleetwise-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21733 2023-03-11 12:26:46.971300 types-aiobotocore-iotfleetwise-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20142 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.971300 types-aiobotocore-iotfleetwise-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.951299 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/
--rw-r--r--   0 runner    (1001) docker     (123)     3445 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3444 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43442 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43370 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11066 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11064 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    16313 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    16297 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    57091 2023-03-11 12:16:24.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    56991 2023-03-11 12:16:24.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:23.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.971300 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21733 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.514154 types-aiobotocore-iotfleetwise-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21868 2023-06-28 01:43:38.514154 types-aiobotocore-iotfleetwise-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20283 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.514154 types-aiobotocore-iotfleetwise-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.510153 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/
+-rw-r--r--   0 runner    (1001) docker     (123)     3445 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3444 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43363 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43291 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11432 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11430 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    16219 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16204 2023-06-28 01:33:01.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    58211 2023-06-28 01:33:02.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58111 2023-06-28 01:33:02.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.514154 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21868 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/LICENSE` & `types-aiobotocore-iotfleetwise-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotfleetwise-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotfleetwise
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTFleetWise 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTFleetWise 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotfleetwise"></a>
 
 # types-aiobotocore-iotfleetwise
 
 [![PyPI - types-aiobotocore-iotfleetwise](https://img.shields.io/pypi/v/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleetwise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleetwise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
+[aiobotocore.IoTFleetWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
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
 [types-aiobotocore-iotfleetwise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -340,14 +340,15 @@
 `types_aiobotocore_iotfleetwise.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotfleetwise.literals import (
     CampaignStatusType,
     CompressionType,
+    DataFormatType,
     DiagnosticsModeType,
     GetVehicleStatusPaginatorName,
     ListCampaignsPaginatorName,
     ListDecoderManifestNetworkInterfacesPaginatorName,
     ListDecoderManifestSignalsPaginatorName,
     ListDecoderManifestsPaginatorName,
     ListFleetsForVehiclePaginatorName,
@@ -361,14 +362,15 @@
     LogTypeType,
     ManifestStatusType,
     NetworkInterfaceTypeType,
     NodeDataTypeType,
     RegistrationStatusType,
     SignalDecoderTypeType,
     SpoolingModeType,
+    StorageCompressionFormatType,
     TriggerModeType,
     UpdateCampaignActionType,
     UpdateModeType,
     VehicleAssociationBehaviorType,
     VehicleStateType,
     IoTFleetWiseServiceName,
     ServiceName,
@@ -392,147 +394,150 @@
 ```python
 from types_aiobotocore_iotfleetwise.type_defs import (
     ActuatorTypeDef,
     AssociateVehicleFleetRequestRequestTypeDef,
     AttributeTypeDef,
     CreateVehicleErrorTypeDef,
     CreateVehicleResponseItemTypeDef,
-    ResponseMetadataTypeDef,
     UpdateVehicleRequestItemTypeDef,
     UpdateVehicleErrorTypeDef,
     UpdateVehicleResponseItemTypeDef,
     BranchTypeDef,
     CampaignSummaryTypeDef,
     CanDbcDefinitionTypeDef,
     CanInterfaceTypeDef,
     CanSignalTypeDef,
     CloudWatchLogDeliveryOptionsTypeDef,
     ConditionBasedCollectionSchemeTypeDef,
     TimeBasedCollectionSchemeTypeDef,
     SignalInformationTypeDef,
     TagTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDecoderManifestResponseTypeDef,
+    CreateFleetResponseTypeDef,
+    CreateModelManifestResponseTypeDef,
+    CreateSignalCatalogResponseTypeDef,
+    CreateVehicleResponseTypeDef,
+    S3ConfigTypeDef,
+    TimestreamConfigTypeDef,
     DecoderManifestSummaryTypeDef,
     DeleteCampaignRequestRequestTypeDef,
+    DeleteCampaignResponseTypeDef,
     DeleteDecoderManifestRequestRequestTypeDef,
+    DeleteDecoderManifestResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
+    DeleteFleetResponseTypeDef,
     DeleteModelManifestRequestRequestTypeDef,
+    DeleteModelManifestResponseTypeDef,
     DeleteSignalCatalogRequestRequestTypeDef,
+    DeleteSignalCatalogResponseTypeDef,
     DeleteVehicleRequestRequestTypeDef,
+    DeleteVehicleResponseTypeDef,
     DisassociateVehicleFleetRequestRequestTypeDef,
     FleetSummaryTypeDef,
     FormattedVssTypeDef,
     GetCampaignRequestRequestTypeDef,
     GetDecoderManifestRequestRequestTypeDef,
+    GetDecoderManifestResponseTypeDef,
     GetFleetRequestRequestTypeDef,
+    GetFleetResponseTypeDef,
     GetModelManifestRequestRequestTypeDef,
+    GetModelManifestResponseTypeDef,
     IamRegistrationResponseTypeDef,
     TimestreamRegistrationResponseTypeDef,
     GetSignalCatalogRequestRequestTypeDef,
     NodeCountsTypeDef,
     GetVehicleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetVehicleResponseTypeDef,
+    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
     GetVehicleStatusRequestRequestTypeDef,
     VehicleStatusTypeDef,
     IamResourcesTypeDef,
+    ImportDecoderManifestResponseTypeDef,
+    ImportSignalCatalogResponseTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
     ListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
+    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
     ListDecoderManifestSignalsRequestRequestTypeDef,
+    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
     ListDecoderManifestsRequestRequestTypeDef,
+    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
     ListFleetsForVehicleRequestRequestTypeDef,
+    ListFleetsForVehicleResponseTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
     ListModelManifestNodesRequestRequestTypeDef,
+    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
     ListModelManifestsRequestRequestTypeDef,
     ModelManifestSummaryTypeDef,
+    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
     ListSignalCatalogNodesRequestRequestTypeDef,
+    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
     ListSignalCatalogsRequestRequestTypeDef,
     SignalCatalogSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
     ListVehiclesInFleetRequestRequestTypeDef,
+    ListVehiclesInFleetResponseTypeDef,
+    ListVehiclesRequestListVehiclesPaginateTypeDef,
     ListVehiclesRequestRequestTypeDef,
     VehicleSummaryTypeDef,
     ObdInterfaceTypeDef,
     SensorTypeDef,
     ObdSignalTypeDef,
+    PaginatorConfigTypeDef,
     TimestreamResourcesTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignRequestRequestTypeDef,
-    UpdateFleetRequestRequestTypeDef,
-    UpdateModelManifestRequestRequestTypeDef,
-    UpdateVehicleRequestRequestTypeDef,
-    BatchCreateVehicleResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDecoderManifestResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateModelManifestResponseTypeDef,
-    CreateSignalCatalogResponseTypeDef,
-    CreateVehicleResponseTypeDef,
-    DeleteCampaignResponseTypeDef,
-    DeleteDecoderManifestResponseTypeDef,
-    DeleteFleetResponseTypeDef,
-    DeleteModelManifestResponseTypeDef,
-    DeleteSignalCatalogResponseTypeDef,
-    DeleteVehicleResponseTypeDef,
-    GetDecoderManifestResponseTypeDef,
-    GetFleetResponseTypeDef,
-    GetModelManifestResponseTypeDef,
-    GetVehicleResponseTypeDef,
-    ImportDecoderManifestResponseTypeDef,
-    ImportSignalCatalogResponseTypeDef,
-    ListFleetsForVehicleResponseTypeDef,
-    ListVehiclesInFleetResponseTypeDef,
     UpdateCampaignResponseTypeDef,
     UpdateDecoderManifestResponseTypeDef,
+    UpdateFleetRequestRequestTypeDef,
     UpdateFleetResponseTypeDef,
+    UpdateModelManifestRequestRequestTypeDef,
     UpdateModelManifestResponseTypeDef,
     UpdateSignalCatalogResponseTypeDef,
+    UpdateVehicleRequestRequestTypeDef,
     UpdateVehicleResponseTypeDef,
+    BatchCreateVehicleResponseTypeDef,
     BatchUpdateVehicleRequestRequestTypeDef,
     BatchUpdateVehicleResponseTypeDef,
     ListCampaignsResponseTypeDef,
     NetworkFileDefinitionTypeDef,
     GetLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     CollectionSchemeTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateModelManifestRequestRequestTypeDef,
     CreateVehicleRequestItemTypeDef,
     CreateVehicleRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataDestinationConfigTypeDef,
     ListDecoderManifestsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ImportSignalCatalogRequestRequestTypeDef,
     GetRegisterAccountStatusResponseTypeDef,
     GetSignalCatalogResponseTypeDef,
-    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
-    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
-    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
-    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-    ListVehiclesRequestListVehiclesPaginateTypeDef,
     GetVehicleStatusResponseTypeDef,
     ListModelManifestsResponseTypeDef,
     ListSignalCatalogsResponseTypeDef,
     ListVehiclesResponseTypeDef,
     NetworkInterfaceTypeDef,
     NodeTypeDef,
     SignalDecoderTypeDef,
     RegisterAccountRequestRequestTypeDef,
     RegisterAccountResponseTypeDef,
     ImportDecoderManifestRequestRequestTypeDef,
+    BatchCreateVehicleRequestRequestTypeDef,
     CreateCampaignRequestRequestTypeDef,
     GetCampaignResponseTypeDef,
-    BatchCreateVehicleRequestRequestTypeDef,
     ListDecoderManifestNetworkInterfacesResponseTypeDef,
     CreateSignalCatalogRequestRequestTypeDef,
     ListModelManifestNodesResponseTypeDef,
     ListSignalCatalogNodesResponseTypeDef,
     UpdateSignalCatalogRequestRequestTypeDef,
     CreateDecoderManifestRequestRequestTypeDef,
     ListDecoderManifestSignalsResponseTypeDef,
@@ -547,43 +552,43 @@
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/README.md` & `types-aiobotocore-iotfleetwise-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotfleetwise"></a>
 
 # types-aiobotocore-iotfleetwise
 
 [![PyPI - types-aiobotocore-iotfleetwise](https://img.shields.io/pypi/v/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleetwise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleetwise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
+[aiobotocore.IoTFleetWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
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
 [types-aiobotocore-iotfleetwise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -307,14 +307,15 @@
 `types_aiobotocore_iotfleetwise.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotfleetwise.literals import (
     CampaignStatusType,
     CompressionType,
+    DataFormatType,
     DiagnosticsModeType,
     GetVehicleStatusPaginatorName,
     ListCampaignsPaginatorName,
     ListDecoderManifestNetworkInterfacesPaginatorName,
     ListDecoderManifestSignalsPaginatorName,
     ListDecoderManifestsPaginatorName,
     ListFleetsForVehiclePaginatorName,
@@ -328,14 +329,15 @@
     LogTypeType,
     ManifestStatusType,
     NetworkInterfaceTypeType,
     NodeDataTypeType,
     RegistrationStatusType,
     SignalDecoderTypeType,
     SpoolingModeType,
+    StorageCompressionFormatType,
     TriggerModeType,
     UpdateCampaignActionType,
     UpdateModeType,
     VehicleAssociationBehaviorType,
     VehicleStateType,
     IoTFleetWiseServiceName,
     ServiceName,
@@ -359,147 +361,150 @@
 ```python
 from types_aiobotocore_iotfleetwise.type_defs import (
     ActuatorTypeDef,
     AssociateVehicleFleetRequestRequestTypeDef,
     AttributeTypeDef,
     CreateVehicleErrorTypeDef,
     CreateVehicleResponseItemTypeDef,
-    ResponseMetadataTypeDef,
     UpdateVehicleRequestItemTypeDef,
     UpdateVehicleErrorTypeDef,
     UpdateVehicleResponseItemTypeDef,
     BranchTypeDef,
     CampaignSummaryTypeDef,
     CanDbcDefinitionTypeDef,
     CanInterfaceTypeDef,
     CanSignalTypeDef,
     CloudWatchLogDeliveryOptionsTypeDef,
     ConditionBasedCollectionSchemeTypeDef,
     TimeBasedCollectionSchemeTypeDef,
     SignalInformationTypeDef,
     TagTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDecoderManifestResponseTypeDef,
+    CreateFleetResponseTypeDef,
+    CreateModelManifestResponseTypeDef,
+    CreateSignalCatalogResponseTypeDef,
+    CreateVehicleResponseTypeDef,
+    S3ConfigTypeDef,
+    TimestreamConfigTypeDef,
     DecoderManifestSummaryTypeDef,
     DeleteCampaignRequestRequestTypeDef,
+    DeleteCampaignResponseTypeDef,
     DeleteDecoderManifestRequestRequestTypeDef,
+    DeleteDecoderManifestResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
+    DeleteFleetResponseTypeDef,
     DeleteModelManifestRequestRequestTypeDef,
+    DeleteModelManifestResponseTypeDef,
     DeleteSignalCatalogRequestRequestTypeDef,
+    DeleteSignalCatalogResponseTypeDef,
     DeleteVehicleRequestRequestTypeDef,
+    DeleteVehicleResponseTypeDef,
     DisassociateVehicleFleetRequestRequestTypeDef,
     FleetSummaryTypeDef,
     FormattedVssTypeDef,
     GetCampaignRequestRequestTypeDef,
     GetDecoderManifestRequestRequestTypeDef,
+    GetDecoderManifestResponseTypeDef,
     GetFleetRequestRequestTypeDef,
+    GetFleetResponseTypeDef,
     GetModelManifestRequestRequestTypeDef,
+    GetModelManifestResponseTypeDef,
     IamRegistrationResponseTypeDef,
     TimestreamRegistrationResponseTypeDef,
     GetSignalCatalogRequestRequestTypeDef,
     NodeCountsTypeDef,
     GetVehicleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetVehicleResponseTypeDef,
+    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
     GetVehicleStatusRequestRequestTypeDef,
     VehicleStatusTypeDef,
     IamResourcesTypeDef,
+    ImportDecoderManifestResponseTypeDef,
+    ImportSignalCatalogResponseTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
     ListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
+    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
     ListDecoderManifestSignalsRequestRequestTypeDef,
+    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
     ListDecoderManifestsRequestRequestTypeDef,
+    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
     ListFleetsForVehicleRequestRequestTypeDef,
+    ListFleetsForVehicleResponseTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
     ListModelManifestNodesRequestRequestTypeDef,
+    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
     ListModelManifestsRequestRequestTypeDef,
     ModelManifestSummaryTypeDef,
+    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
     ListSignalCatalogNodesRequestRequestTypeDef,
+    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
     ListSignalCatalogsRequestRequestTypeDef,
     SignalCatalogSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
     ListVehiclesInFleetRequestRequestTypeDef,
+    ListVehiclesInFleetResponseTypeDef,
+    ListVehiclesRequestListVehiclesPaginateTypeDef,
     ListVehiclesRequestRequestTypeDef,
     VehicleSummaryTypeDef,
     ObdInterfaceTypeDef,
     SensorTypeDef,
     ObdSignalTypeDef,
+    PaginatorConfigTypeDef,
     TimestreamResourcesTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignRequestRequestTypeDef,
-    UpdateFleetRequestRequestTypeDef,
-    UpdateModelManifestRequestRequestTypeDef,
-    UpdateVehicleRequestRequestTypeDef,
-    BatchCreateVehicleResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDecoderManifestResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateModelManifestResponseTypeDef,
-    CreateSignalCatalogResponseTypeDef,
-    CreateVehicleResponseTypeDef,
-    DeleteCampaignResponseTypeDef,
-    DeleteDecoderManifestResponseTypeDef,
-    DeleteFleetResponseTypeDef,
-    DeleteModelManifestResponseTypeDef,
-    DeleteSignalCatalogResponseTypeDef,
-    DeleteVehicleResponseTypeDef,
-    GetDecoderManifestResponseTypeDef,
-    GetFleetResponseTypeDef,
-    GetModelManifestResponseTypeDef,
-    GetVehicleResponseTypeDef,
-    ImportDecoderManifestResponseTypeDef,
-    ImportSignalCatalogResponseTypeDef,
-    ListFleetsForVehicleResponseTypeDef,
-    ListVehiclesInFleetResponseTypeDef,
     UpdateCampaignResponseTypeDef,
     UpdateDecoderManifestResponseTypeDef,
+    UpdateFleetRequestRequestTypeDef,
     UpdateFleetResponseTypeDef,
+    UpdateModelManifestRequestRequestTypeDef,
     UpdateModelManifestResponseTypeDef,
     UpdateSignalCatalogResponseTypeDef,
+    UpdateVehicleRequestRequestTypeDef,
     UpdateVehicleResponseTypeDef,
+    BatchCreateVehicleResponseTypeDef,
     BatchUpdateVehicleRequestRequestTypeDef,
     BatchUpdateVehicleResponseTypeDef,
     ListCampaignsResponseTypeDef,
     NetworkFileDefinitionTypeDef,
     GetLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     CollectionSchemeTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateModelManifestRequestRequestTypeDef,
     CreateVehicleRequestItemTypeDef,
     CreateVehicleRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataDestinationConfigTypeDef,
     ListDecoderManifestsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ImportSignalCatalogRequestRequestTypeDef,
     GetRegisterAccountStatusResponseTypeDef,
     GetSignalCatalogResponseTypeDef,
-    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
-    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
-    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
-    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-    ListVehiclesRequestListVehiclesPaginateTypeDef,
     GetVehicleStatusResponseTypeDef,
     ListModelManifestsResponseTypeDef,
     ListSignalCatalogsResponseTypeDef,
     ListVehiclesResponseTypeDef,
     NetworkInterfaceTypeDef,
     NodeTypeDef,
     SignalDecoderTypeDef,
     RegisterAccountRequestRequestTypeDef,
     RegisterAccountResponseTypeDef,
     ImportDecoderManifestRequestRequestTypeDef,
+    BatchCreateVehicleRequestRequestTypeDef,
     CreateCampaignRequestRequestTypeDef,
     GetCampaignResponseTypeDef,
-    BatchCreateVehicleRequestRequestTypeDef,
     ListDecoderManifestNetworkInterfacesResponseTypeDef,
     CreateSignalCatalogRequestRequestTypeDef,
     ListModelManifestNodesResponseTypeDef,
     ListSignalCatalogNodesResponseTypeDef,
     UpdateSignalCatalogRequestRequestTypeDef,
     CreateDecoderManifestRequestRequestTypeDef,
     ListDecoderManifestSignalsResponseTypeDef,
@@ -514,43 +519,43 @@
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/setup.py` & `types-aiobotocore-iotfleetwise-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotfleetwise.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotfleetwise",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotfleetwise"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTFleetWise 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTFleetWise 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/"
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__init__.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__init__.pyi` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/__main__.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTFleetWise 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTFleetWise 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise\nOther"
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/client.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -53,14 +53,15 @@
     CreateCampaignResponseTypeDef,
     CreateDecoderManifestResponseTypeDef,
     CreateFleetResponseTypeDef,
     CreateModelManifestResponseTypeDef,
     CreateSignalCatalogResponseTypeDef,
     CreateVehicleRequestItemTypeDef,
     CreateVehicleResponseTypeDef,
+    DataDestinationConfigTypeDef,
     DeleteCampaignResponseTypeDef,
     DeleteDecoderManifestResponseTypeDef,
     DeleteFleetResponseTypeDef,
     DeleteModelManifestResponseTypeDef,
     DeleteSignalCatalogResponseTypeDef,
     DeleteVehicleResponseTypeDef,
     FormattedVssTypeDef,
@@ -211,15 +212,16 @@
         postTriggerCollectionDuration: int = ...,
         diagnosticsMode: DiagnosticsModeType = ...,
         spoolingMode: SpoolingModeType = ...,
         compression: CompressionType = ...,
         priority: int = ...,
         signalsToCollect: Sequence[SignalInformationTypeDef] = ...,
         dataExtraDimensions: Sequence[str] = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        dataDestinationConfigs: Sequence[DataDestinationConfigTypeDef] = ...
     ) -> CreateCampaignResponseTypeDef:
         """
         Creates an orchestration of data collection rules.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.create_campaign)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#create_campaign)
         """
@@ -619,21 +621,19 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.put_logging_options)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#put_logging_options)
         """
 
     async def register_account(
         self,
         *,
-        timestreamResources: TimestreamResourcesTypeDef,
+        timestreamResources: TimestreamResourcesTypeDef = ...,
         iamResources: IamResourcesTypeDef = ...
     ) -> RegisterAccountResponseTypeDef:
         """
-        Registers your Amazon Web Services account, IAM, and Amazon Timestream resources
-        so Amazon Web Services IoT FleetWise can transfer your vehicle data to the
-        Amazon Web Services Cloud.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.register_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#register_account)
         """
 
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/client.pyi` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -53,14 +53,15 @@
     CreateCampaignResponseTypeDef,
     CreateDecoderManifestResponseTypeDef,
     CreateFleetResponseTypeDef,
     CreateModelManifestResponseTypeDef,
     CreateSignalCatalogResponseTypeDef,
     CreateVehicleRequestItemTypeDef,
     CreateVehicleResponseTypeDef,
+    DataDestinationConfigTypeDef,
     DeleteCampaignResponseTypeDef,
     DeleteDecoderManifestResponseTypeDef,
     DeleteFleetResponseTypeDef,
     DeleteModelManifestResponseTypeDef,
     DeleteSignalCatalogResponseTypeDef,
     DeleteVehicleResponseTypeDef,
     FormattedVssTypeDef,
@@ -201,15 +202,16 @@
         postTriggerCollectionDuration: int = ...,
         diagnosticsMode: DiagnosticsModeType = ...,
         spoolingMode: SpoolingModeType = ...,
         compression: CompressionType = ...,
         priority: int = ...,
         signalsToCollect: Sequence[SignalInformationTypeDef] = ...,
         dataExtraDimensions: Sequence[str] = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        dataDestinationConfigs: Sequence[DataDestinationConfigTypeDef] = ...
     ) -> CreateCampaignResponseTypeDef:
         """
         Creates an orchestration of data collection rules.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.create_campaign)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#create_campaign)
         """
@@ -570,21 +572,19 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.put_logging_options)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#put_logging_options)
         """
     async def register_account(
         self,
         *,
-        timestreamResources: TimestreamResourcesTypeDef,
+        timestreamResources: TimestreamResourcesTypeDef = ...,
         iamResources: IamResourcesTypeDef = ...
     ) -> RegisterAccountResponseTypeDef:
         """
-        Registers your Amazon Web Services account, IAM, and Amazon Timestream resources
-        so Amazon Web Services IoT FleetWise can transfer your vehicle data to the
-        Amazon Web Services Cloud.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Client.register_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/client/#register_account)
         """
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds to or modifies the tags of the given resource.
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/literals.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "CampaignStatusType",
     "CompressionType",
+    "DataFormatType",
     "DiagnosticsModeType",
     "GetVehicleStatusPaginatorName",
     "ListCampaignsPaginatorName",
     "ListDecoderManifestNetworkInterfacesPaginatorName",
     "ListDecoderManifestSignalsPaginatorName",
     "ListDecoderManifestsPaginatorName",
     "ListFleetsForVehiclePaginatorName",
@@ -39,14 +40,15 @@
     "LogTypeType",
     "ManifestStatusType",
     "NetworkInterfaceTypeType",
     "NodeDataTypeType",
     "RegistrationStatusType",
     "SignalDecoderTypeType",
     "SpoolingModeType",
+    "StorageCompressionFormatType",
     "TriggerModeType",
     "UpdateCampaignActionType",
     "UpdateModeType",
     "VehicleAssociationBehaviorType",
     "VehicleStateType",
     "IoTFleetWiseServiceName",
     "ServiceName",
@@ -54,14 +56,15 @@
     "PaginatorName",
     "RegionName",
 )
 
 
 CampaignStatusType = Literal["CREATING", "RUNNING", "SUSPENDED", "WAITING_FOR_APPROVAL"]
 CompressionType = Literal["OFF", "SNAPPY"]
+DataFormatType = Literal["JSON", "PARQUET"]
 DiagnosticsModeType = Literal["OFF", "SEND_ACTIVE_DTCS"]
 GetVehicleStatusPaginatorName = Literal["get_vehicle_status"]
 ListCampaignsPaginatorName = Literal["list_campaigns"]
 ListDecoderManifestNetworkInterfacesPaginatorName = Literal[
     "list_decoder_manifest_network_interfaces"
 ]
 ListDecoderManifestSignalsPaginatorName = Literal["list_decoder_manifest_signals"]
@@ -107,14 +110,15 @@
     "UNKNOWN",
 ]
 RegistrationStatusType = Literal[
     "REGISTRATION_FAILURE", "REGISTRATION_PENDING", "REGISTRATION_SUCCESS"
 ]
 SignalDecoderTypeType = Literal["CAN_SIGNAL", "OBD_SIGNAL"]
 SpoolingModeType = Literal["OFF", "TO_DISK"]
+StorageCompressionFormatType = Literal["GZIP", "NONE"]
 TriggerModeType = Literal["ALWAYS", "RISING_EDGE"]
 UpdateCampaignActionType = Literal["APPROVE", "RESUME", "SUSPEND", "UPDATE"]
 UpdateModeType = Literal["Merge", "Overwrite"]
 VehicleAssociationBehaviorType = Literal["CreateIotThing", "ValidateIotThingExists"]
 VehicleStateType = Literal["CREATED", "DELETING", "HEALTHY", "READY", "SUSPENDED"]
 IoTFleetWiseServiceName = Literal["iotfleetwise"]
 ServiceName = Literal[
@@ -175,14 +179,15 @@
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
@@ -261,14 +266,15 @@
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
@@ -279,14 +285,15 @@
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
@@ -322,14 +329,15 @@
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
@@ -348,16 +356,19 @@
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
@@ -441,15 +452,17 @@
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/literals.pyi` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -17,14 +17,15 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "CampaignStatusType",
     "CompressionType",
+    "DataFormatType",
     "DiagnosticsModeType",
     "GetVehicleStatusPaginatorName",
     "ListCampaignsPaginatorName",
     "ListDecoderManifestNetworkInterfacesPaginatorName",
     "ListDecoderManifestSignalsPaginatorName",
     "ListDecoderManifestsPaginatorName",
     "ListFleetsForVehiclePaginatorName",
@@ -38,28 +39,30 @@
     "LogTypeType",
     "ManifestStatusType",
     "NetworkInterfaceTypeType",
     "NodeDataTypeType",
     "RegistrationStatusType",
     "SignalDecoderTypeType",
     "SpoolingModeType",
+    "StorageCompressionFormatType",
     "TriggerModeType",
     "UpdateCampaignActionType",
     "UpdateModeType",
     "VehicleAssociationBehaviorType",
     "VehicleStateType",
     "IoTFleetWiseServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 CampaignStatusType = Literal["CREATING", "RUNNING", "SUSPENDED", "WAITING_FOR_APPROVAL"]
 CompressionType = Literal["OFF", "SNAPPY"]
+DataFormatType = Literal["JSON", "PARQUET"]
 DiagnosticsModeType = Literal["OFF", "SEND_ACTIVE_DTCS"]
 GetVehicleStatusPaginatorName = Literal["get_vehicle_status"]
 ListCampaignsPaginatorName = Literal["list_campaigns"]
 ListDecoderManifestNetworkInterfacesPaginatorName = Literal[
     "list_decoder_manifest_network_interfaces"
 ]
 ListDecoderManifestSignalsPaginatorName = Literal["list_decoder_manifest_signals"]
@@ -105,14 +108,15 @@
     "UNKNOWN",
 ]
 RegistrationStatusType = Literal[
     "REGISTRATION_FAILURE", "REGISTRATION_PENDING", "REGISTRATION_SUCCESS"
 ]
 SignalDecoderTypeType = Literal["CAN_SIGNAL", "OBD_SIGNAL"]
 SpoolingModeType = Literal["OFF", "TO_DISK"]
+StorageCompressionFormatType = Literal["GZIP", "NONE"]
 TriggerModeType = Literal["ALWAYS", "RISING_EDGE"]
 UpdateCampaignActionType = Literal["APPROVE", "RESUME", "SUSPEND", "UPDATE"]
 UpdateModeType = Literal["Merge", "Overwrite"]
 VehicleAssociationBehaviorType = Literal["CreateIotThing", "ValidateIotThingExists"]
 VehicleStateType = Literal["CREATED", "DELETING", "HEALTHY", "READY", "SUSPENDED"]
 IoTFleetWiseServiceName = Literal["iotfleetwise"]
 ServiceName = Literal[
@@ -173,14 +177,15 @@
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
@@ -259,14 +264,15 @@
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
@@ -277,14 +283,15 @@
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
@@ -320,14 +327,15 @@
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
@@ -346,16 +354,19 @@
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
@@ -439,15 +450,17 @@
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/paginator.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -40,16 +40,15 @@
         list_model_manifests_paginator: ListModelManifestsPaginator = client.get_paginator("list_model_manifests")
         list_signal_catalog_nodes_paginator: ListSignalCatalogNodesPaginator = client.get_paginator("list_signal_catalog_nodes")
         list_signal_catalogs_paginator: ListSignalCatalogsPaginator = client.get_paginator("list_signal_catalogs")
         list_vehicles_paginator: ListVehiclesPaginator = client.get_paginator("list_vehicles")
         list_vehicles_in_fleet_paginator: ListVehiclesInFleetPaginator = client.get_paginator("list_vehicles_in_fleet")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetVehicleStatusResponseTypeDef,
     ListCampaignsResponseTypeDef,
@@ -63,20 +62,14 @@
     ListSignalCatalogNodesResponseTypeDef,
     ListSignalCatalogsResponseTypeDef,
     ListVehiclesInFleetResponseTypeDef,
     ListVehiclesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetVehicleStatusPaginator",
     "ListCampaignsPaginator",
     "ListDecoderManifestNetworkInterfacesPaginator",
     "ListDecoderManifestSignalsPaginator",
     "ListDecoderManifestsPaginator",
     "ListFleetsPaginator",
@@ -85,211 +78,196 @@
     "ListModelManifestsPaginator",
     "ListSignalCatalogNodesPaginator",
     "ListSignalCatalogsPaginator",
     "ListVehiclesPaginator",
     "ListVehiclesInFleetPaginator",
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
 class GetVehicleStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.GetVehicleStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#getvehiclestatuspaginator)
     """
 
     def paginate(
-        self, *, vehicleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, vehicleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetVehicleStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.GetVehicleStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#getvehiclestatuspaginator)
         """
 
-
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listcampaignspaginator)
     """
 
     def paginate(
-        self, *, status: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, status: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listcampaignspaginator)
         """
 
-
 class ListDecoderManifestNetworkInterfacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestNetworkInterfaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestnetworkinterfacespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestNetworkInterfacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestNetworkInterfaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestnetworkinterfacespaginator)
         """
 
-
 class ListDecoderManifestSignalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestSignals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestsignalspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestSignalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestSignals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestsignalspaginator)
         """
 
-
 class ListDecoderManifestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestspaginator)
     """
 
     def paginate(
-        self, *, modelManifestArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, modelManifestArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestspaginator)
         """
 
-
 class ListFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetspaginator)
         """
 
-
 class ListFleetsForVehiclePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleetsForVehicle)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetsforvehiclepaginator)
     """
 
     def paginate(
-        self, *, vehicleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, vehicleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsForVehicleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleetsForVehicle.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetsforvehiclepaginator)
         """
 
-
 class ListModelManifestNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifestNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestnodespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelManifestNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifestNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestnodespaginator)
         """
 
-
 class ListModelManifestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestspaginator)
     """
 
     def paginate(
-        self, *, signalCatalogArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, signalCatalogArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelManifestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestspaginator)
         """
 
-
 class ListSignalCatalogNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalognodespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalCatalogNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalognodespaginator)
         """
 
-
 class ListSignalCatalogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalogspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalCatalogsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalogspaginator)
         """
 
-
 class ListVehiclesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehicles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclespaginator)
     """
 
     def paginate(
-        self, *, modelManifestArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, modelManifestArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVehiclesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehicles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclespaginator)
         """
 
-
 class ListVehiclesInFleetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehiclesInFleet)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclesinfleetpaginator)
     """
 
     def paginate(
-        self, *, fleetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, fleetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVehiclesInFleetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehiclesInFleet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclesinfleetpaginator)
         """
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/paginator.pyi` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -40,16 +40,15 @@
         list_model_manifests_paginator: ListModelManifestsPaginator = client.get_paginator("list_model_manifests")
         list_signal_catalog_nodes_paginator: ListSignalCatalogNodesPaginator = client.get_paginator("list_signal_catalog_nodes")
         list_signal_catalogs_paginator: ListSignalCatalogsPaginator = client.get_paginator("list_signal_catalogs")
         list_vehicles_paginator: ListVehiclesPaginator = client.get_paginator("list_vehicles")
         list_vehicles_in_fleet_paginator: ListVehiclesInFleetPaginator = client.get_paginator("list_vehicles_in_fleet")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetVehicleStatusResponseTypeDef,
     ListCampaignsResponseTypeDef,
@@ -63,19 +62,14 @@
     ListSignalCatalogNodesResponseTypeDef,
     ListSignalCatalogsResponseTypeDef,
     ListVehiclesInFleetResponseTypeDef,
     ListVehiclesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetVehicleStatusPaginator",
     "ListCampaignsPaginator",
     "ListDecoderManifestNetworkInterfacesPaginator",
     "ListDecoderManifestSignalsPaginator",
     "ListDecoderManifestsPaginator",
     "ListFleetsPaginator",
@@ -84,196 +78,211 @@
     "ListModelManifestsPaginator",
     "ListSignalCatalogNodesPaginator",
     "ListSignalCatalogsPaginator",
     "ListVehiclesPaginator",
     "ListVehiclesInFleetPaginator",
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
 class GetVehicleStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.GetVehicleStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#getvehiclestatuspaginator)
     """
 
     def paginate(
-        self, *, vehicleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, vehicleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetVehicleStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.GetVehicleStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#getvehiclestatuspaginator)
         """
 
+
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listcampaignspaginator)
     """
 
     def paginate(
-        self, *, status: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, status: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listcampaignspaginator)
         """
 
+
 class ListDecoderManifestNetworkInterfacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestNetworkInterfaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestnetworkinterfacespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestNetworkInterfacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestNetworkInterfaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestnetworkinterfacespaginator)
         """
 
+
 class ListDecoderManifestSignalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestSignals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestsignalspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestSignalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifestSignals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestsignalspaginator)
         """
 
+
 class ListDecoderManifestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestspaginator)
     """
 
     def paginate(
-        self, *, modelManifestArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, modelManifestArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDecoderManifestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListDecoderManifests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listdecodermanifestspaginator)
         """
 
+
 class ListFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetspaginator)
         """
 
+
 class ListFleetsForVehiclePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleetsForVehicle)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetsforvehiclepaginator)
     """
 
     def paginate(
-        self, *, vehicleName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, vehicleName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsForVehicleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListFleetsForVehicle.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listfleetsforvehiclepaginator)
         """
 
+
 class ListModelManifestNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifestNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestnodespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelManifestNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifestNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestnodespaginator)
         """
 
+
 class ListModelManifestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestspaginator)
     """
 
     def paginate(
-        self, *, signalCatalogArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, signalCatalogArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListModelManifestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListModelManifests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listmodelmanifestspaginator)
         """
 
+
 class ListSignalCatalogNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalognodespaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalCatalogNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalognodespaginator)
         """
 
+
 class ListSignalCatalogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalogspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalCatalogsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListSignalCatalogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listsignalcatalogspaginator)
         """
 
+
 class ListVehiclesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehicles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclespaginator)
     """
 
     def paginate(
-        self, *, modelManifestArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, modelManifestArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVehiclesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehicles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclespaginator)
         """
 
+
 class ListVehiclesInFleetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehiclesInFleet)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclesinfleetpaginator)
     """
 
     def paginate(
-        self, *, fleetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, fleetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVehiclesInFleetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise.Paginator.ListVehiclesInFleet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/paginators/#listvehiclesinfleetpaginator)
         """
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/type_defs.py` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,22 +16,24 @@
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     CampaignStatusType,
     CompressionType,
+    DataFormatType,
     DiagnosticsModeType,
     LogTypeType,
     ManifestStatusType,
     NetworkInterfaceTypeType,
     NodeDataTypeType,
     RegistrationStatusType,
     SignalDecoderTypeType,
     SpoolingModeType,
+    StorageCompressionFormatType,
     TriggerModeType,
     UpdateCampaignActionType,
     UpdateModeType,
     VehicleAssociationBehaviorType,
     VehicleStateType,
 )
 
@@ -43,147 +45,150 @@
 
 __all__ = (
     "ActuatorTypeDef",
     "AssociateVehicleFleetRequestRequestTypeDef",
     "AttributeTypeDef",
     "CreateVehicleErrorTypeDef",
     "CreateVehicleResponseItemTypeDef",
-    "ResponseMetadataTypeDef",
     "UpdateVehicleRequestItemTypeDef",
     "UpdateVehicleErrorTypeDef",
     "UpdateVehicleResponseItemTypeDef",
     "BranchTypeDef",
     "CampaignSummaryTypeDef",
     "CanDbcDefinitionTypeDef",
     "CanInterfaceTypeDef",
     "CanSignalTypeDef",
     "CloudWatchLogDeliveryOptionsTypeDef",
     "ConditionBasedCollectionSchemeTypeDef",
     "TimeBasedCollectionSchemeTypeDef",
     "SignalInformationTypeDef",
     "TagTypeDef",
+    "CreateCampaignResponseTypeDef",
+    "CreateDecoderManifestResponseTypeDef",
+    "CreateFleetResponseTypeDef",
+    "CreateModelManifestResponseTypeDef",
+    "CreateSignalCatalogResponseTypeDef",
+    "CreateVehicleResponseTypeDef",
+    "S3ConfigTypeDef",
+    "TimestreamConfigTypeDef",
     "DecoderManifestSummaryTypeDef",
     "DeleteCampaignRequestRequestTypeDef",
+    "DeleteCampaignResponseTypeDef",
     "DeleteDecoderManifestRequestRequestTypeDef",
+    "DeleteDecoderManifestResponseTypeDef",
     "DeleteFleetRequestRequestTypeDef",
+    "DeleteFleetResponseTypeDef",
     "DeleteModelManifestRequestRequestTypeDef",
+    "DeleteModelManifestResponseTypeDef",
     "DeleteSignalCatalogRequestRequestTypeDef",
+    "DeleteSignalCatalogResponseTypeDef",
     "DeleteVehicleRequestRequestTypeDef",
+    "DeleteVehicleResponseTypeDef",
     "DisassociateVehicleFleetRequestRequestTypeDef",
     "FleetSummaryTypeDef",
     "FormattedVssTypeDef",
     "GetCampaignRequestRequestTypeDef",
     "GetDecoderManifestRequestRequestTypeDef",
+    "GetDecoderManifestResponseTypeDef",
     "GetFleetRequestRequestTypeDef",
+    "GetFleetResponseTypeDef",
     "GetModelManifestRequestRequestTypeDef",
+    "GetModelManifestResponseTypeDef",
     "IamRegistrationResponseTypeDef",
     "TimestreamRegistrationResponseTypeDef",
     "GetSignalCatalogRequestRequestTypeDef",
     "NodeCountsTypeDef",
     "GetVehicleRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetVehicleResponseTypeDef",
+    "GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
     "GetVehicleStatusRequestRequestTypeDef",
     "VehicleStatusTypeDef",
     "IamResourcesTypeDef",
+    "ImportDecoderManifestResponseTypeDef",
+    "ImportSignalCatalogResponseTypeDef",
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
     "ListCampaignsRequestRequestTypeDef",
+    "ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
     "ListDecoderManifestNetworkInterfacesRequestRequestTypeDef",
+    "ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
     "ListDecoderManifestSignalsRequestRequestTypeDef",
+    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
     "ListDecoderManifestsRequestRequestTypeDef",
+    "ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
     "ListFleetsForVehicleRequestRequestTypeDef",
+    "ListFleetsForVehicleResponseTypeDef",
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     "ListFleetsRequestRequestTypeDef",
+    "ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
     "ListModelManifestNodesRequestRequestTypeDef",
+    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
     "ListModelManifestsRequestRequestTypeDef",
     "ModelManifestSummaryTypeDef",
+    "ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
     "ListSignalCatalogNodesRequestRequestTypeDef",
+    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
     "ListSignalCatalogsRequestRequestTypeDef",
     "SignalCatalogSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
     "ListVehiclesInFleetRequestRequestTypeDef",
+    "ListVehiclesInFleetResponseTypeDef",
+    "ListVehiclesRequestListVehiclesPaginateTypeDef",
     "ListVehiclesRequestRequestTypeDef",
     "VehicleSummaryTypeDef",
     "ObdInterfaceTypeDef",
     "SensorTypeDef",
     "ObdSignalTypeDef",
+    "PaginatorConfigTypeDef",
     "TimestreamResourcesTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCampaignRequestRequestTypeDef",
-    "UpdateFleetRequestRequestTypeDef",
-    "UpdateModelManifestRequestRequestTypeDef",
-    "UpdateVehicleRequestRequestTypeDef",
-    "BatchCreateVehicleResponseTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "CreateDecoderManifestResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "CreateModelManifestResponseTypeDef",
-    "CreateSignalCatalogResponseTypeDef",
-    "CreateVehicleResponseTypeDef",
-    "DeleteCampaignResponseTypeDef",
-    "DeleteDecoderManifestResponseTypeDef",
-    "DeleteFleetResponseTypeDef",
-    "DeleteModelManifestResponseTypeDef",
-    "DeleteSignalCatalogResponseTypeDef",
-    "DeleteVehicleResponseTypeDef",
-    "GetDecoderManifestResponseTypeDef",
-    "GetFleetResponseTypeDef",
-    "GetModelManifestResponseTypeDef",
-    "GetVehicleResponseTypeDef",
-    "ImportDecoderManifestResponseTypeDef",
-    "ImportSignalCatalogResponseTypeDef",
-    "ListFleetsForVehicleResponseTypeDef",
-    "ListVehiclesInFleetResponseTypeDef",
     "UpdateCampaignResponseTypeDef",
     "UpdateDecoderManifestResponseTypeDef",
+    "UpdateFleetRequestRequestTypeDef",
     "UpdateFleetResponseTypeDef",
+    "UpdateModelManifestRequestRequestTypeDef",
     "UpdateModelManifestResponseTypeDef",
     "UpdateSignalCatalogResponseTypeDef",
+    "UpdateVehicleRequestRequestTypeDef",
     "UpdateVehicleResponseTypeDef",
+    "BatchCreateVehicleResponseTypeDef",
     "BatchUpdateVehicleRequestRequestTypeDef",
     "BatchUpdateVehicleResponseTypeDef",
     "ListCampaignsResponseTypeDef",
     "NetworkFileDefinitionTypeDef",
     "GetLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "CollectionSchemeTypeDef",
     "CreateFleetRequestRequestTypeDef",
     "CreateModelManifestRequestRequestTypeDef",
     "CreateVehicleRequestItemTypeDef",
     "CreateVehicleRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "DataDestinationConfigTypeDef",
     "ListDecoderManifestsResponseTypeDef",
     "ListFleetsResponseTypeDef",
     "ImportSignalCatalogRequestRequestTypeDef",
     "GetRegisterAccountStatusResponseTypeDef",
     "GetSignalCatalogResponseTypeDef",
-    "GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    "ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    "ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
-    "ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    "ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
-    "ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
-    "ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    "ListVehiclesRequestListVehiclesPaginateTypeDef",
     "GetVehicleStatusResponseTypeDef",
     "ListModelManifestsResponseTypeDef",
     "ListSignalCatalogsResponseTypeDef",
     "ListVehiclesResponseTypeDef",
     "NetworkInterfaceTypeDef",
     "NodeTypeDef",
     "SignalDecoderTypeDef",
     "RegisterAccountRequestRequestTypeDef",
     "RegisterAccountResponseTypeDef",
     "ImportDecoderManifestRequestRequestTypeDef",
+    "BatchCreateVehicleRequestRequestTypeDef",
     "CreateCampaignRequestRequestTypeDef",
     "GetCampaignResponseTypeDef",
-    "BatchCreateVehicleRequestRequestTypeDef",
     "ListDecoderManifestNetworkInterfacesResponseTypeDef",
     "CreateSignalCatalogRequestRequestTypeDef",
     "ListModelManifestNodesResponseTypeDef",
     "ListSignalCatalogNodesResponseTypeDef",
     "UpdateSignalCatalogRequestRequestTypeDef",
     "CreateDecoderManifestRequestRequestTypeDef",
     "ListDecoderManifestSignalsResponseTypeDef",
@@ -202,14 +207,16 @@
     {
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
         "assignedValue": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 
 class ActuatorTypeDef(_RequiredActuatorTypeDef, _OptionalActuatorTypeDef):
     pass
@@ -236,14 +243,16 @@
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
         "assignedValue": str,
         "defaultValue": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 
 class AttributeTypeDef(_RequiredAttributeTypeDef, _OptionalAttributeTypeDef):
     pass
@@ -265,25 +274,14 @@
         "vehicleName": str,
         "arn": str,
         "thingArn": str,
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
 _RequiredUpdateVehicleRequestItemTypeDef = TypedDict(
     "_RequiredUpdateVehicleRequestItemTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalUpdateVehicleRequestItemTypeDef = TypedDict(
@@ -329,14 +327,16 @@
         "fullyQualifiedName": str,
     },
 )
 _OptionalBranchTypeDef = TypedDict(
     "_OptionalBranchTypeDef",
     {
         "description": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 
 class BranchTypeDef(_RequiredBranchTypeDef, _OptionalBranchTypeDef):
     pass
@@ -509,14 +509,98 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDecoderManifestResponseTypeDef = TypedDict(
+    "CreateDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateModelManifestResponseTypeDef = TypedDict(
+    "CreateModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSignalCatalogResponseTypeDef = TypedDict(
+    "CreateSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVehicleResponseTypeDef = TypedDict(
+    "CreateVehicleResponseTypeDef",
+    {
+        "vehicleName": str,
+        "arn": str,
+        "thingArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredS3ConfigTypeDef = TypedDict(
+    "_RequiredS3ConfigTypeDef",
+    {
+        "bucketArn": str,
+    },
+)
+_OptionalS3ConfigTypeDef = TypedDict(
+    "_OptionalS3ConfigTypeDef",
+    {
+        "dataFormat": DataFormatType,
+        "storageCompressionFormat": StorageCompressionFormatType,
+        "prefix": str,
+    },
+    total=False,
+)
+
+
+class S3ConfigTypeDef(_RequiredS3ConfigTypeDef, _OptionalS3ConfigTypeDef):
+    pass
+
+
+TimestreamConfigTypeDef = TypedDict(
+    "TimestreamConfigTypeDef",
+    {
+        "timestreamTableArn": str,
+        "executionRoleArn": str,
+    },
+)
+
 _RequiredDecoderManifestSummaryTypeDef = TypedDict(
     "_RequiredDecoderManifestSummaryTypeDef",
     {
         "creationTime": datetime,
         "lastModificationTime": datetime,
     },
 )
@@ -542,49 +626,103 @@
 DeleteCampaignRequestRequestTypeDef = TypedDict(
     "DeleteCampaignRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteCampaignResponseTypeDef = TypedDict(
+    "DeleteCampaignResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDecoderManifestRequestRequestTypeDef = TypedDict(
     "DeleteDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteDecoderManifestResponseTypeDef = TypedDict(
+    "DeleteDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFleetRequestRequestTypeDef = TypedDict(
     "DeleteFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 
+DeleteFleetResponseTypeDef = TypedDict(
+    "DeleteFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteModelManifestRequestRequestTypeDef = TypedDict(
     "DeleteModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteModelManifestResponseTypeDef = TypedDict(
+    "DeleteModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSignalCatalogRequestRequestTypeDef = TypedDict(
     "DeleteSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteSignalCatalogResponseTypeDef = TypedDict(
+    "DeleteSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVehicleRequestRequestTypeDef = TypedDict(
     "DeleteVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 
+DeleteVehicleResponseTypeDef = TypedDict(
+    "DeleteVehicleResponseTypeDef",
+    {
+        "vehicleName": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateVehicleFleetRequestRequestTypeDef = TypedDict(
     "DisassociateVehicleFleetRequestRequestTypeDef",
     {
         "vehicleName": str,
         "fleetId": str,
     },
 )
@@ -630,28 +768,69 @@
 GetDecoderManifestRequestRequestTypeDef = TypedDict(
     "GetDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetDecoderManifestResponseTypeDef = TypedDict(
+    "GetDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "description": str,
+        "modelManifestArn": str,
+        "status": ManifestStatusType,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFleetRequestRequestTypeDef = TypedDict(
     "GetFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 
+GetFleetResponseTypeDef = TypedDict(
+    "GetFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "description": str,
+        "signalCatalogArn": str,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetModelManifestRequestRequestTypeDef = TypedDict(
     "GetModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetModelManifestResponseTypeDef = TypedDict(
+    "GetModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "description": str,
+        "signalCatalogArn": str,
+        "status": ManifestStatusType,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredIamRegistrationResponseTypeDef = TypedDict(
     "_RequiredIamRegistrationResponseTypeDef",
     {
         "roleArn": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -717,24 +896,50 @@
 GetVehicleRequestRequestTypeDef = TypedDict(
     "GetVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetVehicleResponseTypeDef = TypedDict(
+    "GetVehicleResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "vehicleName": str,
+        "arn": str,
+        "modelManifestArn": str,
+        "decoderManifestArn": str,
+        "attributes": Dict[str, str],
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
+    {
+        "vehicleName": str,
+    },
+)
+_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef(
+    _RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
+    _OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetVehicleStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetVehicleStatusRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalGetVehicleStatusRequestRequestTypeDef = TypedDict(
@@ -766,24 +971,73 @@
 IamResourcesTypeDef = TypedDict(
     "IamResourcesTypeDef",
     {
         "roleArn": str,
     },
 )
 
+ImportDecoderManifestResponseTypeDef = TypedDict(
+    "ImportDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportSignalCatalogResponseTypeDef = TypedDict(
+    "ImportSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
+    {
+        "status": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": str,
     },
     total=False,
 )
 
+_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
+    "_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
+    "_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef(
+    _RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
+    _OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef = TypedDict(
     "_RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListDecoderManifestNetworkInterfacesRequestRequestTypeDef = TypedDict(
@@ -799,14 +1053,36 @@
 class ListDecoderManifestNetworkInterfacesRequestRequestTypeDef(
     _RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
     _OptionalListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
+    "_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
+    "_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef(
+    _RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
+    _OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDecoderManifestSignalsRequestRequestTypeDef = TypedDict(
     "_RequiredListDecoderManifestSignalsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListDecoderManifestSignalsRequestRequestTypeDef = TypedDict(
@@ -822,24 +1098,55 @@
 class ListDecoderManifestSignalsRequestRequestTypeDef(
     _RequiredListDecoderManifestSignalsRequestRequestTypeDef,
     _OptionalListDecoderManifestSignalsRequestRequestTypeDef,
 ):
     pass
 
 
+ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef = TypedDict(
+    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
+    {
+        "modelManifestArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDecoderManifestsRequestRequestTypeDef = TypedDict(
     "ListDecoderManifestsRequestRequestTypeDef",
     {
         "modelManifestArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
+    "_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
+    {
+        "vehicleName": str,
+    },
+)
+_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
+    "_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef(
+    _RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
+    _OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFleetsForVehicleRequestRequestTypeDef = TypedDict(
     "_RequiredListFleetsForVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalListFleetsForVehicleRequestRequestTypeDef = TypedDict(
@@ -855,23 +1162,62 @@
 class ListFleetsForVehicleRequestRequestTypeDef(
     _RequiredListFleetsForVehicleRequestRequestTypeDef,
     _OptionalListFleetsForVehicleRequestRequestTypeDef,
 ):
     pass
 
 
+ListFleetsForVehicleResponseTypeDef = TypedDict(
+    "ListFleetsForVehicleResponseTypeDef",
+    {
+        "fleets": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsRequestListFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFleetsRequestRequestTypeDef = TypedDict(
     "ListFleetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
+    "_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
+    "_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef(
+    _RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
+    _OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListModelManifestNodesRequestRequestTypeDef = TypedDict(
     "_RequiredListModelManifestNodesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListModelManifestNodesRequestRequestTypeDef = TypedDict(
@@ -887,14 +1233,23 @@
 class ListModelManifestNodesRequestRequestTypeDef(
     _RequiredListModelManifestNodesRequestRequestTypeDef,
     _OptionalListModelManifestNodesRequestRequestTypeDef,
 ):
     pass
 
 
+ListModelManifestsRequestListModelManifestsPaginateTypeDef = TypedDict(
+    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
+    {
+        "signalCatalogArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListModelManifestsRequestRequestTypeDef = TypedDict(
     "ListModelManifestsRequestRequestTypeDef",
     {
         "signalCatalogArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -923,14 +1278,36 @@
 
 class ModelManifestSummaryTypeDef(
     _RequiredModelManifestSummaryTypeDef, _OptionalModelManifestSummaryTypeDef
 ):
     pass
 
 
+_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
+    "_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
+    "_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef(
+    _RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
+    _OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSignalCatalogNodesRequestRequestTypeDef = TypedDict(
     "_RequiredListSignalCatalogNodesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListSignalCatalogNodesRequestRequestTypeDef = TypedDict(
@@ -946,14 +1323,22 @@
 class ListSignalCatalogNodesRequestRequestTypeDef(
     _RequiredListSignalCatalogNodesRequestRequestTypeDef,
     _OptionalListSignalCatalogNodesRequestRequestTypeDef,
 ):
     pass
 
 
+ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef = TypedDict(
+    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSignalCatalogsRequestRequestTypeDef = TypedDict(
     "ListSignalCatalogsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -973,14 +1358,36 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
+    "_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
+    {
+        "fleetId": str,
+    },
+)
+_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
+    "_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef(
+    _RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
+    _OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVehiclesInFleetRequestRequestTypeDef = TypedDict(
     "_RequiredListVehiclesInFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 _OptionalListVehiclesInFleetRequestRequestTypeDef = TypedDict(
@@ -996,14 +1403,32 @@
 class ListVehiclesInFleetRequestRequestTypeDef(
     _RequiredListVehiclesInFleetRequestRequestTypeDef,
     _OptionalListVehiclesInFleetRequestRequestTypeDef,
 ):
     pass
 
 
+ListVehiclesInFleetResponseTypeDef = TypedDict(
+    "ListVehiclesInFleetResponseTypeDef",
+    {
+        "vehicles": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListVehiclesRequestListVehiclesPaginateTypeDef = TypedDict(
+    "ListVehiclesRequestListVehiclesPaginateTypeDef",
+    {
+        "modelManifestArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVehiclesRequestRequestTypeDef = TypedDict(
     "ListVehiclesRequestRequestTypeDef",
     {
         "modelManifestArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1057,14 +1482,16 @@
     "_OptionalSensorTypeDef",
     {
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 
 class SensorTypeDef(_RequiredSensorTypeDef, _OptionalSensorTypeDef):
     pass
@@ -1092,22 +1519,43 @@
 )
 
 
 class ObdSignalTypeDef(_RequiredObdSignalTypeDef, _OptionalObdSignalTypeDef):
     pass
 
 
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
 TimestreamResourcesTypeDef = TypedDict(
     "TimestreamResourcesTypeDef",
     {
         "timestreamDatabaseName": str,
         "timestreamTableName": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1131,14 +1579,33 @@
 
 class UpdateCampaignRequestRequestTypeDef(
     _RequiredUpdateCampaignRequestRequestTypeDef, _OptionalUpdateCampaignRequestRequestTypeDef
 ):
     pass
 
 
+UpdateCampaignResponseTypeDef = TypedDict(
+    "UpdateCampaignResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "status": CampaignStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDecoderManifestResponseTypeDef = TypedDict(
+    "UpdateDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFleetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 _OptionalUpdateFleetRequestRequestTypeDef = TypedDict(
@@ -1152,14 +1619,23 @@
 
 class UpdateFleetRequestRequestTypeDef(
     _RequiredUpdateFleetRequestRequestTypeDef, _OptionalUpdateFleetRequestRequestTypeDef
 ):
     pass
 
 
+UpdateFleetResponseTypeDef = TypedDict(
+    "UpdateFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateModelManifestRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateModelManifestRequestRequestTypeDef = TypedDict(
@@ -1177,299 +1653,71 @@
 class UpdateModelManifestRequestRequestTypeDef(
     _RequiredUpdateModelManifestRequestRequestTypeDef,
     _OptionalUpdateModelManifestRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredUpdateVehicleRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateVehicleRequestRequestTypeDef",
-    {
-        "vehicleName": str,
-    },
-)
-_OptionalUpdateVehicleRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateVehicleRequestRequestTypeDef",
-    {
-        "modelManifestArn": str,
-        "decoderManifestArn": str,
-        "attributes": Mapping[str, str],
-        "attributeUpdateMode": UpdateModeType,
-    },
-    total=False,
-)
-
-
-class UpdateVehicleRequestRequestTypeDef(
-    _RequiredUpdateVehicleRequestRequestTypeDef, _OptionalUpdateVehicleRequestRequestTypeDef
-):
-    pass
-
-
-BatchCreateVehicleResponseTypeDef = TypedDict(
-    "BatchCreateVehicleResponseTypeDef",
-    {
-        "vehicles": List[CreateVehicleResponseItemTypeDef],
-        "errors": List[CreateVehicleErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDecoderManifestResponseTypeDef = TypedDict(
-    "CreateDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelManifestResponseTypeDef = TypedDict(
-    "CreateModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSignalCatalogResponseTypeDef = TypedDict(
-    "CreateSignalCatalogResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVehicleResponseTypeDef = TypedDict(
-    "CreateVehicleResponseTypeDef",
-    {
-        "vehicleName": str,
-        "arn": str,
-        "thingArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCampaignResponseTypeDef = TypedDict(
-    "DeleteCampaignResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDecoderManifestResponseTypeDef = TypedDict(
-    "DeleteDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFleetResponseTypeDef = TypedDict(
-    "DeleteFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteModelManifestResponseTypeDef = TypedDict(
-    "DeleteModelManifestResponseTypeDef",
+UpdateModelManifestResponseTypeDef = TypedDict(
+    "UpdateModelManifestResponseTypeDef",
     {
         "name": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteSignalCatalogResponseTypeDef = TypedDict(
-    "DeleteSignalCatalogResponseTypeDef",
+UpdateSignalCatalogResponseTypeDef = TypedDict(
+    "UpdateSignalCatalogResponseTypeDef",
     {
         "name": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteVehicleResponseTypeDef = TypedDict(
-    "DeleteVehicleResponseTypeDef",
+_RequiredUpdateVehicleRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDecoderManifestResponseTypeDef = TypedDict(
-    "GetDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "description": str,
-        "modelManifestArn": str,
-        "status": ManifestStatusType,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFleetResponseTypeDef = TypedDict(
-    "GetFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "description": str,
-        "signalCatalogArn": str,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-GetModelManifestResponseTypeDef = TypedDict(
-    "GetModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "description": str,
-        "signalCatalogArn": str,
-        "status": ManifestStatusType,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVehicleResponseTypeDef = TypedDict(
-    "GetVehicleResponseTypeDef",
+_OptionalUpdateVehicleRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateVehicleRequestRequestTypeDef",
     {
-        "vehicleName": str,
-        "arn": str,
         "modelManifestArn": str,
         "decoderManifestArn": str,
-        "attributes": Dict[str, str],
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportDecoderManifestResponseTypeDef = TypedDict(
-    "ImportDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSignalCatalogResponseTypeDef = TypedDict(
-    "ImportSignalCatalogResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFleetsForVehicleResponseTypeDef = TypedDict(
-    "ListFleetsForVehicleResponseTypeDef",
-    {
-        "fleets": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVehiclesInFleetResponseTypeDef = TypedDict(
-    "ListVehiclesInFleetResponseTypeDef",
-    {
-        "vehicles": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCampaignResponseTypeDef = TypedDict(
-    "UpdateCampaignResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "status": CampaignStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "attributes": Mapping[str, str],
+        "attributeUpdateMode": UpdateModeType,
     },
+    total=False,
 )
 
-UpdateDecoderManifestResponseTypeDef = TypedDict(
-    "UpdateDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateFleetResponseTypeDef = TypedDict(
-    "UpdateFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateVehicleRequestRequestTypeDef(
+    _RequiredUpdateVehicleRequestRequestTypeDef, _OptionalUpdateVehicleRequestRequestTypeDef
+):
+    pass
 
-UpdateModelManifestResponseTypeDef = TypedDict(
-    "UpdateModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateSignalCatalogResponseTypeDef = TypedDict(
-    "UpdateSignalCatalogResponseTypeDef",
+UpdateVehicleResponseTypeDef = TypedDict(
+    "UpdateVehicleResponseTypeDef",
     {
-        "name": str,
+        "vehicleName": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateVehicleResponseTypeDef = TypedDict(
-    "UpdateVehicleResponseTypeDef",
+BatchCreateVehicleResponseTypeDef = TypedDict(
+    "BatchCreateVehicleResponseTypeDef",
     {
-        "vehicleName": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "vehicles": List[CreateVehicleResponseItemTypeDef],
+        "errors": List[CreateVehicleErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateVehicleRequestRequestTypeDef = TypedDict(
     "BatchUpdateVehicleRequestRequestTypeDef",
     {
         "vehicles": Sequence[UpdateVehicleRequestItemTypeDef],
@@ -1477,24 +1725,24 @@
 )
 
 BatchUpdateVehicleResponseTypeDef = TypedDict(
     "BatchUpdateVehicleResponseTypeDef",
     {
         "vehicles": List[UpdateVehicleResponseItemTypeDef],
         "errors": List[UpdateVehicleErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCampaignsResponseTypeDef = TypedDict(
     "ListCampaignsResponseTypeDef",
     {
         "campaignSummaries": List[CampaignSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFileDefinitionTypeDef = TypedDict(
     "NetworkFileDefinitionTypeDef",
     {
         "canDbc": CanDbcDefinitionTypeDef,
@@ -1502,15 +1750,15 @@
     total=False,
 )
 
 GetLoggingOptionsResponseTypeDef = TypedDict(
     "GetLoggingOptionsResponseTypeDef",
     {
         "cloudWatchLogDelivery": CloudWatchLogDeliveryOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "cloudWatchLogDelivery": CloudWatchLogDeliveryOptionsTypeDef,
@@ -1624,41 +1872,50 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+DataDestinationConfigTypeDef = TypedDict(
+    "DataDestinationConfigTypeDef",
+    {
+        "s3Config": S3ConfigTypeDef,
+        "timestreamConfig": TimestreamConfigTypeDef,
+    },
+    total=False,
+)
+
 ListDecoderManifestsResponseTypeDef = TypedDict(
     "ListDecoderManifestsResponseTypeDef",
     {
         "summaries": List[DecoderManifestSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFleetsResponseTypeDef = TypedDict(
     "ListFleetsResponseTypeDef",
     {
         "fleetSummaries": List[FleetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredImportSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -1687,270 +1944,64 @@
     {
         "customerAccountId": str,
         "accountStatus": RegistrationStatusType,
         "timestreamRegistrationResponse": TimestreamRegistrationResponseTypeDef,
         "iamRegistrationResponse": IamRegistrationResponseTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSignalCatalogResponseTypeDef = TypedDict(
     "GetSignalCatalogResponseTypeDef",
     {
         "name": str,
         "arn": str,
         "description": str,
         "nodeCounts": NodeCountsTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    {
-        "vehicleName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef(
-    _RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-    _OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-):
-    pass
-
-
-ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    {
-        "status": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
-    "_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
-    "_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef(
-    _RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-    _OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
-    "_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
-    "_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef(
-    _RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-    _OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-):
-    pass
-
-
-ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef = TypedDict(
-    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
-    {
-        "modelManifestArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
-    "_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    {
-        "vehicleName": str,
-    },
-)
-_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
-    "_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef(
-    _RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-    _OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-):
-    pass
-
-
-ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
-    "_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
-    "_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef(
-    _RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-    _OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-):
-    pass
-
-
-ListModelManifestsRequestListModelManifestsPaginateTypeDef = TypedDict(
-    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
-    {
-        "signalCatalogArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
-    "_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
-    "_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef(
-    _RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-    _OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-):
-    pass
-
-
-ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef = TypedDict(
-    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
-    "_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    {
-        "fleetId": str,
-    },
-)
-_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
-    "_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef(
-    _RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-    _OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-):
-    pass
-
-
-ListVehiclesRequestListVehiclesPaginateTypeDef = TypedDict(
-    "ListVehiclesRequestListVehiclesPaginateTypeDef",
-    {
-        "modelManifestArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 GetVehicleStatusResponseTypeDef = TypedDict(
     "GetVehicleStatusResponseTypeDef",
     {
         "campaigns": List[VehicleStatusTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListModelManifestsResponseTypeDef = TypedDict(
     "ListModelManifestsResponseTypeDef",
     {
         "summaries": List[ModelManifestSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalCatalogsResponseTypeDef = TypedDict(
     "ListSignalCatalogsResponseTypeDef",
     {
         "summaries": List[SignalCatalogSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVehiclesResponseTypeDef = TypedDict(
     "ListVehiclesResponseTypeDef",
     {
         "vehicleSummaries": List[VehicleSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNetworkInterfaceTypeDef = TypedDict(
     "_RequiredNetworkInterfaceTypeDef",
     {
         "interfaceId": str,
@@ -2000,55 +2051,50 @@
 )
 
 
 class SignalDecoderTypeDef(_RequiredSignalDecoderTypeDef, _OptionalSignalDecoderTypeDef):
     pass
 
 
-_RequiredRegisterAccountRequestRequestTypeDef = TypedDict(
-    "_RequiredRegisterAccountRequestRequestTypeDef",
+RegisterAccountRequestRequestTypeDef = TypedDict(
+    "RegisterAccountRequestRequestTypeDef",
     {
         "timestreamResources": TimestreamResourcesTypeDef,
-    },
-)
-_OptionalRegisterAccountRequestRequestTypeDef = TypedDict(
-    "_OptionalRegisterAccountRequestRequestTypeDef",
-    {
         "iamResources": IamResourcesTypeDef,
     },
     total=False,
 )
 
-
-class RegisterAccountRequestRequestTypeDef(
-    _RequiredRegisterAccountRequestRequestTypeDef, _OptionalRegisterAccountRequestRequestTypeDef
-):
-    pass
-
-
 RegisterAccountResponseTypeDef = TypedDict(
     "RegisterAccountResponseTypeDef",
     {
         "registerAccountStatus": RegistrationStatusType,
         "timestreamResources": TimestreamResourcesTypeDef,
         "iamResources": IamResourcesTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportDecoderManifestRequestRequestTypeDef = TypedDict(
     "ImportDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
         "networkFileDefinitions": Sequence[NetworkFileDefinitionTypeDef],
     },
 )
 
+BatchCreateVehicleRequestRequestTypeDef = TypedDict(
+    "BatchCreateVehicleRequestRequestTypeDef",
+    {
+        "vehicles": Sequence[CreateVehicleRequestItemTypeDef],
+    },
+)
+
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "name": str,
         "signalCatalogArn": str,
         "targetArn": str,
         "collectionScheme": CollectionSchemeTypeDef,
@@ -2064,14 +2110,15 @@
         "diagnosticsMode": DiagnosticsModeType,
         "spoolingMode": SpoolingModeType,
         "compression": CompressionType,
         "priority": int,
         "signalsToCollect": Sequence[SignalInformationTypeDef],
         "dataExtraDimensions": Sequence[str],
         "tags": Sequence[TagTypeDef],
+        "dataDestinationConfigs": Sequence[DataDestinationConfigTypeDef],
     },
     total=False,
 )
 
 
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
@@ -2096,31 +2143,25 @@
         "compression": CompressionType,
         "priority": int,
         "signalsToCollect": List[SignalInformationTypeDef],
         "collectionScheme": CollectionSchemeTypeDef,
         "dataExtraDimensions": List[str],
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchCreateVehicleRequestRequestTypeDef = TypedDict(
-    "BatchCreateVehicleRequestRequestTypeDef",
-    {
-        "vehicles": Sequence[CreateVehicleRequestItemTypeDef],
+        "dataDestinationConfigs": List[DataDestinationConfigTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDecoderManifestNetworkInterfacesResponseTypeDef = TypedDict(
     "ListDecoderManifestNetworkInterfacesResponseTypeDef",
     {
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -2145,24 +2186,24 @@
 
 
 ListModelManifestNodesResponseTypeDef = TypedDict(
     "ListModelManifestNodesResponseTypeDef",
     {
         "nodes": List[NodeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalCatalogNodesResponseTypeDef = TypedDict(
     "ListSignalCatalogNodesResponseTypeDef",
     {
         "nodes": List[NodeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -2214,15 +2255,15 @@
 
 
 ListDecoderManifestSignalsResponseTypeDef = TypedDict(
     "ListDecoderManifestSignalsResponseTypeDef",
     {
         "signalDecoders": List[SignalDecoderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDecoderManifestRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise/type_defs.pyi` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -16,22 +16,24 @@
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     CampaignStatusType,
     CompressionType,
+    DataFormatType,
     DiagnosticsModeType,
     LogTypeType,
     ManifestStatusType,
     NetworkInterfaceTypeType,
     NodeDataTypeType,
     RegistrationStatusType,
     SignalDecoderTypeType,
     SpoolingModeType,
+    StorageCompressionFormatType,
     TriggerModeType,
     UpdateCampaignActionType,
     UpdateModeType,
     VehicleAssociationBehaviorType,
     VehicleStateType,
 )
 
@@ -42,147 +44,150 @@
 
 __all__ = (
     "ActuatorTypeDef",
     "AssociateVehicleFleetRequestRequestTypeDef",
     "AttributeTypeDef",
     "CreateVehicleErrorTypeDef",
     "CreateVehicleResponseItemTypeDef",
-    "ResponseMetadataTypeDef",
     "UpdateVehicleRequestItemTypeDef",
     "UpdateVehicleErrorTypeDef",
     "UpdateVehicleResponseItemTypeDef",
     "BranchTypeDef",
     "CampaignSummaryTypeDef",
     "CanDbcDefinitionTypeDef",
     "CanInterfaceTypeDef",
     "CanSignalTypeDef",
     "CloudWatchLogDeliveryOptionsTypeDef",
     "ConditionBasedCollectionSchemeTypeDef",
     "TimeBasedCollectionSchemeTypeDef",
     "SignalInformationTypeDef",
     "TagTypeDef",
+    "CreateCampaignResponseTypeDef",
+    "CreateDecoderManifestResponseTypeDef",
+    "CreateFleetResponseTypeDef",
+    "CreateModelManifestResponseTypeDef",
+    "CreateSignalCatalogResponseTypeDef",
+    "CreateVehicleResponseTypeDef",
+    "S3ConfigTypeDef",
+    "TimestreamConfigTypeDef",
     "DecoderManifestSummaryTypeDef",
     "DeleteCampaignRequestRequestTypeDef",
+    "DeleteCampaignResponseTypeDef",
     "DeleteDecoderManifestRequestRequestTypeDef",
+    "DeleteDecoderManifestResponseTypeDef",
     "DeleteFleetRequestRequestTypeDef",
+    "DeleteFleetResponseTypeDef",
     "DeleteModelManifestRequestRequestTypeDef",
+    "DeleteModelManifestResponseTypeDef",
     "DeleteSignalCatalogRequestRequestTypeDef",
+    "DeleteSignalCatalogResponseTypeDef",
     "DeleteVehicleRequestRequestTypeDef",
+    "DeleteVehicleResponseTypeDef",
     "DisassociateVehicleFleetRequestRequestTypeDef",
     "FleetSummaryTypeDef",
     "FormattedVssTypeDef",
     "GetCampaignRequestRequestTypeDef",
     "GetDecoderManifestRequestRequestTypeDef",
+    "GetDecoderManifestResponseTypeDef",
     "GetFleetRequestRequestTypeDef",
+    "GetFleetResponseTypeDef",
     "GetModelManifestRequestRequestTypeDef",
+    "GetModelManifestResponseTypeDef",
     "IamRegistrationResponseTypeDef",
     "TimestreamRegistrationResponseTypeDef",
     "GetSignalCatalogRequestRequestTypeDef",
     "NodeCountsTypeDef",
     "GetVehicleRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetVehicleResponseTypeDef",
+    "GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
     "GetVehicleStatusRequestRequestTypeDef",
     "VehicleStatusTypeDef",
     "IamResourcesTypeDef",
+    "ImportDecoderManifestResponseTypeDef",
+    "ImportSignalCatalogResponseTypeDef",
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
     "ListCampaignsRequestRequestTypeDef",
+    "ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
     "ListDecoderManifestNetworkInterfacesRequestRequestTypeDef",
+    "ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
     "ListDecoderManifestSignalsRequestRequestTypeDef",
+    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
     "ListDecoderManifestsRequestRequestTypeDef",
+    "ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
     "ListFleetsForVehicleRequestRequestTypeDef",
+    "ListFleetsForVehicleResponseTypeDef",
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     "ListFleetsRequestRequestTypeDef",
+    "ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
     "ListModelManifestNodesRequestRequestTypeDef",
+    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
     "ListModelManifestsRequestRequestTypeDef",
     "ModelManifestSummaryTypeDef",
+    "ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
     "ListSignalCatalogNodesRequestRequestTypeDef",
+    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
     "ListSignalCatalogsRequestRequestTypeDef",
     "SignalCatalogSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
     "ListVehiclesInFleetRequestRequestTypeDef",
+    "ListVehiclesInFleetResponseTypeDef",
+    "ListVehiclesRequestListVehiclesPaginateTypeDef",
     "ListVehiclesRequestRequestTypeDef",
     "VehicleSummaryTypeDef",
     "ObdInterfaceTypeDef",
     "SensorTypeDef",
     "ObdSignalTypeDef",
+    "PaginatorConfigTypeDef",
     "TimestreamResourcesTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCampaignRequestRequestTypeDef",
-    "UpdateFleetRequestRequestTypeDef",
-    "UpdateModelManifestRequestRequestTypeDef",
-    "UpdateVehicleRequestRequestTypeDef",
-    "BatchCreateVehicleResponseTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "CreateDecoderManifestResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "CreateModelManifestResponseTypeDef",
-    "CreateSignalCatalogResponseTypeDef",
-    "CreateVehicleResponseTypeDef",
-    "DeleteCampaignResponseTypeDef",
-    "DeleteDecoderManifestResponseTypeDef",
-    "DeleteFleetResponseTypeDef",
-    "DeleteModelManifestResponseTypeDef",
-    "DeleteSignalCatalogResponseTypeDef",
-    "DeleteVehicleResponseTypeDef",
-    "GetDecoderManifestResponseTypeDef",
-    "GetFleetResponseTypeDef",
-    "GetModelManifestResponseTypeDef",
-    "GetVehicleResponseTypeDef",
-    "ImportDecoderManifestResponseTypeDef",
-    "ImportSignalCatalogResponseTypeDef",
-    "ListFleetsForVehicleResponseTypeDef",
-    "ListVehiclesInFleetResponseTypeDef",
     "UpdateCampaignResponseTypeDef",
     "UpdateDecoderManifestResponseTypeDef",
+    "UpdateFleetRequestRequestTypeDef",
     "UpdateFleetResponseTypeDef",
+    "UpdateModelManifestRequestRequestTypeDef",
     "UpdateModelManifestResponseTypeDef",
     "UpdateSignalCatalogResponseTypeDef",
+    "UpdateVehicleRequestRequestTypeDef",
     "UpdateVehicleResponseTypeDef",
+    "BatchCreateVehicleResponseTypeDef",
     "BatchUpdateVehicleRequestRequestTypeDef",
     "BatchUpdateVehicleResponseTypeDef",
     "ListCampaignsResponseTypeDef",
     "NetworkFileDefinitionTypeDef",
     "GetLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "CollectionSchemeTypeDef",
     "CreateFleetRequestRequestTypeDef",
     "CreateModelManifestRequestRequestTypeDef",
     "CreateVehicleRequestItemTypeDef",
     "CreateVehicleRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "DataDestinationConfigTypeDef",
     "ListDecoderManifestsResponseTypeDef",
     "ListFleetsResponseTypeDef",
     "ImportSignalCatalogRequestRequestTypeDef",
     "GetRegisterAccountStatusResponseTypeDef",
     "GetSignalCatalogResponseTypeDef",
-    "GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    "ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    "ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
-    "ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    "ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
-    "ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
-    "ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    "ListVehiclesRequestListVehiclesPaginateTypeDef",
     "GetVehicleStatusResponseTypeDef",
     "ListModelManifestsResponseTypeDef",
     "ListSignalCatalogsResponseTypeDef",
     "ListVehiclesResponseTypeDef",
     "NetworkInterfaceTypeDef",
     "NodeTypeDef",
     "SignalDecoderTypeDef",
     "RegisterAccountRequestRequestTypeDef",
     "RegisterAccountResponseTypeDef",
     "ImportDecoderManifestRequestRequestTypeDef",
+    "BatchCreateVehicleRequestRequestTypeDef",
     "CreateCampaignRequestRequestTypeDef",
     "GetCampaignResponseTypeDef",
-    "BatchCreateVehicleRequestRequestTypeDef",
     "ListDecoderManifestNetworkInterfacesResponseTypeDef",
     "CreateSignalCatalogRequestRequestTypeDef",
     "ListModelManifestNodesResponseTypeDef",
     "ListSignalCatalogNodesResponseTypeDef",
     "UpdateSignalCatalogRequestRequestTypeDef",
     "CreateDecoderManifestRequestRequestTypeDef",
     "ListDecoderManifestSignalsResponseTypeDef",
@@ -201,14 +206,16 @@
     {
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
         "assignedValue": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 class ActuatorTypeDef(_RequiredActuatorTypeDef, _OptionalActuatorTypeDef):
     pass
 
@@ -233,14 +240,16 @@
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
         "assignedValue": str,
         "defaultValue": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 class AttributeTypeDef(_RequiredAttributeTypeDef, _OptionalAttributeTypeDef):
     pass
 
@@ -260,25 +269,14 @@
         "vehicleName": str,
         "arn": str,
         "thingArn": str,
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
 _RequiredUpdateVehicleRequestItemTypeDef = TypedDict(
     "_RequiredUpdateVehicleRequestItemTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalUpdateVehicleRequestItemTypeDef = TypedDict(
@@ -322,14 +320,16 @@
         "fullyQualifiedName": str,
     },
 )
 _OptionalBranchTypeDef = TypedDict(
     "_OptionalBranchTypeDef",
     {
         "description": str,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 class BranchTypeDef(_RequiredBranchTypeDef, _OptionalBranchTypeDef):
     pass
 
@@ -486,14 +486,96 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDecoderManifestResponseTypeDef = TypedDict(
+    "CreateDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateModelManifestResponseTypeDef = TypedDict(
+    "CreateModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSignalCatalogResponseTypeDef = TypedDict(
+    "CreateSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVehicleResponseTypeDef = TypedDict(
+    "CreateVehicleResponseTypeDef",
+    {
+        "vehicleName": str,
+        "arn": str,
+        "thingArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredS3ConfigTypeDef = TypedDict(
+    "_RequiredS3ConfigTypeDef",
+    {
+        "bucketArn": str,
+    },
+)
+_OptionalS3ConfigTypeDef = TypedDict(
+    "_OptionalS3ConfigTypeDef",
+    {
+        "dataFormat": DataFormatType,
+        "storageCompressionFormat": StorageCompressionFormatType,
+        "prefix": str,
+    },
+    total=False,
+)
+
+class S3ConfigTypeDef(_RequiredS3ConfigTypeDef, _OptionalS3ConfigTypeDef):
+    pass
+
+TimestreamConfigTypeDef = TypedDict(
+    "TimestreamConfigTypeDef",
+    {
+        "timestreamTableArn": str,
+        "executionRoleArn": str,
+    },
+)
+
 _RequiredDecoderManifestSummaryTypeDef = TypedDict(
     "_RequiredDecoderManifestSummaryTypeDef",
     {
         "creationTime": datetime,
         "lastModificationTime": datetime,
     },
 )
@@ -517,49 +599,103 @@
 DeleteCampaignRequestRequestTypeDef = TypedDict(
     "DeleteCampaignRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteCampaignResponseTypeDef = TypedDict(
+    "DeleteCampaignResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDecoderManifestRequestRequestTypeDef = TypedDict(
     "DeleteDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteDecoderManifestResponseTypeDef = TypedDict(
+    "DeleteDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFleetRequestRequestTypeDef = TypedDict(
     "DeleteFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 
+DeleteFleetResponseTypeDef = TypedDict(
+    "DeleteFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteModelManifestRequestRequestTypeDef = TypedDict(
     "DeleteModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteModelManifestResponseTypeDef = TypedDict(
+    "DeleteModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSignalCatalogRequestRequestTypeDef = TypedDict(
     "DeleteSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DeleteSignalCatalogResponseTypeDef = TypedDict(
+    "DeleteSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVehicleRequestRequestTypeDef = TypedDict(
     "DeleteVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 
+DeleteVehicleResponseTypeDef = TypedDict(
+    "DeleteVehicleResponseTypeDef",
+    {
+        "vehicleName": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateVehicleFleetRequestRequestTypeDef = TypedDict(
     "DisassociateVehicleFleetRequestRequestTypeDef",
     {
         "vehicleName": str,
         "fleetId": str,
     },
 )
@@ -603,28 +739,69 @@
 GetDecoderManifestRequestRequestTypeDef = TypedDict(
     "GetDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetDecoderManifestResponseTypeDef = TypedDict(
+    "GetDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "description": str,
+        "modelManifestArn": str,
+        "status": ManifestStatusType,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFleetRequestRequestTypeDef = TypedDict(
     "GetFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 
+GetFleetResponseTypeDef = TypedDict(
+    "GetFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "description": str,
+        "signalCatalogArn": str,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetModelManifestRequestRequestTypeDef = TypedDict(
     "GetModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetModelManifestResponseTypeDef = TypedDict(
+    "GetModelManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "description": str,
+        "signalCatalogArn": str,
+        "status": ManifestStatusType,
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredIamRegistrationResponseTypeDef = TypedDict(
     "_RequiredIamRegistrationResponseTypeDef",
     {
         "roleArn": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -686,24 +863,48 @@
 GetVehicleRequestRequestTypeDef = TypedDict(
     "GetVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetVehicleResponseTypeDef = TypedDict(
+    "GetVehicleResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "vehicleName": str,
+        "arn": str,
+        "modelManifestArn": str,
+        "decoderManifestArn": str,
+        "attributes": Dict[str, str],
+        "creationTime": datetime,
+        "lastModificationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
+    {
+        "vehicleName": str,
+    },
+)
+_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef(
+    _RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
+    _OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredGetVehicleStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetVehicleStatusRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalGetVehicleStatusRequestRequestTypeDef = TypedDict(
@@ -733,24 +934,71 @@
 IamResourcesTypeDef = TypedDict(
     "IamResourcesTypeDef",
     {
         "roleArn": str,
     },
 )
 
+ImportDecoderManifestResponseTypeDef = TypedDict(
+    "ImportDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportSignalCatalogResponseTypeDef = TypedDict(
+    "ImportSignalCatalogResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
+    {
+        "status": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": str,
     },
     total=False,
 )
 
+_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
+    "_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
+    "_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef(
+    _RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
+    _OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef = TypedDict(
     "_RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListDecoderManifestNetworkInterfacesRequestRequestTypeDef = TypedDict(
@@ -764,14 +1012,34 @@
 
 class ListDecoderManifestNetworkInterfacesRequestRequestTypeDef(
     _RequiredListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
     _OptionalListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
+    "_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
+    "_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef(
+    _RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
+    _OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDecoderManifestSignalsRequestRequestTypeDef = TypedDict(
     "_RequiredListDecoderManifestSignalsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListDecoderManifestSignalsRequestRequestTypeDef = TypedDict(
@@ -785,24 +1053,53 @@
 
 class ListDecoderManifestSignalsRequestRequestTypeDef(
     _RequiredListDecoderManifestSignalsRequestRequestTypeDef,
     _OptionalListDecoderManifestSignalsRequestRequestTypeDef,
 ):
     pass
 
+ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef = TypedDict(
+    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
+    {
+        "modelManifestArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDecoderManifestsRequestRequestTypeDef = TypedDict(
     "ListDecoderManifestsRequestRequestTypeDef",
     {
         "modelManifestArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
+    "_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
+    {
+        "vehicleName": str,
+    },
+)
+_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
+    "_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef(
+    _RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
+    _OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
+):
+    pass
+
 _RequiredListFleetsForVehicleRequestRequestTypeDef = TypedDict(
     "_RequiredListFleetsForVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
     },
 )
 _OptionalListFleetsForVehicleRequestRequestTypeDef = TypedDict(
@@ -816,23 +1113,60 @@
 
 class ListFleetsForVehicleRequestRequestTypeDef(
     _RequiredListFleetsForVehicleRequestRequestTypeDef,
     _OptionalListFleetsForVehicleRequestRequestTypeDef,
 ):
     pass
 
+ListFleetsForVehicleResponseTypeDef = TypedDict(
+    "ListFleetsForVehicleResponseTypeDef",
+    {
+        "fleets": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsRequestListFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFleetsRequestRequestTypeDef = TypedDict(
     "ListFleetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
+    "_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
+    "_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef(
+    _RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
+    _OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
+):
+    pass
+
 _RequiredListModelManifestNodesRequestRequestTypeDef = TypedDict(
     "_RequiredListModelManifestNodesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListModelManifestNodesRequestRequestTypeDef = TypedDict(
@@ -846,14 +1180,23 @@
 
 class ListModelManifestNodesRequestRequestTypeDef(
     _RequiredListModelManifestNodesRequestRequestTypeDef,
     _OptionalListModelManifestNodesRequestRequestTypeDef,
 ):
     pass
 
+ListModelManifestsRequestListModelManifestsPaginateTypeDef = TypedDict(
+    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
+    {
+        "signalCatalogArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListModelManifestsRequestRequestTypeDef = TypedDict(
     "ListModelManifestsRequestRequestTypeDef",
     {
         "signalCatalogArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -880,14 +1223,34 @@
 )
 
 class ModelManifestSummaryTypeDef(
     _RequiredModelManifestSummaryTypeDef, _OptionalModelManifestSummaryTypeDef
 ):
     pass
 
+_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
+    "_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
+    "_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef(
+    _RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
+    _OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
+):
+    pass
+
 _RequiredListSignalCatalogNodesRequestRequestTypeDef = TypedDict(
     "_RequiredListSignalCatalogNodesRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalListSignalCatalogNodesRequestRequestTypeDef = TypedDict(
@@ -901,14 +1264,22 @@
 
 class ListSignalCatalogNodesRequestRequestTypeDef(
     _RequiredListSignalCatalogNodesRequestRequestTypeDef,
     _OptionalListSignalCatalogNodesRequestRequestTypeDef,
 ):
     pass
 
+ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef = TypedDict(
+    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSignalCatalogsRequestRequestTypeDef = TypedDict(
     "ListSignalCatalogsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -928,14 +1299,34 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
+    "_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
+    {
+        "fleetId": str,
+    },
+)
+_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
+    "_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef(
+    _RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
+    _OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
+):
+    pass
+
 _RequiredListVehiclesInFleetRequestRequestTypeDef = TypedDict(
     "_RequiredListVehiclesInFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 _OptionalListVehiclesInFleetRequestRequestTypeDef = TypedDict(
@@ -949,14 +1340,32 @@
 
 class ListVehiclesInFleetRequestRequestTypeDef(
     _RequiredListVehiclesInFleetRequestRequestTypeDef,
     _OptionalListVehiclesInFleetRequestRequestTypeDef,
 ):
     pass
 
+ListVehiclesInFleetResponseTypeDef = TypedDict(
+    "ListVehiclesInFleetResponseTypeDef",
+    {
+        "vehicles": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListVehiclesRequestListVehiclesPaginateTypeDef = TypedDict(
+    "ListVehiclesRequestListVehiclesPaginateTypeDef",
+    {
+        "modelManifestArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVehiclesRequestRequestTypeDef = TypedDict(
     "ListVehiclesRequestRequestTypeDef",
     {
         "modelManifestArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1008,14 +1417,16 @@
     "_OptionalSensorTypeDef",
     {
         "description": str,
         "unit": str,
         "allowedValues": Sequence[str],
         "min": float,
         "max": float,
+        "deprecationMessage": str,
+        "comment": str,
     },
     total=False,
 )
 
 class SensorTypeDef(_RequiredSensorTypeDef, _OptionalSensorTypeDef):
     pass
 
@@ -1039,22 +1450,43 @@
     },
     total=False,
 )
 
 class ObdSignalTypeDef(_RequiredObdSignalTypeDef, _OptionalObdSignalTypeDef):
     pass
 
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
 TimestreamResourcesTypeDef = TypedDict(
     "TimestreamResourcesTypeDef",
     {
         "timestreamDatabaseName": str,
         "timestreamTableName": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1076,14 +1508,33 @@
 )
 
 class UpdateCampaignRequestRequestTypeDef(
     _RequiredUpdateCampaignRequestRequestTypeDef, _OptionalUpdateCampaignRequestRequestTypeDef
 ):
     pass
 
+UpdateCampaignResponseTypeDef = TypedDict(
+    "UpdateCampaignResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "status": CampaignStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDecoderManifestResponseTypeDef = TypedDict(
+    "UpdateDecoderManifestResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFleetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetRequestRequestTypeDef",
     {
         "fleetId": str,
     },
 )
 _OptionalUpdateFleetRequestRequestTypeDef = TypedDict(
@@ -1095,14 +1546,23 @@
 )
 
 class UpdateFleetRequestRequestTypeDef(
     _RequiredUpdateFleetRequestRequestTypeDef, _OptionalUpdateFleetRequestRequestTypeDef
 ):
     pass
 
+UpdateFleetResponseTypeDef = TypedDict(
+    "UpdateFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateModelManifestRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelManifestRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateModelManifestRequestRequestTypeDef = TypedDict(
@@ -1118,297 +1578,69 @@
 
 class UpdateModelManifestRequestRequestTypeDef(
     _RequiredUpdateModelManifestRequestRequestTypeDef,
     _OptionalUpdateModelManifestRequestRequestTypeDef,
 ):
     pass
 
-_RequiredUpdateVehicleRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateVehicleRequestRequestTypeDef",
-    {
-        "vehicleName": str,
-    },
-)
-_OptionalUpdateVehicleRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateVehicleRequestRequestTypeDef",
-    {
-        "modelManifestArn": str,
-        "decoderManifestArn": str,
-        "attributes": Mapping[str, str],
-        "attributeUpdateMode": UpdateModeType,
-    },
-    total=False,
-)
-
-class UpdateVehicleRequestRequestTypeDef(
-    _RequiredUpdateVehicleRequestRequestTypeDef, _OptionalUpdateVehicleRequestRequestTypeDef
-):
-    pass
-
-BatchCreateVehicleResponseTypeDef = TypedDict(
-    "BatchCreateVehicleResponseTypeDef",
-    {
-        "vehicles": List[CreateVehicleResponseItemTypeDef],
-        "errors": List[CreateVehicleErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDecoderManifestResponseTypeDef = TypedDict(
-    "CreateDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelManifestResponseTypeDef = TypedDict(
-    "CreateModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSignalCatalogResponseTypeDef = TypedDict(
-    "CreateSignalCatalogResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVehicleResponseTypeDef = TypedDict(
-    "CreateVehicleResponseTypeDef",
-    {
-        "vehicleName": str,
-        "arn": str,
-        "thingArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCampaignResponseTypeDef = TypedDict(
-    "DeleteCampaignResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDecoderManifestResponseTypeDef = TypedDict(
-    "DeleteDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFleetResponseTypeDef = TypedDict(
-    "DeleteFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteModelManifestResponseTypeDef = TypedDict(
-    "DeleteModelManifestResponseTypeDef",
+UpdateModelManifestResponseTypeDef = TypedDict(
+    "UpdateModelManifestResponseTypeDef",
     {
         "name": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteSignalCatalogResponseTypeDef = TypedDict(
-    "DeleteSignalCatalogResponseTypeDef",
+UpdateSignalCatalogResponseTypeDef = TypedDict(
+    "UpdateSignalCatalogResponseTypeDef",
     {
         "name": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteVehicleResponseTypeDef = TypedDict(
-    "DeleteVehicleResponseTypeDef",
+_RequiredUpdateVehicleRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateVehicleRequestRequestTypeDef",
     {
         "vehicleName": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDecoderManifestResponseTypeDef = TypedDict(
-    "GetDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "description": str,
-        "modelManifestArn": str,
-        "status": ManifestStatusType,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFleetResponseTypeDef = TypedDict(
-    "GetFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "description": str,
-        "signalCatalogArn": str,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetModelManifestResponseTypeDef = TypedDict(
-    "GetModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "description": str,
-        "signalCatalogArn": str,
-        "status": ManifestStatusType,
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-GetVehicleResponseTypeDef = TypedDict(
-    "GetVehicleResponseTypeDef",
+_OptionalUpdateVehicleRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateVehicleRequestRequestTypeDef",
     {
-        "vehicleName": str,
-        "arn": str,
         "modelManifestArn": str,
         "decoderManifestArn": str,
-        "attributes": Dict[str, str],
-        "creationTime": datetime,
-        "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportDecoderManifestResponseTypeDef = TypedDict(
-    "ImportDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSignalCatalogResponseTypeDef = TypedDict(
-    "ImportSignalCatalogResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFleetsForVehicleResponseTypeDef = TypedDict(
-    "ListFleetsForVehicleResponseTypeDef",
-    {
-        "fleets": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVehiclesInFleetResponseTypeDef = TypedDict(
-    "ListVehiclesInFleetResponseTypeDef",
-    {
-        "vehicles": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCampaignResponseTypeDef = TypedDict(
-    "UpdateCampaignResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "status": CampaignStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDecoderManifestResponseTypeDef = TypedDict(
-    "UpdateDecoderManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFleetResponseTypeDef = TypedDict(
-    "UpdateFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "attributes": Mapping[str, str],
+        "attributeUpdateMode": UpdateModeType,
     },
+    total=False,
 )
 
-UpdateModelManifestResponseTypeDef = TypedDict(
-    "UpdateModelManifestResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateVehicleRequestRequestTypeDef(
+    _RequiredUpdateVehicleRequestRequestTypeDef, _OptionalUpdateVehicleRequestRequestTypeDef
+):
+    pass
 
-UpdateSignalCatalogResponseTypeDef = TypedDict(
-    "UpdateSignalCatalogResponseTypeDef",
+UpdateVehicleResponseTypeDef = TypedDict(
+    "UpdateVehicleResponseTypeDef",
     {
-        "name": str,
+        "vehicleName": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateVehicleResponseTypeDef = TypedDict(
-    "UpdateVehicleResponseTypeDef",
+BatchCreateVehicleResponseTypeDef = TypedDict(
+    "BatchCreateVehicleResponseTypeDef",
     {
-        "vehicleName": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "vehicles": List[CreateVehicleResponseItemTypeDef],
+        "errors": List[CreateVehicleErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateVehicleRequestRequestTypeDef = TypedDict(
     "BatchUpdateVehicleRequestRequestTypeDef",
     {
         "vehicles": Sequence[UpdateVehicleRequestItemTypeDef],
@@ -1416,24 +1648,24 @@
 )
 
 BatchUpdateVehicleResponseTypeDef = TypedDict(
     "BatchUpdateVehicleResponseTypeDef",
     {
         "vehicles": List[UpdateVehicleResponseItemTypeDef],
         "errors": List[UpdateVehicleErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCampaignsResponseTypeDef = TypedDict(
     "ListCampaignsResponseTypeDef",
     {
         "campaignSummaries": List[CampaignSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFileDefinitionTypeDef = TypedDict(
     "NetworkFileDefinitionTypeDef",
     {
         "canDbc": CanDbcDefinitionTypeDef,
@@ -1441,15 +1673,15 @@
     total=False,
 )
 
 GetLoggingOptionsResponseTypeDef = TypedDict(
     "GetLoggingOptionsResponseTypeDef",
     {
         "cloudWatchLogDelivery": CloudWatchLogDeliveryOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "cloudWatchLogDelivery": CloudWatchLogDeliveryOptionsTypeDef,
@@ -1555,41 +1787,50 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+DataDestinationConfigTypeDef = TypedDict(
+    "DataDestinationConfigTypeDef",
+    {
+        "s3Config": S3ConfigTypeDef,
+        "timestreamConfig": TimestreamConfigTypeDef,
+    },
+    total=False,
+)
+
 ListDecoderManifestsResponseTypeDef = TypedDict(
     "ListDecoderManifestsResponseTypeDef",
     {
         "summaries": List[DecoderManifestSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFleetsResponseTypeDef = TypedDict(
     "ListFleetsResponseTypeDef",
     {
         "fleetSummaries": List[FleetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredImportSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -1616,256 +1857,64 @@
     {
         "customerAccountId": str,
         "accountStatus": RegistrationStatusType,
         "timestreamRegistrationResponse": TimestreamRegistrationResponseTypeDef,
         "iamRegistrationResponse": IamRegistrationResponseTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSignalCatalogResponseTypeDef = TypedDict(
     "GetSignalCatalogResponseTypeDef",
     {
         "name": str,
         "arn": str,
         "description": str,
         "nodeCounts": NodeCountsTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    {
-        "vehicleName": str,
-    },
-)
-_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-class GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef(
-    _RequiredGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-    _OptionalGetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-):
-    pass
-
-ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    {
-        "status": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
-    "_RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef = TypedDict(
-    "_OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef(
-    _RequiredListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-    _OptionalListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-):
-    pass
-
-_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
-    "_RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef = TypedDict(
-    "_OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef(
-    _RequiredListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-    _OptionalListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-):
-    pass
-
-ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef = TypedDict(
-    "ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef",
-    {
-        "modelManifestArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
-    "_RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    {
-        "vehicleName": str,
-    },
-)
-_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef = TypedDict(
-    "_OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef(
-    _RequiredListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-    _OptionalListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-):
-    pass
-
-ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
-    "_RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef = TypedDict(
-    "_OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef(
-    _RequiredListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-    _OptionalListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-):
-    pass
-
-ListModelManifestsRequestListModelManifestsPaginateTypeDef = TypedDict(
-    "ListModelManifestsRequestListModelManifestsPaginateTypeDef",
-    {
-        "signalCatalogArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
-    "_RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef = TypedDict(
-    "_OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef(
-    _RequiredListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-    _OptionalListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-):
-    pass
-
-ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef = TypedDict(
-    "ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
-    "_RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    {
-        "fleetId": str,
-    },
-)
-_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef = TypedDict(
-    "_OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef(
-    _RequiredListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-    _OptionalListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-):
-    pass
-
-ListVehiclesRequestListVehiclesPaginateTypeDef = TypedDict(
-    "ListVehiclesRequestListVehiclesPaginateTypeDef",
-    {
-        "modelManifestArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 GetVehicleStatusResponseTypeDef = TypedDict(
     "GetVehicleStatusResponseTypeDef",
     {
         "campaigns": List[VehicleStatusTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListModelManifestsResponseTypeDef = TypedDict(
     "ListModelManifestsResponseTypeDef",
     {
         "summaries": List[ModelManifestSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalCatalogsResponseTypeDef = TypedDict(
     "ListSignalCatalogsResponseTypeDef",
     {
         "summaries": List[SignalCatalogSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVehiclesResponseTypeDef = TypedDict(
     "ListVehiclesResponseTypeDef",
     {
         "vehicleSummaries": List[VehicleSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNetworkInterfaceTypeDef = TypedDict(
     "_RequiredNetworkInterfaceTypeDef",
     {
         "interfaceId": str,
@@ -1911,53 +1960,50 @@
     },
     total=False,
 )
 
 class SignalDecoderTypeDef(_RequiredSignalDecoderTypeDef, _OptionalSignalDecoderTypeDef):
     pass
 
-_RequiredRegisterAccountRequestRequestTypeDef = TypedDict(
-    "_RequiredRegisterAccountRequestRequestTypeDef",
+RegisterAccountRequestRequestTypeDef = TypedDict(
+    "RegisterAccountRequestRequestTypeDef",
     {
         "timestreamResources": TimestreamResourcesTypeDef,
-    },
-)
-_OptionalRegisterAccountRequestRequestTypeDef = TypedDict(
-    "_OptionalRegisterAccountRequestRequestTypeDef",
-    {
         "iamResources": IamResourcesTypeDef,
     },
     total=False,
 )
 
-class RegisterAccountRequestRequestTypeDef(
-    _RequiredRegisterAccountRequestRequestTypeDef, _OptionalRegisterAccountRequestRequestTypeDef
-):
-    pass
-
 RegisterAccountResponseTypeDef = TypedDict(
     "RegisterAccountResponseTypeDef",
     {
         "registerAccountStatus": RegistrationStatusType,
         "timestreamResources": TimestreamResourcesTypeDef,
         "iamResources": IamResourcesTypeDef,
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportDecoderManifestRequestRequestTypeDef = TypedDict(
     "ImportDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
         "networkFileDefinitions": Sequence[NetworkFileDefinitionTypeDef],
     },
 )
 
+BatchCreateVehicleRequestRequestTypeDef = TypedDict(
+    "BatchCreateVehicleRequestRequestTypeDef",
+    {
+        "vehicles": Sequence[CreateVehicleRequestItemTypeDef],
+    },
+)
+
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "name": str,
         "signalCatalogArn": str,
         "targetArn": str,
         "collectionScheme": CollectionSchemeTypeDef,
@@ -1973,14 +2019,15 @@
         "diagnosticsMode": DiagnosticsModeType,
         "spoolingMode": SpoolingModeType,
         "compression": CompressionType,
         "priority": int,
         "signalsToCollect": Sequence[SignalInformationTypeDef],
         "dataExtraDimensions": Sequence[str],
         "tags": Sequence[TagTypeDef],
+        "dataDestinationConfigs": Sequence[DataDestinationConfigTypeDef],
     },
     total=False,
 )
 
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
 ):
@@ -2003,31 +2050,25 @@
         "compression": CompressionType,
         "priority": int,
         "signalsToCollect": List[SignalInformationTypeDef],
         "collectionScheme": CollectionSchemeTypeDef,
         "dataExtraDimensions": List[str],
         "creationTime": datetime,
         "lastModificationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchCreateVehicleRequestRequestTypeDef = TypedDict(
-    "BatchCreateVehicleRequestRequestTypeDef",
-    {
-        "vehicles": Sequence[CreateVehicleRequestItemTypeDef],
+        "dataDestinationConfigs": List[DataDestinationConfigTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDecoderManifestNetworkInterfacesResponseTypeDef = TypedDict(
     "ListDecoderManifestNetworkInterfacesResponseTypeDef",
     {
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -2050,24 +2091,24 @@
     pass
 
 ListModelManifestNodesResponseTypeDef = TypedDict(
     "ListModelManifestNodesResponseTypeDef",
     {
         "nodes": List[NodeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalCatalogNodesResponseTypeDef = TypedDict(
     "ListSignalCatalogNodesResponseTypeDef",
     {
         "nodes": List[NodeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSignalCatalogRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSignalCatalogRequestRequestTypeDef",
     {
         "name": str,
@@ -2115,15 +2156,15 @@
     pass
 
 ListDecoderManifestSignalsResponseTypeDef = TypedDict(
     "ListDecoderManifestSignalsResponseTypeDef",
     {
         "signalDecoders": List[SignalDecoderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDecoderManifestRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDecoderManifestRequestRequestTypeDef",
     {
         "name": str,
```

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/PKG-INFO` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotfleetwise
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTFleetWise 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTFleetWise 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotfleetwise"></a>
 
 # types-aiobotocore-iotfleetwise
 
 [![PyPI - types-aiobotocore-iotfleetwise](https://img.shields.io/pypi/v/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleetwise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleetwise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleetwise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleetwise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
+[aiobotocore.IoTFleetWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleetwise.html#IoTFleetWise)
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
 [types-aiobotocore-iotfleetwise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleetwise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -340,14 +340,15 @@
 `types_aiobotocore_iotfleetwise.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotfleetwise.literals import (
     CampaignStatusType,
     CompressionType,
+    DataFormatType,
     DiagnosticsModeType,
     GetVehicleStatusPaginatorName,
     ListCampaignsPaginatorName,
     ListDecoderManifestNetworkInterfacesPaginatorName,
     ListDecoderManifestSignalsPaginatorName,
     ListDecoderManifestsPaginatorName,
     ListFleetsForVehiclePaginatorName,
@@ -361,14 +362,15 @@
     LogTypeType,
     ManifestStatusType,
     NetworkInterfaceTypeType,
     NodeDataTypeType,
     RegistrationStatusType,
     SignalDecoderTypeType,
     SpoolingModeType,
+    StorageCompressionFormatType,
     TriggerModeType,
     UpdateCampaignActionType,
     UpdateModeType,
     VehicleAssociationBehaviorType,
     VehicleStateType,
     IoTFleetWiseServiceName,
     ServiceName,
@@ -392,147 +394,150 @@
 ```python
 from types_aiobotocore_iotfleetwise.type_defs import (
     ActuatorTypeDef,
     AssociateVehicleFleetRequestRequestTypeDef,
     AttributeTypeDef,
     CreateVehicleErrorTypeDef,
     CreateVehicleResponseItemTypeDef,
-    ResponseMetadataTypeDef,
     UpdateVehicleRequestItemTypeDef,
     UpdateVehicleErrorTypeDef,
     UpdateVehicleResponseItemTypeDef,
     BranchTypeDef,
     CampaignSummaryTypeDef,
     CanDbcDefinitionTypeDef,
     CanInterfaceTypeDef,
     CanSignalTypeDef,
     CloudWatchLogDeliveryOptionsTypeDef,
     ConditionBasedCollectionSchemeTypeDef,
     TimeBasedCollectionSchemeTypeDef,
     SignalInformationTypeDef,
     TagTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDecoderManifestResponseTypeDef,
+    CreateFleetResponseTypeDef,
+    CreateModelManifestResponseTypeDef,
+    CreateSignalCatalogResponseTypeDef,
+    CreateVehicleResponseTypeDef,
+    S3ConfigTypeDef,
+    TimestreamConfigTypeDef,
     DecoderManifestSummaryTypeDef,
     DeleteCampaignRequestRequestTypeDef,
+    DeleteCampaignResponseTypeDef,
     DeleteDecoderManifestRequestRequestTypeDef,
+    DeleteDecoderManifestResponseTypeDef,
     DeleteFleetRequestRequestTypeDef,
+    DeleteFleetResponseTypeDef,
     DeleteModelManifestRequestRequestTypeDef,
+    DeleteModelManifestResponseTypeDef,
     DeleteSignalCatalogRequestRequestTypeDef,
+    DeleteSignalCatalogResponseTypeDef,
     DeleteVehicleRequestRequestTypeDef,
+    DeleteVehicleResponseTypeDef,
     DisassociateVehicleFleetRequestRequestTypeDef,
     FleetSummaryTypeDef,
     FormattedVssTypeDef,
     GetCampaignRequestRequestTypeDef,
     GetDecoderManifestRequestRequestTypeDef,
+    GetDecoderManifestResponseTypeDef,
     GetFleetRequestRequestTypeDef,
+    GetFleetResponseTypeDef,
     GetModelManifestRequestRequestTypeDef,
+    GetModelManifestResponseTypeDef,
     IamRegistrationResponseTypeDef,
     TimestreamRegistrationResponseTypeDef,
     GetSignalCatalogRequestRequestTypeDef,
     NodeCountsTypeDef,
     GetVehicleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetVehicleResponseTypeDef,
+    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
     GetVehicleStatusRequestRequestTypeDef,
     VehicleStatusTypeDef,
     IamResourcesTypeDef,
+    ImportDecoderManifestResponseTypeDef,
+    ImportSignalCatalogResponseTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
     ListDecoderManifestNetworkInterfacesRequestRequestTypeDef,
+    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
     ListDecoderManifestSignalsRequestRequestTypeDef,
+    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
     ListDecoderManifestsRequestRequestTypeDef,
+    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
     ListFleetsForVehicleRequestRequestTypeDef,
+    ListFleetsForVehicleResponseTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
     ListModelManifestNodesRequestRequestTypeDef,
+    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
     ListModelManifestsRequestRequestTypeDef,
     ModelManifestSummaryTypeDef,
+    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
     ListSignalCatalogNodesRequestRequestTypeDef,
+    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
     ListSignalCatalogsRequestRequestTypeDef,
     SignalCatalogSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
     ListVehiclesInFleetRequestRequestTypeDef,
+    ListVehiclesInFleetResponseTypeDef,
+    ListVehiclesRequestListVehiclesPaginateTypeDef,
     ListVehiclesRequestRequestTypeDef,
     VehicleSummaryTypeDef,
     ObdInterfaceTypeDef,
     SensorTypeDef,
     ObdSignalTypeDef,
+    PaginatorConfigTypeDef,
     TimestreamResourcesTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignRequestRequestTypeDef,
-    UpdateFleetRequestRequestTypeDef,
-    UpdateModelManifestRequestRequestTypeDef,
-    UpdateVehicleRequestRequestTypeDef,
-    BatchCreateVehicleResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDecoderManifestResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateModelManifestResponseTypeDef,
-    CreateSignalCatalogResponseTypeDef,
-    CreateVehicleResponseTypeDef,
-    DeleteCampaignResponseTypeDef,
-    DeleteDecoderManifestResponseTypeDef,
-    DeleteFleetResponseTypeDef,
-    DeleteModelManifestResponseTypeDef,
-    DeleteSignalCatalogResponseTypeDef,
-    DeleteVehicleResponseTypeDef,
-    GetDecoderManifestResponseTypeDef,
-    GetFleetResponseTypeDef,
-    GetModelManifestResponseTypeDef,
-    GetVehicleResponseTypeDef,
-    ImportDecoderManifestResponseTypeDef,
-    ImportSignalCatalogResponseTypeDef,
-    ListFleetsForVehicleResponseTypeDef,
-    ListVehiclesInFleetResponseTypeDef,
     UpdateCampaignResponseTypeDef,
     UpdateDecoderManifestResponseTypeDef,
+    UpdateFleetRequestRequestTypeDef,
     UpdateFleetResponseTypeDef,
+    UpdateModelManifestRequestRequestTypeDef,
     UpdateModelManifestResponseTypeDef,
     UpdateSignalCatalogResponseTypeDef,
+    UpdateVehicleRequestRequestTypeDef,
     UpdateVehicleResponseTypeDef,
+    BatchCreateVehicleResponseTypeDef,
     BatchUpdateVehicleRequestRequestTypeDef,
     BatchUpdateVehicleResponseTypeDef,
     ListCampaignsResponseTypeDef,
     NetworkFileDefinitionTypeDef,
     GetLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     CollectionSchemeTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateModelManifestRequestRequestTypeDef,
     CreateVehicleRequestItemTypeDef,
     CreateVehicleRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataDestinationConfigTypeDef,
     ListDecoderManifestsResponseTypeDef,
     ListFleetsResponseTypeDef,
     ImportSignalCatalogRequestRequestTypeDef,
     GetRegisterAccountStatusResponseTypeDef,
     GetSignalCatalogResponseTypeDef,
-    GetVehicleStatusRequestGetVehicleStatusPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDecoderManifestNetworkInterfacesRequestListDecoderManifestNetworkInterfacesPaginateTypeDef,
-    ListDecoderManifestSignalsRequestListDecoderManifestSignalsPaginateTypeDef,
-    ListDecoderManifestsRequestListDecoderManifestsPaginateTypeDef,
-    ListFleetsForVehicleRequestListFleetsForVehiclePaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListModelManifestNodesRequestListModelManifestNodesPaginateTypeDef,
-    ListModelManifestsRequestListModelManifestsPaginateTypeDef,
-    ListSignalCatalogNodesRequestListSignalCatalogNodesPaginateTypeDef,
-    ListSignalCatalogsRequestListSignalCatalogsPaginateTypeDef,
-    ListVehiclesInFleetRequestListVehiclesInFleetPaginateTypeDef,
-    ListVehiclesRequestListVehiclesPaginateTypeDef,
     GetVehicleStatusResponseTypeDef,
     ListModelManifestsResponseTypeDef,
     ListSignalCatalogsResponseTypeDef,
     ListVehiclesResponseTypeDef,
     NetworkInterfaceTypeDef,
     NodeTypeDef,
     SignalDecoderTypeDef,
     RegisterAccountRequestRequestTypeDef,
     RegisterAccountResponseTypeDef,
     ImportDecoderManifestRequestRequestTypeDef,
+    BatchCreateVehicleRequestRequestTypeDef,
     CreateCampaignRequestRequestTypeDef,
     GetCampaignResponseTypeDef,
-    BatchCreateVehicleRequestRequestTypeDef,
     ListDecoderManifestNetworkInterfacesResponseTypeDef,
     CreateSignalCatalogRequestRequestTypeDef,
     ListModelManifestNodesResponseTypeDef,
     ListSignalCatalogNodesResponseTypeDef,
     UpdateSignalCatalogRequestRequestTypeDef,
     CreateDecoderManifestRequestRequestTypeDef,
     ListDecoderManifestSignalsResponseTypeDef,
@@ -547,43 +552,43 @@
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

### Comparing `types-aiobotocore-iotfleetwise-2.5.0.post1/types_aiobotocore_iotfleetwise.egg-info/SOURCES.txt` & `types-aiobotocore-iotfleetwise-2.5.1/types_aiobotocore_iotfleetwise.egg-info/SOURCES.txt`

 * *Files identical despite different names*

