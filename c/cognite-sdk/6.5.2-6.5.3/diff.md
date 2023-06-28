# Comparing `tmp/cognite_sdk-6.5.2.tar.gz` & `tmp/cognite_sdk-6.5.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cognite_sdk-6.5.2.tar", max compression
+gzip compressed data, was "cognite_sdk-6.5.3.tar", max compression
```

## Comparing `cognite_sdk-6.5.2.tar` & `cognite_sdk-6.5.3.tar`

### file list

```diff
@@ -1,115 +1,115 @@
--rw-r--r--   0        0        0    11349 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/LICENSE
--rw-r--r--   0        0        0     3945 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/README.md
--rw-r--r--   0        0        0      574 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/__init__.py
--rw-r--r--   0        0        0        0 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/__init__.py
--rw-r--r--   0        0        0     7558 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/annotations.py
--rw-r--r--   0        0        0    49210 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/assets.py
--rw-r--r--   0        0        0     1157 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/__init__.py
--rw-r--r--   0        0        0     8056 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/containers.py
--rw-r--r--   0        0        0     8429 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/data_models.py
--rw-r--r--   0        0        0    37850 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/instances.py
--rw-r--r--   0        0        0     6503 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/spaces.py
--rw-r--r--   0        0        0     7897 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_modeling/views.py
--rw-r--r--   0        0        0    11115 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/data_sets.py
--rw-r--r--   0        0        0    54681 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/datapoint_tasks.py
--rw-r--r--   0        0        0    87544 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/datapoints.py
--rw-r--r--   0        0        0    12424 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/diagrams.py
--rw-r--r--   0        0        0    12245 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/entity_matching.py
--rw-r--r--   0        0        0    21384 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/events.py
--rw-r--r--   0        0        0    17504 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/extractionpipelines.py
--rw-r--r--   0        0        0    41584 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/files.py
--rw-r--r--   0        0        0    45636 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/functions.py
--rw-r--r--   0        0        0    50175 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/geospatial.py
--rw-r--r--   0        0        0     9619 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/iam.py
--rw-r--r--   0        0        0     6088 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/labels.py
--rw-r--r--   0        0        0    24756 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/raw.py
--rw-r--r--   0        0        0    22919 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/relationships.py
--rw-r--r--   0        0        0    38200 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/sequences.py
--rw-r--r--   0        0        0     7936 2023-06-27 15:18:33.819772 cognite_sdk-6.5.2/cognite/client/_api/synthetic_time_series.py
--rw-r--r--   0        0        0    32072 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/templates.py
--rw-r--r--   0        0        0    28258 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/three_d.py
--rw-r--r--   0        0        0    19276 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/time_series.py
--rw-r--r--   0        0        0    22021 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/transformations/__init__.py
--rw-r--r--   0        0        0     5083 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/transformations/jobs.py
--rw-r--r--   0        0        0     4691 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/transformations/notifications.py
--rw-r--r--   0        0        0     9705 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/transformations/schedules.py
--rw-r--r--   0        0        0     1881 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/transformations/schema.py
--rw-r--r--   0        0        0     5910 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api/vision.py
--rw-r--r--   0        0        0    38099 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_api_client.py
--rw-r--r--   0        0        0     5391 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_cognite_client.py
--rw-r--r--   0        0        0      215 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_constants.py
--rw-r--r--   0        0        0     6937 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_http_client.py
--rw-r--r--   0        0        0      553 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response.proto
--rw-r--r--   0        0        0     1985 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response_pb2.py
--rw-r--r--   0        0        0     3364 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response_pb2.pyi
--rw-r--r--   0        0        0      811 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_points.proto
--rw-r--r--   0        0        0     2495 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_points_pb2.py
--rw-r--r--   0        0        0     5321 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto/data_points_pb2.pyi
--rw-r--r--   0        0        0     9509 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_point_list_response_pb2.py
--rw-r--r--   0        0        0     3364 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi
--rw-r--r--   0        0        0    15421 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_points_pb2.py
--rw-r--r--   0        0        0     5321 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_points_pb2.pyi
--rw-r--r--   0        0        0       91 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/_version.py
--rw-r--r--   0        0        0      300 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/beta.py
--rw-r--r--   0        0        0     4508 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/config.py
--rw-r--r--   0        0        0    19252 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/credentials.py
--rw-r--r--   0        0        0     8794 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/__init__.py
--rw-r--r--   0        0        0    19074 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/_base.py
--rw-r--r--   0        0        0        0 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/annotation_types/__init__.py
--rw-r--r--   0        0        0     1595 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/annotation_types/images.py
--rw-r--r--   0        0        0     2936 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/annotation_types/primitives.py
--rw-r--r--   0        0        0     8753 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/annotations.py
--rw-r--r--   0        0        0    34185 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/assets.py
--rw-r--r--   0        0        0    33708 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/contextualization.py
--rw-r--r--   0        0        0     4087 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/__init__.py
--rw-r--r--   0        0        0     1224 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/_core.py
--rw-r--r--   0        0        0     1239 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/_validation.py
--rw-r--r--   0        0        0     5154 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/aggregations.py
--rw-r--r--   0        0        0    11348 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/containers.py
--rw-r--r--   0        0        0     7395 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/data_models.py
--rw-r--r--   0        0        0     4710 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/data_types.py
--rw-r--r--   0        0        0     9519 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/filters.py
--rw-r--r--   0        0        0     6593 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/ids.py
--rw-r--r--   0        0        0    30982 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/instances.py
--rw-r--r--   0        0        0     2582 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/spaces.py
--rw-r--r--   0        0        0    15081 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/views.py
--rw-r--r--   0        0        0     6691 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/data_sets.py
--rw-r--r--   0        0        0    33969 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/datapoints.py
--rw-r--r--   0        0        0    11015 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/events.py
--rw-r--r--   0        0        0    14376 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/extractionpipelines.py
--rw-r--r--   0        0        0    13671 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/files.py
--rw-r--r--   0        0        0    16695 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/functions.py
--rw-r--r--   0        0        0    16556 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/geospatial.py
--rw-r--r--   0        0        0     6349 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/iam.py
--rw-r--r--   0        0        0     5885 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/labels.py
--rw-r--r--   0        0        0     4120 2023-06-27 15:18:33.823772 cognite_sdk-6.5.2/cognite/client/data_classes/raw.py
--rw-r--r--   0        0        0    12267 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/relationships.py
--rw-r--r--   0        0        0    17675 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/sequences.py
--rw-r--r--   0        0        0     8699 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/shared.py
--rw-r--r--   0        0        0    16892 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/templates.py
--rw-r--r--   0        0        0    11855 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/three_d.py
--rw-r--r--   0        0        0    12090 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/time_series.py
--rw-r--r--   0        0        0    23040 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/__init__.py
--rw-r--r--   0        0        0    12116 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/common.py
--rw-r--r--   0        0        0    11469 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/jobs.py
--rw-r--r--   0        0        0     2382 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/notifications.py
--rw-r--r--   0        0        0     2475 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/schedules.py
--rw-r--r--   0        0        0     2770 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/data_classes/transformations/schema.py
--rw-r--r--   0        0        0     9383 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/exceptions.py
--rw-r--r--   0        0        0        0 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/py.typed
--rw-r--r--   0        0        0     9006 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/testing.py
--rw-r--r--   0        0        0      534 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/__init__.py
--rw-r--r--   0        0        0     8165 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_auxiliary.py
--rw-r--r--   0        0        0     9853 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_concurrency.py
--rw-r--r--   0        0        0     1396 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_graph.py
--rw-r--r--   0        0        0     7684 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_identifier.py
--rw-r--r--   0        0        0     2134 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_logging.py
--rw-r--r--   0        0        0     3548 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_pandas_helpers.py
--rw-r--r--   0        0        0     6188 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_priority_tpe.py
--rw-r--r--   0        0        0     4260 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_pyodide_helpers.py
--rw-r--r--   0        0        0     2981 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_text.py
--rw-r--r--   0        0        0    24536 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_time.py
--rw-r--r--   0        0        0     1820 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_validation.py
--rw-r--r--   0        0        0     3341 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/cognite/client/utils/_version_checker.py
--rw-r--r--   0        0        0     2151 2023-06-27 15:18:33.827772 cognite_sdk-6.5.2/pyproject.toml
--rw-r--r--   0        0        0     5625 1970-01-01 00:00:00.000000 cognite_sdk-6.5.2/PKG-INFO
+-rw-r--r--   0        0        0    11349 2023-06-28 06:53:27.240192 cognite_sdk-6.5.3/LICENSE
+-rw-r--r--   0        0        0     3945 2023-06-28 06:53:27.240192 cognite_sdk-6.5.3/README.md
+-rw-r--r--   0        0        0      574 2023-06-28 06:53:27.240192 cognite_sdk-6.5.3/cognite/client/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:53:27.240192 cognite_sdk-6.5.3/cognite/client/_api/__init__.py
+-rw-r--r--   0        0        0     7558 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/annotations.py
+-rw-r--r--   0        0        0    49210 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/assets.py
+-rw-r--r--   0        0        0     1157 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/__init__.py
+-rw-r--r--   0        0        0     8056 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/containers.py
+-rw-r--r--   0        0        0     8429 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/data_models.py
+-rw-r--r--   0        0        0    37850 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/instances.py
+-rw-r--r--   0        0        0     6503 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/spaces.py
+-rw-r--r--   0        0        0     7897 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_modeling/views.py
+-rw-r--r--   0        0        0    11115 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/data_sets.py
+-rw-r--r--   0        0        0    54681 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/datapoint_tasks.py
+-rw-r--r--   0        0        0    87544 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/datapoints.py
+-rw-r--r--   0        0        0    12424 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/diagrams.py
+-rw-r--r--   0        0        0    12245 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/entity_matching.py
+-rw-r--r--   0        0        0    21384 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/events.py
+-rw-r--r--   0        0        0    17504 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/extractionpipelines.py
+-rw-r--r--   0        0        0    41584 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/files.py
+-rw-r--r--   0        0        0    45636 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/functions.py
+-rw-r--r--   0        0        0    50175 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/geospatial.py
+-rw-r--r--   0        0        0     9619 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/iam.py
+-rw-r--r--   0        0        0     6088 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/labels.py
+-rw-r--r--   0        0        0    24756 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/raw.py
+-rw-r--r--   0        0        0    22919 2023-06-28 06:53:27.244192 cognite_sdk-6.5.3/cognite/client/_api/relationships.py
+-rw-r--r--   0        0        0    38200 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/sequences.py
+-rw-r--r--   0        0        0     7936 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/synthetic_time_series.py
+-rw-r--r--   0        0        0    32072 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/templates.py
+-rw-r--r--   0        0        0    28258 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/three_d.py
+-rw-r--r--   0        0        0    19276 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/time_series.py
+-rw-r--r--   0        0        0    22021 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/transformations/__init__.py
+-rw-r--r--   0        0        0     5083 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/transformations/jobs.py
+-rw-r--r--   0        0        0     4691 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/transformations/notifications.py
+-rw-r--r--   0        0        0     9705 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/transformations/schedules.py
+-rw-r--r--   0        0        0     1881 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/transformations/schema.py
+-rw-r--r--   0        0        0     5910 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api/vision.py
+-rw-r--r--   0        0        0    38099 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_api_client.py
+-rw-r--r--   0        0        0     5391 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_cognite_client.py
+-rw-r--r--   0        0        0      215 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_constants.py
+-rw-r--r--   0        0        0     6937 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_http_client.py
+-rw-r--r--   0        0        0      553 2023-06-28 06:53:27.248192 cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response.proto
+-rw-r--r--   0        0        0     1985 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response_pb2.py
+-rw-r--r--   0        0        0     3364 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response_pb2.pyi
+-rw-r--r--   0        0        0      811 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto/data_points.proto
+-rw-r--r--   0        0        0     2495 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto/data_points_pb2.py
+-rw-r--r--   0        0        0     5321 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto/data_points_pb2.pyi
+-rw-r--r--   0        0        0     9509 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_point_list_response_pb2.py
+-rw-r--r--   0        0        0     3364 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi
+-rw-r--r--   0        0        0    15421 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_points_pb2.py
+-rw-r--r--   0        0        0     5321 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_points_pb2.pyi
+-rw-r--r--   0        0        0       91 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/_version.py
+-rw-r--r--   0        0        0      300 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/beta.py
+-rw-r--r--   0        0        0     4508 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/config.py
+-rw-r--r--   0        0        0    19252 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/credentials.py
+-rw-r--r--   0        0        0     8794 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/__init__.py
+-rw-r--r--   0        0        0    19074 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/_base.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/annotation_types/__init__.py
+-rw-r--r--   0        0        0     1595 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/annotation_types/images.py
+-rw-r--r--   0        0        0     2936 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/annotation_types/primitives.py
+-rw-r--r--   0        0        0     8753 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/annotations.py
+-rw-r--r--   0        0        0    34185 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/assets.py
+-rw-r--r--   0        0        0    33708 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/contextualization.py
+-rw-r--r--   0        0        0     4087 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/__init__.py
+-rw-r--r--   0        0        0     1224 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/_core.py
+-rw-r--r--   0        0        0     1239 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/_validation.py
+-rw-r--r--   0        0        0     5154 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/aggregations.py
+-rw-r--r--   0        0        0    11348 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/containers.py
+-rw-r--r--   0        0        0     7395 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/data_models.py
+-rw-r--r--   0        0        0     4710 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/data_types.py
+-rw-r--r--   0        0        0     9519 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/filters.py
+-rw-r--r--   0        0        0     6593 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/ids.py
+-rw-r--r--   0        0        0    30982 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/instances.py
+-rw-r--r--   0        0        0     2944 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/spaces.py
+-rw-r--r--   0        0        0    15081 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/views.py
+-rw-r--r--   0        0        0     6691 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/data_sets.py
+-rw-r--r--   0        0        0    33969 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/datapoints.py
+-rw-r--r--   0        0        0    11015 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/events.py
+-rw-r--r--   0        0        0    14376 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/extractionpipelines.py
+-rw-r--r--   0        0        0    13671 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/files.py
+-rw-r--r--   0        0        0    16695 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/functions.py
+-rw-r--r--   0        0        0    16556 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/geospatial.py
+-rw-r--r--   0        0        0     6349 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/iam.py
+-rw-r--r--   0        0        0     5885 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/labels.py
+-rw-r--r--   0        0        0     4120 2023-06-28 06:53:27.252192 cognite_sdk-6.5.3/cognite/client/data_classes/raw.py
+-rw-r--r--   0        0        0    12267 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/relationships.py
+-rw-r--r--   0        0        0    17675 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/sequences.py
+-rw-r--r--   0        0        0     8699 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/shared.py
+-rw-r--r--   0        0        0    16892 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/templates.py
+-rw-r--r--   0        0        0    11855 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/three_d.py
+-rw-r--r--   0        0        0    12090 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/time_series.py
+-rw-r--r--   0        0        0    23040 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/__init__.py
+-rw-r--r--   0        0        0    12116 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/common.py
+-rw-r--r--   0        0        0    11469 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/jobs.py
+-rw-r--r--   0        0        0     2382 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/notifications.py
+-rw-r--r--   0        0        0     2475 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/schedules.py
+-rw-r--r--   0        0        0     2770 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/data_classes/transformations/schema.py
+-rw-r--r--   0        0        0     9383 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/exceptions.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/py.typed
+-rw-r--r--   0        0        0     9006 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/testing.py
+-rw-r--r--   0        0        0      534 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/__init__.py
+-rw-r--r--   0        0        0     8165 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_auxiliary.py
+-rw-r--r--   0        0        0     9853 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_concurrency.py
+-rw-r--r--   0        0        0     1396 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_graph.py
+-rw-r--r--   0        0        0     7684 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_identifier.py
+-rw-r--r--   0        0        0     2134 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_logging.py
+-rw-r--r--   0        0        0     3548 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_pandas_helpers.py
+-rw-r--r--   0        0        0     6188 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_priority_tpe.py
+-rw-r--r--   0        0        0     4260 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_pyodide_helpers.py
+-rw-r--r--   0        0        0     2981 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_text.py
+-rw-r--r--   0        0        0    24536 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_time.py
+-rw-r--r--   0        0        0     1820 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_validation.py
+-rw-r--r--   0        0        0     3341 2023-06-28 06:53:27.256192 cognite_sdk-6.5.3/cognite/client/utils/_version_checker.py
+-rw-r--r--   0        0        0     2151 2023-06-28 06:53:27.260192 cognite_sdk-6.5.3/pyproject.toml
+-rw-r--r--   0        0        0     5625 1970-01-01 00:00:00.000000 cognite_sdk-6.5.3/PKG-INFO
```

### Comparing `cognite_sdk-6.5.2/LICENSE` & `cognite_sdk-6.5.3/LICENSE`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/README.md` & `cognite_sdk-6.5.3/README.md`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/__init__.py` & `cognite_sdk-6.5.3/cognite/client/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/annotations.py` & `cognite_sdk-6.5.3/cognite/client/_api/annotations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/assets.py` & `cognite_sdk-6.5.3/cognite/client/_api/assets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/__init__.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/containers.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/containers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/data_models.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/data_models.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/instances.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/instances.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/spaces.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/spaces.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_modeling/views.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_modeling/views.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/data_sets.py` & `cognite_sdk-6.5.3/cognite/client/_api/data_sets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/datapoint_tasks.py` & `cognite_sdk-6.5.3/cognite/client/_api/datapoint_tasks.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/datapoints.py` & `cognite_sdk-6.5.3/cognite/client/_api/datapoints.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/diagrams.py` & `cognite_sdk-6.5.3/cognite/client/_api/diagrams.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/entity_matching.py` & `cognite_sdk-6.5.3/cognite/client/_api/entity_matching.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/events.py` & `cognite_sdk-6.5.3/cognite/client/_api/events.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/extractionpipelines.py` & `cognite_sdk-6.5.3/cognite/client/_api/extractionpipelines.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/files.py` & `cognite_sdk-6.5.3/cognite/client/_api/files.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/functions.py` & `cognite_sdk-6.5.3/cognite/client/_api/functions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/geospatial.py` & `cognite_sdk-6.5.3/cognite/client/_api/geospatial.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/iam.py` & `cognite_sdk-6.5.3/cognite/client/_api/iam.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/labels.py` & `cognite_sdk-6.5.3/cognite/client/_api/labels.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/raw.py` & `cognite_sdk-6.5.3/cognite/client/_api/raw.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/relationships.py` & `cognite_sdk-6.5.3/cognite/client/_api/relationships.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/sequences.py` & `cognite_sdk-6.5.3/cognite/client/_api/sequences.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/synthetic_time_series.py` & `cognite_sdk-6.5.3/cognite/client/_api/synthetic_time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/templates.py` & `cognite_sdk-6.5.3/cognite/client/_api/templates.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/three_d.py` & `cognite_sdk-6.5.3/cognite/client/_api/three_d.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/time_series.py` & `cognite_sdk-6.5.3/cognite/client/_api/time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/transformations/__init__.py` & `cognite_sdk-6.5.3/cognite/client/_api/transformations/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/transformations/jobs.py` & `cognite_sdk-6.5.3/cognite/client/_api/transformations/jobs.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/transformations/notifications.py` & `cognite_sdk-6.5.3/cognite/client/_api/transformations/notifications.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/transformations/schedules.py` & `cognite_sdk-6.5.3/cognite/client/_api/transformations/schedules.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/transformations/schema.py` & `cognite_sdk-6.5.3/cognite/client/_api/transformations/schema.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api/vision.py` & `cognite_sdk-6.5.3/cognite/client/_api/vision.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_api_client.py` & `cognite_sdk-6.5.3/cognite/client/_api_client.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_cognite_client.py` & `cognite_sdk-6.5.3/cognite/client/_cognite_client.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_http_client.py` & `cognite_sdk-6.5.3/cognite/client/_http_client.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response.proto` & `cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response.proto`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response_pb2.py` & `cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_point_list_response_pb2.pyi` & `cognite_sdk-6.5.3/cognite/client/_proto/data_point_list_response_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_points.proto` & `cognite_sdk-6.5.3/cognite/client/_proto/data_points.proto`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_points_pb2.py` & `cognite_sdk-6.5.3/cognite/client/_proto/data_points_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto/data_points_pb2.pyi` & `cognite_sdk-6.5.3/cognite/client/_proto/data_points_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_point_list_response_pb2.py` & `cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_point_list_response_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi` & `cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_points_pb2.py` & `cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_points_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/_proto_legacy/data_points_pb2.pyi` & `cognite_sdk-6.5.3/cognite/client/_proto_legacy/data_points_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/config.py` & `cognite_sdk-6.5.3/cognite/client/config.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/credentials.py` & `cognite_sdk-6.5.3/cognite/client/credentials.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/__init__.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/_base.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/_base.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/annotation_types/images.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/annotation_types/images.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/annotation_types/primitives.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/annotation_types/primitives.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/annotations.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/annotations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/assets.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/assets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/contextualization.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/contextualization.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/__init__.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/_core.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/_core.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/_validation.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/_validation.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/aggregations.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/aggregations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/containers.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/containers.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -42,15 +42,14 @@
         description: str = None,
         name: str = None,
         used_for: Literal["node", "edge", "all"] = None,
         constraints: dict[str, Constraint] = None,
         indexes: dict[str, Index] = None,
         **_: dict,
     ):
-        validate_data_modeling_identifier(space, external_id)
         self.space = space
         self.external_id = external_id
         self.description = description
         self.name = name
         self.used_for = used_for
         self.properties = properties
         self.constraints = constraints
@@ -103,14 +102,15 @@
         properties: dict[str, ContainerProperty],
         description: str = None,
         name: str = None,
         used_for: Literal["node", "edge", "all"] = None,
         constraints: dict[str, Constraint] = None,
         indexes: dict[str, Index] = None,
     ):
+        validate_data_modeling_identifier(space, external_id)
         super().__init__(space, external_id, properties, description, name, used_for, constraints, indexes)
 
 
 class Container(ContainerCore):
     """Represent the physical storage of data. This is the read format of the container
 
     Args:
```

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/data_models.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/data_models.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -29,15 +29,14 @@
         space: str,
         external_id: str,
         version: str,
         description: str = None,
         name: str = None,
         **_: dict,
     ):
-        validate_data_modeling_identifier(space, external_id)
         self.space = space
         self.external_id = external_id
         self.description = description
         self.name = name
         self.version = version
 
     def as_id(self) -> DataModelId:
@@ -61,14 +60,15 @@
         space: str,
         external_id: str,
         version: str,
         description: str = None,
         name: str = None,
         views: list[ViewId | ViewApply] = None,
     ):
+        validate_data_modeling_identifier(space, external_id)
         super().__init__(space, external_id, version, description, name)
         self.views = views
 
     @classmethod
     def _load_view(cls, view_data: dict) -> ViewId | ViewApply:
         if "type" in view_data:
             return ViewId.load(view_data)
```

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/data_types.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/data_types.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/filters.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/filters.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/ids.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/ids.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/instances.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/instances.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -82,15 +82,14 @@
     Args:
         instance_type (Literal["node", "edge"]) The type of instance.
         space (str): The workspace for the instance.a unique identifier for the space.
         external_id (str): Combined with the space is the unique identifier of the instance.
     """
 
     def __init__(self, space: str, external_id: str, instance_type: Literal["node", "edge"] = "node"):
-        validate_data_modeling_identifier(space, external_id)
         self.instance_type = instance_type
         self.space = space
         self.external_id = external_id
 
 
 class InstanceApply(InstanceCore):
     """A node or edge. This is the write version of the instance.
@@ -113,14 +112,15 @@
         self,
         space: str,
         external_id: str,
         instance_type: Literal["node", "edge"] = "node",
         existing_version: int = None,
         sources: list[NodeOrEdgeData] = None,
     ):
+        validate_data_modeling_identifier(space, external_id)
         super().__init__(space, external_id, instance_type)
         self.existing_version = existing_version
         self.sources = sources
 
     def dump(self, camel_case: bool = False) -> dict[str, Any]:
         output = super().dump(camel_case)
         if self.sources:
```

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/spaces.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/spaces.py`

 * *Files 7% similar despite different names*

```diff
@@ -15,27 +15,40 @@
     Args:
         space (str): A unique identifier for space.
         description (str): Textual description of the space
         name (str): Human readable name for the space.
     """
 
     def __init__(self, space: str, description: str = None, name: str = None):
-        validate_data_modeling_identifier(space)
         self.space = space
         self.description = description
         self.name = name
 
     def as_id(self) -> str:
         return self.space
 
 
 class SpaceApply(SpaceCore):
-    """A workspace for data models and instances. This is the write version"""
+    """A workspace for data models and instances. This is the write version
+
+    Args:
+        space (str): A unique identifier for space.
+        description (str): Textual description of the space
+        name (str): Human readable name for the space.
+    """
 
-    ...
+    def __init__(
+        self,
+        space: str,
+        description: str = None,
+        name: str = None,
+        **_: Any,
+    ):
+        validate_data_modeling_identifier(space)
+        super().__init__(space, description, name)
 
 
 class Space(SpaceCore):
     """A workspace for data models and instances. This is the read version.
 
     Args:
         space (str): a unique identifier for the space.
```

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_modeling/views.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_modeling/views.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -32,15 +32,14 @@
         version: str,
         description: str = None,
         name: str = None,
         filter: Filter | None = None,
         implements: list[ViewId] = None,
         **_: dict,
     ):
-        validate_data_modeling_identifier(space, external_id)
         self.space = space
         self.external_id = external_id
         self.description = description
         self.name = name
         self.filter = filter
         self.implements = implements
         self.version = version
@@ -93,14 +92,15 @@
         version: str,
         description: str = None,
         name: str = None,
         filter: Filter | None = None,
         implements: list[ViewId] = None,
         properties: dict[str, MappedPropertyApply | ConnectionDefinition] = None,
     ):
+        validate_data_modeling_identifier(space, external_id)
         super().__init__(space, external_id, version, description, name, filter, implements)
         self.properties = properties
 
     @classmethod
     def load(cls, resource: dict | str) -> ViewApply:
         data = json.loads(resource) if isinstance(resource, str) else resource
         if "properties" in data and isinstance(data["properties"], dict):
```

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/data_sets.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/data_sets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/datapoints.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/datapoints.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/events.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/events.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/extractionpipelines.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/extractionpipelines.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/files.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/files.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/functions.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/functions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/geospatial.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/geospatial.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/iam.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/iam.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/labels.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/labels.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/raw.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/raw.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/relationships.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/relationships.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/sequences.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/sequences.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/shared.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/shared.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/templates.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/templates.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/three_d.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/three_d.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/time_series.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/__init__.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/common.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/common.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/jobs.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/jobs.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/notifications.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/notifications.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/schedules.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/schedules.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/data_classes/transformations/schema.py` & `cognite_sdk-6.5.3/cognite/client/data_classes/transformations/schema.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/exceptions.py` & `cognite_sdk-6.5.3/cognite/client/exceptions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/testing.py` & `cognite_sdk-6.5.3/cognite/client/testing.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/__init__.py` & `cognite_sdk-6.5.3/cognite/client/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_auxiliary.py` & `cognite_sdk-6.5.3/cognite/client/utils/_auxiliary.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_concurrency.py` & `cognite_sdk-6.5.3/cognite/client/utils/_concurrency.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_graph.py` & `cognite_sdk-6.5.3/cognite/client/utils/_graph.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_identifier.py` & `cognite_sdk-6.5.3/cognite/client/utils/_identifier.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_logging.py` & `cognite_sdk-6.5.3/cognite/client/utils/_logging.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_pandas_helpers.py` & `cognite_sdk-6.5.3/cognite/client/utils/_pandas_helpers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_priority_tpe.py` & `cognite_sdk-6.5.3/cognite/client/utils/_priority_tpe.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_pyodide_helpers.py` & `cognite_sdk-6.5.3/cognite/client/utils/_pyodide_helpers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_text.py` & `cognite_sdk-6.5.3/cognite/client/utils/_text.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_time.py` & `cognite_sdk-6.5.3/cognite/client/utils/_time.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_validation.py` & `cognite_sdk-6.5.3/cognite/client/utils/_validation.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/cognite/client/utils/_version_checker.py` & `cognite_sdk-6.5.3/cognite/client/utils/_version_checker.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.2/pyproject.toml` & `cognite_sdk-6.5.3/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [tool.poetry]
 name = "cognite-sdk"
 
-version = "6.5.2"
+version = "6.5.3"
 
 description = "Cognite Python SDK"
 readme = "README.md"
 documentation = "https://cognite-sdk-python.readthedocs-hosted.com"
 authors = ["Erlend Vollset <erlend.vollset@cognite.com>"]
 license = "Apache-2.0"
```

### Comparing `cognite_sdk-6.5.2/PKG-INFO` & `cognite_sdk-6.5.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cognite-sdk
-Version: 6.5.2
+Version: 6.5.3
 Summary: Cognite Python SDK
 License: Apache-2.0
 Author: Erlend Vollset
 Author-email: erlend.vollset@cognite.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: cognite-sdk Version: 6.5.2 Summary: Cognite Python
+Metadata-Version: 2.1 Name: cognite-sdk Version: 6.5.3 Summary: Cognite Python
 SDK License: Apache-2.0 Author: Erlend Vollset Author-email:
 erlend.vollset@cognite.com Requires-Python: >=3.8,<4.0 Classifier: License ::
 OSI Approved :: Apache Software License Classifier: Programming Language ::
 Python :: 3 Classifier: Programming Language :: Python :: 3.8 Classifier:
 Programming Language :: Python :: 3.9 Classifier: Programming Language ::
 Python :: 3.10 Classifier: Programming Language :: Python :: 3.11 Provides-
 Extra: all Provides-Extra: functions Provides-Extra: geo Provides-Extra: numpy
```

