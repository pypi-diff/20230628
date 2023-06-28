# Comparing `tmp/types-aiobotocore-location-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-location-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-location-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:54 2023, max compression
+gzip compressed data, was "types-aiobotocore-location-2.5.1.tar", last modified: Wed Jun 28 01:43:46 2023, max compression
```

## Comparing `types-aiobotocore-location-2.5.0.post1.tar` & `types-aiobotocore-location-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.791377 types-aiobotocore-location-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20871 2023-03-11 12:26:54.791377 types-aiobotocore-location-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19289 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:54.791377 types-aiobotocore-location-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.791377 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/
--rw-r--r--   0 runner    (1001) docker     (123)     2422 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2421 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43754 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43683 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9921 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9919 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11414 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11402 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    56828 2023-03-11 12:17:46.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    56741 2023-03-11 12:17:45.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:44.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.791377 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20871 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:54.000000 types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.834169 types-aiobotocore-location-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21454 2023-06-28 01:43:46.826169 types-aiobotocore-location-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19878 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:46.834169 types-aiobotocore-location-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.826169 types-aiobotocore-location-2.5.1/types_aiobotocore_location/
+-rw-r--r--   0 runner    (1001) docker     (123)     2576 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2575 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48010 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47933 2023-06-28 01:34:26.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10281 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10279 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12380 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12368 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    64877 2023-06-28 01:34:28.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    64766 2023-06-28 01:34:27.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:25.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.826169 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21454 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:46.000000 types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-location-2.5.0.post1/LICENSE` & `types-aiobotocore-location-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-location-2.5.0.post1/PKG-INFO` & `types-aiobotocore-location-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-location
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LocationService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LocationService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-location"></a>
 
 # types-aiobotocore-location
 
 [![PyPI - types-aiobotocore-location](https://img.shields.io/pypi/v/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-location?color=blue)](https://pypistats.org/packages/types-aiobotocore-location)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LocationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
+[aiobotocore.LocationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
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
 [types-aiobotocore-location docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,14 +277,15 @@
 
 from types_aiobotocore_location import LocationServiceClient
 from types_aiobotocore_location.paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 
@@ -300,14 +301,15 @@
     list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator(
         "list_device_positions"
     )
     list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator(
         "list_geofence_collections"
     )
     list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+    list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
     list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
     list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator(
         "list_place_indexes"
     )
     list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator(
         "list_route_calculators"
     )
@@ -330,22 +332,24 @@
     DimensionUnitType,
     DistanceUnitType,
     GetDevicePositionHistoryPaginatorName,
     IntendedUseType,
     ListDevicePositionsPaginatorName,
     ListGeofenceCollectionsPaginatorName,
     ListGeofencesPaginatorName,
+    ListKeysPaginatorName,
     ListMapsPaginatorName,
     ListPlaceIndexesPaginatorName,
     ListRouteCalculatorsPaginatorName,
     ListTrackerConsumersPaginatorName,
     ListTrackersPaginatorName,
     PositionFilteringType,
     PricingPlanType,
     RouteMatrixErrorCodeType,
+    StatusType,
     TravelModeType,
     VehicleWeightUnitType,
     LocationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -361,140 +365,154 @@
 ### Typed dictionaries
 
 `types_aiobotocore_location.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_location.type_defs import (
+    ApiKeyFilterTypeDef,
+    ApiKeyRestrictionsTypeDef,
     AssociateTrackerConsumerRequestRequestTypeDef,
     BatchItemErrorTypeDef,
     BatchDeleteDevicePositionHistoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteGeofenceRequestRequestTypeDef,
     BatchGetDevicePositionRequestRequestTypeDef,
     BatchPutGeofenceSuccessTypeDef,
     CalculateRouteCarModeOptionsTypeDef,
     CalculateRouteMatrixSummaryTypeDef,
     CalculateRouteSummaryTypeDef,
     TruckDimensionsTypeDef,
     TruckWeightTypeDef,
     CircleTypeDef,
     CreateGeofenceCollectionRequestRequestTypeDef,
+    CreateGeofenceCollectionResponseTypeDef,
+    CreateKeyResponseTypeDef,
     MapConfigurationTypeDef,
+    CreateMapResponseTypeDef,
     DataSourceConfigurationTypeDef,
+    CreatePlaceIndexResponseTypeDef,
     CreateRouteCalculatorRequestRequestTypeDef,
+    CreateRouteCalculatorResponseTypeDef,
     CreateTrackerRequestRequestTypeDef,
+    CreateTrackerResponseTypeDef,
     DeleteGeofenceCollectionRequestRequestTypeDef,
+    DeleteKeyRequestRequestTypeDef,
     DeleteMapRequestRequestTypeDef,
     DeletePlaceIndexRequestRequestTypeDef,
     DeleteRouteCalculatorRequestRequestTypeDef,
     DeleteTrackerRequestRequestTypeDef,
     DescribeGeofenceCollectionRequestRequestTypeDef,
+    DescribeGeofenceCollectionResponseTypeDef,
+    DescribeKeyRequestRequestTypeDef,
     DescribeMapRequestRequestTypeDef,
     DescribePlaceIndexRequestRequestTypeDef,
     DescribeRouteCalculatorRequestRequestTypeDef,
+    DescribeRouteCalculatorResponseTypeDef,
     DescribeTrackerRequestRequestTypeDef,
+    DescribeTrackerResponseTypeDef,
     PositionalAccuracyTypeDef,
     DisassociateTrackerConsumerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
     GetDevicePositionHistoryRequestRequestTypeDef,
     GetDevicePositionRequestRequestTypeDef,
     GetGeofenceRequestRequestTypeDef,
     GetMapGlyphsRequestRequestTypeDef,
+    GetMapGlyphsResponseTypeDef,
     GetMapSpritesRequestRequestTypeDef,
+    GetMapSpritesResponseTypeDef,
     GetMapStyleDescriptorRequestRequestTypeDef,
+    GetMapStyleDescriptorResponseTypeDef,
     GetMapTileRequestRequestTypeDef,
+    GetMapTileResponseTypeDef,
     GetPlaceRequestRequestTypeDef,
     LegGeometryTypeDef,
     StepTypeDef,
+    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
     ListDevicePositionsRequestRequestTypeDef,
+    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
     ListGeofenceCollectionsRequestRequestTypeDef,
     ListGeofenceCollectionsResponseEntryTypeDef,
+    ListGeofencesRequestListGeofencesPaginateTypeDef,
     ListGeofencesRequestRequestTypeDef,
+    ListMapsRequestListMapsPaginateTypeDef,
     ListMapsRequestRequestTypeDef,
     ListMapsResponseEntryTypeDef,
+    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
     ListPlaceIndexesRequestRequestTypeDef,
     ListPlaceIndexesResponseEntryTypeDef,
+    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
     ListRouteCalculatorsRequestRequestTypeDef,
     ListRouteCalculatorsResponseEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
     ListTrackerConsumersRequestRequestTypeDef,
+    ListTrackerConsumersResponseTypeDef,
+    ListTrackersRequestListTrackersPaginateTypeDef,
     ListTrackersRequestRequestTypeDef,
     ListTrackersResponseEntryTypeDef,
+    MapConfigurationUpdateTypeDef,
+    PaginatorConfigTypeDef,
     PlaceGeometryTypeDef,
     TimeZoneTypeDef,
+    PutGeofenceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RouteMatrixEntryErrorTypeDef,
     SearchForSuggestionsResultTypeDef,
     SearchPlaceIndexForPositionRequestRequestTypeDef,
     SearchPlaceIndexForPositionSummaryTypeDef,
     SearchPlaceIndexForSuggestionsRequestRequestTypeDef,
     SearchPlaceIndexForSuggestionsSummaryTypeDef,
     SearchPlaceIndexForTextRequestRequestTypeDef,
     SearchPlaceIndexForTextSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGeofenceCollectionRequestRequestTypeDef,
-    UpdateMapRequestRequestTypeDef,
+    UpdateGeofenceCollectionResponseTypeDef,
+    UpdateKeyResponseTypeDef,
+    UpdateMapResponseTypeDef,
+    UpdatePlaceIndexResponseTypeDef,
     UpdateRouteCalculatorRequestRequestTypeDef,
+    UpdateRouteCalculatorResponseTypeDef,
     UpdateTrackerRequestRequestTypeDef,
+    UpdateTrackerResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
+    ListKeysRequestRequestTypeDef,
+    CreateKeyRequestRequestTypeDef,
+    DescribeKeyResponseTypeDef,
+    ListKeysResponseEntryTypeDef,
+    UpdateKeyRequestRequestTypeDef,
     BatchDeleteDevicePositionHistoryErrorTypeDef,
     BatchDeleteGeofenceErrorTypeDef,
     BatchEvaluateGeofencesErrorTypeDef,
     BatchGetDevicePositionErrorTypeDef,
     BatchPutGeofenceErrorTypeDef,
     BatchUpdateDevicePositionErrorTypeDef,
-    CreateGeofenceCollectionResponseTypeDef,
-    CreateMapResponseTypeDef,
-    CreatePlaceIndexResponseTypeDef,
-    CreateRouteCalculatorResponseTypeDef,
-    CreateTrackerResponseTypeDef,
-    DescribeGeofenceCollectionResponseTypeDef,
-    DescribeRouteCalculatorResponseTypeDef,
-    DescribeTrackerResponseTypeDef,
-    GetMapGlyphsResponseTypeDef,
-    GetMapSpritesResponseTypeDef,
-    GetMapStyleDescriptorResponseTypeDef,
-    GetMapTileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTrackerConsumersResponseTypeDef,
-    PutGeofenceResponseTypeDef,
-    UpdateGeofenceCollectionResponseTypeDef,
-    UpdateMapResponseTypeDef,
-    UpdatePlaceIndexResponseTypeDef,
-    UpdateRouteCalculatorResponseTypeDef,
-    UpdateTrackerResponseTypeDef,
     CalculateRouteTruckModeOptionsTypeDef,
     GeofenceGeometryTypeDef,
     CreateMapRequestRequestTypeDef,
     DescribeMapResponseTypeDef,
     CreatePlaceIndexRequestRequestTypeDef,
     DescribePlaceIndexResponseTypeDef,
     UpdatePlaceIndexRequestRequestTypeDef,
     DevicePositionTypeDef,
     DevicePositionUpdateTypeDef,
     GetDevicePositionResponseTypeDef,
     ListDevicePositionsResponseEntryTypeDef,
-    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
-    ListGeofencesRequestListGeofencesPaginateTypeDef,
-    ListMapsRequestListMapsPaginateTypeDef,
-    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
-    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
-    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-    ListTrackersRequestListTrackersPaginateTypeDef,
     LegTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTrackersResponseTypeDef,
+    UpdateMapRequestRequestTypeDef,
     PlaceTypeDef,
     RouteMatrixEntryTypeDef,
     SearchPlaceIndexForSuggestionsResponseTypeDef,
+    ListKeysResponseTypeDef,
     BatchDeleteDevicePositionHistoryResponseTypeDef,
     BatchDeleteGeofenceResponseTypeDef,
     BatchEvaluateGeofencesResponseTypeDef,
     BatchPutGeofenceResponseTypeDef,
     BatchUpdateDevicePositionResponseTypeDef,
     CalculateRouteMatrixRequestRequestTypeDef,
     CalculateRouteRequestRequestTypeDef,
@@ -515,54 +533,54 @@
     BatchPutGeofenceRequestRequestTypeDef,
     ListGeofencesResponseTypeDef,
     SearchPlaceIndexForPositionResponseTypeDef,
     SearchPlaceIndexForTextResponseTypeDef,
 )
 
 
-def get_structure() -> AssociateTrackerConsumerRequestRequestTypeDef:
+def get_structure() -> ApiKeyFilterTypeDef:
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

### Comparing `types-aiobotocore-location-2.5.0.post1/README.md` & `types-aiobotocore-location-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-location"></a>
 
 # types-aiobotocore-location
 
 [![PyPI - types-aiobotocore-location](https://img.shields.io/pypi/v/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-location?color=blue)](https://pypistats.org/packages/types-aiobotocore-location)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LocationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
+[aiobotocore.LocationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
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
 [types-aiobotocore-location docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/).
 
 See how it helps to find and fix potential bugs:
 
@@ -244,14 +244,15 @@
 
 from types_aiobotocore_location import LocationServiceClient
 from types_aiobotocore_location.paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 
@@ -267,14 +268,15 @@
     list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator(
         "list_device_positions"
     )
     list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator(
         "list_geofence_collections"
     )
     list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+    list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
     list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
     list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator(
         "list_place_indexes"
     )
     list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator(
         "list_route_calculators"
     )
@@ -297,22 +299,24 @@
     DimensionUnitType,
     DistanceUnitType,
     GetDevicePositionHistoryPaginatorName,
     IntendedUseType,
     ListDevicePositionsPaginatorName,
     ListGeofenceCollectionsPaginatorName,
     ListGeofencesPaginatorName,
+    ListKeysPaginatorName,
     ListMapsPaginatorName,
     ListPlaceIndexesPaginatorName,
     ListRouteCalculatorsPaginatorName,
     ListTrackerConsumersPaginatorName,
     ListTrackersPaginatorName,
     PositionFilteringType,
     PricingPlanType,
     RouteMatrixErrorCodeType,
+    StatusType,
     TravelModeType,
     VehicleWeightUnitType,
     LocationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -328,140 +332,154 @@
 ### Typed dictionaries
 
 `types_aiobotocore_location.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_location.type_defs import (
+    ApiKeyFilterTypeDef,
+    ApiKeyRestrictionsTypeDef,
     AssociateTrackerConsumerRequestRequestTypeDef,
     BatchItemErrorTypeDef,
     BatchDeleteDevicePositionHistoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteGeofenceRequestRequestTypeDef,
     BatchGetDevicePositionRequestRequestTypeDef,
     BatchPutGeofenceSuccessTypeDef,
     CalculateRouteCarModeOptionsTypeDef,
     CalculateRouteMatrixSummaryTypeDef,
     CalculateRouteSummaryTypeDef,
     TruckDimensionsTypeDef,
     TruckWeightTypeDef,
     CircleTypeDef,
     CreateGeofenceCollectionRequestRequestTypeDef,
+    CreateGeofenceCollectionResponseTypeDef,
+    CreateKeyResponseTypeDef,
     MapConfigurationTypeDef,
+    CreateMapResponseTypeDef,
     DataSourceConfigurationTypeDef,
+    CreatePlaceIndexResponseTypeDef,
     CreateRouteCalculatorRequestRequestTypeDef,
+    CreateRouteCalculatorResponseTypeDef,
     CreateTrackerRequestRequestTypeDef,
+    CreateTrackerResponseTypeDef,
     DeleteGeofenceCollectionRequestRequestTypeDef,
+    DeleteKeyRequestRequestTypeDef,
     DeleteMapRequestRequestTypeDef,
     DeletePlaceIndexRequestRequestTypeDef,
     DeleteRouteCalculatorRequestRequestTypeDef,
     DeleteTrackerRequestRequestTypeDef,
     DescribeGeofenceCollectionRequestRequestTypeDef,
+    DescribeGeofenceCollectionResponseTypeDef,
+    DescribeKeyRequestRequestTypeDef,
     DescribeMapRequestRequestTypeDef,
     DescribePlaceIndexRequestRequestTypeDef,
     DescribeRouteCalculatorRequestRequestTypeDef,
+    DescribeRouteCalculatorResponseTypeDef,
     DescribeTrackerRequestRequestTypeDef,
+    DescribeTrackerResponseTypeDef,
     PositionalAccuracyTypeDef,
     DisassociateTrackerConsumerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
     GetDevicePositionHistoryRequestRequestTypeDef,
     GetDevicePositionRequestRequestTypeDef,
     GetGeofenceRequestRequestTypeDef,
     GetMapGlyphsRequestRequestTypeDef,
+    GetMapGlyphsResponseTypeDef,
     GetMapSpritesRequestRequestTypeDef,
+    GetMapSpritesResponseTypeDef,
     GetMapStyleDescriptorRequestRequestTypeDef,
+    GetMapStyleDescriptorResponseTypeDef,
     GetMapTileRequestRequestTypeDef,
+    GetMapTileResponseTypeDef,
     GetPlaceRequestRequestTypeDef,
     LegGeometryTypeDef,
     StepTypeDef,
+    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
     ListDevicePositionsRequestRequestTypeDef,
+    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
     ListGeofenceCollectionsRequestRequestTypeDef,
     ListGeofenceCollectionsResponseEntryTypeDef,
+    ListGeofencesRequestListGeofencesPaginateTypeDef,
     ListGeofencesRequestRequestTypeDef,
+    ListMapsRequestListMapsPaginateTypeDef,
     ListMapsRequestRequestTypeDef,
     ListMapsResponseEntryTypeDef,
+    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
     ListPlaceIndexesRequestRequestTypeDef,
     ListPlaceIndexesResponseEntryTypeDef,
+    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
     ListRouteCalculatorsRequestRequestTypeDef,
     ListRouteCalculatorsResponseEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
     ListTrackerConsumersRequestRequestTypeDef,
+    ListTrackerConsumersResponseTypeDef,
+    ListTrackersRequestListTrackersPaginateTypeDef,
     ListTrackersRequestRequestTypeDef,
     ListTrackersResponseEntryTypeDef,
+    MapConfigurationUpdateTypeDef,
+    PaginatorConfigTypeDef,
     PlaceGeometryTypeDef,
     TimeZoneTypeDef,
+    PutGeofenceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RouteMatrixEntryErrorTypeDef,
     SearchForSuggestionsResultTypeDef,
     SearchPlaceIndexForPositionRequestRequestTypeDef,
     SearchPlaceIndexForPositionSummaryTypeDef,
     SearchPlaceIndexForSuggestionsRequestRequestTypeDef,
     SearchPlaceIndexForSuggestionsSummaryTypeDef,
     SearchPlaceIndexForTextRequestRequestTypeDef,
     SearchPlaceIndexForTextSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGeofenceCollectionRequestRequestTypeDef,
-    UpdateMapRequestRequestTypeDef,
+    UpdateGeofenceCollectionResponseTypeDef,
+    UpdateKeyResponseTypeDef,
+    UpdateMapResponseTypeDef,
+    UpdatePlaceIndexResponseTypeDef,
     UpdateRouteCalculatorRequestRequestTypeDef,
+    UpdateRouteCalculatorResponseTypeDef,
     UpdateTrackerRequestRequestTypeDef,
+    UpdateTrackerResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
+    ListKeysRequestRequestTypeDef,
+    CreateKeyRequestRequestTypeDef,
+    DescribeKeyResponseTypeDef,
+    ListKeysResponseEntryTypeDef,
+    UpdateKeyRequestRequestTypeDef,
     BatchDeleteDevicePositionHistoryErrorTypeDef,
     BatchDeleteGeofenceErrorTypeDef,
     BatchEvaluateGeofencesErrorTypeDef,
     BatchGetDevicePositionErrorTypeDef,
     BatchPutGeofenceErrorTypeDef,
     BatchUpdateDevicePositionErrorTypeDef,
-    CreateGeofenceCollectionResponseTypeDef,
-    CreateMapResponseTypeDef,
-    CreatePlaceIndexResponseTypeDef,
-    CreateRouteCalculatorResponseTypeDef,
-    CreateTrackerResponseTypeDef,
-    DescribeGeofenceCollectionResponseTypeDef,
-    DescribeRouteCalculatorResponseTypeDef,
-    DescribeTrackerResponseTypeDef,
-    GetMapGlyphsResponseTypeDef,
-    GetMapSpritesResponseTypeDef,
-    GetMapStyleDescriptorResponseTypeDef,
-    GetMapTileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTrackerConsumersResponseTypeDef,
-    PutGeofenceResponseTypeDef,
-    UpdateGeofenceCollectionResponseTypeDef,
-    UpdateMapResponseTypeDef,
-    UpdatePlaceIndexResponseTypeDef,
-    UpdateRouteCalculatorResponseTypeDef,
-    UpdateTrackerResponseTypeDef,
     CalculateRouteTruckModeOptionsTypeDef,
     GeofenceGeometryTypeDef,
     CreateMapRequestRequestTypeDef,
     DescribeMapResponseTypeDef,
     CreatePlaceIndexRequestRequestTypeDef,
     DescribePlaceIndexResponseTypeDef,
     UpdatePlaceIndexRequestRequestTypeDef,
     DevicePositionTypeDef,
     DevicePositionUpdateTypeDef,
     GetDevicePositionResponseTypeDef,
     ListDevicePositionsResponseEntryTypeDef,
-    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
-    ListGeofencesRequestListGeofencesPaginateTypeDef,
-    ListMapsRequestListMapsPaginateTypeDef,
-    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
-    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
-    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-    ListTrackersRequestListTrackersPaginateTypeDef,
     LegTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTrackersResponseTypeDef,
+    UpdateMapRequestRequestTypeDef,
     PlaceTypeDef,
     RouteMatrixEntryTypeDef,
     SearchPlaceIndexForSuggestionsResponseTypeDef,
+    ListKeysResponseTypeDef,
     BatchDeleteDevicePositionHistoryResponseTypeDef,
     BatchDeleteGeofenceResponseTypeDef,
     BatchEvaluateGeofencesResponseTypeDef,
     BatchPutGeofenceResponseTypeDef,
     BatchUpdateDevicePositionResponseTypeDef,
     CalculateRouteMatrixRequestRequestTypeDef,
     CalculateRouteRequestRequestTypeDef,
@@ -482,54 +500,54 @@
     BatchPutGeofenceRequestRequestTypeDef,
     ListGeofencesResponseTypeDef,
     SearchPlaceIndexForPositionResponseTypeDef,
     SearchPlaceIndexForTextResponseTypeDef,
 )
 
 
-def get_structure() -> AssociateTrackerConsumerRequestRequestTypeDef:
+def get_structure() -> ApiKeyFilterTypeDef:
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

### Comparing `types-aiobotocore-location-2.5.0.post1/setup.py` & `types-aiobotocore-location-2.5.1/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-location.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-location",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_location"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LocationService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LocationService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/"
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

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__init__.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -7,14 +7,15 @@
     from aiobotocore.session import get_session
     from types_aiobotocore_location import (
         Client,
         GetDevicePositionHistoryPaginator,
         ListDevicePositionsPaginator,
         ListGeofenceCollectionsPaginator,
         ListGeofencesPaginator,
+        ListKeysPaginator,
         ListMapsPaginator,
         ListPlaceIndexesPaginator,
         ListRouteCalculatorsPaginator,
         ListTrackerConsumersPaginator,
         ListTrackersPaginator,
         LocationServiceClient,
     )
@@ -25,27 +26,29 @@
         ...
 
 
     get_device_position_history_paginator: GetDevicePositionHistoryPaginator = client.get_paginator("get_device_position_history")
     list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator("list_device_positions")
     list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator("list_geofence_collections")
     list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+    list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
     list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
     list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator("list_place_indexes")
     list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator("list_route_calculators")
     list_tracker_consumers_paginator: ListTrackerConsumersPaginator = client.get_paginator("list_tracker_consumers")
     list_trackers_paginator: ListTrackersPaginator = client.get_paginator("list_trackers")
     ```
 """
 from .client import LocationServiceClient
 from .paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 
@@ -54,14 +57,15 @@
 
 __all__ = (
     "Client",
     "GetDevicePositionHistoryPaginator",
     "ListDevicePositionsPaginator",
     "ListGeofenceCollectionsPaginator",
     "ListGeofencesPaginator",
+    "ListKeysPaginator",
     "ListMapsPaginator",
     "ListPlaceIndexesPaginator",
     "ListRouteCalculatorsPaginator",
     "ListTrackerConsumersPaginator",
     "ListTrackersPaginator",
     "LocationServiceClient",
 )
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__init__.pyi` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/__init__.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -7,14 +7,15 @@
     from aiobotocore.session import get_session
     from types_aiobotocore_location import (
         Client,
         GetDevicePositionHistoryPaginator,
         ListDevicePositionsPaginator,
         ListGeofenceCollectionsPaginator,
         ListGeofencesPaginator,
+        ListKeysPaginator,
         ListMapsPaginator,
         ListPlaceIndexesPaginator,
         ListRouteCalculatorsPaginator,
         ListTrackerConsumersPaginator,
         ListTrackersPaginator,
         LocationServiceClient,
     )
@@ -25,27 +26,29 @@
         ...
 
 
     get_device_position_history_paginator: GetDevicePositionHistoryPaginator = client.get_paginator("get_device_position_history")
     list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator("list_device_positions")
     list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator("list_geofence_collections")
     list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+    list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
     list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
     list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator("list_place_indexes")
     list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator("list_route_calculators")
     list_tracker_consumers_paginator: ListTrackerConsumersPaginator = client.get_paginator("list_tracker_consumers")
     list_trackers_paginator: ListTrackersPaginator = client.get_paginator("list_trackers")
     ```
 """
 from .client import LocationServiceClient
 from .paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 
@@ -53,14 +56,15 @@
 
 __all__ = (
     "Client",
     "GetDevicePositionHistoryPaginator",
     "ListDevicePositionsPaginator",
     "ListGeofenceCollectionsPaginator",
     "ListGeofencesPaginator",
+    "ListKeysPaginator",
     "ListMapsPaginator",
     "ListPlaceIndexesPaginator",
     "ListRouteCalculatorsPaginator",
     "ListTrackerConsumersPaginator",
     "ListTrackersPaginator",
     "LocationServiceClient",
 )
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/__main__.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LocationService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LocationService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService\nOther"
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

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/client.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -23,39 +23,44 @@
 
 from .literals import DistanceUnitType, PositionFilteringType, PricingPlanType, TravelModeType
 from .paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 from .type_defs import (
+    ApiKeyFilterTypeDef,
+    ApiKeyRestrictionsTypeDef,
     BatchDeleteDevicePositionHistoryResponseTypeDef,
     BatchDeleteGeofenceResponseTypeDef,
     BatchEvaluateGeofencesResponseTypeDef,
     BatchGetDevicePositionResponseTypeDef,
     BatchPutGeofenceRequestEntryTypeDef,
     BatchPutGeofenceResponseTypeDef,
     BatchUpdateDevicePositionResponseTypeDef,
     CalculateRouteCarModeOptionsTypeDef,
     CalculateRouteMatrixResponseTypeDef,
     CalculateRouteResponseTypeDef,
     CalculateRouteTruckModeOptionsTypeDef,
     CreateGeofenceCollectionResponseTypeDef,
+    CreateKeyResponseTypeDef,
     CreateMapResponseTypeDef,
     CreatePlaceIndexResponseTypeDef,
     CreateRouteCalculatorResponseTypeDef,
     CreateTrackerResponseTypeDef,
     DataSourceConfigurationTypeDef,
     DescribeGeofenceCollectionResponseTypeDef,
+    DescribeKeyResponseTypeDef,
     DescribeMapResponseTypeDef,
     DescribePlaceIndexResponseTypeDef,
     DescribeRouteCalculatorResponseTypeDef,
     DescribeTrackerResponseTypeDef,
     DevicePositionUpdateTypeDef,
     GeofenceGeometryTypeDef,
     GetDevicePositionHistoryResponseTypeDef,
@@ -65,26 +70,29 @@
     GetMapSpritesResponseTypeDef,
     GetMapStyleDescriptorResponseTypeDef,
     GetMapTileResponseTypeDef,
     GetPlaceResponseTypeDef,
     ListDevicePositionsResponseTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListGeofencesResponseTypeDef,
+    ListKeysResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrackerConsumersResponseTypeDef,
     ListTrackersResponseTypeDef,
     MapConfigurationTypeDef,
+    MapConfigurationUpdateTypeDef,
     PutGeofenceResponseTypeDef,
     SearchPlaceIndexForPositionResponseTypeDef,
     SearchPlaceIndexForSuggestionsResponseTypeDef,
     SearchPlaceIndexForTextResponseTypeDef,
     UpdateGeofenceCollectionResponseTypeDef,
+    UpdateKeyResponseTypeDef,
     UpdateMapResponseTypeDef,
     UpdatePlaceIndexResponseTypeDef,
     UpdateRouteCalculatorResponseTypeDef,
     UpdateTrackerResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -195,15 +203,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#batch_put_geofence)
         """
 
     async def batch_update_device_position(
         self, *, TrackerName: str, Updates: Sequence[DevicePositionUpdateTypeDef]
     ) -> BatchUpdateDevicePositionResponseTypeDef:
         """
-        Uploads position update data for one or more devices to a tracker resource.
+        Uploads position update data for one or more devices to a tracker resource (up
+        to 10 devices per batch).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_update_device_position)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#batch_update_device_position)
         """
 
     async def calculate_route(
         self,
@@ -282,26 +291,45 @@
         """
         Creates a geofence collection, which manages and stores geofences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_geofence_collection)
         """
 
+    async def create_key(
+        self,
+        *,
+        KeyName: str,
+        Restrictions: ApiKeyRestrictionsTypeDef,
+        Description: str = ...,
+        ExpireTime: Union[datetime, str] = ...,
+        NoExpiry: bool = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateKeyResponseTypeDef:
+        """
+        Creates an API key resource in your Amazon Web Services account, which lets you
+        grant `geo:GetMap*` actions for Amazon Location Map resources to the API key
+        bearer.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_key)
+        """
+
     async def create_map(
         self,
         *,
         Configuration: MapConfigurationTypeDef,
         MapName: str,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateMapResponseTypeDef:
         """
-        Creates a map resource in your AWS account, which provides map tiles of
-        different styles sourced from global location data providers.
+        Creates a map resource in your Amazon Web Services account, which provides map
+        tiles of different styles sourced from global location data providers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_map)
         """
 
     async def create_place_index(
         self,
@@ -310,15 +338,15 @@
         IndexName: str,
         DataSourceConfiguration: DataSourceConfigurationTypeDef = ...,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreatePlaceIndexResponseTypeDef:
         """
-        Creates a place index resource in your AWS account.
+        Creates a place index resource in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_place_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_place_index)
         """
 
     async def create_route_calculator(
         self,
@@ -326,15 +354,15 @@
         CalculatorName: str,
         DataSource: str,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateRouteCalculatorResponseTypeDef:
         """
-        Creates a route calculator resource in your AWS account.
+        Creates a route calculator resource in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_route_calculator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_route_calculator)
         """
 
     async def create_tracker(
         self,
@@ -344,56 +372,64 @@
         KmsKeyId: str = ...,
         PositionFiltering: PositionFilteringType = ...,
         PricingPlan: PricingPlanType = ...,
         PricingPlanDataSource: str = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateTrackerResponseTypeDef:
         """
-        Creates a tracker resource in your AWS account, which lets you retrieve current
-        and historical location of devices.
+        Creates a tracker resource in your Amazon Web Services account, which lets you
+        retrieve current and historical location of devices.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_tracker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_tracker)
         """
 
     async def delete_geofence_collection(self, *, CollectionName: str) -> Dict[str, Any]:
         """
-        Deletes a geofence collection from your AWS account.
+        Deletes a geofence collection from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_geofence_collection)
         """
 
+    async def delete_key(self, *, KeyName: str) -> Dict[str, Any]:
+        """
+        Deletes the specified API key.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_key)
+        """
+
     async def delete_map(self, *, MapName: str) -> Dict[str, Any]:
         """
-        Deletes a map resource from your AWS account.
+        Deletes a map resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_map)
         """
 
     async def delete_place_index(self, *, IndexName: str) -> Dict[str, Any]:
         """
-        Deletes a place index resource from your AWS account.
+        Deletes a place index resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_place_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_place_index)
         """
 
     async def delete_route_calculator(self, *, CalculatorName: str) -> Dict[str, Any]:
         """
-        Deletes a route calculator resource from your AWS account.
+        Deletes a route calculator resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_route_calculator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_route_calculator)
         """
 
     async def delete_tracker(self, *, TrackerName: str) -> Dict[str, Any]:
         """
-        Deletes a tracker resource from your AWS account.
+        Deletes a tracker resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_tracker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_tracker)
         """
 
     async def describe_geofence_collection(
         self, *, CollectionName: str
@@ -401,14 +437,22 @@
         """
         Retrieves the geofence collection details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_geofence_collection)
         """
 
+    async def describe_key(self, *, KeyName: str) -> DescribeKeyResponseTypeDef:
+        """
+        Retrieves the API key resource details.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_key)
+        """
+
     async def describe_map(self, *, MapName: str) -> DescribeMapResponseTypeDef:
         """
         Retrieves the map resource details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_map)
         """
@@ -498,43 +542,45 @@
         Retrieves the geofence details from a geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_geofence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_geofence)
         """
 
     async def get_map_glyphs(
-        self, *, FontStack: str, FontUnicodeRange: str, MapName: str
+        self, *, FontStack: str, FontUnicodeRange: str, MapName: str, Key: str = ...
     ) -> GetMapGlyphsResponseTypeDef:
         """
         Retrieves glyphs used to display labels on a map.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_glyphs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_glyphs)
         """
 
-    async def get_map_sprites(self, *, FileName: str, MapName: str) -> GetMapSpritesResponseTypeDef:
+    async def get_map_sprites(
+        self, *, FileName: str, MapName: str, Key: str = ...
+    ) -> GetMapSpritesResponseTypeDef:
         """
         Retrieves the sprite sheet corresponding to a map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_sprites)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_sprites)
         """
 
     async def get_map_style_descriptor(
-        self, *, MapName: str
+        self, *, MapName: str, Key: str = ...
     ) -> GetMapStyleDescriptorResponseTypeDef:
         """
         Retrieves the map style descriptor from a map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_style_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_style_descriptor)
         """
 
     async def get_map_tile(
-        self, *, MapName: str, X: str, Y: str, Z: str
+        self, *, MapName: str, X: str, Y: str, Z: str, Key: str = ...
     ) -> GetMapTileResponseTypeDef:
         """
         Retrieves a vector data tile from the map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_tile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_tile)
         """
@@ -559,15 +605,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_device_positions)
         """
 
     async def list_geofence_collections(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListGeofenceCollectionsResponseTypeDef:
         """
-        Lists geofence collections in your AWS account.
+        Lists geofence collections in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofence_collections)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_geofence_collections)
         """
 
     async def list_geofences(
         self, *, CollectionName: str, MaxResults: int = ..., NextToken: str = ...
@@ -575,39 +621,49 @@
         """
         Lists geofences stored in a given geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_geofences)
         """
 
+    async def list_keys(
+        self, *, Filter: ApiKeyFilterTypeDef = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListKeysResponseTypeDef:
+        """
+        Lists API key resources in your Amazon Web Services account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_keys)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_keys)
+        """
+
     async def list_maps(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListMapsResponseTypeDef:
         """
-        Lists map resources in your AWS account.
+        Lists map resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_maps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_maps)
         """
 
     async def list_place_indexes(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListPlaceIndexesResponseTypeDef:
         """
-        Lists place index resources in your AWS account.
+        Lists place index resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_place_indexes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_place_indexes)
         """
 
     async def list_route_calculators(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListRouteCalculatorsResponseTypeDef:
         """
-        Lists route calculator resources in your AWS account.
+        Lists route calculator resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_route_calculators)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_route_calculators)
         """
 
     async def list_tags_for_resource(
         self, *, ResourceArn: str
@@ -630,22 +686,27 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_tracker_consumers)
         """
 
     async def list_trackers(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListTrackersResponseTypeDef:
         """
-        Lists tracker resources in your AWS account.
+        Lists tracker resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_trackers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_trackers)
         """
 
     async def put_geofence(
-        self, *, CollectionName: str, GeofenceId: str, Geometry: GeofenceGeometryTypeDef
+        self,
+        *,
+        CollectionName: str,
+        GeofenceId: str,
+        Geometry: GeofenceGeometryTypeDef,
+        GeofenceProperties: Mapping[str, str] = ...
     ) -> PutGeofenceResponseTypeDef:
         """
         Stores a geofence geometry in a given geofence collection, or updates the
         geometry of an existing geofence if a geofence ID is included in the request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.put_geofence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#put_geofence)
@@ -669,14 +730,15 @@
     async def search_place_index_for_suggestions(
         self,
         *,
         IndexName: str,
         Text: str,
         BiasPosition: Sequence[float] = ...,
         FilterBBox: Sequence[float] = ...,
+        FilterCategories: Sequence[str] = ...,
         FilterCountries: Sequence[str] = ...,
         Language: str = ...,
         MaxResults: int = ...
     ) -> SearchPlaceIndexForSuggestionsResponseTypeDef:
         """
         Generates suggestions for addresses and points of interest based on partial or
         misspelled free-form text.
@@ -688,14 +750,15 @@
     async def search_place_index_for_text(
         self,
         *,
         IndexName: str,
         Text: str,
         BiasPosition: Sequence[float] = ...,
         FilterBBox: Sequence[float] = ...,
+        FilterCategories: Sequence[str] = ...,
         FilterCountries: Sequence[str] = ...,
         Language: str = ...,
         MaxResults: int = ...
     ) -> SearchPlaceIndexForTextResponseTypeDef:
         """
         Geocodes free-form text, such as an address, name, city, or region to allow you
         to search for Places or points of interest.
@@ -732,16 +795,38 @@
         """
         Updates the specified properties of a given geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_geofence_collection)
         """
 
+    async def update_key(
+        self,
+        *,
+        KeyName: str,
+        Description: str = ...,
+        ExpireTime: Union[datetime, str] = ...,
+        ForceUpdate: bool = ...,
+        NoExpiry: bool = ...,
+        Restrictions: ApiKeyRestrictionsTypeDef = ...
+    ) -> UpdateKeyResponseTypeDef:
+        """
+        Updates the specified properties of a given API key resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_key)
+        """
+
     async def update_map(
-        self, *, MapName: str, Description: str = ..., PricingPlan: PricingPlanType = ...
+        self,
+        *,
+        MapName: str,
+        ConfigurationUpdate: MapConfigurationUpdateTypeDef = ...,
+        Description: str = ...,
+        PricingPlan: PricingPlanType = ...
     ) -> UpdateMapResponseTypeDef:
         """
         Updates the specified properties of a given map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_map)
         """
@@ -818,14 +903,21 @@
     def get_paginator(self, operation_name: Literal["list_geofences"]) -> ListGeofencesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(self, operation_name: Literal["list_keys"]) -> ListKeysPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_maps"]) -> ListMapsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/client.pyi` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -23,39 +23,44 @@
 
 from .literals import DistanceUnitType, PositionFilteringType, PricingPlanType, TravelModeType
 from .paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 from .type_defs import (
+    ApiKeyFilterTypeDef,
+    ApiKeyRestrictionsTypeDef,
     BatchDeleteDevicePositionHistoryResponseTypeDef,
     BatchDeleteGeofenceResponseTypeDef,
     BatchEvaluateGeofencesResponseTypeDef,
     BatchGetDevicePositionResponseTypeDef,
     BatchPutGeofenceRequestEntryTypeDef,
     BatchPutGeofenceResponseTypeDef,
     BatchUpdateDevicePositionResponseTypeDef,
     CalculateRouteCarModeOptionsTypeDef,
     CalculateRouteMatrixResponseTypeDef,
     CalculateRouteResponseTypeDef,
     CalculateRouteTruckModeOptionsTypeDef,
     CreateGeofenceCollectionResponseTypeDef,
+    CreateKeyResponseTypeDef,
     CreateMapResponseTypeDef,
     CreatePlaceIndexResponseTypeDef,
     CreateRouteCalculatorResponseTypeDef,
     CreateTrackerResponseTypeDef,
     DataSourceConfigurationTypeDef,
     DescribeGeofenceCollectionResponseTypeDef,
+    DescribeKeyResponseTypeDef,
     DescribeMapResponseTypeDef,
     DescribePlaceIndexResponseTypeDef,
     DescribeRouteCalculatorResponseTypeDef,
     DescribeTrackerResponseTypeDef,
     DevicePositionUpdateTypeDef,
     GeofenceGeometryTypeDef,
     GetDevicePositionHistoryResponseTypeDef,
@@ -65,26 +70,29 @@
     GetMapSpritesResponseTypeDef,
     GetMapStyleDescriptorResponseTypeDef,
     GetMapTileResponseTypeDef,
     GetPlaceResponseTypeDef,
     ListDevicePositionsResponseTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListGeofencesResponseTypeDef,
+    ListKeysResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrackerConsumersResponseTypeDef,
     ListTrackersResponseTypeDef,
     MapConfigurationTypeDef,
+    MapConfigurationUpdateTypeDef,
     PutGeofenceResponseTypeDef,
     SearchPlaceIndexForPositionResponseTypeDef,
     SearchPlaceIndexForSuggestionsResponseTypeDef,
     SearchPlaceIndexForTextResponseTypeDef,
     UpdateGeofenceCollectionResponseTypeDef,
+    UpdateKeyResponseTypeDef,
     UpdateMapResponseTypeDef,
     UpdatePlaceIndexResponseTypeDef,
     UpdateRouteCalculatorResponseTypeDef,
     UpdateTrackerResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -184,15 +192,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_put_geofence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#batch_put_geofence)
         """
     async def batch_update_device_position(
         self, *, TrackerName: str, Updates: Sequence[DevicePositionUpdateTypeDef]
     ) -> BatchUpdateDevicePositionResponseTypeDef:
         """
-        Uploads position update data for one or more devices to a tracker resource.
+        Uploads position update data for one or more devices to a tracker resource (up
+        to 10 devices per batch).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.batch_update_device_position)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#batch_update_device_position)
         """
     async def calculate_route(
         self,
         *,
@@ -265,26 +274,44 @@
     ) -> CreateGeofenceCollectionResponseTypeDef:
         """
         Creates a geofence collection, which manages and stores geofences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_geofence_collection)
         """
+    async def create_key(
+        self,
+        *,
+        KeyName: str,
+        Restrictions: ApiKeyRestrictionsTypeDef,
+        Description: str = ...,
+        ExpireTime: Union[datetime, str] = ...,
+        NoExpiry: bool = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateKeyResponseTypeDef:
+        """
+        Creates an API key resource in your Amazon Web Services account, which lets you
+        grant `geo:GetMap*` actions for Amazon Location Map resources to the API key
+        bearer.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_key)
+        """
     async def create_map(
         self,
         *,
         Configuration: MapConfigurationTypeDef,
         MapName: str,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateMapResponseTypeDef:
         """
-        Creates a map resource in your AWS account, which provides map tiles of
-        different styles sourced from global location data providers.
+        Creates a map resource in your Amazon Web Services account, which provides map
+        tiles of different styles sourced from global location data providers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_map)
         """
     async def create_place_index(
         self,
         *,
@@ -292,30 +319,30 @@
         IndexName: str,
         DataSourceConfiguration: DataSourceConfigurationTypeDef = ...,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreatePlaceIndexResponseTypeDef:
         """
-        Creates a place index resource in your AWS account.
+        Creates a place index resource in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_place_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_place_index)
         """
     async def create_route_calculator(
         self,
         *,
         CalculatorName: str,
         DataSource: str,
         Description: str = ...,
         PricingPlan: PricingPlanType = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateRouteCalculatorResponseTypeDef:
         """
-        Creates a route calculator resource in your AWS account.
+        Creates a route calculator resource in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_route_calculator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_route_calculator)
         """
     async def create_tracker(
         self,
         *,
@@ -324,64 +351,78 @@
         KmsKeyId: str = ...,
         PositionFiltering: PositionFilteringType = ...,
         PricingPlan: PricingPlanType = ...,
         PricingPlanDataSource: str = ...,
         Tags: Mapping[str, str] = ...
     ) -> CreateTrackerResponseTypeDef:
         """
-        Creates a tracker resource in your AWS account, which lets you retrieve current
-        and historical location of devices.
+        Creates a tracker resource in your Amazon Web Services account, which lets you
+        retrieve current and historical location of devices.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.create_tracker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#create_tracker)
         """
     async def delete_geofence_collection(self, *, CollectionName: str) -> Dict[str, Any]:
         """
-        Deletes a geofence collection from your AWS account.
+        Deletes a geofence collection from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_geofence_collection)
         """
+    async def delete_key(self, *, KeyName: str) -> Dict[str, Any]:
+        """
+        Deletes the specified API key.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_key)
+        """
     async def delete_map(self, *, MapName: str) -> Dict[str, Any]:
         """
-        Deletes a map resource from your AWS account.
+        Deletes a map resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_map)
         """
     async def delete_place_index(self, *, IndexName: str) -> Dict[str, Any]:
         """
-        Deletes a place index resource from your AWS account.
+        Deletes a place index resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_place_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_place_index)
         """
     async def delete_route_calculator(self, *, CalculatorName: str) -> Dict[str, Any]:
         """
-        Deletes a route calculator resource from your AWS account.
+        Deletes a route calculator resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_route_calculator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_route_calculator)
         """
     async def delete_tracker(self, *, TrackerName: str) -> Dict[str, Any]:
         """
-        Deletes a tracker resource from your AWS account.
+        Deletes a tracker resource from your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.delete_tracker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#delete_tracker)
         """
     async def describe_geofence_collection(
         self, *, CollectionName: str
     ) -> DescribeGeofenceCollectionResponseTypeDef:
         """
         Retrieves the geofence collection details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_geofence_collection)
         """
+    async def describe_key(self, *, KeyName: str) -> DescribeKeyResponseTypeDef:
+        """
+        Retrieves the API key resource details.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_key)
+        """
     async def describe_map(self, *, MapName: str) -> DescribeMapResponseTypeDef:
         """
         Retrieves the map resource details.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.describe_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#describe_map)
         """
@@ -462,40 +503,42 @@
         """
         Retrieves the geofence details from a geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_geofence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_geofence)
         """
     async def get_map_glyphs(
-        self, *, FontStack: str, FontUnicodeRange: str, MapName: str
+        self, *, FontStack: str, FontUnicodeRange: str, MapName: str, Key: str = ...
     ) -> GetMapGlyphsResponseTypeDef:
         """
         Retrieves glyphs used to display labels on a map.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_glyphs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_glyphs)
         """
-    async def get_map_sprites(self, *, FileName: str, MapName: str) -> GetMapSpritesResponseTypeDef:
+    async def get_map_sprites(
+        self, *, FileName: str, MapName: str, Key: str = ...
+    ) -> GetMapSpritesResponseTypeDef:
         """
         Retrieves the sprite sheet corresponding to a map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_sprites)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_sprites)
         """
     async def get_map_style_descriptor(
-        self, *, MapName: str
+        self, *, MapName: str, Key: str = ...
     ) -> GetMapStyleDescriptorResponseTypeDef:
         """
         Retrieves the map style descriptor from a map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_style_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_style_descriptor)
         """
     async def get_map_tile(
-        self, *, MapName: str, X: str, Y: str, Z: str
+        self, *, MapName: str, X: str, Y: str, Z: str, Key: str = ...
     ) -> GetMapTileResponseTypeDef:
         """
         Retrieves a vector data tile from the map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_map_tile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_map_tile)
         """
@@ -517,51 +560,60 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_device_positions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_device_positions)
         """
     async def list_geofence_collections(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListGeofenceCollectionsResponseTypeDef:
         """
-        Lists geofence collections in your AWS account.
+        Lists geofence collections in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofence_collections)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_geofence_collections)
         """
     async def list_geofences(
         self, *, CollectionName: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListGeofencesResponseTypeDef:
         """
         Lists geofences stored in a given geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_geofences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_geofences)
         """
+    async def list_keys(
+        self, *, Filter: ApiKeyFilterTypeDef = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListKeysResponseTypeDef:
+        """
+        Lists API key resources in your Amazon Web Services account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_keys)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_keys)
+        """
     async def list_maps(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListMapsResponseTypeDef:
         """
-        Lists map resources in your AWS account.
+        Lists map resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_maps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_maps)
         """
     async def list_place_indexes(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListPlaceIndexesResponseTypeDef:
         """
-        Lists place index resources in your AWS account.
+        Lists place index resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_place_indexes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_place_indexes)
         """
     async def list_route_calculators(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListRouteCalculatorsResponseTypeDef:
         """
-        Lists route calculator resources in your AWS account.
+        Lists route calculator resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_route_calculators)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_route_calculators)
         """
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
@@ -581,21 +633,26 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_tracker_consumers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_tracker_consumers)
         """
     async def list_trackers(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListTrackersResponseTypeDef:
         """
-        Lists tracker resources in your AWS account.
+        Lists tracker resources in your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.list_trackers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#list_trackers)
         """
     async def put_geofence(
-        self, *, CollectionName: str, GeofenceId: str, Geometry: GeofenceGeometryTypeDef
+        self,
+        *,
+        CollectionName: str,
+        GeofenceId: str,
+        Geometry: GeofenceGeometryTypeDef,
+        GeofenceProperties: Mapping[str, str] = ...
     ) -> PutGeofenceResponseTypeDef:
         """
         Stores a geofence geometry in a given geofence collection, or updates the
         geometry of an existing geofence if a geofence ID is included in the request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.put_geofence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#put_geofence)
@@ -617,14 +674,15 @@
     async def search_place_index_for_suggestions(
         self,
         *,
         IndexName: str,
         Text: str,
         BiasPosition: Sequence[float] = ...,
         FilterBBox: Sequence[float] = ...,
+        FilterCategories: Sequence[str] = ...,
         FilterCountries: Sequence[str] = ...,
         Language: str = ...,
         MaxResults: int = ...
     ) -> SearchPlaceIndexForSuggestionsResponseTypeDef:
         """
         Generates suggestions for addresses and points of interest based on partial or
         misspelled free-form text.
@@ -635,14 +693,15 @@
     async def search_place_index_for_text(
         self,
         *,
         IndexName: str,
         Text: str,
         BiasPosition: Sequence[float] = ...,
         FilterBBox: Sequence[float] = ...,
+        FilterCategories: Sequence[str] = ...,
         FilterCountries: Sequence[str] = ...,
         Language: str = ...,
         MaxResults: int = ...
     ) -> SearchPlaceIndexForTextResponseTypeDef:
         """
         Geocodes free-form text, such as an address, name, city, or region to allow you
         to search for Places or points of interest.
@@ -675,16 +734,37 @@
     ) -> UpdateGeofenceCollectionResponseTypeDef:
         """
         Updates the specified properties of a given geofence collection.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_geofence_collection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_geofence_collection)
         """
+    async def update_key(
+        self,
+        *,
+        KeyName: str,
+        Description: str = ...,
+        ExpireTime: Union[datetime, str] = ...,
+        ForceUpdate: bool = ...,
+        NoExpiry: bool = ...,
+        Restrictions: ApiKeyRestrictionsTypeDef = ...
+    ) -> UpdateKeyResponseTypeDef:
+        """
+        Updates the specified properties of a given API key resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_key)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_key)
+        """
     async def update_map(
-        self, *, MapName: str, Description: str = ..., PricingPlan: PricingPlanType = ...
+        self,
+        *,
+        MapName: str,
+        ConfigurationUpdate: MapConfigurationUpdateTypeDef = ...,
+        Description: str = ...,
+        PricingPlan: PricingPlanType = ...
     ) -> UpdateMapResponseTypeDef:
         """
         Updates the specified properties of a given map resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.update_map)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#update_map)
         """
@@ -753,14 +833,20 @@
     @overload
     def get_paginator(self, operation_name: Literal["list_geofences"]) -> ListGeofencesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
         """
     @overload
+    def get_paginator(self, operation_name: Literal["list_keys"]) -> ListKeysPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_maps"]) -> ListMapsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/client/#get_paginator)
         """
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/literals.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/literals.py`

 * *Files 0% similar despite different names*

```diff
@@ -24,22 +24,24 @@
     "DimensionUnitType",
     "DistanceUnitType",
     "GetDevicePositionHistoryPaginatorName",
     "IntendedUseType",
     "ListDevicePositionsPaginatorName",
     "ListGeofenceCollectionsPaginatorName",
     "ListGeofencesPaginatorName",
+    "ListKeysPaginatorName",
     "ListMapsPaginatorName",
     "ListPlaceIndexesPaginatorName",
     "ListRouteCalculatorsPaginatorName",
     "ListTrackerConsumersPaginatorName",
     "ListTrackersPaginatorName",
     "PositionFilteringType",
     "PricingPlanType",
     "RouteMatrixErrorCodeType",
+    "StatusType",
     "TravelModeType",
     "VehicleWeightUnitType",
     "LocationServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
@@ -57,14 +59,15 @@
 DimensionUnitType = Literal["Feet", "Meters"]
 DistanceUnitType = Literal["Kilometers", "Miles"]
 GetDevicePositionHistoryPaginatorName = Literal["get_device_position_history"]
 IntendedUseType = Literal["SingleUse", "Storage"]
 ListDevicePositionsPaginatorName = Literal["list_device_positions"]
 ListGeofenceCollectionsPaginatorName = Literal["list_geofence_collections"]
 ListGeofencesPaginatorName = Literal["list_geofences"]
+ListKeysPaginatorName = Literal["list_keys"]
 ListMapsPaginatorName = Literal["list_maps"]
 ListPlaceIndexesPaginatorName = Literal["list_place_indexes"]
 ListRouteCalculatorsPaginatorName = Literal["list_route_calculators"]
 ListTrackerConsumersPaginatorName = Literal["list_tracker_consumers"]
 ListTrackersPaginatorName = Literal["list_trackers"]
 PositionFilteringType = Literal["AccuracyBased", "DistanceBased", "TimeBased"]
 PricingPlanType = Literal["MobileAssetManagement", "MobileAssetTracking", "RequestBasedUsage"]
@@ -72,14 +75,15 @@
     "DeparturePositionNotFound",
     "DestinationPositionNotFound",
     "OtherValidationError",
     "PositionsNotFound",
     "RouteNotFound",
     "RouteTooLong",
 ]
+StatusType = Literal["Active", "Expired"]
 TravelModeType = Literal["Bicycle", "Car", "Motorcycle", "Truck", "Walking"]
 VehicleWeightUnitType = Literal["Kilograms", "Pounds"]
 LocationServiceServiceName = Literal["location"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -137,14 +141,15 @@
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
@@ -223,14 +228,15 @@
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
@@ -241,14 +247,15 @@
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
@@ -284,14 +291,15 @@
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
@@ -310,16 +318,19 @@
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
@@ -403,15 +414,17 @@
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
@@ -434,14 +447,15 @@
     "sqs",
 ]
 PaginatorName = Literal[
     "get_device_position_history",
     "list_device_positions",
     "list_geofence_collections",
     "list_geofences",
+    "list_keys",
     "list_maps",
     "list_place_indexes",
     "list_route_calculators",
     "list_tracker_consumers",
     "list_trackers",
 ]
 RegionName = Literal[
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/literals.pyi` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/literals.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -23,22 +23,24 @@
     "DimensionUnitType",
     "DistanceUnitType",
     "GetDevicePositionHistoryPaginatorName",
     "IntendedUseType",
     "ListDevicePositionsPaginatorName",
     "ListGeofenceCollectionsPaginatorName",
     "ListGeofencesPaginatorName",
+    "ListKeysPaginatorName",
     "ListMapsPaginatorName",
     "ListPlaceIndexesPaginatorName",
     "ListRouteCalculatorsPaginatorName",
     "ListTrackerConsumersPaginatorName",
     "ListTrackersPaginatorName",
     "PositionFilteringType",
     "PricingPlanType",
     "RouteMatrixErrorCodeType",
+    "StatusType",
     "TravelModeType",
     "VehicleWeightUnitType",
     "LocationServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
@@ -55,14 +57,15 @@
 DimensionUnitType = Literal["Feet", "Meters"]
 DistanceUnitType = Literal["Kilometers", "Miles"]
 GetDevicePositionHistoryPaginatorName = Literal["get_device_position_history"]
 IntendedUseType = Literal["SingleUse", "Storage"]
 ListDevicePositionsPaginatorName = Literal["list_device_positions"]
 ListGeofenceCollectionsPaginatorName = Literal["list_geofence_collections"]
 ListGeofencesPaginatorName = Literal["list_geofences"]
+ListKeysPaginatorName = Literal["list_keys"]
 ListMapsPaginatorName = Literal["list_maps"]
 ListPlaceIndexesPaginatorName = Literal["list_place_indexes"]
 ListRouteCalculatorsPaginatorName = Literal["list_route_calculators"]
 ListTrackerConsumersPaginatorName = Literal["list_tracker_consumers"]
 ListTrackersPaginatorName = Literal["list_trackers"]
 PositionFilteringType = Literal["AccuracyBased", "DistanceBased", "TimeBased"]
 PricingPlanType = Literal["MobileAssetManagement", "MobileAssetTracking", "RequestBasedUsage"]
@@ -70,14 +73,15 @@
     "DeparturePositionNotFound",
     "DestinationPositionNotFound",
     "OtherValidationError",
     "PositionsNotFound",
     "RouteNotFound",
     "RouteTooLong",
 ]
+StatusType = Literal["Active", "Expired"]
 TravelModeType = Literal["Bicycle", "Car", "Motorcycle", "Truck", "Walking"]
 VehicleWeightUnitType = Literal["Kilograms", "Pounds"]
 LocationServiceServiceName = Literal["location"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -135,14 +139,15 @@
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
@@ -221,14 +226,15 @@
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
@@ -239,14 +245,15 @@
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
@@ -282,14 +289,15 @@
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
@@ -308,16 +316,19 @@
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
@@ -401,15 +412,17 @@
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
@@ -432,14 +445,15 @@
     "sqs",
 ]
 PaginatorName = Literal[
     "get_device_position_history",
     "list_device_positions",
     "list_geofence_collections",
     "list_geofences",
+    "list_keys",
     "list_maps",
     "list_place_indexes",
     "list_route_calculators",
     "list_tracker_consumers",
     "list_trackers",
 ]
 RegionName = Literal[
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/paginator.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 
     from types_aiobotocore_location.client import LocationServiceClient
     from types_aiobotocore_location.paginator import (
         GetDevicePositionHistoryPaginator,
         ListDevicePositionsPaginator,
         ListGeofenceCollectionsPaginator,
         ListGeofencesPaginator,
+        ListKeysPaginator,
         ListMapsPaginator,
         ListPlaceIndexesPaginator,
         ListRouteCalculatorsPaginator,
         ListTrackerConsumersPaginator,
         ListTrackersPaginator,
     )
 
@@ -25,52 +26,49 @@
     with session.create_client("location") as client:
         client: LocationServiceClient
 
         get_device_position_history_paginator: GetDevicePositionHistoryPaginator = client.get_paginator("get_device_position_history")
         list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator("list_device_positions")
         list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator("list_geofence_collections")
         list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+        list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
         list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
         list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator("list_place_indexes")
         list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator("list_route_calculators")
         list_tracker_consumers_paginator: ListTrackerConsumersPaginator = client.get_paginator("list_tracker_consumers")
         list_trackers_paginator: ListTrackersPaginator = client.get_paginator("list_trackers")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
+    ApiKeyFilterTypeDef,
     GetDevicePositionHistoryResponseTypeDef,
     ListDevicePositionsResponseTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListGeofencesResponseTypeDef,
+    ListKeysResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTrackerConsumersResponseTypeDef,
     ListTrackersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetDevicePositionHistoryPaginator",
     "ListDevicePositionsPaginator",
     "ListGeofenceCollectionsPaginator",
     "ListGeofencesPaginator",
+    "ListKeysPaginator",
     "ListMapsPaginator",
     "ListPlaceIndexesPaginator",
     "ListRouteCalculatorsPaginator",
     "ListTrackerConsumersPaginator",
     "ListTrackersPaginator",
 )
 
@@ -94,133 +92,148 @@
     def paginate(
         self,
         *,
         DeviceId: str,
         TrackerName: str,
         EndTimeExclusive: Union[datetime, str] = ...,
         StartTimeInclusive: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevicePositionHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.GetDevicePositionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#getdevicepositionhistorypaginator)
         """
 
 
 class ListDevicePositionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListDevicePositions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listdevicepositionspaginator)
     """
 
     def paginate(
-        self, *, TrackerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TrackerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicePositionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListDevicePositions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listdevicepositionspaginator)
         """
 
 
 class ListGeofenceCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofenceCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencecollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeofenceCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofenceCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencecollectionspaginator)
         """
 
 
 class ListGeofencesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofences)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencespaginator)
     """
 
     def paginate(
-        self, *, CollectionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CollectionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeofencesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofences.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencespaginator)
         """
 
 
+class ListKeysPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListKeys)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listkeyspaginator)
+    """
+
+    def paginate(
+        self, *, Filter: ApiKeyFilterTypeDef = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListKeysResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListKeys.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listkeyspaginator)
+        """
+
+
 class ListMapsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListMaps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listmapspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMapsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListMaps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listmapspaginator)
         """
 
 
 class ListPlaceIndexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListPlaceIndexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listplaceindexespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaceIndexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListPlaceIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listplaceindexespaginator)
         """
 
 
 class ListRouteCalculatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListRouteCalculators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listroutecalculatorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRouteCalculatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListRouteCalculators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listroutecalculatorspaginator)
         """
 
 
 class ListTrackerConsumersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackerConsumers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerconsumerspaginator)
     """
 
     def paginate(
-        self, *, TrackerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TrackerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrackerConsumersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackerConsumers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerconsumerspaginator)
         """
 
 
 class ListTrackersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrackersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerspaginator)
         """
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/paginator.pyi` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 
     from types_aiobotocore_location.client import LocationServiceClient
     from types_aiobotocore_location.paginator import (
         GetDevicePositionHistoryPaginator,
         ListDevicePositionsPaginator,
         ListGeofenceCollectionsPaginator,
         ListGeofencesPaginator,
+        ListKeysPaginator,
         ListMapsPaginator,
         ListPlaceIndexesPaginator,
         ListRouteCalculatorsPaginator,
         ListTrackerConsumersPaginator,
         ListTrackersPaginator,
     )
 
@@ -25,51 +26,49 @@
     with session.create_client("location") as client:
         client: LocationServiceClient
 
         get_device_position_history_paginator: GetDevicePositionHistoryPaginator = client.get_paginator("get_device_position_history")
         list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator("list_device_positions")
         list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator("list_geofence_collections")
         list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+        list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
         list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
         list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator("list_place_indexes")
         list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator("list_route_calculators")
         list_tracker_consumers_paginator: ListTrackerConsumersPaginator = client.get_paginator("list_tracker_consumers")
         list_trackers_paginator: ListTrackersPaginator = client.get_paginator("list_trackers")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
+    ApiKeyFilterTypeDef,
     GetDevicePositionHistoryResponseTypeDef,
     ListDevicePositionsResponseTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListGeofencesResponseTypeDef,
+    ListKeysResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTrackerConsumersResponseTypeDef,
     ListTrackersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetDevicePositionHistoryPaginator",
     "ListDevicePositionsPaginator",
     "ListGeofenceCollectionsPaginator",
     "ListGeofencesPaginator",
+    "ListKeysPaginator",
     "ListMapsPaginator",
     "ListPlaceIndexesPaginator",
     "ListRouteCalculatorsPaginator",
     "ListTrackerConsumersPaginator",
     "ListTrackersPaginator",
 )
 
@@ -90,125 +89,139 @@
     def paginate(
         self,
         *,
         DeviceId: str,
         TrackerName: str,
         EndTimeExclusive: Union[datetime, str] = ...,
         StartTimeInclusive: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevicePositionHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.GetDevicePositionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#getdevicepositionhistorypaginator)
         """
 
 class ListDevicePositionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListDevicePositions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listdevicepositionspaginator)
     """
 
     def paginate(
-        self, *, TrackerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TrackerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicePositionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListDevicePositions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listdevicepositionspaginator)
         """
 
 class ListGeofenceCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofenceCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencecollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeofenceCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofenceCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencecollectionspaginator)
         """
 
 class ListGeofencesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofences)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencespaginator)
     """
 
     def paginate(
-        self, *, CollectionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CollectionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeofencesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListGeofences.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listgeofencespaginator)
         """
 
+class ListKeysPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListKeys)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listkeyspaginator)
+    """
+
+    def paginate(
+        self, *, Filter: ApiKeyFilterTypeDef = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListKeysResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListKeys.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listkeyspaginator)
+        """
+
 class ListMapsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListMaps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listmapspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMapsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListMaps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listmapspaginator)
         """
 
 class ListPlaceIndexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListPlaceIndexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listplaceindexespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaceIndexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListPlaceIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listplaceindexespaginator)
         """
 
 class ListRouteCalculatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListRouteCalculators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listroutecalculatorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRouteCalculatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListRouteCalculators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listroutecalculatorspaginator)
         """
 
 class ListTrackerConsumersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackerConsumers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerconsumerspaginator)
     """
 
     def paginate(
-        self, *, TrackerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TrackerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrackerConsumersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackerConsumers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerconsumerspaginator)
         """
 
 class ListTrackersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrackersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService.Paginator.ListTrackers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/paginators/#listtrackerspaginator)
         """
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/type_defs.py` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for location service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_location.type_defs import AssociateTrackerConsumerRequestRequestTypeDef
+    from types_aiobotocore_location.type_defs import ApiKeyFilterTypeDef
 
-    data: AssociateTrackerConsumerRequestRequestTypeDef = {...}
+    data: ApiKeyFilterTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -21,151 +21,165 @@
     BatchItemErrorCodeType,
     DimensionUnitType,
     DistanceUnitType,
     IntendedUseType,
     PositionFilteringType,
     PricingPlanType,
     RouteMatrixErrorCodeType,
+    StatusType,
     TravelModeType,
     VehicleWeightUnitType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
+    "ApiKeyFilterTypeDef",
+    "ApiKeyRestrictionsTypeDef",
     "AssociateTrackerConsumerRequestRequestTypeDef",
     "BatchItemErrorTypeDef",
     "BatchDeleteDevicePositionHistoryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteGeofenceRequestRequestTypeDef",
     "BatchGetDevicePositionRequestRequestTypeDef",
     "BatchPutGeofenceSuccessTypeDef",
     "CalculateRouteCarModeOptionsTypeDef",
     "CalculateRouteMatrixSummaryTypeDef",
     "CalculateRouteSummaryTypeDef",
     "TruckDimensionsTypeDef",
     "TruckWeightTypeDef",
     "CircleTypeDef",
     "CreateGeofenceCollectionRequestRequestTypeDef",
+    "CreateGeofenceCollectionResponseTypeDef",
+    "CreateKeyResponseTypeDef",
     "MapConfigurationTypeDef",
+    "CreateMapResponseTypeDef",
     "DataSourceConfigurationTypeDef",
+    "CreatePlaceIndexResponseTypeDef",
     "CreateRouteCalculatorRequestRequestTypeDef",
+    "CreateRouteCalculatorResponseTypeDef",
     "CreateTrackerRequestRequestTypeDef",
+    "CreateTrackerResponseTypeDef",
     "DeleteGeofenceCollectionRequestRequestTypeDef",
+    "DeleteKeyRequestRequestTypeDef",
     "DeleteMapRequestRequestTypeDef",
     "DeletePlaceIndexRequestRequestTypeDef",
     "DeleteRouteCalculatorRequestRequestTypeDef",
     "DeleteTrackerRequestRequestTypeDef",
     "DescribeGeofenceCollectionRequestRequestTypeDef",
+    "DescribeGeofenceCollectionResponseTypeDef",
+    "DescribeKeyRequestRequestTypeDef",
     "DescribeMapRequestRequestTypeDef",
     "DescribePlaceIndexRequestRequestTypeDef",
     "DescribeRouteCalculatorRequestRequestTypeDef",
+    "DescribeRouteCalculatorResponseTypeDef",
     "DescribeTrackerRequestRequestTypeDef",
+    "DescribeTrackerResponseTypeDef",
     "PositionalAccuracyTypeDef",
     "DisassociateTrackerConsumerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
     "GetDevicePositionHistoryRequestRequestTypeDef",
     "GetDevicePositionRequestRequestTypeDef",
     "GetGeofenceRequestRequestTypeDef",
     "GetMapGlyphsRequestRequestTypeDef",
+    "GetMapGlyphsResponseTypeDef",
     "GetMapSpritesRequestRequestTypeDef",
+    "GetMapSpritesResponseTypeDef",
     "GetMapStyleDescriptorRequestRequestTypeDef",
+    "GetMapStyleDescriptorResponseTypeDef",
     "GetMapTileRequestRequestTypeDef",
+    "GetMapTileResponseTypeDef",
     "GetPlaceRequestRequestTypeDef",
     "LegGeometryTypeDef",
     "StepTypeDef",
+    "ListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
     "ListDevicePositionsRequestRequestTypeDef",
+    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
     "ListGeofenceCollectionsRequestRequestTypeDef",
     "ListGeofenceCollectionsResponseEntryTypeDef",
+    "ListGeofencesRequestListGeofencesPaginateTypeDef",
     "ListGeofencesRequestRequestTypeDef",
+    "ListMapsRequestListMapsPaginateTypeDef",
     "ListMapsRequestRequestTypeDef",
     "ListMapsResponseEntryTypeDef",
+    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
     "ListPlaceIndexesRequestRequestTypeDef",
     "ListPlaceIndexesResponseEntryTypeDef",
+    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
     "ListRouteCalculatorsRequestRequestTypeDef",
     "ListRouteCalculatorsResponseEntryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
     "ListTrackerConsumersRequestRequestTypeDef",
+    "ListTrackerConsumersResponseTypeDef",
+    "ListTrackersRequestListTrackersPaginateTypeDef",
     "ListTrackersRequestRequestTypeDef",
     "ListTrackersResponseEntryTypeDef",
+    "MapConfigurationUpdateTypeDef",
+    "PaginatorConfigTypeDef",
     "PlaceGeometryTypeDef",
     "TimeZoneTypeDef",
+    "PutGeofenceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RouteMatrixEntryErrorTypeDef",
     "SearchForSuggestionsResultTypeDef",
     "SearchPlaceIndexForPositionRequestRequestTypeDef",
     "SearchPlaceIndexForPositionSummaryTypeDef",
     "SearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     "SearchPlaceIndexForSuggestionsSummaryTypeDef",
     "SearchPlaceIndexForTextRequestRequestTypeDef",
     "SearchPlaceIndexForTextSummaryTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateGeofenceCollectionRequestRequestTypeDef",
-    "UpdateMapRequestRequestTypeDef",
+    "UpdateGeofenceCollectionResponseTypeDef",
+    "UpdateKeyResponseTypeDef",
+    "UpdateMapResponseTypeDef",
+    "UpdatePlaceIndexResponseTypeDef",
     "UpdateRouteCalculatorRequestRequestTypeDef",
+    "UpdateRouteCalculatorResponseTypeDef",
     "UpdateTrackerRequestRequestTypeDef",
+    "UpdateTrackerResponseTypeDef",
+    "ListKeysRequestListKeysPaginateTypeDef",
+    "ListKeysRequestRequestTypeDef",
+    "CreateKeyRequestRequestTypeDef",
+    "DescribeKeyResponseTypeDef",
+    "ListKeysResponseEntryTypeDef",
+    "UpdateKeyRequestRequestTypeDef",
     "BatchDeleteDevicePositionHistoryErrorTypeDef",
     "BatchDeleteGeofenceErrorTypeDef",
     "BatchEvaluateGeofencesErrorTypeDef",
     "BatchGetDevicePositionErrorTypeDef",
     "BatchPutGeofenceErrorTypeDef",
     "BatchUpdateDevicePositionErrorTypeDef",
-    "CreateGeofenceCollectionResponseTypeDef",
-    "CreateMapResponseTypeDef",
-    "CreatePlaceIndexResponseTypeDef",
-    "CreateRouteCalculatorResponseTypeDef",
-    "CreateTrackerResponseTypeDef",
-    "DescribeGeofenceCollectionResponseTypeDef",
-    "DescribeRouteCalculatorResponseTypeDef",
-    "DescribeTrackerResponseTypeDef",
-    "GetMapGlyphsResponseTypeDef",
-    "GetMapSpritesResponseTypeDef",
-    "GetMapStyleDescriptorResponseTypeDef",
-    "GetMapTileResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListTrackerConsumersResponseTypeDef",
-    "PutGeofenceResponseTypeDef",
-    "UpdateGeofenceCollectionResponseTypeDef",
-    "UpdateMapResponseTypeDef",
-    "UpdatePlaceIndexResponseTypeDef",
-    "UpdateRouteCalculatorResponseTypeDef",
-    "UpdateTrackerResponseTypeDef",
     "CalculateRouteTruckModeOptionsTypeDef",
     "GeofenceGeometryTypeDef",
     "CreateMapRequestRequestTypeDef",
     "DescribeMapResponseTypeDef",
     "CreatePlaceIndexRequestRequestTypeDef",
     "DescribePlaceIndexResponseTypeDef",
     "UpdatePlaceIndexRequestRequestTypeDef",
     "DevicePositionTypeDef",
     "DevicePositionUpdateTypeDef",
     "GetDevicePositionResponseTypeDef",
     "ListDevicePositionsResponseEntryTypeDef",
-    "GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    "ListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
-    "ListGeofencesRequestListGeofencesPaginateTypeDef",
-    "ListMapsRequestListMapsPaginateTypeDef",
-    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
-    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
-    "ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    "ListTrackersRequestListTrackersPaginateTypeDef",
     "LegTypeDef",
     "ListGeofenceCollectionsResponseTypeDef",
     "ListMapsResponseTypeDef",
     "ListPlaceIndexesResponseTypeDef",
     "ListRouteCalculatorsResponseTypeDef",
     "ListTrackersResponseTypeDef",
+    "UpdateMapRequestRequestTypeDef",
     "PlaceTypeDef",
     "RouteMatrixEntryTypeDef",
     "SearchPlaceIndexForSuggestionsResponseTypeDef",
+    "ListKeysResponseTypeDef",
     "BatchDeleteDevicePositionHistoryResponseTypeDef",
     "BatchDeleteGeofenceResponseTypeDef",
     "BatchEvaluateGeofencesResponseTypeDef",
     "BatchPutGeofenceResponseTypeDef",
     "BatchUpdateDevicePositionResponseTypeDef",
     "CalculateRouteMatrixRequestRequestTypeDef",
     "CalculateRouteRequestRequestTypeDef",
@@ -185,14 +199,42 @@
     "CalculateRouteMatrixResponseTypeDef",
     "BatchPutGeofenceRequestRequestTypeDef",
     "ListGeofencesResponseTypeDef",
     "SearchPlaceIndexForPositionResponseTypeDef",
     "SearchPlaceIndexForTextResponseTypeDef",
 )
 
+ApiKeyFilterTypeDef = TypedDict(
+    "ApiKeyFilterTypeDef",
+    {
+        "KeyStatus": StatusType,
+    },
+    total=False,
+)
+
+_RequiredApiKeyRestrictionsTypeDef = TypedDict(
+    "_RequiredApiKeyRestrictionsTypeDef",
+    {
+        "AllowActions": Sequence[str],
+        "AllowResources": Sequence[str],
+    },
+)
+_OptionalApiKeyRestrictionsTypeDef = TypedDict(
+    "_OptionalApiKeyRestrictionsTypeDef",
+    {
+        "AllowReferers": Sequence[str],
+    },
+    total=False,
+)
+
+class ApiKeyRestrictionsTypeDef(
+    _RequiredApiKeyRestrictionsTypeDef, _OptionalApiKeyRestrictionsTypeDef
+):
+    pass
+
 AssociateTrackerConsumerRequestRequestTypeDef = TypedDict(
     "AssociateTrackerConsumerRequestRequestTypeDef",
     {
         "ConsumerArn": str,
         "TrackerName": str,
     },
 )
@@ -210,25 +252,14 @@
     "BatchDeleteDevicePositionHistoryRequestRequestTypeDef",
     {
         "DeviceIds": Sequence[str],
         "TrackerName": str,
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
 BatchDeleteGeofenceRequestRequestTypeDef = TypedDict(
     "BatchDeleteGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceIds": Sequence[str],
     },
 )
@@ -322,37 +353,86 @@
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateGeofenceCollectionRequestRequestTypeDef(
     _RequiredCreateGeofenceCollectionRequestRequestTypeDef,
     _OptionalCreateGeofenceCollectionRequestRequestTypeDef,
 ):
     pass
 
+CreateGeofenceCollectionResponseTypeDef = TypedDict(
+    "CreateGeofenceCollectionResponseTypeDef",
+    {
+        "CollectionArn": str,
+        "CollectionName": str,
+        "CreateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateKeyResponseTypeDef = TypedDict(
+    "CreateKeyResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "Key": str,
+        "KeyArn": str,
+        "KeyName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-MapConfigurationTypeDef = TypedDict(
-    "MapConfigurationTypeDef",
+_RequiredMapConfigurationTypeDef = TypedDict(
+    "_RequiredMapConfigurationTypeDef",
     {
         "Style": str,
     },
 )
+_OptionalMapConfigurationTypeDef = TypedDict(
+    "_OptionalMapConfigurationTypeDef",
+    {
+        "PoliticalView": str,
+    },
+    total=False,
+)
+
+class MapConfigurationTypeDef(_RequiredMapConfigurationTypeDef, _OptionalMapConfigurationTypeDef):
+    pass
+
+CreateMapResponseTypeDef = TypedDict(
+    "CreateMapResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "MapArn": str,
+        "MapName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DataSourceConfigurationTypeDef = TypedDict(
     "DataSourceConfigurationTypeDef",
     {
         "IntendedUse": IntendedUseType,
     },
     total=False,
 )
 
+CreatePlaceIndexResponseTypeDef = TypedDict(
+    "CreatePlaceIndexResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "IndexArn": str,
+        "IndexName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRouteCalculatorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
         "DataSource": str,
     },
 )
@@ -362,21 +442,29 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateRouteCalculatorRequestRequestTypeDef(
     _RequiredCreateRouteCalculatorRequestRequestTypeDef,
     _OptionalCreateRouteCalculatorRequestRequestTypeDef,
 ):
     pass
 
+CreateRouteCalculatorResponseTypeDef = TypedDict(
+    "CreateRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "CreateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
@@ -389,28 +477,43 @@
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateTrackerRequestRequestTypeDef(
     _RequiredCreateTrackerRequestRequestTypeDef, _OptionalCreateTrackerRequestRequestTypeDef
 ):
     pass
 
+CreateTrackerResponseTypeDef = TypedDict(
+    "CreateTrackerResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "TrackerArn": str,
+        "TrackerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteGeofenceCollectionRequestRequestTypeDef = TypedDict(
     "DeleteGeofenceCollectionRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
 
+DeleteKeyRequestRequestTypeDef = TypedDict(
+    "DeleteKeyRequestRequestTypeDef",
+    {
+        "KeyName": str,
+    },
+)
+
 DeleteMapRequestRequestTypeDef = TypedDict(
     "DeleteMapRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
 
@@ -438,14 +541,37 @@
 DescribeGeofenceCollectionRequestRequestTypeDef = TypedDict(
     "DescribeGeofenceCollectionRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
 
+DescribeGeofenceCollectionResponseTypeDef = TypedDict(
+    "DescribeGeofenceCollectionResponseTypeDef",
+    {
+        "CollectionArn": str,
+        "CollectionName": str,
+        "CreateTime": datetime,
+        "Description": str,
+        "KmsKeyId": str,
+        "PricingPlan": PricingPlanType,
+        "PricingPlanDataSource": str,
+        "Tags": Dict[str, str],
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeKeyRequestRequestTypeDef = TypedDict(
+    "DescribeKeyRequestRequestTypeDef",
+    {
+        "KeyName": str,
+    },
+)
+
 DescribeMapRequestRequestTypeDef = TypedDict(
     "DescribeMapRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
 
@@ -459,21 +585,53 @@
 DescribeRouteCalculatorRequestRequestTypeDef = TypedDict(
     "DescribeRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
     },
 )
 
+DescribeRouteCalculatorResponseTypeDef = TypedDict(
+    "DescribeRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "CreateTime": datetime,
+        "DataSource": str,
+        "Description": str,
+        "PricingPlan": PricingPlanType,
+        "Tags": Dict[str, str],
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTrackerRequestRequestTypeDef = TypedDict(
     "DescribeTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 
+DescribeTrackerResponseTypeDef = TypedDict(
+    "DescribeTrackerResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "Description": str,
+        "KmsKeyId": str,
+        "PositionFiltering": PositionFilteringType,
+        "PricingPlan": PricingPlanType,
+        "PricingPlanDataSource": str,
+        "Tags": Dict[str, str],
+        "TrackerArn": str,
+        "TrackerName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PositionalAccuracyTypeDef = TypedDict(
     "PositionalAccuracyTypeDef",
     {
         "Horizontal": float,
     },
 )
 
@@ -481,24 +639,37 @@
     "DisassociateTrackerConsumerRequestRequestTypeDef",
     {
         "ConsumerArn": str,
         "TrackerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DeviceId": str,
+        "TrackerName": str,
+    },
+)
+_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
+    {
+        "EndTimeExclusive": Union[datetime, str],
+        "StartTimeInclusive": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef(
+    _RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
+    _OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetDevicePositionHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetDevicePositionHistoryRequestRequestTypeDef",
     {
         "DeviceId": str,
         "TrackerName": str,
     },
 )
@@ -509,22 +680,20 @@
         "MaxResults": int,
         "NextToken": str,
         "StartTimeInclusive": Union[datetime, str],
     },
     total=False,
 )
 
-
 class GetDevicePositionHistoryRequestRequestTypeDef(
     _RequiredGetDevicePositionHistoryRequestRequestTypeDef,
     _OptionalGetDevicePositionHistoryRequestRequestTypeDef,
 ):
     pass
 
-
 GetDevicePositionRequestRequestTypeDef = TypedDict(
     "GetDevicePositionRequestRequestTypeDef",
     {
         "DeviceId": str,
         "TrackerName": str,
     },
 )
@@ -533,47 +702,136 @@
     "GetGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceId": str,
     },
 )
 
-GetMapGlyphsRequestRequestTypeDef = TypedDict(
-    "GetMapGlyphsRequestRequestTypeDef",
+_RequiredGetMapGlyphsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapGlyphsRequestRequestTypeDef",
     {
         "FontStack": str,
         "FontUnicodeRange": str,
         "MapName": str,
     },
 )
+_OptionalGetMapGlyphsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapGlyphsRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapSpritesRequestRequestTypeDef = TypedDict(
-    "GetMapSpritesRequestRequestTypeDef",
+class GetMapGlyphsRequestRequestTypeDef(
+    _RequiredGetMapGlyphsRequestRequestTypeDef, _OptionalGetMapGlyphsRequestRequestTypeDef
+):
+    pass
+
+GetMapGlyphsResponseTypeDef = TypedDict(
+    "GetMapGlyphsResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapSpritesRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapSpritesRequestRequestTypeDef",
     {
         "FileName": str,
         "MapName": str,
     },
 )
+_OptionalGetMapSpritesRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapSpritesRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
-    "GetMapStyleDescriptorRequestRequestTypeDef",
+class GetMapSpritesRequestRequestTypeDef(
+    _RequiredGetMapSpritesRequestRequestTypeDef, _OptionalGetMapSpritesRequestRequestTypeDef
+):
+    pass
+
+GetMapSpritesResponseTypeDef = TypedDict(
+    "GetMapSpritesResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapStyleDescriptorRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
+_OptionalGetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapStyleDescriptorRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapTileRequestRequestTypeDef = TypedDict(
-    "GetMapTileRequestRequestTypeDef",
+class GetMapStyleDescriptorRequestRequestTypeDef(
+    _RequiredGetMapStyleDescriptorRequestRequestTypeDef,
+    _OptionalGetMapStyleDescriptorRequestRequestTypeDef,
+):
+    pass
+
+GetMapStyleDescriptorResponseTypeDef = TypedDict(
+    "GetMapStyleDescriptorResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapTileRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapTileRequestRequestTypeDef",
     {
         "MapName": str,
         "X": str,
         "Y": str,
         "Z": str,
     },
 )
+_OptionalGetMapTileRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapTileRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
+
+class GetMapTileRequestRequestTypeDef(
+    _RequiredGetMapTileRequestRequestTypeDef, _OptionalGetMapTileRequestRequestTypeDef
+):
+    pass
+
+GetMapTileResponseTypeDef = TypedDict(
+    "GetMapTileResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetPlaceRequestRequestTypeDef = TypedDict(
     "_RequiredGetPlaceRequestRequestTypeDef",
     {
         "IndexName": str,
         "PlaceId": str,
     },
@@ -582,21 +840,19 @@
     "_OptionalGetPlaceRequestRequestTypeDef",
     {
         "Language": str,
     },
     total=False,
 )
 
-
 class GetPlaceRequestRequestTypeDef(
     _RequiredGetPlaceRequestRequestTypeDef, _OptionalGetPlaceRequestRequestTypeDef
 ):
     pass
 
-
 LegGeometryTypeDef = TypedDict(
     "LegGeometryTypeDef",
     {
         "LineString": List[List[float]],
     },
     total=False,
 )
@@ -614,18 +870,36 @@
     "_OptionalStepTypeDef",
     {
         "GeometryOffset": int,
     },
     total=False,
 )
 
-
 class StepTypeDef(_RequiredStepTypeDef, _OptionalStepTypeDef):
     pass
 
+_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
+    "_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
+    {
+        "TrackerName": str,
+    },
+)
+_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
+    "_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDevicePositionsRequestListDevicePositionsPaginateTypeDef(
+    _RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
+    _OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
+):
+    pass
 
 _RequiredListDevicePositionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDevicePositionsRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
@@ -634,21 +908,27 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListDevicePositionsRequestRequestTypeDef(
     _RequiredListDevicePositionsRequestRequestTypeDef,
     _OptionalListDevicePositionsRequestRequestTypeDef,
 ):
     pass
 
+ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef = TypedDict(
+    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListGeofenceCollectionsRequestRequestTypeDef = TypedDict(
     "ListGeofenceCollectionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
@@ -669,21 +949,39 @@
     {
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
-
 class ListGeofenceCollectionsResponseEntryTypeDef(
     _RequiredListGeofenceCollectionsResponseEntryTypeDef,
     _OptionalListGeofenceCollectionsResponseEntryTypeDef,
 ):
     pass
 
+_RequiredListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
+    "_RequiredListGeofencesRequestListGeofencesPaginateTypeDef",
+    {
+        "CollectionName": str,
+    },
+)
+_OptionalListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
+    "_OptionalListGeofencesRequestListGeofencesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGeofencesRequestListGeofencesPaginateTypeDef(
+    _RequiredListGeofencesRequestListGeofencesPaginateTypeDef,
+    _OptionalListGeofencesRequestListGeofencesPaginateTypeDef,
+):
+    pass
 
 _RequiredListGeofencesRequestRequestTypeDef = TypedDict(
     "_RequiredListGeofencesRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
@@ -692,20 +990,26 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListGeofencesRequestRequestTypeDef(
     _RequiredListGeofencesRequestRequestTypeDef, _OptionalListGeofencesRequestRequestTypeDef
 ):
     pass
 
+ListMapsRequestListMapsPaginateTypeDef = TypedDict(
+    "ListMapsRequestListMapsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListMapsRequestRequestTypeDef = TypedDict(
     "ListMapsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
@@ -726,20 +1030,26 @@
     "_OptionalListMapsResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
-
 class ListMapsResponseEntryTypeDef(
     _RequiredListMapsResponseEntryTypeDef, _OptionalListMapsResponseEntryTypeDef
 ):
     pass
 
+ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef = TypedDict(
+    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListPlaceIndexesRequestRequestTypeDef = TypedDict(
     "ListPlaceIndexesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
@@ -760,20 +1070,26 @@
     "_OptionalListPlaceIndexesResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
-
 class ListPlaceIndexesResponseEntryTypeDef(
     _RequiredListPlaceIndexesResponseEntryTypeDef, _OptionalListPlaceIndexesResponseEntryTypeDef
 ):
     pass
 
+ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef = TypedDict(
+    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListRouteCalculatorsRequestRequestTypeDef = TypedDict(
     "ListRouteCalculatorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
@@ -794,29 +1110,55 @@
     "_OptionalListRouteCalculatorsResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
-
 class ListRouteCalculatorsResponseEntryTypeDef(
     _RequiredListRouteCalculatorsResponseEntryTypeDef,
     _OptionalListRouteCalculatorsResponseEntryTypeDef,
 ):
     pass
 
-
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
+_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
+    "_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
+    {
+        "TrackerName": str,
+    },
+)
+_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
+    "_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef(
+    _RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
+    _OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
+):
+    pass
+
 _RequiredListTrackerConsumersRequestRequestTypeDef = TypedDict(
     "_RequiredListTrackerConsumersRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 _OptionalListTrackerConsumersRequestRequestTypeDef = TypedDict(
@@ -824,21 +1166,36 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListTrackerConsumersRequestRequestTypeDef(
     _RequiredListTrackerConsumersRequestRequestTypeDef,
     _OptionalListTrackerConsumersRequestRequestTypeDef,
 ):
     pass
 
+ListTrackerConsumersResponseTypeDef = TypedDict(
+    "ListTrackerConsumersResponseTypeDef",
+    {
+        "ConsumerArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTrackersRequestListTrackersPaginateTypeDef = TypedDict(
+    "ListTrackersRequestListTrackersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListTrackersRequestRequestTypeDef = TypedDict(
     "ListTrackersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
@@ -859,20 +1216,36 @@
     {
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
-
 class ListTrackersResponseEntryTypeDef(
     _RequiredListTrackersResponseEntryTypeDef, _OptionalListTrackersResponseEntryTypeDef
 ):
     pass
 
+MapConfigurationUpdateTypeDef = TypedDict(
+    "MapConfigurationUpdateTypeDef",
+    {
+        "PoliticalView": str,
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
+    },
+    total=False,
+)
 
 PlaceGeometryTypeDef = TypedDict(
     "PlaceGeometryTypeDef",
     {
         "Point": List[float],
     },
     total=False,
@@ -888,18 +1261,37 @@
     "_OptionalTimeZoneTypeDef",
     {
         "Offset": int,
     },
     total=False,
 )
 
-
 class TimeZoneTypeDef(_RequiredTimeZoneTypeDef, _OptionalTimeZoneTypeDef):
     pass
 
+PutGeofenceResponseTypeDef = TypedDict(
+    "PutGeofenceResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "GeofenceId": str,
+        "UpdateTime": datetime,
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
 
 _RequiredRouteMatrixEntryErrorTypeDef = TypedDict(
     "_RequiredRouteMatrixEntryErrorTypeDef",
     {
         "Code": RouteMatrixErrorCodeType,
     },
 )
@@ -907,42 +1299,40 @@
     "_OptionalRouteMatrixEntryErrorTypeDef",
     {
         "Message": str,
     },
     total=False,
 )
 
-
 class RouteMatrixEntryErrorTypeDef(
     _RequiredRouteMatrixEntryErrorTypeDef, _OptionalRouteMatrixEntryErrorTypeDef
 ):
     pass
 
-
 _RequiredSearchForSuggestionsResultTypeDef = TypedDict(
     "_RequiredSearchForSuggestionsResultTypeDef",
     {
         "Text": str,
     },
 )
 _OptionalSearchForSuggestionsResultTypeDef = TypedDict(
     "_OptionalSearchForSuggestionsResultTypeDef",
     {
+        "Categories": List[str],
         "PlaceId": str,
+        "SupplementalCategories": List[str],
     },
     total=False,
 )
 
-
 class SearchForSuggestionsResultTypeDef(
     _RequiredSearchForSuggestionsResultTypeDef, _OptionalSearchForSuggestionsResultTypeDef
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForPositionRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForPositionRequestRequestTypeDef",
     {
         "IndexName": str,
         "Position": Sequence[float],
     },
 )
@@ -951,22 +1341,20 @@
     {
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForPositionRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForPositionRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForPositionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForPositionSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForPositionSummaryTypeDef",
     {
         "DataSource": str,
         "Position": List[float],
     },
 )
@@ -975,130 +1363,124 @@
     {
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForPositionSummaryTypeDef(
     _RequiredSearchPlaceIndexForPositionSummaryTypeDef,
     _OptionalSearchPlaceIndexForPositionSummaryTypeDef,
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     {
         "IndexName": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     {
         "BiasPosition": Sequence[float],
         "FilterBBox": Sequence[float],
+        "FilterCategories": Sequence[str],
         "FilterCountries": Sequence[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForSuggestionsRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef",
     {
         "DataSource": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef",
     {
         "BiasPosition": List[float],
         "FilterBBox": List[float],
+        "FilterCategories": List[str],
         "FilterCountries": List[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForSuggestionsSummaryTypeDef(
     _RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef,
     _OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef,
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForTextRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForTextRequestRequestTypeDef",
     {
         "IndexName": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForTextRequestRequestTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForTextRequestRequestTypeDef",
     {
         "BiasPosition": Sequence[float],
         "FilterBBox": Sequence[float],
+        "FilterCategories": Sequence[str],
         "FilterCountries": Sequence[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForTextRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForTextRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForTextRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredSearchPlaceIndexForTextSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForTextSummaryTypeDef",
     {
         "DataSource": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForTextSummaryTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForTextSummaryTypeDef",
     {
         "BiasPosition": List[float],
         "FilterBBox": List[float],
+        "FilterCategories": List[str],
         "FilterCountries": List[str],
         "Language": str,
         "MaxResults": int,
         "ResultBBox": List[float],
     },
     total=False,
 )
 
-
 class SearchPlaceIndexForTextSummaryTypeDef(
     _RequiredSearchPlaceIndexForTextSummaryTypeDef, _OptionalSearchPlaceIndexForTextSummaryTypeDef
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -1123,43 +1505,59 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
-
 class UpdateGeofenceCollectionRequestRequestTypeDef(
     _RequiredUpdateGeofenceCollectionRequestRequestTypeDef,
     _OptionalUpdateGeofenceCollectionRequestRequestTypeDef,
 ):
     pass
 
-
-_RequiredUpdateMapRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateMapRequestRequestTypeDef",
+UpdateGeofenceCollectionResponseTypeDef = TypedDict(
+    "UpdateGeofenceCollectionResponseTypeDef",
     {
-        "MapName": str,
+        "CollectionArn": str,
+        "CollectionName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalUpdateMapRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateMapRequestRequestTypeDef",
+
+UpdateKeyResponseTypeDef = TypedDict(
+    "UpdateKeyResponseTypeDef",
     {
-        "Description": str,
-        "PricingPlan": PricingPlanType,
+        "KeyArn": str,
+        "KeyName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
+UpdateMapResponseTypeDef = TypedDict(
+    "UpdateMapResponseTypeDef",
+    {
+        "MapArn": str,
+        "MapName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-class UpdateMapRequestRequestTypeDef(
-    _RequiredUpdateMapRequestRequestTypeDef, _OptionalUpdateMapRequestRequestTypeDef
-):
-    pass
-
+UpdatePlaceIndexResponseTypeDef = TypedDict(
+    "UpdatePlaceIndexResponseTypeDef",
+    {
+        "IndexArn": str,
+        "IndexName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateRouteCalculatorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
     },
 )
@@ -1168,21 +1566,29 @@
     {
         "Description": str,
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
-
 class UpdateRouteCalculatorRequestRequestTypeDef(
     _RequiredUpdateRouteCalculatorRequestRequestTypeDef,
     _OptionalUpdateRouteCalculatorRequestRequestTypeDef,
 ):
     pass
 
+UpdateRouteCalculatorResponseTypeDef = TypedDict(
+    "UpdateRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
@@ -1193,279 +1599,180 @@
         "PositionFiltering": PositionFilteringType,
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
-
 class UpdateTrackerRequestRequestTypeDef(
     _RequiredUpdateTrackerRequestRequestTypeDef, _OptionalUpdateTrackerRequestRequestTypeDef
 ):
     pass
 
-
-BatchDeleteDevicePositionHistoryErrorTypeDef = TypedDict(
-    "BatchDeleteDevicePositionHistoryErrorTypeDef",
-    {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-    },
-)
-
-BatchDeleteGeofenceErrorTypeDef = TypedDict(
-    "BatchDeleteGeofenceErrorTypeDef",
-    {
-        "Error": BatchItemErrorTypeDef,
-        "GeofenceId": str,
-    },
-)
-
-BatchEvaluateGeofencesErrorTypeDef = TypedDict(
-    "BatchEvaluateGeofencesErrorTypeDef",
-    {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-        "SampleTime": datetime,
-    },
-)
-
-BatchGetDevicePositionErrorTypeDef = TypedDict(
-    "BatchGetDevicePositionErrorTypeDef",
-    {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-    },
-)
-
-BatchPutGeofenceErrorTypeDef = TypedDict(
-    "BatchPutGeofenceErrorTypeDef",
-    {
-        "Error": BatchItemErrorTypeDef,
-        "GeofenceId": str,
-    },
-)
-
-BatchUpdateDevicePositionErrorTypeDef = TypedDict(
-    "BatchUpdateDevicePositionErrorTypeDef",
+UpdateTrackerResponseTypeDef = TypedDict(
+    "UpdateTrackerResponseTypeDef",
     {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-        "SampleTime": datetime,
+        "TrackerArn": str,
+        "TrackerName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateGeofenceCollectionResponseTypeDef = TypedDict(
-    "CreateGeofenceCollectionResponseTypeDef",
+ListKeysRequestListKeysPaginateTypeDef = TypedDict(
+    "ListKeysRequestListKeysPaginateTypeDef",
     {
-        "CollectionArn": str,
-        "CollectionName": str,
-        "CreateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filter": ApiKeyFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-CreateMapResponseTypeDef = TypedDict(
-    "CreateMapResponseTypeDef",
+ListKeysRequestRequestTypeDef = TypedDict(
+    "ListKeysRequestRequestTypeDef",
     {
-        "CreateTime": datetime,
-        "MapArn": str,
-        "MapName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filter": ApiKeyFilterTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
+    total=False,
 )
 
-CreatePlaceIndexResponseTypeDef = TypedDict(
-    "CreatePlaceIndexResponseTypeDef",
+_RequiredCreateKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateKeyRequestRequestTypeDef",
     {
-        "CreateTime": datetime,
-        "IndexArn": str,
-        "IndexName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
     },
 )
-
-CreateRouteCalculatorResponseTypeDef = TypedDict(
-    "CreateRouteCalculatorResponseTypeDef",
+_OptionalCreateKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateKeyRequestRequestTypeDef",
     {
-        "CalculatorArn": str,
-        "CalculatorName": str,
-        "CreateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Description": str,
+        "ExpireTime": Union[datetime, str],
+        "NoExpiry": bool,
+        "Tags": Mapping[str, str],
     },
+    total=False,
 )
 
-CreateTrackerResponseTypeDef = TypedDict(
-    "CreateTrackerResponseTypeDef",
-    {
-        "CreateTime": datetime,
-        "TrackerArn": str,
-        "TrackerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class CreateKeyRequestRequestTypeDef(
+    _RequiredCreateKeyRequestRequestTypeDef, _OptionalCreateKeyRequestRequestTypeDef
+):
+    pass
 
-DescribeGeofenceCollectionResponseTypeDef = TypedDict(
-    "DescribeGeofenceCollectionResponseTypeDef",
+DescribeKeyResponseTypeDef = TypedDict(
+    "DescribeKeyResponseTypeDef",
     {
-        "CollectionArn": str,
-        "CollectionName": str,
         "CreateTime": datetime,
         "Description": str,
-        "KmsKeyId": str,
-        "PricingPlan": PricingPlanType,
-        "PricingPlanDataSource": str,
+        "ExpireTime": datetime,
+        "Key": str,
+        "KeyArn": str,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeRouteCalculatorResponseTypeDef = TypedDict(
-    "DescribeRouteCalculatorResponseTypeDef",
+_RequiredListKeysResponseEntryTypeDef = TypedDict(
+    "_RequiredListKeysResponseEntryTypeDef",
     {
-        "CalculatorArn": str,
-        "CalculatorName": str,
         "CreateTime": datetime,
-        "DataSource": str,
-        "Description": str,
-        "PricingPlan": PricingPlanType,
-        "Tags": Dict[str, str],
+        "ExpireTime": datetime,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-DescribeTrackerResponseTypeDef = TypedDict(
-    "DescribeTrackerResponseTypeDef",
+_OptionalListKeysResponseEntryTypeDef = TypedDict(
+    "_OptionalListKeysResponseEntryTypeDef",
     {
-        "CreateTime": datetime,
         "Description": str,
-        "KmsKeyId": str,
-        "PositionFiltering": PositionFilteringType,
-        "PricingPlan": PricingPlanType,
-        "PricingPlanDataSource": str,
-        "Tags": Dict[str, str],
-        "TrackerArn": str,
-        "TrackerName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMapGlyphsResponseTypeDef = TypedDict(
-    "GetMapGlyphsResponseTypeDef",
-    {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-GetMapSpritesResponseTypeDef = TypedDict(
-    "GetMapSpritesResponseTypeDef",
-    {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListKeysResponseEntryTypeDef(
+    _RequiredListKeysResponseEntryTypeDef, _OptionalListKeysResponseEntryTypeDef
+):
+    pass
 
-GetMapStyleDescriptorResponseTypeDef = TypedDict(
-    "GetMapStyleDescriptorResponseTypeDef",
+_RequiredUpdateKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateKeyRequestRequestTypeDef",
     {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "KeyName": str,
     },
 )
-
-GetMapTileResponseTypeDef = TypedDict(
-    "GetMapTileResponseTypeDef",
+_OptionalUpdateKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateKeyRequestRequestTypeDef",
     {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Description": str,
+        "ExpireTime": Union[datetime, str],
+        "ForceUpdate": bool,
+        "NoExpiry": bool,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
     },
+    total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateKeyRequestRequestTypeDef(
+    _RequiredUpdateKeyRequestRequestTypeDef, _OptionalUpdateKeyRequestRequestTypeDef
+):
+    pass
 
-ListTrackerConsumersResponseTypeDef = TypedDict(
-    "ListTrackerConsumersResponseTypeDef",
+BatchDeleteDevicePositionHistoryErrorTypeDef = TypedDict(
+    "BatchDeleteDevicePositionHistoryErrorTypeDef",
     {
-        "ConsumerArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
     },
 )
 
-PutGeofenceResponseTypeDef = TypedDict(
-    "PutGeofenceResponseTypeDef",
+BatchDeleteGeofenceErrorTypeDef = TypedDict(
+    "BatchDeleteGeofenceErrorTypeDef",
     {
-        "CreateTime": datetime,
+        "Error": BatchItemErrorTypeDef,
         "GeofenceId": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateGeofenceCollectionResponseTypeDef = TypedDict(
-    "UpdateGeofenceCollectionResponseTypeDef",
-    {
-        "CollectionArn": str,
-        "CollectionName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-UpdateMapResponseTypeDef = TypedDict(
-    "UpdateMapResponseTypeDef",
+BatchEvaluateGeofencesErrorTypeDef = TypedDict(
+    "BatchEvaluateGeofencesErrorTypeDef",
     {
-        "MapArn": str,
-        "MapName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
+        "SampleTime": datetime,
     },
 )
 
-UpdatePlaceIndexResponseTypeDef = TypedDict(
-    "UpdatePlaceIndexResponseTypeDef",
+BatchGetDevicePositionErrorTypeDef = TypedDict(
+    "BatchGetDevicePositionErrorTypeDef",
     {
-        "IndexArn": str,
-        "IndexName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
     },
 )
 
-UpdateRouteCalculatorResponseTypeDef = TypedDict(
-    "UpdateRouteCalculatorResponseTypeDef",
+BatchPutGeofenceErrorTypeDef = TypedDict(
+    "BatchPutGeofenceErrorTypeDef",
     {
-        "CalculatorArn": str,
-        "CalculatorName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Error": BatchItemErrorTypeDef,
+        "GeofenceId": str,
     },
 )
 
-UpdateTrackerResponseTypeDef = TypedDict(
-    "UpdateTrackerResponseTypeDef",
+BatchUpdateDevicePositionErrorTypeDef = TypedDict(
+    "BatchUpdateDevicePositionErrorTypeDef",
     {
-        "TrackerArn": str,
-        "TrackerName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
+        "SampleTime": datetime,
     },
 )
 
 CalculateRouteTruckModeOptionsTypeDef = TypedDict(
     "CalculateRouteTruckModeOptionsTypeDef",
     {
         "AvoidFerries": bool,
@@ -1498,34 +1805,32 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateMapRequestRequestTypeDef(
     _RequiredCreateMapRequestRequestTypeDef, _OptionalCreateMapRequestRequestTypeDef
 ):
     pass
 
-
 DescribeMapResponseTypeDef = TypedDict(
     "DescribeMapResponseTypeDef",
     {
         "Configuration": MapConfigurationTypeDef,
         "CreateTime": datetime,
         "DataSource": str,
         "Description": str,
         "MapArn": str,
         "MapName": str,
         "PricingPlan": PricingPlanType,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePlaceIndexRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePlaceIndexRequestRequestTypeDef",
     {
         "DataSource": str,
@@ -1539,34 +1844,32 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreatePlaceIndexRequestRequestTypeDef(
     _RequiredCreatePlaceIndexRequestRequestTypeDef, _OptionalCreatePlaceIndexRequestRequestTypeDef
 ):
     pass
 
-
 DescribePlaceIndexResponseTypeDef = TypedDict(
     "DescribePlaceIndexResponseTypeDef",
     {
         "CreateTime": datetime,
         "DataSource": str,
         "DataSourceConfiguration": DataSourceConfigurationTypeDef,
         "Description": str,
         "IndexArn": str,
         "IndexName": str,
         "PricingPlan": PricingPlanType,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePlaceIndexRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePlaceIndexRequestRequestTypeDef",
     {
         "IndexName": str,
@@ -1578,21 +1881,19 @@
         "DataSourceConfiguration": DataSourceConfigurationTypeDef,
         "Description": str,
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
-
 class UpdatePlaceIndexRequestRequestTypeDef(
     _RequiredUpdatePlaceIndexRequestRequestTypeDef, _OptionalUpdatePlaceIndexRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredDevicePositionTypeDef = TypedDict(
     "_RequiredDevicePositionTypeDef",
     {
         "Position": List[float],
         "ReceivedTime": datetime,
         "SampleTime": datetime,
     },
@@ -1603,19 +1904,17 @@
         "Accuracy": PositionalAccuracyTypeDef,
         "DeviceId": str,
         "PositionProperties": Dict[str, str],
     },
     total=False,
 )
 
-
 class DevicePositionTypeDef(_RequiredDevicePositionTypeDef, _OptionalDevicePositionTypeDef):
     pass
 
-
 _RequiredDevicePositionUpdateTypeDef = TypedDict(
     "_RequiredDevicePositionUpdateTypeDef",
     {
         "DeviceId": str,
         "Position": Sequence[float],
         "SampleTime": Union[datetime, str],
     },
@@ -1625,31 +1924,29 @@
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "PositionProperties": Mapping[str, str],
     },
     total=False,
 )
 
-
 class DevicePositionUpdateTypeDef(
     _RequiredDevicePositionUpdateTypeDef, _OptionalDevicePositionUpdateTypeDef
 ):
     pass
 
-
 GetDevicePositionResponseTypeDef = TypedDict(
     "GetDevicePositionResponseTypeDef",
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "DeviceId": str,
         "Position": List[float],
         "PositionProperties": Dict[str, str],
         "ReceivedTime": datetime,
         "SampleTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListDevicePositionsResponseEntryTypeDef = TypedDict(
     "_RequiredListDevicePositionsResponseEntryTypeDef",
     {
         "DeviceId": str,
@@ -1662,153 +1959,20 @@
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "PositionProperties": Dict[str, str],
     },
     total=False,
 )
 
-
 class ListDevicePositionsResponseEntryTypeDef(
     _RequiredListDevicePositionsResponseEntryTypeDef,
     _OptionalListDevicePositionsResponseEntryTypeDef,
 ):
     pass
 
-
-_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "TrackerName": str,
-    },
-)
-_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    {
-        "EndTimeExclusive": Union[datetime, str],
-        "StartTimeInclusive": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef(
-    _RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-    _OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
-    "_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    {
-        "TrackerName": str,
-    },
-)
-_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
-    "_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDevicePositionsRequestListDevicePositionsPaginateTypeDef(
-    _RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-    _OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-):
-    pass
-
-
-ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef = TypedDict(
-    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
-    "_RequiredListGeofencesRequestListGeofencesPaginateTypeDef",
-    {
-        "CollectionName": str,
-    },
-)
-_OptionalListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
-    "_OptionalListGeofencesRequestListGeofencesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGeofencesRequestListGeofencesPaginateTypeDef(
-    _RequiredListGeofencesRequestListGeofencesPaginateTypeDef,
-    _OptionalListGeofencesRequestListGeofencesPaginateTypeDef,
-):
-    pass
-
-
-ListMapsRequestListMapsPaginateTypeDef = TypedDict(
-    "ListMapsRequestListMapsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef = TypedDict(
-    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef = TypedDict(
-    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
-    "_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    {
-        "TrackerName": str,
-    },
-)
-_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
-    "_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef(
-    _RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-    _OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-):
-    pass
-
-
-ListTrackersRequestListTrackersPaginateTypeDef = TypedDict(
-    "ListTrackersRequestListTrackersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredLegTypeDef = TypedDict(
     "_RequiredLegTypeDef",
     {
         "Distance": float,
         "DurationSeconds": float,
         "EndPosition": List[float],
         "StartPosition": List[float],
@@ -1819,95 +1983,114 @@
     "_OptionalLegTypeDef",
     {
         "Geometry": LegGeometryTypeDef,
     },
     total=False,
 )
 
-
 class LegTypeDef(_RequiredLegTypeDef, _OptionalLegTypeDef):
     pass
 
-
 ListGeofenceCollectionsResponseTypeDef = TypedDict(
     "ListGeofenceCollectionsResponseTypeDef",
     {
         "Entries": List[ListGeofenceCollectionsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMapsResponseTypeDef = TypedDict(
     "ListMapsResponseTypeDef",
     {
         "Entries": List[ListMapsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlaceIndexesResponseTypeDef = TypedDict(
     "ListPlaceIndexesResponseTypeDef",
     {
         "Entries": List[ListPlaceIndexesResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRouteCalculatorsResponseTypeDef = TypedDict(
     "ListRouteCalculatorsResponseTypeDef",
     {
         "Entries": List[ListRouteCalculatorsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrackersResponseTypeDef = TypedDict(
     "ListTrackersResponseTypeDef",
     {
         "Entries": List[ListTrackersResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredUpdateMapRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateMapRequestRequestTypeDef",
+    {
+        "MapName": str,
+    },
+)
+_OptionalUpdateMapRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateMapRequestRequestTypeDef",
+    {
+        "ConfigurationUpdate": MapConfigurationUpdateTypeDef,
+        "Description": str,
+        "PricingPlan": PricingPlanType,
+    },
+    total=False,
+)
+
+class UpdateMapRequestRequestTypeDef(
+    _RequiredUpdateMapRequestRequestTypeDef, _OptionalUpdateMapRequestRequestTypeDef
+):
+    pass
+
 _RequiredPlaceTypeDef = TypedDict(
     "_RequiredPlaceTypeDef",
     {
         "Geometry": PlaceGeometryTypeDef,
     },
 )
 _OptionalPlaceTypeDef = TypedDict(
     "_OptionalPlaceTypeDef",
     {
         "AddressNumber": str,
+        "Categories": List[str],
         "Country": str,
         "Interpolated": bool,
         "Label": str,
         "Municipality": str,
         "Neighborhood": str,
         "PostalCode": str,
         "Region": str,
         "Street": str,
         "SubRegion": str,
+        "SupplementalCategories": List[str],
         "TimeZone": TimeZoneTypeDef,
         "UnitNumber": str,
         "UnitType": str,
     },
     total=False,
 )
 
-
 class PlaceTypeDef(_RequiredPlaceTypeDef, _OptionalPlaceTypeDef):
     pass
 
-
 RouteMatrixEntryTypeDef = TypedDict(
     "RouteMatrixEntryTypeDef",
     {
         "Distance": float,
         "DurationSeconds": float,
         "Error": RouteMatrixEntryErrorTypeDef,
     },
@@ -1915,56 +2098,65 @@
 )
 
 SearchPlaceIndexForSuggestionsResponseTypeDef = TypedDict(
     "SearchPlaceIndexForSuggestionsResponseTypeDef",
     {
         "Results": List[SearchForSuggestionsResultTypeDef],
         "Summary": SearchPlaceIndexForSuggestionsSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListKeysResponseTypeDef = TypedDict(
+    "ListKeysResponseTypeDef",
+    {
+        "Entries": List[ListKeysResponseEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDevicePositionHistoryResponseTypeDef = TypedDict(
     "BatchDeleteDevicePositionHistoryResponseTypeDef",
     {
         "Errors": List[BatchDeleteDevicePositionHistoryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteGeofenceResponseTypeDef = TypedDict(
     "BatchDeleteGeofenceResponseTypeDef",
     {
         "Errors": List[BatchDeleteGeofenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEvaluateGeofencesResponseTypeDef = TypedDict(
     "BatchEvaluateGeofencesResponseTypeDef",
     {
         "Errors": List[BatchEvaluateGeofencesErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutGeofenceResponseTypeDef = TypedDict(
     "BatchPutGeofenceResponseTypeDef",
     {
         "Errors": List[BatchPutGeofenceErrorTypeDef],
         "Successes": List[BatchPutGeofenceSuccessTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateDevicePositionResponseTypeDef = TypedDict(
     "BatchUpdateDevicePositionResponseTypeDef",
     {
         "Errors": List[BatchUpdateDevicePositionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCalculateRouteMatrixRequestRequestTypeDef = TypedDict(
     "_RequiredCalculateRouteMatrixRequestRequestTypeDef",
     {
         "CalculatorName": str,
@@ -1981,22 +2173,20 @@
         "DistanceUnit": DistanceUnitType,
         "TravelMode": TravelModeType,
         "TruckModeOptions": CalculateRouteTruckModeOptionsTypeDef,
     },
     total=False,
 )
 
-
 class CalculateRouteMatrixRequestRequestTypeDef(
     _RequiredCalculateRouteMatrixRequestRequestTypeDef,
     _OptionalCalculateRouteMatrixRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCalculateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCalculateRouteRequestRequestTypeDef",
     {
         "CalculatorName": str,
         "DeparturePosition": Sequence[float],
         "DestinationPosition": Sequence[float],
     },
@@ -2012,76 +2202,111 @@
         "TravelMode": TravelModeType,
         "TruckModeOptions": CalculateRouteTruckModeOptionsTypeDef,
         "WaypointPositions": Sequence[Sequence[float]],
     },
     total=False,
 )
 
-
 class CalculateRouteRequestRequestTypeDef(
     _RequiredCalculateRouteRequestRequestTypeDef, _OptionalCalculateRouteRequestRequestTypeDef
 ):
     pass
 
-
-BatchPutGeofenceRequestEntryTypeDef = TypedDict(
-    "BatchPutGeofenceRequestEntryTypeDef",
+_RequiredBatchPutGeofenceRequestEntryTypeDef = TypedDict(
+    "_RequiredBatchPutGeofenceRequestEntryTypeDef",
     {
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
     },
 )
+_OptionalBatchPutGeofenceRequestEntryTypeDef = TypedDict(
+    "_OptionalBatchPutGeofenceRequestEntryTypeDef",
+    {
+        "GeofenceProperties": Mapping[str, str],
+    },
+    total=False,
+)
+
+class BatchPutGeofenceRequestEntryTypeDef(
+    _RequiredBatchPutGeofenceRequestEntryTypeDef, _OptionalBatchPutGeofenceRequestEntryTypeDef
+):
+    pass
 
 GetGeofenceResponseTypeDef = TypedDict(
     "GetGeofenceResponseTypeDef",
     {
         "CreateTime": datetime,
         "GeofenceId": str,
+        "GeofenceProperties": Dict[str, str],
         "Geometry": GeofenceGeometryTypeDef,
         "Status": str,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListGeofenceResponseEntryTypeDef = TypedDict(
-    "ListGeofenceResponseEntryTypeDef",
+_RequiredListGeofenceResponseEntryTypeDef = TypedDict(
+    "_RequiredListGeofenceResponseEntryTypeDef",
     {
         "CreateTime": datetime,
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
         "Status": str,
         "UpdateTime": datetime,
     },
 )
+_OptionalListGeofenceResponseEntryTypeDef = TypedDict(
+    "_OptionalListGeofenceResponseEntryTypeDef",
+    {
+        "GeofenceProperties": Dict[str, str],
+    },
+    total=False,
+)
 
-PutGeofenceRequestRequestTypeDef = TypedDict(
-    "PutGeofenceRequestRequestTypeDef",
+class ListGeofenceResponseEntryTypeDef(
+    _RequiredListGeofenceResponseEntryTypeDef, _OptionalListGeofenceResponseEntryTypeDef
+):
+    pass
+
+_RequiredPutGeofenceRequestRequestTypeDef = TypedDict(
+    "_RequiredPutGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
     },
 )
+_OptionalPutGeofenceRequestRequestTypeDef = TypedDict(
+    "_OptionalPutGeofenceRequestRequestTypeDef",
+    {
+        "GeofenceProperties": Mapping[str, str],
+    },
+    total=False,
+)
+
+class PutGeofenceRequestRequestTypeDef(
+    _RequiredPutGeofenceRequestRequestTypeDef, _OptionalPutGeofenceRequestRequestTypeDef
+):
+    pass
 
 BatchGetDevicePositionResponseTypeDef = TypedDict(
     "BatchGetDevicePositionResponseTypeDef",
     {
         "DevicePositions": List[DevicePositionTypeDef],
         "Errors": List[BatchGetDevicePositionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicePositionHistoryResponseTypeDef = TypedDict(
     "GetDevicePositionHistoryResponseTypeDef",
     {
         "DevicePositions": List[DevicePositionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEvaluateGeofencesRequestRequestTypeDef = TypedDict(
     "BatchEvaluateGeofencesRequestRequestTypeDef",
     {
         "CollectionName": str,
@@ -2098,32 +2323,32 @@
 )
 
 ListDevicePositionsResponseTypeDef = TypedDict(
     "ListDevicePositionsResponseTypeDef",
     {
         "Entries": List[ListDevicePositionsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CalculateRouteResponseTypeDef = TypedDict(
     "CalculateRouteResponseTypeDef",
     {
         "Legs": List[LegTypeDef],
         "Summary": CalculateRouteSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPlaceResponseTypeDef = TypedDict(
     "GetPlaceResponseTypeDef",
     {
         "Place": PlaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchForPositionResultTypeDef = TypedDict(
     "_RequiredSearchForPositionResultTypeDef",
     {
         "Distance": float,
@@ -2134,21 +2359,19 @@
     "_OptionalSearchForPositionResultTypeDef",
     {
         "PlaceId": str,
     },
     total=False,
 )
 
-
 class SearchForPositionResultTypeDef(
     _RequiredSearchForPositionResultTypeDef, _OptionalSearchForPositionResultTypeDef
 ):
     pass
 
-
 _RequiredSearchForTextResultTypeDef = TypedDict(
     "_RequiredSearchForTextResultTypeDef",
     {
         "Place": PlaceTypeDef,
     },
 )
 _OptionalSearchForTextResultTypeDef = TypedDict(
@@ -2157,29 +2380,27 @@
         "Distance": float,
         "PlaceId": str,
         "Relevance": float,
     },
     total=False,
 )
 
-
 class SearchForTextResultTypeDef(
     _RequiredSearchForTextResultTypeDef, _OptionalSearchForTextResultTypeDef
 ):
     pass
 
-
 CalculateRouteMatrixResponseTypeDef = TypedDict(
     "CalculateRouteMatrixResponseTypeDef",
     {
         "RouteMatrix": List[List[RouteMatrixEntryTypeDef]],
         "SnappedDeparturePositions": List[List[float]],
         "SnappedDestinationPositions": List[List[float]],
         "Summary": CalculateRouteMatrixSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutGeofenceRequestRequestTypeDef = TypedDict(
     "BatchPutGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
@@ -2188,28 +2409,28 @@
 )
 
 ListGeofencesResponseTypeDef = TypedDict(
     "ListGeofencesResponseTypeDef",
     {
         "Entries": List[ListGeofenceResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchPlaceIndexForPositionResponseTypeDef = TypedDict(
     "SearchPlaceIndexForPositionResponseTypeDef",
     {
         "Results": List[SearchForPositionResultTypeDef],
         "Summary": SearchPlaceIndexForPositionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchPlaceIndexForTextResponseTypeDef = TypedDict(
     "SearchPlaceIndexForTextResponseTypeDef",
     {
         "Results": List[SearchForTextResultTypeDef],
         "Summary": SearchPlaceIndexForTextSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location/type_defs.pyi` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for location service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_location.type_defs import AssociateTrackerConsumerRequestRequestTypeDef
+    from types_aiobotocore_location.type_defs import ApiKeyFilterTypeDef
 
-    data: AssociateTrackerConsumerRequestRequestTypeDef = {...}
+    data: ApiKeyFilterTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
@@ -21,150 +21,166 @@
     BatchItemErrorCodeType,
     DimensionUnitType,
     DistanceUnitType,
     IntendedUseType,
     PositionFilteringType,
     PricingPlanType,
     RouteMatrixErrorCodeType,
+    StatusType,
     TravelModeType,
     VehicleWeightUnitType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
+    "ApiKeyFilterTypeDef",
+    "ApiKeyRestrictionsTypeDef",
     "AssociateTrackerConsumerRequestRequestTypeDef",
     "BatchItemErrorTypeDef",
     "BatchDeleteDevicePositionHistoryRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteGeofenceRequestRequestTypeDef",
     "BatchGetDevicePositionRequestRequestTypeDef",
     "BatchPutGeofenceSuccessTypeDef",
     "CalculateRouteCarModeOptionsTypeDef",
     "CalculateRouteMatrixSummaryTypeDef",
     "CalculateRouteSummaryTypeDef",
     "TruckDimensionsTypeDef",
     "TruckWeightTypeDef",
     "CircleTypeDef",
     "CreateGeofenceCollectionRequestRequestTypeDef",
+    "CreateGeofenceCollectionResponseTypeDef",
+    "CreateKeyResponseTypeDef",
     "MapConfigurationTypeDef",
+    "CreateMapResponseTypeDef",
     "DataSourceConfigurationTypeDef",
+    "CreatePlaceIndexResponseTypeDef",
     "CreateRouteCalculatorRequestRequestTypeDef",
+    "CreateRouteCalculatorResponseTypeDef",
     "CreateTrackerRequestRequestTypeDef",
+    "CreateTrackerResponseTypeDef",
     "DeleteGeofenceCollectionRequestRequestTypeDef",
+    "DeleteKeyRequestRequestTypeDef",
     "DeleteMapRequestRequestTypeDef",
     "DeletePlaceIndexRequestRequestTypeDef",
     "DeleteRouteCalculatorRequestRequestTypeDef",
     "DeleteTrackerRequestRequestTypeDef",
     "DescribeGeofenceCollectionRequestRequestTypeDef",
+    "DescribeGeofenceCollectionResponseTypeDef",
+    "DescribeKeyRequestRequestTypeDef",
     "DescribeMapRequestRequestTypeDef",
     "DescribePlaceIndexRequestRequestTypeDef",
     "DescribeRouteCalculatorRequestRequestTypeDef",
+    "DescribeRouteCalculatorResponseTypeDef",
     "DescribeTrackerRequestRequestTypeDef",
+    "DescribeTrackerResponseTypeDef",
     "PositionalAccuracyTypeDef",
     "DisassociateTrackerConsumerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
     "GetDevicePositionHistoryRequestRequestTypeDef",
     "GetDevicePositionRequestRequestTypeDef",
     "GetGeofenceRequestRequestTypeDef",
     "GetMapGlyphsRequestRequestTypeDef",
+    "GetMapGlyphsResponseTypeDef",
     "GetMapSpritesRequestRequestTypeDef",
+    "GetMapSpritesResponseTypeDef",
     "GetMapStyleDescriptorRequestRequestTypeDef",
+    "GetMapStyleDescriptorResponseTypeDef",
     "GetMapTileRequestRequestTypeDef",
+    "GetMapTileResponseTypeDef",
     "GetPlaceRequestRequestTypeDef",
     "LegGeometryTypeDef",
     "StepTypeDef",
+    "ListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
     "ListDevicePositionsRequestRequestTypeDef",
+    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
     "ListGeofenceCollectionsRequestRequestTypeDef",
     "ListGeofenceCollectionsResponseEntryTypeDef",
+    "ListGeofencesRequestListGeofencesPaginateTypeDef",
     "ListGeofencesRequestRequestTypeDef",
+    "ListMapsRequestListMapsPaginateTypeDef",
     "ListMapsRequestRequestTypeDef",
     "ListMapsResponseEntryTypeDef",
+    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
     "ListPlaceIndexesRequestRequestTypeDef",
     "ListPlaceIndexesResponseEntryTypeDef",
+    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
     "ListRouteCalculatorsRequestRequestTypeDef",
     "ListRouteCalculatorsResponseEntryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
     "ListTrackerConsumersRequestRequestTypeDef",
+    "ListTrackerConsumersResponseTypeDef",
+    "ListTrackersRequestListTrackersPaginateTypeDef",
     "ListTrackersRequestRequestTypeDef",
     "ListTrackersResponseEntryTypeDef",
+    "MapConfigurationUpdateTypeDef",
+    "PaginatorConfigTypeDef",
     "PlaceGeometryTypeDef",
     "TimeZoneTypeDef",
+    "PutGeofenceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RouteMatrixEntryErrorTypeDef",
     "SearchForSuggestionsResultTypeDef",
     "SearchPlaceIndexForPositionRequestRequestTypeDef",
     "SearchPlaceIndexForPositionSummaryTypeDef",
     "SearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     "SearchPlaceIndexForSuggestionsSummaryTypeDef",
     "SearchPlaceIndexForTextRequestRequestTypeDef",
     "SearchPlaceIndexForTextSummaryTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateGeofenceCollectionRequestRequestTypeDef",
-    "UpdateMapRequestRequestTypeDef",
+    "UpdateGeofenceCollectionResponseTypeDef",
+    "UpdateKeyResponseTypeDef",
+    "UpdateMapResponseTypeDef",
+    "UpdatePlaceIndexResponseTypeDef",
     "UpdateRouteCalculatorRequestRequestTypeDef",
+    "UpdateRouteCalculatorResponseTypeDef",
     "UpdateTrackerRequestRequestTypeDef",
+    "UpdateTrackerResponseTypeDef",
+    "ListKeysRequestListKeysPaginateTypeDef",
+    "ListKeysRequestRequestTypeDef",
+    "CreateKeyRequestRequestTypeDef",
+    "DescribeKeyResponseTypeDef",
+    "ListKeysResponseEntryTypeDef",
+    "UpdateKeyRequestRequestTypeDef",
     "BatchDeleteDevicePositionHistoryErrorTypeDef",
     "BatchDeleteGeofenceErrorTypeDef",
     "BatchEvaluateGeofencesErrorTypeDef",
     "BatchGetDevicePositionErrorTypeDef",
     "BatchPutGeofenceErrorTypeDef",
     "BatchUpdateDevicePositionErrorTypeDef",
-    "CreateGeofenceCollectionResponseTypeDef",
-    "CreateMapResponseTypeDef",
-    "CreatePlaceIndexResponseTypeDef",
-    "CreateRouteCalculatorResponseTypeDef",
-    "CreateTrackerResponseTypeDef",
-    "DescribeGeofenceCollectionResponseTypeDef",
-    "DescribeRouteCalculatorResponseTypeDef",
-    "DescribeTrackerResponseTypeDef",
-    "GetMapGlyphsResponseTypeDef",
-    "GetMapSpritesResponseTypeDef",
-    "GetMapStyleDescriptorResponseTypeDef",
-    "GetMapTileResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListTrackerConsumersResponseTypeDef",
-    "PutGeofenceResponseTypeDef",
-    "UpdateGeofenceCollectionResponseTypeDef",
-    "UpdateMapResponseTypeDef",
-    "UpdatePlaceIndexResponseTypeDef",
-    "UpdateRouteCalculatorResponseTypeDef",
-    "UpdateTrackerResponseTypeDef",
     "CalculateRouteTruckModeOptionsTypeDef",
     "GeofenceGeometryTypeDef",
     "CreateMapRequestRequestTypeDef",
     "DescribeMapResponseTypeDef",
     "CreatePlaceIndexRequestRequestTypeDef",
     "DescribePlaceIndexResponseTypeDef",
     "UpdatePlaceIndexRequestRequestTypeDef",
     "DevicePositionTypeDef",
     "DevicePositionUpdateTypeDef",
     "GetDevicePositionResponseTypeDef",
     "ListDevicePositionsResponseEntryTypeDef",
-    "GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    "ListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
-    "ListGeofencesRequestListGeofencesPaginateTypeDef",
-    "ListMapsRequestListMapsPaginateTypeDef",
-    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
-    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
-    "ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    "ListTrackersRequestListTrackersPaginateTypeDef",
     "LegTypeDef",
     "ListGeofenceCollectionsResponseTypeDef",
     "ListMapsResponseTypeDef",
     "ListPlaceIndexesResponseTypeDef",
     "ListRouteCalculatorsResponseTypeDef",
     "ListTrackersResponseTypeDef",
+    "UpdateMapRequestRequestTypeDef",
     "PlaceTypeDef",
     "RouteMatrixEntryTypeDef",
     "SearchPlaceIndexForSuggestionsResponseTypeDef",
+    "ListKeysResponseTypeDef",
     "BatchDeleteDevicePositionHistoryResponseTypeDef",
     "BatchDeleteGeofenceResponseTypeDef",
     "BatchEvaluateGeofencesResponseTypeDef",
     "BatchPutGeofenceResponseTypeDef",
     "BatchUpdateDevicePositionResponseTypeDef",
     "CalculateRouteMatrixRequestRequestTypeDef",
     "CalculateRouteRequestRequestTypeDef",
@@ -184,14 +200,44 @@
     "CalculateRouteMatrixResponseTypeDef",
     "BatchPutGeofenceRequestRequestTypeDef",
     "ListGeofencesResponseTypeDef",
     "SearchPlaceIndexForPositionResponseTypeDef",
     "SearchPlaceIndexForTextResponseTypeDef",
 )
 
+ApiKeyFilterTypeDef = TypedDict(
+    "ApiKeyFilterTypeDef",
+    {
+        "KeyStatus": StatusType,
+    },
+    total=False,
+)
+
+_RequiredApiKeyRestrictionsTypeDef = TypedDict(
+    "_RequiredApiKeyRestrictionsTypeDef",
+    {
+        "AllowActions": Sequence[str],
+        "AllowResources": Sequence[str],
+    },
+)
+_OptionalApiKeyRestrictionsTypeDef = TypedDict(
+    "_OptionalApiKeyRestrictionsTypeDef",
+    {
+        "AllowReferers": Sequence[str],
+    },
+    total=False,
+)
+
+
+class ApiKeyRestrictionsTypeDef(
+    _RequiredApiKeyRestrictionsTypeDef, _OptionalApiKeyRestrictionsTypeDef
+):
+    pass
+
+
 AssociateTrackerConsumerRequestRequestTypeDef = TypedDict(
     "AssociateTrackerConsumerRequestRequestTypeDef",
     {
         "ConsumerArn": str,
         "TrackerName": str,
     },
 )
@@ -209,25 +255,14 @@
     "BatchDeleteDevicePositionHistoryRequestRequestTypeDef",
     {
         "DeviceIds": Sequence[str],
         "TrackerName": str,
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
 BatchDeleteGeofenceRequestRequestTypeDef = TypedDict(
     "BatchDeleteGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceIds": Sequence[str],
     },
 )
@@ -321,35 +356,90 @@
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateGeofenceCollectionRequestRequestTypeDef(
     _RequiredCreateGeofenceCollectionRequestRequestTypeDef,
     _OptionalCreateGeofenceCollectionRequestRequestTypeDef,
 ):
     pass
 
-MapConfigurationTypeDef = TypedDict(
-    "MapConfigurationTypeDef",
+
+CreateGeofenceCollectionResponseTypeDef = TypedDict(
+    "CreateGeofenceCollectionResponseTypeDef",
+    {
+        "CollectionArn": str,
+        "CollectionName": str,
+        "CreateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateKeyResponseTypeDef = TypedDict(
+    "CreateKeyResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "Key": str,
+        "KeyArn": str,
+        "KeyName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredMapConfigurationTypeDef = TypedDict(
+    "_RequiredMapConfigurationTypeDef",
     {
         "Style": str,
     },
 )
+_OptionalMapConfigurationTypeDef = TypedDict(
+    "_OptionalMapConfigurationTypeDef",
+    {
+        "PoliticalView": str,
+    },
+    total=False,
+)
+
+
+class MapConfigurationTypeDef(_RequiredMapConfigurationTypeDef, _OptionalMapConfigurationTypeDef):
+    pass
+
+
+CreateMapResponseTypeDef = TypedDict(
+    "CreateMapResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "MapArn": str,
+        "MapName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DataSourceConfigurationTypeDef = TypedDict(
     "DataSourceConfigurationTypeDef",
     {
         "IntendedUse": IntendedUseType,
     },
     total=False,
 )
 
+CreatePlaceIndexResponseTypeDef = TypedDict(
+    "CreatePlaceIndexResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "IndexArn": str,
+        "IndexName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRouteCalculatorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
         "DataSource": str,
     },
 )
@@ -359,20 +449,32 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateRouteCalculatorRequestRequestTypeDef(
     _RequiredCreateRouteCalculatorRequestRequestTypeDef,
     _OptionalCreateRouteCalculatorRequestRequestTypeDef,
 ):
     pass
 
+
+CreateRouteCalculatorResponseTypeDef = TypedDict(
+    "CreateRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "CreateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 _OptionalCreateTrackerRequestRequestTypeDef = TypedDict(
@@ -384,26 +486,45 @@
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateTrackerRequestRequestTypeDef(
     _RequiredCreateTrackerRequestRequestTypeDef, _OptionalCreateTrackerRequestRequestTypeDef
 ):
     pass
 
+
+CreateTrackerResponseTypeDef = TypedDict(
+    "CreateTrackerResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "TrackerArn": str,
+        "TrackerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteGeofenceCollectionRequestRequestTypeDef = TypedDict(
     "DeleteGeofenceCollectionRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
 
+DeleteKeyRequestRequestTypeDef = TypedDict(
+    "DeleteKeyRequestRequestTypeDef",
+    {
+        "KeyName": str,
+    },
+)
+
 DeleteMapRequestRequestTypeDef = TypedDict(
     "DeleteMapRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
 
@@ -431,14 +552,37 @@
 DescribeGeofenceCollectionRequestRequestTypeDef = TypedDict(
     "DescribeGeofenceCollectionRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
 
+DescribeGeofenceCollectionResponseTypeDef = TypedDict(
+    "DescribeGeofenceCollectionResponseTypeDef",
+    {
+        "CollectionArn": str,
+        "CollectionName": str,
+        "CreateTime": datetime,
+        "Description": str,
+        "KmsKeyId": str,
+        "PricingPlan": PricingPlanType,
+        "PricingPlanDataSource": str,
+        "Tags": Dict[str, str],
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeKeyRequestRequestTypeDef = TypedDict(
+    "DescribeKeyRequestRequestTypeDef",
+    {
+        "KeyName": str,
+    },
+)
+
 DescribeMapRequestRequestTypeDef = TypedDict(
     "DescribeMapRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
 
@@ -452,21 +596,53 @@
 DescribeRouteCalculatorRequestRequestTypeDef = TypedDict(
     "DescribeRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
     },
 )
 
+DescribeRouteCalculatorResponseTypeDef = TypedDict(
+    "DescribeRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "CreateTime": datetime,
+        "DataSource": str,
+        "Description": str,
+        "PricingPlan": PricingPlanType,
+        "Tags": Dict[str, str],
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTrackerRequestRequestTypeDef = TypedDict(
     "DescribeTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 
+DescribeTrackerResponseTypeDef = TypedDict(
+    "DescribeTrackerResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "Description": str,
+        "KmsKeyId": str,
+        "PositionFiltering": PositionFilteringType,
+        "PricingPlan": PricingPlanType,
+        "PricingPlanDataSource": str,
+        "Tags": Dict[str, str],
+        "TrackerArn": str,
+        "TrackerName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PositionalAccuracyTypeDef = TypedDict(
     "PositionalAccuracyTypeDef",
     {
         "Horizontal": float,
     },
 )
 
@@ -474,24 +650,39 @@
     "DisassociateTrackerConsumerRequestRequestTypeDef",
     {
         "ConsumerArn": str,
         "TrackerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DeviceId": str,
+        "TrackerName": str,
+    },
+)
+_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
+    {
+        "EndTimeExclusive": Union[datetime, str],
+        "StartTimeInclusive": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef(
+    _RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
+    _OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetDevicePositionHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetDevicePositionHistoryRequestRequestTypeDef",
     {
         "DeviceId": str,
         "TrackerName": str,
     },
 )
@@ -502,20 +693,22 @@
         "MaxResults": int,
         "NextToken": str,
         "StartTimeInclusive": Union[datetime, str],
     },
     total=False,
 )
 
+
 class GetDevicePositionHistoryRequestRequestTypeDef(
     _RequiredGetDevicePositionHistoryRequestRequestTypeDef,
     _OptionalGetDevicePositionHistoryRequestRequestTypeDef,
 ):
     pass
 
+
 GetDevicePositionRequestRequestTypeDef = TypedDict(
     "GetDevicePositionRequestRequestTypeDef",
     {
         "DeviceId": str,
         "TrackerName": str,
     },
 )
@@ -524,47 +717,144 @@
     "GetGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceId": str,
     },
 )
 
-GetMapGlyphsRequestRequestTypeDef = TypedDict(
-    "GetMapGlyphsRequestRequestTypeDef",
+_RequiredGetMapGlyphsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapGlyphsRequestRequestTypeDef",
     {
         "FontStack": str,
         "FontUnicodeRange": str,
         "MapName": str,
     },
 )
+_OptionalGetMapGlyphsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapGlyphsRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapSpritesRequestRequestTypeDef = TypedDict(
-    "GetMapSpritesRequestRequestTypeDef",
+
+class GetMapGlyphsRequestRequestTypeDef(
+    _RequiredGetMapGlyphsRequestRequestTypeDef, _OptionalGetMapGlyphsRequestRequestTypeDef
+):
+    pass
+
+
+GetMapGlyphsResponseTypeDef = TypedDict(
+    "GetMapGlyphsResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapSpritesRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapSpritesRequestRequestTypeDef",
     {
         "FileName": str,
         "MapName": str,
     },
 )
+_OptionalGetMapSpritesRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapSpritesRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
-    "GetMapStyleDescriptorRequestRequestTypeDef",
+
+class GetMapSpritesRequestRequestTypeDef(
+    _RequiredGetMapSpritesRequestRequestTypeDef, _OptionalGetMapSpritesRequestRequestTypeDef
+):
+    pass
+
+
+GetMapSpritesResponseTypeDef = TypedDict(
+    "GetMapSpritesResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapStyleDescriptorRequestRequestTypeDef",
     {
         "MapName": str,
     },
 )
+_OptionalGetMapStyleDescriptorRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapStyleDescriptorRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
 
-GetMapTileRequestRequestTypeDef = TypedDict(
-    "GetMapTileRequestRequestTypeDef",
+
+class GetMapStyleDescriptorRequestRequestTypeDef(
+    _RequiredGetMapStyleDescriptorRequestRequestTypeDef,
+    _OptionalGetMapStyleDescriptorRequestRequestTypeDef,
+):
+    pass
+
+
+GetMapStyleDescriptorResponseTypeDef = TypedDict(
+    "GetMapStyleDescriptorResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetMapTileRequestRequestTypeDef = TypedDict(
+    "_RequiredGetMapTileRequestRequestTypeDef",
     {
         "MapName": str,
         "X": str,
         "Y": str,
         "Z": str,
     },
 )
+_OptionalGetMapTileRequestRequestTypeDef = TypedDict(
+    "_OptionalGetMapTileRequestRequestTypeDef",
+    {
+        "Key": str,
+    },
+    total=False,
+)
+
+
+class GetMapTileRequestRequestTypeDef(
+    _RequiredGetMapTileRequestRequestTypeDef, _OptionalGetMapTileRequestRequestTypeDef
+):
+    pass
+
+
+GetMapTileResponseTypeDef = TypedDict(
+    "GetMapTileResponseTypeDef",
+    {
+        "Blob": StreamingBody,
+        "CacheControl": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetPlaceRequestRequestTypeDef = TypedDict(
     "_RequiredGetPlaceRequestRequestTypeDef",
     {
         "IndexName": str,
         "PlaceId": str,
     },
@@ -573,19 +863,21 @@
     "_OptionalGetPlaceRequestRequestTypeDef",
     {
         "Language": str,
     },
     total=False,
 )
 
+
 class GetPlaceRequestRequestTypeDef(
     _RequiredGetPlaceRequestRequestTypeDef, _OptionalGetPlaceRequestRequestTypeDef
 ):
     pass
 
+
 LegGeometryTypeDef = TypedDict(
     "LegGeometryTypeDef",
     {
         "LineString": List[List[float]],
     },
     total=False,
 )
@@ -603,17 +895,41 @@
     "_OptionalStepTypeDef",
     {
         "GeometryOffset": int,
     },
     total=False,
 )
 
+
 class StepTypeDef(_RequiredStepTypeDef, _OptionalStepTypeDef):
     pass
 
+
+_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
+    "_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
+    {
+        "TrackerName": str,
+    },
+)
+_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
+    "_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDevicePositionsRequestListDevicePositionsPaginateTypeDef(
+    _RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
+    _OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDevicePositionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDevicePositionsRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 _OptionalListDevicePositionsRequestRequestTypeDef = TypedDict(
@@ -621,20 +937,30 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListDevicePositionsRequestRequestTypeDef(
     _RequiredListDevicePositionsRequestRequestTypeDef,
     _OptionalListDevicePositionsRequestRequestTypeDef,
 ):
     pass
 
+
+ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef = TypedDict(
+    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGeofenceCollectionsRequestRequestTypeDef = TypedDict(
     "ListGeofenceCollectionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -654,20 +980,44 @@
     {
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
+
 class ListGeofenceCollectionsResponseEntryTypeDef(
     _RequiredListGeofenceCollectionsResponseEntryTypeDef,
     _OptionalListGeofenceCollectionsResponseEntryTypeDef,
 ):
     pass
 
+
+_RequiredListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
+    "_RequiredListGeofencesRequestListGeofencesPaginateTypeDef",
+    {
+        "CollectionName": str,
+    },
+)
+_OptionalListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
+    "_OptionalListGeofencesRequestListGeofencesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGeofencesRequestListGeofencesPaginateTypeDef(
+    _RequiredListGeofencesRequestListGeofencesPaginateTypeDef,
+    _OptionalListGeofencesRequestListGeofencesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGeofencesRequestRequestTypeDef = TypedDict(
     "_RequiredListGeofencesRequestRequestTypeDef",
     {
         "CollectionName": str,
     },
 )
 _OptionalListGeofencesRequestRequestTypeDef = TypedDict(
@@ -675,19 +1025,29 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListGeofencesRequestRequestTypeDef(
     _RequiredListGeofencesRequestRequestTypeDef, _OptionalListGeofencesRequestRequestTypeDef
 ):
     pass
 
+
+ListMapsRequestListMapsPaginateTypeDef = TypedDict(
+    "ListMapsRequestListMapsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMapsRequestRequestTypeDef = TypedDict(
     "ListMapsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -707,19 +1067,29 @@
     "_OptionalListMapsResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
+
 class ListMapsResponseEntryTypeDef(
     _RequiredListMapsResponseEntryTypeDef, _OptionalListMapsResponseEntryTypeDef
 ):
     pass
 
+
+ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef = TypedDict(
+    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPlaceIndexesRequestRequestTypeDef = TypedDict(
     "ListPlaceIndexesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -739,19 +1109,29 @@
     "_OptionalListPlaceIndexesResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
+
 class ListPlaceIndexesResponseEntryTypeDef(
     _RequiredListPlaceIndexesResponseEntryTypeDef, _OptionalListPlaceIndexesResponseEntryTypeDef
 ):
     pass
 
+
+ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef = TypedDict(
+    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRouteCalculatorsRequestRequestTypeDef = TypedDict(
     "ListRouteCalculatorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -771,27 +1151,59 @@
     "_OptionalListRouteCalculatorsResponseEntryTypeDef",
     {
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
+
 class ListRouteCalculatorsResponseEntryTypeDef(
     _RequiredListRouteCalculatorsResponseEntryTypeDef,
     _OptionalListRouteCalculatorsResponseEntryTypeDef,
 ):
     pass
 
+
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
+_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
+    "_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
+    {
+        "TrackerName": str,
+    },
+)
+_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
+    "_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef(
+    _RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
+    _OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTrackerConsumersRequestRequestTypeDef = TypedDict(
     "_RequiredListTrackerConsumersRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 _OptionalListTrackerConsumersRequestRequestTypeDef = TypedDict(
@@ -799,20 +1211,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListTrackerConsumersRequestRequestTypeDef(
     _RequiredListTrackerConsumersRequestRequestTypeDef,
     _OptionalListTrackerConsumersRequestRequestTypeDef,
 ):
     pass
 
+
+ListTrackerConsumersResponseTypeDef = TypedDict(
+    "ListTrackerConsumersResponseTypeDef",
+    {
+        "ConsumerArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTrackersRequestListTrackersPaginateTypeDef = TypedDict(
+    "ListTrackersRequestListTrackersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTrackersRequestRequestTypeDef = TypedDict(
     "ListTrackersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -832,19 +1263,39 @@
     {
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
+
 class ListTrackersResponseEntryTypeDef(
     _RequiredListTrackersResponseEntryTypeDef, _OptionalListTrackersResponseEntryTypeDef
 ):
     pass
 
+
+MapConfigurationUpdateTypeDef = TypedDict(
+    "MapConfigurationUpdateTypeDef",
+    {
+        "PoliticalView": str,
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
+    },
+    total=False,
+)
+
 PlaceGeometryTypeDef = TypedDict(
     "PlaceGeometryTypeDef",
     {
         "Point": List[float],
     },
     total=False,
 )
@@ -859,55 +1310,84 @@
     "_OptionalTimeZoneTypeDef",
     {
         "Offset": int,
     },
     total=False,
 )
 
+
 class TimeZoneTypeDef(_RequiredTimeZoneTypeDef, _OptionalTimeZoneTypeDef):
     pass
 
+
+PutGeofenceResponseTypeDef = TypedDict(
+    "PutGeofenceResponseTypeDef",
+    {
+        "CreateTime": datetime,
+        "GeofenceId": str,
+        "UpdateTime": datetime,
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
 _RequiredRouteMatrixEntryErrorTypeDef = TypedDict(
     "_RequiredRouteMatrixEntryErrorTypeDef",
     {
         "Code": RouteMatrixErrorCodeType,
     },
 )
 _OptionalRouteMatrixEntryErrorTypeDef = TypedDict(
     "_OptionalRouteMatrixEntryErrorTypeDef",
     {
         "Message": str,
     },
     total=False,
 )
 
+
 class RouteMatrixEntryErrorTypeDef(
     _RequiredRouteMatrixEntryErrorTypeDef, _OptionalRouteMatrixEntryErrorTypeDef
 ):
     pass
 
+
 _RequiredSearchForSuggestionsResultTypeDef = TypedDict(
     "_RequiredSearchForSuggestionsResultTypeDef",
     {
         "Text": str,
     },
 )
 _OptionalSearchForSuggestionsResultTypeDef = TypedDict(
     "_OptionalSearchForSuggestionsResultTypeDef",
     {
+        "Categories": List[str],
         "PlaceId": str,
+        "SupplementalCategories": List[str],
     },
     total=False,
 )
 
+
 class SearchForSuggestionsResultTypeDef(
     _RequiredSearchForSuggestionsResultTypeDef, _OptionalSearchForSuggestionsResultTypeDef
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForPositionRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForPositionRequestRequestTypeDef",
     {
         "IndexName": str,
         "Position": Sequence[float],
     },
 )
@@ -916,20 +1396,22 @@
     {
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForPositionRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForPositionRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForPositionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForPositionSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForPositionSummaryTypeDef",
     {
         "DataSource": str,
         "Position": List[float],
     },
 )
@@ -938,120 +1420,134 @@
     {
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForPositionSummaryTypeDef(
     _RequiredSearchPlaceIndexForPositionSummaryTypeDef,
     _OptionalSearchPlaceIndexForPositionSummaryTypeDef,
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     {
         "IndexName": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef",
     {
         "BiasPosition": Sequence[float],
         "FilterBBox": Sequence[float],
+        "FilterCategories": Sequence[str],
         "FilterCountries": Sequence[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForSuggestionsRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForSuggestionsRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForSuggestionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef",
     {
         "DataSource": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef",
     {
         "BiasPosition": List[float],
         "FilterBBox": List[float],
+        "FilterCategories": List[str],
         "FilterCountries": List[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForSuggestionsSummaryTypeDef(
     _RequiredSearchPlaceIndexForSuggestionsSummaryTypeDef,
     _OptionalSearchPlaceIndexForSuggestionsSummaryTypeDef,
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForTextRequestRequestTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForTextRequestRequestTypeDef",
     {
         "IndexName": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForTextRequestRequestTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForTextRequestRequestTypeDef",
     {
         "BiasPosition": Sequence[float],
         "FilterBBox": Sequence[float],
+        "FilterCategories": Sequence[str],
         "FilterCountries": Sequence[str],
         "Language": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForTextRequestRequestTypeDef(
     _RequiredSearchPlaceIndexForTextRequestRequestTypeDef,
     _OptionalSearchPlaceIndexForTextRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredSearchPlaceIndexForTextSummaryTypeDef = TypedDict(
     "_RequiredSearchPlaceIndexForTextSummaryTypeDef",
     {
         "DataSource": str,
         "Text": str,
     },
 )
 _OptionalSearchPlaceIndexForTextSummaryTypeDef = TypedDict(
     "_OptionalSearchPlaceIndexForTextSummaryTypeDef",
     {
         "BiasPosition": List[float],
         "FilterBBox": List[float],
+        "FilterCategories": List[str],
         "FilterCountries": List[str],
         "Language": str,
         "MaxResults": int,
         "ResultBBox": List[float],
     },
     total=False,
 )
 
+
 class SearchPlaceIndexForTextSummaryTypeDef(
     _RequiredSearchPlaceIndexForTextSummaryTypeDef, _OptionalSearchPlaceIndexForTextSummaryTypeDef
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -1076,39 +1572,61 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
+
 class UpdateGeofenceCollectionRequestRequestTypeDef(
     _RequiredUpdateGeofenceCollectionRequestRequestTypeDef,
     _OptionalUpdateGeofenceCollectionRequestRequestTypeDef,
 ):
     pass
 
-_RequiredUpdateMapRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateMapRequestRequestTypeDef",
+
+UpdateGeofenceCollectionResponseTypeDef = TypedDict(
+    "UpdateGeofenceCollectionResponseTypeDef",
     {
-        "MapName": str,
+        "CollectionArn": str,
+        "CollectionName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalUpdateMapRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateMapRequestRequestTypeDef",
+
+UpdateKeyResponseTypeDef = TypedDict(
+    "UpdateKeyResponseTypeDef",
     {
-        "Description": str,
-        "PricingPlan": PricingPlanType,
+        "KeyArn": str,
+        "KeyName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class UpdateMapRequestRequestTypeDef(
-    _RequiredUpdateMapRequestRequestTypeDef, _OptionalUpdateMapRequestRequestTypeDef
-):
-    pass
+UpdateMapResponseTypeDef = TypedDict(
+    "UpdateMapResponseTypeDef",
+    {
+        "MapArn": str,
+        "MapName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdatePlaceIndexResponseTypeDef = TypedDict(
+    "UpdatePlaceIndexResponseTypeDef",
+    {
+        "IndexArn": str,
+        "IndexName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateRouteCalculatorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteCalculatorRequestRequestTypeDef",
     {
         "CalculatorName": str,
     },
 )
@@ -1117,20 +1635,32 @@
     {
         "Description": str,
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
+
 class UpdateRouteCalculatorRequestRequestTypeDef(
     _RequiredUpdateRouteCalculatorRequestRequestTypeDef,
     _OptionalUpdateRouteCalculatorRequestRequestTypeDef,
 ):
     pass
 
+
+UpdateRouteCalculatorResponseTypeDef = TypedDict(
+    "UpdateRouteCalculatorResponseTypeDef",
+    {
+        "CalculatorArn": str,
+        "CalculatorName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTrackerRequestRequestTypeDef",
     {
         "TrackerName": str,
     },
 )
 _OptionalUpdateTrackerRequestRequestTypeDef = TypedDict(
@@ -1140,277 +1670,188 @@
         "PositionFiltering": PositionFilteringType,
         "PricingPlan": PricingPlanType,
         "PricingPlanDataSource": str,
     },
     total=False,
 )
 
+
 class UpdateTrackerRequestRequestTypeDef(
     _RequiredUpdateTrackerRequestRequestTypeDef, _OptionalUpdateTrackerRequestRequestTypeDef
 ):
     pass
 
-BatchDeleteDevicePositionHistoryErrorTypeDef = TypedDict(
-    "BatchDeleteDevicePositionHistoryErrorTypeDef",
-    {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-    },
-)
-
-BatchDeleteGeofenceErrorTypeDef = TypedDict(
-    "BatchDeleteGeofenceErrorTypeDef",
-    {
-        "Error": BatchItemErrorTypeDef,
-        "GeofenceId": str,
-    },
-)
 
-BatchEvaluateGeofencesErrorTypeDef = TypedDict(
-    "BatchEvaluateGeofencesErrorTypeDef",
-    {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-        "SampleTime": datetime,
-    },
-)
-
-BatchGetDevicePositionErrorTypeDef = TypedDict(
-    "BatchGetDevicePositionErrorTypeDef",
+UpdateTrackerResponseTypeDef = TypedDict(
+    "UpdateTrackerResponseTypeDef",
     {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
+        "TrackerArn": str,
+        "TrackerName": str,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-BatchPutGeofenceErrorTypeDef = TypedDict(
-    "BatchPutGeofenceErrorTypeDef",
+ListKeysRequestListKeysPaginateTypeDef = TypedDict(
+    "ListKeysRequestListKeysPaginateTypeDef",
     {
-        "Error": BatchItemErrorTypeDef,
-        "GeofenceId": str,
+        "Filter": ApiKeyFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-BatchUpdateDevicePositionErrorTypeDef = TypedDict(
-    "BatchUpdateDevicePositionErrorTypeDef",
+ListKeysRequestRequestTypeDef = TypedDict(
+    "ListKeysRequestRequestTypeDef",
     {
-        "DeviceId": str,
-        "Error": BatchItemErrorTypeDef,
-        "SampleTime": datetime,
+        "Filter": ApiKeyFilterTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
+    total=False,
 )
 
-CreateGeofenceCollectionResponseTypeDef = TypedDict(
-    "CreateGeofenceCollectionResponseTypeDef",
+_RequiredCreateKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateKeyRequestRequestTypeDef",
     {
-        "CollectionArn": str,
-        "CollectionName": str,
-        "CreateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
     },
 )
-
-CreateMapResponseTypeDef = TypedDict(
-    "CreateMapResponseTypeDef",
+_OptionalCreateKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateKeyRequestRequestTypeDef",
     {
-        "CreateTime": datetime,
-        "MapArn": str,
-        "MapName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Description": str,
+        "ExpireTime": Union[datetime, str],
+        "NoExpiry": bool,
+        "Tags": Mapping[str, str],
     },
+    total=False,
 )
 
-CreatePlaceIndexResponseTypeDef = TypedDict(
-    "CreatePlaceIndexResponseTypeDef",
-    {
-        "CreateTime": datetime,
-        "IndexArn": str,
-        "IndexName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateRouteCalculatorResponseTypeDef = TypedDict(
-    "CreateRouteCalculatorResponseTypeDef",
-    {
-        "CalculatorArn": str,
-        "CalculatorName": str,
-        "CreateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class CreateKeyRequestRequestTypeDef(
+    _RequiredCreateKeyRequestRequestTypeDef, _OptionalCreateKeyRequestRequestTypeDef
+):
+    pass
 
-CreateTrackerResponseTypeDef = TypedDict(
-    "CreateTrackerResponseTypeDef",
-    {
-        "CreateTime": datetime,
-        "TrackerArn": str,
-        "TrackerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-DescribeGeofenceCollectionResponseTypeDef = TypedDict(
-    "DescribeGeofenceCollectionResponseTypeDef",
+DescribeKeyResponseTypeDef = TypedDict(
+    "DescribeKeyResponseTypeDef",
     {
-        "CollectionArn": str,
-        "CollectionName": str,
         "CreateTime": datetime,
         "Description": str,
-        "KmsKeyId": str,
-        "PricingPlan": PricingPlanType,
-        "PricingPlanDataSource": str,
+        "ExpireTime": datetime,
+        "Key": str,
+        "KeyArn": str,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeRouteCalculatorResponseTypeDef = TypedDict(
-    "DescribeRouteCalculatorResponseTypeDef",
+_RequiredListKeysResponseEntryTypeDef = TypedDict(
+    "_RequiredListKeysResponseEntryTypeDef",
     {
-        "CalculatorArn": str,
-        "CalculatorName": str,
         "CreateTime": datetime,
-        "DataSource": str,
-        "Description": str,
-        "PricingPlan": PricingPlanType,
-        "Tags": Dict[str, str],
+        "ExpireTime": datetime,
+        "KeyName": str,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-DescribeTrackerResponseTypeDef = TypedDict(
-    "DescribeTrackerResponseTypeDef",
+_OptionalListKeysResponseEntryTypeDef = TypedDict(
+    "_OptionalListKeysResponseEntryTypeDef",
     {
-        "CreateTime": datetime,
         "Description": str,
-        "KmsKeyId": str,
-        "PositionFiltering": PositionFilteringType,
-        "PricingPlan": PricingPlanType,
-        "PricingPlanDataSource": str,
-        "Tags": Dict[str, str],
-        "TrackerArn": str,
-        "TrackerName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-GetMapGlyphsResponseTypeDef = TypedDict(
-    "GetMapGlyphsResponseTypeDef",
-    {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-GetMapSpritesResponseTypeDef = TypedDict(
-    "GetMapSpritesResponseTypeDef",
-    {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListKeysResponseEntryTypeDef(
+    _RequiredListKeysResponseEntryTypeDef, _OptionalListKeysResponseEntryTypeDef
+):
+    pass
 
-GetMapStyleDescriptorResponseTypeDef = TypedDict(
-    "GetMapStyleDescriptorResponseTypeDef",
-    {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-GetMapTileResponseTypeDef = TypedDict(
-    "GetMapTileResponseTypeDef",
+_RequiredUpdateKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateKeyRequestRequestTypeDef",
     {
-        "Blob": StreamingBody,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "KeyName": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalUpdateKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateKeyRequestRequestTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Description": str,
+        "ExpireTime": Union[datetime, str],
+        "ForceUpdate": bool,
+        "NoExpiry": bool,
+        "Restrictions": ApiKeyRestrictionsTypeDef,
     },
+    total=False,
 )
 
-ListTrackerConsumersResponseTypeDef = TypedDict(
-    "ListTrackerConsumersResponseTypeDef",
-    {
-        "ConsumerArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-PutGeofenceResponseTypeDef = TypedDict(
-    "PutGeofenceResponseTypeDef",
+class UpdateKeyRequestRequestTypeDef(
+    _RequiredUpdateKeyRequestRequestTypeDef, _OptionalUpdateKeyRequestRequestTypeDef
+):
+    pass
+
+
+BatchDeleteDevicePositionHistoryErrorTypeDef = TypedDict(
+    "BatchDeleteDevicePositionHistoryErrorTypeDef",
     {
-        "CreateTime": datetime,
-        "GeofenceId": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
     },
 )
 
-UpdateGeofenceCollectionResponseTypeDef = TypedDict(
-    "UpdateGeofenceCollectionResponseTypeDef",
+BatchDeleteGeofenceErrorTypeDef = TypedDict(
+    "BatchDeleteGeofenceErrorTypeDef",
     {
-        "CollectionArn": str,
-        "CollectionName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Error": BatchItemErrorTypeDef,
+        "GeofenceId": str,
     },
 )
 
-UpdateMapResponseTypeDef = TypedDict(
-    "UpdateMapResponseTypeDef",
+BatchEvaluateGeofencesErrorTypeDef = TypedDict(
+    "BatchEvaluateGeofencesErrorTypeDef",
     {
-        "MapArn": str,
-        "MapName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
+        "SampleTime": datetime,
     },
 )
 
-UpdatePlaceIndexResponseTypeDef = TypedDict(
-    "UpdatePlaceIndexResponseTypeDef",
+BatchGetDevicePositionErrorTypeDef = TypedDict(
+    "BatchGetDevicePositionErrorTypeDef",
     {
-        "IndexArn": str,
-        "IndexName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
     },
 )
 
-UpdateRouteCalculatorResponseTypeDef = TypedDict(
-    "UpdateRouteCalculatorResponseTypeDef",
+BatchPutGeofenceErrorTypeDef = TypedDict(
+    "BatchPutGeofenceErrorTypeDef",
     {
-        "CalculatorArn": str,
-        "CalculatorName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Error": BatchItemErrorTypeDef,
+        "GeofenceId": str,
     },
 )
 
-UpdateTrackerResponseTypeDef = TypedDict(
-    "UpdateTrackerResponseTypeDef",
+BatchUpdateDevicePositionErrorTypeDef = TypedDict(
+    "BatchUpdateDevicePositionErrorTypeDef",
     {
-        "TrackerArn": str,
-        "TrackerName": str,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DeviceId": str,
+        "Error": BatchItemErrorTypeDef,
+        "SampleTime": datetime,
     },
 )
 
 CalculateRouteTruckModeOptionsTypeDef = TypedDict(
     "CalculateRouteTruckModeOptionsTypeDef",
     {
         "AvoidFerries": bool,
@@ -1443,32 +1884,34 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateMapRequestRequestTypeDef(
     _RequiredCreateMapRequestRequestTypeDef, _OptionalCreateMapRequestRequestTypeDef
 ):
     pass
 
+
 DescribeMapResponseTypeDef = TypedDict(
     "DescribeMapResponseTypeDef",
     {
         "Configuration": MapConfigurationTypeDef,
         "CreateTime": datetime,
         "DataSource": str,
         "Description": str,
         "MapArn": str,
         "MapName": str,
         "PricingPlan": PricingPlanType,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePlaceIndexRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePlaceIndexRequestRequestTypeDef",
     {
         "DataSource": str,
@@ -1482,32 +1925,34 @@
         "Description": str,
         "PricingPlan": PricingPlanType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreatePlaceIndexRequestRequestTypeDef(
     _RequiredCreatePlaceIndexRequestRequestTypeDef, _OptionalCreatePlaceIndexRequestRequestTypeDef
 ):
     pass
 
+
 DescribePlaceIndexResponseTypeDef = TypedDict(
     "DescribePlaceIndexResponseTypeDef",
     {
         "CreateTime": datetime,
         "DataSource": str,
         "DataSourceConfiguration": DataSourceConfigurationTypeDef,
         "Description": str,
         "IndexArn": str,
         "IndexName": str,
         "PricingPlan": PricingPlanType,
         "Tags": Dict[str, str],
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePlaceIndexRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePlaceIndexRequestRequestTypeDef",
     {
         "IndexName": str,
@@ -1519,19 +1964,21 @@
         "DataSourceConfiguration": DataSourceConfigurationTypeDef,
         "Description": str,
         "PricingPlan": PricingPlanType,
     },
     total=False,
 )
 
+
 class UpdatePlaceIndexRequestRequestTypeDef(
     _RequiredUpdatePlaceIndexRequestRequestTypeDef, _OptionalUpdatePlaceIndexRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredDevicePositionTypeDef = TypedDict(
     "_RequiredDevicePositionTypeDef",
     {
         "Position": List[float],
         "ReceivedTime": datetime,
         "SampleTime": datetime,
     },
@@ -1542,17 +1989,19 @@
         "Accuracy": PositionalAccuracyTypeDef,
         "DeviceId": str,
         "PositionProperties": Dict[str, str],
     },
     total=False,
 )
 
+
 class DevicePositionTypeDef(_RequiredDevicePositionTypeDef, _OptionalDevicePositionTypeDef):
     pass
 
+
 _RequiredDevicePositionUpdateTypeDef = TypedDict(
     "_RequiredDevicePositionUpdateTypeDef",
     {
         "DeviceId": str,
         "Position": Sequence[float],
         "SampleTime": Union[datetime, str],
     },
@@ -1562,29 +2011,31 @@
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "PositionProperties": Mapping[str, str],
     },
     total=False,
 )
 
+
 class DevicePositionUpdateTypeDef(
     _RequiredDevicePositionUpdateTypeDef, _OptionalDevicePositionUpdateTypeDef
 ):
     pass
 
+
 GetDevicePositionResponseTypeDef = TypedDict(
     "GetDevicePositionResponseTypeDef",
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "DeviceId": str,
         "Position": List[float],
         "PositionProperties": Dict[str, str],
         "ReceivedTime": datetime,
         "SampleTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListDevicePositionsResponseEntryTypeDef = TypedDict(
     "_RequiredListDevicePositionsResponseEntryTypeDef",
     {
         "DeviceId": str,
@@ -1597,142 +2048,21 @@
     {
         "Accuracy": PositionalAccuracyTypeDef,
         "PositionProperties": Dict[str, str],
     },
     total=False,
 )
 
+
 class ListDevicePositionsResponseEntryTypeDef(
     _RequiredListDevicePositionsResponseEntryTypeDef,
     _OptionalListDevicePositionsResponseEntryTypeDef,
 ):
     pass
 
-_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "TrackerName": str,
-    },
-)
-_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef",
-    {
-        "EndTimeExclusive": Union[datetime, str],
-        "StartTimeInclusive": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef(
-    _RequiredGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-    _OptionalGetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
-    "_RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    {
-        "TrackerName": str,
-    },
-)
-_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef = TypedDict(
-    "_OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDevicePositionsRequestListDevicePositionsPaginateTypeDef(
-    _RequiredListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-    _OptionalListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-):
-    pass
-
-ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef = TypedDict(
-    "ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
-    "_RequiredListGeofencesRequestListGeofencesPaginateTypeDef",
-    {
-        "CollectionName": str,
-    },
-)
-_OptionalListGeofencesRequestListGeofencesPaginateTypeDef = TypedDict(
-    "_OptionalListGeofencesRequestListGeofencesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGeofencesRequestListGeofencesPaginateTypeDef(
-    _RequiredListGeofencesRequestListGeofencesPaginateTypeDef,
-    _OptionalListGeofencesRequestListGeofencesPaginateTypeDef,
-):
-    pass
-
-ListMapsRequestListMapsPaginateTypeDef = TypedDict(
-    "ListMapsRequestListMapsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef = TypedDict(
-    "ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef = TypedDict(
-    "ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
-    "_RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    {
-        "TrackerName": str,
-    },
-)
-_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef = TypedDict(
-    "_OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef(
-    _RequiredListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-    _OptionalListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-):
-    pass
-
-ListTrackersRequestListTrackersPaginateTypeDef = TypedDict(
-    "ListTrackersRequestListTrackersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 _RequiredLegTypeDef = TypedDict(
     "_RequiredLegTypeDef",
     {
         "Distance": float,
         "DurationSeconds": float,
         "EndPosition": List[float],
@@ -1744,91 +2074,120 @@
     "_OptionalLegTypeDef",
     {
         "Geometry": LegGeometryTypeDef,
     },
     total=False,
 )
 
+
 class LegTypeDef(_RequiredLegTypeDef, _OptionalLegTypeDef):
     pass
 
+
 ListGeofenceCollectionsResponseTypeDef = TypedDict(
     "ListGeofenceCollectionsResponseTypeDef",
     {
         "Entries": List[ListGeofenceCollectionsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMapsResponseTypeDef = TypedDict(
     "ListMapsResponseTypeDef",
     {
         "Entries": List[ListMapsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlaceIndexesResponseTypeDef = TypedDict(
     "ListPlaceIndexesResponseTypeDef",
     {
         "Entries": List[ListPlaceIndexesResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRouteCalculatorsResponseTypeDef = TypedDict(
     "ListRouteCalculatorsResponseTypeDef",
     {
         "Entries": List[ListRouteCalculatorsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrackersResponseTypeDef = TypedDict(
     "ListTrackersResponseTypeDef",
     {
         "Entries": List[ListTrackersResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredUpdateMapRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateMapRequestRequestTypeDef",
+    {
+        "MapName": str,
+    },
+)
+_OptionalUpdateMapRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateMapRequestRequestTypeDef",
+    {
+        "ConfigurationUpdate": MapConfigurationUpdateTypeDef,
+        "Description": str,
+        "PricingPlan": PricingPlanType,
+    },
+    total=False,
+)
+
+
+class UpdateMapRequestRequestTypeDef(
+    _RequiredUpdateMapRequestRequestTypeDef, _OptionalUpdateMapRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredPlaceTypeDef = TypedDict(
     "_RequiredPlaceTypeDef",
     {
         "Geometry": PlaceGeometryTypeDef,
     },
 )
 _OptionalPlaceTypeDef = TypedDict(
     "_OptionalPlaceTypeDef",
     {
         "AddressNumber": str,
+        "Categories": List[str],
         "Country": str,
         "Interpolated": bool,
         "Label": str,
         "Municipality": str,
         "Neighborhood": str,
         "PostalCode": str,
         "Region": str,
         "Street": str,
         "SubRegion": str,
+        "SupplementalCategories": List[str],
         "TimeZone": TimeZoneTypeDef,
         "UnitNumber": str,
         "UnitType": str,
     },
     total=False,
 )
 
+
 class PlaceTypeDef(_RequiredPlaceTypeDef, _OptionalPlaceTypeDef):
     pass
 
+
 RouteMatrixEntryTypeDef = TypedDict(
     "RouteMatrixEntryTypeDef",
     {
         "Distance": float,
         "DurationSeconds": float,
         "Error": RouteMatrixEntryErrorTypeDef,
     },
@@ -1836,56 +2195,65 @@
 )
 
 SearchPlaceIndexForSuggestionsResponseTypeDef = TypedDict(
     "SearchPlaceIndexForSuggestionsResponseTypeDef",
     {
         "Results": List[SearchForSuggestionsResultTypeDef],
         "Summary": SearchPlaceIndexForSuggestionsSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListKeysResponseTypeDef = TypedDict(
+    "ListKeysResponseTypeDef",
+    {
+        "Entries": List[ListKeysResponseEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteDevicePositionHistoryResponseTypeDef = TypedDict(
     "BatchDeleteDevicePositionHistoryResponseTypeDef",
     {
         "Errors": List[BatchDeleteDevicePositionHistoryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteGeofenceResponseTypeDef = TypedDict(
     "BatchDeleteGeofenceResponseTypeDef",
     {
         "Errors": List[BatchDeleteGeofenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEvaluateGeofencesResponseTypeDef = TypedDict(
     "BatchEvaluateGeofencesResponseTypeDef",
     {
         "Errors": List[BatchEvaluateGeofencesErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutGeofenceResponseTypeDef = TypedDict(
     "BatchPutGeofenceResponseTypeDef",
     {
         "Errors": List[BatchPutGeofenceErrorTypeDef],
         "Successes": List[BatchPutGeofenceSuccessTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateDevicePositionResponseTypeDef = TypedDict(
     "BatchUpdateDevicePositionResponseTypeDef",
     {
         "Errors": List[BatchUpdateDevicePositionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCalculateRouteMatrixRequestRequestTypeDef = TypedDict(
     "_RequiredCalculateRouteMatrixRequestRequestTypeDef",
     {
         "CalculatorName": str,
@@ -1902,20 +2270,22 @@
         "DistanceUnit": DistanceUnitType,
         "TravelMode": TravelModeType,
         "TruckModeOptions": CalculateRouteTruckModeOptionsTypeDef,
     },
     total=False,
 )
 
+
 class CalculateRouteMatrixRequestRequestTypeDef(
     _RequiredCalculateRouteMatrixRequestRequestTypeDef,
     _OptionalCalculateRouteMatrixRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCalculateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCalculateRouteRequestRequestTypeDef",
     {
         "CalculatorName": str,
         "DeparturePosition": Sequence[float],
         "DestinationPosition": Sequence[float],
     },
@@ -1931,74 +2301,119 @@
         "TravelMode": TravelModeType,
         "TruckModeOptions": CalculateRouteTruckModeOptionsTypeDef,
         "WaypointPositions": Sequence[Sequence[float]],
     },
     total=False,
 )
 
+
 class CalculateRouteRequestRequestTypeDef(
     _RequiredCalculateRouteRequestRequestTypeDef, _OptionalCalculateRouteRequestRequestTypeDef
 ):
     pass
 
-BatchPutGeofenceRequestEntryTypeDef = TypedDict(
-    "BatchPutGeofenceRequestEntryTypeDef",
+
+_RequiredBatchPutGeofenceRequestEntryTypeDef = TypedDict(
+    "_RequiredBatchPutGeofenceRequestEntryTypeDef",
     {
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
     },
 )
+_OptionalBatchPutGeofenceRequestEntryTypeDef = TypedDict(
+    "_OptionalBatchPutGeofenceRequestEntryTypeDef",
+    {
+        "GeofenceProperties": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class BatchPutGeofenceRequestEntryTypeDef(
+    _RequiredBatchPutGeofenceRequestEntryTypeDef, _OptionalBatchPutGeofenceRequestEntryTypeDef
+):
+    pass
+
 
 GetGeofenceResponseTypeDef = TypedDict(
     "GetGeofenceResponseTypeDef",
     {
         "CreateTime": datetime,
         "GeofenceId": str,
+        "GeofenceProperties": Dict[str, str],
         "Geometry": GeofenceGeometryTypeDef,
         "Status": str,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListGeofenceResponseEntryTypeDef = TypedDict(
-    "ListGeofenceResponseEntryTypeDef",
+_RequiredListGeofenceResponseEntryTypeDef = TypedDict(
+    "_RequiredListGeofenceResponseEntryTypeDef",
     {
         "CreateTime": datetime,
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
         "Status": str,
         "UpdateTime": datetime,
     },
 )
+_OptionalListGeofenceResponseEntryTypeDef = TypedDict(
+    "_OptionalListGeofenceResponseEntryTypeDef",
+    {
+        "GeofenceProperties": Dict[str, str],
+    },
+    total=False,
+)
 
-PutGeofenceRequestRequestTypeDef = TypedDict(
-    "PutGeofenceRequestRequestTypeDef",
+
+class ListGeofenceResponseEntryTypeDef(
+    _RequiredListGeofenceResponseEntryTypeDef, _OptionalListGeofenceResponseEntryTypeDef
+):
+    pass
+
+
+_RequiredPutGeofenceRequestRequestTypeDef = TypedDict(
+    "_RequiredPutGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
         "GeofenceId": str,
         "Geometry": GeofenceGeometryTypeDef,
     },
 )
+_OptionalPutGeofenceRequestRequestTypeDef = TypedDict(
+    "_OptionalPutGeofenceRequestRequestTypeDef",
+    {
+        "GeofenceProperties": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class PutGeofenceRequestRequestTypeDef(
+    _RequiredPutGeofenceRequestRequestTypeDef, _OptionalPutGeofenceRequestRequestTypeDef
+):
+    pass
+
 
 BatchGetDevicePositionResponseTypeDef = TypedDict(
     "BatchGetDevicePositionResponseTypeDef",
     {
         "DevicePositions": List[DevicePositionTypeDef],
         "Errors": List[BatchGetDevicePositionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicePositionHistoryResponseTypeDef = TypedDict(
     "GetDevicePositionHistoryResponseTypeDef",
     {
         "DevicePositions": List[DevicePositionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEvaluateGeofencesRequestRequestTypeDef = TypedDict(
     "BatchEvaluateGeofencesRequestRequestTypeDef",
     {
         "CollectionName": str,
@@ -2015,32 +2430,32 @@
 )
 
 ListDevicePositionsResponseTypeDef = TypedDict(
     "ListDevicePositionsResponseTypeDef",
     {
         "Entries": List[ListDevicePositionsResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CalculateRouteResponseTypeDef = TypedDict(
     "CalculateRouteResponseTypeDef",
     {
         "Legs": List[LegTypeDef],
         "Summary": CalculateRouteSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPlaceResponseTypeDef = TypedDict(
     "GetPlaceResponseTypeDef",
     {
         "Place": PlaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchForPositionResultTypeDef = TypedDict(
     "_RequiredSearchForPositionResultTypeDef",
     {
         "Distance": float,
@@ -2051,19 +2466,21 @@
     "_OptionalSearchForPositionResultTypeDef",
     {
         "PlaceId": str,
     },
     total=False,
 )
 
+
 class SearchForPositionResultTypeDef(
     _RequiredSearchForPositionResultTypeDef, _OptionalSearchForPositionResultTypeDef
 ):
     pass
 
+
 _RequiredSearchForTextResultTypeDef = TypedDict(
     "_RequiredSearchForTextResultTypeDef",
     {
         "Place": PlaceTypeDef,
     },
 )
 _OptionalSearchForTextResultTypeDef = TypedDict(
@@ -2072,27 +2489,29 @@
         "Distance": float,
         "PlaceId": str,
         "Relevance": float,
     },
     total=False,
 )
 
+
 class SearchForTextResultTypeDef(
     _RequiredSearchForTextResultTypeDef, _OptionalSearchForTextResultTypeDef
 ):
     pass
 
+
 CalculateRouteMatrixResponseTypeDef = TypedDict(
     "CalculateRouteMatrixResponseTypeDef",
     {
         "RouteMatrix": List[List[RouteMatrixEntryTypeDef]],
         "SnappedDeparturePositions": List[List[float]],
         "SnappedDestinationPositions": List[List[float]],
         "Summary": CalculateRouteMatrixSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutGeofenceRequestRequestTypeDef = TypedDict(
     "BatchPutGeofenceRequestRequestTypeDef",
     {
         "CollectionName": str,
@@ -2101,28 +2520,28 @@
 )
 
 ListGeofencesResponseTypeDef = TypedDict(
     "ListGeofencesResponseTypeDef",
     {
         "Entries": List[ListGeofenceResponseEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchPlaceIndexForPositionResponseTypeDef = TypedDict(
     "SearchPlaceIndexForPositionResponseTypeDef",
     {
         "Results": List[SearchForPositionResultTypeDef],
         "Summary": SearchPlaceIndexForPositionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchPlaceIndexForTextResponseTypeDef = TypedDict(
     "SearchPlaceIndexForTextResponseTypeDef",
     {
         "Results": List[SearchForTextResultTypeDef],
         "Summary": SearchPlaceIndexForTextSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/PKG-INFO` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-location
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LocationService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LocationService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-location"></a>
 
 # types-aiobotocore-location
 
 [![PyPI - types-aiobotocore-location](https://img.shields.io/pypi/v/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-location.svg?color=blue)](https://pypi.org/project/types-aiobotocore-location)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-location?color=blue)](https://pypistats.org/packages/types-aiobotocore-location)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LocationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
+[aiobotocore.LocationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/location.html#LocationService)
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
 [types-aiobotocore-location docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_location/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,14 +277,15 @@
 
 from types_aiobotocore_location import LocationServiceClient
 from types_aiobotocore_location.paginator import (
     GetDevicePositionHistoryPaginator,
     ListDevicePositionsPaginator,
     ListGeofenceCollectionsPaginator,
     ListGeofencesPaginator,
+    ListKeysPaginator,
     ListMapsPaginator,
     ListPlaceIndexesPaginator,
     ListRouteCalculatorsPaginator,
     ListTrackerConsumersPaginator,
     ListTrackersPaginator,
 )
 
@@ -300,14 +301,15 @@
     list_device_positions_paginator: ListDevicePositionsPaginator = client.get_paginator(
         "list_device_positions"
     )
     list_geofence_collections_paginator: ListGeofenceCollectionsPaginator = client.get_paginator(
         "list_geofence_collections"
     )
     list_geofences_paginator: ListGeofencesPaginator = client.get_paginator("list_geofences")
+    list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
     list_maps_paginator: ListMapsPaginator = client.get_paginator("list_maps")
     list_place_indexes_paginator: ListPlaceIndexesPaginator = client.get_paginator(
         "list_place_indexes"
     )
     list_route_calculators_paginator: ListRouteCalculatorsPaginator = client.get_paginator(
         "list_route_calculators"
     )
@@ -330,22 +332,24 @@
     DimensionUnitType,
     DistanceUnitType,
     GetDevicePositionHistoryPaginatorName,
     IntendedUseType,
     ListDevicePositionsPaginatorName,
     ListGeofenceCollectionsPaginatorName,
     ListGeofencesPaginatorName,
+    ListKeysPaginatorName,
     ListMapsPaginatorName,
     ListPlaceIndexesPaginatorName,
     ListRouteCalculatorsPaginatorName,
     ListTrackerConsumersPaginatorName,
     ListTrackersPaginatorName,
     PositionFilteringType,
     PricingPlanType,
     RouteMatrixErrorCodeType,
+    StatusType,
     TravelModeType,
     VehicleWeightUnitType,
     LocationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -361,140 +365,154 @@
 ### Typed dictionaries
 
 `types_aiobotocore_location.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_location.type_defs import (
+    ApiKeyFilterTypeDef,
+    ApiKeyRestrictionsTypeDef,
     AssociateTrackerConsumerRequestRequestTypeDef,
     BatchItemErrorTypeDef,
     BatchDeleteDevicePositionHistoryRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteGeofenceRequestRequestTypeDef,
     BatchGetDevicePositionRequestRequestTypeDef,
     BatchPutGeofenceSuccessTypeDef,
     CalculateRouteCarModeOptionsTypeDef,
     CalculateRouteMatrixSummaryTypeDef,
     CalculateRouteSummaryTypeDef,
     TruckDimensionsTypeDef,
     TruckWeightTypeDef,
     CircleTypeDef,
     CreateGeofenceCollectionRequestRequestTypeDef,
+    CreateGeofenceCollectionResponseTypeDef,
+    CreateKeyResponseTypeDef,
     MapConfigurationTypeDef,
+    CreateMapResponseTypeDef,
     DataSourceConfigurationTypeDef,
+    CreatePlaceIndexResponseTypeDef,
     CreateRouteCalculatorRequestRequestTypeDef,
+    CreateRouteCalculatorResponseTypeDef,
     CreateTrackerRequestRequestTypeDef,
+    CreateTrackerResponseTypeDef,
     DeleteGeofenceCollectionRequestRequestTypeDef,
+    DeleteKeyRequestRequestTypeDef,
     DeleteMapRequestRequestTypeDef,
     DeletePlaceIndexRequestRequestTypeDef,
     DeleteRouteCalculatorRequestRequestTypeDef,
     DeleteTrackerRequestRequestTypeDef,
     DescribeGeofenceCollectionRequestRequestTypeDef,
+    DescribeGeofenceCollectionResponseTypeDef,
+    DescribeKeyRequestRequestTypeDef,
     DescribeMapRequestRequestTypeDef,
     DescribePlaceIndexRequestRequestTypeDef,
     DescribeRouteCalculatorRequestRequestTypeDef,
+    DescribeRouteCalculatorResponseTypeDef,
     DescribeTrackerRequestRequestTypeDef,
+    DescribeTrackerResponseTypeDef,
     PositionalAccuracyTypeDef,
     DisassociateTrackerConsumerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
     GetDevicePositionHistoryRequestRequestTypeDef,
     GetDevicePositionRequestRequestTypeDef,
     GetGeofenceRequestRequestTypeDef,
     GetMapGlyphsRequestRequestTypeDef,
+    GetMapGlyphsResponseTypeDef,
     GetMapSpritesRequestRequestTypeDef,
+    GetMapSpritesResponseTypeDef,
     GetMapStyleDescriptorRequestRequestTypeDef,
+    GetMapStyleDescriptorResponseTypeDef,
     GetMapTileRequestRequestTypeDef,
+    GetMapTileResponseTypeDef,
     GetPlaceRequestRequestTypeDef,
     LegGeometryTypeDef,
     StepTypeDef,
+    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
     ListDevicePositionsRequestRequestTypeDef,
+    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
     ListGeofenceCollectionsRequestRequestTypeDef,
     ListGeofenceCollectionsResponseEntryTypeDef,
+    ListGeofencesRequestListGeofencesPaginateTypeDef,
     ListGeofencesRequestRequestTypeDef,
+    ListMapsRequestListMapsPaginateTypeDef,
     ListMapsRequestRequestTypeDef,
     ListMapsResponseEntryTypeDef,
+    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
     ListPlaceIndexesRequestRequestTypeDef,
     ListPlaceIndexesResponseEntryTypeDef,
+    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
     ListRouteCalculatorsRequestRequestTypeDef,
     ListRouteCalculatorsResponseEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
     ListTrackerConsumersRequestRequestTypeDef,
+    ListTrackerConsumersResponseTypeDef,
+    ListTrackersRequestListTrackersPaginateTypeDef,
     ListTrackersRequestRequestTypeDef,
     ListTrackersResponseEntryTypeDef,
+    MapConfigurationUpdateTypeDef,
+    PaginatorConfigTypeDef,
     PlaceGeometryTypeDef,
     TimeZoneTypeDef,
+    PutGeofenceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RouteMatrixEntryErrorTypeDef,
     SearchForSuggestionsResultTypeDef,
     SearchPlaceIndexForPositionRequestRequestTypeDef,
     SearchPlaceIndexForPositionSummaryTypeDef,
     SearchPlaceIndexForSuggestionsRequestRequestTypeDef,
     SearchPlaceIndexForSuggestionsSummaryTypeDef,
     SearchPlaceIndexForTextRequestRequestTypeDef,
     SearchPlaceIndexForTextSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGeofenceCollectionRequestRequestTypeDef,
-    UpdateMapRequestRequestTypeDef,
+    UpdateGeofenceCollectionResponseTypeDef,
+    UpdateKeyResponseTypeDef,
+    UpdateMapResponseTypeDef,
+    UpdatePlaceIndexResponseTypeDef,
     UpdateRouteCalculatorRequestRequestTypeDef,
+    UpdateRouteCalculatorResponseTypeDef,
     UpdateTrackerRequestRequestTypeDef,
+    UpdateTrackerResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
+    ListKeysRequestRequestTypeDef,
+    CreateKeyRequestRequestTypeDef,
+    DescribeKeyResponseTypeDef,
+    ListKeysResponseEntryTypeDef,
+    UpdateKeyRequestRequestTypeDef,
     BatchDeleteDevicePositionHistoryErrorTypeDef,
     BatchDeleteGeofenceErrorTypeDef,
     BatchEvaluateGeofencesErrorTypeDef,
     BatchGetDevicePositionErrorTypeDef,
     BatchPutGeofenceErrorTypeDef,
     BatchUpdateDevicePositionErrorTypeDef,
-    CreateGeofenceCollectionResponseTypeDef,
-    CreateMapResponseTypeDef,
-    CreatePlaceIndexResponseTypeDef,
-    CreateRouteCalculatorResponseTypeDef,
-    CreateTrackerResponseTypeDef,
-    DescribeGeofenceCollectionResponseTypeDef,
-    DescribeRouteCalculatorResponseTypeDef,
-    DescribeTrackerResponseTypeDef,
-    GetMapGlyphsResponseTypeDef,
-    GetMapSpritesResponseTypeDef,
-    GetMapStyleDescriptorResponseTypeDef,
-    GetMapTileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTrackerConsumersResponseTypeDef,
-    PutGeofenceResponseTypeDef,
-    UpdateGeofenceCollectionResponseTypeDef,
-    UpdateMapResponseTypeDef,
-    UpdatePlaceIndexResponseTypeDef,
-    UpdateRouteCalculatorResponseTypeDef,
-    UpdateTrackerResponseTypeDef,
     CalculateRouteTruckModeOptionsTypeDef,
     GeofenceGeometryTypeDef,
     CreateMapRequestRequestTypeDef,
     DescribeMapResponseTypeDef,
     CreatePlaceIndexRequestRequestTypeDef,
     DescribePlaceIndexResponseTypeDef,
     UpdatePlaceIndexRequestRequestTypeDef,
     DevicePositionTypeDef,
     DevicePositionUpdateTypeDef,
     GetDevicePositionResponseTypeDef,
     ListDevicePositionsResponseEntryTypeDef,
-    GetDevicePositionHistoryRequestGetDevicePositionHistoryPaginateTypeDef,
-    ListDevicePositionsRequestListDevicePositionsPaginateTypeDef,
-    ListGeofenceCollectionsRequestListGeofenceCollectionsPaginateTypeDef,
-    ListGeofencesRequestListGeofencesPaginateTypeDef,
-    ListMapsRequestListMapsPaginateTypeDef,
-    ListPlaceIndexesRequestListPlaceIndexesPaginateTypeDef,
-    ListRouteCalculatorsRequestListRouteCalculatorsPaginateTypeDef,
-    ListTrackerConsumersRequestListTrackerConsumersPaginateTypeDef,
-    ListTrackersRequestListTrackersPaginateTypeDef,
     LegTypeDef,
     ListGeofenceCollectionsResponseTypeDef,
     ListMapsResponseTypeDef,
     ListPlaceIndexesResponseTypeDef,
     ListRouteCalculatorsResponseTypeDef,
     ListTrackersResponseTypeDef,
+    UpdateMapRequestRequestTypeDef,
     PlaceTypeDef,
     RouteMatrixEntryTypeDef,
     SearchPlaceIndexForSuggestionsResponseTypeDef,
+    ListKeysResponseTypeDef,
     BatchDeleteDevicePositionHistoryResponseTypeDef,
     BatchDeleteGeofenceResponseTypeDef,
     BatchEvaluateGeofencesResponseTypeDef,
     BatchPutGeofenceResponseTypeDef,
     BatchUpdateDevicePositionResponseTypeDef,
     CalculateRouteMatrixRequestRequestTypeDef,
     CalculateRouteRequestRequestTypeDef,
@@ -515,54 +533,54 @@
     BatchPutGeofenceRequestRequestTypeDef,
     ListGeofencesResponseTypeDef,
     SearchPlaceIndexForPositionResponseTypeDef,
     SearchPlaceIndexForTextResponseTypeDef,
 )
 
 
-def get_structure() -> AssociateTrackerConsumerRequestRequestTypeDef:
+def get_structure() -> ApiKeyFilterTypeDef:
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

### Comparing `types-aiobotocore-location-2.5.0.post1/types_aiobotocore_location.egg-info/SOURCES.txt` & `types-aiobotocore-location-2.5.1/types_aiobotocore_location.egg-info/SOURCES.txt`

 * *Files identical despite different names*

