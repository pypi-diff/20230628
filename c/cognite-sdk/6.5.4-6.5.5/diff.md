# Comparing `tmp/cognite_sdk-6.5.4.tar.gz` & `tmp/cognite_sdk-6.5.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cognite_sdk-6.5.4.tar", max compression
+gzip compressed data, was "cognite_sdk-6.5.5.tar", max compression
```

## Comparing `cognite_sdk-6.5.4.tar` & `cognite_sdk-6.5.5.tar`

### file list

```diff
@@ -1,115 +1,115 @@
--rw-r--r--   0        0        0    11349 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/LICENSE
--rw-r--r--   0        0        0     3945 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/README.md
--rw-r--r--   0        0        0      574 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/__init__.py
--rw-r--r--   0        0        0        0 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/__init__.py
--rw-r--r--   0        0        0     7558 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/annotations.py
--rw-r--r--   0        0        0    49210 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/assets.py
--rw-r--r--   0        0        0     1157 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/__init__.py
--rw-r--r--   0        0        0     8056 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/containers.py
--rw-r--r--   0        0        0     9702 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/data_models.py
--rw-r--r--   0        0        0    37850 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/instances.py
--rw-r--r--   0        0        0     6699 2023-06-28 11:02:56.746840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/spaces.py
--rw-r--r--   0        0        0     8221 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/data_modeling/views.py
--rw-r--r--   0        0        0    11115 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/data_sets.py
--rw-r--r--   0        0        0    54681 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/datapoint_tasks.py
--rw-r--r--   0        0        0    87544 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/datapoints.py
--rw-r--r--   0        0        0    12424 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/diagrams.py
--rw-r--r--   0        0        0    12245 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/entity_matching.py
--rw-r--r--   0        0        0    21384 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/events.py
--rw-r--r--   0        0        0    17504 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/extractionpipelines.py
--rw-r--r--   0        0        0    41584 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/files.py
--rw-r--r--   0        0        0    45636 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/functions.py
--rw-r--r--   0        0        0    50175 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/geospatial.py
--rw-r--r--   0        0        0     9619 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/iam.py
--rw-r--r--   0        0        0     6088 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/labels.py
--rw-r--r--   0        0        0    24756 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/raw.py
--rw-r--r--   0        0        0    22919 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/relationships.py
--rw-r--r--   0        0        0    38200 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/sequences.py
--rw-r--r--   0        0        0     7936 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/synthetic_time_series.py
--rw-r--r--   0        0        0    32072 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/templates.py
--rw-r--r--   0        0        0    28258 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/three_d.py
--rw-r--r--   0        0        0    19276 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/time_series.py
--rw-r--r--   0        0        0    22021 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/transformations/__init__.py
--rw-r--r--   0        0        0     5083 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/transformations/jobs.py
--rw-r--r--   0        0        0     4691 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/transformations/notifications.py
--rw-r--r--   0        0        0     9705 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/transformations/schedules.py
--rw-r--r--   0        0        0     1881 2023-06-28 11:02:56.750840 cognite_sdk-6.5.4/cognite/client/_api/transformations/schema.py
--rw-r--r--   0        0        0     5910 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_api/vision.py
--rw-r--r--   0        0        0    38334 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_api_client.py
--rw-r--r--   0        0        0     5391 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_cognite_client.py
--rw-r--r--   0        0        0      215 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_constants.py
--rw-r--r--   0        0        0     6937 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_http_client.py
--rw-r--r--   0        0        0      553 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response.proto
--rw-r--r--   0        0        0     1985 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response_pb2.py
--rw-r--r--   0        0        0     3364 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response_pb2.pyi
--rw-r--r--   0        0        0      811 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_points.proto
--rw-r--r--   0        0        0     2495 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_points_pb2.py
--rw-r--r--   0        0        0     5321 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto/data_points_pb2.pyi
--rw-r--r--   0        0        0     9509 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_point_list_response_pb2.py
--rw-r--r--   0        0        0     3364 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi
--rw-r--r--   0        0        0    15421 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_points_pb2.py
--rw-r--r--   0        0        0     5321 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_points_pb2.pyi
--rw-r--r--   0        0        0       91 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/_version.py
--rw-r--r--   0        0        0      300 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/beta.py
--rw-r--r--   0        0        0     4508 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/config.py
--rw-r--r--   0        0        0    19252 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/credentials.py
--rw-r--r--   0        0        0     8794 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/__init__.py
--rw-r--r--   0        0        0    19074 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/_base.py
--rw-r--r--   0        0        0        0 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/annotation_types/__init__.py
--rw-r--r--   0        0        0     1595 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/annotation_types/images.py
--rw-r--r--   0        0        0     2936 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/annotation_types/primitives.py
--rw-r--r--   0        0        0     8753 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/annotations.py
--rw-r--r--   0        0        0    34185 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/assets.py
--rw-r--r--   0        0        0    33708 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/contextualization.py
--rw-r--r--   0        0        0     4087 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/__init__.py
--rw-r--r--   0        0        0     1224 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/_core.py
--rw-r--r--   0        0        0     1239 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/_validation.py
--rw-r--r--   0        0        0     5154 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/aggregations.py
--rw-r--r--   0        0        0    11348 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/containers.py
--rw-r--r--   0        0        0     7687 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/data_models.py
--rw-r--r--   0        0        0     4710 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/data_types.py
--rw-r--r--   0        0        0     9519 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/filters.py
--rw-r--r--   0        0        0     6593 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/ids.py
--rw-r--r--   0        0        0    30982 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/instances.py
--rw-r--r--   0        0        0     2944 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/spaces.py
--rw-r--r--   0        0        0    15081 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/views.py
--rw-r--r--   0        0        0     6691 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/data_sets.py
--rw-r--r--   0        0        0    33969 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/datapoints.py
--rw-r--r--   0        0        0    11015 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/events.py
--rw-r--r--   0        0        0    14376 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/extractionpipelines.py
--rw-r--r--   0        0        0    13671 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/files.py
--rw-r--r--   0        0        0    16695 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/functions.py
--rw-r--r--   0        0        0    16556 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/geospatial.py
--rw-r--r--   0        0        0     6349 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/iam.py
--rw-r--r--   0        0        0     5885 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/labels.py
--rw-r--r--   0        0        0     4120 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/raw.py
--rw-r--r--   0        0        0    12267 2023-06-28 11:02:56.754840 cognite_sdk-6.5.4/cognite/client/data_classes/relationships.py
--rw-r--r--   0        0        0    17675 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/sequences.py
--rw-r--r--   0        0        0     8699 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/shared.py
--rw-r--r--   0        0        0    16892 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/templates.py
--rw-r--r--   0        0        0    11855 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/three_d.py
--rw-r--r--   0        0        0    12090 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/time_series.py
--rw-r--r--   0        0        0    23040 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/__init__.py
--rw-r--r--   0        0        0    12116 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/common.py
--rw-r--r--   0        0        0    11469 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/jobs.py
--rw-r--r--   0        0        0     2382 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/notifications.py
--rw-r--r--   0        0        0     2475 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/schedules.py
--rw-r--r--   0        0        0     2770 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/data_classes/transformations/schema.py
--rw-r--r--   0        0        0     9383 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/exceptions.py
--rw-r--r--   0        0        0        0 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/py.typed
--rw-r--r--   0        0        0     9006 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/testing.py
--rw-r--r--   0        0        0      534 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/__init__.py
--rw-r--r--   0        0        0     8165 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_auxiliary.py
--rw-r--r--   0        0        0     9853 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_concurrency.py
--rw-r--r--   0        0        0     1396 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_graph.py
--rw-r--r--   0        0        0     7684 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_identifier.py
--rw-r--r--   0        0        0     2134 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_logging.py
--rw-r--r--   0        0        0     3548 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_pandas_helpers.py
--rw-r--r--   0        0        0     6188 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_priority_tpe.py
--rw-r--r--   0        0        0     4260 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_pyodide_helpers.py
--rw-r--r--   0        0        0     2981 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_text.py
--rw-r--r--   0        0        0    24536 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_time.py
--rw-r--r--   0        0        0     1820 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_validation.py
--rw-r--r--   0        0        0     3341 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/cognite/client/utils/_version_checker.py
--rw-r--r--   0        0        0     2151 2023-06-28 11:02:56.758840 cognite_sdk-6.5.4/pyproject.toml
--rw-r--r--   0        0        0     5625 1970-01-01 00:00:00.000000 cognite_sdk-6.5.4/PKG-INFO
+-rw-r--r--   0        0        0    11349 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/LICENSE
+-rw-r--r--   0        0        0     3945 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/README.md
+-rw-r--r--   0        0        0      574 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/__init__.py
+-rw-r--r--   0        0        0     7558 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/annotations.py
+-rw-r--r--   0        0        0    49210 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/assets.py
+-rw-r--r--   0        0        0     1157 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/__init__.py
+-rw-r--r--   0        0        0     8056 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/containers.py
+-rw-r--r--   0        0        0     9702 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/data_models.py
+-rw-r--r--   0        0        0    37850 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/instances.py
+-rw-r--r--   0        0        0     6620 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/spaces.py
+-rw-r--r--   0        0        0     8221 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_modeling/views.py
+-rw-r--r--   0        0        0    11115 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/data_sets.py
+-rw-r--r--   0        0        0    54681 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/datapoint_tasks.py
+-rw-r--r--   0        0        0    87544 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/datapoints.py
+-rw-r--r--   0        0        0    12424 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/diagrams.py
+-rw-r--r--   0        0        0    12245 2023-06-28 12:07:36.817034 cognite_sdk-6.5.5/cognite/client/_api/entity_matching.py
+-rw-r--r--   0        0        0    21384 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/events.py
+-rw-r--r--   0        0        0    17504 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/extractionpipelines.py
+-rw-r--r--   0        0        0    41590 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/files.py
+-rw-r--r--   0        0        0    45636 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/functions.py
+-rw-r--r--   0        0        0    50175 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/geospatial.py
+-rw-r--r--   0        0        0     9619 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/iam.py
+-rw-r--r--   0        0        0     6088 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/labels.py
+-rw-r--r--   0        0        0    24756 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/raw.py
+-rw-r--r--   0        0        0    22919 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/relationships.py
+-rw-r--r--   0        0        0    38200 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/sequences.py
+-rw-r--r--   0        0        0     7936 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/synthetic_time_series.py
+-rw-r--r--   0        0        0    32072 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/templates.py
+-rw-r--r--   0        0        0    28258 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/three_d.py
+-rw-r--r--   0        0        0    19276 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/time_series.py
+-rw-r--r--   0        0        0    22021 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/transformations/__init__.py
+-rw-r--r--   0        0        0     5083 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/transformations/jobs.py
+-rw-r--r--   0        0        0     4691 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/transformations/notifications.py
+-rw-r--r--   0        0        0     9705 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/transformations/schedules.py
+-rw-r--r--   0        0        0     1881 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/transformations/schema.py
+-rw-r--r--   0        0        0     5910 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api/vision.py
+-rw-r--r--   0        0        0    38337 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_api_client.py
+-rw-r--r--   0        0        0     5391 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_cognite_client.py
+-rw-r--r--   0        0        0      215 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_constants.py
+-rw-r--r--   0        0        0     6937 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_http_client.py
+-rw-r--r--   0        0        0      553 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response.proto
+-rw-r--r--   0        0        0     1985 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response_pb2.py
+-rw-r--r--   0        0        0     3364 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response_pb2.pyi
+-rw-r--r--   0        0        0      811 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_points.proto
+-rw-r--r--   0        0        0     2495 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_points_pb2.py
+-rw-r--r--   0        0        0     5321 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto/data_points_pb2.pyi
+-rw-r--r--   0        0        0     9509 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_point_list_response_pb2.py
+-rw-r--r--   0        0        0     3364 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi
+-rw-r--r--   0        0        0    15421 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_points_pb2.py
+-rw-r--r--   0        0        0     5321 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_points_pb2.pyi
+-rw-r--r--   0        0        0       91 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/_version.py
+-rw-r--r--   0        0        0      300 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/beta.py
+-rw-r--r--   0        0        0     4508 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/config.py
+-rw-r--r--   0        0        0    19252 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/credentials.py
+-rw-r--r--   0        0        0     8794 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/__init__.py
+-rw-r--r--   0        0        0    19074 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/_base.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/annotation_types/__init__.py
+-rw-r--r--   0        0        0     1595 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/annotation_types/images.py
+-rw-r--r--   0        0        0     2936 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/annotation_types/primitives.py
+-rw-r--r--   0        0        0     8753 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/annotations.py
+-rw-r--r--   0        0        0    34185 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/assets.py
+-rw-r--r--   0        0        0    33708 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/contextualization.py
+-rw-r--r--   0        0        0     4087 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/__init__.py
+-rw-r--r--   0        0        0     1224 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/_core.py
+-rw-r--r--   0        0        0     1239 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/_validation.py
+-rw-r--r--   0        0        0     5154 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/aggregations.py
+-rw-r--r--   0        0        0    11348 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/containers.py
+-rw-r--r--   0        0        0     7670 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/data_models.py
+-rw-r--r--   0        0        0     4710 2023-06-28 12:07:36.821033 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/data_types.py
+-rw-r--r--   0        0        0     9519 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/filters.py
+-rw-r--r--   0        0        0     6968 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/ids.py
+-rw-r--r--   0        0        0    30982 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/instances.py
+-rw-r--r--   0        0        0     2944 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/spaces.py
+-rw-r--r--   0        0        0    15081 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/views.py
+-rw-r--r--   0        0        0     6691 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/data_sets.py
+-rw-r--r--   0        0        0    33969 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/datapoints.py
+-rw-r--r--   0        0        0    11015 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/events.py
+-rw-r--r--   0        0        0    14376 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/extractionpipelines.py
+-rw-r--r--   0        0        0    13671 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/files.py
+-rw-r--r--   0        0        0    16695 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/functions.py
+-rw-r--r--   0        0        0    16556 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/geospatial.py
+-rw-r--r--   0        0        0     6349 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/iam.py
+-rw-r--r--   0        0        0     5885 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/labels.py
+-rw-r--r--   0        0        0     4120 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/raw.py
+-rw-r--r--   0        0        0    12267 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/relationships.py
+-rw-r--r--   0        0        0    17675 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/sequences.py
+-rw-r--r--   0        0        0     8699 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/shared.py
+-rw-r--r--   0        0        0    16892 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/templates.py
+-rw-r--r--   0        0        0    11855 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/three_d.py
+-rw-r--r--   0        0        0    12090 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/time_series.py
+-rw-r--r--   0        0        0    23040 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/__init__.py
+-rw-r--r--   0        0        0    12116 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/common.py
+-rw-r--r--   0        0        0    11469 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/jobs.py
+-rw-r--r--   0        0        0     2382 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/notifications.py
+-rw-r--r--   0        0        0     2475 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/schedules.py
+-rw-r--r--   0        0        0     2770 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/data_classes/transformations/schema.py
+-rw-r--r--   0        0        0     9383 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/exceptions.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/py.typed
+-rw-r--r--   0        0        0     9006 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/testing.py
+-rw-r--r--   0        0        0      534 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/__init__.py
+-rw-r--r--   0        0        0     7559 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_auxiliary.py
+-rw-r--r--   0        0        0     9853 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_concurrency.py
+-rw-r--r--   0        0        0     1396 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_graph.py
+-rw-r--r--   0        0        0     7748 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_identifier.py
+-rw-r--r--   0        0        0     2134 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_logging.py
+-rw-r--r--   0        0        0     3548 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_pandas_helpers.py
+-rw-r--r--   0        0        0     6188 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_priority_tpe.py
+-rw-r--r--   0        0        0     4260 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_pyodide_helpers.py
+-rw-r--r--   0        0        0     2981 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_text.py
+-rw-r--r--   0        0        0    24536 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_time.py
+-rw-r--r--   0        0        0     1820 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_validation.py
+-rw-r--r--   0        0        0     3341 2023-06-28 12:07:36.825032 cognite_sdk-6.5.5/cognite/client/utils/_version_checker.py
+-rw-r--r--   0        0        0     2151 2023-06-28 12:07:36.829031 cognite_sdk-6.5.5/pyproject.toml
+-rw-r--r--   0        0        0     5625 1970-01-01 00:00:00.000000 cognite_sdk-6.5.5/PKG-INFO
```

### Comparing `cognite_sdk-6.5.4/LICENSE` & `cognite_sdk-6.5.5/LICENSE`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/README.md` & `cognite_sdk-6.5.5/README.md`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/__init__.py` & `cognite_sdk-6.5.5/cognite/client/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/annotations.py` & `cognite_sdk-6.5.5/cognite/client/_api/annotations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/assets.py` & `cognite_sdk-6.5.5/cognite/client/_api/assets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/__init__.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/containers.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/containers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/data_models.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/data_models.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/instances.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/instances.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/spaces.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/spaces.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from __future__ import annotations
 
 from typing import Iterator, Sequence, cast, overload
 
 from cognite.client._api_client import APIClient
 from cognite.client._constants import LIST_LIMIT_DEFAULT
+from cognite.client.data_classes.data_modeling.ids import _load_space_identifier
 from cognite.client.data_classes.data_modeling.spaces import Space, SpaceApply, SpaceList
-from cognite.client.utils._identifier import DataModelingIdentifierSequence
 
 
 class SpacesAPI(APIClient):
     _RESOURCE_PATH = "/models/spaces"
 
     @overload
     def __call__(
@@ -87,15 +87,15 @@
          Get multiple spaces by id:
 
                 >>> from cognite.client import CogniteClient
                 >>> c = CogniteClient()
                 >>> res = c.data_modeling.spaces.retrieve(spaces=["MySpace", "MyAwesomeSpace", "MyOtherSpace"])
 
         """
-        identifier = DataModelingIdentifierSequence.load_spaces(spaces=space)
+        identifier = _load_space_identifier(space)
         return self._retrieve_multiple(list_cls=SpaceList, resource_cls=Space, identifiers=identifier)
 
     def delete(self, space: str | Sequence[str]) -> list[str]:
         """`Delete one or more spaces <https://developer.cognite.com/api#tag/Spaces/operation/deleteSpacesV3>`_
 
         Args:
             space (str | Sequence[str]): ID or ID list ids of spaces.
@@ -107,17 +107,15 @@
 
                 >>> from cognite.client import CogniteClient
                 >>> c = CogniteClient()
                 >>> c.data_modeling.spaces.delete(space=["mySpace", "myOtherSpace"])
         """
         deleted_spaces = cast(
             list,
-            self._delete_multiple(
-                identifiers=DataModelingIdentifierSequence.load_spaces(spaces=space), wrap_ids=True, returns_items=True
-            ),
+            self._delete_multiple(identifiers=_load_space_identifier(space), wrap_ids=True, returns_items=True),
         )
         return [item["space"] for item in deleted_spaces]
 
     def list(
         self,
         limit: int = LIST_LIMIT_DEFAULT,
         include_global: bool = False,
```

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_modeling/views.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_modeling/views.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/data_sets.py` & `cognite_sdk-6.5.5/cognite/client/_api/data_sets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/datapoint_tasks.py` & `cognite_sdk-6.5.5/cognite/client/_api/datapoint_tasks.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/datapoints.py` & `cognite_sdk-6.5.5/cognite/client/_api/datapoints.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/diagrams.py` & `cognite_sdk-6.5.5/cognite/client/_api/diagrams.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/entity_matching.py` & `cognite_sdk-6.5.5/cognite/client/_api/entity_matching.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/events.py` & `cognite_sdk-6.5.5/cognite/client/_api/events.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/extractionpipelines.py` & `cognite_sdk-6.5.5/cognite/client/_api/extractionpipelines.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/files.py` & `cognite_sdk-6.5.5/cognite/client/_api/files.py`

 * *Files 1% similar despite different names*

```diff
@@ -793,30 +793,30 @@
         id_to_metadata: Dict[Union[str, int], FileMetadata],
     ) -> None:
         tasks = [(directory, id, id_to_metadata) for id in all_ids]
         tasks_summary = utils._concurrency.execute_tasks(
             self._process_file_download, tasks, max_workers=self._config.max_workers
         )
         tasks_summary.raise_compound_exception_if_failed_tasks(
-            task_unwrap_fn=lambda task: id_to_metadata[utils._auxiliary.unwrap_identifer(task[1])],
+            task_unwrap_fn=lambda task: id_to_metadata[IdentifierSequence.unwrap_identifier(task[1])],
             str_format_element_fn=lambda metadata: metadata.id,
         )
 
     def _get_download_link(self, identifier: Dict[str, Union[int, str]]) -> str:
         return self._post(url_path="/files/downloadlink", json={"items": [identifier]}).json()["items"][0][
             "downloadUrl"
         ]
 
     def _process_file_download(
         self,
         directory: Path,
         identifier: Dict[str, Union[int, str]],
         id_to_metadata: Dict[Union[str, int], FileMetadata],
     ) -> None:
-        id = utils._auxiliary.unwrap_identifer(identifier)
+        id = IdentifierSequence.unwrap_identifier(identifier)
         file_metadata = id_to_metadata[id]
         file_path = (directory / cast(str, file_metadata.name)).resolve()
         file_is_in_download_directory = directory.resolve() in file_path.parents
         if not file_is_in_download_directory:
             raise RuntimeError(f"Resolved file path '{file_path}' is not inside download directory")
         download_link = self._get_download_link(identifier)
         self._download_file_to_path(download_link, file_path)
```

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/functions.py` & `cognite_sdk-6.5.5/cognite/client/_api/functions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/geospatial.py` & `cognite_sdk-6.5.5/cognite/client/_api/geospatial.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/iam.py` & `cognite_sdk-6.5.5/cognite/client/_api/iam.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/labels.py` & `cognite_sdk-6.5.5/cognite/client/_api/labels.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/raw.py` & `cognite_sdk-6.5.5/cognite/client/_api/raw.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/relationships.py` & `cognite_sdk-6.5.5/cognite/client/_api/relationships.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/sequences.py` & `cognite_sdk-6.5.5/cognite/client/_api/sequences.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/synthetic_time_series.py` & `cognite_sdk-6.5.5/cognite/client/_api/synthetic_time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/templates.py` & `cognite_sdk-6.5.5/cognite/client/_api/templates.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/three_d.py` & `cognite_sdk-6.5.5/cognite/client/_api/three_d.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/time_series.py` & `cognite_sdk-6.5.5/cognite/client/_api/time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/transformations/__init__.py` & `cognite_sdk-6.5.5/cognite/client/_api/transformations/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/transformations/jobs.py` & `cognite_sdk-6.5.5/cognite/client/_api/transformations/jobs.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/transformations/notifications.py` & `cognite_sdk-6.5.5/cognite/client/_api/transformations/notifications.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/transformations/schedules.py` & `cognite_sdk-6.5.5/cognite/client/_api/transformations/schedules.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/transformations/schema.py` & `cognite_sdk-6.5.5/cognite/client/_api/transformations/schema.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api/vision.py` & `cognite_sdk-6.5.5/cognite/client/_api/vision.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_api_client.py` & `cognite_sdk-6.5.5/cognite/client/_api_client.py`

 * *Files 1% similar despite different names*

```diff
@@ -700,15 +700,15 @@
                 "headers": headers,
             }
             for chunk in identifiers.chunked(self._DELETE_LIMIT)
         ]
         summary = utils._concurrency.execute_tasks(self._post, tasks, max_workers=self._config.max_workers)
         summary.raise_compound_exception_if_failed_tasks(
             task_unwrap_fn=lambda task: task["json"]["items"],
-            task_list_element_unwrap_fn=utils._auxiliary.unwrap_identifer,
+            task_list_element_unwrap_fn=identifiers.unwrap_identifier,
         )
         if returns_items:
             return summary.joined_results(lambda res: res.json()["items"])
         else:
             return None
 
     @overload
@@ -771,15 +771,15 @@
             {"url_path": resource_path + "/update", "json": {"items": chunk}, "params": params, "headers": headers}
             for chunk in patch_object_chunks
         ]
 
         tasks_summary = utils._concurrency.execute_tasks(self._post, tasks, max_workers=self._config.max_workers)
         tasks_summary.raise_compound_exception_if_failed_tasks(
             task_unwrap_fn=lambda task: task["json"]["items"],
-            task_list_element_unwrap_fn=lambda el: utils._auxiliary.unwrap_identifer(el),
+            task_list_element_unwrap_fn=lambda el: IdentifierSequenceCore.unwrap_identifier(el),
         )
         updated_items = tasks_summary.joined_results(lambda res: res.json()["items"])
 
         if single_item:
             return resource_cls._load(updated_items[0], cognite_client=self._cognite_client)
         return list_cls._load(updated_items, cognite_client=self._cognite_client)
```

### Comparing `cognite_sdk-6.5.4/cognite/client/_cognite_client.py` & `cognite_sdk-6.5.5/cognite/client/_cognite_client.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_http_client.py` & `cognite_sdk-6.5.5/cognite/client/_http_client.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response.proto` & `cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response.proto`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response_pb2.py` & `cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_point_list_response_pb2.pyi` & `cognite_sdk-6.5.5/cognite/client/_proto/data_point_list_response_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_points.proto` & `cognite_sdk-6.5.5/cognite/client/_proto/data_points.proto`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_points_pb2.py` & `cognite_sdk-6.5.5/cognite/client/_proto/data_points_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto/data_points_pb2.pyi` & `cognite_sdk-6.5.5/cognite/client/_proto/data_points_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_point_list_response_pb2.py` & `cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_point_list_response_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi` & `cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_point_list_response_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_points_pb2.py` & `cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_points_pb2.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/_proto_legacy/data_points_pb2.pyi` & `cognite_sdk-6.5.5/cognite/client/_proto_legacy/data_points_pb2.pyi`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/config.py` & `cognite_sdk-6.5.5/cognite/client/config.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/credentials.py` & `cognite_sdk-6.5.5/cognite/client/credentials.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/__init__.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/_base.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/_base.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/annotation_types/images.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/annotation_types/images.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/annotation_types/primitives.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/annotation_types/primitives.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/annotations.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/annotations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/assets.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/assets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/contextualization.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/contextualization.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/__init__.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/_core.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/_core.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/_validation.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/_validation.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/aggregations.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/aggregations.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/containers.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/containers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/data_models.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/data_models.py`

 * *Files 0% similar despite different names*

```diff
@@ -172,15 +172,15 @@
         )
 
 
 class DataModelApplyList(CogniteResourceList[DataModelApply]):
     _RESOURCE = DataModelApply
 
 
-class DataModelList(Generic[T_View], CogniteResourceList[DataModel[T_View]]):
+class DataModelList(CogniteResourceList[DataModel[T_View]]):
     _RESOURCE = DataModel
 
     def to_data_model_apply_list(self) -> DataModelApplyList:
         return DataModelApplyList(resources=[d.as_apply() for d in self.items])
 
 
 class DataModelFilter(CogniteFilter):
```

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/data_types.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/data_types.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/filters.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/filters.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/ids.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/ids.py`

 * *Files 9% similar despite different names*

```diff
@@ -147,16 +147,24 @@
 DataModelIdentifier = Union[DataModelId, Tuple[str, str], Tuple[str, str, str]]
 NodeIdentifier = Union[NodeId, Tuple[str, str, str]]
 EdgeIdentifier = Union[EdgeId, Tuple[str, str, str]]
 
 Id = Union[Tuple[str, str], Tuple[str, str, str], DataModelingId, VersionedDataModelingId, NodeId, EdgeId, InstanceId]
 
 
+def _load_space_identifier(ids: str | Sequence[str]) -> DataModelingIdentifierSequence:
+    is_sequence = isinstance(ids, Sequence) and not isinstance(ids, str)
+    spaces = [ids] if isinstance(ids, str) else ids
+    return DataModelingIdentifierSequence(
+        identifiers=[DataModelingIdentifier(space) for space in spaces], is_singleton=not is_sequence
+    )
+
+
 def _load_identifier(
-    ids: Id | Sequence[Id], id_type: Literal["container", "view", "data_model", "node", "edge"]
+    ids: Id | Sequence[Id], id_type: Literal["container", "view", "data_model", "space", "node", "edge"]
 ) -> DataModelingIdentifierSequence:
     is_sequence = isinstance(ids, Sequence) and not (isinstance(ids, tuple) and isinstance(ids[0], str))
     is_view_or_data_model = id_type in {"view", "data_model"}
     is_instance = id_type in {"node", "edge"}
     id_list = cast(Sequence, ids)
     if not is_sequence:
         id_list = [ids]
```

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/instances.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/instances.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/spaces.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/spaces.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_modeling/views.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_modeling/views.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/data_sets.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/data_sets.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/datapoints.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/datapoints.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/events.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/events.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/extractionpipelines.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/extractionpipelines.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/files.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/files.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/functions.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/functions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/geospatial.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/geospatial.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/iam.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/iam.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/labels.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/labels.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/raw.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/raw.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/relationships.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/relationships.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/sequences.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/sequences.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/shared.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/shared.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/templates.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/templates.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/three_d.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/three_d.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/time_series.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/time_series.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/__init__.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/common.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/common.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/jobs.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/jobs.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/notifications.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/notifications.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/schedules.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/schedules.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/data_classes/transformations/schema.py` & `cognite_sdk-6.5.5/cognite/client/data_classes/transformations/schema.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/exceptions.py` & `cognite_sdk-6.5.5/cognite/client/exceptions.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/testing.py` & `cognite_sdk-6.5.5/cognite/client/testing.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/__init__.py` & `cognite_sdk-6.5.5/cognite/client/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_auxiliary.py` & `cognite_sdk-6.5.5/cognite/client/utils/_auxiliary.py`

 * *Files 8% similar despite different names*

```diff
@@ -89,40 +89,14 @@
     if isinstance(x, (Decimal, numbers.Real)):
         return float(x)
     if hasattr(x, "__dict__"):
         return x.__dict__
     raise TypeError(f"Object {x} of type {x.__class__} can't be serialized by the JSON encoder")
 
 
-@overload
-def unwrap_identifer(identifier: str) -> str:
-    ...
-
-
-@overload
-def unwrap_identifer(identifier: int) -> int:
-    ...
-
-
-@overload
-def unwrap_identifer(identifier: Dict) -> Union[str, int]:
-    ...
-
-
-def unwrap_identifer(identifier: Union[str, int, Dict]) -> Union[str, int]:
-    # TODO: Move to Identifier class?
-    if isinstance(identifier, (str, int)):
-        return identifier
-    if "externalId" in identifier:
-        return identifier["externalId"]
-    if "id" in identifier:
-        return identifier["id"]
-    raise ValueError(f"{identifier} does not contain 'id' or 'externalId'")
-
-
 def assert_type(var: Any, var_name: str, types: List[type], allow_none: bool = False) -> None:
     if var is None:
         if not allow_none:
             raise TypeError(f"{var_name} cannot be None")
     elif not isinstance(var, tuple(types)):
         raise TypeError(f"{var_name!r} must be one of types {types}, not {type(var)}")
```

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_concurrency.py` & `cognite_sdk-6.5.5/cognite/client/utils/_concurrency.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_graph.py` & `cognite_sdk-6.5.5/cognite/client/utils/_graph.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_identifier.py` & `cognite_sdk-6.5.5/cognite/client/utils/_identifier.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 from __future__ import annotations
 
 import numbers
+from abc import ABC
 from typing import (
     Dict,
     Generic,
     Iterable,
     List,
     Literal,
     NoReturn,
@@ -113,20 +114,18 @@
 class InternalId(Identifier[int]):
     ...
 
 
 T_Identifier = TypeVar("T_Identifier", bound=IdentifierCore)
 
 
-class IdentifierSequenceCore(Generic[T_Identifier]):
-    _no_identifiers_error_message: str = ""
-
+class IdentifierSequenceCore(Generic[T_Identifier], ABC):
     def __init__(self, identifiers: List[T_Identifier], is_singleton: bool) -> None:
         if not identifiers:
-            raise ValueError(self._no_identifiers_error_message)
+            raise ValueError("No identifiers specified")
         self._identifiers = identifiers
         self.__is_singleton = is_singleton
 
     def __len__(self) -> int:
         return len(self._identifiers)
 
     def __getitem__(self, item: int) -> T_Identifier:
@@ -154,18 +153,28 @@
 
     def as_primitives(self) -> list[int | str]:
         return [identifier.as_primitive() for identifier in self._identifiers]
 
     def are_unique(self) -> bool:
         return len(self) == len(set(self.as_primitives()))
 
+    @staticmethod
+    def unwrap_identifier(identifier: Union[str, int, Dict]) -> Union[str, int]:
+        if isinstance(identifier, (str, int)):
+            return identifier
+        if "externalId" in identifier:
+            return identifier["externalId"]
+        if "id" in identifier:
+            return identifier["id"]
+        if "space" in identifier:
+            return identifier["space"]
+        raise ValueError(f"{identifier} does not contain 'id' or 'externalId' or 'space'")
 
-class IdentifierSequence(IdentifierSequenceCore[Identifier]):
-    _no_identifiers_error_message = "No ids or external_ids specified"
 
+class IdentifierSequence(IdentifierSequenceCore[Identifier]):
     @overload
     @classmethod
     def of(cls, *ids: List[Union[int, str]]) -> IdentifierSequence:
         ...
 
     @overload
     @classmethod
@@ -212,19 +221,13 @@
                     f"{id_name}external_ids must be of type str or Sequence[str]. Found {type(external_ids)}"
                 )
 
         is_singleton = value_passed_as_primitive and len(all_identifiers) == 1
         return cls(identifiers=[Identifier(val) for val in all_identifiers], is_singleton=is_singleton)
 
 
-class DataModelingIdentifierSequence(IdentifierSequenceCore[DataModelingIdentifier]):
-    _no_identifiers_error_message = "No spaces specified."
-
-    @classmethod
-    def load_spaces(cls, spaces: str | Sequence[str]) -> DataModelingIdentifierSequence:
-        spaces = [spaces] if isinstance(spaces, str) else spaces
-
-        return cls(identifiers=[DataModelingIdentifier(space) for space in spaces], is_singleton=len(spaces) == 1)
+class SingletonIdentifierSequence(IdentifierSequenceCore[Identifier]):
+    ...
 
 
-class SingletonIdentifierSequence(IdentifierSequenceCore):
+class DataModelingIdentifierSequence(IdentifierSequenceCore[DataModelingIdentifier]):
     ...
```

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_logging.py` & `cognite_sdk-6.5.5/cognite/client/utils/_logging.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_pandas_helpers.py` & `cognite_sdk-6.5.5/cognite/client/utils/_pandas_helpers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_priority_tpe.py` & `cognite_sdk-6.5.5/cognite/client/utils/_priority_tpe.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_pyodide_helpers.py` & `cognite_sdk-6.5.5/cognite/client/utils/_pyodide_helpers.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_text.py` & `cognite_sdk-6.5.5/cognite/client/utils/_text.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_time.py` & `cognite_sdk-6.5.5/cognite/client/utils/_time.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_validation.py` & `cognite_sdk-6.5.5/cognite/client/utils/_validation.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/cognite/client/utils/_version_checker.py` & `cognite_sdk-6.5.5/cognite/client/utils/_version_checker.py`

 * *Files identical despite different names*

### Comparing `cognite_sdk-6.5.4/pyproject.toml` & `cognite_sdk-6.5.5/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [tool.poetry]
 name = "cognite-sdk"
 
-version = "6.5.4"
+version = "6.5.5"
 
 description = "Cognite Python SDK"
 readme = "README.md"
 documentation = "https://cognite-sdk-python.readthedocs-hosted.com"
 authors = ["Erlend Vollset <erlend.vollset@cognite.com>"]
 license = "Apache-2.0"
```

### Comparing `cognite_sdk-6.5.4/PKG-INFO` & `cognite_sdk-6.5.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cognite-sdk
-Version: 6.5.4
+Version: 6.5.5
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
-Metadata-Version: 2.1 Name: cognite-sdk Version: 6.5.4 Summary: Cognite Python
+Metadata-Version: 2.1 Name: cognite-sdk Version: 6.5.5 Summary: Cognite Python
 SDK License: Apache-2.0 Author: Erlend Vollset Author-email:
 erlend.vollset@cognite.com Requires-Python: >=3.8,<4.0 Classifier: License ::
 OSI Approved :: Apache Software License Classifier: Programming Language ::
 Python :: 3 Classifier: Programming Language :: Python :: 3.8 Classifier:
 Programming Language :: Python :: 3.9 Classifier: Programming Language ::
 Python :: 3.10 Classifier: Programming Language :: Python :: 3.11 Provides-
 Extra: all Provides-Extra: functions Provides-Extra: geo Provides-Extra: numpy
```

